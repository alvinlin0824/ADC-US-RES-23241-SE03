---
title: "ADC-US-RES-23241 SE03 Yuwell Accuracy Performance"
description: "Continuous Glucose Monitoring System Comparison Study"
author: "Alvin, Lin"
date: "2024-10-03"
date-format: full
format:
   html:
     theme: flatly
     embed-resources: true
toc: true
toc-depth: 3
toc-location: left
execute:
  echo: false
  warning: false
  keep-md: true
params:
  plot: FALSE
  analysis: TRUE
  title1: "Profile Plot"
  title2: "Accuracy Performance"
---




<!-- EDC \\wf00168p.oneabbott.com\data1\CDM\ADC-US-RES-23241\SE03\OpenClinica\Current -->

<!-- AUU \\wf00168p.oneabbott.com\data1\CDM\ADC-US-RES-23241\SE03\UploadData -->

<!-- CRF \\oneabbott.com\dept\ADC\Technical_OPS\Clinical_Affairs\Clinical Study Files\Apollo\ADC-US-RES-23241-CGM Comparison\Case Report Forms\Version_A\Approved\PDF -->

<!-- DMP \\oneabbott.com\dept\ADC\Technical_OPS\Clinical_Affairs\Clinical Study Files\Apollo\ADC-US-RES-23241-CGM Comparison\CDM\Study_Binder\Data_Management_Plan\SE03\Version_1.0\Approved -->

<!-- study request \\oneabbott.com\dept\ADC\Technical_OPS\Clinical_Affairs\Clinical Study Files\Apollo\ADC-US-RES-23241-CGM Comparison\Study Events_ Requests\SE_03 -->

<!-- Conversion 18.016*mmol/L = mg/dL -->

<!-- Yuwell dynamic range 1.7mmol/L ~ 27.8mmol/L	 -->

`<a href="//oneabbott.com/dept/ADC/Technical_OPS/Clinical_Affairs/Clinical Study Files/Apollo/ADC-US-RES-23241-CGM Comparison/Study Events_ Requests/SE_03/ADC_23241_SE03_Yuwell_EventRequest_Final_01Mar2024.pdf">Study Request</a>`{=html}


::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::



# **Investigate Errorcode**


::: {.cell}
::: {.cell-output-display}


```{=html}
<div id="lbwbptyfnz" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#lbwbptyfnz table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#lbwbptyfnz thead, #lbwbptyfnz tbody, #lbwbptyfnz tfoot, #lbwbptyfnz tr, #lbwbptyfnz td, #lbwbptyfnz th {
  border-style: none;
}

#lbwbptyfnz p {
  margin: 0;
  padding: 0;
}

#lbwbptyfnz .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#lbwbptyfnz .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#lbwbptyfnz .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#lbwbptyfnz .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#lbwbptyfnz .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#lbwbptyfnz .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#lbwbptyfnz .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#lbwbptyfnz .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#lbwbptyfnz .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#lbwbptyfnz .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#lbwbptyfnz .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#lbwbptyfnz .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#lbwbptyfnz .gt_spanner_row {
  border-bottom-style: hidden;
}

#lbwbptyfnz .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#lbwbptyfnz .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#lbwbptyfnz .gt_from_md > :first-child {
  margin-top: 0;
}

#lbwbptyfnz .gt_from_md > :last-child {
  margin-bottom: 0;
}

#lbwbptyfnz .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#lbwbptyfnz .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#lbwbptyfnz .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#lbwbptyfnz .gt_row_group_first td {
  border-top-width: 2px;
}

#lbwbptyfnz .gt_row_group_first th {
  border-top-width: 2px;
}

#lbwbptyfnz .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#lbwbptyfnz .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#lbwbptyfnz .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#lbwbptyfnz .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#lbwbptyfnz .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#lbwbptyfnz .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#lbwbptyfnz .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#lbwbptyfnz .gt_striped {
  background-color: #EDF7FC;
}

#lbwbptyfnz .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#lbwbptyfnz .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#lbwbptyfnz .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#lbwbptyfnz .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#lbwbptyfnz .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#lbwbptyfnz .gt_left {
  text-align: left;
}

#lbwbptyfnz .gt_center {
  text-align: center;
}

#lbwbptyfnz .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#lbwbptyfnz .gt_font_normal {
  font-weight: normal;
}

#lbwbptyfnz .gt_font_bold {
  font-weight: bold;
}

#lbwbptyfnz .gt_font_italic {
  font-style: italic;
}

#lbwbptyfnz .gt_super {
  font-size: 65%;
}

#lbwbptyfnz .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#lbwbptyfnz .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#lbwbptyfnz .gt_indent_1 {
  text-indent: 5px;
}

#lbwbptyfnz .gt_indent_2 {
  text-indent: 10px;
}

#lbwbptyfnz .gt_indent_3 {
  text-indent: 15px;
}

#lbwbptyfnz .gt_indent_4 {
  text-indent: 20px;
}

#lbwbptyfnz .gt_indent_5 {
  text-indent: 25px;
}

#lbwbptyfnz .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#lbwbptyfnz div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="7" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipHbHVjb3NlIEdyb3VwIEJ5IEVycm9yY29kZSoq"><div class='gt_from_md'><p><strong>Glucose Group By Errorcode</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="ErrorCode">ErrorCode</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Min">Min</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Max">Max</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="N">N</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="ErrorCode" class="gt_row gt_center">0</td>
<td headers="Mean" class="gt_row gt_center">10.15</td>
<td headers="Median" class="gt_row gt_center">9.30</td>
<td headers="SD" class="gt_row gt_center">4.93</td>
<td headers="Min" class="gt_row gt_center">0.00</td>
<td headers="Max" class="gt_row gt_center">100.00</td>
<td headers="N" class="gt_row gt_center">204281</td></tr>
    <tr><td headers="ErrorCode" class="gt_row gt_center gt_striped">103</td>
<td headers="Mean" class="gt_row gt_center gt_striped">0.53</td>
<td headers="Median" class="gt_row gt_center gt_striped">0.10</td>
<td headers="SD" class="gt_row gt_center gt_striped">0.73</td>
<td headers="Min" class="gt_row gt_center gt_striped">0.00</td>
<td headers="Max" class="gt_row gt_center gt_striped">3.80</td>
<td headers="N" class="gt_row gt_center gt_striped">170</td></tr>
    <tr><td headers="ErrorCode" class="gt_row gt_center">11</td>
<td headers="Mean" class="gt_row gt_center">61.62</td>
<td headers="Median" class="gt_row gt_center">83.10</td>
<td headers="SD" class="gt_row gt_center">43.26</td>
<td headers="Min" class="gt_row gt_center">0.00</td>
<td headers="Max" class="gt_row gt_center">100.00</td>
<td headers="N" class="gt_row gt_center">14</td></tr>
    <tr><td headers="ErrorCode" class="gt_row gt_center gt_striped">13</td>
<td headers="Mean" class="gt_row gt_center gt_striped">0.17</td>
<td headers="Median" class="gt_row gt_center gt_striped">0.00</td>
<td headers="SD" class="gt_row gt_center gt_striped">0.30</td>
<td headers="Min" class="gt_row gt_center gt_striped">0.00</td>
<td headers="Max" class="gt_row gt_center gt_striped">3.30</td>
<td headers="N" class="gt_row gt_center gt_striped">3038</td></tr>
    <tr><td headers="ErrorCode" class="gt_row gt_center">15</td>
<td headers="Mean" class="gt_row gt_center">0.01</td>
<td headers="Median" class="gt_row gt_center">0.00</td>
<td headers="SD" class="gt_row gt_center">0.04</td>
<td headers="Min" class="gt_row gt_center">0.00</td>
<td headers="Max" class="gt_row gt_center">0.50</td>
<td headers="N" class="gt_row gt_center">3107</td></tr>
    <tr><td headers="ErrorCode" class="gt_row gt_center gt_striped">16</td>
<td headers="Mean" class="gt_row gt_center gt_striped">100.00</td>
<td headers="Median" class="gt_row gt_center gt_striped">100.00</td>
<td headers="SD" class="gt_row gt_center gt_striped">0.00</td>
<td headers="Min" class="gt_row gt_center gt_striped">100.00</td>
<td headers="Max" class="gt_row gt_center gt_striped">100.00</td>
<td headers="N" class="gt_row gt_center gt_striped">68</td></tr>
    <tr><td headers="ErrorCode" class="gt_row gt_center">5</td>
<td headers="Mean" class="gt_row gt_center">3.33</td>
<td headers="Median" class="gt_row gt_center">0.00</td>
<td headers="SD" class="gt_row gt_center">5.50</td>
<td headers="Min" class="gt_row gt_center">0.00</td>
<td headers="Max" class="gt_row gt_center">15.40</td>
<td headers="N" class="gt_row gt_center">8</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell layout-align="center"}
::: {.cell-output-display}
![](ADC-US-RES-23241-SE03_files/figure-html/Investigate Errorcode Distrubution Plot-1.png){fig-align='center' width=672}
:::
:::



# **Demographic**


::: {.cell}

:::

::: {.cell}
::: {.cell-output-display}


```{=html}
<div id="zalolsgwpb" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#zalolsgwpb table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#zalolsgwpb thead, #zalolsgwpb tbody, #zalolsgwpb tfoot, #zalolsgwpb tr, #zalolsgwpb td, #zalolsgwpb th {
  border-style: none;
}

#zalolsgwpb p {
  margin: 0;
  padding: 0;
}

#zalolsgwpb .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#zalolsgwpb .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#zalolsgwpb .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#zalolsgwpb .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#zalolsgwpb .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#zalolsgwpb .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#zalolsgwpb .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#zalolsgwpb .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#zalolsgwpb .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#zalolsgwpb .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#zalolsgwpb .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#zalolsgwpb .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#zalolsgwpb .gt_spanner_row {
  border-bottom-style: hidden;
}

#zalolsgwpb .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#zalolsgwpb .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#zalolsgwpb .gt_from_md > :first-child {
  margin-top: 0;
}

#zalolsgwpb .gt_from_md > :last-child {
  margin-bottom: 0;
}

#zalolsgwpb .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#zalolsgwpb .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#zalolsgwpb .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#zalolsgwpb .gt_row_group_first td {
  border-top-width: 2px;
}

#zalolsgwpb .gt_row_group_first th {
  border-top-width: 2px;
}

#zalolsgwpb .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#zalolsgwpb .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#zalolsgwpb .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#zalolsgwpb .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#zalolsgwpb .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#zalolsgwpb .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#zalolsgwpb .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#zalolsgwpb .gt_striped {
  background-color: #EDF7FC;
}

#zalolsgwpb .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#zalolsgwpb .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#zalolsgwpb .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#zalolsgwpb .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#zalolsgwpb .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#zalolsgwpb .gt_left {
  text-align: left;
}

#zalolsgwpb .gt_center {
  text-align: center;
}

#zalolsgwpb .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#zalolsgwpb .gt_font_normal {
  font-weight: normal;
}

#zalolsgwpb .gt_font_bold {
  font-weight: bold;
}

#zalolsgwpb .gt_font_italic {
  font-style: italic;
}

#zalolsgwpb .gt_super {
  font-size: 65%;
}

#zalolsgwpb .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#zalolsgwpb .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#zalolsgwpb .gt_indent_1 {
  text-indent: 5px;
}

#zalolsgwpb .gt_indent_2 {
  text-indent: 10px;
}

#zalolsgwpb .gt_indent_3 {
  text-indent: 15px;
}

#zalolsgwpb .gt_indent_4 {
  text-indent: 20px;
}

#zalolsgwpb .gt_indent_5 {
  text-indent: 25px;
}

#zalolsgwpb .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#zalolsgwpb div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="3" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipTdWJqZWN0IERlbW9ncmFwaGljcyBhbmQgRGlhYmV0ZXMgSGlzdG9yeSoq"><div class='gt_from_md'><p><strong>Subject Demographics and Diabetes History</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Charateristic">Charateristic</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="N">N</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="%">%</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr class="gt_group_heading_row">
      <th colspan="3" class="gt_group_heading" scope="colgroup" id="Sex">Sex</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="Sex  Charateristic" class="gt_row gt_center">Female</td>
<td headers="Sex  N" class="gt_row gt_center">21</td>
<td headers="Sex  %" class="gt_row gt_center">58.3</td></tr>
    <tr><td headers="Sex  Charateristic" class="gt_row gt_center gt_striped">Male</td>
<td headers="Sex  N" class="gt_row gt_center gt_striped">15</td>
<td headers="Sex  %" class="gt_row gt_center gt_striped">41.7</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="3" class="gt_group_heading" scope="colgroup" id="Race">Race</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="Race  Charateristic" class="gt_row gt_center">White - Not Hispanic or Latino</td>
<td headers="Race  N" class="gt_row gt_center">23</td>
<td headers="Race  %" class="gt_row gt_center">63.9</td></tr>
    <tr><td headers="Race  Charateristic" class="gt_row gt_center gt_striped">White - Hispanic or Latino</td>
<td headers="Race  N" class="gt_row gt_center gt_striped">2</td>
<td headers="Race  %" class="gt_row gt_center gt_striped">5.6</td></tr>
    <tr><td headers="Race  Charateristic" class="gt_row gt_center">American Indian or Alaska Native</td>
<td headers="Race  N" class="gt_row gt_center">0</td>
<td headers="Race  %" class="gt_row gt_center">0.0</td></tr>
    <tr><td headers="Race  Charateristic" class="gt_row gt_center gt_striped">Asian</td>
<td headers="Race  N" class="gt_row gt_center gt_striped">5</td>
<td headers="Race  %" class="gt_row gt_center gt_striped">13.9</td></tr>
    <tr><td headers="Race  Charateristic" class="gt_row gt_center">Black or African American</td>
<td headers="Race  N" class="gt_row gt_center">3</td>
<td headers="Race  %" class="gt_row gt_center">8.3</td></tr>
    <tr><td headers="Race  Charateristic" class="gt_row gt_center gt_striped">Native Hawaiian or Pacific Islander</td>
<td headers="Race  N" class="gt_row gt_center gt_striped">2</td>
<td headers="Race  %" class="gt_row gt_center gt_striped">5.6</td></tr>
    <tr><td headers="Race  Charateristic" class="gt_row gt_center">Other</td>
<td headers="Race  N" class="gt_row gt_center">1</td>
<td headers="Race  %" class="gt_row gt_center">2.8</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="3" class="gt_group_heading" scope="colgroup" id="Education">Education</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="Education  Charateristic" class="gt_row gt_center gt_striped">Grade 0-8</td>
<td headers="Education  N" class="gt_row gt_center gt_striped">0</td>
<td headers="Education  %" class="gt_row gt_center gt_striped">0.0</td></tr>
    <tr><td headers="Education  Charateristic" class="gt_row gt_center">High School (Grades 9-12)</td>
<td headers="Education  N" class="gt_row gt_center">4</td>
<td headers="Education  %" class="gt_row gt_center">11.1</td></tr>
    <tr><td headers="Education  Charateristic" class="gt_row gt_center gt_striped">Some College (1-4 years)</td>
<td headers="Education  N" class="gt_row gt_center gt_striped">21</td>
<td headers="Education  %" class="gt_row gt_center gt_striped">58.3</td></tr>
    <tr><td headers="Education  Charateristic" class="gt_row gt_center">Bachelor's Degree (BA BS etc)</td>
<td headers="Education  N" class="gt_row gt_center">7</td>
<td headers="Education  %" class="gt_row gt_center">19.4</td></tr>
    <tr><td headers="Education  Charateristic" class="gt_row gt_center gt_striped">Master's Degree (MA MS etc)</td>
<td headers="Education  N" class="gt_row gt_center gt_striped">4</td>
<td headers="Education  %" class="gt_row gt_center gt_striped">11.1</td></tr>
    <tr><td headers="Education  Charateristic" class="gt_row gt_center">Doctorate or Professional school degree (PhD EdD MD JD etc)</td>
<td headers="Education  N" class="gt_row gt_center">0</td>
<td headers="Education  %" class="gt_row gt_center">0.0</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="3" class="gt_group_heading" scope="colgroup" id="Type of Diabetes">Type of Diabetes</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="Type of Diabetes  Charateristic" class="gt_row gt_center gt_striped">Type 1</td>
<td headers="Type of Diabetes  N" class="gt_row gt_center gt_striped">8</td>
<td headers="Type of Diabetes  %" class="gt_row gt_center gt_striped">22.2</td></tr>
    <tr><td headers="Type of Diabetes  Charateristic" class="gt_row gt_center">Type 2</td>
<td headers="Type of Diabetes  N" class="gt_row gt_center">28</td>
<td headers="Type of Diabetes  %" class="gt_row gt_center">77.8</td></tr>
    <tr><td headers="Type of Diabetes  Charateristic" class="gt_row gt_center gt_striped">Other: Non-Diabetic</td>
<td headers="Type of Diabetes  N" class="gt_row gt_center gt_striped">0</td>
<td headers="Type of Diabetes  %" class="gt_row gt_center gt_striped">0.0</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell}

:::

::: {.cell}
::: {.cell-output-display}


