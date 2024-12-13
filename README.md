<html>
  <head>
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="" />
    <link
      rel="stylesheet"
      as="style"
      onload="this.rel='stylesheet'"
      href="https://fonts.googleapis.com/css2?display=swap&amp;family=Noto+Sans:wght@400;500;700;900&amp;family=Space+Grotesk:wght@400;500;700"
    />

    <title>Munchies ZA Landing Page</title>
    <link rel="icon" type="image/x-icon" href="data:image/x-icon;base64," />

    <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  </head>
  <body>
    <div
      class="relative flex size-full min-h-screen flex-col bg-[#F9FAFA] justify-between group/design-root overflow-x-hidden"
      style='font-family: "Space Grotesk", "Noto Sans", sans-serif;'
    >
      <div>
        <div class="flex items-center bg-[#F9FAFA] p-4 pb-2 justify-between">
          <h2 class="text-[#1C1D22] text-lg font-bold leading-tight tracking-[-0.015em] flex-1 text-center pl-12">Munchies</h2>
          <div class="flex w-12 items-center justify-end">
            <button
              class="flex max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-12 bg-transparent text-[#1C1D22] gap-2 text-base font-bold leading-normal tracking-[0.015em] min-w-0 p-0"
            >
              <div class="text-[#1C1D22]" data-icon="MapPin" data-size="24px" data-weight="regular">
                <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                  <path
                    d="M128,64a40,40,0,1,0,40,40A40,40,0,0,0,128,64Zm0,64a24,24,0,1,1,24-24A24,24,0,0,1,128,128Zm0-112a88.1,88.1,0,0,0-88,88c0,31.4,14.51,64.68,42,96.25a254.19,254.19,0,0,0,41.45,38.3,8,8,0,0,0,9.18,0A254.19,254.19,0,0,0,174,200.25c27.45-31.57,42-64.85,42-96.25A88.1,88.1,0,0,0,128,16Zm0,206c-16.53-13-72-60.75-72-118a72,72,0,0,1,144,0C200,161.23,144.53,209,128,222Z"
                  ></path>
                </svg>
              </div>
            </button>
          </div>
        </div>
        <div class="px-4 py-3">
          <label class="flex flex-col min-w-40 h-12 w-full">
            <div class="flex w-full flex-1 items-stretch rounded-xl h-full">
              <div
                class="text-[#3C3F4A] flex border-none bg-[#EEEFF2] items-center justify-center pl-4 rounded-l-xl border-r-0"
                data-icon="MagnifyingGlass"
                data-size="24px"
                data-weight="regular"
              >
                <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                  <path d="M229.66,218.34l-50.07-50.06a88.11,88.11,0,1,0-11.31,11.31l50.06,50.07a8,8,0,0,0,11.32-11.32ZM40,112a72,72,0,1,1,72,72A72.08,72.08,0,0,1,40,112Z"></path>
                </svg>
              </div>
              <input
                placeholder="Search for food,locations"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#1C1D22] focus:outline-0 focus:ring-0 border-none bg-[#EEEFF2] focus:border-none h-full placeholder:text-[#3C3F4A] px-4 rounded-l-none border-l-0 pl-2 text-base font-normal leading-normal"
                value=""
              />
            </div>
          </label>
        </div>
        <div class="flex gap-3 p-3 overflow-x-hidden">
          <div class="flex h-8 shrink-0 items-center justify-center gap-x-2 rounded-xl bg-[#EEEFF2] pl-4 pr-4">
            <p class="text-[#1C1D22] text-sm font-medium leading-normal">Bunny Chow</p>
          </div>
          <div class="flex h-8 shrink-0 items-center justify-center gap-x-2 rounded-xl bg-[#EEEFF2] pl-4 pr-4">
            <p class="text-[#1C1D22] text-sm font-medium leading-normal">Rock Shandies</p>
          </div>
          <div class="flex h-8 shrink-0 items-center justify-center gap-x-2 rounded-xl bg-[#EEEFF2] pl-4 pr-4">
            <p class="text-[#1C1D22] text-sm font-medium leading-normal">Wors</p>
          </div>
          <div class="flex h-8 shrink-0 items-center justify-center gap-x-2 rounded-xl bg-[#EEEFF2] pl-4 pr-4">
            <p class="text-[#1C1D22] text-sm font-medium leading-normal">Tacos</p>
          </div>
          <div class="flex h-8 shrink-0 items-center justify-center gap-x-2 rounded-xl bg-[#EEEFF2] pl-4 pr-4">
            <p class="text-[#1C1D22] text-sm font-medium leading-normal">Indian</p>
          </div>
          <div class="flex h-8 shrink-0 items-center justify-center gap-x-2 rounded-xl bg-[#EEEFF2] pl-4 pr-4">
            <p class="text-[#1C1D22] text-sm font-medium leading-normal">Sushi</p>
          </div>
        </div>
        <div class="p-4 @container">
          <div class="flex flex-col items-stretch justify-start rounded-xl @xl:flex-row @xl:items-start">
            <div
              class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl"
              style='background-image: url("https://i.postimg.cc/PxB9bSrL/Spaghetti-Bolognese-tall-FS-0204-531x720.webp");'
            ></div>
            <div class="flex w-full min-w-72 grow flex-col items-stretch justify-center gap-1 py-4 @xl:px-4">
              <p class="text-[#1C1D22] text-lg font-bold leading-tight tracking-[-0.015em]">Theo's Spagh Bol</p>
              <div class="flex items-end gap-3 justify-between"><p class="text-[#3C3F4A] text-base font-normal leading-normal">LoneHill · 2.25 kilometers away</p></div>
            </div>
          </div>
        </div>
        <div class="p-4 @container">
          <div class="flex flex-col items-stretch justify-start rounded-xl @xl:flex-row @xl:items-start">
            <div
              class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl"
              style='background-image: url("https://i.postimg.cc/TPZvQdtY/Whipped-Shortbread-EXPS-HCBZ24-2523-MD-P2-06-04-1b.webp");'
            ></div>
            <div class="flex w-full min-w-72 grow flex-col items-stretch justify-center gap-1 py-4 @xl:px-4">
              <p class="text-[#1C1D22] text-lg font-bold leading-tight tracking-[-0.015em]">Mrs. Ndlovu's' Shortbread Cookies</p>
              <div class="flex items-end gap-3 justify-between"><p class="text-[#3C3F4A] text-base font-normal leading-normal">Paulshof · 3.52 kilometers away</p></div>
            </div>
          </div>
        </div>
        <div class="p-4 @container">
          <div class="flex flex-col items-stretch justify-start rounded-xl @xl:flex-row @xl:items-start">
            <div
              class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl"
              style='background-image: url("https://i.postimg.cc/KYV3NTXk/oven-baked-baby-back-ribs-beauty-332-preview-34579f7f15ed4548ae3bb5b2048aab60.jpg");'
            ></div>
            <div class="flex w-full min-w-72 grow flex-col items-stretch justify-center gap-1 py-4 @xl:px-4">
              <p class="text-[#1C1D22] text-lg font-bold leading-tight tracking-[-0.015em]">Patrick's Ribs</p>
              <div class="flex items-end gap-3 justify-between"><p class="text-[#3C3F4A] text-base font-normal leading-normal"> Paulshof · 5.14 kilometers away</p></div>
            </div>
          </div>
        </div>
        <div class="p-4 @container">
          <div class="flex flex-col items-stretch justify-start rounded-xl @xl:flex-row @xl:items-start">
            <div
              class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl"
              style='background-image: url("https://i.postimg.cc/BZ5ydch0/potjiekos-500x.jpg");'
            ></div>
            <div class="flex w-full min-w-72 grow flex-col items-stretch justify-center gap-1 py-4 @xl:px-4">
              <p class="text-[#1C1D22] text-lg font-bold leading-tight tracking-[-0.015em]">Zakhele's Potjie </p>
              <div class="flex items-end gap-3 justify-between"><p class="text-[#3C3F4A] text-base font-normal leading-normal">Dunkeld· 7.24 kilometers away</p></div>
            </div>
          </div>
        </div>
        <div class="p-4 @container">
          <div class="flex flex-col items-stretch justify-start rounded-xl @xl:flex-row @xl:items-start">
            <div
              class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl"
              style='background-image: url("https://i.postimg.cc/j5t2v4gj/2021-02-9-Bobote-0101.jpg");'
            ></div>
            <div class="flex w-full min-w-72 grow flex-col items-stretch justify-center gap-1 py-4 @xl:px-4">
              <p class="text-[#1C1D22] text-lg font-bold leading-tight tracking-[-0.015em]">Fatima's Bobotie</p>
              <div class="flex items-end gap-3 justify-between"><p class="text-[#3C3F4A] text-base font-normal leading-normal">Bryanston· 8.05 kilometers away</p></div>
            </div>
          </div>
        </div>
      </div>
      <div>
        <div class="flex gap-2 border-t border-[#EEEFF2] bg-[#FFFFFF] px-4 pb-3 pt-2">
          <a class="just flex flex-1 flex-col items-center justify-end gap-1 rounded-full text-[#1C1D22]" href="#">
            <div class="text-[#1C1D22] flex h-8 items-center justify-center" data-icon="House" data-size="24px" data-weight="fill">
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path
                  d="M224,115.55V208a16,16,0,0,1-16,16H168a16,16,0,0,1-16-16V168a8,8,0,0,0-8-8H112a8,8,0,0,0-8,8v40a16,16,0,0,1-16,16H48a16,16,0,0,1-16-16V115.55a16,16,0,0,1,5.17-11.78l80-75.48.11-.11a16,16,0,0,1,21.53,0,1.14,1.14,0,0,0,.11.11l80,75.48A16,16,0,0,1,224,115.55Z"
                ></path>
              </svg>
            </div>
            <p class="text-[#1C1D22] text-xs font-medium leading-normal tracking-[0.015em]">Home</p>
          </a>
          <a class="just flex flex-1 flex-col items-center justify-end gap-1 text-[#3C3F4A]" href="#">
            <div class="text-[#3C3F4A] flex h-8 items-center justify-center" data-icon="MagnifyingGlass" data-size="24px" data-weight="regular">
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path d="M229.66,218.34l-50.07-50.06a88.11,88.11,0,1,0-11.31,11.31l50.06,50.07a8,8,0,0,0,11.32-11.32ZM40,112a72,72,0,1,1,72,72A72.08,72.08,0,0,1,40,112Z"></path>
              </svg>
            </div>
            <p class="text-[#3C3F4A] text-xs font-medium leading-normal tracking-[0.015em]">Find</p>
          </a>
          <a class="just flex flex-1 flex-col items-center justify-end gap-1 text-[#3C3F4A]" href="#">
            <div class="text-[#3C3F4A] flex h-8 items-center justify-center" data-icon="ShoppingBag" data-size="24px" data-weight="regular">
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path
                  d="M216,40H40A16,16,0,0,0,24,56V200a16,16,0,0,0,16,16H216a16,16,0,0,0,16-16V56A16,16,0,0,0,216,40Zm0,160H40V56H216V200ZM176,88a48,48,0,0,1-96,0,8,8,0,0,1,16,0,32,32,0,0,0,64,0,8,8,0,0,1,16,0Z"
                ></path>
              </svg>
            </div>
            <p class="text-[#3C3F4A] text-xs font-medium leading-normal tracking-[0.015em]">Orders</p>
          </a>
          <a class="just flex flex-1 flex-col items-center justify-end gap-1 text-[#3C3F4A]" href="#">
            <div class="text-[#3C3F4A] flex h-8 items-center justify-center" data-icon="Receipt" data-size="24px" data-weight="regular">
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path
                  d="M72,104a8,8,0,0,1,8-8h96a8,8,0,0,1,0,16H80A8,8,0,0,1,72,104Zm8,40h96a8,8,0,0,0,0-16H80a8,8,0,0,0,0,16ZM232,56V208a8,8,0,0,1-11.58,7.15L192,200.94l-28.42,14.21a8,8,0,0,1-7.16,0L128,200.94,99.58,215.15a8,8,0,0,1-7.16,0L64,200.94,35.58,215.15A8,8,0,0,1,24,208V56A16,16,0,0,1,40,40H216A16,16,0,0,1,232,56Zm-16,0H40V195.06l20.42-10.22a8,8,0,0,1,7.16,0L96,199.06l28.42-14.22a8,8,0,0,1,7.16,0L160,199.06l28.42-14.22a8,8,0,0,1,7.16,0L216,195.06Z"
                ></path>
              </svg>
            </div>
            <p class="text-[#3C3F4A] text-xs font-medium leading-normal tracking-[0.015em]">Receipts</p>
          </a>
          <a class="just flex flex-1 flex-col items-center justify-end gap-1 text-[#3C3F4A]" href="#">
            <div class="text-[#3C3F4A] flex h-8 items-center justify-center" data-icon="UserCircle" data-size="24px" data-weight="regular">
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path
                  d="M128,24A104,104,0,1,0,232,128,104.11,104.11,0,0,0,128,24ZM74.08,197.5a64,64,0,0,1,107.84,0,87.83,87.83,0,0,1-107.84,0ZM96,120a32,32,0,1,1,32,32A32,32,0,0,1,96,120Zm97.76,66.41a79.66,79.66,0,0,0-36.06-28.75,48,48,0,1,0-59.4,0,79.66,79.66,0,0,0-36.06,28.75,88,88,0,1,1,131.52,0Z"
                ></path>
              </svg>
            </div>
            <p class="text-[#3C3F4A] text-xs font-medium leading-normal tracking-[0.015em]">Account</p>
          </a>
        </div>
        <div class="h-5 bg-[#FFFFFF]"></div>
      </div>
    </div>
  </body>
