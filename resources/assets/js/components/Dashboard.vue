<template>
    <div class="container">
        <div class="row justify-content-center">
          <div class="col-md-12">
            <div class="card">
              <div class="card-header">
                <ul class="nav nav-pills">
                  <li class="nav-item"><a class="nav-link active show" href="#add" data-toggle="tab">Adicionar Curso</a></li>
                  <li class="nav-item"><a class="nav-link" href="#config" data-toggle="tab">Cursos Adicionados</a></li>
                </ul>
              </div>
              <div class="card-body">
                <div class="tab-content">
                  <div class="tab-pane active show" id="add">
                    <label for="photo" class="col-sm-2 control-label">Profile Photo</label>
                    <div class="col-sm-12">
                        <input type="file" @change="updateProfile" name="photo" class="form-input">
                    </div>
                  </div>
                  <div class="tab-pane" id="config">
                    kkasskd
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        },
        methods:{

        }

    }
</script>
