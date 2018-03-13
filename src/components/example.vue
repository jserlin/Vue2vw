<template>
  <div class="example">
    <div class="aa">摩西摩西</div>
    <div aspectratio w-188-246>
      <div aspectratio-content>auto</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'example',
  data () {
    return {
      msg: 'example'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
[aspectratio] {
  position: relative;
}
[aspectratio]::before {
  content: '';
  display: block;
  width: 1px;
  margin-left: -1px;
  height: 0;
}
[aspectratio-content] {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  height: 100%;
}
[w-188-246] {
  width: 188px;
  background-color: red;
}
[w-188-246] {
  aspect-ratio: '188:246';
}
@svg 1px-border { 
  height: 2px; 
  @rect { 
     fill: var(--color, black);
     width: 100%;
     height: 50%; 
     }
 } 
.example { 
  border: 1px solid transparent; 
  border-image: svg(1px-border param(--color #00b1ff)) 2 2 stretch;
}

</style>
