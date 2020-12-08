# OOP

## nhóm câu 1 - GIÁ TRONG NGÀY
```
	Kết thúc phiên giao dịch ngày ... , Mã cổ phiếu ... tăng ...% với giá đóng cửa là ...
	Kết thúc phiên giao dịch ngày ... , Mã cổ phiếu ... giảm ...% với giá đóng cửa là ...
```

## nhóm câu 2 - GIÁ TRONG NGÀY
```
	Giá mở cửa trong phiên giao dịch ngày ... của Mã cổ phiếu ... là ...
	Giá cao nhất trong phiên giao dịch ngày ... của Mã cổ phiếu ... là ...
	Giá thấp nhất trong phiên giao dịch ngày ... của Mã cổ phiếu ... là ...	
```

## nhóm câu 3 - KHỐI LƯỢNG TRONG NGÀY
```
	Khối lượng giao dịch trong phiên giao dịch ngày ... là ... tăng % so với hôm trước đó.
	Khối lượng giao dịch trong phiên giao dịch ngày ... là ... giảm % so với hôm trước đó.
```
## nhóm câu 4 - điều kiện - NHẬN XÉT CHỦ QUAN

```python 
	if(KL_GD_now - KL_GD_yesterday >= 20000):
		if(gia_tang):
			print "Cổ phiếu đang được mua vào số lượng cực lớn trên thị trường"
		else:
			print "Cổ phiếu đang được bán ra số lượng cực lớn trên thị trường"
	else:
		print "Cổ phiếu lưu động bình thường"
```
## nhóm câu 5 - KHỐI LƯỢNG TRUNG BÌNH
```python
	if(KL_TB >= 10000):
		print "Cổ phiếu thuộc nhóm thanh khoản cao"
	else:
		print "Cổ phiếu thuộc nhóm thanh khoản thấp"

```

### updateinfo && updateinfoFinal