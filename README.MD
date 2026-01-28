Install Zrok client with ease
以最簡單方式設定 Zrok 用戶端

For starters, download zrok at https://docs.zrok.io/docs/guides/install/windows/

第一步，到 https://docs.zrok.io/docs/guides/install/windows/ 下載 Zrok


Extract the file, enter the folder and then extract the file in there

解壓縮檔案後，在進入解出來的資料夾並解壓縮裡面的檔案


Copy the zrok.exe and go to the drive you want to put the file in (probably Disk C)

拷貝 zrok.exe 並進入要安裝的硬碟（很有可能是Ｃ槽）


Create (or open) a folder named "bin" and paste the zrok.exe into it

新增（或打開）一個名為「 bin 」的資料夾並貼上 zrok.exe

Right click the file, choose properties and copy the loaction of the folder

右鍵點擊檔案，選擇內容並複製資料夾位置

Type env in the windows search bar and choose "Edit the system environment variables"

在 windows 搜尋欄中打入 env 並選擇「編輯系統環境變數」

Select "environment variables..." at the bottom

選擇下方的「環境變數」

Click "path", "edit", "new" and paste the location then hit "Ok" 3 times

點擊「path」，「編輯」，「新增」並貼上檔案位置接著點擊「確定」3次

Type pow in the windows search bar and choose "Windows Powershell"

在 windows 搜尋欄中打入 pow 並選擇「Windows Powershell」

Type in "zrok version" to verify that it exists

輸入「zrok version」來確認安裝

Sign in or sign up at https://myzrok.io/dashboard

Please note: you will set up two accounts with the same email, giving them the same password will make life so much easier

在 https://myzrok.io/dashboard 中登入或註冊帳號

請注意：你將要設定兩個以同電子郵件為名的帳號，給予他們相同的密碼將會讓人生好過很多

After finishing signing in/up, head to https://api-v1.zrok.io, log in and click on your email address, copy the account token

註冊或登入完成後，於 https://api-v1.zrok.io 登入，點選你的電子郵件並複製 account token

Head back to powershell and type in "zrok enable" and paste in the token (be sure to leave a blank between "enable" and the token!)

回到 powershell 並輸入「 zrok enable 」並貼上 account token（記得在 enable 跟 token 間留下一個空格！）

You're all set! wait for the one at the server side for further instructions!
你完成了！等待伺服器端的那位給予下一步指示吧！
