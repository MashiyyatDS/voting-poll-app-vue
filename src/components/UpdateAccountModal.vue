<template>
  <div class="modal fade" id="updateAccountModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <form @submit.prevent="submitAccount">
          <div class="modal-header">
            <h5 class="modal-title" id="exampleModalLabel">Update Account</h5>
            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
          </div>
          <div class="modal-body">
            <div class="mb-1">
              <small class="text-muted">Username: </small>
              <input type="text" class="form-control">
            </div>
            <div class="mb-1">
              <small class="text-muted">Email: </small>
              <input type="email" class="form-control">
            </div>
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
            <button type="submit" class="btn btn-primary">Save changes</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'UpdateAccountModal',
  methods: {
    
  }
}
</script>