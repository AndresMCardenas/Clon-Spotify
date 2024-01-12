<script lang="ts">
  const currenTime = new Date()
  const currenHours = currenTime.getHours()

  let greeting = ''

  if (currenHours < 12) {
    greeting = 'Buenos dias'
  } else if (currenHours < 18) {
    greeting = 'Buenas tardes'
  } else {
    greeting = 'Buenas noches'
  }
</script>

<h1 class="text-3xl font-bold">{greeting}</h1>
