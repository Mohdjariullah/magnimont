<script>
  import {
    Footer,
    FooterLinkGroup,
    FooterLink,
    FooterIcon,
    FooterCopyright,
  } from "flowbite-svelte";
  import {
    DiscordSolid,
    LinkedinSolid,
    GithubSolid,
    YoutubeSolid,
  } from "flowbite-svelte-icons";
</script>

<Footer footerType="sitemap">

  <div class="bg-black text-white p-8 rounded-lg shadow-lg">
    <div class="flex flex-col md:flex-row gap-8 justify-center">
      <!-- Image, Description, Copyright -->
      <div class="flex flex-col items-center md:items-start flex-1">
        <!-- Image -->
        <img
          src="https://images-ext-1.discordapp.net/external/Fck1ccubcCLfJ_sL7BuIG3Q6c5uU_MFZ3XbEAme0jBQ/%3Fsize%3D512/https/cdn.discordapp.com/icons/876113814314164256/0e0f35f8cd793beefafbdec39382f1db.png"
          alt="Company Image"
          class="w-32 h-32 mb-4 rounded-full border-2 border-amber-200"
        />

        <!-- Description -->
        <div class="text-center md:text-left">
          <p class="text-white text-lg font-bold mb-4">Innovating since binary age!</p>
        </div>

        <!-- Copyright -->
        <FooterCopyright
          spanClass="text-xs text-amber-200 sm:text-center"
          href="/"
          by="Magnimont™"
        />
      </div>

      <!-- Horizontal Sections -->
      <div class="flex flex-col md:flex-row gap-8 flex-1 justify-between">
        <!-- Magnimont -->
        <div class="flex flex-col space-y-2">
          <h2 class="text-amber-200 font-bold uppercase mb-2">Magnimont</h2> <!-- Bold subcategory title -->
          <FooterLinkGroup ulClass="space-y-2">
            <FooterLink href="/">About</FooterLink>
            <FooterLink href="https://forum.magnimont.com">Forum</FooterLink>
            <FooterLink href="https://host.magnimont.com">Hosting</FooterLink>
            <FooterLink href="/">Career</FooterLink>
          </FooterLinkGroup>
        </div>

        <!-- Socials -->
        <div class="flex flex-col space-y-2">
          <h2 class="text-amber-200 font-bold uppercase mb-2">Socials</h2> <!-- Bold subcategory title -->
          <FooterLinkGroup ulClass="space-y-2">
            <FooterLink href="https://discord.gg/magnimont-876113814314164256">Discord Server</FooterLink>
            <FooterLink href="https://www.linkedin.com/company/magnimont/">Linkedin</FooterLink>
            <FooterLink href="https://github.com/Magnimont">Github</FooterLink>
            <FooterLink href="https://www.youtube.com/@Magnimont/videos">Youtube</FooterLink>
          </FooterLinkGroup>
        </div>

        <!-- Legal -->
        <div class="flex flex-col space-y-2">
          <h2 class="text-amber-200 font-bold uppercase mb-2">Legal</h2> <!-- Bold subcategory title -->
          <FooterLinkGroup ulClass="space-y-2">
            <FooterLink href="/privacy-policy">Privacy Policy</FooterLink>
            <FooterLink href="/">Licensing</FooterLink>
            <FooterLink href="/terms-of-service">Terms & Conditions</FooterLink>
          </FooterLinkGroup>
        </div>

        <!-- Connect -->
        <div class="flex flex-col space-y-2">
          <h2 class="text-amber-200 font-bold uppercase mb-2">Connect</h2> <!-- Bold subcategory title -->
          <FooterLinkGroup ulClass="space-y-2">
            <FooterLink href="tel:+91 8076974315">+91 8076974315</FooterLink>
            <FooterLink href="mailto:hi@magnimont.com">hi@magnimont.com</FooterLink>
          </FooterLinkGroup>
        </div>
      </div>
