<template>
    <div class="main">
Copyright © 2018 上海开创广告有限公司 版权所有 All rights reserved. <svg-icon icon-class="mit" class="card-panel-icon"  />
<span class="build"><svg-icon icon-class="building" class="card-panel-icon" /></span>
<span class="npm"><svg-icon icon-class="npm" class="card-panel-icon" /></span>
</div>
</template>
<script>
export default {
    name: 'FooterBar'
}
</script>
<style scoped>
.main{
 text-align: center; padding-top: 10px; padding-bottom: 10px;
 font-size: 14px;
 background: #f0f2f5;
 color: #909399;
}
.main >>> .svg-icon{
   width: 3.9em; height:1em;
}
.build >>> .svg-icon{
   width: 5.3em; height:1em;
}
.npm >>> .svg-icon{
   width: 4.4em; height:1em;
}

</style>