```{=html}
<div id="otdyjsqohk" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#otdyjsqohk table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#otdyjsqohk thead, #otdyjsqohk tbody, #otdyjsqohk tfoot, #otdyjsqohk tr, #otdyjsqohk td, #otdyjsqohk th {
  border-style: none;
}

#otdyjsqohk p {
  margin: 0;
  padding: 0;
}

#otdyjsqohk .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#otdyjsqohk .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#otdyjsqohk .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#otdyjsqohk .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#otdyjsqohk .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#otdyjsqohk .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#otdyjsqohk .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#otdyjsqohk .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#otdyjsqohk .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#otdyjsqohk .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#otdyjsqohk .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#otdyjsqohk .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#otdyjsqohk .gt_spanner_row {
  border-bottom-style: hidden;
}

#otdyjsqohk .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#otdyjsqohk .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#otdyjsqohk .gt_from_md > :first-child {
  margin-top: 0;
}

#otdyjsqohk .gt_from_md > :last-child {
  margin-bottom: 0;
}

#otdyjsqohk .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#otdyjsqohk .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#otdyjsqohk .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#otdyjsqohk .gt_row_group_first td {
  border-top-width: 2px;
}

#otdyjsqohk .gt_row_group_first th {
  border-top-width: 2px;
}

#otdyjsqohk .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#otdyjsqohk .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#otdyjsqohk .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#otdyjsqohk .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#otdyjsqohk .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#otdyjsqohk .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#otdyjsqohk .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#otdyjsqohk .gt_striped {
  background-color: #EDF7FC;
}

#otdyjsqohk .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#otdyjsqohk .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#otdyjsqohk .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#otdyjsqohk .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#otdyjsqohk .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#otdyjsqohk .gt_left {
  text-align: left;
}

#otdyjsqohk .gt_center {
  text-align: center;
}

#otdyjsqohk .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#otdyjsqohk .gt_font_normal {
  font-weight: normal;
}

#otdyjsqohk .gt_font_bold {
  font-weight: bold;
}

#otdyjsqohk .gt_font_italic {
  font-style: italic;
}

#otdyjsqohk .gt_super {
  font-size: 65%;
}

#otdyjsqohk .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#otdyjsqohk .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#otdyjsqohk .gt_indent_1 {
  text-indent: 5px;
}

#otdyjsqohk .gt_indent_2 {
  text-indent: 10px;
}

#otdyjsqohk .gt_indent_3 {
  text-indent: 15px;
}

#otdyjsqohk .gt_indent_4 {
  text-indent: 20px;
}

#otdyjsqohk .gt_indent_5 {
  text-indent: 25px;
}

#otdyjsqohk .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#otdyjsqohk div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="4" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipCYXNlbGluZSBDaGFyYWN0ZXJpc3RpY3MqKg=="><div class='gt_from_md'><p><strong>Baseline Characteristics</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Characteristics">Characteristics</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean ± SD">Mean ± SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Range">Range</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Characteristics" class="gt_row gt_center">Age (Years)</td>
<td headers="Mean ± SD" class="gt_row gt_center">56.0 ± 12.5</td>
<td headers="Median" class="gt_row gt_center">57.5</td>
<td headers="Range" class="gt_row gt_center">24.0 - 76.0</td></tr>
    <tr><td headers="Characteristics" class="gt_row gt_center gt_striped">Weight (Pounds)</td>
<td headers="Mean ± SD" class="gt_row gt_center gt_striped">221.1 ± 63.1</td>
<td headers="Median" class="gt_row gt_center gt_striped">205.5</td>
<td headers="Range" class="gt_row gt_center gt_striped">119.0 - 358.0</td></tr>
    <tr><td headers="Characteristics" class="gt_row gt_center">Weight (Kilograms)</td>
<td headers="Mean ± SD" class="gt_row gt_center">100.3 ± 28.6</td>
<td headers="Median" class="gt_row gt_center">93.2</td>
<td headers="Range" class="gt_row gt_center">54.0 - 162.4</td></tr>
    <tr><td headers="Characteristics" class="gt_row gt_center gt_striped">Height (Inches)</td>
<td headers="Mean ± SD" class="gt_row gt_center gt_striped">66.9 ± 4.2</td>
<td headers="Median" class="gt_row gt_center gt_striped">68.0</td>
<td headers="Range" class="gt_row gt_center gt_striped">58.0 - 74.0</td></tr>
    <tr><td headers="Characteristics" class="gt_row gt_center">Height (Meters)</td>
<td headers="Mean ± SD" class="gt_row gt_center">1.7 ± 0.1</td>
<td headers="Median" class="gt_row gt_center">1.7</td>
<td headers="Range" class="gt_row gt_center">1.5 - 1.9</td></tr>
    <tr><td headers="Characteristics" class="gt_row gt_center gt_striped">Body Mass Index (BMI)</td>
<td headers="Mean ± SD" class="gt_row gt_center gt_striped">34.4 ± 8.0</td>
<td headers="Median" class="gt_row gt_center gt_striped">32.9</td>
<td headers="Range" class="gt_row gt_center gt_striped">22.7 - 52.4</td></tr>
    <tr><td headers="Characteristics" class="gt_row gt_center">Duration of diabetes (years)</td>
<td headers="Mean ± SD" class="gt_row gt_center">15.7 ± 12.2</td>
<td headers="Median" class="gt_row gt_center">12.5</td>
<td headers="Range" class="gt_row gt_center">0.0 - 45.0</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell}

:::

::: {.cell}

:::



# **Survival Analysis**


::: {.cell}

:::

::: {.cell .column-body-outset}
::: {.cell-output-display}


```{=html}
<div id="bahheopinb" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#bahheopinb table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#bahheopinb thead, #bahheopinb tbody, #bahheopinb tfoot, #bahheopinb tr, #bahheopinb td, #bahheopinb th {
  border-style: none;
}

#bahheopinb p {
  margin: 0;
  padding: 0;
}

#bahheopinb .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#bahheopinb .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#bahheopinb .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#bahheopinb .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#bahheopinb .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#bahheopinb .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#bahheopinb .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#bahheopinb .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#bahheopinb .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#bahheopinb .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#bahheopinb .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#bahheopinb .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#bahheopinb .gt_spanner_row {
  border-bottom-style: hidden;
}

#bahheopinb .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#bahheopinb .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#bahheopinb .gt_from_md > :first-child {
  margin-top: 0;
}

#bahheopinb .gt_from_md > :last-child {
  margin-bottom: 0;
}

#bahheopinb .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#bahheopinb .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#bahheopinb .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#bahheopinb .gt_row_group_first td {
  border-top-width: 2px;
}

#bahheopinb .gt_row_group_first th {
  border-top-width: 2px;
}

#bahheopinb .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#bahheopinb .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#bahheopinb .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#bahheopinb .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#bahheopinb .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#bahheopinb .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#bahheopinb .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#bahheopinb .gt_striped {
  background-color: #EDF7FC;
}

#bahheopinb .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#bahheopinb .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#bahheopinb .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#bahheopinb .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#bahheopinb .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#bahheopinb .gt_left {
  text-align: left;
}

#bahheopinb .gt_center {
  text-align: center;
}

#bahheopinb .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#bahheopinb .gt_font_normal {
  font-weight: normal;
}

#bahheopinb .gt_font_bold {
  font-weight: bold;
}

#bahheopinb .gt_font_italic {
  font-style: italic;
}

#bahheopinb .gt_super {
  font-size: 65%;
}

#bahheopinb .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#bahheopinb .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#bahheopinb .gt_indent_1 {
  text-indent: 5px;
}

#bahheopinb .gt_indent_2 {
  text-indent: 10px;
}

#bahheopinb .gt_indent_3 {
  text-indent: 15px;
}

#bahheopinb .gt_indent_4 {
  text-indent: 20px;
}

#bahheopinb .gt_indent_5 {
  text-indent: 25px;
}

#bahheopinb .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#bahheopinb div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Number of Subjects enrolled">Number of Subjects enrolled</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Number of sensors(EDC)">Number of sensors(EDC)</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Number of sensors(Upload)">Number of sensors(Upload)</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Number of sensors(Paired)">Number of sensors(Paired)</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Number of sensors(Paired) with 14 Days">Number of sensors(Paired) with 14 Days</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Number of Subjects enrolled" class="gt_row gt_center">36</td>
<td headers="Number of sensors(EDC)" class="gt_row gt_center">36</td>
<td headers="Number of sensors(Upload)" class="gt_row gt_center">35</td>
<td headers="Number of sensors(Paired)" class="gt_row gt_center">34</td>
<td headers="Number of sensors(Paired) with 14 Days" class="gt_row gt_center">25</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell .column-body-outset}
::: {.cell-output-display}


```{=html}
<div id="cobbvvqitj" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#cobbvvqitj table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#cobbvvqitj thead, #cobbvvqitj tbody, #cobbvvqitj tfoot, #cobbvvqitj tr, #cobbvvqitj td, #cobbvvqitj th {
  border-style: none;
}

#cobbvvqitj p {
  margin: 0;
  padding: 0;
}

#cobbvvqitj .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#cobbvvqitj .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#cobbvvqitj .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#cobbvvqitj .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#cobbvvqitj .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#cobbvvqitj .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#cobbvvqitj .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#cobbvvqitj .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#cobbvvqitj .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#cobbvvqitj .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#cobbvvqitj .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#cobbvvqitj .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#cobbvvqitj .gt_spanner_row {
  border-bottom-style: hidden;
}

#cobbvvqitj .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#cobbvvqitj .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#cobbvvqitj .gt_from_md > :first-child {
  margin-top: 0;
}

#cobbvvqitj .gt_from_md > :last-child {
  margin-bottom: 0;
}

#cobbvvqitj .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#cobbvvqitj .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#cobbvvqitj .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#cobbvvqitj .gt_row_group_first td {
  border-top-width: 2px;
}

#cobbvvqitj .gt_row_group_first th {
  border-top-width: 2px;
}

#cobbvvqitj .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#cobbvvqitj .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#cobbvvqitj .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#cobbvvqitj .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#cobbvvqitj .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#cobbvvqitj .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#cobbvvqitj .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#cobbvvqitj .gt_striped {
  background-color: #EDF7FC;
}

#cobbvvqitj .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#cobbvvqitj .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#cobbvvqitj .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#cobbvvqitj .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#cobbvvqitj .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#cobbvvqitj .gt_left {
  text-align: left;
}

#cobbvvqitj .gt_center {
  text-align: center;
}

#cobbvvqitj .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#cobbvvqitj .gt_font_normal {
  font-weight: normal;
}

#cobbvvqitj .gt_font_bold {
  font-weight: bold;
}

#cobbvvqitj .gt_font_italic {
  font-style: italic;
}

#cobbvvqitj .gt_super {
  font-size: 65%;
}

#cobbvvqitj .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#cobbvvqitj .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#cobbvvqitj .gt_indent_1 {
  text-indent: 5px;
}

#cobbvvqitj .gt_indent_2 {
  text-indent: 10px;
}

#cobbvvqitj .gt_indent_3 {
  text-indent: 15px;
}

#cobbvvqitj .gt_indent_4 {
  text-indent: 20px;
}

#cobbvvqitj .gt_indent_5 {
  text-indent: 25px;
}

#cobbvvqitj .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#cobbvvqitj div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="9" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipTZW5zb3IgR2x1Y29zZSBEdXJhdGlvbioq"><div class='gt_from_md'><p><strong>Sensor Glucose Duration</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Sensor">Sensor</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Minimum">Minimum</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Maximum">Maximum</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="No. Sensors in Analysis">No. Sensors in Analysis</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="No. Successful Wears (14 days)">No. Successful Wears (14 days)</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="% Successful Wears (14 days)">% Successful Wears (14 days)</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Sensor" class="gt_row gt_center">Yuwell</td>
<td headers="Mean" class="gt_row gt_center">12.2</td>
<td headers="Median" class="gt_row gt_center">14</td>
<td headers="SD" class="gt_row gt_center">3.8</td>
<td headers="Minimum" class="gt_row gt_center">2</td>
<td headers="Maximum" class="gt_row gt_center">14</td>
<td headers="No. Sensors in Analysis" class="gt_row gt_center">35</td>
<td headers="No. Successful Wears (14 days)" class="gt_row gt_center">27</td>
<td headers="% Successful Wears (14 days)" class="gt_row gt_center">77.1</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell}

:::

::: {.cell layout-align="center"}
::: {.cell-output-display}
![](ADC-US-RES-23241-SE03_files/figure-html/Survival Plot Function-1.png){fig-align='center' width=672}
:::
:::

::: {.cell}
::: {.cell-output-display}


```{=html}
<div id="jhxecfawzz" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#jhxecfawzz table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#jhxecfawzz thead, #jhxecfawzz tbody, #jhxecfawzz tfoot, #jhxecfawzz tr, #jhxecfawzz td, #jhxecfawzz th {
  border-style: none;
}

#jhxecfawzz p {
  margin: 0;
  padding: 0;
}

#jhxecfawzz .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#jhxecfawzz .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#jhxecfawzz .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#jhxecfawzz .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#jhxecfawzz .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#jhxecfawzz .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#jhxecfawzz .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#jhxecfawzz .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#jhxecfawzz .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#jhxecfawzz .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#jhxecfawzz .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#jhxecfawzz .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#jhxecfawzz .gt_spanner_row {
  border-bottom-style: hidden;
}

#jhxecfawzz .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#jhxecfawzz .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#jhxecfawzz .gt_from_md > :first-child {
  margin-top: 0;
}

#jhxecfawzz .gt_from_md > :last-child {
  margin-bottom: 0;
}

#jhxecfawzz .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#jhxecfawzz .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#jhxecfawzz .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#jhxecfawzz .gt_row_group_first td {
  border-top-width: 2px;
}

#jhxecfawzz .gt_row_group_first th {
  border-top-width: 2px;
}

#jhxecfawzz .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#jhxecfawzz .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#jhxecfawzz .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#jhxecfawzz .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#jhxecfawzz .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#jhxecfawzz .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#jhxecfawzz .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#jhxecfawzz .gt_striped {
  background-color: #EDF7FC;
}

#jhxecfawzz .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#jhxecfawzz .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#jhxecfawzz .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#jhxecfawzz .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#jhxecfawzz .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#jhxecfawzz .gt_left {
  text-align: left;
}

#jhxecfawzz .gt_center {
  text-align: center;
}

#jhxecfawzz .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#jhxecfawzz .gt_font_normal {
  font-weight: normal;
}

#jhxecfawzz .gt_font_bold {
  font-weight: bold;
}

#jhxecfawzz .gt_font_italic {
  font-style: italic;
}

#jhxecfawzz .gt_super {
  font-size: 65%;
}

#jhxecfawzz .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#jhxecfawzz .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#jhxecfawzz .gt_indent_1 {
  text-indent: 5px;
}

#jhxecfawzz .gt_indent_2 {
  text-indent: 10px;
}

#jhxecfawzz .gt_indent_3 {
  text-indent: 15px;
}

#jhxecfawzz .gt_indent_4 {
  text-indent: 20px;
}

#jhxecfawzz .gt_indent_5 {
  text-indent: 25px;
}

#jhxecfawzz .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#jhxecfawzz div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Day">Day</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Number of Remaining Sensors">Number of Remaining Sensors</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Number of Failed Sensors">Number of Failed Sensors</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Survival Probability Estimate (%)">Survival Probability Estimate (%)</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Estimate SE (%)">Estimate SE (%)</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Day" class="gt_row gt_center">0</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center">35</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center">0</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center">100.0</td>
<td headers="Estimate SE (%)" class="gt_row gt_center">0.0</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">1</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center gt_striped">35</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center gt_striped">0</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center gt_striped">100.0</td>
<td headers="Estimate SE (%)" class="gt_row gt_center gt_striped">0.0</td></tr>
    <tr><td headers="Day" class="gt_row gt_center">2</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center">35</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center">0</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center">100.0</td>
<td headers="Estimate SE (%)" class="gt_row gt_center">0.0</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">3</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center gt_striped">33</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center gt_striped">2</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center gt_striped">94.3</td>
<td headers="Estimate SE (%)" class="gt_row gt_center gt_striped">3.9</td></tr>
    <tr><td headers="Day" class="gt_row gt_center">4</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center">32</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center">3</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center">91.4</td>
<td headers="Estimate SE (%)" class="gt_row gt_center">4.7</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">5</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center gt_striped">31</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center gt_striped">4</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center gt_striped">88.6</td>
<td headers="Estimate SE (%)" class="gt_row gt_center gt_striped">5.4</td></tr>
    <tr><td headers="Day" class="gt_row gt_center">6</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center">31</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center">4</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center">88.6</td>
<td headers="Estimate SE (%)" class="gt_row gt_center">5.4</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">7</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center gt_striped">30</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center gt_striped">5</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center gt_striped">85.7</td>
<td headers="Estimate SE (%)" class="gt_row gt_center gt_striped">5.9</td></tr>
    <tr><td headers="Day" class="gt_row gt_center">8</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center">30</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center">5</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center">85.7</td>
<td headers="Estimate SE (%)" class="gt_row gt_center">5.9</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">9</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center gt_striped">30</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center gt_striped">5</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center gt_striped">85.7</td>
<td headers="Estimate SE (%)" class="gt_row gt_center gt_striped">5.9</td></tr>
    <tr><td headers="Day" class="gt_row gt_center">10</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center">29</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center">6</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center">82.9</td>
<td headers="Estimate SE (%)" class="gt_row gt_center">6.4</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">11</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center gt_striped">28</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center gt_striped">7</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center gt_striped">80.0</td>
<td headers="Estimate SE (%)" class="gt_row gt_center gt_striped">6.8</td></tr>
    <tr><td headers="Day" class="gt_row gt_center">12</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center">27</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center">8</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center">77.1</td>
<td headers="Estimate SE (%)" class="gt_row gt_center">7.1</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">13</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center gt_striped">27</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center gt_striped">8</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center gt_striped">77.1</td>
<td headers="Estimate SE (%)" class="gt_row gt_center gt_striped">7.1</td></tr>
    <tr><td headers="Day" class="gt_row gt_center">14</td>
<td headers="Number of Remaining Sensors" class="gt_row gt_center">15</td>
<td headers="Number of Failed Sensors" class="gt_row gt_center">8</td>
<td headers="Survival Probability Estimate (%)" class="gt_row gt_center">77.1</td>
<td headers="Estimate SE (%)" class="gt_row gt_center">7.1</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::



# **Accuracy Performance**

## Difference Measures


::: {.cell layout-align="center"}
::: {.cell-output-display}
![](ADC-US-RES-23241-SE03_files/figure-html/MARD Line Plot-1.png){fig-align='center' width=672}
:::
:::

::: {.cell layout-align="center"}
::: {.cell-output-display}
![](ADC-US-RES-23241-SE03_files/figure-html/Bias Line Plot-1.png){fig-align='center' width=672}
:::
:::

::: {.cell .column-page}
::: {.cell-output-display}


