

点击 <router-link :to="...">等同于调用this.$router.push(),都会向history栈加入一个新记录
router.replace() 不会向history添加新记录,而是替换掉当前的history记录

this.$router.push({name : 'suer',params:{userId:'123'}})