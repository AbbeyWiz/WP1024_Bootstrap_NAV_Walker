# WP1024_Bootstrap_NAV_Walker

> A custom WordPress nav walker class to implement the Bootstrap 3 navigation style in a custom theme using the WordPress built in menu manager.

## Clone 

```
git clone git@github.com:ckwen/WP1024_Bootstrap_NAV_Walker.git

git clone https://github.com/ckwen/WP1024_Bootstrap_NAV_Walker.git
```

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