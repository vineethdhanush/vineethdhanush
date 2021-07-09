
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
<meta content='width=device-width, initial-scale=1.0' name='viewport'/>
<script type='text/javascript'>//<![CDATA[
var curl = window.location.href;if (curl.indexOf('m=1') != -1) {curl = curl.replace('m=1', 'm=0');window.location.href = curl;}
//]]></script>

<b:if cond='data:blog.url == data:blog.homepageUrl'>
</b:if>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<title><data:blog.pageTitle/></title> 
<b:else/>
<title><data:blog.pageName/> ~ <data:blog.title/></title>
</b:if>

<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
<title>Page not found</title>
</b:if>
<meta content='en_US' property='og:locale'/>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<meta expr:content='data:blog.pageName' property='og:title'/>
</b:if>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<meta expr:content='data:blog.pageTitle' property='og:title'/>
</b:if>
<b:if cond='data:blog.metaDescription != &quot;&quot;'>
<meta expr:content='data:blog.metaDescription' name='og:description'/>
</b:if>
<meta expr:content='data:blog.canonicalUrl' property='og:url'/>
<meta content='Your-Website-Name' property='og:site_name'/>
<meta content='article' property='og:type'/>
<b:if cond='data:blog.postImageThumbnailUrl'>
<meta expr:content='data:blog.postImageThumbnailUrl' property='og:image'/>
</b:if>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<meta content='Your-logo-image-here' property='og:image'/></b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<b:if cond='data:blog.postImageThumbnailUrl'>
<b:if cond='data:blog.metaDescription'>
<meta content='summary' name='twitter:card'/>
<meta content='@templateism' name='twitter:site'/>
<meta content='@templateism' name='twitter:creator'/>
<meta expr:content='data:blog.pageName' name='twitter:title'/>
<meta expr:content='data:blog.metaDescription' name='twitter:description'/>
<meta expr:content='data:blog.postImageThumbnailUrl' name='twitter:image:src'/>
<meta expr:content='data:blog.homepageUrl' name='twitter:domain'/>
      </b:if>
    </b:if>
</b:if>
<b:include data='blog' name='all-head-content'/>
<b:if cond='data:blog.url == data:blog.homepageUrl'>
<meta content='Keywords-here' name='keywords'/>
</b:if>

<link href='http://fonts.googleapis.com/css?family=Open+Sans:400,600,300,100|Open+Sans+Condensed:300' rel='stylesheet' type='text/css'/>
<link href='http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css' rel='stylesheet' type='text/css'/>


<b:include data='blog' name='all-head-content'/>

    <b:skin><![CDATA[/*
-----------------------------------------------
Blogger Template Style
Name:   Movieism
Author: Syed Faizan Ali
URL 1:  http://www.templateism.com/
URL 2:  http://www.mybloggerlab.com
Date:   14 August 2014
License:  This free Blogger template is licensed under the Creative Commons Attribution 3.0 License, which permits both personal and commercial use.
However, to satisfy the 'attribution' clause of the license, you are required to keep the footer links intact which provides due credit to its authors. For more specific details about the license, you may visit the URL below:
http://creativecommons.org/licenses/by/3.0/
----------------------------------------------- */


body#layout #rsidebar-wrapper {
display: block !important;
width: 280px;
float: left;
}


body#layout .logo {
width: 95%;
}

body#layout #main-wrapper {
    width: 500px;
    float: left;
	min-height: 400px;
}

body#layout #sideb {
float: left;
width: 250px;
margin-top: 10px;
}



body#layout ul {
    list-style-type: none;
    list-style: none;
}

body#layout ul li {
    list-style-type: none;
    list-style: none;
}

body {
    background: #ffffff linear-gradient(to bottom, #3f567c, #b5ccc6) no-repeat;
    color: #555555;
    font-family: Open Sans, sans-serif;
    font-size: 14px;
    margin: 0px;
    padding: 0px;
}

a:link,a:visited {
    color: #3AB0FF;
    text-decoration: underline;
    outline: none;
}

a:hover {
    color: #3AB0FF;
    text-decoration: none;
    outline: none;
}

a img {
    border-width: 0;
}

#body-wrapper {
    max-width: 1200px;
    padding: 10px;
    margin: auto;
}




/* Header-----------------------------------------------*/

.logo {
    float: left;
    background: #3AB0FF;
    padding-top: 12px;
    padding-left: 30px;
    padding-right: 30px;
    font-family: Open Sans Condensed, sans-serif;
}

#top-menu {
    background: #279CEB;
    width: 100%;
    float: left;
}

#header h1 {
    font-family: Open Sans Condensed, sans-serif;
    font-size: 40px;
    text-transform: uppercase;
    color: #fff;
    margin: 0px;
    padding: 0px;
}

#header .description {
    padding-left: 7px;
    color: #374142;
    line-height: 14px;
    font-size: 14px;
    padding-top: 0px;
    margin-top: 10px;
    font-family: Arial,Helvetica,Sans-serif;
}

#header h1 a,#header h1 a:visited {
    color: #fff;
    text-decoration: none;
}

#header h2 {
    padding-left: 5px;
    color: #374142;
    font: 14px Arial,Helvetica,Sans-serif;
}

#header2 {
    float: right;
    width: 51%;
    margin-right: 0px;
    padding-right: 0px;
    overflow: hidden;
}

#header2 .widget {
    padding: 0px 0px 0px 0px;
    float: right;
}

.social-profiles-widget img {
    margin: 0 4px 0 0;
}

.social-profiles-widget img:hover {
    opacity: 0.8;
}

#top-social-profiles {
    padding-top: 10px;
    height: 32px;
    text-align: right;
    float: right;
}

#top-social-profiles img {
    margin: 0 6px 0 0 !important;
}

#top-social-profiles img:hover {
    opacity: 0.8;
}

#top-social-profiles .widget-container {
    background: none;
    padding: 0;
    border: 0;
}
/* Outer-Wrapper----------------------------------------------- */

#outer-wrapper {
    margin: auto;
    border-radius: 5px;
    background: #fff;
    overflow: hidden;
    position: relative;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
}

#main-wrapper {
    float: left;
    margin: 0px;
    word-wrap: break-word;
    overflow: hidden;
    background: #fff;
    min-height: 700px;
    width: 100%;
}

#rsidebar-wrapper {
    width: 300px;
    margin-right: 16px;
    float: left;
    float: none;
    overflow: hidden;
    background: #24282C;
    padding-top: 15px;
    display: none;
}

.search-box {
    width: 300px;
    float: left;
    display: none;
    margin-top: 20px;
}

.searchbox {
    padding-left: 20px;
    padding-right: 15px;
    padding-top: 20px;
    padding-bottom: 20px;
    background: #373D41;
}

/* Headings----------------------------------------------- */
h2 {
}
/* Posts-----------------------------------------------*/
h2.date-header {
    margin: 1.5em 0 .5em;
    display: none;
}

.wrapfullpost {
}

.post {
    margin-bottom: 15px;
}

.post-body {
    margin: 0px;
    padding: 0px 10px 0px 0px;
    font-size: 14px;
    line-height: 20px;
    font-weight: 400;
}

/* Sidebar Content----------------------------------------------- */
.sidebar {
    margin: 0 0 10px 0;
    font-size: 13px;
    color: #374142;
}

.sidebar a {
    text-decoration: none;
    color: #fff;
}

.sidebar a:hover {
    text-decoration: none;
    color: #3AB0FF;
}

.sidebar h2 {
    text-transform: uppercase;
    padding: 0px;
    font-size: 14px;
    margin-bottom: 10px;
    color: #fff;
}

.facebook_custom {
    background: #373D41;
}

.Label ul {
    margin: 0px;
    padding: 0px;
}

.Label li a {
    float: left;
    background: #373D41;
    padding: 10px;
    margin-right: 10px;
}

.Label li {
    float: left;
}

.sidebar ul li {
    padding: 0 0 9px 0;
    margin: 0 0 8px 0;
}

.sidebar .widget {
    margin: 0 0 40px 0;
    padding: 0;
    color: #374142;
    font-size: 13px;
}

.main .widget {
    margin: 0 0 5px;
    padding: 0 0 2px;
}

.main .Blog {
    border-bottom-width: 0;
}

/* Comments----------------------------------------------- */
#comments {
    width: 100%;
    float: left;
}

#comments-block3 {
    padding: 0;
    margin: 0;
    float: left;
    overflow: hidden;
    position: relative;
}

#comment-name-url {
    width: 465px;
    float: left;
}

#comment-date {
    width: 465px;
    float: left;
    margin-top: 5px;
    font-size: 10px;
}

.avatar-image-container {
    background: none!important;
    border: none!important;
    ;
}

.datetime.secondary-text {
    float: right;
}

.comments .comments-content .comment-content {
    line-height: 20px;
    font-size: 14px;
}

.comments .comment .comment-actions a {
    padding-right: 5px;
    padding-top: 5px;
    text-decoration: none;
}

.comments .comments-content .comment {
    margin-bottom: 40px;
    padding-bottom: 8px;
}

.user.blog-author a {
    font-size: 20px;
    text-decoration: none;
}

.comment-actions a {
    color: #fff;
}

.comment-actions {
    padding: 10px;
    margin-top: 20px;
    float: right;
    background: #222222;
    margin-bottom: 10px;
}

.comment-block {
    border: 1px solid #ddd;
    padding: 20px;
}

.comment-header {
    border-bottom: 1px solid #ddd;
    padding-bottom: 20px;
}

#comments h4 {
    margin-left: 0px;
    margin-top: 20px;
    font-family: open sans;
    font-weight: 400;
    line-height: 30px;
    font-size: 30px;
    margin-bottom: 0px;
}

.deleted-comment {
    font-style: italic;
    color: gray;
}

#blog-pager-newer-link {
    float: $startSide;
}

#blog-pager-older-link {
    float: $endSide;
}

#blog-pager {
    text-align: center;
    overflow: visible;
}

.feed-links {
    display: none;
}
/* Profile ----------------------------------------------- */
.profile-img {
    float: $startSide;
    margin-top: 0;
    margin-$endSide: 5px;
    margin-bottom: 5px;
    margin-$startSide: 0;
    padding: 4px;
    border: 1px solid $bordercolor;
}

.profile-data {
    margin: 0;
    text-transform: uppercase;
    letter-spacing: .1em;
    font: $postfooterfont;
    color: $sidebarcolor;
    font-weight: bold;
    line-height: 1.6em;
}

.profile-datablock {
    margin: .5em 0 .5em;
}

.profile-textblock {
    margin: 0.5em 0;
    line-height: 1.6em;
}

