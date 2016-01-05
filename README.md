# facebook filters
various filters to block certain aspects of facebook and facebook messenger, using your favourite adblocker

## instructions
install these scripts using any adblock plus compatible blocker as it uses adblock plus syntax
tested using uBlock origin on Chrome, Windows 10

#### scripts in facebook-filters/ are only for facebook.com
#### scripts in messenger-filters/ are only for messenger.com
#### scripts in root are for both

### block_online.txt
this blocks you from appearing online when using http://messenger.com and http://facebook.com

### block_seen_and_type.txt
this prevents messages from being marked as read when you read them on http://facebook.com, and http://messenger.com. it also prevents the typing notification

(essentially serves the exact same purpose as [unseen](https://chrome.google.com/webstore/detail/unseen/oclokcfejikeggpnhgakanfbdnlafaon?hl=en), but without any of the ad crap)

### facebook-filters/chat_block.txt
blocks facebook chat on http://facebook.com. this also causes you to appear offline

### facebook-filters/pubcontent_block.txt
blocks pubcontent (e.g trending, or suggested groups) from appearing in the sidebar on http://facebook.com

### license
licensed under GNU General Public License v3.0
