<template>
     <div>
        <footer>
            <p>&copy; {{ currentYear }}@ThandoNaturals2024</p>
        </footer>
     </div>
  </template>

  <script>
    export default {
        data() {
            return{
                currentYear: new Date().getFullYear(),
            }
        }
    }
 </script>

<style>

</style>