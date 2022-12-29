# food-segmentation

## 食物分割

- 偵測食物在影像中的區域，並進行分類
- 類別共分為4類
    - staple food (主食)
    - main course (主菜)
    - side dish (副菜)
    - vegetable (蔬菜)

### 資料集位置
> https://drive.google.com/file/d/18jlv_DHYlUQpFUzBrC1er0B5km8DXneK/view?usp=share_link

### 訓練範例程式
> https://colab.research.google.com/drive/1RcWhgL5Ag2lLmpqEg7jotZ3r4Y-RhreL?usp=share_link

### 繳交內容
1. 程式碼
2. 模型權重檔
3. [報告](#報告內容)
4. 測試集在訓練後的模型預測之結果 ([COCO AP](https://cocodataset.org/#detection-eval))
![](https://i.imgur.com/ipOv9w4.png)

可使用`pycocotools`套件產生測試結果，範例code連結：https://gist.github.com/huang0819/3f6bf5b8d0f0ad5c8954c9d0ce559f02

### 模型訓練
- 若使用助教提供的訓練範例程式訓練模型(Mask R-CNN)，分數會斟酌扣分
- 使用其他模型，分數會比較高
- 在模型訓練時，**請勿使用測試資料集**

### 報告內容
繳交的報告，需含以下內容：
1. 介紹使用的模型
2. 如何訓練模型
3. 訓練相關的結果
4. 組員分工情形

### 檔案繳交位置
- 請將[繳交內容](#繳交內容)中，四個項目壓縮，並將壓縮檔命名為`{組別}.zip`
- 繳交位置：https://drive.google.com/drive/folders/1EmOdL6adfh9QuG-yFxOBTlv4dE7koKGP?usp=share_link

---

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
- 詳細操作可參考moodle上[Food Instance Segmentation.pdf](./resources/Food%20Instance%20Segmentaion.pdf) p.7 ~ p.13

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
