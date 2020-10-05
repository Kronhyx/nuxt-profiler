<template>
  <div class="sf-toolbarreset clear-fix" style="display: block;">
    <ToolbarRequest></ToolbarRequest>

    <ToolbarTime></ToolbarTime>

    <div class="sf-toolbar-block sf-toolbar-block-ajax sf-toolbar-status-normal" style="display: none;">
      <div class="sf-toolbar-icon">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
          <path fill="#AAA"
                d="M9.8 18L6 22.4c-.3.3-.8.4-1.1 0L1 18c-.4-.5-.1-1 .5-1H3V6.4C3 3.8 5.5 2 8.2 2h3.9c1.1 0 2 .9 2 2s-.9 2-2 2H8.2C7.7 6 7 6 7 6.4V17h2.2c.6 0 1 .5.6 1zM23 6l-3.8-4.5a.8.8 0 0 0-1.1 0L14.2 6c-.4.5-.1 1 .5 1H17v10.6c0 .4-.7.4-1.2.4h-3.9c-1.1 0-2 .9-2 2s.9 2 2 2h3.9c2.6 0 5.2-1.8 5.2-4.4V7h1.5c.6 0 .9-.5.5-1z" />
        </svg>

        <span class="sf-toolbar-value sf-toolbar-ajax-request-counter">0</span>
      </div>
      <div class="sf-toolbar-info">
        <div class="sf-toolbar-info-piece">
          <b class="sf-toolbar-ajax-info">0 AJAX requests</b>
        </div>
        <div class="sf-toolbar-info-piece">
          <table class="sf-toolbar-ajax-requests">
            <thead>
            <tr>
              <th>Method</th>
              <th>Type</th>
              <th>Status</th>
              <th>URL</th>
              <th>Time</th>
              <th>Profile</th>
            </tr>
            </thead>
            <tbody class="sf-toolbar-ajax-request-list" />
          </table>
        </div>
      </div>
    </div>

    <div class="sf-toolbar-block sf-toolbar-block-form sf-toolbar-status-normal ">
      <a href="https://flexy.ftwo.local/_profiler/3346c2?panel=form">
        <div class="sf-toolbar-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
            <path fill="#AAA"
                  d="M20.5 4H18V2.5c0-.8-.7-1.5-1.5-1.5h-9C6.7 1 6 1.7 6 2.5V4H3.5C2.7 4 2 4.7 2 5.5v16c0 .8.7 1.5 1.5 1.5h17c.8 0 1.5-.7 1.5-1.5v-16c0-.8-.7-1.5-1.5-1.5zM9 4h6v1H9V4zm10 16H5V7h1.1c.2.6.8 1 1.4 1h9c.7 0 1.2-.4 1.4-1H19v13zm-2-9c0 .6-.4 1-1 1H8c-.6 0-1-.4-1-1s.4-1 1-1h8c.6 0 1 .4 1 1zm0 3c0 .6-.4 1-1 1H8c-.6 0-1-.4-1-1s.4-1 1-1h8c.6 0 1 .4 1 1zm-4 3c0 .6-.4 1-1 1H8c-.6 0-1-.4-1-1s.4-1 1-1h4c.6 0 1 .4 1 1z" />
          </svg>

          <span class="sf-toolbar-value">
          1
        </span>
        </div>
      </a>
      <div class="sf-toolbar-info">
        <div class="sf-toolbar-info-piece">
          <b>Number of forms</b>
          <span class="sf-toolbar-status">1</span>
        </div>
        <div class="sf-toolbar-info-piece">
          <b>Number of errors</b>
          <span class="sf-toolbar-status sf-toolbar-status-">0</span>
        </div>
      </div>
    </div>

    <div class="sf-toolbar-block sf-toolbar-block-logger sf-toolbar-status-yellow ">
      <a href="https://flexy.ftwo.local/_profiler/3346c2?panel=logger">
        <div class="sf-toolbar-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
            <path fill="#AAA"
                  d="M21 4v13.8c0 2.7-2.5 5.2-5.2 5.2H6c-.6 0-1-.4-1-1s.4-1 1-1h9.8c1.6 0 3.2-1.7 3.2-3.2V4c0-.6.4-1 1-1s1 .4 1 1zM5.5 20A2.5 2.5 0 0 1 3 17.5v-14C3 2.1 4.1 1 5.5 1h10.1C16.9 1 18 2.1 18 3.5v14.1c0 1.4-1.1 2.5-2.5 2.5h-10zM9 11.4c0 .3.3.6.6.6h1.8c.3 0 .6-.3.6-.6V4.6c0-.3-.3-.6-.6-.6H9.6c-.3 0-.6.3-.6.6v6.8zm0 5c0 .3.3.6.6.6h1.8c.3 0 .6-.3.6-.6v-1.8c0-.3-.3-.6-.6-.6H9.6c-.3 0-.6.3-.6.6v1.8z" />
          </svg>

          <span class="sf-toolbar-value">2674</span>
        </div>
      </a>
      <div class="sf-toolbar-info">
        <div class="sf-toolbar-info-piece">
          <b>Errors</b>
          <span class="sf-toolbar-status sf-toolbar-status-">0</span>
        </div>

        <div class="sf-toolbar-info-piece">
          <b>Warnings</b>
          <span class="sf-toolbar-status sf-toolbar-status-yellow">37</span>
        </div>

        <div class="sf-toolbar-info-piece">
          <b>Deprecations</b>
          <span class="sf-toolbar-status sf-toolbar-status-yellow">2637</span>
        </div>
      </div>
    </div>

    <div class="sf-toolbar-block sf-toolbar-block-cache sf-toolbar-status-normal ">
      <a href="https://flexy.ftwo.local/_profiler/3346c2?panel=cache">
        <div class="sf-toolbar-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
            <path fill="#AAA"
                  d="M2.3 6l9-4.6a1.5 1.5 0 0 1 1.4 0l9 4.7a1.5 1.5 0 0 1 0 2.6l-9 4.7a1.5 1.5 0 0 1-1.4 0l-9-4.7a1.5 1.5 0 0 1 0-2.6zm18.3 5L12 15.4 3.4 11a1.4 1.4 0 0 0-1.2 2.4l9.2 4.8a1.4 1.4 0 0 0 1.2 0l9.2-4.8a1.4 1.4 0 0 0-1.3-2.4zm0 4.5L12 19.9l-8.6-4.4a1.4 1.4 0 0 0-1.2 2.4l9.2 4.7a1.4 1.4 0 0 0 1.2 0l9.2-4.7a1.4 1.4 0 0 0-1.3-2.5z" />
          </svg>

          <span class="sf-toolbar-value">138</span>
          <span class="sf-toolbar-info-piece-additional-detail">
          <span class="sf-toolbar-label">in</span>
          <span class="sf-toolbar-value">13.61</span>
          <span class="sf-toolbar-label">ms</span>
        </span>
        </div>
      </a>
      <div class="sf-toolbar-info">
        <div class="sf-toolbar-info-piece">
          <b>Cache Calls</b>
          <span>138</span>
        </div>
        <div class="sf-toolbar-info-piece">
          <b>Total time</b>
          <span>13.61 ms</span>
        </div>
        <div class="sf-toolbar-info-piece">
          <b>Cache hits</b>
          <span>138 / 138 (100%)</span>
        </div>
        <div class="sf-toolbar-info-piece">
          <b>Cache writes</b>
          <span>0</span>
        </div>
      </div>
    </div>

    <div class="sf-toolbar-block sf-toolbar-block-translation sf-toolbar-status-red ">
      <a href="https://flexy.ftwo.local/_profiler/3346c2?panel=translation">
        <div class="sf-toolbar-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
            <path fill="#AAA"
                  d="M5.4 6H7v.3c0 1.2-.7 1.9-1.7 1.9-1.1 0-1.4-.4-1.4-1.1 0-.9.6-1.1 1.5-1.1zm3.8-6H2.7C1.2 0 0 .9 0 2.4v6.5C0 10.4 1.2 11 2.7 11h1.2l3.3 3.2c.4.2.8.3.8-.1V9.9l.1-1.1h-.4c-.3.1-.7-.1-.7-.4v-.5c0 .7-1 1-1.8 1-1.5 0-2.4-.7-2.4-2s1.1-2 2.6-2H7v-.4c0-1-.4-1.6-1.5-1.6-.7 0-1.1.2-1.5.7l-.3.2a.4.4 0 0 1-.4-.4l.1-.2c.4-.7 1-1.2 2.2-1.2C7.2 2 8 3 8 4.5v3c1-1.4 1.8-2.4 4-2.4V2.4C12 .9 10.7 0 9.2 0zm11.5 6h-8C10.8 6 9 7.2 9 9v8c0 1.8 2 3.3 4 3.3v3c0 .5.5.7.9.3l4-3.7h2.7c1.8 0 3.3-1.2 3.3-3V9c.1-1.8-1.4-3-3.2-3zM13 9h7v.8s-.7.3-1.1.3h-4.8a10 10 0 0 1-1.1-.4V9zm-.5 7.9l-.6-.5c1-.8 1.8-2.1 2.2-3.4l.7.3c-.6 1.5-1.4 2.6-2.3 3.6zM17 12v4.8c0 .7-.2.8-1.2.8l-1.4-.1-.2-.7 1.4.1c.4 0 .4 0 .4-.3V12h-2.9l-1.1.1v-.8s.7-.4 1.1-.4h6.8c.5 0 1.1.4 1.1.4v.8l-1.1-.1H17zm3.7 4.8c-1-1.1-1.6-1.9-2.3-3.6l.6-.2a9 9 0 0 0 2.2 3.3l-.5.5z" />
          </svg>

          <span class="sf-toolbar-value">33</span>
        </div>
      </a>
      <div class="sf-toolbar-info">
        <div class="sf-toolbar-info-piece">
          <b>Default locale</b>
          <span class="sf-toolbar-status">
            pt_BR
          </span>
        </div>
        <div class="sf-toolbar-info-piece">
          <b>Missing messages</b>
          <span class="sf-toolbar-status sf-toolbar-status-red">
            33
          </span>
        </div>

        <div class="sf-toolbar-info-piece">
          <b>Fallback messages</b>
          <span class="sf-toolbar-status sf-toolbar-status-">
            0
          </span>
        </div>

        <div class="sf-toolbar-info-piece">
          <b>Defined messages</b>
          <span class="sf-toolbar-status">239</span>
        </div>
      </div>
    </div>

    <div class="sf-toolbar-block sf-toolbar-block-security sf-toolbar-status-normal ">
      <a href="https://flexy.ftwo.local/_profiler/3346c2?panel=security">
        <div class="sf-toolbar-icon">
          <svg
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            x="0px"
            y="0px"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            enable-background="new 0 0 24 24"
            xml:space="preserve"
          >
                                                                                                                        <path
                                                                                                                          fill="#AAAAAA"
                                                                                                                          d="M21,20.4V22H3v-1.6c0-3.7,2.4-6.9,5.8-8c-1.7-1.1-2.9-3-2.9-5.2c0-3.4,2.7-6.1,6.1-6.1s6.1,2.7,6.1,6.1c0,2.2-1.2,4.1-2.9,5.2C18.6,13.5,21,16.7,21,20.4z" />
                                                                                                                      </svg>

          <span class="sf-toolbar-value">anon.</span>
        </div>
      </a>
      <div class="sf-toolbar-info">
        <div class="sf-toolbar-info-group">
          <div class="sf-toolbar-info-piece">
            <b>Logged in as</b>
            <span>anon.</span>
          </div>

          <div class="sf-toolbar-info-piece">
            <b>Authenticated</b>
            <span class="sf-toolbar-status sf-toolbar-status-green">Yes</span>
          </div>

          <div class="sf-toolbar-info-piece">
            <b>Token class</b>
            <span><abbr
              title="Symfony\Component\Security\Core\Authentication\Token\AnonymousToken">AnonymousToken</abbr></span>
          </div>

          <div class="sf-toolbar-info-piece">
            <b>Firewall name</b>
            <span>main</span>
          </div>
        </div>
      </div>
    </div>

    <div class="sf-toolbar-block sf-toolbar-block-twig sf-toolbar-status-normal ">
      <a href="https://flexy.ftwo.local/_profiler/3346c2?panel=twig">
        <div class="sf-toolbar-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
            <path fill="#AAA"
                  d="M20.1 1H3.9A2.9 2.9 0 0 0 1 3.9v16.3C1 21.7 2.3 23 3.9 23h16.3c1.6 0 2.9-1.3 2.9-2.9V3.9a3 3 0 0 0-3-2.9zm.9 19.1c0 .5-.4.9-.9.9H3.9a.9.9 0 0 1-.9-.9V3.9c0-.5.4-.9.9-.9h16.3c.4 0 .8.4.8.9v16.2zM5 5h14v3H5V5zm0 5h3v9H5v-9zm5 0h9v9h-9v-9z" />
          </svg>

          <span class="sf-toolbar-value">5399</span>
          <span class="sf-toolbar-label">ms</span>
        </div>
      </a>
      <div class="sf-toolbar-info" style="left: 0px;">
        <div class="sf-toolbar-info-piece">
          <b>Render Time</b>
          <span>5399 ms</span>
        </div>
        <div class="sf-toolbar-info-piece">
          <b>Template Calls</b>
          <span class="sf-toolbar-status">65</span>
        </div>
        <div class="sf-toolbar-info-piece">
          <b>Block Calls</b>
          <span class="sf-toolbar-status">310</span>
        </div>
        <div class="sf-toolbar-info-piece">
          <b>Macro Calls</b>
          <span class="sf-toolbar-status">13</span>
        </div>
      </div>
    </div>

    <div class="sf-toolbar-block sf-toolbar-block-db sf-toolbar-status-red ">
      <a href="https://flexy.ftwo.local/_profiler/3346c2?panel=db">
        <div class="sf-toolbar-icon">

          <svg
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            x="0px"
            y="0px"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            enable-background="new 0 0 24 24"
            xml:space="preserve"
          >
          <path
            fill="#AAAAAA"
            d="M5,8h14c1.7,0,3-1.3,3-3s-1.3-3-3-3H5C3.3,2,2,3.3,2,5S3.3,8,5,8z M18,3.6c0.8,0,1.5,0.7,1.5,1.5S18.8,6.6,18,6.6s-1.5-0.7-1.5-1.5S17.2,3.6,18,3.6z M19,9H5c-1.7,0-3,1.3-3,3s1.3,3,3,3h14c1.7,0,3-1.3,3-3S20.7,9,19,9z M18,13.6
    c-0.8,0-1.5-0.7-1.5-1.5s0.7-1.5,1.5-1.5s1.5,0.7,1.5,1.5S18.8,13.6,18,13.6z M19,16H5c-1.7,0-3,1.3-3,3s1.3,3,3,3h14c1.7,0,3-1.3,3-3S20.7,16,19,16z M18,20.6c-0.8,0-1.5-0.7-1.5-1.5s0.7-1.5,1.5-1.5s1.5,0.7,1.5,1.5S18.8,20.6,18,20.6z"
          />
        </svg>

          <span class="sf-toolbar-value">257</span>
          <span class="sf-toolbar-info-piece-additional-detail">
          <span class="sf-toolbar-label">in</span>
          <span class="sf-toolbar-value">156.93</span>
          <span class="sf-toolbar-label">ms</span>
        </span>

        </div>
      </a>
      <div class="sf-toolbar-info" style="left: 0px;">
        <div class="sf-toolbar-info-piece">
          <b>Database Queries</b>
          <span class="sf-toolbar-status sf-toolbar-status-yellow">257</span>
        </div>
        <div class="sf-toolbar-info-piece">
          <b>Query time</b>
          <span>156.93 ms</span>
        </div>
        <div class="sf-toolbar-info-piece">
          <b>Invalid entities</b>
          <span class="sf-toolbar-status sf-toolbar-status-red">10</span>
        </div>
        <div class="sf-toolbar-info-piece">
          <b>Second Level Cache</b>
          <span class="sf-toolbar-status">disabled</span>
        </div>
      </div>
    </div>

    <div class="sf-toolbar-block sf-toolbar-block-elastica sf-toolbar-status-normal ">
      <a href="https://flexy.ftwo.local/_profiler/3346c2?panel=elastica">
        <div class="sf-toolbar-icon">
          <svg
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            x="0px"
            y="0px"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            enable-background="new 0 0 24 24"
            xml:space="preserve"
          >
                                                                                                                            <g
                                                                                                                              transform="matrix(0.09962018,0,0,0.10022867,-0.74934957,-0.88367143)">
                                                                                                                              <path
                                                                                                                                d="m 100.08527,110.36444 57.04233,26.11829 57.66917,-50.565 c 0.83579,-4.178926 1.25368,-8.357851 1.25368,-12.745723 0,-35.520867 -28.83459,-64.3554535 -64.35545,-64.3554535 -21.31252,0 -41.16242,10.4473135 -53.072357,27.9988015 l -9.611529,49.729214 11.074156,23.819871 0,0 z"
                                                                                                                                fill="#aaaaaa" />
                                                                                                                              <path
                                                                                                                                d="m 40.95347,170.74992 c -0.835785,4.17892 -1.253677,8.5668 -1.253677,12.95467 0,35.52086 29.043532,64.5644 64.564397,64.5644 21.52147,0 41.37137,-10.65626 53.49025,-28.20775 l 9.40258,-49.72921 -12.74572,-24.23777 -57.251281,-26.11829 -56.206549,50.77395 0,0 z"
                                                                                                                                fill="#aaaaaa" />
                                                                                                                              <path
                                                                                                                                d="m 40.535578,71.918329 39.072954,9.193637 8.775743,-44.505558 C 82.951672,32.427483 76.474338,30.33802 69.57911,30.33802 c -16.924648,0 -30.924049,13.790454 -30.924049,30.924049 0,3.552087 0.626839,7.31312 1.880517,10.65626 l 0,0 z"
                                                                                                                                fill="#aaaaaa" />
                                                                                                                              <path
                                                                                                                                d="M 37.192437,81.320912 C 19.64095,86.962461 7.522066,103.88711 7.522066,122.27438 c 0,17.96938 11.074153,34.05825 27.789855,40.32663 L 90.264792,112.8718 80.235371,91.350333 37.192437,81.320912 l 0,0 z"
                                                                                                                                fill="#aaaaaa" />
                                                                                                                              <path
                                                                                                                                d="m 167.78386,219.85229 c 5.4326,4.17893 11.90994,6.47734 18.59622,6.47734 16.92465,0 30.92405,-13.79046 30.92405,-30.92405 0,-3.76103 -0.62684,-7.31312 -1.88052,-10.65626 l -39.07295,-9.19364 -8.5668,44.29661 0,0 z"
                                                                                                                                fill="#aaaaaa" />
                                                                                                                              <path
                                                                                                                                d="m 175.72382,165.31731 43.04293,10.02943 c 17.55149,-5.8505 29.67037,-22.5662 29.67037,-40.95347 0,-17.96938 -11.07415,-33.8493 -27.78985,-40.326635 l -56.4155,49.311325 11.49205,21.93935 0,0 z"
                                                                                                                                fill="#aaaaaa" />
                                                                                                                            </g>
                                                                                                                          </svg>
          <span class="sf-toolbar-value">0</span>
        </div>
      </a>
      <div class="sf-toolbar-info" style="left: 0px;">
        <div class="sf-toolbar-info-piece">
          <b>Queries</b>
          <span class="sf-toolbar-status">0</span>
        </div>
        <div class="sf-toolbar-info-piece">
          <b>Query Time</b>
          <span>0.00 ms</span>
        </div>
        <div class="sf-toolbar-info-piece">
          <b>Execution Time</b>
          <span>0.00 ms</span>
        </div>
      </div>
    </div>

    <div class="sf-toolbar-block sf-toolbar-block-redis sf-toolbar-status-normal ">
      <a href="https://flexy.ftwo.local/_profiler/3346c2?panel=redis">
        <div class="sf-toolbar-icon">
          <svg
            id="Layer_1"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            x="0px"
            y="0px"
            width="28.004px"
            height="24px"
            viewBox="0 0 28.004 24"
            enable-background="new 0 0 28.004 24"
            xml:space="preserve"
          >
                                                                                                                         <path
                                                                                                                           fill="#aaa"
                                                                                                                           d="M1.135,6.663c1.484,0.711,9.722,4.039,11.023,4.66c1.302,0.623,2.219,0.63,3.865-0.229 c1.648-0.859,9.391-4.043,10.885-4.821s1.438-1.218-0.02-1.752c-1.455-0.533-9.15-3.596-10.625-4.136 c-1.474-0.54-2.076-0.517-3.806,0.104L1.075,4.896C-0.382,5.467-0.351,5.956,1.135,6.663z M14.555,9.889L10.026,8.01l6.49-0.995 L14.555,9.889z M24.38,5.423l-3.838,1.516L20.54,3.904L24.38,5.423z M13.112,2.641l-0.627-1.157l1.957,0.766l1.846-0.604l-0.5,1.197 l1.883,0.704l-2.426,0.251l-0.543,1.308l-0.879-1.458l-2.801-0.251L13.112,2.641z M8.279,4.275c1.916,0,3.469,0.601,3.469,1.345 c0,0.742-1.553,1.344-3.469,1.344S4.81,6.362,4.81,5.62C4.81,4.875,6.362,4.274,8.279,4.275z M1.075,9.684 c0.066-0.028,0.15-0.061,0.248-0.098c1.891,0.862,9.578,3.969,10.832,4.57c1.302,0.621,2.219,0.629,3.865-0.23 c1.578-0.822,8.707-3.762,10.646-4.701c0.082,0.031,0.16,0.061,0.224,0.083c1.454,0.534,1.512,0.974,0.016,1.755 c-1.493,0.778-9.236,3.96-10.885,4.82c-1.646,0.86-2.564,0.85-3.865,0.229c-1.3-0.62-9.538-3.95-11.023-4.659 C-0.353,10.743-0.384,10.254,1.075,9.684z M26.907,15.676c-1.496,0.777-9.236,3.961-10.886,4.82 c-1.648,0.859-2.563,0.852-3.864,0.229c-1.303-0.621-9.541-3.949-11.023-4.658c-1.484-0.711-1.516-1.196-0.059-1.77 c0.016-0.006,0.033-0.014,0.051-0.02c0.002,0,0.004,0.002,0.008,0.004c1.482,0.709,9.723,4.035,11.023,4.658 c1.303,0.623,2.217,0.631,3.864-0.229c1.636-0.854,9.25-3.983,10.84-4.799c0.009,0.004,0.019,0.008,0.025,0.01 C28.343,14.457,28.4,14.896,26.907,15.676z" />
            <path fill="#555"
                  d="M28.001,14.73c0,0.002,0.002,0.002,0.002,0.002s0,2.526,0,2.789c0,0.28-0.336,0.588-1.096,0.983 c-1.496,0.779-9.236,3.961-10.886,4.82c-1.648,0.858-2.563,0.852-3.864,0.229c-1.303-0.621-9.541-3.949-11.023-4.658 c-0.742-0.354-1.133-0.654-1.133-0.938s0-2.822,0-2.828c0.012,0.281,0.391,0.58,1.133,0.935c1.482,0.709,9.723,4.039,11.023,4.66 c1.303,0.623,2.217,0.631,3.864-0.229c1.648-0.861,9.39-4.043,10.886-4.82C27.632,15.297,27.986,15,28.001,14.73z M26.907,11.061 c-1.496,0.777-9.236,3.96-10.886,4.82c-1.648,0.86-2.563,0.852-3.864,0.229c-1.303-0.62-9.541-3.948-11.023-4.657 c-0.742-0.354-1.121-0.654-1.133-0.937c0,0.01,0,2.547,0,2.831c0,0.284,0.391,0.58,1.133,0.938 c1.482,0.709,9.723,4.034,11.023,4.655c1.303,0.623,2.217,0.631,3.864-0.227c1.648-0.859,9.39-4.043,10.886-4.822 c0.76-0.395,1.096-0.703,1.096-0.981c0-0.265,0-2.791,0-2.791h-0.002C27.988,10.383,27.632,10.682,26.907,11.061z M1.132,9.497 c1.484,0.709,9.725,4.037,11.025,4.66c1.301,0.62,2.217,0.631,3.864-0.23c1.646-0.858,9.39-4.042,10.883-4.821 c0.763-0.396,1.099-0.703,1.099-0.983c0-0.263,0-2.791,0-2.791s-0.002,0-0.004,0c-0.013,0.268-0.367,0.564-1.095,0.942 c-1.493,0.778-9.233,3.962-10.885,4.821c-1.646,0.859-2.563,0.853-3.862,0.229c-1.303-0.621-9.541-3.949-11.025-4.658 C0.392,6.31,0.013,6.01,0.001,5.729c0,0.007,0,2.548,0,2.83C0.001,8.842,0.39,9.141,1.132,9.497z M20.542,6.939L20.54,3.905 l-4.25,1.682l3.836,1.517L20.542,6.939z" />
                                                                                                                       </svg>

          <span class="sf-toolbar-value">141</span>
          <span class="sf-toolbar-info-piece-additional-detail">
          <span class="sf-toolbar-label">in</span>
          <span class="sf-toolbar-value">46.60</span>
          <span class="sf-toolbar-label">ms</span>
        </span>
        </div>
      </a>
      <div class="sf-toolbar-info" style="left: 0px;">
        <div class="sf-toolbar-info-piece">
          <b>Queries</b>
          <span class="sf-toolbar-status">141</span>
        </div>

        <div class="sf-toolbar-info-piece">
          <b>Query time</b>
          <span>46.60 ms</span>
        </div>
      </div>
    </div>

    <div class="sf-toolbar-block sf-toolbar-block-config sf-toolbar-status-normal sf-toolbar-block-right" title="">
      <a href="https://flexy.ftwo.local/_profiler/3346c2?panel=config">
        <div class="sf-toolbar-icon">
          <span class="sf-toolbar-label">
            <Logo/>
          </span>
          <span class="sf-toolbar-value">3.4.37</span>
        </div>
      </a>
      <div class="sf-toolbar-info" style="right: 0px;">
        <div class="sf-toolbar-info-group">
          <div class="sf-toolbar-info-piece">
            <b>Profiler token</b>
            <span>
              <a href="https://flexy.ftwo.local/_profiler/3346c2">3346c2</a>
            </span>
          </div>

          <div class="sf-toolbar-info-piece">
            <b>Kernel name</b>
            <span>app</span>
          </div>

          <div class="sf-toolbar-info-piece">
            <b>Environment</b>
            <span>dev</span>
          </div>

          <div class="sf-toolbar-info-piece">
            <b>Debug</b>
            <span class="sf-toolbar-status sf-toolbar-status-green">enabled</span>
          </div>
        </div>

        <div class="sf-toolbar-info-group">
          <div class="sf-toolbar-info-piece sf-toolbar-info-php">
            <b>PHP version</b>
            <span>
              7.2.32
              &nbsp; <a href="/_profiler/phpinfo">View phpinfo()</a>
            </span>
          </div>

          <div class="sf-toolbar-info-piece sf-toolbar-info-php-ext">
            <b>PHP Extensions</b>
            <span class="sf-toolbar-status sf-toolbar-status-green">xdebug</span>
            <span class="sf-toolbar-status sf-toolbar-status-red">APCu</span>
            <span class="sf-toolbar-status sf-toolbar-status-red">OPcache</span>
          </div>

          <div class="sf-toolbar-info-piece">
            <b>PHP SAPI</b>
            <span>fpm-fcgi</span>
          </div>
        </div>

        <div class="sf-toolbar-info-group">
          <div class="sf-toolbar-info-piece">
            <b>Resources</b>
            <span>
              <a href="https://symfony.com/doc/3.4.37/index.html" rel="help">
                Read Symfony 3.4.37 Docs
              </a>
            </span>
          </div>
          <div class="sf-toolbar-info-piece">
            <b>Help</b>
            <span>
              <a href="https://symfony.com/support">
                Symfony Support Channels
              </a>
            </span>
          </div>
        </div>
      </div>
    </div>

    <a id="sfToolbarHideButton-3346c2" class="hide-button" title="Close Toolbar" tabindex="-1" accesskey="D">
      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
        <path fill="#AAA"
              d="M21.1 18.3c.8.8.8 2 0 2.8-.4.4-.9.6-1.4.6s-1-.2-1.4-.6L12 14.8l-6.3 6.3c-.4.4-.9.6-1.4.6s-1-.2-1.4-.6a2 2 0 0 1 0-2.8L9.2 12 2.9 5.7a2 2 0 0 1 0-2.8 2 2 0 0 1 2.8 0L12 9.2l6.3-6.3a2 2 0 0 1 2.8 0c.8.8.8 2 0 2.8L14.8 12l6.3 6.3z" />
      </svg>

    </a>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator'
