<!DOCTYPE html><html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DIA DAS MÃES</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-pink-50 font-sans">  <!-- Header -->  <header class="bg-red-500 text-white p-5 text-center text-3xl font-bold">
    🌸 DIA DAS MÃES 🌸
  </header>  <!-- Produto -->  <section class="p-6 flex flex-col items-center">
    <img src="/mnt/data/file_0000000054ec71f5a2b59636f53161e6" alt="Cesta Dia das Mães" class="rounded-2xl shadow-lg w-full max-w-md">
    <h2 class="text-2xl font-bold mt-4">Cesta Café da Manhã + Chocolates</h2>
    <p class="text-xl text-green-600 font-semibold">R$ 25,00</p><button onclick="mostrarFormulario()" class="mt-4 bg-red-500 text-white px-6 py-3 rounded-2xl shadow hover:bg-red-600">
  Comprar Agora
</button>

  </section>  <!-- Formulário -->  <section id="formulario" class="hidden p-6">
    <div class="max-w-md mx-auto bg-white p-6 rounded-2xl shadow">
      <h3 class="text-xl font-bold mb-4">Criar Conta</h3><input type="text" placeholder="Nome" class="w-full mb-3 p-2 border rounded">
  <input type="email" placeholder="Email" class="w-full mb-3 p-2 border rounded">
  <input type="text" placeholder="Endereço" class="w-full mb-3 p-2 border rounded">
  <input type="password" placeholder="Senha" class="w-full mb-3 p-2 border rounded">

  <button onclick="pagar()" class="w-full bg-green-500 text-white p-3 rounded-xl mt-2 hover:bg-green-600">
    Ir para pagamento
  </button>
</div>

  </section>  <!-- Footer -->  <footer class="text-center p-4 text-gray-600">
    © 2026 DIA DAS MÃES - Feito com carinho 💖
  </footer>  <script>
    function mostrarFormulario() {
      document.getElementById('formulario').classList.remove('hidden');
      window.scrollTo({ top: document.getElementById('formulario').offsetTop, behavior: 'smooth' });
    }

    function pagar() {
      window.location.href = "https://app.syncpayments.com.br/payment-link/a1a58857-4496-427c-9c7a-7e2f6bca4acd";
    }
  </script></body>
</html
