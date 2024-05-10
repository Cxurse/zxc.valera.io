# zxc.valera.io
/*
 $$$$$$\  $$\        $$$$$$\  $$$$$$$\   $$$$$$\  $$\        $$$$$$\  
$$  __$$\ $$ |      $$  __$$\ $$  __$$\ $$  __$$\ $$ |      $$  __$$\ 
$$ /  \__|$$ |      $$ /  $$ |$$ |  $$ |$$ /  $$ |$$ |      $$ /  \__|
$$ |$$$$\ $$ |      $$ |  $$ |$$$$$$$\ |$$$$$$$$ |$$ |      \$$$$$$\  
$$ |\_$$ |$$ |      $$ |  $$ |$$  __$$\ $$  __$$ |$$ |       \____$$\ 
$$ |  $$ |$$ |      $$ |  $$ |$$ |  $$ |$$ |  $$ |$$ |      $$\   $$ |
\$$$$$$  |$$$$$$$$\  $$$$$$  |$$$$$$$  |$$ |  $$ |$$$$$$$$\ \$$$$$$  |
 \______/ \________| \______/ \_______/ \__|  \__|\________| \______/ 
*/
:root {
  /*Global variables that were made/edited by me*/
  --Main-Color: rgb(250, 0, 158); /*main master color*/
  --Secondary-Color: rgb(170, 0, 158); /*secondary color*/
  --Third-Color: rgb(110,0,158); /*third color*/
  --Color-4: rgb(90,0,158); /*color number 4*/
  --Color-5: hsla(320, 40%, 40%, 0.366); /*color number 5*/
  --Color-6: hsla(320, 50%, 50%, 0.466); /*color number 6*/
  --Grey-Color: rgb(31, 31, 31); /*grey color*/
  --Black: rgb(0,0,0); /*black color*/
  --White: rgb(255,255,255); /*white color*/
  --White-Second: rgb(175, 175, 175); /*white but gray color*/
  --Red-color: rgb(255,0,0); /*red color*/
  --Neon-Line: 150,0,150; /*master neon color*/
  --Neon-Line2: 255,0,0; /*red neon line*/
  --Neon-Rgb: var(--Neon-Line); /*neon node #1*/
  --Neon-Rgb2: var(--Neon-Line2); /*red noen node #2*/
  --Cards-Background-Color: rgb(63, 0, 64);/*darker cards color*/
  /*Backgrounds*/
  --master-background: url('https://github.com/xy-nyxy/AnotherEternity/blob/main/background/Master%20Background.png?raw=true'); /*master background*/
  --background-floating: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.2)) , var(--master-background)50% 50%/cover !important; /*background used in normal discord's code*/
  /*Gifs for popouts and stuff*/
  --loop-gif: url('https://github.com/xy-nyxy/AnotherEternity/blob/main/background/loop-gif.gif?raw=true'); /*Used in files background*/
  --loop-gif2: url('https://github.com/xy-nyxy/AnotherEternity/blob/main/background/loop-gif2.gif?raw=true'); /*Used in guild popouts > User popout*/
  --loop-gif3: url('https://github.com/xy-nyxy/AnotherEternity/blob/main/background/loop-gif3.gif?raw=true'); /*Used in guild popouts > Mentioned card*/
  --loop-gif-diamond: url('https://github.com/xy-nyxy/AnotherEternity/blob/main/background/loop-gif-diamond.gif?raw=true'); /*Used on home icon*/
  --logo-photo: url('https://raw.githubusercontent.com/xy-nyxy/AnotherEternity/main/background/Wumpus%20Pink.gif'); /*Used in Friends tab when no friends are online*/
  /*Borders*/
  --border1: 2px solid var(--Secondary-Color); /*master border*/
  --border2: 2px solid var(--Third-Color); /*border 2*/
  --border3: 2px solid rgb(90,0,150); /*border 3*/
  
  /*Others variables*/
  /*Radial status*/
  --rs-small-spacing: 0px;
  --rs-medium-spacing: 0.1px;
  --rs-large-spacing: 0px;
  --rs-small-width: 2px;
  --rs-medium-width: 3px;
  --rs-large-width: 4px;
  --rs-avatar-shape: 50%;
  --rs-online-color: #21df00;
  --rs-idle-color: #faa81a;
  --rs-dnd-color: #ee0000;
  --rs-offline-color: #636b75;
  --rs-streaming-color: #b300fa;
  --rs-invisible-color: #747f8d;
  --rs-phone-color: var(--rs-online-color);
  --rs-phone-visible: none;
}
/*Discord's global variables copy-paste and edited*/
.theme-dark, .theme-light {
  --info-positive-background: transparent!important;
  --info-positive-foreground: transparent!important;
  --info-warning-background: transparent!important;
  --info-warning-foreground: transparent!important;
  --info-danger-background: transparent!important;
  --info-danger-foreground: transparent!important;
  --status-positive-background: transparent!important;
  --status-positive-text: #fff;
  --status-warning-background: hsl(38,calc(var(--saturation-factor, 1)*95.7%),54.1%);
  --status-danger-background: hsl(359,calc(var(--Secondary-Color, 1)*82.6%),59.4%);
  --status-danger-text: var(--Main-Color);
  --focus-primary: hsl(197,calc(var(--saturation-factor, 1)*100%),47.8%);
}
.theme-dark {
  --header-primary: #8f949c;
  --header-secondary: #7a7f86;
  --text-normal: #fff;
  --text-muted: #55585d;
  --text-link: var(--Main-Color);
  --text-link-low-saturation: var(--Secondary-Color);
  --text-positive: hsl(139,calc(var(--saturation-factor, 1)*66.8%),58.6%);
  --text-warning: hsl(38,calc(var(--saturation-factor, 1)*95.7%),54.1%);
  --text-danger: hsl(359,calc(var(--saturation-factor, 1)*82.6%),59.4%);
  --text-brand: hsl(235,calc(var(--saturation-factor, 1)*86.1%),77.5%);
  --interactive-normal: var(--Third-Color);
  --interactive-hover: var(--Secondary-Color);
  --interactive-active: var(--Main-Color);
  --interactive-muted: var(--Color-4);
  --background-primary: transparent;
  --background-secondary: transparent;
  --background-secondary-alt: transparent;
  --background-tertiary: transparent;
  --background-accent: transparent;
  --background-floating: transparent;
  --background-nested-floating: transparent;
  --background-mobile-primary: transparent;
  --background-mobile-secondary: transparent;
  --background-modifier-hover: transparent;
  --background-modifier-active: transparent;
  --background-modifier-selected: transparent;
  --background-modifier-accent: transparent;
  --info-positive-text: #fff;
  --info-warning-text: #fff;
  --info-danger-text: #fff;
  --info-help-background: transparent;
  --info-help-foreground: transparent;
  --info-help-text: #fff;
  --status-warning-text: #000;
  --scrollbar-thin-thumb: var(--Main-Color);
  --scrollbar-thin-track: transparent;
  --scrollbar-auto-thumb: var(--Secondary-Color);
  --scrollbar-auto-track:  transparent;
  --scrollbar-auto-scrollbar-color-thumb: transparent;
  --scrollbar-auto-scrollbar-color-track: transparent;
  --elevation-stroke: 0 0 0 1px rgba(4,4,5,0.15);
  --elevation-low: 0 1px 0 rgba(4,4,5,0.2),0 1.5px 0 rgba(6,6,7,0.05),0 2px 0 rgba(4,4,5,0.05);
  --elevation-medium: 0 4px 4px rgba(0,0,0,0.16);
  --elevation-high: 0 8px 16px rgba(0,0,0,0.24);
  --logo-primary: #fff;
  --control-brand-foreground: hsl(235,calc(var(--saturation-factor, 1)*86.1%),77.5%);
  --control-brand-foreground-new: hsl(235,calc(var(--saturation-factor, 1)*86.1%),77.5%);
  --background-mentioned: transparent;
  --background-mentioned-hover: transparent;
  --background-message-hover: var(--Color-5);
  --background-message-automod: transparent;
  --background-message-automod-hover: transparent;
  --channels-default: var(--Secondary-Color);
  --guild-header-text-shadow: 0 1px 1px rgba(0,0,0,0.4);
  --channeltextarea-background: transparent;
  --activity-card-background: #202225;
  --textbox-markdown-syntax: #8e9297;
  --spoiler-revealed-background: #292b2f;
  --spoiler-hidden-background: #202225;
  --deprecated-card-bg: transparent;
  --deprecated-card-editable-bg: transparent;
  --deprecated-store-bg: transparent;
  --deprecated-quickswitcher-input-background: transparent;
  --deprecated-quickswitcher-input-placeholder: hsla(0,0%,100%,0.3);
  --deprecated-text-input-bg: transparent;
  --deprecated-text-input-border: rgba(0,0,0,0.3);
  --deprecated-text-input-border-hover: #040405;
  --deprecated-text-input-border-disabled: #202225;
  --deprecated-text-input-prefix: #dcddde;
  --button--underline-color: transparent !important;
  --channel-icon: var(--Secondary-Color);
}

/*Brand experminet things (idk what i did here but works)*/
:root {
	--brand-experiment: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%);
	--brand-experiment-100: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 98%);
	--brand-experiment-130: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 93.5%);
	--brand-experiment-160: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 89%);
	--brand-experiment-200: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 84.6%);
	--brand-experiment-230: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 80.1%);
	--brand-experiment-260: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 75.6%);
	--brand-experiment-300: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 71.1%);
	--brand-experiment-330: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 66.6%);
	--brand-experiment-360: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 62.1%);
	--brand-experiment-400: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 57.7%);
	--brand-experiment-430: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 53.2%);
	--brand-experiment-460: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 48.7%);
	--brand-experiment-500: hsl(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%);
	--brand-experiment-530: hsl(305, calc(var(--saturation-factor, 1)*44.9%), 40.8%);
	--brand-experiment-560: hsl(305, calc(var(--saturation-factor, 1)*35.9%), 37.3%);
	--brand-experiment-600: hsl(305, calc(var(--saturation-factor, 1)*32.8%), 33.9%);
	--brand-experiment-630: hsl(305, calc(var(--saturation-factor, 1)*32.8%), 30.5%);
	--brand-experiment-660: hsl(305, calc(var(--saturation-factor, 1)*32.8%), 27%);
	--brand-experiment-700: hsl(305, calc(var(--saturation-factor, 1)*32.8%), 23.6%);
	--brand-experiment-730: hsl(305, calc(var(--saturation-factor, 1)*32.8%), 20.2%);
	--brand-experiment-760: hsl(305, calc(var(--saturation-factor, 1)*32.8%), 16.7%);
	--brand-experiment-800: hsl(305, calc(var(--saturation-factor, 1)*32.8%), 13.3%);
	--brand-experiment-830: hsl(305, calc(var(--saturation-factor, 1)*32.8%), 9.9%);
	--brand-experiment-860: hsl(305, calc(var(--saturation-factor, 1)*32.8%), 6.4%);
	--brand-experiment-900: hsl(305, calc(var(--saturation-factor, 1)*32.8%), 3%);
	--brand-experiment-05a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.05);
	--brand-experiment-10a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.1);
	--brand-experiment-15a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.15);
	--brand-experiment-20a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.2);
	--brand-experiment-25a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.25);
	--brand-experiment-30a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.3);
	--brand-experiment-35a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.35);
	--brand-experiment-40a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.4);
	--brand-experiment-45a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.45);
	--brand-experiment-50a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.5);
	--brand-experiment-55a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.55);
	--brand-experiment-60a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.6);
	--brand-experiment-65a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.65);
	--brand-experiment-70a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.7);
	--brand-experiment-75a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.75);
	--brand-experiment-80a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.8);
	--brand-experiment-85a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.85);
	--brand-experiment-90a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.9);
	--brand-experiment-95a: hsla(305, calc(var(--saturation-factor, 1)*59.9%), 44.2%, 0.95);
}

/*
$$\      $$\  $$$$$$\  $$$$$$$$\ $$$$$$$$\ $$$$$$$\  $$\      $$\  $$$$$$\  $$$$$$$\  $$\   $$\ 
$$ | $\  $$ |$$  __$$\ \__$$  __|$$  _____|$$  __$$\ $$$\    $$$ |$$  __$$\ $$  __$$\ $$ | $$  |
$$ |$$$\ $$ |$$ /  $$ |   $$ |   $$ |      $$ |  $$ |$$$$\  $$$$ |$$ /  $$ |$$ |  $$ |$$ |$$  / 
$$ $$ $$\$$ |$$$$$$$$ |   $$ |   $$$$$\    $$$$$$$  |$$\$$\$$ $$ |$$$$$$$$ |$$$$$$$  |$$$$$  /  
$$$$  _$$$$ |$$  __$$ |   $$ |   $$  __|   $$  __$$< $$ \$$$  $$ |$$  __$$ |$$  __$$< $$  $$<   
$$$  / \$$$ |$$ |  $$ |   $$ |   $$ |      $$ |  $$ |$$ |\$  /$$ |$$ |  $$ |$$ |  $$ |$$ |\$$\  
$$  /   \$$ |$$ |  $$ |   $$ |   $$$$$$$$\ $$ |  $$ |$$ | \_/ $$ |$$ |  $$ |$$ |  $$ |$$ | \$$\ 
\__/     \__|\__|  \__|   \__|   \________|\__|  \__|\__|     \__|\__|  \__|\__|  \__|\__|  \__|
*/
div[class*="typeWindows-"]::after {
  content: '🔮ANOTHER ETERNITY🔮 v1.1.3';
  font-weight: bold;
  font-size: 14px;
  line-height: 30px;
  top: 0;
  left: 0;
  position: absolute;
  padding: 0 15px;
  z-index: -1;
  width: 100%;
  height: 20px;
  background: transparent;
  color: var(--Main-Color);
}

/*
$$$$$$$\   $$$$$$\   $$$$$$\  $$\   $$\  $$$$$$\  $$$$$$$\   $$$$$$\  $$\   $$\ $$\   $$\ $$$$$$$\   $$$$$$\  
$$  __$$\ $$  __$$\ $$  __$$\ $$ | $$  |$$  __$$\ $$  __$$\ $$  __$$\ $$ |  $$ |$$$\  $$ |$$  __$$\ $$  __$$\ 
$$ |  $$ |$$ /  $$ |$$ /  \__|$$ |$$  / $$ /  \__|$$ |  $$ |$$ /  $$ |$$ |  $$ |$$$$\ $$ |$$ |  $$ |$$ /  \__|
$$$$$$$\ |$$$$$$$$ |$$ |      $$$$$  /  $$ |$$$$\ $$$$$$$  |$$ |  $$ |$$ |  $$ |$$ $$\$$ |$$ |  $$ |\$$$$$$\  
$$  __$$\ $$  __$$ |$$ |      $$  $$<   $$ |\_$$ |$$  __$$< $$ |  $$ |$$ |  $$ |$$ \$$$$ |$$ |  $$ | \____$$\ 
$$ |  $$ |$$ |  $$ |$$ |  $$\ $$ |\$$\  $$ |  $$ |$$ |  $$ |$$ |  $$ |$$ |  $$ |$$ |\$$$ |$$ |  $$ |$$\   $$ |
$$$$$$$  |$$ |  $$ |\$$$$$$  |$$ | \$$\ \$$$$$$  |$$ |  $$ | $$$$$$  |\$$$$$$  |$$ | \$$ |$$$$$$$  |\$$$$$$  |
\_______/ \__|  \__| \______/ \__|  \__| \______/ \__|  \__| \______/  \______/ \__|  \__|\_______/  \______/ 
*/
.appMount-3lHmkl, body {
  background: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.2)) , var(--master-background) 50% 50%/cover !important;
  background-color: transparent !important;
  text-rendering: optimizeLegibility;
}
.appMount-2yBXZl, body {
  background: linear-gradient(rgba(0, 0, 0, 0.6),rgba(0, 0, 0, 0.8)) , var(--master-background) 50% 50%/cover !important;
  background-color: transparent !important;
  text-rendering: optimizeLegibility;
}

