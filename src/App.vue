<template>
  <breadcrumbs/>
  <main>
    <div class="container"><h1>Комплекты стеллажных систем</h1></div>
    <catalog/>
  </main>
</template>

<script>
import breadcrumbs from './components/breadcrumbs.vue'
import catalog from './components/catalog.vue'

export default {
  name: 'App',
  components: {
    breadcrumbs,
    catalog
  }
}
</script>

<style>
html {
  line-height: 1.15; /* 1 */
  -webkit-text-size-adjust: 100%; /* 2 */
}
body {
  margin: 0;
}
main {
  display: block;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
hr {
  box-sizing: content-box; /* 1 */
  height: 0; /* 1 */
  overflow: visible; /* 2 */
}
pre {
  font-family: monospace, monospace; /* 1 */
  font-size: 1em; /* 2 */
}
a {
  background-color: transparent;
}
abbr[title] {
  border-bottom: none; /* 1 */
  text-decoration: underline; /* 2 */
  text-decoration: underline dotted; /* 2 */
}
b,
strong {
  font-weight: bolder;
}
code,
kbd,
samp {
  font-family: monospace, monospace; /* 1 */
  font-size: 1em; /* 2 */
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sub {
  bottom: -0.25em;
}
sup {
  top: -0.5em;
}
img {
  border-style: none;
}
button,
input,
optgroup,
select,
textarea {
  font-family: inherit; /* 1 */
  font-size: 100%; /* 1 */
  line-height: 1.15; /* 1 */
  margin: 0;/* 2 */
  max-width: 100%;
}
button,
input { /* 1 */
  overflow: visible;
}
button,
select { /* 1 */
  text-transform: none;
}
button,
[type="button"],
[type="reset"],
[type="submit"] {
  -webkit-appearance: button;
}
button::-moz-focus-inner,
[type="button"]::-moz-focus-inner,
[type="reset"]::-moz-focus-inner,
[type="submit"]::-moz-focus-inner {
  border-style: none;
  padding: 0;
}
button:-moz-focusring,
[type="button"]:-moz-focusring,
[type="reset"]:-moz-focusring,
[type="submit"]:-moz-focusring {
  outline: 1px dotted ButtonText;
}
fieldset {
  padding: 0.35em 0.75em 0.625em;
}
legend {
  box-sizing: border-box; /* 1 */
  color: inherit; /* 2 */
  display: table; /* 1 */
  max-width: 100%; /* 1 */
  padding: 0; /* 3 */
  white-space: normal; /* 1 */
}
progress {
  vertical-align: baseline;
}
textarea {
  overflow: auto;
}
[type="checkbox"],
[type="radio"] {
  box-sizing: border-box; /* 1 */
  padding: 0; /* 2 */
}
[type="number"]::-webkit-inner-spin-button,
[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
[type="search"] {
  -webkit-appearance: textfield; /* 1 */
  outline-offset: -2px; /* 2 */
}
[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
::-webkit-file-upload-button {
  -webkit-appearance: button; /* 1 */
  font: inherit; /* 2 */
}
details {
  display: block;
}
summary {
  display: list-item;
}
template {
  display: none;
}
[hidden] {
  display: none;
}
@font-face {
    font-family: 'SF UI Text';
    src: url('assets/fonts/SFUIText-Regular.eot');
    src: local('SF UI Text Regular'), local('SFUIText-Regular'),
        url('assets/fonts/SFUIText-Regular.eot?#iefix') format('embedded-opentype'),
        url('assets/fonts/SFUIText-Regular.woff2') format('woff2'),
        url('assets/fonts/SFUIText-Regular.woff') format('woff'),
        url('assets/fonts/SFUIText-Regular.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;
}
@font-face {
    font-family: 'SF UI Text';
    src: url('assets/fonts/SFUIText-Medium.eot');
    src: local('SF UI Text Medium'), local('SFUIText-Medium'),
        url('assets/fonts/SFUIText-Medium.eot?#iefix') format('embedded-opentype'),
        url('assets/fonts/SFUIText-Medium.woff2') format('woff2'),
        url('assets/fonts/SFUIText-Medium.woff') format('woff'),
        url('assets/fonts/SFUIText-Medium.ttf') format('truetype');
    font-weight: 500;
    font-style: normal;
}
@font-face {
    font-family: 'SF Pro Display';
    src: url('assets/fonts/SFProDisplay-Semibold.eot');
    src: local('SF Pro Display Semibold'), local('SFProDisplay-Semibold'),
        url('assets/fonts/SFProDisplay-Semibold.eot?#iefix') format('embedded-opentype'),
        url('assets/fonts/SFProDisplay-Semibold.woff2') format('woff2'),
        url('assets/fonts/SFProDisplay-Semibold.woff') format('woff'),
        url('assets/fonts/SFProDisplay-Semibold.ttf') format('truetype');
    font-weight: 600;
    font-style: normal;
}
img {
	max-width: 100%;
	height: auto;
}
.container {
  width:calc(100% - 100px);
  max-width: 1488px;
  padding-left: 50px;
  padding-right: 50px;
  margin:0 auto;
}
@media (max-width: 768px) {
  .container {
    width:calc(100% - 40px);
    padding-left: 20px;
    padding-right: 20px;
  }
}
body {
  font-family: 'SF UI Text';
  font-size: 16px;
}
h1 {
  font-family: 'SF Pro Display';
  font-weight: 600;
  font-size: 36px;
  line-height: 1.33em;
}
@media (max-width: 960px) {
  h1 {font-size: 24px;}
}
@media (max-width: 600px) {
  h1 {font-size: 18px;}
}
main {
  margin-top: 20px;
}
</style>