import ToolbarRequest from './toolbar/request.vue'
import ToolbarTime from './toolbar/time.vue'
import Logo from './Logo.vue'

@Component({components: { ToolbarRequest, ToolbarTime, Logo }})
export default class Toolbar extends Vue {

}
</script>

<style nonce="8b5e39dd604649a8bf0d04031d4c0011">    .sf-minitoolbar {
  background-color: #222;
  border-top-left-radius: 4px;
  bottom: 0;
  box-sizing: border-box;
  display: none;
  height: 36px;
  padding: 6px;
  position: fixed;
  right: 0;
  z-index: 99999;
}

.sf-minitoolbar a {
  display: block;
}

.sf-minitoolbar svg, .sf-minitoolbar img {
  max-height: 24px;
  max-width: 24px;
  display: inline;
}

.sf-toolbar-clearer {
  clear: both;
  height: 36px;
}

.sf-display-none {
  display: none;
}

.sf-toolbarreset * {
  box-sizing: content-box;
  vertical-align: baseline;
  letter-spacing: normal;
  width: auto;
}

.sf-toolbarreset {
  background-color: #222;
  bottom: 0;
  box-shadow: 0 -1px 0 rgba(0, 0, 0, 0.2);
  color: #EEE;
  font: 11px Arial, sans-serif;
  left: 0;
  margin: 0;
  padding: 0 36px 0 0;
  position: fixed;
  right: 0;
  text-align: left;
  text-transform: none;
  z-index: 99999;
  direction: ltr; /* neutralize the aliasing defined by external CSS styles */
  -webkit-font-smoothing: subpixel-antialiased;
  -moz-osx-font-smoothing: auto;
}

