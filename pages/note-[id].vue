<template>
  <div class="h-screen flex items-center justify-center bg-slate-200">
    <div class="w-96 h-96 shadow-lg p-4 bg-slate-50 rounded-md border-t-4 border-yellow-300">
      <div class="flex items-center cursor-pointer text-slate-500 hover:text-slate-950" @click="navigateTo({name: 'index'})">
        <Icon name="material-symbols:arrow-back-ios-new" />
        <h1 class="text-sm ml-2">Back</h1>
      </div>
      <div class="bg-slate-100 h-80 rounded-md mt-2 overflow-auto px-4 py-2">
        <div class="border-b py-1 text-slate-950">
          Example Note
        </div>
        <p class="text-slate-600 text-sm my-2">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Architecto vel veritatis officiis quae ducimus quibusdam suscipit asperiores numquam consequatur doloribus, quo reiciendis tenetur ab, veniam omnis eveniet a, culpa dolorum molestias! Aspernatur tempora ab adipisci numquam qui delectus, dolore quaerat, alias veritatis ipsum magnam? Voluptas eos, tempora quibusdam ipsum exercitationem ipsam. Exercitationem minima voluptatibus dolores cum atque facere quis sequi ipsum? Asperiores natus ut odit itaque expedita, dolorum debitis repellat vel, officiis sunt quibusdam cum, totam nemo nisi dicta aliquam impedit! Iste expedita consequuntur sunt quia magni dolores ex laudantium repellendus. Nesciunt in temporibus quae magni fugiat est ex quidem!
        </p>
      </div>
    </div>
  </div>
</template>