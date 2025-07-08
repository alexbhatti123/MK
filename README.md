<html>
  <head>
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="" />
    <link
      rel="stylesheet"
      as="style"
      onload="this.rel='stylesheet'"
      href="https://fonts.googleapis.com/css2?display=swap&amp;family=Noto+Sans%3Awght%40400%3B500%3B700%3B900&amp;family=Plus+Jakarta+Sans%3Awght%40400%3B500%3B700%3B800"
    />

    <title>Stitch Design</title>
    <link rel="icon" type="image/x-icon" href="data:image/x-icon;base64," />

    <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  </head>
  <body>
    <div
      class="relative flex size-full min-h-screen flex-col bg-white group/design-root overflow-x-hidden"
      style='--select-button-svg: url(&apos;data:image/svg+xml,%3csvg xmlns=%27http://www.w3.org/2000/svg%27 width=%2724px%27 height=%2724px%27 fill=%27rgb(96,117,138)%27 viewBox=%270 0 256 256%27%3e%3cpath d=%27M181.66,170.34a8,8,0,0,1,0,11.32l-48,48a8,8,0,0,1-11.32,0l-48-48a8,8,0,0,1,11.32-11.32L128,212.69l42.34-42.35A8,8,0,0,1,181.66,170.34Zm-96-84.68L128,43.31l42.34,42.35a8,8,0,0,0,11.32-11.32l-48-48a8,8,0,0,0-11.32,0l-48,48A8,8,0,0,0,85.66,85.66Z%27%3e%3c/path%3e%3c/svg%3e&apos;); font-family: "Plus Jakarta Sans", "Noto Sans", sans-serif;'
    >
      <div class="layout-container flex h-full grow flex-col">
        <header class="flex items-center justify-between whitespace-nowrap border-b border-solid border-b-[#f0f2f5] px-10 py-3">
          <div class="flex items-center gap-4 text-[#111418]">
            <div class="size-4">
              <svg viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
                <g clip-path="url(#clip0_6_330)">
                  <path
                    fill-rule="evenodd"
                    clip-rule="evenodd"
                    d="M24 0.757355L47.2426 24L24 47.2426L0.757355 24L24 0.757355ZM21 35.7574V12.2426L9.24264 24L21 35.7574Z"
                    fill="currentColor"
                  ></path>
                </g>
                <defs>
                  <clipPath id="clip0_6_330"><rect width="48" height="48" fill="white"></rect></clipPath>
                </defs>
              </svg>
            </div>
            <h2 class="text-[#111418] text-lg font-bold leading-tight tracking-[-0.015em]">CivicConnect</h2>
          </div>
          <div class="flex flex-1 justify-end gap-8">
            <div class="flex items-center gap-9">
              <a class="text-[#111418] text-sm font-medium leading-normal" href="#">Home</a>
              <a class="text-[#111418] text-sm font-medium leading-normal" href="#">Create Post</a>
              <a class="text-[#111418] text-sm font-medium leading-normal" href="#">Browse Issues</a>
              <a class="text-[#111418] text-sm font-medium leading-normal" href="#">Profile</a>
              <a class="text-[#111418] text-sm font-medium leading-normal" href="#">About</a>
            </div>
            <div
              class="bg-center bg-no-repeat aspect-square bg-cover rounded-full size-10"
              style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuAouf9asAKg843d2PAmntODiUGP-9p4bLQu9nRp1c3zzZ7WypcnlysUtxpOq3RJpwRN7_pKTtySJmhR8nEZeX_EDWNhyWKgiSESUcuRank9c3dXJaxeaRVd9Ta3lsXTlmGTH_XloiQbFyONgLs5jNTkTikP74kkE0XEv2hQSebo286n3grFcd6D_foxqHvECIP7Y7isOHm7tlOsqxqeIw2rpryQMu0z95mPlAva3UHB9VXzwoRMs_RBIzLlKgs87PEusM6syUCofcU");'
            ></div>
          </div>
        </header>
        <div class="px-40 flex flex-1 justify-center py-5">
          <div class="layout-content-container flex flex-col max-w-[960px] flex-1">
            <h2 class="text-[#111418] tracking-light text-[28px] font-bold leading-tight px-4 text-center pb-3 pt-5">Report local issues in your community</h2>
            <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
              <label class="flex flex-col min-w-40 flex-1">
                <select
                  class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-lg text-[#111418] focus:outline-0 focus:ring-0 border border-[#dbe0e6] bg-white focus:border-[#dbe0e6] h-14 bg-[image:--select-button-svg] placeholder:text-[#60758a] p-[15px] text-base font-normal leading-normal"
                >
                  <option value="one">Select Location</option>
                  <option value="two">two</option>
                  <option value="three">three</option>
                </select>
              </label>
            </div>
            <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
              <label class="flex flex-col min-w-40 flex-1">
                <textarea
                  placeholder="Describe the issue"
                  class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-lg text-[#111418] focus:outline-0 focus:ring-0 border border-[#dbe0e6] bg-white focus:border-[#dbe0e6] min-h-36 placeholder:text-[#60758a] p-[15px] text-base font-normal leading-normal"
                ></textarea>
              </label>
            </div>
            <div class="flex px-4 py-3 justify-center">
              <button
                class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-lg h-10 px-4 bg-[#0c7ff2] text-white text-sm font-bold leading-normal tracking-[0.015em]"
              >
                <span class="truncate">Submit</span>
              </button>
            </div>
            <h2 class="text-[#111418] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5">Recent Issues</h2>
            <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
              <label class="flex flex-col min-w-40 flex-1">
                <select
                  class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-lg text-[#111418] focus:outline-0 focus:ring-0 border border-[#dbe0e6] bg-white focus:border-[#dbe0e6] h-14 bg-[image:--select-button-svg] placeholder:text-[#60758a] p-[15px] text-base font-normal leading-normal"
                >
                  <option value="one">Filter by Location</option>
                  <option value="two">two</option>
                  <option value="three">three</option>
                </select>
              </label>
            </div>
            <div class="flex gap-4 bg-white px-4 py-3 justify-between">
              <div class="flex items-start gap-4">
                <div
                  class="bg-center bg-no-repeat aspect-square bg-cover rounded-full h-[70px] w-fit"
                  style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuAktcAOCG4X6u1xAXj3hwKpl_6SK75Lz_SNr_IQWuAQSnKAHX9zCiu5WL-F0nf7hAzqRZkXZ5OniRAmbUgO9pZr9W6tLRAf9Mjt9rpgWdg8c_g1MfOhDAMcsPaoSUbMAx9xNYf7KTRWHAjfZxtP96PPX8tq8faZ4N7rJA00QdZjE7MWVfUR-V3Qx-dWMxird8Qknn18YppcZ8_SB7BjLrVCya0j9tb8YDBB8nQnlXSVZ1gdhyBPzz7CR4uQrtoY4y0g5TfCpkWaZZQ");'
                ></div>
                <div class="flex flex-1 flex-col justify-center">
                  <p class="text-[#111418] text-base font-medium leading-normal">Potholes on Main Street</p>
                  <p class="text-[#60758a] text-sm font-normal leading-normal">Location: Karachi</p>
                  <p class="text-[#60758a] text-sm font-normal leading-normal">Posted by Aisha Khan · 2 days ago</p>
                </div>
              </div>
              <div class="shrink-0"><p class="text-[#111418] text-base font-normal leading-normal">120 agrees · 30 disagrees</p></div>
            </div>
            <div class="flex gap-4 bg-white px-4 py-3 justify-between">
              <div class="flex items-start gap-4">
                <div
                  class="bg-center bg-no-repeat aspect-square bg-cover rounded-full h-[70px] w-fit"
                  style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuD5ypErkx5KI_CfwiHSHYTpltehQTMKPqrnVjUuKnsiJvRoQDshvdoIzzoFJmd3FR6exnyxrml3tH55XAeWMCwWIUKSKbq1eOdDX_CSrNMYG7PJybYFGeP802ndtlQmbWN4c2Z6t9kWh-2abS9G9a3ySSa8Txd5fi3b2_nJTNyeOVvUcjOw1yy3xzgA_KWNZ7P2WDGHIWiC-7UXRxGMQShDuUR0wRHnAyZ5pK1DMvZ4ldgWzoS8rkN5AHBu0qMpmb_mDF70t6DNOoc");'
                ></div>
                <div class="flex flex-1 flex-col justify-center">
                  <p class="text-[#111418] text-base font-medium leading-normal">Garbage piling up near the market</p>
                  <p class="text-[#60758a] text-sm font-normal leading-normal">Location: Lahore</p>
                  <p class="text-[#60758a] text-sm font-normal leading-normal">Posted by Omar Farooq · 3 days ago</p>
                </div>
              </div>
              <div class="shrink-0"><p class="text-[#111418] text-base font-normal leading-normal">150 agrees · 20 disagrees</p></div>
            </div>
            <div class="flex gap-4 bg-white px-4 py-3 justify-between">
              <div class="flex items-start gap-4">
                <div
                  class="bg-center bg-no-repeat aspect-square bg-cover rounded-full h-[70px] w-fit"
                  style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCAudhgxjUrNI4_6sOUWvbqwWTtlYfGfn3W1TC-kYRJaLzfRL5Tu5ijtRvJ1BYD9OMo-JE4dfJ2FcM9UPgv_ZkXi60-rFSrTnydmIut-LCIcNniuutbJpq5EGjdkRYYhQQu-_soSAOzCB-J_AIvO6UAGtPnoBlfuNTFDKQGyet35h4yB8YPYB7TWsx7LpEubgq0VhYOz77V1KNmueFCE0KyL7SA_kG6ikbQlQRPIfqXrpI7KbQOGIg0BkGKfc6H0svxM7YGvshcrwk");'
                ></div>
                <div class="flex flex-1 flex-col justify-center">
                  <p class="text-[#111418] text-base font-medium leading-normal">Water shortage in Sector G-6</p>
                  <p class="text-[#60758a] text-sm font-normal leading-normal">Location: Islamabad</p>
                  <p class="text-[#60758a] text-sm font-normal leading-normal">Posted by Fatima Ali · 4 days ago</p>
                </div>
              </div>
              <div class="shrink-0"><p class="text-[#111418] text-base font-normal leading-normal">180 agrees · 10 disagrees</p></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