.sf-toolbarreset abbr {
  border: dashed #777;
  border-width: 0 0 1px;
}

.sf-toolbarreset svg, .sf-toolbarreset img {
  height: 20px;
  width: 20px;
  display: inline-block;
}

.sf-toolbarreset .hide-button {
  background: #444;
  display: block;
  position: absolute;
  top: 0;
  right: 0;
  width: 36px;
  height: 36px;
  cursor: pointer;
  text-align: center;
}

.sf-toolbarreset .hide-button svg {
  max-height: 18px;
  margin-top: 10px;
}

.sf-toolbar-block {
  cursor: default;
  display: block;
  float: left;
  height: 36px;
  margin-right: 0;
  white-space: nowrap;
}

.sf-toolbar-block > a, .sf-toolbar-block > a:hover {
  display: block;
  text-decoration: none;
}

.sf-toolbar-block span {
  display: inline-block;
}

.sf-toolbar-block .sf-toolbar-value {
  color: #F5F5F5;
  font-size: 13px;
  line-height: 36px;
  padding: 0;
}

.sf-toolbar-block .sf-toolbar-label, .sf-toolbar-block .sf-toolbar-class-separator {
  color: #AAA;
  font-size: 12px;
}

.sf-toolbar-block .sf-toolbar-info {
  border-collapse: collapse;
  display: table;
  z-index: 100000;
}

