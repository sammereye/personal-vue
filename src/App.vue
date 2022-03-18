<template>
  <div class="container mx-auto mt-24 lg:px-0 px-2">
    <div class="flex lg:flex-row flex-col">
      <div class="lg:w-1/2 w-full lg:mb-0 mb-10 ">
        <div class="flex flex-col lg:w-[90%] w-full">
          <div class="name text-4xl font-semibold mb-2 font-[Poppins] text-white">Hello, I'm Sammer</div>
          <div class="bg-[#1aea9b] w-28 h-2 mb-4"></div>
          <div class="description font-[Inter] tracking-wide leading-9 text-[15px] text-[#e7e7ea]">I'm a <b class="text-[#1aea9b]">passionate Full Stack Web Developer</b> with over <b class="text-[#1aea9b]">3 years of industry experience</b>. At my current position at the Indiana University School of Medicine, <b class="text-[#1aea9b]">I independently design and develop</b> internal applications that assist radiologists in optimizing their workflow. In the process of development, I ensure that all <b class="text-[#1aea9b]">HIPAA-protected patient data is securely processed and stored.</b></div>
        </div>
      </div>
      <div class="flex lg:w-1/2 w-full justify-end">
        <div class="window lg:w-[90%] w-full h-full flex flex-col rounded-md overflow-hidden shadow-xl">
          <div class="bar h-7 w-full flex">
            <div class="bar-options flex items-center h-full">
              <div class="close w-3 h-3 mr-2 ml-3 rounded-full"></div>
              <div class="minimize w-3 h-3 mr-2 rounded-full"></div>
              <div class="maximize w-3 h-3 mr-2 rounded-full"></div>
            </div>

            <div class="header-name grow text-xs flex items-center justify-center">app.js — aboutMe</div>

            <!-- Only here to ensure that the title of the window is centered correctly -->
            <div class="bar-options flex items-center h-full invisible">
              <div class="w-3 h-3 mr-2 ml-3 rounded-full"></div>
              <div class="minimize w-3 h-3 mr-2 rounded-full"></div>
              <div class="maximize w-3 h-3 mr-2 rounded-full"></div>
            </div>
          </div>
          <div class="editor grow w-full flex">
            <div class="side-bar w-12 min-h-full">

            </div>
            <div class="grow flex flex-col overflow-x-scroll overflow-y-hidden">
              <div class="file-bar w-full h-9 flex">
                <div class="file-tab file-tab-active h-full flex items-center">
                  <svg class="ml-7" width="12" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path fill="#caca41" d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM243.8 381.4c0 43.6-25.6 63.5-62.9 63.5-33.7 0-53.2-17.4-63.2-38.5l34.3-20.7c6.6 11.7 12.6 21.6 27.1 21.6 13.8 0 22.6-5.4 22.6-26.5V237.7h42.1v143.7zm99.6 63.5c-39.1 0-64.4-18.6-76.7-43l34.3-19.8c9 14.7 20.8 25.6 41.5 25.6 17.4 0 28.6-8.7 28.6-20.8 0-14.4-11.4-19.5-30.7-28l-10.5-4.5c-30.4-12.9-50.5-29.2-50.5-63.5 0-31.6 24.1-55.6 61.6-55.6 26.8 0 46 9.3 59.8 33.7L368 290c-7.2-12.9-15-18-27.1-18-12.3 0-20.1 7.8-20.1 18 0 12.6 7.8 17.7 25.9 25.6l10.5 4.5c35.8 15.3 55.9 31 55.9 66.2 0 37.8-29.8 58.6-69.7 58.6z"/></svg>
                  <div class="file-tab-text text-xs ml-3">aboutMe.js</div>
                  <svg class="ml-3 mr-7" width="8" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 352 512"><path fill="#e1e1e5" d="M242.72 256l100.07-100.07c12.28-12.28 12.28-32.19 0-44.48l-22.24-22.24c-12.28-12.28-32.19-12.28-44.48 0L176 189.28 75.93 89.21c-12.28-12.28-32.19-12.28-44.48 0L9.21 111.45c-12.28 12.28-12.28 32.19 0 44.48L109.28 256 9.21 356.07c-12.28 12.28-12.28 32.19 0 44.48l22.24 22.24c12.28 12.28 32.2 12.28 44.48 0L176 322.72l100.07 100.07c12.28 12.28 32.2 12.28 44.48 0l22.24-22.24c12.28-12.28 12.28-32.19 0-44.48L242.72 256z"/></svg>
                </div>
              </div>
              <div class="code-editor flex grow flex-col">
                <div class="code-upper flex h-80">
                  <div class="number-column font-[Roboto Mono] h-full w-7 flex flex-col items-end text-end space-y-1 text-xs mt-2">
                    <div>1</div>
                    <div>2</div>
                    <div>3</div>
                    <div>4</div>
                    <div>5</div>
                    <div>6</div>
                    <div>7</div>
                    <div>8</div>
                    <div>9</div>
                    <div>10</div>
                    <div>11</div>
                    <div>12</div>
                    <div>13</div>
                    <div>14</div>
                    <div>15</div>
                  </div>
                  <div class="code-column font-[Roboto Mono] h-full grow flex flex-col space-y-1 ml-5 text-xs mt-2 whitespace-nowrap">
                    <div><span class="code-purple">import</span> <span class="code-red">Dev</span> <span class="code-purple">from</span> <span class="code-green">'./Dev'</span>;</div>
                    <div class="invisible">invisible</div>
                    <div><span class="code-purple">let</span> <span class="code-orange">sammer</span> = <span class="code-purple">new</span> <span class="code-blue">Dev</span>({</div>
                      <div>&nbsp;&nbsp;<span class="code-red">full_name</span>: <span class="code-green">'Sammer Aburumman'</span>,</div>
                      <div>&nbsp;&nbsp;<span class="code-red">location</span>: <span class="code-green">'Indiana, USA'</span>,</div>
                      <div>&nbsp;&nbsp;<span class="code-red">career</span>: <span class="code-green">'Full Stack Web Developer'</span>,</div>
                      <div>&nbsp;&nbsp;<span class="code-red">yearsOfExperience</span>: <span class="code-orange">3,</span></div>
                      <div>&nbsp;&nbsp;<span class="code-red">education</span>: {</div>
                        <div>&nbsp;&nbsp;&nbsp;&nbsp;<span class="code-red">school:</span> <span class="code-green">'Indiana University-Purdue University Indianapolis'</span>,</div>
                        <div>&nbsp;&nbsp;&nbsp;&nbsp;<span class="code-red">degree:</span> <span class="code-green">'B.S. Computer Information Technology'</span></div>
                      <div>&nbsp;&nbsp;},</div>
                      <div>&nbsp;&nbsp;<span class="code-red">certifications</span>: [</div>
                        <div>&nbsp;&nbsp;&nbsp;&nbsp;<span class="code-green">'AWS Certified Developer Associate'</span></div>
                      <div>&nbsp;&nbsp;]</div>
                    <div>});</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="flex flex-col mt-24">
      <div class="name text-3xl font-semibold mb-2 font-[Poppins] uppercase text-[#e8eaee]">Projects</div>
      <div class="bg-[#1aea9b] w-20 h-1.5 mb-4"></div>
      <div class="projects-container">
        <div class="project flex lg:flex-row flex-col mt-4">
          <div class="lg:w-[50%] w-full">
            <div class="name text-2xl font-medium mb-1 font-[Poppins] text-[#e8eaee]">Dig our RIS v2 (DORIS2)</div>
            <div class="name text-sm font-medium mb-2 font-[Poppins] text-[#a0a6b1]">February 2020 &mdash; Ongoing</div>
            <div class="flex space-x-3 font-bold text-xs mb-5">
              <div class="px-2 py-1.5 bg-[#1aea9b] rounded-md">Ruby on Rails</div>
              <div class="px-2 py-1.5 bg-[#1aea9b] rounded-md">SQL Server</div>
              <div class="px-2 py-1.5 bg-[#1aea9b] rounded-md">ElasticSearch</div>
            </div>
            <div class="w-[90%] font-[Inter] tracking-wide leading-9 text-[15px] text-[#e7e7ea]">Dig our RIS v2 (DORIS2) is an independently built Ruby on Rails web application that gives researchers and physicians at the IU School of Medicine the ability to query through roughly 20,000,000 radiology exams with less than a second of response time. The application utilizes ElasticSearch and SQL Server to give users the ablity to fine-tune their search requirements to tailor their exacts needs. Searches are utilized by researchers, administration and residents.</div>
          </div>
          <div class="lg:w-[50%] w-full flex items-center lg:mt-0 mt-5">
            <img src="/assets/doris2.webp" alt="Image of DORIS2" class="shadow-lg w-full rounded-md bg-gray-400" />
          </div>
        </div>

        <div class="project flex lg:flex-row flex-col mt-20">
          <div class="lg:w-[50%] w-full">
            <div class="name text-2xl font-medium mb-1 font-[Poppins] text-[#e8eaee]">Tarkov Handboook</div>
            <div class="name text-sm font-medium mb-2 font-[Poppins] text-[#a0a6b1]">January 2022 &mdash; Ongoing</div>
            <div class="flex space-x-3 font-bold text-xs mb-5">
              <div class="px-2 py-1.5 bg-[#1aea9b] rounded-md">HTML</div>
              <div class="px-2 py-1.5 bg-[#1aea9b] rounded-md">CSS</div>
              <div class="px-2 py-1.5 bg-[#1aea9b] rounded-md">NodeJS</div>
              <div class="px-2 py-1.5 bg-[#1aea9b] rounded-md">Electron</div>
            </div>
            <div class="w-[90%] font-[Inter] tracking-wide leading-9 text-[15px] text-[#e7e7ea]">Tarkov Handbook is an Electron application with NodeJS that allows users to click a hotkey and launch a small but detailed overlay on top of the game to search for in-game market prices, quest guides, interactive maps and more. During development, the Tarkov Handbook was in beta for public use which resulted in roughly 500 downloads and 3,000 YouTube views.</div>
          </div>
          <div class="lg:w-[50%] w-full lg:mt-0 mt-5">
            <video class="shadow-lg w-full rounded-md bg-gray-400" autoplay muted loop>
              <source src="/assets/tarkovhandbook.mp4" type="video/mp4">
            </video>
            <!-- <img src="images/tarkovhandbook.mp4" alt="Animated GIF of Tarkov Handbook" class="shadow-lg w-full rounded-md bg-gray-400" loading="lazy"></img> -->
          </div>
        </div>

        <div class="project flex lg:flex-row flex-col mt-20">
          <div class="lg:w-[50%] w-full">
            <div class="name text-2xl font-medium mb-1 font-[Poppins] text-[#e8eaee]">RECIST Dashboard</div>
            <div class="name text-sm font-medium mb-2 font-[Poppins] text-[#a0a6b1]">January 2019 &mdash; February 2020</div>
            <div class="flex space-x-3 font-bold text-xs mb-5">
              <div class="px-2 py-1.5 bg-[#1aea9b] rounded-md">HTML</div>
              <div class="px-2 py-1.5 bg-[#1aea9b] rounded-md">CSS</div>
              <div class="px-2 py-1.5 bg-[#1aea9b] rounded-md">Ruby on Rails</div>
              <div class="px-2 py-1.5 bg-[#1aea9b] rounded-md">SQL Server</div>
            </div>
            <div class="w-[90%] font-[Inter] tracking-wide leading-9 text-[15px] text-[#e7e7ea]">The RECIST Dashboard is an independently built Ruby on Rails web application that allows radiologists and oncologists to add patients, add associated lesions/tumors and enter in measurements each time they visit for an appointment. The measurement data is then used to track how the patient is progressing throughout their treatment. Prior to the launch of the RECIST Dashboard, radiology assistants were required to hand-write all patient data and store them within physical folders. This system dramatically increased workflow times and reduced human error by setting strict submission guidelines.</div>
          </div>
          <div class="lg:w-[50%] w-full lg:mt-0 mt-5">
            <img src="/assets/recist.webp" alt="Image of RECIST" class="shadow-lg w-full rounded-md bg-gray-400" />
          </div>
        </div>
      </div>
    </div>  
  </div>
  <footer class="w-full py-5 mt-20 flex flex-col items-center justify-center text-sm bg-[#21283d] text-white">
    <div>Designed and Developed by Sammer &copy;</div>
    <div class="flex w-full justify-center space-x-6 mt-4">
      <a href="https://github.com/sammereye/" target="_blank">
        <svg class="w-8" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path fill="#d3d4da" d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM277.3 415.7c-8.4 1.5-11.5-3.7-11.5-8 0-5.4.2-33 .2-55.3 0-15.6-5.2-25.5-11.3-30.7 37-4.1 76-9.2 76-73.1 0-18.2-6.5-27.3-17.1-39 1.7-4.3 7.4-22-1.7-45-13.9-4.3-45.7 17.9-45.7 17.9-13.2-3.7-27.5-5.6-41.6-5.6-14.1 0-28.4 1.9-41.6 5.6 0 0-31.8-22.2-45.7-17.9-9.1 22.9-3.5 40.6-1.7 45-10.6 11.7-15.6 20.8-15.6 39 0 63.6 37.3 69 74.3 73.1-4.8 4.3-9.1 11.7-10.6 22.3-9.5 4.3-33.8 11.7-48.3-13.9-9.1-15.8-25.5-17.1-25.5-17.1-16.2-.2-1.1 10.2-1.1 10.2 10.8 5 18.4 24.2 18.4 24.2 9.7 29.7 56.1 19.7 56.1 19.7 0 13.9.2 36.5.2 40.6 0 4.3-3 9.5-11.5 8-66-22.1-112.2-84.9-112.2-158.3 0-91.8 70.2-161.5 162-161.5S388 165.6 388 257.4c.1 73.4-44.7 136.3-110.7 158.3zm-98.1-61.1c-1.9.4-3.7-.4-3.9-1.7-.2-1.5 1.1-2.8 3-3.2 1.9-.2 3.7.6 3.9 1.9.3 1.3-1 2.6-3 3zm-9.5-.9c0 1.3-1.5 2.4-3.5 2.4-2.2.2-3.7-.9-3.7-2.4 0-1.3 1.5-2.4 3.5-2.4 1.9-.2 3.7.9 3.7 2.4zm-13.7-1.1c-.4 1.3-2.4 1.9-4.1 1.3-1.9-.4-3.2-1.9-2.8-3.2.4-1.3 2.4-1.9 4.1-1.5 2 .6 3.3 2.1 2.8 3.4zm-12.3-5.4c-.9 1.1-2.8.9-4.3-.6-1.5-1.3-1.9-3.2-.9-4.1.9-1.1 2.8-.9 4.3.6 1.3 1.3 1.8 3.3.9 4.1zm-9.1-9.1c-.9.6-2.6 0-3.7-1.5s-1.1-3.2 0-3.9c1.1-.9 2.8-.2 3.7 1.3 1.1 1.5 1.1 3.3 0 4.1zm-6.5-9.7c-.9.9-2.4.4-3.5-.6-1.1-1.3-1.3-2.8-.4-3.5.9-.9 2.4-.4 3.5.6 1.1 1.3 1.3 2.8.4 3.5zm-6.7-7.4c-.4.9-1.7 1.1-2.8.4-1.3-.6-1.9-1.7-1.5-2.6.4-.6 1.5-.9 2.8-.4 1.3.7 1.9 1.8 1.5 2.6z"/></svg>
      </a>
      <a href="https://linkedin.com/in/sammerabu/" target="_blank">
        <svg class="w-8" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path fill="#d3d4da" d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z"/></svg>
      </a>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'App',
  components: {
    
  }
}
</script>