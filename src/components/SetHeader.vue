<template>
  <div>
    <div class="flex flex-wrap items-center justify-between my-5 px-4 lg:px-0">
      <div class="flex">
        <svg
          @click="$router.push('/')"
          class="h-11 lg:mr-8 cursor-pointer"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 247 44.59"
        >
          <path
            d="M238,14.4a9.16,9.16,0,0,1-2.55-.33l2.49-5.55,2.49,5.55a8.34,8.34,0,0,1-2.44.33h0Zm8.81,4.22L240.95,5.93a3,3,0,0,0-2.88-2h-0.22a3,3,0,0,0-2.94,2l-5.82,12.71a2,2,0,0,0,3.22,2.44,2,2,0,0,0,.43-0.67l1.33-2.79a13.34,13.34,0,0,0,4,.61,11.28,11.28,0,0,0,3.82-.58l1.28,2.79a2,2,0,0,0,2.66,1.05,2,2,0,0,0,.93-2.83v0Zm-21-1.12h-1.11V5.82a2.05,2.05,0,0,0-2.14-2.1,2,2,0,0,0-2.11,2.11V17.48H213V5.82a2.16,2.16,0,1,0-4.32,0V19.51a2,2,0,0,0,2.11,2.11h12.91v1.89a2,2,0,0,0,2.11,2.11,2,2,0,0,0,2-1.28,2,2,0,0,0,.12-0.83V19.58a1.92,1.92,0,0,0-2.11-2.11Zm-21.48,0h-1.11V5.82A2.05,2.05,0,0,0,201,3.72a2,2,0,0,0-2.11,2.11V17.48h-7.42V5.82a2.16,2.16,0,1,0-4.32,0V19.51a2,2,0,0,0,2.11,2.11h12.91v1.89a2,2,0,0,0,2.11,2.11,2,2,0,0,0,2.11-2.11V19.58A1.92,1.92,0,0,0,204.32,17.48ZM180.43,3.88h-0.17c-1.28,0-2.11.61-3,1.89l-7,9.93V6a2.09,2.09,0,1,0-4.18,0V19.2a2.24,2.24,0,0,0,2.38,2.39h0.22a3.53,3.53,0,0,0,3-1.89l7-9.93v9.71a2.05,2.05,0,1,0,4.1,0V6.27a2.23,2.23,0,0,0-2.44-2.39h0Zm-20.87,0h-12A2,2,0,0,0,145.48,6V19.7a2.05,2.05,0,0,0,.62,1.53,2,2,0,0,0,1.54.58,2,2,0,0,0,2.11-2.11V8h7.65V19.7a2,2,0,0,0,2.16,2.11,2.07,2.07,0,0,0,2.16-2.17V5.93A2,2,0,0,0,159.56,3.88ZM128.61,17.75a4.74,4.74,0,0,1-4.82-5,4.75,4.75,0,0,1,4.82-4.94,4.72,4.72,0,0,1,4.82,4.94A4.73,4.73,0,0,1,128.61,17.75Zm0-14a8.89,8.89,0,0,0-9.09,9,8.85,8.85,0,0,0,9.09,9,9,9,0,0,0,9.09-9.1A8.87,8.87,0,0,0,128.61,3.77ZM111.15,17.48h-7a13.55,13.55,0,0,0,1.05-3,25,25,0,0,0,.46-4.39L105.77,8h5.43Zm5.38,0h-1.11V6a2,2,0,0,0-.13-0.82,2,2,0,0,0-2-1.29h-9.81A1.88,1.88,0,0,0,101.57,6V8.78a25.64,25.64,0,0,1-.41,5.2,8.64,8.64,0,0,1-1.39,3.49H99.3a1.91,1.91,0,0,0-2.05,2.11v3.94a2,2,0,0,0,2.11,2.11,2,2,0,0,0,2.11-2.11V21.64h12.91v1.89a2,2,0,0,0,2.09,2.11,2,2,0,0,0,2.11-2.11V19.58a1.86,1.86,0,0,0-2.05-2.11h0Zm-28.77.28a4.74,4.74,0,0,1-4.82-5,4.82,4.82,0,1,1,9.64,0A4.7,4.7,0,0,1,87.76,17.75Zm0-14a8.89,8.89,0,0,0-9.09,9,8.84,8.84,0,0,0,9.1,9,9,9,0,0,0,9.09-9.1,8.8,8.8,0,0,0-9.09-9v0ZM70.2,17.45h-7a13.53,13.53,0,0,0,1.05-3,24.88,24.88,0,0,0,.46-4.39L64.82,8h5.43Zm5.38,0H74.47V6a2,2,0,0,0-2.11-2.11H62.56A1.88,1.88,0,0,0,60.62,6V8.78A22.12,22.12,0,0,1,60.23,14a8.64,8.64,0,0,1-1.39,3.49H58.37a1.91,1.91,0,0,0-2.05,2.11v3.94a2,2,0,0,0,2.15,2.1,2,2,0,0,0,2.11-2.11V21.64H73.49v1.89a2,2,0,0,0,2.11,2.11,2,2,0,0,0,2.11-2.11V19.58a1.92,1.92,0,0,0-2.11-2.11"
          ></path>
          <path
            style="fill: #ff6900"
            d="M19.78,0C32.63,0,42.51,8.86,42.51,22s-9.88,22.3-22.74,22.3H5.33A5.1,5.1,0,0,1,0,39V5.52A5.25,5.25,0,0,1,5.33,0H19.78Z"
          ></path>
          <path
            d="M34.57,17.23c-0.07.55-.69,0.55-1,0.07-0.9-1.52-2.07-1.8-3.94-1.94-1.39-.07-3,0.07-4.56.07H25l-0.11-.06a0.31,0.31,0,0,1-.11-0.21c0.28-1.31,1.39-3.72,2.56-3.94,0.55-.07,1.8-0.21,2.49-0.21C33,11,34.71,14.67,34.57,17.23Zm-18,12.55a22.11,22.11,0,0,0,7.19.69,19.13,19.13,0,0,0,8.92-2.91c-1,2.64-5,4.28-8.71,4.69,0,0.21-.07.34-0.07,0.55a14.91,14.91,0,0,0,6.77-1.94c-0.69,2.56-4.15,3.6-7.33,3.81a4.09,4.09,0,0,1-.28.55,15.88,15.88,0,0,0,4.64-.62c-1.46,2.7-7.68,4.57-12.93,2.1a16.62,16.62,0,0,0,1.8-6.92h0ZM33.95,11.35a6.07,6.07,0,0,0-4.36-1.66c-2.07,0-3.8.55-6.36,0.62-1.73.07-3.32-3.72-5.39-4.22a2.69,2.69,0,0,0-4.21-1.24c-1.17-.69-3-0.34-3,1-1.31-.41-3,0.28-2.28,2.08-3.25.07-3.8,3-1.66,3.25C3.8,12.74,5.12,15.51,7.47,15c0.42,4.15,2.28,9.55-.76,10.87a8.14,8.14,0,0,1-4.36-.14L0,25.06V27.2A21.34,21.34,0,0,0,6,28c4-.41,4.22-3.72,4-6.64s-1.17-6.16-.83-8.51l-0.14-.14c-1.45,1.52-2.42,1.11-2.56.62C6.31,12.39,8,11.15,9,10.73c0-.07.07-0.14,0.07-0.21-0.9.14-2,0-2.07-.62s1.52-1.52,3.6-1.31c0.07,0,.07-0.07.14-0.07l-0.41-.21a0.72,0.72,0,0,1-.46-1,1.48,1.48,0,0,1,1.24-.46A4.63,4.63,0,0,1,13,7.22c0.07,0,.07-0.07.14-0.07a2.47,2.47,0,0,1-.41-0.41,0.53,0.53,0,0,1,0-.7,1.44,1.44,0,0,1,1.66.28l0.34,0.34h0.11l0.1-.06a0.75,0.75,0,0,1-.21-0.46A0.41,0.41,0,0,1,15,5.57a0.84,0.84,0,0,1,.83.34,3.38,3.38,0,0,1,.41.86A5.74,5.74,0,0,0,12,8.93a6.61,6.61,0,0,0-.83,5.68,40.57,40.57,0,0,0,2,6.23v0.07C14.85,25.68,18,37.44,2.63,43.68a6.33,6.33,0,0,0,2.56.62H6.78a20,20,0,0,0,6.84-5.67c7.05,3.11,13.46,1.52,16.24-3.6A6.77,6.77,0,0,0,33,30a5.19,5.19,0,0,0,1-4.48c-0.07-.28-0.34-0.28-0.76-0.07-5.74,3.46-10.78,4-16.8,2.22a45.53,45.53,0,0,0-.83-5.61c-0.14-2.42.62-3.6,5-2.15a13.71,13.71,0,0,1,5.25,2.79c0.46,0.34,1.1.76,1.45,0.46a1.33,1.33,0,0,0,.28-1,11.58,11.58,0,0,0-1.24-4.36,36.1,36.1,0,0,1,3.94,0,2.23,2.23,0,0,1,2,1.52c0.46,1.39,3.18,1,3.39-.14,0.41-2.42.55-5.61-1.8-7.82h0ZM3.25,32.11a25.44,25.44,0,0,0-3.25,0v1.45c1.86-.41,3-0.62,3-0.62Z"
          ></path>
          <path
            style="fill: #fff"
            d="M20.54,17c-2.42-.55-5.1-1.25-6.5-3.32,0-.07-0.07-0.07-0.14-0.07l0,0a0.07,0.07,0,0,0,0,0,0.62,0.62,0,0,0,.07.34l-0.21.07a1.39,1.39,0,0,1-.07-1.66,1.78,1.78,0,0,1,2.28-.21l-0.07.21a1.52,1.52,0,0,0-1,.07,0.38,0.38,0,0,0-.2.24,0.38,0.38,0,0,0,.06.31c1.17,2.22,4.64,2.7,8.71,2.36A0.49,0.49,0,0,0,24,15a7.85,7.85,0,0,1,1.93-3.67,10.82,10.82,0,0,1-2,.14c-2.07.14-3.32-.14-3.67-0.41l0.07-.21a0.49,0.49,0,0,0,.46,0,0.26,0.26,0,0,0-.07-0.21c-0.39-.37-2.19-2.23-2.19-2.23C18.32,6.77,16,6.77,15.14,8.29l-0.28-.07a2.33,2.33,0,0,1,.34-0.83A4.35,4.35,0,0,0,12,11.11c-0.83,7.06,9.88,5.4,12.93,8.24,0.07,0.07.21,0.28,0.28,0.14s-1.24-1.8-4.7-2.56v0ZM16.82,8.48a1.67,1.67,0,0,1,1.59,1.11c0.35,0.76.28,1.52-.21,1.73a1.55,1.55,0,0,1-1.61-1.1c-0.07-.14-0.07-0.21-0.14-0.34h0.07A0.46,0.46,0,0,0,17,10a0.52,0.52,0,0,0,0-.69,0.64,0.64,0,0,0-.55-0.41l-0.07-.07a0.93,0.93,0,0,1,.41-0.34"
          ></path>
          <path
            style="fill: #fff"
            d="M32.7,27.55a19.13,19.13,0,0,1-8.92,2.91,24.42,24.42,0,0,1-7.19-.69,10.59,10.59,0,0,1-.21,2.08,28.73,28.73,0,0,0,6.15.76,10.33,10.33,0,0,1-3,5.26c3.71,0.14,7.12-1.31,8.16-3.25a14.11,14.11,0,0,1-4.64.62c0.07-.21.21-0.34,0.28-0.55,3.18-.14,6.64-1.18,7.33-3.81a14.91,14.91,0,0,1-6.77,1.94c0-.21.07-0.34,0.07-0.55,3.71-.46,7.67-2.08,8.71-4.71"
          ></path>
          <path
            d="M58.5,37.73c0-1.63.78-3.43,2.68-3.43,1.32,0,1.56.84,2,.84a0.46,0.46,0,0,0,.43-0.5c0-.43-1-1.25-2.47-1.25-2.53,0-3.8,2.12-3.8,4.34s1.27,4.34,3.74,4.34c1.5,0,2.71-.65,2.71-1.19a0.43,0.43,0,0,0-.42-0.49c-0.44,0-1,.77-2.29.77C59.3,41.16,58.5,39.36,58.5,37.73ZM66,39.22h4a0.49,0.49,0,0,0,.59-0.56,2.91,2.91,0,0,0-2.75-3.11,3,3,0,0,0-2.87,3.26c0,1.69.89,3.26,2.93,3.26,1.25,0,2.56-.79,2.56-1.31A0.42,0.42,0,0,0,70,40.3c-0.4,0-.76.86-2.16,0.86A1.82,1.82,0,0,1,66,39.22Zm3.5-.79H66a1.77,1.77,0,0,1,1.81-2A1.8,1.8,0,0,1,69.47,38.42Zm2.39-1.84H73.2v4.86a0.53,0.53,0,0,0,.52.62,0.54,0.54,0,0,0,.53-0.62V36.59h1.33a0.47,0.47,0,0,0,.53-0.49,0.46,0.46,0,0,0-.53-0.48H71.86a0.46,0.46,0,0,0-.53.48A0.47,0.47,0,0,0,71.86,36.59Zm8.22,1.63H78.36V36.17a0.54,0.54,0,0,0-.53-0.62,0.53,0.53,0,0,0-.52.62v5.28a0.51,0.51,0,0,0,.6.55h1.93c1.7,0,2.44-.9,2.44-1.91S81.6,38.22,80.08,38.22Zm-0.23,2.84h-1.5V39.13h1.5c1,0,1.38.35,1.38,1S80.62,41.06,79.86,41.06Zm8.32,0.38V36.58H91.1v4.87a0.53,0.53,0,1,0,1,0V36.07a0.44,0.44,0,0,0-.48-0.46h-4a0.49,0.49,0,0,0-.53.56v5.27a0.53,0.53,0,0,0,.52.62A0.54,0.54,0,0,0,88.18,41.45Zm6.94,0.22,3-4.32v4.1a0.53,0.53,0,1,0,1,0V36.13a0.51,0.51,0,0,0-.5-0.59A0.76,0.76,0,0,0,98,36l-3,4.28V36.17a0.53,0.53,0,0,0-.53-0.62,0.53,0.53,0,0,0-.52.62v5.29a0.49,0.49,0,0,0,.49.61A0.68,0.68,0,0,0,95.11,41.66ZM101.53,42h4.55v1.16a0.51,0.51,0,0,0,.5.62,0.52,0.52,0,0,0,.5-0.62V41.56a0.5,0.5,0,0,0-.52-0.52h-0.5V36.17a0.53,0.53,0,1,0-1,0V41H102.1V36.17a0.54,0.54,0,0,0-.53-0.62,0.53,0.53,0,0,0-.52.62v5.38A0.43,0.43,0,0,0,101.53,42Zm7.37,0h4.55v1.16a0.51,0.51,0,0,0,.5.62,0.52,0.52,0,0,0,.5-0.62V41.56a0.5,0.5,0,0,0-.52-0.52h-0.5V36.17a0.53,0.53,0,1,0-1,0V41h-2.93V36.17a0.54,0.54,0,0,0-.53-0.62,0.53,0.53,0,0,0-.52.62v5.38A0.43,0.43,0,0,0,108.9,42Zm7.56-2.78h4a0.49,0.49,0,0,0,.59-0.56,2.91,2.91,0,0,0-2.75-3.11,3,3,0,0,0-2.87,3.26c0,1.69.89,3.26,2.93,3.26,1.25,0,2.56-.79,2.56-1.31a0.42,0.42,0,0,0-.38-0.47c-0.4,0-.76.86-2.16,0.86A1.82,1.82,0,0,1,116.46,39.22Zm3.5-.79h-3.5a1.77,1.77,0,0,1,1.81-2A1.8,1.8,0,0,1,120,38.42Zm2.59-2.32V44a0.53,0.53,0,1,0,1.06,0V41.21h0a2.09,2.09,0,0,0,1.7.86c1.73,0,2.72-1.57,2.72-3.26s-1-3.26-2.72-3.26a1.74,1.74,0,0,0-1.7.88h0V36.11A0.53,0.53,0,1,0,122.56,36.11Zm0.95,2.7c0-1.08.46-2.35,1.75-2.35S127,37.73,127,38.81s-0.46,2.35-1.75,2.35S123.5,39.89,123.5,38.81Zm7.24,2.86,3-4.32v4.1a0.53,0.53,0,1,0,1,0V36.13a0.51,0.51,0,0,0-.5-0.59,0.76,0.76,0,0,0-.64.41l-3,4.28V36.17a0.53,0.53,0,0,0-.53-0.62,0.53,0.53,0,0,0-.52.62v5.29a0.49,0.49,0,0,0,.49.61A0.68,0.68,0,0,0,130.75,41.66Zm6.95-8a1.71,1.71,0,0,0,3.24,0,0.39,0.39,0,0,0-.37-0.43c-0.37,0-.58.68-1.25,0.68s-0.88-.68-1.25-0.68A0.39,0.39,0,0,0,137.69,33.64Zm0.08,8,3-4.32v4.1a0.53,0.53,0,1,0,1,0V36.13a0.51,0.51,0,0,0-.5-0.59,0.76,0.76,0,0,0-.64.41l-3,4.28V36.17a0.53,0.53,0,0,0-.53-0.62,0.53,0.53,0,0,0-.52.62v5.29a0.49,0.49,0,0,0,.49.61A0.68,0.68,0,0,0,137.78,41.66Zm19-8.32A2.38,2.38,0,1,0,159,35.74,2.22,2.22,0,0,0,156.76,33.35Zm-3.22,8.1V34a0.53,0.53,0,0,0-.53-0.64,0.53,0.53,0,0,0-.53.64v6h0l-4-6.13a0.76,0.76,0,0,0-.66-0.46,0.53,0.53,0,0,0-.53.6v7.45a0.53,0.53,0,0,0,.53.64,0.53,0.53,0,0,0,.53-0.64v-6h0l4.09,6.19a0.72,0.72,0,0,0,.62.46A0.51,0.51,0,0,0,153.54,41.45Zm3.22-7.31a1.38,1.38,0,0,1,1.22,1.6,1.37,1.37,0,0,1-1.22,1.56,1.38,1.38,0,0,1-1.22-1.58A1.37,1.37,0,0,1,156.76,34.14ZM158.29,39h-3a0.47,0.47,0,1,0,0,.94h3A0.47,0.47,0,1,0,158.29,39Zm6-4.58h1.1v7.14a0.53,0.53,0,1,0,1.06,0V33.74c0-.26-0.12-0.29-0.32-0.29h-1.84A0.46,0.46,0,0,0,164.26,34.37Zm8,1.79v5.29a0.51,0.51,0,0,0,.6.55h1.93c1.61,0,2.44-.8,2.44-1.86a1.47,1.47,0,0,0-1.49-1.55v0a1.38,1.38,0,0,0,1-1.34c0-1.13-.84-1.61-2-1.61h-1.81A0.5,0.5,0,0,0,172.27,36.16Zm2.11,2.1h-1.07V36.5h1.25a0.93,0.93,0,0,1,1.13.84C175.69,38.05,175.16,38.26,174.38,38.26Zm0.43,2.86h-1.5v-2h1.4c1.07,0,1.48.38,1.48,1S175.63,41.11,174.82,41.11Zm8.47,0.4V37.93l4,3.91a0.66,0.66,0,0,0,.52.23,0.5,0.5,0,0,0,.52-0.47,0.54,0.54,0,0,0-.22-0.43l-3.83-3.7,3.5-3.16a0.54,0.54,0,0,0,.22-0.48,0.43,0.43,0,0,0-.46-0.46,0.91,0.91,0,0,0-.58.34l-3.66,3.35V33.95a0.53,0.53,0,1,0-1.06,0v7.56A0.53,0.53,0,1,0,183.29,41.51Zm11.6,0v-5.5a0.49,0.49,0,0,0-.49-0.52,0.48,0.48,0,0,0-.49.52V36.4h0a2.23,2.23,0,0,0-1.74-.85c-1.8,0-2.81,1.57-2.81,3.26s1,3.26,2.81,3.26a2.07,2.07,0,0,0,1.74-1h0v0.44a0.48,0.48,0,0,0,.49.52A0.49,0.49,0,0,0,194.88,41.56Zm-4.5-2.75c0-1.08.46-2.35,1.75-2.35s1.75,1.27,1.75,2.35-0.46,2.35-1.75,2.35S190.38,39.89,190.38,38.81Zm11,1.32a1.58,1.58,0,0,0-1.45-1.56A1.49,1.49,0,0,0,201,37.12c0-.89-0.73-1.62-2.23-1.62-1.18,0-2.2.53-2.2,1a0.44,0.44,0,0,0,.44.44,0.6,0.6,0,0,0,.34-0.12,2.18,2.18,0,0,1,1.34-.46c0.9,0,1.24.41,1.24,0.88s-0.52.95-1.76,0.95a0.5,0.5,0,0,0-.58.46,0.49,0.49,0,0,0,.58.46c1.18,0,2.08.14,2.08,1,0,0.61-.55,1.06-1.61,1.06-1.27,0-1.63-.74-2-0.74a0.49,0.49,0,0,0-.47.54c0,0.42.85,1.09,2.45,1.09C200.46,42.1,201.35,41.16,201.35,40.13Zm6.79,1.43v-5.5a0.49,0.49,0,0,0-.49-0.52,0.48,0.48,0,0,0-.49.52V36.4h0a2.23,2.23,0,0,0-1.74-.85c-1.8,0-2.81,1.57-2.81,3.26s1,3.26,2.81,3.26a2.07,2.07,0,0,0,1.74-1h0v0.44a0.48,0.48,0,0,0,.49.52A0.49,0.49,0,0,0,208.14,41.56Zm-4.5-2.75c0-1.08.46-2.35,1.75-2.35s1.75,1.27,1.75,2.35-0.46,2.35-1.75,2.35S203.64,39.89,203.64,38.81Zm6.19-2.36,1.66,2.17-1.88,2.47a0.87,0.87,0,0,0-.22.5,0.47,0.47,0,0,0,.48.48,0.57,0.57,0,0,0,.47-0.24l1.76-2.45,1.76,2.45a0.57,0.57,0,0,0,.47.24,0.47,0.47,0,0,0,.48-0.48,0.87,0.87,0,0,0-.22-0.5l-1.88-2.47,1.66-2.17a0.71,0.71,0,0,0,.18-0.42,0.46,0.46,0,0,0-.44-0.48,0.53,0.53,0,0,0-.46.24l-1.55,2.06-1.55-2.06a0.53,0.53,0,0,0-.46-0.24,0.46,0.46,0,0,0-.44.48A0.71,0.71,0,0,0,209.82,36.44Zm5.95,2.36c0,1.69.94,3.26,2.88,3.26,1.09,0,1.68-.43,1.68-0.83a0.4,0.4,0,0,0-.41-0.44,5,5,0,0,1-1.27.36c-1.31,0-1.82-1.27-1.82-2.35s0.52-2.35,1.82-2.35a7.23,7.23,0,0,1,1.28.34,0.45,0.45,0,0,0,.43-0.44c0-.43-0.64-0.8-1.72-0.8C216.71,35.54,215.77,37.12,215.77,38.81Zm5.94-2.22h1.34v4.86a0.53,0.53,0,0,0,.52.62,0.54,0.54,0,0,0,.53-0.62V36.59h1.33A0.47,0.47,0,0,0,226,36.1a0.46,0.46,0,0,0-.53-0.48h-3.72a0.46,0.46,0,0,0-.53.48A0.47,0.47,0,0,0,221.72,36.59Zm10.73,5v-5.5a0.49,0.49,0,0,0-.49-0.52,0.48,0.48,0,0,0-.49.52V36.4h0a2.23,2.23,0,0,0-1.74-.85c-1.8,0-2.81,1.57-2.81,3.26s1,3.26,2.81,3.26a2.07,2.07,0,0,0,1.74-1h0v0.44a0.48,0.48,0,0,0,.49.52A0.49,0.49,0,0,0,232.45,41.56ZM228,38.81c0-1.08.46-2.35,1.75-2.35s1.75,1.27,1.75,2.35-0.46,2.35-1.75,2.35S228,39.89,228,38.81Zm7.41,2.64V39.17h3v2.28a0.53,0.53,0,1,0,1,0V36.17a0.53,0.53,0,1,0-1,0v2.08h-3V36.17a0.53,0.53,0,0,0-.53-0.62,0.53,0.53,0,0,0-.52.62v5.28a0.53,0.53,0,0,0,.52.62A0.54,0.54,0,0,0,235.36,41.45ZM242,39.22h4a0.49,0.49,0,0,0,.59-0.56,2.91,2.91,0,0,0-2.75-3.11,3,3,0,0,0-2.87,3.26c0,1.69.89,3.26,2.93,3.26,1.25,0,2.56-.79,2.56-1.31A0.42,0.42,0,0,0,246,40.3c-0.4,0-.76.86-2.16,0.86A1.82,1.82,0,0,1,242,39.22Zm3.5-.79H242a1.77,1.77,0,0,1,1.81-2A1.8,1.8,0,0,1,245.49,38.42Z"
          ></path>
        </svg>
        <div class="hidden lg:block">
          <p class="text-base font-medium">
            Доставка пиццы
            <span
              @click="showCityList"
              id="menu-button"
              class="text-main cursor-pointer"
              >{{ selectedCity }}</span
            >
          </p>
          <p class="text-base">27 мин <span>·</span> 4.83</p>
        </div>
      </div>
      <div class="hidden lg:block px-5 mr-auto">
        <p class="font-medium">+7 707 447-07-07</p>
        <p class="text-xs text-gray-500 font-semibold">Звонок по телефону</p>
      </div>
      <div class="px-5 flex-col items-center ml-auto hidden lg:flex">
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M11 1a1 1 0 011 1v2a8 8 0 110 16v2a1 1 0 11-2 0v-2H6.6c-.56 0-.84 0-1.054-.109a1 1 0 01-.437-.437C5 19.24 5 18.96 5 18.4V5.6c0-.56 0-.84.109-1.054a1 1 0 01.437-.437C5.76 4 6.04 4 6.6 4H10V2a1 1 0 011-1zm1 17a6 6 0 000-12H7v12h5z"
            fill="#000"
          ></path>
        </svg>

        <p class="text-sm font-semibold">Додокоины</p>
      </div>
      <button
        v-if="currentUser != null"
        @click="showModal = 1"
        class="py-2 px-4 rounded-full bg-gray-200 hover:bg-main hover:text-white"
      >
        {{ currentUser }}
      </button>
      <div class="w-full flex lg:w-auto">
        <button
          v-if="currentUser === null"
          @click="showModalReg = 1"
          class="py-2 px-4 rounded-full bg-gray-200 hover:bg-main hover:text-white mr-5 mt-4 lg:mt-0"
        >
          Зарегистрироваться
        </button>
        <button
          v-if="currentUser === null"
          @click="showModal = 1"
          class="py-2 px-4 rounded-full bg-gray-200 hover:bg-main hover:text-white mt-4 lg:mt-0 ml-auto"
        >
          Войти
        </button>
      </div>
    </div>
    <div class="flex justify-between items-center px-4 lg:px-0">
      <ul class="list-none hidden lg:flex">
        <li
          class="py-5 cursor-pointer hover:text-main text-sm mx-3 first:ml-0 last:mr-0"
          v-for="item of category"
          :key="item"
        >
          {{ item }}
        </li>
      </ul>
      <button
        @click="showCart = 1"
        class="bg-main text-white ml-auto py-2 px-4 rounded-full"
      >
        Корзина | <span>{{ countOrders }}</span>
      </button>
    </div>
    <div
      v-if="showModal === 1"
      class="fixed bg-black w-full h-full top-0 left-0 bg-opacity-50"
    >
      <div class="relative w-full h-full">
        <div
          v-if="currentUser === null"
          class="abs p-10 bg-white rounded-2xl w-full lg:w-1/3"
        >
          <p class="text-3xl font-medium">Войти</p>
          <div class="mt-4">
            <input
              v-model="form.login"
              class="border-2 w-full p-2 rounded-lg my-2"
              placeholder="Введите логин"
              type="text"
            />
            <input
              v-model="form.password"
              class="border-2 w-full p-2 rounded-lg my-2"
              placeholder="Введите пароль"
              type="text"
            />
            <div class="flex items-center justify-evenly mt-4">
              <button
                @click="validateUser()"
                class="py-2 px-4 rounded-lg bg-main text-white"
              >
                Войти
              </button>
              <button
                @click="showModal = 0"
                class="py-2 px-4 rounded-lg bg-gray-200"
              >
                Закрыть
              </button>
            </div>
          </div>
        </div>
        <div
          v-if="currentUser != null"
          class="abs p-10 bg-white rounded-2xl w-full lg:w-1/3"
        >
          <p class="text-3xl font-medium">Выйти</p>
          <p class="mt-4">Вы уверены что хотите выйти, {{ currentUser }}?</p>
          <div class="mt-4">
            <div class="flex items-center justify-evenly mt-4">
              <button
                @click="showModal = 0"
                class="py-2 px-4 rounded-lg bg-gray-200"
              >
                Закрыть
              </button>
              <button
                @click="logout()"
                class="py-2 px-4 rounded-lg bg-main text-white"
              >
                Выйти
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div
      v-if="showModalReg === 1"
      class="fixed bg-black w-full h-full top-0 left-0 bg-opacity-50"
    >
      <div class="relative w-full h-full">
        <div class="abs p-10 bg-white rounded-2xl w-full lg:w-1/3">
          <p class="text-3xl font-medium">Зарегистрироваться</p>
          <div class="mt-4">
            <input
              v-model="reg.name"
              class="border-2 w-full p-2 rounded-lg my-2"
              placeholder="Введите имя"
              type="text"
            />
            <input
              v-model="reg.login"
              class="border-2 w-full p-2 rounded-lg my-2"
              placeholder="Введите логин"
              type="text"
            />
            <input
              v-model="reg.phone"
              class="border-2 w-full p-2 rounded-lg my-2"
              placeholder="Введите телефон"
              type="text"
            />
            <input
              v-model="reg.password"
              class="border-2 w-full p-2 rounded-lg my-2"
              placeholder="Введите пароль"
              type="text"
            />
            <div class="flex items-center justify-evenly mt-4">
              <button
                @click="registerUser()"
                class="py-2 px-4 rounded-lg bg-main text-white"
              >
                Войти
              </button>
              <button
                @click="showModalReg = 0"
                class="py-2 px-4 rounded-lg bg-gray-200"
              >
                Закрыть
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div
      v-show="showCart === 1"
      class="fixed bg-black w-full h-full top-0 left-0 bg-opacity-50"
      @click.self="showCart = 0"
    >
      <div
        v-if="activeOrder && activeOrder.products.length"
        class="absolute right-0 top-0 w-full lg:w-1/4 bg-slate-200 h-full flex flex-col pt-5"
      >
        <i
          class="fa-solid fa-x lg:text-4xl text-2xl absolute lg:top-1/2 cursor-pointer font-bold text-black lg:text-white lg:-left-10 right-4 top-4"
          @click="showCart = 0"
        ></i>
        <p class="px-3 text-xl font-medium">
          {{ activeOrder.products.length }} товара на
          {{ activeOrder.totalOfProducts }} тг.
        </p>
        <div class="overflow-y-auto overflow-x-hidden scroll-m-0 flex-grow">
          <transition-group name="flip-list" tag="div">
            <div
              class="bg-white my-2 p-4 cart-item"
              v-for="(item, idx) of activeOrder.products"
              :key="item.id"
            >
              <div class="flex items-start pb-4 border-b-2 border-gray-200">
                <img class="mr-5 w-1/5" :src="item.image" alt="" />
                <div>
                  <p class="text-lg font-medium mb-2">{{ item.title }}</p>
                  <p class="text-xs mb-2">
                    {{ pizzaSize[item.size] }}, традиционное тесто
                  </p>
                  <p
                    v-if="item.ingredients && item.ingredients.length"
                    class="text-xs"
                  >
                    +
                    <span
                      v-for="(ing, ind) of item.ingredients"
                      :key="ing.title"
                    >
                      {{ ing.title
                      }}{{ item.ingredients.length - (ind + 1) ? ', ' : '' }}
                    </span>
                  </p>
                </div>
              </div>
              <div
                class="flex items-center text-lg font-medium justify-between mt-3"
              >
                <p>{{ item.price }}</p>
                <button
                  @click="removePizza(idx)"
                  class="block px-3 py-2 rounded-md bg-slate-200 text-xs"
                >
                  Удалить
                </button>
              </div>
            </div>
          </transition-group>
        </div>
        <div class="p-4 bg-white shadow-xl">
          <button
            class="py-2 px-4 rounded-lg bg-slate-200 text-black w-full mb-5"
            @click="removeOrder"
          >
            Очистить
          </button>
          <button
            class="py-2 px-4 rounded-lg bg-main text-white w-full"
            @click="endOrder"
          >
            Заказать
          </button>
        </div>
      </div>
      <div
        v-else
        class="absolute right-0 top-0 bg-slate-200 h-full flex justify-center items-center flex-col pt-5 w-full lg:w-1/4"
      >
        <img
          class="w-3/4"
          src="https://dodopizza-a.akamaihd.net/site-static/dist/121df529925b0f43cc73.svg"
          alt=""
        />
        <h2 class="my-5 text-xl font-semibold">Ой, пусто!</h2>
        <p class="w-2/3 text-center">
          Ваша корзина пуста, откройте «Меню» и выберите понравившийся товар. Мы
          доставим ваш заказ от 3 000 тг.
        </p>
        <i
          class="fa-solid fa-x text-4xl absolute lg:top-1/2 cursor-pointer font-bold text-black lg:text-white lg:-left-10 right-4 top-4"
          @click="showCart = 0"
        ></i>
      </div>
    </div>
    <div
      @click="showSelectCity = false"
      v-show="showSelectCity"
      class="absolute left-0 top-0 bottom-0 right-0"
    >
      <div
        v-show="showSelectCity"
        class="z-10 abs-city mt-2 w-56 rounded-md shadow-lg bg-white ring-1 ring-black ring-opacity-5 focus:outline-none"
      >
        <div class="py-1">
          <div
            class="hover:bg-gray-100 hover:text-gray-900 text-gray-700 text-sm"
            v-for="city of cities"
            :key="city"
          >
            <input
              type="radio"
              tabindex="-1"
              name="city"
              :id="city"
              :value="city"
              v-model="selectedCity"
              v-on:click="sendSelectCity($event.target.value)"
              hidden
            />
            <label class="block cursor-pointer px-4 py-2" :for="city">{{
              city
            }}</label>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import axios from 'axios';

