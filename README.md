# Learn_HTML5

### HTML Images

```
<!-- internal -->
<img src="image/img01.jpg" alt="people" width="120px" height="160px" /> </br>
<!-- external -->
<img
    src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png"
/>
```

adapt

```
<a href="http://www.google.com">
    <img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png">
</a>
```

### Lists

```
<h1>ร้านอาหารอีสาน</h1>
<ol type="I">
    <li>ส้มตำ</li>
    <li>ไก่ย่าง</li>
    <li>ปลาเผา</li>
</ol>
<hr />
<h1>ร้านอาหารใต้</h1>
<ul type="circle">
    <li>ข้าวยำปักษ์ใต้</li>
    <li>สตอผัดกุ้ง</li>
    <li>แกงใตปลา</li>
</ul>
```

### Table

```
<table border="1" cellpadding="10" cellspacing="2">
    <thead>
    <th>รหัสสินค้า</th>
    <th>ภาพสินค้า</th>
    <th>ชื่อสินค้า</th>
    <th>ราคา</th>
    <th>ดำเนินการสั่งซื้อ</th>
    </thead>
    <tbody>
    <tr bgcolor="pink">
        <td>P001</td>
        <td>
        <img
            src="https://cdn.pixabay.com/photo/2016/07/28/19/57/somtum-1549340__340.jpg"
            alt=""
            width="50px"
            height="50"
        />
        </td>
        <td>ส้มตำ</td>
        <td>150.00</td>
        <td><a href="#">สั่งซื้อ</a></td>
    </tr>
    <tr bgcolor="yellow" align="center">
        <td>P002</td>
        <td>
        <img
            src="https://cdn.pixabay.com/photo/2017/03/23/19/57/asparagus-2169305__340.jpg"
            alt=""
            width="50px"
            height="50"
        />
        </td>
        <td>สเต็ก</td>
        <td>200.00</td>
        <td><a href="#">สั่งซื้อ</a></td>
    </tr>
    <tr></tr>
    </tbody>
    <tfoot>
    <tr align="right">
        <td colspan="5">ราคารวม : 500 บาท</td>
    </tr>
    <tr>
        <td rowspan="2"></td>
    </tr>
    <tr>
        <td></td>
    </tr>
    </tfoot>
</table>
```

### div, span

```
<span>kittisak</span>
<span>kittisak</span>
<span>kittisak</span>
<div>kittisak</div>
<div>kittisak</div>
<div>kittisak</div>
```

### HTML Form

```
<form align="left">
    <div>
    <label for="firstname">ชื่อจริง</label>
    <input
        type="text"
        name="fname"
        placeholder="ป้อนชื่อของคุณ (ก-ฮ)"
        required
    />
    </div>

    <div>
    <label for="lastname">นามสกุล</label>
    <input type="text" name="lname" />
    </div>

    <div>
    <label for="email">อีเมล</label>
    <input type="email" name="email" required />
    </div>

    <div>
    <label for="password">รหัสผ่าน</label>
    <input type="password" name="password" />
    </div>

    <div>
    <label for="">ที่อยู่</label>
    <textarea name="" id="" cols="20" rows="5">kittisak</textarea>
    </div>

    <div>
    <label for="password">อายุ</label>
    <input type="number" name="age" min="0" max="10" value="2" readonly />
    </div>

    <div>
    <label for="password">วันเกิด</label>
    <input type="date" name="birthdate" />
    </div>

    <div>
    <label for="password">เบอร์โทรศัพท์</label>
    <input type="tel" name="tel" />
    </div>

    <div>
    <label for="password">สีที่ชอบ</label>
    <input type="color" name="color" />
    </div>

    <div>
    <label for="password">ช่วงตัวเลข</label>
    <input type="range" name="rangenumber" value="5" />
    </div>

    <div>
    <label for="password">ระดับการศึกษา</label>
    <select name="edu" id="">
        <option value="มัธยมศึกษา">มัธยมศึกษา</option>
        <option value="ปริญญาตรี">ปริญญาตรี</option>
        <option value="ปริญญาโท" selected>ปริญญาโท</option>
    </select>
    </div>

    <div>
    <label for="password">เพศ</label>
    <input type="radio" name="gender" />เพศชาย
    <input type="radio" name="gender" />เพศหญิง
    <input type="radio" name="gender" />กำหนดเอง
    </div>

    <div>
    <label for="password">เพศ</label>
    <input type="checkbox" name="fav" />เขียนเว็ป
    <input type="checkbox" name="fav" />สร้างเกมส์
    <input type="checkbox" name="fav" />ซ่อมคอม
    <input type="checkbox" name="fav" />อื่นๆ
    </div>

    <div>
    <label for="password">เว็ปไซต์</label>
    <input type="url" />
    </div>

    <div>
    <button type="submit">บันทึกข้อมูล</button>
    <input type="reset" name="" id="" value="ล้างข้อมูล" />
    </div>

</form>
```

### Block VS Inline

Block

```
<address>
<article>
<aside>
<blockquote>
<canvas>
<dd>
<div>
<dl>
<table>
<dt>
<fieldset>
<figcaption>
<figure>
<footer>
<form>
<h1>-<h6>
<header>
<tfoot>
<hr>
<li>
<main>
<nav>
<noscript>
<ol>
<p>
<pre>
<section>
<tfoot>
<ul>
<video>
```

inline

```
<a>
<abbr>
<acronym>
<b>
<bdo>
<big>
<br>
<button>
<cite>
<code>
<dfn>
<em>
<i>
<img>
<input>
<kbd>
<label>
<map>
<object>
<output>
<q>
<samp>
<script>
<select>
<small>
<span>
<strong>
<sub>
<sup>
<textarea>
<time>
<tt>
<ver>
```
