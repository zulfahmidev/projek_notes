<template>
  <div class="h-screen flex items-center justify-center bg-slate-200">
    <div class="w-96 h-96 shadow-lg p-4 bg-slate-50 rounded-md border-t-4 border-yellow-300">
      <div class="flex justify-between items-center ">
        <h1 class="text-xl">Notes</h1>
        <div class="rounded-full active:bg-slate-200 bg-slate-100 text-slate-800 cursor-pointer w-7 h-7 flex items-center justify-center">
          <Icon name="material-symbols:add-circle-outline" />
        </div>
      </div>
      <div class="w-full py-2 rounded-md bg-slate-100 mt-2 hover:shadow-md border-t-2 border-slate-300 flex justify-between items-center" v-for="index in 5" :key="index">
        <div class="px-4 cursor-pointer" @click="navigateTo(`note-${index}`)">
          note-{{ index }}
        </div>
        <div class="pr-4">
          <div class="rounded-full active:bg-slate-200 text-slate-800 cursor-pointer w-7 h-7 flex items-center justify-center">
            <Icon name="material-symbols:delete-forever-outline-sharp" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>