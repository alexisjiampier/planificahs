<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PlanificaSH - Plataforma Financiera Completa</title>
    <script src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
    <script src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Quitar flechas de inputs numéricos */
        input[type="number"]::-webkit-inner-spin-button,
        input[type="number"]::-webkit-outer-spin-button {
            -webkit-appearance: none;
            margin: 0;
        }
        input[type="number"] {
            -moz-appearance: textfield;
        }
        
        .line-clamp-3 {
            display: -webkit-box;
            -webkit-line-clamp: 3;
            -webkit-box-orient: vertical;
            overflow: hidden;
        }
        
        @keyframes slideIn {
            from { transform: translateX(100%); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }
        
        @keyframes slideOut {
            from { transform: translateX(0); opacity: 1; }
            to { transform: translateX(100%); opacity: 0; }
        }
        
        @keyframes fadeInUp {
            from { transform: translateY(30px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        
        @keyframes bounce {
            0%, 20%, 53%, 80%, 100% { transform: translateY(0); }
            40%, 43% { transform: translateY(-30px); }
            70% { transform: translateY(-15px); }
            90% { transform: translateY(-4px); }
        }
        
        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: .5; }
        }
        
        @keyframes spin {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        
        @keyframes wiggle {
            0%, 7% { transform: rotateZ(0); }
            15% { transform: rotateZ(-15deg); }
            20% { transform: rotateZ(10deg); }
            25% { transform: rotateZ(-10deg); }
            30% { transform: rotateZ(6deg); }
            35% { transform: rotateZ(-4deg); }
            40%, 100% { transform: rotateZ(0); }
        }
        
        .animate-pulse { animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite; }
        .animate-bounce { animation: bounce 1s infinite; }
        .animate-spin { animation: spin 1s linear infinite; }
        .animate-wiggle { animation: wiggle 1s ease-in-out; }
        .animate-fadeInUp { animation: fadeInUp 0.6s ease-out; }
        
        .glass-effect {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .gradient-button {
            background: linear-gradient(135deg, #8b5cf6, #ec4899);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .gradient-button::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
            transition: left 0.5s;
        }
        
        .gradient-button:hover::before {
            left: 100%;
        }
        
        .gradient-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(139, 92, 246, 0.4);
        }
        
        .button-hover-effect {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        
        .button-hover-effect:hover {
            transform: translateY(-2px) scale(1.02);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
        }
        
        .floating-animation {
            animation: float 6s ease-in-out infinite;
        }
        
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0px); }
        }
        
        .notification-enter {
            animation: slideIn 0.3s ease-out;
        }
        
        .notification-exit {
            animation: slideOut 0.3s ease-in;
        }
        
        /* Efectos de glassmorphism mejorados */
        .glass-card {
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0.05));
            backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.15);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
        }
        
        .glass-card:hover {
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.15), rgba(255, 255, 255, 0.08));
            border: 1px solid rgba(255, 255, 255, 0.25);
            box-shadow: 0 12px 40px rgba(0, 0, 0, 0.4);
        }
        
        /* Scrollbar personalizado */
        ::-webkit-scrollbar {
            width: 8px;
        }
        
        ::-webkit-scrollbar-track {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
        }
        
        ::-webkit-scrollbar-thumb {
            background: linear-gradient(135deg, #8b5cf6, #ec4899);
            border-radius: 10px;
        }
        
        ::-webkit-scrollbar-thumb:hover {
            background: linear-gradient(135deg, #7c3aed, #db2777);
        }
    </style>
</head>
<body>
    <div id="root"></div>
    <script type="text/babel">
        const { useState, useEffect } = React;

        // Iconos como componentes SVG optimizados
        const StarIcon = ({ className, onClick, filled = false }) => (
            <svg className={`${className} transition-all duration-200`} onClick={onClick} fill={filled ? "currentColor" : "none"} viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M11.049 2.927c.3-.921 1.603-.921 1.902 0l1.519 4.674a1 1 0 00.95.69h4.915c.969 0 1.371 1.24.588 1.81l-3.976 2.888a1 1 0 00-.363 1.118l1.518 4.674c.3.922-.755 1.688-1.538 1.118l-3.976-2.888a1 1 0 00-1.176 0l-3.976 2.888c-.783.57-1.838-.197-1.538-1.118l1.518-4.674a1 1 0 00-.363-1.118l-3.976-2.888c-.784-.57-.38-1.81.588-1.81h4.914a1 1 0 00.951-.69l1.519-4.674z" />
            </svg>
        );

        const CalculatorIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M9 7h6m0 10v-3m-3 3h.01M9 17h.01M9 14h.01M12 14h.01M15 11h.01M12 11h.01M9 11h.01M7 21h10a2 2 0 002-2V5a2 2 0 00-2-2H7a2 2 0 00-2 2v14a2 2 0 002 2z" />
            </svg>
        );

        const TrendingUpIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6" />
            </svg>
        );

        const FileTextIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
            </svg>
        );

        const MessageCircleIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z" />
            </svg>
        );

        const BarChart3Icon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
            </svg>
        );

        const WalletIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M3 10h18M7 15h1m4 0h1m-7 4h12a3 3 0 003-3V8a3 3 0 00-3-3H6a3 3 0 00-3 3v8a3 3 0 003 3z" />
            </svg>
        );

        const ArrowRightIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M17 8l4 4m0 0l-4 4m4-4H3" />
            </svg>
        );

        const ZapIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M13 10V3L4 14h7v7l9-11h-7z" />
            </svg>
        );

        const CrownIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M5 3l6 6 6-6v4l-6 6-6-6V3z" />
            </svg>
        );

        const LockIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z" />
            </svg>
        );

        const DownloadIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4" />
            </svg>
        );

        const XIcon = ({ className, onClick }) => (
            <svg className={`${className} transition-transform duration-300 cursor-pointer`} onClick={onClick} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M6 18L18 6M6 6l12 12" />
            </svg>
        );

        const CheckCircleIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
            </svg>
        );

        const LightbulbIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
            </svg>
        );

        const MenuIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M4 6h16M4 12h16M4 18h16" />
            </svg>
        );

        const UserIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
            </svg>
        );

        const LogOutIcon = ({ className }) => (
            <svg className={`${className} transition-transform duration-300`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M17 16l4-4m0 0l-4-4m4 4H7m6 4v1a3 3 0 01-3 3H6a3 3 0 01-3-3V7a3 3 0 013-3h4a3 3 0 013 3v1" />
            </svg>
        );

        const PlanificaSH = () => {
            // Estados principales de la aplicación
            const [currentSection, setCurrentSection] = useState('home');
            const [isPro, setIsPro] = useState(false);
            const [showUpgradeModal, setShowUpgradeModal] = useState(false);
            const [isLoggedIn, setIsLoggedIn] = useState(false);
            const [userName, setUserName] = useState('');
            const [showChatbot, setShowChatbot] = useState(false);
            const [activeToolId, setActiveToolId] = useState(null);
            const [isLoading, setIsLoading] = useState(false);
            const [showMobileMenu, setShowMobileMenu] = useState(false);

            // Estados para comentarios
            const [comments, setComments] = useState([
                { id: 1, name: 'María González', age: 24, city: 'Lima', rating: 5, text: 'Increíble plataforma! Logré ahorrar S/500 en mi primer mes usando las herramientas.' },
                { id: 2, name: 'Carlos Ruiz', age: 28, city: 'Arequipa', rating: 5, text: 'Las calculadoras me ayudaron mucho a optimizar los precios de mi negocio.' },
                { id: 3, name: 'Ana Pérez', age: 22, city: 'Cusco', rating: 4, text: 'Fácil de usar y muy útil para aprender finanzas. Lo recomiendo totalmente.' }
            ]);

            // Estados para chatbot
            const [newMessage, setNewMessage] = useState('');
            const [chatMessages, setChatMessages] = useState([
                { id: 1, text: '¡Hola! Soy Chanchi, tu asistente financiero. ¿En qué te puedo ayudar hoy?', sender: 'bot' }
            ]);

            // Plantillas disponibles
            const templates = [
                { 
                    id: 1, 
                    title: 'Gestión de Leads', 
                    description: 'Organiza y gestiona tus prospectos de manera eficiente. Realiza seguimiento de contactos, estado de conversión y optimiza tu embudo de ventas.',
                    category: 'Ventas y Marketing',
                    isPro: false,
                    size: '2.5 MB'
                },
                { 
                    id: 2, 
                    title: 'Flujo de Caja Emprendedor', 
                    description: 'Controla el flujo de efectivo de tu negocio. Monitorea ingresos, egresos y mantén una visibilidad clara de tu situación financiera.',
                    category: 'Finanzas Empresariales',
                    isPro: false,
                    size: '1.8 MB'
                },
                { 
                    id: 3, 
                    title: 'Finanzas Personales', 
                    description: 'Gestiona tus finanzas personales de manera profesional. Controla gastos, ingresos, ahorros e inversiones en un solo lugar.',
                    category: 'Finanzas Personales',
                    isPro: false,
                    size: '2.1 MB'
                },
                { 
                    id: 4, 
                    title: 'Punto de Equilibrio', 
                    description: 'Calcula el punto exacto donde tu negocio comienza a generar ganancias. Analiza costos fijos, variables y determina objetivos de ventas.',
                    category: 'Análisis Financiero',
                    isPro: true,
                    size: '3.2 MB'
                },
                { 
                    id: 5, 
                    title: 'Cálculo de Precio de Servicio', 
                    description: 'Define precios competitivos y rentables para tus servicios. Considera todos los costos y márgenes para maximizar tus ganancias.',
                    category: 'Pricing',
                    isPro: true,
                    size: '2.7 MB'
                },
                { 
                    id: 6, 
                    title: 'Cálculo de Precio de Producto', 
                    description: 'Establece precios óptimos para tus productos. Analiza costos de producción, distribución y define márgenes de ganancia adecuados.',
                    category: 'Pricing',
                    isPro: true,
                    size: '2.9 MB'
                },
                { 
                    id: 7, 
                    title: 'Control de Inventarios', 
                    description: 'Gestiona tu inventario eficientemente. Controla entradas, salidas, stock mínimo y evita pérdidas por falta o exceso de productos.',
                    category: 'Operaciones',
                    isPro: true,
                    size: '4.1 MB'
                }
            ];

            const handleStartFree = () => {
                setIsLoading(true);
                setTimeout(() => {
                    setIsLoading(false);
                    if (isLoggedIn) {
                        setCurrentSection('dashboard');
                    } else {
                        setCurrentSection('register');
                    }
                }, 1000);
            };

            // Función mejorada para mostrar notificaciones
            const showNotification = (message, isError = false, duration = 3000) => {
                const notification = document.createElement('div');
                notification.className = 'notification-enter';
                notification.style.cssText = `
                    position: fixed;
                    top: 90px;
                    right: 20px;
                    background: ${isError ? 'linear-gradient(135deg, #ef4444, #dc2626)' : 'linear-gradient(135deg, #8b5cf6, #ec4899)'};
                    color: white;
                    padding: 16px 24px;
                    border-radius: 16px;
                    box-shadow: 0 10px 40px rgba(139, 92, 246, 0.3);
                    border: 1px solid rgba(255, 255, 255, 0.2);
                    backdrop-filter: blur(20px);
                    z-index: 1000;
                    font-weight: 600;
                    max-width: 320px;
                    transform: translateX(100%);
                    opacity: 0;
                    transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
                `;
                
                const icon = document.createElement('div');
                icon.innerHTML = isError ? '❌' : '✅';
                icon.style.cssText = 'display: inline-block; margin-right: 8px; font-size: 16px;';
                
                const text = document.createElement('span');
                text.textContent = message;
                
                notification.appendChild(icon);
                notification.appendChild(text);
                document.body.appendChild(notification);
                
                // Trigger entrada
                setTimeout(() => {
                    notification.style.transform = 'translateX(0)';
                    notification.style.opacity = '1';
                }, 10);
                
                // Trigger salida
                setTimeout(() => {
                    notification.style.transform = 'translateX(100%)';
                    notification.style.opacity = '0';
                    setTimeout(() => {
                        if (document.body.contains(notification)) {
                            document.body.removeChild(notification);
                        }
                    }, 300);
                }, duration);
            };

            const handleTemplateClick = (template) => {
                if (template.isPro && !isPro) {
                    setShowUpgradeModal(true);
                    showNotification('Necesitas Plan Pro para acceder a esta plantilla', true);
                } else {
                    setIsLoading(true);
                    setTimeout(() => {
                        setIsLoading(false);
                        showNotification(`¡${template.title} descargado exitosamente! (${template.size})`);
                    }, 1500);
                }
            };

            const handleChatSubmit = () => {
                if (newMessage.trim()) {
                    const userMessage = { 
                        id: chatMessages.length + 1, 
                        text: newMessage, 
                        sender: 'user' 
                    };
                    
                    let botResponse = '';
                    const msg = newMessage.toLowerCase();
                    
                    if (msg.includes('hola') || msg.includes('hi') || msg.includes('hello')) {
                        botResponse = '¡Hola! 👋 Soy Chanchi, tu asistente financiero. Te puedo ayudar con dudas sobre finanzas, herramientas o Plan Pro. ¿Qué necesitas?';
                    } else if (msg.includes('plan pro') || msg.includes('premium') || msg.includes('pro')) {
                        botResponse = '💎 El Plan Pro incluye 7+ plantillas Excel premium, herramientas avanzadas de pricing y soporte prioritario por solo S/ 29/mes. ¿Te gustaría actualizar?';
                    } else if (msg.includes('herramientas') || msg.includes('calculadoras')) {
                        botResponse = '🛠️ Tenemos 5 herramientas poderosas: Calculadora de Precios, Planificador de Presupuesto, Control de Ingresos, Simulador de Ganancia y Estructura de Costos. ¡Todas gratuitas!';
                    } else if (msg.includes('precio') || msg.includes('precios')) {
                        botResponse = '💰 La Calculadora de Precios te ayuda a determinar el precio óptimo para tus productos considerando costos, margen deseado y precios de la competencia.';
                    } else if (msg.includes('plantillas') || msg.includes('excel')) {
                        const totalTemplates = templates.length;
                        const freeTemplates = templates.filter(t => !t.isPro).length;
                        const proTemplates = templates.filter(t => t.isPro).length;
                        
                        botResponse = `📊 Tenemos ${totalTemplates} plantillas profesionales: ${freeTemplates} gratuitas (Leads, Flujo de Caja, Finanzas Personales) y ${proTemplates} premium (Pricing, Inventarios, Punto de Equilibrio). ${isPro ? '¡Tienes acceso completo! 🎉' : 'Actualiza a Pro para todas.'}`;
                    } else if (msg.includes('ayuda') || msg.includes('help') || msg.includes('soporte')) {
                        botResponse = '🤝 Te puedo ayudar con: calculadoras financieras, análisis de precios, presupuestos, información sobre Plan Pro, plantillas Excel y consejos de emprendimiento.';
                    } else if (msg.includes('costo') || msg.includes('gratis') || msg.includes('dinero')) {
                        botResponse = '💸 PlanificaSH es completamente GRATIS. Acceso a 5 herramientas y 3 plantillas sin costo. Plan Pro: S/29/mes para funciones avanzadas.';
                    } else if (msg.includes('emprendimiento') || msg.includes('negocio') || msg.includes('empresa')) {
                        botResponse = '🚀 ¡Perfecto! Nuestras herramientas están diseñadas para emprendedores. Te ayudamos con precios, presupuestos, flujo de caja y control de costos.';
                    } else {
                        const responses = [
                            '🤔 Interesante pregunta. Te puedo ayudar con herramientas financieras, Plan Pro, plantillas Excel y más. ¿Qué necesitas específicamente?',
                            '💡 Te puedo orientar con: calculadoras de precios, presupuestos, análisis de costos, plantillas y estrategias financieras. ¿Por dónde empezamos?',
                            '✨ Estoy aquí para ayudarte con tus finanzas. Pregúntame sobre nuestras herramientas, plantillas o Plan Pro.'
                        ];
                        botResponse = responses[Math.floor(Math.random() * responses.length)];
                    }
                    
                    const botMessage = { 
                        id: chatMessages.length + 2, 
                        text: botResponse, 
                        sender: 'bot' 
                    };
                    
                    setChatMessages([...chatMessages, userMessage, botMessage]);
                    setNewMessage('');
                }
            };

            const renderStars = (rating, interactive = false, onRate = null) => {
                return Array.from({ length: 5 }, (_, i) => (
                    <StarIcon
                        key={i}
                        className={`w-5 h-5 transition-all duration-200 ${i < rating ? 'text-yellow-400' : 'text-gray-300'} ${interactive ? 'cursor-pointer hover:text-yellow-400 hover:scale-110' : ''}`}
                        onClick={() => interactive && onRate && onRate(i + 1)}
                        filled={i < rating}
                    />
                ));
            };

            const handleLogin = (e) => {
                e.preventDefault();
                const email = e.target.email.value;
                const name = email.split('@')[0];
                setUserName(name);
                setIsLoggedIn(true);
                setCurrentSection('dashboard');
                setActiveToolId(null);
                showNotification(`¡Bienvenido ${name}!`);
            };

            const handleLogout = () => {
                setIsLoggedIn(false);
                setUserName('');
                setIsPro(false);
                setCurrentSection('home');
                showNotification('Has cerrado sesión correctamente');
            };

            // Herramientas como componentes individuales
            const PriceCalculatorTool = () => {
                const [cost, setCost] = useState('');
                const [margin, setMargin] = useState('');
                const [competition, setCompetition] = useState('');
                const [result, setResult] = useState(null);
                const [calculating, setCalculating] = useState(false);

                const calculatePrice = () => {
                    setCalculating(true);
                    setTimeout(() => {
                        const costValue = parseFloat(cost) || 0;
                        const marginValue = parseFloat(margin) || 0;
                        const competitionValue = parseFloat(competition) || 0;
                        
                        const priceWithMargin = costValue * (1 + marginValue / 100);
                        const recommendedPrice = competitionValue > 0 ? (priceWithMargin + competitionValue) / 2 : priceWithMargin;
                        const profit = recommendedPrice - costValue;
                        const profitMargin = costValue > 0 ? ((profit / costValue) * 100) : 0;
                        
                        setResult({
                            recommendedPrice: recommendedPrice.toFixed(2),
                            profit: profit.toFixed(2),
                            profitMargin: profitMargin.toFixed(1),
                            competitiveAnalysis: competitionValue > 0 ? (recommendedPrice < competitionValue ? 'Competitivo' : 'Alto') : 'Sin referencia'
                        });
                        setCalculating(false);
                        showNotification('¡Precio calculado exitosamente!');
                    }, 800);
                };

                return (
                    <div className="glass-card rounded-3xl p-8 animate-fadeInUp">
                        <div className="flex items-center mb-6">
                            <div className="w-12 h-12 bg-gradient-to-r from-indigo-500 to-purple-500 rounded-2xl flex items-center justify-center mr-4">
                                <CalculatorIcon className="w-6 h-6 text-white" />
                            </div>
                            <div>
                                <h2 className="text-2xl font-bold text-white">Calculadora de Precios</h2>
                                <p className="text-gray-400">Determina el precio óptimo para tus productos</p>
                            </div>
                        </div>
                        
                        <div className="grid md:grid-cols-2 gap-8">
                            <div className="space-y-6">
                                <h3 className="text-lg font-semibold text-white mb-4">Datos del producto</h3>
                                
                                <div className="space-y-4">
                                    <div>
                                        <label className="block text-white font-semibold mb-2">Costo de producción (S/)</label>
                                        <input
                                            type="number"
                                            value={cost}
                                            onChange={(e) => setCost(e.target.value)}
                                            placeholder="50.00"
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500 transition-all"
                                        />
                                    </div>
                                    
                                    <div>
                                        <label className="block text-white font-semibold mb-2">Margen deseado (%)</label>
                                        <input
                                            type="number"
                                            value={margin}
                                            onChange={(e) => setMargin(e.target.value)}
                                            placeholder="40"
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500 transition-all"
                                        />
                                    </div>
                                    
                                    <div>
                                        <label className="block text-white font-semibold mb-2">Precio competencia (S/) - Opcional</label>
                                        <input
                                            type="number"
                                            value={competition}
                                            onChange={(e) => setCompetition(e.target.value)}
                                            placeholder="80.00"
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500 transition-all"
                                        />
                                    </div>
                                    
                                    <button
                                        onClick={calculatePrice}
                                        disabled={calculating}
                                        className="w-full py-4 gradient-button text-white rounded-xl font-semibold button-hover-effect disabled:opacity-50"
                                    >
                                        {calculating ? (
                                            <div className="flex items-center justify-center">
                                                <div className="animate-spin rounded-full h-5 w-5 border-b-2 border-white mr-2"></div>
                                                Calculando...
                                            </div>
                                        ) : (
                                            'Calcular precio'
                                        )}
                                    </button>
                                </div>
                            </div>

                            <div className="flex items-center justify-center">
                                {result ? (
                                    <div className="w-full space-y-4 animate-fadeInUp">
                                        <div className="text-center p-6 bg-gradient-to-r from-indigo-600/20 to-purple-600/20 rounded-2xl border border-indigo-500/30">
                                            <div className="text-4xl font-bold text-white mb-2">S/ {result.recommendedPrice}</div>
                                            <p className="text-indigo-400 font-semibold">Precio recomendado</p>
                                        </div>
                                        
                                        <div className="grid grid-cols-2 gap-4">
                                            <div className="p-4 glass-effect rounded-xl text-center button-hover-effect">
                                                <div className="text-xl font-bold text-green-400">S/ {result.profit}</div>
                                                <p className="text-gray-400 text-sm">Ganancia</p>
                                            </div>
                                            <div className="p-4 glass-effect rounded-xl text-center button-hover-effect">
                                                <div className="text-xl font-bold text-blue-400">{result.profitMargin}%</div>
                                                <p className="text-gray-400 text-sm">Margen real</p>
                                            </div>
                                        </div>
                                        
                                        <div className="p-4 glass-effect rounded-xl">
                                            <h4 className="text-white font-semibold mb-2">Análisis competitivo:</h4>
                                            <p className="text-gray-300 text-sm">{result.competitiveAnalysis}</p>
                                        </div>
                                    </div>
                                ) : (
                                    <div className="text-center p-8 glass-effect rounded-2xl">
                                        <CalculatorIcon className="w-16 h-16 text-gray-400 mx-auto mb-4 floating-animation" />
                                        <p className="text-gray-400">Ingresa los datos para calcular</p>
                                    </div>
                                )}
                            </div>
                        </div>
                    </div>
                );
            };

            const BudgetPlannerTool = () => {
                const [income, setIncome] = useState('');
                const [housing, setHousing] = useState('');
                const [transportation, setTransportation] = useState('');
                const [food, setFood] = useState('');
                const [utilities, setUtilities] = useState('');
                const [entertainment, setEntertainment] = useState('');
                const [savings, setSavings] = useState('');
                const [analysis, setAnalysis] = useState(null);
                const [analyzing, setAnalyzing] = useState(false);

                const calculateBudget = () => {
                    setAnalyzing(true);
                    setTimeout(() => {
                        const incomeValue = parseFloat(income) || 0;
                        const housingValue = parseFloat(housing) || 0;
                        const transportationValue = parseFloat(transportation) || 0;
                        const foodValue = parseFloat(food) || 0;
                        const utilitiesValue = parseFloat(utilities) || 0;
                        const entertainmentValue = parseFloat(entertainment) || 0;
                        const savingsValue = parseFloat(savings) || 0;
                        
                        const totalExpenses = housingValue + transportationValue + foodValue + utilitiesValue + entertainmentValue + savingsValue;
                        const remaining = incomeValue - totalExpenses;
                        const expenseRatio = incomeValue > 0 ? (totalExpenses / incomeValue) * 100 : 0;
                        
                        setAnalysis({
                            income: incomeValue,
                            totalExpenses,
                            remaining,
                            expenseRatio,
                            status: remaining > 0 ? 'positive' : remaining < 0 ? 'negative' : 'neutral'
                        });
                        setAnalyzing(false);
                        showNotification('¡Presupuesto analizado exitosamente!');
                    }, 1000);
                };

                return (
                    <div className="glass-card rounded-3xl p-8 animate-fadeInUp">
                        <div className="flex items-center mb-6">
                            <div className="w-12 h-12 bg-gradient-to-r from-emerald-500 to-teal-500 rounded-2xl flex items-center justify-center mr-4">
                                <BarChart3Icon className="w-6 h-6 text-white" />
                            </div>
                            <div>
                                <h2 className="text-2xl font-bold text-white">Planificador de Presupuesto</h2>
                                <p className="text-gray-400">Organiza tus ingresos y gastos mensuales</p>
                            </div>
                        </div>
                        
                        <div className="grid md:grid-cols-2 gap-8">
                            <div className="space-y-6">
                                <h3 className="text-lg font-semibold text-white mb-4">Datos mensuales</h3>
                                <div className="space-y-4">
                                    <div>
                                        <label className="block text-white font-semibold mb-2">💰 Ingresos (S/)</label>
                                        <input
                                            type="number"
                                            value={income}
                                            onChange={(e) => setIncome(e.target.value)}
                                            placeholder="3000"
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-emerald-500 transition-all"
                                        />
                                    </div>
                                    
                                    <div className="grid grid-cols-2 gap-4">
                                        <div>
                                            <label className="block text-white font-semibold mb-2">🏠 Vivienda</label>
                                            <input
                                                type="number"
                                                value={housing}
                                                onChange={(e) => setHousing(e.target.value)}
                                                placeholder="900"
                                                className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-emerald-500 transition-all"
                                            />
                                        </div>
                                        <div>
                                            <label className="block text-white font-semibold mb-2">🚗 Transporte</label>
                                            <input
                                                type="number"
                                                value={transportation}
                                                onChange={(e) => setTransportation(e.target.value)}
                                                placeholder="300"
                                                className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-emerald-500 transition-all"
                                            />
                                        </div>
                                    </div>

                                    <div className="grid grid-cols-2 gap-4">
                                        <div>
                                            <label className="block text-white font-semibold mb-2">🍽️ Comida</label>
                                            <input
                                                type="number"
                                                value={food}
                                                onChange={(e) => setFood(e.target.value)}
                                                placeholder="400"
                                                className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-emerald-500 transition-all"
                                            />
                                        </div>
                                        <div>
                                            <label className="block text-white font-semibold mb-2">⚡ Servicios</label>
                                            <input
                                                type="number"
                                                value={utilities}
                                                onChange={(e) => setUtilities(e.target.value)}
                                                placeholder="200"
                                                className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-emerald-500 transition-all"
                                            />
                                        </div>
                                    </div>

                                    <div className="grid grid-cols-2 gap-4">
                                        <div>
                                            <label className="block text-white font-semibold mb-2">🎮 Entretenimiento</label>
                                            <input
                                                type="number"
                                                value={entertainment}
                                                onChange={(e) => setEntertainment(e.target.value)}
                                                placeholder="150"
                                                className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-emerald-500 transition-all"
                                            />
                                        </div>
                                        <div>
                                            <label className="block text-white font-semibold mb-2">💾 Ahorros</label>
                                            <input
                                                type="number"
                                                value={savings}
                                                onChange={(e) => setSavings(e.target.value)}
                                                placeholder="600"
                                                className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-emerald-500 transition-all"
                                            />
                                        </div>
                                    </div>
                                    
                                    <button
                                        onClick={calculateBudget}
                                        disabled={analyzing}
                                        className="w-full py-4 bg-gradient-to-r from-emerald-600 to-teal-600 text-white rounded-xl font-semibold button-hover-effect disabled:opacity-50"
                                    >
                                        {analyzing ? (
                                            <div className="flex items-center justify-center">
                                                <div className="animate-spin rounded-full h-5 w-5 border-b-2 border-white mr-2"></div>
                                                Analizando...
                                            </div>
                                        ) : (
                                            'Analizar presupuesto'
                                        )}
                                    </button>
                                </div>
                            </div>

                            {analysis ? (
                                <div className="animate-fadeInUp">
                                    <h3 className="text-lg font-semibold text-white mb-4">Análisis financiero</h3>
                                    
                                    <div className={`p-6 rounded-xl mb-6 ${
                                        analysis.status === 'positive' ? 'bg-green-500/20 border border-green-500/30' :
                                        analysis.status === 'negative' ? 'bg-red-500/20 border border-red-500/30' :
                                        'bg-yellow-500/20 border border-yellow-500/30'
                                    }`}>
                                        <div className="text-center">
                                            <div className="text-4xl font-bold text-white mb-2">
                                                S/ {Math.abs(analysis.remaining).toFixed(2)}
                                            </div>
                                            <p className={`font-semibold ${
                                                analysis.status === 'positive' ? 'text-green-400' :
                                                analysis.status === 'negative' ? 'text-red-400' :
                                                'text-yellow-400'
                                            }`}>
                                                {analysis.status === 'positive' ? '✅ Excedente' :
                                                 analysis.status === 'negative' ? '⚠️ Déficit' :
                                                 '⚖️ Equilibrado'}
                                            </p>
                                        </div>
                                    </div>

                                    <div className="space-y-4">
                                        <div className="p-4 glass-effect rounded-xl">
                                            <div className="flex justify-between text-white mb-2">
                                                <span>💰 Ingresos:</span>
                                                <span className="font-bold">S/ {analysis.income.toFixed(2)}</span>
                                            </div>
                                            <div className="flex justify-between text-white mb-2">
                                                <span>💸 Gastos:</span>
                                                <span className="font-bold">S/ {analysis.totalExpenses.toFixed(2)}</span>
                                            </div>
                                            <div className="flex justify-between text-white">
                                                <span>📊 % gastado:</span>
                                                <span className="font-bold">{analysis.expenseRatio.toFixed(1)}%</span>
                                            </div>
                                        </div>

                                        {analysis.status === 'negative' && (
                                            <div className="p-4 bg-red-500/20 border border-red-500/30 rounded-xl">
                                                <h5 className="text-red-400 font-semibold mb-2">🚨 Necesitas ajustes:</h5>
                                                <ul className="text-red-300 text-sm space-y-1">
                                                    <li>• Reduce gastos no esenciales</li>
                                                    <li>• Busca ingresos adicionales</li>
                                                    <li>• Revisa entretenimiento y otros gastos</li>
                                                </ul>
                                            </div>
                                        )}

                                        {analysis.status === 'positive' && (
                                            <div className="p-4 bg-green-500/20 border border-green-500/30 rounded-xl">
                                                <h5 className="text-green-400 font-semibold mb-2">🎉 ¡Excelente control!</h5>
                                                <ul className="text-green-300 text-sm space-y-1">
                                                    <li>• Considera invertir el excedente</li>
                                                    <li>• Aumenta tu fondo de emergencia</li>
                                                    <li>• Explora oportunidades de inversión</li>
                                                </ul>
                                            </div>
                                        )}
                                    </div>
                                </div>
                            ) : (
                                <div className="flex items-center justify-center">
                                    <div className="text-center p-8 glass-effect rounded-2xl">
                                        <BarChart3Icon className="w-16 h-16 text-gray-400 mx-auto mb-4 floating-animation" />
                                        <p className="text-gray-400">Completa los datos para analizar</p>
                                    </div>
                                </div>
                            )}
                        </div>
                    </div>
                );
            };

            const IncomeExpensesTool = () => {
                const [transactions, setTransactions] = useState([]);
                const [type, setType] = useState('income');
                const [category, setCategory] = useState('');
                const [amount, setAmount] = useState('');
                const [description, setDescription] = useState('');

                const addTransaction = () => {
                    if (category && amount && description) {
                        const transaction = {
                            id: Date.now(),
                            type: type,
                            category: category,
                            amount: parseFloat(amount),
                            description: description,
                            date: new Date().toISOString().split('T')[0]
                        };
                        
                        setTransactions([transaction, ...transactions]);
                        setCategory('');
                        setAmount('');
                        setDescription('');
                        showNotification('¡Transacción agregada exitosamente!');
                    } else {
                        showNotification('Por favor completa todos los campos', true);
                    }
                };

                const deleteTransaction = (id) => {
                    setTransactions(transactions.filter(t => t.id !== id));
                    showNotification('Transacción eliminada');
                };

                return (
                    <div className="glass-card rounded-3xl p-8 animate-fadeInUp">
                        <div className="flex items-center mb-6">
                            <div className="w-12 h-12 bg-gradient-to-r from-blue-500 to-cyan-500 rounded-2xl flex items-center justify-center mr-4">
                                <WalletIcon className="w-6 h-6 text-white" />
                            </div>
                            <div>
                                <h2 className="text-2xl font-bold text-white">Control de Ingresos y Gastos</h2>
                                <p className="text-gray-400">Registra y controla cada movimiento de dinero</p>
                            </div>
                        </div>
                        
                        <div className="grid md:grid-cols-2 gap-8">
                            <div className="space-y-6">
                                <h3 className="text-lg font-semibold text-white mb-4">Nueva transacción</h3>
                                <div className="space-y-4">
                                    <div>
                                        <label className="block text-white font-semibold mb-2">Tipo</label>
                                        <select
                                            value={type}
                                            onChange={(e) => setType(e.target.value)}
                                            className="w-full p-4 glass-effect rounded-xl text-white focus:outline-none focus:ring-2 focus:ring-blue-500 transition-all"
                                        >
                                            <option value="income" className="bg-gray-800">💰 Ingreso</option>
                                            <option value="expense" className="bg-gray-800">💸 Gasto</option>
                                        </select>
                                    </div>
                                    
                                    <div>
                                        <label className="block text-white font-semibold mb-2">Categoría</label>
                                        <input
                                            type="text"
                                            value={category}
                                            onChange={(e) => setCategory(e.target.value)}
                                            placeholder="Ventas, Comida, Transporte..."
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-blue-500 transition-all"
                                        />
                                    </div>
                                    
                                    <div>
                                        <label className="block text-white font-semibold mb-2">Monto (S/)</label>
                                        <input
                                            type="number"
                                            value={amount}
                                            onChange={(e) => setAmount(e.target.value)}
                                            placeholder="100.00"
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-blue-500 transition-all"
                                        />
                                    </div>
                                    
                                    <div>
                                        <label className="block text-white font-semibold mb-2">Descripción</label>
                                        <input
                                            type="text"
                                            value={description}
                                            onChange={(e) => setDescription(e.target.value)}
                                            placeholder="Detalle de la transacción"
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-blue-500 transition-all"
                                        />
                                    </div>
                                    
                                    <button
                                        onClick={addTransaction}
                                        className="w-full py-4 bg-gradient-to-r from-blue-600 to-cyan-600 text-white rounded-xl font-semibold button-hover-effect"
                                    >
                                        Agregar transacción
                                    </button>
                                </div>
                            </div>

                            <div>
                                <h3 className="text-lg font-semibold text-white mb-4">Historial reciente</h3>
                                
                                <div className="space-y-3 max-h-96 overflow-y-auto">
                                    {transactions.length > 0 ? (
                                        transactions.map((transaction) => (
                                            <div key={transaction.id} className="p-4 glass-effect rounded-xl button-hover-effect">
                                                <div className="flex justify-between items-start mb-2">
                                                    <div className="flex-1">
                                                        <div className="flex items-center mb-1">
                                                            <span className={`px-3 py-1 rounded-full text-xs font-semibold mr-3 ${
                                                                transaction.type === 'income' ? 'bg-green-500/20 text-green-400' : 'bg-red-500/20 text-red-400'
                                                            }`}>
                                                                {transaction.type === 'income' ? '💰 Ingreso' : '💸 Gasto'}
                                                            </span>
                                                            <span className="text-white font-semibold">{transaction.category}</span>
                                                        </div>
                                                        <p className="text-gray-300 text-sm">{transaction.description}</p>
                                                        <p className="text-gray-400 text-xs mt-1">{transaction.date}</p>
                                                    </div>
                                                    <div className="text-right ml-4">
                                                        <div className={`text-lg font-bold ${
                                                            transaction.type === 'income' ? 'text-green-400' : 'text-red-400'
                                                        }`}>
                                                            {transaction.type === 'income' ? '+' : '-'}S/ {transaction.amount.toFixed(2)}
                                                        </div>
                                                        <button
                                                            onClick={() => deleteTransaction(transaction.id)}
                                                            className="text-red-400 hover:text-red-300 text-xs mt-1 opacity-70 hover:opacity-100 transition-opacity"
                                                        >
                                                            Eliminar
                                                        </button>
                                                    </div>
                                                </div>
                                            </div>
                                        ))
                                    ) : (
                                        <div className="text-center p-8 glass-effect rounded-2xl">
                                            <WalletIcon className="w-16 h-16 text-gray-400 mx-auto mb-4 floating-animation" />
                                            <p className="text-gray-400">No hay transacciones aún</p>
                                            <p className="text-gray-500 text-sm mt-2">Agrega tu primera transacción</p>
                                        </div>
                                    )}
                                </div>

                                {transactions.length > 0 && (
                                    <div className="mt-6 p-6 bg-gradient-to-r from-blue-600/20 to-cyan-600/20 rounded-xl border border-blue-500/30">
                                        <h4 className="text-white font-semibold mb-4">📊 Resumen financiero</h4>
                                        <div className="grid grid-cols-2 gap-4">
                                            <div className="text-center p-4 glass-effect rounded-xl">
                                                <div className="text-xl font-bold text-green-400">
                                                    +S/ {transactions
                                                        .filter(t => t.type === 'income')
                                                        .reduce((sum, t) => sum + t.amount, 0)
                                                        .toFixed(2)}
                                                </div>
                                                <p className="text-gray-300 text-sm">Total Ingresos</p>
                                            </div>
                                            <div className="text-center p-4 glass-effect rounded-xl">
                                                <div className="text-xl font-bold text-red-400">
                                                    -S/ {transactions
                                                        .filter(t => t.type === 'expense')
                                                        .reduce((sum, t) => sum + t.amount, 0)
                                                        .toFixed(2)}
                                                </div>
                                                <p className="text-gray-300 text-sm">Total Gastos</p>
                                            </div>
                                        </div>
                                        <div className="mt-4 text-center p-3 glass-effect rounded-lg">
                                            <div className="text-lg font-bold text-white">
                                                Balance: S/ {(transactions
                                                    .filter(t => t.type === 'income')
                                                    .reduce((sum, t) => sum + t.amount, 0) -
                                                transactions
                                                    .filter(t => t.type === 'expense')
                                                    .reduce((sum, t) => sum + t.amount, 0)
                                                ).toFixed(2)}
                                            </div>
                                        </div>
                                    </div>
                                )}
                            </div>
                        </div>
                    </div>
                );
            };

            const ProfitSimulatorTool = () => {
                const [salesPrice, setSalesPrice] = useState('');
                const [unitCost, setUnitCost] = useState('');
                const [fixedCosts, setFixedCosts] = useState('');
                const [unitsToSell, setUnitsToSell] = useState('');
                const [result, setResult] = useState(null);
                const [simulating, setSimulating] = useState(false);

                const calculateProfit = () => {
                    setSimulating(true);
                    setTimeout(() => {
                        const salesPriceValue = parseFloat(salesPrice) || 0;
                        const unitCostValue = parseFloat(unitCost) || 0;
                        const fixedCostsValue = parseFloat(fixedCosts) || 0;
                        const unitsToSellValue = parseFloat(unitsToSell) || 0;
                        
                        const unitProfit = salesPriceValue - unitCostValue;
                        const totalRevenue = salesPriceValue * unitsToSellValue;
                        const totalVariableCosts = unitCostValue * unitsToSellValue;
                        const netProfit = totalRevenue - totalVariableCosts - fixedCostsValue;
                        const profitMargin = totalRevenue > 0 ? ((netProfit / totalRevenue) * 100) : 0;
                        const breakEvenUnits = unitProfit > 0 ? Math.ceil(fixedCostsValue / unitProfit) : 0;
                        
                        setResult({
                            unitProfit: unitProfit.toFixed(2),
                            totalRevenue: totalRevenue.toFixed(2),
                            netProfit: netProfit.toFixed(2),
                            profitMargin: profitMargin.toFixed(1),
                            breakEvenUnits: breakEvenUnits,
                            unitsToSell: unitsToSellValue,
                            isProfit: netProfit > 0
                        });
                        setSimulating(false);
                        showNotification('¡Simulación completada exitosamente!');
                    }, 1200);
                };

                return (
                    <div className="glass-card rounded-3xl p-8 animate-fadeInUp">
                        <div className="flex items-center mb-6">
                            <div className="w-12 h-12 bg-gradient-to-r from-green-500 to-emerald-500 rounded-2xl flex items-center justify-center mr-4">
                                <TrendingUpIcon className="w-6 h-6 text-white" />
                            </div>
                            <div>
                                <h2 className="text-2xl font-bold text-white">Simulador de Ganancia</h2>
                                <p className="text-gray-400">Calcula tus ganancias proyectadas y punto de equilibrio</p>
                            </div>
                        </div>
                        
                        <div className="grid md:grid-cols-2 gap-8">
                            <div className="space-y-6">
                                <h3 className="text-lg font-semibold text-white mb-4">Datos del negocio</h3>
                                <div className="space-y-4">
                                    <div>
                                        <label className="block text-white font-semibold mb-2">💰 Precio de venta por unidad (S/)</label>
                                        <input
                                            type="number"
                                            value={salesPrice}
                                            onChange={(e) => setSalesPrice(e.target.value)}
                                            placeholder="25.00"
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-green-500 transition-all"
                                        />
                                    </div>
                                    
                                    <div>
                                        <label className="block text-white font-semibold mb-2">📦 Costo variable por unidad (S/)</label>
                                        <input
                                            type="number"
                                            value={unitCost}
                                            onChange={(e) => setUnitCost(e.target.value)}
                                            placeholder="10.00"
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-green-500 transition-all"
                                        />
                                    </div>
                                    
                                    <div>
                                        <label className="block text-white font-semibold mb-2">🏢 Costos fijos mensuales (S/)</label>
                                        <input
                                            type="number"
                                            value={fixedCosts}
                                            onChange={(e) => setFixedCosts(e.target.value)}
                                            placeholder="2000.00"
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-green-500 transition-all"
                                        />
                                    </div>
                                    
                                    <div>
                                        <label className="block text-white font-semibold mb-2">🎯 Unidades a vender</label>
                                        <input
                                            type="number"
                                            value={unitsToSell}
                                            onChange={(e) => setUnitsToSell(e.target.value)}
                                            placeholder="200"
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-green-500 transition-all"
                                        />
                                    </div>
                                    
                                    <button
                                        onClick={calculateProfit}
                                        disabled={simulating}
                                        className="w-full py-4 bg-gradient-to-r from-green-600 to-emerald-600 text-white rounded-xl font-semibold button-hover-effect disabled:opacity-50"
                                    >
                                        {simulating ? (
                                            <div className="flex items-center justify-center">
                                                <div className="animate-spin rounded-full h-5 w-5 border-b-2 border-white mr-2"></div>
                                                Simulando...
                                            </div>
                                        ) : (
                                            'Simular ganancias'
                                        )}
                                    </button>
                                </div>
                            </div>

                            <div className="flex items-center justify-center">
                                {result ? (
                                    <div className="w-full space-y-4 animate-fadeInUp">
                                        <div className={`text-center p-6 rounded-2xl border ${
                                            result.isProfit 
                                                ? 'bg-gradient-to-r from-green-600/20 to-emerald-600/20 border-green-500/30' 
                                                : 'bg-gradient-to-r from-red-600/20 to-pink-600/20 border-red-500/30'
                                        }`}>
                                            <div className="text-4xl font-bold text-white mb-2">
                                                {result.isProfit ? '🎉' : '⚠️'} S/ {result.netProfit}
                                            </div>
                                            <p className={`font-semibold ${result.isProfit ? 'text-green-400' : 'text-red-400'}`}>
                                                {result.isProfit ? 'Ganancia neta proyectada' : 'Pérdida proyectada'}
                                            </p>
                                        </div>
                                        
                                        <div className="grid grid-cols-2 gap-4">
                                            <div className="p-4 glass-effect rounded-xl text-center button-hover-effect">
                                                <div className="text-xl font-bold text-blue-400">S/ {result.totalRevenue}</div>
                                                <p className="text-gray-400 text-sm">Ingresos totales</p>
                                            </div>
                                            <div className="p-4 glass-effect rounded-xl text-center button-hover-effect">
                                                <div className="text-xl font-bold text-purple-400">{result.profitMargin}%</div>
                                                <p className="text-gray-400 text-sm">Margen de ganancia</p>
                                            </div>
                                        </div>
                                        
                                        <div className="grid grid-cols-2 gap-4">
                                            <div className="p-4 glass-effect rounded-xl text-center button-hover-effect">
                                                <div className="text-xl font-bold text-green-400">S/ {result.unitProfit}</div>
                                                <p className="text-gray-400 text-sm">Ganancia por unidad</p>
                                            </div>
                                            <div className="p-4 glass-effect rounded-xl text-center button-hover-effect">
                                                <div className="text-xl font-bold text-orange-400">{result.breakEvenUnits}</div>
                                                <p className="text-gray-400 text-sm">Punto de equilibrio</p>
                                            </div>
                                        </div>
                                        
                                        <div className="p-4 bg-blue-500/20 border border-blue-500/30 rounded-xl">
                                            <h4 className="text-blue-400 font-semibold mb-2">📈 Análisis:</h4>
                                            <p className="text-gray-300 text-sm">
                                                Necesitas vender {result.breakEvenUnits} unidades para cubrir tus costos fijos.
                                                {result.breakEvenUnits < result.unitsToSell 
                                                    ? ' 🎯 Tu meta de ventas generará ganancias.' 
                                                    : ' 💡 Considera aumentar ventas o reducir costos.'}
                                            </p>
                                        </div>
                                    </div>
                                ) : (
                                    <div className="text-center p-8 glass-effect rounded-2xl">
                                        <TrendingUpIcon className="w-16 h-16 text-gray-400 mx-auto mb-4 floating-animation" />
                                        <p className="text-gray-400">Ingresa los datos para simular</p>
                                        <p className="text-gray-500 text-sm mt-2">Proyecta tus ganancias futuras</p>
                                    </div>
                                )}
                            </div>
                        </div>
                    </div>
                );
            };

            const CostStructureTool = () => {
                const [directCosts, setDirectCosts] = useState([]);
                const [indirectCosts, setIndirectCosts] = useState([]);
                const [type, setType] = useState('direct');
                const [description, setDescription] = useState('');
                const [amount, setAmount] = useState('');
                const [result, setResult] = useState(null);

                const addCost = () => {
                    if (description && amount) {
                        const cost = {
                            id: Date.now(),
                            description: description,
                            amount: parseFloat(amount)
                        };
                        
                        if (type === 'direct') {
                            setDirectCosts([...directCosts, cost]);
                        } else {
                            setIndirectCosts([...indirectCosts, cost]);
                        }
                        
                        setDescription('');
                        setAmount('');
                        showNotification('¡Costo agregado exitosamente!');
                    } else {
                        showNotification('Por favor completa todos los campos', true);
                    }
                };

                const deleteCost = (id, costType) => {
                    if (costType === 'direct') {
                        setDirectCosts(directCosts.filter(cost => cost.id !== id));
                    } else {
                        setIndirectCosts(indirectCosts.filter(cost => cost.id !== id));
                    }
                    showNotification('Costo eliminado');
                };

                const calculateCostStructure = () => {
                    const totalDirectCosts = directCosts.reduce((sum, cost) => sum + cost.amount, 0);
                    const totalIndirectCosts = indirectCosts.reduce((sum, cost) => sum + cost.amount, 0);
                    const totalCosts = totalDirectCosts + totalIndirectCosts;
                    
                    setResult({
                        totalDirectCosts: totalDirectCosts.toFixed(2),
                        totalIndirectCosts: totalIndirectCosts.toFixed(2),
                        totalCosts: totalCosts.toFixed(2),
                        directPercentage: totalCosts > 0 ? ((totalDirectCosts / totalCosts) * 100).toFixed(1) : 0,
                        indirectPercentage: totalCosts > 0 ? ((totalIndirectCosts / totalCosts) * 100).toFixed(1) : 0
                    });
                    showNotification('¡Estructura de costos calculada!');
                };

                return (
                    <div className="glass-card rounded-3xl p-8 animate-fadeInUp">
                        <div className="flex items-center mb-6">
                            <div className="w-12 h-12 bg-gradient-to-r from-rose-500 to-pink-500 rounded-2xl flex items-center justify-center mr-4">
                                <FileTextIcon className="w-6 h-6 text-white" />
                            </div>
                            <div>
                                <h2 className="text-2xl font-bold text-white">Estructura de Costos</h2>
                                <p className="text-gray-400">Organiza y analiza todos tus costos empresariales</p>
                            </div>
                        </div>
                        
                        <div className="grid md:grid-cols-2 gap-8">
                            <div className="space-y-6">
                                <h3 className="text-lg font-semibold text-white mb-4">Agregar costo</h3>
                                <div className="space-y-4">
                                    <div>
                                        <label className="block text-white font-semibold mb-2">Tipo de costo</label>
                                        <select
                                            value={type}
                                            onChange={(e) => setType(e.target.value)}
                                            className="w-full p-4 glass-effect rounded-xl text-white focus:outline-none focus:ring-2 focus:ring-rose-500 transition-all"
                                        >
                                            <option value="direct" className="bg-gray-800">🎯 Costo directo</option>
                                            <option value="indirect" className="bg-gray-800">🏢 Costo indirecto</option>
                                        </select>
                                    </div>
                                    
                                    <div>
                                        <label className="block text-white font-semibold mb-2">Descripción</label>
                                        <input
                                            type="text"
                                            value={description}
                                            onChange={(e) => setDescription(e.target.value)}
                                            placeholder="Materia prima, Alquiler, etc."
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-rose-500 transition-all"
                                        />
                                    </div>
                                    
                                    <div>
                                        <label className="block text-white font-semibold mb-2">Monto (S/)</label>
                                        <input
                                            type="number"
                                            value={amount}
                                            onChange={(e) => setAmount(e.target.value)}
                                            placeholder="500.00"
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-rose-500 transition-all"
                                        />
                                    </div>
                                    
                                    <button
                                        onClick={addCost}
                                        className="w-full py-4 bg-gradient-to-r from-rose-600 to-pink-600 text-white rounded-xl font-semibold button-hover-effect"
                                    >
                                        Agregar costo
                                    </button>

                                    {(directCosts.length > 0 || indirectCosts.length > 0) && (
                                        <button
                                            onClick={calculateCostStructure}
                                            className="w-full py-4 bg-gradient-to-r from-purple-600 to-cyan-600 text-white rounded-xl font-semibold button-hover-effect"
                                        >
                                            Calcular estructura
                                        </button>
                                    )}
                                </div>
                            </div>

                            <div>
                                <h3 className="text-lg font-semibold text-white mb-4">Estructura de costos</h3>
                                
                                <div className="space-y-4">
                                    <div className="p-4 glass-effect rounded-xl">
                                        <div className="flex justify-between items-center mb-3">
                                            <h4 className="text-white font-semibold">🎯 Costos Directos</h4>
                                            <span className="text-green-400 font-bold">
                                                S/ {directCosts.reduce((sum, cost) => sum + cost.amount, 0).toFixed(2)}
                                            </span>
                                        </div>
                                        {directCosts.length > 0 ? (
                                            <div className="space-y-2 max-h-32 overflow-y-auto">
                                                {directCosts.map((cost) => (
                                                    <div key={cost.id} className="flex justify-between items-center text-sm bg-white/5 p-2 rounded-lg">
                                                        <span className="text-gray-300">{cost.description}</span>
                                                        <div className="flex items-center">
                                                            <span className="text-white mr-2">S/ {cost.amount.toFixed(2)}</span>
                                                            <button
                                                                onClick={() => deleteCost(cost.id, 'direct')}
                                                                className="text-red-400 hover:text-red-300 text-xs"
                                                            >
                                                                ✕
                                                            </button>
                                                        </div>
                                                    </div>
                                                ))}
                                            </div>
                                        ) : (
                                            <p className="text-gray-400 text-sm">No hay costos directos</p>
                                        )}
                                    </div>

                                    <div className="p-4 glass-effect rounded-xl">
                                        <div className="flex justify-between items-center mb-3">
                                            <h4 className="text-white font-semibold">🏢 Costos Indirectos</h4>
                                            <span className="text-blue-400 font-bold">
                                                S/ {indirectCosts.reduce((sum, cost) => sum + cost.amount, 0).toFixed(2)}
                                            </span>
                                        </div>
                                        {indirectCosts.length > 0 ? (
                                            <div className="space-y-2 max-h-32 overflow-y-auto">
                                                {indirectCosts.map((cost) => (
                                                    <div key={cost.id} className="flex justify-between items-center text-sm bg-white/5 p-2 rounded-lg">
                                                        <span className="text-gray-300">{cost.description}</span>
                                                        <div className="flex items-center">
                                                            <span className="text-white mr-2">S/ {cost.amount.toFixed(2)}</span>
                                                            <button
                                                                onClick={() => deleteCost(cost.id, 'indirect')}
                                                                className="text-red-400 hover:text-red-300 text-xs"
                                                            >
                                                                ✕
                                                            </button>
                                                        </div>
                                                    </div>
                                                ))}
                                            </div>
                                        ) : (
                                            <p className="text-gray-400 text-sm">No hay costos indirectos</p>
                                        )}
                                    </div>

                                    {result && (
                                        <div className="p-6 bg-gradient-to-r from-rose-600/20 to-pink-600/20 rounded-xl border border-rose-500/30 animate-fadeInUp">
                                            <h4 className="text-rose-400 font-semibold mb-4">📊 Resumen total</h4>
                                            <div className="space-y-3">
                                                <div className="flex justify-between p-3 glass-effect rounded-lg">
                                                    <span className="text-gray-300">🎯 Costos directos:</span>
                                                    <span className="text-green-400 font-bold">S/ {result.totalDirectCosts} ({result.directPercentage}%)</span>
                                                </div>
                                                <div className="flex justify-between p-3 glass-effect rounded-lg">
                                                    <span className="text-gray-300">🏢 Costos indirectos:</span>
                                                    <span className="text-blue-400 font-bold">S/ {result.totalIndirectCosts} ({result.indirectPercentage}%)</span>
                                                </div>
                                                <div className="border-t border-white/20 pt-3">
                                                    <div className="flex justify-between font-bold p-3 bg-gradient-to-r from-rose-600/30 to-pink-600/30 rounded-lg">
                                                        <span className="text-white">💼 Total costos:</span>
                                                        <span className="text-rose-400 text-lg">S/ {result.totalCosts}</span>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    )}
                                </div>
                            </div>
                        </div>
                    </div>
                );
            };

            // Navbar Component
            const Navbar = () => (
                <nav className="fixed top-0 left-0 right-0 z-50 bg-gray-900/80 backdrop-blur-lg border-b border-gray-800">
                    <div className="max-w-7xl mx-auto px-6">
                        <div className="flex items-center justify-between h-16">
                            <div className="flex items-center">
                                <button
                                    onClick={() => setCurrentSection(isLoggedIn ? 'dashboard' : 'home')}
                                    className="text-2xl font-bold text-white flex items-center hover:text-purple-400 transition-colors"
                                >
                                    💰 PlanificaSH
                                </button>
                            </div>
                            
                            <div className="hidden md:flex items-center space-x-8">
                                {isLoggedIn && (
                                    <>
                                        <button
                                            onClick={() => setCurrentSection('dashboard')}
                                            className="text-gray-300 hover:text-white transition-colors"
                                        >
                                            Dashboard
                                        </button>
                                        <button
                                            onClick={() => setCurrentSection('tools')}
                                            className="text-gray-300 hover:text-white transition-colors"
                                        >
                                            Herramientas
                                        </button>
                                        <button
                                            onClick={() => setCurrentSection('templates')}
                                            className="text-gray-300 hover:text-white transition-colors"
                                        >
                                            Plantillas
                                        </button>
                                    </>
                                )}
                                <button
                                    onClick={() => setCurrentSection('reviews')}
                                    className="text-gray-300 hover:text-white transition-colors"
                                >
                                    Testimonios
                                </button>
                                {isLoggedIn ? (
                                    <div className="relative group">
                                        <button className="flex items-center space-x-2 text-gray-300 hover:text-white transition-colors">
                                            <UserIcon className="w-5 h-5" />
                                            <span>{userName}</span>
                                        </button>
                                        <div className="absolute right-0 mt-2 w-48 glass-effect rounded-xl shadow-lg opacity-0 invisible group-hover:opacity-100 group-hover:visible transition-all duration-200">
                                            <button
                                                onClick={handleLogout}
                                                className="flex items-center w-full px-4 py-3 text-white hover:bg-white/10 rounded-xl transition-colors"
                                            >
                                                <LogOutIcon className="w-4 h-4 mr-2" />
                                                Cerrar sesión
                                            </button>
                                        </div>
                                    </div>
                                ) : (
                                    <button
                                        onClick={() => setCurrentSection('login')}
                                        className="px-6 py-2 gradient-button text-white rounded-xl font-semibold"
                                    >
                                        Iniciar sesión
                                    </button>
                                )}
                                {isPro && (
                                    <div className="flex items-center px-3 py-1 bg-gradient-to-r from-purple-600 to-pink-600 rounded-full">
                                        <CrownIcon className="w-4 h-4 text-white mr-1" />
                                        <span className="text-white text-sm font-semibold">PRO</span>
                                    </div>
                                )}
                            </div>
                            
                            <button
                                onClick={() => setShowMobileMenu(!showMobileMenu)}
                                className="md:hidden text-white"
                            >
                                <MenuIcon className="w-6 h-6" />
                            </button>
                        </div>
                    </div>
                    
                    {/* Mobile Menu */}
                    {showMobileMenu && (
                        <div className="md:hidden bg-gray-900/95 backdrop-blur-lg border-t border-gray-800">
                            <div className="px-6 py-4 space-y-2">
                                {isLoggedIn && (
                                    <>
                                        <button
                                            onClick={() => {setCurrentSection('dashboard'); setShowMobileMenu(false)}}
                                            className="block w-full text-left px-4 py-2 text-gray-300 hover:text-white hover:bg-white/10 rounded-lg transition-colors"
                                        >
                                            Dashboard
                                        </button>
                                        <button
                                            onClick={() => {setCurrentSection('tools'); setShowMobileMenu(false)}}
                                            className="block w-full text-left px-4 py-2 text-gray-300 hover:text-white hover:bg-white/10 rounded-lg transition-colors"
                                        >
                                            Herramientas
                                        </button>
                                        <button
                                            onClick={() => {setCurrentSection('templates'); setShowMobileMenu(false)}}
                                            className="block w-full text-left px-4 py-2 text-gray-300 hover:text-white hover:bg-white/10 rounded-lg transition-colors"
                                        >
                                            Plantillas
                                        </button>
                                    </>
                                )}
                                <button
                                    onClick={() => {setCurrentSection('reviews'); setShowMobileMenu(false)}}
                                    className="block w-full text-left px-4 py-2 text-gray-300 hover:text-white hover:bg-white/10 rounded-lg transition-colors"
                                >
                                    Testimonios
                                </button>
                                {isLoggedIn ? (
                                    <button
                                        onClick={() => {handleLogout(); setShowMobileMenu(false)}}
                                        className="block w-full text-left px-4 py-2 text-red-400 hover:text-white hover:bg-white/10 rounded-lg transition-colors"
                                    >
                                        Cerrar sesión
                                    </button>
                                ) : (
                                    <button
                                        onClick={() => {setCurrentSection('login'); setShowMobileMenu(false)}}
                                        className="block w-full text-left px-4 py-2 gradient-button text-white rounded-lg font-semibold"
                                    >
                                        Iniciar sesión
                                    </button>
                                )}
                            </div>
                        </div>
                    )}
                </nav>
            );

            const HomePage = () => (
                <div className="min-h-screen">
                    {/* Hero Section */}
                    <section className="relative min-h-screen flex items-center justify-center overflow-hidden bg-gradient-to-br from-purple-900 via-blue-900 to-indigo-900">
                        <div className="absolute inset-0 bg-gradient-to-r from-purple-500/20 to-cyan-500/20 backdrop-blur-3xl"></div>
                        <div className="absolute inset-0">
                            <div className="absolute top-1/4 left-1/4 w-96 h-96 bg-purple-500/30 rounded-full blur-3xl animate-pulse"></div>
                            <div className="absolute bottom-1/4 right-1/4 w-96 h-96 bg-cyan-500/30 rounded-full blur-3xl animate-pulse delay-1000"></div>
                            <div className="absolute top-1/2 left-1/2 w-64 h-64 bg-pink-500/20 rounded-full blur-2xl animate-bounce"></div>
                        </div>
                        
                        <div className="relative z-10 text-center max-w-5xl mx-auto px-6">
                            <div className="mb-8 animate-fadeInUp">
                                <div className="inline-flex items-center px-6 py-3 rounded-full glass-effect border border-white/20 mb-8 button-hover-effect">
                                    <ZapIcon className="w-5 h-5 mr-2 text-yellow-400 animate-bounce" />
                                    <span className="text-white text-sm font-medium">Educación financiera revolucionaria para jóvenes</span>
                                </div>
                            </div>
                            
                            <h1 className="text-6xl md:text-8xl font-bold text-white mb-8 leading-tight animate-fadeInUp">
                                Domina tus <span className="bg-gradient-to-r from-purple-400 to-cyan-400 bg-clip-text text-transparent animate-pulse">finanzas</span> y 
                                <br />construye tu <span className="bg-gradient-to-r from-cyan-400 to-purple-400 bg-clip-text text-transparent animate-pulse">futuro</span>
                            </h1>
                            
                            <p className="text-xl md:text-2xl text-gray-300 mb-10 max-w-4xl mx-auto leading-relaxed animate-fadeInUp">
                                La plataforma de educación financiera más completa de Perú. Herramientas profesionales 
                                para gestionar dinero, optimizar precios y hacer crecer tu emprendimiento.
                            </p>
                            
                            <div className="flex flex-col sm:flex-row gap-6 justify-center items-center animate-fadeInUp">
                                <button 
                                    onClick={handleStartFree}
                                    disabled={isLoading}
                                    className="group px-10 py-5 gradient-button text-white rounded-2xl font-semibold text-lg shadow-2xl hover:shadow-purple-500/25 transition-all duration-300 hover:scale-105 flex items-center disabled:opacity-50"
                                >
                                    {isLoading ? (
                                        <>
                                            <div className="animate-spin rounded-full h-5 w-5 border-b-2 border-white mr-3"></div>
                                            Cargando...
                                        </>
                                    ) : (
                                        <>
                                            🚀 Empieza gratis
                                            <ArrowRightIcon className="w-5 h-5 ml-2 group-hover:translate-x-1 transition-transform" />
                                        </>
                                    )}
                                </button>
                                
                                <button 
                                    onClick={() => {
                                        if (isLoggedIn) {
                                            setCurrentSection('tools');
                                        } else {
                                            showNotification('Regístrate para acceder a todas las herramientas', true);
                                            setCurrentSection('register');
                                        }
                                    }}
                                    className="px-10 py-5 glass-effect text-white rounded-2xl font-semibold text-lg border border-white/20 hover:bg-white/20 transition-all duration-300 hover:scale-105 button-hover-effect"
                                >
                                    🛠️ Ver herramientas
                                </button>
                            </div>

                            <div className="mt-16 flex justify-center items-center space-x-8 text-gray-400">
                                <div className="text-center">
                                    <div className="text-2xl font-bold text-white">5+</div>
                                    <div className="text-sm">Herramientas</div>
                                </div>
                                <div className="text-center">
                                    <div className="text-2xl font-bold text-white">7+</div>
                                    <div className="text-sm">Plantillas Excel</div>
                                </div>
                                <div className="text-center">
                                    <div className="text-2xl font-bold text-white">100%</div>
                                    <div className="text-sm">Gratis</div>
                                </div>
                            </div>
                        </div>
                    </section>

                    {/* Features Section */}
                    <section className="py-24 bg-gradient-to-b from-gray-900 to-black">
                        <div className="max-w-7xl mx-auto px-6">
                            <div className="text-center mb-20">
                                <h2 className="text-5xl font-bold text-white mb-6">Herramientas que transformarán tu negocio</h2>
                                <p className="text-gray-400 text-xl max-w-3xl mx-auto">Calculadoras profesionales diseñadas para optimizar precios, presupuestos y ganancias de tu emprendimiento</p>
                            </div>
                            
                            <div className="grid md:grid-cols-3 gap-10">
                                <div className="group p-8 glass-card rounded-3xl hover:border-white/20 transition-all duration-500 hover:scale-105 animate-fadeInUp">
                                    <div className="w-20 h-20 bg-gradient-to-r from-indigo-500 to-purple-500 rounded-2xl flex items-center justify-center mb-8 group-hover:scale-110 transition-transform duration-300 floating-animation">
                                        <CalculatorIcon className="w-10 h-10 text-white" />
                                    </div>
                                    <h3 className="text-2xl font-bold text-white mb-4">Calculadora de Precios</h3>
                                    <p className="text-gray-400 leading-relaxed">Determina el precio óptimo para tus productos considerando costos de producción, margen deseado y análisis de competencia</p>
                                    <button 
                                        onClick={() => {
                                            if (isLoggedIn) {
                                                setCurrentSection('tools');
                                                setActiveToolId(1);
                                            } else {
                                                setCurrentSection('register');
                                            }
                                        }}
                                        className="mt-6 flex items-center text-purple-400 font-semibold hover:text-purple-300 transition-colors"
                                    >
                                        <span>Usar ahora</span>
                                        <ArrowRightIcon className="w-4 h-4 ml-2 group-hover:translate-x-1 transition-transform" />
                                    </button>
                                </div>
                                
                                <div className="group p-8 glass-card rounded-3xl hover:border-white/20 transition-all duration-500 hover:scale-105 animate-fadeInUp delay-100">
                                    <div className="w-20 h-20 bg-gradient-to-r from-emerald-500 to-teal-500 rounded-2xl flex items-center justify-center mb-8 group-hover:scale-110 transition-transform duration-300 floating-animation">
                                        <BarChart3Icon className="w-10 h-10 text-white" />
                                    </div>
                                    <h3 className="text-2xl font-bold text-white mb-4">Planificador de Presupuesto</h3>
                                    <p className="text-gray-400 leading-relaxed">Organiza tus ingresos y gastos personales aplicando la regla 50/30/20 para una gestión financiera inteligente</p>
                                    <button 
                                        onClick={() => {
                                            if (isLoggedIn) {
                                                setCurrentSection('tools');
                                                setActiveToolId(2);
                                            } else {
                                                setCurrentSection('register');
                                            }
                                        }}
                                        className="mt-6 flex items-center text-emerald-400 font-semibold hover:text-emerald-300 transition-colors"
                                    >
                                        <span>Usar ahora</span>
                                        <ArrowRightIcon className="w-4 h-4 ml-2 group-hover:translate-x-1 transition-transform" />
                                    </button>
                                </div>
                                
                                <div className="group p-8 glass-card rounded-3xl hover:border-white/20 transition-all duration-500 hover:scale-105 animate-fadeInUp delay-200">
                                    <div className="w-20 h-20 bg-gradient-to-r from-green-500 to-emerald-500 rounded-2xl flex items-center justify-center mb-8 group-hover:scale-110 transition-transform duration-300 floating-animation">
                                        <TrendingUpIcon className="w-10 h-10 text-white" />
                                    </div>
                                    <h3 className="text-2xl font-bold text-white mb-4">Simulador de Ganancia</h3>
                                    <p className="text-gray-400 leading-relaxed">Proyecta tus ganancias futuras, calcula el punto de equilibrio y toma decisiones basadas en datos reales</p>
                                    <button 
                                        onClick={() => {
                                            if (isLoggedIn) {
                                                setCurrentSection('tools');
                                                setActiveToolId(4);
                                            } else {
                                                setCurrentSection('register');
                                            }
                                        }}
                                        className="mt-6 flex items-center text-green-400 font-semibold hover:text-green-300 transition-colors"
                                    >
                                        <span>Usar ahora</span>
                                        <ArrowRightIcon className="w-4 h-4 ml-2 group-hover:translate-x-1 transition-transform" />
                                    </button>
                                </div>
                            </div>
                        </div>
                    </section>
                </div>
            );

            const ToolsPage = () => (
                <div className="min-h-screen pt-20 bg-gradient-to-br from-purple-900 via-blue-900 to-indigo-900">
                    <div className="max-w-7xl mx-auto px-6 py-12">
                        <div className="text-center mb-12">
                            <h1 className="text-5xl font-bold text-white mb-4">Herramientas Financieras</h1>
                            <p className="text-gray-300 text-xl">Potencia tu negocio con nuestras calculadoras profesionales</p>
                        </div>
                        
                        {isLoggedIn && activeToolId !== null ? (
                            <div>
                                <button
                                    onClick={() => setActiveToolId(null)}
                                    className="mb-6 flex items-center text-gray-300 hover:text-white transition-colors"
                                >
                                    <ArrowRightIcon className="w-5 h-5 mr-2 rotate-180" />
                                    Volver a herramientas
                                </button>
                                
                                {activeToolId === 1 && <PriceCalculatorTool />}
                                {activeToolId === 2 && <BudgetPlannerTool />}
                                {activeToolId === 3 && <IncomeExpensesTool />}
                                {activeToolId === 4 && <ProfitSimulatorTool />}
                                {activeToolId === 5 && <CostStructureTool />}
                            </div>
                        ) : (
                            <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                                {[
                                    { id: 1, title: 'Calculadora de Precios', icon: CalculatorIcon, color: 'from-indigo-500 to-purple-500', desc: 'Calcula el precio óptimo para maximizar tus ganancias' },
                                    { id: 2, title: 'Planificador de Presupuesto', icon: BarChart3Icon, color: 'from-emerald-500 to-teal-500', desc: 'Organiza tus finanzas con la regla 50/30/20' },
                                    { id: 3, title: 'Control de Ingresos y Gastos', icon: WalletIcon, color: 'from-blue-500 to-cyan-500', desc: 'Registra cada movimiento de tu dinero' },
                                    { id: 4, title: 'Simulador de Ganancia', icon: TrendingUpIcon, color: 'from-green-500 to-emerald-500', desc: 'Proyecta tus ganancias y punto de equilibrio' },
                                    { id: 5, title: 'Estructura de Costos', icon: FileTextIcon, color: 'from-rose-500 to-pink-500', desc: 'Analiza tus costos directos e indirectos' }
                                ].map((tool) => (
                                    <div
                                        key={tool.id}
                                        className="p-8 glass-card rounded-3xl hover:scale-105 transition-all duration-300 group relative"
                                    >
                                        <div className={`w-16 h-16 bg-gradient-to-r ${tool.color} rounded-2xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform`}>
                                            <tool.icon className="w-8 h-8 text-white" />
                                        </div>
                                        <h3 className="text-xl font-bold text-white mb-3">{tool.title}</h3>
                                        <p className="text-gray-400 text-sm mb-6">{tool.desc}</p>
                                        
                                        <button
                                            onClick={() => {
                                                if (isLoggedIn) {
                                                    setActiveToolId(tool.id);
                                                } else {
                                                    showNotification('Debes iniciar sesión para usar las herramientas', true);
                                                    setCurrentSection('register');
                                                }
                                            }}
                                            className="w-full py-3 gradient-button text-white rounded-xl font-semibold button-hover-effect"
                                        >
                                            {isLoggedIn ? 'Usar ahora' : 'Registrarse para usar'}
                                        </button>
                                        
                                        {!isLoggedIn && (
                                            <div className="absolute inset-0 bg-black/50 backdrop-blur-sm rounded-3xl flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity">
                                                <div className="text-center p-6">
                                                    <LockIcon className="w-12 h-12 text-white mx-auto mb-4" />
                                                    <p className="text-white font-semibold">Regístrate gratis para usar</p>
                                                </div>
                                            </div>
                                        )}
                                    </div>
                                ))}
                            </div>
                        )}
                    </div>
                </div>
            );

            const TemplatesPage = () => (
                <div className="min-h-screen pt-20 bg-gradient-to-br from-purple-900 via-blue-900 to-indigo-900">
                    <div className="max-w-7xl mx-auto px-6 py-12">
                        <div className="text-center mb-12">
                            <h1 className="text-5xl font-bold text-white mb-4">Plantillas Excel Profesionales</h1>
                            <p className="text-gray-300 text-xl">Descarga plantillas listas para usar en tu negocio</p>
                            
                            {!isLoggedIn ? (
                                <div className="mt-6 inline-flex items-center px-6 py-3 bg-gradient-to-r from-red-600/20 to-orange-600/20 rounded-full border border-red-500/30">
                                    <LockIcon className="w-5 h-5 text-red-400 mr-2" />
                                    <span className="text-red-300">Debes iniciar sesión para acceder a las plantillas</span>
                                </div>
                            ) : !isPro && (
                                <div className="mt-6 inline-flex items-center px-6 py-3 bg-gradient-to-r from-purple-600/20 to-pink-600/20 rounded-full border border-purple-500/30">
                                    <LockIcon className="w-5 h-5 text-purple-400 mr-2" />
                                    <span className="text-purple-300">Actualiza a Pro para acceder a todas las plantillas</span>
                                </div>
                            )}
                        </div>
                        
                        <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                            {templates.map((template) => (
                                <div
                                    key={template.id}
                                    className={`glass-card rounded-3xl p-8 ${!isLoggedIn || (template.isPro && !isPro) ? 'opacity-75' : ''} hover:scale-105 transition-all duration-300 relative group`}
                                >
                                    <div className="flex justify-between items-start mb-4">
                                        <span className="px-3 py-1 bg-gradient-to-r from-blue-600/20 to-purple-600/20 rounded-full text-blue-400 text-sm font-semibold">
                                            {template.category}
                                        </span>
                                        {template.isPro && (
                                            <div className="flex items-center px-2 py-1 bg-gradient-to-r from-purple-600 to-pink-600 rounded-full">
                                                <CrownIcon className="w-3 h-3 text-white mr-1" />
                                                <span className="text-white text-xs font-semibold">PRO</span>
                                            </div>
                                        )}
                                    </div>
                                    
                                    <h3 className="text-xl font-bold text-white mb-3">{template.title}</h3>
                                    <p className="text-gray-400 text-sm mb-6 line-clamp-3">{template.description}</p>
                                    
                                    <div className="flex justify-between items-center">
                                        <span className="text-gray-500 text-sm">{template.size}</span>
                                        <button
                                            onClick={() => {
                                                if (!isLoggedIn) {
                                                    showNotification('Debes iniciar sesión para descargar plantillas', true);
                                                    setCurrentSection('register');
                                                } else {
                                                    handleTemplateClick(template);
                                                }
                                            }}
                                            className={`flex items-center px-4 py-2 rounded-xl font-semibold transition-all ${
                                                !isLoggedIn || (template.isPro && !isPro)
                                                    ? 'bg-gray-700 text-gray-400'
                                                    : 'gradient-button text-white hover:scale-105'
                                            }`}
                                        >
                                            {!isLoggedIn ? (
                                                <>
                                                    <LockIcon className="w-4 h-4 mr-2" />
                                                    Registrarse
                                                </>
                                            ) : template.isPro && !isPro ? (
                                                <>
                                                    <LockIcon className="w-4 h-4 mr-2" />
                                                    Pro
                                                </>
                                            ) : (
                                                <>
                                                    <DownloadIcon className="w-4 h-4 mr-2" />
                                                    Descargar
                                                </>
                                            )}
                                        </button>
                                    </div>
                                    
                                    {!isLoggedIn && (
                                        <div className="absolute inset-0 bg-black/50 backdrop-blur-sm rounded-3xl flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity">
                                            <div className="text-center p-6">
                                                <LockIcon className="w-12 h-12 text-white mx-auto mb-4" />
                                                <p className="text-white font-semibold">Regístrate gratis para descargar</p>
                                            </div>
                                        </div>
                                    )}
                                </div>
                            ))}
                        </div>
                    </div>
                </div>
            );

            const ReviewsPage = () => {
                const [localNewComment, setLocalNewComment] = useState({ 
                    name: '', 
                    age: '', 
                    city: '', 
                    rating: 5, 
                    text: '' 
                });

                const handleLocalAddComment = () => {
                    if (localNewComment.name && localNewComment.age && localNewComment.city && localNewComment.text) {
                        const comment = {
                            id: comments.length + 1,
                            ...localNewComment
                        };
                        setComments([...comments, comment]);
                        setLocalNewComment({ name: '', age: '', city: '', rating: 5, text: '' });
                        showNotification('¡Comentario agregado exitosamente!');
                    } else {
                        showNotification('Por favor completa todos los campos', true);
                    }
                };

                return (
                    <div className="min-h-screen pt-20 bg-gradient-to-br from-purple-900 via-blue-900 to-indigo-900">
                        <div className="max-w-7xl mx-auto px-6 py-12">
                            <div className="text-center mb-12">
                                <h1 className="text-5xl font-bold text-white mb-4">Lo que dicen nuestros usuarios</h1>
                                <p className="text-gray-300 text-xl">Miles de jóvenes están transformando sus finanzas con PlanificaSH</p>
                            </div>
                            
                            <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8 mb-12">
                                {comments.map((comment) => (
                                    <div key={comment.id} className="glass-card rounded-3xl p-8 hover:scale-105 transition-all duration-300">
                                        <div className="flex items-center mb-4">
                                            <div className="w-12 h-12 bg-gradient-to-r from-purple-500 to-pink-500 rounded-full flex items-center justify-center text-white font-bold text-lg mr-4">
                                                {comment.name.charAt(0)}
                                            </div>
                                            <div>
                                                <h4 className="text-white font-semibold">{comment.name}</h4>
                                                <p className="text-gray-400 text-sm">{comment.age} años, {comment.city}</p>
                                            </div>
                                        </div>
                                        
                                        <div className="flex mb-4">{renderStars(comment.rating)}</div>
                                        <p className="text-gray-300">{comment.text}</p>
                                    </div>
                                ))}
                            </div>
                            
                            <div className="max-w-2xl mx-auto">
                                <div className="glass-card rounded-3xl p-8">
                                    <h3 className="text-2xl font-bold text-white mb-6 text-center">Deja tu testimonio</h3>
                                    
                                    <form onSubmit={(e) => { e.preventDefault(); handleLocalAddComment(); }} className="space-y-4">
                                        <div className="grid md:grid-cols-3 gap-4">
                                            <input
                                                type="text"
                                                placeholder="Tu nombre"
                                                value={localNewComment.name}
                                                onChange={(e) => setLocalNewComment({...localNewComment, name: e.target.value})}
                                                className="p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500"
                                                autoComplete="off"
                                            />
                                            <input
                                                type="number"
                                                placeholder="Tu edad"
                                                value={localNewComment.age}
                                                onChange={(e) => setLocalNewComment({...localNewComment, age: e.target.value})}
                                                className="p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500"
                                                autoComplete="off"
                                                min="1"
                                                max="120"
                                            />
                                            <input
                                                type="text"
                                                placeholder="Tu ciudad"
                                                value={localNewComment.city}
                                                onChange={(e) => setLocalNewComment({...localNewComment, city: e.target.value})}
                                                className="p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500"
                                                autoComplete="off"
                                            />
                                        </div>
                                        
                                        <div className="flex items-center justify-center space-x-2">
                                            <span className="text-white mr-3">Tu calificación:</span>
                                            {renderStars(localNewComment.rating, true, (rating) => setLocalNewComment({...localNewComment, rating}))}
                                        </div>
                                        
                                        <textarea
                                            placeholder="Comparte tu experiencia con PlanificaSH..."
                                            value={localNewComment.text}
                                            onChange={(e) => setLocalNewComment({...localNewComment, text: e.target.value})}
                                            rows={4}
                                            className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500 resize-none"
                                            autoComplete="off"
                                        />
                                        
                                        <button
                                            type="submit"
                                            className="w-full py-4 gradient-button text-white rounded-xl font-semibold button-hover-effect"
                                        >
                                            Publicar testimonio
                                        </button>
                                    </form>
                                </div>
                            </div>
                        </div>
                    </div>
                );
            };

            const LoginPage = () => (
                <div className="min-h-screen pt-20 bg-gradient-to-br from-purple-900 via-blue-900 to-indigo-900 flex items-center justify-center">
                    <div className="max-w-md w-full mx-auto px-6">
                        <div className="glass-card rounded-3xl p-8">
                            <h2 className="text-3xl font-bold text-white mb-8 text-center">Iniciar Sesión</h2>
                            
                            <form onSubmit={handleLogin} className="space-y-6">
                                <div>
                                    <label className="block text-white font-semibold mb-2">Correo electrónico</label>
                                    <input
                                        type="email"
                                        name="email"
                                        required
                                        className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500"
                                        placeholder="tu@email.com"
                                    />
                                </div>
                                
                                <div>
                                    <label className="block text-white font-semibold mb-2">Contraseña</label>
                                    <input
                                        type="password"
                                        name="password"
                                        required
                                        className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500"
                                        placeholder="••••••••"
                                    />
                                </div>
                                
                                <button
                                    type="submit"
                                    className="w-full py-4 gradient-button text-white rounded-xl font-semibold button-hover-effect"
                                >
                                    Iniciar sesión
                                </button>
                            </form>
                            
                            <div className="mt-6 text-center">
                                <p className="text-gray-400">
                                    ¿No tienes cuenta?{' '}
                                    <button
                                        onClick={() => setCurrentSection('register')}
                                        className="text-purple-400 hover:text-purple-300 font-semibold"
                                    >
                                        Regístrate gratis
                                    </button>
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            );

            const RegisterPage = () => (
                <div className="min-h-screen pt-20 bg-gradient-to-br from-purple-900 via-blue-900 to-indigo-900 flex items-center justify-center">
                    <div className="max-w-md w-full mx-auto px-6">
                        <div className="glass-card rounded-3xl p-8">
                            <h2 className="text-3xl font-bold text-white mb-8 text-center">Crear Cuenta Gratis</h2>
                            
                            <form onSubmit={handleLogin} className="space-y-6">
                                <div>
                                    <label className="block text-white font-semibold mb-2">Nombre completo</label>
                                    <input
                                        type="text"
                                        name="name"
                                        required
                                        className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500"
                                        placeholder="Juan Pérez"
                                    />
                                </div>
                                
                                <div>
                                    <label className="block text-white font-semibold mb-2">Correo electrónico</label>
                                    <input
                                        type="email"
                                        name="email"
                                        required
                                        className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500"
                                        placeholder="tu@email.com"
                                    />
                                </div>
                                
                                <div>
                                    <label className="block text-white font-semibold mb-2">Contraseña</label>
                                    <input
                                        type="password"
                                        name="password"
                                        required
                                        className="w-full p-4 glass-effect rounded-xl text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-purple-500"
                                        placeholder="Mínimo 8 caracteres"
                                    />
                                </div>
                                
                                <button
                                    type="submit"
                                    className="w-full py-4 gradient-button text-white rounded-xl font-semibold button-hover-effect"
                                >
                                    Crear cuenta gratis
                                </button>
                            </form>
                            
                            <div className="mt-6 text-center">
                                <p className="text-gray-400">
                                    ¿Ya tienes cuenta?{' '}
                                    <button
                                        onClick={() => setCurrentSection('login')}
                                        className="text-purple-400 hover:text-purple-300 font-semibold"
                                    >
                                        Inicia sesión
                                    </button>
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            );

            const DashboardPage = () => (
                <div className="min-h-screen pt-20 bg-gradient-to-br from-purple-900 via-blue-900 to-indigo-900">
                    <div className="max-w-7xl mx-auto px-6 py-12">
                        <div className="mb-8">
                            <h1 className="text-4xl font-bold text-white mb-2">¡Hola, {userName}! 👋</h1>
                            <p className="text-gray-300">Aquí está tu resumen financiero del mes</p>
                        </div>
                        
                        <div className="grid md:grid-cols-4 gap-6 mb-12">
                            <div className="glass-card rounded-2xl p-6">
                                <div className="flex items-center justify-between mb-4">
                                    <div className="w-12 h-12 bg-gradient-to-r from-green-500 to-emerald-500 rounded-xl flex items-center justify-center">
                                        <span className="text-2xl">💰</span>
                                    </div>
                                    <span className="text-green-400 text-sm font-semibold">+15%</span>
                                </div>
                                <p className="text-gray-400 text-sm">Ingresos totales</p>
                                <p className="text-2xl font-bold text-white">S/ 4,850</p>
                            </div>
                            
                            <div className="glass-card rounded-2xl p-6">
                                <div className="flex items-center justify-between mb-4">
                                    <div className="w-12 h-12 bg-gradient-to-r from-red-500 to-pink-500 rounded-xl flex items-center justify-center">
                                        <span className="text-2xl">💸</span>
                                    </div>
                                    <span className="text-red-400 text-sm font-semibold">-8%</span>
                                </div>
                                <p className="text-gray-400 text-sm">Gastos totales</p>
                                <p className="text-2xl font-bold text-white">S/ 2,320</p>
                            </div>
                            
                            <div className="glass-card rounded-2xl p-6">
                                <div className="flex items-center justify-between mb-4">
                                    <div className="w-12 h-12 bg-gradient-to-r from-blue-500 to-cyan-500 rounded-xl flex items-center justify-center">
                                        <span className="text-2xl">💾</span>
                                    </div>
                                    <span className="text-blue-400 text-sm font-semibold">+23%</span>
                                </div>
                                <p className="text-gray-400 text-sm">Ahorros</p>
                                <p className="text-2xl font-bold text-white">S/ 1,230</p>
                            </div>
                            
                            <div className="glass-card rounded-2xl p-6">
                                <div className="flex items-center justify-between mb-4">
                                    <div className="w-12 h-12 bg-gradient-to-r from-purple-500 to-pink-500 rounded-xl flex items-center justify-center">
                                        <span className="text-2xl">📊</span>
                                    </div>
                                    <span className="text-purple-400 text-sm font-semibold">85%</span>
                                </div>
                                <p className="text-gray-400 text-sm">Salud financiera</p>
                                <p className="text-2xl font-bold text-white">Excelente</p>
                            </div>
                        </div>
                        
                        <div className="grid md:grid-cols-2 gap-8">
                            <div className="glass-card rounded-3xl p-8">
                                <h3 className="text-xl font-bold text-white mb-6">🎯 Acciones rápidas</h3>
                                <div className="space-y-4">
                                    <button
                                        onClick={() => {
                                            setCurrentSection('tools');
                                            setActiveToolId(1);
                                        }}
                                        className="w-full p-4 glass-effect rounded-xl text-left hover:bg-white/10 transition-colors"
                                    >
                                        <div className="flex items-center justify-between">
                                            <div className="flex items-center">
                                                <CalculatorIcon className="w-6 h-6 text-purple-400 mr-3" />
                                                <span className="text-white font-semibold">Calcular precios</span>
                                            </div>
                                            <ArrowRightIcon className="w-5 h-5 text-gray-400" />
                                        </div>
                                    </button>
                                    
                                    <button
                                        onClick={() => setCurrentSection('templates')}
                                        className="w-full p-4 glass-effect rounded-xl text-left hover:bg-white/10 transition-colors"
                                    >
                                        <div className="flex items-center justify-between">
                                            <div className="flex items-center">
                                                <FileTextIcon className="w-6 h-6 text-blue-400 mr-3" />
                                                <span className="text-white font-semibold">Descargar plantillas</span>
                                            </div>
                                            <ArrowRightIcon className="w-5 h-5 text-gray-400" />
                                        </div>
                                    </button>
                                    
                                    <button
                                        onClick={() => setShowChatbot(true)}
                                        className="w-full p-4 glass-effect rounded-xl text-left hover:bg-white/10 transition-colors"
                                    >
                                        <div className="flex items-center justify-between">
                                            <div className="flex items-center">
                                                <MessageCircleIcon className="w-6 h-6 text-green-400 mr-3" />
                                                <span className="text-white font-semibold">Hablar con Chanchi</span>
                                            </div>
                                            <ArrowRightIcon className="w-5 h-5 text-gray-400" />
                                        </div>
                                    </button>
                                </div>
                            </div>
                            
                            <div className="glass-card rounded-3xl p-8">
                                <h3 className="text-xl font-bold text-white mb-6">💡 Tips del día</h3>
                                <div className="space-y-4">
                                    <div className="p-4 bg-gradient-to-r from-purple-600/20 to-pink-600/20 rounded-xl border border-purple-500/30">
                                        <LightbulbIcon className="w-6 h-6 text-purple-400 mb-2" />
                                        <p className="text-white font-semibold mb-1">Regla 50/30/20</p>
                                        <p className="text-gray-300 text-sm">Destina 50% a necesidades, 30% a deseos y 20% a ahorros</p>
                                    </div>
                                    
                                    <div className="p-4 bg-gradient-to-r from-blue-600/20 to-cyan-600/20 rounded-xl border border-blue-500/30">
                                        <LightbulbIcon className="w-6 h-6 text-blue-400 mb-2" />
                                        <p className="text-white font-semibold mb-1">Automatiza tus ahorros</p>
                                        <p className="text-gray-300 text-sm">Programa transferencias automáticas apenas recibas tu ingreso</p>
                                    </div>
                                    
                                    <div className="p-4 bg-gradient-to-r from-green-600/20 to-emerald-600/20 rounded-xl border border-green-500/30">
                                        <LightbulbIcon className="w-6 h-6 text-green-400 mb-2" />
                                        <p className="text-white font-semibold mb-1">Revisa tus gastos</p>
                                        <p className="text-gray-300 text-sm">Analiza tus gastos semanalmente para identificar fugas</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        
                        {!isPro && (
                            <div className="mt-12 p-8 bg-gradient-to-r from-purple-600/20 to-pink-600/20 rounded-3xl border border-purple-500/30">
                                <div className="flex items-center justify-between">
                                    <div>
                                        <h3 className="text-2xl font-bold text-white mb-2">🚀 Desbloquea todo el potencial</h3>
                                        <p className="text-gray-300">Accede a todas las plantillas y herramientas premium</p>
                                    </div>
                                    <button
                                        onClick={() => setShowUpgradeModal(true)}
                                        className="px-8 py-4 gradient-button text-white rounded-xl font-semibold button-hover-effect"
                                    >
                                        Actualizar a Pro
                                    </button>
                                </div>
                            </div>
                        )}
                    </div>
                </div>
            );

            // Upgrade Modal
            const UpgradeModal = () => (
                <div className="fixed inset-0 bg-black/80 backdrop-blur-sm flex items-center justify-center z-50 p-6">
                    <div className="glass-card rounded-3xl max-w-2xl w-full p-8 animate-fadeInUp">
                        <div className="flex justify-between items-start mb-6">
                            <div>
                                <h2 className="text-3xl font-bold text-white mb-2">Actualiza a Plan Pro</h2>
                                <p className="text-gray-400">Desbloquea todas las herramientas premium</p>
                            </div>
                            <button
                                onClick={() => setShowUpgradeModal(false)}
                                className="text-gray-400 hover:text-white transition-colors"
                            >
                                <XIcon className="w-6 h-6" />
                            </button>
                        </div>
                        
                        <div className="grid md:grid-cols-2 gap-6 mb-8">
                            <div className="p-6 glass-effect rounded-2xl">
                                <h3 className="text-xl font-bold text-white mb-4">Plan Gratis</h3>
                                <p className="text-3xl font-bold text-white mb-6">S/ 0<span className="text-gray-400 text-lg font-normal">/mes</span></p>
                                <ul className="space-y-3">
                                    <li className="flex items-center text-gray-300">
                                        <CheckCircleIcon className="w-5 h-5 text-green-400 mr-3" />
                                        5 herramientas básicas
                                    </li>
                                    <li className="flex items-center text-gray-300">
                                        <CheckCircleIcon className="w-5 h-5 text-green-400 mr-3" />
                                        3 plantillas Excel
                                    </li>
                                    <li className="flex items-center text-gray-300">
                                        <CheckCircleIcon className="w-5 h-5 text-green-400 mr-3" />
                                        Chatbot básico
                                    </li>
                                </ul>
                            </div>
                            
                            <div className="p-6 bg-gradient-to-r from-purple-600/20 to-pink-600/20 rounded-2xl border border-purple-500/30">
                                <div className="flex items-center justify-between mb-4">
                                    <h3 className="text-xl font-bold text-white">Plan Pro</h3>
                                    <div className="flex items-center px-3 py-1 bg-gradient-to-r from-purple-600 to-pink-600 rounded-full">
                                        <CrownIcon className="w-4 h-4 text-white mr-1" />
                                        <span className="text-white text-sm font-semibold">RECOMENDADO</span>
                                    </div>
                                </div>
                                <p className="text-3xl font-bold text-white mb-6">S/ 29<span className="text-gray-400 text-lg font-normal">/mes</span></p>
                                <ul className="space-y-3">
                                    <li className="flex items-center text-white">
                                        <CheckCircleIcon className="w-5 h-5 text-purple-400 mr-3" />
                                        Todo del plan gratis
                                    </li>
                                    <li className="flex items-center text-white">
                                        <CheckCircleIcon className="w-5 h-5 text-purple-400 mr-3" />
                                        7+ plantillas premium
                                    </li>
                                    <li className="flex items-center text-white">
                                        <CheckCircleIcon className="w-5 h-5 text-purple-400 mr-3" />
                                        Herramientas avanzadas
                                    </li>
                                    <li className="flex items-center text-white">
                                        <CheckCircleIcon className="w-5 h-5 text-purple-400 mr-3" />
                                        Soporte prioritario
                                    </li>
                                    <li className="flex items-center text-white">
                                        <CheckCircleIcon className="w-5 h-5 text-purple-400 mr-3" />
                                        Análisis avanzados
                                    </li>
                                </ul>
                            </div>
                        </div>
                        
                        <button
                            onClick={() => {
                                setIsPro(true);
                                setShowUpgradeModal(false);
                                showNotification('¡Felicidades! Ahora eres usuario Pro 🎉');
                            }}
                            className="w-full py-4 gradient-button text-white rounded-xl font-semibold button-hover-effect text-lg"
                        >
                            Actualizar ahora - S/ 29/mes
                        </button>
                        
                        <p className="text-center text-gray-400 text-sm mt-4">
                            Cancela cuando quieras • Sin compromisos • Garantía de 30 días
                        </p>
                    </div>
                </div>
            );

            // Chatbot Component
           // Chatbot Component - COMPLETAMENTE AISLADO
            const Chatbot = () => {
                // Estado local para el chatbot
                const [localMessage, setLocalMessage] = useState('');

                const handleSendMessage = () => {
                    if (localMessage.trim()) {
                        const userMsg = { 
                            id: Date.now(), 
                            text: localMessage.trim(), 
                            sender: 'user' 
                        };
                        
                        let botMsg = '¡Hola! Soy Chanchi 🐷. Te puedo ayudar con finanzas, herramientas y Plan Pro.';
                        
                        if (localMessage.toLowerCase().includes('hola')) {
                            botMsg = '¡Hola! 👋 ¿En qué puedo ayudarte hoy?';
                        } else if (localMessage.toLowerCase().includes('herramientas')) {
                            botMsg = '🛠️ Tenemos 5 herramientas: Calculadora de Precios, Presupuesto, Control de Gastos, Simulador y Estructura de Costos.';
                        } else if (localMessage.toLowerCase().includes('pro')) {
                            botMsg = '💎 Plan Pro: S/29/mes con plantillas premium y herramientas avanzadas.';
                        }
                        
                        const botResponse = { 
                            id: Date.now() + 1, 
                            text: botMsg, 
                            sender: 'bot' 
                        };
                        
                        setChatMessages(prev => [...prev, userMsg, botResponse]);
                        setLocalMessage('');
                    }
                };

                return (
                    <div className="fixed bottom-6 right-6 z-50" style={{ isolation: 'isolate' }}>
                        {showChatbot ? (
                            <div 
                                className="glass-card rounded-3xl shadow-2xl animate-fadeInUp" 
                                style={{ width: '320px', height: '450px', isolation: 'isolate' }}
                                onClick={(e) => e.stopPropagation()}
                            >
                                {/* Header */}
                                <div className="p-4 border-b border-white/10">
                                    <div className="flex items-center justify-between">
                                        <div className="flex items-center">
                                            <div className="w-8 h-8 bg-gradient-to-r from-purple-500 to-pink-500 rounded-full flex items-center justify-center mr-2">
                                                <span className="text-sm">🐷</span>
                                            </div>
                                            <div>
                                                <h3 className="text-white font-bold text-sm">Chanchi</h3>
                                                <p className="text-green-400 text-xs">En línea</p>
                                            </div>
                                        </div>
                                        <div
                                            onClick={() => setShowChatbot(false)}
                                            className="text-gray-400 hover:text-white text-xl font-bold w-8 h-8 flex items-center justify-center hover:bg-white/10 rounded-lg cursor-pointer"
                                        >
                                            ×
                                        </div>
                                    </div>
                                </div>
                                
                                {/* Messages */}
                                <div className="p-4 overflow-y-auto" style={{ height: '280px' }}>
                                    {chatMessages.map((message) => (
                                        <div key={message.id} className={`mb-3 ${message.sender === 'user' ? 'text-right' : 'text-left'}`}>
                                            <div className={`inline-block px-3 py-2 rounded-xl text-sm max-w-xs ${
                                                message.sender === 'user'
                                                    ? 'gradient-button text-white'
                                                    : 'glass-effect text-white'
                                            }`}>
                                                {message.text}
                                            </div>
                                        </div>
                                    ))}
                                </div>
                                
                                {/* Input - COMPLETAMENTE AISLADO */}
                                <div className="p-4 border-t border-white/10">
                                    <div className="flex items-center space-x-2">
                                        <div className="flex-1 relative">
                                            <textarea
                                                value={localMessage}
                                                onChange={(e) => {
                                                    e.stopPropagation();
                                                    setLocalMessage(e.target.value);
                                                }}
                                                onKeyPress={(e) => {
                                                    e.stopPropagation();
                                                    if (e.key === 'Enter' && !e.shiftKey) {
                                                        e.preventDefault();
                                                        handleSendMessage();
                                                    }
                                                }}
                                                placeholder="Escribe aquí..."
                                                rows="1"
                                                className="w-full p-2 rounded-lg text-white text-sm placeholder-gray-400 resize-none"
                                                style={{
                                                    background: 'rgba(255, 255, 255, 0.1)',
                                                    border: '1px solid rgba(255, 255, 255, 0.2)',
                                                    outline: 'none',
                                                    fontSize: '14px',
                                                    lineHeight: '20px',
                                                    minHeight: '32px',
                                                    maxHeight: '80px'
                                                }}
                                            />
                                        </div>
                                        <div
                                            onClick={(e) => {
                                                e.stopPropagation();
                                                handleSendMessage();
                                            }}
                                            className="w-8 h-8 gradient-button rounded-lg text-white hover:scale-105 transition-transform flex items-center justify-center text-sm cursor-pointer"
                                        >
                                            ➤
                                        </div>
                                    </div>
                                </div>
                            </div>
                        ) : (
                            <div
                                onClick={(e) => {
                                    e.stopPropagation();
                                    setShowChatbot(true);
                                }}
                                className="w-14 h-14 gradient-button rounded-full shadow-2xl hover:scale-110 transition-all duration-300 flex items-center justify-center cursor-pointer"
                            >
                                <span className="text-xl">🐷</span>
                            </div>
                        )}
                    </div>
                );
            };

            return (
                <div className="min-h-screen bg-black">
                    <Navbar />
                    
                    {currentSection === 'home' && <HomePage />}
                    {currentSection === 'tools' && <ToolsPage />}
                    {currentSection === 'templates' && <TemplatesPage />}
                    {currentSection === 'reviews' && <ReviewsPage />}
                    {currentSection === 'login' && <LoginPage />}
                    {currentSection === 'register' && <RegisterPage />}
                    {currentSection === 'dashboard' && <DashboardPage />}
                    
                    {showUpgradeModal && <UpgradeModal />}
                    <Chatbot />
                </div>
            );
        };

        ReactDOM.render(<PlanificaSH />, document.getElementById('root'));
    </script>
</body>
</html>
