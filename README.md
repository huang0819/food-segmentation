# food-segmentation

## Label
- You can reffer to [dishes.csv](./dishes.csv).
- Use `school_id` and `ch_name` as primary key to find `en_name`

| **school_id** | **ch_name** | **en_name**                                   | **dish_type** |
|:-------------:|:-----------:|:---------------------------------------------:|:-------------:|
| 14            | 燕麥飯         | oat rice                                      | 1             |
| 14            | 三杯雞         | three cup chicken                             | 2             |
| 14            | 雙蘿滷麵輪       | radish with bean wheel                        | 3             |
| 14            | 蒜香高麗菜       | cabbage                                       | 4             |
| 14            | 胚芽米飯        | germ rice                                     | 1             |
| 14            | 橙汁燒鴨        | roast duck                                    | 2             |
| 14            | 田園鮮蔬        | garden veggie                                 | 3             |
| 14            | 蒜香菠菜        | spinach                                       | 4             |
| 14            | 蕃茄蛋炒飯       | tomato egg fried rice                         | 1             |
| 14            | 鮮菇燒豆腐       | tofu with mushroom                            | 2             |
| 14            | 五穀飯         | five-grain rice                               | 1             |
| 14            | 椰汁咖哩雞       | coconut curry chicken                         | 2             |
| 14            | 彩椒百頁        | tofu with bell pepper                         | 3             |
| 14            | 枸杞有機油菜      | rape with wolfberry                           | 4             |
| 14            | 糙米飯         | brown rice                                    | 1             |
| 14            | 海結筍干腱肉      | shank with bamboo shoots and kelp knot        | 2             |
| 14            | 珊瑚蛋         | carrot with scrambled eggs                    | 3             |
| 14            | 鮮菇有機青江      | bok choy with mushroom                        | 4             |
| 15            | 小米飯         | millet rice                                   | 1             |
| 15            | 瓜子肉燥        | steamed minced pork                           | 2             |
| 15            | 高麗菜炒蛋       | scrambled eggs with cabbage                   | 3             |
| 15            | 金針菇炒油菜      | rape with enoki mushroom                      | 4             |
| 15            | 麻油雞         | sesame oil chicken                            | 2             |
| 15            | 珍珠丸子        | rice meat ball                                | 3             |
| 15            | 有機蚵白菜       | oyster cabbage                                | 4             |
| 15            | 雜糧粥         | multigrain porridge                           | 1             |
| 15            | 魚片五穀粥料      | fillet five-grain porridge material           | 2             |
| 15            | 鴿蛋滷油腐       | braised tofu with pigeon eggs                 | 3             |
| 15            | 珍花炒大白       | chinese cabbage                               | 4             |
| 15            | 糙米飯         | brown rice                                    | 1             |
| 15            | 黃金豬排        | pork chop                                     | 2             |
| 15            | 豆薯炒蛋        | yam bean with scrambled eggs                  | 3             |
| 15            | 有機荷葉白菜      | chinese cabbage                               | 4             |
| 15            | 鹹水雞         | saltwater chicken                             | 2             |
| 15            | 珍味粉絲        | cellophane noodles                            | 3             |
| 15            | 雙色花菜        | broccoli and cauliflower                      | 4             |
| 16            | 糙米飯         | brown rice                                    | 1             |
| 16            | 馬鈴薯燜肉       | pork stew with potato                         | 2             |
| 16            | 菇炒黃瓜        | fried cucumber with mushroom                  | 3             |
| 16            | 金針菠菜        | spinach with enoki mushroom                   | 4             |
| 16            | 燕麥飯         | oat rice                                      | 1             |
| 16            | 蔥爆雞         | sauted chicken with green onion               | 2             |
| 16            | 開陽瓠瓜        | calabash gourd                                | 3             |
| 16            | 有機蔬菜        | vegetable                                     | 4             |
| 16            | 白飯          | rice                                          | 1             |
| 16            | 洋蔥豬肉蓋飯料     | pork and onion donburi material               | 2             |
| 16            | 叉燒包         | barbecued pork bun                            | 3             |
| 16            | 鹹水蔬菜        | vegetable                                     | 4             |
| 16            | 虱目魚肉燥       | milkfish braised pork                         | 2             |
| 16            | 干貝絲瓜        | loofah with scallops                          | 3             |
| 16            | 櫻蝦高麗菜       | cabbage with sakura shrimp                    | 4             |
| 16            | 十穀飯         | ten-grain rice                                | 1             |
| 16            | 橙汁排骨        | pork ribs                                     | 2             |
| 16            | 炒什錦         | fried assorted                                | 3             |
| 18            | 白米飯         | rice                                          | 1             |
| 18            | 家常滷肉        | braised pork belly                            | 2             |
| 18            | 芹菜甜不辣       | tempura with celery                           | 3             |
| 18            | 蒜香高麗菜       | cabbage                                       | 4             |
| 18            | 糙米飯         | brown rice                                    | 1             |
| 18            | 香菇雞         | mushroom chicken                              | 2             |
| 18            | 海帶菜滑蛋       | slippery egg with kelp                        | 3             |
| 18            | 有機蔬菜        | vegetable                                     | 4             |
| 18            | 烏龍麵         | udon noodles                                  | 1             |
| 18            | 日式咖哩烏龍麵     | curry udon noodles                            | 2             |
| 18            | 茄汁蛋包        | tomato sauce omelet rice                      | 3             |
| 18            | 薑絲炒尼龍       | ni long cabbage                               | 4             |
| 18            | 燕麥飯         | oat rice                                      | 1             |
| 18            | 紅燒豆腐        | braised tofu                                  | 2             |
| 18            | 珊瑚蛋         | carrot with scrambled eggs                    | 3             |
| 18            | 金菇絲瓜        | loofah with enoki mushroom                    | 4             |
| 18            | 紅藜飯         | red quinoa rice                               | 1             |
| 18            | 雞肉親子丼       | chicken donburi                               | 2             |
| 18            | 豬肉餡餅        | pork pie                                      | 3             |
| 8             | 地瓜飯         | sweet potato rice                             | 1             |
| 8             | 糖醋雞丁        | sweet and sour chicken                        | 2             |
| 8             | 韓式泡菜燒肉      | kimchi roast pork                             | 3             |
| 8             | 油蔥地瓜葉       | fried garlic sweet potato leaves              | 4             |
| 8             | 糙米飯         | brown rice                                    | 1             |
| 8             | 雞肉飯         | chicken rice                                  | 2             |
| 8             | 筍乾油腐        | braised tofu with bamboo shoots               | 3             |
| 8             | 白菜滷         | chinese cabbage stew                          | 4             |
| 8             | 馬鈴薯燒肉       | roast pork with potato                        | 2             |
| 8             | 結頭燴鮮菇       | kohlrabi with mushroom                        | 3             |
| 8             | 快炒高麗菜       | cabbage                                       | 4             |
| 8             | 白米飯         | rice                                          | 1             |
| 8             | 嫩薑肉片        | sliced ​​meat with ginger                     | 2             |
| 8             | 豆瓣冬粉        | bean noodles with bean paste                  | 3             |
| 8             | 炒鵝白菜        | bok choy                                      | 4             |
| 8             | 甜醬滷鴨        | braised duck                                  | 2             |
| 8             | 白菜肉羹        | chinese cabbage in pork thick soup            | 3             |
| 8             | 蒜香菠菜        | spinach                                       | 4             |
| 9             | 胚芽米飯        | germ rice                                     | 1             |
| 9             | 香酥肉魚        | crispy fried fish                             | 2             |
| 9             | 刺瓜炒肉片       | sliced ​​meat with cucumber                   | 3             |
| 9             | 炒高麗菜        | cabbage                                       | 4             |
| 9             | 義大利麵        | pasta                                         | 1             |
| 9             | 雞丁義大利麵      | diced chicken pasta                           | 2             |
| 9             | 砂鍋豆腐煲       | tofu with clay pot                            | 3             |
| 9             | 炒青江菜        | pak choy                                      | 4             |
| 9             | 糙米飯         | brown rice                                    | 1             |
| 9             | 筍乾肉丁        | diced meat with bamboo shoots                 | 2             |
| 9             | 紅蘿蔔炒蛋       | carrot scrambled eggs                         | 3             |
| 9             | 炒有機小松菜      | komutsuna                                     | 4             |
| 9             | 白米飯         | rice                                          | 1             |
| 9             | 三杯雞丁        | three cup chicken                             | 2             |
| 9             | 香菇冬瓜滷       | mushroom and wax gourd stew                   | 3             |
| 9             | 炒油菜         | rape                                          | 4             |
| 9             | 梅醬雞         | chicken with plum sauce                       | 2             |
| 9             | 芙蓉蒸蛋        | steamed egg                                   | 3             |
| 10            | 胚芽飯         | germ rice                                     | 1             |
| 10            | 豆輪滷肉        | braised pork belly with bean wheel            | 2             |
| 10            | 螞蟻上樹        | sauteed vermicelli with minced pork           | 3             |
| 10            | 沙茶油菜        | rape                                          | 4             |
| 10            | 白米飯         | rice                                          | 1             |
| 10            | 肉絲蛋炒飯       | shredded pork egg fried rice                  | 2             |
| 10            | 五香豆干        | spiced dried bean curd                        | 3             |
| 10            | 炒高麗菜        | cabbage                                       | 4             |
| 10            | 五穀飯         | five-grain rice                               | 1             |
| 10            | 蜜汁雞丁        | chicken breast with honey                     | 2             |
| 10            | 四色炒蛋        | scrambled egg                                 | 3             |
| 10            | 炒菠菜         | spinach                                       | 4             |
| 10            | 粉蒸肉         | steamed pork slices with glutinous rice flour | 2             |
| 10            | 壽喜豆腐        | sukiyaki tofu                                 | 3             |
| 10            | 蒜炒油麥菜       | indian lettuce                                | 4             |
| 10            | 黑胡椒豬柳       | black pepper pork tenderloin                  | 2             |
| 10            | 紅籮蔔炒蛋       | carrot scrambled eggs                         | 3             |
| 10            | 炒油菜         | rape                                          | 4             |
| 19            | 藜麥飯         | quinoa rice                                   | 1             |
| 19            | 宮保雞丁        | kung pao chicken                              | 2             |
| 19            | 刺瓜燴魚丸       | fish ball with cucumber                       | 3             |
| 19            | 炒高麗菜        | cabbage                                       | 4             |
| 19            | 麵食          | noodles                                       | 1             |
| 19            | 義大利肉醬麵      | pasta                                         | 2             |
| 19            | 香酥小雞塊       | chicken nuggets                               | 3             |
| 19            | 炒蚵白菜        | oyster cabbage                                | 4             |
| 19            | 胚芽飯         | germ rice                                     | 1             |
| 19            | 瓜仔肉         | steamed minced pork                           | 2             |
| 19            | 銀芽雞絲        | bean sprouts with chicken                     | 3             |
| 19            | 炒菠菜         | spinach                                       | 4             |
| 19            | 小米燕麥紫米飯     | black rice                                    | 1             |
| 19            | 蔭鳳梨蒸魚       | fermented pineapple steamed fish              | 2             |
| 19            | 紅蘿蔔炒蛋       | carrot scrambled eggs                         | 3             |
| 19            | 炒油菜         | rape                                          | 4             |
| 19            | 地瓜飯         | sweet potato rice                             | 1             |
| 19            | 馬鈴薯燉肉       | pork stew with potato                         | 2             |
| 19            | 麻婆豆腐        | mapo tofu                                     | 3             |
| 4             | 胚芽米飯        | germ rice                                     | 1             |
| 4             | 滷肉燥(豆干)     | braised pork belly with dried bean curd       | 2             |
| 4             | 培根蛋香蘿蔔      | radish with bacon eggs                        | 3             |
| 4             | 枸杞菠菜        | spinach with wolfberry                        | 4             |
| 4             | 糙米飯         | brown rice                                    | 1             |
| 4             | 蔬菜咖哩燴飯配料    | vegetable curry material                      | 2             |
| 4             | 蛋香小黃瓜       | cucumber with egg                             | 3             |
| 4             | 香鬆飯         | furikake rice                                 | 1             |
| 4             | 香蔥番茄燉雞      | scallion tomato stewed chicken                | 2             |
| 4             | 香菇熬白菜       | chinese cabbage stew with mushroom            | 3             |
| 4             | 香菇油菜        | rape with mushroom                            | 4             |
| 4             | 刈包          | gua bao                                       | 1             |
| 4             | 酸菜肉絲(刈包)    | shredded pork with sauerkraut                 | 2             |
| 4             | 花生粉糖        | peanut powder                                 | 3             |
| 4             | 蒜香高麗菜       | cabbage                                       | 4             |
| 4             | 小米飯         | millet rice                                   | 1             |
| 4             | 三杯魚丁豆腐      | three cup diced fish and tofu                 | 2             |
| 4             | 家常炒年糕       | fried rice cake                               | 3             |
| 4             | 蒜香菠菜        | spinach                                       | 4             |
| 5             | 白米飯         | rice                                          | 1             |
| 5             | 親子丼         | chicken donburi                               | 2             |
| 5             | 涼拌海帶絲       | kelp salad                                    | 3             |
| 5             | 蒜香芥藍菜       | kale                                          | 4             |
| 5             | 咖哩炒飯        | curry fried rice                              | 1             |
| 5             | 紅燒獅子頭       | braised pork ball in brown sauce              | 2             |
| 5             | 炒青江菜        | pak choy                                      | 3             |
| 5             | 糙米飯         | brown rice                                    | 1             |
| 5             | 冬瓜排骨        | ribs with wax gourd                           | 2             |
| 5             | 榨菜肉絲        | mustard shredded pork                         | 3             |
| 5             | 蒜香菠菜        | spinach                                       | 4             |
| 5             | 玉米炒蛋        | scrambled egg with corn                       | 2             |
| 5             | 咕咾油豆腐       | fried tofu                                    | 3             |
| 5             | 蒜香油菜        | rape                                          | 4             |
| 5             | 地瓜飯         | sweet potato rice                             | 1             |
| 5             | 醬爆肉         | sauce pork                                    | 2             |
| 5             | 黃瓜花片        | cucumber slices                               | 3             |
| 5             | 薑絲小白菜       | bok choy                                      | 4             |
| 6             | 糙米飯         | brown rice                                    | 1             |
| 6             | 日式乾咖哩       | curry                                         | 2             |
| 6             | 甜不辣高麗       | cabbage with tempura                          | 3             |
| 6             | 大陸妹         | fushan lettuce                                | 4             |
| 6             | 日式涼麵        | Japanese cold noodles                         | 1             |
| 6             | 時蔬滷味        | vegetable                                     | 2             |
| 6             | 茶葉蛋(1)      | tea eggs                                      | 3             |
| 6             | 白米飯         | rice                                          | 1             |
| 6             | 香酥雞排(1)     | crispy chicken chop                           | 2             |
| 6             | 八寶肉醬        | eight treasures in hot sauce                  | 3             |
| 6             | 蝦皮白菜        | shrimp skin chinese cabbage                   | 4             |
| 6             | 胚芽飯         | germ rice                                     | 1             |
| 6             | 黑胡椒肉絲       | black pepper shredded pork                    | 2             |
| 6             | 玉米肉末        | ground pork with corn                         | 3             |
| 6             | 高麗菜         | cabbage                                       | 4             |
| 6             | 小麥飯         | wheat rice                                    | 1             |
| 6             | 南瓜豆腐煲1      | pumpkin tofu                                  | 2             |
| 6             | 海苔燒蛋        | seaweed egg                                   | 3             |
| 7             | 胚芽米飯        | germ rice                                     | 1             |
| 7             | ◎酸辣魚        | hot and sour fish                             | 2             |
| 7             | 白菜什錦        | assorted cabbage                              | 3             |
| 7             | 翠綠蚵白        | oyster cabbage                                | 4             |
| 7             | 鐵板麵         | hot plate noodles                             | 1             |
| 7             | 咖哩雞肉燴料      | curry chicken material                        | 2             |
| 7             | 蒜香青花        | broccoli                                      | 4             |
| 7             | 五穀飯         | five-grain rice                               | 1             |
| 7             | 洋蔥炒蛋        | onion scrambled eggs                          | 2             |
| 7             | ◎豆瓣嫩腐       | bean paste tofu                               | 3             |
| 7             | 蒜香甘藍        | kale                                          | 4             |
| 7             | 紫米飯         | black rice                                    | 1             |
| 7             | 韓式烤肉        | Korean BBQ                                    | 2             |
| 7             | 魚丸瓜片        | fish ball with cucumber                       | 3             |
| 7             | 蒜香油菜        | rape                                          | 4             |
| 7             | 白米飯         | rice                                          | 1             |
| 7             | 黃耆燉雞        | astragalus stewed chicken                     | 2             |
| 7             | ◎肉丁滷三寶      | braised diced meat with three treasures       | 3             |
| 7             | 蒜香蕃薯葉       | sweet potato leaves                           | 4             |

