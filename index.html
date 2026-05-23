<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agrotech Calculus: Oil Palm Canopy Growth Rate</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #115e59 0%, #064e3b 100%);
        }
    </style>
</head>
<body class="bg-gray-50 font-sans min-h-screen flex flex-col">

    <header class="gradient-bg text-white py-6 px-4 shadow-lg">
        <div class="max-w-6xl mx-auto flex flex-col md:flex-row justify-between items-center gap-4">
            <div>
                <span class="bg-teal-200 text-teal-900 text-xs font-bold px-2.5 py-1 rounded-full uppercase tracking-wider">SFA: Agrotech Module</span>
                <h1 class="text-2xl md:text-3xl font-bold mt-1">Applying Derivatives to Malaysian Oil Palm Phenology</h1>
            </div>
            <div class="text-right text-sm text-teal-100">
                <p>Bioscience Application: <strong>Canopy Development Rate</strong></p>
                <p>Location Context: Carey Island, Selangor Plantation Trial</p>
            </div>
        </div>
    </header>

    <main class="max-w-6xl w-full mx-auto p-4 md:p-6 grid grid-cols-1 lg:grid-cols-3 gap-6 flex-grow">
        
        <div class="lg:col-span-1 space-y-6">
            <div class="bg-white p-5 rounded-2xl shadow-sm border border-gray-100">
                <h2 class="text-lg font-bold text-gray-800 border-b pb-2 mb-3 flex items-center gap-2">
                    🌱 The Bioscience Problem
                </h2>
                <p class="text-sm text-gray-600 leading-relaxed">
                    In modern Malaysian agrotechnology, tracking the <strong>Rate of Canopy Cover (RCC)</strong> is vital. Faster canopy closure smothers competing weeds and maximizes solar radiation interception for photosynthesis. 
                </p>
                <p class="text-sm text-gray-600 mt-2 leading-relaxed">
                    Using realistic data adapted from MPOB (Malaysian Palm Oil Board) growth charts, this app models a young tenera palm's canopy expansion percentage over its first 180 days post-field planting.
                </p>
            </div>

            <div class="bg-white p-5 rounded-2xl shadow-sm border border-gray-100">
                <h2 class="text-lg font-bold text-gray-800 border-b pb-2 mb-3 flex items-center gap-2">
                    🧮 Calculus Framework
                </h2>
                <div class="space-y-4 text-sm text-gray-700">
                    <div>
                        <p class="font-semibold text-gray-500 text-xs uppercase tracking-wider">Canopy Cover Function f(x)</p>
                        <div class="bg-teal-50 text-teal-900 font-mono p-3 rounded-lg text-center font-bold text-base my-1">
                            f(x) = -0.000015x³ + 0.0045x² + 0.1x + 5
                        </div>
                        <p class="text-xs text-gray-500">Yields the total canopy cover % at day <span class="font-mono">x</span>.</p>
                    </div>
                    <div>
                        <p class="font-semibold text-gray-500 text-xs uppercase tracking-wider">First Derivative f'(x)</p>
                        <div class="bg-amber-50 text-amber-950 font-mono p-3 rounded-lg text-center font-bold text-base my-1">
                            f'(x) = -0.000045x² + 0.009x + 0.1
                        </div>
                        <p class="text-xs text-gray-500">Calculates the <em>instantaneous rate of change</em> (growth velocity in % per day).</p>
                    </div>
                </div>
            </div>

            <div class="bg-gray-100 p-4 rounded-xl text-xs text-gray-500 border border-gray-200">
                <p class="font-semibold mb-1">Data Source Framework Reference:</p>
                <p class="italic">"Physiological and growth responses of young oil palm to water stress", Malaysian Palm Oil Board (MPOB) Palm Oil Journal / Agronomy Phenology Framework.</p>
            </div>
        </div>

        <div class="lg:col-span-2 space-y-6">
            <div class="bg-white p-5 rounded-2xl shadow-sm border border-gray-100 flex flex-col justify-between min-h-[400px]">
                <div>
                    <div class="flex justify-between items-start mb-2">
                        <div>
                            <h2 class="text-lg font-bold text-gray-800">Interactive Growth & Derivative Graph</h2>
                            <p class="text-xs text-gray-500">Click anywhere along the chart line to analyze that specific day's growth dynamics.</p>
                        </div>
                        <button onclick="resetAnimation()" class="bg-teal-600 hover:bg-teal-700 text-white text-xs px-3 py-1.5 rounded-lg transition font-medium cursor-pointer">
                            🔄 Replay Animation
                        </button>
                    </div>
                    <div class="relative w-full h-[320px]">
                        <canvas id="canopyChart"></canvas>
                    </div>
                </div>
            </div>

            <div id="feedbackTerminal" class="bg-slate-900 text-slate-100 p-5 rounded-2xl shadow-inner transition-all duration-300 border-l-4 border-amber-500">
                <div id="promptMessage" class="text-center py-4 text-slate-400 text-sm">
                    💡 <span class="italic">Click a point on the chart line above to trigger the Agrotech Calculus breakdown.</span>
                </div>
                <div id="dataContent" class="hidden space-y-3">
                    <div class="flex justify-between border-b border-slate-800 pb-2">
                        <span class="text-xs text-slate-400 font-mono uppercase tracking-wider">Calculus Diagnostic Point</span>
                        <span id="diagnosticDay" class="text-xs font-bold px-2 py-0.5 bg-slate-800 text-amber-400 rounded-md font-mono">Day X</span>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                        <div class="bg-slate-800/50 p-3 rounded-lg">
                            <div class="text-xs text-slate-400">Total Canopy Cover $f(x)$</div>
                            <div class="text-xl font-bold text-teal-400 mt-1" id="valFx">0.0%</div>
                        </div>
                        <div class="bg-slate-800/50 p-3 rounded-lg">
                            <div class="text-xs text-slate-400">Growth Rate $f'(x)$ (Derivative)</div>
                            <div class="text-xl font-bold text-amber-400 mt-1" id="valFprimeX">0.00 %/day</div>
                        </div>
                    </div>
                    <div class="bg-slate-950 p-3 rounded-xl border border-slate-800 mt-2">
                        <span class="text-xs font-bold text-teal-500 uppercase block mb-1">🌿 Layman Agronomist Breakdown:</span>
                        <p id="laymanExplanation" class="text-sm text-slate-300 leading-relaxed"></p>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <footer class="bg-gray-100 text-center py-4 text-xs text-gray-500 border-t border-gray-200 mt-auto">
        <p>Built for SFA: Agrotechnology Undergraduate Studies — Mathematical Biology Integration Demonstration.</p>
    </footer>

    <script>
        let chartInstance = null;
        const totalDays = 180;
        
        // Define the cubic function f(x) for canopy cover percentage
        function f(x) {
            return (-0.000015 * Math.pow(x, 3)) + (0.0045 * Math.pow(x, 2)) + (0.1 * x) + 5;
        }

        // Define the exact mathematical derivative f'(x) 
        function fPrime(x) {
            return (-0.000045 * Math.pow(x, 2)) + (0.009 * x) + 0.1;
        }

        // Generate data structures for the graph
        const labels = [];
        const dataFx = [];
        for (let x = 0; x <= totalDays; x += 5) {
            labels.push(x);
            dataFx.push(f(x).toFixed(2));
        }

        // Initialize and render Chart.js configuration
        function initChart() {
            const ctx = document.getElementById('canopyChart').getContext('2d');
            
            chartInstance = new Chart(ctx, {
                type: 'line',
                data: {
                    labels: labels,
                    datasets: [{
                        label: 'Canopy Cover Area f(x) (%)',
                        data: dataFx,
                        borderColor: '#0d9488',
                        borderWidth: 3,
                        backgroundColor: 'rgba(13, 148, 136, 0.05)',
                        fill: true,
                        tension: 0.2,
                        pointBackgroundColor: '#0d9488',
                        pointHoverRadius: 8,
                        pointHoverBackgroundColor: '#f59e0b',
                        pointHoverBorderColor: '#fff',
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: { display: false }
                    },
                    scales: {
                        x: {
                            title: { display: true, text: 'Days Post-Field Planting (x)', color: '#475569', font: { weight: 'bold' } },
                            grid: { color: '#f1f5f9' }
                        },
                        y: {
                            title: { display: true, text: 'Total Crop Coverage Area (%)', color: '#475569', font: { weight: 'bold' } },
                            min: 0,
                            max: 100,
                            grid: { color: '#f1f5f9' }
                        }
                    },
                    // Handle user interactivity via clicking points on the line
                    onClick: (event, activeElements) => {
                        if (activeElements.length > 0) {
                            const index = activeElements[0].index;
                            const daySelected = labels[index];
                            processDiagnostic(daySelected);
                        }
                    },
                    // Custom entrance animation configuration
                    animation: {
                        duration: 2000,
                        easing: 'easeOutQuart'
                    }
                }
            });
        }

        // Calculate and present the derivative context to the user
        function processDiagnostic(day) {
            const totalCover = f(day).toFixed(2);
            const rateOfGrowth = fPrime(day).toFixed(3);
            
            // Toggle terminal DOM elements
            document.getElementById('promptMessage').classList.add('hidden');
            document.getElementById('dataContent').classList.remove('hidden');
            
            // Inject variables into elements
            document.getElementById('diagnosticDay').innerText = `Day ${day}`;
            document.getElementById('valFx').innerText = `${totalCover}%`;
            document.getElementById('valFprimeX').innerText = `+${rateOfGrowth} %/day`;
            
            // Generate contextual agrotechnology translations based on derivative benchmarks
            let briefText = "";
            if (day <= 45) {
                briefText = `At Day ${day}, the crop is in its early growth lag phase. The derivative is quite low (${rateOfGrowth}% per day), meaning expansion is slow because root architecture is still establishing itself in the soil.`;
            } else if (day > 45 && day <= 120) {
                briefText = `Notice that the derivative reaches near peak velocities around here! The palm is in its exponential vegetative phase. It is putting on foliage at a massive speed of ${rateOfGrowth}% every single day, working aggressively to lock down light capture before competing weeds can take root.`;
            } else {
                briefText = `The derivative is dropping significantly back down toward zero here. The palm's physical frond layers have matured and filled out the allotted field space, causing the growth acceleration rate to level off into the plateau phase.`;
            }
            
            document.getElementById('laymanExplanation').innerText = briefText;
        }

        // Replay button controller logic
        function resetAnimation() {
            if (chartInstance) {
                chartInstance.destroy();
            }
            document.getElementById('promptMessage').classList.remove('hidden');
            document.getElementById('dataContent').classList.add('hidden');
            initChart();
        }

        // Window Lifecycle execution
        window.onload = () => {
            initChart();
        };
    </script>
</body>
</html>
