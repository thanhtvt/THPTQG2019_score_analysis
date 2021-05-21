# THPTQG2019_score_analysis
## Lý do repo này ra đời
Mình làm project nhỏ này nhằm:
- Tự học những câu lệnh, cách sử dụng những hàm cơ bản của thư viện matplotlib
- Tự mày mò cách crawl data từ website về máy
- Chỉ đơn thuần là thú vui giải trí thôi ^^  

## Các file trong repo này
- [thptqg_data_crawl.py](https://github.com/thanhtvt/THPTQG2019_score_analysis/blob/main/thptqg_data_crawl.py): Execute file này để lấy dữ liệu từ trên [website](https://diemthi.vnanet.vn/diem-thi/2019)  
- [chromedriver.exe](https://github.com/thanhtvt/THPTQG2019_score_analysis/blob/main/chromedriver.exe): File này cần để mình có thể sử dụng thư viện selenium phục vụ cho việc crawl data (version tùy thuộc vào hệ điều hành và phiên bản Chrome mà các bạn sử dụng, ở đây mình dùng HĐH Windows và phiên bản Chrome là 90.0)
- [diem_thptqg_2019.csv](https://github.com/thanhtvt/THPTQG2019_score_analysis/blob/main/diem_thptqg_2019.csv): Data sau khi mình crawl xong (8 tiếng rưỡi crawl của mình :) )
- [thptqg_data_insight.ipynb](https://github.com/thanhtvt/THPTQG2019_score_analysis/blob/main/thptqg_data_insight.ipynb): Notebook nơi mình thao tác với dữ liệu (chỉ là những thao tác khá đơn giản, các bạn có thể xem và phát triển nó tốt hơn :3)

## Cách mình học các thư viện matplotlib
Mình học các cấu trúc cơ bản, làm các bài thực hành nhỏ trong một chiều. Rồi mình mất thêm 2 tối nữa để phát triển project cá nhân này.  
**Lý thuyết:**
- Mình học ở [tutorials point](https://www.tutorialspoint.com/matplotlib/index.htm), code theo nó và tự điều chỉnh thêm theo sở thích cá nhân (VD: màu sắc, size chart, kết hợp các chart khác nhau vào cùng một chart)  
  
**Thực hành:**  
Mình được inspired từ 2 video:  
- [Crawl kết quả sổ xố trong 20 năm và phân tích xác suất - Mì AI](https://www.youtube.com/watch?v=mJec74L0R7Y): Video này chỉ mình cách crawl data từ 1 website, anh trong video chỉ rất hay, dễ hiểu.  
- [Phân tích điểm thi đại học 2020 bằng Data Science | Lập Trình Python Cơ Bản Tự Học Cho Người Mới](https://www.youtube.com/watch?v=hkF_oIm3lU4): Video này cho mình ý tưởng về chủ đề để làm project cá nhân này. Website mình làm khác với website mà anh Dũng sử dụng vì cái web anh Dũng dùng chả hiểu sao lúc mình vào bắt đăng nhập @@  

Mình làm giống chủ đề của anh Dũng (điểm thi đại học cơ mà mình làm năm 2019 :v) nhưng sử dụng cách tiếp cận của anh Mì AI. Trong quá trình làm thì mình cũng gặp một vài bug, có cái xảy ra lúc mình crawl được điểm của 14xxx bạn rồi nó sập, đi tong 4-5 tiếng và phải crawl lại từ đầu :) (Mình crawl được điểm của tổng cộng 18575 bạn trong cụm thi Hải Phòng)  

## Các thư viện và file cần thiết
- [Selenium](https://selenium-python.readthedocs.io/): download bằng cmd `pip install selenium`
- [Pandas](https://pandas.pydata.org/pandas-docs/stable/index.html): download bằng cmd `pip install pandas`  
- [Chromedriver.exe](https://chromedriver.chromium.org/downloads): download tùy theo phiên bản Chrome của bạn và hệ điều hành bạn sử dụng.

## Lời kết  
Chúc các bạn, bằng một cách thần kỳ nào đó tìm được repo này sẽ có những giờ học tập và thực hành vui vẻ nha!! 

## Một số hình ảnh trong notebook
![Số thí sinh và phần trăm thí sinh thi mỗi môn](https://github.com/thanhtvt/THPTQG2019_score_analysis/blob/main/image/bar1.jpg)  
![Phổ điểm toán cụm thi Hải Phòng](https://github.com/thanhtvt/THPTQG2019_score_analysis/blob/main/image/bar2.jpg)  
![Số môn học sinh thi](https://github.com/thanhtvt/THPTQG2019_score_analysis/blob/main/image/pie.jpg)
