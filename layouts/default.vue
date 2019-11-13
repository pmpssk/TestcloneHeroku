<template>
  <v-app >
    <v-toolbar  flat app color="#6bb83c">
      <v-spacer></v-spacer>
      <v-toolbar-items >
        <v-btn class="white--text" depressed text color="#6bb83c">เข้าสู่ระบบ</v-btn>
        <v-btn class="white--text" depressed text color="#6bb83c">สมัครสมาชิก</v-btn>
      </v-toolbar-items>
    </v-toolbar>
    <v-content>
      <v-card class="d-flex pa-2" outlined tile color="#6bb83c">

      </v-card>
    </v-content>

    <v-content>

      <v-container>
        <nuxt />
      </v-container>
    </v-content>
  </v-app>
</template>

<script>


export default {
  data() {
    return{

    }
  },
  components:{

  }
}
</script>
