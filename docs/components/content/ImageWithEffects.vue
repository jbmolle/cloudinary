<template>
  <CldImage
    src="cld-sample-5"
    width="900"
    height="900"
    alt="Sample Product"
    crop="fill"
    :effects="[
      {
        background: 'green',
      },
      {
        gradientFade: true,
      },
      {
        gradientFade: 'symetric,x_0.5',
      },
    ]"
  />
</template>
