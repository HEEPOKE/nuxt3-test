<template>
  <headerVue />
  <div class="container justify-content-center col-8">
    <div class="card">
      <div class="card-body">
        <NuxtLink to="/create">
          <button class="btn btn-primary col-auto mb-3 float-end">
            create
          </button>
        </NuxtLink>
        <table class="table table-dark table-striped-columns">
          <thead>
            <tr class="text-center">
              <th scope="col">#</th>
              <th scope="col">First</th>
              <th scope="col">Last</th>
              <th scope="col">Manage</th>
            </tr>
          </thead>
          <tbody>
            <tr class="text-center">
              <th scope="row">1</th>
              <td>Mark</td>
              <td>Otto</td>
              <td class="col-4">
                <button class="btn btn-warning mx-2">edit</button>
                <button class="btn btn-danger">delete</button>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>
<script>
import headerVue from "./header.vue";

export default {
  name: "tableVue",
  components: {
    headerVue,
  },
};
</script>