/*
$$$$$$$\  $$$$$$$$\ $$$$$$$\  $$\      $$\  $$$$$$\  $$\   $$\ $$$$$$$$\ $$\   $$\ $$$$$$$$\ 
$$  __$$\ $$  _____|$$  __$$\ $$$\    $$$ |$$  __$$\ $$$\  $$ |$$  _____|$$$\  $$ |\__$$  __|
$$ |  $$ |$$ |      $$ |  $$ |$$$$\  $$$$ |$$ /  $$ |$$$$\ $$ |$$ |      $$$$\ $$ |   $$ |   
$$$$$$$  |$$$$$\    $$$$$$$  |$$\$$\$$ $$ |$$$$$$$$ |$$ $$\$$ |$$$$$\    $$ $$\$$ |   $$ |   
$$  ____/ $$  __|   $$  __$$< $$ \$$$  $$ |$$  __$$ |$$ \$$$$ |$$  __|   $$ \$$$$ |   $$ |   
$$ |      $$ |      $$ |  $$ |$$ |\$  /$$ |$$ |  $$ |$$ |\$$$ |$$ |      $$ |\$$$ |   $$ |   
$$ |      $$$$$$$$\ $$ |  $$ |$$ | \_/ $$ |$$ |  $$ |$$ | \$$ |$$$$$$$$\ $$ | \$$ |   $$ |   
\__|      \________|\__|  \__|\__|     \__|\__|  \__|\__|  \__|\________|\__|  \__|   \__|   
*/
/*Permanent things that you always see.
Titlebar top buttons colors. Close, rezise and hide*/
.winButton-3UMjdg {
  color: var(--Main-Color);
}
/*Hide discord text from titlebar*/
.wordmarkWindows-2dq6rw {
  display: none;
}

/*Close pannel "ESC" button*/
/*normal*/
.closeButton-PCZcma, .keybind-13vtq8 {
  color: var(--Main-Color);
}
.closeButton-PCZcma:hover, .keybind-13vtq8:hover {
  color: var(--Secondary-Color);
}
.closeButton-PCZcma:hover, .closeButton-PCZcma:hover+.keybind-13vtq8 {
  color: var(--Secondary-Color);
}

/*Message Input Area*/
.channelTextArea-1FufC0 {
  margin-bottom: 24px;
  background: black !important;
  border: var(--Main-Color);
}
.channelTextArea-1VQBuV {
  background-color: black !important;
}
.editor-H2NA06 {
  caret-color: var(--Secondary-Color) !important;
}

/*Upload files button color*/
/*Stable*/
.attachButtonPlus-3IYelE {
  fill: var(--Secondary-Color);
}
/*Hover*/
.attachButtonPlus-3IYelE:hover {
  fill: var(--Main-Color);
  color: var(--Main-Color);
}

/*Atachements*/
/*Files*/
.attachment-1PZZB2 {
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
  background: linear-gradient(rgba(0, 0, 0, 0.6),rgba(0, 0, 0, 0.8)) , var(--loop-gif) 50% 50%/cover !important;
}

/*"You are viewing older messages" popout*/
.jumpToPresentBar-1cEnH0 {
  border: 1px solid var(--Secondary-Color);
  border-top-left-radius: 15px;
  border-top-right-radius: 15px;
  padding-bottom: 4px ;
  background: black !important;
}
/*"You are viewing older messages" color*/
.barButtonMain-2GIx4o {
  color: var(--Main-Color);
}
/*"Jump To Present" color*/
.barButtonAlt-TQoCdZ {
  color: var(--Main-Color);
}

