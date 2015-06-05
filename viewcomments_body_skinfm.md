![http://i44.servimg.com/u/f44/15/64/85/86/skin_b10.jpg](http://i44.servimg.com/u/f44/15/64/85/86/skin_b10.jpg)

```
    <style type="text/css">
@keyframes realava
{
0%  {top:0px;}
10%  {top:55px;}
20%  {top:0px;}
30%  {top:35px;}
40%  {top:0px;}
50%  {top:20px;}
60%  {top:0px;}
70%  {top:10px;}
80%  {top:0px;}
90%  {top:2px;}
100%  {top:0px;}
}

@-moz-keyframes realava /* Firefox */
{
0%  {top:0px;}
10%  {top:55px;}
20%  {top:0px;}
30%  {top:35px;}
40%  {top:0px;}
50%  {top:20px;}
60%  {top:0px;}
70%  {top:10px;}
80%  {top:0px;}
90%  {top:2px;}
100%  {top:0px;}
}

@-webkit-keyframes realava /* Safari and Chrome */
{
0%  {top:0px;}
10%  {top:55px;}
20%  {top:0px;}
30%  {top:35px;}
40%  {top:0px;}
50%  {top:20px;}
60%  {top:0px;}
70%  {top:10px;}
80%  {top:0px;}
90%  {top:2px;}
100%  {top:0px;}
}

@-o-keyframes realava /* Opera */
{
0%  {top:0px;}
10%  {top:55px;}
20%  {top:0px;}
30%  {top:35px;}
40%  {top:0px;}
50%  {top:20px;}
60%  {top:0px;}
70%  {top:10px;}
80%  {top:0px;}
90%  {top:2px;}
100%  {top:0px;}
}






.user-ident {
background: #262626;text-align: center;
}
.pun .user-ident .user-basic-info {
text-align: center;
padding: 20px 0;
}
.inf {
height: 170px;
width: 150px;
overflow: hidden;
position: relative;
margin: 10px auto;
border: 1px solid;
}
.ava, .ava img {
height: 170px;
width: 150px;
}
.inf1 {
z-index: 99;
position: absolute;
width: 134px;
top: 130px;
height: 170px;
background: rgba(0, 0, 0, 0.7);
padding: 8px;
}
.nam3 {
height: 30px;
text-align: center;
line-height: 30px;
margin-bottom: 5px;
}
.nam3 a, .nam3 span a {
color: #fff !important;
}
.inf:hover .inf1 {
top: 0;
text-overflow: ellipsis;
animation: realava .8s both;
-moz-animation: realava .8s both;
-webkit-animation: realava .8s both;
-o-animation: realava .8s both;
}
.user-ident > a img:hover {
opacity: 0.7;
}
.user-ident > a img {
opacity: 0.2;
box-shadow: 0 0 3px white;
}
.user-info hr {
border: 0;
border-bottom: 1px solid #fff;
-ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=20)";
filter: alpha(opacity=20);
opacity: .2;
margin: 4px 0;
}
.user-info, .user-info span {
color: #fff !important;
font: 13px/1.231 normal arial,helvetica,clean,sans-serif;
}
.proline:first-of-type {
width: 49%;
border-right: 1px solid rgba(255, 255, 255, 0.2);
display: inline-block;
padding-right: 4px;
margin-right: 6px;
}
.proline:first-of-type + hr {
display: none;
}
.ds p {
white-space: nowrap;
overflow: hidden;
text-overflow: ellipsis;
line-height: 1.5em;
}
#pun-qpost, .main .main-foot {
clear: both;
}
#bailienquan, #cungchuyenmuc {
padding-bottom: 15px;
margin-bottom: 10PX;
border-radius: 0px 0px 4px 4px;
border: 1px solid #d5d5d5;
background-color: #FFF;
}
.ds p {
white-space: nowrap;
overflow: hidden;
text-overflow: ellipsis;
line-height: 1.5em;
padding: 2px 8px;
}
.ds p:hover {
background-color: #EDF1F5;
}


#blog_comments {
background: none;
border: none;
width: 100%;
}
.dempost {
list-style: none;
width: 73%;
float: left;
}
.main.ds {
width: 25%;
float: right;
}
.dempost li {
margin: 10px 0;
}
.dempost li .post {
margin-right: 70px;
margin-left: 0;
padding: 7px 8px;
border: 1px solid #d5d5d5;
background-color: #FFF;
font-size: 11px;
color: #333;font-family: Arial, Helvetica, sans-serif;
line-height: 17px;
-moz-border-radius: 3px;
-webkit-border-radius: 3px;
-o-border-radius: 3px;
-ms-border-radius: 3px;
border-radius: 3px;position: relative;
}
.dempost li:nth-child(2n+1) .post {
margin-left: 70px;
margin-right: 0;
}.main-content.topic {
background: #fff;
}
.dempost li .blog_comment-avatar {
padding: 0px 0 0 10px;
float: right;
}
.dempost li:nth-child(2n+1) .blog_comment-avatar {
padding: 0px 10px 0 0;
float: left;
}
.blog_comment-avatar img {
margin: 0;
vertical-align: middle;
width: 50px;
padding: 4px;
background-color: #fff;
border: 1px solid #ccc;
border: 1px solid rgba(0, 0, 0, 0.2);
-webkit-box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
-moz-box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
}
#blog_comments .postfoot {
position: absolute;
bottom: 0;
right: 0;
margin: 0;
padding: 2px 10px;
visibility: hidden;
}
#blog_comments li:hover .postfoot {
visibility: visible;
}

.author-b a {
font-weight: bold;
}
.dempost li .post .author-a {
float: left;
font-size: 11px;
color: #999;
}
.dempost li .post .author-b {
float: right;
}
.dempost li:nth-child(2n+1) .post .author-b {
float: left;
}
.dempost li:nth-child(2n+1) .post .author-a {
float: right;
}
p.hed {
margin-bottom: 10px;
display: block;
float: left;
width: 100%;
}
#bookmarks {
width: 100%;
text-align: center;
border-bottom: 1px solid #ccc;
font-size: 0;
position: relative;
}

#bookmarks a {
bottom: -12px;
position: relative;
background: url('http://i43.servimg.com/u/f43/15/23/22/46/bgnois10.png');
display: inline-block;
padding: 2px;
}
#bookmarks a img:hover {
opacity: 0.7;
}
#text_editor_controls, fieldset.frm-set dl dt, #pun-qpost .main-head {
display: none !important;
}
fieldset.frm-set dl dd {
margin: 0;
}
#text_editor_textarea {
background-color: #ffffff;
border: 1px solid #cccccc;
-webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
-moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
-webkit-transition: border linear 0.2s, box-shadow linear 0.2s;
-moz-transition: border linear 0.2s, box-shadow linear 0.2s;
-o-transition: border linear 0.2s, box-shadow linear 0.2s;
transition: border linear 0.2s, box-shadow linear 0.2s;
color: #555555;
vertical-align: middle;
-webkit-border-radius: 4px;
-moz-border-radius: 4px;
border-radius: 4px;
font-size: 11px !important;
font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
padding: 5px 7px;
}
.main .main-content.frm, .pun .frm-form {
background: none;
border: none;
}





Unknown end tag for &lt;/style&gt;


<script type="text/javascript">
//<![CDATA[
var multiquote_img_off = '{JS_MULTIQUOTE_IMG_OFF}', multiquote_img_on = '{JS_MULTIQUOTE_IMG_ON}', _atr = '{JS_DIR}addthis/', _ati = '{PATH_IMG_FA}addthis/'{ADDTHIS_LANG}, addthis_localize = { share_caption: "{L_SHARE_CAPTION}", email: "{L_EMAIL}", email_caption: "{L_EMAIL_CAPTION}", favorites: "{L_SHARE_BOOKMARKS}", print: "{L_PRINT}", more: "{L_MORE}" };
$(function(){
_atc.cwait = 0;
$('.addthis_button').mouseup(function(){
if ($('#at15s').css('display') == 'block') {
addthis_close();
addthis_close();
}
});
});
//]]>


Unknown end tag for &lt;/script&gt;



<!-- BEGIN switch_user_logged_in -->
<div id="pun-visit" class="clearfix">
<ul>
<li>
<script type="text/javascript">//<![CDATA[
var url_favourite = '{U_FAVOURITE_JS_PLUS_MENU}';
var url_newposts = '{U_NEWPOSTS_JS_PLUS_MENU}';
var url_egosearch = '{U_EGOSEARCH_JS_PLUS_MENU}';
var url_unanswered = '{U_UNANSWERED_JS_PLUS_MENU}';
var url_watchsearch = '{U_WATCHSEARCH_JS_PLUS_MENU}';
var url_tellfriend = '{U_TELLFRIEND_JS_PLUS_MENU}';
insert_plus_menu_new('f{FORUM_ID}&amp;t={TOPIC_ID}','{JS_SESSION_ID}', {JS_AUTH_FAVOURITES});
//]]>


Unknown end tag for &lt;/script&gt;




Unknown end tag for &lt;/li&gt;


<li><a class="addthis_button" href="http://www.addthis.com/bookmark.php?v=250&amp;pub=forumotion">{L_SHARE}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/li&gt;


<li><a href="{U_SEARCH_NEW}">{L_SEARCH_NEW}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/li&gt;


<li><a href="{U_SEARCH_SELF}">{L_SEARCH_SELF}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/li&gt;


<!-- BEGIN watchtopic -->
<li>{S_WATCH_TOPIC}

Unknown end tag for &lt;/li&gt;


<!-- END watchtopic -->


Unknown end tag for &lt;/ul&gt;


<p>{LOGGED_AS}. {LAST_VISIT_DATE}

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


<!-- END switch_user_logged_in -->
<!-- BEGIN switch_user_logged_out -->
<div id="pun-visit">
<p>{L_NOT_CONNECTED} {L_LOGIN_REGISTER}

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


<!-- END switch_user_logged_out -->

<div class="pun-crumbs noprint">
<p class="crumbs">
<a href="{U_INDEX}">{L_INDEX}

Unknown end tag for &lt;/a&gt;

{NAV_CAT_DESC} »
<strong><a href="{TOPIC_URL}">{TOPIC_TITLE}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/strong&gt;




Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;



<div class="main paged">
<div class="paged-head clearfix">
<!-- BEGIN topicpagination -->
<p class="paging">{PAGINATION}

Unknown end tag for &lt;/p&gt;


<!-- END topicpagination -->
<p class="posting">
<!-- BEGIN switch_user_authpost -->
<a href="{U_POST_NEW_TOPIC}" rel="nofollow"><img src="{POST_IMG}" class="{POST_IMG_CLASS}" alt="{L_POST_NEW_TOPIC}" />

Unknown end tag for &lt;/a&gt;


<!-- END switch_user_authpost -->

<!-- BEGIN switch_user_authreply -->
<a href="{U_POST_REPLY_TOPIC}"><img src="{REPLY_IMG}" class="i_reply" alt="{L_POST_REPLY_TOPIC}" />

Unknown end tag for &lt;/a&gt;


<!-- END switch_user_authreply -->


Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


{POLL_DISPLAY}
<div class="main-head clearfix">
<p class="h2">
<a href="{U_VIEW_OLDER_TOPIC}">{L_VIEW_PREVIOUS_TOPIC}

Unknown end tag for &lt;/a&gt;

 <a href="{U_VIEW_NEWER_TOPIC}">{L_VIEW_NEXT_TOPIC}

Unknown end tag for &lt;/a&gt;

 <a href="#bottom">{L_GOTO_DOWN}

Unknown end tag for &lt;/a&gt;


{L_MESSAGE} [{PAGE_NUMBER}]


Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;



<div class="main-content topic">
<!-- BEGIN postrow -->
<!-- BEGIN displayed -->
<div class="post"{postrow.displayed.THANK_BGCOLOR}>
<a name="{postrow.displayed.U_POST_ID}">

Unknown end tag for &lt;/a&gt;


<div class="postmain"{postrow.displayed.THANK_BGCOLOR}>

<div id="p{postrow.displayed.U_POST_ID}" class="posthead"{postrow.displayed.THANK_BGCOLOR}>

<div class="blog_cal-border" style="margin-top:5px">
<div class="blog_cal-content">
<span class="blog_cal-{postrow.displayed.POST_DATE_DMY_CLASS0}">{postrow.displayed.POST_DATE_DMY_VALUE0}

Unknown end tag for &lt;/span&gt;


<span class="blog_cal-{postrow.displayed.POST_DATE_DMY_CLASS1}">{postrow.displayed.POST_DATE_DMY_VALUE1}

Unknown end tag for &lt;/span&gt;


<span class="blog_cal-{postrow.displayed.POST_DATE_DMY_CLASS2}">{postrow.displayed.POST_DATE_DMY_VALUE2}

Unknown end tag for &lt;/span&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;



<h2>
{postrow.displayed.ICON} <a href="{postrow.displayed.POST_URL}">{postrow.displayed.POST_SUBJECT}

Unknown end tag for &lt;/a&gt;

 {postrow.displayed.POST_DATE_NEW}


Unknown end tag for &lt;/h2&gt;




Unknown end tag for &lt;/div&gt;



<div class="postbody"{postrow.displayed.THANK_BGCOLOR}>

<div class="user online" style=" margin-left: -319px; ">
<div class="user-ident">

<div class="user-basic-info">
<div class="inf"> <div class="ava">{postrow.displayed.POSTER_AVATAR}

Unknown end tag for &lt;/div&gt;

<div class="inf1"><p class="nam3">{postrow.displayed.POSTER_NAME}

Unknown end tag for &lt;/p&gt;

<div class="user-info">
{postrow.displayed.ONLINE_IMG}
<!-- BEGIN profile_field -->
<span class="proline">{postrow.displayed.profile_field.LABEL}{postrow.displayed.profile_field.CONTENT}

Unknown end tag for &lt;/span&gt;

{postrow.displayed.profile_field.SEPARATOR}
<!-- END profile_field -->
{postrow.displayed.POSTER_RPG}




Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/div&gt;

{postrow.displayed.RANK_IMAGE}


Unknown end tag for &lt;/div&gt;




{postrow.displayed.PROFILE_IMG} {postrow.displayed.PM_IMG} {postrow.displayed.EMAIL_IMG}<!-- BEGIN contact_field --> {postrow.displayed.contact_field.CONTENT}<!-- END contact_field -->




Unknown end tag for &lt;/div&gt;





Unknown end tag for &lt;/div&gt;



<div class="post-entry">
<div class="entry-content">
<!-- BEGIN switch_vote_active -->
<div style="display: inline-block;">

<!-- BEGIN switch_bar -->
<div class="vote-bar" title="{postrow.displayed.switch_vote_active.L_VOTE_TITLE}">
<!-- BEGIN switch_vote_plus -->
<div class="vote-bar-plus" style="height:{postrow.displayed.switch_vote_active.switch_bar.switch_vote_plus.HEIGHT_PLUS}px;">

Unknown end tag for &lt;/div&gt;


<!-- END switch_vote_plus -->

<!-- BEGIN switch_vote_minus -->
<div class="vote-bar-minus" style="height:{postrow.displayed.switch_vote_active.switch_bar.switch_vote_minus.HEIGHT_MINUS}px;">

Unknown end tag for &lt;/div&gt;


<!-- END switch_vote_minus -->


Unknown end tag for &lt;/div&gt;


<!-- END switch_bar -->


Unknown end tag for &lt;/div&gt;


<!-- END switch_vote_active -->
<div>
{postrow.displayed.MESSAGE}
<!-- BEGIN switch_attachments -->
<div class="clear">

Unknown end tag for &lt;/div&gt;


<dl class="attachbox">
<dt>{postrow.displayed.switch_attachments.L_ATTACHMENTS}

Unknown end tag for &lt;/dt&gt;


<dd>
<!-- BEGIN switch_post_attachments -->
<dl class="file">
<dt>
<img src="{postrow.displayed.switch_attachments.switch_post_attachments.U_IMG}" />

<!-- BEGIN switch_dl_att -->
<a class="postlink" href="{postrow.displayed.switch_attachments.switch_post_attachments.switch_dl_att.U_ATTACHMENT}">{postrow.displayed.switch_attachments.switch_post_attachments.switch_dl_att.ATTACHMENT}

Unknown end tag for &lt;/a&gt;

 {postrow.displayed.switch_attachments.switch_post_attachments.switch_dl_att.ATTACHMENT_DEL}
<!-- END switch_dl_att -->

<!-- BEGIN switch_no_dl_att -->
{postrow.displayed.switch_attachments.switch_post_attachments.switch_no_dl_att.ATTACHMENT} {postrow.displayed.switch_attachments.switch_post_attachments.switch_no_dl_att.ATTACHMENT_DEL}
<!-- END switch_no_dl_att -->


Unknown end tag for &lt;/dt&gt;



<!-- BEGIN switch_no_comment -->
<dd>
<em>{postrow.displayed.switch_attachments.switch_post_attachments.switch_no_comment.ATTACHMENT_COMMENT}

Unknown end tag for &lt;/em&gt;




Unknown end tag for &lt;/dd&gt;


<!-- END switch_no_comment -->

<!-- BEGIN switch_no_dl_att -->
<dd>
<em>{postrow.displayed.switch_attachments.switch_post_attachments.switch_no_dl_att.TEXT_NO_DL}

Unknown end tag for &lt;/em&gt;




Unknown end tag for &lt;/dd&gt;


<!-- END switch_no_dl_att -->

<dd>({postrow.displayed.switch_attachments.switch_post_attachments.FILE_SIZE}) {postrow.displayed.switch_attachments.switch_post_attachments.NB_DL}

Unknown end tag for &lt;/dd&gt;




Unknown end tag for &lt;/dl&gt;


<!-- END switch_post_attachments -->


Unknown end tag for &lt;/dd&gt;




Unknown end tag for &lt;/dl&gt;


<!-- END switch_attachments -->


Unknown end tag for &lt;/div&gt;


<p>
{postrow.displayed.EDITED_MESSAGE}


Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;



<!-- BEGIN switch_signature -->
<div class="sig-content">
<span class="sig-line">

Unknown end tag for &lt;/span&gt;


{postrow.displayed.SIGNATURE_NEW}


Unknown end tag for &lt;/div&gt;


<!-- END switch_signature -->

<div class="postfoot clearfix">

<div class="post-options">
<!-- BEGIN switch_vote_active -->
<div style="display: inline-block;">
<!-- BEGIN switch_vote -->
<div class="vote-button"><a href="{postrow.displayed.switch_vote_active.switch_vote.U_VOTE_PLUS}"><i class="iplus">

Unknown end tag for &lt;/i&gt;



Unknown end tag for &lt;/a&gt;


<a href="{postrow.displayed.switch_vote_active.switch_vote.U_VOTE_MINUS}"><i class="iminus">

Unknown end tag for &lt;/i&gt;



Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/div&gt;


<!-- END switch_vote -->


Unknown end tag for &lt;/div&gt;


<!-- END switch_vote_active -->  {postrow.displayed.THANK_IMG}<span class="adminok"> {postrow.displayed.MULTIQUOTE_IMG} {postrow.displayed.QUOTE_IMG}

Unknown end tag for &lt;/span&gt;

 {postrow.displayed.EDIT_IMG} {postrow.displayed.DELETE_IMG} {postrow.displayed.IP_IMG} {postrow.displayed.REPORT_IMG}


Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<!-- END displayed -->
<!-- BEGIN hidden -->
<p class="p-hidden">{postrow.hidden.MESSAGE}

Unknown end tag for &lt;/p&gt;


<!-- END hidden -->
<!-- END postrow -->


Unknown end tag for &lt;/div&gt;



<!-- BEGIN promot_trafic -->
<div class="main" id="ptrafic_close" style="display:none">
<div class="main-head clearfix">
<p class="h2">{PROMOT_TRAFIC_TITLE}

Unknown end tag for &lt;/p&gt;


<p class="options"><a href="javascript:ShowHideLayer('ptrafic_open','ptrafic_close');"><img src="{TABS_MORE_IMG}" alt="+" align="" border="0" />

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<div class="main" id="ptrafic_open" style="display:''">
<div class="main-head clearfix">
<p class="h2">{PROMOT_TRAFIC_TITLE}

Unknown end tag for &lt;/p&gt;


<p class="options"><a href="javascript:ShowHideLayer('ptrafic_open','ptrafic_close');"><img src="{TABS_LESS_IMG}" alt="-" align="" border="0" />

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


<div class="main-content clearfix">
<!-- BEGIN link -->
» <a href="{promot_trafic.link.U_HREF}" target="_blank" title="{promot_trafic.link.TITLE}">{promot_trafic.link.TITLE}

Unknown end tag for &lt;/a&gt;

<br />
<!-- END link -->


Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<!-- END promot_trafic -->

<div id="bookmarks">
{L_BOOKMARKS}
<!-- BEGIN social_bookmarking -->
<a href="{social_bookmarking.URL}" title="{social_bookmarking.TITLE}" target="_blank" rel="nofollow">
<img class="{social_bookmarking.CLASS}" src="http://illiweb.com/fa/empty.gif" alt="{social_bookmarking.TITLE}" title="{social_bookmarking.TITLE}" />


Unknown end tag for &lt;/a&gt;


<!-- END social_bookmarking -->


Unknown end tag for &lt;/div&gt;


<div class="clear">

Unknown end tag for &lt;/div&gt;


<br />





<div class="main-content" id="blog_comments"><ul class="dempost">
<!-- BEGIN comment -->
<!-- BEGIN displayed --><li>
<div class="blog_comment-avatar">
{comment.displayed.POSTER_AVATAR}


Unknown end tag for &lt;/div&gt;


<div class="post"{comment.displayed.THANK_BGCOLOR}>






<a name="{comment.displayed.U_POST_ID}">

Unknown end tag for &lt;/a&gt;



<div id="p{comment.displayed.U_POST_ID}" class="postbody"{comment.displayed.THANK_BGCOLOR}><p class="hed">
<span class="author-a"><img src="{comment.displayed.MINI_POST_IMG}" alt="{comment.displayed.L_MINI_POST_ALT}" title="{comment.displayed.L_MINI_POST_ALT}" /> {comment.displayed.POST_DATE_NEW} 

Unknown end tag for &lt;/span&gt;

<span class="author-b"> {comment.displayed.POSTER_NAME}{comment.displayed.L_ONLINE}

Unknown end tag for &lt;/span&gt;




Unknown end tag for &lt;/p&gt;


<div class="post-entry">
<div class="entry-content">
<!-- BEGIN switch_vote_active -->
<div class="vote gensmall">
<!-- BEGIN switch_bar -->
<div class="vote-bar" title="{comment.displayed.switch_vote_active.L_VOTE_TITLE}">
<!-- BEGIN switch_vote_plus -->
<div class="vote-bar-plus" style="height:{comment.displayed.switch_vote_active.switch_bar.switch_vote_plus.HEIGHT_PLUS}px;">

Unknown end tag for &lt;/div&gt;


<!-- END switch_vote_plus -->

<!-- BEGIN switch_vote_minus -->
<div class="vote-bar-minus" style="height:{comment.displayed.switch_vote_active.switch_bar.switch_vote_minus.HEIGHT_MINUS}px;">

Unknown end tag for &lt;/div&gt;


<!-- END switch_vote_minus -->


Unknown end tag for &lt;/div&gt;


<!-- END switch_bar -->




Unknown end tag for &lt;/div&gt;


<!-- END switch_vote_active -->
<div>
{comment.displayed.MESSAGE}
<!-- BEGIN switch_attachments -->
<div class="clear">

Unknown end tag for &lt;/div&gt;


<dl class="attachbox">
<dt>{comment.displayed.switch_attachments.L_ATTACHMENTS}

Unknown end tag for &lt;/dt&gt;


<dd>
<!-- BEGIN switch_post_attachments -->
<dl class="file">
<dt>
<img src="{comment.displayed.switch_attachments.switch_post_attachments.U_IMG}" />

<!-- BEGIN switch_dl_att -->
<a class="postlink" href="{comment.displayed.switch_attachments.switch_post_attachments.switch_dl_att.U_ATTACHMENT}">{comment.displayed.switch_attachments.switch_post_attachments.switch_dl_att.ATTACHMENT}

Unknown end tag for &lt;/a&gt;

 {comment.displayed.switch_attachments.switch_post_attachments.switch_dl_att.ATTACHMENT_DEL}
<!-- END switch_dl_att -->

<!-- BEGIN switch_no_dl_att -->
{comment.displayed.switch_attachments.switch_post_attachments.switch_no_dl_att.ATTACHMENT} {comment.displayed.switch_attachments.switch_post_attachments.switch_no_dl_att.ATTACHMENT_DEL}
<!-- END switch_no_dl_att -->


Unknown end tag for &lt;/dt&gt;



<!-- BEGIN switch_no_comment -->
<dd>
<em>{comment.displayed.switch_attachments.switch_post_attachments.switch_no_comment.ATTACHMENT_COMMENT}

Unknown end tag for &lt;/em&gt;




Unknown end tag for &lt;/dd&gt;


<!-- END switch_no_comment -->

<!-- BEGIN switch_no_dl_att -->
<dd>
<em>{comment.displayed.switch_attachments.switch_post_attachments.switch_no_dl_att.TEXT_NO_DL}

Unknown end tag for &lt;/em&gt;




Unknown end tag for &lt;/dd&gt;


<!-- END switch_no_dl_att -->

<dd>({comment.displayed.switch_attachments.switch_post_attachments.FILE_SIZE}) {comment.displayed.switch_attachments.switch_post_attachments.NB_DL}

Unknown end tag for &lt;/dd&gt;




Unknown end tag for &lt;/dl&gt;


<!-- END switch_post_attachments -->


Unknown end tag for &lt;/dd&gt;




Unknown end tag for &lt;/dl&gt;


<!-- END switch_attachments -->


Unknown end tag for &lt;/div&gt;


<p>
{comment.displayed.EDITED_MESSAGE}


Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;



<div class="postfoot clearfix">
<div class="post-options">
{comment.displayed.THANK_IMG} {comment.displayed.MULTIQUOTE_IMG} {comment.displayed.QUOTE_IMG} {comment.displayed.EDIT_IMG} {comment.displayed.DELETE_IMG} {comment.displayed.IP_IMG} {comment.displayed.REPORT_IMG}


Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/li&gt;


<!-- END displayed -->
<!-- BEGIN hidden -->
<p class="p-hidden">{comment.hidden.MESSAGE}

Unknown end tag for &lt;/p&gt;


<!-- END hidden -->
<!-- END comment -->


Unknown end tag for &lt;/ul&gt;


<!-- BEGIN no_comment -->
<div class="post">
<div class="postbody no_comment">
<p style="text-align:center">{no_comment.L_NO_COMMENT}

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<!-- END no_comment -->


<div class="main ds">
<div class="main-head clearfix">
<p class="h2">
Bài viết mới cùng chuyên mục


Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


<div id="cungchuyenmuc" class="main-content frm">


Unknown end tag for &lt;/div&gt;


<div class="main-head clearfix">
<p class="h2">
Bài viết liên quan


Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


<div id="bailienquan" class="main-content frm">


Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<script type="text/javascript">
$(function () {
$('#cungchuyenmuc').load('/f{FORUM_ID}-forum .tdtopics:not(".tdtopics:contains(\"Announcement\"), .tdtopics:contains(\"Sticky\"), .tdtopics:contains(\"Global announcement\")") .topic-title a.topictitle:lt(10)', function () {
$('#cungchuyenmuc a.topictitle').wrap("<p>

Unknown end tag for &lt;/p&gt;

");
});
var topictitleFMvi = '{TOPIC_TITLE}';
var fmviTopictitle = topictitleFMvi.replace(/ /gi, '+');
$('#bailienquan').load('/search?mode=searchbox&search_keywords=' + fmviTopictitle + '&show_results=topics .tdtopics:not(".tdtopics:contains(\"Announcement\"), .tdtopics:contains(\"Sticky\"), .tdtopics:contains(\"Global announcement\")") .topic-title a.topictitle:lt(10)', function () {
$('#bailienquan a.topictitle').wrap("<p>

Unknown end tag for &lt;/p&gt;

");
});
});


Unknown end tag for &lt;/script&gt;










<!-- BEGIN switch_user_logged_in -->
<a name="quickreply">

Unknown end tag for &lt;/a&gt;


{QUICK_REPLY_FORM}
<!-- END switch_user_logged_in -->






<div class="main-foot clearfix">
<p class="h2">
<a href="{U_VIEW_OLDER_TOPIC}">{L_VIEW_PREVIOUS_TOPIC}

Unknown end tag for &lt;/a&gt;

 <a href="{U_VIEW_NEWER_TOPIC}">{L_VIEW_NEXT_TOPIC}

Unknown end tag for &lt;/a&gt;

 <a href="#top">{L_BACK_TO_TOP}

Unknown end tag for &lt;/a&gt;


{L_MESSAGE} [{PAGE_NUMBER}]


Unknown end tag for &lt;/p&gt;


<p class="options">
<input type="hidden" name="t" value="{TOPIC_ID}" />

<!-- <input type="hidden" name="sid" value="{S_SID}" /> -->
<input type="hidden" name="{SECURE_ID_NAME}" value="{SECURE_ID_VALUE}" />

<!-- BEGIN viewtopic_bottom -->
{S_TOPIC_ADMIN}
<!-- END viewtopic_bottom -->


Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;



<a name="bottomtitle">

Unknown end tag for &lt;/a&gt;



<div class="paged-foot clearfix">
<!-- BEGIN topicpagination -->
<p class="paging">{PAGINATION}

Unknown end tag for &lt;/p&gt;


<!-- END topicpagination -->
<p class="posting">
<!-- BEGIN switch_user_authpost -->
<a href="{U_POST_NEW_TOPIC}" rel="nofollow"><img src="{POST_IMG}" class="{POST_IMG_CLASS}" alt="{L_POST_NEW_TOPIC}" />

Unknown end tag for &lt;/a&gt;


<!-- END switch_user_authpost -->

<!-- BEGIN switch_user_authreply -->
<a href="{U_POST_REPLY_TOPIC}"><img src="{REPLY_IMG}" class="i_reply" alt="{L_POST_REPLY_TOPIC}" />

Unknown end tag for &lt;/a&gt;


<!-- END switch_user_authreply -->


Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;





Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;



<div class="pun-crumbs">
<p class="crumbs">
<a href="{U_INDEX}">{L_INDEX}

Unknown end tag for &lt;/a&gt;

{NAV_CAT_DESC} »
<strong><a href="{TOPIC_URL}">{TOPIC_TITLE}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/strong&gt;




Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;





<div id="pun-info" class="main">
<div class="main-content">
<div id="stats">
<p>{L_TABS_PERMISSIONS} <br />{S_AUTH_LIST}

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;



<!-- BEGIN switch_image_resize -->
<script type="text/javascript">
//<![CDATA[
$(resize_images({ 'selector' : '.post-entry .entry-content', 'max_width' : {switch_image_resize.IMG_RESIZE_WIDTH}, 'max_height' : {switch_image_resize.IMG_RESIZE_HEIGHT} }));
//]]>


Unknown end tag for &lt;/script&gt;


<!-- END switch_image_resize -->

<script src="{JS_DIR}addthis/addthis_widget.js" type="text/javascript">

Unknown end tag for &lt;/script&gt;

```