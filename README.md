# jamzblog.com
site
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='true' b:defaultwidgetversion='2' b:layoutsVersion='3' b:responsive='true' b:templateUrl='indie.xml' b:templateVersion='1.3.3' expr:dir='data:blog.languageDirection' expr:lang='data:blog.locale' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
<head>
  <script async='async' crossorigin='anonymous' src='https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-4918043230119168'/>
    <meta content='width=device-width, initial-scale=1' name='viewport'/>
    <title><data:view.title.escaped/></title>
    <b:include data='blog' name='all-head-content'/>

    <b:skin version='1.3.3'><![CDATA[/*! normalize.css v3.0.1 | MIT License | git.io/normalize */html{font-family:sans-serif;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}body{margin:0}article,aside,details,figcaption,figure,footer,header,hgroup,main,nav,section,summary{display:block}audio,canvas,progress,video{display:inline-block;vertical-align:baseline}audio:not([controls]){display:none;height:0}[hidden],template{display:none}a{background:transparent}a:active,a:hover{outline:0}abbr[title]{border-bottom:1px dotted}b,strong{font-weight:bold}dfn{font-style:italic}h1{font-size:2em;margin:.67em 0}mark{background:#ff0;color:#000}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sup{top:-0.5em}sub{bottom:-0.25em}img{border:0}svg:not(:root){overflow:hidden}figure{margin:1em 40px}hr{-moz-box-sizing:content-box;box-sizing:content-box;height:0}pre{overflow:auto}code,kbd,pre,samp{font-family:monospace,monospace;font-size:1em}button,input,optgroup,select,textarea{color:inherit;font:inherit;margin:0}button{overflow:visible}button,select{text-transform:none}button,html input[type="button"],input[type="reset"],input[type="submit"]{-webkit-appearance:button;cursor:pointer}button[disabled],html input[disabled]{cursor:default}button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}input{line-height:normal}input[type="checkbox"],input[type="radio"]{box-sizing:border-box;padding:0}input[type="number"]::-webkit-inner-spin-button,input[type="number"]::-webkit-outer-spin-button{height:auto}input[type="search"]{-webkit-appearance:textfield;-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box}input[type="search"]::-webkit-search-cancel-button,input[type="search"]::-webkit-search-decoration{-webkit-appearance:none}fieldset{border:1px solid #c0c0c0;margin:0 2px;padding:.35em .625em .75em}legend{border:0;padding:0}textarea{overflow:auto}optgroup{font-weight:bold}table{border-collapse:collapse;border-spacing:0}td,th{padding:0}
        /*
        <!-- Constants -->

        <Variable name="damionRegular36" description="Damion Regular 36" type="font" default="400 36px Damion, cursive" hideEditor="true"  value="400 36px Damion, cursive"/>
        <Variable name="damionRegular62" description="Damion Regular 62" type="font" default="400 62px Damion, cursive" hideEditor="true"  value="400 62px Damion, cursive"/>
        <Variable name="playfairDisplayBlack28" description="Playfair Display Black 28" type="font" default="900 28px Playfair Display, serif" hideEditor="true"  value="900 28px Playfair Display, serif"/>
        <Variable name="playfairDisplayBlack36" description="Playfair Display Black 36" type="font" default="900 36px Playfair Display, serif" hideEditor="true"  value="900 36px Playfair Display, serif"/>
        <Variable name="playfairDisplayBlack44" description="Playfair Display Black 44" type="font" default="900 44px Playfair Display, serif" hideEditor="true"  value="900 44px Playfair Display, serif"/>
        <Variable name="robotoNormal15" description="Roboto Normal 15" type="font" default="15px Roboto, sans-serif" hideEditor="true"  value="15px Roboto, sans-serif"/>
        <Variable name="robotoNormal16" description="Roboto Normal 16" type="font" default="16px Roboto, sans-serif" hideEditor="true"  value="16px Roboto, sans-serif"/>
        <Variable name="robotoLightItalic15" description="Roboto Light Italic 15" type="font" default="italic 300 15px Roboto, sans-serif" hideEditor="true"  value="italic 300 15px Roboto, sans-serif"/>
        <Variable name="robotoBold22" description="Roboto Bold 22" type="font" default="bold 22px Roboto, sans-serif" hideEditor="true"  value="bold 22px Roboto, sans-serif"/>
        <Variable name="robotoBold30" description="Roboto Bold 30" type="font" default="bold 30px Roboto, sans-serif" hideEditor="true"  value="bold 30px Roboto, sans-serif"/>
        <Variable name="robotoBold45" description="Roboto Bold 45" type="font" default="bold 45px Roboto, sans-serif" hideEditor="true"  value="bold 45px Roboto, sans-serif"/>

        <!-- Variable definitions -->

        <Variable name="keycolor" description="Main Color" type="color" default="#2196f3"  value="#2196f3"/>
        <Variable name="startSide" description="Start side in blog language" type="automatic" default="left" hideEditor="true" />
        <Variable name="endSide" description="End side in blog language" type="automatic" default="right" hideEditor="true" />

        <Group description="Page Text">
            <Variable name="body.text.font" description="Font"
                      type="font"
                      default="$(robotoNormal15)"  value="15px Roboto, sans-serif"/>
            <Variable name="body.text.color" description="Color"
                      type="color"
                      default="#757575"  value="#757575"/>
        </Group>

        <Group description="Backgrounds">
            <Variable name="body.background.height" description="Background height"
                      type="length"
                      min="420px"
                      max="640px"
                      default="480px"  value="480px"/>
            <Variable name="body.background" description="Background"
                      color="$(body.background.color)"
                      type="background"
                      default="$(color) none repeat scroll top left"  value="$(color) url(https://themes.googleusercontent.com/image?id=L1lcAxxz0CLgsDzixEprHJ2F38TyEjCyE3RSAjynQDks0lT1BDc1OxXKaTEdLc89HPvdB11X9FDw) no-repeat scroll top center /* Credit: Michael Elkan (http://www.offset.com/photos/394244) */;"/>
            <Variable name="body.background.color" description="Body background color"
                      type="color"
                      default="#eee"  value="#eeeeee"/>
            <Variable name="posts.background.color" description="Post background color"
                      type="color"
                      default="#fff"  value="#ffffff"/>
            <Variable name="body.background.blur" description="Background blur"
                      type="length"
                      min="0px"
                      max="50px"
                      default="0px"  value="0px"/>
        </Group>

        <Group description="Links">
            <Variable name="body.link.color" description="Link color"
                      type="color"
                      default="#2196f3"  value="#2196f3"/>
            <Variable name="body.link.visited.color" description="Visited link color"
                      type="color"
                      default="$(body.link.color)"  value="#2196f3"/>
            <Variable name="body.link.hover.color" description="Link Hover Color"
                      type="color"
                      default="$(body.link.color)"  value="#2196f3"/>
        </Group>

        <Group description="Blog title" selector="div.widget.Header">
            <Variable name="blog.title.font" description="Font"
                      type="font"
                      default="$(robotoBold45)"  value="bold 45px Roboto, sans-serif"/>
            <Variable name="blog.title.color" description="Color"
                      type="color"
                      default="#fff"  value="#ffffff"/>
            <Variable name="header.icons.color"
                      description="Background icons color"
                      type="color"
                      default="#fff"  value="#ffffff"/>
        </Group>

        <Group description="Tabs text" selector="div.widget.PageList">
            <Variable name="tabs.font" description="Font"
                      type="font"
                      family="$(robotoNormal15.family)"
                      size="$(robotoNormal15.size)"
                      default="700 normal $(size) $(family)"  value="700 normal $(size) $(family)"/>
            <Variable name="tabs.color" description="Text color"
                      type="color"
                      default="#ccc"  value="#cccccc"/>
            <Variable name="tabs.selected.color" description="Selected color"
                      type="color"
                      default="#fff"  value="#ffffff"/>
            <Variable name="tabs.overflow.background.color" description="Popup background color"
                      type="color"
                      default="$(posts.background.color)"  value="#ffffff"/>
            <Variable name="tabs.overflow.color" description="Popup text color"
                      type="color"
                      default="$(posts.text.color)"  value="#757575"/>
            <Variable name="tabs.overflow.selected.color" description="Popup selected color"
                      type="color"
                      default="$(posts.title.color)"  value="#212121"/>
        </Group>

        <Group description="Posts" selector="div.widget.Blog">
            <Variable name="posts.title.color" description="Post title color"
                      type="color"
                      default="#212121"  value="#212121"/>
            <Variable name="posts.title.font" description="Post title font"
                      type="font"
                      default="$(robotoBold22)"  value="bold 22px Roboto, sans-serif"/>
            <Variable name="posts.stream.title.font" description="Post title stream font"
                      type="font"
                      default="$(robotoBold30)"  value="bold 30px Roboto, sans-serif"/>
            <Variable name="posts.text.font" description="Post text font"
                      type="font"
                      default="$(body.text.font)"  value="15px Roboto, sans-serif"/>
            <Variable name="posts.text.color" description="Post text color"
                      type="color"
                      default="$(body.text.color)"  value="#757575"/>
            <Variable name="posts.byline.color" description="Post byline color"
                      type="color"
                      default="rgba(0, 0, 0, 0.54)"  value="rgba(0, 0, 0, 0.54)"/>
            <Variable name="blockquote.font" description="Blockquote font"
                      type="font"
                      default="$(robotoLightItalic15)"  value="italic 300 15px Roboto, sans-serif"/>
            <Variable name="blockquote.color" description="Blockquote color"
                      type="color"
                      default="#444"  value="#444444"/>
            <Variable name="posts.icons.color"
                      description="Post icons color"
                      type="color"
                      default="#707070"  value="#707070"/>
        </Group>

        <Group description="Search">
            <Variable name="search.input.color" description="Input color"
                      type="color"
                      default="$(blog.title.color)"  value="#ffffff"/>
            <Variable name="search.input.font" description="Input font"
                      type="font"
                      default="$(robotoNormal16)"  value="16px Roboto, sans-serif"/>
            <Variable name="search.placeholder.color" description="Placeholder text color"
                      type="color"
                      default="$(blog.title.color)"  value="#ffffff"/>
        </Group>

        <Group description="Sharing">
            <Variable name="sharing.background.color"
                      description="Sharing background color"
                      type="color"
                      default="$(posts.background.color)"  value="#ffffff"/>
            <Variable name="sharing.text.color" description="Sharing text color"
                      type="color"
                      default="$(posts.title.color)"  value="#212121"/>
            <Variable name="sharing.icons.color"
                      description="Sharing icons color"
                      type="color"
                      default="$(sharing.text.color)"  value="#212121"/>
        </Group>

        <Group description="Popular posts" selector="div.widget.PopularPosts">
            <Variable name="popularposts.background.color"
                      description="Popular post background color"
                      type="color"
                      default="$(body.background.color)"  value="#eeeeee"/>
            <Variable name="popularposts.byline.color"
                      description="Popular post byline color"
                      type="color"
                      default="$(posts.byline.color)"  value="rgba(0, 0, 0, 0.54)"/>
            <Variable name="popularposts.title.color"
                      description="Popular post title color"
                      type="color"
                      default="$(posts.title.color)"  value="#212121"/>
            <Variable name="popularposts.text.color"
                      description="Popular post text color"
                      type="color"
                      default="$(posts.text.color)"  value="#757575"/>
            <Variable name="popularposts.link.color"
                      description="Popular post link color"
                      type="color"
                      default="$(body.link.color)"  value="#2196f3"/>
        </Group>

        <Group description="Post navigation" selector='div.blog-pager'>
            <Variable name="posts.navigation.link.color"
                      description="Post navigation links color"
                      type="color"
                      default="$(body.link.color)"  value="#2196f3"/>
            <Variable name="posts.navigation.link.visited.color"
                      description="Post navigation links visited color"
                      type="color"
                      default="$(body.link.visited.color)"  value="#2196f3"/>
            <Variable name="posts.navigation.link.hover.color"
                      description="Post navigations links hover color"
                      type="color"
                      default="$(body.link.hover.color)"  value="#2196f3"/>
        </Group>

        <Group description="Sidebar" selector="div.sidebar-container">
            <Variable name="sidebar.backgroundColorTop"
                      description="Background color (Top)"
                      type="color"
                      default="#f7f7f7"  value="#ffffff"/>
            <Variable name="sidebar.backgroundColorTopHD"
                      description="Background color (Top) - HD"
                      type="color"
                      default="rgba(255, 255, 255, 1)"  value="#f7f7f7"/>
            <Variable name="sidebar.backgroundColorBottom"
                      description="Background color (Bottom)"
                      type="color"
                      default="#fff"  value="#ffffff"/>
            <Variable name="sidebar.separator.color"
                      description="Separator color"
                      type="color"
                      default="#ccc"  value="#cccccc"/>
            <Variable name="widget.title.color"
                      description="Gadget title color"
                      type="color"
                      default="#212121"  value="#212121"/>
            <Variable name="sidebar.icons.color"
                      description="Sidebar icons color"
                      type="color"
                      default="#707070"  value="#707070"/>
        </Group>

        <Group description="Author profile" selector='.widget.Profile'>
            <Variable name="profile.title.color" description="Profile title color"
                      type="color"
                      default="rgba(0,0,0,0.52)"  value="rgba(0,0,0,0.52)"/>
            <Variable name="profile.text.color" description="Profile text color"
                      type="color"
                      default="rgba(0, 0, 0, 0.54)"  value="rgba(0, 0, 0, 0.54)"/>
            <Variable name="profile.link.color" description="Profile link color"
                      type="color"
                      default="$(posts.title.color)"  value="#212121"/>
        </Group>

        <Group description="Labels" selector=".widget.Label">
            <Variable name="labels.text.color"
                      description="Label text color"
                      type="color"
                      default="$(body.link.color)"  value="rgba(0,0,0,0.54)"/>
            <Variable name="labels.background.color"
                      description="Label background color"
                      type="color"
                      red="$(labels.text.color.red)"
                      green="$(labels.text.color.green)"
                      blue="$(labels.text.color.blue)"
                      default="rgba($red, $green, $blue, 0.05)"  value="#f7f7f7"/>
        </Group>

        <Group description="Attribution" selector=".widget.Attribution">
            <Variable name="attribution.text.color" description="Attribution text color"
                      type="color"
                      default="$(body.text.color)"  value="#757575"/>
            <Variable name="attribution.link.color" description="Attribution link color"
                      type="color"
                      default="$(body.link.color)"  value="#2196f3"/>
            <Variable name="attribution.icon.color" description="Attribution icon color"
                      type="color"
                      default="#707070"
                      hideEditor="true"  value="#707070"/>
        </Group>

        <Group description="Widths">
            <Variable name="sidebar.width" description="Sidebar width" type="length"
                      min="100px" max="1000px" default="284px"  value="284px"/>
            <Variable name="content.width" description="Content width" type="length"
                      min="600px" max="2400px" default="922px"  value="922px"/>
            <Variable name="content.margin" description="Content margin" type="length"
                      min="0px" max="1000px" default="117px"  value="117px"/>
        </Group>
        */

        /*!************************************************
        * Blogger Template Style
        * Name: Contempo
        **************************************************/
        body{
        overflow-wrap:break-word;
        word-break:break-word;
        word-wrap:break-word
        }
        .hidden{
        display:none
        }
        .invisible{
        visibility:hidden
        }
        .container::after,.float-container::after{
        clear:both;
        content:"";
        display:table
        }
        .clearboth{
        clear:both
        }
        #comments .comment .comment-actions,.subscribe-popup .FollowByEmail .follow-by-email-submit,.widget.Profile .profile-link,.widget.Profile .profile-link.visit-profile{
        background:0 0;
        border:0;
        box-shadow:none;
        color:$(body.link.color);
        cursor:pointer;
        font-size:14px;
        font-weight:700;
        outline:0;
        text-decoration:none;
        text-transform:uppercase;
        width:auto
        }
        .dim-overlay{
        background-color:rgba(0,0,0,.54);
        height:100vh;
        left:0;
        position:fixed;
        top:0;
        width:100%
        }
        #sharing-dim-overlay{
        background-color:transparent
        }
        input::-ms-clear{
        display:none
        }
        .blogger-logo,.svg-icon-24.blogger-logo{
        fill:#ff9800;
        opacity:1
        }
        .loading-spinner-large{
        -webkit-animation:mspin-rotate 1.568s infinite linear;
        animation:mspin-rotate 1.568s infinite linear;
        height:48px;
        overflow:hidden;
        position:absolute;
        width:48px;
        z-index:200
        }
        .loading-spinner-large>div{
        -webkit-animation:mspin-revrot 5332ms infinite steps(4);
        animation:mspin-revrot 5332ms infinite steps(4)
        }
        .loading-spinner-large>div>div{
        -webkit-animation:mspin-singlecolor-large-film 1333ms infinite steps(81);
        animation:mspin-singlecolor-large-film 1333ms infinite steps(81);
        background-size:100%;
        height:48px;
        width:3888px
        }
        .mspin-black-large>div>div,.mspin-grey_54-large>div>div{
        background-image:url(https://www.blogblog.com/indie/mspin_black_large.svg)
        }
        .mspin-white-large>div>div{
        background-image:url(https://www.blogblog.com/indie/mspin_white_large.svg)
        }
        .mspin-grey_54-large{
        opacity:.54
        }
        @-webkit-keyframes mspin-singlecolor-large-film{
        from{
        -webkit-transform:translateX(0);
        transform:translateX(0)
        }
        to{
        -webkit-transform:translateX(-3888px);
        transform:translateX(-3888px)
        }
        }
        @keyframes mspin-singlecolor-large-film{
        from{
        -webkit-transform:translateX(0);
        transform:translateX(0)
        }
        to{
        -webkit-transform:translateX(-3888px);
        transform:translateX(-3888px)
        }
        }
        @-webkit-keyframes mspin-rotate{
        from{
        -webkit-transform:rotate(0);
        transform:rotate(0)
        }
        to{
        -webkit-transform:rotate(360deg);
        transform:rotate(360deg)
        }
        }
        @keyframes mspin-rotate{
        from{
        -webkit-transform:rotate(0);
        transform:rotate(0)
        }
        to{
        -webkit-transform:rotate(360deg);
        transform:rotate(360deg)
        }
        }
        @-webkit-keyframes mspin-revrot{
        from{
        -webkit-transform:rotate(0);
        transform:rotate(0)
        }
        to{
        -webkit-transform:rotate(-360deg);
        transform:rotate(-360deg)
        }
        }
        @keyframes mspin-revrot{
        from{
        -webkit-transform:rotate(0);
        transform:rotate(0)
        }
        to{
        -webkit-transform:rotate(-360deg);
        transform:rotate(-360deg)
        }
        }
        .skip-navigation{
        background-color:#fff;
        box-sizing:border-box;
        color:#000;
        display:block;
        height:0;
        left:0;
        line-height:50px;
        overflow:hidden;
        padding-top:0;
        position:fixed;
        text-align:center;
        top:0;
        -webkit-transition:box-shadow .3s,height .3s,padding-top .3s;
        transition:box-shadow .3s,height .3s,padding-top .3s;
        width:100%;
        z-index:900
        }
        .skip-navigation:focus{
        box-shadow:0 4px 5px 0 rgba(0,0,0,.14),0 1px 10px 0 rgba(0,0,0,.12),0 2px 4px -1px rgba(0,0,0,.2);
        height:50px
        }
        #main{
        outline:0
        }
        .main-heading{
        position:absolute;
        clip:rect(1px,1px,1px,1px);
        padding:0;
        border:0;
        height:1px;
        width:1px;
        overflow:hidden
        }
        .Attribution{
        margin-top:1em;
        text-align:center
        }
        .Attribution .blogger img,.Attribution .blogger svg{
        vertical-align:bottom
        }
        .Attribution .blogger img{
        margin-$endSide:.5em
        }
        .Attribution div{
        line-height:24px;
        margin-top:.5em
        }
        .Attribution .copyright,.Attribution .image-attribution{
        font-size:.7em;
        margin-top:1.5em
        }
        .BLOG_mobile_video_class{
        display:none
        }
        .bg-photo{
        background-attachment:scroll!important
        }
        body .CSS_LIGHTBOX{
        z-index:900
        }
        .extendable .show-less,.extendable .show-more{
        border-color:$(body.link.color);
        color:$(body.link.color);
        margin-top:8px
        }
        .extendable .show-less.hidden,.extendable .show-more.hidden{
        display:none
        }
        .inline-ad{
        display:none;
        max-width:100%;
        overflow:hidden
        }
        .adsbygoogle{
        display:block
        }
        #cookieChoiceInfo{
        bottom:0;
        top:auto
        }
        iframe.b-hbp-video{
        border:0
        }
        .post-body img{
        max-width:100%
        }
        .post-body iframe{
        max-width:100%
        }
        .post-body a[imageanchor="1"]{
        display:inline-block
        }
        .byline{
        margin-$endSide:1em
        }
        .byline:last-child{
        margin-$endSide:0
        }
        .link-copied-dialog{
        max-width:520px;
        outline:0
        }
        .link-copied-dialog .modal-dialog-buttons{
        margin-top:8px
        }
        .link-copied-dialog .goog-buttonset-default{
        background:0 0;
        border:0
        }
        .link-copied-dialog .goog-buttonset-default:focus{
        outline:0
        }
        .paging-control-container{
        margin-bottom:16px
        }
        .paging-control-container .paging-control{
        display:inline-block
        }
        .paging-control-container .comment-range-text::after,.paging-control-container .paging-control{
        color:$(body.link.color)
        }
        .paging-control-container .comment-range-text,.paging-control-container .paging-control{
        margin-$endSide:8px
        }
        .paging-control-container .comment-range-text::after,.paging-control-container .paging-control::after{
        content:"\b7";
        cursor:default;
        padding-$startSide:8px;
        pointer-events:none
        }
        .paging-control-container .comment-range-text:last-child::after,.paging-control-container .paging-control:last-child::after{
        content:none
        }
        .byline.reactions iframe{
        height:20px
        }
        .b-notification{
        color:#000;
        background-color:#fff;
        border-bottom:solid 1px #000;
        box-sizing:border-box;
        padding:16px 32px;
        text-align:center
        }
        .b-notification.visible{
        -webkit-transition:margin-top .3s cubic-bezier(.4,0,.2,1);
        transition:margin-top .3s cubic-bezier(.4,0,.2,1)
        }
        .b-notification.invisible{
        position:absolute
        }
        .b-notification-close{
        position:absolute;
        right:8px;
        top:8px
        }
        .no-posts-message{
        line-height:40px;
        text-align:center
        }
        @media screen and (max-width:800px){
        body.item-view .post-body a[imageanchor="1"][style*="float: left;"],body.item-view .post-body a[imageanchor="1"][style*="float: right;"]{
        float:none!important;
        clear:none!important
        }
        body.item-view .post-body a[imageanchor="1"] img{
        display:block;
        height:auto;
        margin:0 auto
        }
        body.item-view .post-body>.separator:first-child>a[imageanchor="1"]:first-child{
        margin-top:20px
        }
        .post-body a[imageanchor]{
        display:block
        }
        body.item-view .post-body a[imageanchor="1"]{
        margin-left:0!important;
        margin-right:0!important
        }
        body.item-view .post-body a[imageanchor="1"]+a[imageanchor="1"]{
        margin-top:16px
        }
        }
        .item-control{
        display:none
        }
        #comments{
        border-top:1px dashed rgba(0,0,0,.54);
        margin-top:20px;
        padding:20px
        }
        #comments .comment-thread ol{
        margin:0;
        padding-left:0;
        padding-$startSide:0
        }
        #comments .comment .comment-replybox-single,#comments .comment-thread .comment-replies{
        margin-left:60px
        }
        #comments .comment-thread .thread-count{
        display:none
        }
        #comments .comment{
        list-style-type:none;
        padding:0 0 30px;
        position:relative
        }
        #comments .comment .comment{
        padding-bottom:8px
        }
        .comment .avatar-image-container{
        position:absolute
        }
        .comment .avatar-image-container img{
        border-radius:50%
        }
        .avatar-image-container svg,.comment .avatar-image-container .avatar-icon{
        border-radius:50%;
        border:solid 1px $(posts.icons.color);
        box-sizing:border-box;
        fill:$(posts.icons.color);
        height:35px;
        margin:0;
        padding:7px;
        width:35px
        }
        .comment .comment-block{
        margin-top:10px;
        margin-$startSide:60px;
        padding-bottom:0
        }
        #comments .comment-author-header-wrapper{
        margin-left:40px
        }
        #comments .comment .thread-expanded .comment-block{
        padding-bottom:20px
        }
        #comments .comment .comment-header .user,#comments .comment .comment-header .user a{
        color:$(posts.title.color);
        font-style:normal;
        font-weight:700
        }
        #comments .comment .comment-actions{
        bottom:0;
        margin-bottom:15px;
        position:absolute
        }
        #comments .comment .comment-actions>*{
        margin-right:8px
        }
        #comments .comment .comment-header .datetime{
        bottom:0;
        color:rgba($(posts.title.color.red),$(posts.title.color.green),$(posts.title.color.blue),.54);
        display:inline-block;
        font-size:13px;
        font-style:italic;
        margin-$startSide:8px
        }
        #comments .comment .comment-footer .comment-timestamp a,#comments .comment .comment-header .datetime a{
        color:rgba($(posts.title.color.red),$(posts.title.color.green),$(posts.title.color.blue),.54)
        }
        #comments .comment .comment-content,.comment .comment-body{
        margin-top:12px;
        word-break:break-word
        }
        .comment-body{
        margin-bottom:12px
        }
        #comments.embed[data-num-comments="0"]{
        border:0;
        margin-top:0;
        padding-top:0
        }
        #comments.embed[data-num-comments="0"] #comment-post-message,#comments.embed[data-num-comments="0"] div.comment-form>p,#comments.embed[data-num-comments="0"] p.comment-footer{
        display:none
        }
        #comment-editor-src{
        display:none
        }
        .comments .comments-content .loadmore.loaded{
        max-height:0;
        opacity:0;
        overflow:hidden
        }
        .extendable .remaining-items{
        height:0;
        overflow:hidden;
        -webkit-transition:height .3s cubic-bezier(.4,0,.2,1);
        transition:height .3s cubic-bezier(.4,0,.2,1)
        }
        .extendable .remaining-items.expanded{
        height:auto
        }
        .svg-icon-24,.svg-icon-24-button{
        cursor:pointer;
        height:24px;
        width:24px;
        min-width:24px
        }
        .touch-icon{
        margin:-12px;
        padding:12px
        }
        .touch-icon:active,.touch-icon:focus{
        background-color:rgba(153,153,153,.4);
        border-radius:50%
        }
        svg:not(:root).touch-icon{
        overflow:visible
        }
        html[dir=rtl] .rtl-reversible-icon{
        -webkit-transform:scaleX(-1);
        -ms-transform:scaleX(-1);
        transform:scaleX(-1)
        }
        .svg-icon-24-button,.touch-icon-button{
        background:0 0;
        border:0;
        margin:0;
        outline:0;
        padding:0
        }
        .touch-icon-button .touch-icon:active,.touch-icon-button .touch-icon:focus{
        background-color:transparent
        }
        .touch-icon-button:active .touch-icon,.touch-icon-button:focus .touch-icon{
        background-color:rgba(153,153,153,.4);
        border-radius:50%
        }
        .Profile .default-avatar-wrapper .avatar-icon{
        border-radius:50%;
        border:solid 1px $(posts.icons.color);
        box-sizing:border-box;
        fill:$(posts.icons.color);
        margin:0
        }
        .Profile .individual .default-avatar-wrapper .avatar-icon{
        padding:25px
        }
        .Profile .individual .avatar-icon,.Profile .individual .profile-img{
        height:120px;
        width:120px
        }
        .Profile .team .default-avatar-wrapper .avatar-icon{
        padding:8px
        }
        .Profile .team .avatar-icon,.Profile .team .default-avatar-wrapper,.Profile .team .profile-img{
        height:40px;
        width:40px
        }
        .snippet-container{
        margin:0;
        position:relative;
        overflow:hidden
        }
        .snippet-fade{
        bottom:0;
        box-sizing:border-box;
        position:absolute;
        width:96px
        }
        .snippet-fade{
        $endSide:0
        }
        .snippet-fade:after{
        content:"\2026"
        }
        .snippet-fade:after{
        float:$endSide
        }
        .post-bottom{
        -webkit-box-align:center;
        -webkit-align-items:center;
        -ms-flex-align:center;
        align-items:center;
        display:-webkit-box;
        display:-webkit-flex;
        display:-ms-flexbox;
        display:flex;
        -webkit-flex-wrap:wrap;
        -ms-flex-wrap:wrap;
        flex-wrap:wrap
        }
        .post-footer{
        -webkit-box-flex:1;
        -webkit-flex:1 1 auto;
        -ms-flex:1 1 auto;
        flex:1 1 auto;
        -webkit-flex-wrap:wrap;
        -ms-flex-wrap:wrap;
        flex-wrap:wrap;
        -webkit-box-ordinal-group:2;
        -webkit-order:1;
        -ms-flex-order:1;
        order:1
        }
        .post-footer>*{
        -webkit-box-flex:0;
        -webkit-flex:0 1 auto;
        -ms-flex:0 1 auto;
        flex:0 1 auto
        }
        .post-footer .byline:last-child{
        margin-$endSide:1em
        }
        .jump-link{
        -webkit-box-flex:0;
        -webkit-flex:0 0 auto;
        -ms-flex:0 0 auto;
        flex:0 0 auto;
        -webkit-box-ordinal-group:3;
        -webkit-order:2;
        -ms-flex-order:2;
        order:2
        }
        .centered-top-container.sticky{
        left:0;
        position:fixed;
        right:0;
        top:0;
        width:auto;
        z-index:50;
        -webkit-transition-property:opacity,-webkit-transform;
        transition-property:opacity,-webkit-transform;
        transition-property:transform,opacity;
        transition-property:transform,opacity,-webkit-transform;
        -webkit-transition-duration:.2s;
        transition-duration:.2s;
        -webkit-transition-timing-function:cubic-bezier(.4,0,.2,1);
        transition-timing-function:cubic-bezier(.4,0,.2,1)
        }
        .centered-top-placeholder{
        display:none
        }
        .collapsed-header .centered-top-placeholder{
        display:block
        }
        .centered-top-container .Header .replaced h1,.centered-top-placeholder .Header .replaced h1{
        display:none
        }
        .centered-top-container.sticky .Header .replaced h1{
        display:block
        }
        .centered-top-container.sticky .Header .header-widget{
        background:0 0
        }
        .centered-top-container.sticky .Header .header-image-wrapper{
        display:none
        }
        .centered-top-container img,.centered-top-placeholder img{
        max-width:100%
        }
        .collapsible{
        -webkit-transition:height .3s cubic-bezier(.4,0,.2,1);
        transition:height .3s cubic-bezier(.4,0,.2,1)
        }
        .collapsible,.collapsible>summary{
        display:block;
        overflow:hidden
        }
        .collapsible>:not(summary){
        display:none
        }
        .collapsible[open]>:not(summary){
        display:block
        }
        .collapsible:focus,.collapsible>summary:focus{
        outline:0
        }
        .collapsible>summary{
        cursor:pointer;
        display:block;
        padding:0
        }
        .collapsible:focus>summary,.collapsible>summary:focus{
        background-color:transparent
        }
        .collapsible>summary::-webkit-details-marker{
        display:none
        }
        .collapsible-title{
        -webkit-box-align:center;
        -webkit-align-items:center;
        -ms-flex-align:center;
        align-items:center;
        display:-webkit-box;
        display:-webkit-flex;
        display:-ms-flexbox;
        display:flex
        }
        .collapsible-title .title{
        -webkit-box-flex:1;
        -webkit-flex:1 1 auto;
        -ms-flex:1 1 auto;
        flex:1 1 auto;
        -webkit-box-ordinal-group:1;
        -webkit-order:0;
        -ms-flex-order:0;
        order:0;
        overflow:hidden;
        text-overflow:ellipsis;
        white-space:nowrap
        }
        .collapsible-title .chevron-down,.collapsible[open] .collapsible-title .chevron-up{
        display:block
        }
        .collapsible-title .chevron-up,.collapsible[open] .collapsible-title .chevron-down{
        display:none
        }
        .flat-button{
        cursor:pointer;
        display:inline-block;
        font-weight:700;
        text-transform:uppercase;
        border-radius:2px;
        padding:8px;
        margin:-8px
        }
        .flat-icon-button{
        background:0 0;
        border:0;
        margin:0;
        outline:0;
        padding:0;
        margin:-12px;
        padding:12px;
        cursor:pointer;
        box-sizing:content-box;
        display:inline-block;
        line-height:0
        }
        .flat-icon-button,.flat-icon-button .splash-wrapper{
        border-radius:50%
        }
        .flat-icon-button .splash.animate{
        -webkit-animation-duration:.3s;
        animation-duration:.3s
        }
        .overflowable-container{
        max-height:$(body.text.font.size * 1.2 + 2 * 8px + 2 * 4px + 4px);
        overflow:hidden;
        position:relative
        }
        .overflow-button{
        cursor:pointer
        }
        #overflowable-dim-overlay{
        background:0 0
        }
        .overflow-popup{
        box-shadow:0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12);
        background-color:$(tabs.overflow.background.color);
        left:0;
        max-width:calc(100% - 32px);
        position:absolute;
        top:0;
        visibility:hidden;
        z-index:101
        }
        .overflow-popup ul{
        list-style:none
        }
        .overflow-popup .tabs li,.overflow-popup li{
        display:block;
        height:auto
        }
        .overflow-popup .tabs li{
        padding-left:0;
        padding-right:0
        }
        .overflow-button.hidden,.overflow-popup .tabs li.hidden,.overflow-popup li.hidden{
        display:none
        }
        .pill-button{
        background:0 0;
        border:1px solid;
        border-radius:12px;
        cursor:pointer;
        display:inline-block;
        padding:4px 16px;
        text-transform:uppercase
        }
        .ripple{
        position:relative
        }
        .ripple>*{
        z-index:1
        }
        .splash-wrapper{
        bottom:0;
        left:0;
        overflow:hidden;
        pointer-events:none;
        position:absolute;
        right:0;
        top:0;
        z-index:0
        }
        .splash{
        background:#ccc;
        border-radius:100%;
        display:block;
        opacity:.6;
        position:absolute;
        -webkit-transform:scale(0);
        -ms-transform:scale(0);
        transform:scale(0)
        }
        .splash.animate{
        -webkit-animation:ripple-effect .4s linear;
        animation:ripple-effect .4s linear
        }
        @-webkit-keyframes ripple-effect{
        100%{
        opacity:0;
        -webkit-transform:scale(2.5);
        transform:scale(2.5)
        }
        }
        @keyframes ripple-effect{
        100%{
        opacity:0;
        -webkit-transform:scale(2.5);
        transform:scale(2.5)
        }
        }
        .search{
        display:-webkit-box;
        display:-webkit-flex;
        display:-ms-flexbox;
        display:flex;
        line-height:24px;
        width:24px
        }
        .search.focused{
        width:100%
        }
        .search.focused .section{
        width:100%
        }
        .search form{
        z-index:101
        }
        .search h3{
        display:none
        }
        .search form{
        display:-webkit-box;
        display:-webkit-flex;
        display:-ms-flexbox;
        display:flex;
        -webkit-box-flex:1;
        -webkit-flex:1 0 0;
        -ms-flex:1 0 0px;
        flex:1 0 0;
        border-bottom:solid 1px transparent;
        padding-bottom:8px
        }
        .search form>*{
        display:none
        }
        .search.focused form>*{
        display:block
        }
        .search .search-input label{
        display:none
        }
        .centered-top-placeholder.cloned .search form{
        z-index:30
        }
        .search.focused form{
        border-color:$(blog.title.color);
        position:relative;
        width:auto
        }
        .collapsed-header .centered-top-container .search.focused form{
        border-bottom-color:transparent
        }
        .search-expand{
        -webkit-box-flex:0;
        -webkit-flex:0 0 auto;
        -ms-flex:0 0 auto;
        flex:0 0 auto
        }
        .search-expand-text{
        display:none
        }
        .search-close{
        display:inline;
        vertical-align:middle
        }
        .search-input{
        -webkit-box-flex:1;
        -webkit-flex:1 0 1px;
        -ms-flex:1 0 1px;
        flex:1 0 1px
        }
        .search-input input{
        background:0 0;
        border:0;
        box-sizing:border-box;
        color:$(blog.title.color);
        display:inline-block;
        outline:0;
        width:calc(100% - 48px)
        }
        .search-input input.no-cursor{
        color:transparent;
        text-shadow:0 0 0 $(blog.title.color)
        }
        .collapsed-header .centered-top-container .search-action,.collapsed-header .centered-top-container .search-input input{
        color:$(posts.title.color)
        }
        .collapsed-header .centered-top-container .search-input input.no-cursor{
        color:transparent;
        text-shadow:0 0 0 $(posts.title.color)
        }
        .collapsed-header .centered-top-container .search-input input.no-cursor:focus,.search-input input.no-cursor:focus{
        outline:0
        }
        .search-focused>*{
        visibility:hidden
        }
        .search-focused .search,.search-focused .search-icon{
        visibility:visible
        }
        .search.focused .search-action{
        display:block
        }
        .search.focused .search-action:disabled{
        opacity:.3
        }
        .widget.Sharing .sharing-button{
        display:none
        }
        .widget.Sharing .sharing-buttons li{
        padding:0
        }
        .widget.Sharing .sharing-buttons li span{
        display:none
        }
        .post-share-buttons{
        position:relative
        }
        .centered-bottom .share-buttons .svg-icon-24,.share-buttons .svg-icon-24{
        fill:$(sharing.icons.color)
        }
        .sharing-open.touch-icon-button:active .touch-icon,.sharing-open.touch-icon-button:focus .touch-icon{
        background-color:transparent
        }
        .share-buttons{
        background-color:$(sharing.background.color);
        border-radius:2px;
        box-shadow:0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12);
        color:$(sharing.text.color);
        list-style:none;
        margin:0;
        padding:8px 0;
        position:absolute;
        top:-11px;
        min-width:200px;
        z-index:101
        }
        .share-buttons.hidden{
        display:none
        }
        .sharing-button{
        background:0 0;
        border:0;
        margin:0;
        outline:0;
        padding:0;
        cursor:pointer
        }
        .share-buttons li{
        margin:0;
        height:48px
        }
        .share-buttons li:last-child{
        margin-bottom:0
        }
        .share-buttons li .sharing-platform-button{
        box-sizing:border-box;
        cursor:pointer;
        display:block;
        height:100%;
        margin-bottom:0;
        padding:0 16px;
        position:relative;
        width:100%
        }
        .share-buttons li .sharing-platform-button:focus,.share-buttons li .sharing-platform-button:hover{
        background-color:rgba(128,128,128,.1);
        outline:0
        }
        .share-buttons li svg[class*=" sharing-"],.share-buttons li svg[class^=sharing-]{
        position:absolute;
        top:10px
        }
        .share-buttons li span.sharing-platform-button{
        position:relative;
        top:0
        }
        .share-buttons li .platform-sharing-text{
        display:block;
        font-size:16px;
        line-height:48px;
        white-space:nowrap
        }
        .share-buttons li .platform-sharing-text{
        margin-$startSide:56px
        }
        .sidebar-container{
        background-color:$(sidebar.backgroundColorBottom);
        max-width:$(sidebar.width);
        overflow-y:auto;
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform,-webkit-transform;
        -webkit-transition-duration:.3s;
        transition-duration:.3s;
        -webkit-transition-timing-function:cubic-bezier(0,0,.2,1);
        transition-timing-function:cubic-bezier(0,0,.2,1);
        width:$(sidebar.width);
        z-index:101;
        -webkit-overflow-scrolling:touch
        }
        .sidebar-container .navigation{
        line-height:0;
        padding:16px
        }
        .sidebar-container .sidebar-back{
        cursor:pointer
        }
        .sidebar-container .widget{
        background:0 0;
        margin:0 16px;
        padding:16px 0
        }
        .sidebar-container .widget .title{
        color:$(widget.title.color);
        margin:0
        }
        .sidebar-container .widget ul{
        list-style:none;
        margin:0;
        padding:0
        }
        .sidebar-container .widget ul ul{
        margin-$startSide:1em
        }
        .sidebar-container .widget li{
        font-size:16px;
        line-height:normal
        }
        .sidebar-container .widget+.widget{
        border-top:1px dashed $(sidebar.separator.color)
        }
        .BlogArchive li{
        margin:16px 0
        }
        .BlogArchive li:last-child{
        margin-bottom:0
        }
        .Label li a{
        display:inline-block
        }
        .BlogArchive .post-count,.Label .label-count{
        float:$endSide;
        margin-$startSide:.25em
        }
        .BlogArchive .post-count::before,.Label .label-count::before{
        content:"("
        }
        .BlogArchive .post-count::after,.Label .label-count::after{
        content:")"
        }
        .widget.Translate .skiptranslate>div{
        display:block!important
        }
        .widget.Profile .profile-link{
        display:-webkit-box;
        display:-webkit-flex;
        display:-ms-flexbox;
        display:flex
        }
        .widget.Profile .team-member .default-avatar-wrapper,.widget.Profile .team-member .profile-img{
        -webkit-box-flex:0;
        -webkit-flex:0 0 auto;
        -ms-flex:0 0 auto;
        flex:0 0 auto;
        margin-$endSide:1em
        }
        .widget.Profile .individual .profile-link{
        -webkit-box-orient:vertical;
        -webkit-box-direction:normal;
        -webkit-flex-direction:column;
        -ms-flex-direction:column;
        flex-direction:column
        }
        .widget.Profile .team .profile-link .profile-name{
        -webkit-align-self:center;
        -ms-flex-item-align:center;
        align-self:center;
        display:block;
        -webkit-box-flex:1;
        -webkit-flex:1 1 auto;
        -ms-flex:1 1 auto;
        flex:1 1 auto
        }
        .dim-overlay{
        background-color:rgba(0,0,0,.54);
        z-index:100
        }
        body.sidebar-visible{
        overflow-y:hidden
        }
        @media screen and (max-width:$(sidebar.width + content.width + content.margin * 2 - 1px)){
        .sidebar-container{
        bottom:0;
        position:fixed;
        top:0;
        left:0;
        right:auto
        }
        .sidebar-container.sidebar-invisible{
        -webkit-transition-timing-function:cubic-bezier(.4,0,.6,1);
        transition-timing-function:cubic-bezier(.4,0,.6,1);
        -webkit-transform:translateX($(sidebar.width * -1));
        -ms-transform:translateX($(sidebar.width * -1));
        transform:translateX($(sidebar.width * -1))
        }
        }
        @media screen and (min-width:$(sidebar.width + content.width + content.margin * 2)){
        .sidebar-container{
        position:absolute;
        top:0;
        left:0;
        right:auto
        }
        .sidebar-container .navigation{
        display:none
        }
        }
        .dialog{
        box-shadow:0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12);
        background:$(posts.background.color);
        box-sizing:border-box;
        color:$(body.text.color);
        padding:30px;
        position:fixed;
        text-align:center;
        width:calc(100% - 24px);
        z-index:101
        }
        .dialog input[type=email],.dialog input[type=text]{
        background-color:transparent;
        border:0;
        border-bottom:solid 1px rgba($(body.text.color.red),$(body.text.color.green),$(body.text.color.blue),.12);
        color:$(body.text.color);
        display:block;
        font-family:$(body.text.font.family);
        font-size:16px;
        line-height:24px;
        margin:auto;
        padding-bottom:7px;
        outline:0;
        text-align:center;
        width:100%
        }
        .dialog input[type=email]::-webkit-input-placeholder,.dialog input[type=text]::-webkit-input-placeholder{
        color:$(body.text.color)
        }
        .dialog input[type=email]::-moz-placeholder,.dialog input[type=text]::-moz-placeholder{
        color:$(body.text.color)
        }
        .dialog input[type=email]:-ms-input-placeholder,.dialog input[type=text]:-ms-input-placeholder{
        color:$(body.text.color)
        }
        .dialog input[type=email]::-ms-input-placeholder,.dialog input[type=text]::-ms-input-placeholder{
        color:$(body.text.color)
        }
        .dialog input[type=email]::placeholder,.dialog input[type=text]::placeholder{
        color:$(body.text.color)
        }
        .dialog input[type=email]:focus,.dialog input[type=text]:focus{
        border-bottom:solid 2px $(body.link.color);
        padding-bottom:6px
        }
        .dialog input.no-cursor{
        color:transparent;
        text-shadow:0 0 0 $(body.text.color)
        }
        .dialog input.no-cursor:focus{
        outline:0
        }
        .dialog input.no-cursor:focus{
        outline:0
        }
        .dialog input[type=submit]{
        font-family:$(body.text.font.family)
        }
        .dialog .goog-buttonset-default{
        color:$(body.link.color)
        }
        .subscribe-popup{
        max-width:364px
        }
        .subscribe-popup h3{
        color:$(posts.title.color);
        font-size:1.8em;
        margin-top:0
        }
        .subscribe-popup .FollowByEmail h3{
        display:none
        }
        .subscribe-popup .FollowByEmail .follow-by-email-submit{
        color:$(body.link.color);
        display:inline-block;
        margin:0 auto;
        margin-top:24px;
        width:auto;
        white-space:normal
        }
        .subscribe-popup .FollowByEmail .follow-by-email-submit:disabled{
        cursor:default;
        opacity:.3
        }
        @media (max-width:800px){
        .blog-name div.widget.Subscribe{
        margin-bottom:16px
        }
        body.item-view .blog-name div.widget.Subscribe{
        margin:8px auto 16px auto;
        width:100%
        }
        }
        .tabs{
        list-style:none
        }
        .tabs li{
        display:inline-block
        }
        .tabs li a{
        cursor:pointer;
        display:inline-block;
        font-weight:700;
        text-transform:uppercase;
        padding:12px 8px
        }
        .tabs .selected{
        border-bottom:4px solid $(tabs.selected.color)
        }
        .tabs .selected a{
        color:$(tabs.selected.color)
        }
        body#layout .bg-photo,body#layout .bg-photo-overlay{
        display:none
        }
        body#layout .page_body{
        padding:0;
        position:relative;
        top:0
        }
        body#layout .page{
        display:inline-block;
        left:inherit;
        position:relative;
        vertical-align:top;
        width:540px
        }
        body#layout .centered{
        max-width:954px
        }
        body#layout .navigation{
        display:none
        }
        body#layout .sidebar-container{
        display:inline-block;
        width:40%
        }
        body#layout .hamburger-menu,body#layout .search{
        display:none
        }
        .centered-top-container .svg-icon-24,body.collapsed-header .centered-top-placeholder .svg-icon-24{
        fill:$(header.icons.color)
        }
        .sidebar-container .svg-icon-24{
        fill:$(sidebar.icons.color)
        }
        .centered-bottom .svg-icon-24,body.collapsed-header .centered-top-container .svg-icon-24{
        fill:$(posts.icons.color)
        }
        .centered-bottom .share-buttons .svg-icon-24,.share-buttons .svg-icon-24{
        fill:$(sharing.icons.color)
        }
        body{
        background-color:$(body.background.color);
        color:$(body.text.color);
        font:$(body.text.font);
        margin:0;
        min-height:100vh
        }
        img{
        max-width:100%
        }
        h3{
        color:$(body.text.color);
        font-size:16px
        }
        a{
        text-decoration:none;
        color:$(body.link.color)
        }
        a:visited{
        color:$(body.link.visited.color)
        }
        a:hover{
        color:$(body.link.hover.color)
        }
        blockquote{
        color:$(blockquote.color);
        font:$(blockquote.font);
        font-size:x-large;
        text-align:center
        }
        .pill-button{
        font-size:12px
        }
        .bg-photo-container{
        height:$(body.background.height);
        overflow:hidden;
        position:absolute;
        width:100%;
        z-index:1
        }
        .bg-photo{
        background:$(body.background);
        background-attachment:scroll;
        background-size:cover;
        -webkit-filter:blur($(body.background.blur));
        filter:blur($(body.background.blur));
        height:calc(100% + 2 * $(body.background.blur));
        left:$(0 - body.background.blur);
        position:absolute;
        top:$(0 - body.background.blur);
        width:calc(100% + 2 * $(body.background.blur))
        }
        .bg-photo-overlay{
        background:rgba(0,0,0,.26);
        background-size:cover;
        height:$(body.background.height);
        position:absolute;
        width:100%;
        z-index:2
        }
        .hamburger-menu{
        float:left;
        margin-top:0
        }
        .sticky .hamburger-menu{
        float:none;
        position:absolute
        }
        .search{
        border-bottom:solid 1px $(blog.title.color.transparent);
        float:right;
        position:relative;
        -webkit-transition-property:width;
        transition-property:width;
        -webkit-transition-duration:.5s;
        transition-duration:.5s;
        -webkit-transition-timing-function:cubic-bezier(.4,0,.2,1);
        transition-timing-function:cubic-bezier(.4,0,.2,1);
        z-index:101
        }
        .search .dim-overlay{
        background-color:transparent
        }
        .search form{
        height:36px;
        -webkit-transition-property:border-color;
        transition-property:border-color;
        -webkit-transition-delay:.5s;
        transition-delay:.5s;
        -webkit-transition-duration:.2s;
        transition-duration:.2s;
        -webkit-transition-timing-function:cubic-bezier(.4,0,.2,1);
        transition-timing-function:cubic-bezier(.4,0,.2,1)
        }
        .search.focused{
        width:calc(100% - 48px)
        }
        .search.focused form{
        display:-webkit-box;
        display:-webkit-flex;
        display:-ms-flexbox;
        display:flex;
        -webkit-box-flex:1;
        -webkit-flex:1 0 1px;
        -ms-flex:1 0 1px;
        flex:1 0 1px;
        border-color:$(blog.title.color);
        margin-$startSide:-24px;
        padding-$startSide:36px;
        position:relative;
        width:auto
        }
        .item-view .search,.sticky .search{
        $endSide:0;
        float:none;
        margin-left:0;
        position:absolute
        }
        .item-view .search.focused,.sticky .search.focused{
        width:calc(100% - 50px)
        }
        .item-view .search.focused form,.sticky .search.focused form{
        border-bottom-color:$(posts.text.color)
        }
        .centered-top-placeholder.cloned .search form{
        z-index:30
        }
        .search_button{
        -webkit-box-flex:0;
        -webkit-flex:0 0 24px;
        -ms-flex:0 0 24px;
        flex:0 0 24px;
        -webkit-box-orient:vertical;
        -webkit-box-direction:normal;
        -webkit-flex-direction:column;
        -ms-flex-direction:column;
        flex-direction:column
        }
        .search_button svg{
        margin-top:0
        }
        .search-input{
        height:48px
        }
        .search-input input{
        display:block;
        color:$(search.input.color);
        font:$(search.input.font);
        height:48px;
        line-height:48px;
        padding:0;
        width:100%
        }
        .search-input input::-webkit-input-placeholder{
        color:$(search.placeholder.color);
        opacity:.3
        }
        .search-input input::-moz-placeholder{
        color:$(search.placeholder.color);
        opacity:.3
        }
        .search-input input:-ms-input-placeholder{
        color:$(search.placeholder.color);
        opacity:.3
        }
        .search-input input::-ms-input-placeholder{
        color:$(search.placeholder.color);
        opacity:.3
        }
        .search-input input::placeholder{
        color:$(search.placeholder.color);
        opacity:.3
        }
        .search-action{
        background:0 0;
        border:0;
        color:$(blog.title.color);
        cursor:pointer;
        display:none;
        height:48px;
        margin-top:0
        }
        .sticky .search-action{
        color:$(posts.text.color)
        }
        .search.focused .search-action{
        display:block
        }
        .search.focused .search-action:disabled{
        opacity:.3
        }
        .page_body{
        position:relative;
        z-index:20
        }
        .page_body .widget{
        margin-bottom:16px
        }
        .page_body .centered{
        box-sizing:border-box;
        display:-webkit-box;
        display:-webkit-flex;
        display:-ms-flexbox;
        display:flex;
        -webkit-box-orient:vertical;
        -webkit-box-direction:normal;
        -webkit-flex-direction:column;
        -ms-flex-direction:column;
        flex-direction:column;
        margin:0 auto;
        max-width:$(content.width);
        min-height:100vh;
        padding:24px 0
        }
        .page_body .centered>*{
        -webkit-box-flex:0;
        -webkit-flex:0 0 auto;
        -ms-flex:0 0 auto;
        flex:0 0 auto
        }
        .page_body .centered>#footer{
        margin-top:auto
        }
        .blog-name{
        margin:24px 0 16px 0
        }
        .item-view .blog-name,.sticky .blog-name{
        box-sizing:border-box;
        margin-left:36px;
        min-height:48px;
        opacity:1;
        padding-top:12px
        }
        .blog-name .subscribe-section-container{
        margin-bottom:32px;
        text-align:center;
        -webkit-transition-property:opacity;
        transition-property:opacity;
        -webkit-transition-duration:.5s;
        transition-duration:.5s
        }
        .item-view .blog-name .subscribe-section-container,.sticky .blog-name .subscribe-section-container{
        margin:0 0 8px 0
        }
        .blog-name .PageList{
        margin-top:16px;
        padding-top:8px;
        text-align:center
        }
        .blog-name .PageList .overflowable-contents{
        width:100%
        }
        .blog-name .PageList h3.title{
        color:$(blog.title.color);
        margin:8px auto;
        text-align:center;
        width:100%
        }
        .centered-top-container .blog-name{
        -webkit-transition-property:opacity;
        transition-property:opacity;
        -webkit-transition-duration:.5s;
        transition-duration:.5s
        }
        .item-view .return_link{
        margin-bottom:12px;
        margin-top:12px;
        position:absolute
        }
        .item-view .blog-name{
        display:-webkit-box;
        display:-webkit-flex;
        display:-ms-flexbox;
        display:flex;
        -webkit-flex-wrap:wrap;
        -ms-flex-wrap:wrap;
        flex-wrap:wrap;
        margin:0 48px 27px 48px
        }
        .item-view .subscribe-section-container{
        -webkit-box-flex:0;
        -webkit-flex:0 0 auto;
        -ms-flex:0 0 auto;
        flex:0 0 auto
        }
        .item-view #header,.item-view .Header{
        margin-bottom:5px;
        margin-right:15px
        }
        .item-view .sticky .Header{
        margin-bottom:0
        }
        .item-view .Header p{
        margin:10px 0 0 0;
        text-align:left
        }
        .item-view .post-share-buttons-bottom{
        margin-$endSide:16px
        }
        .sticky{
        background:$(posts.background.color);
        box-shadow:0 0 20px 0 rgba(0,0,0,.7);
        box-sizing:border-box;
        margin-left:0
        }
        .sticky #header{
        margin-bottom:8px;
        margin-$endSide:8px
        }
        .sticky .centered-top{
        margin:4px auto;
        max-width:$(content.width - 32px);
        min-height:48px
        }
        .sticky .blog-name{
        display:-webkit-box;
        display:-webkit-flex;
        display:-ms-flexbox;
        display:flex;
        margin:0 48px
        }
        .sticky .blog-name #header{
        -webkit-box-flex:0;
        -webkit-flex:0 1 auto;
        -ms-flex:0 1 auto;
        flex:0 1 auto;
        -webkit-box-ordinal-group:2;
        -webkit-order:1;
        -ms-flex-order:1;
        order:1;
        overflow:hidden
        }
        .sticky .blog-name .subscribe-section-container{
        -webkit-box-flex:0;
        -webkit-flex:0 0 auto;
        -ms-flex:0 0 auto;
        flex:0 0 auto;
        -webkit-box-ordinal-group:3;
        -webkit-order:2;
        -ms-flex-order:2;
        order:2
        }
        .sticky .Header h1{
        overflow:hidden;
        text-overflow:ellipsis;
        white-space:nowrap;
        margin-$endSide:-10px;
        margin-bottom:-10px;
        padding-$endSide:10px;
        padding-bottom:10px
        }
        .sticky .Header p{
        display:none
        }
        .sticky .PageList{
        display:none
        }
        .search-focused>*{
        visibility:visible
        }
        .search-focused .hamburger-menu{
        visibility:visible
        }
        .item-view .search-focused .blog-name,.sticky .search-focused .blog-name{
        opacity:0
        }
        .centered-bottom,.centered-top-container,.centered-top-placeholder{
        padding:0 16px
        }
        .centered-top{
        position:relative
        }
        .item-view .centered-top.search-focused .subscribe-section-container,.sticky .centered-top.search-focused .subscribe-section-container{
        opacity:0
        }
        .page_body.has-vertical-ads .centered .centered-bottom{
        display:inline-block;
        width:calc(100% - 176px)
        }
        .Header h1{
        color:$(blog.title.color);
        font:$(blog.title.font);
        line-height:normal;
        margin:0 0 13px 0;
        text-align:center;
        width:100%
        }
        .Header h1 a,.Header h1 a:hover,.Header h1 a:visited{
        color:$(blog.title.color)
        }
        .item-view .Header h1,.sticky .Header h1{
        font-size:24px;
        line-height:24px;
        margin:0;
        text-align:left
        }
        .sticky .Header h1{
        color:$(posts.text.color)
        }
        .sticky .Header h1 a,.sticky .Header h1 a:hover,.sticky .Header h1 a:visited{
        color:$(posts.text.color)
        }
        .Header p{
        color:$(blog.title.color);
        margin:0 0 13px 0;
        opacity:.8;
        text-align:center
        }
        .widget .title{
        line-height:28px
        }
        .BlogArchive li{
        font-size:16px
        }
        .BlogArchive .post-count{
        color:$(posts.text.color)
        }
        #page_body .FeaturedPost,.Blog .blog-posts .post-outer-container{
        background:$(posts.background.color);
        min-height:40px;
        padding:30px 40px;
        width:auto
        }
        .Blog .blog-posts .post-outer-container:last-child{
        margin-bottom:0
        }
        .Blog .blog-posts .post-outer-container .post-outer{
        border:0;
        position:relative;
        padding-bottom:.25em
        }
        .post-outer-container{
        margin-bottom:16px
        }
        .post:first-child{
        margin-top:0
        }
        .post .thumb{
        float:left;
        height:20%;
        width:20%
        }
        .post-share-buttons-bottom,.post-share-buttons-top{
        float:$(endSide)
        }
        .post-share-buttons-bottom{
        margin-$endSide:24px
        }
        .post-footer,.post-header{
        clear:$(startSide);
        color:$(posts.byline.color);
        margin:0;
        width:inherit
        }
        .blog-pager{
        text-align:center
        }
        .blog-pager a{
        color:$(posts.navigation.link.color)
        }
        .blog-pager a:visited{
        color:$(posts.navigation.link.visited.color)
        }
        .blog-pager a:hover{
        color:$(posts.navigation.link.hover.color)
        }
        .post-title{
        font:$(posts.title.font);
        float:$(startSide);
        margin:0 0 8px 0;
        max-width:calc(100% - 48px)
        }
        .post-title a{
        font:$(posts.stream.title.font)
        }
        .post-title,.post-title a,.post-title a:hover,.post-title a:visited{
        color:$(posts.title.color)
        }
        .post-body{
        color:$(posts.text.color);
        font:$(posts.text.font);
        line-height:1.6em;
        margin:1.5em 0 2em 0;
        display:block
        }
        .post-body img{
        height:inherit
        }
        .post-body .snippet-thumbnail{
        float:$(startSide);
        margin:0;
        margin-$endSide:2em;
        max-height:128px;
        max-width:128px
        }
        .post-body .snippet-thumbnail img{
        max-width:100%
        }
        .main .FeaturedPost .widget-content{
        border:0;
        position:relative;
        padding-bottom:.25em
        }
        .FeaturedPost img{
        margin-top:2em
        }
        .FeaturedPost .snippet-container{
        margin:2em 0
        }
        .FeaturedPost .snippet-container p{
        margin:0
        }
        .FeaturedPost .snippet-thumbnail{
        float:none;
        height:auto;
        margin-bottom:2em;
        margin-$endSide:0;
        overflow:hidden;
        max-height:calc(600px + 2em);
        max-width:100%;
        text-align:center;
        width:100%
        }
        .FeaturedPost .snippet-thumbnail img{
        max-width:100%;
        width:100%
        }
        .byline{
        color:$(posts.byline.color);
        display:inline-block;
        line-height:24px;
        margin-top:8px;
        vertical-align:top
        }
        .byline.post-author:first-child{
        margin-$endSide:0
        }
        .byline.reactions .reactions-label{
        line-height:22px;
        vertical-align:top
        }
        .byline.post-share-buttons{
        position:relative;
        display:inline-block;
        margin-top:0;
        width:100%
        }
        .byline.post-share-buttons .sharing{
        float:$(endSide)
        }
        .flat-button.ripple:hover{
        background-color:rgba($(body.link.color.red),$(body.link.color.green),$(body.link.color.blue),.12)
        }
        .flat-button.ripple .splash{
        background-color:rgba($(body.link.color.red),$(body.link.color.green),$(body.link.color.blue),.4)
        }
        a.timestamp-link,a:active.timestamp-link,a:visited.timestamp-link{
        color:inherit;
        font:inherit;
        text-decoration:inherit
        }
        .post-share-buttons{
        margin-left:0
        }
        .clear-sharing{
        min-height:24px
        }
        .comment-link{
        color:$(body.link.color);
        position:relative
        }
        .comment-link .num_comments{
        margin-left:8px;
        vertical-align:top
        }
        #comment-holder .continue{
        display:none
        }
        #comment-editor{
        margin-bottom:20px;
        margin-top:20px
        }
        #comments .comment-form h4,#comments h3.title{
        position:absolute;
        clip:rect(1px,1px,1px,1px);
        padding:0;
        border:0;
        height:1px;
        width:1px;
        overflow:hidden
        }
        .post-filter-message{
        background-color:rgba(0,0,0,.7);
        color:#fff;
        display:table;
        margin-bottom:16px;
        width:100%
        }
        .post-filter-message div{
        display:table-cell;
        padding:15px 28px
        }
        .post-filter-message div:last-child{
        padding-$startSide:0;
        text-align:$(endSide)
        }
        .post-filter-message a{
        white-space:nowrap
        }
        .post-filter-message .search-label,.post-filter-message .search-query{
        font-weight:700;
        color:$(body.link.color)
        }
        #blog-pager{
        margin:2em 0
        }
        #blog-pager a{
        color:$(attribution.link.color);
        font-size:14px
        }
        .subscribe-button{
        border-color:$(blog.title.color);
        color:$(blog.title.color)
        }
        .sticky .subscribe-button{
        border-color:$(posts.text.color);
        color:$(posts.text.color)
        }
        .tabs{
        margin:0 auto;
        padding:0
        }
        .tabs li{
        margin:0 8px;
        vertical-align:top
        }
        .tabs .overflow-button a,.tabs li a{
        color:$(tabs.color);
        font:$(tabs.font);
        line-height:$(body.text.font.size * 1.2)
        }
        .tabs .overflow-button a{
        padding:12px 8px
        }
        .overflow-popup .tabs li{
        text-align:left
        }
        .overflow-popup li a{
        color:$(tabs.overflow.color);
        display:block;
        padding:8px 20px
        }
        .overflow-popup li.selected a{
        color:$(tabs.overflow.selected.color)
        }
        a.report_abuse{
        font-weight:400
        }
        .Label li,.Label span.label-size,.byline.post-labels a{
        background-color:$(labels.background.color);
        border:1px solid $(labels.background.color);
        border-radius:15px;
        display:inline-block;
        margin:4px 4px 4px 0;
        padding:3px 8px
        }
        .Label a,.byline.post-labels a{
        color:$(labels.text.color)
        }
        .Label ul{
        list-style:none;
        padding:0
        }
        .PopularPosts{
        background-color:$(popularposts.background.color);
        padding:30px 40px
        }
        .PopularPosts .item-content{
        color:$(popularposts.text.color);
        margin-top:24px
        }
        .PopularPosts a,.PopularPosts a:hover,.PopularPosts a:visited{
        color:$(popularposts.link.color)
        }
        .PopularPosts .post-title,.PopularPosts .post-title a,.PopularPosts .post-title a:hover,.PopularPosts .post-title a:visited{
        color:$(popularposts.title.color);
        font-size:18px;
        font-weight:700;
        line-height:24px
        }
        .PopularPosts,.PopularPosts h3.title a{
        color:$(posts.text.color);
        font:$(posts.text.font)
        }
        .main .PopularPosts{
        padding:16px 40px
        }
        .PopularPosts h3.title{
        font-size:14px;
        margin:0
        }
        .PopularPosts h3.post-title{
        margin-bottom:0
        }
        .PopularPosts .byline{
        color:$(popularposts.byline.color)
        }
        .PopularPosts .jump-link{
        float:$(endSide);
        margin-top:16px
        }
        .PopularPosts .post-header .byline{
        font-size:.9em;
        font-style:italic;
        margin-top:6px
        }
        .PopularPosts ul{
        list-style:none;
        padding:0;
        margin:0
        }
        .PopularPosts .post{
        padding:20px 0
        }
        .PopularPosts .post+.post{
        border-top:1px dashed $(sidebar.separator.color)
        }
        .PopularPosts .item-thumbnail{
        float:$(startSide);
        margin-$endSide:32px
        }
        .PopularPosts .item-thumbnail img{
        height:88px;
        padding:0;
        width:88px
        }
        .inline-ad{
        margin-bottom:16px
        }
        .desktop-ad .inline-ad{
        display:block
        }
        .adsbygoogle{
        overflow:hidden
        }
        .vertical-ad-container{
        float:$(endSide);
        margin-$endSide:16px;
        width:128px
        }
        .vertical-ad-container .AdSense+.AdSense{
        margin-top:16px
        }
        .inline-ad-placeholder,.vertical-ad-placeholder{
        background:$(posts.background.color);
        border:1px solid #000;
        opacity:.9;
        vertical-align:middle;
        text-align:center
        }
        .inline-ad-placeholder span,.vertical-ad-placeholder span{
        margin-top:290px;
        display:block;
        text-transform:uppercase;
        font-weight:700;
        color:$(posts.title.color)
        }
        .vertical-ad-placeholder{
        height:600px
        }
        .vertical-ad-placeholder span{
        margin-top:290px;
        padding:0 40px
        }
        .inline-ad-placeholder{
        height:90px
        }
        .inline-ad-placeholder span{
        margin-top:36px
        }
        .Attribution{
        color:$(attribution.text.color)
        }
        .Attribution a,.Attribution a:hover,.Attribution a:visited{
        color:$(attribution.link.color)
        }
        .Attribution svg{
        fill:$(attribution.icon.color)
        }
        .sidebar-container{
        box-shadow:1px 1px 3px rgba(0,0,0,.1)
        }
        .sidebar-container,.sidebar-container .sidebar_bottom{
        background-color:$(sidebar.backgroundColorBottom)
        }
        .sidebar-container .navigation,.sidebar-container .sidebar_top_wrapper{
        background-color:$(sidebar.backgroundColorTop)
        }
        .sidebar-container .sidebar_top{
        overflow:auto
        }
        .sidebar-container .sidebar_bottom{
        width:100%;
        padding-top:16px
        }
        .sidebar-container .widget:first-child{
        padding-top:0
        }
        .sidebar_top .widget.Profile{
        padding-bottom:16px
        }
        .widget.Profile{
        margin:0;
        width:100%
        }
        .widget.Profile h2{
        display:none
        }
        .widget.Profile h3.title{
        color:$(profile.title.color);
        margin:16px 32px
        }
        .widget.Profile .individual{
        text-align:center
        }
        .widget.Profile .individual .profile-link{
        padding:1em
        }
        .widget.Profile .individual .default-avatar-wrapper .avatar-icon{
        margin:auto
        }
        .widget.Profile .team{
        margin-bottom:32px;
        margin-left:32px;
        margin-right:32px
        }
        .widget.Profile ul{
        list-style:none;
        padding:0
        }
        .widget.Profile li{
        margin:10px 0
        }
        .widget.Profile .profile-img{
        border-radius:50%;
        float:none
        }
        .widget.Profile .profile-link{
        color:$(profile.link.color);
        font-size:.9em;
        margin-bottom:1em;
        opacity:.87;
        overflow:hidden
        }
        .widget.Profile .profile-link.visit-profile{
        border-style:solid;
        border-width:1px;
        border-radius:12px;
        cursor:pointer;
        font-size:12px;
        font-weight:400;
        padding:5px 20px;
        display:inline-block;
        line-height:normal
        }
        .widget.Profile dd{
        color:$(profile.text.color);
        margin:0 16px
        }
        .widget.Profile location{
        margin-bottom:1em
        }
        .widget.Profile .profile-textblock{
        font-size:14px;
        line-height:24px;
        position:relative
        }
        body.sidebar-visible .page_body{
        overflow-y:scroll
        }
        body.sidebar-visible .bg-photo-container{
        overflow-y:scroll
        }
        @media screen and (min-width:$(sidebar.width + content.width + content.margin * 2)){
        .sidebar-container{
        margin-top:$(body.background.height);
        min-height:calc(100% - $(body.background.height));
        overflow:visible;
        z-index:32
        }
        .sidebar-container .sidebar_top_wrapper{
        background-color:$(sidebar.backgroundColorTopHD);
        height:$(body.background.height);
        margin-top:$(body.background.height * -1)
        }
        .sidebar-container .sidebar_top{
        display:-webkit-box;
        display:-webkit-flex;
        display:-ms-flexbox;
        display:flex;
        height:$(body.background.height);
        -webkit-box-orient:horizontal;
        -webkit-box-direction:normal;
        -webkit-flex-direction:row;
        -ms-flex-direction:row;
        flex-direction:row;
        max-height:$(body.background.height)
        }
        .sidebar-container .sidebar_bottom{
        max-width:$(sidebar.width);
        width:$(sidebar.width)
        }
        body.collapsed-header .sidebar-container{
        z-index:15
        }
        .sidebar-container .sidebar_top:empty{
        display:none
        }
        .sidebar-container .sidebar_top>:only-child{
        -webkit-box-flex:0;
        -webkit-flex:0 0 auto;
        -ms-flex:0 0 auto;
        flex:0 0 auto;
        -webkit-align-self:center;
        -ms-flex-item-align:center;
        align-self:center;
        width:100%
        }
        .sidebar_top_wrapper.no-items{
        display:none
        }
        }
        .post-snippet.snippet-container{
        max-height:120px
        }
        .post-snippet .snippet-item{
        line-height:24px
        }
        .post-snippet .snippet-fade{
        background:-webkit-linear-gradient($startSide,$(posts.background.color) 0,$(posts.background.color) 20%,$(posts.background.color.transparent) 100%);
        background:linear-gradient(to $startSide,$(posts.background.color) 0,$(posts.background.color) 20%,$(posts.background.color.transparent) 100%);
        color:$(body.text.color);
        height:24px
        }
        .popular-posts-snippet.snippet-container{
        max-height:72px
        }
        .popular-posts-snippet .snippet-item{
        line-height:24px
        }
        .PopularPosts .popular-posts-snippet .snippet-fade{
        color:$(body.text.color);
        height:24px
        }
        .main .popular-posts-snippet .snippet-fade{
        background:-webkit-linear-gradient($startSide,$(popularposts.background.color) 0,$(popularposts.background.color) 20%,$(popularposts.background.color.transparent) 100%);
        background:linear-gradient(to $startSide,$(popularposts.background.color) 0,$(popularposts.background.color) 20%,$(popularposts.background.color.transparent) 100%)
        }
        .sidebar_bottom .popular-posts-snippet .snippet-fade{
        background:-webkit-linear-gradient($startSide,$(sidebar.backgroundColorBottom) 0,$(sidebar.backgroundColorBottom) 20%,$(sidebar.backgroundColorBottom.transparent) 100%);
        background:linear-gradient(to $startSide,$(sidebar.backgroundColorBottom) 0,$(sidebar.backgroundColorBottom) 20%,$(sidebar.backgroundColorBottom.transparent) 100%)
        }
        .profile-snippet.snippet-container{
        max-height:192px
        }
        .has-location .profile-snippet.snippet-container{
        max-height:144px
        }
        .profile-snippet .snippet-item{
        line-height:24px
        }
        .profile-snippet .snippet-fade{
        background:-webkit-linear-gradient($startSide,$(sidebar.backgroundColorTop) 0,$(sidebar.backgroundColorTop) 20%,$(sidebar.backgroundColorTop.transparent) 100%);
        background:linear-gradient(to $startSide,$(sidebar.backgroundColorTop) 0,$(sidebar.backgroundColorTop) 20%,$(sidebar.backgroundColorTop.transparent) 100%);
        color:$(profile.text.color);
        height:24px
        }
        @media screen and (min-width:$(sidebar.width + content.width + content.margin * 2)){
        .profile-snippet .snippet-fade{
        background:-webkit-linear-gradient($startSide,$(sidebar.backgroundColorTopHD) 0,$(sidebar.backgroundColorTopHD) 20%,$(sidebar.backgroundColorTopHD.transparent) 100%);
        background:linear-gradient(to $startSide,$(sidebar.backgroundColorTopHD) 0,$(sidebar.backgroundColorTopHD) 20%,$(sidebar.backgroundColorTopHD.transparent) 100%)
        }
        }
        @media screen and (max-width:800px){
        .blog-name{
        margin-top:0
        }
        body.item-view .blog-name{
        margin:0 48px
        }
        .centered-bottom{
        padding:8px
        }
        body.item-view .centered-bottom{
        padding:0
        }
        .page_body .centered{
        padding:10px 0
        }
        body.item-view #header,body.item-view .widget.Header{
        margin-right:0
        }
        body.collapsed-header .centered-top-container .blog-name{
        display:block
        }
        body.collapsed-header .centered-top-container .widget.Header h1{
        text-align:center
        }
        .widget.Header header{
        padding:0
        }
        .widget.Header h1{
        font-size:$(blog.title.font.size * 24 / 45);
        line-height:$(blog.title.font.size * 24 / 45);
        margin-bottom:13px
        }
        body.item-view .widget.Header h1{
        text-align:center
        }
        body.item-view .widget.Header p{
        text-align:center
        }
        .blog-name .widget.PageList{
        padding:0
        }
        body.item-view .centered-top{
        margin-bottom:5px
        }
        .search-action,.search-input{
        margin-bottom:-8px
        }
        .search form{
        margin-bottom:8px
        }
        body.item-view .subscribe-section-container{
        margin:5px 0 0 0;
        width:100%
        }
        #page_body.section div.widget.FeaturedPost,div.widget.PopularPosts{
        padding:16px
        }
        div.widget.Blog .blog-posts .post-outer-container{
        padding:16px
        }
        div.widget.Blog .blog-posts .post-outer-container .post-outer{
        padding:0
        }
        .post:first-child{
        margin:0
        }
        .post-body .snippet-thumbnail{
        margin:0 3vw 3vw 0
        }
        .post-body .snippet-thumbnail img{
        height:20vw;
        width:20vw;
        max-height:128px;
        max-width:128px
        }
        div.widget.PopularPosts div.item-thumbnail{
        margin:0 3vw 3vw 0
        }
        div.widget.PopularPosts div.item-thumbnail img{
        height:20vw;
        width:20vw;
        max-height:88px;
        max-width:88px
        }
        .post-title{
        line-height:1
        }
        .post-title,.post-title a{
        font-size:20px
        }
        #page_body.section div.widget.FeaturedPost h3 a{
        font-size:22px
        }
        .mobile-ad .inline-ad{
        display:block
        }
        .page_body.has-vertical-ads .vertical-ad-container,.page_body.has-vertical-ads .vertical-ad-container ins{
        display:none
        }
        .page_body.has-vertical-ads .centered .centered-bottom,.page_body.has-vertical-ads .centered .centered-top{
        display:block;
        width:auto
        }
        div.post-filter-message div{
        padding:8px 16px
        }
        }
        @media screen and (min-width:$(sidebar.width + content.width + content.margin * 2)){
        body{
        position:relative
        }
        body.item-view .blog-name{
        margin-left:48px
        }
        .page_body{
        margin-left:$(sidebar.width)
        }
        .search{
        margin-left:0
        }
        .search.focused{
        width:100%
        }
        .sticky{
        padding-left:$(sidebar.width)
        }
        .hamburger-menu{
        display:none
        }
        body.collapsed-header .page_body .centered-top-container{
        padding-left:$(sidebar.width);
        padding-right:0;
        width:100%
        }
        body.collapsed-header .centered-top-container .search.focused{
        width:100%
        }
        body.collapsed-header .centered-top-container .blog-name{
        margin-left:0
        }
        body.collapsed-header.item-view .centered-top-container .search.focused{
        width:calc(100% - 50px)
        }
        body.collapsed-header.item-view .centered-top-container .blog-name{
        margin-left:40px
        }
        }
        ]]></b:skin>

    <b:template-skin>
        <![CDATA[
        body#layout .hidden,
        body#layout .invisible {
        display: inherit;
        }
        body#layout .navigation {
        display: none;
        }
        body#layout .page,
        body#layout .sidebar_top,
        body#layout .sidebar_bottom {
        display: inline-block;
        left: inherit;
        position: relative;
        vertical-align: top;
        }
        body#layout .page {
        float: right;
        margin-left: 20px;
        width: 55%;
        }
        body#layout .sidebar-container {
        float: right;
        width: 40%;
        }
        body#layout .hamburger-menu {
        display: none;
        }
        ]]>
    </b:template-skin>

    <b:defaultmarkups>
        <b:defaultmarkup type='Common'>
            <b:includable id='widgetNotAvailableInPreview'>
                <b:if cond='data:widget.type == &quot;AdSense&quot;'>
                    <div class='vertical-ad-placeholder'>
                        <span><b:message name='messages.adsGoHere'/></span>
                    </div>
                    <b:else/>
                    <b:include name='super.widgetNotAvailableInPreview'/>
                </b:if>
            </b:includable>
        </b:defaultmarkup>
        <b:defaultmarkup type='AdSense,Blog'>
            <b:includable id='defaultAdUnit'>
                <b:comment>Clear out style (needs to be a non-empty string)</b:comment>
                <b:with value='&quot;/* Done in css. */&quot;' var='style'>
                    <b:include name='super.defaultAdUnit'/>
                </b:with>
            </b:includable>
        </b:defaultmarkup>
        <b:defaultmarkup type='Blog,FeaturedPost'>
            <b:includable id='headerByline'>
                <b:include cond='data:view.isMultipleItems or data:widgets.Blog.first.headerByline.items.share' data='{ shareButtonClass: &quot;post-share-buttons-top&quot;, overridden: true }' name='maybeAddShareButtons'/>
                <b:include name='super.headerByline'/>
            </b:includable>
        </b:defaultmarkup>
        <b:defaultmarkup type='Blog,FeaturedPost,PopularPosts'>
            <b:includable id='commentsLink'>
                <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
                    <b:include data='{ iconClass: &quot;touch-icon&quot; }' name='commentIcon'/>
                    <span class='num_comments'>
              <b:if cond='data:post.numberOfComments &gt; 0'>
                <b:message name='messages.numberOfComments'>
                  <b:param expr:value='data:post.numberOfComments' name='numComments'/>
                </b:message>
              <b:else/>
                <data:messages.postAComment/>
              </b:if>
            </span>
                </a>
            </b:includable>
            <b:includable id='snippetedPostByline'>
                <b:include name='headerByline'/>
            </b:includable>
            <b:includable id='postLabels'>
                <b:comment>We don&#39;t display labels on the home page.</b:comment>
                <b:if cond='data:view.isSingleItem and data:widget.type == &quot;Blog&quot;'>
                    <b:include name='super.postLabels'/>
                </b:if>
            </b:includable>
            <b:includable id='postShareButtons' var='post'>
                <b:comment>We call super.postShareButtons from the migrated positions.</b:comment>
            </b:includable>
            <b:includable id='postJumpLink'>
                <b:comment>Overridden, and migrated to postFooter. Called as postFooterJumpLink.</b:comment>
            </b:includable>
            <b:includable id='postFooterJumpLink'>
                <b:comment>Ripple, and show &#39;keep reading&#39; as the default.</b:comment>
                <div class='jump-link flat-button ripple'>
                    <a expr:href='data:post.hasJumpLink ? data:post.url fragment &quot;more&quot; : data:post.url' expr:title='data:post.title'>
                        <data:blog.jumpLinkMessage/>
                    </a>
                </div>
            </b:includable>
            <b:includable id='postFooter' var='post'>
                <div class='post-bottom'>
                    <div class='post-footer float-container'>
                        <b:include name='footerBylines'/>
                        <b:include cond='data:widget.type == &quot;Blog&quot;' data='post' name='postFooterAuthorProfile'/>
                    </div>
                    <b:if cond='data:view.isSingleItem'>
                        <b:include data='{ shareButtonClass: &quot;post-share-buttons-bottom invisible&quot;, overridden: true }' name='maybeAddShareButtons'/>
                        <b:else/>
                        <b:include data='post' name='postFooterJumpLink'/>
                    </b:if>
                </div>
            </b:includable>
        </b:defaultmarkup>
        <b:defaultmarkup type='Blog'>
            <b:includable id='main'>
                <b:include name='noContentPlaceholder'/>

                <b:comment>Cap the total number of ads (widgets and inline ads).</b:comment>
                <b:with value='3' var='maxNumAds'>
                    <b:with value='data:widgets.AdSense.size' var='numDesktopAds'>
                        <b:with value='data:widgets.AdSense count (w =&gt; w.sectionId != &quot;ads&quot;)' var='numMobileAds'>
                            <b:comment>Filter out the featured post, but only on the homepage.</b:comment>
                            <b:with value='data:widgets.FeaturedPost filter (w =&gt; w.sectionId == &quot;page_body&quot;) map (w =&gt; w.postId)' var='featuredPostIds'>
                                <b:with value='data:view.isHomepage                                          ? data:posts filter (post =&gt; post.id not in data:featuredPostIds)                                          : data:posts' var='posts'>
                                    <b:include name='super.main'/>
                                </b:with>
                            </b:with>
                        </b:with>
                    </b:with>
                </b:with>
            </b:includable>
            <b:includable id='feedLinks'>
                <b:comment>Don&#39;t show feed links.</b:comment>
            </b:includable>
            <b:includable id='postBodySnippet' var='post'>
                <div class='container post-body entry-content' expr:id='&quot;post-snippet-&quot; + data:post.id'>

                    <b:if cond='data:post.featuredImage'>
                        <div class='snippet-thumbnail'>
                            <b:include data='{                                     image: data:post.featuredImage,                                     imageSizes: [32, 64, 128, 256],                                     imageRatio: &quot;1:1&quot;,                                     sourceSizes: &quot;(max-width: 800px) 20vw, 128px&quot;                                  }' name='responsiveImage'/>
                        </div>
                    </b:if>
                    <b:include cond='data:post' data='post' name='postSnippet'/>
                </div>
            </b:includable>
            <b:includable id='previousPageLink'><b:comment>Don&#39;t show</b:comment></b:includable>
            <b:includable id='homePageLink'><b:comment>Don&#39;t show</b:comment></b:includable>
            <b:includable id='nextPageLink'>
                <a class='blog-pager-older-link flat-button ripple' expr:href='data:olderPageUrl' expr:title='data:messages.morePosts'>
                    <data:messages.morePosts/>
                </a>
            </b:includable>
            <b:includable id='inlineAd' var='post'>
                <div>
                    <b:class cond='data:post.adNumber + data:numDesktopAds lt data:maxNumAds' name='desktop-ad'/>
                    <b:class cond='data:post.adNumber + data:numMobileAds lt data:maxNumAds' name='mobile-ad'/>
                    <b:include data='post' name='super.inlineAd'/>
                </div>
            </b:includable>
        </b:defaultmarkup>
        <b:defaultmarkup type='BlogArchive'>
            <b:includable id='main' var='this'>
                <details class='collapsible extendable'>
                    <b:attr cond='data:view.isArchive' name='open' value='open'/>
                    <b:with value='true' var='renderAsDetails'>
                        <b:with value='data:messages.archive' var='defaultTitle'>
                            <b:include name='super.main'/>
                        </b:with>
                    </b:with>
                </details>
            </b:includable>
            <b:includable id='flat'>
                <b:include data='{                               buttonClass: &quot;pill-button&quot;,                               items: data:this.data,                               itemSet: &quot;data&quot;,                               itemsMarkup: &quot;super.flat&quot;                             }' name='extendableItems'/>
            </b:includable>
            <b:includable id='hierarchy'>
                <b:include data='{                               buttonClass: &quot;pill-button&quot;,                               limit: 1,                               items: data:this.data,                               itemSet: &quot;data&quot;,                               itemsMarkup: &quot;super.hierarchy&quot;                             }' name='extendableItems'/>
            </b:includable>
        </b:defaultmarkup>
        <b:defaultmarkup type='BlogSearch'>
            <b:includable id='searchSubmit'>
                <input class='search-action flat-button' type='submit'/>
            </b:includable>
        </b:defaultmarkup>
        <b:defaultmarkup type='Label'>
            <b:includable id='main' var='this'>
                <details class='collapsible extendable'>
                    <b:attr cond='data:view.isLabelSearch' name='open' value='open'/>
                    <b:with value='true' var='renderAsDetails'>
                        <b:with value='data:messages.labels' var='defaultTitle'>
                            <b:include name='super.main'/>
                        </b:with>
                    </b:with>
                </details>
            </b:includable>
            <b:includable id='list'>
                <b:include data='{                               buttonClass: &quot;pill-button&quot;,                               items: data:this.labels,                               itemSet: &quot;labels&quot;,                               itemsMarkup: &quot;super.list&quot;                             }' name='extendableItems'/>
            </b:includable>
            <b:includable id='cloud'>
                <b:include data='{                               buttonClass: &quot;pill-button&quot;,                               items: data:this.labels,                               itemSet: &quot;labels&quot;,                               itemsMarkup: &quot;super.cloud&quot;                             }' name='extendableItems'/>
            </b:includable>
        </b:defaultmarkup>
        <b:defaultmarkup type='FeaturedPost'>
            <b:includable id='snippetedPostContent'>
                <b:comment>Re-order the thumbnail before the snippet, add &#39;Keep reading&#39; link.</b:comment>
                <b:include cond='data:this.postDisplay.showTitle' name='snippetedPostTitle'/>
                <b:include name='headerByline'/>
                <b:include cond='data:this.postDisplay.showFeaturedImage and data:post.featuredImage' data='post' name='snippetedPostThumbnail'/>
                <b:include cond='data:this.postDisplay.showSnippet' data='post' name='postSnippet'/>
                <b:include data='post' name='postFooter'/>
            </b:includable>
            <b:includable id='snippetedPostThumbnail'>
                <div class='snippet-thumbnail'>
                    <b:with value='data:post.featuredImage.isYoutube                            ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl, 945, &quot;945:600&quot;)                            : &quot;&quot;' var='highRes'>
                        <b:include data='{                                  image: data:post.featuredImage,                                  imageSizes: [256, 512, 945, 1684],                                  imageRatio: &quot;945:600&quot;,                                  sourceSizes: &quot;(min-width: 954px) 842px, (min-width: 801px) calc(100vw - 112px), calc(100vw - 64px)&quot;,                                  enhancedSourceset: data:highRes                                }' name='responsiveImage'/>
                    </b:with>
                </div>
            </b:includable>
        </b:defaultmarkup>
        <b:defaultmarkup type='Header'>
            <b:includable id='image'>
                <b:include name='super.image'/>
                <b:comment>If we are replacing the title, force it to render anyway, and it&#39;ll be hidden in CSS.</b:comment>
                <b:include cond='data:this.imagePlacement == &quot;REPLACE&quot;' name='title'/>
            </b:includable>
            <b:includable id='title'>
                <div>
                    <b:class cond='data:this.imagePlacement == &quot;REPLACE&quot;' name='replaced'/>
                    <b:include name='super.title'/>
                </div>
            </b:includable>
        </b:defaultmarkup>
        <b:defaultmarkup type='PopularPosts'>
            <b:includable id='main' var='this'>
                <b:comment>Default the title to &#39;Popular posts from this blog&#39;.</b:comment>
                <b:with value='data:messages.popularPostsFromThisBlog' var='defaultTitle'>
                    <b:include name='super.main'/>
                </b:with>
            </b:includable>
            <b:includable id='snippetedPostContent'>
                <b:comment>Add a &#39;keep reading&#39; link to the item-content.</b:comment>
                <b:include name='snippetedPostTitle'/>
                <b:include name='snippetedPostByline'/>
                <div class='item-content float-container'>
                    <b:include cond='data:this.postDisplay.showFeaturedImage and data:post.featuredImage' name='snippetedPostThumbnail'/>
                    <b:if cond='data:this.postDisplay.showSnippet'>
                        <b:with value='&quot;popular-posts&quot;' var='snippetPrefix'>
                            <b:include cond='data:post' data='post' name='postSnippet'/>
                        </b:with>
                    </b:if>
                    <b:include data='post' name='postFooterJumpLink'/>
                </div>
            </b:includable>
        </b:defaultmarkup>
        <b:defaultmarkup type='PageList'>
            <b:includable id='content'>
                <div class='widget-content'>
                    <b:include cond='data:widget.sectionId == &quot;page_list_top&quot;' name='overflowablePageList'/>
                    <b:include cond='data:widget.sectionId != &quot;page_list_top&quot;' name='pageList'/>
                </div>
            </b:includable>
            <b:includable id='overflowButton'>
                <a><data:messages.moreEllipsis/></a>
            </b:includable>
        </b:defaultmarkup>
        <b:defaultmarkup type='Profile'>
            <b:includable id='main' var='this'>
                <div class='wrapper'>
                    <b:class cond='!data:this.team' name='solo'/>
                    <b:comment>No title for single profiles. Default to &#39;Blog authors&#39; for team.</b:comment>
                    <b:with value='data:messages.blogAuthors' var='defaultTitle'>
                        <b:include cond='data:this.team' name='widget-title'/>
                    </b:with>
                    <b:include name='content'/>
                </div>
            </b:includable>
            <b:includable id='defaultProfileImage'>
                <div class='default-avatar-wrapper'>
                    <b:include data='{ iconClass: &quot;avatar-icon&quot; }' name='defaultAvatarIcon'/>
                </div>
            </b:includable>
            <b:includable id='userProfileText'>
                <dd class='profile-textblock profile-snippet snippet-container r-snippet-container'>
                    <div class='snippet-item r-snippetized'>
                        <data:aboutme/>
                    </div>
                    <div class='snippet-fade r-snippet-fade hidden'/>
                </dd>
            </b:includable>
            <b:includable id='viewProfileLink'>
                <b:comment>Change link to &#39;visit profile&#39;</b:comment>
                <a class='profile-link visit-profile pill-button' rel='author'>
                    <data:messages.visitProfile/>
                </a>
            </b:includable>
        </b:defaultmarkup>
    </b:defaultmarkups>

    <b:include cond='not data:view.isPreview' data='{                         image: data:skin.vars.body_background.image,                         selector: &quot;.bg-photo&quot;,                         imageSizes: [480, 640, 800, 1200, 1600]                      }' name='responsiveImageStyle'/>

    <b:if cond='(data:widgets.AdSense.first or data:blog.adsenseClientId) and not data:blog.adsenseAutoAds'>
        <script async='async' src='//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js'/>
    </b:if>
    <b:include data='blog' name='google-analytics'/>

    <script async='async' src='https://www.gstatic.com/external_hosted/clipboardjs/clipboard.min.js'/>
