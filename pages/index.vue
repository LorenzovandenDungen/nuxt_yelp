<template>
  <div class="flex flex-col h-screen">
    <Header />
    <div class="flex flex-1 overflow-hidden">
      <Sidebar />
      <div class="flex flex-1 overflow-hidden">
        <BusinessList />
        <MapView />
      </div>
    </div>
  </div>
</template>