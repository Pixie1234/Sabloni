# Sabloni

<h2>Useful things</h2>

<li><a href="#">Chicago</a> -> href="#" </li> 
<li><a href="javascript:void(0)">Chicago</a> ->href="javascript:void(0) </li> 
We used JavaScript: void(0) above to prevent the page from reloading when the button is clicked the first time.<br>

<h2>1.Армоника</h2>
<script>
    $(function () {
        menu = $("#nav");

    $("#pull").on("click", function (e) {
        e.preventDefault();
        menu.slideToggle();
        });
    });
</script>

<body>
<nav id="collapse">
    <a href="#" id="pull" style="display: block"><!--display: none e za da ne se pojavuva napocetoko listata-->
        <h2>Menu</h2>
    </a>
    <ul id="nav">
        <li><a href="#">Pizza</a></li>
        <li><a href="#">Pasta</a></li>
        <li><a href="#">Burger</a></li>
        <li><a href="#">Drinks</a></li>
    </ul>
</nav>
</body>
