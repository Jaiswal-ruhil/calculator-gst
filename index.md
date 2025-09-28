---
layout: default
title: GST Calculator
description:
  Calculate GST amounts and base rates for different tax slabs with instant
  results.
breadcrumbs:
  - name: Home
    url: /
  - name: Calculators
    url: /Calc/
  - name: GST Calculator
    url: /Calc/GST/
---

<div class="mui-hero">
  <h1>GST Calculator</h1>
  <p class="subtitle">Calculate taxes quickly and accurately</p>
</div>

<div class="mui-features-grid" style="grid-template-columns: 1fr 1fr; gap: 2rem; align-items: start;">
  <!-- Calculator Input -->
  <div class="mui-calculator">
    <div class="mui-calculator__header">
      <h2 class="mui-calculator__title">GST Calculator</h2>
      <p class="mui-calculator__subtitle">Enter any value to calculate GST amounts instantly</p>
    </div>
    
    <div class="mui-calculator__form">
      <!-- 5% GST Rate -->
      <div class="mui-calculator__section">
        <h3 class="mui-calculator__section-title">
          <span class="mui-calculator__section-icon material-icons">percent</span>
          5% GST Rate
        </h3>
        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 0.75rem;">
          <div class="mui-calculator__input-group">
            <label for="taxable_5" class="mui-calculator__label">
              <span class="mui-calculator__label-icon material-icons">currency_rupee</span>
              Taxable Amount
            </label>
            <div class="mui-calculator__input-wrapper">
              <input type="number" id="taxable_5" class="mui-calculator__input mui-calculator__input--with-prefix" 
                     placeholder="0" min="0" step="0.01" oninput="calculateGST(5)">
              <span class="mui-calculator__input-prefix">₹</span>
            </div>
          </div>
          <div class="mui-calculator__input-group">
            <label for="gst_5" class="mui-calculator__label">
              <span class="mui-calculator__label-icon material-icons">account_balance_wallet</span>
              GST Amount
            </label>
            <div class="mui-calculator__input-wrapper">
              <input type="number" id="gst_5" class="mui-calculator__input mui-calculator__input--with-prefix" 
                     placeholder="0" min="0" step="0.01" oninput="calculateGSTFromTax(5)">
              <span class="mui-calculator__input-prefix">₹</span>
            </div>
          </div>
          <div class="mui-calculator__input-group" style="grid-column: span 2;">
            <label for="total_5" class="mui-calculator__label">
              <span class="mui-calculator__label-icon material-icons">receipt</span>
              Total Amount
            </label>
            <div class="mui-calculator__input-wrapper">
              <input type="number" id="total_5" class="mui-calculator__input mui-calculator__input--with-prefix" 
                     placeholder="0" min="0" step="0.01" oninput="calculateGSTFromTotal(5)">
              <span class="mui-calculator__input-prefix">₹</span>
            </div>
          </div>
        </div>
      </div>

      <!-- 12% GST Rate -->
      <div class="mui-calculator__section">
        <h3 class="mui-calculator__section-title">
          <span class="mui-calculator__section-icon material-icons">percent</span>
          12% GST Rate
        </h3>
        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 0.75rem;">
          <div class="mui-calculator__input-group">
            <label for="taxable_12" class="mui-calculator__label">
              <span class="mui-calculator__label-icon material-icons">currency_rupee</span>
              Taxable Amount
            </label>
            <div class="mui-calculator__input-wrapper">
              <input type="number" id="taxable_12" class="mui-calculator__input mui-calculator__input--with-prefix"
                     placeholder="0" min="0" step="0.01" oninput="calculateGST(12)">
              <span class="mui-calculator__input-prefix">₹</span>
            </div>
          </div>
          <div class="mui-calculator__input-group">
            <label for="gst_12" class="mui-calculator__label">
              <span class="mui-calculator__label-icon material-icons">account_balance_wallet</span>
              GST Amount
            </label>
            <div class="mui-calculator__input-wrapper">
              <input type="number" id="gst_12" class="mui-calculator__input mui-calculator__input--with-prefix"
                     placeholder="0" min="0" step="0.01" oninput="calculateGSTFromTax(12)">
              <span class="mui-calculator__input-prefix">₹</span>
            </div>
          </div>
          <div class="mui-calculator__input-group" style="grid-column: span 2;">
            <label for="total_12" class="mui-calculator__label">
              <span class="mui-calculator__label-icon material-icons">receipt</span>
              Total Amount
            </label>
            <div class="mui-calculator__input-wrapper">
              <input type="number" id="total_12" class="mui-calculator__input mui-calculator__input--with-prefix"
                     placeholder="0" min="0" step="0.01" oninput="calculateGSTFromTotal(12)">
              <span class="mui-calculator__input-prefix">₹</span>
            </div>
          </div>
        </div>
      </div>

      <!-- 18% GST Rate -->
      <div style="border: 1px solid var(--border-primary); border-radius: var(--mui-radius); padding: 1rem; background: var(--bg-elevated);">
        <h4 style="margin: 0 0 1rem 0; color: var(--accent-primary);">18% GST Rate</h4>
        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 0.75rem;">
          <div>
            <label for="taxable_18" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text);">Taxable Amount (₹)</label>
            <input type="number" id="taxable_18" placeholder="0" min="0" step="0.01"
                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-elevated); color: var(--text);"
                   oninput="calculateGST(18)">
          </div>
          <div>
            <label for="gst_18" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text);">GST Amount (₹)</label>
            <input type="number" id="gst_18" placeholder="0" min="0" step="0.01"
                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-elevated); color: var(--text);"
                   oninput="calculateGSTFromTax(18)">
          </div>
          <div style="grid-column: span 2;">
            <label for="total_18" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text);">Total Amount (₹)</label>
            <input type="number" id="total_18" placeholder="0" min="0" step="0.01"
                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-elevated); color: var(--text);"
                   oninput="calculateGSTFromTotal(18)">
          </div>
        </div>
      </div>

      <!-- 28% GST Rate -->
      <div style="border: 1px solid var(--border-primary); border-radius: var(--mui-radius); padding: 1rem; background: var(--bg-elevated);">
        <h4 style="margin: 0 0 1rem 0; color: var(--accent-primary);">28% GST Rate</h4>
        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 0.75rem;">
          <div>
            <label for="taxable_28" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text);">Taxable Amount (₹)</label>
            <input type="number" id="taxable_28" placeholder="0" min="0" step="0.01"
                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-elevated); color: var(--text);"
                   oninput="calculateGST(28)">
          </div>
          <div>
            <label for="gst_28" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text);">GST Amount (₹)</label>
            <input type="number" id="gst_28" placeholder="0" min="0" step="0.01"
                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-elevated); color: var(--text);"
                   oninput="calculateGSTFromTax(28)">
          </div>
          <div style="grid-column: span 2;">
            <label for="total_28" style="display: block; margin-bottom: 0.5rem; font-weight: 500; color: var(--text);">Total Amount (₹)</label>
            <input type="number" id="total_28" placeholder="0" min="0" step="0.01"
                   style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-primary); border-radius: var(--mui-radius); background: var(--bg-elevated); color: var(--text);"
                   oninput="calculateGSTFromTotal(28)">
          </div>
        </div>
      </div>
    </div>

  </div>

  <!-- Results Summary -->
  <div class="mui-card">
    <h3>Quick Reference</h3>
    <div style="display: grid; gap: 1rem;">
      <div style="padding: 1rem; background: var(--bg-elevated); border-radius: var(--mui-radius); border: 1px solid var(--border-primary);">
        <h4 style="margin: 0 0 0.5rem 0; color: var(--accent-primary);">GST Rates in India</h4>
        <ul style="margin: 0; padding-left: 1.2rem; color: var(--text-secondary);">
          <li><strong>5%</strong> - Essential goods, food items</li>
          <li><strong>12%</strong> - Processed foods, industrial intermediaries</li>
          <li><strong>18%</strong> - Capital goods, industrial inputs</li>
          <li><strong>28%</strong> - Luxury items, tobacco, cars</li>
        </ul>
      </div>

      <div style="padding: 1rem; background: var(--bg-elevated); border-radius: var(--mui-radius); border: 1px solid var(--border-primary);">
        <h4 style="margin: 0 0 0.5rem 0; color: var(--accent-primary);">How to Use</h4>
        <ul style="margin: 0; padding-left: 1.2rem; color: var(--text-secondary);">
          <li>Enter <strong>taxable amount</strong> to calculate GST and total</li>
          <li>Enter <strong>GST amount</strong> to find taxable value</li>
          <li>Enter <strong>total amount</strong> to reverse calculate</li>
        </ul>
      </div>

      <div id="gst-loading" style="padding: 1rem; background: var(--bg-elevated); border-radius: var(--mui-radius); border: 1px solid var(--border-primary); display: none; text-align: center;">
        <div class="gst-loading-spinner" style="display: inline-block; width: 20px; height: 20px; border: 2px solid var(--border-primary); border-radius: 50%; border-top-color: var(--accent-primary); animation: spin 1s ease-in-out infinite; margin-right: 0.5rem;"></div>
        Calculating...
      </div>
    </div>

  </div>
