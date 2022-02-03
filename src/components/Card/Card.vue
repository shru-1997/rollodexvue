<template>
<div className='card-container'>
<img
alt='monster'
src='https://robohash.org/${id}?set=set2&size=180x180'
/>
<h2> {name} </h2>
<p> {email} </p>
</div>
</template>
<script>
export default {
    name: 'card'    
}
</script>

<style >
.card-container{
  display: flex;
  flex-direction: column;
  background-color: #95dada;
  border: 1px solid grey;
  border-radius: 5px;
  padding: 25px;
  cursor: pointer;
  -moz-osx-font-smoothing: grayscale;
  backface-visibility: hidden;
  transform: translateZ(0);
  transition: transform 0.25s ease-out;
}
</style>