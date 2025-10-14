<!doctype html>
<html lang="th">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>ชำระเงินโฆษณา | DDDD</title>
  <meta name="description" content="หน้าชำระเงินโฆษณา โทนสีแดง รองรับทั้งมือถือและเดสก์ท็อป" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='0.9em' font-size='90'>💳</text></svg>">
  <style>
    :root{
      --red-50:#fff1f2; --red-100:#ffe4e6; --red-200:#fecdd3; --red-300:#fda4af; --red-400:#fb7185;
      --red-500:#f43f5e; --red-600:#e11d48; --red-700:#be123c; --red-800:#9f1239; --red-900:#881337;
      --ink:#121212; --muted:#6b7280; --card:#ffffff; --bg:#fffafa; --ring:rgba(244,63,94,.35);
      --ok:#16a34a; --warn:#ca8a04; --shadow: 0 10px 30px rgba(190, 18, 60, .12);
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:#1f2937;font-family:"Kanit",system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif}
    a{color:var(--red-700);text-decoration:none}
    .container{max-width:1200px;margin:0 auto;padding:24px}
    header{
      position:sticky;top:0;z-index:40;background:linear-gradient(180deg,rgba(255,255,255,.95),rgba(255,255,255,.7));
      backdrop-filter:saturate(1.2) blur(10px);border-bottom:1px solid var(--red-100)
    }
    .brand{display:flex;align-items:center;gap:12px}
    .brand-badge{width:40px;height:40px;border-radius:12px;background:linear-gradient(135deg,var(--red-600),var(--red-400));
      box-shadow:var(--shadow);display:grid;place-items:center;color:white;font-weight:700}
    .brand h1{font-size:20px;margin:0;color:var(--red-800)}

    .grid{display:grid;gap:24px}
    @media (min-width: 960px){ .grid{grid-template-columns: 1.3fr .7fr} }

    .card{background:var(--card);border:1px solid var(--red-100);border-radius:18px;box-shadow:var(--shadow)}
    .card-header{padding:18px 20px;border-bottom:1px solid var(--red-100);display:flex;align-items:center;gap:10px}
    .card-title{margin:0;font-size:18px;color:var(--red-900)}
    .card-body{padding:20px}

    .section-title{font-size:14px;color:var(--muted);margin:0 0 8px}
    .row{display:grid;gap:14px}
    @media (min-width:720px){ .row.cols-2{grid-template-columns:1fr 1fr} }

    label{font-size:14px;color:#374151}
    .field{display:flex;flex-direction:column;gap:8px}
    .input, select, textarea{appearance:none;padding:12px 14px;border-radius:12px;border:1px solid var(--red-200);
      outline:none;background:white;font-size:14px;transition:.15s ease}
    .input:focus, select:focus, textarea:focus{border-color:var(--red-400);box-shadow:0 0 0 4px var(--ring)}

    .badge{display:inline-flex;align-items:center;gap:6px;padding:6px 10px;border-radius:999px;font-size:12px;border:1px solid var(--red-200);color:var(--red-700);background:var(--red-50)}

    .plans{display:grid;gap:12px}
    .plan{display:flex;align-items:center;justify-content:space-between;padding:14px;border-radius:14px;border:1px solid var(--red-200);background:white;cursor:pointer}
    .plan:hover{border-color:var(--red-400)}
    .plan input{margin-right:10px}
    .price{font-weight:700;color:var(--red-800)}

    .tabs{display:flex;gap:8px;margin-bottom:14px}
    .tab{padding:10px 12px;border-radius:999px;border:1px solid var(--red-200);background:white;cursor:pointer;font-size:14px}
    .tab.active{background:linear-gradient(135deg,var(--red-600),var(--red-500));border-color:transparent;color:white}

    .help{font-size:12px;color:var(--muted)}

    .summary{position:sticky;top:90px}
    .summary-row{display:flex;justify-content:space-between;padding:8px 0}
    .summary-row.total{border-top:1px dashed var(--red-200);margin-top:8px;padding-top:12px;font-weight:700;color:var(--red-900)}

    .btn{display:inline-flex;align-items:center;justify-content:center;gap:10px;padding:12px 16px;border-radius:14px;border:none;cursor:pointer;font-weight:600}
    .btn-primary{background:linear-gradient(135deg,var(--red-600),var(--red-500));color:white;box-shadow:var(--shadow)}
    .btn-ghost{background:transparent;border:1px dashed var(--red-300);color:var(--red-700)}
    .btn:disabled{opacity:.6;cursor:not-allowed}

    .bank-box{border:1px dashed var(--red-300);border-radius:14px;padding:14px;background:var(--red-50)}

    .qr{width:160px;height:160px;border-radius:12px;background:repeating-linear-gradient(45deg,var(--red-200),var(--red-200) 8px,white 8px,white 16px);display:grid;place-items:center;font-weight:700;color:var(--red-700)}

    footer{padding:32px 24px;color:var(--muted);text-align:center}
  </style>
</head>
<body>
  <header>
    <div class="container" style="display:flex;align-items:center;justify-content:space-between;gap:16px">
      <div class="brand">
        <div class="brand-badge">DDD</div>
        <h1>ชำระเงินโฆษณา</h1>
      </div>
      
    </div>
  </header>

  <main class="container grid" id="app">
    <!-- ซ้าย: ฟอร์ม -->
    <section class="card">
      <div class="card-header">
        <h2 class="card-title">รายละเอียดคำสั่งซื้อ</h2>
      </div>
      <div class="card-body">
        <div class="row cols-2">
          <div class="field">
            <label>แพ็กเกจโฆษณา</label>
            <div class="plans" role="radiogroup" aria-label="แพ็กเกจโฆษณา">
              <label class="plan"><span><input type="radio" name="plan" value="BASIC" data-price="1500" checked> Basic 7 วัน</span><span class="price" data-price-label>B 1,500</span></label>
              <label class="plan"><span><input type="radio" name="plan" value="BOOST" data-price="3900"> Boost 21 วัน</span><span class="price" data-price-label>B 3,900</span></label>
              <label class="plan"><span><input type="radio" name="plan" value="MAX" data-price="7900"> Max 45 วัน</span><span class="price" data-price-label>B 7,900</span></label>
            </div>
          </div>
          
        </div>

        <hr style="border:none;border-top:1px solid var(--red-100);margin:18px 0" />

        <h3 class="section-title">ข้อมูลผู้ออกใบกำกับ/ใบเสร็จ</h3>
        <div class="row cols-2">
          <div class="field">
            <label>ประเภทใบเสร็จ</label>
            <select id="invoiceType" class="input">
              <option value="PERSONAL">บุคคลธรรมดา</option>
              <option value="COMPANY">นิติบุคคล</option>
            </select>
          </div>
          <div class="field" id="taxIdField" style="display:none">
            <label>เลขประจำตัวผู้เสียภาษี / VAT</label>
            <input class="input" id="taxId" placeholder="เช่น 0105555xxxxx" />
          </div>
        </div>
        <div class="row cols-2">
          <div class="field">
            <label>ชื่อ-นามสกุล / ชื่อบริษัท</label>
            <input class="input" id="fullName" placeholder="กรอกชื่อสำหรับออกใบเสร็จ" />
          </div>
          <div class="field">
            <label>อีเมลสำหรับรับใบเสร็จ</label>
            <input class="input" id="email" type="email" placeholder="you@example.com" />
          </div>
        </div>
        <div class="row">
          <div class="field">
            <label>ที่อยู่สำหรับออกใบเสร็จ</label>
            <textarea class="input" id="address" rows="3" placeholder="บ้านเลขที่ ถนน แขวง/ตำบล เขต/อำเภอ จังหวัด รหัสไปรษณีย์"></textarea>
          </div>
        </div>

        <hr style="border:none;border-top:1px solid var(--red-100);margin:18px 0" />

        <h3 class="section-title">วิธีการชำระเงิน</h3>
        <div class="tabs" role="tablist">
          <button class="tab active" role="tab" aria-selected="true" data-tab="transfer">โอนผ่านธนาคาร</button>
          <button class="tab" role="tab" aria-selected="false" data-tab="qr">QR พร้อมเพย์</button>
        </div>

        <!-- โอน -->
        <div class="pay-panel" id="panel-transfer">
          <div class="bank-box">
            <div style="display:flex;justify-content:space-between;gap:12px;align-items:center;flex-wrap:wrap">
              <div>
                <div style="font-weight:700;color:var(--red-900)">บัญชีรับโอน</div>
                <div>ธนาคารกุหลาบไทย (KRB) | บัญชีออมทรัพย์</div>
                <div>ชื่อบัญชี: บริษัท แอดเพย์ จำกัด</div>
                <div>เลขที่: 123-4-56789-0</div>
              </div>
              <button class="btn btn-ghost" type="button" id="copyAcc">คัดลอกเลขบัญชี</button>
            </div>
          </div>
          <div class="row cols-2" style="margin-top:12px">
            <div class="field">
              <label>เวลาโอน</label>
              <input class="input" id="transferTime" type="datetime-local" />
            </div>
            <div class="field">
              <label>อัปโหลดสลิป (ไม่บังคับ)</label>
              <input class="input" id="slip" type="file" accept="image/*,.pdf" />
            </div>
          </div>
        </div>

        <!-- QR -->
        <div class="pay-panel" id="panel-qr" style="display:none">
          <div style="display:flex;gap:16px;align-items:center;flex-wrap:wrap">
            <div class="qr" aria-label="QR พร้อมเพย์">QR</div>
            <div>
              <div style="font-weight:700">สแกนจ่ายผ่านพร้อมเพย์</div>
              <div class="help">QR นี้เป็นตัวอย่าง คุณสามารถแทนที่ด้วยรูป QR ที่สร้างจากระบบของคุณ</div>
              <button class="btn btn-ghost" type="button" id="downloadQr">ดาวน์โหลด QR</button>
            </div>
          </div>
        </div>

        <div style="display:flex;align-items:center;gap:10px;margin-top:16px">
          <input id="agree" type="checkbox" />
          <label for="agree">ฉันยอมรับ <a href="#">ข้อตกลงการให้บริการ</a> และ <a href="#">นโยบายความเป็นส่วนตัว</a></label>
        </div>

        <div style="display:flex;gap:10px;flex-wrap:wrap;margin-top:16px">
          <button class="btn btn-primary" id="payBtn" disabled>ชำระเงินตอนนี้</button>
          <button class="btn btn-ghost" type="button" id="saveDraft">บันทึกร่าง</button>
        </div>
      </div>
    </section>

    <!-- ขวา: สรุป -->
    <aside class="card summary">
      <div class="card-header">
        <h2 class="card-title">สรุปคำสั่งซื้อ</h2>
      </div>
      <div class="card-body">
        <div class="summary-row"><span>แพ็กเกจ</span><strong id="sumPlan">Basic 7 วัน</strong></div>
        <div class="summary-row"><span>ราคา</span><span id="sumPrice">B 1,500.00</span></div>
        <div class="summary-row" id="sumDiscountRow" style="display:none"><span>ส่วนลด</span><span id="sumDiscount">-B 0.00</span></div>
        <div class="summary-row"><span>VAT 7%</span><span id="sumVat">B 105.00</span></div>
        <div class="summary-row total"><span>รวมทั้งสิ้น</span><span id="sumTotal">B 1,605.00</span></div>
        <div class="help">จะมีการออกใบเสร็จอิเล็กทรอนิกส์ให้ทางอีเมล</div>
      </div>
    </aside>
  </main>

  <footer>
    © <span id="year"></span> DDDD Co., Ltd. สงวนลิขสิทธิ์ · <a href="#">ศูนย์ช่วยเหลือ</a>
  </footer>

  <script>
    const fmt = new Intl.NumberFormat('th-TH', { style:'currency', currency:'THB', minimumFractionDigits:2 });
    const planRadios = document.querySelectorAll('input[name="plan"]');
    
    const invoiceType = document.getElementById('invoiceType');
    const taxIdField = document.getElementById('taxIdField');
    const agree = document.getElementById('agree');
    const payBtn = document.getElementById('payBtn');

    const sumPlan = document.getElementById('sumPlan');
    const sumPrice = document.getElementById('sumPrice');
    const sumDiscountRow = document.getElementById('sumDiscountRow');
    const sumDiscount = document.getElementById('sumDiscount');
    const sumVat = document.getElementById('sumVat');
    const sumTotal = document.getElementById('sumTotal');

    const panels = {
      transfer: document.getElementById('panel-transfer'),
      qr: document.getElementById('panel-qr')
    };

    // Tabs
    document.querySelectorAll('.tab').forEach(tab=>{
      tab.addEventListener('click', ()=>{
        document.querySelectorAll('.tab').forEach(t=>t.classList.remove('active'));
        tab.classList.add('active');
        const name = tab.dataset.tab;
        Object.keys(panels).forEach(k=> panels[k].style.display = (k===name? 'block':'none'));
      })
    })

    // Invoice type toggle
    invoiceType.addEventListener('change', ()=>{
      taxIdField.style.display = invoiceType.value === 'COMPANY' ? 'block' : 'none';
    });

    // Copy bank account
    document.getElementById('copyAcc').addEventListener('click', async ()=>{
      await navigator.clipboard.writeText('123-4-56789-0');
      toast('คัดลอกเลขบัญชีแล้ว');
    });

    // Download QR (placeholder)
    document.getElementById('downloadQr').addEventListener('click', ()=>{
      const blob = new Blob(['QR PLACEHOLDER'], {type:'text/plain'});
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url; a.download = 'qr-placeholder.txt'; a.click();
      URL.revokeObjectURL(url);
    });

    // Plan change + totals
    planRadios.forEach(r=> r.addEventListener('change', recalc));

    

    function getSelectedPlan(){
      const r = [...planRadios].find(x=>x.checked);
      const price = parseFloat(r.dataset.price);
      const label = r.parentElement.innerText.replace(/^[\s\S]*?\s/, '').trim();
      return {price, label};
    }

    function recalc(){
      const {price, label} = getSelectedPlan();
      const discount = 0;
      const vatBase = price - discount;
      const vat = vatBase * 0.07;
      const total = vatBase + vat;

      sumPlan.textContent = label;
      sumPrice.textContent = fmt.format(price);
      sumDiscountRow.style.display ='none';
      sumDiscount.textContent = '-' + fmt.format(discount);
      sumVat.textContent = fmt.format(vat);
      sumTotal.textContent = fmt.format(total);
    }
    recalc();

    // Enable pay button when agree
    agree.addEventListener('change', ()=>{ payBtn.disabled = !agree.checked; });

    // Fake pay
    payBtn.addEventListener('click', ()=>{
      if (!validate()) return;
      payBtn.disabled = true; payBtn.textContent = 'กำลังดำเนินการ...';
      setTimeout(()=>{
        payBtn.textContent = 'ชำระเงินสำเร็จ ✅';
        toast('ขอบคุณที่ชำระเงิน ระบบได้ส่งใบเสร็จไปยังอีเมลแล้ว');
      }, 800);
    });

    document.getElementById('saveDraft').addEventListener('click', ()=>{
      const data = collectData();
      localStorage.setItem('adpay-draft', JSON.stringify(data));
      toast('บันทึกร่างแล้ว');
    });

    function collectData(){
      const {price, label} = getSelectedPlan();
      return {
        plan: label, price, discountPct,
        invoiceType: invoiceType.value,
        taxId: document.getElementById('taxId').value,
        fullName: document.getElementById('fullName').value,
        email: document.getElementById('email').value,
        address: document.getElementById('address').value
      };
    }

    function validate(){
      const errs = [];
      const name = document.getElementById('fullName').value.trim();
      const email = document.getElementById('email').value.trim();
      const addr = document.getElementById('address').value.trim();
      if (!name) errs.push('กรุณากรอกชื่อสำหรับออกใบเสร็จ');
      if (!/^[^@\s]+@[^@\s]+\.[^@\s]+$/.test(email)) errs.push('อีเมลไม่ถูกต้อง');
      if (!addr) errs.push('กรุณากรอกที่อยู่สำหรับออกใบเสร็จ');
      if (!agree.checked) errs.push('กรุณายอมรับข้อตกลงก่อนชำระเงิน');
      if (invoiceType.value === 'COMPANY' && !document.getElementById('taxId').value.trim()) errs.push('กรอกเลขผู้เสียภาษีสำหรับนิติบุคคล');
      if (errs.length){ toast(errs[0], true); return false; }
      return true;
    }

    function toast(msg, danger){
      let el = document.getElementById('toast');
      if (!el){
        el = document.createElement('div'); el.id='toast'; document.body.appendChild(el);
        Object.assign(el.style, {
          position:'fixed', bottom:'24px', right:'24px', padding:'12px 14px', borderRadius:'12px',
          background: danger? 'linear-gradient(135deg,#b91c1c,#ef4444)': 'linear-gradient(135deg,var(--red-600),var(--red-500))', color:'#fff',
          boxShadow: 'var(--shadow)', zIndex: 1000, maxWidth:'80vw'
        });
      }
      el.textContent = msg; el.style.opacity='0'; el.style.transform='translateY(12px)';
      el.animate([{opacity:0, transform:'translateY(12px)'},{opacity:1, transform:'translateY(0)'}], {duration:160, fill:'forwards'});
      clearTimeout(el._t); el._t = setTimeout(()=>{
        el.animate([{opacity:1},{opacity:0}], {duration:200, fill:'forwards'});
      }, 2200);
    }

    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