</div>

<style>
@keyframes spin {
  to { transform: rotate(360deg); }
}
</style>

<script>
function calculateGST(rate) {
  showLoading();
  setTimeout(() => {
    const taxable = parseFloat(document.getElementById(	axable_).value) || 0;
    const gstAmount = taxable * (rate / 100);
    const total = taxable + gstAmount;

    document.getElementById(gst_).value = gstAmount.toFixed(2);
    document.getElementById(	otal_).value = total.toFixed(2);

    trackUsage(rate, 'taxable', taxable);
    hideLoading();
  }, 150);
}

function calculateGSTFromTax(rate) {
  showLoading();
  setTimeout(() => {
    const gstAmount = parseFloat(document.getElementById(gst_).value) || 0;
    const taxable = gstAmount / (rate / 100);
    const total = taxable + gstAmount;

    document.getElementById(	axable_).value = taxable.toFixed(2);
    document.getElementById(	otal_).value = total.toFixed(2);

    trackUsage(rate, 'gst', gstAmount);
    hideLoading();
  }, 150);
}

function calculateGSTFromTotal(rate) {
  showLoading();
  setTimeout(() => {
    const total = parseFloat(document.getElementById(	otal_).value) || 0;
    const taxable = total / (1 + rate / 100);
    const gstAmount = total - taxable;

    document.getElementById(	axable_).value = taxable.toFixed(2);
    document.getElementById(gst_).value = gstAmount.toFixed(2);

    trackUsage(rate, 'total', total);
    hideLoading();
  }, 150);
}

function trackUsage(rate, inputType, amount) {
  if (window.RKAnalytics && amount > 0) {
    window.RKAnalytics.trackCalculator('GST', 'calculate', {
      rate: rate,
      inputType: inputType,
      amount: amount
    });
  }
}

function showLoading() {
  const loadingEl = document.getElementById('gst-loading');
  if (loadingEl) {
    loadingEl.style.display = 'block';
  }
}

function hideLoading() {
  const loadingEl = document.getElementById('gst-loading');
  if (loadingEl) {
    loadingEl.style.display = 'none';
  }
}
</script>
