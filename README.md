# HaveFun交友媒合平台
<img src="https://github.com/ANATANI/HaveFunWebsite/blob/main/IMG_0134.jpg" height="450px" width="300px">
此為截取 組員-黃滙勻 於<a href="https://havefun.azurewebsites.net/">HaveFun交友媒合平台</a> 負責之內容：網站首頁、個人活動管理、個人貼文部分功能<br><br>
完整團體開發內容在：<a href="https://github.com/Turner-Chang/HaveFun.git">HaveFun-GitHub</a><br><br>

### 首頁
**前端頁面**：`HaveFun/Views/Home/Index.cshtml`<br>
**後端WebApi**:`HaveFun/Controllers/APIs/HomeController.cs`<br>
**功能介紹**：<br>
- 展示後台系統設定的公告
- 展示網站當前最熱門的活動<br>
**使用技術**：<br>
- 前端：HTML/CSS、Vue框架搭配Razor語法
- 後端：使用ASP .NET CORE MVC開發WebApi實現數據呈現<br><br>

### 個人活動管理
**前端頁面**：`HaveFun/Views/Profile/_ActivitysManagement.cshtml`<br>
**後端WebApi**:`HaveFun/Controllers/APIs/PersonalActivitytiesController.cs`<br>
**功能介紹**：<br>
- 依「即將發生的活動」、「會員自己主辦的活動」、「過去的活動」檢視會員參加的活動
- 取消報名已經參加的活動
- 修改主辦活動內容
- 刪除主辦的活動<br>
**使用技術**：<br>
- 前端：HTML/CSS、Vue框架搭配Razor語法、串接Google Maps API顯示地圖與自動完成地址
- 後端：使用ASP .NET CORE MVC開發WebApi實現數據呈現與操作資料庫刪除和修改<br><br>

### 個人貼文部分功能
**前端頁面**：`HaveFun/Views/Post/Index.cshtml`<br>
**後端WebApi**:`HaveFun/Controllers/APIs/PostsApiController.cs`<br><br>
**功能介紹**：<br>
- 顯示貼文
- 貼文上傳圖片與預覽
- 刪除自己的發文
- 檢舉別人的貼文
- 按/取消Like貼文<br>
**使用技術**：<br>
- 前端：HTML/CSS、Vue框架搭配Razor語法
- 後端：使用ASP .NET CORE MVC開發WebApi實現數據呈現與操作資料庫刪除和修改<br><br>
