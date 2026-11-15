
<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DXN Shop Bangladesh - আসল DXN প্রোডাক্ট</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Hind Siliguri',Arial,sans-serif}
body{background:#f6fff8;padding-bottom:90px}
.header{background:#0a7a42;color:white;text-align:center;padding:22px 12px;position:sticky;top:0;z-index:10}
.header h1{font-size:26px}
.header p{font-size:13px;opacity:.9;margin-top:4px}
.searchbar{max-width:1100px;margin:14px auto 0;padding:0 12px;display:flex;gap:8px}
.searchbar input{flex:1;padding:12px;border:1px solid #ddd;border-radius:10px;font-size:15px;outline:none}
.searchbar select{padding:12px;border:1px solid #ddd;border-radius:10px;font-size:14px}
.shop{max-width:1100px;margin:14px auto;padding:0 12px;display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:14px}
.card{background:white;border-radius:16px;overflow:hidden;box-shadow:0 4px 15px rgba(0,0,0,.08);border:1px solid #e8f5ee}
.card img{width:100%;height:280px;object-fit:cover;background:#eee}
.info{padding:13px}
.info h3{font-size:18px;margin-bottom:3px}
.info p{font-size:13px;color:#666;line-height:1.5;min-height:38px}
.price{margin:9px 0;font-size:21px;font-weight:900;color:#0a7a42}
.price span{font-size:13px;color:#999;text-decoration:line-through;margin-left:4px;font-weight:400}
.row{display:flex;gap:8px}
.add{flex:1;background:#0a7a42;color:white;border:none;padding:11px;border-radius:10px;font-weight:700;cursor:pointer}
.buy{flex:1;background:#25D366;color:white;text-decoration:none;text-align:center;padding:11px;border-radius:10px;font-weight:700}
.badge{display:inline-block;background:#fff3cd;color:#7a5a00;font-size:12px;padding:3px 8px;border-radius:20px;margin-bottom:6px}
.cartbar{position:fixed;bottom:0;left:0;right:0;background:white;border-top:2px solid #0a7a42;padding:12px;display:flex;justify-content:space-between;align-items:center;box-shadow:0 -4px 15px rgba(0,0,0,.1);z-index:20}
.cartbar b{font-size:16px}
.cartbar button{background:#25D366;color:white;border:none;padding:12px 18px;border-radius:10px;font-weight:800;font-size:15px;cursor:pointer}
.footer{text-align:center;padding:20px;color:#666;font-size:13px;line-height:1.7}
</style>
</head>
<body>

<div class="header">
<h1>🌿 DXN Shop Bangladesh</h1>
<p>১০০% আসল DXN প্রোডাক্ট | ক্যাশ অন ডেলিভারি | 01748-820303</p>
</div>

<div class="searchbar">
<input id="search" oninput="filter()" placeholder="🔍 প্রোডাক্ট খুঁজুন... যেমন: সাবান, কফি, চা">
<select id="cat" onchange="filter()">
<option value="all">সব ক্যাটাগরি</option>
<option value="skin">ত্বকের যত্ন</option>
<option value="oral">দাঁত ও মুখ</option>
<option value="drink">চা / কফি</option>
</select>
</div>

<div class="shop" id="shop">

<div class="card" data-cat="skin" data-name="lily body wash"><img src="lily.jpg"><div class="info"><span class="badge">✨ Best Seller</span><h3>Lily Body Wash</h3><p>কোমল ও মসৃণ ত্বকের জন্য। ফুলের সুবাসে সারাদিন ফ্রেশ।</p><div class="price">৳১৯৯ <span>৳২৫০</span></div><div class="row"><button class="add" onclick="add('Lily Body Wash',199)">🛒 Add</button><a class="buy" href="https://wa.me/8801748820303?text=আমি Lily Body Wash (১৯৯ টাকা) নিতে চাই">Buy</a></div></div></div>

<div class="card" data-cat="skin" data-name="skin lotion"><img src="lotion.jpg"><div class="info"><span class="badge">💧 Moisturizer</span><h3>DXN Skin Lotion</h3><p>ত্বককে নরম, উজ্জ্বল ও হাইড্রেট রাখে।</p><div class="price">৳২৯৫</div><div class="row"><button class="add" onclick="add('DXN Skin Lotion',295)">🛒 Add</button><a class="buy" href="https://wa.me/8801748820303?text=আমি DXN Skin Lotion (২৯৫ টাকা) নিতে চাই">Buy</a></div></div></div>

<div class="card" data-cat="oral" data-name="ganozhi toothpaste"><img src="toothpaste.jpg"><div class="info"><span class="badge">🦷 দাঁতের যত্ন</span><h3>Ganozhi Toothpaste PLUS</h3><p>গ্যানোডার্মা সমৃদ্ধ টুথপেস্ট। দাঁত মজবুত করে।</p><div class="price">৳২৩৫</div><div class="row"><button class="add" onclick="add('Ganozhi Toothpaste PLUS',235)">🛒 Add</button><a class="buy" href="https://wa.me/8801748820303?text=আমি Ganozhi Toothpaste PLUS (২৩৫ টাকা) নিতে চাই">Buy</a></div></div></div>

<div class="card" data-cat="skin" data-name="neem bathing bar saban"><img src="neem.jpg"><div class="info"><span class="badge">🌿 নিম</span><h3>Neem Bathing Bar</h3><p>নিম এক্সট্রাক্ট সাবান। ব্রণ ও চুলকানিতে কার্যকর।</p><div class="price">৳২১০</div><div class="row"><button class="add" onclick="add('Neem Bathing Bar',210)">🛒 Add</button><a class="buy" href="https://wa.me/8801748820303?text=আমি Neem Bathing Bar (২১০ টাকা) নিতে চাই">Buy</a></div></div></div>

<div class="card" data-cat="skin" data-name="apricot facial scrub"><img src="scrub.jpg"><div class="info"><span class="badge">✨ Face Scrub</span><h3>Apricot Facial Scrub</h3><p>মৃত কোষ দূর করে ত্বককে উজ্জ্বল করে।</p><div class="price">৳২৮০</div><div class="row"><button class="add" onclick="add('Apricot Facial Scrub',280)">🛒 Add</button><a class="buy" href="https://wa.me/8801748820303?text=আমি Apricot Facial Scrub (২৮০ টাকা) নিতে চাই">Buy</a></div></div></div>

<div class="card" data-cat="skin" data-name="ganozhi soap saban"><img src="ganozhi.jpg"><div class="info"><span class="badge">🔥 সবচেয়ে জনপ্রিয়</span><h3>Ganozhi Soap</h3><p>গ্যানোডার্মা যুক্ত আসল DXN সাবান।</p><div class="price">৳৪৭০</div><div class="row"><button class="add" onclick="add('Ganozhi Soap',470)">🛒 Add</button><a class="buy" href="https://wa.me/8801748820303?text=আমি Ganozhi Soap (৪৭০ টাকা) নিতে চাই">Buy</a></div></div></div>

<div class="card" data-cat="drink" data-name="lingzhi coffee black"><img src="coffee.jpg"><div class="info"><span class="badge">☕ Coffee</span><h3>Lingzhi Coffee Black</h3><p>চিনি ছাড়া ব্ল্যাক কফি + গ্যানোডার্মা। ২০ প্যাক।</p><div class="price">৳১১৯০</div><div class="row"><button class="add" onclick="add('Lingzhi Coffee Black',1190)">🛒 Add</button><a class="buy" href="https://wa.me/8801748820303?text=আমি Lingzhi Coffee Black (১১৯০ টাকা) নিতে চাই">Buy</a></div></div></div>

<div class="card" data-cat="skin" data-name="face wash neem"><img src="facewash.jpg"><div class="info"><span class="badge">🌿 Face Wash</span><h3>Face Wash (Neem)</h3><p>নিম ফেস ওয়াশ। তৈলাক্ত ও ব্রণযুক্ত ত্বকের জন্য।</p><div class="price">৳২৩০</div><div class="row"><button class="add" onclick="add('Face Wash Neem',230)">🛒 Add</button><a class="buy" href="https://wa.me/8801748820303?text=আমি Face Wash Neem (২৩০ টাকা) নিতে চাই">Buy</a></div></div></div>

<div class="card" data-cat="drink" data-name="lemonzhi tea cha"><img src="tea.jpg"><div class="info"><span class="badge">🍋 Tea</span><h3>Lemonzhi Premix Tea</h3><p>লেমন ফ্লেভার + গ্যানোডার্মা চা। রিফ্রেশিং।</p><div class="price">৳৮৯৫</div><div class="row"><button class="add" onclick="add('Lemonzhi Tea',895)">🛒 Add</button><a class="buy" href="https://wa.me/8801748820303?text=আমি Lemonzhi Tea (৮৯৫ টাকা) নিতে চাই">Buy</a></div></div></div>

</div>

<div class="footer">
<b>অর্ডার করতে Add বাটনে ক্লিক করে নিচে WhatsApp অর্ডার করুন</b><br>
ডেলিভারি: ঢাকার ভিতরে ৬০ টাকা, ঢাকার বাইরে ১৩০ টাকা | ক্যাশ অন ডেলিভারি<br>
যোগাযোগ: 01748-820303
</div>

<div class="cartbar">
<b id="cartText">🛒 কার্ট: ০টি | মোট: ০ টাকা</b>
<button onclick="checkout()">WhatsApp এ অর্ডার করুন</button>
</div>

<script>
let cart=[];
function add(name,price){cart.push({name,price});update();}
function update(){
let total=cart.reduce((s,i)=>s+i.price,0);
document.getElementById('cartText').innerText=`🛒 কার্ট: ${cart.length}টি | মোট: ${total} টাকা`;
}
function checkout(){
if(cart.length==0){alert('আগে একটা প্রোডাক্ট Add করুন');return;}
let total=cart.reduce((s,i)=>s+i.price,0);
let msg="আসসালামু আলাইকুম, আমি অর্ডার করতে চাই:%0A%0A";
cart.forEach((i,n)=>{msg+=`${n+1}. ${i.name} - ${i.price} টাকা%0A`;});
msg+=`%0Aমোট: ${total} টাকা%0Aনাম:%0Aঠিকানা:%0Aফোন:`;
window.open(`https://wa.me/8801748820303?text=${msg}`,'_blank');
}
function filter(){
let q=document.getElementById('search').value.toLowerCase();
let c=document.getElementById('cat').value;
document.querySelectorAll('.card').forEach(card=>{
let name=card.dataset.name;
let cat=card.dataset.cat;
let show=(c=='all'||c==cat) && name.includes(q);
card.style.display=show?'block':'none';
});
}
</script>
</body>
</html>