<!-- Vue d'Analyse Détaillée -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Hinsight Audit - SEO Technical Analysis</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&amp;family=Manrope:wght@700;800&amp;family=JetBrains+Mono&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-primary-fixed-variant": "#653e00",
              "inverse-surface": "#263143",
              "on-secondary-fixed": "#00174b",
              "tertiary": "#006c49",
              "on-tertiary": "#ffffff",
              "tertiary-fixed-dim": "#4edea3",
              "on-secondary": "#ffffff",
              "surface-container-lowest": "#ffffff",
              "surface-container-highest": "#d8e3fb",
              "secondary-container": "#316bf3",
              "error-container": "#ffdad6",
              "on-tertiary-fixed-variant": "#005236",
              "tertiary-container": "#30c88f",
              "surface-container-high": "#dee8ff",
              "inverse-primary": "#ffb95f",
              "primary-fixed": "#ffddb8",
              "primary": "#855300",
              "on-secondary-fixed-variant": "#003ea8",
              "on-primary": "#ffffff",
              "error": "#ba1a1a",
              "background": "#f9f9ff",
              "on-primary-fixed": "#2a1700",
              "surface-container": "#e7eeff",
              "primary-fixed-dim": "#ffb95f",
              "on-error": "#ffffff",
              "secondary": "#0051d5",
              "surface-tint": "#855300",
              "tertiary-fixed": "#6ffbbe",
              "surface-container-low": "#f0f3ff",
              "surface-bright": "#f9f9ff",
              "on-surface-variant": "#534434",
              "surface": "#f9f9ff",
              "on-primary-container": "#613b00",
              "on-tertiary-container": "#004e34",
              "on-error-container": "#93000a",
              "on-surface": "#111c2d",
              "inverse-on-surface": "#ecf1ff",
              "on-background": "#111c2d",
              "surface-variant": "#d8e3fb",
              "on-secondary-container": "#fefcff",
              "outline": "#867461",
              "on-tertiary-fixed": "#002113",
              "surface-dim": "#cfdaf2",
              "primary-container": "#f59e0b",
              "secondary-fixed": "#dbe1ff",
              "secondary-fixed-dim": "#b4c5ff",
              "outline-variant": "#d8c3ad"
            },
            fontFamily: {
              "headline": ["Manrope"],
              "body": ["Inter"],
              "label": ["Inter"],
              "mono": ["JetBrains Mono"]
            },
            borderRadius: {"DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem"},
          },
        },
      }
    </script>
<style>
      .material-symbols-outlined {
        font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
      }
      body {
        background-color: #f9f9ff;
        color: #111c2d;
        font-family: 'Inter', sans-serif;
      }
      .custom-scrollbar::-webkit-scrollbar {
        width: 4px;
        height: 4px;
      }
      .custom-scrollbar::-webkit-scrollbar-track {
        background: transparent;
      }
      .custom-scrollbar::-webkit-scrollbar-thumb {
        background: #d8e3fb;
        border-radius: 10px;
      }
    </style>
