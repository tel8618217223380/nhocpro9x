```
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
<input onclick="check_uncheck_all_{topics_blog_box.row.header_table.BOX_ID}();" type="checkbox" name="all_mark_{topics_blog_box.row.header_table.BOX_ID}" value="0" /	>
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
<input type="radio" name="{topics_blog_box.FIELDNAME}" value="{topics_blog_box.row.FID}" {topics_blog_box.row.L_SELECT} />&nbsp;
<!-- END single_selection -->


<div class="blog_title">

<span class="status"><img title="{topics_blog_box.row.L_TOPIC_FOLDER_ALT}" src="{topics_blog_box.row.TOPIC_FOLDER_IMG}" alt="{topics_blog_box.row.L_TOPIC_FOLDER_ALT}" />

Unknown end tag for &lt;/span&gt;


{topics_blog_box.row.ICON}&nbsp;{topics_blog_box.row.NEWEST_POST_IMG}{topics_blog_box.row.PARTICIPATE_POST_IMG}&nbsp;
{topics_blog_box.row.TOPIC_TYPE}&nbsp;<h2 class="topic-title hierarchy"><a class="topictitle" href="{topics_blog_box.row.U_VIEW_TOPIC}">

{topics_blog_box.row.TOPIC_TITLE}<br />

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/h2&gt;





Unknown end tag for &lt;/div&gt;



<!-- BEGIN switch_description -->
<span class="genmed">
<br />
{topics_blog_box.row.topic.switch_description.TOPIC_DESCRIPTION}


Unknown end tag for &lt;/span&gt;


<!-- END switch_description -->
<div class="clear""></div>
<div class="blog_message">
{topics_blog_box.row.FIRST_POST_TEXT}


Unknown end tag for &lt;/div&gt;


<br />[<a href="{topics_blog_box.row.U_VIEW_TOPIC}">&raquo; Xem tiếp

Unknown end tag for &lt;/a&gt;

]
<div class="clear">

Unknown end tag for &lt;/div&gt;


<div class="blog_comments">
<span class="gensmall">Người đăng: <strong>{topics_blog_box.row.TOPIC_AUTHOR}

Unknown end tag for &lt;/strong&gt;

&nbsp;-&nbsp;
<a href="{topics_blog_box.row.U_VIEW_TOPIC}#comments">{L_COMMENTS}

Unknown end tag for &lt;/a&gt;

: {topics_blog_box.row.REPLIES}&nbsp;-&nbsp;
{L_VIEWS}: {topics_blog_box.row.VIEWS}
&nbsp;-&nbsp;Thời gian đăng:&nbsp;{topics_blog_box.row.FIRST_POST_DMY_VALUE0}/{topics_blog_box.row.FIRST_POST_DMY_VALUE1}/{topics_blog_box.row.FIRST_POST_DMY_VALUE2}


Unknown end tag for &lt;/span&gt;




Unknown end tag for &lt;/div&gt;


<!-- BEGIN multi_selection -->
<input onclick="javascript:check_uncheck_main_{topics_blog_box.row.BOX_ID}();" type="checkbox" name="{topics_blog_box.FIELDNAME}[]{topics_blog_box.row.BOX_ID}" value="{topics_blog_box.row.FID}" {topics_blog_box.row.L_SELECT} />
<!-- END multi_selection -->


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

&nbsp;{S_WATCH_FORUM}&nbsp;<a href="#top">{L_BACK_TO_TOP}

Unknown end tag for &lt;/a&gt;




Unknown end tag for &lt;/p&gt;



Unknown end tag for &lt;/div&gt;


<!-- END bottom -->
<!-- BEGIN spacer --><br /><!-- END spacer -->
<!-- END row -->
<!-- END topics_blog_box -->

<!-- BEGIN switch_image_resize -->
<script type="text/javascript">
//<![CDATA[
$(resize_images({ 'selector' : '.blog_message', 'max_width' : {switch_image_resize.IMG_RESIZE_WIDTH}, 'max_height' : {switch_image_resize.IMG_RESIZE_HEIGHT} }));
//]]>


Unknown end tag for &lt;/script&gt;



<!-- END switch_image_resize -->
<style>.ImgBlog{float:left;margin:3px 10px;width:120px;height:100px;}
.blog_message{text-align:justify;font-size:18px;line-height:120%;margin-right:10px;}


Unknown end tag for &lt;/style&gt;



<script type="text/javascript">//<![CDATA[
$('.blog_message').each(function(){if ($(this).find('img').length){ImgBlog = "";$(this).find('img').each(function(){if ($(this).attr('src').search('smiles') == -1){ImgBlog = $(this).attr('src');return false;}else if (ImgBlog == ""){ImgBlog = "http://i36.servimg.com/u/f36/17/76/06/16/no-pho10.jpg";}});}else{ImgBlog = "http://i36.servimg.com/u/f36/17/76/06/16/no-pho10.jpg";}$(this).text($(this).text());$('<img src="'+ImgBlog+'" class="ImgBlog" />').prependTo(this);});//]]>

Unknown end tag for &lt;/script&gt;

```