.sf-toolbar-block hr {
  border-top: 1px solid #777;
  margin: 4px 0;
  padding-top: 4px;
}

.sf-toolbar-block .sf-toolbar-info-piece { /* this 'border-bottom' trick is needed because 'margin-bottom' doesn't work for table rows */
  border-bottom: solid transparent 3px;
  display: table-row;
}

.sf-toolbar-block .sf-toolbar-info-piece-additional, .sf-toolbar-block .sf-toolbar-info-piece-additional-detail {
  display: none;
}

.sf-toolbar-block .sf-toolbar-info-group {
  margin-bottom: 4px;
  padding-bottom: 2px;
  border-bottom: 1px solid #333333;
}

.sf-toolbar-block .sf-toolbar-info-group:last-child {
  margin-bottom: 0;
  padding-bottom: 0;
  border-bottom: none;
}

.sf-toolbar-block .sf-toolbar-info-piece .sf-toolbar-status {
  padding: 2px 5px;
  margin-bottom: 0;
}

.sf-toolbar-block .sf-toolbar-info-piece .sf-toolbar-status + .sf-toolbar-status {
  margin-left: 4px;
}

.sf-toolbar-block .sf-toolbar-info-piece:last-child {
  margin-bottom: 0;
}

div.sf-toolbar .sf-toolbar-block .sf-toolbar-info-piece a {
  color: #99CDD8;
  text-decoration: underline;
}

