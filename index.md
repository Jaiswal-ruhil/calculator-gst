------

layout: defaultlayout: default

title: GST Calculatortitle: GST Calculator

breadcrumbs:breadcrumbs:

  - name: Home  - name: Home

    url: /    url: /

  - name: Calculators  - name: Calculators

    url: /Calc/    url: /Calc/

  - name: GST Calculator  - name: GST Calculator

    url: /Calc/GST/    url: /Calc/GST/

------



<div class="mui-hero mui-hero--bleed"><div class="mui-hero mui-hero--bleed">

  <div class="mui-hero-content">  <div class="mui-hero-content">

    <div class="mui-hero-icon">    <div class="mui-hero-icon">

      <span class="material-icons" style="font-size: 4rem;">receipt_long</span>      <span class="material-icons" style="font-size: 4rem;">receipt_long</span>

    </div>    </div>

    <h1 class="mui-hero-title">GST Calculator</h1>    <h1 class="mui-hero-title">GST Calculator</h1>

    <p class="mui-hero-subtitle">Calculate GST amounts and base rates for different tax slabs</p>    <p class="mui-hero-subtitle">Calculate GST amounts and base rates for different tax slabs</p>

  </div>  </div>

</div></div>



<!-- Calculator Section --><!-- Calculator Section -->

<div class="mui-card"><div class="mui-card">

  <div class="mui-container">  <div class="mui-container">

    <h2 class="mui-section-title">GST Calculator</h2>    <h2 class="mui-section-title">GST Calculator</h2>

    <p class="mui-text-center">Type a value in any of the following fields to calculate GST amounts:</p>    <p class="mui-text-center">Type a value in any of the following fields to calculate GST amounts:</p>



    <div class="mui-calculator-grid">    <div class="mui-calculator-grid">

      <div class="mui-calculator-header">      <div class="mui-calculator-header">

        <div>Taxable Amount</div>        <div>Taxable Amount</div>

        <div>Tax Rate</div>        <div>Tax Rate</div>

        <div>Tax Amount</div>        <div>Tax Amount</div>

        <div>Total Amount</div>        <div>Total Amount</div>

      </div>      </div>



      <!-- 5% GST -->      <!-- 5% GST -->

      <div class="mui-calculator-row">      <div class="mui-calculator-row">

        <input id="5_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 5)" class="gst-input">        <input id="5_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 5)" class="gst-input">

        <div class="mui-calculator-label">5%</div>        <div class="mui-calculator-label">5%</div>

        <input id="5_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .05, 5)" class="gst-input">        <input id="5_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .05, 5)" class="gst-input">

        <input id="5_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.05, 5)" class="gst-input">        <input id="5_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.05, 5)" class="gst-input">

      </div>      </div>



      <!-- 12% GST -->      <!-- 12% GST -->

      <div class="mui-calculator-row">      <div class="mui-calculator-row">

        <input id="12_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 12)" class="gst-input">        <input id="12_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 12)" class="gst-input">

        <div class="mui-calculator-label">12%</div>        <div class="mui-calculator-label">12%</div>

        <input id="12_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .12, 12)" class="gst-input">        <input id="12_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .12, 12)" class="gst-input">

        <input id="12_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.12, 12)" class="gst-input">        <input id="12_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.12, 12)" class="gst-input">

      </div>      </div>



      <!-- 18% GST -->      <!-- 18% GST -->

      <div class="mui-calculator-row">      <div class="mui-calculator-row">

        <input id="18_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 18)" class="gst-input">        <input id="18_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 18)" class="gst-input">

        <div class="mui-calculator-label">18%</div>        <div class="mui-calculator-label">18%</div>

        <input id="18_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .18, 18)" class="gst-input">        <input id="18_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .18, 18)" class="gst-input">

        <input id="18_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.18, 18)" class="gst-input">        <input id="18_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.18, 18)" class="gst-input">

      </div>      </div>



      <!-- 28% GST -->      <!-- 28% GST -->

      <div class="mui-calculator-row">      <div class="mui-calculator-row">

        <input id="28_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 28)" class="gst-input">        <input id="28_TAXABLE" type="number" placeholder="TAXABLE" oninput="Converter(this.value, 28)" class="gst-input">

        <div class="mui-calculator-label">28%</div>        <div class="mui-calculator-label">28%</div>

        <input id="28_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .28, 28)" class="gst-input">        <input id="28_TAX" type="number" placeholder="TAX" oninput="Converter(this.value / .28, 28)" class="gst-input">

        <input id="28_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.28, 28)" class="gst-input">        <input id="28_TOTAL" type="number" placeholder="TOTAL" oninput="Converter(this.value / 1.28, 28)" class="gst-input">

      </div>      </div>

    </div>    </div>



    <div id="gst-loading" class="gst-loading" style="display: none;">    <div id="gst-loading" class="gst-loading" style="display: none;">

      <div class="gst-loading-spinner"></div>      <div class="gst-loading-spinner"></div>

      Calculating...      Calculating...

    </div>    </div>

  </div>  </div>

</div></div>



<!-- Instructions Section --><!-- Instructions Section -->

<div class="mui-card"><div class="mui-card">

  <div class="mui-container">  <div class="mui-container">

    <h2 class="mui-section-title">How to Use</h2>    <h2 class="mui-section-title">How to Use</h2>

    <div class="mui-info-grid">    <div class="mui-info-grid">

      <div class="mui-info-item">      <div class="mui-info-item">

        <strong>Taxable Amount:</strong>        <strong>Taxable Amount:</strong>

        <span>Enter the base price before GST</span>        <span>Enter the base price before GST</span>

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
