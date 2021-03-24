# vs.Nav

Very simple, responsive CSS & Vanilla Javascript navigation (menu)...
CSS Animations --- custom or Animate.css

### Stand-alone Example

```html
<div id="vs-nav-container">
    <ul id="vs-nav">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li>
            <a href="#">Categories</a>
            <ul>
                <li><a href="">Category 1</a></li>
                <li><a href="">Category 2</a></li>
                <li><a href="">Category 3</a></li>
            </ul>
        </li>
        <li><a href="#">Contact</a></li>
    </ul>
    <div id="vs-nav-mobile-icon">
        <span></span>
        <span></span>
        <span></span>
    </div>
</div>
```

### Example in Wordpress template ...

```php
wp_nav_menu([
            'theme_location' => '<...theme-location...>',
            'container_id' => 'vs-nav-container',
            'menu_id' => 'vs-nav',
            'item_spacing' => 'discard'
            ]);
```

## License

MIT
