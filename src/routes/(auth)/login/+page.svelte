<script>
	import EligibilityAgreement from '$lib/components/application/EligibilityAgreement.svelte';
</script>

<div class="flex-1 flex-col h-full rounded-inherit flex items-center justify-center">
	<div class="p-5 flex gap-2 cursor-pointer items-center w-full">
		<img src="launchlab_logo.png" alt="citeams_logo" class="w-8" />
		<a href="/" class="cursor-pointer font-black normal-case text-2xl">LaunchLab</a>
	</div>
	<img src="startup.png" alt="" class="flex-1 w-4/5 scale-x-[-1]" />
</div>
<div class="flex-1 flex flex-col gap-5 items-center justify-between h-full">
	<div class="flex-1 flex flex-col w-full p-10 justify-center">
		<h1 class="text-2xl font-semibold mb-5">Login</h1>
		<div class="form-control w-3/4">
			<label class="label" for="">
				<span class="label-text">Email</span>
			</label>
			<input type="text" placeholder="email" class="input input-bordered" />
		</div>
		<div class="form-control w-3/4">
			<label class="label" for="">
				<span class="label-text">Password</span>
			</label>
			<input type="text" placeholder="password" class="input input-bordered" />
		</div>
            <button class="btn mt-8 w-40 btn-primary border-none normal-case text-white bg-flutter-blue shadow-lg shadow-flutter-blue/50">
                Login
            </button>
	</div>
</div>