</head>

<body>
<b:class cond='data:view.isPreview' name='preview'/>
<b:class cond='data:view.isSingleItem' name='item-view'/>
<b:class cond='data:view.isArchive' name='archive-view'/>
<b:class cond='data:view.isLabelSearch' name='label-view'/>
<b:class cond='data:view.isSearch and !data:view.isLabelSearch' name='search-view'/>
<b:class name='version-1-3-3'/>

<b:include name='skipNavigation'/>

<div class='page'>
    <div class='bg-photo-overlay'/>
    <div class='bg-photo-container'>
        <div class='bg-photo'/>
    </div>

    <b:with value='data:widgets.AdSense any (w =&gt; w.sectionId == &quot;ads&quot;)' var='hasVerticalAds'>
        <div class='page_body'>
            <b:class cond='data:hasVerticalAds' name='has-vertical-ads'/>

            <div class='centered'>
                <div class='centered-top-placeholder'/>
                <header class='centered-top-container' role='banner'>
                    <div class='centered-top'>
                        <b:class cond='data:view.isSearch and data:view.search.query' name='search-focused'/>

                        <b:if cond='data:view.isSingleItem'>
                            <a class='return_link' expr:href='data:blog.homepageUrl'>
                                <b:include data='{ button: true, iconClass: &quot;back-button rtl-reversible-icon flat-icon-button ripple&quot; }' name='backArrowIcon'/>
                            </a>
                            <b:else/>
                            <b:include data='{ button: true, iconClass: &quot;hamburger-menu flat-icon-button ripple&quot; }' name='menuIcon'/>
                        </b:if>

                        <b:if cond='data:view.isLayoutMode or data:widgets any (w =&gt; w.sectionId == &quot;search_top&quot;)'>
                            <div class='search'>
                                <b:class cond='data:view.isSearch and data:view.search.query' name='focused'/>
                                <button class='search-expand touch-icon-button' expr:aria-label='data:messages.search.escaped'>
                                    <div class='flat-icon-button ripple'>
                                        <b:include data='{ iconClass: &quot;search-expand-icon&quot; }' name='searchIcon'/>
                                    </div>
                                </button>
                                <b:section id='search_top' name='Search (Top)' showaddelement='false'>
                                  <b:widget id='BlogSearch1' locked='true' title='Search This Blog' type='BlogSearch' visible='true'>
                                    <b:includable id='main'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
                                    <b:includable id='content'>
  <div class='widget-content' role='search'>
    <b:include name='searchForm'/>
  </div>
