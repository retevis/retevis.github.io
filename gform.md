<style type="text/css">
    fieldset {
        border-width: 0;
    }
/* Стили модального окна и содержания 
-------------------------------------------------------------------------------*/
 
/* слой затемнения */
 
.dm-overlay {
    position: fixed;
    top: 0;
    left: 0;
    background: rgba(0, 0, 0, 0.65);
    display: none;
    overflow: auto;
    width: 100%;
    height: 100%;
    z-index: 1000;
}
/* активируем модальное окно */
 
.dm-overlay:target {
    display: block;
    -webkit-animation: fade .6s;
    -moz-animation: fade .6s;
    animation: fade .6s;
}
/* блочная таблица */
 
.dm-table {
    display: table;
    width: 100%;
    height: 100%;
}
/* ячейка блочной таблицы */
 
.dm-cell {
    display: table-cell;
    padding: 0 1em;
    vertical-align: middle;
    text-align: center;
}
/* модальный блок */
 
.dm-modal {
    display: inline-block;
    padding: 20px;
    max-width: 50em;
    background: #607d8b;
    -webkit-box-shadow: 0px 15px 20px rgba(0, 0, 0, 0.22), 0px 19px 60px rgba(0, 0, 0, 0.3);
    -moz-box-shadow: 0px 15px 20px rgba(0, 0, 0, 0.22), 0px 19px 60px rgba(0, 0, 0, 0.3);
    box-shadow: 0px 15px 20px rgba(0, 0, 0, 0.22), 0px 19px 60px rgba(0, 0, 0, 0.3);
    color: #cfd8dc;
    text-align: left;
}
/* изображения в модальном окне */
 
.dm-modal img {
    width: 100%;
    height: auto;
}
/* миниатюры изображений */
 
.pl-left,
.pl-right {
    width: 25%;
    height: auto;
}
/* миниатюра справа */
 
.pl-right {
    float: right;
    margin: 5px 0 5px 15px;
}
/* миниатюра слева */
 
.pl-left {
    float: left;
    margin: 5px 15px 5px 0;
}
/* встраиваемое видео в модальном окне */
 
