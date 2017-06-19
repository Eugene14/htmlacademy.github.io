<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<HTML expr:dir='data:blog.languageDirection'>
<head>

<b:if cond='data:blog.pageType == &quot;item&quot;'>
    <b:if cond='data:blog.postImageThumbnailUrl'>
      <b:if cond='data:blog.metaDescription'>
        <meta content='summary' name='twitter:card'/>
        <meta content='@LargehiphopCom' name='twitter:site'/>
        <meta content='@LargehiphopCom' name='twitter:creator'/>
        <meta expr:content='data:blog.pageName' name='twitter:title'/>
        <meta expr:content='data:blog.metaDescription' name='twitter:description'/>
        <meta expr:content='data:blog.postImageThumbnailUrl' name='twitter:image:src'/>
        <meta expr:content='data:blog.homepageUrl' name='twitter:domain'/>
      </b:if>
    </b:if>
</b:if>

<!-- [ Meta Tag SEO ] -->
<meta charset='utf-8'/>
<meta content='width=device-width, initial-scale=1' name='viewport'/>
<meta content='blogger' name='generator'/>
<meta content='text/html; charset=UTF-8' http-equiv='Content-Type'/>
<link href='http://www.blogger.com/openid-server.g' rel='openid.server'/>
<link expr:href='data:blog.homepageUrl' rel='openid.delegate'/>
<link expr:href='data:blog.url' rel='canonical'/>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<title><data:blog.pageTitle/></title>
<b:else/>
<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
<title><data:blog.pageName/> - <data:blog.title/></title>
</b:if></b:if>
<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
<title>Page Not Found - <data:blog.title/></title>
</b:if>
<b:if cond='data:blog.pageType == &quot;archive&quot;'>
<meta content='noindex' name='robots'/>
</b:if>
<b:if cond='data:blog.searchLabel'>
<meta content='noindex,nofollow' name='robots'/>
</b:if>
<b:if cond='data:blog.isMobile'>
<meta content='noindex,nofollow' name='robots'/>
</b:if>
<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
<meta expr:content='data:blog.metaDescription' name='description'/>
<script type='application/ld+json'>{ &quot;@context&quot;: &quot;http://schema.org&quot;, &quot;@type&quot;: &quot;WebSite&quot;, &quot;url&quot;: &quot;<data:blog.homepageUrl/>&quot;, &quot;potentialAction&quot;: { &quot;@type&quot;: &quot;SearchAction&quot;, &quot;target&quot;: &quot;<data:blog.homepageUrl/>?q={search_term}&quot;, &quot;query-input&quot;: &quot;required name=search_term&quot; } }</script>
<b:if cond='data:blog.homepageUrl != data:blog.url'>
<meta expr:content='data:blog.pageName + &quot;, &quot; + data:blog.pageTitle + &quot;, &quot; + data:blog.title' name='keywords'/>
</b:if></b:if>
<b:if cond='data:blog.url == data:blog.homepageUrl'>
<meta content='Simplify Responsive Blogger Template' name='keywords'/></b:if>
<link expr:href='data:blog.homepageUrl + &quot;feeds/posts/default&quot;' expr:title='data:blog.title + &quot; - Atom&quot;' rel='alternate' type='application/atom+xml'/>
<link expr:href='data:blog.homepageUrl + &quot;feeds/posts/default?alt=rss&quot;' expr:title='data:blog.title + &quot; - RSS&quot;' rel='alternate' type='application/rss+xml'/>
<link expr:href='&quot;http://www.blogger.com/feeds/&quot; + data:blog.blogId + &quot;/posts/default&quot;' expr:title='data:blog.title + &quot; - Atom&quot;' rel='alternate' type='application/atom+xml'/>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<b:if cond='data:blog.postImageThumbnailUrl'>
<link expr:href='data:blog.postImageThumbnailUrl' rel='image_src'/>
</b:if></b:if>
<link expr:href='data:blog.url' hreflang='x-default' rel='alternate'/>
<link href='/favicon.ico' rel='icon' type='image/x-icon'/>
<link href='https://plus.google.com/xxxxx/posts' rel='publisher'/>
<link href='https://plus.google.com/xxxxx/about' rel='author'/>
<link href='https://plus.google.com/xxxxx' rel='me'/>
<meta content='xxxxx' name='google-site-verification'/>
<meta content='xxxxx' name='msvalidate.01'/>
<meta content='xxxxx' name='alexaVerifyID'/>
<meta content='Indonesia' name='geo.placename'/>
<meta content='xxxxx' name='Author'/>
<meta content='general' name='rating'/>
<meta content='id' name='geo.country'/>
<!-- [ Social Media Meta Tag ] -->
<b:if cond='data:blog.url == data:blog.homepageUrl'> 
<b:if cond='data:blog.pageType == &quot;item&quot;'> 
<b:if cond='data:blog.pageType == &quot;static_page&quot;'>  
<b:if cond='data:blog.url'>
<meta expr:content='data:blog.url' property='og:url'/>
</b:if>
<meta expr:content='data:blog.title' property='og:site_name'/>
<b:if cond='data:blog.pageName'>
<meta expr:content='data:blog.pageName' property='og:title'/>
</b:if></b:if></b:if></b:if>
<meta expr:content='data:blog.pageTitle' property='og:title'/>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<meta content='article' property='og:type'/>
<b:else/>
<meta content='website' property='og:type'/>
</b:if>
<meta expr:content='data:blog.canonicalUrl' property='og:url'/>
<b:if cond='data:blog.postImageUrl'>
<meta expr:content='data:blog.postImageUrl' property='og:image'/>
<b:else/>
<b:if cond='data:blog.postImageThumbnailUrl'>
<meta expr:content='data:blog.postThumbnailUrl' property='og:image'/>
<b:else/>
<meta expr:content='data:blog.blogspotFaviconUrl' property='og:image'/>
</b:if></b:if>
<b:if cond='data:blog.metaDescription'>
<meta expr:content='data:blog.metaDescription' property='og:description'/>
<b:else/>
<meta content='Simplify Responsive Blogger Template' property='og:description'/>
</b:if>
<meta expr:content='data:blog.title' property='og:site_name'/>
<meta content='https://www.facebook.com/URL-PROFILE-FB' property='article:author'/>
<meta content='https://www.facebook.com/URL-FANPAGE-FB' property='article:publisher'/>
<meta content='562901580420523' property='fb:app_id'/>
<meta content='100005787193074' property='fb:admins'/>
<meta content='en_US' property='og:locale'/>
<meta content='en_GB' property='og:locale:alternate'/>
<meta content='id_ID' property='og:locale:alternate'/>
<meta content='summary' name='twitter:card'/>
<meta expr:content='data:blog.pageTitle' name='twitter:title'/>
<meta content='@ArlinaDesign' name='twitter:site'/>
<meta content='@ArlinaDesign' name='twitter:creator'/>
<b:skin><![CDATA[
/*
Name             : simplify Custom Responsive 2016
Theme Published  : 07-06-2016
Type             : Personal Blog
Style            : Minimalist
Designer         : Arlina Design
Designer url     : www.arlinadzgn.com
Thanks to        : All supported
License          : This free Blogger template is licensed under the Creative Commons Attribution 4.0 License, which permits both personal and commercial use.
*/
/* CSS Reset */
html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,embed,figure,figcaption,footer,header,hgroup,menu,nav,output,ruby,section,summary,time,mark,audio,video{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline;}
/* HTML5 */
article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block;}body{line-height:1;display:block;}*{margin:0;padding:0;}html{display:block;}ol,ul{list-style:none;}blockquote,q{quotes:none;}blockquote:before,blockquote:after,q:before,q:after{background:transparent;}table{border-collapse:collapse;border-spacing:0;}*,*:before, *:after {-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;}ins{background:#fff;}
/* Body Layout */
body#layout ul,#layout ul {display:none;}
body#layout #outer-wrapper, body#layout .post-inner, body#layout .sidebar, body#layout .sidebartop {padding:0;}
body#layout #wrapper, body#layout .post-inner, body#layout .sidebar-inner {padding:0;}
body#layout .header-wrapper {margin-top:0;}
body#layout #header {min-height:0px;width:100%;}
body#layout #headerdua {width:30%;float:left;}
body#layout .sosial-atas li{display:none}
#layout,#layout .widget-content,#layout .add_widget {border:none;}
body#layout .add_widget {border:1px solid #ddd;}
#layout .add_widget a {color:#111;}
#layout #header{min-height:0px;width:100%;margin:10px 0 0 0;}
#layout #footer-wrapper .footer-column{width:33.33%;float:left}
#layout #main-wrapper{width:70%;float:left}
#layout #sidebar-wrapper{width:30%;left:0;padding:0;float:right}
#layout .draggable-widget .widget-wrap2 {background:#c1cfd9;}
#layout #banner,#layout #banner2 {background-color:#444;padding:20px 0!important;margin-bottom:20px;}
#layout #banner .widget,#layout #banner2 .widget{width:80%;margin:5px auto!important;overflow:hidden;float:none}
#layout #banner .add_widget,#layout #banner2 .add_widget{width:80%;margin:5px auto!important;overflow:hidden;float:none}
#footer-xwidget .footer-widget {width:31.7%;float:left;margin-left:10px;}
#footer-wrapper {overflow:hidden;margin:0 auto 20px auto;padding:20px 0 0;}
#layout #footer-wrapper #column1,#layout #footer-wrapper #column2{margin:0}
/* Layout */
body {background:#ededed;font-family:'Roboto',sans-serif;font-size:14px;font-weight:400;text-align:left;color:#000;margin:0;padding:0;}
.navbar,.post-feeds,.feed-links{display:none;}.section,.widget{margin:0;padding:0;}strong,b{font-weight:bold;padding:0;}cite,em,i{font-style:italic;}a:link,a:visited {color:#138be6;text-decoration:none;transition:all .3s}a:hover,a:hover:visited {color:#000}a img{border:none;border-width:0;outline:none;}img{max-width:100%;vertical-align:middle;border:0;}abbr,acronym{border-bottom:1px dotted;cursor:help;}sup,sub{vertical-align:baseline;position:relative;top:-.4em;font-size:86%;}sub{top:.4em;}small{font-size:86%;}kbd{display:inline-block;font-size:90%;color:#138be6;}mark{background-color:#ffce00;color:#182025;}p,blockquote,pre,table,figure,hr,form,ol,ul,dl{margin:1.5em 0;}hr{height:1px;border:none;background-color:#999;}code,kbd,pre,samp{font-family:monospace,monospace;}
pre{white-space:pre;word-wrap:normal;overflow:auto;font-size:13px;margin:0;}*:focus {outline:0!important;}h1,h2,h3,h4,h5,h6{font-weight:700;line-height:normal;}h1{font-size:200%}h2{font-size:180%}h3{font-size:160%}h4{font-size:140%}h5{font-size:120%}h6{font-size:100%}
.post-body blockquote{position:relative;background:#f8f8f9;border-left:none;padding:20px 55px;color:#676767;font-weight:700;line-height:22px}
.post-body blockquote:before{color:#bbb;position:absolute;top:15px;left:20px;display:inline-block;font-family:'FontAwesome';font-style:normal;font-weight:normal;line-height:1;content:"\f10d";font-size:20px;-webkit-font-smoothing:antialiased}
.post-body blockquote:after{color:#bbb;position:absolute;bottom:15px;right:20px;display:inline-block;font-family:'FontAwesome';font-style:normal;font-weight:normal;line-height:1;content:"\f10e";font-size:20px;-webkit-font-smoothing:antialiased}
.post-body h1{font-size:200%}.post-body h2{font-size:180%}.post-body h3{font-size:160%}.post-body h4{font-size:140%}.post-body h5{font-size:120%}.post-body h6{font-size:100%}
.post-body h1 b,.post-body h2 b,.post-body h3 b,.post-body h4 b,.post-body h5 b,.post-body h6 b{font-weight:700;}
input,button,select,textarea{font-size:100%;line-height:normal;vertical-align:baseline;}
textarea{display:block;box-sizing:border-box;}
input.placeholder_text,textarea.placeholder_text{color:#888}
input::-webkit-input-placeholder,textarea::-webkit-input-placeholder,input:-moz-placeholder,textarea:-moz-placeholder,input.placeholder_text,textarea.placeholder_text{color:#444}[placeholder]:focus::-webkit-input-placeholder{transition:opacity .5s .5s ease;opacity:0}
.post ul li span{position:relative;display:block;padding:0;margin:.5em 0 .5em 2em;text-decoration:none;}
ol {counter-reset:li;list-style:none;padding:0;margin:0;}
ol ol {margin: 0 0 0 2em;}
.post ol li{position:relative;display:block;padding:0;margin:.5em 0 .5em 2em;background:#fff;text-decoration:none;}
.post ol li:before {content:counter(li);counter-increment:li;position:absolute;left:-2.5em;height:2em;width:2em;text-align:center;}
.post-body ul {position:relative;display:block;padding:0;margin:.5em 0 .5em 1.5em;text-decoration:none;}
/* Post Table */
.post-body table {width:100%;}
.post-body table td,.post-body table caption{background:#fff;border:1px solid rgba(0,0,0,0.05);padding:10px;text-align:left;vertical-align:top}
.post-body table th{background:#e74c3c;color:#fff;border:1px solid rgba(0,0,0,0.05);border-bottom:0;padding:10px;text-align:left;vertical-align:top}
.post-body table.tr-caption-container {border:1px solid rgba(0,0,0,0.14);margin:0;}
.post-body th{font-weight:700;}
.post-body table caption{border:none;font-style:italic;}
.post-body td, .post-body th{vertical-align:top;text-align:left;font-size:13px;padding:3px 5px;border:1px solid #97b28e;}
.post-body th{}
.post-body th:hover{color:#fff;}
.post-body td a{color:#444;}
.post-body td a:hover{color:#cf4d35;}
.post-body table.tr-caption-container td{border:0;padding:8px;background:#fff;line-height:17px;overflow:hidden;text-align:center;text-overflow:ellipsis;white-space:nowrap;font-weight:700;color:#000;}
.post-body table.tr-caption-container, .post-body table.tr-caption-container img, .post-body img {max-width:100%;height:auto;}
.post-body li {list-style-type:square;}
.post-body td.tr-caption {color:#666;font-size:80%;padding:0px 8px 8px!important;}
.sr {visibility:hidden;width:0;height:0;}
.clear{clear:both}
html {-webkit-font-smoothing:antialiased;}
::selection {background:#effdca;text-shadow:none;}
]]></b:skin>
<b:if cond='data:blog.isMobileRequest == &quot;false&quot;'>
<style type='text/css'>
.makesticking{position:fixed!important;top:0;z-index:99;-webkit-transform:translateZ(0);margin:auto;}
#headersticky {background:#fff;position:relative;display:block;padding:0 20px;height:83px;margin:0 auto;max-width:970px;border-bottom:1px solid rgba(0,0,0,0.1);border-top:1px solid rgba(0,0,0,0.1)}
#headersticky.makesticking{height:62px;box-shadow:0 2px 1px 0 rgba(0,0,0,0.06);}
#headersticky.makesticking p.description{display:none}
#headersticky.makesticking nav#simplify-nav a{line-height:62px}
#headersticky.makesticking nav#simplify-nav li li,#headersticky.makesticking nav#simplify-nav li li &gt; a{line-height:36px}
</style>
</b:if>
<style type='text/css'>
/* Custom Cookies Info Dark */
.cookie-choices-info{background-color:rgba(56,66,75,.97)!important;line-height:normal!important;top:initial!important;bottom:0!important;font-family:inherit!important;-webkit-transform:translateZ(0);}
.cookie-choices-info .cookie-choices-text{font-size:14px!important;color:#cee6ea!important}
.cookie-choices-info .cookie-choices-button{font-weight:normal!important;color:#fff!important;margin-left:5px!important;padding:3px 6px!important;background:#f64c3b!important;letter-spacing:.8px;transition:all .4s linear}
.cookie-choices-info .cookie-choices-button:nth-child(2){background:#f68c2e!important;transition:all .4s linear}
.cookie-choices-info .cookie-choices-button:hover,.cookie-choices-info .cookie-choices-button:nth-child(2):hover{background:#282f36!important;transition:all .1s linear}
/* Arlina Fixed Layout */
.CSS_LIGHTBOX {z-index:999999!important;}
.CSS_LIGHTBOX_BG_MASK_TRANSPARENT {opacity:.95!important;}
.CSS_LIGHTBOX_SCALED_IMAGE_IMG {width:auto!important;max-width:100%;box-shadow:0 0 10px rgba(0,0,0,0.1);}
.CSS_LIGHTBOX_BTN_CLOSE {background: url(&#39;https://4.bp.blogspot.com/-cmZSAe4hgWI/V0K-3C5xiHI/AAAAAAAAG90/2btatUgRsM4qf8HIc7QweuToTkRqRNeuACLcB/s1600/delete.png&#39;) no-repeat!important;width:32px!important;height:32px!important;top:30px!important;opacity:0.7;transition:all .3s;}
.CSS_LIGHTBOX_BTN_CLOSE:hover{opacity:1;}
.CSS_LIGHTBOX_BTN_CLOSE_POS {right:10px!important;}
.CSS_LIGHTBOX_BG_MASK{background-color:rgba(0,0,0,0.8)!important}
.CSS_LIGHTBOX_FILMSTRIP{background-color:rgba(0,0,0,0.5)!important}
.quickedit,#ContactForm1,#ContactForm1 br {display:none}
.post,.widget-content,.breadcrumbs,.banner .widget,.banner2 .widget,#blog-pager,#comments{}
.banner .widget-content,.banner2 .widget-content,#LinkList215 .widget-content{}
#BlogArchive1 li.archivedate {padding:0;}
#BlogArchive1 #ArchiveList ul.posts li {padding:0 0 0 22px;line-height:normal;}
#ArchiveList{padding:10px}
#ArchiveList select{width:100%;padding:10px;margin-bottom:5px;border:1px solid rgba(201,201,201,0.52);font-size:13px;font-family:&#39;Roboto&#39;,sans-serif}
/* Arlina Template Wrapper */
.maxwrap {max-width:970px;margin:0 auto;}
#wrapper{background:#fff;display:block;position:relative;overflow:hidden;max-width:970px;margin:0 auto;padding:0;}
#content-wrapper {display:block;position:relative;overflow:hidden;padding:0;}
/* Arlina Top Menu */
.simplify-menu_wrapper{background:#fff;width:100%;margin:0 auto;max-width:970px;}
.simplify-menu ul li{position:relative;list-style:none;display:inline-block;float:left;border-right:1px solid rgba(0,0,0,0.05);transition:all .6s}
.simplify-menu{float:left;width:auto;height:auto;padding:0;margin:0 5px 0 0;font-size:100%;font-weight:700}
.simplify-menu ul{margin:0 auto;padding:0;}
.simplify-menu ul li a{color:#000;padding:0 15px;line-height:38px;text-decoration:none;text-transform:uppercase;font-size:11px;transition:all .6s}
.simplify-menu ul li:first-child{border-left:1px solid rgba(0,0,0,0.05)}
.simplify-menu ul li a i{margin:0 5px 0 0;font-weight:normal;}
.search-box{display:none;width:230px;height:27px;float:right;padding:0;position:relative;transition:all .1s}
#search-form,#searchform,.search-button{border:0;line-height:27px}
#searchform{position:relative;border:0;margin:9px 0 0 0}
#search-form{background:rgba(255,255,255,1);border-radius:3px;color:rgba(0,0,0,.5);width:100%;padding:0 30px 0 10px;height:27px;line-height:27px;font-size:13px;margin:0;transition:all .3s}
.search-button{background:none;width:30px;padding:0;text-align:center;margin:0;top:0;right:0;font-size:13px;color:#666;position:absolute;border-radius:0;text-shadow:none;box-shadow:none}
#search-form:focus,#search-form:hover,.search-button:focus,.search-button:hover{background:rgba(255,255,255,.95);border:none;outline:0;color:rgba(0,0,0,.5)}
.sosial-atas{float:right;width:auto;height:auto;padding:0;font-weight:400}
.sosial-atas li{float:left;list-style:none;display:inline-block;transition:all .6s}
.sosial-atas li a{display:block;color:#000;padding:0 10px;border-right:1px solid rgba(0,0,0,0.05);text-decoration:none;text-transform:uppercase;line-height:38px;font-size:11px;font-weight:700;transition:initial}
.sosial-atas li:last-child a{border-right:0;padding:0 20px;}
.sosial-atas li:nth-child(1) a{border-left:1px solid rgba(0,0,0,0.05);}
.sosial-atas li:nth-child(1) a:hover{background:#516ca4;color:#fff;}
.sosial-atas li:nth-child(2) a:hover{background:#00baff;color:#fff;}
.sosial-atas li:nth-child(3) a:hover{background:#f20000;color:#fff;}
.sosial-atas li:nth-child(4) a:hover{background:#cc181e;color:#fff;}
.sosial-atas li:nth-child(5) a:hover{background:#87b3f7;color:#fff;}
.sosial-atas li:nth-child(6) a:hover{background:#e73339;color:#fff;}
.sosial-atas li:nth-child(7) a:hover{background:#f39c12;color:#fff;}
.sosial-atas li a i{width:15px;text-align:center;font-weight:normal}
.simplify-menu ul li:hover,.simplify-menu ul li:hover a,.sosial-atas li a:hover,.sosial-atas li:hover a{background:rgba(0,0,0,0.03);;}
.simplify-menu ul li a:hover,.simplify-menu ul li:hover a,.sosial-atas li a:hover,.sosial-atas li:hover a{color:rgba(0,0,0,1)}
/* Arlina Header Wrapper */
#header{background:#fff;position:relative;display:block;margin:0 auto;max-width:970px;}
#header .title{font-size:210%;margin:10px 0 0 0;padding:0;display:inline-block;width:100%;max-width:240px;}
#header .title a{color:#000;}
#header .title a:hover {color:#138be6;}
#header p.description{display:inline-block;font-size:90%;margin:5px 0 0 0;line-height:normal;}
.header img {display:block;height:auto;}
#headerdua {float:left;}
/* Arlina Main Navigation */
#simplify-nav{font-size:0;white-space:nowrap;padding:0;margin:0 auto;float:right}
#simplify-nav ul.menus{height:auto;overflow:hidden;position:absolute;z-index:99;display:none}
#simplify-nav a{display:block;position:relative;line-height:82px;padding:0 13px;color:#000;font-size:13px;font-weight:700;}
#simplify-nav ul,#simplify-nav li {margin:0 auto;padding:0;list-style:none}
#simplify-nav li{position:relative;float:left;line-height:82px;display:block;margin:0}
#simplify-nav input {display:none;margin:0;padding:0;width:80px;height:45px;opacity:0;cursor:pointer}
#simplify-nav label {display:none;width:55px;height:48px;line-height:48px;text-align:center}
#simplify-nav label span {font-size:16px;position:absolute;left:55px}
#simplify-nav ul.menus li {display:block;width:100%;text-transform:none;text-shadow:none;}
#simplify-nav ul.menus a {color:#138be6;line-height:55px}
#simplify-nav li a:hover,#simplify-nav ul.menus a:hover {background:rgba(0,0,0,0.03);color:#000;}
#simplify-nav li ul{display:none;background:#fff;margin:0;height:auto;position:absolute;top:99%;left:0;z-index:12;box-shadow:0 3px 10px 1px rgba(0,0,0,0.14);}
#simplify-nav li:hover ul.menus,#simplify-nav li:hover &gt; ul{visibility:visible;opacity:1;}
#simplify-nav li li{display:block;float:none;font-size:13px;height:auto;clear:both;margin-left:0;line-height:36px;border-bottom:1px solid rgba(0,0,0,0.05)}
#simplify-nav li li:last-child {border:0;}
#simplify-nav li ul ul {left:100%;top:0}
#simplify-nav li li &gt; a{background:#fff;color:#666;display:block;margin:0;text-decoration:none;text-transform:none;min-width:200px;line-height:36px;padding:0 13px;font-size:11px;border:0;;border-left:3px solid transparent;margin-top:0}
#simplify-nav li li a:hover {background:#fafafa;color:#000;}
/* Arlina Post Wrapper */
#main-wrapper{width:64.98%;float:left;margin:0;padding:0;word-wrap:break-word;border-right:1px solid rgba(0,0,0,0.1)}
.main .Blog{border-bottom-width:0}
.main .widget{margin:0;padding:0}
.date-header{display:none!important}
h1.post-title.entry-title,h2.post-title.entry-title {font-size:18px;margin:0 0 15px;}
h1.post-title.entry-title a,h2.post-title.entry-title a{color:#000;}
h1.post-title.entry-title a:hover,h2.post-title.entry-title a:hover{color:#138be6;}
.post{background:#fff;position:relative;margin:0 0 20px 0;padding:0}
.post-body {margin:0;line-height:1.7em;text-align:left;font-size:15px;padding:20px;}
.post-info abbr {border:0;}
.post-timestamp,.author-info,.comment-info,.label-info{padding:0 10px 0 0}
.post-body img,.post-body video,.post-body object {background:#fafafa;max-width:100%}
.breadcrumbs{overflow:hidden;white-space:nowrap;text-overflow:ellipsis;font-size:12px;padding:20px;border-bottom:1px solid rgba(0,0,0,0.14);font-weight:700;}
.breadcrumbs a{color:#000;margin:0 2px;line-height:normal;}
.breadcrumbs .breadhome a{margin:0 5px 0 0}
.breadcrumbs .breadlabel:last-child{margin:0 0 0 4px}
.breadcrumbs a:hover{color:#138be6;}
.post-footer{line-height:1.6em}
.post-footer a{color:#97b28e;}
.feed-links{clear:both;line-height:2.5em;}
/* Arlina Sidebar Wrapper */
#sidebar-wrapper{padding:20px;width:35%;float:right;word-wrap:break-word;overflow:hidden}
#sidebar-wrapper h2,#sidebar-wrapper h3,#sidebar-wrapper h4{position:relative;overflow:hidden;margin:0;font-size:1rem;vertical-align:middle;padding:0 0 10px 0;border-bottom:1px solid rgba(0,0,0,.1);}
#sidebar-wrapper h2 span,#sidebar-wrapper h3 span,#sidebar-wrapper h4 span{display:inline-block;vertical-align:middle}
#sidebar-wrapper h2:after,#sidebar-wrapper h3:after,#sidebar-wrapper h4:after{content:&#39;&#39;;display:inline-block;position:absolute;height:15px;top:0;margin:3px 0 12px 10px;width:100%;background:url(http://4.bp.blogspot.com/-R2WTW6O9E1o/VX7dqIGT1eI/AAAAAAAACc4/pyvQDMMLX3E/s1600/repeat-bg.png)repeat}
#sidebar-wrapper .widget ul{margin:0;padding:0}
.widget-content{margin:0;padding:10px 0;overflow:hidden}
.sidebar,.sidebartop {line-height:1.5em;padding:0}
.sidebar ul,.sidebartop ul {padding:0;margin:0}
.BlogArchive #ArchiveList ul li {text-indent:0!important}
.sidebar ul li,.sidebartop ul li{margin:0;padding:10px;border-bottom:1px solid #eaeaea}
.sidebar .widget{margin:0}
.sidebartop .widget{margin:0 0 20px 0}
/* Dropdown Label */
.droplabdown select{outline:none;cursor:pointer;transition:all .6s ease-out}
.droplabdown{display:inline-block;position:relative;overflow:hidden;width:100%;border:0;height:40px;line-height:40px;color:#7f8c8d}
.droplabdown:before,.droplabdown:after{content:&#39;&#39;;position:absolute;z-index:2;top:15px;right:12px;width:0;height:0;line-height:40px;border:4px dashed;border-color:#999 transparent;pointer-events:none}
.droplabdown:before{border-bottom-style:solid;border-top:none}
.droplabdown:after{margin-top:8px;border-top-style:solid;border-bottom:none}
.dropdown-select{background:#fff;color:#000;position:relative;width:100%;margin:0;padding:6px 8px 6px 10px;height:40px;line-height:20px;font-size:13px;border:1px solid rgba(0,0,0,0.1);-webkit-appearance:none;transition:border-color ease-in-out .15s,box-shadow ease-in-out .15s}
.droplabdown select:hover{border-color:rgba(0,0,0,.34);}
.droplabdown select:focus{outline:none;cursor:pointer;border-color:#66afe9;box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 8px rgba(102,175,233,0.6);}
.dropdown-select&gt;option{background:#fafafa;position:relative;display:block;margin:3px;text-shadow:none;outline:0;border:0;cursor:pointer}
/* Arlina Footer Wrapper */
#footer-wrapper{background:#fff;text-align:center;padding:20px;margin:auto;max-width:970px;border-top:1px solid rgba(0,0,0,0.1)}
.simplifymedsos a{display:inline-block;text-align:center;margin-top:10px;margin-right:5px;color:#fff;border-radius:100%;opacity:.9;}
.simplifymedsos a i{font-family:Fontawesome;width:32px;height:32px;line-height:32px;display:block}
.simplifymedsos a:hover{color:#fff;opacity:1;transform:rotate(360deg);}
.simplifymedsos .facebook{background:#3b5998}
.simplifymedsos .twitter{background:#00aced}
.simplifymedsos .googleplus{background:#dd4b39}
.simplifymedsos .rssfeed{background:#ee802f}
#footme{max-width:970px;height:auto;padding:0;margin:0 auto;overflow:hidden;font-size:13px;color:#666;line-height:1.8}
#footme a{color:#138be6}
.footmekiri{text-align:left;float:left}
.footmekanan{text-align:right;float:right;}
.footmekanan a{color:#666;}
.footmekanan a:hover{color:#000;}
.footmekanan a:before{content:&quot;\b7&quot;;padding-right:0.5em;display:inline-block}
.footmekanan a:first-child:before{content:&quot;&quot;;}
.footer-column{position:relative;margin:0 auto 20px auto;clear:both;font-size:14px;line-height:24px;overflow:hidden;text-align:left;border-bottom:1px solid rgba(0,0,0,0.1);}
.footer-column h3{position:relative;overflow:hidden;margin:0 0 10px 0;font-size:1rem;padding:0 0 10px 0;border-bottom:1px solid rgba(0,0,0,.1);color:#000}
.footer-column h3:before{content:&#39;&#39;;position:absolute;bottom:-1px;left:0;right:0;background:#e74c3c;width:16%;height:1px}
.footer-column h3:after{content:&#39;&#39;;display:inline-block;position:absolute;height:15px;top:0;margin:3px 0 12px 10px;width:100%;background:url(http://4.bp.blogspot.com/-R2WTW6O9E1o/VX7dqIGT1eI/AAAAAAAACc4/pyvQDMMLX3E/s1600/repeat-bg.png)repeat}
.footer-menu{float:left;width:31%;margin:0 20px 20px 0}
.footer-menu p.footer2{margin:5px auto}
.footer-menu ul{margin:0}
.footer-menu ul li{list-style-type:square;margin:0 0 0 15px}
.footer-menu ul li a{color:#000}
.footer-menu ul li a:hover{color:#138be6}
/* Custom Heading Widget */
.footer-column .footer-menu h3:before{content:&#39;\f07c&#39;;font-family:fontawesome;font-weight:normal;display:inline-block;margin:0 5px 0 0;color:#95a5a6}
.footer-column .footer-menu:nth-child(1) h3:before{content:&#39;\f046&#39;;}
.footer-column .footer-menu:nth-child(2) h3:before{content:&#39;\f085&#39;;}
.footer-column .footer-menu:nth-child(3) h3:before{content:&#39;\f003&#39;;}
/* Subscribe Footer */
#subscribe-footer{overflow:hidden;margin:0 0 20px 0;width:33.4%}
#subscribe-footer p{margin:1em 0}
#subscribe-footer .emailfooter{margin:auto;text-align:center;}
#subscribe-footer .emailfooter form{margin:0;padding:0;float:left}
#subscribe-footer .emailfooter input{background:rgba(255,255,255,1);padding:9px 12px;color:#999;font-size:14px;margin-bottom:10px;border:1px solid rgba(0,0,0,0.14);transition:border-color ease-in-out .15s,box-shadow ease-in-out .15s}
#subscribe-footer .emailfooter input:hover{border-color:rgba(0,0,0,.34);}
#subscribe-footer .emailfooter input:focus{color:#000;outline:none;border-color:#66afe9;box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 8px rgba(102,175,233,0.6);}
#subscribe-footer .emailfooter .submitfooter{background:#e74c3c;color:#fff;margin:0 0 0 5px;font-size:14px;cursor:pointer;border:1px solid rgba(0,0,0,0.05);border-radius:3px;transition:all .3s}
#subscribe-footer .emailfooter .submitfooter:active,#subscribe-footer .emailfooter .submitfooter:hover{background:#c0392b;color:#fff;}
/* Popular Post */
#PopularPosts1 ul,.PopularPosts li,.PopularPosts li img,.PopularPosts li a,.PopularPosts li a img{color:#000;margin:0;padding:0;list-style:none;border:none}
#PopularPosts1 ul{margin:0;list-style:none}
#PopularPosts1 ul li{margin:5px 0;padding:5px 0;position:relative}
#PopularPosts1 ul li:last-child{border:0}
#PopularPosts1 ul li img{display:block;width:100%;height:auto}
#PopularPosts1 ul li .item-title a,.PopularPosts ul li a{font-size:13px;font-weight:700;line-height:1.6;}
#PopularPosts1 ul li .item-title a:hover,.PopularPosts ul li a:hover{color:#138be6}
#PopularPosts1 .item-thumbnail{margin:0 10px 0 0;overflow:hidden;z-index:2;display:block;position:relative;border-radius:0;width:62px;height:62px;float:left}
#PopularPosts1 .item-title{padding:0 5px}
#PopularPosts1 ul li:nth-child(1){border-top:none}
#PopularPosts1 ul li .item-snippet{color:#999;font-size:13px}
/* Banner */
.kotak_iklan1 {position:relative;}
.kotak_iklan1:before{content:&#39;300x250 Ad&#39;;position:absolute;background:rgba(25,25,25,.9);color:#fff;top:0;right:0;padding:2px 8px;font-size:80%}
.kotak_iklan1:hover:before{content:&#39;Pasang iklan&#39;;}
.banner,.banner2{margin:0 auto;text-align:center;overflow:hidden}
.banner .widget,.banner2 .widget{width:100%;max-width:100%;margin:0 auto;background:#fff;text-align:center;overflow:hidden;padding:20px}
.banner .widget{border-bottom:1px solid rgba(0,0,0,0.1);}
.banner2 .widget{border-top:1px solid rgba(0,0,0,0.1);}
.banner img,.banner iframe,.banner2 img,.banner2 iframe{display:block;margin:0 auto;text-align:center;height:auto;}
.kotak_iklan{text-align:center;margin:0 auto;transition:all 1s ease-out}
.kotak_iklan .sidebar .widget-content,.kotak_iklan .sidebar-atas .widget-content{padding:0;border:0}
.kotak_iklan .sidebar .widget{margin-bottom:0;padding:0}
.kotak_iklan img{background:#fff;text-align:center;margin:0 auto;padding:4px;border:1px solid transparent!important;transition:all .6s ease-out}
.kotak_iklan img:hover{background:#fdfdfd;border:1px solid #e6e6e6}
.kotak_iklan2,.kotak_iklan3{text-align:center;margin:0 auto;transition:all 1s ease-out}
.kotak_iklan2 .sidebar .widget-content,.kotak_iklan2 .sidebar-atas .widget-content{padding:0;background:#f2f6f7;box-shadow:0 1px 2px 0 rgba(0,0,0,.1);border:0}
.kotak_iklan2 .sidebar .widget,.kotak_iklan2 .sidebar-atas .widget{margin-bottom:0;padding:0}
.kotak_iklan2 img{text-align:center;transition:all 1s ease-out}
.kotak_iklan2 img:hover{transition:all .5s ease-out}
#HTML2 .widget-content,#HTML3 .widget-content,#HTML4 .widget-content,#HTML5 .widget-content{padding:0;}
/* Search Form */
.widget.widget_search form{position:relative;margin:0 auto 20px auto;border:7px solid rgba(0,0,0,0.1);padding:5px;}
.widget_search .search-field{background:#fff;font-size:97%;border:0;padding:10px 0;text-indent:10px;width:80%}
.widget_search .search-field:focus{background:#fefefe;border-color:rgba(0,0,0,0.2)}
.widget_search .search-submit{background:#e74c3c;font-family:fontawesome;padding:10px;color:#fff;border:0;width:18%;cursor:pointer;float:right;transition:all .4s;}
.widget_search .search-submit:hover,.widget_search .search-submit:active{background:#c0392b;}
/* To top */
.simplifytotop{visibility:hidden;z-index:2;background:#e74c3c;color:#fff;font-size:20px;width:37px;height:37px;line-height:37px;text-align:center;position:fixed;bottom:10px;right:10px;border-radius:2px;cursor:pointer;transition:all .4s;}
.simplifytotop:hover{background:#c0392b}
.simplifytotop.arlniainf{visibility:visible;cursor:pointer;opacity:1;-webkit-transform:translateZ(0);transform:translateZ(0);transition:all .4s;}
/* Arlina Global Responsive */
@media screen and (max-width:800px) {
#footer-wrapper{padding:20px 0;border:0}
#header,#headersticky{padding:0;height:auto;text-align:center;border:0;}
#headerdua {float:none;max-width:100%;padding:20px;}
#header .title{margin:0 0 5px 0}
#headersticky.makesticking {position:relative!important;height:auto;box-shadow:none}
#headersticky.makesticking p.description{display:block}
#headersticky.makesticking nav#simplify-nav a{line-height:initial}
#headersticky.makesticking nav#simplify-nav li li{line-height:initial}
#main-wrapper {float:none;border:0;width:100%;}
#sidebar-wrapper {padding: 0 20px;width:100%;float:none;}
.simplify-menu,.search-box{width:100%;margin:0 auto;padding:10px;}
.search-box:hover,.search-box:active,.search-box:focus{width:100%;}
.simplify-menu ul li{width:25%;float:left}
.simplify-menu ul li,.simplify-menu ul li:first-child{border:0;}
.simplify-menu ul li,.search-box{text-align:center}
.simplify-menu ul li a{margin:0 auto;padding:0;color:#fff}
.simplify-menu ul li a:hover,.simplify-menu ul li:hover a{background:transparent;color:rgba(255,255,255,.8)}
.simplify-menu ul li:first-child a{background:transparent;color:rgba(255,255,255,.9);}
#search-box{padding:0 0 10px 0}
.simplify-menu_wrapper{background:#138be6;}
.simplify-menu{background:rgba(0,0,0,0.1)}
#search-box{width:96%;float:left;padding-right:0;margin:0 2%}
.search-box{margin-top:10px;height:auto;}
#searchform{margin:0 10px}
#menu {display:block;}
#simplify-nav{background:#fff;font-size:initial;position:relative;display:block;padding:15px;text-transform:uppercase;font-weight:700;border-top:1px solid rgba(0,0,0,0.12);border-bottom:1px solid rgba(0,0,0,0.12);box-shadow:none;float:none;text-align:left;}
#simplify-nav ul{background:#fff;position:absolute;top:100%;left:0;z-index:3;height:auto;display:none}
#simplify-nav ul.menus{width:100%;position:static;padding-left:20px}
#simplify-nav li{display:block;float:none;width:auto}
#simplify-nav li a:hover,#simplify-nav ul.menus a:hover{background:#333;color:#fff;}
#simplify-nav a{background:#333;padding:12px;height:initial;line-height:initial;color:#fff;border:0}
#simplify-nav input,#simplify-nav label{position:absolute;top:0;left:0;display:block}
#simplify-nav input{z-index:4}
#simplify-nav input:checked + label{color:#fff}
#simplify-nav input:checked ~ ul{display:block;width:100%}
#simplify-nav li:hover &gt; ul{width:100%}
#simplify-nav li li {border:0;}
#simplify-nav li li &gt; a{background:#2f2f2f;color:#fff;height:auto;font-size:12px;line-height:30px;padding:0 10px;}
#simplify-nav li li:hover, #simplify-nav li li a:hover {background:#333;color:#fff;}
#simplify-nav li ul {background:#333;padding:0;position:relative;width:100%;left:initial;box-shadow:none;}
#simplify-nav li:hover ul.menus,#simplify-nav li:hover &gt; ul{left:initial}
#simplify-nav a i {float:right;}
#footme{padding:0 20px}}
@media only screen and (max-width:768px) {
#headerdua {float:none;max-width:100%;}
#sidebar-wrapper,#main-wrapper {width:100%;padding:0 20px 20px 20px;}
.sidebar {padding:0;}
.sosial-atas li a{color:#fff}
.sosial-atas li a:hover,.sosial-atas li:hover a{background:rgba(0,0,0,0.1);color:#fff}
.page-menu ul li a:hover,.page-menu ul li:hover a{background:transparent}
.footer-menu,#subscribe-footer{float:none;width:auto;margin:0 20px 20px 20px}}
@media screen and (max-width:640px) {
#main-wrapper {width:100%;padding:0 10px 20px 10px;}
#sidebar-wrapper {width:100%;padding:0 20px 20px 20px;}
.post-info {display:none}
.status-msg-border {width:97%}
.post h2 {font-size:100%}
h1.post-title.entry-title,h2.post-title.entry-title{font-size:18px;margin:0}
#simplify-nav ul{height:400px;overflow:auto;}
#footer-wrapper{margin:auto;border-top:1px solid rgba(0,0,0,0.1)}
#footer-wrapper .footmekiri,#footer-wrapper .footmekanan{float:none;text-align:center}
.simplifytotop{width:32px;height:32px;line-height:32px}
#footme {padding:0 10px;}}
@media screen and (max-width:480px) {
body{background:#fff}
.comments .comments-content .user{line-height:2.8em}
.post h2{font-size:100%}
.post h1{font-size:120%}
body,.body-fauxcolumn-outer{font-size:80%}
.search-box{display:block;}
#search-form,#searchform,.search-button{line-height:34px}
#search-form{height:34px;line-height:34px}
.sosial-atas,.simplify-menu ul li a i{display:none;}
#header{border:0}
#header p.description{line-height:normal}
#main-wrapper{padding:0}
#sidebar-wrapper{padding:0 10px}
.post-body{padding:10px}
.breadcrumbs{padding:18px 7px}
.widget-content{box-shadow:none;border:0}
.simplify-menu_wrapper{padding:0 0 10px 0}
.simplify-menu ul{line-height:2em}
#simplifynewsletter{margin:0 0 20px 0}
.sidebar .widget,.sidebartop .widget {margin:0;}
#Label1 .widget-content {padding:20px 10px;}
.banner .widget,.banner2 .widget{padding:10px}
#subscribe-footer .emailfooter input{width:100%}
#subscribe-footer .emailfooter .submitfooter{margin:0}
#subscribe-footer .emailfooter form{margin:auto;float:none}}
@media screen and (max-width:320px) {
body{background:#fff}
#sidebar-wrapper{padding:0 10px}
.widget-content{padding:12px 0}
#HTML2 .widget-content,#HTML3 .widget-content,#HTML4 .widget-content,#HTML5 .widget-content {padding:0}
#Label1 .widget-content {padding:20px 0;}}
@media screen and (max-width:240px) {
body,.body-fauxcolumn-outer {font-size:80%}
.simplify-menu ul li{width:50%}}
.status-msg-body {padding:10px 0;display:none}
.status-msg-wrap{display:none;font-size:14px;margin-left:1px;width:100%;color:#666}
.status-msg-wrap a{color:orange!important}
.status-msg-bg{display:none;background:#ccc;position:relative;width:99%;padding:6px;z-index:1;border:2px #999 solid}
.status-msg-border{display:none;border:0;position:relative;width:99%}
</style>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<style type='text/css'>
.post{padding:20px;margin:0;border-bottom:1px solid rgba(0,0,0,0.14);transition:all .3s}
.post-body{padding:0;}
h1.post-title.entry-title a:hover, h2.post-title.entry-title a:hover {color:#138be6;}
h1.post-title.entry-title,h2.post-title.entry-title{margin:0 12px 15px 0}
.post-thumb{position:relative;background:#f1f1f1;overflow:hidden;float:left;min-width:200px;height:auto;min-height:150px;margin:0 20px 0 0;transition:all .3s}
.post-thumbnail{background:#f1f1f1;width:100%;height:auto;}
.post-thumb img{background:#f1f1f1;}
.post-thumb .comment-info{position:absolute;top:0;left:0;z-index:5;color:#fff;padding:0}
.post-thumb .comment-info a{display:inline-block;background:red;color:#fff;padding:10px}
.snippets{font-size:96%;line-height:1.5;margin:0 0 8px 0}
.post-timestamp,.author-info,.comment-info{padding:0;margin:0 5px 0 0;}
.post-timestamp a abbr.published.updated{border:0;cursor:pointer}
.post-info{color:#999;padding:0;overflow:hidden;border:0;margin:0 0 10px;font-size:13px;}
.post-info a{color:#999;margin:0 5px 0 0}
.post-info a:hover{color:#138be6;}
.author-info img.avatar-photo1{height:22px;width:22px;border-radius:100%;margin:0 3px 0 0}
.label-info{position:absolute;left:0;top:0;opacity:0;visibility:hidden;z-index:2;transition:all .3s}
.post-thumb:hover .label-info{opacity:1;visibility:visible;}
.label-info a{display:inline-block;background:#7f8c8d;color:#fff;font-size:12px;padding:6px}
.label-info a:hover{background:#e74c3c;}
/* Page Navigation */
#blog-pager{background:#fff;clear:both;width:auto;padding:20px;line-height:normal;position:relative;display:block;text-align:left;overflow:visible;margin:0;}
.showpage a,.showpageNum a,.showpagePoint,.showpageOf{position:relative;background:#fff;display:inline-block;font-size:13px;color:#000;margin:0;border:1px solid rgba(0,0,0,0.14);border-right:0;padding:6px 12px;line-height:1.42857143;text-decoration:none;transition:all .3s}
.showpageNum:last-child a{border-right:1px solid rgba(0,0,0,0.1)}
.showpageNum a:before{content:&#39;&#39;;position:absolute;top:0;bottom:0;left:0;right:0;box-shadow:inset 0 -2px 2px rgba(0,0,0,0.02);transition:box-shadow 0.5s}
.showpage a:hover,.showpageNum a:hover{background:#f9f9f9;color:#000;position:relative;}
.showpagePoint,.showpagePoint:hover{background:#f5f5f5}
span.label-info a.label-block:nth-child(n+2) {display:none;}
@media screen and (max-width:768px) {
.post,#blog-pager{padding:20px 0}
h1.post-title.entry-title a, h2.post-title.entry-title a {margin:15px 0;}}
@media screen and (max-width:640px) {
.post{margin:0 0 10px 0;padding:10px}
.post-thumb{width:100%;margin:0;min-width:auto;min-height:auto;max-height:200px;}
.post-thumbnail {width:100%;height:auto;}
h1.post-title.entry-title a, h2.post-title.entry-title a {display:inline-block;margin:10px 0;}
#blog-pager {padding:12px 12px 22px 12px;}
.snippets{font-size:96%;color:#999}
.label-info a{font-size:12px}}
@media screen and (max-width:480px) {
.post-thumb{max-height:180px;}
h1.post-title.entry-title, h2.post-title.entry-title {margin:0 0 5px 0;}}
@media screen and (max-width:320px) {
.showpage a,.showpageNum a,.showpagePoint,.showpageOf{padding:5px 8px}}
</style>
</b:if></b:if>
<b:if cond='data:blog.pageType != &quot;index&quot;'>
<style type='text/css'>
/* CSS Comments */
#comments{background:#fff;position:relative;margin:0 auto;padding:20px;}
#comments h3 {display:inline-block;margin:0 0 10px 0;}
.comment_avatar_wrap{width:42px;height:42px;background:#fcfcfc;border-radius:6px;text-align:center;margin:0 0 20px 0;padding:0}
#comments .avatar-image-container{float:left;margin:0 10px 0 0;width:42px;height:42px;max-width:42px;max-height:42px;padding:0;margin-bottom:10px}
#comments .avatar-image-container img{width:42px;height:42px;max-width:42px;max-height:42px;background:url(http://2.bp.blogspot.com/-fjaZBtfvzac/UN1mw2tUamI/AAAAAAAADkc/XdKqt8hWZ6w/s1600/anon.jpg) no-repeat}
#comments .comment_name,#comments .comment_admin .comment_name{padding:0 0 10px 0;font-size:13px;position:relative}
#comments .comment_name a{color:#666;font-weight:700;padding:0;font-size:14px;text-decoration:none}
#comments .comment_admin .comment_date{font-weight:normal;font-size:11px}
#comments .comment_admin .comment_author_flag{display:inline-block;font-size:14px;color:rgb(17,143,249);text-align:center;margin:0 0 0 3px;}
#comments .comment_service{margin-top:5px}
#comments .comment_date{color:#a9a9a9;float:right;font-size:11px;font-weight:normal;margin-top:-3px}
#comments .comment_date a{color:#a9a9a9;float:right;font-size:11px;font-weight:normal;margin:0;padding:0}
#comments .comment_date a:hover{color:#a9a9a9;text-decoration:underline}
#comments .comment_body{margin-left:62px;margin-top:-64px;background:#fafafa;padding:18px 20px;line-height:26px;border-radius:7px;margin-bottom:20px;position:relative;border:1px solid rgba(0,0,0,0.05)}
#comments .comment_body p{margin:5px 0 0 0;font-size:14px;word-wrap:break-word;padding:0 0 5px 0}
#comments .comment_body:before{content:&#39;&#39;;right:100%;border:solid transparent;height:0;width:0;position:absolute;pointer-events:none;border-right-color:rgba(0,0,0,0.08);border-width:10px}
#comments .comment_body:after{content:&#39;&#39;;top:19px;right:99.9%;border:solid transparent;height:0;width:0;position:absolute;pointer-events:none;border-right-color:#fafafa;border-width:9px}
#comments .comment_inner{margin:12px 0}
#comments .comment_child .comment_wrap{padding-left:3%}
#comments .comment_reply{display:inline-block;margin-top:10px;padding:1px 7px;color:#fff;text-align:center;text-decoration:none;background:#bdc3c7;font:11px/18px sans-serif;transition:background-color .5s ease-out 0s}
#comments .comment_reply:hover{text-decoration:none;background:#95a5a6}
#comments .unneeded-paging-control{display:none}
#comments .comment-form{max-width:100%;}
#comment-editor{width:100%;background:transparent url(http://4.bp.blogspot.com/-jSUS8v5kwpQ/U8Z_6Ufr-PI/AAAAAAAAEYY/o4cQPKvt8vQ/s1600/loading.gif) no-repeat 50% 30%;border:1px solid #eee}
#comments .comment_form a{text-decoration:none;}
#comments .comment-form p{background:#f5f5f5;padding:15px 15px 11px;margin:5px 0 15px;color:rgba(0,0,0,.8);font-size:15px;line-height:normal;border-radius:3px;position:relative;max-width:100%;}
#comments .comment-form p:after{content:&quot;&quot;;width:0;height:0;position:absolute;bottom:-16px;left:7%;border:8px solid transparent;border-color:#f5f5f5 transparent transparent}
#comments .comment_reply_form{padding:0 0 0 70px}
#comments .comment_reply_form .comment-form{width:99%}
.comment_emo_list .item{float:left;display:block;text-align:center;margin:1px 1px 0 0;height:40px;width:41px}
.comment_emo_list span{display:block;font-weight:700;font-size:11px;margin:3px 0 0 0;letter-spacing:1px}
img.comment_emo {width:16px;height:16px;}
.comment_youtube{max-width:100%;width:400px;height:225px;display:block;margin:auto}
.comment_img{max-width:100%}
#comments .deleted-comment{display:block;color:#999;}
#comments .comment_header{width:50px}
#respond{overflow:hidden;padding-left:10px;clear:both}
#comments .comment_avatar img{width:42px;height:auto;background:url(http://3.bp.blogspot.com/-fr42e67HG4I/Vky8HLexiEI/AAAAAAAAM0I/MLMd2qwIH1E/s1600/avatar.png) no-repeat;border-radius:6px}
#comments .comment-delete img{float:right;margin-left:15px;margin-top:3px;}
iframe{border:none;overflow:hidden}
#emo-box,#hide-emo{display:none}
.paging-control-container{text-align:center;margin:0 0 0 25%}
.paging-control-container a{text-align:center;margin:0 auto;background:#ccc;border:1px solid #e1e1e1;padding:3px 10px}
.button-group{float:right;text-align:left;margin:0 auto}
button,button[disabled]:active{border:none;font-size:12px;font-weight:normal;border-radius:1px;padding:4px 10px;text-decoration:none;background:#b6c472;color:#fff;display:inline-block;transition:all 0.5s linear;cursor:pointer}
button:hover{background:#a0ad64;color:#fff;transition:all 0.2s linear}
button:active{background:#a0ad64;color:#fff}
button[disabled],button[disabled]:active{background:#a0ad64;border-bottom:2px solid #8b9656;color:#fff;cursor:default}
.small-button a,.small-button1 a{background:#f84141;color:#fff;font-size:13px;cursor:pointer;margin:15px 5px 5px 0;text-decoration:none;text-transform:none;text-shadow:none;border-radius:3px;display:inline-block;padding:5px 10px;box-shadow:0 1px 2px rgba(0,0,0,0.1)}
.small-button:hover a,.small-button1:hover a{background:#e73636;}
/* Arlina Search Bar */
#searchbar{display:inline-block;width:100%;text-align:center;margin:20px auto 0 auto;padding:0;border-top:1px solid rgba(0,0,0,0.14);}
#searchbar form{position:relative;margin:0;padding:20px}
#searchbar form:after{content:&#39;\f002&#39;;font-family:fontawesome;position:absolute;right:6%;top:38%;color:rgba(0,0,0,0.5);transition:all 0.5s linear}
#searchbar form:hover:after{color:rgba(0,0,0,0.8)}
#searchbar input{position:relative;background:#fff;width:100%;padding:17px 15px;border:1px solid rgba(0,0,0,.14);box-shadow:inset 0 1px 1px rgba(0,0,0,0.075);transition:border-color ease-in-out .15s,box-shadow ease-in-out .15s}
#searchbar input:hover{border-color:rgba(0,0,0,.34);}
#searchbar input:focus{border-color:#66afe9;box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 8px rgba(102,175,233,0.6);}
@media screen and (max-width:480px) {
#comments{padding:10px}
#comments .comment_body{background:#fff;margin-left:52px;margin-top:-57px;padding:0;width:auto;border:0;}
.comment_avatar_wrap{width:32px;height:32px;border-radius:2px}
#comments .comment_avatar img{width:32px;background:#f6f6f6;border-radius:2px}
#comments .comment_reply{margin-top:5px;padding:0;color:#444;background:#fff;}
#comments .comment_body p{margin:0;font-size:13px;padding:0}
#comments .comment_name,#comments .comment_admin .comment_name{padding:0}
#comments .comment-delete img{opacity:.5}
#comments .comment-delete:hover img{opacity:.8}
#comments .comment_inner{border-bottom:1px solid rgba(0,0,0,0.14)}
#comments .comment_date,#comments .comment_body:before{display:none}}
</style>
</b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<style type='text/css'>
/* Arlina Post Area */
.post {overflow:hidden;}
.post-info{background:#fff;display:block;color:#666;font-style:italic;line-height:1.6em;font-size:13px;padding:10px 15px;border-bottom:1px solid rgba(0,0,0,0.14);border-top:1px solid rgba(0,0,0,0.14)}
.post-info a{position:relative;color:#138be6;padding:0 10px 0 0;font-style:normal;font-weight:700;}
.post-info a:hover{text-decoration:underline;}
.author-info img.avatar-photo1{background:rgba(0,0,0,0.1);height:28px;width:28px;margin:0 7px 0 0;border-radius:100%;transition:all .3s;}
.author-info img.avatar-photo1:hover {transform:rotate(360deg);}
.post-timestamp,.author-info,.comment-info,.label-info{padding:0}
.post-body p{margin:0}
.post-timestamp {padding:0;}
.post-body img {height:auto;margin-bottom:2px;opacity:1;transition:all .6s ease;}
.post-body img:hover {opacity:0.97;}
.post-body a.img,.post-body .separator a {margin-left:0!important;margin-right:0!important;}
h1.post-title.entry-title,h2.post-title.entry-title{color:#138be6;padding:15px;font-size:24px;margin:0}
.label-wrap{display:block;color:#666;padding:10px 15px;border-bottom:1px solid rgba(0,0,0,0.14);overflow:hidden}
.label-info{position:relative;margin:auto}
.label-info a,.label-tags{float:left;display:inline-block;position:relative;font-size:10px;margin-left:8px;padding:5px 6px;background:#5c7dc2;color:#fff;text-decoration:none;border:1px solid;text-transform:uppercase;border-radius:3px}
.label-tags{background:#fff;color:#f39c12;font-family:fontawesome;}
.label-info a:hover{background:#fff;color:#5c7dc2;border-color:inherit;text-decoration:none}
.bottomshare{display:block;padding:0 20px;margin:auto;text-align:center}
/* Arlina Related Post */
#related-post {margin:0;padding:0;}
#related-post h4{background:#fafafa;color:#111;border-bottom:1px solid rgba(0,0,0,0.14);border-top:1px solid rgba(0,0,0,0.14);padding:10px 0;font-size:20px;margin:0 0 20px 0;padding-left:8px;line-height:1em}
#related-post h4 span{padding:6px;display:inline-block;vertical-align:middle}
.relhead {background:#fff;font-size:100%;font-weight:normal;line-height:150%;overflow:hidden;padding:0;}
ul#related-summary {margin:0;padding:0 15px;}
ul#related-summary li{position:relative;float:left;list-style:none outside none;margin:0 5px 15px 5px;padding:0;overflow:hidden;height:180px;width:31.6%}
ul#related-summary li img{background-color:#f1f1f1;width:100%;height:auto;max-width:100%;margin:0 auto;vertical-align:middle;}
ul#related-summary li a.relinkjdulx{color:#666;display:block;font-size:12px;font-weight:700;line-height:normal;overflow:hidden;text-align:left;padding:10px 10px 10px 0}
ul#related-summary li a.relinkjdulx:hover{color:#000;}
.overlayb {position:relative;max-height:140px;overflow:hidden;}
.overlayb:before{content:&#39;&#39;;background-color:rgba(0,0,0,0.4);position:absolute;text-align:center;top:0;left:0;right:0;bottom:0;z-index:2;opacity:0;visibility:hidden;transition:all 0.4s linear}
.overlayb:after{content:&#39;\f002&#39;;font-family:fontawesome;font-size:1.3rem;color:rgba(255,255,255,.8);position:absolute;top:45%;left:45%;text-align:center;z-index:2;opacity:0;visibility:hidden;transition:all 0.20s linear}
.overlayb:hover:before,.overlayb:hover:after {opacity:1;visibility:visible;}
/* Share Button */
.sharede,.sharesimply{position:relative;}
.sharesimply{margin:20px auto 0 auto;}
.sharesimply a.fb,.sharesimply a.gp,.sharesimply a.tw{position:relative;display:inline-block;margin:0 0 5px 0;color:#fff;text-shadow:none;padding:12px 0;width:32.9%;font-size:16px;font-weight:700;overflow:hidden;transition:all .3s}
.sharesimply a.gp {background:#f20000;}
.sharesimply a.fb {background:#516ca4;}
.sharesimply a.tw {background:#00baff;}
.fbtea,.gotea,.plustea,.twtea{font-size:2.5rem;vertical-align:middle;position:absolute;left:5px;top:5px;color:rgba(255,255,255,.5);transition:all .3s}
.sharesimply a:hover .fbtea,.sharesimply a:hover .gotea,.sharesimply a:hover .plustea,.sharesimply a:hover .twtea{color:rgba(255,255,255,.3);transform:scale(1.3) rotate(-20deg)}
.sharesimply a.fb:hover,.sharesimply a.gp:hover,.sharesimply a.tw:hover{color:#fff;background:#333;}
.sharesimply a.fb:active,.sharesimply a.gp:active,.sharesimply a.tw:active{box-shadow:inset 0 1px 0 rgba(0,0,0,.16)}
/* Arlina Shortcodes */
.button{list-style:none;text-align:center;width:95%;margin:10px;padding:2px;font-size:14px;clear:both;}
.button ul {margin:0;padding:0}
.post-body ul.button {list-style:none;text-align:center;margin:20px auto;padding:2px;font-size:14px;clear:both;z-index:2;}
.button li{display:inline;margin:0 5px;padding:0;list-style:none;}
.post-body ul.button a.demo,.post-body ul.button a.download{display:block;background:#97b28e;max-width:180px;padding:8px 12px;color:#fff;font-weight:700;font-size:14px;text-align:center;text-transform:uppercase;letter-spacing:0.5px;margin:auto;border-radius:3px;transition:all .3s}
.post-body ul.button a.demo{background:#5c7dc2;}
.post-body ul.button a.download{background:#da972d;}
.post-body ul.button a.demo:hover,.post-body ul.button a.download:hover {opacity:.9;color:#fff}
.first-letter{float:left;color:#f77c6a;font-size:75px;line-height:60px;padding-top:4px;padding-right:8px;padding-left:3px;font-family:Georgia}
.bagidua {-webkit-column-count:2;-moz-column-count:2;column-count:2;}
.bagitiga {-webkit-column-count:3;-moz-column-count:3;column-count:3;}
.bagiempat {-webkit-column-count:4;-moz-column-count:3;column-count:4;}
.bagidua img,.bagitiga img,.bagiempat img{-webkit-backface-visibility:hidden;margin-bottom:20px;max-width:100%;}
#wrap{margin:20px auto;text-align:center}
.btn{background:#7fa4ed;padding:8px 12px;color:#fff;font-weight:700;font-size:14px;text-align:center;text-transform:uppercase;letter-spacing:0.5px;border-radius:4px;transition:all .3s}
.btn:hover,.btn:active,.btn.down:hover,.btn.down:active{background:#41598B}
.post-body a:visited.btn,.post-body a:visited.btn.down,.post-body a:link.btn,.post-body a.btn.down,.post-body a.btn:hover,.post-body a.btn:active,.post-body a.btn.down:hover,.post-body a.btn.down:active{color:#fff}
.btn i{margin:0}
.btn.down.anima{-webkit-animation:anim 2s ease-in infinite;animation:anim 2s ease-in infinite}
.videoyoutube{text-align:center;margin:auto;width:100%;}.video-responsive{position:relative;padding-bottom:56.25%;height:0;overflow:hidden;}.video-responsive iframe{position:absolute;top:0;left:0;width:100%;height:100%;border:0}
.post-body pre{-webkit-user-select:text;-khtml-user-select:text;-moz-user-select:text;-ms-user-select:text;user-select:text;padding:0;margin:.5em auto;white-space:pre;word-wrap:break-word;overflow:auto;background-color:#333;position:relative;width:100%;-moz-tab-size:2;-o-tab-size:2;tab-size:2;word-break:normal;-webkit-user-select:text;-khtml-user-select:text;-moz-user-select:text;-ms-user-select:text;user-select:text;-webkit-hyphens:none;-moz-hyphens:none;-ms-hyphens:none;hyphens:none;}
.post-body pre::-webkit-scrollbar,pre::-moz-scrollbar,pre code::-webkit-scrollbar,pre code::-moz-scrollbar,code::-webkit-scrollbar,code::-moz-scrollbar {display:none;}
.post-body pre code{display:block;background:none;border:none;color:#ccc;padding:25px 20px 20px 20px;font-family:&#39;Source Code Pro&#39;,Menlo,Consolas,Monaco,monospace;font-size:.83rem;white-space:pre;overflow:auto}
pre mark,code mark,pre code mark {background-color:#f39c12!important;color:#fff!important;padding:2px;margin:0 2px;border-radius:2px;}
#related-summary .news-text,#share-menu{display:none}
.post-body pre code::selection,.post-body pre::selection{background:#95a5a6;color:#eee;}
/* CSS Multi Author Box */
.authorboxwrap{background:#444;color:#fff;margin:20px auto 0 auto;padding:20px;overflow:hidden;}
.avatar-container{float:left;padding:10px;margin:0 20px 0 0;background:rgba(0,0,0,0.2)}
.avatar-container img{width:90px;height:auto;max-width:100%!important;transition:all .3s}
.author_description_container h4{font-size:18px;display:block;margin:0;margin-bottom:2px}
.author_description_container h4 a{color:#fff}
.author_description_container p{margin:0;font-size:14px;margin-bottom:8px;line-height:25px;font-weight:400}
.social-links li{list-style:none!important;float:left}
.social-links a{border-bottom:none}
.social-links a:after,.social-links a:before{content:none!important}
.social-links li a{color:#fff;font-size:12px;text-align:center;display:inline-block;padding:0;margin:0 10px 0 0;width:24px;height:24px;line-height:24px;border-radius:100%}
.social-links li:nth-child(1):hover a{background:#516ca4;}
.social-links li:nth-child(2):hover a{background:#00c3f3;}
.social-links li:nth-child(3):hover a{background:#f20000;}
.social-links li a:hover{color:#fff}
/* Arlina Post Navigation */
#blog-pager-newer-link,#blog-pager-older-link{font-size:100%}
.blog-pager-older-link,.home-link,.blog-pager-newer-link{padding:0}
.halaman{margin:auto;padding:0;border-bottom:1px solid rgba(0,0,0,0.08);}
.halaman-kanan,.halaman-kiri{color:#141924;background:0 0;width:50%;position:relative;margin:0}
.halaman-kiri{background:#fff;width:50%;float:left;margin:0;text-align:left;padding:20px 20px 20px 30px;height:72px;border-right:1px solid rgba(0,0,0,0.08);}
.halaman-kanan{background:#fff;width:50%;float:right;margin:0;text-align:right;padding:20px 30px 20px 20px;height:72px}
.halaman-kanan:hover,.halaman-kiri:hover{background:#e74c3c;color:rgba(255,255,255,1);}
.halaman-kanan:hover a,.halaman-kiri:hover a{color:rgba(255,255,255,1);}
.halaman-kanan a,.halaman-kiri a{color:#111;font-size:14px;font-weight:500;line-height:1.3em;transition:initial}
.current-pageleft,.current-pageright,.halaman-kanan a,.halaman-kiri a{font-size:14px;font-family:Roboto,Arial,sans-serif;font-weight:700;background:transparent;text-decoration:none;line-height:normal;transition:initial}
.halaman-kanan a:hover,.halaman-kanan:hover .pager-title-left,.halaman-kiri a:hover,.halaman-kiri:hover .pager-title-left,.halaman-kiri:hover .current-pageleft,.halaman-kanan:hover .current-pageright{color:rgba(255,255,255,1);}
#blog-pager,.isihalaman-kanan,.isihalaman-kiri{margin:0}
.panahkanan,.panahkiri{position:absolute;top:50%;margin-top:-8px}
.panahkiri{left:10px}
.panahkanan{right:10px}
.comments-content {display:block;position:relative;margin-top:20px;}
#HTML1{width:100%;max-width:300px}
/* CSS Item Responsive */
@media only screen and (max-width:960px){
.bagidua,.bagitiga,.bagiempat{-webkit-column-count:2;-moz-column-count:2;column-count:2;}}
@media only screen and (max-width:800px){
#HTML1{max-width:100%;position:relative!important;top:initial!important}}
@media only screen and (max-width:640px){
h1.post-title.entry-title,h2.post-title.entry-title{font-size:16px;}
#related-post h4{margin:0 0 5px;border-bottom:1px solid rgba(0,0,0,0.12)}
ul#related-summary li{float:left;list-style:none;overflow:hidden;width:50%;padding:10px 0;height:160px;margin:0}
ul#related-summary li a.relinkjdulx{font-size:12px;font-weight:400;padding:5px 5px 5px 4px}
ul#related-summary li .overlaytext{float:left;display:inline-block;font-size:12px;font-weight:700;line-height:normal;overflow:hidden;padding:0}
ul#related-summary li .overlayb{display:inline-block;float:left;height:auto;margin:0 4px}
ul#related-summary li img{height:auto;}
.sharesimply a.fb,.sharesimply a.gp,.sharesimply a.tw{width:100%}
.bagidua,.bagitiga,.bagiempat{-webkit-column-count:1;-moz-column-count:1;column-count:1;}
#searchbar form:after {right:12%;top:40%;}}
@media screen and (max-width:603px){
.halaman-kanan,.halaman-kiri{width:100%;padding:15px 0;height:auto;border:0;}
.halaman-kanan{background:#95a5a6;color:#fff}
.halaman-kiri{background:#fff;}
.halaman-kanan a{color:#fff}
.isihalaman-kiri{margin-left:40px!important}
.isihalaman-kanan{margin-right:40px!important}
.panahkanan,.panahkiri{margin-top:-6px}
.avatar-container,.label-info{display:none}}
</style>
<script type='text/javascript'>/*<![CDATA[*/function saringtags(r,l){for(var e=r.split("<"),n=0;n<e.length;n++)-1!=e[n].indexOf(">")&&(e[n]=e[n].substring(e[n].indexOf(">")+1,e[n].length));return e=e.join(""),e=e.substring(0,l-1)}function relpostimgcuplik(r){for(var l=0;l<r.feed.entry.length;l++){var e=r.feed.entry[l];reljudul[relnojudul]=e.title.$t,postcontent="","content"in e?postcontent=e.content.$t:"summary"in e&&(postcontent=e.summary.$t),relcuplikan[relnojudul]=saringtags(postcontent,numchars),"media$thumbnail"in e?postimg=e.media$thumbnail.url:postimg="http://1.bp.blogspot.com/-htG7vy9vIAA/Tp0KrMUdoWI/AAAAAAAABAU/e7XkFtErqsU/s1600/grey.GIF",relgambar[relnojudul]=postimg;for(var n=0;n<e.link.length;n++)if("alternate"==e.link[n].rel){relurls[relnojudul]=e.link[n].href;break}relnojudul++}}function contains(r,l){for(var e=0;e<r.length;e++)if(r[e]==l)return!0;return!1}function artikelterkait(){for(var r=new Array(0),l=new Array(0),e=new Array(0),n=new Array(0),t=0;t<relurls.length;t++)contains(r,relurls[t])||(r.length+=1,r[r.length-1]=relurls[t],l.length+=1,l[l.length-1]=reljudul[t],e.length+=1,e[e.length-1]=relcuplikan[t],n.length+=1,n[n.length-1]=relgambar[t]);reljudul=l,relurls=r,relcuplikan=e,relgambar=n;for(var t=0;t<reljudul.length;t++){var a=Math.floor((reljudul.length-1)*Math.random()),u=reljudul[t],i=relurls[t],o=relcuplikan[t],s=relgambar[t];reljudul[t]=reljudul[a],relurls[t]=relurls[a],relcuplikan[t]=relcuplikan[a],relgambar[t]=relgambar[a],reljudul[a]=u,relurls[a]=i,relcuplikan[a]=o,relgambar[a]=s}for(var g,m=0,d=Math.floor((reljudul.length-1)*Math.random()),c=d,h=document.URL;relmaxtampil>m&&(relurls[d]==h||(g="<li class='news-title clearfix'>",g+="<a href='"+relurls[d]+"' rel='nofollow' target='_top' title='"+reljudul[d]+"'><div class='overlayb'><img src='"+relgambar[d]+"' /></div></a>",g+="<div class='overlaytext'><a class='relinkjdulx' href='"+relurls[d]+"' target='_top'>"+reljudul[d]+"</a></div>",g+="<span class='news-text'>"+relcuplikan[d]+"</span>",g+="</li>",document.write(g),m++,m!=relmaxtampil))&&(d<reljudul.length-1?d++:d=0,d!=c););}var relnojudul=0,relmaxtampil=6,numchars=90,reljudul=new Array,relurls=new Array,relcuplikan=new Array,relgambar=new Array;/*]]>*/</script>
</b:if>
<b:if cond='data:blog.pageType == &quot;static_page&quot;'>
<style type='text/css'>
h1.post-title.entry-title,h2.post-title.entry-title,h3.post-title.entry-title,h4.post-title.entry-title{color:#138be6;padding:15px;font-size:24px;margin:0;border-bottom:1px solid rgba(0,0,0,0.14);}
#sidebar-wrapper {display:none;}
#main-wrapper {width:100%;float:none;border:0;}
/* Arlina Post Navigation */
#blog-pager{position:relative;display:block;width:100%;margin:20px 10px 20px 0;text-align:center}
#blog-pager-newer-link{float:left}#blog-pager-older-link{float:right}
#blog-pager a:link,#blog-pager a:visited{display:inline-block;color:#fff;font-size:14px!important;padding:10px 20px;margin:5px;background:#5cb9c1;text-transform:uppercase;font-weight:700;transition:all .3s}
#blog-pager a:link:hover,#blog-pager a:visited:hover{background:#127c7a;color:#fff;}
#blog-pager{text-align:center;border:0}
.comments-content {display:block;position:relative;margin-top:20px;}
</style>
</b:if>
<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
<style type='text/css'>
.header-wrapper, #header, #outer-wrapper, #post-wrapper, #sidebar-wrapper, #content-wrapper,#footer-wrapper,#simplify-nav,#wrapper,.simplifytotop.arlniainf,.simplifytotop,.simplify-menu_wrapper{display:none;}
body,html{overflow:hidden;margin:0;padding:0;width:100%;min-height:100vh;}
body{background:#fa4949;color:#fff;}
.simplify-menu_wrapper{background:rgba(0,0,0,0.5);border-bottom:1px solid rgba(0,0,0,0.05)}
.container404{margin:8% auto 0 auto;max-width:768px;min-width:200px;line-height:normal;font-size:16px;backface-visibility:hidden;transition:all .3s;}
.box404 hr{background:transparent;display:block;border:none;border-bottom:4px solid rgba(255,255,255,.3)}
.box404{padding:20px;font-size:110%;color:#fff;border-radius:5px 5px 0 0}
.box404 h2,.box404 h3{color:#fff;display:block;font-weight:700;font-size:2.6rem;text-transform:uppercase}
.box404 h2{position:absolute;font-size:20rem;color:rgba(255,255,255,.3);transform:rotate(-45deg);right:3%;bottom:8%}
.box404 p{display:block;margin:10px 0}
.box404 ul li{margin:0 0 8px 20px;list-style:initial;list-style-type:square}
.box404 ul li a{color:#e5ffaf;}.box404 ul li a:hover{background:rgba(0,0,0,0.1);color:#e5ffaf;text-decoration:underline}
.copyright404{display:block;margin:auto;font-weight:normal;max-width:768px;min-width:200px;padding:0 20px}
.copyright404 a,.copyright404 a:hover{color:#fff}
@media screen and (max-width:1024px) {
.box404 h2{font-size:10rem;}
.container404{margin:4% auto 0 auto;}}
@media screen and (max-width:640px) {
.box404 h3{font-size:1.6rem;}
.box404 h2{display:none}}
</style>
</b:if>
<script type='text/javascript'>
(function() { var ad = document.createElement(&#39;script&#39;); ad.type = &#39;text/javascript&#39;; ad.async = true; ad.src = &#39;https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js&#39;; var sc = document.getElementsByTagName(&#39;script&#39;)[0]; sc.parentNode.insertBefore(ad, sc); })();
//<![CDATA[
//CSS Ready
function loadCSS(e, t, n) { "use strict"; var i = window.document.createElement("link"); var o = t || window.document.getElementsByTagName("script")[0]; i.rel = "stylesheet"; i.href = e; i.media = "only x"; o.parentNode.insertBefore(i, o); setTimeout(function () { i.media = n || "all" }) }
loadCSS("https://fonts.googleapis.com/css?family=Roboto:400,400italic,700,700italic");loadCSS("https://maxcdn.bootstrapcdn.com/font-awesome/4.6.0/css/font-awesome.min.css");
//]]>
</script>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<script type='text/javascript'>
snippet_count = 120;
//<![CDATA[
function removeHtmlTag(n,e){if(-1!=n.indexOf("<")){for(var t=n.split("<"),i=0;i<t.length;i++)-1!=t[i].indexOf(">")&&(t[i]=t[i].substring(t[i].indexOf(">")+1,t[i].length));n=t.join("")}for(e=e<n.length-1?e:n.length-2;" "!=n.charAt(e-1)&&-1!=n.indexOf(" ",e);)e++;return n=n.substring(0,e-1),n+"..."}function createSnippet(n){var e=document.getElementById(n),t=snippet_count,i='<div class="snippets">'+removeHtmlTag(e.innerHTML,t)+"..."+"</div>";e.innerHTML=i}
//]]>
</script>
</b:if>
</b:if>
</head>
<!-- <body><div></div> -->
<body expr:class='&quot;loading&quot; + data:blog.mobileClass'>
<div class='simplify-menu_wrapper'>
<div class='maxwrap'>
<nav class='simplify-menu' itemscope='itemscope' itemtype='http://schema.org/SiteNavigationElement' role='navigation'>
 <ul>
   <li><a href='http://largehiph0p.blogspot.com/p/contact-us_13.html' itemprop='url' title='Contact Us'><span itemprop='name'>Contact Us</span></a></li>
   <li><a href='http://largehiph0p.blogspot.com/p/this-blog-does-not-store-files-on-its.html' itemprop='url' title='Disclaimer'><span itemprop='name'>Disclaimer</span></a></li>
   <li><a href='http://largehiph0p.blogspot.com/p/dmca.html' itemprop='url' title='DMCA'><span itemprop='name'>DMCA</span></a></li>
    </ul>  
    <div class='clear'/>
</nav>
<div class='sosial-atas'>
  <li class='menu-item'>
    <a href='https://twitter.com/LargehiphopCom' rel='nofollow' target='_blank' title='Follow Our Twitter'><i class='fa fa-twitter'/></a>
  </li>
</div>
<div class='search-box'>
<form action='/search' id='searchform' method='get'>
<input id='search-form' name='q' placeholder='Search' type='text'/>
    <span class='search-button'><i class='fa fa-search'/></span>
</form>
</div>
<div class='clear'/>
</div>
</div>
<div id='header' itemscope='itemscope' itemtype='http://schema.org/WPHeader'>
<div class='maxwrap'>
<div id='headersticky'>
   <b:section id='headerdua' maxwidgets='1' showaddelement='no'>
     <b:widget id='Header1' locked='true' title='largehiphop (Header)' type='Header' version='1'>
       <b:widget-settings>
         <b:widget-setting name='displayUrl'>http://3.bp.blogspot.com/-PQh6KScwp3k/WR1GhBKXfvI/AAAAAAAAA4Q/IT_HSkB72ygux8pEQz4zlxXNfDcRcp-OQCK4B/s1600/122.jpg</b:widget-setting>
         <b:widget-setting name='displayHeight'>53</b:widget-setting>
         <b:widget-setting name='sectionWidth'>273</b:widget-setting>
         <b:widget-setting name='useImage'>true</b:widget-setting>
         <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
         <b:widget-setting name='imagePlacement'>REPLACE</b:widget-setting>
         <b:widget-setting name='displayWidth'>206</b:widget-setting>
       </b:widget-settings>
       <b:includable id='main'>
  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <b:if cond='data:mobile'>
          <div id='header-inner'>
            <div class='titlewrapper' style='background: transparent'>
                <b:include name='title'/>
            </div>
            <b:include name='description'/>
          </div>
        <b:else/>
          <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                        + &quot;background-position: &quot;                        + data:backgroundPositionStyleStr + &quot;; &quot;                        + data:widthStyleStr                        + &quot;min-height: &quot; + data:height                        + &quot;_height: &quot; + data:height                        + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
            <div class='titlewrapper' style='background: transparent'>
                <b:include name='title'/>
            </div>
            <b:include name='description'/>
          </div>
        </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>

        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
          <b:include name='title'/>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
       <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
       <b:includable id='title'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'>
    <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
      <h1 class='title'>
        <a expr:href='data:blog.homepageUrl' expr:title='data:blog.title' itemprop='url'>
          <span itemprop='name'><data:title/></span>
        </a>
      </h1>
      <b:else/>
      <h2 class='title'>
        <a expr:href='data:blog.homepageUrl' expr:title='data:blog.title' itemprop='url'>
          <span itemprop='name'><data:title/></span>
        </a>
      </h2>
    </b:if>
    <b:else/>
    <h2 class='title'>
      <a expr:href='data:blog.homepageUrl' expr:title='data:blog.title' itemprop='url'>
        <span itemprop='name'><data:title/></span>
      </a>
    </h2>
      </b:if>
</b:includable>
     </b:widget>
   </b:section>
<nav id='simplify-nav' itemscope='itemscope' itemtype='http://schema.org/SiteNavigationElement'>
<div class='maxwrap'>


<li><a href='http://largehiph0p.blogspot.com/' itemprop='url'><span itemprop='name'>Home</span></a></li>
<li><a href='https://largehiph0p.blogspot.com/search/label/Releases%202017' itemprop='url'><span itemprop='name'>Releases 2017</span></a></li>
<li><a href='http://largehiph0p.blogspot.com/search/label/Albums' itemprop='url'><span itemprop='name'>Albums</span></a></li>
<li><a href='http://largehiph0p.blogspot.com/search/label/Instrumentals' itemprop='url'><span itemprop='name'>Instrumentals</span></a></li>
</div>
</nav>
</div>
</div>
</div>
<div class='clear'/>
<div id='wrapper'>
  <div id='content-wrapper' itemscope='itemscope' itemtype='http://schema.org/Blog' role='main'>
  <b:section class='banner section' id='banner' maxwidgets='1' showaddelement='yes'/>
<div class='clear'/>
    <div id='main-wrapper'>
      <b:section class='main' id='main' showaddelement='no'>
        <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='1'>
          <b:widget-settings>
            <b:widget-setting name='commentLabel'>коммент.</b:widget-setting>
            <b:widget-setting name='showShareButtons'>true</b:widget-setting>
            <b:widget-setting name='authorLabel'>By</b:widget-setting>
            <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
            <b:widget-setting name='timestampLabel'>на</b:widget-setting>
            <b:widget-setting name='reactionsLabel'>Действия:</b:widget-setting>
            <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
            <b:widget-setting name='style.layout'>1x1</b:widget-setting>
            <b:widget-setting name='showLocation'>false</b:widget-setting>
            <b:widget-setting name='showTimestamp'>true</b:widget-setting>
            <b:widget-setting name='postsPerAd'>1</b:widget-setting>
            <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
            <b:widget-setting name='backlinksLabel'>Ссылки на это сообщение</b:widget-setting>
            <b:widget-setting name='showDateHeader'>true</b:widget-setting>
            <b:widget-setting name='style.textcolor'>#000000</b:widget-setting>
            <b:widget-setting name='showCommentLink'>true</b:widget-setting>
            <b:widget-setting name='style.urlcolor'>#008000</b:widget-setting>
            <b:widget-setting name='postLocationLabel'>Место:</b:widget-setting>
            <b:widget-setting name='showAuthor'>false</b:widget-setting>
            <b:widget-setting name='style.linkcolor'>#0000ff</b:widget-setting>
            <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
            <b:widget-setting name='showLabels'>true</b:widget-setting>
            <b:widget-setting name='postLabelsLabel'>Tags:</b:widget-setting>
            <b:widget-setting name='showBacklinks'>false</b:widget-setting>
            <b:widget-setting name='showInlineAds'>false</b:widget-setting>
            <b:widget-setting name='showReactions'>false</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main' var='top'>
          <b:include data='posts' name='breadcrumb'/>
        <b:if cond='data:mobile == &quot;false&quot;'>
          <!-- posts -->
          <div class='blog-posts hfeed'>
            <b:include data='top' name='status-message'/>
            <data:defaultAdStart/>
            <b:loop values='data:posts' var='post'>
              <b:if cond='data:post.isDateStart'>
                <b:if cond='data:post.isFirstPost == &quot;false&quot;'>
                  &lt;/div&gt;&lt;/div&gt;
                </b:if>
              </b:if>
              <b:if cond='data:post.isDateStart'>
                &lt;div class=&quot;date-outer&quot;&gt;
              </b:if>
              <b:if cond='data:post.dateHeader'>
                <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
              </b:if>
              <b:if cond='data:post.isDateStart'>
                &lt;div class=&quot;date-posts&quot;&gt;
              </b:if>
              <div class='post-outer'>
              <b:include data='post' name='post'/>
              <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                <b:if cond='data:post.showThreadedComments'>
                  <b:include data='post' name='comments'/>
                <b:else/>
                  <b:include data='post' name='comments'/>
                </b:if>
              </b:if>
              <b:if cond='data:blog.pageType == &quot;item&quot;'>
                <b:if cond='data:post.showThreadedComments'>
                  <b:include data='post' name='comments'/>
                <b:else/>
                  <b:include data='post' name='comments'/>
                </b:if>
              </b:if>
              </div>
              <b:if cond='data:post.includeAd'>
                <b:if cond='data:post.isFirstPost'>
                  <data:defaultAdEnd/>
                <b:else/>
                  <data:adEnd/>
                </b:if>
                <div class='inline-ad'>
                  <data:adCode/>
                </div>
                <data:adStart/>
              </b:if>
            </b:loop>
            <b:if cond='data:numPosts != 0'>
              &lt;/div&gt;&lt;/div&gt;
            </b:if>
            <data:adEnd/>
          </div>
    <!-- navigation -->
	<b:if cond='data:blog.pageType == &quot;index&quot;'>
		<b:include name='nextprev'/>
    <b:else/>
    <b:if cond='data:blog.pageType == &quot;archive&quot;'>
        <b:include name='nextprev'/>
	</b:if>
	</b:if>
          <!-- feed links -->
          <b:include name='feedLinks'/>
          <b:if cond='data:top.showStars'>
<script src='//www.google.com/jsapi' type='text/javascript'/>
<script type='text/javascript'>
google.load(&quot;annotations&quot;, &quot;1&quot;, {&quot;locale&quot;: &quot;<data:top.languageCode/>&quot;});
function initialize() {google.annotations.setApplicationId(<data:top.blogspotReviews/>);google.annotations.createAll();google.annotations.fetch();}google.setOnLoadCallback(initialize);
</script>
</b:if>
<b:else/>
<b:include name='mobile-main'/>
</b:if>
        <b:if cond='data:top.showDummy'>
          <data:top.dummyBootstrap/>
        </b:if>
      </b:includable>
          <b:includable id='backlinkDeleteIcon' var='backlink'>
        <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
          <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
            <img src='//www.blogger.com/img/icon_delete13.gif'/>
          </a>
        </span>
      </b:includable>
          <b:includable id='backlinks' var='post'>
        <a name='links'/><h4><data:post.backlinksLabel/></h4>
        <b:if cond='data:post.numBacklinks != 0'>
          <dl class='comments-block' id='comments-block'>
            <b:loop values='data:post.backlinks' var='backlink'>
              <div class='collapsed-backlink backlink-control'>
                <dt class='comment-title'>
                  <span class='backlink-toggle-zippy'>&#160;</span>
                  <a expr:href='data:backlink.url' rel='nofollow'><data:backlink.title/></a>
                  <b:include data='backlink' name='backlinkDeleteIcon'/>
                </dt>
                <dd class='comment-body collapseable'>
                  <data:backlink.snippet/>
                </dd>
                <dd class='comment-footer collapseable'>
                  <span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span>
                  <span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span>
                </dd>
              </div>
            </b:loop>
          </dl>
        </b:if>
        <p class='comment-footer'>
          <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'><data:post.createLinkLabel/></a>
        </p>
      </b:includable>
          <b:includable id='breadcrumb' var='posts'>
      <b:if cond='data:blog.homepageUrl != data:blog.url'>
      <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
      <div class='breadcrumbs'><span class='breadhome'><a expr:href='data:blog.homepageUrl' rel='tag'>Home</a> <i class='fa fa-angle-right'/></span><span class='breadlabel'><data:blog.pageName/></span></div>
      <b:else/>
      <b:if cond='data:blog.pageType == &quot;item&quot;'>
      <!-- breadcrumb for the post page -->
      <b:loop values='data:posts' var='post'>
      <b:if cond='data:post.labels'>
      <div class='breadcrumbs' xmlns:v='http://rdf.data-vocabulary.org/#'>
      <span class='breadhome' typeof='v:Breadcrumb'><a expr:href='data:blog.homepageUrl' property='v:title' rel='v:url'>Home</a> <i class='fa fa-angle-right'/></span>
      <b:loop values='data:post.labels' var='label'>
      <span class='breadlabel' typeof='v:Breadcrumb'><a expr:href='data:label.url + &quot;?&amp;amp;max-results=7&quot;' property='v:title' rel='v:url'><data:label.name/></a> <i class='fa fa-angle-right'/></span>
      </b:loop>
      <span class='breadlabel'><data:post.title/></span>
      </div>
      <b:else/>
      <div class='breadcrumbs'><span class='breadhome'><a expr:href='data:blog.homepageUrl' rel='tag'>Home</a> <i class='fa fa-angle-right'/></span><span class='breadlabel'>Unlabelled</span> <span class='breadlabel'><data:post.title/></span></div>
      </b:if>
      </b:loop>
      <b:else/>
      <b:if cond='data:blog.pageType == &quot;archive&quot;'>
      <!-- breadcrumb for the label archive page and search pages.. -->
      <div class='breadcrumbs'>
        <span class='breadhome'><a expr:href='data:blog.homepageUrl'>Home</a> <i class='fa fa-angle-right'/></span><span>Archives for <data:blog.pageName/></span>
      </div>
      <b:else/>
      <b:if cond='data:blog.pageType == &quot;index&quot;'>
      <div class='breadcrumbs'>
      <b:if cond='data:blog.pageName == &quot;&quot;'>
        <span class='breadhome'><a expr:href='data:blog.homepageUrl'>Home</a> <i class='fa fa-angle-right'/></span><span class='breadlabel'>All posts </span>
      <b:else/>
        <span class='breadhome'> <a expr:href='data:blog.homepageUrl'>Home</a> <i class='fa fa-angle-right'/></span><span class='breadlabel'>Posts filed under <data:blog.pageName/></span>
      </b:if>
      </div>
      </b:if>
      </b:if>
      </b:if>
      </b:if>
      </b:if>
      </b:includable>
          <b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <h4 id='comment-post-message'><data:postCommentMsg/></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
          <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
        <img src='https://img1.blogblog.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
          <b:includable id='comment_count_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.url.canonical.http'>
    </span>
  <b:else/>
    <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
      <data:post.commentLabelFull/>:
    </a>
  </b:if>
</b:includable>
          <b:includable id='comment_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <b:include data='post' name='iframe_comments'/>
  <b:elseif cond='data:post.showThreadedComments'/>
    <b:include data='post' name='comments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
          <b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <b:if cond='data:post.allowComments'>
      <b:if cond='data:post.numComments != 0'>
        <h3>
    <b:if cond='data:post.numComments == 1'>1 <data:commentLabel/> so far
     <b:else/>
     <data:post.numComments/> <data:commentLabelPlural/>
    </b:if>
   </h3>
      </b:if>
      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
    <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
    &#160;
    <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
    &#160;
    <data:post.commentRangeText/>
    &#160;
    <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
    &#160;
    <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
   </span>
      </b:if>
      <div class='clear'/>
      <div id='comment_block'>
        <b:loop values='data:post.comments' var='comment'>
          <div class='data:comment.adminClass' expr:id='data:comment.anchorName'>
            <b:if cond='data:post.adminClass == data:comment.adminClass'>
              &lt;div class=&#39;comment_inner comment_admin&#39;&gt;
              <b:else/> &lt;div class=&#39;comment_inner&#39;&gt;
            </b:if>
            <div class='comment_header'>
              <div class='comment_avatar_wrap'>
                <div class='comment_avatar'>
                  <img alt='avatar' expr:src='data:comment.authorAvatarSrc' expr:title='data:comment.author'/>
                </div>
                <a class='comment_reply' expr:href='&quot;#r_&quot;+data:comment.anchorName' expr:id='&quot;r&quot;+data:comment.anchorName' onclick='javascript:Display_Reply_Form(this)' title='Balas'>Balas</a>
              </div>
              <div class='clear'/>
            </div>
            <div class='comment_body'>
              <div class='comment_name'>
                <b:if cond='data:comment.authorUrl'>
                  <a expr:href='data:comment.authorUrl' expr:title='data:comment.author' rel='nofollow' target='_blank'>
                    <data:comment.author/>
                  </a>
                  <b:else/>
                  <data:comment.author/>
                </b:if>
                <b:if cond='data:comment.author == data:post.author'>
                  <span class='comment_author_flag'><i class='fa fa-check-circle' title='Verified Author'/></span>
                </b:if>
                <span class='comment_service'>
      <a class='comment-delete' expr:href='&quot;http://www.blogger.com/delete-comment.g?blogID=&quot; + data:blog.blogId + &quot;&amp;amp;postID=&quot; + data:comment.id' expr:title='data:top.deleteCommentMsg'>
<img alt='delete' src='http://2.bp.blogspot.com/-d-5BS0YCkho/UOKe2UIw0rI/AAAAAAAAC4w/md_iYNVHaHk/s1600/delete4.png' title='Hapus Komentar'/>
</a>                
      <span class='comment_date'><a expr:href='data:comment.url' rel='nofollow' title='comment permalink'>
                  <data:comment.timestamp/>
        </a></span>
                </span>
              </div>
              <b:if cond='data:comment.isDeleted'>
                <span class='deleted-comment'><data:comment.body/></span>
                <b:else/>
                <p>
                  <data:comment.body/>
                </p>
                <div class='clear'/>
              </b:if>
            </div>
            <div class='clear'/> &lt;/div&gt;
            <div class='clear'/>
            <div class='comment_child'/>
            <div class='comment_reply_form' expr:id='&quot;r_f_&quot;+data:comment.anchorName'/>
          </div>
        </b:loop>
      </div>
      <div class='clear'/>
      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
       <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
       &#160;
       <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
       &#160;
       <data:post.commentRangeText/>
       &#160;
       <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
       &#160;
       <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
     </span>
      </b:if>
      <div class='clear'/>
      <div class='comment_form'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='threaded-comment-form'/>
            <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
          <b:else/>
          <b:if cond='data:post.allowComments'>
            <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick' expr:title='data:postCommentMsg'>
              <data:postCommentMsg/>
            </a>
          </b:if>
        </b:if>
      </div>
    </b:if>
  </div>
<script type='text/javascript'>
//<![CDATA[
if (typeof(jQuery) == 'undefined') {
//output the script (load it from google api)
 document.write("<scr" + "ipt type=\"text/javascript\" src=\"http://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js\"></scr" + "ipt>");
}
//]]>
</script>
<script async='async' src='//www.blogblog.com/dynamicviews/4224c15c4e7c9321/js/comments.js' type='text/javascript'/>
<script type='text/javascript'>

<b:if cond='data:post.numComments != 0'>
         var Items = <data:post.commentJso/>;
         var Msgs = <data:post.commentMsgs/>;
         var Config = <data:post.commentConfig/>;
        <b:else/>
         var Items = {};
         var Msgs = {};
         var Config = {&#39;maxThreadDepth&#39;:&#39;0&#39;};
        </b:if>
       //<![CDATA[
       //Global setting
        Config.maxThreadDepth = 3;//Kedalaman tingkat threaded comment
        Display_Emo = true;//Tampilkan emoticon? ketik "false" untuk menyembunyikan
        Replace_Youtube_Link = false;//Embed video YouTube, ketik "false" untuk mendisable
        Replace_Image_Link = false;//Auto replace link image,  ketik "false" untuk mendisable.
        Replace_Force_Tag = false;//Auto replace virtual tag contoh: [pre] menjadi <pre>, dan [/pre] menjadi </pre>, apabila salah menulis, tidak akan berfungsi
        Replace_Image_Ext = ['JPG', 'GIF', 'PNG', 'BMP'];//(support: jpg, gif, png, bmp),hanya berfungsi apabila Replace_Image_Link=true
        //Pengaturan Emoticon
        Emo_List = [
':)'  	,'http://twemoji.maxcdn.com/36x36/1f600.png',
':('  	,'http://twemoji.maxcdn.com/36x36/1f615.png',
'hihi'  ,'http://twemoji.maxcdn.com/36x36/1f601.png',
':-)'  	,'http://twemoji.maxcdn.com/36x36/1f60f.png',
':D'  	,'http://twemoji.maxcdn.com/36x36/1f603.png',
'=D'  	,'http://twemoji.maxcdn.com/36x36/1f62c.png',
':-d'  	,'http://twemoji.maxcdn.com/36x36/1f604.png',
';('  	,'http://twemoji.maxcdn.com/36x36/1f61e.png',
';-('  	,'http://twemoji.maxcdn.com/36x36/1f62d.png',
'@-)'   ,'http://twemoji.maxcdn.com/36x36/1f616.png',
':o'	,'http://twemoji.maxcdn.com/36x36/1f62e.png',     
':&gt;)','http://twemoji.maxcdn.com/36x36/1f606.png',     
'(o)'	,'http://twemoji.maxcdn.com/36x36/1f609.png',     
':p'	,'http://twemoji.maxcdn.com/36x36/1f614.png',     
':-?'	,'http://twemoji.maxcdn.com/36x36/2753.png', 
'(p)'	,'http://twemoji.maxcdn.com/36x36/1f619.png', 
':-s'	,'http://twemoji.maxcdn.com/36x36/1f625.png',
'8-)'	,'http://twemoji.maxcdn.com/36x36/1f60e.png',
':-t'	,'http://twemoji.maxcdn.com/36x36/1f624.png',
':-b'	,'http://twemoji.maxcdn.com/36x36/1f634.png',
'b-('	,'http://twemoji.maxcdn.com/36x36/1f635.png',
'(y)'	,'http://twemoji.maxcdn.com/36x36/1f44d.png',
'x-)'	,'http://twemoji.maxcdn.com/36x36/1f60d.png',
'(h)'	,'http://twemoji.maxcdn.com/36x36/1f44f.png',   
        ];
                                //Config Force tag list, define all in lower case
                                Force_Tag = [
                                    '[pre]','<pre>',
                                    '[/pre]','</pre>',
                                    '<pre class="brush: plain; title: ; notranslate" title="">','&lt;code&gt;',
                                    '</pre>','</code>'
                                ];
eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('3 o=\'.1c\';3 1b=$(\'#O-19\').G(\'A\');u 1l(F){3 1j=\' \\n\\r\\t\\f\\1D\\1G\\1F\\1E\\2l\\2k\\2i\\2f\\2c\\26\\25\\23\\1Y\\1S\\1N\\1L\\1H\\2v\\1M\\2p\\24\\22\\1R\';E(3 i=0;i<F.5;i++){9(1j.d(F.1Q(i))!=-1){F=F.b(0,i);11}}z F}$(\'#1P .1i p\').j(u(y,7){9(1J){3 l=\'1v://13.V.W/1y?v=\';3 8=7.d(l);D(8!=-1){1d=7.b(8);J=1l(1d);3 X=J.d(\'&\');3 N=\'\';9(X==-1){N=J.b(l.5)}Y{N=J.b(l.5,X)}3 1r=\'<1u B="1T" A="1v://13.V.W/1U/\'+N+\'?1V=1" 1W="0" 2w></1u>\';7=7.b(0,8)+1r+7.b(8+J.5);8=7.d(l);9(8==-1){l=\'1Z://13.V.W/1y?v=\';8=7.d(l)}}}9(21){3 Z=\'\';3 s=7;E(3 i=0;i<1w.5;i++){3 l=\'.\'+1w[i];3 m=s.C();3 8=m.d(l);D(8!=-1){k=s.b(0,8+l.5);m=k.C();3 q=\'2h://\';3 w=m.d(q);3 I=\'\';D(w!=-1){I=q.M();k=k.b(w+q.5);m=k.C();w=m.d(q)}q=\'2n://\';m=k.C();w=m.d(q);D(w!=-1){I=q.M();k=k.b(w+q.5);m=k.C();w=m.d(q)}9(I==\'\'||k.5<6){11}k=I+k;Z+=s.b(0,8+l.5-k.5)+\'<10 A="\'+k+\'" B="2r"/>\';s=s.b(8+l.5);m=s.C();8=m.d(l)}}7=Z+s}9(1A){3 5=x.5;9(5%2==1){5--}E(3 i=0;i<5;i+=2){3 S=\'<10 A="\'+x[i+1]+\'" B="1B"/>\';8=7.d(x[i]);D(8!=-1){7=7.b(0,8)+S+7.b(8+x[i].5);8=7.d(x[i])}}}9(1I){3 5=R.5;9(5%2==1){5--}E(3 i=0;i<5;i+=2){D(1){3 s=7.M();8=s.d(R[i]);9(8!=-1){7=7.b(0,8)+R[i+1]+7.b(8+R[i].5)}Y{11}}}}z 7});$(\'.1K\').j(u(y,7){9(1A){3 5=x.5;9(5%2==1){5--}3 12=\'\';E(3 i=0;i<5;i+=2){3 1e=\'<1f>\'+x[i]+\'</1f>\';3 S=\'<10 A="\'+x[i+1]+\'" B="1B"/>\';12+=\'<Q B="1O">\'+S+1e+\'</Q>\'}z 12}});$(\'.1g .1i p\').j(u(i,h){T=h.M();y=T.d(\'@<a U="#c\');9(y!=-1){14=T.d(\'</a>\',y);9(14!=-1){h=h.b(0,y)+h.b(14+4)}}z h});u 1k(g){r=g.d(\'c\');9(r!=-1)g=g.b(r+1);z g}u 1m(g){g=\'&1X=\'+g+\'#%1n\';1o=1b.20(/#%1n/,g);z 1o}u 1p(){j=$(o).j();$(o).j(\'\');o=\'.1c\';$(o).j(j);$(\'#O-19\').G(\'A\',1b)}u 1q(e){g=$(e).G(\'15\');g=1k(g);j=$(o).j();9(o==\'.1c\'){1s=\'<a U="#1t" 27="1p()">\'+28.29+\'</a><a 2a="1t"/>\';$(o).j(1s)}Y{$(o).j(\'\')}o=\'#2b\'+g;$(o).j(j);$(\'#O-19\').G(\'A\',1m(g))}16=2d.2e.U;17=\'#O-2g\';18=16.d(17);9(18!=-1){1x=16.b(18+17.5);1q(\'#2j\'+1x)}E(3 i=0;i<P.5;i++){9(\'1z\'2m P[i]){3 g=P[i].1z;3 1a=2o($(\'#c\'+g+\':L\').G(\'1C\'));$(\'#c\'+g+\' .2q:L\').j(u(y,7){3 H=P[i].15;9(1a>=2s.2t){$(\'#c\'+H+\':L .2u\').1h()}3 K=$(\'#c\'+H+\':L\').j();K=\'<Q B="1g" 15="c\'+H+\'" 1C="\'+(1a+1)+\'">\'+K+\'</Q>\';$(\'#c\'+H).1h();z(7+K)})}}',62,157,'|||var||length||oldhtml|check_index|if||substring||indexOf|||par_id|||html|img_src|search_key|upper_html||Cur_Cform_Hdr||http_search||temp_html||function||find_http|Emo_List|index|return|src|class|toUpperCase|while|for|str|attr|child_id|save_http|yt_link|child_html|first|toLowerCase|yt_code|comment|Items|div|Force_Tag|img_html|temp|href|youtube|com|yt_code_index|else|save_html|img|break|newhtml|www|index_tail|id|cur_url|search_formid|search_index|editor|par_level|Cur_Cform_Url|comment_form|ht|img_code|span|comment_wrap|remove|comment_body|whitespace|Valid_Par_Id|trim|Cform_Ins_ParID|7B|n_cform_url|Reset_Comment_Form|Display_Reply_Form|yt_video|reset_html|origin_cform|iframe|http|Replace_Image_Ext|ret_id|watch|parentId|Display_Emo|comment_emo|level|x5b|x7d|x7c|x5d|u2008|Replace_Force_Tag|Replace_Youtube_Link|comment_emo_list|u2007|u200a|u2006|item|comment_block|charAt|u3000|u2005|comment_youtube|embed|autohide|frameborder|parentID|u2004|https|replace|Replace_Image_Link|u2029|u2003|u2028|u2002|u2001|onclick|Msgs|addComment|name|r_f_c|u2000|window|location|xa0|form_|HTTP|x0b|rc|x3e|x3c|in|HTTPS|parseInt|u200b|comment_child|comment_img|Config|maxThreadDepth|comment_reply|u2009|allowfullscreen'.split('|'),0,{}))   
var avatar=$("#comments");avatar.find('.comment_avatar img').each(function() {var ava = $(this).attr('src');$(this).show().attr('src', ava.replace(/\/s[0-9]+(\-c)?\//,"/s45-c/"));});var _0xf2c9=["\x73\x63\x72\x65\x65\x6E\x20\x61\x6E\x64\x20\x28\x6D\x69\x6E\x2D\x77\x69\x64\x74\x68\x3A\x20\x36\x30\x65\x6D\x29","\x6D\x61\x74\x63\x68\x4D\x65\x64\x69\x61","\x6D\x61\x74\x63\x68\x65\x73","\x6F\x6E\x6C\x6F\x61\x64","\x6C\x69\x67\x68\x74\x63\x72\x65\x64\x69\x74","\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x42\x79\x49\x64","\x68\x72\x65\x66","\x6C\x6F\x63\x61\x74\x69\x6F\x6E","\x68\x74\x74\x70\x3A\x2F\x2F\x77\x77\x77\x2E\x61\x72\x6C\x69\x6E\x61\x64\x7A\x67\x6E\x2E\x63\x6F\x6D","\x73\x65\x74\x41\x74\x74\x72\x69\x62\x75\x74\x65","\x72\x65\x6C","\x6E\x6F\x66\x6F\x6C\x6C\x6F\x77","\x69\x6E\x6E\x65\x72\x48\x54\x4D\x4C","\x3C\x61\x20\x68\x72\x65\x66\x3D\x27\x68\x74\x74\x70\x3A\x2F\x2F\x77\x77\x77\x2E\x61\x72\x6C\x69\x6E\x61\x64\x7A\x67\x6E\x2E\x63\x6F\x6D\x2F\x27\x20\x74\x61\x72\x67\x65\x74\x3D\x27\x5F\x62\x6C\x61\x6E\x6B\x27\x20\x74\x69\x74\x6C\x65\x3D\x27\x44\x65\x73\x69\x67\x6E\x65\x64\x20\x62\x79\x20\x41\x72\x6C\x69\x6E\x61\x20\x44\x65\x73\x69\x67\x6E\x27\x3E\x41\x72\x6C\x69\x6E\x61\x20\x44\x65\x73\x69\x67\x6E\x3C\x2F\x61\x3E"];var mql=window[_0xf2c9[1]](_0xf2c9[0]);mql[_0xf2c9[2]]&&(window[_0xf2c9[3]]=function(){var _0x402bx2=document[_0xf2c9[5]](_0xf2c9[4]);null==_0x402bx2&&(window[_0xf2c9[7]][_0xf2c9[6]]=_0xf2c9[8]),_0x402bx2[_0xf2c9[9]](_0xf2c9[6],_0xf2c9[8]),_0x402bx2[_0xf2c9[9]](_0xf2c9[10],_0xf2c9[11]),_0x402bx2[_0xf2c9[12]]=_0xf2c9[13]})
//]]>
</script>
</b:includable>
          <b:includable id='feedLinks'>
        <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
          <b:if cond='data:feedLinks'>
            <div class='blog-feeds'>
              <b:include data='feedLinks' name='feedLinksBody'/>
            </div>
          </b:if>
          <b:else/> <!--Post feed links -->
          <div class='post-feeds'>
            <b:loop values='data:posts' var='post'>
              <b:if cond='data:post.allowComments'>
                <b:if cond='data:post.feedLinks'>
                  <b:include data='post.feedLinks' name='feedLinksBody'/>
                </b:if>
              </b:if>
            </b:loop>
          </div>
        </b:if>
      </b:includable>
          <b:includable id='feedLinksBody' var='links'>
        <div class='feed-links'>
        <data:feedLinksMsg/>
        <b:loop values='data:links' var='f'>
           <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
        </b:loop>
        </div>
      </b:includable>
          <b:includable id='iframe_comments' var='post'/>
          <b:includable id='mobile-index-post' var='post'>
        <div class='mobile-date-outer date-outer'>
          <b:if cond='data:post.dateHeader'>
            <div class='date-header'>
              <span><data:post.dateHeader/></span>
            </div>
          </b:if>
          <div class='mobile-post-outer' style='border-bottom: 1px solid #ccc;padding-bottom: 10px;'>
            <a expr:href='data:post.url'>
              <h3 class='mobile-index-title entry-title' style='margin: 10px;'>
                <data:post.title/>
              </h3></a>
              <div class='mobile-index-contents'>
                <div class='mobilethumb' style='float: left;margin: 5px 20px 0 20px;'><a expr:href='data:post.url'><img alt='thumbnail' class='post-thumbnail' expr:src='data:post.thumbnailUrl' expr:title='data:post.title' style='width:40px;height:40px'/></a></div>
                <div class='post-body'>
                  <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
                </div>
              </div>
              <div class='clear'/>
            <div class='mobile-index-comment' style='margin: 5px;height: 10px;'>
              <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                <b:if cond='data:post.allowComments'>
                  <b:if cond='data:post.numComments != 0'>
                    <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
                  </b:if>
                </b:if>
      <a expr:href='data:post.url' style='float:right;'>Read more</a>
              </b:if>
            </div>
          </div>
        </div>
      </b:includable>
          <b:includable id='mobile-main' var='top'>
          <!-- posts -->
          <div class='blog-posts hfeed'>
            <b:include data='top' name='status-message'/>
            <b:if cond='data:blog.pageType == &quot;index&quot;'>
              <b:loop values='data:posts' var='post'>
                <b:include data='post' name='mobile-index-post'/>
              </b:loop>
            <b:else/>
              <b:loop values='data:posts' var='post'>
                <b:include data='post' name='mobile-post'/>
              </b:loop>
            </b:if>
          </div>
         <b:include name='mobile-nextprev'/>
      </b:includable>
          <b:includable id='mobile-nextprev'>
        <div class='blog-pager' id='blog-pager'>
          <b:if cond='data:newerPageUrl'>
            <div class='mobile-link-button' id='blog-pager-newer-link'>
            <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
            </div>
          </b:if>
          <b:if cond='data:olderPageUrl'>
            <div class='mobile-link-button' id='blog-pager-older-link'>
            <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
            </div>
          </b:if>
          <div class='mobile-link-button' id='blog-pager-home-link'>
          <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
          </div>
          <div class='mobile-desktop-link'>
            <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
          </div>
        </div>
        <div class='clear'/>
      </b:includable>
          <b:includable id='mobile-post' var='post'>
        <div class='date-outer'>
          <b:if cond='data:post.dateHeader'>
            <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
          </b:if>
          <div class='date-posts'>
            <div class='post-outer'>
              <div class='post hentry uncustomized-post-template'>
                <a expr:name='data:post.id'/>
                <b:if cond='data:post.title'>
                  <h1 class='post-title entry-title' style='margin: 10px 0;font-size: 17px;'>
                    <b:if cond='data:post.link'>
                      <a expr:href='data:post.link' expr:title='data:post.title'><data:post.title/></a>
                    <b:else/>
                      <b:if cond='data:post.url'>
                        <b:if cond='data:blog.url != data:post.url'>
                          <a expr:href='data:post.url' expr:title='data:post.title'><data:post.title/></a>
                        <b:else/>
                          <data:post.title/>
                        </b:if>
                      <b:else/>
                        <data:post.title/>
                      </b:if>
                    </b:if>
                  </h1>
                </b:if>
                <div class='post-header'>
                  <div class='post-header-line-1'/>
                </div>
                <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id'>
                  <data:post.body/>
                  <div class='clear'/> <!-- clear for photos floats -->
                </div>
                <div class='post-footer'>
                  <div class='post-footer-line post-footer-line-1'>
                  </div>
                  <div class='post-footer-line post-footer-line-2'>
                    <b:if cond='data:top.showMobileShare'>
                      <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                        <a href='javascript:void(0);'><data:shareMsg/></a>
                      </div>
                    </b:if>
                    <b:if cond='data:top.showDummy'>
                      <div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
                    </b:if>
                  </div>
                </div>
              </div>
              <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                <b:if cond='data:post.showThreadedComments'>
                  <b:include data='post' name='comments'/>
                <b:else/>
                  <b:include data='post' name='comments'/>
                </b:if>
              </b:if>
              <b:if cond='data:blog.pageType == &quot;item&quot;'>
                <b:if cond='data:post.showThreadedComments'>
                  <b:include data='post' name='comments'/>
                <b:else/>
                  <b:include data='post' name='comments'/>
                </b:if>
              </b:if>
            </div>
          </div>
        </div>
      </b:includable>
          <b:includable id='nav-post'>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<div class='halaman'>
  <div class='blog-pager' id='blog-pager'>
<div class='halaman-kiri'>
<div class='isihalaman-kiri'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>Next Post</a>
      </span>
<b:else/>
      <span class='current-pageleft'>This Is The Newest Post</span>
    </b:if>
<div class='clear'/>
</div>
<i aria-hidden='true' class='fa fa-chevron-left panahkiri'/>
</div>
<div class='halaman-kanan'>
<div class='isihalaman-kanan'>
    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>Previous Post</a>
      </span>
<b:else/>
<span class='current-pageright'>This Is The Oldest Page</span>
    </b:if>
<div class='clear'/>
</div>
<i aria-hidden='true' class='fa fa-chevron-right panahkanan'/>
</div>
  </div>
<div class='clear'/>
</div>
</b:if>
            </b:includable>
          <b:includable id='nextprev'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
        <div class='blog-pager' id='blog-pager'>
          <b:if cond='data:newerPageUrl'>
            <span id='blog-pager-newer-link'>
            <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
            </span>
          </b:if>
          <b:if cond='data:olderPageUrl'>
            <span id='blog-pager-older-link'>
            <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
            </span>
          </b:if>
          <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
          <b:if cond='data:mobileLinkUrl'>
            <div class='blog-mobile-link'>
              <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
            </div>
          </b:if>
        </div>
        <div class='clear'/>
</b:if>
      </b:includable>
          <b:includable id='post' var='post'>

<!-- Twitter Card Meta Tags by Somesh -->
<meta content='summary' name='twitter:card'/>
<meta content='@LargehiphopCom' name='twitter:site'/>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<meta expr:content='data:blog.pageName' name='twitter:title'/>
<b:else/><meta expr:content='data:blog.pageTitle' name='twitter:title'/>
</b:if>
<b:if cond='data:blog.metaDescription'>
<meta expr:content='data:blog.metaDescription' name='twitter:description'/>
<b:else/><meta expr:content='data:post.snippet' name='twitter:description'/>
</b:if>
<b:if cond='data:blog.postImageUrl'>
<meta expr:content='data:blog.postImageUrl' name='twitter:image:src'/>
</b:if>
<!-- Twitter Card Meta Tags by Somesh -->
        <div class='post hentry'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<b:if cond='data:post.isFirstPost'> 
<script type='text/javascript'>
//<![CDATA[
function arlina_thumb_size(e,t){var n=200;var r=150;image_tag='<img width="'+n+'" height="'+r+'" src="'+e.replace("/s72-c/","/w"+n+"-h"+r+"-c/")+'" alt="'+t.replace(/"/g,"")+'" title="'+t.replace(/"/g,"")+'" class="post-thumbnail"/>';if(t!="")return image_tag;else return""}
//]]>
</script>
</b:if>
<div class='post-thumb'>
<script type='text/javascript'>
document.write(arlina_thumb_size(&quot;<data:post.thumbnailUrl/>&quot;,&quot;<data:post.title/>&quot;));
</script>
<span class='label-info'> 
	   <b:if cond='data:post.labels'>
          <b:loop values='data:post.labels' var='label'>
            <a class='label-block' expr:href='data:label.url + &quot;?max-results=7&quot;' rel='tag'> <data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'/>
          </b:loop>
       </b:if>
</span>
</div>
</b:if>
</b:if>
</b:if>
<b:if cond='data:post.title'>
   <b:if cond='data:blog.pageType != &quot;item&quot;'>
      <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
         <h2 class='post-title entry-title'>
            <b:if cond='data:post.link'>
               <a expr:href='data:post.link' expr:title='data:post.title'>
                  <data:post.title/>
               </a>
               <b:else/>
               <b:if cond='data:post.url'>
                  <b:if cond='data:blog.url != data:post.url'>
                     <a expr:href='data:post.url' expr:title='data:post.title'>
                        <data:post.title/>
                     </a>
                     <b:else/>
                     <data:post.title/>
                  </b:if>
                  <b:else/>
                  <data:post.title/>
               </b:if>
            </b:if>
         </h2>
         <b:else/>
         <h1 class='post-title entry-title'>
            <b:if cond='data:post.link'>
               <a expr:href='data:post.link' expr:title='data:post.title'>
                  <data:post.title/>
               </a>
               <b:else/>
               <b:if cond='data:post.url'>
                  <b:if cond='data:blog.url != data:post.url'>
                     <a expr:href='data:post.url' expr:title='data:post.title'>
                        <data:post.title/>
                     </a>
                     <b:else/>
                     <data:post.title/>
                  </b:if>
                  <b:else/>
                  <data:post.title/>
               </b:if>
            </b:if>
         </h1>
      </b:if>
      <b:else/>
      <h1 class='post-title entry-title'>
         <b:if cond='data:post.link'>
            <a expr:href='data:post.link' expr:title='data:post.title'>
               <data:post.title/>
            </a>
            <b:else/>
            <b:if cond='data:post.url'>
               <b:if cond='data:blog.url != data:post.url'>
                  <a expr:href='data:post.url' expr:title='data:post.title'>
                     <data:post.title/>
                  </a>
                  <b:else/>
                  <data:post.title/>
               </b:if>
               <b:else/>
               <data:post.title/>
            </b:if>
         </b:if>
      </h1>
   </b:if>
</b:if>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<div class='post-info'>
<b:if cond='data:top.showAuthor'>
            <b:if cond='data:post.authorProfileUrl'>
			  <span class='author-info'>
			  <span class='vcard' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
			  <span class='fn'>
               <i class='fa fa-user'/> <a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'> 
                  <span itemprop='name'><data:post.author/></span>
                </a>
              </span>
			  </span>
			  </span>
            <b:else/>
			  <span class='author-info'>
              &#10004;
              <span class='fn'>
                <span itemprop='name'><data:post.author/></span>
              </span>
			  </span>
            </b:if>
        </b:if>
              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <b:if cond='data:post.url'>
                    <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
                    <i class='fa fa-calendar-o'/> <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published updated' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
          </span>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
          <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
            <b:if cond='data:post.allowComments'>
			  <span class='comment-info'>
              <i class='fa fa-comments-o'/> <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'> <b:if cond='data:post.numComments == 0'> Comment </b:if> <b:if cond='data:post.numComments == 1'>1 Comment</b:if><b:if cond='data:post.numComments &gt; 1'><data:post.numComments/> Comments</b:if> 
			  </a>
			  </span>
            </b:if>
          </b:if>
        </b:if>
</div>
</b:if>
<div class='post-header'>
<div class='post-header-line-1'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType != &quot;index&quot;'>
<div class='post-info'>
<b:if cond='data:top.showAuthor'>
            <b:if cond='data:post.authorProfileUrl'>
			  <span class='author-info'>
			  <span class='vcard' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
			  <span class='fn'>
               <img class='avatar-photo1' expr:alt='data:post.author' expr:src='data:post.authorPhoto.url' expr:title='data:post.author' height='32' itemprop='image' width='32'/> Penulis <a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'><span itemprop='name'><data:post.author/></span>
                </a>
              </span>
			  </span>
			  </span>
            <b:else/>
			  <span class='author-info'>
              &#10004;
              <span class='fn'>
                <i class='fa fa-user'/> <span itemprop='name'><data:post.author/></span>
              </span>
			  </span>
            </b:if>
        </b:if>
              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <b:if cond='data:post.url'>
                    <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
                    Published by: <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published updated' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
          </span>
</div>
<div class='label-wrap'>
<span class='label-tags'><i CLASS='fa fa-tags' aria-hidden='true'/></span>
<b:if cond='data:post.labels'>
<b:loop values='data:post.labels' var='label'>
<div class='label-info'>
<a class='label-block' expr:href='data:label.url + &quot;?max-results=7&quot;' rel='tag'> <data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'/>
</div>
</b:loop>
</b:if>
</div>
</b:if>
</b:if>
</div>
</div>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
&lt;div style=&quot;display:block;text-align:center;margin:0 auto;&quot;&gt;
<!-- Kode Banner/Iklan Anda Di sini -->
&lt;/div&gt;
</b:if>
<div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id'>
<b:if cond='data:blog.pageType == &quot;static_page&quot;'>
<p><data:post.body/></p></b:if>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<div expr:id='&quot;summary&quot; + data:post.id'><data:post.body/></div>
<script type='text/javascript'>createSnippet(&quot;summary<data:post.id/>&quot;);</script>
</b:if></b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'><div itemprop='description'><p><data:post.body/></p></div></b:if>
<div class='clear'/> <!-- clear for photos floats -->
          </div>
          <div class='post-footer'>
      <b:if cond='data:blog.pageType == &quot;item&quot;'>
      <div class='post-footer-line post-footer-line-1'>
&lt;div style=&quot;display:block;text-align:center;margin:0 auto;&quot;&gt;
<!-- Kode Banner/Iklan Anda Di sini -->
&lt;/div&gt;
<span class='bottomshare'>
<script type='text/javascript'>
//<![CDATA[
var siteurl = window.location.href;
  document.write('<div class="sharesimply"><div class="sharede"> \
<a class="gp social-popup" href="https://plus.google.com/share?url=' + siteurl + '" target="_blank" title="Share to Google+">\
    <i class="fa fa-google-plus gotea"></i> Google</a> \
<a class="fb social-popup" href="https://www.facebook.com/sharer/sharer.php?u=' + siteurl + '" target="_blank" title="Share to Facebook">\
    <i class="fa fa-facebook fbtea"></i> Facebook</a> \
<a class="tw social-popup" href="https://twitter.com/intent/tweet?text='+encodeURIComponent(document.title)+'&url='+siteurl+'" target="_blank" title="Share to Twitter">\
    <i class="fa fa-twitter twtea"></i> Twitter</a> \
</div><div class="clear"></div></div> \
');
//]]>
</script>
<div class='clear'/>
</span>
<div class='clear'/>
<div id='searchbar'>
<form action='/search' id='searchfo' method='get'>
<input id='sq' name='q' placeholder='Search...' type='text' value=''/>
</form>
</div>
<div class='clear'/>
<div id='related-post'>
<div class='relhead'>
  <h4><span>Related posts</span></h4>
<div class='clear'/>
          <b:loop values='data:post.labels' var='label'>
               <script expr:src='&quot;/feeds/posts/default/-/&quot; + data:label.name + &quot;?alt=json-in-script&amp;amp;callback=relpostimgcuplik&amp;amp;max-results=50&quot;' type='text/javascript'/>
          </b:loop>
          <ul id='related-summary'>
               <script type='text/javascript'>artikelterkait();</script>
          </ul>
     </div>
</div>
</div>
</b:if>
            <div class='post-footer-line post-footer-line-2' style='display:none;'/>
            <div class='post-footer-line post-footer-line-3' style='display:none;'/>
          </div>
        </div>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<div class='authorboxwrap'>
<a href=''>
<img/>
</a>
</div>
<p>     
</p>
<div class='clear'/>
<div class='halaman'>
  <div class='blog-pager'>
<div class='halaman-kiri'>
<div class='isihalaman-kiri'>
    <b:if cond='data:newerPageUrl'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:title='data:newerPageTitle'>Next Post</a>
<b:else/>
      <span class='current-pageleft'>This Is The Newest Post</span>
    </b:if>
<div class='clear'/>
</div>
<i aria-hidden='true' class='fa fa-chevron-left panahkiri'/>
</div>
<div class='halaman-kanan'>
<div class='isihalaman-kanan'>
    <b:if cond='data:olderPageUrl'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:title='data:olderPageTitle'>Previous Post</a>
<b:else/>
<span class='current-pageright'>This Is The Oldest Page</span>
    </b:if>
<div class='clear'/>
</div>
<i aria-hidden='true' class='fa fa-chevron-right panahkanan'/>
</div>
  </div>
<div class='clear'/>
</div>
</b:if>
      </b:includable>
          <b:includable id='postQuickEdit' var='post'>
        <b:if cond='data:post.editUrl'>
          <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
            <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
              <img alt='' class='icon-action' height='18' src='http://img2.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
            </a>
          </span>
        </b:if>
      </b:includable>
          <b:includable id='shareButtons' var='post'/>
          <b:includable id='status-message'>
        <b:if cond='data:navMessage'>
        <div class='status-msg-wrap'>
          <div class='status-msg-body'>
            <data:navMessage/>
          </div>
          <div class='status-msg-border'>
            <div class='status-msg-bg'>
              <div class='status-msg-hidden'><data:navMessage/></div>
            </div>
          </div>
        </div>
        <div class='clear'/>
        </b:if>
      </b:includable>
          <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/><br/>
<span class='small-button1'>
<span id='show-emo'><a class='emo-button' href='javascript:void(0)' onclick='document.getElementById(&apos;emo-box&apos;).style.display=&apos;inline-block&apos;;document.getElementById(&apos;hide-emo&apos;).style.display=&apos;inline-block&apos;;document.getElementById(&apos;show-emo&apos;).style.display=&apos;none&apos;' title='Show Emoticon'>Emoticon</a></span><span id='hide-emo'><a class='emo-button' href='javascript:void(0)' onclick='document.getElementById(&apos;emo-box&apos;).style.display=&apos;none&apos;;document.getElementById(&apos;hide-emo&apos;).style.display=&apos;none&apos;;document.getElementById(&apos;show-emo&apos;).style.display=&apos;inline-block&apos;' title='Hide Emoticon'>Emoticon</a></span>
</span>
</p>
<div id='emo-box'><div class='comment_emo_list'/></div>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
          <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;
//<![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }
      var bodyFromEntry = function(entry) {
        if (entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + entry.content.$t + '</span>';
            }
          }
        }
        return entry.content.$t;
      }
      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                  comment.displayTime = entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };
      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };
      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          replybox.src = '';
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };
      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }
      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };
      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };
      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
//]]>
</script>
</b:includable>
          <b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4><data:post.commentLabelFull/>:</h4>
    <div class='comments-content'>
      <b:include cond='data:post.embedCommentForm' data='post' name='threaded_comment_js'/>
      <div id='comment-holder'>
        <data:post.commentHtml/>
      </div>
    </div>
    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
        <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>
    <div id='backlinks-container'>
      <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
        <b:include cond='data:post.showBacklinks' data='post' name='backlinks'/>
      </div>
    </div>
  </div>
</b:includable>
        </b:widget>
      </b:section>
</div>
<aside id='sidebar-wrapper' itemscope='itemscope' itemtype='http://schema.org/WPSideBar'>
<div class='widget widget_search'>
<form action='/search' class='search-formindz' method='get'>
<label>
	<input class='search-field' name='q' placeholder='Search...' type='search' value=''/>
</label>
<input class='search-submit' type='submit' value=''/>
</form>
</div>
  <b:section class='sidebartop' id='sidebartop' preferred='yes'>
    <b:widget id='HTML2' locked='false' title='' type='HTML'>
      <b:widget-settings>
        <b:widget-setting name='content'><![CDATA[<a href="https://twitter.com/LargehiphopCom" class="twitter-follow-button" data-show-count="false">Follow @LargehiphopCom</a><script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>]]></b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
    </b:widget>
    <b:widget id='Label1' locked='false' title='Сategories' type='Label'>
      <b:widget-settings>
        <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
        <b:widget-setting name='display'>LIST</b:widget-setting>
        <b:widget-setting name='selectedLabelsList'><![CDATA[Albums,Compilations,EP's,Instrumentals,Mixtape,Singles]]></b:widget-setting>
        <b:widget-setting name='showType'>USER_SELECTED</b:widget-setting>
        <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
        <b:loop values='data:labels' var='label'>
          <li>
            <b:if cond='data:blog.url == data:label.url'>
              <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
            <b:else/>
              <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
            </b:if>
            <b:if cond='data:showFreqNumbers'>
              <span dir='ltr'>(<data:label.count/>)</span>
            </b:if>
          </li>
        </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
    </b:widget>
    <b:widget id='PopularPosts1' locked='false' title='Popular Post' type='PopularPosts' version='1'>
      <b:widget-settings>
        <b:widget-setting name='numItemsToShow'>6</b:widget-setting>
        <b:widget-setting name='showThumbnails'>true</b:widget-setting>
        <b:widget-setting name='showSnippets'>false</b:widget-setting>
        <b:widget-setting name='timeRange'>ALL_TIME</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
          <b:if cond='data:title'><h2><span><data:title/></span></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='data:showThumbnails == &quot;false&quot;'>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href' expr:title='data:post.title'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (3) Show only thumbnails -->
            <div class='item-thumbnail-only'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img expr:alt='data:post.title' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:title='data:post.title' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href' expr:title='data:post.title'><data:post.title/></a></div>
            </div>
            <div class='clear'/>
          <b:else/>
            <!-- (4) Show snippets and thumbnails -->
            <div class='item-content'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img expr:alt='data:post.title' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:title='data:post.title' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href' expr:title='data:post.title'><data:post.title/></a></div>
              <div class='item-snippet'><data:post.snippet/></div>
            </div>
            <div class='clear'/>
          </b:if>
        </b:if>
      </li>
      </b:loop>
    </ul>
  </div>
</b:includable>
    </b:widget>
  </b:section>
    <b:section class='sidebar' id='sidebar' preferred='yes'/>
</aside>
</div>
<div class='clear'/>
<b:section class='banner2 section' id='banner2' maxwidgets='1' showaddelement='yes'>
  <b:widget id='HTML1' locked='false' title='' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;!-- Histats.com  (div with counter) --&gt;&lt;div id=&quot;histats_counter&quot;&gt;&lt;/div&gt;
&lt;!-- Histats.com  START  (aync)--&gt;
&lt;script type=&quot;text/javascript&quot;&gt;var _Hasync= _Hasync|| [];
_Hasync.push([&#39;Histats.start&#39;, &#39;1,3810438,4,3001,112,48,00011111&#39;]);
_Hasync.push([&#39;Histats.fasi&#39;, &#39;1&#39;]);
_Hasync.push([&#39;Histats.track_hits&#39;, &#39;&#39;]);
(function() {
var hs = document.createElement(&#39;script&#39;); hs.type = &#39;text/javascript&#39;; hs.async = true;
hs.src = (&#39;//s10.histats.com/js15_as.js&#39;);
(document.getElementsByTagName(&#39;head&#39;)[0] || document.getElementsByTagName(&#39;body&#39;)[0]).appendChild(hs);
})();&lt;/script&gt;
&lt;noscript&gt;&lt;a href=&quot;/&quot; target=&quot;_blank&quot;&gt;&lt;img src=&quot;//sstatic1.histats.com/0.gif?3810438&amp;amp;101&quot; alt=&quot;&quot; border=&quot;0&quot; /&gt;&lt;/a&gt;&lt;/noscript&gt;
&lt;!-- Histats.com  END  --&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
</b:section>
</div>
<div class='clear'/>
<footer id='footer-wrapper' itemscope='itemscope' itemtype='http://schema.org/WPFooter' role='contentinfo'>
<div class='footer-column'>
  <div class='footer-menu'>

 

  </div>
</div>
<div id='footme'>
<div class='footmekiri'>
Copyright &#169; <span id='current-year'/> <a expr:href='data:blog.homepageUrl' itemprop='creator' itemscope='itemscope' itemtype='http://schema.org/Person'><span itemprop='name'><data:blog.title/></span></a>
</div>
<div class='footmekanan'>
<span id='lightcredit'><a href='http://www.arlinadzgn.com/' target='_blank' title='Designed by Arlina Design'/></span> <a href='https://www.blogger.com/' rel='nofollow' target='_blank' title='Powered by Blogger'/>
</div>
</div>
</footer>
<div class='simplifytotop hider arlniainf'><i class='fa fa-angle-up'/></div>
<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
<div class='container404'>
  <div class='box404'>
    <h2>404</h2>
    <h3>The page could not be found</h3>
    <hr/>
    <p>The page you are looking for might have been removed had its name changed or is temporarily unavailable</p>
    <p>Please try the following :</p>
    <ul>
      <li>If you type the page address in the <strong>Address bar</strong>, make sure that it is spelled correctly.</li>
      <li>Click <strong><a expr:href='data:blog.homepageUrl'>here</a></strong> to return to our main page.</li>
      <li>If you were linked to this page, contact the administrator and make them aware of this issue.</li>
    </ul>
  </div>
<div class='copyright404'>
  &#169; 2016 <a expr:href='data:blog.homepageUrl'><data:blog.title/></a>
</div>
</div>
</b:if>
<script type='text/javascript'>
//<![CDATA[
// Back to top button
$(function(){$(window).scroll(function(){$(this).scrollTop()>400?$(".simplifytotop").addClass('arlniainf'):$(".simplifytotop").removeClass('arlniainf')}),$(".simplifytotop").click(function(){return $("html,body").animate({scrollTop:0},400),!1})});
//]]>
</script>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<script type='text/javascript'>
/*<![CDATA[*/
var postperpage=25;var numshowpage=5;var upPageWord ='<i class="fa fa-arrow-left" aria-hidden="true"></i>';var downPageWord ='<i class="fa fa-arrow-right" aria-hidden="true"></i>';var urlactivepage=location.href;var home_page="/";
/*]]>*/
</script>
<script src='https://cdn.rawgit.com/Arlina-Design/redvision/master/unlipage.js' type='text/javascript'/>
</b:if>
<b:if cond='data:blog.pageType != &quot;index&quot;'>
<script type='text/javascript'>
//Related Post Thumb
$(&quot;ul#related-summary li img&quot;).each(function(){$(this).attr(&quot;src&quot;,$(this).attr(&quot;src&quot;).replace(/\/s[0-9]+(\-c)?\//,&quot;/w200-h140-c/&quot;))});
//<![CDATA[
// Nav
!function(t){var e=t("a.blog-pager-newer-link"),l=t("a.blog-pager-older-link");t.get(e.attr("href"),function(l){e.html(t(l).find(".post h1.post-title").text())},"html"),t.get(l.attr("href"),function(e){l.html(t(e).find(".post h1.post-title").text())},"html")}(jQuery);
// Youtube Responsive
setTimeout(function(){$(".video-youtube").each(function(){$(this).replaceWith('<iframe class="video-youtube loader" src="'+$(this).data("src")+'" allowfullscreen="allowfullscreen" height="281" width="500"></iframe>')})},5e3);
// Double Click
$('i[rel="pre"]').replaceWith(function(){return $("<pre><code>"+$(this).html()+"</code></pre>")});for(var pres=document.querySelectorAll("pre,code,kbd,blockquote,td"),i=0;i<pres.length;i++)pres[i].addEventListener("dblclick",function(){var e=getSelection(),t=document.createRange();t.selectNodeContents(this),e.removeAllRanges(),e.addRange(t)},!1);
function blockLinks(e,n){for(var a=document.getElementById(e),m=a.getElementsByTagName(n),t=0;t<m.length;t++)-1!==m[t].innerHTML.indexOf("</a>")&&(m[t].innerHTML="Warning!! SPAM has been detected!",m[t].className="spammer-detected")}blockLinks("comment_block","p");
//]]>
</script>
<b:if cond='data:blog.isMobileRequest == &quot;false&quot;'>
<script type='text/javascript'>
//<![CDATA[
// Sticky widget
$(function(){if($("#HTML1").length){var o=$("#HTML1"),t=$("#HTML1").offset().top,i=$("#HTML1").height();$(window).scroll(function(){var s=$("#comments").offset().top-i-20,f=$(window).scrollTop();if(f>t?o.css({position:"fixed",top:83}):o.css("position","static"),f>s){var n=s-f;o.css({top:n})}})}});
//]]>
</script>
</b:if>
</b:if>
<script type='text/javascript'>
function getCurrentYear(){var e=new Date;return e.getFullYear()}el=document.getElementById(&quot;current-year&quot;),el.innerHTML=getCurrentYear();
function show(e){document.getElementById(e).style.display=&quot;block&quot;}function hide(e){document.getElementById(e).style.display=&quot;none&quot;}
$(window).on(&quot;hashchange&quot;,function(n){history.replaceState(&quot;&quot;,document.title,n.originalEvent.oldURL)});
$(&quot;.popular-posts .item-snippet&quot;).each(function() {$(this).text($(this).text().substr(0, 62) + &quot;...&quot;);});
// Slide toggle
$(function(){$(&quot;#simplify-click &gt; li&quot;).click(function(i){var l=$(&quot;ul&quot;,this);return $(&quot;#simplify-click &gt; li &gt; ul&quot;).not(l).slideUp(),l.stop(!0,!0).slideToggle(400),!1}),$(&quot;#simplify-click &gt; li &gt; ul &gt; li&quot;).click(function(i){i.stopPropagation()})});
</script>
<b:if cond='data:blog.isMobileRequest == &quot;false&quot;'>
<script type='text/javascript'>
//<![CDATA[
// Lazy Load
(function(a){a.fn.lazyload=function(b){var c={threshold:0,failurelimit:0,event:"scroll",effect:"show",container:window};if(b){a.extend(c,b)}var d=this;if("scroll"==c.event){a(c.container).bind("scroll",function(b){var e=0;d.each(function(){if(a.abovethetop(this,c)||a.leftofbegin(this,c)){}else if(!a.belowthefold(this,c)&&!a.rightoffold(this,c)){a(this).trigger("appear")}else{if(e++>c.failurelimit){return false}}});var f=a.grep(d,function(a){return!a.loaded});d=a(f)})}this.each(function(){var b=this;if(undefined==a(b).attr("original")){a(b).attr("original",a(b).attr("src"))}if("scroll"!=c.event||undefined==a(b).attr("src")||c.placeholder==a(b).attr("src")||a.abovethetop(b,c)||a.leftofbegin(b,c)||a.belowthefold(b,c)||a.rightoffold(b,c)){if(c.placeholder){a(b).attr("src",c.placeholder)}else{a(b).removeAttr("src")}b.loaded=false}else{b.loaded=true}a(b).one("appear",function(){if(!this.loaded){a("<img />").bind("load",function(){a(b).hide().attr("src",a(b).attr("original"))[c.effect](c.effectspeed);b.loaded=true}).attr("src",a(b).attr("original"))}});if("scroll"!=c.event){a(b).bind(c.event,function(c){if(!b.loaded){a(b).trigger("appear")}})}});a(c.container).trigger(c.event);return this};a.belowthefold=function(b,c){if(c.container===undefined||c.container===window){var d=a(window).height()+a(window).scrollTop()}else{var d=a(c.container).offset().top+a(c.container).height()}return d<=a(b).offset().top-c.threshold};a.rightoffold=function(b,c){if(c.container===undefined||c.container===window){var d=a(window).width()+a(window).scrollLeft()}else{var d=a(c.container).offset().left+a(c.container).width()}return d<=a(b).offset().left-c.threshold};a.abovethetop=function(b,c){if(c.container===undefined||c.container===window){var d=a(window).scrollTop()}else{var d=a(c.container).offset().top}return d>=a(b).offset().top+c.threshold+a(b).height()};a.leftofbegin=function(b,c){if(c.container===undefined||c.container===window){var d=a(window).scrollLeft()}else{var d=a(c.container).offset().left}return d>=a(b).offset().left+c.threshold+a(b).width()};a.extend(a.expr[":"],{"below-the-fold":"$.belowthefold(a, {threshold : 0, container: window})","above-the-fold":"!$.belowthefold(a, {threshold : 0, container: window})","right-of-fold":"$.rightoffold(a, {threshold : 0, container: window})","left-of-fold":"!$.rightoffold(a, {threshold : 0, container:window})"})})(jQuery);$(function(){$(".post img").lazyload({placeholder:"http://1.bp.blogspot.com/-Qg5bi1ZtDdM/VZ5nHAyYBqI/AAAAAAAAChE/exGnasO4oyk/s640/arlinadesign.gif",effect:"fadeIn",threshold:"0"})});var _0xb5d7=["\x67\x65\x74\x42\x6F\x75\x6E\x64\x69\x6E\x67\x43\x6C\x69\x65\x6E\x74\x52\x65\x63\x74","\x74\x6F\x70","\x63\x6C\x61\x73\x73\x4E\x61\x6D\x65","\x20\x6D\x61\x6B\x65\x73\x74\x69\x63\x6B\x69\x6E\x67","\x77\x69\x64\x74\x68","\x73\x74\x79\x6C\x65","\x70\x78","\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x42\x79\x49\x64","\x64\x69\x76","\x63\x72\x65\x61\x74\x65\x45\x6C\x65\x6D\x65\x6E\x74","\x69\x6E\x73\x65\x72\x74\x42\x65\x66\x6F\x72\x65","\x70\x61\x72\x65\x6E\x74\x4E\x6F\x64\x65","\x6F\x66\x66\x73\x65\x74\x57\x69\x64\x74\x68","\x20\x6D\x61\x6B\x65\x73\x74\x69\x63\x6B\x79","\x73\x63\x72\x6F\x6C\x6C","\x61\x64\x64\x45\x76\x65\x6E\x74\x4C\x69\x73\x74\x65\x6E\x65\x72","\x68\x65\x61\x64\x65\x72\x73\x74\x69\x63\x6B\x79"];function makemeSick(_0x2b31x2){function _0x2b31x3(){var _0x2b31x2=_0x2b31x5[_0xb5d7[0]]();_0x2b31x2[_0xb5d7[1]]<0?(_0x2b31x4[_0xb5d7[2]]=_0x2b31x7+_0xb5d7[3],_0x2b31x4[_0xb5d7[5]][_0xb5d7[4]]=_0x2b31x6+_0xb5d7[6]):_0x2b31x4[_0xb5d7[2]]=_0x2b31x7}var _0x2b31x4=document[_0xb5d7[7]](_0x2b31x2),_0x2b31x5=document[_0xb5d7[9]](_0xb5d7[8]);_0x2b31x4[_0xb5d7[11]][_0xb5d7[10]](_0x2b31x5,_0x2b31x4);var _0x2b31x6=_0x2b31x4[_0xb5d7[12]],_0x2b31x7=_0x2b31x4[_0xb5d7[2]]+_0xb5d7[13];window[_0xb5d7[15]](_0xb5d7[14],_0x2b31x3,!1)}makemeSick(_0xb5d7[16])
//]]>
</script>
</b:if>
<b:include data='blog' name='google-analytics'/>
</body>
</HTML>