</b:includable>
                                    <b:includable id='searchForm'>
  <form expr:action='data:blog.searchUrl'>
    <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
    <b:include name='urlParamsAsFormInput'/>
    <div class='search-input'>
      <input autocomplete='off' expr:aria-label='data:messages.searchThisBlog' expr:placeholder='data:messages.searchThisBlog' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q'/>
    </div>
    <b:include name='searchSubmit'/>
  </form>
</b:includable>
                                    <b:includable id='searchSubmit'>
                <input class='search-action flat-button' type='submit'/>
            </b:includable>
                                  </b:widget>
                                </b:section>
                            </div>
                        </b:if>

                        <div class='clearboth'/>

                        <div class='blog-name container'>
                            <b:section class='container' id='header' name='Header' showaddelement='false'>
                              <b:widget id='Header1' locked='true' title='jamzblog.com (Header)' type='Header' visible='true'>
                                <b:widget-settings>
                                  <b:widget-setting name='displayUrl'/>
                                  <b:widget-setting name='displayHeight'>0</b:widget-setting>
                                  <b:widget-setting name='sectionWidth'>-1</b:widget-setting>
                                  <b:widget-setting name='useImage'>false</b:widget-setting>
                                  <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
                                  <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
                                  <b:widget-setting name='displayWidth'>0</b:widget-setting>
                                </b:widget-settings>
                                <b:includable id='main' var='this'>
    <div class='header-widget'>
      <b:include cond='data:imagePlacement in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='image'/>
      <b:include cond='data:imagePlacement not in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='title'/>
      <b:include cond='data:imagePlacement != &quot;REPLACE&quot;' name='description'/>
    </div>
    <b:include cond='data:imagePlacement == &quot;BEHIND&quot;' name='behindImageStyle'/>
  </b:includable>
                                <b:includable id='behindImageStyle'>
    <b:if cond='data:sourceUrl'>
      <b:include cond='data:this.image' data='{                    image: data:this.image,                    selector: &quot;.header-widget&quot;                  }' name='responsiveImageStyle'/>
      <style type='text/css'>
        .header-widget {
          background-position: <data:blog.locale.languageAlignment/>;
          background-repeat: no-repeat;
          background-size: cover;
        }
      </style>
    </b:if>
  </b:includable>
                                <b:includable id='description'>
    <p>
      <data:this.description/>
    </p>
  </b:includable>
                                <b:includable id='image'>
                <b:include name='super.image'/>
                <b:comment>If we are replacing the title, force it to render anyway, and it&#39;ll be hidden in CSS.</b:comment>
                <b:include cond='data:this.imagePlacement == &quot;REPLACE&quot;' name='title'/>
            </b:includable>
                                <b:includable id='title'>
                <div>
                    <b:class cond='data:this.imagePlacement == &quot;REPLACE&quot;' name='replaced'/>
                    <b:include name='super.title'/>
                </div>
            </b:includable>
                              </b:widget>
                            </b:section>
                            <b:comment>Nav primarily intended for sections that consist of major navigation blocks.</b:comment>
                            <nav role='navigation'>
                                <b:section class='clearboth' id='page_list_top' name='Page List (Top)' showaddelement='false'>
                                  <b:widget id='PageList1' locked='true' title='' type='PageList' visible='false'>
                                    <b:widget-settings>
                                      <b:widget-setting name='pageListJson'><![CDATA[{"home":{"href":"http://shekwoyemilo.blogspot.com/","position":0,"title":"Home"}}]]></b:widget-setting>
                                      <b:widget-setting name='homeTitle'>Home</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
                                    <b:includable id='content'>
                <div class='widget-content'>
                    <b:include cond='data:widget.sectionId == &quot;page_list_top&quot;' name='overflowablePageList'/>
                    <b:include cond='data:widget.sectionId != &quot;page_list_top&quot;' name='pageList'/>
                </div>
            </b:includable>
                                    <b:includable id='overflowButton'>
                <a><data:messages.moreEllipsis/></a>
            </b:includable>
                                    <b:includable id='overflowablePageList'>
  <div class='overflowable-container'>
    <div class='overflowable-contents'>
      <div class='container'>
        <b:with value='true' var='overflow'>
        <b:with value='&quot;tabs&quot;' var='pageListClass'>
          <b:include name='pageList'/>
        </b:with>
        </b:with>
      </div>
    </div>
    <div class='overflow-button hidden'>
      <b:include name='overflowButton'/>
    </div>
  </div>
