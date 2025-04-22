<!DOCTYPE html>
<html lang="en"><head>
    <script type="module" src="/@vite/client"></script>

    <meta charset="UTF-8">
    <link rel="icon" type="image/svg+xml" href="/vite.svg">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vite + Vue</title>
  <style type="text/css" data-vite-dev-id="/usr/src/app/src/style.css">:root {
  font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
  line-height: 1.5;
  font-weight: 400;

  color-scheme: light dark;
  color: rgba(255, 255, 255, 0.87);
  background-color: #242424;

  font-synthesis: none;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
html {
  scroll-padding-top: 70px; /* Adjust this value to match the height of your navbar */
}
#app {
  width: 100%;
}

a {
  font-weight: 500;
  color: #0000EE;
  text-decoration: inherit;
}

.header-subtext {
  padding-bottom: 0px !important;
}

.page-container a {
  color: #0000EE !important;
}
a:hover {
  color: #535bf2;
}

body {
  margin: 0;
  display: flex;
  place-items: center;
  min-width: 320px;
  min-height: 100vh;
}

h1 {
  font-size: 3.2em;
  line-height: 1.1;
}

h1, h2, h3, p, table {
  padding-bottom: 15px;
}

button {
  border-radius: 8px;
  border: 1px solid transparent;
  padding: 0.6em 1.2em;
  font-size: 1em;
  font-weight: 500;
  font-family: inherit;
  background-color: #1a1a1a;
  cursor: pointer;
  transition: border-color 0.25s;
}
button:hover {
  border-color: #646cff;
}
button:focus,
button:focus-visible {
  outline: 4px auto -webkit-focus-ring-color;
}

.card {
  padding: 2em;
}

#app {
  text-align: center;
}

@media (prefers-color-scheme: light) {
  :root {
    color: #213547;
    background-color: #ffffff;
  }
  a:hover {
    color: #747bff;
  }
  button {
    background-color: #f9f9f9;
  }
}

.router-link-exact-active {
  background-color: lightgray;
}

.sidebar-container {
  min-width:20%;
  width: 20vw;
  padding-left:15px;
  padding-right: 15px;
  padding-bottom:15px;
}
.container-page {
  width:100%;
}
.content-container {
  padding-left: 50px;
}

.styled-table {
  width: 100%;
  border-collapse: collapse;
}

.styled-table th,
.styled-table td {
  border: 1px solid #ddd;
  padding: 8px;
}

.styled-table th {
  background-color: #f2f2f2;
  text-align: left;
}

.container-page {
  display: flex;
  text-align:left;
  padding-top:20px;
}

.table-container {
  padding-bottom: 15px;
}
</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/components/HelloWorld.vue?vue&amp;type=style&amp;index=0&amp;scoped=e17ea971&amp;lang.css">
.read-the-docs[data-v-e17ea971] {
  color: #888;
}
</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/components/NavBar.vue?vue&amp;type=style&amp;index=0&amp;scoped=c3ceb15a&amp;lang.css">
a[data-v-c3ceb15a] {
  text-decoration: none;
}
.logo-container[data-v-c3ceb15a] {
  padding-right: 0.5rem;
  align-items: center;
  display: flex;
  border-right: solid black 3px;
  margin-right: 0.5rem;
}
#mitre-logo[data-v-c3ceb15a] {
  width: 70px;
}
nav[data-v-c3ceb15a] {
  background-color: #ffffff;
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 1000;
  display: flex; /* Use flexbox for layout */
  justify-content: space-between; /* Space between left and right sections */
  align-items: center; /* Center items vertically */
  border-bottom: solid 1px black;
  height: 60px;
}
.nav-left[data-v-c3ceb15a] {
  display: flex;
  align-items: center;
  padding-left: 1rem;
  cursor: pointer;
}
.nav-right[data-v-c3ceb15a] {
    padding-right: 1rem;
}
.site-name[data-v-c3ceb15a] {
  color: black; 
  font-size: 1.5rem; /* Adjust font size */
  text-decoration: none !important;
}
.nav-right ul[data-v-c3ceb15a] {
  list-style: none;
  display: flex;
  gap: 1rem;
  margin: 0;
  padding: 0;
}
.nav-right li[data-v-c3ceb15a] {
  color: black !important;
}
.nav-right a[data-v-c3ceb15a] {
  color: black;
  text-decoration: none;
}
.nav-right a.router-link-active[data-v-c3ceb15a] {
  font-weight: bold;
}

