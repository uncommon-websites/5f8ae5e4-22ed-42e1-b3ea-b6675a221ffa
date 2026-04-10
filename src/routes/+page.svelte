<script>
  import { onMount } from 'svelte';
</script>

<!-- HERO SECTION (USER APPROVED) -->
<div class="w-full bg-dot-grid text-[#111827] font-sans antialiased min-h-screen flex flex-col overflow-x-hidden">
  
  <!-- HERO SECTION -->
  <section class="relative w-full pt-32 pb-20 md:pt-48 md:pb-32 px-6 border-b border-gray-200 grid-bg">
    <div class="max-w-7xl mx-auto w-full grid grid-cols-1 lg:grid-cols-2 gap-12 items-start">
      
      <!-- Left Content -->
      <div class="flex flex-col items-start z-10 relative">
        <div class="inline-flex items-center gap-2 bg-white border border-gray-200 rounded-full px-3 py-1 text-xs font-medium text-gray-600 mb-8 shadow-sm">
          <span class="w-2 h-2 rounded-full bg-thoughtful-blue"></span>
          Announcing our $5M round led by General Catalyst,...
        </div>
        
        <h1 class="text-5xl md:text-7xl font-semibold tracking-tight text-black mb-6 leading-[1.1]">
          Intelligence that <br />
          <span class="text-thoughtful-blue relative inline-block">
            Runs
            <!-- Cursor/Underline decoration could go here -->
             <svg class="absolute -bottom-2 left-0 w-full h-3 text-thoughtful-blue opacity-50" viewBox="0 0 100 10" preserveAspectRatio="none">
                <path d="M0 5 Q 50 10 100 5" stroke="currentColor" stroke-width="2" fill="none" />
             </svg>
          </span> 
          Manufacturing Operations
        </h1>
        
        <p class="text-xl text-gray-600 mb-10 max-w-lg leading-relaxed">
          Thoughtful builds artificial intelligence that mimics, optimizes, and automates complex human decisions in manufacturing operations
        </p>
        
        <button class="bg-thoughtful-blue text-white px-6 py-3 rounded-sm font-medium text-sm tracking-wide flex items-center gap-2 hover:bg-blue-700 transition-colors">
          <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M3 11V1L10 6L3 11Z" fill="currentColor"/>
          </svg>
          WATCH VIDEO
        </button>
      </div>

      <!-- Right Visual (Schematic) -->
      <div class="relative w-full h-[500px] lg:h-[600px] lg:-mt-20 lg:-mr-20 hidden md:block">
        <!-- This area needs to be a complex SVG or HTML construction to mimic the schematic -->
        <div class="absolute inset-0 border border-gray-200 bg-white/50 backdrop-blur-sm p-4 relative overflow-hidden rounded-lg shadow-sm">
           <!-- Mock Schematic SVG -->
           <svg class="w-full h-full text-gray-300" viewBox="0 0 800 600">
              <!-- Background Grid Lines -->
              <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
                <path d="M 40 0 L 0 0 0 40" fill="none" stroke="currentColor" stroke-width="0.5" opacity="0.3"/>
              </pattern>
              <rect width="100%" height="100%" fill="url(#grid)" />
              
              <!-- Machine Outline -->
              <g stroke="currentColor" stroke-width="1.5" fill="none">
                 <rect x="200" y="100" width="400" height="300" rx="4" />
                 <rect x="220" y="120" width="100" height="100" />
                 <circle cx="270" cy="170" r="30" />
                 <path d="M350 120 H 580 V 380 H 350 V 120" />
                 
                 <!-- Pipes/Connectors -->
                 <path d="M600 250 H 700" />
                 <path d="M100 250 H 200" />
                 <path d="M400 400 V 500" />
              </g>

              <!-- Blue Annotations -->
              <g class="text-thoughtful-blue" stroke="currentColor" fill="none" stroke-width="1">
                 <rect x="220" y="120" width="100" height="100" stroke-dasharray="4 4" />
                 <text x="220" y="110" fill="currentColor" font-size="10" font-family="monospace">A24729382</text>
                 
                 <rect x="600" y="50" width="50" height="50" />
                 <text x="600" y="45" fill="currentColor" font-size="10" font-family="monospace">219128</text>
                 <line x1="625" y1="100" x2="625" y2="200" stroke-dasharray="2 2" />
              </g>
           </svg>

           <!-- Floating Hugo AI Card -->
           <div class="absolute top-1/3 right-10 bg-[#f0f4ff] border border-thoughtful-blue/30 p-4 rounded shadow-lg max-w-xs font-mono text-xs text-gray-700 z-20">
              <div class="flex justify-between items-center text-thoughtful-blue mb-2 border-b border-thoughtful-blue/10 pb-2">
                 <span>A247293C3</span>
                 <div class="w-3 h-3 border border-current"></div>
              </div>
              <div class="space-y-1">
                 <p>Connecting to ERP... success</p>
                 <p>Reading data from inventory</p>
                 <p class="pl-2 text-blue-600">✦ Hugo AI: <span class="text-gray-700">We have 3 late items</span></p>
                 <p>Thinking...</p>
                 <p class="pl-2 text-blue-600">✦ Hugo AI: <span class="text-gray-700">Follow up with suppliers</span></p>
                 <p class="pl-2 text-blue-600">✦ Hugo AI: <span class="text-gray-700">Increase safety stock by 5</span></p>
              </div>
              
              <!-- Connector Line -->
               <div class="absolute -left-4 top-10 w-4 h-px bg-thoughtful-blue/50"></div>
               <div class="absolute -left-4 top-10 w-1 h-1 bg-thoughtful-blue rounded-full -translate-x-1/2 -translate-y-1/2"></div>
           </div>
        </div>
      </div>
    </div>
  </section>

  <!-- BLUE SECTION -->
  <section class="bg-thoughtful-blue text-white py-24 md:py-32 px-6 relative overflow-hidden grid-bg-blue" id="manifesto">
    <!-- Grid overlay is handled by grid-bg-blue class -->
    
    <div class="max-w-7xl mx-auto w-full grid grid-cols-1 lg:grid-cols-2 gap-16 relative z-10">
      <!-- Left Text -->
      <div>
        <div class="inline-flex items-center gap-2 text-xs font-medium tracking-widest mb-12 uppercase opacity-80">
          <svg width="10" height="10" viewBox="0 0 10 10" fill="currentColor">
             <path d="M5 0L6.5 3.5L10 5L6.5 6.5L5 10L3.5 6.5L0 5L3.5 3.5L5 0Z" />
          </svg>
          About
        </div>

        <div class="space-y-8 text-xl md:text-2xl font-light leading-relaxed opacity-90">
          <p>
            Every few decades, technology reshapes collaboration.
          </p>
          <p>
            Teams once depended on disconnected workflows — knowledge scattered across tools, never compounding.
          </p>
          <p>
            For decades, no software has deeply rethought how collaborative knowledge gets captured, shared, and put into action to drive real productivity.
          </p>
          <p class="font-medium opacity-100">
            Thoughtful aims to change that.
          </p>
          <p class="opacity-70">
            We combine a multiplayer-native chat platform with AI agents and skills, delivering compounding utility through shared context, code execution, and open knowledge for every team.
          </p>
        </div>
      </div>

      <!-- Right Visual (Computer Wireframe) -->
      <div class="relative flex items-center justify-center lg:justify-end">
         <div class="absolute top-0 right-0 text-[200px] font-bold opacity-10 leading-none select-none">00</div>
         
         <!-- Computer SVG -->
         <div class="relative w-full max-w-md aspect-square border border-white/20 rounded p-4">
            <svg viewBox="0 0 400 400" fill="none" stroke="currentColor" class="w-full h-full text-white/80" stroke-width="1">
               <!-- Monitor -->
               <rect x="50" y="50" width="300" height="220" rx="10" />
               <rect x="70" y="70" width="260" height="160" rx="4" />
               <!-- Floppy Drive -->
               <rect x="260" y="240" width="70" height="10" rx="2" />
               <!-- Stand -->
               <path d="M50 270 H 350 V 300 H 50 V 270" />
               <!-- Logo on computer -->
               <rect x="70" y="240" width="20" height="20" rx="2" />
               
               <!-- Keyboard connector -->
               <path d="M300 300 V 320" />
            </svg>
            
            <div class="absolute bottom-4 right-4 text-xs font-mono opacity-50">
               Collective Intelligence [2020s]
            </div>
         </div>
      </div>
    </div>
    
    <!-- Decorative marks -->
    <div class="absolute top-1/2 left-0 w-full h-px border-t border-dashed border-white/20"></div>
    <div class="absolute left-1/2 top-0 h-full w-px border-l border-dashed border-white/20 hidden lg:block"></div>
    
    <!-- Crosshairs -->
    <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 text-white/40 hidden lg:block">+</div>
    <div class="absolute top-1/2 left-6 -translate-y-1/2 text-white/40">+</div>
    <div class="absolute top-1/2 right-6 -translate-y-1/2 text-white/40">+</div>

  </section>