</b:includable>
                                    <b:includable id='pageLink'>
  <li>
    <b:class cond='data:overflow' name='overflowable-item'/>
    <b:class cond='data:link.isCurrentPage' name='selected'/>

    <a expr:href='data:link.href'><data:link.title/></a>
  </li>
</b:includable>
                                    <b:includable id='pageList'>
  <ul>
    <b:class cond='data:pageListClass' expr:name='data:pageListClass'/>
    <b:loop values='data:links' var='link'>
      <b:include name='pageLink'/>
    </b:loop>
  </ul>
</b:includable>
                                  </b:widget>
                                </b:section>
                            </nav>
                        </div>
                    </div>
                </header>
                <div>
                    <b:section ads='true' class='vertical-ad-container' id='ads' name='Ads' showaddelement='false'>
                      <b:widget id='AdSense1' locked='true' title='' type='AdSense' visible='true'>
                        <b:widget-settings>
                          <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
                          <b:widget-setting name='style.textcolor'>#2196f3</b:widget-setting>
                          <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                          <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
                          <b:widget-setting name='style.urlcolor'>#212121</b:widget-setting>
                          <b:widget-setting name='style.linkcolor'>#757575</b:widget-setting>
                          <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
                        </b:widget-settings>
                        <b:includable id='main'>
  <div class='widget-content'>
    <b:if cond='data:adCode'>
      <data:adCode/>
    <b:else/>
      <b:include name='defaultAdUnit'/>
    </b:if>
  </div>
