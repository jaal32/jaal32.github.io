<html lang="en-US">
    <head>
        <meta charset="UTF-8"/>
        <meta name='viewport' content='width=device-width, initial-scale=1.0'/>
        <meta http-equiv='X-UA-Compatible' content='IE=edge'/>
        <script>
            var gform;
            gform || (document.addEventListener("gform_main_scripts_loaded", function() {
                gform.scriptsLoaded = !0
            }),
            window.addEventListener("DOMContentLoaded", function() {
                gform.domLoaded = !0
            }),
            gform = {
                domLoaded: !1,
                scriptsLoaded: !1,
                initializeOnLoaded: function(o) {
                    gform.domLoaded && gform.scriptsLoaded ? o() : !gform.domLoaded && gform.scriptsLoaded ? window.addEventListener("DOMContentLoaded", o) : document.addEventListener("gform_main_scripts_loaded", o)
                },
                hooks: {
                    action: {},
                    filter: {}
                },
                addAction: function(o, n, r, t) {
                    gform.addHook("action", o, n, r, t)
                },
                addFilter: function(o, n, r, t) {
                    gform.addHook("filter", o, n, r, t)
                },
                doAction: function(o) {
                    gform.doHook("action", o, arguments)
                },
                applyFilters: function(o) {
                    return gform.doHook("filter", o, arguments)
                },
                removeAction: function(o, n) {
                    gform.removeHook("action", o, n)
                },
                removeFilter: function(o, n, r) {
                    gform.removeHook("filter", o, n, r)
                },
                addHook: function(o, n, r, t, i) {
                    null == gform.hooks[o][n] && (gform.hooks[o][n] = []);
                    var e = gform.hooks[o][n];
                    null == i && (i = n + "_" + e.length),
                    gform.hooks[o][n].push({
                        tag: i,
                        callable: r,
                        priority: t = null == t ? 10 : t
                    })
                },
                doHook: function(n, o, r) {
                    var t;
                    if (r = Array.prototype.slice.call(r, 1),
                    null != gform.hooks[n][o] && ((o = gform.hooks[n][o]).sort(function(o, n) {
                        return o.priority - n.priority
                    }),
                    o.forEach(function(o) {
                        "function" != typeof (t = o.callable) && (t = window[t]),
                        "action" == n ? t.apply(null, r) : r[0] = t.apply(null, r)
                    })),
                    "filter" == n)
                        return r[0]
                },
                removeHook: function(o, n, t, i) {
                    var r;
                    null != gform.hooks[o][n] && (r = (r = gform.hooks[o][n]).filter(function(o, n, r) {
                        return !!(null != i && i != o.tag || null != t && t != o.priority)
                    }),
                    gform.hooks[o][n] = r)
                }
            });
        </script>
        <link rel="profile" href="https://gmpg.org/xfn/11"/>
        <title>Hank Green</title>
        <link rel="preload" as="style" href="https://fonts.googleapis.com/css?family=Source%20Serif%20Pro%3A700&#038;display=swap"/>
        <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Source%20Serif%20Pro%3A700&#038;display=swap" media="print" onload="this.media='all'"/>
        <noscript>
            <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Source%20Serif%20Pro%3A700&#038;display=swap"/>
        </noscript>
        <meta name="dc.title" content="Hank Green">
        <meta name="dc.description" content="Hank Green is the New York Times best-selling author, a science communicator, video creator, and entrepreneur. Hank Green has founded Complexly, Subbable, VidCon, and DFTBA.com. ">
        <meta name="dc.relation" content="https://hankgreen.com/">
        <meta name="dc.source" content="https://hankgreen.com/">
        <meta name="dc.language" content="en_US">
        <meta name="description" content="Hank Green is the New York Times best-selling author, a science communicator, video creator, and entrepreneur. Hank Green has founded Complexly, Subbable, VidCon, and DFTBA.com. ">
        <meta name="robots" content="index, follow">
        <meta name="googlebot" content="index, follow, max-snippet:-1, max-image-preview:large, max-video-preview:-1">
        <meta name="bingbot" content="index, follow, max-snippet:-1, max-image-preview:large, max-video-preview:-1">
        <link rel="canonical" href="https://hankgreen.com/">
        <script type="application/ld+json">
            {
                "@context": "https:\/\/schema.org",
                "@type": "WebSite",
                "name": "Hank Green",
                "alternateName": "Hank Green",
                "description": "",
                "url": "https:\/\/hankgreen.com",
                "potentialAction": {
                    "@type": "SearchAction",
                    "target": {
                        "@type": "EntryPoint",
                        "urlTemplate": "https:\/\/hankgreen.com\/?s={search_term_string}"
                    },
                    "query-input": "required name=search_term_string"
                }
            }</script>
        <meta property="og:url" content="https://hankgreen.com/">
        <meta property="og:site_name" content="Hank Green">
        <meta property="og:locale" content="en_US">
        <meta property="og:type" content="website">
        <meta property="og:title" content="Hank Green">
        <meta property="og:description" content="Hank Green is the New York Times best-selling author, a science communicator, video creator, and entrepreneur. Hank Green has founded Complexly, Subbable, VidCon, and DFTBA.com. ">
        <meta property="og:image" content="http://hankgreen.com/wp-content/uploads/2021/10/Hank-Green-1.jpg">
        <meta property="og:image:secure_url" content="http://hankgreen.com/wp-content/uploads/2021/10/Hank-Green-1.jpg">
        <meta property="og:image:width" content="600">
        <meta property="og:image:height" content="757">
        <meta property="fb:pages" content="">
        <meta property="fb:admins" content="">
        <meta property="fb:app_id" content="">
        <meta name="twitter:card" content="summary">
        <meta name="twitter:site" content="@hankgreen">
        <meta name="twitter:creator" content="@hankgreen">
        <meta name="twitter:title" content="Hank Green">
        <meta name="twitter:description" content="Hank Green is the New York Times best-selling author, a science communicator, video creator, and entrepreneur. Hank Green has founded Complexly, Subbable, VidCon, and DFTBA.com. ">
        <meta name="twitter:image" content="http://hankgreen.com/wp-content/uploads/2021/10/Hank-Green-1.jpg">
        <link rel='dns-prefetch' href='//fonts.googleapis.com'/>
        <link href='https://fonts.gstatic.com' crossorigin rel='preconnect'/>
        <link rel="alternate" type="application/rss+xml" title="Hank Green &raquo; Feed" href="https://hankgreen.com/feed/"/>
        <link rel="alternate" type="application/rss+xml" title="Hank Green &raquo; Comments Feed" href="https://hankgreen.com/comments/feed/"/>
        <script type="application/ld+json">
            {
                "@context": "https:\/\/schema.org",
                "@type": "Person",
                "name": "Hank Gree",
                "url": "https:\/\/hankgreen.com",
                "alternateName": "Hank Green",
                "description": "Hank Green",
                "sameAs": [
                    "https:\/\/www.facebook.com\/hankgreen\/",
                    "https:\/\/twitter.com\/@hankgreen",
                    "https:\/\/www.instagram.com\/hankgreen\/",
                    "https:\/\/www.youtube.com\/vlogbrothers"
                ]
            }</script>
        <link rel="preload" href="https://hankgreen.com/wp-content/plugins/bb-plugin/fonts/fontawesome/5.15.4/webfonts/fa-solid-900.woff2" as="font" type="font/woff2" crossorigin="anonymous">
        <link rel="preload" href="https://hankgreen.com/wp-content/plugins/bb-plugin/fonts/fontawesome/5.15.4/webfonts/fa-brands-400.woff2" as="font" type="font/woff2" crossorigin="anonymous">
        <link rel="preload" href="https://hankgreen.com/wp-content/plugins/bb-plugin/fonts/fontawesome/5.15.4/webfonts/fa-regular-400.woff2" as="font" type="font/woff2" crossorigin="anonymous">
        <style id='wp-emoji-styles-inline-css'>
            img.wp-smiley, img.emoji {
                display: inline !important;
                border: none !important;
                box-shadow: none !important;
                height: 1em !important;
                width: 1em !important;
                margin: 0 0.07em !important;
                vertical-align: -0.1em !important;
                background: none !important;
                padding: 0 !important;
            }
        </style>
        <link rel='stylesheet' id='wp-block-library-css' href='https://hankgreen.com/wp-includes/css/dist/block-library/style.min.css?ver=6.4.3' media='all'/>
        <style id='wp-block-library-theme-inline-css'>
            .wp-block-audio figcaption {
                color: #555;
                font-size: 13px;
                text-align: center
            }

            .is-dark-theme .wp-block-audio figcaption {
                color: hsla(0,0%,100%,.65)
            }

            .wp-block-audio {
                margin: 0 0 1em
            }

            .wp-block-code {
                border: 1px solid #ccc;
                border-radius: 4px;
                font-family: Menlo,Consolas,monaco,monospace;
                padding: .8em 1em
            }

            .wp-block-embed figcaption {
                color: #555;
                font-size: 13px;
                text-align: center
            }

            .is-dark-theme .wp-block-embed figcaption {
                color: hsla(0,0%,100%,.65)
            }

            .wp-block-embed {
                margin: 0 0 1em
            }

            .blocks-gallery-caption {
                color: #555;
                font-size: 13px;
                text-align: center
            }

            .is-dark-theme .blocks-gallery-caption {
                color: hsla(0,0%,100%,.65)
            }

            .wp-block-image figcaption {
                color: #555;
                font-size: 13px;
                text-align: center
            }

            .is-dark-theme .wp-block-image figcaption {
                color: hsla(0,0%,100%,.65)
            }

            .wp-block-image {
                margin: 0 0 1em
            }

            .wp-block-pullquote {
                border-bottom: 4px solid;
                border-top: 4px solid;
                color: currentColor;
                margin-bottom: 1.75em
            }

            .wp-block-pullquote cite,.wp-block-pullquote footer,.wp-block-pullquote__citation {
                color: currentColor;
                font-size: .8125em;
                font-style: normal;
                text-transform: uppercase
            }

            .wp-block-quote {
                border-left: .25em solid;
                margin: 0 0 1.75em;
                padding-left: 1em
            }

            .wp-block-quote cite,.wp-block-quote footer {
                color: currentColor;
                font-size: .8125em;
                font-style: normal;
                position: relative
            }

            .wp-block-quote.has-text-align-right {
                border-left: none;
                border-right: .25em solid;
                padding-left: 0;
                padding-right: 1em
            }

            .wp-block-quote.has-text-align-center {
                border: none;
                padding-left: 0
            }

            .wp-block-quote.is-large,.wp-block-quote.is-style-large,.wp-block-quote.is-style-plain {
                border: none
            }

            .wp-block-search .wp-block-search__label {
                font-weight: 700
            }

            .wp-block-search__button {
                border: 1px solid #ccc;
                padding: .375em .625em
            }

            :where(.wp-block-group.has-background) {
                padding: 1.25em 2.375em
            }

            .wp-block-separator.has-css-opacity {
                opacity: .4
            }

            .wp-block-separator {
                border: none;
                border-bottom: 2px solid;
                margin-left: auto;
                margin-right: auto
            }

            .wp-block-separator.has-alpha-channel-opacity {
                opacity: 1
            }

            .wp-block-separator:not(.is-style-wide):not(.is-style-dots) {
                width: 100px
            }

            .wp-block-separator.has-background:not(.is-style-dots) {
                border-bottom: none;
                height: 1px
            }

            .wp-block-separator.has-background:not(.is-style-wide):not(.is-style-dots) {
                height: 2px
            }

            .wp-block-table {
                margin: 0 0 1em
            }

            .wp-block-table td,.wp-block-table th {
                word-break: normal
            }

            .wp-block-table figcaption {
                color: #555;
                font-size: 13px;
                text-align: center
            }

            .is-dark-theme .wp-block-table figcaption {
                color: hsla(0,0%,100%,.65)
            }

            .wp-block-video figcaption {
                color: #555;
                font-size: 13px;
                text-align: center
            }

            .is-dark-theme .wp-block-video figcaption {
                color: hsla(0,0%,100%,.65)
            }

            .wp-block-video {
                margin: 0 0 1em
            }

            .wp-block-template-part.has-background {
                margin-bottom: 0;
                margin-top: 0;
                padding: 1.25em 2.375em
            }
        </style>
        <style id='wpseopress-local-business-style-inline-css'>
            span.wp-block-wpseopress-local-business-field {
                margin-right: 8px
            }
        </style>
        <style id='classic-theme-styles-inline-css'>
            /*! This file is auto-generated */
            .wp-block-button__link {
                color: #fff;
                background-color: #32373c;
                border-radius: 9999px;
                box-shadow: none;
                text-decoration: none;
                padding: calc(.667em + 2px) calc(1.333em + 2px);
                font-size: 1.125em
            }

            .wp-block-file__button {
                background: #32373c;
                color: #fff;
                text-decoration: none
            }
        </style>
        <style id='global-styles-inline-css'>
            body {
                --wp--preset--color--black: #000000;
                --wp--preset--color--cyan-bluish-gray: #abb8c3;
                --wp--preset--color--white: #ffffff;
                --wp--preset--color--pale-pink: #f78da7;
                --wp--preset--color--vivid-red: #cf2e2e;
                --wp--preset--color--luminous-vivid-orange: #ff6900;
                --wp--preset--color--luminous-vivid-amber: #fcb900;
                --wp--preset--color--light-green-cyan: #7bdcb5;
                --wp--preset--color--vivid-green-cyan: #00d084;
                --wp--preset--color--pale-cyan-blue: #8ed1fc;
                --wp--preset--color--vivid-cyan-blue: #0693e3;
                --wp--preset--color--vivid-purple: #9b51e0;
                --wp--preset--color--fl-heading-text: #333333;
                --wp--preset--color--fl-body-bg: #ffffff;
                --wp--preset--color--fl-body-text: #444444;
                --wp--preset--color--fl-accent: #006ba3;
                --wp--preset--color--fl-accent-hover: #2b7bb9;
                --wp--preset--color--fl-topbar-bg: #ffffff;
                --wp--preset--color--fl-topbar-text: #757575;
                --wp--preset--color--fl-topbar-link: #2b7bb9;
                --wp--preset--color--fl-topbar-hover: #2b7bb9;
                --wp--preset--color--fl-header-bg: #ffffff;
                --wp--preset--color--fl-header-text: #757575;
                --wp--preset--color--fl-header-link: #757575;
                --wp--preset--color--fl-header-hover: #2b7bb9;
                --wp--preset--color--fl-nav-bg: #ffffff;
                --wp--preset--color--fl-nav-link: #757575;
                --wp--preset--color--fl-nav-hover: #2b7bb9;
                --wp--preset--color--fl-content-bg: #ffffff;
                --wp--preset--color--fl-footer-widgets-bg: #ffffff;
                --wp--preset--color--fl-footer-widgets-text: #757575;
                --wp--preset--color--fl-footer-widgets-link: #2b7bb9;
                --wp--preset--color--fl-footer-widgets-hover: #2b7bb9;
                --wp--preset--color--fl-footer-bg: #ffffff;
                --wp--preset--color--fl-footer-text: #757575;
                --wp--preset--color--fl-footer-link: #2b7bb9;
                --wp--preset--color--fl-footer-hover: #2b7bb9;
                --wp--preset--gradient--vivid-cyan-blue-to-vivid-purple: linear-gradient(135deg,rgba(6,147,227,1) 0%,rgb(155,81,224) 100%);
                --wp--preset--gradient--light-green-cyan-to-vivid-green-cyan: linear-gradient(135deg,rgb(122,220,180) 0%,rgb(0,208,130) 100%);
                --wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange: linear-gradient(135deg,rgba(252,185,0,1) 0%,rgba(255,105,0,1) 100%);
                --wp--preset--gradient--luminous-vivid-orange-to-vivid-red: linear-gradient(135deg,rgba(255,105,0,1) 0%,rgb(207,46,46) 100%);
                --wp--preset--gradient--very-light-gray-to-cyan-bluish-gray: linear-gradient(135deg,rgb(238,238,238) 0%,rgb(169,184,195) 100%);
                --wp--preset--gradient--cool-to-warm-spectrum: linear-gradient(135deg,rgb(74,234,220) 0%,rgb(151,120,209) 20%,rgb(207,42,186) 40%,rgb(238,44,130) 60%,rgb(251,105,98) 80%,rgb(254,248,76) 100%);
                --wp--preset--gradient--blush-light-purple: linear-gradient(135deg,rgb(255,206,236) 0%,rgb(152,150,240) 100%);
                --wp--preset--gradient--blush-bordeaux: linear-gradient(135deg,rgb(254,205,165) 0%,rgb(254,45,45) 50%,rgb(107,0,62) 100%);
                --wp--preset--gradient--luminous-dusk: linear-gradient(135deg,rgb(255,203,112) 0%,rgb(199,81,192) 50%,rgb(65,88,208) 100%);
                --wp--preset--gradient--pale-ocean: linear-gradient(135deg,rgb(255,245,203) 0%,rgb(182,227,212) 50%,rgb(51,167,181) 100%);
                --wp--preset--gradient--electric-grass: linear-gradient(135deg,rgb(202,248,128) 0%,rgb(113,206,126) 100%);
                --wp--preset--gradient--midnight: linear-gradient(135deg,rgb(2,3,129) 0%,rgb(40,116,252) 100%);
                --wp--preset--font-size--small: 13px;
                --wp--preset--font-size--medium: 20px;
                --wp--preset--font-size--large: 36px;
                --wp--preset--font-size--x-large: 42px;
                --wp--preset--spacing--20: 0.44rem;
                --wp--preset--spacing--30: 0.67rem;
                --wp--preset--spacing--40: 1rem;
                --wp--preset--spacing--50: 1.5rem;
                --wp--preset--spacing--60: 2.25rem;
                --wp--preset--spacing--70: 3.38rem;
                --wp--preset--spacing--80: 5.06rem;
                --wp--preset--shadow--natural: 6px 6px 9px rgba(0, 0, 0, 0.2);
                --wp--preset--shadow--deep: 12px 12px 50px rgba(0, 0, 0, 0.4);
                --wp--preset--shadow--sharp: 6px 6px 0px rgba(0, 0, 0, 0.2);
                --wp--preset--shadow--outlined: 6px 6px 0px -3px rgba(255, 255, 255, 1), 6px 6px rgba(0, 0, 0, 1);
                --wp--preset--shadow--crisp: 6px 6px 0px rgba(0, 0, 0, 1);
            }

            :where(.is-layout-flex) {
                gap: 0.5em;
            }

            :where(.is-layout-grid) {
                gap: 0.5em;
            }

            body .is-layout-flow > .alignleft {
                float: left;
                margin-inline-start: 0;margin-inline-end: 2em;}

            body .is-layout-flow > .alignright {
                float: right;
                margin-inline-start: 2em;margin-inline-end: 0;}

            body .is-layout-flow > .aligncenter {
                margin-left: auto !important;
                margin-right: auto !important;
            }

            body .is-layout-constrained > .alignleft {
                float: left;
                margin-inline-start: 0;margin-inline-end: 2em;}

            body .is-layout-constrained > .alignright {
                float: right;
                margin-inline-start: 2em;margin-inline-end: 0;}

            body .is-layout-constrained > .aligncenter {
                margin-left: auto !important;
                margin-right: auto !important;
            }

            body .is-layout-constrained > :where(:not(.alignleft):not(.alignright):not(.alignfull)) {
                max-width: var(--wp--style--global--content-size);
                margin-left: auto !important;
                margin-right: auto !important;
            }

            body .is-layout-constrained > .alignwide {
                max-width: var(--wp--style--global--wide-size);
            }

            body .is-layout-flex {
                display: flex;
            }

            body .is-layout-flex {
                flex-wrap: wrap;
                align-items: center;
            }

            body .is-layout-flex > * {
                margin: 0;
            }

            body .is-layout-grid {
                display: grid;
            }

            body .is-layout-grid > * {
                margin: 0;
            }

            :where(.wp-block-columns.is-layout-flex) {
                gap: 2em;
            }

            :where(.wp-block-columns.is-layout-grid) {
                gap: 2em;
            }

            :where(.wp-block-post-template.is-layout-flex) {
                gap: 1.25em;
            }

            :where(.wp-block-post-template.is-layout-grid) {
                gap: 1.25em;
            }

            .has-black-color {
                color: var(--wp--preset--color--black) !important;
            }

            .has-cyan-bluish-gray-color {
                color: var(--wp--preset--color--cyan-bluish-gray) !important;
            }

            .has-white-color {
                color: var(--wp--preset--color--white) !important;
            }

            .has-pale-pink-color {
                color: var(--wp--preset--color--pale-pink) !important;
            }

            .has-vivid-red-color {
                color: var(--wp--preset--color--vivid-red) !important;
            }

            .has-luminous-vivid-orange-color {
                color: var(--wp--preset--color--luminous-vivid-orange) !important;
            }

            .has-luminous-vivid-amber-color {
                color: var(--wp--preset--color--luminous-vivid-amber) !important;
            }

            .has-light-green-cyan-color {
                color: var(--wp--preset--color--light-green-cyan) !important;
            }

            .has-vivid-green-cyan-color {
                color: var(--wp--preset--color--vivid-green-cyan) !important;
            }

            .has-pale-cyan-blue-color {
                color: var(--wp--preset--color--pale-cyan-blue) !important;
            }

            .has-vivid-cyan-blue-color {
                color: var(--wp--preset--color--vivid-cyan-blue) !important;
            }

            .has-vivid-purple-color {
                color: var(--wp--preset--color--vivid-purple) !important;
            }

            .has-black-background-color {
                background-color: var(--wp--preset--color--black) !important;
            }

            .has-cyan-bluish-gray-background-color {
                background-color: var(--wp--preset--color--cyan-bluish-gray) !important;
            }

            .has-white-background-color {
                background-color: var(--wp--preset--color--white) !important;
            }

            .has-pale-pink-background-color {
                background-color: var(--wp--preset--color--pale-pink) !important;
            }

            .has-vivid-red-background-color {
                background-color: var(--wp--preset--color--vivid-red) !important;
            }

            .has-luminous-vivid-orange-background-color {
                background-color: var(--wp--preset--color--luminous-vivid-orange) !important;
            }

            .has-luminous-vivid-amber-background-color {
                background-color: var(--wp--preset--color--luminous-vivid-amber) !important;
            }

            .has-light-green-cyan-background-color {
                background-color: var(--wp--preset--color--light-green-cyan) !important;
            }

            .has-vivid-green-cyan-background-color {
                background-color: var(--wp--preset--color--vivid-green-cyan) !important;
            }

            .has-pale-cyan-blue-background-color {
                background-color: var(--wp--preset--color--pale-cyan-blue) !important;
            }

            .has-vivid-cyan-blue-background-color {
                background-color: var(--wp--preset--color--vivid-cyan-blue) !important;
            }

            .has-vivid-purple-background-color {
                background-color: var(--wp--preset--color--vivid-purple) !important;
            }

            .has-black-border-color {
                border-color: var(--wp--preset--color--black) !important;
            }

            .has-cyan-bluish-gray-border-color {
                border-color: var(--wp--preset--color--cyan-bluish-gray) !important;
            }

            .has-white-border-color {
                border-color: var(--wp--preset--color--white) !important;
            }

            .has-pale-pink-border-color {
                border-color: var(--wp--preset--color--pale-pink) !important;
            }

            .has-vivid-red-border-color {
                border-color: var(--wp--preset--color--vivid-red) !important;
            }

            .has-luminous-vivid-orange-border-color {
                border-color: var(--wp--preset--color--luminous-vivid-orange) !important;
            }

            .has-luminous-vivid-amber-border-color {
                border-color: var(--wp--preset--color--luminous-vivid-amber) !important;
            }

            .has-light-green-cyan-border-color {
                border-color: var(--wp--preset--color--light-green-cyan) !important;
            }

            .has-vivid-green-cyan-border-color {
                border-color: var(--wp--preset--color--vivid-green-cyan) !important;
            }

            .has-pale-cyan-blue-border-color {
                border-color: var(--wp--preset--color--pale-cyan-blue) !important;
            }

            .has-vivid-cyan-blue-border-color {
                border-color: var(--wp--preset--color--vivid-cyan-blue) !important;
            }

            .has-vivid-purple-border-color {
                border-color: var(--wp--preset--color--vivid-purple) !important;
            }

            .has-vivid-cyan-blue-to-vivid-purple-gradient-background {
                background: var(--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple) !important;
            }

            .has-light-green-cyan-to-vivid-green-cyan-gradient-background {
                background: var(--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan) !important;
            }

            .has-luminous-vivid-amber-to-luminous-vivid-orange-gradient-background {
                background: var(--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange) !important;
            }

            .has-luminous-vivid-orange-to-vivid-red-gradient-background {
                background: var(--wp--preset--gradient--luminous-vivid-orange-to-vivid-red) !important;
            }

            .has-very-light-gray-to-cyan-bluish-gray-gradient-background {
                background: var(--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray) !important;
            }

            .has-cool-to-warm-spectrum-gradient-background {
                background: var(--wp--preset--gradient--cool-to-warm-spectrum) !important;
            }

            .has-blush-light-purple-gradient-background {
                background: var(--wp--preset--gradient--blush-light-purple) !important;
            }

            .has-blush-bordeaux-gradient-background {
                background: var(--wp--preset--gradient--blush-bordeaux) !important;
            }

            .has-luminous-dusk-gradient-background {
                background: var(--wp--preset--gradient--luminous-dusk) !important;
            }

            .has-pale-ocean-gradient-background {
                background: var(--wp--preset--gradient--pale-ocean) !important;
            }

            .has-electric-grass-gradient-background {
                background: var(--wp--preset--gradient--electric-grass) !important;
            }

            .has-midnight-gradient-background {
                background: var(--wp--preset--gradient--midnight) !important;
            }

            .has-small-font-size {
                font-size: var(--wp--preset--font-size--small) !important;
            }

            .has-medium-font-size {
                font-size: var(--wp--preset--font-size--medium) !important;
            }

            .has-large-font-size {
                font-size: var(--wp--preset--font-size--large) !important;
            }

            .has-x-large-font-size {
                font-size: var(--wp--preset--font-size--x-large) !important;
            }

            .wp-block-navigation a:where(:not(.wp-element-button)) {
                color: inherit;
            }

            :where(.wp-block-post-template.is-layout-flex) {
                gap: 1.25em;
            }

            :where(.wp-block-post-template.is-layout-grid) {
                gap: 1.25em;
            }

            :where(.wp-block-columns.is-layout-flex) {
                gap: 2em;
            }

            :where(.wp-block-columns.is-layout-grid) {
                gap: 2em;
            }

            .wp-block-pullquote {
                font-size: 1.5em;
                line-height: 1.6;
            }
        </style>
        <link data-minify="1" rel='stylesheet' id='jquery-bxslider-css' href='https://hankgreen.com/wp-content/cache/min/1/wp-content/plugins/bb-plugin/css/jquery.bxslider.css?ver=1710141750' media='all'/>
        <link data-minify="1" rel='stylesheet' id='fl-builder-layout-13-css' href='https://hankgreen.com/wp-content/cache/min/1/wp-content/uploads/bb-plugin/cache/13-layout.css?ver=1710141750' media='all'/>
        <link data-minify="1" rel='stylesheet' id='font-awesome-5-css' href='https://hankgreen.com/wp-content/cache/min/1/wp-content/plugins/bb-plugin/fonts/fontawesome/5.15.4/css/all.min.css?ver=1710141750' media='all'/>
        <link data-minify="1" rel='stylesheet' id='fl-builder-layout-bundle-7659e76c4c6fffb6a6f98afdb4fee13d-css' href='https://hankgreen.com/wp-content/cache/min/1/wp-content/uploads/bb-plugin/cache/7659e76c4c6fffb6a6f98afdb4fee13d-layout-bundle.css?ver=1710141915' media='all'/>
        <link rel='stylesheet' id='jquery-magnificpopup-css' href='https://hankgreen.com/wp-content/plugins/bb-plugin/css/jquery.magnificpopup.min.css?ver=2.8.0.3' media='all'/>
        <link data-minify="1" rel='stylesheet' id='bootstrap-css' href='https://hankgreen.com/wp-content/cache/min/1/wp-content/themes/bb-theme/css/bootstrap.min.css?ver=1710141750' media='all'/>
        <link data-minify="1" rel='stylesheet' id='fl-automator-skin-css' href='https://hankgreen.com/wp-content/cache/min/1/wp-content/uploads/bb-theme/skin-65eeb22c55889.css?ver=1710141996' media='all'/>
        <link rel='stylesheet' id='fl-child-theme-css' href='https://hankgreen.com/wp-content/themes/bb-theme-child/style.css?ver=6.4.3' media='all'/>
        <link rel='stylesheet' id='pp-animate-css' href='https://hankgreen.com/wp-content/plugins/bbpowerpack/assets/css/animate.min.css?ver=3.5.1' media='all'/>
        <script src="https://hankgreen.com/wp-includes/js/jquery/jquery.min.js?ver=3.7.1" id="jquery-core-js" defer></script>
        <script src="https://hankgreen.com/wp-includes/js/jquery/jquery-migrate.min.js?ver=3.4.1" id="jquery-migrate-js" defer></script>
        <script src="https://hankgreen.com/wp-content/plugins/bbpowerpack/assets/js/jquery.cookie.min.js?ver=1.4.1" id="jquery-cookie-js" defer></script>
        <link rel="https://api.w.org/" href="https://hankgreen.com/wp-json/"/>
        <link rel="alternate" type="application/json" href="https://hankgreen.com/wp-json/wp/v2/pages/13"/>
        <link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://hankgreen.com/xmlrpc.php?rsd"/>
        <meta name="generator" content="WordPress 6.4.3"/>
        <link rel='shortlink' href='https://hankgreen.com/'/>
        <link rel="alternate" type="application/json+oembed" href="https://hankgreen.com/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fhankgreen.com%2F"/>
        <link rel="alternate" type="text/xml+oembed" href="https://hankgreen.com/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fhankgreen.com%2F&#038;format=xml"/>
        <script>
            var bb_powerpack = {
                search_term: '',
                version: '2.35.1',
                getAjaxUrl: function() {
                    return atob('aHR0cHM6Ly9oYW5rZ3JlZW4uY29tL3dwLWFkbWluL2FkbWluLWFqYXgucGhw');
                },
                callback: function() {}
            };
        </script>
        <script type="text/javascript">
            (function(url) {
                if (/(?:Chrome\/26\.0\.1410\.63 Safari\/537\.31|WordfenceTestMonBot)/.test(navigator.userAgent)) {
                    return;
                }
                var addEvent = function(evt, handler) {
                    if (window.addEventListener) {
                        document.addEventListener(evt, handler, false);
                    } else if (window.attachEvent) {
                        document.attachEvent('on' + evt, handler);
                    }
                };
                var removeEvent = function(evt, handler) {
                    if (window.removeEventListener) {
                        document.removeEventListener(evt, handler, false);
                    } else if (window.detachEvent) {
                        document.detachEvent('on' + evt, handler);
                    }
                };
                var evts = 'contextmenu dblclick drag dragend dragenter dragleave dragover dragstart drop keydown keypress keyup mousedown mousemove mouseout mouseover mouseup mousewheel scroll'.split(' ');
                var logHuman = function() {
                    if (window.wfLogHumanRan) {
                        return;
                    }
                    window.wfLogHumanRan = true;
                    var wfscr = document.createElement('script');
                    wfscr.type = 'text/javascript';
                    wfscr.async = true;
                    wfscr.src = url + '&r=' + Math.random();
                    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(wfscr);
                    for (var i = 0; i < evts.length; i++) {
                        removeEvent(evts[i], logHuman);
                    }
                };
                for (var i = 0; i < evts.length; i++) {
                    addEvent(evts[i], logHuman);
                }
            }
            )('//hankgreen.com/?wordfence_lh=1&hid=EE5C100AD88635E47A83EBD6A65FB72A');
        </script>
        <link rel="icon" href="https://hankgreen.com/wp-content/uploads/2022/05/cropped-Hank-Green-32x32.png" sizes="32x32"/>
        <link rel="icon" href="https://hankgreen.com/wp-content/uploads/2022/05/cropped-Hank-Green-192x192.png" sizes="192x192"/>
        <link rel="apple-touch-icon" href="https://hankgreen.com/wp-content/uploads/2022/05/cropped-Hank-Green-180x180.png"/>
        <meta name="msapplication-TileImage" content="https://hankgreen.com/wp-content/uploads/2022/05/cropped-Hank-Green-270x270.png"/>
        <style id="wp-custom-css">
            .HGFooterNav a:hover {
                text-decoration: underline !important;
            }

            .HGEvent .pp-infobox-title-prefix {
                display: block;
                background: #006ba3;
                padding-left: 10px;
            }
        </style>
        <script async src='https://www.googletagmanager.com/gtag/js?id=G-VR2XLX9RYM'></script>
        <script>
            window.dataLayer = window.dataLayer || [];
            function gtag() {
                dataLayer.push(arguments);
            }
            gtag('js', new Date());
            gtag('config', 'G-VR2XLX9RYM', {});
        </script>
    </head>
    <body class="home page-template-default page page-id-13 fl-builder fl-theme-builder-header fl-theme-builder-header-header fl-theme-builder-footer fl-theme-builder-footer-footer fl-framework-bootstrap fl-preset-default fl-full-width fl-search-active" itemscope="itemscope" itemtype="https://schema.org/WebPage">
        <a aria-label="Skip to content" class="fl-screen-reader-text" href="#fl-main-content">Skip to content</a>
        <div class="fl-page">
            <header class="fl-builder-content fl-builder-content-34 fl-builder-global-templates-locked" data-post-id="34" data-type="header" data-sticky="1" data-sticky-on="" data-sticky-breakpoint="medium" data-shrink="1" data-overlay="0" data-overlay-bg="transparent" data-shrink-image-height="50px" role="banner" itemscope="itemscope" itemtype="http://schema.org/WPHeader">
                <div class="fl-row fl-row-full-width fl-row-bg-none fl-node-617bf212496c5 fl-row-default-height fl-row-align-center" data-node="617bf212496c5">
                    <div class="fl-row-content-wrap">
                        <div class="uabb-row-separator uabb-top-row-separator"></div>
                        <div class="fl-row-content fl-row-full-width fl-node-content">
                            <div class="fl-col-group fl-node-617bf21252473" data-node="617bf21252473">
                                <div class="fl-col fl-node-617bf212525c3" data-node="617bf212525c3">
                                    <div class="fl-col-content fl-node-content">
                                        <div class="fl-module fl-module-pp-announcement-bar fl-node-617bf212491e2 fl-visible-desktop fl-visible-large fl-visible-medium" data-node="617bf212491e2">
                                            <div class="fl-module-content fl-node-content">
                                                <div class="pp-announcement-bar-wrap pp-announcement-bar-top">
                                                    <div class="pp-announcement-bar-inner">
                                                        <div class="pp-announcement-bar-content">
                                                            <p>
                                                                <a href="https://www.amazon.com/dp/152474347X/ref=cm_sw_em_r_mt_dp_U_rHh9EbBWC72A5" target="_blank" rel="noopener">
                                                                    <span style="color: #ffffff;">OUT NOW: </span>
                                                                    <strong>
                                                                        <span style="color: #ffffff;">
                                                                            <u>A BEAUTIFULLY FOOLISH ENDEAVOR</u>
                                                                        </span>
                                                                    </strong>
                                                                </a>
                                                            </p>
                                                        </div>
                                                        <div class="pp-announcement-bar-close-button" tabindex="0" aria-label="Close" role="button">
                                                            <span class="fas fa-times pp-close-button" aria-hidden="true"></span>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="fl-module fl-module-pp-announcement-bar fl-node-618e8f2a89356" data-node="618e8f2a89356">
                                            <div class="fl-module-content fl-node-content">
                                                <div class="pp-announcement-bar-wrap pp-announcement-bar-bottom">
                                                    <div class="pp-announcement-bar-inner">
                                                        <div class="pp-announcement-bar-content">
                                                            <p>This website uses cookies to improve your experience. If you continue to use this site, you agree with it.</p>
                                                        </div>
                                                        <div class="pp-announcement-bar-close-button" tabindex="0" aria-label="Close" role="button">
                                                            <span class="fas fa-times pp-close-button" aria-hidden="true"></span>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="fl-row fl-row-full-width fl-row-bg-color fl-node-617befbf15fea fl-row-default-height fl-row-align-center" data-node="617befbf15fea">
                    <div class="fl-row-content-wrap">
                        <div class="uabb-row-separator uabb-top-row-separator"></div>
                        <div class="fl-row-content fl-row-full-width fl-node-content">
                            <div class="fl-col-group fl-node-617befbf17cce fl-col-group-equal-height fl-col-group-align-center fl-col-group-custom-width" data-node="617befbf17cce">
                                <div class="fl-col fl-node-617befbf17dbe fl-col-small fl-col-small-custom-width" data-node="617befbf17dbe">
                                    <div class="fl-col-content fl-node-content">
                                        <div class="fl-module fl-module-photo fl-node-617befd76a1e5" data-node="617befd76a1e5">
                                            <div class="fl-module-content fl-node-content">
                                                <div class="fl-photo fl-photo-align-left" itemscope itemtype="https://schema.org/ImageObject">
                                                    <div class="fl-photo-content fl-photo-img-png">
                                                        <a href="https://hankgreen.com" target="_self" itemprop="url">
                                                            <img loading="lazy" decoding="async" width="350" height="51" class="fl-photo-img wp-image-750" src="http://hankgreen.com/wp-content/uploads/2021/10/Hank-Green-1.png" alt="Hank-Green" itemprop="image" title="Hank-Green" data-no-lazy="1" srcset="https://hankgreen.com/wp-content/uploads/2021/10/Hank-Green-1.png 350w, https://hankgreen.com/wp-content/uploads/2021/10/Hank-Green-1-300x44.png 300w" sizes="(max-width: 350px) 100vw, 350px"/>
                                                        </a>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="fl-col fl-node-617befbf17dc1 fl-col-small-custom-width" data-node="617befbf17dc1">
                                    <div class="fl-col-content fl-node-content">
                                        <div class="fl-module fl-module-menu fl-node-617bf014b0339" data-node="617bf014b0339">
                                            <div class="fl-module-content fl-node-content">
                                                <div class="fl-menu fl-menu-responsive-toggle-mobile fl-menu-responsive-flyout-overlay fl-flyout-left">
                                                    <button class="fl-menu-mobile-toggle hamburger" aria-label="Menu">
                                                        <span class="fl-menu-icon svg-container">
                                                            <svg version="1.1" class="hamburger-menu" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 512 512">
                                                                <rect class="fl-hamburger-menu-top" width="512" height="102"/>
                                                                <rect class="fl-hamburger-menu-middle" y="205" width="512" height="102"/>
                                                                <rect class="fl-hamburger-menu-bottom" y="410" width="512" height="102"/>
                                                            </svg>
                                                        </span>
                                                    </button>
                                                    <div class="fl-clear"></div>
                                                    <nav aria-label="Menu" itemscope="itemscope" itemtype="https://schema.org/SiteNavigationElement">
                                                        <ul id="menu-main-menu" class="menu fl-menu-horizontal fl-toggle-none">
                                                            <li id="menu-item-28" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-home current-menu-item page_item page-item-13 current_page_item">
                                                                <a href="https://hankgreen.com/">Home</a>
                                                            </li>
                                                            <li id="menu-item-29" class="menu-item menu-item-type-post_type menu-item-object-page">
                                                                <a href="https://hankgreen.com/about/">About Hank</a>
                                                            </li>
                                                            <li id="menu-item-30" class="menu-item menu-item-type-post_type menu-item-object-page">
                                                                <a href="https://hankgreen.com/books/">Books</a>
                                                            </li>
                                                            <li id="menu-item-32" class="menu-item menu-item-type-post_type menu-item-object-page">
                                                                <a href="https://hankgreen.com/speaking/">Speaking</a>
                                                            </li>
                                                            <li id="menu-item-33" class="menu-item menu-item-type-post_type menu-item-object-page">
                                                                <a href="https://hankgreen.com/wheres-hank/">Where’s Hank?</a>
                                                            </li>
                                                            <li id="menu-item-31" class="menu-item menu-item-type-post_type menu-item-object-page">
                                                                <a href="https://hankgreen.com/events/">Events</a>
                                                            </li>
                                                        </ul>
                                                    </nav>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="fl-col fl-node-617befbf17dc3 fl-col-small" data-node="617befbf17dc3">
                                    <div class="fl-col-content fl-node-content">
                                        <div class="fl-module fl-module-icon-group fl-node-617bf0f89f9d3 fl-visible-desktop fl-visible-large" data-node="617bf0f89f9d3">
                                            <div class="fl-module-content fl-node-content">
                                                <div class="fl-icon-group">
                                                    <span class="fl-icon">
                                                        <a href="https://twitter.com/hankgreen" target="_blank" rel="noopener">
                                                            <i class="fab fa-twitter" aria-hidden="true"></i>
                                                        </a>
                                                    </span>
                                                    <span class="fl-icon">
                                                        <a href="https://www.facebook.com/hankgreen/" target="_blank" rel="noopener">
                                                            <i class="fab fa-facebook" aria-hidden="true"></i>
                                                        </a>
                                                    </span>
                                                    <span class="fl-icon">
                                                        <a href="https://www.instagram.com/hankgreen/" target="_blank" rel="noopener">
                                                            <i class="fab fa-instagram" aria-hidden="true"></i>
                                                        </a>
                                                    </span>
                                                    <span class="fl-icon">
                                                        <a href="https://www.youtube.com/vlogbrothers" target="_blank" rel="noopener">
                                                            <i class="fab fa-youtube" aria-hidden="true"></i>
                                                        </a>
                                                    </span>
                                                    <span class="fl-icon">
                                                        <a href="https://www.tiktok.com/@hankgreen1?source=h5_m" target="_blank" rel="noopener">
                                                            <i class="fab fa-tumblr" aria-hidden="true"></i>
                                                        </a>
                                                    </span>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </header>
            <div class="uabb-js-breakpoint" style="display: none;"></div>
            <div id="fl-main-content" class="fl-page-content" itemprop="mainContentOfPage" role="main">
                <div class="fl-content-full container">
                    <div class="row">
                        <div class="fl-content col-md-12">
                            <article class="fl-post post-13 page type-page status-publish hentry" id="fl-post-13" itemscope="itemscope" itemtype="https://schema.org/CreativeWork">
                                <div class="fl-post-content clearfix" itemprop="text">
                                    <div class="fl-builder-content fl-builder-content-13 fl-builder-content-primary fl-builder-global-templates-locked" data-post-id="13">
                                        <div class="fl-row fl-row-full-width fl-row-bg-none fl-node-617bf394ea2d7 fl-row-default-height fl-row-align-center" data-node="617bf394ea2d7">
                                            <div class="fl-row-content-wrap">
                                                <div class="uabb-row-separator uabb-top-row-separator"></div>
                                                <div class="fl-row-content fl-row-fixed-width fl-node-content">
                                                    <div class="fl-col-group fl-node-617bf394ec31d fl-col-group-equal-height fl-col-group-align-center fl-col-group-responsive-reversed" data-node="617bf394ec31d">
                                                        <div class="fl-col fl-node-617bf394ec437 fl-col-small" data-node="617bf394ec437">
                                                            <div class="fl-col-content fl-node-content">
                                                                <div class="fl-module fl-module-photo fl-node-617bf39b11e42" data-node="617bf39b11e42">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <div class="fl-photo fl-photo-align-center" itemscope itemtype="https://schema.org/ImageObject">
                                                                            <div class="fl-photo-content fl-photo-img-jpg">
                                                                                <img fetchpriority="high" decoding="async" width="600" height="757" class="fl-photo-img wp-image-40" src="http://hankgreen.com/wp-content/uploads/2021/10/Hank-Green-1.jpg" alt="Hank-Green-1 Home" itemprop="image" title="Home" srcset="https://hankgreen.com/wp-content/uploads/2021/10/Hank-Green-1.jpg 600w, https://hankgreen.com/wp-content/uploads/2021/10/Hank-Green-1-238x300.jpg 238w" sizes="(max-width: 600px) 100vw, 600px"/>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <div class="fl-col fl-node-617bf394ec43a fl-col-small" data-node="617bf394ec43a">
                                                            <div class="fl-col-content fl-node-content">
                                                                <div class="fl-module fl-module-dual-color-heading fl-node-617bf3e7e48d9" data-node="617bf3e7e48d9">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <div class="uabb-module-content uabb-dual-color-heading  uabb-heading-layout-block uabb-heading-align-left ">
                                                                            <h1>
                                                                                <span class="uabb-first-heading-text">Make Things,</span>
                                                                                <span class="uabb-second-heading-text">Learn stuff.</span>
                                                                            </h1>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="fl-row fl-row-full-width fl-row-bg-gradient fl-node-617bf49d7c8da fl-row-default-height fl-row-align-center" data-node="617bf49d7c8da">
                                            <div class="fl-row-content-wrap">
                                                <div class="uabb-row-separator uabb-top-row-separator"></div>
                                                <div class="fl-row-content fl-row-fixed-width fl-node-content">
                                                    <div class="fl-col-group fl-node-617bf49d7ff0b fl-col-group-equal-height fl-col-group-align-center fl-col-group-responsive-reversed" data-node="617bf49d7ff0b">
                                                        <div class="fl-col fl-node-617bf49d80039 fl-col-small" data-node="617bf49d80039">
                                                            <div class="fl-col-content fl-node-content">
                                                                <div class="fl-module fl-module-heading fl-node-617bf5c525093" data-node="617bf5c525093">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <h2 class="fl-heading">
                                                                            <span class="fl-heading-text">The Books</span>
                                                                        </h2>
                                                                    </div>
                                                                </div>
                                                                <div class="fl-module fl-module-heading fl-node-617bf5f4d1c9f" data-node="617bf5f4d1c9f">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <h3 class="fl-heading">
                                                                            <span class="fl-heading-text">The Carl Saga</span>
                                                                        </h3>
                                                                    </div>
                                                                </div>
                                                                <div class="fl-module fl-module-rich-text fl-node-617bf614727f9" data-node="617bf614727f9">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <div class="fl-rich-text">
                                                                            <p>The country, and the planet, is healing from a crisis. Three young people are uncovering a mystery and building their power in this new world. Andy has picked up the mantle of April’s fame, Maya, struggling through grief, is following a string of mysteries that she is convinced will lead her to April, and Miranda is considering taking a new job at a company building a new technology that might have repercussions beyond anyone’s comprehension.</p>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                                <div class="fl-module fl-module-testimonials fl-node-617bf680b77d4" data-node="617bf680b77d4">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <div class="fl-testimonials-wrap wide">
                                                                            <div class="fl-testimonials">
                                                                                <div class="fl-testimonial">
                                                                                    <p>
                                                                                        While &nbsp;there are many parallels to our current climate, “A Beautifully Foolish Endeavor” is a hopeful read that provides a “Black Mirror”-like warning of new technology without the heavy feeling of dread.<br/>
                                                                                        <strong>– USA Today</strong>
                                                                                    </p>
                                                                                </div>
                                                                                <div class="fl-testimonial">
                                                                                    <p>
                                                                                        [A] raucous, boldly inventive tale of alien technology, social media and influencers, the limits of the human mind, and the lengths humans will go to get what they want. Even after a satisfying ending, readers will have much to think about.<br/>
                                                                                        <strong>– Booklist Starred</strong>
                                                                                    </p>
                                                                                </div>
                                                                                <div class="fl-testimonial">
                                                                                    <p>
                                                                                        Filled with compassion, bravery, smart mobs and stupid ones, and a hell of a metaphor for late-stage capitalism, besides.<br/>
                                                                                        <strong>– Cory Doctorow</strong>
                                                                                    </p>
                                                                                </div>
                                                                                <div class="fl-testimonial">
                                                                                    <p>
                                                                                        Throughout this adventurous, witty, and compelling novel, Green delivers sharp social commentary on the power of social media and both the benefits and horrendous consequences that follow when we give too much of ourselves to technology. An essential choice for all sf collections.<br/>
                                                                                        <strong>– Library Journal (starred review)</strong>
                                                                                    </p>
                                                                                </div>
                                                                            </div>
                                                                            <div class="fl-slider-prev" role="button" aria-pressed="false" aria-label="Previous"></div>
                                                                            <div class="fl-slider-next" role="button" aria-pressed="false" aria-label="Next"></div>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <div class="fl-col fl-node-617bf539f3516 fl-col-small" data-node="617bf539f3516">
                                                            <div class="fl-col-content fl-node-content">
                                                                <div class="fl-module fl-module-photo fl-node-617bf53f81cae" data-node="617bf53f81cae">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <div class="fl-photo fl-photo-align-center" itemscope itemtype="https://schema.org/ImageObject">
                                                                            <div class="fl-photo-content fl-photo-img-jpg">
                                                                                <img loading="lazy" decoding="async" width="500" height="813" class="fl-photo-img wp-image-41" src="http://hankgreen.com/wp-content/uploads/2021/10/A-Beautifully-Foolish-Endeavor.jpg" alt="A-Beautifully-Foolish-Endeavor Home" itemprop="image" title="Home" srcset="https://hankgreen.com/wp-content/uploads/2021/10/A-Beautifully-Foolish-Endeavor.jpg 500w, https://hankgreen.com/wp-content/uploads/2021/10/A-Beautifully-Foolish-Endeavor-185x300.jpg 185w" sizes="(max-width: 500px) 100vw, 500px"/>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="fl-col-group fl-node-617bf95f7e36c" data-node="617bf95f7e36c">
                                                        <div class="fl-col fl-node-617bf95f7e44a" data-node="617bf95f7e44a">
                                                            <div class="fl-col-content fl-node-content">
                                                                <div class="fl-module fl-module-heading fl-node-617bfbd5c956d" data-node="617bfbd5c956d">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <h4 class="fl-heading">
                                                                            <span class="fl-heading-text">Hardcover</span>
                                                                        </h4>
                                                                    </div>
                                                                </div>
                                                                <div class="fl-module fl-module-pp-logos-grid fl-node-617bf95f7e2dc" data-node="617bf95f7e2dc">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <div class="pp-logos-content clearfix">
                                                                            <div class="pp-logos-wrapper pp-logos-grid clearfix">
                                                                                <div class="pp-logo pp-logo-0">
                                                                                    <a href="https://bookshop.org/books/a-beautifully-foolish-endeavor/9781524743475" target="_blank" rel="nofollow noopener">
                                                                                        <div class="pp-logo-inner">
                                                                                            <div class="pp-logo-inner-wrap">
                                                                                                <div class="logo-image-wrapper">
                                                                                                    <img title="Home" decoding="async" class="logo-image" src="http://hankgreen.com/wp-content/uploads/2021/10/image.png" alt="image Home" data-no-lazy="1"/>
                                                                                                </div>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </div>
                                                                                <div class="pp-logo pp-logo-1">
                                                                                    <a href="https://www.waterstones.com/book/a-beautifully-foolish-endeavour/hank-green/9781473224223" target="_blank" rel="nofollow noopener">
                                                                                        <div class="pp-logo-inner">
                                                                                            <div class="pp-logo-inner-wrap">
                                                                                                <div class="logo-image-wrapper">
                                                                                                    <img title="Home" decoding="async" class="logo-image" src="http://hankgreen.com/wp-content/uploads/2021/10/image-1.png" alt="image-1 Home" data-no-lazy="1"/>
                                                                                                </div>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </div>
                                                                                <div class="pp-logo pp-logo-2">
                                                                                    <a href="https://www.chapters.indigo.ca/en-ca/books/a-beautifully-foolish-endeavor-signed/9780593183915-item.html?ikwid=a+beautifully+foolish+endeavor&ikwsec=Home&ikwidx=0#algoliaQueryId=d7fff070a5e13b349a296676718314e5" target="_blank" rel="nofollow noopener">
                                                                                        <div class="pp-logo-inner">
                                                                                            <div class="pp-logo-inner-wrap">
                                                                                                <div class="logo-image-wrapper">
                                                                                                    <img title="Home" decoding="async" class="logo-image" src="http://hankgreen.com/wp-content/uploads/2021/10/image-2.png" alt="image-2 Home" data-no-lazy="1"/>
                                                                                                </div>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </div>
                                                                                <div class="pp-logo pp-logo-3">
                                                                                    <a href="https://www.barnesandnoble.com/w/a-beautifully-foolish-endeavor-hank-green/1135102884;jsessionid=114FC1FEF86112C236A4F70CEFE2FB48.prodny_store01-atgap07?2sid=Random%20House%20Inc_8373827_NA&ean=9781524743475&sourceId=AFFRandom%20House%20Inc&st=AFF" target="_blank" rel="nofollow noopener">
                                                                                        <div class="pp-logo-inner">
                                                                                            <div class="pp-logo-inner-wrap">
                                                                                                <div class="logo-image-wrapper">
                                                                                                    <img title="Home" decoding="async" class="logo-image" src="http://hankgreen.com/wp-content/uploads/2021/10/image-3.png" alt="image-3 Home" data-no-lazy="1"/>
                                                                                                </div>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </div>
                                                                                <div class="pp-logo pp-logo-4">
                                                                                    <a href="https://bookshop.org/books/a-beautifully-foolish-endeavor/9781524743475" target="_blank" rel="nofollow noopener">
                                                                                        <div class="pp-logo-inner">
                                                                                            <div class="pp-logo-inner-wrap">
                                                                                                <div class="logo-image-wrapper">
                                                                                                    <img title="Home" decoding="async" class="logo-image" src="http://hankgreen.com/wp-content/uploads/2021/10/image-4.png" alt="image-4 Home" data-no-lazy="1"/>
                                                                                                </div>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </div>
                                                                                <div class="pp-logo pp-logo-5">
                                                                                    <a href="https://www.booksamillion.com/p/9781524743475?AID=10747236&PID=8373827&SID=PRHC900C58C3E--9781524743475&cjevent=acf685c1bae411ea809e00560a1c0e11" target="_blank" rel="nofollow noopener">
                                                                                        <div class="pp-logo-inner">
                                                                                            <div class="pp-logo-inner-wrap">
                                                                                                <div class="logo-image-wrapper">
                                                                                                    <img title="Home" decoding="async" class="logo-image" src="http://hankgreen.com/wp-content/uploads/2021/10/image-5.png" alt="image-5 Home" data-no-lazy="1"/>
                                                                                                </div>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </div>
                                                                                <div class="pp-logo pp-logo-6">
                                                                                    <a href="https://www.indiebound.org/book/9781524743475?aff=penguinrandom" target="_blank" rel="nofollow noopener">
                                                                                        <div class="pp-logo-inner">
                                                                                            <div class="pp-logo-inner-wrap">
                                                                                                <div class="logo-image-wrapper">
                                                                                                    <img title="Home" decoding="async" class="logo-image" src="http://hankgreen.com/wp-content/uploads/2021/10/image-6.png" alt="image-6 Home" data-no-lazy="1"/>
                                                                                                </div>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                                <div class="fl-module fl-module-heading fl-node-617bfbedc8131" data-node="617bfbedc8131">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <h4 class="fl-heading">
                                                                            <span class="fl-heading-text">Audio</span>
                                                                        </h4>
                                                                    </div>
                                                                </div>
                                                                <div class="fl-module fl-module-pp-logos-grid fl-node-617bfb3dabbe5" data-node="617bfb3dabbe5">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <div class="pp-logos-content clearfix">
                                                                            <div class="pp-logos-wrapper pp-logos-grid clearfix">
                                                                                <div class="pp-logo pp-logo-0">
                                                                                    <a href="https://bit.ly/2VPfET0" target="_blank" rel="nofollow noopener">
                                                                                        <div class="pp-logo-inner">
                                                                                            <div class="pp-logo-inner-wrap">
                                                                                                <div class="logo-image-wrapper">
                                                                                                    <img title="Home" decoding="async" class="logo-image" src="http://hankgreen.com/wp-content/uploads/2021/10/image-7.png" alt="image-7 Home" data-no-lazy="1"/>
                                                                                                </div>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </div>
                                                                                <div class="pp-logo pp-logo-1">
                                                                                    <a href="http://hankgreen.com//#" target="_blank" rel="nofollow noopener">
                                                                                        <div class="pp-logo-inner">
                                                                                            <div class="pp-logo-inner-wrap">
                                                                                                <div class="logo-image-wrapper">
                                                                                                    <img title="Home" decoding="async" class="logo-image" src="http://hankgreen.com/wp-content/uploads/2021/10/image-8.png" alt="image-8 Home" data-no-lazy="1"/>
                                                                                                </div>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </div>
                                                                                <div class="pp-logo pp-logo-2">
                                                                                    <a href="http://hankgreen.com//#" target="_blank" rel="nofollow noopener">
                                                                                        <div class="pp-logo-inner">
                                                                                            <div class="pp-logo-inner-wrap">
                                                                                                <div class="logo-image-wrapper">
                                                                                                    <img title="Home" decoding="async" class="logo-image" src="http://hankgreen.com/wp-content/uploads/2021/10/image-9.png" alt="image-9 Home" data-no-lazy="1"/>
                                                                                                </div>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </div>
                                                                                <div class="pp-logo pp-logo-3">
                                                                                    <a href="https://bit.ly/2y2ROu9" target="_blank" rel="nofollow noopener">
                                                                                        <div class="pp-logo-inner">
                                                                                            <div class="pp-logo-inner-wrap">
                                                                                                <div class="logo-image-wrapper">
                                                                                                    <img title="Home" decoding="async" class="logo-image" src="http://hankgreen.com/wp-content/uploads/2021/10/image-10.png" alt="image-10 Home" data-no-lazy="1"/>
                                                                                                </div>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </div>
                                                                                <div class="pp-logo pp-logo-4">
                                                                                    <a href="https://adbl.co/2yYZz40" target="_blank" rel="nofollow noopener">
                                                                                        <div class="pp-logo-inner">
                                                                                            <div class="pp-logo-inner-wrap">
                                                                                                <div class="logo-image-wrapper">
                                                                                                    <img title="Home" decoding="async" class="logo-image" src="http://hankgreen.com/wp-content/uploads/2021/10/image-11.png" alt="image-11 Home" data-no-lazy="1"/>
                                                                                                </div>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="fl-row fl-row-full-width fl-row-bg-gradient fl-node-617c0363587e4 fl-row-default-height fl-row-align-center" data-node="617c0363587e4">
                                            <div class="fl-row-content-wrap">
                                                <div class="uabb-row-separator uabb-top-row-separator"></div>
                                                <div class="fl-row-content fl-row-fixed-width fl-node-content">
                                                    <div class="fl-col-group fl-node-617c0363589be fl-col-group-equal-height fl-col-group-align-center fl-col-group-responsive-reversed" data-node="617c0363589be">
                                                        <div class="fl-col fl-node-617c0363589bf fl-col-small" data-node="617c0363589bf">
                                                            <div class="fl-col-content fl-node-content">
                                                                <div class="fl-module fl-module-photo fl-node-617c0363589c5" data-node="617c0363589c5">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <div class="fl-photo fl-photo-align-center" itemscope itemtype="https://schema.org/ImageObject">
                                                                            <div class="fl-photo-content fl-photo-img-jpg">
                                                                                <img loading="lazy" decoding="async" width="800" height="1202" class="fl-photo-img wp-image-63" src="http://hankgreen.com/wp-content/uploads/2021/10/Hank-Green.jpg" alt="Hank-Green Home" itemprop="image" title="Home" srcset="https://hankgreen.com/wp-content/uploads/2021/10/Hank-Green.jpg 800w, https://hankgreen.com/wp-content/uploads/2021/10/Hank-Green-200x300.jpg 200w, https://hankgreen.com/wp-content/uploads/2021/10/Hank-Green-682x1024.jpg 682w, https://hankgreen.com/wp-content/uploads/2021/10/Hank-Green-768x1154.jpg 768w" sizes="(max-width: 800px) 100vw, 800px"/>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <div class="fl-col fl-node-617c0363589c4" data-node="617c0363589c4">
                                                            <div class="fl-col-content fl-node-content">
                                                                <div class="fl-module fl-module-heading fl-node-617c0363589c0" data-node="617c0363589c0">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <h2 class="fl-heading">
                                                                            <span class="fl-heading-text">About Hank</span>
                                                                        </h2>
                                                                    </div>
                                                                </div>
                                                                <div class="fl-module fl-module-heading fl-node-617c0363589c1" data-node="617c0363589c1">
                                                                    <div class="fl-module-content fl-node-content">
                                                                        <h3 class="fl-heading">
                                                                            <span class="fl-heading-text">Make things, learn stuff.</span>

