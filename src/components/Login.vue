<script setup>
import { ref } from "vue";
</script>

<template>
  <div class="card lg:card-side bg-base-100 shadow-xl max-w-3xl">
    <figure>
      <img
        src="https://daisyui.com/images/stock/photo-1494232410401-ad00d5433cfa.jpg"
        alt="Album"
      />
    </figure>
    <div class="card-body">
      <form>
        <h2 class="card-title">Login</h2>
        <div class="mb-3">
          <label class="form-control w-full max-w-xs">
            <div class="label">
              <span class="label-text">Email</span>
            </div>
            <input
              type="email"
              placeholder="Email"
              class="input input-bordered w-full max-w-xs"
            />
          </label>
        </div>
        <div class="mb-3">
          <label class="form-control w-full max-w-xs">
            <div class="label">
              <span class="label-text">Password</span>
            </div>
            <input
              type="password"
              placeholder="Password"
              class="input input-bordered w-full max-w-xs"
            />
          </label>
        </div>
        <div class="card-actions justify-end">
          <button type="submit" class="btn btn-primary">Login</button>
        </div>
      </form>
    </div>
  </div>
</template>
