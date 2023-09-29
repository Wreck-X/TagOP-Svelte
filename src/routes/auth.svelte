<script>
import {Link} from 'svelte-routing';

</script>
<div class="flex justify-center items-center bg-[#BAFFF3] h-screen">
    <div class="flex flex-col bg-[#A1DDFF] border-[5px] border-white rounded-xl h-[25rem] w-[28rem]">
        <div class="flex p-2 items-center justify-center basis-2/6 text-white text-[3rem]">
            <p>TagOP</p>
        </div>
        <div class="mx-10 flex flex-col text-white font-semibold text-xl gap-4">
            <div class="flex flex-col gap-2">
                <label for="username">Username:</label>
                <input class="rounded-xl h-10 text-black p-2" name="username">
            </div>
            <div class="flex flex-col gap-2">
                <label for="password">Password:</label>
                <input class="rounded-xl h-10 text-black p-2" type="password" name="password">
            </div>
        </div>
       <div class="flex h-full w-full  justify-center items-center">
            <Link to="/options">
                <div class="rounded-full font-bold text-white text-xl transition-bg duration-200 cursor-pointer hover:bg-blue-300 bg-blue-400 h-14 w-44 flex items-center justify-center">
                    Login
                </div>
            </Link>
       </div> 
    </div>
</div>