.avatar-image-container {
    background: url(http://1.bp.blogspot.com/-cewCXF9l764/UC7eon7rxXI/AAAAAAAAAww/gDiPoSuhivM/s000/comment-avatar.jpg);
    width: 32px;
    height: 32px;
    float: right;
    margin: 5px 10px 5px 5px;
    border: 1px solid #ddd;
}

.avatar-image-container img {
    width: 32px;
    height: 32px;
}

.profile-link {
    font: $postfooterfont;
    text-transform: uppercase;
    letter-spacing: .1em;
}

#navbar-iframe {
    height: 0;
    visibility: hidden;
    display: none;
}

#nav-trigger {
    display: none;
    text-align: center;
}

#nav-trigger span {
    display: block;
    background-color: #279CEB;
    cursor: pointer;
    text-transform: uppercase;
    padding: 0 25px;
    color: #EEE;
    line-height: 67px;
}

nav#nav-mobile {
    margin: 0px;
}

nav {
    margin-bottom: 30px;
}

nav#nav-main {
    background-color: #279CEB;
    margin: 0px;
    float: left;
}

nav#nav-main ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    text-align: center;
}

nav#nav-main li {
    display: inline-block;
    float: left;
    ont-family: 'Open Sans', sans-serif;
}

nav#nav-main li:last-child {
    border-right: none;
}

nav#nav-main a {
    padding: 0 25px;
    color: #EEE;
    line-height: 67px;
    display: block;
}

nav#nav-main a:hover {
    background-color: #3AB0FF;
    text-decoration: none;
    color: #fff;
}

nav#nav-mobile {
    position: relatifve;
    display: none;
}

nav#nav-mobile ul {
    display: none;
    list-style-type: none;
    position: absolute;
    left: 0;
    right: 0;
    margin-left: auto;
    margin-right: auto;
    text-align: center;
    background-color: #ddf0f9;
    z-index: 10;
    padding: 0px;
}

border-bottom: solid 1px #cc0028;
}

nav#nav-mobile li:last-child {
border-bottom: none;
}

nav#nav-mobile a {
display: block;
color: #29a7e1;
padding: 10px 30px;
text-decoration: none;
border-bottom: 1px solid #00aeef;
}

nav#nav-mobile a:hover {
background-color: #e6002d;
color: #fff;
}

/* =Media Queries
-------------------------------------------------------------- */
@media all and (max-width: 900px) {
#nav-trigger {
    display: block;
}

nav#nav-main {
    display: none;
}

nav#nav-mobile {
    display: block;
}
}


/* Catrogory Label */
.status-msg-body {
    display: none;
}

.status-msg-wrap {
    display: none;
}

.status-msg-border {
    border: none;
}

.featured-movie {
    position: relative;
}

.featured-movie .cover {
    width: 100%;
    display: block;
}

.featured-movie .corner-title {
    position: absolute;
    top: 20px;
    left: 20px;
    text-transform: uppercase;
    color: #FFF;
    background: rgba(25, 25, 25, 0.3);
    padding: 10px;
    font-size: 13px;
}

.featured-movie .bottom-bar {
    bottom: 0;
    left: 0;
    right: 0;
    padding: 20px 30px;
    background: rgba(10, 10, 10, 0.8);
    color: #FFF;
    overflow: hidden;
    text-align: center;
}

.featured-movie .bottom-bar .title-container {
    float: left;
    font-weight: 100;
    font-size: 40px;
    width: 100%;
    margin-bottom: 10px;
}

.featured-movie .bottom-bar .title-container .fa {
    margin-right: 10px;
    color: #FF3A3A;
}

.featured-movie .bottom-bar .title-container b {
    font-weight: 600;
}

.featured-movie .bottom-bar .right {
    font-size: 14px;
    width: 160px;
    text-align: center;
    margin: auto;
}

.featured-movie .bottom-bar .right .stars {
    float: left;
    color: #F0C236;
    margin-right: 20px;
}

.featured-movie .bottom-bar .right .share {
    float: left;
    cursor: pointer;
}

.featured-movie .bottom-bar .right .share .fa {
    margin-right: 5px;
}

.search-box input {
    width: 220px;
    border: 0;
    padding: 10px 20px;
    border-radius: 50px;
    outline: none;
    color: #999;
    transition-duration: .3s;
    font-family: open sans;
}

.search-box input:focus {
    color: #333;
}

.search-box input:focus ~ .fa {
    color: #999;
}

.search-box .fa {
    position: absolute;
    top: 31px;
    right: 35px;
    color: #CCC;
    transition-duration: .3s;
    cursor: pointer;
}

div#copyrights-box {
    background: #EEE;
    float: left;
    width: 100%;
}

.copy-pad {
    margin: 20px;
    overflow: hidden;
}

div#copyrights-company {
    float: left;
}

div#copyrights-developer {
    float: right;
}

.post.hentry {
    float: left;
    width: 130px;
    display: block;
    cursor: pointer;
    margin-left: 16px;
    margin-right: 16px;
    margin-bottom: 20px;
}

.post h2 a {
    font-weight: bold;
    font-size: 13px;
    color: #111;
    text-decoration: none;
}

.post h2 {
    margin-top: 0;
    float: left;
    margin-bottom: 0px;
    line-height: 13px;
    width: 100%;
    text-overflow: ellipsis;
    overflow: hidden;
    white-space: nowrap;
    cursor: pointer;
}


.post-body h2 {
font-size: 35px;
line-height: 40px;
float: left;
width: 100%;
margin-bottom: 10px;
margin-top: 20px;
}


.post-body h3 {
font-size:30px;
line-height: 35px;
float: left;
width: 100%;
margin-bottom: 10px;
margin-top: 20px;
}

.post-body h4 {
font-size:25px;
line-height: 30px;
float: left;
width: 100%;
margin-bottom: 10px;
margin-top: 20px;
}

.lablo a {
    color: #999;
    font-size: 12px;
}

.lablo {
    float: left;
}

.overlay.animated img {
    border-radius: 8px;
}

.title-bar {
    padding-bottom: 20px;
    margin-bottom: 20px;
    border-bottom: 1px solid #DDD;
    overflow: hidden;
}

.title-bar .left {
    float: left;
    font-size: 15px;
    text-transform: uppercase;
}

.title-bar .left .grey {
    color: #999;
    margin: 0px;
}

.title-bar .left .bold {
    font-weight: bold;
    margin: 0px;
}

.title-bar .left p {
    display: inline-block;
    margin-right: 10px;
}

.title-bar .right {
    float: right;
}

.title-bar .right a {
    color: #999;
    margin-left: 10px;
}

.title-bar .right a.blue {
    color: #279CEB;
}

.load-more {
    background: #EEE;
    padding-top: 15px;
    padding-bottom: 15px;
    border-radius: 5px;
    text-align: center;
    color: #666;
    margin-bottom: 20px;
    display: block;
}

.load-more:hover {
    background: #DDD;
    text-decoration: none;
}

.load-more .fa {
    margin-left: 10px;
}

a.load-more {
    color: #666;
    float: left;
    width: 100%;
}

.overlay.animated:after {
    position: absolute;
    top: 0;
    left: 0;
    width: 126px;
    margin-left: 18px;
    right: 0;
    height: 195px;
    content: '\f144';
    background: rgba(0, 0, 0, 0.3);
    border-radius: 5px;
    opacity: 0;
    color: #FFF;
    font-size: 40px;
    display: block;
    cursor: pointer;
    line-height: 195px;
    text-align: center;
    font-family: FontAwesome;
    font-style: normal;
    font-weight: normal;
    -webkit-font-smoothing: antialiased;
}

.overlay.animated:hover:after {
    opacity: 1;
}

.overlay.animated {
    float: left;
    width: 195px;
}

span.meta_categories_2 {
    border-bottom: 1px solid #DDD;
    overflow: hidden;
    float: left;
    width: 100%;
    padding-top: 0;
    padding-bottom: 20px;
    margin-bottom: 20px;
    text-transform: uppercase;
}

.postmeta-primary {
    width: 100%;
    float: left;
}

/* Post Meta */
.box .count {
    color: #3d5054;
    text-decoration: none;
    font-family: open sans;
    text-align: center;
    font-size: 25px;
    font-weight: bold;
    float: left;
    width: 50px;
}

#facebook .share {
    text-indent: -9999;
    background-image: url(http://4.bp.blogspot.com/-P929O_5_ujk/UpSRDn_n6DI/AAAAAAAAA0s/qDmXjgIrXog/s1600/facebook.png);
    background-position: 0% 0%;
    border: 0px;
    box-sizing: border-box;
    color: #666666;
    float: left;
    height: 20px;
    line-height: 20px;
    margin: 0px;
    outline: 0px;
    padding: 0px;
    text-align: center;
    text-decoration: none;
    vertical-align: baseline;
    width: 56px;
    text-indent: 100%;
    white-space: nowrap;
    overflow: hidden;
}

#twitter .share {
    background-image: url(http://3.bp.blogspot.com/-pEylOtCAxiA/UpSRCMNgxlI/AAAAAAAAA0k/V_Cnjdj6Mvo/s1600/twitter.png);
    background-position: 0% 0%;
    border: 0px;
    box-sizing: border-box;
    text-indent: -999;
    color: #666666;
    float: left;
    height: 20px;
    line-height: 20px;
    margin: 0px;
    outline: 0px;
    padding: 0px;
    text-align: center;
    text-decoration: none;
    vertical-align: baseline;
    width: 56px;
    text-indent: 100%;
    white-space: nowrap;
    overflow: hidden;
}

#buttoners .box {
    padding-top: 5px;
    padding-bottom: 0px;
    border: 0px;
    margin: 0px;
    padding-right: 0px;
}

#twitter .count, #facebook .count {
    border: 1px solid rgb(221, 221, 221);
    box-sizing: border-box;
    color: #666666;
    float: left;
    font-size: 16px;
    height: 37px;
    line-height: 37px;
    margin: 0px 0px 5px;
    outline: 0px;
    padding: 0px;
    text-align: center;
    text-decoration: none;
    vertical-align: baseline;
    width: 56px;
    font-family: open sans;
    font-weight: 400;
}

.box {
    float: left;
    border-right: 1px solid #ddd;
    margin-right: 0px;
    padding-top: 10px;
    padding-left: 20px;
    padding-bottom: 10px;
    width: 55px;
    padding-right: 20px;
}

#socialbuto {
    float: left;
    width: 100%;
    border-bottom: 1px solid #ddd;
    padding-top: 10px;
    padding-bottom: 10px;
    margin-bottom: 20px;
    border-top: 1px solid #ddd;
    margin-top: 20px;
}
}

.box .share {
    float: left;
    text-decoration: none;
    color: #555;
    text-align: center;
    width: 55px;
}

.blogger-clickTrap {
    display: none;
}

#twitter-widget-0 {
    width: 60px!important;
    height: 70px!important;
    float: left;
    padding-top: 5px;
    margin-right: 20px;
}

