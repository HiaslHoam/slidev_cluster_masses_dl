# What can we do next?
<div class="grid grid-cols-2 gap-5 justify-center justify-items-center items-center">
<div class="list opacity-40">

* Continue to optimize the parameters for ResNet 
* Usage of ResNet50V2 is especially promising, because it combines accuracy and training efficiency
* Try different input parameters (e.g. input image resolution, frequencies etc.)

</div>

<div class="opacity-100">
  <img src="/images/results/test_ResNet50V2_hist.png" class="max-h-100 shadow-xl" />

<p class="text-sm text-gray-500"> 

Improved ResNet50V2 model with a $\sigma = 0.132$ compared to the $\sigma = 0.14$ from my thesis. This was achieved by continuing the training of the best performing model with a variable learning rate.

</p>
</div>

</div>

<style>

  .list li{
    margin-bottom: 1.8rem !important;
  }
</style>