```{=html}
<div id="dlwljpruoz" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#dlwljpruoz table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#dlwljpruoz thead, #dlwljpruoz tbody, #dlwljpruoz tfoot, #dlwljpruoz tr, #dlwljpruoz td, #dlwljpruoz th {
  border-style: none;
}

#dlwljpruoz p {
  margin: 0;
  padding: 0;
}

#dlwljpruoz .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#dlwljpruoz .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#dlwljpruoz .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#dlwljpruoz .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#dlwljpruoz .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#dlwljpruoz .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#dlwljpruoz .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#dlwljpruoz .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#dlwljpruoz .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#dlwljpruoz .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#dlwljpruoz .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#dlwljpruoz .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#dlwljpruoz .gt_spanner_row {
  border-bottom-style: hidden;
}

#dlwljpruoz .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#dlwljpruoz .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#dlwljpruoz .gt_from_md > :first-child {
  margin-top: 0;
}

#dlwljpruoz .gt_from_md > :last-child {
  margin-bottom: 0;
}

#dlwljpruoz .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#dlwljpruoz .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#dlwljpruoz .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#dlwljpruoz .gt_row_group_first td {
  border-top-width: 2px;
}

#dlwljpruoz .gt_row_group_first th {
  border-top-width: 2px;
}

#dlwljpruoz .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#dlwljpruoz .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#dlwljpruoz .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#dlwljpruoz .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#dlwljpruoz .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#dlwljpruoz .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#dlwljpruoz .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#dlwljpruoz .gt_striped {
  background-color: #EDF7FC;
}

#dlwljpruoz .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#dlwljpruoz .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#dlwljpruoz .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#dlwljpruoz .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#dlwljpruoz .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#dlwljpruoz .gt_left {
  text-align: left;
}

#dlwljpruoz .gt_center {
  text-align: center;
}

#dlwljpruoz .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#dlwljpruoz .gt_font_normal {
  font-weight: normal;
}

#dlwljpruoz .gt_font_bold {
  font-weight: bold;
}

#dlwljpruoz .gt_font_italic {
  font-style: italic;
}

#dlwljpruoz .gt_super {
  font-size: 65%;
}

#dlwljpruoz .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#dlwljpruoz .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#dlwljpruoz .gt_indent_1 {
  text-indent: 5px;
}

#dlwljpruoz .gt_indent_2 {
  text-indent: 10px;
}

#dlwljpruoz .gt_indent_3 {
  text-indent: 15px;
}

#dlwljpruoz .gt_indent_4 {
  text-indent: 20px;
}

#dlwljpruoz .gt_indent_5 {
  text-indent: 25px;
}

#dlwljpruoz .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#dlwljpruoz div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="8" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipEaWZmZXJlbmNlIE1lYXN1cmVzIGF0IDEwMCBtZy9kTCBicmVha3BvaW50Kio="><div class='gt_from_md'><p><strong>Difference Measures at 100 mg/dL breakpoint</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Measure">Measure</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Min">Min</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Max">Max</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Grand Mean (95% CI)">Grand Mean (95% CI)</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="N">N</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr class="gt_group_heading_row">
      <th colspan="8" class="gt_group_heading" scope="colgroup" id="&amp;lt;100 mg/dL[5.6 mmol/L]">&lt;100 mg/dL[5.6 mmol/L]</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="<100 mg/dL[5.6 mmol/L]  Measure" class="gt_row gt_center">Difference (mmol/L)</td>
<td headers="<100 mg/dL[5.6 mmol/L]  Mean" class="gt_row gt_center">1.4</td>
<td headers="<100 mg/dL[5.6 mmol/L]  SD" class="gt_row gt_center">1.7</td>
<td headers="<100 mg/dL[5.6 mmol/L]  Median" class="gt_row gt_center">1.5</td>
<td headers="<100 mg/dL[5.6 mmol/L]  Min" class="gt_row gt_center">−3.1</td>
<td headers="<100 mg/dL[5.6 mmol/L]  Max" class="gt_row gt_center">7.2</td>
<td headers="<100 mg/dL[5.6 mmol/L]  Grand Mean (95% CI)" class="gt_row gt_center">1.9 (1.5,2.4)</td>
<td headers="<100 mg/dL[5.6 mmol/L]  N" class="gt_row gt_center">432</td></tr>
    <tr><td headers="<100 mg/dL[5.6 mmol/L]  Measure" class="gt_row gt_center gt_striped">Absolute Difference (mmol/L)</td>
<td headers="<100 mg/dL[5.6 mmol/L]  Mean" class="gt_row gt_center gt_striped">1.9</td>
<td headers="<100 mg/dL[5.6 mmol/L]  SD" class="gt_row gt_center gt_striped">1.2</td>
<td headers="<100 mg/dL[5.6 mmol/L]  Median" class="gt_row gt_center gt_striped">1.8</td>
<td headers="<100 mg/dL[5.6 mmol/L]  Min" class="gt_row gt_center gt_striped">0.0</td>
<td headers="<100 mg/dL[5.6 mmol/L]  Max" class="gt_row gt_center gt_striped">7.2</td>
<td headers="<100 mg/dL[5.6 mmol/L]  Grand Mean (95% CI)" class="gt_row gt_center gt_striped">2.2 (1.8,2.5)</td>
<td headers="<100 mg/dL[5.6 mmol/L]  N" class="gt_row gt_center gt_striped">432</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="8" class="gt_group_heading" scope="colgroup" id="&amp;gt;=100 mg/dL[5.6 mmol/L]">&gt;=100 mg/dL[5.6 mmol/L]</th>
    </tr>
    <tr class="gt_row_group_first"><td headers=">=100 mg/dL[5.6 mmol/L]  Measure" class="gt_row gt_center">Relative Difference(%)</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  Mean" class="gt_row gt_center">14.9</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  SD" class="gt_row gt_center">28.3</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  Median" class="gt_row gt_center">17.2</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  Min" class="gt_row gt_center">−76.3</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  Max" class="gt_row gt_center">95.6</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  Grand Mean (95% CI)" class="gt_row gt_center">14.2 (7.4,21.1)</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  N" class="gt_row gt_center">2328</td></tr>
    <tr><td headers=">=100 mg/dL[5.6 mmol/L]  Measure" class="gt_row gt_center gt_striped">Absolute Relative Difference(%)</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  Mean" class="gt_row gt_center gt_striped">26.3</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  SD" class="gt_row gt_center gt_striped">18.3</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  Median" class="gt_row gt_center gt_striped">23.1</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  Min" class="gt_row gt_center gt_striped">0.1</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  Max" class="gt_row gt_center gt_striped">95.6</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  Grand Mean (95% CI)" class="gt_row gt_center gt_striped">26.1 (22.1,30.1)</td>
<td headers=">=100 mg/dL[5.6 mmol/L]  N" class="gt_row gt_center gt_striped">2328</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="8" class="gt_group_heading" scope="colgroup" id="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)">Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Measure" class="gt_row gt_center">Difference (mmol/L)</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Mean" class="gt_row gt_center">1.3</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  SD" class="gt_row gt_center">2.6</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Median" class="gt_row gt_center">1.5</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Min" class="gt_row gt_center">−12.0</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Max" class="gt_row gt_center">11.7</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Grand Mean (95% CI)" class="gt_row gt_center">1.2 (0.6,1.8)</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  N" class="gt_row gt_center">2760</td></tr>
    <tr><td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Measure" class="gt_row gt_center gt_striped">Absolute Difference (mmol/L)</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Mean" class="gt_row gt_center gt_striped">2.3</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  SD" class="gt_row gt_center gt_striped">1.7</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Median" class="gt_row gt_center gt_striped">2.1</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Min" class="gt_row gt_center gt_striped">0.0</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Max" class="gt_row gt_center gt_striped">12.0</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Grand Mean (95% CI)" class="gt_row gt_center gt_striped">2.3 (2,2.7)</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  N" class="gt_row gt_center gt_striped">2760</td></tr>
    <tr><td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Measure" class="gt_row gt_center">Relative Difference(%)</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Mean" class="gt_row gt_center">17.3</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  SD" class="gt_row gt_center">30.5</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Median" class="gt_row gt_center">18.6</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Min" class="gt_row gt_center">−76.3</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Max" class="gt_row gt_center">159.3</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Grand Mean (95% CI)" class="gt_row gt_center">17.3 (10.4,24.3)</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  N" class="gt_row gt_center">2760</td></tr>
    <tr><td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Measure" class="gt_row gt_center gt_striped">Absolute Relative Difference(%)</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Mean" class="gt_row gt_center gt_striped">28.5</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  SD" class="gt_row gt_center gt_striped">20.5</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Median" class="gt_row gt_center gt_striped">25.0</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Min" class="gt_row gt_center gt_striped">0.1</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Max" class="gt_row gt_center gt_striped">159.3</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  Grand Mean (95% CI)" class="gt_row gt_center gt_striped">28.2 (23.9,32.5)</td>
<td headers="Overall Levels (100 mg/dL[5.6 mmol/L] breakpoint)  N" class="gt_row gt_center gt_striped">2760</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell .column-page}
::: {.cell-output-display}


```{=html}
<div id="bwreldnmhb" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#bwreldnmhb table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#bwreldnmhb thead, #bwreldnmhb tbody, #bwreldnmhb tfoot, #bwreldnmhb tr, #bwreldnmhb td, #bwreldnmhb th {
  border-style: none;
}

#bwreldnmhb p {
  margin: 0;
  padding: 0;
}

#bwreldnmhb .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#bwreldnmhb .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#bwreldnmhb .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#bwreldnmhb .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#bwreldnmhb .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#bwreldnmhb .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#bwreldnmhb .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#bwreldnmhb .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#bwreldnmhb .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#bwreldnmhb .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#bwreldnmhb .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#bwreldnmhb .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#bwreldnmhb .gt_spanner_row {
  border-bottom-style: hidden;
}

#bwreldnmhb .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#bwreldnmhb .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#bwreldnmhb .gt_from_md > :first-child {
  margin-top: 0;
}

#bwreldnmhb .gt_from_md > :last-child {
  margin-bottom: 0;
}

#bwreldnmhb .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#bwreldnmhb .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#bwreldnmhb .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#bwreldnmhb .gt_row_group_first td {
  border-top-width: 2px;
}

#bwreldnmhb .gt_row_group_first th {
  border-top-width: 2px;
}

#bwreldnmhb .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#bwreldnmhb .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#bwreldnmhb .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#bwreldnmhb .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#bwreldnmhb .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#bwreldnmhb .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#bwreldnmhb .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#bwreldnmhb .gt_striped {
  background-color: #EDF7FC;
}

#bwreldnmhb .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#bwreldnmhb .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#bwreldnmhb .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#bwreldnmhb .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#bwreldnmhb .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#bwreldnmhb .gt_left {
  text-align: left;
}

#bwreldnmhb .gt_center {
  text-align: center;
}

#bwreldnmhb .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#bwreldnmhb .gt_font_normal {
  font-weight: normal;
}

#bwreldnmhb .gt_font_bold {
  font-weight: bold;
}

#bwreldnmhb .gt_font_italic {
  font-style: italic;
}

#bwreldnmhb .gt_super {
  font-size: 65%;
}

#bwreldnmhb .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#bwreldnmhb .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#bwreldnmhb .gt_indent_1 {
  text-indent: 5px;
}

#bwreldnmhb .gt_indent_2 {
  text-indent: 10px;
}

#bwreldnmhb .gt_indent_3 {
  text-indent: 15px;
}

#bwreldnmhb .gt_indent_4 {
  text-indent: 20px;
}

#bwreldnmhb .gt_indent_5 {
  text-indent: 25px;
}

#bwreldnmhb .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#bwreldnmhb div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="14" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipEaWZmZXJlbmNlIE1lYXN1cmVzIEdyb3VwIGJ5IFJlZmVyZW5jZSBHbHVjb3NlIExldmVsKio="><div class='gt_from_md'><p><strong>Difference Measures Group by Reference Glucose Level</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings gt_spanner_row">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="2" colspan="1" scope="col" id="Glucose Level(mg/dL) [mmol/L]">Glucose Level(mg/dL) [mmol/L]</th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Difference (mmol/L)">
        <span class="gt_column_spanner">Difference (mmol/L)</span>
      </th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Abs. Difference (mmol/L)">
        <span class="gt_column_spanner">Abs. Difference (mmol/L)</span>
      </th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Relative Difference(%)">
        <span class="gt_column_spanner">Relative Difference(%)</span>
      </th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Absolute Relative Difference(%)">
        <span class="gt_column_spanner">Absolute Relative Difference(%)</span>
      </th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="2" colspan="1" scope="col" id="N">N</th>
    </tr>
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center">&lt;54 [3.0]</td>
<td headers="Difference Mean" class="gt_row gt_center">1.5</td>
<td headers="Difference Median" class="gt_row gt_center">1.9</td>
<td headers="Difference SD" class="gt_row gt_center">1.30</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">1.7</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">1.9</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">0.97</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">56.4</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">69.6</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">48.02</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">63.6</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">69.6</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">36.40</td>
<td headers="N" class="gt_row gt_center">8</td></tr>
    <tr><td headers="Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center gt_striped">54 to 69 [3.0-3.8]</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">1.4</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">1.5</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">1.80</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">1.8</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">1.5</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.30</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">39.8</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">47.4</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">52.34</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">53.0</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">47.4</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">38.40</td>
<td headers="N" class="gt_row gt_center gt_striped">37</td></tr>
    <tr><td headers="Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center">70 to 180 [3.9-10.0]</td>
<td headers="Difference Mean" class="gt_row gt_center">1.4</td>
<td headers="Difference Median" class="gt_row gt_center">1.5</td>
<td headers="Difference SD" class="gt_row gt_center">2.08</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.1</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">1.9</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.38</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">20.3</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">21.7</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">30.93</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">30.5</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">27.7</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">20.85</td>
<td headers="N" class="gt_row gt_center">1911</td></tr>
    <tr><td headers="Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center gt_striped">181 to 250 [10.0-13.9]</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">1.3</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">1.5</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.96</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.6</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">2.4</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.86</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">11.4</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">14.0</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">25.25</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">22.6</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">19.8</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">15.93</td>
<td headers="N" class="gt_row gt_center gt_striped">509</td></tr>
    <tr><td headers="Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center">&gt;250 [13.9]</td>
<td headers="Difference Mean" class="gt_row gt_center">0.5</td>
<td headers="Difference Median" class="gt_row gt_center">1.1</td>
<td headers="Difference SD" class="gt_row gt_center">4.20</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">3.5</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.9</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">2.41</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">4.0</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">6.6</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">24.98</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">21.0</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">17.6</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">14.14</td>
<td headers="N" class="gt_row gt_center">295</td></tr>
    <tr><td headers="Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center gt_striped">Overall</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">1.3</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">1.5</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.57</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.3</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">2.1</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.68</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">17.3</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">18.6</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">30.50</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">28.5</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">25.0</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">20.46</td>
<td headers="N" class="gt_row gt_center gt_striped">2760</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell .column-page}
::: {.cell-output-display}


```{=html}
<div id="coevhdotop" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#coevhdotop table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#coevhdotop thead, #coevhdotop tbody, #coevhdotop tfoot, #coevhdotop tr, #coevhdotop td, #coevhdotop th {
  border-style: none;
}

#coevhdotop p {
  margin: 0;
  padding: 0;
}

#coevhdotop .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#coevhdotop .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#coevhdotop .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#coevhdotop .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#coevhdotop .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#coevhdotop .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#coevhdotop .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#coevhdotop .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#coevhdotop .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#coevhdotop .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#coevhdotop .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#coevhdotop .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#coevhdotop .gt_spanner_row {
  border-bottom-style: hidden;
}

#coevhdotop .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#coevhdotop .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#coevhdotop .gt_from_md > :first-child {
  margin-top: 0;
}

#coevhdotop .gt_from_md > :last-child {
  margin-bottom: 0;
}

#coevhdotop .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#coevhdotop .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#coevhdotop .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#coevhdotop .gt_row_group_first td {
  border-top-width: 2px;
}

#coevhdotop .gt_row_group_first th {
  border-top-width: 2px;
}

#coevhdotop .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#coevhdotop .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#coevhdotop .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#coevhdotop .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#coevhdotop .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#coevhdotop .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#coevhdotop .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#coevhdotop .gt_striped {
  background-color: #EDF7FC;
}

#coevhdotop .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#coevhdotop .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#coevhdotop .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#coevhdotop .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#coevhdotop .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#coevhdotop .gt_left {
  text-align: left;
}

#coevhdotop .gt_center {
  text-align: center;
}

#coevhdotop .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#coevhdotop .gt_font_normal {
  font-weight: normal;
}

#coevhdotop .gt_font_bold {
  font-weight: bold;
}

#coevhdotop .gt_font_italic {
  font-style: italic;
}

#coevhdotop .gt_super {
  font-size: 65%;
}

#coevhdotop .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#coevhdotop .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#coevhdotop .gt_indent_1 {
  text-indent: 5px;
}

#coevhdotop .gt_indent_2 {
  text-indent: 10px;
}

#coevhdotop .gt_indent_3 {
  text-indent: 15px;
}

#coevhdotop .gt_indent_4 {
  text-indent: 20px;
}

#coevhdotop .gt_indent_5 {
  text-indent: 25px;
}

#coevhdotop .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#coevhdotop div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="14" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipEaWZmZXJlbmNlIE1lYXN1cmVzIEdyb3VwIGJ5IFdlYXIgUGVyaW9kKio="><div class='gt_from_md'><p><strong>Difference Measures Group by Wear Period</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings gt_spanner_row">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="2" colspan="1" scope="col" id="Wear Period">Wear Period</th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Difference (mmol/L)">
        <span class="gt_column_spanner">Difference (mmol/L)</span>
      </th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Abs. Difference (mmol/L)">
        <span class="gt_column_spanner">Abs. Difference (mmol/L)</span>
      </th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Relative Difference(%)">
        <span class="gt_column_spanner">Relative Difference(%)</span>
      </th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Absolute Relative Difference(%)">
        <span class="gt_column_spanner">Absolute Relative Difference(%)</span>
      </th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="2" colspan="1" scope="col" id="N">N</th>
    </tr>
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Wear Period" class="gt_row gt_center">Beginning</td>
<td headers="Difference Mean" class="gt_row gt_center">2.0</td>
<td headers="Difference Median" class="gt_row gt_center">2.2</td>
<td headers="Difference SD" class="gt_row gt_center">2.39</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.6</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.4</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.72</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">28.2</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">27.6</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">28.59</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">32.7</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">29.1</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">23.22</td>
<td headers="N" class="gt_row gt_center">699</td></tr>
    <tr><td headers="Wear Period" class="gt_row gt_center gt_striped">Early Middle</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">1.9</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">2.0</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.01</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.4</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">2.2</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.51</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">24.8</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">24.6</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">24.95</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">28.9</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">26.0</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">19.96</td>
<td headers="N" class="gt_row gt_center gt_striped">1010</td></tr>
    <tr><td headers="Wear Period" class="gt_row gt_center">Late Middle</td>
<td headers="Difference Mean" class="gt_row gt_center">0.5</td>
<td headers="Difference Median" class="gt_row gt_center">0.6</td>
<td headers="Difference SD" class="gt_row gt_center">2.64</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.1</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">1.7</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.71</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">7.0</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">7.7</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">30.14</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">24.9</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">20.1</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">18.36</td>
<td headers="N" class="gt_row gt_center">715</td></tr>
    <tr><td headers="Wear Period" class="gt_row gt_center gt_striped">End</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">−0.7</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">−0.5</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.77</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.1</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">1.8</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.89</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">−6.1</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">−6.2</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">30.96</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">25.7</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">23.1</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">18.24</td>
<td headers="N" class="gt_row gt_center gt_striped">336</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell .column-page}
::: {.cell-output-display}


```{=html}
<div id="vkynqpzqrv" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#vkynqpzqrv table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#vkynqpzqrv thead, #vkynqpzqrv tbody, #vkynqpzqrv tfoot, #vkynqpzqrv tr, #vkynqpzqrv td, #vkynqpzqrv th {
  border-style: none;
}

