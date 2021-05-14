<template>
  <div>
    <form
      netlify
      action="/"
      method="POST"
      class="grid grid-cols-1 gap-y-6 grid-cols-2 gap-x-4 sm:gap-x-8"
      name="Contact"
    >
      <input type="hidden" name="form-name" value="Contact" />
      <div>
        <label for="first_name" class="sr-only">First Name</label>
        <input
          type="text"
          name="first_name"
          id="first_name"
          autocomplete="name"
          class="bg-gray-100 block w-full shadow-sm py-3 px-4 placeholder-gray-500 focus:ring-indigo-500 focus:border-indigo-500 border-none rounded-md"
          placeholder="Full name"
        />
      </div>
      <div>
        <label for="last_name" class="sr-only">Last Name</label>
        <input
          type="text"
          name="last_name"
          id="last_name"
          autocomplete="name"
          class="bg-gray-100 block w-full shadow-sm py-3 px-4 placeholder-gray-500 focus:ring-indigo-500 focus:border-indigo-500 border-none rounded-md"
          placeholder="Full name"
        />
      </div>
      <div class="col-span-2">
        <button
          type="submit"
          class="w-full text-center inline-flex justify-center items-center px-3 py-2 border border-transparent text-base leading-4 font-medium rounded-md shadow-sm text-white bg-black hover:bg-gray-800 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-500"
        >
          Submit
        </button>
      </div>
    </form>
  </div>
</template>
