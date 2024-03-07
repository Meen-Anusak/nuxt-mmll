<template>
  <div class="">
    <div
      class="w-full h-[126px] bg-[#46A09B] bg-cover rounded"
      style="
        background-image: url(https://static.cdntap.com/tap-assets-prod/wp-content/uploads/sites/25/2021/09/howto0.jpg);
      "
    ></div>

    <div class="w-full bg-white p-2 gap-y-2 mt-3 rounded">
      <div class="w-full bg-gray-200 rounded p-3">
        <div class="text-black text-xs font-light">ยอดเงินของคุณ</div>
        <div class="text-center mt-2 text-3xl font-bold flex items-center justify-around">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="currentColor"
            class="w-9 h-9 text-[#46A09B]"
          >
            <path
              d="M2.273 5.625A4.483 4.483 0 0 1 5.25 4.5h13.5c1.141 0 2.183.425 2.977 1.125A3 3 0 0 0 18.75 3H5.25a3 3 0 0 0-2.977 2.625ZM2.273 8.625A4.483 4.483 0 0 1 5.25 7.5h13.5c1.141 0 2.183.425 2.977 1.125A3 3 0 0 0 18.75 6H5.25a3 3 0 0 0-2.977 2.625ZM5.25 9a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h13.5a3 3 0 0 0 3-3v-6a3 3 0 0 0-3-3H15a.75.75 0 0 0-.75.75 2.25 2.25 0 0 1-4.5 0A.75.75 0 0 0 9 9H5.25Z"
            />
          </svg>
          <div>100,000.00</div>
          <div>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-9 h-9 text-[#46A09B]"
            >
              <path
                d="M10.464 8.746c.227-.18.497-.311.786-.394v2.795a2.252 2.252 0 0 1-.786-.393c-.394-.313-.546-.681-.546-1.004 0-.323.152-.691.546-1.004ZM12.75 15.662v-2.824c.347.085.664.228.921.421.427.32.579.686.579.991 0 .305-.152.671-.579.991a2.534 2.534 0 0 1-.921.42Z"
              />
              <path
                fill-rule="evenodd"
                d="M12 2.25c-5.385 0-9.75 4.365-9.75 9.75s4.365 9.75 9.75 9.75 9.75-4.365 9.75-9.75S17.385 2.25 12 2.25ZM12.75 6a.75.75 0 0 0-1.5 0v.816a3.836 3.836 0 0 0-1.72.756c-.712.566-1.112 1.35-1.112 2.178 0 .829.4 1.612 1.113 2.178.502.4 1.102.647 1.719.756v2.978a2.536 2.536 0 0 1-.921-.421l-.879-.66a.75.75 0 0 0-.9 1.2l.879.66c.533.4 1.169.645 1.821.75V18a.75.75 0 0 0 1.5 0v-.81a4.124 4.124 0 0 0 1.821-.749c.745-.559 1.179-1.344 1.179-2.191 0-.847-.434-1.632-1.179-2.191a4.122 4.122 0 0 0-1.821-.75V8.354c.29.082.559.213.786.393l.415.33a.75.75 0 0 0 .933-1.175l-.415-.33a3.836 3.836 0 0 0-1.719-.755V6Z"
                clip-rule="evenodd"
              />
            </svg>
          </div>
        </div>
      </div>
      <div class="grid grid-cols-2 gap-3 mt-3">
        <button
          class="text-white col-span-1 font-medium p-1 bg-[#46A09B] flex items-center justify-center gap-x-2 rounded-full"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="currentColor"
            class="w-6 h-6"
          >
            <path
              fill-rule="evenodd"
              d="M12 2.25c-5.385 0-9.75 4.365-9.75 9.75s4.365 9.75 9.75 9.75 9.75-4.365 9.75-9.75S17.385 2.25 12 2.25ZM12.75 9a.75.75 0 0 0-1.5 0v2.25H9a.75.75 0 0 0 0 1.5h2.25V15a.75.75 0 0 0 1.5 0v-2.25H15a.75.75 0 0 0 0-1.5h-2.25V9Z"
              clip-rule="evenodd"
            />
          </svg>

          เติมเงิน
        </button>
        <button
          class="text-white col-span-1 font-medium p-1 bg-[#46A09B] flex items-center justify-center gap-x-2 rounded-full"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="currentColor"
            class="w-6 h-6"
          >
            <path
              fill-rule="evenodd"
              d="M12 2.25c-5.385 0-9.75 4.365-9.75 9.75s4.365 9.75 9.75 9.75 9.75-4.365 9.75-9.75S17.385 2.25 12 2.25Zm3 10.5a.75.75 0 0 0 0-1.5H9a.75.75 0 0 0 0 1.5h6Z"
              clip-rule="evenodd"
            />
          </svg>

          ถอนเงิน
        </button>
      </div>
      <div class="mt-3 grid grid-cols-12 gap-3 text-sm">
        <div
          class="col-span-4 p-2 py-4 bg-[#46A09B28] flex flex-col items-center justify-center gap-y-1 rounded"
        >
          <div>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-8 h-8 text-[#46A09B]"
            >
              <path
                d="M21.731 2.269a2.625 2.625 0 0 0-3.712 0l-1.157 1.157 3.712 3.712 1.157-1.157a2.625 2.625 0 0 0 0-3.712ZM19.513 8.199l-3.712-3.712-8.4 8.4a5.25 5.25 0 0 0-1.32 2.214l-.8 2.685a.75.75 0 0 0 .933.933l2.685-.8a5.25 5.25 0 0 0 2.214-1.32l8.4-8.4Z"
              />
              <path
                d="M5.25 5.25a3 3 0 0 0-3 3v10.5a3 3 0 0 0 3 3h10.5a3 3 0 0 0 3-3V13.5a.75.75 0 0 0-1.5 0v5.25a1.5 1.5 0 0 1-1.5 1.5H5.25a1.5 1.5 0 0 1-1.5-1.5V8.25a1.5 1.5 0 0 1 1.5-1.5h5.25a.75.75 0 0 0 0-1.5H5.25Z"
              />
            </svg>
          </div>

          <div class="text-sm font-medium">แทงหวย</div>
        </div>
        <div
          class="col-span-4 p-2 py-4 bg-[#46A09B28] flex flex-col items-center justify-center gap-y-1 rounded"
        >
          <div>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-8 h-8 text-[#46A09B]"
            >
              <path
                fill-rule="evenodd"
                d="M1.5 6.375c0-1.036.84-1.875 1.875-1.875h17.25c1.035 0 1.875.84 1.875 1.875v3.026a.75.75 0 0 1-.375.65 2.249 2.249 0 0 0 0 3.898.75.75 0 0 1 .375.65v3.026c0 1.035-.84 1.875-1.875 1.875H3.375A1.875 1.875 0 0 1 1.5 17.625v-3.026a.75.75 0 0 1 .374-.65 2.249 2.249 0 0 0 0-3.898.75.75 0 0 1-.374-.65V6.375Zm15-1.125a.75.75 0 0 1 .75.75v.75a.75.75 0 0 1-1.5 0V6a.75.75 0 0 1 .75-.75Zm.75 4.5a.75.75 0 0 0-1.5 0v.75a.75.75 0 0 0 1.5 0v-.75Zm-.75 3a.75.75 0 0 1 .75.75v.75a.75.75 0 0 1-1.5 0v-.75a.75.75 0 0 1 .75-.75Zm.75 4.5a.75.75 0 0 0-1.5 0V18a.75.75 0 0 0 1.5 0v-.75ZM6 12a.75.75 0 0 1 .75-.75H12a.75.75 0 0 1 0 1.5H6.75A.75.75 0 0 1 6 12Zm.75 2.25a.75.75 0 0 0 0 1.5h3a.75.75 0 0 0 0-1.5h-3Z"
                clip-rule="evenodd"
              />
            </svg>
          </div>

          <div class="text-sm font-medium">ซื้อล็อตเตอรี่</div>
        </div>
        <div
          class="col-span-4 p-2 py-4 bg-[#46A09B28] flex flex-col items-center justify-center gap-y-1 rounded"
        >
          <div>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-8 h-8 text-[#46A09B]"
            >
              <path
                d="M5.566 4.657A4.505 4.505 0 0 1 6.75 4.5h10.5c.41 0 .806.055 1.183.157A3 3 0 0 0 15.75 3h-7.5a3 3 0 0 0-2.684 1.657ZM2.25 12a3 3 0 0 1 3-3h13.5a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5.25a3 3 0 0 1-3-3v-6ZM5.25 7.5c-.41 0-.806.055-1.184.157A3 3 0 0 1 6.75 6h10.5a3 3 0 0 1 2.683 1.657A4.505 4.505 0 0 0 18.75 7.5H5.25Z"
              />
            </svg>
          </div>

          <div class="text-sm font-medium">ซื้อหวยมะก่องถี่</div>
        </div>
      </div>
      <div class="grid-col-1 mt-3">
        <div
          class="col-span-1 p-2 bg-[#46A09B28] text-center flex items-center justify-center gap-x-1"
        >
          <div>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6 text-[#46A09B]"
            >
              <path
                fill-rule="evenodd"
                d="M2.25 12c0-5.385 4.365-9.75 9.75-9.75s9.75 4.365 9.75 9.75-4.365 9.75-9.75 9.75S2.25 17.385 2.25 12Zm14.024-.983a1.125 1.125 0 0 1 0 1.966l-5.603 3.113A1.125 1.125 0 0 1 9 15.113V8.887c0-.857.921-1.4 1.671-.983l5.603 3.113Z"
                clip-rule="evenodd"
              />
            </svg>
          </div>
          <div>LIVE</div>
        </div>
      </div>
      <div class="mt-3 grid grid-cols-12 gap-2 text-sm">
        <div
          class="col-span-3 p-1 py-3 gap-y-2 bg-[#46A09B28] flex flex-col items-center justify-center rounded-md"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="currentColor"
            class="w-6 h-6 text-[#46A09B]"
          >
            <path
              d="M9.375 3a1.875 1.875 0 0 0 0 3.75h1.875v4.5H3.375A1.875 1.875 0 0 1 1.5 9.375v-.75c0-1.036.84-1.875 1.875-1.875h3.193A3.375 3.375 0 0 1 12 2.753a3.375 3.375 0 0 1 5.432 3.997h3.943c1.035 0 1.875.84 1.875 1.875v.75c0 1.036-.84 1.875-1.875 1.875H12.75v-4.5h1.875a1.875 1.875 0 1 0-1.875-1.875V6.75h-1.5V4.875C11.25 3.839 10.41 3 9.375 3ZM11.25 12.75H3v6.75a2.25 2.25 0 0 0 2.25 2.25h6v-9ZM12.75 12.75v9h6.75a2.25 2.25 0 0 0 2.25-2.25v-6.75h-9Z"
            />
          </svg>

          <div class="text-xs">ผลรางวัล</div>
        </div>
        <div
          class="col-span-3 p-1 py-3 gap-y-2 bg-[#46A09B28] flex flex-col items-center justify-center rounded-md"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="currentColor"
            class="w-6 h-6 text-[#46A09B]"
          >
            <path
              fill-rule="evenodd"
              d="M15.97 2.47a.75.75 0 0 1 1.06 0l4.5 4.5a.75.75 0 0 1 0 1.06l-4.5 4.5a.75.75 0 1 1-1.06-1.06l3.22-3.22H7.5a.75.75 0 0 1 0-1.5h11.69l-3.22-3.22a.75.75 0 0 1 0-1.06Zm-7.94 9a.75.75 0 0 1 0 1.06l-3.22 3.22H16.5a.75.75 0 0 1 0 1.5H4.81l3.22 3.22a.75.75 0 1 1-1.06 1.06l-4.5-4.5a.75.75 0 0 1 0-1.06l4.5-4.5a.75.75 0 0 1 1.06 0Z"
              clip-rule="evenodd"
            />
          </svg>

          <div class="text-xs">ประวัติรายการ</div>
        </div>
        <div
          class="col-span-3 p-1 py-3 gap-y-2 bg-[#46A09B28] flex flex-col items-center justify-center rounded-md"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="currentColor"
            class="w-6 h-6 text-[#46A09B]"
          >
            <path
              fill-rule="evenodd"
              d="M7.502 6h7.128A3.375 3.375 0 0 1 18 9.375v9.375a3 3 0 0 0 3-3V6.108c0-1.505-1.125-2.811-2.664-2.94a48.972 48.972 0 0 0-.673-.05A3 3 0 0 0 15 1.5h-1.5a3 3 0 0 0-2.663 1.618c-.225.015-.45.032-.673.05C8.662 3.295 7.554 4.542 7.502 6ZM13.5 3A1.5 1.5 0 0 0 12 4.5h4.5A1.5 1.5 0 0 0 15 3h-1.5Z"
              clip-rule="evenodd"
            />
            <path
              fill-rule="evenodd"
              d="M3 9.375C3 8.339 3.84 7.5 4.875 7.5h9.75c1.036 0 1.875.84 1.875 1.875v11.25c0 1.035-.84 1.875-1.875 1.875h-9.75A1.875 1.875 0 0 1 3 20.625V9.375ZM6 12a.75.75 0 0 1 .75-.75h.008a.75.75 0 0 1 .75.75v.008a.75.75 0 0 1-.75.75H6.75a.75.75 0 0 1-.75-.75V12Zm2.25 0a.75.75 0 0 1 .75-.75h3.75a.75.75 0 0 1 0 1.5H9a.75.75 0 0 1-.75-.75ZM6 15a.75.75 0 0 1 .75-.75h.008a.75.75 0 0 1 .75.75v.008a.75.75 0 0 1-.75.75H6.75a.75.75 0 0 1-.75-.75V15Zm2.25 0a.75.75 0 0 1 .75-.75h3.75a.75.75 0 0 1 0 1.5H9a.75.75 0 0 1-.75-.75ZM6 18a.75.75 0 0 1 .75-.75h.008a.75.75 0 0 1 .75.75v.008a.75.75 0 0 1-.75.75H6.75a.75.75 0 0 1-.75-.75V18Zm2.25 0a.75.75 0 0 1 .75-.75h3.75a.75.75 0 0 1 0 1.5H9a.75.75 0 0 1-.75-.75Z"
              clip-rule="evenodd"
            />
          </svg>

          <div class="text-xs">สร้างเลขชุด</div>
        </div>
        <div
          class="col-span-3 p-1 py-3 gap-y-2 bg-[#46A09B28] flex flex-col items-center justify-center rounded-md"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="currentColor"
            class="w-6 h-6 text-[#46A09B]"
          >
            <path
              fill-rule="evenodd"
              d="M8.25 6.75a3.75 3.75 0 1 1 7.5 0 3.75 3.75 0 0 1-7.5 0ZM15.75 9.75a3 3 0 1 1 6 0 3 3 0 0 1-6 0ZM2.25 9.75a3 3 0 1 1 6 0 3 3 0 0 1-6 0ZM6.31 15.117A6.745 6.745 0 0 1 12 12a6.745 6.745 0 0 1 6.709 7.498.75.75 0 0 1-.372.568A12.696 12.696 0 0 1 12 21.75c-2.305 0-4.47-.612-6.337-1.684a.75.75 0 0 1-.372-.568 6.787 6.787 0 0 1 1.019-4.38Z"
              clip-rule="evenodd"
            />
            <path
              d="M5.082 14.254a8.287 8.287 0 0 0-1.308 5.135 9.687 9.687 0 0 1-1.764-.44l-.115-.04a.563.563 0 0 1-.373-.487l-.01-.121a3.75 3.75 0 0 1 3.57-4.047ZM20.226 19.389a8.287 8.287 0 0 0-1.308-5.135 3.75 3.75 0 0 1 3.57 4.047l-.01.121a.563.563 0 0 1-.373.486l-.115.04c-.567.2-1.156.349-1.764.441Z"
            />
          </svg>

          <div class="text-xs">แชร์เพื่อน</div>
        </div>
        <div
          class="col-span-3 p-1 py-3 gap-y-2 bg-[#46A09B28] flex flex-col items-center justify-center rounded-md"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="currentColor"
            class="w-6 h-6 text-[#46A09B]"
          >
            <path
              fill-rule="evenodd"
              d="M12.963 2.286a.75.75 0 0 0-1.071-.136 9.742 9.742 0 0 0-3.539 6.176 7.547 7.547 0 0 1-1.705-1.715.75.75 0 0 0-1.152-.082A9 9 0 1 0 15.68 4.534a7.46 7.46 0 0 1-2.717-2.248ZM15.75 14.25a3.75 3.75 0 1 1-7.313-1.172c.628.465 1.35.81 2.133 1a5.99 5.99 0 0 1 1.925-3.546 3.75 3.75 0 0 1 3.255 3.718Z"
              clip-rule="evenodd"
            />
          </svg>

          <div class="text-xs">โบนัส</div>
        </div>
        <div
          class="col-span-3 p-1 py-3 gap-y-2 bg-[#46A09B28] flex flex-col items-center justify-center rounded-md"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="currentColor"
            class="w-6 h-6 text-[#46A09B]"
          >
            <path
              d="M11.25 4.533A9.707 9.707 0 0 0 6 3a9.735 9.735 0 0 0-3.25.555.75.75 0 0 0-.5.707v14.25a.75.75 0 0 0 1 .707A8.237 8.237 0 0 1 6 18.75c1.995 0 3.823.707 5.25 1.886V4.533ZM12.75 20.636A8.214 8.214 0 0 1 18 18.75c.966 0 1.89.166 2.75.47a.75.75 0 0 0 1-.708V4.262a.75.75 0 0 0-.5-.707A9.735 9.735 0 0 0 18 3a9.707 9.707 0 0 0-5.25 1.533v16.103Z"
            />
          </svg>

          <div class="text-xs">วิธีใช้งาน</div>
        </div>
        <div
          class="col-span-3 p-1 py-3 gap-y-2 bg-[#46A09B28] flex flex-col items-center justify-center rounded-md"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="currentColor"
            class="w-6 h-6 text-[#46A09B]"
          >
            <path
              d="M18.375 2.25c-1.035 0-1.875.84-1.875 1.875v15.75c0 1.035.84 1.875 1.875 1.875h.75c1.035 0 1.875-.84 1.875-1.875V4.125c0-1.036-.84-1.875-1.875-1.875h-.75ZM9.75 8.625c0-1.036.84-1.875 1.875-1.875h.75c1.036 0 1.875.84 1.875 1.875v11.25c0 1.035-.84 1.875-1.875 1.875h-.75a1.875 1.875 0 0 1-1.875-1.875V8.625ZM3 13.125c0-1.036.84-1.875 1.875-1.875h.75c1.036 0 1.875.84 1.875 1.875v6.75c0 1.035-.84 1.875-1.875 1.875h-.75A1.875 1.875 0 0 1 3 19.875v-6.75Z"
            />
          </svg>

          <div class="text-xs">ผู้ถูกรางวัล</div>
        </div>
        <div
          class="col-span-3 p-0.5 py-3 gap-y-2 bg-[#46A09B28] flex flex-col items-center justify-center rounded-md"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="currentColor"
            class="w-6 h-6 text-[#46A09B]"
          >
            <path
              d="M4.913 2.658c2.075-.27 4.19-.408 6.337-.408 2.147 0 4.262.139 6.337.408 1.922.25 3.291 1.861 3.405 3.727a4.403 4.403 0 0 0-1.032-.211 50.89 50.89 0 0 0-8.42 0c-2.358.196-4.04 2.19-4.04 4.434v4.286a4.47 4.47 0 0 0 2.433 3.984L7.28 21.53A.75.75 0 0 1 6 21v-4.03a48.527 48.527 0 0 1-1.087-.128C2.905 16.58 1.5 14.833 1.5 12.862V6.638c0-1.97 1.405-3.718 3.413-3.979Z"
            />
            <path
              d="M15.75 7.5c-1.376 0-2.739.057-4.086.169C10.124 7.797 9 9.103 9 10.609v4.285c0 1.507 1.128 2.814 2.67 2.94 1.243.102 2.5.157 3.768.165l2.782 2.781a.75.75 0 0 0 1.28-.53v-2.39l.33-.026c1.542-.125 2.67-1.433 2.67-2.94v-4.286c0-1.505-1.125-2.811-2.664-2.94A49.392 49.392 0 0 0 15.75 7.5Z"
            />
          </svg>

          <div class="text-xs">ติดต่อเจ้าหน้าที่</div>
        </div>
      </div>
    </div>

    <div
      class="w-full h-[126px] bg-[#46A09B] bg-cover rounded mt-3"
      style="
        background-image: url(https://www.brighttv.co.th/wp-content/uploads/2021/06/10-%E0%B9%80%E0%B8%A5%E0%B8%82%E0%B9%80%E0%B8%94%E0%B9%87%E0%B8%94-1.png);
      "
    ></div>

    <div class="bg-white p-2 gap-y-2 mt-3 rounded">
      <h1 class="text-[#46A09B]">News</h1>
      <div class="grid grid-cols-12 gap-2 gap-y-4 mt-3 text-[10px]">
        <div
          class="col-span-3 bg-[#46A09B] bg-cover w-full"
          style="
            background-image: url(https://www.sawad.co.th/wp-content/uploads/2022/09/%E0%B8%8B%E0%B8%B7%E0%B9%89%E0%B8%AD%E0%B8%AB%E0%B8%A7%E0%B8%A2%E0%B8%AD%E0%B8%AD%E0%B8%99%E0%B9%84%E0%B8%A5%E0%B8%99%E0%B9%8C%E0%B8%A3%E0%B8%B2%E0%B8%84%E0%B8%B2-80-%E0%B8%9A%E0%B8%B2%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B9%81%E0%B8%AD%E0%B8%9B%E0%B9%80%E0%B8%9B%E0%B9%8B%E0%B8%B2%E0%B8%95%E0%B8%B1%E0%B8%87.jpg);
          "
        ></div>
        <div class="col-span-9 w-full">
          <div class="text-black">
            Sydney man discovers he's $20 million richer after Powerball win
          </div>
          <div class="text-gray-500">
            One mystery Sydney shopper is waking up $20 million richer, while 20
            Victorians each become millionaires in a winning syndicate, after $40 million
            Powerball draw.
          </div>
        </div>
        <div
          class="col-span-3 bg-[#46A09B] bg-cover w-full"
          style="
            background-image: url(https://www.sawad.co.th/wp-content/uploads/2022/09/%E0%B8%8B%E0%B8%B7%E0%B9%89%E0%B8%AD%E0%B8%AB%E0%B8%A7%E0%B8%A2%E0%B8%AD%E0%B8%AD%E0%B8%99%E0%B9%84%E0%B8%A5%E0%B8%99%E0%B9%8C%E0%B8%A3%E0%B8%B2%E0%B8%84%E0%B8%B2-80-%E0%B8%9A%E0%B8%B2%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B9%81%E0%B8%AD%E0%B8%9B%E0%B9%80%E0%B8%9B%E0%B9%8B%E0%B8%B2%E0%B8%95%E0%B8%B1%E0%B8%87.jpg);
          "
        ></div>
        <div class="col-span-9 w-full">
          <div class="text-black">
            Sydney man discovers he's $20 million richer after Powerball win
          </div>
          <div class="text-gray-500">
            One mystery Sydney shopper is waking up $20 million richer, while 20
            Victorians each become millionaires in a winning syndicate, after $40 million
            Powerball draw.
          </div>
        </div>
        <div
          class="col-span-3 bg-[#46A09B] bg-cover w-full"
          style="
            background-image: url(https://www.sawad.co.th/wp-content/uploads/2022/09/%E0%B8%8B%E0%B8%B7%E0%B9%89%E0%B8%AD%E0%B8%AB%E0%B8%A7%E0%B8%A2%E0%B8%AD%E0%B8%AD%E0%B8%99%E0%B9%84%E0%B8%A5%E0%B8%99%E0%B9%8C%E0%B8%A3%E0%B8%B2%E0%B8%84%E0%B8%B2-80-%E0%B8%9A%E0%B8%B2%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B9%81%E0%B8%AD%E0%B8%9B%E0%B9%80%E0%B8%9B%E0%B9%8B%E0%B8%B2%E0%B8%95%E0%B8%B1%E0%B8%87.jpg);
          "
        ></div>
        <div class="col-span-9 w-full">
          <div class="text-black">
            Sydney man discovers he's $20 million richer after Powerball win
          </div>
          <div class="text-gray-500">
            One mystery Sydney shopper is waking up $20 million richer, while 20
            Victorians each become millionaires in a winning syndicate, after $40 million
            Powerball draw.
          </div>
        </div>
        <div
          class="col-span-3 bg-[#46A09B] bg-cover w-full"
          style="
            background-image: url(https://www.sawad.co.th/wp-content/uploads/2022/09/%E0%B8%8B%E0%B8%B7%E0%B9%89%E0%B8%AD%E0%B8%AB%E0%B8%A7%E0%B8%A2%E0%B8%AD%E0%B8%AD%E0%B8%99%E0%B9%84%E0%B8%A5%E0%B8%99%E0%B9%8C%E0%B8%A3%E0%B8%B2%E0%B8%84%E0%B8%B2-80-%E0%B8%9A%E0%B8%B2%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B9%81%E0%B8%AD%E0%B8%9B%E0%B9%80%E0%B8%9B%E0%B9%8B%E0%B8%B2%E0%B8%95%E0%B8%B1%E0%B8%87.jpg);
          "
        ></div>
        <div class="col-span-9 w-full">
          <div class="text-black">
            Sydney man discovers he's $20 million richer after Powerball win
          </div>
          <div class="text-gray-500">
            One mystery Sydney shopper is waking up $20 million richer, while 20
            Victorians each become millionaires in a winning syndicate, after $40 million
            Powerball draw.
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped></style>
