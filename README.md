<html>
<head>
	<link rel="icon" type="image/jpg" href="photos\7-Inspiring-books.jpg"> 
    <title> HTML kodlari </title>
	<meta charset="utf-8">
	<meta name="author" content="Usmonjon" />
	<meta name="description" content="HTML ning barcha kodlaridan amaliy foydalanilgan sahifa">
	<meta name="keywords" content="HTML kodlari, web Dasturlash, html">
</head>
<body>
    
    <h2 id="top" align="center"> 				
   		HTML ning barcha teglari 
    </h2>
    
    <p>
       Paragraf(sarlavha) tegi
    </p>
    
   <h2> Sarlavha o'lchamlari </h2>
    <h3> Sarlavha o'lchamlari </h3>
    <h6> Sarlavha o'lchamlari </h6>

<hr size="8" color="green">
    <p> Rasm qo'yish: </p>
    	<img src="photos\11.jpg" width="240" height="140" alt="Bu yerda rasm bor edi"><br>

    	<img width="240" height="140" src="photos\7-Inspiring-books.jpg">

    <p> Rasmga link qo'yish: </p>
    	<a title="google.com" href="http://google.com">
    	<img width="240" height="140" src="photos\7-Inspiring-books.jpg" >
    </a>
<hr>
    <p> Fraza elementlari(so'zni ajratib ko'rsatish): </p>
    	<b>Bold</b><br>
    	<i>Italik</i><br>
    	<s>Strike</s><br>
    	<u>Underline</u><br>
<hr>

    <ul><caption> Tartiblanmagan ro'yhat: </caption>
    	<li type="disc">Bjarne stroustrup</li>
    		<ul>
    			<li type="circle">1980-yilda C++</li>
    		</ul>
    	<li type="square">kvadrat</li>
    </ul>

<hr>

    <ol start="3"><caption>Tartiblangan ro'yhat</caption>
    	<li type="I">Rim raqami</li>
    	<li>12345</li>
    	<li type="A">ABS</li>
    	<li type="a">abs</li>
    </ol>

    <ol type="1" reversed start="7"><caption>Yuqoridan pastga o'sish tartibida</caption>
    	<li>C#</li>
    	<li>C++</li>
    	<li>Java</li>
    	<li>Python</li>
    </ol>
<hr>
	<p>Ta'riflar ro'yhati:</p>
		<dl>
			<dt>HTML:</dt>
			<dd> Asoschisi Tim Beners Li</dd>
			<dt>C++:</dt>
			<dd>Bjarne Stroustrup</dd>
		</dl>
<hr>
	<table cellpadding="15" width="500" border="10" cellspacing="2" ><caption>Jadval tuzish</caption>
		<tr>
			<th>Jadvalning yuqori qismi </th>
			<th>Dasturlash tillari </th>
		</tr>
		
		<tr>
			<td>1-satr</td>
			<td>C++-satr</td>
		</tr>

		<tr>
			<td>2-satr</td>
			<td>Java</td>
		</tr>
	
	</table>
<hr>	
	<blockquote>
	<p> Sitatalar( Quotation )</p>
		Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		tempor <q>incididunt ut labore et dolore magna aliqua.</q> 

    	Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    	tempor <q>incididunt ut labore et dolore magna aliqua.</q> <!-- bu tegdan foydalanishning asosiy maqsadi keyinchalik stillar bilan ishlaganda bu kontentni alohida rangda, alohida shriftda chop etishni istasak avtomatik tarxda bir vaqtda barchasiga ta'sir o'tkazishimiz mumkin bo'ladi--> 
    </blockquote>	
<hr>
	<p>Belgilarning ifodalanishi</p>
		
		&lt;<br>
		&gt;<br>
		&trade;<br>
		&copy;<br>
		&quot;<br>
		&pi;<br>
		&delta;<br>
		&gamma;<br>
		&beta;<br>
		&Delta;<br>
		&amp;<br>
		&#1048;<br>
		&nbsp;<br>
