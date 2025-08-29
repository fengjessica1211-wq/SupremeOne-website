<html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SupremeONE Group - Data-Driven Supply Chain Solutions</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&amp;display=swap" rel="stylesheet">
    
    <!-- Tailwind Configuration -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'primary-green': '#81B68D',
                        'deep-blue': '#004674',
                        'neutral-gray': '#676866',
                        'light-gray': '#D4D5D5',
                        'soft-green': 'rgba(129, 182, 141, 0.1)',
                        'required-red': '#e53e3e',
                    },
                    fontFamily: {
                        inter: ['Inter', 'sans-serif'],
                    },
                    boxShadow: {
                        'subtle': '0 4px 12px rgba(0, 0, 0, 0.05)',
                        'card': '0 6px 16px rgba(0, 0, 0, 0.08)',
                    }
                },
            }
        }
    </script>
    
    <style type="text/tailwindcss">
        @layer utilities {
            .content-auto {
                content-visibility: auto;
            }
            .text-shadow-sm {
                text-shadow: 0 1px 2px rgba(0, 0, 0, 0.1);
            }
            .transition-custom {
                transition: all 0.3s ease;
            }
            .logo {
                max-height: 40px;
                width: auto;
            }
            .footer-logo {
                max-height: 50px;
                width: auto;
                filter: brightness(0) invert(1); /* Makes logo white for dark background */
            }
        }
    </style>