</head>
<body class="bg-surface selection:bg-primary-container/30">
<!-- SideNavBar (Authority Source: JSON) -->
<aside class="h-screen w-64 fixed left-0 top-0 bg-[#F9F9FF] border-r border-slate-200 flex flex-col p-4 gap-2 z-40">
<div class="flex items-center gap-3 px-2 mb-8">
<div class="w-8 h-8 bg-primary rounded flex items-center justify-center">
<span class="material-symbols-outlined text-white text-lg">analytics</span>
</div>
<div>
<h1 class="text-lg font-bold text-[#111C2D]">Hinsight Audit</h1>
<p class="text-[10px] uppercase tracking-tighter text-slate-500 font-medium">Technical Ledger</p>
</div>
</div>
<nav class="flex-1 space-y-1">
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] hover:bg-slate-100 transition-colors rounded-md font-medium text-sm" href="#">
<span class="material-symbols-outlined text-xl">dashboard</span>
<span>Dashboard</span>
</a>
<!-- Active Navigation: SEO On-page -->
<a class="flex items-center gap-3 px-3 py-2 text-[#855300] font-bold bg-[#F59E0B]/10 rounded-md text-sm translate-x-1 transition-transform" href="#">
<span class="material-symbols-outlined text-xl">description</span>
<span>SEO On-page</span>
</a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] hover:bg-slate-100 transition-colors rounded-md font-medium text-sm" href="#">
<span class="material-symbols-outlined text-xl">settings_suggest</span>
<span>Technical</span>
</a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] hover:bg-slate-100 transition-colors rounded-md font-medium text-sm" href="#">
<span class="material-symbols-outlined text-xl">speed</span>
<span>Speed</span>
</a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] hover:bg-slate-100 transition-colors rounded-md font-medium text-sm" href="#">
<span class="material-symbols-outlined text-xl">link</span>
<span>Backlinks</span>
</a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] hover:bg-slate-100 transition-colors rounded-md font-medium text-sm" href="#">
<span class="material-symbols-outlined text-xl">article</span>
<span>Content</span>
</a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] hover:bg-slate-100 transition-colors rounded-md font-medium text-sm" href="#">
<span class="material-symbols-outlined text-xl">accessibility_new</span>
<span>Accessibility</span>
</a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] hover:bg-slate-100 transition-colors rounded-md font-medium text-sm" href="#">
<span class="material-symbols-outlined text-xl">query_stats</span>
<span>Core Web Vitals</span>
</a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] hover:bg-slate-100 transition-colors rounded-md font-medium text-sm" href="#">
<span class="material-symbols-outlined text-xl">history</span>
<span>History</span>
</a>
</nav>
<div class="pt-4 border-t border-slate-200">
<div class="flex items-center gap-3 px-2 py-2">
<div class="w-8 h-8 rounded-full bg-slate-200 flex items-center justify-center overflow-hidden">
<img class="w-full h-full object-cover" data-alt="professional portrait of a technical SEO auditor in a bright modern office setting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCE2ByI0dRdQq6DZyqHtIhkKtpGcyOQRGaGMdACIAfm9BX2Pi9H59Vo3g0aib05YuwE_6qaX6-BEnnLLeRFGuJavZSgC45AtFuZhSKWOOV4-I0IAibjxsmX39QBPA81iAUsJv4oIXGqzigQ7tMqvxorfjbcssjrKLGwMDiwybqVPeD01giMcjlsA7Y6Cq6LnfLmFi7yiipjAvswQr853wxvhTHvV6nA4SZgrbVska-njwII468AlT8D5mV3OzTk_303bJ5FOEiIwBI"/>
</div>
<div class="flex-1 min-w-0">
<p class="text-xs font-bold text-on-surface truncate">Admin Account</p>
<p class="text-[10px] text-slate-500 truncate">Premium Tier</p>
</div>
</div>
</div>
</aside>
<!-- TopNavBar (Authority Source: JSON) -->
<header class="fixed top-0 right-0 left-64 bg-[#F9F9FF] z-30 flex justify-between items-center px-6 py-3 border-b border-slate-200">
<div class="flex items-center gap-6">
<h2 class="font-headline font-bold text-lg text-[#111C2D]">Hinsight</h2>
<div class="relative w-72">
<span class="material-symbols-outlined absolute left-3 top-1/2 -translate-y-1/2 text-slate-400 text-lg">search</span>
<input class="w-full bg-surface-container-low border-none rounded-md pl-10 pr-4 py-1.5 text-sm focus:ring-2 focus:ring-secondary/20" placeholder="Search URLs or issues..." type="text"/>
</div>
<nav class="hidden md:flex gap-4">
<a class="text-sm font-medium text-slate-400 hover:text-primary transition-colors" href="#">Settings</a>
</nav>
</div>
<div class="flex items-center gap-4">
<button class="flex items-center gap-2 px-3 py-1.5 bg-primary text-white rounded-md text-sm font-bold hover:opacity-90 transition-opacity">
<span>Export</span>
</button>
<button class="w-10 h-10 flex items-center justify-center text-slate-500 hover:bg-slate-100 rounded-full">
<span class="material-symbols-outlined">notifications</span>
</button>
<button class="w-10 h-10 flex items-center justify-center text-slate-500 hover:bg-slate-100 rounded-full">
<span class="material-symbols-outlined">account_circle</span>
</button>
</div>
</header>
<!-- Main Content -->
<main class="ml-64 mt-16 p-8 pb-16">
<div class="max-w-[1400px] mx-auto space-y-8">
<!-- Page Header -->
<div class="flex flex-col md:flex-row md:items-end justify-between gap-4">
<div>
<nav class="flex items-center gap-2 text-[10px] font-bold text-slate-400 uppercase tracking-widest mb-2">
<span>Audits</span>
<span class="material-symbols-outlined text-[12px]">chevron_right</span>
<span class="text-secondary">On-page SEO</span>
</nav>
<h3 class="text-3xl font-headline font-extrabold text-on-surface tracking-tight">On-page Detailed Analysis</h3>
<p class="text-slate-500 text-sm mt-1">Crawl ID: #782-AF9 | Analyzing 14,204 discovered entities.</p>
</div>
<div class="flex items-center gap-3">
<div class="flex bg-surface-container-low p-1 rounded-lg">
<button class="px-4 py-1.5 bg-white shadow-sm rounded-md text-xs font-bold text-on-surface">Live View</button>
<button class="px-4 py-1.5 text-xs font-medium text-slate-500 hover:text-on-surface">Comparison</button>
</div>
</div>
</div>
<!-- Bento Stats Grid -->
<div class="grid grid-cols-1 md:grid-cols-4 gap-6">
<div class="bg-surface-container-low p-6 rounded-xl space-y-2">
<p class="text-xs font-bold text-slate-500 uppercase tracking-wider">Health Score</p>
<div class="flex items-baseline gap-2">
<span class="text-4xl font-headline font-black text-tertiary">84</span>
<span class="text-xs font-medium text-tertiary-fixed-variant">+2.4% vs last week</span>
</div>
<div class="w-full bg-slate-200 h-1 rounded-full overflow-hidden">
<div class="bg-tertiary w-[84%] h-full"></div>
</div>
</div>
<div class="bg-surface-container-low p-6 rounded-xl space-y-2">
<p class="text-xs font-bold text-slate-500 uppercase tracking-wider">Critical Issues</p>
<div class="flex items-baseline gap-2">
<span class="text-4xl font-headline font-black text-error">24</span>
<span class="text-xs font-medium text-error">-12 total</span>
</div>
<div class="flex gap-1">
<div class="h-2 w-full bg-error rounded-full opacity-20"></div>
<div class="h-2 w-full bg-error rounded-full opacity-40"></div>
<div class="h-2 w-full bg-error rounded-full"></div>
</div>
</div>
<div class="bg-surface-container-low p-6 rounded-xl space-y-2">
<p class="text-xs font-bold text-slate-500 uppercase tracking-wider">Warnings</p>
<div class="flex items-baseline gap-2">
<span class="text-4xl font-headline font-black text-primary">158</span>
<span class="text-xs font-medium text-primary-fixed-variant">+43 new</span>
</div>
<div class="h-1 bg-primary/20 rounded-full"></div>
</div>
<div class="bg-surface-container-low p-6 rounded-xl space-y-2">
<p class="text-xs font-bold text-slate-500 uppercase tracking-wider">Pages Passed</p>
<div class="flex items-baseline gap-2">
<span class="text-4xl font-headline font-black text-on-surface">12.1k</span>
</div>
<div class="h-1 bg-slate-300 rounded-full"></div>
</div>
</div>
<!-- Filters Bar -->
<div class="flex flex-wrap items-center justify-between gap-4 py-4 border-y border-slate-200">
<div class="flex flex-wrap items-center gap-3">
<div class="flex items-center gap-2 px-3 py-1.5 bg-white border border-slate-200 rounded-md cursor-pointer hover:bg-slate-50">
<span class="material-symbols-outlined text-sm text-slate-400">filter_list</span>
<span class="text-xs font-bold">Status: All</span>
</div>
<div class="flex items-center gap-2 px-3 py-1.5 bg-white border border-slate-200 rounded-md cursor-pointer hover:bg-slate-50">
<span class="text-xs font-bold">Priority: High/Medium</span>
</div>
<div class="flex items-center gap-2 px-3 py-1.5 bg-white border border-slate-200 rounded-md cursor-pointer hover:bg-slate-50">
<span class="text-xs font-bold">Category: Meta Tags</span>
<span class="material-symbols-outlined text-sm text-slate-400">close</span>
</div>
<button class="text-xs font-bold text-secondary px-2">Clear all</button>
</div>
<div class="flex items-center gap-4">
<span class="text-[10px] font-bold text-slate-400 uppercase">Showing 1-20 of 1,248 Issues</span>
<div class="flex gap-1">
<button class="w-8 h-8 flex items-center justify-center border border-slate-200 rounded-md hover:bg-slate-100">
<span class="material-symbols-outlined text-sm">chevron_left</span>
</button>
<button class="w-8 h-8 flex items-center justify-center border border-slate-200 rounded-md hover:bg-slate-100">
<span class="material-symbols-outlined text-sm">chevron_right</span>
</button>
</div>
</div>
</div>
<!-- Data Table Container -->
<div class="bg-white rounded-xl overflow-hidden shadow-sm border border-slate-100">
<div class="overflow-x-auto custom-scrollbar">
<table class="w-full border-collapse">
<thead class="bg-slate-50 border-b border-slate-100">
<tr>
<th class="text-left px-6 py-4 text-[10px] font-bold text-slate-400 uppercase tracking-widest w-1/3">URL</th>
<th class="text-left px-6 py-4 text-[10px] font-bold text-slate-400 uppercase tracking-widest">Issue Type</th>
<th class="text-left px-6 py-4 text-[10px] font-bold text-slate-400 uppercase tracking-widest">Status</th>
<th class="text-center px-6 py-4 text-[10px] font-bold text-slate-400 uppercase tracking-widest">Priority</th>
<th class="text-left px-6 py-4 text-[10px] font-bold text-slate-400 uppercase tracking-widest">Action Needed</th>
<th class="px-6 py-4"></th>
</tr>
</thead>
<tbody class="divide-y-0">
<!-- Row 1: Critical -->
<tr class="hover:bg-slate-50 transition-colors group">
<td class="px-6 py-4">
<div class="flex flex-col">
<span class="text-xs font-mono text-secondary truncate max-w-xs">/products/high-performance-precision-instrument</span>
<span class="text-[10px] text-slate-400 mt-0.5">Last indexed: 2h ago</span>
</div>
</td>
<td class="px-6 py-4">
<span class="text-xs font-medium text-on-surface">Duplicate Meta Description</span>
</td>
<td class="px-6 py-4">
<div class="flex items-center gap-2">
<span class="w-1.5 h-1.5 rounded-full bg-error"></span>
<span class="text-xs font-bold text-error">Critical</span>
</div>
</td>
<td class="px-6 py-4 text-center">
<div class="inline-flex items-center justify-center px-2 py-0.5 bg-error/10 text-error rounded text-[10px] font-bold">98</div>
</td>
<td class="px-6 py-4">
<p class="text-xs text-slate-600">Apply unique meta from database ID #992</p>
</td>
<td class="px-6 py-4 text-right">
<button class="opacity-0 group-hover:opacity-100 transition-opacity text-slate-400 hover:text-on-surface">
<span class="material-symbols-outlined text-lg">arrow_forward</span>
</button>
</td>
</tr>
<!-- Row 2: Warning -->
<tr class="hover:bg-slate-50 transition-colors group">
<td class="px-6 py-4">
<div class="flex flex-col">
<span class="text-xs font-mono text-secondary truncate max-w-xs">/blog/modern-ui-patterns-2024</span>
<span class="text-[10px] text-slate-400 mt-0.5">Last indexed: 1d ago</span>
</div>
</td>
<td class="px-6 py-4">
<span class="text-xs font-medium text-on-surface">Missing Alt Text (3 images)</span>
</td>
<td class="px-6 py-4">
<div class="flex items-center gap-2">
<span class="w-1.5 h-1.5 rounded-full bg-primary"></span>
<span class="text-xs font-bold text-primary">Warning</span>
</div>
</td>
<td class="px-6 py-4 text-center">
<div class="inline-flex items-center justify-center px-2 py-0.5 bg-primary/10 text-primary rounded text-[10px] font-bold">64</div>
</td>
<td class="px-6 py-4">
<p class="text-xs text-slate-600">Run auto-captioning or manual entry</p>
</td>
<td class="px-6 py-4 text-right">
<button class="opacity-0 group-hover:opacity-100 transition-opacity text-slate-400 hover:text-on-surface">
<span class="material-symbols-outlined text-lg">arrow_forward</span>
</button>
</td>
</tr>
<!-- Row 3: Pass -->
<tr class="hover:bg-slate-50 transition-colors group">
<td class="px-6 py-4">
<div class="flex flex-col">
<span class="text-xs font-mono text-secondary truncate max-w-xs">/careers/technical-seo-manager</span>
<span class="text-[10px] text-slate-400 mt-0.5">Last indexed: 5m ago</span>
</div>
</td>
<td class="px-6 py-4">
<span class="text-xs font-medium text-on-surface">H1 Structure Compliance</span>
</td>
<td class="px-6 py-4">
<div class="flex items-center gap-2">
<span class="w-1.5 h-1.5 rounded-full bg-tertiary"></span>
<span class="text-xs font-bold text-tertiary">Pass</span>
</div>
</td>
<td class="px-6 py-4 text-center">
<div class="inline-flex items-center justify-center px-2 py-0.5 bg-slate-100 text-slate-400 rounded text-[10px] font-bold">--</div>
</td>
<td class="px-6 py-4">
<p class="text-xs text-slate-400 italic">No action required</p>
</td>
<td class="px-6 py-4 text-right">
<button class="opacity-0 group-hover:opacity-100 transition-opacity text-slate-400 hover:text-on-surface">
<span class="material-symbols-outlined text-lg">arrow_forward</span>
</button>
</td>
</tr>
<!-- Row 4: Critical -->
<tr class="hover:bg-slate-50 transition-colors group">
<td class="px-6 py-4">
<div class="flex flex-col">
<span class="text-xs font-mono text-secondary truncate max-w-xs">/services/consulting-ledger-analysis</span>
<span class="text-[10px] text-slate-400 mt-0.5">Last indexed: 4h ago</span>
</div>
</td>
<td class="px-6 py-4">
<span class="text-xs font-medium text-on-surface">404 Broken Internal Link</span>
</td>
<td class="px-6 py-4">
<div class="flex items-center gap-2">
<span class="w-1.5 h-1.5 rounded-full bg-error"></span>
<span class="text-xs font-bold text-error">Critical</span>
</div>
</td>
<td class="px-6 py-4 text-center">
<div class="inline-flex items-center justify-center px-2 py-0.5 bg-error/10 text-error rounded text-[10px] font-bold">88</div>
</td>
<td class="px-6 py-4">
<p class="text-xs text-slate-600">Update destination to /services/ledger</p>
</td>
<td class="px-6 py-4 text-right">
<button class="opacity-0 group-hover:opacity-100 transition-opacity text-slate-400 hover:text-on-surface">
<span class="material-symbols-outlined text-lg">arrow_forward</span>
</button>
</td>
</tr>
<!-- Row 5: Warning -->
<tr class="hover:bg-slate-50 transition-colors group">
<td class="px-6 py-4">
<div class="flex flex-col">
<span class="text-xs font-mono text-secondary truncate max-w-xs">/solutions/enterprise-audit-tools</span>
<span class="text-[10px] text-slate-400 mt-0.5">Last indexed: 12h ago</span>
</div>
</td>
<td class="px-6 py-4">
<span class="text-xs font-medium text-on-surface">Low Word Count (&lt;200)</span>
</td>
<td class="px-6 py-4">
<div class="flex items-center gap-2">
<span class="w-1.5 h-1.5 rounded-full bg-primary"></span>
<span class="text-xs font-bold text-primary">Warning</span>
</div>
</td>
<td class="px-6 py-4 text-center">
<div class="inline-flex items-center justify-center px-2 py-0.5 bg-primary/10 text-primary rounded text-[10px] font-bold">42</div>
</td>
<td class="px-6 py-4">
<p class="text-xs text-slate-600">Expand section 2 with topical authority data</p>
</td>
<td class="px-6 py-4 text-right">
<button class="opacity-0 group-hover:opacity-100 transition-opacity text-slate-400 hover:text-on-surface">
<span class="material-symbols-outlined text-lg">arrow_forward</span>
</button>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<!-- Action Summary Footer -->
<div class="grid grid-cols-1 md:grid-cols-2 gap-8">
<div class="bg-white p-6 rounded-xl border border-slate-100 shadow-sm">
<h4 class="text-sm font-bold text-on-surface mb-4">Urgent Recommendations</h4>
<div class="space-y-4">
<div class="flex gap-4 p-3 bg-error/5 rounded-lg border-l-4 border-error">
<span class="material-symbols-outlined text-error">priority_high</span>
<div>
<p class="text-xs font-bold text-on-surface">Fix 12 Critical 404s</p>
<p class="text-[10px] text-slate-500 mt-1">High impact on link equity. Estimated crawl budget waste: 14%.</p>
</div>
</div>
<div class="flex gap-4 p-3 bg-primary/5 rounded-lg border-l-4 border-primary">
<span class="material-symbols-outlined text-primary">auto_fix</span>
<div>
<p class="text-xs font-bold text-on-surface">Optimize 158 Image Assets</p>
<p class="text-[10px] text-slate-500 mt-1">Potential LCP improvement of 0.4s. Use WebP conversion.</p>
</div>
</div>
</div>
</div>
<div class="bg-inverse-surface p-6 rounded-xl text-white">
<div class="flex justify-between items-start mb-6">
<div>
<h4 class="text-sm font-bold">Audit Intelligence</h4>
<p class="text-[10px] text-slate-400">AI-driven predictive analysis</p>
</div>
<span class="material-symbols-outlined text-primary-container">lightbulb</span>
</div>
<p class="text-sm leading-relaxed mb-6">
                        Technical debt is increasing in the <span class="text-primary-container font-mono">/products</span> segment. We recommend a full schematic overhaul of meta-data architecture to prevent further cannibalization between instrument categories.
                    </p>
