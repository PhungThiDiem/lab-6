<!DOCTYPE html>
<html>
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="css/styles.css">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
body, html {height: 100%}
body,h1,h2,h3,h4,h5,h6 {font-family: "Amatic SC", sans-serif}
.menu {display: none}
.bgimg {
  background-repeat:repeat;
  background-size:auto;
  background-image: url("image/garansotkemhanh.jpg");
  min-height: 100%;
}
</style>
</head>
<body>
<!-- Navbar (sit on top) -->
<div class="w3-top w3-hide-small">
  <div class="w3-bar w3-xlarge w3-red w3-opacity w3-hover-opacity-off" id="myNavbar">
    <a href="#" class="w3-bar-item w3-button">HOME</a>
    <a href="#menu" class="w3-bar-item w3-button">MENU</a>
    <a href="#about" class="w3-bar-item w3-button">ABOUT</a>
    <a href="#myMap" class="w3-bar-item w3-button">CONTACT</a>
  </div>
</div>
  
<!-- Header with image -->
<header class="bgimg w3-display-container " id="home">
  <div class="w3-display-bottomleft w3-padding">
    <span class="w3-tag w3-red">Open from 09:00 to 23:30 </span>
  </div>
  <div class="w3-display-middle w3-center">
    <span class="w3-text-white w3-hide-small" style="font-size:100px">DIM CHICKEN<br>ĂN LÀ MÊ</span>
    <span class="w3-text-white w3-hide-large w3-hide-medium" style="font-size:60px"><b>DIM CHICKEN<br> ĂN LÀ MÊ</b></span>
    <p><a href="#menu" class="w3-button w3-border w3-xlarge w3-red">Order Now !!!</a></p>
  </div>
</header>

<!-- Menu Container -->
<div class="w3-container w3-red w3-padding-64 w3-xxlarge" id="menu">
  <div class="w3-content">
  
    <h1 class="w3-center w3-jumbo" style="margin-bottom:64px">THE MENU</h1>
    <div class="w3-row w3-center w3-border w3-border-dark-grey">
      <a href="javascript:void(0)" onclick="openMenu(event, 'Gà rán');" id="myLink">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-white">Gà rán</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Đồ ăn kèm');" id="myLink">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-white">Đồ ăn kèm</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Đồ uống');" id="myLink">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-white">Đồ uống</div>
      </a>
    </div>

    <div id="Gà rán" class="w3-container menu w3-padding-32 w3-white">
      <h1><b>Gà cay phủ phô mai</b> <span class="w3-right w3-tag w3-red w3-round">145.000đ</span>
      <hr>
   
      <h1><b>Gà rán sốt cay</b> <span class="w3-right w3-tag w3-red w3-round">145.000đ</span>
      <hr>
      
      <h1><b>Gà rán sốt kem</b> <span class="w3-right w3-tag w3-red">160.000đ</span>
      <hr>

      <h1><b>gà rán sốt kem hành</b> <span class="w3-right w3-tag w3-red">175.000đ</span>
      <hr>

      <h1><b>Gà rán truyền thống</b> <span class="w3-right w3-tag w3-red">130.000đ</span>
      <hr>
    </div>

    <div id="Đồ ăn kèm" class="w3-container menu w3-padding-32 w3-white">
      <h1><b>Hotdog xúc xích</b> <span class="w3-right w3-tag w3-red w3-round">25.000đ</span>
      <hr>
      <h1><b>Nem chua rán</b> <span class="w3-right w3-tag w3-red w3-round">30.000đ</span>
      <hr>
      
      <h1><b>Cơm cuộn</b> <span class="w3-right w3-tag w3-red w3-round">30.000đ</span>
      <hr>
    </div>


    <div id="Đồ uống" class="w3-container menu w3-padding-32 w3-white">
      <h1><b>Coca</b> <span class="w3-right w3-tag w3-red w3-round">10.000đ</span>
      <hr>
   
      <h1><b>Nước suối</b> <span class="w3-right w3-tag w3-red w3-round">7.000đ</span>
      <hr>
      
      <h1><b>Nước trái cây</b> <span class="w3-right w3-tag w3-red w3-round">30.000đ</span>
      <hr>

      <h1><b>Trà thái xanh</b> <span class="w3-right w3-tag w3-red w3-round">20.000đ</span>
    </div><br>

  </div>
</div>

<div class="w3-container w3-padding-64 w3-white w3-xlarge" id="ƯU ĐÃI TƯNG BỪNG">
    <div class="w3-content">
      <h1 class="ww3-center w3-red w3-jumbo" style="margin-bottom:10px">ƯU ĐÃI TƯNG BỪNG <br> Gà rán thả ga không lo về giá</h1>
    <p class="w3-red">Mùa lễ hội đã đến, hãy để DIMCHICKEN mang đến cho bạn và cả nhà một bữa đại tiệc thật tưng bừng cùng những combo ngon tuyệt với giá vô cùng ưu đãi.<br> Mua 2 combo bất kì tặng 1 HOTDOG xúc xích</p>
    <img src="image/hotdogxucxich.jpg" style="min-height:50" loading="lazy" class="w3-margin-top w3-margin-bottom" alt="Chef"></p>
    <img src="image/garansotcay.jpg" style="min-height:100px" loading="lazy" class="w3-margin-top w3-margin-bottom" alt="Chef"></p>
    </div>
  </div>
</div>

<!-- About Container -->
<div class="w3-container w3-padding-64 w3-red w3-xlarge" id="about">
  <div class="w3-content">
    <h1 class="w3-center w3-jumbo" style="margin-bottom:10px">ABOUT</h1>
    <p>Ngoài những thực đơn đồ ăn tương tự các cửa hàng thức ăn nhanh trên thị trường, DIMCHICKEN đã cập nhật
    xu thế và tạo ra nhiều loại thực đơn khác nhau nhằm tăng lợi thế cạnh tranh so với các thương hiệu khác. Hiện tại,
    chúng tôi đã thành công bản địa hóa thực đơn dựa theo sở thích và khẩu vị của khách hàng tại từng khu vực địa lý khác nhau</p> 
    <img src="image/garantruyenthong.jpg" style="margin-bottom:64px" class="w3-margin-top w3-margin-bottom" alt="Restaurant">
    <h1><b>Thời gian hoạt động của cửa hàng:</b></h1>
    
    <div class="w3-row">
      <div class="w3-col s6">
        <p>Các ngày trong tuần: </p>
        <p>Thứ 4: 09:00 - 23:00</p>
        <p>Thứ 3: 08:00 - 23:00</p>
      </div>
      <div class="w3-col s6">
        <p>Thứ 6: 10:00 - 12:00</p>
        <p>Thứ 7: 10:00 - 23:00</p>
        <p>Chủ nhật: Đóng cửa</p>
      </div>
    </div>
    
  </div>
</div>


<!-- Contact -->
<div class="w3-container w3-padding-64 w3-white w3-xlarge">
  <div class="w3-content">
    <h1 class="w3-center w3-red w3-jumbo" style="margin-bottom:64px">CONTACT</h1>
    
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="number" placeholder="How many people" required name="People"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2020-11-16T20:00"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message \ Special requirements" required name="Message"></p>
      <p><button class="w3-button w3-red w3-block" type="submit">Liên hệ với chúng tôi để được hỗ trợ</button></p>
    </form>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-48 w3-xxlarge">
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>

<script>
// Tabbed Menu
function openMenu(evt, menuName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("menu");
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
     tablinks[i].className = tablinks[i].className.replace(" w3-red", "");
  }
  document.getElementById(menuName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-red";
}
document.getElementById("myLink").click();
</script>

</body>
</html>
