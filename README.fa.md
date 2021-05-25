<p dir="rtl">اگه روی دستگاهت گیت نداری.
<a href="https://help.github.com/articles/set-up-git/"> نصبش کن</a>.</p>
<h2 dir="rtl">
<a id="user-content-این-ریپوزیتوری-رو-فورک-کن" class="anchor" href="#%D8%A7%DB%8C%D9%86-%D8%B1%DB%8C%D9%BE%D9%88%D8%B2%DB%8C%D8%AA%D9%88%D8%B1%DB%8C-%D8%B1%D9%88-%D9%81%D9%88%D8%B1%DA%A9-%DA%A9%D9%86" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>این ریپوزیتوری رو فورک کن</h2>
<p dir="rtl">این ریپوزیتوری رو از طریق کلیک کردن روی دکمه فورک بالای این صفحه فورک کن
این کار یک کپی از ریپوزیتوری تو اکانتت میسازه</p>
<img style="float: left;" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

<h2 dir="rtl">
<a id="user-content-ریپپوزیتوری-رو-کلون-کن" class="anchor" href="#%D8%B1%DB%8C%D9%BE%D9%BE%D9%88%D8%B2%DB%8C%D8%AA%D9%88%D8%B1%DB%8C-%D8%B1%D9%88-%DA%A9%D9%84%D9%88%D9%86-%DA%A9%D9%86" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>ریپپوزیتوری رو کلون کن</h2>
<p dir="rtl">حالا ریپ و رو داخل کامپیوترت کلون کن. روی دکمه کلون کلیک کن و بعد روی (کپی در کلیپبورد) کلیک کن</p>
<img style="float: left;" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />
<img style="float: left;" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

<p dir="rtl">ترمینال رو باز کن و دستورات زیر رو وارد کن</p>
<pre><code>git clone "لینکی که کپی کردی"
</code></pre>
<p dir="rtl">جایی که (لینکی که کپی کردی) هست درواقع آدرس ریپوزیتوری هست که تو قدم پیش دیدی</p>

<p dir="rtl">برای مثال</p>
<pre><code>git clone https://github.com/this-is-you/contributions.git
</code></pre>
<p dir="rtl">داخل لینک بجای
<code>this-is-you</code>
نام کاربری گیتهاب خودت رو قرار بده
تو این مرحله داری محتویات ریپوزیتوری رو از گیتهاب کپی میکنی تو کامپیوتر خودت</p>
<h2 dir="rtl">
<a id="user-content-برنچ-شاخه-بساز" class="anchor" href="#%D8%A8%D8%B1%D9%86%DA%86-%D8%B4%D8%A7%D8%AE%D9%87-%D8%A8%D8%B3%D8%A7%D8%B2" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>برنچ (شاخه) بساز</h2>
<p dir="rtl">اگه هنوز داخل پوشه ریپوزیتوری نیستی. برو داخلش</p>
<pre><code>cd contributions
</code></pre>
<p dir="rtl">حالا با استفاده از دستور
<code>git checkout</code>
یک برنچ جدید بساز</p>
<pre><code>git checkout -b &lt;add-your-name&gt;
</code></pre>
<p dir="rtl">برای مثال</p>
<pre><code>git checkout -b rmros
</code></pre>
<p dir="rtl">لازم نیست کلمه
<code>add</code>
رو اول اسم برنچ بنویسی اما از اونجا که هدف از ساخت این برنچ اضافه کردن اسمت به لیست هست کار منطقی ای هست</p>
<h2 dir="rtl">
<a id="user-content-تغیرات-ضروری-رو-انجام-بده-و-کامیت-کن" class="anchor" href="#%D8%AA%D8%BA%DB%8C%D8%B1%D8%A7%D8%AA-%D8%B6%D8%B1%D9%88%D8%B1%DB%8C-%D8%B1%D9%88-%D8%A7%D9%86%D8%AC%D8%A7%D9%85-%D8%A8%D8%AF%D9%87-%D9%88-%DA%A9%D8%A7%D9%85%DB%8C%D8%AA-%DA%A9%D9%86" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>تغیرات ضروری رو انجام بده و کامیت کن</h2>
<p dir="rtl">حالا فایل
<code>Contributors.md</code>
رو داخل تکست ایدتور باز کن و اسمت رو به آخر فایل اضافه ک. بعد فابل رو ذخیره کن. اگه حالا وارد پوشه پروژه بشی و دستور
<code>git status</code>
رو اجرا کنی. میبینی که تغیرات اونجاست. حالا اون تغیرات رو به برنچی که ساختی اضافه کن با استفاده از دستور
<code>git add</code></p>
<pre><code>git add Contributors.md
</code></pre>
<p dir="rtl">حالا اون تغیرات با استفاده از دستور زیر کامیت کن
<code>git commit</code></p>
<pre><code>git commit -m "Add &lt;your-name&gt; to Contributors list"
</code></pre>
<p dir="rtl">جای
<code>&lt;your-name&gt;</code>
رو با اسم خودت عوض کن</p>
<h2 dir="rtl">
<a id="user-content-تغیرات-رو-به-گیتهاب-پوش-کن" class="anchor" href="#%D8%AA%D8%BA%DB%8C%D8%B1%D8%A7%D8%AA-%D8%B1%D9%88-%D8%A8%D9%87-%DA%AF%DB%8C%D8%AA%D9%87%D8%A7%D8%A8-%D9%BE%D9%88%D8%B4-%DA%A9%D9%86" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>تغیرات رو به گیتهاب پوش کن</h2>
<p dir="rtl">با استفاده از دستور زیر تغیراتت رو به گیتهاب پوش کن
<code>git push</code></p>
<pre><code>git push origin &lt;add-your-name&gt;
</code></pre>
<p dir="rtl">اسم
<code>&lt;add-your-name&gt;</code>
رو با اسم برنچی که ساخته بودی عوض کن</p>
<h2 dir="rtl">
<a id="user-content-تغیراتت-رو-برای-برسی-ثبت-کن" class="anchor" href="#%D8%AA%D8%BA%DB%8C%D8%B1%D8%A7%D8%AA%D8%AA-%D8%B1%D9%88-%D8%A8%D8%B1%D8%A7%DB%8C-%D8%A8%D8%B1%D8%B3%DB%8C-%D8%AB%D8%A8%D8%AA-%DA%A9%D9%86" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>تغیراتت رو برای برسی ثبت کن</h2>
<p dir="rtl">اگه بری داخل ریپوزیتوریت تو گیتهاب. میبینی که دکمه
<code>Compare &amp; pull request</code>
وجود داره . روش کلیک کن</p>

<img style="float: left;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

<p dir="rtl">حالا دستور پل رو ثبت کن</p>
<img style="float: left;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

<p dir="rtl">ali habibi</p>