<script>
    let collapsed = false;
</script>

<div class="flex flex-col items-center" >
    <div class="tag h-14 w-full mx-28 rounded-lg cursor-pointer" on:click={() => {collapsed = !collapsed}}></div>
    <div class={collapsed ? "extended w-full  top-1" :  "extend w-full  top-1"}></div>
</div>

<style>
.tag{
    background-color: #C5D0F9;
    transition: background-color 300ms;
}
.tag:hover{
    background-color: #0085cc;
}

.extend{
    height: 0;
    transition: height 300ms;
    background-color: #7c96f7;
}

.extended{
    height: 100px;
    background-color: #7c96f7;
    transition: height 300ms
}
</style>