div.sf-toolbar .sf-toolbar-block a:hover {
  text-decoration: none;
}

.sf-toolbar-block .sf-toolbar-info-piece b {
  color: #AAA;
  display: table-cell;
  font-size: 11px;
  padding: 4px 8px 4px 0;
}

.sf-toolbar-block:not(.sf-toolbar-block-dump) .sf-toolbar-info-piece span {
  color: #F5F5F5;
}

.sf-toolbar-block .sf-toolbar-info-piece span {
  font-size: 12px;
}

.sf-toolbar-block .sf-toolbar-info {
  background-color: #444;
  bottom: 36px;
  color: #F5F5F5;
  display: none;
  padding: 9px 0;
  position: absolute;
}

.sf-toolbar-block .sf-toolbar-info:empty {
  visibility: hidden;
}

.sf-toolbar-block .sf-toolbar-status {
  display: inline-block;
  color: #FFF;
  background-color: #666;
  padding: 3px 6px;
  margin-bottom: 2px;
  vertical-align: middle;
  min-width: 15px;
  min-height: 13px;
  text-align: center;
}

.sf-toolbar-block .sf-toolbar-status-green {
  background-color: #4F805D;
}

.sf-toolbar-block .sf-toolbar-status-red {
  background-color: #B0413E;
}

