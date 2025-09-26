------------

layout: default

title: GST Calculatorlayout: default

description: Calculate GST amounts and base rates for different tax slabs with instant results.

breadcrumbs:title: GST Calculatorlayout: defaultlayout: default

  - name: Home

    url: /breadcrumbs:

  - name: Calculators

    url: /Calc/  - name: Hometitle: GST Calculatortitle: GST Calculator

  - name: GST Calculator

    url: /Calc/GST/    url: /

---

  - name: Calculatorsbreadcrumbs:breadcrumbs:

<div class="mui-hero mui-hero--bleed">

  <div class="mui-hero-content">    url: /Calc/

    <div class="mui-hero-icon">

      <span class="material-icons" style="font-size: 4rem;">receipt_long</span>  - name: GST Calculator  - name: Home  - name: Home

    </div>

    <h1 class="mui-hero-title">GST Calculator</h1>    url: /Calc/GST/

    <p class="mui-hero-subtitle">Calculate GST inclusive/exclusive amounts for all tax slabs</p>

  </div>---    url: /    url: /

</div>



<div class="mui-features-grid" style="grid-template-columns: 1fr 1fr; gap: 2rem; align-items: start;">

  <!-- Calculator Input --><div class="mui-hero mui-hero--bleed">  - name: Calculators  - name: Calculators

  <div class="mui-card">

    <h3>GST Calculator</h3>  <div class="mui-hero-content">

    <p style="margin-bottom: 1.5rem; color: var(--text-secondary);">Enter any value to calculate GST amounts instantly</p>

    <div class="mui-hero-icon">    url: /Calc/    url: /Calc/

    <div style="display: grid; gap: 1.5rem;">

      <!-- 5% GST Rate -->      <span class="material-icons" style="font-size: 4rem;">receipt_long</span>

      <div style="border: 1px solid var(--border-primary); border-radius: var(--mui-radius); padding: 1rem; background: var(--bg-elevated);">

        <h4 style="margin: 0 0 1rem 0; color: var(--accent-primary);">5% GST Rate</h4>    </div>  - name: GST Calculator  - name: GST Calculator

        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 0.75rem;">

          <div>    <h1 class="mui-hero-title">GST Calculator</h1>

            <label for="taxable_5" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text); font-size: 0.875rem;">Taxable Amount (₹)</label>

            <input type="number" id="taxable_5" placeholder="0" min="0" step="0.01"    <p class="mui-hero-subtitle">Calculate GST amounts and base rates for different tax slabs</p>    url: /Calc/GST/    url: /Calc/GST/

                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-primary); color: var(--text);"

                   oninput="calculateGST(5)">  </div>

          </div>

          <div></div>------

            <label for="gst_5" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text); font-size: 0.875rem;">GST Amount (₹)</label>

            <input type="number" id="gst_5" placeholder="0" min="0" step="0.01"

                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-primary); color: var(--text);"

                   oninput="calculateGSTFromTax(5)"><!-- Calculator Section -->

          </div>

          <div style="grid-column: span 2;"><div class="mui-card">

            <label for="total_5" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text); font-size: 0.875rem;">Total Amount (₹)</label>

            <input type="number" id="total_5" placeholder="0" min="0" step="0.01"  <div class="mui-container"><div class="mui-hero mui-hero--bleed"><div class="mui-hero mui-hero--bleed">

                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-primary); color: var(--text);"

                   oninput="calculateGSTFromTotal(5)">    <h2 class="mui-section-title">GST Calculator</h2>

          </div>

        </div>    <p class="mui-text-center">Type a value in any of the following fields to calculate GST amounts:</p>  <div class="mui-hero-content">  <div class="mui-hero-content">

      </div>



      <!-- 12% GST Rate -->

      <div style="border: 1px solid var(--border-primary); border-radius: var(--mui-radius); padding: 1rem; background: var(--bg-elevated);">    <div class="mui-calculator-grid">    <div class="mui-hero-icon">    <div class="mui-hero-icon">

        <h4 style="margin: 0 0 1rem 0; color: var(--accent-primary);">12% GST Rate</h4>

        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 0.75rem;">      <div class="mui-calculator-header">

          <div>

            <label for="taxable_12" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text); font-size: 0.875rem;">Taxable Amount (₹)</label>        <div>Taxable Amount</div>      <span class="material-icons" style="font-size: 4rem;">receipt_long</span>      <span class="material-icons" style="font-size: 4rem;">receipt_long</span>

            <input type="number" id="taxable_12" placeholder="0" min="0" step="0.01"

                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-primary); color: var(--text);"        <div>Tax Rate</div>

                   oninput="calculateGST(12)">

          </div>        <div>Tax Amount</div>    </div>    </div>

          <div>

            <label for="gst_12" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text); font-size: 0.875rem;">GST Amount (₹)</label>        <div>Total Amount</div>

            <input type="number" id="gst_12" placeholder="0" min="0" step="0.01"

                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-primary); color: var(--text);"      </div>    <h1 class="mui-hero-title">GST Calculator</h1>    <h1 class="mui-hero-title">GST Calculator</h1>

                   oninput="calculateGSTFromTax(12)">

          </div>

          <div style="grid-column: span 2;">

            <label for="total_12" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text); font-size: 0.875rem;">Total Amount (₹)</label>      <!-- 5% GST -->    <p class="mui-hero-subtitle">Calculate GST amounts and base rates for different tax slabs</p>    <p class="mui-hero-subtitle">Calculate GST amounts and base rates for different tax slabs</p>

            <input type="number" id="total_12" placeholder="0" min="0" step="0.01"

                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-primary); color: var(--text);"      <div class="mui-calculator-row">

                   oninput="calculateGSTFromTotal(12)">

          </div>        <input id="5_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 5)" class="gst-input">  </div>  </div>

        </div>

      </div>        <div class="mui-calculator-label">5%</div>



      <!-- 18% GST Rate -->        <input id="5_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .05, 5)" class="gst-input"></div></div>

      <div style="border: 1px solid var(--border-primary); border-radius: var(--mui-radius); padding: 1rem; background: var(--bg-elevated);">

        <h4 style="margin: 0 0 1rem 0; color: var(--accent-primary);">18% GST Rate</h4>        <input id="5_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.05, 5)" class="gst-input">

        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 0.75rem;">

          <div>      </div>

            <label for="taxable_18" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text); font-size: 0.875rem;">Taxable Amount (₹)</label>

            <input type="number" id="taxable_18" placeholder="0" min="0" step="0.01"

                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-primary); color: var(--text);"

                   oninput="calculateGST(18)">      <!-- 12% GST --><!-- Calculator Section --><!-- Calculator Section -->

          </div>

          <div>      <div class="mui-calculator-row">

            <label for="gst_18" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text); font-size: 0.875rem;">GST Amount (₹)</label>

            <input type="number" id="gst_18" placeholder="0" min="0" step="0.01"        <input id="12_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 12)" class="gst-input"><div class="mui-card"><div class="mui-card">

                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-primary); color: var(--text);"

                   oninput="calculateGSTFromTax(18)">        <div class="mui-calculator-label">12%</div>

          </div>

          <div style="grid-column: span 2;">        <input id="12_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .12, 12)" class="gst-input">  <div class="mui-container">  <div class="mui-container">

            <label for="total_18" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text); font-size: 0.875rem;">Total Amount (₹)</label>

            <input type="number" id="total_18" placeholder="0" min="0" step="0.01"        <input id="12_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.12, 12)" class="gst-input">

                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-primary); color: var(--text);"

                   oninput="calculateGSTFromTotal(18)">      </div>    <h2 class="mui-section-title">GST Calculator</h2>    <h2 class="mui-section-title">GST Calculator</h2>

          </div>

        </div>

      </div>

      <!-- 18% GST -->    <p class="mui-text-center">Type a value in any of the following fields to calculate GST amounts:</p>    <p class="mui-text-center">Type a value in any of the following fields to calculate GST amounts:</p>

      <!-- 28% GST Rate -->

      <div style="border: 1px solid var(--border-primary); border-radius: var(--mui-radius); padding: 1rem; background: var(--bg-elevated);">      <div class="mui-calculator-row">

        <h4 style="margin: 0 0 1rem 0; color: var(--accent-primary);">28% GST Rate</h4>

        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 0.75rem;">        <input id="18_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 18)" class="gst-input">

          <div>

            <label for="taxable_28" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text); font-size: 0.875rem;">Taxable Amount (₹)</label>        <div class="mui-calculator-label">18%</div>

            <input type="number" id="taxable_28" placeholder="0" min="0" step="0.01"

                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-primary); color: var(--text);"        <input id="18_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .18, 18)" class="gst-input">    <div class="mui-calculator-grid">    <div class="mui-calculator-grid">

                   oninput="calculateGST(28)">

          </div>        <input id="18_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.18, 18)" class="gst-input">

          <div>

            <label for="gst_28" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text); font-size: 0.875rem;">GST Amount (₹)</label>      </div>      <div class="mui-calculator-header">      <div class="mui-calculator-header">

            <input type="number" id="gst_28" placeholder="0" min="0" step="0.01"

                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-primary); color: var(--text);"

                   oninput="calculateGSTFromTax(28)">

          </div>      <!-- 28% GST -->        <div>Taxable Amount</div>        <div>Taxable Amount</div>

          <div style="grid-column: span 2;">

            <label for="total_28" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text); font-size: 0.875rem;">Total Amount (₹)</label>      <div class="mui-calculator-row">

            <input type="number" id="total_28" placeholder="0" min="0" step="0.01"

                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-primary); color: var(--text);"        <input id="28_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 28)" class="gst-input">        <div>Tax Rate</div>        <div>Tax Rate</div>

                   oninput="calculateGSTFromTotal(28)">

          </div>        <div class="mui-calculator-label">28%</div>

        </div>

      </div>        <input id="28_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .28, 28)" class="gst-input">        <div>Tax Amount</div>        <div>Tax Amount</div>

    </div>

  </div>        <input id="28_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.28, 28)" class="gst-input">



  <!-- Results Summary -->      </div>        <div>Total Amount</div>        <div>Total Amount</div>

  <div class="mui-card">

    <h3>Quick Reference</h3>    </div>

    <div style="display: grid; gap: 1rem;">

      <div style="padding: 1rem; background: var(--bg-elevated); border-radius: var(--mui-radius); border: 1px solid var(--border-primary);">      </div>      </div>

        <h4 style="margin: 0 0 0.5rem 0; color: var(--accent-primary);">GST Rates in India</h4>

        <ul style="margin: 0; padding-left: 1.2rem; color: var(--text-secondary);">    <div id="gst-loading" class="gst-loading" style="display: none;">

          <li><strong>5%</strong> - Essential goods, food items</li>

          <li><strong>12%</strong> - Processed foods, industrial intermediaries</li>      <div class="gst-loading-spinner"></div>

          <li><strong>18%</strong> - Capital goods, industrial inputs</li>

          <li><strong>28%</strong> - Luxury items, tobacco, cars</li>      Calculating...

        </ul>

      </div>    </div>      <!-- 5% GST -->      <!-- 5% GST -->



      <div style="padding: 1rem; background: var(--bg-elevated); border-radius: var(--mui-radius); border: 1px solid var(--border-primary);">  </div>

        <h4 style="margin: 0 0 0.5rem 0; color: var(--accent-primary);">How to Use</h4>

        <ul style="margin: 0; padding-left: 1.2rem; color: var(--text-secondary);"></div>      <div class="mui-calculator-row">      <div class="mui-calculator-row">

          <li>Enter <strong>taxable amount</strong> to calculate GST and total</li>

          <li>Enter <strong>GST amount</strong> to find taxable value</li>

          <li>Enter <strong>total amount</strong> to reverse calculate</li>

        </ul><!-- Instructions Section -->        <input id="5_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 5)" class="gst-input">        <input id="5_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 5)" class="gst-input">

      </div>

