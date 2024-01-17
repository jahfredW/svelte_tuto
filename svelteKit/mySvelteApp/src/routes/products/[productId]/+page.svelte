<script>
    // importer le module page du store, permet de récupérer l'id dynamique du nom de dossier
    // correspond également au paramètre dans l'url 
    import { page } from '$app/stores'

    // récupération de l'id
    const productId = $page.params.productId
</script>

<!-- injection de l'id dans le template  -->
<h1>Details about product { productId }</h1>