<script>
	import { page } from '$app/stores';
    import '/app.css';
</script>

<nav>
    <div class="navlogo">
        <img src="/images/ca-logo.png" style="max-width: 250px; padding: 20px;">
    </div>
    <div class="nav-items">
        <a href="/declaration">Declaration of Existence</a>        
        <a href="/shop">Shop</a>
        <a href="/understand">Seek to Understand</a>
        <a href="/play">Fiddle with us</a>
    </div>
</nav>

<style>
  nav {
    display: flex;
    flex-direction: column;  
    align-items: flex-start;
    margin: 0;
    width: 100%;
    padding: 0;
    padding-bottom: 10px;
    box-sizing: border-box;
}

.navlogo {
    display: grid;
}

.nav-items {
    display: flex;
    justify-content: space-between;
    width: 100%; 
}
</style>
