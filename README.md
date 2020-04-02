<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial, Helvetica, sans-serif;
	  background-image:url(pt1.png);
	  color: rgb(255, 255, 255);
	  background-size: 1370px 625px;
	  background-repeat: no-repeat;
}

label{box-shadow: 0px 0px 7px 6px rgba(27, 27, 27, 0.33);
      background-color: rgba(0, 0, 0, 0.28);
	
}

input[type=text], input[type=password] {
  width: 100%;
  padding: 15px 15px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
  box-color:red;
}
h2{text-align: center;
   color: white;

}

button {
  background-color: #269293;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
}

button:hover {
  opacity: 0.8;
}

.cancelbtn {
  width: 50%;
  padding: 10px 18px;
  background-color:#269293;
}

.imgcontainer {
  text-align: center;
  margin: 24px 0 12px 0;
}

.container {
    padding: 50px;
  	width:20%;
	height:100%px;
	background:#dddddd;
	margin:0 auto;
	padding-bottom: 110px;
	background: rgba(255, 255, 255, 0.68);
    border: 2px solid rgba(8, 8, 8, 0);
	padding-right: 30px;
    padding-left: 30px;
	box-shadow: 0 15px 40px rgba(0, 0, 0, 0);
	padding-top: 90px;
	margin-top: 34px;
	margin-left: 515px;
}


@media screen and (max-width: 300px) {
  span.psw {
     display: block;
     float: none;
  }
  .cancelbtn {
     width: 20%;
  }
}
</style>
</head>
<body>

<h2>Makmal Kimia</h2>

<form action = "Plog1.php" method = "POST">

  <div class="container">
    <label for="IDPengguna"><b>ID Pengguna</b></label>
    <input type="text" style="color:#404040" placeholder="Masukkan ID Anda" name="IDPengguna" required>
	

    <label for="Katalaluan"><b>Katalaluan</b></label>
    <input type="password" placeholder="Masukkan Katalaluan" name="Katalaluan" required>
        
   <button type="submit"><a href="Plog1.php">LOG MASUK</a></button>

	 <tr>
		   
		  
    <button type="button"   class="cancelbtn" ><a href="mainmenu.php">Kembali Ke Menu Utama</a></button>
			   <td colspan align = "center"><a href = "login.php">English Version?</a><td>
	</tr>
  </div>


    
  </div>
</form>

</body>
</html>
