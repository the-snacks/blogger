# Installing Webfonts
Follow these simple Steps.

## 1.
Put `hind/` Folder into a Folder called `fonts/`.

## 2.
Put `hind.css` into your `css/` Folder.

## 3. (Optional)
You may adapt the `url('path')` in `hind.css` depends on your Website Filesystem.

## 4.
Import `hind.css` at the top of you main Stylesheet.

```
@import url('hind.css');
```

## 5.
You are now ready to use the following Rules in your CSS to specify each Font Style:
```
font-family: Hind-Light;
font-family: Hind-Regular;
font-family: Hind-Medium;
font-family: Hind-SemiBold;
font-family: Hind-Bold;
font-family: Hind-Variable;

```
## 6. (Optional)
Use `font-variation-settings` rule to controll axes of variable fonts:
wght 300.0

Available axes:
'wght' (range from 300.0 to 700.0

