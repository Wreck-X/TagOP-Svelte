<script>
import {Link} from 'svelte-routing';

</script>

<div class="flex justify-center items-center bg-[#BAFFF3] h-screen">
   <div class="flex gap-4">
   <Link to="/add">
        <div class="flex justify-center items-center h-96 rounded-xl w-96 border-white border-[5px] transition-bg duration-300 hover:bg-blue-300 cursor-pointer bg-[#A1DDFF]">
            ADD
        </div>
   </Link>
    <Link to="/search">
        <div class="flex justify-content items-center h-96 rounded-xl w-96 border-white border-[5px] transition-bg duration-300 hover:bg-blue-300 cursor-pointer bg-[#A1DDFF]">
            SEARCH
        </div>
    </Link>
   </div>
</div>