#vkynqpzqrv p {
  margin: 0;
  padding: 0;
}

#vkynqpzqrv .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#vkynqpzqrv .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#vkynqpzqrv .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#vkynqpzqrv .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#vkynqpzqrv .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#vkynqpzqrv .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#vkynqpzqrv .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#vkynqpzqrv .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#vkynqpzqrv .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#vkynqpzqrv .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#vkynqpzqrv .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#vkynqpzqrv .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#vkynqpzqrv .gt_spanner_row {
  border-bottom-style: hidden;
}

#vkynqpzqrv .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#vkynqpzqrv .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#vkynqpzqrv .gt_from_md > :first-child {
  margin-top: 0;
}

#vkynqpzqrv .gt_from_md > :last-child {
  margin-bottom: 0;
}

#vkynqpzqrv .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#vkynqpzqrv .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#vkynqpzqrv .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#vkynqpzqrv .gt_row_group_first td {
  border-top-width: 2px;
}

#vkynqpzqrv .gt_row_group_first th {
  border-top-width: 2px;
}

#vkynqpzqrv .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#vkynqpzqrv .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#vkynqpzqrv .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#vkynqpzqrv .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#vkynqpzqrv .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#vkynqpzqrv .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#vkynqpzqrv .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#vkynqpzqrv .gt_striped {
  background-color: #EDF7FC;
}

#vkynqpzqrv .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#vkynqpzqrv .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#vkynqpzqrv .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#vkynqpzqrv .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#vkynqpzqrv .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#vkynqpzqrv .gt_left {
  text-align: left;
}

#vkynqpzqrv .gt_center {
  text-align: center;
}

#vkynqpzqrv .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#vkynqpzqrv .gt_font_normal {
  font-weight: normal;
}

#vkynqpzqrv .gt_font_bold {
  font-weight: bold;
}

#vkynqpzqrv .gt_font_italic {
  font-style: italic;
}

#vkynqpzqrv .gt_super {
  font-size: 65%;
}

#vkynqpzqrv .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#vkynqpzqrv .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#vkynqpzqrv .gt_indent_1 {
  text-indent: 5px;
}

#vkynqpzqrv .gt_indent_2 {
  text-indent: 10px;
}

#vkynqpzqrv .gt_indent_3 {
  text-indent: 15px;
}

#vkynqpzqrv .gt_indent_4 {
  text-indent: 20px;
}

#vkynqpzqrv .gt_indent_5 {
  text-indent: 25px;
}

#vkynqpzqrv .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#vkynqpzqrv div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="14" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipEaWZmZXJlbmNlIE1lYXN1cmVzIEdyb3VwIGJ5IERheSoq"><div class='gt_from_md'><p><strong>Difference Measures Group by Day</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings gt_spanner_row">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="2" colspan="1" scope="col" id="Day">Day</th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Difference (mmol/L)">
        <span class="gt_column_spanner">Difference (mmol/L)</span>
      </th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Abs. Difference (mmol/L)">
        <span class="gt_column_spanner">Abs. Difference (mmol/L)</span>
      </th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Relative Difference(%)">
        <span class="gt_column_spanner">Relative Difference(%)</span>
      </th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Absolute Relative Difference(%)">
        <span class="gt_column_spanner">Absolute Relative Difference(%)</span>
      </th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="2" colspan="1" scope="col" id="N">N</th>
    </tr>
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Day" class="gt_row gt_center">1</td>
<td headers="Difference Mean" class="gt_row gt_center">1.5</td>
<td headers="Difference Median" class="gt_row gt_center">1.7</td>
<td headers="Difference SD" class="gt_row gt_center">2.45</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.3</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.0</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.68</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">22.7</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">20.6</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">30.79</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">29.6</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">25.4</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">24.27</td>
<td headers="N" class="gt_row gt_center">245</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">2</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">2.3</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">2.3</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.31</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.8</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">2.6</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.71</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">30.8</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">29.8</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">27.05</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">34.2</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">30.9</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">22.58</td>
<td headers="N" class="gt_row gt_center gt_striped">238</td></tr>
    <tr><td headers="Day" class="gt_row gt_center">3</td>
<td headers="Difference Mean" class="gt_row gt_center">2.3</td>
<td headers="Difference Median" class="gt_row gt_center">2.6</td>
<td headers="Difference SD" class="gt_row gt_center">2.31</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.8</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.7</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.74</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">31.3</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">32.0</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">26.82</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">34.6</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">33.9</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">22.44</td>
<td headers="N" class="gt_row gt_center">216</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">4</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">2.4</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">2.6</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.03</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.7</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">2.6</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.58</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">30.5</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">32.2</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">23.27</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">33.0</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">32.3</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">19.60</td>
<td headers="N" class="gt_row gt_center gt_striped">215</td></tr>
    <tr><td headers="Day" class="gt_row gt_center">5</td>
<td headers="Difference Mean" class="gt_row gt_center">2.2</td>
<td headers="Difference Median" class="gt_row gt_center">2.2</td>
<td headers="Difference SD" class="gt_row gt_center">2.01</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.5</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.4</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.56</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">27.7</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">26.9</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">25.44</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">30.6</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">28.0</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">21.89</td>
<td headers="N" class="gt_row gt_center">195</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">6</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">1.9</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">2.1</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">1.83</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">2.2</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.41</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">25.0</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">23.8</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">24.63</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">28.5</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">24.4</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">20.47</td>
<td headers="N" class="gt_row gt_center gt_striped">204</td></tr>
    <tr><td headers="Day" class="gt_row gt_center">7</td>
<td headers="Difference Mean" class="gt_row gt_center">1.9</td>
<td headers="Difference Median" class="gt_row gt_center">2.0</td>
<td headers="Difference SD" class="gt_row gt_center">2.09</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.3</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.1</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.55</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">22.6</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">24.2</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">24.54</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">27.8</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">25.3</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">18.40</td>
<td headers="N" class="gt_row gt_center">198</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">8</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">1.3</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">1.4</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">1.97</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.0</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">1.7</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.34</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">17.6</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">17.6</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">25.21</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">24.6</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">20.4</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">18.42</td>
<td headers="N" class="gt_row gt_center gt_striped">198</td></tr>
    <tr><td headers="Day" class="gt_row gt_center">9</td>
<td headers="Difference Mean" class="gt_row gt_center">1.0</td>
<td headers="Difference Median" class="gt_row gt_center">1.2</td>
<td headers="Difference SD" class="gt_row gt_center">2.59</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">1.8</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.72</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">13.1</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">16.0</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">28.08</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">25.4</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">22.2</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">17.60</td>
<td headers="N" class="gt_row gt_center">191</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">10</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">0.3</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">0.3</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.62</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.0</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">1.7</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.69</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">6.0</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">3.8</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">29.98</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">24.0</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">19.5</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">18.88</td>
<td headers="N" class="gt_row gt_center gt_striped">182</td></tr>
    <tr><td headers="Day" class="gt_row gt_center">11</td>
<td headers="Difference Mean" class="gt_row gt_center">0.4</td>
<td headers="Difference Median" class="gt_row gt_center">0.6</td>
<td headers="Difference SD" class="gt_row gt_center">2.42</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">1.9</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">1.6</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.52</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">4.4</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">8.5</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">29.57</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">24.2</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">19.0</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">17.44</td>
<td headers="N" class="gt_row gt_center">180</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">12</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">0.2</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">0.3</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.89</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">1.6</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.89</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">3.9</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">3.8</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">32.46</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">26.0</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">20.8</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">19.69</td>
<td headers="N" class="gt_row gt_center gt_striped">162</td></tr>
    <tr><td headers="Day" class="gt_row gt_center">13</td>
<td headers="Difference Mean" class="gt_row gt_center">−0.5</td>
<td headers="Difference Median" class="gt_row gt_center">−0.3</td>
<td headers="Difference SD" class="gt_row gt_center">2.60</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.0</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">1.6</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.69</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">−3.8</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">−4.4</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">30.54</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">24.7</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">21.2</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">18.24</td>
<td headers="N" class="gt_row gt_center">178</td></tr>
    <tr><td headers="Day" class="gt_row gt_center gt_striped">14</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">−1.0</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">−0.7</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.95</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.3</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">1.9</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">2.09</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">−8.8</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">−8.9</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">31.31</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">26.8</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">24.9</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">18.25</td>
<td headers="N" class="gt_row gt_center gt_striped">158</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell .column-page}
::: {.cell-output-display}


```{=html}
<div id="cndvkhlhmx" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#cndvkhlhmx table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#cndvkhlhmx thead, #cndvkhlhmx tbody, #cndvkhlhmx tfoot, #cndvkhlhmx tr, #cndvkhlhmx td, #cndvkhlhmx th {
  border-style: none;
}

#cndvkhlhmx p {
  margin: 0;
  padding: 0;
}

#cndvkhlhmx .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#cndvkhlhmx .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#cndvkhlhmx .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#cndvkhlhmx .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#cndvkhlhmx .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#cndvkhlhmx .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#cndvkhlhmx .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#cndvkhlhmx .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#cndvkhlhmx .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#cndvkhlhmx .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#cndvkhlhmx .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#cndvkhlhmx .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#cndvkhlhmx .gt_spanner_row {
  border-bottom-style: hidden;
}

#cndvkhlhmx .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#cndvkhlhmx .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#cndvkhlhmx .gt_from_md > :first-child {
  margin-top: 0;
}

#cndvkhlhmx .gt_from_md > :last-child {
  margin-bottom: 0;
}

#cndvkhlhmx .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#cndvkhlhmx .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#cndvkhlhmx .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#cndvkhlhmx .gt_row_group_first td {
  border-top-width: 2px;
}

#cndvkhlhmx .gt_row_group_first th {
  border-top-width: 2px;
}

#cndvkhlhmx .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#cndvkhlhmx .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#cndvkhlhmx .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#cndvkhlhmx .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#cndvkhlhmx .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#cndvkhlhmx .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#cndvkhlhmx .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#cndvkhlhmx .gt_striped {
  background-color: #EDF7FC;
}

#cndvkhlhmx .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#cndvkhlhmx .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#cndvkhlhmx .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#cndvkhlhmx .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#cndvkhlhmx .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#cndvkhlhmx .gt_left {
  text-align: left;
}

#cndvkhlhmx .gt_center {
  text-align: center;
}

#cndvkhlhmx .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#cndvkhlhmx .gt_font_normal {
  font-weight: normal;
}

#cndvkhlhmx .gt_font_bold {
  font-weight: bold;
}

#cndvkhlhmx .gt_font_italic {
  font-style: italic;
}

#cndvkhlhmx .gt_super {
  font-size: 65%;
}

#cndvkhlhmx .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#cndvkhlhmx .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#cndvkhlhmx .gt_indent_1 {
  text-indent: 5px;
}

#cndvkhlhmx .gt_indent_2 {
  text-indent: 10px;
}

#cndvkhlhmx .gt_indent_3 {
  text-indent: 15px;
}

#cndvkhlhmx .gt_indent_4 {
  text-indent: 20px;
}

#cndvkhlhmx .gt_indent_5 {
  text-indent: 25px;
}

#cndvkhlhmx .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#cndvkhlhmx div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="14" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipEaWZmZXJlbmNlIE1lYXN1cmVzIEdyb3VwIGJ5IFN1YmplY3QqKg=="><div class='gt_from_md'><p><strong>Difference Measures Group by Subject</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings gt_spanner_row">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="2" colspan="1" scope="col" id="Subject ID">Subject ID</th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Difference (mmol/L)">
        <span class="gt_column_spanner">Difference (mmol/L)</span>
      </th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Abs. Difference (mmol/L)">
        <span class="gt_column_spanner">Abs. Difference (mmol/L)</span>
      </th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Relative Difference(%)">
        <span class="gt_column_spanner">Relative Difference(%)</span>
      </th>
      <th class="gt_center gt_columns_top_border gt_column_spanner_outer" rowspan="1" colspan="3" scope="colgroup" id="Absolute Relative Difference(%)">
        <span class="gt_column_spanner">Absolute Relative Difference(%)</span>
      </th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="2" colspan="1" scope="col" id="N">N</th>
    </tr>
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="SD">SD</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Subject ID" class="gt_row gt_center">1170001</td>
<td headers="Difference Mean" class="gt_row gt_center">1.9</td>
<td headers="Difference Median" class="gt_row gt_center">2.0</td>
<td headers="Difference SD" class="gt_row gt_center">1.37</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.0</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">0.76</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">27.3</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">28.9</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">18.32</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">30.1</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">28.9</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">12.89</td>
<td headers="N" class="gt_row gt_center">28</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170003</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">−2.8</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">−2.4</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">3.30</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">3.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">2.4</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">2.94</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">−15.3</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">−12.7</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">18.81</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">18.7</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">14.1</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">15.30</td>
<td headers="N" class="gt_row gt_center gt_striped">23</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170004</td>
<td headers="Difference Mean" class="gt_row gt_center">2.6</td>
<td headers="Difference Median" class="gt_row gt_center">2.7</td>
<td headers="Difference SD" class="gt_row gt_center">1.21</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.7</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.7</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.05</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">34.9</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">33.9</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">18.10</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">35.5</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">33.9</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">16.85</td>
<td headers="N" class="gt_row gt_center">109</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170005</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">2.5</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">3.0</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.68</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">3.3</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">3.2</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.72</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">23.4</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">22.7</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">23.07</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">27.8</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">24.0</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">17.42</td>
<td headers="N" class="gt_row gt_center gt_striped">110</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170006</td>
<td headers="Difference Mean" class="gt_row gt_center">−2.3</td>
<td headers="Difference Median" class="gt_row gt_center">−1.3</td>
<td headers="Difference SD" class="gt_row gt_center">2.82</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.5</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">1.6</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">2.57</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">−17.5</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">−13.5</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">20.57</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">20.5</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">14.7</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">17.51</td>
<td headers="N" class="gt_row gt_center">104</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170007</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">0.4</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">0.6</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">1.13</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">1.0</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">0.9</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">0.69</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">6.7</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">9.0</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">15.90</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">14.1</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">12.3</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">9.90</td>
<td headers="N" class="gt_row gt_center gt_striped">111</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170008</td>
<td headers="Difference Mean" class="gt_row gt_center">1.0</td>
<td headers="Difference Median" class="gt_row gt_center">1.2</td>
<td headers="Difference SD" class="gt_row gt_center">0.99</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">1.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">1.3</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">0.65</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">14.6</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">15.2</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">15.12</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">17.8</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">15.9</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">11.13</td>
<td headers="N" class="gt_row gt_center">109</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170009</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">0.8</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">1.0</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">1.15</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">1.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">1.1</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">0.75</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">16.7</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">15.7</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">21.30</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">22.0</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">19.0</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">15.75</td>
<td headers="N" class="gt_row gt_center gt_striped">46</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170010</td>
<td headers="Difference Mean" class="gt_row gt_center">−0.5</td>
<td headers="Difference Median" class="gt_row gt_center">−0.1</td>
<td headers="Difference SD" class="gt_row gt_center">1.65</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">1.0</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">0.6</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.36</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">−2.9</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">−1.1</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">15.24</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">10.8</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">7.7</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">10.97</td>
<td headers="N" class="gt_row gt_center">24</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170011</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">4.1</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">4.4</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.65</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">4.3</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">4.4</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">2.13</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">27.2</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">29.5</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">17.49</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">28.9</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">29.5</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">14.40</td>
<td headers="N" class="gt_row gt_center gt_striped">68</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170012</td>
<td headers="Difference Mean" class="gt_row gt_center">1.0</td>
<td headers="Difference Median" class="gt_row gt_center">1.5</td>
<td headers="Difference SD" class="gt_row gt_center">1.60</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">1.6</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">1.6</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">0.93</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">16.2</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">17.1</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">26.08</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">24.9</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">20.4</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">17.73</td>
<td headers="N" class="gt_row gt_center">67</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170014</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">0.4</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">0.5</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">1.16</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">0.9</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">0.8</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">0.77</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">7.3</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">8.4</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">17.10</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">14.3</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">12.9</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">11.80</td>
<td headers="N" class="gt_row gt_center gt_striped">95</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170015</td>
<td headers="Difference Mean" class="gt_row gt_center">0.7</td>
<td headers="Difference Median" class="gt_row gt_center">1.3</td>
<td headers="Difference SD" class="gt_row gt_center">2.49</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.3</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.2</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.24</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">9.0</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">12.8</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">27.88</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">25.3</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">25.4</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">14.61</td>
<td headers="N" class="gt_row gt_center">112</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170016</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">3.2</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">3.3</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">1.24</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">3.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">3.3</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.23</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">38.3</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">38.8</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">14.62</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">38.4</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">38.8</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">14.47</td>
<td headers="N" class="gt_row gt_center gt_striped">110</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170017</td>
<td headers="Difference Mean" class="gt_row gt_center">3.3</td>
<td headers="Difference Median" class="gt_row gt_center">3.6</td>
<td headers="Difference SD" class="gt_row gt_center">1.23</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">3.3</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">3.6</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.19</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">41.4</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">41.8</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">19.35</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">41.6</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">41.8</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">19.01</td>
<td headers="N" class="gt_row gt_center">112</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170018</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">2.5</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">2.7</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">1.93</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.8</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">2.8</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.50</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">26.2</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">28.3</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">20.38</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">28.0</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">28.3</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">17.77</td>
<td headers="N" class="gt_row gt_center gt_striped">106</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170019</td>
<td headers="Difference Mean" class="gt_row gt_center">0.4</td>
<td headers="Difference Median" class="gt_row gt_center">1.5</td>
<td headers="Difference SD" class="gt_row gt_center">2.60</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.4</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.4</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.12</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">8.1</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">20.1</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">38.22</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">35.2</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">36.1</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">16.61</td>
<td headers="N" class="gt_row gt_center">115</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170020</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">2.1</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">2.3</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">1.66</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">2.3</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.41</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">21.3</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">18.4</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">21.14</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">23.0</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">18.4</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">19.27</td>
<td headers="N" class="gt_row gt_center gt_striped">99</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170021</td>
<td headers="Difference Mean" class="gt_row gt_center">0.0</td>
<td headers="Difference Median" class="gt_row gt_center">0.0</td>
<td headers="Difference SD" class="gt_row gt_center">2.58</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.3</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.33</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">1.5</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">−0.5</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">43.87</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">36.0</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">34.5</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">24.80</td>
<td headers="N" class="gt_row gt_center">105</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170022</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">−1.7</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">−1.6</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">1.29</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">1.8</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">1.6</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.16</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">−12.7</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">−13.3</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">9.70</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">13.8</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">13.6</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">8.03</td>
<td headers="N" class="gt_row gt_center gt_striped">55</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170023</td>
<td headers="Difference Mean" class="gt_row gt_center">1.4</td>
<td headers="Difference Median" class="gt_row gt_center">1.6</td>
<td headers="Difference SD" class="gt_row gt_center">1.19</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">1.6</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">1.7</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">0.83</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">20.2</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">19.4</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">18.25</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">22.5</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">19.6</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">15.21</td>
<td headers="N" class="gt_row gt_center">65</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170024</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">−0.9</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">−0.3</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.87</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">1.7</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">2.07</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">−2.1</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">−4.2</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">34.10</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">27.9</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">26.8</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">19.53</td>
<td headers="N" class="gt_row gt_center gt_striped">86</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170025</td>
<td headers="Difference Mean" class="gt_row gt_center">2.9</td>
<td headers="Difference Median" class="gt_row gt_center">2.8</td>
<td headers="Difference SD" class="gt_row gt_center">0.86</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.9</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.8</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">0.86</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">54.4</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">54.4</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">18.18</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">54.4</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">54.4</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">18.18</td>
<td headers="N" class="gt_row gt_center">109</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170026</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">2.8</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">3.3</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">1.71</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">3.1</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">3.3</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">0.96</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">53.3</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">53.1</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">29.62</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">55.1</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">53.1</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">26.17</td>
<td headers="N" class="gt_row gt_center gt_striped">49</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170027</td>
<td headers="Difference Mean" class="gt_row gt_center">0.9</td>
<td headers="Difference Median" class="gt_row gt_center">1.9</td>
<td headers="Difference SD" class="gt_row gt_center">2.21</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">2.0</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.0</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.17</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">14.5</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">19.4</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">23.81</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">23.6</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">24.6</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">14.26</td>
<td headers="N" class="gt_row gt_center">20</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170028</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">0.8</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">1.1</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">0.97</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">1.1</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">1.1</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">0.58</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">15.9</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">19.3</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">17.57</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">20.5</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">20.1</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">11.70</td>
<td headers="N" class="gt_row gt_center gt_striped">59</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170029</td>
<td headers="Difference Mean" class="gt_row gt_center">0.1</td>
<td headers="Difference Median" class="gt_row gt_center">0.3</td>
<td headers="Difference SD" class="gt_row gt_center">2.17</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">1.8</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">1.8</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.20</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">4.6</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">2.0</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">18.02</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">13.9</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">12.0</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">12.34</td>
<td headers="N" class="gt_row gt_center">94</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170030</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">1.5</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">1.7</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">1.01</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">1.6</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">1.7</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">0.80</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">17.9</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">17.7</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">13.88</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">19.1</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">18.0</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">12.13</td>
<td headers="N" class="gt_row gt_center gt_striped">51</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170031</td>
<td headers="Difference Mean" class="gt_row gt_center">5.2</td>
<td headers="Difference Median" class="gt_row gt_center">5.3</td>
<td headers="Difference SD" class="gt_row gt_center">1.09</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">5.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">5.3</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.09</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">59.3</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">57.9</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">17.42</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">59.3</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">57.9</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">17.42</td>
<td headers="N" class="gt_row gt_center">27</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170032</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">2.8</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">3.3</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.82</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">3.3</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">3.3</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">2.17</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">30.5</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">32.6</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">32.42</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">37.6</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">35.8</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">23.65</td>
<td headers="N" class="gt_row gt_center gt_striped">109</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170033</td>
<td headers="Difference Mean" class="gt_row gt_center">3.0</td>
<td headers="Difference Median" class="gt_row gt_center">2.8</td>
<td headers="Difference SD" class="gt_row gt_center">2.10</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">3.1</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">2.8</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.89</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">32.4</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">32.5</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">20.35</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">33.5</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">32.5</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">18.56</td>
<td headers="N" class="gt_row gt_center">105</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170034</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">−0.1</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">−0.1</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">0.86</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">0.7</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">0.6</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">0.52</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">−0.2</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">−2.1</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">13.15</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">10.6</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">9.1</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">7.74</td>
<td headers="N" class="gt_row gt_center gt_striped">116</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170035</td>
<td headers="Difference Mean" class="gt_row gt_center">2.5</td>
<td headers="Difference Median" class="gt_row gt_center">3.3</td>
<td headers="Difference SD" class="gt_row gt_center">2.58</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center">3.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center">3.3</td>
<td headers="Absolute Difference SD" class="gt_row gt_center">1.66</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center">35.1</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center">38.1</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center">26.04</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center">38.8</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center">38.6</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center">20.00</td>
<td headers="N" class="gt_row gt_center">62</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170036</td>
<td headers="Difference Mean" class="gt_row gt_center gt_striped">−1.2</td>
<td headers="Difference Median" class="gt_row gt_center gt_striped">−1.3</td>
<td headers="Difference SD" class="gt_row gt_center gt_striped">2.64</td>
<td headers="Absolute Difference Mean" class="gt_row gt_center gt_striped">2.2</td>
<td headers="Absolute Difference Median" class="gt_row gt_center gt_striped">1.9</td>
<td headers="Absolute Difference SD" class="gt_row gt_center gt_striped">1.91</td>
<td headers="Relative Difference(%) Mean" class="gt_row gt_center gt_striped">−18.6</td>
<td headers="Relative Difference(%) Median" class="gt_row gt_center gt_striped">−26.2</td>
<td headers="Relative Difference(%) SD" class="gt_row gt_center gt_striped">39.73</td>
<td headers="Absolute Relative Difference(%) Mean" class="gt_row gt_center gt_striped">35.8</td>
<td headers="Absolute Relative Difference(%) Median" class="gt_row gt_center gt_striped">32.8</td>
<td headers="Absolute Relative Difference(%) SD" class="gt_row gt_center gt_striped">25.15</td>
<td headers="N" class="gt_row gt_center gt_striped">100</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::



## System Agreement Analysis


::: {.cell layout-align="center"}
::: {.cell-output-display}
![](ADC-US-RES-23241-SE03_files/figure-html/System Agreement Plot-1.png){fig-align='center' width=672}
:::
:::

::: {.cell .column-page}
::: {.cell-output-display}


```{=html}
<div id="ddigmknmtw" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#ddigmknmtw table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#ddigmknmtw thead, #ddigmknmtw tbody, #ddigmknmtw tfoot, #ddigmknmtw tr, #ddigmknmtw td, #ddigmknmtw th {
  border-style: none;
}

