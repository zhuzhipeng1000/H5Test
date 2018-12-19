<template>
 
    <div class="Myimage">
      <Myimage id=Myimage style="font-size:50px; color: #ff0000">你好，image</Myimage>
    </div>

</template>


<style>
  .title{
    position:absolute;
    top:50;
    left:10;
  }
</style>
function aa(aa){
  var event = weex.requireModule('event')
  event.openURL('test.js',function(ret) { 
                                      //回调执行
                     self.loadVersionData(ret.result);


                   }）
}

