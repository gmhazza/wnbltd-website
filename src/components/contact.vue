<script setup>

</script>



<template>
        <section id="contact" class="bg-light py-5">
            <div class="container">
                <h2 class="text-center mb-5">Contact Us</h2>
                <div class="row">
                    <div class="col-lg-6 mb-4">
                        <h4>Get in Touch</h4>
                        <p>Ready to start your project? We'd love to hear from you. Send us a message and we'll respond as soon as possible.</p>
                        <ul class="list-unstyled">
                            <li><i class="bi bi-envelope me-2"></i> mhazzashabir@gmail.com</li>
                            <li><i class="bi bi-phone me-2"></i> +92 315 5497354</li>
                            <li><i class="bi bi-geo-alt me-2"></i>255 13V Gulberg Residence, Islamabad, Pakistan</li>
                        </ul>
                    </div>
                    <div class="col-lg-6">
                        <form>
                            <div class="mb-3">
                                <label for="name" class="form-label">Name</label>
                                <input type="text" class="form-control" id="name" required>
                            </div>
                            <div class="mb-3">
                                <label for="email" class="form-label">Email</label>
                                <input type="email" class="form-control" id="email" required>
                            </div>
                            <div class="mb-3">
                                <label for="message" class="form-label">Message</label>
                                <textarea class="form-control" id="message" rows="5" required></textarea>
                            </div>
                            <button type="submit" class="btn btn-primary">Send Message</button>
                        </form>
                    </div>
                </div>
            </div>
        </section>
</template>



<style scoped>

</style>