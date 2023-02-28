<script setup>
import { TheChessboard } from 'vue3-chessboard';
import { ref } from 'vue';
import 'vue3-chessboard/style.css';

const boardAPI = ref();
const boardConfig = {
  coordinates: false,
  autoCastle: false,
};
</script>

<template>
    <TheChessboard
        :board-config="boardConfig"
        @board-created="(api) => (boardAPI = api)"
    />
</template>



