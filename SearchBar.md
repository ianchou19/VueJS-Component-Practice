```vue
<template>
  <SearchBar class="temp_style" :autocomplete_data='{
    fakeData_1: {
      id: "item_1",
      content: "apple"
    },
    fakeData_2: {
      id: "item_2",
      content: "apple farmer"
    },
    fakeData_3: {
      id: "item_3",
      content: "apple is delicious"
    },
    fakeData_4: {
      id: "item_4",
      content: "apple apple apple!"
    },
    fakeData_5: {
      id: "item_5",
      content: "apple can save your life!!!!!"
    }
  }'/>
</template>
<style>
.temp_style {
  width: 723px;
}
</style>
```