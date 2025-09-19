<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <meta name="description" content="칼하인츠 슈톡하우젠과 Gesang der Jünglinge(소년들의 노래) — 발표 자료" />
  <title>슈톡하우젠 — 소년들의 노래 (발표 자료)</title>
  <style>
    :root{
      --accent:#2563eb;
      --muted:#475569;
      --card:#ffffff;
    }
    body{
      font-family:"Noto Sans KR", system-ui, sans-serif;
      color:#0f172a;
      margin:0;
      background:linear-gradient(-45deg,#fdfcfb,#e2ebf0,#dbeafe,#f0f9ff);
      background-size:400% 400%;
      animation:gradientMove 18s ease infinite;
    }
    @keyframes gradientMove {
      0%{background-position:0% 50%}
      50%{background-position:100% 50%}
      100%{background-position:0% 50%}
    }
    header{
      background:rgba(255,255,255,0.7);
      backdrop-filter:blur(8px);
      color:#0f172a;
      padding:32px 16px;
      text-align:center;
      border-bottom:1px solid rgba(0,0,0,0.1);
    }
    header h1{margin:0;font-size:1.8rem}
    header p{margin:6px 0 0 0;opacity:0.8}
    #start-button{
      margin-top:14px;padding:10px 18px;font-size:1rem;
      border:none;border-radius:12px;cursor:pointer;
      background:var(--accent);color:#fff;transition:0.3s;
    }
    #start-button:hover{background:#1d4ed8}
    main{max-width:960px;margin:20px auto;padding:16px;display:none}
    .controls{display:flex;gap:8px;justify-content:center;margin-bottom:16px}
    #search-input{
      width:65%;padding:10px 12px;border-radius:10px;
      border:1px solid rgba(0,0,0,0.15);background:#fff;color:#0f172a
    }
    #search-button{
      background:var(--accent);color:#fff;border:none;padding:10px 14px;
      border-radius:10px;cursor:pointer;transition:0.3s
    }
    #search-button:hover{background:#1d4ed8}
    .keywords{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin-bottom:12px}
    .keywords span{
      background:#e0f2fe;color:#0f172a;padding:8px 12px;border-radius:999px;
      cursor:pointer;font-weight:600;transition:0.3s
    }
    .keywords span:hover{background:#bae6fd}
    section{
      background:var(--card);padding:20px;border-radius:14px;margin-bottom:16px;
      box-shadow:0 4px 12px rgba(0,0,0,0.1);line-height:1.65
    }
    section h2{margin:0 0 12px 0;border-left:4px solid var(--accent);padding-left:10px;font-size:1.2rem}
    section h3{margin:14px 0 6px 0}
    ul{padding-left:20px}
    .hidden{display:none}
    iframe{width:100%;height:360px;border-radius:10px;border:0;margin-top:12px}
    footer{padding:14px;text-align:center;color:var(--muted);font-size:0.9rem}
    @media (max-width:640px){iframe{height:220px}}
  </style>
</head>
<body>
  <header>
    <h1>칼하인츠 슈톡하우젠 — 소년들의 노래 (Gesang der Jünglinge)</h1>
    <p>발표 자료 — 검색 또는 키워드로 탐색하세요</p>
    <button id="start-button">시작하기</button>
  </header>

  <main>
    <div class="controls">
      <input id="search-input" type="search" placeholder="검색어 입력 (예: 시대적 배경, 슈톡하우젠)" />
      <button id="search-button">검색</button>
    </div>
    <div class="keywords">
      <span data-key="시대적 배경">시대적 배경</span>
      <span data-key="음악적 배경">음악적 배경</span>
      <span data-key="사회 문화적 특징">사회 문화적 특징</span>
      <span data-key="슈톡하우젠">슈톡하우젠</span>
      <span data-key="소년들의 노래">소년들의 노래</span>
      <span data-key="느낌">느낌</span>
      <span data-key="참고 문헌">참고 문헌</span>
    </div>

    <section id="era" class="hidden">
      <h2>1. 시대적 배경</h2>
      <ul>
        <li>제2차 세계대전 이후 독일과 유럽은 폐허 속에서 새로운 예술적 출발을 모색.</li>
        <li>전통적인 음악 질서가 무너지고, 완전히 새로운 언어와 기법이 요구됨.</li>
        <li>다름슈타트 현대음악 강좌는 유럽 아방가르드 음악의 중심지가 됨.</li>
        <li>냉전 속 과학기술 발전(전자공학, 음향기술)은 음악에도 직접 반영됨.</li>
      </ul>
    </section>

    <section id="music-background" class="hidden">
      <h2>2. 음악적 배경 및 특징</h2>
      <h3>총렬주의</h3>
      <ul>
        <li>쇤베르크의 12음기법을 확장하여, 음고뿐 아니라 길이·강약·음색까지 체계적으로 배열.</li>
        <li>베베른의 영향을 받아 미세한 음향 단위까지 조직화하려는 시도가 등장.</li>
      </ul>
      <h3>전자음악</h3>
      <ul>
        <li>독일 쾰른 WDR 스튜디오: 발진기·노이즈 발생기를 활용해 인공 전자음을 창작.</li>
        <li>프랑스 GRM: 녹음된 실제 소리를 편집·조작하는 뮤직 콘크레트.</li>
        <li>슈톡하우젠은 두 방식을 융합하여 새로운 가능성을 열음.</li>
      </ul>
      <h3>공간음향</h3>
      <ul>
        <li>소리의 높이·길이뿐 아니라 위치와 이동을 중요한 요소로 삼음.</li>
        <li>다채널 스피커를 이용해 청중이 입체적으로 소리를 체험하게 함.</li>
      </ul>
    </section>

    <section id="social-context" class="hidden">
      <h2>3. 사회·문화적 특징</h2>
      <ul>
        <li>과학과 예술의 융합: 냉전과 기술 발전의 시대 분위기 반영.</li>
        <li>예술가의 사회적·윤리적 책임 강조 — 단순 오락을 넘어 인류적 메시지를 전달.</li>
        <li>종교적 상징과 영적 세계관이 작품에 반영됨.</li>
        <li>대중음악에도 영향: 비틀즈 등은 그의 전자음악 실험을 참고함.</li>
      </ul>
    </section>

    <section id="stockhausen" class="hidden">
      <h2>4. 슈톡하우젠 — 생애와 업적</h2>
      <h3>생애</h3>
      <ul>
        <li>1928년 독일에서 출생. 어린 시절 제2차 세계대전의 참상을 직접 경험.</li>
        <li>쾰른 음악원에서 작곡 공부 후, 파리와 다름슈타트에서 현대음악을 접함.</li>
        <li>WDR 전자음악 스튜디오에서 본격적인 전자음악 창작 시작.</li>
        <li>2007년 별세. 20세기 현대음악의 선구자로 평가받음.</li>
      </ul>
      <h3>업적</h3>
      <ul>
        <li>전자음악과 인간 목소리의 결합이라는 새로운 장르 개척.</li>
        <li>공간음향 개념을 도입해 청취 경험을 확장.</li>
        <li>‘순간 형식(Moment form)’을 창안해 음악 형식의 새로운 방향 제시.</li>
        <li>현대 대중음악과 실험음악, 사운드 아트 전반에 영향을 줌.</li>
      </ul>
      <h3>대표곡</h3>
      <h4>접촉 (Kontakte, 1958–60)</h4>
      <ul>
        <li>전자음과 피아노·타악기를 결합한 작품.</li>
        <li>음색과 공간 이동을 활용한 실험적 곡.</li>
      </ul>
      <h4>그루펜 (Gruppen, 1955–57)</h4>
      <ul>
        <li>세 개의 오케스트라와 세 명의 지휘자가 동시에 연주.</li>
        <li>시간과 공간을 다차원적으로 조직한 대규모 작품.</li>
      </ul>
    </section>

    <section id="youthsong" class="hidden">
      <h2>5. 소년들의 노래 (Gesang der Jünglinge)</h2>
      <ul>
        <li>작곡 시기: 1955–56, 쾰른 WDR 전자음악 스튜디오에서 제작.</li>
        <li>재료: 소년의 목소리를 잘게 분해(모음·자음) + 순음, 노이즈, 펄스 등 전자음.</li>
        <li>형식: 순간 형식(Moment form) — 독립된 단위들이 배열되는 구조.</li>
        <li>공간: 다채널 스피커를 통해 소리가 이동하며 공간감을 강조.</li>
        <li>텍스트: 성경 다니엘서의 구절 사용.</li>
        <li>의의: 전자음악과 인간 목소리를 결합한 획기적 시도, 전자음악사의 전환점.</li>
      </ul>
      <iframe src="https://www.youtube.com/embed/LcCs6Muljmk" title="Gesang der Jünglinge - Stockhausen" allowfullscreen></iframe>
    </section>

    <section id="feeling" class="hidden">
      <h2>6. 느낌</h2>
      <h3>선택한 이유</h3>
      <p>다른 음악보다 특이한 작품을 조사하고 싶었기에, 슈톡하우젠의 <em>소년들의 노래</em>를 선택했습니다.</p>
      <h3>느낀 점</h3>
      <p>이 작품이 소년의 목소리와 전자음만으로 이루어졌다는 점이 신기했습니다. 전자음과 목소리만으로도 완성된 음악이 될 수 있다는 사실이 새로웠습니다. 슈톡하우젠이 어려운 시대적 상황 속에서도 이런 작품을 만들었다는 점에서 대단하다고 느꼈습니다.</p>
    </section>

    <section id="reference" class="hidden">
      <h2>7. 참고 문헌</h2>
      <ul>
        <li>위키백과 — <a href="https://ko.wikipedia.org/wiki/%EC%B9%BC%ED%95%98%EC%9D%B8%EC%B8%A0_%EC%8A%88%ED%86%A1%ED%95%98%EC%9A%B4%EC%A0%A0" target="_blank">칼하인츠 슈톡하우젠</a></li>
        <li>네이버 지식백과 — 소년들의 노래 (Gesang der Jünglinge)</li>
        <li>Stockhausen 공식 사이트 — <a href="https://www.stockhausen.org" target="_blank">stockhausen.org</a></li>
        <li>유튜브 — 소년들의 노래 (Gesang der Jünglinge, WDR, 1956 녹음)</li>
        <li>브리태니커 백과사전 한국어판 — “칼하인츠 슈톡하우젠”</li>
      </ul>
    </section>
  </main>

  <footer>© 2025 발표자료 — 슈톡하우젠 / 소년들의 노래</footer>

  <script>
    const startButton=document.getElementById('start-button');
    const main=document.querySelector('main');
    const searchInput=document.getElementById('search-input');
    const searchButton=document.getElementById('search-button');
    const keywords=document.querySelectorAll('.keywords span');
    const allSections=document.querySelectorAll('main section');

    function hideAll(){allSections.forEach(s=>s.classList.add('hidden'))}
    function showByQuery(q){
      const ql=q.toLowerCase().trim();if(!ql)return;
      let shown=0;
      allSections.forEach(sec=>{
        if(sec.innerText.toLowerCase().includes(ql)){
          sec.classList.remove('hidden');shown++;
        } else {sec.classList.add('hidden')}
      });
      if(shown===0){alert('검색 결과가 없습니다.');hideAll();}
    }
    function showByKey(key){
      hideAll();
      if(key.includes('시대')) document.getElementById('era').classList.remove('hidden');
      else if(key.includes('음악')) document.getElementById('music-background').classList.remove('hidden');
      else if(key.includes('사회')) document.getElementById('social-context').classList.remove('hidden');
      else if(key.includes('슈톡')) document.getElementById('stockhausen').classList.remove('hidden');
      else if(key.includes('소년')) document.getElementById('youthsong').classList.remove('hidden');
      else if(key.includes('느낌')) document.getElementById('feeling').classList.remove('hidden');
      else if(key.includes('참고')) document.getElementById('reference').classList.remove('hidden');
    }

    startButton.addEventListener('click',()=>{
      main.style.display='block';
      startButton.style.display='none';
    });
    searchButton.addEventListener('click',()=>showByQuery(searchInput.value));
    searchInput.addEventListener('keydown',e=>{if(e.key==='Enter')showByQuery(searchInput.value)});
    keywords.forEach(k=>k.addEventListener('click',()=>showByKey(k.dataset.key)));

    hideAll();
  </script>
</body>
</html>