#ddigmknmtw p {
  margin: 0;
  padding: 0;
}

#ddigmknmtw .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#ddigmknmtw .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#ddigmknmtw .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#ddigmknmtw .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#ddigmknmtw .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#ddigmknmtw .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#ddigmknmtw .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#ddigmknmtw .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#ddigmknmtw .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#ddigmknmtw .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#ddigmknmtw .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#ddigmknmtw .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#ddigmknmtw .gt_spanner_row {
  border-bottom-style: hidden;
}

#ddigmknmtw .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#ddigmknmtw .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#ddigmknmtw .gt_from_md > :first-child {
  margin-top: 0;
}

#ddigmknmtw .gt_from_md > :last-child {
  margin-bottom: 0;
}

#ddigmknmtw .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#ddigmknmtw .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#ddigmknmtw .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#ddigmknmtw .gt_row_group_first td {
  border-top-width: 2px;
}

#ddigmknmtw .gt_row_group_first th {
  border-top-width: 2px;
}

#ddigmknmtw .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#ddigmknmtw .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#ddigmknmtw .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#ddigmknmtw .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#ddigmknmtw .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#ddigmknmtw .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#ddigmknmtw .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#ddigmknmtw .gt_striped {
  background-color: #EDF7FC;
}

#ddigmknmtw .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#ddigmknmtw .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#ddigmknmtw .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#ddigmknmtw .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#ddigmknmtw .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#ddigmknmtw .gt_left {
  text-align: left;
}

#ddigmknmtw .gt_center {
  text-align: center;
}

#ddigmknmtw .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#ddigmknmtw .gt_font_normal {
  font-weight: normal;
}

#ddigmknmtw .gt_font_bold {
  font-weight: bold;
}

#ddigmknmtw .gt_font_italic {
  font-style: italic;
}

#ddigmknmtw .gt_super {
  font-size: 65%;
}

#ddigmknmtw .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#ddigmknmtw .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#ddigmknmtw .gt_indent_1 {
  text-indent: 5px;
}

#ddigmknmtw .gt_indent_2 {
  text-indent: 10px;
}

#ddigmknmtw .gt_indent_3 {
  text-indent: 15px;
}

#ddigmknmtw .gt_indent_4 {
  text-indent: 20px;
}

#ddigmknmtw .gt_indent_5 {
  text-indent: 25px;
}

#ddigmknmtw .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#ddigmknmtw div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" style="table-layout: fixed;; width: 0px" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <colgroup>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
  </colgroup>
  <thead>
    <tr class="gt_heading">
      <td colspan="4" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipTeXN0ZW0gQWNjdXJhY3kgUmVzdWx0cyBHcm91cCBieSBSZWZlcmVuY2UgTGV2ZWwqKg=="><div class='gt_from_md'><p><strong>System Accuracy Results Group by Reference Level</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 15% / 15 mg/dL [0.8 mmol/L]">Within ± 15% / 15 mg/dL [0.8 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 20% / 20 mg/dL [1.1 mmol/L]">Within ± 20% / 20 mg/dL [1.1 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 40% / 40 mg/dL [2.2 mmol/L]">Within ± 40% / 40 mg/dL [2.2 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Outside ± 40%/ 40 mg/dL [2.2 mmol/L]">Outside ± 40%/ 40 mg/dL [2.2 mmol/L]</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr class="gt_group_heading_row">
      <th colspan="4" class="gt_group_heading" scope="colgroup" id="&amp;lt;70 mg/dL">&lt;70 mg/dL</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">12/45 (26.7%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">18/45 (40%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">33/45 (73.3%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">12/45 (26.7%)</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="4" class="gt_group_heading" scope="colgroup" id="&amp;gt;=70 mg/dL">&gt;=70 mg/dL</th>
    </tr>
    <tr class="gt_row_group_first"><td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">872/2715 (32.1%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">1156/2715 (42.6%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">2009/2715 (74%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">706/2715 (26%)</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="4" class="gt_group_heading" scope="colgroup" id="Overall">Overall</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">884/2760 (32%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">1174/2760 (42.5%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">2042/2760 (74%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">718/2760 (26%)</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell .column-page}
::: {.cell-output-display}


```{=html}
<div id="aoklfycaff" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#aoklfycaff table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#aoklfycaff thead, #aoklfycaff tbody, #aoklfycaff tfoot, #aoklfycaff tr, #aoklfycaff td, #aoklfycaff th {
  border-style: none;
}

#aoklfycaff p {
  margin: 0;
  padding: 0;
}

#aoklfycaff .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#aoklfycaff .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#aoklfycaff .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#aoklfycaff .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#aoklfycaff .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#aoklfycaff .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#aoklfycaff .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#aoklfycaff .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#aoklfycaff .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#aoklfycaff .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#aoklfycaff .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#aoklfycaff .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#aoklfycaff .gt_spanner_row {
  border-bottom-style: hidden;
}

#aoklfycaff .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#aoklfycaff .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#aoklfycaff .gt_from_md > :first-child {
  margin-top: 0;
}

#aoklfycaff .gt_from_md > :last-child {
  margin-bottom: 0;
}

#aoklfycaff .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#aoklfycaff .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#aoklfycaff .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#aoklfycaff .gt_row_group_first td {
  border-top-width: 2px;
}

#aoklfycaff .gt_row_group_first th {
  border-top-width: 2px;
}

#aoklfycaff .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#aoklfycaff .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#aoklfycaff .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#aoklfycaff .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#aoklfycaff .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#aoklfycaff .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#aoklfycaff .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#aoklfycaff .gt_striped {
  background-color: #EDF7FC;
}

#aoklfycaff .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#aoklfycaff .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#aoklfycaff .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#aoklfycaff .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#aoklfycaff .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#aoklfycaff .gt_left {
  text-align: left;
}

#aoklfycaff .gt_center {
  text-align: center;
}

#aoklfycaff .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#aoklfycaff .gt_font_normal {
  font-weight: normal;
}

#aoklfycaff .gt_font_bold {
  font-weight: bold;
}

#aoklfycaff .gt_font_italic {
  font-style: italic;
}

#aoklfycaff .gt_super {
  font-size: 65%;
}

#aoklfycaff .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#aoklfycaff .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#aoklfycaff .gt_indent_1 {
  text-indent: 5px;
}

#aoklfycaff .gt_indent_2 {
  text-indent: 10px;
}

#aoklfycaff .gt_indent_3 {
  text-indent: 15px;
}

#aoklfycaff .gt_indent_4 {
  text-indent: 20px;
}

#aoklfycaff .gt_indent_5 {
  text-indent: 25px;
}

#aoklfycaff .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#aoklfycaff div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" style="table-layout: fixed;; width: 0px" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <colgroup>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
  </colgroup>
  <thead>
    <tr class="gt_heading">
      <td colspan="5" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipTeXN0ZW0gQWNjdXJhY3kgUmVzdWx0cyBHcm91cCBieSBSZWZlcmVuY2UgR2x1Y29zZSBMZXZlbCoq"><div class='gt_from_md'><p><strong>System Accuracy Results Group by Reference Glucose Level</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Glucose Level(mg/dL) [mmol/L]">Glucose Level(mg/dL) [mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 15% / 15 mg/dL [0.8 mmol/L]">Within ± 15% / 15 mg/dL [0.8 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 20% / 20 mg/dL [1.1 mmol/L]">Within ± 20% / 20 mg/dL [1.1 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 40% / 40 mg/dL [2.2 mmol/L]">Within ± 40% / 40 mg/dL [2.2 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Outside ± 40%/ 40 mg/dL [2.2 mmol/L]">Outside ± 40%/ 40 mg/dL [2.2 mmol/L]</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr class="gt_group_heading_row">
      <th colspan="5" class="gt_group_heading" scope="colgroup" id="&amp;lt;70 mg/dL">&lt;70 mg/dL</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="<70 mg/dL  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center">&lt;54 [3.0]</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">2/8 (25%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">2/8 (25%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">7/8 (87.5%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">1/8 (12.5%)</td></tr>
    <tr><td headers="<70 mg/dL  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center gt_striped">54 to 69 [3.0-3.8]</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">10/37 (27%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">16/37 (43.2%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">26/37 (70.3%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">11/37 (29.7%)</td></tr>
    <tr><td headers="<70 mg/dL  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center">70 to 180 [3.9-10.0]</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">0/0 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">0/0 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/0 (0%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/0 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center gt_striped">181 to 250 [10.0-13.9]</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/0 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">0/0 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">0/0 (0%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">0/0 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center">&gt;250 [13.9]</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">0/0 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">0/0 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/0 (0%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/0 (0%)</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="5" class="gt_group_heading" scope="colgroup" id="&amp;gt;=70 mg/dL">&gt;=70 mg/dL</th>
    </tr>
    <tr class="gt_row_group_first"><td headers=">=70 mg/dL  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center gt_striped">&lt;54 [3.0]</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/0 (0%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">0/0 (0%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">0/0 (0%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">0/0 (0%)</td></tr>
    <tr><td headers=">=70 mg/dL  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center">54 to 69 [3.0-3.8]</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">0/0 (0%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">0/0 (0%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/0 (0%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/0 (0%)</td></tr>
    <tr><td headers=">=70 mg/dL  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center gt_striped">70 to 180 [3.9-10.0]</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">545/1911 (28.5%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">731/1911 (38.3%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">1318/1911 (69%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">593/1911 (31%)</td></tr>
    <tr><td headers=">=70 mg/dL  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center">181 to 250 [10.0-13.9]</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">201/509 (39.5%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">264/509 (51.9%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">427/509 (83.9%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">82/509 (16.1%)</td></tr>
    <tr><td headers=">=70 mg/dL  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center gt_striped">&gt;250 [13.9]</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">126/295 (42.7%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">161/295 (54.6%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">264/295 (89.5%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">31/295 (10.5%)</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="5" class="gt_group_heading" scope="colgroup" id="Overall">Overall</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="Overall  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center">&lt;54 [3.0]</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">2/8 (25%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">2/8 (25%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">7/8 (87.5%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">1/8 (12.5%)</td></tr>
    <tr><td headers="Overall  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center gt_striped">54 to 69 [3.0-3.8]</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">10/37 (27%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">16/37 (43.2%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">26/37 (70.3%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">11/37 (29.7%)</td></tr>
    <tr><td headers="Overall  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center">70 to 180 [3.9-10.0]</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">545/1911 (28.5%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">731/1911 (38.3%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">1318/1911 (69%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">593/1911 (31%)</td></tr>
    <tr><td headers="Overall  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center gt_striped">181 to 250 [10.0-13.9]</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">201/509 (39.5%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">264/509 (51.9%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">427/509 (83.9%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">82/509 (16.1%)</td></tr>
    <tr><td headers="Overall  Glucose Level(mg/dL) [mmol/L]" class="gt_row gt_center">&gt;250 [13.9]</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">126/295 (42.7%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">161/295 (54.6%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">264/295 (89.5%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">31/295 (10.5%)</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell .column-page}
::: {.cell-output-display}


```{=html}
<div id="kehafxtzer" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#kehafxtzer table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#kehafxtzer thead, #kehafxtzer tbody, #kehafxtzer tfoot, #kehafxtzer tr, #kehafxtzer td, #kehafxtzer th {
  border-style: none;
}

#kehafxtzer p {
  margin: 0;
  padding: 0;
}

#kehafxtzer .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#kehafxtzer .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#kehafxtzer .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#kehafxtzer .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#kehafxtzer .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#kehafxtzer .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#kehafxtzer .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#kehafxtzer .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#kehafxtzer .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#kehafxtzer .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#kehafxtzer .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#kehafxtzer .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#kehafxtzer .gt_spanner_row {
  border-bottom-style: hidden;
}

#kehafxtzer .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#kehafxtzer .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#kehafxtzer .gt_from_md > :first-child {
  margin-top: 0;
}

