<style>
@import '../assets/vendors/weui.0.4.0.min.css';
@import '../assets/vendors/1px.css';

.weui_cell_box.weui_cell {
  padding:0;
}
.weui_cell_ft.with_arrow:after {
  content: " ";
  display: inline-block;
  -webkit-transform: rotate(45deg);
  transform: rotate(45deg);
  height: 6px;
  width: 6px;
  border-width: 2px 2px 0 0;
  border-color: #C8C8CD;
  border-style: solid;
  position: relative;
  top: -2px;
  top: -1px;
  margin-left: .3em;
}
.weui_cells > a {
  color:#000;
}
</style>