/*Emoji popout*/
.wrapper-3u51GQ {
  background: black;
  border-radius: 15px;
}
.contentWrapper-3vHNP2 {
  padding: 6px;
  background-color: black;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
/*Little fix for background*/
.list-obNEuP {
  background-color: transparent !important;
}
/*Header*/
.header-11eigE {
  padding: 0px 0px 15px;
  background-color: transparent;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
/*Emoji Category Header*/
.wrapper-1NNaWG {
  background-color: black;
}
/*Default emoji icons colors*/
.categoryIcon-2cYeku {
  color: var(--Third-Color);
}
/*Hover/selected default emoji icons colors*/
/*Hover*/
.categoryItemDefaultCategorySelected-2YeRUu:hover, .categoryItemDefaultCategorySelected-2YeRUu:hover {
  color: var(--Main-Color);
}
.categoryItemDefaultCategory-3haEDq:hover .categoryIcon-2cYeku {
  color: var(--Main-Color);
}
/*Selected*/
.categoryItemDefaultCategorySelected-2YeRUu .categoryIcon-2cYeku, .categoryItemDefaultCategorySelected-2YeRUu:hover .categoryIcon-2cYeku {
  color: var(--Main-Color);
}

/*Sticker & gif popouts*/
.emojiPickerInExpressionPicker-2nOwH8, .container-3u7RcY {
  background: transparent;
}
/*Gif popout, favorite fade*/
.theme-dark .categoryFadeBlurple-1l49_Q, .theme-light .categoryFadeBlurple-1l49_Q {
  background-color: transparent;
}

/*Nitro gift popout*/
.spinner-3QeLKO {
  border-radius: 15px;
  background-color: var(--Black);
}

/*Pinned messages popout*/
.messagesPopoutWrap-3zryHW {
  background: black !important;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
/*Popout: the pinned message that u wanna pin*/
.theme-dark .message-G6O-Wv {
  background-color: transparent;
}
/*Inbox messages popout*/
/*Unreads*/
.container-2ebMPP {
  background-color: black;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 2.5px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}
/*Mentioned*/
.recentMentionsPopout-2bI1ZN {
  background-color: black;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 2.5px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}

/*Threads popout*/ 
.browser-mnQ1T7 {
  background-color: black;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 2.5px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}

/*Click on friend profile then hover on photo ["View Profile" fix]*/
.avatarHint-k7pYop {
  position: absolute;
  top: 0%;
  left: 0%;
  opacity: 0;
}

/*Left click on friends tab popout*/
.menu-1QACrS {
  background: black !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 2.5px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}
.accountProfilePopoutWrapper-3GskID [class^=menu-1QACrS]{
  background: none !important;
  box-shadow: none;
}
.scroller-1bVxF5 {
  background-color: transparent;
  border: transparent !important;
}
.item-1OdjEX:hover {
  color: var(--Main-Color) !important;
  background-color: var(--Color-5) !important;
  border-radius: 12px;
}

/*Button clicked*/
.colorDefault-CDqZdO:active:not(.hideInteraction-2jPGL_) {
  background-color: transparent;
  color: var(--Main-Color);
}
/*Hover on buttons*/
.colorDefault-CDqZdO.focused-3qFvc8 {
  background-color: transparent;
  color: var(--Main-Color);
}

/*Click on emoji for informations (in channels/dms)*/
.popoutContainer-2wbmiM {
  width: 288px;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 2.5px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
  background: black;
}

/*Triple code blocks text format*/
.markup-eYLPri code {
  scrollbar-color: var(--Secondary-Color);
  background: black !important;
  border-color: var(--Third-Color);
}
/*Single and double code block text format*/
.markup-eYLPri code.inline {
  border: none!important;
  box-shadow: none;
  background-color: var(--Color-5) !important;
  background: var(--Color-5) !important;
}

/*Timestamps everywhere*/
.content-3spvdd {
  color: var(--Main-Color) !important;
  background: black;
  border: var(--border2) !important;
  padding: 3px;
}
.divider-2rZFJK {
  border-top: var(--border2);
}
.cozy-VmLDNB .timestamp-p1Df1m {
  color: var(--Third-Color) !important;
}

/*Emoji searching, matching When typing for an emoji in chat "ex: :wink"*/
.theme-dark .autocomplete-3NRXG8 {
  background: var(--Black);
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}
/*Found searched emoji, matched emoji*/
.theme-dark .selected-3H3-RC {
  background-color: transparent;
  border: var(--border2);
}

/*CTRL+F Search & find messages popout*/
.theme-dark .container-2McqkF {
  background: black!important;
  border-radius: 15px; 
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}
/*Icon and "Search" text colors*/
.search-2Mwzzq .DraftEditor-root .public-DraftEditorPlaceholder-root, .icon-18rqoe {
  color: var(--Third-Color);
}

/*"Search Options" header container, text color*/
.resultsGroup-cfY57t .header-1BR0Ro {
  color: var(--Main-Color);
}
/*Subcategories (from, mentions, has, before, during, after, in, pinned) text color*/
.option-ayUoaq .searchOption-3u1gRt, .searchOption-3u1gRt .filter-2QaH9y, .searchOption-3u1gRt .answer-14OVbQ, .resultsGroup-cfY57t .plusIcon-1RVszG {
  color: var(--Secondary-Color) !important; 
}
/*Search history*/
/*Stable*/
.option-ayUoaq, .option-ayUoaq .filter-2QaH9y, .option-ayUoaq .answer-14OVbQ {
  color: var(--Secondary-Color) !important;
}
/*Hover*/
.option-ayUoaq:hover {
  background-color: var(--Color-5);
  border-radius: 15px;
}

/*Delete history*/
/*Stable*/
.resultsGroup-cfY57t .searchClearHistory-3nIKUO, .resultsGroup-cfY57t .searchLearnMore-1gNL3A {
  color: var(--Secondary-Color) !important;
}
/*Hover*/
.resultsGroup-cfY57t .searchClearHistory-3nIKUO:hover, .resultsGroup-cfY57t .searchLearnMore-1gNL3A:hover {
  color: var(--Main-Color) !important;
}

/*Search input text color*/
.search-2Mwzzq .DraftEditor-root .public-DraftStyleDefault-block {
  color: var(--Main-Color) !important;
}

/*After searching text color*/
.queryText-j8z984, .theme-dark .queryContainer-ZunrLZ strong  {
  color: var(--Secondary-Color) !important;
}
.queryShortcut-GrmI-7 {
  background-color: black !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}
.theme-dark .keybindShortcut-3zF1P9, .theme-dark .keybindShortcut-3zF1P9 .key-N5VmHN {
  background-color: transparent !important;
  color: var(--Main-Color);
  box-shadow: none !important;
}

/*Also in this popout, the last thing thing from a button*/
.option-ayUoaq:after {
  display: none!important;
}
/*CTRL+F After search popout*/
.searchResultsWrap-5RVOkx {
  background-color: black;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}
.theme-dark .focused-2FU0YH {
  background-color: transparent;
}

/*Disable home icon*/
.homeIcon-r0w4ny {
  display: none;
  width: 28px;
  height: 20px;
}

/*Custom background for home icon and for guilds with no photos*/
.childWrapper-1j_1ub {
  background: linear-gradient(rgba(170, 0, 158, 0.4),rgba(170, 0, 158, 0.3)) , var(--loop-gif-diamond) 50% 100%/cover !important;
  color: var(--text-normal);
}

/*Reactions popout from "See reactions" background*/
.theme-dark .container-KM8BU6, .theme-dark .reactors-1VXca7, .scroller-2GkvCq {
  background-color: black !important;
}

/*Message buttons*/
/*Stable*/
.button-3bklZh {
  color: var(--Third-Color);
}
/*Hover*/
.button-3bklZh:hover {
  color: var(--Main-Color);
}

/*Camera preview popout*/
.modalRoot-1bgrci {
  background-color: black;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Data picker*/
.react-datepicker {
  background-color: transparent !important;
}
.react-datepicker__month-container, .theme-dark .calendarPicker-sDhzdi .react-datepicker__day {
  color: var(--Main-Color);
}
.calendarPicker-sDhzdi .react-datepicker__header, .react-datepicker__month, .react-datepicker__day-names, .react-datepicker__week {
  background-color: transparent !important
}

/*Back button*/
.calendarPicker-sDhzdi .react-datepicker__navigation.react-datepicker__navigation--next, .calendarPicker-sDhzdi .react-datepicker__navigation.react-datepicker__navigation--previous {
  margin-top: 1px;
  margin-left: 1px;
  border: 1px var(--Main-Color) solid !important;
}

/*Disabled days*/
.theme-dark .calendarPicker-sDhzdi .react-datepicker__day--disabled, .theme-dark .calendarPicker-sDhzdi .react-datepicker__day--outside-month, .theme-dark .calendarPicker-sDhzdi .react-datepicker__day.react-datepicker__day--disabled, .theme-dark .calendarPicker-sDhzdi .react-datepicker__day.react-datepicker__day--disabled:hover {
  color: var(--Main-Color);
  background-color: var(--Color-5);
}

/*Borders*/
.calendarPicker-sDhzdi .react-datepicker__day {
  border-top: 1px solid var(--Color-5);
  border-left: 1px solid var(--Color-5);
}

/*Member since icon color*/
.discordIcon-32mgeP {
  color: var(--Secondary-Color);
}

/*Spotify activity (by & on) text color*/
/*by*/
.detailsWrap-omKn0b, .nameWrap-3TyM52 {
  color: var(--Main-Color);
  font-weight: 900;
}
/*on*/
.details-2-ciHo, .nameNormal-2fPMD2, .playTime-3fSgOm, .state-2NT76I, .timestamp-2f1NmH {
  color: var(--Main-Color);
  font-weight: 900;
}
/*Song lenght bar*/
.bar-1GpknY {
  border-color: var(--Main-Color);
  color: var(--Main-Color);
  background-color: var(--Third-Color);
}
.themed-1LCNAV .barInner-3dHef4 {
  background-color: var(--Main-Color);
}
/*Song lenght*/
.themed-1LCNAV .textLeft-1Noen0, .themed-1LCNAV .textRight-2IW704 {
  color: var(--Main-Color);
  font-weight: 900;
}
.activityName-3YXl6e, .nameNormal-2fPMD2, .nameWrap-3TyM52 {
  color: var(--Main-Color) !important;
}
.details-2-ciHo, .nameNormal-2fPMD2, .playTime-3fSgOm, .state-2NT76I, .timestamp-2f1NmH {
  color: var(--Main-Color) !important;
}


/*User popout cards, fix "User info, Activity border-bottom"*/
.top-K_jibn .selected-g-kMVV.themed-2-lozF.item-3XjbnG, .top-K_jibn .themed-2-lozF.item-3XjbnG:active {
  border-bottom: none;
}
.top-K_jibn .selected-g-kMVV.themed-2-lozF.item-3XjbnG, .top-K_jibn .themed-2-lozF.item-3XjbnG {
  border-bottom: none;
}
/*divider backgrounds*/
.divider-1tWBgZ {
  background-color: transparent !important;
}

/*Almost all buttons*/
/*Stable*/
.button-f2h6uQ .contents-3ca1mk {
  --button--underline-color: transparent;
  color: var(--Main-Color) !important;
  border-radius: 15px;
  background-image: none !important;
  text-decoration: none !important;
}
/*Hover*/
.button-f2h6uQ .contents-3ca1mk:hover {
  --button--underline-color: transparent;
  color: var(--Main-Color) !important;
  border-radius: 15px;
  background-image: none !important;
  text-decoration: none !important;
}
/*Change phone number? and Remove email button*/
/*Stable*/
.theme-dark .lookLink-15mFoz.colorPrimary-2AuQVo {
  border: 1px var(--button-outline-danger-border) solid;
  border-radius: 15px;
  margin-left: 10px;
}
/*Hover*/
.theme-dark .lookLink-15mFoz.colorPrimary-2AuQVo:hover {
  text-decoration: none !important;
  background-color: transparent !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb2)) !important;
  box-shadow: inset 0px 0px 1px 1px rgb(var(--Neon-Rgb2)), 0px 0px 15px 1px rgb(var(--Neon-Rgb2)) !important;
}

/*#################### Threads ####################*/
/*Backgrounds*/
.container-3wLKDe {
  background-color: transparent !important;
}

/*Post guidelines button color*/
/*Stable*/
.guidelinesButton-3Vrz0u {
  color: var(--Secondary-Color);
}
/*Hover*/
.guidelinesButton-3Vrz0u:hover {
  color: var(--Main-Color);
}

/*Search icon color*/
.pencilIcon-1d4fcw, .searchIcon-2Nw0OL {
  color: var(--Secondary-Color);
}

/*Threads containers*/
/*Stable*/
.container-2qVG6q {
  border: 1px var(--Main-Color) solid;
  transition: none !important;
  transform: none !important;
}
/*Hover*/
.container-2qVG6q:hover {
  transition: none !important;
  transform: none !important;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Threads tags text colors*/
.text-xs-bold-1NF1lz, .text-xs-semibold-3E_l31 {
  color: var(--Secondary-Color);
}

/*Icons colors*/
/*First > thread in a forum icon color from beggining. Second > forum name > thread name, the ">" color*/
.icon-3gfzEo, .caret-1le2LN {
  color: var(--Main-Color);
}

/*Create new thread from message*/
/*Icon color when container opened*/
.icon-382itv {
  color: var(--Main-Color);
}

/*Thread background*/
.scrollerInner-22scD4 {
  background-color: transparent;
}
.container-3XgAHv {
  background-color: black;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Thread input name container area*/
.inputWrapper-1YNMmM {
  border-radius: 15px;
  background-color: var(--Color-5);
}
.inputWrapper-1YNMmM {
  padding-left: 5px;
  padding-bottom: 2px;
}

/*Nitro gifts in dms/channels*/
/*backgrounds*/
.scroller-2M3eAB, .content-2eQb8J {
  background: transparent !important;
}
.modalHeader-gQTY3L {
  background: black;
}
.headerBackground-131uxy {
  background: transparent;
}
.tier2Foreground-2DWr4f, .wrapper-38Ds8r svg {
  background-color: transparent !important;
  background: transparent !important;
  background-image: none !important;
}

/*Nitro gifts by discord.gift, whole card*/
/*Stable*/
.tile-2mmK5T {
  background-color: black;
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}
/*Hover*/
.tile-2mmK5T:hover {
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Both cards background*/
.description-X8_53U, .mediaHorizontal-1eDgDq {
  background-color: black;
}

/*Title color*/
.title-oJa_A6 {
  color: var(--Main-Color);
}
/*Description color*/
.theme-dark .tagline-3DhQWg {
  color: var(--Secondary-Color);
}

/*Nitro text color*/
.theme-dark .headerIcon-1ACCh0, .theme-light .closeIcon-3tKOgJ, .theme-light .headerIcon-1ACCh0 {
  color: var(--Main-Color);
}

/*You are purchasing a gift text color*/
.colorSecondary-3_y5BS {
  color: var(--Main-Color);
  font-weight: 1000;
  font-size: medium;
}
/*Select plan > Payment > Review text color*/
.breadcrumb-17S_pr {
  color: var(--Secondary-Color);
}
/*Arrows colors*/
.breadcrumbArrow-1LY2zF {
  color: var(--Secondary-Color);
}

/*Toal to pay color*/
.pricePerInterval-3PUiOj strong {
  color: var(--Main-Color);
}

/*Choose one text color*/
.selectPlanChooseSubtitle-1MPOZK, .selectPlanChooseTitle-2d61LF {
  color: var(--Main-Color);
}

/*1 year, 1 month, prices text color*/
.optionSelected-2AMHHJ {
  color: var(--Main-Color);
}
.planOptionInterval-3QyrC0 {
  color: var(--Secondary-Color);
}
.planOption-187LtR {
  color: var(--Secondary-Color);
}

/*Total text color*/
.totalLabel-2RGUEh {
  color: var(--Main-Color);
}

/*Auto complete menu ( /command )*/
/*Header*/
.categoryHeader-OpJ1Ly { 
  background-color: black; 
}
/*Build in text color*/
.header-1XpmZs {
  color: var(--Main-Color);
}
/*small icon color*/
.icon-1kx1ir {
  color: var(--Secondary-Color);
}
/*big icon color (left one)*/
.selected-3B2w1z .icon-1kx1ir, .selected-3B2w1z:hover .icon-1kx1ir {
  color: var(--Main-Color);
}

/*Keyboard shortcuts modals (ctrl + /)*/
/*backgrounds*/
.keyboardShortcutsModal-2CRmCm, .keyboardShortcutList-3VFAYS {
  background-color: black;
}
.auto-2K3UW5.scrollerBase-_bVAAt.fade-1R6FHN {
  background-color: black;
}
.modalTitle-2skSKy {
  background-color: black;
  margin: 0 0 0 0;
}

/*Keyboard combos text color*/
.modalTitle-2skSKy .content-1i_k8f {
  color: var(--Main-Color);
  font-weight: 600;
}
/*subtitle text color*/
.modalSubtitle-2lx7qk {
  background-color: black;
  color: var(--Secondary-Color) !important;
  font-weight: 600;
}

/*All descriptions*/
.keyboardShortcutList-3VFAYS .keybindGroup-39HP2U .keybindDescription-oXh6w_ {
  color: var(--Secondary-Color) !important;
}

/*CTRL + T popout*/
/*content color, border, background*/
.quickswitcher-pKcM9U {
  width: unset;
  border: none;
  border-radius: 0px;
  padding: 20px 20px 0;
  box-shadow: none;
  background-color: none;
  color: none;
}
/*"Where would you like to go?" text color*/
.input-3r5zZY {
  border: none;
  color: var(--Main-Color);
  background-color: var(--Color-5);
}

/*Channels list hover*/
.result-u66Ywh[aria-selected=true] {
  background-color: var(--Color-5);
  border-radius: 15px;
}

/*Previous channels headers*/
.header-1ZpMzy {
  color: var(--Main-Color);
}
/*Previous channels descriptions*/
/*Icon color*/
.icon-12xJtb {
  color: var(--Secondary-Color);
}
/*Channel color*/
.badge-3k1jbq, .match-20K5f5 {
  color: var(--Secondary-Color);
}
/*Category color*/
.note-OhIxFa {
  color: var(--Third-Color);
}
/*Server name*/
.misc-XwBATi {
  color: var(--Secondary-Color);
}

/*ProTip Padding*/
.protip-1jXzAl {
  padding: 1px;
}

/*"Careful -- You have unsaved changes!" popout*/
.container-20TyK0 {
  background-color: black !important;
  width: 1000px;
  position: static !important;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
/*Message color*/
.theme-dark .message-3C6JQ1 {
  color: var(--Main-Color) !important;
}

/*RTC status popout*/
.container-1ILvLB {
  background-color: black;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
/*Text color*/
.popoutText-3NRmTw {
  color: var(--Main-Color);
}
.popoutText-3NRmTw.popoutTextDetails-zNomhC {
  color: var(--Third-Color);
}
/*Secure connection color*/
.secured-2wavXv {
  color: var(--Main-Color);
}

/*Guild Boost modal*/
/*text color*/
.perkDescription-3e1T_w {
  color: var(--Main-Color);
}

/*After clicking boost this server*/
/*Photo removal*/
.tier2Foreground-2DWr4f, .wrapper-38Ds8r svg {
  display: none;
}
/*background*/
.guildBackground-3BSNJY, .animation-3szaot, .header-kxb7f7 {
  background-image: none !important;
}

/*"Help a server unlock..." text color*/
.bodyText-1qcdxO {
  color: var(--Main-Color);
}

/*Add, remove (+ -) - Buttons colors*/
/*Stable*/
.icon-2TbMdT, .icon-2TbMdT.disabled-2gUzwG {
  color: var(--Secondary-Color);
  background-color: var(--Color-5);
}
/*Hover*/
.icon-2TbMdT:hover, .icon-2TbMdT.disabled-2gUzwG:hover {
  color: var(--Main-Color);
  background-color: var(--Color-4);
}

/*"Server boosts", subtotal, "You could be paying 30%..." text color*/
.planSelectorLabel-2T9D_0, .planSelectorSubtotal-1A7sWH, .upsellFooter-1H_OCF, .bodyText-3Op3yx {
  color: var(--Main-Color);
}

/*Price, price per interval text color*/
.planSelectorPreviewPrice-3is8Gl, .pricePerInterval-3PUiOj {
  color: var(--Secondary-Color);
}

/*Code upload (as a file) box container*/
.container-rr3Ruk {
  background-color: black;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 1px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 1px rgb(var(--Neon-Rgb)) !important;
}
/*Change language popout fix*/
.languageSelector-2e1IuO {
  background-color: black;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 1px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 1px rgb(var(--Neon-Rgb)) !important;
}
/*Languages list*/
/*Stable*/
.item-1BCeuB {
  color: var(--Secondary-Color);
}
/*Hover*/
.item-1BCeuB:hover {
  color: var(--Main-Color) !important;
}

/*Attachement name, code size text colors */
/*Stable*/
.attachmentName-vgRpzs, .formattedSize-1YbZww {
  color: var(--Secondary-Color);
}
/*Hover + Expand code, open full view, code size and change language icons on hover colors*/
.attachmentName-vgRpzs:hover, .toggleExpandSection-1710zV:hover, .openFullPreviewSection-31zc2v:hover, .formattedSize-1YbZww:hover, .attachmentName-vgRpzs:hover, .codeIcon-Ni8XUA:hover {
  color: var(--Main-Color);
}

/*New popout about nitro (update 25.10.2022)*/
.contentPremium-_Y0-cX {
  background-color: black !important;
}

/*Links with popouts*/
/*Description color*/
.embedDescription-1DrJxZ {
  color: var(--Secondary-Color);
}
/*Background*/
.grid-1aWVsE {
  background-color: black;
  border-top-right-radius: 15px;
  border-bottom-right-radius: 15px;
}

/*Add a server & explore public servers icons colors*/
.circleIconButton-1VxDrg {
  color: var(--Third-Color);
  background-color: var(--Color-5);
}
.circleIconButton-1VxDrg.selected-2r1Hvo {
  color: var(--Main-Color);
  background-color: var(--Color-6);
}

/*Server invites paused icon on server*/
.pauseBackground-1zgiN0 {
  background-color: var(--Third-Color);
  color: var(--Main-Color) !important;
}

/*In call "focus, more, show chat" icons*/
.controlIcon-10O-4h {
  color: var(--Third-Color);
}
.controlIcon-10O-4h:hover {
  color: var(--Secondary-Color);
}

/*Invite button color*/
.buttonColor-28DXIe {
  border-radius: 15px;
  background-color: black;
  border: 1px solid var(--Third-Color);
}
.buttonColor-28DXIe:hover {
  background-color: black;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Control buttons*/
/*When stable all icons colors*/
.colorable-3rVGna.primaryDark-2UJt1G, .colorable-3rVGna.primaryDark-2UJt1G .centerIcon-JYpTUi {
  color: var(--Main-Color);
}
/*When stable unmuted, camera, activity, share screen activity, emoji icon colors*/
.colorable-3rVGna.primaryDark-2UJt1G {
  background-color: var(--Color-5);
}
/*When muted icon color*/
.colorable-3rVGna.white-11auuQ .centerIcon-JYpTUi {
  color: var(--Main-Color);
}
/*When muted icon color*/
.colorable-3rVGna.white-11auuQ {
  background-color: var(--Color-4);
}
/*When hover on unmute and emoji icon color*/
.colorable-3rVGna.white-11auuQ.active-3D763s, .colorable-3rVGna.white-11auuQ:hover {
  background-color: var(--Color-6);
}
/*When hover on camera, activity, share screen colors*/
.colorable-3rVGna.primaryDark-2UJt1G.active-3D763s, .colorable-3rVGna.primaryDark-2UJt1G:hover {
  background-color: var(--Color-6);
}
/*Stable disconnect icon*/
.colorable-3rVGna.red-3T8maV {
  background-color: var(--Color-5);
  color: var(--Main-Color);
}
/*When hover on disconnect*/
.colorable-3rVGna.red-3T8maV:hover {
  background-color: var(--Color-6);
  border-color: rgb(var(--Neon-Rgb2)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb2)), 0px 0px 15px 4px rgb(var(--Neon-Rgb2)) !important;
}
/*Disconnect color icon*/
.centerIcon-JYpTUi, .centerIcon-JYpTUi:hover {
  color: var(--Main-Color) !important;
}

/*Invite button from no one else is here yet, invite people to join*/
.button-3Vyz67 {
  background-color: var(--Color-5);
}
.button-3Vyz67:hover {
  background-color: var(--Color-6);
}

/*Name background color*/
.overlayTitle-2efoIF {
  background-color: var(--Color-5);
}

/*Muted/deafen icon*/
.status-15kcmy {
  color: var(--Main-Color);
  background-color: var(--Color-5);
}

/*When someone is speaking border*/
.border-2Vy6FN.speaking-7QZEkv {
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Emoji colors*/
.slots-paZlX-, .slotsContainer-3Li39W {
  background-color: black;
}
.container-3a5mk- {
  background-color: black;
}

/*
$$\   $$\  $$$$$$\  $$\      $$\ $$$$$$$$\ 
$$ |  $$ |$$  __$$\ $$$\    $$$ |$$  _____|
$$ |  $$ |$$ /  $$ |$$$$\  $$$$ |$$ |      
$$$$$$$$ |$$ |  $$ |$$\$$\$$ $$ |$$$$$\    
$$  __$$ |$$ |  $$ |$$ \$$$  $$ |$$  __|   
$$ |  $$ |$$ |  $$ |$$ |\$  /$$ |$$ |      
$$ |  $$ | $$$$$$  |$$ | \_/ $$ |$$$$$$$$\ 
\__|  \__| \______/ \__|     \__|\________|
*/
/*Friends tab*/
/*Main container background*/
.theme-dark .container-2cd8Mz {
  background-color: transparent !important;
}

/*"No one is around to play with wumpus" text message*/
.text-27cdrj, .title-2CL_z0 {
  color: var(--Secondary-Color);
}
/*The image*/
.image-20MDYu {
  background-image: var(--logo-photo) !important;
}

/*Activity cards background "In a voice channel"*/
/*Stable*/
.wrapper-2RrXDg {
  background-color: transparent;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
/*Hover*/
.wrapper-2RrXDg:hover {
  background: none !important;
}
/*Selected*/
.theme-dark .outer-2JOHae.active-1W_Gl9, .theme-dark .outer-2JOHae.interactive-2zD88a:hover {
  background: none !important;
}

/*Server name, channel name, friend icon card background*/
.section-3G9aLW {
  background-color: var(--Color-5);
}

/*Add friend border card*/
.addFriendInputWrapper-kkoSV9 {
  background-color: var(--Color-5);
  border: none;
  border-radius: 15px;
}
.addFriendInput-1Ta-rO {
  background-color: transparent;
  border: none;
  color: var(--Main-Color);
  margin-right: 16px;
}

/*It's quiet from now message*/
.emptyCard-KDifrB {
  background: transparent !important;
  border-radius: 8px;
  padding: 16px;
  color: var(--Main-Color) !important;
}

/*Message, more options for friends*/
/*Stable*/
.actionButton-3-B2x- {
  color: var(--Main-Color) !important;
  background-color: transparent !important;
}
/*Hover*/
.actionButton-3-B2x-:hover {
  color: var(--Secondary-Color);
  background-color: transparent !important;
}

/*Search icon from search section*/
.medium-2NClDM .iconContainer-6pgShY {
  width: 20px;
  height: 20px;
  color: var(--Main-Color) !important;
}

/*Friends and Nitro Icons Colors*/
.linkButtonIcon-7rsZcu {
  width: 24px;
  height: 24px;
  color: var(--Main-Color) !important;
}

/*Active now Text Color*/
.header-Imy05m {
  font-family: var(--font-display);
  margin: 8px 0 16px;
  font-weight: 700;
  color: var(--Main-Color) !important;
}

/*Online Tab Text Color*/
.title-x4dI75 {
  margin: 16px 20px 8px 30px;
  color: var(--Main-Color) !important;
}
/*Online friends card*/
/*Name and status color*/
.text-3j8t_e {
  color: var(--Secondary-Color);
}

/*Add friend tab*/
/*Stable*/
.tabBar-ra-EuL .addFriend-emTWY1.addFriend-emTWY1.addFriend-emTWY1, .tabBar-ra-EuL .addFriend-emTWY1.addFriend-emTWY1.addFriend-emTWY1 {
  background-color: transparent;
  color: var(--Third-Color);
}
/*Hover*/
.tabBar-ra-EuL .addFriend-emTWY1.addFriend-emTWY1.addFriend-emTWY1, .tabBar-ra-EuL .addFriend-emTWY1.addFriend-emTWY1.addFriend-emTWY1:hover {
  background-color: transparent;
  color: var(--Secondary-Color);
}
/*Selected*/
.tabBar-ra-EuL .addFriend-emTWY1.addFriend-emTWY1.addFriend-emTWY1[aria-selected=true] {
  background-color: transparent;
  color: var(--Main-Color);
}

/*Direct Messages Text Color*/
.headerText-1qIDDT {
  color: var(--Main-Color) !important;
}

/*Friends Text Color*/
.title-17SveM {
  color: var(--Main-Color) !important;
}

/*Know as (friend name in guild) color*/
.tooltip-C5N4wl {
  color: var(--Secondary-Color);
}

/*Find or start a conversation Text Color*/
/*Stable*/
.searchBar-3TnChZ .searchBarComponent-3N7dCG {
  color: var(--Secondary-Color);
}
/*Hover*/
.searchBar-3TnChZ .searchBarComponent-3N7dCG:hover {
  color: var(--Main-Color);
}

/*#################### Invite modal ####################*/
/*Backgrounds*/
.theme-dark .contentWrapper-3oy4Xo {
  background-color: transparent;
  border-radius: 15px;
}
.modal-atz_3z {
  border-radius: 15px !important;
}
/*Header*/
.theme-dark .separator-2lLxgC {
  border-radius: 15px;
}
/*Middle*/
.scroller-3nFW5p {
  border-radius: 15px;
}
/*Footer*/
.theme-dark .footer-1hTRRZ {
  background: transparent;
  border-radius: 15px;
}

/*Channel icon (before channel name)*/
.channelIcon-2x-GOw {
  color: var(--Main-Color);
}
/*Copy button size*/
.copyButton-2k4drX {
  margin-right: 2px;
  margin-left: 8px;
}

/*Learn more text*/
.anchor-1MIwyf {
  font-weight: 800;
}

/*Public servers icon*/
.avatar-1HDIsL {
  color: var(--Main-Color);
}

/*Search input color*/
.bd-search {
  color: var(--Main-Color);
}

/*Pagination color*/
.bd-pagination span {
  color: var(--Main-Color);
}

/*Server cards*/
/*Stable*/
.bd-server-card {
  border: 1px var(--Main-Color) solid;
  background-color: black !important;
}
/*Hover*/
.bd-server-card:hover {
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Server name, description colors*/
.bd-server-name {
  color: var(--Main-Color);
}
.bd-server-description {
  color: var(--Secondary-Color);
}

/*Members, added date colors*/
.bd-server-count-text {
  color: var(--Secondary-Color);
}

/*#################### Discovery tab ####################*/
/*Main background*/
.interactive-iyXY_x {
  background-color: transparent;
}
.scroller-3j5xK2 {
  background-color: black !important;
}
.interactive-iyXY_x:hover {
  border-radius: 15px;
  background-color: var(--Color-5);
}
.interactive-iyXY_x[aria-selected=true], .selected-3veCBZ {
  border-radius: 15px;
  background-color: var(--Color-6);
}

/*Search thing*/
.search-25t1e9 .searchBox-31Zv9h {
  background-color: black !important;
  color: var(--Main-Color);
}
/*input color*/
.searchBoxInputWrapper-3XLwVB {
  color: var(--Main-Color);
}
/*Border color*/
.search-25t1e9 .searchBox-31Zv9h:focus, .search-25t1e9 .searchBox-31Zv9h:focus-within, .theme-dark .searchBox-pyIJJj {
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Server Cards*/
.card-2TuZPZ {
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}
.card-2TuZPZ:hover {
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Student hubs headertext colors*/
.text-lg-semibold-2iEErr {
  color: var(--Main-Color) !important;
}

/*Blur blocked users list*/
/*Stable*/
.listItemContents-f4Uz5J {
  filter: blur(8px) !important;
}
/*Hover*/
.listItemContents-f4Uz5J:hover {
  filter: blur(0px) !important;
}


/*
 $$$$$$\  $$$$$$$$\ $$$$$$$\  $$$$$$$$\  $$$$$$\  $$\      $$\ $$$$$$\ $$\   $$\  $$$$$$\  
$$  __$$\ \__$$  __|$$  __$$\ $$  _____|$$  __$$\ $$$\    $$$ |\_$$  _|$$$\  $$ |$$  __$$\ 
$$ /  \__|   $$ |   $$ |  $$ |$$ |      $$ /  $$ |$$$$\  $$$$ |  $$ |  $$$$\ $$ |$$ /  \__|
\$$$$$$\     $$ |   $$$$$$$  |$$$$$\    $$$$$$$$ |$$\$$\$$ $$ |  $$ |  $$ $$\$$ |$$ |$$$$\ 
 \____$$\    $$ |   $$  __$$< $$  __|   $$  __$$ |$$ \$$$  $$ |  $$ |  $$ \$$$$ |$$ |\_$$ |
$$\   $$ |   $$ |   $$ |  $$ |$$ |      $$ |  $$ |$$ |\$  /$$ |  $$ |  $$ |\$$$ |$$ |  $$ |
\$$$$$$  |   $$ |   $$ |  $$ |$$$$$$$$\ $$ |  $$ |$$ | \_/ $$ |$$$$$$\ $$ | \$$ |\$$$$$$  |
 \______/    \__|   \__|  \__|\________|\__|  \__|\__|     \__|\______|\__|  \__| \______/ 
*/
/*Screen share popout border*/
/*Stable*/
.theme-dark .elevationHigh-3KUiqj, .pictureInPictureVideo-2puO2Q {
  border: 1px var(--Main-Color) solid;
  border-radius: 15px;
}
.theme-dark .elevationHigh-3KUiqj:hover, .pictureInPictureVideo-2puO2Q:hover {
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 2px 1px rgb(var(--Neon-Rgb)), 0px 0px 5px 1px rgb(var(--Neon-Rgb));
}

/*Applications, Screens Text Color*/
/*Stable*/
.item-LN5zvA {
  cursor: pointer;
  font-size: 13px;
  margin-right: 20px;
  padding-top: 20px;
  padding-bottom: 20px;
  color: var(--Third-Color);
}
/*Hover*/
.item-LN5zvA:hover {
  cursor: pointer;
  font-size: 13px;
  margin-right: 20px;
  padding-top: 20px;
  padding-bottom: 20px;
  color: var(--Secondary-Color);
}
/*Selected*/
.item-LN5zvA[aria-selected=true] {
  cursor: pointer;
  font-size: 13px;
  margin-right: 20px;
  padding-top: 20px;
  padding-bottom: 20px;
  color: var(--Main-Color);
}
/*Remove border and change box color*/
.theme-dark .selected-2xa993 {
  color: var(--Main-Color);
  border-bottom: none !important;
}

/*Footer background color*/
.footer-31IekZ {
    border-radius: 0 0 0px 0px;
    background-color: transparent;
}

/*"Select something to stream and have your friends grab a seat!" text color*/
.headerDescription-yFPU-Q {
    text-align: center;
    padding: 0 32px;
    color: var(--Main-Color) !important;
}

/*"Sound may not be available..." text color*/
.text-xs-normal-3SiVjE {
    font-weight: 1000;
    color: var(--Secondary-Color) !important;
}
/*Icon Color*/
.warningIcon-3vNf04 {
  width: 20px;
  height: 20px;
  margin-right: 8px;
  color: var(--Secondary-Color);
}

/*Stream Quality > Smoother Video Background*/
.option-2eIyOn[aria-selected=true]:not(.option-2eIyOn.multi-1HXDiv) {
  color: var(--Main-Color);
  background-color: black !important;
}
/*The icon after selected option color*/
.selectedIcon-19TbzU {
  color: var(--Main-Color);
}

/*Stream in hd resoultion*/
/*Stable*/
.gradientBackground-MytxDL {
    background: transparent;
    color: var(--Secondary-Color);
}
/*Hover*/
.gradientBackground-MytxDL:hover {
  background-color: var(--Color-5);
  color: var(--Secondary-Color);
}

/*Resolution, Frame Rate text color*/
/*Stable*/
.selectorButtonSelected-3cQUnj {
  background-color: var(--Color-5);
}
.selectorButton-3fWZ0_:not(.selectorButtonPremiumRequired-IZXhgV):hover {
  background-color: var(--Color-4);
}
.selectorText-LxivBc {
  font-weight: 1000;
  color: var(--Main-Color) !important;
}

/*Smooter Video, Better text reading, custom options text color*/
/*Stable*/
.option-2eIyOn {
    color: var(--Third-Color) !important;
}
/*Hover*/
.option-2eIyOn:hover {
  color: var(--Secondary-Color) !important;
  background-color: var(--Color-5);
  border-radius: 15px !important;
}
/*Selected*/
.option-2eIyOn[aria-selected=true] {
  color: var(--Main-Color) !important;
}

/*Screen 1 text color*/
.ellipsisText-1-5iVA {
  white-space: nowrap;
  text-overflow: ellipsis;
  overflow: hidden;
  max-width: 100%;
  margin-right: 8px;
  color: var(--Third-Color) !important;
}
/*Icon Color*/
.selectedIcon-277z4I {
    margin-right: 8px;
    color: var(--Third-Color) !important;
}

/*Streaming channel text color*/
.channelName-3Ezu2W {
    color: var(--Third-Color);
}
/*Icon color*/
.channelIcon-1BydE- {
    margin-right: 5px;
    color: var(--Third-Color) !important;
}

/*"Notify my friends in this server that I'm streaming" Checkbox color*/
.theme-dark .checkbox-f1HnKB {
  border-color: var(--Main-Color);
}


/*Streaming popout preview controls icons colors*/
.bottomControls-34xgN7 {
    color: var(--Main-Color) !important;
}
/*Streaming popout preview background*/
.videoControls-e2Ogs3 {
    border-color: rgb(var(--Neon-Rgb));
    box-shadow: inset 0px 0px 2px 1px rgb(var(--Neon-Rgb)), 0px 0px 5px 1px rgb(var(--Neon-Rgb));
}

/*
$$\      $$\ $$$$$$$$\ $$\   $$\ $$$$$$$$\ $$$$$$\  $$$$$$\  $$\   $$\  $$$$$$\  
$$$\    $$$ |$$  _____|$$$\  $$ |\__$$  __|\_$$  _|$$  __$$\ $$$\  $$ |$$  __$$\ 
$$$$\  $$$$ |$$ |      $$$$\ $$ |   $$ |     $$ |  $$ /  $$ |$$$$\ $$ |$$ /  \__|
$$\$$\$$ $$ |$$$$$\    $$ $$\$$ |   $$ |     $$ |  $$ |  $$ |$$ $$\$$ |\$$$$$$\  
$$ \$$$  $$ |$$  __|   $$ \$$$$ |   $$ |     $$ |  $$ |  $$ |$$ \$$$$ | \____$$\ 
$$ |\$  /$$ |$$ |      $$ |\$$$ |   $$ |     $$ |  $$ |  $$ |$$ |\$$$ |$$\   $$ |
$$ | \_/ $$ |$$$$$$$$\ $$ | \$$ |   $$ |   $$$$$$\  $$$$$$  |$$ | \$$ |\$$$$$$  |
\__|     \__|\________|\__|  \__|   \__|   \______| \______/ \__|  \__| \______/ 
*/
/*In guild channels*/
/*Mentioned background (the yellow name)*/
.mentioned-Tre-dv {
  background-color: var(--Color-5);
  border-radius: 15px;
}
.mentioned-Tre-dv:before {
  background-color: transparent;
}
.message-2CShn3.selected-2LX7Jy, .mouse-mode.full-motion .message-2CShn3:hover, .message-2CShn3.mentioned-Tre-dv.selected-2LX7Jy, .mouse-mode.full-motion .mentioned-Tre-dv:hover {
  background-color: var(--Color-5) !important;
  border-radius: 15px;
}

/*Unread mentioned badge after channel in guild*/
.mentionsBadge-3H1BKJ {
  pointer-events: none;
}
.base-3IDx3L {
  color: var(--Main-Color) !important;
  background-color: var(--Color-4) !important;
}

.mentionsBadge-3H1BKJ .iconBase-2RQsdz {
  color: var(--Main-Color) !important;
  background-color: var(--Color-4) !important;
}

/*
$$\   $$\  $$$$$$\  $$$$$$$$\ $$$$$$$\         $$$$$$\  $$$$$$$$\ $$$$$$$$\ $$$$$$$$\ $$$$$$\ $$\   $$\  $$$$$$\   $$$$$$\  
$$ |  $$ |$$  __$$\ $$  _____|$$  __$$\       $$  __$$\ $$  _____|\__$$  __|\__$$  __|\_$$  _|$$$\  $$ |$$  __$$\ $$  __$$\ 
$$ |  $$ |$$ /  \__|$$ |      $$ |  $$ |      $$ /  \__|$$ |         $$ |      $$ |     $$ |  $$$$\ $$ |$$ /  \__|$$ /  \__|
$$ |  $$ |\$$$$$$\  $$$$$\    $$$$$$$  |      \$$$$$$\  $$$$$\       $$ |      $$ |     $$ |  $$ $$\$$ |$$ |$$$$\ \$$$$$$\  
$$ |  $$ | \____$$\ $$  __|   $$  __$$<        \____$$\ $$  __|      $$ |      $$ |     $$ |  $$ \$$$$ |$$ |\_$$ | \____$$\ 
$$ |  $$ |$$\   $$ |$$ |      $$ |  $$ |      $$\   $$ |$$ |         $$ |      $$ |     $$ |  $$ |\$$$ |$$ |  $$ |$$\   $$ |
\$$$$$$  |\$$$$$$  |$$$$$$$$\ $$ |  $$ |      \$$$$$$  |$$$$$$$$\    $$ |      $$ |   $$$$$$\ $$ | \$$ |\$$$$$$  |\$$$$$$  |
 \______/  \______/ \________|\__|  \__|       \______/ \________|   \__|      \__|   \______|\__|  \__| \______/  \______/ 
*/
/*#################### Page layouts ####################*/
/*Sidebar layout*/
.sidebarRegion-1VBisG {
  -ms-flex: 1 0 218px;
  flex: 0 0 0px;
}

/*#################### My account tab ####################*/
/*Page layout*/
.contentColumn-1C7as6, .customColumn-2n-oKU {
  -ms-flex: 1 1 auto;
  flex: 1 1 auto;
  max-width: 2000px;
  min-width: 460px;
  min-height: 100%;
}
/*name and tag colors*/
.username-3JLfHz, .discriminator-2m-MqL {
  color: var(--Main-Color) !important;
}

/*Headers Text Colors (Username, Email, Phone Number, Two Factor Authentification, Sms Backup Authentification, Account removal)*/
.h5-2RwDNl {
  color: var(--Main-Color) !important;
}

/*All text descriptions (Two-Factor authentificator (2FA)... & Add your phone number... & Your current phone number... & Disabling your account...) Text Colors*/
.description-30xx7u, .labelDescriptor-34wZ-z {
  color: var(--Secondary-Color) !important;
  padding-left: 15px;
}
/*Two factor authentificator icon color*/
.userSettingsSecurity-2kODPN .lockIcon-3t6Ow0 {
  margin-right: 4px;
  position: relative;
  color: var(--Main-Color);
}

/*Remove 2FA, Delete Account buttons colors*/
/*Stable*/
.lookOutlined-3yKVGo.colorRed-rQXKgM {
  background-color: transparent !important;
  border-radius: 15px;
}
/*Hover*/
.lookOutlined-3yKVGo.colorRed-rQXKgM:hover {
  background-color: transparent !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb2)) !important;
  box-shadow: inset 0px 0px 1px 1px rgb(var(--Neon-Rgb2)), 0px 0px 15px 1px rgb(var(--Neon-Rgb2)) !important;
}

/*Name, Email, Phone Number Buttons Colors*/
/*Stable*/
.lookFilled-yCfaCM.colorPrimary-2AuQVo {
  color: var(--Secondary-Color);
  background-color: transparent;
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}
/*Hover*/
.lookFilled-yCfaCM.colorPrimary-2AuQVo:hover {
  color: var(--Main-Color);
  background-color: transparent;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
.lookFilled-yCfaCM.colorPrimary-2AuQVo:disabled {
  background-color: transparent;
  border-radius: 15px;
}

/*Username, Email, Phone Number (not the titles, the contents) text colors*/
.text-md-medium-2avxhQ, .text-md-normal-304U3g {
  line-height: 20px;
  color: var(--Main-Color) !important;
}

/* #################### Profiles tab #################### */

/*User profile, Server profile text color*/
/*Stable*/
.top-K_jibn .item-3XjbnG {
  border-bottom: none !important;
  text-decoration: none !important;
  color: var(--Third-Color);
  padding: 5px 10px 5px 10px;
}
/*Hover*/
.tabBarItem-MeqDhW:hover {
  padding: 10px !important;
  margin-right: 0px;
  color: var(--Secondary-Color) !important;
  padding: 5px 10px 5px 10px;
}
/*Selected*/
.top-K_jibn .item-3XjbnG[aria-selected=true] {
  border-radius: 15px;
  border: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
  text-decoration: none !important;
  color: var(--Main-Color);
  padding-right: 10px !important;
  margin-right: 10px !important;
}
.tabBar-2hXqzU, .tabBarItem-30Te4- {
  padding: 10px;
}
/*Buttons size*/
.tabBarItem-MeqDhW {
  padding: 10px !important;
  margin-right: 0px;
}
/*"Example button" color*/
.buttonColor-1u-3JF {
  background-color: black;
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}
.buttonColor-1u-3JF:hover {
  background-color: black;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*User probile pag layout*/
.sectionsContainer-3BlPu4 {
  max-width: 400px !important;
  max-height: 540px !important;
}

/*Avatar decoration card background*/
.limitedBackground-2ogRHb, .limitedFeatureBorder-hpm0GQ {
  background-color: var(--Black);
  border-color: var(--Black) !important;
}

/*Preview banners*/
.profileBannerPreview-3mLIdO {
  background-color: black;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
.bannerSVGWrapper-qc0szY {
  max-width: 342px !important;
}
.overlayBackground-1KgwVi {
  background-color: transparent !important;
  background: transparent !important;
}

/*Nitro tab profile view*/
.improvedUpsellContainer-GX81ui {
  width: 684px;
  margin-top: 48px;
  margin-left: -12px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
  background: black;
}
.background-3N0xBT {
  background: transparent;
  border-radius: 15px;
}
.premiumFeatureBorder-3vL7bn {
  background: black !important;
  border: 1px solid var(--Main-Color) !important;
  border-radius: 15px;
}

/*Banner color, Color picker popout*/
.theme-dark .colorPickerCustom-1swUKF {
  background-color: black;
  border-radius: 15px;
  padding: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*"About me" text area background*/
.bioTextArea-dDGOeC {
  width: unset;
  background-color: transparent;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}

/* User popout preview */
.preview-Z55SA3 {
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}
/* Disable Banner */
.bannerNitroUpsell-2iP18z {
  display: none;
}
.banner-3D8GgT {
  width: 0%;
}
/*"Avatar, Profile color, Preview, Profile Banner, About me" text paddings*/
.defaultMarginh5-3Jxf6f {
  padding-top: 5px;
  padding-left: 5px;
}

/*#################### Privacy and safety ####################*/
/*Request data button color, border and background*/
/*Normal*/
.lookOutlined-3yKVGo.colorBrand-I6CyqQ {
  color: var(--Secondary-Color);
  border: none !important;
  border-radius: 15px;
}
/*Hover*/
.lookOutlined-3yKVGo.colorBrand-I6CyqQ:hover {
  background-color: transparent;
  color: var(--Main-Color);
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}
/*Text*/
.contents-3ca1mk {
  color: var(--Main-Color);
}

/*All blue and underlined text*/
/*Stable*/
.anchor-1MIwyf {
  color: var(--Main-Color) !important;
  text-decoration: none !important;
}
/*Hover*/
.anchor-1MIwyf:hover {
  color: var(--Secondary-Color) !important;
  text-decoration: none !important;
}
/*Check out or Terms and... text color*/
.colorStandard-1Xxp1s {
  color: var(--Secondary-Color);
}

/*#################### Authorized Apps Tab ####################*/

/*Cards borders*/
.cardPrimaryOutline-1ofwVz {
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*#################### Connections tab ####################*/

/*Cards borders*/
.connection-YOVI9j {
  background-color: transparent;
  width: 100%;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Display on profile text color*/
.text-sm-bold-1Dtt0R, .text-sm-semibold-3TWn25 {
  color: var(--Secondary-Color) !important;
}

/*Connected accounts name color*/
.connectionAccountLabelContainer-1KuLS6 {
  color: var(--Main-Color);
}

/*Platform/Game name (under account name) text color*/
.connectionAccountLabel-28GEPk {
  margin-left: 16px;
  color: var(--Secondary-Color) !important;
}

/*#################### Billing settings ####################*/
/*#################### Nitro tab ####################*/

/*Unleash more fun with nitro card*/
.settingsContainer-36qZZ9 {
  background: black;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
/*Stars colors*/
.sparkleStar-J6zUP3 {
  color: var(--Main-Color);
}
/*"Plan starts at..." text color*/
.description-2_tPhd {
  color: var(--Main-Color) !important;
}

/*Nitro classic card*/
/*background*/
.tier0-17mYUd {
  background-image: none;
  background-color: black;
  background: black;
}
/*Nitro basic text color*/
.tier0LogoContainer-cNnIFm {
  color: var(--Main-Color);
}

/*New nitro cards backgrounds*/
.ctaWrapperTier2-1hk2M8, .ctaWrapperTier0-1GlgHE {
  background-image: none !important;
  background-color: var(--Black) !important;
}

/*Nitro tier text colors*/
.tier0CtaLogoContainer-1tt-UU, .ctaLogo-hfS4Fj {
  color: var(--Main-Color) !important;
}

/*Limited time holiday card background color*/

/*Nitro card (Make discord yours)*/
.hero-1aNo0v {
  background-image: none;
  color: var(--Main-Color);
  background: black !important;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
  height: 300px;
}

/*Discord nitro header text color*/
.hero-1aNo0v .heroHeader-1A0uOZ, .heroIcon-3kmupU {
  color: var(--Main-Color);
}

/*Ready to upgrade to Nitro? text color*/
.marketingRefreshTitle-UaHKpk {
  color: var(--Main-Color);
  font-size: 24px;
  line-height: 30px;
  margin-bottom: 8px;
  margin-top: 0;
}
/*Pick the plan... text color*/
.marketingRefreshSubtitle-17I8Dd {
  color: var(--Secondary-Color);
  font-size: 16px;
  line-height: 20px;
  margin: 0;
}

/*Nitro classic text color*/
.marketingRefreshTier1Logo-38ksW_ {
  color: var(--Main-Color);
  display: block;
  height: 20px;
  margin-bottom: 8px;
  width: 194px;
}

/*Want to keep... text color (under nitro classic)*/
.marketingRefreshDescription-2_tCTt {
  color: var(--Main-Color);
  font-size: 16px;
  line-height: 20px;
  margin: 0 0 16px;
}

/*#################### Server boost tab ####################*/
/*"Server boost" text color*/
.marketingLogoIcon-3HQY2K {
  color: var(--Main-Color);
}

/*Anyone can help... text color (under server boost header)*/
.marketingHeader-CpUYrf {
  margin: 8px 0 16px;
  color: var(--Secondary-Color);
}

/*"Boost a server and get" & "Boosted servers can get" messages*/
.base-21yXnu.muted-eZM05q {
  color: var(--Main-Color);
}
/*All descriptions (A member.../A shiny.../An exclusive.../Room for.../Unlock more.../Better quality.../etc)*/
.descriptionStandalone-3ChjDk {
  color: var(--Secondary-Color);
}

/*#################### Subscriptions tab ####################*/
/*"Your subscriptions" description text message */
.sectionDescription-2ealM1 {
  color: var(--Main-Color);
}
/*"Subscription credit" description text message */ 
.accountCreditDescription-1lEaJI {
  color: var(--Main-Color);
}
/*"Your subscriptions" "You have no active subscriptions" text message*/
.cardText-1KLO-g {
  color: var(--Main-Color);
}
/*"Subscription credit" "You have no unused credits"*/
.cardText-3dmnX6 {
  color: var(--Main-Color);
}

/*#################### Gift inventory ####################*/
/*"Reedem codes" text area input*/
.input-2g-os5 {
  color: var(--Main-Color) !important;
  background-color: transparent;
}
.input-2g-os5:hover {
  color: var(--Main-Color) !important;
  background-color: transparent;
}

/*#################### Biling ####################*/
/*Transaction history*/
/*"Date", "Description" & "Amount"*/
.theme-dark .paymentPane-ut5qKZ {
  background-color: transparent;
  color: var(--Main-Color);
}
/*Under container details and background*/
.theme-dark .paginator-1eqD2g {
  background: transparent;
}
.theme-dark .bottomDivider-ZmTm-j {
  background-color: transparent;
}

/*"Psst! Looking to redeem a Discord key? We've moved it to" message and card*/
.theme-dark .codeRedemptionRedirect-2hYMSQ {
  color: var(--Main-Color);
  background-color: transparent;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}

/*#################### App Settings ####################*/
/*#################### Apperance tab ####################*/
/*Chat font scalling bars colors*/
/*The bars*/ 
/*The line thats above*/
.barFill-2Bh7CX {
  background: var(--Main-Color);
  height: 100%;
}
/*The line that is under*/
.theme-dark .bar-1Bhnl9, .theme-dark .markDash-yk2kJ- {
  background-color: var(--Third-Color);
}

/*Values (12px, 14px, 15px, etc)*/
.markValue-2U_-UG {
  color: var(--Third-Color);
}

/*Grabbers*/
.grabber-2GQyvM {
  border-radius: 3px;
  background-color: var(--Third-Color);
  border-color: var(--Main-Color);
}

/*#################### Accesibility ####################*/
/*Text to speech button color*/
.lookFilled-yCfaCM.colorBrandNew-2-gGsS {
  color: var(--Main-Color);
  background-color: transparent !important;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*#################### Voice and video ####################*/
/**/

/*#################### Text & Images ####################*/
/**/

/*#################### Notifications ####################*/
/**/

/*#################### Keybinds ####################*/
/*Keybinds are disabled... text message*/
.text-2iTkaw {
  margin-left: 10px;
  color: var(--Secondary-Color);
}

/*All keybinds text colors*/
.key-N5VmHN {
  background-color: var(--background-accent);
  border: 1px solid var(--background-primary);
  color: var(--Main-Color) !important;
}
.key-N5VmHN .bindArrow-EmK4SC {
  width: 10px;
  height: 10px;
  color: var(--Main-Color) !important;
}
.theme-dark .keybindShortcut-3zF1P9 .key-N5VmHN .bindArrow-EmK4SC g {
  fill: var(--Main-Color) !important;
}

/*#################### Languages ####################*/
/**/

/*#################### Windows settings ####################*/
/**/

/*#################### Streamer Mode ####################*/
/**/

/*#################### Advanced ####################*/
/**/

/*#################### Activity settings ####################*/
/*#################### Activity privacy ####################*/
/*Add a new game popout*/
.theme-dark .addGamePopout-2SKNIV {
  background: black !important;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}
/*"Select" background card*/
.lookFilled-1GseHa.select-1Ia3hD {
  background-color: var(--Color-5);
  border-radius: 15px;
}
/*Select background game popout*/
.popout-1KHNAq {
  background: black !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}

/*#################### Activity privacy ####################*/
/*#################### Registred games ####################*/
/*No game detected text color*/
.gameName-zbZetm {
  font-size: 16px;
  font-weight: 600;
  line-height: 22px;
  color: var(--Main-Color) !important;
}

/*Now playing game text color (Not seeing your game)*/
.theme-dark .nowPlayingAdd-3I4RbE {
  color: var(--Main-Color);
}

/*Last played game text color*/
.hoverRoll-2XwpoF {
  color: var(--Secondary-Color);
}

/*The bar between the games*/
.theme-dark .game-2f2vPC {
  color: var(--Main-Color) !important;
  box-shadow: var(--Main-Color) !important;
}

/*#################### Game overlay ####################*/
/*Overlay notifications, notification positions cards background and colors*/
.wrapper-SdcMKg {
  border-radius: 9px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
/*Selected overlay position*/
.selected-18Wszc.option-1QI4c9 {
  background-color: var(--Main-Color);
}
/*Overlay position*/
/*Static*/
.option-1QI4c9 {
  background-color: var(--Third-Color);
}
/*Hover*/
.option-1QI4c9:hover {
  background-color: var(--Secondary-Color);
}

/*Disabled icon color*/
.disabledIcon-1rpL82 {
  color: var(--Third-Color);
}

/*#################### BetterDiscord ####################*/
/*#################### Settings ####################*/
/*Settings titles colors*/
.bd-settings-title {
  color: var(--Main-Color) !important;
}
/*Lines color*/
.bd-settings-group.collapsible .bd-settings-title::before {
  background-color: var(--Color-5);
}
/*All category titles colors*/
.bd-setting-header label {
  color: var(--Secondary-Color);
}
/*All descriptions for sub categoryes colors*/
.bd-setting-note {
  color: var(--Third-Color);
}

/*All lists/popouts and inputs backgrounds*/
.bd-select, .bd-number-input {
  background-color: var(--Color-5);
  border-top-left-radius: 15px;
  border-top-right-radius: 15px;
}
/*Popouts*/
.bd-select .bd-select-options {
  background-color: black;
  color: var(--Third-Color);
  border-bottom-left-radius: 15px;
  border-bottom-right-radius: 15px;
}
.bd-select-option:hover {
  background-color: var(--Color-5) !important;
  border-radius: 12px;
}

/*Arrow dropdowns*/
.bd-settings-group.collapsible .bd-settings-title::after {
  background-color: var(--Main-Color);
}

/*Sliders (turn on/off things) colors*/ 
.bd-switch input {
  transition: none;
  color: var(--Main-Color) !important;
}
.bd-switch {
  transition: none;
  color: var(--Main-Color) !important;
}
.bd-switch-body {
  transition: none;
  background-color: var(--Secondary-Color);
}

/*#################### Updates ####################*/
/*Check for updates buttons*/
/*Stable*/
.bd-button {
  background-color: transparent;
  color: var(--Main-Color);
  border-radius: 15px;
  padding: 4px 8px;
  transition: none;
  border: 1px var(--Main-Color) solid;
}
/*Hover*/
.bd-button:hover {
  background-color: transparent;
  color: var(--Secondary-Color);
  border-radius: 15px;
  transition: none;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Icon checkmark color*/
.bd-filled-checkmark, .bd-empty-updates svg {
  background-color: var(--Color-5);
  border-radius: 15px;
}

/*Updates status description*/
.bd-empty-updates {
  color: var(--Main-Color);
}

/*BD-addon list, disease theme script fix transparent background*/
.bd-addon-card:hover .bd-description-wrap, .bd-addon-card:hover {
  background-color: black;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
/*Description color*/
.bd-addon-list .bd-description {
  color: var(--Secondary-Color);
}

/*#################### Custom Css ####################*/
/*Header color*/
#bd-editor-controls {
  background-color: black;
  border-top-left-radius: 15px;
  border-top-right-radius: 15px;
}

/*################### Plugins & Themes ###################*/
/*Sort by: & Order: text colors*/
.bd-select-wrapper label {
  color: var(--Main-Color);
}

/*Selected things (name / ascendending)*/
.bd-select-value {
  color: var(--Secondary-Color);
}

/*Buttons List/Grid View*/
.bd-addon-views .bd-view-button.selected {
  background-color: var(--Color-6);
  border: none !important;
}
.bd-addon-views .bd-view-button {
  border: none !important;
}

/*Themes and plugins names colors*/
.bd-name {
  color: var(--Main-Color);
}

/*#################### HypeSquad tab ####################*/
/*"You're exited about..." text color*/
.defaultColor-24IHKz {
  color: var(--Secondary-Color);
}

/*Perks of being hype, titles & descriptions colors*/
.title-2pQsrN {
  color: var(--Main-Color);
}
.description-22Sl9U {
  color: var(--Secondary-Color);
}

/*"Intereseted in repping..." text color from the bottom of the page*/
.attendeeCTA-2etnq5 {
  color: var(--Main-Color);
}

/*
 $$$$$$\  $$$$$$$$\ $$$$$$$\  $$\    $$\ $$$$$$$$\ $$$$$$$\         $$$$$$\  $$$$$$$$\ $$$$$$$$\ $$$$$$$$\ $$$$$$\ $$\   $$\  $$$$$$\   $$$$$$\  
$$  __$$\ $$  _____|$$  __$$\ $$ |   $$ |$$  _____|$$  __$$\       $$  __$$\ $$  _____|\__$$  __|\__$$  __|\_$$  _|$$$\  $$ |$$  __$$\ $$  __$$\ 
$$ /  \__|$$ |      $$ |  $$ |$$ |   $$ |$$ |      $$ |  $$ |      $$ /  \__|$$ |         $$ |      $$ |     $$ |  $$$$\ $$ |$$ /  \__|$$ /  \__|
\$$$$$$\  $$$$$\    $$$$$$$  |\$$\  $$  |$$$$$\    $$$$$$$  |      \$$$$$$\  $$$$$\       $$ |      $$ |     $$ |  $$ $$\$$ |$$ |$$$$\ \$$$$$$\  
 \____$$\ $$  __|   $$  __$$<  \$$\$$  / $$  __|   $$  __$$<        \____$$\ $$  __|      $$ |      $$ |     $$ |  $$ \$$$$ |$$ |\_$$ | \____$$\ 
$$\   $$ |$$ |      $$ |  $$ |  \$$$  /  $$ |      $$ |  $$ |      $$\   $$ |$$ |         $$ |      $$ |     $$ |  $$ |\$$$ |$$ |  $$ |$$\   $$ |
\$$$$$$  |$$$$$$$$\ $$ |  $$ |   \$  /   $$$$$$$$\ $$ |  $$ |      \$$$$$$  |$$$$$$$$\    $$ |      $$ |   $$$$$$\ $$ | \$$ |\$$$$$$  |\$$$$$$  |
 \______/ \________|\__|  \__|    \_/    \________|\__|  \__|       \______/ \________|   \__|      \__|   \______|\__|  \__| \______/  \______/ 
*/
/*Sidebar > Category headers ("Guild name", "Community", "User Management") colors*/
.header-2Kx1US {
  color: var(--Main-Color);
}
/*Sidebar > Sub-category colors*/
/*Default*/
.brand-3g5E0C.item-3XjbnG, .themed-2-lozF.item-3XjbnG {
  color: var(--Third-Color);
}
/*Hover*/
.brand-3g5E0C.item-3XjbnG, .themed-2-lozF.item-3XjbnG:hover {
  color: var(--Secondary-Color);
  background-color: var(--Color-5) !important;
  border-radius: 15px;
  padding-right: 10px !important;
  margin-right: 10px !important;
}
/*When sub-category selected > border and color*/
.brand-3g5E0C.item-3XjbnG, .themed-2-lozF.item-3XjbnG[aria-selected=true] {
  color: var(--Main-Color);
  background-color: var(--Color-6) !important;
  border-radius: 15px;
}

/*Server boost status color text and background*/
.serverBoostTabItem-3QwA3W[aria-selected=true] {
  background-color: transparent !important;
  color: var(--Main-Color) !important;
  border-left: 2px solid var(--Main-Color) !important;
}

/*All buttons*/
.container-2nx-BQ {
  opacity: 0.3;
  background-color: var(--Secondary-Color) !important;
}

/* #################### Overview #################### */
/*All spacers*/
.theme-dark .divider--oiTeJ {
  border-color: var(--Third-Color);
}

/*Server overview*/
.defaultColor-2cKwKo {
  color: var(--Main-Color);
  font-weight: 800;
}

/*All titles ("Server name", "Inactive channel", "Inactive timeout", "System message channel", "Default notification settings", "Server banned background lvl2", "Server invite background lvl1")*/
.h5-2RwDNl {
  color: var(--Main-Color);
  font-weight: 900;
}

/*All disabled dropdowns*/
.select-1Ia3hD, .wrapper-1b33hy {
  color: var(--Secondary-Color);
  border: none;
}

/*All sub dropdowns*/
.colorStandard-21JIj7 {
  color: var(--Secondary-Color);
  border: none;
}

/*Icons sub dropdowns*/
/*Stable*/
.icon-poPImO {
  color: var(--Secondary-Color) !important;
}

/*Category name color*/
/*Stable*/
.subtitle-2SfoOV {
  color: var(--Third-Color);
}

/*Remove button under the photo*/
/*Stable*/
.removeButton-2apMfV {
  color: var(--Secondary-Color) !important;
  background-color: transparent !important;
  border-radius: 15px !important;
  border: 1px var(--Main-Color) solid;
  padding: 10px 10px 10px 10px;
  margin-left: 210px;
  margin-right: 210px;
}
/*Hover*/
.removeButton-2apMfV:hover {
  color: var(--Main-Color) !important;
  background-color: transparent !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Change icon text color*/
.imageUploaderInner-IIRaFr:focus-within .imageUploaderHint-33zkjZ, .imageUploaderInner-IIRaFr:hover .imageUploaderHint-33zkjZ {
  color: var(--Main-Color);
}
/*Image uploader icon color*/
.theme-dark .imageUploaderIcon-2OHmFu {
  background-color: var(--Secondary-Color);
}

/*Upload Image button*/
/*Stable*/
.lookOutlined-3yKVGo.colorPrimary-2AuQVo {
  color: var(--Secondary-Color) !important;
  background-color: transparent !important;
  border-radius: 15px !important;
  border: 1px var(--Main-Color) solid;
}
/*Hover*/
.lookOutlined-3yKVGo.colorPrimary-2AuQVo:hover {
  color: var(--Main-Color) !important;
  background-color: transparent !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Display*/
/*Show boost progress bar*/
.colorInteractiveActive-30E9n8 {
  color: var(--Secondary-Color);
}

/*Server Banner backgrounds*/
.avatarUploaderInnerSquareDisabled-3M9eJS {
  background-color: black;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*"Unlock with boosting" buttons colors*/
/*Stable*/
.shinyButton-2Q9MDB {
  background-color: transparent !important;
  color: transparent !important;
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}
.shinyButton-2Q9MDB:hover {
  background-color: transparent !important;
  color: transparent !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/* #################### Roles #################### */
/*Page layout*/
.customScroller-m1-jZn>div {
  margin-right: 40px;
  max-width: 2000px;
}

/*Default Permissions*/ 
/*Icon color*/
.icon-2DGsye {
  color: var(--Secondary-Color);
}
/*Card background*/
/*Stable*/
.container-3EtAkD {
  background-color: var(--Black);
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}
/*Hover*/
.container-3EtAkD:hover {
  background-color: var(--Black);
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Roles & Members margins*/
.rolesTable-11lOYY {
  margin-top: 40px;
  margin-left: 40px;
  margin-right: 40px;
  margin-bottom: 0px;
}

/*Roles cards*/
/*Stable*/
.roleRow-230vCm {
  border-radius: 15px;
  margin: 5px;
}
/*Hover*/
.roleRow-230vCm:hover {
  background-color: var(--Color-5) !important;
}

/*Roles cards hover*/
.container-1zDvAE:hover {
  background-color: var(--Color-5);
  border-radius: 12px;
}

/*Roles cards > members count > icon color*/
/*Stable*/
.person-2z4Mcy {
  color: var(--Secondary-Color);
}
/*Hover*/
.person-2z4Mcy:hover {
  color: var(--Secondary-Color);
}

/*Roles cards > "Edit and More" icons colors*/
.roleRow-230vCm:hover:not(.roleRowDisableHover-3En0vy) .circleButton-2Yr5A1 {
  color: var(--Main-Color);
}

/*Drag icon color*/
.dragIcon-2L691r {
  color: var(--Secondary-Color);
}
.dragIcon-2L691r:hover {
  color: var(--Main-Color);
}

/*Search roles container background*/
.container-2oNtJn, .inner-2pOSmK {
  background-color: var(--Color-5);
  border-radius: 15px;
}

/*The arrow icon*/
.arrow-2v2Yl2 {
  color: var(--Secondary-Color);
}

/*Search roles input*/
.input-2m5SfJ {
  color: var(--Secondary-Color);
}

/*Create role button*/
/*Normal*/
.lookFilled-yCfaCM.colorBrand-I6CyqQ {
  color: var(--Main-Color);
  border: 1px var(--Main-Color) solid;
  background-color: transparent !important;
  border-radius: 15px;
}
/*Hover*/
.lookFilled-yCfaCM.colorBrand-I6CyqQ:hover {
  color: var(--Secondary-Color);
  background-color: transparent !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}

/* ########## Roles > Default permissions tab ########## */
/*Page layout*/
/*Edit role container*/
.contentWidth-3aWel5 {
  max-width: 1500px;
}
/*Scrollers overflow*/
.scroller-39BnzZ {
  overflow: hidden;
}

/*Back button and arrow color*/
/*Normal*/
.title-JU0E7C {
  color: var(--Secondary-Color);
}
/*Hover*/
.title-JU0E7C:hover {
  color: var(--Main-Color);
}

/*Create new role "+" icon*/
.addRole-viKZpC {
  color: var(--Secondary-Color);
}
.addRole-viKZpC:hover {
  color: var(--Main-Color);
}

/*Roles list*/
/*Stable*/
.row-LoqnA5 {
  color: var(--Secondary-Color);
  margin-bottom: 10px !important;
}
/*Hover*/
.row-LoqnA5:hover {
  color: var(--Main-Color);
  background-color: var(--Color-5) !important;
  border-radius: 15px;
}
/*Selected*/
.row-LoqnA5[aria-selected=true] {
  color: var(--Main-Color);
  border-radius: 15px;
  background-color: var(--Color-6) !important;
}

/*Edit role container*/
.header-JUTO-g {
  background-color: black;
  height: 290px;
  margin-top: 60px;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*"Edit Role" text color*/
.titleText-35PD5k {
  color: var(--Main-Color) !important;
  margin-left: 10px;
}

/*Display, permissions, manage members tab tar margin fix*/
.tabBar-3DfKkN {
  height: 60px;
  margin: 5px !important;
  margin-left: 15px;
  border-bottom: 0px !important;
}
/*Display, permissions, manage members colors and margins fix*/
/*Stable*/
.tabBarItem-3nPo4Z {
  color: var(--Secondary-Color) !important;
  padding-left: 0px;
  padding-right: 0px;
  padding-top: 19px;
  padding-bottom: 0px;
  margin: 0px 20px 0px 20px !important;
}
/*Hover*/
.tabBarItem-3nPo4Z:hover {
  color: var(--Main-Color) !important;
}
/*Selected*/
.tabBarItem-3nPo4Z[aria-selected=true] {
  padding-right: 10px !important;
  margin-right: 10px !important;
}

/*Edit role > Options menu (The 3 dots) color*/
.menu-2p630X {
  color: var(--Main-Color);
}

/*Role icon > Choose image button*/
/*Normal*/
.lookOutlined-3yKVGo.colorWhite-1H92hK {
  color: var(--Main-Color) !important;
  border-color: var(--Main-Color) !important;
  border: 1px var(--Main-Color) solid;
  border-radius: 15px;
}
.lookOutlined-3yKVGo.colorWhite-1H92hK:hover {
  color: var(--Secondary-Color) !important;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Image preview icon color*/
.preview-3SR4Rd {
  color: var(--Main-Color);
}
/*Image preview border*/
.previewContainer-1GxmBJ {
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*View server as role button*/
/*Normal*/
.theme-dark .lookFilled-yCfaCM.colorGrey-2iAG-B {
  color: var(--Main-Color);
  background-color: transparent !important;
  border: var(--border2);
}
/*Hover*/
.theme-dark .lookFilled-yCfaCM.colorGrey-2iAG-B:hover {
  color: var(--Secondary-Color);
  background-color: transparent !important;
  border: var(--border3);
}

/*Manage members list*/
/*Stable*/
.memberRow-1FhJgR {
  background-color: black;
  border-radius: 15px;
  margin-top: 10px;
  margin-bottom: 10px;
  border: 1px var(--Main-Color) solid;
}
/*Hover*/
.memberRow-1FhJgR:hover {
  background-color: black;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Remove member icon color*/
/*Stable*/
.removeButton-JGNeoQ {
  color: var(--Secondary-Color);
}
/*Hover*/
.removeButton-JGNeoQ:hover {
  color: var(--Main-Color);
}
/* #################### Roles tab #################### */
.theme-dark .emojiAliasInput-3ZhdKx .emojiInput-B8MGXq, .theme-dark .emojiAliasInput-3ZhdKx .emojiInput-B8MGXq:hover {
  color: rgba(255, 255, 255, 0) !important;
  background-color: transparent !important;
}

/* #################### Stickers tab #################### */

/*Get boosted card background*/
/*Stable*/
.upsellContainer-22N_CL {
  background: black !important;
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}
/*Hover*/
.upsellContainer-22N_CL:hover {
  background: black !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}

/*Both buttons backgrounds*/
/*normal*/
.lookFilled-yCfaCM.colorWhite-1H92hK {
  background-color: transparent;
  border: 1px solid var(--Main-Color);
}
/*hover*/
.lookFilled-yCfaCM.colorWhite-1H92hK:hover {
  background-color: var(--Third-Color);
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}

/*Level cards (1,2,3)*/
/*border*/
/*Stable*/
.tier-3CS7-p {
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}
/*Hover*/
.tier-3CS7-p:hover {
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}

/*All tiers headers*/
.theme-dark .tierHeaderLocked-30MLlO, .theme-dark .tierHeaderUnlocked-1OpOLf {
  background-color: black !important;
  border-top-left-radius: 15px;
  border-top-right-radius: 15px;
}

/*Buy level buttons*/
/*Stable*/
.lookFilled-yCfaCM.colorGreen-3y-Z79 {
  background-color: transparent !important;
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}
/*Hover*/
.lookFilled-yCfaCM.colorGreen-3y-Z79:hover {
  background-color: transparent !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}

/*Top tier header*/
.theme-dark .tierHeaderLocked-30MLlO {
  background-color: transparent;
}
.tierHeaderWithoutCardBody-1iT8o_ {
  margin-bottom: 0px;
}
/*Middle*/
.grid-5BH14o {
  background-color: black;
  border-bottom-left-radius: 15px;
  border-bottom-right-radius: 15px;
}

/*Second tier body (middle)*/
.theme-dark .tierBody-1d3UiS {
  background-color: black;
  border-bottom-left-radius: 15px;
  border-bottom-right-radius: 15px;
}

/*"Boost server & Learn more" buttons colors*/
/*Stable*/
.lookFilled-yCfaCM.colorWhite-1H92hK {
  background-color: transparent;
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}
/*Hover*/
.lookFilled-yCfaCM.colorWhite-1H92hK:hover {
  background-color: transparent;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}

/*Boosts required to level up text and icon color*/
.tierRequirement-7q3_7-, .tierLock-1eabw6 {
  color: var(--Main-Color);
}

/* #################### Widgets tab #################### */
/*Server id, json api, premade widget borders colors*/
.theme-dark .copyInputDefault-3jiMHw {
  background-color: transparent;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}

/*#################### Server Template tab ####################*/
/*Templates descriptions and what u get, text color*/
.descriptionRow-1UPN0d {
  color: var(--Main-Color);
}

/*#################### Custom invite link tab ####################*/

/*#################### Integrations tab ####################*/
/*Webhooks, channel followed, bots and apps headers colors */
.secondaryHeader-1sJsuH {
  color: var(--Main-Color);
}
/*Icons colors*/
.icon-3TvnqF, .detailsIcon-2NtTO9 {
  color: var(--Main-Color);
}
/*Bots and apps*/
/*Headers text colors*/
.defaultColor-1GKx81 {
  color: var(--Main-Color) !important;
}
/*Banner description*/
.permissionV3BannerDescription-_RTKq- {
  color: var(--Secondary-Color);
}
/*Icons bot colors*/
.featureIcon-3rvFkz {
  color: var(--Secondary-Color);
}

/*#################### Safety setup tab ####################*/

/*#################### Audit log tab ####################*/
/*Filter by user, filter by action padding fix*/
.quickSelect-i8mQq1 {
  padding-right: 50px;
}

/*Audit log containers*/
/*Stable*/
.theme-dark .headerClickable-zGQJz3, .theme-dark .headerDefault-1e6yjj, .header-2pgFQm, .headerClickable-zGQJz3, .headerExpanded-1-zwDr, .auditLog-1NVAY0 {
  background-color: black;
  border-radius: 15px !important;
  border: 1px var(--Main-Color) solid;
}
/*Hover*/
.theme-dark .headerClickable-zGQJz3:hover, .theme-dark .headerDefault-1e6yjj:hover, .header-2pgFQm:hover, .headerClickable-zGQJz3:hover, .headerExpanded-1-zwDr:hover, .auditLog-1NVAY0:hover {
  border-radius: 15px !important;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
/*Audit log action color (header)*/
.overflowEllipsis-BfHznL {
  color: var(--Main-Color);
}
/*What user did, action color*/
.theme-dark .auditLog-1NVAY0 strong {
  color: var(--Third-Color);
}
.changeStr--UjBBu, .overflowEllipsis-BfHznL, .subListItem-3B43Tg {
  color: var(--Main-Color);
}

/*#################### Bans tab ####################*/

/* #################### Community tab #################### */
/*Page layout fix*/
.container-2CHEay {
  min-height: 1550px !important;
}
.banner-3-oqyl {
  height: 356px;
}

/*Server insights text color and icon color*/
.text-dIcRfJ, .icon-2iwvYS {
  color: var(--Main-Color);
}

/*Welcome screen read the rules & read info text color*/
.text-md-semibold-3xVVGu {
  color: var(--Main-Color) !important;
}
/*icon colors*/
.channelTitleIcon-3BTw9v {
  color: var(--Secondary-Color);
}

/*Server name color*/
.welcomeTitle-13oDgb strong {
  color: var(--Main-Color);
}

/* #################### Server boost status tab #################### */
/*Nitro card below*/
.tier2-qNjKTW {
  background-image: none !important;
  background-color: black !important;
}
/*Nitro title, icons colors*/
.tier2Title-8gwAVr, .icon-2iprHa {
  color: var(--Main-Color);
}

/*All percs text color*/
.perkText-3nOGp0, .previousPerks-2h1eyr {
  color: var(--Main-Color);
}

/* #################### Members tab #################### */
/*"Display role" text color*/
.quickSelectLabel-ArUyd9 {
  color: var(--Main-Color);
}
/*"@everyone" text color*/
.quickSelectValue-rmtkbe {
  margin-left: 4px;
  color: var(--Main-Color);
}

/*Members cards*/
/*Stable*/
.member-2cj2PI {
  background-color: black;
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
  margin-bottom: 10px;
  padding-left: 5px;
}
/*Hover*/
.member-2cj2PI:hover {
  background-color: black;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/* #################### Invites tab #################### */
/*Invites card*/
/*Stable*/
.inviteSettingsInviteRow-FAjfDN {
  color: var(--Main-Color);
  background-color: black;
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}
/*Hover*/
.inviteSettingsInviteRow-FAjfDN:hover {
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*Content, margin for user photo*/
.horizontal-112GEH>.flex-2S1XBF:first-child, .horizontal-112GEH>.flexChild-3PzYmX:first-child {
  margin-left: 5px;
}

/* #################### Delete Server #################### */
/*Delete server button color*/
/*Stable*/
.lookFilled-yCfaCM.colorRed-rQXKgM {
  background-color: transparent !important;
  border-radius: 15px;
  border: 1px var(--button-outline-danger-border) solid;
  margin-left: 10px;
}
/*Hover*/
.lookFilled-yCfaCM.colorRed-rQXKgM:hover {
  background-color: transparent !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb2)) !important;
  box-shadow: inset 0px 0px 1px 1px rgb(var(--Neon-Rgb2)), 0px 0px 15px 1px rgb(var(--Neon-Rgb2)) !important;
}

/*#################### App directory tab ####################*/
/*Background*/
.theme-dark .directoryModal-YJsOMv {
  background-color: black;
}

/*Discord logo color*/
.logo-ScFp2k {
  color: var(--Main-Color);
}

/*Category icons colors*/
.icon-3xkfFv {
  color: var(--Main-Color);
}

/*All containers*/
.textContainer-TzRfgH {
  color: var(--Main-Color);
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}

/*After clicking a random app > overview text color*/
.detailedDescription-no5P98 {
  color: var(--Main-Color) !important;
}
/*Show more/less text and icon color*/
.showMoreButtonText-1jnEQf, .showMoreButtonIcon-3D4iRn {
  color: var(--Third-Color);
}

/*Other icon colors*/
.defaultIcon-27uYKL, .listIcon-1_fckz {
  color: var(--Main-Color);
}

/*Command text color*/
.commandName-SDgdgz {
  color: var(--Third-Color) !important;
}

/*Utility tab icons colors*/
.icon-14PytS {
  color: var(--Main-Color) !important;
}

/*Back icon color*/
/*Stable*/
.backHeader-2Yfz4X, .backIcon-3OYRTx {
  color: var(--Secondary-Color);
}
/*Hover*/
.backHeader-2Yfz4X:hover, .backIcon-3OYRTx:hover, .back-1RLxsC:hover {
  color: var(--Main-Color) !important;
}

/*
 $$$$$$\  $$\   $$\ $$$$$$\ $$\       $$$$$$$\   $$$$$$\  
$$  __$$\ $$ |  $$ |\_$$  _|$$ |      $$  __$$\ $$  __$$\ 
$$ /  \__|$$ |  $$ |  $$ |  $$ |      $$ |  $$ |$$ /  \__|
$$ |$$$$\ $$ |  $$ |  $$ |  $$ |      $$ |  $$ |\$$$$$$\  
$$ |\_$$ |$$ |  $$ |  $$ |  $$ |      $$ |  $$ | \____$$\ 
$$ |  $$ |$$ |  $$ |  $$ |  $$ |      $$ |  $$ |$$\   $$ |
\$$$$$$  |\$$$$$$  |$$$$$$\ $$$$$$$$\ $$$$$$$  |\$$$$$$  |
 \______/  \______/ \______|\________|\_______/  \______/ 
*/

/*User popout (update 25.10.2022)*/
/*The master one*/
.userPopoutOuter-3AVBmJ {
  background-color: black;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 1px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 1px rgb(var(--Neon-Rgb)) !important;
}
/*The premium/nonpremium one*/
.userProfileInnerNonPremium-1XjSjn, .userProfileInnerWithBanner-3CJ1Og, .userProfileInnerThemedNonPremium-1gT-zY {
  background: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.6)) , var(--loop-gif2) 50% 50%/cover !important;
}
/*Tag color and name fix*/
.username-28Thtk, .discriminator-3_S3CG {
  color: var(--Main-Color);
}
.discrimBase-KriZSj {
  color: var(--Main-Color);
}

/*Memberlist*/
.member-2gU6Ar {
  background-color: transparent;
}
.member-2gU6Ar:hover {
  border-radius: 15px;
  background-color: var(--Color-5);
}
.member-2gU6Ar[aria-selected=true] {
  border-radius: 15px;
  background-color: var(--Color-6);
}

/*Edit profile (new fix 04/11/2022) icon*/
.pencilIcon-1MUmnO {
  color: var(--Main-Color);
}
/*After clicking the icon, server/profile user settings, the description color*/
.colorDefault-CDqZdO .subtext-2GlkbE {
  color: var(--Secondary-Color);
}

/*Border role color no nitro no themed*/
.rolePill-2IJ1vo {
  color: var(--Secondary-Color);
  border-color: var(--Third-Color);
  border-radius: 15px;
  border: 1.7px solid;
  font-size: 12px;
}
/*Border and role text color nitro themed*/
.rolePillBorder-RiRiuN {
  color: var(--Secondary-Color);
  border-color: var(--Third-Color);
  border-radius: 15px;
}

/*Actions buttons (update 25.10.2022)*/
/*On popout*/
.buttonColor-XIRMbp {
  color: var(--Secondary-Color);
  background-color: transparent;
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}
.buttonColor-XIRMbp:hover {
  color: var(--Main-Color);
  background-color: transparent;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 1px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 1px rgb(var(--Neon-Rgb)) !important;
}
/*When viewing user profile popout actions button color (update 25.10.2022)*/
.actionColor-3JIzOn {
  color: var(--Secondary-Color);
  background-color: transparent;
  border-radius: 15px;
  border: 1px var(--Main-Color) solid;
}
.actionColor-3JIzOn:hover {
  color: var(--Main-Color);
  background-color: transparent;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 1px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 1px rgb(var(--Neon-Rgb)) !important;
}

/*Dropdown arrow color after server name*/
.button-2BMPJJ {
  color: var(--Main-Color);
}

/*Home tab*/
.theme-dark .background-fkKrXt {
  background-color: transparent;
}

/*Server name and info, active now border*/
.container-2Hi7Km, .container-xwOzwi {
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 1px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 1px rgb(var(--Neon-Rgb)) !important;
}

/*Content*/
.container-Jqlbgl {
  background-color: black;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 1px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 1px rgb(var(--Neon-Rgb)) !important;
}

/*Create a guild user popout*/
.container-1Lk8p7 {
  background-color: transparent;
  color: var(--Main-Color);
}
.root-g14mjS {
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
  background-color: black !important;
}
.header-1c1AhF, .content-2hZxGK, .footer-31IekZ {
  background-color: transparent !important;
}
/*Footer separator*/
.theme-light .footerSeparator-VzAYwb {
  box-shadow: none !important;
}
/*Contents, what u want to create*/
/*Stable*/
.container-x8Y1ix {
  background-color: black;
  border: 1px var(--Main-Color) solid;
}
/*Hover*/
.container-x8Y1ix:hover {
  background-color: black;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*"Start from a template" text color*/
.text-xs-bold-1NF1lz, .optionHeader-27AHfD {
  color: var(--Main-Color) !important;
}

/*User popout*/
.userPopout-2j1gM4 {
  background: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.6)) , var(--loop-gif2) 50% 50%/cover !important;
  background-color: black !important;
  border-radius: 15px;
  padding: 5px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
/*Add more roles popout after clicking the +*/
.container-2O1UgZ {
  background: black !important;
  border-radius: 15px !important;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}
/*User Banner*/
.popoutBanner-3cqRD9 {
  border-radius: 5px;
}

/*Server name color*/
.name-3Uvkvr {
  color: var(--Main-Color);
}

/*Guilds unread & mentioned popouts*/
/*Unread*/
.unread-2wipsx {
  background: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.2)) , var(--loop-gif) 50% 50%/cover !important;
  opacity: .9;
  border: solid 2px var(--Secondary-Color);
  border-radius: 15px; 
}
/*Unread pill in chat*/
.unreadPill-3nEWYM {
  color: var(--Main-Color);
  background-color: var(--Color-4);
}
.unreadPillCapStroke-1nE1Q8 {
  color: var(--Color-4) !important;
  fill: var(--Color-4) !important;
}
/*Metioned*/
.mention-3XBnnZ {
  background: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.2)) , var(--loop-gif3) 50% 50%/cover !important;
  opacity: .9;
  border: solid 2px var(--Secondary-Color);
  border-radius: 15px; 
}

/*Guild folders*/
.expandedFolderBackground-1kSAf6 {
  position: absolute;
  top: 0px;
  left: 9.5px;
  bottom: 0px;
  border-radius: 20px;
  background: var(--Black);
  border: solid 2px var(--Secondary-Color);
}
/*Closed guilds folder blur effect*/
.closedFolderIconWrapper-3tRb2d {
  filter: blur(3px);
}
/*Guild info popout when hover (Thanks Disease)*/
.tooltip-14MtrL {
  background: var(--Black) !important;
  border: var(--border1) !important;
  border-radius: 15px;
}

/*Selected guild pill color*/
.item-2LIpTv {
  background-color: var(--Main-Color);
}

/*Guild Roles*/
/*Default permissions*/
.container-_phMUq {
  background-color: transparent;
  color: var(--Main-Color);
  border-radius: 0px;
  padding: 16px 24px 16px 16px;
}
.container-_phMUq:hover {
  background-color: var(--Black-Color);
  color: var(--Main-Color);
  border-radius: 0px;
  padding: 16px 24px 16px 16px;
}
/* Search Roles */
.container-cMG81i {
  border-radius: 4px;
  overflow: hidden;
  background-color: transparent;
}
/*Roles Column Margins*/
.rolesList-3uZoaa {
  margin-bottom: 20px;
}
/*Roles margin left-right*/
.role-2TIOKu {
  margin: 0 4px 4px 0;
  padding: 4px;
  margin-right: 200px;
}
/*Roles card in guilds*/
.userPopout-2j1gM4 {
  border-radius: 8px;
  border-color: var(--Main-Color);
  overflow: hidden;
}
/*+ add roles popout*/
.container-2O1UgZ {
  width: 250px;
  overflow: hidden;
  padding: 8px;
  background-color: var(--Black);
  border: var(--border1);
}

/*Unread message bar "X+ new messages since XX:XXPM/AM" color and background*/
.newMessagesBar-1hF-9G {
  border: 1px solid var(--Main-Color);
  border-bottom-left-radius: 15px;
  border-bottom-right-radius: 15px;
  border-top: transparent;
  background: black !important;
}

/* #################### Server boost tab #################### */
/*background*/
.theme-dark .perksModal-CLcR1c {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.2)) , var(--master-background) 50% 50%/cover !important;
  background-color: transparent;
}

/*Everything below "server boost" text*/
/*gift icon from "gift nitro"*/
.theme-dark .giftIcon-2kmx1K {
  color: var(--Main-Color);
}

/*Server boost icon "no boosts"*/
.theme-dark .badgeIconWithoutSubscribers-1hjTfX {
  color: var(--Main-Color);
}
/*Server boost icon "X boosts"*/
.badgeIconWithSubscribers-2WYJsQ {
  color: var(--Main-Color);
}

/*Progress bar stable*/
.barForeground-2kwBa_ {
  background-color: var(--Main-Color);
}
/*Progress bar when hover on a tier level*/
.barSecondary-VouwoY {
  background-color: var(--Third-Color);
}

/*Tiers*/
.theme-dark .tierMarkerBackground-G8FoN4 {
  background-color: var(--Third-Color);
}

/*"Get cool rewards for becoming a Booster!" the 3 cards below*/
.perks-BtAudq {
  background: transparent;
}
.theme-dark .perk-19D_HN {
  background-color: transparent;
}
/*Text Color*/
.text-sm-medium-3Pz3rB, .text-sm-normal-3Zj3Iv {
  color: var(--Secondary-Color) !important;
}

/*"Ready to boost?" card from below*/
.wrapper-3Zq_cJ {
  background: transparent;
  color: var(--Main-Color);
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}
/*"Learn more about discord nitro button" color and background*/
/*normal*/
.lookInverted-2mDUMi.colorBrand-I6CyqQ {
  color: var(--Secondary-Color);
  background-color: transparent;
  border: 1px solid var(--Main-Color);
  border-radius: 15px;
}
/*hover*/
.lookInverted-2mDUMi.colorBrand-I6CyqQ:hover {
  color: var(--Main-Color);
  background-color: transparent;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*#################### Stream preview ####################*/
.theme-dark .streamPreview-I7itZ6 {
  background-color: transparent;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
/*Body and info*/
.body-2WIpo7 {
  padding: 10px;
  background-color: black;
}
/*Stream Details*/
.theme-dark .activityStreamPreview-uBr6hk .activityName-3YXl6e, .theme-dark .activityStreamPreview-uBr6hk .content-tXPNDw, .theme-dark .activityStreamPreview-uBr6hk .details-2-ciHo, .theme-dark .activityStreamPreview-uBr6hk .name-1-Q7l2, .theme-dark .activityStreamPreview-uBr6hk .nameNormal-2fPMD2 {
  color: var(--Main-Color);
}

/*Nitro, gif, Stickers icons*/
.active-z80xEj .buttonWrapper-3YFQGJ, .buttonWrapper-3YFQGJ:hover {
  color: var(--Main-Color);
}

/*Emoji button color*/
.emojiButton-3FRTuj:not(:hover)>div>.sprite-2lxwfc{
  filter: invert(11%) sepia(98%) saturate(6887%) hue-rotate(284deg) brightness(65%) contrast(111%) !important;
}

/*System messages channel disabled messages*/
.title-2dsDLn {
  color: var(--Main-Color);
  padding-left: 5px;
}

/*Default notification settings, circle buttons*/
.radioIconForeground-2BMavi {
  color: var(--Secondary-Color);
}
/*"All messages", "Only @mentions" text color*/
.title-1yyp9V {
  color: var(--Secondary-Color);
}

/*The video and play on spotify buttons when hovering over a channel fix*/
.button-1Ofqs0 {
  border: 2px var(--Main-Color) solid;
  border-radius: 15px;
}
/*Song name color*/
.headerLink-1hmZgL {
  color: var(--Main-Color);
}
.headerLink-1hmZgL:hover {
  color: var(--Secondary-Color);
}

/*Noise cancelation popout*/
.noiseCancellationPopout-2-e5Xz {
  background-color: black !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}

/*
 $$$$$$\  $$\   $$\  $$$$$$\  $$\   $$\ $$\   $$\ $$$$$$$$\ $$\        $$$$$$\  
$$  __$$\ $$ |  $$ |$$  __$$\ $$$\  $$ |$$$\  $$ |$$  _____|$$ |      $$  __$$\ 
$$ /  \__|$$ |  $$ |$$ /  $$ |$$$$\ $$ |$$$$\ $$ |$$ |      $$ |      $$ /  \__|
$$ |      $$$$$$$$ |$$$$$$$$ |$$ $$\$$ |$$ $$\$$ |$$$$$\    $$ |      \$$$$$$\  
$$ |      $$  __$$ |$$  __$$ |$$ \$$$$ |$$ \$$$$ |$$  __|   $$ |       \____$$\ 
$$ |  $$\ $$ |  $$ |$$ |  $$ |$$ |\$$$ |$$ |\$$$ |$$ |      $$ |      $$\   $$ |
\$$$$$$  |$$ |  $$ |$$ |  $$ |$$ | \$$ |$$ | \$$ |$$$$$$$$\ $$$$$$$$\ \$$$$$$  |
 \______/ \__|  \__|\__|  \__|\__|  \__|\__|  \__|\________|\________| \______/ 
*/
/*Selected channels in guild*/
/*Text color*/
.modeConnected-NrO4cP .name-28HaxV, .modeConnected-NrO4cP:hover .name-28HaxV, .modeSelected-3DmyhH .name-28HaxV, .modeSelected-3DmyhH:hover .name-28HaxV, .modeUnread-3Cxepe .name-28HaxV, .modeUnread-3Cxepe:hover .name-28HaxV, .notInteractive-2tFrlE.modeConnected-NrO4cP .name-28HaxV, .notInteractive-2tFrlE.modeSelected-3DmyhH .name-28HaxV {
  color: var(--Main-Color);
}
/*Icon color*/
.modeSelected-3DmyhH .icon-2W8DHg, .modeSelected-3DmyhH:hover .icon-2W8DHg, .modeUnread-3Cxepe .icon-2W8DHg, .modeUnread-3Cxepe:hover .icon-2W8DHg {
  color: var(--Main-Color);
}

/*Hover on channel color*/
.modeMuted-2T4MDZ:hover .name-28HaxV, .wrapper-NhbLHG:hover .name-28HaxV {
  color: var(--Third-Color);
}

/*Unread Icon Color (The bubble before the channel name)*/
.unreadRelevant-2f-VSK {
    background-color: var(--Main-Color);
}

/*Create Invite & Edit Channel Icons colors*/
.actionIcon-2sw4Sl {
    color: var(--Main-Color);
}

/*More active threads popout of all threads in that channel*/
.popout-TdhJ6Z {
  background-color: black !important;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
/*Hovering on threads list*/
.row-1qtctT:hover {
  border-radius: 15px;
  background-color: var(--Color-5);
}
/*See all button*/
.more-2c3Z-T:hover {
  text-decoration: none !important;
  background-color: var(--Color-5);
  border-radius: 15px;
}
/*Threads name in text channels*/
/*header*/
.name-13vPlv {
  color: var(--Main-Color);
}
/*The small text preview and timestamp color*/
.threadMessageAccessoryPreview-13YRmc, .timestamp-1VMnSc {
  color: var(--Secondary-Color);
}

/*All in channel Icons, Threads, Notifications, Pinned messages, Hide member List, Notes*/
/*Stable*/
.clickable-ZD7xvu .icon-2xnN2Y {
  color: var(--Third-Color);
}
.icon-2xnN2Y {
  color: var(--Third-Color);
}
/*Hover*/
.clickable-ZD7xvu .icon-2xnN2Y:hover {
  color: var(--Secondary-Color);
}
.icon-2xnN2Y {
  color: var(--Secondary-Color);
}
/*Selected*/
.clickable-ZD7xvu .icon-2xnN2Y[aria-selected=true] {
  color: var(--Main-Color);
}
.icon-2xnN2Y[aria-selected=true] {
  color: var(--Main-Color);
}

/*Guild Channel Slow Mode warning*/
.base-3bcbY3 .cooldownWrapper-2k1jHK {
  color: var(--Main-Color)!important;
}

/*Channel topic color*/
.topic-11NuQZ {
  color: var(--Third-Color);
}

/*In guild hover on voice channel popout (playing, listening to spotify)*/
.container-8Futzw {
  background: black !important;
  border-color: rgb(var(--Neon-Rgb));
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb));
}
/*Spotify on*/
.attachButton-1ijpt9:hover path:not(:last-child){
  fill: var(--Main-Color);
}
/*Spotify off*/
.attachButton-1ijpt9:hover path:not(path+path, #a#B){
  fill: var(--Main-Color);
}
/*Channel name color*/
.text-md-bold-22PzaZ, .text-md-semibold-3xVVGu {
  color: var(--Main-Color);
}
/*Channel icon color*/
.channelIcon-3Oew8h {
  color: var(--Main-Color);
}
/*People icon color*/
.peopleIcon-1zv5D6 {
  color: var(--Main-Color);
}
/*Game/software they are streaming*/
.activityVoiceChannel-2vojOH .activityName-3YXl6e, .activityVoiceChannel-2vojOH .name-1-Q7l2, .activityVoiceChannel-2vojOH .nameNormal-2fPMD2, .activityVoiceChannel-2vojOH .nameWrap-3TyM52 {
  color: var(--Main-Color);
}
/*Details*/
.activityVoiceChannel-2vojOH .content-tXPNDw, .activityVoiceChannel-2vojOH .details-2-ciHo, .activityVoiceChannel-2vojOH .playTime-3fSgOm, .activityVoiceChannel-2vojOH .state-2NT76I, .activityVoiceChannel-2vojOH .timestamp-2f1NmH {
  color: var(--Secondary-Color);
}

/*In guild channel, Roles acces*/
.role-23oyrw {
  color: var(--text-normal);
  background-color: transparent;
  border: var(--border2);
  border-radius: 15px;
}

/*Channel icon*/
.emptyChannelIcon-1YdEz2 {
  border-radius: 50%;
  background-color: var(--Color-5);
  background-position: 50%;
  color: var(--Main-Color) !important;
}

/*Channel name "Welcome to [channel_name]"*/
.defaultColor-HXu-5n {
  color: var(--Secondary-Color) !important;
}
/*"This is the start of the [channel_name] channel." text color*/
.description-22d6ux {
  color: var(--Secondary-Color) !important;
}

/*In guilds channel, message options icons colors*/
.wrapper-2vIMkT {
  background-color: transparent;
  border-radius: 15px;
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
  color: var(--Secondary-Color) !important;
}

/*#################### Channel Permissions #########################*/
/*Header category color*/
.lineClamp1-1iDPU7 {
  color: var(--Main-Color) !important;
}

/*########## Permissions ##########*/
/*Private Channel icon color*/
.cardIcon-2nTUq4 {
  color: var(--Main-Color);
}

/*Advanced permissions*/
/*Page layout*/
.sidebarScrollable-2mW9Ls+.content-2ssVKB {
  margin-left: 232px;
  max-width: 2000px;
}

/*Permission name header*/
.horizontal-112GEH>.flex-2S1XBF:first-child, .horizontal-112GEH>.flexChild-3PzYmX:first-child {
  margin-left: 15px;
  margin-top: 5px;
}

/*Buttons colors*/
.passthrough--fbdFR.selected-3jieYB {
  background-color: var(--Third-Color);
  border-radius: 5px;
}
/*Buttons padding*/
.group-LWHoGI {
  margin-top: 5px;
  margin-right: 5px;
}

/*After clicking the + icon, popout*/
.theme-dark .autocompleteArrow-jJE9TQ, .theme-dark .autocompleteShadow-2nfsSy {
  background-color: black; 
  border-color: rgb(var(--Neon-Rgb)) !important;
  box-shadow: inset 0px 0px 5px 1px rgb(var(--Neon-Rgb)), 0px 0px 15px 4px rgb(var(--Neon-Rgb)) !important;
}
/*Header*/
.container-1S70rv .header-3i_Csh {
  background-color: transparent;
}
/*"Add" text color*/
.container-1S70rv .headerText-27z-EV {
  color: var(--Main-Color);
}
/*input text color*/
.theme-dark .container-1S70rv .input-2lpFVz {
  color: var(--Secondary-Color);
}

/*"Roles, Members" headers, sections colors*/
.empty-3J6aBo, .section-3PvCGN {
  color: var(--Main-Color);
}

/*No results text color*/
.empty-3J6aBo p {
  color: var(--Main-Color) !important;
}

/*Rest container*/
.container-1S70rv .sectionTag-28mLyE {
  background-color: transparent;
}

/*NSFW channel alert text color*/
/*Header*/
.title-FyH9jw {
  color: var(--Main-Color) !important;
}
/*Description*/
.description-fPkcPm {
  color: var(--Secondary-Color) !important;
}

/*Browse Channels tab*/
/*background*/
.theme-dark .container-1um7CU {
  background-color: transparent !important;
}
.theme-dark .container-2IKOsH, .theme-dark .header-3xB4vB {
  background-color: transparent !important; 
}
/*headers text*/
.text-xs-bold-1NF1lz, .text-xs-semibold-3E_l31 {
  color: var(--Main-Color) !important;
}
/*follow category text color*/
.text-xs-medium-2LRpEj {
  color: var(--Secondary-Color) !important;
}

/*
 $$$$$$\   $$$$$$\  $$\             $$$$$$$$\ $$\   $$\ $$$$$$\ $$\   $$\  $$$$$$\   $$$$$$\  
$$  __$$\ $$  __$$\ $$ |            \__$$  __|$$ |  $$ |\_$$  _|$$$\  $$ |$$  __$$\ $$  __$$\ 
$$ /  $$ |$$ /  $$ |$$ |               $$ |   $$ |  $$ |  $$ |  $$$$\ $$ |$$ /  \__|$$ /  \__|
$$ |  $$ |$$ |  $$ |$$ |               $$ |   $$$$$$$$ |  $$ |  $$ $$\$$ |$$ |$$$$\ \$$$$$$\  
$$ |  $$ |$$ |  $$ |$$ |               $$ |   $$  __$$ |  $$ |  $$ \$$$$ |$$ |\_$$ | \____$$\ 
$$ $$\$$ |$$ |  $$ |$$ |               $$ |   $$ |  $$ |  $$ |  $$ |\$$$ |$$ |  $$ |$$\   $$ |
\$$$$$$ /  $$$$$$  |$$$$$$$$\          $$ |   $$ |  $$ |$$$$$$\ $$ | \$$ |\$$$$$$  |\$$$$$$  |
 \___$$$\  \______/ \________|         \__|   \__|  \__|\______|\__|  \__| \______/  \______/ 
     \___|
*/
/*Blur spolier text instead of hiding it (by rye.#3861)*/
.spoilerText-27bIiA,
.spoilerText-27bIiA.hidden-3B-Rum {
  background-color: transparent !important;
}
.spoilerText-27bIiA.hidden-3B-Rum > .inlineContent-2YnoDy {
  opacity: 1 !important;
  filter: blur(3px) !important;
  pointer-events: unset;
}

/*Fix for nonsense text flickering*/
html, span:not(.spinner-item) {
  backface-visibility: hidden;
}

/*
$$$$$$$\  $$\       $$\   $$\  $$$$$$\  $$$$$$\ $$\   $$\  $$$$$$\         $$$$$$\  $$\   $$\ $$$$$$$\  $$$$$$$\   $$$$$$\  $$$$$$$\  $$$$$$$$\ 
$$  __$$\ $$ |      $$ |  $$ |$$  __$$\ \_$$  _|$$$\  $$ |$$  __$$\       $$  __$$\ $$ |  $$ |$$  __$$\ $$  __$$\ $$  __$$\ $$  __$$\ \__$$  __|
$$ |  $$ |$$ |      $$ |  $$ |$$ /  \__|  $$ |  $$$$\ $$ |$$ /  \__|      $$ /  \__|$$ |  $$ |$$ |  $$ |$$ |  $$ |$$ /  $$ |$$ |  $$ |   $$ |   
$$$$$$$  |$$ |      $$ |  $$ |$$ |$$$$\   $$ |  $$ $$\$$ |\$$$$$$\        \$$$$$$\  $$ |  $$ |$$$$$$$  |$$$$$$$  |$$ |  $$ |$$$$$$$  |   $$ |   
$$  ____/ $$ |      $$ |  $$ |$$ |\_$$ |  $$ |  $$ \$$$$ | \____$$\        \____$$\ $$ |  $$ |$$  ____/ $$  ____/ $$ |  $$ |$$  __$$<    $$ |   
$$ |      $$ |      $$ |  $$ |$$ |  $$ |  $$ |  $$ |\$$$ |$$\   $$ |      $$\   $$ |$$ |  $$ |$$ |      $$ |      $$ |  $$ |$$ |  $$ |   $$ |   
$$ |      $$$$$$$$\ \$$$$$$  |\$$$$$$  |$$$$$$\ $$ | \$$ |\$$$$$$  |      \$$$$$$  |\$$$$$$  |$$ |      $$ |       $$$$$$  |$$ |  $$ |   $$ |   
\__|      \________| \______/  \______/ \______|\__|  \__| \______/        \______/  \______/ \__|      \__|       \______/ \__|  \__|   \__|   
*/
/*#################### Image Utilities (DevilBro) ####################*/
/*Image details text color */
.imageDetails-1t6Zms > span {
  color: var(--Main-Color);
}

/*Download image icon color*/
.cursorPointer-B3uwDA {
  color: var(--Main-Color);
}
