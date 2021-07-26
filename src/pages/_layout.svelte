<script>
    import { url } from "@roxi/routify";
</script>

<nav>
    <a href={$url("/")}>Home</a>
    <a href={$url("/about")}>About</a>
</nav>
<slot />

<p>Copyright my website 2021</p>
