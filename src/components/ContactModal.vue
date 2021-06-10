<template>
  <div class="modal" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="exampleModalLabel">
            Modal title
          </h5>
          <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
          </button>
        </div>
        <div class="modal-body">
          <form @submit.prevent="createVault" v-if="state.account.id === state.activeProfile.id">
            <div class="form-group">
              <label for="title">Email</label>
              <input type="text"
                     class="form-control"
                     id="email"
                     aria-describedby="title"
                     placeholder="Email"
              >
            </div>
            <div class="form-group">
              <label for="comment">Company</label>
              <input type="text"
                     class="form-control"
                     id="companyName"
                     aria-describedby="Company Name"
                     placeholder="Company Name"
              >
            </div>
            <div class="form-group">
              <label for="comment">Comments</label>
              <input type="textarea"
                     class="form-control"
                     columns="18"
                     rows="10"
                     id="comment"
                     aria-describedby="comment"
                     placeholder=""
              >
            </div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-dismiss="modal">
            Close
          </button>
          <button type="button" class="btn btn-primary">
            Save changes
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {

}
</script>
<style>

</style>
