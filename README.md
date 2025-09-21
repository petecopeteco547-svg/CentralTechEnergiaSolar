<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Central Tech Energia Solar - Soluções em Energia Renovável</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'solar-orange': '#fe8f04',
                        'solar-dark': '#262626',
                        'solar-gray': '#6B7280'
                    }
                }
            }
        }
    </script>
    <style>

        
        .hero-bg {
            background: linear-gradient(135deg, rgba(38, 38, 38, 0.7), rgba(254, 143, 4, 0.5)), 
                        url('https://i.imgur.com/0jBPo4q.jpg');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }
        
        .smooth-scroll {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="font-sans text-gray-800 smooth-scroll">


    <!-- Header -->
    <header class="bg-white shadow-lg sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4">
            <div class="flex justify-between items-center">
                <!-- Logo -->
                <div class="flex items-center space-x-3">
                    <img src="https://i.imgur.com/A2YbXOd.png" 
                         alt="Central Tech Energia Solar Logo" 
                         class="h-12 w-auto"
                         onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                    <div class="w-12 h-12 bg-[#fe8f04] rounded-full flex items-center justify-center" style="display: none;">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#262626]">
                            <circle cx="12" cy="12" r="5"/>
                            <line x1="12" y1="1" x2="12" y2="3"/>
                            <line x1="12" y1="21" x2="12" y2="23"/>
                            <line x1="4.22" y1="4.22" x2="5.64" y2="5.64"/>
                            <line x1="18.36" y1="18.36" x2="19.78" y2="19.78"/>
                            <line x1="1" y1="12" x2="3" y2="12"/>
                            <line x1="21" y1="12" x2="23" y2="12"/>
                            <line x1="4.22" y1="19.78" x2="5.64" y2="18.36"/>
                            <line x1="18.36" y1="5.64" x2="19.78" y2="4.22"/>
                        </svg>
                    </div>
                </div>

                <!-- Navigation -->
                <nav class="hidden md:flex space-x-8">
                    <a href="#inicio" class="text-gray-700 hover:text-solar-orange transition-colors">Início</a>
                    <a href="#sobre" class="text-gray-700 hover:text-solar-orange transition-colors">Sobre Nós</a>
                    <a href="#servicos" class="text-gray-700 hover:text-solar-orange transition-colors">Serviços</a>
                    <a href="#projetos" class="text-gray-700 hover:text-solar-orange transition-colors">Projetos</a>
                    <a href="#contato" class="text-gray-700 hover:text-solar-orange transition-colors">Contato</a>
                </nav>

                <!-- Mobile Menu Button -->
                <button id="mobile-menu-btn" class="md:hidden text-gray-700">
                    <svg width="24" height="24" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
                    </svg>
                </button>
            </div>

            <!-- Mobile Menu -->
            <nav id="mobile-menu" class="hidden md:hidden mt-4 pb-4">
                <div class="flex flex-col space-y-4">
                    <a href="#inicio" class="text-gray-700 hover:text-solar-orange transition-colors">Início</a>
                    <a href="#sobre" class="text-gray-700 hover:text-solar-orange transition-colors">Sobre Nós</a>
                    <a href="#servicos" class="text-gray-700 hover:text-solar-orange transition-colors">Serviços</a>
                    <a href="#projetos" class="text-gray-700 hover:text-solar-orange transition-colors">Projetos</a>
                    <a href="#contato" class="text-gray-700 hover:text-solar-orange transition-colors">Contato</a>
                </div>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="inicio" class="hero-bg min-h-screen flex items-center">
        <div class="container mx-auto px-4 text-center text-white">
            <h2 class="text-4xl md:text-6xl font-bold mb-6 drop-shadow-2xl text-shadow-lg" style="text-shadow: 2px 2px 4px rgba(0,0,0,0.8), 0 0 10px rgba(0,0,0,0.5);">
                Quem disse que dinheiro não cai do céu?
            </h2>
            <p class="text-xl md:text-2xl mb-8 drop-shadow-xl font-medium" style="text-shadow: 1px 1px 3px rgba(0,0,0,0.8), 0 0 8px rgba(0,0,0,0.4);">
                Transforme a energia do sol em economia real para sua casa ou empresa
            </p>
            <button onclick="document.getElementById('contato').scrollIntoView({behavior: 'smooth'})" 
                    class="bg-solar-orange text-white px-8 py-4 rounded-full text-lg font-semibold hover:bg-orange-600 transition-all transform hover:scale-105 shadow-2xl border-2 border-white">
                Solicite um Orçamento
            </button>
        </div>
    </section>

    <!-- Sobre Nós -->
    <section id="sobre" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="max-w-4xl mx-auto text-center">
                <h2 class="text-3xl md:text-4xl font-bold text-solar-dark mb-8">Sobre Nós</h2>
                <div class="grid md:grid-cols-3 gap-8 mb-12">
                    <div class="bg-white p-6 rounded-lg shadow-md">
                        <div class="w-16 h-16 bg-solar-orange rounded-full flex items-center justify-center mx-auto mb-4">
                            <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-white">
                                <path d="M9 12l2 2 4-4"/>
                                <path d="M21 12c-1 0-3-1-3-3s2-3 3-3 3 1 3 3-2 3-3 3"/>
                                <path d="M3 12c1 0 3-1 3-3s-2-3-3-3-3 1-3 3 2 3 3 3"/>
                                <path d="M12 3c0 1-1 3-3 3s-3-2-3-3 1-3 3-3 3 2 3 3"/>
                                <path d="M12 21c0-1 1-3 3-3s3 2 3 3-1 3-3 3-3-2-3-3"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-semibold text-solar-dark mb-2">Experiência</h3>
                        <p class="text-gray-600">Anos de experiência no mercado de energia solar, com centenas de projetos executados com excelência.</p>
                    </div>
                    
                    <div class="bg-white p-6 rounded-lg shadow-md">
                        <div class="w-16 h-16 bg-solar-orange rounded-full flex items-center justify-center mx-auto mb-4">
                            <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-white">
                                <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-semibold text-solar-dark mb-2">Credibilidade</h3>
                        <p class="text-gray-600">Empresa certificada e licenciada, com garantia total em todos os nossos serviços e equipamentos.</p>
                    </div>
                    
                    <div class="bg-white p-6 rounded-lg shadow-md">
                        <div class="w-16 h-16 bg-solar-orange rounded-full flex items-center justify-center mx-auto mb-4">
                            <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-white">
                                <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/>
                                <circle cx="12" cy="7" r="4"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-semibold text-solar-dark mb-2">Atendimento</h3>
                        <p class="text-gray-600">Atendimento personalizado do projeto à instalação, com suporte técnico especializado.</p>
                    </div>
                </div>
                
                <p class="text-lg text-gray-700 leading-relaxed">
                    A Central Tech Energia Solar é especializada em soluções completas de energia fotovoltaica. 
                    Nossa missão é democratizar o acesso à energia limpa e renovável, proporcionando economia 
                    significativa na conta de luz e contribuindo para um futuro mais sustentável.
                </p>
            </div>
        </div>
    </section>

    <!-- Serviços -->
    <section id="servicos" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-solar-dark text-center mb-12">Nossos Serviços</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="text-center p-6 border-2 border-gray-200 rounded-lg hover:border-solar-orange transition-colors">
                    <div class="w-20 h-20 bg-solar-dark rounded-full flex items-center justify-center mx-auto mb-6">
                        <svg width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2">
                            <path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/>
                            <polyline points="9,22 9,12 15,12 15,22"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-solar-dark mb-4">Energia Solar Residencial</h3>
                    <p class="text-gray-600">
                        Sistemas fotovoltaicos completos para residências. Reduza sua conta de luz em até 90% 
                        com nossa tecnologia de ponta e instalação profissional.
                    </p>
                </div>
                
                <div class="text-center p-6 border-2 border-gray-200 rounded-lg hover:border-solar-orange transition-colors">
                    <div class="w-20 h-20 bg-solar-dark rounded-full flex items-center justify-center mx-auto mb-6">
                        <svg width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2">
                            <path d="M6 2L3 6v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V6l-3-4z"/>
                            <line x1="3" y1="6" x2="21" y2="6"/>
                            <path d="M16 10a4 4 0 0 1-8 0"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-solar-dark mb-4">Energia Solar Comercial</h3>
                    <p class="text-gray-600">
                        Soluções empresariais que reduzem custos operacionais e aumentam a competitividade 
                        do seu negócio com energia limpa e sustentável.
                    </p>
                </div>
                
                <div class="text-center p-6 border-2 border-gray-200 rounded-lg hover:border-solar-orange transition-colors">
                    <div class="w-20 h-20 bg-solar-dark rounded-full flex items-center justify-center mx-auto mb-6">
                        <svg width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2">
                            <path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/>
                            <path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-solar-dark mb-4">Energia Solar Rural</h3>
                    <p class="text-gray-600">
                        Sistemas especializados para propriedades rurais, incluindo bombeamento solar 
                        e eletrificação de áreas remotas.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Projetos -->
    <section id="projetos" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-solar-dark text-center mb-12">Nossos Projetos</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <div class="h-48 overflow-hidden">
                        <img src="https://i.imgur.com/6882Nvo.jpg" 
                             alt="Instalação de energia solar residencial em Brasília" 
                             class="w-full h-full object-cover"
                             onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <div class="h-48 bg-gray-200 flex items-center justify-center" style="display: none;">
                            <p class="text-gray-500 text-center px-4">Espaço para Foto<br>Instalação Residencial</p>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-lg font-semibold text-solar-dark mb-2">Residência - Padre Bernardo-GO</h3>
                        <p class="text-gray-600">Sistema de 3,9kWp instalado em residência, gerando economia de 90% na conta de luz.</p>
                    </div>
                </div>
                
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <div class="h-48 overflow-hidden">
                        <img src="https://i.imgur.com/HqCqxzj.jpg" 
                             alt="Instalação de energia solar comercial em Brasília-DF" 
                             class="w-full h-full object-cover"
                             onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <div class="h-48 bg-gray-200 flex items-center justify-center" style="display: none;">
                            <p class="text-gray-500 text-center px-4">Espaço para Foto<br>Instalação Comercial</p>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-lg font-semibold text-solar-dark mb-2">Empresa - Brasília-DF</h3>
                        <p class="text-gray-600">Sistema comercial de 50kWp, reduzindo custos operacionais significativamente.</p>
                    </div>
                </div>
                
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <div class="h-48 overflow-hidden">
                        <img src="https://i.imgur.com/aqcApNl.jpg" 
                             alt="Instalação de energia solar rural em Padre Bernardo" 
                             class="w-full h-full object-cover"
                             onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <div class="h-48 bg-gray-200 flex items-center justify-center" style="display: none;">
                            <p class="text-gray-500 text-center px-4">Espaço para Foto<br>Instalação Rural</p>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-lg font-semibold text-solar-dark mb-2">Fazenda - Padre Bernardo</h3>
                        <p class="text-gray-600">Sistema rural de 6kWp para bombeamento solar poço artesiano.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contato -->
    <section id="contato" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-solar-dark text-center mb-12">Entre em Contato</h2>
            <div class="max-w-2xl mx-auto">
                <div class="mb-8 text-center">
                    <p class="text-gray-600 mb-4">Fale conosco diretamente pelo WhatsApp:</p>
                    <div class="flex flex-col sm:flex-row gap-4 justify-center">
                        <a href="https://wa.me/5561992658100?text=Olá! Gostaria de solicitar um orçamento para energia solar." 
                           target="_blank" 
                           rel="noopener noreferrer"
                           class="inline-flex items-center bg-solar-orange text-white px-6 py-3 rounded-lg hover:bg-orange-600 transition-colors">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor" class="mr-2">
                                <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.890-5.335 11.893-11.893A11.821 11.821 0 0020.465 3.516"/>
                            </svg>
                            Falar com Ruan
                        </a>
                        
                        <a href="https://wa.me/5561999338526?text=Olá! Gostaria de solicitar um orçamento para energia solar." 
                           target="_blank" 
                           rel="noopener noreferrer"
                           class="inline-flex items-center bg-solar-orange text-white px-6 py-3 rounded-lg hover:bg-orange-600 transition-colors">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor" class="mr-2">
                                <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.890-5.335 11.893-11.893A11.821 11.821 0 0020.465 3.516"/>
                            </svg>
                            Falar com Diogo
                        </a>
                    </div>
                </div>
                
                <div class="text-center mb-6">
                    <p class="text-gray-600">Ou preencha o formulário abaixo:</p>
                </div>
                
                <form id="contact-form" class="space-y-6">
                    <div class="grid md:grid-cols-2 gap-6">
                        <div>
                            <label for="nome" class="block text-sm font-medium text-gray-700 mb-2">Nome Completo</label>
                            <input type="text" id="nome" name="nome" required 
                                   class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-solar-orange focus:border-transparent">
                        </div>
                        <div>
                            <label for="telefone" class="block text-sm font-medium text-gray-700 mb-2">Telefone</label>
                            <input type="tel" id="telefone" name="telefone" required 
                                   class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-solar-orange focus:border-transparent">
                        </div>
                    </div>
                    
                    <div>
                        <label for="email" class="block text-sm font-medium text-gray-700 mb-2">E-mail</label>
                        <input type="email" id="email" name="email" required 
                               class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-solar-orange focus:border-transparent">
                    </div>
                    
                    <div>
                        <label for="mensagem" class="block text-sm font-medium text-gray-700 mb-2">Mensagem</label>
                        <textarea id="mensagem" name="mensagem" rows="5" required 
                                  class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-solar-orange focus:border-transparent"
                                  placeholder="Conte-nos sobre seu projeto de energia solar..."></textarea>
                    </div>
                    
                    <button type="submit" 
                            class="w-full bg-solar-orange text-white px-8 py-4 rounded-lg text-lg font-semibold hover:bg-orange-600 transition-colors">
                        Enviar Mensagem
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-solar-dark text-white py-16">
        <div class="container mx-auto px-4">
            <!-- Main Footer Content -->
            <div class="grid lg:grid-cols-3 md:grid-cols-2 gap-8 mb-12">
                <!-- Company Info -->
                <div class="lg:col-span-2">
                    <div class="flex items-center space-x-3 mb-6">
                        <img src="https://i.imgur.com/vjynQjy.png" 
                             alt="Central Tech Energia Solar Logo" 
                             class="h-12 w-auto"
                             onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <div class="w-12 h-12 bg-[#fe8f04] rounded-full flex items-center justify-center" style="display: none;">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#262626]">
                                <circle cx="12" cy="12" r="5"/>
                                <line x1="12" y1="1" x2="12" y2="3"/>
                                <line x1="12" y1="21" x2="12" y2="23"/>
                                <line x1="4.22" y1="4.22" x2="5.64" y2="5.64"/>
                                <line x1="18.36" y1="18.36" x2="19.78" y2="19.78"/>
                                <line x1="1" y1="12" x2="3" y2="12"/>
                                <line x1="21" y1="12" x2="23" y2="12"/>
                                <line x1="4.22" y1="19.78" x2="5.64" y2="18.36"/>
                                <line x1="18.36" y1="5.64" x2="19.78" y2="4.22"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-white">Central Tech Energia Solar</h3>
                        </div>
                    </div>
                    <p class="text-gray-300 text-lg mb-6 leading-relaxed max-w-md">
                        Especialistas em energia solar fotovoltaica. Transformamos a luz do sol em economia real para sua casa ou empresa.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#" target="_blank" rel="noopener noreferrer" 
                           class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center text-gray-300 hover:bg-solar-orange hover:text-white transition-all duration-300">
                            <svg width="20" height="20" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"/>
                            </svg>
                        </a>
                        <a href="#" target="_blank" rel="noopener noreferrer" 
                           class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center text-gray-300 hover:bg-solar-orange hover:text-white transition-all duration-300">
                            <svg width="20" height="20" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
                            </svg>
                        </a>
                        <a href="#" target="_blank" rel="noopener noreferrer" 
                           class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center text-gray-300 hover:bg-solar-orange hover:text-white transition-all duration-300">
                            <svg width="20" height="20" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M22.46 6c-.77.35-1.6.58-2.46.69.88-.53 1.56-1.37 1.88-2.38-.83.5-1.75.85-2.72 1.05C18.37 4.5 17.26 4 16 4c-2.35 0-4.27 1.92-4.27 4.29 0 .34.04.67.11.98C8.28 9.09 5.11 7.38 3 4.79c-.37.63-.58 1.37-.58 2.15 0 1.49.75 2.81 1.91 3.56-.71 0-1.37-.2-1.95-.5v.03c0 2.08 1.48 3.82 3.44 4.21a4.22 4.22 0 0 1-1.93.07 4.28 4.28 0 0 0 4 2.98 8.521 8.521 0 0 1-5.33 1.84c-.34 0-.68-.02-1.02-.06C3.44 20.29 5.7 21 8.12 21 16 21 20.33 14.46 20.33 8.79c0-.19 0-.37-.01-.56.84-.6 1.56-1.36 2.14-2.23z"/>
                            </svg>
                        </a>
                    </div>
                </div>
                
                <!-- Contact Info -->
                <div>
                    <h4 class="text-lg font-semibold mb-6 text-white">Contato</h4>
                    <div class="space-y-4">
                        <div class="flex items-start space-x-3">
                            <div class="w-5 h-5 text-solar-orange mt-1">
                                <svg fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"/>
                                </svg>
                            </div>
                            <p class="text-gray-300">Rua Governador Mauro Borges<br>Padre Bernardo - GO</p>
                        </div>
                        
                        <div class="flex items-center space-x-3">
                            <div class="w-5 h-5 text-solar-orange">
                                <svg fill="currentColor" viewBox="0 0 20 20">
                                    <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
                                </svg>
                            </div>
                            <div class="text-gray-300">
                                <p>Ruan: (61) 99265-8100</p>
                                <p>Diogo: (61) 99933-8526</p>
                            </div>
                        </div>
                        
                        <div class="flex items-center space-x-3">
                            <div class="w-5 h-5 text-solar-orange">
                                <svg fill="currentColor" viewBox="0 0 20 20">
                                    <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/>
                                    <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/>
                                </svg>
                            </div>
                            <p class="text-gray-300">centraltechsolucoesenergia@gmail.com</p>
                        </div>
                    </div>
                </div>
                

            </div>
            
            <!-- Bottom Footer -->
            <div class="border-t border-gray-600 pt-8">
                <div class="flex flex-col md:flex-row justify-between items-center space-y-4 md:space-y-0">
                    <p class="text-gray-400 text-sm">
                        &copy; 2024 Central Tech Energia Solar. Todos os direitos reservados.
                    </p>
                    <div class="flex space-x-6 text-sm text-gray-400">
                        <a href="#" class="hover:text-solar-orange transition-colors">Política de Privacidade</a>
                        <a href="#" class="hover:text-solar-orange transition-colors">Termos de Uso</a>
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.getElementById('mobile-menu-btn').addEventListener('click', function() {
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenu.classList.toggle('hidden');
        });

        // Form submission
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const formData = new FormData(this);
            const nome = formData.get('nome');
            const telefone = formData.get('telefone');
            const email = formData.get('email');
            const mensagem = formData.get('mensagem');
            
            // Create WhatsApp message
            const whatsappMessage = `Olá! Meu nome é ${nome}.

📧 E-mail: ${email}
📞 Telefone: ${telefone}

Mensagem: ${mensagem}

Gostaria de receber um orçamento para energia solar.`;
            
            const whatsappUrl = `https://wa.me/5561992658100?text=${encodeURIComponent(whatsappMessage)}`;
            
            // Show success message
            alert('Redirecionando para o WhatsApp com suas informações!');
            
            // Open WhatsApp
            window.open(whatsappUrl, '_blank', 'noopener,noreferrer');
            
            // Reset form
            this.reset();
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                    
                    // Close mobile menu if open
                    const mobileMenu = document.getElementById('mobile-menu');
                    mobileMenu.classList.add('hidden');
                }
            });
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'98256c72a1f8344f',t:'MTc1ODQxNDMwOC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
