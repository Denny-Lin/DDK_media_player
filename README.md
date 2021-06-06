# DDK_media_player
* It is an idea.
* It will be light with no advertisements.
<br><br/>

## Features
* It only play videos.
* No more ads.
* Lightweight.
* Fast.
<br><br/>

## Platforms
* windows
<br><br/>

## Languages
* C, C++, C#
<br><br/>

## All the thinking is following bellow
* This project will be progressed someday.
```c
MCIERROR mciSendString(
      LPCTSTR lpszCommand,
      LPTSTR  lpszReturnString,
      UINT    cchReturn,
      HANDLE  hwndCallback
);
```

* Example:
```c
mciSendString("play home.mp3", NULL, 0, NULL);
mciSendString("stop home.mp3", NULL, 0, NULL);
mciSendString("close home.mp3", NULL, 0, NULL);
mciSendString("open home.wav", NULL, 0, NULL);
mciSendString("play home.wav", NULL, 0, NULL);
```
<br><br/>

## References
* https://docs.microsoft.com/en-us/previous-versions/dd757161(v=vs.85)
* https://www.write-bug.com/article/1570.html

