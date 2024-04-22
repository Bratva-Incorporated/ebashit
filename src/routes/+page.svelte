<div class="w-screen h-screen grid items-center justify-center bg-red-500">
  <h1 class="font-bold text-size-9xl text-center strobe-text">EBASHIT</h1>
</div>

<style>
  .strobe-text {
    color: white;
    animation: strobeEffect 0.15s steps(1, end) infinite; /* 66ms is roughly equivalent to about 15 frames per second */
  }

  @keyframes strobeEffect {
    0%,
    49.99% {
      color: white;
    }
    50%,
    100% {
      color: black;
    }
  }
</style>