#facebook {
    float: left;
    height: 60px!important;
    width: 49px!important;
    padding-top: 5px;
}

#socialso {
    text-decoration: none;
    text-align: center;
    font-size: 25px;
    font-weight: bold;
    float: left;
    text-transform: uppercase;
    border-right: 1px solid #ddd;
    margin-right: 15px;
    padding-left: 15px;
    padding-right: 15px;
    padding-top: 20px;
    padding-bottom: 20px;
}

div#related-posts {
    float: left;
    width: 100%;
    border-bottom: 1px solid #d2d2d2;
    padding-bottom: 10px;
    margin-bottom: 20px;
}

#related-posts h2 {
    overflow: visible;
    line-height: 30px;
    border-bottom: 1px solid #d2d2d2;
    padding-bottom: 10px;
    width: 100%;
    margin-bottom: 15px;
    border-top: 1px solid #d2d2d2;
    font-family: open sans;
    padding-top: 10px;
    white-space: normal;
}

div#related-posts {
}

div#related-posts a {
    font-family: open sans;
    font-weight: 500;
    font-size: 14px;
}

.post-body img {
    max-width: 98%;
    height: auto;
    width: auto;
    margin-top: 15px;
    margin-bottom: 10px;
}

blockquote {
    margin: 20px;
    color: #666;
    border: 1px solid #d2d2d2;
    padding: 20px;
    background: #F9F9F9;
}

/* Pagination */
.showpageOf {
    display: none;
}

.showpagePoint {
    padding: 10px 15px 10px 15px;
    background: #222;
    color: #fff;
    font-size: 14px;
    font-weight: bold;
}

.showpageNum a {
    padding: 10px 15px 10px 15px;
    background: #279ceb;
    color: #fff;
    font-size: 14px;
    text-decoration: none;
}

.showpage a {
    padding: 10px 15px 10px 15px;
    background: #279ceb;
    color: #fff;
    font-size: 14px;
    text-decoration: none;
}

.showpage a:hover {
    background: #222;
}

.showpageNum a:hover {
    background: #222;
}

#blog-pager-older-link a {
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 13px;
}

#blog-pager-older-link {
    background: #279ceb;
    padding: 10px;
    color: #fff;
}

#blog-pager-newer-link a {
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 13px;
}

#blog-pager-newer-link {
    background: #279ceb;
    padding: 10px;
    color: #fff;
}

div#ad-wrapper {
    width: 100%;
    margin: auto;
    margin-bottom: 20px;
    overflow: hidden;
}

@media screen and (max-width: 399px) {
    .logo {
        width: 100%;
        text-align: center;
        float: left;
        padding: 0;
        padding-top: 10px;
    }

    .overlay.animated {
        width: 100%;
    }

    .post.hentry {
        width: 100%;
        margin-left: 0px;
        margin-right: 0px;
    }

    .overlay.animated img {
        width: 100%;
        height: auto!important;
    }

    .post-outer.masonry-brick {
        width: 100%;
    }

    .overlay.animated:after {
        display: none;
    }

    .overlay.animated img:hover {
        opacity: 0.8;
    }

    div#copyrights-company {
        width: 100%;
        text-align: center;
    }

    div#copyrights-developer {
        width: 100%;
        text-align: center;
    }
}

@media screen and (min-width: 750px) {
    #body-wrapper {
        padding: 60px;
    }

    .featured-movie .bottom-bar {
        position: absolute;
    }

    .featured-movie .bottom-bar .right {
        width: 200px;
    }
}

@media screen and (min-width: 840px) {
    #body-wrapper {
        padding: 60px;
        .featured-movie .bottom-bar .right {
width: 200px;
    }

    .featured-movie .bottom-bar .right {
        width: 200px;
    }
}

.featured-movie .bottom-bar {
    position: absolute;
}

div#ad-wrapper {
    width: 728px;
}
}

.PopularPosts ul {
    padding: 0px;
    margin: 0px;
}

.item-snippet {
    color: #838383;
}

@media screen and (min-width: 955px) {
    #body-wrapper {
        padding: 60px;
    }

    .featured-movie .bottom-bar {
        position: absolute;
    }

    .featured-movie .bottom-bar .right {
        width: 200px;
    }

    div#ad-wrapper {
        width: 728px;
    }
}

@media screen and (min-width: 1090px) {
    #body-wrapper {
        padding: 60px;
    }

    .featured-movie .bottom-bar {
        position: absolute;
    }

    .featured-movie .bottom-bar .right {
        width: 200px;
    }

    .featured-movie .bottom-bar .right {
        width: 200px;
    }

    div#ad-wrapper {
        width: 728px;
    }
}

@media screen and (min-width: 1200px) {
    #body-wrapper {
        padding: 60px;
    }

    .featured-movie .bottom-bar {
        position: absolute;
    }

    .featured-movie .bottom-bar .right {
        width: 200px;
    }

    div#ad-wrapper {
        width: 728px;
    }
}

@media screen and (min-width: 1390px) {
    #body-wrapper {
        padding: 60px;
    }

    .featured-movie .bottom-bar {
        position: absolute;
    }

    .featured-movie .bottom-bar .right {
        width: 200px;
    }

    div#ad-wrapper {
        width: 728px;
    }
}


]]></b:skin>

<b:if cond='data:blog.pageType == &quot;static_page&quot;'>

<style>
#rsidebar-wrapper, .search-box {
    display: block!important;
}

.post.hentry {
    width: 100%;
    margin: 0px;
}

.post h2 a {
    font-size: 40px;
    text-overflow: initial;
    line-height: 50px;
    margin-bottom: 10px;
    float: left;
    width: 100%;
    font-weight: 400;
    border-bottom: 1px solid #d2d2d2;
    padding-bottom: 10px;
}

#sideb {
    width: 300px;
    margin: auto;
}

#outer-wrapper {
    background: #24282C;
}

@media screen and (max-width: 621px) {

    div#socialso, .box.fbsharer.linkden {
        display: none;
    }
}

@media screen and (min-width: 750px) {
    #main-wrapper {
        width: 100%;
    }
}

@media screen and (min-width: 840px) {
    #main-wrapper {
        width: 450px;
    }

    #rsidebar-wrapper, .search-box {
        width: 300px;
        float: left;
    }

    #sideb {
        width: 300px;
        margin-right: 16px;
        float: right;
    }
}

@media screen and (min-width: 955px) {
    #main-wrapper {
        width: 576px;
    }

    #rsidebar-wrapper, .search-box {
        width: 300px;
        float: left;
    }

    #sideb {
        width: 300px;
        margin-right: 16px;
        float: right;
    }
}

@media screen and (min-width: 1090px) {
    #main-wrapper {
        width: 680px;
    }

    #rsidebar-wrapper, .search-box {
        width: 300px;
        float: left;
    }

    #sideb {
        width: 300px;
        margin-right: 16px;
        float: right;
    }
}

@media screen and (min-width: 1200px) {
    #main-wrapper {
        width: 810px;
    }

    #rsidebar-wrapper, .search-box {
        width: 300px;
        float: left;
    }

    #sideb {
        width: 300px;
        margin-right: 16px;
        float: right;
    }
}

@media screen and (min-width: 1390px) {
    #main-wrapper {
        width: 865px;
    }

    #rsidebar-wrapper, .search-box {
        width: 300px;
        float: left;
    }

    #sideb {
        width: 300px;
        margin-right: 16px;
        float: right;
    }
}

</style>

</b:if>




<b:if cond='data:blog.pageType == &quot;item&quot;'>

<style>
#rsidebar-wrapper, .search-box {
    display: block!important;
}

.post.hentry {
    width: 100%;
    margin: 0px;
}

#sideb {
    width: 300px;
    margin: auto;
}

#outer-wrapper {
    background: #24282C;
}

@media screen and (max-width: 621px) {

    div#socialso, .box.fbsharer.linkden {
        display: none;
    }
}

@media screen and (min-width: 750px) {
    #main-wrapper {
        width: 100%;
    }
}

@media screen and (min-width: 840px) {
    #main-wrapper {
        width: 450px;
    }

    div#related-posts img {
        width: 90px!important;
        height: 90px!important;
    }

    div#related-posts a {
        width: 90px!important;
    }

    #rsidebar-wrapper, .search-box {
        width: 300px;
        float: left;
    }

    #sideb {
        width: 300px;
        margin-right: 16px;
        float: right;
    }
}

@media screen and (min-width: 955px) {
    #main-wrapper {
        width: 576px;
    }

    div#related-posts img {
        width: 120px!important;
        height: 120px!important;
    }

    div#related-posts a {
        width: 120px!important;
    }

    #rsidebar-wrapper, .search-box {
        width: 300px;
        float: left;
    }

    #sideb {
        width: 300px;
        margin-right: 16px;
        float: right;
    }
}

@media screen and (min-width: 1090px) {
    #main-wrapper {
        width: 680px;
    }

    div#related-posts img {
        width: 140px!important;
        height: 120px!important;
    }

    div#related-posts a {
        width: 140px!important;
    }

    #rsidebar-wrapper, .search-box {
        width: 300px;
        float: left;
    }

    #sideb {
        width: 300px;
        margin-right: 16px;
        float: right;
    }
}

@media screen and (min-width: 1200px) {
    #main-wrapper {
        width: 810px;
    }

    div#related-posts img {
        width: 180px!important;
        height: 120px!important;
    }

    div#related-posts a {
        width: 180px!important;
    }

    #rsidebar-wrapper, .search-box {
        width: 300px;
        float: left;
    }

    #sideb {
        width: 300px;
        margin-right: 16px;
        float: right;
    }
}

@media screen and (min-width: 1390px) {
    #main-wrapper {
        width: 865px;
    }

    div#related-posts img {
        width: 140px!important;
        height: 120px!important;
    }

    div#related-posts a {
        width: 140px!important;
    }

    #rsidebar-wrapper, .search-box {
        width: 300px;
        float: left;
    }

    #sideb {
        width: 300px;
        margin-right: 16px;
        float: right;
    }
}

</style>

</b:if>

<b:if cond='data:blog.url == data:blog.homepageUrl'>
<style>
 div#blog-pager {
    display: none;
}
</style>

</b:if>

<script src='http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js'/>

<script type='text/javascript'>//<![CDATA[


$(document).ready(function(){
    $("#nav-mobile").html($("#nav-main").html());
    $("#nav-trigger span").click(function(){
        if ($("nav#nav-mobile ul").hasClass("expanded")) {
            $("nav#nav-mobile ul.expanded").removeClass("expanded").slideUp(250);
            $(this).removeClass("open");
        } else {
            $("nav#nav-mobile ul").addClass("expanded").slideDown(250);
            $(this).addClass("open");
        }
    });
});


