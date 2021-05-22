<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>lab3 daalgawar</title>
</head>
<body>
	<h3>1. Дараах даалгавруудад тохирох HTML5 элементүүдийг бич</h3>
	<h4>a) Сурагчид хоолны газрын үйлчилгээг 1-10 үнэлгээгээр үнэлж, дундаж оноо нь 7 гэж
    гарав. Meter элементийг тексттэй хослуулан дундаж үнэлгээг харуул.</h4>
    0 <meter min="0" max="10" value="7"></meter>10
    <p>Сурагчдын хоолны газарт өгсөн үнэлгээ дунджаар 7 гарсан байна</p>
    <h4>b)Хүнийнэрийгоруулахтекстэлементийгхаруул.Энэтекстталбарньхуудасачаалагдангуут автоматаар идэвхижидэг байна</h4>
    <form method="post">
    	<input type="hidden" name="recipient" value="first name">
    	<input type="hidden" name="redirect" value="last name">
    	<p><label>First name
    		<input type="text" name="Firs name" size="25" maxlength="30">
    	</label></p>
    	<p><label>Last name
    		<input type="text" name="Last name" size="25" maxlength="30">
    	</label></p>
    	<p>
    		<input type="submit" name="sent">
    	</p>
    </form>
    <h4>c)5 аймгийг автоматаар оруулах боломжтой  жагсаалтыгdatalist ашиглан хий.</h4>
    <p><label for="txtlist">Аймгууд:
    <input type="text" name="txtlist" placeholder="Аймаг сонгох" list="strict" />
    <datalist id="strict">
    	<option value="Ховд">
    	<option value="Булган">
    	<option value="Увс">
    	<option value="Завхан">
    	<option value="Дархан">
    </datalist>
    </label></p>
    <h4>d)Хэрэглэгчид1-ээс100хүртэлхтоогсонгохболомжийголгодогоролтынэлементийгүүсгэ.</h4>
    <label>Дугаар
    	<input type="number"
    	    min="1"
    	    max="100"
    	    step="1"
    	    value="1">
    </label>(1-100 хүртэлх тоо сонго)
    <h4>e)Формыг автоматаар бөглөхийг зөвшөөрдөггүй болго.</h4>
     <form autocomplete="off">autocomplete="off"
    	<input type="hidden" name="recipient" value="first name">
    	<input type="hidden" name="redirect" value="last name">
    	<p><label>First name
    		<input type="text" name="First name" size="25" maxlength="30">
    	</label></p>
    	<p><label>Last name
    		<input type="text" name="Last name" size="25" maxlength="30">
    	</label></p>
    	<p>
    		<input type="submit" name="sent">
    	</p>
    </form>
    <h4>f)Дараах праграфаас 2 дахь өгүүлбэрийг mark элементашиглан тодосго.</h4>
    <p>Оюутнуудхоолныгазрынүйлчилгээг1-10үнэлгээгээрүнэлжээ.<mark>Дундажүнэлгээ нь 7 байв.</mark></p>
    <h3>2.(Бүртгэлийнформ)Хэрэглэгчийновог,нэр,emailхаягзэргийгавдагбүртгэлийнформүүсгэх.Detailsэлемэнтдээрхэрэглэгчээсхэддүгээркурсыноюутангэдгийгсонголтоор(1–ркурс,2-ркурс...) авах боломжтой байхаар гүйцэтгэ.</h3>
    <p><label for="text">Нэр:
    	<input type="text" name="name" placeholder="Өөрийн нэр" />
    </label>(Нэр)</p>
    <p><label for="text">Овог:
    	<input type="text" name="name" placeholder="Эцгийн нэр" />
    </label>(Овог)</p>
    <p><label for="text">Имэйл хаяг:
    	<input type="text" name="email" placeholder="email" />
    </label>(num.stud.edu.mn)</p>
    <p><label for="textlist">Түвшин:
    	<input type="textlist" name="name" placeholder="Курс" list="class" />
    	<datalist id="class">
    		<option value="1">
    		<option value="2">
    		<option value="3">
    		<option value="4">	
    	</datalist>
    </label>(Курс)</p>
    <h3>3.(Autocompleteбүхийформ)input-нsearchтөрлийгашигланэнгийнхайлтынформүүсгэ.Угталбартаа“Даваа”гэжбичээдилгээхтовчыгдар.Дараань“Д”үсэгбичихэдөмнөньоруулсан“Даваа” гэдэг үг гарч ирж байгаа эсэхийг шалга.</h3>
    <form autocomplete="on">
    	<p><label>Гараг:
    		<input type="search" name="day" placeholder="Гараг" list="search" />
    	</label></p>
    	<datalist id="search">
    		<option value="Даваа">
    		<option value="Мягмар">
    		<option value="Лхагва">
    		<option value="Пүрэв">
    		<option value="Баасан">
    	</datalist>
    	<p>
    		<input type="submit" name="sent">
    	</p>
    </form>
    <h3>4.(Datalistбүхийautocompleteформ)Долоохоногийннэрсийгавтоматаароруулахболомжтойdatalist бүхий форм үүсгэ.</h3>
    <form autocomplete="on">
    	<p><label>Гараг:
    		<input type="search" name="day" placeholder="Гараг" list="search" />
    	</label></p>
    	<datalist id="search">
    		<option value="Даваа">
    		<option value="Мягмар">
    		<option value="Лхагва">
    		<option value="Пүрэв">
    		<option value="Баасан">
    		<option value="Хагассайн">
    		<option value="Бүтэнсайн">
    	</datalist>
    </form>
    <h3>5.Номныхуудсуудыгагуулсанхэсгүүдийгүүсгэ.HTML5-н хуудасны бүтцийн элементүүдийг ашиглан номныхуудсыг хий.</h3>
    <header>
    	<img src="Monfa.png" alt="monfa logo">
    	<h3>Эрүүл мэндийн зөвлөгөө.</h3>
    	<time>2021-2-29</time>
    </header> 
    <nav>
    	<h4>Эрүүл мэндийн зөвлөгөөнүүд.</h4>
    	<ul>
    		<li><a href="https://monfatrade.mn/нүдний-болор-цайх-эмгэг-гэж-юу-вэ/">НҮДНИЙ БОЛОР ЦАЙХ ЭМГЭГ ГЭЖ ЮУ ВЭ?</a></li>
    		<li><a href="https://monfatrade.mn/хүүхэд-тураал-юунаас-болдог-вэ-ямар-ар/">ХҮҮХДИЙН ТУРААЛ ЮУНААС БОЛДОГ ВЭ? ЯМАР АРГА ХЭМЖЭЭ АВАХ ВЭ?</a></li>
    		<li><a href="https://monfatrade.mn/рахит-буюу-сульдаа-өвчин-үүсэх-үндсэн/">Рахит буюу сульдаа өвчин үүсэх үндсэн шалтгаан, хэрхэн эмчлэх вэ?</a></li>
    		<li><a href="https://monfatrade.mn/коронавирус-болон-covid-19-та-юу-мэдэх-ёстой/">Коронавирус болон COVID-19: ТА ЮУ МЭДЭХ ЁСТОЙ ВЭ?</a></li>
    	</ul>
    </nav> 
    <figure>
    	<img src="kalium.png" alt="Калигийн ач тус">
    	<figcaption><em>Калид агуулагдах</em>хүнсний бүтээгдэхүүнүүд</figcaption>
    </figure> 
    <article>
    	<header>
    		<em>
    			<a href="http://www.gatsuurt.mn/бүтээгдэхүүнүүд/хүнс/хүнсний-ногоо/">Хүнсний ногоо</a>
    		</em>
    	</header>
    	<p>Хүнсний тухай:</p>
    	    <ul>
    	    	<li>Хаш нь улаан эд ихээр агуулдаг. Эд эсийн өвчлөлтийг зогсоох ба нимбэгийн хүчил, алимны хүчлээр баялаг тул халуун бууруулж хордлогыг тайлж, элгийг хамгаалж, шээсийг тэтгэх сайн талтай. Сайхан амталж чадвал махыг ч орлож чадах увидастай. </li>
    	    	<li>Эрдэнэшиш нь нүүрс ус, тос, уураг агуулах бөгөөд кали, фосфор, манган, фолийн хүчил болон пантотены хүчлээр баялаг. Эрдэнэшиш нь эслэг болон фолийн хүчлээр баялаг тул бүдүүн гэдэсний хорт хавдар болон зүрх судасны өвчний эрсдэлийг бууруулах ач тустай. <mark>Эрүүл мэнд талаас</mark></li>
    	    </ul>
    	    <details>
    	    	<summary>Эмийн заавраар</summary>
                Цус багадалт, элэг эмчлэх, аминдэмийн дутмагшилыг нөхөх, дархлаа  дэмжих сироп
                <ul>
                	<li>Хэрэглэх заалт<strong>&dashТөмөр дутмагшилын цус багадалтыг эмчлэх, урьдчилан сэргийлэх</strong></li>
                </ul>
    	    </details>
    </article>
</body>
</html>