#kehafxtzer .gt_from_md > :last-child {
  margin-bottom: 0;
}

#kehafxtzer .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#kehafxtzer .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#kehafxtzer .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#kehafxtzer .gt_row_group_first td {
  border-top-width: 2px;
}

#kehafxtzer .gt_row_group_first th {
  border-top-width: 2px;
}

#kehafxtzer .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#kehafxtzer .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#kehafxtzer .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#kehafxtzer .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#kehafxtzer .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#kehafxtzer .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#kehafxtzer .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#kehafxtzer .gt_striped {
  background-color: #EDF7FC;
}

#kehafxtzer .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#kehafxtzer .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#kehafxtzer .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#kehafxtzer .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#kehafxtzer .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#kehafxtzer .gt_left {
  text-align: left;
}

#kehafxtzer .gt_center {
  text-align: center;
}

#kehafxtzer .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#kehafxtzer .gt_font_normal {
  font-weight: normal;
}

#kehafxtzer .gt_font_bold {
  font-weight: bold;
}

#kehafxtzer .gt_font_italic {
  font-style: italic;
}

#kehafxtzer .gt_super {
  font-size: 65%;
}

#kehafxtzer .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#kehafxtzer .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#kehafxtzer .gt_indent_1 {
  text-indent: 5px;
}

#kehafxtzer .gt_indent_2 {
  text-indent: 10px;
}

#kehafxtzer .gt_indent_3 {
  text-indent: 15px;
}

#kehafxtzer .gt_indent_4 {
  text-indent: 20px;
}

#kehafxtzer .gt_indent_5 {
  text-indent: 25px;
}

#kehafxtzer .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#kehafxtzer div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" style="table-layout: fixed;; width: 0px" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <colgroup>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
  </colgroup>
  <thead>
    <tr class="gt_heading">
      <td colspan="5" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipTeXN0ZW0gQWNjdXJhY3kgUmVzdWx0cyBHcm91cCBieSBXZWFyIFBlcmlvZCoq"><div class='gt_from_md'><p><strong>System Accuracy Results Group by Wear Period</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Wear Period">Wear Period</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 15% / 15 mg/dL [0.8 mmol/L]">Within ± 15% / 15 mg/dL [0.8 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 20% / 20 mg/dL [1.1 mmol/L]">Within ± 20% / 20 mg/dL [1.1 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 40% / 40 mg/dL [2.2 mmol/L]">Within ± 40% / 40 mg/dL [2.2 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Outside ± 40%/ 40 mg/dL [2.2 mmol/L]">Outside ± 40%/ 40 mg/dL [2.2 mmol/L]</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr class="gt_group_heading_row">
      <th colspan="5" class="gt_group_heading" scope="colgroup" id="&amp;lt;70 mg/dL">&lt;70 mg/dL</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="<70 mg/dL  Wear Period" class="gt_row gt_center">Beginning</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">0/12 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">1/12 (8.3%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">7/12 (58.3%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">5/12 (41.7%)</td></tr>
    <tr><td headers="<70 mg/dL  Wear Period" class="gt_row gt_center gt_striped">Early Middle</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">2/17 (11.8%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">3/17 (17.6%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">10/17 (58.8%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">7/17 (41.2%)</td></tr>
    <tr><td headers="<70 mg/dL  Wear Period" class="gt_row gt_center">Late Middle</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">9/12 (75%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">11/12 (91.7%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">12/12 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/12 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Wear Period" class="gt_row gt_center gt_striped">End</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">1/4 (25%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">3/4 (75%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">4/4 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">0/4 (0%)</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="5" class="gt_group_heading" scope="colgroup" id="&amp;gt;=70 mg/dL">&gt;=70 mg/dL</th>
    </tr>
    <tr class="gt_row_group_first"><td headers=">=70 mg/dL  Wear Period" class="gt_row gt_center">Beginning</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">187/687 (27.2%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">252/687 (36.7%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">469/687 (68.3%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">218/687 (31.7%)</td></tr>
    <tr><td headers=">=70 mg/dL  Wear Period" class="gt_row gt_center gt_striped">Early Middle</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">296/993 (29.8%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">398/993 (40.1%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">740/993 (74.5%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">253/993 (25.5%)</td></tr>
    <tr><td headers=">=70 mg/dL  Wear Period" class="gt_row gt_center">Late Middle</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">260/703 (37%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">352/703 (50.1%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">547/703 (77.8%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">156/703 (22.2%)</td></tr>
    <tr><td headers=">=70 mg/dL  Wear Period" class="gt_row gt_center gt_striped">End</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">129/332 (38.9%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">154/332 (46.4%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">253/332 (76.2%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">79/332 (23.8%)</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="5" class="gt_group_heading" scope="colgroup" id="Overall">Overall</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="Overall  Wear Period" class="gt_row gt_center">Beginning</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">187/699 (26.8%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">253/699 (36.2%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">476/699 (68.1%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">223/699 (31.9%)</td></tr>
    <tr><td headers="Overall  Wear Period" class="gt_row gt_center gt_striped">Early Middle</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">298/1010 (29.5%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">401/1010 (39.7%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">750/1010 (74.3%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">260/1010 (25.7%)</td></tr>
    <tr><td headers="Overall  Wear Period" class="gt_row gt_center">Late Middle</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">269/715 (37.6%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">363/715 (50.8%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">559/715 (78.2%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">156/715 (21.8%)</td></tr>
    <tr><td headers="Overall  Wear Period" class="gt_row gt_center gt_striped">End</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">130/336 (38.7%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">157/336 (46.7%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">257/336 (76.5%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">79/336 (23.5%)</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell .column-page}
::: {.cell-output-display}


```{=html}
<div id="zzilbzmnbg" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#zzilbzmnbg table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#zzilbzmnbg thead, #zzilbzmnbg tbody, #zzilbzmnbg tfoot, #zzilbzmnbg tr, #zzilbzmnbg td, #zzilbzmnbg th {
  border-style: none;
}

#zzilbzmnbg p {
  margin: 0;
  padding: 0;
}

#zzilbzmnbg .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#zzilbzmnbg .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#zzilbzmnbg .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#zzilbzmnbg .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#zzilbzmnbg .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#zzilbzmnbg .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#zzilbzmnbg .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#zzilbzmnbg .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#zzilbzmnbg .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#zzilbzmnbg .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#zzilbzmnbg .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#zzilbzmnbg .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#zzilbzmnbg .gt_spanner_row {
  border-bottom-style: hidden;
}

#zzilbzmnbg .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#zzilbzmnbg .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#zzilbzmnbg .gt_from_md > :first-child {
  margin-top: 0;
}

#zzilbzmnbg .gt_from_md > :last-child {
  margin-bottom: 0;
}

#zzilbzmnbg .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#zzilbzmnbg .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#zzilbzmnbg .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#zzilbzmnbg .gt_row_group_first td {
  border-top-width: 2px;
}

#zzilbzmnbg .gt_row_group_first th {
  border-top-width: 2px;
}

#zzilbzmnbg .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#zzilbzmnbg .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#zzilbzmnbg .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#zzilbzmnbg .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#zzilbzmnbg .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#zzilbzmnbg .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#zzilbzmnbg .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#zzilbzmnbg .gt_striped {
  background-color: #EDF7FC;
}

#zzilbzmnbg .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#zzilbzmnbg .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#zzilbzmnbg .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#zzilbzmnbg .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#zzilbzmnbg .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#zzilbzmnbg .gt_left {
  text-align: left;
}

#zzilbzmnbg .gt_center {
  text-align: center;
}

#zzilbzmnbg .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#zzilbzmnbg .gt_font_normal {
  font-weight: normal;
}

#zzilbzmnbg .gt_font_bold {
  font-weight: bold;
}

#zzilbzmnbg .gt_font_italic {
  font-style: italic;
}

#zzilbzmnbg .gt_super {
  font-size: 65%;
}

#zzilbzmnbg .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#zzilbzmnbg .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#zzilbzmnbg .gt_indent_1 {
  text-indent: 5px;
}

#zzilbzmnbg .gt_indent_2 {
  text-indent: 10px;
}

#zzilbzmnbg .gt_indent_3 {
  text-indent: 15px;
}

#zzilbzmnbg .gt_indent_4 {
  text-indent: 20px;
}

#zzilbzmnbg .gt_indent_5 {
  text-indent: 25px;
}

#zzilbzmnbg .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#zzilbzmnbg div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" style="table-layout: fixed;; width: 0px" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <colgroup>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
  </colgroup>
  <thead>
    <tr class="gt_heading">
      <td colspan="5" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipTeXN0ZW0gQWNjdXJhY3kgUmVzdWx0cyBHcm91cCBieSBTZW5zb3IgV2Vhcioq"><div class='gt_from_md'><p><strong>System Accuracy Results Group by Sensor Wear</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Day">Day</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 15% / 15 mg/dL [0.8 mmol/L]">Within ± 15% / 15 mg/dL [0.8 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 20% / 20 mg/dL [1.1 mmol/L]">Within ± 20% / 20 mg/dL [1.1 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 40% / 40 mg/dL [2.2 mmol/L]">Within ± 40% / 40 mg/dL [2.2 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Outside ± 40%/ 40 mg/dL [2.2 mmol/L]">Outside ± 40%/ 40 mg/dL [2.2 mmol/L]</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr class="gt_group_heading_row">
      <th colspan="5" class="gt_group_heading" scope="colgroup" id="&amp;lt;70 mg/dL">&lt;70 mg/dL</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="<70 mg/dL  Day" class="gt_row gt_center">1</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">0/4 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">0/4 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">1/4 (25%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">3/4 (75%)</td></tr>
    <tr><td headers="<70 mg/dL  Day" class="gt_row gt_center gt_striped">2</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/5 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">0/5 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">3/5 (60%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">2/5 (40%)</td></tr>
    <tr><td headers="<70 mg/dL  Day" class="gt_row gt_center">3</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">0/3 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">1/3 (33.3%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">3/3 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/3 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Day" class="gt_row gt_center gt_striped">4</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/4 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">0/4 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">1/4 (25%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">3/4 (75%)</td></tr>
    <tr><td headers="<70 mg/dL  Day" class="gt_row gt_center">5</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">0/3 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">0/3 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">1/3 (33.3%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">2/3 (66.7%)</td></tr>
    <tr><td headers="<70 mg/dL  Day" class="gt_row gt_center gt_striped">6</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">1/5 (20%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">1/5 (20%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">4/5 (80%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">1/5 (20%)</td></tr>
    <tr><td headers="<70 mg/dL  Day" class="gt_row gt_center">7</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">1/2 (50%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">1/2 (50%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">2/2 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/2 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Day" class="gt_row gt_center gt_striped">8</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/3 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">1/3 (33.3%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">2/3 (66.7%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">1/3 (33.3%)</td></tr>
    <tr><td headers="<70 mg/dL  Day" class="gt_row gt_center">9</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">2/2 (100%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">2/2 (100%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">2/2 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/2 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Day" class="gt_row gt_center gt_striped">10</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">4/6 (66.7%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">6/6 (100%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">6/6 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">0/6 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Day" class="gt_row gt_center">11</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">2/3 (66.7%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">2/3 (66.7%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">3/3 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/3 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Day" class="gt_row gt_center gt_striped">12</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">1/1 (100%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">1/1 (100%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">1/1 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">0/1 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Day" class="gt_row gt_center">13</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">1/2 (50%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">2/2 (100%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">2/2 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/2 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Day" class="gt_row gt_center gt_striped">14</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/2 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">1/2 (50%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">2/2 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">0/2 (0%)</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="5" class="gt_group_heading" scope="colgroup" id="&amp;gt;=70 mg/dL">&gt;=70 mg/dL</th>
    </tr>
    <tr class="gt_row_group_first"><td headers=">=70 mg/dL  Day" class="gt_row gt_center">1</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">80/241 (33.2%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">105/241 (43.6%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">184/241 (76.3%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">57/241 (23.7%)</td></tr>
    <tr><td headers=">=70 mg/dL  Day" class="gt_row gt_center gt_striped">2</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">55/233 (23.6%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">78/233 (33.5%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">155/233 (66.5%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">78/233 (33.5%)</td></tr>
    <tr><td headers=">=70 mg/dL  Day" class="gt_row gt_center">3</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">52/213 (24.4%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">69/213 (32.4%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">130/213 (61%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">83/213 (39%)</td></tr>
    <tr><td headers=">=70 mg/dL  Day" class="gt_row gt_center gt_striped">4</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">46/211 (21.8%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">65/211 (30.8%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">141/211 (66.8%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">70/211 (33.2%)</td></tr>
    <tr><td headers=">=70 mg/dL  Day" class="gt_row gt_center">5</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">53/192 (27.6%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">73/192 (38%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">143/192 (74.5%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">49/192 (25.5%)</td></tr>
    <tr><td headers=">=70 mg/dL  Day" class="gt_row gt_center gt_striped">6</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">64/199 (32.2%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">85/199 (42.7%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">150/199 (75.4%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">49/199 (24.6%)</td></tr>
    <tr><td headers=">=70 mg/dL  Day" class="gt_row gt_center">7</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">58/196 (29.6%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">76/196 (38.8%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">150/196 (76.5%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">46/196 (23.5%)</td></tr>
    <tr><td headers=">=70 mg/dL  Day" class="gt_row gt_center gt_striped">8</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">75/195 (38.5%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">99/195 (50.8%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">156/195 (80%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">39/195 (20%)</td></tr>
    <tr><td headers=">=70 mg/dL  Day" class="gt_row gt_center">9</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">63/189 (33.3%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">86/189 (45.5%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">144/189 (76.2%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">45/189 (23.8%)</td></tr>
    <tr><td headers=">=70 mg/dL  Day" class="gt_row gt_center gt_striped">10</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">72/176 (40.9%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">92/176 (52.3%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">138/176 (78.4%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">38/176 (21.6%)</td></tr>
    <tr><td headers=">=70 mg/dL  Day" class="gt_row gt_center">11</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">64/177 (36.2%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">94/177 (53.1%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">149/177 (84.2%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">28/177 (15.8%)</td></tr>
    <tr><td headers=">=70 mg/dL  Day" class="gt_row gt_center gt_striped">12</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">61/161 (37.9%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">80/161 (49.7%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">116/161 (72%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">45/161 (28%)</td></tr>
    <tr><td headers=">=70 mg/dL  Day" class="gt_row gt_center">13</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">75/176 (42.6%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">87/176 (49.4%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">138/176 (78.4%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">38/176 (21.6%)</td></tr>
    <tr><td headers=">=70 mg/dL  Day" class="gt_row gt_center gt_striped">14</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">54/156 (34.6%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">67/156 (42.9%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">115/156 (73.7%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">41/156 (26.3%)</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="5" class="gt_group_heading" scope="colgroup" id="Overall">Overall</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="Overall  Day" class="gt_row gt_center">1</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">80/245 (32.7%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">105/245 (42.9%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">185/245 (75.5%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">60/245 (24.5%)</td></tr>
    <tr><td headers="Overall  Day" class="gt_row gt_center gt_striped">2</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">55/238 (23.1%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">78/238 (32.8%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">158/238 (66.4%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">80/238 (33.6%)</td></tr>
    <tr><td headers="Overall  Day" class="gt_row gt_center">3</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">52/216 (24.1%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">70/216 (32.4%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">133/216 (61.6%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">83/216 (38.4%)</td></tr>
    <tr><td headers="Overall  Day" class="gt_row gt_center gt_striped">4</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">46/215 (21.4%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">65/215 (30.2%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">142/215 (66%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">73/215 (34%)</td></tr>
    <tr><td headers="Overall  Day" class="gt_row gt_center">5</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">53/195 (27.2%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">73/195 (37.4%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">144/195 (73.8%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">51/195 (26.2%)</td></tr>
    <tr><td headers="Overall  Day" class="gt_row gt_center gt_striped">6</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">65/204 (31.9%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">86/204 (42.2%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">154/204 (75.5%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">50/204 (24.5%)</td></tr>
    <tr><td headers="Overall  Day" class="gt_row gt_center">7</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">59/198 (29.8%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">77/198 (38.9%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">152/198 (76.8%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">46/198 (23.2%)</td></tr>
    <tr><td headers="Overall  Day" class="gt_row gt_center gt_striped">8</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">75/198 (37.9%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">100/198 (50.5%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">158/198 (79.8%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">40/198 (20.2%)</td></tr>
    <tr><td headers="Overall  Day" class="gt_row gt_center">9</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">65/191 (34%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">88/191 (46.1%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">146/191 (76.4%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">45/191 (23.6%)</td></tr>
    <tr><td headers="Overall  Day" class="gt_row gt_center gt_striped">10</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">76/182 (41.8%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">98/182 (53.8%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">144/182 (79.1%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">38/182 (20.9%)</td></tr>
    <tr><td headers="Overall  Day" class="gt_row gt_center">11</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">66/180 (36.7%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">96/180 (53.3%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">152/180 (84.4%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">28/180 (15.6%)</td></tr>
    <tr><td headers="Overall  Day" class="gt_row gt_center gt_striped">12</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">62/162 (38.3%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">81/162 (50%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">117/162 (72.2%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">45/162 (27.8%)</td></tr>
    <tr><td headers="Overall  Day" class="gt_row gt_center">13</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">76/178 (42.7%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">89/178 (50%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">140/178 (78.7%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">38/178 (21.3%)</td></tr>
    <tr><td headers="Overall  Day" class="gt_row gt_center gt_striped">14</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">54/158 (34.2%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">68/158 (43%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">117/158 (74.1%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">41/158 (25.9%)</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell .column-page}
::: {.cell-output-display}


```{=html}
<div id="zsgwftpniv" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#zsgwftpniv table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#zsgwftpniv thead, #zsgwftpniv tbody, #zsgwftpniv tfoot, #zsgwftpniv tr, #zsgwftpniv td, #zsgwftpniv th {
  border-style: none;
}

#zsgwftpniv p {
  margin: 0;
  padding: 0;
}

#zsgwftpniv .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#zsgwftpniv .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#zsgwftpniv .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#zsgwftpniv .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#zsgwftpniv .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#zsgwftpniv .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#zsgwftpniv .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#zsgwftpniv .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#zsgwftpniv .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#zsgwftpniv .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#zsgwftpniv .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#zsgwftpniv .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#zsgwftpniv .gt_spanner_row {
  border-bottom-style: hidden;
}

#zsgwftpniv .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#zsgwftpniv .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#zsgwftpniv .gt_from_md > :first-child {
  margin-top: 0;
}

#zsgwftpniv .gt_from_md > :last-child {
  margin-bottom: 0;
}

#zsgwftpniv .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#zsgwftpniv .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#zsgwftpniv .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#zsgwftpniv .gt_row_group_first td {
  border-top-width: 2px;
}

#zsgwftpniv .gt_row_group_first th {
  border-top-width: 2px;
}

#zsgwftpniv .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#zsgwftpniv .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#zsgwftpniv .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#zsgwftpniv .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#zsgwftpniv .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#zsgwftpniv .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#zsgwftpniv .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#zsgwftpniv .gt_striped {
  background-color: #EDF7FC;
}

#zsgwftpniv .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#zsgwftpniv .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#zsgwftpniv .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#zsgwftpniv .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#zsgwftpniv .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#zsgwftpniv .gt_left {
  text-align: left;
}

#zsgwftpniv .gt_center {
  text-align: center;
}

#zsgwftpniv .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#zsgwftpniv .gt_font_normal {
  font-weight: normal;
}

#zsgwftpniv .gt_font_bold {
  font-weight: bold;
}

