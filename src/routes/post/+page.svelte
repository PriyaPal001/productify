
<form>
	<div class="space-y-12">
		<div class="border-b border-white/10 pb-12">
			<h2 class="text-base font-semibold leading-7 text-white md:text-2xl">Create Post</h2>
			<p class="mt-1 text-sm leading-6 text-gray-400">
				This information will be displayed publicly so be careful what you share.
			</p>

			<div class="mt-10 grid grid-cols-1 gap-x-6 gap-y-8 sm:grid-cols-6">
				<div class="sm:col-span-4">
					<label for="username" class="block text-sm font-medium leading-6 text-white"
						>Username</label
					>
					<div class="mt-2">
						<div
							class="flex rounded-md bg-white/5 ring-1 ring-inset ring-white/10 focus-within:ring-2 focus-within:ring-inset focus-within:ring-indigo-500"
						>
							<span class="flex select-none items-center pl-3 text-gray-500 sm:text-sm"
								>workcation.com/</span
							>
							<input
								type="text"
								name="username"
								id="username"
								autocomplete="username"
								class="flex-1 border-0 bg-transparent py-1.5 pl-1 text-white focus:ring-0 sm:text-sm sm:leading-6"
								placeholder="janesmith"
							/>
						</div>
					</div>
				</div>

				<div class="col-span-full">
					<label for="about" class="block text-sm font-medium leading-6 text-white">About</label>
					<div class="mt-2">
						<textarea
							id="about"
							name="about"
							rows="3"
							class="block w-full rounded-md border-0 bg-white/5 py-1.5 text-white shadow-sm ring-1 ring-inset ring-white/10 focus:ring-2 focus:ring-inset focus:ring-indigo-500 sm:text-sm sm:leading-6"
						/>
					</div>
					<p class="mt-3 text-sm leading-6 text-gray-400">Write a few sentences about yourself.</p>
				</div>

				

				<div class="col-span-full">
					<label for="cover-photo" class="block text-sm font-medium leading-6 text-white"
						>Cover photo</label
					>
					<div
						class="mt-2 flex justify-center rounded-lg border border-dashed border-white/25 px-6 py-10"
					>
						<div class="text-center">
							<svg
								class="mx-auto h-12 w-12 text-gray-500"
								viewBox="0 0 24 24"
								fill="currentColor"
								aria-hidden="true"
							>
								<path
									fill-rule="evenodd"
									d="M1.5 6a2.25 2.25 0 012.25-2.25h16.5A2.25 2.25 0 0122.5 6v12a2.25 2.25 0 01-2.25 2.25H3.75A2.25 2.25 0 011.5 18V6zM3 16.06V18c0 .414.336.75.75.75h16.5A.75.75 0 0021 18v-1.94l-2.69-2.689a1.5 1.5 0 00-2.12 0l-.88.879.97.97a.75.75 0 11-1.06 1.06l-5.16-5.159a1.5 1.5 0 00-2.12 0L3 16.061zm10.125-7.81a1.125 1.125 0 112.25 0 1.125 1.125 0 01-2.25 0z"
									clip-rule="evenodd"
								/>
							</svg>
							<div class="mt-4 flex text-sm leading-6 text-gray-400">
								<label
									for="file-upload"
									class="relative cursor-pointer rounded-md bg-gray-900 font-semibold text-white focus-within:outline-none focus-within:ring-2 focus-within:ring-indigo-600 focus-within:ring-offset-2 focus-within:ring-offset-gray-900 hover:text-indigo-500"
								>
									<span>Upload a file</span>
									<input id="file-upload" name="file-upload" type="file" class="sr-only" />
								</label>
								<p class="pl-1">or drag and drop</p>
							</div>
							<p class="text-xs leading-5 text-gray-400">PNG, JPG, GIF up to 10MB</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>

	<div class="mt-6 flex items-center justify-end gap-x-6">
		<button type="button" class="text-sm font-semibold leading-6 text-white">Cancel</button>
		<button
			type="submit"
			class="rounded-md bg-indigo-500 px-3 py-2 text-sm font-semibold text-white shadow-sm hover:bg-indigo-400 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-500"
			>Save</button
		>
	</div>
</form>
