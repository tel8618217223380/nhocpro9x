![http://img405.imageshack.us/img405/60/79540334.png](http://img405.imageshack.us/img405/60/79540334.png)
demo 2: http://www.xaydungthanhhoa.com

```

<div class="main">
<!-- BEGIN catrow -->
<!-- BEGIN tablehead -->
<div class="main-head">
<div class="page-title">{catrow.tablehead.L_FORUM}

Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<div class="main-content">
<table cellspacing="0" class="table">
<thead>
<tr>
<th class="tcl">{L_FORUM}

Unknown end tag for &lt;/th&gt;


<th class="tc2">{L_TOPICS}

Unknown end tag for &lt;/th&gt;



<th class="tcr">{L_LASTPOST}

Unknown end tag for &lt;/th&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/thead&gt;


<tbody class="statused">
<!-- END tablehead -->

<!-- BEGIN forumrow -->
<tr>
<td class="tcl" style="padding-right: {catrow.forumrow.INC_LEVEL_RIGHT}; padding-left: {catrow.forumrow.INC_LEVEL_LEFT};">
<span class="status" style="margin-right: -{catrow.forumrow.INC_WIDTH_ICON}; margin-left: -{catrow.forumrow.INC_WIDTH_ICON};">
<img title="{catrow.forumrow.L_FORUM_FOLDER_ALT}" src="{catrow.forumrow.FORUM_FOLDER_IMG}" alt="{catrow.forumrow.L_FORUM_FOLDER_ALT}" />


Unknown end tag for &lt;/span&gt;


<h{catrow.forumrow.LEVEL} class="hierarchy"><a href="{catrow.forumrow.U_VIEWFORUM}" class="forumtitle">{catrow.forumrow.FORUM_NAME}

Unknown end tag for &lt;/a&gt;

</h{catrow.forumrow.LEVEL}>
<br />
{catrow.forumrow.FORUM_DESC}
<!-- BEGIN switch_moderators_links -->
<br />
{catrow.forumrow.switch_moderators_links.L_MODERATOR}{catrow.forumrow.switch_moderators_links.MODERATORS}
<!-- END switch_moderators_links -->
{catrow.forumrow.L_LINKS}{catrow.forumrow.LINKS}
<strong>{forumrow.L_SUBFORUM_STR}

Unknown end tag for &lt;/strong&gt;

 {forumrow.SUBFORUMS}


Unknown end tag for &lt;/td&gt;


<td class="tc2">{catrow.forumrow.TOPICS}  topics <br>{catrow.forumrow.POSTS} replies

Unknown end tag for &lt;/td&gt;



<td class="tcr">
<div class="avs"><span>
<!-- BEGIN switch_topic_title -->
<a href="{catrow.forumrow.U_LATEST_TOPIC}" title="{catrow.forumrow.LATEST_TOPIC_TITLE}">{catrow.forumrow.LATEST_TOPIC_NAME}

Unknown end tag for &lt;/a&gt;

<br />
<!-- END switch_topic_title -->
{catrow.forumrow.USER_LAST_POST}


Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;


<!-- END forumrow -->

<!-- BEGIN tablefoot -->


Unknown end tag for &lt;/tbody&gt;




Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/div&gt;


<!-- END tablefoot -->
<!-- END catrow -->


Unknown end tag for &lt;/div&gt;



<style>.avs a.inx img {
float: left;
width: 40px;
height: 40px;
padding: 1px;
border: 1px solid #DDD;
margin: 0 5px;
-webkit-box-shadow: 0px 0px 3px rgba(50, 50, 50, 0.75);
-moz-box-shadow: 0px 0px 3px rgba(50, 50, 50, 0.75);
box-shadow: 0px 0px 3px rgba(50, 50, 50, 0.75);
}


Unknown end tag for &lt;/style&gt;



<script>
$(document).on('ready', function() {
$('.avs').each(function () {
var touser = $(this).children('span').children('strong').children('a').attr('href');
$(this).prepend('<a href="' + touser + '" class="inx"><img src="http://i34.servimg.com/u/f34/16/54/26/99/female10.png" alt="нет аватара" />

Unknown end tag for &lt;/a&gt;

');
$(this).children('a').load(touser + ' div.main-content.clearfix.center img:eq(0)');
});
});


Unknown end tag for &lt;/script&gt;


<!-- BEGIN switch_on_index -->
<div class="main-box clearfix">
<ul>
<li><a href="{U_TODAY_ACTIVE}">{L_TODAY_ACTIVE}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/li&gt;


<li><a href="{U_TODAY_POSTERS}">{L_TODAY_POSTERS}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/li&gt;


<li><a href="{U_OVERALL_POSTERS}">{L_OVERALL_POSTERS}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/li&gt;




Unknown end tag for &lt;/ul&gt;


<!-- BEGIN switch_delete_cookies -->
<p class="right">
<a href="{switch_on_index.switch_delete_cookies.U_DELETE_COOKIES}">{switch_on_index.switch_delete_cookies.L_DELETE_COOKIES}

Unknown end tag for &lt;/a&gt;




Unknown end tag for &lt;/p&gt;


<!-- END switch_delete_cookies -->


Unknown end tag for &lt;/div&gt;


<!-- END switch_on_index -->

```



kiểu 2

```

<div class="main">
<!-- BEGIN catrow -->
<!-- BEGIN tablehead -->
<div class="main-head">
<div class="page-title">{catrow.tablehead.L_FORUM}

Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<div class="main-content">
<table cellspacing="0" class="table">
<thead>
<tr>
<th class="tcl">{L_FORUM}

Unknown end tag for &lt;/th&gt;




<th class="tcr">{L_LASTPOST}

Unknown end tag for &lt;/th&gt;





Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/thead&gt;


<tbody class="statused">
<!-- END tablehead -->

<!-- BEGIN forumrow -->
<tr>
<td class="tcl" style="padding-right: {catrow.forumrow.INC_LEVEL_RIGHT}; padding-left: {catrow.forumrow.INC_LEVEL_LEFT};">
<span class="status" style="margin-right: -{catrow.forumrow.INC_WIDTH_ICON}; margin-left: -{catrow.forumrow.INC_WIDTH_ICON};">
<img title="{catrow.forumrow.L_FORUM_FOLDER_ALT}" src="{catrow.forumrow.FORUM_FOLDER_IMG}" alt="{catrow.forumrow.L_FORUM_FOLDER_ALT}" />


Unknown end tag for &lt;/span&gt;


<h{catrow.forumrow.LEVEL} class="hierarchy"><a href="{catrow.forumrow.U_VIEWFORUM}" class="forumtitle">{catrow.forumrow.FORUM_NAME}

Unknown end tag for &lt;/a&gt;

</h{catrow.forumrow.LEVEL}>
<br />

{catrow.forumrow.FORUM_DESC}<br>
<strong>{catrow.forumrow.TOPICS} Chủ đề | {catrow.forumrow.POSTS} nhận xét

Unknown end tag for &lt;/strong&gt;


<!-- BEGIN switch_moderators_links -->
<br />
{catrow.forumrow.switch_moderators_links.L_MODERATOR}{catrow.forumrow.switch_moderators_links.MODERATORS}
<!-- END switch_moderators_links -->
{catrow.forumrow.L_LINKS}{catrow.forumrow.LINKS}
<strong>{forumrow.L_SUBFORUM_STR}

Unknown end tag for &lt;/strong&gt;

 {forumrow.SUBFORUMS}


Unknown end tag for &lt;/td&gt;





<td class="tcr">
<span>  <div id="forums-stats">
<!-- BEGIN switch_topic_title -->
<a href="{catrow.forumrow.U_LATEST_TOPIC}" title="{catrow.forumrow.LATEST_TOPIC_TITLE}">{catrow.forumrow.LATEST_TOPIC_NAME}

Unknown end tag for &lt;/a&gt;

<br />
<!-- END switch_topic_title -->
{catrow.forumrow.USER_LAST_POST}


Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;


<!-- END forumrow -->

<!-- BEGIN tablefoot -->


Unknown end tag for &lt;/tbody&gt;




Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/div&gt;


<!-- END tablefoot -->
<!-- END catrow -->


Unknown end tag for &lt;/div&gt;



<!-- BEGIN switch_on_index -->
<div class="main-box clearfix">
<ul>
<li><a href="{U_TODAY_ACTIVE}">{L_TODAY_ACTIVE}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/li&gt;


<li><a href="{U_TODAY_POSTERS}">{L_TODAY_POSTERS}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/li&gt;


<li><a href="{U_OVERALL_POSTERS}">{L_OVERALL_POSTERS}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/li&gt;




Unknown end tag for &lt;/ul&gt;


<!-- BEGIN switch_delete_cookies -->
<p class="right">
<a href="{switch_on_index.switch_delete_cookies.U_DELETE_COOKIES}">{switch_on_index.switch_delete_cookies.L_DELETE_COOKIES}

Unknown end tag for &lt;/a&gt;




Unknown end tag for &lt;/p&gt;


<!-- END switch_delete_cookies -->


Unknown end tag for &lt;/div&gt;


<!-- END switch_on_index -->


<style>/* Avatar in index */
.avatar-index {float: left;}
.avatar-index img {width: 40px;height: 40px;background: #F4F4F4;border: 1px solid #DDD;margin: 0 5px;padding: 1px;}
.avatar-index img:hover {border: 1px dashed #CCC;}


Unknown end tag for &lt;/style&gt;



<script>
$(document).ready(function(){var Copyrights="Â©Copyright by giObanii. Â©Copyright by toxigeek.com. All Rights Reserved.";$('.statused .tdtopics').each(function(s){$(this).prepend('<div id="avatar-subforo'+s+'" class="avatar-index avatar-subforo"><div>');var b=this.getElementsByTagName('a')[1].href;$('#avatar-subforo'+s).load(b+' .module .main-content.clearfix.center:eq(0) img:eq(0)')});$('.statused .tcr').each(function(i){$(this).prepend('<div id="avatar-index'+i+'" class="avatar-index"><div>');var a=this.getElementsByTagName('a')[1].href;$('#avatar-index'+i).load(a+' .module .main-content.clearfix.center:eq(0) img:eq(0)')})});



Unknown end tag for &lt;/script&gt;



```
