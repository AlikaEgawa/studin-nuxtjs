<template>
  <div>
    <h2>一覧表示</h2>
    <NuxtLink to="./products/create">新規作成</NuxtLink>

    <table>
      <tr>
        <th>商品番号</th>
        <th>商品名</th>
        <th>詳細</th>
        <th>編集</th>
      </tr>
      <tr>
        <td>1</td>
        <td>商品A</td>
        <td><NuxtLink to="/products/1/show">詳細</NuxtLink></td>
        <td><NuxtLink to="/products/1/edit">編集</NuxtLink></td>
      </tr>
      <tr>
        <td>2</td>
        <td>商品B</td>
        <td><NuxtLink to="/products/2/show">詳細</NuxtLink></td>
        <td><NuxtLink to="/products/2/edit">編集</NuxtLink></td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>