export default {
  name: 'SetHeader',
  data() {
    return {
      pizzaSize: {
        0: 'Маленькая 25 см',
        1: 'Средняя 30 см',
        2: 'Большая 35 см',
      },
      selectedCity: 'Нур-Султан',
      showSelectCity: false,
      cities: ['Нур-Султан', 'Алматы', 'Караганда', 'Актау'],
      category: [
        'Пицца',
        'Комбо',
        'Закуски',
        'Десерты',
        'Напитки',
        'Другие товары',
        'Акции',
        'Контакты',
      ],
      show: false,
      showCart: 0,
      showModal: 0,
      showModalReg: 0,
      showError: 0,
      users: null,
      currentUser: localStorage.getItem('loggedUser'),
      orders: null,
      activeOrder: null,
      form: {
        login: null,
        password: null,
      },
      reg: {
        login: null,
        phone: null,
        name: null,
        password: null,
      },
    };
  },
  computed: {
    countOrders() {
      return this.activeOrder ? this.activeOrder.products.length : 0;
    },
  },
  async mounted() {
    let res = await axios.get(
      'https://628512d6a48bd3c40b7a955d.mockapi.io/users'
    );
    this.users = res.data;

    await this.$store.dispatch('getOrdersAsync');
    this.activeOrder = this.$store.getters.order(this.currentUser);
  },
  methods: {
    async endOrder() {
      if (this.activeOrder) {
        let index = this.$store.getters.order(this.currentUser, true);
        this.activeOrder.status = true;
        await axios.put(
          'https://628512d6a48bd3c40b7a955d.mockapi.io/orders/' + index,
          this.activeOrder
        );
        this.$router.go();
      }
    },
    async removePizza(idx) {
      this.activeOrder.products.splice(idx, 1);
      this.activeOrder.totalOfProducts = 0;
      this.activeOrder.products.forEach((element) => {
        this.activeOrder.totalOfProducts =
          this.activeOrder.totalOfProducts + element.price;
      });
      await axios.put(
        'https://628512d6a48bd3c40b7a955d.mockapi.io/orders/' +
          this.activeOrder.id,
        this.activeOrder
      );
    },
    async removeOrder() {
      await axios
        .delete(
          'https://628512d6a48bd3c40b7a955d.mockapi.io/orders/' +
            this.activeOrder.id
        )
        .then(() => this.$router.go());
    },
    sendSelectCity(e) {
      this.showSelectCity = false;
      this.selectedCity = e;
    },
    showCityList(e) {
      this.showSelectCity = true;
      const cityMenuElem = document.querySelector('.abs-city');
      cityMenuElem.style.top = e.target.offsetTop + 20 + 'px';
      cityMenuElem.style.left = e.target.offsetLeft + 'px';
    },
    validateUser() {
      this.users.forEach((element) => {
        if (
          this.form.login === element.login &&
          this.form.password === element.password
        ) {
          localStorage.setItem('loggedUser', element.login);
          this.$router.go();
        } else if (this.form.login === '' || this.form.login === null) {
          console.log('Поле логина пустое');
          this.showError = 1;
        }
      });
    },
    logout() {
      localStorage.removeItem('loggedUser');
      this.$router.go();
    },
    async registerUser() {
      await axios.post('https://628512d6a48bd3c40b7a955d.mockapi.io/users', {
        login: this.reg.login,
        phone: this.reg.phone,
        name: this.reg.name,
        password: this.reg.password,
      });
      this.$router.go();
    },
  },
};
</script>