.sf-toolbar-block .sf-toolbar-status-yellow {
  background-color: #A46A1F;
}

.sf-toolbar-block.sf-toolbar-status-green {
  background-color: #4F805D;
  color: #FFF;
}

.sf-toolbar-block.sf-toolbar-status-red {
  background-color: #B0413E;
  color: #FFF;
}

.sf-toolbar-block.sf-toolbar-status-yellow {
  background-color: #A46A1F;
  color: #FFF;
}

.sf-toolbar-block-request .sf-toolbar-status {
  color: #FFF;
  display: inline-block;
  font-size: 14px;
  height: 36px;
  line-height: 36px;
  padding: 0 10px;
}

.sf-toolbar-block-request .sf-toolbar-info-piece a {
  text-decoration: none;
}

.sf-toolbar-block-request .sf-toolbar-info-piece a:hover {
  text-decoration: underline;
}

.sf-toolbar-block-request .sf-toolbar-redirection-status {
  font-weight: normal;
  padding: 2px 4px;
  line-height: 18px;
}

.sf-toolbar-block-request .sf-toolbar-info-piece span.sf-toolbar-redirection-method {
  font-size: 12px;
  height: 17px;
  line-height: 17px;
  margin-right: 5px;
}

.sf-toolbar-block-ajax .sf-toolbar-icon {
  cursor: pointer;
}

