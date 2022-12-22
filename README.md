# food-segmentation

## 食物標註

### 資料位置
- 要標記的資料請從[google drive下載](https://drive.google.com/file/d/1F51Gu2Yg9IvjCx268Dv5nkNkHQDZMwal/view?usp=share_link)

![](https://i.imgur.com/iw8P9Op.png)

- 各組資料已分配好，請根據自己的組別找到要標記的檔案
- `img`資料夾放要標記的影像
- 請將標記檔存放在`ann`資料夾中
- `label.xlsx`為各食物的label名稱
    - `school_id`對應到資料夾名稱
    - `B`欄中文菜色名稱對應`F`欄英文菜色名稱，其他欄位依此類推

![](https://i.imgur.com/HxrQw0V.png)

---

### 標記程式
- 請使用[labelme](https://github.com/wkentaro/labelme)進行標記
- 詳細操作可參考moodle上[Food Instance Segmentation.pdf](resources\Food&#32Instance&#32Segmentaion.pdf) p.7 ~ p.13

![pdf file](https://i.imgur.com/OcE92z9_d.webp?maxwidth=1520&fidelity=grand)

- 請使用`Polygons`進行標記，可點選左側工具列或滑鼠右鍵選擇`Create Polygons`

![](https://i.imgur.com/Nxu2wvL.png)

--- 

### 標記說明
- 請將圖片放大至一定程度後再進行標記
- 標記食物輪廓，並依照食物<span style="color: red">**英文名稱**</span>進行label
- 若餐盤裡沒有菜色，可跳過
- 菜色份量過少，可跳過
- 骨頭可不標
- 相同菜色若距離太遠，可將其分為兩份

--- 

### 繳交格式
- <span style="color: red">**繳交期限為2022-12-28 00:00:00前**</span>

1. 在助教提供的資料中，找到自己組被分配到的資料夾
2. 在同一層資料夾下，有一個資料夾`ann`，請將標記檔存放在裡面
![dir structure](https://i.imgur.com/BMRLI2q.png)
3. 標記完畢後，請將**整個**助教提供的資料夾(包含`img`資料夾以及`ann`資料夾)壓縮(.zip)，檔案命名格是為`team_{組別}.zip`，如`team_1.zip`
4. 檔案請上傳至雲端資料夾：https://drive.google.com/drive/folders/1VDpgccJ18IsmQiLKCG1n-kUf4oivZFu6?usp=sharing

---

若有任何問題，可在群組發問，或email助教：n26094265@gs.ncku.edu.tw