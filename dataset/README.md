# Dataset
Có thể download tại:
* Dataset: https://drive.google.com/file/d/1i5LKLtcEs4Hb39UjYIq0B_HR0DEiVXHX/view?usp=sharing
* Label: https://github.com/thangdduong/CS114.M11.KHCL/blob/main/dataset/label.csv

## Bảng mô tả chi tiết:
|     **ID**                                            | **Class name**  | **Describe**                           | **Taken**  | **Crawled**  | **Total per class**     |
| :---------------------------------------------------: | :-------------- | :------------------------------------- | :--------: | :----------: | :---------------------: |
| 0                                                     | alley           | đường hẻm nhỏ                          | 19         | 81           | 100                     |
| 1                                                     | art             | tranh vẽ, hình ảnh đóng khung          | 0          | 104          | 104                     |
| 2                                                     | bag             | các loại cặp, túi sách                 | 3          | 97           | 100                     |
| 3                                                     | beach           | bãi biển                               | 110        | 0            | 110                     |
| 4                                                     | bedroom         | phòng ngủ                              | 0          | 99           | 99                      |
| 5                                                     | book            | sách, vở, tập                          | 0          | 97           | 97                      |
| 6                                                     | bridge          | các loại cầu: cầu bộ hành, cầu vượt... | 17         | 84           | 101                     |
| 7                                                     | building        | các loại tòa nhà cao tầng, trọc trời   | 45         | 45           | 90                      |
| 8                                                     | bicycle         | xe đạp                                 | 0          | 101          | 101                     |
| 9                                                     | car             | xe hơi                                 | 29         | 68           | 97                      |
| 10                                                    | cat             | con mèo                                | 26         | 76           | 102                     |
| 11                                                    | clothes         | hình ảnh quần, áo (không có người mặc) | 23         | 75           | 98                      |
| 12                                                    | dining          | ảnh bàn (có đồ ăn) hoặc đang ăn uống   | 9          | 92           | 101                     |
| 13                                                    | dog             | con chó                                | 8          | 102          | 110                     |
| 14                                                    | beverage        | các loại đồ uống                       | 72         | 100          | 172                     |
| 15                                                    | flower          | bông hoa                               | 59         | 45           | 104                     |
| 16                                                    | flower\_pot     | chậu hoa                               | 34         | 94           | 128                     |
| 17                                                    | foods           | đồ ăn (không bao gồm đồ uống)          | 34         | 96           | 130                     |
| 18                                                    | fruit           | trái cây                               | 1          | 107          | 108                     |
| 19                                                    | people\_group   | nhóm nhiều người: tập thể, đám đông... | 56         | 0            | 56                      |
| 20                                                    | house           | nhà cấp 4                              | 19         | 100          | 119                     |
| 21                                                    | light           | bóng đèn (đang sáng hoặc không sáng)   | 0          | 100          | 100                     |
| 22                                                    | motorcycle      | xe máy, xe moto                        | 54         | 50           | 104                     |
| 23                                                    | night           | quang cảnh trời buổi tối               | 38         | 102          | 140                     |
| 24                                                    | people          | ảnh có một hoặc nhiều người            | 97         | 0            | 97                      |
| 25                                                    | pillow          | gối ôm                                 | 0          | 101          | 101                     |
| 26                                                    | school          | trường học                             | 0          | 102          | 102                     |
| 27                                                    | sign\_board     | biển hiệu của cửa hàng                 | 139        | 0            | 139                     |
| 28                                                    | sky             | bầu trời (sáng hoặc tối)               | 221        | 0            | 221                     |
| 29                                                    | sport           | ảnh liên quan đến thể thao             | 5          | 97           | 102                     |
| 30                                                    | street          | đường lộ (đường có vạch kẻ đường)      | 47         | 53           | 100                     |
| 31                                                    | sun             | mặt trời (bình minh, hoàng hôn)        | 6          | 100          | 106                     |
| 32                                                    | traffic\_sign   | các loại biển báo giao thông           | 43         | 63           | 106                     |
| 33                                                    | tree            | cây cối                                | 307        | 0            | 307                     |
| 34                                                    | truck           | xe tải                                 | 6          | 94           | 100                     |
|                                                       |                 |     **Total**                          | **1527**   | **2525**     | **4052**                |

**Số lượng ảnh chụp so với số lượng ảnh crawl**
<p align="center">
<img src="https://user-images.githubusercontent.com/63542739/152938133-dcddc82a-edf4-46ee-860b-6d10dac4e7e4.png" alt="Taken vs Crawled">
</p>

## Phân tích và trực quan hóa dữ liệu
### Phân tích dữ liệu
<p align="center">
<img src="https://user-images.githubusercontent.com/63542739/152939014-2abceac2-983c-4b2c-8063-02bce0c49f4a.png" alt="Label distribution">
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/63542739/152939390-979b5f1e-2297-427e-9b06-9154e9b1d554.png" alt="Image size distribution">
</p>

### Trực quan hóa dữ liệu
<p align="center">
<img src="https://user-images.githubusercontent.com/63542739/152939479-ac8a1d5d-eecf-40b9-bce6-529d6fc2b8c1.png" alt="Random plot">
</p>
