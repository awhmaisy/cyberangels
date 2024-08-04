<script>
    import Navigation from '$lib/Navigation.svelte';
    import '/app.css';
</script>

<div class="toppart">
    <Navigation />
</div>

<div class="container">
    <div>
        <p>hello</p>
    </div>
    <div class="column">
        <p>Sample text for the left column.</p>
        <!-- Add more content as needed -->
    </div>
    <div class="column center-column">
        <h1>Welcome to My Page</h1>
        <p>This is the main content area.</p>
        <!-- Add more content as needed -->
    </div>
    <div class="column">
        <p>Sample text for the right column.</p>
        <!-- Add more content as needed -->
    </div>
</div>