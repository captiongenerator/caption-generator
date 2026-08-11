<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CaptionCraft V2 | Smart Social Content Generator</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#070b16;--panel:#10172a;--line:#29344d;--muted:#8f9bb2;--accent:#7657ff;--cyan:#21d4fd}
body{font-family:Inter,Arial,sans-serif;background:var(--bg);color:#fff;min-height:100vh;overflow-x:hidden}
body:before{content:"";position:fixed;inset:-35%;z-index:-2;background:conic-gradient(from 90deg,transparent,#7657ff22,transparent 30%,#21d4fd18,transparent 60%);animation:spin 20s linear infinite}
body:after{content:"";position:fixed;width:500px;height:500px;left:-180px;top:20%;border-radius:50%;background:#7657ff18;filter:blur(80px);z-index:-1;animation:orb 8s ease-in-out infinite alternate}
@keyframes spin{to{transform:rotate(360deg)}}@keyframes orb{to{transform:translate(180px,-80px)}}
button,input,select,textarea{font:inherit}
.auth{min-height:100vh;display:grid;place-items:center;padding:20px;background:radial-gradient(circle at 15% 10%,#4938a844,transparent 32%),radial-gradient(circle at 85% 90%,#087f9940,transparent 30%)}
.box{width:min(430px,100%);padding:34px;border:1px solid #ffffff18;border-radius:26px;background:#11182add;backdrop-filter:blur(20px);box-shadow:0 30px 100px #0008;animation:enter .8s ease}
@keyframes enter{from{opacity:0;transform:translateY(25px) scale(.97)}to{opacity:1;transform:none}}
.logo{width:70px;height:70px;margin:0 auto 16px;border-radius:21px;display:grid;place-items:center;font-size:33px;background:linear-gradient(135deg,var(--accent),var(--cyan));box-shadow:0 0 45px #7657ff40;animation:pulse 3s ease-in-out infinite}
@keyframes pulse{50%{transform:translateY(-5px);box-shadow:0 0 55px #21d4fd35}}
.center{text-align:center}.brand{font-size:29px;font-weight:800}.muted{color:var(--muted);margin-top:7px}
h2{margin:25px 0 17px}.err{color:#ff8794;min-height:20px;margin-bottom:8px;font-size:14px}
.field{margin-bottom:16px}label{display:block;color:#bbc5d8;font-size:14px;margin-bottom:7px}
input,select,textarea{width:100%;border:1px solid #303b55;background:#151d32;color:#fff;border-radius:12px;padding:13px;outline:none}
input:focus,select:focus,textarea:focus{border-color:var(--accent);box-shadow:0 0 0 3px #7657ff14}
textarea{min-height:155px;resize:vertical;line-height:1.6}
.hint{font-size:12px;color:#718098;margin-top:7px}
.btn{width:100%;border:0;border-radius:12px;padding:14px;background:linear-gradient(135deg,var(--accent),var(--cyan));color:#fff;font-weight:800;cursor:pointer;position:relative;overflow:hidden;transition:.25s}
.btn:hover{transform:translateY(-2px);box-shadow:0 14px 35px #7657ff35}
.btn:after{content:"";position:absolute;top:0;left:-120%;width:75%;height:100%;background:#ffffff55;transform:skewX(-20deg);transition:.7s}.btn:hover:after{left:140%}
.switch{margin-top:18px;color:#929db3;text-align:center;font-size:14px}.switch span{color:#8edcff;font-weight:bold;cursor:pointer}
.app{display:none;min-height:100vh}.nav{height:72px;padding:0 5%;display:flex;align-items:center;justify-content:space-between;background:#0d1425dd;border-bottom:1px solid #273149;backdrop-filter:blur(18px);position:sticky;top:0;z-index:10}
.navbrand{display:flex;gap:10px;align-items:center;font-weight:800;font-size:19px}.navlogo{width:39px;height:39px;display:grid;place-items:center;border-radius:11px;background:linear-gradient(135deg,var(--accent),var(--cyan))}
.navright{display:flex;align-items:center;gap:12px}.email{color:#9da8bb;font-size:13px}.logout{padding:9px 13px;border-radius:9px;border:1px solid #37425b;background:#1b2438;color:#fff;cursor:pointer;transition:.25s}.logout:hover{border-color:var(--accent);transform:translateY(-2px)}
.wrap{width:90%;max-width:1220px;margin:auto;padding:42px 0 75px}.welcome{animation:enter .7s ease}.welcome h1{font-size:40px;margin-bottom:8px}.welcome p{color:#929db3}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:23px;margin-top:30px}.panel{background:#10172aee;border:1px solid #273149;border-radius:20px;padding:24px;box-shadow:0 20px 60px #0002;animation:enter .7s ease}
.ptitle{font-size:20px;font-weight:800;margin-bottom:20px}.platform-note{display:none;font-size:12px;color:#8edcff;margin:-8px 0 14px}
.result{min-height:430px;border:1px solid #29354d;background:#080e1c;border-radius:15px;padding:19px;line-height:1.7;color:#dfe5f1;overflow:auto}
.placeholder{text-align:center;color:#66728a;padding-top:135px}.result.generated{animation:resultIn .45s ease}.output-title{font-size:12px;color:#8fa0bd;text-transform:uppercase;letter-spacing:.12em;margin-bottom:11px}.output-item{margin-bottom:13px;padding:15px;border:1px solid #29354d;border-radius:13px;background:#0d1424}.output-label{font-weight:800;color:#9ddfff;margin-bottom:8px}.output-value{white-space:pre-wrap;line-height:1.65}
@keyframes resultIn{from{opacity:.15;transform:scale(.98)}to{opacity:1;transform:none}}
.actions{display:flex;gap:9px;margin-top:13px}.action{flex:1;padding:11px;border:1px solid #36415b;border-radius:10px;background:#192239;color:#fff;cursor:pointer;transition:.25s}.action:hover{transform:translateY(-2px);border-color:var(--accent)}
.history{margin-top:34px}.hhead{display:flex;justify-content:space-between;align-items:center;margin-bottom:15px}.cards{display:grid;gap:13px}.card{background:#10172a;border:1px solid #273149;border-radius:15px;padding:18px;animation:enter .5s ease}.tags{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:11px}.tag{font-size:11px;background:#202b45;color:#b8c5ff;padding:5px 8px;border-radius:20px}.ctext{white-space:pre-wrap;line-height:1.7;color:#d9dfeb}.cardactions{display:flex;gap:8px;margin-top:12px}.small{padding:8px 11px;border-radius:8px;border:1px solid #36415b;background:#192239;color:#fff;cursor:pointer}.empty{text-align:center;color:#68748b;padding:30px;border:1px solid #273149;border-radius:14px;background:#10172a}
.typing{display:inline-flex;gap:5px;align-items:center}.typing i{width:7px;height:7px;border-radius:50%;background:#8edcff;animation:dot 1s infinite}.typing i:nth-child(2){animation-delay:.15s}.typing i:nth-child(3){animation-delay:.3s}@keyframes dot{0%,60%,100%{transform:translateY(0);opacity:.35}30%{transform:translateY(-5px);opacity:1}}
@media(max-width:850px){.grid{grid-template-columns:1fr}.email{display:none}.welcome h1{font-size:31px}}
@media(max-width:550px){.wrap{width:92%;padding-top:28px}.panel{padding:18px}.box{padding:25px}.actions{flex-wrap:wrap}.action{min-width:45%}}
</style>
</head>
<body>

<div class="auth" id="auth">
<div class="box">
<div class="center"><div class="logo">✨</div><div class="brand">CaptionCraft</div><div class="muted">Smart Social Content Generator</div></div>

<div id="login">
<h2>Welcome Back</h2><div class="err" id="loginErr"></div>
<div class="field"><label>Email</label><input id="le" type="email" placeholder="you@example.com"></div>
<div class="field"><label>Password</label><input id="lp" type="password" placeholder="Your password"></div>
<button class="btn" id="loginBtn">Login</button>
<div class="switch">Don't have an account? <span id="showSignup">Create Account</span></div>
</div>

<div id="signup" style="display:none">
<h2>Create Account</h2><div class="err" id="signupErr"></div>
<div class="field"><label>Name</label><input id="sn" placeholder="Your name"></div>
<div class="field"><label>Email</label><input id="se" type="email" placeholder="you@example.com"></div>
<div class="field"><label>Password</label><input id="sp" type="password" placeholder="Minimum 6 characters"></div>
<button class="btn" id="signupBtn">Create Account</button>
<div class="switch">Already have an account? <span id="showLogin">Login</span></div>
</div>
</div>
</div>

<div class="app" id="app">
<nav class="nav"><div class="navbrand"><div class="navlogo">✨</div>CaptionCraft</div><div class="navright"><span class="email" id="email"></span><button class="logout" id="logout">Logout</button></div></nav>

<main class="wrap">
<div class="welcome"><h1>Turn Your Script Into Content 🚀</h1><p>Paste your video script and get titles, descriptions, captions and hashtags tailored to it.</p></div>

<div class="grid">
<section class="panel">
<div class="ptitle">🎬 Content Settings</div>
<div class="field"><label>Paste Your Video Script</label><textarea id="topic" placeholder="Paste your complete video script here..."></textarea><div class="hint">The longer and clearer your script is, the better the generated ideas will be.</div></div>

<div class="field"><label>Platform</label><select id="platform"><option>Facebook</option><option>Instagram</option><option>TikTok</option><option>YouTube</option></select></div>
<div class="platform-note" id="youtubeNote">YouTube mode: titles + description + caption + hashtags will be generated.</div>

<div class="field"><label>Style</label><select id="style"><option>Elegant</option><option>Emotional</option><option>Short</option><option>Viral</option><option>Storytelling</option></select></div>
<div class="field"><label>Language</label><select id="language"><option>English</option><option>Urdu</option><option>Roman Urdu</option><option>Spanish</option><option>Hindi</option></select></div>
<div class="field"><label>Content Length</label><select id="length"><option>Short</option><option selected>Medium</option><option>Long</option></select></div>
<button class="btn" id="generate">✨ Generate Content</button>
</section>

<section class="panel">
<div class="ptitle">✨ Generated Content</div>
<div class="result" id="result"><div class="placeholder">Paste your script and generate titles, description, caption & hashtags.</div></div>
<div class="actions"><button class="action" id="copy">📋 Copy All</button><button class="action" id="regen">🔄 Regenerate</button><button class="action" id="clear">🗑 Clear</button></div>
</section>
</div>

<section class="history"><div class="hhead"><h2>📚 Content History</h2></div><div class="cards" id="history"><div class="empty">Your saved content packs will appear here.</div></div></section>
</main>
</div>

<script type="module">
import {initializeApp} from "https://www.gstatic.com/firebasejs/12.1.0/firebase-app.js";
import {getAuth,createUserWithEmailAndPassword,signInWithEmailAndPassword,signOut,onAuthStateChanged} from "https://www.gstatic.com/firebasejs/12.1.0/firebase-auth.js";
import {getFirestore,collection,addDoc,deleteDoc,doc,query,orderBy,onSnapshot,serverTimestamp} from "https://www.gstatic.com/firebasejs/12.1.0/firebase-firestore.js";

const firebaseConfig={
apiKey:"AIzaSyBp3NKyu8Bb90EfQjQ6M5HUHoiBwQDJxXk",
authDomain:"caption-generator-ddb05.firebaseapp.com",
projectId:"caption-generator-ddb05",
storageBucket:"caption-generator-ddb05.firebasestorage.app",
messagingSenderId:"405355316544",
appId:"1:405355316544:web:302e22cd7d32a3026c66a5",
measurementId:"G-71BR72SMDS"
};
const app=initializeApp(firebaseConfig);
const auth=getAuth(app);
const db=getFirestore(app);
let user=null,stopHistory=null;
const $=id=>document.getElementById(id);

$("showSignup").onclick=()=>{$("login").style.display="none";$("signup").style.display="block"};
$("showLogin").onclick=()=>{$("signup").style.display="none";$("login").style.display="block"};
$("logout").onclick=()=>signOut(auth);

$("signupBtn").onclick=async()=>{
$("signupErr").textContent="";
const name=$("sn").value.trim(),email=$("se").value.trim(),pass=$("sp").value;
if(!name||!email||!pass)return $("signupErr").textContent="Please fill all fields.";
if(pass.length<6)return $("signupErr").textContent="Password must be at least 6 characters.";
try{await createUserWithEmailAndPassword(auth,email,pass)}catch(e){$("signupErr").textContent=err(e.code)}
};
$("loginBtn").onclick=async()=>{
$("loginErr").textContent="";
const email=$("le").value.trim(),pass=$("lp").value;
if(!email||!pass)return $("loginErr").textContent="Please enter email and password.";
try{await signInWithEmailAndPassword(auth,email,pass)}catch(e){$("loginErr").textContent=err(e.code)}
};
function err(c){return {"auth/email-already-in-use":"This email is already registered.","auth/invalid-email":"Please enter a valid email.","auth/weak-password":"Password must be at least 6 characters.","auth/invalid-credential":"Email or password is incorrect.","auth/operation-not-allowed":"Email/Password sign-in is not enabled in Firebase.","auth/network-request-failed":"Network error. Check your internet connection.","auth/unauthorized-domain":"This website domain is not authorized in Firebase. Add captiongenerator.github.io in Authentication > Settings > Authorized domains."}[c]||("Firebase error: "+c)}

onAuthStateChanged(auth,u=>{
user=u;
if(u){$("auth").style.display="none";$("app").style.display="block";$("email").textContent=u.email;loadHistory(u.uid)}
else{$("auth").style.display="grid";$("app").style.display="none";if(stopHistory){stopHistory();stopHistory=null}}
});

$("platform").onchange=()=>{$("youtubeNote").style.display=$("platform").value==="YouTube"?"block":"none"};

function clean(s){return s.replace(/\s+/g," ").trim()}
function firstIdea(s){const x=clean(s).split(/[.!?]/).filter(Boolean)[0]||"Your Video";return x.length>85?x.slice(0,82)+"...":x}
function esc(s){return s.replace(/[&<>"']/g,m=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#039;"}[m]))}

function makePack(){
const script=clean($("topic").value),p=$("platform").value,style=$("style").value,lang=$("language").value,len=$("length").value,idea=firstIdea(script);
let titles=[],caption="",description="",hashtags="";
if(lang==="English"){
if(p==="YouTube"){
if(style==="Viral")titles=[`${idea} — You Won't Believe What Happens Next!`,`This Changes Everything About ${idea}`,`Wait Until You See What Happens! 😱`,`The Ending Will Surprise You! | ${idea}`,`${idea} — The Moment Everyone Is Talking About`];
else if(style==="Storytelling")titles=[`The Story Behind ${idea}`,`It Started With ${idea}... Then Everything Changed`,`What Really Happened? The Full Story`,`From Beginning to End: ${idea}`,`The Complete Story You Need to Hear`];
else if(style==="Emotional")titles=[`${idea} — A Moment That Says More Than Words`,`This Moment Will Stay With You ❤️`,`A Story Worth Remembering`,`Some Moments Are Impossible to Forget`,`The Beautiful Story Behind This Moment`];
else titles=[`${idea} | Full Story`,`Everything You Need to Know About ${idea}`,`A Closer Look at ${idea}`,`${idea} — Watch the Full Video`,`What You Need to Know Before You Scroll`];
description=`${script}\n\nIn this video, we take a closer look at the story and details behind this moment. Watch until the end so you don't miss what happens next.\n\n💬 What do you think about this? Share your thoughts in the comments!\n👍 Like the video if you enjoyed it.\n🔔 Subscribe for more interesting videos and turn on notifications.\n\n${style==="Viral"?"Stay until the end — you won't want to miss it!": "Thanks for watching and supporting the channel!"}`;
caption=`✨ ${idea} — a moment worth watching and sharing.`;
hashtags="#YouTube #YouTubeShorts #Shorts #ViralVideo #Trending #ContentCreator";
}else{
titles=[`${idea} ✨`,`You Have to See This! 👀`,`This Moment Is Too Good to Miss`,`Wait Until the End! 🔥`];
caption=style==="Emotional"?`❤️ ${idea} — some moments are not just seen, they are felt. This is one of those moments worth remembering.`
:style==="Viral"?`🔥 ${idea} — this deserves your attention! Watch till the end and tell me what you think. 👀`
:style==="Storytelling"?`There is a story behind ${idea}. Sometimes the simplest moments become the most unforgettable memories.`
:`✨ ${idea} — a beautiful moment worth sharing.`;
description=script;hashtags="#Viral #Trending #Explore #Reels #ContentCreator";
}
}else if(lang==="Roman Urdu"){
titles=[`${idea} — Aakhir Mein Kya Hua? 👀`,`${idea} Ki Kahani Jo Aap Ko Zaroor Dekhni Chahiye`,`Ye Moment Dekh Kar Aap Bhi Hairan Ho Jao Ge!`,`Puri Kahani Dekhein — ${idea}`,`End Tak Dekhna Mat Bhoolna! 🔥`];
caption=`✨ ${idea} — kuch lamhay sirf dekhe nahi, mehsoos kiye jate hain. Video ko end tak zaroor dekhein!`;
description=`${script}\n\nIs video mein aap ko is moment ki poori story aur interesting details dekhne ko milengi. End tak zaroor dekhein.\n\n💬 Apni rai comments mein zaroor batayein!\n👍 Video pasand aaye to like karein.\n🔔 More videos ke liye subscribe/follow karein.`;
hashtags="#Viral #Trending #Shorts #FYP #Pakistan";
}else if(lang==="Urdu"){
titles=[`آخر میں کیا ہوا؟ پوری کہانی دیکھیں 👀`,`یہ کہانی آپ کو حیران کر دے گی`,`آخر میں جو ہوا، کسی نے سوچا بھی نہیں تھا!`,`${idea} کی مکمل کہانی`,`ویڈیو آخر تک ضرور دیکھیں! 🔥`];
caption=`✨ ${idea} — کچھ لمحے صرف دیکھے نہیں جاتے، محسوس بھی کیے جاتے ہیں۔ ویڈیو آخر تک ضرور دیکھیں۔`;
description=`${script}\n\nاس ویڈیو میں آپ کو اس واقعے کی مکمل تفصیل اور دلچسپ کہانی دیکھنے کو ملے گی۔ ویڈیو آخر تک ضرور دیکھیں۔\n\n💬 اپنی رائے کمنٹس میں بتائیں!\n👍 ویڈیو پسند آئے تو لائک کریں۔\n🔔 مزید ویڈیوز کے لیے سبسکرائب کریں۔`;
hashtags="#شارٹس #وائرل #ٹرینڈنگ #ویڈیو";
}else if(lang==="Spanish"){
titles=[`${idea} — ¡Mira lo que pasó al final!`,`La historia detrás de ${idea}`,`¡No podrás creer lo que sucede!`,`Historia completa: ${idea}`,`¡Tienes que ver esto hasta el final!`];
caption=`✨ ${idea} — algunos momentos simplemente merecen ser compartidos. ¡Mira hasta el final!`;
description=`${script}\n\nEn este video descubrimos la historia y los detalles detrás de este momento. ¡Mira hasta el final!\n\n💬 Cuéntanos tu opinión en los comentarios.\n👍 Dale like y comparte.\n🔔 Suscríbete para más contenido.`;
hashtags="#Viral #Trending #YouTubeShorts #Reels #ParaTi";
}else{
titles=[`${idea} — आखिर में क्या हुआ? 👀`,`${idea} की पूरी कहानी`,`आखिर में जो हुआ, किसी ने सोचा भी नहीं था!`,`यह जरूर देखिए — ${idea}`,`वीडियो को अंत तक जरूर देखें! 🔥`];
caption=`✨ ${idea} — कुछ पल सिर्फ देखे नहीं जाते, महसूस भी किए जाते हैं। वीडियो को अंत तक जरूर देखें।`;
description=`${script}\n\nइस वीडियो में आपको इस कहानी और इसके खास पलों के बारे में पूरी जानकारी मिलेगी। अंत तक जरूर देखें!\n\n💬 अपनी राय कमेंट में बताएं।\n👍 वीडियो पसंद आए तो लाइक करें।\n🔔 ऐसे और वीडियो के लिए सब्सक्राइब करें।`;
hashtags="#Viral #Trending #Shorts #YouTube #Reels";
}
if(len==="Short")titles=titles.slice(0,3);
if(len==="Long"){titles.push(`${idea} — Full Details, Story & Everything You Need to Know`);caption+=`\n\n${script.slice(0,280)}${script.length>280?"...":""}\n\nWhat do you think? Share your thoughts in the comments.`}
return{titles,caption,description,hashtags,platform:p,style,language:lang,length:len};
}

function render(o){
$("result").classList.remove("generated");void $("result").offsetWidth;$("result").classList.add("generated");
$("result").innerHTML=`<div class="output-title">${o.platform==="YouTube"?"YouTube Content Pack":"Social Content Pack"}</div>
<div class="output-item"><div class="output-label">🔥 Best Titles</div><div class="output-value">${o.titles.map((x,i)=>`${i+1}. ${esc(x)}`).join("\n")}</div></div>
<div class="output-item"><div class="output-label">✍️ Caption</div><div class="output-value">${esc(o.caption)}</div></div>
${o.platform==="YouTube"?`<div class="output-item"><div class="output-label">📝 Video Description</div><div class="output-value">${esc(o.description)}</div></div>`:""}
<div class="output-item"><div class="output-label">#️⃣ Hashtags</div><div class="output-value">${esc(o.hashtags)}</div></div>`;
}

async function generate(){
if(!$("topic").value.trim())return alert("Please paste your video script first.");
$("result").innerHTML='<div class="placeholder"><span class="typing">Creating smart content <i></i><i></i><i></i></span></div>';
await new Promise(r=>setTimeout(r,500));
const o=makePack();render(o);await save(o);
}
$("generate").onclick=generate;$("regen").onclick=generate;
$("clear").onclick=()=>$("result").innerHTML='<div class="placeholder">Paste your script and generate titles, description, caption & hashtags.</div>';
$("copy").onclick=async()=>{const t=$("result").innerText.trim();if(!t||t.includes("Paste your script"))return;await navigator.clipboard.writeText(t);$("copy").textContent="✓ Copied!";setTimeout(()=>$("copy").textContent="📋 Copy All",1200)};

async function save(o){
if(!user)return;
await addDoc(collection(db,"users",user.uid,"captions"),{titles:o.titles,caption:o.caption,description:o.description,hashtags:o.hashtags,topic:$("topic").value,platform:o.platform,style:o.style,language:o.language,length:o.length,createdAt:serverTimestamp()});
}

function loadHistory(uid){
if(stopHistory)stopHistory();
const q=query(collection(db,"users",uid,"captions"),orderBy("createdAt","desc"));
stopHistory=onSnapshot(q,snap=>{
if(snap.empty){$("history").innerHTML='<div class="empty">Your saved content packs will appear here.</div>';return}
$("history").innerHTML="";
snap.forEach(ds=>{
const d=ds.data(),card=document.createElement("div");card.className="card";
const tags=document.createElement("div");tags.className="tags";
[d.platform,d.style,d.language].forEach(v=>{const z=document.createElement("span");z.className="tag";z.textContent=v||"";tags.appendChild(z)});
const text=document.createElement("div");text.className="ctext";text.textContent=`🔥 Titles:\n${(d.titles||[]).map((t,i)=>`${i+1}. ${t}`).join("\n")}\n\n✍️ Caption:\n${d.caption||""}${d.platform==="YouTube"?`\n\n📝 Description:\n${d.description||""}`}\n\n#️⃣ Hashtags:\n${d.hashtags||""}`;
const acts=document.createElement("div");acts.className="cardactions";
const cp=document.createElement("button");cp.className="small";cp.textContent="📋 Copy";cp.onclick=async()=>{await navigator.clipboard.writeText(text.textContent);cp.textContent="✓ Copied";setTimeout(()=>cp.textContent="📋 Copy",1000)};
const del=document.createElement("button");del.className="small";del.textContent="🗑 Delete";del.onclick=async()=>{if(confirm("Delete this content pack?"))await deleteDoc(doc(db,"users",uid,"captions",ds.id))};
acts.append(cp,del);card.append(tags,text,acts);$("history").appendChild(card);
});
},e=>console.error("History:",e));
}
</script>
</body>
</html>
