<template>
    <div>
        <h1>Account Sign-Up</h1>
        <form method="POST" @submit.prevent="signUp">
            <input type="text" class="form-control" name="username" placeholder="E-mail" required/>
                <input type="password" class="form-control" name="password" placeholder=" Enter Password" required/>
                <br>
                <button type="submit" class="btn btn-success btn-lg" id="submit">SIGN UP</button>
        </form>
    </div>
</template>

<script>
export default {
    name: "signUpForm"
}
</script>