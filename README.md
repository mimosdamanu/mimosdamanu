<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mimos da Manu - Personalizados</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css">
    <style>
        body { font-family: Arial, sans-serif; }
        .hero { background: url('https://via.placeholder.com/1500x500') center/cover; color: white; padding: 50px 20px; text-align: center; }
        .product { padding: 20px; text-align: center; }
        .footer { background: #333; color: white; text-align: center; padding: 20px; margin-top: 20px; }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Mimos da Manu</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#produtos">Produtos</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="hero">
        <h1>Personalizados Exclusivos</h1>
        <p>Transforme momentos especiais com nossos produtos</p>
    </div>

    <div class="container" id="produtos">
        <h2 class="text-center mt-4">Nossos Produtos</h2>
        <div class="row">
            <div class="col-md-4 product">
                <img src="https://via.placeholder.com/300" class="img-fluid" alt="Produto 1">
                <h3>Produto 1</h3>
                <p>Descrição do produto.</p>
            </div>
            <div class="col-md-4 product">
                <img src="https://via.placeholder.com/300" class="img-fluid" alt="Produto 2">
                <h3>Produto 2</h3>
                <p>Descrição do produto.</p>
            </div>
            <div class="col-md-4 product">
                <img src="https://via.placeholder.com/300" class="img-fluid" alt="Produto 3">
                <h3>Produto 3</h3>
                <p>Descrição do produto.</p>
            </div>
        </div>
    </div>

    <div class="footer">
        <p>&copy; 2025 Mimos da Manu. Todos os direitos reservados.</p>
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
</body>
</html>
