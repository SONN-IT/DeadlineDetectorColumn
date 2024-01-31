# Columns

## Thunderbird 115

```
<thead xmlns="http://www.w3.org/1999/xhtml" is="tree-view-table-header" class="tree-table-header threaded">
  <tr>
    <th xmlns="http://www.w3.org/1999/xhtml" is="tree-view-table-header-cell" draggable="true" id="subjectDateCol" data-resizable="false" style="">
      <div class="tree-table-cell tree-table-cell-container">
        <button id="subjectDateColButton" data-l10n-id="threadpane-column-header-date" tabindex="-1" class="sorting ascending" title="Sort by date">Date</button>
      </div>
      <hr is="pane-splitter" resize-direction="horizontal" resize-id="subjectDateCol" id="subjectDateColSplitter" disabled="true" />
    </th>
  </tr>
</thead>
```

## Thunderbird 102

```
<treecols xmlns="http://www.mozilla.org/keymaster/gatekeeper/there.is.only.xul" is="thread-pane-treecols" id="threadCols" pickertooltiptext="Select columns to display" slot="treecols">
  <treecol xmlns="http://www.mozilla.org/keymaster/gatekeeper/there.is.only.xul" id="dateCol"
    persist="hidden ordinal sortDirection width" flex="2" closemenu="none" label="Date" tooltiptext="Sort by date"
    style="-moz-box-ordinal-group: 23;" ordinal="23" sortDirection="ascending">
    <label class="treecol-text" flex="1" crop="right" value="Date"></label>
    <image class="treecol-sortdirection" />
  </treecol>
</treecols>
```