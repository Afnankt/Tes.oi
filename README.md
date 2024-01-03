<!DOCTYPE html>

<html lang="en">
  <head>
    <title>Online furniture store - Template</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta charset="utf-8" />
    <meta property="twitter:card" content="summary_large_image" />
    <style data-tag="reset-style-sheet">
      html {  line-height: 1.15;}body {  margin: 0;}* {  box-sizing: border-box;  border-width: 0;  border-style: solid;}p,li,ul,pre,div,h1,h2,h3,h4,h5,h6,figure,blockquote,figcaption {  margin: 0;  padding: 0;}button {  background-color: transparent;}button,input,optgroup,select,textarea {  font-family: inherit;  font-size: 100%;  line-height: 1.15;  margin: 0;}button,select {  text-transform: none;}button,[type="button"],[type="reset"],[type="submit"] {  -webkit-appearance: button;}button::-moz-focus-inner,[type="button"]::-moz-focus-inner,[type="reset"]::-moz-focus-inner,[type="submit"]::-moz-focus-inner {  border-style: none;  padding: 0;}button:-moz-focus,[type="button"]:-moz-focus,[type="reset"]:-moz-focus,[type="submit"]:-moz-focus {  outline: 1px dotted ButtonText;}a {  color: inherit;  text-decoration: inherit;}input {  padding: 2px 4px;}img {  display: block;}html { scroll-behavior: smooth  }
    </style>
    <style data-tag="default-style-sheet">
      html {
        font-family: Jost;
        font-size: 16px;
      }

      body {
        font-weight: 400;
        font-style:normal;
        text-decoration: none;
        text-transform: none;
        letter-spacing: 0.02;
        line-height: 1.55;
        color: var(--dl-color-gray-black);
        background-color: var(--dl-color-gray-white);

      }
    </style>
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Jost:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://unpkg.com/@teleporthq/teleport-custom-scripts/dist/style.css"
    />
  </head>
  <body>
    <div id="app"></div>
    <script src="https://unpkg.com/@teleporthq/teleport-custom-scripts"></script>
  </body>
</html>
.blog-post-card-blog-post-card {
  width: 100%;
  display: flex;
  position: relative;
  max-width: 400px;
  align-self: stretch;
  transition: 0.3s;
  flex-direction: column;
  justify-content: space-between;
}
.blog-post-card-blog-post-card:hover {
  transform: scale(1.02);
}
.blog-post-card-image {
  flex: 1;
  width: 100%;
  object-fit: cover;
}
.blog-post-card-container {
  width: 100%;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-halfunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-twounits);
  justify-content: space-between;
  background-color: var(--dl-color-gray-white);
}
.blog-post-card-text {
  color: var(--dl-color-gray-black80);
  font-size: 22px;
  font-style: normal;
  margin-top: var(--dl-space-space-unit);
  font-weight: 500;
  line-height: 28px;
  margin-bottom: var(--dl-space-space-unit);
}
.blog-post-card-text1 {
  color: var(--dl-color-gray-black50);
  font-size: 16px;
  font-style: normal;
  margin-bottom: var(--dl-space-space-twounits);
}

@media(max-width: 991px) {
  .blog-post-card-blog-post-card {
    max-width: 48%;
  }
}
@media(max-width: 767px) {
  .blog-post-card-blog-post-card {
    max-width: 100%;
  }
}
.blog-post-card-blog-post-card {
  width: 100%;
  display: flex;
  position: relative;
  max-width: 400px;
  align-self: stretch;
  transition: 0.3s;
  flex-direction: column;
  justify-content: space-between;
}
.blog-post-card-blog-post-card:hover {
  transform: scale(1.02);
}
.blog-post-card-image {
  flex: 1;
  width: 100%;
  object-fit: cover;
}
.blog-post-card-container {
  width: 100%;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-halfunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-twounits);
  justify-content: space-between;
  background-color: var(--dl-color-gray-white);
}
.blog-post-card-text {
  color: var(--dl-color-gray-black80);
  font-size: 22px;
  font-style: normal;
  margin-top: var(--dl-space-space-unit);
  font-weight: 500;
  line-height: 28px;
  margin-bottom: var(--dl-space-space-unit);
}
.blog-post-card-text1 {
  color: var(--dl-color-gray-black50);
  font-size: 16px;
  font-style: normal;
  margin-bottom: var(--dl-space-space-twounits);
}

@media(max-width: 991px) {
  .blog-post-card-blog-post-card {
    max-width: 48%;
  }
}
@media(max-width: 767px) {
  .blog-post-card-blog-post-card {
    max-width: 100%;
  }
}