<div class="mui-card">

      <div id="gst-loading" style="padding: 1rem; background: var(--bg-elevated); border-radius: var(--mui-radius); border: 1px solid var(--border-primary); display: none; text-align: center;">

        <div class="gst-loading-spinner" style="display: inline-block; width: 20px; height: 20px; border: 2px solid var(--border-primary); border-radius: 50%; border-top-color: var(--accent-primary); animation: spin 1s ease-in-out infinite; margin-right: 0.5rem;"></div>  <div class="mui-container">        <div class="mui-calculator-label">5%</div>        <div class="mui-calculator-label">5%</div>

        Calculating...

      </div>    <h2 class="mui-section-title">How to Use</h2>

    </div>

  </div>    <div class="mui-info-grid">        <input id="5_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .05, 5)" class="gst-input">        <input id="5_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .05, 5)" class="gst-input">

</div>

      <div class="mui-info-item">

<style>

@keyframes spin {        <strong>Taxable Amount:</strong>        <input id="5_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.05, 5)" class="gst-input">        <input id="5_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.05, 5)" class="gst-input">

  to { transform: rotate(360deg); }

}        <span>Enter the base price before GST</span>

</style>

      </div>      </div>      </div>

<script>

function calculateGST(rate) {      <div class="mui-info-item">

  showLoading();

  setTimeout(() => {        <strong>Tax Amount:</strong>

    const taxable = parseFloat(document.getElementById(`taxable_${rate}`).value) || 0;

    const gstAmount = taxable * (rate / 100);        <span>Enter the GST amount to calculate base price</span>

    const total = taxable + gstAmount;

      </div>      <!-- 12% GST -->      <!-- 12% GST -->

    document.getElementById(`gst_${rate}`).value = gstAmount.toFixed(2);

    document.getElementById(`total_${rate}`).value = total.toFixed(2);      <div class="mui-info-item">



    trackUsage(rate, 'taxable', taxable);        <strong>Total Amount:</strong>      <div class="mui-calculator-row">      <div class="mui-calculator-row">

    hideLoading();

  }, 150);        <span>Enter the final price including GST</span>

}

      </div>        <input id="12_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 12)" class="gst-input">        <input id="12_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 12)" class="gst-input">