<!-- FEATURES SECTION -->
<section class="bg-white py-24 px-6 border-b border-gray-100" id="features">
  <div class="max-w-7xl mx-auto w-full">
    <div class="mb-14 text-center">
      <h2 class="text-4xl md:text-5xl font-semibold text-[#244BFF] mb-4">How Thoughtful Works</h2>
      <p class="text-lg text-gray-700 max-w-2xl mx-auto">A multiplayer AI workspace that compounds your team’s knowledge and executes real work, not just chat.</p>
    </div>
    <div class="grid md:grid-cols-3 gap-12 mt-16">
      <div class="flex flex-col items-center text-center">
        <div class="mb-4 w-16 h-16 rounded-full bg-[#eaf0ff] flex items-center justify-center">
          <svg width="32" height="32" fill="none" viewBox="0 0 32 32" class="text-[#244BFF]"><circle cx="16" cy="16" r="15" stroke="currentColor" stroke-width="2"/><path d="M10 16h12M16 10v12" stroke="currentColor" stroke-width="2"/></svg>
        </div>
        <h3 class="text-xl font-bold mb-2">Multiplayer-native Chat</h3>
        <p class="text-gray-600">Collaborate in real time with teammates, AI agents, and skills in a single, persistent workspace.</p>
      </div>
      <div class="flex flex-col items-center text-center">
        <div class="mb-4 w-16 h-16 rounded-full bg-[#eaf0ff] flex items-center justify-center">
          <svg width="32" height="32" fill="none" viewBox="0 0 32 32" class="text-[#244BFF]"><rect x="6" y="6" width="20" height="20" rx="4" stroke="currentColor" stroke-width="2"/><path d="M16 10v8M12 16h8" stroke="currentColor" stroke-width="2"/></svg>
        </div>
        <h3 class="text-xl font-bold mb-2">Shared Skills & AI Agents</h3>
        <p class="text-gray-600">Leverage reusable skills and powerful AI agents that understand your team’s context and drive action.</p>
      </div>
      <div class="flex flex-col items-center text-center">
        <div class="mb-4 w-16 h-16 rounded-full bg-[#eaf0ff] flex items-center justify-center">
          <svg width="32" height="32" fill="none" viewBox="0 0 32 32" class="text-[#244BFF]"><path d="M8 24V8l16 8-16 8z" fill="currentColor"/></svg>
        </div>
        <h3 class="text-xl font-bold mb-2">Executable Code & API Integration</h3>
        <p class="text-gray-600">Run code and connect to APIs directly from chat, automating real work and integrating your tools.</p>
      </div>
    </div>
    <div class="grid md:grid-cols-2 gap-12 mt-16">
      <div class="flex flex-col items-center text-center">
        <div class="mb-4 w-16 h-16 rounded-full bg-[#eaf0ff] flex items-center justify-center">
          <svg width="32" height="32" fill="none" viewBox="0 0 32 32" class="text-[#244BFF]"><circle cx="16" cy="16" r="14" stroke="currentColor" stroke-width="2"/><path d="M10 22c4-8 8-8 12 0" stroke="currentColor" stroke-width="2"/></svg>
        </div>
        <h3 class="text-xl font-bold mb-2">Compounding Team Knowledge</h3>
        <p class="text-gray-600">Every message and workflow strengthens your proprietary knowledge base—no more fragmented context.</p>
      </div>
      <div class="flex flex-col items-center text-center">
        <div class="mb-4 w-16 h-16 rounded-full bg-[#eaf0ff] flex items-center justify-center">
          <svg width="32" height="32" fill="none" viewBox="0 0 32 32" class="text-[#244BFF]"><rect x="8" y="8" width="16" height="16" rx="4" stroke="currentColor" stroke-width="2"/><path d="M12 16h8" stroke="currentColor" stroke-width="2"/></svg>
        </div>
        <h3 class="text-xl font-bold mb-2">Open Standards & Secure Privacy</h3>
        <p class="text-gray-600">Thoughtful is built on open standards and puts your team’s privacy and IP ownership first.</p>
      </div>
    </div>
    <div class="mt-16 flex justify-center">
      <div class="w-full md:w-2/3 rounded-lg overflow-hidden shadow-lg border border-[#eaf0ff]">
        <div class="w-full h-64 bg-[#eaf0ff] flex items-center justify-center text-[#244BFF] text-lg">[Image: Teams collaborating with Thoughtful's AI workspace]</div>
      </div>
    </div>
  </div>
</section>

<!-- TESTIMONIALS SECTION -->
<section class="bg-[#f8faff] py-24 px-6 border-b border-gray-100" id="testimonials">
  <div class="max-w-4xl mx-auto">
    <div class="flex flex-col md:flex-row items-center gap-12">
      <div class="w-full md:w-1/2 rounded-lg overflow-hidden shadow border border-[#eaf0ff] mb-8 md:mb-0">
        <div class="w-full h-72 bg-[#eaf0ff] flex items-center justify-center text-[#244BFF] text-lg">[Image: Diverse team using Thoughtful chat platform]</div>
      </div>
      <div class="w-full md:w-1/2">
        <blockquote class="text-2xl leading-relaxed text-gray-900 font-light mb-4">“Thoughtful transformed the way our team collaborates. No more lost context—just instant, actionable knowledge and real AI-powered workflows.”</blockquote>
        <div class="font-semibold text-[#244BFF]">Jordan Lee, Director of Operations<br><span class="text-gray-500 font-normal">Forward-Thinking Tech Company</span></div>
      </div>
    </div>
  </div>
</section>

<!-- CTA SECTION -->
<section class="py-24 px-6 bg-[#244BFF] text-white relative overflow-hidden" id="cta">
  <div class="max-w-5xl mx-auto flex flex-col md:flex-row items-center justify-between gap-12">
    <div class="flex-1">
      <h2 class="text-4xl md:text-5xl font-semibold mb-4">Ready to unify your team’s intelligence?</h2>
      <p class="text-lg mb-8">Start your private AI workspace with Thoughtful. Capture collaborative knowledge, execute code, and empower your team with real AI.</p>
      <button class="bg-white text-[#244BFF] px-8 py-4 font-semibold rounded shadow hover:bg-blue-50 transition">Get Started</button>
    </div>
    <div class="flex-1 max-w-md w-full rounded-lg overflow-hidden shadow-lg border border-white/20">
      <div class="w-full h-64 bg-white/20 flex items-center justify-center text-white text-lg">[Image: Professional using Thoughtful AI workspace]</div>
    </div>
  </div>
</section>

</div>
