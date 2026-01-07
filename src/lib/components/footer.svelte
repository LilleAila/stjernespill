<script lang="ts">
  import Instagram from "$lib/assets/instagram.svelte";
  import TikTok from "$lib/assets/tiktok.svelte";
  import Facebook from "$lib/assets/facebook.svelte";
</script>

<footer>
  <p>
    <small>&copy; 2026 Stjernespill UB. All rights reserved.</small>
  </p>
  <ul>
    <li>
      <a
        href="https://www.tiktok.com/@stjernespillub?_t=ZN-90trEtXFeVy&_r=1"
        target="_blank"
        aria-label="TikTok logo"
      >
        <TikTok />
      </a>
    </li>
    <li>
      <a
        href="https://www.instagram.com/stjernespill.ub/"
        target="_blank"
        aria-label="Instagram logo"
      >
        <Instagram />
      </a>
    </li>
    <li>
      <a
        href="https://www.facebook.com/profile.php?id=61582798795489"
        target="_blank"
        aria-label="Facebook logo"
      >
        <Facebook />
      </a>
    </li>
  </ul>
</footer>
