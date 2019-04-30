<template>
  <div>
    <div class="name">
      nihai
      <ul class="name1">
        <li class="name3">1</li>
        <li class="name3">2</li>
        <li class="name3">3</li>
      </ul>
    </div>
  </div>
</template>
<script>
import page from '@/components/page'
import { Tab, TabItem, XButton, Swiper, SwiperItem} from 'vux'
const list = () => ['精选', '美食']
export default {
  data () {
    return {      

    }
  },
  components:{
    page,  
    Tab,
    TabItem,
    XButton,
    Swiper,
    SwiperItem
  }
}
</script>




