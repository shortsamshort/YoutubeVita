# YouTubeVita
*An attempt at making a decent YouTube client for PS Vita*


- [ ] Create YouTube Backend
- [ ] Create UX
- [ ] Refactor/QA
---
## YouTube Backend
So I was thinking for the backend to reference the Lua scripts in VLC's own playlist parsers. This is tested and upkept by the VLC team making updates to the script easier. I have also looked at the formatting for Noboru's multiple manga site parsers. I think I may have to focus on that format to make the application very updateable and modular. This is the VLC parser project I am currently looking at: https://github.com/videolan/vlc/blob/master/share/lua/playlist/README.txt and also Noboru's manga parser setup: https://github.com/Creckeryop/NOBORU-parsers

## User Experience
For this I have viewed various applications in the homebrew app store, the current official YouTube application for consoles and TVs, and also various mobile applications. I like Noboru's side bar style for the Vita, but I don't know if the scrolling list is good or if I should use the side-scrolling style the TV application uses. This is Noboru's repository for reference: https://github.com/Creckeryop/NOBORU

## Refactor and QA
As I am not a developer by trade there will be a LOT of refactoring and adjustments. I apologize in advance for this and if there are any tips or tricks that you have I am open to input. I am someone who learns from getting their hands dirty and making mistakes. I would love for someone to assist with QA and testing.

## Technologies Used
I plan on using as much Lua as possible, with some JS and C where needed. The lpp-vita project should fit this nicely: https://github.com/Rinnegatamante/lpp-vita as well as vitasdk: https://github.com/vitasdk and/or vitaGL: https://github.com/Rinnegatamante/vitaGL
