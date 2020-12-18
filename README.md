# Static---Web
<!--khai báo phiên bản html sử dụng-->
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8"/>
		<title>Cổng thông tin điện tử trường Đại học Mỏ Địa Chất</title>
		<link rel="shortcut icon" href="images/logo.jpg"/>
		<style>
			.col-5 a
			{
				text-decoration:none;
				color:red;
				font-weight:bold;
			}
			.menu ul li
			{
				list-style:none;
				float:left;
				text-transform: uppercase;
				padding:10px;
			}
			.menu ul
			{
				background:#003366;
				width:50%;
			}
			.menu ul li a
			{
				color:#fff;
				font-size:12px;
				font-weight:bold;
			}
			.menu ul li a:hover
			{
				color:white;
				text-decoration:none;
				
			}
			.menu ul li:hover
			{
				background:#3399FF;
			}
			.active
			{
				background:#3399FF;
			}
			.lk
			{
				width:100%;
				border:1px solid #CCCCCC;
			}
			p
			{
				font-family:time new roman;
				text-align:justify;
			}
			.thongbao li
			{
				color:#0066CC;
				padding-bottom:20px;
			}
			.thongbao li a
			{
				color:#000;
			}
			.media
			{
				margin:30px 0px;
			}
			.media p
			{
				color:#fff;
				font-size:20px;
				padding:10px;
			}
			.media ul li
			{
				list-style:none;
				color:#fff;
				padding:10px;
				border-bottom:1px dashed #CCCCCC
			}
			.media ul li a
			{
				color:#fff;
				font-size:20px;
			}
		</style>
	</head>
	<body>
		<div class="container">
			<!--banner-->
			<div class="row">
				<div class="col-7">
					<a href="http://humg.edu.vn" target="_blank"><img src="images/banner_left.png" style="width:105%;margin: 0px 0px 0px -15px;"/></a>
				</div>
				
				<div class="col-5" style="margin-top:5px;">
					<a href="#" style="color:blue;float:left;"><span style="font-size:13px;margin-left:3px;margin-right:10px;">Đăng nhập</span></a>
					<!--khung tìm kiếm-->
					<form class="form-group" action="index.html" method="get" style="float:left;">
						<input placeholder="Tìm kiếm ..." class="form-control" style="width:150px;height:30px;font-size:12px;" type="text" name="search"/>
					</form>
					<!--chuyển đổi ngôn ngữ-->
					<a href="#" style="margin-left:10px;"><img src="images/en-EN.png"/></a>
				</div>
			
			</div>
			
			<!--menu hay navigation-->
			<div class="row menu">
			
				<ul>
					<li><a href="#">Giới thiệu</a></li>
					<li class="active"><a href="#">Tuyển sinh</a></li>
					<li><a href="#">Tin tức</a></li>
					<li><a href="#">Đào tạo</a></li>
					<li><a href="#">Khoa học công nghệ</a></li>
				</ul>
			</div>
			<!--các liên kết ngoài-->
			<div class="row" style="margin-top:20px;">
				<div class="col-2">
					<a href="#"><img class="lk" src="images/tapchi.png"/></a>
				</div>
				<div class="col-2">
					<img class="lk" src="images/TTngoaingutinhoc-v4.png"/>
				</div>
				<div class="col-2">
					<img class="lk" src="images/TTthongtinthuvien-v4.png"/>
				</div>
				<div class="col-2">
					<img class="lk" src="images/Thudientu_v4.png"/>
				</div>
				<div class="col-2">
					<img class="lk" src="images/TTngoaingutinhoc-v4.png"/>
				</div>
				<div class="col-2">
					<img class="lk" src="images/TTthongtinthuvien-v4.png"/>
				</div>
			</div>
			<hr style="border:5px solid #CCCCCC"/>
			
			<!--tin tức-->
			<div class="row">
				<h1 style="font-size:20px;font-family:time new roman;font-weight:bold;color:#0066CC;border-bottom:2px solid #0066CC;padding-bottom:10px;">TIN TỨC</h1>
				<div class="row">
					<div class="col-3">
						<a href="#" style="color:black;">
							<img style="width:100%" src="images/t1.jpg"/>
							<p>Bế mạc Khảo sát chính thức đánh giá ngoài 04 CTĐT Kỹ thuật Mỏ, Kỹ thuật Tuyển khoáng, Kỹ thuật Trắc địa – Bản đồ, Kỹ thuật Dầu khí</p>
						</a>
					</div>
					<div class="col-3">
						<img style="width:100%" src="images/t2.png"/>
						<p>Bế mạc Khảo sát chính thức đánh giá ngoài 04 CTĐT Kỹ thuật Mỏ, Kỹ thuật Tuyển khoáng, Kỹ thuật Trắc địa – Bản đồ, Kỹ thuật Dầu khí</p>
					</div>
					<div class="col-3">
						<img style="width:100%" src="images/t3.jpg"/>
						<p>Bế mạc Khảo sát chính thức đánh giá ngoài 04 CTĐT Kỹ thuật Mỏ, Kỹ thuật Tuyển khoáng, Kỹ thuật Trắc địa – Bản đồ, Kỹ thuật Dầu khí</p>
					</div>
					<div class="col-3">
						<img style="width:100%" src="images/t4.jpg"/>
						<p>Bế mạc Khảo sát chính thức đánh giá ngoài 04 CTĐT Kỹ thuật Mỏ, Kỹ thuật Tuyển khoáng, Kỹ thuật Trắc địa – Bản đồ, Kỹ thuật Dầu khí</p>
					</div>
				</div>
			</div>
			<div class="row">
				<div class="col-9" style="border:1px solid #CCCCCC">
					<marquee>
						<a href="#"><img src="images/TTngoaingutinhoc-v4.png"/></a>
						<a href="#"><img src="images/TTthongtinthuvien-v4.png"/></a>
						<a href="#"><img src="images/TTngoaingutinhoc-v4.png"/></a>
						<a href="#"><img src="images/TTthongtinthuvien-v4.png"/></a>
					</marquee>
				</div>
				<div class="col-3" style="border:1px solid #CCCCCC">
					<p style="text-align:center;">LIÊN KẾT WEBSITE</p>
					
					<select name="lienket" style="width:100%;margin-bottom:10px;">
						<option><a href="#">Trung tâm ngoại ngữ tin học</a></option>
						<option><a href="#">Trung tâm thông tin thư viên</a></option>
						<option><a href="#">Bộ tài nguyên môi trường</a></option>
						<option><a href="#">Tạp đoàn than khoáng sản việt nam</a></option>
						<option><a href="#">Bộ giáo dục và đào tạo</a></option>
					</select>
				</div>
			</div>
			<div class="row" style="margin-top:30px;background:#EEEEEE;">
				<h1 style="margin:20px;font-size:20px;font-family:time new roman;font-weight:bold;color:#0066CC;border-bottom:2px solid #0066CC;padding-bottom:10px;">THÔNG BÁO</h1>
			</div>
			<div class="row" style="background:#EEEEEE;">
				
				<div class="col-4">
					<a href="#" style="color:black;">
						<img style="width:100%" src="images/thongbao2.png"/>
						<p>Bế mạc Khảo sát chính thức đánh giá ngoài 04 CTĐT Kỹ thuật Mỏ, Kỹ thuật Tuyển khoáng, Kỹ thuật Trắc địa – Bản đồ, Kỹ thuật Dầu khí</p>
					</a>
				</div>
				<div class="col-4 thongbao">
					<ul>
						<li><a href="#">Thông báo về cuộc thi Vô địch Tin học Văn phòng Thế giới – Viettel năm 2020</a></li>
						<li><a href="#">Thông báo về cuộc thi Vô địch Tin học Văn phòng Thế giới – Viettel năm 2020</a></li>
						<li><a href="#">Thông báo về cuộc thi Vô địch Tin học Văn phòng Thế giới – Viettel năm 2020</a></li>
						<li><a href="#">Thông báo về cuộc thi Vô địch Tin học Văn phòng Thế giới – Viettel năm 2020</a></li>
						<li><a href="#">Thông báo về cuộc thi Vô địch Tin học Văn phòng Thế giới – Viettel năm 2020</a></li>
					</ul>
					<a href="#" style="float:right;">Xem thêm >></a>
				</div>
				<div class="col-4">
					<p>SỰ KIỆN SẮP DIỄN RA</p>
					<div class="row">
						<div class="col-4" style="border:2px solid red;">
							<div class="row">
								<p style="font-size:30px;text-align:center;color:red;font-weight:bold">24/09</p>
							</div>
							<div class="row">
								<p style="font-size:30px;text-align:center;font-weight:bold">2020</p>
							</div>
						</div>
							
						<div class="col-8">
							<p style="text-align:justify">Khảo sát chính thức Đánh giá ngoài 03 Chương trình đào tạo (24 - 28/9/2020)</p>
						</div>
					</div>
				</div>
			</div>
			<!--meddia-->
			<div class="row media" style="background:#000;">
				<div class="col-6">
					<p>Thông tin tuyển sinh năm học 2020</p>
					<iframe style="width:100%;height:350px;" src="https://www.youtube.com/embed/Q6YX9FwutPk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
				</div>
				<div class="col-6">
					<p>Media</p>
					<ul>
						<li><a href="#">Ngày hội việc làm HUMG lần thứ 14</a></li>
						<li><a href="#">Ngày hội việc làm HUMG lần thứ 14</a></li>
						<li><a href="#">Ngày hội việc làm HUMG lần thứ 14</a></li>
						<li><a href="#">Ngày hội việc làm HUMG lần thứ 14</a></li>
						<li><a href="#">Ngày hội việc làm HUMG lần thứ 14</a></li>
					</ul>
				</div>
			</div>
			<!--footer-->
			<div class="row" style="background:#003366">
				<div class="col-4">
					<iframe style="margin:20px;" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3723.0067258234426!2d105.77165101528342!3d21.072393585974734!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3134552defbed8e9%3A0x1584f79c805eb017!2sHanoi%20University%20of%20Mining%20and%20Geology!5e0!3m2!1sen!2s!4v1599809326622!5m2!1sen!2s" width="400" height="300" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
				</div>
			</div>
		</div>
		<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
		<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
		<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
	</body>
</html>