function calculateGSTFromTax(rate) {

  showLoading();      <div class="mui-info-item">

  setTimeout(() => {

    const gstAmount = parseFloat(document.getElementById(`gst_${rate}`).value) || 0;        <strong>Tax Rate:</strong>        <div class="mui-calculator-label">12%</div>        <div class="mui-calculator-label">12%</div>

    const taxable = gstAmount / (rate / 100);

    const total = taxable + gstAmount;        <span>Select from standard GST rates (5%, 12%, 18%, 28%)</span>



    document.getElementById(`taxable_${rate}`).value = taxable.toFixed(2);      </div>        <input id="12_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .12, 12)" class="gst-input">        <input id="12_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .12, 12)" class="gst-input">

    document.getElementById(`total_${rate}`).value = total.toFixed(2);

    </div>

    trackUsage(rate, 'gst', gstAmount);

    hideLoading();  </div>        <input id="12_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.12, 12)" class="gst-input">        <input id="12_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.12, 12)" class="gst-input">

  }, 150);

}</div>



function calculateGSTFromTotal(rate) {      </div>      </div>

  showLoading();

  setTimeout(() => {<script>

    const total = parseFloat(document.getElementById(`total_${rate}`).value) || 0;

    const taxable = total / (1 + rate / 100);function Converter(val, rate) {

    const gstAmount = total - taxable;

  // Show loading state

    document.getElementById(`taxable_${rate}`).value = taxable.toFixed(2);

    document.getElementById(`gst_${rate}`).value = gstAmount.toFixed(2);  showLoading();      <!-- 18% GST -->      <!-- 18% GST -->



    trackUsage(rate, 'total', total);

    hideLoading();

  }, 150);  // Small delay to show loading state for better UX      <div class="mui-calculator-row">      <div class="mui-calculator-row">

}

  setTimeout(() => {

function trackUsage(rate, inputType, amount) {

  if (window.RKAnalytics && amount > 0) {    // Get all input fields for the selected rate        <input id="18_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 18)" class="gst-input">        <input id="18_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 18)" class="gst-input">

    window.RKAnalytics.trackCalculator('GST', 'calculate', {

      rate: rate,    var taxable = document.getElementById(rate + '_TAXABLE');

      inputType: inputType,

      amount: amount    var tax = document.getElementById(rate + '_TAX');        <div class="mui-calculator-label">18%</div>        <div class="mui-calculator-label">18%</div>

    });

  }    var total = document.getElementById(rate + '_TOTAL');

}

        <input id="18_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .18, 18)" class="gst-input">        <input id="18_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .18, 18)" class="gst-input">

function showLoading() {

  const loadingEl = document.getElementById('gst-loading');    // Determine which field triggered the event

  if (loadingEl) {

    loadingEl.style.display = 'block';    var source = event.target.id;        <input id="18_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.18, 18)" class="gst-input">        <input id="18_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.18, 18)" class="gst-input">

  }

}



function hideLoading() {    // Track calculator usage      </div>      </div>

  const loadingEl = document.getElementById('gst-loading');

  if (loadingEl) {    if (window.RKAnalytics && val && parseFloat(val) > 0) {

    loadingEl.style.display = 'none';

  }      window.RKAnalytics.trackCalculator('GST', 'calculate', {

}

</script>        rate: rate,

        inputType: source.includes('TAXABLE') ? 'taxable' : source.includes('TAX') ? 'tax' : 'total',      <!-- 28% GST -->      <!-- 28% GST -->

        amount: parseFloat(val)

      });      <div class="mui-calculator-row">      <div class="mui-calculator-row">

    }

        <input id="28_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 28)" class="gst-input">        <input id="28_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 28)" class="gst-input">

    if (source === rate + '_TAXABLE') {

      // User entered taxable amount        <div class="mui-calculator-label">28%</div>        <div class="mui-calculator-label">28%</div>

      var t = parseFloat(val) || 0;

      var taxAmt = +(t * (rate / 100)).toFixed(2);        <input id="28_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .28, 28)" class="gst-input">        <input id="28_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .28, 28)" class="gst-input">

      var tot = +(t + taxAmt).toFixed(2);

      tax.value = taxAmt;        <input id="28_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.28, 28)" class="gst-input">        <input id="28_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.28, 28)" class="gst-input">

      total.value = tot;

    } else if (source === rate + '_TAX') {      </div>      </div>

      // User entered tax amount

      var taxAmt = parseFloat(val) || 0;    </div>    </div>

      var t = +(taxAmt / (rate / 100)).toFixed(2);

      var tot = +(t + taxAmt).toFixed(2);

      taxable.value = t;

      total.value = tot;    <div id="gst-loading" class="gst-loading" style="display: none;">    <div id="gst-loading" class="gst-loading" style="display: none;">

    } else if (source === rate + '_TOTAL') {

      // User entered total amount      <div class="gst-loading-spinner"></div>      <div class="gst-loading-spinner"></div>

      var tot = parseFloat(val) || 0;

      var t = +(tot / (1 + rate / 100)).toFixed(2);      Calculating...      Calculating...

      var taxAmt = +(tot - t).toFixed(2);

      taxable.value = t;    </div>    </div>

      tax.value = taxAmt;

    }  </div>  </div>



    // Hide loading state</div></div>

    hideLoading();

  }, 150);

}