<button class="w-full py-2 bg-primary-container text-on-primary-container text-xs font-bold rounded-md hover:opacity-90 transition-opacity">
                        Generate Automated Fix Script
                    </button>
</div>
</div>
</div>
</main>
<!-- Footer (Authority Source: JSON) -->
<footer class="fixed bottom-0 w-full bg-[#F9F9FF] border-t border-slate-200 flex justify-between items-center px-6 py-2 ml-64 z-50">
<p class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500">Crawl completed 5 mins ago | API: Active | Source: Google Search Console</p>
<div class="flex gap-6">
<a class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500 hover:text-[#855300] transition-opacity" href="#">Help Center</a>
<a class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500 hover:text-[#855300] transition-opacity" href="#">Privacy</a>
<a class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500 hover:text-[#855300] transition-opacity" href="#">Support</a>
</div>
</footer>
</body></html>

<!-- Tableau de Synthèse -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Hinsight Audit - Synthesis Dashboard</title>
<!-- Fonts -->
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&amp;family=Manrope:wght@700;800&amp;family=JetBrains+Mono&amp;display=swap" rel="stylesheet"/>
<!-- Icons -->
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    colors: {
                        "on-primary-fixed-variant": "#653e00",
                        "inverse-surface": "#263143",
                        "on-secondary-fixed": "#00174b",
                        "tertiary": "#006c49",
                        "on-tertiary": "#ffffff",
                        "tertiary-fixed-dim": "#4edea3",
                        "on-secondary": "#ffffff",
                        "surface-container-lowest": "#ffffff",
                        "surface-container-highest": "#d8e3fb",
                        "secondary-container": "#316bf3",
                        "error-container": "#ffdad6",
                        "on-tertiary-fixed-variant": "#005236",
                        "tertiary-container": "#30c88f",
                        "surface-container-high": "#dee8ff",
                        "inverse-primary": "#ffb95f",
                        "primary-fixed": "#ffddb8",
                        "primary": "#855300",
                        "on-secondary-fixed-variant": "#003ea8",
                        "on-primary": "#ffffff",
                        "error": "#ba1a1a",
                        "background": "#f9f9ff",
                        "on-primary-fixed": "#2a1700",
                        "surface-container": "#e7eeff",
                        "primary-fixed-dim": "#ffb95f",
                        "on-error": "#ffffff",
                        "secondary": "#0051d5",
                        "surface-tint": "#855300",
                        "tertiary-fixed": "#6ffbbe",
                        "surface-container-low": "#f0f3ff",
                        "surface-bright": "#f9f9ff",
                        "on-surface-variant": "#534434",
                        "surface": "#f9f9ff",
                        "on-primary-container": "#613b00",
                        "on-tertiary-container": "#004e34",
                        "on-error-container": "#93000a",
                        "on-surface": "#111c2d",
                        "inverse-on-surface": "#ecf1ff",
                        "on-background": "#111c2d",
                        "surface-variant": "#d8e3fb",
                        "on-secondary-container": "#fefcff",
                        "outline": "#867461",
                        "on-tertiary-fixed": "#002113",
                        "surface-dim": "#cfdaf2",
                        "primary-container": "#f59e0b",
                        "secondary-fixed": "#dbe1ff",
                        "secondary-fixed-dim": "#b4c5ff",
                        "outline-variant": "#d8c3ad"
                    },
                    fontFamily: {
                        "headline": ["Manrope"],
                        "body": ["Inter"],
                        "label": ["Inter"],
                        "mono": ["JetBrains Mono"]
                    },
                    borderRadius: {"DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem"},
                },
            },
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .technical-gradient {
            background: linear-gradient(135deg, #855300 0%, #F59E0B 100%);
        }
        .custom-scrollbar::-webkit-scrollbar {
            width: 4px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: transparent;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #d8e3fb;
            border-radius: 10px;
        }
    </style>
</head>
<body class="bg-surface text-on-surface font-body selection:bg-primary-container selection:text-on-primary-container">
<!-- TopNavBar (Shared Component) -->
<header class="flex justify-between items-center w-full px-6 py-3 border-b border-slate-200 dark:border-slate-800 bg-[#F9F9FF] dark:bg-slate-900 docked full-width top-0 z-50 fixed">
<div class="flex items-center gap-8">
<span class="text-xl font-black text-[#111C2D] dark:text-slate-100 tracking-tight font-['Manrope']">Hinsight</span>
<div class="hidden md:flex items-center bg-surface-container-low px-3 py-1.5 rounded-lg border border-outline-variant/20">
<span class="material-symbols-outlined text-on-surface-variant text-sm mr-2">search</span>
<input class="bg-transparent border-none focus:ring-0 text-sm w-64 p-0 placeholder:text-on-surface-variant/50" placeholder="https://example-domain.com" type="text"/>
</div>
</div>
<nav class="flex items-center gap-6">
<a class="font-['Manrope'] font-bold text-lg text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-colors px-2 py-1" href="#">Settings</a>
<div class="h-6 w-px bg-outline-variant/30"></div>
<div class="flex items-center gap-4">
<button class="material-symbols-outlined text-on-surface-variant hover:bg-slate-100 p-2 rounded-full transition-colors">notifications</button>
<button class="material-symbols-outlined text-on-surface-variant hover:bg-slate-100 p-2 rounded-full transition-colors">account_circle</button>
<button class="technical-gradient text-white px-4 py-1.5 rounded-md font-bold text-sm shadow-sm active:opacity-80 duration-150">Export</button>
</div>
</nav>
</header>
<!-- SideNavBar (Shared Component) -->
<aside class="flex flex-col h-screen w-64 fixed left-0 top-0 p-4 gap-2 bg-[#F9F9FF] dark:bg-slate-900 border-r border-slate-200 dark:border-slate-800 pt-20">
<div class="flex items-center gap-3 px-2 mb-6">
<div class="w-10 h-10 bg-primary-container rounded flex items-center justify-center">
<span class="material-symbols-outlined text-on-primary-container" style="font-variation-settings: 'FILL' 1;">analytics</span>
</div>
<div>
<h2 class="text-lg font-bold text-[#111C2D] dark:text-slate-100 font-['Inter'] leading-tight">Hinsight Audit</h2>
<p class="text-[10px] uppercase tracking-widest text-secondary font-bold">Technical Ledger</p>
</div>
</div>
<nav class="flex flex-col gap-1 overflow-y-auto custom-scrollbar pr-1">
<!-- Active State: Dashboard -->
<a class="flex items-center gap-3 px-3 py-2.5 text-[#855300] dark:text-[#F59E0B] font-bold bg-[#F59E0B]/10 rounded-md active:translate-x-1 transition-transform group" href="#">
<span class="material-symbols-outlined text-[20px]" style="font-variation-settings: 'FILL' 1;">dashboard</span>
<span class="text-sm font-['Inter']">Dashboard</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all group" href="#">
<span class="material-symbols-outlined text-[20px]">description</span>
<span class="text-sm font-['Inter']">SEO On-page</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all group" href="#">
<span class="material-symbols-outlined text-[20px]">settings_suggest</span>
<span class="text-sm font-['Inter']">Technical</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all group" href="#">
<span class="material-symbols-outlined text-[20px]">speed</span>
<span class="text-sm font-['Inter']">Speed</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all group" href="#">
<span class="material-symbols-outlined text-[20px]">link</span>
<span class="text-sm font-['Inter']">Backlinks</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all group" href="#">
<span class="material-symbols-outlined text-[20px]">article</span>
<span class="text-sm font-['Inter']">Content</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all group" href="#">
<span class="material-symbols-outlined text-[20px]">accessibility_new</span>
<span class="text-sm font-['Inter']">Accessibility</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all group" href="#">
<span class="material-symbols-outlined text-[20px]">query_stats</span>
<span class="text-sm font-['Inter']">Core Web Vitals</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all group" href="#">
<span class="material-symbols-outlined text-[20px]">history</span>
<span class="text-sm font-['Inter']">History</span>
</a>
</nav>
</aside>
<!-- Main Content Canvas -->
<main class="ml-64 pt-24 pb-16 px-10 bg-surface min-h-screen">
<!-- Dashboard Header & Top Metric -->
<section class="grid grid-cols-12 gap-8 mb-10 items-start">
<!-- Huge Global SEO Score Card -->
<div class="col-span-12 lg:col-span-5 bg-surface-container-lowest p-8 rounded-xl border border-outline-variant/10 shadow-[0_12px_40px_rgba(17,28,45,0.04)] flex flex-col items-center justify-center relative overflow-hidden">
<div class="absolute -right-12 -top-12 w-48 h-48 bg-primary-container/10 rounded-full blur-3xl"></div>
<h3 class="font-headline font-extrabold text-on-surface-variant text-sm tracking-widest uppercase mb-8 self-start">Global SEO Authority Score</h3>
<div class="relative flex items-center justify-center w-64 h-64">
<!-- SVG Gauge Component -->
<svg class="w-full h-full -rotate-90 transform">
<circle class="text-surface-container-high" cx="128" cy="128" fill="transparent" r="110" stroke="currentColor" stroke-width="20"></circle>
<circle class="text-primary-container" cx="128" cy="128" fill="transparent" r="110" stroke="currentColor" stroke-dasharray="691" stroke-dashoffset="138" stroke-linecap="round" stroke-width="20"></circle>
</svg>
<div class="absolute flex flex-col items-center">
<span class="font-headline text-7xl font-extrabold text-on-surface tracking-tighter">82</span>
<span class="font-label text-xs font-bold text-tertiary bg-tertiary/10 px-2 py-0.5 rounded uppercase">+4.2% Monthly</span>
</div>
</div>
<div class="mt-8 grid grid-cols-2 w-full gap-4 pt-6 border-t border-outline-variant/20">
<div>
<p class="text-[10px] text-on-surface-variant font-bold uppercase tracking-wider">Benchmark Rank</p>
<p class="text-lg font-headline font-bold text-on-surface">Tier 1 Elite</p>
</div>
<div class="text-right">
<p class="text-[10px] text-on-surface-variant font-bold uppercase tracking-wider">Target Projection</p>
<p class="text-lg font-headline font-bold text-secondary">90.0 <span class="text-xs">/ 100</span></p>
</div>
</div>
</div>
<!-- KPI Summary Grid -->
<div class="col-span-12 lg:col-span-7">
<div class="grid grid-cols-2 gap-4">
<!-- On-Page KPI -->
<div class="bg-surface-container-low p-6 rounded-lg group hover:bg-surface-container-high transition-colors cursor-default">
<div class="flex justify-between items-start mb-4">
<span class="material-symbols-outlined text-secondary">description</span>
<span class="text-[10px] font-mono font-bold text-on-surface-variant/60">OP-204</span>
</div>
<p class="text-xs font-bold text-on-surface-variant uppercase tracking-wider">On-Page SEO</p>
<p class="text-3xl font-headline font-extrabold text-on-surface mt-1">94%</p>
<div class="w-full bg-surface-container-highest h-1 rounded-full mt-4 overflow-hidden">
<div class="bg-secondary h-full" style="width: 94%"></div>
</div>
</div>
<!-- Technical KPI -->
<div class="bg-surface-container-low p-6 rounded-lg group hover:bg-surface-container-high transition-colors cursor-default">
<div class="flex justify-between items-start mb-4">
<span class="material-symbols-outlined text-error">settings_suggest</span>
<span class="text-[10px] font-mono font-bold text-on-surface-variant/60">TH-912</span>
</div>
<p class="text-xs font-bold text-on-surface-variant uppercase tracking-wider">Technical Health</p>
<p class="text-3xl font-headline font-extrabold text-on-surface mt-1">68%</p>
<div class="w-full bg-surface-container-highest h-1 rounded-full mt-4 overflow-hidden">
<div class="bg-error h-full" style="width: 68%"></div>
</div>
</div>
<!-- Page Speed KPI -->
<div class="bg-surface-container-low p-6 rounded-lg group hover:bg-surface-container-high transition-colors cursor-default">
<div class="flex justify-between items-start mb-4">
<span class="material-symbols-outlined text-primary">speed</span>
<span class="text-[10px] font-mono font-bold text-on-surface-variant/60">PS-055</span>
</div>
<p class="text-xs font-bold text-on-surface-variant uppercase tracking-wider">Page Speed</p>
<div class="flex items-baseline gap-2">
<p class="text-3xl font-headline font-extrabold text-on-surface mt-1">1.2s</p>
<span class="text-xs font-bold text-tertiary">Optimal</span>
</div>
<div class="w-full bg-surface-container-highest h-1 rounded-full mt-4 overflow-hidden">
<div class="bg-primary h-full" style="width: 88%"></div>
</div>
</div>
<!-- Core Web Vitals KPI -->
<div class="bg-surface-container-low p-6 rounded-lg group hover:bg-surface-container-high transition-colors cursor-default">
<div class="flex justify-between items-start mb-4">
<span class="material-symbols-outlined text-tertiary">query_stats</span>
<span class="text-[10px] font-mono font-bold text-on-surface-variant/60">CW-102</span>
</div>
<p class="text-xs font-bold text-on-surface-variant uppercase tracking-wider">Core Web Vitals</p>
<p class="text-3xl font-headline font-extrabold text-on-surface mt-1">Pass</p>
<div class="flex gap-1 mt-4">
<div class="h-1 flex-1 bg-tertiary rounded-full"></div>
<div class="h-1 flex-1 bg-tertiary rounded-full"></div>
<div class="h-1 flex-1 bg-primary-container/30 rounded-full"></div>
</div>
</div>
</div>
</div>
</section>
<!-- Critical Issues & Crawl Overview Bento Section -->
<section class="grid grid-cols-12 gap-8">
<!-- Critical Issues Panel -->
<div class="col-span-12 lg:col-span-8 bg-surface-container-lowest rounded-xl border border-outline-variant/10 shadow-[0_12px_40px_rgba(17,28,45,0.04)] overflow-hidden">
<div class="flex justify-between items-center px-8 py-6 border-b border-outline-variant/10">
<div>
<h3 class="font-headline font-extrabold text-on-surface">Critical Issue Ledger</h3>
<p class="text-xs text-on-surface-variant">Prioritized by business impact and crawl budget</p>
</div>
<div class="flex items-center gap-2">
<span class="w-2 h-2 rounded-full bg-error"></span>
<span class="text-xs font-bold text-error uppercase tracking-wider">3 Urgent Actions</span>
</div>
</div>
<div class="divide-y divide-outline-variant/10">
<!-- Issue Row 1 -->
<div class="px-8 py-5 flex items-center gap-6 hover:bg-surface-container-low transition-colors group">
<div class="w-10 h-10 rounded-md bg-error-container flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-error" style="font-variation-settings: 'FILL' 1;">error</span>
</div>
<div class="flex-grow">
<p class="text-sm font-bold text-on-surface mb-0.5">Missing Meta Descriptions on 24 Core Product Pages</p>
<code class="text-[10px] bg-surface-container-highest px-1.5 py-0.5 rounded font-mono text-on-surface-variant">/products/*</code>
</div>
<div class="text-right shrink-0">
<p class="text-[10px] font-bold text-on-surface-variant uppercase">Estimated Impact</p>
<p class="text-sm font-headline font-extrabold text-error">-12% CTR</p>
</div>
<span class="material-symbols-outlined text-on-surface-variant/30 group-hover:text-secondary transition-colors cursor-pointer">chevron_right</span>
</div>
<!-- Issue Row 2 -->
<div class="px-8 py-5 flex items-center gap-6 hover:bg-surface-container-low transition-colors group">
<div class="w-10 h-10 rounded-md bg-primary-container/20 flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-primary" style="font-variation-settings: 'FILL' 1;">warning</span>
</div>
<div class="flex-grow">
<p class="text-sm font-bold text-on-surface mb-0.5">Broken Canonical Tags in Global Footer</p>
<code class="text-[10px] bg-surface-container-highest px-1.5 py-0.5 rounded font-mono text-on-surface-variant">all_pages.liquid</code>
</div>
<div class="text-right shrink-0">
<p class="text-[10px] font-bold text-on-surface-variant uppercase">Estimated Impact</p>
<p class="text-sm font-headline font-extrabold text-primary">Crawl Bloat</p>
</div>
<span class="material-symbols-outlined text-on-surface-variant/30 group-hover:text-secondary transition-colors cursor-pointer">chevron_right</span>
</div>
<!-- Issue Row 3 -->
<div class="px-8 py-5 flex items-center gap-6 hover:bg-surface-container-low transition-colors group">
<div class="w-10 h-10 rounded-md bg-secondary-container/10 flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-secondary" style="font-variation-settings: 'FILL' 1;">sync_problem</span>
</div>
<div class="flex-grow">
<p class="text-sm font-bold text-on-surface mb-0.5">404 Errors on Legacy Landing Pages</p>
<code class="text-[10px] bg-surface-container-highest px-1.5 py-0.5 rounded font-mono text-on-surface-variant">Redirect Required</code>
</div>
<div class="text-right shrink-0">
<p class="text-[10px] font-bold text-on-surface-variant uppercase">Estimated Impact</p>
<p class="text-sm font-headline font-extrabold text-secondary">UX Friction</p>
</div>
<span class="material-symbols-outlined text-on-surface-variant/30 group-hover:text-secondary transition-colors cursor-pointer">chevron_right</span>
</div>
</div>
<div class="px-8 py-4 bg-surface-container-low text-center">
<button class="text-xs font-bold text-secondary hover:text-primary transition-colors uppercase tracking-widest">View All 18 Issues</button>
</div>
</div>
<!-- Crawl Overview Card -->
<div class="col-span-12 lg:col-span-4 flex flex-col gap-8">
<!-- Live Status -->
<div class="bg-on-surface p-6 rounded-xl text-white flex flex-col justify-between h-48 relative overflow-hidden group">
<div class="z-10">
<div class="flex items-center gap-2 mb-2">
<span class="relative flex h-2 w-2">
<span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-tertiary-fixed-dim opacity-75"></span>
<span class="relative inline-flex rounded-full h-2 w-2 bg-tertiary-fixed-dim"></span>
</span>
<p class="text-[10px] font-bold uppercase tracking-widest opacity-60">Engine Status: Active</p>
</div>
<h4 class="font-headline text-2xl font-bold">Bot Crawler v.4.2</h4>
<p class="text-sm opacity-70 mt-1">Scanning mobile-first assets...</p>
</div>
<div class="z-10 flex justify-between items-end">
<div>
<p class="text-3xl font-headline font-bold">12,840</p>
<p class="text-[10px] uppercase font-bold opacity-50 tracking-tighter">Pages Discovered</p>
</div>
<div class="bg-white/10 p-2 rounded backdrop-blur-md">
<span class="material-symbols-outlined text-white">lan</span>
</div>
</div>
<!-- Decorative Graphic Background -->
<div class="absolute inset-0 bg-[radial-gradient(circle_at_top_right,_var(--tw-gradient-stops))] from-primary/20 via-transparent to-transparent opacity-50"></div>
<div class="absolute bottom-0 right-0 p-4 opacity-10 group-hover:opacity-20 transition-opacity">
<span class="material-symbols-outlined text-8xl">troubleshoot</span>
</div>
</div>
<!-- Coverage Card -->
<div class="bg-surface-container-low p-6 rounded-xl border border-outline-variant/10 flex flex-col flex-grow">
<h4 class="font-headline font-bold text-on-surface mb-6">Search Console Coverage</h4>
<div class="space-y-4">
<div>
<div class="flex justify-between text-[10px] font-bold uppercase mb-1.5">
<span class="text-on-surface-variant">Indexed</span>
<span class="text-on-surface">11.2k</span>
</div>
<div class="w-full bg-surface-container-highest h-1.5 rounded-full">
<div class="bg-tertiary h-full rounded-full" style="width: 87%"></div>
</div>
</div>
<div>
<div class="flex justify-between text-[10px] font-bold uppercase mb-1.5">
<span class="text-on-surface-variant">Excluded</span>
<span class="text-on-surface">1.6k</span>
</div>
<div class="w-full bg-surface-container-highest h-1.5 rounded-full">
<div class="bg-primary-container h-full rounded-full" style="width: 13%"></div>
</div>
</div>
<div>
<div class="flex justify-between text-[10px] font-bold uppercase mb-1.5">
<span class="text-on-surface-variant">Errors</span>
<span class="text-on-surface">14</span>
</div>
<div class="w-full bg-surface-container-highest h-1.5 rounded-full">
<div class="bg-error h-full rounded-full" style="width: 2%"></div>
</div>
</div>
</div>
<div class="mt-auto pt-6 flex items-center justify-between text-xs font-bold text-secondary">
<span>Success Rate: 99.8%</span>
<span class="material-symbols-outlined text-sm">trending_up</span>
</div>
</div>
</div>
</section>
</main>
<!-- Footer (Shared Component) -->
<footer class="fixed bottom-0 w-full flex justify-between items-center px-6 py-2 ml-64 bg-[#F9F9FF] dark:bg-slate-900 border-t border-slate-200 dark:border-slate-800 z-40">
<div class="flex items-center gap-4">
<span class="text-secondary dark:text-secondary font-['Inter'] text-[10px] uppercase tracking-wider font-bold">Crawl completed 5 mins ago | API: Active | Source: Google Search Console</span>
</div>
<div class="flex items-center gap-6">
<a class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500 hover:text-[#855300] transition-opacity duration-200" href="#">Help Center</a>
<a class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500 hover:text-[#855300] transition-opacity duration-200" href="#">Privacy</a>
<a class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500 hover:text-[#855300] transition-opacity duration-200" href="#">Support</a>
</div>
</footer>
</body></html>

<!-- Centre d'Insights & Exports -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Hinsight Audit SEO - Recommendations &amp; Insights</title>
<!-- Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&amp;family=Manrope:wght@700;800&amp;family=JetBrains+Mono&amp;display=swap" rel="stylesheet"/>
<!-- Material Symbols -->
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<!-- Tailwind -->
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    colors: {
                        "on-primary-fixed-variant": "#653e00",
                        "inverse-surface": "#263143",
                        "on-secondary-fixed": "#00174b",
                        "tertiary": "#006c49",
                        "on-tertiary": "#ffffff",
                        "tertiary-fixed-dim": "#4edea3",
                        "on-secondary": "#ffffff",
                        "surface-container-lowest": "#ffffff",
                        "surface-container-highest": "#d8e3fb",
                        "secondary-container": "#316bf3",
                        "error-container": "#ffdad6",
                        "on-tertiary-fixed-variant": "#005236",
                        "tertiary-container": "#30c88f",
                        "surface-container-high": "#dee8ff",
                        "inverse-primary": "#ffb95f",
                        "primary-fixed": "#ffddb8",
                        "primary": "#855300",
                        "on-secondary-fixed-variant": "#003ea8",
                        "on-primary": "#ffffff",
                        "error": "#ba1a1a",
                        "background": "#f9f9ff",
                        "on-primary-fixed": "#2a1700",
                        "surface-container": "#e7eeff",
                        "primary-fixed-dim": "#ffb95f",
                        "on-error": "#ffffff",
                        "secondary": "#0051d5",
                        "surface-tint": "#855300",
                        "tertiary-fixed": "#6ffbbe",
                        "surface-container-low": "#f0f3ff",
                        "surface-bright": "#f9f9ff",
                        "on-surface-variant": "#534434",
                        "surface": "#f9f9ff",
                        "on-primary-container": "#613b00",
                        "on-tertiary-container": "#004e34",
                        "on-error-container": "#93000a",
                        "on-surface": "#111c2d",
                        "inverse-on-surface": "#ecf1ff",
                        "on-background": "#111c2d",
                        "surface-variant": "#d8e3fb",
                        "on-secondary-container": "#fefcff",
                        "outline": "#867461",
                        "on-tertiary-fixed": "#002113",
                        "surface-dim": "#cfdaf2",
                        "primary-container": "#f59e0b",
                        "secondary-fixed": "#dbe1ff",
                        "secondary-fixed-dim": "#b4c5ff",
                        "outline-variant": "#d8c3ad"
                    },
                    fontFamily: {
                        "headline": ["Manrope"],
                        "body": ["Inter"],
                        "label": ["Inter"],
                        "mono": ["JetBrains Mono"]
                    },
                    borderRadius: {"DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem"},
                },
            },
        }
    </script>
<style>
        body { font-family: 'Inter', sans-serif; }
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .header-anchor { font-family: 'Manrope', sans-serif; }
        .card-gradient {
            background: linear-gradient(135deg, #855300 0%, #f59e0b 100%);
        }
        .ambient-shadow {
            box-shadow: 0 12px 40px rgba(17, 28, 45, 0.06);
        }
        .glass-nav {
            background: rgba(249, 249, 255, 0.8);
            backdrop-filter: blur(12px);
        }
    </style>
</head>
<body class="bg-surface text-on-surface">
<!-- SideNavBar (Authority Source: JSON & Design System) -->
<aside class="h-screen w-64 fixed left-0 top-0 bg-[#F9F9FF] dark:bg-slate-900 border-r border-slate-200 dark:border-slate-800 flex flex-col h-full p-4 gap-2 z-50">
<div class="mb-8 px-2">
<div class="flex items-center gap-3">
<div class="w-8 h-8 rounded bg-primary-container flex items-center justify-center text-on-primary">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">analytics</span>
</div>
<div>
<h1 class="text-lg font-bold text-[#111C2D] dark:text-slate-100 leading-tight">Hinsight Audit</h1>
<p class="text-[10px] uppercase tracking-widest text-slate-500 font-bold">Technical Ledger</p>
</div>
</div>
</div>
<nav class="flex-1 space-y-1">
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all rounded-md font-['Inter'] font-medium text-sm" href="#">
<span class="material-symbols-outlined text-[20px]">dashboard</span> Dashboard
            </a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all rounded-md font-['Inter'] font-medium text-sm" href="#">
<span class="material-symbols-outlined text-[20px]">description</span> SEO On-page
            </a>
<a class="flex items-center gap-3 px-3 py-2 text-[#855300] dark:text-[#F59E0B] font-bold bg-[#F59E0B]/10 rounded-md translate-x-1 transition-transform font-['Inter'] text-sm" href="#">
<span class="material-symbols-outlined text-[20px]">settings_suggest</span> Technical
            </a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all rounded-md font-['Inter'] font-medium text-sm" href="#">
<span class="material-symbols-outlined text-[20px]">speed</span> Speed
            </a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all rounded-md font-['Inter'] font-medium text-sm" href="#">
<span class="material-symbols-outlined text-[20px]">link</span> Backlinks
            </a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all rounded-md font-['Inter'] font-medium text-sm" href="#">
<span class="material-symbols-outlined text-[20px]">article</span> Content
            </a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all rounded-md font-['Inter'] font-medium text-sm" href="#">
<span class="material-symbols-outlined text-[20px]">accessibility_new</span> Accessibility
            </a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all rounded-md font-['Inter'] font-medium text-sm" href="#">
<span class="material-symbols-outlined text-[20px]">query_stats</span> Core Web Vitals
            </a>
<a class="flex items-center gap-3 px-3 py-2 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 transition-all rounded-md font-['Inter'] font-medium text-sm" href="#">
<span class="material-symbols-outlined text-[20px]">history</span> History
            </a>
</nav>
<div class="mt-auto pt-4 border-t border-slate-200 dark:border-slate-800">
<div class="bg-surface-container-low p-3 rounded-lg mb-4">
<p class="text-[10px] text-slate-500 uppercase tracking-tighter mb-2">System Status</p>
<div class="flex items-center gap-2">
<div class="w-1.5 h-1.5 rounded-full bg-tertiary"></div>
<span class="text-[11px] font-mono text-tertiary font-medium">API: CONNECTED</span>
</div>
</div>
<button class="w-full flex items-center justify-center gap-2 px-4 py-2 card-gradient text-white rounded-md text-sm font-bold shadow-sm active:opacity-80 transition-opacity">
<span class="material-symbols-outlined text-sm">download</span> Export Report
            </button>
</div>
</aside>
<!-- TopNavBar (Authority Source: JSON & Design System) -->
<header class="fixed top-0 left-64 right-0 glass-nav border-b border-slate-200 dark:border-slate-800 flex justify-between items-center px-6 py-3 z-40">
<div class="flex items-center gap-6">
<h2 class="text-xl font-black text-[#111C2D] dark:text-slate-100 tracking-tight font-['Manrope']">Hinsight</h2>
<div class="relative">
<span class="absolute left-3 top-1/2 -translate-y-1/2 material-symbols-outlined text-slate-400 text-sm">search</span>
<input class="pl-10 pr-4 py-1.5 bg-surface-container-lowest border-outline-variant/20 rounded text-sm w-64 focus:ring-2 focus:ring-secondary-container outline-none transition-all" placeholder="Search Audit Insights..." type="text"/>
</div>
</div>
<div class="flex items-center gap-4">
<nav class="flex items-center gap-6 mr-6 border-r border-slate-200 pr-6">
<a class="text-[#855300] dark:text-[#F59E0B] border-b-2 border-[#855300] font-['Manrope'] font-bold text-sm h-full flex items-center py-1" href="#">Insights</a>
<a class="text-slate-500 hover:text-[#855300] font-['Manrope'] font-bold text-sm transition-colors" href="#">Settings</a>
</nav>
<button class="p-2 text-slate-500 hover:bg-slate-100 rounded-full transition-colors relative">
<span class="material-symbols-outlined">notifications</span>
<span class="absolute top-2 right-2 w-2 h-2 bg-error rounded-full"></span>
</button>
<div class="flex items-center gap-3 ml-2 cursor-pointer group">
<div class="text-right">
<p class="text-xs font-bold text-on-surface">Alex Fischer</p>
<p class="text-[10px] text-slate-500 uppercase">Lead Analyst</p>
</div>
<div class="w-8 h-8 rounded-full bg-surface-container-highest overflow-hidden border border-outline-variant/30">
<img class="w-full h-full object-cover" data-alt="professional portrait of a male data analyst in a clean studio setting with soft lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAXOHsfO4069IWFb0oi3d3TBEPOG452wxQc2mmhe8pb_UF4ywjoyDtLcfV6QlSqe4UHtk7IMVqea7H8mHLwxLHEVwphN6BD-lYLC1Cz0MMOtZYwxOSrZ08NCJqCIy_VKtMvIi52jhHKaxZZIQvTbxqUKdQow71WGJfi20id_JHRZ4Tko23SVBUynZfD9w-jZI9NErtT8MtbJh41SDaR7Ha92_RIzHLiDd34w0iY0BKou-9til07CexfF19xrvReqkAZ50E2UVCrb3E"/>
</div>
</div>
</div>
</header>
<!-- Main Content -->
<main class="ml-64 mt-16 p-10 bg-surface min-h-screen">
<!-- Hero Summary Section -->
<section class="mb-12">
<div class="flex justify-between items-end mb-6">
<div>
<h2 class="text-3xl font-black text-on-surface font-headline tracking-tight mb-2">Recommendation Center</h2>
<p class="text-on-surface-variant max-w-2xl font-body leading-relaxed">We've translated your raw crawl data into 24 actionable business insights. Prioritize high-impact issues to recover organic traffic and improve conversion rates.</p>
</div>
<div class="flex gap-3">
<button class="bg-surface-container-highest text-on-surface px-4 py-2 rounded font-bold text-sm hover:opacity-90 transition-opacity flex items-center gap-2">
<span class="material-symbols-outlined text-sm">filter_list</span> Filter Views
                    </button>
<button class="card-gradient text-white px-5 py-2 rounded font-bold text-sm shadow-md flex items-center gap-2">
<span class="material-symbols-outlined text-sm" style="font-variation-settings: 'FILL' 1;">share</span> Share Report
                    </button>
</div>
</div>
<!-- Bento Grid Stats -->
<div class="grid grid-cols-1 md:grid-cols-4 gap-6">
<div class="bg-surface-container-low p-6 rounded-xl border border-outline-variant/10 ambient-shadow">
<p class="text-[10px] font-bold text-slate-500 uppercase tracking-widest mb-1">Audit Score</p>
<div class="flex items-baseline gap-2">
<span class="text-4xl font-black font-headline text-primary">82</span>
<span class="text-tertiary text-xs font-bold">+4% vs last week</span>
</div>
<div class="w-full bg-surface-container-high h-1.5 rounded-full mt-4 overflow-hidden">
<div class="bg-primary h-full w-[82%]"></div>
</div>
</div>
<div class="bg-surface-container-low p-6 rounded-xl border border-outline-variant/10 ambient-shadow">
<p class="text-[10px] font-bold text-slate-500 uppercase tracking-widest mb-1">Critical Fixes</p>
<span class="text-4xl font-black font-headline text-error">07</span>
<p class="text-xs text-on-surface-variant mt-2">Requires immediate developer focus</p>
</div>
<div class="bg-surface-container-low p-6 rounded-xl border border-outline-variant/10 ambient-shadow">
<p class="text-[10px] font-bold text-slate-500 uppercase tracking-widest mb-1">Est. Revenue Lift</p>
<span class="text-4xl font-black font-headline text-tertiary">$12.4k</span>
<p class="text-xs text-on-surface-variant mt-2">Projected monthly organic growth</p>
</div>
<div class="bg-surface-container-low p-6 rounded-xl border border-outline-variant/10 ambient-shadow">
<p class="text-[10px] font-bold text-slate-500 uppercase tracking-widest mb-1">Crawl Health</p>
<span class="text-4xl font-black font-headline text-secondary">99.2%</span>
<p class="text-xs text-on-surface-variant mt-2">Clean connectivity across all nodes</p>
</div>
</div>
</section>
<!-- Insights Feed -->
<section class="space-y-8">
<div class="flex items-center gap-4 mb-4">
<span class="h-px flex-1 bg-outline-variant/20"></span>
<span class="text-[10px] font-bold text-slate-400 uppercase tracking-[0.2em]">Prioritized Action Items</span>
<span class="h-px flex-1 bg-outline-variant/20"></span>
</div>
<!-- Insight Card 1: Performance -->
<article class="bg-surface-container-lowest rounded-xl border border-outline-variant/5 ambient-shadow overflow-hidden group">
<div class="flex flex-col md:flex-row">
<div class="md:w-1/4 p-6 bg-surface-container-low flex flex-col justify-between">
<div>
<div class="w-10 h-10 rounded-lg bg-primary/10 flex items-center justify-center text-primary mb-4">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">speed</span>
</div>
<h3 class="font-bold text-on-surface font-headline leading-tight">Performance Criticality</h3>
<p class="text-xs text-on-surface-variant mt-1">Core Web Vitals Bottleneck</p>
</div>
<div class="space-y-3 mt-6">
<div class="flex justify-between items-center">
<span class="text-[10px] uppercase font-bold text-slate-500 tracking-tighter">Impact</span>
<span class="px-2 py-0.5 bg-error/10 text-error text-[10px] font-bold rounded">HIGH</span>
</div>
<div class="flex justify-between items-center">
<span class="text-[10px] uppercase font-bold text-slate-500 tracking-tighter">Effort</span>
<span class="px-2 py-0.5 bg-secondary/10 text-secondary text-[10px] font-bold rounded">MEDIUM</span>
</div>
</div>
</div>
<div class="md:w-3/4 p-8">
<div class="flex justify-between items-start mb-4">
<h4 class="text-xl font-bold text-on-surface">Unused JavaScript Bloat on Mobile Index</h4>
<span class="text-xs font-mono text-slate-400">ID: PERF-091</span>
</div>
<p class="text-on-surface-variant mb-6 leading-relaxed">Large JavaScript bundles are delaying main-thread activity by 1.4s. This is causing significant "LCP" delays on mobile, which directly correlates with a 12% higher bounce rate compared to desktop.</p>
<div class="bg-surface-container-low p-5 rounded-lg border border-outline-variant/10">
<div class="flex items-center gap-2 mb-3">
<span class="material-symbols-outlined text-sm text-primary">lightbulb</span>
<span class="text-xs font-bold uppercase tracking-wide text-primary">How to Fix</span>
</div>
<ul class="space-y-2 text-sm text-on-surface-variant list-none">
<li class="flex items-start gap-3">
<span class="text-primary font-bold">01.</span>
<span>Implement <code class="bg-surface-container-highest px-1.5 py-0.5 rounded text-xs font-mono">code-splitting</code> via Webpack or Next.js dynamic imports.</span>
</li>
<li class="flex items-start gap-3">
<span class="text-primary font-bold">02.</span>
<span>Audit third-party scripts (Intercom, Hotjar) and set them to <code class="bg-surface-container-highest px-1.5 py-0.5 rounded text-xs font-mono">defer</code> or load on interaction.</span>
</li>
</ul>
</div>
<div class="mt-6 flex justify-end gap-3">
<button class="text-[10px] font-bold text-on-surface-variant uppercase hover:text-primary transition-colors">View technical breakdown</button>
<button class="px-4 py-2 border border-outline-variant/30 rounded text-xs font-bold hover:bg-surface-container-low transition-colors">Assign to Developer</button>
</div>
</div>
</div>
</article>
<!-- Insight Card 2: Content -->
<article class="bg-surface-container-lowest rounded-xl border border-outline-variant/5 ambient-shadow overflow-hidden group">
<div class="flex flex-col md:flex-row">
<div class="md:w-1/4 p-6 bg-surface-container-low flex flex-col justify-between">
<div>
<div class="w-10 h-10 rounded-lg bg-tertiary/10 flex items-center justify-center text-tertiary mb-4">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">article</span>
</div>
<h3 class="font-bold text-on-surface font-headline leading-tight">Content Strategy</h3>
<p class="text-xs text-on-surface-variant mt-1">Topic Cluster Opportunity</p>
</div>
<div class="space-y-3 mt-6">
<div class="flex justify-between items-center">
<span class="text-[10px] uppercase font-bold text-slate-500 tracking-tighter">Impact</span>
<span class="px-2 py-0.5 bg-tertiary/10 text-tertiary text-[10px] font-bold rounded">HIGH</span>
</div>
<div class="flex justify-between items-center">
<span class="text-[10px] uppercase font-bold text-slate-500 tracking-tighter">Effort</span>
<span class="px-2 py-0.5 bg-primary/10 text-primary text-[10px] font-bold rounded">LOW</span>
</div>
</div>
</div>
<div class="md:w-3/4 p-8">
<div class="flex justify-between items-start mb-4">
<h4 class="text-xl font-bold text-on-surface">Thin Content on Key Conversion Pages</h4>
<span class="text-xs font-mono text-slate-400">ID: CONT-204</span>
</div>
<p class="text-on-surface-variant mb-6 leading-relaxed">Product category pages have less than 150 words of unique content. Google is de-prioritizing these nodes in favor of competitor pages that include detailed FAQ sections and user reviews.</p>
<div class="bg-surface-container-low p-5 rounded-lg border border-outline-variant/10">
<div class="flex items-center gap-2 mb-3">
<span class="material-symbols-outlined text-sm text-primary">lightbulb</span>
<span class="text-xs font-bold uppercase tracking-wide text-primary">How to Fix</span>
</div>
<ul class="space-y-2 text-sm text-on-surface-variant list-none">
<li class="flex items-start gap-3">
<span class="text-primary font-bold">01.</span>
<span>Deploy semantic "User Also Ask" content modules at the bottom of category grids.</span>
</li>
<li class="flex items-start gap-3">
<span class="text-primary font-bold">02.</span>
<span>Inject structured JSON-LD <code class="bg-surface-container-highest px-1.5 py-0.5 rounded text-xs font-mono">FAQPage</code> data to capture rich snippets.</span>
</li>
</ul>
</div>
<div class="mt-6 flex justify-end gap-3">
<button class="text-[10px] font-bold text-on-surface-variant uppercase hover:text-primary transition-colors">Compare with Competitor</button>
<button class="px-4 py-2 border border-outline-variant/30 rounded text-xs font-bold hover:bg-surface-container-low transition-colors">Send to Content Team</button>
</div>
</div>
</div>
</article>
<!-- Insight Card 3: UX -->
<article class="bg-surface-container-lowest rounded-xl border border-outline-variant/5 ambient-shadow overflow-hidden group">
<div class="flex flex-col md:flex-row">
<div class="md:w-1/4 p-6 bg-surface-container-low flex flex-col justify-between">
<div>
<div class="w-10 h-10 rounded-lg bg-secondary/10 flex items-center justify-center text-secondary mb-4">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">touch_app</span>
</div>
<h3 class="font-bold text-on-surface font-headline leading-tight">UX &amp; Accessibility</h3>
<p class="text-xs text-on-surface-variant mt-1">Interactivity Failure</p>
</div>
<div class="space-y-3 mt-6">
<div class="flex justify-between items-center">
<span class="text-[10px] uppercase font-bold text-slate-500 tracking-tighter">Impact</span>
<span class="px-2 py-0.5 bg-secondary/10 text-secondary text-[10px] font-bold rounded">MEDIUM</span>
</div>
<div class="flex justify-between items-center">
<span class="text-[10px] uppercase font-bold text-slate-500 tracking-tighter">Effort</span>
<span class="px-2 py-0.5 bg-tertiary/10 text-tertiary text-[10px] font-bold rounded">VERY LOW</span>
</div>
</div>
</div>
<div class="md:w-3/4 p-8">
<div class="flex justify-between items-start mb-4">
<h4 class="text-xl font-bold text-on-surface">Tap Targets Too Small for Mobile Users</h4>
<span class="text-xs font-mono text-slate-400">ID: UX-551</span>
</div>
<p class="text-on-surface-variant mb-6 leading-relaxed">Secondary navigation links in the footer and sidebar are less than 48px apart. Heatmaps show a high frequency of "mis-clicks" leading to exit sessions on touch devices.</p>
<div class="bg-surface-container-low p-5 rounded-lg border border-outline-variant/10">
<div class="flex items-center gap-2 mb-3">
<span class="material-symbols-outlined text-sm text-primary">lightbulb</span>
<span class="text-xs font-bold uppercase tracking-wide text-primary">How to Fix</span>
</div>
<p class="text-sm text-on-surface-variant leading-relaxed">Update global CSS variables to ensure minimum padding of <code class="bg-surface-container-highest px-1.5 py-0.5 rounded text-xs font-mono">12px</code> around all clickable anchor tags and increase line-height for text clusters in the footer area.</p>
</div>
<div class="mt-6 flex justify-end gap-3">
<button class="px-4 py-2 border border-outline-variant/30 rounded text-xs font-bold hover:bg-surface-container-low transition-colors">Mark as Resolved</button>
</div>
</div>
</div>
</article>
</section>
</main>
<!-- Footer (Authority Source: JSON & Design System) -->
<footer class="fixed bottom-0 w-full bg-[#F9F9FF] dark:bg-slate-900 border-t border-slate-200 dark:border-slate-800 flex justify-between items-center px-6 py-2 ml-64 z-50">
<div class="flex items-center gap-4">
<p class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500">Crawl completed 5 mins ago | API: Active | Source: Google Search Console</p>
</div>
<div class="flex gap-6">
<a class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500 hover:text-[#855300] transition-opacity duration-200" href="#">Help Center</a>
<a class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500 hover:text-[#855300] transition-opacity duration-200" href="#">Privacy</a>
<a class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500 hover:text-[#855300] transition-opacity duration-200" href="#">Support</a>
</div>
</footer>
</body></html>

<!-- Lancement d'Audit -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;700;800&amp;family=Inter:wght@400;500;600&amp;family=JetBrains+Mono&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-primary-fixed-variant": "#653e00",
              "inverse-surface": "#263143",
              "on-secondary-fixed": "#00174b",
              "tertiary": "#006c49",
              "on-tertiary": "#ffffff",
              "tertiary-fixed-dim": "#4edea3",
              "on-secondary": "#ffffff",
              "surface-container-lowest": "#ffffff",
              "surface-container-highest": "#d8e3fb",
              "secondary-container": "#316bf3",
              "error-container": "#ffdad6",
              "on-tertiary-fixed-variant": "#005236",
              "tertiary-container": "#30c88f",
              "surface-container-high": "#dee8ff",
              "inverse-primary": "#ffb95f",
              "primary-fixed": "#ffddb8",
              "primary": "#855300",
              "on-secondary-fixed-variant": "#003ea8",
              "on-primary": "#ffffff",
              "error": "#ba1a1a",
              "background": "#f9f9ff",
              "on-primary-fixed": "#2a1700",
              "surface-container": "#e7eeff",
              "primary-fixed-dim": "#ffb95f",
              "on-error": "#ffffff",
              "secondary": "#0051d5",
              "surface-tint": "#855300",
              "tertiary-fixed": "#6ffbbe",
              "surface-container-low": "#f0f3ff",
              "surface-bright": "#f9f9ff",
              "on-surface-variant": "#534434",
              "surface": "#f9f9ff",
              "on-primary-container": "#613b00",
              "on-tertiary-container": "#004e34",
              "on-error-container": "#93000a",
              "on-surface": "#111c2d",
              "inverse-on-surface": "#ecf1ff",
              "on-background": "#111c2d",
              "surface-variant": "#d8e3fb",
              "on-secondary-container": "#fefcff",
              "outline": "#867461",
              "on-tertiary-fixed": "#002113",
              "surface-dim": "#cfdaf2",
              "primary-container": "#f59e0b",
              "secondary-fixed": "#dbe1ff",
              "secondary-fixed-dim": "#b4c5ff",
              "outline-variant": "#d8c3ad"
            },
            fontFamily: {
              "headline": ["Manrope"],
              "body": ["Inter"],
              "label": ["Inter"],
              "mono": ["JetBrains Mono"]
            },
            borderRadius: {"DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem"},
          },
        },
      }
    </script>
<style>
      .material-symbols-outlined {
        font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
      }
      .glass-effect {
        background: rgba(249, 249, 255, 0.8);
        backdrop-filter: blur(12px);
      }
      .custom-shadow {
        box-shadow: 0 12px 40px rgba(17, 28, 45, 0.06);
      }
      .primary-gradient {
        background: linear-gradient(135deg, #855300 0%, #f59e0b 100%);
      }
    </style>
</head>
<body class="bg-surface font-body text-on-surface antialiased">
<!-- Top Navigation Shell -->
<nav class="flex justify-between items-center w-full px-6 py-3 border-b border-slate-200 dark:border-slate-800 bg-[#F9F9FF] dark:bg-slate-900 docked full-width top-0 z-50">
<div class="flex items-center gap-8">
<span class="text-xl font-black text-[#111C2D] dark:text-slate-100 tracking-tight font-headline">Hinsight</span>
<div class="hidden md:flex items-center gap-6">
<a class="text-[#111C2D] dark:text-slate-400 font-['Manrope'] font-bold text-lg hover:bg-slate-100 dark:hover:bg-slate-800 transition-colors px-3 py-1 rounded" href="#">Settings</a>
</div>
</div>
<div class="flex items-center gap-4">
<div class="relative group">
<span class="material-symbols-outlined text-slate-500 hover:text-primary cursor-pointer">notifications</span>
</div>
<div class="flex items-center gap-2 px-3 py-1.5 rounded-lg border border-outline-variant/20">
<span class="material-symbols-outlined text-slate-500">account_circle</span>
<span class="text-sm font-medium">Technical Ledger</span>
</div>
<button class="primary-gradient text-white px-4 py-2 rounded-lg text-sm font-bold shadow-sm transition-all active:opacity-80">Export</button>
</div>
</nav>
<!-- Sidebar Navigation Shell -->
<aside class="hidden lg:flex flex-col h-screen w-64 fixed left-0 top-0 pt-16 bg-[#F9F9FF] dark:bg-slate-900 border-r border-slate-200 dark:border-slate-800 z-40 p-4 gap-2">
<div class="mb-8 px-2">
<h2 class="text-lg font-bold text-[#111C2D] dark:text-slate-100">Hinsight Audit</h2>
<p class="text-[10px] uppercase tracking-wider text-slate-500">Technical Ledger</p>
</div>
<nav class="space-y-1">
<a class="flex items-center gap-3 px-3 py-2.5 text-[#855300] dark:text-[#F59E0B] font-bold bg-[#F59E0B]/10 rounded-md transition-transform active:translate-x-1" href="#">
<span class="material-symbols-outlined">dashboard</span>
<span class="font-['Inter'] font-medium text-sm">Dashboard</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 rounded-md" href="#">
<span class="material-symbols-outlined">description</span>
<span class="font-['Inter'] font-medium text-sm">SEO On-page</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 rounded-md" href="#">
<span class="material-symbols-outlined">settings_suggest</span>
<span class="font-['Inter'] font-medium text-sm">Technical</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 rounded-md" href="#">
<span class="material-symbols-outlined">speed</span>
<span class="font-['Inter'] font-medium text-sm">Speed</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 rounded-md" href="#">
<span class="material-symbols-outlined">link</span>
<span class="font-['Inter'] font-medium text-sm">Backlinks</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 rounded-md" href="#">
<span class="material-symbols-outlined">article</span>
<span class="font-['Inter'] font-medium text-sm">Content</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 rounded-md" href="#">
<span class="material-symbols-outlined">accessibility_new</span>
<span class="font-['Inter'] font-medium text-sm">Accessibility</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 rounded-md" href="#">
<span class="material-symbols-outlined">query_stats</span>
<span class="font-['Inter'] font-medium text-sm">Core Web Vitals</span>
</a>
<a class="flex items-center gap-3 px-3 py-2.5 text-[#111C2D] dark:text-slate-400 hover:bg-slate-100 dark:hover:bg-slate-800 rounded-md" href="#">
<span class="material-symbols-outlined">history</span>
<span class="font-['Inter'] font-medium text-sm">History</span>
</a>
</nav>
</aside>
<!-- Main Content Canvas -->
<main class="lg:ml-64 pt-16 pb-12 min-h-screen">
<div class="max-w-6xl mx-auto px-6 py-10">
<!-- Hero Section -->
<header class="text-center mb-16">
<div class="inline-flex items-center gap-2 px-3 py-1 bg-surface-container-high rounded-full mb-6">
<span class="w-2 h-2 rounded-full bg-tertiary"></span>
<span class="text-[10px] font-bold uppercase tracking-widest text-tertiary">Engine v4.2 Stable</span>
</div>
<h1 class="text-5xl font-black font-headline text-on-surface mb-6 tracking-tight">Audit with Precision.</h1>
<p class="text-slate-500 max-w-xl mx-auto mb-10 text-lg">Enter a URL to begin a deep-crawl technical analysis of your search performance and SEO architecture.</p>
<!-- URL Input Centerpiece -->
<div class="max-w-3xl mx-auto relative group">
<div class="flex items-center bg-white border border-outline-variant/30 rounded-xl overflow-hidden custom-shadow focus-within:border-secondary transition-all">
<div class="pl-5 pr-3 text-slate-400">
<span class="material-symbols-outlined">language</span>
</div>
<input class="flex-grow py-5 bg-transparent border-none focus:ring-0 text-on-surface font-mono text-sm placeholder:text-slate-300" placeholder="https://your-technical-domain.com" type="text"/>
<div class="pr-3">
<button class="primary-gradient text-white px-8 py-3.5 rounded-lg font-bold text-sm shadow-md flex items-center gap-2 active:scale-95 transition-transform">
<span>Start Audit</span>
<span class="material-symbols-outlined text-lg" style="font-variation-settings: 'FILL' 1;">bolt</span>
</button>
</div>
</div>
<div class="absolute -bottom-8 left-0 right-0 flex justify-center gap-6">
<div class="flex items-center gap-2 text-[10px] uppercase font-bold tracking-widest text-slate-400">
<span class="material-symbols-outlined text-xs">verified</span> JS Rendering: Enabled
                        </div>
<div class="flex items-center gap-2 text-[10px] uppercase font-bold tracking-widest text-slate-400">
<span class="material-symbols-outlined text-xs">devices</span> Agent: Googlebot
                        </div>
</div>
</div>
</header>
<!-- Configuration Bento Grid -->
<section class="grid grid-cols-1 md:grid-cols-12 gap-6 mt-20">
<!-- Left: Crawl Mode Selection -->
<div class="md:col-span-5 flex flex-col gap-6">
<div class="bg-surface-container-low p-6 rounded-xl border border-outline-variant/10">
<h3 class="font-headline font-bold text-lg mb-4 flex items-center gap-2">
<span class="material-symbols-outlined text-primary">analytics</span>
                            Crawl Mode
                        </h3>
<div class="space-y-3">
<!-- Full Scan -->
<label class="relative flex items-center p-4 bg-white rounded-lg border-2 border-secondary cursor-pointer transition-all">
<input checked="" class="hidden" name="crawl_mode" type="radio"/>
<div class="flex-grow">
<span class="block font-bold text-sm">Full Scan</span>
<span class="block text-xs text-slate-500">Comprehensive site-wide architecture analysis.</span>
</div>
<span class="material-symbols-outlined text-secondary" style="font-variation-settings: 'FILL' 1;">check_circle</span>
</label>
<!-- Quick Audit -->
<label class="relative flex items-center p-4 bg-white rounded-lg border border-outline-variant/20 hover:border-outline transition-all cursor-pointer">
<input class="hidden" name="crawl_mode" type="radio"/>
<div class="flex-grow">
<span class="block font-bold text-sm">Quick Audit</span>
<span class="block text-xs text-slate-500">Surface-level crawl (Top 100 pages).</span>
</div>
</label>
<!-- Selective -->
<label class="relative flex items-center p-4 bg-white rounded-lg border border-outline-variant/20 hover:border-outline transition-all cursor-pointer">
<input class="hidden" name="crawl_mode" type="radio"/>
<div class="flex-grow">
<span class="block font-bold text-sm">Selective</span>
<span class="block text-xs text-slate-500">Specific subfolder or regex targeted.</span>
</div>
</label>
</div>
</div>
<div class="bg-surface-container-low p-6 rounded-xl border border-outline-variant/10">
<h3 class="font-headline font-bold text-lg mb-4 flex items-center gap-2">
<span class="material-symbols-outlined text-primary">vpn_key</span>
                            API Connectivity
                        </h3>
<div class="space-y-4">
<div class="relative">
<label class="text-[10px] font-bold uppercase tracking-widest text-slate-400 mb-1 block">Google Search Console API</label>
<input class="w-full bg-white border border-outline-variant/20 rounded-md py-2 px-3 text-xs font-mono focus:ring-secondary focus:border-secondary" placeholder="••••••••••••••••" type="password"/>
</div>
<div class="relative">
<label class="text-[10px] font-bold uppercase tracking-widest text-slate-400 mb-1 block">Custom User-Agent</label>
<select class="w-full bg-white border border-outline-variant/20 rounded-md py-2 px-3 text-xs focus:ring-secondary focus:border-secondary">
<option>Googlebot Smartphone (Mobile First)</option>
<option>Googlebot Desktop</option>
<option>Bingbot</option>
<option>Hinsight Technical Spider</option>
</select>
</div>
</div>
</div>
</div>
<!-- Right: Advanced Parameters -->
<div class="md:col-span-7">
<div class="bg-surface-container-low p-6 rounded-xl border border-outline-variant/10 h-full">
<div class="flex justify-between items-center mb-6">
<h3 class="font-headline font-bold text-lg flex items-center gap-2">
<span class="material-symbols-outlined text-primary">tune</span>
                                Advanced Parameters
                            </h3>
<span class="text-[10px] font-bold bg-secondary/10 text-secondary px-2 py-1 rounded">Advanced Mode</span>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
<div>
<label class="text-[10px] font-bold uppercase tracking-widest text-slate-400 mb-2 block">Inclusion Filters (Regex)</label>
<textarea class="w-full bg-white border border-outline-variant/20 rounded-md p-3 text-xs font-mono focus:ring-secondary focus:border-secondary" placeholder="/products/.*|/collections/.*" rows="4"></textarea>
</div>
<div>
<label class="text-[10px] font-bold uppercase tracking-widest text-slate-400 mb-2 block">Exclusion Rules</label>
<textarea class="w-full bg-white border border-outline-variant/20 rounded-md p-3 text-xs font-mono focus:ring-secondary focus:border-secondary" placeholder="/admin/*|/checkout/*|.*\.pdf$" rows="4"></textarea>
</div>
</div>
<div class="space-y-6">
<div class="flex items-center justify-between p-4 bg-white rounded-lg border border-outline-variant/10">
<div class="flex items-center gap-3">
<span class="material-symbols-outlined text-slate-400">javascript</span>
<div>
<span class="block text-sm font-bold">JavaScript Execution</span>
<span class="block text-xs text-slate-500">Execute client-side scripts to discover dynamic content.</span>
</div>
</div>
<div class="w-10 h-6 bg-tertiary rounded-full relative flex items-center px-1">
<div class="w-4 h-4 bg-white rounded-full translate-x-4"></div>
</div>
</div>
<div class="flex items-center justify-between p-4 bg-white rounded-lg border border-outline-variant/10 opacity-60">
<div class="flex items-center gap-3">
<span class="material-symbols-outlined text-slate-400">imagesmode</span>
<div>
<span class="block text-sm font-bold">Image Alt-Text Audit</span>
<span class="block text-xs text-slate-500">Analyze accessibility and vision-engine compatibility.</span>
</div>
</div>
<div class="w-10 h-6 bg-slate-200 rounded-full relative flex items-center px-1">
<div class="w-4 h-4 bg-white rounded-full"></div>
</div>
</div>
<div class="flex items-center justify-between p-4 bg-white rounded-lg border border-outline-variant/10">
<div class="flex items-center gap-3">
<span class="material-symbols-outlined text-slate-400">history_edu</span>
<div>
<span class="block text-sm font-bold">Store Content Snapshots</span>
<span class="block text-xs text-slate-500">Keep a historical record of DOM states for comparison.</span>
</div>
</div>
<div class="w-10 h-6 bg-tertiary rounded-full relative flex items-center px-1">
<div class="w-4 h-4 bg-white rounded-full translate-x-4"></div>
</div>
</div>
</div>
<div class="mt-8 pt-6 border-t border-outline-variant/10">
<div class="flex gap-4">
<button class="flex-grow py-3 bg-surface-container-highest text-on-surface font-bold text-sm rounded-lg hover:bg-surface-variant transition-colors">Save as Template</button>
<button class="flex-grow py-3 bg-white border border-outline-variant/30 text-on-surface font-bold text-sm rounded-lg hover:bg-slate-50 transition-colors">Clear All</button>
</div>
</div>
</div>
</div>
</section>
</div>
</main>
<!-- Footer Shell -->
<footer class="fixed bottom-0 w-full bg-[#F9F9FF] dark:bg-slate-900 border-t border-slate-200 dark:border-slate-800 flex justify-between items-center px-6 py-2 lg:ml-64 z-50">
<div class="flex items-center gap-4">
<span class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500">Crawl completed 5 mins ago | API: Active | Source: Google Search Console</span>
</div>
<div class="flex items-center gap-6">
<a class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500 hover:text-[#855300] transition-opacity duration-200" href="#">Help Center</a>
<a class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500 hover:text-[#855300] transition-opacity duration-200" href="#">Privacy</a>
<a class="font-['Inter'] text-[10px] uppercase tracking-wider text-slate-500 hover:text-[#855300] transition-opacity duration-200" href="#">Support</a>
</div>
</footer>
</body></html>