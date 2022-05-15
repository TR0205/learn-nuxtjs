<template>
  <div>
    一覧表示<br>
    <NuxtLink to="/products/create">新規作成</NuxtLink>
    <table>
      <tr>
        <th>商品番号</th>
        <td>商品名<td>
        <td>詳細</td>
        <td>編集</td>
      </tr>
      <tr>
        <td>1</td>
        <td>テスト<td>
        <td>
          <NuxtLink to="/products/1/show">詳細</NuxtLink>
          <NuxtLink to="/products/1/edit">編集</NuxtLink>
        </td>
      </tr>
      <tr>
        <td>2</td>
        <td>テスト<td>
        <td>
          <NuxtLink to="/products/2/show">詳細</NuxtLink>
          <NuxtLink to="/products/2/edit">編集</NuxtLink>
        </td>
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
