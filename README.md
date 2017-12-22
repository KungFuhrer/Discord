@import url(https://fonts.googleapis.com/css?family=Roboto);
@import url(https://fonts.googleapis.com/css?family=Ubuntu+Mono:400,400i);
@import url("https://rawgit.com/0mniscient/Discord-Themes/master/css/Tags.css");

:root {
    --version-content: "7.5";
    --theme-name: "Quiet";
    --theme-letter: "Q";
}

/* Version Displayed */
.theme-light{--theme-name: "Loud" !important;}

.version{display:inline-block;margin:0px 0px 0px 0px;}

.version:after{content:var(--version-content);display:block;font-size:14px;font-weight:700;color:#43B581;}

.ui-standard-sidebar-view #bd-settingspane-container .content-column.default .bda-slist::before{content: var(--theme-name)" v" var(--version-content) "\A \A Theme Options:\A \A - Revert bottom to default\A - Bring back mention(s) notifications bar\A - Circle Avatars\A - Revert Min, Max, Close buttons to default\A - Better Mentions (Pulsing Box Shadow)\A - Show/Hide Blocked messages\A - Loading Theme Animation \A \A Go to discord.me/mrrobotserver to show love and support! <3"!important;}

.need-help-modal .header h1::after{content:var(--theme-name)" v" var(--version-content);color:#fff;font-weight:700;font-size:250%;z-index:11;position:absolute;width:200%;left: 0px;margin-left: -45px;top: 16px;font-family:Roboto;text-shadow:1px 1px 1px rgba(0, 0, 0, 0.4);}

#bd-settingspane-container .content-column.default .ui-form-title.h2::after{content: "Hi, I have a server where I post customizable options for the theme and \A you can give me feedback, also with tons of bots. Join the server at \A\A discord.me/mrrobotserver \A\A It's also easier to report bugs and has a higher chance of getting them \A fixed faster.";}

.themedescription{display:block;width:100%;margin-right:5px;}

.themedescription:before{display:block;font-size:14px;height:15px;color:#3ddcb1;font-weight:700;content:"Updates are automatic. Just restart Discord to get the latest version.";}

body:before{content:"Thanks for using "var(--theme-name)"!";z-index:1000000000000000000000000;color:#fff;background:var(--main-color);top:0px;left:50%;position:absolute;border-radius:5px;padding:5px 15px;-webkit-transform:translate(-50%, -100%);transform:translate(-50%, -100%);-webkit-animation:version 3s ease;animation:version 3s ease;-webkit-animation-delay:4s;animation-delay:4s;}

body,span:not(.spinner-item){-webkit-font-smoothing:antialiased;-webkit-backface-visibility:hidden;}

@-webkit-keyframes version{from{-webkit-transform:translate(-50%, -100%);transform:translate(-50%, -100%);}

20%{-webkit-transform:translate(-50%, 20%);transform:translate(-50%, 20%)}

80%{-webkit-transform:translate(-50%, 20%);transform:translate(-50%, 20%)}

to{-webkit-transform:translate(-50%, -100%);transform:translate(-50%, -100%);}

}

@keyframes version{from{-webkit-transform:translate(-50%, -100%);transform:translate(-50%, -100%);}

20%{-webkit-transform:translate(-50%, 20%);transform:translate(-50%, 20%)}

80%{-webkit-transform:translate(-50%, 20%);transform:translate(-50%, 20%)}

to{-webkit-transform:translate(-50%, -100%);transform:translate(-50%, -100%);}

}

.help-container{display:none;}

.account{border-top:none !important;padding:0 15px !important;background:#19191b;border-top: 2px solid #212121 !important;height: 72px;overflow: visible;z-index: 9;width: 310px;margin-left: -80px;box-sizing: border-box;}

.links{background-color:#19191b !important;}

.account .btn{background:transparent;box-shadow:none !important;}

#voice-connection, #rtc-connection{z-index:9;border-top:none !important;/*width:285px;margin-left:-83px;*/
padding:15px 20px 15px 18px !important;}

#voice-connection .btn, #rtc-connection .btn{background:#19191b;box-shadow:none !important;}

.title-wrap{border-bottom:#19191b !important;background:#19191b !important;}

.chat .new-messages-bar{background-color:var(--main-color);}

.chat .new-messages-bar:hover{background-color:var(--hover-color);}

.chat>.title-wrap>.topic{font-size:14px;margin-top:5px;color:#656565 !important;}

.chat .divider>span{background:#19191b !important;font-size:12px;text-transform:uppercase;margin:0px 0px;border-radius:0px;opacity:1;padding:5px 15px;width:100%;text-align:center;}

.chat>.content .messages .message-group{border-bottom:none !important;}

.chat>.content .messages .message-group a{color: var(--main-color) !important;font-weight: 500;}

.chat>.content .messages .message-group .markup{color:#aaaaaa;line-height:1.3em;padding:0;}

.channel-textarea-inner{border: 0;background:#19191b !important;padding:0;border-radius: 0px!important;height: 100%;}

.channel-members .member:hover{background:rgba(255, 255, 255, 0.07) !important;}

.channel-members .member .member-username{font-size:15px;}

.channel-members .member .member-game{font-size:10px;}

.channel-members .avatar-small .status{border-color:rgba(0, 0, 0, 0.7) !important;}

.channel-members h2{color:var(--main-color) !important;background-image:linear-gradient(90deg, transparent, transparent), linear-gradient(90deg, transparent, var(--main-color), transparent);background-size:100% 3px;/* This get flipped. */
background-position:0 0, 0 100%;/* The last argument gets flipped. */
background-repeat:no-repeat;padding-top: 6px;padding-bottom: 6px;margin-top: 4px;font-weight: 700;;text-align:center;border-radius:3px;width:145px;margin-left:15px;}

.channel-members h2:first-of-type{margin-top:0px !important;}

.settings .settings-header{background:#141417 !important;}

.form .btn-primary{background-color:var(--main-color);}

.form .btn-primary:hover{background-color:var(--hover-color) !important;}

.user-settings-modal a:hover{color:var(--hover-color);}

.hljs  {White-space: pre-wrap !important;}

.tab-bar.SIDE{margin-right:-17px;}

.guild-header ul{background:#19191b !important;transition:transform .5s cubic-bezier(0.18, 0.89, 0.32, 1.28) !important;padding-top:100px;top:-56px;border-bottom:2px solid var(--main-color);}

.add-friend-popout .btn{background-color:#19191b !important;}

.private-channels .search-bar{background:rgba(10, 13, 16, 0) !important;border-bottom:2px var(--main-color) solid !important;box-shadow:0 0px 0 0 rgba(0, 0, 0, .06), inset 0 0px 0 0 rgba(0, 0, 0, .2);-webkit-border-radius:0px;border-radius:0px;margin-top:-1px;}

.private-channels .search-bar input{background:#transparent !important;}

.private-channels .search-bar-inner{background: #19191b !important;}

.friends-header{background:#19191b !important;}

.friends-table{background:#19191b !important;margin-top:0 !important;}

.friends-header,.friends-table .friends-table-header{border-bottom:1px solid hsla(0, 0%, 100%, .1) !important;}

.friends-header .tab-bar .tab-bar-separator,.friends-table .friends-table-header .friends-column-separator{background-color:hsla(0, 0%, 100%, .1) !important;}

.friends-table .friends-table-body{padding-top:20px !important;}

.friends-table .friends-row:hover{background:#39393b !important;}

.theme-dark .chat .title-wrap .channel-name{font-size:16px !important;text-transform:capitalize !important;}

.theme-dark .chat .title-wrap .topic{padding-bottom:6px;}

.theme-dark .friends-table .messages .message-group h2 strong,.theme-dark .messages-wrapper .messages .message-group h2 strong{font-size:15px;}

div.avatar-large{border-radius:5px;}

.avatar-small{border-radius:3px;}

.guilds-wrapper .guild-separator:after{display:none;}

.guilds-wrapper .guilds .guild .guild-inner{background:#0a0a0a !important;}

.chat .divider.divider-red > span{color:#b12340 !important;background-color:#111113 !important;border-radius:3px;text-align:center;left:0px;}

.message-group.has-divider{border-color:transparent;}

.theme-dark .message-group .comment .markup code.inline,.theme-dark .message-group .comment .markup pre code{background:#121213;}

.chat .new-messages-bar button:last-child{color:#fff;}

.chat>.title-wrap>.topic:before{display:none;}

.guild-header ul li:hover a{background-color:#121213;}

.guild-channels .channel-text.selected{background:linear-gradient(to right, #121213 85%, #19191b);}

.guilds-wrapper .guilds .guild.selected:before{background:var(--main-color) !important;}

.guilds-wrapper .guilds .guild.unread:before{background:var(--hover-color);}

.guild-channels .channel-text.selected:before{border-left:3px solid var(--main-color);}

.guild-channels .channel-text.unread:not(.selected):not(.channel-muted):before{background:var(--hover-color);}

.guild-channels .channel-text:hover{background:linear-gradient(to right, #121213 85%, #19191b);}

.guild-channels .channel-text:hover.channel-muted:before,.guild-channels .channel-text:hover:not(.unread):before{border-left:3px solid var(--main-color);}

.channel-textarea{box-shadow: 0 0 transparent;margin: 0px;border-radius: 0px;-webkit-transition: all 200ms ease;transition: all 200ms ease;}

.theme-dark .channel-textarea-inner .channel-textarea-upload{border-right-color:transparent;}

.theme-dark .channel-textarea-inner .channel-textarea-upload:hover{background-color:#151517;border-radius:3px;}

.channel-textarea-inner .channel-textarea-upload{border-radius: 0px !important;width: 80px;-webkit-transition: all 100ms ease!important;transition: all 100ms ease!important;display: inline-block!important;margin: 0;}

.edit-message .channel-textarea-emoji {width: 40px;top: 2px;display: block;}

.channel-members .member:hover{background:linear-gradient(to right, #121213 85%, #19191b) !important;margin-left:14px;border-top-left-radius:3px;border-bottom-left-radius:3px;}

.channel-members .member:hover>.avatar-small{margin-left:-14px;}

.guild-header{border-bottom:2px solid var(--main-color);}

.theme-dark .message-group .comment .markup pre{background:#141417 !important;border-color:#111113 !important;}

.theme-dark .hljs{color:#888888 !important;}

.account .btn-settings:after{opacity:0.2;}

.account .btn-group{border:1px solid transparent;}

.account .btn-deafen,.account .btn-mute{border-right:1px solid transparent;}

button.btn:hover{background-color:#151517;border-radius:3px;}

.tooltip{background-color:var(--main-color) !important;}

.tooltip.tooltip-top:after{border-top-color:var(--main-color) !important;}

.tooltip.tooltip-black.tooltip-right:after, .tooltip.tooltip-right:after{border-right-color: var(--main-color) !important;}

.tooltip.tooltip-bottom:after{border-bottom-color:var(--main-color) !important;}

.bot-tag{background:var(--main-color);color:#e8e8e8!important;text-shadow: 0px 1px 3px #000;}

.chat .divider > span{color:#a0a0a0 !important;background:transparent !important;border-radius:3px;position:relative;text-align:left;left:-14px;}

.theme-dark .chat .has-more button{background:#111113 !important;border:1px solid #111113 !important;color:var(--main-color) !important;}

.chat .divider{height:28px;background-color:transparent;}

.highlight{color:var(--main-color);background:#131315;border-radius:3px;padding:1px 4px 2px 3px;}

.highlight:hover{background-color:var(--main-color);}

.theme-dark .message-group .comment .markup .highlight:hover{background-color:var(--hover-color);color:#fff !important;opacity:0.9;}

.theme-dark .chat .title-wrap .topic .highlight:hover{background-color:var(--hover-color) !important;color:#fff !important;opacity:0.9;}

.theme-dark .message-group .comment .markup .highlight,.theme-dark .chat .title-wrap .topic .highlight{transition:.3s ease-in-out all;background:rgba(10, 9, 9, 0.35);}

.guilds .friends-icon:hover{background-color:var(--main-color);}

.flex-vertical.channels-wrap{width:230px;}

.theme-dark .channel-members .member.popout-open,.theme-dark .channel-members .member:hover{background:linear-gradient(to right, #121213 85%, #19191b) !important;}

.user-popout .avatar-wrapper .avatar-popout{border:2px solid #141417;background-color:var(--hover-color);}

.user-popout .header{background:#141417;height:100px;}

.user-popout .body{background:#111113;}

.user-popout .footer{background:#0e0e0e;border-top:2px solid var(--hover-color);}

.member-roles .member-role{color:var(--hover-color);}

.quick-message{background:#0b0b0c;border:2px solid var(--hover-color);color:#adadad;}

.user-popout .username-wrapper .activity{color:#c7c7c7;}

.protip,.user-popout .body .section .label{color:#c7c7c7;}

.bot-tag.bot-tag-invert{background:var(--main-color);color:#e8e8e8!important;}

.guilds-wrapper .guilds .guild.active:first-of-type .guild-inner{background:var(--main-color) !important;}

.user-popout .username-wrapper.has-nickname .discriminator,.user-popout .username-wrapper.has-nickname .username{color:#b5b5b5;}

#user-profile-modal{opacity:1;position:relative;}

#user-profile-modal .avatar-wrapper .avatar-profile,#user-profile-modal .sub-header,#user-profile-modal .scroller-wrap,#user-profile-modal .empty,#user-profile-modal .scroller{background-color:#141415 !important;}

#user-profile-modal .header:before{content:"";width:100%;height:100px;background-size:cover;background-position:center center;background-repeat:no-repeat;position:absolute;top:0;right:0;left:0;z-index:-1;}

#user-profile-modal .header .activity{margin-left:-50px;margin-top:-4px;padding-top:13px !important;}

#user-profile-modal .header .discord-tag .username,#user-profile-modal .header .activity{text-shadow:1px 1px 1px rgba(0, 0, 0, 0.3);}

#user-profile-modal .header .discord-tag .discriminator{display:inline;background:rgba(93, 93, 93, 0.3);font-weight:600;color:#fff;margin-left:8px;padding:3px 5px;border-radius:3px;-webkit-user-select:none;opacity:1;transition:opacity 300ms;}

#user-profile-modal .avatar-profile .status{border:4px solid #19191b;}

#user-profile-modal .avatar-wrapper .avatar-profile{border-color:#19191b;box-shadow:1px 1px 2px rgba(0, 0, 0, 0.3);left:20px;}

#user-profile-modal .avatar-wrapper .avatar-profile .status{box-shadow:1px 1px 2px rgba(0, 0, 0, 0.3);right:0;bottom:0;left:0;width:100%;height:100%;border-radius:5px;}

#user-profile-modal .header{background-color:#121213;background-image:none;}

#user-profile-modal .tab-bar-container{border:0!important;position:absolute;top:120px;right:0;padding:0;width:80px;height:100%;justify-content:center;transition:width 500ms;transition-timing-function:cubic-bezier(0.52, 1.64, 0.37, 0.66);z-index:1;background-color:#121213;-webkit-background-size:270px 213px;-moz-background-size:270px 213px;background-size:270px 213px;}

#user-profile-modal .tab-bar-container:before{content:"...";position:absolute;top:0;left:0;width:10px;height:100%;padding-top:180px;background:transparent;writing-mode:vertical-lr;color:transparent;font-size:18px;font-weight:700;letter-spacing:15px;line-height:20px;cursor:pointer;transition:letter-spacing 300ms, padding 300ms;;}

#user-profile-modal .tab-bar-container:hover{width:180px;}

#user-profile-modal .tab-bar-container .tab-bar{background:transparent;border:0!important;flex-flow:column;position:absolute;top:40px;left:35px;}

#user-profile-modal .tab-bar-container .tab-bar-item{padding:10px 25px;position:relative;font-size:16px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}

#user-profile-modal .tab-bar-container .tab-bar-item,#user-profile-modal .tab-bar-container .tab-bar-item:hover,#user-profile-modal .tab-bar-container .tab-bar-item.selected{color:transparent!important;}

#user-profile-modal .tab-bar-container:hover .tab-bar-item{color:#ececec!important;opacity:1;transition:color 500ms;}

#user-profile-modal .tab-bar-container:hover .tab-bar-item:hover,#user-profile-modal .tab-bar-container:hover .tab-bar-item.selected{color:#fff!important;}

#user-profile-modal .tab-bar-container .tab-bar-item:before{content:"";position:absolute;top:7px;left:0;width:18px;height:18px;background-position:center center;background-repeat:no-repeat;background-size:18px 18px;opacity:0.5;transition:opacity 500ms;}

#user-profile-modal .tab-bar-container .tab-bar-item:hover:before,#user-profile-modal .tab-bar-container .tab-bar-item.selected:before{opacity:1;}

#user-profile-modal .tab-bar-container .tab-bar-item:nth-child(1):before{background-image:url(data:image/svg+xml;utf8;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pgo8IS0tIEdlbmVyYXRvcjogQWRvYmUgSWxsdXN0cmF0b3IgMTYuMC4wLCBTVkcgRXhwb3J0IFBsdWctSW4gLiBTVkcgVmVyc2lvbjogNi4wMCBCdWlsZCAwKSAgLS0+CjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4PSIwcHgiIHk9IjBweCIgd2lkdGg9IjY0cHgiIGhlaWdodD0iNjRweCIgdmlld0JveD0iMCAwIDQwOS4xNjUgNDA5LjE2NCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgNDA5LjE2NSA0MDkuMTY0OyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+CjxnPgoJPGc+CgkJPHBhdGggZD0iTTIwNC41ODMsMjE2LjY3MWM1MC42NjQsMCw5MS43NC00OC4wNzUsOTEuNzQtMTA3LjM3OGMwLTgyLjIzNy00MS4wNzQtMTA3LjM3Ny05MS43NC0xMDcuMzc3ICAgIGMtNTAuNjY4LDAtOTEuNzQsMjUuMTQtOTEuNzQsMTA3LjM3N0MxMTIuODQ0LDE2OC41OTYsMTUzLjkxNiwyMTYuNjcxLDIwNC41ODMsMjE2LjY3MXoiIGZpbGw9IiNGRkZGRkYiLz4KCQk8cGF0aCBkPSJNNDA3LjE2NCwzNzQuNzE3TDM2MC44OCwyNzAuNDU0Yy0yLjExNy00Ljc3MS01LjgzNi04LjcyOC0xMC40NjUtMTEuMTM4bC03MS44My0zNy4zOTIgICAgYy0xLjU4NC0wLjgyMy0zLjUwMi0wLjY2My00LjkyNiwwLjQxNWMtMjAuMzE2LDE1LjM2Ni00NC4yMDMsMjMuNDg4LTY5LjA3NiwyMy40ODhjLTI0Ljg3NywwLTQ4Ljc2Mi04LjEyMi02OS4wNzgtMjMuNDg4ICAgIGMtMS40MjgtMS4wNzgtMy4zNDYtMS4yMzgtNC45My0wLjQxNUw1OC43NSwyNTkuMzE2Yy00LjYzMSwyLjQxLTguMzQ2LDYuMzY1LTEwLjQ2NSwxMS4xMzhMMi4wMDEsMzc0LjcxNyAgICBjLTMuMTkxLDcuMTg4LTIuNTM3LDE1LjQxMiwxLjc1LDIyLjAwNWM0LjI4NSw2LjU5MiwxMS41MzcsMTAuNTI2LDE5LjQsMTAuNTI2aDM2Mi44NjFjNy44NjMsMCwxNS4xMTctMy45MzYsMTkuNDAyLTEwLjUyNyAgICBDNDA5LjY5OSwzOTAuMTI5LDQxMC4zNTUsMzgxLjkwMiw0MDcuMTY0LDM3NC43MTd6IiBmaWxsPSIjRkZGRkZGIi8+Cgk8L2c+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPC9zdmc+Cg==);}

#user-profile-modal .tab-bar-container .tab-bar-item:nth-child(2):before{background-image:url(data:image/svg+xml;utf8;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pgo8IS0tIEdlbmVyYXRvcjogQWRvYmUgSWxsdXN0cmF0b3IgMTYuMC4wLCBTVkcgRXhwb3J0IFBsdWctSW4gLiBTVkcgVmVyc2lvbjogNi4wMCBCdWlsZCAwKSAgLS0+CjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4PSIwcHgiIHk9IjBweCIgd2lkdGg9IjY0cHgiIGhlaWdodD0iNjRweCIgdmlld0JveD0iMCAwIDk3Ljk2OCA5Ny45NjgiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDk3Ljk2OCA5Ny45Njg7IiB4bWw6c3BhY2U9InByZXNlcnZlIj4KPGc+Cgk8Zz4KCQk8cGF0aCBkPSJNNDkuNTQxLDM4LjY1NWMxLjYxNywwLDMuMTU4LDAuMzM4LDQuNTU5LDAuOTQ2YzAuMTA1LTIuMjg2LDAuODkzLTQuNCwyLjE1Ny02LjE1Yy0wLjg5LTAuMTg2LTEuODA4LTAuMjg1LTIuNzQ4LTAuMjg1ICAgIGgtOC45MDZjLTAuOTM4LDAtMS44NTYsMC4wOTgtMi43MzksMC4yODJjMS4zNDcsMS44NjksMi4xNTIsNC4xNSwyLjE2NSw2LjYyQzQ1LjY2NiwzOS4xNjgsNDcuNTQ0LDM4LjY1NSw0OS41NDEsMzguNjU1eiIgZmlsbD0iI0ZGRkZGRiIvPgoJCTxjaXJjbGUgY3g9IjQ5LjA1NCIgY3k9IjIxLjk1NCIgcj0iMTAuNDk2IiBmaWxsPSIjRkZGRkZGIi8+CgkJPHBhdGggZD0iTTY1LjUzOSw1MC4zNmM1LjM0MiwwLDkuNjctNC4zMyw5LjY3LTkuNjdjMC01LjM0Mi00LjMyOC05LjY3LTkuNjctOS42N2MtNS4yOTIsMC05LjU4Myw0LjI1MS05LjY2Myw5LjUyNCAgICBjMy4wNDksMS45MTIsNS4xODcsNS4xNDYsNS41NzcsOC45QzYyLjY5NSw1MC4wMjYsNjQuMDc2LDUwLjM2LDY1LjUzOSw1MC4zNnoiIGZpbGw9IiNGRkZGRkYiLz4KCQk8cGF0aCBkPSJNMzIuNTcxLDMxLjAxOWMtNS4zNDMsMC05LjY3MSw0LjMyOS05LjY3MSw5LjY3czQuMzI4LDkuNjY5LDkuNjcxLDkuNjY5YzEuODkyLDAsMy42NTEtMC41NTMsNS4xNDMtMS40OTIgICAgYzAuNDc1LTMuMDkxLDIuMTMyLTUuNzk0LDQuNDk5LTcuNjM0YzAuMDEtMC4xODEsMC4wMjctMC4zNiwwLjAyNy0wLjU0M0M0Mi4yNCwzNS4zNDgsMzcuOTEsMzEuMDE5LDMyLjU3MSwzMS4wMTl6IiBmaWxsPSIjRkZGRkZGIi8+CgkJPHBhdGggZD0iTTcxLjgyLDMwLjgxM2MzLjA0OSwxLjkxMiw1LjE4Nyw1LjE0Niw1LjU3Niw4LjkwMWMxLjI0MSwwLjU4MSwyLjYyMywwLjkxNiw0LjA4NiwwLjkxNmM1LjM0MiwwLDkuNjctNC4zMjksOS42Ny05LjY3ICAgIGMwLTUuMzQxLTQuMzI4LTkuNjctOS42Ny05LjY3Qzc2LjE5MSwyMS4yODksNzEuOSwyNS41NDEsNzEuODIsMzAuODEzeiIgZmlsbD0iI0ZGRkZGRiIvPgoJCTxjaXJjbGUgY3g9IjQ5LjU0MSIgY3k9IjUwLjY3MyIgcj0iOS42NzEiIGZpbGw9IiNGRkZGRkYiLz4KCQk8cGF0aCBkPSJNNjkuNjQzLDUxLjAxOWgtOC4xNDRjLTAuMDg5LDMuMjU4LTEuNDc5LDYuMTkyLTMuNjc5LDguMzAxYzYuMDY4LDEuODA2LDEwLjUwOSw3LjQzNCwxMC41MDksMTQuMDgydjMuMDkyICAgIGM4LjA0LTAuMjk3LDEyLjY3NC0yLjU3MywxMi45NzktMi43MjlsMC42NDYtMC4zMjhoMC4wNjdWNjMuNDAxQzgyLjAyMyw1Ni41NzMsNzYuNDY5LDUxLjAxOSw2OS42NDMsNTEuMDE5eiIgZmlsbD0iI0ZGRkZGRiIvPgoJCTxwYXRoIGQ9Ik04NS41ODUsNDEuMjg5aC04LjE0MmMtMC4wODgsMy4yNTgtMS40NzksNi4xOTItMy42NzgsOC4zMDFjNi4wNjgsMS44MDYsMTAuNTA4LDcuNDMzLDEwLjUwOCwxNC4wODF2My4wOTIgICAgYzguMDM5LTAuMjk2LDEyLjY3NC0yLjU3MiwxMi45NzktMi43MjlsMC42NDYtMC4zMjdoMC4wNjlWNTMuNjcxQzk3Ljk2Nyw0Ni44NDQsOTIuNDEzLDQxLjI4OSw4NS41ODUsNDEuMjg5eiIgZmlsbD0iI0ZGRkZGRiIvPgoJCTxwYXRoIGQ9Ik00MS4yNTYsNTkuMzE5Yy0yLjE4OS0yLjA5OS0zLjU3NS01LjAxNy0zLjY3Ny04LjI1NGMtMC4zMDEtMC4wMjItMC42LTAuMDQ3LTAuOTA4LTAuMDQ3aC04LjIwMyAgICBjLTYuODI4LDAtMTIuMzgzLDUuNTU1LTEyLjM4MywxMi4zODN2MTAuMDM3bDAuMDI1LDAuMTU1bDAuNjkxLDAuMjE4YzUuMjI3LDEuNjMzLDkuODkzLDIuMzgzLDEzLjk0NCwyLjYyMXYtMy4wMzEgICAgQzMwLjc0Nyw2Ni43NTQsMzUuMTg2LDYxLjEyNiw0MS4yNTYsNTkuMzE5eiIgZmlsbD0iI0ZGRkZGRiIvPgoJCTxwYXRoIGQ9Ik01My42NDMsNjEuMDAzaC04LjIwNmMtNi44MjgsMC0xMi4zODMsNS41NTctMTIuMzgzLDEyLjM4MnYxMC4wMzdsMC4wMjYsMC4xNTdsMC42OSwwLjIxNiAgICBjNi41MTYsMi4wMzUsMTIuMTc3LDIuNzE1LDE2LjgzNSwyLjcxNWM5LjEwMSwwLDE0LjM3NS0yLjU5NSwxNC43MDEtMi43NmwwLjY0Ni0wLjMyOGgwLjA2OFY3My4zODUgICAgQzY2LjAyMyw2Ni41NTgsNjAuNDY5LDYxLjAwMyw1My42NDMsNjEuMDAzeiIgZmlsbD0iI0ZGRkZGRiIvPgoJCTxwYXRoIGQ9Ik0xNi40ODYsNDAuOTM4YzEuNDYzLDAsMi44NDQtMC4zMzUsNC4wODYtMC45MTZjMC4zOS0zLjc1NSwyLjUyNy02Ljk5LDUuNTc2LTguOTAyYy0wLjA4LTUuMjcxLTQuMzcxLTkuNTIzLTkuNjYyLTkuNTIzICAgIGMtNS4zNDMsMC05LjY3MSw0LjMyOS05LjY3MSw5LjY3MUM2LjgxNSwzNi42MDksMTEuMTQzLDQwLjkzOCwxNi40ODYsNDAuOTM4eiIgZmlsbD0iI0ZGRkZGRiIvPgoJCTxwYXRoIGQ9Ik0yNC4yMDIsNDkuODk5Yy0yLjE5OC0yLjEwOS0zLjU4OS01LjA0NC0zLjY3Ny04LjMwM2gtOC4xNDNDNS41NTQsNDEuNTk3LDAsNDcuMTUyLDAsNTMuOTc5djEwLjAzN2gwLjA2OWwwLjY0NiwwLjMyNyAgICBjMC4zMDYsMC4xNTQsNC45MzksMi40MzMsMTIuOTc5LDIuNzI4di0zLjA5MkMxMy42OTQsNTcuMzMyLDE4LjEzMyw1MS43MDQsMjQuMjAyLDQ5Ljg5OXoiIGZpbGw9IiNGRkZGRkYiLz4KCQk8cGF0aCBkPSJNMjcuNzk2LDMwLjA2M2MxLjE2LTAuNDcsMi45My0xLjA0Nyw0LjYyLTEuMDQ3YzEuOTY3LDAsMy44OTEsMC41MDYsNS42MDcsMS40NjljMC4zODItMC4zNzUsMC43MzItMC43ODMsMS4wNS0xLjIyICAgIGMtMS42My0yLjE0MS0yLjUyLTQuNzY1LTIuNTItNy40NjRjMC0xLjgxOCwwLjQwNi0zLjYyMiwxLjE4LTUuMjYxYy0xLjc2Mi0xLjU5Mi00LjAxLTIuNDYxLTYuMzk5LTIuNDYxICAgIGMtNC4zNDgsMC04LjEzMywyLjk0My05LjI0MSw3LjA4OEMyNS4zNDEsMjMuMDU3LDI3LjQ1NywyNi4zNjEsMjcuNzk2LDMwLjA2M3oiIGZpbGw9IiNGRkZGRkYiLz4KCQk8cGF0aCBkPSJNNTkuMTE3LDI4LjcxOGMwLjMzNiwwLjUzNCwwLjcyOSwxLjAzNywxLjE3NSwxLjUwNWMxLjU4OC0wLjc5MiwzLjMzNC0xLjIwOCw1LjA5Mi0xLjIwOCAgICBjMS43MjksMCwzLjM4NiwwLjQ0Miw0LjQ3MiwwLjgxMmMwLjM0LTQuMDEzLDIuNzY3LTcuNTU1LDYuNC05LjM1Yy0xLjMzMi0zLjgwNS00LjkzOC02LjQwMi05LjAyMS02LjQwMiAgICBjLTIuNjQsMC01LjE0LDEuMDg0LTYuOTQ1LDIuOTkyYzAuNjM0LDEuNTEyLDAuOTU1LDMuMTAxLDAuOTU1LDQuNzNDNjEuMjQ0LDI0LjI5Miw2MC41MSwyNi42Nyw1OS4xMTcsMjguNzE4eiIgZmlsbD0iI0ZGRkZGRiIvPgoJPC9nPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+Cjwvc3ZnPgo=);}

#user-profile-modal .tab-bar-container .tab-bar-item:nth-child(3):before{background-image:url(data:image/svg+xml;utf8;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pgo8IS0tIEdlbmVyYXRvcjogQWRvYmUgSWxsdXN0cmF0b3IgMTYuMC4wLCBTVkcgRXhwb3J0IFBsdWctSW4gLiBTVkcgVmVyc2lvbjogNi4wMCBCdWlsZCAwKSAgLS0+CjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4PSIwcHgiIHk9IjBweCIgd2lkdGg9IjY0cHgiIGhlaWdodD0iNjRweCIgdmlld0JveD0iMCAwIDQ2Ni40OCA0NjYuNDgiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDQ2Ni40OCA0NjYuNDg7IiB4bWw6c3BhY2U9InByZXNlcnZlIj4KPGc+Cgk8ZyBpZD0iaWNvbnNfMjRfIj4KCQk8Zz4KCQkJPGc+CgkJCQk8cGF0aCBkPSJNMTEzLjc3NCwxMTcuNWwwLjAwMSwwLjAwNmMwLjAyLTAuMDA0LDAuMDM5LTAuMDEsMC4wNi0wLjAxNGMwLjAxOS0wLjAwMiwwLjA0LTAuMDAzLDAuMDU5LTAuMDA2bC0wLjAwMS0wLjAwNSAgICAgIGMyMC44MjUtMy44LDM0Ljg0NS0yMy41OTEsMzEuNDA0LTQ0LjU2M2MtMy40NDItMjAuOTctMjMuMDQ5LTM1LjI0My00My45OTYtMzIuMTg4di0wLjAwNWMtMC4wMiwwLjAwMy0wLjAzOSwwLjAwOC0wLjA1OSwwLjAxMiAgICAgIGMtMC4wMTksMC4wMDMtMC4wMzksMC4wMDQtMC4wNiwwLjAwOGwwLjAwMSwwLjAwNGMtMjAuODIyLDMuOC0zNC44NDMsMjMuNTg5LTMxLjQwMyw0NC41NTkgICAgICBDNzMuMjIxLDEwNi4yNzksOTIuODMxLDEyMC41NTMsMTEzLjc3NCwxMTcuNXoiIGZpbGw9IiNGRkZGRkYiLz4KCQkJCTxwYXRoIGQ9Ik0yNTYuNjUsMzQ3LjEwOGwtNzUuMTcxLTc2LjE4Yy01LjE2MS02LjE3OS0xOS4wODItOTMuNzc5LTE5LjY3OS05Ny40MTZjLTEuNTMtOS4zMjMsMS4xMTYtMTUuMjQsMS4xMTYtMTUuMjQgICAgICBzMzcuNzc5LTk3LjA2Myw0MS42MDYtMTA3Ljc0OWMzLjgyOS0xMC42ODcsMy42MS0xNy42NzYtMy43NzEtMjIuOTgxYy03LjM4OS01LjMwNy0xOS45OTQtNS40NjUtMjIuOTg0LDMuNzcxbC00MC40NzUsOTcuMTE5ICAgICAgYzAsMC0xMC4zMTctMy43Ni0yMS43MTItMi4wODhjLTAuMDk2LDAuMDE4LTAuMTg4LDAuMDM2LTAuMjg0LDAuMDU1Yy0wLjA5NSwwLjAxNC0wLjE4OCwwLjAyMy0wLjI4NiwwLjAzOSAgICAgIGMtMTEuMzI5LDIuMDU3LTE5LjkwNiw4LjkxNy0xOS45MDYsOC45MTdMMjUuNzE5LDU2LjI2MWMtOC4xODktOC0xNy42NzgtMy42MTktMjIuOTg1LDMuNzcxICAgICAgYy01LjI5OCw3LjM4NS0yLjI3NCwxNS43MTQsMy43NywyMi45ODFjNi4wNDQsNy4yNjgsNzMuODU2LDg4LjgwNyw3My44NTYsODguODA3czQuMzk1LDQuNzYyLDUuOTI0LDE0LjA4NCAgICAgIGMwLjEyMSwwLjc0LDAuMTU2LDAuOTUzLDE0LjY5NCw4OS41MzhsOS43NTMsMTQ5Ljg3NmMwLjYzNiw5Ljc3MSw4Ljc2LDE3LjI3MiwxOC40MTUsMTcuMjcyYzAuNDAzLDAsMC44MS0wLjAxMywxLjIxOC0wLjAzOSAgICAgIGMxMC4xOC0wLjY2MywxNy44OTYtOS40NTMsMTcuMjMzLTE5LjYzM2MwLDAtOC43OTItMTMwLjMyMy04Ljc5Mi0xMzUuMTE1YzAtMi45NDIsMi44NjUtNC42Miw2LjI0My0xLjE5NSAgICAgIGMzLjM3OCwzLjQyMyw4NS4zMDYsODYuNDQ5LDg1LjMwNiw4Ni40NDljNy4xNjUsNy4yNjEsMTguODYxLDcuMzQsMjYuMTIzLDAuMTc0ICAgICAgQzI2My43MzcsMzY2LjA2NCwyNjMuODE1LDM1NC4zNjksMjU2LjY1LDM0Ny4xMDh6IiBmaWxsPSIjRkZGRkZGIi8+CgkJCTwvZz4KCQkJPGc+CgkJCQk8cGF0aCBkPSJNMzQxLjQxNSwxNTMuNTY2bC0wLjAwMiwwLjAwNGMwLjAxNiwwLjAwNiwwLjAyOSwwLjAwOCwwLjA0NSwwLjAxM2MwLjAxNywwLjAwNSwwLjAyOCwwLjAxMiwwLjA0NCwwLjAxN2wwLjAwMi0wLjAwMyAgICAgIGMwLjEzMywwLjA0MywwLjI2NiwwLjA3NywwLjM5NiwwLjExN2MwLjEzLDAuMDQ5LDAuMjU2LDAuMTA0LDAuMzg3LDAuMTUxbC0wLjAwMiwwLjAwNGMwLjAxNywwLjAwNCwwLjAyOSwwLjAwOCwwLjA0NiwwLjAxMyAgICAgIGMwLjAxNCwwLjAwNCwwLjAyNywwLjAxMiwwLjA0MywwLjAxN2wwLjAwMS0wLjAwM2MxNS42NzQsNS4wNjEsMzIuNTcyLTMuMzQ0LDM3LjkzNi0xOC45ODkgICAgICBjNS4zNjItMTUuNjQzLTIuODI2LTMyLjY0Ni0xOC4zMDktMzguMjYzbDAuMDAxLTAuMDAzYy0wLjAxNy0wLjAwNi0wLjAzLTAuMDEtMC4wNDctMC4wMTQgICAgICBjLTAuMDE0LTAuMDA1LTAuMDI3LTAuMDExLTAuMDQzLTAuMDE3bC0wLjAwMSwwLjAwM2MtMC4xMzMtMC4wNDItMC4yNjUtMC4wNzctMC4zOTYtMC4xMTdjLTAuMTMtMC4wNDktMC4yNTUtMC4xMDMtMC4zODgtMC4xNTEgICAgICBsMC4wMDQtMC4wMDNjLTAuMDE2LTAuMDA2LTAuMDMxLTAuMDA4LTAuMDQ2LTAuMDE0Yy0wLjAxNi0wLjAwNC0wLjAyOC0wLjAxMS0wLjA0NS0wLjAxNmwtMC4wMDEsMC4wMDMgICAgICBjLTE1LjY3My01LjA2Mi0zMi41NjksMy4zNDMtMzcuOTMyLDE4Ljk4NVMzMjUuOTMxLDE0Ny45NDksMzQxLjQxNSwxNTMuNTY2eiIgZmlsbD0iI0ZGRkZGRiIvPgoJCQkJPHBhdGggZD0iTTQ2Ni4wMTYsMTY2LjA5NmMtMS41OTEtNi44OTgtOC4yODUtOS45MDgtMjAuMzc1LTcuMzkzbC05MC43Myw5Ljc2NmMwLDAtNC4yMzUtNS4wNTMtMTUuMDg4LTguNzcyICAgICAgYy0xMC44NTMtMy43Mi0xNy4yNS0yLjMxMy0xNy4yNS0yLjMxM2wtNjUuNjU4LTYzLjM3M2MtOC4wMDQtOS40MDQtMTUuMTM4LTExLjEzNC0yMC42MjUtNi42NjMgICAgICBjLTYuNjA0LDUuMzgtNy44MjIsMTMuODg5LTMuOTU1LDE4LjY5MWM1LjgzLDcuMjQxLDY0LjU3Niw2Ny40NjIsNjYuNzA0LDcwLjkxMmMyLjEyOCwzLjQ1MSwxLjI2Miw0Ljg4My0xLjEyNSwxMS44MzcgICAgICBjLTEuMDEzLDIuOTU1LTE2LjYyOSw0Ni40NjktMjIuNTUyLDYyLjYwMWwtNzcuNTY5LDUyLjI3MWMtNi43NjgsNC41NjEtOC41NTcsMTMuNzQ1LTMuOTk3LDIwLjUxMyAgICAgIGM0LjU2LDYuNzY5LDEzLjc0NCw4LjU1OSwyMC41MTMsMy45OTdjMCwwLDgxLjgwMi01NC45NzEsODMuNzgyLTU2LjQ1NmMxLjk4LTEuNDg1LDQuNjM0LTAuNTU0LDMuNzM5LDIuMjY4ICAgICAgYy0wLjg5NCwyLjgyLTM1LjEwNCwxMTAuODctMzUuMTA0LDExMC44N2MtMi40NjQsNy43ODEsMS44NDcsMTYuMDg1LDkuNjI4LDE4LjU0OWMxLjQ4MywwLjQ3MSwyLjk4NiwwLjY5Myw0LjQ2NCwwLjY5MyAgICAgIGM2LjI3MSwwLDEyLjA5MS00LjAyMiwxNC4wODUtMTAuMzJsMzguNjExLTEyMS45NDZjMC4xNjMtMC41MTUsMC4yODYtMS4wMzQsMC4zOTEtMS41NTQgICAgICBjMjEuOTQ3LTY0LjAxNCwyMS43ODctNjMuNTQ5LDIxLjIxMy02MS44NzVjMi4zODQtNi45NTQsMi41NzgtOC42MTgsNi4zNzQtMTAuMDM3czg3LjEzNC0xMi45MzUsOTYuMTgzLTE1LjA3NyAgICAgIEM0NjMuNjcyLDE4MS44NjIsNDY3LjkzLDE3NC4zOTYsNDY2LjAxNiwxNjYuMDk2eiIgZmlsbD0iI0ZGRkZGRiIvPgoJCQk8L2c+CgkJPC9nPgoJPC9nPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+Cjwvc3ZnPgo=);}

#user-profile-modal .tab-bar-container .tab-bar-item:first-child{margin-top:90px;}

#user-profile-modal .tab-bar-container .tab-bar-item:hover,#user-profile-modal .tab-bar-container .tab-bar-item.selected{border:0!important;}

#user-profile-modal .tab-bar-container .tab-bar-item + .tab-bar-item{margin:0;}

#user-profile-modal .scroller-wrap{height:380px;}

#user-profile-modal .scroller-wrap .scroller{margin-top:15px;animation:sw-fade 300ms ease-in-out;}

@keyframes sw-fade{0%{opacity:0;}

100%{opacity:1;}

}

#user-profile-modal .guilds .section .section-header{color:#6c82ce;}

#user-profile-modal .guilds .section + .section{border:0!important;}

#user-profile-modal .guilds .section .note textarea:focus{background-color:rgba(0, 0, 0, 0.15);border:1px solid rgba(0, 0, 0, 0.1);color:#e4e4e4;}

#user-profile-modal .guilds .section .connected-account .connected-account-name a{color:rgba(0, 176, 244, 0.6);font-weight:700;transition:color 500ms;}

#user-profile-modal .guilds .section .connected-account:hover .connected-account-name a{color:rgba(0, 176, 244, 1);}

#user-profile-modal .guilds .guild{color:#c1c1c1;margin:0 10px;transition:background 300ms;}

#user-profile-modal .guilds .guild .avatar-large{box-shadow:1px 1px 2px rgba(0, 0, 0, 0.3);}

#user-profile-modal .guilds .guild .avatar-large:empty{border-radius:15px!important;}

#user-profile-modal .guilds .guild:hover{border-radius:5px;color:#fff;}

#user-profile-modal .guilds .guild .status{border:2px solid rgba(64, 68, 74, 1);}

#user-profile-modal .guilds .guild:hover .status{border:2px solid rgba(133, 141, 150, 0.7);}

#user-profile-modal .guilds .guild .guild-name .discriminator{display:none;}

#user-profile-modal .guilds .guild:hover .guild-name .discriminator{display:block;}

#user-profile-modal .header .header-info .badge-premium{background-image:url(data:image/svg+xml;utf8;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pgo8IS0tIEdlbmVyYXRvcjogQWRvYmUgSWxsdXN0cmF0b3IgMTYuMC4wLCBTVkcgRXhwb3J0IFBsdWctSW4gLiBTVkcgVmVyc2lvbjogNi4wMCBCdWlsZCAwKSAgLS0+CjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4PSIwcHgiIHk9IjBweCIgd2lkdGg9IjY0cHgiIGhlaWdodD0iNjRweCIgdmlld0JveD0iMCAwIDM5LjgzNiAzOS44MzUiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDM5LjgzNiAzOS44MzU7IiB4bWw6c3BhY2U9InByZXNlcnZlIj4KPGc+Cgk8cGF0aCBkPSJNMzkuODM2LDE0Ljc0MmMwLDEuMjU5LTAuMTkzLDIuNTA0LTAuNTc0LDMuNzAxYy0xLjk3Nyw4LjMzNi0xNi4zNjcsMTcuNTgzLTE4LjAwOCwxOC42MTQgICBjLTAuNDA2LDAuMjU2LTAuODY5LDAuMzgzLTEuMzMsMC4zODNjLTAuNDYzLDAtMC45MjQtMC4xMjctMS4zMy0wLjM4M0MxNi45NTEsMzYuMDI1LDIuNTQ3LDI2Ljc3NSwwLjU3NiwxOC40NCAgIEMwLjE5MywxNy4yMzQsMCwxNS45OSwwLDE0Ljc0MUMwLDEwLjI1LDIuNDQzLDYuMTA5LDYuMzc5LDMuOTMyYzEuODI2LTEuMDA1LDMuODg3LTEuNTM2LDUuOTU5LTEuNTM2ICAgYzIuNzc5LDAsNS40MzQsMC45MjYsNy41ODIsMi41OTljMi4xNDUtMS42NzMsNC43OTctMi41OTksNy41NzYtMi41OTljMi4wOCwwLDQuMTQxLDAuNTMxLDUuOTU5LDEuNTM1ICAgQzM3LjM5Myw2LjEwOSwzOS44MzYsMTAuMjUxLDM5LjgzNiwxNC43NDJ6IiBmaWxsPSIjRDgwMDI3Ii8+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPC9zdmc+Cg==)!important;background-position:center;background-size:75%;width:30px;height:40px;position:absolute;padding:0;opacity:0.9;}

#user-profile-modal footer .btn.add-friend{transition:background 500ms;}

#user-profile-modal .scroller-wrap .scroller::-webkit-scrollbar{width:0px;}

#user-profile-modal footer{border-top:1px solid transparent;background:#141415 !important;z-index:10;}

#user-profile-modal .guilds .section{margin-left:47px;margin-right:29px;padding-top:17px;padding-bottom:25px;}

#friends .friends-header{position:relative;height:46px !important;}

#friends .friends-header .tab-bar{width:100%;position:absolute;top:70px;display:flex;justify-content:center;z-index:2;}

#friends .friends-header .header-toolbar{position:absolute;right:20px;}

#friends .friends-table .friends-table-body{padding:0;margin:40px 0 0;}

#friends .friends-header .tab-bar .tab-bar-separator,#friends .friends-table .friends-table-header .friends-column-separator{display:none;}

#friends .friends-header .tab-bar .tab-bar-item,#friends .friends-table .friends-table-header .friends-column,#friends .friends-table .friends-row .friends-column-name,#friends .friends-table .friends-row .friends-column-status{color:rgba(255, 255, 255, 0.6)!important;}

#friends .friends-header .btn,#friends .friends-header .tab-bar .tab-bar-item.selected{background-color:var(--main-color) !important;color:#fff !important;}

#friends .friends-header .tab-bar .tab-bar-item:hover:not(.selected){background-color:var(--hover-color) !important;}

#friends .friends-header .tab-bar .tab-bar-item{padding:5px 8px;margin:0 5px;transition:color 500ms, background 500ms;}

#friends .friends-header .tab-bar .tab-bar-item .badge{background:rgba(0, 0, 0, 0.2)!important;color:#fff!important;opacity:0.7;transition:opacity 500ms;}

#friends .friends-header .tab-bar .tab-bar-item:hover .badge{opacity:1;}

#friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary{background-color:var(--main-color) !important;color:#fff !important;}

#friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary:not(.selected):hover{background-color:var(--hover-color);}

#friends .friends-table{padding-top:11px;}

#friends .friends-table .friend-table-add-wrapper{margin-top:20px;}

#friends .friends-table .friend-table-add-wrapper .friend-table-add-header{background:rgba(0, 0, 0, 0.2);box-shadow:1px 1px 2px 1px rgba(0, 0, 0, 0.3);margin:20px 30px;border-radius:5px;}

#friends .friends-table .friend-table-add-wrapper h2{color:rgba(225, 225, 225, 0.9);}

#friends .friends-table .friend-table-add-wrapper .friend-table-suggestions-header{margin:30px 30px 16px;padding:0;border-bottom:1px solid rgba(206, 196, 196, 0.6);}

#friends .friends-table .friend-table-add-wrapper .friend-table-suggestions-header h2{color:rgba(225, 225, 225, 0.9);}

#friends .friends-table .friends-table-header{display:none;}

#friends .friends-table .friends-table-body > span{display:flex;flex-flow:row wrap;justify-content:center;}

#friends .friends-table .friends-row{background:rgba(0, 0, 0, 0.2)!important;box-shadow:1px 1px 2px rgba(0, 0, 0, 0.5);border-radius:5px;margin:15px;padding:0;height:120px!important;flex-direction:column;flex-basis:300px;position:relative;transition:opacity 300ms;}

#friends .friends-table .friends-row:hover{box-shadow:1px 1px 2px rgba(0, 0, 0, 0.5);border-radius:5px;margin:15px;padding:0;opacity:1!important;}

#friends .friends-table .friends-row .avatar-small{border-radius:5px;box-shadow:1px 1px 2px rgba(0, 0, 0, 0.3);}

#friends .friends-table .friends-row + .friends-row{border-top:none!important;}

#friends .friends-table .friends-row .friends-column{position:absolute;backface-visibility:hidden;}

#friends .friends-table .friends-row .friends-column + .friends-column{margin:0;}

#friends .friends-table .friends-row .friends-column-name .avatar-small{top:25px;left:15px;width:85px;height:85px;background-size:85px 85px;opacity:0.6;transition:opacity 500ms, transform .2s linear, box-shadow .2s linear;transform: scale(0.97) perspective(1px);}

#friends .friends-table .friends-row:hover .friends-column-name .avatar-small{opacity:0.9;transform: scale(1) perspective(1px);box-shadow: 1px 1px 8px 1px #000;}

#friends .friends-table .friends-row .friends-column-name .discord-tag{display:block;position:absolute;top:25px;left:115px;text-shadow:1px 1px 1px rgba(0, 0, 0, 0.3);}

#friends .friends-table .friends-row .friends-column-name .discord-tag .username{clear:left;float:left;width:100px;text-overflow:ellipsis;white-space:nowrap;overflow:hidden;}

#friends .friends-table .friends-row .friends-column-name .discord-tag .discriminator{visibility:visible;}

#friends .friends-table .friends-row .friends-column-name .username{transition:color 300ms;}

#friends .friends-table .friends-row:hover .username{color:rgba(225, 225, 225, 1);}

#friends .friends-table .friends-row .friends-column-status{top:0;width:100%;justify-content:center;height:18px;}

#friends .friends-table .friends-row .friends-column-status .status{width:100%;height:20px;border-radius:5px 5px 0 0 !important;position:absolute;top:0;opacity:0.5;z-index:0;}

#friends .friends-table .friends-row .friends-column-status .status-text{color:rgba(255, 255, 255, 0.5);font-weight:800 !important;max-width:90%;font-size:12px;line-height:normal;transition:color 300ms;z-index:0;}

#friends .friends-table .friends-row:hover .friends-column-status .status-text{color:#fff;}

#friends .friends-table .friends-table-body .friends-row .friends-column-guilds{/* .friends-table-body is important here */
top:80px;left:115px;width:150px;display:flex!important;}

#friends .friends-table .friends-table-body .friends-row .friends-column-guilds .avatar-small{opacity:0.7;transition:opacity 500ms;}

#friends .friends-table .friends-table-body .friends-row:hover .friends-column-guilds .avatar-small{opacity:1;}

#friends .friends-table .friends-row .friends-column-guilds a:nth-child(4),#friends .friends-table .friends-row .friends-column-guilds a:nth-child(4) .avatar-small,#friends .friends-table .friends-row .friends-column-guilds a:nth-child(5),#friends .friends-table .friends-row .friends-column-guilds a:nth-child(5) .avatar-small,#friends .friends-table .friends-row .friends-column-guilds a:nth-child(n + 6){display:none;}

#friends .friends-table .friends-row .friends-column-guilds .avatar-small{background-color:rgba(0, 0, 0, 0.4);}

#friends .friends-table .friends-row .friends-column-guilds .more-mutual-guilds-btn:before{content:"";background-color:rgba(0, 0, 0, 0.4);background-image:url(data:image/svg+xml;utf8;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pgo8IS0tIEdlbmVyYXRvcjogQWRvYmUgSWxsdXN0cmF0b3IgMTYuMC4wLCBTVkcgRXhwb3J0IFBsdWctSW4gLiBTVkcgVmVyc2lvbjogNi4wMCBCdWlsZCAwKSAgLS0+CjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4PSIwcHgiIHk9IjBweCIgd2lkdGg9IjY0cHgiIGhlaWdodD0iNjRweCIgdmlld0JveD0iMCAwIDYxMiA2MTIiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDYxMiA2MTI7IiB4bWw6c3BhY2U9InByZXNlcnZlIj4KPGc+Cgk8Zz4KCQk8Y2lyY2xlIGN4PSI2OS41NDUiIGN5PSIzMDYiIHI9IjY5LjU0NSIgZmlsbD0iI0ZGRkZGRiIvPgoJCTxjaXJjbGUgY3g9IjMwNiIgY3k9IjMwNiIgcj0iNjkuNTQ1IiBmaWxsPSIjRkZGRkZGIi8+CgkJPGNpcmNsZSBjeD0iNTQyLjQ1NSIgY3k9IjMwNiIgcj0iNjkuNTQ1IiBmaWxsPSIjRkZGRkZGIi8+Cgk8L2c+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPC9zdmc+Cg==);background-size:18px 18px;background-position:center center;background-repeat:no-repeat;border-radius:5px;width:30px;height:30px;box-shadow:1px 1px 2px rgba(0, 0, 0, 0.5);position:absolute;top:0;}

#friends .friends-table .friends-row .friends-column-guilds .more-mutual-guilds-btn,#friends .friends-table .friends-row .friends-column-guilds .more-mutual-guilds-btn:hover{border:0;color:transparent !important;}

#friends .friends-table .friends-row .friends-column-actions{top:25px;right:-5px;opacity:0;transition:opacity 500ms;visibility:visible;}

#friends .friends-table .friends-row:hover .friends-column-actions{opacity:1;}

#friends .friends-table .friends-row .friends-column-actions .friends-action{width:28px;height:28px;transform:translateX(120px);transition:transform 500ms, background 500ms;}

#friends .friends-table .friends-row:hover .friends-column-actions .friends-action{transform:translateX(0px);}

#friends .friends-table .friends-row .friends-column-actions .friends-action:first-child{background-color:rgba(73, 152, 76, 0.7);}

#friends .friends-table .friends-row .friends-column-actions .friends-action:nth-child(2){background-color:rgba(199, 0, 67, 0.7);transition-delay:200ms;}

#friends .friends-table .friends-row .friends-suggestion-inner{padding:20px;}

#friends .friends-table .friends-row .friends-suggestion-inner .avatar-large{border-radius:5px;opacity:0.6;transition:opacity 500ms;}

#friends .friends-table .friends-row:hover .friends-suggestion-inner .avatar-large{opacity:0.8;}

#friends .friends-table .friends-row .friends-suggestion-inner .friends-suggestion-info .discord-tag .username{color:rgba(225, 225, 225, 0.6);width:100px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;transition:color 500ms;}

#friends .friends-table .friends-row:hover .friends-suggestion-inner .friends-suggestion-info .discord-tag .username{color:rgba(225, 225, 225, 0.9);}

#friends .friends-table .friends-row .friends-suggestion-inner .friends-suggestion-info .discord-tag .discriminator{color:rgba(225, 225, 225, 0.7);visibility:visible;}

#friends .friends-table .friends-row .friends-suggestion-inner ~ .friends-column-actions{display:flex;flex-direction:column;padding:5px 25px 0 0;}

#friends .friends-table .friends-row .friends-suggestion-inner ~ .friends-column-actions .friends-action:nth-child(2){margin:5px 0 0 0;}

@media (max-width:1300px){#friends .friends-table .friends-table-header .friends-column-guilds, #friends .friends-table .friends-table-header .friends-column-guilds + .friends-column-separator, #friends .friends-table .friends-row .friends-column-guilds{display:block!important;}

}

#friends .friends-empty p{color:rgba(225, 225, 225, 0.8);}

.theme-dark #friends .friends-table .friends-row .friends-column-actions .friends-action:hover{background-color:rgb(73, 152, 76);}

#friends .friends-table .friends-row .friends-column-status .status.status-unknown{border:none;}

#friends .friends-table .friends-row .friends-column-actions .friends-action.friends-action-remove:hover{background-color:rgb(199, 0, 67) !important;}

.guilds-wrapper .btn-download-apps{display:none;}

#user-profile-modal .guilds .section .section-header{color:var(--hover-color);}

.context-menu{background:#1a1a1d;}

.context-menu .item:hover{background:#18181b;color:#c7c7c7;}

.context-menu .item{color:#adadad;}

.theme-dark.context-menu{background:#18181b;}

.theme-dark.context-menu .item-group{border-color:transparent;}

.theme-dark.context-menu .item-subMenu{background:url(https://discordapp.com/assets/1988164a7c55346d32117b151f4e319d.svg) 155px 50% no-repeat #18181b;}

.theme-dark.context-menu .item:hover{background:#131315;color:#fff;}

.theme-dark.context-menu .item-subMenu:hover{background:url(https://discordapp.com/assets/e4afe52f6863408a35654a6e5fd69ba9.svg) 155px 50% no-repeat #131315;}

.popout.popout-bottom header:before,.popout.popout-bottom-right header:before{border-bottom-color:var(--main-color);}

.popout.popout-invert.popout-top header:before,.popout.popout-invert.popout-top-right header:before{border-top-color:var(--main-color);}

.popout header{background-color:var(--main-color);}

.account .btn:active{background:#151517;}

.settings .settings-inner, .user-settings-modal-streamer-mode{background-color:#19191b;}

.tab-bar.SIDE .tab-bar-item:before{border-left:3px solid var(--main-color);}

.change-log-button-container:before{display:none;}

.change-log-button-container .change-log-button{font-size:14px;}

.settings .settings-actions{background-color:#121213;border-top:1px solid #121213;}

.links,.chat,.typing,.private-channels,.divider-red span,.messages-wrapper,#voice-connection, #rtc-connection{background:transparent !important;}

.guild-channels{background-color:#19191b !important;}

.guild-channels ul .channel-text.unread:not(.selected):not(.channel-muted):before{left:-15px;}

.guild-header header{background-color:#19191b !important;}

/*.links,*/
.help-container{display:none;}

/* Server list area */
.guilds-wrapper{background:#121213;}

/* Channels list area */
.channels-wrap{background:#19191b !important}

/* Chat area */
.content .flex-spacer{background:#19191b}

/* User list area */
.channel-members{background:#19191b !important}

div.message-group{background-color:#19191b;}

textarea{background:transparent !important;}

.scroller-wrap .scroller::-webkit-scrollbar-thumb{border:3px solid transparent !important;background-color:var(--main-color) !important;}

.scroller-wrap .scroller::-webkit-scrollbar-track-piece{border:3px solid rgb(25, 25, 27) !important;background-color:#111113 !important;}

.message-group{padding:11px 0;}

.guild-header header{box-shadow:none !important;color:var(--main-color);}

#bda-qem-favourite-container .scroller-wrap .scroller::-webkit-scrollbar,#bda-qem-twitch-container .scroller-wrap .scroller::-webkit-scrollbar,.emoji-picker .scroller-wrap .scroller::-webkit-scrollbar{background:#212121;width:6px!important;display:none;}

#bda-qem-favourite-container .scroller-wrap .scroller::-webkit-scrollbar-thumb,#bda-qem-twitch-container .scroller-wrap .scroller::-webkit-scrollbar-thumb,.emoji-picker .scroller-wrap .scroller::-webkit-scrollbar-thumb{border:none !important;background-color:rgba(225, 225, 225, 0.2) !important;display:initial;border-radius:0!important}

#bda-qem-favourite-container .scroller-wrap .scroller::-webkit-scrollbar-thumb:active,#bda-qem-twitch-container .scroller-wrap .scroller::-webkit-scrollbar-thumb:active,.emoji-picker .scroller-wrap .scroller::-webkit-scrollbar-thumb:active{border:none !important;background-color:rgba(225, 225, 225, 0.4) !important;display:initial;border-radius:0!important}

.popout.no-shadow{box-shadow:none!important;}

.popout:not(.no-shadow) #bda-qem,.popout:not(.no-shadow) #bda-qem-twitch-container,.popout:not(.no-shadow) #bda-qem-favourite-container{display:block;}

#bda-qem-twitch:after{content:"";width:28px;height:44px;display:block;position:absolute;top:0px;left:78px;background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItMzg3IDI4OSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtMzg3IDI4OSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tMzg3LDI4OWgyNHYyNGgtMjRWMjg5eiIvPg0KPGcgaWQ9IlhNTElEXzc3XyI+DQoJPHJlY3QgaWQ9IlhNTElEXzExMV8iIHg9Ii0zNzcuMyIgeT0iMjk2LjciIGNsYXNzPSJzdDEiIHdpZHRoPSIyIiBoZWlnaHQ9IjQuNyIvPg0KCTxyZWN0IGlkPSJYTUxJRF8xMTVfIiB4PSItMzczIiB5PSIyOTYuNyIgY2xhc3M9InN0MSIgd2lkdGg9IjIiIGhlaWdodD0iNC43Ii8+DQoJPHBhdGggaWQ9IlhNTElEXzEzMF8iIGNsYXNzPSJzdDEiIGQ9Ik0tMzgyLjcsMjkybC0wLjQsMWwtMC40LDFsLTAuNSwxLjJ2MTIuNmg0LjN2Mi4zaDJsMi4zLTIuM2g0LjJsMi42LTIuNmwwLjgtMC43bDItMlYyOTINCgkJSC0zODIuN3ogTS0zNjgsMzAxLjZsLTMuNSwzLjVoLTkuOVYyOTRoMTMuNFYzMDEuNnoiLz4NCjwvZz4NCjwvc3ZnPg0K);background-position:50%;background-repeat:no-repeat;background-size:22px;opacity:.4;visibility:visible;-webkit-transition:all 50ms ease;transition:all 50ms ease;}

#bda-qem-favourite:after{content:"";width:28px;height:43px;display:block;position:absolute;top:0px;left:46px;background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItMzg3IDI4OSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtMzg3IDI4OSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tMzg3LDI4OWgyNHYyNGgtMjRWMjg5eiIvPg0KPGc+DQoJPHBhdGggY2xhc3M9InN0MSIgZD0iTS0zNzUsMjk1LjhsMS44LDIuNmwwLjQsMC41bDAuNiwwLjJsMywwLjlsLTEuOSwyLjVsLTAuNCwwLjVsMCwwLjZsMC4xLDMuMmwtMy0xLjFsLTAuNi0wLjJsLTAuNiwwLjJsLTMsMS4xDQoJCWwwLjEtMy4ybDAtMC42bC0wLjQtMC41bC0xLjktMi41bDMtMC45bDAuNi0wLjJsMC40LTAuNUwtMzc1LDI5NS44IE0tMzc1LDI5Mi42bC0zLjMsNC44bC01LjYsMS42bDMuNSw0LjZsLTAuMiw1LjhsNS41LTEuOQ0KCQlsNS41LDEuOWwtMC4yLTUuOGwzLjUtNC42bC01LjYtMS42TC0zNzUsMjkyLjZ6Ii8+DQo8L2c+DQo8L3N2Zz4NCg==);background-position:50%;background-repeat:no-repeat;background-size:24px;opacity:.4;visibility:visible;-webkit-transition:all 50ms ease;transition:all 50ms ease;}

#bda-qem-emojis:after{content:"";width:28px;height:44px;display:block;position:absolute;top:0px;left:14px;background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItMzg3IDI4OSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtMzg3IDI4OSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tMzg3LDI4OWgyNHYyNGgtMjRWMjg5eiIvPg0KPGc+DQoJPGcgaWQ9IlhNTElEXzM1XyI+DQoJCTxwYXRoIGlkPSJYTUxJRF80OF8iIGNsYXNzPSJzdDEiIGQ9Ik0tMzc1LDI5MmMtNSwwLTksNC05LDlzNCw5LDksOXM5LTQsOS05Uy0zNzAsMjkyLTM3NSwyOTJ6IE0tMzc1LDMwOGMtMy45LDAtNy0zLjEtNy03DQoJCQlzMy4xLTcsNy03czcsMy4xLDcsN1MtMzcxLjEsMzA4LTM3NSwzMDh6Ii8+DQoJPC9nPg0KCTxnIGlkPSJYTUxJRF83M18iPg0KCQk8cGF0aCBjbGFzcz0ic3QxIiBkPSJNLTM3OS45LDMwMS40YzAuMiwyLjUsMi4zLDQuNSw0LjksNC41czQuNy0yLDQuOS00LjVILTM3OS45eiIvPg0KCTwvZz4NCgk8cmVjdCBpZD0iWE1MSURfMzBfIiB4PSItMzc4LjkiIHk9IjI5Ny41IiBjbGFzcz0ic3QxIiB3aWR0aD0iMiIgaGVpZ2h0PSIyIi8+DQoJPHJlY3QgaWQ9IlhNTElEXzY4XyIgeD0iLTM3My4xIiB5PSIyOTcuNSIgY2xhc3M9InN0MSIgd2lkdGg9IjIiIGhlaWdodD0iMiIvPg0KPC9nPg0KPC9zdmc+DQo=);background-position:50%;background-repeat:no-repeat;background-size:24px;opacity:.4;visibility:visible;-webkit-transition:all 50ms ease;transition:all 50ms ease;}

#bda-qem-twitch.active:after,#bda-qem-favourite.active:after,#bda-qem-emojis.active:after,#bda-qem-twitch:hover:after,#bda-qem-favourite:hover:after,#bda-qem-emojis:hover:after{opacity:1!important}

#bda-qem{border:0!important;height:40px;}

#bda-qem-twitch,#bda-qem-favourite,#bda-qem-emojis{visibility:hidden}

.no-shadow .emoji-picker{padding-left:2px;border-radius:3px 3px 0 0!important;}

/*Icons by beard design*/
.emoji-picker .categories .item.recent,.emoji-picker .categories .item.recent.selected,.emoji-picker .categories .item.recent:hover{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzFfIj4NCgk8cGF0aCBpZD0iWE1MSURfMTNfIiBjbGFzcz0ic3QxIiBkPSJNLTkzNSw1MzJjLTUsMC05LDQtOSw5czQsOSw5LDlzOS00LDktOVMtOTMwLDUzMi05MzUsNTMyeiBNLTkzNSw1NDhjLTMuOSwwLTctMy4xLTctNw0KCQlzMy4xLTcsNy03czcsMy4xLDcsN1MtOTMxLjEsNTQ4LTkzNSw1NDh6Ii8+DQoJPHBvbHlnb24gaWQ9IlhNTElEXzEyXyIgY2xhc3M9InN0MSIgcG9pbnRzPSItOTMxLjUsNTQzLjEgLTkzMi45LDU0NC41IC05MzYsNTQxLjQgLTkzNiw1MzUuNyAtOTM0LDUzNS43IC05MzQsNTQwLjYgCSIvPg0KPC9nPg0KPC9zdmc+DQo=)!important}

.emoji-picker .categories .item.custom,.emoji-picker .categories .item.custom.selected,.emoji-picker .categories .item.custom:hover{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItMzg3IDI4OSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtMzg3IDI4OSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tMzg3LDI4OWgyNHYyNGgtMjRWMjg5eiIvPg0KPGcgaWQ9IlhNTElEXzEwMF8iPg0KCTxwYXRoIGlkPSJYTUxJRF8xMDdfIiBjbGFzcz0ic3QxIiBkPSJNLTM3Mi44LDI5NC44bDQsNGwtOS4yLDkuMmgtNHYtNEwtMzcyLjgsMjk0LjggTS0zNzIuOCwyOTJsLTExLjIsMTEuMnY2LjhoNi44bDExLjItMTEuMg0KCQlMLTM3Mi44LDI5MnoiLz4NCjwvZz4NCjwvc3ZnPg0K)!important}

.emoji-picker .categories .item.people,.emoji-picker .categories .item.people.selected,.emoji-picker .categories .item.people:hover{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzNfIj4NCgk8cGF0aCBpZD0iWE1MSURfNTlfIiBjbGFzcz0ic3QxIiBkPSJNLTkzNSw1MzEuNWMtNSwwLTksNC05LDljMCwzLDEuNSw1LjcsMy44LDcuM3YtMi43Yy0xLjEtMS4yLTEuOC0yLjktMS44LTQuN2MwLTMuOSwzLjEtNyw3LTcNCgkJczcsMy4xLDcsN2MwLDEuOC0wLjcsMy40LTEuOCw0Ljd2Mi43YzIuMy0xLjYsMy44LTQuMywzLjgtNy4zQy05MjYsNTM1LjUtOTMwLDUzMS41LTkzNSw1MzEuNXoiLz4NCgk8ZyBpZD0iWE1MSURfNTVfIj4NCgkJPHBhdGggaWQ9IlhNTElEXzU2XyIgY2xhc3M9InN0MSIgZD0iTS05MzIuOCw1NDUuNXYwLjhjMCwxLjItMSwyLjItMi4yLDIuMnMtMi4yLTEtMi4yLTIuMnYtMC44SC05MzIuOCBNLTkzMC44LDU0My41aC04LjR2Mi44DQoJCQljMCwyLjMsMS45LDQuMiw0LjIsNC4yczQuMi0xLjksNC4yLTQuMlY1NDMuNXoiLz4NCgk8L2c+DQoJPHJlY3QgaWQ9IlhNTElEXzU0XyIgeD0iLTk0MC4yIiB5PSI1NDAuMiIgY2xhc3M9InN0MSIgd2lkdGg9IjIiIGhlaWdodD0iMiIvPg0KCTxyZWN0IGlkPSJYTUxJRF81M18iIHg9Ii05MzEuOCIgeT0iNTQwLjIiIGNsYXNzPSJzdDEiIHdpZHRoPSIyIiBoZWlnaHQ9IjIiLz4NCjwvZz4NCjwvc3ZnPg0K)!important}

.emoji-picker .categories .item.nature,.emoji-picker .categories .item.nature.selected,.emoji-picker .categories .item.nature:hover{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItMzg3IDI4OSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtMzg3IDI4OSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tMzg3LDI4OWgyNHYyNGgtMjRWMjg5eiIvPg0KPHBhdGggY2xhc3M9InN0MSIgZD0iTS0zNjcuNywyOTQuOGwxLjQtMS40bC0xLjEtMS4xbC0xLjQsMS40Yy0xLjEtMC45LTIuNS0xLjQtNC0xLjRoMGMtNiwwLTEwLjksNC45LTEwLjksMTAuOXY2LjRoNi40DQoJYzYsMCwxMC45LTQuOSwxMC45LTEwLjloMEMtMzY2LjQsMjk3LjMtMzY2LjksMjk1LjktMzY3LjcsMjk0Ljh6IE0tMzc3LjIsMzA3LjdoLTQuNHYtNC40YzAtNC45LDQtOC45LDguOS04LjloMA0KCWMwLjksMCwxLjgsMC4zLDIuNSwwLjhsLTEuMiwxLjJoLTUuNXYxLjVoNGwtMi4zLDIuM2gtMy42djEuNWgyLjFsLTMuMiwzLjJsMS4xLDEuMWwzLjItMy4ydjIuMWgxLjV2LTMuNmwyLjMtMi4zdjRoMS41di01LjUNCglsMS4yLTEuMmMwLjUsMC43LDAuOCwxLjYsMC44LDIuNUMtMzY4LjQsMzAzLjctMzcyLjMsMzA3LjctMzc3LjIsMzA3Ljd6Ii8+DQo8L3N2Zz4NCg==)!important}

.emoji-picker .categories .item.food,.emoji-picker .categories .item.food.selected,.emoji-picker .categories .item.food:hover{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzVfIj4NCgk8cGF0aCBpZD0iWE1MSURfNDRfIiBjbGFzcz0ic3QxIiBkPSJNLTkyOS40LDUzNy42YzAtMy4xLTIuNS01LjYtNS42LTUuNnMtNS42LDIuNS01LjYsNS42djguNWgyLjd2My44aDUuOHYtMy44aDIuN1Y1MzcuNnoNCgkJIE0tOTM0LjEsNTQ4aC0xLjh2LTEuOGgxLjhWNTQ4eiBNLTkzMS40LDU0NC4yaC0wLjdoLTUuOGgtMC43di02LjVjMC0yLDEuNi0zLjYsMy42LTMuNnMzLjYsMS42LDMuNiwzLjZWNTQ0LjJ6Ii8+DQo8L2c+DQo8L3N2Zz4NCg==)!important}

.emoji-picker .categories .item.activity,.emoji-picker .categories .item.activity.selected,.emoji-picker .categories .item.activity:hover{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzZfIj4NCgk8cGF0aCBpZD0iWE1MSURfNDBfIiBjbGFzcz0ic3QxIiBkPSJNLTkzMCw1MzUuOWgtNHYtM2gtMnYzaC00Yy0yLjIsMC00LDEuOC00LDR2NC4ydjIuMWMwLDEuOCwxLjUsMywzLDNjMC44LDAsMS42LTAuMywyLjItMQ0KCQlsMS42LTEuN2MwLjYtMC42LDEuNC0xLDIuMi0xczEuNiwwLjMsMi4yLDFsMS42LDEuN2MwLjYsMC43LDEuNCwxLDIuMiwxYzEuNSwwLDMtMS4yLDMtM1Y1NDR2LTQuMg0KCQlDLTkyNiw1MzcuNy05MjcuOCw1MzUuOS05MzAsNTM1Ljl6IE0tOTI4LDU0NHYyLjFjMCwwLjctMC42LDEtMSwxYy0wLjMsMC0wLjUtMC4xLTAuNy0wLjNsLTEuNi0xLjdjLTAuOS0xLTIuMy0xLjYtMy43LTEuNg0KCQlzLTIuNywwLjYtMy43LDEuNmwtMS42LDEuN2MtMC4yLDAuMi0wLjQsMC4zLTAuNywwLjNjLTAuNCwwLTEtMC4zLTEtMVY1NDR2LTQuMmMwLTEuMSwwLjktMiwyLTJoMTBjMS4xLDAsMiwwLjksMiwyVjU0NHoiLz4NCjwvZz4NCjwvc3ZnPg0K)!important}

.emoji-picker .categories .item.travel,.emoji-picker .categories .item.travel.selected,.emoji-picker .categories .item.travel:hover{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzdfIj4NCgk8cGF0aCBpZD0iWE1MSURfMzZfIiBjbGFzcz0ic3QxIiBkPSJNLTkyNiw1NDEuMWMwLTEuMS0wLjktMi0yLTJoLTEuOHYtMy4yYzAtMS4xLTAuOS0yLTItMmgtNi41Yy0xLjEsMC0yLDAuOS0yLDJ2My4yaC0xLjgNCgkJYy0xLjEsMC0yLDAuOS0yLDJ2NWgxLjdjMC40LDEuMiwxLjUsMiwyLjgsMmMxLjMsMCwyLjQtMC44LDIuOC0yaDMuMmMwLjQsMS4yLDEuNSwyLDIuOCwyYzEuMywwLDIuNC0wLjgsMi44LTJoMS43VjU0MS4xeg0KCQkgTS05MjgsNTQ0LjFoLTAuN2MwLDAsMCwwLDAsMGgtNS43YzAsMCwwLDAsMCwwaC0xLjJjMCwwLDAsMCwwLDBoLTUuN2MwLDAsMCwwLDAsMGgtMC43di0zaDMuOHYtNS4yaDYuNXY1LjJoMy44VjU0NC4xeiIvPg0KPC9nPg0KPC9zdmc+DQo=)!important}

.emoji-picker .categories .item.objects,.emoji-picker .categories .item.objects.selected,.emoji-picker .categories .item.objects:hover{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzhfIj4NCgk8cGF0aCBpZD0iWE1MSURfMzFfIiBjbGFzcz0ic3QxIiBkPSJNLTkyOC42LDU0NC44di00LjVjMC0zLjEtMi4xLTUuNi01LTYuMmMwLDAsMC0wLjEsMC0wLjFjMC0wLjgtMC42LTEuNC0xLjQtMS40DQoJCXMtMS40LDAuNi0xLjQsMS40YzAsMC4xLDAsMC4xLDAsMC4xYy0yLjksMC42LTUsMy4yLTUsNi4ydjQuNWgtMXYyaDFoMy42YzAsMS41LDEuMiwyLjgsMi44LDIuOHMyLjgtMS4yLDIuOC0yLjhoMy42aDF2LTJILTkyOC42eg0KCQkgTS05MzUsNTQ3LjVjLTAuNCwwLTAuOC0wLjMtMC44LTAuOGgxLjVDLTkzNC4zLDU0Ny4yLTkzNC42LDU0Ny41LTkzNSw1NDcuNXogTS05MzAuNiw1NDQuOGgtOC44di00LjVjMC0yLjQsMi00LjQsNC40LTQuNA0KCQljMi40LDAsNC40LDIsNC40LDQuNFY1NDQuOHoiLz4NCjwvZz4NCjwvc3ZnPg0K)!important}

.emoji-picker .categories .item.symbols,.emoji-picker .categories .item.symbols.selected,.emoji-picker .categories .item.symbols:hover{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzI2XyI+DQoJPHBhdGggaWQ9IlhNTElEXzI3XyIgY2xhc3M9InN0MSIgZD0iTS05MzEuMyw1MzUuNWMxLjQsMCwyLjUsMS4xLDIuNSwyLjVjMCwyLjEtMi40LDQuNC02LjEsNy43Yy0zLjctMy40LTYuMS01LjYtNi4xLTcuNw0KCQljMC0xLjUsMS4yLTIuNiwyLjctMi41YzAuOCwwLjEsMS41LDAuNSwyLDEuMWwwLjcsMC44YzAuNCwwLjUsMS4xLDAuNSwxLjUsMGwwLjgtMC45Qy05MzIuOSw1MzUuOS05MzIuMSw1MzUuNS05MzEuMyw1MzUuNQ0KCQkgTS05MzEuMyw1MzMuNWMtMS40LDAtMi44LDAuNy0zLjcsMS43Yy0wLjktMS0yLjItMS43LTMuNy0xLjdjLTIuNSwwLTQuNSwyLTQuNSw0LjVjMCwzLjEsMi44LDUuNiw3LDkuNGwxLjIsMS4xbDEuMi0xLjENCgkJYzQuMi0zLjgsNy02LjMsNy05LjRDLTkyNi45LDUzNS41LTkyOC44LDUzMy41LTkzMS4zLDUzMy41eiIvPg0KPC9nPg0KPC9zdmc+DQo=)!important}

.emoji-picker .categories .item.flags,.emoji-picker .categories .item.flags.selected,.emoji-picker .categories .item.flags:hover{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzlfIj4NCgk8cGF0aCBpZD0iWE1MSURfMjNfIiBjbGFzcz0ic3QxIiBkPSJNLTkyOSw1MzQuMWgtMTJ2LTEuNmgtMnYxN2gydi01LjFoMTJjMS4xLDAsMi0wLjksMi0ydi02LjNDLTkyNyw1MzUtOTI3LjksNTM0LjEtOTI5LDUzNC4xeg0KCQkgTS05MjksNTQyLjRoLTEydi02LjNoMTJWNTQyLjR6Ii8+DQo8L2c+DQo8L3N2Zz4NCg==)!important}

.guilds-add{font-size:30px !important;color:#fff !important;font-weight:500 !important;background:var(--main-color) !important;transition:.2s all linear !important;transform:scale(1);box-shadow:0 0px 6px 0px var(--hover-color);}

.guilds-add:hover{transform:scale(1.1);box-shadow:0 0px 9px 0px var(--hover-color);}

.guilds .friends-online{margin-left:-5px;}

.guilds li .guild-inner{background:#19191b !important;}

.guilds li.active .guild-inner{background:#25ACE8;}

.guilds li .guild-inner:hover{background:#1D6586;}

.guilds li .guild-inner a,.guilds li,.guilds li .avatar-small{width:40px;height:40px;}

.guilds li .avatar-small{width:40px;height:40px;background-size:40px 40px;}

.guilds li .guild-inner{line-height:40px;}

.guilds .friends-icon{width:40px;height:40px;background-size:25px 19px;}

.guilds li.audio .guild-inner:after{background-size:12px;background-color:rgba(0, 0, 0, 0.8);}

.guilds-separator:after{background:#19191b;}

.guilds li .guild-inner:before{display:none;}

.guilds li.unread .guild-inner:before,.guild-channels ul .channel-text.unread:not(.selected):not(.channel-muted):before{background:#25ACE8;}

.guilds li.active .guild-inner:before{background:#fff !important;}

.guilds .friends-online{color:#717171 !important;font-size:9px;margin-left:-7px;line-height:20px;width:55px;height:20px;border-radius:25px;overflow:hidden;}

.form .control-group input[type=text],.form .control-group input[type=email],.form .control-group input[type=password],.form .control-group input[type=number],.form .control-group textarea{color:#cecece;border-bottom:2px solid #121213;border: 2px solid #121213 !important;background:#121213;padding:0px 0px 0px 7px;border-radius:3px;}

.form .control-group input[type=text]:focus,.form .control-group input[type=email]:focus,.form .control-group input[type=password]:focus,.form .control-group input[type=number]:focus,.form .control-group textarea:focus{animation-duration: 2s;animation-name: focusborder;animation-fill-mode: forwards;transition-property: all;transition-timing-function: ease;}

@keyframes focusborder{0%{border-bottom:2px solid var(--main-color);}

25%{border-right:2px solid var(--main-color);border-bottom:2px solid var(--main-color);}

50%{border-top:2px solid var(--main-color);border-right:2px solid var(--main-color);border-bottom:2px solid var(--main-color);}

100%{border-left:2px solid var(--main-color);border-top:2px solid var(--main-color);border-right:2px solid var(--main-color);border-bottom:2px solid var(--main-color);}

}

.checkbox .checkbox-inner+span,.form .control-group label,.form .radio-group .radio,.user-settings-security button,.user-settings-security p,.tab-bar.TOP .tab-bar-item,.settings-connections-wrapper .user-settings-modal-connections .user-settings-modal-accounts-list h3{color:#b7b7b7;}

.form .btn-default{background-color:transparent;color:#949494;border-bottom:2px solid #39393b;}

.btn.btn-default:hover{background-color:transparent;border-radius:0px;}

.radio .radio-inner{background:#121213;border:1px solid #121213;}

.user-settings-security .btn-ghost{background:#121213;border:2px solid #121213;}

.user-settings-security .btn-ghost:hover{background:#111113;border-color:#111113;}

.tab-bar.SIDE .tab-bar-header{margin-left:24px;}

.user-settings-streamer-mode{background:#19191b;}

.form hr{border-bottom:0px solid #f0f0f0;}

.checkbox .checkbox-inner span{border:2px solid var(--main-color);}

.checkbox .checkbox-inner input[type=checkbox]:checked+span{background-color:var(--main-color);border-color:var(--main-color);}

.form .control-group .help-text{color:#9e9e9e;}

.user-settings-modal a{color:var(--main-color);}

.radio .radio-inner span:after{background:var(--main-color);}

.user-settings-modal button.preview-sound:before{-webkit-filter:grayscale(100%);}

.tab-bar.TOP .tab-bar-item.selected{border-bottom:2px solid var(--main-color);color:var(--main-color);}

.tab-bar.TOP{border-bottom:1px solid var(--hover-color);}

.tab-bar.TOP {border-top: 1px solid var(--hover-color);border-bottom: 1px solid var(--hover-color);}

.settings-connections-wrapper .user-settings-modal-connections .user-settings-modal-accounts-list .user-settings-modal-accounts-list-description .user-settings-modal-accounts-list-description-inner{color:#8a8a8a;}

.settings-connections-wrapper .user-settings-modal-connections .no-connections p{color:#929292;}

.settings-connections-wrapper .user-settings-modal-connections .user-settings-modal-connections-list{box-shadow:0 -1px transparent;}

.slider-bar-fill{background:var(--main-color);}

.slider-bar{background:#121213;}

.slider-handle{border:2px solid var(--main-color);}

.slider-handle,.slider-handle span{background-color:#121213;}

.form .Select-control{border:2px solid var(--main-color);}

.Select-control{background-color:#121213;color:#d8d8d8;}

.has-value>.Select-control>.Select-placeholder{color:#c5c5c5;}

.form .Select-control:hover{border-color:var(--hover-color);}

.form .is-focused:not(.is-open)>.Select-control{border:2px solid var(--main-color);}

.form .Select.is-disabled .Select-control:hover,.form .Select.is-open .Select-control:hover{border-color:var(--main-color);}

.is-open>.Select-control{background:#121213;}

.Select-menu-outer{border-bottom-right-radius:4px;border-bottom-left-radius:4px;background-color:#121213;border:2px solid var(--main-color);border-top-color:var(--main-color);}

.form .Select-option,.form .has-value .Select-placeholder{color:#c5c5c5;}

.Select-menu-outer::-webkit-scrollbar,.Select-menu::-webkit-scrollbar{width:0px;}

.Select-option.is-focused{background-color:#09090a !important;color:#c5c5c5 !important;}

.region-select .region-select-inner{border:2px solid var(--main-color);}

.region-select button{color:#cccccc;border:2px solid var(--main-color);}

.region-select:hover .region-select-inner,.region-select:hover button{border-color:var(--main-color);}

.region-select:hover button{background-color:var(--main-color);}

.region-select-name{color:#b1b1b1;}

.guild-settings-modal-overview a{color:var(--main-color);}

.avatar-uploader .avatar-uploader-inner{border:5px solid var(--hover-color);background-color:var(--hover-color);}

.form .control-groups.control-separator{border-top:1px solid transparent;}

.popout section{background-color:#141417;}

.instant-invite-popout a{color:#a0a0a0;}

.instant-invite-popout a:hover{color:#bdbdbd;}

.instant-invite-popout hr{border:2px solid var(--main-color);}

.clipboard-input-inner button{border-left:2px solid var(--main-color);background-color:#121213;}

.clipboard-input-inner{background:#121213;border:2px solid var(--main-color);}

.clipboard-input-inner input{color:#afafaf;background:#121213;}

.clipboard-input-inner button:first-of-type:before{background:linear-gradient(to right, rgba(255, 255, 255, 0), #040404);}

.create-guild-container .create-or-join .form-inner,.region-select-modal{background-color:#161617;}

.form .form-inner{background-color:#0d0d0e;color: #e0e0e0;}

.create-guild-container{background-color:transparent;}

.create-guild-container .action{background:#121213;}

.form header{color:var(--main-color);}

.form .form-actions{background-color:#0d0d0e;border-top:2px solid #151515;}

.create-guild-container .form-actions .btn-default{color:#b3b3b3;}

.region-select-modal .region-select-modal-header,.create-guild-container h5,.create-guild-container .join-server .sample-link{color:var(--main-color);}

.region-select-modal .region-select-modal-option{border:2px solid #101010;background-color:#101010;}

.region-select-modal .region-select-modal-option:hover{border-color:var(--main-color);}

.region-select-modal .region-select-modal-footer{color:#b1b1b1;background-color: transparent !important;}

.create-guild-container p{color:#bfbfbf;}

.create-guild-container .join-server .link-container input{border:0px solid #99aab5;}

.create-guild-container .join-server .link-container label{color:#a5a5a5;}

.small-popout-box{background:#141417;border:1px solid #141417;}

.option-popout .btn-item{color:#a2a2a2;}

.option-popout .btn-item:hover{color:#c1c1c1;}

.form .form-header{background:#0d0d0e;border-bottom:2px solid var(--main-color);}

.form .control-group label a{color:var(--main-color);}

.form .control-group label a:hover{color:var(--hover-color);}

.markdown-modal .scroller-wrap .scroller{background:#19191b;color:#bdbdbd;}

.markdown-modal{background-color:#141417;}

.markdown-modal .markdown-modal-header{border-bottom:1px solid #141417;color:#efefef;text-transform:capitalize;}

.guild-settings-modal-members{background-color:#19191b !important;}

.guild-settings-modal-members .guild-settings-modal-members-header{border-bottom:2px solid var(--main-color);}

.guild-settings-modal-members .guild-settings-modal-members-footer .help-text{color:#ababab;}

.guild-settings-modal-members .guild-settings-modal-members-footer{border-top:2px solid var(--main-color);}

.guild-settings-modal-members .guild-settings-modal-list .member .member-username{color:#e6e6e6;}

.guild-settings-modal-members .member-buttons .btn.btn-danger{border:1px solid #121213;}

.guild-settings-modal-members .member-buttons .btn{background:#121213;border:1px solid #121213;color:#d6d6d6;}

.guild-settings-modal-members .member-buttons .btn.btn-danger:hover{background:var(--main-color);color:#fff;}

.guild-settings-modal-members .guild-settings-modal-list .member:hover{background:#141417;border-radius:3px;padding:0px 17px 0px 23px;}

.guild-settings-modal-members .guild-settings-modal-list .member{padding:0px 17px 0px 23px;}

.guild-settings-modal-members h6{color:#fff;}

.search-bar.search-bar-light .search-bar-inner{background-color:#121213;border:1px solid #121213;}

.search-bar.search-bar-light{background-color:transparent;}

.search-bar.search-bar-light input{color:#b7b7b7;}

.search-bar.search-bar-light input::-webkit-input-placeholder{color:#a0a0a0;}

.search-bar-light .search-bar-clear:before{background:#121213 !important;}

.search-bar-light .search-bar-clear,.search-bar-clear,.search-bar-light .search-bar-clear:after,.search-bar-clear:after{background:var(--main-color) !important;}

.search-bar-clear:before{background:#19191b;}

#settings-roles .roles{border-right:2px solid #141417;}

#settings-roles .roles header{background-image:linear-gradient(90deg, transparent, transparent), linear-gradient(90deg, transparent, var(--main-color), transparent);background-size:100% 3px;background-position:0 0, 0 100%;background-repeat:no-repeat;border-bottom:0px solid;}

#settings-roles h1{color:#e8e8e8;}

#settings-roles .roles li:hover,#settings-roles .roles li.selected{background:linear-gradient(to right, #141417, #19191b) !important;}

#settings-roles .roles li:hover:before{background-color:var(--main-color);}

#settings-roles .roles li:before{width:4px;}

#settings-roles .roles li.selected:before{color:var(--main-color);background-color:var(--main-color);}

#permissions .permissions-helpdesk{color:var(--main-color);}

#permissions .permissions-helpdesk:hover{color:var(--hover-color);}

.notification-settings-modal .mute-server .checkbox .label{color:#eaeaea;}

.notification-settings-modal .notification-settings-modal-channel-settings-header label{color:#a0a0a0;}

.notification-settings-modal .notification-settings-modal-channel-settings-list{box-shadow:0 -2px var(--main-color) !important;background-color: transparent !important;}

.channel-notification-settings .content label{color:#888888;}

.popout.popout-right header:before{border-right-color:var(--main-color);}

.channel-notification-settings{border-bottom:0px solid #f0f0f0;background-image:linear-gradient(90deg, transparent, transparent), linear-gradient(90deg, transparent, var(--main-color), transparent);background-size:100% 3px;background-position:0 0, 0 100%;background-repeat:no-repeat;}

.tutorial-popout .button-area .skip-tips a{color:var(--main-color);}

.button:hover{background-color:var(--hover-color);}

.button{background-color:var(--main-color);}

.guilds-wrapper .guilds-add{border: 0px solid transparent;position: fixed !important;bottom: 72px;width: 74px !important;border-radius: 0px;left: 0px;height: 3px !important;line-height: 1px;font-size: 0px !important;transition: .1s all linear;}

.user-popout .body .roles .member-roles::-webkit-scrollbar{width:0px;}

.user-popout .body .roles .member-roles{overflow-y:scroll;max-height:179px;padding-bottom:7px;}

.confirm-message-modal .form-inner .message-group{background:#0d0d0e;}

.modal-content .form-inner p{color:#e4e4e4;}

.message-group h2 strong{color:#f3f3f3;}

.message-group h2 .timestamp{color:#b5b5b5;padding-top:6px;}

.radio-theme.light{display:none;}

.radio-theme input[type=radio]:checked~label{width:500px;background-image:none;background:#27ae60;border-color:var(--main-color);}

.radio-theme label{border:4px solid #656565;}

.radio-theme.dark label{width:500px;background-image:none;background:#141417;}

.radio-theme.dark label::after{content:"If Light theme is enabled please click me to enable the Dark theme!";color:#fff;}

.user-settings-locale p{color:#b1b1b1;}

.user-settings-locale .select-item .primary,.user-settings-locale .select-item .localized{color:#c7c7c7!important;}

.create-guild-container .action:hover.create .btn{background-color:var(--main-color);}

.create-guild-container .action.create .action-icon{-webkit-filter:invert() hue-rotate(-270deg);}

.create-guild-container .action.join .action-icon{-webkit-filter:invert() hue-rotate(-175deg);}

.create-guild-container .action.create .action-header{color:#288d5b;}

.create-guild-container .create-or-join .actions .or{display:none;}

.markdown-modal .markdown-modal-footer{border-top:1px solid #141417;color:#a5a5a5;background-color:#141417;}

.markdown-modal ul li{color:#b3b3b3;}

.guilds-wrapper .guilds-add:hover{border-color:transparent;height: 25px !important;line-height: 0px;font-size: 25px !important;}

#friends .btn,.theme-dark #friends .friends-header .tab-bar .tab-bar-item.selected{background-color:var(--main-color);color:#fff;}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item:hover:not(.selected),#friends .friends-empty .btn:hover{background-color:var(--hover-color);}

.add-friend-popout{background:transparent;}

.theme-dark #friends .friends-header{border-bottom:1px #141416 solid !important;}

.message-group .avatar-large{margin-top:0px;}

.spinner-wandering-cubes .spinner-item{background-color:var(--main-color);border-radius:20px;}

.theme-dark .channel-textarea-autocomplete-inner,.channel-textarea-autocomplete-inner{background-color:#19191b;border-color:#131315;}

.theme-dark .channel-textarea-autocomplete-inner ul li.active,.channel-textarea-autocomplete-inner ul li.active{background:#131315;}

.channel-textarea-autocomplete-inner ul li{color:rgba(255, 255, 255, .6);}

.theme-dark .channel-textarea-autocomplete-inner:after,.channel-textarea-autocomplete-inner:after{border-bottom:2px solid #131315;}

.theme-dark .channel-textarea-autocomplete-inner header,.channel-textarea-autocomplete-inner header{border-bottom-color:var(--main-color);background-color:var(--main-color);color:#fff;border-radius:3px 3px 0px 0px;}

.spinner-pulsing-ellipsis .spinner-item{background-color:var(--main-color);}

.message-group .mentioned .message-text{background:#111113 !important;}

.message-group .mentioned .message-text:after{background:var(--main-color);border-left:3px solid var(--main-color);}

.header-toolbar button.active{background-color:transparent;}

.theme-dark .themed-popout{background-color:#19191b !important;border:2px solid #131315 !important;}

.theme-dark .themed-popout .header{background-color:#131315 !important;}

.theme-dark .themed-popout .footer{background-color:#131315 !important;}

.theme-dark .messages-popout-wrap .messages-popout .message-group{border-color:rgb(19, 19, 21) !important;background-color:#131315 !important;}

.theme-dark .messages-popout-wrap .messages-popout .message-group:hover{border-color:var(--main-color) !important;}

.theme-dark .messages-popout-wrap .messages-popout .message-group:hover .action-buttons{-webkit-box-shadow:0 0 6px 4px transparent !important;box-shadow:0 0 6px 4px transparent !important;background-color:transparent !important;}

.theme-dark .messages-popout-wrap .messages-popout .message-group .action-buttons .jump-button{background-color:var(--main-color) !important;}

.theme-dark .themed-popout .header .subtitle,.theme-dark .themed-popout .text{color:#fff !important;}

.theme-dark .messages-popout-wrap .messages-popout .message-group .action-buttons .jump-button:hover{color:#fff;background:var(--hover-color) !important;}

.member-roles .member-role .member-role-remove{background:url(https://i.imgur.com/O2TX2bn.png) 50% no-repeat;width:8px;height:12px;background-size:8px;}

.member-roles .member-role.member-role-add button{background:url(https://i.imgur.com/1MfzLoF.png) 50% no-repeat;width:8px;height:12px;background-size:10px;}

.theme-dark .friends-table .messages .message-group-blocked,.theme-dark .messages-wrapper .messages .message-group-blocked{background:#19191b !important;border-color:#111113;}

.theme-dark .friends-table .messages .divider:not(.red) span,.theme-dark .messages-wrapper .messages .divider:not(.red) span{opacity:1;}

.theme-dark .friends-table .messages .message-group-blocked .message-group-blocked-btn,.theme-dark .messages-wrapper .messages .message-group-blocked .message-group-blocked-btn{background:#111113;color:#a0a0a0 !important;}

#friends .btn:hover{background:var(--hover-color);}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary.selected{background-color:var(--main-color);color:#fff;}

.private-channels .channel .channel-activity{color:#e2e2e2;}

.member-roles .manipulate:hover{border-color:var(--main-color);}

.theme-dark .channel-members-loading .member:nth-child(2n-4),.theme-dark .channel-members-loading .member,.theme-dark .channel-members-loading .heading,.theme-dark .channel-members-loading .member:nth-child(7n-1),.theme-dark .channel-members-loading,.theme-dark .channel-members-loading .member:nth-child(3n+2),.theme-dark .channel-members-loading .member:nth-child(7n+4){background:transparent;}

.theme-dark .channel-members-loading .background{background-image:linear-gradient(90deg, transparent, rgba(0, 0, 0, 0.4), transparent);}

.theme-dark.context-menu .context-menu{background:#18181b;border-color:#18181b;}

.slider-handle span{border:2px solid var(--main-color);}

.slider-handle span:before{border-color:var(--main-color) transparent transparent;}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary:hover:not(.selected){background-color:var(--hover-color);color:#fff;}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary{background-color:var(--main-color);}

.theme-dark .add-friend-input-wrapper{border-color:transparent;background-color:rgba(36, 39, 43, .2);background-image:linear-gradient(90deg, transparent, transparent), linear-gradient(90deg, transparent, var(--main-color), transparent);background-size:100% 3px;background-position:0 0, 0 100%;background-repeat:no-repeat;}

.theme-dark #friends .friends-table .friend-table-add-wrapper .friend-table-add-header{background:transparent;border-bottom:1px solid transparent;}

.theme-dark #friends .friends-table .friend-table-add-wrapper .friend-table-suggestions-header{border-bottom:1px solid transparent;background-color:transparent;background-image:linear-gradient(90deg, transparent, transparent), linear-gradient(90deg, transparent, var(--main-color), transparent);background-size:100% 3px;background-position:0 0, 0 100%;background-repeat:no-repeat;}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary .badge,.theme-dark #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary.selected .badge{background-color:#f04747;color:#fff;}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary:hover:not(.selected) .badge{color:#fff;}

.settings-connections-wrapper .authed-app{background:#141417;border:2px solid #141417;}

.settings-connections-wrapper .authed-app .header .app-name,.settings-connections-wrapper .authed-app .details .header,.settings-connections-wrapper .authed-app .details .body,.settings-connections-wrapper .authed-app .details .permissions .body{color:#a2a2a2;}

.settings-connections-wrapper .authed-app:hover{border-color:var(--main-color);}

#user-profile-modal .guilds .guild:hover{background:linear-gradient(to right, #121213 90%, #141415);color:#dcdcdc;width:300px;}

.channel-members .member .member-activity{color:#d4d4d4;}

.private-channels .search-result.selected,.private-channels .search-result:hover{background:linear-gradient(to right, #121213 85%, #19191b);}

.private-channels .search-result.selected:before,.private-channels .search-result:hover:before{border-left:3px solid var(--main-color);}

.message-group .comment .markup{color:#9c9c9c;}

.popout.popout-top section:after,.popout.popout-top-right section:after{display:none;}

#voice-connection-popout hr, #rtc-connection-popout hr{border:2px solid var(--main-color);}

#voice-connection .btn:active, #rtc-connection .btn:active{background:#151517 !important;}

.theme-dark .friends-table .messages .message-group-blocked .message-group-blocked-btn:hover,.theme-dark .messages-wrapper .messages .message-group-blocked .message-group-blocked-btn:hover{background:#111113 !important;}

.change-log-button-container{padding-top:0px;margin-top:0px;font-weight:600;}

.alert.form .form-inner .btn{border:1px solid transparent;}

.alert.form.has-icon:before{-webkit-filter:invert() grayscale();}

.alert.form .form-inner h4{color:#b4b4b5;}

.alert.form .form-inner p{color:#a9a9a9;}

.channel-members .invite-btn:hover{background-color:var(--hover-color);}

.channel-members .invite-btn{background-color:var(--main-color);}

.chat .welcome-message h1{color:var(--main-color);}

.instant-invites .instant-invites-header{border-bottom:1px solid transparent;color:#c1c1c1;background-image:linear-gradient(90deg, transparent, transparent), linear-gradient(90deg, transparent, var(--main-color), transparent);background-size:100% 3px;background-position:0 0, 0 100%;background-repeat:no-repeat;}

.instant-invites .instant-invites-list .instant-invite .channel{color:#b3b3b3;text-transform:capitalize;}

.instant-invites .instant-invites-list .instant-invite .member,.instant-invites .instant-invites-list .instant-invite{color:#d8d8d8;}

.instant-invites .instant-invite-buttons .btn.btn-danger{border:1px solid var(--main-color);color:#ffffff;background:var(--main-color);}

.instant-invites .instant-invite-buttons .btn.btn-danger:hover{border:1px solid var(--hover-color);background:var(--hover-color);}

.instant-invites .instant-invites-list .instant-invite+.instant-invite{border-top:1px solid #121213;}

.guild-settings-modal-integrations .guild-settings-modal-integrations-header{color:#b9b9b9;border-bottom:1px solid #121213;-webkit-box-shadow:0 2px 0 transparent;box-shadow:0 2px 0 transparent;}

.guild-settings-modal-integrations .guild-settings-modal-integrations-body.no-integrations p{color:#fff;}

.guild-settings-modal-integrations .guild-settings-modal-integrations-body.no-integrations .integration-logos{-webkit-filter:invert();}

#permissions .permission-actions{color:#fff;}

#permissions .permission-actions>div,#permissions .permission-actions.disabled>div{background-color:var(--main-color);border:2px solid var(--hover-color);}

#permissions .permission-actions>div.PASSTHROUGH:hover{border-color:var(--main-color);}

.guild-settings-modal-members .guild-settings-modal-members-header .form .Select .Select-value{color:#bdbdbd;}

.Select-arrow{border-color:var(--main-color) transparent transparent;}

.theme-dark #friends .friends-header .tab-bar .tab-bar-item.selected .badge{background-color:#f04747;color:#fff;}

.form .btn.red{background-color:var(--main-color);}

.theme-dark .message-group.is-local-bot-message{background-image:linear-gradient(90deg, #19191b 80%, #19191b 100%);-webkit-box-shadow:-20px 0 #19191b, 20px 0 #19191b, -20px -1px 0 0 #19191b, -20px 1px 0 #19191b, 20px 1px 0 #19191b, 20px -1px 0 #19191b;box-shadow:-20px 0 #19191b, 20px 0 #19191b, -20px -1px 0 0 #19191b, -20px 1px 0 #19191b, 20px 1px 0 #19191b, 20px -1px 0 #19191b;}

.private-channels .channel .icon-friends{background:url(https://discordapp.com/assets/78edad9e528abdda340ef4341ac52b57.svg) center center no-repeat #121213;}

.private-channels .channel:hover .icon-friends{background-color:var(--main-color);}

.private-channels .channel.selected .icon-friends{background-color:var(--hover-color);border-radius: 3px;}

.guild-settings-modal-members .guild-settings-modal-list .member+.member{border-top:2px solid var(--main-color);}

.guild-settings-modal-members .member-buttons .btn:hover{background:var(--main-color);color:#fff;}

#autocomplete-popout .row.selected,#autocomplete-popout .row:hover{background:linear-gradient(to right, #121213 85%, #141417);}

div.control-group .shortcut-recorder input[type=text]{border:2px solid var(--main-color);color:#fff;}

.now-playing{background:var(--main-color);}

.user-settings-modal-games .games-table .games-row{background:#19191b;}

.user-settings-modal-games{background:#19191b;border-top:2px solid var(--main-color);}

.user-settings-modal-games .games-table .games-row .item-game .game-input{color:#fff;}

.user-settings-modal-games .games-table .games-row .item-game,.user-settings-modal-games .games-table .games-row .item-overlay{border-bottom:2px solid var(--main-color);}

.user-settings-modal-games .games-table .games-row .item-game .last-played{color:#c7c7c7;}

.bda-slist .bda-description{color:#bbbbbb;border-top:2px solid var(--main-color);}

.bda-slist li:nth-child(odd){background:#121213;border-top:1px solid #121213;}

.bda-slist li{background:#121213;border-bottom:1px solid var(--main-color);}

.bda-slist .bda-name{color:#d6d6d6;font-size:14px;}

.bda-slist .checkbox:before{color:#cccccc;}

#bd-customcss-attach-controls{border:1px solid #121213;border-top:1px solid #121213;}

#bd-customcss-attach-controls,#bd-customcss-detach-controls{background:#121213;-webkit-box-shadow:inset 0 1px 0 0 #19191b;}

.chat>.content .messages .message-group.hide-overflow.compact .markup{padding:0px 0px 0px 5rem;}

.gitbutton{font-size:14px;font-weight:600;color:#fff !important;background-color:var(--main-color);padding:8px 8px;border-radius:3px;position:absolute;bottom:0px;right:0px;text-align:center;}

.docsbutton{font-size:14px;font-weight:600;color:#fff !important;background:var(--main-color);padding:8px 8px;border-radius:3px;position:absolute;bottom:0px;right:69px;text-align:center;}

.serverbutton{font-size:14px;font-weight:600;color:#fff !important;background:var(--main-color);padding:8px 11px;border-radius:3px;position:absolute;bottom:0px;right:182px;text-align:center;}

.donatebutton{font-size:14px;font-weight:600;color:#fff !important;background:var(--main-color);padding:8px 8px;border-radius:3px;position:absolute;bottom:0px;right:255px;text-align:center;}

.gitbutton:hover,.docsbutton:hover,.serverbutton:hover,.donatebutton:hover{background-color:var(--hover-color);}

.jump-to-present-bar button:first-of-type{display:none;}

.jump-to-present-bar{width:130px!important;right:10px!important;left:auto!important;}

.chat .divider:before{display:none;}

.guilds-wrapper{width:76px;}

.guilds-wrapper .guilds .guild,.guilds-wrapper .guilds .guild .guild-inner a,.guilds-wrapper .guilds .friends-icon{width:45px;height:45px;}

.guilds-wrapper .guilds .guild .guild-inner a{background-size:cover;}

.guilds-wrapper .guilds{padding: 48px 0px 70px 14px !important;}

.guilds-wrapper .guilds .friends-online{margin:10px -4px;}

.guilds-wrapper .guild-separator:after{margin-left:-5px;margin-right:10px;}

.guilds-wrapper .guilds .guild.selected:before{height:35px;margin-top:-18px;}

code{background:#121213 !important;}

.modal .modal-inner .modal-content .form-inner .message-group code {box-shadow: 0 0 0 0 #fff;}

.message-group .comment .markup pre{border:2px solid #121213;}

.message-group .comment .markup code.inline,.message-group .comment .markup pre{background:#121213 !important;}

.upload-modal{background-color:var(--main-color);}

.upload-modal .footer{background-color:var(--hover-color);}

.upload-modal .inner{border:2px dashed var(--hover-color);}

.upload-modal .inner .file .icon.image{border:2px solid var(--hover-color);}

.upload-modal .inner .comment .channel-textarea{box-shadow:0 0px 0px rgb(23, 23, 23);}

.upload-modal .footer .button{background-color:var(--main-color);}

.upload-modal .footer .button-primary{color:#ffffff;background-color:var(--main-color);}

.channel-notices .channel-notice.invite{background:url(https://discordapp.com/assets/bf625d222187f542b9d7179109422e2c.svg) center 20px no-repeat #19191b;}

#instant-invite-modal .form-actions,#instant-invite-modal-advanced .form-actions{background-color:#0d0d0e;border-top:2px solid #151515;}

.instant-invite-modal{background:transparent;}

#instant-invite-modal .form-header header{color:#d2d2d2;}

#instant-invite-modal .blurb{color:#ffffff;}

#instant-invite-modal .expire-text{color:#c7c7c7;}

#instant-invite-modal .copy{background-color:var(--main-color);}

#instant-invite-modal-advanced .form-actions .btn{padding:9px;top:9px;}

.popout-menu{background:#19191b;}

.popout-menu .popout-menu-icon,.popout-menu .popout-menu-item:hover .popout-menu-icon{-webkit-filter:grayscale(100%);}

.popout-menu .popout-menu-separator{border-bottom:2px solid var(--main-color);}

.popout-menu .popout-menu-item,.popout-menu .popout-menu-item.invite{color:#bdbdbd;}

.popout-menu .popout-menu-item:hover.invite{color:#f7f7f7;}

.popout{box-shadow:0 3px 6px rgba(0, 0, 0, .2);}

.sensitivity .slider .slider-bar-auto{background-color:#121213;}

.user-settings-modal-keybinds .user-settings-modal-keybinds-header{border-bottom:1px solid #151515;}

#user-profile-modal .guilds .avatar-large{background-color:var(--main-color);}

.guilds-wrapper .guilds .guild.selected .guild-inner{background:var(--main-color) !important;}

.guilds-wrapper .guilds .guild:hover .guild-inner{background:var(--main-color) !important;}

.guild-settings-modal-emoji .guild-settings-modal-emoji-header h6{color:#fff;}

.guild-settings-modal-emoji .guild-settings-modal-emoji-header p{color:#c5c5c5;}

.guild-settings-modal-emoji .guild-settings-modal-emoji-header{border-bottom:1px solid transparent;background-image:linear-gradient(90deg, transparent, transparent), linear-gradient(90deg, transparent, var(--main-color), transparent);background-size:100% 3px;background-position:0 0, 0 100%;background-repeat:no-repeat;}

.guild-settings-modal-emoji .no-emoji p{color:#dadada;}

.guild-settings-modal-emoji .table-header{color:#ececec;}

.guild-settings-modal-emoji .emoji-uploader .emoji-uploader-username{color:#fff;}

.guild-settings-modal-emoji .emoji-row .emoji-name{background:#121213;color:#fff;border: 2px solid transparent;}

.guild-settings-modal-emoji .emoji-row:hover .emoji-name{background-color:rgba(43, 43, 43, 0.6);border-color: var(--main-color);border: 2px solid var(--main-color);}

.guild-settings-modal .emoji-row .btn.btn-danger,.guild-settings-modal .member-buttons .btn.btn-danger{border:1px solid #9c2121;color:#ffffff;}

.guild-settings-modal .emoji-row .btn,.guild-settings-modal .member-buttons .btn{background:#9c2121;}

.guild-settings-modal-emoji .emoji-row{border-bottom:2px solid #151515;}

.status-picker .popout-menu-item .helper{margin:-21px 0px 0 -4px;color:#fff;text-align:center;padding-top:6px;opacity:0;}

.chat .welcome-message .item-container .icon.exclamation,.chat .welcome-message .item-container .icon.share,.chat .welcome-message .item-container .icon.apps,.chat .welcome-message .item-container .icon.mobile,.chat .welcome-message .item-container .icon.twitter{background-image:url("https://i.imgur.com/DYPXksE.png");background-repeat:no-repeat;background-size:20px 20px;background-position:29px 13px;}

.bda-dark #bda-qem-favourite-container,.bda-dark #bda-qem-twitch-container,.bda-dark .emoji-picker,.bda-dark .emoji-picker .category,.bda-dark .emoji-picker .header .search-bar{background-color:#121213;}

.bda-dark #bda-qem button{background:#121213;border-left:1px solid #121213;box-shadow:#121213 1px 0 0 0;}

.bda-dark #bda-qem{border-bottom:0px solid transparent!important;background:#121213;}

.emoji-picker{border:1px solid #19191b !important;border-top:0px solid transparent !important;}

.emoji-picker .search-bar .search-bar-inner{background-color:#19191b;}

.emoji-picker .search-bar-clear:before{background:#19191b;}

.emoji-picker .category{color:#cacaca;}

.emoji-picker .scroller::-webkit-scrollbar{width:0px;}

#bda-qem-twitch-container::-webkit-scrollbar,#bda-qem-favourite-container::-webkit-scrollbar,#bda-qem-favourite-container .scroller-wrap::-webkit-scrollbar,#bda-qem-twitch-container .scroller-wrap::-webkit-scrollbar{width:0px;}

.emoji-picker .scroller .emoji-item.selected{background-position:center center !important;background-repeat:no-repeat !important;-webkit-background-size:contain !important;-moz-background-size:contain !important;background-size:contain !important;}

.bda-dark .emoji-picker .dimmer.visible{background-color:rgba(0, 0, 0, 0.65);z-index:2;}

.bda-dark .emoji-picker .diversity-selector .popout{background:#121213;border-color:#121213;}

.theme-dark .channel-textarea-inner{border-color:#1D1C1B;}

.chat .jump-to-present-bar button:last-child{color:#fff;}

.theme-dark .chat .jump-to-present-bar{background-color:var(--main-color);}

.theme-dark .chat .jump-to-present-bar:hover{background-color:var(--hover-color);}

.context-menu,.small-popout-box{-webkit-animation:animation-folding .3s cubic-bezier(.2, .6, .5, 1.1);animation:animation-folding .3s cubic-bezier(.2, .6, .5, 1.1);-webkit-transform-origin:50% 0;transform-origin:50% 0;}

.context-menu.invertY{-webkit-transform-origin:50% 100%;transform-origin:50% 100%;}

.user-popout{-webkit-animation:animation-popping .15s cubic-bezier(.2, .6, .5, 1.1);animation:animation-popping .15s cubic-bezier(.2, .6, .5, 1.1);}

.item-subMenu .context-menu{-webkit-animation:animation-sliding .15s cubic-bezier(.2, .6, .5, 1.1);animation:animation-sliding .15s cubic-bezier(.2, .6, .5, 1.1);-webkit-transform-origin:0% 50%;transform-origin:0% 50%;}

@-webkit-keyframes animation-folding{0%{-webkit-transform:rotateX(-90deg);transform:rotateX(-90deg);}

100%{-webkit-transform:none;transform:none;}

}

@keyframes animation-folding{0%{-webkit-transform:rotateX(-90deg);transform:rotateX(-90deg);}

100%{-webkit-transform:none;transform:none;}

}

@-webkit-keyframes animation-sliding{0%{-webkit-transform:rotateY(-90deg);transform:rotateY(-90deg);}

100%{-webkit-transform:none;transform:none;}

}

@keyframes animation-sliding{0%{-webkit-transform:rotateY(-90deg);transform:rotateY(-90deg);}

100%{-webkit-transform:none;transform:none;}

}

@-webkit-keyframes animation-popping{0%{-webkit-transform:scale(0);transform:scale(0);}

100%{-webkit-transform:none;transform:none;}

}

@keyframes animation-popping{0%{-webkit-transform:scale(0);transform:scale(0);}

100%{-webkit-transform:none;transform:none;}

}

/* Alert made by BeardDesign and heavily modified by me */
.tutorial-indicators+.theme-light:before{content:"You need to have the dark mode enabled for this theme to work properly. To enable it, go into settings > appearance.";position:fixed;display:block;width:400px;height:30px;top:50%;left:50%;background:#121213;-webkit-transform:translate(-50%, -50%);transform:translate(-50%, -50%);color:#fff;padding:20px 20px;border-radius:5px;box-shadow:0px 2px 10px var(--main-color);border:3px solid var(--main-color);z-index:10;}

.tutorial-indicators+.theme-light:after{content:"";position:fixed;display:block;width:100%;height:200%;left:50%;top:45%;background:rgba(0, 0, 0, 0.7);-webkit-transform:translate(-50%, -50%);transform:translate(-50%, -50%);padding:20px 20px;border-radius:5px;z-index:8;}

.radio-theme input[type=radio]:checked~label{border-color:transparent}

.radio-theme.dark label{width:506px;height:50px;background:#7289DA;border:0px!important}

.theme-light+span .radio-theme.dark label{background:#F04747;box-shadow:0 2px 10px rgba(240, 71, 71, .3);}

.radio-theme.dark:after{content:"ENABLE DARK MODE";display:block;color:#fff;-webkit-transform:translate(-50%, -32px);transform:translate(-50%, -32px);position:absolute;left:50%;font-weight:800;pointer-events:none}

.theme-dark+span .radio-theme.dark:after{content:"DARK MODE ENABLED"}

.radio-theme.light{display:none;}

div[data-reactroot]:not(.platform-osx):not(.platform-win) .theme-light + div .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(9),div.platform-win .theme-light + div .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(10),div.platform-osx .theme-light + div .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(10){box-shadow:0 2px 10px var(--main-color);border:3px solid var(--main-color);width:110px;border-radius:3px;margin-left:29px;}

.theme-light .account .btn-settings{position:fixed;width:256px;height:31px;border-radius:3px;font-size:20px;box-shadow:0 2px 10px var(--main-color) !important;border:3px solid var(--main-color);top:60%;left:50%;margin-left:-124px;}

.theme-light .account .btn-deafen,.theme-light .account .btn-mute{border-right:1px solid transparent;display:none;}

.theme-light .account .btn-settings:after{opacity:1;}

.theme-light .account .btn-settings:after{z-index:1000;position:absolute;}

.theme-light .account .btn:after{content:"CLICK ME FOR SETTINGS";display:block;color:#fff;background:#121213;opacity:1;z-index:1003;}

.theme-light .account{height:0px;margin-bottom:-30px;}

.ebr-theme-item-info,.ebr-plugin-item-info{color:#fff;}

.ebr-plugin-item,.ebr-theme-item{background-color:#121213 !important;border:1px solid #121213 !important;}

#ebr-themes-pane .ebr-top .themes-header,#ebr-plugins-pane .ebr-top .plugins-header{color:#fff;}

#theme-search,#plugin-search{border:1px solid #121213 !important;background:#121213;border-radius:3px;color:#fff;}

.message-group .edit-message .channel-textarea-inner{border-color:#1D1C1B;}

.keyboard-shortcuts-modal{background-color:#19191b;}

.keybind-shortcut span{border:1px solid var(--main-color) !important;box-shadow:inset 0 -4px 0 var(--main-color) !important;color:#cbcbcb !important;}

.keyboard-shortcuts-modal .modal-title{color:#dedede;}

.keyboard-shortcuts-modal .modal-subtitle,.keyboard-shortcuts-modal .keyboard-shortcut-list .keybind-group .keybind-description{color:#c1c1c1;}

.keybind-shortcut{color:var(--main-color);}

.keyboard-shortcuts-modal .keyboard-shortcut-list .keybind-group .bind-arrow.up,.keyboard-shortcuts-modal .keyboard-shortcut-list .keybind-group .bind-arrow{-webkit-filter:invert() grayscale(100%);}

.keyboard-shortcuts-modal .ddr-arrows .arrow{-webkit-filter:invert() hue-rotate(208deg);}

.webhooks .webhooks-header{border-bottom:2px solid var(--main-color);}

.webhooks .webhook{background:#141417;}

.webhooks .webhook .webhook-header .webhook-details .webhook-name{color:#e8e8e8;}

.webhooks .webhook .webhook-header .webhook-details .webhook-created-on{color:#d0d0d0;}

.form .btn-clear{background:var(--main-color);color:#fff;}

.form .btn-clear:hover{background:var(--hover-color);}

#instant-invite-modal .clipboard-input-inner input{color:#adadad;}

.channel-notices .channel-notice.guild-mfa-warning{background:url(/assets/916a384814e3bbd2a84e2a1b352a17c3.svg) center 20px no-repeat #19191b;}

.messages .renamer-tag{margin-left:6px;}

.bot-tag.kawaii-tag{padding: 1px 5px 1px 3px;text-shadow: 0px 1px 3px #000;}

.message-group .renamer-tag, .channel-members .renamer-tag{padding: 1px 5px 1px 4px;text-shadow: 0px 1px 3px #000;}

.channel-members .avatar-small .status,.private-channels .avatar-small .status,.account .avatar-small .status{width:100%;height:100%;background:transparent;top:-2px;left:-2px;box-shadow:0 0 1px #000 inset;transition:.3s all linear;}

.channel-members .avatar-small .status-online,.private-channels .avatar-small .status-online,.account .avatar-small .status-online{border:2px solid #43b581 !important;}

.channel-members .avatar-small .status-idle,.private-channels .avatar-small .status-idle,.account .avatar-small .status-idle{border:2px solid #faa61a !important;}

.channel-members .avatar-small .status-dnd,.private-channels .avatar-small .status-dnd,.account .avatar-small .status-dnd{border:2px solid #f04747 !important;}

.channel-members .avatar-small .status-offline,.private-channels .avatar-small .status-offline,.account .avatar-small .status-offline{border:2px solid #282829 !important;}

.channel-members .avatar-small .status-invisible,.private-channels .avatar-small .status-invisible,.account .avatar-small .status-invisible{border:2px solid #747f8d !important;}

.channel-members .avatar-small .status-streaming,.private-channels .avatar-small .status-streaming,.account .avatar-small .status-streaming{border:2px solid #643da7 !important;}

.status.status-typing.status-online{width:26px!important;right:-11px!important;height:8px !important;background:#43b581 !important;border:2px solid #19191b !important;margin:22px 0px 0px 14px;transition:.3s all ease-in-out;}

.status.status-typing.status-idle{width:26px!important;right:-11px!important;height:8px !important;background:#faa61a !important;border:2px solid #19191b !important;margin:22px 0px 0px 14px;transition:.3s all ease-in-out;}

.status.status-typing.status-dnd{width:26px!important;right:-11px!important;height:8px !important;background:#f04747 !important;border:2px solid #19191b !important;margin:22px 0px 0px 14px;transition:.3s all linear;}

.status.status-typing.status-invisible{width:26px!important;right:-11px!important;height:8px !important;background:#747f8d !important;border:2px solid #19191b !important;margin:22px 0px 0px 14px;transition:.3s all linear;}

.status.status-typing.status-offline{width:26px!important;right:-11px!important;height:8px !important;background:#282829 !important;border:2px solid #19191b !important;margin:22px 0px 0px 14px;transition:.3s all linear;}

.user-popout .avatar-wrapper .avatar-popout .status.status-online{width:100%;height:100%;-webkit-border-radius:20px;border-radius:75px;position:absolute;border:4px solid #43b581;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;bottom:0px;right:0px;z-index:2;-webkit-box-shadow:inset 0 0 0 0 rgba(255, 255, 255, .3);box-shadow:inset 0 0 0 0 rgba(255, 255, 255, .3);background:transparent;}

.user-popout .avatar-wrapper .avatar-popout .status.status-dnd{width:100%;height:100%;-webkit-border-radius:20px;border-radius:75px;position:absolute;border:4px solid #f04747;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;bottom:0px;right:0px;z-index:2;-webkit-box-shadow:inset 0 0 0 0 rgba(255, 255, 255, .3);box-shadow:inset 0 0 0 0 rgba(255, 255, 255, .3);background:transparent;}

.user-popout .avatar-wrapper .avatar-popout .status.status-idle{width:100%;height:100%;-webkit-border-radius:20px;border-radius:75px;position:absolute;border:4px solid #faa61a;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;bottom:0px;right:0px;z-index:2;-webkit-box-shadow:inset 0 0 0 0 rgba(255, 255, 255, .3);box-shadow:inset 0 0 0 0 rgba(255, 255, 255, .3);background:transparent;}

.user-popout .avatar-wrapper .avatar-popout .status.status-invisible{width:100%;height:100%;-webkit-border-radius:20px;border-radius:75px;position:absolute;border:4px solid #747f8d;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;bottom:0px;right:0px;z-index:2;-webkit-box-shadow:inset 0 0 0 0 rgba(255, 255, 255, .3);box-shadow:inset 0 0 0 0 rgba(255, 255, 255, .3);background:transparent;}

.user-popout .avatar-wrapper .avatar-popout .status.status-offline{width:100%;height:100%;-webkit-border-radius:20px;border-radius:75px;position:absolute;border:4px solid #282829;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;bottom:0px;right:0px;z-index:2;-webkit-box-shadow:inset 0 0 0 0 rgba(255, 255, 255, .3);box-shadow:inset 0 0 0 0 rgba(255, 255, 255, .3);background:transparent;}

.status-picker .popout-menu-item:nth-child(1){background:#43b581 !important;}

.status-picker>.popout-menu-separator{border-bottom:0px solid #000 !important;}

.status-picker .popout-menu-item:nth-child(3){background:#faa61a !important;color:#fff;}

.status-picker .popout-menu-item:nth-child(4){background:#f04747 !important;color:#fff;transition:.2s all linear;height:38px;}

.status-picker .popout-menu-item:nth-child(4) > .status-icon-text > .status-text{margin-top:19px;transition:.2s all linear;}

.status-picker .popout-menu-item:nth-child(4) > .helper{margin-top:-9px;}

.status-picker .popout-menu-item:nth-child(4):hover > .helper{opacity:1;transition:.2s all linear;}

.status-picker .popout-menu-item:nth-child(4):hover > .status-icon-text > .status-text{opacity:0;transition:.2s all linear;}

.status-picker .popout-menu-item:nth-child(5){background:#747f8d !important;color:#fff;transition:.2s all linear;height:38px;}

.status-picker .popout-menu-item:nth-child(5) > .status-icon-text > .status-text{margin-top:16px;transition:.2s all linear;}

.status-picker .popout-menu-item:nth-child(5) > .helper{margin-top:-9px;}

.status-picker .popout-menu-item:nth-child(5):hover > .helper{opacity:1;transition:.2s all linear;margin-top:-9px;}

.status-picker .popout-menu-item:nth-child(5):hover > .status-icon-text > .status-text{opacity:0;transition:.2s all linear;}

.status-icon-text > .status{margin-right:0px !important;}

.status-picker .popout-menu-item{-webkit-align-items:center;align-items:center;}

/*by maple*/
#app-mount > div > div.context-menu{margin-left:-10px;margin-top:-15px;}

#app-mount > div > div.context-menu .item-group{display:flex;flex-direction:column;}

#app-mount > div > div.context-menu .item-group .item.danger{order:1 !important;}

#app-mount > div > div.context-menu .item-group .item{order:2;}

#app-mount > div > div.context-menu.invertX.invertY.invertChildX{margin-left:100px;margin-top:135px;}

#app-mount > div > div.context-menu.invertX.invertChildX{margin-left:100px;margin-top:-10px;}

/* */
.CodeMirror{color:#efefef;background-color:#121213!important;}

.CodeMirror-gutters{border-right:1px solid #19191b;background-color:#141417;}

.channel-members .member.popout-open .avatar-small{margin-left:-14px;}

.theme-dark .channel-members .member.popout-open{margin-left:14px;border-top-left-radius:3px;border-bottom-left-radius:3px;}

.user-popout{width:450px;}

.user-popout .body{display:flex;background:#111113;padding-top:14px;}

.user-popout .avatar-wrapper{position:fixed;margin:4px 0px 14px -169px;}

.section.roles{max-width:250px;width:250px;}

.section.notes,.section.roles{background:#0f0f10;margin-left:15px;border-radius:3px;}

.user-popout .username-wrapper .activity,.user-popout .username-wrapper .discord-tag,.user-popout .username-wrapper .nickname{text-align:left;margin-left:127px;white-space:nowrap;text-overflow:ellipsis;overflow:hidden;}

.user-popout .username-wrapper .nickname::before{content:"Nickname:";color:#cecece;padding-right:3px;}

.user-popout .username-wrapper .nickname{margin-bottom:2px;}

.creation-date-wrapper{margin-left:-33px;}

.quick-message.isBlocked{background:#0b0b0c;}

.theme-dark .friends-table .messages .message-group-blocked.revealed,.theme-dark .messages-wrapper .messages .message-group-blocked.revealed{border:2px solid #111113;-webkit-box-shadow:0 1px 3px rgba(0, 0, 0, .16);box-shadow:0 1px 3px rgba(0, 0, 0, .16);}

.user-popout .header.streaming .live-on-twitch{border-top:0px solid transparent;text-decoration:none;width:150px;margin-left:129px;border-radius:3px;padding:4px 0;}

.user-popout .header.streaming{padding-bottom:8px;}

.user-popout .header.streaming .activity{padding:0;}

.streaming>.creation-date-wrapper{display:none;}

.chat .jump-to-present-bar .spinner{padding-right:7px;padding:8px;padding-left:50px;}

.account .btn-settings:after{background-image:url(https://storage.googleapis.com/material-icons/external-assets/v4/icons/svg/ic_settings_white_24px.svg) !important;zoom:1.2;}

.account .btn-settings:hover:after{opacity:0.6;}

.account .btn-deafen:after{background-image:url(https://storage.googleapis.com/material-icons/external-assets/v4/icons/svg/ic_volume_up_white_24px.svg) !important;opacity:0.2;zoom:1.2;}

.account .btn-deafen:hover:after{opacity:0.6;}

.icon-deafened,.account .btn-deafen.disabled:after{background-image:url(https://storage.googleapis.com/material-icons/external-assets/v4/icons/svg/ic_volume_off_white_24px.svg) !important;}

.account .btn-mute:after{background-image:url(https://storage.googleapis.com/material-icons/external-assets/v4/icons/svg/ic_mic_white_24px.svg) !important;opacity:0.2!important;zoom:1.2;}

.account .btn-mute:hover:after{opacity:0.6!important;}

.icon-muted,.account .btn-mute.disabled:after{background-image:url(https://storage.googleapis.com/material-icons/external-assets/v4/icons/svg/ic_mic_off_white_24px.svg) !important;}

#voice-connection .btn-info:after, #rtc-connection .btn-info:after{background-image:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAMAAABEpIrGAAAAJFBMVEUAAAD///////////////////////////////////////////+0CY3pAAAAC3RSTlMAECCvsL/A3+Dv8NZYMh8AAABeSURBVHjazZE7DkAhCARZxO/e/77PwsRKCiyeU0DBBLJBnkNTrUmdeeeknw1jAQrtKAxCBKy+oGzOiQxk54QOTgacGNaaQcJwcSOs6m2ICZvnhZ2CjAu7u78ICD/zAe+MBVc6o3cPAAAAAElFTkSuQmCC) !important;background-size:22px;}

#voice-connection .btn-disconnect:after, #rtc-connection .btn-disconnect:after{background-image:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAMAAABEpIrGAAAAP1BMVEUAAAD///////////////////////////////////////////////////////////////////////////////9Du/pqAAAAFHRSTlMAECAwQFBwf4CfoK+wwM/Q3+Dv8JnWEvoAAAC9SURBVHjaxZLNDoQgDIRpERdRW3/m/Z91o3EbyFavzoFDZwIfA+FV0eduvmAbOJAgu77g0NYJlP7txII1hTgBvm/zAnTe/gpwOFWwkZ+Qaz6heIyMXyJC/DtYAnB95euUhLnhp3OF0sVBC/rah5DlDg4WzD6bdankshkHOFSajc04mpfqsZ6zioNyu0GyFh1ZJfcJRXxOFIzhMUE7hroP96MM1ke+ecMxhrRA2fe1263fVtYdlx2aHd+6e09fDtYMiY3H4msAAAAASUVORK5CYII=);zoom:1.3;-webkit-transition:-webkit-transform 300ms ease;transition:-webkit-transform 300ms ease;transition:transform 300ms ease;transition:transform 300ms ease, -webkit-transform 300ms ease;}

::selection{color:#fff !important;background:var(--main-color);}

.scroller-wrap .scroller::-webkit-scrollbar{width:12px;}

.messages-popout .channel-separator{margin-top:26px;margin-bottom:10px;background:#131315;padding:8px;border-radius:3px;top:5px;border:2px solid #131315;}

.messages-popout .channel-separator:hover{border:2px solid var(--main-color);}

.upload-drop-modal .bgScale{background:var(--main-color) !important;}

.upload-drop-modal .inner .icon{filter:grayscale(100%) !important;}

.theme-light .account .btn-settings:after{background-image:none !important;zoom:1.2;}

.emoji-picker .categories .item.selected{border-bottom-color:var(--main-color);}

#user-profile-modal .header:after{content:' ';background-color:transparent;background-image:linear-gradient(-180deg, transparent, transparent);}

#user-profile-modal .avatar-wrapper{background-color:transparent;top:8px;left:0px;}

#user-profile-modal .header .header-info .header-info-inner .discord-tag{color:#e4e4e4;}

#user-profile-modal .header .header-info .header-info-inner .discord-tag .discriminator{color:#969696;}

.avatar-profile{width:100px;height:100px;background-size:cover;}

#user-profile-modal .header{height:120px;}

#user-profile-modal .header .discord-tag{margin-left:-50px;margin-top:-20px;}

#user-profile-modal .actions{padding-top:14px;margin-left:-50px;}

.connected-account{max-width:170px !important;}

.connected-accounts{max-width:85%;min-width:85%;}

#user-profile-modal .guilds .section .connected-accounts .connected-account .connected-account-name-inner .connected-account-name{color:#bbbbbb;}

#user-profile-modal .guilds .section .connected-accounts .connected-account{border:2px solid #101010;background:#121213;}

.alert.form .form-inner .cancel{background-color:#a23636;}

.alert.form .form-inner .cancel:hover{background-color:#8a2c2c;}

.upload-drop-modal .bgScale{background:var(--main-color);}

.upload-drop-modal .inner .icon{filter:grayscale(100%) !important;}

.message-reactions-modal{background:#19191b;}

.message-reactions-modal .message-reactions-reactors .reactor .name{color:#e4e4e4;}

.message-reactions-modal .message-reactions-reactors .reactor{-webkit-box-shadow:inset 0 -1px 0 0 #1f1f1f;box-shadow:inset 0 -1px 0 0 #1f1f1f;}

.message-reactions-modal .message-reactions-list .scroller-wrap{background:#19191b;}

.tooltip.tooltip-left:after{border-left-color:var(--main-color);}

.message-reactions-modal .message-reactions-list-inner .reaction .count{color:#d0d0d0;}

.message-reactions-modal .message-reactions-list-inner .reaction.selected,.message-reactions-modal .message-reactions-list-inner .reaction:hover:not(.selected){background:#131313;}

#bda-qem-line{margin-left:104px;opacity:0.55;}

#bda-qem-line:hover,#bda-qem-line.active{opacity:1;}

.bda-dark #bda-qem button:hover{background-color:#121213;}

.bda-dark #bda-qem button.active{background-color:#121213;}

button.bd-customicon-settings{display:none;}

#bda-qem-line{margin-left:100px;opacity:0.55;color:transparent !important;margin-top:3px;background-image:url(https://i.imgur.com/v1dAJSb.png) !important;background-repeat:no-repeat !important;background-position:50% !important;background-size:22px !important;}

#bda-qem-line-container .emote-menu-inner,#bda-qem-line-container .categories{background:#121213 !important;}

#bda-qem-line-container .category-header{color:#c3c3c3 !important;}

.emote-container:hover{background:#19191b;}

#preview-sticker-wrapper{background-color:#121213 !important;}

.bda-dark .emoji-picker .scroller .emoji-item.selected{background:var(--hover-color);}

.theme-dark .message-group .embed{background-color:#111113;border-color:#111113;border-radius: 3px !important;}

.embed-color-pill[style*='background-color: rgb(114, 137, 218);']{background-color:var(--main-color) !important;}

.theme-dark .reaction.reaction-me{background:var(--main-color);}

.theme-dark .reaction.reaction-me .reaction-count{color:#fff !important;}

.attachment-image .image,.message-group .comment .attachment-image img,.embed .image,.embed .embed-thumbnail img{border-radius:3px;box-shadow:0 3px 7px rgba(0, 0, 0, 0.4);}

.embed-wrapper{-webkit-transition:200ms cubic-bezier(.2, .11, 0, 1);transition:200ms cubic-bezier(.2, .11, 0, 1);box-shadow:2px 2px 10px #0c0c0c;}

.embed-wrapper:hover{-webkit-transform:scale(1.03);transform:scale(1.03)}

.theme-dark .chat .title-wrap{border-bottom:2px solid var(--main-color) !important;height:58px;}

.message-reactions-modal .message-reactions-list-inner{background:#19191b;}

.header-toolbar button{-webkit-transition:all 300ms cubic-bezier(.23, .23, 0, 1);transition:all 300ms cubic-bezier(.23, .23, 0, 1);display:block;z-index:500;}

.header-toolbar button.popout-open{-webkit-transition:all 400ms cubic-bezier(.3, .3, 0, 1);transition:all 400ms cubic-bezier(.3, .3, 0, 1);}

.messages-popout-wrap{-webkit-animation:toppopout 400ms cubic-bezier(.3, .3, 0, 1);animation:toppopout 400ms cubic-bezier(.3, .3, 0, 1)}

@-webkit-keyframes toppopout{from{-webkit-transform:translate(0, -55px);transform:translate(0, -55px);opacity:0}

}

@keyframes toppopout{from{-webkit-transform:translate(0, -55px);transform:translate(0, -55px);opacity:0}

}

.search-bar{border-bottom:0px var(--main-color) solid !important;box-shadow:0 0px 0 0 rgba(0, 0, 0, .06), inset 0 0px 0 0 rgba(0, 0, 0, .2);-webkit-border-radius:0px;border-radius:0px;margin-top:-1px;}

.theme-dark #friends .friends-header{border-bottom:2px var(--main-color) solid !important;}

#friends .friends-table .friends-row .friends-suggestion-inner .avatar-large{margin-right:20px;height:60px;width:60px;background-repeat:no-repeat;border-radius:3px;background-size:60px;}

#friends .friends-table .friends-row .friends-suggestion-inner{padding:15px;}

.tipsy{opacity:1 !important;}

.tipsy-inner{background-color:var(--main-color);color:#fff !important;padding:5px 10px !important;border-radius:3px !important;font-size:12px !important;}

.fav{background:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItMzg3IDI4OSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtMzg3IDI4OSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tMzg3LDI4OWgyNHYyNGgtMjRWMjg5eiIvPg0KPGc+DQoJPHBhdGggY2xhc3M9InN0MSIgZD0iTS0zNzUsMjk1LjhsMS44LDIuNmwwLjQsMC41bDAuNiwwLjJsMywwLjlsLTEuOSwyLjVsLTAuNCwwLjVsMCwwLjZsMC4xLDMuMmwtMy0xLjFsLTAuNi0wLjJsLTAuNiwwLjJsLTMsMS4xDQoJCWwwLjEtMy4ybDAtMC42bC0wLjQtMC41bC0xLjktMi41bDMtMC45bDAuNi0wLjJsMC40LTAuNUwtMzc1LDI5NS44IE0tMzc1LDI5Mi42bC0zLjMsNC44bC01LjYsMS42bDMuNSw0LjZsLTAuMiw1LjhsNS41LTEuOQ0KCQlsNS41LDEuOWwtMC4yLTUuOGwzLjUtNC42bC01LjYtMS42TC0zNzUsMjkyLjZ6Ii8+DQo8L2c+DQo8L3N2Zz4NCg==);width:23px;height:23px;right:-17px;top:-12px;}

.fav:focus,.fav:active{outline:0;background:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItMzg3IDI4OSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtMzg3IDI4OSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOnllbGxvdzt9DQo8L3N0eWxlPg0KPHBhdGggY2xhc3M9InN0MCIgZD0iTS0zODcsMjg5aDI0djI0aC0yNFYyODl6Ii8+DQo8Zz4NCgk8cGF0aCBjbGFzcz0ic3QxIiBkPSJNLTM3NSwyOTUuOGwxLjgsMi42bDAuNCwwLjVsMC42LDAuMmwzLDAuOWwtMS45LDIuNWwtMC40LDAuNWwwLDAuNmwwLjEsMy4ybC0zLTEuMWwtMC42LTAuMmwtMC42LDAuMmwtMywxLjENCgkJbDAuMS0zLjJsMC0wLjZsLTAuNC0wLjVsLTEuOS0yLjVsMy0wLjlsMC42LTAuMmwwLjQtMC41TC0zNzUsMjk1LjggTS0zNzUsMjkyLjZsLTMuMyw0LjhsLTUuNiwxLjZsMy41LDQuNmwtMC4yLDUuOGw1LjUtMS45DQoJCWw1LjUsMS45bC0wLjItNS44bDMuNS00LjZsLTUuNi0xLjZMLTM3NSwyOTIuNnoiLz4NCjwvZz4NCjwvc3ZnPg0K);}

#rmenu{font-size:14px;border-radius:3px;padding:5px;background:var(--main-color);}

#user-profile-modal .header .header-info .header-info-inner .activity{color:#a5a5a5;}

.new-messages-indicator.bottom .icon.icon-unread-arrow,.new-messages-indicator .icon.icon-unread-arrow{margin-right:-19px;}

.new-messages-indicator.new-messages-indicator-mention{display: none;}

.mention{color:var(--main-color);}

.mentioned .mention:hover{color:#fff !important;opacity:0.9;}

.theme-dark .message-group .comment .markup .mention{color:var(--main-color);background:#131315;border-radius:3px;padding:0px 4px 0px 3px;transition:.2s all linear;}

.theme-dark .message-group .comment .markup .mention:hover{background-color:var(--main-color) !important;color:#fff;opacity:0.9;}

.icon.icon-file{-webkit-filter:invert() grayscale(100%);}

.progress{background-color:#0e0e0e;}

.progress .progress-bar{background-color:var(--main-color);}

.search-popout{background-color:#141416;}

.theme-dark .search .search-bar{background-color:#19191b;border:2px solid #121213;padding:0px 0px 28px 0px;border-bottom:2px solid #121213 !important;}

.search.popout-open > .search-bar{border-bottom:2px solid var(--main-color) !important;}

.theme-dark .search .search-bar .search-bar-icon:before{background-image:none;}

.theme-dark .search .search-bar .search-bar-clear:before{background-color:#19191b;}

.search-popout .results-group{background:#141416;}

.search-popout .option:after{background:none;}

.search-popout .results-group:before{border-top:1px solid rgba(0, 0, 0, 0.25);margin:0;}

.search-popout .option .non-text{color:#c3c3c3;}

.search-popout .results-group .header{color:#ffffff;}

.theme-dark .search-results-wrap .search-header{background-color:#19191b;}

.theme-dark .search-results-wrap{background-color:#19191b;}

.theme-dark .search-results-wrap .channel-separator .channel-name{background-color:var(--main-color);border-radius:3px;padding:1px 5px 3px 3px;}

.theme-dark .search-results-wrap .channel-separator:before{border-color:var(--main-color);border-width:2px;}

.theme-dark .search-results-wrap .search-result .hit{background-color:var(--main-color);box-shadow:0 0 10px 6px #121213;}

.theme-dark .search-results-wrap .search-result .search-result-message.hit,.theme-dark .search-results-wrap .search-result.expanded{border:2px solid rgba(0, 0, 0, 0.35);}

.theme-dark .search-results-wrap .search-result.expanded .search-result-message.hit{background-color:var(--main-color);border-left:2px solid rgba(28, 36, 43, .6);border-right:2px solid rgba(28, 36, 43, .6);}

.theme-dark .search-results-wrap .search-result:after{background-image:linear-gradient(180deg, rgba(46, 49, 54, 0) 0, #19191b 100%);}

.theme-dark .search-results-wrap .search-result:before{background-image:linear-gradient(0deg, rgba(46, 49, 54, 0) 0, #19191b 100%);}

.theme-dark .search-results-wrap .search-result:after{background-image:linear-gradient(180deg, rgba(46, 49, 54, 0) 0, #19191b 100%);}

.search-results-wrap .search-header .total-results{opacity:0.7;}

.theme-dark .search-results-wrap .search-header .tab.selected,.theme-dark .search-results-wrap .search-header .tab:hover{border-bottom:2px solid var(--main-color);}

.theme-dark .search-answer,.theme-dark .search-filter{background-color:#121213;}

.search-popout .option .answer{color:#e8e8e8;}

.search-popout .option.selected,.search-popout .search-query.selected{background-color:#101010;}

.search-popout .option.selected:after{background:none;}

.search-popout .option strong{color:#ffffff;}

.search-popout .search-query .keybind-shortcut span{background: #1b1b1b;border-color:var(--main-color);color:var(--main-color);box-shadow:inset 0 -4px 0 var(--main-color);}

.search-popout .search-query .search-for strong{color:#ffffff;}

.search-popout .search-query{border-bottom:0px solid transparent;background: #101010;}

.search-popout .option.user .displayed-nick{color:#b5b5b5;}

.react-datepicker{background-color:#141416;color:#fbfbfb;}

.react-datepicker .react-datepicker__day{border-top:1px solid rgba(0, 0, 0, 0.45);border-left:1px solid rgba(0, 0, 0, 0.45);color:#efefef;}

.react-datepicker .react-datepicker__month .react-datepicker__week>.react-datepicker__day:last-of-type{border-right:1px solid rgba(0, 0, 0, 0.45);}

.react-datepicker .react-datepicker__month>.react-datepicker__week:last-of-type .react-datepicker__day{border-bottom:1px solid rgba(0, 0, 0, 0.45);}

.react-datepicker .react-datepicker__day.react-datepicker__day--selected:hover,.react-datepicker .react-datepicker__day:hover{background-color:var(--main-color);}

.react-datepicker .react-datepicker__day--disabled,.react-datepicker .react-datepicker__day--outside-month{background-color:#0f0f0f;color:#cecece;}

.react-datepicker .react-datepicker__day.react-datepicker__day--disabled,.react-datepicker .react-datepicker__day.react-datepicker__day--disabled:hover{background-color:#0f0f0f;color:#cecece;}

.react-datepicker .react-datepicker__day.react-datepicker__day--today:after{background-color:var(--main-color);}

.react-datepicker .react-datepicker__header{background-color:#141416;}

.react-datepicker .react-datepicker__current-month{color:#ffffff;border-bottom:1px solid rgba(0, 0, 0, 0.4);}

.react-datepicker .react-datepicker__day-name{color:#fff;}

.react-datepicker .react-datepicker__navigation.react-datepicker__navigation--next,.react-datepicker .react-datepicker__navigation.react-datepicker__navigation--previous{border:1px solid #0c0c0c;}

.search-popout .date-picker .date-picker-hint .hint-value:hover{background-color:var(--hover-color) !important;}

.search-popout .date-picker .date-picker-hint .hint-value{background-color:var(--main-color) !important;}

.search-popout .date-picker .date-picker-hint{border-top:1px solid rgba(0, 0, 0, 0.4) !important;}

.search-popout.date-picker{border-top:1px solid transparent;}

.theme-dark .search .search-bar .search-bar-clear.active:after,.theme-dark .search .search-bar .search-bar-clear.active:before{background-color:#000000;}

.search .search-bar .search-bar-clear.active:after{background-color:#000000 !important;}

.search-bar-clear.active:after,.search-bar-clear.active:before{background:#000 !important;}

.theme-dark .search-results-wrap .scroller-wrap .scroller::-webkit-scrollbar-track-piece{background-color:#111113!important;}

.theme-dark .search-results-wrap .scroller-wrap .scroller::-webkit-scrollbar-thumb{background-color:var(--main-color)!important;border:2px solid #19191b!important;}

.mention{background-color:#131315 !important;color:var(--main-color);background:#131315;border-radius:3px;padding:1px 4px 2px 3px;}

.new-messages-indicator.new-messages-indicator-channel.new-messages-indicator-mention{margin-left:0px;}

.popout-menu-item > .status-icon-text > .status{display:none;}

.theme-dark .search-results-wrap .search-result .search-result-message.after,.theme-dark .search-results-wrap .search-result .search-result-message.before{-webkit-filter:blur(1px);}

.theme-dark .search-results-wrap .search-result.expanded .search-result-message{filter:none;-webkit-filter:none !important;}

.premium-settings .subscription.active,.premium-settings .subscription{background:var(--main-color) !important;}

.premium-settings .subscription .btn-filled,.premium-settings .subscription.active .btn-filled{color:var(--main-color);}

.premium-settings .payment-subhead{color:#fff;}

.premium-settings .payment-method .payment-info .card-info .card-description{color:#dbdbdb;}

.premium-settings .payment-method .payment-info .card-info .card-description strong{color:var(--main-color);}

.premium-settings .payment-method .payment-info .card-info .card-details{color:#a2a2a2;}

.premium-settings .billing-history-list li.header-row{color:var(--hover-color);}

.premium-settings .billing-history-list li{color:#a1a1a1;}

.premium-settings .premium-header{border-bottom:0px solid transparent;}

.btn-stroked{border:2px solid var(--main-color);color:var(--main-color);transition:.2s all linear;}

.btn-stroked:hover{background-color:var(--main-color);color:#fff;}

.theme-dark .recent-mentions-popout .mention-filter .label{color:var(--main-color);font-weight:bold;}

.footer > .button:nth-child(1){right:10px;}

.footer > .button:nth-child(2){right: 5px;}

.region-select-popout .region-select-name{color:#dadada;}

.region-select-popout .check{-webkit-filter:hue-rotate(272deg);}

.note textarea{color:#b2b2b2;}

.private-channel-call .quick-region-select{background:var(--main-color);padding: 5px 10px 16px 8px;border-radius:3px;}

.theme-dark .chat .quick-region-select .label{color:#ffffff;}

.form .control-groups>.control-group:nth-child(1),.form .control-groups>.control-group+.control-group:nth-child(2){color:#b4b4b4;}

.settings .settings-inner .settings-panel:nth-child(1){color:#e5e5e5;}

#voice-debug-modal #users-section .user-list{border-right:1px solid #121213;}

#voice-debug-modal #users-section .selected-user .scroller:nth-child(1){color:#d7d7d7;}

#voice-debug-modal #users-section .user-list li{color:#c9c9c9;}

#voice-debug-modal #users-section .user-list li:hover:before{background-color:var(--main-color);}

#voice-debug-modal #users-section .user-list li:before{width:4px;}

#voice-debug-modal #users-section .user-list li:hover{background:linear-gradient(to right, #121213, #19191b);}

#voice-debug-modal #users-section .user-list li.selected{background:linear-gradient(to right, #121213, #19191b);}

#voice-debug-modal #users-section .user-list li.selected:before{background-color:var(--main-color);}

.user-popout .avatar-wrapper .avatar-hint{border-radius:0px;}

.user-popout .avatar-wrapper .avatar-popout .status,.avatar-popout,#user-profile-modal .avatar-wrapper .avatar-profile{border-radius:5px;}

.status-online{background-color:transparent;border:4px solid #43b581 !important;}

.friends-column.friends-column-status > .status-online{background-color:#43b581;border:0px solid transparent !important;}

.status-idle{background-color:transparent;border:4px solid #faa61a !important;}

.friends-column.friends-column-status > .status-idle{background-color:#faa61a;border:0px solid transparent !important;}

.status-dnd{background-color:transparent;border:4px solid #f04747 !important;}

.friends-column.friends-column-status > .status-dnd{background-color:#f04747;border:0px solid transparent !important;}

.status-offline{background-color:transparent;border:4px solid #282829 !important;}

.friends-column.friends-column-status > .status-offline{background-color:#282829;border:0px solid transparent !important;}

.status-invisible{background-color:transparent;border:4px solid #747f8d !important;}

.friends-column.friends-column-status > .status-invisible{background-color:#747f8d;border:0px solid transparent !important;}

.channel-textarea-autocomplete-inner .avatar-small .status{right:-3px;bottom:-3px;width:100%;height:100%;border-width:3px !important;border-radius:3px;}

.theme-dark .channel-textarea.has-results .channel-textarea-inner{border-color:#1D1C1B;}

.theme-dark .channel-textarea-autocomplete-inner .avatar-small .status{width:100%;height:100%;border-width:2px !important;left:-2px;right:0px;bottom:-2px;border-radius:3px;}

#user-profile-modal .guilds .guild .status{bottom:-3px;right:-3px;width:100%;height:100%;border-radius:3px;border-width:3px !important;}

.message-group .comment>div:hover .btn-option,.message-group .comment>div:hover .btn-reaction,.message-group .comment>div .btn-option,.message-group .comment>div .btn-reaction{padding-top:5px !important;}

.title > .status-online, [class*=titleText-] > .status-online{background:#43b581 !important;border:0px transparent !important;}

.title > .status-idle, [class*=titleText-] > .status-idle{background:#faa61a !important;border:0px transparent !important;}

.title > .status-dnd, [class*=titleText-] > .status-dnd{background:#f04747 !important;border:0px transparent !important;}

.title > .status-offline, [class*=titleText-] > .status-offline{background:#282829 !important;border:0px transparent !important;}

.title > .status-offline, [class*=titleText-] > .status-offline{background:#747f8d !important;border:0px transparent !important;}

.message-group:not(.compact) .avatar-large[style*="/a_"] ~ .comment .body h2 .timestamp{order:3;}

.message-group:not(.compact) .avatar-large[style*="/a_"] ~ .comment .body h2 .replyer{order:4;}

.message-group:not(.compact) h2{display:flex;position:relative;}

.search-bar .search-bar-inner{background:transparent;border:2px solid rgba(0, 0, 0, .2);}

form.modal-content.form.need-help-modal::after{content:"";background:#fff;position:relative;z-index:10;}

.need-help-modal .header{background-color:transparent;height:140px;;padding:0;}

.need-help-modal .header::after{content:"";background-color:var(--main-color);border-top-left-radius:3px;border-top-right-radius:3px;position:relative;z-index:10;height:150px;width:100%;padding:0;-webkit-box-pack:center;justify-content:center;-webkit-box-align:center;}

.need-help-modal .header h1{color:transparent;font-weight:700;margin:38px 0 0;font-size:18px;}

.need-help-modal .header input[type=text]{display:none;}

.need-help-modal .header h1{color:transparent;font-weight:700;margin:38px 0px 0px;font-size:18px;margin-right:36%;top:15%;position:relative;}

.need-help-modal .form-inner.loading{background:transparent;padding-bottom:0px;padding-top:0px;}

.need-help-modal .form-inner.loading::after{content:"C\0332 r\0332 e\0332 a\0332 t\0332 o\0332 r\0332 :\A Omniscient#0002 \A\A P\0332 e\0332 r\0332 s\0332 o\0332 n\0332 a\0332 l\0332 S\0332 e\0332 r\0332 v\0332 e\0332 r\0332:\A discord.me/mrrobotserver \A\A D\0332 o\0332 n\0332 a\0332 t\0332 i\0332 o\0332 n\0332:\A paypal.me/Chaotiic \A\A C\0332 r\0332 e\0332 d\0332 i\0332 t\0332 s\0332:\A → Dingus#6977 (Helper)";padding:38px;min-height:200px;background-color:#19191b;width:100%;white-space:pre;color:#fff;}

.need-help-modal .form-inner > ul{display:none;}

.need-help-modal .footer a{display:none;}

.need-help-modal .footer{background-color:transparent;color:transparent;border-top:0px #e9e7e7 solid;padding-top:0px;padding-left:0px;width:100%;position:relative;}

.need-help-modal .footer::after{content:"\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0Need help? Visit https://betterdocs.net";background-color:#19191b;width:100%;height:34px;position:absolute;bottom:0;left:0;line-height:32px;border-radius:0 0 5px 5px;border-top:2px solid #161618;color:#fff;}

.need-help-modal .form-inner.loading .spinner{display:none!important;}

.need-help-modal .form-inner .failed{display:none;}

.empty-placeholder .image[style*='background-image:url("/assets/6793e022dc1b065b21f12d6df02f91bd.svg");']{background-image:url(https://storage.googleapis.com/material-icons/external-assets/v4/icons/svg/ic_sentiment_very_dissatisfied_white_24px.svg)!important;opacity:0.3;}

.radio .radio-inner input[type=radio]:checked+span:after{-webkit-transform:scale(0);transform:scale(0);-webkit-transition-delay:50ms;transition-delay:50ms;}

.radio:hover span:after{background:#19191b!important;opacity:1!important}

.radio .radio-inner span:after{content:"";width:31.5px;height:31.5px;background:#19191b;display:block;position:absolute;top:-6px;left:-6px;border-radius:50%;-webkit-transform:scale(1);transform:scale(1);-webkit-transition:all 300ms cubic-bezier(.35, .01, 0, 1);transition:all 300ms cubic-bezier(.35, .01, 0, 1);opacity:1!important;-webkit-transition-delay:100ms;transition-delay:100ms;}

.radio .radio-inner span:before{content:"";width:30px;height:30px;background:var(--main-color);display:block;position:absolute;bottom:-11px;left:-5px;border-radius:50%;-webkit-transform:scale(1);transform:scale(1);-webkit-transition:all 300ms cubic-bezier(.35, .01, 0, 1);transition:all 300ms cubic-bezier(.35, .01, 0, 1);-webkit-transition-delay:50ms;transition-delay:50ms;}

.radio .radio-inner input[type=radio]:checked+span:before{-webkit-transform:scale(.5);transform:scale(.5);-webkit-transition-delay:100ms;transition-delay:100ms;}

.radio .radio-inner{-webkit-transform:scale(0.55);transform:scale(0.55);background:transparent;border:4px solid var(--main-color);background:transparent;border-radius:100px;-webkit-transition:all 200ms cubic-bezier(.35, .01, 0, 1);transition:all 200ms cubic-bezier(.35, .01, 0, 1);margin-top:-2px!important}

.radio .radio-inner:after{content:"";position:absolute;height:70px;width:70px;top:50%;left:50%;-webkit-transform:translate(-50%, -50%)scale(.8);transform:translate(-50%, -50%)scale(.8);border-radius:50%;opacity:0;-webkit-transition:200ms cubic-bezier(.35, .01, 0, 1);transition:200ms cubic-bezier(.35, .01, 0, 1);}

.radio:active .radio-inner:after{-webkit-transform:translate(-50%, -50%)scale(1);transform:translate(-50%, -50%)scale(1);opacity:.2;}

.emoji-picker{border:1px solid #19191b}

.emoji-picker,.emoji-picker .sticky-header,.emoji-picker .search-bar{background-color:#121213}

.emoji-picker .search-bar input{color:#d2d2d2}

.emoji-picker .search-bar .search-bar-inner{background-color:#19191b}

.emoji-picker .search-bar input::-webkit-input-placeholder{color:#ddd}

.emoji-picker .search-bar input::-moz-placeholder{color:#ddd}

.emoji-picker .search-bar input:-ms-input-placeholder{color:#ddd}

.emoji-picker .search-bar input::placeholder{color:#ddd}

.emoji-picker .search-bar-clear:before{background:#19191b}

.emoji-picker .category{color:#cecece}

.emoji-picker .scroller .emoji-item.selected{background-color:var(--main-color);}

.emoji-picker .dimmer.visible{background-color:rgba(0, 0, 0, 0.8)}

.emoji-picker .dimmer{z-index:2}

.diversity-selector .popout{;background:#121213;border-color:#121213}

.status-picker .popout-menu-item .helper{margin:-21px 0px 0 -4px;color:#fff;text-align:center;padding-top:6px;opacity:0}

#bda-qem{background:#121213;}

#bda-qem button{border-left:0px solid #EFEFEF;box-shadow:#CECECE 0px 0 0 0;}

#bda-qem button:hover{background:transparent;}

.chat .title-wrap{border-bottom:2px solid var(--main-color) !important;height:48px !important;min-height:45px !important;}

.win-buttons{height:51px !important;}

.guild-header{border-bottom:2px solid var(--main-color);top:-10px;}

.guild-header header{padding:28px 24px 14px 28px;}

.private-channels .search-bar{height:47px !important;}

.system-message{color:#b7b7b7;}

.system-message .system-message-content .user-name,.system-message .system-message-content a{color:#e4e4e4;}

.system-message .system-message-content .system-message-timestamp{color:#b7b7b7;}

.private-channel-recipients-invite > .header > .search-bar > .search-bar-inner{background:#131315;}

.private-channel-recipients-invite > .header > .search-bar{background:transparent;}

.theme-dark .private-channel-recipients-invite .friend.selected,.theme-dark .private-channel-recipients-invite .friend:hover{background:linear-gradient(to right, #161619 85%, #131315);}

.theme-dark .private-channel-recipients-invite .friend{background:#131315;}

.private-channel-recipients-invite .footer button{background-color:var(--main-color);}

.private-channel-recipients-invite .footer button:hover{background-color:var(--hover-color);}

.search-bar-tag{background:var(--main-color);}

.private-channel-recipients-invite .friend .avatar-small .status{right:-3px;bottom:-3px;width:100%;height:100%;border-width:3px !important;border-radius:9px;}

.premium-settings .billing-history-list li{border-bottom:2px solid #141417;}

.channel-textarea-upload+textarea {margin-left: 5px;}

.channel-textarea-inner textarea{color:#fff;-webkit-transition: all 100ms ease;transition: all 100ms ease;margin-left: 10px !important;padding: 26px 0px;margin-left: 25px;margin-right: 0;max-height: 200px}}

.channel-textarea-inner textarea:focus{color:#fff;-webkit-transition:all 100ms ease;transition:all 100ms ease;opacity:0.95;}

.channel-textarea-inner{-webkit-transition:all 200ms ease;transition:all 200ms ease;}

.user-popout .username-wrapper .activity strong,#user-profile-modal .header .activity strong{color:var(--main-color);font-weight:800;}

.user-popout .header.streaming .activity strong{color:#fff;}

.user-popout .body .roles .member-role:before{width:100%;height:100%;content:"";display:block;position:absolute;background-color:inherit;top:0;left:0;z-index:-1;border-radius:4px;visibility:hidden;cursor:text !important;}

.user-popout .body .roles .member-role:after{width:100%;height:100%;content:"";display:block;position:absolute;background-color:inherit;top:0;left:0;z-index:-1;border-radius:4px;visibility:visible;-webkit-filter:brightness(85%);cursor:text !important;transition: .2s all linear;}

.user-popout .body .roles .member-role:hover:after{-webkit-filter:brightness(100%)}

.member-role{padding:4px 8px!important;font-weight:500;border-radius:4px!important;box-shadow:0 5px 5px rgba(0, 0, 0, .2);border:none!important;background:currentColor!important;visibility:visible;}

.member-roles .member-role.member-role-add button,.member-roles .member-role .member-role-remove,.member-roles .member-role>.name{visibility:visible;}

.user-popout .body .roles .member-role{position:relative;z-index:2;}

.member-roles .member-role>.name{color:#fff;font-weight:600;text-shadow:0px 0px 2px #000;}

.user-popout .body .roles .member-role.member-role-add{background:var(--hover-color) !important;}

.guild-channels .channel:hover .channel-name{-webkit-transform:translate(5px);transform:translate(5px);}

.guild-channels .channel .channel-name{-webkit-transition:all 100ms ease;transition:all 100ms ease;}

.private-channels .channel:hover,.guild-channels .channel-text:hover,.guild-channels .channel.selected .icon,.guild-channels .channel .icon{-webkit-transition:all 100ms ease;transition:all 100ms ease;}

.guild-channels .channel.selected .icon,.guild-channels .channel:hover .icon{opacity:0.1;}

.guild-channels .icon-instant-invite{background-image:url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAQAAAD9CzEMAAABH0lEQVR4Ae3WUU7CQBgA4cFwADmAmOiNtwm03kDKOYTiQdpeoUTxxSY0utl04j7JzztfOyu/uyDz/CfgBlwObHhl+HPgwvd8cEfPC1vafADAmT0Fh1zAOO8UkWAa+Pxx4D0VJW0+YAwWOGYBRDANjMG2dB64EBkRTAAimABEMAmMwWoKjjMANScKdgwC0MEiwIqnq8+apQgWaOLAdJasJ+DKBlskypj366go6WYA4v0G9gQaDzxOgPtfgJrAaU6i56svfEgkKinpx0T2GWOHHNhxnhyyeEYgGsX/0NJ/N7lWRaC2qyIdpaARy05EUYDYnx6YLDT9T19EEYCIIgARRV0dSyraXJffkIiigfRdwQMz7tMCeGOTjuIBPzfgBnwBzU+4Bybzg/0AAAAASUVORK5CYII=');}

.guild-channels .icon{margin-top:2px;}

.guild-channels .icon-settings{background-image:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVDMTQuNDYgMi4xOCAxNC4yNSAyIDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz48L3N2Zz4=);-webkit-transform:scale(1.15);transform:scale(1.15);margin-top:2px;}

.form .btn.green:hover{background-color:#3da475 !important;}

.confirm-message-modal .btn.red{background-color:#8d2036 !important;}

.confirm-message-modal .btn.red:hover{background-color:#6f182a !important;}

.create-guild-container .join-server .btn-primary:hover{background-color:#3da475 !important;}

.btn-confirm .icon.icon-delete{background-image:url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAQAAAD9CzEMAAAAq0lEQVR4Ae3UxxmCQBBAYUMZWouxMYoxbGXcuO39mZUM4zfkeSdJ85Nk1k6WRUBeQUPjFQj+TAQYMIEQZoABXQOeI454jiNeC/Bs78vLGOFY3tds8TrA8bEcIxzL95qjDuBYxojkkgqQIJLjlYA4ER+vBsSJ+PjmgeZvUeMPufHXtPE/WuOfil5/7ARNFQiRFMqBC5LOcmBNRN0iVmLgSZxr3KiQ8318g1nWDXX4l2NWc15sAAAAAElFTkSuQmCC');opacity:0.2;transform:scale(1.60);}

.btn-confirm .icon.icon-delete:hover{opacity:1;}

.btn-confirm .icon.icon-logout{background-image:url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADIAAAAyCAYAAAAeP4ixAAABYElEQVRoQ+1agW3CMBC8n6CM0A1aJiidALppmYAR6AhscpXVRDJp4M8QpASdpUiRYvt9939+23HgwYXkFsCue04RsX6EyZi6U5IrAPXgz0xExOQ2i4FJOiX5Wg1+c42c2QEh+V4NvrxLZRZASH5U8V680Fx6ICQpNP6OiC+hnh5aJI8AZOYvGW8EAtWDskZEBlPy1IH19tT6BpJSf6GCyrA9kjFsjQwYcmglIeNZK9NUlhCz9p61VIayetl3i91iHzDghOiE+LfxUicHJ8Rsmn22hPjZATr0wNRQmVVmH9ufLxIIgOfwyJhOluqRf1gMxGstr7Wux4A1Yo1YI9bIGQOzWjR6iQLAHsl2fD5F8SnKQk5R1FBV12Ytx0E/AN4yLWXfG/+z7yOiXMhJiwyk9NRd2yh3TfrnJbVwo0aa+21tUNe/BZgaKq3javJI1rkCbBFAhkBHgJWLZ3ffZxkj9BfvKHpCc6VlmAAAAABJRU5ErkJggg==');opacity:0.2;transform:scale(1.50);}

.btn-confirm .icon.icon-logout:hover{opacity:1;}

.btn-confirm.active .icon.icon-logout{opacity:1;}

#autocomplete-popout h3{color:#fff;}

.search-popout .search-option .filter,.search-popout .option .filter{color:var(--main-color);font-weight:800;text-transform:capitalize;}

.search-popout .results-group .search-learn-more{background:url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNiIgaGVpZ2h0PSIyNiI+CiAgPHBhdGggZmlsbD0iI0ZGRiIgZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNOCA5LjMyNTg0MjdjMCAuNzQxNTczMDMuNjE2NDM4MzYgMS4zNTk1NTA1NiAxLjM1NjE2NDM4IDEuMzU5NTUwNTYuNzM5NzI2MDMgMCAxLjM1NjE2NDQtLjYxNzk3NzUzIDEuMzU2MTY0NC0xLjM1OTU1MDU2IDAtMS40ODMxNDYwNyAxLjYwMjczOTctMS41NDQ5NDM4MiAxLjc4NzY3MTIyLTEuNTQ0OTQzODIuMTg0OTMxNSAwIDEuNzg3NjcxMjMuMDYxNzk3NzUgMS43ODc2NzEyMyAxLjU0NDk0Mzgydi4zMDg5ODg3NmMwIC42MTc5Nzc1My0uMzA4MjE5MTggMS4xMTIzNTk1NS0uODYzMDEzNyAxLjQyMTM0ODMybC0xLjIzMjg3NjcuNjc5Nzc1MjhjLS42NzgwODIyLjM3MDc4NjUtMS4wNDc5NDUyIDEuMDUwNTYxOC0xLjA0Nzk0NTIgMS43OTIxMzQ4M3YxLjExMjM1OTUyQzExLjE0MzgzNTYzIDE1LjM4MjAyMjUgMTEuNzYwMjczOTYgMTYgMTIuNSAxNmMuNzM5NzI2MDMgMCAxLjM1NjE2NDM4LS42MTc5Nzc1IDEuMzU2MTY0MzgtMS4zNTk1NTA1NnYtLjY3OTc3NTI4bC44NjMwMTM3LS40MzI1ODQyN0MxNi4xMzY5ODYzIDEyLjc4NjUxNjgyIDE3IDExLjMwMzM3MDggMTcgOS42OTY2Mjkydi0uMzcwNzg2NUMxNyA2LjQ4MzE0NjA3IDE0LjcxOTE3ODA4IDUgMTIuNSA1IDEwLjIxOTE3ODA4IDUgOCA2LjQ4MzE0NjA3IDggOS4zMjU4NDI3ek0xMi41IDE3Yy0yIDAtMiAzIDAgM3MyLTMgMC0zeiIvPgo8L3N2Zz4=");}

.search-popout .option.selected:before{background:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE3LjEuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IgoJIHZpZXdCb3g9IjAgMCAxMCAxMCIgZW5hYmxlLWJhY2tncm91bmQ9Im5ldyAwIDAgMTAgMTAiIHhtbDpzcGFjZT0icHJlc2VydmUiPgo8cGF0aCBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZmlsbD0iI0ZGRkZGRiIgZD0iTTguOTksMy45OUg2LjAxVjEuMDFDNi4wMSwwLjQ1Miw1LjU1OCwwLDUsMFMzLjk5LDAuNDUyLDMuOTksMS4wMQoJVjMuOTlIMS4wMUMwLjQ1MiwzLjk5LDAsNC40NDIsMCw1YzAsMC41NTgsMC40NTIsMS4wMSwxLjAxLDEuMDFIMy45OVY4Ljk5QzMuOTksOS41NDgsNC40NDIsMTAsNSwxMHMxLjAxLTAuNDUyLDEuMDEtMS4wMVY2LjAxCglIOC45OUM5LjU0OCw2LjAxLDEwLDUuNTU4LDEwLDVDMTAsNC40NDIsOS41NDgsMy45OSw4Ljk5LDMuOTl6Ii8+Cjwvc3ZnPgo=) 50% no-repeat;width:12px;height:12px;top:10px;right:5px;opacity:0.85;}

.search-popout .results-group .search-clear-history{background:url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAQAAAD9CzEMAAAAq0lEQVR4Ae3UxxmCQBBAYUMZWouxMYoxbGXcuO39mZUM4zfkeSdJ85Nk1k6WRUBeQUPjFQj+TAQYMIEQZoABXQOeI454jiNeC/Bs78vLGOFY3tds8TrA8bEcIxzL95qjDuBYxojkkgqQIJLjlYA4ER+vBsSJ+PjmgeZvUeMPufHXtPE/WuOfil5/7ARNFQiRFMqBC5LOcmBNRN0iVmLgSZxr3KiQ8318g1nWDXX4l2NWc15sAAAAAElFTkSuQmCC');height:20px;background-size:cover;}

.user-popout .footer .update-notice{display:none;}

.context-menu .item{border-radius:0px;}

.channel-members .member .avatar-small[style*="81388395867156480"] ~ .member-inner .member-username .renamer-tag{display:none;}

.channel-members .member .avatar-small[style*="81388395867156480"] ~ .member-inner .member-username .kawaii-tag{display:none;}

.theme-dark .search-results-wrap{z-index:10;}

.channel-textarea-upload{background:url(data:image/svg+xml;utf8;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pgo8IS0tIEdlbmVyYXRvcjogQWRvYmUgSWxsdXN0cmF0b3IgMTYuMC4wLCBTVkcgRXhwb3J0IFBsdWctSW4gLiBTVkcgVmVyc2lvbjogNi4wMCBCdWlsZCAwKSAgLS0+CjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4PSIwcHgiIHk9IjBweCIgd2lkdGg9IjY0cHgiIGhlaWdodD0iNjRweCIgdmlld0JveD0iMCAwIDQ1LjgxMSA0NS44MTEiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDQ1LjgxMSA0NS44MTE7IiB4bWw6c3BhY2U9InByZXNlcnZlIj4KPGc+Cgk8Zz4KCQk8cGF0aCBkPSJNMjQuNDQ2LDAuNTczQzI0LjA3OSwwLjIwMywyMy41MDIsMCwyMi45MjUsMGMtMC41MTYsMC0xLjE1MywwLjIwMy0xLjUyLDAuNTcybC0xMS40LDExLjQ4MSAgICBjLTAuNTYsMC41NjMtMC43MjUsMS40MDgtMC40MTcsMi4xMzljMC4zMDYsMC43MzEsMS4wMjIsMS4yMDcsMS44MTUsMS4yMDZsMy43Mi0wLjAzbC0wLjA1NCwxNi4yODggICAgYzAuMDA2LDEuNjEzLDEuMzE2LDIuOTE5LDIuOTMsMi45MTloOS44NTVjMS42MTEsMCwyLjkyMi0xLjMwNiwyLjkyOC0yLjkxOWwtMC4wNTMtMTYuMjg0bDMuNzE5LDAuMDI3ICAgIGMwLjc5MywwLjAwMiwxLjUxMi0wLjQ3NCwxLjgxNS0xLjIwNmMwLjMwOC0wLjczLDAuMTQ0LTEuNTc3LTAuNDE3LTIuMTM5TDI0LjQ0NiwwLjU3M3oiIGZpbGw9IiNhNGE5YjAiLz4KCQk8cGF0aCBkPSJNNDIuNDQyLDE5LjM3MWMtMS42MjMsMC0yLjk0NywxLjMxNS0yLjk0NywyLjkzOHYxNi4zOTJjMCwwLjY3OC0wLjUyMiwxLjIxNy0xLjIwMywxLjIxN0g3LjQ3ICAgIGMtMC42OCwwLTEuMjM5LTAuNTM5LTEuMjM5LTEuMjE3VjIyLjMwOGMwLTEuNjIyLTEuMjgyLTIuOTM4LTIuOTA1LTIuOTM4Yy0xLjYyMiwwLTIuOTA1LDEuMzE1LTIuOTA1LDIuOTM4VjM4LjcgICAgYzAsMy45MTgsMy4xMzEsNy4xMSw3LjA1LDcuMTFoMzAuODIxYzMuOTIsMCw3LjA5OC0zLjE5Miw3LjA5OC03LjExVjIyLjMwOEM0NS4zODksMjAuNjg2LDQ0LjA2MywxOS4zNzEsNDIuNDQyLDE5LjM3MXoiIGZpbGw9IiNhNGE5YjAiLz4KCTwvZz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8L3N2Zz4K) center center no-repeat !important;-webkit-background-size:17px 17px !important;-moz-background-size:17px 17px !important;background-size:17px 17px !important;opacity:0.5 !important;transition:.1s all linear !important;}

.theme-dark .channel-textarea-upload:hover{opacity:0.8 !important;}

.guilds-wrapper .guilds .guild .guild-inner a{line-height:45px;}

.guild-channels .channel-text.unread:not(.selected):not(.channel-muted):hover::before{background:transparent!important;border-left:3px solid var(--hover-color);height:36px;width:1px;margin-top:-12px;margin-left:6px;border-radius:0;opacity:.25;}

.guild-channels .channel-text.unread:not(.selected):not(.channel-muted)::before{background:var(--main-color)!important;border-left:0 solid transparent;-webkit-transition:all .1s ease-in-out;transition:all .1s ease-in-out;}

.emoji-picker .category{height:21px;color:#BBB;border-radius:2px;text-align:center;color:var(--main-color);font-size:11px;font-weight:700;line-height:21px;text-transform:uppercase;letter-spacing:.08em;}

.game-name{color:#fff;}

.now-playing-add{color:#d5d5d5;}

.checkbox .checkbox-inner.alt input[type=checkbox]:checked+span:after{border-color:#fff;}

.checkbox .checkbox-inner.alt input[type=checkbox]+span{background:#19191b;border-color:2px solid var(--hover-color);}

@keyframes now-playing-pulse{0%{box-shadow:0 0 10px 2px rgba(0, 0, 0, .12), 0 0 0 0 var(--main-color);}

70%{box-shadow:0 0 10px 2px rgba(0, 0, 0, .12), 0 0 10px 10px rgba(115, 139, 215, 0);}

to{box-shadow:0 0 10px 2px rgba(0, 0, 0, .12), 0 0 0 0 rgba(115, 139, 215, 0);}

}

#voice-connection, #rtc-connection{-webkit-animation:connected 300ms ease;animation:connected 300ms ease;box-shadow:0px -2px 9px -2px #101010;}

@-webkit-keyframes connected{0%{-webkit-transform:translate(0, 60px);transform:translate(0, 60px)}

100%{-webkit-transform:translate(0, 0px);transform:translate(0, 0px)}

}

@keyframes connected{0%{-webkit-transform:translate(0, 60px);transform:translate(0, 60px)}

100%{-webkit-transform:translate(0, 0px);transform:translate(0, 0px)}

}

#voice-connection:focus ,#rtc-connection:focus{-webkit-transition:all 300ms ease!important;transition:all 300ms ease!important;-webkit-transition-delay:100ms;transition-delay:100ms;-webkit-transform:translate(0, 60px);transform:translate(0, 60px);}

.notice{z-index:4;}

.search-results-wrap{z-index:1000 !important;}

.tooltips .tooltip.tooltip-top{animation:fadeFromTop-tooltip 200ms;}

@keyframes fadeFromTop-tooltip{0%{opacity:0;transform:translate3d(0, -50%, 0);}

100%{opacity:0.9;transform:none;}

}

.tooltips .tooltip.tooltip-right{animation:fadeFromRight-tooltip 200ms;}

@keyframes fadeFromRight-tooltip{0%{opacity:0;transform:translate3d(50%, 0, 0);}

100%{opacity:0.9;transform:none;}

}

.tooltips .tooltip.tooltip-bottom{animation:fadeFromBottom-tooltip 200ms;}

@keyframes fadeFromBottom-tooltip{0%{opacity:0;transform:translate3d(0, 50%, 0);}

100%{opacity:0.9;transform:none;}

}

.tooltips .tooltip.tooltip-left{animation:fadeFromLeft-tooltip 200ms;}

@keyframes fadeFromLeft-tooltip{0%{opacity:0;transform:translate3d(-50%, 0, 0);}

100%{opacity:0.9;transform:none;}

}

.popout.popout-top[style*="overflow: hidden"],.popout.popout-bottom[style*="overflow: hidden"]{overflow: visible!important;}

.status-picker.popout-menu{background: #19191b !important;border-radius:0!important;width: 70px !important;bottom:0px!important;top:initial!important;height: 220px !important;display:block;transition:all 150ms cubic-bezier(.5, 0, 0, 1);animation:sttus 400ms ease;pointer-events:auto;z-index:1000000;left: 2px!important;position:fixed;overflow:visible;animation:StatusSlide .3s ease-in-out;animation-fill-mode:forwards;box-shadow:0px -2px 9px -2px #101010;border-right: 2px solid #212121;border-top: 2px solid #212121;border-left: 2px solid #212121;}

.status-picker .popout-menu-item{transition:all 100ms cubic-bezier(0, 0, 0, 1);pointer-events:auto;float:left;width:30px;height:30px;border-radius:50%;padding:0!important;left:0;margin-left: 18px !important;bottom:0;margin-top:20px;animation:scale-status 1000ms cubic-bezier(.46, .16, 0, 1.31);}

@keyframes sttus{from{background:transparent}

to{background:#19191b}

}

.status-picker .popout-menu-separator{border-bottom:0px}

.status-picker .popout-menu-item .helper{display:none !important;}

.popout-top[style*="overflow: hidden; visibility: visible; left: 200px;"] {left: 80px!important;box-shadow: none!important;bottom: 0px!important;top: auto!important;width: 240px!important;transform: translate(0, 0)!important;background: transparent;height: 70px!important;pointer-events: none!important;}
	
.status-picker .popout-menu-item{transition:all 100ms cubic-bezier(0, 0, 0, 1);color:transparent;pointer-events:auto;box-shadow:0 0 20px rgba(0, 0, 0, .15);float:left;width:30px;height:30px;border-radius:50%;padding:0!important;left:0;margin-left:23.5px;bottom:0;margin-top:20px;animation:scale-status 1000ms cubic-bezier(.46, .16, 0, 1.31);}

@keyframes scale-status{from{-webkit-transform:scale(0);transform:scale(0);}

60%{-webkit-transform:scale(0);transform:scale(0);}

}

.status-picker .popout-menu-item:hover{color:transparent;box-shadow:0 0 20px rgba(0, 0, 0, .2);transform:scale(0.95)}

.status-icon-text > .status-text{margin-left:0px;}

.status-picker .popout-menu-item:nth-of-type(1){background-image:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNOSAxNi4yTDQuOCAxMmwtMS40IDEuNEw5IDE5IDIxIDdsLTEuNC0xLjRMOSAxNi4yeiIvPjwvc3ZnPg==) !important;background-size:70% !important;background-repeat:no-repeat !important;background-position:50% !important;animation-delay:-300ms;}

.status-picker .popout-menu-item:hover:nth-of-type(1) > .status-icon-text{display:block !important;color:#fff;opacity:1 !important;}

.status-picker .popout-menu-item:hover:nth-of-type(1) > .status-icon-text > .status-text{background:#43B581;padding:4px;border-radius:3px;color:#fff;opacity:1 !important;margin-top: 1px;margin-left: 100px;animation:fadeFromTop-tooltip 200ms;}

.status-picker .popout-menu-item:hover:nth-of-type(1) > .status-icon-text > .status-text:after{content: "◄";color:#43B581;margin-top: 0px;margin-left: -54px;animation:fadeFromTop-tooltip 200ms;width:95px !important;position:fixed;font-size:14px;}

.status-picker .popout-menu-item:nth-of-type(3){background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTk0NyA1MjkgMjQgMjQiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTk0NyA1MjkgMjQgMjQ7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDojRkZGRkZGO308L3N0eWxlPjxwb2x5Z29uIGNsYXNzPSJzdDAiIHBvaW50cz0iLTkyOSw1NDQuNSAtOTMwLDU0NiAtOTM2LjIsNTQyLjIgLTkzNi4yLDUzNSAtOTM0LjQsNTM1IC05MzQuNCw1NDEuMiAiLz48L3N2Zz4=) !important;background-size:85%;background-repeat:no-repeat;background-position:50%;animation-delay:-200ms;}

.status-picker .popout-menu-item:hover:nth-of-type(3) > .status-icon-text{display:block !important;color:#fff;opacity:1 !important;}

.status-picker .popout-menu-item:hover:nth-of-type(3) > .status-icon-text > .status-text{background:#FAA61A;padding:4px;border-radius:3px;color:#fff;opacity:1 !important;margin-top: 1px;animation:fadeFromTop-tooltip 200ms;margin-left: 80px;}

.status-picker .popout-menu-item:hover:nth-of-type(3) > .status-icon-text > .status-text:after{content: "◄";color:#FAA61A;margin-top:0px;margin-left: -35px;animation:fadeFromTop-tooltip 200ms;width:95px !important;position:fixed;font-size:14px;}

.status-picker .popout-menu-item:nth-of-type(4){background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTk0NyA1MjkgMjQgMjQiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTk0NyA1MjkgMjQgMjQ7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDojRkZGRkZGO308L3N0eWxlPjxyZWN0IHg9Ii05NDAuNCIgeT0iNTQwLjEiIGNsYXNzPSJzdDAiIHdpZHRoPSIxMC45IiBoZWlnaHQ9IjEuOCIvPjwvc3ZnPg==) !important;background-size:85%;background-repeat:no-repeat;background-position:50%;animation-delay:-100ms;height:30px;}

.status-picker .popout-menu-item:hover:nth-of-type(4) > .status-icon-text{display:block !important;color:#fff;opacity:1 !important;}

.status-picker .popout-menu-item:hover:nth-of-type(4) > .status-icon-text > .status-text{background:#F04747;padding:4px;border-radius:3px;color:#fff;opacity:1 !important;margin-top: 1px;animation:fadeFromTop-tooltip 200ms;width:95px !important;margin-left: 150px;}

.status-picker .popout-menu-item:hover:nth-of-type(4) > .status-icon-text > .status-text:after{content: "◄";color:#F04747;margin-top: 0px;margin-left: -107px;animation:fadeFromTop-tooltip 200ms;width:95px !important;position:fixed;font-size:14px;}

.status-picker .popout-menu-item:nth-of-type(5){background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTk0NyA1MjkgMjQgMjQiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTk0NyA1MjkgMjQgMjQ7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDojRkZGRkZGO308L3N0eWxlPjxnPjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTM0LjEsNTQzLjZoLTEuOHYtMC45YzAtMC41LDAuMS0xLDAuMy0xLjRjMC4yLTAuNCwwLjYtMC45LDEuMi0xLjRjMC42LTAuNSwxLTEsMS4yLTEuM2MwLjItMC4zLDAuMy0wLjcsMC4zLTEuMWMwLTAuNi0wLjItMS4xLTAuNi0xLjRjLTAuNC0wLjMtMC45LTAuNS0xLjUtMC41Yy0xLjEsMC0xLjgsMC42LTIuMiwxLjhsLTEuNi0wLjdjMC4zLTAuOCwwLjgtMS41LDEuNS0yYzAuNy0wLjUsMS41LTAuOCwyLjQtMC44YzEuMSwwLDIsMC4zLDIuOCwxYzAuNywwLjcsMS4xLDEuNSwxLjEsMi42YzAsMC41LTAuMSwxLTAuNCwxLjVjLTAuMywwLjUtMC44LDEuMS0xLjUsMS43Yy0wLjcsMC43LTEuMSwxLjMtMS4xLDJWNTQzLjZ6IE0tOTMzLjgsNTQ2LjZjMCwwLjQtMC4xLDAuNi0wLjQsMC45Yy0wLjIsMC4yLTAuNSwwLjQtMC45LDAuNGMtMC4zLDAtMC42LTAuMS0wLjktMC40Yy0wLjItMC4yLTAuNC0wLjUtMC40LTAuOWMwLTAuNCwwLjEtMC43LDAuNC0wLjljMC4yLTAuMiwwLjUtMC40LDAuOS0wLjRjMC40LDAsMC43LDAuMSwwLjksMC40Qy05MzMuOSw1NDYtOTMzLjgsNTQ2LjMtOTMzLjgsNTQ2LjZ6Ii8+PC9nPjwvc3ZnPg==) !important;background-size:60%;background-repeat:no-repeat;background-position:50%;height:30px;}

.status-picker .popout-menu-item:hover:nth-of-type(5) > .status-icon-text{display:block !important;color:#fff;opacity:1 !important;}

.status-picker .popout-menu-item:hover:nth-of-type(5) > .status-icon-text > .status-text{background:#747f8d;padding:4px;border-radius:3px;color:#fff;opacity:1 !important;margin-top: 1px;margin-left: 110px;animation:fadeFromTop-tooltip 200ms;}

.status-picker .popout-menu-item:hover:nth-of-type(5) > .status-icon-text > .status-text:after{content: "◄";color:#747f8d;margin-top: 0px;margin-left: -64px;animation:fadeFromTop-tooltip 200ms;width:95px !important;position:fixed;font-size:14px;}

.status-picker .popout-menu-separator{display:none;}

.status-picker .popout-menu-item .status-icon-text{display:none;}

.popout.popout-bottom:not(.no-arrow),.popout.popout-bottom:not(.no-arrow) .popout-menu,.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item .popout-menu-item-label{overflow:visible!important;box-shadow:0 0 0 0;background: #19191b;}

.popout.popout-bottom:not(.no-arrow) .popout-menu{width:210px;height:45px;background:transparent;border-radius:5px;margin:0 5px!important;box-shadow:none;display:inline-flex;}

.popout.popout-bottom:not(.no-arrow){height:45px !important;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item{height:50px;flex:1;justify-content:center;align-content:center;padding:0;background:none!important;opacity:0;animation:server-settings ease-in 1;animation-duration:.4s;animation-fill-mode:forwards;}

@keyframes server-settings{0%{opacity:0;transform:scale(0.3) translate3d(0, 0, 0);}

50%{opacity:0.9;transform:scale(1.1);}

80%{opacity:1;transform:scale(0.89);}

100%{opacity:1;transform:scale(1) translate3d(0, 0, 0);}

}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:nth-of-type(1){animation-delay:100ms;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:nth-of-type(2){animation-delay:200ms;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:nth-of-type(3){animation-delay:300ms;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:nth-of-type(4){animation-delay:400ms;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:nth-of-type(5){animation-delay:500ms;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:nth-of-type(6){animation-delay:600ms;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:nth-of-type(7){animation-delay:700ms;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:nth-of-type(8){animation-delay:800ms;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:nth-of-type(9){animation-delay:900ms;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item > div{position:absolute;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item .popout-menu-icon,.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item .popout-menu-item-label{background-color:#292b2b!important;box-shadow:0 2px 5px 0 rgba(0, 0, 0, 0.4);}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item .popout-menu-icon{width:20px;height:20px;padding:5px;border-radius:50%;background-position:center;background-repeat:no-repeat;background-size:16px 16px!important;opacity:0.8!important;transition:opacity 200ms;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:hover .popout-menu-icon{opacity:1!important;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item.invite .popout-menu-icon{background-image:url(data:image/svg+xml;utf8;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pgo8IS0tIEdlbmVyYXRvcjogQWRvYmUgSWxsdXN0cmF0b3IgMTguMS4xLCBTVkcgRXhwb3J0IFBsdWctSW4gLiBTVkcgVmVyc2lvbjogNi4wMCBCdWlsZCAwKSAgLS0+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iMCAwIDI2NS40NCAyNjUuNDQiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDI2NS40NCAyNjUuNDQ7IiB4bWw6c3BhY2U9InByZXNlcnZlIiB3aWR0aD0iMTZweCIgaGVpZ2h0PSIxNnB4Ij4KPGc+Cgk8cGF0aCBkPSJNMjUyLjYzOSw5Ny4xNzVMMjAuNTQzLDUuMDY0QzUuNzU0LTAuODEtMy4wMTksNi45MjQsMC45NTcsMjIuMzMzbDU3Ljc1MiwyMjMuOTc1ICAgYzMuOTc2LDE1LjQwOSwxNy44NCwyMC42MTQsMzAuOTc1LDExLjYzNGw2MC4xNDUtNDEuMTU3bDQ1Ljc3LDM4Ljc5MWMxMi4xMzUsMTAuMjk2LDIxLjk3OSw1LjczOCwyMS45NzktMTAuMTc2di04My4xMDkgICBsNDAuMjIyLTM1LjQzQzI2OS43MzksMTE2LjMzNywyNjcuNDMzLDEwMy4wNDksMjUyLjYzOSw5Ny4xNzV6IE0xNTguMTk1LDE4OS4yNTNMMzIuMTE4LDQwLjY2M2wxNTguNSwxMTguODc2TDE1OC4xOTUsMTg5LjI1M3oiIGZpbGw9IiM3MzdmOGQiLz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8L3N2Zz4K)!important;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item .popout-menu-icon[style*="/assets/9a93097ab591379729c68f15a17b26af.svg"]{background-image:url(data:image/svg+xml;utf8;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pgo8IS0tIEdlbmVyYXRvcjogQWRvYmUgSWxsdXN0cmF0b3IgMTguMC4wLCBTVkcgRXhwb3J0IFBsdWctSW4gLiBTVkcgVmVyc2lvbjogNi4wMCBCdWlsZCAwKSAgLS0+CjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iMCAwIDMxMCAzMTAiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDMxMCAzMTA7IiB4bWw6c3BhY2U9InByZXNlcnZlIiB3aWR0aD0iMTZweCIgaGVpZ2h0PSIxNnB4Ij4KPHBhdGggZD0iTTMwMC41NjQsMTc5LjMxMUwyODIuNCwxNjguODI0YzAuNDg5LTQuNTQzLDAuNzQ3LTkuMTU0LDAuNzQ3LTEzLjgyNHMtMC4yNTgtOS4yODEtMC43NDctMTMuODI0bDE4LjE2NC0xMC40ODcgIGMzLjg4MS0yLjI0MSw2LjY1OC01Ljg2LDcuODE2LTEwLjE5MWMxLjE2LTQuMzMsMC41NjQtOC44NTQtMS42NzYtMTIuNzM1bC0zNC45NDMtNjAuNTI0Yy0yLjk5LTUuMTgtOC41NjQtOC4zOTYtMTQuNTUxLTguMzk2ICBjLTIuOTMsMC01LjgyNiwwLjc3OC04LjM3NywyLjI1MUwyMzAuNjE5LDUxLjYxYy03LjQwMi01LjQyOS0xNS40MDYtMTAuMDgzLTIzLjg5My0xMy44NDJWMTYuNzgzICBDMjA2LjcyNyw3LjUyOSwxOTkuMTk1LDAsMTg5Ljk0NSwwaC02OS44OTFjLTkuMjU0LDAtMTYuNzgxLDcuNTI5LTE2Ljc4MSwxNi43ODN2MjAuOTg1Yy04LjQ4NiwzLjc1OS0xNi40OSw4LjQxMy0yMy44OTQsMTMuODQyICBMNjEuMTY0LDQxLjA5NGMtMi41NTEtMS40NzMtNS40NDUtMi4yNS04LjM3NS0yLjI1Yy01Ljk4NiwwLTExLjU2MywzLjIxNS0xNC41NTMsOC4zOTVMMy4yOTUsMTA3Ljc2MiAgYy0yLjI0MiwzLjg4MS0yLjgzNiw4LjQwNi0xLjY3NCwxMi43MzZjMS4xNTYsNC4zMywzLjkzNSw3Ljk0OSw3LjgxNCwxMC4xOTFMMjcuNiwxNDEuMTc2Yy0wLjQ4OSw0LjU0My0wLjc0Nyw5LjE1NC0wLjc0NywxMy44MjQgIHMwLjI1OCw5LjI4MSwwLjc0NywxMy44MjRMOS40MzUsMTc5LjMxMWMtMy44NzksMi4yNDEtNi42NTgsNS44Ni03LjgxNCwxMC4xOTFjLTEuMTYyLDQuMzMtMC41NjgsOC44NTUsMS42NzQsMTIuNzM1bDM0Ljk0MSw2MC41MjQgIGMyLjk5LDUuMTgsOC41NjYsOC4zOTUsMTQuNTUzLDguMzk1YzIuOTMsMCw1LjgyNC0wLjc3Nyw4LjM3NS0yLjI1TDc5LjM4LDI1OC4zOWM3LjQwMyw1LjQyOSwxNS40MDcsMTAuMDgzLDIzLjg5NCwxMy44NDJ2MjAuOTg2ICBjMCw0LjQ4MiwxLjc0NCw4LjY5NSw0LjkxNCwxMS44NjZjMy4xNzQsMy4xNjksNy4zODUsNC45MTYsMTEuODY3LDQuOTE2aDY5Ljg5MWM5LjI1LDAsMTYuNzgxLTcuNTI5LDE2Ljc4MS0xNi43ODJ2LTIwLjk4NiAgYzguNDg2LTMuNzU5LDE2LjQ5LTguNDEzLDIzLjg5My0xMy44NDJsMTguMjE1LDEwLjUxN2MyLjU1MSwxLjQ3Myw1LjQ0NywyLjI1LDguMzc3LDIuMjVjNS45ODYsMCwxMS41NjEtMy4yMTUsMTQuNTUxLTguMzk1ICBsMzQuOTQzLTYwLjUyM2MyLjI0LTMuODgxLDIuODM2LTguNDA2LDEuNjc2LTEyLjczNkMzMDcuMjIzLDE4NS4xNzIsMzA0LjQ0NSwxODEuNTUzLDMwMC41NjQsMTc5LjMxMXogTTE1NSwyNDYuMTAxICBjLTE4LjIzLDAtMzUuMjA3LTUuMzU3LTQ5LjQ0OS0xNC41NzlsMzAuODAxLTMwLjgwNGM2LjQ0OSwyLjc3MiwxMy40NSw0LjI0LDIwLjY3Nyw0LjI0MWMwLjAwMiwwLDAuMDAzLDAsMC4wMDQsMCAgYzE0LjAxMSwwLDI3LjE3NS01LjQ2NiwzNy4wNjQtMTUuMzljMTMuNS0xMy41MzYsMTguNTQxLTMzLjM2MywxMy4xNTUtNTEuNzQzYy0wLjMxMy0xLjA2OS0xLjE2OC0xLjg5NC0yLjI0OC0yLjE2OSAgYy0xLjA3OC0wLjI3Ny0yLjIyNSwwLjA0LTMuMDExLDAuODI5bC0zMi45NywzMy4wNjljLTEuOTc5LTAuODA0LTYuOTYxLTMuNTQyLTE2LjE4Ni0xMi43MzYgIGMtOS4yMjYtOS4xOTctMTEuOTc2LTE0LjE3My0xMi43ODMtMTYuMTQ4bDMyLjk2Ni0zMy4wNjljMC43ODctMC43ODksMS4wOTgtMS45MzUsMC44Mi0zLjAxM2MtMC4yNzgtMS4wNzktMS4xMDUtMS45MzEtMi4xNzUtMi4yNDEgIGMtNC43NTEtMS4zNzgtOS42NzYtMi4wNzgtMTQuNjM3LTIuMDc4Yy0xNC4wMTYsMC0yNy4xODEsNS40NjQtMzcuMDY5LDE1LjM4NWMtOS44NzMsOS45MDMtMTUuMjk5LDIzLjA1Ny0xNS4yOCwzNy4wMzkgIGMwLjAxLDcuMjA0LDEuNDc2LDE0LjE4LDQuMjQsMjAuNjA0bC0zMC43MjIsMzAuNzI0QzY5LjE0NSwxODkuODY4LDYzLjg5NiwxNzMuMDQ3LDYzLjg5NiwxNTUgIGMwLTUwLjMxMyw0MC43ODctOTEuMTAyLDkxLjEwNC05MS4xMDJzOTEuMTAyLDQwLjc4OSw5MS4xMDIsOTEuMTAyUzIwNS4zMTYsMjQ2LjEwMSwxNTUsMjQ2LjEwMXoiIGZpbGw9IiM3MzdmOGQiLz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPC9zdmc+Cg==)!important;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item .popout-menu-icon[style*="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGQ9Ik0wIDBoMTh2MThIMHoiLz4KICAgIDxnIGZpbGw9IiM3MzdGOEQiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIuMjUgMS41KSI+CiAgICAgIDxwYXRoIGQ9Ik02Ljc2NzcyMTAzLjc1SDEuNDk2MzE2OTdDLjY2OTQ2NzEuNzUgMCAxLjQxOTkyMzkzIDAgMi4yNDYzMTY5N1YxMi43NTM2ODNDMCAxMy41ODA1MzI5LjY2OTkyMzkzIDE0LjI1IDEuNDk2MzE2OTcgMTQuMjVIMTIuMDAzNjgzYy44MjY4NDk5IDAgMS40OTYzMTctLjY2OTkyMzkgMS40OTYzMTctMS40OTYzMTdWNy40ODIwODM2MmMtLjQ1NDM1NTYuMjkxMjMwODgtLjk1OTk3NTguNTA5MTQ4OS0xLjUuNjM3MDU3NDRWMTIuNzVIMS41VjIuMjVoNC42MzA3Mzk5MmMuMTI3ODkxMzYtLjU0MDI4ODcuMzQ1ODI2Ny0xLjA0NTg0MjQuNjM2OTgxMS0xLjV6Ii8+CiAgICAgIDxyZWN0IHdpZHRoPSI2IiBoZWlnaHQ9IjYiIHg9IjguMjUiIHJ4PSIzIi8+CiAgICA8L2c+CiAgPC9nPgo8L3N2Zz4="]{background-image:url(data:image/svg+xml;utf8;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pgo8IS0tIEdlbmVyYXRvcjogQWRvYmUgSWxsdXN0cmF0b3IgMTkuMC4wLCBTVkcgRXhwb3J0IFBsdWctSW4gLiBTVkcgVmVyc2lvbjogNi4wMCBCdWlsZCAwKSAgLS0+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iMCAwIDQ4OS42IDQ4OS42IiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA0ODkuNiA0ODkuNjsiIHhtbDpzcGFjZT0icHJlc2VydmUiIHdpZHRoPSIxNnB4IiBoZWlnaHQ9IjE2cHgiPgo8Zz4KCTxnPgoJCTxnPgoJCQk8cGF0aCBkPSJNMjAwLjksMzk0YzEwOC44LDAsMTk3LTg4LjIsMTk3LTE5N1MzMDkuNywwLDIwMC45LDBTMy45LDg4LjIsMy45LDE5N1M5Mi4xLDM5NCwyMDAuOSwzOTR6IE0yNzksMTk3ICAgICBjMCw0My4xLTM1LDc4LjEtNzguMSw3OC4xcy03OC4xLTM1LTc4LjEtNzguMXMzNS03OC4xLDc4LjEtNzguMUMyNDQsMTE4LjksMjc5LDE1My45LDI3OSwxOTd6IE00My41LDIwNi43ICAgICBjLTUuNCwwLTEwLjEtNC4zLTEwLjEtMTAuMWMwLTkyLjEsNzUtMTY3LjUsMTY3LjUtMTY3LjVjNS40LDAsMTAuMSw0LjMsMTAuMSwxMC4xcy00LjMsMTAuMS0xMC4xLDEwLjEgICAgIGMtODEuMiwwLTE0Ny4zLDY2LjEtMTQ3LjMsMTQ3LjNDNTMuMiwyMDIuNCw0OSwyMDYuNyw0My41LDIwNi43eiIgZmlsbD0iIzczN2Y4ZCIvPgoJCQk8cGF0aCBkPSJNNDg1LjcsMTU4LjVjMC0yMC4yLTE2LjMtMzYuOS0zNi45LTM2LjljLTIwLjIsMC0zNi45LDE2LjMtMzYuOSwzNi45YzAsMjAuMiwxNi4zLDM2LjksMzYuOSwzNi45YzAuOCwwLDEuNiwwLDIuMywwICAgICBDNDYyLDQwMC42LDM4NSw0NDQuMSwzNjkuOSw0NTEuMXYtMTcuNWgtMzM4djU2SDM3MHYtMTguM2MwLjgsMCwxMTUuOC0yMy4yLDEwMS0yODMuM0M0NzkuOSwxODEuNSw0ODUuNywxNzAuNiw0ODUuNywxNTguNXoiIGZpbGw9IiM3MzdmOGQiLz4KCQk8L2c+Cgk8L2c+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPC9zdmc+Cg==)!important;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item .popout-menu-icon[style*="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGQ9Ik0wIDBoMTh2MThIMHoiLz4KICAgIDxwYXRoIGZpbGw9IiM3MzdGOEQiIGQ9Ik05IDloNS4yNWMtLjM5NzUgMy4wODI1LTIuNDYgNS44MzUtNS4yNSA2LjY5VjlIMy43NVY0LjcyNUw5IDIuMzkyNVY5em0wIDBIMy43NWMuMzk3NSAzLjA4MjUgMi40NiA1LjgzNSA1LjI1IDYuNjlWOWg1LjI1VjQuNzI1TDkgMi4zOTI1Vjl6TTkgLjc1bC02Ljc1IDN2NC41YzAgNC4xNjI1IDIuODggOC4wNDc1IDYuNzUgOSAzLjg3LS45NTI1IDYuNzUtNC44Mzc1IDYuNzUtOXYtNC41TDkgLjc1eiIvPgogIDwvZz4KPC9zdmc+"]{background-image:url(data:image/svg+xml;utf8;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pgo8IS0tIEdlbmVyYXRvcjogQWRvYmUgSWxsdXN0cmF0b3IgMTkuMC4wLCBTVkcgRXhwb3J0IFBsdWctSW4gLiBTVkcgVmVyc2lvbjogNi4wMCBCdWlsZCAwKSAgLS0+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iMCAwIDYwIDYwIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA2MCA2MDsiIHhtbDpzcGFjZT0icHJlc2VydmUiIHdpZHRoPSIxNnB4IiBoZWlnaHQ9IjE2cHgiPgo8cGF0aCBkPSJNMzAsMEMxMy40NTgsMCwwLDEzLjQ1OCwwLDMwczEzLjQ1OCwzMCwzMCwzMHMzMC0xMy40NTgsMzAtMzBTNDYuNTQyLDAsMzAsMHogTTM4LjE1Miw0OEgyMS44NDhsMi42NzUtMTguODYyICBDMjIuMzA2LDI3LjQzOCwyMSwyNC44MTQsMjEsMjJjMC00Ljk2Myw0LjAzOC05LDktOXM5LDQuMDM3LDksOWMwLDIuODE0LTEuMzA2LDUuNDM4LTMuNTIzLDcuMTM4TDM4LjE1Miw0OHoiIGZpbGw9IiM3MzdmOGQiLz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPC9zdmc+Cg==)!important;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item .popout-menu-icon[style*="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCI+CiAgPHBhdGggZmlsbD0iIzczN0Y4RCIgZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNMyAxNHYtMi41bDcuODgtNy44NWMuMTktLjIuNTEtLjIuNzEgMGwxLjc2IDEuNzZjLjIuMi4yLjUxIDAgLjcxTDUuNDcgMTRIM3ptMTIgMEg3LjVsMi0ySDE1djJ6Ii8+Cjwvc3ZnPg=="]{background-image:url(data:image/svg+xml;utf8;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pgo8IS0tIEdlbmVyYXRvcjogQWRvYmUgSWxsdXN0cmF0b3IgMTguMC4wLCBTVkcgRXhwb3J0IFBsdWctSW4gLiBTVkcgVmVyc2lvbjogNi4wMCBCdWlsZCAwKSAgLS0+CjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iMCAwIDI5NyAyOTciIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDI5NyAyOTc7IiB4bWw6c3BhY2U9InByZXNlcnZlIiB3aWR0aD0iMTZweCIgaGVpZ2h0PSIxNnB4Ij4KPGc+Cgk8cGF0aCBkPSJNMjE4Ljg4OCwyMDguOTM5Yy0wLjI2NS0yLjMwMSwwLjQ4LTQuNjA0LDIuMDQ0LTYuMzE0bDExLjIzNi0xMi4yODVsLTE2LjIzNy0zLjI5NGMtMi4yODEtMC40NjItNC4yNDgtMS44OTYtNS4zODctMy45MjcgICBsLTguMDk2LTE0LjQzNmwtOC4wOTIsMTQuNDM1Yy0xLjEzOSwyLjAzMS0zLjEwNiwzLjQ2NS01LjM4OCwzLjkyOGwtMTYuMjM5LDMuMjk0bDExLjIzNCwxMi4yODYgICBjMS41NjMsMS43MDksMi4zMDksNC4wMTEsMi4wNDQsNi4zMTFsLTEuODk4LDE2LjUyNGwxNC45OTMtNi44OThjMS4wNjEtMC40ODgsMi4yMDItMC43MzIsMy4zNDQtMC43MzJzMi4yODIsMC4yNDQsMy4zNDMsMC43MzIgICBsMTUsNi44OTlMMjE4Ljg4OCwyMDguOTM5eiIgZmlsbD0iIzczN2Y4ZCIvPgoJPHBhdGggZD0iTTkwLjc0OSwxMDloMTE1LjVjNS41MjMsMCwxMC00LjQ3OCwxMC0xMFY0OS41YzAtNS41MjItNC40NzctMTAtMTAtMTBoLTE1LjkyNGMtNC41MTktMTguOTA0LTIxLjU1OC0zMy00MS44MjYtMzMgICBjLTIwLjI2OCwwLTM3LjMwOCwxNC4wOTYtNDEuODI2LDMzSDkwLjc0OWMtNS41MjIsMC0xMCw0LjQ3OC0xMCwxMFY5OUM4MC43NDksMTA0LjUyMiw4NS4yMjcsMTA5LDkwLjc0OSwxMDl6IE0xNDguNDk5LDQxLjQxNiAgIGM0LjQ2NSwwLDguMDgzLDMuNjE5LDguMDgzLDguMDg0cy0zLjYxOCw4LjA4NC04LjA4Myw4LjA4NGMtNC40NjUsMC04LjA4My0zLjYxOS04LjA4My04LjA4NFMxNDQuMDM0LDQxLjQxNiwxNDguNDk5LDQxLjQxNnoiIGZpbGw9IiM3MzdmOGQiLz4KCTxwYXRoIGQ9Ik0yNjYsNzIuNWgtMzUuNzUxVjk5YzAsMTMuMjMzLTEwLjc2NywyNC0yNCwyNGgtMTE1LjVjLTEzLjIzMywwLTI0LTEwLjc2Ny0yNC0yNFY3Mi41SDMxYy0xNy4wOTQsMC0zMSwxMy45MDYtMzEsMzF2MTU2ICAgYzAsMTcuMDk0LDEzLjkwNiwzMSwzMSwzMWgyMzVjMTcuMDk0LDAsMzEtMTMuOTA2LDMxLTMxdi0xNTZDMjk3LDg2LjQwNiwyODMuMDk0LDcyLjUsMjY2LDcyLjV6IE0xMTUuNDk5LDI0Mi4wMDhoLTY2ICAgYy00LjQxOCwwLTgtMy41ODItOC04czMuNTgyLTgsOC04aDY2YzQuNDE4LDAsOCwzLjU4Miw4LDhTMTE5LjkxNywyNDIuMDA4LDExNS40OTksMjQyLjAwOHogTTExNS40OTksMjA5LjAwOGgtNjYgICBjLTQuNDE4LDAtOC0zLjU4Mi04LThzMy41ODItOCw4LThoNjZjNC40MTgsMCw4LDMuNTgyLDgsOFMxMTkuOTE3LDIwOS4wMDgsMTE1LjQ5OSwyMDkuMDA4eiBNMTE1LjQ5OSwxNzYuMDA4aC02NiAgIGMtNC40MTgsMC04LTMuNTgyLTgtOHMzLjU4Mi04LDgtOGg2NmM0LjQxOCwwLDgsMy41ODIsOCw4UzExOS45MTcsMTc2LjAwOCwxMTUuNDk5LDE3Ni4wMDh6IE0yNDcuNjU1LDE5Ny41NTUgICBjLTAuMTMsMC0wLjI1Ni0wLjAxNi0wLjM4NS0wLjAybC0xMi4wNzEsMTMuMTk3bDIuMjc2LDE5Ljc4N2MzLjY0NCwxLjk4Miw2LjEyNiw1Ljg1OCw2LjEyNiwxMC4zMDkgICBjMCw2LjQ1OS01LjIyNiwxMS43MTQtMTEuNjQ4LDExLjcxNGMtNS43MDQsMC0xMC40NTQtNC4xNDgtMTEuNDQ4LTkuNTk5bC0xOC4wNTktOC4zMDdsLTE4LjA1Myw4LjMwNyAgIGMtMC45OTQsNS40NTEtNS43NDMsOS41OTktMTEuNDQ3LDkuNTk5Yy02LjQyNSwwLTExLjY1MS01LjI1NS0xMS42NTEtMTEuNzE0YzAtNC40NSwyLjQ4Mi04LjMyNyw2LjEyOC0xMC4zMDlsMi4yNzMtMTkuNzg3ICAgbC0xMS4zOTItMTIuNDU4Yy0wLjEyOCwwLjAwNC0wLjI1NCwwLjAyLTAuMzgzLDAuMDJjLTYuNDIzLDAtMTEuNjQ3LTUuMjU0LTExLjY0Ny0xMS43MTJjMC02LjQ1OSw1LjIyNS0xMS43MTQsMTEuNjQ3LTExLjcxNCAgIGMxLjc4MywwLDMuNDY3LDAuNDE3LDQuOTgsMS4xNDFsMTkuMjkyLTMuOTE0bDkuNjIzLTE3LjE2NmMtMC42NDctMS40NTYtMS4wMTUtMy4wNjMtMS4wMTUtNC43NTkgICBjMC02LjQ1OCw1LjIyNC0xMS43MTIsMTEuNjQ1LTExLjcxMmM2LjQyNSwwLDExLjY1MSw1LjI1NCwxMS42NTEsMTEuNzEyYzAsMS42OTctMC4zNjgsMy4zMDctMS4wMTgsNC43NjRsOS42MjUsMTcuMTYxICAgbDE4LjgwNCwzLjgxNGMxLjc4Ni0xLjEyMiwzLjg4OS0xLjc4Miw2LjE0Ni0xLjc4MmM2LjQyMywwLDExLjY0OCw1LjI1NSwxMS42NDgsMTEuNzE1ICAgQzI1OS4zMDQsMTkyLjMwMSwyNTQuMDc4LDE5Ny41NTUsMjQ3LjY1NSwxOTcuNTU1eiIgZmlsbD0iIzczN2Y4ZCIvPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+CjxnPgo8L2c+Cjwvc3ZnPgo=)!important;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item.leave .popout-menu-icon{background-image:url(data:image/svg+xml;utf8;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pgo8IS0tIEdlbmVyYXRvcjogQWRvYmUgSWxsdXN0cmF0b3IgMTkuMC4wLCBTVkcgRXhwb3J0IFBsdWctSW4gLiBTVkcgVmVyc2lvbjogNi4wMCBCdWlsZCAwKSAgLS0+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiBpZD0iTGF5ZXJfMSIgeD0iMHB4IiB5PSIwcHgiIHZpZXdCb3g9IjAgMCA1MTIgNTEyIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1MTIgNTEyOyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSIgd2lkdGg9IjE2cHgiIGhlaWdodD0iMTZweCI+CjxnPgoJPGc+CgkJPHBhdGggZD0iTTQxOC4xNzcsMTc5LjJjLTkuNiwwLTE4LjQ2NiwzLjE4My0yNS42LDguNTV2LTguNTVjMC0yMy41MjYtMTkuMTQtNDIuNjY3LTQyLjY2Ny00Mi42NjdjLTkuNiwwLTE4LjQ2NiwzLjE4My0yNS42LDguNTUgICAgVjQyLjY2N0MzMjQuMzEsMTkuMTQsMzA1LjE3LDAsMjgxLjY0NCwwYy0yMy41MjYsMC00Mi42NjcsMTkuMTQtNDIuNjY3LDQyLjY2N3Y4NS4zNWMtNy4xMzQtNS4zNjctMTYtOC41NS0yNS42LTguNTUgICAgYy0yMy41MjYsMC00Mi42NjcsMTkuMTQtNDIuNjY3LDQyLjY2N3Y3NC44NjNjLTE5LjAyOS0zMi4zODQtNjIuNjQzLTQ5LjI4OS05NS41MTQtMzYuOTMyYy0zLjY2MSwxLjM3NC03LjIzNiwzLjI3Ny0xMS42MDUsNi4xNTMgICAgYy0xMi43OTIsOC40ODItMTIuNDUsMTguOTEtMTIuMjExLDIyLjY5OWMtMC44MjgsNC42MzQsMC4xMjgsNS43MzQsMTEuNzg1LDE5LjIwOGMxNS4wNTMsMTcuMzkxLDQ2LjM3OSw1My41NzIsNjYuMTQyLDg5LjE0OCAgICBjMC43MzQsMS4xODYsMTMuMTU4LDIxLjI2NSwyOS42NzksNDIuODJjOC41MDgsNS4wMDksMTguNzU2LDEwLjcyNiwyNy44ODcsMTUuODIxYzE4LjQ0OSwxMC4yNzQsMzQuMzcyLDE5LjE1Nyw0MC40NjUsMjQuMTc1ICAgIGMzLjY0NCwyLjk4Nyw0LjE1Niw4LjM2MywxLjE1MiwxMi4wMDZjLTEuNjgxLDIuMDQ4LTQuMTIyLDMuMTA2LTYuNTg4LDMuMTA2Yy0xLjkxMSwwLTMuODIzLTAuNjQtNS40MTktMS45NTQgICAgYy00LjgzLTMuOTU5LTIxLjkyMi0xMy41MTctMzcuMjM5LTIyLjA1djE1LjU1NmMwLDQ3LjAxLDM4LjIzOCw4NS4yNDgsODUuMjQ4LDg1LjI0OGg4NS40MTkgICAgYzM2Ljk4NCwwLDc1LjExOS0zMC42OTQsODMuMjc3LTY3LjAyMWMwLjk5OC00LjQ4OSwyLjE4NS04LjM5NywzLjQ2NS0xMS43ODVjLTE3Ljg4Niw1Ljk5LTMzLjA1OCwxMC4xOC0zMy4zOTksMTAuMjY2ICAgIGMtMC43MTcsMC4xODgtMS40NDIsMC4yNzMtMi4xNSwwLjI3M2MtMy43ODksMC03LjI1My0yLjU0My04LjI1Mi02LjM5MWMtMS4xNzgtNC41NTcsMS41NTMtOS4yMTYsNi4xMTgtMTAuNDAyICAgIGMxNC4wMDMtMy42MzUsMzQuMjc4LTEwLjI0LDUxLjA4OS0xNi42NjZjNS45MDUtMTIuMzE0LDEwLjc4Ni0yOS45ODYsMTAuNzg2LTUxLjg3NFYyMjEuODY3ICAgIEM0NjAuODQ0LDE5OC4zNCw0NDEuNzAzLDE3OS4yLDQxOC4xNzcsMTc5LjJ6IiBmaWxsPSIjNzM3ZjhkIi8+Cgk8L2c+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPC9zdmc+Cg==)!important;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item .popout-menu-item-label{color:rgba(225, 225, 225, 0.8)!important;width:calc(100% + 40px);top:48px;right:0;left:-25px;margin:auto;padding:5px;border-radius:5px;text-align:center;text-overflow:inherit;white-space:inherit;visibility:hidden;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:first-child .popout-menu-item-label{left:-10px;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:last-child .popout-menu-item-label{left:-26px;}

@keyframes server-titles{0%{transform:scale(0);}

100%{transform:none;}

}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:hover .popout-menu-item-label{visibility:visible;animation:server-titles 200ms cubic-bezier(0.2, 0.6, 0.5, 1.1);}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-separator{display:none;}

.channels-wrap .guild-header + .channel-notices:not(:empty),.channels-wrap .guild-header + .channel-notices:empty + .scroller-wrap{transition:300ms cubic-bezier(0, 1, 0.5, 1)!important;}

.channels-wrap .guild-header.popout-open + .channel-notices:not(:empty){margin-top:60px!important;}

.channels-wrap .guild-header.popout-open + .channel-notices:empty + .scroller-wrap .guild-channels{margin-top:40px!important;}

@keyframes StatusSlide{0%{bottom:0px;}

100%{bottom:70px;}

}

.avatar-uploader .avatar-uploader-inner,.avatar-xxlarge{border-radius:4px;}

.premium-settings .premium-feature .premium-feature-title {font-weight: 800;color: var(--main-color);}

.premium-settings .premium-feature .premium-feature-description {color: #b3b3b3;}

.premium-settings .premium-header.splash { border-bottom: 2px solid var(--main-color);}

.premium-settings .premium-header .premium-options button.btn-clear {background-color: var(--main-color);color: rgba(255, 255, 255, 0.41);transition: .2s background-color linear;}

.premium-settings .premium-header .premium-options button.btn-clear strong {color: #fff;}

.premium-settings .premium-header .premium-options button.btn-clear:hover {background-color: var(--hover-color);}

.premium-settings .premium-header .intro-subtitle {color: #dadada;}

.user-settings-modal .account-warning {border: 1px solid #b82d49;border-radius: 3px;background: #b82d49;color: #fff;}

.copybutton {background-color: var(--main-color) !important;color: #fff !important;border: 0px transparent solid !important;border-radius: 3px !important;transition: .01s transform linear !important;}

.copybutton:active {transform: scale(0.96);}

.replyer {top: 1px !important;background-color: #121213 !important;padding: 6px 5px 0px 5px !important;}

#settings-roles .roles li {color: #c2c2c2;padding: 0 21px 0 24px;}

#autocomplete-popout .section {color: #c8c8c8;}

.channel-textarea-emoji{-webkit-transition: all 100ms ease;transition: all 100ms ease;width: 80px;margin: 0;height: 100%;}

.message-group .edit-message .channel-textarea{margin-top: 4px;box-shadow: 0 0 6px -1px #000;}

.message-group .edit-message .channel-textarea-inner, .message-group .edit-message .channel-textarea{border-radius: 3px!important;opacity: 1!important;}

.message-group .edit-message .channel-textarea-inner, .message-group .edit-message .channel-textarea-inner textarea{padding: 6px 0px!important;}

.upload-modal .inner .comment .channel-textarea .channel-textarea-inner {padding: 0 0!important;border-radius: 3px!important;background: rgba(0,0,0,0.3) !important;border-left: 0px solid transparent !important;border-right: 0px solid transparent !important;}

.upload-modal .inner .comment .channel-textarea .channel-textarea-inner textarea {padding: 5px 0px !important;}

.upload-modal .inner .comment .channel-textarea .channel-textarea-inner .channel-textarea-emoji {margin: -7px -5px -12px 10px;height: 41px;width: 45px;}

.channel-textarea-autocomplete-inner ul.images li.active {padding-left: 0;border-color: var(--main-color);}

.channel-textarea-autocomplete-inner ul.images li {border: 3px solid #3e3e3e;border-radius: 3px;}
 
div.control-group .shortcut-recorder input[type=text] {line-height: 41px;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item.leave:hover {cursor: url("https://betterdocs.net/classic/assets/middlefinger.cur"), auto !important;}

.theme-dark .channel-textarea-autocomplete-inner ul.images li{transition:all 100ms cubic-bezier(0, 0, 0, 1);animation:images-search 1000ms cubic-bezier(.46, .16, 0, 1.31);animation-fill-mode:forwards;opacity:0;}

@keyframes images-search{from{opacity:0;transform:scale(0.3) translate3d(0,0,0);}

 to{opacity:1;transform:scale(1) translate3d(0,0,0);}

}

.chat form .channel-textarea.has-results .channel-textarea-autocomplete-inner ul.images li:nth-of-type(1){animation-delay: 100ms;}
.chat form .channel-textarea.has-results .channel-textarea-autocomplete-inner ul.images li:nth-of-type(2){animation-delay: 200ms;}
.chat form .channel-textarea.has-results .channel-textarea-autocomplete-inner ul.images li:nth-of-type(3){animation-delay: 300ms;}
.chat form .channel-textarea.has-results .channel-textarea-autocomplete-inner ul.images li:nth-of-type(4){animation-delay: 400ms;}
.chat form .channel-textarea.has-results .channel-textarea-autocomplete-inner ul.images li:nth-of-type(5){animation-delay: 500ms;}
.chat form .channel-textarea.has-results .channel-textarea-autocomplete-inner ul.images li:nth-of-type(6){animation-delay: 600ms;}
.chat form .channel-textarea.has-results .channel-textarea-autocomplete-inner ul.images li:nth-of-type(7){animation-delay: 700ms;}
.chat form .channel-textarea.has-results .channel-textarea-autocomplete-inner ul.images li:nth-of-type(8){animation-delay: 800ms;}
.chat form .channel-textarea.has-results .channel-textarea-autocomplete-inner ul.images li:nth-of-type(9){animation-delay: 900ms;}

.emoji-picker .header { border-bottom: 2px solid var(--main-color);}

.message-group .avatar-large[style*="172218388880293888"]:hover, .channel-members .member .avatar-small[style*="172218388880293888"]:hover {cursor: url("https://betterdocs.net/classic/assets/penis.cur"), auto !important;}

.quote-msg {box-shadow: 0px 0px 6px -2px #000;}

.citar-btn {order: 5;top: 1px !important;background-color: #121213 !important;padding: 5px 5px 0px 5px !important;}

.citar-btn.quoting {background: #43b581 !important;}

.popout.popout-bottom {margin-top: 0px;}

.guild-channels header {margin: 5px 0 0;}

.invite-button.accepted{background-color:#43b581 !important;border-color:#43b581 !important;}

.invite-button.expired{background-color:#f04747 !important;border-color:#f04747 !important;}

.invite-button.join{background-color:#747f8d !important;border-color:#747f8d !important;}

.invite-button.resolving{background-color: orange !important;border-color: orange !important;}

.invite-button-icon.join{background-color:#747f8d;border-color:#747f8d;}

.invite-button.join:hover .invite-button-icon{border-color:#747f8d;}

.invite-button-icon:before{border-color:transparent;opacity:1;}

.invite-button-icon.join:before{content:"";background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTk0NyA1MjkgMjQgMjQiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTk0NyA1MjkgMjQgMjQ7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDojRkZGRkZGO308L3N0eWxlPjxnPjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTM0LjEsNTQzLjZoLTEuOHYtMC45YzAtMC41LDAuMS0xLDAuMy0xLjRjMC4yLTAuNCwwLjYtMC45LDEuMi0xLjRjMC42LTAuNSwxLTEsMS4yLTEuM2MwLjItMC4zLDAuMy0wLjcsMC4zLTEuMWMwLTAuNi0wLjItMS4xLTAuNi0xLjRjLTAuNC0wLjMtMC45LTAuNS0xLjUtMC41Yy0xLjEsMC0xLjgsMC42LTIuMiwxLjhsLTEuNi0wLjdjMC4zLTAuOCwwLjgtMS41LDEuNS0yYzAuNy0wLjUsMS41LTAuOCwyLjQtMC44YzEuMSwwLDIsMC4zLDIuOCwxYzAuNywwLjcsMS4xLDEuNSwxLjEsMi42YzAsMC41LTAuMSwxLTAuNCwxLjVjLTAuMywwLjUtMC44LDEuMS0xLjUsMS43Yy0wLjcsMC43LTEuMSwxLjMtMS4xLDJWNTQzLjZ6IE0tOTMzLjgsNTQ2LjZjMCwwLjQtMC4xLDAuNi0wLjQsMC45Yy0wLjIsMC4yLTAuNSwwLjQtMC45LDAuNGMtMC4zLDAtMC42LTAuMS0wLjktMC40Yy0wLjItMC4yLTAuNC0wLjUtMC40LTAuOWMwLTAuNCwwLjEtMC43LDAuNC0wLjljMC4yLTAuMiwwLjUtMC40LDAuOS0wLjRjMC40LDAsMC43LDAuMSwwLjksMC40Qy05MzMuOSw1NDYtOTMzLjgsNTQ2LjMtOTMzLjgsNTQ2LjZ6Ii8+PC9nPjwvc3ZnPg==) !important;background-repeat:no-repeat;background-position:50%;height:30px;transform:rotate(0deg);background-size:50px;opacity:1;width:14px;left:17px;top:10px;}

.invite-button.expired:hover{cursor:not-allowed;}

.invite-button .invite-button-header{color:#fff !important; line-height: normal;}

.invite-button .invite-button-body{color:rgba(255,255,255,0.65) !important;}

.invite-button-icon.accepted, .invite-button-icon.resolving, .invite-button-icon.expired, .invite-button-icon.join{transform:scale(0.94);transition:.2s transform linear, .2s box-shadow linear !important;}

.invite-button-icon.accepted{box-shadow:0 0 8px -2px #095331;}

.invite-button-icon.expired{box-shadow:0 0 8px -2px #8d0d0d;}

.invite-button-icon.join{box-shadow:0 0 8px -2px #4f545c;}

.invite-button-icon.resolving{box-shadow:0 0 8px -2px #966203;}

.invite-button:hover .invite-button-icon.accepted{box-shadow:0 2px 8px -1px #095331;}

.invite-button:hover .invite-button-icon.expired{box-shadow:0 2px 8px -1px #8d0d0d;}

.invite-button:hover .invite-button-icon.join{box-shadow:0 2px 8px -1px #4f545c;}

.invite-button:hover .invite-button-icon.resolving{box-shadow:0 2px 8px -1px #966203;}

.invite-button:hover .invite-button-icon.accepted, .invite-button:hover .invite-button-icon.resolving, .invite-button:hover .invite-button-icon.expired, .invite-button:hover .invite-button-icon.join{transform:scale(1);}

.premium-settings .premium-header .premium-logo{margin: 36px 0 10px 40px;text-indent: 0px;background: 0;color: var(--main-color);font-size: 65px;font-weight: 600;font-style: italic;line-height: 53px;}

.premium-settings .premium-header .premium-splash-wumpus {right: 75px;}

#settings-roles .roles li.sorting:after {border: 2px solid var(--hover-color);content: " ";}

.avatar-small .status{border-radius: 3px;}

.channel-members .avatar-small{border-radius: 0px;}

.status-typing{border-radius: 7px !important;}

.spinner-chasing-dots .spinner-item {background-color: var(--main-color) !important;}

.embed-video-actions-inner{padding:0!important;width:100%;height:100%;border-radius:3px!important;background:rgba(0, 0, 0, .6)!important;-webkit-transition:all 300ms cubic-bezier(.23, .01, 0, 1);transition:all 300ms cubic-bezier(.23, .01, 0, 1);}

.embed-video-play:first-of-type{width:100%!important;height:100%!important;background-image:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTIgMkM2LjQ4IDIgMiA2LjQ4IDIgMTJzNC40OCAxMCAxMCAxMCAxMC00LjQ4IDEwLTEwUzE3LjUyIDIgMTIgMnptLTIgMTQuNXYtOWw2IDQuNS02IDQuNXoiLz48L3N2Zz4=)!important;background-position:50%!important;background-repeat:no-repeat!important;background-size:20%!important;-webkit-transition:all 300ms cubic-bezier(.23, .01, 0, 1);transition:all 300ms cubic-bezier(.23, .01, 0, 1);}

.embed-video-actions-inner:hover{background:rgba(0, 0, 0, .7)!important}

.embed-video-play+.embed-video-popout{position:absolute;right:10px;bottom:10px;background-image:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTkgMTlINVY1aDdWM0g1Yy0xLjExIDAtMiAuOS0yIDJ2MTRjMCAxLjEuODkgMiAyIDJoMTRjMS4xIDAgMi0uOSAyLTJ2LTdoLTJ2N3pNMTQgM3YyaDMuNTlsLTkuODMgOS44MyAxLjQxIDEuNDFMMTkgNi40MVYxMGgyVjNoLTd6Ii8+PC9zdmc+)!important;background-size:100%!important;height:25px!important;width:25px!important;}

.embed-thumbnail-video{-webkit-transition:all 300ms cubic-bezier(.23, .01, 0, 1);transition:all 300ms cubic-bezier(.23, .01, 0, 1);}

.change-log .embed .embed-video-actions{padding-bottom:4px}

.detTubeButton{position:absolute;right:40px;bottom:12px;background-image:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMyAxM2gydi0ySDN2MnptMCA0aDJ2LTJIM3Yyem0yIDR2LTJIM2MwIDEuMS44OSAyIDIgMnpNMyA5aDJWN0gzdjJ6bTEyIDEyaDJ2LTJoLTJ2MnptNC0xOEg5Yy0xLjExIDAtMiAuOS0yIDJ2MTBjMCAxLjEuODkgMiAyIDJoMTBjMS4xIDAgMi0uOSAyLTJWNWMwLTEuMS0uOS0yLTItMnptMCAxMkg5VjVoMTB2MTB6bS04IDZoMnYtMmgtMnYyem0tNCAwaDJ2LTJIN3YyeiIvPjwvc3ZnPg==)!important;background-size:100%!important;height:24px!important;width:25px!important;}

.search-popout .date-picker{border-top: 0px solid transparent;}

.search-popout .date-picker, .search-popout .date-picker .date-picker-hint{background-color: #141416;}

.scroller.messages{overflow-y: scroll;}

.channel-notices .channel-notice .message .btn{background-color: var(--main-color);}

.quickswitcher.dark{background-color:#19191b;}

.quickswitcher.dark .scroller-wrap:before{background-image:-webkit-linear-gradient(bottom,transparent,#19191b 60%,#19191b);background-image:linear-gradient(0deg,transparent,#19191b 60%,#19191b);}

.quickswitcher.dark .big-input{background-color:#19191b;color:#fff;box-shadow:0 0 0 0;border:2px solid #121213;}

.quickswitcher.dark .result.selected{background-color:#121213;}

.quickswitcher.dark .result .result-action{color:rgba(255, 255, 255, 0.55);box-shadow:-4px 0 4px #121213;background-color:#121213;}

.quickswitcher.dark .tips{border-color:#121213;}

.quickswitcher.dark .scroller-wrap .scroller::-webkit-scrollbar-track-piece{background-color:#111113!important;}

.quickswitcher.dark .scroller-wrap .scroller::-webkit-scrollbar-thumb{background-color:var(--main-color)!important;}

.quickswitcher .tips .misc-controls .keybind-shortcut:last-of-type:before{display:none;}

.keybind-shortcut span:active{box-shadow: inset 0 -3px 0 var(--main-color) !important;}

.quickswitcher .result .section-title{color: var(--main-color);font-weight: 800;font-size: 14px;}

.guild-settings-modal-members .guild-settings-modal-members-footer a:hover, .user-settings-modal .link-button:hover{color:var(--hover-color);}

.guild-settings-modal-members .guild-settings-modal-members-footer a, .user-settings-modal .link-button{color:var(--main-color);}

.btn-help:hover{background-color:var(--main-color);}

img[src="/assets/4fd1841c200d08f011c59d4f029d8258.png"]{content:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTQ5MSA0OTMgMTYgMTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTQ5MSA0OTMgMTYgMTY7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDojRkZGRkZGO30uc3Qxe2ZpbGw6bm9uZTt9PC9zdHlsZT48cGF0aCBjbGFzcz0ic3QwIiBkPSJNLTQ4Myw1MDQuNGMtMiwwLTIuOS0xLTIuOS0xLjdjMC0wLjQsMC4zLTAuNiwwLjctMC42YzAuOCwwLDAuNiwxLjIsMi4yLDEuMmMwLjgsMCwxLjMtMC40LDEuMy0wLjljMC0wLjMtMC4xLTAuNi0wLjctMC43bC0xLjgtMC40Yy0xLjQtMC40LTEuNy0xLjEtMS43LTEuOGMwLTEuNSwxLjQtMi4xLDIuNy0yLjFjMS4yLDAsMi42LDAuNywyLjYsMS42YzAsMC40LTAuMywwLjYtMC43LDAuNmMtMC43LDAtMC42LTEtMi0xYy0wLjcsMC0xLjEsMC4zLTEuMSwwLjhjMCwwLjUsMC42LDAuNiwxLjEsMC43bDEuMywwLjNjMS40LDAuMywxLjgsMS4yLDEuOCwxLjlDLTQ4MC4yLDUwMy41LTQ4MS4xLDUwNC40LTQ4Myw1MDQuNCBNLTQ3Ny41LDUwMkwtNDc3LjUsNTAyTC00NzcuNSw1MDJDLTQ3Ny42LDUwMS45LTQ3Ny42LDUwMi00NzcuNSw1MDJjMC4xLTAuMywwLjEtMC43LDAuMS0xYzAtMC44LTAuMS0xLjUtMC40LTIuMmMtMC4zLTAuNy0wLjctMS4zLTEuMi0xLjhjLTAuNS0wLjUtMS4xLTAuOS0xLjgtMS4yYy0wLjctMC4zLTEuNC0wLjQtMi4yLTAuNGMtMC40LDAtMC43LDAtMS4xLDAuMWgwbDAuMSwwbC0wLjEsMGwwLjEsMGMtMC41LTAuMy0xLTAuNC0xLjUtMC40Yy0wLjksMC0xLjcsMC4zLTIuMywxcy0xLDEuNC0xLDIuM2MwLDAuNiwwLjEsMS4xLDAuNCwxLjZsMC0wLjFsMCwwLjFjMCwwLDAsMCwwLTAuMWMtMC4xLDAuMy0wLjEsMC42LTAuMSwxYzAsMC44LDAuMSwxLjUsMC40LDIuMmMwLjMsMC43LDAuNywxLjMsMS4yLDEuOGMwLjUsMC41LDEuMSwwLjksMS44LDEuMmMwLjcsMC4zLDEuNCwwLjQsMi4yLDAuNGMwLjMsMCwwLjcsMCwxLTAuMWwtMC4xLDBsMC4xLDBsLTAuMSwwYzAuNSwwLjMsMSwwLjQsMS42LDAuNGMwLjksMCwxLjctMC4zLDIuMy0xYzAuNi0wLjYsMS0xLjQsMS0yLjNDLTQ3Ny4xLDUwMy00NzcuMyw1MDIuNS00NzcuNSw1MDIiLz48cmVjdCB4PSItNDkxIiB5PSI0OTMiIGNsYXNzPSJzdDEiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIvPjwvc3ZnPg==)!important;}

*[style='background-image:url("/assets/4fd1841c200d08f011c59d4f029d8258.png");']{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTQ5MSA0OTMgMTYgMTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTQ5MSA0OTMgMTYgMTY7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDojRkZGRkZGO30uc3Qxe2ZpbGw6bm9uZTt9PC9zdHlsZT48cGF0aCBjbGFzcz0ic3QwIiBkPSJNLTQ4Myw1MDQuNGMtMiwwLTIuOS0xLTIuOS0xLjdjMC0wLjQsMC4zLTAuNiwwLjctMC42YzAuOCwwLDAuNiwxLjIsMi4yLDEuMmMwLjgsMCwxLjMtMC40LDEuMy0wLjljMC0wLjMtMC4xLTAuNi0wLjctMC43bC0xLjgtMC40Yy0xLjQtMC40LTEuNy0xLjEtMS43LTEuOGMwLTEuNSwxLjQtMi4xLDIuNy0yLjFjMS4yLDAsMi42LDAuNywyLjYsMS42YzAsMC40LTAuMywwLjYtMC43LDAuNmMtMC43LDAtMC42LTEtMi0xYy0wLjcsMC0xLjEsMC4zLTEuMSwwLjhjMCwwLjUsMC42LDAuNiwxLjEsMC43bDEuMywwLjNjMS40LDAuMywxLjgsMS4yLDEuOCwxLjlDLTQ4MC4yLDUwMy41LTQ4MS4xLDUwNC40LTQ4Myw1MDQuNCBNLTQ3Ny41LDUwMkwtNDc3LjUsNTAyTC00NzcuNSw1MDJDLTQ3Ny42LDUwMS45LTQ3Ny42LDUwMi00NzcuNSw1MDJjMC4xLTAuMywwLjEtMC43LDAuMS0xYzAtMC44LTAuMS0xLjUtMC40LTIuMmMtMC4zLTAuNy0wLjctMS4zLTEuMi0xLjhjLTAuNS0wLjUtMS4xLTAuOS0xLjgtMS4yYy0wLjctMC4zLTEuNC0wLjQtMi4yLTAuNGMtMC40LDAtMC43LDAtMS4xLDAuMWgwbDAuMSwwbC0wLjEsMGwwLjEsMGMtMC41LTAuMy0xLTAuNC0xLjUtMC40Yy0wLjksMC0xLjcsMC4zLTIuMywxcy0xLDEuNC0xLDIuM2MwLDAuNiwwLjEsMS4xLDAuNCwxLjZsMC0wLjFsMCwwLjFjMCwwLDAsMCwwLTAuMWMtMC4xLDAuMy0wLjEsMC42LTAuMSwxYzAsMC44LDAuMSwxLjUsMC40LDIuMmMwLjMsMC43LDAuNywxLjMsMS4yLDEuOGMwLjUsMC41LDEuMSwwLjksMS44LDEuMmMwLjcsMC4zLDEuNCwwLjQsMi4yLDAuNGMwLjMsMCwwLjcsMCwxLTAuMWwtMC4xLDBsMC4xLDBsLTAuMSwwYzAuNSwwLjMsMSwwLjQsMS42LDAuNGMwLjksMCwxLjctMC4zLDIuMy0xYzAuNi0wLjYsMS0xLjQsMS0yLjNDLTQ3Ny4xLDUwMy00NzcuMyw1MDIuNS00NzcuNSw1MDIiLz48cmVjdCB4PSItNDkxIiB5PSI0OTMiIGNsYXNzPSJzdDEiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIvPjwvc3ZnPg==)!important;}

img[src="/assets/760b812456804ad977f968ca0b6a8b0b.png"]{content:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTQ5MSA0OTMgMTYgMTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTQ5MSA0OTMgMTYgMTY7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDpub25lO30uc3Qxe2ZpbGw6I0ZGRkZGRjt9PC9zdHlsZT48cmVjdCB4PSItNDkxIiB5PSI0OTMiIGNsYXNzPSJzdDAiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIvPjxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0tNDgzLDQ5NS4xYy0zLjEsMC01LjYsMi40LTUuOSw1LjRsMy4xLDEuM2MwLjMtMC4yLDAuNi0wLjMsMC45LTAuM2MwLDAsMC4xLDAsMC4xLDBsMS40LTJ2MGMwLTEuMiwxLTIuMiwyLjItMi4yYzEuMiwwLDIuMiwxLDIuMiwyLjJzLTEsMi4yLTIuMiwyLjJoLTAuMWwtMiwxLjRjMCwwLDAsMC4xLDAsMC4xYzAsMC45LTAuNywxLjctMS43LDEuN2MtMC44LDAtMS41LTAuNi0xLjYtMS4zbC0yLjMtMC45YzAuNywyLjUsMyw0LjMsNS42LDQuM2MzLjIsMCw1LjktMi42LDUuOS01LjlTLTQ3OS44LDQ5NS4xLTQ4Myw0OTUuMUwtNDgzLDQ5NS4xeiBNLTQ4NS4yLDUwNGwtMC43LTAuM2MwLjEsMC4zLDAuMywwLjUsMC42LDAuNmMwLjYsMC4zLDEuNCwwLDEuNi0wLjdjMC4xLTAuMywwLjEtMC42LDAtMWMtMC4xLTAuMy0wLjQtMC41LTAuNy0wLjdjLTAuMy0wLjEtMC42LTAuMS0wLjksMGwwLjcsMC4zYzAuNSwwLjIsMC43LDAuNywwLjUsMS4yQy00ODQuMiw1MDQtNDg0LjcsNTA0LjItNDg1LjIsNTA0TC00ODUuMiw1MDR6IE0tNDc5LjYsNDk5LjVjMC0wLjgtMC43LTEuNS0xLjUtMS41Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjVjMCwwLjgsMC43LDEuNSwxLjUsMS41Qy00ODAuMyw1MDEtNDc5LjYsNTAwLjMtNDc5LjYsNDk5LjV6IE0tNDgyLjIsNDk5LjVjMC0wLjYsMC41LTEuMSwxLjEtMS4xYzAuNiwwLDEuMSwwLjUsMS4xLDEuMWMwLDAuNi0wLjUsMS4xLTEuMSwxLjFDLTQ4MS43LDUwMC42LTQ4Mi4yLDUwMC4xLTQ4Mi4yLDQ5OS41eiIvPjwvc3ZnPg==)!important;}

*[style='background-image:url("/assets/760b812456804ad977f968ca0b6a8b0b.png");']{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTQ5MSA0OTMgMTYgMTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTQ5MSA0OTMgMTYgMTY7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDpub25lO30uc3Qxe2ZpbGw6I0ZGRkZGRjt9PC9zdHlsZT48cmVjdCB4PSItNDkxIiB5PSI0OTMiIGNsYXNzPSJzdDAiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIvPjxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0tNDgzLDQ5NS4xYy0zLjEsMC01LjYsMi40LTUuOSw1LjRsMy4xLDEuM2MwLjMtMC4yLDAuNi0wLjMsMC45LTAuM2MwLDAsMC4xLDAsMC4xLDBsMS40LTJ2MGMwLTEuMiwxLTIuMiwyLjItMi4yYzEuMiwwLDIuMiwxLDIuMiwyLjJzLTEsMi4yLTIuMiwyLjJoLTAuMWwtMiwxLjRjMCwwLDAsMC4xLDAsMC4xYzAsMC45LTAuNywxLjctMS43LDEuN2MtMC44LDAtMS41LTAuNi0xLjYtMS4zbC0yLjMtMC45YzAuNywyLjUsMyw0LjMsNS42LDQuM2MzLjIsMCw1LjktMi42LDUuOS01LjlTLTQ3OS44LDQ5NS4xLTQ4Myw0OTUuMUwtNDgzLDQ5NS4xeiBNLTQ4NS4yLDUwNGwtMC43LTAuM2MwLjEsMC4zLDAuMywwLjUsMC42LDAuNmMwLjYsMC4zLDEuNCwwLDEuNi0wLjdjMC4xLTAuMywwLjEtMC42LDAtMWMtMC4xLTAuMy0wLjQtMC41LTAuNy0wLjdjLTAuMy0wLjEtMC42LTAuMS0wLjksMGwwLjcsMC4zYzAuNSwwLjIsMC43LDAuNywwLjUsMS4yQy00ODQuMiw1MDQtNDg0LjcsNTA0LjItNDg1LjIsNTA0TC00ODUuMiw1MDR6IE0tNDc5LjYsNDk5LjVjMC0wLjgtMC43LTEuNS0xLjUtMS41Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjVjMCwwLjgsMC43LDEuNSwxLjUsMS41Qy00ODAuMyw1MDEtNDc5LjYsNTAwLjMtNDc5LjYsNDk5LjV6IE0tNDgyLjIsNDk5LjVjMC0wLjYsMC41LTEuMSwxLjEtMS4xYzAuNiwwLDEuMSwwLjUsMS4xLDEuMWMwLDAuNi0wLjUsMS4xLTEuMSwxLjFDLTQ4MS43LDUwMC42LTQ4Mi4yLDUwMC4xLTQ4Mi4yLDQ5OS41eiIvPjwvc3ZnPg==)!important;}

img[src="/assets/d62770cb3449a04c7292fc2ad7a9ffd9.png"]{content:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTQ5MSA0OTMgMTYgMTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTQ5MSA0OTMgMTYgMTY7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDojRkZGRkZGO30uc3Qxe2ZpbGw6bm9uZTt9PC9zdHlsZT48Zz48cGF0aCBjbGFzcz0ic3QwIiBkPSJNLTQ4OC4xLDQ5NC45bC0wLjgsMi4xdjguNWgyLjl2MS42aDEuNmwxLjYtMS42aDIuNGwzLjItMy4ydi03LjVILTQ4OC4xTC00ODguMSw0OTQuOXogTS00ODcsNDk1LjloOC44djUuOWwtMS45LDEuOWgtMi45bC0xLjYsMS42di0xLjZoLTIuNFY0OTUuOXoiLz48cGF0aCBjbGFzcz0ic3QwIiBkPSJNLTQ4NC4xLDUwMS4zaDEuMXYtMy4yaC0xLjFWNTAxLjN6IE0tNDgxLjEsNTAxLjNoMS4xdi0zLjJoLTEuMVY1MDEuM3oiLz48L2c+PHJlY3QgeD0iLTQ5MSIgeT0iNDkzIiBjbGFzcz0ic3QxIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiLz48L3N2Zz4=)!important;}

*[style='background-image:url("/assets/d62770cb3449a04c7292fc2ad7a9ffd9.png");']{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTQ5MSA0OTMgMTYgMTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTQ5MSA0OTMgMTYgMTY7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDojRkZGRkZGO30uc3Qxe2ZpbGw6bm9uZTt9PC9zdHlsZT48Zz48cGF0aCBjbGFzcz0ic3QwIiBkPSJNLTQ4OC4xLDQ5NC45bC0wLjgsMi4xdjguNWgyLjl2MS42aDEuNmwxLjYtMS42aDIuNGwzLjItMy4ydi03LjVILTQ4OC4xTC00ODguMSw0OTQuOXogTS00ODcsNDk1LjloOC44djUuOWwtMS45LDEuOWgtMi45bC0xLjYsMS42di0xLjZoLTIuNFY0OTUuOXoiLz48cGF0aCBjbGFzcz0ic3QwIiBkPSJNLTQ4NC4xLDUwMS4zaDEuMXYtMy4yaC0xLjFWNTAxLjN6IE0tNDgxLjEsNTAxLjNoMS4xdi0zLjJoLTEuMVY1MDEuM3oiLz48L2c+PHJlY3QgeD0iLTQ5MSIgeT0iNDkzIiBjbGFzcz0ic3QxIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiLz48L3N2Zz4=)!important;background-size:63%!important;}

img[src="/assets/3f902475b3576b6d008f27d1731e4c86.png"]{content:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTQ5MSA0OTMgMTYgMTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTQ5MSA0OTMgMTYgMTY7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDojRkZGRkZGO30uc3Qxe2ZpbGw6bm9uZTt9PC9zdHlsZT48cGF0aCBjbGFzcz0ic3QwIiBkPSJNLTQ3Ny4zLDQ5OC42YzAsMC0wLjEtMC44LTAuNS0xLjJjLTAuNS0wLjUtMS0wLjUtMS4yLTAuNWMtMS42LTAuMS00LjEtMC4xLTQuMS0wLjFzLTMsMC00LDAuMWMtMC4zLDAtMC44LDAtMS4zLDAuNWMtMC4zLDAuNC0wLjUsMS4yLTAuNSwxLjJzLTAuMSwxLTAuMSwxLjl2MC45YzAsMSwwLjEsMS45LDAuMSwxLjlzMC4xLDAuOCwwLjUsMS4yYzAuNSwwLjUsMSwwLjUsMS4zLDAuNWMwLjksMC4xLDQsMC4xLDQsMC4xczIuNSwwLDQuMS0wLjFjMC4yLDAsMC43LDAsMS4yLTAuNWMwLjMtMC40LDAuNS0xLjIsMC41LTEuMnMwLjEtMC45LDAuMS0xLjl2LTAuOUMtNDc3LjEsNDk5LjYtNDc3LjMsNDk4LjYtNDc3LjMsNDk4LjZ6IE0tNDg0LjIsNTAyLjV2LTMuM2wzLjIsMS43TC00ODQuMiw1MDIuNXoiLz48cmVjdCB4PSItNDkxIiB5PSI0OTMiIGNsYXNzPSJzdDEiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIvPjwvc3ZnPg==)!important;}

*[style='background-image:url("/assets/3f902475b3576b6d008f27d1731e4c86.png");']{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTQ5MSA0OTMgMTYgMTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTQ5MSA0OTMgMTYgMTY7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDojRkZGRkZGO30uc3Qxe2ZpbGw6bm9uZTt9PC9zdHlsZT48cGF0aCBjbGFzcz0ic3QwIiBkPSJNLTQ3Ny4zLDQ5OC42YzAsMC0wLjEtMC44LTAuNS0xLjJjLTAuNS0wLjUtMS0wLjUtMS4yLTAuNWMtMS42LTAuMS00LjEtMC4xLTQuMS0wLjFzLTMsMC00LDAuMWMtMC4zLDAtMC44LDAtMS4zLDAuNWMtMC4zLDAuNC0wLjUsMS4yLTAuNSwxLjJzLTAuMSwxLTAuMSwxLjl2MC45YzAsMSwwLjEsMS45LDAuMSwxLjlzMC4xLDAuOCwwLjUsMS4yYzAuNSwwLjUsMSwwLjUsMS4zLDAuNWMwLjksMC4xLDQsMC4xLDQsMC4xczIuNSwwLDQuMS0wLjFjMC4yLDAsMC43LDAsMS4yLTAuNWMwLjMtMC40LDAuNS0xLjIsMC41LTEuMnMwLjEtMC45LDAuMS0xLjl2LTAuOUMtNDc3LjEsNDk5LjYtNDc3LjMsNDk4LjYtNDc3LjMsNDk4LjZ6IE0tNDg0LjIsNTAyLjV2LTMuM2wzLjIsMS43TC00ODQuMiw1MDIuNXoiLz48cmVjdCB4PSItNDkxIiB5PSI0OTMiIGNsYXNzPSJzdDEiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIvPjwvc3ZnPg==)!important;}

img[src="/assets/e531a8063a4cde9853e38a861a7b2add.png"]{content:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTQ5MSA0OTMgMTYgMTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTQ5MSA0OTMgMTYgMTY7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDpub25lO30uc3Qxe2ZpbGw6I0ZGRkZGRjt9PC9zdHlsZT48cmVjdCB4PSItNDkxIiB5PSI0OTMiIGNsYXNzPSJzdDAiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIvPjxnPjxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iLTQ3OCw0OTYuNCAtNDc4LDQ5Ni40IC00NzgsNDk2LjQgIi8+PHBvbHlnb24gY2xhc3M9InN0MSIgcG9pbnRzPSItNDg4LjUsNDk4LjggLTQ4OC41LDQ5OC44IC00ODguNSw0OTguOCAiLz48cGF0aCBjbGFzcz0ic3QxIiBkPSJNLTQ3Ny40LDUwMS4zYy0wLjMtMC40LTAuNi0wLjctMC45LTAuOWMwLjEsMCwwLjIsMCwwLjMtMC4xYzAuMSwwLDAuMi0wLjEsMC4zLTAuMmMwLjEtMC4xLDAuMS0wLjIsMC4xLTAuNGMwLTAuMi0wLjEtMC40LTAuMi0wLjZjLTAuMy0wLjQtMC44LTAuNy0xLTAuOGMwLDAsMC0wLjEsMC4xLTAuMWMwLjEtMC4xLDAuMS0wLjMsMC4yLTAuNGMwLjEtMC4xLDAuMi0wLjQsMC4zLTAuN2MwLjEtMC4xLDAuMS0wLjMsMC4xLTAuNGMwLTAuMSwwLjEtMC4yLDAuMS0wLjNjMC0wLjEsMC0wLjEsMC0wLjJjMC0wLjIsMC0wLjItMC4xLTAuM2MwLDAtMC4xLTAuMS0wLjEsMGMwLDAtMC4xLDAuMS0wLjEsMC4xYzAsMC4xLTAuMSwwLjMtMC4yLDAuNWMtMC4xLDAuMy0wLjQsMC43LTAuNSwxLjFjLTAuMSwwLjItMC4yLDAuMy0wLjIsMC40YzAsMCwwLDAuMS0wLjEsMC4xYy0wLjgtMC4zLTEuNy0wLjUtMi0wLjVjLTAuMS0wLjItMC40LTAuNy0wLjctMS4yYy0wLjItMC4zLTAuNS0wLjYtMC44LTAuOWMtMC4zLTAuMi0wLjYtMC40LTAuOS0wLjRjLTAuMywwLTAuNiwwLjItMC43LDAuNGMtMC4zLDAuMy0wLjQsMC44LTAuNCwxLjJjMCwwLjEsMCwwLjMsMCwwLjRjMCwwLDAsMCwwLDBjLTAuMS0wLjEtMC4yLTAuMi0wLjMtMC4yYy0wLjEtMC4xLTAuMi0wLjEtMC4zLTAuMWMtMC4yLDAtMC4zLDAuMS0wLjQsMC4yYy0wLjIsMC4yLTAuMywwLjQtMC4zLDAuN2MtMC4xLDAuMy0wLjEsMC42LTAuMSwwLjljLTEuMSwwLTIsMC4zLTIuMSwwLjNjMCwwLTAuMSwwLTAuMSwwYzAsMC0wLjEsMC4xLTAuMSwwLjFjMCwwLDAsMC0wLjEsMC4xbDAsMGMwLDAsMCwwLDAsMC4xbDAsMC4xYzAsMCwwLDAuMSwwLjEsMC4xbDAsMGwwLDBsMCwwYzAuMSwwLDAuMy0wLjEsMC43LTAuMWMwLjMsMCwwLjctMC4xLDEuMi0wLjFjMC4yLDAsMC4zLDAsMC41LDBjMCwwLjQsMC4yLDAuOSwwLjMsMS4zYzAuMSwwLjMsMC4yLDAuNSwwLjIsMC43Yy0wLjEsMC4xLTAuMywwLjUtMC41LDAuOWMtMC4zLDAuNi0wLjYsMS4zLTAuNiwxLjljMCwwLjIsMCwwLjQsMC4yLDAuNmMwLjIsMC4yLDAuNCwwLjQsMC45LDAuNGMwLjQsMCwwLjctMC4xLDEtMC4yYzAuMSwwLDAuMi0wLjEsMC4zLTAuMWMwLDAsMCwwLDAsMGMwLDAuMS0wLjEsMC4zLTAuMSwwLjRjMCwwLjEsMCwwLjIsMC4xLDAuNGMwLjEsMC4xLDAuMywwLjIsMC42LDAuMmMwLjQsMCwwLjctMC4xLDEtMC4zYzAuMi0wLjEsMC4zLTAuMSwwLjQtMC4yYzAuMSwwLjEsMC4yLDAuMywwLjQsMC42YzAuMywwLjQsMC42LDAuOCwwLjksMS4xbDAsMGMwLjIsMC4yLDAuNCwwLjIsMC40LDAuMmMwLjEsMCwwLjEsMCwwLjEtMC4xYzAsMCwwLTAuMSwwLTAuMWwwLDBjLTAuMS0wLjEtMC42LTAuNi0xLjMtMS45YzAuNC0wLjIsMC43LTAuNiwxLTAuOWMwLjItMC4yLDAuNC0wLjUsMC40LTAuNmMwLjEsMCwwLjMsMCwwLjcsMGMwLjYsMCwxLjItMC4xLDEuOC0wLjJjMC4zLTAuMSwwLjUtMC4yLDAuNy0wLjRjMC4yLTAuMiwwLjMtMC40LDAuMy0wLjZDLTQ3Ny4xLDUwMS44LTQ3Ny4yLDUwMS41LTQ3Ny40LDUwMS4zeiBNLTQ4NS42LDUwMmMwLTAuMSwwLjEtMC4yLDAuMS0wLjNjMC4xLDAuMSwwLjIsMC4zLDAuMywwLjRjMC4yLDAuMywwLjUsMC42LDAuOSwwLjljLTAuNCwwLjItMC43LDAuMy0xLDAuM2MtMC4yLDAtMC40LTAuMS0wLjQtMC4xYy0wLjEtMC4xLTAuMS0wLjItMC4xLTAuM0MtNDg1LjgsNTAyLjYtNDg1LjcsNTAyLjMtNDg1LjYsNTAyeiBNLTQ4NC45LDQ5Ny45YzAsMC4xLDAsMC4yLDAsMC40YzAsMC4xLDAsMC4xLDAsMC4ybC0wLjcsMGMwLTAuMywwLjEtMC42LDAuMi0wLjdjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjJjMCwwLDAuMSwwLDAuMSwwLjFDLTQ4NSw0OTcuOC00ODQuOSw0OTcuOC00ODQuOSw0OTcuOXogTS00ODAuMyw0OTljLTAuMi0wLjItMC41LTAuNS0wLjgtMC42Yy0wLjEsMC0wLjEsMC0wLjEsMC4xczAsMC4xLDAsMC4xYzAuMywwLjIsMC41LDAuNCwwLjcsMC43Yy0xLjItMC40LTIuNy0wLjctMy4zLTAuOGMwLjMtMC4yLDAuOC0wLjMsMS40LTAuM2MwLjgsMCwxLjUsMC4yLDIsMC4zYzAuMywwLjEsMC41LDAuMiwwLjYsMC4yYzAsMCwwLjEsMCwwLjEsMGwtMC4zLDAuNEMtNDgwLjEsNDk5LjItNDgwLjIsNDk5LjEtNDgwLjMsNDk5eiBNLTQ4My4xLDUwMi40Qy00ODMuMSw1MDIuNC00ODMuMSw1MDIuMy00ODMuMSw1MDIuNGMtMC4yLTAuNS0wLjYtMS44LTAuNy0zLjFjMCwwLDAsMCwwLjEsMGMwLDAsMCwwLDAuMSwwYzAuNCwwLjEsMS43LDAuNCwyLjksMC45YzAsMCwwLDAsMCwwQy00ODEuMSw1MDAuNi00ODIuMSw1MDEuNi00ODMuMSw1MDIuNEMtNDgzLjEsNTAyLjQtNDgzLjEsNTAyLjQtNDgzLjEsNTAyLjR6IE0tNDgzLjcsNTAyLjhjLTAuNy0wLjQtMS4yLTEuMi0xLjUtMmMtMC4yLTAuNy0wLjMtMS40LTAuNC0xLjdsMC42LDAuMWMwLDAuMS0wLjEsMC4xLTAuMSwwLjJjLTAuMSwwLjItMC4yLDAuNS0wLjIsMC43YzAsMC4yLDAsMC4zLDAsMC40YzAsMCwwLDAuMSwwLDAuMWMwLDAsMCwwLDAuMSwwLjFjMCwwLDAuMSwwLDAuMSwwYzAsMCwwLjEtMC4xLDAuMS0wLjFsMCwwYzAsMCwwLTAuNSwwLjMtMUMtNDg0LjQsNTAxLjEtNDg0LDUwMi4yLTQ4My43LDUwMi44Qy00ODMuNyw1MDIuOC00ODMuNyw1MDIuOC00ODMuNyw1MDIuOHogTS00ODMuOCw1MDQuMUMtNDgzLjgsNTA0LjEtNDgzLjgsNTA0LjEtNDgzLjgsNTA0LjFMLTQ4My44LDUwNC4xYzAuMS0wLjEsMC4yLTAuMiwwLjMtMC4zYzAuMS0wLjEsMC4yLTAuMSwwLjItMC4yYzAsMCwwLDAsMCwwbDAuMywwLjZjLTAuMSwwLTAuMSwwLjEtMC4yLDAuMWMtMC4xLDAuMS0wLjMsMC4xLTAuNCwwLjFjLTAuMiwwLTAuMiwwLTAuMi0wLjFjMCwwLDAtMC4xLDAtMC4xQy00ODMuOSw1MDQuMy00ODMuOSw1MDQuMi00ODMuOCw1MDQuMXogTS00ODIuNiw1MDMuNkMtNDgyLjYsNTAzLjUtNDgyLjcsNTAzLjUtNDgyLjYsNTAzLjZjMC4xLTAuMSwwLjMtMC4xLDAuNS0wLjJjMC4zLTAuMSwwLjUtMC4yLDAuOC0wLjRjMCwwLDAtMC4xLDAtMC4yYzAsMC0wLjEtMC4xLTAuMSwwYy0wLjIsMC4xLTAuNiwwLjItMSwwLjJjMS0wLjksMS44LTEuOCwyLjMtMi41YzAsMCwwLDAsMCwwYzAsMC45LTAuNSwxLjctMS4xLDIuNGMtMC4zLDAuMy0wLjYsMC42LTAuOCwwLjhjLTAuMiwwLjEtMC4zLDAuMi0wLjQsMC4zQy00ODIuNSw1MDMuOC00ODIuNiw1MDMuNy00ODIuNiw1MDMuNnogTS00ODIuMSw0OTcuNmMtMC40LDAtMS4xLDAtMS43LDAuNGMwLTAuMywwLjEtMC43LDAuMi0wLjljMC4xLTAuMSwwLjEtMC4zLDAuMi0wLjNjMC4xLTAuMSwwLjItMC4xLDAuMy0wLjFjMC4xLDAsMC4yLDAuMSwwLjMsMC4yYzAuMiwwLjIsMC40LDAuNCwwLjYsMC42Qy00ODIuMiw0OTcuNS00ODIuMSw0OTcuNi00ODIuMSw0OTcuNkMtNDgyLjEsNDk3LjYtNDgyLjEsNDk3LjYtNDgyLjEsNDk3LjZ6IE0tNDc4LjcsNDk5LjlDLTQ3OC43LDQ5OS45LTQ3OC43LDQ5OS45LTQ3OC43LDQ5OS45bC0wLjEsMC4xbDAsMGwwLDBsMCwwbDAsMGwtMC4yLDBjLTAuMSwwLTAuMy0wLjItMC42LTAuM2MwLTAuMSwwLjEtMC4xLDAuMS0wLjJjMC4xLTAuMSwwLjItMC4zLDAuMi0wLjRjMC4xLDAsMC4yLDAuMSwwLjMsMC4yYzAuMSwwLjEsMC4yLDAuMiwwLjIsMC4yYzAuMSwwLjEsMC4xLDAuMiwwLjEsMC4yQy00NzguNyw0OTkuOC00NzguNyw0OTkuOS00NzguNyw0OTkuOXogTS00NzkuNiw1MDAuOWMwLjEsMC4xLDAuMywwLjIsMC40LDAuM2MwLjEsMC4xLDAuMiwwLjIsMC4zLDAuNGMwLjEsMC4xLDAuMSwwLjMsMC4xLDAuNGMwLDAuMSwwLDAuMS0wLjEsMC4yYy0wLjEsMC4xLTAuMiwwLjItMC4zLDAuMmMtMC4yLDAuMS0wLjUsMC4xLTAuOCwwLjJjLTAuMSwwLTAuMiwwLTAuMiwwQy00ODAsNTAyLjMtNDc5LjcsNTAxLjYtNDc5LjYsNTAwLjl6Ii8+PC9nPjwvc3ZnPg==)!important;}

*[style='background-image:url("/assets/76927ab03ebcbac8b84f40ff423a7907.png");']{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTQ5MSA0OTMgMTYgMTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgLTQ5MSA0OTMgMTYgMTY7IiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGUgdHlwZT0idGV4dC9jc3MiPi5zdDB7ZmlsbDpub25lO30uc3Qxe2ZpbGw6I0ZGRkZGRjt9PC9zdHlsZT48cmVjdCB4PSItNDkxIiB5PSI0OTMiIGNsYXNzPSJzdDAiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIvPjxnPjxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iLTQ3OCw0OTYuNCAtNDc4LDQ5Ni40IC00NzgsNDk2LjQgIi8+PHBvbHlnb24gY2xhc3M9InN0MSIgcG9pbnRzPSItNDg4LjUsNDk4LjggLTQ4OC41LDQ5OC44IC00ODguNSw0OTguOCAiLz48cGF0aCBjbGFzcz0ic3QxIiBkPSJNLTQ3Ny40LDUwMS4zYy0wLjMtMC40LTAuNi0wLjctMC45LTAuOWMwLjEsMCwwLjIsMCwwLjMtMC4xYzAuMSwwLDAuMi0wLjEsMC4zLTAuMmMwLjEtMC4xLDAuMS0wLjIsMC4xLTAuNGMwLTAuMi0wLjEtMC40LTAuMi0wLjZjLTAuMy0wLjQtMC44LTAuNy0xLTAuOGMwLDAsMC0wLjEsMC4xLTAuMWMwLjEtMC4xLDAuMS0wLjMsMC4yLTAuNGMwLjEtMC4xLDAuMi0wLjQsMC4zLTAuN2MwLjEtMC4xLDAuMS0wLjMsMC4xLTAuNGMwLTAuMSwwLjEtMC4yLDAuMS0wLjNjMC0wLjEsMC0wLjEsMC0wLjJjMC0wLjIsMC0wLjItMC4xLTAuM2MwLDAtMC4xLTAuMS0wLjEsMGMwLDAtMC4xLDAuMS0wLjEsMC4xYzAsMC4xLTAuMSwwLjMtMC4yLDAuNWMtMC4xLDAuMy0wLjQsMC43LTAuNSwxLjFjLTAuMSwwLjItMC4yLDAuMy0wLjIsMC40YzAsMCwwLDAuMS0wLjEsMC4xYy0wLjgtMC4zLTEuNy0wLjUtMi0wLjVjLTAuMS0wLjItMC40LTAuNy0wLjctMS4yYy0wLjItMC4zLTAuNS0wLjYtMC44LTAuOWMtMC4zLTAuMi0wLjYtMC40LTAuOS0wLjRjLTAuMywwLTAuNiwwLjItMC43LDAuNGMtMC4zLDAuMy0wLjQsMC44LTAuNCwxLjJjMCwwLjEsMCwwLjMsMCwwLjRjMCwwLDAsMCwwLDBjLTAuMS0wLjEtMC4yLTAuMi0wLjMtMC4yYy0wLjEtMC4xLTAuMi0wLjEtMC4zLTAuMWMtMC4yLDAtMC4zLDAuMS0wLjQsMC4yYy0wLjIsMC4yLTAuMywwLjQtMC4zLDAuN2MtMC4xLDAuMy0wLjEsMC42LTAuMSwwLjljLTEuMSwwLTIsMC4zLTIuMSwwLjNjMCwwLTAuMSwwLTAuMSwwYzAsMC0wLjEsMC4xLTAuMSwwLjFjMCwwLDAsMC0wLjEsMC4xbDAsMGMwLDAsMCwwLDAsMC4xbDAsMC4xYzAsMCwwLDAuMSwwLjEsMC4xbDAsMGwwLDBsMCwwYzAuMSwwLDAuMy0wLjEsMC43LTAuMWMwLjMsMCwwLjctMC4xLDEuMi0wLjFjMC4yLDAsMC4zLDAsMC41LDBjMCwwLjQsMC4yLDAuOSwwLjMsMS4zYzAuMSwwLjMsMC4yLDAuNSwwLjIsMC43Yy0wLjEsMC4xLTAuMywwLjUtMC41LDAuOWMtMC4zLDAuNi0wLjYsMS4zLTAuNiwxLjljMCwwLjIsMCwwLjQsMC4yLDAuNmMwLjIsMC4yLDAuNCwwLjQsMC45LDAuNGMwLjQsMCwwLjctMC4xLDEtMC4yYzAuMSwwLDAuMi0wLjEsMC4zLTAuMWMwLDAsMCwwLDAsMGMwLDAuMS0wLjEsMC4zLTAuMSwwLjRjMCwwLjEsMCwwLjIsMC4xLDAuNGMwLjEsMC4xLDAuMywwLjIsMC42LDAuMmMwLjQsMCwwLjctMC4xLDEtMC4zYzAuMi0wLjEsMC4zLTAuMSwwLjQtMC4yYzAuMSwwLjEsMC4yLDAuMywwLjQsMC42YzAuMywwLjQsMC42LDAuOCwwLjksMS4xbDAsMGMwLjIsMC4yLDAuNCwwLjIsMC40LDAuMmMwLjEsMCwwLjEsMCwwLjEtMC4xYzAsMCwwLTAuMSwwLTAuMWwwLDBjLTAuMS0wLjEtMC42LTAuNi0xLjMtMS45YzAuNC0wLjIsMC43LTAuNiwxLTAuOWMwLjItMC4yLDAuNC0wLjUsMC40LTAuNmMwLjEsMCwwLjMsMCwwLjcsMGMwLjYsMCwxLjItMC4xLDEuOC0wLjJjMC4zLTAuMSwwLjUtMC4yLDAuNy0wLjRjMC4yLTAuMiwwLjMtMC40LDAuMy0wLjZDLTQ3Ny4xLDUwMS44LTQ3Ny4yLDUwMS41LTQ3Ny40LDUwMS4zeiBNLTQ4NS42LDUwMmMwLTAuMSwwLjEtMC4yLDAuMS0wLjNjMC4xLDAuMSwwLjIsMC4zLDAuMywwLjRjMC4yLDAuMywwLjUsMC42LDAuOSwwLjljLTAuNCwwLjItMC43LDAuMy0xLDAuM2MtMC4yLDAtMC40LTAuMS0wLjQtMC4xYy0wLjEtMC4xLTAuMS0wLjItMC4xLTAuM0MtNDg1LjgsNTAyLjYtNDg1LjcsNTAyLjMtNDg1LjYsNTAyeiBNLTQ4NC45LDQ5Ny45YzAsMC4xLDAsMC4yLDAsMC40YzAsMC4xLDAsMC4xLDAsMC4ybC0wLjcsMGMwLTAuMywwLjEtMC42LDAuMi0wLjdjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjJjMCwwLDAuMSwwLDAuMSwwLjFDLTQ4NSw0OTcuOC00ODQuOSw0OTcuOC00ODQuOSw0OTcuOXogTS00ODAuMyw0OTljLTAuMi0wLjItMC41LTAuNS0wLjgtMC42Yy0wLjEsMC0wLjEsMC0wLjEsMC4xczAsMC4xLDAsMC4xYzAuMywwLjIsMC41LDAuNCwwLjcsMC43Yy0xLjItMC40LTIuNy0wLjctMy4zLTAuOGMwLjMtMC4yLDAuOC0wLjMsMS40LTAuM2MwLjgsMCwxLjUsMC4yLDIsMC4zYzAuMywwLjEsMC41LDAuMiwwLjYsMC4yYzAsMCwwLjEsMCwwLjEsMGwtMC4zLDAuNEMtNDgwLjEsNDk5LjItNDgwLjIsNDk5LjEtNDgwLjMsNDk5eiBNLTQ4My4xLDUwMi40Qy00ODMuMSw1MDIuNC00ODMuMSw1MDIuMy00ODMuMSw1MDIuNGMtMC4yLTAuNS0wLjYtMS44LTAuNy0zLjFjMCwwLDAsMCwwLjEsMGMwLDAsMCwwLDAuMSwwYzAuNCwwLjEsMS43LDAuNCwyLjksMC45YzAsMCwwLDAsMCwwQy00ODEuMSw1MDAuNi00ODIuMSw1MDEuNi00ODMuMSw1MDIuNEMtNDgzLjEsNTAyLjQtNDgzLjEsNTAyLjQtNDgzLjEsNTAyLjR6IE0tNDgzLjcsNTAyLjhjLTAuNy0wLjQtMS4yLTEuMi0xLjUtMmMtMC4yLTAuNy0wLjMtMS40LTAuNC0xLjdsMC42LDAuMWMwLDAuMS0wLjEsMC4xLTAuMSwwLjJjLTAuMSwwLjItMC4yLDAuNS0wLjIsMC43YzAsMC4yLDAsMC4zLDAsMC40YzAsMCwwLDAuMSwwLDAuMWMwLDAsMCwwLDAuMSwwLjFjMCwwLDAuMSwwLDAuMSwwYzAsMCwwLjEtMC4xLDAuMS0wLjFsMCwwYzAsMCwwLTAuNSwwLjMtMUMtNDg0LjQsNTAxLjEtNDg0LDUwMi4yLTQ4My43LDUwMi44Qy00ODMuNyw1MDIuOC00ODMuNyw1MDIuOC00ODMuNyw1MDIuOHogTS00ODMuOCw1MDQuMUMtNDgzLjgsNTA0LjEtNDgzLjgsNTA0LjEtNDgzLjgsNTA0LjFMLTQ4My44LDUwNC4xYzAuMS0wLjEsMC4yLTAuMiwwLjMtMC4zYzAuMS0wLjEsMC4yLTAuMSwwLjItMC4yYzAsMCwwLDAsMCwwbDAuMywwLjZjLTAuMSwwLTAuMSwwLjEtMC4yLDAuMWMtMC4xLDAuMS0wLjMsMC4xLTAuNCwwLjFjLTAuMiwwLTAuMiwwLTAuMi0wLjFjMCwwLDAtMC4xLDAtMC4xQy00ODMuOSw1MDQuMy00ODMuOSw1MDQuMi00ODMuOCw1MDQuMXogTS00ODIuNiw1MDMuNkMtNDgyLjYsNTAzLjUtNDgyLjcsNTAzLjUtNDgyLjYsNTAzLjZjMC4xLTAuMSwwLjMtMC4xLDAuNS0wLjJjMC4zLTAuMSwwLjUtMC4yLDAuOC0wLjRjMCwwLDAtMC4xLDAtMC4yYzAsMC0wLjEtMC4xLTAuMSwwYy0wLjIsMC4xLTAuNiwwLjItMSwwLjJjMS0wLjksMS44LTEuOCwyLjMtMi41YzAsMCwwLDAsMCwwYzAsMC45LTAuNSwxLjctMS4xLDIuNGMtMC4zLDAuMy0wLjYsMC42LTAuOCwwLjhjLTAuMiwwLjEtMC4zLDAuMi0wLjQsMC4zQy00ODIuNSw1MDMuOC00ODIuNiw1MDMuNy00ODIuNiw1MDMuNnogTS00ODIuMSw0OTcuNmMtMC40LDAtMS4xLDAtMS43LDAuNGMwLTAuMywwLjEtMC43LDAuMi0wLjljMC4xLTAuMSwwLjEtMC4zLDAuMi0wLjNjMC4xLTAuMSwwLjItMC4xLDAuMy0wLjFjMC4xLDAsMC4yLDAuMSwwLjMsMC4yYzAuMiwwLjIsMC40LDAuNCwwLjYsMC42Qy00ODIuMiw0OTcuNS00ODIuMSw0OTcuNi00ODIuMSw0OTcuNkMtNDgyLjEsNDk3LjYtNDgyLjEsNDk3LjYtNDgyLjEsNDk3LjZ6IE0tNDc4LjcsNDk5LjlDLTQ3OC43LDQ5OS45LTQ3OC43LDQ5OS45LTQ3OC43LDQ5OS45bC0wLjEsMC4xbDAsMGwwLDBsMCwwbDAsMGwtMC4yLDBjLTAuMSwwLTAuMy0wLjItMC42LTAuM2MwLTAuMSwwLjEtMC4xLDAuMS0wLjJjMC4xLTAuMSwwLjItMC4zLDAuMi0wLjRjMC4xLDAsMC4yLDAuMSwwLjMsMC4yYzAuMSwwLjEsMC4yLDAuMiwwLjIsMC4yYzAuMSwwLjEsMC4xLDAuMiwwLjEsMC4yQy00NzguNyw0OTkuOC00NzguNyw0OTkuOS00NzguNyw0OTkuOXogTS00NzkuNiw1MDAuOWMwLjEsMC4xLDAuMywwLjIsMC40LDAuM2MwLjEsMC4xLDAuMiwwLjIsMC4zLDAuNGMwLjEsMC4xLDAuMSwwLjMsMC4xLDAuNGMwLDAuMSwwLDAuMS0wLjEsMC4yYy0wLjEsMC4xLTAuMiwwLjItMC4zLDAuMmMtMC4yLDAuMS0wLjUsMC4xLTAuOCwwLjJjLTAuMSwwLTAuMiwwLTAuMiwwQy00ODAsNTAyLjMtNDc5LjcsNTAxLjYtNDc5LjYsNTAwLjl6Ii8+PC9nPjwvc3ZnPg==)!important;}

img[src="/assets/6d584208bb994e12d9596554a49e74fc.png"]{content:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTI3MTMgMTUyMy40IDE2IDE2IiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IC0yNzEzIDE1MjMuNCAxNiAxNjsiIHhtbDpzcGFjZT0icHJlc2VydmUiPjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+LnN0MHtmaWxsOm5vbmU7fS5zdDF7ZmlsbDojRkZGRkZGO308L3N0eWxlPjxyZWN0IHg9Ii0yNzEzIiB5PSIxNTIzLjQiIGNsYXNzPSJzdDAiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIvPjxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0tMjcwOS45LDE1MjUuNWg1LjRjMC4xLDAsMC4yLDAuMSwwLjEsMC4ybC0xLjEsMS41djcuN2MyLjQsMC45LDQuNy0wLjgsNS40LTEuNGMwLjEtMC4xLDAuMiwwLDAuMiwwLjFjLTAuMiwxLjMtMS4xLDMuMi0xLjUsMy43YzAsMC0wLjEsMC0wLjEsMGgtOC41Yy0wLjEsMC0wLjItMC4xLTAuMS0wLjJsMS42LTEuNXYtOC4ybC0xLjUtMS42Qy0yNzEwLjEsMTUyNS42LTI3MTAsMTUyNS41LTI3MDkuOSwxNTI1LjV6Ii8+PC9zdmc+)!important;}

*[style='background-image:url("/assets/6d584208bb994e12d9596554a49e74fc.png");']{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTI3MTMgMTUyMy40IDE2IDE2IiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IC0yNzEzIDE1MjMuNCAxNiAxNjsiIHhtbDpzcGFjZT0icHJlc2VydmUiPjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+LnN0MHtmaWxsOm5vbmU7fS5zdDF7ZmlsbDojRkZGRkZGO308L3N0eWxlPjxyZWN0IHg9Ii0yNzEzIiB5PSIxNTIzLjQiIGNsYXNzPSJzdDAiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIvPjxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0tMjcwOS45LDE1MjUuNWg1LjRjMC4xLDAsMC4yLDAuMSwwLjEsMC4ybC0xLjEsMS41djcuN2MyLjQsMC45LDQuNy0wLjgsNS40LTEuNGMwLjEtMC4xLDAuMiwwLDAuMiwwLjFjLTAuMiwxLjMtMS4xLDMuMi0xLjUsMy43YzAsMC0wLjEsMC0wLjEsMGgtOC41Yy0wLjEsMC0wLjItMC4xLTAuMS0wLjJsMS42LTEuNXYtOC4ybC0xLjUtMS42Qy0yNzEwLjEsMTUyNS42LTI3MTAsMTUyNS41LTI3MDkuOSwxNTI1LjV6Ii8+PC9zdmc+)!important;background-size:60%!important;}

img[src="/assets/c795f9ef8be0d19a0555ee96213abd00.png"]{content:url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTYgMTYiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiIHN0cm9rZS1taXRlcmxpbWl0PSIxLjQxNCI+PHBhdGggc3R5bGU9ImZpbGw6I2ZmZiIgZD0iTTE2IDMuMDM4Yy0uNTkuMjYtMS4yMi40MzctMS44ODUuNTE3LjY3Ny0uNDA3IDEuMTk4LTEuMDUgMS40NDMtMS44MTYtLjYzNC4zNy0xLjMzNy42NC0yLjA4NS43OS0uNTk4LS42NC0xLjQ1LTEuMDQtMi4zOTYtMS4wNC0xLjgxMiAwLTMuMjgyIDEuNDctMy4yODIgMy4yOCAwIC4yNi4wMy41MS4wODUuNzUtMi43MjgtLjEzLTUuMTQ3LTEuNDQtNi43NjYtMy40MkMuODMgMi41OC42NyAzLjE0LjY3IDMuNzVjMCAxLjE0LjU4IDIuMTQzIDEuNDYgMi43MzItLjUzOC0uMDE3LTEuMDQ1LS4xNjUtMS40ODctLjQxdi4wNGMwIDEuNTkgMS4xMyAyLjkxOCAyLjYzMyAzLjIyLS4yNzYuMDc0LS41NjYuMTE0LS44NjUuMTE0LS4yMSAwLS40MS0uMDItLjYxLS4wNTguNDIgMS4zMDQgMS42MyAyLjI1MyAzLjA3IDIuMjgtMS4xMi44OC0yLjU0IDEuNDA0LTQuMDcgMS40MDQtLjI2IDAtLjUyLS4wMTUtLjc4LS4wNDUgMS40Ni45MyAzLjE4IDEuNDc0IDUuMDQgMS40NzQgNi4wNCAwIDkuMzQtNSA5LjM0LTkuMzMgMC0uMTQgMC0uMjgtLjAxLS40Mi42NC0uNDYgMS4yLTEuMDQgMS42NC0xLjd6IiBmaWxsLXJ1bGU9Im5vbnplcm8iLz48L3N2Zz4=)!important;-webkit-transform:scale(.8);transform:scale(.8)}

*[style='background-image:url("/assets/c795f9ef8be0d19a0555ee96213abd00.png");']{background-image:url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTYgMTYiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiIHN0cm9rZS1taXRlcmxpbWl0PSIxLjQxNCI+PHBhdGggc3R5bGU9ImZpbGw6I2ZmZiIgZD0iTTE2IDMuMDM4Yy0uNTkuMjYtMS4yMi40MzctMS44ODUuNTE3LjY3Ny0uNDA3IDEuMTk4LTEuMDUgMS40NDMtMS44MTYtLjYzNC4zNy0xLjMzNy42NC0yLjA4NS43OS0uNTk4LS42NC0xLjQ1LTEuMDQtMi4zOTYtMS4wNC0xLjgxMiAwLTMuMjgyIDEuNDctMy4yODIgMy4yOCAwIC4yNi4wMy41MS4wODUuNzUtMi43MjgtLjEzLTUuMTQ3LTEuNDQtNi43NjYtMy40MkMuODMgMi41OC42NyAzLjE0LjY3IDMuNzVjMCAxLjE0LjU4IDIuMTQzIDEuNDYgMi43MzItLjUzOC0uMDE3LTEuMDQ1LS4xNjUtMS40ODctLjQxdi4wNGMwIDEuNTkgMS4xMyAyLjkxOCAyLjYzMyAzLjIyLS4yNzYuMDc0LS41NjYuMTE0LS44NjUuMTE0LS4yMSAwLS40MS0uMDItLjYxLS4wNTguNDIgMS4zMDQgMS42MyAyLjI1MyAzLjA3IDIuMjgtMS4xMi44OC0yLjU0IDEuNDA0LTQuMDcgMS40MDQtLjI2IDAtLjUyLS4wMTUtLjc4LS4wNDUgMS40Ni45MyAzLjE4IDEuNDc0IDUuMDQgMS40NzQgNi4wNCAwIDkuMzQtNSA5LjM0LTkuMzMgMC0uMTQgMC0uMjgtLjAxLS40Mi42NC0uNDYgMS4yLTEuMDQgMS42NC0xLjd6IiBmaWxsLXJ1bGU9Im5vbnplcm8iLz48L3N2Zz4=)!important;background-size:50%!important;background-position:50% 57%!important}

img[src="/assets/4a3496c5b0924198ae0234331c912d1b.png"]{content:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/PjxzdmcgaGVpZ2h0PSI1Ni43cHgiIGlkPSJMYXllcl8xIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1Ni43IDU2Ljc7IiB2ZXJzaW9uPSIxLjEiIHZpZXdCb3g9IjAgMCA1Ni43IDU2LjciIHdpZHRoPSI1Ni43cHgiIHhtbDpzcGFjZT0icHJlc2VydmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiPjxnPjxnPjxwYXRoIHN0eWxlPSJmaWxsOiNmZmYiIGQ9Ik01My4wNDgsMjguNDQ1N2MwLTMuMTM3My0yLjU1MjUtNS42ODk5LTUuNjg5OS01LjY4OTljLTEuMzk1NiwwLTIuNzExNiwwLjUwNDktMy43NTA2LDEuNDE5ICAgIGMtMy43NjI3LTIuNDA3OS04Ljc4MzQtMy45MjUtMTQuMzIxNS00LjA4ODRsMy4zODg2LTExLjU5MDNsOC4zMjAxLDEuNTQ1OGMtMC4wMDA0LDAuMDY3Ni0wLjAxMzUsMC4xMzIxLTAuMDEsMC4yMDA0ICAgIGMwLjEwMSwxLjk4MDEsMS43OTM4LDMuNTA4NiwzLjc3NCwzLjQwNzZjMS45OC0wLjEwMSwzLjUwODYtMS43OTM5LDMuNDA3Ni0zLjc3MzljLTAuMTAxLTEuOTgwMS0xLjc5MzgtMy41MDg2LTMuNzczOS0zLjQwNzYgICAgYy0xLjI3ODUsMC4wNjUyLTIuMzYwNSwwLjc5ODUtMi45NDU1LDEuODM5OGMtMC4wMDEtMC4wMDAzLTAuMDAxOS0wLjAwMS0wLjAwMy0wLjAwMTJsLTEwLjAyNi0xLjg2MjZsLTMuOTkzNCwxMy42Mzg4ICAgIGMtNS41NTE1LDAuMTQ4LTEwLjU4ODEsMS42NTYzLTE0LjM2Nyw0LjA1OThjLTEuMDMzNS0wLjg5NDQtMi4zMzU4LTEuMzg3Mi0zLjcxNTYtMS4zODcyYy0zLjEzNzIsMC01LjY4OTksMi41NTI1LTUuNjg5OSw1LjY4OTkgICAgYzAsMS45NDA1LDAuOTk5LDMuNzI5OSwyLjYxNjcsNC43NzM5Yy0wLjA5ODMsMC41Njc4LTAuMTU0NCwxLjE0NDMtMC4xNTQ0LDEuNzI5NmMwLDguMjEyNyw5Ljk1NTQsMTQuODk0OCwyMi4xOTM0LDE0Ljg5NDggICAgUzUwLjUwMSw0My4xNjE4LDUwLjUwMSwzNC45NDkyYzAtMC41Njg0LTAuMDUyMi0xLjEyODMtMC4xNDUxLTEuNjgwM0M1Mi4wMTgyLDMyLjIzMjksNTMuMDQ4LDMwLjQxNjcsNTMuMDQ4LDI4LjQ0NTd6ICAgICBNMTcuNzYwMiwzMi4zMTgzYzAtMS45Mjk4LDEuNTY1LTMuNDk1NiwzLjQ5NzUtMy40OTU2YzEuOTMwNywwLDMuNDk1NywxLjU2NTgsMy40OTU3LDMuNDk1NiAgICBjMCwxLjkzMTYtMS41NjUsMy40OTY2LTMuNDk1NywzLjQ5NjZDMTkuMzI1MiwzNS44MTQ5LDE3Ljc2MDIsMzQuMjQ5OSwxNy43NjAyLDMyLjMxODN6IE0zNi41NTAxLDQxLjc3NTUgICAgYy0wLjEwNDIsMC4xMDktMi42MTMyLDIuNjYxNS04LjI4MzMsMi42NjE1Yy01LjY5OTIsMC03Ljk3OTEtMi41ODc5LTguMDczLTIuNjk3N2MtMC4zMjEzLTAuMzc1Mi0wLjI3NzUtMC45NDAzLDAuMDk3Ny0xLjI2MDUgICAgYzAuMzczMy0wLjMxODQsMC45MzI4LTAuMjc3NCwxLjI1NSwwLjA5MjFjMC4wNTExLDAuMDU1OSwxLjk1NCwyLjA3ODgsNi43MjA0LDIuMDc4OGM0Ljg0OTIsMCw2Ljk3NTQtMi4wOTQ2LDYuOTk2OC0yLjExNSAgICBjMC4zNDM1LTAuMzUsMC45MDg2LTAuMzU4NCwxLjI2MTQtMC4wMTQ5QzM2Ljg3NTksNDAuODYyMywzNi44ODksNDEuNDIwOSwzNi41NTAxLDQxLjc3NTV6IE0zNS44NTQ3LDM1LjgxNDkgICAgYy0xLjkzMjYsMC0zLjQ5NzUtMS41NjUtMy40OTc1LTMuNDk2NmMwLTEuOTI5OCwxLjU2NS0zLjQ5NTYsMy40OTc1LTMuNDk1NmMxLjkzMDgsMCwzLjQ5NTcsMS41NjU4LDMuNDk1NywzLjQ5NTYgICAgQzM5LjM1MDQsMzQuMjQ5OSwzNy43ODU1LDM1LjgxNDksMzUuODU0NywzNS44MTQ5eiIvPjwvZz48L2c+PC9zdmc+)!important;}

*[style='background-image:url("/assets/4a3496c5b0924198ae0234331c912d1b.png");']{background-image:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/PjxzdmcgaGVpZ2h0PSI1Ni43cHgiIGlkPSJMYXllcl8xIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1Ni43IDU2Ljc7IiB2ZXJzaW9uPSIxLjEiIHZpZXdCb3g9IjAgMCA1Ni43IDU2LjciIHdpZHRoPSI1Ni43cHgiIHhtbDpzcGFjZT0icHJlc2VydmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiPjxnPjxnPjxwYXRoIHN0eWxlPSJmaWxsOiNmZmYiIGQ9Ik01My4wNDgsMjguNDQ1N2MwLTMuMTM3My0yLjU1MjUtNS42ODk5LTUuNjg5OS01LjY4OTljLTEuMzk1NiwwLTIuNzExNiwwLjUwNDktMy43NTA2LDEuNDE5ICAgIGMtMy43NjI3LTIuNDA3OS04Ljc4MzQtMy45MjUtMTQuMzIxNS00LjA4ODRsMy4zODg2LTExLjU5MDNsOC4zMjAxLDEuNTQ1OGMtMC4wMDA0LDAuMDY3Ni0wLjAxMzUsMC4xMzIxLTAuMDEsMC4yMDA0ICAgIGMwLjEwMSwxLjk4MDEsMS43OTM4LDMuNTA4NiwzLjc3NCwzLjQwNzZjMS45OC0wLjEwMSwzLjUwODYtMS43OTM5LDMuNDA3Ni0zLjc3MzljLTAuMTAxLTEuOTgwMS0xLjc5MzgtMy41MDg2LTMuNzczOS0zLjQwNzYgICAgYy0xLjI3ODUsMC4wNjUyLTIuMzYwNSwwLjc5ODUtMi45NDU1LDEuODM5OGMtMC4wMDEtMC4wMDAzLTAuMDAxOS0wLjAwMS0wLjAwMy0wLjAwMTJsLTEwLjAyNi0xLjg2MjZsLTMuOTkzNCwxMy42Mzg4ICAgIGMtNS41NTE1LDAuMTQ4LTEwLjU4ODEsMS42NTYzLTE0LjM2Nyw0LjA1OThjLTEuMDMzNS0wLjg5NDQtMi4zMzU4LTEuMzg3Mi0zLjcxNTYtMS4zODcyYy0zLjEzNzIsMC01LjY4OTksMi41NTI1LTUuNjg5OSw1LjY4OTkgICAgYzAsMS45NDA1LDAuOTk5LDMuNzI5OSwyLjYxNjcsNC43NzM5Yy0wLjA5ODMsMC41Njc4LTAuMTU0NCwxLjE0NDMtMC4xNTQ0LDEuNzI5NmMwLDguMjEyNyw5Ljk1NTQsMTQuODk0OCwyMi4xOTM0LDE0Ljg5NDggICAgUzUwLjUwMSw0My4xNjE4LDUwLjUwMSwzNC45NDkyYzAtMC41Njg0LTAuMDUyMi0xLjEyODMtMC4xNDUxLTEuNjgwM0M1Mi4wMTgyLDMyLjIzMjksNTMuMDQ4LDMwLjQxNjcsNTMuMDQ4LDI4LjQ0NTd6ICAgICBNMTcuNzYwMiwzMi4zMTgzYzAtMS45Mjk4LDEuNTY1LTMuNDk1NiwzLjQ5NzUtMy40OTU2YzEuOTMwNywwLDMuNDk1NywxLjU2NTgsMy40OTU3LDMuNDk1NiAgICBjMCwxLjkzMTYtMS41NjUsMy40OTY2LTMuNDk1NywzLjQ5NjZDMTkuMzI1MiwzNS44MTQ5LDE3Ljc2MDIsMzQuMjQ5OSwxNy43NjAyLDMyLjMxODN6IE0zNi41NTAxLDQxLjc3NTUgICAgYy0wLjEwNDIsMC4xMDktMi42MTMyLDIuNjYxNS04LjI4MzMsMi42NjE1Yy01LjY5OTIsMC03Ljk3OTEtMi41ODc5LTguMDczLTIuNjk3N2MtMC4zMjEzLTAuMzc1Mi0wLjI3NzUtMC45NDAzLDAuMDk3Ny0xLjI2MDUgICAgYzAuMzczMy0wLjMxODQsMC45MzI4LTAuMjc3NCwxLjI1NSwwLjA5MjFjMC4wNTExLDAuMDU1OSwxLjk1NCwyLjA3ODgsNi43MjA0LDIuMDc4OGM0Ljg0OTIsMCw2Ljk3NTQtMi4wOTQ2LDYuOTk2OC0yLjExNSAgICBjMC4zNDM1LTAuMzUsMC45MDg2LTAuMzU4NCwxLjI2MTQtMC4wMTQ5QzM2Ljg3NTksNDAuODYyMywzNi44ODksNDEuNDIwOSwzNi41NTAxLDQxLjc3NTV6IE0zNS44NTQ3LDM1LjgxNDkgICAgYy0xLjkzMjYsMC0zLjQ5NzUtMS41NjUtMy40OTc1LTMuNDk2NmMwLTEuOTI5OCwxLjU2NS0zLjQ5NTYsMy40OTc1LTMuNDk1NmMxLjkzMDgsMCwzLjQ5NTcsMS41NjU4LDMuNDk1NywzLjQ5NTYgICAgQzM5LjM1MDQsMzQuMjQ5OSwzNy43ODU1LDM1LjgxNDksMzUuODU0NywzNS44MTQ5eiIvPjwvZz48L2c+PC9zdmc+)!important;}

.checkbox .checkbox-inner+span{color:rgba(255, 255, 255, .7);}

.connect-account-btn .connect-account-btn-inner{background-color:#121213;border:0px solid transparent;}

.connect-account-btn .connect-account-btn-inner:hover{background-color:var(--main-color);}

.channel-members .member.member-status-offline .status{display: block !important;}

form .bf-toolbar{transform:translate(0,-35px);margin-left:60px;width:auto;position:relative;z-index:1337}

.bf-toolbar{color:#fff}

.channels-wrap .guild-header ~ .channel-notices:not(:empty), /* For non-canary users */
.channels-wrap .guild-header ~ .channel-list-top,
.channels-wrap .guild-header ~ .scroller-wrap{transition: 300ms cubic-bezier(0, 1, 0.5, 1);}

.channels-wrap .guild-header ~ .scroller-wrap{margin-top: 0px;}

.channels-wrap .guild-header ~ .channel-list-top{margin-top: 0px;}

.channels-wrap .guild-header.popout-open ~ .channel-notices:not(:empty){margin-top: 30px;} /* For non-canary users */

.channels-wrap .guild-header.popout-open ~ .channel-list-top{margin-top: 30px;}

.channels-wrap .guild-header.popout-open + .channel-notices:empty + .scroller-wrap{margin-top: 30px;} /* For non-canary users */

.ui-button.brand.filled:hover{background-color:var(--hover-color);}

.ui-button.brand.filled, .ui-tab-bar.SIDE .ui-tab-bar-item.selected{background-color:var(--main-color);}

.ui-tab-bar.SIDE .ui-tab-bar-item.brand{color:var(--main-color);}

.ui-standard-sidebar-view .sidebar-region,.ui-standard-sidebar-view .sidebar-region .scrollbar{background:#19191b !important;}

.ui-standard-sidebar-view .content-region,.ui-standard-sidebar-view .content-region .scrollbar{background:#19191b !important;}

.ui-tab-bar-item:hover{background-color:#111113 !important;}

.ui-card-primary{background:rgba(0, 0, 0, 0.18)!important;}

.theme-dark .ui-standard-sidebar-view .btn-close:hover{background-color:var(--main-color);border-color:var(--hover-color);}

.ui-switch-checkbox:checked+.ui-switch{background:var(--main-color);}

.theme-dark .ui-card-primary .ui-form-title.h5{color:#fff;}

.theme-dark .ui-card-primary.editable{border:2px solid #121213 !important;}

.theme-dark .ui-radiogroup .checked{border-color:var(--hover-color) !important;border-width: 2px;}

.theme-dark .ui-checkbox.checked{background:#131313;}

.theme-dark .ui-checkbox{border-color: #101011;border-width: 2px;}

polyline[stroke*="#7289da"]{stroke:var(--main-color) !important;}

.ui-checkbox-wrapper .input:focus+.ui-checkbox{box-shadow:none;}

.user-settings-modal .tab-bar.SIDE .tab-bar-item.selected,.user-settings-modal .tab-bar.SIDE .tab-bar-item:hover{opacity:1!important;}

.user-settings-modal .tab-bar.SIDE .tab-bar-item:hover{-webkit-transition:0ms;transition:0ms}

.user-settings-modal .tab-bar.SIDE .tab-bar-item{opacity:.3;color:#fff;}

.ui-tab-bar.SIDE .ui-tab-bar-item:before{margin-right:10px;vertical-align:-30%;}

.ui-tab-bar-item:before{opacity:0.7;}

.ui-tab-bar-item:hover:before, .ui-tab-bar-item.selected:before{opacity:1 !important;}

.ui-slider .slider-bar-fill{background:var(--main-color);}

.theme-dark .ui-standard-sidebar-view{background:transparent;}

.layers{background:#19191b !important;}

.layers>.layer.animating,.layers>.layer.animating *{pointer-events:none!important}

.platform-osx .layer.animating .chat>.title-wrap{-webkit-app-region:no-drag}

.ui-text-input .input:focus{border-color:var(--main-color) !important;border-width:2px !important;}

.ui-standard-sidebar-view .sidebar-region .scroller::-webkit-scrollbar{width:0px;}

.theme-dark .ui-select .Select-menu-outer{border-left-color:#000;border-bottom-color:#000;border-right-color:#000;border-top-color:transparent;border-width:1px;border-top-width:0px;border-top-left-radius:0px;border-top-right-radius:0px;background:#121213;}

.theme-dark .ui-select .Select-option.is-selected, .theme-dark .ui-select .Select-option.is-focused{background:var(--main-color) !important;color:#fff !important;}

.Select-option.is-focused, .theme-dark .ui-select .Select-option:hover{background:var(--hover-color) !important;color:#fff !important;}

.Select-control{background-color:#121213 !important;}

#user-profile-modal .header .header-info .profile-badge.badge-partner, #user-profile-modal .header .header-info .profile-badge.badge-staff{position: absolute;opacity: 0.9;}

.ui-popout{background-color: #202225;border: 0px solid rgba(0,0,0,.05);border-radius: 3px;}

.ui-popout .item:hover{background-color: rgba(0,0,0,0.2);}

.ui-popout .item .name{color: var(--main-color);}

.ui-popout{background-color:#202225;border:0px solid rgba(0,0,0,.05);border-radius:3px;}

.ui-popout .item:hover{background-color:rgba(0,0,0,0.2);}

.ui-popout .item .name{color:var(--main-color);}

.invite-banner{background-color:var(--main-color);}

.invite-banner.invite-banner-2 .instant-invite:not(.clipboard-input-copied) .clipboard-input-inner{border-color:var(--hover-color);}

.invite-banner.invite-banner-2 .instant-invite .clipboard-input-inner{background-color:var(--hover-color);opacity:0.9;}

.invite-banner .instant-invite:not(.clipboard-input-copied) .clipboard-input-inner button{background-color:#19191b;color:#fff;}

.invite-banner.invite-banner-2 .instant-invite .clipboard-input-inner button:before{background:linear-gradient(to right,hsla(0,0%,100%,0),rgba(0,0,0,.3));}

.message .username-wrapper.popout-open{background: var(--main-color);}

.message .username-wrapper.popout-open .user-name {color: #fff!important;}

.message .username-wrapper .user-name{transition: all 0ms ease!important;}

.message .username-wrapper{border-radius: 2px;margin-left: -2px;margin-right: -2px;padding-right: 4px;padding-left: 4px;padding-top: 3px;padding-bottom: 3px;transition: all 0ms ease;}

.theme-light .btn.btn-settings{position: fixed;left: 58%;top: 50%;-webkit-transform: translate(-50%, -50%);-ms-transform: translate(-50%, -50%);transform: translate(-50%, -50%);margin-top: 65px;width: 230px;height: 40px;visibility: visible!important;background: var(--main-color)!important;border-radius: 5px;box-shadow: 0 2px 10px rgba(240, 71, 71, .3);}

.theme-light .btn.btn-settings:before{position: absolute;z-index: 10000;content: "GO TO SETTINGS";display: block;width: 230px;height: 22px;border-radius: 5px;top: 50%;left: 50%;-webkit-transform: translate(-50%, -50%);-ms-transform: translate(-50%, -50%);transform: translate(-50%, -50%);visibility: visible!important;font-size: 17px;font-weight: 700;color: #fff}

.theme-light .btn.btn-settings:after{visibility: hidden;}

.theme-dark .ui-radiogroup .desc {color: #b1b1b1;}

.theme-dark .ui-form-text.style-description, .theme-dark .ui-form-text.style-label-descriptor {color: #a2a2a2;}

.ui-card[style*="padding: 10px; border-color: rgb(250, 166, 26); background-color: rgb(250, 166, 26);"] {border-color: #faa61a !important;background-color: #faa61a !important;border: 2px solid #faa61a !important; }

.ui-card[style*="padding: 10px; border-color: rgb(67, 181, 129); background-color: rgb(67, 181, 129);"] {border-color: #43b581 !important;background-color: #43b581 !important;border: 2px solid #43b581 !important;}

.ui-card[style*="padding: 10px; border-color: rgb(240, 71, 71); background-color: rgb(240, 71, 71);"] {border-color: #f04747 !important;background-color: #f04747 !important;border: 2px solid #f04747 !important;}

.channel-members::after {content: var(--theme-name)" v"var(--version-content);font-family: "Roboto";text-align: center;background: transparent;color: transparent;font-weight: 700;font-size: 250%;width: 100%;height: 70px;bottom: 0px;position: absolute;line-height: 75px;border-top: 2px solid #212121;left: -2px;z-index: 1;border-radius: 0px !important;padding-right: 30px;}

#friends .friends-table .friends-table-body::after{content: "";background: #19191b;width: 1400px;height: 70px;bottom: 0px;position: absolute;border-top: 2px solid #212121;}

.account .avatar-small{margin-left: 13px;}

.popout.popout-top:not(.no-arrow){z-index: 8;}

[class*="scroller-"].channel-members{height: calc(100% - 71px);}

#friends .friends-table .friends-table-body{height: calc(100% - 133px);}

.quiet{height: 70px;}

.guilds-wrapper .dms{display: block;margin-top: 7px;margin-bottom: -4px;}

.app .guilds .guild:first-child{border-bottom: 2px solid var(--main-color);background: #19191b;top: 0px;padding-bottom: 1px;position: fixed;width: 79px;left: -3px;z-index: 2;}

.app .guilds .guild:first-of-type .guild-inner{background: #19191b !important;}

.guilds-wrapper .guilds .guild:first-of-type .guild-inner{background: #19191b !important;}

.guilds .guild:hover:first-child, .guilds-wrapper .guilds .guild:hover:first-of-type .guild-inner, .guilds-wrapper .guilds .guild.active:first-of-type .guild-inner, .guilds .friends-icon:hover{background-color: #131313 !important;}

.guilds-wrapper .guilds .friends-icon{background-position: 10px 10px;margin-left: 13px;}

.dms .guild:first-child{border-bottom: 0px solid var(--main-color) !important;background: transparent!important;top: 0px!important;width: 45px!important;left: 0px!important;position: initial!important;border-radius: 25px !important;z-index: 1!important;}

.dms .guild .guild-inner:first-child{border-radius: 25px !important;}

.tooltips .tooltip.tooltip-right[style*="left: 42px; top: 12.5px;"]{display: none;}

.account .btn-group::after{content: "";width: 3px;height: 70px;background: #19191b;position: absolute;bottom: 0px;left: 305px;z-index: 1;}

.theme-dark .channel-textarea-inner{border-left: 2px solid #212121 !important;border-right: 2px solid #212121 !important;}

.message-group .avatar-large[style*="172218388880293888"] {background-image:url(https://i.imgur.com/KUFVy78.png) !important;}

.message-group:hover .avatar-large[style*="172218388880293888"]{background-image:url(https://i.imgur.com/tLfxGiD.gif) !important;}

*[style*="172218388880293888"] {background-image:url(https://i.imgur.com/tLfxGiD.gif) !important;}

.app .guilds .guild.active:first-child{background: #131313;}

.titlebar{width: calc(100% - 300px);left: auto;right: 0;}

*[style*="81388395867156480"] {background-image:url(https://i.imgur.com/5dMIWlw.png)!important;}

.app .guilds>div.guild:first-child .badge{margin: 0px 2px 0px 0px !important;padding: 20px 38px 16px 35px;border-radius: 0px !important;background-color: #19191b;border-bottom: 2px solid var(--main-color);transition: .2s background-color linear;}

.app .guilds>div.guild:first-child:hover .badge{background-color: #121213;}

.friends-icon{background-image: url(https://betterdocs.net/dm-icon.svg)!important; }

[style*="81388395867156480"] ~ .member-inner .member-username-inner,
[style*="81388395867156480"] ~ .comment .user-name {font-size:0px !important;}
[style*="81388395867156480"] ~ .member-inner .member-username-inner::before,
[style*="81388395867156480"] ~ .comment .user-name::after {content:"betterdocs.net";font-size:16px;}

.channel-members .member .avatar-small[style*="81388395867156480"] ~ .member-inner .member-username .member-username-inner::after{line-height: 26px!important;}

.keybind-shortcut.dark span{background-color: #121213;}

.scroller-wrap .scroller.messages::-webkit-scrollbar-track-piece{border: 3px solid transparent !important;background-color: transparent !important;}

.scroller-wrap .scroller.messages::-webkit-scrollbar-thumb{background-color: transparent !important;}

.scroller-wrap .scroller.messages:hover::-webkit-scrollbar-track-piece{border: 3px solid rgb(25, 25, 27) !important;background-color: #111113 !important;}

.scroller-wrap .scroller.messages:hover::-webkit-scrollbar-thumb{background-color: var(--main-color) !important;}

.header-toolbar button span[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNiIgaGVpZ2h0PSIyNiI+CiAgPHBhdGggZmlsbD0iI0ZGRiIgZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNOCA5LjMyNTg0MjdjMCAuNzQxNTczMDMuNjE2NDM4MzYgMS4zNTk1NTA1NiAxLjM1NjE2NDM4IDEuMzU5NTUwNTYuNzM5NzI2MDMgMCAxLjM1NjE2NDQtLjYxNzk3NzUzIDEuMzU2MTY0NC0xLjM1OTU1MDU2IDAtMS40ODMxNDYwNyAxLjYwMjczOTctMS41NDQ5NDM4MiAxLjc4NzY3MTIyLTEuNTQ0OTQzODIuMTg0OTMxNSAwIDEuNzg3NjcxMjMuMDYxNzk3NzUgMS43ODc2NzEyMyAxLjU0NDk0Mzgydi4zMDg5ODg3NmMwIC42MTc5Nzc1My0uMzA4MjE5MTggMS4xMTIzNTk1NS0uODYzMDEzNyAxLjQyMTM0ODMybC0xLjIzMjg3NjcuNjc5Nzc1MjhjLS42NzgwODIyLjM3MDc4NjUtMS4wNDc5NDUyIDEuMDUwNTYxOC0xLjA0Nzk0NTIgMS43OTIxMzQ4M3YxLjExMjM1OTUyQzExLjE0MzgzNTYzIDE1LjM4MjAyMjUgMTEuNzYwMjczOTYgMTYgMTIuNSAxNmMuNzM5NzI2MDMgMCAxLjM1NjE2NDM4LS42MTc5Nzc1IDEuMzU2MTY0MzgtMS4zNTk1NTA1NnYtLjY3OTc3NTI4bC44NjMwMTM3LS40MzI1ODQyN0MxNi4xMzY5ODYzIDEyLjc4NjUxNjgyIDE3IDExLjMwMzM3MDggMTcgOS42OTY2Mjkydi0uMzcwNzg2NUMxNyA2LjQ4MzE0NjA3IDE0LjcxOTE3ODA4IDUgMTIuNSA1IDEwLjIxOTE3ODA4IDUgOCA2LjQ4MzE0NjA3IDggOS4zMjU4NDI3ek0xMi41IDE3Yy0yIDAtMiAzIDAgM3MyLTMgMC0zeiIvPgo8L3N2Zz4=");']{background-image:none !important;}

.header-toolbar button span[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNiIgaGVpZ2h0PSIyNiI+CiAgPHBhdGggZmlsbD0iI0ZGRiIgZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNOCA5LjMyNTg0MjdjMCAuNzQxNTczMDMuNjE2NDM4MzYgMS4zNTk1NTA1NiAxLjM1NjE2NDM4IDEuMzU5NTUwNTYuNzM5NzI2MDMgMCAxLjM1NjE2NDQtLjYxNzk3NzUzIDEuMzU2MTY0NC0xLjM1OTU1MDU2IDAtMS40ODMxNDYwNyAxLjYwMjczOTctMS41NDQ5NDM4MiAxLjc4NzY3MTIyLTEuNTQ0OTQzODIuMTg0OTMxNSAwIDEuNzg3NjcxMjMuMDYxNzk3NzUgMS43ODc2NzEyMyAxLjU0NDk0Mzgydi4zMDg5ODg3NmMwIC42MTc5Nzc1My0uMzA4MjE5MTggMS4xMTIzNTk1NS0uODYzMDEzNyAxLjQyMTM0ODMybC0xLjIzMjg3NjcuNjc5Nzc1MjhjLS42NzgwODIyLjM3MDc4NjUtMS4wNDc5NDUyIDEuMDUwNTYxOC0xLjA0Nzk0NTIgMS43OTIxMzQ4M3YxLjExMjM1OTUyQzExLjE0MzgzNTYzIDE1LjM4MjAyMjUgMTEuNzYwMjczOTYgMTYgMTIuNSAxNmMuNzM5NzI2MDMgMCAxLjM1NjE2NDM4LS42MTc5Nzc1IDEuMzU2MTY0MzgtMS4zNTk1NTA1NnYtLjY3OTc3NTI4bC44NjMwMTM3LS40MzI1ODQyN0MxNi4xMzY5ODYzIDEyLjc4NjUxNjgyIDE3IDExLjMwMzM3MDggMTcgOS42OTY2Mjkydi0uMzcwNzg2NUMxNyA2LjQ4MzE0NjA3IDE0LjcxOTE3ODA4IDUgMTIuNSA1IDEwLjIxOTE3ODA4IDUgOCA2LjQ4MzE0NjA3IDggOS4zMjU4NDI3ek0xMi41IDE3Yy0yIDAtMiAzIDAgM3MyLTMgMC0zeiIvPgo8L3N2Zz4=");']:hover{opacity:1 !important;}

.header-toolbar button span[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNiIgaGVpZ2h0PSIyNiI+CiAgPHBhdGggZmlsbD0iI0ZGRiIgZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNOCA5LjMyNTg0MjdjMCAuNzQxNTczMDMuNjE2NDM4MzYgMS4zNTk1NTA1NiAxLjM1NjE2NDM4IDEuMzU5NTUwNTYuNzM5NzI2MDMgMCAxLjM1NjE2NDQtLjYxNzk3NzUzIDEuMzU2MTY0NC0xLjM1OTU1MDU2IDAtMS40ODMxNDYwNyAxLjYwMjczOTctMS41NDQ5NDM4MiAxLjc4NzY3MTIyLTEuNTQ0OTQzODIuMTg0OTMxNSAwIDEuNzg3NjcxMjMuMDYxNzk3NzUgMS43ODc2NzEyMyAxLjU0NDk0Mzgydi4zMDg5ODg3NmMwIC42MTc5Nzc1My0uMzA4MjE5MTggMS4xMTIzNTk1NS0uODYzMDEzNyAxLjQyMTM0ODMybC0xLjIzMjg3NjcuNjc5Nzc1MjhjLS42NzgwODIyLjM3MDc4NjUtMS4wNDc5NDUyIDEuMDUwNTYxOC0xLjA0Nzk0NTIgMS43OTIxMzQ4M3YxLjExMjM1OTUyQzExLjE0MzgzNTYzIDE1LjM4MjAyMjUgMTEuNzYwMjczOTYgMTYgMTIuNSAxNmMuNzM5NzI2MDMgMCAxLjM1NjE2NDM4LS42MTc5Nzc1IDEuMzU2MTY0MzgtMS4zNTk1NTA1NnYtLjY3OTc3NTI4bC44NjMwMTM3LS40MzI1ODQyN0MxNi4xMzY5ODYzIDEyLjc4NjUxNjgyIDE3IDExLjMwMzM3MDggMTcgOS42OTY2Mjkydi0uMzcwNzg2NUMxNyA2LjQ4MzE0NjA3IDE0LjcxOTE3ODA4IDUgMTIuNSA1IDEwLjIxOTE3ODA4IDUgOCA2LjQ4MzE0NjA3IDggOS4zMjU4NDI3ek0xMi41IDE3Yy0yIDAtMiAzIDAgM3MyLTMgMC0zeiIvPgo8L3N2Zz4=");']:hover::after{opacity:1 !important;color:#d1d1d1 !important;}

.header-toolbar button span[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNiIgaGVpZ2h0PSIyNiI+CiAgPHBhdGggZmlsbD0iI0ZGRiIgZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNOCA5LjMyNTg0MjdjMCAuNzQxNTczMDMuNjE2NDM4MzYgMS4zNTk1NTA1NiAxLjM1NjE2NDM4IDEuMzU5NTUwNTYuNzM5NzI2MDMgMCAxLjM1NjE2NDQtLjYxNzk3NzUzIDEuMzU2MTY0NC0xLjM1OTU1MDU2IDAtMS40ODMxNDYwNyAxLjYwMjczOTctMS41NDQ5NDM4MiAxLjc4NzY3MTIyLTEuNTQ0OTQzODIuMTg0OTMxNSAwIDEuNzg3NjcxMjMuMDYxNzk3NzUgMS43ODc2NzEyMyAxLjU0NDk0Mzgydi4zMDg5ODg3NmMwIC42MTc5Nzc1My0uMzA4MjE5MTggMS4xMTIzNTk1NS0uODYzMDEzNyAxLjQyMTM0ODMybC0xLjIzMjg3NjcuNjc5Nzc1MjhjLS42NzgwODIyLjM3MDc4NjUtMS4wNDc5NDUyIDEuMDUwNTYxOC0xLjA0Nzk0NTIgMS43OTIxMzQ4M3YxLjExMjM1OTUyQzExLjE0MzgzNTYzIDE1LjM4MjAyMjUgMTEuNzYwMjczOTYgMTYgMTIuNSAxNmMuNzM5NzI2MDMgMCAxLjM1NjE2NDM4LS42MTc5Nzc1IDEuMzU2MTY0MzgtMS4zNTk1NTA1NnYtLjY3OTc3NTI4bC44NjMwMTM3LS40MzI1ODQyN0MxNi4xMzY5ODYzIDEyLjc4NjUxNjgyIDE3IDExLjMwMzM3MDggMTcgOS42OTY2Mjkydi0uMzcwNzg2NUMxNyA2LjQ4MzE0NjA3IDE0LjcxOTE3ODA4IDUgMTIuNSA1IDEwLjIxOTE3ODA4IDUgOCA2LjQ4MzE0NjA3IDggOS4zMjU4NDI3ek0xMi41IDE3Yy0yIDAtMiAzIDAgM3MyLTMgMC0zeiIvPgo8L3N2Zz4=");']::after{content:var(--theme-letter);font-family:"Roboto";text-align:center;color:#fff;font-size:18px;position:absolute;left:9px;top:3px;padding-left:1px;transition:.1s color linear;}

.theme-dark .user-settings-connections .connect-account-btn .connect-account-btn-inner:hover {background-color: var(--hover-color);}

.theme-dark .user-settings-connections .connect-account-btn .connect-account-btn-inner {background-color: var(--main-color);}

.change-log .embed-wrapper .embed{padding: 0;margin: 0;margin-top: 0px !important;border: none;}

.change-log .embed-video-actions-inner{margin-bottom: -20px !important;height: 100% !important;padding-top: 20px !important;border-radius: 0px !important;}

.tooltips .tooltip.tooltip-right[style*="left: 42px; top: 11.5px;"]{display: none !important;}	

.theme-dark .ui-slider .slider-bar{background: #151516;}

.ui-checkbox-wrapper .ui-checkbox.checked polyline{stroke: var(--main-color) !important;}

.user-popout .body .notes:only-child{width: calc(100% - 50px);}

.settings-right .member-roles .member-role{background: var(--main-color) !important;visibility: visible !important;}

.account .avatar-small[style*="172218388880293888"]{background-image:url(https://u.nya.is/jkjuia.png) !important;}

.guilds-wrapper .guilds-error{width: 45px;height: 45px;border-radius: 25px;background: #19191b;line-height: 41px;border: 2px solid var(--main-color);}

.guilds-wrapper .guilds-error:hover{background-color: var(--main-color);}

.tooltip.tooltip-error.tooltip-right:after{border-right-color: var(--main-color);}

.channel-notices .channel-notice.quickswitcher-notice{background: #121213 url(/assets/8fdb69b7684b8e1ecb3fdde909daca41.svg) no-repeat center 35px;padding: 100px 20px 20px;}

.new-messages-indicator.new-messages-indicator-channel.new-messages-indicator-mention{top: -10px;}

.new-messages-indicator.new-messages-indicator-channel.new-messages-indicator-mention.bottom{display: none !important;}

.content{background-color: #19191b !important;}

.message-group .accessory{display: flex;flex-flow: row wrap;}

.message-group .accessory>*:not(:last-of-type){margin-right:10px;}

.message-group .accessory>*{margin-top:5px;}

.reactions{width:100%;flex:100%;order:9999999999;}

.embed-wrapper .embed-color-pill{height:calc(100% - 20px);position:absolute;z-index:1;top:10px;left:6px;border-radius:20px;}

.embed.embed-rich{padding-left:17px;}

.ui-tab-bar-item.selected:hover{background-color:var(--hover-color) !important;}

.ui-tab-bar-item.selected{transition:background-color .1s linear;}

.ui-draggable .guild-role .overflow-ellipsis{text-shadow:1px 0px #000;}

.ui-tab-bar.SIDE .ui-tab-bar-header{font-size:17px;color:var(--main-color);font-weight:800;border-bottom:2px solid;text-align:center;}

.ui-tab-bar.SIDE .ui-tab-bar-separator{display:none;}

.ui-tab-bar.SIDE .ui-tab-bar-item{margin-top:6px;}

.theme-dark .ui-card-primary{border-color:#121213;border-width:2px;}

.ui-button.grey.ghost{background-color:#121213;border:2px solid var(--main-color)}

.ui-button.grey.ghost:hover,.ui-button.brand.ghost{background-color:var(--main-color);color:#fff;border:2px solid var(--main-color)}

.ui-button.white.outlined{border-color:var(--main-color);border-width:2px;}

.ui-button.white.outlined:hover{background-color:var(--main-color);border-color:var(--main-color);}

.theme-dark .ui-settings-notice{background:var(--main-color) !important;}

.theme-dark .ui-hover-card:before{background-color:#121213;border-color:#121213;}

.theme-dark .ui-text-input .input.emoji-alias-input{background-color:#19191b;}

.theme-dark .round-remove-button{background-color:#121213;box-shadow:0 0 0 1px rgb(18, 18, 19),0 1px 5px 0 rgba(0,0,0,.3);}

.theme-dark .round-remove-button:hover{background-color:#161617;box-shadow:0 0 0 1px rgb(18, 18, 19),0 2px 10px 0 rgba(0,0,0,.2);}

.theme-dark .guild-settings-members-member .tag{color:#a3a3a3;}

.theme-dark .ui-search-bar{background-color:#151314;}

.theme-dark .ui-color-picker-custom{background:#121213;border-color:#121213;box-shadow:0px 0px 7px 0px #000;}

.ui-color-picker-swatch{background-color:var(--main-color);}

.overflow-ellipsis.user-select-text.ui-flex-child.size-medium.color-primary.font-family-code, .invite-settings-invite-row .countdown-never{opacity:1 !important;}

.theme-dark .ui-form-title.h5{color:var(--main-color);}

.prune-red-link:link{opacity:1;}

.ui-quick-select-popout{background-color:#151314;color:#ffffff;box-shadow:0px 0px 6px 0px #000;}

.theme-light .ui-scroller-wrap:not(.ui-scroller-wrap-dark) .scroller::-webkit-scrollbar-thumb, .ui-scroller-wrap-light .scroller::-webkit-scrollbar-thumb{background-color:var(--main-color);}

.theme-light .ui-scroller-wrap:not(.ui-scroller-wrap-dark) .scroller::-webkit-scrollbar-track-piece, .ui-scroller-wrap-light .scroller::-webkit-scrollbar-track-piece{background-color:#111111;}

.ui-quick-select-popout-option:hover{background-color:#111111;}

.theme-dark .ui-quick-select-label{opacity:1;color:var(--main-color);font-weight:800;color: #fff;text-transform: capitalize;}

/* Notifications */
.theme-light .ui-tab-bar-item:nth-of-type(13),
.theme-light div.platform-osx .ui-tab-bar-item:nth-of-type(14),
.theme-light div.platform-win .ui-tab-bar-item:nth-of-type(14){color: #fff !important;animation: tab-pulse 1.5s infinite, FColorPulse 1.5s infinite;}
@-webkit-keyframes FColorPulse {
	0% {
		background: var(--hover-color);
	}
	50% {
		background: var(--main-color);
	}
	100% {
		background: var(--hover-color);
	}
}
@keyframes tab-pulse {
	0% {
		box-shadow: 0 0 0 0 var(--main-color);
	}
	70% {
		box-shadow: 0 0 10px 10px rgba(241, 71, 71, 0);
	}
	to {
		box-shadow: 0 0 0 0 rgba(241, 71, 71, 0);
	}
}

.ui-button.brand.filled:not(.disabled):active{background-color: var(--hover-color);}

.ui-guild-nsfw .ui-button.filled::after{content: "Jesus is watching you";color: #fff;background: var(--main-color);width: 100%;height: 100%;position: absolute;top: 65px;right: 50%;line-height: 40px;padding-left: 10px;padding-right: 10px;border-radius: 3px;opacity: 0;transition: .2s all linear;}

.ui-guild-nsfw .ui-button.filled:hover::after{opacity: 1;}

.embed-wrapper .embed{padding-left: 18px;}

.ui-switch-wrapper:not(.disabled):not(.clear):hover .ui-switch-checkbox:checked+.ui-switch{background: var(--hover-color);}

.bd-blue #instant-invite-modal .copy, .bd-blue #oauth2-authorize .scope-bot .avatar-large, .bd-blue #overlay-wrapper .overlay .guild-panel .guild-panel-header, .bd-blue #settings-roles .roles li.selected:before, .bd-blue #unsupported-browser li:hover .btn, .bd-blue #user-profile-modal .btn, .bd-blue #user-profile-modal .guilds .avatar-large, .bd-blue .avatar-uploader-inner, .bd-blue .btn-filled, .bd-blue .button, .bd-blue .change-log .changelog-button .cta, .bd-blue .change-log .changelog-fixed, .bd-blue .channel-members .invite-btn, .bd-blue .channel-textarea-guard button, .bd-blue .chat .new-messages-bar:hover, .bd-blue .checkbox .checkbox-inner input[type=checkbox]:checked+span, .bd-blue .detected-platform-accounts-modal .btn-group .btn-primary, .bd-blue .download-apps .platforms .platform.active .download-button, .bd-blue .emoji-picker .premium-promo .btn, .bd-blue .form .btn-primary, .bd-blue .guild-channels .channel-text.unread:not(.selected):not(.channel-muted).selected:before, .bd-blue .guild-channels .channel-voice-states li.speaking .avatar-small, .bd-blue .invite-banner, .bd-blue .invite-header .invite-guild-icon, .bd-blue .invite-mobile .link.purple, .bd-blue .invite-mobile .top, .bd-blue .invite-modal .avatar-xxxlarge, .bd-blue .mention:hover, .bd-blue .modal-new-user .steps-wrap .steps li.active, .bd-blue .modal-new-user .steps-wrap .steps li.on:before, .bd-blue .overlay-user-popout .user-popout-options .btn, .bd-blue .premium-payment-modal, .bd-blue .premium-payment-modal .premium-payment-button .spinner .spinner-item, .bd-blue .private-channel-recipients-invite .footer button, .bd-blue .private-channel-recipients-invite .footer button:disabled:hover, .bd-blue .progress .progress-bar, .bd-blue .react-datepicker .react-datepicker__day.react-datepicker__day--today:after, .bd-blue .react-datepicker .react-datepicker__day:hover, .bd-blue .region-select-flag, .bd-blue .region-select:hover button, .bd-blue .search-popout .date-picker .date-picker-hint .hint-value, .bd-blue .spinner-chasing-dots .ui-spinner-item, .bd-blue .spinner-wandering-cubes .ui-spinner-item, .bd-blue .tooltip, .bd-blue .ui-button.brand .ui-spinner-item, .bd-blue .ui-button.brand.filled, .bd-blue .ui-button.brand.filled:disabled, .bd-blue .ui-button.brand.outlined:active, .bd-blue .ui-scroller-wrap .scrollbar .thumb:after, .bd-blue .ui-tab-bar.SIDE .ui-tab-bar-item.selected, .bd-blue .ui-tab-bar.SIDE .ui-tab-bar-item:active, .bd-blue .upload-modal, .bd-blue .verify-connected-account .btn, .bd-blue #oauth2-authorize .authorize-inner footer button.primary, .bd-blue #oauth2-authorize .authorize-inner header, .bd-blue .now-playing, .bd-blue .private-channel-recipients-invite .error-state.not-friends .btn, .bd-blue .ui-bot-tag, .bd-blue .ui-checkbox-wrapper .ui-checkbox.checked.inverted, .bd-blue .ui-region-flag.vip:after, .bd-blue .ui-slider .slider-bar-fill, .bd-blue .ui-switch-checkbox:checked+.ui-switch {background-color: var(--main-color) !important;}

.bd-blue #autocomplete-popout .empty h4, .bd-blue #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary .badge, .bd-blue #instant-invite-modal .clipboard-input-inner input, .bd-blue #overlay-wrapper .overlay .guild-panel .btn-call, .bd-blue #rtc-debug-modal #users-section .user-list li.selected:before, .bd-blue #settings-roles .roles li.selected:before, .bd-blue .chat .has-more button, .bd-blue .chat .welcome-message h1, .bd-blue .color-brand, .bd-blue .create-guild-container .action.create .action-header, .bd-blue .create-guild-container .join-server .sample-link, .bd-blue .create-guild-container h5, .bd-blue .download-apps .footer a, .bd-blue .form .form-header, .bd-blue .form header, .bd-blue .guild-settings-modal-overview a, .bd-blue .invite-banner .instant-invite:not(.clipboard-input-copied) .clipboard-input-inner button, .bd-blue .invite-marketing .invite-marketing-button, .bd-blue .invite-marketing .invite-marketing-header, .bd-blue .markdown-modal .markdown-modal-header b, .bd-blue .mention, .bd-blue .mentioned .mention:hover, .bd-blue .message-group .edit-message .edit-operation>a, .bd-blue .messages-popout-wrap .has-more button, .bd-blue .modal-new-user h5, .bd-blue .modal-new-user>.steps .step-3 .instant-invite input, .bd-blue .notice.notice-brand .btn:hover, .bd-blue .onboarding-navigation .button, .bd-blue .onboarding-slide.mic-test .content.waiting .button, .bd-blue .popout-menu .popout-menu-item.invite, .bd-blue .premium-payment-modal .premium-payment-button, .bd-blue .reaction.reaction-me .reaction-count, .bd-blue .region-select button, .bd-blue .region-select-modal .region-select-modal-header, .bd-blue .tab-bar.TOP .tab-bar-item.selected, .bd-blue .theme-blurple .ui-button.primary.filled, .bd-blue .theme-blurple .ui-form-title.h5, .bd-blue .theme-blurple .ui-select .Select-menu-outer .Select-option, .bd-blue .theme-blurple .ui-select .Select-value-label, .bd-blue .theme-blurple .ui-text-input .input, .bd-blue .theme-dark #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary .badge, .bd-blue .theme-dark #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary.selected, .bd-blue .theme-dark .reaction.reaction-me .reaction-count, .bd-blue .tutorial-popout .button-area .skip-tips a, .bd-blue .ui-bot-tag.invert, .bd-blue .ui-button.brand.ghost, .bd-blue .ui-button.brand.inverted, .bd-blue .ui-button.brand.link, .bd-blue .ui-button.brand.outlined, .bd-blue .ui-button.brand.outlined:disabled, .bd-blue .ui-new-terms-modal .title, .bd-blue .ui-tab-bar.SIDE .ui-tab-bar-item.brand, .bd-blue .user-settings-modal-account .discord-tag, .bd-blue .webkhook-modal-header.ui-form-title.h5 {color: var(--main-color) !important;}

.bd-blue .guild-channels .channel-text.selected:before, .bd-blue .guild-channels .channel-text:hover:not(.unread):before {border-left: 2px solid var(--main-color) !important;}

.bd-blue .bot-tag, .bd-blue .note textarea::selection {background-color: var(--main-color) !important;}

.bd-blue .user-popout .header{background-color: #141417 !important;}

.bd-blue .popout.popout-right header:before, .bd-blue .tooltip.tooltip-right:after {border-right-color: var(--main-color);}

.bd-blue .bot-tag.bot-tag-invert{color: #fff!important;}

.bd-blue [style*="background-color: rgb(114, 137, 218)"]{background-color: var(--main-color) !important;}

.bd-server-card.bd-server-card-pinned:after {display: none;}

.ui-standard-sidebar-view .bda-slist li:nth-child(odd){background: #161617;border-top: 0px solid transparent;}

.ui-standard-sidebar-view .bda-slist li{background: #161617;border-bottom: 0px solid transparent;margin-top: 7px;box-shadow: 0px 0px 3px 0px #161617;transform: scale(0.99);transition: .2s all linear;}

.ui-standard-sidebar-view .bda-slist li:hover{transform: scale(1);box-shadow: 0px 0px 6px 0px #161617;}

.ui-standard-sidebar-view .bda-slist .bda-right button{background: var(--main-color);border-radius: 3px;}

.bda-slist p,.bda-slist h3, .bda-slist {color: #fff !important;}

.bda-slist button {color: #fff !important;background: var(--main-color);padding: 4px;border-radius: 3px;margin-left: 7px;transition: .2s background linear;}

.bda-slist button:hover {background: var(--hover-color);}

.bda-slist input {background: var(--hover-color);color: #fff;border-color: transparent;margin-top: 20px;padding: 3px;border-radius: 3px;}

#bd-customcss-detach-container .CodeMirror, #bd-customcss-detach-container .cm-s-material .CodeMirror-gutters, .content-region .CodeMirror, .content-region .cm-s-material .CodeMirror-gutters, #bd-customcss-detach-container #bd-customcss-attach-controls, .content-region #bd-customcss-attach-controls {background: #161617 !important;}

.bd-detached-css-editor #bd-customcss-attach-controls button, .ui-standard-sidebar-view #bd-customcss-attach-controls button{background: var(--main-color) !important;border-right: 0px solid transparent !important;border-radius: 3px !important;border-left: 0px solid transparent !important; margin-left: 5px;}

.bd-blue .checkbox .checkbox-inner input[type=checkbox]:checked+span, .bd-blue .checkbox .checkbox-inner.alt input[type=checkbox]:checked+span:after, .bd-blue .download-apps .platforms .platform.active{border-color: var(--main-color);}

.bd-blue .need-help-modal .header{background-color: transparent !important;}

.theme-dark .private-channels .ui-scroller-wrap.ui-scroller-track>.scroller::-webkit-scrollbar-track, .theme-light .ui-scroller-themed.ui-scroller-dark.ui-scroller-track>.scroller::-webkit-scrollbar-track, .ui-scroller-themed.ui-scroller-dark.ui-scroller-track>.scroller::-webkit-scrollbar-track{background-color: #121213;}

.theme-dark .private-channels .ui-scroller-wrap .scroller::-webkit-scrollbar-thumb, .theme-light .ui-scroller-themed.ui-scroller-dark .scroller::-webkit-scrollbar-thumb, .ui-scroller-themed.ui-scroller-dark .scroller::-webkit-scrollbar-thumb{background-color: var(--main-color);}

.deprecated-settings-modal .settings-inner{background-color: #19191b;}

.deprecated-settings-modal .settings-actions{background-color: #19191b;border-top: 2px solid var(--hover-color);}

.theme-dark .ui-scroller-themed.ui-scroller-light.ui-scroller-track>.scroller::-webkit-scrollbar-track, .theme-light .ui-scroller-wrap.ui-scroller-track>.scroller::-webkit-scrollbar-track, .ui-scroller-themed.ui-scroller-light.ui-scroller-track>.scroller::-webkit-scrollbar-track{background-color: #0f0f10;}

.theme-dark .ui-scroller-themed.ui-scroller-light .scroller::-webkit-scrollbar-thumb, .theme-light .ui-scroller-wrap .scroller::-webkit-scrollbar-thumb, .ui-scroller-themed.ui-scroller-light .scroller::-webkit-scrollbar-thumb{background-color: var(--main-color);}

#user-profile-modal .header .header-info .profile-badge{position: absolute;left: 3px;bottom: 0px;}

.theme-dark .search-results-wrap .search-result.expanded .search-result-message.hit:last-of-type{border-bottom: 2px solid rgba(0, 0, 0, 0.45) !important;}

.theme-dark .search-results-wrap .search-result.expanded .search-result-message:last-of-type{border-bottom: 2px solid #19191b;}

.theme-dark .search-results-wrap .action-buttons .jump-button{background-color: var(--main-color);color: #fff;transition: .2s background-color linear;}

.theme-dark .search-results-wrap .action-buttons .jump-button:hover{background-color: var(--hover-color);}

.search-result.expanded .jump-button{background-color: var(--hover-color) !important;}

.tooltips .tooltip{text-shadow: 0px 1px 3px #000}

.user-popout-kick-body{color: #ffffff;}

.modal-content{background-color: transparent;}

.theme-light .ui-text-input .input.editable:focus:hover, .theme-light .ui-text-input .input.editable:hover:hover, .theme-light .ui-text-input .input:hover{border-color: var(--main-color);border-width: 2px;overflow-y: visible;padding-right: 0px !important;}
	
.theme-light .ui-text-input .input.editable, .theme-light .ui-text-input .input.editable, .theme-light .ui-text-input .input{overflow-y: hidden;padding-right: 0px !important;}

.theme-light .ui-text-input .input, .theme-light .ui-text-input .input.editable:focus, .theme-light .ui-text-input .input.editable:hover{color: #c4c4c4;}

.form .control-group label{color: var(--main-color) !important;}

.ui-text-area-max-length{color: #c51616;font-weight: 900;font-size: 13px;position: static;}

.ui-text-area-max-length::before{content: "Characters Left: ";color: var(--hover-color);font-weight: 900;font-size: 13px;}

.channel-textarea.channel-textarea-disabled .channel-textarea-inner textarea::-webkit-input-placeholder{color: #e74c3c !important;font-weight: 900;}

.channel-textarea.channel-textarea-disabled{opacity: 1;}

.theme-dark .channel-textarea-emoji{position: relative;}

.bd-pfbtn{background-color: var(--main-color);border-radius: 3px;transition: background .2s linear;}

.bd-pfbtn:hover{background-color: var(--hover-color);}

._3Mv0RaJ0{background-color: var(--main-color);color: #fff !important;}

._3Mv0RaJ0:hover{background-color: var(--hover-color);}

.theme-dark .ui-popout-list{background:#141416;}

.theme-dark .elevation-border-high{box-shadow:0 0 6px 1px rgba(6, 8, 11, 0.6), 0 2px 10px 0 rgba(0,0,0,.2);}

.ui-selectable-item.selected, .theme-dark .ui-selectable-item:active{background:var(--main-color) !important;}

.theme-dark .ui-selectable-item:active{background:var(--main-color) !important;color:#fff !important;}

.theme-dark .ui-selectable-item:hover:active{color:#fff !important;}

.theme-dark .ui-selectable-item:hover{background-color:#121213;color:var(--main-color) !important;border:1px solid var(--main-color);}

.theme-dark .ui-selectable-item{border:1px solid transparent;}

.ui-selectable-item.selected:hover{color:#fff !important;}

.theme-dark .ui-audit-log .header, .theme-dark .ui-audit-log.ui-audit-log-expanded .header{background-color:#141416;}

.theme-dark .ui-audit-log{border-color:#141416;}

.theme-dark .ui-audit-log-change-details{background-color:#141416;}

.theme-dark .ui-audit-log .divider{background-color:#1d1d1d;}

.ui-audit-log.ui-audit-log-expanded{box-shadow:0px 0px 6px 0px #0b0b0b;transform:scale(1);}

.ui-audit-log{box-shadow:0px 0px 5px 0px #0b0b0b;transform:scale(0.99);transition:.2s transform linear, .2s box-shadow linear;}

.ui-audit-log:hover{box-shadow:0px 0px 6px 0px #0b0b0b;transform:scale(1);}

.deprecated-settings-modal .settings-header{background-color:#121212;}

.settings-panel h1, .selected-user .scroller-wrap .scroller h3{color:#fff;}

#rtc-debug-modal #users-section .user-list li{color:#cacaca;}

#rtc-debug-modal #users-section .user-list{border-right:2px solid #121212;}

#rtc-debug-modal #users-section .user-list li:hover{background:linear-gradient(90deg,#121212,#19191b);}

#rtc-debug-modal #users-section .user-list li:hover:before{background-color:var(--main-color);}

#rtc-debug-modal #users-section .user-list li:before{width:3px;}

.theme-dark .ui-popout-list .ui-scroller-wrap.ui-scroller-track>.scroller::-webkit-scrollbar-track, .theme-light .ui-popout-list .ui-scroller-themed.ui-scroller-dark.ui-scroller-track>.scroller::-webkit-scrollbar-track, .ui-popout-list .ui-scroller-themed.ui-scroller-dark.ui-scroller-track>.scroller::-webkit-scrollbar-track{background-color:#19191b !important;}

.theme-dark .ui-scroller-wrap .scroller.ui-popout-list-options::-webkit-scrollbar-thumb, .theme-light .ui-scroller-themed.ui-scroller-dark .scroller.ui-popout-list-options::-webkit-scrollbar-thumb, .ui-scroller-themed.ui-scroller-dark .scroller.ui-popout-list-options::-webkit-scrollbar-thumb{background-color:var(--main-color);}

.ui-scroller-wrap .scroller.ui-popout-list-options::-webkit-scrollbar{width:12px;}

.container-RYiLUQ{background-color: #19191b;}

.contentSelectedText-3j5CXt, .contentSelectedVoice-gTtYM9{background-color: #121213;}

.contentHoveredText-2HYGIY, .contentHoveredVoice-3qGNKh:active, .contentSelectedVoice-gTtYM9:active, .userHovered-3tfm93:active{background-color: #151515 !important;}

.containerUserOver-2YhVL6:after{background-color: rgba(2, 2, 2, 0.1);border: 2px solid var(--main-color);}

.unread-23Kvxk{background-color: var(--main-color);}

.ui-scroller-wrap.ui-scroller-ghost-hairline.ui-scroller-themed.ui-scroller-fade .scroller.scroller-NXV0-d::-webkit-scrollbar-thumb{background-color: var(--main-color);}

.private-channels .scroller::-webkit-scrollbar{width: 11px;}

.wrapperDefault-1Dl4SS, .wrapperHovered-1KDCyZ, .wrapperMuted-PmsxPn, .wrapperUnread-450E16{height: 0px;padding-top: 7px;padding-bottom: 20px;}

.avatar-small .status{width: 100%;height: 100%;border-width: 2px !important;right: -2px;bottom: -2px;}

.container-iksrDt{height: 71px;background: #19191b;border-top: 2px solid #212121;width: calc(100% - 18px) !important;position: relative;z-index: 10;color: #fff;border-radius: 0px !important;margin-bottom: -1px;}

[class*="flexChild-"] > [class*="container-"] > [class*="header"]:not(.header-toolbar){border-bottom: 2px solid var(--main-color);height: 48px;}
.private-channels .channel.selected a, .private-channels .channel:hover a{background-color: #121213;}

[class*="scrollerThemed"] [class*="scroller"]::-webkit-scrollbar-thumb{background-color: var(--main-color) !important;}

.wrapper-2ldvyE{color: #fff;background-color: #19191b;border: 2px solid var(--main-color);opacity: 0.8;}

[class*="itemDefaultSelected"]{background-color: var(--main-color);}

[class*="itemDefault"]:hover{background-color: #141415;}

.theme-dark [class*="itemDefaultSelected"]:hover{background-color: var(--hover-color);}

.theme-dark [class*="checked"]{border-color: var(--main-color);background: #19191b;border-width: 2px;}

.theme-dark [class*="checkbox"]{border-width: 2px;}

.need-help-modal.deprecated .header{background-color: transparent;height: 125px;}

.need-help-modal.deprecated .footer{padding: 0px;background-color: transparent;border-top: 0px solid transparent;color:transparent;}

.theme-dark [class*="input-"]:focus{border-color: var(--main-color);}

[class*="buttonBrandFilled"]{color: #fff !important;background-color: var(--main-color);}

[class*="buttonBrandFilledDefault-"]:hover{background-color: var(--hover-color);}

[class*="itemBrand-"]{color: var(--main-color);font-weight: bold;}

[class*="barFill-"]{background: var(--main-color);}

[class*="checked-"]{stroke: var(--main-color);}

[class*="switchWrapperDefaultActive-"]:hover [class*="switch-"][class*="checked-"], .user-settings-notifications .notifications-sound:hover [class*="switch-"]{background: var(--main-color) !important;}

.theme-dark [class*="switch"][class*="checked"]{background: var(--hover-color) !important;}

[class*="nameDefaultText-"], [class*="nameDefaultVoice-"], [class*="nameLockedText-"], [class*="nameLockedVoice-"]{color: #828282;}

[class*="nameMutedText-"], [class*="nameMutedVoice-"]{color: #5a5a5a;}

[class*="nameDefault-"]{color: #a5a5a5;}

.theme-dark [class*="modal-"] [class*="inner-"] [class*="modal-"]{background-color: #0f0f10;box-shadow: 0px 0px;}

.theme-dark [class*="footer-"]{box-shadow: 0px 0px;border-top: 2px solid var(--main-color);}

.container-3lnMWU{background: #19191b;border-bottom: 0px solid transparent;box-shadow: 4px -1px 16px -1px rgba(0, 0, 0, 0.46);position: relative;z-index: 1;}

.channel-textarea.channel-textarea-disabled textarea{text-align: center;}

.form.deprecated .btn-primary{background-color: var(--main-color);}

.notification-settings-modal .notification-settings-modal-channel-settings-header{background-color: transparent !important;}

.need-help-modal.deprecated{background: transparent !important;}

#bd-settings-sidebar .ui-tab-bar-item.selected{background-color: var(--main-color) !important;}

#bd-settings-sidebar .ui-tab-bar-item.selected{background-color: var(--main-color) !important;}

.buttonBrandGhostDefault-2JCnWW:active, .buttonBrandGhost-1-Lmhc{background-color: var(--main-color);color: #fff;}

.private-channel-recipients-invite .error-state.not-friends .btn{background: var(--main-color);}

.private-channel-recipients-invite .error-state.not-friends .btn:hover{background: var(--hover-color);}

.theme-dark .ui-video{background-color: #19191b;}

.theme-dark .ui-quick-select-popout{background: #151314 !important;}

.theme-dark .ui-quick-select-popout-option:hover{background-color: #1b191a;}

.theme-dark #friends .friends-table .friend-table-add-wrapper .friend-table-add-header .connect-accounts .connect-account-btn-inner:hover{background-color: var(--main-color);}

.scrollerThemed-19vinI.themeLight-1WK0Av.scrollerTrack-3hhmU0>.scroller-fzNley::-webkit-scrollbar-track, .theme-dark .scrollerThemed-19vinI.themeLight-1WK0Av.scrollerTrack-3hhmU0>.scroller-fzNley::-webkit-scrollbar-track, .theme-light .scrollerWrap-2uBjct.scrollerTrack-3hhmU0>.scroller-fzNley::-webkit-scrollbar-track{background-color: #19191b;}

.scrollerThemed-19vinI.themeLight-1WK0Av .scroller-fzNley::-webkit-scrollbar-thumb, .theme-dark .scrollerThemed-19vinI.themeLight-1WK0Av .scroller-fzNley::-webkit-scrollbar-thumb, .theme-light .scrollerWrap-2uBjct .scroller-fzNley::-webkit-scrollbar-thumb{background-color: var(--main-color);}

.popout.popout-top-right section:before, .popout.popout-top section:before{border-top-color: var(--main-color);}

[class*="itemBrandSelected-"]{background-color: var(--main-color);}

.create-guild-container.deprecated .action:hover.create .btn{background-color: var(--hover-color);}

.create-guild-container.deprecated, .create-guild-container.deprecated .create-or-join .form-inner, .theme-dark .form.deprecated .form-inner, .form.deprecated .form-actions{background-color: #0d0d0d !important;}

.form.deprecated header, .create-guild-container.deprecated .action.create .action-header{color: var(--main-color);}

.theme-dark .form.deprecated .form-header{background: #0d0d0e !important;}

.create-guild-container.deprecated .action{background: #0b0b0b;box-shadow: 0px 0px 11px 0px rgb(0, 0, 0);}

.form.deprecated .form-actions {border-top: 2px solid var(--main-color);}

.region-select-modal .region-select-modal-header{background-color: transparent !important;}

.region-select-modal .region-select-modal-options{background-color: transparent !important;}

.form.deprecated .btn-default{background-color: #0d0d0d;border-bottom: 0px solid transparent;}

.create-guild-container.deprecated .form-actions .btn-default{color: #c8c8c8;}

.form.deprecated .btn-default:hover{border-bottom: 0px solid transparent;}

.create-guild-container.deprecated .join-server .sample-link{color: var(--main-color);}

.guilds-wrapper .guilds .guild.selected .guild-inner:not([style*="background-color:"]), .guilds-wrapper .guilds .guild:hover .guild-inner:not([style*="background-color:"]){background-color:#0a0a0a !important;}

.form.deprecated .control-group input[type=email], .form.deprecated .control-group input[type=number], .form.deprecated .control-group input[type=password], .form.deprecated .control-group input[type=text], .form.deprecated .control-group textarea {color: #eaeaea;}

.emoji {margin: 0 !important;}

.theme-dark [class*="cardPrimaryEditable"], .theme-dark [class*="cardPrimary"], .theme-dark [class*="cardPrimaryOutline"], .theme-dark [class*="headerClickable"], .theme-dark [class*="headerDefault"], .theme-dark [class*="headerExpanded"] {background: #171719 !important;border-color: rgba(32, 34, 37, 0) !important;box-shadow: 0px 0px 3px 1px #121212;}

.theme-dark [class*="changeDetails"] {background: #19191b !important;border-color: rgba(32, 34, 37, 0) !important;box-shadow: 0px 0px 3px 1px #121212;}

.theme-dark .layer, .theme-dark .layers, body{background: #19191b !important;}

.modal-image{background: transparent !important;}

.channel-text-area-default{margin: 12px 0 14px;}
	
.theme-dark [class*="attachButtonDivider-"]{background-color:transparent;}

.platform-osx .titlebar{width: 100%;height: 25px;absolute;top: 0;right: 0;left: 0;}

.platform-osx .titlebar .osx-buttons{position: absolute;top: 17px;left: initial;right: 15px;}

.platform-osx .title-wrap{padding: 0 85px 0 0;}

.platform-osx .guilds-wrapper{padding: 50px 0 0 0;}

.platform-osx .guilds-wrapper .guilds{height: calc(100% - 95px);}

.platform-osx .channel-notices .channel-notice{margin: 10px 0 0 0;}

.platform-osx .popout.popout-bottom[style*="top: 48px"]{background: none; /* you need this because the server settings looks weird when a QuickSwitcher exists on top of the channels list*/}

.theme-dark [class*="autocomplete-"]{background-color:#19191b;box-shadow:0px 0px 6px 0px #101010;border-radius:3px !important;margin-bottom:20px !important;animation:opacity-autocomplete 200ms;}

@keyframes opacity-autocomplete{0%{opacity:0;}

100%{opacity:1;}

}

.theme-dark [class*="selectorSelected-"]{background-color:#141414;}

.ui-standard-sidebar-view #bd-settingspane-container .content-column.default .ui-form-title.h2::after{display:block;position:relative;background:var(--main-color);padding:10px 15px;white-space:pre;margin-bottom:-10px;margin-top:15px;border-radius:2px;box-shadow:0 2px 10px rgba(0, 0, 0, .2);font-weight:600;color:#fff;text-transform:initial;text-align:center;}

.ui-standard-sidebar-view #bd-settingspane-container .content-column.default .bda-slist::before{display:block;position:relative;background:#43B581;padding:10px 15px;white-space:pre;margin-bottom:10px;border-radius:2px;box-shadow:0 2px 10px rgba(0, 0, 0, .2);font-weight:600;margin-top:2px;color:#fff;text-transform:initial;}

.ui-standard-sidebar-view #bd-settingspane-container .content-column.default .ui-form-title.h2+.bd-pfbtn{top:60px;position:absolute;left:120px;background:var(--main-color);font-weight:600;}

.bd-pfbtn{margin-bottom:5px;box-shadow:0 6px 10px rgba(0, 0, 0, .0);transition:all 200ms ease;border-radius:3px;}

.ui-standard-sidebar-view #bd-settingspane-container .content-column.default{position:relative;}

.content-region #bd-customcss-attach-controls::after{width:100%;padding:10px;content:"To change the default colors just copy and paste the code below\A and replace the hex codes with your own. (those are my colors)\A \A:root{\A --main-color:#e91e63 !important;\A --hover-color:#b81147 !important;\A}\A\A To add custom options to the theme, copy the following code from\A my server and place the options you want in the box above.\A\A Don't forget to save/update when you're done!\A";background:#43B581;margin-top:10px;display:block;border-radius:2px;font-family:Consolas, Liberation Mono, Menlo, Courier, monospace;white-space:pre;color:#fff;margin-bottom:0px;width:auto;}

/*settings icons*/
.user-settings-modal .tab-bar.SIDE .tab-bar-item::before {
    opacity: 1!important;
    border-left: 0px;
    margin-top: 4px;
    transition: all 100ms ease;
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVDMTQuNDYgMi4xOCAxNC4yNSAyIDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz48L3N2Zz4=);
    -ms-transform: translate(0, 2px);
    transform: translate(0, 2px)
}
.layer[layer-id="user-settings"] #bd-settings-sidebar .ui-tab-bar-item,
.item-3879bf,
.ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item{
    display:flex;
}
.layer[layer-id="user-settings"] #bd-settings-sidebar .ui-tab-bar-item::before,
.layer[layer-id="server-settings"] .item-3879bf::before,
.layer[layer-id="user-settings"] .item-3879bf::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item::before{
    transition: all 100ms ease;
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVDMTQuNDYgMi4xOCAxNC4yNSAyIDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz48L3N2Zz4=);
    display:block;
    height:0px;
    top:-4px;
    margin-right:5px;
    position:relative;
    -ms-transform: translate(0, 2px);
    transform: translate(0, 2px);
    opacity:0.7;
}
.layer[layer-id="user-settings"] #bd-settings-sidebar .ui-tab-bar-item.selected::before,
.layer[layer-id="server-settings"] .item-3879bf.itemDefaultSelected-1UAWLe::before,
.layer[layer-id="user-settings"] .item-3879bf.itemDefaultSelected-1UAWLe::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item.selected::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item.selected::before{
    opacity:1;
}
.layer[layer-id="user-settings"] #bd-settings-sidebar .ui-tab-bar-item:hover::before,
.layer[layer-id="server-settings"] .item-3879bf:hover::before,
.layer[layer-id="user-settings"] .item-3879bf:hover::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:hover::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:hover::before{
    opacity:1;
}
/*account*/
.layer[layer-id="user-settings"] .item-3879bf:nth-of-type(2)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(2)::before,
.user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(2)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTEyIDEyYzIuMjEgMCA0LTEuNzkgNC00cy0xLjc5LTQtNC00LTQgMS43OS00IDQgMS43OSA0IDQgNHptMCAyYy0yLjY3IDAtOCAxLjM0LTggNHYyaDE2di0yYzAtMi42Ni01LjMzLTQtOC00eiIvPiAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PC9zdmc+);
}
/*nitro*/
.user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(3)::before {
    content: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iLTM3IDM5IDI0IDI0IiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IC0zNyAzOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+LnN0MHtmaWxsOm5vbmU7fS5zdDF7ZmlsbDojRkZGRkZGO308L3N0eWxlPjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tMzcsMzloMjR2MjRoLTI0VjM5eiIvPjxnPjxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0tMTMuNyw1MC4zYy0wLjMtNC43LTQuNC04LjMtOS4yLTguM2gtOWMtMC44LDAtMS41LDAuNy0xLjUsMS41czAuNywxLjUsMS41LDEuNWgxLjFjMC42LDAsMC45LDAuNywwLjYsMS4xYy0wLjEsMC4yLTAuMywwLjMtMC42LDAuM2gtNC42Yy0wLjYsMC0xLDAuNC0xLDFjMCwwLjUsMC40LDEsMSwxaDNjMC41LDAsMC45LDAuNCwwLjgsMC45YzAsMCwwLDAsMCwwYy0wLjEsMC40LTAuNCwwLjctMC44LDAuN2gtMS41Yy0wLjUsMC0xLDAuNS0xLDFzMC41LDEsMSwxaDIuMWMwLjUsNC41LDQuMyw4LDguOSw4Qy0xNy41LDYwLTEzLjMsNTUuNi0xMy43LDUwLjN6IE0tMjIuNyw1Ni4yYy0yLjgsMC01LjEtMi4zLTUuMS01LjJzMi4zLTUuMiw1LjEtNS4yYzIuOSwwLDUuMiwyLjMsNS4yLDUuMlMtMTkuOCw1Ni4yLTIyLjcsNTYuMnoiLz48cG9seWdvbiBjbGFzcz0ic3QxIiBwb2ludHM9Ii0xOSw1MSAtMjAuOCw1NC4yIC0yNC41LDU0LjIgLTI2LjMsNTEgLTI0LjUsNDcuOCAtMjAuOCw0Ny44ICIvPjwvZz48L3N2Zz4=);
}
.layer[layer-id="user-settings"] .item-3879bf:nth-of-type(7)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(7)::before {
    content: "|";
    width: 24px;
    height: 0px;
    font-family:BMTicons,Whitney,Helvetica Neue,Helvetica,Arial,sans-serif;
    color:var(--main-color);
    font-size:23px;
    transform:translate(0,4px);
}
.layer[layer-id="user-settings"] .item-3879bf:active:nth-of-type(7)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:active:nth-of-type(7)::before,
.layer[layer-id="user-settings"] .item-3879bf.selected-eNoxEK:nth-of-type(7)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item.selected:nth-of-type(7)::before {
    width: 24px;
    height: 0px;
    font-family:BMTicons,Whitney,Helvetica Neue,Helvetica,Arial,sans-serif;
    color:#fff;
    font-size:23px;
    transform:translate(0,4px);
    transition:0ms!important;
}
/*connections*/
.layer[layer-id="user-settings"] .item-3879bf:nth-of-type(5)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(5)::before,
.user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(4)::before {
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMy45IDEyYzAtMS43MSAxLjM5LTMuMSAzLjEtMy4xaDRWN0g3Yy0yLjc2IDAtNSAyLjI0LTUgNXMyLjI0IDUgNSA1aDR2LTEuOUg3Yy0xLjcxIDAtMy4xLTEuMzktMy4xLTMuMXpNOCAxM2g4di0ySDh2MnptOS02aC00djEuOWg0YzEuNzEgMCAzLjEgMS4zOSAzLjEgMy4xcy0xLjM5IDMuMS0zLjEgMy4xaC00VjE3aDRjMi43NiAwIDUtMi4yNCA1LTVzLTIuMjQtNS01LTV6Ii8+PC9zdmc+);
}
/*privacy and safety*/
.layer[layer-id="user-settings"] .item-3879bf:nth-of-type(3)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(3)::before,
.user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(5)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTggOGgtMVY2YzAtMi43Ni0yLjI0LTUtNS01UzcgMy4yNCA3IDZ2Mkg2Yy0xLjEgMC0yIC45LTIgMnYxMGMwIDEuMS45IDIgMiAyaDEyYzEuMSAwIDItLjkgMi0yVjEwYzAtMS4xLS45LTItMi0yem0tNiA5Yy0xLjEgMC0yLS45LTItMnMuOS0yIDItMiAyIC45IDIgMi0uOSAyLTIgMnptMy4xLTlIOC45VjZjMC0xLjcxIDEuMzktMy4xIDMuMS0zLjEgMS43MSAwIDMuMSAxLjM5IDMuMSAzLjF2MnoiLz48L3N2Zz4=);
}
/*text & images*/
.layer[layer-id="user-settings"] .item-3879bf:nth-of-type(13)::before,
div.platform-osx .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(14)::before,
div.platform-win .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(15)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(13)::before,
div.platform-osx .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(14)::before,
div.platform-win .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(15)::before,
.user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(6)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTIwIDJINGMtMS4xIDAtMS45OS45LTEuOTkgMkwyIDIybDQtNGgxNGMxLjEgMCAyLS45IDItMlY0YzAtMS4xLS45LTItMi0yek02IDloMTJ2Mkg2Vjl6bTggNUg2di0yaDh2MnptNC02SDZWNmgxMnYyeiIvPiAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PC9zdmc+);
}
/*voice*/
.layer[layer-id="user-settings"] .item-3879bf:nth-of-type(10)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(10)::before,
.user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(7)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTEyIDE0YzEuNjYgMCAyLjk5LTEuMzQgMi45OS0zTDE1IDVjMC0xLjY2LTEuMzQtMy0zLTNTOSAzLjM0IDkgNXY2YzAgMS42NiAxLjM0IDMgMyAzem01LjMtM2MwIDMtMi41NCA1LjEtNS4zIDUuMVM2LjcgMTQgNi43IDExSDVjMCAzLjQxIDIuNzIgNi4yMyA2IDYuNzJWMjFoMnYtMy4yOGMzLjI4LS40OCA2LTMuMyA2LTYuNzJoLTEuN3oiLz4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjwvc3ZnPg==);
}
/*notifications*/
.layer[layer-id="user-settings"] .item-3879bf:nth-of-type(11)::before,
div.platform-osx .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(11)::before,
div.platform-win .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(12)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(11)::before,
div.platform-osx .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(11)::before,
div.platform-win .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(12)::before,
.user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(8)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTEyIDIyYzEuMSAwIDItLjkgMi0yaC00YzAgMS4xLjg5IDIgMiAyem02LTZ2LTVjMC0zLjA3LTEuNjQtNS42NC00LjUtNi4zMlY0YzAtLjgzLS42Ny0xLjUtMS41LTEuNXMtMS41LjY3LTEuNSAxLjV2LjY4QzcuNjMgNS4zNiA2IDcuOTIgNiAxMXY1bC0yIDJ2MWgxNnYtMWwtMi0yeiIvPjwvc3ZnPg==);
}
/*keybinds*/
.layer[layer-id="user-settings"] .item-3879bf:nth-of-type(12)::before,
div.platform-osx .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(12)::before,
div.platform-win .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(13)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(12)::before,
div.platform-osx .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(12)::before,
div.platform-win .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(13)::before,
div.platform-osx .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(9)::before,
div.platform-win .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(9)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTIwIDVINGMtMS4xIDAtMS45OS45LTEuOTkgMkwyIDE3YzAgMS4xLjkgMiAyIDJoMTZjMS4xIDAgMi0uOSAyLTJWN2MwLTEuMS0uOS0yLTItMnptLTkgM2gydjJoLTJWOHptMCAzaDJ2MmgtMnYtMnpNOCA4aDJ2Mkg4Vjh6bTAgM2gydjJIOHYtMnptLTEgMkg1di0yaDJ2MnptMC0zSDVWOGgydjJ6bTkgN0g4di0yaDh2MnptMC00aC0ydi0yaDJ2MnptMC0zaC0yVjhoMnYyem0zIDNoLTJ2LTJoMnYyem0wLTNoLTJWOGgydjJ6Ii8+ICAgIDxwYXRoIGQ9Ik0wIDBoMjR2MjRIMHptMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PC9zdmc+);
}
/*appearance*/
.layer[layer-id="user-settings"] .item-3879bf:nth-of-type(14)::before,
div.platform-osx .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(15)::before,
div.platform-win .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(16)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(14)::before,
div.platform-osx .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(15)::before,
div.platform-win .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(16)::before,
.user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(9)::before,
div.platform-win .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(10)::before,
div.platform-osx .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(10)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTEyIDNjLTQuOTcgMC05IDQuMDMtOSA5czQuMDMgOSA5IDljLjgzIDAgMS41LS42NyAxLjUtMS41IDAtLjM5LS4xNS0uNzQtLjM5LTEuMDEtLjIzLS4yNi0uMzgtLjYxLS4zOC0uOTkgMC0uODMuNjctMS41IDEuNS0xLjVIMTZjMi43NiAwIDUtMi4yNCA1LTUgMC00LjQyLTQuMDMtOC05LTh6bS01LjUgOWMtLjgzIDAtMS41LS42Ny0xLjUtMS41UzUuNjcgOSA2LjUgOSA4IDkuNjcgOCAxMC41IDcuMzMgMTIgNi41IDEyem0zLTRDOC42NyA4IDggNy4zMyA4IDYuNVM4LjY3IDUgOS41IDVzMS41LjY3IDEuNSAxLjVTMTAuMzMgOCA5LjUgOHptNSAwYy0uODMgMC0xLjUtLjY3LTEuNS0xLjVTMTMuNjcgNSAxNC41IDVzMS41LjY3IDEuNSAxLjVTMTUuMzMgOCAxNC41IDh6bTMgNGMtLjgzIDAtMS41LS42Ny0xLjUtMS41UzE2LjY3IDkgMTcuNSA5czEuNS42NyAxLjUgMS41LS42NyAxLjUtMS41IDEuNXoiLz4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjwvc3ZnPg==);
}
/*games*/
div.platform-osx .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(13)::before,
div.platform-win .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(14)::before,
div.platform-osx .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(13)::before,
div.platform-win .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(14)::before,
div.platform-win .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(11)::before,
div.platform-osx .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(11)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTUgNy41VjJIOXY1LjVsMyAzIDMtM3pNNy41IDlIMnY2aDUuNWwzLTMtMy0zek05IDE2LjVWMjJoNnYtNS41bC0zLTMtMyAzek0xNi41IDlsLTMgMyAzIDNIMjJWOWgtNS41eiIvPjwvc3ZnPg==);
}
/*overlay*/
.layer[layer-id="user-settings"] .item-3879bf:nth-of-type(11)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(11)::before,
div.platform-win .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(12)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMjEgMkgzYy0xLjEgMC0yIC45LTIgMnYxMmMwIDEuMS45IDIgMiAyaDd2Mkg4djJoOHYtMmgtMnYtMmg3YzEuMSAwIDItLjkgMi0yVjRjMC0xLjEtLjktMi0yLTJ6bTAgMTRIM1Y0aDE4djEyeiIvPjwvc3ZnPg==);
}
/*locale*/
.layer[layer-id="user-settings"] .item-3879bf:nth-of-type(16)::before,
div.platform-osx .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(17)::before,
div.platform-win .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(18)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(16)::before,
div.platform-osx .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(17)::before,
div.platform-win .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(18)::before,
.user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(10)::before,
div.platform-osx .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(12)::before,
div.platform-win .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(13)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTEuOTkgMkM2LjQ3IDIgMiA2LjQ4IDIgMTJzNC40NyAxMCA5Ljk5IDEwQzE3LjUyIDIyIDIyIDE3LjUyIDIyIDEyUzE3LjUyIDIgMTEuOTkgMnptNi45MyA2aC0yLjk1Yy0uMzItMS4yNS0uNzgtMi40NS0xLjM4LTMuNTYgMS44NC42MyAzLjM3IDEuOTEgNC4zMyAzLjU2ek0xMiA0LjA0Yy44MyAxLjIgMS40OCAyLjUzIDEuOTEgMy45NmgtMy44MmMuNDMtMS40MyAxLjA4LTIuNzYgMS45MS0zLjk2ek00LjI2IDE0QzQuMSAxMy4zNiA0IDEyLjY5IDQgMTJzLjEtMS4zNi4yNi0yaDMuMzhjLS4wOC42Ni0uMTQgMS4zMi0uMTQgMiAwIC42OC4wNiAxLjM0LjE0IDJINC4yNnptLjgyIDJoMi45NWMuMzIgMS4yNS43OCAyLjQ1IDEuMzggMy41Ni0xLjg0LS42My0zLjM3LTEuOS00LjMzLTMuNTZ6bTIuOTUtOEg1LjA4Yy45Ni0xLjY2IDIuNDktMi45MyA0LjMzLTMuNTZDOC44MSA1LjU1IDguMzUgNi43NSA4LjAzIDh6TTEyIDE5Ljk2Yy0uODMtMS4yLTEuNDgtMi41My0xLjkxLTMuOTZoMy44MmMtLjQzIDEuNDMtMS4wOCAyLjc2LTEuOTEgMy45NnpNMTQuMzQgMTRIOS42NmMtLjA5LS42Ni0uMTYtMS4zMi0uMTYtMiAwLS42OC4wNy0xLjM1LjE2LTJoNC42OGMuMDkuNjUuMTYgMS4zMi4xNiAyIDAgLjY4LS4wNyAxLjM0LS4xNiAyem0uMjUgNS41NmMuNi0xLjExIDEuMDYtMi4zMSAxLjM4LTMuNTZoMi45NWMtLjk2IDEuNjUtMi40OSAyLjkzLTQuMzMgMy41NnpNMTYuMzYgMTRjLjA4LS42Ni4xNC0xLjMyLjE0LTIgMC0uNjgtLjA2LTEuMzQtLjE0LTJoMy4zOGMuMTYuNjQuMjYgMS4zMS4yNiAycy0uMSAxLjM2LS4yNiAyaC0zLjM4eiIvPjwvc3ZnPg==);
}
/*streamer mode*/
.layer[layer-id="user-settings"] .item-3879bf:nth-of-type(15)::before,
div.platform-osx .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(16)::before,
div.platform-win .layer[layer-id="user-settings"] .item-3879bf:nth-of-type(17)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(15)::before,
div.platform-osx .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(16)::before,
div.platform-win .layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(17)::before,
.user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(11)::before,
div.platform-osx .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(13)::before,
div.platform-win .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(14)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTcgMTAuNVY3YzAtLjU1LS40NS0xLTEtMUg0Yy0uNTUgMC0xIC40NS0xIDF2MTBjMCAuNTUuNDUgMSAxIDFoMTJjLjU1IDAgMS0uNDUgMS0xdi0zLjVsNCA0di0xMWwtNCA0eiIvPjwvc3ZnPg==);
}
/*security*/
.user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(12)::before,
div.platform-osx .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(14)::before,
div.platform-win .user-settings-modal .tab-bar.SIDE .tab-bar-item:nth-of-type(15)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTEyIDFMMyA1djZjMCA1LjU1IDMuODQgMTAuNzQgOSAxMiA1LjE2LTEuMjYgOS02LjQ1IDktMTJWNWwtOS00em0wIDEwLjk5aDdjLS41MyA0LjEyLTMuMjggNy43OS03IDguOTRWMTJINVY2LjNsNy0zLjExdjguOHoiLz4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjwvc3ZnPg==);
}
/*authorized apps*/
.layer[layer-id="user-settings"] .item-3879bf:nth-of-type(4)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(4)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTEzIDEzdjhoOHYtOGgtOHpNMyAyMWg4di04SDN2OHpNMyAzdjhoOFYzSDN6bTEzLjY2LTEuMzFMMTEgNy4zNCAxNi42NiAxM2w1LjY2LTUuNjYtNS42Ni01LjY1eiIvPiAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PC9zdmc+);
}
/*betterdiscord core*/
.layer[layer-id="user-settings"] #bd-settings-sidebar .ui-tab-bar-item:nth-of-type(3)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE #bd-settings-sidebar .ui-tab-bar-item:nth-of-type(3)::before{
    content:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IiB2aWV3Qm94PSIwIDAgMjAwMCAyMDAwIiBlbmFibGUtYmFja2dyb3VuZD0ibmV3IDAgMCAyMDAwIDIwMDAiIHhtbDpzcGFjZT0icHJlc2VydmUiPjxnPjxwYXRoIGZpbGw9IiNGRkZGRkYiIGQ9Ik0xNDAyLjIsNjMxLjdjLTkuNy0zNTMuNC0yODYuMi00OTYtNjQyLjYtNDk2SDY4LjR2NzE0LjFsNDQyLDM5OFY0OTAuN2gyNTdjMjc0LjUsMCwyNzQuNSwzNDQuOSwwLDM0NC45SDU5Ny42djMyOS41aDE2OS44YzI3NC41LDAsMjc0LjUsMzQ0LjgsMCwzNDQuOGgtNjk5djM1NC45aDY5MS4yYzM1Ni4zLDAsNjMyLjgtMTQyLjYsNjQyLjYtNDk2YzAtMTYyLjYtNDQuNS0yODQuMS0xMjIuOS0zNjguNkMxMzU3LjcsOTE1LjgsMTQwMi4yLDc5NC4zLDE0MDIuMiw2MzEuN3oiLz48cGF0aCBmaWxsPSIjRkZGRkZGIiBkPSJNMTI2Mi41LDEzNS4yTDEyNjIuNSwxMzUuMmwtNzYuOCwwYzI2LjYsMTMuMyw1MS43LDI4LjEsNzUsNDQuM2M3MC43LDQ5LjEsMTI2LjEsMTExLjUsMTY0LjYsMTg1LjNjMzkuOSw3Ni42LDYxLjUsMTY1LjYsNjQuMywyNjQuNmwwLDEuMnYxLjJjMCwxNDEuMSwwLDU5Ni4xLDAsNzM3LjF2MS4ybDAsMS4yYy0yLjcsOTktMjQuMywxODgtNjQuMywyNjQuNmMtMzguNSw3My44LTkzLjgsMTM2LjItMTY0LjYsMTg1LjNjLTIyLjYsMTUuNy00Ni45LDMwLjEtNzIuNiw0My4xaDcyLjVjMzQ2LjIsMS45LDY3MS0xNzEuMiw2NzEtNTY3LjlWNzE2LjdDMTkzMy41LDMxMi4yLDE2MDguNywxMzUuMiwxMjYyLjUsMTM1LjJ6Ii8+PC9nPjwvc3ZnPg==)!important;
    width:22px;
    padding-left:2px;
    top:-4px;
}
/*betterdiscord emotes*/
.layer[layer-id="user-settings"] #bd-settings-sidebar .ui-tab-bar-item:nth-of-type(4)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE #bd-settings-sidebar .ui-tab-bar-item:nth-of-type(4)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTEuOTkgMkM2LjQ3IDIgMiA2LjQ4IDIgMTJzNC40NyAxMCA5Ljk5IDEwQzE3LjUyIDIyIDIyIDE3LjUyIDIyIDEyUzE3LjUyIDIgMTEuOTkgMnpNMTIgMjBjLTQuNDIgMC04LTMuNTgtOC04czMuNTgtOCA4LTggOCAzLjU4IDggOC0zLjU4IDgtOCA4em0zLjUtOWMuODMgMCAxLjUtLjY3IDEuNS0xLjVTMTYuMzMgOCAxNS41IDggMTQgOC42NyAxNCA5LjVzLjY3IDEuNSAxLjUgMS41em0tNyAwYy44MyAwIDEuNS0uNjcgMS41LTEuNVM5LjMzIDggOC41IDggNyA4LjY3IDcgOS41IDcuNjcgMTEgOC41IDExem0zLjUgNi41YzIuMzMgMCA0LjMxLTEuNDYgNS4xMS0zLjVINi44OWMuOCAyLjA0IDIuNzggMy41IDUuMTEgMy41eiIvPjwvc3ZnPg==);
}
/*betterdiscord custom css*/
.layer[layer-id="user-settings"] #bd-settings-sidebar .ui-tab-bar-item:nth-of-type(5)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE #bd-settings-sidebar .ui-tab-bar-item:nth-of-type(5)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+ICAgIDxwYXRoIGQ9Ik0yMi43IDE5bC05LjEtOS4xYy45LTIuMy40LTUtMS41LTYuOS0yLTItNS0yLjQtNy40LTEuM0w5IDYgNiA5IDEuNiA0LjdDLjQgNy4xLjkgMTAuMSAyLjkgMTIuMWMxLjkgMS45IDQuNiAyLjQgNi45IDEuNWw5LjEgOS4xYy40LjQgMSAuNCAxLjQgMGwyLjMtMi4zYy41LS40LjUtMS4xLjEtMS40eiIvPjwvc3ZnPg==);
    transform:none;
}
/*betterdiscord plugins*/
.layer[layer-id="user-settings"] #bd-settings-sidebar .ui-tab-bar-item:nth-of-type(6)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE #bd-settings-sidebar .ui-tab-bar-item:nth-of-type(6)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMjAuNSAxMUgxOVY3YzAtMS4xLS45LTItMi0yaC00VjMuNUMxMyAyLjEyIDExLjg4IDEgMTAuNSAxUzggMi4xMiA4IDMuNVY1SDRjLTEuMSAwLTEuOTkuOS0xLjk5IDJ2My44SDMuNWMxLjQ5IDAgMi43IDEuMjEgMi43IDIuN3MtMS4yMSAyLjctMi43IDIuN0gyVjIwYzAgMS4xLjkgMiAyIDJoMy44di0xLjVjMC0xLjQ5IDEuMjEtMi43IDIuNy0yLjcgMS40OSAwIDIuNyAxLjIxIDIuNyAyLjdWMjJIMTdjMS4xIDAgMi0uOSAyLTJ2LTRoMS41YzEuMzggMCAyLjUtMS4xMiAyLjUtMi41UzIxLjg4IDExIDIwLjUgMTF6Ii8+PC9zdmc+);
}
/*betterdiscord themes*/
.layer[layer-id="user-settings"] #bd-settings-sidebar .ui-tab-bar-item:nth-of-type(7)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE #bd-settings-sidebar .ui-tab-bar-item:nth-of-type(7)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTIuNTMgMTkuNjVsMS4zNC41NnYtOS4wM2wtMi40MyA1Ljg2Yy0uNDEgMS4wMi4wOCAyLjE5IDEuMDkgMi42MXptMTkuNS0zLjdMMTcuMDcgMy45OGMtLjMxLS43NS0xLjA0LTEuMjEtMS44MS0xLjIzLS4yNiAwLS41My4wNC0uNzkuMTVMNy4xIDUuOTVjLS43NS4zMS0xLjIxIDEuMDMtMS4yMyAxLjgtLjAxLjI3LjA0LjU0LjE1LjhsNC45NiAxMS45N2MuMzEuNzYgMS4wNSAxLjIyIDEuODMgMS4yMy4yNiAwIC41Mi0uMDUuNzctLjE1bDcuMzYtMy4wNWMxLjAyLS40MiAxLjUxLTEuNTkgMS4wOS0yLjZ6TTcuODggOC43NWMtLjU1IDAtMS0uNDUtMS0xcy40NS0xIDEtMSAxIC40NSAxIDEtLjQ1IDEtMSAxem0tMiAxMWMwIDEuMS45IDIgMiAyaDEuNDVsLTMuNDUtOC4zNHY2LjM0eiIvPiAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PC9zdmc+);
}
/*changelog*/
.layer[layer-id="user-settings"] .item-3879bf:nth-last-of-type(5)::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-last-of-type(5)::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTkgM2gtNC4xOEMxNC40IDEuODQgMTMuMyAxIDEyIDFjLTEuMyAwLTIuNC44NC0yLjgyIDJINWMtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxNGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yem0tNyAwYy41NSAwIDEgLjQ1IDEgMXMtLjQ1IDEtMSAxLTEtLjQ1LTEtMSAuNDUtMSAxLTF6bTIgMTRIN3YtMmg3djJ6bTMtNEg3di0yaDEwdjJ6bTAtNEg3VjdoMTB2MnoiLz48L3N2Zz4=);
}
/*log out*/
.layer[layer-id="user-settings"] .item-3879bf:nth-last-of-type(3):not([data-reactid])::before,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-last-of-type(3):not([data-reactid])::before {
    content: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjZjA0NzQ3IiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTAuMDkgMTUuNTlMMTEuNSAxN2w1LTUtNS01LTEuNDEgMS40MUwxMi42NyAxMUgzdjJoOS42N2wtMi41OCAyLjU5ek0xOSAzSDVjLTEuMTEgMC0yIC45LTIgMnY0aDJWNWgxNHYxNEg1di00SDN2NGMwIDEuMS44OSAyIDIgMmgxNGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yeiIvPjwvc3ZnPg==);
    transform:rotate(180deg)translate(0,-26px);
    opacity: 1;
}
.layer[layer-id="user-settings"] .item-3879bf.selected:nth-last-of-type(3):not([data-reactid]),
.layer[layer-id="user-settings"] .item-3879bf:nth-last-of-type(3):not([data-reactid]):active,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item.selected:nth-last-of-type(3):not([data-reactid]),
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-last-of-type(3):not([data-reactid]):active{
    background:#fff;
}
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE #bd-settings-sidebar .ui-tab-bar-item.selected:nth-last-of-type(3):not([data-reactid]),
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE #bd-settings-sidebar .ui-tab-bar-item:nth-last-of-type(3):not([data-reactid]):active,
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE #bd-settings-sidebar .ui-tab-bar-item.selected:nth-last-of-type(3):not([data-reactid]),
.layer[layer-id="user-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE #bd-settings-sidebar .ui-tab-bar-item:nth-last-of-type(3):not([data-reactid]):active{
    background:var(--main-color);
}
/*-SERVER SETTINGS-*/
/*Overview*/
.layer[layer-id="server-settings"] .item-3879bf:nth-of-type(2)::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(2)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMyAxM2g4VjNIM3YxMHptMCA4aDh2LTZIM3Y2em0xMCAwaDhWMTFoLTh2MTB6bTAtMTh2Nmg4VjNoLTh6Ii8+PC9zdmc+);
}
/*Moderation*/
.layer[layer-id="server-settings"] .item-3879bf:nth-of-type(3)::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(3)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTEyIDFMMyA1djZjMCA1LjU1IDMuODQgMTAuNzQgOSAxMiA1LjE2LTEuMjYgOS02LjQ1IDktMTJWNWwtOS00em0wIDEwLjk5aDdjLS41MyA0LjEyLTMuMjggNy43OS03IDguOTRWMTJINVY2LjNsNy0zLjExdjguOHoiLz4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjwvc3ZnPg==);
}
/*Audit Logs*/
.layer[layer-id="server-settings"] .item-3879bf:nth-of-type(4)::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(4)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTkgM2gtNC4xOEMxNC40IDEuODQgMTMuMyAxIDEyIDFjLTEuMyAwLTIuNC44NC0yLjgyIDJINWMtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxNGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yem0tNyAwYy41NSAwIDEgLjQ1IDEgMXMtLjQ1IDEtMSAxLTEtLjQ1LTEtMSAuNDUtMSAxLTF6bS0yIDE0bC00LTQgMS40MS0xLjQxTDEwIDE0LjE3bDYuNTktNi41OUwxOCA5bC04IDh6Ii8+PC9zdmc+);
}
/*Roles*/
.layer[layer-id="server-settings"] .item-3879bf:nth-of-type(5)::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(5)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTEyIDJDNi40OCAyIDIgNi40OCAyIDEyczQuNDggMTAgMTAgMTAgMTAtNC40OCAxMC0xMFMxNy41MiAyIDEyIDJ6bTAgM2MxLjY2IDAgMyAxLjM0IDMgM3MtMS4zNCAzLTMgMy0zLTEuMzQtMy0zIDEuMzQtMyAzLTN6bTAgMTQuMmMtMi41IDAtNC43MS0xLjI4LTYtMy4yMi4wMy0xLjk5IDQtMy4wOCA2LTMuMDggMS45OSAwIDUuOTcgMS4wOSA2IDMuMDgtMS4yOSAxLjk0LTMuNSAzLjIyLTYgMy4yMnoiLz4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjwvc3ZnPg==);
}
/*Integrations*/
.layer[layer-id="server-settings"] .item-3879bf:nth-of-type(6)::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(6)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTS03NCAyOWg0OHY0OGgtNDhWMjl6IiBmaWxsPSJub25lIi8+ICAgIDxwYXRoIGQ9Ik0yMiA5VjdoLTJWNWMwLTEuMS0uOS0yLTItMkg0Yy0xLjEgMC0yIC45LTIgMnYxNGMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0ydi0yaDJ2LTJoLTJ2LTJoMnYtMmgtMlY5aDJ6bS00IDEwSDRWNWgxNHYxNHpNNiAxM2g1djRINnptNi02aDR2M2gtNHpNNiA3aDV2NUg2em02IDRoNHY2aC00eiIvPiAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6bTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjwvc3ZnPg==);
}
/*Emoji*/
.layer[layer-id="server-settings"] .item-3879bf:nth-of-type(7)::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(7)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTEuOTkgMkM2LjQ3IDIgMiA2LjQ4IDIgMTJzNC40NyAxMCA5Ljk5IDEwQzE3LjUyIDIyIDIyIDE3LjUyIDIyIDEyUzE3LjUyIDIgMTEuOTkgMnpNMTIgMjBjLTQuNDIgMC04LTMuNTgtOC04czMuNTgtOCA4LTggOCAzLjU4IDggOC0zLjU4IDgtOCA4em0zLjUtOWMuODMgMCAxLjUtLjY3IDEuNS0xLjVTMTYuMzMgOCAxNS41IDggMTQgOC42NyAxNCA5LjVzLjY3IDEuNSAxLjUgMS41em0tNyAwYy44MyAwIDEuNS0uNjcgMS41LTEuNVM5LjMzIDggOC41IDggNyA4LjY3IDcgOS41IDcuNjcgMTEgOC41IDExem0zLjUgNi41YzIuMzMgMCA0LjMxLTEuNDYgNS4xMS0zLjVINi44OWMuOCAyLjA0IDIuNzggMy41IDUuMTEgMy41eiIvPjwvc3ZnPg==);
}
/*Webhooks*/
.layer[layer-id="server-settings"] .item-3879bf:nth-of-type(8)::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(8)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMjAgNEg0Yy0xLjEgMC0yIC45LTIgMnYxMmMwIDEuMS45IDIgMiAyaDE2YzEuMSAwIDItLjkgMi0yVjZjMC0xLjEtLjktMi0yLTJ6TTcuNzYgMTYuMjRsLTEuNDEgMS40MUM0Ljc4IDE2LjEgNCAxNC4wNSA0IDEyYzAtMi4wNS43OC00LjEgMi4zNC01LjY2bDEuNDEgMS40MUM2LjU5IDguOTMgNiAxMC40NiA2IDEycy41OSAzLjA3IDEuNzYgNC4yNHpNMTIgMTZjLTIuMjEgMC00LTEuNzktNC00czEuNzktNCA0LTQgNCAxLjc5IDQgNC0xLjc5IDQtNCA0em01LjY2IDEuNjZsLTEuNDEtMS40MUMxNy40MSAxNS4wNyAxOCAxMy41NCAxOCAxMnMtLjU5LTMuMDctMS43Ni00LjI0bDEuNDEtMS40MUMxOS4yMiA3LjkgMjAgOS45NSAyMCAxMmMwIDIuMDUtLjc4IDQuMS0yLjM0IDUuNjZ6TTEyIDEwYy0xLjEgMC0yIC45LTIgMnMuOSAyIDIgMiAyLS45IDItMi0uOS0yLTItMnoiLz48L3N2Zz4=);
}
/*Widget*/
.layer[layer-id="server-settings"] .item-3879bf:nth-of-type(9)::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(9)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTEzIDEzdjhoOHYtOGgtOHpNMyAyMWg4di04SDN2OHpNMyAzdjhoOFYzSDN6bTEzLjY2LTEuMzFMMTEgNy4zNCAxNi42NiAxM2w1LjY2LTUuNjYtNS42Ni01LjY1eiIvPiAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PC9zdmc+);
}
/*Members*/
.layer[layer-id="server-settings"] .item-3879bf:nth-of-type(12)::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(12)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMjEgNXYxNGgyVjVoLTJ6bS00IDE0aDJWNWgtMnYxNHpNMTQgNUgyYy0uNTUgMC0xIC40NS0xIDF2MTJjMCAuNTUuNDUgMSAxIDFoMTJjLjU1IDAgMS0uNDUgMS0xVjZjMC0uNTUtLjQ1LTEtMS0xek04IDcuNzVjMS4yNCAwIDIuMjUgMS4wMSAyLjI1IDIuMjVTOS4yNCAxMi4yNSA4IDEyLjI1IDUuNzUgMTEuMjQgNS43NSAxMCA2Ljc2IDcuNzUgOCA3Ljc1ek0xMi41IDE3aC05di0uNzVjMC0xLjUgMy0yLjI1IDQuNS0yLjI1czQuNS43NSA0LjUgMi4yNVYxN3oiLz48L3N2Zz4=);
}
/*Invites*/
.layer[layer-id="server-settings"] .item-3879bf:nth-of-type(13)::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(13)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTIwIDZoLTIuMThjLjExLS4zMS4xOC0uNjUuMTgtMSAwLTEuNjYtMS4zNC0zLTMtMy0xLjA1IDAtMS45Ni41NC0yLjUgMS4zNWwtLjUuNjctLjUtLjY4QzEwLjk2IDIuNTQgMTAuMDUgMiA5IDIgNy4zNCAyIDYgMy4zNCA2IDVjMCAuMzUuMDcuNjkuMTggMUg0Yy0xLjExIDAtMS45OS44OS0xLjk5IDJMMiAxOWMwIDEuMTEuODkgMiAyIDJoMTZjMS4xMSAwIDItLjg5IDItMlY4YzAtMS4xMS0uODktMi0yLTJ6bS01LTJjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXpNOSA0Yy41NSAwIDEgLjQ1IDEgMXMtLjQ1IDEtMSAxLTEtLjQ1LTEtMSAuNDUtMSAxLTF6bTExIDE1SDR2LTJoMTZ2MnptMC01SDRWOGg1LjA4TDcgMTAuODMgOC42MiAxMiAxMSA4Ljc2bDEtMS4zNiAxIDEuMzZMMTUuMzggMTIgMTcgMTAuODMgMTQuOTIgOEgyMHY2eiIvPiAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PC9zdmc+);
}
/*Bans*/
.layer[layer-id="server-settings"] .item-3879bf:nth-of-type(14)::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item:nth-of-type(14)::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayI+ICAgIDxkZWZzPiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgwVjB6IiBpZD0iYSIvPiAgICA8L2RlZnM+ICAgIDxjbGlwUGF0aCBpZD0iYiI+ICAgICAgICA8dXNlIG92ZXJmbG93PSJ2aXNpYmxlIiB4bGluazpocmVmPSIjYSIvPiAgICA8L2NsaXBQYXRoPiAgICA8cGF0aCBjbGlwLXBhdGg9InVybCgjYikiIGQ9Ik0xIDIxaDEydjJIMXpNNS4yNDUgOC4wN2wyLjgzLTIuODI3IDE0LjE0IDE0LjE0Mi0yLjgyOCAyLjgyOHpNMTIuMzE3IDFsNS42NTcgNS42NTYtMi44MyAyLjgzLTUuNjU0LTUuNjZ6TTMuODI1IDkuNDg1bDUuNjU3IDUuNjU3LTIuODI4IDIuODI4LTUuNjU3LTUuNjU3eiIvPjwvc3ZnPg==);
}
.layer[layer-id="server-settings"] .item-3879bf.itemDanger-3m3dwx::before,
.layer[layer-id="server-settings"] .ui-standard-sidebar-view .sidebar-region .ui-tab-bar.SIDE .ui-tab-bar-item.danger::before{
    content:url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjZjA0NzQ3IiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgwVjB6IiBmaWxsPSJub25lIi8+ICAgIDxwYXRoIGQ9Ik02IDE5YzAgMS4xLjkgMiAyIDJoOGMxLjEgMCAyLS45IDItMlY3SDZ2MTJ6bTIuNDYtNy4xMmwxLjQxLTEuNDFMMTIgMTIuNTlsMi4xMi0yLjEyIDEuNDEgMS40MUwxMy40MSAxNGwyLjEyIDIuMTItMS40MSAxLjQxTDEyIDE1LjQxbC0yLjEyIDIuMTItMS40MS0xLjQxTDEwLjU5IDE0bC0yLjEzLTIuMTJ6TTE1LjUgNGwtMS0xaC01bC0xIDFINXYyaDE0VjR6Ii8+ICAgIDxwYXRoIGQ9Ik0wIDBoMjR2MjRIMHoiIGZpbGw9Im5vbmUiLz48L3N2Zz4=);
    opacity: 1;
}
/*/settings icons*/
@font-face{
    font-family:'BMTicons';
    src: url(data:application/font-ttf;charset=utf-8;base64,AAEAAAAKAIAAAwAgT1MvMlbwY3AAAAEoAAAAVmNtYXAEDAI9AAABkAAAAUpnbHlmQr+w7AAAAugAAAHUaGVhZA3Ar3cAAADQAAAANmhoZWEIZQP+AAAArAAAACRobXR4EAAAAAAAAYAAAAAQbG9jYQFQAKgAAALcAAAACm1heHABEQBQAAABCAAAACBuYW1l01mGtgAABLwAAAJtcG9zdAIWAQMAAAcsAAAALwABAAAEAAAAAFwEAAAA//kEBwABAAAAAAAAAAAAAAAAAAAABAABAAAAAQAAbjPooV8PPPUACwQAAAAAANVNtT0AAAAA1U21PQAAAAAEBwQAAAAACAACAAAAAAAAAAEAAAAEAEQAAwAAAAAAAgAAAAoACgAAAP8AAAAAAAAAAQQAAZAABQAIAokCzAAAAI8CiQLMAAAB6wAyAQgAAAIABQMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAUGZFZABAAHwAfgQAAAAAXAQAAAAAAAABAAAAAAAABAAAAAQAAAAEAAAABAAAAAAAAAMAAAADAAAAHAABAAAAAABEAAMAAQAAABwABAAoAAAABgAEAAEAAgAAAH7//wAAAAAAfP//AAD/hQABAAAAAAAAAAABBgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAECAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABmAKgA6gAAAAMAAAAABAcDnAAtADsAQwAAAS4BJyEOARQWFzMeAQcGKwEiBgcUFjsBHgEHMDEOASsBIgYUFhczHgEXPgEnMAEuASc+ATceARcOAQcwNwYPASMnNzMD/w7rpP5rGykmHjMUEQwGE9EUGgEYF4gRFwYDEg1EER0aFF4U35647Qj+Z2OBAgKBY2WDAgKDZaoFIymqUVGqAiWj0AQBJjsmAQEhEQ0YFxEdARcTDREbKBoBncoDDvq4/vcDgmZlgwICg2VmggPrCUBIkZEAAAIAAAAABAAEAAANACUAAAEGAAcWABc2ADcmACcwAQYPAgYiLwImND8CNjIfAhYUBzACANr+3wUFASHa2gEhBQX+39oBag5gbmMPOQ5j3Bwc3GMPOA9j3BwcBAAF/t/a2v7fBQUBIdraASEF/dUGKzLcHBzcYw84D2PcHBzcYw84DwAAAAIAAAAABAAEAAANACUAAAEGAAcWABc2ADcmACcwEwYPAgYiLwImND8CNjIfAhYUBzACANr+3wUFASHa2gEhBQX+39r9CURNRQooCkWaFBSaRQooCkWaFBQEAAX+39ra/t8FBQEh2toBIQX94gUeIpoUFJpFCigKRZoUFJpFCigKAAAAAAAAEgDeAAEAAAAAAAAAFQAAAAEAAAAAAAEACAAVAAEAAAAAAAIABwAdAAEAAAAAAAMACAAkAAEAAAAAAAQACAAsAAEAAAAAAAUACwA0AAEAAAAAAAYACAA/AAEAAAAAAAoAKwBHAAEAAAAAAAsAEwByAAMAAQQJAAAAKgCFAAMAAQQJAAEAEACvAAMAAQQJAAIADgC/AAMAAQQJAAMAEADNAAMAAQQJAAQAEADdAAMAAQQJAAUAFgDtAAMAAQQJAAYAEAEDAAMAAQQJAAoAVgETAAMAAQQJAAsAJgFpR2VuZXJhdGVkIGJ5IEdseXBodGVyQk1UaWNvbnNSZWd1bGFyQk1UaWNvbnNCTVRpY29uc1ZlcnNpb24gMS4wQk1UaWNvbnNHZW5lcmF0ZWQgYnkgc3ZnMnR0ZiBmcm9tIEZvbnRlbGxvIHByb2plY3QuaHR0cDovL2ZvbnRlbGxvLmNvbQBHAGUAbgBlAHIAYQB0AGUAZAAgAGIAeQAgAEcAbAB5AHAAaAB0AGUAcgBCAE0AVABpAGMAbwBuAHMAUgBlAGcAdQBsAGEAcgBCAE0AVABpAGMAbwBuAHMAQgBNAFQAaQBjAG8AbgBzAFYAZQByAHMAaQBvAG4AIAAxAC4AMABCAE0AVABpAGMAbwBuAHMARwBlAG4AZQByAGEAdABlAGQAIABiAHkAIABzAHYAZwAyAHQAdABmACAAZgByAG8AbQAgAEYAbwBuAHQAZQBsAGwAbwAgAHAAcgBvAGoAZQBjAHQALgBoAHQAdABwADoALwAvAGYAbwBuAHQAZQBsAGwAbwAuAGMAbwBtAAAAAAIAAAAAAAAACgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABAAAAQIBAwEEAAAAAAAA) format('truetype');
}

.textAreaEdit-1qc9VQ{box-shadow: 0px 0px 6px 0px #101010;}

form .bf-toolbar{position:absolute !important;transform:translate(0px, -60px) !important;z-index:5;}

.bf-toolbar .bf-arrow{right:1px !important;top:16px !important;background-color:#19191b !important;opacity:1 !important;border-left:2px solid #212121 !important;border-right:2px solid #212121 !important;border-top:2px solid #212121 !important;z-index:1 !important;}

.bf-toolbar.bf-visible .bf-arrow, .bf-toolbar.bf-hover:hover .bf-arrow{-webkit-transform:translate(7px,-5px)rotate(-90deg) !important;-ms-transform:translate(7px,-5px)rotate(-90deg) !important;transform:translate(7px,-5px)rotate(-90deg !important);width:43px !important;height:23px !important;opacity:1 !important;border-top:2px solid #212121 !important;border-right:2px solid #212121 !important;border-bottom:2px solid #212121 !important;border-left:2px solid #19191b!important;z-index:0 !important;}

.bf-toolbar:before{content:"";width:95% !important;background:#19191b !important;box-shadow:0px 0px 0px 0px #0a0a0a !important;border:2px solid #212121 !important;border-right:0px solid transparent !important;left:6px !important;}

.bf-toolbar div:not(.bf-arrow):hover{background:rgb(32, 32, 32) !important;color:#fff !important;}

.guild.guild-sorter{height:8px !important;}

.guild-sorter .guild-inner{background:#19191b !important;}

.bd-detached-css-editor #bd-customcss-attach-controls button:active,.ui-standard-sidebar-view #bd-customcss-attach-controls button:active,.ui-standard-sidebar-view #editor-detached button:active{background:var(--hover-color) !important;}

.ui-standard-sidebar-view #editor-detached button{background:var(--main-color) !important;}

.bf-toolbar div:not(.bf-arrow){margin-top:-2px;}

.bf-toolbar.bf-visible div:not(.bf-arrow), .bf-toolbar.bf-hover:hover div:not(.bf-arrow){z-index:2;}

.bf-toolbar.bf-visible:before, .bf-toolbar.bf-hover:hover:before{-webkit-transform:translate(0,-4px)!important;-ms-transform:translate(0,-4px)!important;transform:translate(0,-4px) !important;z-index:1;}

#autocomplete-popout .autocomplete-scroller{background-color:transparent !important;box-shadow:0px 0px 0px 0px #101010 !important;}

.edit-container-inner .bf-toolbar.bf-visible:before, .edit-container-inner .bf-toolbar.bf-hover:before {transform: translate(0,-4px) !important;}

.edit-container-inner .bf-toolbar:before {border-right: 2px solid #212121 !important;}

.edit-container-inner .bf-toolbar{-webkit-transform: translate(21px,-100%);-ms-transform: translate(21px,-100%);transform: translate(21px,-100%);}

.bf-toolbar div:not(.bf-arrow):hover{background: var(--hover-color) !important;}

.avatar-large .status{width: 100%;height: 100%;border-radius: 8px;border-width: 3px !important;right: -3px !important;top: -3px !important;}

.theme-dark .guild-role::before{content: "" !important;}

.theme-light .radio .radio-inner span:after,.theme-dark .radio .radio-inner span:after{background-color: #19191b;}

.deprecated-settings-modal .checkbox .checkbox-inner span{border: 2px solid #323234;}

.theme-light .radio .radio-inner{background-color: #19191b;border-color: #323234;}

.theme-dark .footer-1PYmcw{background-color:#0f0f10;}

.userPopout-4pfA0d .body-3rkFrF{background-color:#0f0f10;border-bottom:1px solid #0f0f10;}

.userPopout-4pfA0d .footer-2J5zqP{background-color:#0f0f10;}

.userPopout-4pfA0d .headerNormal-1cioxU{background:var(--main-color);background-image:url(https://betterdocs.net/img/bg.svg);background-size: 15em;}

.headerTagNormal-KyD3_J{color:#f9f9f9;}

.avatarWrapper-2Gfmp1{border-radius:3px;}

.avatar-1jmnc-{border:0px solid;}

.header-3mZJcV .avatarStatusNormal-1OXVjG{border-color:var(--hover-color);height:100%;width:100%;border-width:4px;box-shadow:0px 0px 7px 0px #000;}

.statusOnline-1Mp2_H{background-color:transparent;border: 2px solid #43b581 !important;bottom: -2px !important;right: -2px !important;}

.statusInvisible-2ci18Q, .statusOffline-jZXr_u {background-color: transparent;border: 2px solid  #747f8d !important;}

.statusDnd-35xAXU{background-color:transparent;border: 2px solid #f04747 !important;}

.statusIdle-2AQdvu{background-color:transparent;border: 2px solid #faa61a !important;}

.status-3jUEha{width:100%;height:100%;border-width:2px !important;}

.status-3jUEha{position:absolute;bottom:-2px;right:-2px;}

.userPopout-4pfA0d .status-3jUEha{width:100%;height:100%;border-radius:0px;position:absolute;}

[class*="userPopout-"] .status-3jUEha{bottom: 0px;right: 0px;}

.avatarHint-2i5XWK{top:0px;left:0px;border-radius:0px;width:100%;height:100%;}

.botTagInvert-gorWR_{background:var(--hover-color);color:#fff;}

.guild div.avatar-large{border-radius:0px !important;}

.message-group .edit-message .edit-container-outer .bf-toolbar div:not(.bf-arrow){padding: 11px 5px;}

.theme-dark .checked-2TahvT{border-color: var(--main-color) !important;}

.private-channel-call-btn:nth-child(2){margin-top: -30px;margin-left: 43px;}

.bodyTitleText-hSiL7d{color: #ababab;}

.theme-dark .message-group a{color: var(--main-color);}

.guilds-wrapper .guilds .guild.selected:before, .guilds-wrapper .guilds .guild.unread:before{margin-left: -3px !important;}

.scroller-fzNley::-webkit-scrollbar{width: 11px;}

.containerDefault-1bbItS, .containerDragAfter-3O-noP, .containerDragBefore-2hcouM, .containerUserOver-3O3u5c{padding-top: 20px;}

[class*="userPopout-"] .avatar-1BXaQj{border-radius: 4px;}

.theme-dark .preview-inner .message-group{background-color: #171719;}

.member-roles{overflow-y: scroll;max-height: 220px;}

.member-roles::-webkit-scrollbar{width: 0px;}

.theme-light .container-iksrDt{background:#2f3136 !important;}

.theme-light .channels-wrap{background-color:#fff !important;}

.theme-light .title-wrap, .theme-light .container-iksrDt, .theme-light .content, .theme-light .content .flex-spacer, .theme-light .chat form, .theme-light div.message-group, .theme-light .channel-members, .theme-light .container-RYiLUQ{background-color:#fff !important;}

.theme-light .friends-table, .theme-light .friends-header, .theme-light .guilds-wrapper .guilds .guild:first-of-type .guild-inner, .app.theme-light .guilds .guild:first-child{background:#fff !important;}

.theme-light .friends-icon{filter:invert();}

.theme-light .channel-members::after{background:#fff !important;color:#e8e8e8 !important;border-top:2px solid #f6f6f7 !important;}

.theme-light .header-1tSljs{color:#656565 !important;}

.theme-light .chat form, .theme-light .container-iksrDt{border-top:2px solid #f6f6f7 !important;}

.theme-light .icon-3rMtHF{fill:#000;}

.theme-light .iconButtonDefault-3QZh-A.iconButton-3mKjyp.button-1aU9q1.small-1ChI_f{filter:invert() !important;}

.theme-light .button-1aU9q1:hover{background-color:rgba(119, 119, 119, 0.3);}

.theme-light .need-help-modal .form-inner.loading::after{background-color:#fff;color:#212121;}

.theme-light .need-help-modal .footer::after{background-color:#fff;border-top:2px solid #f6f6f7;color:#212121;}

.theme-light .guilds-wrapper, .theme-light .guilds .guild:hover:first-child, .theme-light .guilds-wrapper .guilds .guild:hover:first-of-type .guild-inner{background:#ececec !important;}

.theme-light .contentSelectedText-3j5CXt, .theme-light .contentSelectedVoice-gTtYM9{background-color:#ececec !important;}

.theme-light .nameSelectedText-32NDX5, .theme-light .nameSelectedVoice-XpjYTw{color:#1d1d1d !important;}

.theme-light .message-group h2 strong{color:#2f3136;}

.theme-light .guilds-wrapper .guilds .guild .guild-inner{background:#d2d2d2 !important;}

.theme-light .guilds-wrapper .guilds .guild .guild-inner a{color:#1f1f1f;}

.theme-light .container-iksrDt{color:#000 !important;}

.theme-light .nameUnreadText-1pxldj, .theme-light .nameUnreadVoice-QK4gxH{color:#545454 !important;}

.theme-light .message-group .comment .markup{color:#8e8e8e;}

.theme-light .contentHoveredText-2HYGIY, .theme-light .contentHoveredVoice-3qGNKh:active, .theme-light .contentSelectedVoice-gTtYM9:active, .theme-light .userHovered-3tfm93:active{background-color:#ececec !important;}

.theme-light .colorDefaultText-2v6rRX, .theme-light .colorDefaultVoice-1x4dEl, .theme-light .colorHoveredText-1CsxK1, .theme-light .colorHoveredVoice-1P3kui, .theme-light .colorLockedText-2onHWv, .theme-light .colorLockedVoice-2VCSgk, .theme-light .colorSelectedText-3YhFC6, .theme-light .colorSelectedVoice-ieXC3Z, .theme-light .colorUnreadText-1KwCnP, .theme-light .colorUnreadVoice-1Ztv9I{color:#484848 !important;}

.theme-light .nameHoveredVoice-TIoHRJ, .theme-light .nameHovered-28u_Fz, .theme-light .nameSpeaking-3ROx9q{color:#757575 !important;}

.theme-light .nameHovered-28u_Fz, .theme-light .nameSpeaking-3ROx9q{color:#000 !important;}

.theme-light .embed-wrapper{box-shadow:2px 2px 10px #dedede !important;}

.theme-light .popout-open .header-1tSljs, .theme-light .header-1tSljs:hover, .theme-light .mention {background-color:#ececec !important;}

.theme-light .mention:hover{color:#000 !important;}

.theme-light .message-group .mentioned .message-text{background:#ececec !important;}

.theme-light .message-group .comment .markup code.inline, .theme-light .message-group .comment .markup pre{background:#ececec !important;box-shadow:0 0 3px 0px #6d6d6d !important;}

.theme-light .channel-members .member:hover{background:linear-gradient(to right, #f6f6f7 85%, #ffffff) !important;}

.theme-light .messages-popout .message-group:hover{border-color:var(--main-color) !important;}

.theme-light .status-picker.popout-menu{background:#fff !important;border-color:#ececec !important;box-shadow:0px -2px 9px -2px #d4d4d4 !important;}

.theme-light .DraftEditor-editorContainer, .theme-light .search .search-bar-icon{background-color:rgba(236, 236, 236, 0.4);}

.theme-light .search .DraftEditor-root .public-DraftEditorPlaceholder-root, .theme-light .search .DraftEditor-root, .theme-light .search .search-bar .public-DraftEditorPlaceholder-root{color:#000 !important;}

.theme-light .guilds-wrapper .guilds-error{background:#d2d2d2 !important;color:#676767!important;}

.theme-light #friends .friends-table .friends-table-body::after{background:#fff;border-top:2px solid #f6f6f7 !important;}

.theme-light #friends .friends-header{border-bottom:2px solid var(--main-color) !important;}

.theme-light #friends .friends-empty p{color:#464646;}

.theme-light .channels-wrap{background-color:#fff !important;}

.theme-light .private-channels header{color:#464646;opacity:1;font-weight:600;}

.theme-light .private-channels .channel .channel-name{color:#000000;opacity:0.6;font-weight:600;}

.theme-light .private-channels .channel.selected a, .theme-light .private-channels .channel:hover a{background-color:#ececec;}

.theme-light .private-channels .channel .close{filter:invert(70%) !important;}

.theme-light .private-channels .search-bar input{background:#ffffff !important;color:#000;}

.theme-light .private-channels .search-bar input::placeholder{color:#000;}

.theme-light #friends .friends-header .tab-bar .tab-bar-item, .theme-light #friends .friends-table .friends-table-header .friends-column, .theme-light #friends .friends-table .friends-row .friends-column-name, .theme-light #friends .friends-table .friends-row .friends-column-status{color:rgba(0, 0, 0, 0.75)!important;}

.theme-light #friends .friends-table .friend-table-add-wrapper .friend-table-add-header{background:transparent;}

.theme-light #friends .friends-table .friend-table-add-wrapper h2{color:#5d5d5d;}

.theme-light .channel-members .member.popout-open, .theme-light .channel-members .member:hover{background:linear-gradient(to right, #f6f6f7 85%, #ffffff) !important;}

.theme-light .userPopout-4pfA0d .body-3rkFrF{background-color:#ffffff;border-bottom:1px solid #f6f6f7;}

.theme-light .userPopout-4pfA0d .footer-2J5zqP, .theme-light .quick-message{background-color:#fff;}

.theme-light .member-role{box-shadow:0 1px 9px rgba(0, 0, 0, .2);}

.theme-light .ui-standard-sidebar-view .sidebar-region, .theme-light .ui-standard-sidebar-view .sidebar-region .scrollbar{background:#fff !important;}

.theme-light .ui-standard-sidebar-view .content-region, .theme-light .ui-standard-sidebar-view .content-region .scrollbar, .theme-light .user-settings-streamer-mode{background:#fff !important;}

.theme-light [class*="itemDefault"]:hover{background:var(--hover-color);color: #fff;}

.theme-light .themeDefault-3M0dJU.valueChecked-3Bzkbm{background-color:var(--main-color);}

.theme-light .search-popout .results-group{background:#fff;}

.theme-light .search-popout{background-color:#fff;}

.theme-light .search-popout .option .answer{color:#353535;font-weight:500;}

.theme-light .search-popout .results-group .header{color:#000000;}

.theme-light .search-popout .option.selected, .theme-light .search-popout .search-query.selected{background-color:#ececec;}

.theme-light .search-popout .option.selected:before{filter:invert(55%);}

.theme-light #friends .friends-header .btn, .theme-light #friends .friends-header .tab-bar .tab-bar-item.selected, .theme-light #friends .friends-header .tab-bar .tab-bar-item.tab-bar-item-primary, .theme-light #friends .friends-header .tab-bar .tab-bar-item:hover:not(.selected){color: #fff !important;}

.theme-light .guilds .guild:hover:first-child, .theme-light .guilds-wrapper .guilds .guild:hover:first-of-type .guild-inner, .theme-light .guilds-wrapper .guilds .guild.active:first-of-type .guild-inner, .app.theme-light .guilds .guild.active:first-child{background-color: #ececec !important;}

.theme-light .layer, .theme-light .layers, body{background: #fff !important;}

.theme-light .layers{background: #fff !important;}

.theme-light [d*="M4.5 4.5l9 9"]{stroke: #000;}

.theme-light [d*="M13.5 4.5l-9 9"]{stroke: #000;}

.theme-light .popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item .popout-menu-icon, .theme-light .popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item .popout-menu-item-label{background-color: #fff !important;}

.theme-light .popout.popout-bottom:not(.no-arrow), .theme-light .popout.popout-bottom:not(.no-arrow) .popout-menu, .theme-light .popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item .popout-menu-item-label{background: #fff !important;}

.theme-light .popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item .popout-menu-item-label{color: #000 !important;}

.theme-light .scroller-wrap .scroller::-webkit-scrollbar-track-piece{border: 3px solid #fff !important;background-color: #ececec !important;}

.theme-light .scroller-wrap .scroller.messages:hover::-webkit-scrollbar-track-piece{border: 3px solid #fff !important;background-color: #ececec !important;}

.theme-light .scrollerThemed-19vinI.themeLight-1WK0Av.scrollerTrack-3hhmU0>.scroller-fzNley::-webkit-scrollbar-track, .theme-light .scrollerThemed-19vinI.themeLight-1WK0Av.scrollerTrack-3hhmU0>.scroller-fzNley::-webkit-scrollbar-track, .theme-light .scrollerWrap-2uBjct.scrollerTrack-3hhmU0>.scroller-fzNley::-webkit-scrollbar-track{background-color: #ececec;}

.theme-light [class*="nameDefaultText-"], .theme-light [class*="nameDefaultVoice-"], .theme-light [class*="nameLockedText-"], .theme-light [class*="nameLockedVoice-"]{color: #a5a5a5 !important;}

.theme-light .guilds-wrapper .guilds .guild.selected .guild-inner:not([style*="background-color:"]), .theme-light .guilds-wrapper .guilds .guild:hover .guild-inner:not([style*="background-color:"]), .theme-light .chat .divider.divider-red > span{background-color: #ececec !important;}

.header-toolbar button span[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBmaWxsPSIjNEY1NDVDIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDcgNCkiPgogICAgPHBhdGggZD0iTTAgNC4zMjU4NDI3QzAgNS4wNjc0MTU3My42MTY0MzgzNTYgNS42ODUzOTMyNiAxLjM1NjE2NDM4IDUuNjg1MzkzMjYgMi4wOTU4OTA0MSA1LjY4NTM5MzI2IDIuNzEyMzI4NzcgNS4wNjc0MTU3MyAyLjcxMjMyODc3IDQuMzI1ODQyNyAyLjcxMjMyODc3IDIuODQyNjk2NjMgNC4zMTUwNjg0OSAyLjc4MDg5ODg4IDQuNSAyLjc4MDg5ODg4IDQuNjg0OTMxNTEgMi43ODA4OTg4OCA2LjI4NzY3MTIzIDIuODQyNjk2NjMgNi4yODc2NzEyMyA0LjMyNTg0MjdMNi4yODc2NzEyMyA0LjYzNDgzMTQ2QzYuMjg3NjcxMjMgNS4yNTI4MDg5OSA1Ljk3OTQ1MjA1IDUuNzQ3MTkxMDEgNS40MjQ2NTc1MyA2LjA1NjE3OTc4TDQuMTkxNzgwODIgNi43MzU5NTUwNkMzLjUxMzY5ODYzIDcuMTA2NzQxNTcgMy4xNDM4MzU2MiA3Ljc4NjUxNjg1IDMuMTQzODM1NjIgOC41MjgwODk4OUwzLjE0MzgzNTYyIDkuNjQwNDQ5NDRDMy4xNDM4MzU2MiAxMC4zODIwMjI1IDMuNzYwMjczOTcgMTEgNC41IDExIDUuMjM5NzI2MDMgMTEgNS44NTYxNjQzOCAxMC4zODIwMjI1IDUuODU2MTY0MzggOS42NDA0NDk0NEw1Ljg1NjE2NDM4IDguOTYwNjc0MTYgNi43MTkxNzgwOCA4LjUyODA4OTg5QzguMTM2OTg2MyA3Ljc4NjUxNjg1IDkgNi4zMDMzNzA3OSA5IDQuNjk2NjI5MjFMOSA0LjMyNTg0MjdDOSAxLjQ4MzE0NjA3IDYuNzE5MTc4MDggMCA0LjUgMCAyLjIxOTE3ODA4IDAgMCAxLjQ4MzE0NjA3IDAgNC4zMjU4NDI3ek00LjUgMTJDMi41IDEyIDIuNSAxNSA0LjUgMTUgNi41IDE1IDYuNSAxMiA0LjUgMTJMNC41IDEyeiIvPgogIDwvZz4KPC9zdmc+Cg==");']::after{content: var(--theme-letter);font-family: "Roboto";text-align: center;color: #4a4a4a;font-size: 18px;position: absolute;left: 9px;top: 3px;padding-left: 1px;transition: .1s color linear;}

.header-toolbar button span[style*='background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBmaWxsPSIjNEY1NDVDIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDcgNCkiPgogICAgPHBhdGggZD0iTTAgNC4zMjU4NDI3QzAgNS4wNjc0MTU3My42MTY0MzgzNTYgNS42ODUzOTMyNiAxLjM1NjE2NDM4IDUuNjg1MzkzMjYgMi4wOTU4OTA0MSA1LjY4NTM5MzI2IDIuNzEyMzI4NzcgNS4wNjc0MTU3MyAyLjcxMjMyODc3IDQuMzI1ODQyNyAyLjcxMjMyODc3IDIuODQyNjk2NjMgNC4zMTUwNjg0OSAyLjc4MDg5ODg4IDQuNSAyLjc4MDg5ODg4IDQuNjg0OTMxNTEgMi43ODA4OTg4OCA2LjI4NzY3MTIzIDIuODQyNjk2NjMgNi4yODc2NzEyMyA0LjMyNTg0MjdMNi4yODc2NzEyMyA0LjYzNDgzMTQ2QzYuMjg3NjcxMjMgNS4yNTI4MDg5OSA1Ljk3OTQ1MjA1IDUuNzQ3MTkxMDEgNS40MjQ2NTc1MyA2LjA1NjE3OTc4TDQuMTkxNzgwODIgNi43MzU5NTUwNkMzLjUxMzY5ODYzIDcuMTA2NzQxNTcgMy4xNDM4MzU2MiA3Ljc4NjUxNjg1IDMuMTQzODM1NjIgOC41MjgwODk4OUwzLjE0MzgzNTYyIDkuNjQwNDQ5NDRDMy4xNDM4MzU2MiAxMC4zODIwMjI1IDMuNzYwMjczOTcgMTEgNC41IDExIDUuMjM5NzI2MDMgMTEgNS44NTYxNjQzOCAxMC4zODIwMjI1IDUuODU2MTY0MzggOS42NDA0NDk0NEw1Ljg1NjE2NDM4IDguOTYwNjc0MTYgNi43MTkxNzgwOCA4LjUyODA4OTg5QzguMTM2OTg2MyA3Ljc4NjUxNjg1IDkgNi4zMDMzNzA3OSA5IDQuNjk2NjI5MjFMOSA0LjMyNTg0MjdDOSAxLjQ4MzE0NjA3IDYuNzE5MTc4MDggMCA0LjUgMCAyLjIxOTE3ODA4IDAgMCAxLjQ4MzE0NjA3IDAgNC4zMjU4NDI3ek00LjUgMTJDMi41IDEyIDIuNSAxNSA0LjUgMTUgNi41IDE1IDYuNSAxMiA0LjUgMTJMNC41IDEyeiIvPgogIDwvZz4KPC9zdmc+Cg==");']{background-image: none !important;}

.theme-brand .divider-2JwdCF{background-color:#222;height:2px;}

.theme-brand .description-YnaVYa, .theme-brand .descriptionUsername-1quCGz{color:#a1a1a1;}

.theme-brand .descriptionDiscriminator-3KCIMj{color:#fff;}

.theme-brand .content-249Pr9{color:#fff;}

.xsmall-2rXiD4{border-radius:2px;}

.theme-light .cardPrimaryEditable-2IQ7-V{background-color:hsla(240,6%,97%,.6) !important;border-color:#dcddde !important;}

.theme-light .descChecked-KbaI-r, .theme-light .titleChecked-3Ngoss{color:#565b62 !important;}

.theme-light .Select-control{background-color:#ffffff !important;}

.theme-light .checked-2TahvT{border-color:var(--main-color) !important;}

.theme-light .channel-notices .channel-notice .message{color:#000;}

.theme-light .channel-notices .channel-notice.quickswitcher-notice{background:#fff url(/assets/8fdb69b7684b8e1ecb3fdde909daca41.svg) no-repeat center 35px;}

.theme-dark [class*="switch"][class*="valueUnchecked"]{background: grey !important;}

.theme-dark [class*="switch"][class*="valueChecked"]{background: var(--hover-color) !important;}

code{background-color: #19191b!important;background-image: linear-gradient(#121213 50%, transparent 50%)!important;background-origin: content-box!important;background-position: 0 1.5em!important;background-size: 100% 3em!important;line-height: 1.5 !important;}

.theme-dark .markup .hljs[class~="java" i]::before,
.theme-dark .markup .hljs[class~="sql" i]::before,
.theme-dark .markup .hljs[class~="ruby" i]::before,
.theme-dark .markup .hljs[class~="coffee" i]::before,
.theme-dark .markup .hljs[class~="xl" i]::before,
.theme-dark .markup .hljs[class~="py" i]::before,
.theme-dark .markup .hljs[class~="python" i]::before,
.theme-dark .markup .hljs[class~="html" i]::before,
.theme-dark .markup .hljs[class~="md" i]::before,
.theme-dark .markup .hljs[class~="markdown" i]::before,
.theme-dark .markup .hljs[class~="bash" i]::before,
.theme-dark .markup .hljs[class~="js" i]::before,
.theme-dark .markup .hljs[class~="javascript" i]:before,
.theme-dark .markup .hljs[class~="css" i]::before,
.theme-dark .markup .hljs[class~="vb" i]::before,
.theme-dark .markup .hljs[class~="visualbasic" i]::before,
.theme-dark .markup .hljs[class~="lua" i]::before,
.theme-dark .markup .hljs[class~="php" i]::before,
.theme-dark .markup .hljs[class~="swift" i]::before,
.theme-dark .markup .hljs[class~="makefile" i]::before,
.theme-dark .markup .hljs[class~="go" i]::before,
.theme-dark .markup .hljs[class~="ini" i]::before,
.theme-dark .markup .hljs[class~="rust" i]::before,
.theme-dark .markup .hljs[class~="prolog" i]::before,
.theme-dark .markup .hljs[class~="ts" i]::before, 
.theme-dark .markup .hljs[class~="typescript" i]::before,
.theme-dark .markup .hljs[class~="http" i]::before,
.theme-dark .markup .hljs[class~="json" i]::before,
.theme-dark .markup .hljs[class~="xml" i]::before,
.theme-dark .markup .hljs[class~="less" i]::before{width: 100%;height: 16px;position: relative;display: -webkit-box;margin-top: 0px;color: #fff;border-top-left-radius: 3px;border-top-right-radius: 3px;border-bottom: 5px solid #19191b;line-height: 15px !important;}

.theme-dark .markup .hljs[class~="java" i],
.theme-dark .markup .hljs[class~="sql" i],
.theme-dark .markup .hljs[class~="ruby" i],
.theme-dark .markup .hljs[class~="coffee" i],
.theme-dark .markup .hljs[class~="xl" i],
.theme-dark .markup .hljs[class~="py" i],
.theme-dark .markup .hljs[class~="python" i],
.theme-dark .markup .hljs[class~="html" i],
.theme-dark .markup .hljs[class~="md" i],
.theme-dark .markup .hljs[class~="markdown" i],
.theme-dark .markup .hljs[class~="js" i],
.theme-dark .markup .hljs[class~="javascript" i],
.theme-dark .markup .hljs[class~="css" i],
.theme-dark .markup .hljs[class~="bash" i],
.theme-dark .markup .hljs[class~="vb" i],
.theme-dark .markup .hljs[class~="visualbasic" i],
.theme-dark .markup .hljs[class~="lua" i],
.theme-dark .markup .hljs[class~="php" i],
.theme-dark .markup .hljs[class~="swift" i],
.theme-dark .markup .hljs[class~="makefile" i],
.theme-dark .markup .hljs[class~="go" i],
.theme-dark .markup .hljs[class~="ini" i],
.theme-dark .markup .hljs[class~="rust" i],
.theme-dark .markup .hljs[class~="prolog" i],
.theme-dark .markup .hljs[class~="ts" i], 
.theme-dark .markup .hljs[class~="typescript" i],
.theme-dark .markup .hljs[class~="http" i],
.theme-dark .markup .hljs[class~="json" i],
.theme-dark .markup .hljs[class~="xml" i],
.theme-dark .markup .hljs[class~="less" i]{padding: 0px !important;}

.theme-dark .markup .hljs[class~="js" i]::before, .theme-dark .markup .hljs[class~="javascript" i]::before{content: " Javascript";background: #165eab;}

.theme-dark .markup .hljs[class~="css" i]::before{content: " Cascading Style Sheet";background: #ab6f16;}

.theme-dark .markup .hljs[class~="bash" i]::before{content: " Bash";background: #ab1663;}

.theme-dark .markup .hljs[class~="markdown" i]::before, .theme-dark .markup .hljs[class~="md" i]::before{content: " Markdown";background: #ab2e16;}

.theme-dark .markup .hljs[class~="html" i]::before{content: " HTML";background: #16ab6f;}

.theme-dark .markup .hljs[class~="xl" i]::before{content: " eXtensible Language";background: #4872a8;}

.theme-dark .markup .hljs[class~="coffee" i]::before{content: " Coffee (Javascript)";background: #3a1b1b;}

.theme-dark .markup .hljs[class~="ruby" i]::before{content: " Ruby";background: #e73e3e;}

.theme-dark .markup .hljs[class~="sql" i]::before{content: " SQL";background: #4474ca;}

.theme-dark .markup .hljs[class~="java" i]::before{content: " Java";background: #eb2d2f;}

.theme-dark .markup .hljs[class~="py" i]::before, .theme-dark .markup .hljs[class~="python" i]::before{content: " Python";background: #1622ab;}

.theme-dark .markup .hljs[class~="vb" i]::before, .theme-dark .markup .hljs[class~="visualbasic" i]::before{content: " Visual Basic";background: #839700;}

.theme-dark .markup .hljs[class~="lua" i]::before{content: " Lua";background: #2ecc71;}

.theme-dark .markup .hljs[class~="php" i]::before{content: " Php";background: #6e81b6;}

.theme-dark .markup .hljs[class~="swift" i]::before{content: " Swift";background: #fd7837;}

.theme-dark .markup .hljs[class~="makefile" i]::before{content: " Makefile";background: #8a2b0f;}

.theme-dark .markup .hljs[class~="go" i]::before{content: " Go";background: #75cede;}

.theme-dark .markup .hljs[class~="ini" i]::before{content: " ini";background: #5a75c0;}

.theme-dark .markup .hljs[class~="rust" i]::before{content: " Rust";background: #000;}

.theme-dark .markup .hljs[class~="prolog" i]::before{content: " Prolog";background: #ef4d25;}

.theme-dark .markup .hljs[class~="ts" i]::before, .theme-dark .markup .hljs[class~="typescript" i]::before{content: " TypeScript";background: #03324c;}

.theme-dark .markup .hljs[class~="http" i]::before{content: " HTTP";background: #618f10;}

.theme-dark .markup .hljs[class~="json" i]::before{content: " Json";background: #108f66;}

.theme-dark .markup .hljs[class~="xml" i]::before{content: " XML";background: #8444af;}

.theme-dark .markup .hljs[class~="less" i]::before{content: " Less";background: #1d365d;}

.theme-light .bda-dark #bda-qem-favourite-container, .theme-light .bda-dark #bda-qem-twitch-container, .theme-light .bda-dark .emoji-picker, .theme-light .bda-dark .emoji-picker .category, .theme-light .bda-dark .emoji-picker .header .search-bar{background-color:#fff !important;}

.theme-light .emoji-picker{border:1px solid #ffffff !important;border-top:0px solid transparent !important;}

.theme-light .emoji-picker .categories .item.recent, .theme-light .emoji-picker .categories .item.custom, .theme-light .emoji-picker .categories .item.people, .theme-light .emoji-picker .categories .item.nature, .theme-light .emoji-picker .categories .item.food, .theme-light .emoji-picker .categories .item.activity, .theme-light .emoji-picker .categories .item.travel, .theme-light .emoji-picker .categories .item.travel, .theme-light .emoji-picker .categories .item.objects, .theme-light .emoji-picker .categories .item.symbols, .theme-light .emoji-picker .categories .item.flags{filter:invert();}

.theme-light .emoji-picker .categories .item.selected{border-bottom-color:#bbb;}

.theme-light .emoji-picker, .theme-light .emoji-picker .sticky-header, .theme-light .emoji-picker .search-bar{background-color:#fff;}

.emoji-picker .dimmer.visible{background-color:rgba(255, 255, 255, 0.8);height:270px;bottom:0px;}

.theme-light .diversity-selector .popout{background:#ffffff;border-color:#ffffff;}

.theme-light .emoji-picker .search-bar .search-bar-inner{background-color:#f6f6f7;border-color:#f6f6f7;}

.theme-light .emoji-picker .search-bar input{color:#808080;}

.theme-light .container-3lnMWU{background:#ffffff;}

.theme-light .inner-ptMwR- .channel-3YGMy1{color:#484848;opacity:.8;font-weight:600;}

.theme-light [d*="M11.5,9 C13.1575,9 14.5,7.6575 14.5,6 C14.5,4.3425 13.1575,3 11.5,3 C9.8425,3 8.5,4.3425 8.5,6 C8.5,7.6575 9.8425,9 11.5,9 Z M4,7 L4,5 L3,5 L3,7 L1,7 L1,8 L3,8 L3,10 L4,10 L4,8 L6,8 L6,7 L4,7 Z M11.5,10 C9.4975,10 6,11.005 6,13 L6,15 L17,15 L17,13 C17,11.005 13.5025,10 11.5,10 Z"]{fill:#000;}

.theme-light .buttonInfo-3r6H7z{filter:invert();}

.theme-light .buttonDisconnect-3xZpYL{filter:invert();}

.theme-light code{background-color: #e6e6e6!important;background-image: linear-gradient(#d5d5d5 50%, transparent 50%)!important;}

.theme-light .message-group .comment .markup pre{border: 2px solid #d5d5d5;}

.theme-light .hljs{color: #555555;}

.tooltip.tooltip-brand.tooltip-right:after{border-right-color: var(--main-color);}

.popout.popout-top-left{top: 0px !important;}

.theme-light .scroller-wrap .scroller.messages::-webkit-scrollbar-thumb{background-color: transparent !important;}

.theme-light .scroller-wrap .scroller::-webkit-scrollbar-thumb{border: 3px solid white !important;background-color: transparent !important;}

.theme-light .scroller-wrap .scroller::-webkit-scrollbar-track-piece{border: 3px solid transparent !important;background-color: transparent !important;}

.theme-light .scroller-wrap:hover .scroller.messages::-webkit-scrollbar-thumb{background-color: var(--main-color) !important;}

.theme-light .scroller-wrap:hover .scroller::-webkit-scrollbar-thumb{border: 3px solid white !important;background-color: var(--main-color) !important;}

.theme-light .scroller-wrap:hover .scroller::-webkit-scrollbar-track-piece{border: 3px solid #fff !important;background-color: #ececec !important;}

.theme-light .chat .jump-to-present-bar{background-color: var(--main-color);}

.theme-light .create-guild-container.deprecated, .theme-light .create-guild-container.deprecated .create-or-join .form-inner, .theme-light .form.deprecated .form-inner, .theme-light .form.deprecated .form-actions{background-color: #fff;}

.theme-light .create-guild-container.deprecated .action{background: #ffffff;box-shadow: 0px 0px 11px 0px rgb(224, 224, 224);}

.theme-light .create-guild-container .action.create .action-icon{-webkit-filter: invert(0) hue-rotate(262deg) !important;}

.theme-light .create-guild-container .action.join .action-icon{-webkit-filter: invert(0) hue-rotate(0deg) !important;}

.theme-light .form .control-group input[type=text], .theme-light .form .control-group input[type=email], .theme-light .form .control-group input[type=password], .theme-light .form .control-group input[type=number], .theme-light .form .control-group textarea{color: var(--main-color) !important;border-bottom: 2px solid #e2e2e2;border: 2px solid #e2e2e2 !important;background: #f6f6f7;}

.theme-light .form.deprecated .btn-default{background-color: #fff;border-bottom: 0px solid transparent;}

.theme-light .mention:hover{color: #fff !important;background: var(--main-color) !important;}

.theme-light .mention{transition: .2s all linear;}

.container-iksrDt .avatar-small{border-radius: 0px;}

.theme-light .mention:hover{color: #fff !important;background: var(--main-color) !important;}

.theme-light .mention{transition: .2s all linear;}

.theme-light .small-popout-box{background: #ffffff;border: 1px solid #f6f6f7;}

.theme-light .option-popout .btn-item, .theme-light .option-popout .btn-item:hover, .context-menu.theme-light.invertY .item, .context-menu.theme-light.invertY .item:hover{color: #696969;}

.context-menu.theme-light.invertY .item:hover{background: #f1f1f1;}

.theme-light .icon.icon-file{-webkit-filter: grayscale(100%) !important;}

.context-menu.theme-light.invertY, .context-menu.theme-light.invertY .context-menu, .theme-light .context-menu{background:#fff !important;}

.theme-light .context-menu .item:hover{background: #efefef;}

.tooltip.tooltip-red.tooltip-right:after{border-right-color: var(--main-color);}

.theme-light #user-profile-modal .avatar-wrapper .avatar-profile, .theme-light #user-profile-modal .sub-header, .theme-light #user-profile-modal .scroller-wrap, .theme-light #user-profile-modal .empty, .theme-light #user-profile-modal .scroller{background-color: #fff !important;}

.theme-light #user-profile-modal .header{background-color: #ececec;}

.theme-light #user-profile-modal .tab-bar-container{background-color: #ececec;}

.theme-light #user-profile-modal .header .header-info .header-info-inner .discord-tag, .theme-light #user-profile-modal .header .header-info .header-info-inner .activity{color: #4e4e4e;}

.theme-light #user-profile-modal .tab-bar-container:hover .tab-bar-item {color: #292929!important; opacity: 0.7;}

.theme-light #user-profile-modal .tab-bar-container .tab-bar-item::before{filter: invert();}

.theme-light #user-profile-modal .tab-bar-container:hover .tab-bar-item:hover, .theme-light #user-profile-modal .tab-bar-container:hover .tab-bar-item.selected{color: #292929!important;opacity: 1;}

.theme-light #user-profile-modal .header .header-info .header-info-inner .discord-tag .discriminator{color: #ffffff;}

.theme-light .search-popout .option strong{color: #444444;}

.theme-light .search-popout .search-query{background: #fff;color: #2b2b2b;font-weight: 600;}

.theme-light .search-popout .search-query .search-for{font-size: 14px;}

.theme-light .search-popout .search-query .keybind-shortcut span{background: #fff;color: var(--main-color) !important;}

.theme-light .channel-notices .channel-notice.quickswitcher-notice {background: #fff url(/assets/8fdb69b7684b8e1ecb3fdde909daca41.svg) no-repeat center 35px;}

.theme-light .channel-notices .channel-notice .message {color: #000;}

.container-iksrDt .avatar-small{border-radius: 0px;}

.theme-light .channel-notices .channel-notice .close{opacity: .5;filter: invert();}

.theme-light .channel-notices .channel-notice.quickswitcher-notice{top: 0px !important;}

.theme-light .messages-popout .channel-separator{background: #ffffff;border: 2px solid #f2f2f3;}

.theme-light .recent-mentions-popout .header .mention-filter{color: #2b2b2b;font-weight: 600;}

.theme-light .context-menu .item{color: #525252;font-weight: 600;}

.tooltip.tooltip-brand.tooltip-left:after{border-left-color: var(--main-color) !important;}

.theme-dark .container-a2vS7i, .theme-dark .reactors-2PjMP0{background-color: #19191b;}

.theme-dark .sidebar-32BRdp{background: #141415;}

.scrollerThemed-19vinI.themeDark-BdSAwu.scrollerTrack-3hhmU0>.scroller-fzNley::-webkit-scrollbar-track, .theme-dark .scrollerWrap-2uBjct.scrollerTrack-3hhmU0>.scroller-fzNley::-webkit-scrollbar-track, .theme-light .scrollerThemed-19vinI.themeDark-BdSAwu.scrollerTrack-3hhmU0>.scroller-fzNley::-webkit-scrollbar-track{background-color: #111113;}

.replyer, .quoter, body .citar-btn{background-image: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTYgMTdoM2wyLTRWN0g1djZoM3ptOCAwaDNsMi00VjdoLTZ2NmgzeiIvPiAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PC9zdmc+)!important;color: transparent!important;background-size: 70%!important;background-position: 50%!important;background-repeat: no-repeat!important;background-color: transparent!important;transition: 100ms ease!important;animation: opacity 100ms ease;opacity: .8!important;border-radius: 2px!important;user-select: none;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:nth-of-type(10){animation-delay: 900ms;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:nth-of-type(11){animation-delay: 1000ms !important;}

.popout.popout-bottom:not(.no-arrow) .popout-menu .popout-menu-item:nth-of-type(12){animation-delay: 1100ms !important;}

.tooltip.tooltip-right[style*="left: 42px; top: 7.5px;"], .tooltip.tooltip-right[style*="left: 42px; top: 10.5px;"]{display: none;}

.tooltip{padding: 5px 8px !important;}

[class*="nsfw-"] [class*="buttonBrandFilled"]::after{content: "God is watching.";width: 100%;background: #98041f;color: white;padding: 12px;border-radius: 3px;position: absolute;right: 50%;top: 130%;transition: .2s all linear;opacity: 0;pointer-events: none;}

[class*="nsfw-"] [class*="buttonBrandFilled"]:hover::after{opacity: 1;}

[class*="nsfw-"] [class*="buttonPrimaryOutlinedDefault"]::after{content: "Your parents would be proud of you.";width: 100%;background: #049857;color: white;padding: 12px;border-radius: 3px;position: absolute;left: 50%;top: 130%;transition: .2s all linear;opacity: 0;pointer-events: none;}

[class*="nsfw-"] [class*="buttonPrimaryOutlinedDefault"]:hover::after{opacity: 1;}

.unread-3nyKcq, .unreadBottom-2LxhSR, .unread-mentions-indicator-bottom, .unread-mentions-indicator-top {display: none;}

#friends .friends-table .friends-row .friends-column-actions .friends-action:hover:nth-child(1){background-color: rgb(73, 152, 76) !important;}

#friends .friends-table .friends-row .friends-column-actions .friends-action:nth-child(2){background-color: rgba(73, 152, 76, 0.7) !important;transition-delay: 200ms;}

#friends .friends-table .friends-row .friends-column-actions .friends-action:hover:nth-child(2){background-color: rgb(73, 152, 76) !important;}

#friends .friends-table .friends-row .friends-column-actions .friends-action:nth-child(3){background-color: rgba(199, 0, 67, 0.7) !important;transition-delay: 200ms;}

#friends .friends-table .friends-row .friends-column-actions .friends-action:hover:nth-child(3){background-color: rgba(199, 0, 67, 1) !important;}

#friends .friends-table .friends-row .friends-column-actions{top: 48px;}

.win-buttons.win-buttons-light .win-minimize{background-color:#ffbe2f;background-image:none;border-radius:50%;height:15px;width:15px;margin-left:-82px !important;}

.win-buttons.win-buttons-light .win-close{background-color:#ff625a;background-image:none;border-radius:50%;height:15px;width:15px;margin-left:15px !important;}

.win-buttons.win-buttons-light .win-maximize{background-color:#29cf42;background-image:none;border-radius:50%;height:15px;width:15px;margin-left:15px !important;}

.guilds-wrapper .guilds .guild.audio .guild-inner:after, .guilds-wrapper .guilds .guild.video .guild-inner:after{background-color: var(--main-color);}

.tutorial-indicators + .theme-light::before, .tutorial-indicators + .theme-light::after{display: none;}

#RANbutton-frame{margin-bottom:20px !important;}

#RANbutton-frame .guild-inner{width:45px !important;height:45px !important;border-radius:50% !important;margin-top:12px !important;transition:.2s linear all;}

#RANbutton-frame .guild-inner:hover{border-radius:15px !important;background-color:var(--main-color) !important;}

#RANbutton{line-height:43px !important;}

.theme-light .nameDefault-Lnjrwm, .theme-light .nameCollapsed-3_ChMu{color: #000 !important;}
 
.theme-light div[class*=wrapperCollapsed-]>div[class*=nameCollapsed-]:after, .theme-light div[class*=wrapperCollapsed-]>div[class*=nameCollapsed-]:before, .theme-light div[class*=wrapperCollapsed-]>div[class*=nameDefault-]:after, .theme-light div[class*=wrapperCollapsed-]>div[class*=nameDefault-]:before, .theme-light div[class*=wrapperCollapsed-]>div[class*=nameHovered-]:after, .theme-light div[class*=wrapperCollapsed-]>div[class*=nameHovered-]:before, .theme-light div[class*=wrapperCollapsed-]>div[class*=nameHoveredCollapsed-]:after, .theme-light div[class*=wrapperCollapsed-]>div[class*=nameHoveredCollapsed-]:before, .theme-light div[class*=wrapperDefault-]>div[class*=nameCollapsed-]:after, .theme-light div[class*=wrapperDefault-]>div[class*=nameCollapsed-]:before, .theme-light div[class*=wrapperDefault-]>div[class*=nameDefault-]:after, .theme-light div[class*=wrapperDefault-]>div[class*=nameDefault-]:before, .theme-light div[class*=wrapperDefault-]>div[class*=nameHovered-]:after, .theme-light div[class*=wrapperDefault-]>div[class*=nameHovered-]:before, .theme-light div[class*=wrapperDefault-]>div[class*=nameHoveredCollapsed-]:after, .theme-light div[class*=wrapperDefault-]>div[class*=nameHoveredCollapsed-]:before, .theme-light div[class*=wrapperHovered-]>div[class*=nameCollapsed-]:after, .theme-light div[class*=wrapperHovered-]>div[class*=nameCollapsed-]:before, .theme-light div[class*=wrapperHovered-]>div[class*=nameDefault-]:after, .theme-light div[class*=wrapperHovered-]>div[class*=nameDefault-]:before, .theme-light div[class*=wrapperHovered-]>div[class*=nameHovered-]:after, .theme-light div[class*=wrapperHovered-]>div[class*=nameHovered-]:before, .theme-light div[class*=wrapperHovered-]>div[class*=nameHoveredCollapsed-]:after, .theme-light div[class*=wrapperHovered-]>div[class*=nameHoveredCollapsed-]:before, .theme-light div[class*=wrapperHoveredCollapsed-]>div[class*=nameCollapsed-]:after, .theme-light div[class*=wrapperHoveredCollapsed-]>div[class*=nameCollapsed-]:before, .theme-light div[class*=wrapperHoveredCollapsed-]>div[class*=nameDefault-]:after, .theme-light div[class*=wrapperHoveredCollapsed-]>div[class*=nameDefault-]:before, .theme-light div[class*=wrapperHoveredCollapsed-]>div[class*=nameHovered-]:after, .theme-light div[class*=wrapperHoveredCollapsed-]>div[class*=nameHovered-]:before, .theme-light div[class*=wrapperHoveredCollapsed-]>div[class*=nameHoveredCollapsed-]:after, .theme-light div[class*=wrapperHoveredCollapsed-]>div[class*=nameHoveredCollapsed-]:before, .theme-light div[class*=wrapperMuted-]>div[class*=nameMuted-]:after, .theme-light div[class*=wrapperMuted-]>div[class*=nameMuted-]:before {background: #000 !important;}

.guilds-wrapper .guilds .friends-online{margin: 0px -13px;background: #121213;border-radius: 0px;line-height: 19px;width: 75px;padding-top: 6px;padding-bottom: 3px;transition: background .2s linear, color .2s linear;cursor: pointer;}

.guilds-wrapper .guilds .friends-online:hover{color: #fff !important;background: var(--main-color);}

.theme-dark .chat [class*="autocomplete-"]{box-shadow: 0px 0px 6px 0px transparent;border-radius: 0px !important;margin-bottom: 12px !important;border-left: 2px solid #212121 !important;border-top: 2px solid #212121 !important;border-right: 2px solid #212121 !important;}

.tooltip.tooltip-black.tooltip-left:after{border-left-color: var(--main-color);}

.theme-dark .friends-table .scroller-wrap ::-webkit-scrollbar-track-piece, .theme-dark .messages-wrapper .scroller-wrap ::-webkit-scrollbar-track-piece {
    background-color: #121213;}

.theme-dark .friends-table .scroller-wrap ::-webkit-scrollbar-thumb, .theme-dark .messages-wrapper .scroller-wrap ::-webkit-scrollbar-thumb {
    background-color: var(--main-color);}

@media screen and (max-width:1100px){.chat .content .flex-spacer.flex-vertical:only-child .message-group .comment .markup{max-width:95%;}

.chat .content .flex-spacer.flex-vertical:not(:only-child) .message-group .comment .markup{max-width:85%;}

}

@media screen and (max-width:1020px){.chat .content .flex-spacer.flex-vertical:only-child .message-group .comment .markup{max-width:90%;}

.chat .content .flex-spacer.flex-vertical:not(:only-child) .message-group .comment .markup{max-width:80%;}

}

@media screen and (max-width:970px){.flex-vertical.channels-wrap{z-index:0;width:0px;transition:width linear .3s;height:100%;background:transparent;border-right:solid transparent 0px;}

.guilds-wrapper:hover ~ .flex-vertical.channels-wrap, .flex-vertical.channels-wrap:hover{width:25%;border-right:0px solid transparent;z-index: 3 !important;}
	
.theme-dark .guilds-wrapper:hover ~ .chat form,  .theme-dark .flex-vertical.channels-wrap:hover ~ .chat form{border-left: 2px solid #212121 !important;}

.channel-members{transform:translate(145px);z-index:2;transition:all 300ms ease;}

.channel-members:hover{animation:member 300ms ease;transform:translate(0px);box-shadow:4px 0 10px 6px rgba(0, 0, 0, 0.32);}

.channel-members h2{width:100px !important;margin-left:8px !important;}

.channel-members .member .member-activity,.channel-members .member .member-username-inner{opacity:0;transition:opacity 300ms ease, margin 100ms ease;}

.channel-members .member .member-username-inner{margin-bottom:6px;}

.channel-members:hover .member .member-activity,.channel-members:hover .member .member-username-inner{opacity:1;}

.header-toolbar button.active{display:none;}

.channel-members h2{transform-origin:left;transform:scale(0.7);padding:6px;transition:all 300ms ease;color:#fff !important;}

.channel-members:hover h2{transform:scale(1);padding:4px 58px;}

.channel-members .avatar-small{transform:scale(1.2);}

.channel-members:hover .avatar-small{transform:scale(1);}

.chat.flex-vertical.flex-spacer>.content.flex-spacer.flex-horizontal>.flex-spacer.flex-vertical{margin-right:-145px !important;z-index:1}

.chat.flex-vertical.flex-spacer.private>.content.flex-spacer.flex-horizontal>.flex-spacer.flex-vertical{margin-right:0px;z-index:1}

.channel-members::after{content: var(--theme-letter)" v"var(--version-content);font-size: 210%;left: -65px;}
	
[class*="scroller-"].channel-members{height: 100%;transform: translate(142px);}

[class*="scroller-"].channel-members:hover{animation: member 300ms ease;transform: translate(0px);box-shadow: 4px 0 10px 6px rgba(0, 0, 0, 0.32);}

.channel-members:hover::after{display: none;}

.container-iksrDt{margin-left: 0px;}

.scroller-wrap .scroller::-webkit-scrollbar{width: 0px;}
	
.scroller.messages::-webkit-scrollbar{width: 12px !important;visibility: hidden;}

.scroller.messages:hover::-webkit-scrollbar{width: 12px !important;visibility: visible;}

.guilds-wrapper .scroller-wrap{width: 75px;}

.guilds-wrapper .guilds-add {
    bottom: 0px !important;
}
}

@media screen and (max-width:725px){.chat.private .content .message-group:not(.compact) h2 .timestamp{display:none;}

}

@media screen and (max-width:430px){.chat .content .flex-spacer.flex-vertical:not(:only-child) ~ .channel-members-wrap{cursor:not-allowed;position:fixed;width:100%;height:100%;background-color:rgba(0, 0, 0, 0.75);background-size:cover;background-position:center center;background-repeat:no-repeat;border-radius:5px;top:0;right:0;bottom:0;left:inherit;z-index:1000;}

.chat .content .flex-spacer.flex-vertical:not(:only-child) ~ .channel-members-wrap:before{content:"Media screen size too small";color:#fff;margin:auto;font-size:2rem;text-align:center;}

.chat .content .flex-spacer.flex-vertical:not(:only-child) ~ .channel-members-wrap .scroller-wrap{display:none;}

.chat:not(.private) .content .message-group:not(.compact) h2 .timestamp{display:block;}

}

@media screen and (max-width:340px){.message-group h2{max-width:60%;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}

.emoji-picker{width:90%;}

}

.iconMuted-Hb4ttQ, .nameMuted-1n0LSj {color: #6e6e6f;opacity: 0.5;}

.member-perms .member-perm{background-color: var(--main-color) !important;border: 1px solid var(--main-color)!important;border-radius: 3px !important;color: #fff !important;font-weight: 600 !important;text-shadow: 0px 0px 2px #000 !important;}

.member-perms::-webkit-scrollbar{width: 0px;}

#permissions-modal-wrapper .role-side{background: #121213;}

#permissions-modal-wrapper .header{background: #121213;}

#permissions-modal-wrapper .perm-side{background-color: #19191b;}

/* editor container styling */

#bd-settingspane-container .content-column.default>div h2{text-shadow:rgba(0, 0, 0, 0.4) 1px 1px 1px;text-transform:uppercase !important;font-style:normal !important;font-size:16px !important;font-weight:600 !important; font-family: 'Whitney', sans-serif !important;}

#bd-settingspane-container .content-column.default>div h2:after{text-shadow:rgba(0, 0, 0, 0.4) 1px 1px 1px;font-size:16px;font-style: normal;font-family: 'Consolas', monospace;text-align:left !important;}

#bd-settingspane-container .CodeMirror-gutters,#bd-settingspane-container .CodeMirror-sizer{background-color:#1a1a1a !important;}

#bd-settingspane-container .CodeMirror-linenumber{color:#9e9e9e !important;background-color:#1a1a1a;}

#bd-settingspane-container .CodeMirror-linenumbers{color:#9e9e9e !important;background-color:#1a1a1a;}

#bd-settingspane-container .CodeMirror-cursor{border-color:#4286f4;}

#bd-settingspane-container .tools {margin-left: 10px !important;width:auto;}

.CodeMirror.cm-s-material.CodeMirror-simplescroll{border: solid 2px var(--main-color);border-bottom:none !important;border-radius: 2px !important;}

.CodeMirror-code{font-family:'Ubuntu Mono', monospace;font-size:15px;line-height:15px;text-shadow:rgba(0, 0, 0, 0.4) 1px 1px 1px;text-align:left;color:#dcdcdc;background-color:#1a1a1a;}

/* syntax styling */
.cm-comment{color:#51707e !important;}

.cm-qualifier{color:#ffac58 !important;}

.cm-variable-3{color:#72bdff !important;font-style:italic;}

.cm-tag{color:#ff6f4f !important;font-style:italic;}

.cm-string{color:#8bff8b !important;}

.cm-property{color:#54fff4 !important;}

.cm-atom{color:#ff7e7e !important;font-style:italic;}

.cm-number{color:#d2dd86 !important;}

.cm-meta{color:#7280ff !important;}

.cm-tab{visibility:hidden;font-size:0;}

.cm-tab:after{content:' ';visibility:visible;font-size:initial;}

.cm-keyword{color:#ff39ff !important;font-style:italic;}

/* editor controls styles */
#bd-customcss-attach-controls{height:90px;}

#bd-customcss-attach-controls .checkbox {margin-left:5px;}

#bd-customcss-attach-controls .checkbox span{text-shadow:rgba(0, 0, 0, 0.4) 1px 1px 1px;color:#f1f1f1;font-family:'Ubuntu Mono',monospace;font-size:20px;font-style:italic;}

#bd-customcss-attach-controls {width: 100%; border:solid 2px var(--main-color) !important;border-top:none!important;}

#bd-customcss-attach-controls .checkbox-inner input[type='checkbox']:checked+span{text-shadow: rgba(0, 0, 0, 0.4) 1px 1px 1px;background-color: #4286f4;border-color: #4286f4;}

#bd-customcss-detach-controls-button .btn{text-shadow:rgba(0, 0, 0, 0.4) 1px 1px 1px;}

#bd-customcss-detach-controls-button span{text-shadow:rgba(0, 0, 0, 0.4) 1px 1px 1px;display:block;padding-top:4px;margin-bottom:10px;font-family:'Ubuntu Mono',monospace;font-style:italic;font-size:18px!important;}
    
#bd-customcss-attach-controls:after {margin-left: -7px;margin-top: 25px !important;width:640px !important;text-shadow:rgba(0,0,0,0.4) 1px 1px 1px;}

/* detached editor styles */
#editor-detached button.btn{text-shadow:rgba(0, 0, 0, 0.4) 1px 1px 1px;background-color:#4286f4;}

#editor-detached {margin-top:0px!important;}
   
#editor-detached h2:after {padding-right: 0px; width:530px;content: "Hi, I have a server where I post customizable options for the \A theme and you can give me feedback, also with tons of bots. \A Join the server at \A\A discord.me/mrrobotserver \A\A It's also easier to report bugs and has a higher chance of \A getting them fixed faster."!important;}

#editor-detached h3 {color: #f1f1f1 !important; margin-top: 10px;}

#bd-customcss-detach-container {padding-top:46px; background-color: #1a1a1a; padding-bottom: 4px;text-shadow:rgba(0, 0, 0, 0.4) 1px 1px 1px;}

#bd-customcss-detach-editor .CodeMirror.cm-s-material.CodeMirror-simplescroll{border-radius:0px!important;}
/* editor page styles */
#app-mount .ui-standard-sidebar-view .content-column[style]{padding: 60px 40px 0px !important;max-width:740px;min-width:460px;}

#app-mount .titleWrapper-3Vi_wz{border-bottom: solid 2px var(--main-color);background-color: #19191b;margin-top: -2px;}

#app-mount .titleWrapper-3Vi_wz > div{background-color: #19191b;}

#app-mount > [class*="platform-"] .scroller-wrap .guilds.scroller .guild:first-child{margin-top: 19px;}

.mask-2vyqAW{-webkit-mask: none!important;border-radius 5% !important}

.private-channels{background-color: #19191b !important;}

#friends > .headerBar-cxbhPD{background-color: #19191b !important;border-bottom: solid 2px var(--main-color);height: 46px;}

.guilds-add{bottom: 0px !important;}

.typeWindows-15E0Ys{margin-top: 1px;background-color: #19191b;}

.image-EVRGPw{border-radius: 0px;}

.title-qAcLxz {box-shadow: 0 0px 0 transparent !important;}

[d="M3.57642276,0.141304348 L0,0.141304348 L0,4.22826087 L2.38069106,6.40217391 L2.38069106,2.43478261 L3.66260163,2.43478261 C4.47052846,2.43478261 4.86910569,2.83695652 4.86910569,3.4673913 L4.86910569,6.5 C4.86910569,7.13043478 4.49207317,7.55434783 3.66260163,7.55434783 L0,7.55434783 L0,9.85869565 L3.57642276,9.85869565 C5.49390244,9.86956522 7.29288618,8.90217391 7.29288618,6.66304348 L7.29288618,3.39130435 C7.29288618,1.13043478 5.49390244,0.141304348 3.57642276,0.141304348 Z M22.3310976,6.67391304 L22.3310976,3.32608696 C22.3310976,2.11956522 24.4640244,1.83695652 25.1103659,3.05434783 L27.0817073,2.23913043 C26.3168699,0.510869565 24.8949187,0 23.7207317,0 C21.803252,0 19.9073171,1.13043478 19.9073171,3.32608696 L19.9073171,6.67391304 C19.9073171,8.88043478 21.803252,10 23.6776423,10 C24.8841463,10 26.3276423,9.39130435 27.1247967,7.81521739 L25.0134146,6.82608696 C24.4963415,8.17391304 22.3310976,7.84782609 22.3310976,6.67391304 Z M15.8030488,3.7826087 C15.0597561,3.61956522 14.5642276,3.34782609 14.5319106,2.88043478 C14.575,1.75 16.2878049,1.7173913 17.2896341,2.79347826 L18.8731707,1.55434783 C17.8821138,0.326086957 16.7617886,0 15.598374,0 C13.8424797,0 12.1404472,1 12.1404472,2.91304348 C12.1404472,4.77173913 13.5408537,5.76086957 15.0813008,6 C15.8676829,6.10869565 16.7402439,6.42391304 16.7186992,6.97826087 C16.654065,8.02173913 14.5426829,7.9673913 13.5839431,6.7826087 L12.0650407,8.23913043 C12.9591463,9.40217391 14.1764228,10 15.3182927,10 C17.074187,10 19.0239837,8.9673913 19.0993902,7.08695652 C19.2071138,4.69565217 17.5050813,4.09782609 15.8030488,3.7826087 Z M8.59634146,9.85869565 L11.0093496,9.85869565 L11.0093496,0.141304348 L8.59634146,0.141304348 L8.59634146,9.85869565 Z M49.2835366,0.141304348 L45.7071138,0.141304348 L45.7071138,4.22826087 L48.0878049,6.40217391 L48.0878049,2.43478261 L49.3589431,2.43478261 C50.1668699,2.43478261 50.5654472,2.83695652 50.5654472,3.4673913 L50.5654472,6.5 C50.5654472,7.13043478 50.1884146,7.55434783 49.3589431,7.55434783 L45.6963415,7.55434783 L45.6963415,9.85869565 L49.2727642,9.85869565 C51.1902439,9.86956522 52.9892276,8.90217391 52.9892276,6.66304348 L52.9892276,3.39130435 C53,1.13043478 51.2010163,0.141304348 49.2835366,0.141304348 Z M31.7353659,0 C29.753252,0 27.7819106,1.09782609 27.7819106,3.33695652 L27.7819106,6.66304348 C27.7819106,8.89130435 29.7640244,10 31.7569106,10 C33.7390244,10 35.7103659,8.89130435 35.7103659,6.66304348 L35.7103659,3.33695652 C35.7103659,1.10869565 33.7174797,0 31.7353659,0 Z M33.2865854,6.66304348 C33.2865854,7.35869565 32.5109756,7.7173913 31.7461382,7.7173913 C30.9705285,7.7173913 30.1949187,7.36956522 30.1949187,6.66304348 L30.1949187,3.33695652 C30.1949187,2.61956522 30.9489837,2.23913043 31.7030488,2.23913043 C32.4894309,2.23913043 33.2865854,2.58695652 33.2865854,3.33695652 L33.2865854,6.66304348 Z M44.3605691,3.33695652 C44.3067073,1.05434783 42.7770325,0.141304348 40.8056911,0.141304348 L36.9815041,0.141304348 L36.9815041,9.86956522 L39.4268293,9.86956522 L39.4268293,6.77173913 L39.8577236,6.77173913 L42.0768293,9.85869565 L45.0930894,9.85869565 L42.4861789,6.52173913 C43.6495935,6.15217391 44.3605691,5.14130435 44.3605691,3.33695652 Z M40.8487805,4.65217391 L39.4268293,4.65217391 L39.4268293,2.43478261 L40.8487805,2.43478261 C42.3784553,2.43478261 42.3784553,4.65217391 40.8487805,4.65217391 Z"]{fill: transparent;}

.wordmark-2L03Wr::after{content: var(--theme-name)" "var(--version-content);font-family: "Roboto";color: #fff; font-size: 16px;font-weight: 600;position: fixed; left: 7px; top: 4px;}

.chat .divider.divider-red > span {color:var(--main-color) !important;}

.theme-light .guilds-wrapper .guilds .friends-online {background: #ececec;}

.theme-light .guilds-wrapper .guilds .friends-online:hover {background: var(--main-color);}

#app-mount .theme-light .titleWrapper-3Vi_wz > div{background-color: #fff;}

.theme-light .textArea-20yzAH{color: #515151;}

.theme-light .inner-3if5cm{background-color: #ffffff;}

.theme-light .attachButtonDivider-3tknGJ {background-color: transparent;}

.header-1tSljs{box-shadow: 0px 0 transparent;}

#friends .tab-bar .tab-bar-item.selected {background-color: var(--main-color) !important;color: #fff!important;}

.theme-light .private-channels{background-color: #ffffff !important;}

.theme-light .private-channels .channel .channel-activity{color: #2c2828;}

.theme-light .private-channels .channel:hover .channel-activity{color: #000;}

.theme-light .private-channels .channel .link-button-icon{filter: invert();}

.theme-light .private-channels .search-bar-inner{background: #ececec !important;}

.theme-light .private-channels .search-bar input::-webkit-input-placeholder{color: #000;}

/* Reposition status bar */

.status-picker.popout-menu{left:76px!important;width:220px !important;height:64px !important;border-right: 2px solid #212121 !important;border-top: 2px solid #212121 !important;border-left: 2px solid #212121 !important;background: #19191b !important;}
 
.status-picker .popout-menu-item:hover:nth-of-type(5) > .status-icon-text > .status-text{margin-top:-38px !important;margin-left:0px !important;}

.status-picker .popout-menu-item:hover:nth-of-type(5) > .status-icon-text > .status-text:after{content:"▼" !important;margin-top:16px !important;margin-left:-33px !important;}

.status-picker .popout-menu-item:hover:nth-of-type(4) > .status-icon-text > .status-text{margin-top:-38px !important;margin-left:0px !important;}

.status-picker .popout-menu-item:hover:nth-of-type(4) > .status-icon-text > .status-text:after{content:"▼" !important;margin-top:16px !important;margin-left:-55px !important;}

.status-picker .popout-menu-item:hover:nth-of-type(3) > .status-icon-text > .status-text{margin-top:-38px !important;margin-left:0px !important;}

.status-picker .popout-menu-item:hover:nth-of-type(3) > .status-icon-text > .status-text:after{content:"▼" !important;margin-top:16px !important;margin-left:-19px !important;}

.status-picker .popout-menu-item:hover:nth-of-type(1) > .status-icon-text > .status-text{margin-top:-38px !important;margin-left:0px !important;}

.status-picker .popout-menu-item:hover:nth-of-type(1) > .status-icon-text > .status-text:after{content:"▼" !important;margin-top:16px !important;margin-left:-26px !important;}

/* End reposition status bar */

.guilds-wrapper .guilds-add{background-color: var(--main-color) !important;bottom: 15px !important;width: 45px !important;border-radius: 50px;left: 14px;height: 45px !important;font-size: 0px !important;line-height: 1px !important;box-shadow: 0px 3px 8px 1px rgba(0, 0, 0, 0.5) !important;border: 0px solid transparent !important;}

.guilds-wrapper .guilds-add:hover{background-color: var(--hover-color) !important;height: 45px !important;width: 45px !important;line-height: 1px !important;font-size: 0px !important;transform: scale(1) !important;box-shadow: 0px 3px 8px 1px rgba(0, 0, 0, 0.7) !important;}

.guilds-wrapper .guilds-add-inner{background-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMTIxNCIgd2lkdGg9IjEwNSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHZpZXdCb3g9IjAgMCAxMDUgMTIxNCI+PHBhdGggZD0iTTI1IDk1NmgyNHYyNEgyNXoiIGZpbGw9Im5vbmUiLz48cGF0aCBkPSJNMjkgOTYyaC0ydjE0YzAgMS4xLjkgMiAyIDJoMTR2LTJIMjl2LTE0em0xNi00SDMzYy0xLjEgMC0yIC45LTIgMnYxMmMwIDEuMS45IDIgMiAyaDEyYzEuMSAwIDItLjkgMi0ydi0xMmMwLTEuMS0uOS0yLTItMnptLTEgOWgtNHY0aC0ydi00aC00di0yaDR2LTRoMnY0aDR2MnoiIGZpbGw9IiNmZmYiLz48ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg1MCA4ODEpIj48c3ltYm9sIGlkPSJhIiB2aWV3Qm94PSIwIC0yNCAyNCAyNCI+PHBhdGggZD0iTTE5LTEzaC02di02aC0ydjZINXYyaDZ2Nmgydi02aDZ2LTJ6Ii8+PHBhdGggZmlsbD0ibm9uZSIgZD0iTTI0LTI0SDBWMGgyNHoiLz48L3N5bWJvbD48dXNlIHhsaW5rOmhyZWY9IiNhIiB0cmFuc2Zvcm09InNjYWxlKDEgLTEpIiBoZWlnaHQ9IjI0IiB3aWR0aD0iMjQiIHk9Ii0yNCIgb3ZlcmZsb3c9InZpc2libGUiLz48L2c+PGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoNjkgNjE0KSI+PHRpdGxlPlNsaWNlIDE8L3RpdGxlPjxnIHNrZXRjaDp0eXBlPSJNU1NoYXBlR3JvdXAiIHhtbG5zOnNrZXRjaD0iaHR0cDovL3d3dy5ib2hlbWlhbmNvZGluZy5jb20vc2tldGNoL25zIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGZpbGw9Im5vbmUiPjxwYXRoIGQ9Ik0tNjg2LTE3ODFINzE0djM2MDBILTY4NnoiLz48cGF0aCBkPSJNMTkgMTNoLTZ2NmgtMnYtNkg1di0yaDZWNWgydjZoNnYyeiIgZmlsbD0iI2ZmZiIvPjxwYXRoIGQ9Ik0wIDBoMjR2MjRIMHoiLz48L2c+PC9nPjxwYXRoIGQ9Ik00NS41NCA4ODYuMjNsLTEuMzktMS42OGMtLjI3LS4zNC0uNjgtLjU1LTEuMTUtLjU1SDMxYy0uNDcgMC0uODguMjEtMS4xNi41NWwtMS4zOCAxLjY4Yy0uMjkuMzQtLjQ2Ljc5LS40NiAxLjI3VjkwMGMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0ydi0xMi41YzAtLjQ4LS4xNy0uOTMtLjQ2LTEuMjd6TTM3IDg5OC41bC01LjUtNS41SDM1di0yaDR2MmgzLjVsLTUuNSA1LjV6TTMwLjEyIDg4NmwuODEtMWgxMmwuOTQgMUgzMC4xMnoiLz48cGF0aCBkPSJNMjUgODgxaDI0djI0SDI1eiIgZmlsbD0ibm9uZSIvPjxwYXRoIGQ9Ik0yMC41NCAxMDA3LjIzbC0xLjM5LTEuNjhjLS4yNy0uMzQtLjY4LS41NS0xLjE1LS41NUg2Yy0uNDcgMC0uODguMjEtMS4xNi41NWwtMS4zOCAxLjY4Yy0uMjkuMzQtLjQ2Ljc5LS40NiAxLjI3djEyLjVjMCAxLjEuOSAyIDIgMmgxNGMxLjEgMCAyLS45IDItMnYtMTIuNWMwLS40OC0uMTctLjkzLS40Ni0xLjI3ek0xMiAxMDE5LjVsLTUuNS01LjVIMTB2LTJoNHYyaDMuNWwtNS41IDUuNXpNNS4xMiAxMDA3bC44MS0xaDEybC45NCAxSDUuMTJ6IiBmaWxsPSIjZmZmIi8+PHBhdGggZD0iTTAgMTAwMmgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjxwYXRoIGZpbGw9IiMyMzFGMjAiIGQ9Ik03IDk0MWw1IDUgNS01eiIvPjxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDk0IDYyNSkiPjx0aXRsZT5JbXBvcnRlZCBFUFM8L3RpdGxlPjxwYXRoIHNrZXRjaDp0eXBlPSJNU1NoYXBlR3JvdXAiIGQ9Ik0wIDBsNSA1IDUtNUgwIiBmaWxsPSIjZmZmIiB4bWxuczpza2V0Y2g9Imh0dHA6Ly93d3cuYm9oZW1pYW5jb2RpbmcuY29tL3NrZXRjaC9ucyIgZmlsbC1ydWxlPSJldmVub2RkIi8+PC9nPjxwYXRoIGQ9Ik05MC40MSA5NzIuMDlsLTQuNTgtNC41OSA0LjU4LTQuNTlMODkgOTYxLjVsLTYgNiA2IDZ6Ii8+PHBhdGggZD0iTTc1IDk1NS41aDI0djI0SDc1eiIgZmlsbD0ibm9uZSIvPjxwYXRoIGQ9Ik0xNS40MSA3NzYuMDlsLTQuNTgtNC41OSA0LjU4LTQuNTlMMTQgNzY1LjVsLTYgNiA2IDZ6IiBmaWxsPSIjZmZmIi8+PHBhdGggZD0iTTAgNzU5LjVoMjR2MjRIMHoiIGZpbGw9Im5vbmUiLz48cGF0aCBkPSJNNTAuNTkgMTYuMzRsNC41OC00LjU5LTQuNTgtNC41OUw1MiA1Ljc1bDYgNi02IDZ6Ii8+PHBhdGggZD0iTTQyLS4yNWgyNHYyNEg0MnoiIGZpbGw9Im5vbmUiLz48cGF0aCBmaWxsPSIjMjMxRjIwIiBkPSJNNjcgOTQ2bC01LTUtNSA1eiIvPjxwYXRoIGQ9Ik0wIDExM2gyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjxwYXRoIGQ9Ik0xOSAxMTZoLTQuMThjLS40Mi0xLjE2LTEuNTItMi0yLjgyLTJzLTIuNC44NC0yLjgyIDJINWMtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxNGMxLjEgMCAyLS45IDItMnYtMTRjMC0xLjEtLjktMi0yLTJ6bS03IDBjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXptMiAxNEg3di0yaDd2MnptMy00SDd2LTJoMTB2MnptMC00SDd2LTJoMTB2MnoiLz48cGF0aCBkPSJNODQgODk2aDI0djI0SDg0di0yNHoiIGZpbGw9Im5vbmUiLz48cGF0aCBkPSJNOTQgODg1aC00LjE4NWMtLjQxLTEuMTYtMS41MS0yLTIuODE1LTJzLTIuNDA1Ljg0LTIuODE1IDJIODBhMiAyIDAgMCAwLTIgMnYxNGEyIDIgMCAwIDAgMiAyaDE0YTIgMiAwIDAgMCAyLTJ2LTE0YTIgMiAwIDAgMC0yLTJ6bS03IDBhMSAxIDAgMSAxIDAgMiAxIDEgMCAwIDEgMC0yem0yIDE0aC03di0yaDd2MnptMy00SDgydi0yaDEwdjJ6bTAtNEg4MnYtMmgxMHYyeiIgZmlsbD0iI2ZmZiIvPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0tNTY4LTU4MEg4MzJ2MzYwMEgtNTY4eiIvPjxwYXRoIGQ9Ik02Ni41IDExNDZ2MTEuNWMwIDIuMi0xLjggNC00IDRzLTQtMS44LTQtNFYxMTQ1YzAtMS40IDEuMS0yLjUgMi41LTIuNXMyLjUgMS4xIDIuNSAyLjV2MTAuNWMwIC42LS40IDEtMSAxcy0xLS40LTEtMXYtOS41SDYwdjkuNWMwIDEuNCAxLjEgMi41IDIuNSAyLjVzMi41LTEuMSAyLjUtMi41VjExNDVjMC0yLjItMS44LTQtNC00cy00IDEuOC00IDR2MTIuNWMwIDMgMi41IDUuNSA1LjUgNS41czUuNS0yLjUgNS41LTUuNVYxMTQ2aC0xLjV6Ii8+PHBhdGggZmlsbD0ibm9uZSIgZD0iTTUwIDExNDBoMjR2MjRINTB6Ii8+PGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCAxMTkwKSI+PHN5bWJvbCBpZD0iYiIgdmlld0JveD0iMCAtMjQgMjQgMjQiPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0wIDB2LTI0aDI0VjB6Ii8+PHBhdGggZD0iTTIwLTExSDcuODI4bDUuNTg2IDUuNTg2TDEyLTRsLTgtOCA4LTggMS40MTQgMS40MTRMNy44MjgtMTNIMjB2MnoiLz48L3N5bWJvbD48dXNlIHhsaW5rOmhyZWY9IiNiIiB0cmFuc2Zvcm09InNjYWxlKDEgLTEpIiBoZWlnaHQ9IjI0IiB3aWR0aD0iMjQiIHk9Ii0yNCIgb3ZlcmZsb3c9InZpc2libGUiLz48L2c+PGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCA0NDcpIj48dGl0bGU+SWNvbjwvdGl0bGU+PGcgc2tldGNoOnR5cGU9Ik1TQXJ0Ym9hcmRHcm91cCIgeG1sbnM6c2tldGNoPSJodHRwOi8vd3d3LmJvaGVtaWFuY29kaW5nLmNvbS9za2V0Y2gvbnMiIGZpbGwtcnVsZT0iZXZlbm9kZCIgZmlsbD0ibm9uZSI+PHBhdGggZD0iTS03IDExaDI0djI0SC03eiIgc2tldGNoOnR5cGU9Ik1TU2hhcGVHcm91cCIvPjxwYXRoIGQ9Ik03LjggMTFsNS42LTUuNkwxMiA0bC04IDggOCA4IDEuNC0xLjRMNy44IDEzSDIwdi0ySDcuOHoiIGZpbGw9IiNmZmYiLz48L2c+PC9nPjxwYXRoIGQ9Ik02NyA3NDdoLTV2NWg1di01em0tMS0xMXYyaC04di0yaC0ydjJoLTFjLTEuMTEgMC0xLjk5LjktMS45OSAyTDUzIDc1NGEyIDIgMCAwIDAgMiAyaDE0YzEuMSAwIDItLjkgMi0ydi0xNGMwLTEuMS0uOS0yLTItMmgtMXYtMmgtMnptMyAxOEg1NXYtMTFoMTR2MTF6Ii8+PHBhdGggZD0iTTUwIDczNWgyNHYyNEg1MHoiIGZpbGw9Im5vbmUiLz48cGF0aCBmaWxsPSJub25lIiBkPSJNLTU0My02MDhIODU3djM2MDBILTU0M3oiLz48cGF0aCBkPSJNOTQgODYxdjE0SDgwdi0xNGgxNG0wLTJIODBjLTEuMSAwLTIgLjktMiAydjE0YzAgMS4xLjkgMiAyIDJoMTRjMS4xIDAgMi0uOSAyLTJ2LTE0YzAtMS4xLS45LTItMi0yeiIvPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik03NSA4NTZoMjR2MjRINzV6Ii8+PHBhdGggZmlsbD0ibm9uZSIgZD0iTS02MTgtMTg4SDc4MnYzNjAwSC02MTh6Ii8+PHBhdGggZmlsbD0ibm9uZSIgZD0iTTAgODkyaDI0djI0SDB6Ii8+PHBhdGggZD0iTTE5IDg5NUg1Yy0xLjEgMC0yIC45LTIgMnYxNGMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0ydi0xNGMwLTEuMS0uOS0yLTItMnptLTkgMTRsLTUtNSAxLjQtMS40IDMuNiAzLjYgNy42LTcuNkwxOSA5MDBsLTkgOXoiLz48cGF0aCBmaWxsPSIjMjMxRjIwIiBkPSJNODYuODU4IDc3Ni4zNTFsNi02LTEuNS0xLjUtNC41IDQuNS00LjUtNC41LTEuNSAxLjV6Ii8+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTExLjg1OCAyMjUuMzUxbDYtNi0xLjUtMS41LTQuNSA0LjUtNC41LTQuNS0xLjUgMS41eiIvPjxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAgMTE0MCkiPjxzeW1ib2wgaWQ9ImMiIHZpZXdCb3g9IjAgLTI0IDI0IDI0Ij48cGF0aCBmaWxsPSJub25lIiBkPSJNMjQtMjRIMFYwaDI0eiIvPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0yNC0yNFYwSDB2LTI0eiIvPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0yNCAwdi0yNEgwVjB6Ii8+PHBhdGggZmlsbD0iIzIzMUYyMCIgZD0iTTEyLThsNi02LTEuNS0xLjVMMTItMTFsLTQuNS00LjVMNi0xNHoiLz48cGF0aCBmaWxsPSJub25lIiBkPSJNMjQgMHYtMjRIMFYweiIvPjwvc3ltYm9sPjx1c2UgeGxpbms6aHJlZj0iI2MiIHRyYW5zZm9ybT0ic2NhbGUoMSAtMSkiIGhlaWdodD0iMjQiIHdpZHRoPSIyNCIgeT0iLTI0IiBvdmVyZmxvdz0idmlzaWJsZSIvPjwvZz48cGF0aCBmaWxsPSIjMjMxRjIwIiBkPSJNMTkuMDY0IDEwNTAuNDI5bC0xLjQxNC0xLjQxNC01LjU4NiA1LjU4Ni01LjU4NS01LjU4Ni0xLjQxNSAxLjQxNCA1LjU4NiA1LjU4Ni01LjU4NiA1LjU4NyAxLjQxNSAxLjQxNCA1LjU4NS01LjU4NiA1LjU4NiA1LjU4NiAxLjQxNC0xLjQxNC01LjU4NS01LjU4N3oiLz48cGF0aCBmaWxsPSIjZmZmIiBkPSJNNDQuMDY0IDkzNy40MjlsLTEuNDE0LTEuNDE0LTUuNTg2IDUuNTg2LTUuNTg1LTUuNTg2LTEuNDE1IDEuNDE0IDUuNTg2IDUuNTg2LTUuNTg2IDUuNTg3IDEuNDE1IDEuNDE0IDUuNTg1LTUuNTg2IDUuNTg2IDUuNTg2IDEuNDE0LTEuNDE0LTUuNTg1LTUuNTg3eiIvPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0tNTkzLTcwNEg4MDd2MzYwMEgtNTkzeiIvPjxwYXRoIGQ9Ik00NyA3NjRjMC0xLjEtLjktMi0yLTJIMjljLTEuMSAwLTIgLjktMiAydjEyYzAgMS4xLjkgMiAyIDJoMTRsNCA0di0xOHptLTQgMTBIMzF2LTJoMTJ2MnptMC0zSDMxdi0yaDEydjJ6bTAtM0gzMXYtMmgxMnYyeiIvPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0yNSA3NjBoMjR2MjRIMjV6Ii8+PHBhdGggZD0iTTcxLjk5IDg2MGMwLTEuMS0uODktMi0xLjk5LTJINTRjLTEuMSAwLTIgLjktMiAydjEyYzAgMS4xLjkgMiAyIDJoMTRsNCA0LS4wMS0xOHpNNjggODcwSDU2di0yaDEydjJ6bTAtM0g1NnYtMmgxMnYyem0wLTNINTZ2LTJoMTJ2MnoiIGZpbGw9IiNmZmYiLz48cGF0aCBkPSJNNTAgODU2aDI0djI0SDUweiIgZmlsbD0ibm9uZSIvPjxnIGZpbGw9IiMyMzFGMjAiPjxwYXRoIGQ9Ik02Ny44NjMgMjI4LjkyOEg1Ni4yN2wzLjMwNi01Ljc5MWgxMS40NjJ6TTY1LjE4IDIxMy4xNDdsNi4wNyA5LjAxN2gtNi42ODRsLTYuMDY5LTkuMDE4ek02MS4wOTIgMjE4LjkwNmwtNS41MzcgOS45MzItMy4zMDUtNi4xNTIgNS4wNzItOS42MTR6Ii8+PC9nPjxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDI1IDkwNikiPjxzeW1ib2wgaWQ9ImQiIHZpZXdCb3g9IjAgLTI0IDI0IDI0Ij48cGF0aCBmaWxsPSJub25lIiBkPSJNMjQtMjRIMFYwaDI0eiIvPjxwYXRoIGQ9Ik0xMi04YTIgMiAwIDEgMS0uMDAxIDQuMDAxQTIgMiAwIDAgMSAxMi04em0wLTJhMiAyIDAgMSAxIC4wMDEtNC4wMDFBMiAyIDAgMCAxIDEyLTEwem0wLTZhMiAyIDAgMSAxIC4wMDEtNC4wMDFBMiAyIDAgMCAxIDEyLTE2eiIvPjwvc3ltYm9sPjx1c2UgeGxpbms6aHJlZj0iI2QiIHRyYW5zZm9ybT0ic2NhbGUoMSAtMSkiIGhlaWdodD0iMjQiIHdpZHRoPSIyNCIgeT0iLTI0IiBvdmVyZmxvdz0idmlzaWJsZSIvPjwvZz48cGF0aCBmaWxsPSJub25lIiBkPSJNNDkgMTM3SDI1di0yNGgyNHoiLz48cGF0aCBkPSJNMzcgMTIxYTIgMiAwIDEgMC0uMDAxLTQuMDAxQTIgMiAwIDAgMCAzNyAxMjF6bTAgMmEyIDIgMCAxIDAgLjAwMSA0LjAwMUEyIDIgMCAwIDAgMzcgMTIzem0wIDZhMiAyIDAgMSAwIC4wMDEgNC4wMDFBMiAyIDAgMCAwIDM3IDEyOXoiIGZpbGw9IiNmZmYiLz48cGF0aCBkPSJNODcgNEg3MWMtMS4xMDQgMC0xLjk5Ljg5Ni0xLjk5IDJMNjkgMThhMiAyIDAgMCAwIDIgMmgxNmEyIDIgMCAwIDAgMi0yVjZhMiAyIDAgMCAwLTItMnptMCA0bC04IDUtOC01VjZsOCA1IDgtNXYyeiIvPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik05MS0yNEg2N1YwaDI0eiIvPjxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDc1IDkwNikiPjxzeW1ib2wgaWQ9ImUiIHZpZXdCb3g9Ii0xMiAtMTIgMjQgMjQiPjxwYXRoIGQ9Ik04IDhILThhMS45OTIgMS45OTIgMCAwIDEtMS45OS0yTC0xMC02YTIgMiAwIDAgMSAyLTJIOGEyIDIgMCAwIDEgMiAyVjZhMiAyIDAgMCAxLTIgMnptMC00TDAtMWwtOCA1djJsOC01IDggNVY0eiIgZmlsbD0iI2ZmZiIvPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0xMi0xMmgtMjR2MjRoMjR6Ii8+PC9zeW1ib2w+PHVzZSB4bGluazpocmVmPSIjZSIgdHJhbnNmb3JtPSJtYXRyaXgoMSAwIDAgLTEgMTIgMTIpIiBoZWlnaHQ9IjI0IiB3aWR0aD0iMjQiIHk9Ii0xMiIgeD0iLTEyIiBvdmVyZmxvdz0idmlzaWJsZSIvPjwvZz48cGF0aCBkPSJNMjUgNjE0aDE4djE4SDI1eiIgZmlsbD0ibm9uZSIvPjxwYXRoIGQ9Ik0zNCA2MTUuMDNjLTQuNDIgMC04IDMuNTgtOCA4czMuNTggOCA4IDggOC0zLjU4IDgtOC0zLjU4LTgtOC04ek0zNSA2MjdoLTJ2LTJoMnYyem0wLTNoLTJ2LTVoMnY1eiIgZmlsbD0iI2ZmZiIvPjxwYXRoIGQ9Ik01OSA5ODQuNzVhMS4yNSAxLjI1IDAgMSAwIDAgMi41IDEuMjUgMS4yNSAwIDAgMCAwLTIuNXptNiAwYTEuMjUgMS4yNSAwIDEgMCAwIDIuNSAxLjI1IDEuMjUgMCAwIDAgMC0yLjV6TTYyIDk3NWMtNS41MiAwLTEwIDQuNDgtMTAgMTBzNC40OCAxMCAxMCAxMCAxMC00LjQ4IDEwLTEwLTQuNDgtMTAtMTAtMTB6bTAgMThjLTQuNDEgMC04LTMuNTktOC04IDAtLjI5LjAyLS41OC4wNS0uODYgMi4zNi0xLjA1IDQuMjMtMi45OCA1LjIxLTUuMzdhOS45NzQgOS45NzQgMCAwIDAgMTAuNDEgMy45N2MuMjEuNzEuMzMgMS40Ny4zMyAyLjI2IDAgNC40MS0zLjU5IDgtOCA4eiIvPjxwYXRoIGQ9Ik01MCA5NzNoMjR2MjRINTB6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTE2IDQwYTEgMSAwIDAgMS0xIDFIMWExIDEgMCAwIDEtMS0xVjI2YTEgMSAwIDAgMSAxLTFoMTRhMSAxIDAgMCAxIDEgMXYxNHoiIGZpbGw9IiM0Mjg1RjQiLz48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMyAzMWgxMHYxSDN6TTMgMjloMTB2MUgzek0zIDMzaDEwdjFIM3pNMyAzNWg2djFIM3oiLz48cGF0aCBmaWxsPSJub25lIiBkPSJNMCAyNWgxNnYxNkgweiIvPjxzd2l0Y2ggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMjUpIj48Zz48cGF0aCBkPSJNMTYgMTVhMSAxIDAgMCAxLTEgMUgxYTEgMSAwIDAgMS0xLTFWMWExIDEgMCAwIDEgMS0xaDE0YTEgMSAwIDAgMSAxIDF2MTR6IiBmaWxsPSIjREI0NDM3Ii8+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTggOGg1djVIOHoiLz48ZyBmaWxsPSIjZmZmIj48cGF0aCBkPSJNOCA4di45MjlBMy4yNCAzLjI0IDAgMCAwIDguOTMgOEg4eiIvPjxwYXRoIGQ9Ik03IDhWN2gyLjM1OWMuMDYxLS4yNDguMTAzLS41MDIuMTAzLS43NjlhMy4yMzIgMy4yMzIgMCAwIDAtNi40NjIgMCAzLjIzIDMuMjMgMCAwIDAgMy4yMyAzLjIzYy4yNjcgMCAuNTIxLS4wNDEuNzctLjEwM1Y4eiIvPjwvZz48cGF0aCBmaWxsPSJub25lIiBkPSJNMCAwaDE2djE2SDB6Ii8+PC9nPjwvc3dpdGNoPjxzd2l0Y2ggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoNTAgOTU2KSI+PGc+PHBhdGggZD0iTTE2IDE1YTEgMSAwIDAgMS0xIDFIMWExIDEgMCAwIDEtMS0xVjFhMSAxIDAgMCAxIDEtMWgxNGExIDEgMCAwIDEgMSAxdjE0eiIgZmlsbD0iIzBGOUQ1OCIvPjxwYXRoIGQ9Ik0xMiAzSDN2MTBoMTBWM2gtMXpNNCA0aDJ2Mkg0VjR6bTAgM2gydjJINFY3em0wIDV2LTJoMnYySDR6bTggMEg3di0yaDV2MnptMC0zSDdWN2g1djJ6bTAtM0g3VjRoNXYyeiIgZmlsbD0iI2ZmZiIvPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0wIDBoMTZ2MTZIMHoiLz48L2c+PC9zd2l0Y2g+PHN3aXRjaCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwIDEwMjcpIj48Zz48cGF0aCBkPSJNMTYgMTNhMyAzIDAgMCAxLTMgM0gzYTMgMyAwIDAgMS0zLTNWM2EzIDMgMCAwIDEgMy0zaDEwYTMgMyAwIDAgMSAzIDN2MTB6IiBmaWxsPSIjRjRCNDAwIi8+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTMgNGgxMHY3SDN6Ii8+PHBhdGggZmlsbD0ibm9uZSIgZD0iTTAgMGgxNnYxNkgweiIvPjwvZz48L3N3aXRjaD48cGF0aCBkPSJNNzcuNSAxMDM1LjN2LS42YzAtLjUuNy0xLjcgMS4yLTEuN2gzLjZjLS4zLS43LTEuMS0xLTEuOC0xSDc5Yy0xLjQgMC0yLjUgMS43LTIuNSAzczEuMiAzIDIuNSAzaDEuNGMuNyAwIDEuNS0uMyAxLjgtMWgtMy41Yy0uNSAwLTEuMi0xLjItMS4yLTEuN3pNODcuMyAxMDM3aC0zLjZjLjMuNyAxLjEgMSAxLjggMUg4N2MxLjQgMCAyLjUtMS43IDIuNS0zcy0xLjItMy0yLjUtM2gtMS40Yy0uNyAwLTEuNS4zLTEuOCAxaDMuNmMuNCAwIDEuMiAxLjIgMS4yIDEuOHYuNmMwIC41LS44IDEuNi0xLjMgMS42eiIvPjxwYXRoIGQ9Ik04MCAxMDM1YzAgLjMuMi41LjYuNWg0LjhjLjMgMCAuNi0uMi42LS41cy0uMi0uNS0uNi0uNWgtNC44Yy0uNCAwLS42LjItLjYuNXoiLz48ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg3NSAxMTY1KSI+PHN5bWJvbCBpZD0iZiIgdmlld0JveD0iMCAtMjQgMjQgMjQiPjxwYXRoIGQ9Ik0yMC4wMDItNC40QzE5LjQtNC4yMDMgMTUuNzAxLTQgMTItNGMtMy42OTkgMC03LjM5OC0uMTg4LTgtLjM4NEMyLjQzNi00LjkgMi04LjQwNCAyLTEycy40MzYtNy4xIDItNy42MTZjLjYwMi0uMTk3IDQuMzAxLS4zODQgOC0uMzg0IDMuNzAxIDAgNy40LjE4NyA4LjAwMi4zODQgMS41NjIuNTE2IDEuOTg4IDQuMDIgMS45ODggNy42MTZzLS40MjYgNy4wODQtMS45ODggNy42ek0xMC0xNnY4bDUuNS00LTUuNS00eiIgZmlsbD0iIzMzMyIvPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0wIDBoMjR2LTI0SDB6Ii8+PC9zeW1ib2w+PHVzZSB4bGluazpocmVmPSIjZiIgdHJhbnNmb3JtPSJtYXRyaXgoLjgzMzMzIDAgMCAtLjgzMzMzIDAgLTMuMzMzKSIgaGVpZ2h0PSIyNCIgd2lkdGg9IjI0IiB5PSItMjQiIG92ZXJmbG93PSJ2aXNpYmxlIi8+PC9nPjxwYXRoIGQ9Ik04NSAxMDIwaDR2LTJoLTR2MnptLTctMTJ2MmgxOHYtMkg3OHptMyA3aDEydi0ySDgxdjJ6IiBmaWxsPSIjZmZmIi8+PHBhdGggZD0iTTc1IDEwMDJoMjR2MjRINzV6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTM1IDEwNDhoLTZjLTEuMTA0IDAtMS45OS44OTYtMS45OSAybC0uMDEgMTJhMiAyIDAgMCAwIDIgMmgxNmEyIDIgMCAwIDAgMi0ydi0xMGEyIDIgMCAwIDAtMi0yaC04bC0yLTJ6IiBmaWxsPSIjMDEwMTAxIi8+PHBhdGggZD0iTTYwIDc4MHYtNmg0djZoNXYtOGgzbC0xMC05LTEwIDloM3Y4ek0zLjkgMTJjMC0xLjcxIDEuMzktMy4xIDMuMS0zLjFoNFY3SDdjLTIuNzYgMC01IDIuMjQtNSA1czIuMjQgNSA1IDVoNHYtMS45SDdjLTEuNzEgMC0zLjEtMS4zOS0zLjEtMy4xek04IDEzaDh2LTJIOHYyem05LTZoLTR2MS45aDRjMS43MSAwIDMuMSAxLjM5IDMuMSAzLjFzLTEuMzkgMy4xLTMuMSAzLjFoLTRWMTdoNGMyLjc2IDAgNS0yLjI0IDUtNXMtMi4yNC01LTUtNXpNMTQgNzQybC01IDUgNSA1di0xMHoiLz48cGF0aCBkPSJNMCA3MzVoMjR2MjRIMHYtMjR6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTYwIDEwNjFsNS01LTUtNXYxMHoiLz48cGF0aCBkPSJNNTAgMTA0NGgyNHYyNEg1MHYtMjR6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTcxIDY1Ny41aDIwdi0zSDcxdjN6bTAtNWgyMHYtM0g3MXYzem0wLTh2M2gyMHYtM0g3MXoiIGZpbGw9IiMyMzFGMjAiLz48ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgyNSAxMTU5KSI+PHRpdGxlPlNsaWNlIDE8L3RpdGxlPjxnIHNrZXRjaDp0eXBlPSJNU1NoYXBlR3JvdXAiIHhtbG5zOnNrZXRjaD0iaHR0cDovL3d3dy5ib2hlbWlhbmNvZGluZy5jb20vc2tldGNoL25zIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGZpbGw9Im5vbmUiPjxwYXRoIGQ9Ik0tNjg0LTIxNjRINzE2djM2MDBILTY4NHoiLz48cGF0aCBkPSJNMCAwaDI0djI0SDB6Ii8+PHBhdGggZD0iTTMgMThoMTh2LTJIM3Yyem0wLTVoMTh2LTJIM3Yyem0wLTd2MmgxOFY2SDN6IiBmaWxsPSIjZmZmIi8+PC9nPjwvZz48cGF0aCBkPSJNNzUgOTMxaDI0djI0SDc1eiIgZmlsbD0ibm9uZSIvPjxwYXRoIGQ9Ik05NCA5NTBIODB2LTE0aDd2LTJoLTdhMiAyIDAgMCAwLTIgMnYxNGEyIDIgMCAwIDAgMiAyaDE0YzEuMSAwIDItLjkgMi0ydi03aC0ydjd6bS01LTE2djJoMy41OWwtOS44MyA5LjgzIDEuNDEgMS40MSA5LjgzLTkuODNWOTQxaDJ2LTdoLTd6Ii8+PHBhdGggZD0iTTEwNC45OCA1MjYuMjk3Yy0uMDE3IDAtLjAxNy01NC4yOTctLjAxNy01NC4yOTdILjAwM3Y3MGg4OS40NDFzMTYuMTM5LTE1LjcwMyAxNS41MzktMTUuNzAzeiIgZmlsbD0iI0U1RTVFNSIgb3BhY2l0eT0iLjUiLz48cGF0aCBmaWxsPSIjM0U4NkZGIiBkPSJNODkuMDQyIDUyNi4wMThWNTQyTDEwNSA1MjYuMDE4eiIvPjxwYXRoIGZpbGw9IiNiYmIiIGQ9Ik03My4wODQgNTQyaDE1Ljk1OHYtMTUuOTgyeiIgb3BhY2l0eT0iLjcwMiIvPjxnPjxwYXRoIGQ9Ik0xMDQuOTggMzU5LjI5N2MtLjAxNyAwLS4wMTctNTQuMjk3LS4wMTctNTQuMjk3SC4wMDN2NzBoODkuNDQxczE2LjEzOS0xNS43MDMgMTUuNTM5LTE1LjcwM3oiIGZpbGw9IiNFNUU1RTUiIG9wYWNpdHk9Ii41Ii8+PHBhdGggZmlsbD0iI0RCNDQzNyIgZD0iTTg5LjA0MiAzNTkuMDE4VjM3NUwxMDUgMzU5LjAxOHoiLz48cGF0aCBmaWxsPSIjYmJiIiBkPSJNNzMuMDg0IDM3NWgxNS45NTh2LTE1Ljk4MnoiIG9wYWNpdHk9Ii43MDIiLz48L2c+PGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCAxMzgpIj48dGl0bGU+b3ZlcmxheV9mb3Jtc3NwcmVhZHNoZWV0czwvdGl0bGU+PGcgc2tldGNoOnR5cGU9Ik1TTGF5ZXJHcm91cCIgeG1sbnM6c2tldGNoPSJodHRwOi8vd3d3LmJvaGVtaWFuY29kaW5nLmNvbS9za2V0Y2gvbnMiIGZpbGwtcnVsZT0iZXZlbm9kZCIgZmlsbD0ibm9uZSI+PHBhdGggZD0iTTEwNC45OCA1NC4yOTdjLS4wMSAwLS4wMS01NC4yOTctLjAxLTU0LjI5N0gwdjcwaDg5LjQ0MXMxNi4xMzktMTUuNzAzIDE1LjUzOS0xNS43MDN6IiBvcGFjaXR5PSIuNSIgc2tldGNoOnR5cGU9Ik1TU2hhcGVHcm91cCIgZmlsbD0iI0U1RTVFNSIvPjxwYXRoIGQ9Ik04OS4wNDIgNTQuMDE4VjcwTDEwNSA1NC4wMThIODkuMDQyeiIgc2tldGNoOnR5cGU9Ik1TU2hhcGVHcm91cCIgZmlsbD0iIzY3M0FCNyIvPjxwYXRoIGQ9Ik03My4wODQgNzBoMTUuOTU4VjU0LjAxOEw3My4wODQgNzB6IiBza2V0Y2g6dHlwZT0iTVNTaGFwZUdyb3VwIiBmaWxsPSIjYmJiIi8+PC9nPjwvZz48Zz48cGF0aCBkPSJNMTA0Ljk4IDI4OC4yOTdjLS4wMTcgMC0uMDE3LTU0LjI5Ny0uMDE3LTU0LjI5N0guMDAzdjcwaDg5LjQ0MXMxNi4xMzktMTUuNzAzIDE1LjUzOS0xNS43MDN6IiBmaWxsPSIjRTVFNUU1IiBvcGFjaXR5PSIuNSIvPjxwYXRoIGZpbGw9IiNGNEI0MDAiIGQ9Ik04OS4wNDIgMjg4LjAxOFYzMDRMMTA1IDI4OC4wMTh6Ii8+PHBhdGggZmlsbD0iI2JiYiIgZD0iTTczLjA4NCAzMDRoMTUuOTU4di0xNS45ODJ6IiBvcGFjaXR5PSIuNzAyIi8+PC9nPjxnPjxwYXRoIGQ9Ik0xMDQuOTggNTk3LjI5N2MtLjAxNyAwLS4wMTctNTQuMjk3LS4wMTctNTQuMjk3SC4wMDN2NzBoODkuNDQxczE2LjEzOS0xNS43MDMgMTUuNTM5LTE1LjcwM3oiIGZpbGw9IiNFNUU1RTUiIG9wYWNpdHk9Ii41Ii8+PHBhdGggZmlsbD0iIzNGNTFCNSIgZD0iTTg5LjA0MiA1OTcuMDE4VjYxM0wxMDUgNTk3LjAxOHoiLz48cGF0aCBmaWxsPSIjYmJiIiBkPSJNNzMuMDg0IDYxM2gxNS45NTh2LTE1Ljk4MnoiIG9wYWNpdHk9Ii43MDIiLz48L2c+PGc+PHBhdGggZD0iTTEwNC45OCAxMTIzLjI5N2MtLjAxNyAwLS4wMTctNTQuMjk3LS4wMTctNTQuMjk3SC4wMDN2NzBoODkuNDQxczE2LjEzOS0xNS43MDMgMTUuNTM5LTE1LjcwM3oiIGZpbGw9IiNFNUU1RTUiIG9wYWNpdHk9Ii41Ii8+PHBhdGggZmlsbD0iIzBGOUQ1OCIgZD0iTTg5LjA0MiAxMTIzLjAxOFYxMTM5TDEwNSAxMTIzLjAxOHoiLz48cGF0aCBmaWxsPSIjYmJiIiBkPSJNNzMuMDg0IDExMzloMTUuOTU4di0xNS45ODJ6IiBvcGFjaXR5PSIuNzAyIi8+PC9nPjxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAgNzg1KSI+PHBhdGggZD0iTTEwNC45NyAwSDB2NzBoMTA1IiBvcGFjaXR5PSIuMiIvPjxjaXJjbGUgb3BhY2l0eT0iLjUiIHI9IjE3LjkxMyIgY3g9IjUyLjUiIGN5PSIzNSIvPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik00OC4wMjEgMjcuNzk2djE0LjQwOGwxMS4yOTEtNy4wMTF6Ii8+PC9nPjxnPjxwYXRoIGQ9Ik0wIDk3N2gyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjxwYXRoIGQ9Ik0xNiA5ODhjMS42NiAwIDIuOTktMS4zNCAyLjk5LTNzLTEuMzMtMy0yLjk5LTNjLTEuNjYgMC0zIDEuMzQtMyAzczEuMzQgMyAzIDN6bS04IDBjMS42NiAwIDIuOTktMS4zNCAyLjk5LTNzLTEuMzMtMy0yLjk5LTNjLTEuNjYgMC0zIDEuMzQtMyAzczEuMzQgMyAzIDN6bTAgMmMtMi4zMyAwLTcgMS4xNy03IDMuNXYyLjVoMTR2LTIuNWMwLTIuMzMtNC42Ny0zLjUtNy0zLjV6bTggMGMtLjI5IDAtLjYyLjAyLS45Ny4wNSAxLjE2Ljg0IDEuOTcgMS45NyAxLjk3IDMuNDV2Mi41aDZ2LTIuNWMwLTIuMzMtNC42Ny0zLjUtNy0zLjV6IiBmaWxsPSIjZmZmIi8+PC9nPjxnPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0tNTkzLTIxMzdIODA3djM2MDBILTU5M3oiLz48cGF0aCBkPSJNNDUgNzM3SDI5Yy0xLjEgMC0yIC45LTIgMnYxOGw0LTRoMTRjMS4xIDAgMi0uOSAyLTJ2LTEyYzAtMS4xLS45LTItMi0yeiIvPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0yNSA3MzVoMjR2MjRIMjV6Ii8+PC9nPjxnPjxwYXRoIGQ9Ik03MCAxMTVINTRhMiAyIDAgMCAwLTIgMnYxOGw0LTRoMTRhMiAyIDAgMCAwIDItMnYtMTJhMiAyIDAgMCAwLTItMnoiIGZpbGw9IiNmZmYiLz48cGF0aCBkPSJNNjIgMTI1aDI0djI0SDYydi0yNHoiIGZpbGw9Im5vbmUiLz48L2c+PGc+PHBhdGggZD0iTTEwIDk1NmMtNS41MjIgMC0xMCA0LjQ3Ny0xMCAxMCAwIDUuNTIyIDQuNDc3IDEwIDEwIDEwczEwLTQuNDc4IDEwLTEwYzAtNS41MjQtNC40NzctMTAtMTAtMTB6bTEuMTIzIDE2LjQwNWgtMi4zNXYtMi4xODloMi4zNXYyLjE4OXptMi43Ni04LjIxMWEyLjc0MiAyLjc0MiAwIDAgMS0uMzUxLjc3MSAzLjA5NCAzLjA5NCAwIDAgMS0uNS41NzhjLS4xODguMTctLjM3NS4zMzYtLjU2MS41LS4yMjQuMTg4LS40MjkuMzY3LS42MTMuNTQzYTMuMDczIDMuMDczIDAgMCAwLS40OTIuNTg3IDIuNjI1IDIuNjI1IDAgMCAwLS4zMjMuNzYyIDQuMzE2IDQuMzE2IDAgMCAwLS4xMTMgMS4wNjhIOS4wMzdjMC0uNTE1LjAyNC0uOTQ3LjA3Ny0xLjMwNi4wNTQtLjM1NC4xNC0uNjY4LjI1NC0uOTM4LjExNy0uMjcuMjYxLS41MDUuNDMxLS43MS4xNy0uMjAzLjM3MS0uNDA1LjYwNC0uNjA0YTIyLjYgMjIuNiAwIDAgMSAuNTM1LS40NTVjLjE2OC0uMTQyLjMxOS0uMjk1LjQ1NS0uNDY1LjEzNS0uMTcuMjM3LS4zNTkuMzEzLS41NjkuMDc2LS4yMTEuMTE1LS40NjEuMTE1LS43NTQgMC0uMzUxLS4wNjItLjY1LS4xODYtLjkwMmExLjg1OSAxLjg1OSAwIDAgMC0uNDQ1LS42MDUgMS43NzcgMS43NzcgMCAwIDAtLjU2Mi0uMzMyIDEuNTkzIDEuNTkzIDAgMCAwLS41MjQtLjEwNWMtLjcyNiAwLTEuMjU4LjIzNi0xLjYwNC43MS0uMzQ0LjQ3NS0uNTE4IDEuMTA3LS41MTggMS45MDJINS45ODZjMC0uNjQzLjA5OC0xLjIyNy4yOTEtMS43NTIuMTkxLS41MjYuNDczLS45NzcuODQtMS4zNS4zNjktLjM3NS44MTItLjY2NCAxLjMzMi0uODY4czEuMTAyLS4zMDcgMS43NDQtLjMwN2MuNTM3IDAgMS4wMzcuMDc5IDEuNDk4LjIzNy40NjMuMTU3Ljg2NS4zODUgMS4yMTEuNjgzLjM0NC4yOTguNjE1LjY2OS44MTQgMS4xMTNzLjI5Ny45NDYuMjk3IDEuNTA3Yy4wMDEuNDEyLS4wNDIuNzY0LS4xMyAxLjA2MXoiLz48L2c+PGc+PHBhdGggZD0iTTMzLjI1IDY0Ni41aDEuNVY2NDVoLTEuNXYxLjV6bS43NS0xMmMtNC4xNCAwLTcuNSAzLjM2LTcuNSA3LjVzMy4zNiA3LjUgNy41IDcuNSA3LjUtMy4zNiA3LjUtNy41LTMuMzYtNy41LTcuNS03LjV6bTAgMTMuNWMtMy4zMDggMC02LTIuNjkyLTYtNnMyLjY5Mi02IDYtNiA2IDIuNjkyIDYgNi0yLjY5MiA2LTYgNnptMC0xMC41YTMgMyAwIDAgMC0zIDNoMS41YzAtLjgyNS42NzUtMS41IDEuNS0xLjVzMS41LjY3NSAxLjUgMS41YzAgMS41LTIuMjUgMS4zMTMtMi4yNSAzLjc1aDEuNWMwLTEuNjg4IDIuMjUtMS44NzUgMi4yNS0zLjc1YTMgMyAwIDAgMC0zLTN6Ii8+PC9nPjxnPjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0tNTc0LTIxMzBIODI2djM2MDBILTU3NHoiLz48cGF0aCBmaWxsPSJub25lIiBkPSJNNDQgNjE0aDI0djI0SDQ0eiIvPjxwYXRoIGQ9Ik01NiA2MTZjLTUuNSAwLTEwIDQuNS0xMCAxMHM0LjUgMTAgMTAgMTAgMTAtNC41IDEwLTEwLTQuNS0xMC0xMC0xMHptMSAxN2gtMnYtMmgydjJ6bTIuMS03LjdsLS45LjljLS44LjctMS4yIDEuMy0xLjIgMi44aC0ydi0uNWMwLTEuMS40LTIuMSAxLjItMi44bDEuMi0xLjNjLjQtLjMuNi0uOC42LTEuNCAwLTEuMS0uOS0yLTItMnMtMiAuOS0yIDJoLTJjMC0yLjIgMS44LTQgNC00czQgMS44IDQgNGMwIC45LS40IDEuNy0uOSAyLjN6Ii8+PC9nPjxnPjxwYXRoIGQ9Ik01MCAxMTkwaDI0djI0SDUweiIgZmlsbD0ibm9uZSIvPjxwYXRoIGQ9Ik02OSAxMTkySDU1YTIgMiAwIDAgMC0yIDJ2MTRhMiAyIDAgMCAwIDIgMmg0bDMgMyAzLTNoNGEyIDIgMCAwIDAgMi0ydi0xNGEyIDIgMCAwIDAtMi0yem0tNiAxNmgtMnYtMmgydjJ6bTIuMDY1LTcuNzQ1bC0uODk1LjkyYy0uNzIuNzItMS4xNyAxLjMyNS0xLjE3IDIuODI1aC0ydi0uNWMwLTEuMTA1LjQ1LTIuMTA1IDEuMTctMi44M2wxLjI0NS0xLjI2QTIgMiAwIDEgMCA2MCAxMTk4aC0yYzAtMi4yMSAxLjc5LTQgNC00czQgMS43OSA0IDRjMCAuODgtLjM1NSAxLjY3NS0uOTM1IDIuMjU1eiIvPjwvZz48Zz48cGF0aCBkPSJNNzUgMTE5MGgyNHYyNEg3NXoiIGZpbGw9Im5vbmUiLz48cGF0aCBkPSJNOTQgMTE5Mkg4MGEyIDIgMCAwIDAtMiAydjE0YTIgMiAwIDAgMCAyIDJoNGwzIDMgMy0zaDRhMiAyIDAgMCAwIDItMnYtMTRhMiAyIDAgMCAwLTItMnptLTYgMTZoLTJ2LTJoMnYyem0yLjA2NS03Ljc0NWwtLjg5NS45MmMtLjcyLjcyLTEuMTcgMS4zMjUtMS4xNyAyLjgyNWgtMnYtLjVjMC0xLjEwNS40NS0yLjEwNSAxLjE3LTIuODNsMS4yNDUtMS4yNkEyIDIgMCAxIDAgODUgMTE5OGgtMmMwLTIuMjEgMS43OS00IDQtNHM0IDEuNzkgNCA0YzAgLjg4LS4zNTUgMS42NzUtLjkzNSAyLjI1NXoiIGZpbGw9IiNmZmYiLz48L2c+PGc+PHBhdGggZmlsbD0ibm9uZSIgZD0iTS01NjggNTYySDgzMnYzNjAwSC01Njh6Ii8+PHBhdGggZD0iTTYwIDEwMTF2LTRsLTcgNyA3IDd2LTQuMWM1IDAgOC41IDEuNiAxMSA1LjEtMS01LTQtMTAtMTEtMTF6Ii8+PHBhdGggZmlsbD0ibm9uZSIgZD0iTTUwIDEwMDJoMjR2MjRINTB6Ii8+PC9nPjxnPjxwYXRoIGQ9Ik0yNSAxMTkwaDI0djI0SDI1eiIgZmlsbD0ibm9uZSIvPjxwYXRoIGQ9Ik0zMiAxMTk3aDEwdjNsNC00LTQtNHYzSDMwdjZoMnYtNHptMTAgMTBIMzJ2LTNsLTQgNCA0IDR2LTNoMTJ2LTZoLTJ2NHoiIGZpbGw9IiNmZmYiLz48L2c+PGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoNzUgMTE0MCkiPjxzeW1ib2wgaWQ9ImciIHZpZXdCb3g9IjAgLTI0IDI0IDI0Ij48cGF0aCBkPSJNMTkuNDI5LTEyLjk3NmMuMDQyLjMyLjA3LjY0NC4wNy45NzZzLS4wMjkuNjU1LS4wNy45NzZsMi4xMTMgMS42NTRhLjUuNSAwIDAgMSAuMTE4LjYzOGwtMiAzLjQ2NGEuNS41IDAgMCAxLS42MTIuMjE3bC0yLjQ5LTEuMDAzYTcuNDczIDcuNDczIDAgMCAxLTEuNjkuOTgzbC0uMzc1IDIuNjQ5QS40OTkuNDk5IDAgMCAxIDE0LTJoLTRhLjUuNSAwIDAgMS0uNDk0LS40MjFMOS4xMzEtNS4wN2E3LjUyIDcuNTIgMCAwIDEtMS42OTEtLjk4NEw0Ljk1Mi01LjA1MWEuNS41IDAgMCAxLS42MTItLjIxN2wtMi0zLjQ2NGEuNS41IDAgMCAxIC4xMTgtLjYzOGwyLjExMi0xLjY1NGMtLjA0Mi0uMzItLjA3LS42NDQtLjA3LS45NzZzLjAyOS0uNjU2LjA3MS0uOTc2bC0yLjExMi0xLjY1M2EuNS41IDAgMCAxLS4xMTgtLjYzOWwyLTMuNDY0YS41LjUgMCAwIDEgLjYxMi0uMjE3bDIuNDg5IDEuMDAzYTcuNDczIDcuNDczIDAgMCAxIDEuNjktLjk4M2wuMzc1LTIuNjQ5QS40OTkuNDk5IDAgMCAxIDEwLTIyaDRhLjUuNSAwIDAgMSAuNDk0LjQyMWwuMzc1IDIuNjQ5YTcuNDQ4IDcuNDQ4IDAgMCAxIDEuNjg5Ljk4NGwyLjQ5LTEuMDA0YS41MDEuNTAxIDAgMCAxIC42MTIuMjE3bDIgMy40NjRhLjUuNSAwIDAgMS0uMTE4LjYzOWwtMi4xMTMgMS42NTR6TTEyLTE2YTQgNCAwIDEgMCAwIDggNCA0IDAgMCAwIDAtOHoiLz48cGF0aCBmaWxsPSJub25lIiBkPSJNMjQtMjRIMFYwaDI0eiIvPjwvc3ltYm9sPjx1c2UgeGxpbms6aHJlZj0iI2ciIHRyYW5zZm9ybT0ic2NhbGUoMSAtMSkiIGhlaWdodD0iMjQiIHdpZHRoPSIyNCIgeT0iLTI0IiBvdmVyZmxvdz0idmlzaWJsZSIvPjwvZz48Zz48cGF0aCBkPSJNMjUgMTAwMmgyNHYyNEgyNXoiIGZpbGw9Im5vbmUiLz48cGF0aCBkPSJNNDQuNDMgMTAxNC45OGMuMDQtLjMyLjA3LS42NC4wNy0uOThzLS4wMy0uNjYtLjA3LS45OGwyLjExLTEuNjVjLjE5LS4xNS4yNC0uNDIuMTItLjY0bC0yLTMuNDZjLS4xMi0uMjItLjM5LS4zLS42MS0uMjJsLTIuNDkgMWMtLjUyLS40LTEuMDgtLjczLTEuNjktLjk4bC0uMzgtMi42NWEuNDg4LjQ4OCAwIDAgMC0uNDktLjQyaC00Yy0uMjUgMC0uNDYuMTgtLjQ5LjQybC0uMzggMi42NWMtLjYxLjI1LTEuMTcuNTktMS42OS45OGwtMi40OS0xYy0uMjMtLjA5LS40OSAwLS42MS4yMmwtMiAzLjQ2Yy0uMTMuMjItLjA3LjQ5LjEyLjY0bDIuMTEgMS42NWMtLjA0LjMyLS4wNy42NS0uMDcuOThzLjAzLjY2LjA3Ljk4bC0yLjExIDEuNjVjLS4xOS4xNS0uMjQuNDItLjEyLjY0bDIgMy40NmMuMTIuMjIuMzkuMy42MS4yMmwyLjQ5LTFjLjUyLjQgMS4wOC43MyAxLjY5Ljk4bC4zOCAyLjY1Yy4wMy4yNC4yNC40Mi40OS40Mmg0Yy4yNSAwIC40Ni0uMTguNDktLjQybC4zOC0yLjY1Yy42MS0uMjUgMS4xNy0uNTkgMS42OS0uOThsMi40OSAxYy4yMy4wOS40OSAwIC42MS0uMjJsMi0zLjQ2Yy4xMi0uMjIuMDctLjQ5LS4xMi0uNjRsLTIuMTEtMS42NXpNMzcgMTAxNy41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiIGZpbGw9IiNmZmYiLz48L2c+PGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCA4NTYpIj48dXNlIHhsaW5rOmhyZWY9IiNoIiB0cmFuc2Zvcm09Im1hdHJpeCgxIDAgMCAtLjk1MjM4IDEyIDYuOTUyKSIgaGVpZ2h0PSItMzI3NjYiIHdpZHRoPSItMzI3NjYiIHk9IjE2MzgzIiB4PSIxNjM4MyIgb3ZlcmZsb3c9InZpc2libGUiIGZpbGw9IiNmZmYiLz48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMS4xIDQuNDc2TDAgNS41MjQgNC43IDEwIDE0IDEuMDQ4IDEyLjkgMCA0LjcgNy45MDV6Ii8+PC9nPjxnPjxwYXRoIGZpbGw9IiMyMzFmMjAiIGQ9Ik05Ny45OSA2MTlMOTQgNjIyLjk5bDEuMDEgMS4wMSAzLjk5LTMuOTkgMy45OSAzLjk5IDEuMDEtMS4wMS0zLjk5LTMuOTkgMy45OS0zLjk5LTEuMDEtMS4wMS0zLjk5IDMuOTktMy45OS0zLjk5LTEuMDEgMS4wMXoiLz48L2c+PGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCA2MTQpIj48Y2lyY2xlIGN5PSIxMiIgY3g9IjEyIiByPSIxMiIgZmlsbD0iIzBDOUQ1OCIvPjxwYXRoIGQ9Ik05Ljc1IDE1LjEyOEw2LjYyMiAxMmwtMS4wNjEgMS4wNjFMOS43NSAxNy4yNWw5LTktMS4wNjEtMS4wNjEtNy45MzkgNy45Mzl6IiBmaWxsPSIjZmZmIi8+PC9nPjxnPjxwYXRoIGQ9Ik0xMiA4NjdjLTYuNjI0IDAtMTIgNS4zNy0xMiAxMnM1LjM3NiAxMiAxMiAxMiAxMi01LjM3IDEyLTEyLTUuMzc2LTEyLTEyLTEyeiIgZmlsbD0iI0RCNDQzNiIvPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik0xMC44IDg4Mi42aDIuNHYyLjRoLTIuNHpNMTAuOCA4NzNoMi40djcuMmgtMi40eiIvPjwvZz48ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwIDYzOSkiPjxjaXJjbGUgY3k9IjEyIiBjeD0iMTIiIHI9IjEyIiBmaWxsPSIjMEM5RDU4Ii8+PHBhdGggZD0iTTMuNTE3IDExLjk5N0w3LjIzIDE1LjcxbDMuNzEyLTMuNzEySDcuNTIxYzAtMS4xNTEuNDIyLTIuMzA0IDEuMjk5LTMuMTgyIDEuNzU4LTEuNzU4IDQuNjA2LTEuNzU4IDYuMzY0IDBzMS43NTggNC42MDYgMCA2LjM2NGE0LjQ5MyA0LjQ5MyAwIDAgMS01LjExOC44NzVsLTEuMTAzIDEuMTAzYTUuOTg3IDUuOTg3IDAgMCAwIDcuMjgxLS45MTdjMi4zNDQtMi4zNDQgMi4zMzktNi4xMzYtLjAwNS04LjQ4cy02LjEzNi0yLjM0OS04LjQ4LS4wMDVhNS45NiA1Ljk2IDAgMCAwLTEuNzUgNC4yNDNIMy41MTd6IiBmaWxsPSIjZmZmIi8+PC9nPjxnPjxwYXRoIGZpbGwtb3BhY2l0eT0iLjA5IiBkPSJNMCA2NjQuMDAxaDEwNXY3MC4wMDFIMHoiLz48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMzguOTY0IDcxOC4xODNsOC4xNjYtMTQuMzA5aDI4LjMyNmwtNy44NTcgMTQuMzF6TTc1Ljk3MSA3MDEuNDcySDU5LjQ2NmwtMTUuMDEyLTIyLjI4N2gxNi41MjJ6TTM3LjE5NiA3MTcuOTZsLTguMTY2LTE1LjIgMTIuNTI0LTIzLjc2MyA5LjMxNyAxNC40Mjl6Ii8+PC9nPjxnPjxwYXRoIGZpbGwtb3BhY2l0eT0iLjA5IiBkPSJNMCA0MmgxMDV2NzBIMHoiLz48cGF0aCBkPSJNNTIuNSA1N2MtMTEgMC0yMCA5LTIwIDIwczkgMjAgMjAgMjAgMjAtOSAyMC0yMC05LTIwLTIwLTIwem0tMiAzNS45Yy03LjktMS0xNC03LjctMTQtMTUuOSAwLTEuMi4yLTIuNC40LTMuNmw5LjYgOS42djJjMCAyLjIgMS44IDQgNCA0djMuOXptMTMuOC01LjFjLS41LTEuNi0yLTIuOC0zLjgtMi44aC0ydi02YzAtMS4xLS45LTItMi0yaC0xMnYtNGg0YzEuMSAwIDItLjkgMi0ydi00aDRjMi4yIDAgNC0xLjggNC00di0uOGM1LjkgMi40IDEwIDguMSAxMCAxNC44IDAgNC4yLTEuNiA3LjktNC4yIDEwLjh6IiBmaWxsPSIjZmZmIi8+PC9nPjxnPjxwYXRoIGZpbGwtb3BhY2l0eT0iLjA5IiBkPSJNMCAzNzZoMTA1djcwSDB6Ii8+PHBhdGggZD0iTTY3IDM5Ny4yYy0xLjEtLjQtNy44LS43LTE0LjUtLjdzLTEzLjQuNC0xNC41LjdjLTIuOC45LTMuNiA3LjItMy42IDEzLjhzLjggMTIuOSAzLjYgMTMuOGMxLjEuNCA3LjguNyAxNC41LjdzMTMuNC0uNCAxNC41LS43YzIuOC0uOSAzLjYtNy4yIDMuNi0xMy44cy0uOC0xMi45LTMuNi0xMy44em0tMTguMSAyMnYtMTYuNGwxMC45IDguMi0xMC45IDguMnoiIGZpbGw9IiNmZmYiLz48L2c+PGc+PHBhdGggZD0iTTUwIDExNjVoMjR2MjRINTB6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTY5IDExNjhoLTF2LTJoLTJ2MmgtOHYtMmgtMnYyaC0xYy0xLjExIDAtMS45OS45LTEuOTkgMmwtLjAxIDE0YTIgMiAwIDAgMCAyIDJoMTRjMS4xIDAgMi0uOSAyLTJ2LTE0YzAtMS4xLS45LTItMi0yem0wIDE2SDU1di0xMWgxNHYxMXptLTEyLTloNXY1aC01eiIgZmlsbD0iI2ZmZiIvPjwvZz48Zz48cGF0aCBkPSJNNy40MSAxMTgzLjU5bDEuNDIgMS40MSAzLjE3LTMuMTcgMy4xNyAzLjE3IDEuNDEtMS40MUwxMiAxMTc5bC00LjU5IDQuNTl6bTkuMTgtMTMuMThsLTEuNDItMS40MS0zLjE3IDMuMTctMy4xNy0zLjE3LTEuNDIgMS40MUwxMiAxMTc1bDQuNTktNC41OXoiLz48L2c+PGc+PHBhdGggZD0iTTM3IDg2MS44M2wzLjE3IDMuMTcgMS40MS0xLjQxTDM3IDg1OWwtNC41OSA0LjU5IDEuNDIgMS40MSAzLjE3LTMuMTd6bTAgMTIuMzRMMzMuODMgODcxbC0xLjQxIDEuNDFMMzcgODc3bDQuNTktNC41OS0xLjQyLTEuNDEtMy4xNyAzLjE3eiIvPjwvZz48ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg3NSA3MzUpIj48c3ltYm9sIGlkPSJpIiB2aWV3Qm94PSIwIC0yNCAyNCAyNCI+PHBhdGggZD0iTTYtMTlhMiAyIDAgMCAxIDItMmg4YTIgMiAwIDAgMSAyIDJ2MTJINnYtMTJ6TTE4LTRoLTIuNWwtMSAxaC01bC0xLTFINmExIDEgMCAwIDEtMS0xdi0xaDE0djFhMSAxIDAgMCAxLTEgMXoiLz48cGF0aCBmaWxsPSJub25lIiBkPSJNMjQtMjRIMFYwaDI0eiIvPjwvc3ltYm9sPjx1c2UgeGxpbms6aHJlZj0iI2kiIHRyYW5zZm9ybT0ic2NhbGUoMSAtMSkiIGhlaWdodD0iMjQiIHdpZHRoPSIyNCIgeT0iLTI0IiBvdmVyZmxvdz0idmlzaWJsZSIvPjwvZz48Zz48cGF0aCBkPSJNODQuNjI1IDk4Ny45N2MwLTEuMDUtLjU4My0xLjkyNS0xLjQ1OC0yLjMzM3YxLjI4NWwxLjQ1OCAxLjQ1OHYtLjQxem0xLjQ1OCAwYzAgLjUyNS0uMTE2IDEuMDUtLjI5MSAxLjUxN2wuODc1Ljg3NmMuNDA4LS43LjU4My0xLjU3NS41ODMtMi40NWE1LjI1OSA1LjI1OSAwIDAgMC00LjA4My01LjEzM3YxLjIyNWMxLjY5MS41ODMgMi45MTYgMi4wOTkgMi45MTYgMy45NjZ6bS04LjU3NS01LjI1bC0uNzU4Ljc1OCAyLjc0MiAyLjc0M0g3Ni43NXYzLjVoMi4zMzNMODIgOTkyLjYzOHYtMy45MDlsMi41MDggMi41MDlhNC44NTkgNC44NTkgMCAwIDEtMS4zNDEuN3YxLjIyNWE0Ljk2OSA0Ljk2OSAwIDAgMCAyLjE1OC0xLjA1bDEuMTY3IDEuMTY3Ljc1OC0uNzU5LTUuMjUtNS4yNS00LjQ5Mi00LjU1em00LjQ5Mi41ODNsLTEuMjI1IDEuMjI1TDgyIDk4NS43NTR2LTIuNDV6IiBmaWxsPSIjZGE0MzM2Ii8+PHBhdGggZmlsbD0ibm9uZSIgZD0iTTc1IDk4MWgxNHYxNEg3NXoiLz48L2c+PGc+PHBhdGggZD0iTTI1IDExNDBoMTh2MThIMjV6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTM0IDExNDMuMzc1Yy0zLjc1IDAtNi45NTIgMi4zMzMtOC4yNSA1LjYyNSAxLjI5OCAzLjI5MiA0LjUgNS42MjUgOC4yNSA1LjYyNSAzLjc1NCAwIDYuOTUyLTIuMzMzIDguMjUtNS42MjUtMS4yOTgtMy4yOTItNC40OTYtNS42MjUtOC4yNS01LjYyNXptMCA5LjM3NWMtMi4wNyAwLTMuNzUtMS42OC0zLjc1LTMuNzVzMS42OC0zLjc1IDMuNzUtMy43NSAzLjc1IDEuNjggMy43NSAzLjc1LTEuNjggMy43NS0zLjc1IDMuNzV6bTAtNmEyLjI1MiAyLjI1MiAwIDAgMC0yLjI1IDIuMjUgMi4yNTIgMi4yNTIgMCAwIDAgMi4yNSAyLjI1IDIuMjUyIDIuMjUyIDAgMCAwIDIuMjUtMi4yNSAyLjI1MiAyLjI1MiAwIDAgMC0yLjI1LTIuMjV6Ii8+PC9nPjxnPjxwYXRoIGQ9Ik00NS4wMDcgMjI4LjZjLS42MDIuMTk3LTQuMzAxLjQtOC4wMDIuNC0zLjY5OSAwLTcuMzk4LS4xODgtOC0uMzg0LTEuNTY0LS41MTYtMi00LjAyLTItNy42MTZzLjQzNi03LjEgMi03LjYxNmMuNjAyLS4xOTcgNC4zMDEtLjM4NCA4LS4zODQgMy43MDEgMCA3LjQuMTg3IDguMDAyLjM4NCAxLjU2Mi41MTYgMS45ODggNC4wMiAxLjk4OCA3LjYxNnMtLjQyNiA3LjA4NC0xLjk4OCA3LjZ6TTM1LjAwNSAyMTd2OGw1LjUtNC01LjUtNHoiLz48cGF0aCBmaWxsPSJub25lIiBkPSJNNDkgMTg1SDI1djI0aDI0eiIvPjwvZz48L3N2Zz4=) !important;background-position: -66px -585px;height: 23px !important;width: 23px !important;background-repeat: no-repeat !important;background-size: 100px;flex-shrink: 0 !important;position: absolute;margin-left: -12px;margin-top: 12px;}

#friends .tab-bar .tab-bar-item.tab-bar-item-primary{background-color:transparent;color:hsla(0,0%,100%,.6) !important;}

#friends .tab-bar .tab-bar-item.tab-bar-item-primary:hover:not(.selected){background-color:#2f3136;}

#friends .tab-bar .tab-bar-item.tab-bar-item-primary.selected, .theme-light #friends .tab-bar .tab-bar-item.tab-bar-item-primary.selected{background-color:var(--main-color) !important;color:#fff!important;}

.theme-light #friends > .headerBar-cxbhPD{background-color:#fff !important;}

.theme-light #friends .tab-bar .tab-bar-item.tab-bar-item-primary{color:#99aab5 !important;}

.theme-light #friends .tab-bar .tab-bar-item.tab-bar-item-primary:hover:not(.selected){background-color:rgba(153,170,181,.2) !important;}

.theme-dark .headerBar-cxbhPD{background:#19191b;box-shadow:0 0px 0 transparent !important;border-bottom:2px solid var(--main-color);height:46px;}

.theme-light .headerBar-cxbhPD{box-shadow:0 0px 0 transparent !important;border-bottom:2px solid var(--main-color);height:46px;}

.theme-dark .activityFeed-HeiGwL{background-color:#19191b;}

.theme-dark .activityFeed-HeiGwL{background-color:#19191b;}

.theme-dark .activity-3tgXuD{background-color:#19191b;border-color:#19191b;color:#f6f6f7;box-shadow:0px 2px 7px 1px #131313;}

.theme-dark .body-2WmNzl{background-color:transparent;}

.theme-dark .nameTag-RG5DEB{color:#868686;}

.theme-dark .header-34ZDfM{background-color:#19191b;border-bottom:2px solid var(--main-color);}

.theme-dark .newsIconCircle-2mzNOD{background-color:#121213;}

.theme-dark .content-1RjmSK:hover{background-color:#121213;}

.theme-dark .content-1RjmSK{background-color:#121213;}

.theme-dark .partyBottomBorder-3UKgJE{background-color:transparent;}

.base-3AoPqv {border-radius: 5px 0 0 5px;}

[style="left: 42px; top: 29.5px;"]{display: none;}

.theme-light .feed-2fHzeU{background-color: #ffffff;}

.base-3AoPqv {border-radius:0px !important;}

.theme-dark #friends .tab-bar .tab-bar-item.tab-bar-item-primary {background-color: var(--hover-color)!important;}

/* Chat Text Area (input) */
.theme-dark .chat form{background-color:#19191b;box-shadow:0 0px 0 transparent;}

.theme-light .chat form{background-color:#fff;box-shadow:0 0px 0 transparent;}

.chat form{margin:0 0px -23px !important;}

.theme-dark .inner-3if5cm{background-color:transparent;border-left:2px solid #212121;border-right:2px solid #212121;border-top:2px solid #212121;border-radius:0px !important;margin-bottom:-18px;padding-top:14px;}

.theme-light .inner-3if5cm{background-color:transparent;border-left:2px solid #f6f6f7;border-right:2px solid #f6f6f7;border-top:2px solid #f6f6f7;border-radius:0px !important;margin-bottom:-18px;padding-top:14px;}

.emojiButton-38mF6t{top:26px;}

.typing{bottom:16px;}

.channelTextArea-os01xC{margin:20px 0 32px;bottom:21px;}

.theme-dark .upload-modal .inner-3if5cm{background-color: #212121;border: 0px solid transparent;margin-bottom: 0px;padding-top: 0px;border-radius: 3px !important;}

.theme-light .upload-modal .inner-3if5cm{background-color: #fff;border: 0px solid transparent;margin-bottom: 0px;padding-top: 0px;border-radius: 3px !important;}

.theme-dark .upload-modal .emojiButton-38mF6t{top: 11px !important;}

.theme-dark .edit-message .inner-3if5cm{border: 0px solid transparent;margin-bottom: 0px;padding-top: 0px;}

.theme-light .edit-message .inner-3if5cm{border: 0px solid transparent;margin-bottom: 0px;padding-top: 0px;}

.theme-dark .edit-message .emojiButton-38mF6t{top: 11px !important;}

.theme-light .edit-message .emojiButton-38mF6t{top: 11px !important;}
/* End Chat Text Area (input)*/
.scrollbarGhostHairline-D_btXm::-webkit-scrollbar-thumb{background-color:var(--main-color);}

.theme-dark .description-3MVziF, .theme-dark .labelDescriptor-1BebCl{color: #9e9e9e;}

.theme-dark .header-1-f9X5{color: var(--main-color);font-size: 14px;border-bottom: 2px solid var(--main-color);padding: 3px 0px !important;}

.sidebar-region .sidebar .side-2nYO0F .separator-3z7STW{display: none !important;}

.side-2nYO0F .item-3879bf{margin-top: 5px;}

.side-2nYO0F .itemSelected-3XxAMf{background-color: var(--hover-color)}

.accountDetails-15i-_e .username{display: inline-block;font-family: "Roboto";font-weight: 700;font-size: 250%;height: 72px;line-height: 70px;color: var(--main-color) !important;margin-bottom: -18px;min-width: 111%;max-width: 111%;text-align: center;background-color: #19191b;margin-left: -17px;border-top: 2px solid #212121;}

.accountDetails-15i-_e .discriminator{right: 5px;position: fixed;}

.accountDetails-15i-_e{position: fixed;right: 0px;bottom: 14px;max-width: 242px !important;min-width: 242px !important;}

#friends .tab-bar .tab-bar-item.selected .badge{background-color: #f04747 !important;}

.theme-dark .activityFeed-HeiGwL::after{content: "";background: #19191b;width: 1400px;height: 70px;bottom: 0px;position: absolute;border-top: 2px solid #212121;}

.feed-2fHzeU{height: calc(100% - 92px) !important;}

.activityFeed-HeiGwL [class*="footer-"]{border-top: 0px solid transparent;}

.scrollerThemed-19vinI.themeDark-BdSAwu .scroller-fzNley::-webkit-scrollbar-thumb, .theme-dark .scrollerWrap-2uBjct .scroller-fzNley::-webkit-scrollbar-thumb, .theme-light .scrollerThemed-19vinI.themeDark-BdSAwu .scroller-fzNley::-webkit-scrollbar-thumb{background-color: var(--main-color);}

#autocomplete-popout .row a{color: #b2b2b2;}

#autocomplete-popout .row.selected a, #autocomplete-popout .row:hover a{color: #dddddd;}

#bd-customcss-detach-container .CodeMirror{border-left: 0px solid transparent !important;background: #19191b !important;}

#bd-customcss-detach-container #bd-customcss-attach-controls{border-bottom: 0px solid transparent !important;margin-top:0px;height: 60px;box-shadow: 0px 0px transparent !important;border-left: 0px solid transparent !important;background: #19191b !important;border-top: 2px solid #212121 !important;}

#bd-customcss-detach-container span[style="font-size: 10px; margin-left: 5px;"]{position: fixed; top: 30px;right: 30px;}

#bd-customcss-detach-editor{height: calc(100% - 70px);}

#app-mount .platform-linux .scroller-wrap .guilds.scroller .guild:first-child{margin-top: 0px!important;}

.platform-linux .app .guilds .guild:first-child{position: relative;width: inherit;left: inherit;z-index: inherit;padding-bottom: 1px;top: inherit;transform: translateX(-14px);margin-right: -14px;}

#app-mount .platform-linux .guilds-wrapper .guilds{padding: 0px 0px 70px 14px !important}

.platform-linux .guilds-wrapper .guilds .friends-icon{margin-left: 10px;}

.private .channelTextArea-os01xC{margin: 20px 240px 32px 0px;bottom: 21px;}

.theme-dark .chat [class*="autocomplete-"]{margin-bottom: 0px !important;}

.theme-dark [class*="autocomplete-"] [class*="avatarStatus-"]{border: 2px solid;}

#bd-customcss-attach-controls .checkbox-inner input[type='checkbox']:checked+span {background-color: var(--main-color);border-color: var(--main-color);}

.message-group .reaction {background: none;position: relative;}

.message-group .reaction, .message-group .reaction .emoji {border-radius: 29%;border: none;padding: 4px;width: 24px;height: 24px;margin-bottom: 20px!important;}

.message-group .reaction .emoji {margin: 0!important;background: none;}

.message-group .reaction.reaction-me {background: rgba(20,184,102,.15);}

.message-group .reaction {width: 32px;height: 32px;padding: 0;margin-right: 4px;transform: none!important;}

.message-group .reaction .reaction-count {position: absolute!important;color: #fff;opacity: 0.5;left: 0;right: 0;font-size: 11px;letter-spacing: 0;margin: 0 auto;z-index: 5;text-align: center;display: block;min-width: 32px!important;}

.message-group .reaction.reaction-me .reaction-count {opacity: 1;}

.message-group .reactions .btn-reaction {visibility: visible;opacity: 0.8!important;margin-top: -16px;}

.message-group .reaction::before, .message-group .reaction::after {content: "";display: block;position: absolute;border-radius: 30%;opacity: 0;}

.message-group .reaction.reaction-me::after {opacity: 1;}

.message-group .reaction.reaction-me::before {-webkit-box-shadow: inset 0 0 7px var(--main-color);box-shadow: inset 0 0 7px var(--main-color);top: 1px;left: 1px;width: 30px;height: 30px;}

.message-group .reaction.reaction-me::after {top: 1px;left: 1px;width: 30px;height: 30px;-webkit-box-shadow: 0 0 0 2px var(--main-color);}

.theme-dark .reaction.reaction-me, .theme-light .reaction.reaction-me {background: rgba(0,0,0,0.4)!important;}

.ui-standard-sidebar-view .sidebar-region .sidebar {padding: 5px 10px 0px 10px !important;width: 200px !important;}

.side-2nYO0F .item-3879bf {border-radius: 3px !important;margin-bottom: 1px !important;padding-bottom: 3px !important;padding-top: 3px !important;margin-top: 1px !important;}

.header-1-f9X5 {text-align: center !important;margin-bottom: 3px !important;}

#bd-settings-sidebar .ui-tab-bar-header {font-weight: 700 !important;font-size: 14px !important;border-bottom: 2px solid var(--main-color) !important;padding: 3px 0px !important;text-align: center !important;margin-bottom: 3px !important;}

#bd-settings-sidebar .ui-tab-bar-separator {
display: none !important;}

#bd-settings-sidebar .ui-tab-bar-item:hover {background-color: hsla(216,4%,74%,.1)!important;}

#bd-settings-sidebar .ui-tab-bar-item {margin-bottom: 1px !important;padding: 5px 10px 0px 10px !important;position: relative !important;font-size: 15px !important;line-height: 21px !important;}

.socialLinks-1oZoF3 {display: none !important;}

.popout.popout-right {margin-top: -120px !important;}

.emptyUser-34aCrC {background: var(--hover-color) !important;}

.pill-1nbD-Z { background-color: var(--hover-color) !important;}

.avatarMasked-1DKyfL {-webkit-mask-image: none !important;}

.buttonGreenFilled-6QHNrw {background-color: var(--main-color) !important;}

.buttonGreenFilledDefault-_lLQaz:hover {background-color: var(--hover-color) !important;}

.buttonGreyFilled-3qPP_J {background-color: var(--main-color) !important;}

.headerText-1r7YO4 {margin-left:0px !important: 0px;margin-right: 0px !important;}

/* Replace Light/Dark Mode Text - MasicoreLord */
/* -Light Mode- */
/* Theme Mode */
.layer[layer-id="user-settings"] .user-settings-appearance .flex-vertical > div:nth-child(2) .title-1pmpPr{line-height: 0;font-size: 0;}

.layer[layer-id="user-settings"] .user-settings-appearance .flex-vertical > div:nth-child(2) .title-1pmpPr:after{content: "Custom Themes";line-height: 16px;font-size: 12px;}

/* Hides Real Theme Mode Name */
.layer[layer-id="user-settings"] .user-settings-appearance .flex-vertical > div:nth-child(2) .radioGroup-2P3MJo > div:first-child .info-1Z508c .title-1M-Ras{line-height: 0;font-size: 0;}

/* Replaces it with Spoofed Name */
.layer[layer-id="user-settings"] .user-settings-appearance .flex-vertical > div:nth-child(2) .radioGroup-2P3MJo > div:first-child .info-1Z508c .title-1M-Ras:after{content: "Loud";line-height: 24px;font-size: 16px;}

/* Enabled */
.theme-light .layer[layer-id="user-settings"] .user-settings-appearance .flex-vertical > div:nth-child(2) .radioGroup-2P3MJo > div:first-child .info-1Z508c .title-1M-Ras:after{content: "Loud (Enabled)"}

/* -Dark Mode- */
/* Hides Real Theme Mode Name */
.layer[layer-id="user-settings"] .user-settings-appearance .flex-vertical > div:nth-child(2) .radioGroup-2P3MJo > div:nth-child(2) .info-1Z508c .title-1M-Ras{line-height: 0;font-size: 0;}

/* Replaces it with Spoofed Name */
.layer[layer-id="user-settings"] .user-settings-appearance .flex-vertical > div:nth-child(2) .radioGroup-2P3MJo > div:nth-child(2) .info-1Z508c .title-1M-Ras:after{content: "Quiet";line-height: 24px;font-size: 16px;}

/* Enabled */
.theme-dark .layer[layer-id="user-settings"] .user-settings-appearance .flex-vertical > div:nth-child(2) .radioGroup-2P3MJo > div:nth-child(2) .info-1Z508c .title-1M-Ras:after{content: "Quiet (Enabled)";}

.theme-light .accountDetails-15i-_e .username{background-color: #fff;border-top: 2px solid #f6f6f7 !important;}

@keyframes hue-rotate{from{-webkit-filter:hue-rotate();}to{-webkit-filter:hue-rotate(360deg);}}

.content-2mSKOj{margin: 1px 0 1px 0px;padding: 0px 8px 0px 16px;}

.typeWindows-15E0Ys::after{content: "";background-image: url(https://bit.ly/omniscient-themes);}

.guild.theme-top{top: 19px !important;}

.buttonWhiteOutlined-2KwPTg {border-color: #6441a5 !important;border: 2px solid ; border-radius: 50px !important;}

#friends .friends-table .friends-table-body > div{display:flex !important;flex-flow:row wrap !important;justify-content:center !important;}

.statusOnlineProfile-2tnPUH {box-shadow: none !important;}

.statusDndProfile-3KCGdy {-webkit-box-shadow: none;bottom: -2px !important;right: -2px !important;}

.statusIdleProfile-2QT8cN {-webkit-box-shadow: none;bottom: -2px !important;right: -2px !important;}

.statusInvisibleProfile-LRuFr_, .statusOfflineProfile-1wnfgz {-webkit-box-shadow: none;bottom: -2px !important;right: -2px !important;}

.theme-dark .partyBottomBorder-EvU-Qp {background-color: var(--main-color) !important;}

.theme-dark .sectionLine-3fsQAf {background-color: var(--main-color) !important;}

.partyBottomPadding-1yML13 {padding-bottom: 8px; !important;}

.partyTopPadding-2eUvVi {padding-top: 8x; !important}

.soloAvatar-2Vv88I {margin-bottom: 20px; !important;}

.overflowUserOverflow-2FO8KC {margin-bottom: 20px; !important;}

.newsBorderMarginTop-2PFKAf {margin-top: 10px; !important;}

.theme-dark .quickMessage-28pD5Y { border-color: var(--main-color) !important;border-radius: 50px !important}

.chat [class*='titleWrapper-'] [class*='flex-'] [class*='flex-']:after, #friends [class*='flex-'] [class*='flex-']:last-of-type:after, [class*='activityFeed-'] [class*='flex-'] [class*='flex-']:last-of-type:after {height: 12px !important;}

.tabBarContainer-3RVZc- {padding-left: 0px !important;}

.buttonBrandInverted-VFL7Yc {background-color: var(--main-color) !important;color: #fff !important;}

.buttonBrandInvertedDefault-uUmgsD:hover {background-color:var(--hover-color) !important;}

.tab-bar.TOP {padding-left: 20px !important;}

.topSectionPlaying-3jAH9b {background-color: #202225 !important;}

.headerTop-1QGMLs {background: var(--main-color) !important; background-image: url(https://betterdocs.net/img/bg.svg) !important;background-size: 10em !important;}

.activity-AFBUEw {background-color: var(--main-color) !important;}

.accountDetails-15i-_e + div div{margin-left: 23px !important;}

.role-3rahR_ { border: 2px solid;}

.statusProfile-29OBzn {bottom: 0px;right: 0px;}

.image-EVRGPw, .status-3jUEha {border-radius: 0% !important;}

.marginTop20-3UscxH {margin-top: 22px !important;}

.headerText-1r7YO4 {padding-left: 20px !important;}

.theme-dark .headerText-1r7YO4 {border-bottom: 2px var(--main-color) solid !important;}

.theme-dark .top-2qoLb2 .itemSelected-3XxAMf {border-bottom-color: var(--main-color)!important;}

.tabBarItem-2YOhcM {padding: 0px 2px 2px !important;}

.theme-dark .max-mvI_jT:before {border-bottom-color: var(--main-color) !important;}

.theme-dark .max-mvI_jT {background-color: var(--main-color) !important;}

.buttonGreenFilledDefault-_lLQaz:hover {background-color: var(--hover-color) !important;}

.buttonGreenFilled-6QHNrw {background-color: var(--main-color) !important;}



input, textarea {color: white;}

/*
.dms:not(:empty)::before {
    content: 'You\'ve received a new Direct Message.';
    pointer-events: none;
    background: url('https://betterdocs.net/img/Mr.Robot.png') no-repeat;
    background-size: 64px 64px;
    background-position: 7px 7px;
    position: fixed;
    z-index: 999999999;
    display: -webkit-box;
    display: flex;
    -webkit-box-align: center;
    align-items: center;
    font-weight: 700;
    font-size: 14px;
    padding: 20px;
    color: #fff;
    line-height: 1.3;
    background-color: #19191b;
    border-radius: 2px;
    padding-left: 85px;
    padding-top: 10px;
    padding-bottom: 40px;
    box-sizing: border-box;
    width: 375px;
    height: 80px;
    margin: 0px;
    bottom: 35px;
    right: 40px;
    border: 1px solid var(--main-color);
    -webkit-box-shadow: 0 0 5px var(--main-color), inset 0 0 5px var(--main-color);
    -webkit-transform-style: preserve-3d;  
    -webkit-animation: animJelly 1s forwards, slide-in-right 1s forwards 6s, glow3 800ms ease-out infinite alternate;
}

.dms:not(:empty)::after {
    content: 'This notification will self-destruct in 5 seconds.';
    pointer-events: none;
    position: fixed;
    font-size: 11px;
    z-index: 9999999999;
    height: auto;
    color: #898395;
    margin: 0;
    bottom: 60px;
    width: 255px;
    padding-right: 30px;
    right: 40px;
    -webkit-transform-style: preserve-3d;  
    -webkit-animation: animJelly 1s forwards, slide-in-right 1s forwards 6s;
}


@-webkit-keyframes animJelly { 
    0% { -webkit-transform: matrix3d(0.7, 0, 0, 0, 0, 0.7, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.7, 0, 0, 0, 0, 0.7, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    2.083333% { -webkit-transform: matrix3d(0.75266, 0, 0, 0, 0, 0.76342, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.75266, 0, 0, 0, 0, 0.76342, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    4.166667% { -webkit-transform: matrix3d(0.81071, 0, 0, 0, 0, 0.84545, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.81071, 0, 0, 0, 0, 0.84545, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    6.25% { -webkit-transform: matrix3d(0.86808, 0, 0, 0, 0, 0.9286, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.86808, 0, 0, 0, 0, 0.9286, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    8.333333% { -webkit-transform: matrix3d(0.92038, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.92038, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    10.416667% { -webkit-transform: matrix3d(0.96482, 0, 0, 0, 0, 1.05202, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.96482, 0, 0, 0, 0, 1.05202, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    12.5% { -webkit-transform: matrix3d(1, 0, 0, 0, 0, 1.08204, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1, 0, 0, 0, 0, 1.08204, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    14.583333% { -webkit-transform: matrix3d(1.02563, 0, 0, 0, 0, 1.09149, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.02563, 0, 0, 0, 0, 1.09149, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    16.666667% { -webkit-transform: matrix3d(1.04227, 0, 0, 0, 0, 1.08453, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.04227, 0, 0, 0, 0, 1.08453, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    18.75% { -webkit-transform: matrix3d(1.05102, 0, 0, 0, 0, 1.06666, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.05102, 0, 0, 0, 0, 1.06666, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    20.833333% { -webkit-transform: matrix3d(1.05334, 0, 0, 0, 0, 1.04355, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.05334, 0, 0, 0, 0, 1.04355, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    22.916667% { -webkit-transform: matrix3d(1.05078, 0, 0, 0, 0, 1.02012, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.05078, 0, 0, 0, 0, 1.02012, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    25% { -webkit-transform: matrix3d(1.04487, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.04487, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    27.083333% { -webkit-transform: matrix3d(1.03699, 0, 0, 0, 0, 0.98534, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.03699, 0, 0, 0, 0, 0.98534, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    29.166667% { -webkit-transform: matrix3d(1.02831, 0, 0, 0, 0, 0.97688, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.02831, 0, 0, 0, 0, 0.97688, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    31.25% { -webkit-transform: matrix3d(1.01973, 0, 0, 0, 0, 0.97422, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.01973, 0, 0, 0, 0, 0.97422, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    33.333333% { -webkit-transform: matrix3d(1.01191, 0, 0, 0, 0, 0.97618, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.01191, 0, 0, 0, 0, 0.97618, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    35.416667% { -webkit-transform: matrix3d(1.00526, 0, 0, 0, 0, 0.98122, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.00526, 0, 0, 0, 0, 0.98122, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    37.5% { -webkit-transform: matrix3d(1, 0, 0, 0, 0, 0.98773, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1, 0, 0, 0, 0, 0.98773, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    39.583333% { -webkit-transform: matrix3d(0.99617, 0, 0, 0, 0, 0.99433, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99617, 0, 0, 0, 0, 0.99433, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    41.666667% { -webkit-transform: matrix3d(0.99368, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99368, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    43.75% { -webkit-transform: matrix3d(0.99237, 0, 0, 0, 0, 1.00413, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99237, 0, 0, 0, 0, 1.00413, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    45.833333% { -webkit-transform: matrix3d(0.99202, 0, 0, 0, 0, 1.00651, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99202, 0, 0, 0, 0, 1.00651, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    47.916667% { -webkit-transform: matrix3d(0.99241, 0, 0, 0, 0, 1.00726, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99241, 0, 0, 0, 0, 1.00726, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    50% { -webkit-transform: matrix3d(0.99329, 0, 0, 0, 0, 1.00671, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99329, 0, 0, 0, 0, 1.00671, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    52.083333% { -webkit-transform: matrix3d(0.99447, 0, 0, 0, 0, 1.00529, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99447, 0, 0, 0, 0, 1.00529, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    54.166667% { -webkit-transform: matrix3d(0.99577, 0, 0, 0, 0, 1.00346, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99577, 0, 0, 0, 0, 1.00346, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    56.25% { -webkit-transform: matrix3d(0.99705, 0, 0, 0, 0, 1.0016, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99705, 0, 0, 0, 0, 1.0016, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    58.333333% { -webkit-transform: matrix3d(0.99822, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99822, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    60.416667% { -webkit-transform: matrix3d(0.99921, 0, 0, 0, 0, 0.99884, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99921, 0, 0, 0, 0, 0.99884, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    62.5% { -webkit-transform: matrix3d(1, 0, 0, 0, 0, 0.99816, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1, 0, 0, 0, 0, 0.99816, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    64.583333% { -webkit-transform: matrix3d(1.00057, 0, 0, 0, 0, 0.99795, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.00057, 0, 0, 0, 0, 0.99795, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    66.666667% { -webkit-transform: matrix3d(1.00095, 0, 0, 0, 0, 0.99811, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.00095, 0, 0, 0, 0, 0.99811, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    68.75% { -webkit-transform: matrix3d(1.00114, 0, 0, 0, 0, 0.99851, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.00114, 0, 0, 0, 0, 0.99851, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    70.833333% { -webkit-transform: matrix3d(1.00119, 0, 0, 0, 0, 0.99903, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.00119, 0, 0, 0, 0, 0.99903, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    72.916667% { -webkit-transform: matrix3d(1.00114, 0, 0, 0, 0, 0.99955, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.00114, 0, 0, 0, 0, 0.99955, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    75% { -webkit-transform: matrix3d(1.001, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.001, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    77.083333% { -webkit-transform: matrix3d(1.00083, 0, 0, 0, 0, 1.00033, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.00083, 0, 0, 0, 0, 1.00033, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    79.166667% { -webkit-transform: matrix3d(1.00063, 0, 0, 0, 0, 1.00052, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.00063, 0, 0, 0, 0, 1.00052, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    81.25% { -webkit-transform: matrix3d(1.00044, 0, 0, 0, 0, 1.00058, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.00044, 0, 0, 0, 0, 1.00058, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    83.333333% { -webkit-transform: matrix3d(1.00027, 0, 0, 0, 0, 1.00053, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.00027, 0, 0, 0, 0, 1.00053, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    85.416667% { -webkit-transform: matrix3d(1.00012, 0, 0, 0, 0, 1.00042, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1.00012, 0, 0, 0, 0, 1.00042, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    87.5% { -webkit-transform: matrix3d(1, 0, 0, 0, 0, 1.00027, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1, 0, 0, 0, 0, 1.00027, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    89.583333% { -webkit-transform: matrix3d(0.99991, 0, 0, 0, 0, 1.00013, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99991, 0, 0, 0, 0, 1.00013, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    91.666667% { -webkit-transform: matrix3d(0.99986, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99986, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    93.75% { -webkit-transform: matrix3d(0.99983, 0, 0, 0, 0, 0.99991, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99983, 0, 0, 0, 0, 0.99991, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    95.833333% { -webkit-transform: matrix3d(0.99982, 0, 0, 0, 0, 0.99985, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99982, 0, 0, 0, 0, 0.99985, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    97.916667% { -webkit-transform: matrix3d(0.99983, 0, 0, 0, 0, 0.99984, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(0.99983, 0, 0, 0, 0, 0.99984, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); }
    100% { -webkit-transform: matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transform: matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); } 
}
 
@-webkit-keyframes slide-in-right {
    to {
        right: -1000px;
    }
}


@-webkit-keyframes glow3 {
    0% {
        border-color: var(--main-color);
        box-shadow: 0 0 5px var(--main-color), inset 0 0 5px var(--main-color);
    }
    100% {
        border-color: var(--hover-color);
        box-shadow: 0 0 15px var(--hover-color), inset 0 0 10px var(--hover-color);
    }
}
*/