.sf-toolbar-status-green .sf-toolbar-label, .sf-toolbar-status-yellow .sf-toolbar-label, .sf-toolbar-status-red .sf-toolbar-label {
  color: #FFF;
}

.sf-toolbar-status-green svg path, .sf-toolbar-status-green svg .sf-svg-path, .sf-toolbar-status-red svg path, .sf-toolbar-status-red svg .sf-svg-path, .sf-toolbar-status-yellow svg path, .sf-toolbar-status-yellow svg .sf-svg-path {
  fill: #FFF;
}

.sf-toolbar-block-config svg path, .sf-toolbar-block-config svg .sf-svg-path {
  fill: #FFF;
}

.sf-toolbar-block .sf-toolbar-icon {
  display: block;
  height: 36px;
  padding: 0 7px;
}

.sf-toolbar-block-request .sf-toolbar-icon {
  padding-left: 0;
  padding-right: 0;
}

.sf-toolbar-block .sf-toolbar-icon img, .sf-toolbar-block .sf-toolbar-icon svg {
  border-width: 0;
  position: relative;
  top: 8px;
  vertical-align: baseline;
}

.sf-toolbar-block .sf-toolbar-icon img + span, .sf-toolbar-block .sf-toolbar-icon svg + span {
  margin-left: 4px;
}

.sf-toolbar-block-config .sf-toolbar-icon .sf-toolbar-value {
  margin-left: 4px;
}

.sf-toolbar-block:hover, .sf-toolbar-block.hover {
  position: relative;
}

.sf-toolbar-block:hover .sf-toolbar-icon, .sf-toolbar-block.hover .sf-toolbar-icon {
  background-color: #444;
  position: relative;
  z-index: 10002;
}

.sf-toolbar-block-ajax.hover .sf-toolbar-info {
  z-index: 10001;
}

.sf-toolbar-block:hover .sf-toolbar-info, .sf-toolbar-block.hover .sf-toolbar-info {
  display: block;
  padding: 10px;
  max-width: 480px;
  max-height: 480px;
  word-wrap: break-word;
  overflow: hidden;
  overflow-y: auto;
}

.sf-toolbar-info-piece b.sf-toolbar-ajax-info {
  color: #F5F5F5;
}

.sf-toolbar-ajax-requests {
  table-layout: auto;
  width: 100%;
}

.sf-toolbar-ajax-requests td {
  background-color: #444;
  border-bottom: 1px solid #777;
  color: #F5F5F5;
  font-size: 12px;
  padding: 4px;
}

.sf-toolbar-ajax-requests tr:last-child td {
  border-bottom: 0;
}

.sf-toolbar-ajax-requests th {
  background-color: #222;
  border-bottom: 0;
  color: #AAA;
  font-size: 11px;
  padding: 4px;
}

.sf-ajax-request-url {
  max-width: 250px;
  line-height: 9px;
  overflow: hidden;
  text-overflow: ellipsis;
}