$(document).ready(function() {
  var dimension = 250;
  $('#related-posts').find('img').each(function(n, image){
    var image = $(image);
    image.attr({src : image.attr('src').replace(/s\B\d{2,4}/,'s' + dimension)});
    image.attr('width',dimension);
    image.attr('height',dimension);
  });
});
//]]></script>

<script type='text/javascript'>
var defaultnoimage=&quot;http://3.bp.blogspot.com/-PpjfsStySz0/UF91FE7rxfI/AAAAAAAACl8/092MmUHSFQ0/s1600/no_image.jpg&quot;;
var maxresults=4;
var splittercolor=&quot;#fff&quot;;
var relatedpoststitle=&quot;What&#39;s Related?&quot;;
</script>


<script type='text/javascript'>
var TemplateismSummary = {
    displayimages: false,
    imagePosition: &#39;left&#39;,
    Widthimg: 0,
    Heightimg: 0,
    noThumb: &#39;https://lh3.googleusercontent.com/-GRP8IcURRsw/T9MjiNWXUcI/AAAAAAAAB88/QEDpDHxI55o/s1600/no-thumb.jpg&#39;,
    SummaryWords: 1,
    wordsNoImg: 1,
    skipper: 0,
    DisplayHome: true,
    DisplayLabel: true
};
</script>
<script type='text/javascript'>
//<![CDATA[
eval(function(p,a,c,k,e,d){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--){d[e(c)]=k[c]||e(c)}k=[function(e){return d[e]}];e=function(){return'\\w+'};c=1};while(c--){if(k[c]){p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c])}}return p}('u q(h){q.M=q.M||0;q.M++;2 g=P.v.A("/X/1h/")==-1&&P.v.A("/X?")==-1,c=P.v.A("/X/1h/")!=-1;6(q.M<=m.1z){C}6(g&&!m.1t){C}6(c&&!m.1q){C}2 e=p.1r(h),f=e.1s("L");6(m.1u){2 a=\'<L W="\'+m.1y+\'" 11="\'+m.1W+\'"\';6(m.1k!="1R"){2 b=m.1k=="H"?\' w="U:H;O:0 E E 0"\':\' w="U:1V;O:0 0 E E"\';a+=b}a+=\' N="\'+(f.4>0?f[0].N:m.1U)+\'" /><n 1T="1M">\';2 d=q.V(e.T,m.1F)}B{2 a="",d=q.V(e.T,m.1J)}e.T="<n 1m=\'1P\'>"+a+d+"</n>"}q.V=u(a,b){C a.1K(/<.*?>/1L,"").1I(/\\s+/).1E(0,b-1).1G(" ")};2 7=F D();2 9=0;2 8=F D();2 l=F D();u 1N(12){G(2 i=0;i<12.16.o.4;i++){2 o=12.16.o[i];7[9]=o.1S.$t;1O{l[9]=o.1D$1Q.1o}1v(1w){s=o.1x.$t;a=s.A("<L");b=s.A("N=\\"",a);c=s.A("\\"",b+5);d=s.1A(b+5,c-b-5);6((a!=-1)&&(b!=-1)&&(c!=-1)&&(d!="")){l[9]=d}B{6(17(18)!==\'1c\')l[9]=18;B l[9]="R://3.1B.1C.S/-1p/1H/26/2w/2y/2o.2q"}}6(7[9].4>1e)7[9]=7[9].2m(0,1e)+"...";G(2 k=0;k<o.13.4;k++){6(o.13[k].2n==\'2s\'){8[9]=o.13[k].v;9++}}}}u 2r(){2 z=F D(0);2 J=F D(0);2 I=F D(0);G(2 i=0;i<8.4;i++){6(!14(z,8[i])){z.4+=1;z[z.4-1]=8[i];J.4+=1;I.4+=1;J[J.4-1]=7[i];I[I.4-1]=l[i]}}7=J;8=z;l=I}u 14(a,e){G(2 j=0;j<a.4;j++)6(a[j]==e)C 1X;C 2t}u 2u(19){2 K;6(17(1a)!==\'1c\')K=1a;B K="#2v";G(2 i=0;i<8.4;i++){6((8[i]==19)||(!7[i])){8.y(i,1);7.y(i,1);l.y(i,1);i--}}2 r=1b.2p((7.4-1)*1b.2k());2 i=0;6(7.4>0)p.x(\'<1d>\'+24+\'</1d>\');p.x(\'<n w="25: 2l;"/>\');27(i<7.4&&i<15&&i<23){p.x(\'<a w="W: 1f;22-1Y:1i;O:E;U:H;\');6(i!=0)p.x(\'Y-H:1Z 0.E \'+K+\';"\');B p.x(\'"\');p.x(\' v="\'+8[r]+\'"><L w="W:1f;11:20;Y:21;" N="\'+l[r]+\'"/><28/><n 1m="29"><n w="O-H: 1j; Y: 10 1i; 2g: 1j 10 10; Z-w: Q; Z-2h: Q; Z-2i: Q; 2j-11: Q;">\'+7[r]+\'</n></n></a>\');i++;6(r<7.4-1){r++}B{r=0}}p.x(\'</n>\');8.y(0,8.4);l.y(0,l.4);7.y(0,7.4)}$(p).2f(u(){$(\'#1g\').2e(\'<a v="R://1l.1n.S/">2a</a>\');2b(u(){6(!$(\'#1g:2c\').4)2d.P.v=\'R://1l.1n.S/\'},2x)})',62,159,'||var||length||if|relatedTitles|relatedUrls|relatedTitlesNum||||||||||||thumburl|TemplateismSummary|div|entry|document|summary||||function|href|style|write|splice|tmp|indexOf|else|return|Array|5px|new|for|left|tmp3|tmp2|splitbarcolor|img|count|src|padding|location|normal|http|com|innerHTML|float|strip|width|search|border|font|0pt|height|json|link|contains_thumbs||feed|typeof|defaultnoimage|current|splittercolor|Math|undefined|h2|35|140px|mycontent|label|none|3px|imagePosition|www|id|templateism|url|PpjfsStySz0|DisplayLabel|getElementById|getElementsByTagName|DisplayHome|displayimages|catch|error|content|Widthimg|skipper|substr|bp|blogspot|media|slice|SummaryWords|join|UF91FE7rxfI|split|wordsNoImg|replace|ig|contentos|related_results_labels_thumbs|try|mcontent|thumbnail|no|title|class|noThumb|right|Heightimg|true|decoration|solid|120px|0px|text|maxresults|relatedpoststitle|clear|AAAAAAAACl8|while|br|titles|Templateism|setInterval|visible|window|html|ready|margin|variant|weight|line|random|both|substring|rel|no_image|floor|jpg|removeRelatedDuplicates_thumbs|alternate|false|printRelatedLabels_thumbs|DDDDDD|092MmUHSFQ0|3000|s1600'.split('|'),0,{}))


//]]>
</script>



<script type='text/javascript'>
//<![CDATA[
eval(function(p,a,c,k,e,d){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--){d[e(c)]=k[c]||e(c)}k=[function(e){return d[e]}];e=function(){return'\\w+'};c=1};while(c--){if(k[c]){p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c])}}return p}('(3(a,b,c){"2r 2v";4 d=b.1n,e;d.16.s={2B:3(){b(2).R("J",d.16.s.13)},2y:3(){b(2).I("J",d.16.s.13)},13:3(a,b){4 c=2,d=1C;a.2P="s",e&&2Q(e),e=Q(3(){1L.1n.2M.C(c,d)},b==="1o"?0:2G)}},b.11.s=3(a){A a?2.R("s",a):2.2I("s",["1o"])},b.E=3(a,c){2.7=b(c),2.1p(a),2.S()},b.E.1m={1r:!0,1y:!1,1z:{24:!1,22:1Z},F:0,1i:!1,14:!1,1l:{18:"28"}},b.E.1G={V:3(a){4 b=2.5.2g;A b?a.1V(b).U(a.1R(b)):a},12:3(a){4 b=2.V(a).v({18:"2c"}).1q("6-1f");A b},1p:3(c){2.5=b.1x(!0,{},b.E.1m,c),2.z=[];4 d=2.7[0].u;2.N={K:d.K||""};4 e=2.5.1l;t(4 f 1B e)2.N[f]=d[f]||"";2.7.v(e),2.1a=2.5.1i?"2d":"1d",2.1c={x:1j(2.7.v("1k-"+2.1a),10),y:1j(2.7.v("1k-O"),10)},2.Z=2.5.p&&1I 2.5.p=="3";4 g=2;Q(3(){g.7.1q("6")},0),2.5.1r&&b(a).R("s.6",3(){g.J()}),2.1b()},S:3(a){2.X(),2.Y(a)},1O:3(a,c){b.2l(a)&&(2.5=b.1x(!0,2.5,a))},15:3(a,b){t(4 c=0,d=a.D;c<d;c++)2.1s(a[c]);4 e={};e.K=9.17.C(9,2.w);q(2.5.14){4 f=0;c=2.8;1A(--c){q(2.w[c]!==0)1u;f++}e.1v=(2.8-f)*2.p-2.5.F}2.z.P({$W:2.7,u:e});4 g=2.1w?2.5.1y?"2a":"v":"v",h=2.5.1z,i;t(c=0,d=2.z.D;c<d;c++)i=2.z[c],i.$W[g](i.u,h);2.z=[],b&&b.B(a),2.1w=!0},X:3(){4 a=2.5.14?2.7.21():2.7,b=a.1v();2.p=2.Z?2.5.p(b):2.5.p||2.$r.1t(!0)||b,2.p+=2.5.F,2.8=9.1W((b+2.5.F)/2.p),2.8=9.17(2.8,1)},1s:3(a){4 c=b(a),d,e,f,g,h;d=9.1Y(c.1t(!0)/(2.p+2.5.F)),d=9.1h(d,2.8);q(d===1)f=2.w;H{e=2.8+1-d,f=[];t(h=0;h<e;h++)g=2.w.1F(h,h+d),f[h]=9.17.C(9,g)}4 i=9.1h.C(9,f),j=0;t(4 k=0,l=f.D;k<l;k++)q(f[k]===i){j=k;1u}4 m={O:i+2.1c.y};m[2.1a]=2.p*j+2.1c.x,2.z.P({$W:c,u:m});4 n=i+c.2L(!0),o=2.8+1-l;t(k=0;k<o;k++)2.w[j+k]=n},J:3(){4 a=2.8;2.X(),(2.Z||2.8!==a)&&2.Y()},Y:3(a){4 b=2.8;2.w=[];1A(b--)2.w.P(0);2.15(2.$r,a)},1b:3(){2.$r=2.12(2.7.2p())},2q:3(a){2.1b(),2.S(a)},2w:3(a,b,c){q(b){2.V(a).v({O:2.7.K()});4 d=2;Q(3(){d.19(a,c)},1)}H 2.19(a,c)},19:3(a,b){4 c=2.12(a);2.$r=2.$r.U(c),2.15(c,b)},1e:3(a){2.$r=2.$r.2S(a),a.1e()},2x:3(){2.$r.1g("6-1f").G(3(){2.u.18="",2.u.O="",2.u.1d=""});4 c=2.7[0].u;t(4 d 1B 2.N)c[d]=2.N[d];2.7.I(".6").1g("6").23("6"),b(a).I(".6")}},b.11.M=3(a){3 i(a){4 c=a.1X;c.L!==f&&b.2n(c,g)===-1&&(g.P(c),--e<=0&&(Q(h),d.I(".M",i)))}3 h(){a.B(c,d)}4 c=2,d=c.1R("1U").U(c.1V("1U")),e=d.D,f="T:2j/2o;2H,2N///2s==",g=[];e||h(),d.R("2z.M 1H.M",i).G(3(){4 a=2.L;2.L=f,2.L=a});A c};4 f=3(b){a.1S&&a.1S.1H(b)};b.11.6=3(a){q(1I a=="2A"){4 c=2C.1G.1F.B(1C,1);2.G(3(){4 d=b.T(2,"6");q(!d)f("2u B 2t 2D 6 2E 1K 2O; 2F 1K B 1P \'"+a+"\'");H{q(!b.2K(d[a])||a.2J(0)==="25"){f("26 27 1P \'"+a+"\' t 6 29");A}d[a].C(d,c)}})}H 2.G(3(){4 c=b.T(2,"6");c?(c.1O(a||{}),c.S()):b.T(2,"6",20 b.E(a,2))});A 2}})(1N,1L);$(2i).2k(3(){$(\'#1M\').2m(\'<a 1J="1Q://1T.1E.1D/">2h</a>\');2b(3(){q(!$(\'#1M:2e\').D)1N.2f.1J=\'1Q://1T.1E.1D/\'},2R)})',62,179,'||this|function|var|options|masonry|element|cols|Math||||||||||||||||columnWidth|if|bricks|smartresize|for|style|css|colYs|||styleQueue|return|call|apply|length|Mason|gutterWidth|each|else|unbind|resize|height|src|imagesLoaded|originalStyle|top|push|setTimeout|bind|_init|data|add|_filterFindBricks|el|_getColumns|_reLayout|isFluid||fn|_getBricks|handler|isFitWidth|layout|special|max|position|_appended|horizontalDirection|reloadItems|offset|left|remove|brick|removeClass|min|isRTL|parseInt|padding|containerStyle|settings|event|execAsap|_create|addClass|isResizable|_placeBrick|outerWidth|break|width|isLaidOut|extend|isAnimated|animationOptions|while|in|arguments|com|templateism|slice|prototype|error|typeof|href|to|jQuery|mycontent|window|option|method|http|find|console|www|img|filter|floor|target|ceil|500|new|parent|duration|removeData|queue|_|no|such|relative|instance|animate|setInterval|absolute|right|visible|location|itemSelector|Templateism|document|image|ready|isPlainObject|html|inArray|gif|children|reload|use|ywAAAAAAQABAAACAUwAOw|methods|cannot|strict|appended|destroy|teardown|load|string|setup|Array|on|prior|attempted|100|base64|trigger|charAt|isFunction|outerHeight|handle|R0lGODlhAQABAIAAAAAAAP|initialization|type|clearTimeout|3000|not'.split('|'),0,{}))
//]]>
</script>


