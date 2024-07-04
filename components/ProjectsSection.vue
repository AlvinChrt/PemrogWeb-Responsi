<template>
  <section class="projects" id="projects">
    <h2>My Project</h2>
    <hr style="width: 30%;">
    <section class="projek">
    <div class="card" style="width: 18rem;">
  <div class="card-body">
    <h5 class="card-title">Project Struktur Data</h5>
    <p class="card-text">Menjadi anggota dan merancang final project Struktur Data, yaitu membuat program game sederhana dengan C++</p>
  </div>
</div>

<div class="card" style="width: 18rem;">
  <div class="card-body">
    <h5 class="card-title">Project Pemrograman Lanjut</h5>
    <p class="card-text">Menjadi anggota tim final project pemrograman lanjut, yaitu program Cashier</p>

  </div>
</div>
</section>

  </section>
</template>

<script>
export default {
  name: 'ProjectsSection'
}
</script>

<style scoped>
.projects {
  text-align: center;
  margin-top: 20px;
  padding: 20px 0px 20px 0px;
  background: #3572EF;
  color: white;
  margin: 17px;
  border-radius: 3px;
}

.card{
  background-color: #050C9C;
  transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
}

.card:hover{
  transform: translateY(-10px);
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.projek{
display: flex;
align-items: center;
justify-content: center;
gap: 5px;
}

</style>