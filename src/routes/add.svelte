<script>
import Tag from '../components/tag.svelte'
</script>


<div class="bg-[#BAFFF3] flex items-center justify-center h-screen">  
    <div class="flex gap-10 h-[90%] w-full justify-center items-center ">
        <div class="flex h-full w-[48%] bg-sky-50 ">
            Dropbox // Selected tags // Two entries 
        </div>
        <div class="w-[30%] h-full overflow-scroll" >
            <Tag></Tag>
            <Tag></Tag>
            
            <Tag></Tag>
            <Tag></Tag>
            <Tag></Tag>
        </div>
    </div>
</div>
