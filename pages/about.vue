<template>
    <div class="container">
        <Navigation />
        <div class="content">
            <div class="card">
                <h1>About Itinerary</h1>
                <p>Itinerary is the successor of <a href="https://scratchtools.edu.eu.org">Scratch Tools</a>, a project that became unsustainable mainly due to its architecture.</p>
                <br />
                <h2>In depth</h2>
                <p>
                    <i>Coming soon...</i>
                </p>
            </div>
            <div class="card">
                <h1>Credits</h1>
                <p>Thank you to everyone who contributed in any way to this project! <a href="https://allcontributors.org/docs/en/emoji-key">What do the emoji represent?</a></p>
                <br />
                <Contributors />
            </div>
        </div>
        <Footer />
    </div>
</template>

<script>
    export default {
        head() {
            return {
                title: 'About | Itinerary'
            };
        }
    };
</script>

<style scoped>
</style>