</b:includable>
                        <b:includable id='defaultAdUnit'>
                <b:comment>Clear out style (needs to be a non-empty string)</b:comment>
                <b:with value='&quot;/* Done in css. */&quot;' var='style'>
                    <b:include name='super.defaultAdUnit'/>
                </b:with>
            </b:includable>
                      </b:widget>
                      <b:widget id='AdSense2' locked='true' title='' type='AdSense' visible='false'>
                        <b:widget-settings>
                          <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
                          <b:widget-setting name='style.textcolor'>#2196f3</b:widget-setting>
                          <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                          <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
                          <b:widget-setting name='style.urlcolor'>#212121</b:widget-setting>
                          <b:widget-setting name='style.linkcolor'>#757575</b:widget-setting>
                          <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
                        </b:widget-settings>
                        <b:includable id='main'>
  <div class='widget-content'>
    <b:if cond='data:adCode'>
      <data:adCode/>
    <b:else/>
      <b:include name='defaultAdUnit'/>
    </b:if>
  </div>
</b:includable>
                        <b:includable id='defaultAdUnit'>
                <b:comment>Clear out style (needs to be a non-empty string)</b:comment>
                <b:with value='&quot;/* Done in css. */&quot;' var='style'>
                    <b:include name='super.defaultAdUnit'/>
                </b:with>
            </b:includable>
                      </b:widget>
                    </b:section>
                    <main class='centered-bottom' id='main' role='main' tabindex='-1'>
                        <b:if cond='data:view.isMultipleItems'>
                            <h2 class='main-heading'><data:messages.posts/></h2>
                        </b:if>
                        <b:if cond='data:view.isArchive or (data:view.isSearch and data:view.search.resultsMessageHtml)'>
                            <div class='post-filter-message'>
                                <div>
                                    <b:if cond='data:view.isArchive'>
                                        <data:view.archive.rangeMessage/>
                                        <b:elseif cond='data:view.isSearch and data:view.search.resultsMessageHtml'/>
                                        <data:view.search.resultsMessageHtml/>
                                    </b:if>
                                </div>
                                <div>
                                    <a class='flat-button ripple' expr:href='data:blog.homepageUrl'>
                                        <data:messages.showAll/>
                                    </a>
                                </div>
                            </div>
                        </b:if>
                        <b:section class='main' id='page_body' name='Page Body' showaddelement='false'>
                          <b:widget id='FeaturedPost1' locked='true' title='' type='FeaturedPost' visible='true'>
                            <b:widget-settings>
                              <b:widget-setting name='showSnippet'>true</b:widget-setting>
                              <b:widget-setting name='showPostTitle'>true</b:widget-setting>
                              <b:widget-setting name='showFirstImage'>true</b:widget-setting>
                              <b:widget-setting name='useMostRecentPost'>true</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main' var='this'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <b:include name='snippetedPosts'/>
  </div>
