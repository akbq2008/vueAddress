<addressSelect
                @currentSelected="selected"
                :resetData="resetData"
              ></addressSelect>

//val，输出的是选中的值
 selected(val) {
      console.log(val);
    },


重置地址值   
this.resetData = true;
    setTimeout(() => {
         this.resetData = false;
   }, 20);
