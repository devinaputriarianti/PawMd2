<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Purnama Anaking">
    <meta name="keyword" content="Belajar HTML, Belajar Web">
    <meta name="description" content="Praktikum modul 2">
    <meta name="robots" content="index, follow">

    <title>Pengenalan HTML Tingkat Lanjut</title>
</head>

<body>
    <strong>Praktikum Pemrograman Web</strong>
    <hr>

    <h1>Pengenalan HTML Tingkat Lanjut</h1> 
    <hr>

    <!-- Selanjutnya kode HTML Tulis di sini -->

    <br><br>
    <div>
        <hr>
        <strong>Program Studi Sistem Informasi ITTelkom Surabaya</strong>
    </div>

    <div>
        <h2>Element Form</h2>
        <hr>
        <form action="" method="get">
            <!-- Tulis elemen Form di sini -->            
        <p><input type="text" name="text_form" size="20"></p>
        <p><input type="text" name="text_form" size="20" placeholder="Dengan Placeholder"></p>
        <p><input type="text" name="readonly_form" size="20" value="Ini Readonly" readonly></p>
        <p><input type="text" name="disabled_form" value="Ini Disabled" size="20" disabled></p>
        <p><input type="text" name="required_form" size="20" required placeholder="Ini Required"></p>

        <p><input type="email" name="email_form" size="20" placeholder="Ini Email"></p>
        <p><input type="password" name="password_form" size="20" placeholder="Ini Password"></p>
        <p><input type="file" name="file"></p>
        <p><input type="hidden" name="hidden_form" value="123456"></p>

        <p>
            <textarea name="textarea_form" cols="30" rows="5" placeholder="Ini Textarea"></textarea>
        </p>

        <p>
            <select name="pilihan">
                <option value=1>Pilihan 1</option>
                <option value=2 selected>Pilihan 2</option>
                <option value=3>Pilihan 3</option>
                <option value=4>Pilihan 4</option>
                <option value=5>Pilihan 5</option>
            </select>
        </p>

        <p>
            <input type="radio" name="radio" value="radio1" id="radio1" checked><label for="radio1">Radio 1</label>
            <input type="radio" name="radio" value="radio2" id="radio2"><label for="radio2">Radio 2</label>
        </p>

        <p>
            <input type="checkbox" name="checkbox1" value="checkbox1" id="checkbox1"><label for="checkbox1">Checkbox 1</label>
            <input type="checkbox" name="checkbox2" value="checkbox2" id="checkbox2"><label for="checkbox2">Checkbox 2</label>
        </p>

        <p>
            <input type="reset" value="Reset">
            <input type="submit" value="Simpan">
            <input type="button" value="Button" onclick="">
        </p>
        </form>
    </div>

    <div>
        <h2>Element Embed</h2>
        <hr>
        <embed src="assets/file.pdf" width="800" height="1000" type="application/pdf">
    </div>

    <div>
        <h2>Elemen Object</h2>
        <hr>
        <object data="assets/file.pdf" width="800" height="1000" type="application/pdf"></object>
    </div>
    
    <div>
        <h2>Element Iframe</h2>
        <hr>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/QIas1H7H_m0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  
    <div>
        <h2>Element Semantic HTML5</h2>
        <hr>
        <header>Ini Header</header>
        <main>Ini Main</main>
        <section>Ini Section</section>
        <aside>Ini Aside</aside>
        <nav>Ini Nav</nav>
        <footer>Ini Footer</footer>
    </div>

</body>
</html>	