</b:includable>
                            <b:includable id='commentsLink'>
                <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
                    <b:include data='{ iconClass: &quot;touch-icon&quot; }' name='commentIcon'/>
                    <span class='num_comments'>
              <b:if cond='data:post.numberOfComments &gt; 0'>
                <b:message name='messages.numberOfComments'>
                  <b:param expr:value='data:post.numberOfComments' name='numComments'/>
                </b:message>
              <b:else/>
                <data:messages.postAComment/>
              </b:if>
            </span>
                </a>
            </b:includable>
                            <b:includable id='headerByline'>
                <b:include cond='data:view.isMultipleItems or data:widgets.Blog.first.headerByline.items.share' data='{ shareButtonClass: &quot;post-share-buttons-top&quot;, overridden: true }' name='maybeAddShareButtons'/>
                <b:include name='super.headerByline'/>
            </b:includable>
                            <b:includable id='postFooter' var='post'>
                <div class='post-bottom'>
                    <div class='post-footer float-container'>
                        <b:include name='footerBylines'/>
                        <b:include cond='data:widget.type == &quot;Blog&quot;' data='post' name='postFooterAuthorProfile'/>
                    </div>
                    <b:if cond='data:view.isSingleItem'>
                        <b:include data='{ shareButtonClass: &quot;post-share-buttons-bottom invisible&quot;, overridden: true }' name='maybeAddShareButtons'/>
                        <b:else/>
                        <b:include data='post' name='postFooterJumpLink'/>
                    </b:if>
                </div>
            </b:includable>
                            <b:includable id='postFooterJumpLink'>
                <b:comment>Ripple, and show &#39;keep reading&#39; as the default.</b:comment>
                <div class='jump-link flat-button ripple'>
                    <a expr:href='data:post.hasJumpLink ? data:post.url fragment &quot;more&quot; : data:post.url' expr:title='data:post.title'>
                        <data:blog.jumpLinkMessage/>
                    </a>
                </div>
            </b:includable>
                            <b:includable id='postJumpLink'>
                <b:comment>Overridden, and migrated to postFooter. Called as postFooterJumpLink.</b:comment>
            </b:includable>
                            <b:includable id='postLabels'>
                <b:comment>We don&#39;t display labels on the home page.</b:comment>
                <b:if cond='data:view.isSingleItem and data:widget.type == &quot;Blog&quot;'>
                    <b:include name='super.postLabels'/>
                </b:if>
            </b:includable>
                            <b:includable id='postShareButtons' var='post'>
                <b:comment>We call super.postShareButtons from the migrated positions.</b:comment>
            </b:includable>
                            <b:includable id='snippetedPostByline'>
                <b:include name='headerByline'/>
            </b:includable>
                            <b:includable id='snippetedPostContent'>
                <b:comment>Re-order the thumbnail before the snippet, add &#39;Keep reading&#39; link.</b:comment>
                <b:include cond='data:this.postDisplay.showTitle' name='snippetedPostTitle'/>
                <b:include name='headerByline'/>
                <b:include cond='data:this.postDisplay.showFeaturedImage and data:post.featuredImage' data='post' name='snippetedPostThumbnail'/>
                <b:include cond='data:this.postDisplay.showSnippet' data='post' name='postSnippet'/>
                <b:include data='post' name='postFooter'/>
            </b:includable>
                            <b:includable id='snippetedPostThumbnail'>
                <div class='snippet-thumbnail'>
                    <b:with value='data:post.featuredImage.isYoutube                            ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl, 945, &quot;945:600&quot;)                            : &quot;&quot;' var='highRes'>
                        <b:include data='{                                  image: data:post.featuredImage,                                  imageSizes: [256, 512, 945, 1684],                                  imageRatio: &quot;945:600&quot;,                                  sourceSizes: &quot;(min-width: 954px) 842px, (min-width: 801px) calc(100vw - 112px), calc(100vw - 64px)&quot;,                                  enhancedSourceset: data:highRes                                }' name='responsiveImage'/>
                    </b:with>
                </div>
            </b:includable>
                          </b:widget>
                          <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' visible='true'>
                            <b:widget-settings>
                              <b:widget-setting name='showDateHeader'>false</b:widget-setting>
                              <b:widget-setting name='style.textcolor'>#ffffff</b:widget-setting>
                              <b:widget-setting name='showShareButtons'>true</b:widget-setting>
                              <b:widget-setting name='showCommentLink'>true</b:widget-setting>
                              <b:widget-setting name='style.urlcolor'>#ffffff</b:widget-setting>
                              <b:widget-setting name='showAuthor'>false</b:widget-setting>
                              <b:widget-setting name='style.linkcolor'>#ffffff</b:widget-setting>
                              <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
                              <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
                              <b:widget-setting name='timestampLabel'/>
                              <b:widget-setting name='reactionsLabel'/>
                              <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
                              <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                              <b:widget-setting name='showLabels'>true</b:widget-setting>
                              <b:widget-setting name='showLocation'>true</b:widget-setting>
                              <b:widget-setting name='postLabelsLabel'/>
                              <b:widget-setting name='showTimestamp'>true</b:widget-setting>
                              <b:widget-setting name='postsPerAd'>1</b:widget-setting>
                              <b:widget-setting name='showBacklinks'>false</b:widget-setting>
                              <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
                              <b:widget-setting name='showInlineAds'>false</b:widget-setting>
                              <b:widget-setting name='showReactions'>false</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main'>
                <b:include name='noContentPlaceholder'/>

                <b:comment>Cap the total number of ads (widgets and inline ads).</b:comment>
                <b:with value='3' var='maxNumAds'>
                    <b:with value='data:widgets.AdSense.size' var='numDesktopAds'>
                        <b:with value='data:widgets.AdSense count (w =&gt; w.sectionId != &quot;ads&quot;)' var='numMobileAds'>
                            <b:comment>Filter out the featured post, but only on the homepage.</b:comment>
                            <b:with value='data:widgets.FeaturedPost filter (w =&gt; w.sectionId == &quot;page_body&quot;) map (w =&gt; w.postId)' var='featuredPostIds'>
                                <b:with value='data:view.isHomepage                                          ? data:posts filter (post =&gt; post.id not in data:featuredPostIds)                                          : data:posts' var='posts'>
                                    <b:include name='super.main'/>
                                </b:with>
                            </b:with>
                        </b:with>
                    </b:with>
                </b:with>
            </b:includable>
                            <b:includable id='aboutPostAuthor'>
  <div class='author-name'>
    <a class='g-profile' expr:href='data:post.author.profileUrl' rel='author' title='author profile'>
      <span>
        <data:post.author.name/>
      </span>
    </a>
  </div>
  <div>
    <span class='author-desc'>
      <data:post.author.aboutMe/>
    </span>
  </div>
