<script lang="ts">
  export let size: number = 48;
  export let className: string = '';
</script>

<svg
  width={size}
  height={size}
  viewBox="0 0 100 100"
  fill="none"
  xmlns="http://www.w3.org/2000/svg"
  class={className}
>
  <!-- Thimble body -->
  <path
    d="M35 30 C35 20, 65 20, 65 30 L65 70 C65 75, 60 80, 50 80 C40 80, 35 75, 35 70 Z"
    fill="currentColor"
    opacity="0.9"
  />
  
  <!-- Dimples/texture on thimble -->
  <circle cx="45" cy="35" r="2" fill="currentColor" opacity="0.3" />
  <circle cx="55" cy="35" r="2" fill="currentColor" opacity="0.3" />
  <circle cx="50" cy="42" r="2" fill="currentColor" opacity="0.3" />
  <circle cx="45" cy="49" r="2" fill="currentColor" opacity="0.3" />
  <circle cx="55" cy="49" r="2" fill="currentColor" opacity="0.3" />
  <circle cx="50" cy="56" r="2" fill="currentColor" opacity="0.3" />
  <circle cx="45" cy="63" r="2" fill="currentColor" opacity="0.3" />
  <circle cx="55" cy="63" r="2" fill="currentColor" opacity="0.3" />
  
  <!-- Top rim highlight -->
  <ellipse cx="50" cy="30" rx="15" ry="3" fill="currentColor" opacity="0.2" />
</svg>