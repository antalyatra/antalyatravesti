
<!DOCTYPE html>
<html amp lang="tr">
<head>
    <meta name="google-site-verification" content="QDrA60k2nCqbAToBUiq4tdfMYwetRUMI2zz3sHe5Uyg" />
    <meta charset="UTF-8">
    <meta name="robots" content="noindex, nofollow">
    <meta name="viewport" content="width=device-width,minimum-scale=1,initial-scale=1">
    <script async src="https://cdn.ampproject.org/v0.js"></script>
    <script async custom-element="amp-bind" src="https://cdn.ampproject.org/v0/amp-bind-latest.js"></script>
    <script async custom-element="amp-script" src="https://cdn.ampproject.org/v0/amp-script-latest.js"></script>
    <script async custom-element="amp-animation" src="https://cdn.ampproject.org/v0/amp-animation-0.1.js"></script>
    <script async custom-element="amp-timer" src="https://cdn.ampproject.org/v0/amp-timer-0.1.js"></script>
    <title>AMP Resim Rastgeleleme</title>
    <style amp-custom>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
        }
        .gallery div {
            width: 150px;
            height: 150px;
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body>

<!-- Resim URL'lerini Tutacak AMP State -->
<amp-state id="images">
    <script type="application/json">
        [
            {"url": "https://esctema.xyz/antalya/kizresimleri/buse.jpg"},
            {"url": "https://esctema.xyz/antalya/kizresimleri/ruşuana.jpg"},
            {"url": "https://esctema.xyz/antalya/kizresimleri/medine.jpg"},
            {"url": "https://esctema.xyz/antalya/kizresimleri/alya.jpg"},
            {"url": "https://esctema.xyz/antalya/kizresimleri/defne.jpg"},
            {"url": "https://esctema.xyz/antalya/kizresimleri/sofia.jpg"}
        ]
    </script>
</amp-state>

<!-- Resimleri Gösteren Galeri -->
<div class="gallery">
    <template type="amp-mustache">
        {{#images}}
        <div style="background-image: url({{url}});"></div>
        {{/images}}
    </template>
</div>

<!-- Zamanlayıcı -->
<amp-timer
    interval="5" <!-- 5 saniyede bir rastgele sıralama yapılır -->
    on="timeout:AMP.setState({images: images.sort(() => Math.random() - 0.5)})"
>
</amp-timer>

</body>
</html>
<html amp="" lang="tr" amp-version="2410081535000" class="i-amphtml-singledoc i-amphtml-standalone"><head>
<meta http-equiv="content-type" content="text/html; charset=UTF-8">
 <script custom-element="amp-analytics" src="https://cdn.ampproject.org/v0/amp-analytics-latest.js" async></script>
 <title>Modeller</title>

  <link rel="preload" as="script" href="https://cdn.ampproject.org/v0.js">
  <script custom-element="amp-bind" src="https://cdn.ampproject.org/v0/amp-bind-latest.js" async></script>
  <script src="https://cdn.ampproject.org/v0.js" async></script>
 
        <style amp-boilerplate="">
            body {
                -webkit-animation: -amp-start 8s steps(1,end) 0s 1 normal both;
                -moz-animation: -amp-start 8s steps(1,end) 0s 1 normal both;
                -ms-animation: -amp-start 8s steps(1,end) 0s 1 normal both;
                animation: -amp-start 8s steps(1,end) 0s 1 normal both
            }

            @-webkit-keyframes -amp-start {
                from {
                    visibility: hidden
                }

                to {
                    visibility: visible
                }
            }

            @-moz-keyframes -amp-start {
                from {
                    visibility: hidden
                }

                to {
                    visibility: visible
                }
            }

            @-ms-keyframes -amp-start {
                from {
                    visibility: hidden
                }

                to {
                    visibility: visible
                }
            }

            @-o-keyframes -amp-start {
                from {
                    visibility: hidden
                }

                to {
                    visibility: visible
                }
            }

            @keyframes -amp-start {
                from {
                    visibility: hidden
                }

                to {
                    visibility: visible
                }
            }
        </style>
        <noscript>
            <style amp-boilerplate>
                body {
                    -webkit-animation: none;
                    -moz-animation: none;
                    -ms-animation: none;
                    animation: none
                }
            </style>
        </noscript>
        <style amp-custom="">
            body {
                background: #f1f1f1;
                font-size: 16px;
                line-height: 1.4;
                font-family: sans-serif
            }

            .amp-wp-post-content p, .amp-wp-content.the_content {
                font-family: sans-serif
            }

            a {
                color: #312C7E;
                text-decoration: none
            }

            .clearfix, .cb {
                clear: both
            }

            amp-iframe {
                max-width: 100%;
                margin-bottom: 20px
            }

            amp-anim {
                max-width: 100%
            }

            .amp-wp-article amp-addthis {
                display: inherit;
                margin-top: 20px;
                margin-left: -10px
            }

            amp-wistia-player {
                margin: 5px 0px
            }

            .alignleft {
                margin-right: 12px;
                margin-bottom: 5px;
                float: left
            }

            .alignright {
                float: right;
                margin-left: 12px;
                margin-bottom: 5px
            }

            .aligncenter {
                display: block;
                text-align: center;
                margin: 0 auto
            }

            #statcounter {
                width: 1px;
                height: 1px
            }

            ol, ul {
                list-style-position: inside
            }

            .hide {
                display: none
            }

            .amp-wp-content, .amp-wp-title-bar div {
                max-width: 1000px;
                margin: 0 auto
            }

            figure.aligncenter amp-img {
                margin: 0 auto
            }

            .nav_container {
                padding: 18px 15px;
                background: #312C7E;
                color: #fff;
                text-align: center
            }

            amp-sidebar {
                width: 250px
            }

            amp-sidebar {
                background: #efefef
            }

            .amp-sidebar-image {
                line-height: 100px;
                vertical-align: middle
            }

            .amp-close-image {
                top: 15px;
                left: 225px;
                cursor: pointer
            }

            .toggle-navigationv2 ul {
                list-style-type: none;
                margin: 0;
                padding: 0
            }

            .toggle-navigationv2 ul ul li a {
                padding-left: 35px;
                background: #ffffff;
                display: inline-block
            }

            .toggle-navigationv2 ul li a {
                padding: 15px 25px;
                width: 100%;
                display: inline-block;
                background: #fafafa;
                font-size: 14px;
                border-bottom: 1px solid #efefef;
                color: #0a89c0
            }

            .close-nav {
                font-size: 12px;
                background: rgba(0,0,0,0.25);
                letter-spacing: 1px;
                display: inline-block;
                padding: 10px;
                border-radius: 100px;
                line-height: 8px;
                margin: 14px;
                color: #ffffff;
                position: relative;
                right: 0px
            }

            .close-nav:hover {
                background: rgba(0,0,0,0.45)
            }

            .toggle-navigation ul {
                list-style-type: none;
                margin: 0;
                padding: 0;
                display: inline-block;
                width: 100%
            }

            .menu-all-pages-container:after {
                content: "";
                clear: both
            }

            .toggle-navigation ul li {
                font-size: 13px;
                border-bottom: 1px solid rgba(0, 0, 0, 0.11);
                padding: 11px 0px;
                width: 25%;
                float: left;
                text-align: center;
                margin-top: 6px
            }

            .toggle-navigation ul ul {
                display: none
            }

            .toggle-navigation ul li a {
                color: #eee;
                padding: 15px
            }

            .toggle-navigation {
                display: none;
                background: #444
            }

            .toggle-text {
                color: #fff;
                font-size: 12px;
                text-transform: uppercase;
                letter-spacing: 3px;
                display: inherit;
                text-align: center
            }

            .toggle-text:before {
                content: "...";
                font-size: 32px;
                font-family: georgia;
                line-height: 0px;
                margin-left: 0px;
                letter-spacing: 1px;
                top: -3px;
                position: relative;
                padding-right: 10px
            }

            .nav_container:hover + .toggle-navigation, .toggle-navigation:hover, .toggle-navigation:active, .toggle-navigation:focus {
                display: inline-block;
                width: 100%
            }

            .category-widget-wrapper {
                padding: 30px 15% 10px 15%
            }

            .amp-category-block ul {
                list-style-type: none;
                padding: 0
            }

            .amp-category-block-btn {
                display: block;
                text-align: center;
                font-size: 13px;
                margin-top: 15px;
                border-bottom: 1px solid #f1f1f1;
                text-decoration: none;
                padding-bottom: 8px
            }

            .category-widget-gutter h4 {
                margin-bottom: 0px
            }

            .category-widget-gutter ul {
                margin-top: 10px;
                list-style-type: none;
                padding: 0
            }

            .amp-category-post {
                width: 32%;
                display: inline-block;
                word-wrap: break-word;
                float: left
            }

            .amp-category-post amp-img {
                margin-bottom: 5px
            }

            .amp-category-block li:nth-child(3) {
                margin: 0 1%
            }

            .searchmenu {
                right: 15px
            }

            .searchmenu {
                top: 31%;
                position: absolute
            }

            .searchmenu button {
                background: transparent;
                border: none
            }

            .closebutton {
                background: transparent;
                border: 0;
                color: rgba(255, 255, 255, 0.7);
                border: 1px solid rgba(255, 255, 255, 0.7);
                border-radius: 30px;
                width: 32px;
                height: 32px;
                font-size: 12px;
                text-align: center;
                position: absolute;
                top: 12px;
                right: 20px;
                outline: none
            }

            amp-lightbox {
                background: rgba(0, 0, 0,0.85)
            }

            [class*=icono-]:after, [class*=icono-]:before {
                content: '';
                pointer-events: none
            }

            .icono-search:before {
                position: absolute;
                left: 50%;
                -webkit-transform: rotate(270deg);
                -ms-transform: rotate(270deg);
                transform: rotate(270deg);
                width: 2px;
                height: 9px;
                box-shadow: inset 0 0 0 32px;
                top: 0px;
                border-radius: 0 0 1px 1px;
                left: 14px
            }

            [class*=icono-] {
                display: inline-block;
                vertical-align: middle;
                position: relative;
                font-style: normal;
                color: #f42;
                text-align: left;
                text-indent: -9999px;
                direction: ltr
            }

            .headerlogo a, [class*=icono-] {
                color: #FF0000
            }

            .amp-wp-content.pagination-holder {
                background: none;
                padding: 0;
                box-shadow: none;
                height: auto;
                min-height: auto
            }

            #pagination {
                width: 100%;
                margin-top: 15px
            }

            #pagination .next {
                float: right;
                max-width: 50%;
                text-align: right
            }

            #pagination .prev {
                float: left;
                max-width: 50%
            }

            #pagination .next a, #pagination .prev a {
                margin-bottom: 12px;
                -moz-border-radius: 2px;
                -webkit-border-radius: 2px;
                border-radius: 2px;
                -moz-box-shadow: 0 2px 3px rgba(0,0,0,.05);
                -webkit-box-shadow: 0 2px 3px rgba(0,0,0,.05);
                box-shadow: 0 2px 3px rgba(0,0,0,.05);
                padding: 11px 15px;
                font-size: 12px
            }

            #pagination .next a, #pagination .prev a {
                color: #666666;
                background: #fefefe;
                display: inline-block
            }

            header.container {
                line-height: 0
            }

            #header {
                background: #000000;
                text-align: center;
                padding: 17px 0px 17px 0px;
                display: inline-block;
                width: 100%;
                position: relative
            }

            #header h1 {
                text-align: center;
                font-size: 20px;
                font-weight: bold;
                line-height: 1;
                padding: 4px 3px;
                margin: 0
            }

            .amp-logo {
                left: 0;
                right: 0;
                display: inline-block
            }

            .amp-logo amp-img {
                margin: 15px 0px 10px 0px
            }

            .amp-logo amp-img {
                margin: 0 auto
            }

            main {
                padding: 30px 15% 10px 15%
            }

            .amp-wp-content.widget-wrapper {
                padding: 12px 10px 10px 10px
            }

            main .amp-wp-content {
                margin-bottom: 12px;
                padding: 15px
            }

            .amp-loop-list, .featured-image-content, .the_content, .taxonomy-description, .taxonomy-image {
                background: #fff;
                -moz-border-radius: 2px;
                -webkit-border-radius: 2px;
                border-radius: 2px;
                -moz-box-shadow: 0 2px 3px rgba(0,0,0,.05);
                -webkit-box-shadow: 0 2px 3px rgba(0,0,0,.05);
                box-shadow: 0 2px 3px rgba(0,0,0,.05)
            }

            .home-post_image {
                float: right;
                margin-left: 15px;
                margin-bottom: -6px
            }

            .amp-wp-title {
                margin-top: 0px
            }

            h2.amp-wp-title, h3.amp-wp-title {
                line-height: 30px
            }

            h2.amp-wp-title a, h3.amp-wp-title a {
                font-weight: 300;
                color: #000;
                font-size: 20px
            }

            h2.amp-wp-title, h3.amp-wp-title, .amp-wp-post-content p {
                margin: 0 0 0 5px;
                word-wrap: break-word
            }

            .amp-wp-post-content .large-screen-excerpt, .amp-wp-post-content .small-screen-excerpt {
                display: block
            }

            .amp-wp-post-content p {
                font-size: 12px;
                color: #999;
                line-height: 20px;
                margin: 3px 0 0 5px
            }

            main .amp-archive-heading {
                background: none;
                box-shadow: none;
                padding: 5px
            }

            .amp-sub-archives li {
                width: 50%
            }

            .amp-sub-archives ul {
                padding: 0;
                list-style: none;
                display: flex;
                font-size: 12px;
                line-height: 1.2;
                margin: 5px 0 10px 0px
            }

            .page-title {
                font-size: 1.17em;
                padding: 6px 0
            }

            #footer {
                background: #FFFFFF;
                font-size: 13px;
                text-align: center;
                letter-spacing: 0.2px;
                padding: 20px 0;
                color: #222222
            }

            #footer a {
                color: #0074A7
            }

            #footer p:first-child {
                margin-bottom: 12px
            }

            #footer p {
                margin: 0
            }

            .footer_menu ul {
                list-style-type: none;
                padding: 0;
                text-align: center;
                margin: 0px 20px 25px 20px;
                line-height: 27px;
                font-size: 13px
            }

            .footer_menu ul li {
                display: inline;
                margin: 0 10px
            }

            .footer_menu ul li:first-child {
                margin-left: 0
            }

            .footer_menu ul li:last-child {
                margin-right: 0
            }

            .footer_menu ul ul {
                display: none
            }

            a.btt:hover {
                cursor: pointer
            }

            .nav_container {
                background: rgba(0,116,167,1)
            }

            .nav_container a, .nav_container a:hover, .nav_container a:focus {
                color: #ffffff
            }

            .amp-facebook-comments {
                margin-top: 45px
            }

            .amp_home_body .amp_ad_1 {
                margin-top: 10px;
                margin-bottom: -20px
            }

            .single-post .amp_ad_1 {
                margin-top: 10px;
                margin-bottom: -20px
            }

            html .single-post .ampforwp-incontent-ad-1 {
                margin-bottom: 10px
            }

            .amp-ad-4 {
                margin-top: 10px
            }

            .amp-wp-content blockquote {
                border-left: 3px solid;
                margin: 0;
                padding: 15px 20px 8px 24px;
                background: #f3f3f3
            }

            pre {
                white-space: pre-wrap
            }

            table {
                display: -webkit-box;
                display: -ms-flexbox;
                display: flex;
                -ms-flex-wrap: wrap;
                flex-wrap: wrap;
                overflow-x: auto
            }

            table a:link {
                font-weight: bold;
                text-decoration: none
            }

            table a:visited {
                color: #999999;
                font-weight: bold;
                text-decoration: none
            }

            table a:active,table a:hover {
                color: #bd5a35;
                text-decoration: underline
            }

            table {
                color: #666;
                font-size: 12px;
                text-shadow: 1px 1px 0px #fff;
                background: inherit;
                margin: 0px;
                width: 95%
            }

            table th {
                padding: 21px 25px 22px 25px;
                border-top: 1px solid #fafafa;
                border-bottom: 1px solid #e0e0e0;
                background: #ededed;
                background: -webkit-gradient(linear, left top, left bottom, from(#ededed), to(#ebebeb));
                background: -moz-linear-gradient(top, #ededed, #ebebeb)
            }

            table th:first-child {
                text-align: left;
                padding-left: 20px
            }

            table tr:first-child th:first-child {
                -moz-border-radius-topleft: 3px;
                -webkit-border-top-left-radius: 3px;
                border-top-left-radius: 3px
            }

            table tr:first-child th:last-child {
                -moz-border-radius-topright: 3px;
                -webkit-border-top-right-radius: 3px;
                border-top-right-radius: 3px
            }

            table tr {
                text-align: center;
                padding-left: 20px;
                border: 2px solid #eee
            }

            table td:first-child {
                text-align: left;
                padding-left: 20px;
                border-left: 0
            }

            table td {
                padding: 18px;
                border-top: 1px solid #ffffff;
                border-bottom: 1px solid #e0e0e0;
                border-left: 1px solid #e0e0e0;
                background: #fafafa;
                background: -webkit-gradient(linear, left top, left bottom, from(#fbfbfb), to(#fafafa));
                background: -moz-linear-gradient(top, #fbfbfb, #fafafa)
            }

            table tr.even td {
                background: #f6f6f6;
                background: -webkit-gradient(linear, left top, left bottom, from(#f8f8f8), to(#f6f6f6));
                background: -moz-linear-gradient(top, #f8f8f8, #f6f6f6)
            }

            table tr:last-child td {
                border-bottom: 0
            }

            table tr:last-child td:first-child {
                -moz-border-radius-bottomleft: 3px;
                -webkit-border-bottom-left-radius: 3px;
                border-bottom-left-radius: 3px
            }

            table tr:last-child td:last-child {
                -moz-border-radius-bottomright: 3px;
                -webkit-border-bottom-right-radius: 3px;
                border-bottom-right-radius: 3px
            }

            table tr:hover td {
                background: #f2f2f2;
                background: -webkit-gradient(linear, left top, left bottom, from(#f2f2f2), to(#f0f0f0));
                background: -moz-linear-gradient(top, #f2f2f2, #f0f0f0)
            }

            .hide-meta-info {
                display: none
            }

            @media screen and (min-width: 650px) {
                table {
                    display:inline-table
                }
            }

            @media screen and (max-width: 800px) {
                .single-post main {
                    padding:12px 10px 10px 10px
                }
            }

            @media screen and (max-width: 630px) {
                .related_link {
                    margin:16px 18px 20px 19px
                }

                .amp-category-post {
                    line-height: 1.45;
                    font-size: 14px
                }

                .amp-category-block li:nth-child(3) {
                    margin: 0 0.6%
                }
            }

            @media screen and (max-width: 510px) {
                .ampforwp-tax-category span {
                    display:none
                }

                .rp ol li p {
                    line-height: 1.6;
                    margin: 7px 0 0 0
                }

                .rp .related_link {
                    margin: 17px 18px 17px 19px
                }

                .cmts_list ul li .cmt-body {
                    width: auto
                }
            }

            @media screen and (max-width: 425px) {
                .alignright, .alignleft {
                    float:none
                }

                .rp .related_link {
                    margin: 13px 18px 14px 19px
                }

                .rp .related_link a {
                    font-size: 18px;
                    line-height: 1.7
                }

                .amp-meta-wrapper {
                    display: inline-block;
                    margin-bottom: 0px;
                    margin-top: 8px;
                    width: 100%
                }

                .ampforwp-tax-category {
                    padding-bottom: 0
                }

                h1.amp-wp-title {
                    margin: 16px 0px 13px 0px
                }

                .amp-wp-byline {
                    padding: 0
                }

                .rp .related_link a {
                    font-size: 17px;
                    line-height: 1.5
                }

                .amp-wp-post-content .large-screen-excerpt, .related_link .large-screen-excerpt {
                    display: none
                }
            }

            @media screen and (max-width: 375px) {
                #pagination .next a, #pagination .prev a {
                    padding:10px 6px;
                    font-size: 11px;
                    color: #666
                }

                .rp .related-title, .cmts_list h3 {
                    margin-top: 15px
                }

                #pagination .next {
                    margin-bottom: 15px
                }

                .rp .related_link a {
                    font-size: 15px;
                    line-height: 1.6
                }
            }

            @media screen and (max-width: 340px) {
                .rp .related_link a {
                    font-size:15px
                }

                .single-post main {
                    padding: 10px 5px 10px 5px
                }

                .the_content .amp-ad-wrapper {
                    text-align: center;
                    margin-left: -13px
                }

                .amp-category-post {
                    line-height: 1.45;
                    font-size: 12px
                }

                .amp-category-block li:nth-child(3) {
                    margin: 0%
                }
            }

            @media screen and (max-width: 320px) {
                .rp .related_link a {
                    font-size:13px
                }

                h1.amp-wp-title {
                    font-size: 17px;
                    padding: 0px 4px
                }
            }

            @media screen and (max-width: 400px) {
                .amp-wp-title {
                    font-size:19px;
                    margin: 21px 10px -1px 10px
                }
            }

            @media screen and (max-width: 767px) {
                .amp-wp-post-content .small-screen-excerpt {
                    display:block
                }

                main, .amp-category-block, .category-widget-wrapper {
                    padding: 15px 18px 0px 18px
                }

                .toggle-navigation ul li {
                    width: 50%
                }

                #pagination .next {
                    width: 100%
                }

                #pagination .prev {
                    float: none;
                    width: 100%
                }
            }

            @media screen and (max-width: 495px) {
                h2.amp-wp-title a {
                    font-size:17px;
                    line-height: 26px
                }
            }

            .amp-wp-tax-tag a, a, .amp-wp-author, .headerlogo a, [class*=icono-] {
                color: #FF0000	;
            }

            body a {
                  color: #FF0000
            }

            .amp-wp-content blockquote {
                border-color: #FF0000	;
            }

            .cmt-button-wrapper a {
                background: #0a89c0;
            }

            amp-user-notification {
                border-color: #0a89c0;
            }

            amp-user-notification button {
                background-color: #0a89c0;
            }

            .amp-wp-author:before {
                content: " Taraf&#305;ndan "
            }

            .ampforwp-tax-category span:first-child:after {
                content: ' '
            }

            .ampforwp-tax-category span:after,.ampforwp-tax-tag span:after {
                content: ', '
            }

            .ampforwp-tax-category span:last-child:after, .ampforwp-tax-tag span:last-child:after {
                content: ' '
            }

            .amp-wp-article-content img {
                max-width: 100%
            }

            .design_2_wrapper .amp-loop-list .amp-wp-meta {
                display: none
            }

            .amp-menu > li > a > amp-img, .sub-menu > li > a > amp-img {
                display: inline-block;
                margin-right: 4px
            }

            .menu-item amp-img {
                width: 16px;
                height: 11px;
                display: inline-block;
                margin-right: 5px
            }

            .amp-carousel-container {
                position: relative;
                width: 100%;
                height: 100%
            }

            .amp-carousel-img img {
                object-fit: contain
            }

            .amp-menu li {
                position: relative;
                margin: 0
            }

            .amp-menu li.menu-item-has-children ul {
                display: none;
                margin: 0;
                background: #222
            }

            .amp-menu li.menu-item-has-children ul ul {
                background: #444
            }

            .amp-menu input {
                display: none
            }

            .amp-menu [id^=drop]:checked + label + ul {
                display: block
            }

            .amp-menu .toggle:after {
                content: '\25be';
                position: absolute;
                padding: 10px 15px 10px 30px;
                right: 0;
                font-size: 18px;
                color: #ccc;
                top: 5px;
                z-index: 10000;
                line-height: 1
            }

            .amp-ad-wrapper span {
                display: inherit;
                font-size: 12px;
                line-height: 1
            }

            @media(max-width: 480px) {
            }

            @media (min-width: 768px) {
                .wp-block-columns {
                    display:flex
                }

                .wp-block-column {
                    max-width: 50%;
                    margin: 0px 10px
                }
            }

            .amp-wp-content.the_content h1, .amp-wp-content.the_content h2, .amp-wp-content.the_content h3, .amp-wp-content.the_content h4, .amp-wp-content.the_content h5, .amp-wp-content.the_content h6 {
                margin: 15px 0px
            }

            .amp-wp-content.the_content h1 {
                font-size: 32px
            }

            .amp-wp-content.the_content h2 {
                font-size: 27px
            }

            .amp-wp-content.the_content h3 {
                font-size: 24px
            }

            .amp-wp-content.the_content h4 {
                font-size: 20px
            }

            .amp-wp-content.the_content h5 {
                font-size: 17px
            }

            .amp-wp-content.the_content h6 {
                font-size: 15px
            }

            amp-facebook-like {
                max-height: 28px
            }

            .rp .related_link a.readmore-rp {
                font-size: 13px;
                margin-left: 5px;
                color: #999;
                font-weight: normal
            }

            .link-menu .toggle {
                width: 100%;
                height: 100%;
                position: absolute;
                top: 0px;
                right: 0;
                cursor: pointer
            }

            .ampforwp-blocks-gallery-caption {
                font-size: 16px
            }

            .amp-wp-content table, .cntn-wrp.artl-cnt table {
                height: auto
            }

            amp-img.amp-wp-enforced-sizes[layout=intrinsic] > img, .amp-wp-unknown-size > img {
                object-fit: contain
            }

            .rtl amp-carousel {
                direction: ltr
            }

            .rtl .amp-menu .toggle:after {
                left: 0;
                right: unset
            }

            .sharedaddy li {
                display: none
            }

            sub {
                vertical-align: sub;
                font-size: small
            }

            sup {
                vertical-align: super;
                font-size: small
            }

            amp-call-tracking a {
                display: none
            }

            @media only screen and (max-width: 480px) {
                svg {
                    max-width:250px;
                    max-height: 250px
                }
            }

            h2.amp-post-title {
                word-break: break-word;
                word-wrap: break-word
            }

            .btt {
                position: fixed;
                bottom: 20px;
                right: 20px;
                background: rgba(71, 71, 71, 0.5);
                color: #fff;
                border-radius: 100%;
                width: 50px;
                height: 50px;
                text-decoration: none
            }

            .btt:hover {
                color: #fff;
                background: #474747
            }

            .btt:before {
                content: '\25be';
                display: block;
                font-size: 35px;
                font-weight: 600;
                color: #fff;
                transform: rotate(180deg);
                text-align: center;
                line-height: 1.5
            }

            .has-text-align-left {
                text-align: left
            }

            .has-text-align-right {
                text-align: right
            }

            .has-text-align-center {
                text-align: center
            }

            .ngy-vitrin {
                max-width: 780px;
                margin: 0 auto
            }

            .banner amp-img {
                width: 100%;
                height: 55px;
                margin-top: 5px
            }

            @keyframes left_scroll {
                from {
                    background-position: 0
                }

                to {
                    background-position: -2988px
                }
            }

            @-webkit-keyframes change {
                0% {
                    background-position-y: top
                }

                50% {
                    background-position-y: bottom
                }
            }

            @keyframes change {
                0% {
                    background-position-y: top
                }

                50% {
                    background-position-y: bottom
                }
            }

            @keyframes right_scroll {
                from {
                    background-position: 0
                }

                to {
                    background-position: +2988px
                }
            }

            @-webkit-keyframes change {
                0% {
                    background-position-y: top
                }

                50% {
                    background-position-y: bottom
                }
            }

            @keyframes change {
                0% {
                    background-position-y: top
                }

                50% {
                    background-position-y: bottom
                }
            }

            @keyframes up_scroll {
                from {
                    background-position-y: +2988px
                }

                to {
                    background-position-y: 0
                }
            }

            @-webkit-keyframes change {
                0% {
                    background-position-y: top
                }

                50% {
                    background-position-y: bottom
                }
            }

            @keyframes change {
                0% {
                    background-position-y: top
                }

                50% {
                    background-position-y: bottom
                }
            }

            @keyframes down_scroll {
                from {
                    background-position-y: -2988px
                }

                to {
                    background-position-y: 0
                }
            }

            @-webkit-keyframes change {
                0% {
                    background-position-y: top
                }

                50% {
                    background-position-y: bottom
                }
            }

            @keyframes change {
                0% {
                    background-position-y: top
                }

                50% {
                    background-position-y: bottom
                }
            }

            .animation_left {
                animation-name: left_scroll;
                background-position: center center;
                animation: 70s left_scroll infinite linear;
                -webkit-animation: 70s left_scroll infinite linear
            }

            .animation_right {
                animation-name: right_scroll;
                background-position: center center;
                animation: 70s right_scroll infinite linear;
                -webkit-animation: 70s right_scroll infinite linear
            }

            .animation_up {
                animation-name: up_scroll;
                background-position: center center;
                animation: 70s up_scroll infinite linear;
                -webkit-animation: 70s up_scroll infinite linear
            }

            .animation_bottom {
                animation-name: down_scroll;
                background-position: center center;
                animation: 70s down_scroll infinite linear;
                -webkit-animation: 70s down_scroll infinite linear
            }

            .ngy-vitrin {
                width: 100%
            }

            .ngy-resim {
                width: 100%;
                height: 160px;
                position: relative;
                background-size: auto 100%
            }

            .ngy-resim span {
                margin: 10px 0 0 15px;
                font-weight: bold;
                cursor: pointer;
                color: white
            }

            .feature {
                display: block;
                width: fit-content;
                padding: 3px 7px;
                font-size: 14px;
                border-radius: 10px
            }

            .float-left {
                float: left
            }

            .float-right {
                float: right
            }

            .isim_vip {
                background: rgba(0,150,244,0.64)
            }

            .telefon_numarasi_arama_vip {
                background: #ae00ff
            }

            .ozellikler_vip {
                background: #ffcc02
            }

            .gorusme_yeri_vip {
                background: rgba(91,15,255,0.81)
            }

            .isim_gold {
                background: rgba(0,89,255,0.64)
            }

            .telefon_numarasi_arama_gold {
                background: #ae00ff
            }

            .ozellikler_gold {
                background: rgba(99,2,255,0.74)
            }

            .gorusme_yeri_gold {
                background: rgba(35,255,15,0.81)
            }

            .isim_silver {
                background: rgba(241,58,255,0.9)
            }

            .telefon_numarasi_arama_silver {
                background: rgba(92,2,247,0.92)
            }

            .ozellikler_silver {
                background: rgba(88,188,26,0.78)
            }

            .gorusme_yeri_silver {
                background: rgba(255,40,40,0.87)
            }

            amp-web-push-widget button.amp-subscribe {
                display: inline-flex;
                align-items: center;
                border-radius: 5px;
                border: 0;
                box-sizing: border-box;
                margin: 0;
                padding: 10px 15px;
                cursor: pointer;
                outline: none;
                font-size: 15px;
                font-weight: 500;
                background: #4A90E2;
                margin-top: 7px;
                color: white;
                box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.5);
                -webkit-tap-highlight-color: rgba(0, 0, 0, 0)
            }

            .amp-logo amp-img {
                width: 52px
            }

            .amp-menu input {
                display: none
            }

            .amp-menu li.menu-item-has-children ul {
                display: none
            }

            .amp-menu li {
                position: relative;
                display: block
            }

            .amp-menu > li a {
                display: block
            }
        </style>
    <body>
    
<header class="container design2-header">
<div id="headerwrap">
                <div id="header">
                    <div class="amp-logo">
                        <a href="https://api.whatsapp.com/send?phone=380955754178&amp;text=%C4%B0lan%20vermek%20istiyorum%20%F0%9F%94%A5" title="Model">AHMET MEDYA</a>
                        <h1 class="hide">AHMET MEDYA</h1>
                    </div>
                </div>
</div>
</header>
		

            

                  
                   
    
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   


               <a target="_blank" href="https://wa.me/905511926565?text=Merhaba+Antalya+sitesinden+geliyorum+can%C4%B1m+g%C3%B6r%C3%BC%C5%9Fmek+istiyorum+m%C3%BCsait+misin%3F&amp;type=phone_number&amp;app_absent=0">
                    <div class="ngy-resim animation_right" style="background-image: url(https://vitrintema.xyz/antalyatrv/kizresimleri/idil.jpg);">
                        <span id="span1" class="feature span1 isim_vip float-right">İdil </span>
                        <div style="clear: both"></div>
                        <span id="span2" class="feature span2 ozellikler_vip float-right">Ödeme Elden </span>
                        <div style="clear: both"></div>
                        <span id="span3" class="feature span3 gorusme_yeri_vip float-right">Ev &amp;Otel &amp;Rezidans </span>
                        <div style="clear: both"></div>
                        <span id="span4" class="feature span4 telefon_numarasi_arama_vip float-left">+905511926565 </span>
                        <div style="clear: both"></div>
                    </div>
                </a>
    


                  
    

                 


                
     
 
               
                   
    

                 
</div>          



                
                  <a target="_blank" href="https://wa.me/905365857523?text=Merhaba+Antalya+sitesinden+geliyorum+can%C4%B1m+g%C3%B6r%C3%BC%C5%9Fmek+istiyorum+m%C3%BCsait+misin%3F&amp;type=phone_number&amp;app_absent=0">
                    <div class="ngy-resim animation_right" style="background-image: url(https://vitrintema.xyz/antalyatra/kizresimleri/güzel.jpg);">
                        <span id="span1" class="feature span1 isim_vip float-right">Güzel </span>
                        <div style="clear: both"></div>
                        <span id="span2" class="feature span2 ozellikler_vip float-right">Ödeme Elden </span>
                        <div style="clear: both"></div>
                        <span id="span3" class="feature span3 gorusme_yeri_vip float-right">Ev &amp;Otel &amp;Rezidans </span>
                        <div style="clear: both"></div>
                        <span id="span4" class="feature span4 telefon_numarasi_arama_vip float-left">+905365857523 </span>
                        <div style="clear: both"></div>
                    </div>


                  
                  
                  
                  
                  <a target="_blank" href="https://wa.me/905439673230?text=Merhaba+Antalya+sitesinden+geliyorum+can%C4%B1m+g%C3%B6r%C3%BC%C5%9Fmek+istiyorum+m%C3%BCsait+misin%3F&amp;type=phone_number&amp;app_absent=0">
                    <div class="ngy-resim animation_right" style="background-image: url(https://vitrintema.xyz/antalyatra/kizresimleri/cccilek.jpg);">
                        <span id="span1" class="feature span1 isim_vip float-right">Çilek </span>
                        <div style="clear: both"></div>
                        <span id="span2" class="feature span2 ozellikler_vip float-right">Ödeme Elden </span>
                        <div style="clear: both"></div>
                        <span id="span3" class="feature span3 gorusme_yeri_vip float-right">Ev &amp;Otel &amp;Rezidans </span>
                        <div style="clear: both"></div>
                        <span id="span4" class="feature span4 telefon_numarasi_arama_vip float-left">+905439673230 </span>
                        <div style="clear: both"></div>
                    </div>
                 
               
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  



            

</a>


</div>
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
           
                
               
                
                <a target="_blank" href="https://api.whatsapp.com/send?phone=380955754178&amp;text=%C4%B0lan%20vermek%20istiyorum%20%F0%9F%94%A5">
                        <amp-img layout="responsive" src="/gaziantep/images/tikla.jpg" width="200" height="80" alt="Banner" class="i-amphtml-element i-amphtml-layout-responsive i-amphtml-layout-size-defined i-amphtml-built i-amphtml-layout" i-amphtml-layout="responsive" style="--loader-delay-offset: 41ms !important;"><i-amphtml-sizer slot="i-amphtml-svc" style="padding-top: 40%;">
						</i-amphtml-sizer><img decoding="async" alt="Banner" src="GOLD%20ESCORT%20%E2%9D%A4%EF%B8%8F%20KIZLAR_dosyalar/tikla.jpg" class="i-amphtml-fill-content i-amphtml-replaced-content">
						</amp-img>
                   </a>    
           
    </a> 
    </div>
                </a>

    
    </a>
              
            </section>

        </div>


        <script type="application/ld+json">
            {
                "@context": "http:\/\/schema.org",
                "@type": "BlogPosting",
                "mainEntityOfPage": "",
                "publisher": {
                    "@type": "Organization",
                    "name": "Model",
                    "logo": {
                        "@type": "ImageObject",
                        "url": "",
                        "height": "60",
                        "width": "600"
                    }
                },
                "headline": "Model | ",
                "author": {
                    "@type": "Person",
                    "name": "admin",
                },
                "datePublished": "2024-10-13 08:14:08",
                "dateModified": "2024-10-13 08:14:10",
                "image": {
                    "@type": "ImageObject",
                    "height": 720,
                    "width": 1280
                },
                "description": ""
            }</script>
        <a id="scrollToTopButton" title="back to top" on="tap:backtotop.scrollTo(duration=500)" class="btt" href="#"></a>
        <amp-analytics type="gtag" id="analytics1" data-credentials="include" class="i-amphtml-element i-amphtml-layout-fixed i-amphtml-layout-size-defined i-amphtml-built i-amphtml-layout" style="width: 1px; height: 1px;" i-amphtml-layout="fixed" aria-hidden="true" hidden="">
            <script type="application/json">
                {
                    "vars": {
                        "gtag_id": "G-BXCJCD1VFW",
                        "config": {
                            "G-BXCJCD1VFW": {
                                "groups": "default"
                            }
                        },
                        "anonymizeIP": "true"
                    },
                    "triggers": {
                        "trackPageview": {
                            "on": "visible",
                            "request": "pageview"
                        }
                    }
                }</script>
        </amp-analytics>
    
<script>
  document.addEventListener('DOMContentLoaded', function () {
    // İlanları seçiyoruz (aynı seviyedeki tüm <a> etiketleri)
    const ilanlar = Array.from(document.querySelectorAll('a[target="_blank"]')); // WhatsApp bağlantılarını seçiyoruz

    // Rastgele sıralama fonksiyonu
    function shuffle(array) {
      for (let i = array.length - 1; i > 0; i--) {
        const j = Math.floor(Math.random() * (i + 1));
        [array[i], array[j]] = [array[j], array[i]];
      }
      return array;
    }

    // İlanları seçildiği sırayla yeniden ekliyoruz (kapsayıcı olmadan çalışır)
    const parent = ilanlar[0].parentNode; // İlk <a> etiketinin ebeveynini alıyoruz
    shuffle(ilanlar).forEach(ilan => parent.appendChild(ilan));
  });
</script> 
 
</body>
</html>
