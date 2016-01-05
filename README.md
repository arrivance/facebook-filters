# facebook filters
various filters to block certain aspects of facebook and facebook messenger, using your favourite adblocker

## instructions
install these scripts using any adblock plus compatible blocker as it uses adblock plus syntax
tested using uBlock origin on Chrome, Windows 10

#### scripts in facebook-filters/ are only for facebook.com
#### scripts in messenger-filters/ are only for messenger.com
#### scripts in root are for both

### block_online.txt ([install](abp:subscribe?location=https://raw.githubusercontent.com/arrivance/facebook-filters/master/block_online.txt&title=Facebook Filter: Block Online))
this prevents you from appearing online when using http://messenger.com and http://facebook.com

### block_seen_and_type.txt ([install](abp:subscribe?location=https://raw.githubusercontent.com/arrivance/facebook-filters/master/block_seen_and_type.txt&title=Facebook Filter: Block Seen and Type))
this prevents messages from being marked as read when you read them on http://facebook.com, and http://messenger.com. it also prevents the typing notification

(essentially serves the exact same purpose as [unseen](https://chrome.google.com/webstore/detail/unseen/oclokcfejikeggpnhgakanfbdnlafaon?hl=en), but without any of the ad crap)

### facebook-filters/chat_block.txt ([install](abp:subscribe?location=https://raw.githubusercontent.com/arrivance/facebook-filters/master/facebook-filters/chat_block.txt&title=Facebook Filter: Facebook Block Chat))
blocks facebook chat on http://facebook.com. this also causes you to appear offline

### facebook-filters/pubcontent_block.txt ([install](abp:subscribe?location=https://raw.githubusercontent.com/arrivance/facebook-filters/master/facebook-filters/pubcontent_block.txt&title=Facebook Filter: Facebook Block Pubcontent))
blocks pubcontent (e.g trending, or suggested groups) from appearing in the sidebar on http://facebook.com

### license
licensed under GNU General Public License v3.0
