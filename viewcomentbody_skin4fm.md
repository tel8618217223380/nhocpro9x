![http://img98.imageshack.us/img98/3931/cuoilbbforumvicomt6topi.png](http://img98.imageshack.us/img98/3931/cuoilbbforumvicomt6topi.png)


ACP >> DISPLAY >> Templates >> Quản Lý Tổng Thể >> viewcomments\_body ; thay toàn bộ bằng code bên dưới

```

<style>
.author {
width: 400px;
text-align: right;
float: right;
padding-top: 5px;
padding-right: 10px;
}
#blog_comments .h3 {
margin-left: 45px;
margin-top: 0;
min-height: 22px;
overflow: hidden;
padding: 0;
width: 400px;
margin-right: 0;
display: inline;
}
.alta {
padding: 3px;
margin: auto;
padding-right: 0px!important;
}
#ptitle {
background: url(http://i23.servimg.com/u/f23/15/23/22/46/untitl10.jpg) no-repeat;
height: 106px;
margin: 0px 8px 0px 0px;
width: 100%;
border: 2px;
border-color: #CCC;
}
.titlew {
padding: 15px 0px 0px 175px;
}
#titlet {
width: 645px;
font: 18px arial,verdana,tahoma,arial;
color: #C83A14;
padding: 0px 0px 3px 0px;
border-bottom: 1px dashed #777;
}
#detailw {
padding: 12px 80px 10px 0px;
}
.rankbg {
background: #FBF9F5;
border: 1px dashed #919191;
padding: 10px;
width: 94%;
}
#pt {
background: url(http://www.skin4fm.com/users/1513/21/33/80/album/tai_xu11.gif) no-repeat;
height: 28px;
}
.pbg {
background: url(http://www.skin4fm.com/users/1513/21/33/80/album/tai_xu12.gif) repeat-y;
}
#arrow {
background: url(http://www.skin4fm.com/users/1513/21/33/80/album/tai_xu14.gif) right no-repeat;
height: 7px;
margin: 5px 10px 0px 0px;
}
.attw {
margin: 10px;
}
#pb {
background: url(http://www.skin4fm.com/users/1513/21/33/80/album/tai_xu13.gif) no-repeat;
height: 28px;
}
.butbg2 {
border-top: 1px dashed #CCC;
clear: both;
margin-right: -17em;
padding: .5em 1em;
background: #E1EBF2;
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


<div id="mainview">
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
<table style="background: #fff;" cellpadding="0" cellspacing="1" border="0" width="100%" align="center">

<tbody><tr>
<td class="thead" colspan="4" align="center">
<div class="normal" style="float:right">
{postrow.displayed.COUNT_POSTS}

Unknown end tag for &lt;/strong&gt;


{postrow.displayed.ICON} <a href="{postrow.displayed.POST_URL}">{postrow.displayed.POST_SUBJECT}

Unknown end tag for &lt;/a&gt;




Unknown end tag for &lt;/div&gt;





Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;



<tr>
<td class="alta">

<div id="ptitle">
<div class="titlew">

<div id="titlet">
{postrow.displayed.ICON} <a href="{postrow.displayed.POST_URL}">{postrow.displayed.POST_SUBJECT}

Unknown end tag for &lt;/a&gt;

 {postrow.displayed.POST_DATE_NEW}


Unknown end tag for &lt;/div&gt;



<div  align="right" id="detailw">

<table cellspacing="0" cellpadding="0">
<tbody><tr>


<td style="padding-left:80px;">
<div class="detailt">
{postrow.displayed.PROFILE_IMG} {postrow.displayed.PM_IMG} {postrow.displayed.EMAIL_IMG}<!-- BEGIN contact_field --> {postrow.displayed.contact_field.CONTENT}<!-- END contact_field -->



Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/tbody&gt;



Unknown end tag for &lt;/table&gt;






Unknown end tag for &lt;/div&gt;





Unknown end tag for &lt;/div&gt;








<!-- BEGIN switch_vote_active -->
<div class="vote gensmall">
<!-- BEGIN switch_vote -->
<div class="vote-button"><a href="{postrow.displayed.switch_vote_active.switch_vote.U_VOTE_PLUS}">+

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/div&gt;


<!-- END switch_vote -->

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

<!-- BEGIN switch_no_bar -->
<div title="{postrow.displayed.switch_vote_active.L_VOTE_TITLE}" class="vote-no-bar">----

Unknown end tag for &lt;/div&gt;


<!-- END switch_no_bar -->

<!-- BEGIN switch_vote -->
<div class="vote-button"><a href="{postrow.displayed.switch_vote_active.switch_vote.U_VOTE_MINUS}">-

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/div&gt;


<!-- END switch_vote -->


Unknown end tag for &lt;/div&gt;


<!-- END switch_vote_active -->





Unknown end tag for &lt;/div&gt;



<table cellpadding="0" cellspacing="0" border="0" width="100%" align="center">
<tbody><tr>

<td valign="top">
<table cellpadding="10" cellspacing="0" border="0" width="100%">
<tbody><tr>



<td class="alta" colspan="3" id="td_post_118815">
<div class="postbody"{postrow.displayed.THANK_BGCOLOR}>
<br>


<div class="rankbg" align="center" style="margin:-10px 0px 20px 0px;">
<div style="padding-left:230px;">{postrow.displayed.RANK_IMAGE}

Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;





<div class="post-entry">
<div class="entry-content">

<div>
{postrow.displayed.MESSAGE}



Unknown end tag for &lt;/div&gt;





Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;










Unknown end tag for &lt;/div&gt;







Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/tbody&gt;



Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/td&gt;



<td width="240" align="right" valign="top">
<div id="pt">

Unknown end tag for &lt;/div&gt;


<div class="pbg">
<table cellpadding="0" cellspacing="0" border="0" width="100%" align="center">
<tbody><tr>
<td align="center">
<div id="postmenu_118815">
{postrow.displayed.POSTER_NAME}




Unknown end tag for &lt;/div&gt;




<div style="padding-bottom:10px;">

Unknown end tag for &lt;/div&gt;



<div align="center">
<div id="avat">

Unknown end tag for &lt;/div&gt;


<div class="avabg"><div class="avatop">
{postrow.displayed.POSTER_AVATAR}


Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/div&gt;


<div id="avab">

Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;




<div style="padding-top:10px;">

Unknown end tag for &lt;/div&gt;


<div class="prot" align="left" style="padding-left:25px;"">
<div><img class="imgp" src="http://hoiquantinhoc.com/forum/HQTH/hqthv5/HQTH_postbit/icon.gif">  {postrow.displayed.POSTER_RANK_NEW}

Unknown end tag for &lt;/div&gt;



<!-- BEGIN profile_field --><img class="imgp" src="http://hoiquantinhoc.com/forum/HQTH/hqthv5/HQTH_postbit/icon.gif">
{postrow.displayed.profile_field.LABEL}{postrow.displayed.profile_field.CONTENT}{postrow.displayed.profile_field.SEPARATOR}
<!-- END profile_field -->
{postrow.displayed.POSTER_RPG}


<div id="arrow">

Unknown end tag for &lt;/div&gt;




<div class="attw" align="left">

<div style="padding-bottom:10px;">




Unknown end tag for &lt;/div&gt;









Unknown end tag for &lt;/div&gt;








Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/tbody&gt;



Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/div&gt;


<div id="pb">

Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/td&gt;





Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/tbody&gt;



Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;



<tr>
<td class="alta">
<div class="alt3" style="padding:10px;">




<!-- BEGIN switch_attachments -->      <fieldset style="border: 1px dashed #6a6a6a;" class="fieldset">
<legend>Attached Files

Unknown end tag for &lt;/legend&gt;



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





Unknown end tag for &lt;/fieldset&gt;

   <!-- END switch_attachments -->





<div class="sig-content">
<span class="sig-line">

Unknown end tag for &lt;/span&gt;


<img src="http://i23.servimg.com/u/f23/15/13/67/04/wsnud910.jpg" border="0">


Unknown end tag for &lt;/div&gt;







Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;



<tr><td class="butbg2" style="padding:10px;"><div class="detailt">
{postrow.displayed.EDITED_MESSAGE}{postrow.displayed.ONLINE_IMG}


Unknown end tag for &lt;/div&gt;


<div style="float:right;">

{postrow.displayed.THANK_IMG} {postrow.displayed.MULTIQUOTE_IMG} {postrow.displayed.QUOTE_IMG} {postrow.displayed.EDIT_IMG} {postrow.displayed.DELETE_IMG} {postrow.displayed.IP_IMG} {postrow.displayed.REPORT_IMG}



Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/td&gt;



Unknown end tag for &lt;/tr&gt;







Unknown end tag for &lt;/tbody&gt;



Unknown end tag for &lt;/table&gt;



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





<div class="main-content" id="blog_comments">
<!-- BEGIN comment -->
<!-- BEGIN displayed -->
<div class="post"{comment.displayed.THANK_BGCOLOR}>
<a name="{comment.displayed.U_POST_ID}">

Unknown end tag for &lt;/a&gt;


<div id="p{comment.displayed.U_POST_ID}" class="posthead"{comment.displayed.THANK_BGCOLOR}>
<div class="blog_comment-avatar">
{comment.displayed.POSTER_AVATAR}


Unknown end tag for &lt;/div&gt;


<div class="h3">
<div class="blog_comment-title">
<a href="{comment.displayed.POST_URL}" name="{comment.displayed.U_POST_ID}">{comment.displayed.POST_SUBJECT}

Unknown end tag for &lt;/a&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<p class="author"><img src="{comment.displayed.MINI_POST_IMG}" alt="{comment.displayed.L_MINI_POST_ALT}" title="{comment.displayed.L_MINI_POST_ALT}" /> {comment.displayed.POST_DATE_NEW} {L_TOPIC_BY} {comment.displayed.POSTER_NAME}{comment.displayed.L_ONLINE}<strong>{postrow.displayed.COUNT_POSTS}

Unknown end tag for &lt;/strong&gt;


{postrow.displayed.ICON} <a href="{postrow.displayed.POST_URL}">{postrow.displayed.POST_SUBJECT}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/p&gt;


<div class="clearfix">

Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;



<div class="postbody"{comment.displayed.THANK_BGCOLOR}>

<div class="post-entry">
<div class="entry-content">
<!-- BEGIN switch_vote_active -->
<div class="vote gensmall">
<!-- BEGIN switch_vote -->
<div class="vote-button"><a href="{comment.displayed.switch_vote_active.switch_vote.U_VOTE_PLUS}">+

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/div&gt;


<!-- END switch_vote -->

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

<!-- BEGIN switch_no_bar -->
<div title="{comment.displayed.switch_vote_active.L_VOTE_TITLE}" class="vote-no-bar">----

Unknown end tag for &lt;/div&gt;


<!-- END switch_no_bar -->

<!-- BEGIN switch_vote -->
<div class="vote-button"><a href="{comment.displayed.switch_vote_active.switch_vote.U_VOTE_MINUS}">-

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/div&gt;


<!-- END switch_vote -->


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


<!-- END displayed -->
<!-- BEGIN hidden -->
<p class="p-hidden">{comment.hidden.MESSAGE}

Unknown end tag for &lt;/p&gt;


<!-- END hidden -->
<!-- END comment -->

<!-- BEGIN no_comment -->
<div class="post">
<div class="postbody no_comment">
<p style="text-align:center">{no_comment.L_NO_COMMENT}

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<!-- END no_comment -->

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



<!-- BEGIN switch_user_logged_in -->
<a name="quickreply">

Unknown end tag for &lt;/a&gt;


{QUICK_REPLY_FORM}
<!-- END switch_user_logged_in -->

<div id="pun-info" class="main">
<div class="main-content">
<div id="stats">
<p>{L_TABS_PERMISSIONS}
{S_AUTH_LIST}

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