<body>
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="" />
    <link
      rel="stylesheet"
      as="style"
      onload="this.rel='stylesheet'"
      href="https://fonts.googleapis.com/css2?display=swap&amp;family=Noto+Sans%3Awght%40400%3B500%3B700%3B900&amp;family=Public+Sans%3Awght%40400%3B500%3B700%3B900"
    />

    <title>Contact Design</title>
    <link rel="icon" type="image/x-icon" href="data:image/x-icon;base64," />

    <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  </head>
  <body>
    <div
      class="relative flex size-full min-h-screen flex-col bg-slate-50 justify-between group/design-root overflow-x-hidden"
      style='font-family: "Public Sans", "Noto Sans", sans-serif;'
    >
      <div>
        <div class="flex items-center bg-slate-50 p-4 pb-2 justify-between">
          <h2 class="text-[#0e141b] text-lg font-bold leading-tight tracking-[-0.015em] flex-1 text-center pl-12">Contact</h2>
          <div class="flex w-12 items-center justify-end">
            <button
              class="flex max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-12 bg-transparent text-[#0e141b] gap-2 text-base font-bold leading-normal tracking-[0.015em] min-w-0 p-0"
            >
              <div class="text-[#0e141b]" data-icon="ArrowLeft" data-size="24px" data-weight="regular">
                <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                  <path
                    d="M224,128a8,8,0,0,1-8,8H59.31l58.35,58.34a8,8,0,0,1-11.32,11.32l-72-72a8,8,0,0,1,0-11.32l72-72a8,8,0,0,1,11.32,11.32L59.31,120H216A8,8,0,0,1,224,128Z"
                  ></path>
                </svg>
              </div>
            </button>
          </div>
        </div>
        <div class="flex gap-4 bg-slate-50 px-4 py-3">
          <div class="text-[#0e141b] flex items-center justify-center rounded-lg bg-[#e7edf3] shrink-0 size-12" data-icon="MapPin" data-size="24px" data-weight="regular">
            <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
              <path
                d="M128,64a40,40,0,1,0,40,40A40,40,0,0,0,128,64Zm0,64a24,24,0,1,1,24-24A24,24,0,0,1,128,128Zm0-112a88.1,88.1,0,0,0-88,88c0,31.4,14.51,64.68,42,96.25a254.19,254.19,0,0,0,41.45,38.3,8,8,0,0,0,9.18,0A254.19,254.19,0,0,0,174,200.25c27.45-31.57,42-64.85,42-96.25A88.1,88.1,0,0,0,128,16Zm0,206c-16.53-13-72-60.75-72-118a72,72,0,0,1,144,0C200,161.23,144.53,209,128,222Z"
              ></path>
            </svg>
          </div>
          <div class="flex flex-1 flex-col justify-center">
            <p class="text-[#0e141b] text-base font-medium leading-normal">Clayville, Olifantsfontein</p>
            <p class="text-[#4e7397] text-sm font-normal leading-normal">Johannesburg, SA  2196</p>
            <p class="text-[#4e7397] text-sm font-normal leading-normal">Office 1666</p>
          </div>
        </div>
        <div class="flex items-center gap-4 bg-slate-50 px-4 min-h-14 justify-between">
          <p class="text-[#0e141b] text-base font-normal leading-normal flex-1 truncate">(+27)  069 22 99 072 </p>
          <div class="shrink-0">
            <div class="text-[#0e141b] flex size-7 items-center justify-center" data-icon="Phone" data-size="24px" data-weight="regular">
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path
                  d="M222.37,158.46l-47.11-21.11-.13-.06a16,16,0,0,0-15.17,1.4,8.12,8.12,0,0,0-.75.56L134.87,160c-15.42-7.49-31.34-23.29-38.83-38.51l20.78-24.71c.2-.25.39-.5.57-.77a16,16,0,0,0,1.32-15.06l0-.12L97.54,33.64a16,16,0,0,0-16.62-9.52A56.26,56.26,0,0,0,32,80c0,79.4,64.6,144,144,144a56.26,56.26,0,0,0,55.88-48.92A16,16,0,0,0,222.37,158.46ZM176,208A128.14,128.14,0,0,1,48,80,40.2,40.2,0,0,1,82.87,40a.61.61,0,0,0,0,.12l21,47L83.2,111.86a6.13,6.13,0,0,0-.57.77,16,16,0,0,0-1,15.7c9.06,18.53,27.73,37.06,46.46,46.11a16,16,0,0,0,15.75-1.14,8.44,8.44,0,0,0,.74-.56L168.89,152l47,21.05h0s.08,0,.11,0A40.21,40.21,0,0,1,176,208Z"
                ></path>
              </svg>
            </div>
          </div>
        </div>
        <div class="flex items-center gap-4 bg-slate-50 px-4 min-h-14 justify-between">
          <p class="text-[#0e141b] text-base font-normal leading-normal flex-1 truncate">leruosebueng@gmail.com <br> info@MunchiesZA.co.za
          </p>
          <div class="shrink-0">
            <div class="text-[#0e141b] flex size-7 items-center justify-center" data-icon="Envelope" data-size="24px" data-weight="regular">
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path
                  d="M224,48H32a8,8,0,0,0-8,8V192a16,16,0,0,0,16,16H216a16,16,0,0,0,16-16V56A8,8,0,0,0,224,48Zm-96,85.15L52.57,64H203.43ZM98.71,128,40,181.81V74.19Zm11.84,10.85,12,11.05a8,8,0,0,0,10.82,0l12-11.05,58,53.15H52.57ZM157.29,128,216,74.18V181.82Z"
                ></path>
              </svg>
            </div>
          </div>
        </div>
        <div class="flex items-center gap-4 bg-slate-50 px-4 min-h-14 justify-between">
          <p class="text-[#0e141b] text-base font-normal leading-normal flex-1 truncate">www.MunchiesZA.co.za</p>
          <div class="shrink-0">
            <div class="text-[#0e141b] flex size-7 items-center justify-center" data-icon="Link" data-size="24px" data-weight="regular">
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path
                  d="M137.54,186.36a8,8,0,0,1,0,11.31l-9.94,10A56,56,0,0,1,48.38,128.4L72.5,104.28A56,56,0,0,1,149.31,102a8,8,0,1,1-10.64,12,40,40,0,0,0-54.85,1.63L59.7,139.72a40,40,0,0,0,56.58,56.58l9.94-9.94A8,8,0,0,1,137.54,186.36Zm70.08-138a56.08,56.08,0,0,0-79.22,0l-9.94,9.95a8,8,0,0,0,11.32,11.31l9.94-9.94a40,40,0,0,1,56.58,56.58L172.18,140.4A40,40,0,0,1,117.33,142,8,8,0,1,0,106.69,154a56,56,0,0,0,76.81-2.26l24.12-24.12A56.08,56.08,0,0,0,207.62,48.38Z"
                ></path>
              </svg>
            </div>
          </div>
        </div>
        <footer class="flex flex-col gap-6 px-5 py-10 text-center @container"><p class="text-[#4e7397] text-base font-normal leading-normal">Munchies ZA</p></footer>
     
      </div>
    </div>
  </body>
</body>
</html>

