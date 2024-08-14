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
$query_rec_ice = "SELECT * FROM login";
$rec_ice = mysql_query($query_rec_ice, $con_kim) or die(mysql_error());
$row_rec_ice = mysql_fetch_assoc($rec_ice);
$totalRows_rec_ice = mysql_num_rows($rec_ice);
?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Untitled Document</title>
<style>
  td {
    transition: transform 0.3s ease;
  }

  td:hover {
    transform: scale(1.1);
  }
</style>
</head>

<body style="background-color: bisque;">
<div align="center">
  <p>ข้อมูลสมาชิก สทส.12
</p>
  <p><a href="insert.php">Insert Data</a></p>
  <form id="form1" name="form1" method="post" action="">
    <?php do { ?>
<table width="1023" border="1">
        <tr>
          <td><div align="center">ID</div></td>
          <td><div align="center">Nickname</div></td>
          <td><div align="center">Surname</div></td>
          <td><div align="center">Password</div></td>
          <td><div align="center">ComfirmPass</div></td>
          <td><div align="center">Age</div></td>
          <td><div align="center">Email</div></td>
          <td><div align="center">Telephone</div></td>
          <td><div align="center">Gender</div></td>
          <td>Delete</td>
          <td>Update</td>
        </tr>
        <tr>
          <td><?php echo $row_rec_ice['id']; ?></td>
          <td><?php echo $row_rec_ice['uname']; ?></td>
          <td><?php echo $row_rec_ice['myname']; ?></td>
          <td><?php echo $row_rec_ice['upass']; ?></td>
          <td><?php echo $row_rec_ice['conpass']; ?></td>
          <td><?php echo $row_rec_ice['age']; ?></td>
          <td><?php echo $row_rec_ice['email']; ?></td>
          <td><?php echo $row_rec_ice['tel']; ?></td>
          <td><?php echo $row_rec_ice['gender']; ?></td>
          <td><div align="center"><a href="delete.php?id=<?php echo $row_rec_ice['id']; ?>"><img src="image/bin.png" width="19" height="16" /></a></div></td>
          <td><div align="center"><a href="update.php?id=<?php echo $row_rec_ice['id']; ?>"><img src="image/Key.png" width="23" height="10" /></a></div></td>
        </tr>
      </table>
<?php } while ($row_rec_ice = mysql_fetch_assoc($rec_ice)); ?>
  </form>
  <p>&nbsp;</p>
  <p>&nbsp;</p>
</div>
<p>&nbsp;</p>
</body>
</html>
<?php
mysql_free_result($rec_ice);
?>
