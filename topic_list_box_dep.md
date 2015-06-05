```

<div class="...">

Unknown end tag for &lt;/div&gt;




```
Chèn vào CSS


```


.khoang{padding: 15px 0}
.thanhtieude1{background:url(http://i43.servimg.com/u/f43/16/03/04/56/iaza1511.gif) no-repeat scroll 0 50% transparent;color:#FFF;font-size:9px;height:50px;line-height:32px;margin-left:-33px;margin-top:-10px;position:absolute;text-align:center;text-shadow:1px 0 1px #2A2A2A;width:510px}
.thanhtieude{background:url(http://i43.servimg.com/u/f43/16/03/04/56/iaza1213.gif) no-repeat scroll 0 50% transparent;margin-left:-19px;margin-top:-36px;width:200px;color:#FFF;font-size:9px;height:50px;line-height:32px;text-align:center;text-shadow:1px 0 1px #2A2A2A;position:absolute}



```
Chèn Topic\_list\_box

```

<!-- BEGIN topics_list_box -->
<!-- BEGIN row -->
<!-- BEGIN header_table -->
<!-- BEGIN multi_selection -->
<script type="text/javascript">
function check_uncheck_main_{topics_list_box.row.header_table.BOX_ID}() {
var all_checked = true;
for (i = 0; (i < document.{topics_list_box.FORMNAME}.elements.length) && all_checked; i++) {
if (document.{topics_list_box.FORMNAME}.elements[i].name == '{topics_list_box.FIELDNAME}[]{topics_list_box.row.header_table.BOX_ID}') {
all_checked = document.{topics_list_box.FORMNAME}.elements[i].checked;
}
}
document.{topics_list_box.FORMNAME}.all_mark_{topics_list_box.row.header_table.BOX_ID}.checked = all_checked;
}
function check_uncheck_all_{topics_list_box.row.header_table.BOX_ID}() {
for (i = 0; i < document.{topics_list_box.FORMNAME}.length; i++) {
if (document.{topics_list_box.FORMNAME}.elements[i].name == '{topics_list_box.FIELDNAME}[]{topics_list_box.row.header_table.BOX_ID}') {
document.{topics_list_box.FORMNAME}.elements[i].checked = document.{topics_list_box.FORMNAME}.all_mark_{topics_list_box.row.header_table.BOX_ID}.checked;
}
}
}


Unknown end tag for &lt;/script&gt;


<!-- END multi_selection -->

<div class="main-head" style="height: 14px; background-color: #EE0000;border: 1px solid #DDD;box-shadow:-3px 3px 3px #c8c8c8;">
<!-- BEGIN multi_selection -->
<input onclick="check_uncheck_all_{topics_list_box.row.header_table.BOX_ID}();" type="checkbox" name="all_mark_{topics_list_box.row.header_table.BOX_ID}" value="0" />
<!-- END multi_selection -->
<span class="thanhtieude1">
<h1 class="page-title">{topics_list_box.row.L_TITLE} [{topics_list_box.row.COUNT_TOTAL_TOPICS}]

Unknown end tag for &lt;/h1&gt;




Unknown end tag for &lt;/span&gt;




Unknown end tag for &lt;/div&gt;


<div class="main-content">
<table id="rootlistFMvi" cellspacing="0" class="table">
<thead>
<tr>
<th class="tcl">{L_TOPICS}

Unknown end tag for &lt;/th&gt;


<th class="tc2">{topics_list_box.row.L_REPLIES}

Unknown end tag for &lt;/th&gt;


<th class="tc3">{topics_list_box.row.L_VIEWS}

Unknown end tag for &lt;/th&gt;


<th class="tcr">{topics_list_box.row.L_LASTPOST}

Unknown end tag for &lt;/th&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/thead&gt;


<tbody class="statused">
<!-- END header_table -->

<!-- BEGIN header_row -->
<strong>{topics_list_box.row.L_TITLE}

Unknown end tag for &lt;/strong&gt;


<!-- END header_row -->

<!-- BEGIN topic -->
<!-- BEGIN table_sticky -->


Unknown end tag for &lt;/tbody&gt;




Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/div&gt;



<div class="main-head" style="height: 14px; height: 14px; background-color: #9C15BC;border: 1px solid #DDD;box-shadow:-3px 3px 3px #c8c8c8;">
<!-- BEGIN multi_selection -->
<input onclick="check_uncheck_all_{topics_list_box.row.header_table.BOX_ID}();" type="checkbox" name="all_mark_{topics_list_box.row.header_table.BOX_ID}" value="0" />
<!-- END multi_selection -->
<span class="thanhtieude1">
<h2>{topics_list_box.row.topic.table_sticky.L_TITLE} [{topics_list_box.row.topic.table_sticky.COUNT_TOTAL_TOPICS}]

Unknown end tag for &lt;/h2&gt;




Unknown end tag for &lt;/span&gt;




Unknown end tag for &lt;/div&gt;


<div class="main-content">
<table cellspacing="0" class="table">
<thead>
<tr>
<th class="tcl">{L_TOPICS}

Unknown end tag for &lt;/th&gt;


<th class="tc2">{topics_list_box.row.topic.table_sticky.L_REPLIES}

Unknown end tag for &lt;/th&gt;


<th class="tc3">{topics_list_box.row.topic.table_sticky.L_VIEWS}

Unknown end tag for &lt;/th&gt;


<th class="tcr">{topics_list_box.row.topic.table_sticky.L_LASTPOST}

Unknown end tag for &lt;/th&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/thead&gt;


<tbody class="statused">
<!-- END table_sticky -->
<tr>
<td class="tcl tdtopics <!-- BEGIN line_sticky --> sticky-separator <!-- END line_sticky -->">
<span class="status">
<img title="{topics_list_box.row.L_TOPIC_FOLDER_ALT}" src="{topics_list_box.row.TOPIC_FOLDER_IMG}" alt="{topics_list_box.row.L_TOPIC_FOLDER_ALT}" />


Unknown end tag for &lt;/span&gt;


<!-- BEGIN single_selection -->
<input type="radio" name="{topics_list_box.FIELDNAME}" value="{topics_list_box.row.FID}" {topics_list_box.row.L_SELECT} />
<!-- END single_selection -->
{topics_list_box.row.ICON}
{topics_list_box.row.NEWEST_POST_IMG}
{topics_list_box.row.PARTICIPATE_POST_IMG}
{topics_list_box.row.TOPIC_TYPE}
<h2 class="topic-title"><a class="topictitle" href="{topics_list_box.row.U_VIEW_TOPIC}">{topics_list_box.row.TOPIC_TITLE}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/h2&gt;


{topics_list_box.row.GOTO_OPEN} {topics_list_box.row.GOTO_PAGE_NEW} {topics_list_box.row.GOTO_CLOSE}
{topics_list_box.row.L_BY} {topics_list_box.row.TOPIC_AUTHOR}
<!-- BEGIN switch_description -->
<br />
{topics_list_box.row.topic.switch_description.TOPIC_DESCRIPTION}
<!-- END switch_description -->


Unknown end tag for &lt;/td&gt;


<td class="tc2 <!-- BEGIN line_sticky --> sticky-separator <!-- END line_sticky -->">{topics_list_box.row.REPLIES}

Unknown end tag for &lt;/td&gt;


<td class="tc3 <!-- BEGIN line_sticky --> sticky-separator <!-- END line_sticky -->">{topics_list_box.row.VIEWS}

Unknown end tag for &lt;/td&gt;


<td class="tcr <!-- BEGIN line_sticky --> sticky-separator <!-- END line_sticky -->">{topics_list_box.row.LAST_POST_TIME} {topics_list_box.row.L_BY} {topics_list_box.row.LAST_POST_AUTHOR} {topics_list_box.row.LAST_POST_IMG}

Unknown end tag for &lt;/td&gt;


<!-- BEGIN multi_selection -->
<td><input onclick="javascript:check_uncheck_main_{topics_list_box.row.BOX_ID}();" type="checkbox" name="{topics_list_box.FIELDNAME}[]{topics_list_box.row.BOX_ID}" value="{topics_list_box.row.FID}" {topics_list_box.row.L_SELECT} />

Unknown end tag for &lt;/td&gt;


<!-- END multi_selection -->


Unknown end tag for &lt;/tr&gt;


<!-- END topic -->
<!-- BEGIN no_topics -->
<tr>
<td class="tcl" colspan="4"><strong>{topics_list_box.row.L_NO_TOPICS}

Unknown end tag for &lt;/strong&gt;



Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;


<!-- END no_topics -->

<!-- BEGIN bottom -->


Unknown end tag for &lt;/tbody&gt;




Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/div&gt;


<div class="main-foot clearfix">
<!-- BEGIN multi_selection -->
<input onclick="check_uncheck_all_{topics_list_box.row.header_table.BOX_ID}();" type="checkbox" name="all_mark_{topics_list_box.row.header_table.BOX_ID}" value="0" />
<!-- END multi_selection -->
<p class="h2">{L_TOPICS} [{topics_list_box.row.bottom.COUNT_TOTAL_TOPICS}]

Unknown end tag for &lt;/p&gt;


<p class="options">
<a href="{U_MARK_READ}">{L_MARK_TOPICS_READ}

Unknown end tag for &lt;/a&gt;

 {S_WATCH_FORUM} <a href="#top">{L_BACK_TO_TOP}

Unknown end tag for &lt;/a&gt;




Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


<!-- END bottom -->
<!-- BEGIN spacer --><br /><!-- END spacer -->
<!-- END row -->
<!-- END topics_list_box -->
<div class="main-head greenBgT" style="height: 14px;">
<span class="thanhtieude1">
<h1 class="page-title">Tùy chọn hiển thị chủ đề

Unknown end tag for &lt;/h1&gt;




Unknown end tag for &lt;/span&gt;




Unknown end tag for &lt;/div&gt;


<div id="sapxepFMvi" class="paged-foot clearfix">
<span>Tìm trước đó

Unknown end tag for &lt;/span&gt;


<select class="search_time">
<option selected="selected" value="0">Không giới hạn

Unknown end tag for &lt;/option&gt;


<option value="1">1 ngày

Unknown end tag for &lt;/option&gt;


<option value="7">7 ngày

Unknown end tag for &lt;/option&gt;


<option value="14">2 tuần

Unknown end tag for &lt;/option&gt;


<option value="30">1 tháng

Unknown end tag for &lt;/option&gt;


<option value="90">3 tháng

Unknown end tag for &lt;/option&gt;


<option value="180">6 tháng

Unknown end tag for &lt;/option&gt;


<option value="364">1 năm

Unknown end tag for &lt;/option&gt;




Unknown end tag for &lt;/select&gt;


<span>Sắp xếp theo

Unknown end tag for &lt;/span&gt;


<select class="sort_by">
<option selected="selected" value="0">Thời gian

Unknown end tag for &lt;/option&gt;


<option value="1">Chủ đề

Unknown end tag for &lt;/option&gt;


<option value="3">Tác giả

Unknown end tag for &lt;/option&gt;




Unknown end tag for &lt;/select&gt;


<span>Kiểu sắp xếp

Unknown end tag for &lt;/span&gt;


<select class="sort_type">
<option selected="selected" value="DESC">Giảm dần

Unknown end tag for &lt;/option&gt;


<option value="ASC">Tăng dần

Unknown end tag for &lt;/option&gt;




Unknown end tag for &lt;/select&gt;


<input type="button" value="Hiện chủ đề" class="button" />


Unknown end tag for &lt;/div&gt;


<div id="sapxepdulieu">

Unknown end tag for &lt;/div&gt;


<script type="text/javascript">
$("#sapxepFMvi .button").click(function () {
var Stime = $("#sapxepFMvi .search_time option:selected:selected").val();
var Ssort = $("#sapxepFMvi .sort_by option:selected:selected").val();
var Stype = $("#sapxepFMvi .sort_type option:selected:selected").val();
$("#sapxepdulieu").load("/search?search_keywords=&search_author=*&search_where=f{FORUM_ID}&search_time=" + Stime + "&sort_by=" + Ssort + "&sort_dir=" + Stype + " #main-content .frm-form", function () {
xepbaiFMvi();
});
});

function xepbaiFMvi() {
$("#sapxepdulieu .statused .tc2").remove();
$(".table:not('#rootlistFMvi') .statused").replaceWith($("#sapxepdulieu .table .statused"));
$(".paging:not('#sapxepdulieu .paging:first')").replaceWith($("#sapxepdulieu .paging"));
var lengthXep = $(".table:not('#rootlistFMvi') .statused tr").length;
$("#rootlistFMvi").parent().next().find("h2").text("Topics [" + lengthXep + "]");
$("#rootlistFMvi").parent().next().next().next().find(".h2").text("Topics [" + lengthXep + "]");
$(".paging a").click(function () {
var linkXeplai = $(this).attr("href");
$("#sapxepdulieu").load(linkXeplai + "#main-content .frm-form", function () {
xepbaiFMvi()
});
return false;
});
}


Unknown end tag for &lt;/script&gt;



```