.video {
    position: relative;
    overflow: hidden;
    padding-bottom: 56.25%;
    height: 0;
}
.video iframe,
.video object,
.video embed {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
/* рисуем кнопарь закрытия */
 
.close {
    z-index: 9999;
    float: right;
    width: 30px;
    height: 30px;
    color: #cfd8dc;
    text-align: center;
    text-decoration: none;
    line-height: 26px;
    cursor: pointer;
}
.close:after {
    display: block;
    border: 2px solid #cfd8dc;
    -webkit-border-radius: 50%;
    -moz-border-radius: 50%;
    border-radius: 50%;
    content: 'X';
    -webkit-transition: all 0.6s;
    -moz-transition: all 0.6s;
    transition: all 0.6s;
    -webkit-transform: scale(0.85);
    -moz-transform: scale(0.85);
    -ms-transform: scale(0.85);
    transform: scale(0.85);
}
/* кнопка закрытия при наведении */
 
.close:hover:after {
    border-color: #fff;
    color: #fff;
    -webkit-transform: scale(1);
    -moz-transform: scale(1);
    -ms-transform: scale(1);
    transform: scale(1);
}
/* варианты фонвой заливки модального блока */
 
.green {
    background: #388e3c!important;
}
.cyan {
    background: #0097a7!important;
}
.teal {
    background: #00796b!important;
}
/* движуха при появлении блоков с содержанием */
 
@-moz-keyframes fade {
    from {
        opacity: 0;
    }
    to {
        opacity: 1
    }
}
@-webkit-keyframes fade {
    from {
        opacity: 0;
    }
    to {
        opacity: 1
    }
}
@keyframes fade {
    from {
        opacity: 0;
    }
    to {
        opacity: 1
    }
}
</style>

<a href="#win1" class="btn">Открыть окно 1</a>

<div class="dm-overlay" id="win1">
    <div class="dm-table">
        <div class="dm-cell">
            <div class="dm-modal">
                <a href="#close" class="close"></a>
                <form action="https://docs.google.com/forms/d/e/1FAIpQLSf00HGPk5iyFc0tTRzXm5vwf_tV71G5pxZPzHFHxGyOBSyDzA/formResponse"
      target="_self"
      id="bootstrapForm"
      method="POST">



    <!-- Field type: "short" id: "1545541244" -->
    <fieldset>
        <legend for="1545541244">url</legend>
        <div class="form-group">
            <input id="153061937" type="text" name="entry.153061937" class="form-control" >
        </div>
    </fieldset>


    <!-- Field type: "choices" id: "1666390864" -->
    <fieldset>
        <legend for="1666390864">Доставка</legend>
        <div class="form-group">
            <div class="radio">
                <label>
                    <input type="radio" name="entry.1816347450" value="Укрпошта" required>
                    Укрпошта
                </label>
            </div>
            <div class="radio">
                <label>
                    <input type="radio" name="entry.1816347450" value="Нова пошта" required>
                    Нова пошта
                </label>
            </div>
            <div class="radio">
                <label>
                    <input type="radio" name="entry.1816347450" value="Justin" required>
                    Justin
                </label>
            </div>
        </div>
    </fieldset>


    <!-- Field type: "short" id: "922137472" -->
    <fieldset>
        <legend for="922137472">Номер відділення</legend>
        <div class="form-group">
            <input id="177585775" type="text" name="entry.177585775" class="form-control" required>
        </div>
    </fieldset>


    <!-- Field type: "short" id: "1469063189" -->
    <fieldset>
        <legend for="1469063189">Місто</legend>
        <div class="form-group">
            <input id="568876291" type="text" name="entry.568876291" class="form-control" required>
        </div>
    </fieldset>


    <!-- Field type: "short" id: "370660783" -->
    <fieldset>
        <legend for="370660783">Прізвище Ім&#x27;я По-батькові</legend>
        <div class="form-group">
            <input id="209201751" type="text" name="entry.209201751" class="form-control" required>
        </div>
    </fieldset>


    <!-- Field type: "short" id: "1431848471" -->
    <fieldset>
        <legend for="1431848471">Номер телефону</legend>
        <div class="form-group">
            <input id="1879794114" type="text" name="entry.1879794114" class="form-control" required>
        </div>
    </fieldset>

    <input type="hidden" name="fvv" value="1">
    <input type="hidden" name="fbzx" value="1188019347611234595">
    <!--
        CAVEAT: In multipages (multisection) forms, *pageHistory* field tells to google what sections we've currently completed.
        This usually starts as "0" for the first page, then "0,1" in the second page... up to "0,1,2..N" in n-th page.
        Keep this in mind if you plan to change this code to recreate any sort of multipage-feature in your exported form.
        We're setting this to the total number of pages in this form because we're sending all fields from all the section together.
    -->
    <input type="hidden" name="pageHistory" value="0">

    <input class="btn btn-primary" type="submit" value="Submit">
</form>
            </div>
        </div>
    </div>
</div>





<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.form/4.2.2/jquery.form.min.js" integrity="sha256-2Pjr1OlpZMY6qesJM68t2v39t+lMLvxwpa8QlRjJroA=" crossorigin="anonymous"></script>
<script type="text/javascript">
    // This script requires jQuery and jquery-form plugin
// You can use these ones from Cloudflare CDN:
// 
//
$('#bootstrapForm').submit(function (event) {
    event.preventDefault()
    var extraData = {}
    $('#bootstrapForm').ajaxSubmit({
        data: extraData,
        dataType: 'jsonp',  // This won't really work. It's just to use a GET instead of a POST to allow cookies from different domain.
        error: function () {
            // Submit of form should be successful but JSONP callback will fail because Google Forms
            // does not support it, so this is handled as a failure.
            alert('Form Submitted. Thanks.')
            // You can also redirect the user to a custom thank-you page:
            window.location = 'https://retevis.com.ua/'
        }
    })
})
</script>
