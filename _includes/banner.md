
<style> 
	.cds-hero { 
		background-image: 
			url('{{ include.banner }}'); background-position: 80%; } 
			
</style>

<section class="cds-hero">
  <div class="container">
    <div class="cds-hero-callout">
      <h1 class="cds-hero-heading">
          <span class="text-white">{{ include.title }}</span>
      </h1>
          <p>{{ include.description }}</p>
          
    </div>
  </div>
</section>
