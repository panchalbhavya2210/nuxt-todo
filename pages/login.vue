<script setup lang="ts">
const supabase = useSupabaseClient()
const email = ref('')

// const signInWithOtp = async () => {
//   const { error } = await supabase.auth.signInWithOtp({
//     email: email.value,
//     options: {
//       emailRedirectTo: 'http://localhost:3000/login',
//     }
//   })
//   if (error) console.log(error)
// }

function signInWithOtp() {
    alert(1)
}
</script>
<template>
  <div>
    <button @click="signInWithOtp">
      Sign In with E-Mails
    </button>
    <input
      v-model="email"
      type="email"
    />
  </div>
</template>
