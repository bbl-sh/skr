<script>
    import Navbar from '../components/Navbar.svelte';
    import Card from '../components/Card.svelte';
</script>

<Navbar /> 
<main class="container mx-auto px-4 py-10">
    <h2 class="text-3xl font-bold mb-8">Getting Started</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <Card 
        title="My Card" 
        description="This is the first point. This is the second point. Here's the third point"
        />
    </div>
</main>