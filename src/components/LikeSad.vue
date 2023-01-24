<script setup>
const like = ref(50);
const sad = ref(100);

function likeClick(){
  like.value++;
}
function sadClick(){
  sad.value++;
}
</script>

<template>
    <div>
    <button @click="likeClick()"> ปุม Like   {{ Like }}</button>
    <button @click="sadClick()"> ปุม Sad   {{ Sad }}</button>
    </div>
</template>