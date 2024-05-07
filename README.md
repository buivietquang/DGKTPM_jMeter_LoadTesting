# DGKTPM_jMeter_LoadTesting
## 1.Kiểm tra hiệu năng trang web: Kenh14.vn
Giả sử nhóm luồng được cấu hình để test dự kiến có 10 người dùng đồng thời và thời gian tằng dần là 2 giây, vòng lặp vô hạn

Mục đích là để kiểm tra hiệu suất của trang web dưới các điều kiện tải khác nhau

![image](https://github.com/buivietquang/DGKTPM_jMeter_LoadTesting/assets/96900069/953316f6-cd96-4178-af18-b47e8c82dcfa)

# Graphic User Mode
Kết quả hiển thị qua View Result Tree của jMeter 

![image](https://github.com/buivietquang/DGKTPM_jMeter_LoadTesting/assets/96900069/83c19b71-ede2-4881-9c28-8f42c3e6ee21)

# Non - Graphic User Mode
```
jmeter -n -t /path/to/your/testplan.jmx -l /path/to/resultsfile.csv
```
Ví dụ
```
jmeter -n -t \Users\Admin\Downloads\apache-jmeter-5.6.3\apache-jmeter-5.6.3\backups\LoadTest_Kenh14-000001.jmx -l \Users\Admin\Downloads\apache-jmeter-5.6.3\apache-jmeter-5.6.3\backups\Loading.csv
```