#zsgwftpniv .gt_font_italic {
  font-style: italic;
}

#zsgwftpniv .gt_super {
  font-size: 65%;
}

#zsgwftpniv .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#zsgwftpniv .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#zsgwftpniv .gt_indent_1 {
  text-indent: 5px;
}

#zsgwftpniv .gt_indent_2 {
  text-indent: 10px;
}

#zsgwftpniv .gt_indent_3 {
  text-indent: 15px;
}

#zsgwftpniv .gt_indent_4 {
  text-indent: 20px;
}

#zsgwftpniv .gt_indent_5 {
  text-indent: 25px;
}

#zsgwftpniv .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#zsgwftpniv div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" style="table-layout: fixed;; width: 0px" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <colgroup>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
    <col style="width:200px;"/>
  </colgroup>
  <thead>
    <tr class="gt_heading">
      <td colspan="5" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipTeXN0ZW0gQWNjdXJhY3kgUmVzdWx0cyBHcm91cCBieSBTdWJqZWN0Kio="><div class='gt_from_md'><p><strong>System Accuracy Results Group by Subject</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Subject ID">Subject ID</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 15% / 15 mg/dL [0.8 mmol/L]">Within ± 15% / 15 mg/dL [0.8 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 20% / 20 mg/dL [1.1 mmol/L]">Within ± 20% / 20 mg/dL [1.1 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Within ± 40% / 40 mg/dL [2.2 mmol/L]">Within ± 40% / 40 mg/dL [2.2 mmol/L]</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Outside ± 40%/ 40 mg/dL [2.2 mmol/L]">Outside ± 40%/ 40 mg/dL [2.2 mmol/L]</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr class="gt_group_heading_row">
      <th colspan="5" class="gt_group_heading" scope="colgroup" id="&amp;lt;70 mg/dL">&lt;70 mg/dL</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="<70 mg/dL  Subject ID" class="gt_row gt_center">1170005</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">0/1 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">0/1 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/1 (0%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">1/1 (100%)</td></tr>
    <tr><td headers="<70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170012</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/2 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">0/2 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">1/2 (50%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">1/2 (50%)</td></tr>
    <tr><td headers="<70 mg/dL  Subject ID" class="gt_row gt_center">1170017</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">0/1 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">0/1 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/1 (0%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">1/1 (100%)</td></tr>
    <tr><td headers="<70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170020</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/1 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">0/1 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">1/1 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">0/1 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Subject ID" class="gt_row gt_center">1170021</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">1/7 (14.3%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">3/7 (42.9%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">3/7 (42.9%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">4/7 (57.1%)</td></tr>
    <tr><td headers="<70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170024</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">3/11 (27.3%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">3/11 (27.3%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">11/11 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">0/11 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Subject ID" class="gt_row gt_center">1170026</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">0/3 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">0/3 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/3 (0%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">3/3 (100%)</td></tr>
    <tr><td headers="<70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170028</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/1 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">0/1 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">1/1 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">0/1 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Subject ID" class="gt_row gt_center">1170029</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">0/1 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">0/1 (0%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/1 (0%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">1/1 (100%)</td></tr>
    <tr><td headers="<70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170033</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/1 (0%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">1/1 (100%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">1/1 (100%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">0/1 (0%)</td></tr>
    <tr><td headers="<70 mg/dL  Subject ID" class="gt_row gt_center">1170036</td>
<td headers="<70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">8/16 (50%)</td>
<td headers="<70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">11/16 (68.8%)</td>
<td headers="<70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">15/16 (93.8%)</td>
<td headers="<70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">1/16 (6.2%)</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="5" class="gt_group_heading" scope="colgroup" id="&amp;gt;=70 mg/dL">&gt;=70 mg/dL</th>
    </tr>
    <tr class="gt_row_group_first"><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170001</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">4/28 (14.3%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">7/28 (25%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">20/28 (71.4%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">8/28 (28.6%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170003</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">12/23 (52.2%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">16/23 (69.6%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">20/23 (87%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">3/23 (13%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170004</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">12/109 (11%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">17/109 (15.6%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">71/109 (65.1%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">38/109 (34.9%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170005</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">25/109 (22.9%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">40/109 (36.7%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">86/109 (78.9%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">23/109 (21.1%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170006</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">54/104 (51.9%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">62/104 (59.6%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">84/104 (80.8%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">20/104 (19.2%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170007</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">68/111 (61.3%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">84/111 (75.7%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">110/111 (99.1%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">1/111 (0.9%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170008</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">52/109 (47.7%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">71/109 (65.1%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">105/109 (96.3%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">4/109 (3.7%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170009</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">19/46 (41.3%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">24/46 (52.2%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">40/46 (87%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">6/46 (13%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170010</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">20/24 (83.3%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">20/24 (83.3%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">23/24 (95.8%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">1/24 (4.2%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170011</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">13/68 (19.1%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">18/68 (26.5%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">56/68 (82.4%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">12/68 (17.6%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170012</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">23/65 (35.4%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">34/65 (52.3%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">54/65 (83.1%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">11/65 (16.9%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170014</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">54/95 (56.8%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">73/95 (76.8%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">92/95 (96.8%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">3/95 (3.2%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170015</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">32/112 (28.6%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">42/112 (37.5%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">99/112 (88.4%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">13/112 (11.6%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170016</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">9/110 (8.2%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">11/110 (10%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">61/110 (55.5%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">49/110 (44.5%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170017</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">10/111 (9%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">18/111 (16.2%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">53/111 (47.7%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">58/111 (52.3%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170018</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">30/106 (28.3%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">39/106 (36.8%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">82/106 (77.4%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">24/106 (22.6%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170019</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">14/115 (12.2%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">25/115 (21.7%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">69/115 (60%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">46/115 (40%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170020</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">46/98 (46.9%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">55/98 (56.1%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">83/98 (84.7%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">15/98 (15.3%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170021</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">26/98 (26.5%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">34/98 (34.7%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">60/98 (61.2%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">38/98 (38.8%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170022</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">31/55 (56.4%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">47/55 (85.5%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">55/55 (100%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/55 (0%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170023</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">23/65 (35.4%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">35/65 (53.8%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">58/65 (89.2%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">7/65 (10.8%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170024</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">27/75 (36%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">33/75 (44%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">60/75 (80%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">15/75 (20%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170025</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/109 (0%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">0/109 (0%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">20/109 (18.3%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">89/109 (81.7%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170026</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">3/46 (6.5%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">4/46 (8.7%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">14/46 (30.4%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">32/46 (69.6%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170027</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">6/20 (30%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">8/20 (40%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">17/20 (85%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">3/20 (15%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170028</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">20/58 (34.5%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">34/58 (58.6%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">57/58 (98.3%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">1/58 (1.7%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170029</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">64/93 (68.8%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">77/93 (82.8%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">90/93 (96.8%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">3/93 (3.2%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170030</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">17/51 (33.3%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">31/51 (60.8%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">49/51 (96.1%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">2/51 (3.9%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170031</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/27 (0%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">0/27 (0%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">3/27 (11.1%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">24/27 (88.9%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170032</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">21/109 (19.3%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">29/109 (26.6%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">60/109 (55%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">49/109 (45%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170033</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">19/104 (18.3%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">28/104 (26.9%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">63/104 (60.6%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">41/104 (39.4%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170034</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">85/116 (73.3%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">104/116 (89.7%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">116/116 (100%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/116 (0%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center gt_striped">1170035</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">9/62 (14.5%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">11/62 (17.7%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">33/62 (53.2%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">29/62 (46.8%)</td></tr>
    <tr><td headers=">=70 mg/dL  Subject ID" class="gt_row gt_center">1170036</td>
<td headers=">=70 mg/dL  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">24/84 (28.6%)</td>
<td headers=">=70 mg/dL  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">25/84 (29.8%)</td>
<td headers=">=70 mg/dL  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">46/84 (54.8%)</td>
<td headers=">=70 mg/dL  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">38/84 (45.2%)</td></tr>
    <tr class="gt_group_heading_row">
      <th colspan="5" class="gt_group_heading" scope="colgroup" id="Overall">Overall</th>
    </tr>
    <tr class="gt_row_group_first"><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170001</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">4/28 (14.3%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">7/28 (25%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">20/28 (71.4%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">8/28 (28.6%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170003</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">12/23 (52.2%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">16/23 (69.6%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">20/23 (87%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">3/23 (13%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170004</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">12/109 (11%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">17/109 (15.6%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">71/109 (65.1%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">38/109 (34.9%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170005</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">25/110 (22.7%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">40/110 (36.4%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">86/110 (78.2%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">24/110 (21.8%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170006</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">54/104 (51.9%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">62/104 (59.6%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">84/104 (80.8%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">20/104 (19.2%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170007</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">68/111 (61.3%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">84/111 (75.7%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">110/111 (99.1%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">1/111 (0.9%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170008</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">52/109 (47.7%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">71/109 (65.1%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">105/109 (96.3%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">4/109 (3.7%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170009</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">19/46 (41.3%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">24/46 (52.2%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">40/46 (87%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">6/46 (13%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170010</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">20/24 (83.3%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">20/24 (83.3%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">23/24 (95.8%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">1/24 (4.2%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170011</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">13/68 (19.1%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">18/68 (26.5%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">56/68 (82.4%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">12/68 (17.6%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170012</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">23/67 (34.3%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">34/67 (50.7%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">55/67 (82.1%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">12/67 (17.9%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170014</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">54/95 (56.8%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">73/95 (76.8%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">92/95 (96.8%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">3/95 (3.2%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170015</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">32/112 (28.6%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">42/112 (37.5%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">99/112 (88.4%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">13/112 (11.6%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170016</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">9/110 (8.2%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">11/110 (10%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">61/110 (55.5%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">49/110 (44.5%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170017</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">10/112 (8.9%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">18/112 (16.1%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">53/112 (47.3%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">59/112 (52.7%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170018</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">30/106 (28.3%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">39/106 (36.8%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">82/106 (77.4%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">24/106 (22.6%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170019</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">14/115 (12.2%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">25/115 (21.7%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">69/115 (60%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">46/115 (40%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170020</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">46/99 (46.5%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">55/99 (55.6%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">84/99 (84.8%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">15/99 (15.2%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170021</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">27/105 (25.7%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">37/105 (35.2%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">63/105 (60%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">42/105 (40%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170022</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">31/55 (56.4%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">47/55 (85.5%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">55/55 (100%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/55 (0%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170023</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">23/65 (35.4%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">35/65 (53.8%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">58/65 (89.2%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">7/65 (10.8%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170024</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">30/86 (34.9%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">36/86 (41.9%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">71/86 (82.6%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">15/86 (17.4%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170025</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/109 (0%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">0/109 (0%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">20/109 (18.3%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">89/109 (81.7%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170026</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">3/49 (6.1%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">4/49 (8.2%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">14/49 (28.6%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">35/49 (71.4%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170027</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">6/20 (30%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">8/20 (40%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">17/20 (85%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">3/20 (15%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170028</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">20/59 (33.9%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">34/59 (57.6%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">58/59 (98.3%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">1/59 (1.7%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170029</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">64/94 (68.1%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">77/94 (81.9%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">90/94 (95.7%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">4/94 (4.3%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170030</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">17/51 (33.3%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">31/51 (60.8%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">49/51 (96.1%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">2/51 (3.9%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170031</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">0/27 (0%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">0/27 (0%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">3/27 (11.1%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">24/27 (88.9%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170032</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">21/109 (19.3%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">29/109 (26.6%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">60/109 (55%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">49/109 (45%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170033</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">19/105 (18.1%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">29/105 (27.6%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">64/105 (61%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">41/105 (39%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170034</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">85/116 (73.3%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">104/116 (89.7%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">116/116 (100%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">0/116 (0%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center gt_striped">1170035</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center gt_striped">9/62 (14.5%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center gt_striped">11/62 (17.7%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">33/62 (53.2%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center gt_striped">29/62 (46.8%)</td></tr>
    <tr><td headers="Overall  Subject ID" class="gt_row gt_center">1170036</td>
<td headers="Overall  Within ± 15% / 15 mg/dL [0.8 mmol/L]" class="gt_row gt_center">32/100 (32%)</td>
<td headers="Overall  Within ± 20% / 20 mg/dL [1.1 mmol/L]" class="gt_row gt_center">36/100 (36%)</td>
<td headers="Overall  Within ± 40% / 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">61/100 (61%)</td>
<td headers="Overall  Outside ± 40%/ 40 mg/dL [2.2 mmol/L]" class="gt_row gt_center">39/100 (39%)</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::



## Consensus Error Grid


::: {.cell}

:::

::: {.cell layout-align="center"}
::: {.cell-output-display}
![](ADC-US-RES-23241-SE03_files/figure-html/Error Grid Plot-1.png){fig-align='center' width=672}
:::
:::

::: {.cell}
::: {.cell-output-display}


```{=html}
<div id="uqdoblpnkb" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#uqdoblpnkb table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#uqdoblpnkb thead, #uqdoblpnkb tbody, #uqdoblpnkb tfoot, #uqdoblpnkb tr, #uqdoblpnkb td, #uqdoblpnkb th {
  border-style: none;
}

#uqdoblpnkb p {
  margin: 0;
  padding: 0;
}

#uqdoblpnkb .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#uqdoblpnkb .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#uqdoblpnkb .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#uqdoblpnkb .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#uqdoblpnkb .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#uqdoblpnkb .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#uqdoblpnkb .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#uqdoblpnkb .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#uqdoblpnkb .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#uqdoblpnkb .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#uqdoblpnkb .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#uqdoblpnkb .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#uqdoblpnkb .gt_spanner_row {
  border-bottom-style: hidden;
}

#uqdoblpnkb .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#uqdoblpnkb .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#uqdoblpnkb .gt_from_md > :first-child {
  margin-top: 0;
}

#uqdoblpnkb .gt_from_md > :last-child {
  margin-bottom: 0;
}

#uqdoblpnkb .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#uqdoblpnkb .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#uqdoblpnkb .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#uqdoblpnkb .gt_row_group_first td {
  border-top-width: 2px;
}

#uqdoblpnkb .gt_row_group_first th {
  border-top-width: 2px;
}

#uqdoblpnkb .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#uqdoblpnkb .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#uqdoblpnkb .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#uqdoblpnkb .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#uqdoblpnkb .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#uqdoblpnkb .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#uqdoblpnkb .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#uqdoblpnkb .gt_striped {
  background-color: #EDF7FC;
}

#uqdoblpnkb .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#uqdoblpnkb .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#uqdoblpnkb .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#uqdoblpnkb .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#uqdoblpnkb .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#uqdoblpnkb .gt_left {
  text-align: left;
}

#uqdoblpnkb .gt_center {
  text-align: center;
}

#uqdoblpnkb .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#uqdoblpnkb .gt_font_normal {
  font-weight: normal;
}

#uqdoblpnkb .gt_font_bold {
  font-weight: bold;
}

#uqdoblpnkb .gt_font_italic {
  font-style: italic;
}

#uqdoblpnkb .gt_super {
  font-size: 65%;
}

#uqdoblpnkb .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#uqdoblpnkb .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#uqdoblpnkb .gt_indent_1 {
  text-indent: 5px;
}

#uqdoblpnkb .gt_indent_2 {
  text-indent: 10px;
}

#uqdoblpnkb .gt_indent_3 {
  text-indent: 15px;
}

#uqdoblpnkb .gt_indent_4 {
  text-indent: 20px;
}

#uqdoblpnkb .gt_indent_5 {
  text-indent: 25px;
}

#uqdoblpnkb .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#uqdoblpnkb div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Zones">Zones</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="BG">BG</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Zones" class="gt_row gt_center">A</td>
<td headers="BG" class="gt_row gt_center">50.4% (1,392)</td></tr>
    <tr><td headers="Zones" class="gt_row gt_center gt_striped">B</td>
<td headers="BG" class="gt_row gt_center gt_striped">47.0% (1,297)</td></tr>
    <tr><td headers="Zones" class="gt_row gt_center">C</td>
<td headers="BG" class="gt_row gt_center">2.6%    (71)</td></tr>
    <tr><td headers="Zones" class="gt_row gt_center gt_striped">D</td>
<td headers="BG" class="gt_row gt_center gt_striped">0.0%     (0)</td></tr>
    <tr><td headers="Zones" class="gt_row gt_center">E</td>
<td headers="BG" class="gt_row gt_center">0.0%     (0)</td></tr>
    <tr><td headers="Zones" class="gt_row gt_center gt_striped">Total</td>
<td headers="BG" class="gt_row gt_center gt_striped">100.0% (2,760)</td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::



# **Appendix**

## Data Quality


::: {.cell .column-screen}
::: {.cell-output-display}


```{=html}
<div id="kdqzmcirip" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#kdqzmcirip table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#kdqzmcirip thead, #kdqzmcirip tbody, #kdqzmcirip tfoot, #kdqzmcirip tr, #kdqzmcirip td, #kdqzmcirip th {
  border-style: none;
}

#kdqzmcirip p {
  margin: 0;
  padding: 0;
}

#kdqzmcirip .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#kdqzmcirip .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#kdqzmcirip .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#kdqzmcirip .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#kdqzmcirip .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#kdqzmcirip .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#kdqzmcirip .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#kdqzmcirip .gt_col_heading {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#kdqzmcirip .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #0076BA;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#kdqzmcirip .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#kdqzmcirip .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#kdqzmcirip .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#kdqzmcirip .gt_spanner_row {
  border-bottom-style: hidden;
}

#kdqzmcirip .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#kdqzmcirip .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
  vertical-align: middle;
}

#kdqzmcirip .gt_from_md > :first-child {
  margin-top: 0;
}

#kdqzmcirip .gt_from_md > :last-child {
  margin-bottom: 0;
}

#kdqzmcirip .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: none;
  border-top-width: 1px;
  border-top-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D5D5D5;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D5D5D5;
  vertical-align: middle;
  overflow-x: hidden;
}

#kdqzmcirip .gt_stub {
  color: #333333;
  background-color: #89D3FE;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D5D5D5;
  padding-left: 5px;
  padding-right: 5px;
}

#kdqzmcirip .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#kdqzmcirip .gt_row_group_first td {
  border-top-width: 2px;
}

#kdqzmcirip .gt_row_group_first th {
  border-top-width: 2px;
}

#kdqzmcirip .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#kdqzmcirip .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #5F5F5F;
}

#kdqzmcirip .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#kdqzmcirip .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#kdqzmcirip .gt_grand_summary_row {
  color: #333333;
  background-color: #D5D5D5;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#kdqzmcirip .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #5F5F5F;
}

#kdqzmcirip .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #5F5F5F;
}

#kdqzmcirip .gt_striped {
  background-color: #EDF7FC;
}

#kdqzmcirip .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #5F5F5F;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #5F5F5F;
}

#kdqzmcirip .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#kdqzmcirip .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#kdqzmcirip .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#kdqzmcirip .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#kdqzmcirip .gt_left {
  text-align: left;
}

#kdqzmcirip .gt_center {
  text-align: center;
}

#kdqzmcirip .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#kdqzmcirip .gt_font_normal {
  font-weight: normal;
}

#kdqzmcirip .gt_font_bold {
  font-weight: bold;
}

#kdqzmcirip .gt_font_italic {
  font-style: italic;
}

#kdqzmcirip .gt_super {
  font-size: 65%;
}

#kdqzmcirip .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#kdqzmcirip .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#kdqzmcirip .gt_indent_1 {
  text-indent: 5px;
}

#kdqzmcirip .gt_indent_2 {
  text-indent: 10px;
}

#kdqzmcirip .gt_indent_3 {
  text-indent: 15px;
}

#kdqzmcirip .gt_indent_4 {
  text-indent: 20px;
}

#kdqzmcirip .gt_indent_5 {
  text-indent: 25px;
}

#kdqzmcirip .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#kdqzmcirip div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="10" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><div data-qmd-base64="KipTdW1tYXJ5IFRhYmxlIGZvciBEYXRhIFF1YWxpdHkqKg=="><div class='gt_from_md'><p><strong>Summary Table for Data Quality</strong></p>
</div></div></td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Subject ID">Subject ID</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Condition ID">Condition ID</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Sensor Serial Number">Sensor Serial Number</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="No.Glucose">No.Glucose</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Start Test Time">Start Test Time</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="End Test Time">End Test Time</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="DUSEQ01">DUSEQ01</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Application Date and Time">Application Date and Time</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Removal Date and Time">Removal Date and Time</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="Message from DIR">Message from DIR</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Subject ID" class="gt_row gt_center">1170001 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170001/1170001_RAB_SN4230002369_2024-03-25 123321.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002369</td>
<td headers="No.Glucose" class="gt_row gt_center">1487</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-03-25 13:36:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-03-28 15:54:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-03-25 12:38:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-03-28 16:00:00</td>
<td headers="Message from DIR" class="gt_row gt_center">Sensor fell off subject while changing clothes</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170002 <br /></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002504</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped"><br /></td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped"><br /></td>
<td headers="End Test Time" class="gt_row gt_center gt_striped"><br /></td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-03-25 13:43:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped"><br /></td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped">Subject has not returned to the clinic and more than likely won't, all devices are lost</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170003 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170003/1170003_RAB_SN4230002183_2024-02-24 100053.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002183</td>
<td headers="No.Glucose" class="gt_row gt_center">6719</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-03-26 12:57:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-09 12:51:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-03-26 11:57:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-09 13:12:00</td>
<td headers="Message from DIR" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170004 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170004/1170004_RAB_SN4230002188_2024-02-29 010322.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002188</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">6699</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-03-26 14:11:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-09 14:17:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-03-26 13:11:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-09 13:11:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170005 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170005/1170005_RAB_SN4230002482_2024-02-28 014844.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002482</td>
<td headers="No.Glucose" class="gt_row gt_center">6649</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-03-27 10:42:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-10 11:09:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-03-27 09:42:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-10 10:06:00</td>
<td headers="Message from DIR" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170006 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170006/1170006_RAB_SN4230002209_2024-02-26 114726.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002209</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">6719</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-03-27 10:40:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-10 11:34:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-03-27 09:40:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-10 15:50:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170007 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170007/1170007_LAB_SN4230002515_2024-02-26 084456.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002515</td>
<td headers="No.Glucose" class="gt_row gt_center">6706</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-03-28 11:52:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-11 12:07:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-03-28 10:52:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-11 10:55:00</td>
<td headers="Message from DIR" class="gt_row gt_center">Subject noticed the time &amp; date wrong on the study phone, which was set to 26feb2024 at 13:53. Subject called site staff who helped connect phone to wi-fi, which corrected the date and time on the phone Subject called to inform site staff that sensor was disconnected, sensor immediately reconnected when call was transferred to site staff.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170008 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170008/1170008_LAB_SN4230002393_2024-02-24 231758.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002393</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">6711</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-03-28 13:09:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-11 12:39:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-03-28 12:09:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-11 12:29:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped">Subject called to inform site staff that study-provided phone had a different time than the yuwell app. Resolved when connected to wi-fi.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170009 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170009/1170009_LAB_SN4230002477_2024-02-28 160821.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002477</td>
<td headers="No.Glucose" class="gt_row gt_center">6716</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-03-28 14:50:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-11 15:35:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-03-28 13:50:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-11 14:32:00</td>
<td headers="Message from DIR" class="gt_row gt_center">Water got spilled on the reader and now it will not work</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170010 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170010/1170010_LAB_SN4230002181_2024-02-19 152707.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002181</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">1181</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-03-29 09:51:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-03-31 20:51:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-03-29 08:51:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-03-31 20:51:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped">Subject stated he woke up and noticed his sensor was missing. Sensor only gave data for 3 days (29mar2024, 30mar2024, and 31mar2024) per the anytime app data; this suggests the sensor came off on 31mar2024 at 20:51 (time corrected for incorrect phone time).</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170011 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170011/1170011_LAB_SN4230002519_2024-02-28 100138.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002519</td>
<td headers="No.Glucose" class="gt_row gt_center">6451</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-03-29 12:41:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-12 00:11:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-03-29 11:41:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-12 09:00:00</td>
<td headers="Message from DIR" class="gt_row gt_center">Subject noticed sensor fell off after changing clothing.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170012 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170012/1170012_LAB_SN4230002514_2024-03-29 133827.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002514</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">6696</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-03-29 14:41:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-12 13:26:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-03-29 13:40:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-12 13:08:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped">Meter would not recognize blood sample at enrollment visit when fingerstick blood was presented despite 2 attempts.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170013 <span style="white-space: pre;"><a href="1170013_SN4230002215_RAB_716.csv" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002215</td>
<td headers="No.Glucose" class="gt_row gt_center">6719</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-04-01 10:32:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-15 10:26:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-04-01 09:33:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-16 10:50:00</td>
<td headers="Message from DIR" class="gt_row gt_center">Anytime app repeatedly crashed while trying to compile and share data file. Was not able to retrieve anytime app data file for upload.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170014 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170014/1170014_RAB_SN4230002202_2024-04-01 103215.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002202</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">6711</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-04-01 11:35:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-15 11:05:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-04-01 10:37:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-15 11:00:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped">Subject wrote: "when i woke up, i did fingerstick and checked the app. "Sensor signal error" displayed in app with no readings for several hours in the graph. Device was still paired properly and adhesive for application has not lifted. Subject wrote: "in periodic checking the app, i noticed there are "dead" spots in the data with no message alert on the iphone. I checked and the sensor was still paired, just no data about current glucose displayed. It picked back up and started reading again on its own. 4/15/24 7:00am *sensor signal error*"</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170015 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170015/1170015_RAB_SN4230002388_2024-04-01 122708.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002388</td>
<td headers="No.Glucose" class="gt_row gt_center">859</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-04-01 13:30:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-03 08:24:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-04-01 12:25:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-15 12:35:00</td>
<td headers="Message from DIR" class="gt_row gt_center">Subject called clinic to let us know study app was prompting her to login. Discovered subject had accidentally logged themselves out of the app, and using the logins provided by study monitor were able to get this subject logged back in and working properly.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170015 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170015/1170015_RAB_SN4230002388_2024-04-03 082528.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002388</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">5847</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-04-03 08:28:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-15 12:46:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-04-01 12:25:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-15 12:35:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped">Subject called clinic to let us know study app was prompting her to login. Discovered subject had accidentally logged themselves out of the app, and using the logins provided by study monitor were able to get this subject logged back in and working properly.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170016 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170016/1170016_RAB_SN4230002203-2024-04-01 133615.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002203</td>
<td headers="No.Glucose" class="gt_row gt_center">391</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-04-01 14:39:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-02 10:09:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-04-01 12:35:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-15 12:43:00</td>
<td headers="Message from DIR" class="gt_row gt_center">Yuwell app was prompting subject to login with username and password, despite no subject login needed for this study.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170016 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170016/1170016_RAB_SN4230002203-2024-04-02 101551.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002203</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">6295</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-04-02 10:18:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-15 13:00:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-04-01 12:35:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-15 12:43:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped">Yuwell app was prompting subject to login with username and password, despite no subject login needed for this study.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170017 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170017/1170017_RAB_SN4230002198_2024-04-02 093753.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002198</td>
<td headers="No.Glucose" class="gt_row gt_center">6699</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-04-02 10:40:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-16 10:28:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-04-02 09:40:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-16 07:30:00</td>
<td headers="Message from DIR" class="gt_row gt_center">Subject was in shower and sensor fell off.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170018 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170018/1170018_RAB_SN4230002189_2024-04-02 103523.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002189</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">6709</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-04-02 11:38:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-16 11:02:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-04-02 10:37:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-16 10:54:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170019 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170019/1170019_LAB_SN4230002506_2024-04-02 132228.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002506</td>
<td headers="No.Glucose" class="gt_row gt_center">6698</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-04-02 14:31:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-16 13:22:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-04-02 13:19:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-16 13:20:00</td>
<td headers="Message from DIR" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170020 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170020/1170020_LAB_SN4230002361_2024-04-02 140155.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002361</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">6696</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-04-02 15:04:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-16 13:49:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-04-02 14:00:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-16 13:45:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170021 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170021/1170021_LAB_SN4230002370_2024-04-03 100037.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002370</td>
<td headers="No.Glucose" class="gt_row gt_center">6705</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-04-03 11:03:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-17 10:15:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-04-03 10:02:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-17 10:11:00</td>
<td headers="Message from DIR" class="gt_row gt_center">Subject stated app was frequently disconnecting from sensor, but immediately re-pairing.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170022 <span style="white-space: pre;"><a href="1170022_SN4230002216_LAB_205.csv" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002216</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">5107</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-04-03 14:58:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-15 05:55:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-04-03 14:00:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-14 13:00:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped">Anytime app repeatedly crashes while trying to compile and share data file. Was not able to retrieve anytime app data file for upload. Subject was at work moving luggage at airport. One of the bags rubbed on abdomen while lifting and peeled sensor off.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170023 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170023/1170023_LAB_SN4230002218-2024-04-03 135526.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002218</td>
<td headers="No.Glucose" class="gt_row gt_center">6714</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-04-03 14:58:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-17 14:37:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-04-03 13:53:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-17 14:10:00</td>
<td headers="Message from DIR" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170024 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170024/1170024_LAB_SN4230002363_2024-04-04 092255.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002363</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">6703</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-04-04 10:25:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-18 10:19:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-04-04 09:25:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-18 12:20:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170025 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170025/1170025_RAB_SN4230002359_2024-04-04 092933.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002359</td>
<td headers="No.Glucose" class="gt_row gt_center">6712</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-04-04 10:32:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-18 10:05:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-04-04 09:31:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-18 10:01:00</td>
<td headers="Message from DIR" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170026 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170026/1170026_RAB_SN4230002385_2024-04-04 135731.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002385</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">3060</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-04-04 15:00:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-10 23:57:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-04-04 13:59:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-18 14:07:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170027 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170027/1170027_RAB_SN4230002374_2024-04-04 135926.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002374</td>
<td headers="No.Glucose" class="gt_row gt_center">1063</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-04-04 15:02:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-06 20:08:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">2</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-04-04 14:11:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-06 20:50:00</td>
<td headers="Message from DIR" class="gt_row gt_center">Sensor adhesive not working properly and sensor looked like it was about to fall off. Sensor came off</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170028 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170028/1170028_RAB_SN4230002383_2024-04-05 093355.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002383</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">6701</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-04-05 10:36:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-19 09:36:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-04-05 09:32:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-19 09:30:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170029 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170029/1170029_RAB_SN4230002191_2024-04-05 093307.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002191</td>
<td headers="No.Glucose" class="gt_row gt_center">6709</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-04-05 10:36:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-19 10:00:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-04-05 09:36:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-19 09:56:00</td>
<td headers="Message from DIR" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170030 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170030/1170030_RAB_SN4230002366_2024-04-05 094935.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">RAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002366</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">4422</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-04-05 10:52:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-14 15:55:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-04-05 09:53:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-14 16:30:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped">Sensor peeled off when subject was putting on a shirt at home.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170031 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170031/1170031_LAB_SN4230002373_2024-04-05 133335.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002373</td>
<td headers="No.Glucose" class="gt_row gt_center">2269</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-04-05 14:36:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-10 08:15:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-04-05 13:34:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-09 12:09:00</td>
<td headers="Message from DIR" class="gt_row gt_center">Subject got up from the dining table and the sensor got caught and fell off.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170032 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170032/1170032_LAB_SN4230002206_2024-04-08 133742.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002206</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">6719</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-04-08 14:40:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-22 14:34:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-04-08 13:40:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-22 14:45:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170033 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170033/1170033_LAB_SN4230002365_2024-04-08 140955.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002365</td>
<td headers="No.Glucose" class="gt_row gt_center">6699</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-04-08 15:12:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-22 14:06:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-04-08 14:13:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-22 14:01:00</td>
<td headers="Message from DIR" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170034 <span style="white-space: pre;"><a href="1170034_SN4230002205_LAB_490.csv" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002205</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">6693</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-04-09 10:35:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-23 10:14:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-04-09 09:37:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-23 10:02:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped">Anytime app repeatedly crashed while trying to compile and share data file. Was not able to retrieve anytime app data file. Was not able to retrieve anytime app data file for upload.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center">1170035 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170035/1170035_GLU_SN4230002505_2024-04-09 133202.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center">4230002505</td>
<td headers="No.Glucose" class="gt_row gt_center">5170</td>
<td headers="Start Test Time" class="gt_row gt_center">2024-04-09 14:35:00</td>
<td headers="End Test Time" class="gt_row gt_center">2024-04-20 09:02:00</td>
<td headers="DUSEQ01" class="gt_row gt_center">1</td>
<td headers="Application Date and Time" class="gt_row gt_center">2024-04-09 13:33:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center">2024-04-20 09:40:00</td>
<td headers="Message from DIR" class="gt_row gt_center">Subject noticed sensor adhesive failing on 19apr2024 before bed. Upon waking up subject noted sensor had come off and phone gave above message.</td></tr>
    <tr><td headers="Subject ID" class="gt_row gt_center gt_striped">1170036 <span style="white-space: pre;"><a href="//Wf00168p.oneabbott.com/DATA1/cdm/ADC-US-RES-23241/SE03/UploadData/Yuwell/117_ERA/001170036/1170036_LAB_SN4230002354_2024-04-15 103443.txt" target="_blank" style="color:#008B8B;text-decoration:none;display: inline-block;">Link</a></span></td>
<td headers="Condition ID" class="gt_row gt_center gt_striped">LAB</td>
<td headers="Sensor Serial Number" class="gt_row gt_center gt_striped">4230002354</td>
<td headers="No.Glucose" class="gt_row gt_center gt_striped">6477</td>
<td headers="Start Test Time" class="gt_row gt_center gt_striped">2024-04-15 11:37:00</td>
<td headers="End Test Time" class="gt_row gt_center gt_striped">2024-04-29 10:52:00</td>
<td headers="DUSEQ01" class="gt_row gt_center gt_striped">1</td>
<td headers="Application Date and Time" class="gt_row gt_center gt_striped">2024-04-15 10:36:00</td>
<td headers="Removal Date and Time" class="gt_row gt_center gt_striped">2024-04-29 10:47:00</td>
<td headers="Message from DIR" class="gt_row gt_center gt_striped"><br /></td></tr>
  </tbody>
  
  
</table>
</div>
```


:::
:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell .column-screen}

:::