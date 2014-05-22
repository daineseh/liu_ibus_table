liu_ibus_table
==============

使用方法: (適用於任何版本 Ubuntu/Debian )

1. 先使用aptitude(或 apt-get )指令安裝 ibus-table 套件
        sudo aptitude install ibus-table

2. 確定已 cd 到檔案所在的資料夾底下，在terminal輸入以下指令
        sudo ibus-table-createdb -s liu_ibus_table.txt -n liu.db

3. 把剛剛產生出來的 .db檔以及資料夾裡原有的icon複製到ibus-table資料夾底下
        sudo cp liu.db /usr/share/ibus-table/tables/
        sudo cp liu.png /usr/share/ibus-table/icons/

4. 請登出系統，重新登入，才能使剛才的修改生效。

5. 登入後修改ibus偏好設定。
   輸入法 -> 選取輸入法 -> 漢語 -> 嘸蝦米
   -> 按下旁邊加入按鈕 -> 再關閉視窗即可
