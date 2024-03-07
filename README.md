# HTML
1- METADADOS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Exemplo de uso de meta tags em HTML">
    <meta name="keywords" content="HTML, meta tags, exemplo">
    <title>Exemplo de Meta Tags</title>
</head>
<body>
    <!-- Conteúdo da página -->
</body>
</html>

2- SEPARAÇÃO DE CONTEÚDO
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Exemplo de Div</title>
</head>
<body>
    <div>
        <h1>Título da Seção 1</h1>
        <p>Conteúdo da seção 1...</p>
    </div>
    <div>
        <h2>Título da Seção 2</h2>
        <p>Conteúdo da seção 2...</p>
    </div>
</body>
</html>

3- TEXTO 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Exemplo de Texto</title>
</head>
<body>
    <h1>Título Principal</h1>
    <p>Este é um exemplo de parágrafo em HTML.</p>
    <h2>Subtítulo</h2>
    <p>Outro parágrafo para ilustrar.</p>
</body>
</html>

4-IMAGEM 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Exemplo de Imagem</title>
</head>
<body>
    <h1>Minha Foto</h1>
    <img src="minha_foto.jpg" alt="Minha Foto">
    <h2>Logo da Empresa</h2>
    <img src="logo_empresa.png" alt="Logo da Empresa">
</body>
</html>

5-FORMULARIO
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Exemplo de Formulário</title>
</head>
<body>
    <h1>Formulário de Contato</h1>
    <form action="processar_form.php" method="post">
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome" required><br><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>
        
        <label for="mensagem">Mensagem:</label><br>
        <textarea id="mensagem" name="mensagem" rows="4" cols="50" required></textarea><br><br>
        
        <button type="submit">Enviar</button>
    </form>
</body>
</html>
