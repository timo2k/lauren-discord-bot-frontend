<div class="flex min-h-full flex-col justify-center py-12 sm:px-6 lg:px-8">
	<div class="sm:mx-auto sm:w-full sm:max-w-md">
		<h2 class="mt-6 text-center text-3xl font-bold tracking-tight text-gray-900">
			Logge dich hier ein
		</h2>
		<p class="mt-2 text-center text-sm text-gray-600">Verpiss dich wenn du keinen Account hast</p>
	</div>

	<div class="mt-8 sm:mx-auto sm:w-full sm:max-w-md">
		<div class="bg-white px-4 py-8 shadow sm:rounded-lg sm:px:10">
			<form class="space-y-6">
				<!-- Form Field Start -->
				<div>
					<label for="" class="block text-sm font-medium leading-6 text-gray-900"
						>E-Mail Adresse</label
					>
					<div class="mt-2">
						<input
							placeholder="fuckyou@deine-mutter.gay"
							type="email"
							required
							class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-purple-600 sm:text-sm sm:leading-6"
						/>
					</div>
				</div>
				<!-- Form Field End -->

				<!-- Form Field Start -->
				<div>
					<label for="" class="block text-sm font-medium leading-6 text-gray-900">Passwort</label>
					<div class="mt-2">
						<input
							required
							autocomplete="current-password"
							name="password"
							type="password"
							class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-purple-600 sm:text-sm sm:leading-6"
						/>
					</div>
				</div>
				<!-- Form Field End -->

				<div>
					<button
						type="submit"
						class="flex w-full justify-center rounded-md bg-purple-600 px-3 py-2 text-sm font-semibold text-white shadow-sm hover:bg-purple-500 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-purple-600"
						>Einloggen</button
					>
				</div>
			</form>
		</div>
	</div>
</div>

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.gray.100);
	}
</style>