</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/components/shared/Footer.vue?vue&amp;type=style&amp;index=0&amp;scoped=fc427fd3&amp;lang.css">
.copyright-text[data-v-fc427fd3] {
  padding-bottom: 0px !important;
  margin-bottom: 0px !important;
}
.footer-container[data-v-fc427fd3] {
  background-color: #fff;
  color: black;
  text-align: center;
  position: relative;
  /*bottom: 0;*/
  width: 100%;
  display:flex;
  height: 60px;
  justify-content: space-between;
  border-top: solid black 1px;
  align-items: center;
}
nav[data-v-fc427fd3] {
  background-color: #ffffff;
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 1000;
  display: flex; /* Use flexbox for layout */
  justify-content: space-between; /* Space between left and right sections */
  align-items: center; /* Center items vertically */
  border-bottom: solid 1px black;
  height: 60px;
}
.nav-left[data-v-fc427fd3] {
  display: flex;
  align-items: center;
  padding-left: 1rem;
}
.nav-right[data-v-fc427fd3] {
    padding-right: 1rem;
}
.site-name[data-v-fc427fd3] {
  color: black; 
  font-size: 1.5rem; /* Adjust font size */
  text-decoration: none !important;
}
.nav-right ul[data-v-fc427fd3] {
  list-style: none;
  display: flex;
  gap: 1rem;
  margin: 0;
  padding: 0;
}
.nav-right li[data-v-fc427fd3] {
  color: black;
}
.nav-right a[data-v-fc427fd3] {
  color: black;
  text-decoration: none;
}
.nav-right a.router-link-active[data-v-fc427fd3] {
  font-weight: bold;
}

