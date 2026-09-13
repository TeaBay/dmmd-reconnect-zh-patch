# DRAMAtical Murder（戲劇性謀殺） 續作 re:connect 繁體中文化 patch

DRAMAtical Murder（戲劇性謀殺） 續作 re:connect（DLsite VJ014718「普及版」）
的非官方繁體中文化 patch。DMMd re:connect 漢化／中文化。
個人製作（[TeaBay](https://github.com/TeaBay)），與 Nitroplus / Nitro+CHiRAL 無關，未經授權或認可。

譯文以機器翻譯為底、再人工校對，仍會有誤譯與不通順的地方，請多多見諒。

本 repo 與發佈的 patch 都不含任何遊戲原始檔案或日文原文。中文版是在使用者
自己的電腦上、由使用者自己那份遊戲檔重建出來的。

<details>
<summary>擷圖</summary>
<img width="1026" height="608" alt="image" src="https://github.com/user-attachments/assets/36d35900-3d91-466d-9578-17a1bd6b1ac6" />
<img width="1026" height="608" alt="image" src="https://github.com/user-attachments/assets/04485793-3675-43f8-ad5f-b41c1b3846e1" />
<img width="1026" height="608" alt="image" src="https://github.com/user-attachments/assets/99684610-e56b-4bd4-ae84-e52d6ca12146" />
<img width="1026" height="608" alt="image" src="https://github.com/user-attachments/assets/54c5d7a6-cd81-41d1-a744-90e8a6802e5c" />
</details>

## 使用條件

本 patch 僅供**已合法購買** DLsite VJ014718「re:connect 普及版」的使用者使用。

patch 不含任何遊戲原始檔案，也**不解除任何複製保護、不繞過購買驗證**；中文版是在
你自己的電腦上、由你自己那份遊戲檔重建出來的。NPA 封裝格式的處理方式參考公開文件
（[GARbro](https://github.com/morkt/GARbro)，MIT）。

## 致權利人

若 Nitroplus / Nitro+CHiRAL 或其代理人認為本專案不妥，請開 GitHub Issue 或聯絡
[TeaBay](https://github.com/TeaBay)，我會立即下架，不會爭辯。

## 下載

[Releases](../../releases) 的 `dmmd-zh-vX.Y.Z.zip`。

**使用風險自負，安裝前請自行備份整個遊戲資料夾。**

安裝：解壓縮 → 關閉遊戲 → 雙擊 `INSTALL.bat` → 對 `DMMdRCZH6.otf` 按右鍵「安裝」。
`INSTALL.bat` 寫入失敗就改用右鍵「以系統管理員身分執行」。
第 4 步不能省，否則遊戲會顯示成方塊。還原用 `UNINSTALL.bat`。

## zip 內容

```
dmmdpatch.exe  patcher
nss.patch      對白／選單的差分（不含原文，套用時由你的 nss.npa 重建）
cg.patch       重畫過的選單圖（不含原廠圖的原始位元組）
DMMdRCZH6.otf  字型
src/           patcher 完整原始碼 ＋ BUILD.txt（編譯與雜湊核對方式）
README         使用說明，內附 exe 的 sha256
LICENSES       授權全文
```

## 自行編譯核對

執行檔可重現編譯：用 zip 內 `src/` 的原始碼，照 `src/BUILD.txt` 編一次，
sha256 應與 `README` 公布的值相同。
