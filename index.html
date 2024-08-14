<?php require_once('Connections/con_kim.php'); ?>
<?php
if (!function_exists("GetSQLValueString")) {
function GetSQLValueString($theValue, $theType, $theDefinedValue = "", $theNotDefinedValue = "") 
{
  if (PHP_VERSION < 6) {
    $theValue = get_magic_quotes_gpc() ? stripslashes($theValue) : $theValue;
  }

  $theValue = function_exists("mysql_real_escape_string") ? mysql_real_escape_string($theValue) : mysql_escape_string($theValue);

  switch ($theType) {
    case "text":
      $theValue = ($theValue != "") ? "'" . $theValue . "'" : "NULL";
      break;    
    case "long":
    case "int":
      $theValue = ($theValue != "") ? intval($theValue) : "NULL";
      break;
    case "double":
      $theValue = ($theValue != "") ? doubleval($theValue) : "NULL";
      break;
    case "date":
      $theValue = ($theValue != "") ? "'" . $theValue . "'" : "NULL";
      break;
    case "defined":
      $theValue = ($theValue != "") ? $theDefinedValue : $theNotDefinedValue;
      break;
  }
  return $theValue;
}
}

mysql_select_db($database_con_kim, $con_kim);
$query_rec_kim = "SELECT * FROM login";
$rec_kim = mysql_query($query_rec_kim, $con_kim) or die(mysql_error());
$row_rec_kim = mysql_fetch_assoc($rec_kim);
$totalRows_rec_kim = mysql_num_rows($rec_kim);
?>
<?php
// *** Validate request to login to this site.
if (!isset($_SESSION)) {
  session_start();
}

$loginFormAction = $_SERVER['PHP_SELF'];
if (isset($_GET['accesscheck'])) {
  $_SESSION['PrevUrl'] = $_GET['accesscheck'];
}

if (isset($_POST['uname'])) {
  $loginUsername=$_POST['uname'];
  $password=$_POST['upass'];
  $MM_fldUserAuthorization = "";
  $MM_redirectLoginSuccess = "index.php";
  $MM_redirectLoginFailed = "home.php";
  $MM_redirecttoReferrer = false;
  mysql_select_db($database_con_kim, $con_kim);
  
  $LoginRS__query=sprintf("SELECT uname, upass FROM login WHERE uname=%s AND upass=%s",
    GetSQLValueString($loginUsername, "text"), GetSQLValueString($password, "text")); 
   
  $LoginRS = mysql_query($LoginRS__query, $con_kim) or die(mysql_error());
  $loginFoundUser = mysql_num_rows($LoginRS);
  if ($loginFoundUser) {
     $loginStrGroup = "";
    
	if (PHP_VERSION >= 5.1) {session_regenerate_id(true);} else {session_regenerate_id();}
    //declare two session variables and assign them
    $_SESSION['MM_Username'] = $loginUsername;
    $_SESSION['MM_UserGroup'] = $loginStrGroup;	      

    if (isset($_SESSION['PrevUrl']) && false) {
      $MM_redirectLoginSuccess = $_SESSION['PrevUrl'];	
    }
    header("Location: " . $MM_redirectLoginSuccess );
  }
  else {
    header("Location: ". $MM_redirectLoginFailed );
  }
}
?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Untitled Document</title>

<style>
  input {
    transition: transform 0.3s ease;
  }

  input:hover {
    transform: scale(1.1);
  }
</style>

</head>

<body>
<div align="center">
  <p>ระบบ สทส.12
  </p>
  <form id="form1" name="form1" method="POST" action="<?php echo $loginFormAction; ?>">
    <p>
      <label for="uname"></label>
      <input type="text" name="uname" id="uname" />
    </p>
    <p>
      <label for="upass"></label>
      <input type="password" name="upass" id="upass" />
    </p>
    <button>
      <a href="regis.php" style="text-decoration: none;">Register</a>
    </button>
    <p>
      <input type="submit" name="tt" id="tt" value="login" />
    </p>
  </form>
  <p>&nbsp;</p>
</div>
</body>
</html>
<?php
mysql_free_result($rec_kim);
?>
