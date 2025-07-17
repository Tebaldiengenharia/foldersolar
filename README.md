!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tebaldi Engenharia & Energia Solar</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f4f8; /* Fundo azul-acinzentado claro */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
            box-sizing: border-box;
        }
        .folder-container {
            max-width: 900px;
            width: 100%;
            background-color: #ffffff;
            border-radius: 1.5rem; /* Cantos mais arredondados */
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
            overflow: hidden;
            display: flex;
            flex-direction: column;
            transition: all 0.3s ease-in-out;
        }
        @media (min-width: 968px) {
            .folder-container {
                flex-direction: row;
            }
        }
        /* Cores personalizadas baseadas na logo */
        .text-tebaldi-blue-dark {
            color: #1A365D; /* Azul escuro da logo */
        }
        .text-tebaldi-blue-light {
            color: #3B82F6; /* Azul claro para destaque */
        }
        .bg-tebaldi-blue-dark {
            background-color: #1A365D;
        }
        .hover\:bg-tebaldi-blue-dark-hover:hover {
            background-color: #152C4A; /* Um pouco mais escuro para hover */
        }
        .bg-gradient-tebaldi {
            background: linear-gradient(to bottom right, #3B82F6, #1A365D); /* Gradiente do azul claro para o escuro */
        }
        .text-tebaldi-orange {
            color: #F59E0B; /* Laranja do sol na logo */
        }
        .svg-tebaldi-green {
            color: #34D399; /* Mantendo um verde para o checkmark, se preferir */
        }
    </style>
</head>
<body class="antialiased">
    <div class="folder-container">
        <!-- Imagem Lateral/Superior com gradiente de cores da logo -->
        <div class="w-full md:w-1/2 bg-gradient-tebaldi p-6 flex items-center justify-center rounded-t-xl md:rounded-l-xl md:rounded-tr-none">
            <!-- Sua logo da Tebaldi Engenharia & Energia Solar. O caminho da imagem é fornecido pelo ambiente. -->
            <img
                src="http://googleusercontent.com/file_content/1"
                alt="Logo Tebaldi Engenharia & Energia Solar"
                class="w-full h-auto object-contain rounded-lg shadow-lg transform hover:scale-105 transition-transform duration-300 max-h-80"
                onerror="this.onerror=null;this.src='https://placehold.co/800x600/9CA3AF/FFFFFF?text=Erro+ao+Carregar+Imagem';"
            >
        </div>

        <!-- Conteúdo Principal -->
        <div class="w-full md:w-1/2 p-8 md:p-12 flex flex-col justify-center">
            <h1 class="text-4xl md:text-5xl font-extrabold text-gray-900 mb-4 leading-tight">
                Ilumine Seu Futuro com <span class="text-tebaldi-orange">Energia Solar</span>
            </h1>
            <p class="text-lg text-gray-700 mb-6">
                Transforme a luz do sol em economia e sustentabilidade para sua casa ou empresa.
                Descubra os benefícios da energia fotovoltaica com a <span class="font-semibold text-tebaldi-blue-dark">
                    Tebaldi Engenharia & Energia Solar
                </span>.
            </p>

            <ul class="list-disc list-inside text-gray-700 mb-8 space-y-2">
                <li class="flex items-center">
                    <svg class="w-5 h-5 svg-tebaldi-green mr-2" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                    Economia significativa na conta de luz.
                </li>
                <li class="flex items-center">
                    <svg class="w-5 h-5 svg-tebaldi-green mr-2" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                    Valorização do seu imóvel.
                </li>
                <li class="flex items-center">
                    <svg class="w-5 h-5 svg-tebaldi-green mr-2" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                    Energia limpa e renovável, protegendo o meio ambiente.
                </li>
                <li class="flex items-center">
                    <svg class="w-5 h-5 svg-tebaldi-green mr-2" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                    Independência energética.
                </li>
            </ul>

            <!-- Botão com link para WhatsApp -->
            <a href="https://wa.me/5519971135834?text=Olá!%20Gostaria%20de%20solicitar%20um%20orçamento%20de%20energia%20solar." target="_blank" class="inline-block bg-tebaldi-blue-dark hover:bg-tebaldi-blue-dark-hover text-white font-bold py-3 px-6 rounded-full text-lg text-center transition-all duration-300 transform hover:scale-105 shadow-lg">
                Solicite um Orçamento Gratuito!
            </a>

            <div id="contato" class="mt-8 pt-6 border-t border-gray-200 text-sm text-gray-600">
                <p class="mb-2">Entre em contato conosco:</p>
                <p>Telefone:
                    <a href="tel:+5519971135834" class="text-tebaldi-blue-light hover:underline">(19) 97113-5834</a>
                </p>
                <p>E-mail:
                    <a href="mailto:tebaldiengenharia@gmail.com" class="text-tebaldi-blue-light hover:underline">tebaldiengenharia@gmail.com</a>
                </p>
                <p>Site:
                    <!-- Insira o URL do seu site aqui, se tiver um -->
                    <a href="http://www.suaempresa.com.br" target="_blank" class="text-tebaldi-blue-light hover:underline">www.suaempresa.com.br</a>
                </p>
                <p class="mt-4 text-xs text-gray-500">
                    Tebaldi Engenharia & Energia Solar - Sua parceira em energia solar.
                </p>
            </div>
        </div>
    </div>
</body>
</html>
