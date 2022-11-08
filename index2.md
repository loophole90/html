<!DOCTYPE html>
<html lang="en">
        <head>
        <meta charset="utf-8">
        </head>
    <body>
        <div class="out1"></div>
        <div class="out2"></div>
        <div class="out3"></div>

        <script>
                let params = (new URL(document.location)).searchParams;
                var a = console.info(params.get("login"));
                var b = console.log(params.get("gmail"));
                var c = console.log(params.get("pass"));
                var v = a+b+c
                document.querySelector('.out1').innerHTML = (params.get("login"));
                document.querySelector('.out2').innerHTML = (params.get("gmail"));
                document.querySelector('.out3').innerHTML = (params.get("pass"));
        </script>
        <form action="C:\Users\Dima\OneDrive\Рабочий стол\САЙТ\index3.html" method="GET">
        <p>Все вірно?</p>
        <button>Так</button>
        </form>
        <form action="C:\Users\Dima\OneDrive\Рабочий стол\САЙТ\index.html" method="GET">
                <button>Hі</button>
        </form>
    </body>
</html>
