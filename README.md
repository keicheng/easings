# Easings
根據你使用的 CSS Preprocessor，使用不同的變數集，這些變數可使用在 transition-timing-function 以及 animation-timing-function。

### Transition 範例
```css
.less {
    transition-timing-function: @ease;
}

.sass
    transition-timing-function: $ease;

.scss {
    transition-timing-function: $ease;
}

.stylus
    transition-timing-function ease
```

### Animation 範例
```css
.less {
    animation-timing-function: @easeInBack;
}

.sass
    animation-timing-function: $easeInBack;

.scss {
    animation-timing-function: $easeInBack;
}

.stylus
    animation-timing-function easeInBack
```