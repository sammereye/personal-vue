<template>
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
</template>

<script>
export default {
  name: 'HeroEditor'
}
</script>