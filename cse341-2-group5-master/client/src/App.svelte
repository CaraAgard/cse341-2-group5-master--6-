<!-- App.svelte -->
<script>
  import TodoList from './components/TodoList.svelte'
  import Header from './components/Header.svelte'
  import SignupModal from './components/SignupModal.svelte'
  import SigninModal from './components/SigninModal.svelte'

</script>

<SignupModal />
<SigninModal />

<div class="flex flex-col items-center mt-10 w-96 mx-auto">
  <Header />
  <TodoList />
</div>

<style>
</style>