</head>
<body class="font-inter text-neutral-gray bg-white">
    <!-- Navigation Bar -->
    <header class="fixed w-full bg-white shadow-subtle z-50 transition-all duration-300" id="navbar">
        <div class="container mx-auto px-4 md:px-6 py-4">
            <div class="flex justify-between items-center">
                <!-- Logo -->
                <a href="#" class="flex items-center">
                    <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/code_assistant/751549a7038440e4ac3ec19f87bb7e05~tplv-a9rns2rl98-image.image?rcl=202508281617344A47ADCEA788BC57291D&amp;rk3s=8e244e95&amp;rrcfp=e75484ac&amp;x-expires=1756973855&amp;x-signature=P9700JWQj4rIFrEJYoQL9CNx7cQ%3D" alt="SupremeONE Group Logo" class="logo">
                </a>
                
                <!-- Desktop Navigation -->
                <nav class="hidden md:flex items-center space-x-8">
                    <a href="#about" class="text-neutral-gray hover:text-primary-green transition-custom font-medium">About Us</a>
                    <a href="#brands" class="text-neutral-gray hover:text-primary-green transition-custom font-medium">Our Brands</a>
                    <a href="#contact" class="text-neutral-gray hover:text-primary-green transition-custom font-medium">Contact</a>
                </nav>
                
                <!-- Mobile Menu Button -->
                <button class="md:hidden text-deep-blue" id="mobile-menu-button">
                    <i class="fa fa-bars text-xl"></i>
                </button>
            </div>
            
            <!-- Mobile Navigation -->
            <div class="md:hidden hidden mt-4 pb-2" id="mobile-menu">
                <div class="flex flex-col space-y-3">
                    <a href="#about" class="text-neutral-gray hover:text-primary-green transition-custom font-medium">About Us</a>
                    <a href="#brands" class="text-neutral-gray hover:text-primary-green transition-custom font-medium">Our Brands</a>
                    <a href="#contact" class="text-neutral-gray hover:text-primary-green transition-custom font-medium">Contact</a>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Banner Section -->
    <section class="pt-28 pb-20 bg-light-gray relative overflow-hidden">
        <div class="absolute top-0 right-0 w-1/3 h-full bg-primary-green opacity-10 -skew-x-12 transform origin-top-right"></div>
        <div class="container mx-auto px-4 md:px-6 relative z-10">
            <div class="max-w-3xl">
                <h1 class="text-[clamp(2.5rem,5vw,4rem)] font-bold text-deep-blue leading-tight mb-4">
                    SupremeONE
                </h1>
                <p class="text-[clamp(1.2rem,2vw,1.5rem)] text-neutral-gray font-semibold mb-6">
                    Driven by Data, Delivering with Purpose
                </p>
                <p class="text-lg md:text-xl mb-8 text-neutral-gray max-w-2xl">
                    Empowering global businesses with data-driven, sustainable supply chain solutions.
                </p>
                <a href="#contact" class="inline-block bg-primary-green hover:bg-primary-green/90 text-white font-medium py-3 px-8 rounded-full shadow-subtle transition-custom transform hover:-translate-y-1">
                    Get in Touch
                </a>
            </div>
        </div>
    </section>

    <!-- About the Group Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-4 md:px-6">
            <div class="max-w-3xl mx-auto text-center mb-12">
                <h2 class="text-[clamp(1.8rem,3vw,2.5rem)] font-bold text-deep-blue mb-6">Who We Are</h2>
                <div class="w-20 h-1 bg-primary-green mx-auto mb-8 rounded-full"></div>
            </div>
            
            <div class="max-w-4xl mx-auto">
                <p class="text-lg leading-relaxed mb-8">
                    From a truly global perspective, we source 70 product categories directly from 16 manufacturing countries — eliminating every import hurdle with end-to-end management of customs, inspections, warehousing, and distribution — so that you enjoy a seamless, data-driven supply chain.
                </p>
                <p class="text-lg leading-relaxed">
                    Powered by our TradeInsight platform, you gain real-time visibility into every shipment and full-chain carbon-footprint tracking, while our expert team and expansive network of vetted factories navigate complex regulations on your behalf, delivering reliable, efficient, and transparent sourcing solutions at every step.
                </p>
                
                <div class="mt-12 grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-soft-green p-6 rounded-xl text-center">
                        <i class="fa fa-globe text-primary-green text-3xl mb-4"></i>
                        <h3 class="font-semibold text-deep-blue mb-2">Global Reach</h3>
                        <p>16 manufacturing countries with direct sourcing capabilities</p>
                    </div>
                    <div class="bg-soft-green p-6 rounded-xl text-center">
                        <i class="fa fa-database text-primary-green text-3xl mb-4"></i>
                        <h3 class="font-semibold text-deep-blue mb-2">Data-Driven</h3>
                        <p>Real-time visibility through our TradeInsight platform</p>
                    </div>
                    <div class="bg-soft-green p-6 rounded-xl text-center">
                        <i class="fa fa-leaf text-primary-green text-3xl mb-4"></i>
                        <h3 class="font-semibold text-deep-blue mb-2">Sustainable</h3>
                        <p>Full-chain carbon-footprint tracking and eco-friendly solutions</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Vision & Mission Section -->
    <section class="py-20 bg-soft-green">
        <div class="container mx-auto px-4 md:px-6">
            <div class="max-w-3xl mx-auto text-center mb-12">
                <h2 class="text-[clamp(1.8rem,3vw,2.5rem)] font-bold text-deep-blue mb-6">Our Vision &amp; Mission</h2>
                <div class="w-20 h-1 bg-primary-green mx-auto mb-8 rounded-full"></div>
            </div>
            
            <div class="max-w-4xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-10">
                <div class="bg-white p-8 rounded-xl shadow-subtle">
                    <div class="w-12 h-12 bg-primary-green/20 rounded-full flex items-center justify-center mb-6">
                        <i class="fa fa-eye text-primary-green text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-deep-blue mb-4">Our Vision</h3>
                    <p class="text-neutral-gray leading-relaxed">
                        To be the world's most trusted partner for sustainable and intelligent supply chain solutions, setting new standards in transparency and responsibility.
                    </p>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-subtle">
                    <div class="w-12 h-12 bg-primary-green/20 rounded-full flex items-center justify-center mb-6">
                        <i class="fa fa-bullseye text-primary-green text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-deep-blue mb-4">Our Mission</h3>
                    <p class="text-neutral-gray leading-relaxed">
                        We empower businesses with eco-friendly products, data-driven platforms, and global logistics expertise — creating measurable impact for people, businesses, and the planet.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Our Brands Section -->
    <section id="brands" class="py-20 bg-white">
        <div class="container mx-auto px-4 md:px-6">
            <div class="max-w-3xl mx-auto text-center mb-16">
                <h2 class="text-[clamp(1.8rem,3vw,2.5rem)] font-bold text-deep-blue mb-6">Our Brand Family</h2>
                <div class="w-20 h-1 bg-primary-green mx-auto mb-8 rounded-full"></div>
                <p class="text-lg text-neutral-gray">
                    A diverse portfolio of brands delivering innovative solutions across the supply chain ecosystem.
                </p>
            </div>
            
            <!-- Product Brands Category -->
            <div class="mb-16">
                <h3 class="text-2xl font-semibold text-deep-blue mb-8 pl-4 md:pl-0 border-l-4 border-primary-green">Product Brands</h3>
                
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Product Brand 1: Supro -->
                    <div class="bg-white rounded-xl shadow-card overflow-hidden transition-custom hover:shadow-lg hover:translate-y-[-5px] group">
                        <div class="h-40 bg-primary-green/10 flex items-center justify-center">
                            <span class="text-deep-blue font-bold text-2xl group-hover:text-primary-green transition-custom">Supro™</span>
                        </div>
                        <div class="p-6">
                            <p class="text-neutral-gray mb-6">
                                Premium quality paper products for commercial and industrial use.
                            </p>
                            <a href="mailto:info@supremeone.com" class="inline-flex items-center text-primary-green font-medium hover:text-deep-blue transition-custom">
                                Contact Us
                                <i class="fa fa-arrow-right ml-2 text-sm"></i>
                            </a>
                        </div>
                    </div>
                    
                    <!-- Product Brand 2: CaterStyle -->
                    <div class="bg-white rounded-xl shadow-card overflow-hidden transition-custom hover:shadow-lg hover:translate-y-[-5px] group">
                        <div class="h-40 bg-primary-green/10 flex items-center justify-center">
                            <span class="text-deep-blue font-bold text-2xl group-hover:text-primary-green transition-custom">CaterStyle™</span>
                        </div>
                        <div class="p-6">
                            <p class="text-neutral-gray mb-6">
                                Paper towels, tissue, napkins, and food packaging essentials.
                            </p>
                            <a href="https://caterstyle.com" target="_blank" class="inline-flex items-center text-primary-green font-medium hover:text-deep-blue transition-custom">
                                Visit Website
                                <i class="fa fa-arrow-right ml-2 text-sm"></i>
                            </a>
                        </div>
                    </div>
                    
                    <!-- Product Brand 3: EcoStyle -->
                    <div class="bg-white rounded-xl shadow-card overflow-hidden transition-custom hover:shadow-lg hover:translate-y-[-5px] group">
                        <div class="h-40 bg-primary-green/10 flex items-center justify-center">
                            <span class="text-deep-blue font-bold text-2xl group-hover:text-primary-green transition-custom">EcoStyle™</span>
                        </div>
                        <div class="p-6">
                            <p class="text-neutral-gray mb-6">
                                Single-use sustainable solutions and paperboard packaging innovations.
                            </p>
                            <a href="https://caterstyle.com/ecostyle" target="_blank" class="inline-flex items-center text-primary-green font-medium hover:text-deep-blue transition-custom">
                                Visit Website
                                <i class="fa fa-arrow-right ml-2 text-sm"></i>
                            </a>
                        </div>
                    </div>
                    
                    <!-- Product Brand 4: Nature's Source -->
                    <div class="bg-white rounded-xl shadow-card overflow-hidden transition-custom hover:shadow-lg hover:translate-y-[-5px] group">
                        <div class="h-40 bg-primary-green/10 flex items-center justify-center">
                            <span class="text-deep-blue font-bold text-2xl group-hover:text-primary-green transition-custom">Nature's Source™</span>
                        </div>
                        <div class="p-6">
                            <p class="text-neutral-gray mb-6">
                                Earth-friendly, compostable, and recyclable food packaging solutions.
                            </p>
                            <a href="https://www.bynaturessource.com/" target="_blank" class="inline-flex items-center text-primary-green font-medium hover:text-deep-blue transition-custom">
                                Visit Website
                                <i class="fa fa-arrow-right ml-2 text-sm"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Service Brands Category -->
            <div>
                <h3 class="text-2xl font-semibold text-deep-blue mb-8 pl-4 md:pl-0 border-l-4 border-primary-green">Service Brands</h3>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <!-- Service Brand 1: Supreme Source & Supply -->
                    <div class="bg-white rounded-xl shadow-card overflow-hidden transition-custom hover:shadow-lg hover:translate-y-[-5px] group">
                        <div class="h-40 bg-primary-green/10 flex items-center justify-center">
                            <span class="text-deep-blue font-bold text-2xl group-hover:text-primary-green transition-custom">Supreme Source &amp; Supply</span>
                        </div>
                        <div class="p-6">
                            <p class="text-neutral-gray mb-6">
                                Warehousing, logistics &amp; customized distribution services, private label solutions.
                            </p>
                            <a href="https://supremesource.net/" target="_blank" class="inline-flex items-center text-primary-green font-medium hover:text-deep-blue transition-custom">
                                Visit Website
                                <i class="fa fa-arrow-right ml-2 text-sm"></i>
                            </a>
                        </div>
                    </div>
                    
                    <!-- Service Brand 2: TradeInsight -->
                    <div class="bg-white rounded-xl shadow-card overflow-hidden transition-custom hover:shadow-lg hover:translate-y-[-5px] group">
                        <div class="h-40 bg-primary-green/10 flex items-center justify-center">
                            <span class="text-deep-blue font-bold text-2xl group-hover:text-primary-green transition-custom">TradeInsight™</span>
                        </div>
                        <div class="p-6">
                            <p class="text-neutral-gray mb-6">
                                Global trade digital platform with purposeful AI and inventory management.
                            </p>
                            <a href="https://www.tradeinsight.com/" target="_blank" class="inline-flex items-center text-primary-green font-medium hover:text-deep-blue transition-custom">
                                Visit Website
                                <i class="fa fa-arrow-right ml-2 text-sm"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Form Section -->
    <section id="contact" class="py-20 bg-light-gray">
        <div class="container mx-auto px-4 md:px-6">
            <div class="max-w-3xl mx-auto text-center mb-12">
                <h2 class="text-[clamp(1.8rem,3vw,2.5rem)] font-bold text-deep-blue mb-6">Let's Connect</h2>
                <div class="w-20 h-1 bg-primary-green mx-auto mb-8 rounded-full"></div>
                <p class="text-lg text-neutral-gray">
                    Ready to transform your supply chain? Reach out to our team today.
                </p>
            </div>
            
            <div class="max-w-2xl mx-auto bg-white rounded-2xl shadow-card p-8 md:p-10">
                <div class="text-center mb-8">
                    <p class="text-neutral-gray mb-4">You can send us an email directly:</p>
                    <a href="mailto:info@supremeone.com" class="text-primary-green hover:text-deep-blue font-medium transition-custom text-lg flex items-center justify-center">
                        <i class="fa fa-envelope mr-2"></i>
                        info@supremeone.com
                    </a>
                </div>
                
                <p class="text-sm text-neutral-gray mb-6"><span class="text-required-red">*</span> Required fields</p>
                
                <form id="contact-form" class="space-y-6">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div>
                            <label for="name" class="block text-neutral-gray font-medium mb-2">
                                Name <span class="text-required-red">*</span>
                            </label>
                            <input type="text" id="name" name="name" class="w-full px-4 py-3 border border-light-gray rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-green/50 transition-custom" required>
                        </div>
                        <div>
                            <label for="email" class="block text-neutral-gray font-medium mb-2">
                                Your Email <span class="text-required-red">*</span>
                            </label>
                            <input type="email" id="email" name="email" class="w-full px-4 py-3 border border-light-gray rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-green/50 transition-custom" required>
                        </div>
                    </div>
                    
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div>
                            <label for="company" class="block text-neutral-gray font-medium mb-2">
                                Company <span class="text-required-red">*</span>
                            </label>
                            <input type="text" id="company" name="company" class="w-full px-4 py-3 border border-light-gray rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-green/50 transition-custom" required>
                        </div>
                        <div>
                            <label for="phone" class="block text-neutral-gray font-medium mb-2">
                                Phone
                            </label>
                            <input type="tel" id="phone" name="phone" class="w-full px-4 py-3 border border-light-gray rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-green/50 transition-custom">
                        </div>
                    </div>
                    
                    <div>
                        <label for="message" class="block text-neutral-gray font-medium mb-2">
                            Message <span class="text-required-red">*</span>
                        </label>
                        <textarea id="message" name="message" rows="5" class="w-full px-4 py-3 border border-light-gray rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-green/50 transition-custom" required></textarea>
                    </div>
                    
                    <div class="text-center">
                        <button type="button" onclick="sendEmail()" class="bg-primary-green hover:bg-primary-green/90 text-white font-medium py-3 px-8 rounded-full shadow-subtle transition-custom transform hover:-translate-y-1">
                            Send Message
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-deep-blue text-white py-12 md:py-16">
        <div class="container mx-auto px-4 md:px-6">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-10">
                <div class="md:col-span-1">
                    <div class="mb-6">
                        <span class="text-white font-bold text-2xl">SupremeONE</span>
                    </div>
                    <p class="text-blue-100 mb-6">
                        Empowering global businesses with data-driven, sustainable supply chain solutions.
                    </p>
                    <div class="flex space-x-4">
                        <a href="https://www.linkedin.com/company/supreme-source-supply/?viewAsMember=true" target="_blank" class="text-white hover:text-primary-green transition-colors duration-300">
                            <i class="fa fa-linkedin-square text-2xl"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h3 class="font-semibold text-lg mb-4">Quick Links</h3>
                    <ul class="space-y-2">
                        <li><a href="#about" class="text-blue-100 hover:text-primary-green transition-custom">About Us</a></li>
                        <li><a href="#brands" class="text-blue-100 hover:text-primary-green transition-custom">Our Brands</a></li>
                        <li><a href="#" class="text-blue-100 hover:text-primary-green transition-custom">Careers</a></li>
                        <li><a href="#contact" class="text-blue-100 hover:text-primary-green transition-custom">Contact</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="font-semibold text-lg mb-4">Our Brands</h3>
                    <ul class="space-y-2">
                        <li><a href="mailto:info@supremeone.com" class="text-blue-100 hover:text-primary-green transition-custom">Supro™</a></li>
                        <li><a href="https://caterstyle.com" target="_blank" class="text-blue-100 hover:text-primary-green transition-custom">CaterStyle™</a></li>
                        <li><a href="https://caterstyle.com/ecostyle" target="_blank" class="text-blue-100 hover:text-primary-green transition-custom">EcoStyle™</a></li>
                        <li><a href="https://supremesource.net/" target="_blank" class="text-blue-100 hover:text-primary-green transition-custom">Supreme Source</a></li>
                        <li><a href="https://www.bynaturessource.com/" target="_blank" class="text-blue-100 hover:text-primary-green transition-custom">Nature's Source™</a></li>
                        <li><a href="https://www.tradeinsight.com/" target="_blank" class="text-blue-100 hover:text-primary-green transition-custom">TradeInsight™</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="font-semibold text-lg mb-4">Contact</h3>
                    <ul class="space-y-3">
                        <li class="flex items-start">
                            <i class="fa fa-map-marker mt-1 mr-3 text-primary-green"></i>
                            <span class="text-blue-100">4260 N Harbor Blvd, Fullerton<br>CA 92835</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fa fa-envelope mr-3 text-primary-green"></i>
                            <a href="mailto:info@supremeone.com" class="text-blue-100 hover:text-primary-green transition-custom">info@supremeone.com</a>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-blue-800 mt-10 pt-6 text-center text-blue-200 text-sm">
                <p>© 2025 SupremeONE. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- JavaScript -->
    <script>
        // Mobile Menu Toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        
        // Navbar Scroll Effect
        const navbar = document.getElementById('navbar');
        
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                navbar.classList.add('py-2');
                navbar.classList.remove('py-4');
                navbar.classList.add('shadow-md');
            } else {
                navbar.classList.add('py-4');
                navbar.classList.remove('py-2');
                navbar.classList.remove('shadow-md');
            }
        });
        
        // Smooth Scrolling for Anchor Links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    if (!mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                }
            });
        });
        
        // Email functionality with validation
        function sendEmail() {
            // Get form values
            const name = document.getElementById('name').value.trim();
            const email = document.getElementById('email').value.trim();
            const company = document.getElementById('company').value.trim();
            const phone = document.getElementById('phone').value.trim();
            const message = document.getElementById('message').value.trim();
            
            // Validate required fields
            if (!name || !email || !company || !message) {
                alert('Please fill in all required fields marked with an asterisk (*)');
                return;
            }
            
            // Validate email format
            const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            if (!emailRegex.test(email)) {
                alert('Please enter a valid email address');
                return;
            }
            
            // Create email subject and body
            const subject = `Message from ${name} - ${company}`;
            let body = `Name: ${name}\n`;
            body += `Email: ${email}\n`;
            body += `Company: ${company}\n`;
            if (phone) body += `Phone: ${phone}\n`;
            body += `\nMessage:\n${message}`;
            
            // Encode for mailto link
            const encodedSubject = encodeURIComponent(subject);
            const encodedBody = encodeURIComponent(body);
            
            // Open default email client
            window.location.href = `mailto:info@supremeone.com?subject=${encodedSubject}&body=${encodedBody}`;
        }
        
        // Add animation on scroll
        const animateOnScroll = () => {
            const elements = document.querySelectorAll('.bg-white.rounded-xl.shadow-card, .bg-soft-green.p-6.rounded-xl');
            
            elements.forEach(element => {
                const elementPosition = element.getBoundingClientRect().top;
                const windowHeight = window.innerHeight;
                
                if (elementPosition < windowHeight - 100) {
                    element.classList.add('opacity-100', 'translate-y-0');
                    element.classList.remove('opacity-0', 'translate-y-8');
                }
            });
        };
        
        // Initialize elements with animation classes
        document.querySelectorAll('.bg-white.rounded-xl.shadow-card, .bg-soft-green.p-6.rounded-xl').forEach(element => {
            element.classList.add('transition-all', 'duration-700', 'opacity-0', 'translate-y-8');
        });
        
        // Run animation on load and scroll
        window.addEventListener('load', animateOnScroll);
        window.addEventListener('scroll', animateOnScroll);
    </script>


    </body></html>
    