</b:includable>
                            <b:includable id='addComments'>
  <a expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:message name='messages.postAComment'/>
  </a>
</b:includable>
                            <b:includable id='commentAuthorAvatar'>
  <div class='avatar-image-container'>
    <img class='author-avatar' expr:src='data:comment.authorAvatarSrc' height='35' width='35'/>
  </div>
</b:includable>
                            <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:messages.deleteComment'>
        <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
                            <b:includable id='commentForm' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <h4 id='comment-post-message'><data:messages.postAComment/></h4>
    <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
      <p><data:this.messages.blogComment/></p>
    </b:if>
    <b:include data='post' name='commentFormIframeSrc'/>
    <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
                            <b:includable id='commentFormIframeSrc' var='post'>
  <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
</b:includable>
                            <b:includable id='commentItem' var='comment'>
  <div class='comment' expr:id='&quot;c&quot; + data:comment.id'>
    <b:include cond='data:blog.enabledCommentProfileImages' name='commentAuthorAvatar'/>

    <div class='comment-block'>
      <div class='comment-author'>
        <b:if cond='data:comment.authorUrl'>
          <b:message name='messages.authorSaidWithLink'>
            <b:param expr:value='data:comment.author' name='authorName'/>
            <b:param expr:value='data:comment.authorUrl' name='authorUrl'/>
          </b:message>
        <b:else/>
          <b:message name='messages.authorSaid'>
            <b:param expr:value='data:comment.author' name='authorName'/>
          </b:message>
        </b:if>
      </div>
      <div expr:class='&quot;comment-body&quot; + (data:comment.isDeleted ? &quot; deleted&quot; : &quot;&quot;)'>
        <data:comment.body/>
      </div>
      <div class='comment-footer'>
        <span class='comment-timestamp'>
          <a expr:href='data:comment.url' title='comment permalink'>
            <data:comment.timestamp/>
          </a>
          <b:include data='comment' name='commentDeleteIcon'/>
        </span>
      </div>
    </div>
  </div>
</b:includable>
                            <b:includable id='commentList' var='comments'>
  <div id='comments-block'>
    <b:loop values='data:comments' var='comment'>
      <b:include data='comment' name='commentItem'/>
    </b:loop>
  </div>
</b:includable>
                            <b:includable id='commentPicker' var='post'>
  <b:if cond='data:post.showThreadedComments'>
    <b:include data='post' name='threadedComments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
                            <b:includable id='comments' var='post'>
  <section expr:class='&quot;comments&quot; + (data:post.embedCommentForm ? &quot; embed&quot; : &quot;&quot;)' expr:data-num-comments='data:post.numberOfComments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>

      <b:include name='commentsTitle'/>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <b:include cond='data:post.comments' data='post.comments' name='commentList'/>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <div class='paging-control-container'>
          <b:if cond='data:post.hasOlderLinks'>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
              <data:messages.oldest/>
            </a>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
              <data:messages.older/>
            </a>
          </b:if>

          <span class='comment-range-text'>
            <data:post.commentRangeText/>
          </span>

          <b:if cond='data:post.hasNewerLinks'>
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
              <data:messages.newer/>
            </a>
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
              <data:messages.newest/>
            </a>
          </b:if>
        </div>
      </b:if>

      <div class='footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='commentForm'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:else/>
          <b:if cond='data:post.allowComments'>
            <b:include data='post' name='addComments'/>
          </b:if>
        </b:if>
      </div>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>
  </section>
</b:includable>
                            <b:includable id='commentsLink'>
                <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
                    <b:include data='{ iconClass: &quot;touch-icon&quot; }' name='commentIcon'/>
                    <span class='num_comments'>
              <b:if cond='data:post.numberOfComments &gt; 0'>
                <b:message name='messages.numberOfComments'>
                  <b:param expr:value='data:post.numberOfComments' name='numComments'/>
                </b:message>
              <b:else/>
                <data:messages.postAComment/>
              </b:if>
            </span>
                </a>
            </b:includable>
                            <b:includable id='commentsTitle'>
  <h3 class='title'><data:messages.comments/></h3>
</b:includable>
                            <b:includable id='defaultAdUnit'>
                <b:comment>Clear out style (needs to be a non-empty string)</b:comment>
                <b:with value='&quot;/* Done in css. */&quot;' var='style'>
                    <b:include name='super.defaultAdUnit'/>
                </b:with>
            </b:includable>
                            <b:includable id='feedLinks'>
                <b:comment>Don&#39;t show feed links.</b:comment>
            </b:includable>
                            <b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:messages.subscribeTo/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
                            <b:includable id='headerByline'>
                <b:include cond='data:view.isMultipleItems or data:widgets.Blog.first.headerByline.items.share' data='{ shareButtonClass: &quot;post-share-buttons-top&quot;, overridden: true }' name='maybeAddShareButtons'/>
                <b:include name='super.headerByline'/>
            </b:includable>
                            <b:includable id='homePageLink'><b:comment>Don&#39;t show</b:comment></b:includable>
                            <b:includable id='iframeComments' var='post'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
                            <b:includable id='inlineAd' var='post'>
                <div>
                    <b:class cond='data:post.adNumber + data:numDesktopAds lt data:maxNumAds' name='desktop-ad'/>
                    <b:class cond='data:post.adNumber + data:numMobileAds lt data:maxNumAds' name='mobile-ad'/>
                    <b:include data='post' name='super.inlineAd'/>
                </div>
            </b:includable>
                            <b:includable id='nextPageLink'>
                <a class='blog-pager-older-link flat-button ripple' expr:href='data:olderPageUrl' expr:title='data:messages.morePosts'>
                    <data:messages.morePosts/>
                </a>
            </b:includable>
                            <b:includable id='post' var='post'>
  <div class='post'>
    <b:include data='post' name='postMeta'/>
    <b:include data='post' name='postTitle'/>
    <b:include name='headerByline'/>
    <b:if cond='data:view.isSingleItem'>
      <b:include data='post' name='postBody'/>
    <b:else/>
      <b:include data='post' name='postBodySnippet'/>
      <b:include data='post' name='postJumpLink'/>
    </b:if>
    <b:include data='post' name='postFooter'/>
  </div>
</b:includable>
                            <b:includable id='postBody' var='post'>
  <!-- If metaDescription is empty, use the post body as the schema.org description too, for G+/FB snippeting. -->
  <div class='post-body entry-content float-container' expr:id='&quot;post-body-&quot; + data:post.id'>
    <data:post.body/>
  </div>
</b:includable>
                            <b:includable id='postBodySnippet' var='post'>
                <div class='container post-body entry-content' expr:id='&quot;post-snippet-&quot; + data:post.id'>

                    <b:if cond='data:post.featuredImage'>
                        <div class='snippet-thumbnail'>
                            <b:include data='{                                     image: data:post.featuredImage,                                     imageSizes: [32, 64, 128, 256],                                     imageRatio: &quot;1:1&quot;,                                     sourceSizes: &quot;(max-width: 800px) 20vw, 128px&quot;                                  }' name='responsiveImage'/>
                        </div>
                    </b:if>
                    <b:include cond='data:post' data='post' name='postSnippet'/>
                </div>
            </b:includable>
                            <b:includable id='postCommentsAndAd' var='post'>
  <article class='post-outer-container'>
    <!-- Post title and body -->
    <div class='post-outer'>
      <b:include data='post' name='post'/>
    </div>

    <!-- Comments -->
    <b:include cond='data:view.isSingleItem' data='post' name='commentPicker'/>

    <!-- Show ad inside post container, after comments, if single item. -->
    <b:include cond='data:view.isSingleItem and data:post.includeAd' data='post' name='inlineAd'/>
  </article>

  <!-- Show ad outside post container (between posts) for feed pages. -->
  <b:include cond='data:view.isMultipleItems and data:post.includeAd' data='post' name='inlineAd'/>
</b:includable>
                            <b:includable id='postCommentsLink'>
  <b:if cond='data:view.isMultipleItems'>
    <span class='byline post-comment-link container'>
      <b:include cond='data:post.commentSource != 1' name='commentsLink'/>
    </span>
  </b:if>
</b:includable>
                            <b:includable id='postFooter' var='post'>
                <div class='post-bottom'>
                    <div class='post-footer float-container'>
                        <b:include name='footerBylines'/>
                        <b:include cond='data:widget.type == &quot;Blog&quot;' data='post' name='postFooterAuthorProfile'/>
                    </div>
                    <b:if cond='data:view.isSingleItem'>
                        <b:include data='{ shareButtonClass: &quot;post-share-buttons-bottom invisible&quot;, overridden: true }' name='maybeAddShareButtons'/>
                        <b:else/>
                        <b:include data='post' name='postFooterJumpLink'/>
                    </b:if>
                </div>
            </b:includable>
                            <b:includable id='postFooterAuthorProfile' var='post'>
  <b:if cond='data:post.author.aboutMe and data:view.isPost'>
    <div class='author-profile'>
      <b:if cond='data:post.author.authorPhoto.url'>
        <img class='author-image' expr:src='data:post.author.authorPhoto.url' width='50px'/>
        <div class='author-about'>
          <b:include data='post' name='aboutPostAuthor'/>
        </div>
      <b:else/>
        <b:include data='post' name='aboutPostAuthor'/>
      </b:if>
    </div>
  </b:if>
</b:includable>
                            <b:includable id='postFooterJumpLink'>
                <b:comment>Ripple, and show &#39;keep reading&#39; as the default.</b:comment>
                <div class='jump-link flat-button ripple'>
                    <a expr:href='data:post.hasJumpLink ? data:post.url fragment &quot;more&quot; : data:post.url' expr:title='data:post.title'>
                        <data:blog.jumpLinkMessage/>
                    </a>
                </div>
            </b:includable>
                            <b:includable id='postHeader' var='post'>
  <b:include name='headerByline'/>
