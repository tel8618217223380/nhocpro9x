> ![http://i76.servimg.com/u/f76/15/23/22/46/blogbo10.jpg](http://i76.servimg.com/u/f76/15/23/22/46/blogbo10.jpg)
```

<style>
.imagedemo:hover {
cursor: pointer;
}
.blog_comments {
text-align: left;
padding-left: 10px;
}
.pun tbody.statused td.tcl {
padding: 0 !important;
width: 85%;
}
.imagedemo span {
font-size: 0 !important;
}
.blog_message {
display: table;
}
.imagedemo .codebox, .blog_message table, span.text img, .imagedemo img, span.text img + br, span.text img + br + br, span.text br + br {
display: none !important;
}
.phantext {
display: table-cell;
padding-left: 20px;
}
.status img {
height: 15px;
}


.imagedemo img:first-of-type {
display: inline !important;
max-width: 120px;
position: absolute;
top: 0;
left: 0;
min-height: 100px;
}
.status {
margin: 0 !important;
display: table-cell;
vertical-align: middle;
padding: 10px;
}
.imagedemo {
font-size: 0 !important;
height: 100px;
overflow: hidden !important;
position: relative;
width: 120px;
border: 1px solid #ccc;
padding: 0;
border-radius: 2px;
box-shadow: 0px 0px 1px #aaa;
background: #fff url('http://i43.servimg.com/u/f43/15/23/22/46/rsz_no10.jpg') no-repeat center;
}

Unknown end tag for &lt;/style&gt;

<!-- BEGIN topics_blog_box -->
<!-- BEGIN row -->
<!-- BEGIN header_table -->
<!-- BEGIN multi_selection -->
<script type="text/javascript">
function check_uncheck_main_{topics_blog_box.row.header_table.BOX_ID}() {
var all_checked = true;
for (i = 0; (i < document.{topics_blog_box.FORMNAME}.elements.length) && all_checked; i++) {
if (document.{topics_blog_box.FORMNAME}.elements[i].name == '{topics_blog_box.FIELDNAME}[]{topics_blog_box.row.header_table.BOX_ID}') {
all_checked = document.{topics_blog_box.FORMNAME}.elements[i].checked;
}
}
document.{topics_blog_box.FORMNAME}.all_mark_{topics_blog_box.row.header_table.BOX_ID}.checked = all_checked;
}
function check_uncheck_all_{topics_blog_box.row.header_table.BOX_ID}() {
for (i = 0; i < document.{topics_blog_box.FORMNAME}.length; i++) {
if (document.{topics_blog_box.FORMNAME}.elements[i].name == '{topics_blog_box.FIELDNAME}[]{topics_blog_box.row.header_table.BOX_ID}') {
document.{topics_blog_box.FORMNAME}.elements[i].checked = document.{topics_blog_box.FORMNAME}.all_mark_{topics_blog_box.row.header_table.BOX_ID}.checked;
}
}
}


Unknown end tag for &lt;/script&gt;


<!-- END multi_selection -->


<div class="main-head">
<!-- BEGIN multi_selection -->
<input onclick="check_uncheck_all_{topics_blog_box.row.header_table.BOX_ID}();" type="checkbox" name="all_mark_{topics_blog_box.row.header_table.BOX_ID}" value="0" />
<!-- END multi_selection -->
<h1 class="page-title">{topics_blog_box.row.L_TITLE} [{topics_blog_box.row.COUNT_TOTAL_TOPICS}]

Unknown end tag for &lt;/h1&gt;




Unknown end tag for &lt;/div&gt;


<div class="main-content">
<table cellspacing="0" class="table">
<tbody class="statused">
<!-- END header_table -->


<!-- BEGIN header_row -->
<strong>{topics_blog_box.row.L_TITLE}

Unknown end tag for &lt;/strong&gt;


<!-- END header_row -->


<!-- BEGIN topic -->
<!-- BEGIN table_sticky -->


Unknown end tag for &lt;/tbody&gt;




Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/div&gt;




<div class="main-head">
<!-- BEGIN multi_selection -->
<input onclick="check_uncheck_all_{topics_blog_box.row.header_table.BOX_ID}();" type="checkbox" name="all_mark_{topics_blog_box.row.header_table.BOX_ID}" value="0" /        >
<!-- END multi_selection -->
<h2>{topics_blog_box.row.topic.table_sticky.L_TITLE} [{topics_blog_box.row.topic.table_sticky.COUNT_TOTAL_TOPICS}]

Unknown end tag for &lt;/h2&gt;




Unknown end tag for &lt;/div&gt;


<div class="main-content">
<table cellspacing="0" class="table">
<tbody class="statused">
<!-- END table_sticky -->
<tr>
<td class="tcl tdtopics <!-- BEGIN line_sticky --> sticky-separator <!-- END line_sticky -->">
<!-- BEGIN single_selection -->
<input type="radio" name="{topics_blog_box.FIELDNAME}" value="{topics_blog_box.row.FID}" {topics_blog_box.row.L_SELECT} />
<!-- END single_selection -->

<!-- BEGIN switch_description -->
<span class="genmed">
<br />
{topics_blog_box.row.topic.switch_description.TOPIC_DESCRIPTION}


Unknown end tag for &lt;/span&gt;


<!-- END switch_description -->


<div class="clear">

Unknown end tag for &lt;/div&gt;


<div class="blog_message">                                        <div class="status"><img title="{topics_blog_box.row.L_TOPIC_FOLDER_ALT}" src="{topics_blog_box.row.TOPIC_FOLDER_IMG}" alt="{topics_blog_box.row.L_TOPIC_FOLDER_ALT}" />

Unknown end tag for &lt;/div&gt;


<div class="imagedemo" onClick="window.location = '{topics_blog_box.row.U_VIEW_TOPIC}#comments';">                                        {topics_blog_box.row.FIRST_POST_TEXT}

Unknown end tag for &lt;/div&gt;


<div class="phantext"><div class="blog_title">


{topics_blog_box.row.ICON} {topics_blog_box.row.NEWEST_POST_IMG}{topics_blog_box.row.PARTICIPATE_POST_IMG}
{topics_blog_box.row.TOPIC_TYPE} <h2 class="topic-title hierarchy"><a class="topictitle" href="{topics_blog_box.row.U_VIEW_TOPIC}">{topics_blog_box.row.TOPIC_TITLE}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/h2&gt;


{topics_blog_box.row.GOTO_OPEN} {topics_blog_box.row.GOTO_PAGE_NEW} {topics_blog_box.row.GOTO_CLOSE}


Unknown end tag for &lt;/div&gt;

<span class="text">{topics_blog_box.row.FIRST_POST_TEXT}<br/><em>{topics_blog_box.row.FIRST_POST_DMY_VALUE0}/{topics_blog_box.row.FIRST_POST_DMY_VALUE1}/{topics_blog_box.row.FIRST_POST_DMY_VALUE2}

Unknown end tag for &lt;/em&gt;



Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<br/>

<!-- BEGIN multi_selection -->
<input onclick="javascript:check_uncheck_main_{topics_blog_box.row.BOX_ID}();" type="checkbox" name="{topics_blog_box.FIELDNAME}[]{topics_blog_box.row.BOX_ID}" value="{topics_blog_box.row.FID}" {topics_blog_box.row.L_SELECT} />
<!-- END multi_selection -->


Unknown end tag for &lt;/td&gt;


<td class="td2"><div class="blog_comments">
<span class="gensmall" style="float: left; margin-left: 5px;">Tác giả: <strong>{topics_blog_box.row.TOPIC_AUTHOR}

Unknown end tag for &lt;/strong&gt;

<br/>
{L_COMMENTS}: {topics_blog_box.row.REPLIES}<br/>
{L_VIEWS}: {topics_blog_box.row.VIEWS}

Unknown end tag for &lt;/span&gt;




Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;


<!-- END topic -->
<!-- BEGIN no_topics -->
<tr>
<td class="tcl" colspan="4"><strong>{topics_blog_box.row.L_NO_TOPICS}

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
<input onclick="check_uncheck_all_{topics_blog_box.row.header_table.BOX_ID}();" type="checkbox" name="all_mark_{topics_blog_box.row.header_table.BOX_ID}" value="0" />
<!-- END multi_selection -->
<p class="h2">{L_TOPICS} [{topics_blog_box.row.bottom.COUNT_TOTAL_TOPICS}]

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
<!-- END topics_blog_box -->
<script>$(".text").each(function(){
if ($(this).text().length > 105) {$(this).text($(this).text().substr(0, 100));$(this).append('...');
}
});

Unknown end tag for &lt;/script&gt;

```