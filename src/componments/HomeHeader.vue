<template>
  <div id="top-header">
    <div class="menu">
      <div class="unicreation">Về UniCreation</div>
      <div class="thanhtoan">Thanh Toán</div>
      <div class="tintuc">Tin Tức</div>
      <div class="website">Kiến Thức Website</div>
      <div class="tuyendung">Tuyển Dụng</div>
      <div class="lienhe">Liên Hệ</div>
      <div>
        <form v-on:submit.prevent=additem>
          <img @click="showSearch" src="../assets/btsearch.png">
          <input type="text" placeholder="Tìm kiếm ..." v-if="search" v-model="itemSearch">
          <a @click="search = daux = false" v-if="daux">x</a>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      itemSearch: null,
      search: false,
      daux: false
    }
  },
  methods: {
    showSearch() {
      this.search = true;
      this.daux = true;
      this.itemSearch = null;
    },
    additem() {
      this.itemSearch = null;
    }
  }
}
</script>

<style >


#top-header {
  background-color: #fafafa;
  width: 100%;
  height: 100%;
  display: flex; /* Sử dụng flexbox để căn giữa theo chiều dọc và ngang */
  justify-content: center; /* Căn giữa theo chiều ngang */
  align-items: center; /* Căn giữa theo chiều dọc */
   position: relative;
   padding: 0;
   margin: 0;
}
.menu {
  padding: 0;
   margin: 0;
  width: 100%;
  max-width: 1200px;
  display: flex;
  /* tất cả thành phần năm ngang*/
  justify-content:end;
  /* tất cả thành phần ở cuoois*/
  align-items: center;
  text-align: center;
  height: 100%;
   flex-wrap: wrap; 
  /* cho phép nếu màn hình nhỏ quá thì các phần tử được xuống dòng */
}

.menu>* {
  margin: 8px 0;
}

.unicreation {
  cursor: pointer;
  /* Thay đổi thành bàn tay*/
  width: 112px;
  margin-left: 16px;
  margin-right: 16px;
  font-size: 16px;
  position: relative;
  color: #333333;
}

.unicreation:hover {
  /* Thay đổi màu sắc khi di chuột vào*/
  color: #06b5ad;
}

.thanhtoan {
  cursor: pointer;
  width: 85px;
  margin-left: 16px;
  margin-right: 16px;
  position: relative;
  color: #333333;
}

.thanhtoan:hover {
  color: #06b5ad;
}

.tintuc {
  cursor: pointer;
  width: 60px;
  margin-left: 16px;
  margin-right: 16px;
  position: relative;
  color: #333333;
}

.tintuc:hover {
  color: #06b5ad;
}

.website {
  cursor: pointer;
  width: 134px;
  margin-left: 16px;
  margin-right: 16px;
  position: relative;
  color: #333333;
}

.website:hover {
  color: #06b5ad;
}

.tuyendung {
  cursor: pointer;
  width: 89px;
  margin-left: 16px;
  margin-right: 16px;
  color: #333333;
}

.tuyendung:hover {
  color: #06b5ad;
}

.lienhe {
  cursor: pointer;
  width: 52px;
  margin-left: 16px;
  margin-right: 16px;
  color: #333333
}

.lienhe:hover {
  color: #06b5ad;
}

img {
  cursor: pointer;
  width: 20px;
  margin-left: 16px;
  margin-right: 16px;
  margin-bottom: -6px;
}

input {
  border: none;
  height: 20px;
  background-color: transparent;

}

input:focus {
  outline: none;
  /* Đây là làm mất viền khi nhấn vào input*/

}

div {
  margin-left: 16px;
  margin-right: 16px;

}

a {
  cursor: pointer;
  background-color: transparent;
}
</style>