# MYUI
One Game Launcher custom UI themes.

https://youtu.be/66sB1ZgfTtg

One Game Launcher - MYUI: https://ogl.app/myui

One Game Launcher home page: https://ogl.app

One Game Launcher reddit: https://www.reddit.com/r/OneGameLauncher

# API:

Get all games: http://localhost:8080/GetAllGames

Request game launch: http://localhost:8080/LaunchGame?Id=<game.Id>&Store=<game.Store>

Close application window: window.chrome.webview.postMessage({ action: 'close' });

Minimiza application window: window.chrome.webview.postMessage({ action: 'minimize' });

Close/Minimize app according to Settings: window.chrome.webview.postMessage({ action: 'closeOrMinimizeAppWindowAfterGameLaunch' });
