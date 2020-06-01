<template>
  <div class="icon__container">
    <div class="icon__wrap">
      <svg
        width="60"
        height="60"
        viewBox="0 0 83 92"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          fill-rule="evenodd"
          clip-rule="evenodd"
          d="M32.21 0.963501V10.0402H50.3636V0.963501H59.4404V10.0402H77.5939C80.1004 10.0402 82.1323 12.0722 82.1323 14.5786V87.193C82.1323 89.6995 80.1004 91.7314 77.5939 91.7314H73.0555L73.0555 46.3474L9.518 46.3475L9.51796 82.6546H63.9787V91.7314H4.97956C2.47307 91.7314 0.441162 89.6995 0.441162 87.193V14.5786C0.441162 12.0722 2.47307 10.0402 4.97956 10.0402H23.1332V0.963501H32.21ZM32.21 28.1939H23.1332V19.117H9.51796V37.2707H73.0555V19.117H59.4404V28.1939H50.3636V19.117H32.21V28.1939Z"
          fill="url(#paint0_linear)"
        />
        <defs>
          <linearGradient
            id="paint0_linear"
            x1="0.241891"
            y1="0.859546"
            x2="84.7446"
            y2="84.5365"
            gradientUnits="userSpaceOnUse"
          >
            <stop offset="0.458333" stop-color="#9E9EB1" />
            <stop offset="1" stop-color="#9595AE" stop-opacity="1" />
          </linearGradient>
        </defs>
      </svg>
    </div> 
    
    <!--Add icon-->
    <div class="icon__wrap">
      <svg width="90" height="90" viewBox="0 0 110 110" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M26.6577 31.8503C39.4647 16.4211 62.3546 14.2955 77.7838 27.1025L83.5811 20.1182C64.2946 4.10947 35.6822 6.76656 19.6734 26.053C3.66465 45.3395 6.32173 73.9519 25.6082 89.9607L31.4055 82.9764C15.9763 70.1694 13.8506 47.2795 26.6577 31.8503Z" fill="url(#paint0_linear)"/>
<path d="M59.1332 36.886H50.0564V50.5012H36.441V59.578H50.0564V73.1931H59.1332V59.578H72.7482V50.5012H59.1332V36.886Z" fill="url(#paint1_linear)"/>
<path d="M65.5443 89.6609C54.1699 93.2465 41.2645 91.16 31.4055 82.9764L25.6082 89.9607C39.1807 101.227 57.3718 103.249 72.5386 96.7361L65.5443 89.6609Z" fill="url(#paint2_linear)"/>
<path d="M74.2778 85.56L80.7707 92.1279C83.9577 89.8757 86.9045 87.1721 89.5159 84.026C90.0601 83.3703 90.5828 82.7038 91.084 82.0274L84.6072 75.4758C83.9652 76.4162 83.2735 77.335 82.5316 78.2287C80.103 81.1546 77.3119 83.602 74.2778 85.56Z" fill="url(#paint3_linear)"/>
<path d="M83.5811 20.1182C99.7202 33.5146 104.215 55.7367 95.8708 73.9342L88.9195 66.9026C93.7128 53.0263 89.7477 37.0331 77.7838 27.1025L83.5811 20.1182Z" fill="url(#paint4_linear)"/>
<defs>
<linearGradient id="paint0_linear" x1="8.98918" y1="9.5516" x2="91.0921" y2="96.268" gradientUnits="userSpaceOnUse">
<stop offset="0.458333" stop-color="#9E9EB1"/>
<stop offset="1" stop-color="#9595AE" stop-opacity="1"/>
</linearGradient>
<linearGradient id="paint1_linear" x1="8.98918" y1="9.5516" x2="91.0921" y2="96.268" gradientUnits="userSpaceOnUse">
<stop offset="0.458333" stop-color="#9E9EB1"/>
<stop offset="1" stop-color="#9595AE" stop-opacity="1"/>
</linearGradient>
<linearGradient id="paint2_linear" x1="8.98918" y1="9.5516" x2="91.0921" y2="96.268" gradientUnits="userSpaceOnUse">
<stop offset="0.458333" stop-color="#9E9EB1"/>
<stop offset="1" stop-color="#9595AE" stop-opacity="1"/>
</linearGradient>
<linearGradient id="paint3_linear" x1="8.98918" y1="9.5516" x2="91.0921" y2="96.268" gradientUnits="userSpaceOnUse">
<stop offset="0.458333" stop-color="#9E9EB1"/>
<stop offset="1" stop-color="#9595AE" stop-opacity="1"/>
</linearGradient>
<linearGradient id="paint4_linear" x1="8.98918" y1="9.5516" x2="91.0921" y2="96.268" gradientUnits="userSpaceOnUse">
<stop offset="0.458333" stop-color="#9E9EB1"/>
<stop offset="1" stop-color="#9595AE" stop-opacity="1"/>
</linearGradient>
</defs>
</svg>

    </div>
  </div>
</template>

<script>
export default {
  name: "Icon"
};
</script>

<style lang="scss">
.icon__container {
display: flex;
align-items: center;
justify-content: center;
.icon__wrap {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 90px;
  width: 90px;
  background: black;
  border-radius: 26px;
  background: #333333;
  box-shadow: 6px 6px 12px #262626, -6px -6px 12px #404040;
  margin: 15px;
  &:hover {
    svg {
      defs {
        linearGradient {
          stop {
            stop-color: lawngreen;
            transition: ease-in-out 0.5s;
          }
        }
      }
    }
  }
}
}
</style>