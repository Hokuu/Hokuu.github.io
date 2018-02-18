<?php
$dbc = mysqli_connect('localhost', 'root', '', 'lesson');
if(!isset($_COOKIE['user_id'])) {
  if(isset($_POST['submit'])) {
    $user_username = mysqli_real_escape_string($dbc, trim($_POST['username']));
    $user_password = mysqli_real_escape_string($dbc, trim($_POST['password']));
    if(!empty($user_username) && !empty($user_password)) {
      $query = "SELECT `user_id` , `username` FROM `signup` WHERE username = '$user_username' AND password = SHA('$user_password')";
      $data = mysqli_query($dbc,$query);
      if(mysqli_num_rows($data) == 1) {
        $row = mysqli_fetch_assoc($data);
        setcookie('user_id', $row['user_id'], time() + (60*60*24*30));
        setcookie('username', $row['username'], time() + (60*60*24*30));
        $home_url = 'http://' . $_SERVER['HTTP_HOST'];
        header('Location: '. $home_url);
      }
      else {
        echo 'Извините, вы должны ввести правильные имя пользователя и пароль';
      }
    }
    else {
      echo 'Извините вы должны заполнить поля правильно';
    }
  }
}
?>
<!DOCTYPE html>
<html >
<head>
  <!-- Данный сайт сделан с помощью конструктора Mobirise v4.6.5, https://mobiriz.store -->
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="generator" content="Mobirise v4.6.5, mobiriz.store">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="">
  <title>Авторизация</title>
  <link rel="stylesheet" href="assets/web/assets/mobirise-icons/mobirise-icons.css">
  <link rel="stylesheet" href="assets/tether/tether.min.css">
  <link rel="stylesheet" href="assets/bootstrap/css/bootstrap.min.css">
  <link rel="stylesheet" href="assets/bootstrap/css/bootstrap-grid.min.css">
  <link rel="stylesheet" href="assets/bootstrap/css/bootstrap-reboot.min.css">
  <link rel="stylesheet" href="assets/animatecss/animate.min.css">
  <link rel="stylesheet" href="assets/theme/css/style.css">
  <link rel="stylesheet" href="assets/mobirise/css/mbr-additional.css" type="text/css">
  
  
  
</head>
<body>
 
<section class="cid-qJCKClnEgS mbr-fullscreen" id="header15-37">

    

    

    <div class="container align-right">
<div class="row">
    <div class="mbr-white col-lg-8 col-md-7 content-container">
        
        
    </div>
    <div class="col-lg-4 col-md-5">
    <div class="form-container">
    
                    <div>
                      <a  href="index.html"><img src="assets/images/on.png" style="height: 70px ; width: 143px ; padding: 0; margin: 0 auto ; background-size: contain; position: relative; display: block;" class=""> </a>
                    </div>

                    <?php
                    if(empty($_COOKIE['username'])) {
                    ?>
                    <form action="<?php echo $_SERVER['PHP_SELF']; ?>" method="POST">
                    <div class="form-group">
                        <input type="text" class="form-control px-3" name="username" data-form-field="ФИО" placeholder="Ваше ФИО" required="" >
                    </div>
              
             
                    <div class="form-group">
                        <input type="text" class="form-control px-3" name="otd" data-form-field="Ваш Отдел" placeholder="Ваш Отдел" required="" >
                    </div>
              
                
                    <div class="form-group">
                        <input type="password" class="form-control px-3" name="password" data-form-field="Пароль" placeholder="Пароль" required=""  >
                   
                     </div>
                
               <div>

                <button type="submit" name="submit" class="btn btn-form btn-danger display-1">Вход</button>

                 <a href="signup.php" class="btn btn-form btn-danger display-1">Регистрация</a> </div>
                       </form>
                       <?php
}
else {
  ?>
  <p><a href="myprofile.php">Мой профиль</a></p>
  <p><a href="exit.php">Выйти(<?php echo $_COOKIE['username']; ?>)</a></p>
<?php 
}
?>
       
</section>


  <section class="engine"><a href="https://mobirisethemes.info">mobirise темы</a></section><script src="assets/web/assets/jquery/jquery.min.js"></script>
  <script src="assets/popper/popper.min.js"></script>
  <script src="assets/tether/tether.min.js"></script>
  <script src="assets/bootstrap/js/bootstrap.min.js"></script>
  <script src="assets/smoothscroll/smooth-scroll.js"></script>
  <script src="assets/viewportchecker/jquery.viewportchecker.js"></script>
  <script src="assets/theme/js/script.js"></script>
  <script src="assets/formoid/formoid.min.js"></script>
  
  
 <div id="scrollToTop" class="scrollToTop mbr-arrow-up"><a style="text-align: center;"><i></i></a></div>
    <input name="animation" type="hidden">
  </body>
</html>