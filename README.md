![Alt text](public/logo.png)
<h2>BC64FilePicker</h2>
<hr />
<p>
    <h4>
        A VueJS File Picker developed for getting documents from the client side and returning the document encoded in a base64 string.
    </h4>
</p>

<h6>Download</h6>

```bash download
npm i @lsbrel/bc64datepicker
```

<h6>Usage</h6>

```html usage
<script setup>
  import BC64FilePicker from "@lsbrel/bc64filepicker";
  import "@lsbrel/bc64filepicker/dist/bc64filepicker.css";
</script>
<template>
  <BC64FilePicker
    text="Clique aqui para enviar um arquivo"
    text-color="#4b5563"
    icon-color="#4b5563"
    border-color="#cacaca"
    @base64result="value => console.log(value)"
  />
</template>
```
