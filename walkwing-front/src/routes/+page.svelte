
<script lang="ts">
    import { goto } from '$app/navigation'

        function goHome() {
            goto('/home');
        }
</script>
    
<div class="flex flex-row h-screen justify-center items-center">
    <div class="basis-6/12 card w-full h-1/2 bg-base-100 shadow-xl justify-center">
        
            <label class="form-control w-full flex-col items-center">

                <div class="text-xl">
                <h1>Please sign in to your account</h1>
                </div>

                <div class="py-2">
                    <input type="text" placeholder="Username" class="input input-bordered w-full max-w-xs" />
                </div>
                
                <div class="py-2">
                <input type="text" placeholder="Password" class="input input-bordered w-full max-w-xs" />
                </div>

                <div class="flex justify-center p-2">
                    <button on:click={goHome}  class="btn btn-primary w-full">Sign In</button>
                </div>

            </label>
        
    </div>
</div>