# **Travel**
###### By Jesus A Acosta

<div class="fl-clear"></div>
                                                    <nav aria-label="Menu" itemscope="itemscope" itemtype="https://schema.org/SiteNavigationElement">
                                                        <ul id="menu-main-menu" class="menu fl-menu-horizontal fl-toggle-none">

<li id="menu-item-28" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-home current-menu-item page_item page-item-13 current_page_item">
                                                                <a href="https://jaal32.github.io/">Home</a>
                                                            </li>
                                                            <li id="menu-item-29" class="menu-item menu-item-type-post_type menu-item-object-page">
                                                                <a href="bio">Bio</a>
                                                            </li>
                                                            <li id="menu-item-30" class="menu-item menu-item-type-post_type menu-item-object-page">
                                                                <a href="topic">Resume</a>
                                                            </li>
                                                            <li id="menu-item-32" class="menu-item menu-item-type-post_type menu-item-object-page">
                                                                <a href="biography">Contact</a>
                                                            </li>
                                                            <li id="menu-item-33" class="menu-item menu-item-type-post_type menu-item-object-page">
                                                                <a href="sm">Social Media</a>
                                                            </li>
                                                            <li id="menu-item-31" class="menu-item menu-item-type-post_type menu-item-object-page">
                                                                <a href="https://www.marinecorpsleaguesfv1277.org/">Veteran Organization to Volunteer</a>

#### Greece

![Greece](https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/Shipwreck_Beach_-_Western_coast_of_Zakynthos%2C_Greece_%2812%29.jpg/200px-Shipwreck_Beach_-_Western_coast_of_Zakynthos%2C_Greece_%2812%29.jpg)

#### Rome

![Rome](http://www.domondonart.com/wp-content/uploads/2016/06/VeniceItaly-restaurant-600x600.jpg)

[Home](https://jaal32.github.io/home)
