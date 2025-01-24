---
title: Home
client_logos:
  - name: "Customer 1"
    logo: "/images/logos/customer-1.png"
  - name: "Customer 2"
    logo: "/images/logos/customer-2.png"
  - name: "Customer 3"
    logo: "/images/logos/customer-3.png"
  - name: "Customer 4"
    logo: "/images/logos/customer-4.png"
  - name: "Customer 5"
    logo: "/images/logos/customer-5.png"
testimonials:
  - name: "Ahmed Salim"
    title: "CTO at TechStartup"
    avatar: "/images/testimonial-1.svg"
    quote: "We built our SaaS website in record time. The performance is incredible, and our users love the modern, clean design."
  - name: "Mohammed Saeed"
    title: "Founder at WebFlow"
    avatar: "/images/testimonial-1.svg"
    quote: "The combination of Hugo and TailwindCSS delivers Advanced Sales Techniques Course. Our website loads instantly, which has significantly improved our conversion rates."
  - name: "Michael Chen"
    title: "Lead Developer at CloudTech"
    avatar: "/images/testimonial-1.svg"
    quote: "This theme made it easy to create a professional SaaS website. The build times are incredibly fast, and the code is clean and maintainable."
---

<!-- my color : #d72323 -->

<!-- {{< hero 
    headline="CH Solutions"
    sub_headline=""
    secondary_button_text="View Courses"
    secondary_button_url="/courses"
    hero_image="/images/ch-logo.png"
    gradient-from="#ffffff"
    gradient-to="#ffffff"
    gradient-angle="180"
>}} -->

<!-- 
{{< client-logos 
  animate="true"
  title="UTM"
  
>}}

{{< features-section 
    title="Modern Features for Modern Websites"
    description="Discover how our theme helps you build fast, beautiful SaaS websites with ease."
>}}

{{< feature
    title="Advanced Sales Techniques Course"
    description="Leverage Hugo's blazing-fast build times and optimized output. Your website loads instantly, providing an exceptional user experience."
    badge="Performance"
    badgeColor="#2563eb"
    image="/images/feature-1.svg"
    buttonText="Learn More"
    buttonLink="/features/performance/"
    features="Sub-second page loads,Optimized assets,Minimal JavaScript,CDN-ready output"
    imagePosition="right"
>}}

{{< feature
    title="Beautiful Design System"
    description="Create stunning user interfaces with our comprehensive design system built on TailwindCSS. Customize everything to match your brand."
    badge="Design"
    badgeColor="#7c3aed"
    image="/images/feature-2.svg"
    buttonText="Learn More"
    buttonLink="/features/design-system/"
    features="Modern UI components,Responsive design,Custom typography,Flexible layouts"
    imagePosition="left"
>}}

{{< feature
    title="Developer Experience"
    description="Enjoy a seamless development experience with hot reload, component-based architecture, and clean, maintainable code."
    badge="Development"
    badgeColor="#16a34a"
    image="/images/feature-3.svg"
    buttonText="Learn More"
    buttonLink="/features/developer-experience/"
    features="Component system,Easy customization,Clean code,Detailed documentation"
    imagePosition="right"
>}}

{{< /features-section >}}

{{< testimonials 
    title="Trusted by Modern Web Teams"
    description="See how teams are building better websites with our theme."
    animate="true"
    background-color="#f1f5f9"
>}} -->


{{< section-container class="bg-gradient-to-b from-blue-50 via-blue-50 to-white pt-20 pb-32" >}}
    <div class="text-center">
        <h1 class="text-4xl md:text-5xl font-bold mb-6">Clear Horizon Solutions</h1>
        <p class="text-xl text-gray-600 mb-16">
            Unlock your potential with our expertly designed courses and consulting services in business management, marketing, and strategy. Benefit from the knowledge and experience of top university lecturers and industry experts, accessible anytime and anywhere to fit your busy schedule.
        </p>
        <!-- Wrap "Anywhere Anytime" in a span and apply color -->
        <p class="text-xl font-bold mb-16">
            Learn With The Experts <span style="color: #d72323;">Anywhere Anytime</span>
        </p>
        <div class="mb-16">
            <img src="/images/ch-logo.png" alt="Clear Horizon Solutions Logo" class="mx-auto" style="max-width: 100%;"/>
        </div>
        <div class="max-w-3xl mx-auto bg-white rounded-xl shadow-sm p-8">
            <h2 class="text-3xl font-bold mb-4">Our Mission</h2>
            <p class="text-xl text-gray-600">
                Our mission is to empower businesses through expertly tailored courses and consulting services in digital marketing and business growth. We provide invaluable insights from experienced professionals and industry leaders, offering guidance specifically designed to meet your unique needs. Alongside our cutting-edge SaaS solutions, our resources are accessible anytime, seamlessly fitting into your schedule, and enabling you to unlock your full potential, drive progress, and achieve lasting success.
            </p>
        </div>
    </div>
{{< /section-container >}}

{{< section-container class="py-20 bg-gray-50" >}}
    <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">Leadership Team</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            {{< my-team-member 
                name="Dr. Monir Abdullah"
                title="Chief Executive Officer"
                image="/images/company/exec-1.svg"
                academia="https://kku-sa.academia.edu/MonirAbdullah"
                image="/images/team-members/monir-abdullah.png"
            >}}
            {{< my-team-member 
                name="Anas Nabil"
                title="Chief Technology Officer"
                image="/images/company/exec-2.svg"
                instagram="https://www.instagram.com/kdb.kd/"
                image="/images/team-members/anas-nabil.jpg"
            >}}
        </div>
    </div>
{{< /section-container >}}

{{< section-container class="py-20" >}}
    <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">Backed by World-Class Universities</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8 items-center">
            {{< investor-logo name="UTM" image="/images/company/UTM.png" url="https://www.utm.my/">}}
            {{< investor-logo name="Faculty of Economics and Business" image="https://brand.utm.my/wp-content/uploads/sites/21/formidable/6/Azman-Hashim-International-Business-School.jpg" url="https://business.utm.my/">}}
            {{< investor-logo name="OXUS" image="https://oxusuniversity.uz/wp-content/uploads/2024/07/Group-179-1.png" url="https://oxusuniversity.uz/">}}
            {{< investor-logo name="Marketerlek" image="https://marketerlek.com/wp-content/uploads/2024/06/ماركيتيرلك.png" url="https://marketerlek.com/11-english/" >}}
        </div>
    </div>
{{< /section-container >}}

{{< section-container class="py-20 bg-gray-50" >}}
    <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">Company Values</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            {{< value-card 
                title="Innovation First"
                icon="lightbulb"
                description="We constantly push boundaries and embrace new technologies to solve complex challenges."
            >}}
            {{< value-card 
                title="Students Success"
                icon="users"
                description="Our Students' success is our success. We're committed to delivering exceptional value."
            >}}
            {{< value-card 
                title="Transparency"
                icon="eye"
                description="We believe in open communication and building trust through transparency."
            >}}
        </div>
    </div>
{{< /section-container >}}

{{< section-container class="py-20" >}}
    <div class="max-w-6xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-4 gap-8 text-center">
            {{< stat number="2024" label="Founded" >}}
            {{< stat number="50+" label="Team Members" >}}
            {{< stat number="1k+" label="Customers" >}}
            {{< stat number="10K+" label="Annual Revenue" >}}
        </div>
    </div>
{{< /section-container >}}



<!-- {{< cta >}} -->