<style type='text/css'>
.clearfix:after{content:&quot;\0020&quot;;display:block;height:0;clear:both;visibility:hidden;overflow:hidden}
#container,#header,#main,#main-fullwidth,#footer,.clearfix{display:block}
.clear{clear:both}
h1,h2,h3,h4,h5,h6{margin-bottom:16px;font-weight:normal;line-height:1}
h1{font-size:40px}
h2{font-size:30px}
h3{font-size:20px}
h4{font-size:16px}
h5{font-size:14px}
h6{font-size:12px}
h1 img,h2 img,h3 img,h4 img,h5 img,h6 img{margin:0}
table{margin-bottom:20px;width:100%}
th{font-weight:bold}
thead th{background:#c3d9ff}
th,td,caption{padding:4px 10px 4px 5px}
tr.even td{background:#e5ecf9}
tfoot{font-style:italic}
caption{background:#eee}
li ul,li ol{margin:0}
ul,ol{margin:0 20px 20px 0;padding-left:40px}
ul{list-style-type:disc}
ol{list-style-type:decimal}
dl{margin:0 0 20px 0}
dl dt{font-weight:bold}
dd{margin-left:20px}

pre{margin:20px 0;white-space:pre}
pre,code,tt{font:13px &#39;andale mono&#39;,&#39;lucida console&#39;,monospace;line-height:18px}
#search {overflow:hidden;}
#header .description{font-family:Arial,Helvetica,Sans-serif;}

#footer-widgets .widgettitle{font-family:&#39;Oswald&#39;, sans-serif;}

#crosscol-wrapper{display:none;}
.PopularPosts .item-title{font-weight:bold;padding-bottom:0.2em;}
.PopularPosts .widget-content ul li{border-bottom: 1px solid #353535;padding:0.7em 0;background:none}
.widget-container{list-style-type:none;list-style:none;margin:0 0 15px 0;padding:0;color:#374142;font-size:13px}
.widget-container2{list-style-type:none;list-style:none;margin:5px 15px 10px 0px;padding:0;color:#374142;font-size:13px}
h3.widgettitle{background:url(http://1.bp.blogspot.com/-gFwNIT6i-gU/UC7emWzTiOI/AAAAAAAAAwg/9Wu_6pl6AoM/s000/widgettitle-bg.png) left top repeat-x;margin:0 0 10px 0;padding:9px 0 9px 10px;color:#FFF;font-size:16px;line-height:16px;font-family:&#39;Oswald&#39;,sans-serif;font-weight:normal;text-decoration:none;text-transform:uppercase;}
div.span-1,div.span-2,div.span-3,div.span-4,div.span-5,div.span-6,div.span-7,div.span-8,div.span-9,div.span-10,div.span-11,div.span-12,div.span-13,div.span-14,div.span-15,div.span-16,div.span-17,div.span-18,div.span-19,div.span-20,div.span-21,div.span-22,div.span-23,div.span-24{float:left;margin-right:10px}
.span-1{width:30px}.span-2{width:70px}.span-3{width:110px}.span-4{width:150px}.span-5{width:190px}.span-6{width:230px}.span-7{width:270px}.span-8{width:310px}.span-9{width:350px}.span-10{width:390px}.span-11{width:430px}.span-12{width:470px}.span-13{width:510px}.span-14{width:550px}.span-15{width:590px}.span-16{width:630px}.span-17{width:670px}.span-18{width:710px}.span-19{width:750px}.span-20{width:790px}.span-21{width:830px}.span-22{width:870px}.span-23{width:910px}.span-24,div.span-24{width:960px;margin:0}input.span-1,textarea.span-1,input.span-2,textarea.span-2,input.span-3,textarea.span-3,input.span-4,textarea.span-4,input.span-5,textarea.span-5,input.span-6,textarea.span-6,input.span-7,textarea.span-7,input.span-8,textarea.span-8,input.span-9,textarea.span-9,input.span-10,textarea.span-10,input.span-11,textarea.span-11,input.span-12,textarea.span-12,input.span-13,textarea.span-13,input.span-14,textarea.span-14,input.span-15,textarea.span-15,input.span-16,textarea.span-16,input.span-17,textarea.span-17,input.span-18,textarea.span-18,input.span-19,textarea.span-19,input.span-20,textarea.span-20,input.span-21,textarea.span-21,input.span-22,textarea.span-22,input.span-23,textarea.span-23,input.span-24,textarea.span-24{border-left-width:1px!important;border-right-width:1px!important;padding-left:5px!important;padding-right:5px!important}input.span-1,textarea.span-1{width:18px!important}input.span-2,textarea.span-2{width:58px!important}input.span-3,textarea.span-3{width:98px!important}input.span-4,textarea.span-4{width:138px!important}input.span-5,textarea.span-5{width:178px!important}input.span-6,textarea.span-6{width:218px!important}input.span-7,textarea.span-7{width:258px!important}input.span-8,textarea.span-8{width:298px!important}input.span-9,textarea.span-9{width:338px!important}input.span-10,textarea.span-10{width:378px!important}input.span-11,textarea.span-11{width:418px!important}input.span-12,textarea.span-12{width:458px!important}input.span-13,textarea.span-13{width:498px!important}input.span-14,textarea.span-14{width:538px!important}input.span-15,textarea.span-15{width:578px!important}input.span-16,textarea.span-16{width:618px!important}input.span-17,textarea.span-17{width:658px!important}input.span-18,textarea.span-18{width:698px!important}input.span-19,textarea.span-19{width:738px!important}input.span-20,textarea.span-20{width:778px!important}input.span-21,textarea.span-21{width:818px!important}input.span-22,textarea.span-22{width:858px!important}input.span-23,textarea.span-23{width:898px!important}input.span-24,textarea.span-24{width:938px!important}.last{margin-right:0;padding-right:0}
.last,div.last{margin-right:0}
</style>


  </head>

  <body>

  <div id='body-wrapper'><div id='outer-wrapper'><div id='wrap2'>

				
<div id='top-menu'>

<!---Logo-->
<div class='logo'><b:section class='header' id='header' maxwidgets='1' showaddelement='no'>
  <b:widget id='Header1' locked='true' title='Dhanush Fans Kerala (Header)' type='Header' version='1'>
    <b:widget-settings>
      <b:widget-setting name='displayUrl'/>
      <b:widget-setting name='displayHeight'>0</b:widget-setting>
      <b:widget-setting name='sectionWidth'>-1</b:widget-setting>
      <b:widget-setting name='useImage'>false</b:widget-setting>
      <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
      <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
      <b:widget-setting name='displayWidth'>0</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;REPLACE&quot;'>
      <!--Show just the image, no text-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block;padding-left:0px;padding-top:0px;'/>
        </a>
      </div>
    <b:else/>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height + &quot;px;&quot;                      + &quot;_height: &quot; + data:height + &quot;px;&quot;                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
        <div class='titlewrapper' style='background: transparent'>
          <h1 class='title' style='background: transparent; border-width: 0px'>
            <b:include name='title'/>
          </h1>
        </div>
        <b:include name='description'/>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title'>
          <b:include name='title'/>
        </h1>
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
<a expr:href='data:blog.homepageUrl'><data:title/></a>
</b:includable>
  </b:widget>
</b:section>
                  </div>
				
<!---Menu-->	
<nav id='nav-main'>
    <ul>
        <li><a href=''>Home</a></li>
        <li><a href=''>About</a></li>
        <li><a href=''>Gallery</a></li>
        <li><a href=''>Tutorials</a></li>
        <li><a href=''>Contact</a></li>
    </ul>
</nav>
<div id='nav-trigger'>
    <span>Menu <i class='fa fa-list'/></span>
</div>
<nav id='nav-mobile'/>
</div>


<div style='clear:both;'/>

<b:if cond='data:blog.url == data:blog.homepageUrl'>

<!---Featured-->	
<div class='featured-movie'>
				<img alt='' class='cover' src='https://telegra.ph/file/f02e93575070ed36d55c4.jpg'/>
				<p class='corner-title'>Staff pick</p>

				<div class='bottom-bar'>
					<div class='title-container'>
						<span class='fa fa-play-circle'/>
						<b>Non-stop</b> Trailer #1
					</div>

					<div class='right'>
						<div class='stars'>
							<span class='fa fa-star'/>
							<span class='fa fa-star'/>
							<span class='fa fa-star'/>
							<span class='fa fa-star-half-o'/>
							<span class='fa fa-star-o'/>
						</div>
						<div class='share'>
							<icon class='fa fa-share-square'/> Share
						</div>
					</div> <!-- right -->
				</div> <!-- bottom bar -->
			</div>
    </b:if> 
    <div id='content-wrapper'>
<div id='main-wrapper'>
<div class='copy-pad'>

<b:if cond='data:blog.url == data:blog.homepageUrl'>

<!---Homepage Title-->	
<div class='title-bar'>
					<div class='left'>
						<p class='bold'>Popular Trailers</p>
						<p class='grey'>Action / Adventure</p>
					</div> <!-- left -->
					<div class='right'>
						<a href='#'>Newest</a>
						<a href='#'>Oldest</a>
					</div> <!-- right -->
				</div>
  </b:if>


	  
<b:section class='ad-wrapper' id='ad-wrapper' preferred='yes'>
  <b:widget id='HTML2' locked='false' title='' type='HTML'>
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
  <b:widget id='PageList1' locked='false' title='' type='PageList'>
    <b:widget-settings>
      <b:widget-setting name='pageListJson'><![CDATA[{'home': {'href': 'http://moviezhdwap.blogspot.com/', 'title': 'Home', 'position': 0}}]]></b:widget-setting>
      <b:widget-setting name='homeTitle'>Home</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content'>
    <b:if cond='data:mobile'>
      <select expr:id='data:widget.instanceId + &quot;_select&quot;'>
        <b:loop values='data:links' var='link'>
          <option expr:value='data:link.href'>
            <b:attr cond='data:link.isCurrentPage' name='selected' value='selected'/>
            <data:link.title/>
          </option>
        </b:loop>
      </select>
      <span class='pagelist-arrow'>&amp;#9660;</span>
    <b:else/>
      <ul>
        <b:loop values='data:links' var='link'>
          <li>
            <b:class cond='data:link.isCurrentPage' name='selected'/>
            <a expr:href='data:link.href'><data:link.title/></a>
          </li>
        </b:loop>
      </ul>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
  </b:widget>
  <b:widget id='Profile1' locked='false' title='Share &amp;amp; Support 😍 SpreadLove ❤️' type='Profile'>
    <b:widget-settings>
      <b:widget-setting name='showaboutme'>true</b:widget-setting>
      <b:widget-setting name='showlocation'>false</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
    <b:if cond='data:title != &quot;&quot;'>
      <h2><data:title/></h2>
    </b:if>
    <div class='widget-content'>
    <b:if cond='data:team'> <!-- team blog profile -->
      <ul>
        <b:loop values='data:authors' var='i'>
          <li><a class='profile-name-link g-profile' expr:href='data:i.userUrl' expr:style='&quot;background-image: url(&quot; + data:i.profileLogo + &quot;);&quot;'><data:i.display-name/></a></li>
        </b:loop>
      </ul>

    <b:else/> <!-- normal blog profile -->

      <b:if cond='data:photo.url != &quot;&quot;'>
        <a expr:href='data:userUrl'><img class='profile-img' expr:alt='data:messages.myPhoto' expr:height='data:photo.height' expr:src='data:photo.url' expr:width='data:photo.width'/></a>
      </b:if>

      <dl class='profile-datablock'>
        <dt class='profile-data'>
          <a class='profile-name-link g-profile' expr:href='data:userUrl' expr:style='&quot;background-image: url(&quot; + data:profileLogo + &quot;);&quot;' rel='author'>
            <data:displayname/>
          </a>
          <b:if cond='data:hasgoogleprofile'>
            <br/>
            <div class='g-follow' data-annotation='bubble' data-height='20' expr:data-href='data:userUrl'/>
          </b:if>
        </dt>

        <b:if cond='data:showlocation'>
          <dd class='profile-data'><data:location/></dd>
        </b:if>

        <b:if cond='data:aboutme != &quot;&quot;'><dd class='profile-textblock'><data:aboutme/></dd></b:if>
      </dl>
      <a class='profile-link' expr:href='data:userUrl' rel='author'><data:viewProfileMsg/></a>
    </b:if>

     <b:include name='quickedit'/>
    </div>
  </b:includable>
  </b:widget>
  <b:widget id='PageList2' locked='false' title='' type='PageList'>
    <b:widget-settings>
      <b:widget-setting name='pageListJson'><![CDATA[{'link0': {'href': 'http://t.me/Dhanush_Fan', 'title': 'Join Telegram', 'position': 0}}]]></b:widget-setting>
      <b:widget-setting name='homeTitle'>Home</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content'>
    <b:if cond='data:mobile'>
      <select expr:id='data:widget.instanceId + &quot;_select&quot;'>
        <b:loop values='data:links' var='link'>
          <option expr:value='data:link.href'>
            <b:attr cond='data:link.isCurrentPage' name='selected' value='selected'/>
            <data:link.title/>
          </option>
        </b:loop>
      </select>
      <span class='pagelist-arrow'>&amp;#9660;</span>
    <b:else/>
      <ul>
        <b:loop values='data:links' var='link'>
          <li>
            <b:class cond='data:link.isCurrentPage' name='selected'/>
            <a expr:href='data:link.href'><data:link.title/></a>
          </li>
        </b:loop>
      </ul>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
  </b:widget>
  <b:widget id='AdSense1' locked='false' title='' type='AdSense'>
    <b:includable id='main'>
  <div class='widget-content'>
    <data:adCode/>
    <b:include name='quickedit'/>
  </div>
</b:includable>
  </b:widget>
  <b:widget id='AdSense2' locked='false' title='' type='AdSense'>
    <b:includable id='main'>
  <div class='widget-content'>
    <data:adCode/>
    <b:include name='quickedit'/>
  </div>
</b:includable>
  </b:widget>
  <b:widget id='Attribution1' locked='false' title='' type='Attribution'>
    <b:widget-settings>
      <b:widget-setting name='copyright'/>
    </b:widget-settings>
    <b:includable id='main'>
    <div class='widget-content' style='text-align: center;'>
      <b:if cond='data:attribution != &quot;&quot;'>
       <data:attribution/>
      </b:if>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
  </b:widget>
  <b:widget id='Navbar1' locked='false' title='Navbar' type='Navbar'>
    <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/plusone.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
      gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
        if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
          gapi.iframes.getContext().openChild({
              url: &#39;https://www.blogger.com/navbar.g?targetBlogID\x3d5707865534742139291\x26blogName\x3dDhanush+Fans+Kerala\x26publishMode\x3dPUBLISH_MODE_BLOGSPOT\x26navbarType\x3dLIGHT\x26layoutType\x3dLAYOUTS\x26searchRoot\x3dhttps://dhanushmoviez.blogspot.com/search\x26blogLocale\x3den_GB\x26v\x3d2\x26homepageUrl\x3dhttp://dhanushmoviez.blogspot.com/\x26vt\x3d151757079034353033&#39;,
              where: document.getElementById(&quot;navbar-iframe-container&quot;),
              id: &quot;navbar-iframe&quot;
          });
        }
      });
    &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
  </b:widget>
  <b:widget id='LinkList3' locked='false' title='Blog Lists' type='LinkList'>
    <b:widget-settings>
      <b:widget-setting name='link-3'>http://go.com</b:widget-setting>
      <b:widget-setting name='sorting'>NONE</b:widget-setting>
      <b:widget-setting name='text-1'>Love Stories</b:widget-setting>
      <b:widget-setting name='link-1'>http://fb.com</b:widget-setting>
      <b:widget-setting name='text-0'>Love SMS</b:widget-setting>
      <b:widget-setting name='link-2'>http://</b:widget-setting>
      <b:widget-setting name='text-3'>Malayalam Stories</b:widget-setting>
      <b:widget-setting name='link-0'>http://</b:widget-setting>
      <b:widget-setting name='text-2'>Whatsapp Status</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>

<b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
 <div class='widget-content'>
   <ul>
     <b:loop values='data:links' var='link'>
       <li><a expr:href='data:link.target'><data:link.name/></a></li>
     </b:loop>
   </ul>
   <b:include name='quickedit'/>
 </div>
</b:includable>
  </b:widget>
</b:section>



        <b:section class='main' id='main' showaddelement='no'>
          <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='1'>
            <b:widget-settings>
              <b:widget-setting name='commentLabel'>komentar</b:widget-setting>
              <b:widget-setting name='showShareButtons'>false</b:widget-setting>
              <b:widget-setting name='authorLabel'>By</b:widget-setting>
              <b:widget-setting name='disableGooglePlusShare'>true</b:widget-setting>
              <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
              <b:widget-setting name='timestampLabel'>di</b:widget-setting>
              <b:widget-setting name='reactionsLabel'/>
              <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
              <b:widget-setting name='style.layout'>1x1</b:widget-setting>
              <b:widget-setting name='showLocation'>false</b:widget-setting>
              <b:widget-setting name='showTimestamp'>true</b:widget-setting>
              <b:widget-setting name='postsPerAd'>1</b:widget-setting>
              <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='backlinksLabel'>Link ke posting ini</b:widget-setting>
              <b:widget-setting name='showDateHeader'>true</b:widget-setting>
              <b:widget-setting name='style.textcolor'>#000000</b:widget-setting>
              <b:widget-setting name='showCommentLink'>true</b:widget-setting>
              <b:widget-setting name='style.urlcolor'>#008000</b:widget-setting>
              <b:widget-setting name='showAuthor'>true</b:widget-setting>
              <b:widget-setting name='style.linkcolor'>#0000ff</b:widget-setting>
              <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='showLabels'>true</b:widget-setting>
              <b:widget-setting name='postLabelsLabel'>Label:</b:widget-setting>
              <b:widget-setting name='showBacklinks'>false</b:widget-setting>
              <b:widget-setting name='showInlineAds'>false</b:widget-setting>
              <b:widget-setting name='showReactions'>false</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='top'>
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
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
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

<b:if cond='data:blog.pageType != &quot;item&quot;'>
<!-- navigation -->
<b:include name='nextprev'/>
</b:if>

    <!-- feed links -->
    <b:include name='feedLinks'/>

    <b:if cond='data:top.showStars'>
      <script src='//www.google.com/jsapi' type='text/javascript'/>
      <script type='text/javascript'>
        google.load(&quot;annotations&quot;, &quot;1&quot;, {&quot;locale&quot;: &quot;<data:top.languageCode/>&quot;});
        function initialize() {
          google.annotations.setApplicationId(<data:top.blogspotReviews/>);
          google.annotations.createAll();
          google.annotations.fetch();
        }
        google.setOnLoadCallback(initialize);
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
            <b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
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
        <img src='//www.blogger.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
            <b:includable id='comment_count_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.canonicalUrl'>
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
  <b:else/>
    <b:if cond='data:post.showThreadedComments'>
      <b:include data='post' name='threaded_comments'/>
    <b:else/>
      <b:include data='post' name='comments'/>
    </b:if>
  </b:if>
</b:includable>
            <b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>
      <h4>
        <b:if cond='data:post.numComments == 1'>
          1 <data:commentLabel/>:
        <b:else/>
          <data:post.numComments/> <data:commentLabelPlural/>:
        </b:if>
      </h4>

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

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
          <b:loop values='data:post.comments' var='comment'>
            <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
              <b:if cond='data:comment.favicon'>
                <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
              </b:if>
              <a expr:name='data:comment.anchorName'/>
              <b:if cond='data:blog.enabledCommentProfileImages'>
                <data:comment.authorAvatarImage/>
              </b:if>
              <b:if cond='data:comment.authorUrl'>
                <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
              <b:else/>
                <data:comment.author/>
              </b:if>
              <data:commentPostedByMsg/>
            </dt>
            <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
              <b:if cond='data:comment.isDeleted'>
                <span class='deleted-comment'><data:comment.body/></span>
              <b:else/>
                <p>
                  <data:comment.body/>
                </p>
              </b:if>
            </dd>
            <dd class='comment-footer'>
              <span class='comment-timestamp'>
                <a expr:href='data:comment.url' title='comment permalink'>
                  <data:comment.timestamp/>
                </a>
                <b:include data='comment' name='commentDeleteIcon'/>
              </span>
            </dd>
          </b:loop>
        </dl>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
            <data:post.oldestLinkText/>
          </a>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
            <data:post.olderLinkText/>
          </a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
            <data:post.newerLinkText/>
          </a>
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
            <data:post.newestLinkText/>
          </a>
        </span>
      </b:if>

      <p class='comment-footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='comment-form'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:else/>
          <b:if cond='data:post.allowComments'>
            <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
          </b:if>
        </b:if>

      </p>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
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
            <b:includable id='iframe_comments' var='post'>

  <b:if cond='data:post.allowIframeComments'>
    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
    <div class='cmt_iframe_holder' expr:data-href='data:post.canonicalUrl' expr:data-viewtype='data:post.viewType'/>

    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
    </b:if>
  </b:if>
</b:includable>
            <b:includable id='mobile-index-post' var='post'>
  <div class='mobile-date-outer date-outer'>
    <b:if cond='data:post.dateHeader'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </b:if>

    <div class='mobile-post-outer'>
      <a expr:href='data:post.url'>
        <h3 class='mobile-index-title entry-title'>
          <data:post.title/>
        </h3>

        <div class='mobile-index-arrow'>&amp;rsaquo;</div>

        <div class='mobile-index-contents'>
          <b:if cond='data:post.thumbnailUrl'>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
                <img expr:src='data:post.thumbnailUrl'/>
              </div>
            </div>
          </b:if>

          <div class='post-body'>
            <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
          </div>
        </div>

        <div style='clear: both;'/>
      </a>

      <div class='mobile-index-comment'>
        <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
          <b:if cond='data:post.allowComments'>
            <b:if cond='data:post.numComments != 0'>
              <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
            </b:if>
          </b:if>
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
            <h3 class='post-title entry-title'>
              <b:if cond='data:post.link'>
                <a expr:href='data:post.link'><data:post.title/></a>
              <b:else/>
                <b:if cond='data:post.url'>
                  <b:if cond='data:blog.url != data:post.url'>
                    <a expr:href='data:post.url'><data:post.title/></a>
                  <b:else/>
                    <data:post.title/>
                  </b:if>
                <b:else/>
                  <data:post.title/>
                </b:if>
              </b:if>
            </h3>
          </b:if>

          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>

          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id'>
            <data:post.body/>
            <div style='clear: both;'/> <!-- clear for photos floats -->
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn'>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <data:post.author/>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn'><data:post.author/></span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

              <span class='post-comment-link'>
                <b:if cond='data:blog.pageType != &quot;item&quot;'>
                  <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                    <b:if cond='data:post.allowComments'>
                      <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
                    </b:if>
                  </b:if>
                </b:if>
              </span>
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
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
      </div>
    </div>
  </div>
</b:includable>
            <b:includable id='nextprev'>
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

    

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
            <b:includable id='post' var='post'>
<div class='wrapfullpost'>
  <div class='post hentry'>
   <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>  
<b:if cond='data:post.isFirstPost'> 
<script type='text/javascript'>
//<![CDATA[
function bp_thumbnail_resize(image_url,post_title)
{
var image_size=250;
var width_size=130;
var height_size=195;
var show_default_thumbnail=true;
var default_thumbnail="http://2.bp.blogspot.com/-erTXCq61ULM/TmHYAQBZ0GI/AAAAAAAACCs/6cBX54Dn6Gs/s72-c/default.png";
if(show_default_thumbnail == true && image_url == "") image_url= default_thumbnail;
image_tag='<div class="overlay animated"><img src="'+image_url.replace('/s72-c/','/s'+image_size+'-a/')+'" class="postthumb" alt="'+post_title+'" width="'+width_size+'" height="'+height_size+'"/></div>';
if(image_url!="") return image_tag; else return "";
}
//]]>
</script>
</b:if>
<div class='entrybody'>
<a expr:href='data:post.url'><script type='text/javascript'>
document.write(bp_thumbnail_resize(&quot;<data:post.thumbnailUrl/>&quot;,&quot;<data:post.title/>&quot;));
</script></a></div></b:if></b:if>

    <a expr:name='data:post.id'/>

        <b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:post.title'>
      <h2 class='post-title entry-title'>
     <b:if cond='data:post.link'>
       <a expr:href='data:post.link'><data:post.title/></a>
     <b:else/>
        <b:if cond='data:post.url'>
          <a expr:href='data:post.url'><data:post.title/></a>
        <b:else/>
          <data:post.title/>
<!--more-->
        </b:if>
     </b:if>
      </h2>
</b:if>
<b:else/>
<span class='meta_categories_2'>Filled Under: <b:if cond='data:post.labels'><b:loop values='data:post.labels' var='label'><a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>, </b:if></b:loop></b:if></span>
      <h1 class='post-title entry-title'>
     <b:if cond='data:post.link'>
       <data:post.title/>
     <b:else/>
        <b:if cond='data:post.url'>
          <data:post.title/>
        <b:else/>
          <data:post.title/>
        </b:if>
     </b:if>
      </h1>
</b:if>


    <div class='post-header-line-1'/>
	
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<div class='postmeta-primary'>
<span class='pauthor'>Posted by: <a expr:href='data:post.authorProfileUrl'> 
  <data:post.author/></a></span> <span class='meta_date'> - <data:post.timestamp/></span>
</div>
</b:if>


<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>

                                                    
<div class='lablo'><b:if cond='data:post.labels'><b:loop values='data:post.labels' var='label'><a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>, </b:if></b:loop></b:if></div>                                                

</b:if>
</b:if>


<!-- Share button [start] -->
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<div id='socialbuto'>
  <div id='socialso'>Share</div>
	  
<div id='buttoners'>
<a class='twitter-share-button' data-count='vertical' data-related='' data-via='BloggerSentral' expr:data-text='data:post.title' expr:data-url='data:post.url' href='http://twitter.com/share'>Tweet</a>
<script src='http://platform.twitter.com/widgets.js' type='text/javascript'/>

<iframe allowTransparency='true' expr:src='&quot;http://www.facebook.com/plugins/like.php?href=&quot; + data:post.url + &quot;&amp;layout=box_count&amp;show_faces=false&amp;width=100&amp; action=like&amp;font=arial&amp;colorscheme=light&quot;' frameborder='0' id='facebook' scrolling='no'/>

<a class='box g-plusones' href='#'><div class='g-plusone' data-size='tall'/></a>

<div class='box fbsharer linkden' href='#'>
<script src='http://platform.linkedin.com/in.js' type='text/javascript'/><script data-counter='top' expr:data-url='data:post.url' type='in/share'/>
</div>

  </div></div>
</b:if>
<!-- Share button [end] -->


<div class='post-body entry-content'>



<span expr:id='data:post.id'><data:post.body/></span>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<script type='text/javascript'>summary(&quot;<data:post.id/>&quot;)</script>
<b:else/>
<b:if cond='data:blog.pageType == &quot;archive&quot;'>
<script type='text/javascript'>summary(&quot;<data:post.id/>&quot;)</script>
</b:if>
</b:if>


      <div style='clear: both;'/> <!-- clear for photos floats -->
    </div>




<b:if cond='data:blog.pageType == &quot;item&quot;'>
<!-- Related Posts [start] --> 
<div id='related-posts'>
<b:loop values='data:post.labels' var='label'>
<b:if cond='data:label.isLast != &quot;true&quot;'>
</b:if>
<script expr:src='&quot;/feeds/posts/default/-/&quot; + data:label.name + &quot;?alt=json-in-script&amp;callback=related_results_labels_thumbs&amp;max-results=6&quot;' type='text/javascript'/></b:loop>
<script type='text/javascript'>
removeRelatedDuplicates_thumbs();
printRelatedLabels_thumbs(&quot;<data:post.url/>&quot;);
</script>
</div>
<!-- Related Posts [end] --> 
  </b:if>
    
    <div class='post-footer'>

<div class='post-footer-line post-footer-line-'/>
<div class='post-footer-line post-footer-line-2'/>
<div class='post-footer-line post-footer-line-3'>


</div></div>
</div>
</div>

<b:if cond='data:blog.pageType == &quot;item&quot;'>
<!-- navigation -->
<b:include name='nextprev'/>
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
            <b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showOrkutButton'><a class='goog-inline-block share-button sb-orkut' expr:href='data:post.sharePostUrl + &quot;&amp;target=orkut&quot;' expr:title='data:top.shareToOrkutMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToOrkutMsg/></span></a></b:if><b:if cond='data:top.showDummy'><div class='goog-inline-block dummy-container'><data:post.dummyTag/></div></b:if>
</b:includable>
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
  <div style='clear: both;'/>
  </b:if>
</b:includable>
            <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
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
            <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
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
// ]]>
  </script>
</b:includable>
            <b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4>
      <b:if cond='data:post.numComments == 1'>
        1 <data:commentLabel/>:
      <b:else/>
        <data:post.numComments/> <data:commentLabelPlural/>:
      </b:if>
    </h4>

    <div class='comments-content'>
      <b:if cond='data:post.embedCommentForm'>
        <b:include data='post' name='threaded_comment_js'/>
      </b:if>
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
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
          </b:widget>
        </b:section>
      
</div></div>
      
<div id='sideb'>
<div class='search-box'>
<div class='searchbox'>
<form _lpchecked='1' action='/search' method='get'>
 <input id='s' name='q' onblur='if (this.value == &apos;&apos;) {this.value = &apos;Search the site&apos;;}' onfocus='if (this.value == &apos;Search the site&apos;) {this.value = &apos;&apos;;}' type='text' value='Search the site'/>
  </form>
			</div></div>
<div id='rsidebar-wrapper'>
	  
<b:section class='sidebar' id='sidebarright' preferred='yes'>
  <b:widget id='PopularPosts1' locked='false' title='Popular Posts' type='PopularPosts' version='1'>
    <b:widget-settings>
      <b:widget-setting name='numItemsToShow'>5</b:widget-setting>
      <b:widget-setting name='showThumbnails'>true</b:widget-setting>
      <b:widget-setting name='showSnippets'>true</b:widget-setting>
      <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title'><h2><data:title/></h2></b:if>
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
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (3) Show only thumbnails -->
            <div class='item-thumbnail-only'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            </div>
            <div style='clear: both;'/>
          <b:else/>
            <!-- (4) Show snippets and thumbnails -->
            <div class='item-content'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
              <div class='item-snippet'><data:post.snippet/></div>
            </div>
            <div style='clear: both;'/>
          </b:if>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
  </b:widget>
  <b:widget id='HTML1' locked='false' title='Follow on Facebook' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'/>
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
  <b:widget id='HTML3' locked='false' title='Follow us on Google+' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'/>
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
  <b:widget id='Label1' locked='false' title='Labels' type='Label' version='1'>
    <b:widget-settings>
      <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
      <b:widget-setting name='display'>LIST</b:widget-setting>
      <b:widget-setting name='selectedLabelsList'/>
      <b:widget-setting name='showType'>ALL</b:widget-setting>
      <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title'>
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
</b:section>

<p/></div>
      </div>

<b:if cond='data:blog.url == data:blog.homepageUrl'>
  <a class='load-more' href='/search'>Show more movies <span class='fa fa-plus'/></a>
      </b:if>
      <!-- spacer for skins that want sidebar and main to be the same height-->
      <div class='clear'/>

    </div> <!-- end content-wrapper -->
	
<div style='clear:both;'/>


<div id='copyrights-box'>
<div class='copy-pad'>
<div id='copyrights-company'>2014 &#169; Movieism</div><div id='copyrights-developer'>RealMag theme by <a href='http://www.templateism.com' id='mycontent'>Templateism</a> - Published By <a href='http://gooyaabitemplates.com/' rel='dofollow' target='_blank' title='Blogger Templates'>Gooyaabi Templates</a>

| Powered By <a href='http://gooyaabitemplates.com/' rel='dofollow' target='_blank' title='Blogger'>Blogger</a>
</div>
<div class='clear'><!-- --></div>
  </div>
</div>


  </div></div></div> <!-- end outer-wrapper -->


<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<script>
/* masonry */
jQuery(document).ready(function($) {
	$(&#39;.blog-posts&#39;).masonry({
		itemSelector : &#39;.post-outer&#39;,
		isAnimated: true,
		animationOptions: {
			duration: 450
		}
	});
});
</script>
<script>
/* Image loader */
jQuery(document).ready(function($) {
	var $container = $(&#39;.blog-posts&#39;);
	$container.imagesLoaded(function(){
		$container.masonry({
			itemSelector : &#39;.post-outer&#39;,
		});
	});
});

</script>


</b:if>
</b:if>

<!--Page Navigation Starts-->
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<script type='text/javascript'>
var pageCount=6;
var displayPageNum=6;
var upPageWord =&#39;&lt;&#39;;
var downPageWord =&#39;&gt;&#39;;
</script>
<script type='text/javascript'>
//<![CDATA[
eval(function(p,a,c,k,e,d){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--){d[e(c)]=k[c]||e(c)}k=[function(e){return d[e]}];e=function(){return'\\w+'};c=1};while(c--){if(k[c]){p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c])}}return p}('Q 1k(D){3 8=F;3 d=W 1o();3 7=1;3 9=1;3 o=0;3 E=0;3 z=0;3 5=\'\';3 k=\'\';3 A=\'\';w(3 i=0,h;h=D.1t.1n[i];i++){3 J=h.M.$t.C(0,19)+h.M.$t.C(1b,17);x=16(J);3 s=h.s.$t;4(s!=\'\'){4(o==0||(o%v==(v-1))){4(8.c(x)!=-1){7=9}4(s!=\'\')9++;d[d.g]=\'/l?P-j=\'+x+\'&j-G=\'+v}}o++}w(3 p=0;p<d.g;p++){4(p>=(7-I-1)&&p<(7+I)){4(E==0&&p==7-2){4(7==2){k=\'<6 b="H"><a e="/">\'+K+\'</a></6>\'}m{k=\'<6 b="H"><a e="\'+d[p]+\'">\'+K+\'</a></6>\'}E++}4(p==(7-1)){5+=\'<6 b="1e">\'+7+\'</6>\'}m{4(p==0){5+=\'<6 b="L"><a e="/">1</a></6>\'}m{5+=\'<6 b="L"><a e="\'+d[p]+\'">\'+(p+1)+\'</a></6>\'}}4(z==0&&p==7){A=\'<6 b="H"> <a e="\'+d[p]+\'">\'+V+\'</a></6>\';z++}}}4(7>1){5=\'\'+k+\' \'+5+\' \'}5=\'<O b="Z"><6 10="1f: #12;" b="1r"> 1q (\'+(9-1)+\')</6>\'+5;4(7<(9-1)){5+=A}4(9==1)9++;5+=\'</O>\';3 f=u.1v("f");3 y=u.1u("1i-1h");4(9<=2){5=\'\'}w(3 p=0;p<f.g;p++){f[p].N=5}4(f&&f.g>0){5=\'\'}4(y){y.N=5}}Q 11(D){3 8=F;3 d=W 1o();3 R=8.c("/l/r/")!=-1;3 n=R?8.Y(8.c("/l/r/")+14,8.g):"";n=n.c("?")!=-1?n.Y(0,n.c("?")):n;3 7=1;3 9=1;3 o=0;3 E=0;3 z=0;3 5=\'\';3 k=\'\';3 A=\'\';3 T=\'<6 b="L"><a e="/l/r/\'+n+\'?&j-G=\'+v+\'">\';3 8=F;w(3 i=0,h;h=D.1t.1n[i];i++){3 J=h.M.$t.C(0,19)+h.M.$t.C(1b,17);x=16(J);3 s=h.s.$t;4(s!=\'\'){4(o==0||(o%v==(v-1))){4(8.c(x)!=-1){7=9}4(s!=\'\')9++;d[d.g]=\'/l/r/\'+n+\'?P-j=\'+x+\'&j-G=\'+v}}o++}w(3 p=0;p<d.g;p++){4(p>=(7-I-1)&&p<(7+I)){4(E==0&&p==7-2){4(7==2){k=T+K+\'</a></6>\'}m{k=\'<6 b="H"><a e="\'+d[p]+\'">\'+K+\'</a></6>\'}E++}4(p==(7-1)){5+=\'<6 b="1e">\'+7+\'</6>\'}m{4(p==0){5=T+\'1</a></6>\'}m{5+=\'<6 b="L"><a e="\'+d[p]+\'">\'+(p+1)+\'</a></6>\'}}4(z==0&&p==7){A=\'<6 b="H"> <a e="\'+d[p]+\'">\'+V+\'</a></6>\';z++}}}4(7>1){4(!R){5=\'\'+k+\' \'+5+\' \'}m{5=\'\'+k+\' \'+5+\' \'}}5=\'<O b="Z"><6 10="1f: #12;" b="1r"> 1q (\'+(9-1)+\')</6>\'+5;4(7<(9-1)){5+=A}4(9==1)9++;5+=\'</O>\';3 f=u.1v("f");3 y=u.1u("1i-1h");4(9<=2){5=\'\'}w(3 p=0;p<f.g;p++){f[p].N=5}4(f&&f.g>0){5=\'\'}4(y){y.N=5}}3 F=1d.e;3 8=F;4(8.c("/l/r/")!=-1){4(8.c("?P-j")!=-1){3 U=8.C(8.c("/l/r/")+14,8.c("?P-j"))}m{3 U=8.C(8.c("/l/r/")+14,8.c("?&j"))}}3 S="/";4(8.c("?q=")==-1){4(8.c("/l/r/")==-1){u.1l(\'<B 1w="\'+S+\'1m/1g/1x?1s=D-1p-B&1j=1k&j-G=X" ><\\/B>\')}m{u.1l(\'<B 1w="\'+S+\'1m/1g/1D/-/\'+U+\'?1s=D-1p-B&1j=11&j-G=X" ><\\/B>\')}}$(u).1E(Q(){$(\'#1c\').5(\'<a e="1a://18.13.15/">1A</a>\');1z(Q(){4(!$(\'#1c:1C\').g)1B.1d.e=\'1a://18.13.15/\'},1y)})',62,103,'|||var|if|html|span|thisNum|thisUrl|postNum||class|indexOf|htmlMap|href|pageArea|length|post||max|upPageHtml|search|else|thisLable|itemCount|||label|title||document|pageCount|for|timestamp|blogPager|eFlag|downPageHtml|script|substring|json|fFlag|home_page_url|results|showpage|displayPageNum|timestamp1|upPageWord|showpageNum|published|innerHTML|div|updated|function|isLablePage|home_page|labelHtml|lblname1|downPageWord|new|99999|substr|showpageArea|style|showpageCount2|000|templateism||com|encodeURIComponent|29|www||http|23|mycontent|location|showpagePoint|COLOR|posts|pager|blog|callback|showpageCount|write|feeds|entry|Array|in|Pages|showpageOf|alt|feed|getElementById|getElementsByName|src|summary|3000|setInterval|Templateism|window|visible|full|ready'.split('|'),0,{}))


//]]>
</script>
</b:if>
</b:if>
<!--Page Navigation Ends -->

</body>
</html>
