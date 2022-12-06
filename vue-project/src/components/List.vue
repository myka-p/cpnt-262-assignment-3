<script>
export default {
  data() {
  	return {
	    category: 'Rings',
    	items: [{ message: 'Gold Rings' }, { message: 'Silver Rings' }],
  	}
	}
}
</script>

<template>
  
	<li v-for="(item, index) in items" class="pt-5 list-none text-2xl">
  	{{ category }} >  {{ item.message }}
	</li>

</template>