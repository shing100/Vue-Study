<template>
    <div>
        <base-header type="gradient-success" class="pb-6 pb-8 pt-5 pt-md-8">

        </base-header>

        <div class="container-fluid mt--7">
            <div class="row">
                <div class="col">
                    <div class="card shadow">
                        <div class="card-header bg-transparent">
                            <h3 class="mb-1">Review</h3>
                        </div>
                        <div class="card-body">
                          <stats-card title="후기 제목"
                                sub-title="후기 내용 보기 리스트 후기 내용 보기 리스트 후기 내용 보기 리스트 후기 내용 보기 리스트"
                                class="mb-4 mb-xl-0 mt-3"
                          >
                            <template slot="footer">
                                <span class="text-nowrap">one hour</span>
                            </template>
                          </stats-card>
                        
                          <stats-card title="후기 제목2"
                                sub-title="후기 내용 보기 리스트 후기 내용 보기 리스트 후기 내용 보기 리스트 후기 내용 보기 리스트"
                                class="mb-4 mb-xl-0 mt-3"
                          >

                            <template slot="footer">
                                <span class="text-nowrap">Since last month</span>
                            </template>
                          </stats-card>

                          <stats-card title="후기 제목3"
                                sub-title="후기 내용 보기 리스트 후기 내용 보기 리스트 후기 내용 보기 리스트 후기 내용 보기 리스트"
                                class="mb-4 mb-xl-0 mt-3"
                          >

                            <template slot="footer">
                                <span class="text-nowrap">Since last month</span>
                            </template>
                          </stats-card>

                          <stats-card title="후기 제목4"
                                sub-title="후기 내용 보기 리스트 후기 내용 보기 리스트 후기 내용 보기 리스트 후기 내용 보기 리스트"
                                class="mb-4 mb-xl-0 mt-3"
                          >
                            <template slot="footer">
                                <span class="text-nowrap">Since last month</span>
                            </template>
                          </stats-card>

                          <stats-card title="후기 제목5"
                                sub-title="후기 내용 보기 리스트 후기 내용 보기 리스트 후기 내용 보기 리스트 후기 내용 보기 리스트"
                                class="mb-4 mb-xl-0 mt-3"
                          >
                            <template slot="footer">
                                <span class="text-nowrap">Since last month</span>
                            </template>
                          </stats-card>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>
<script>
  import Vue from 'vue'
  import VueClipboard from 'vue-clipboard2'
  import BTooltipDirective from 'bootstrap-vue/es/directives/tooltip'
  Vue.use(VueClipboard)

  export default {
    directives: {
      'b-tooltip': BTooltipDirective
    },
    methods: {
      onCopy() {
        this.$notify({
          type: 'success',
          title: 'Copied to clipboard'
        })
      }
    }
  };
</script>
<style></style>