</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/App.vue?vue&amp;type=style&amp;index=0&amp;scoped=7a7a37b1&amp;lang.css">
.layout[data-v-7a7a37b1] {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
.page-container[data-v-7a7a37b1] {
  margin-top: 60px;
  /*height: calc(100vh - 60px - 60px);*/
  display: flex;
  flex: 1;
  /*width: 100vw;*/
}
body[data-v-7a7a37b1] {
  margin: 0; /* Removes default margin from the body */
  padding-top: 60px; /* Adds padding to prevent content from being hidden under the fixed nav bar */
}
</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/components/Home.vue?vue&amp;type=style&amp;index=0&amp;scoped=08e32229&amp;lang.css">
.separation-border[data-v-08e32229] {
  border-top: 3px gray solid;
  width: 30%;
  margin-top: 30px;
}
.text-container[data-v-08e32229] {
  width: 60%;
}
.homepage-container[data-v-08e32229] {
  text-align: left;
  padding-left: 60px;
  padding-top: 75px;
  padding-right: 60px;
}

</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/components/shared/SidebarElement.vue?vue&amp;type=style&amp;index=0&amp;scoped=0c8fc035&amp;lang.css">
.sidebar-item a[data-v-0c8fc035] {
  line-height: 1.25rem;
}
.category[data-v-0c8fc035] {
  cursor: pointer;
  font-weight: bold;
  margin-bottom: 0.5rem;
}
li[data-v-0c8fc035] {
  line-height: 1;
}
.icon[data-v-0c8fc035] {
  float: right;
}
ul li[data-v-0c8fc035] {
  margin-bottom:10px;
}
ul[data-v-0c8fc035] {
  list-style: none;
  padding: 0;
  margin: 0;
  padding-left: 15px !important;
}
ul[data-v-0c8fc035] {
    list-style: none;
}
</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/components/shared/SideBar.vue?vue&amp;type=style&amp;index=0&amp;scoped=4ae1c7ab&amp;lang.css">
.sidebar-item[data-v-4ae1c7ab] {
  padding-top:5px;
  padding-bottom: 5px;
  font-weight: normal;
}
.sidebar-link[data-v-4ae1c7ab] {
  color:black !important;
  text-decoration: none;
}
.sidebar[data-v-4ae1c7ab] {
  border: 1px black solid;
  overflow-y: auto;
  padding: 1rem;
  box-shadow: 2px 0 5px rgba(0, 0, 0, 0.1);
  text-align: left;
}
.category[data-v-4ae1c7ab] {
  cursor: pointer;
  font-weight: bold;
  margin-bottom: 0.5rem;
}
li[data-v-4ae1c7ab] {
  margin-left: 1rem;
}
.router-link-exact-active[data-v-4ae1c7ab] {
  font-weight: bold;
  background-color:lightgray;
}
.icon[data-v-4ae1c7ab] {
  float: right;
}
</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/components/pages/Risks.vue?vue&amp;type=style&amp;index=0&amp;scoped=f4e0ae5f&amp;lang.css">
.table-subheader[data-v-f4e0ae5f] {
    font-weight: bold;
}
.styled-table[data-v-f4e0ae5f] {
  width: 100%;
  border-collapse: collapse;
}
.styled-table th[data-v-f4e0ae5f],
.styled-table td[data-v-f4e0ae5f] {
  border: 1px solid #ddd;
  padding: 8px;
}
.styled-table th[data-v-f4e0ae5f] {
  background-color: #f2f2f2;
  text-align: left;
}

/* .styled-table tr:hover {
  background-color: #ddd;
} */
.sidebar-container[data-v-f4e0ae5f] {
    padding-left:15px;
    padding-right: 15px;
    padding-bottom:15px;
}
.container-page[data-v-f4e0ae5f] {
    display: flex;
    text-align:left;
    padding-top:20px;
}
ul[data-v-f4e0ae5f] {
            list-style-type: none; /* Remove default bullets */
            padding-left: 0; /* Remove default padding */
}
li[data-v-f4e0ae5f] {
            position: relative; /* Position relative for the pseudo-element */
            padding-left: 20px; /* Space for the dash */
}
li[data-v-f4e0ae5f]::before {
            content: "-"; /* Use dash as bullet */
            position: absolute; /* Position it absolutely */
            left: 0; /* Align it to the left */
}

</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/components/pages/Mitigations.vue?vue&amp;type=style&amp;index=0&amp;scoped=4f0e9610&amp;lang.css">
.table-subheader[data-v-4f0e9610] {
    font-weight: bold;
}
.styled-table[data-v-4f0e9610] {
  width: 100%;
  border-collapse: collapse;
}
.styled-table th[data-v-4f0e9610],
.styled-table td[data-v-4f0e9610] {
  border: 1px solid #ddd;
  padding: 8px;
}
.styled-table th[data-v-4f0e9610] {
  background-color: #f2f2f2;
  text-align: left;
}

/* .styled-table tr:hover {
  background-color: #ddd;
} */
.sidebar-container[data-v-4f0e9610] {
    padding-left:15px;
    padding-right: 15px;
    padding-bottom:15px;
}
.container-page[data-v-4f0e9610] {
    display: flex;
    text-align:left;
    padding-top:20px;
}
ul[data-v-4f0e9610] {
            list-style-type: none; /* Remove default bullets */
            padding-left: 0; /* Remove default padding */
}
li[data-v-4f0e9610] {
            position: relative; /* Position relative for the pseudo-element */
            padding-left: 20px; /* Space for the dash */
}
li[data-v-4f0e9610]::before {
            content: "-"; /* Use dash as bullet */
            position: absolute; /* Position it absolutely */
            left: 0; /* Align it to the left */
}

</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/components/pages/IndividualRisk.vue?vue&amp;type=style&amp;index=0&amp;scoped=89f037f1&amp;lang.css">
.table-subheader[data-v-89f037f1] {
    font-weight: bold;
}
.styled-table[data-v-89f037f1] {
  width: 100%;
  border-collapse: collapse;
}
.styled-table th[data-v-89f037f1],
.styled-table td[data-v-89f037f1] {
  border: 1px solid #ddd;
  padding: 8px;
}
.styled-table th[data-v-89f037f1] {
  background-color: #f2f2f2;
  text-align: left;
}

/* .styled-table tr:hover {
  background-color: #ddd;
} */
.container-page[data-v-89f037f1] {
    display: flex;
    text-align:left;
    padding-top:20px;
}
ul[data-v-89f037f1] {
            list-style-type: none; /* Remove default bullets */
            padding-left: 0; /* Remove default padding */
}
li[data-v-89f037f1] {
            position: relative; /* Position relative for the pseudo-element */
            padding-left: 20px; /* Space for the dash */
}
li[data-v-89f037f1]::before {
            content: "-"; /* Use dash as bullet */
            position: absolute; /* Position it absolutely */
            left: 0; /* Align it to the left */
}
.reference-container li[data-v-89f037f1]::before {
    content: "";
}
</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/components/pages/MitigationPhase.vue?vue&amp;type=style&amp;index=0&amp;scoped=d6b3f66a&amp;lang.css">
.container-page[data-v-d6b3f66a] {
    display: flex;
}

</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/components/pages/IndividualMitigation.vue?vue&amp;type=style&amp;index=0&amp;scoped=9fa56426&amp;lang.css">
.container-page[data-v-9fa56426] {
    display: flex;
}

</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/components/shared/MatrixSidePanel.vue?vue&amp;type=style&amp;index=0&amp;lang.css">
.side-panel-top {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
}
.side-panel {
  position: fixed;
  top: 60px;
  right: 0;
  width: 300px;
  height: 100%;
  background-color: #f9f9f9;
  box-shadow: -2px 0 5px rgba(0, 0, 0, 0.1);
  padding: 20px;
  display: flex;
  flex-direction: column;
}
.close-button {
  background: none;
  border: none;
  font-size: x-large;
  cursor: pointer;
}
.side-panel-content {
  margin-top: 20px;
}
.side-panel-content h2 {
  margin: 0 0 10px;
}
.side-panel-content p {
  margin: 0;
}
</style><style type="text/css" data-vite-dev-id="/usr/src/app/src/components/pages/Matrix.vue?vue&amp;type=style&amp;index=0&amp;scoped=058eb164&amp;lang.css">
.phase-name-header[data-v-058eb164] {
}
.matrix-page-container[data-v-058eb164] {
  padding-left: 20px;
  padding-right: 20px;
}
ul[data-v-058eb164] {
  /*list-style: none;*/
}
.container-page[data-v-058eb164] {
    display: flex;
}
.table-container[data-v-058eb164] {
  width: 100%;
  overflow-x: auto; /* Allows horizontal scrolling if the table is too wide */
}
table[data-v-058eb164] {
  width: 100%;
  border-collapse: collapse; /* Ensures single-line borders between cells */
  font-family: Arial, sans-serif; /* Sets a clean font for the table */
}
th[data-v-058eb164], td[data-v-058eb164] {
  padding: 10px; /* Adds padding inside table cells */
  text-align: left; /* Aligns text to the left */
  border: 1px solid #ddd; /* Adds single-line borders between cells */
}
th[data-v-058eb164] {
  background-color: #f4f4f4; /* Light gray background for headers */
  font-weight: bold; /* Makes header text bold */
}

/* tr:nth-child(even) {
  background-color: #f9f9f9; /* Alternating row colors for better readability 
} */
tr[data-v-058eb164]:hover {
  background-color: #f1f1f1; /* Highlight row on hover */
}
.table-cell[data-v-058eb164] {
  cursor: pointer; /* Changes cursor to pointer when hovering over cells */
}
.table-cell[data-v-058eb164]:hover {
  background-color: #e0e0e0; /* Slightly darker background on hover */
}

</style></head>
  <body>
    <div id="app" data-v-app=""><div data-v-7a7a37b1="" class="layout"><nav data-v-c3ceb15a="" data-v-7a7a37b1=""><a data-v-c3ceb15a="" href="/"><div data-v-c3ceb15a="" class="nav-left"><span data-v-c3ceb15a="" class="site-name logo-container" style="padding-right: 0.5rem;"><img data-v-c3ceb15a="" id="mitre-logo" src="data:image/svg+xml,%3c?xml%20version='1.0'%20encoding='UTF-8'?%3e%3c!--%20Generator:%20Adobe%20Illustrator%2027.4.0,%20SVG%20Export%20Plug-In%20.%20SVG%20Version:%206.00%20Build%200)%20--%3e%3csvg%20xmlns='http://www.w3.org/2000/svg'%20xmlns:xlink='http://www.w3.org/1999/xlink'%20version='1.1'%20id='Layer_1'%20x='0px'%20y='0px'%20viewBox='0%200%20240%2092'%20style='enable-background:new%200%200%20240%2092;'%20xml:space='preserve'%3e%3cg%3e%3cg%3e%3cpolygon%20points='62.1,14.5%2047.6,51.9%2032.9,14.5%2021.2,14.5%2010,74.4%2022,74.4%2029.1,36.9%2043,74.4%2052,74.4%2065.9,36.9%2073,74.4%2085.4,74.4%2073.8,14.5%20'%3e%3c/polygon%3e%3crect%20x='88.4'%20y='14.5'%20width='11.2'%20height='60'%3e%3c/rect%3e%3cpolygon%20points='103.3,14.5%20103.3,24.2%20116.5,24.2%20116.5,74.4%20127.7,74.4%20127.7,24.2%20140.9,24.2%20140.9,14.5%20'%3e%3c/polygon%3e%3cg%3e%3cpath%20d='M155.8,74.4h-11.2v-60h26.7c1.1,0,2.9,0.4,5.4,1.1c2.5,0.7,5,2.4,7.5,4.9c2.5,2.6,3.7,6.3,3.7,11.2c0,5.1-1.3,9-4,11.6%20c-2.7,2.7-5.4,4.3-8.2,5c-2.7,0.8-4.8,1.1-6.1,1.1l20,25H176l-18.3-24.8V38.9l11.2-0.1h0.6c1.5,0,3.1-0.6,4.6-1.7%20c1.7-1.3,2.5-3.1,2.5-5.4c0-2.1-0.7-3.8-2.1-5.2c-1.4-1.3-3.3-2-5.7-2h-13.1V74.4z'%3e%3c/path%3e%3cpolygon%20points='189.5,14.5%20224.3,14.5%20224.3,24.2%20200.8,24.2%20200.8,39.6%20224,39.6%20224,49.3%20200.8,49.3%20200.8,64.7%20224.3,64.7%20224.3,74.4%20189.5,74.4%20'%3e%3c/polygon%3e%3c/g%3e%3c/g%3e%3c/g%3e%3c/svg%3e" alt="MITRE LOGO"></span><span data-v-c3ceb15a="" class="site-name"> LILAC™</span></div></a><div data-v-c3ceb15a="" class="nav-right"><ul data-v-c3ceb15a=""><li data-v-c3ceb15a=""><a data-v-c3ceb15a="" href="/" class="router-link-active router-link-exact-active" aria-current="page">Home</a></li><li data-v-c3ceb15a=""><a data-v-c3ceb15a="" href="/matrix" class="">Matrix</a></li><li data-v-c3ceb15a=""><a data-v-c3ceb15a="" href="/risks" class="">Risks</a></li><li data-v-c3ceb15a=""><a data-v-c3ceb15a="" href="/mitigations" class="">Mitigations</a></li><li data-v-c3ceb15a=""><a data-v-c3ceb15a="" href="/test" class="">Test Harness</a></li></ul></div></nav><main data-v-7a7a37b1=""><div data-v-7a7a37b1="" class="page-container"><div data-v-08e32229="" data-v-7a7a37b1="" class="homepage-container"><h1 data-v-08e32229="">List of Interventions for LLM-Assisted Chatbots (MITRE LILAC™)</h1><h2 data-v-08e32229="">MITRE LILAC™ is a toolkit for identifying and mitigating problematic outputs from chatbots powered by generative artificial intelligence.</h2><p data-v-08e32229="" class="separation-border"></p><h3 data-v-08e32229="">What is LILAC™?</h3><div data-v-08e32229="" class="text-container"><p data-v-08e32229="">Grounded in real incidents and reports of negative outcomes resulting from LLMs, LILAC™ presents a typology for discussing chatbot risks and a protocol for applying strategies to mitigate those risks. </p><p data-v-08e32229="">The risk typology comprises of 10 risk categories, with 19 subcategories, that chatbot development teams can prioritize and use for assessment, which is linked to 30 mitigation stretegies covering the human-chatbot interaction workflow that development teams can apply to diminish those risks. </p><p data-v-08e32229="">LILAC™ represents a key step towards realizing the promise of trustworthy chatbots that maximize benefits and minimize risks to the public. LILAC™ also serves as a roadmap for researchers assessing the state of the art. </p><p data-v-08e32229="">Check out our report here: <a data-v-08e32229="" href="/LILAC-v1-RELEASE.pdf" download="LILAC-technical-report.pdf">LILAC™ technical report</a></p></div><p data-v-08e32229=""> MITRE LILAC™ and LILAC™ are trademarks of The MITRE Corporation. All Rights Reserved. </p></div></div></main><footer data-v-7a7a37b1=""><div data-v-fc427fd3="" data-v-7a7a37b1="" class="footer-container"><div data-v-fc427fd3="" class="nav-left"><p data-v-fc427fd3="" class="copyright-text">© 2025 The MITRE Corporation. All Rights Reserved.</p></div><div data-v-fc427fd3="" class="nav-right"><a data-v-fc427fd3="" href="https://forms.office.com/Pages/DesignPageV2.aspx?subpage=design&amp;FormId=SNwgxlAdUkmLOd9NVNdNgnavvUf4ajdOvCW37EAiXMFUODc0SUtKQloxVjNOUUUyVjc5T1RDODlZRy4u&amp;Token=31d1f3a2bd47450297230858c422e4b6" target="_blank" rel="noopener noreferrer">Contact Us</a></div></div></footer></div></div>
    <script type="module" src="/src/main.js?t=1745297039261"></script>
  

</body></html>
