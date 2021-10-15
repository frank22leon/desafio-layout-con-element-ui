.<template>
  <div>
    <el-menu
      :default-active="activeIndex2"
      class="el-menu-demo"
      mode="horizontal"
      @select="handleSelect"
      background-color="#545c64"
      text-color="#fff"
      active-text-color="#ffd04b"
    >
      
        <el-menu-item index="1">
          <router-link to="/home">INICIO</router-link>
          </el-menu-item>
      
      <el-menu-item index="2">BUSCAR</el-menu-item>
      <el-menu-item index="3">ACERCA DE</el-menu-item>
    </el-menu>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