<!-- Instructions Section --><!-- Instructions Section -->

function showLoading() {

  const loadingEl = document.getElementById('gst-loading');<div class="mui-card"><div class="mui-card">

  if (loadingEl) {

    loadingEl.style.display = 'flex';  <div class="mui-container">  <div class="mui-container">

  }

}    <h2 class="mui-section-title">How to Use</h2>    <h2 class="mui-section-title">How to Use</h2>



function hideLoading() {    <div class="mui-info-grid">    <div class="mui-info-grid">

  const loadingEl = document.getElementById('gst-loading');

  if (loadingEl) {      <div class="mui-info-item">      <div class="mui-info-item">

    loadingEl.style.display = 'none';

  }        <strong>Taxable Amount:</strong>        <strong>Taxable Amount:</strong>

}

</script>        <span>Enter the base price before GST</span>        <span>Enter the base price before GST</span>

      </div>      </div>

      <div class="mui-info-item">      <div class="mui-info-item">

        <strong>Tax Amount:</strong>        <strong>Tax Amount:</strong>

        <span>Enter the GST amount to calculate base price</span>        <span>Enter the GST amount to calculate base price</span>

      </div>      </div>

      <div class="mui-info-item">      <div class="mui-info-item">

        <strong>Total Amount:</strong>        <strong>Total Amount:</strong>

        <span>Enter the final price including GST</span>        <span>Enter the final price including GST</span>

      </div>      </div>

      <div class="mui-info-item">      <div class="mui-info-item">

        <strong>Tax Rate:</strong>        <strong>Tax Rate:</strong>

        <span>Select from standard GST rates (5%, 12%, 18%, 28%)</span>        <span>Select from standard GST rates (5%, 12%, 18%, 28%)</span>

      </div>      </div>

    </div>    </div>

  </div>  </div>

