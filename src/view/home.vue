<template>
    <section class="pic">
      <div class="pic-items">
        <img src="https://hdbbmp-dev.oss-cn-shenzhen.aliyuncs.com/hdb/2020/09/10/d5ddfaef6f43405895b3985979f00178" large="https://hdbbmp-dev.oss-cn-shenzhen.aliyuncs.com/hdb/2020/09/10/d5ddfaef6f43405895b3985979f00178" preview="2" preview-text="缩略图与大图模式">
      </div>
      <div class="pic-items">
        <img src="https://hdbbmp-dev.oss-cn-shenzhen.aliyuncs.com/hdb/2020/09/04/b566b6c6ba9d4608b42749c541ff6bca" large="https://hdbbmp-dev.oss-cn-shenzhen.aliyuncs.com/hdb/2020/09/04/b566b6c6ba9d4608b42749c541ff6bca" preview="2" preview-text="缩略图与大图模式">
      </div>
      <div class="pic-items">
        <img src="https://hdbbmp-dev.oss-cn-shenzhen.aliyuncs.com/hdb/2020/09/04/b566b6c6ba9d4608b42749c541ff6bca" large="https://hdbbmp-dev.oss-cn-shenzhen.aliyuncs.com/hdb/2020/09/04/b566b6c6ba9d4608b42749c541ff6bca" preview="2" preview-text="缩略图与大图模式">
      </div>
      <div class="pic-items">
        <img src="https://hdbbmp-dev.oss-cn-shenzhen.aliyuncs.com/2018/1_1_1/1d137d4a-b1cc-4359-b61e-e6e2742aae8d.jpg" large="https://hdbbmp-dev.oss-cn-shenzhen.aliyuncs.com/2018/1_1_1/1d137d4a-b1cc-4359-b61e-e6e2742aae8d.jpg" preview="2" preview-text="缩略图与大图模式">
      </div>
    </section>
</template>

<script>
export default {
  name: 'home'
}
</script>

<style scoped>
  .pic{
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    flex-wrap: wrap;
    padding: 5px;
  }
  .pic-items{
    width: 50%;
    padding: 5px;
  }
  img{
    border-radius: 10px;
  }
</style>
