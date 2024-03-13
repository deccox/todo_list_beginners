<template>
    <div id="board-container">
        <div class="board-header">
            <form>
                <input type="text" name="search" id="search" placeholder="search">
                <input type="submit" value="search">
            </form>
        </div>
        <div class="board-container-itens">
            <BoardItens/>
            <BoardItens/>
            <BoardItens/>
            <BoardItens/>
            <BoardItens/>
        </div>
    </div>
</template>


<script setup lang="ts">
import BoardItens from '../../src/components/BoardItensC.vue'
</script>


<style scoped > 



#board-container{
    margin-top: 20px;
    display: flex;
    flex-direction: column;
    gap: 10px;
    max-width: 700px;
    width: 100%;
    height: 100%;
    background-color: red;
    border-radius: 4px;
    box-shadow: 0 0 10px rgba(0,0,0,0.4);
}

.board-container-itens {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.board-header{
    width: 100%;
    height: 40px;
    background-color: blue;
}
</style>