</div></div>

    <span>Calculating...</span>

<script>  </div>

function Converter(val, rate) {</div>

  // Show loading state<script>

  showLoading();function Converter(val, rate) {

  // Show loading state

  // Small delay to show loading state for better UX  showLoading();

  setTimeout(() => {

    // Get all input fields for the selected rate  // Small delay to show loading state for better UX

    var taxable = document.getElementById(rate + '_TAXABLE');  setTimeout(() => {

    var tax = document.getElementById(rate + '_TAX');    // Get all input fields for the selected rate

    var total = document.getElementById(rate + '_TOTAL');    var taxable = document.getElementById(rate + '_TAXABLE');

    var tax = document.getElementById(rate + '_TAX');

    // Determine which field triggered the event    var total = document.getElementById(rate + '_TOTAL');

    var source = event.target.id;

    // Determine which field triggered the event

    // Track calculator usage    var source = event.target.id;

    if (window.RKAnalytics && val && parseFloat(val) > 0) {

      window.RKAnalytics.trackCalculator('GST', 'calculate', {    // Track calculator usage

        rate: rate,    if (window.RKAnalytics && val && parseFloat(val) > 0) {

        inputType: source.includes('TAXABLE') ? 'taxable' : source.includes('TAX') ? 'tax' : 'total',      window.RKAnalytics.trackCalculator('GST', 'calculate', {

        amount: parseFloat(val)        rate: rate,

      });        inputType: source.includes('TAXABLE') ? 'taxable' : source.includes('TAX') ? 'tax' : 'total',

    }        amount: parseFloat(val)

      });

    if (source === rate + '_TAXABLE') {    }

      // User entered taxable amount

      var t = parseFloat(val) || 0;    if (source === rate + '_TAXABLE') {

      var taxAmt = +(t * (rate / 100)).toFixed(2);      // User entered taxable amount

      var tot = +(t + taxAmt).toFixed(2);      var t = parseFloat(val) || 0;

      tax.value = taxAmt;      var taxAmt = +(t * (rate / 100)).toFixed(2);

      total.value = tot;      var tot = +(t + taxAmt).toFixed(2);

    } else if (source === rate + '_TAX') {      tax.value = taxAmt;

      // User entered tax amount      total.value = tot;

      var taxAmt = parseFloat(val) || 0;    } else if (source === rate + '_TAX') {

      var t = +(taxAmt / (rate / 100)).toFixed(2);      // User entered tax amount

      var tot = +(t + taxAmt).toFixed(2);      var taxAmt = parseFloat(val) || 0;

      taxable.value = t;      var t = +(taxAmt / (rate / 100)).toFixed(2);

      total.value = tot;      var tot = +(t + taxAmt).toFixed(2);

    } else if (source === rate + '_TOTAL') {      taxable.value = t;

      // User entered total amount      total.value = tot;

      var tot = parseFloat(val) || 0;    } else if (source === rate + '_TOTAL') {

      var t = +(tot / (1 + rate / 100)).toFixed(2);      // User entered total amount

      var taxAmt = +(tot - t).toFixed(2);      var tot = parseFloat(val) || 0;

      taxable.value = t;      var t = +(tot / (1 + rate / 100)).toFixed(2);

      tax.value = taxAmt;      var taxAmt = +(tot - t).toFixed(2);

    }      taxable.value = t;

      tax.value = taxAmt;

    // Hide loading state    }

    hideLoading();

  }, 150);    // Hide loading state

}    hideLoading();

  }, 150);

function showLoading() {}

  const loadingEl = document.getElementById('gst-loading');

  if (loadingEl) {function showLoading() {

    loadingEl.style.display = 'flex';  const loadingEl = document.getElementById('gst-loading');

  }  if (loadingEl) {

}    loadingEl.style.display = 'flex';

  }

function hideLoading() {}

  const loadingEl = document.getElementById('gst-loading');

  if (loadingEl) {function hideLoading() {

    loadingEl.style.display = 'none';  const loadingEl = document.getElementById('gst-loading');

  }  if (loadingEl) {

}    loadingEl.style.display = 'none';

</script>  }
}
</script>
