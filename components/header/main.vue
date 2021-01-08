<template>
  <div>
    <FundoMain />
    <div class="header-content">
      <span class="text-content">
        Olá você que está aqui na<br />
        minha pagina aqui quem fala <br />
        é o Jeff sou desenvolvedor nerd,<br />
        e fitness as vezes (esse ano vai),<br />
        esse espaço é para que eu possa<br />
        compartilhar tudo que eu curto e faço
      </span>
      <img src="@/assets/avatar.svg" />
    </div>
  </div>
</template>
<style scoped>
.header-content {
  height: 650px;
  display: flex;
  justify-content: center;
  align-items: flex-end;
}
.text-content {
  font-size: 24px;
  font-weight: bold;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  top: -300px;
  margin-right: 20px;
}
</style>

<script>
import FundoMain from './fundoMain.vue'

export default {
  components: {
    FundoMain,
  },
}
</script>
