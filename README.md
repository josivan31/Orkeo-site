# Orkeo-site
Site Empresarial
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Orkeo - A IA que orquestra sua empresa</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/887c0c2c2d.js" crossorigin="anonymous"></script>
    <style>
        body {
            font-family: 'Manrope', sans-serif;
        }
        .gradient-text {
            background: linear-gradient(90deg, #7B3EE0 0%, #5B2CD8 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .btn-primary {
            background: linear-gradient(90deg, #7B3EE0 0%, #5B2CD8 100%);
            box-shadow: 0 4px 15px rgba(123, 62, 224, 0.3);
        }
        .section {
            scroll-margin-top: 100px;
        }
    </style>
</head>
<body class="bg-gray-900 text-white">
    <!-- Navbar -->
    <nav class="fixed w-full bg-gray-900/90 backdrop-blur-md z-50 border-b border-gray-800">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <div class="w-8 h-8 bg-gradient-to-r from-purple-500 to-indigo-600 rounded-lg flex items-center justify-center">
                    <span class="text-white font-bold text-sm">O</span>
                </div>
                <span class="text-xl font-bold">Orkeo</span>
            </div>
            <div class="hidden md:flex space-x-8">
                <a href="#problema" class="hover:text-purple-400 transition">Problema</a>
                <a href="#solucao" class="hover:text-purple-400 transition">Solução</a>
                <a href="#como-funciona" class="hover:text-purple-400 transition">Como Funciona</a>
                <a href="#planos" class="hover:text-purple-400 transition">Planos</a>
            </div>
            <a href="#contato" class="bg-gradient-to-r from-purple-500 to-indigo-600 px-6 py-2 rounded-full text-sm font-medium hover:shadow-lg transform hover:-translate-y-0.5 transition">Agende um diagnóstico</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="pt-32 pb-20 px-6 text-center">
        <div class="max-w-4xl mx-auto">
            <h1 class="text-5xl md:text-6xl font-bold mb-6 leading-tight">
                A IA que 
                <span class="gradient-text">orquestra</span> 
                sua empresa
            </h1>
            <p class="text-xl text-gray-300 mb-8 leading-relaxed">
                Automatizamos processos operacionais para empresas com faturamento acima de R$ 50 mil/mês. 
                Em 7 dias, seu maior gargalo vira automático.
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="#contato" class="btn-primary text-white px-8 py-4 rounded-xl text-lg font-semibold hover:shadow-2xl transform hover:-translate-y-1 transition">
                    Agende um diagnóstico gratuito
                </a>
                <a href="#solucao" class="border border-gray-600 hover:border-purple-500 px-8 py-4 rounded-xl text-lg font-medium hover:bg-gray-800 transition flex items-center justify-center">
                    <i class="fas fa-play-circle mr-2"></i> Veja como funciona
                </a>
            </div>
        </div>
    </section>

    <!-- Problem Section -->
    <section id="problema" class="py-20 px-6 bg-gray-800/50 section">
        <div class="max-w-6xl mx-auto">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-4xl font-bold mb-6">
                        Você cresceu. 
                        <span class="text-purple-400">Mas seus processos continuam manuais?</span>
                    </h2>
                    <p class="text-xl text-gray-300 mb-6">
                        Empresas com +R$ 50k/mês ainda perdem:
                    </p>
                    <div class="space-y-4">
                        <div class="flex items-start space-x-3">
                            <div class="w-6 h-6 bg-purple-500 rounded-full flex items-center justify-center mt-1 flex-shrink-0">
                                <i class="fas fa-check text-white text-xs"></i>
                            </div>
                            <p class="text-lg">20h+ por semana com tarefas repetitivas</p>
                        </div>
                        <div class="flex items-start space-x-3">
                            <div class="w-6 h-6 bg-purple-500 rounded-full flex items-center justify-center mt-1 flex-shrink-0">
                                <i class="fas fa-check text-white text-xs"></i>
                            </div>
                            <p class="text-lg">Leads por falta de follow-up</p>
                        </div>
                        <div class="flex items-start space-x-3">
                            <div class="w-6 h-6 bg-purple-500 rounded-full flex items-center justify-center mt-1 flex-shrink-0">
                                <i class="fas fa-check text-white text-xs"></i>
                            </div>
                            <p class="text-lg">Dinheiro com erros em cobrança, planilhas, atendimento</p>
                        </div>
                    </div>
                    <p class="text-xl text-gray-300 mt-8">
                        Isso não é escala. 
                        <span class="font-semibold text-white">É retrabalho disfarçado de produtividade.</span>
                    </p>
                </div>
                <div class="bg-gray-800 rounded-2xl p-8 border border-gray-700">
                    <div class="space-y-4">
                        <div class="flex items-center space-x-4 p-4 bg-red-500/20 border border-red-500/30 rounded-lg">
                            <div class="w-12 h-12 bg-red-500 rounded-lg flex items-center justify-center flex-shrink-0">
                                <i class="fas fa-clock text-white"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold">Tempo perdido</h3>
                                <p class="text-sm text-gray-400">32h/mês em tarefas repetitivas</p>
                            </div>
                        </div>
                        <div class="flex items-center space-x-4 p-4 bg-yellow-500/20 border border-yellow-500/30 rounded-lg">
                            <div class="w-12 h-12 bg-yellow-500 rounded-lg flex items-center justify-center flex-shrink-0">
                                <i class="fas fa-exclamation-triangle text-white"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold">Erros operacionais</h3>
                                <p class="text-sm text-gray-400">7 em cada 10 processos têm falhas</p>
                            </div>
                        </div>
                        <div class="flex items-center space-x-4 p-4 bg-blue-500/20 border border-blue-500/30 rounded-lg">
                            <div class="w-12 h-12 bg-blue-500 rounded-lg flex items-center justify-center flex-shrink-0">
                                <i class="fas fa-arrow-down text-white"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold">Crescimento travado</h3>
                                <p class="text-sm text-gray-400">83% das empresas não escalam por processos manuais</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Solution Section -->
    <section id="solucao" class="py-20 px-6 section">
        <div class="max-w-6xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold mb-4">Conheça o <span class="gradient-text">Orkeo Core</span></h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                    A IA que entra na sua empresa, entende seus processos e orquestra tudo em automático — sem código, sem equipe técnica.
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6 mb-16">
                <div class="bg-gray-800/70 p-6 rounded-2xl border border-gray-700 hover:border-purple-500/50 transition group">
                    <div class="w-12 h-12 bg-gradient-to-r from-purple-500 to-indigo-600 rounded-xl flex items-center justify-center mb-4 group-hover:scale-110 transition">
                        <i class="fas fa-bullseye text-white text-lg"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Orkeo Sales</h3>
                    <p class="text-gray-400">Prospecção B2B autônoma com follow-up inteligente e agendamento de reuniões</p>
                </div>
                
                <div class="bg-gray-800/70 p-6 rounded-2xl border border-gray-700 hover:border-purple-500/50 transition group">
                    <div class="w-12 h-12 bg-gradient-to-r from-purple-500 to-indigo-600 rounded-xl flex items-center justify-center mb-4 group-hover:scale-110 transition">
                        <i class="fas fa-comments text-white text-lg"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Orkeo Atendimento</h3>
                    <p class="text-gray-400">Respostas inteligentes no WhatsApp e e-mail com memória de cliente</p>
                </div>
                
                <div class="bg-gray-800/70 p-6 rounded-2xl border border-gray-700 hover:border-purple-500/50 transition group">
                    <div class="w-12 h-12 bg-gradient-to-r from-purple-500 to-indigo-600 rounded-xl flex items-center justify-center mb-4 group-hover:scale-110 transition">
                        <i class="fas fa-tasks text-white text-lg"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Orkeo Ops</h3>
                    <p class="text-gray-400">Automação de tarefas, relatórios e alertas operacionais</p>
                </div>
                
                <div class="bg-gray-800/70 p-6 rounded-2xl border border-gray-700 hover:border-purple-500/50 transition group">
                    <div class="w-12 h-12 bg-gradient-to-r from-purple-500 to-indigo-600 rounded-xl flex items-center justify-center mb-4 group-hover:scale-110 transition">
                        <i class="fas fa-wallet text-white text-lg"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Orkeo Financeiro</h3>
                    <p class="text-gray-400">Cobrança inteligente, lembretes e conciliação automática</p>
                </div>
            </div>

            <div class="bg-gradient-to-r from-purple-900/30 to-indigo-900/30 p-8 rounded-2xl border border-purple-500/30 text-center max-w-4xl mx-auto">
                <h3 class="text-2xl font-bold mb-4">Resultado em 30 dias:</h3>
                <div class="grid md:grid-cols-3 gap-6">
                    <div>
                        <div class="text-3xl font-bold text-purple-400">+40h</div>
                        <div class="text-gray-300">recuperadas por mês</div>
                    </div>
                    <div>
                        <div class="text-3xl font-bold text-green-400">70%</div>
                        <div class="text-gray-300">menos erros operacionais</div>
                    </div>
                    <div>
                        <div class="text-3xl font-bold text-blue-400">3.2x</div>
                        <div class="text-gray-300">mais escalabilidade</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- How it Works -->
    <section id="como-funciona" class="py-20 px-6 bg-gray-800/50 section">
        <div class="max-w-6xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold mb-4">Em 4 passos, sua operação vira <span class="gradient-text">autônoma</span></h2>
                <p class="text-xl text-gray-300">Processo simples e rápido para você começar a escalar</p>
            </div>
            
            <div class="grid md:grid-cols-4 gap-8">
                <div class="text-center">
                    <div class="w-16 h-16 bg-gradient-to-r from-purple-500 to-indigo-600 rounded-full flex items-center justify-center mx-auto mb-6 text-2xl font-bold">
                        1
                    </div>
                    <h3 class="text-xl font-semibold mb-4">Diagnóstico (1h)</h3>
                    <p class="text-gray-400">Nós mapeamos seu maior gargalo operacional e identificamos oportunidades de automação.</p>
                </div>
                
                <div class="text-center">
                    <div class="w-16 h-16 bg-gradient-to-r from-purple-500 to-indigo-600 rounded-full flex items-center justify-center mx-auto mb-6 text-2xl font-bold">
                        2
                    </div>
                    <h3 class="text-xl font-semibold mb-4">Escolha do Processo</h3>
                    <p class="text-gray-400">Você escolhe qual processo será automatizado: vendas, atendimento, financeiro ou operações.</p>
                </div>
                
                <div class="text-center">
                    <div class="w-16 h-16 bg-gradient-to-r from-purple-500 to-indigo-600 rounded-full flex items-center justify-center mx-auto mb-6 text-2xl font-bold">
                        3
                    </div>
                    <h3 class="text-xl font-semibold mb-4">Orquestração com IA</h3>
                    <p class="text-gray-400">Criamos a automação personalizada com inteligência artificial e testamos com seus dados.</p>
                </div>
                
                <div class="text-center">
                    <div class="w-16 h-16 bg-gradient-to-r from-purple-500 to-indigo-600 rounded-full flex items-center justify-center mx-auto mb-6 text-2xl font-bold">
                        4
                    </div>
                    <h3 class="text-xl font-semibold mb-4">Resultado em 7 Dias</h3>
                    <p class="text-gray-400">Entregamos, treinamos sua equipe e você começa a ver resultados imediatos.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing -->
    <section id="planos" class="py-20 px-6 section">
        <div class="max-w-6xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold mb-4">Comece com um processo. <span class="gradient-text">Escalone com tudo.</span></h2>
                <p class="text-xl text-gray-300">Soluções para empresas que querem crescer com inteligência</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
                <div class="bg-gray-800/70 rounded-2xl border border-gray-700 p-8 hover:border-purple-500/50 transition group">
                    <div class="text-center">
                        <h3 class="text-2xl font-bold mb-2">Piloto Orkeo</h3>
                        <div class="text-4xl font-bold mb-4">R$ 997</div>
                        <p class="text-gray-400 mb-6">único | 1 processo</p>
                        
                        <ul class="space-y-3 mb-8 text-left">
                            <li class="flex items-center space-x-3">
                                <i class="fas fa-check text-green-400"></i>
                                <span>Diagnóstico operacional</span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <i class="fas fa-check text-green-400"></i>
                                <span>1 processo automatizado</span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <i class="fas fa-check text-green-400"></i>
                                <span>Treinamento da equipe</span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <i class="fas fa-check text-green-400"></i>
                                <span>Relatório de impacto</span>
                            </li>
                        </ul>
                        
                        <a href="#contato" class="btn-primary w-full text-white py-3 rounded-xl font-semibold hover:shadow-2xl transform hover:-translate-y-1 transition">
                            Começar com o Piloto
                        </a>
                    </div>
                </div>
                
                <div class="bg-gradient-to-b from-purple-900/30 to-transparent rounded-2xl border-2 border-purple-500/50 p-8 transform scale-105 relative">
                    <div class="absolute -top-4 left-1/2 transform -translate-x-1/2">
                        <span class="bg-gradient-to-r from-purple-500 to-indigo-600 px-6 py-2 rounded-full text-sm font-semibold">MAIS POPULAR</span>
                    </div>
                    <div class="text-center">
                        <h3 class="text-2xl font-bold mb-2">Crescimento</h3>
                        <div class="text-4xl font-bold mb-4">R$ 1.497<span class="text-lg font-normal text-gray-400">/mês</span></div>
                        <p class="text-gray-400 mb-6">3 módulos | atualizações</p>
                        
                        <ul class="space-y-3 mb-8 text-left">
                            <li class="flex items-center space-x-3">
                                <i class="fas fa-check text-green-400"></i>
                                <span>3 processos automatizados</span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <i class="fas fa-check text-green-400"></i>
                                <span>Atualizações mensais</span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <i class="fas fa-check text-green-400"></i>
                                <span>Suporte prioritário</span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <i class="fas fa-check text-green-400"></i>
                                <span>Relatórios de desempenho</span>
                            </li>
                        </ul>
                        
                        <a href="#contato" class="btn-primary w-full text-white py-3 rounded-xl font-semibold hover:shadow-2xl transform hover:-translate-y-1 transition">
                            Assinar Plano Crescimento
                        </a>
                    </div>
                </div>
                
                <div class="bg-gray-800/70 rounded-2xl border border-gray-700 p-8 hover:border-purple-500/50 transition group">
                    <div class="text-center">
                        <h3 class="text-2xl font-bold mb-2">Autônomo</h3>
                        <div class="text-4xl font-bold mb-4">R$ 3.997<span class="text-lg font-normal text-gray-400">/mês</span></div>
                        <p class="text-gray-400 mb-6">tudo orquestrado | IA dedicada</p>
                        
                        <ul class="space-y-3 mb-8 text-left">
                            <li class="flex items-center space-x-3">
                                <i class="fas fa-check text-green-400"></i>
    