<hr>		
	<p>PRE va CODE teglari</p>
		HTML da <code> blockquote </code> tegi orqali sitatalar tuziladi

		<pre> qanday yozilsa        shundayligicha      probellar bilan qabul qilish</pre>
<hr>
	<p>Kodlarni ham yozuv sifatida oladi:</p>
	<xmp>

		<p> 
			<strong>Lorem ipsum dolor sit amet,</strong> consectetur adipisicing elit, <b>sed do eiusmod</b>
			tempor incididunt ut labore et dolore magna aliqua.
		</p>
	</xmp>
<hr>
	<h3>Block va qator elementlari</h3>
		<div>
			<h4>Block_1</h4>
				Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		</div>
		<p>
			<h4>Block_2</h4>
				Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		</p>
		<article>
			<h4>Block_3</h4>
				Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod 
		</article>
<hr>
	<h3>Formalar bilan ishlash</h3>			
		<form action="links/2_1.html">
			<input type="text" placeholder="So'rovni kiriting" name="submit">
			<input type="submit" value="Qidiruv" name="Qidiruv">
		</form>
<hr>
	<h4>Form - Register</h4>		
	<form>
		<label>Email<br>
			<input type="email" name="email" placeholder="username@mail.com"></label><br>

		<label>Parol<br>
			<input type="password" name="password" placeholder="Parol"></label><br>
		
		<p><label>
			Jinsingiz:<br>
			<input type="radio" name="gender" value="male" id="male"><label for="male">Erkak</label>

			<input type="radio" name="gender" value="female" id="female"><label for="female">Ayol</label>
			<!-- Bu shaklda yozuv ustiga bosganimizda ham qabul qiladi-->
		</label><br>

		<p><label>
			Jinsingiz:<br>
			<input type="radio" name="gender" value="male">Erkak
				
			<input type="radio" name="gender" value="female">Ayol
			<!-- Bu shakldan foydalanganimizda faqat belgi ustiga bosganimizda qabul qiladi-->
		</label>

		<p><label> Tug'ilgan kun<br>
			<input type="date" name="birthday"><br>
		</label>

		<label>
			<p>Qiziqadigan fanlaringiz</p>

			<input type="checkbox" name="subject" value="Dasturlash tillari" id="dasturlash tillari"><label for="dasturlash tillari">Dasturlash tillari<br>

			<input type="checkbox" name="subject" value="Kompyuter tizimlari" id="kompyuter tizimlari"><label for="kompyuter tizimlari">Kompyuter tizimlari<br>

			<input type="checkbox" name="subject" value="Web dasturlash" id="web dasturlash"><label for="web dasturlash">Web dasturlash
		</label>

		<p><input type="submit" name="submit" value="Yuborish">

	</form>
<hr>
	<h3>Indeks va daraja</h3>
		H<sub>2</sub>O<br> <!-- Indeksda hosil bo'ladi-->
		ax<sup>2</sup>+bx+c=0 <br> <!-- darajada hosil bo'ladi-->	
<hr>
	<h3>Giperssilkalar bilan ishlash</h3>
		<h4>Sahifada navigatsiya o'rnatish</h4>
			<a href="#top"> Yuqoriga qaytish </a><br>
		<h4>Saytga o'tish</h4>
			<a href="http://www.google.com" target="_blank"> "Google" ga o'tish </a><br> <!-- yangi oyna ochib o'tadi-->
		<h4>Sahifani bog'lash</h4>
			<a href="links\2_1.html"> 2_1 tajriba ishiga o'tish </a><br>
		<h4>Kursorni olib borganda pastki qismida izoh paydo qilish</h4>	
    		<a href="links\2_1.html" title="A tegining Title parametridan foydalanilgan"> Kursorni olib kelganda pastki qismida izoh paydo bo'ladi </a>






	
</body>
</html>
