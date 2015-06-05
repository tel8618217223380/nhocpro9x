cái này của tui làm rùi sài giờ share
hoàn toàn tự động (mod, người truy cập)
Hướng dẫn là vào Admin -> Display -> TemPlates -> Quản lý tổng thể -> viewforum\_body (xoá hết trong đó rồi để vào }
Lưu ý : không phải viewtopic nhé
demo

![http://i68.servimg.com/u/f68/15/18/46/10/share112.jpg](http://i68.servimg.com/u/f68/15/18/46/10/share112.jpg)


Lick download

```
{BOARD_INDEX}
<table width="100%" border="0" cellspacing="2" cellpadding="0" align="center">
<tr>
<td align="left" valign="middle" width="50">
<!-- BEGIN switch_user_authpost -->
<a href="{U_POST_NEW_TOPIC}" rel="nofollow"><img src="{POST_IMG}" id="{POST_IMG_ID}" alt="{L_POST_NEW_TOPIC}" border="0" />

Unknown end tag for &lt;/a&gt;


<!-- END switch_user_authpost -->


Unknown end tag for &lt;/td&gt;


<td class="nav" valign="middle" width="100%"><div class="nav"><a class="nav" href="{U_INDEX}">{L_INDEX}

Unknown end tag for &lt;/a&gt;

{NAV_CAT_DESC}

Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/td&gt;


<td class="nav" align="right" valign="bottom" nowrap="nowrap">
<span class="gensmall">
<script type="text/javascript">
//<![CDATA[
insert_plus_menu('f{FORUM_ID}&f={FORUM_ID}','{JS_SESSION_ID}', {JS_AUTH_FAVOURITES});
//]]>


Unknown end tag for &lt;/script&gt;




Unknown end tag for &lt;/span&gt;




Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/table&gt;


<br /><br />
{TOPICS_LIST_BOX}
<br /><br />
<div id="info_open" style="display:''">
<table class="tborder" width="100%" border="0" cellspacing="1" cellpadding="0">
<tr><td class="tcat" colspan="8" height="35"> Thông tin hiển thị

Unknown end tag for &lt;/td&gt;



Unknown end tag for &lt;/tr&gt;



<table class="tborder" cellpadding="6" cellspacing="1" border="0" width="100%" align="center">

<tr>
<td class="thead">X&#7871;p bài:

Unknown end tag for &lt;/td&gt;



<td class="thead">Thành viên đang online:

Unknown end tag for &lt;/td&gt;



<td class="thead">Ban qu&#7843;n tr&#7883; : {MEMBERS}

Unknown end tag for &lt;/td&gt;





Unknown end tag for &lt;/tr&gt;


<tr valign="top">
<td class="alt1">

<table cellpadding="0" cellspacing="1" border="0">
<tr valign="bottom">
<td class="smallfont" style="padding-right:6px">
<div><label for="sel_sort">X&#7871;p theo

Unknown end tag for &lt;/label&gt;



Unknown end tag for &lt;/div&gt;


<select name="sort" id="sel_sort">
<option value="title" >Thread Title

Unknown end tag for &lt;/option&gt;


<option value="lastpost" selected="selected">Last Post Time

Unknown end tag for &lt;/option&gt;



<option value="dateline" >Thread Start Time

Unknown end tag for &lt;/option&gt;


<option value="replycount" >S&#7889; l&#7847;n tr&#7843; l&#7901;i

Unknown end tag for &lt;/option&gt;


<option value="views" >S&#7889; l&#7847;n xem

Unknown end tag for &lt;/option&gt;



<option value="postusername" >Ng&#432;&#7901;i kh&#7903;i x&#432;&#7899;ng ch&#7911; &#273;&#7873;

Unknown end tag for &lt;/option&gt;


<option value="voteavg" >Thread Rating

Unknown end tag for &lt;/option&gt;




Unknown end tag for &lt;/select&gt;




Unknown end tag for &lt;/td&gt;


<td class="smallfont" style="padding-right:6px">
<div><label for="sel_order">Li&#7879;t kê

Unknown end tag for &lt;/label&gt;



Unknown end tag for &lt;/div&gt;



<select name="order" id="sel_order">
<option value="asc" >L&#7899;n d&#7847;n

Unknown end tag for &lt;/option&gt;


<option value="desc" selected="selected">Nh&#7887; d&#7847;n

Unknown end tag for &lt;/option&gt;




Unknown end tag for &lt;/select&gt;




Unknown end tag for &lt;/td&gt;



<td class="smallfont">
<div><label for="sel_daysprune">From The

Unknown end tag for &lt;/label&gt;



Unknown end tag for &lt;/div&gt;


<select name="daysprune" id="sel_daysprune">
<option value="1" >Last Day

Unknown end tag for &lt;/option&gt;


<option value="2" >Last 2 Days

Unknown end tag for &lt;/option&gt;


<option value="7" >Last Week

Unknown end tag for &lt;/option&gt;


<option value="10" >Last 10 Days

Unknown end tag for &lt;/option&gt;



<option value="14" >Last 2 Weeks

Unknown end tag for &lt;/option&gt;


<option value="30" >Last Month

Unknown end tag for &lt;/option&gt;


<option value="45" >Last 45 Days

Unknown end tag for &lt;/option&gt;


<option value="60" >Last 2 Months

Unknown end tag for &lt;/option&gt;


<option value="75" >Last 75 Days

Unknown end tag for &lt;/option&gt;


<option value="100" >Last 100 Days

Unknown end tag for &lt;/option&gt;



<option value="365" >Last Year

Unknown end tag for &lt;/option&gt;


<option value="-1" selected="selected">Beginning

Unknown end tag for &lt;/option&gt;




Unknown end tag for &lt;/select&gt;




Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;


<tr valign="bottom">
<td class="smallfont" colspan="2">

&nbsp;




Unknown end tag for &lt;/td&gt;


<td class="smallfont" align="right" style="padding-top:6px">
<input type="submit" class="button" value="Hi&#7879;n ch&#7911; &#273;&#7873;" />


Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/table&gt;





Unknown end tag for &lt;/td&gt;





<td class="alt1"><div class="smallfont">{LOGGED_IN_USER_LIST}

Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/td&gt;



<td class="alt1"><div class="smallfont">{MODERATORS}

Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/td&gt;





Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/table&gt;





Unknown end tag for &lt;/form&gt;












<div id="info_close" style="display:none">
<table class="tborder" width="100%" border="0" cellspacing="1" cellpadding="0">
<tr>
<td class="alt1" colspan="2" align="right" valign="top"><span class="smallfont"><a href="{U_MARK_READ}">{L_MARK_TOPICS_READ}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;


<tr>
<td class="alt2" colspan="2" valign="top"><span class="smallfont"><b>{LOGGED_IN_USER_LIST}

Unknown end tag for &lt;/b&gt;



Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;


<tr>
<td class="catBottom" colspan="2" height="28">
<table width="100%" border="0" cellspacing="0" cellpadding="0">
<tr>
<td class="navbar" valign="middle" width="100%"><span class="navbar">�<a class="navbar" href="{U_INDEX}">{L_INDEX}

Unknown end tag for &lt;/a&gt;

{nav_CAT_DESC_SECOND}

Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/td&gt;


<td align="right" valign="middle"><span class="smallfont"><a href="javascript:ShowHideLayer('info_open','info_close');"><img src="{TABS_MORE_IMG}" alt="+" align="middle" border="0" />

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;


<tr>
<td class="catBottom" colspan="2" height="28">
<table width="100%" border="0" cellspacing="0" cellpadding="0">
<tr>
<td class="nav" valign="middle" width="100%"><span class="nav">�<a class="nav" href="{U_INDEX}">{L_INDEX}

Unknown end tag for &lt;/a&gt;

{NAV_CAT_DESC_SECOND}

Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/td&gt;


<td align="right" valign="middle"><span class="gensmall"><a href="javascript:ShowHideLayer('info_open','info_close');"><img src="{TABS_MORE_IMG}" alt="+" align="middle" border="0" />

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/div&gt;

<br />
<form action="{S_JUMPBOX_ACTION}" method="get" name="jumpbox" onsubmit="if(document.jumpbox.f.value == -1){return false;}">
<table width="100%" border="0" cellspacing="2" cellpadding="0" align="center">
<tr>

<td align="left" valign="middle" width="50">
<!-- BEGIN switch_user_logged_in -->
<a href="{U_POST_NEW_TOPIC}" rel="nofollow"><img src="{POST_IMG}" id="{POST_IMG_ID}1" alt="{L_POST_NEW_TOPIC}" border="0" />

Unknown end tag for &lt;/a&gt;


<!-- END switch_user_logged_in -->


Unknown end tag for &lt;/td&gt;


<td align="right" nowrap="nowrap"><span class="smallfont">{L_JUMP_TO}: {S_JUMPBOX_SELECT} <input class="liteoption" type="submit" value="{L_GO}" />

Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/td&gt;





Unknown end tag for &lt;/tr&gt;



Unknown end tag for &lt;/table&gt;


<!-- BEGIN switch_legend --><div align="left" width="100%">
<table width="100%" border="0" cellspacing="0" cellpadding="0">
<tr>
<td colspan="2">
<table border="0" cellpadding="6" cellspacing="2" align="left">
<tr>
<td>
<img src="{FOLDER_NEW_IMG}" alt="{L_FOLDER_NEW_IMG}" border="0" /> <span class="smallfont">{L_FOLDER_NEW_IMG}

Unknown end tag for &lt;/span&gt;

<br />
<img src="{FOLDER_HOT_NEW_IMG}" alt="{L_FOLDER_HOT_NEW_IMG}" border="0" /> <span class="smallfont">{L_FOLDER_HOT_NEW_IMG}

Unknown end tag for &lt;/span&gt;

<br />
<img src="{FOLDER_LOCKED_NEW_IMG}" alt="{L_FOLDER_LOCKED_NEW_IMG}" border="0" /> <span class="smallfont">{L_FOLDER_LOCKED_NEW_IMG}

Unknown end tag for &lt;/span&gt;




Unknown end tag for &lt;/td&gt;


<td>
<img src="{FOLDER_IMG}" alt="{L_FOLDER_IMG}" border="0" /> <span class="smallfont">{L_FOLDER_IMG}

Unknown end tag for &lt;/span&gt;

<br />
<img src="{FOLDER_HOT_IMG}" alt="{L_FOLDER_HOT_IMG}" border="0" /> <span class="smallfont">{L_FOLDER_HOT_IMG}

Unknown end tag for &lt;/span&gt;

<br />
<img src="{FOLDER_LOCKED_IMG}" alt="{L_FOLDER_LOCKED_IMG}" border="0" /> <span class="smallfont">{L_FOLDER_LOCKED_IMG}

Unknown end tag for &lt;/span&gt;




Unknown end tag for &lt;/td&gt;


<td valign="top">
<img src="{FOLDER_ANNOUNCE_IMG}" alt="{L_FOLDER_ANNOUNCE_IMG}" border="0" /> <span class="smallfont">{L_FOLDER_ANNOUNCE_IMG}

Unknown end tag for &lt;/span&gt;

<br />
<img src="{FOLDER_STICKY_IMG}" alt="{L_FOLDER_STICKY_IMG}" border="0" /> <span class="smallfont">{L_FOLDER_STICKY_IMG}

Unknown end tag for &lt;/span&gt;

<br />


Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;



Unknown end tag for &lt;/table&gt;



Unknown end tag for &lt;/div&gt;


<!-- END switch_legend -->

<div align="left" width="100%">	<table class="tborder" width="300" border="0" cellspacing="1" cellpadding="0">
<tr>
<td class="tcat" valign="top" width="150" height="25">{L_TABS_PERMISSIONS}

Unknown end tag for &lt;/td&gt;



Unknown end tag for &lt;/tr&gt;

<tr>
<td class="alt1" valign="top"><span class="gensmall">{S_AUTH_LIST}

Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;





Unknown end tag for &lt;/table&gt;



Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/form&gt;


```