.sf-toolbar-ajax-requests .sf-ajax-request-url a {
  text-decoration: none;
}

.sf-toolbar-ajax-requests .sf-ajax-request-url a:hover {
  text-decoration: underline;
}

.sf-ajax-request-duration {
  text-align: right;
}

.sf-ajax-request-loading {
  animation: sf-blink .5s ease-in-out infinite;
}

@keyframes sf-blink {
  0% {
    background: #222;
  }
  50% {
    background: #444;
  }
  100% {
    background: #222;
  }
}

.sf-toolbar-block.sf-toolbar-block-dump .sf-toolbar-info {
  max-width: none;
  width: 100%;
  position: fixed;
  box-sizing: border-box;
  left: 0;
}

.sf-toolbar-block-dump pre.sf-dump {
  background-color: #222;
  border-color: #777;
  border-radius: 0;
  margin: 6px 0 12px 0;
}

.sf-toolbar-block-dump pre.sf-dump:last-child {
  margin-bottom: 0;
}

.sf-toolbar-block-dump pre.sf-dump .sf-dump-search-wrapper {
  margin-bottom: 5px;
}

.sf-toolbar-block-dump pre.sf-dump span.sf-dump-search-count {
  color: #333;
  font-size: 12px;
}

.sf-toolbar-block-dump .sf-toolbar-info-piece {
  display: block;
}

.sf-toolbar-block-dump .sf-toolbar-info-piece .sf-toolbar-file-line {
  color: #AAA;
  margin-left: 4px;
}

.sf-toolbar-block-dump .sf-toolbar-info img {
  display: none;
}

/* Override the setting when the toolbar is on the top *//* Responsive Design */
.sf-toolbar-icon .sf-toolbar-label, .sf-toolbar-icon .sf-toolbar-value {
  display: none;
}

.sf-toolbar-block-config .sf-toolbar-icon .sf-toolbar-label {
  display: inline-block;
}

/* Legacy Design - these styles are maintained to make old panels look   a bit better on the new toolbar */
.sf-toolbar-block .sf-toolbar-info-piece-additional-detail {
  color: #AAA;
  font-size: 12px;
}

.sf-toolbar-status-green .sf-toolbar-info-piece-additional-detail, .sf-toolbar-status-yellow .sf-toolbar-info-piece-additional-detail, .sf-toolbar-status-red .sf-toolbar-info-piece-additional-detail {
  color: #FFF;
}

@media (min-width: 768px) {
  .sf-toolbar-icon .sf-toolbar-label, .sf-toolbar-icon .sf-toolbar-value {
    display: inline;
  }

  .sf-toolbar-block .sf-toolbar-icon img, .sf-toolbar-block .sf-toolbar-icon svg {
    top: 6px;
  }

  .sf-toolbar-block-time .sf-toolbar-icon svg, .sf-toolbar-block-memory .sf-toolbar-icon svg {
    display: none;
  }

  .sf-toolbar-block-time .sf-toolbar-icon svg + span, .sf-toolbar-block-memory .sf-toolbar-icon svg + span {
    margin-left: 0;
  }

  .sf-toolbar-block .sf-toolbar-icon {
    padding: 0 10px;
  }

  .sf-toolbar-block-time .sf-toolbar-icon {
    padding-right: 5px;
  }

  .sf-toolbar-block-memory .sf-toolbar-icon {
    padding-left: 5px;
  }

  .sf-toolbar-block-request .sf-toolbar-icon {
    padding-left: 0;
    padding-right: 0;
  }

  .sf-toolbar-block-request .sf-toolbar-label {
    margin-left: 5px;
  }

  .sf-toolbar-block-request .sf-toolbar-status + svg {
    margin-left: 5px;
  }

  .sf-toolbar-block-request .sf-toolbar-icon svg + .sf-toolbar-label {
    margin-left: 0;
  }

  .sf-toolbar-block-request .sf-toolbar-label + .sf-toolbar-value {
    margin-right: 10px;
  }

  .sf-toolbar-block-request:hover .sf-toolbar-info {
    max-width: none;
  }

  .sf-toolbar-block .sf-toolbar-info-piece b {
    font-size: 12px;
  }

  .sf-toolbar-block .sf-toolbar-info-piece span {
    font-size: 13px;
  }

  .sf-toolbar-block-right {
    float: right;
    margin-left: 0;
    margin-right: 0;
  }
}

@media (min-width: 1024px) {
  .sf-toolbar-block .sf-toolbar-info-piece-additional, .sf-toolbar-block .sf-toolbar-info-piece-additional-detail {
    display: inline-block;
  }

  .sf-toolbar-block .sf-toolbar-info-piece-additional:empty, .sf-toolbar-block .sf-toolbar-info-piece-additional-detail:empty {
    display: none;
  }
}

/***** Error Toolbar *****/
.sf-error-toolbar .sf-toolbarreset {
  background: #222;
  color: #f5f5f5;
  font: 13px/36px Arial, sans-serif;
  height: 36px;
  padding: 0 15px;
  text-align: left;
}

.sf-error-toolbar .sf-toolbarreset svg {
  height: auto;
}

.sf-error-toolbar .sf-toolbarreset a {
  color: #99cdd8;
  margin-left: 5px;
  text-decoration: underline;
}

.sf-error-toolbar .sf-toolbarreset a:hover {
  text-decoration: none;
}

.sf-error-toolbar .sf-toolbarreset .sf-toolbar-icon {
  float: left;
  padding: 5px 0;
  margin-right: 10px;
}

/***** Media query print: Do not print the Toolbar. *****/
@media print {
  .sf-toolbar {
    display: none;
  }
}</style>
