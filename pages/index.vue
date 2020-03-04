<template>
<div class=""> 
	<table class="table borderd">
		<thead>
			<th>Taes</th>
		</thead>
		<tbody>
			<tr>
				<td>123213</td>
			</tr>
		</tbody>
	</table>
</div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
router: {
  routes: [
    {
      name: 'index',
      path: '/',
      component: 'pages/index.vue'
    },
    {
      name: 'user',
      path: '/user',
      component: 'pages/user/index.vue'
    },
    {
      name: 'user-one',
      path: '/user/one',
      component: 'pages/user/one.vue'
    }
  ]
}
</script>