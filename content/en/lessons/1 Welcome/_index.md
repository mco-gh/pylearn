---
title: "1 Course Overview, Background, and Getting Started"
linkTitle: "1 Welcome"
weight: "1"
---
<!DOCTYPE html>

<html lang="en">
<head><meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>1_Welcome</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<style type="text/css">
    pre { line-height: 125%; }
td.linenos .normal { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
span.linenos { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
td.linenos .special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
.highlight .hll { background-color: var(--jp-cell-editor-active-background) }
.highlight { background: var(--jp-cell-editor-background); color: var(--jp-mirror-editor-variable-color) }
.highlight .c { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment */
.highlight .err { color: var(--jp-mirror-editor-error-color) } /* Error */
.highlight .k { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword */
.highlight .o { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator */
.highlight .p { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation */
.highlight .ch { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Multiline */
.highlight .cp { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Preproc */
.highlight .cpf { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Single */
.highlight .cs { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Special */
.highlight .kc { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Pseudo */
.highlight .kr { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Type */
.highlight .m { color: var(--jp-mirror-editor-number-color) } /* Literal.Number */
.highlight .s { color: var(--jp-mirror-editor-string-color) } /* Literal.String */
.highlight .ow { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator.Word */
.highlight .pm { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation.Marker */
.highlight .w { color: var(--jp-mirror-editor-variable-color) } /* Text.Whitespace */
.highlight .mb { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Bin */
.highlight .mf { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Float */
.highlight .mh { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Hex */
.highlight .mi { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer */
.highlight .mo { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Oct */
.highlight .sa { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Affix */
.highlight .sb { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Backtick */
.highlight .sc { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Char */
.highlight .dl { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Delimiter */
.highlight .sd { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Doc */
.highlight .s2 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Double */
.highlight .se { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Escape */
.highlight .sh { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Heredoc */
.highlight .si { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Interpol */
.highlight .sx { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Other */
.highlight .sr { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Regex */
.highlight .s1 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Single */
.highlight .ss { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Symbol */
.highlight .il { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer.Long */
  </style>
<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
 * Mozilla scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */
[data-jp-theme-scrollbars='true'] {
  scrollbar-color: rgb(var(--jp-scrollbar-thumb-color))
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar. These selectors
 * will match lower in the tree, and so will override the above */
[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
}

/* tiny scrollbar */

.jp-scrollbar-tiny {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
  scrollbar-width: thin;
}

/* tiny scrollbar */

.jp-scrollbar-tiny::-webkit-scrollbar,
.jp-scrollbar-tiny::-webkit-scrollbar-corner {
  background-color: transparent;
  height: 4px;
  width: 4px;
}

.jp-scrollbar-tiny::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:horizontal {
  border-left: 0 solid transparent;
  border-right: 0 solid transparent;
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:vertical {
  border-top: 0 solid transparent;
  border-bottom: 0 solid transparent;
}

/*
 * Lumino
 */

.lm-ScrollBar[data-orientation='horizontal'] {
  min-height: 16px;
  max-height: 16px;
  min-width: 45px;
  border-top: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] {
  min-width: 16px;
  max-width: 16px;
  min-height: 45px;
  border-left: 1px solid #a0a0a0;
}

.lm-ScrollBar-button {
  background-color: #f0f0f0;
  background-position: center center;
  min-height: 15px;
  max-height: 15px;
  min-width: 15px;
  max-width: 15px;
}

.lm-ScrollBar-button:hover {
  background-color: #dadada;
}

.lm-ScrollBar-button.lm-mod-active {
  background-color: #cdcdcd;
}

.lm-ScrollBar-track {
  background: #f0f0f0;
}

.lm-ScrollBar-thumb {
  background: #cdcdcd;
}

.lm-ScrollBar-thumb:hover {
  background: #bababa;
}

.lm-ScrollBar-thumb.lm-mod-active {
  background: #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal'] .lm-ScrollBar-thumb {
  height: 100%;
  min-width: 15px;
  border-left: 1px solid #a0a0a0;
  border-right: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] .lm-ScrollBar-thumb {
  width: 100%;
  min-height: 15px;
  border-top: 1px solid #a0a0a0;
  border-bottom: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-left);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-right);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-up);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-down);
  background-size: 17px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-Widget {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
}

.lm-Widget.lm-mod-hidden {
  display: none !important;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.lm-AccordionPanel[data-orientation='horizontal'] > .lm-AccordionPanel-title {
  /* Title is rotated for horizontal accordion panel using CSS */
  display: block;
  transform-origin: top left;
  transform: rotate(-90deg) translate(-100%);
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  display: flex;
  flex-direction: column;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-CommandPalette-search {
  flex: 0 0 auto;
}

.lm-CommandPalette-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  min-height: 0;
  overflow: auto;
  list-style-type: none;
}

.lm-CommandPalette-header {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-CommandPalette-item {
  display: flex;
  flex-direction: row;
}

.lm-CommandPalette-itemIcon {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemContent {
  flex: 1 1 auto;
  overflow: hidden;
}

.lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemLabel {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-close-icon {
  border: 1px solid transparent;
  background-color: transparent;
  position: absolute;
  z-index: 1;
  right: 3%;
  top: 0;
  bottom: 0;
  margin: auto;
  padding: 7px 0;
  display: none;
  vertical-align: middle;
  outline: 0;
  cursor: pointer;
}
.lm-close-icon:after {
  content: 'X';
  display: block;
  width: 15px;
  height: 15px;
  text-align: center;
  color: #000;
  font-weight: normal;
  font-size: 12px;
  cursor: pointer;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-DockPanel {
  z-index: 0;
}

.lm-DockPanel-widget {
  z-index: 0;
}

.lm-DockPanel-tabBar {
  z-index: 1;
}

.lm-DockPanel-handle {
  z-index: 2;
}

.lm-DockPanel-handle.lm-mod-hidden {
  display: none !important;
}

.lm-DockPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}

.lm-DockPanel-handle[data-orientation='horizontal'] {
  cursor: ew-resize;
}

.lm-DockPanel-handle[data-orientation='vertical'] {
  cursor: ns-resize;
}

.lm-DockPanel-handle[data-orientation='horizontal']:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}

.lm-DockPanel-handle[data-orientation='vertical']:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

.lm-DockPanel-overlay {
  z-index: 3;
  box-sizing: border-box;
  pointer-events: none;
}

.lm-DockPanel-overlay.lm-mod-hidden {
  display: none !important;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-Menu {
  z-index: 10000;
  position: absolute;
  white-space: nowrap;
  overflow-x: hidden;
  overflow-y: auto;
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-Menu-content {
  margin: 0;
  padding: 0;
  display: table;
  list-style-type: none;
}

.lm-Menu-item {
  display: table-row;
}

.lm-Menu-item.lm-mod-hidden,
.lm-Menu-item.lm-mod-collapsed {
  display: none !important;
}

.lm-Menu-itemIcon,
.lm-Menu-itemSubmenuIcon {
  display: table-cell;
  text-align: center;
}

.lm-Menu-itemLabel {
  display: table-cell;
  text-align: left;
}

.lm-Menu-itemShortcut {
  display: table-cell;
  text-align: right;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-MenuBar {
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-MenuBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: row;
  list-style-type: none;
}

.lm-MenuBar-item {
  box-sizing: border-box;
}

.lm-MenuBar-itemIcon,
.lm-MenuBar-itemLabel {
  display: inline-block;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-ScrollBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-ScrollBar[data-orientation='horizontal'] {
  flex-direction: row;
}

.lm-ScrollBar[data-orientation='vertical'] {
  flex-direction: column;
}

.lm-ScrollBar-button {
  box-sizing: border-box;
  flex: 0 0 auto;
}

.lm-ScrollBar-track {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  flex: 1 1 auto;
}

.lm-ScrollBar-thumb {
  box-sizing: border-box;
  position: absolute;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-SplitPanel-child {
  z-index: 0;
}

.lm-SplitPanel-handle {
  z-index: 1;
}

.lm-SplitPanel-handle.lm-mod-hidden {
  display: none !important;
}

.lm-SplitPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}

.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle {
  cursor: ew-resize;
}

.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle {
  cursor: ns-resize;
}

.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}

.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-TabBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-TabBar[data-orientation='horizontal'] {
  flex-direction: row;
  align-items: flex-end;
}

.lm-TabBar[data-orientation='vertical'] {
  flex-direction: column;
  align-items: flex-end;
}

.lm-TabBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex: 1 1 auto;
  list-style-type: none;
}

.lm-TabBar[data-orientation='horizontal'] > .lm-TabBar-content {
  flex-direction: row;
}

.lm-TabBar[data-orientation='vertical'] > .lm-TabBar-content {
  flex-direction: column;
}

.lm-TabBar-tab {
  display: flex;
  flex-direction: row;
  box-sizing: border-box;
  overflow: hidden;
  touch-action: none; /* Disable native Drag/Drop */
}

.lm-TabBar-tabIcon,
.lm-TabBar-tabCloseIcon {
  flex: 0 0 auto;
}

.lm-TabBar-tabLabel {
  flex: 1 1 auto;
  overflow: hidden;
  white-space: nowrap;
}

.lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing: border-box;
}

.lm-TabBar-tab.lm-mod-hidden {
  display: none !important;
}

.lm-TabBar-addButton.lm-mod-hidden {
  display: none !important;
}

.lm-TabBar.lm-mod-dragging .lm-TabBar-tab {
  position: relative;
}

.lm-TabBar.lm-mod-dragging[data-orientation='horizontal'] .lm-TabBar-tab {
  left: 0;
  transition: left 150ms ease;
}

.lm-TabBar.lm-mod-dragging[data-orientation='vertical'] .lm-TabBar-tab {
  top: 0;
  transition: top 150ms ease;
}

.lm-TabBar.lm-mod-dragging .lm-TabBar-tab.lm-mod-dragging {
  transition: none;
}

.lm-TabBar-tabLabel .lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing: border-box;
  background: inherit;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-TabPanel-tabBar {
  z-index: 1;
}

.lm-TabPanel-stackedPanel {
  z-index: 0;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapse {
  display: flex;
  flex-direction: column;
  align-items: stretch;
}

.jp-Collapse-header {
  padding: 1px 12px;
  background-color: var(--jp-layout-color1);
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  align-items: center;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  text-transform: uppercase;
  user-select: none;
}

.jp-Collapser-icon {
  height: 16px;
}

.jp-Collapse-header-collapsed .jp-Collapser-icon {
  transform: rotate(-90deg);
  margin: auto 0;
}

.jp-Collapser-title {
  line-height: 25px;
}

.jp-Collapse-contents {
  padding: 0 12px;
  background-color: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensureUiComponents() in @jupyterlab/buildutils */

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

/* Icons urls */

:root {
  --jp-icon-add-above: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwXzEzN18xOTQ5MikiPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGQ9Ik00Ljc1IDQuOTMwNjZINi42MjVWNi44MDU2NkM2LjYyNSA3LjAxMTkxIDYuNzkzNzUgNy4xODA2NiA3IDcuMTgwNjZDNy4yMDYyNSA3LjE4MDY2IDcuMzc1IDcuMDExOTEgNy4zNzUgNi44MDU2NlY0LjkzMDY2SDkuMjVDOS40NTYyNSA0LjkzMDY2IDkuNjI1IDQuNzYxOTEgOS42MjUgNC41NTU2NkM5LjYyNSA0LjM0OTQxIDkuNDU2MjUgNC4xODA2NiA5LjI1IDQuMTgwNjZINy4zNzVWMi4zMDU2NkM3LjM3NSAyLjA5OTQxIDcuMjA2MjUgMS45MzA2NiA3IDEuOTMwNjZDNi43OTM3NSAxLjkzMDY2IDYuNjI1IDIuMDk5NDEgNi42MjUgMi4zMDU2NlY0LjE4MDY2SDQuNzVDNC41NDM3NSA0LjE4MDY2IDQuMzc1IDQuMzQ5NDEgNC4zNzUgNC41NTU2NkM0LjM3NSA0Ljc2MTkxIDQuNTQzNzUgNC45MzA2NiA0Ljc1IDQuOTMwNjZaIiBmaWxsPSIjNjE2MTYxIiBzdHJva2U9IiM2MTYxNjEiIHN0cm9rZS13aWR0aD0iMC43Ii8+CjwvZz4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZD0iTTExLjUgOS41VjExLjVMMi41IDExLjVWOS41TDExLjUgOS41Wk0xMiA4QzEyLjU1MjMgOCAxMyA4LjQ0NzcyIDEzIDlWMTJDMTMgMTIuNTUyMyAxMi41NTIzIDEzIDEyIDEzTDIgMTNDMS40NDc3MiAxMyAxIDEyLjU1MjMgMSAxMlY5QzEgOC40NDc3MiAxLjQ0NzcxIDggMiA4TDEyIDhaIiBmaWxsPSIjNjE2MTYxIi8+CjxkZWZzPgo8Y2xpcFBhdGggaWQ9ImNsaXAwXzEzN18xOTQ5MiI+CjxyZWN0IGNsYXNzPSJqcC1pY29uMyIgd2lkdGg9IjYiIGhlaWdodD0iNiIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0ibWF0cml4KC0xIDAgMCAxIDEwIDEuNTU1NjYpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==);
  --jp-icon-add-below: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwXzEzN18xOTQ5OCkiPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGQ9Ik05LjI1IDEwLjA2OTNMNy4zNzUgMTAuMDY5M0w3LjM3NSA4LjE5NDM0QzcuMzc1IDcuOTg4MDkgNy4yMDYyNSA3LjgxOTM0IDcgNy44MTkzNEM2Ljc5Mzc1IDcuODE5MzQgNi42MjUgNy45ODgwOSA2LjYyNSA4LjE5NDM0TDYuNjI1IDEwLjA2OTNMNC43NSAxMC4wNjkzQzQuNTQzNzUgMTAuMDY5MyA0LjM3NSAxMC4yMzgxIDQuMzc1IDEwLjQ0NDNDNC4zNzUgMTAuNjUwNiA0LjU0Mzc1IDEwLjgxOTMgNC43NSAxMC44MTkzTDYuNjI1IDEwLjgxOTNMNi42MjUgMTIuNjk0M0M2LjYyNSAxMi45MDA2IDYuNzkzNzUgMTMuMDY5MyA3IDEzLjA2OTNDNy4yMDYyNSAxMy4wNjkzIDcuMzc1IDEyLjkwMDYgNy4zNzUgMTIuNjk0M0w3LjM3NSAxMC44MTkzTDkuMjUgMTAuODE5M0M5LjQ1NjI1IDEwLjgxOTMgOS42MjUgMTAuNjUwNiA5LjYyNSAxMC40NDQzQzkuNjI1IDEwLjIzODEgOS40NTYyNSAxMC4wNjkzIDkuMjUgMTAuMDY5M1oiIGZpbGw9IiM2MTYxNjEiIHN0cm9rZT0iIzYxNjE2MSIgc3Ryb2tlLXdpZHRoPSIwLjciLz4KPC9nPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMi41IDUuNUwyLjUgMy41TDExLjUgMy41TDExLjUgNS41TDIuNSA1LjVaTTIgN0MxLjQ0NzcyIDcgMSA2LjU1MjI4IDEgNkwxIDNDMSAyLjQ0NzcyIDEuNDQ3NzIgMiAyIDJMMTIgMkMxMi41NTIzIDIgMTMgMi40NDc3MiAxMyAzTDEzIDZDMTMgNi41NTIyOSAxMi41NTIzIDcgMTIgN0wyIDdaIiBmaWxsPSIjNjE2MTYxIi8+CjxkZWZzPgo8Y2xpcFBhdGggaWQ9ImNsaXAwXzEzN18xOTQ5OCI+CjxyZWN0IGNsYXNzPSJqcC1pY29uMyIgd2lkdGg9IjYiIGhlaWdodD0iNiIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0ibWF0cml4KDEgMS43NDg0NmUtMDcgMS43NDg0NmUtMDcgLTEgNCAxMy40NDQzKSIvPgo8L2NsaXBQYXRoPgo8L2RlZnM+Cjwvc3ZnPgo=);
  --jp-icon-add: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDEzaC02djZoLTJ2LTZINXYtMmg2VjVoMnY2aDZ2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bell: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE2IDE2IiB2ZXJzaW9uPSIxLjEiPgogICA8cGF0aCBjbGFzcz0ianAtaWNvbjIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMzMzMzMzIgogICAgICBkPSJtOCAwLjI5Yy0xLjQgMC0yLjcgMC43My0zLjYgMS44LTEuMiAxLjUtMS40IDMuNC0xLjUgNS4yLTAuMTggMi4yLTAuNDQgNC0yLjMgNS4zbDAuMjggMS4zaDVjMC4wMjYgMC42NiAwLjMyIDEuMSAwLjcxIDEuNSAwLjg0IDAuNjEgMiAwLjYxIDIuOCAwIDAuNTItMC40IDAuNi0xIDAuNzEtMS41aDVsMC4yOC0xLjNjLTEuOS0wLjk3LTIuMi0zLjMtMi4zLTUuMy0wLjEzLTEuOC0wLjI2LTMuNy0xLjUtNS4yLTAuODUtMS0yLjItMS44LTMuNi0xLjh6bTAgMS40YzAuODggMCAxLjkgMC41NSAyLjUgMS4zIDAuODggMS4xIDEuMSAyLjcgMS4yIDQuNCAwLjEzIDEuNyAwLjIzIDMuNiAxLjMgNS4yaC0xMGMxLjEtMS42IDEuMi0zLjQgMS4zLTUuMiAwLjEzLTEuNyAwLjMtMy4zIDEuMi00LjQgMC41OS0wLjcyIDEuNi0xLjMgMi41LTEuM3ptLTAuNzQgMTJoMS41Yy0wLjAwMTUgMC4yOCAwLjAxNSAwLjc5LTAuNzQgMC43OS0wLjczIDAuMDAxNi0wLjcyLTAuNTMtMC43NC0wLjc5eiIgLz4KPC9zdmc+Cg==);
  --jp-icon-bug-dot: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiPgogICAgICAgIDxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMTcuMTkgOEgyMFYxMEgxNy45MUMxNy45NiAxMC4zMyAxOCAxMC42NiAxOCAxMVYxMkgyMFYxNEgxOC41SDE4VjE0LjAyNzVDMTUuNzUgMTQuMjc2MiAxNCAxNi4xODM3IDE0IDE4LjVDMTQgMTkuMjA4IDE0LjE2MzUgMTkuODc3OSAxNC40NTQ5IDIwLjQ3MzlDMTMuNzA2MyAyMC44MTE3IDEyLjg3NTcgMjEgMTIgMjFDOS43OCAyMSA3Ljg1IDE5Ljc5IDYuODEgMThINFYxNkg2LjA5QzYuMDQgMTUuNjcgNiAxNS4zNCA2IDE1VjE0SDRWMTJINlYxMUM2IDEwLjY2IDYuMDQgMTAuMzMgNi4wOSAxMEg0VjhINi44MUM3LjI2IDcuMjIgNy44OCA2LjU1IDguNjIgNi4wNEw3IDQuNDFMOC40MSAzTDEwLjU5IDUuMTdDMTEuMDQgNS4wNiAxMS41MSA1IDEyIDVDMTIuNDkgNSAxMi45NiA1LjA2IDEzLjQyIDUuMTdMMTUuNTkgM0wxNyA0LjQxTDE1LjM3IDYuMDRDMTYuMTIgNi41NSAxNi43NCA3LjIyIDE3LjE5IDhaTTEwIDE2SDE0VjE0SDEwVjE2Wk0xMCAxMkgxNFYxMEgxMFYxMloiIGZpbGw9IiM2MTYxNjEiLz4KICAgICAgICA8cGF0aCBkPSJNMjIgMTguNUMyMiAyMC40MzMgMjAuNDMzIDIyIDE4LjUgMjJDMTYuNTY3IDIyIDE1IDIwLjQzMyAxNSAxOC41QzE1IDE2LjU2NyAxNi41NjcgMTUgMTguNSAxNUMyMC40MzMgMTUgMjIgMTYuNTY3IDIyIDE4LjVaIiBmaWxsPSIjNjE2MTYxIi8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bug: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yMCA4aC0yLjgxYy0uNDUtLjc4LTEuMDctMS40NS0xLjgyLTEuOTZMMTcgNC40MSAxNS41OSAzbC0yLjE3IDIuMTdDMTIuOTYgNS4wNiAxMi40OSA1IDEyIDVjLS40OSAwLS45Ni4wNi0xLjQxLjE3TDguNDEgMyA3IDQuNDFsMS42MiAxLjYzQzcuODggNi41NSA3LjI2IDcuMjIgNi44MSA4SDR2MmgyLjA5Yy0uMDUuMzMtLjA5LjY2LS4wOSAxdjFINHYyaDJ2MWMwIC4zNC4wNC42Ny4wOSAxSDR2MmgyLjgxYzEuMDQgMS43OSAyLjk3IDMgNS4xOSAzczQuMTUtMS4yMSA1LjE5LTNIMjB2LTJoLTIuMDljLjA1LS4zMy4wOS0uNjYuMDktMXYtMWgydi0yaC0ydi0xYzAtLjM0LS4wNC0uNjctLjA5LTFIMjBWOHptLTYgOGgtNHYtMmg0djJ6bTAtNGgtNHYtMmg0djJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-build: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE0LjkgMTcuNDVDMTYuMjUgMTcuNDUgMTcuMzUgMTYuMzUgMTcuMzUgMTVDMTcuMzUgMTMuNjUgMTYuMjUgMTIuNTUgMTQuOSAxMi41NUMxMy41NCAxMi41NSAxMi40NSAxMy42NSAxMi40NSAxNUMxMi40NSAxNi4zNSAxMy41NCAxNy40NSAxNC45IDE3LjQ1Wk0yMC4xIDE1LjY4TDIxLjU4IDE2Ljg0QzIxLjcxIDE2Ljk1IDIxLjc1IDE3LjEzIDIxLjY2IDE3LjI5TDIwLjI2IDE5LjcxQzIwLjE3IDE5Ljg2IDIwIDE5LjkyIDE5LjgzIDE5Ljg2TDE4LjA5IDE5LjE2QzE3LjczIDE5LjQ0IDE3LjMzIDE5LjY3IDE2LjkxIDE5Ljg1TDE2LjY0IDIxLjdDMTYuNjIgMjEuODcgMTYuNDcgMjIgMTYuMyAyMkgxMy41QzEzLjMyIDIyIDEzLjE4IDIxLjg3IDEzLjE1IDIxLjdMMTIuODkgMTkuODVDMTIuNDYgMTkuNjcgMTIuMDcgMTkuNDQgMTEuNzEgMTkuMTZMOS45NjAwMiAxOS44NkM5LjgxMDAyIDE5LjkyIDkuNjIwMDIgMTkuODYgOS41NDAwMiAxOS43MUw4LjE0MDAyIDE3LjI5QzguMDUwMDIgMTcuMTMgOC4wOTAwMiAxNi45NSA4LjIyMDAyIDE2Ljg0TDkuNzAwMDIgMTUuNjhMOS42NTAwMSAxNUw5LjcwMDAyIDE0LjMxTDguMjIwMDIgMTMuMTZDOC4wOTAwMiAxMy4wNSA4LjA1MDAyIDEyLjg2IDguMTQwMDIgMTIuNzFMOS41NDAwMiAxMC4yOUM5LjYyMDAyIDEwLjEzIDkuODEwMDIgMTAuMDcgOS45NjAwMiAxMC4xM0wxMS43MSAxMC44NEMxMi4wNyAxMC41NiAxMi40NiAxMC4zMiAxMi44OSAxMC4xNUwxMy4xNSA4LjI4OTk4QzEzLjE4IDguMTI5OTggMTMuMzIgNy45OTk5OCAxMy41IDcuOTk5OThIMTYuM0MxNi40NyA3Ljk5OTk4IDE2LjYyIDguMTI5OTggMTYuNjQgOC4yODk5OEwxNi45MSAxMC4xNUMxNy4zMyAxMC4zMiAxNy43MyAxMC41NiAxOC4wOSAxMC44NEwxOS44MyAxMC4xM0MyMCAxMC4wNyAyMC4xNyAxMC4xMyAyMC4yNiAxMC4yOUwyMS42NiAxMi43MUMyMS43NSAxMi44NiAyMS43MSAxMy4wNSAyMS41OCAxMy4xNkwyMC4xIDE0LjMxTDIwLjE1IDE1TDIwLjEgMTUuNjhaIi8+CiAgICA8cGF0aCBkPSJNNy4zMjk2NiA3LjQ0NDU0QzguMDgzMSA3LjAwOTU0IDguMzM5MzIgNi4wNTMzMiA3LjkwNDMyIDUuMjk5ODhDNy40NjkzMiA0LjU0NjQzIDYuNTA4MSA0LjI4MTU2IDUuNzU0NjYgNC43MTY1NkM1LjM5MTc2IDQuOTI2MDggNS4xMjY5NSA1LjI3MTE4IDUuMDE4NDkgNS42NzU5NEM0LjkxMDA0IDYuMDgwNzEgNC45NjY4MiA2LjUxMTk4IDUuMTc2MzQgNi44NzQ4OEM1LjYxMTM0IDcuNjI4MzIgNi41NzYyMiA3Ljg3OTU0IDcuMzI5NjYgNy40NDQ1NFpNOS42NTcxOCA0Ljc5NTkzTDEwLjg2NzIgNC45NTE3OUMxMC45NjI4IDQuOTc3NDEgMTEuMDQwMiA1LjA3MTMzIDExLjAzODIgNS4xODc5M0wxMS4wMzg4IDYuOTg4OTNDMTEuMDQ1NSA3LjEwMDU0IDEwLjk2MTYgNy4xOTUxOCAxMC44NTUgNy4yMTA1NEw5LjY2MDAxIDcuMzgwODNMOS4yMzkxNSA4LjEzMTg4TDkuNjY5NjEgOS4yNTc0NUM5LjcwNzI5IDkuMzYyNzEgOS42NjkzNCA5LjQ3Njk5IDkuNTc0MDggOS41MzE5OUw4LjAxNTIzIDEwLjQzMkM3LjkxMTMxIDEwLjQ5MiA3Ljc5MzM3IDEwLjQ2NzcgNy43MjEwNSAxMC4zODI0TDYuOTg3NDggOS40MzE4OEw2LjEwOTMxIDkuNDMwODNMNS4zNDcwNCAxMC4zOTA1QzUuMjg5MDkgMTAuNDcwMiA1LjE3MzgzIDEwLjQ5MDUgNS4wNzE4NyAxMC40MzM5TDMuNTEyNDUgOS41MzI5M0MzLjQxMDQ5IDkuNDc2MzMgMy4zNzY0NyA5LjM1NzQxIDMuNDEwNzUgOS4yNTY3OUwzLjg2MzQ3IDguMTQwOTNMMy42MTc0OSA3Ljc3NDg4TDMuNDIzNDcgNy4zNzg4M0wyLjIzMDc1IDcuMjEyOTdDMi4xMjY0NyA3LjE5MjM1IDIuMDQwNDkgNy4xMDM0MiAyLjA0MjQ1IDYuOTg2ODJMMi4wNDE4NyA1LjE4NTgyQzIuMDQzODMgNS4wNjkyMiAyLjExOTA5IDQuOTc5NTggMi4yMTcwNCA0Ljk2OTIyTDMuNDIwNjUgNC43OTM5M0wzLjg2NzQ5IDQuMDI3ODhMMy40MTEwNSAyLjkxNzMxQzMuMzczMzcgMi44MTIwNCAzLjQxMTMxIDIuNjk3NzYgMy41MTUyMyAyLjYzNzc2TDUuMDc0MDggMS43Mzc3NkM1LjE2OTM0IDEuNjgyNzYgNS4yODcyOSAxLjcwNzA0IDUuMzU5NjEgMS43OTIzMUw2LjExOTE1IDIuNzI3ODhMNi45ODAwMSAyLjczODkzTDcuNzI0OTYgMS43ODkyMkM3Ljc5MTU2IDEuNzA0NTggNy45MTU0OCAxLjY3OTIyIDguMDA4NzkgMS43NDA4Mkw5LjU2ODIxIDIuNjQxODJDOS42NzAxNyAyLjY5ODQyIDkuNzEyODUgMi44MTIzNCA5LjY4NzIzIDIuOTA3OTdMOS4yMTcxOCA0LjAzMzgzTDkuNDYzMTYgNC4zOTk4OEw5LjY1NzE4IDQuNzk1OTNaIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iOS45LDEzLjYgMy42LDcuNCA0LjQsNi42IDkuOSwxMi4yIDE1LjQsNi43IDE2LjEsNy40ICIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNS45TDksOS43bDMuOC0zLjhsMS4yLDEuMmwtNC45LDVsLTQuOS01TDUuMiw1Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNy41TDksMTEuMmwzLjgtMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-left: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik0xMC44LDEyLjhMNy4xLDlsMy44LTMuOGwwLDcuNkgxMC44eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-right: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik03LjIsNS4yTDEwLjksOWwtMy44LDMuOFY1LjJINy4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-up-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iMTUuNCwxMy4zIDkuOSw3LjcgNC40LDEzLjIgMy42LDEyLjUgOS45LDYuMyAxNi4xLDEyLjYgIi8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-up: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik01LjIsMTAuNUw5LDYuOGwzLjgsMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-case-sensitive: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWFjY2VudDIiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTcuNiw4aDAuOWwzLjUsOGgtMS4xTDEwLDE0SDZsLTAuOSwySDRMNy42LDh6IE04LDkuMUw2LjQsMTNoMy4yTDgsOS4xeiIvPgogICAgPHBhdGggZD0iTTE2LjYsOS44Yy0wLjIsMC4xLTAuNCwwLjEtMC43LDAuMWMtMC4yLDAtMC40LTAuMS0wLjYtMC4yYy0wLjEtMC4xLTAuMi0wLjQtMC4yLTAuNyBjLTAuMywwLjMtMC42LDAuNS0wLjksMC43Yy0wLjMsMC4xLTAuNywwLjItMS4xLDAuMmMtMC4zLDAtMC41LDAtMC43LTAuMWMtMC4yLTAuMS0wLjQtMC4yLTAuNi0wLjNjLTAuMi0wLjEtMC4zLTAuMy0wLjQtMC41IGMtMC4xLTAuMi0wLjEtMC40LTAuMS0wLjdjMC0wLjMsMC4xLTAuNiwwLjItMC44YzAuMS0wLjIsMC4zLTAuNCwwLjQtMC41QzEyLDcsMTIuMiw2LjksMTIuNSw2LjhjMC4yLTAuMSwwLjUtMC4xLDAuNy0wLjIgYzAuMy0wLjEsMC41LTAuMSwwLjctMC4xYzAuMiwwLDAuNC0wLjEsMC42LTAuMWMwLjIsMCwwLjMtMC4xLDAuNC0wLjJjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjRjMC0xLTEuMS0xLTEuMy0xIGMtMC40LDAtMS40LDAtMS40LDEuMmgtMC45YzAtMC40LDAuMS0wLjcsMC4yLTFjMC4xLTAuMiwwLjMtMC40LDAuNS0wLjZjMC4yLTAuMiwwLjUtMC4zLDAuOC0wLjNDMTMuMyw0LDEzLjYsNCwxMy45LDQgYzAuMywwLDAuNSwwLDAuOCwwLjFjMC4zLDAsMC41LDAuMSwwLjcsMC4yYzAuMiwwLjEsMC40LDAuMywwLjUsMC41QzE2LDUsMTYsNS4yLDE2LDUuNnYyLjljMCwwLjIsMCwwLjQsMCwwLjUgYzAsMC4xLDAuMSwwLjIsMC4zLDAuMmMwLjEsMCwwLjIsMCwwLjMsMFY5Ljh6IE0xNS4yLDYuOWMtMS4yLDAuNi0zLjEsMC4yLTMuMSwxLjRjMCwxLjQsMy4xLDEsMy4xLTAuNVY2Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik05IDE2LjE3TDQuODMgMTJsLTEuNDIgMS40MUw5IDE5IDIxIDdsLTEuNDEtMS40MXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-circle-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDJDNi40NyAyIDIgNi40NyAyIDEyczQuNDcgMTAgMTAgMTAgMTAtNC40NyAxMC0xMFMxNy41MyAyIDEyIDJ6bTAgMThjLTQuNDEgMC04LTMuNTktOC04czMuNTktOCA4LTggOCAzLjU5IDggOC0zLjU5IDgtOCA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iOSIgY3k9IjkiIHI9IjgiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-clear: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8bWFzayBpZD0iZG9udXRIb2xlIj4KICAgIDxyZWN0IHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgZmlsbD0id2hpdGUiIC8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI4IiBmaWxsPSJibGFjayIvPgogIDwvbWFzaz4KCiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxyZWN0IGhlaWdodD0iMTgiIHdpZHRoPSIyIiB4PSIxMSIgeT0iMyIgdHJhbnNmb3JtPSJyb3RhdGUoMzE1LCAxMiwgMTIpIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIgbWFzaz0idXJsKCNkb251dEhvbGUpIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-close: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1ub25lIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIGpwLWljb24zLWhvdmVyIiBmaWxsPSJub25lIj4KICAgIDxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjExIi8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIGpwLWljb24tYWNjZW50Mi1ob3ZlciIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMTkgNi40MUwxNy41OSA1IDEyIDEwLjU5IDYuNDEgNSA1IDYuNDEgMTAuNTkgMTIgNSAxNy41OSA2LjQxIDE5IDEyIDEzLjQxIDE3LjU5IDE5IDE5IDE3LjU5IDEzLjQxIDEyeiIvPgogIDwvZz4KCiAgPGcgY2xhc3M9ImpwLWljb24tbm9uZSBqcC1pY29uLWJ1c3kiIGZpbGw9Im5vbmUiPgogICAgPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBzaGFwZS1yZW5kZXJpbmc9Imdlb21ldHJpY1ByZWNpc2lvbiI+CiAgICA8cGF0aCBkPSJNNi41OSwzLjQxTDIsOEw2LjU5LDEyLjZMOCwxMS4xOEw0LjgyLDhMOCw0LjgyTDYuNTksMy40MU0xMi40MSwzLjQxTDExLDQuODJMMTQuMTgsOEwxMSwxMS4xOEwxMi40MSwxMi42TDE3LDhMMTIuNDEsMy40MU0yMS41OSwxMS41OUwxMy41LDE5LjY4TDkuODMsMTZMOC40MiwxNy40MUwxMy41LDIyLjVMMjMsMTNMMjEuNTksMTEuNTlaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTExLjQgMTguNkw2LjggMTRMMTEuNCA5LjRMMTAgOEw0IDE0TDEwIDIwTDExLjQgMTguNlpNMTYuNiAxOC42TDIxLjIgMTRMMTYuNiA5LjRMMTggOEwyNCAxNEwxOCAyMEwxNi42IDE4LjZWMTguNloiLz4KCTwvZz4KPC9zdmc+Cg==);
  --jp-icon-collapse-all: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTggMmMxIDAgMTEgMCAxMiAwczIgMSAyIDJjMCAxIDAgMTEgMCAxMnMwIDItMiAyQzIwIDE0IDIwIDQgMjAgNFMxMCA0IDYgNGMwLTIgMS0yIDItMnoiIC8+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTE4IDhjMC0xLTEtMi0yLTJTNSA2IDQgNnMtMiAxLTIgMmMwIDEgMCAxMSAwIDEyczEgMiAyIDJjMSAwIDExIDAgMTIgMHMyLTEgMi0yYzAtMSAwLTExIDAtMTJ6bS0yIDB2MTJINFY4eiIgLz4KICAgICAgICA8cGF0aCBkPSJNNiAxM3YyaDh2LTJ6IiAvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-console: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwMCAyMDAiPgogIDxnIGNsYXNzPSJqcC1jb25zb2xlLWljb24tYmFja2dyb3VuZC1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMjg4RDEiPgogICAgPHBhdGggZD0iTTIwIDE5LjhoMTYwdjE1OS45SDIweiIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtY29uc29sZS1pY29uLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIj4KICAgIDxwYXRoIGQ9Ik0xMDUgMTI3LjNoNDB2MTIuOGgtNDB6TTUxLjEgNzdMNzQgOTkuOWwtMjMuMyAyMy4zIDEwLjUgMTAuNSAyMy4zLTIzLjNMOTUgOTkuOSA4NC41IDg5LjQgNjEuNiA2Ni41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copy: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTExLjksMUgzLjJDMi40LDEsMS43LDEuNywxLjcsMi41djEwLjJoMS41VjIuNWg4LjdWMXogTTE0LjEsMy45aC04Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjV2MTAuMmMwLDAuOCwwLjcsMS41LDEuNSwxLjVoOCBjMC44LDAsMS41LTAuNywxLjUtMS41VjUuNEMxNS41LDQuNiwxNC45LDMuOSwxNC4xLDMuOXogTTE0LjEsMTUuNWgtOFY1LjRoOFYxNS41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copyright: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDI0IDI0IiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCI+CiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0xMS44OCw5LjE0YzEuMjgsMC4wNiwxLjYxLDEuMTUsMS42MywxLjY2aDEuNzljLTAuMDgtMS45OC0xLjQ5LTMuMTktMy40NS0zLjE5QzkuNjQsNy42MSw4LDksOCwxMi4xNCBjMCwxLjk0LDAuOTMsNC4yNCwzLjg0LDQuMjRjMi4yMiwwLDMuNDEtMS42NSwzLjQ0LTIuOTVoLTEuNzljLTAuMDMsMC41OS0wLjQ1LDEuMzgtMS42MywxLjQ0QzEwLjU1LDE0LjgzLDEwLDEzLjgxLDEwLDEyLjE0IEMxMCw5LjI1LDExLjI4LDkuMTYsMTEuODgsOS4xNHogTTEyLDJDNi40OCwyLDIsNi40OCwyLDEyczQuNDgsMTAsMTAsMTBzMTAtNC40OCwxMC0xMFMxNy41MiwyLDEyLDJ6IE0xMiwyMGMtNC40MSwwLTgtMy41OS04LTggczMuNTktOCw4LThzOCwzLjU5LDgsOFMxNi40MSwyMCwxMiwyMHoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-cut: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkuNjQgNy42NGMuMjMtLjUuMzYtMS4wNS4zNi0xLjY0IDAtMi4yMS0xLjc5LTQtNC00UzIgMy43OSAyIDZzMS43OSA0IDQgNGMuNTkgMCAxLjE0LS4xMyAxLjY0LS4zNkwxMCAxMmwtMi4zNiAyLjM2QzcuMTQgMTQuMTMgNi41OSAxNCA2IDE0Yy0yLjIxIDAtNCAxLjc5LTQgNHMxLjc5IDQgNCA0IDQtMS43OSA0LTRjMC0uNTktLjEzLTEuMTQtLjM2LTEuNjRMMTIgMTRsNyA3aDN2LTFMOS42NCA3LjY0ek02IDhjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTAgMTJjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTYtNy41Yy0uMjggMC0uNS0uMjItLjUtLjVzLjIyLS41LjUtLjUuNS4yMi41LjUtLjIyLjUtLjUuNXpNMTkgM2wtNiA2IDIgMiA3LTdWM3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-delete: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2cHgiIGhlaWdodD0iMTZweCI+CiAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIiAvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjI2MjYyIiBkPSJNNiAxOWMwIDEuMS45IDIgMiAyaDhjMS4xIDAgMi0uOSAyLTJWN0g2djEyek0xOSA0aC0zLjVsLTEtMWgtNWwtMSAxSDV2MmgxNFY0eiIgLz4KPC9zdmc+Cg==);
  --jp-icon-download: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDloLTRWM0g5djZINWw3IDcgNy03ek01IDE4djJoMTR2LTJINXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-duplicate: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZD0iTTIuNzk5OTggMC44NzVIOC44OTU4MkM5LjIwMDYxIDAuODc1IDkuNDQ5OTggMS4xMzkxNCA5LjQ0OTk4IDEuNDYxOThDOS40NDk5OCAxLjc4NDgyIDkuMjAwNjEgMi4wNDg5NiA4Ljg5NTgyIDIuMDQ4OTZIMy4zNTQxNUMzLjA0OTM2IDIuMDQ4OTYgMi43OTk5OCAyLjMxMzEgMi43OTk5OCAyLjYzNTk0VjkuNjc5NjlDMi43OTk5OCAxMC4wMDI1IDIuNTUwNjEgMTAuMjY2NyAyLjI0NTgyIDEwLjI2NjdDMS45NDEwMyAxMC4yNjY3IDEuNjkxNjUgMTAuMDAyNSAxLjY5MTY1IDkuNjc5NjlWMi4wNDg5NkMxLjY5MTY1IDEuNDAzMjggMi4xOTA0IDAuODc1IDIuNzk5OTggMC44NzVaTTUuMzY2NjUgMTEuOVY0LjU1SDExLjA4MzNWMTEuOUg1LjM2NjY1Wk00LjE0MTY1IDQuMTQxNjdDNC4xNDE2NSAzLjY5MDYzIDQuNTA3MjggMy4zMjUgNC45NTgzMiAzLjMyNUgxMS40OTE3QzExLjk0MjcgMy4zMjUgMTIuMzA4MyAzLjY5MDYzIDEyLjMwODMgNC4xNDE2N1YxMi4zMDgzQzEyLjMwODMgMTIuNzU5NCAxMS45NDI3IDEzLjEyNSAxMS40OTE3IDEzLjEyNUg0Ljk1ODMyQzQuNTA3MjggMTMuMTI1IDQuMTQxNjUgMTIuNzU5NCA0LjE0MTY1IDEyLjMwODNWNC4xNDE2N1oiIGZpbGw9IiM2MTYxNjEiLz4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNOS40MzU3NCA4LjI2NTA3SDguMzY0MzFWOS4zMzY1QzguMzY0MzEgOS40NTQzNSA4LjI2Nzg4IDkuNTUwNzggOC4xNTAwMiA5LjU1MDc4QzguMDMyMTcgOS41NTA3OCA3LjkzNTc0IDkuNDU0MzUgNy45MzU3NCA5LjMzNjVWOC4yNjUwN0g2Ljg2NDMxQzYuNzQ2NDUgOC4yNjUwNyA2LjY1MDAyIDguMTY4NjQgNi42NTAwMiA4LjA1MDc4QzYuNjUwMDIgNy45MzI5MiA2Ljc0NjQ1IDcuODM2NSA2Ljg2NDMxIDcuODM2NUg3LjkzNTc0VjYuNzY1MDdDNy45MzU3NCA2LjY0NzIxIDguMDMyMTcgNi41NTA3OCA4LjE1MDAyIDYuNTUwNzhDOC4yNjc4OCA2LjU1MDc4IDguMzY0MzEgNi42NDcyMSA4LjM2NDMxIDYuNzY1MDdWNy44MzY1SDkuNDM1NzRDOS41NTM2IDcuODM2NSA5LjY1MDAyIDcuOTMyOTIgOS42NTAwMiA4LjA1MDc4QzkuNjUwMDIgOC4xNjg2NCA5LjU1MzYgOC4yNjUwNyA5LjQzNTc0IDguMjY1MDdaIiBmaWxsPSIjNjE2MTYxIiBzdHJva2U9IiM2MTYxNjEiIHN0cm9rZS13aWR0aD0iMC41Ii8+Cjwvc3ZnPgo=);
  --jp-icon-edit: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMgMTcuMjVWMjFoMy43NUwxNy44MSA5Ljk0bC0zLjc1LTMuNzVMMyAxNy4yNXpNMjAuNzEgNy4wNGMuMzktLjM5LjM5LTEuMDIgMC0xLjQxbC0yLjM0LTIuMzRjLS4zOS0uMzktMS4wMi0uMzktMS40MSAwbC0xLjgzIDEuODMgMy43NSAzLjc1IDEuODMtMS44M3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-ellipses: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iNSIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxOSIgY3k9IjEyIiByPSIyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-error: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj48Y2lyY2xlIGN4PSIxMiIgY3k9IjE5IiByPSIyIi8+PHBhdGggZD0iTTEwIDNoNHYxMmgtNHoiLz48L2c+CjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0wIDBoMjR2MjRIMHoiLz4KPC9zdmc+Cg==);
  --jp-icon-expand-all: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTggMmMxIDAgMTEgMCAxMiAwczIgMSAyIDJjMCAxIDAgMTEgMCAxMnMwIDItMiAyQzIwIDE0IDIwIDQgMjAgNFMxMCA0IDYgNGMwLTIgMS0yIDItMnoiIC8+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTE4IDhjMC0xLTEtMi0yLTJTNSA2IDQgNnMtMiAxLTIgMmMwIDEgMCAxMSAwIDEyczEgMiAyIDJjMSAwIDExIDAgMTIgMHMyLTEgMi0yYzAtMSAwLTExIDAtMTJ6bS0yIDB2MTJINFY4eiIgLz4KICAgICAgICA8cGF0aCBkPSJNMTEgMTBIOXYzSDZ2MmgzdjNoMnYtM2gzdi0yaC0zeiIgLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-extension: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwLjUgMTFIMTlWN2MwLTEuMS0uOS0yLTItMmgtNFYzLjVDMTMgMi4xMiAxMS44OCAxIDEwLjUgMVM4IDIuMTIgOCAzLjVWNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAydjMuOEgzLjVjMS40OSAwIDIuNyAxLjIxIDIuNyAyLjdzLTEuMjEgMi43LTIuNyAyLjdIMlYyMGMwIDEuMS45IDIgMiAyaDMuOHYtMS41YzAtMS40OSAxLjIxLTIuNyAyLjctMi43IDEuNDkgMCAyLjcgMS4yMSAyLjcgMi43VjIySDE3YzEuMSAwIDItLjkgMi0ydi00aDEuNWMxLjM4IDAgMi41LTEuMTIgMi41LTIuNVMyMS44OCAxMSAyMC41IDExeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-fast-forward: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTQgMThsOC41LTZMNCA2djEyem05LTEydjEybDguNS02TDEzIDZ6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-file-upload: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTZoNnYtNmg0bC03LTctNyA3aDR6bS00IDJoMTR2Mkg1eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-file: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuMyA4LjJsLTUuNS01LjVjLS4zLS4zLS43LS41LTEuMi0uNUgzLjljLS44LjEtMS42LjktMS42IDEuOHYxNC4xYzAgLjkuNyAxLjYgMS42IDEuNmgxNC4yYy45IDAgMS42LS43IDEuNi0xLjZWOS40Yy4xLS41LS4xLS45LS40LTEuMnptLTUuOC0zLjNsMy40IDMuNmgtMy40VjQuOXptMy45IDEyLjdINC43Yy0uMSAwLS4yIDAtLjItLjJWNC43YzAtLjIuMS0uMy4yLS4zaDcuMnY0LjRzMCAuOC4zIDEuMWMuMy4zIDEuMS4zIDEuMS4zaDQuM3Y3LjJzLS4xLjItLjIuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-filter-dot: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTE0LDEyVjE5Ljg4QzE0LjA0LDIwLjE4IDEzLjk0LDIwLjUgMTMuNzEsMjAuNzFDMTMuMzIsMjEuMSAxMi42OSwyMS4xIDEyLjMsMjAuNzFMMTAuMjksMTguN0MxMC4wNiwxOC40NyA5Ljk2LDE4LjE2IDEwLDE3Ljg3VjEySDkuOTdMNC4yMSw0LjYyQzMuODcsNC4xOSAzLjk1LDMuNTYgNC4zOCwzLjIyQzQuNTcsMy4wOCA0Ljc4LDMgNSwzVjNIMTlWM0MxOS4yMiwzIDE5LjQzLDMuMDggMTkuNjIsMy4yMkMyMC4wNSwzLjU2IDIwLjEzLDQuMTkgMTkuNzksNC42MkwxNC4wMywxMkgxNFoiIC8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWRvdCIgZmlsbD0iI0ZGRiI+CiAgICA8Y2lyY2xlIGN4PSIxOCIgY3k9IjE3IiByPSIzIj48L2NpcmNsZT4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-filter-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEwIDE4aDR2LTJoLTR2MnpNMyA2djJoMThWNkgzem0zIDdoMTJ2LTJINnYyeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-filter: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTE0LDEyVjE5Ljg4QzE0LjA0LDIwLjE4IDEzLjk0LDIwLjUgMTMuNzEsMjAuNzFDMTMuMzIsMjEuMSAxMi42OSwyMS4xIDEyLjMsMjAuNzFMMTAuMjksMTguN0MxMC4wNiwxOC40NyA5Ljk2LDE4LjE2IDEwLDE3Ljg3VjEySDkuOTdMNC4yMSw0LjYyQzMuODcsNC4xOSAzLjk1LDMuNTYgNC4zOCwzLjIyQzQuNTcsMy4wOCA0Ljc4LDMgNSwzVjNIMTlWM0MxOS4yMiwzIDE5LjQzLDMuMDggMTkuNjIsMy4yMkMyMC4wNSwzLjU2IDIwLjEzLDQuMTkgMTkuNzksNC42MkwxNC4wMywxMkgxNFoiIC8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-folder-favorite: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjRweCIgdmlld0JveD0iMCAwIDI0IDI0IiB3aWR0aD0iMjRweCIgZmlsbD0iIzAwMDAwMCI+CiAgPHBhdGggZD0iTTAgMGgyNHYyNEgwVjB6IiBmaWxsPSJub25lIi8+PHBhdGggY2xhc3M9ImpwLWljb24zIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxNjE2MSIgZD0iTTIwIDZoLThsLTItMkg0Yy0xLjEgMC0yIC45LTIgMnYxMmMwIDEuMS45IDIgMiAyaDE2YzEuMSAwIDItLjkgMi0yVjhjMC0xLjEtLjktMi0yLTJ6bS0yLjA2IDExTDE1IDE1LjI4IDEyLjA2IDE3bC43OC0zLjMzLTIuNTktMi4yNCAzLjQxLS4yOUwxNSA4bDEuMzQgMy4xNCAzLjQxLjI5LTIuNTkgMi4yNC43OCAzLjMzeiIvPgo8L3N2Zz4K);
  --jp-icon-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY4YzAtMS4xLS45LTItMi0yaC04bC0yLTJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-home: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjRweCIgdmlld0JveD0iMCAwIDI0IDI0IiB3aWR0aD0iMjRweCIgZmlsbD0iIzAwMDAwMCI+CiAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjxwYXRoIGNsYXNzPSJqcC1pY29uMyBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xMCAyMHYtNmg0djZoNXYtOGgzTDEyIDMgMiAxMmgzdjh6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-html5: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMDAiIGQ9Ik0xMDguNCAwaDIzdjIyLjhoMjEuMlYwaDIzdjY5aC0yM1Y0NmgtMjF2MjNoLTIzLjJNMjA2IDIzaC0yMC4zVjBoNjMuN3YyM0gyMjl2NDZoLTIzbTUzLjUtNjloMjQuMWwxNC44IDI0LjNMMzEzLjIgMGgyNC4xdjY5aC0yM1YzNC44bC0xNi4xIDI0LjgtMTYuMS0yNC44VjY5aC0yMi42bTg5LjItNjloMjN2NDYuMmgzMi42VjY5aC01NS42Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2U0NGQyNiIgZD0iTTEwNy42IDQ3MWwtMzMtMzcwLjRoMzYyLjhsLTMzIDM3MC4yTDI1NS43IDUxMiIvPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNmMTY1MjkiIGQ9Ik0yNTYgNDgwLjVWMTMxaDE0OC4zTDM3NiA0NDciLz4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNlYmViZWIiIGQ9Ik0xNDIgMTc2LjNoMTE0djQ1LjRoLTY0LjJsNC4yIDQ2LjVoNjB2NDUuM0gxNTQuNG0yIDIyLjhIMjAybDMuMiAzNi4zIDUwLjggMTMuNnY0Ny40bC05My4yLTI2Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIiBkPSJNMzY5LjYgMTc2LjNIMjU1Ljh2NDUuNGgxMDkuNm0tNC4xIDQ2LjVIMjU1Ljh2NDUuNGg1NmwtNS4zIDU5LTUwLjcgMTMuNnY0Ny4ybDkzLTI1LjgiLz4KPC9zdmc+Cg==);
  --jp-icon-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1icmFuZDQganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNGRkYiIGQ9Ik0yLjIgMi4yaDE3LjV2MTcuNUgyLjJ6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzNGNTFCNSIgZD0iTTIuMiAyLjJ2MTcuNWgxNy41bC4xLTE3LjVIMi4yem0xMi4xIDIuMmMxLjIgMCAyLjIgMSAyLjIgMi4ycy0xIDIuMi0yLjIgMi4yLTIuMi0xLTIuMi0yLjIgMS0yLjIgMi4yLTIuMnpNNC40IDE3LjZsMy4zLTguOCAzLjMgNi42IDIuMi0zLjIgNC40IDUuNEg0LjR6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-info: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUwLjk3OCA1MC45NzgiPgoJPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KCQk8cGF0aCBkPSJNNDMuNTIsNy40NThDMzguNzExLDIuNjQ4LDMyLjMwNywwLDI1LjQ4OSwwQzE4LjY3LDAsMTIuMjY2LDIuNjQ4LDcuNDU4LDcuNDU4CgkJCWMtOS45NDMsOS45NDEtOS45NDMsMjYuMTE5LDAsMzYuMDYyYzQuODA5LDQuODA5LDExLjIxMiw3LjQ1NiwxOC4wMzEsNy40NThjMCwwLDAuMDAxLDAsMC4wMDIsMAoJCQljNi44MTYsMCwxMy4yMjEtMi42NDgsMTguMDI5LTcuNDU4YzQuODA5LTQuODA5LDcuNDU3LTExLjIxMiw3LjQ1Ny0xOC4wM0M1MC45NzcsMTguNjcsNDguMzI4LDEyLjI2Niw0My41Miw3LjQ1OHoKCQkJIE00Mi4xMDYsNDIuMTA1Yy00LjQzMiw0LjQzMS0xMC4zMzIsNi44NzItMTYuNjE1LDYuODcyaC0wLjAwMmMtNi4yODUtMC4wMDEtMTIuMTg3LTIuNDQxLTE2LjYxNy02Ljg3MgoJCQljLTkuMTYyLTkuMTYzLTkuMTYyLTI0LjA3MSwwLTMzLjIzM0MxMy4zMDMsNC40NCwxOS4yMDQsMiwyNS40ODksMmM2LjI4NCwwLDEyLjE4NiwyLjQ0LDE2LjYxNyw2Ljg3MgoJCQljNC40MzEsNC40MzEsNi44NzEsMTAuMzMyLDYuODcxLDE2LjYxN0M0OC45NzcsMzEuNzcyLDQ2LjUzNiwzNy42NzUsNDIuMTA2LDQyLjEwNXoiLz4KCQk8cGF0aCBkPSJNMjMuNTc4LDMyLjIxOGMtMC4wMjMtMS43MzQsMC4xNDMtMy4wNTksMC40OTYtMy45NzJjMC4zNTMtMC45MTMsMS4xMS0xLjk5NywyLjI3Mi0zLjI1MwoJCQljMC40NjgtMC41MzYsMC45MjMtMS4wNjIsMS4zNjctMS41NzVjMC42MjYtMC43NTMsMS4xMDQtMS40NzgsMS40MzYtMi4xNzVjMC4zMzEtMC43MDcsMC40OTUtMS41NDEsMC40OTUtMi41CgkJCWMwLTEuMDk2LTAuMjYtMi4wODgtMC43NzktMi45NzljLTAuNTY1LTAuODc5LTEuNTAxLTEuMzM2LTIuODA2LTEuMzY5Yy0xLjgwMiwwLjA1Ny0yLjk4NSwwLjY2Ny0zLjU1LDEuODMyCgkJCWMtMC4zMDEsMC41MzUtMC41MDMsMS4xNDEtMC42MDcsMS44MTRjLTAuMTM5LDAuNzA3LTAuMjA3LDEuNDMyLTAuMjA3LDIuMTc0aC0yLjkzN2MtMC4wOTEtMi4yMDgsMC40MDctNC4xMTQsMS40OTMtNS43MTkKCQkJYzEuMDYyLTEuNjQsMi44NTUtMi40ODEsNS4zNzgtMi41MjdjMi4xNiwwLjAyMywzLjg3NCwwLjYwOCw1LjE0MSwxLjc1OGMxLjI3OCwxLjE2LDEuOTI5LDIuNzY0LDEuOTUsNC44MTEKCQkJYzAsMS4xNDItMC4xMzcsMi4xMTEtMC40MSwyLjkxMWMtMC4zMDksMC44NDUtMC43MzEsMS41OTMtMS4yNjgsMi4yNDNjLTAuNDkyLDAuNjUtMS4wNjgsMS4zMTgtMS43MywyLjAwMgoJCQljLTAuNjUsMC42OTctMS4zMTMsMS40NzktMS45ODcsMi4zNDZjLTAuMjM5LDAuMzc3LTAuNDI5LDAuNzc3LTAuNTY1LDEuMTk5Yy0wLjE2LDAuOTU5LTAuMjE3LDEuOTUxLTAuMTcxLDIuOTc5CgkJCUMyNi41ODksMzIuMjE4LDIzLjU3OCwzMi4yMTgsMjMuNTc4LDMyLjIxOHogTTIzLjU3OCwzOC4yMnYtMy40ODRoMy4wNzZ2My40ODRIMjMuNTc4eiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-inspector: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaW5zcGVjdG9yLWljb24tY29sb3IganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY2YzAtMS4xLS45LTItMi0yem0tNSAxNEg0di00aDExdjR6bTAtNUg0VjloMTF2NHptNSA1aC00VjloNHY5eiIvPgo8L3N2Zz4K);
  --jp-icon-json: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtanNvbi1pY29uLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0Y5QTgyNSI+CiAgICA8cGF0aCBkPSJNMjAuMiAxMS44Yy0xLjYgMC0xLjcuNS0xLjcgMSAwIC40LjEuOS4xIDEuMy4xLjUuMS45LjEgMS4zIDAgMS43LTEuNCAyLjMtMy41IDIuM2gtLjl2LTEuOWguNWMxLjEgMCAxLjQgMCAxLjQtLjggMC0uMyAwLS42LS4xLTEgMC0uNC0uMS0uOC0uMS0xLjIgMC0xLjMgMC0xLjggMS4zLTItMS4zLS4yLTEuMy0uNy0xLjMtMiAwLS40LjEtLjguMS0xLjIuMS0uNC4xLS43LjEtMSAwLS44LS40LS43LTEuNC0uOGgtLjVWNC4xaC45YzIuMiAwIDMuNS43IDMuNSAyLjMgMCAuNC0uMS45LS4xIDEuMy0uMS41LS4xLjktLjEgMS4zIDAgLjUuMiAxIDEuNyAxdjEuOHpNMS44IDEwLjFjMS42IDAgMS43LS41IDEuNy0xIDAtLjQtLjEtLjktLjEtMS4zLS4xLS41LS4xLS45LS4xLTEuMyAwLTEuNiAxLjQtMi4zIDMuNS0yLjNoLjl2MS45aC0uNWMtMSAwLTEuNCAwLTEuNC44IDAgLjMgMCAuNi4xIDEgMCAuMi4xLjYuMSAxIDAgMS4zIDAgMS44LTEuMyAyQzYgMTEuMiA2IDExLjcgNiAxM2MwIC40LS4xLjgtLjEgMS4yLS4xLjMtLjEuNy0uMSAxIDAgLjguMy44IDEuNC44aC41djEuOWgtLjljLTIuMSAwLTMuNS0uNi0zLjUtMi4zIDAtLjQuMS0uOS4xLTEuMy4xLS41LjEtLjkuMS0xLjMgMC0uNS0uMi0xLTEuNy0xdi0xLjl6Ii8+CiAgICA8Y2lyY2xlIGN4PSIxMSIgY3k9IjEzLjgiIHI9IjIuMSIvPgogICAgPGNpcmNsZSBjeD0iMTEiIGN5PSI4LjIiIHI9IjIuMSIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-julia: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDMyNSAzMDAiPgogIDxnIGNsYXNzPSJqcC1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjY2IzYzMzIj4KICAgIDxwYXRoIGQ9Ik0gMTUwLjg5ODQzOCAyMjUgQyAxNTAuODk4NDM4IDI2Ni40MjE4NzUgMTE3LjMyMDMxMiAzMDAgNzUuODk4NDM4IDMwMCBDIDM0LjQ3NjU2MiAzMDAgMC44OTg0MzggMjY2LjQyMTg3NSAwLjg5ODQzOCAyMjUgQyAwLjg5ODQzOCAxODMuNTc4MTI1IDM0LjQ3NjU2MiAxNTAgNzUuODk4NDM4IDE1MCBDIDExNy4zMjAzMTIgMTUwIDE1MC44OTg0MzggMTgzLjU3ODEyNSAxNTAuODk4NDM4IDIyNSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzM4OTgyNiI+CiAgICA8cGF0aCBkPSJNIDIzNy41IDc1IEMgMjM3LjUgMTE2LjQyMTg3NSAyMDMuOTIxODc1IDE1MCAxNjIuNSAxNTAgQyAxMjEuMDc4MTI1IDE1MCA4Ny41IDExNi40MjE4NzUgODcuNSA3NSBDIDg3LjUgMzMuNTc4MTI1IDEyMS4wNzgxMjUgMCAxNjIuNSAwIEMgMjAzLjkyMTg3NSAwIDIzNy41IDMzLjU3ODEyNSAyMzcuNSA3NSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzk1NThiMiI+CiAgICA8cGF0aCBkPSJNIDMyNC4xMDE1NjIgMjI1IEMgMzI0LjEwMTU2MiAyNjYuNDIxODc1IDI5MC41MjM0MzggMzAwIDI0OS4xMDE1NjIgMzAwIEMgMjA3LjY3OTY4OCAzMDAgMTc0LjEwMTU2MiAyNjYuNDIxODc1IDE3NC4xMDE1NjIgMjI1IEMgMTc0LjEwMTU2MiAxODMuNTc4MTI1IDIwNy42Nzk2ODggMTUwIDI0OS4xMDE1NjIgMTUwIEMgMjkwLjUyMzQzOCAxNTAgMzI0LjEwMTU2MiAxODMuNTc4MTI1IDMyNC4xMDE1NjIgMjI1Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-jupyter-favicon: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTUyIiBoZWlnaHQ9IjE2NSIgdmlld0JveD0iMCAwIDE1MiAxNjUiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgPGcgY2xhc3M9ImpwLWp1cHl0ZXItaWNvbi1jb2xvciIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA3ODk0NywgMTEwLjU4MjkyNykiIGQ9Ik03NS45NDIyODQyLDI5LjU4MDQ1NjEgQzQzLjMwMjM5NDcsMjkuNTgwNDU2MSAxNC43OTY3ODMyLDE3LjY1MzQ2MzQgMCwwIEM1LjUxMDgzMjExLDE1Ljg0MDY4MjkgMTUuNzgxNTM4OSwyOS41NjY3NzMyIDI5LjM5MDQ5NDcsMzkuMjc4NDE3MSBDNDIuOTk5Nyw0OC45ODk4NTM3IDU5LjI3MzcsNTQuMjA2NzgwNSA3NS45NjA1Nzg5LDU0LjIwNjc4MDUgQzkyLjY0NzQ1NzksNTQuMjA2NzgwNSAxMDguOTIxNDU4LDQ4Ljk4OTg1MzcgMTIyLjUzMDY2MywzOS4yNzg0MTcxIEMxMzYuMTM5NDUzLDI5LjU2Njc3MzIgMTQ2LjQxMDI4NCwxNS44NDA2ODI5IDE1MS45MjExNTgsMCBDMTM3LjA4Nzg2OCwxNy42NTM0NjM0IDEwOC41ODI1ODksMjkuNTgwNDU2MSA3NS45NDIyODQyLDI5LjU4MDQ1NjEgTDc1Ljk0MjI4NDIsMjkuNTgwNDU2MSBaIiAvPgogICAgPHBhdGggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMzczNjgsIDAuNzA0ODc4KSIgZD0iTTc1Ljk3ODQ1NzksMjQuNjI2NDA3MyBDMTA4LjYxODc2MywyNC42MjY0MDczIDEzNy4xMjQ0NTgsMzYuNTUzNDQxNSAxNTEuOTIxMTU4LDU0LjIwNjc4MDUgQzE0Ni40MTAyODQsMzguMzY2MjIyIDEzNi4xMzk0NTMsMjQuNjQwMTMxNyAxMjIuNTMwNjYzLDE0LjkyODQ4NzggQzEwOC45MjE0NTgsNS4yMTY4NDM5IDkyLjY0NzQ1NzksMCA3NS45NjA1Nzg5LDAgQzU5LjI3MzcsMCA0Mi45OTk3LDUuMjE2ODQzOSAyOS4zOTA0OTQ3LDE0LjkyODQ4NzggQzE1Ljc4MTUzODksMjQuNjQwMTMxNyA1LjUxMDgzMjExLDM4LjM2NjIyMiAwLDU0LjIwNjc4MDUgQzE0LjgzMzA4MTYsMzYuNTg5OTI5MyA0My4zMzg1Njg0LDI0LjYyNjQwNzMgNzUuOTc4NDU3OSwyNC42MjY0MDczIEw3NS45Nzg0NTc5LDI0LjYyNjQwNzMgWiIgLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzkiIGhlaWdodD0iNTEiIHZpZXdCb3g9IjAgMCAzOSA1MSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMTYzOCAtMjI4MSkiPgogICAgIDxnIGNsYXNzPSJqcC1qdXB5dGVyLWljb24tY29sb3IiIGZpbGw9IiNGMzc3MjYiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5Ljc0IDIzMTEuOTgpIiBkPSJNIDE4LjI2NDYgNy4xMzQxMUMgMTAuNDE0NSA3LjEzNDExIDMuNTU4NzIgNC4yNTc2IDAgMEMgMS4zMjUzOSAzLjgyMDQgMy43OTU1NiA3LjEzMDgxIDcuMDY4NiA5LjQ3MzAzQyAxMC4zNDE3IDExLjgxNTIgMTQuMjU1NyAxMy4wNzM0IDE4LjI2OSAxMy4wNzM0QyAyMi4yODIzIDEzLjA3MzQgMjYuMTk2MyAxMS44MTUyIDI5LjQ2OTQgOS40NzMwM0MgMzIuNzQyNCA3LjEzMDgxIDM1LjIxMjYgMy44MjA0IDM2LjUzOCAwQyAzMi45NzA1IDQuMjU3NiAyNi4xMTQ4IDcuMTM0MTEgMTguMjY0NiA3LjEzNDExWiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5LjczIDIyODUuNDgpIiBkPSJNIDE4LjI3MzMgNS45MzkzMUMgMjYuMTIzNSA1LjkzOTMxIDMyLjk3OTMgOC44MTU4MyAzNi41MzggMTMuMDczNEMgMzUuMjEyNiA5LjI1MzAzIDMyLjc0MjQgNS45NDI2MiAyOS40Njk0IDMuNjAwNEMgMjYuMTk2MyAxLjI1ODE4IDIyLjI4MjMgMCAxOC4yNjkgMEMgMTQuMjU1NyAwIDEwLjM0MTcgMS4yNTgxOCA3LjA2ODYgMy42MDA0QyAzLjc5NTU2IDUuOTQyNjIgMS4zMjUzOSA5LjI1MzAzIDAgMTMuMDczNEMgMy41Njc0NSA4LjgyNDYzIDEwLjQyMzIgNS45MzkzMSAxOC4yNzMzIDUuOTM5MzFaIi8+CiAgICA8L2c+CiAgICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjY5LjMgMjI4MS4zMSkiIGQ9Ik0gNS44OTM1MyAyLjg0NEMgNS45MTg4OSAzLjQzMTY1IDUuNzcwODUgNC4wMTM2NyA1LjQ2ODE1IDQuNTE2NDVDIDUuMTY1NDUgNS4wMTkyMiA0LjcyMTY4IDUuNDIwMTUgNC4xOTI5OSA1LjY2ODUxQyAzLjY2NDMgNS45MTY4OCAzLjA3NDQ0IDYuMDAxNTEgMi40OTgwNSA1LjkxMTcxQyAxLjkyMTY2IDUuODIxOSAxLjM4NDYzIDUuNTYxNyAwLjk1NDg5OCA1LjE2NDAxQyAwLjUyNTE3IDQuNzY2MzMgMC4yMjIwNTYgNC4yNDkwMyAwLjA4MzkwMzcgMy42Nzc1N0MgLTAuMDU0MjQ4MyAzLjEwNjExIC0wLjAyMTIzIDIuNTA2MTcgMC4xNzg3ODEgMS45NTM2NEMgMC4zNzg3OTMgMS40MDExIDAuNzM2ODA5IDAuOTIwODE3IDEuMjA3NTQgMC41NzM1MzhDIDEuNjc4MjYgMC4yMjYyNTkgMi4yNDA1NSAwLjAyNzU5MTkgMi44MjMyNiAwLjAwMjY3MjI5QyAzLjYwMzg5IC0wLjAzMDcxMTUgNC4zNjU3MyAwLjI0OTc4OSA0Ljk0MTQyIDAuNzgyNTUxQyA1LjUxNzExIDEuMzE1MzEgNS44NTk1NiAyLjA1Njc2IDUuODkzNTMgMi44NDRaIi8+CiAgICAgIDxwYXRoIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE2MzkuOCAyMzIzLjgxKSIgZD0iTSA3LjQyNzg5IDMuNTgzMzhDIDcuNDYwMDggNC4zMjQzIDcuMjczNTUgNS4wNTgxOSA2Ljg5MTkzIDUuNjkyMTNDIDYuNTEwMzEgNi4zMjYwNyA1Ljk1MDc1IDYuODMxNTYgNS4yODQxMSA3LjE0NDZDIDQuNjE3NDcgNy40NTc2MyAzLjg3MzcxIDcuNTY0MTQgMy4xNDcwMiA3LjQ1MDYzQyAyLjQyMDMyIDcuMzM3MTIgMS43NDMzNiA3LjAwODcgMS4yMDE4NCA2LjUwNjk1QyAwLjY2MDMyOCA2LjAwNTIgMC4yNzg2MSA1LjM1MjY4IDAuMTA1MDE3IDQuNjMyMDJDIC0wLjA2ODU3NTcgMy45MTEzNSAtMC4wMjYyMzYxIDMuMTU0OTQgMC4yMjY2NzUgMi40NTg1NkMgMC40Nzk1ODcgMS43NjIxNyAwLjkzMTY5NyAxLjE1NzEzIDEuNTI1NzYgMC43MjAwMzNDIDIuMTE5ODMgMC4yODI5MzUgMi44MjkxNCAwLjAzMzQzOTUgMy41NjM4OSAwLjAwMzEzMzQ0QyA0LjU0NjY3IC0wLjAzNzQwMzMgNS41MDUyOSAwLjMxNjcwNiA2LjIyOTYxIDAuOTg3ODM1QyA2Ljk1MzkzIDEuNjU4OTYgNy4zODQ4NCAyLjU5MjM1IDcuNDI3ODkgMy41ODMzOEwgNy40Mjc4OSAzLjU4MzM4WiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM4LjM2IDIyODYuMDYpIiBkPSJNIDIuMjc0NzEgNC4zOTYyOUMgMS44NDM2MyA0LjQxNTA4IDEuNDE2NzEgNC4zMDQ0NSAxLjA0Nzk5IDQuMDc4NDNDIDAuNjc5MjY4IDMuODUyNCAwLjM4NTMyOCAzLjUyMTE0IDAuMjAzMzcxIDMuMTI2NTZDIDAuMDIxNDEzNiAyLjczMTk4IC0wLjA0MDM3OTggMi4yOTE4MyAwLjAyNTgxMTYgMS44NjE4MUMgMC4wOTIwMDMxIDEuNDMxOCAwLjI4MzIwNCAxLjAzMTI2IDAuNTc1MjEzIDAuNzEwODgzQyAwLjg2NzIyMiAwLjM5MDUxIDEuMjQ2OTEgMC4xNjQ3MDggMS42NjYyMiAwLjA2MjA1OTJDIDIuMDg1NTMgLTAuMDQwNTg5NyAyLjUyNTYxIC0wLjAxNTQ3MTQgMi45MzA3NiAwLjEzNDIzNUMgMy4zMzU5MSAwLjI4Mzk0MSAzLjY4NzkyIDAuNTUxNTA1IDMuOTQyMjIgMC45MDMwNkMgNC4xOTY1MiAxLjI1NDYyIDQuMzQxNjkgMS42NzQzNiA0LjM1OTM1IDIuMTA5MTZDIDQuMzgyOTkgMi42OTEwNyA0LjE3Njc4IDMuMjU4NjkgMy43ODU5NyAzLjY4NzQ2QyAzLjM5NTE2IDQuMTE2MjQgMi44NTE2NiA0LjM3MTE2IDIuMjc0NzEgNC4zOTYyOUwgMi4yNzQ3MSA0LjM5NjI5WiIvPgogICAgPC9nPgogIDwvZz4+Cjwvc3ZnPgo=);
  --jp-icon-jupyterlab-wordmark: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIHZpZXdCb3g9IjAgMCAxODYwLjggNDc1Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0RTRFNEUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQ4MC4xMzY0MDEsIDY0LjI3MTQ5MykiPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMDAwMDAsIDU4Ljg3NTU2NikiPgogICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA4NzYwMywgMC4xNDAyOTQpIj4KICAgICAgICA8cGF0aCBkPSJNLTQyNi45LDE2OS44YzAsNDguNy0zLjcsNjQuNy0xMy42LDc2LjRjLTEwLjgsMTAtMjUsMTUuNS0zOS43LDE1LjVsMy43LDI5IGMyMi44LDAuMyw0NC44LTcuOSw2MS45LTIzLjFjMTcuOC0xOC41LDI0LTQ0LjEsMjQtODMuM1YwSC00Mjd2MTcwLjFMLTQyNi45LDE2OS44TC00MjYuOSwxNjkuOHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTU1LjA0NTI5NiwgNTYuODM3MTA0KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuNTYyNDUzLCAxLjc5OTg0MikiPgogICAgICAgIDxwYXRoIGQ9Ik0tMzEyLDE0OGMwLDIxLDAsMzkuNSwxLjcsNTUuNGgtMzEuOGwtMi4xLTMzLjNoLTAuOGMtNi43LDExLjYtMTYuNCwyMS4zLTI4LDI3LjkgYy0xMS42LDYuNi0yNC44LDEwLTM4LjIsOS44Yy0zMS40LDAtNjktMTcuNy02OS04OVYwaDM2LjR2MTEyLjdjMCwzOC43LDExLjYsNjQuNyw0NC42LDY0LjdjMTAuMy0wLjIsMjAuNC0zLjUsMjguOS05LjQgYzguNS01LjksMTUuMS0xNC4zLDE4LjktMjMuOWMyLjItNi4xLDMuMy0xMi41LDMuMy0xOC45VjAuMmgzNi40VjE0OEgtMzEyTC0zMTIsMTQ4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzOTAuMDEzMzIyLCA1My40Nzk2MzgpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS43MDY0NTgsIDAuMjMxNDI1KSI+CiAgICAgICAgPHBhdGggZD0iTS00NzguNiw3MS40YzAtMjYtMC44LTQ3LTEuNy02Ni43aDMyLjdsMS43LDM0LjhoMC44YzcuMS0xMi41LDE3LjUtMjIuOCwzMC4xLTI5LjcgYzEyLjUtNywyNi43LTEwLjMsNDEtOS44YzQ4LjMsMCw4NC43LDQxLjcsODQuNywxMDMuM2MwLDczLjEtNDMuNywxMDkuMi05MSwxMDkuMmMtMTIuMSwwLjUtMjQuMi0yLjItMzUtNy44IGMtMTAuOC01LjYtMTkuOS0xMy45LTI2LjYtMjQuMmgtMC44VjI5MWgtMzZ2LTIyMEwtNDc4LjYsNzEuNEwtNDc4LjYsNzEuNHogTS00NDIuNiwxMjUuNmMwLjEsNS4xLDAuNiwxMC4xLDEuNywxNS4xIGMzLDEyLjMsOS45LDIzLjMsMTkuOCwzMS4xYzkuOSw3LjgsMjIuMSwxMi4xLDM0LjcsMTIuMWMzOC41LDAsNjAuNy0zMS45LDYwLjctNzguNWMwLTQwLjctMjEuMS03NS42LTU5LjUtNzUuNiBjLTEyLjksMC40LTI1LjMsNS4xLTM1LjMsMTMuNGMtOS45LDguMy0xNi45LDE5LjctMTkuNiwzMi40Yy0xLjUsNC45LTIuMywxMC0yLjUsMTUuMVYxMjUuNkwtNDQyLjYsMTI1LjZMLTQ0Mi42LDEyNS42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDYuNzQwNzI2LCA1Ni44MzcxMDQpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC43NTEyMjYsIDEuOTg5Mjk5KSI+CiAgICAgICAgPHBhdGggZD0iTS00NDAuOCwwbDQzLjcsMTIwLjFjNC41LDEzLjQsOS41LDI5LjQsMTIuOCw0MS43aDAuOGMzLjctMTIuMiw3LjktMjcuNywxMi44LTQyLjQgbDM5LjctMTE5LjJoMzguNUwtMzQ2LjksMTQ1Yy0yNiw2OS43LTQzLjcsMTA1LjQtNjguNiwxMjcuMmMtMTIuNSwxMS43LTI3LjksMjAtNDQuNiwyMy45bC05LjEtMzEuMSBjMTEuNy0zLjksMjIuNS0xMC4xLDMxLjgtMTguMWMxMy4yLTExLjEsMjMuNy0yNS4yLDMwLjYtNDEuMmMxLjUtMi44LDIuNS01LjcsMi45LTguOGMtMC4zLTMuMy0xLjItNi42LTIuNS05LjdMLTQ4MC4yLDAuMSBoMzkuN0wtNDQwLjgsMEwtNDQwLjgsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoODIyLjc0ODEwNCwgMC4wMDAwMDApIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS40NjQwNTAsIDAuMzc4OTE0KSI+CiAgICAgICAgPHBhdGggZD0iTS00MTMuNywwdjU4LjNoNTJ2MjguMmgtNTJWMTk2YzAsMjUsNywzOS41LDI3LjMsMzkuNWM3LjEsMC4xLDE0LjItMC43LDIxLjEtMi41IGwxLjcsMjcuN2MtMTAuMywzLjctMjEuMyw1LjQtMzIuMiw1Yy03LjMsMC40LTE0LjYtMC43LTIxLjMtMy40Yy02LjgtMi43LTEyLjktNi44LTE3LjktMTIuMWMtMTAuMy0xMC45LTE0LjEtMjktMTQuMS01Mi45IFY4Ni41aC0zMVY1OC4zaDMxVjkuNkwtNDEzLjcsMEwtNDEzLjcsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTc0LjQzMzI4NiwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuOTkwMDM0LCAwLjYxMDMzOSkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDQ1LjgsMTEzYzAuOCw1MCwzMi4yLDcwLjYsNjguNiw3MC42YzE5LDAuNiwzNy45LTMsNTUuMy0xMC41bDYuMiwyNi40IGMtMjAuOSw4LjktNDMuNSwxMy4xLTY2LjIsMTIuNmMtNjEuNSwwLTk4LjMtNDEuMi05OC4zLTEwMi41Qy00ODAuMiw0OC4yLTQ0NC43LDAtMzg2LjUsMGM2NS4yLDAsODIuNyw1OC4zLDgyLjcsOTUuNyBjLTAuMSw1LjgtMC41LDExLjUtMS4yLDE3LjJoLTE0MC42SC00NDUuOEwtNDQ1LjgsMTEzeiBNLTMzOS4yLDg2LjZjMC40LTIzLjUtOS41LTYwLjEtNTAuNC02MC4xIGMtMzYuOCwwLTUyLjgsMzQuNC01NS43LDYwLjFILTMzOS4yTC0zMzkuMiw4Ni42TC0zMzkuMiw4Ni42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjAxLjk2MTA1OCwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuMTc5NjQwLCAwLjcwNTA2OCkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDc4LjYsNjhjMC0yMy45LTAuNC00NC41LTEuNy02My40aDMxLjhsMS4yLDM5LjloMS43YzkuMS0yNy4zLDMxLTQ0LjUsNTUuMy00NC41IGMzLjUtMC4xLDcsMC40LDEwLjMsMS4ydjM0LjhjLTQuMS0wLjktOC4yLTEuMy0xMi40LTEuMmMtMjUuNiwwLTQzLjcsMTkuNy00OC43LDQ3LjRjLTEsNS43LTEuNiwxMS41LTEuNywxNy4ydjEwOC4zaC0zNlY2OCBMLTQ3OC42LDY4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCBkPSJNMTM1Mi4zLDMyNi4yaDM3VjI4aC0zN1YzMjYuMnogTTE2MDQuOCwzMjYuMmMtMi41LTEzLjktMy40LTMxLjEtMy40LTQ4Ljd2LTc2IGMwLTQwLjctMTUuMS04My4xLTc3LjMtODMuMWMtMjUuNiwwLTUwLDcuMS02Ni44LDE4LjFsOC40LDI0LjRjMTQuMy05LjIsMzQtMTUuMSw1My0xNS4xYzQxLjYsMCw0Ni4yLDMwLjIsNDYuMiw0N3Y0LjIgYy03OC42LTAuNC0xMjIuMywyNi41LTEyMi4zLDc1LjZjMCwyOS40LDIxLDU4LjQsNjIuMiw1OC40YzI5LDAsNTAuOS0xNC4zLDYyLjItMzAuMmgxLjNsMi45LDI1LjZIMTYwNC44eiBNMTU2NS43LDI1Ny43IGMwLDMuOC0wLjgsOC0yLjEsMTEuOGMtNS45LDE3LjItMjIuNywzNC00OS4yLDM0Yy0xOC45LDAtMzQuOS0xMS4zLTM0LjktMzUuM2MwLTM5LjUsNDUuOC00Ni42LDg2LjItNDUuOFYyNTcuN3ogTTE2OTguNSwzMjYuMiBsMS43LTMzLjZoMS4zYzE1LjEsMjYuOSwzOC43LDM4LjIsNjguMSwzOC4yYzQ1LjQsMCw5MS4yLTM2LjEsOTEuMi0xMDguOGMwLjQtNjEuNy0zNS4zLTEwMy43LTg1LjctMTAzLjcgYy0zMi44LDAtNTYuMywxNC43LTY5LjMsMzcuNGgtMC44VjI4aC0zNi42djI0NS43YzAsMTguMS0wLjgsMzguNi0xLjcsNTIuNUgxNjk4LjV6IE0xNzA0LjgsMjA4LjJjMC01LjksMS4zLTEwLjksMi4xLTE1LjEgYzcuNi0yOC4xLDMxLjEtNDUuNCw1Ni4zLTQ1LjRjMzkuNSwwLDYwLjUsMzQuOSw2MC41LDc1LjZjMCw0Ni42LTIzLjEsNzguMS02MS44LDc4LjFjLTI2LjksMC00OC4zLTE3LjYtNTUuNS00My4zIGMtMC44LTQuMi0xLjctOC44LTEuNy0xMy40VjIwOC4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzYxNjE2MSIgZD0iTTE1IDlIOXY2aDZWOXptLTIgNGgtMnYtMmgydjJ6bTgtMlY5aC0yVjdjMC0xLjEtLjktMi0yLTJoLTJWM2gtMnYyaC0yVjNIOXYySDdjLTEuMSAwLTIgLjktMiAydjJIM3YyaDJ2MkgzdjJoMnYyYzAgMS4xLjkgMiAyIDJoMnYyaDJ2LTJoMnYyaDJ2LTJoMmMxLjEgMCAyLS45IDItMnYtMmgydi0yaC0ydi0yaDJ6bS00IDZIN1Y3aDEwdjEweiIvPgo8L3N2Zz4K);
  --jp-icon-keyboard: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMTdjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY3YzAtMS4xLS45LTItMi0yem0tOSAzaDJ2MmgtMlY4em0wIDNoMnYyaC0ydi0yek04IDhoMnYySDhWOHptMCAzaDJ2Mkg4di0yem0tMSAySDV2LTJoMnYyem0wLTNINVY4aDJ2MnptOSA3SDh2LTJoOHYyem0wLTRoLTJ2LTJoMnYyem0wLTNoLTJWOGgydjJ6bTMgM2gtMnYtMmgydjJ6bTAtM2gtMlY4aDJ2MnoiLz4KPC9zdmc+Cg==);
  --jp-icon-launch: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMzIgMzIiIHdpZHRoPSIzMiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yNiwyOEg2YTIuMDAyNywyLjAwMjcsMCwwLDEtMi0yVjZBMi4wMDI3LDIuMDAyNywwLDAsMSw2LDRIMTZWNkg2VjI2SDI2VjE2aDJWMjZBMi4wMDI3LDIuMDAyNywwLDAsMSwyNiwyOFoiLz4KICAgIDxwb2x5Z29uIHBvaW50cz0iMjAgMiAyMCA0IDI2LjU4NiA0IDE4IDEyLjU4NiAxOS40MTQgMTQgMjggNS40MTQgMjggMTIgMzAgMTIgMzAgMiAyMCAyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-launcher: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkgMTlINVY1aDdWM0g1YTIgMiAwIDAwLTIgMnYxNGEyIDIgMCAwMDIgMmgxNGMxLjEgMCAyLS45IDItMnYtN2gtMnY3ek0xNCAzdjJoMy41OWwtOS44MyA5LjgzIDEuNDEgMS40MUwxOSA2LjQxVjEwaDJWM2gtN3oiLz4KPC9zdmc+Cg==);
  --jp-icon-line-form: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNS44OCA0LjEyTDEzLjc2IDEybC03Ljg4IDcuODhMOCAyMmwxMC0xMEw4IDJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-link: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMuOSAxMmMwLTEuNzEgMS4zOS0zLjEgMy4xLTMuMWg0VjdIN2MtMi43NiAwLTUgMi4yNC01IDVzMi4yNCA1IDUgNWg0di0xLjlIN2MtMS43MSAwLTMuMS0xLjM5LTMuMS0zLjF6TTggMTNoOHYtMkg4djJ6bTktNmgtNHYxLjloNGMxLjcxIDAgMy4xIDEuMzkgMy4xIDMuMXMtMS4zOSAzLjEtMy4xIDMuMWgtNFYxN2g0YzIuNzYgMCA1LTIuMjQgNS01cy0yLjI0LTUtNS01eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xOSA1djE0SDVWNWgxNG0xLjEtMkgzLjljLS41IDAtLjkuNC0uOS45djE2LjJjMCAuNC40LjkuOS45aDE2LjJjLjQgMCAuOS0uNS45LS45VjMuOWMwLS41LS41LS45LS45LS45ek0xMSA3aDZ2MmgtNlY3em0wIDRoNnYyaC02di0yem0wIDRoNnYyaC02ek03IDdoMnYySDd6bTAgNGgydjJIN3ptMCA0aDJ2Mkg3eiIvPgo8L3N2Zz4K);
  --jp-icon-markdown: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjN0IxRkEyIiBkPSJNNSAxNC45aDEybC02LjEgNnptOS40LTYuOGMwLTEuMy0uMS0yLjktLjEtNC41LS40IDEuNC0uOSAyLjktMS4zIDQuM2wtMS4zIDQuM2gtMkw4LjUgNy45Yy0uNC0xLjMtLjctMi45LTEtNC4zLS4xIDEuNi0uMSAzLjItLjIgNC42TDcgMTIuNEg0LjhsLjctMTFoMy4zTDEwIDVjLjQgMS4yLjcgMi43IDEgMy45LjMtMS4yLjctMi42IDEtMy45bDEuMi0zLjdoMy4zbC42IDExaC0yLjRsLS4zLTQuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-move-down: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNMTIuNDcxIDcuNTI4OTlDMTIuNzYzMiA3LjIzNjg0IDEyLjc2MzIgNi43NjMxNiAxMi40NzEgNi40NzEwMVY2LjQ3MTAxQzEyLjE3OSA2LjE3OTA1IDExLjcwNTcgNi4xNzg4NCAxMS40MTM1IDYuNDcwNTRMNy43NSAxMC4xMjc1VjEuNzVDNy43NSAxLjMzNTc5IDcuNDE0MjEgMSA3IDFWMUM2LjU4NTc5IDEgNi4yNSAxLjMzNTc5IDYuMjUgMS43NVYxMC4xMjc1TDIuNTk3MjYgNi40NjgyMkMyLjMwMzM4IDYuMTczODEgMS44MjY0MSA2LjE3MzU5IDEuNTMyMjYgNi40Njc3NFY2LjQ2Nzc0QzEuMjM4MyA2Ljc2MTcgMS4yMzgzIDcuMjM4MyAxLjUzMjI2IDcuNTMyMjZMNi4yOTI4OSAxMi4yOTI5QzYuNjgzNDIgMTIuNjgzNCA3LjMxNjU4IDEyLjY4MzQgNy43MDcxMSAxMi4yOTI5TDEyLjQ3MSA3LjUyODk5WiIgZmlsbD0iIzYxNjE2MSIvPgo8L3N2Zz4K);
  --jp-icon-move-up: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNMS41Mjg5OSA2LjQ3MTAxQzEuMjM2ODQgNi43NjMxNiAxLjIzNjg0IDcuMjM2ODQgMS41Mjg5OSA3LjUyODk5VjcuNTI4OTlDMS44MjA5NSA3LjgyMDk1IDIuMjk0MjYgNy44MjExNiAyLjU4NjQ5IDcuNTI5NDZMNi4yNSAzLjg3MjVWMTIuMjVDNi4yNSAxMi42NjQyIDYuNTg1NzkgMTMgNyAxM1YxM0M3LjQxNDIxIDEzIDcuNzUgMTIuNjY0MiA3Ljc1IDEyLjI1VjMuODcyNUwxMS40MDI3IDcuNTMxNzhDMTEuNjk2NiA3LjgyNjE5IDEyLjE3MzYgNy44MjY0MSAxMi40Njc3IDcuNTMyMjZWNy41MzIyNkMxMi43NjE3IDcuMjM4MyAxMi43NjE3IDYuNzYxNyAxMi40Njc3IDYuNDY3NzRMNy43MDcxMSAxLjcwNzExQzcuMzE2NTggMS4zMTY1OCA2LjY4MzQyIDEuMzE2NTggNi4yOTI4OSAxLjcwNzExTDEuNTI4OTkgNi40NzEwMVoiIGZpbGw9IiM2MTYxNjEiLz4KPC9zdmc+Cg==);
  --jp-icon-new-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDZoLThsLTItMkg0Yy0xLjExIDAtMS45OS44OS0xLjk5IDJMMiAxOGMwIDEuMTEuODkgMiAyIDJoMTZjMS4xMSAwIDItLjg5IDItMlY4YzAtMS4xMS0uODktMi0yLTJ6bS0xIDhoLTN2M2gtMnYtM2gtM3YtMmgzVjloMnYzaDN2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-not-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI1IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMTkgMTcuMTg0NCAyLjk2OTY4IDE0LjMwMzIgMS44NjA5NCAxMS40NDA5WiIvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24yIiBzdHJva2U9IiMzMzMzMzMiIHN0cm9rZS13aWR0aD0iMiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOS4zMTU5MiA5LjMyMDMxKSIgZD0iTTcuMzY4NDIgMEwwIDcuMzY0NzkiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDkuMzE1OTIgMTYuNjgzNikgc2NhbGUoMSAtMSkiIGQ9Ik03LjM2ODQyIDBMMCA3LjM2NDc5Ii8+Cjwvc3ZnPgo=);
  --jp-icon-notebook: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtbm90ZWJvb2staWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNFRjZDMDAiPgogICAgPHBhdGggZD0iTTE4LjcgMy4zdjE1LjRIMy4zVjMuM2gxNS40bTEuNS0xLjVIMS44djE4LjNoMTguM2wuMS0xOC4zeiIvPgogICAgPHBhdGggZD0iTTE2LjUgMTYuNWwtNS40LTQuMy01LjYgNC4zdi0xMWgxMXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-numbering: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTQgMTlINlYxOS41SDVWMjAuNUg2VjIxSDRWMjJIN1YxOEg0VjE5Wk01IDEwSDZWNkg0VjdINVYxMFpNNCAxM0g1LjhMNCAxNS4xVjE2SDdWMTVINS4yTDcgMTIuOVYxMkg0VjEzWk05IDdWOUgyM1Y3SDlaTTkgMjFIMjNWMTlIOVYyMVpNOSAxNUgyM1YxM0g5VjE1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-offline-bolt: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDIuMDJjLTUuNTEgMC05Ljk4IDQuNDctOS45OCA5Ljk4czQuNDcgOS45OCA5Ljk4IDkuOTggOS45OC00LjQ3IDkuOTgtOS45OFMxNy41MSAyLjAyIDEyIDIuMDJ6TTExLjQ4IDIwdi02LjI2SDhMMTMgNHY2LjI2aDMuMzVMMTEuNDggMjB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-palette: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE4IDEzVjIwSDRWNkg5LjAyQzkuMDcgNS4yOSA5LjI0IDQuNjIgOS41IDRINEMyLjkgNCAyIDQuOSAyIDZWMjBDMiAyMS4xIDIuOSAyMiA0IDIySDE4QzE5LjEgMjIgMjAgMjEuMSAyMCAyMFYxNUwxOCAxM1pNMTkuMyA4Ljg5QzE5Ljc0IDguMTkgMjAgNy4zOCAyMCA2LjVDMjAgNC4wMSAxNy45OSAyIDE1LjUgMkMxMy4wMSAyIDExIDQuMDEgMTEgNi41QzExIDguOTkgMTMuMDEgMTEgMTUuNDkgMTFDMTYuMzcgMTEgMTcuMTkgMTAuNzQgMTcuODggMTAuM0wyMSAxMy40MkwyMi40MiAxMkwxOS4zIDguODlaTTE1LjUgOUMxNC4xMiA5IDEzIDcuODggMTMgNi41QzEzIDUuMTIgMTQuMTIgNCAxNS41IDRDMTYuODggNCAxOCA1LjEyIDE4IDYuNUMxOCA3Ljg4IDE2Ljg4IDkgMTUuNSA5WiIvPgogICAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00IDZIOS4wMTg5NEM5LjAwNjM5IDYuMTY1MDIgOSA2LjMzMTc2IDkgNi41QzkgOC44MTU3NyAxMC4yMTEgMTAuODQ4NyAxMi4wMzQzIDEySDlWMTRIMTZWMTIuOTgxMUMxNi41NzAzIDEyLjkzNzcgMTcuMTIgMTIuODIwNyAxNy42Mzk2IDEyLjYzOTZMMTggMTNWMjBINFY2Wk04IDhINlYxMEg4VjhaTTYgMTJIOFYxNEg2VjEyWk04IDE2SDZWMThIOFYxNlpNOSAxNkgxNlYxOEg5VjE2WiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-paste: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE5IDJoLTQuMThDMTQuNC44NCAxMy4zIDAgMTIgMGMtMS4zIDAtMi40Ljg0LTIuODIgMkg1Yy0xLjEgMC0yIC45LTIgMnYxNmMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjRjMC0xLjEtLjktMi0yLTJ6bS03IDBjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXptNyAxOEg1VjRoMnYzaDEwVjRoMnYxNnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-pdf: url(data:image/svg+xml;base64,PHN2ZwogICB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyMiAyMiIgd2lkdGg9IjE2Ij4KICAgIDxwYXRoIHRyYW5zZm9ybT0icm90YXRlKDQ1KSIgY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0ZGMkEyQSIKICAgICAgIGQ9Im0gMjIuMzQ0MzY5LC0zLjAxNjM2NDIgaCA1LjYzODYwNCB2IDEuNTc5MjQzMyBoIC0zLjU0OTIyNyB2IDEuNTA4NjkyOTkgaCAzLjMzNzU3NiBWIDEuNjUwODE1NCBoIC0zLjMzNzU3NiB2IDMuNDM1MjYxMyBoIC0yLjA4OTM3NyB6IG0gLTcuMTM2NDQ0LDEuNTc5MjQzMyB2IDQuOTQzOTU0MyBoIDAuNzQ4OTIgcSAxLjI4MDc2MSwwIDEuOTUzNzAzLC0wLjYzNDk1MzUgMC42NzgzNjksLTAuNjM0OTUzNSAwLjY3ODM2OSwtMS44NDUxNjQxIDAsLTEuMjA0NzgzNTUgLTAuNjcyOTQyLC0xLjgzNDMxMDExIC0wLjY3Mjk0MiwtMC42Mjk1MjY1OSAtMS45NTkxMywtMC42Mjk1MjY1OSB6IG0gLTIuMDg5Mzc3LC0xLjU3OTI0MzMgaCAyLjIwMzM0MyBxIDEuODQ1MTY0LDAgMi43NDYwMzksMC4yNjU5MjA3IDAuOTA2MzAxLDAuMjYwNDkzNyAxLjU1MjEwOCwwLjg5MDAyMDMgMC41Njk4MywwLjU0ODEyMjMgMC44NDY2MDUsMS4yNjQ0ODAwNiAwLjI3Njc3NCwwLjcxNjM1NzgxIDAuMjc2Nzc0LDEuNjIyNjU4OTQgMCwwLjkxNzE1NTEgLTAuMjc2Nzc0LDEuNjM4OTM5OSAtMC4yNzY3NzUsMC43MTYzNTc4IC0wLjg0NjYwNSwxLjI2NDQ4IC0wLjY1MTIzNCwwLjYyOTUyNjYgLTEuNTYyOTYyLDAuODk1NDQ3MyAtMC45MTE3MjgsMC4yNjA0OTM3IC0yLjczNTE4NSwwLjI2MDQ5MzcgaCAtMi4yMDMzNDMgeiBtIC04LjE0NTg1NjUsMCBoIDMuNDY3ODIzIHEgMS41NDY2ODE2LDAgMi4zNzE1Nzg1LDAuNjg5MjIzIDAuODMwMzI0LDAuNjgzNzk2MSAwLjgzMDMyNCwxLjk1MzcwMzE0IDAsMS4yNzUzMzM5NyAtMC44MzAzMjQsMS45NjQ1NTcwNiBRIDkuOTg3MTk2MSwyLjI3NDkxNSA4LjQ0MDUxNDUsMi4yNzQ5MTUgSCA3LjA2MjA2ODQgViA1LjA4NjA3NjcgSCA0Ljk3MjY5MTUgWiBtIDIuMDg5Mzc2OSwxLjUxNDExOTkgdiAyLjI2MzAzOTQzIGggMS4xNTU5NDEgcSAwLjYwNzgxODgsMCAwLjkzODg2MjksLTAuMjkzMDU1NDcgMC4zMzEwNDQxLC0wLjI5ODQ4MjQxIDAuMzMxMDQ0MSwtMC44NDExNzc3MiAwLC0wLjU0MjY5NTMxIC0wLjMzMTA0NDEsLTAuODM1NzUwNzQgLTAuMzMxMDQ0MSwtMC4yOTMwNTU1IC0wLjkzODg2MjksLTAuMjkzMDU1NSB6IgovPgo8L3N2Zz4K);
  --jp-icon-python: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iLTEwIC0xMCAxMzEuMTYxMzYxNjk0MzM1OTQgMTMyLjM4ODk5OTkzODk2NDg0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMzA2OTk4IiBkPSJNIDU0LjkxODc4NSw5LjE5Mjc0MjFlLTQgQyA1MC4zMzUxMzIsMC4wMjIyMTcyNyA0NS45NTc4NDYsMC40MTMxMzY5NyA0Mi4xMDYyODUsMS4wOTQ2NjkzIDMwLjc2MDA2OSwzLjA5OTE3MzEgMjguNzAwMDM2LDcuMjk0NzcxNCAyOC43MDAwMzUsMTUuMDMyMTY5IHYgMTAuMjE4NzUgaCAyNi44MTI1IHYgMy40MDYyNSBoIC0yNi44MTI1IC0xMC4wNjI1IGMgLTcuNzkyNDU5LDAgLTE0LjYxNTc1ODgsNC42ODM3MTcgLTE2Ljc0OTk5OTgsMTMuNTkzNzUgLTIuNDYxODE5OTgsMTAuMjEyOTY2IC0yLjU3MTAxNTA4LDE2LjU4NjAyMyAwLDI3LjI1IDEuOTA1OTI4Myw3LjkzNzg1MiA2LjQ1NzU0MzIsMTMuNTkzNzQ4IDE0LjI0OTk5OTgsMTMuNTkzNzUgaCA5LjIxODc1IHYgLTEyLjI1IGMgMCwtOC44NDk5MDIgNy42NTcxNDQsLTE2LjY1NjI0OCAxNi43NSwtMTYuNjU2MjUgaCAyNi43ODEyNSBjIDcuNDU0OTUxLDAgMTMuNDA2MjUzLC02LjEzODE2NCAxMy40MDYyNSwtMTMuNjI1IHYgLTI1LjUzMTI1IGMgMCwtNy4yNjYzMzg2IC02LjEyOTk4LC0xMi43MjQ3NzcxIC0xMy40MDYyNSwtMTMuOTM3NDk5NyBDIDY0LjI4MTU0OCwwLjMyNzk0Mzk3IDU5LjUwMjQzOCwtMC4wMjAzNzkwMyA1NC45MTg3ODUsOS4xOTI3NDIxZS00IFogbSAtMTQuNSw4LjIxODc1MDEyNTc5IGMgMi43Njk1NDcsMCA1LjAzMTI1LDIuMjk4NjQ1NiA1LjAzMTI1LDUuMTI0OTk5NiAtMmUtNiwyLjgxNjMzNiAtMi4yNjE3MDMsNS4wOTM3NSAtNS4wMzEyNSw1LjA5Mzc1IC0yLjc3OTQ3NiwtMWUtNiAtNS4wMzEyNSwtMi4yNzc0MTUgLTUuMDMxMjUsLTUuMDkzNzUgLTEwZS03LC0yLjgyNjM1MyAyLjI1MTc3NCwtNS4xMjQ5OTk2IDUuMDMxMjUsLTUuMTI0OTk5NiB6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2ZmZDQzYiIgZD0ibSA4NS42Mzc1MzUsMjguNjU3MTY5IHYgMTEuOTA2MjUgYyAwLDkuMjMwNzU1IC03LjgyNTg5NSwxNi45OTk5OTkgLTE2Ljc1LDE3IGggLTI2Ljc4MTI1IGMgLTcuMzM1ODMzLDAgLTEzLjQwNjI0OSw2LjI3ODQ4MyAtMTMuNDA2MjUsMTMuNjI1IHYgMjUuNTMxMjQ3IGMgMCw3LjI2NjM0NCA2LjMxODU4OCwxMS41NDAzMjQgMTMuNDA2MjUsMTMuNjI1MDA0IDguNDg3MzMxLDIuNDk1NjEgMTYuNjI2MjM3LDIuOTQ2NjMgMjYuNzgxMjUsMCA2Ljc1MDE1NSwtMS45NTQzOSAxMy40MDYyNTMsLTUuODg3NjEgMTMuNDA2MjUsLTEzLjYyNTAwNCBWIDg2LjUwMDkxOSBoIC0yNi43ODEyNSB2IC0zLjQwNjI1IGggMjYuNzgxMjUgMTMuNDA2MjU0IGMgNy43OTI0NjEsMCAxMC42OTYyNTEsLTUuNDM1NDA4IDEzLjQwNjI0MSwtMTMuNTkzNzUgMi43OTkzMywtOC4zOTg4ODYgMi42ODAyMiwtMTYuNDc1Nzc2IDAsLTI3LjI1IC0xLjkyNTc4LC03Ljc1NzQ0MSAtNS42MDM4NywtMTMuNTkzNzUgLTEzLjQwNjI0MSwtMTMuNTkzNzUgeiBtIC0xNS4wNjI1LDY0LjY1NjI1IGMgMi43Nzk0NzgsM2UtNiA1LjAzMTI1LDIuMjc3NDE3IDUuMDMxMjUsNS4wOTM3NDcgLTJlLTYsMi44MjYzNTQgLTIuMjUxNzc1LDUuMTI1MDA0IC01LjAzMTI1LDUuMTI1MDA0IC0yLjc2OTU1LDAgLTUuMDMxMjUsLTIuMjk4NjUgLTUuMDMxMjUsLTUuMTI1MDA0IDJlLTYsLTIuODE2MzMgMi4yNjE2OTcsLTUuMDkzNzQ3IDUuMDMxMjUsLTUuMDkzNzQ3IHoiLz4KPC9zdmc+Cg==);
  --jp-icon-r-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjE5NkYzIiBkPSJNNC40IDIuNWMxLjItLjEgMi45LS4zIDQuOS0uMyAyLjUgMCA0LjEuNCA1LjIgMS4zIDEgLjcgMS41IDEuOSAxLjUgMy41IDAgMi0xLjQgMy41LTIuOSA0LjEgMS4yLjQgMS43IDEuNiAyLjIgMyAuNiAxLjkgMSAzLjkgMS4zIDQuNmgtMy44Yy0uMy0uNC0uOC0xLjctMS4yLTMuN3MtMS4yLTIuNi0yLjYtMi42aC0uOXY2LjRINC40VjIuNXptMy43IDYuOWgxLjRjMS45IDAgMi45LS45IDIuOS0yLjNzLTEtMi4zLTIuOC0yLjNjLS43IDAtMS4zIDAtMS42LjJ2NC41aC4xdi0uMXoiLz4KPC9zdmc+Cg==);
  --jp-icon-react: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMTUwIDE1MCA1NDEuOSAyOTUuMyI+CiAgPGcgY2xhc3M9ImpwLWljb24tYnJhbmQyIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxREFGQiI+CiAgICA8cGF0aCBkPSJNNjY2LjMgMjk2LjVjMC0zMi41LTQwLjctNjMuMy0xMDMuMS04Mi40IDE0LjQtNjMuNiA4LTExNC4yLTIwLjItMTMwLjQtNi41LTMuOC0xNC4xLTUuNi0yMi40LTUuNnYyMi4zYzQuNiAwIDguMy45IDExLjQgMi42IDEzLjYgNy44IDE5LjUgMzcuNSAxNC45IDc1LjctMS4xIDkuNC0yLjkgMTkuMy01LjEgMjkuNC0xOS42LTQuOC00MS04LjUtNjMuNS0xMC45LTEzLjUtMTguNS0yNy41LTM1LjMtNDEuNi01MCAzMi42LTMwLjMgNjMuMi00Ni45IDg0LTQ2LjlWNzhjLTI3LjUgMC02My41IDE5LjYtOTkuOSA1My42LTM2LjQtMzMuOC03Mi40LTUzLjItOTkuOS01My4ydjIyLjNjMjAuNyAwIDUxLjQgMTYuNSA4NCA0Ni42LTE0IDE0LjctMjggMzEuNC00MS4zIDQ5LjktMjIuNiAyLjQtNDQgNi4xLTYzLjYgMTEtMi4zLTEwLTQtMTkuNy01LjItMjktNC43LTM4LjIgMS4xLTY3LjkgMTQuNi03NS44IDMtMS44IDYuOS0yLjYgMTEuNS0yLjZWNzguNWMtOC40IDAtMTYgMS44LTIyLjYgNS42LTI4LjEgMTYuMi0zNC40IDY2LjctMTkuOSAxMzAuMS02Mi4yIDE5LjItMTAyLjcgNDkuOS0xMDIuNyA4Mi4zIDAgMzIuNSA0MC43IDYzLjMgMTAzLjEgODIuNC0xNC40IDYzLjYtOCAxMTQuMiAyMC4yIDEzMC40IDYuNSAzLjggMTQuMSA1LjYgMjIuNSA1LjYgMjcuNSAwIDYzLjUtMTkuNiA5OS45LTUzLjYgMzYuNCAzMy44IDcyLjQgNTMuMiA5OS45IDUzLjIgOC40IDAgMTYtMS44IDIyLjYtNS42IDI4LjEtMTYuMiAzNC40LTY2LjcgMTkuOS0xMzAuMSA2Mi0xOS4xIDEwMi41LTQ5LjkgMTAyLjUtODIuM3ptLTEzMC4yLTY2LjdjLTMuNyAxMi45LTguMyAyNi4yLTEzLjUgMzkuNS00LjEtOC04LjQtMTYtMTMuMS0yNC00LjYtOC05LjUtMTUuOC0xNC40LTIzLjQgMTQuMiAyLjEgMjcuOSA0LjcgNDEgNy45em0tNDUuOCAxMDYuNWMtNy44IDEzLjUtMTUuOCAyNi4zLTI0LjEgMzguMi0xNC45IDEuMy0zMCAyLTQ1LjIgMi0xNS4xIDAtMzAuMi0uNy00NS0xLjktOC4zLTExLjktMTYuNC0yNC42LTI0LjItMzgtNy42LTEzLjEtMTQuNS0yNi40LTIwLjgtMzkuOCA2LjItMTMuNCAxMy4yLTI2LjggMjAuNy0zOS45IDcuOC0xMy41IDE1LjgtMjYuMyAyNC4xLTM4LjIgMTQuOS0xLjMgMzAtMiA0NS4yLTIgMTUuMSAwIDMwLjIuNyA0NSAxLjkgOC4zIDExLjkgMTYuNCAyNC42IDI0LjIgMzggNy42IDEzLjEgMTQuNSAyNi40IDIwLjggMzkuOC02LjMgMTMuNC0xMy4yIDI2LjgtMjAuNyAzOS45em0zMi4zLTEzYzUuNCAxMy40IDEwIDI2LjggMTMuOCAzOS44LTEzLjEgMy4yLTI2LjkgNS45LTQxLjIgOCA0LjktNy43IDkuOC0xNS42IDE0LjQtMjMuNyA0LjYtOCA4LjktMTYuMSAxMy0yNC4xek00MjEuMiA0MzBjLTkuMy05LjYtMTguNi0yMC4zLTI3LjgtMzIgOSAuNCAxOC4yLjcgMjcuNS43IDkuNCAwIDE4LjctLjIgMjcuOC0uNy05IDExLjctMTguMyAyMi40LTI3LjUgMzJ6bS03NC40LTU4LjljLTE0LjItMi4xLTI3LjktNC43LTQxLTcuOSAzLjctMTIuOSA4LjMtMjYuMiAxMy41LTM5LjUgNC4xIDggOC40IDE2IDEzLjEgMjQgNC43IDggOS41IDE1LjggMTQuNCAyMy40ek00MjAuNyAxNjNjOS4zIDkuNiAxOC42IDIwLjMgMjcuOCAzMi05LS40LTE4LjItLjctMjcuNS0uNy05LjQgMC0xOC43LjItMjcuOC43IDktMTEuNyAxOC4zLTIyLjQgMjcuNS0zMnptLTc0IDU4LjljLTQuOSA3LjctOS44IDE1LjYtMTQuNCAyMy43LTQuNiA4LTguOSAxNi0xMyAyNC01LjQtMTMuNC0xMC0yNi44LTEzLjgtMzkuOCAxMy4xLTMuMSAyNi45LTUuOCA0MS4yLTcuOXptLTkwLjUgMTI1LjJjLTM1LjQtMTUuMS01OC4zLTM0LjktNTguMy01MC42IDAtMTUuNyAyMi45LTM1LjYgNTguMy01MC42IDguNi0zLjcgMTgtNyAyNy43LTEwLjEgNS43IDE5LjYgMTMuMiA0MCAyMi41IDYwLjktOS4yIDIwLjgtMTYuNiA0MS4xLTIyLjIgNjAuNi05LjktMy4xLTE5LjMtNi41LTI4LTEwLjJ6TTMxMCA0OTBjLTEzLjYtNy44LTE5LjUtMzcuNS0xNC45LTc1LjcgMS4xLTkuNCAyLjktMTkuMyA1LjEtMjkuNCAxOS42IDQuOCA0MSA4LjUgNjMuNSAxMC45IDEzLjUgMTguNSAyNy41IDM1LjMgNDEuNiA1MC0zMi42IDMwLjMtNjMuMiA0Ni45LTg0IDQ2LjktNC41LS4xLTguMy0xLTExLjMtMi43em0yMzcuMi03Ni4yYzQuNyAzOC4yLTEuMSA2Ny45LTE0LjYgNzUuOC0zIDEuOC02LjkgMi42LTExLjUgMi42LTIwLjcgMC01MS40LTE2LjUtODQtNDYuNiAxNC0xNC43IDI4LTMxLjQgNDEuMy00OS45IDIyLjYtMi40IDQ0LTYuMSA2My42LTExIDIuMyAxMC4xIDQuMSAxOS44IDUuMiAyOS4xem0zOC41LTY2LjdjLTguNiAzLjctMTggNy0yNy43IDEwLjEtNS43LTE5LjYtMTMuMi00MC0yMi41LTYwLjkgOS4yLTIwLjggMTYuNi00MS4xIDIyLjItNjAuNiA5LjkgMy4xIDE5LjMgNi41IDI4LjEgMTAuMiAzNS40IDE1LjEgNTguMyAzNC45IDU4LjMgNTAuNi0uMSAxNS43LTIzIDM1LjYtNTguNCA1MC42ek0zMjAuOCA3OC40eiIvPgogICAgPGNpcmNsZSBjeD0iNDIwLjkiIGN5PSIyOTYuNSIgcj0iNDUuNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-redo: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTE4LjQgMTAuNkMxNi41NSA4Ljk5IDE0LjE1IDggMTEuNSA4Yy00LjY1IDAtOC41OCAzLjAzLTkuOTYgNy4yMkwzLjkgMTZjMS4wNS0zLjE5IDQuMDUtNS41IDcuNi01LjUgMS45NSAwIDMuNzMuNzIgNS4xMiAxLjg4TDEzIDE2aDlWN2wtMy42IDMuNnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-refresh: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTkgMTMuNWMtMi40OSAwLTQuNS0yLjAxLTQuNS00LjVTNi41MSA0LjUgOSA0LjVjMS4yNCAwIDIuMzYuNTIgMy4xNyAxLjMzTDEwIDhoNVYzbC0xLjc2IDEuNzZDMTIuMTUgMy42OCAxMC42NiAzIDkgMyA1LjY5IDMgMy4wMSA1LjY5IDMuMDEgOVM1LjY5IDE1IDkgMTVjMi45NyAwIDUuNDMtMi4xNiA1LjktNWgtMS41MmMtLjQ2IDItMi4yNCAzLjUtNC4zOCAzLjV6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-regex: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiBmaWxsPSIjRkZGIj4KICAgIDxjaXJjbGUgY2xhc3M9InN0MiIgY3g9IjUuNSIgY3k9IjE0LjUiIHI9IjEuNSIvPgogICAgPHJlY3QgeD0iMTIiIHk9IjQiIGNsYXNzPSJzdDIiIHdpZHRoPSIxIiBoZWlnaHQ9IjgiLz4KICAgIDxyZWN0IHg9IjguNSIgeT0iNy41IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjg2NiAtMC41IDAuNSAwLjg2NiAtMi4zMjU1IDcuMzIxOSkiIGNsYXNzPSJzdDIiIHdpZHRoPSI4IiBoZWlnaHQ9IjEiLz4KICAgIDxyZWN0IHg9IjEyIiB5PSI0IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjUgLTAuODY2IDAuODY2IDAuNSAtMC42Nzc5IDE0LjgyNTIpIiBjbGFzcz0ic3QyIiB3aWR0aD0iMSIgaGVpZ2h0PSI4Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-run: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTggNXYxNGwxMS03eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-running: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMjU2IDhDMTE5IDggOCAxMTkgOCAyNTZzMTExIDI0OCAyNDggMjQ4IDI0OC0xMTEgMjQ4LTI0OFMzOTMgOCAyNTYgOHptOTYgMzI4YzAgOC44LTcuMiAxNi0xNiAxNkgxNzZjLTguOCAwLTE2LTcuMi0xNi0xNlYxNzZjMC04LjggNy4yLTE2IDE2LTE2aDE2MGM4LjggMCAxNiA3LjIgMTYgMTZ2MTYweiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-save: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE3IDNINWMtMS4xMSAwLTIgLjktMiAydjE0YzAgMS4xLjg5IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjdsLTQtNHptLTUgMTZjLTEuNjYgMC0zLTEuMzQtMy0zczEuMzQtMyAzLTMgMyAxLjM0IDMgMy0xLjM0IDMtMyAzem0zLTEwSDVWNWgxMHY0eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-search: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-settings: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVBLjQ4OC40ODggMCAwMDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz4KPC9zdmc+Cg==);
  --jp-icon-share: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTSAxOCAyIEMgMTYuMzU0OTkgMiAxNSAzLjM1NDk5MDQgMTUgNSBDIDE1IDUuMTkwOTUyOSAxNS4wMjE3OTEgNS4zNzcxMjI0IDE1LjA1NjY0MSA1LjU1ODU5MzggTCA3LjkyMTg3NSA5LjcyMDcwMzEgQyA3LjM5ODUzOTkgOS4yNzc4NTM5IDYuNzMyMDc3MSA5IDYgOSBDIDQuMzU0OTkwNCA5IDMgMTAuMzU0OTkgMyAxMiBDIDMgMTMuNjQ1MDEgNC4zNTQ5OTA0IDE1IDYgMTUgQyA2LjczMjA3NzEgMTUgNy4zOTg1Mzk5IDE0LjcyMjE0NiA3LjkyMTg3NSAxNC4yNzkyOTcgTCAxNS4wNTY2NDEgMTguNDM5NDUzIEMgMTUuMDIxNTU1IDE4LjYyMTUxNCAxNSAxOC44MDgzODYgMTUgMTkgQyAxNSAyMC42NDUwMSAxNi4zNTQ5OSAyMiAxOCAyMiBDIDE5LjY0NTAxIDIyIDIxIDIwLjY0NTAxIDIxIDE5IEMgMjEgMTcuMzU0OTkgMTkuNjQ1MDEgMTYgMTggMTYgQyAxNy4yNjc0OCAxNiAxNi42MDE1OTMgMTYuMjc5MzI4IDE2LjA3ODEyNSAxNi43MjI2NTYgTCA4Ljk0MzM1OTQgMTIuNTU4NTk0IEMgOC45NzgyMDk1IDEyLjM3NzEyMiA5IDEyLjE5MDk1MyA5IDEyIEMgOSAxMS44MDkwNDcgOC45NzgyMDk1IDExLjYyMjg3OCA4Ljk0MzM1OTQgMTEuNDQxNDA2IEwgMTYuMDc4MTI1IDcuMjc5Mjk2OSBDIDE2LjYwMTQ2IDcuNzIyMTQ2MSAxNy4yNjc5MjMgOCAxOCA4IEMgMTkuNjQ1MDEgOCAyMSA2LjY0NTAwOTYgMjEgNSBDIDIxIDMuMzU0OTkwNCAxOS42NDUwMSAyIDE4IDIgeiBNIDE4IDQgQyAxOC41NjQxMjkgNCAxOSA0LjQzNTg3MDYgMTkgNSBDIDE5IDUuNTY0MTI5NCAxOC41NjQxMjkgNiAxOCA2IEMgMTcuNDM1ODcxIDYgMTcgNS41NjQxMjk0IDE3IDUgQyAxNyA0LjQzNTg3MDYgMTcuNDM1ODcxIDQgMTggNCB6IE0gNiAxMSBDIDYuNTY0MTI5NCAxMSA3IDExLjQzNTg3MSA3IDEyIEMgNyAxMi41NjQxMjkgNi41NjQxMjk0IDEzIDYgMTMgQyA1LjQzNTg3MDYgMTMgNSAxMi41NjQxMjkgNSAxMiBDIDUgMTEuNDM1ODcxIDUuNDM1ODcwNiAxMSA2IDExIHogTSAxOCAxOCBDIDE4LjU2NDEyOSAxOCAxOSAxOC40MzU4NzEgMTkgMTkgQyAxOSAxOS41NjQxMjkgMTguNTY0MTI5IDIwIDE4IDIwIEMgMTcuNDM1ODcxIDIwIDE3IDE5LjU2NDEyOSAxNyAxOSBDIDE3IDE4LjQzNTg3MSAxNy40MzU4NzEgMTggMTggMTggeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-spreadsheet: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNENBRjUwIiBkPSJNMi4yIDIuMnYxNy42aDE3LjZWMi4ySDIuMnptMTUuNCA3LjdoLTUuNVY0LjRoNS41djUuNXpNOS45IDQuNHY1LjVINC40VjQuNGg1LjV6bS01LjUgNy43aDUuNXY1LjVINC40di01LjV6bTcuNyA1LjV2LTUuNWg1LjV2NS41aC01LjV6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-stop: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik02IDZoMTJ2MTJINnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tab: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIxIDNIM2MtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxOGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yem0wIDE2SDNWNWgxMHY0aDh2MTB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-table-rows: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMSw4SDNWNGgxOFY4eiBNMjEsMTBIM3Y0aDE4VjEweiBNMjEsMTZIM3Y0aDE4VjE2eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-tag: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjgiIGhlaWdodD0iMjgiIHZpZXdCb3g9IjAgMCA0MyAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTI4LjgzMzIgMTIuMzM0TDMyLjk5OTggMTYuNTAwN0wzNy4xNjY1IDEyLjMzNEgyOC44MzMyWiIvPgoJCTxwYXRoIGQ9Ik0xNi4yMDk1IDIxLjYxMDRDMTUuNjg3MyAyMi4xMjk5IDE0Ljg0NDMgMjIuMTI5OSAxNC4zMjQ4IDIxLjYxMDRMNi45ODI5IDE0LjcyNDVDNi41NzI0IDE0LjMzOTQgNi4wODMxMyAxMy42MDk4IDYuMDQ3ODYgMTMuMDQ4MkM1Ljk1MzQ3IDExLjUyODggNi4wMjAwMiA4LjYxOTQ0IDYuMDY2MjEgNy4wNzY5NUM2LjA4MjgxIDYuNTE0NzcgNi41NTU0OCA2LjA0MzQ3IDcuMTE4MDQgNi4wMzA1NUM5LjA4ODYzIDUuOTg0NzMgMTMuMjYzOCA1LjkzNTc5IDEzLjY1MTggNi4zMjQyNUwyMS43MzY5IDEzLjYzOUMyMi4yNTYgMTQuMTU4NSAyMS43ODUxIDE1LjQ3MjQgMjEuMjYyIDE1Ljk5NDZMMTYuMjA5NSAyMS42MTA0Wk05Ljc3NTg1IDguMjY1QzkuMzM1NTEgNy44MjU2NiA4LjYyMzUxIDcuODI1NjYgOC4xODI4IDguMjY1QzcuNzQzNDYgOC43MDU3MSA3Ljc0MzQ2IDkuNDE3MzMgOC4xODI4IDkuODU2NjdDOC42MjM4MiAxMC4yOTY0IDkuMzM1ODIgMTAuMjk2NCA5Ljc3NTg1IDkuODU2NjdDMTAuMjE1NiA5LjQxNzMzIDEwLjIxNTYgOC43MDUzMyA5Ljc3NTg1IDguMjY1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-terminal: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0IiA+CiAgICA8cmVjdCBjbGFzcz0ianAtdGVybWluYWwtaWNvbi1iYWNrZ3JvdW5kLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZSIgd2lkdGg9IjIwIiBoZWlnaHQ9IjIwIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgyIDIpIiBmaWxsPSIjMzMzMzMzIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtdGVybWluYWwtaWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUtaW52ZXJzZSIgZD0iTTUuMDU2NjQgOC43NjE3MkM1LjA1NjY0IDguNTk3NjYgNS4wMzEyNSA4LjQ1MzEyIDQuOTgwNDcgOC4zMjgxMkM0LjkzMzU5IDguMTk5MjIgNC44NTU0NyA4LjA4MjAzIDQuNzQ2MDkgNy45NzY1NkM0LjY0MDYyIDcuODcxMDkgNC41IDcuNzc1MzkgNC4zMjQyMiA3LjY4OTQ1QzQuMTUyMzQgNy41OTk2MSAzLjk0MzM2IDcuNTExNzIgMy42OTcyNyA3LjQyNTc4QzMuMzAyNzMgNy4yODUxNiAyLjk0MzM2IDcuMTM2NzIgMi42MTkxNCA2Ljk4MDQ3QzIuMjk0OTIgNi44MjQyMiAyLjAxNzU4IDYuNjQyNTggMS43ODcxMSA2LjQzNTU1QzEuNTYwNTUgNi4yMjg1MiAxLjM4NDc3IDUuOTg4MjggMS4yNTk3NyA1LjcxNDg0QzEuMTM0NzcgNS40Mzc1IDEuMDcyMjcgNS4xMDkzOCAxLjA3MjI3IDQuNzMwNDdDMS4wNzIyNyA0LjM5ODQ0IDEuMTI4OTEgNC4wOTU3IDEuMjQyMTkgMy44MjIyN0MxLjM1NTQ3IDMuNTQ0OTIgMS41MTU2MiAzLjMwNDY5IDEuNzIyNjYgMy4xMDE1NkMxLjkyOTY5IDIuODk4NDQgMi4xNzk2OSAyLjczNDM3IDIuNDcyNjYgMi42MDkzOEMyLjc2NTYyIDIuNDg0MzggMy4wOTE4IDIuNDA0MyAzLjQ1MTE3IDIuMzY5MTRWMS4xMDkzOEg0LjM4ODY3VjIuMzgwODZDNC43NDAyMyAyLjQyNzczIDUuMDU2NjQgMi41MjM0NCA1LjMzNzg5IDIuNjY3OTdDNS42MTkxNCAyLjgxMjUgNS44NTc0MiAzLjAwMTk1IDYuMDUyNzMgMy4yMzYzM0M2LjI1MTk1IDMuNDY2OCA2LjQwNDMgMy43NDAyMyA2LjUwOTc3IDQuMDU2NjRDNi42MTkxNCA0LjM2OTE0IDYuNjczODMgNC43MjA3IDYuNjczODMgNS4xMTEzM0g1LjA0NDkyQzUuMDQ0OTIgNC42Mzg2NyA0LjkzNzUgNC4yODEyNSA0LjcyMjY2IDQuMDM5MDZDNC41MDc4MSAzLjc5Mjk3IDQuMjE2OCAzLjY2OTkyIDMuODQ5NjEgMy42Njk5MkMzLjY1MDM5IDMuNjY5OTIgMy40NzY1NiAzLjY5NzI3IDMuMzI4MTIgMy43NTE5NUMzLjE4MzU5IDMuODAyNzMgMy4wNjQ0NSAzLjg3Njk1IDIuOTcwNyAzLjk3NDYxQzIuODc2OTUgNC4wNjgzNiAyLjgwNjY0IDQuMTc5NjkgMi43NTk3NyA0LjMwODU5QzIuNzE2OCA0LjQzNzUgMi42OTUzMSA0LjU3ODEyIDIuNjk1MzEgNC43MzA0N0MyLjY5NTMxIDQuODgyODEgMi43MTY4IDUuMDE5NTMgMi43NTk3NyA1LjE0MDYyQzIuODA2NjQgNS4yNTc4MSAyLjg4MjgxIDUuMzY3MTkgMi45ODgyOCA1LjQ2ODc1QzMuMDk3NjYgNS41NzAzMSAzLjI0MDIzIDUuNjY3OTcgMy40MTYwMiA1Ljc2MTcyQzMuNTkxOCA1Ljg1MTU2IDMuODEwNTUgNS45NDMzNiA0LjA3MjI3IDYuMDM3MTFDNC40NjY4IDYuMTg1NTUgNC44MjQyMiA2LjMzOTg0IDUuMTQ0NTMgNi41QzUuNDY0ODQgNi42NTYyNSA1LjczODI4IDYuODM5ODQgNS45NjQ4NCA3LjA1MDc4QzYuMTk1MzEgNy4yNTc4MSA2LjM3MTA5IDcuNSA2LjQ5MjE5IDcuNzc3MzRDNi42MTcxOSA4LjA1MDc4IDYuNjc5NjkgOC4zNzUgNi42Nzk2OSA4Ljc1QzYuNjc5NjkgOS4wOTM3NSA2LjYyMzA1IDkuNDA0MyA2LjUwOTc3IDkuNjgxNjRDNi4zOTY0OCA5Ljk1NTA4IDYuMjM0MzggMTAuMTkxNCA2LjAyMzQ0IDEwLjM5MDZDNS44MTI1IDEwLjU4OTggNS41NTg1OSAxMC43NSA1LjI2MTcyIDEwLjg3MTFDNC45NjQ4NCAxMC45ODgzIDQuNjMyODEgMTEuMDY0NSA0LjI2NTYyIDExLjA5OTZWMTIuMjQ4SDMuMzMzOThWMTEuMDk5NkMzLjAwMTk1IDExLjA2ODQgMi42Nzk2OSAxMC45OTYxIDIuMzY3MTkgMTAuODgyOEMyLjA1NDY5IDEwLjc2NTYgMS43NzczNCAxMC41OTc3IDEuNTM1MTYgMTAuMzc4OUMxLjI5Njg4IDEwLjE2MDIgMS4xMDU0NyA5Ljg4NDc3IDAuOTYwOTM4IDkuNTUyNzNDMC44MTY0MDYgOS4yMTY4IDAuNzQ0MTQxIDguODE0NDUgMC43NDQxNDEgOC4zNDU3SDIuMzc4OTFDMi4zNzg5MSA4LjYyNjk1IDIuNDE5OTIgOC44NjMyOCAyLjUwMTk1IDkuMDU0NjlDMi41ODM5OCA5LjI0MjE5IDIuNjg5NDUgOS4zOTI1OCAyLjgxODM2IDkuNTA1ODZDMi45NTExNyA5LjYxNTIzIDMuMTAxNTYgOS42OTMzNiAzLjI2OTUzIDkuNzQwMjNDMy40Mzc1IDkuNzg3MTEgMy42MDkzOCA5LjgxMDU1IDMuNzg1MTYgOS44MTA1NUM0LjIwMzEyIDkuODEwNTUgNC41MTk1MyA5LjcxMjg5IDQuNzM0MzggOS41MTc1OEM0Ljk0OTIyIDkuMzIyMjcgNS4wNTY2NCA5LjA3MDMxIDUuMDU2NjQgOC43NjE3MlpNMTMuNDE4IDEyLjI3MTVIOC4wNzQyMlYxMUgxMy40MThWMTIuMjcxNVoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMuOTUyNjQgNikiIGZpbGw9IndoaXRlIi8+Cjwvc3ZnPgo=);
  --jp-icon-text-editor: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtdGV4dC1lZGl0b3ItaWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xNSAxNUgzdjJoMTJ2LTJ6bTAtOEgzdjJoMTJWN3pNMyAxM2gxOHYtMkgzdjJ6bTAgOGgxOHYtMkgzdjJ6TTMgM3YyaDE4VjNIM3oiLz4KPC9zdmc+Cg==);
  --jp-icon-toc: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik03LDVIMjFWN0g3VjVNNywxM1YxMUgyMVYxM0g3TTQsNC41QTEuNSwxLjUgMCAwLDEgNS41LDZBMS41LDEuNSAwIDAsMSA0LDcuNUExLjUsMS41IDAgMCwxIDIuNSw2QTEuNSwxLjUgMCAwLDEgNCw0LjVNNCwxMC41QTEuNSwxLjUgMCAwLDEgNS41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMy41QTEuNSwxLjUgMCAwLDEgMi41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMC41TTcsMTlWMTdIMjFWMTlIN000LDE2LjVBMS41LDEuNSAwIDAsMSA1LjUsMThBMS41LDEuNSAwIDAsMSA0LDE5LjVBMS41LDEuNSAwIDAsMSAyLjUsMThBMS41LDEuNSAwIDAsMSA0LDE2LjVaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tree-view: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMiAxMVYzaC03djNIOVYzSDJ2OGg3VjhoMnYxMGg0djNoN3YtOGgtN3YzaC0yVjhoMnYzeiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMiAxNy4xODQ0IDIuOTY5NjggMTQuMzAzMiAxLjg2MDk0IDExLjQ0MDlaIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiMzMzMzMzMiIHN0cm9rZT0iIzMzMzMzMyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOCA5Ljg2NzE5KSIgZD0iTTIuODYwMTUgNC44NjUzNUwwLjcyNjU0OSAyLjk5OTU5TDAgMy42MzA0NUwyLjg2MDE1IDYuMTMxNTdMOCAwLjYzMDg3Mkw3LjI3ODU3IDBMMi44NjAxNSA0Ljg2NTM1WiIvPgo8L3N2Zz4K);
  --jp-icon-undo: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjUgOGMtMi42NSAwLTUuMDUuOTktNi45IDIuNkwyIDd2OWg5bC0zLjYyLTMuNjJjMS4zOS0xLjE2IDMuMTYtMS44OCA1LjEyLTEuODggMy41NCAwIDYuNTUgMi4zMSA3LjYgNS41bDIuMzctLjc4QzIxLjA4IDExLjAzIDE3LjE1IDggMTIuNSA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-user: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE2IDdhNCA0IDAgMTEtOCAwIDQgNCAwIDAxOCAwek0xMiAxNGE3IDcgMCAwMC03IDdoMTRhNyA3IDAgMDAtNy03eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-users: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZlcnNpb249IjEuMSIgdmlld0JveD0iMCAwIDM2IDI0IiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgogPGcgY2xhc3M9ImpwLWljb24zIiB0cmFuc2Zvcm09Im1hdHJpeCgxLjczMjcgMCAwIDEuNzMyNyAtMy42MjgyIC4wOTk1NzcpIiBmaWxsPSIjNjE2MTYxIj4KICA8cGF0aCB0cmFuc2Zvcm09Im1hdHJpeCgxLjUsMCwwLDEuNSwwLC02KSIgZD0ibTEyLjE4NiA3LjUwOThjLTEuMDUzNSAwLTEuOTc1NyAwLjU2NjUtMi40Nzg1IDEuNDEwMiAwLjc1MDYxIDAuMzEyNzcgMS4zOTc0IDAuODI2NDggMS44NzMgMS40NzI3aDMuNDg2M2MwLTEuNTkyLTEuMjg4OS0yLjg4MjgtMi44ODA5LTIuODgyOHoiLz4KICA8cGF0aCBkPSJtMjAuNDY1IDIuMzg5NWEyLjE4ODUgMi4xODg1IDAgMCAxLTIuMTg4NCAyLjE4ODUgMi4xODg1IDIuMTg4NSAwIDAgMS0yLjE4ODUtMi4xODg1IDIuMTg4NSAyLjE4ODUgMCAwIDEgMi4xODg1LTIuMTg4NSAyLjE4ODUgMi4xODg1IDAgMCAxIDIuMTg4NCAyLjE4ODV6Ii8+CiAgPHBhdGggdHJhbnNmb3JtPSJtYXRyaXgoMS41LDAsMCwxLjUsMCwtNikiIGQ9Im0zLjU4OTggOC40MjE5Yy0xLjExMjYgMC0yLjAxMzcgMC45MDExMS0yLjAxMzcgMi4wMTM3aDIuODE0NWMwLjI2Nzk3LTAuMzczMDkgMC41OTA3LTAuNzA0MzUgMC45NTg5OC0wLjk3ODUyLTAuMzQ0MzMtMC42MTY4OC0xLjAwMzEtMS4wMzUyLTEuNzU5OC0xLjAzNTJ6Ii8+CiAgPHBhdGggZD0ibTYuOTE1NCA0LjYyM2ExLjUyOTQgMS41Mjk0IDAgMCAxLTEuNTI5NCAxLjUyOTQgMS41Mjk0IDEuNTI5NCAwIDAgMS0xLjUyOTQtMS41Mjk0IDEuNTI5NCAxLjUyOTQgMCAwIDEgMS41Mjk0LTEuNTI5NCAxLjUyOTQgMS41Mjk0IDAgMCAxIDEuNTI5NCAxLjUyOTR6Ii8+CiAgPHBhdGggZD0ibTYuMTM1IDEzLjUzNWMwLTMuMjM5MiAyLjYyNTktNS44NjUgNS44NjUtNS44NjUgMy4yMzkyIDAgNS44NjUgMi42MjU5IDUuODY1IDUuODY1eiIvPgogIDxjaXJjbGUgY3g9IjEyIiBjeT0iMy43Njg1IiByPSIyLjk2ODUiLz4KIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-vega: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbjEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjEyMTIxIj4KICAgIDxwYXRoIGQ9Ik0xMC42IDUuNGwyLjItMy4ySDIuMnY3LjNsNC02LjZ6Ii8+CiAgICA8cGF0aCBkPSJNMTUuOCAyLjJsLTQuNCA2LjZMNyA2LjNsLTQuOCA4djUuNWgxNy42VjIuMmgtNHptLTcgMTUuNEg1LjV2LTQuNGgzLjN2NC40em00LjQgMEg5LjhWOS44aDMuNHY3Ljh6bTQuNCAwaC0zLjRWNi41aDMuNHYxMS4xeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-word: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KIDxnIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzQxNDE0MSI+CiAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiA8L2c+CiA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSguNDMgLjA0MDEpIiBmaWxsPSIjZmZmIj4KICA8cGF0aCBkPSJtNC4xNCA4Ljc2cTAuMDY4Mi0xLjg5IDIuNDItMS44OSAxLjE2IDAgMS42OCAwLjQyIDAuNTY3IDAuNDEgMC41NjcgMS4xNnYzLjQ3cTAgMC40NjIgMC41MTQgMC40NjIgMC4xMDMgMCAwLjItMC4wMjMxdjAuNzE0cS0wLjM5OSAwLjEwMy0wLjY1MSAwLjEwMy0wLjQ1MiAwLTAuNjkzLTAuMjItMC4yMzEtMC4yLTAuMjg0LTAuNjYyLTAuOTU2IDAuODcyLTIgMC44NzItMC45MDMgMC0xLjQ3LTAuNDcyLTAuNTI1LTAuNDcyLTAuNTI1LTEuMjYgMC0wLjI2MiAwLjA0NTItMC40NzIgMC4wNTY3LTAuMjIgMC4xMTYtMC4zNzggMC4wNjgyLTAuMTY4IDAuMjMxLTAuMzA0IDAuMTU4LTAuMTQ3IDAuMjYyLTAuMjQyIDAuMTE2LTAuMDkxNCAwLjM2OC0wLjE2OCAwLjI2Mi0wLjA5MTQgMC4zOTktMC4xMjYgMC4xMzYtMC4wNDUyIDAuNDcyLTAuMTAzIDAuMzM2LTAuMDU3OCAwLjUwNC0wLjA3OTggMC4xNTgtMC4wMjMxIDAuNTY3LTAuMDc5OCAwLjU1Ni0wLjA2ODIgMC43NzctMC4yMjEgMC4yMi0wLjE1MiAwLjIyLTAuNDQxdi0wLjI1MnEwLTAuNDMtMC4zNTctMC42NjItMC4zMzYtMC4yMzEtMC45NzYtMC4yMzEtMC42NjIgMC0wLjk5OCAwLjI2Mi0wLjMzNiAwLjI1Mi0wLjM5OSAwLjc5OHptMS44OSAzLjY4cTAuNzg4IDAgMS4yNi0wLjQxIDAuNTA0LTAuNDIgMC41MDQtMC45MDN2LTEuMDVxLTAuMjg0IDAuMTM2LTAuODYxIDAuMjMxLTAuNTY3IDAuMDkxNC0wLjk4NyAwLjE1OC0wLjQyIDAuMDY4Mi0wLjc2NiAwLjMyNi0wLjMzNiAwLjI1Mi0wLjMzNiAwLjcwNHQwLjMwNCAwLjcwNCAwLjg2MSAwLjI1MnoiIHN0cm9rZS13aWR0aD0iMS4wNSIvPgogIDxwYXRoIGQ9Im0xMCA0LjU2aDAuOTQ1djMuMTVxMC42NTEtMC45NzYgMS44OS0wLjk3NiAxLjE2IDAgMS44OSAwLjg0IDAuNjgyIDAuODQgMC42ODIgMi4zMSAwIDEuNDctMC43MDQgMi40Mi0wLjcwNCAwLjg4Mi0xLjg5IDAuODgyLTEuMjYgMC0xLjg5LTEuMDJ2MC43NjZoLTAuODV6bTIuNjIgMy4wNHEtMC43NDYgMC0xLjE2IDAuNjQtMC40NTIgMC42My0wLjQ1MiAxLjY4IDAgMS4wNSAwLjQ1MiAxLjY4dDEuMTYgMC42M3EwLjc3NyAwIDEuMjYtMC42MyAwLjQ5NC0wLjY0IDAuNDk0LTEuNjggMC0xLjA1LTAuNDcyLTEuNjgtMC40NjItMC42NC0xLjI2LTAuNjR6IiBzdHJva2Utd2lkdGg9IjEuMDUiLz4KICA8cGF0aCBkPSJtMi43MyAxNS44IDEzLjYgMC4wMDgxYzAuMDA2OSAwIDAtMi42IDAtMi42IDAtMC4wMDc4LTEuMTUgMC0xLjE1IDAtMC4wMDY5IDAtMC4wMDgzIDEuNS0wLjAwODMgMS41LTJlLTMgLTAuMDAxNC0xMS4zLTAuMDAxNC0xMS4zLTAuMDAxNGwtMC4wMDU5Mi0xLjVjMC0wLjAwNzgtMS4xNyAwLjAwMTMtMS4xNyAwLjAwMTN6IiBzdHJva2Utd2lkdGg9Ii45NzUiLz4KIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-yaml: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1jb250cmFzdDIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjRDgxQjYwIj4KICAgIDxwYXRoIGQ9Ik03LjIgMTguNnYtNS40TDMgNS42aDMuM2wxLjQgMy4xYy4zLjkuNiAxLjYgMSAyLjUuMy0uOC42LTEuNiAxLTIuNWwxLjQtMy4xaDMuNGwtNC40IDcuNnY1LjVsLTIuOS0uMXoiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxNi41IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxMSIgcj0iMi4xIi8+CiAgPC9nPgo8L3N2Zz4K);
}

/* Icon CSS class declarations */

.jp-AddAboveIcon {
  background-image: var(--jp-icon-add-above);
}

.jp-AddBelowIcon {
  background-image: var(--jp-icon-add-below);
}

.jp-AddIcon {
  background-image: var(--jp-icon-add);
}

.jp-BellIcon {
  background-image: var(--jp-icon-bell);
}

.jp-BugDotIcon {
  background-image: var(--jp-icon-bug-dot);
}

.jp-BugIcon {
  background-image: var(--jp-icon-bug);
}

.jp-BuildIcon {
  background-image: var(--jp-icon-build);
}

.jp-CaretDownEmptyIcon {
  background-image: var(--jp-icon-caret-down-empty);
}

.jp-CaretDownEmptyThinIcon {
  background-image: var(--jp-icon-caret-down-empty-thin);
}

.jp-CaretDownIcon {
  background-image: var(--jp-icon-caret-down);
}

.jp-CaretLeftIcon {
  background-image: var(--jp-icon-caret-left);
}

.jp-CaretRightIcon {
  background-image: var(--jp-icon-caret-right);
}

.jp-CaretUpEmptyThinIcon {
  background-image: var(--jp-icon-caret-up-empty-thin);
}

.jp-CaretUpIcon {
  background-image: var(--jp-icon-caret-up);
}

.jp-CaseSensitiveIcon {
  background-image: var(--jp-icon-case-sensitive);
}

.jp-CheckIcon {
  background-image: var(--jp-icon-check);
}

.jp-CircleEmptyIcon {
  background-image: var(--jp-icon-circle-empty);
}

.jp-CircleIcon {
  background-image: var(--jp-icon-circle);
}

.jp-ClearIcon {
  background-image: var(--jp-icon-clear);
}

.jp-CloseIcon {
  background-image: var(--jp-icon-close);
}

.jp-CodeCheckIcon {
  background-image: var(--jp-icon-code-check);
}

.jp-CodeIcon {
  background-image: var(--jp-icon-code);
}

.jp-CollapseAllIcon {
  background-image: var(--jp-icon-collapse-all);
}

.jp-ConsoleIcon {
  background-image: var(--jp-icon-console);
}

.jp-CopyIcon {
  background-image: var(--jp-icon-copy);
}

.jp-CopyrightIcon {
  background-image: var(--jp-icon-copyright);
}

.jp-CutIcon {
  background-image: var(--jp-icon-cut);
}

.jp-DeleteIcon {
  background-image: var(--jp-icon-delete);
}

.jp-DownloadIcon {
  background-image: var(--jp-icon-download);
}

.jp-DuplicateIcon {
  background-image: var(--jp-icon-duplicate);
}

.jp-EditIcon {
  background-image: var(--jp-icon-edit);
}

.jp-EllipsesIcon {
  background-image: var(--jp-icon-ellipses);
}

.jp-ErrorIcon {
  background-image: var(--jp-icon-error);
}

.jp-ExpandAllIcon {
  background-image: var(--jp-icon-expand-all);
}

.jp-ExtensionIcon {
  background-image: var(--jp-icon-extension);
}

.jp-FastForwardIcon {
  background-image: var(--jp-icon-fast-forward);
}

.jp-FileIcon {
  background-image: var(--jp-icon-file);
}

.jp-FileUploadIcon {
  background-image: var(--jp-icon-file-upload);
}

.jp-FilterDotIcon {
  background-image: var(--jp-icon-filter-dot);
}

.jp-FilterIcon {
  background-image: var(--jp-icon-filter);
}

.jp-FilterListIcon {
  background-image: var(--jp-icon-filter-list);
}

.jp-FolderFavoriteIcon {
  background-image: var(--jp-icon-folder-favorite);
}

.jp-FolderIcon {
  background-image: var(--jp-icon-folder);
}

.jp-HomeIcon {
  background-image: var(--jp-icon-home);
}

.jp-Html5Icon {
  background-image: var(--jp-icon-html5);
}

.jp-ImageIcon {
  background-image: var(--jp-icon-image);
}

.jp-InfoIcon {
  background-image: var(--jp-icon-info);
}

.jp-InspectorIcon {
  background-image: var(--jp-icon-inspector);
}

.jp-JsonIcon {
  background-image: var(--jp-icon-json);
}

.jp-JuliaIcon {
  background-image: var(--jp-icon-julia);
}

.jp-JupyterFaviconIcon {
  background-image: var(--jp-icon-jupyter-favicon);
}

.jp-JupyterIcon {
  background-image: var(--jp-icon-jupyter);
}

.jp-JupyterlabWordmarkIcon {
  background-image: var(--jp-icon-jupyterlab-wordmark);
}

.jp-KernelIcon {
  background-image: var(--jp-icon-kernel);
}

.jp-KeyboardIcon {
  background-image: var(--jp-icon-keyboard);
}

.jp-LaunchIcon {
  background-image: var(--jp-icon-launch);
}

.jp-LauncherIcon {
  background-image: var(--jp-icon-launcher);
}

.jp-LineFormIcon {
  background-image: var(--jp-icon-line-form);
}

.jp-LinkIcon {
  background-image: var(--jp-icon-link);
}

.jp-ListIcon {
  background-image: var(--jp-icon-list);
}

.jp-MarkdownIcon {
  background-image: var(--jp-icon-markdown);
}

.jp-MoveDownIcon {
  background-image: var(--jp-icon-move-down);
}

.jp-MoveUpIcon {
  background-image: var(--jp-icon-move-up);
}

.jp-NewFolderIcon {
  background-image: var(--jp-icon-new-folder);
}

.jp-NotTrustedIcon {
  background-image: var(--jp-icon-not-trusted);
}

.jp-NotebookIcon {
  background-image: var(--jp-icon-notebook);
}

.jp-NumberingIcon {
  background-image: var(--jp-icon-numbering);
}

.jp-OfflineBoltIcon {
  background-image: var(--jp-icon-offline-bolt);
}

.jp-PaletteIcon {
  background-image: var(--jp-icon-palette);
}

.jp-PasteIcon {
  background-image: var(--jp-icon-paste);
}

.jp-PdfIcon {
  background-image: var(--jp-icon-pdf);
}

.jp-PythonIcon {
  background-image: var(--jp-icon-python);
}

.jp-RKernelIcon {
  background-image: var(--jp-icon-r-kernel);
}

.jp-ReactIcon {
  background-image: var(--jp-icon-react);
}

.jp-RedoIcon {
  background-image: var(--jp-icon-redo);
}

.jp-RefreshIcon {
  background-image: var(--jp-icon-refresh);
}

.jp-RegexIcon {
  background-image: var(--jp-icon-regex);
}

.jp-RunIcon {
  background-image: var(--jp-icon-run);
}

.jp-RunningIcon {
  background-image: var(--jp-icon-running);
}

.jp-SaveIcon {
  background-image: var(--jp-icon-save);
}

.jp-SearchIcon {
  background-image: var(--jp-icon-search);
}

.jp-SettingsIcon {
  background-image: var(--jp-icon-settings);
}

.jp-ShareIcon {
  background-image: var(--jp-icon-share);
}

.jp-SpreadsheetIcon {
  background-image: var(--jp-icon-spreadsheet);
}

.jp-StopIcon {
  background-image: var(--jp-icon-stop);
}

.jp-TabIcon {
  background-image: var(--jp-icon-tab);
}

.jp-TableRowsIcon {
  background-image: var(--jp-icon-table-rows);
}

.jp-TagIcon {
  background-image: var(--jp-icon-tag);
}

.jp-TerminalIcon {
  background-image: var(--jp-icon-terminal);
}

.jp-TextEditorIcon {
  background-image: var(--jp-icon-text-editor);
}

.jp-TocIcon {
  background-image: var(--jp-icon-toc);
}

.jp-TreeViewIcon {
  background-image: var(--jp-icon-tree-view);
}

.jp-TrustedIcon {
  background-image: var(--jp-icon-trusted);
}

.jp-UndoIcon {
  background-image: var(--jp-icon-undo);
}

.jp-UserIcon {
  background-image: var(--jp-icon-user);
}

.jp-UsersIcon {
  background-image: var(--jp-icon-users);
}

.jp-VegaIcon {
  background-image: var(--jp-icon-vega);
}

.jp-WordIcon {
  background-image: var(--jp-icon-word);
}

.jp-YamlIcon {
  background-image: var(--jp-icon-yaml);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

.jp-Icon,
.jp-MaterialIcon {
  background-position: center;
  background-repeat: no-repeat;
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-cover {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/**
 * (DEPRECATED) Support for specific CSS icon sizes
 */

.jp-Icon-16 {
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-18 {
  background-size: 18px;
  min-width: 18px;
  min-height: 18px;
}

.jp-Icon-20 {
  background-size: 20px;
  min-width: 20px;
  min-height: 20px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.lm-TabBar .lm-TabBar-addButton {
  align-items: center;
  display: flex;
  padding: 4px;
  padding-bottom: 5px;
  margin-right: 1px;
  background-color: var(--jp-layout-color2);
}

.lm-TabBar .lm-TabBar-addButton:hover {
  background-color: var(--jp-layout-color1);
}

.lm-DockPanel-tabBar .lm-TabBar-tab {
  width: var(--jp-private-horizontal-tab-width);
}

.lm-DockPanel-tabBar .lm-TabBar-content {
  flex: unset;
}

.lm-DockPanel-tabBar[data-orientation='horizontal'] {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for icons as inline SVG HTMLElements
 */

/* recolor the primary elements of an icon */
.jp-icon0[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon1[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon2[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon3[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-accent0[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-accent1[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-accent2[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-accent3[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-accent4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-accent0[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-accent1[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-accent2[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-accent3[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-accent4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-none[fill] {
  fill: none;
}

.jp-icon-none[stroke] {
  stroke: none;
}

/* brand icon colors. Same for light and dark */
.jp-icon-brand0[fill] {
  fill: var(--jp-brand-color0);
}

.jp-icon-brand1[fill] {
  fill: var(--jp-brand-color1);
}

.jp-icon-brand2[fill] {
  fill: var(--jp-brand-color2);
}

.jp-icon-brand3[fill] {
  fill: var(--jp-brand-color3);
}

.jp-icon-brand4[fill] {
  fill: var(--jp-brand-color4);
}

.jp-icon-brand0[stroke] {
  stroke: var(--jp-brand-color0);
}

.jp-icon-brand1[stroke] {
  stroke: var(--jp-brand-color1);
}

.jp-icon-brand2[stroke] {
  stroke: var(--jp-brand-color2);
}

.jp-icon-brand3[stroke] {
  stroke: var(--jp-brand-color3);
}

.jp-icon-brand4[stroke] {
  stroke: var(--jp-brand-color4);
}

/* warn icon colors. Same for light and dark */
.jp-icon-warn0[fill] {
  fill: var(--jp-warn-color0);
}

.jp-icon-warn1[fill] {
  fill: var(--jp-warn-color1);
}

.jp-icon-warn2[fill] {
  fill: var(--jp-warn-color2);
}

.jp-icon-warn3[fill] {
  fill: var(--jp-warn-color3);
}

.jp-icon-warn0[stroke] {
  stroke: var(--jp-warn-color0);
}

.jp-icon-warn1[stroke] {
  stroke: var(--jp-warn-color1);
}

.jp-icon-warn2[stroke] {
  stroke: var(--jp-warn-color2);
}

.jp-icon-warn3[stroke] {
  stroke: var(--jp-warn-color3);
}

/* icon colors that contrast well with each other and most backgrounds */
.jp-icon-contrast0[fill] {
  fill: var(--jp-icon-contrast-color0);
}

.jp-icon-contrast1[fill] {
  fill: var(--jp-icon-contrast-color1);
}

.jp-icon-contrast2[fill] {
  fill: var(--jp-icon-contrast-color2);
}

.jp-icon-contrast3[fill] {
  fill: var(--jp-icon-contrast-color3);
}

.jp-icon-contrast0[stroke] {
  stroke: var(--jp-icon-contrast-color0);
}

.jp-icon-contrast1[stroke] {
  stroke: var(--jp-icon-contrast-color1);
}

.jp-icon-contrast2[stroke] {
  stroke: var(--jp-icon-contrast-color2);
}

.jp-icon-contrast3[stroke] {
  stroke: var(--jp-icon-contrast-color3);
}

.jp-icon-dot[fill] {
  fill: var(--jp-warn-color0);
}

.jp-jupyter-icon-color[fill] {
  fill: var(--jp-jupyter-icon-color, var(--jp-warn-color0));
}

.jp-notebook-icon-color[fill] {
  fill: var(--jp-notebook-icon-color, var(--jp-warn-color0));
}

.jp-json-icon-color[fill] {
  fill: var(--jp-json-icon-color, var(--jp-warn-color1));
}

.jp-console-icon-color[fill] {
  fill: var(--jp-console-icon-color, white);
}

.jp-console-icon-background-color[fill] {
  fill: var(--jp-console-icon-background-color, var(--jp-brand-color1));
}

.jp-terminal-icon-color[fill] {
  fill: var(--jp-terminal-icon-color, var(--jp-layout-color2));
}

.jp-terminal-icon-background-color[fill] {
  fill: var(
    --jp-terminal-icon-background-color,
    var(--jp-inverse-layout-color2)
  );
}

.jp-text-editor-icon-color[fill] {
  fill: var(--jp-text-editor-icon-color, var(--jp-inverse-layout-color3));
}

.jp-inspector-icon-color[fill] {
  fill: var(--jp-inspector-icon-color, var(--jp-inverse-layout-color3));
}

/* CSS for icons in selected filebrowser listing items */
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

.jp-DirListing-item.jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* stylelint-disable selector-max-class, selector-max-compound-selectors */

/**
* TODO: come up with non css-hack solution for showing the busy icon on top
*  of the close icon
* CSS for complex behavior of close icon of tabs in the main area tabbar
*/
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}

.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

/* stylelint-enable selector-max-class, selector-max-compound-selectors */

/* CSS for icons in status bar */
#jp-main-statusbar .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

#jp-main-statusbar .jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* special handling for splash icon CSS. While the theme CSS reloads during
   splash, the splash icon can loose theming. To prevent that, we set a
   default for its color variable */
:root {
  --jp-warn-color0: var(--md-orange-700);
}

/* not sure what to do with this one, used in filebrowser listing */
.jp-DragIcon {
  margin-right: 4px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for alt colors for icons as inline SVG HTMLElements
 */

/* alt recolor the primary elements of an icon */
.jp-icon-alt .jp-icon0[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-alt .jp-icon1[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-alt .jp-icon2[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-alt .jp-icon3[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-alt .jp-icon4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-alt .jp-icon0[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-alt .jp-icon1[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-alt .jp-icon2[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-alt .jp-icon3[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-alt .jp-icon4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* alt recolor the accent elements of an icon */
.jp-icon-alt .jp-icon-accent0[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-alt .jp-icon-accent1[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-alt .jp-icon-accent2[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-alt .jp-icon-accent3[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-alt .jp-icon-accent4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-alt .jp-icon-accent0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-alt .jp-icon-accent1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-alt .jp-icon-accent2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-alt .jp-icon-accent3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-alt .jp-icon-accent4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-icon-hoverShow:not(:hover) .jp-icon-hoverShow-content {
  display: none !important;
}

/**
 * Support for hover colors for icons as inline SVG HTMLElements
 */

/**
 * regular colors
 */

/* recolor the primary elements of an icon */
.jp-icon-hover :hover .jp-icon0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-hover :hover .jp-icon1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-hover :hover .jp-icon2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-hover :hover .jp-icon3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-hover :hover .jp-icon4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-hover :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-hover :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-hover :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-hover :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-hover :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-hover :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-hover :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-hover :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-hover :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-hover :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-hover :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-hover :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-hover :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-hover :hover .jp-icon-none-hover[fill] {
  fill: none;
}

.jp-icon-hover :hover .jp-icon-none-hover[stroke] {
  stroke: none;
}

/**
 * inverse colors
 */

/* inverse recolor the primary elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* inverse recolor the accent elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-IFrame {
  width: 100%;
  height: 100%;
}

.jp-IFrame > iframe {
  border: none;
}

/*
When drag events occur, `lm-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-IFrame {
  position: relative;
}

body.lm-mod-override-cursor .jp-IFrame::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-HoverBox {
  position: fixed;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FormGroup-content fieldset {
  border: none;
  padding: 0;
  min-width: 0;
  width: 100%;
}

/* stylelint-disable selector-max-type */

.jp-FormGroup-content fieldset .jp-inputFieldWrapper input,
.jp-FormGroup-content fieldset .jp-inputFieldWrapper select,
.jp-FormGroup-content fieldset .jp-inputFieldWrapper textarea {
  font-size: var(--jp-content-font-size2);
  border-color: var(--jp-input-border-color);
  border-style: solid;
  border-radius: var(--jp-border-radius);
  border-width: 1px;
  padding: 6px 8px;
  background: none;
  color: var(--jp-ui-font-color0);
  height: inherit;
}

.jp-FormGroup-content fieldset input[type='checkbox'] {
  position: relative;
  top: 2px;
  margin-left: 0;
}

.jp-FormGroup-content button.jp-mod-styled {
  cursor: pointer;
}

.jp-FormGroup-content .checkbox label {
  cursor: pointer;
  font-size: var(--jp-content-font-size1);
}

.jp-FormGroup-content .jp-root > fieldset > legend {
  display: none;
}

.jp-FormGroup-content .jp-root > fieldset > p {
  display: none;
}

/** copy of `input.jp-mod-styled:focus` style */
.jp-FormGroup-content fieldset input:focus,
.jp-FormGroup-content fieldset select:focus {
  -moz-outline-radius: unset;
  outline: var(--jp-border-width) solid var(--md-blue-500);
  outline-offset: -1px;
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-FormGroup-content fieldset input:hover:not(:focus),
.jp-FormGroup-content fieldset select:hover:not(:focus) {
  background-color: var(--jp-border-color2);
}

/* stylelint-enable selector-max-type */

.jp-FormGroup-content .checkbox .field-description {
  /* Disable default description field for checkbox:
   because other widgets do not have description fields,
   we add descriptions to each widget on the field level.
  */
  display: none;
}

.jp-FormGroup-content #root__description {
  display: none;
}

.jp-FormGroup-content .jp-modifiedIndicator {
  width: 5px;
  background-color: var(--jp-brand-color2);
  margin-top: 0;
  margin-left: calc(var(--jp-private-settingeditor-modifier-indent) * -1);
  flex-shrink: 0;
}

.jp-FormGroup-content .jp-modifiedIndicator.jp-errorIndicator {
  background-color: var(--jp-error-color0);
  margin-right: 0.5em;
}

/* RJSF ARRAY style */

.jp-arrayFieldWrapper legend {
  font-size: var(--jp-content-font-size2);
  color: var(--jp-ui-font-color0);
  flex-basis: 100%;
  padding: 4px 0;
  font-weight: var(--jp-content-heading-font-weight);
  border-bottom: 1px solid var(--jp-border-color2);
}

.jp-arrayFieldWrapper .field-description {
  padding: 4px 0;
  white-space: pre-wrap;
}

.jp-arrayFieldWrapper .array-item {
  width: 100%;
  border: 1px solid var(--jp-border-color2);
  border-radius: 4px;
  margin: 4px;
}

.jp-ArrayOperations {
  display: flex;
  margin-left: 8px;
}

.jp-ArrayOperationsButton {
  margin: 2px;
}

.jp-ArrayOperationsButton .jp-icon3[fill] {
  fill: var(--jp-ui-font-color0);
}

button.jp-ArrayOperationsButton.jp-mod-styled:disabled {
  cursor: not-allowed;
  opacity: 0.5;
}

/* RJSF form validation error */

.jp-FormGroup-content .validationErrors {
  color: var(--jp-error-color0);
}

/* Hide panel level error as duplicated the field level error */
.jp-FormGroup-content .panel.errors {
  display: none;
}

/* RJSF normal content (settings-editor) */

.jp-FormGroup-contentNormal {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.jp-FormGroup-contentNormal .jp-FormGroup-contentItem {
  margin-left: 7px;
  color: var(--jp-ui-font-color0);
}

.jp-FormGroup-contentNormal .jp-FormGroup-description {
  flex-basis: 100%;
  padding: 4px 7px;
}

.jp-FormGroup-contentNormal .jp-FormGroup-default {
  flex-basis: 100%;
  padding: 4px 7px;
}

.jp-FormGroup-contentNormal .jp-FormGroup-fieldLabel {
  font-size: var(--jp-content-font-size1);
  font-weight: normal;
  min-width: 120px;
}

.jp-FormGroup-contentNormal fieldset:not(:first-child) {
  margin-left: 7px;
}

.jp-FormGroup-contentNormal .field-array-of-string .array-item {
  /* Display `jp-ArrayOperations` buttons side-by-side with content except
    for small screens where flex-wrap will place them one below the other.
  */
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.jp-FormGroup-contentNormal .jp-objectFieldWrapper .form-group {
  padding: 2px 8px 2px var(--jp-private-settingeditor-modifier-indent);
  margin-top: 2px;
}

/* RJSF compact content (metadata-form) */

.jp-FormGroup-content.jp-FormGroup-contentCompact {
  width: 100%;
}

.jp-FormGroup-contentCompact .form-group {
  display: flex;
  padding: 0.5em 0.2em 0.5em 0;
}

.jp-FormGroup-contentCompact
  .jp-FormGroup-compactTitle
  .jp-FormGroup-description {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color2);
}

.jp-FormGroup-contentCompact .jp-FormGroup-fieldLabel {
  padding-bottom: 0.3em;
}

.jp-FormGroup-contentCompact .jp-inputFieldWrapper .form-control {
  width: 100%;
  box-sizing: border-box;
}

.jp-FormGroup-contentCompact .jp-arrayFieldWrapper .jp-FormGroup-compactTitle {
  padding-bottom: 7px;
}

.jp-FormGroup-contentCompact
  .jp-objectFieldWrapper
  .jp-objectFieldWrapper
  .form-group {
  padding: 2px 8px 2px var(--jp-private-settingeditor-modifier-indent);
  margin-top: 2px;
}

.jp-FormGroup-contentCompact ul.error-detail {
  margin-block-start: 0.5em;
  margin-block-end: 0.5em;
  padding-inline-start: 1em;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-SidePanel {
  display: flex;
  flex-direction: column;
  min-width: var(--jp-sidebar-min-width);
  overflow-y: auto;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  font-size: var(--jp-ui-font-size1);
}

.jp-SidePanel-header {
  flex: 0 0 auto;
  display: flex;
  border-bottom: var(--jp-border-width) solid var(--jp-border-color2);
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin: 0;
  padding: 2px;
  text-transform: uppercase;
}

.jp-SidePanel-toolbar {
  flex: 0 0 auto;
}

.jp-SidePanel-content {
  flex: 1 1 auto;
}

.jp-SidePanel-toolbar,
.jp-AccordionPanel-toolbar {
  height: var(--jp-private-toolbar-height);
}

.jp-SidePanel-toolbar.jp-Toolbar-micro {
  display: none;
}

.lm-AccordionPanel .jp-AccordionPanel-title {
  box-sizing: border-box;
  line-height: 25px;
  margin: 0;
  display: flex;
  align-items: center;
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  font-size: var(--jp-ui-font-size0);
}

.jp-AccordionPanel-title {
  cursor: pointer;
  user-select: none;
  -moz-user-select: none;
  -webkit-user-select: none;
  text-transform: uppercase;
}

.lm-AccordionPanel[data-orientation='horizontal'] > .jp-AccordionPanel-title {
  /* Title is rotated for horizontal accordion panel using CSS */
  display: block;
  transform-origin: top left;
  transform: rotate(-90deg) translate(-100%);
}

.jp-AccordionPanel-title .lm-AccordionPanel-titleLabel {
  user-select: none;
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
}

.jp-AccordionPanel-title .lm-AccordionPanel-titleCollapser {
  transform: rotate(-90deg);
  margin: auto 0;
  height: 16px;
}

.jp-AccordionPanel-title.lm-mod-expanded .lm-AccordionPanel-titleCollapser {
  transform: rotate(0deg);
}

.lm-AccordionPanel .jp-AccordionPanel-toolbar {
  background: none;
  box-shadow: none;
  border: none;
  margin-left: auto;
}

.lm-AccordionPanel .lm-SplitPanel-handle:hover {
  background: var(--jp-layout-color3);
}

.jp-text-truncated {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Spinner {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 10;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-layout-color0);
  outline: none;
}

.jp-SpinnerContent {
  font-size: 10px;
  margin: 50px auto;
  text-indent: -9999em;
  width: 3em;
  height: 3em;
  border-radius: 50%;
  background: var(--jp-brand-color3);
  background: linear-gradient(
    to right,
    #f37626 10%,
    rgba(255, 255, 255, 0) 42%
  );
  position: relative;
  animation: load3 1s infinite linear, fadeIn 1s;
}

.jp-SpinnerContent::before {
  width: 50%;
  height: 50%;
  background: #f37626;
  border-radius: 100% 0 0;
  position: absolute;
  top: 0;
  left: 0;
  content: '';
}

.jp-SpinnerContent::after {
  background: var(--jp-layout-color0);
  width: 75%;
  height: 75%;
  border-radius: 50%;
  content: '';
  margin: auto;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 1;
  }
}

@keyframes load3 {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

button.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: none;
  box-sizing: border-box;
  text-align: center;
  line-height: 32px;
  height: 32px;
  padding: 0 12px;
  letter-spacing: 0.8px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input.jp-mod-styled {
  background: var(--jp-input-background);
  height: 28px;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color1);
  padding-left: 7px;
  padding-right: 7px;
  font-size: var(--jp-ui-font-size2);
  color: var(--jp-ui-font-color0);
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input[type='checkbox'].jp-mod-styled {
  appearance: checkbox;
  -webkit-appearance: checkbox;
  -moz-appearance: checkbox;
  height: auto;
}

input.jp-mod-styled:focus {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-select-wrapper {
  display: flex;
  position: relative;
  flex-direction: column;
  padding: 1px;
  background-color: var(--jp-layout-color1);
  box-sizing: border-box;
  margin-bottom: 12px;
}

.jp-select-wrapper:not(.multiple) {
  height: 28px;
}

.jp-select-wrapper.jp-mod-focused select.jp-mod-styled {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-input-active-background);
}

select.jp-mod-styled:hover {
  cursor: pointer;
  color: var(--jp-ui-font-color0);
  background-color: var(--jp-input-hover-background);
  box-shadow: inset 0 0 1px rgba(0, 0, 0, 0.5);
}

select.jp-mod-styled {
  flex: 1 1 auto;
  width: 100%;
  font-size: var(--jp-ui-font-size2);
  background: var(--jp-input-background);
  color: var(--jp-ui-font-color0);
  padding: 0 25px 0 8px;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

select.jp-mod-styled:not([multiple]) {
  height: 32px;
}

select.jp-mod-styled[multiple] {
  max-height: 200px;
  overflow-y: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-switch {
  display: flex;
  align-items: center;
  padding-left: 4px;
  padding-right: 4px;
  font-size: var(--jp-ui-font-size1);
  background-color: transparent;
  color: var(--jp-ui-font-color1);
  border: none;
  height: 20px;
}

.jp-switch:hover {
  background-color: var(--jp-layout-color2);
}

.jp-switch-label {
  margin-right: 5px;
  font-family: var(--jp-ui-font-family);
}

.jp-switch-track {
  cursor: pointer;
  background-color: var(--jp-switch-color, var(--jp-border-color1));
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 34px;
  height: 16px;
  width: 35px;
  position: relative;
}

.jp-switch-track::before {
  content: '';
  position: absolute;
  height: 10px;
  width: 10px;
  margin: 3px;
  left: 0;
  background-color: var(--jp-ui-inverse-font-color1);
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 50%;
}

.jp-switch[aria-checked='true'] .jp-switch-track {
  background-color: var(--jp-switch-true-position-color, var(--jp-warn-color0));
}

.jp-switch[aria-checked='true'] .jp-switch-track::before {
  /* track width (35) - margins (3 + 3) - thumb width (10) */
  left: 19px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toolbar-height: calc(
    28px + var(--jp-border-width)
  ); /* leave 28px for content */
}

.jp-Toolbar {
  color: var(--jp-ui-font-color1);
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: 2px;
  z-index: 8;
  overflow-x: hidden;
}

/* Toolbar items */

.jp-Toolbar > .jp-Toolbar-item.jp-Toolbar-spacer {
  flex-grow: 1;
  flex-shrink: 1;
}

.jp-Toolbar-item.jp-Toolbar-kernelStatus {
  display: inline-block;
  width: 32px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: 16px;
}

.jp-Toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  display: flex;
  padding-left: 1px;
  padding-right: 1px;
  font-size: var(--jp-ui-font-size1);
  line-height: var(--jp-private-toolbar-height);
  height: 100%;
}

/* Toolbar buttons */

/* This is the div we use to wrap the react component into a Widget */
div.jp-ToolbarButton {
  color: transparent;
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0;
  margin: 0;
}

button.jp-ToolbarButtonComponent {
  background: var(--jp-layout-color1);
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0 6px;
  margin: 0;
  height: 24px;
  border-radius: var(--jp-border-radius);
  display: flex;
  align-items: center;
  text-align: center;
  font-size: 14px;
  min-width: unset;
  min-height: unset;
}

button.jp-ToolbarButtonComponent:disabled {
  opacity: 0.4;
}

button.jp-ToolbarButtonComponent > span {
  padding: 0;
  flex: 0 0 auto;
}

button.jp-ToolbarButtonComponent .jp-ToolbarButtonComponent-label {
  font-size: var(--jp-ui-font-size1);
  line-height: 100%;
  padding-left: 2px;
  color: var(--jp-ui-font-color1);
  font-family: var(--jp-ui-font-family);
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar.jp-Toolbar-micro {
  padding: 0;
  min-height: 0;
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar {
  border: none;
  box-shadow: none;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-WindowedPanel-outer {
  position: relative;
  overflow-y: auto;
}

.jp-WindowedPanel-inner {
  position: relative;
}

.jp-WindowedPanel-window {
  position: absolute;
  left: 0;
  right: 0;
  overflow: visible;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* Sibling imports */

body {
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
}

/* Disable native link decoration styles everywhere outside of dialog boxes */
a {
  text-decoration: unset;
  color: unset;
}

a:hover {
  text-decoration: unset;
  color: unset;
}

/* Accessibility for links inside dialog box text */
.jp-Dialog-content a {
  text-decoration: revert;
  color: var(--jp-content-link-color);
}

.jp-Dialog-content a:hover {
  text-decoration: revert;
}

/* Styles for ui-components */
.jp-Button {
  color: var(--jp-ui-font-color2);
  border-radius: var(--jp-border-radius);
  padding: 0 12px;
  font-size: var(--jp-ui-font-size1);

  /* Copy from blueprint 3 */
  display: inline-flex;
  flex-direction: row;
  border: none;
  cursor: pointer;
  align-items: center;
  justify-content: center;
  text-align: left;
  vertical-align: middle;
  min-height: 30px;
  min-width: 30px;
}

.jp-Button:disabled {
  cursor: not-allowed;
}

.jp-Button:empty {
  padding: 0 !important;
}

.jp-Button.jp-mod-small {
  min-height: 24px;
  min-width: 24px;
  font-size: 12px;
  padding: 0 7px;
}

/* Use our own theme for hover styles */
.jp-Button.jp-mod-minimal:hover {
  background-color: var(--jp-layout-color2);
}

.jp-Button.jp-mod-minimal {
  background: none;
}

.jp-InputGroup {
  display: block;
  position: relative;
}

.jp-InputGroup input {
  box-sizing: border-box;
  border: none;
  border-radius: 0;
  background-color: transparent;
  color: var(--jp-ui-font-color0);
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
  padding-bottom: 0;
  padding-top: 0;
  padding-left: 10px;
  padding-right: 28px;
  position: relative;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  font-size: 14px;
  font-weight: 400;
  height: 30px;
  line-height: 30px;
  outline: none;
  vertical-align: middle;
}

.jp-InputGroup input:focus {
  box-shadow: inset 0 0 0 var(--jp-border-width)
      var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-InputGroup input:disabled {
  cursor: not-allowed;
  resize: block;
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color2);
}

.jp-InputGroup input:disabled ~ span {
  cursor: not-allowed;
  color: var(--jp-ui-font-color2);
}

.jp-InputGroup input::placeholder,
input::placeholder {
  color: var(--jp-ui-font-color2);
}

.jp-InputGroupAction {
  position: absolute;
  bottom: 1px;
  right: 0;
  padding: 6px;
}

.jp-HTMLSelect.jp-DefaultStyle select {
  background-color: initial;
  border: none;
  border-radius: 0;
  box-shadow: none;
  color: var(--jp-ui-font-color0);
  display: block;
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  height: 24px;
  line-height: 14px;
  padding: 0 25px 0 10px;
  text-align: left;
  -moz-appearance: none;
  -webkit-appearance: none;
}

.jp-HTMLSelect.jp-DefaultStyle select:disabled {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color2);
  cursor: not-allowed;
  resize: block;
}

.jp-HTMLSelect.jp-DefaultStyle select:disabled ~ span {
  cursor: not-allowed;
}

/* Use our own theme for hover and option styles */
/* stylelint-disable-next-line selector-max-type */
.jp-HTMLSelect.jp-DefaultStyle select:hover,
.jp-HTMLSelect.jp-DefaultStyle select > option {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color0);
}

select {
  box-sizing: border-box;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-StatusBar-Widget {
  display: flex;
  align-items: center;
  background: var(--jp-layout-color2);
  min-height: var(--jp-statusbar-height);
  justify-content: space-between;
  padding: 0 10px;
}

.jp-StatusBar-Left {
  display: flex;
  align-items: center;
  flex-direction: row;
}

.jp-StatusBar-Middle {
  display: flex;
  align-items: center;
}

.jp-StatusBar-Right {
  display: flex;
  align-items: center;
  flex-direction: row-reverse;
}

.jp-StatusBar-Item {
  max-height: var(--jp-statusbar-height);
  margin: 0 2px;
  height: var(--jp-statusbar-height);
  white-space: nowrap;
  text-overflow: ellipsis;
  color: var(--jp-ui-font-color1);
  padding: 0 6px;
}

.jp-mod-highlighted:hover {
  background-color: var(--jp-layout-color3);
}

.jp-mod-clicked {
  background-color: var(--jp-brand-color1);
}

.jp-mod-clicked:hover {
  background-color: var(--jp-brand-color0);
}

.jp-mod-clicked .jp-StatusBar-TextItem {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-StatusBar-HoverItem {
  box-shadow: '0px 4px 4px rgba(0, 0, 0, 0.25)';
}

.jp-StatusBar-TextItem {
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  line-height: 24px;
  color: var(--jp-ui-font-color1);
}

.jp-StatusBar-GroupItem {
  display: flex;
  align-items: center;
  flex-direction: row;
}

.jp-Statusbar-ProgressCircle svg {
  display: block;
  margin: 0 auto;
  width: 16px;
  height: 24px;
  align-self: normal;
}

.jp-Statusbar-ProgressCircle path {
  fill: var(--jp-inverse-layout-color3);
}

.jp-Statusbar-ProgressBar-progress-bar {
  height: 10px;
  width: 100px;
  border: solid 0.25px var(--jp-brand-color2);
  border-radius: 3px;
  overflow: hidden;
  align-self: center;
}

.jp-Statusbar-ProgressBar-progress-bar > div {
  background-color: var(--jp-brand-color2);
  background-image: linear-gradient(
    -45deg,
    rgba(255, 255, 255, 0.2) 25%,
    transparent 25%,
    transparent 50%,
    rgba(255, 255, 255, 0.2) 50%,
    rgba(255, 255, 255, 0.2) 75%,
    transparent 75%,
    transparent
  );
  background-size: 40px 40px;
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 14px;
  color: #fff;
  text-align: center;
  animation: jp-Statusbar-ExecutionTime-progress-bar 2s linear infinite;
}

.jp-Statusbar-ProgressBar-progress-bar p {
  color: var(--jp-ui-font-color1);
  font-family: var(--jp-ui-font-family);
  font-size: var(--jp-ui-font-size1);
  line-height: 10px;
  width: 100px;
}

@keyframes jp-Statusbar-ExecutionTime-progress-bar {
  0% {
    background-position: 0 0;
  }

  100% {
    background-position: 40px 40px;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-commandpalette-search-height: 28px;
}

/*-----------------------------------------------------------------------------
| Overall styles
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  padding-bottom: 0;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);

  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Modal variant
|----------------------------------------------------------------------------*/

.jp-ModalCommandPalette {
  position: absolute;
  z-index: 10000;
  top: 38px;
  left: 30%;
  margin: 0;
  padding: 4px;
  width: 40%;
  box-shadow: var(--jp-elevation-z4);
  border-radius: 4px;
  background: var(--jp-layout-color0);
}

.jp-ModalCommandPalette .lm-CommandPalette {
  max-height: 40vh;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-close-icon::after {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-header {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-item {
  margin-left: 4px;
  margin-right: 4px;
}

.jp-ModalCommandPalette
  .lm-CommandPalette
  .lm-CommandPalette-item.lm-mod-disabled {
  display: none;
}

/*-----------------------------------------------------------------------------
| Search
|----------------------------------------------------------------------------*/

.lm-CommandPalette-search {
  padding: 4px;
  background-color: var(--jp-layout-color1);
  z-index: 2;
}

.lm-CommandPalette-wrapper {
  overflow: overlay;
  padding: 0 9px;
  background-color: var(--jp-input-active-background);
  height: 30px;
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.lm-CommandPalette.lm-mod-focused .lm-CommandPalette-wrapper {
  box-shadow: inset 0 0 0 1px var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-SearchIconGroup {
  color: white;
  background-color: var(--jp-brand-color1);
  position: absolute;
  top: 4px;
  right: 4px;
  padding: 5px 5px 1px;
}

.jp-SearchIconGroup svg {
  height: 20px;
  width: 20px;
}

.jp-SearchIconGroup .jp-icon3[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-input {
  background: transparent;
  width: calc(100% - 18px);
  float: left;
  border: none;
  outline: none;
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  line-height: var(--jp-private-commandpalette-search-height);
}

.lm-CommandPalette-input::-webkit-input-placeholder,
.lm-CommandPalette-input::-moz-placeholder,
.lm-CommandPalette-input:-ms-input-placeholder {
  color: var(--jp-ui-font-color2);
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Results
|----------------------------------------------------------------------------*/

.lm-CommandPalette-header:first-child {
  margin-top: 0;
}

.lm-CommandPalette-header {
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin-top: 8px;
  padding: 8px 0 8px 12px;
  text-transform: uppercase;
}

.lm-CommandPalette-header.lm-mod-active {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-header > mark {
  background-color: transparent;
  font-weight: bold;
  color: var(--jp-ui-font-color1);
}

.lm-CommandPalette-item {
  padding: 4px 12px 4px 4px;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  font-weight: 400;
  display: flex;
}

.lm-CommandPalette-item.lm-mod-disabled {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item.lm-mod-active {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item.lm-mod-active .lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-inverse-font-color0);
}

.lm-CommandPalette-item.lm-mod-active .jp-icon-selectable[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-item.lm-mod-active:hover:not(.lm-mod-disabled) {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item:hover:not(.lm-mod-active):not(.lm-mod-disabled) {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-itemContent {
  overflow: hidden;
}

.lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.lm-CommandPalette-item.lm-mod-disabled mark {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item .lm-CommandPalette-itemIcon {
  margin: 0 4px 0 0;
  position: relative;
  width: 16px;
  top: 2px;
  flex: 0 0 auto;
}

.lm-CommandPalette-item.lm-mod-disabled .lm-CommandPalette-itemIcon {
  opacity: 0.6;
}

.lm-CommandPalette-item .lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemCaption {
  display: none;
}

.lm-CommandPalette-content {
  background-color: var(--jp-layout-color1);
}

.lm-CommandPalette-content:empty::after {
  content: 'No results';
  margin: auto;
  margin-top: 20px;
  width: 100px;
  display: block;
  font-size: var(--jp-ui-font-size2);
  font-family: var(--jp-ui-font-family);
  font-weight: lighter;
}

.lm-CommandPalette-emptyMessage {
  text-align: center;
  margin-top: 24px;
  line-height: 1.32;
  padding: 0 8px;
  color: var(--jp-content-font-color3);
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Dialog {
  position: absolute;
  z-index: 10000;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  top: 0;
  left: 0;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-dialog-background);
}

.jp-Dialog-content {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  background: var(--jp-layout-color1);
  padding: 24px 24px 12px;
  min-width: 300px;
  min-height: 150px;
  max-width: 1000px;
  max-height: 500px;
  box-sizing: border-box;
  box-shadow: var(--jp-elevation-z20);
  word-wrap: break-word;
  border-radius: var(--jp-border-radius);

  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color1);
  resize: both;
}

.jp-Dialog-content.jp-Dialog-content-small {
  max-width: 500px;
}

.jp-Dialog-button {
  overflow: visible;
}

button.jp-Dialog-button:focus {
  outline: 1px solid var(--jp-brand-color1);
  outline-offset: 4px;
  -moz-outline-radius: 0;
}

button.jp-Dialog-button:focus::-moz-focus-inner {
  border: 0;
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-accept:focus,
button.jp-Dialog-button.jp-mod-styled.jp-mod-warn:focus,
button.jp-Dialog-button.jp-mod-styled.jp-mod-reject:focus {
  outline-offset: 4px;
  -moz-outline-radius: 0;
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-accept:focus {
  outline: 1px solid var(--jp-accept-color-normal, var(--jp-brand-color1));
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-warn:focus {
  outline: 1px solid var(--jp-warn-color-normal, var(--jp-error-color1));
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-reject:focus {
  outline: 1px solid var(--jp-reject-color-normal, var(--md-grey-600));
}

button.jp-Dialog-close-button {
  padding: 0;
  height: 100%;
  min-width: unset;
  min-height: unset;
}

.jp-Dialog-header {
  display: flex;
  justify-content: space-between;
  flex: 0 0 auto;
  padding-bottom: 12px;
  font-size: var(--jp-ui-font-size3);
  font-weight: 400;
  color: var(--jp-ui-font-color1);
}

.jp-Dialog-body {
  display: flex;
  flex-direction: column;
  flex: 1 1 auto;
  font-size: var(--jp-ui-font-size1);
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

.jp-Dialog-footer {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  align-items: center;
  flex: 0 0 auto;
  margin-left: -12px;
  margin-right: -12px;
  padding: 12px;
}

.jp-Dialog-checkbox {
  padding-right: 5px;
}

.jp-Dialog-checkbox > input:focus-visible {
  outline: 1px solid var(--jp-input-active-border-color);
  outline-offset: 1px;
}

.jp-Dialog-spacer {
  flex: 1 1 auto;
}

.jp-Dialog-title {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.jp-Dialog-body > .jp-select-wrapper {
  width: 100%;
}

.jp-Dialog-body > button {
  padding: 0 16px;
}

.jp-Dialog-body > label {
  line-height: 1.4;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-button.jp-mod-styled:not(:last-child) {
  margin-right: 12px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-Input-Boolean-Dialog {
  flex-direction: row-reverse;
  align-items: end;
  width: 100%;
}

.jp-Input-Boolean-Dialog > label {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MainAreaWidget > :focus {
  outline: none;
}

.jp-MainAreaWidget .jp-MainAreaWidget-error {
  padding: 6px;
}

.jp-MainAreaWidget .jp-MainAreaWidget-error > pre {
  width: auto;
  padding: 10px;
  background: var(--jp-error-color3);
  border: var(--jp-border-width) solid var(--jp-error-color1);
  border-radius: var(--jp-border-radius);
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  white-space: pre-wrap;
  word-wrap: break-word;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/**
 * google-material-color v1.2.6
 * https://github.com/danlevan/google-material-color
 */
:root {
  --md-red-50: #ffebee;
  --md-red-100: #ffcdd2;
  --md-red-200: #ef9a9a;
  --md-red-300: #e57373;
  --md-red-400: #ef5350;
  --md-red-500: #f44336;
  --md-red-600: #e53935;
  --md-red-700: #d32f2f;
  --md-red-800: #c62828;
  --md-red-900: #b71c1c;
  --md-red-A100: #ff8a80;
  --md-red-A200: #ff5252;
  --md-red-A400: #ff1744;
  --md-red-A700: #d50000;
  --md-pink-50: #fce4ec;
  --md-pink-100: #f8bbd0;
  --md-pink-200: #f48fb1;
  --md-pink-300: #f06292;
  --md-pink-400: #ec407a;
  --md-pink-500: #e91e63;
  --md-pink-600: #d81b60;
  --md-pink-700: #c2185b;
  --md-pink-800: #ad1457;
  --md-pink-900: #880e4f;
  --md-pink-A100: #ff80ab;
  --md-pink-A200: #ff4081;
  --md-pink-A400: #f50057;
  --md-pink-A700: #c51162;
  --md-purple-50: #f3e5f5;
  --md-purple-100: #e1bee7;
  --md-purple-200: #ce93d8;
  --md-purple-300: #ba68c8;
  --md-purple-400: #ab47bc;
  --md-purple-500: #9c27b0;
  --md-purple-600: #8e24aa;
  --md-purple-700: #7b1fa2;
  --md-purple-800: #6a1b9a;
  --md-purple-900: #4a148c;
  --md-purple-A100: #ea80fc;
  --md-purple-A200: #e040fb;
  --md-purple-A400: #d500f9;
  --md-purple-A700: #a0f;
  --md-deep-purple-50: #ede7f6;
  --md-deep-purple-100: #d1c4e9;
  --md-deep-purple-200: #b39ddb;
  --md-deep-purple-300: #9575cd;
  --md-deep-purple-400: #7e57c2;
  --md-deep-purple-500: #673ab7;
  --md-deep-purple-600: #5e35b1;
  --md-deep-purple-700: #512da8;
  --md-deep-purple-800: #4527a0;
  --md-deep-purple-900: #311b92;
  --md-deep-purple-A100: #b388ff;
  --md-deep-purple-A200: #7c4dff;
  --md-deep-purple-A400: #651fff;
  --md-deep-purple-A700: #6200ea;
  --md-indigo-50: #e8eaf6;
  --md-indigo-100: #c5cae9;
  --md-indigo-200: #9fa8da;
  --md-indigo-300: #7986cb;
  --md-indigo-400: #5c6bc0;
  --md-indigo-500: #3f51b5;
  --md-indigo-600: #3949ab;
  --md-indigo-700: #303f9f;
  --md-indigo-800: #283593;
  --md-indigo-900: #1a237e;
  --md-indigo-A100: #8c9eff;
  --md-indigo-A200: #536dfe;
  --md-indigo-A400: #3d5afe;
  --md-indigo-A700: #304ffe;
  --md-blue-50: #e3f2fd;
  --md-blue-100: #bbdefb;
  --md-blue-200: #90caf9;
  --md-blue-300: #64b5f6;
  --md-blue-400: #42a5f5;
  --md-blue-500: #2196f3;
  --md-blue-600: #1e88e5;
  --md-blue-700: #1976d2;
  --md-blue-800: #1565c0;
  --md-blue-900: #0d47a1;
  --md-blue-A100: #82b1ff;
  --md-blue-A200: #448aff;
  --md-blue-A400: #2979ff;
  --md-blue-A700: #2962ff;
  --md-light-blue-50: #e1f5fe;
  --md-light-blue-100: #b3e5fc;
  --md-light-blue-200: #81d4fa;
  --md-light-blue-300: #4fc3f7;
  --md-light-blue-400: #29b6f6;
  --md-light-blue-500: #03a9f4;
  --md-light-blue-600: #039be5;
  --md-light-blue-700: #0288d1;
  --md-light-blue-800: #0277bd;
  --md-light-blue-900: #01579b;
  --md-light-blue-A100: #80d8ff;
  --md-light-blue-A200: #40c4ff;
  --md-light-blue-A400: #00b0ff;
  --md-light-blue-A700: #0091ea;
  --md-cyan-50: #e0f7fa;
  --md-cyan-100: #b2ebf2;
  --md-cyan-200: #80deea;
  --md-cyan-300: #4dd0e1;
  --md-cyan-400: #26c6da;
  --md-cyan-500: #00bcd4;
  --md-cyan-600: #00acc1;
  --md-cyan-700: #0097a7;
  --md-cyan-800: #00838f;
  --md-cyan-900: #006064;
  --md-cyan-A100: #84ffff;
  --md-cyan-A200: #18ffff;
  --md-cyan-A400: #00e5ff;
  --md-cyan-A700: #00b8d4;
  --md-teal-50: #e0f2f1;
  --md-teal-100: #b2dfdb;
  --md-teal-200: #80cbc4;
  --md-teal-300: #4db6ac;
  --md-teal-400: #26a69a;
  --md-teal-500: #009688;
  --md-teal-600: #00897b;
  --md-teal-700: #00796b;
  --md-teal-800: #00695c;
  --md-teal-900: #004d40;
  --md-teal-A100: #a7ffeb;
  --md-teal-A200: #64ffda;
  --md-teal-A400: #1de9b6;
  --md-teal-A700: #00bfa5;
  --md-green-50: #e8f5e9;
  --md-green-100: #c8e6c9;
  --md-green-200: #a5d6a7;
  --md-green-300: #81c784;
  --md-green-400: #66bb6a;
  --md-green-500: #4caf50;
  --md-green-600: #43a047;
  --md-green-700: #388e3c;
  --md-green-800: #2e7d32;
  --md-green-900: #1b5e20;
  --md-green-A100: #b9f6ca;
  --md-green-A200: #69f0ae;
  --md-green-A400: #00e676;
  --md-green-A700: #00c853;
  --md-light-green-50: #f1f8e9;
  --md-light-green-100: #dcedc8;
  --md-light-green-200: #c5e1a5;
  --md-light-green-300: #aed581;
  --md-light-green-400: #9ccc65;
  --md-light-green-500: #8bc34a;
  --md-light-green-600: #7cb342;
  --md-light-green-700: #689f38;
  --md-light-green-800: #558b2f;
  --md-light-green-900: #33691e;
  --md-light-green-A100: #ccff90;
  --md-light-green-A200: #b2ff59;
  --md-light-green-A400: #76ff03;
  --md-light-green-A700: #64dd17;
  --md-lime-50: #f9fbe7;
  --md-lime-100: #f0f4c3;
  --md-lime-200: #e6ee9c;
  --md-lime-300: #dce775;
  --md-lime-400: #d4e157;
  --md-lime-500: #cddc39;
  --md-lime-600: #c0ca33;
  --md-lime-700: #afb42b;
  --md-lime-800: #9e9d24;
  --md-lime-900: #827717;
  --md-lime-A100: #f4ff81;
  --md-lime-A200: #eeff41;
  --md-lime-A400: #c6ff00;
  --md-lime-A700: #aeea00;
  --md-yellow-50: #fffde7;
  --md-yellow-100: #fff9c4;
  --md-yellow-200: #fff59d;
  --md-yellow-300: #fff176;
  --md-yellow-400: #ffee58;
  --md-yellow-500: #ffeb3b;
  --md-yellow-600: #fdd835;
  --md-yellow-700: #fbc02d;
  --md-yellow-800: #f9a825;
  --md-yellow-900: #f57f17;
  --md-yellow-A100: #ffff8d;
  --md-yellow-A200: #ff0;
  --md-yellow-A400: #ffea00;
  --md-yellow-A700: #ffd600;
  --md-amber-50: #fff8e1;
  --md-amber-100: #ffecb3;
  --md-amber-200: #ffe082;
  --md-amber-300: #ffd54f;
  --md-amber-400: #ffca28;
  --md-amber-500: #ffc107;
  --md-amber-600: #ffb300;
  --md-amber-700: #ffa000;
  --md-amber-800: #ff8f00;
  --md-amber-900: #ff6f00;
  --md-amber-A100: #ffe57f;
  --md-amber-A200: #ffd740;
  --md-amber-A400: #ffc400;
  --md-amber-A700: #ffab00;
  --md-orange-50: #fff3e0;
  --md-orange-100: #ffe0b2;
  --md-orange-200: #ffcc80;
  --md-orange-300: #ffb74d;
  --md-orange-400: #ffa726;
  --md-orange-500: #ff9800;
  --md-orange-600: #fb8c00;
  --md-orange-700: #f57c00;
  --md-orange-800: #ef6c00;
  --md-orange-900: #e65100;
  --md-orange-A100: #ffd180;
  --md-orange-A200: #ffab40;
  --md-orange-A400: #ff9100;
  --md-orange-A700: #ff6d00;
  --md-deep-orange-50: #fbe9e7;
  --md-deep-orange-100: #ffccbc;
  --md-deep-orange-200: #ffab91;
  --md-deep-orange-300: #ff8a65;
  --md-deep-orange-400: #ff7043;
  --md-deep-orange-500: #ff5722;
  --md-deep-orange-600: #f4511e;
  --md-deep-orange-700: #e64a19;
  --md-deep-orange-800: #d84315;
  --md-deep-orange-900: #bf360c;
  --md-deep-orange-A100: #ff9e80;
  --md-deep-orange-A200: #ff6e40;
  --md-deep-orange-A400: #ff3d00;
  --md-deep-orange-A700: #dd2c00;
  --md-brown-50: #efebe9;
  --md-brown-100: #d7ccc8;
  --md-brown-200: #bcaaa4;
  --md-brown-300: #a1887f;
  --md-brown-400: #8d6e63;
  --md-brown-500: #795548;
  --md-brown-600: #6d4c41;
  --md-brown-700: #5d4037;
  --md-brown-800: #4e342e;
  --md-brown-900: #3e2723;
  --md-grey-50: #fafafa;
  --md-grey-100: #f5f5f5;
  --md-grey-200: #eee;
  --md-grey-300: #e0e0e0;
  --md-grey-400: #bdbdbd;
  --md-grey-500: #9e9e9e;
  --md-grey-600: #757575;
  --md-grey-700: #616161;
  --md-grey-800: #424242;
  --md-grey-900: #212121;
  --md-blue-grey-50: #eceff1;
  --md-blue-grey-100: #cfd8dc;
  --md-blue-grey-200: #b0bec5;
  --md-blue-grey-300: #90a4ae;
  --md-blue-grey-400: #78909c;
  --md-blue-grey-500: #607d8b;
  --md-blue-grey-600: #546e7a;
  --md-blue-grey-700: #455a64;
  --md-blue-grey-800: #37474f;
  --md-blue-grey-900: #263238;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| RenderedText
|----------------------------------------------------------------------------*/

:root {
  /* This is the padding value to fill the gaps between lines containing spans with background color. */
  --jp-private-code-span-padding: calc(
    (var(--jp-code-line-height) - 1) * var(--jp-code-font-size) / 2
  );
}

.jp-RenderedText {
  text-align: left;
  padding-left: var(--jp-code-padding);
  line-height: var(--jp-code-line-height);
  font-family: var(--jp-code-font-family);
}

.jp-RenderedText pre,
.jp-RenderedJavaScript pre,
.jp-RenderedHTMLCommon pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
  border: none;
  margin: 0;
  padding: 0;
}

.jp-RenderedText pre a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedText pre a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedText pre a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* console foregrounds and backgrounds */
.jp-RenderedText pre .ansi-black-fg {
  color: #3e424d;
}

.jp-RenderedText pre .ansi-red-fg {
  color: #e75c58;
}

.jp-RenderedText pre .ansi-green-fg {
  color: #00a250;
}

.jp-RenderedText pre .ansi-yellow-fg {
  color: #ddb62b;
}

.jp-RenderedText pre .ansi-blue-fg {
  color: #208ffb;
}

.jp-RenderedText pre .ansi-magenta-fg {
  color: #d160c4;
}

.jp-RenderedText pre .ansi-cyan-fg {
  color: #60c6c8;
}

.jp-RenderedText pre .ansi-white-fg {
  color: #c5c1b4;
}

.jp-RenderedText pre .ansi-black-bg {
  background-color: #3e424d;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-red-bg {
  background-color: #e75c58;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-green-bg {
  background-color: #00a250;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-yellow-bg {
  background-color: #ddb62b;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-blue-bg {
  background-color: #208ffb;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-magenta-bg {
  background-color: #d160c4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-cyan-bg {
  background-color: #60c6c8;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-white-bg {
  background-color: #c5c1b4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-black-intense-fg {
  color: #282c36;
}

.jp-RenderedText pre .ansi-red-intense-fg {
  color: #b22b31;
}

.jp-RenderedText pre .ansi-green-intense-fg {
  color: #007427;
}

.jp-RenderedText pre .ansi-yellow-intense-fg {
  color: #b27d12;
}

.jp-RenderedText pre .ansi-blue-intense-fg {
  color: #0065ca;
}

.jp-RenderedText pre .ansi-magenta-intense-fg {
  color: #a03196;
}

.jp-RenderedText pre .ansi-cyan-intense-fg {
  color: #258f8f;
}

.jp-RenderedText pre .ansi-white-intense-fg {
  color: #a1a6b2;
}

.jp-RenderedText pre .ansi-black-intense-bg {
  background-color: #282c36;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-red-intense-bg {
  background-color: #b22b31;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-green-intense-bg {
  background-color: #007427;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-yellow-intense-bg {
  background-color: #b27d12;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-blue-intense-bg {
  background-color: #0065ca;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-magenta-intense-bg {
  background-color: #a03196;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-cyan-intense-bg {
  background-color: #258f8f;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-white-intense-bg {
  background-color: #a1a6b2;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-default-inverse-fg {
  color: var(--jp-ui-inverse-font-color0);
}

.jp-RenderedText pre .ansi-default-inverse-bg {
  background-color: var(--jp-inverse-layout-color0);
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-bold {
  font-weight: bold;
}

.jp-RenderedText pre .ansi-underline {
  text-decoration: underline;
}

.jp-RenderedText[data-mime-type='application/vnd.jupyter.stderr'] {
  background: var(--jp-rendermime-error-background);
  padding-top: var(--jp-code-padding);
}

/*-----------------------------------------------------------------------------
| RenderedLatex
|----------------------------------------------------------------------------*/

.jp-RenderedLatex {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
}

/* Left-justify outputs.*/
.jp-OutputArea-output.jp-RenderedLatex {
  padding: var(--jp-code-padding);
  text-align: left;
}

/*-----------------------------------------------------------------------------
| RenderedHTML
|----------------------------------------------------------------------------*/

.jp-RenderedHTMLCommon {
  color: var(--jp-content-font-color1);
  font-family: var(--jp-content-font-family);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);

  /* Give a bit more R padding on Markdown text to keep line lengths reasonable */
  padding-right: 20px;
}

.jp-RenderedHTMLCommon em {
  font-style: italic;
}

.jp-RenderedHTMLCommon strong {
  font-weight: bold;
}

.jp-RenderedHTMLCommon u {
  text-decoration: underline;
}

.jp-RenderedHTMLCommon a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* Headings */

.jp-RenderedHTMLCommon h1,
.jp-RenderedHTMLCommon h2,
.jp-RenderedHTMLCommon h3,
.jp-RenderedHTMLCommon h4,
.jp-RenderedHTMLCommon h5,
.jp-RenderedHTMLCommon h6 {
  line-height: var(--jp-content-heading-line-height);
  font-weight: var(--jp-content-heading-font-weight);
  font-style: normal;
  margin: var(--jp-content-heading-margin-top) 0
    var(--jp-content-heading-margin-bottom) 0;
}

.jp-RenderedHTMLCommon h1:first-child,
.jp-RenderedHTMLCommon h2:first-child,
.jp-RenderedHTMLCommon h3:first-child,
.jp-RenderedHTMLCommon h4:first-child,
.jp-RenderedHTMLCommon h5:first-child,
.jp-RenderedHTMLCommon h6:first-child {
  margin-top: calc(0.5 * var(--jp-content-heading-margin-top));
}

.jp-RenderedHTMLCommon h1:last-child,
.jp-RenderedHTMLCommon h2:last-child,
.jp-RenderedHTMLCommon h3:last-child,
.jp-RenderedHTMLCommon h4:last-child,
.jp-RenderedHTMLCommon h5:last-child,
.jp-RenderedHTMLCommon h6:last-child {
  margin-bottom: calc(0.5 * var(--jp-content-heading-margin-bottom));
}

.jp-RenderedHTMLCommon h1 {
  font-size: var(--jp-content-font-size5);
}

.jp-RenderedHTMLCommon h2 {
  font-size: var(--jp-content-font-size4);
}

.jp-RenderedHTMLCommon h3 {
  font-size: var(--jp-content-font-size3);
}

.jp-RenderedHTMLCommon h4 {
  font-size: var(--jp-content-font-size2);
}

.jp-RenderedHTMLCommon h5 {
  font-size: var(--jp-content-font-size1);
}

.jp-RenderedHTMLCommon h6 {
  font-size: var(--jp-content-font-size0);
}

/* Lists */

/* stylelint-disable selector-max-type, selector-max-compound-selectors */

.jp-RenderedHTMLCommon ul:not(.list-inline),
.jp-RenderedHTMLCommon ol:not(.list-inline) {
  padding-left: 2em;
}

.jp-RenderedHTMLCommon ul {
  list-style: disc;
}

.jp-RenderedHTMLCommon ul ul {
  list-style: square;
}

.jp-RenderedHTMLCommon ul ul ul {
  list-style: circle;
}

.jp-RenderedHTMLCommon ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol ol {
  list-style: upper-alpha;
}

.jp-RenderedHTMLCommon ol ol ol {
  list-style: lower-alpha;
}

.jp-RenderedHTMLCommon ol ol ol ol {
  list-style: lower-roman;
}

.jp-RenderedHTMLCommon ol ol ol ol ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol,
.jp-RenderedHTMLCommon ul {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon ul ul,
.jp-RenderedHTMLCommon ul ol,
.jp-RenderedHTMLCommon ol ul,
.jp-RenderedHTMLCommon ol ol {
  margin-bottom: 0;
}

/* stylelint-enable selector-max-type, selector-max-compound-selectors */

.jp-RenderedHTMLCommon hr {
  color: var(--jp-border-color2);
  background-color: var(--jp-border-color1);
  margin-top: 1em;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon > pre {
  margin: 1.5em 2em;
}

.jp-RenderedHTMLCommon pre,
.jp-RenderedHTMLCommon code {
  border: 0;
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  line-height: var(--jp-code-line-height);
  padding: 0;
  white-space: pre-wrap;
}

.jp-RenderedHTMLCommon :not(pre) > code {
  background-color: var(--jp-layout-color2);
  padding: 1px 5px;
}

/* Tables */

.jp-RenderedHTMLCommon table {
  border-collapse: collapse;
  border-spacing: 0;
  border: none;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  table-layout: fixed;
  margin-left: auto;
  margin-bottom: 1em;
  margin-right: auto;
}

.jp-RenderedHTMLCommon thead {
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  vertical-align: bottom;
}

.jp-RenderedHTMLCommon td,
.jp-RenderedHTMLCommon th,
.jp-RenderedHTMLCommon tr {
  vertical-align: middle;
  padding: 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}

.jp-RenderedMarkdown.jp-RenderedHTMLCommon td,
.jp-RenderedMarkdown.jp-RenderedHTMLCommon th {
  max-width: none;
}

:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon td,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon th,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon tr {
  text-align: right;
}

.jp-RenderedHTMLCommon th {
  font-weight: bold;
}

.jp-RenderedHTMLCommon tbody tr:nth-child(odd) {
  background: var(--jp-layout-color0);
}

.jp-RenderedHTMLCommon tbody tr:nth-child(even) {
  background: var(--jp-rendermime-table-row-background);
}

.jp-RenderedHTMLCommon tbody tr:hover {
  background: var(--jp-rendermime-table-row-hover-background);
}

.jp-RenderedHTMLCommon p {
  text-align: left;
  margin: 0;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon img {
  -moz-force-broken-image-icon: 1;
}

/* Restrict to direct children as other images could be nested in other content. */
.jp-RenderedHTMLCommon > img {
  display: block;
  margin-left: 0;
  margin-right: 0;
  margin-bottom: 1em;
}

/* Change color behind transparent images if they need it... */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-light-background {
  background-color: var(--jp-inverse-layout-color1);
}

[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-dark-background {
  background-color: var(--jp-inverse-layout-color1);
}

.jp-RenderedHTMLCommon img,
.jp-RenderedImage img,
.jp-RenderedHTMLCommon svg,
.jp-RenderedSVG svg {
  max-width: 100%;
  height: auto;
}

.jp-RenderedHTMLCommon img.jp-mod-unconfined,
.jp-RenderedImage img.jp-mod-unconfined,
.jp-RenderedHTMLCommon svg.jp-mod-unconfined,
.jp-RenderedSVG svg.jp-mod-unconfined {
  max-width: none;
}

.jp-RenderedHTMLCommon .alert {
  padding: var(--jp-notebook-padding);
  border: var(--jp-border-width) solid transparent;
  border-radius: var(--jp-border-radius);
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon .alert-info {
  color: var(--jp-info-color0);
  background-color: var(--jp-info-color3);
  border-color: var(--jp-info-color2);
}

.jp-RenderedHTMLCommon .alert-info hr {
  border-color: var(--jp-info-color3);
}

.jp-RenderedHTMLCommon .alert-info > p:last-child,
.jp-RenderedHTMLCommon .alert-info > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-warning {
  color: var(--jp-warn-color0);
  background-color: var(--jp-warn-color3);
  border-color: var(--jp-warn-color2);
}

.jp-RenderedHTMLCommon .alert-warning hr {
  border-color: var(--jp-warn-color3);
}

.jp-RenderedHTMLCommon .alert-warning > p:last-child,
.jp-RenderedHTMLCommon .alert-warning > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-success {
  color: var(--jp-success-color0);
  background-color: var(--jp-success-color3);
  border-color: var(--jp-success-color2);
}

.jp-RenderedHTMLCommon .alert-success hr {
  border-color: var(--jp-success-color3);
}

.jp-RenderedHTMLCommon .alert-success > p:last-child,
.jp-RenderedHTMLCommon .alert-success > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-danger {
  color: var(--jp-error-color0);
  background-color: var(--jp-error-color3);
  border-color: var(--jp-error-color2);
}

.jp-RenderedHTMLCommon .alert-danger hr {
  border-color: var(--jp-error-color3);
}

.jp-RenderedHTMLCommon .alert-danger > p:last-child,
.jp-RenderedHTMLCommon .alert-danger > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon blockquote {
  margin: 1em 2em;
  padding: 0 1em;
  border-left: 5px solid var(--jp-border-color2);
}

a.jp-InternalAnchorLink {
  visibility: hidden;
  margin-left: 8px;
  color: var(--md-blue-800);
}

h1:hover .jp-InternalAnchorLink,
h2:hover .jp-InternalAnchorLink,
h3:hover .jp-InternalAnchorLink,
h4:hover .jp-InternalAnchorLink,
h5:hover .jp-InternalAnchorLink,
h6:hover .jp-InternalAnchorLink {
  visibility: visible;
}

.jp-RenderedHTMLCommon kbd {
  background-color: var(--jp-rendermime-table-row-background);
  border: 1px solid var(--jp-border-color0);
  border-bottom-color: var(--jp-border-color2);
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
  display: inline-block;
  font-size: var(--jp-ui-font-size0);
  line-height: 1em;
  padding: 0.2em 0.5em;
}

/* Most direct children of .jp-RenderedHTMLCommon have a margin-bottom of 1.0.
 * At the bottom of cells this is a bit too much as there is also spacing
 * between cells. Going all the way to 0 gets too tight between markdown and
 * code cells.
 */
.jp-RenderedHTMLCommon > *:last-child {
  margin-bottom: 0.5em;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-cursor-backdrop {
  position: fixed;
  width: 200px;
  height: 200px;
  margin-top: -100px;
  margin-left: -100px;
  will-change: transform;
  z-index: 100;
}

.lm-mod-drag-image {
  will-change: transform;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-lineFormSearch {
  padding: 4px 12px;
  background-color: var(--jp-layout-color2);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
  font-size: var(--jp-ui-font-size1);
}

.jp-lineFormCaption {
  font-size: var(--jp-ui-font-size0);
  line-height: var(--jp-ui-font-size1);
  margin-top: 4px;
  color: var(--jp-ui-font-color0);
}

.jp-baseLineForm {
  border: none;
  border-radius: 0;
  position: absolute;
  background-size: 16px;
  background-repeat: no-repeat;
  background-position: center;
  outline: none;
}

.jp-lineFormButtonContainer {
  top: 4px;
  right: 8px;
  height: 24px;
  padding: 0 12px;
  width: 12px;
}

.jp-lineFormButtonIcon {
  top: 0;
  right: 0;
  background-color: var(--jp-brand-color1);
  height: 100%;
  width: 100%;
  box-sizing: border-box;
  padding: 4px 6px;
}

.jp-lineFormButton {
  top: 0;
  right: 0;
  background-color: transparent;
  height: 100%;
  width: 100%;
  box-sizing: border-box;
}

.jp-lineFormWrapper {
  overflow: hidden;
  padding: 0 8px;
  border: 1px solid var(--jp-border-color0);
  background-color: var(--jp-input-active-background);
  height: 22px;
}

.jp-lineFormWrapperFocusWithin {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-lineFormInput {
  background: transparent;
  width: 200px;
  height: 100%;
  border: none;
  outline: none;
  color: var(--jp-ui-font-color0);
  line-height: 28px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-JSONEditor {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.jp-JSONEditor-host {
  flex: 1 1 auto;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0;
  background: var(--jp-layout-color0);
  min-height: 50px;
  padding: 1px;
}

.jp-JSONEditor.jp-mod-error .jp-JSONEditor-host {
  border-color: red;
  outline-color: red;
}

.jp-JSONEditor-header {
  display: flex;
  flex: 1 0 auto;
  padding: 0 0 0 12px;
}

.jp-JSONEditor-header label {
  flex: 0 0 auto;
}

.jp-JSONEditor-commitButton {
  height: 16px;
  width: 16px;
  background-size: 18px;
  background-repeat: no-repeat;
  background-position: center;
}

.jp-JSONEditor-host.jp-mod-focused {
  background-color: var(--jp-input-active-background);
  border: 1px solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

.jp-Editor.jp-mod-dropTarget {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/
.jp-DocumentSearch-input {
  border: none;
  outline: none;
  color: var(--jp-ui-font-color0);
  font-size: var(--jp-ui-font-size1);
  background-color: var(--jp-layout-color0);
  font-family: var(--jp-ui-font-family);
  padding: 2px 1px;
  resize: none;
}

.jp-DocumentSearch-overlay {
  position: absolute;
  background-color: var(--jp-toolbar-background);
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  border-left: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  top: 0;
  right: 0;
  z-index: 7;
  min-width: 405px;
  padding: 2px;
  font-size: var(--jp-ui-font-size1);

  --jp-private-document-search-button-height: 20px;
}

.jp-DocumentSearch-overlay button {
  background-color: var(--jp-toolbar-background);
  outline: 0;
}

.jp-DocumentSearch-overlay button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-overlay button:active {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-overlay-row {
  display: flex;
  align-items: center;
  margin-bottom: 2px;
}

.jp-DocumentSearch-button-content {
  display: inline-block;
  cursor: pointer;
  box-sizing: border-box;
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-button-content svg {
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-input-wrapper {
  border: var(--jp-border-width) solid var(--jp-border-color0);
  display: flex;
  background-color: var(--jp-layout-color0);
  margin: 2px;
}

.jp-DocumentSearch-input-wrapper:focus-within {
  border-color: var(--jp-cell-editor-active-border-color);
}

.jp-DocumentSearch-toggle-wrapper,
.jp-DocumentSearch-button-wrapper {
  all: initial;
  overflow: hidden;
  display: inline-block;
  border: none;
  box-sizing: border-box;
}

.jp-DocumentSearch-toggle-wrapper {
  width: 14px;
  height: 14px;
}

.jp-DocumentSearch-button-wrapper {
  width: var(--jp-private-document-search-button-height);
  height: var(--jp-private-document-search-button-height);
}

.jp-DocumentSearch-toggle-wrapper:focus,
.jp-DocumentSearch-button-wrapper:focus {
  outline: var(--jp-border-width) solid
    var(--jp-cell-editor-active-border-color);
  outline-offset: -1px;
}

.jp-DocumentSearch-toggle-wrapper,
.jp-DocumentSearch-button-wrapper,
.jp-DocumentSearch-button-content:focus {
  outline: none;
}

.jp-DocumentSearch-toggle-placeholder {
  width: 5px;
}

.jp-DocumentSearch-input-button::before {
  display: block;
  padding-top: 100%;
}

.jp-DocumentSearch-input-button-off {
  opacity: var(--jp-search-toggle-off-opacity);
}

.jp-DocumentSearch-input-button-off:hover {
  opacity: var(--jp-search-toggle-hover-opacity);
}

.jp-DocumentSearch-input-button-on {
  opacity: var(--jp-search-toggle-on-opacity);
}

.jp-DocumentSearch-index-counter {
  padding-left: 10px;
  padding-right: 10px;
  user-select: none;
  min-width: 35px;
  display: inline-block;
}

.jp-DocumentSearch-up-down-wrapper {
  display: inline-block;
  padding-right: 2px;
  margin-left: auto;
  white-space: nowrap;
}

.jp-DocumentSearch-spacer {
  margin-left: auto;
}

.jp-DocumentSearch-up-down-wrapper button {
  outline: 0;
  border: none;
  width: var(--jp-private-document-search-button-height);
  height: var(--jp-private-document-search-button-height);
  vertical-align: middle;
  margin: 1px 5px 2px;
}

.jp-DocumentSearch-up-down-button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-up-down-button:active {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-filter-button {
  border-radius: var(--jp-border-radius);
}

.jp-DocumentSearch-filter-button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-filter-button-enabled {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-filter-button-enabled:hover {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-search-options {
  padding: 0 8px;
  margin-left: 3px;
  width: 100%;
  display: grid;
  justify-content: start;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  justify-items: stretch;
}

.jp-DocumentSearch-search-filter-disabled {
  color: var(--jp-ui-font-color2);
}

.jp-DocumentSearch-search-filter {
  display: flex;
  align-items: center;
  user-select: none;
}

.jp-DocumentSearch-regex-error {
  color: var(--jp-error-color0);
}

.jp-DocumentSearch-replace-button-wrapper {
  overflow: hidden;
  display: inline-block;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color0);
  margin: auto 2px;
  padding: 1px 4px;
  height: calc(var(--jp-private-document-search-button-height) + 2px);
}

.jp-DocumentSearch-replace-button-wrapper:focus {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
}

.jp-DocumentSearch-replace-button {
  display: inline-block;
  text-align: center;
  cursor: pointer;
  box-sizing: border-box;
  color: var(--jp-ui-font-color1);

  /* height - 2 * (padding of wrapper) */
  line-height: calc(var(--jp-private-document-search-button-height) - 2px);
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-replace-button:focus {
  outline: none;
}

.jp-DocumentSearch-replace-wrapper-class {
  margin-left: 14px;
  display: flex;
}

.jp-DocumentSearch-replace-toggle {
  border: none;
  background-color: var(--jp-toolbar-background);
  border-radius: var(--jp-border-radius);
}

.jp-DocumentSearch-replace-toggle:hover {
  background-color: var(--jp-layout-color2);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.cm-editor {
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  border: 0;
  border-radius: 0;
  height: auto;

  /* Changed to auto to autogrow */
}

.cm-editor pre {
  padding: 0 var(--jp-code-padding);
}

.jp-CodeMirrorEditor[data-type='inline'] .cm-dialog {
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

.jp-CodeMirrorEditor {
  cursor: text;
}

/* When zoomed out 67% and 33% on a screen of 1440 width x 900 height */
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .jp-CodeMirrorEditor[data-type='inline'] .cm-cursor {
    border-left: var(--jp-code-cursor-width1) solid
      var(--jp-editor-cursor-color);
  }
}

/* When zoomed out less than 33% */
@media screen and (min-width: 4320px) {
  .jp-CodeMirrorEditor[data-type='inline'] .cm-cursor {
    border-left: var(--jp-code-cursor-width2) solid
      var(--jp-editor-cursor-color);
  }
}

.cm-editor.jp-mod-readOnly .cm-cursor {
  display: none;
}

.jp-CollaboratorCursor {
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-top: none;
  border-bottom: 3px solid;
  background-clip: content-box;
  margin-left: -5px;
  margin-right: -5px;
}

.cm-searching,
.cm-searching span {
  /* `.cm-searching span`: we need to override syntax highlighting */
  background-color: var(--jp-search-unselected-match-background-color);
  color: var(--jp-search-unselected-match-color);
}

.cm-searching::selection,
.cm-searching span::selection {
  background-color: var(--jp-search-unselected-match-background-color);
  color: var(--jp-search-unselected-match-color);
}

.jp-current-match > .cm-searching,
.jp-current-match > .cm-searching span,
.cm-searching > .jp-current-match,
.cm-searching > .jp-current-match span {
  background-color: var(--jp-search-selected-match-background-color);
  color: var(--jp-search-selected-match-color);
}

.jp-current-match > .cm-searching::selection,
.cm-searching > .jp-current-match::selection,
.jp-current-match > .cm-searching span::selection {
  background-color: var(--jp-search-selected-match-background-color);
  color: var(--jp-search-selected-match-color);
}

.cm-trailingspace {
  background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAgAAAAFCAYAAAB4ka1VAAAAsElEQVQIHQGlAFr/AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA7+r3zKmT0/+pk9P/7+r3zAAAAAAAAAAABAAAAAAAAAAA6OPzM+/q9wAAAAAA6OPzMwAAAAAAAAAAAgAAAAAAAAAAGR8NiRQaCgAZIA0AGR8NiQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQyoYJ/SY80UAAAAASUVORK5CYII=);
  background-position: center left;
  background-repeat: repeat-x;
}

.jp-CollaboratorCursor-hover {
  position: absolute;
  z-index: 1;
  transform: translateX(-50%);
  color: white;
  border-radius: 3px;
  padding-left: 4px;
  padding-right: 4px;
  padding-top: 1px;
  padding-bottom: 1px;
  text-align: center;
  font-size: var(--jp-ui-font-size1);
  white-space: nowrap;
}

.jp-CodeMirror-ruler {
  border-left: 1px dashed var(--jp-border-color2);
}

/* Styles for shared cursors (remote cursor locations and selected ranges) */
.jp-CodeMirrorEditor .cm-ySelectionCaret {
  position: relative;
  border-left: 1px solid black;
  margin-left: -1px;
  margin-right: -1px;
  box-sizing: border-box;
}

.jp-CodeMirrorEditor .cm-ySelectionCaret > .cm-ySelectionInfo {
  white-space: nowrap;
  position: absolute;
  top: -1.15em;
  padding-bottom: 0.05em;
  left: -1px;
  font-size: 0.95em;
  font-family: var(--jp-ui-font-family);
  font-weight: bold;
  line-height: normal;
  user-select: none;
  color: white;
  padding-left: 2px;
  padding-right: 2px;
  z-index: 101;
  transition: opacity 0.3s ease-in-out;
}

.jp-CodeMirrorEditor .cm-ySelectionInfo {
  transition-delay: 0.7s;
  opacity: 0;
}

.jp-CodeMirrorEditor .cm-ySelectionCaret:hover > .cm-ySelectionInfo {
  opacity: 1;
  transition-delay: 0s;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MimeDocument {
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-filebrowser-button-height: 28px;
  --jp-private-filebrowser-button-width: 48px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FileBrowser .jp-SidePanel-content {
  display: flex;
  flex-direction: column;
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  flex-wrap: wrap;
  row-gap: 12px;
  border-bottom: none;
  height: auto;
  margin: 8px 12px 0;
  box-shadow: none;
  padding: 0;
  justify-content: flex-start;
}

.jp-FileBrowser-Panel {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
}

.jp-BreadCrumbs {
  flex: 0 0 auto;
  margin: 8px 12px;
}

.jp-BreadCrumbs-item {
  margin: 0 2px;
  padding: 0 2px;
  border-radius: var(--jp-border-radius);
  cursor: pointer;
}

.jp-BreadCrumbs-item:hover {
  background-color: var(--jp-layout-color2);
}

.jp-BreadCrumbs-item:first-child {
  margin-left: 0;
}

.jp-BreadCrumbs-item.jp-mod-dropTarget {
  background-color: var(--jp-brand-color2);
  opacity: 0.7;
}

/*-----------------------------------------------------------------------------
| Buttons
|----------------------------------------------------------------------------*/

.jp-FileBrowser-toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  padding-left: 0;
  padding-right: 2px;
  align-items: center;
  height: unset;
}

.jp-FileBrowser-toolbar > .jp-Toolbar-item .jp-ToolbarButtonComponent {
  width: 40px;
}

/*-----------------------------------------------------------------------------
| Other styles
|----------------------------------------------------------------------------*/

.jp-FileDialog.jp-mod-conflict input {
  color: var(--jp-error-color1);
}

.jp-FileDialog .jp-new-name-title {
  margin-top: 12px;
}

.jp-LastModified-hidden {
  display: none;
}

.jp-FileSize-hidden {
  display: none;
}

.jp-FileBrowser .lm-AccordionPanel > h3:first-child {
  display: none;
}

/*-----------------------------------------------------------------------------
| DirListing
|----------------------------------------------------------------------------*/

.jp-DirListing {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
  outline: 0;
}

.jp-DirListing-header {
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  align-items: center;
  overflow: hidden;
  border-top: var(--jp-border-width) solid var(--jp-border-color2);
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
}

.jp-DirListing-headerItem {
  padding: 4px 12px 2px;
  font-weight: 500;
}

.jp-DirListing-headerItem:hover {
  background: var(--jp-layout-color2);
}

.jp-DirListing-headerItem.jp-id-name {
  flex: 1 0 84px;
}

.jp-DirListing-headerItem.jp-id-modified {
  flex: 0 0 112px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-DirListing-headerItem.jp-id-filesize {
  flex: 0 0 75px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-id-narrow {
  display: none;
  flex: 0 0 5px;
  padding: 4px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
  color: var(--jp-border-color2);
}

.jp-DirListing-narrow .jp-id-narrow {
  display: block;
}

.jp-DirListing-narrow .jp-id-modified,
.jp-DirListing-narrow .jp-DirListing-itemModified {
  display: none;
}

.jp-DirListing-headerItem.jp-mod-selected {
  font-weight: 600;
}

/* increase specificity to override bundled default */
.jp-DirListing-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-content mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.jp-DirListing-content .jp-DirListing-item.jp-mod-selected mark {
  color: var(--jp-ui-inverse-font-color0);
}

/* Style the directory listing content when a user drops a file to upload */
.jp-DirListing.jp-mod-native-drop .jp-DirListing-content {
  outline: 5px dashed rgba(128, 128, 128, 0.5);
  outline-offset: -10px;
  cursor: copy;
}

.jp-DirListing-item {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 4px 12px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-DirListing-checkboxWrapper {
  /* Increases hit area of checkbox. */
  padding: 4px;
}

.jp-DirListing-header
  .jp-DirListing-checkboxWrapper
  + .jp-DirListing-headerItem {
  padding-left: 4px;
}

.jp-DirListing-content .jp-DirListing-checkboxWrapper {
  position: relative;
  left: -4px;
  margin: -4px 0 -4px -8px;
}

.jp-DirListing-checkboxWrapper.jp-mod-visible {
  visibility: visible;
}

/* For devices that support hovering, hide checkboxes until hovered, selected...
*/
@media (hover: hover) {
  .jp-DirListing-checkboxWrapper {
    visibility: hidden;
  }

  .jp-DirListing-item:hover .jp-DirListing-checkboxWrapper,
  .jp-DirListing-item.jp-mod-selected .jp-DirListing-checkboxWrapper {
    visibility: visible;
  }
}

.jp-DirListing-item[data-is-dot] {
  opacity: 75%;
}

.jp-DirListing-item.jp-mod-selected {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.jp-DirListing-item.jp-mod-dropTarget {
  background: var(--jp-brand-color3);
}

.jp-DirListing-item:hover:not(.jp-mod-selected) {
  background: var(--jp-layout-color2);
}

.jp-DirListing-itemIcon {
  flex: 0 0 20px;
  margin-right: 4px;
}

.jp-DirListing-itemText {
  flex: 1 0 64px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  user-select: none;
}

.jp-DirListing-itemText:focus {
  outline-width: 2px;
  outline-color: var(--jp-inverse-layout-color1);
  outline-style: solid;
  outline-offset: 1px;
}

.jp-DirListing-item.jp-mod-selected .jp-DirListing-itemText:focus {
  outline-color: var(--jp-layout-color1);
}

.jp-DirListing-itemModified {
  flex: 0 0 125px;
  text-align: right;
}

.jp-DirListing-itemFileSize {
  flex: 0 0 90px;
  text-align: right;
}

.jp-DirListing-editor {
  flex: 1 0 64px;
  outline: none;
  border: none;
  color: var(--jp-ui-font-color1);
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-item.jp-mod-running .jp-DirListing-itemIcon::before {
  color: var(--jp-success-color1);
  content: '\25CF';
  font-size: 8px;
  position: absolute;
  left: -8px;
}

.jp-DirListing-item.jp-mod-running.jp-mod-selected
  .jp-DirListing-itemIcon::before {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-DirListing-item.lm-mod-drag-image,
.jp-DirListing-item.jp-mod-selected.lm-mod-drag-image {
  font-size: var(--jp-ui-font-size1);
  padding-left: 4px;
  margin-left: 4px;
  width: 160px;
  background-color: var(--jp-ui-inverse-font-color2);
  box-shadow: var(--jp-elevation-z2);
  border-radius: 0;
  color: var(--jp-ui-font-color1);
  transform: translateX(-40%) translateY(-58%);
}

.jp-Document {
  min-width: 120px;
  min-height: 120px;
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Main OutputArea
| OutputArea has a list of Outputs
|----------------------------------------------------------------------------*/

.jp-OutputArea {
  overflow-y: auto;
}

.jp-OutputArea-child {
  display: table;
  table-layout: fixed;
  width: 100%;
  overflow: hidden;
}

.jp-OutputPrompt {
  width: var(--jp-cell-prompt-width);
  color: var(--jp-cell-outprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);

  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-OutputArea-prompt {
  display: table-cell;
  vertical-align: top;
}

.jp-OutputArea-output {
  display: table-cell;
  width: 100%;
  height: auto;
  overflow: auto;
  user-select: text;
  -moz-user-select: text;
  -webkit-user-select: text;
  -ms-user-select: text;
}

.jp-OutputArea .jp-RenderedText {
  padding-left: 1ch;
}

/**
 * Prompt overlay.
 */

.jp-OutputArea-promptOverlay {
  position: absolute;
  top: 0;
  width: var(--jp-cell-prompt-width);
  height: 100%;
  opacity: 0.5;
}

.jp-OutputArea-promptOverlay:hover {
  background: var(--jp-layout-color2);
  box-shadow: inset 0 0 1px var(--jp-inverse-layout-color0);
  cursor: zoom-out;
}

.jp-mod-outputsScrolled .jp-OutputArea-promptOverlay:hover {
  cursor: zoom-in;
}

/**
 * Isolated output.
 */
.jp-OutputArea-output.jp-mod-isolated {
  width: 100%;
  display: block;
}

/*
When drag events occur, `lm-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated {
  position: relative;
}

body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/* pre */

.jp-OutputArea-output pre {
  border: none;
  margin: 0;
  padding: 0;
  overflow-x: auto;
  overflow-y: auto;
  word-break: break-all;
  word-wrap: break-word;
  white-space: pre-wrap;
}

/* tables */

.jp-OutputArea-output.jp-RenderedHTMLCommon table {
  margin-left: 0;
  margin-right: 0;
}

/* description lists */

.jp-OutputArea-output dl,
.jp-OutputArea-output dt,
.jp-OutputArea-output dd {
  display: block;
}

.jp-OutputArea-output dl {
  width: 100%;
  overflow: hidden;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dt {
  font-weight: bold;
  float: left;
  width: 20%;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dd {
  float: left;
  width: 80%;
  padding: 0;
  margin: 0;
}

.jp-TrimmedOutputs pre {
  background: var(--jp-layout-color3);
  font-size: calc(var(--jp-code-font-size) * 1.4);
  text-align: center;
  text-transform: uppercase;
}

/* Hide the gutter in case of
 *  - nested output areas (e.g. in the case of output widgets)
 *  - mirrored output areas
 */
.jp-OutputArea .jp-OutputArea .jp-OutputArea-prompt {
  display: none;
}

/* Hide empty lines in the output area, for instance due to cleared widgets */
.jp-OutputArea-prompt:empty {
  padding: 0;
  border: 0;
}

/*-----------------------------------------------------------------------------
| executeResult is added to any Output-result for the display of the object
| returned by a cell
|----------------------------------------------------------------------------*/

.jp-OutputArea-output.jp-OutputArea-executeResult {
  margin-left: 0;
  width: 100%;
}

/* Text output with the Out[] prompt needs a top padding to match the
 * alignment of the Out[] prompt itself.
 */
.jp-OutputArea-executeResult .jp-RenderedText.jp-OutputArea-output {
  padding-top: var(--jp-code-padding);
  border-top: var(--jp-border-width) solid transparent;
}

/*-----------------------------------------------------------------------------
| The Stdin output
|----------------------------------------------------------------------------*/

.jp-Stdin-prompt {
  color: var(--jp-content-font-color0);
  padding-right: var(--jp-code-padding);
  vertical-align: baseline;
  flex: 0 0 auto;
}

.jp-Stdin-input {
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  color: inherit;
  background-color: inherit;
  width: 42%;
  min-width: 200px;

  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;

  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0 0.25em;
  margin: 0 0.25em;
  flex: 0 0 70%;
}

.jp-Stdin-input::placeholder {
  opacity: 0;
}

.jp-Stdin-input:focus {
  box-shadow: none;
}

.jp-Stdin-input:focus::placeholder {
  opacity: 1;
}

/*-----------------------------------------------------------------------------
| Output Area View
|----------------------------------------------------------------------------*/

.jp-LinkedOutputView .jp-OutputArea {
  height: 100%;
  display: block;
}

.jp-LinkedOutputView .jp-OutputArea-output:only-child {
  height: 100%;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

@media print {
  .jp-OutputArea-child {
    break-inside: avoid-page;
  }
}

/*-----------------------------------------------------------------------------
| Mobile
|----------------------------------------------------------------------------*/
@media only screen and (max-width: 760px) {
  .jp-OutputPrompt {
    display: table-row;
    text-align: left;
  }

  .jp-OutputArea-child .jp-OutputArea-output {
    display: table-row;
    margin-left: var(--jp-notebook-padding);
  }
}

/* Trimmed outputs warning */
.jp-TrimmedOutputs > a {
  margin: 10px;
  text-decoration: none;
  cursor: pointer;
}

.jp-TrimmedOutputs > a:hover {
  text-decoration: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Table of Contents
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toc-active-width: 4px;
}

.jp-TableOfContents {
  display: flex;
  flex-direction: column;
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  height: 100%;
}

.jp-TableOfContents-placeholder {
  text-align: center;
}

.jp-TableOfContents-placeholderContent {
  color: var(--jp-content-font-color2);
  padding: 8px;
}

.jp-TableOfContents-placeholderContent > h3 {
  margin-bottom: var(--jp-content-heading-margin-bottom);
}

.jp-TableOfContents .jp-SidePanel-content {
  overflow-y: auto;
}

.jp-TableOfContents-tree {
  margin: 4px;
}

.jp-TableOfContents ol {
  list-style-type: none;
}

/* stylelint-disable-next-line selector-max-type */
.jp-TableOfContents li > ol {
  /* Align left border with triangle icon center */
  padding-left: 11px;
}

.jp-TableOfContents-content {
  /* left margin for the active heading indicator */
  margin: 0 0 0 var(--jp-private-toc-active-width);
  padding: 0;
  background-color: var(--jp-layout-color1);
}

.jp-tocItem {
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-tocItem-heading {
  display: flex;
  cursor: pointer;
}

.jp-tocItem-heading:hover {
  background-color: var(--jp-layout-color2);
}

.jp-tocItem-content {
  display: block;
  padding: 4px 0;
  white-space: nowrap;
  text-overflow: ellipsis;
  overflow-x: hidden;
}

.jp-tocItem-collapser {
  height: 20px;
  margin: 2px 2px 0;
  padding: 0;
  background: none;
  border: none;
  cursor: pointer;
}

.jp-tocItem-collapser:hover {
  background-color: var(--jp-layout-color3);
}

/* Active heading indicator */

.jp-tocItem-heading::before {
  content: ' ';
  background: transparent;
  width: var(--jp-private-toc-active-width);
  height: 24px;
  position: absolute;
  left: 0;
  border-radius: var(--jp-border-radius);
}

.jp-tocItem-heading.jp-tocItem-active::before {
  background-color: var(--jp-brand-color1);
}

.jp-tocItem-heading:hover.jp-tocItem-active::before {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapser {
  flex: 0 0 var(--jp-cell-collapser-width);
  padding: 0;
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
  border-radius: var(--jp-border-radius);
  opacity: 1;
}

.jp-Collapser-child {
  display: block;
  width: 100%;
  box-sizing: border-box;

  /* height: 100% doesn't work because the height of its parent is computed from content */
  position: absolute;
  top: 0;
  bottom: 0;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

/*
Hiding collapsers in print mode.

Note: input and output wrappers have "display: block" propery in print mode.
*/

@media print {
  .jp-Collapser {
    display: none;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Header/Footer
|----------------------------------------------------------------------------*/

/* Hidden by zero height by default */
.jp-CellHeader,
.jp-CellFooter {
  height: 0;
  width: 100%;
  padding: 0;
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Input
|----------------------------------------------------------------------------*/

/* All input areas */
.jp-InputArea {
  display: table;
  table-layout: fixed;
  width: 100%;
  overflow: hidden;
}

.jp-InputArea-editor {
  display: table-cell;
  overflow: hidden;
  vertical-align: top;

  /* This is the non-active, default styling */
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0;
  background: var(--jp-cell-editor-background);
}

.jp-InputPrompt {
  display: table-cell;
  vertical-align: top;
  width: var(--jp-cell-prompt-width);
  color: var(--jp-cell-inprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  opacity: var(--jp-cell-prompt-opacity);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;

  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

/*-----------------------------------------------------------------------------
| Mobile
|----------------------------------------------------------------------------*/
@media only screen and (max-width: 760px) {
  .jp-InputArea-editor {
    display: table-row;
    margin-left: var(--jp-notebook-padding);
  }

  .jp-InputPrompt {
    display: table-row;
    text-align: left;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Placeholder {
  display: table;
  table-layout: fixed;
  width: 100%;
}

.jp-Placeholder-prompt {
  display: table-cell;
  box-sizing: border-box;
}

.jp-Placeholder-content {
  display: table-cell;
  padding: 4px 6px;
  border: 1px solid transparent;
  border-radius: 0;
  background: none;
  box-sizing: border-box;
  cursor: pointer;
}

.jp-Placeholder-contentContainer {
  display: flex;
}

.jp-Placeholder-content:hover,
.jp-InputPlaceholder > .jp-Placeholder-content:hover {
  border-color: var(--jp-layout-color3);
}

.jp-Placeholder-content .jp-MoreHorizIcon {
  width: 32px;
  height: 16px;
  border: 1px solid transparent;
  border-radius: var(--jp-border-radius);
}

.jp-Placeholder-content .jp-MoreHorizIcon:hover {
  border: 1px solid var(--jp-border-color1);
  box-shadow: 0 0 2px 0 rgba(0, 0, 0, 0.25);
  background-color: var(--jp-layout-color0);
}

.jp-PlaceholderText {
  white-space: nowrap;
  overflow-x: hidden;
  color: var(--jp-inverse-layout-color3);
  font-family: var(--jp-code-font-family);
}

.jp-InputPlaceholder > .jp-Placeholder-content {
  border-color: var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-cell-scrolling-output-offset: 5px;
}

/*-----------------------------------------------------------------------------
| Cell
|----------------------------------------------------------------------------*/

.jp-Cell {
  padding: var(--jp-cell-padding);
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Common input/output
|----------------------------------------------------------------------------*/

.jp-Cell-inputWrapper,
.jp-Cell-outputWrapper {
  display: flex;
  flex-direction: row;
  padding: 0;
  margin: 0;

  /* Added to reveal the box-shadow on the input and output collapsers. */
  overflow: visible;
}

/* Only input/output areas inside cells */
.jp-Cell-inputArea,
.jp-Cell-outputArea {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Collapser
|----------------------------------------------------------------------------*/

/* Make the output collapser disappear when there is not output, but do so
 * in a manner that leaves it in the layout and preserves its width.
 */
.jp-Cell.jp-mod-noOutputs .jp-Cell-outputCollapser {
  border: none !important;
  background: transparent !important;
}

.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputCollapser {
  min-height: var(--jp-cell-collapser-min-height);
}

/*-----------------------------------------------------------------------------
| Output
|----------------------------------------------------------------------------*/

/* Put a space between input and output when there IS output */
.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputWrapper {
  margin-top: 5px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea {
  overflow-y: auto;
  max-height: 24em;
  margin-left: var(--jp-private-cell-scrolling-output-offset);
  resize: vertical;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea[style*='height'] {
  max-height: unset;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea::after {
  content: ' ';
  box-shadow: inset 0 0 6px 2px rgb(0 0 0 / 30%);
  width: 100%;
  height: 100%;
  position: sticky;
  bottom: 0;
  top: 0;
  margin-top: -50%;
  float: left;
  display: block;
  pointer-events: none;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-child {
  padding-top: 6px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  width: calc(
    var(--jp-cell-prompt-width) - var(--jp-private-cell-scrolling-output-offset)
  );
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-promptOverlay {
  left: calc(-1 * var(--jp-private-cell-scrolling-output-offset));
}

/*-----------------------------------------------------------------------------
| CodeCell
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| MarkdownCell
|----------------------------------------------------------------------------*/

.jp-MarkdownOutput {
  display: table-cell;
  width: 100%;
  margin-top: 0;
  margin-bottom: 0;
  padding-left: var(--jp-code-padding);
}

.jp-MarkdownOutput.jp-RenderedHTMLCommon {
  overflow: auto;
}

/* collapseHeadingButton (show always if hiddenCellsButton is _not_ shown) */
.jp-collapseHeadingButton {
  display: flex;
  min-height: var(--jp-cell-collapser-min-height);
  font-size: var(--jp-code-font-size);
  position: absolute;
  background-color: transparent;
  background-size: 25px;
  background-repeat: no-repeat;
  background-position-x: center;
  background-position-y: top;
  background-image: var(--jp-icon-caret-down);
  right: 0;
  top: 0;
  bottom: 0;
}

.jp-collapseHeadingButton.jp-mod-collapsed {
  background-image: var(--jp-icon-caret-right);
}

/*
 set the container font size to match that of content
 so that the nested collapse buttons have the right size
*/
.jp-MarkdownCell .jp-InputPrompt {
  font-size: var(--jp-content-font-size1);
}

/*
  Align collapseHeadingButton with cell top header
  The font sizes are identical to the ones in packages/rendermime/style/base.css
*/
.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='1'] {
  font-size: var(--jp-content-font-size5);
  background-position-y: calc(0.3 * var(--jp-content-font-size5));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='2'] {
  font-size: var(--jp-content-font-size4);
  background-position-y: calc(0.3 * var(--jp-content-font-size4));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='3'] {
  font-size: var(--jp-content-font-size3);
  background-position-y: calc(0.3 * var(--jp-content-font-size3));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='4'] {
  font-size: var(--jp-content-font-size2);
  background-position-y: calc(0.3 * var(--jp-content-font-size2));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='5'] {
  font-size: var(--jp-content-font-size1);
  background-position-y: top;
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='6'] {
  font-size: var(--jp-content-font-size0);
  background-position-y: top;
}

/* collapseHeadingButton (show only on (hover,active) if hiddenCellsButton is shown) */
.jp-Notebook.jp-mod-showHiddenCellsButton .jp-collapseHeadingButton {
  display: none;
}

.jp-Notebook.jp-mod-showHiddenCellsButton
  :is(.jp-MarkdownCell:hover, .jp-mod-active)
  .jp-collapseHeadingButton {
  display: flex;
}

/* showHiddenCellsButton (only show if jp-mod-showHiddenCellsButton is set, which
is a consequence of the showHiddenCellsButton option in Notebook Settings)*/
.jp-Notebook.jp-mod-showHiddenCellsButton .jp-showHiddenCellsButton {
  margin-left: calc(var(--jp-cell-prompt-width) + 2 * var(--jp-code-padding));
  margin-top: var(--jp-code-padding);
  border: 1px solid var(--jp-border-color2);
  background-color: var(--jp-border-color3) !important;
  color: var(--jp-content-font-color0) !important;
  display: flex;
}

.jp-Notebook.jp-mod-showHiddenCellsButton .jp-showHiddenCellsButton:hover {
  background-color: var(--jp-border-color2) !important;
}

.jp-showHiddenCellsButton {
  display: none;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

/*
Using block instead of flex to allow the use of the break-inside CSS property for
cell outputs.
*/

@media print {
  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-notebook-toolbar-padding: 2px 5px 2px 2px;
}

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-NotebookPanel-toolbar {
  padding: var(--jp-notebook-toolbar-padding);

  /* disable paint containment from lumino 2.0 default strict CSS containment */
  contain: style size !important;
}

.jp-Toolbar-item.jp-Notebook-toolbarCellType .jp-select-wrapper.jp-mod-focused {
  border: none;
  box-shadow: none;
}

.jp-Notebook-toolbarCellTypeDropdown select {
  height: 24px;
  font-size: var(--jp-ui-font-size1);
  line-height: 14px;
  border-radius: 0;
  display: block;
}

.jp-Notebook-toolbarCellTypeDropdown span {
  top: 5px !important;
}

.jp-Toolbar-responsive-popup {
  position: absolute;
  height: fit-content;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: flex-end;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: var(--jp-notebook-toolbar-padding);
  z-index: 1;
  right: 0;
  top: 0;
}

.jp-Toolbar > .jp-Toolbar-responsive-opener {
  margin-left: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-Notebook-ExecutionIndicator {
  position: relative;
  display: inline-block;
  height: 100%;
  z-index: 9997;
}

.jp-Notebook-ExecutionIndicator-tooltip {
  visibility: hidden;
  height: auto;
  width: max-content;
  width: -moz-max-content;
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color1);
  text-align: justify;
  border-radius: 6px;
  padding: 0 5px;
  position: fixed;
  display: table;
}

.jp-Notebook-ExecutionIndicator-tooltip.up {
  transform: translateX(-50%) translateY(-100%) translateY(-32px);
}

.jp-Notebook-ExecutionIndicator-tooltip.down {
  transform: translateX(calc(-100% + 16px)) translateY(5px);
}

.jp-Notebook-ExecutionIndicator-tooltip.hidden {
  display: none;
}

.jp-Notebook-ExecutionIndicator:hover .jp-Notebook-ExecutionIndicator-tooltip {
  visibility: visible;
}

.jp-Notebook-ExecutionIndicator span {
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  color: var(--jp-ui-font-color1);
  line-height: 24px;
  display: block;
}

.jp-Notebook-ExecutionIndicator-progress-bar {
  display: flex;
  justify-content: center;
  height: 100%;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*
 * Execution indicator
 */
.jp-tocItem-content::after {
  content: '';

  /* Must be identical to form a circle */
  width: 12px;
  height: 12px;
  background: none;
  border: none;
  position: absolute;
  right: 0;
}

.jp-tocItem-content[data-running='0']::after {
  border-radius: 50%;
  border: var(--jp-border-width) solid var(--jp-inverse-layout-color3);
  background: none;
}

.jp-tocItem-content[data-running='1']::after {
  border-radius: 50%;
  border: var(--jp-border-width) solid var(--jp-inverse-layout-color3);
  background-color: var(--jp-inverse-layout-color3);
}

.jp-tocItem-content[data-running='0'],
.jp-tocItem-content[data-running='1'] {
  margin-right: 12px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-Notebook-footer {
  height: 27px;
  margin-left: calc(
    var(--jp-cell-prompt-width) + var(--jp-cell-collapser-width) +
      var(--jp-cell-padding)
  );
  width: calc(
    100% -
      (
        var(--jp-cell-prompt-width) + var(--jp-cell-collapser-width) +
          var(--jp-cell-padding) + var(--jp-cell-padding)
      )
  );
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  color: var(--jp-ui-font-color3);
  margin-top: 6px;
  background: none;
  cursor: pointer;
}

.jp-Notebook-footer:focus {
  border-color: var(--jp-cell-editor-active-border-color);
}

/* For devices that support hovering, hide footer until hover */
@media (hover: hover) {
  .jp-Notebook-footer {
    opacity: 0;
  }

  .jp-Notebook-footer:focus,
  .jp-Notebook-footer:hover {
    opacity: 1;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Imports
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-side-by-side-output-size: 1fr;
  --jp-side-by-side-resized-cell: var(--jp-side-by-side-output-size);
  --jp-private-notebook-dragImage-width: 304px;
  --jp-private-notebook-dragImage-height: 36px;
  --jp-private-notebook-selected-color: var(--md-blue-400);
  --jp-private-notebook-active-color: var(--md-green-400);
}

/*-----------------------------------------------------------------------------
| Notebook
|----------------------------------------------------------------------------*/

/* stylelint-disable selector-max-class */

.jp-NotebookPanel {
  display: block;
  height: 100%;
}

.jp-NotebookPanel.jp-Document {
  min-width: 240px;
  min-height: 120px;
}

.jp-Notebook {
  padding: var(--jp-notebook-padding);
  outline: none;
  overflow: auto;
  background: var(--jp-layout-color0);
}

.jp-Notebook.jp-mod-scrollPastEnd::after {
  display: block;
  content: '';
  min-height: var(--jp-notebook-scroll-padding);
}

.jp-MainAreaWidget-ContainStrict .jp-Notebook * {
  contain: strict;
}

.jp-Notebook .jp-Cell {
  overflow: visible;
}

.jp-Notebook .jp-Cell .jp-InputPrompt {
  cursor: move;
}

/*-----------------------------------------------------------------------------
| Notebook state related styling
|
| The notebook and cells each have states, here are the possibilities:
|
| - Notebook
|   - Command
|   - Edit
| - Cell
|   - None
|   - Active (only one can be active)
|   - Selected (the cells actions are applied to)
|   - Multiselected (when multiple selected, the cursor)
|   - No outputs
|----------------------------------------------------------------------------*/

/* Command or edit modes */

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-InputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-OutputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

/* cell is active */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser {
  background: var(--jp-brand-color1);
}

/* cell is dirty */
.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt {
  color: var(--jp-warn-color1);
}

.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt::before {
  color: var(--jp-warn-color1);
  content: '•';
}

.jp-Notebook .jp-Cell.jp-mod-active.jp-mod-dirty .jp-Collapser {
  background: var(--jp-warn-color1);
}

/* collapser is hovered */
.jp-Notebook .jp-Cell .jp-Collapser:hover {
  box-shadow: var(--jp-elevation-z2);
  background: var(--jp-brand-color1);
  opacity: var(--jp-cell-collapser-not-active-hover-opacity);
}

/* cell is active and collapser is hovered */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser:hover {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/* Command mode */

.jp-Notebook.jp-mod-commandMode .jp-Cell.jp-mod-selected {
  background: var(--jp-notebook-multiselected-color);
}

.jp-Notebook.jp-mod-commandMode
  .jp-Cell.jp-mod-active.jp-mod-selected:not(.jp-mod-multiSelected) {
  background: transparent;
}

/* Edit mode */

.jp-Notebook.jp-mod-editMode .jp-Cell.jp-mod-active .jp-InputArea-editor {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-cell-editor-active-background);
}

/*-----------------------------------------------------------------------------
| Notebook drag and drop
|----------------------------------------------------------------------------*/

.jp-Notebook-cell.jp-mod-dropSource {
  opacity: 0.5;
}

.jp-Notebook-cell.jp-mod-dropTarget,
.jp-Notebook.jp-mod-commandMode
  .jp-Notebook-cell.jp-mod-active.jp-mod-selected.jp-mod-dropTarget {
  border-top-color: var(--jp-private-notebook-selected-color);
  border-top-style: solid;
  border-top-width: 2px;
}

.jp-dragImage {
  display: block;
  flex-direction: row;
  width: var(--jp-private-notebook-dragImage-width);
  height: var(--jp-private-notebook-dragImage-height);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
  overflow: visible;
}

.jp-dragImage-singlePrompt {
  box-shadow: 2px 2px 4px 0 rgba(0, 0, 0, 0.12);
}

.jp-dragImage .jp-dragImage-content {
  flex: 1 1 auto;
  z-index: 2;
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  line-height: var(--jp-code-line-height);
  padding: var(--jp-code-padding);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background-color);
  color: var(--jp-content-font-color3);
  text-align: left;
  margin: 4px 4px 4px 0;
}

.jp-dragImage .jp-dragImage-prompt {
  flex: 0 0 auto;
  min-width: 36px;
  color: var(--jp-cell-inprompt-font-color);
  padding: var(--jp-code-padding);
  padding-left: 12px;
  font-family: var(--jp-cell-prompt-font-family);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: 1.9;
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
}

.jp-dragImage-multipleBack {
  z-index: -1;
  position: absolute;
  height: 32px;
  width: 300px;
  top: 8px;
  left: 8px;
  background: var(--jp-layout-color2);
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  box-shadow: 2px 2px 4px 0 rgba(0, 0, 0, 0.12);
}

/*-----------------------------------------------------------------------------
| Cell toolbar
|----------------------------------------------------------------------------*/

.jp-NotebookTools {
  display: block;
  min-width: var(--jp-sidebar-min-width);
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);

  /* This is needed so that all font sizing of children done in ems is
    * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  overflow: auto;
}

.jp-ActiveCellTool {
  padding: 12px 0;
  display: flex;
}

.jp-ActiveCellTool-Content {
  flex: 1 1 auto;
}

.jp-ActiveCellTool .jp-ActiveCellTool-CellContent {
  background: var(--jp-cell-editor-background);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0;
  min-height: 29px;
}

.jp-ActiveCellTool .jp-InputPrompt {
  min-width: calc(var(--jp-cell-prompt-width) * 0.75);
}

.jp-ActiveCellTool-CellContent > pre {
  padding: 5px 4px;
  margin: 0;
  white-space: normal;
}

.jp-MetadataEditorTool {
  flex-direction: column;
  padding: 12px 0;
}

.jp-RankedPanel > :not(:first-child) {
  margin-top: 12px;
}

.jp-KeySelector select.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: var(--jp-border-width) solid var(--jp-border-color1);
}

.jp-KeySelector label,
.jp-MetadataEditorTool label,
.jp-NumberSetter label {
  line-height: 1.4;
}

.jp-NotebookTools .jp-select-wrapper {
  margin-top: 4px;
  margin-bottom: 0;
}

.jp-NumberSetter input {
  width: 100%;
  margin-top: 4px;
}

.jp-NotebookTools .jp-Collapse {
  margin-top: 16px;
}

/*-----------------------------------------------------------------------------
| Presentation Mode (.jp-mod-presentationMode)
|----------------------------------------------------------------------------*/

.jp-mod-presentationMode .jp-Notebook {
  --jp-content-font-size1: var(--jp-content-presentation-font-size1);
  --jp-code-font-size: var(--jp-code-presentation-font-size);
}

.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-InputPrompt,
.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-OutputPrompt {
  flex: 0 0 110px;
}

/*-----------------------------------------------------------------------------
| Side-by-side Mode (.jp-mod-sideBySide)
|----------------------------------------------------------------------------*/
.jp-mod-sideBySide.jp-Notebook .jp-Notebook-cell {
  margin-top: 3em;
  margin-bottom: 3em;
  margin-left: 5%;
  margin-right: 5%;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell {
  display: grid;
  grid-template-columns: minmax(0, 1fr) min-content minmax(
      0,
      var(--jp-side-by-side-output-size)
    );
  grid-template-rows: auto minmax(0, 1fr) auto;
  grid-template-areas:
    'header header header'
    'input handle output'
    'footer footer footer';
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell.jp-mod-resizedCell {
  grid-template-columns: minmax(0, 1fr) min-content minmax(
      0,
      var(--jp-side-by-side-resized-cell)
    );
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellHeader {
  grid-area: header;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-Cell-inputWrapper {
  grid-area: input;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-Cell-outputWrapper {
  /* overwrite the default margin (no vertical separation needed in side by side move */
  margin-top: 0;
  grid-area: output;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellFooter {
  grid-area: footer;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellResizeHandle {
  grid-area: handle;
  user-select: none;
  display: block;
  height: 100%;
  cursor: ew-resize;
  padding: 0 var(--jp-cell-padding);
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellResizeHandle::after {
  content: '';
  display: block;
  background: var(--jp-border-color2);
  height: 100%;
  width: 5px;
}

.jp-mod-sideBySide.jp-Notebook
  .jp-CodeCell.jp-mod-resizedCell
  .jp-CellResizeHandle::after {
  background: var(--jp-border-color0);
}

.jp-CellResizeHandle {
  display: none;
}

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Cell-Placeholder {
  padding-left: 55px;
}

.jp-Cell-Placeholder-wrapper {
  background: #fff;
  border: 1px solid;
  border-color: #e5e6e9 #dfe0e4 #d0d1d5;
  border-radius: 4px;
  -webkit-border-radius: 4px;
  margin: 10px 15px;
}

.jp-Cell-Placeholder-wrapper-inner {
  padding: 15px;
  position: relative;
}

.jp-Cell-Placeholder-wrapper-body {
  background-repeat: repeat;
  background-size: 50% auto;
}

.jp-Cell-Placeholder-wrapper-body div {
  background: #f6f7f8;
  background-image: -webkit-linear-gradient(
    left,
    #f6f7f8 0%,
    #edeef1 20%,
    #f6f7f8 40%,
    #f6f7f8 100%
  );
  background-repeat: no-repeat;
  background-size: 800px 104px;
  height: 104px;
  position: absolute;
  right: 15px;
  left: 15px;
  top: 15px;
}

div.jp-Cell-Placeholder-h1 {
  top: 20px;
  height: 20px;
  left: 15px;
  width: 150px;
}

div.jp-Cell-Placeholder-h2 {
  left: 15px;
  top: 50px;
  height: 10px;
  width: 100px;
}

div.jp-Cell-Placeholder-content-1,
div.jp-Cell-Placeholder-content-2,
div.jp-Cell-Placeholder-content-3 {
  left: 15px;
  right: 15px;
  height: 10px;
}

div.jp-Cell-Placeholder-content-1 {
  top: 100px;
}

div.jp-Cell-Placeholder-content-2 {
  top: 120px;
}

div.jp-Cell-Placeholder-content-3 {
  top: 140px;
}

</style>
<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
The following CSS variables define the main, public API for styling JupyterLab.
These variables should be used by all plugins wherever possible. In other
words, plugins should not define custom colors, sizes, etc unless absolutely
necessary. This enables users to change the visual theme of JupyterLab
by changing these variables.

Many variables appear in an ordered sequence (0,1,2,3). These sequences
are designed to work well together, so for example, `--jp-border-color1` should
be used with `--jp-layout-color1`. The numbers have the following meanings:

* 0: super-primary, reserved for special emphasis
* 1: primary, most important under normal situations
* 2: secondary, next most important under normal situations
* 3: tertiary, next most important under normal situations

Throughout JupyterLab, we are mostly following principles from Google's
Material Design when selecting colors. We are not, however, following
all of MD as it is not optimized for dense, information rich UIs.
*/

:root {
  /* Elevation
   *
   * We style box-shadows using Material Design's idea of elevation. These particular numbers are taken from here:
   *
   * https://github.com/material-components/material-components-web
   * https://material-components-web.appspot.com/elevation.html
   */

  --jp-shadow-base-lightness: 0;
  --jp-shadow-umbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.2
  );
  --jp-shadow-penumbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.14
  );
  --jp-shadow-ambient-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.12
  );
  --jp-elevation-z0: none;
  --jp-elevation-z1: 0 2px 1px -1px var(--jp-shadow-umbra-color),
    0 1px 1px 0 var(--jp-shadow-penumbra-color),
    0 1px 3px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z2: 0 3px 1px -2px var(--jp-shadow-umbra-color),
    0 2px 2px 0 var(--jp-shadow-penumbra-color),
    0 1px 5px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z4: 0 2px 4px -1px var(--jp-shadow-umbra-color),
    0 4px 5px 0 var(--jp-shadow-penumbra-color),
    0 1px 10px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z6: 0 3px 5px -1px var(--jp-shadow-umbra-color),
    0 6px 10px 0 var(--jp-shadow-penumbra-color),
    0 1px 18px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z8: 0 5px 5px -3px var(--jp-shadow-umbra-color),
    0 8px 10px 1px var(--jp-shadow-penumbra-color),
    0 3px 14px 2px var(--jp-shadow-ambient-color);
  --jp-elevation-z12: 0 7px 8px -4px var(--jp-shadow-umbra-color),
    0 12px 17px 2px var(--jp-shadow-penumbra-color),
    0 5px 22px 4px var(--jp-shadow-ambient-color);
  --jp-elevation-z16: 0 8px 10px -5px var(--jp-shadow-umbra-color),
    0 16px 24px 2px var(--jp-shadow-penumbra-color),
    0 6px 30px 5px var(--jp-shadow-ambient-color);
  --jp-elevation-z20: 0 10px 13px -6px var(--jp-shadow-umbra-color),
    0 20px 31px 3px var(--jp-shadow-penumbra-color),
    0 8px 38px 7px var(--jp-shadow-ambient-color);
  --jp-elevation-z24: 0 11px 15px -7px var(--jp-shadow-umbra-color),
    0 24px 38px 3px var(--jp-shadow-penumbra-color),
    0 9px 46px 8px var(--jp-shadow-ambient-color);

  /* Borders
   *
   * The following variables, specify the visual styling of borders in JupyterLab.
   */

  --jp-border-width: 1px;
  --jp-border-color0: var(--md-grey-400);
  --jp-border-color1: var(--md-grey-400);
  --jp-border-color2: var(--md-grey-300);
  --jp-border-color3: var(--md-grey-200);
  --jp-inverse-border-color: var(--md-grey-600);
  --jp-border-radius: 2px;

  /* UI Fonts
   *
   * The UI font CSS variables are used for the typography all of the JupyterLab
   * user interface elements that are not directly user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-ui-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-ui-font-scale-factor: 1.2;
  --jp-ui-font-size0: 0.83333em;
  --jp-ui-font-size1: 13px; /* Base font size */
  --jp-ui-font-size2: 1.2em;
  --jp-ui-font-size3: 1.44em;
  --jp-ui-font-family: system-ui, -apple-system, blinkmacsystemfont, 'Segoe UI',
    helvetica, arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',
    'Segoe UI Symbol';

  /*
   * Use these font colors against the corresponding main layout colors.
   * In a light theme, these go from dark to light.
   */

  /* Defaults use Material Design specification */
  --jp-ui-font-color0: rgba(0, 0, 0, 1);
  --jp-ui-font-color1: rgba(0, 0, 0, 0.87);
  --jp-ui-font-color2: rgba(0, 0, 0, 0.54);
  --jp-ui-font-color3: rgba(0, 0, 0, 0.38);

  /*
   * Use these against the brand/accent/warn/error colors.
   * These will typically go from light to darker, in both a dark and light theme.
   */

  --jp-ui-inverse-font-color0: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color1: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color2: rgba(255, 255, 255, 0.7);
  --jp-ui-inverse-font-color3: rgba(255, 255, 255, 0.5);

  /* Content Fonts
   *
   * Content font variables are used for typography of user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-content-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-content-line-height: 1.6;
  --jp-content-font-scale-factor: 1.2;
  --jp-content-font-size0: 0.83333em;
  --jp-content-font-size1: 14px; /* Base font size */
  --jp-content-font-size2: 1.2em;
  --jp-content-font-size3: 1.44em;
  --jp-content-font-size4: 1.728em;
  --jp-content-font-size5: 2.0736em;

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-content-presentation-font-size1: 17px;
  --jp-content-heading-line-height: 1;
  --jp-content-heading-margin-top: 1.2em;
  --jp-content-heading-margin-bottom: 0.8em;
  --jp-content-heading-font-weight: 500;

  /* Defaults use Material Design specification */
  --jp-content-font-color0: rgba(0, 0, 0, 1);
  --jp-content-font-color1: rgba(0, 0, 0, 0.87);
  --jp-content-font-color2: rgba(0, 0, 0, 0.54);
  --jp-content-font-color3: rgba(0, 0, 0, 0.38);
  --jp-content-link-color: var(--md-blue-900);
  --jp-content-font-family: system-ui, -apple-system, blinkmacsystemfont,
    'Segoe UI', helvetica, arial, sans-serif, 'Apple Color Emoji',
    'Segoe UI Emoji', 'Segoe UI Symbol';

  /*
   * Code Fonts
   *
   * Code font variables are used for typography of code and other monospaces content.
   */

  --jp-code-font-size: 13px;
  --jp-code-line-height: 1.3077; /* 17px for 13px base */
  --jp-code-padding: 5px; /* 5px for 13px base, codemirror highlighting needs integer px value */
  --jp-code-font-family-default: menlo, consolas, 'DejaVu Sans Mono', monospace;
  --jp-code-font-family: var(--jp-code-font-family-default);

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-code-presentation-font-size: 16px;

  /* may need to tweak cursor width if you change font size */
  --jp-code-cursor-width0: 1.4px;
  --jp-code-cursor-width1: 2px;
  --jp-code-cursor-width2: 4px;

  /* Layout
   *
   * The following are the main layout colors use in JupyterLab. In a light
   * theme these would go from light to dark.
   */

  --jp-layout-color0: white;
  --jp-layout-color1: white;
  --jp-layout-color2: var(--md-grey-200);
  --jp-layout-color3: var(--md-grey-400);
  --jp-layout-color4: var(--md-grey-600);

  /* Inverse Layout
   *
   * The following are the inverse layout colors use in JupyterLab. In a light
   * theme these would go from dark to light.
   */

  --jp-inverse-layout-color0: #111;
  --jp-inverse-layout-color1: var(--md-grey-900);
  --jp-inverse-layout-color2: var(--md-grey-800);
  --jp-inverse-layout-color3: var(--md-grey-700);
  --jp-inverse-layout-color4: var(--md-grey-600);

  /* Brand/accent */

  --jp-brand-color0: var(--md-blue-900);
  --jp-brand-color1: var(--md-blue-700);
  --jp-brand-color2: var(--md-blue-300);
  --jp-brand-color3: var(--md-blue-100);
  --jp-brand-color4: var(--md-blue-50);
  --jp-accent-color0: var(--md-green-900);
  --jp-accent-color1: var(--md-green-700);
  --jp-accent-color2: var(--md-green-300);
  --jp-accent-color3: var(--md-green-100);

  /* State colors (warn, error, success, info) */

  --jp-warn-color0: var(--md-orange-900);
  --jp-warn-color1: var(--md-orange-700);
  --jp-warn-color2: var(--md-orange-300);
  --jp-warn-color3: var(--md-orange-100);
  --jp-error-color0: var(--md-red-900);
  --jp-error-color1: var(--md-red-700);
  --jp-error-color2: var(--md-red-300);
  --jp-error-color3: var(--md-red-100);
  --jp-success-color0: var(--md-green-900);
  --jp-success-color1: var(--md-green-700);
  --jp-success-color2: var(--md-green-300);
  --jp-success-color3: var(--md-green-100);
  --jp-info-color0: var(--md-cyan-900);
  --jp-info-color1: var(--md-cyan-700);
  --jp-info-color2: var(--md-cyan-300);
  --jp-info-color3: var(--md-cyan-100);

  /* Cell specific styles */

  --jp-cell-padding: 5px;
  --jp-cell-collapser-width: 8px;
  --jp-cell-collapser-min-height: 20px;
  --jp-cell-collapser-not-active-hover-opacity: 0.6;
  --jp-cell-editor-background: var(--md-grey-100);
  --jp-cell-editor-border-color: var(--md-grey-300);
  --jp-cell-editor-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-cell-editor-active-background: var(--jp-layout-color0);
  --jp-cell-editor-active-border-color: var(--jp-brand-color1);
  --jp-cell-prompt-width: 64px;
  --jp-cell-prompt-font-family: var(--jp-code-font-family-default);
  --jp-cell-prompt-letter-spacing: 0;
  --jp-cell-prompt-opacity: 1;
  --jp-cell-prompt-not-active-opacity: 0.5;
  --jp-cell-prompt-not-active-font-color: var(--md-grey-700);

  /* A custom blend of MD grey and blue 600
   * See https://meyerweb.com/eric/tools/color-blend/#546E7A:1E88E5:5:hex */
  --jp-cell-inprompt-font-color: #307fc1;

  /* A custom blend of MD grey and orange 600
   * https://meyerweb.com/eric/tools/color-blend/#546E7A:F4511E:5:hex */
  --jp-cell-outprompt-font-color: #bf5b3d;

  /* Notebook specific styles */

  --jp-notebook-padding: 10px;
  --jp-notebook-select-background: var(--jp-layout-color1);
  --jp-notebook-multiselected-color: var(--md-blue-50);

  /* The scroll padding is calculated to fill enough space at the bottom of the
  notebook to show one single-line cell (with appropriate padding) at the top
  when the notebook is scrolled all the way to the bottom. We also subtract one
  pixel so that no scrollbar appears if we have just one single-line cell in the
  notebook. This padding is to enable a 'scroll past end' feature in a notebook.
  */
  --jp-notebook-scroll-padding: calc(
    100% - var(--jp-code-font-size) * var(--jp-code-line-height) -
      var(--jp-code-padding) - var(--jp-cell-padding) - 1px
  );

  /* Rendermime styles */

  --jp-rendermime-error-background: #fdd;
  --jp-rendermime-table-row-background: var(--md-grey-100);
  --jp-rendermime-table-row-hover-background: var(--md-light-blue-50);

  /* Dialog specific styles */

  --jp-dialog-background: rgba(0, 0, 0, 0.25);

  /* Console specific styles */

  --jp-console-padding: 10px;

  /* Toolbar specific styles */

  --jp-toolbar-border-color: var(--jp-border-color1);
  --jp-toolbar-micro-height: 8px;
  --jp-toolbar-background: var(--jp-layout-color1);
  --jp-toolbar-box-shadow: 0 0 2px 0 rgba(0, 0, 0, 0.24);
  --jp-toolbar-header-margin: 4px 4px 0 4px;
  --jp-toolbar-active-background: var(--md-grey-300);

  /* Statusbar specific styles */

  --jp-statusbar-height: 24px;

  /* Input field styles */

  --jp-input-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-input-active-background: var(--jp-layout-color1);
  --jp-input-hover-background: var(--jp-layout-color1);
  --jp-input-background: var(--md-grey-100);
  --jp-input-border-color: var(--jp-inverse-border-color);
  --jp-input-active-border-color: var(--jp-brand-color1);
  --jp-input-active-box-shadow-color: rgba(19, 124, 189, 0.3);

  /* General editor styles */

  --jp-editor-selected-background: #d9d9d9;
  --jp-editor-selected-focused-background: #d7d4f0;
  --jp-editor-cursor-color: var(--jp-ui-font-color0);

  /* Code mirror specific styles */

  --jp-mirror-editor-keyword-color: #008000;
  --jp-mirror-editor-atom-color: #88f;
  --jp-mirror-editor-number-color: #080;
  --jp-mirror-editor-def-color: #00f;
  --jp-mirror-editor-variable-color: var(--md-grey-900);
  --jp-mirror-editor-variable-2-color: rgb(0, 54, 109);
  --jp-mirror-editor-variable-3-color: #085;
  --jp-mirror-editor-punctuation-color: #05a;
  --jp-mirror-editor-property-color: #05a;
  --jp-mirror-editor-operator-color: #a2f;
  --jp-mirror-editor-comment-color: #408080;
  --jp-mirror-editor-string-color: #ba2121;
  --jp-mirror-editor-string-2-color: #708;
  --jp-mirror-editor-meta-color: #a2f;
  --jp-mirror-editor-qualifier-color: #555;
  --jp-mirror-editor-builtin-color: #008000;
  --jp-mirror-editor-bracket-color: #997;
  --jp-mirror-editor-tag-color: #170;
  --jp-mirror-editor-attribute-color: #00c;
  --jp-mirror-editor-header-color: blue;
  --jp-mirror-editor-quote-color: #090;
  --jp-mirror-editor-link-color: #00c;
  --jp-mirror-editor-error-color: #f00;
  --jp-mirror-editor-hr-color: #999;

  /*
    RTC user specific colors.
    These colors are used for the cursor, username in the editor,
    and the icon of the user.
  */

  --jp-collaborator-color1: #ffad8e;
  --jp-collaborator-color2: #dac83d;
  --jp-collaborator-color3: #72dd76;
  --jp-collaborator-color4: #00e4d0;
  --jp-collaborator-color5: #45d4ff;
  --jp-collaborator-color6: #e2b1ff;
  --jp-collaborator-color7: #ff9de6;

  /* Vega extension styles */

  --jp-vega-background: white;

  /* Sidebar-related styles */

  --jp-sidebar-min-width: 250px;

  /* Search-related styles */

  --jp-search-toggle-off-opacity: 0.5;
  --jp-search-toggle-hover-opacity: 0.8;
  --jp-search-toggle-on-opacity: 1;
  --jp-search-selected-match-background-color: rgb(245, 200, 0);
  --jp-search-selected-match-color: black;
  --jp-search-unselected-match-background-color: var(
    --jp-inverse-layout-color0
  );
  --jp-search-unselected-match-color: var(--jp-ui-inverse-font-color0);

  /* Icon colors that work well with light or dark backgrounds */
  --jp-icon-contrast-color0: var(--md-purple-600);
  --jp-icon-contrast-color1: var(--md-green-600);
  --jp-icon-contrast-color2: var(--md-pink-600);
  --jp-icon-contrast-color3: var(--md-blue-600);

  /* Button colors */
  --jp-accept-color-normal: var(--md-blue-700);
  --jp-accept-color-hover: var(--md-blue-800);
  --jp-accept-color-active: var(--md-blue-900);
  --jp-warn-color-normal: var(--md-red-700);
  --jp-warn-color-hover: var(--md-red-800);
  --jp-warn-color-active: var(--md-red-900);
  --jp-reject-color-normal: var(--md-grey-600);
  --jp-reject-color-hover: var(--md-grey-700);
  --jp-reject-color-active: var(--md-grey-800);

  /* File or activity icons and switch semantic variables */
  --jp-jupyter-icon-color: #f37626;
  --jp-notebook-icon-color: #f37626;
  --jp-json-icon-color: var(--md-orange-700);
  --jp-console-icon-background-color: var(--md-blue-700);
  --jp-console-icon-color: white;
  --jp-terminal-icon-background-color: var(--md-grey-800);
  --jp-terminal-icon-color: var(--md-grey-200);
  --jp-text-editor-icon-color: var(--md-grey-700);
  --jp-inspector-icon-color: var(--md-grey-700);
  --jp-switch-color: var(--md-grey-400);
  --jp-switch-true-position-color: var(--md-orange-900);
}
</style>
<style type="text/css">
/* Force rendering true colors when outputing to pdf */
* {
  -webkit-print-color-adjust: exact;
}

/* Misc */
a.anchor-link {
  display: none;
}

/* Input area styling */
.jp-InputArea {
  overflow: hidden;
}

.jp-InputArea-editor {
  overflow: hidden;
}

.cm-editor.cm-s-jupyter .highlight pre {
/* weird, but --jp-code-padding defined to be 5px but 4px horizontal padding is hardcoded for pre.cm-line */
  padding: var(--jp-code-padding) 4px;
  margin: 0;

  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
  color: inherit;

}

.jp-OutputArea-output pre {
  line-height: inherit;
  font-family: inherit;
}

.jp-RenderedText pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
}

/* Hiding the collapser by default */
.jp-Collapser {
  display: none;
}

@page {
    margin: 0.5in; /* Margin for each printed piece of paper */
}

@media print {
  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }
}
</style>
<!-- Load mathjax -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/latest.js?config=TeX-AMS_CHTML-full,Safe"> </script>
<!-- MathJax configuration -->
<script type="text/x-mathjax-config">
    init_mathjax = function() {
        if (window.MathJax) {
        // MathJax loaded
            MathJax.Hub.Config({
                TeX: {
                    equationNumbers: {
                    autoNumber: "AMS",
                    useLabelIds: true
                    }
                },
                tex2jax: {
                    inlineMath: [ ['$','$'], ["\\(","\\)"] ],
                    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
                    processEscapes: true,
                    processEnvironments: true
                },
                displayAlign: 'center',
                CommonHTML: {
                    linebreaks: {
                    automatic: true
                    }
                }
            });

            MathJax.Hub.Queue(["Typeset", MathJax.Hub]);
        }
    }
    init_mathjax();
    </script>
<!-- End of mathjax configuration --><script type="module">
  document.addEventListener("DOMContentLoaded", async () => {
    const diagrams = document.querySelectorAll(".jp-Mermaid > pre.mermaid");
    // do not load mermaidjs if not needed
    if (!diagrams.length) {
      return;
    }
    const mermaid = (await import("https://cdnjs.cloudflare.com/ajax/libs/mermaid/10.7.0/mermaid.esm.min.mjs")).default;
    const parser = new DOMParser();

    mermaid.initialize({
      maxTextSize: 100000,
      maxEdges: 100000,
      startOnLoad: false,
      fontFamily: window
        .getComputedStyle(document.body)
        .getPropertyValue("--jp-ui-font-family"),
      theme: document.querySelector("body[data-jp-theme-light='true']")
        ? "default"
        : "dark",
    });

    let _nextMermaidId = 0;

    function makeMermaidImage(svg) {
      const img = document.createElement("img");
      const doc = parser.parseFromString(svg, "image/svg+xml");
      const svgEl = doc.querySelector("svg");
      const { maxWidth } = svgEl?.style || {};
      const firstTitle = doc.querySelector("title");
      const firstDesc = doc.querySelector("desc");

      img.setAttribute("src", `data:image/svg+xml,${encodeURIComponent(svg)}`);
      if (maxWidth) {
        img.width = parseInt(maxWidth);
      }
      if (firstTitle) {
        img.setAttribute("alt", firstTitle.textContent);
      }
      if (firstDesc) {
        const caption = document.createElement("figcaption");
        caption.className = "sr-only";
        caption.textContent = firstDesc.textContent;
        return [img, caption];
      }
      return [img];
    }

    async function makeMermaidError(text) {
      let errorMessage = "";
      try {
        await mermaid.parse(text);
      } catch (err) {
        errorMessage = `${err}`;
      }

      const result = document.createElement("details");
      result.className = 'jp-RenderedMermaid-Details';
      const summary = document.createElement("summary");
      summary.className = 'jp-RenderedMermaid-Summary';
      const pre = document.createElement("pre");
      const code = document.createElement("code");
      code.innerText = text;
      pre.appendChild(code);
      summary.appendChild(pre);
      result.appendChild(summary);

      const warning = document.createElement("pre");
      warning.innerText = errorMessage;
      result.appendChild(warning);
      return [result];
    }

    async function renderOneMarmaid(src) {
      const id = `jp-mermaid-${_nextMermaidId++}`;
      const parent = src.parentNode;
      let raw = src.textContent.trim();
      const el = document.createElement("div");
      el.style.visibility = "hidden";
      document.body.appendChild(el);
      let results = null;
      let output = null;
      try {
        let { svg } = await mermaid.render(id, raw, el);
        svg = cleanMermaidSvg(svg);
        results = makeMermaidImage(svg);
        output = document.createElement("figure");
        results.map(output.appendChild, output);
      } catch (err) {
        parent.classList.add("jp-mod-warning");
        results = await makeMermaidError(raw);
        output = results[0];
      } finally {
        el.remove();
      }
      parent.classList.add("jp-RenderedMermaid");
      parent.appendChild(output);
    }


    /**
     * Post-process to ensure mermaid diagrams contain only valid SVG and XHTML.
     */
    function cleanMermaidSvg(svg) {
      return svg.replace(RE_VOID_ELEMENT, replaceVoidElement);
    }


    /**
     * A regular expression for all void elements, which may include attributes and
     * a slash.
     *
     * @see https://developer.mozilla.org/en-US/docs/Glossary/Void_element
     *
     * Of these, only `<br>` is generated by Mermaid in place of `\n`,
     * but _any_ "malformed" tag will break the SVG rendering entirely.
     */
    const RE_VOID_ELEMENT =
      /<\s*(area|base|br|col|embed|hr|img|input|link|meta|param|source|track|wbr)\s*([^>]*?)\s*>/gi;

    /**
     * Ensure a void element is closed with a slash, preserving any attributes.
     */
    function replaceVoidElement(match, tag, rest) {
      rest = rest.trim();
      if (!rest.endsWith('/')) {
        rest = `${rest} /`;
      }
      return `<${tag} ${rest}>`;
    }

    void Promise.all([...diagrams].map(renderOneMarmaid));
  });
</script>
<style>
  .jp-Mermaid:not(.jp-RenderedMermaid) {
    display: none;
  }

  .jp-RenderedMermaid {
    overflow: auto;
    display: flex;
  }

  .jp-RenderedMermaid.jp-mod-warning {
    width: auto;
    padding: 0.5em;
    margin-top: 0.5em;
    border: var(--jp-border-width) solid var(--jp-warn-color2);
    border-radius: var(--jp-border-radius);
    color: var(--jp-ui-font-color1);
    font-size: var(--jp-ui-font-size1);
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  .jp-RenderedMermaid figure {
    margin: 0;
    overflow: auto;
    max-width: 100%;
  }

  .jp-RenderedMermaid img {
    max-width: 100%;
  }

  .jp-RenderedMermaid-Details > pre {
    margin-top: 1em;
  }

  .jp-RenderedMermaid-Summary {
    color: var(--jp-warn-color2);
  }

  .jp-RenderedMermaid:not(.jp-mod-warning) pre {
    display: none;
  }

  .jp-RenderedMermaid-Summary > pre {
    display: inline-block;
    white-space: normal;
  }
</style>
<!-- End of mermaid configuration --></head>
<body class="jp-Notebook" data-jp-theme-light="true" data-jp-theme-name="JupyterLab Light">
<main>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p><a href="https://colab.research.google.com/github/mco-gh/pylearn/blob/master/notebooks/1_Welcome.ipynb" target="_parent"><img alt="Open In Colab" src="https://colab.research.google.com/assets/colab-badge.svg"/></a></p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h1 id="Notebook-1---Course-Overview,-Background,-and-Getting-Started">Notebook 1 - Course Overview, Background, and Getting Started<a class="anchor-link" href="#Notebook-1---Course-Overview,-Background,-and-Getting-Started">¶</a></h1><p><strong>You can make your own copy of this notebook by selecting File-&gt;Save a copy in Drive from the menu bar above.</strong></p>
<p>Things you'll learn in this lesson:</p>
<ul>
<li>An overview of this course</li>
<li>A brief background on computing, programming, and Python</li>
<li>Some getting start material</li>
</ul>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p><a href="https://pylearn.io/lessons/2-Variables">Next Lesson</a></p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Course-Overview">Course Overview<a class="anchor-link" href="#Course-Overview">¶</a></h2>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Course-Description">Course Description<a class="anchor-link" href="#Course-Description">¶</a></h3><p>Pylearn is...</p>
<ul>
<li><strong>inclusive</strong> - no prerequisites, perfect for beginners</li>
<li><strong>approachable</strong> - nothing to install or configure</li>
<li><strong>convenient</strong> - learn at your pace, on your schedule</li>
<li><strong>free</strong> - no fees, no ads, not now, not ever</li>
<li><strong>practical</strong> - understand not only how, but why</li>
<li><strong>respectful</strong> - we never request or store any personal information</li>
<li><strong>interactive</strong> - learn by doing, using Colab notebooks</li>
</ul>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Course-Goals">Course Goals<a class="anchor-link" href="#Course-Goals">¶</a></h3><ul>
<li>Demystify programming in general and Python in particular</li>
<li>Show how to use Python to a practical, hands-on way</li>
<li>Provide a solid foundation for diving deeper</li>
</ul>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Instructor">Instructor<a class="anchor-link" href="#Instructor">¶</a></h3><p>I'm <a href="https://mco.dev/about-marc">Marc</a>. I love teaching, programming, and teaching programming.</p>
<ul>
<li>My blog can be found at <a href="https://mco.dev">mco.dev</a>.</li>
<li>My email address is marc@mco.dev.</li>
</ul>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Target-Audience">Target Audience<a class="anchor-link" href="#Target-Audience">¶</a></h3><ul>
<li>Programming and/or Python beginners</li>
<li>Underrepresented groups in tech</li>
<li>Aspiring data scientists</li>
</ul>
<p>There are <strong>no prerequisites</strong> for this course. We'll start at the beginning.</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Syllabus">Syllabus<a class="anchor-link" href="#Syllabus">¶</a></h3><table>
<thead>
<tr>
<th>Lesson</th>
<th>Title</th>
</tr>
</thead>
<tbody>
<tr>
<td>Notebook 1</td>
<td>Course Overview, Background, and Getting Started</td>
</tr>
<tr>
<td>Notebook 2</td>
<td>Numbers, Strings, Variables, and Assignment Statements</td>
</tr>
<tr>
<td>Notebook 3</td>
<td>Boolean Comparisons, Boolean Operators, and Expressions</td>
</tr>
<tr>
<td>Notebook 4</td>
<td>Controlling Program Flow and Using Modules</td>
</tr>
<tr>
<td>Notebook 5</td>
<td>More Strings and Loops</td>
</tr>
<tr>
<td>Notebook 6</td>
<td>Functions and Modules</td>
</tr>
<tr>
<td>Notebook 7</td>
<td>Tuples, Lists, and Dictionaries</td>
</tr>
<tr>
<td>Notebook 8</td>
<td>Files and Exceptions</td>
</tr>
<tr>
<td>Notebook 9</td>
<td>Sample Project</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Some-thoughts-on-learning-to-code">Some thoughts on learning to code<a class="anchor-link" href="#Some-thoughts-on-learning-to-code">¶</a></h3><ul>
<li>Programming is a creative activity.</li>
<li>There has never been a better time in history to learn to code.</li>
<li>Anyone can learn to program, as long as you’re willing to do the work.</li>
<li>Think of it a little like learning to play a musical instrument.</li>
<li>Practice between classes is very helpful.</li>
<li>Give yourself time &amp; kindness.</li>
<li>Mistakes are feedback.</li>
<li>When you get stuck:<ul>
<li>Don’t beat yourself up.</li>
<li>Take a break.</li>
<li>Don’t be afraid to ask me or a peer for help.</li>
</ul>
</li>
<li>The dirty secret about professional programmers: <em>No one knows everything - we all use Google, Stack Overflow, and other websites all the time.</em></li>
</ul>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="What-is-a-Notebook?">What is a Notebook?<a class="anchor-link" href="#What-is-a-Notebook?">¶</a></h3><ul>
<li>You're looking at one. :)</li>
<li>Notebooks are interactive documents where you can read instructions and try your own code experiments in one unified experience.</li>
<li>The notebooks we're using are called <a href="https://jupyter.org">Jupyter</a> and the hosting service (the notebook provider) is called <a href="https://colab.research.google.com/">Google Colaboratory</a> or just "Colab". This service makes it easy to use and share Python notebooks for free, much like Google Docs.</li>
</ul>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>From the menu bar, select Tools-&gt;Command Palette to see a list of the commands you can execute inside a Colab notebook. Most of these commands are intuitively named. For example, to save your notebook in Google Drive, run "Save notebook" now from the command palette. You can find it quickly by typing "save" in the search box.</p>
<p>Don't worry if you're not sure what some of the commands in the command palette do. For now, I just want you to know about this resource.</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>Congratulations for making it this far! Your last assignment is to watch this <a href="https://www.youtube.com/watch?v=inN8seMm7UI">short video</a> and take a <a href="https://colab.research.google.com/notebooks/intro.ipynb">quick tour of Colab</a>.</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p><strong>It's a good idea to save your work after a notebook session.</strong> You can use the command palette to do this, as you just did in the previous cell, but since this is a common function, you'll see an easier way to save your notebook via the File-&gt;Save menu item.</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h4 id="When-you-run-a-cell-in-a-notebook,-where-does-it-actually-run?">When you run a cell in a notebook, where does it actually run?<a class="anchor-link" href="#When-you-run-a-cell-in-a-notebook,-where-does-it-actually-run?">¶</a></h4>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<img alt="No description has been provided for this image" src="https://lh3.googleusercontent.com/LWgdIXTXW6nO0Wi5rGpEJoZ5Hd4EtXq8gm55_wyfIcfZOs07paFyWlrlFUyl9bRCKFKpS_I3nP6O4CN8vXwWG0bV2XtAUH4X2PRWiQ=w1200-l80-sg-rj-c0xffffff"/>
<p><a href="https://www.google.com/about/datacenters/">Learn more.</a></p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Background">Background<a class="anchor-link" href="#Background">¶</a></h2>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="The-March-of-Progress">The March of Progress<a class="anchor-link" href="#The-March-of-Progress">¶</a></h3><p>The cell phone in your pocket has more computing power than all of NASA back in 1969. They used it to put two astronauts on the moon. We use it to play Candy Crush. :)</p>
<p>Learning to program gives you the power to build amazing things with your computer.</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="What-is-an-operating-system?">What is an operating system?<a class="anchor-link" href="#What-is-an-operating-system?">¶</a></h3><p>A software layer that functions as the computer’s traffic cop.</p>
<p>Operating systems provide:</p>
<ul>
<li>core system services (e.g. processes/threads, memory management)</li>
<li>abstraction of lower level services (e.g. reading a file, using the network)</li>
<li>permissions and access control (e.g. login authentication, verifying a user is allowed to access a file)</li>
<li>resource management (e.g. multiple programs sharing the CPU, multiple access to the same disk device)</li>
</ul>
<p>Popular operating systems: Windows, Linux, Android, iOS, MacOS</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="What-is-an-algorithm?">What is an algorithm?<a class="anchor-link" href="#What-is-an-algorithm?">¶</a></h3><p>A step-by-step procedure for solving a problem or accomplishing some end, especially by a computer</p>
<p>Example Algorithm: Marc’s Scrambled Eggs Recipe</p>
<p><strong>Ingredients:</strong></p>
<ul>
<li>2 eggs</li>
<li>butter</li>
</ul>
<p><strong>Cooking steps:</strong></p>
<ul>
<li>mix eggs in a bowl</li>
<li>lightly coat a frying pan with gasoline</li>
<li>heat pan to 4000 degrees</li>
<li>stir eggs until firm</li>
<li>pour mixed eggs into frying pan</li>
</ul>
<p>Just like programs, recipes can have errors, or "bugs". Can you find three bugs in this recipe?</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="What-is-a-program?">What is a program?<a class="anchor-link" href="#What-is-a-program?">¶</a></h3><ul>
<li>Encoding of an algorithm, in some particular programming language.</li>
<li>In other words, a set of instructions, which tell a computer how to do something.</li>
<li>Programming statements are called “source code” or just “code”.</li>
<li>"Coding" is just another word for programming.</li>
</ul>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="What-is-a-programming-language?">What is a programming language?<a class="anchor-link" href="#What-is-a-programming-language?">¶</a></h3><ul>
<li>A set of rules for expressing algorithms symbolically.</li>
<li>Provides an abstraction layer for using your computer to solve a problem.</li>
<li>Provides a way to reuse other peoples’ work.</li>
</ul>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Compiled-vs.-interpreted-languages">Compiled vs. interpreted languages<a class="anchor-link" href="#Compiled-vs.-interpreted-languages">¶</a></h3><img alt="No description has been provided for this image" height="300" src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*3Iy-ohRRXj3lChmEbQTxIQ.png"/>  
[Source](https://medium.com/from-the-scratch/stop-it-there-are-no-compiled-and-interpreted-languages-512f84756664)

<ul>
<li>A compiler converts one language to another (usually a high level language to low level code that can be run directly by the hardware).</li>
<li>An interpreter executes the source program one statement at a time.</li>
<li>Portability vs. performance</li>
</ul>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="What-is-Python-and-why-learn-it?">What is Python and why learn it?<a class="anchor-link" href="#What-is-Python-and-why-learn-it?">¶</a></h3><ul>
<li>an interpreted programming language that was invented in 1989 by Dutch programmer Guido van Rossum</li>
<li>powerful and expressive</li>
<li>easy to learn</li>
<li>highly readable</li>
<li>freely available open source</li>
<li>widely used &amp; well supported</li>
<li>Very strong for:<ul>
<li>AI</li>
<li>Data Science</li>
<li>Finance</li>
<li>Statistics</li>
<li>Machine Learning</li>
<li>Social Sciences</li>
<li>Web development</li>
<li>Education</li>
</ul>
</li>
<li>not a bad thing to have on your resume/CV</li>
</ul>
<p><a href="https://www.techrepublic.com/article/python-is-eating-the-world-how-one-developers-side-project-became-the-hottest-programming-language-on-the-planet/">Python is eating the world: How one developer's side project became the hottest programming language on the planet</a></p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>Here's a visualisation of programming language popularirity worldwide, as of September 2024, based on how often language tutorials are searched on Google:</p>
<img alt="No description has been provided for this image" height="300" src="https://pypl.github.io/PYPL/All.png"/>
<p><a href="https://pypl.github.io/PYPL.html">Source</a></p>
<p>And here's a graph showing language popularity as a function of Stack Overflow questions over time:</p>
<img alt="No description has been provided for this image" height="300" src="https://mco.dev/img/stackoverflow.svg"/>
<p><a href="https://trends.stackoverflow.co/?tags=java,c,python,c%23,vb.net,javascript,assembly,php,perl,ruby,swift,r,objective-c">Source</a></p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Python-execution-model">Python execution model<a class="anchor-link" href="#Python-execution-model">¶</a></h3><p><img alt="No description has been provided for this image" height="400" src="https://mco.dev/img/py.gif"/></p>
<p><a href="https://www.google.com/url?sa=i&amp;url=https%3A%2F%2Fblog.gopenai.com%2Fhow-python-works-unveiling-the-magic-behind-python-programming-c95ab99f1ee3&amp;psig=AOvVaw0cKy_Fwe-pc44QwiMoEkAK&amp;ust=1727354649845000&amp;source=images&amp;cd=vfe&amp;opi=89978449&amp;ved=0CBQQjhxqFwoTCLCK29mP3ogDFQAAAAAdAAAAABAE">Source</a></p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="The-Zen-of-Python">The Zen of Python<a class="anchor-link" href="#The-Zen-of-Python">¶</a></h3>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [2]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="kn">import</span> <span class="nn">this</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain" tabindex="0">
<pre>The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Getting-Started">Getting Started<a class="anchor-link" href="#Getting-Started">¶</a></h2>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Installing-Python">Installing Python<a class="anchor-link" href="#Installing-Python">¶</a></h3><p><img alt="No description has been provided for this image" height="400" src="https://mco.dev/img/pyinstall.png"/></p>
<p><a href="https://www.python.org/downloads/">Source</a></p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Running-a-Python-program-from-the-command-line">Running a Python program from the command line<a class="anchor-link" href="#Running-a-Python-program-from-the-command-line">¶</a></h3><p><img alt="No description has been provided for this image" height="300" src="https://mco.dev/img/pyrun.png"/></p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Example-Programs">Example Programs<a class="anchor-link" href="#Example-Programs">¶</a></h3>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h4 id="Example-1---Print-a-Multiplication-Table">Example 1 - Print a Multiplication Table<a class="anchor-link" href="#Example-1---Print-a-Multiplication-Table">¶</a></h4>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [3]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span><span class="mi">10</span><span class="p">):</span>
  <span class="nb">print</span><span class="p">(</span><span class="n">i</span><span class="p">,</span> <span class="n">end</span><span class="o">=</span><span class="s1">' '</span><span class="p">)</span>
  <span class="k">for</span> <span class="n">j</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">2</span><span class="p">,</span> <span class="mi">10</span><span class="p">):</span>
    <span class="nb">print</span><span class="p">(</span><span class="sa">f</span><span class="s1">'</span><span class="si">{</span><span class="n">i</span><span class="o">*</span><span class="n">j</span><span class="si">:</span><span class="s1">2</span><span class="si">}</span><span class="s1">'</span><span class="p">,</span> <span class="n">end</span><span class="o">=</span><span class="s1">' '</span><span class="p">)</span>
  <span class="nb">print</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain" tabindex="0">
<pre>1  2  3  4  5  6  7  8  9 
2  4  6  8 10 12 14 16 18 
3  6  9 12 15 18 21 24 27 
4  8 12 16 20 24 28 32 36 
5 10 15 20 25 30 35 40 45 
6 12 18 24 30 36 42 48 54 
7 14 21 28 35 42 49 56 63 
8 16 24 32 40 48 56 64 72 
9 18 27 36 45 54 63 72 81 
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h4 id="Example-2---Search-IMDb">Example 2 - Search IMDb<a class="anchor-link" href="#Example-2---Search-IMDb">¶</a></h4>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [4]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="err">!</span><span class="n">pip</span> <span class="n">install</span> <span class="o">-</span><span class="n">q</span> <span class="n">imdbpy</span>
<span class="kn">from</span> <span class="nn">imdb</span> <span class="kn">import</span> <span class="n">IMDb</span>
<span class="kn">from</span> <span class="nn">IPython.display</span> <span class="kn">import</span> <span class="n">Image</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain" tabindex="0">
<pre>   <span class="ansi-black-intense-fg">━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━</span> <span class="ansi-green-fg">0.0/297.2 kB</span> <span class="ansi-red-fg">?</span> eta <span class="ansi-cyan-fg">-:--:--</span>   <span class="ansi-red-intense-fg">━━━━━━━━━━━━━━━━━━━━</span><span class="ansi-red-intense-fg">╸</span><span class="ansi-black-intense-fg">━━━━━━━━━━━━━━━━━━━</span> <span class="ansi-green-fg">153.6/297.2 kB</span> <span class="ansi-red-fg">4.8 MB/s</span> eta <span class="ansi-cyan-fg">0:00:01</span>   <span class="ansi-black-intense-fg">━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━</span> <span class="ansi-green-fg">297.2/297.2 kB</span> <span class="ansi-red-fg">5.1 MB/s</span> eta <span class="ansi-cyan-fg">0:00:00</span>
</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [6]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">title</span> <span class="o">=</span> <span class="s1">'trainspotting'</span>
<span class="n">imdb</span> <span class="o">=</span> <span class="n">IMDb</span><span class="p">()</span>  <span class="c1"># create imdb API object</span>
<span class="n">results</span> <span class="o">=</span> <span class="n">imdb</span><span class="o">.</span><span class="n">search_movie</span><span class="p">(</span><span class="n">title</span><span class="p">)</span>
<span class="n">limit</span> <span class="o">=</span> <span class="mi">3</span>
<span class="n">count</span> <span class="o">=</span> <span class="mi">0</span>

<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">results</span><span class="p">:</span>
  <span class="k">if</span> <span class="n">count</span> <span class="o">&gt;</span> <span class="n">limit</span><span class="p">:</span>
    <span class="k">break</span>
  <span class="n">count</span> <span class="o">+=</span> <span class="mi">1</span>
  <span class="k">if</span> <span class="n">i</span><span class="o">.</span><span class="n">data</span><span class="p">[</span><span class="s1">'kind'</span><span class="p">]</span> <span class="o">==</span> <span class="s1">'movie'</span><span class="p">:</span>
    <span class="n">movie</span> <span class="o">=</span> <span class="n">imdb</span><span class="o">.</span><span class="n">get_movie</span><span class="p">(</span><span class="n">i</span><span class="o">.</span><span class="n">movieID</span><span class="p">)</span>
    <span class="n">imdb</span><span class="o">.</span><span class="n">update</span><span class="p">(</span><span class="n">movie</span><span class="p">,</span> <span class="n">info</span><span class="o">=</span><span class="p">[</span><span class="s1">'vote details'</span><span class="p">])</span>
    <span class="k">if</span> <span class="s1">'rating'</span> <span class="ow">in</span> <span class="n">movie</span><span class="o">.</span><span class="n">data</span><span class="p">:</span>
      <span class="n">display</span><span class="p">(</span><span class="n">Image</span><span class="p">(</span><span class="n">url</span><span class="o">=</span><span class="n">movie</span><span class="o">.</span><span class="n">data</span><span class="p">[</span><span class="s1">'cover url'</span><span class="p">]))</span>
      <span class="nb">print</span><span class="p">(</span><span class="n">movie</span><span class="p">,</span> <span class="n">movie</span><span class="o">.</span><span class="n">data</span><span class="p">[</span><span class="s1">'rating'</span><span class="p">])</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output" data-mime-type="text/html" tabindex="0">
<img alt="No description has been provided for this image" src="https://m.media-amazon.com/images/M/MV5BYmVkNGJkMzQtYWQwOS00OTZmLThjODQtZjNjNzllYzRiNTE0XkEyXkFqcGc@._V1_SY150_CR0,0,101,150_.jpg">
</img></div>
</div>
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain" tabindex="0">
<pre>Trainspotting 8.1
</pre>
</div>
</div>
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output" data-mime-type="text/html" tabindex="0">
<img alt="No description has been provided for this image" src="https://m.media-amazon.com/images/M/MV5BMjI0MTE1ODkzMl5BMl5BanBnXkFtZTgwMTQ1MTg5MDI@._V1_SY150_CR0,0,101,150_.jpg"/>
</div>
</div>
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain" tabindex="0">
<pre>T2 Trainspotting 7.1
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h4 id="Example-3---Generate-a-Histogram">Example 3 - Generate a Histogram<a class="anchor-link" href="#Example-3---Generate-a-Histogram">¶</a></h4>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [7]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sns</span>

<span class="n">countries</span> <span class="o">=</span> <span class="p">[</span><span class="s1">'UK'</span><span class="p">,</span> <span class="s1">'UK'</span><span class="p">,</span> <span class="s1">'India'</span><span class="p">,</span> <span class="s1">'UK'</span><span class="p">,</span> <span class="s1">'India'</span><span class="p">,</span> <span class="s1">'UK'</span><span class="p">,</span> <span class="s1">'Sweden'</span><span class="p">,</span>
             <span class="s1">'India'</span><span class="p">,</span> <span class="s1">'India'</span><span class="p">,</span> <span class="s1">'India'</span><span class="p">,</span> <span class="s1">'India'</span><span class="p">,</span> <span class="s1">'UK'</span><span class="p">,</span> <span class="s1">'India'</span><span class="p">,</span> <span class="s1">'Nigeria'</span><span class="p">,</span>
             <span class="s1">'US'</span><span class="p">,</span> <span class="s1">'Afghanistan'</span><span class="p">,</span> <span class="s1">'Afghanistan'</span><span class="p">,</span> <span class="s1">'US'</span><span class="p">,</span> <span class="s1">'UK'</span><span class="p">,</span> <span class="s1">'US'</span><span class="p">,</span>
             <span class="s1">'Afghanistan'</span><span class="p">,</span> <span class="s1">'UK'</span><span class="p">]</span>
<span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">countries</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[7]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>&lt;Axes: xlabel='count'&gt;</pre>
</div>
</div>
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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
"/>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h4 id="Example-4---Generative-AI-built-into-Colab">Example 4 - Generative AI built into Colab<a class="anchor-link" href="#Example-4---Generative-AI-built-into-Colab">¶</a></h4><p>Try this in Colab:</p>
<img alt="No description has been provided for this image" src="https://mco.dev/img/generate.png" width="800"/>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [10]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="c1"># prompt: generate a colorful time series graph, make the values sparse, i.e. fewer than 20</span>

<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">random</span>

<span class="c1"># Generate sparse time series data</span>
<span class="n">num_points</span> <span class="o">=</span> <span class="n">random</span><span class="o">.</span><span class="n">randint</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="mi">19</span><span class="p">)</span>  <span class="c1"># Ensure fewer than 20 data points</span>
<span class="n">time_values</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">linspace</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="mi">10</span><span class="p">,</span> <span class="n">num_points</span><span class="p">)</span>
<span class="n">data_values</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">random</span><span class="o">.</span><span class="n">randint</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">50</span><span class="p">,</span> <span class="n">num_points</span><span class="p">)</span>

<span class="c1"># Create a colorful time series plot</span>
<span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="mi">6</span><span class="p">))</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">time_values</span><span class="p">,</span> <span class="n">data_values</span><span class="p">,</span> <span class="n">marker</span><span class="o">=</span><span class="s1">'o'</span><span class="p">,</span> <span class="n">linestyle</span><span class="o">=</span><span class="s1">'-'</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'blue'</span><span class="p">,</span> <span class="n">linewidth</span><span class="o">=</span><span class="mi">2</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">fill_between</span><span class="p">(</span><span class="n">time_values</span><span class="p">,</span> <span class="n">data_values</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'skyblue'</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.4</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">'Time'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">'Values'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s1">'Colorful Time Series Graph (Sparse Data)'</span><span class="p">)</span>

<span class="c1"># Add some aesthetics</span>
<span class="n">plt</span><span class="o">.</span><span class="n">grid</span><span class="p">(</span><span class="kc">True</span><span class="p">,</span> <span class="n">linestyle</span><span class="o">=</span><span class="s1">'--'</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.7</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xticks</span><span class="p">(</span><span class="n">fontsize</span><span class="o">=</span><span class="mi">12</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">yticks</span><span class="p">(</span><span class="n">fontsize</span><span class="o">=</span><span class="mi">12</span><span class="p">)</span>

<span class="c1"># Show the plot</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAA00AAAInCAYAAABEG7KkAAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjcuMSwgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy/bCgiHAAAACXBIWXMAAA9hAAAPYQGoP6dpAADluklEQVR4nOydd3wU5fb/P89ueieQQCAJkEZCQkIJoCBNijRpAooKgtdyvXptV+/Pq96iXuVav3i9NizYCyAoYkUURapAOoQuEGooSSCQsjPP74/J7s4mm2Qn2d0pe96vFy8mTyYz55k5c2bO85znHMY55yAIgiAIgiAIgiCcYlJbAIIgCIIgCIIgCC1DThNBEARBEARBEEQLkNNEEARBEARBEATRAuQ0EQRBEARBEARBtAA5TQRBEARBEARBEC1AThNBEARBEARBEEQLkNNEEARBEARBEATRAuQ0EQRBEARBEARBtAA5TQRBEARBEARBEC1AThNBELpg5MiRGDlypNuPe/LkScycORMdO3YEYwyLFi1STa7ff/8djDG88847bjme3vD1/jcHYwx33XVXu46xdetWBAQE4NChQ26SivAE9fX1SEhIwCuvvKK2KARBNIKcJoIgPML+/ftx++23IykpCUFBQYiIiMDQoUPx4osv4tKlS2qLZ+O+++7Dd999h7/97W94//33MX78eLce/1//+hcYY63+84RD6A5EUcR7772HwYMHIzo6GuHh4UhLS8O8efOwefNmtcVzG6dOncJDDz2EPn36ICwsDEFBQUhJScGCBQvw66+/qi1eu3nkkUcwZ84cdO/e3dbmK/e2MY2fyZCQECQmJuLqq6/GkiVLUFtb2+Zjf/311/jXv/7V5r/39/fH/fffjyeffBI1NTVtPg5BEO7HT20BCIIwHl999RVmzZqFwMBAzJs3D1lZWairq8Ovv/6KBx98ECUlJVi8eLHaYgIAfvzxR0ydOhUPPPCAR44/Y8YMpKSk2H6+cOEC7rjjDkyfPh0zZsywtXfu3Bndu3fHpUuX4O/v7xFZ2sLdd9+Nl19+GVOnTsUNN9wAPz8/7N69G9988w2SkpJw2WWXue1cavV/69atmDRpEs6fP4/rrrsOf/zjHxEYGIiDBw/i888/xzvvvIOff/4Zw4cP96pc7iI/Px8//PADNm7c6NDuzXurRV599VWEhYWhtrYWR48exXfffYebb74ZixYtwurVq5GQkKD4mF9//TVefvnldjlOCxYswEMPPYSPPvoIN998c5uPQxCEm+EEQRBu5MCBAzwsLIynp6fzY8eONfn93r17+aJFixQfd8SIEXzEiBFukJDz+vp6XltbyznnnDHG77zzzjYfS6lc5eXlHAD/5z//2eZzeosTJ05wxhi/9dZbm/xOFEV+8uRJt5xHfj+8zdmzZ3lcXBzv0qUL37VrV5Pfi6LIP/roI75169YWj3PhwgVPicgBtEtH7777bp6YmMhFUbS1eeveKqG6utor5/nnP//JAfDy8vImv/vggw+4yWTigwcPbtOx77zzTu6OT6vJkyfzYcOGtfs4BEG4DwrPIwjCrTzzzDO4cOEC3nrrLcTFxTX5fUpKCu655x7bzxaLBU888QSSk5MRGBiIHj164OGHH3YpRObUqVP4wx/+gM6dOyMoKAg5OTl49913HfaxrpN57rnnsGjRItt5XnnlFTDGwDnHyy+/bAvVAezhO4155513wBjD77//rvCquIazNT3z589HWFgYDh8+jMmTJyMsLAzdunXDyy+/DAAoKirClVdeidDQUHTv3h0fffRRk+NWVFTg3nvvRUJCAgIDA5GSkoKnn34aoii2KM/BgwfBOcfQoUOb/I4xhtjYWMXnae5+7Ny5s9k1TaWlpZg5cyaio6MRFBSE3NxcrFq1ymGf+vp6PPbYY0hNTUVQUBA6duyIK664AmvWrGmxj6+99hqOHz+ORYsWIT093Wk/58yZg4EDB9rarPqxc+dOXH/99ejQoQOuuOIKAEBhYSHmz59vC0vt0qULbr75Zpw5c8bhuNZjlJaWYvbs2YiIiEDHjh1xzz33NBuW9fnnnyMrKwuBgYHIzMzEt99+22Lf5H935ZVXOui0kntr1ftffvkFt99+Ozp27IiIiAjMmzcP586dc/jbL774ApMmTULXrl0RGBiI5ORkPPHEExAEwWG/kSNHIisrC9u3b8fw4cMREhKChx9+GACwbds2XHXVVejUqROCg4PRs2fPJjMuoihi0aJFyMzMRFBQEDp37ozbb7+9iTxKueGGG3DLLbdgy5YtDrqzfv16zJo1C4mJiQgMDERCQgLuu+8+h1Dj+fPn255Lefifleeeew5DhgxBx44dERwcjAEDBmD58uVO5Rg7dix+/fVXnD17tl39IQjC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9u3b8cEHH+D48eOYP3++yUdCREThxKSJiIiixrhx4/DII49gxIgR+PnPf474+HgMGjQI//RP/4QRI0bg0UcfxenTp7Fz504AwNNPP43y8nIsXrwYpaWlKC8vx9KlS7F27VpUVlaafDRERBQuXNNERERRY+zYsZ5th8OB9PR0jBkzxrMvKysLAHDixAkAwBdffIG1a9d2uz6qqqoKxcXF/dxiIiKyAiZNREQUNWJiYvx+FkL47XNX5dM0DQDQ2NiIG264Ab/97W+7/K3s7Ox+bCkREVkJkyYiIqIeTJgwAW+//TaGDRsGp5NDJhFRtOKaJiIioh488MADOHPmDG6//XZs27YNVVVV+PDDD3HPPfdAVVWzm0dERGHCpImIiKgHOTk52Lx5M1RVxbXXXosxY8Zg0aJFSE1NhaJwCCUiihZC8nHpREREREREPeJlMiIiIiIiogCYNBEREREREQXApImIiIiIiCgAJk1EREREREQBMGkiIiIiIiIKgEkTERERERFRAEyaiIiIiIiIAmDSREREREREFACTJiIiIiIiogCYNBEREREREQXApImIiIiIiCiA/x82SyhwhTWSiAAAAABJRU5ErkJggg==
"/>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Your-first-Python-program">Your first Python program<a class="anchor-link" href="#Your-first-Python-program">¶</a></h3>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [11]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s1">'Hello world!'</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain" tabindex="0">
<pre>Hello world!
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>Just for context, here's how we wrote that program in 1982:</p>
<pre><code>HELLO    CSECT               The name of this program is 'HELLO'
 *                            Register 15 points here on entry from OPSYS or caller.
          STM   14,12,12(13)  Save registers 14,15, and 0 thru 12 in caller's Save area
          LR    12,15         Set up base register with program's entry point address
          USING HELLO,12      Tell assembler which register we are using for pgm. base
          LA    15,SAVE       Now Point at our own save area
          ST    15,8(13)      Set forward chain
          ST    13,4(15)      Set back chain               
          LR    13,15         Set R13 to address of new save area
 *                            -end of housekeeping (similar for most programs) -
          WTO   'Hello World' Write To Operator  (Operating System macro)
 *
          L     13,4(13)      restore address to caller-provided save area
          XC    8(4,13),8(13) Clear forward chain
          LM    14,12,12(13)  Restore registers as on entry
          DROP  12            The opposite of 'USING'
          SR    15,15         Set register 15 to 0 so that the return code (R15) is Zero
          BR    14            Return to caller
 *           
 SAVE     DS    18F           Define 18 fullwords to save calling program registers
          END  HELLO          This is the end of the program

</code></pre>
<p>Now you see why I love Python. :)</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>The <code>print</code> function provides a mechanism to generate output from a Python program. Another useful function to know about is the <code>input</code> function. It's sort of the opposite of <code>print</code>, because it gathers input into your program. Here's an example:</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [14]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s1">'Enter your name: '</span><span class="p">)</span>
<span class="n">name</span> <span class="o">=</span> <span class="nb">input</span><span class="p">()</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">'Hello'</span><span class="p">,</span> <span class="n">name</span> <span class="o">+</span> <span class="s1">'!'</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain" tabindex="0">
<pre>Enter your name: 
Marc
Hello Marc!
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>Printing a prompt before gathering input is such a common pattern that you can combine them into one function call, like this:</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [13]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">name</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="s1">'Enter your name: '</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">'Hello'</span><span class="p">,</span> <span class="n">name</span> <span class="o">+</span> <span class="s1">'!'</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain" tabindex="0">
<pre>Enter your name: Marc
Hello Marc!
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>🎉 Congratulations - you are now a Python programmer! 🎉</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Errors---when-bad-things-happen-to-good-programs">Errors - when bad things happen to good programs<a class="anchor-link" href="#Errors---when-bad-things-happen-to-good-programs">¶</a></h3>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [15]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="s2">"42"</span> <span class="o">+</span> <span class="s2">"1"</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[15]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>'421'</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h4 id="Three-kinds-of-errors">Three kinds of errors<a class="anchor-link" href="#Three-kinds-of-errors">¶</a></h4><ul>
<li><strong>syntax errors</strong>: invalid Python</li>
</ul>
<pre><code>    print'Hello from Python')
</code></pre>
<ul>
<li><strong>runtime errors</strong>: legal code tries to do something illegal</li>
</ul>
<pre><code>    primt('Hello from Python')
    print(10 / 0)
</code></pre>
<ul>
<li><strong>logic errors</strong>: code is legal and runs fine but it does the wrong thing</li>
</ul>
<pre><code>    age = birth_year - current_year
</code></pre>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Comments">Comments<a class="anchor-link" href="#Comments">¶</a></h3>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<ul>
<li><code>#</code> marks the rest of the line as a "comment"</li>
<li>Ignored by Python</li>
<li>useful for documenting your code</li>
<li>blank lines are also fine and sometimes improve readability</li>
</ul>
<p>Example:</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [22]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="c1"># Python ignores this line.</span>
<span class="c1"># print('this line does not print anything when commented out')</span>
<span class="c1"># The following blank lines are ignored as well...</span>

<span class="c1">#print('hi') # this is a comment</span>

<span class="c1"># I can have as many comments and blank lines as I like in a program.</span>
<span class="c1"># They are for the benefit of me and "future me".</span>
</pre></div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>Try removing the # preceding the print function call in the previous cell. We call this "uncommenting" a line of code.</p>
<p>Now put the # back in place. We call this "commenting out" a line of code. Often we'll do this to temporarily disable some code from running, where we want to keep the code in place for possible future use.</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="What-is-a-function?">What is a function?<a class="anchor-link" href="#What-is-a-function?">¶</a></h3><p>A reusable piece of code that completes a specific task.
We just met two functions - <code>print</code> and <code>input</code> are functions you used to do input/output (I/O) operations.
We say "call" or "invoke" a function to request that it do its job.
We do this by writing the function name followed by parentheses (aka brackets).
We may optionally include some values inside the brackets. We call those values function arguments, or just arguments.
We'll often refer to this process as "passing arguments" to a function.
I like to think of the function as a work request and the arguments as the job specification.
For example, you can pass arguments to the print function to produce just about any desired output.</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [30]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s1">'test'</span><span class="p">)</span>
<span class="nb">print</span><span class="p">()</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">'this'</span><span class="p">,</span> <span class="s1">'is'</span><span class="p">,</span> <span class="s1">'a'</span><span class="p">,</span> <span class="s1">'test'</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain" tabindex="0">
<pre>test

this is a test
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>Built-in functions, like <code>print</code> and <code>input</code> are always available to use.</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h4 id="More-about-print">More about print<a class="anchor-link" href="#More-about-print">¶</a></h4><p>A print function call with no arguments simply prints a blank line:</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [31]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="nb">print</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain" tabindex="0">
<pre>
</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="c1"># Now try calling the print function with something else, like your name...</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">'your name here'</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>Functions are the basic building blocks of a Python program. Later we'll see how to define your own functions. We've seen a simple print function call with zero and one argument:</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s1">'My name is Marc'</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>We can also print a sequence of arguments, where spaces are added between each element in sequence, like this:</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s1">'My'</span><span class="p">,</span> <span class="s1">'name'</span><span class="p">,</span> <span class="s1">'is'</span><span class="p">,</span> <span class="s1">'Marc'</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">'next line'</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>By default, we get a newline character at the end of a print request but we can override that behavior using the <code>end</code> argument:</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [32]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s1">'My name is Marc'</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">'next line'</span><span class="p">)</span>

<span class="nb">print</span><span class="p">(</span><span class="s1">'My name is Marc'</span><span class="p">,</span> <span class="n">end</span><span class="o">=</span><span class="s1">'</span><span class="se">\n</span><span class="s1">'</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">'next line'</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain" tabindex="0">
<pre>My name is Marc
next line
My name is Marc
next line
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>We can also change the separator string, using the <code>sep</code> argument, like this:</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s1">'My'</span><span class="p">,</span> <span class="s1">'name'</span><span class="p">,</span> <span class="s1">'is'</span><span class="p">,</span> <span class="s1">'Marc'</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">'</span><span class="se">\n</span><span class="s1">'</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>We could even use a null (empty) separator:</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s1">'My'</span><span class="p">,</span> <span class="s1">'name'</span><span class="p">,</span> <span class="s1">'is'</span><span class="p">,</span> <span class="s1">'Marc'</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">''</span><span class="p">,</span> <span class="n">end</span><span class="o">=</span><span class="s1">''</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">'hi'</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Useful-Python-Resources">Useful Python Resources<a class="anchor-link" href="#Useful-Python-Resources">¶</a></h3><ul>
<li><a href="https://python.org">The official Python site</a></li>
<li><a href="https://python.org/downloads/">Install Python</a></li>
<li><a href="https://jakevdp.github.io/WhirlwindTourOfPython/">A Whirlwind Tour of Python</a></li>
<li><a href="https://mco.dev/my-favorite-books-for-beginning-python-students/">My Favorite Books for Beginning Python Students</a></li>
<li><a href="https://repl.it">repl.it</a></li>
<li><a href="https://code.visualstudio.com/">vscode</a></li>
<li><a href="https://codingbat.com/python">codingbat.com</a></li>
</ul>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h4 id="Recommended-Book-for-Further-Study">Recommended Book for Further Study<a class="anchor-link" href="#Recommended-Book-for-Further-Study">¶</a></h4><p><a href="http://automatetheboringstuff.com/">Automate the Boring Stuff with Python</a></p>
<p>Great fit for our course:</p>
<ul>
<li>well written</li>
<li>free to read online</li>
<li>perfect for beginners</li>
<li>focusses on practical applications</li>
<li>if you buy it, make sure you get the 3rd edition</li>
</ul>
<br/>
<img alt="No description has been provided for this image" height="350" src="https://m.media-amazon.com/images/I/61yYe66I4+L._SL1321_.jpg"/>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h4 id="Documentation">Documentation<a class="anchor-link" href="#Documentation">¶</a></h4>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<ul>
<li><a href="https://python.org/doc/">Official Python Documentation</a></li>
<li>the <code>help</code> function (see example below)</li>
<li>Google</li>
<li>Stack Overflow</li>
<li>AI - I like Github Co-Pilot and Google Gemini</li>
</ul>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [33]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">help</span><span class="p">(</span><span class="nb">print</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain" tabindex="0">
<pre>Help on built-in function print in module builtins:

print(...)
    print(value, ..., sep=' ', end='\n', file=sys.stdout, flush=False)
    
    Prints the values to a stream, or to sys.stdout by default.
    Optional keyword arguments:
    file:  a file-like object (stream); defaults to the current sys.stdout.
    sep:   string inserted between values, default a space.
    end:   string appended after the last value, default a newline.
    flush: whether to forcibly flush the stream.

</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p><a href="https://pylearn.io/lessons/2-Variables">Next Lesson</a></p>
</div>
</div>
</div>
</div>
</main>
</body>
</html>
