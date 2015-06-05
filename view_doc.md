demo: http://hotro27.forumvi.com/t2-topic#7

dạo qua 4skinfm xem thấy cái vew đẹp quá mới tìm hiểu cách thức sao làm dc như vậy
thì thật hay chỉ với css mà skin4fm làm dc thật là hay :D
mình ko rip lại và share mà mình sẽ làm 1 ví dụ để mọi người hiểu dc cách thức của nó
mình ko biết là dùng cách nào nhưng mình đoán là dùng
```
{postrow.displayed.COUNT_POSTS}
```

đó là thứ tự của topic và dc hiện thị ở dạng số



trong vewtopic có đoạn
```

<div class="post number"{postrow.displayed.THANK_BGCOLOR}>
```
và sửa thành
```

<div class="post number{postrow.displayed.COUNT_POSTS}"{postrow.displayed.THANK_BGCOLOR}>
```
như vậy ta đã có clas theo số thứ tự để mình có thể chỉnh css cho comen đầu tiên ở dạng ngang

sau đó khi ta có class theo số thứ tự thì ta có thể dùng css như sau
.number1 .postmain {tính năng-(mình ko biết gọi là gì hix)}
thôi bạn xem code ở dưới đây thì hiểu rõ hơn

lưu ý là bài này mình hướng dẫn theo cách hiểu của mình còn skin4fm dùng có đúng thế ko thì mình ko biết nữa :( hix
mình chỉ hưởng dẫn các bạn cách sửa mình ko rip lại y nguyên nó đâu lên các bạn đừng thắc mắc sao ko giống skin4fm vì mình chưa xin phép admin bên đó lên ko rip :D


demo đây là mẫu vew mình đã sửa lại
http://hotro27.forumvi.com/t2-topic#7


```

<script type="text/javascript">//<![CDATA[
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


<style>
/*---firstPost---*/
.number1 .postmain {margin-left: 0;position: relative;}
.number1 .postmain .user {margin-left: 0;float: left;width: 100%;background: #F7F7F7;border-bottom: 1px solid #DDD;height: 150px;}
.number1 .postmain .user .user-ident {display: block;float: left;padding: 10px;padding-top: 0;}
.number1 .postmain .user .user-basic-info a img {width: 120px;height: 120px;padding: 5px;background: white;border-radius: 4px;border: 1px solid #DDD;}
.number1 .postmain .user .user-info {display: block;float: right;padding: 10px;}
.number1 .postmain .user .user-basic-info {display: table;}
.number1 .postmain .user .user-basic-info a { display: table-cell;}
.number1 .postmain .user .user-basic-info .rankn {top: -97px;position: relative;padding: 10px;display: block;}
.number1 .postmain .user .user-basic-info .rankn img{width: 90px;}
.number1 .postmain .postbody {padding-top: 10px;}
.postmain a, .entry-content table a:link, .quote, .codebox , .posthead {z-index: 100 !important;position: relative;}



Unknown end tag for &lt;/style&gt;




width: 90px;
<!-- BEGIN switch_user_logged_in -->
<div id="pun-visit" class="clearfix">
<ul>
<!-- BEGIN switch_plus_menu -->
<li>
<script type="text/javascript">//<![CDATA[
var url_favourite = '{switch_user_logged_in.U_FAVOURITE_JS_PLUS_MENU}';
var url_newposts = '{U_NEWPOSTS_JS_PLUS_MENU}';
var url_egosearch = '{U_EGOSEARCH_JS_PLUS_MENU}';
var url_unanswered = '{U_UNANSWERED_JS_PLUS_MENU}';
var url_watchsearch = '{U_WATCHSEARCH_JS_PLUS_MENU}';
var url_tellfriend = '{U_TELLFRIEND_JS_PLUS_MENU}';
insert_plus_menu_new('f{FORUM_ID}&amp;t={TOPIC_ID}','{JS_SESSION_ID}', {JS_AUTH_FAVOURITES});
//]]>


Unknown end tag for &lt;/script&gt;




Unknown end tag for &lt;/li&gt;


<!-- END switch_plus_menu -->
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


<!-- BEGIN switch_twitter_btn -->
<span id="twitter_btn" style="margin-left: 6px; ">
<a href="http://twitter.com/share" class="twitter-share-button" data-count="horizontal">Tweet

Unknown end tag for &lt;/a&gt;


<script type="text/javascript" src="http://platform.twitter.com/widgets.js">

Unknown end tag for &lt;/script&gt;




Unknown end tag for &lt;/span&gt;


<!-- END switch_twitter_btn -->
<!-- BEGIN switch_fb_likebtn -->
<span id="fb_likebtn" style="margin-left: 6px; ">
<iframe src="http://www.facebook.com/plugins/like.php?href={FORUM_URL}{TOPIC_URL}&amp;layout=button_count&amp;show_faces=false&amp;width=450&amp;action=like&amp;colorscheme=light&amp;height=21" scrolling="no" frameborder="0" style="border:none; overflow:hidden; width:auto; height:21px;" allowTransparency="true">

Unknown end tag for &lt;/iframe&gt;




Unknown end tag for &lt;/span&gt;


<!-- END switch_fb_likebtn -->


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
<div class="post number{postrow.displayed.COUNT_POSTS}"{postrow.displayed.THANK_BGCOLOR}>
<a name="{postrow.displayed.U_POST_ID}">

Unknown end tag for &lt;/a&gt;


<div class="postmain"{postrow.displayed.THANK_BGCOLOR}>
<div id="p{postrow.displayed.U_POST_ID}" class="posthead"{postrow.displayed.THANK_BGCOLOR}>
<h2>
<strong>{postrow.displayed.COUNT_POSTS}

Unknown end tag for &lt;/strong&gt;


{postrow.displayed.ICON} <a href="{postrow.displayed.POST_URL}">{postrow.displayed.POST_SUBJECT}

Unknown end tag for &lt;/a&gt;

 {postrow.displayed.POST_DATE_NEW}


Unknown end tag for &lt;/h2&gt;




Unknown end tag for &lt;/div&gt;



<div class="postbody"{postrow.displayed.THANK_BGCOLOR}>
<div class="user">
<div class="user-ident">


<div class="user-basic-info">



{postrow.displayed.POSTER_AVATAR}<br />
<span class="rankn">
<p> {postrow.displayed.POSTER_NAME}

Unknown end tag for &lt;/p&gt;


<p> {postrow.displayed.POSTER_RANK_NEW}  

Unknown end tag for &lt;/p&gt;

  <p> {postrow.displayed.RANK_IMAGE}  

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/span&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<div class="user-info">
{postrow.displayed.ONLINE_IMG}
<!-- BEGIN profile_field -->
{postrow.displayed.profile_field.LABEL}{postrow.displayed.profile_field.CONTENT}{postrow.displayed.profile_field.SEPARATOR}
<!-- END profile_field -->
{postrow.displayed.POSTER_RPG}


Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;



<div class="post-entry">
<div class="entry-content">
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
<div>
<div>{postrow.displayed.MESSAGE}

Unknown end tag for &lt;/div&gt;


<!-- BEGIN switch_attachments -->
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
<em><strong>{postrow.displayed.switch_attachments.switch_post_attachments.switch_no_dl_att.TEXT_NO_DL}

Unknown end tag for &lt;/strong&gt;



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
<div class="clear">

Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<p>
{postrow.displayed.EDITED_MESSAGE}


Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;



<!-- BEGIN switch_signature -->
<div class="sig-content">
{postrow.displayed.SIGNATURE_NEW}


Unknown end tag for &lt;/div&gt;


<!-- END switch_signature -->

<div class="postfoot">
<div class="user-contact">
{postrow.displayed.PROFILE_IMG} {postrow.displayed.PM_IMG} {postrow.displayed.EMAIL_IMG}<!-- BEGIN contact_field --> {postrow.displayed.contact_field.CONTENT}<!-- END contact_field -->


Unknown end tag for &lt;/div&gt;


<div class="post-options">
{postrow.displayed.THANK_IMG} {postrow.displayed.MULTIQUOTE_IMG} {postrow.displayed.QUOTE_IMG} {postrow.displayed.EDIT_IMG} {postrow.displayed.DELETE_IMG} {postrow.displayed.IP_IMG} {postrow.displayed.REPORT_IMG}


Unknown end tag for &lt;/div&gt;


<div style="clear:both;">

Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<!-- BEGIN first_post_br -->


Unknown end tag for &lt;/div&gt;


<hr id="first-post-br" />
<div class="main-content topic">
<!-- END first_post_br -->
<!-- END displayed -->
<!-- BEGIN hidden -->
<p class="p-hidden">{postrow.hidden.MESSAGE}

Unknown end tag for &lt;/p&gt;


<!-- END hidden -->
<!-- END postrow -->


Unknown end tag for &lt;/div&gt;



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

<!-- BEGIN switch_forum_rules -->
<div class="main" id="forum_rules">
<div class="main-head clearfix">
<p class="h2">{L_FORUM_RULES}

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


<table class="main-content frm">
<tr>
<!-- BEGIN switch_forum_rule_image -->
<td class="logo">
<img src="{RULE_IMG_URL}" />


Unknown end tag for &lt;/td&gt;


<!-- END switch_forum_rule_image -->
<td class="rules entry-content">
{RULE_MSG}


Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/div&gt;


<!-- END switch_forum_rules -->

<!-- BEGIN switch_user_logged_in -->
<a name="quickreply">

Unknown end tag for &lt;/a&gt;


{QUICK_REPLY_FORM}
<!-- END switch_user_logged_in -->

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