</b:includable>
                            <b:includable id='postJumpLink'>
                <b:comment>Overridden, and migrated to postFooter. Called as postFooterJumpLink.</b:comment>
            </b:includable>
                            <b:includable id='postLabels'>
                <b:comment>We don&#39;t display labels on the home page.</b:comment>
                <b:if cond='data:view.isSingleItem and data:widget.type == &quot;Blog&quot;'>
                    <b:include name='super.postLabels'/>
                </b:if>
            </b:includable>
                            <b:includable id='postMeta' var='post'>
  <b:include data='post' name='postMetadataJSON'/>
</b:includable>
                            <b:includable id='postPagination'>
  <div class='blog-pager container' id='blog-pager'>
    <b:include cond='data:newerPageUrl' name='previousPageLink'/>
    <b:include cond='data:olderPageUrl' name='nextPageLink'/>
    <b:include cond='data:view.url != data:blog.homepageUrl' name='homePageLink'/>
  </div>
</b:includable>
                            <b:includable id='postShareButtons' var='post'>
                <b:comment>We call super.postShareButtons from the migrated positions.</b:comment>
            </b:includable>
                            <b:includable id='postTitle' var='post'>
  <a expr:name='data:post.id'/>
  <b:if cond='data:post.title != &quot;&quot;'>
    <h3 class='post-title entry-title'>
      <b:if cond='data:post.link or (data:post.url and data:view.url != data:post.url)'>
        <a expr:href='data:post.link ?: data:post.url'><data:post.title/></a>
      <b:else/>
        <data:post.title/>
      </b:if>
    </h3>
  </b:if>
</b:includable>
                            <b:includable id='previousPageLink'><b:comment>Don&#39;t show</b:comment></b:includable>
                            <b:includable id='snippetedPostByline'>
                <b:include name='headerByline'/>
            </b:includable>
                            <b:includable id='threadedCommentForm' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <h4 id='comment-post-message'><data:messages.postAComment/></h4>
    <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
      <p><data:this.messages.blogComment/></p>
    </b:if>
    <b:include data='post' name='commentFormIframeSrc'/>
    <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
                            <b:includable id='threadedCommentJs' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
  <b:template-script inline='true' name='threaded_comments'/>
  <script type='text/javascript'>
    blogger.widgets.blog.initThreadedComments(
        <data:post.commentJso/>,
        <data:post.commentMsgs/>,
        <data:post.commentConfig/>);
  </script>
</b:includable>
                            <b:includable id='threadedComments' var='post'>
  <section class='comments threaded' expr:data-embed='data:post.embedCommentForm' expr:data-num-comments='data:post.numberOfComments' id='comments'>
    <a name='comments'/>

    <b:include name='commentsTitle'/>

    <div class='comments-content'>
      <b:if cond='data:post.embedCommentForm'>
        <b:include data='post' name='threadedCommentJs'/>
      </b:if>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threadedCommentForm'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
      <b:if cond='data:post.showManageComments'>
        <b:include data='post' name='manageComments'/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>
  </section>
</b:includable>
                          </b:widget>
                          <b:widget id='PopularPosts1' locked='true' title='' type='PopularPosts' visible='true'>
                            <b:widget-settings>
                              <b:widget-setting name='numItemsToShow'>3</b:widget-setting>
                              <b:widget-setting name='showThumbnails'>true</b:widget-setting>
                              <b:widget-setting name='showSnippets'>true</b:widget-setting>
                              <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main' var='this'>
                <b:comment>Default the title to &#39;Popular posts from this blog&#39;.</b:comment>
                <b:with value='data:messages.popularPostsFromThisBlog' var='defaultTitle'>
                    <b:include name='super.main'/>
                </b:with>
            </b:includable>
                            <b:includable id='commentsLink'>
                <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
                    <b:include data='{ iconClass: &quot;touch-icon&quot; }' name='commentIcon'/>
                    <span class='num_comments'>
              <b:if cond='data:post.numberOfComments &gt; 0'>
                <b:message name='messages.numberOfComments'>
                  <b:param expr:value='data:post.numberOfComments' name='numComments'/>
                </b:message>
              <b:else/>
                <data:messages.postAComment/>
              </b:if>
            </span>
                </a>
            </b:includable>
                            <b:includable id='postFooter' var='post'>
                <div class='post-bottom'>
                    <div class='post-footer float-container'>
                        <b:include name='footerBylines'/>
                        <b:include cond='data:widget.type == &quot;Blog&quot;' data='post' name='postFooterAuthorProfile'/>
                    </div>
                    <b:if cond='data:view.isSingleItem'>
                        <b:include data='{ shareButtonClass: &quot;post-share-buttons-bottom invisible&quot;, overridden: true }' name='maybeAddShareButtons'/>
                        <b:else/>
                        <b:include data='post' name='postFooterJumpLink'/>
                    </b:if>
                </div>
            </b:includable>
                            <b:includable id='postFooterJumpLink'>
                <b:comment>Ripple, and show &#39;keep reading&#39; as the default.</b:comment>
                <div class='jump-link flat-button ripple'>
                    <a expr:href='data:post.hasJumpLink ? data:post.url fragment &quot;more&quot; : data:post.url' expr:title='data:post.title'>
                        <data:blog.jumpLinkMessage/>
                    </a>
                </div>
            </b:includable>
                            <b:includable id='postJumpLink'>
                <b:comment>Overridden, and migrated to postFooter. Called as postFooterJumpLink.</b:comment>
            </b:includable>
                            <b:includable id='postLabels'>
                <b:comment>We don&#39;t display labels on the home page.</b:comment>
                <b:if cond='data:view.isSingleItem and data:widget.type == &quot;Blog&quot;'>
                    <b:include name='super.postLabels'/>
                </b:if>
            </b:includable>
                            <b:includable id='postShareButtons' var='post'>
                <b:comment>We call super.postShareButtons from the migrated positions.</b:comment>
            </b:includable>
                            <b:includable id='snippetedPostByline'>
                <b:include name='headerByline'/>
            </b:includable>
                            <b:includable id='snippetedPostContent'>
                <b:comment>Add a &#39;keep reading&#39; link to the item-content.</b:comment>
                <b:include name='snippetedPostTitle'/>
                <b:include name='snippetedPostByline'/>
                <div class='item-content float-container'>
                    <b:include cond='data:this.postDisplay.showFeaturedImage and data:post.featuredImage' name='snippetedPostThumbnail'/>
                    <b:if cond='data:this.postDisplay.showSnippet'>
                        <b:with value='&quot;popular-posts&quot;' var='snippetPrefix'>
                            <b:include cond='data:post' data='post' name='postSnippet'/>
                        </b:with>
                    </b:if>
                    <b:include data='post' name='postFooterJumpLink'/>
                </div>
            </b:includable>
                          </b:widget>
                        </b:section>
                    </main>
                </div>
                <b:section class='footer' id='footer' name='Footer' showaddelement='false' tag='footer'>
                  <b:widget id='Attribution1' locked='true' title='' type='Attribution' visible='true'>
                    <b:widget-settings>
                      <b:widget-setting name='copyright'/>
                    </b:widget-settings>
                    <b:includable id='main' var='this'>
  <div class='widget-content'>
    <div class='blogger'>
      <a expr:href='data:bloggerUrl' rel='nofollow'>
        <b:include name='flatBloggerIcon'/>
        <b:message name='messages.poweredByBlogger'/>
      </a>
    </div>

    <b:if cond='data:imageAuthor'>
      <div class='image-attribution'>
        <b:if cond='data:imageAuthor.url'>
          <b:message name='messages.templateImagesByLink'>
            <b:param expr:value='data:imageAuthor.url'/>
            <b:param expr:value='data:imageAuthor.name'/>
          </b:message>
        <b:else/>
          <b:message name='messages.templateImagesBy'>
            <b:param expr:value='data:imageAuthor.name'/>
          </b:message>
        </b:if>
      </div>
    </b:if>

    <b:if cond='data:copyright != &quot;&quot;'>
      <div class='copyright'><data:copyright/></div>
    </b:if>
  </div>
</b:includable>
                  </b:widget>
                </b:section>
            </div>
        </div>
    </b:with>
</div>
<aside class='sidebar-container container sidebar-invisible' role='complementary'>
    <div class='navigation'>
        <b:include data='{ button: true, iconClass: &quot;flat-icon-button ripple sidebar-back&quot; }' name='backArrowIcon'/>
    </div>
    <div class='sidebar_top_wrapper'>
        <b:class cond='data:widgets none w =&gt; w.sectionId == &quot;sidebar_top&quot;' name='no-items'/>

        <b:section class='sidebar_top' id='sidebar_top' name='Sidebar (Top)'>
          <b:widget id='Profile1' locked='true' title='About Me' type='Profile' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='showaboutme'>true</b:widget-setting>
              <b:widget-setting name='showlocation'>false</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
                <div class='wrapper'>
                    <b:class cond='!data:this.team' name='solo'/>
                    <b:comment>No title for single profiles. Default to &#39;Blog authors&#39; for team.</b:comment>
                    <b:with value='data:messages.blogAuthors' var='defaultTitle'>
                        <b:include cond='data:this.team' name='widget-title'/>
                    </b:with>
                    <b:include name='content'/>
                </div>
            </b:includable>
            <b:includable id='authorProfileImage'>
  <img class='profile-img' expr:alt='data:messages.myPhoto' expr:height='data:authorPhoto.height' expr:src='data:authorPhoto.image' expr:width='data:authorPhoto.width'/>
</b:includable>
            <b:includable id='content'>
  <b:if cond='data:team'>
    <div class='widget-content team'>
      <b:include name='teamProfile'/>
    </div>
  <b:else/>
    <div class='widget-content individual'>
      <b:include name='userProfile'/>
    </div>
  </b:if>
</b:includable>
            <b:includable id='defaultProfileImage'>
                <div class='default-avatar-wrapper'>
                    <b:include data='{ iconClass: &quot;avatar-icon&quot; }' name='defaultAvatarIcon'/>
                </div>
            </b:includable>
            <b:includable id='profileImage'>
  <b:if cond='data:authorPhoto.image'>
    <b:include name='authorProfileImage'/>
  <b:else/>
    <b:include name='defaultProfileImage'/>
  </b:if>
</b:includable>
            <b:includable id='teamProfile'>
  <ul>
    <b:loop values='data:authors' var='author'>
      <li>
        <div class='team-member'>
          <b:include data='author' name='teamProfileLink'/>
        </div>
      </li>
    </b:loop>
  </ul>
</b:includable>
            <b:includable id='teamProfileLink'>
  <a class='profile-link g-profile' expr:href='data:userUrl' rel='nofollow'>
    <b:include name='profileImage'/>
    <span class='profile-name'><data:display-name/></span>
  </a>
</b:includable>
            <b:includable id='userLocation'>
  <dd class='profile-data location'><data:location/></dd>
</b:includable>
            <b:includable id='userProfile'>
  <b:include name='userProfileImage'/>
  <b:include name='userProfileInfo'/>
</b:includable>
            <b:includable id='userProfileData'>
  <dt class='profile-data'>
    <a class='profile-link g-profile' expr:href='data:userUrl' rel='author nofollow'>
      <data:displayname/>
    </a>
  </dt>
</b:includable>
            <b:includable id='userProfileImage'>
  <a expr:href='data:userUrl' rel='nofollow'>
    <b:include name='profileImage'/>
  </a>
</b:includable>
            <b:includable id='userProfileInfo'>
  <div class='profile-info'>
    <dl class='profile-datablock'>
      <b:class cond='data:showlocation and data:location != &quot;&quot;' name='has-location'/>

      <b:include name='userProfileData'/>
      <b:include cond='data:showlocation and data:location != &quot;&quot;' name='userLocation'/>
      <b:include cond='data:aboutme != &quot;&quot;' name='userProfileText'/>
    </dl>
    <b:include name='viewProfileLink'/>
  </div>
</b:includable>
            <b:includable id='userProfileText'>
                <dd class='profile-textblock profile-snippet snippet-container r-snippet-container'>
                    <div class='snippet-item r-snippetized'>
                        <data:aboutme/>
                    </div>
                    <div class='snippet-fade r-snippet-fade hidden'/>
                </dd>
            </b:includable>
            <b:includable id='viewProfileLink'>
                <b:comment>Change link to &#39;visit profile&#39;</b:comment>
                <a class='profile-link visit-profile pill-button' rel='author'>
                    <data:messages.visitProfile/>
                </a>
            </b:includable>
          </b:widget>
        </b:section>
    </div>
    <b:section class='sidebar_bottom' id='sidebar_bottom' name='Sidebar (Bottom)' preferred='yes'>
      <b:widget id='BlogArchive1' locked='false' title='' type='BlogArchive' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='showStyle'>MENU</b:widget-setting>
          <b:widget-setting name='yearPattern'>yyyy</b:widget-setting>
          <b:widget-setting name='showWeekEnd'>true</b:widget-setting>
          <b:widget-setting name='monthPattern'>MMMM yyyy</b:widget-setting>
          <b:widget-setting name='dayPattern'>MMM dd</b:widget-setting>
          <b:widget-setting name='weekPattern'>MM/dd</b:widget-setting>
          <b:widget-setting name='chronological'>false</b:widget-setting>
          <b:widget-setting name='showPosts'>false</b:widget-setting>
          <b:widget-setting name='frequency'>MONTHLY</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main' var='this'>
                <details class='collapsible extendable'>
                    <b:attr cond='data:view.isArchive' name='open' value='open'/>
                    <b:with value='true' var='renderAsDetails'>
                        <b:with value='data:messages.archive' var='defaultTitle'>
                            <b:include name='super.main'/>
                        </b:with>
                    </b:with>
                </details>
            </b:includable>
        <b:includable id='content'>
  <div class='widget-content'>
    <div id='ArchiveList'>
      <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
        <b:include cond='data:this.style == &quot;HIERARCHY&quot;' name='hierarchy'/>
        <b:include cond='data:this.style in {&quot;FLAT&quot;, &quot;MENU&quot;}' name='flat'/>
      </div>
    </div>
  </div>
</b:includable>
        <b:includable id='flat'>
                <b:include data='{                               buttonClass: &quot;pill-button&quot;,                               items: data:this.data,                               itemSet: &quot;data&quot;,                               itemsMarkup: &quot;super.flat&quot;                             }' name='extendableItems'/>
            </b:includable>
        <b:includable id='hierarchy'>
                <b:include data='{                               buttonClass: &quot;pill-button&quot;,                               limit: 1,                               items: data:this.data,                               itemSet: &quot;data&quot;,                               itemsMarkup: &quot;super.hierarchy&quot;                             }' name='extendableItems'/>
            </b:includable>
        <b:includable id='interval' var='intervals'>
  <ul class='hierarchy'>
    <b:loop values='data:intervals' var='interval'>
      <li class='archivedate'>
        <div class='hierarchy-title'>
          <a class='post-count-link' expr:href='data:interval.url'>
            <data:interval.name/>
            <span class='post-count'><data:interval.post-count/></span>
          </a>
        </div>
        <div class='hierarchy-content'>
          <b:include cond='data:interval.data' data='interval.data' name='interval'/>
          <b:include cond='data:interval.posts' data='interval.posts' name='posts'/>
        </div>
      </li>
    </b:loop>
  </ul>
</b:includable>
        <b:includable id='posts' var='posts'>
  <ul class='posts hierarchy'>
    <b:loop values='data:posts' var='post'>
      <li>
        <a expr:href='data:post.url'><data:post.title/></a>
      </li>
    </b:loop>
  </ul>
</b:includable>
      </b:widget>
      <b:widget id='Label1' locked='false' title='Labels' type='Label' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
          <b:widget-setting name='display'>LIST</b:widget-setting>
          <b:widget-setting name='selectedLabelsList'/>
          <b:widget-setting name='showType'>ALL</b:widget-setting>
          <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main' var='this'>
                <details class='collapsible extendable'>
                    <b:attr cond='data:view.isLabelSearch' name='open' value='open'/>
                    <b:with value='true' var='renderAsDetails'>
                        <b:with value='data:messages.labels' var='defaultTitle'>
                            <b:include name='super.main'/>
                        </b:with>
                    </b:with>
                </details>
            </b:includable>
        <b:includable id='cloud'>
                <b:include data='{                               buttonClass: &quot;pill-button&quot;,                               items: data:this.labels,                               itemSet: &quot;labels&quot;,                               itemsMarkup: &quot;super.cloud&quot;                             }' name='extendableItems'/>
            </b:includable>
        <b:includable id='content'>
  <div class='widget-content'>
    <b:class expr:name='data:this.display + &quot;-label-widget-content&quot;'/>
    <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
    <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
  </div>
</b:includable>
        <b:includable id='list'>
                <b:include data='{                               buttonClass: &quot;pill-button&quot;,                               items: data:this.labels,                               itemSet: &quot;labels&quot;,                               itemsMarkup: &quot;super.list&quot;                             }' name='extendableItems'/>
            </b:includable>
      </b:widget>
      <b:widget id='ReportAbuse1' locked='true' title='' type='ReportAbuse' visible='true'>
        <b:includable id='main'>
  <b:include name='reportAbuse'/>
</b:includable>
      </b:widget>
    </b:section>
</aside>

<b:template-script async='true' name='indie' version='1.0.0'/>
</body>
</html>