<!-- =======
  <div
    class="grid grid-cols-2 gap-8 pt-12 px-6 md:grid-cols-4 place-content-center bg-black"
  >
    <div>
      <h2 class="mb-6 text-sm font-semibold text-amber-200 uppercase">
        Magnimont
      </h2>
      <FooterLinkGroup ulClass="text-gray-300 text-xs">
        <FooterLink liClass="mb-2" href="/">About</FooterLink>
        <FooterLink liClass="mb-2" href="https://forum.magnimont.com"
          >Forum</FooterLink
        >
        <FooterLink liClass="mb-2" href="https://host.magnimont.com"
          >Hosting</FooterLink
        >
        <FooterLink liClass="mb-2" href="/careers">Careers</FooterLink>
      </FooterLinkGroup>
    </div>
    <div>
      <h2 class="mb-6 text-sm font-semibold uppercase text-amber-200">
        Socials
      </h2>
      <FooterLinkGroup ulClass="text-gray-300 text-xs">
        <FooterLink
          liClass="mb-2"
          href="https://discord.gg/magnimont-876113814314164256"
          >Discord Server</FooterLink
        >
        <FooterLink
          liClass="mb-2"
          href="https://www.linkedin.com/company/magnimont/"
          >Linkedin</FooterLink
        >
        <FooterLink liClass="mb-2" href="https://github.com/Magnimont"
          >Github</FooterLink
        >
        <FooterLink
          liClass="mb-2"
          href="https://www.youtube.com/@Magnimont/videos">Youtube</FooterLink
        >
      </FooterLinkGroup>
    </div>
    <div>
      <h2 class="mb-6 text-sm font-semibold uppercase text-amber-200">Legal</h2>
      <FooterLinkGroup ulClass="text-gray-300 text-xs">
        <FooterLink liClass="mb-2" href="/privacy-policy"
          >Privacy Policy</FooterLink
        >
        <FooterLink liClass="mb-2" href="/">Licensing</FooterLink>
        <FooterLink liClass="mb-2" href="/terms-of-service"
          >Terms & Conditions</FooterLink
        >
      </FooterLinkGroup>
    </div>
    <div>
      <h2 class="mb-6 text-sm font-semibold uppercase text-amber-200">
        Connect
      </h2>
      <FooterLinkGroup ulClass="text-gray-300 text-xs">
        <FooterLink liClass="mb-4" href="tel:+91 8076974315"
          >+91 8076974315</FooterLink
        >
        <FooterLink liClass="mb-4" href="mailto:hi@magnimont.com"
          >hi@magnimont.com</FooterLink
        >
      </FooterLinkGroup>
    </div>
  </div>
  <div class="pb-5 px-8 bg-black md:flex md:items-center md:justify-between">
    <FooterCopyright
      spanClass="text-xs text-amber-200 sm:text-center"
      href="/"
      by="Magnimont™"
    />
    <div
      class="flex mt-4 space-x-6 rtl:space-x-reverse sm:justify-center md:mt-0"
    >
      <FooterIcon href="/" />
      <FooterIcon href="https://discord.gg/magnimont-876113814314164256">
        <DiscordSolid
          class="w-5 h-5 text-gray-500 dark:text-gray-500 hover:text-gray-900 dark:hover:text-white"
        />
      </FooterIcon>
      <FooterIcon href="https://www.linkedin.com/company/magnimont/">
        <LinkedinSolid
          class="w-5 h-5 text-gray-500 dark:text-gray-500 hover:text-gray-900 dark:hover:text-white"
        />
      </FooterIcon>
      <FooterIcon href="https://github.com/Magnimont">
        <GithubSolid
          class="w-5 h-5 text-gray-500 dark:text-gray-500 hover:text-gray-900 dark:hover:text-white"
        />
      </FooterIcon>
      <FooterIcon href="https://www.youtube.com/@Magnimont/videos">
        <YoutubeSolid
          class="w-5 h-5 text-gray-500 dark:text-gray-500 hover:text-gray-900 dark:hover:text-white"
        /></FooterIcon
      >

    </div>-->
  </div>
</Footer>
