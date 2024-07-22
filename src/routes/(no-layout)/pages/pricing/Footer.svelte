<script>
	import {
		Footer,
		FooterCopyright,
		FooterLinkGroup,
		FooterLink,
		FooterBrand,
		FooterIcon
	} from 'flowbite-svelte';
</script>

<Footer footerType="socialmedia" class="mt-12">
	<div class="container mx-auto px-4 sm:py-12 md:px-0">
		<div class="md:flex md:justify-between">
			<div class="grid grid-cols-2 gap-8 sm:grid-cols-6 sm:gap-6">
				<div class="col-span-2 mb-6 md:mb-0">
					<FooterBrand
						href="https://aliasystems.com"
						src="/images/flowbite-svelte-icon-logo.svg"
						alt="Alia Systems Logo"
						name="Alia Systems"
					/>
					<p class="mt-4 max-w-lg text-gray-500 dark:text-gray-400">
						Alia Systems is a small AI consultancy which builds ethical systems with a focus on privacy and security.
					</p>
				</div>
				<div>
					<h2 class="mb-6 text-sm font-semibold uppercase text-gray-900 dark:text-white">
						Resources
					</h2>
					<FooterLinkGroup>
						<FooterLink liClass="mb-4" href="/">Alia Systems</FooterLink>
						<FooterLink liClass="mb-4" href="/">WeAllShare</FooterLink>
						<FooterLink liClass="mb-4" href="/">Documentation</FooterLink>
						<FooterLink liClass="mb-4" href="/">Journal</FooterLink>
						<FooterLink liClass="mb-4" href="/">Support</FooterLink>
					</FooterLinkGroup>
				</div>
				<div>
					<h2 class="mb-6 text-sm font-semibold uppercase text-gray-900 dark:text-white">
						Help and support
					</h2>
					<FooterLinkGroup>
						<FooterLink liClass="mb-4" href="/">GitHub Repository</FooterLink>
						<FooterLink liClass="mb-4" href="/">Alia Systems Data</FooterLink>
					</FooterLinkGroup>
				</div>
				<div>
					<h2 class="mb-6 text-sm font-semibold uppercase text-gray-900 dark:text-white">
						Follow us
					</h2>
					<FooterLinkGroup>
						<FooterLink liClass="mb-4" href="/">GitHub</FooterLink>
						<FooterLink liClass="mb-4" href="/">Twitter</FooterLink>
						<FooterLink liClass="mb-4" href="/">Facebook</FooterLink>
						<FooterLink liClass="mb-4" href="/">LinkedIn</FooterLink>
					</FooterLinkGroup>
				</div>
				<div>
					<h2 class="mb-6 text-sm font-semibold uppercase text-gray-900 dark:text-white">Legal</h2>
					<FooterLinkGroup>
						<FooterLink liClass="mb-4" href="/">Privacy Policy</FooterLink>
						<FooterLink liClass="mb-4" href="/">Terms & Conditions</FooterLink>
						<FooterLink liClass="mb-4" href="/">EULA</FooterLink>
					</FooterLinkGroup>
				</div>
			</div>
		</div>
		<hr class="my-6 border-gray-200 dark:border-gray-700 sm:mx-auto lg:my-8" />
		<div class="sm:flex sm:items-center sm:justify-center">
			<FooterCopyright href="/" by="Alia Systems™" />
		</div>
	</div>
</Footer>
