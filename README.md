# WP1024_Bootstrap_NAV_Walker

> A custom WordPress nav walker class to implement the Bootstrap 3 navigation style in a custom theme using the WordPress built in menu manager.

## Clone 

```
git clone git@github.com:ckwen/WP1024_Bootstrap_NAV_Walker.git

git clone https://github.com/ckwen/WP1024_Bootstrap_NAV_Walker.git
```

## Bootstrap NAV Example

```
<ul class="nav navbar-nav">
    <li class="active"><a href="./index.html">Home</a></li>
    <li><a href="./index.html">WordPress</a></li>
    <li><a href="./index.html">CodeIgniter</a></li>
    <li><a href="./index.html">Python</a></li>
    <li class="dropdown">
        <a href="index.html" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Java <span class="caret"></span></a>
        <ul class="dropdown-menu">
            <li><a href="#">Struts</a></li>
            <li><a href="#">Spring</a></li>
            <li><a href="#">Hibernate</a></li>
            <li><a href="#">MyBatis</a></li>
        </ul>
    </li>
    <li><a href="#">About</a></li>
</ul>
```

[Read more...](./navbar.html)

## Installation


### JavaScript

```
<script type="text/javascript">
$(function () {
    $(document).off('click.bs.dropdown.data-api');
    $('.dropdown').mouseover(function () { $(this).addClass('open'); });
    $('.dropdown').mouseleave(function() { $(this).removeClass('open'); });
});
</script>
```

## Change Log