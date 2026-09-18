"use strict";
const $ = (s) => document.querySelector(s);
const colors = [
  "#9fe3cc",
  "#f8ce76",
  "#b5b4ff",
  "#86caff",
  "#f9b9d0",
  "#e0dc9b",
];
const sources = {
  official: {
    label: "Starpath · Starmine",
    url: "https://www.starpath.space/starmine",
    evidence: "https://www.starpath.space/starmine",
    type: "Starpath website",
  },
  solar: {
    label: "Starpath · Starlight",
    url: "https://www.starpath.space/starlight",
    evidence: "https://www.starpath.space/starlight",
    type: "Starpath website",
  },
  testing: {
    label: "Starpath · News",
    url: "https://www.starpath.space/news",
    evidence: "https://www.starpath.space/news",
    type: "Starpath website",
  },
  cold: {
    label: "NASA · Lunar thermal control",
    url: "https://ntrs.nasa.gov/citations/20120014158",
    evidence: "https://ntrs.nasa.gov/citations/20120014158",
    type: "NASA science background",
  },
  lunar: {
    label: "Lunar Ice Mining For Multiplanetary Travel | Starpath",
    url: "https://www.youtube.com/watch?v=5aCJdWwF9Eg",
    evidence: "https://www.sourcery.vc/p/aramco-of-the-moon-starpath",
    type: "Published episode notes",
  },
  mars: {
    label: "Relentless · Building a self-sustaining city on Mars",
    url: "https://www.youtube.com/watch?v=LImT2qvOFiE",
    evidence:
      "https://www.linkedin.com/posts/ti-morse_sat-down-with-saurav-shroff-co-founder-activity-7386502260991782913-5Y9Y",
    type: "Host’s episode description and published excerpt",
  },
  chapters: {
    label: "Relentless · Testing and iteration chapters",
    url: "https://www.youtube.com/watch?v=LImT2qvOFiE",
    evidence:
      "https://www.linkedin.com/posts/stephaniesoquet_how-to-build-a-self-sustaining-city-on-mars-activity-7388648758810615809-_FJd",
    type: "Published chapter list; application clue",
  },
  nasa: {
    label: "NASA · Producing propellant from lunar water",
    url: "https://ntrs.nasa.gov/citations/20230010039",
    evidence: "https://ntrs.nasa.gov/citations/20230010039",
    type: "Science background for the lunar-ice discussion",
  },
  glossary: {
    label: "NASA · Lunar soil and water",
    url: "https://www.nasa.gov/missions/nasa-scientists-show-how-ingredients-for-water-could-be-made-on-surface-of-moon-a-chemical-factory/",
    evidence:
      "https://www.nasa.gov/missions/nasa-scientists-show-how-ingredients-for-water-could-be-made-on-surface-of-moon-a-chemical-factory/",
    type: "Science background",
  },
  vision: {
    label: "Sourcery · Founder’s long-term vision",
    url: "https://www.youtube.com/watch?v=5aCJdWwF9Eg",
    evidence:
      "https://www.linkedin.com/posts/mollysoshea_new-pod-aramco-of-the-moon-starpath-activity-7258126559562084352-AEBi",
    type: "Publisher’s interview excerpt",
  },
};
const categories = [
  {
    name: "The Big Mission",
    clues: [
      [
        "This red planet is the destination for Starpath’s long-term city-building vision.",
        "What is Mars?",
        "",
        "mars",
      ],
      [
        "This CEO and cofounder once worked, briefly, at SpaceX.",
        "Who is Saurav Shroff?",
        "Accept Saurav or Shroff.",
        "mars",
      ],
      [
        "This word means living on more than one planet.",
        "What is multiplanetary?",
        "Accept “multi-planet” or an equivalent explanation.",
        "mars",
      ],
      [
        "A city that can keep going without essential supplies from Earth is described this way.",
        "What is self-sustaining?",
        "Accept self-sufficient or able to support itself.",
        "mars",
      ],
      [
        "A second home for humanity could help protect civilization if this happens on Earth.",
        "What is a major catastrophe?",
        "Accept a disaster that threatens humanity. This is a motivation, not a guarantee of safety.",
        "vision",
      ],
    ],
  },
  {
    name: "Ice to Liftoff",
    clues: [
      [
        "This frozen resource is the starting material in the lunar-mining discussion.",
        "What is water ice?",
        "Ice or frozen water is enough.",
        "lunar",
      ],
      [
        "LOX is short for this rocket-propellant ingredient.",
        "What is liquid oxygen?",
        "",
        "lunar",
      ],
      [
        "Starpath targets icy regolith near this lunar pole.",
        "What is the South Pole?",
        "",
        "official",
      ],
      [
        "Water is H₂O. Splitting it releases these two elements.",
        "What are hydrogen and oxygen?",
        "Both are needed. No chemical equation required.",
        "nasa",
      ],
      [
        "This word describes the loose dust and broken rock covering the Moon.",
        "What is regolith?",
        "Accept lunar soil or Moon dust.",
        "glossary",
      ],
    ],
  },
  {
    name: "Meet the Machines",
    clues: [
      [
        "This robotic vehicle moves around the surface and gathers material.",
        "What is a rover?",
        "Accept mining robot.",
        "lunar",
      ],
      [
        "Starpath’s space-ready solar panel line goes by this bright name.",
        "What is Starlight?",
        "",
        "solar",
      ],
      [
        "This processing facility turns mined material into useful products.",
        "What is a refinery?",
        "Accept processing plant.",
        "lunar",
      ],
      [
        "In the later interview, Starpath sells solar panels to companies that build these orbiting machines.",
        "What are satellites?",
        "",
        "mars",
      ],
      [
        "A rover digs and a refinery processes. The third core system supplies this.",
        "What is electrical power?",
        "Accept electricity or energy.",
        "lunar",
      ],
    ],
  },
  {
    name: "Build, Test, Repeat",
    clues: [
      [
        "Starpath tested its rover in a thermal-vacuum chamber run by this U.S. space agency.",
        "What is NASA?",
        "",
        "testing",
      ],
      [
        "An early model built to try out a design is called this.",
        "What is a prototype?",
        "Accept test model. Application of the prototyping topic.",
        "lunar",
      ],
      [
        "Starpath is developing this lunar rover to search permanently shadowed craters for water ice.",
        "What is Shadow Voyager?",
        "",
        "testing",
      ],
      [
        "Build, test, improve, repeat: this cycle helps engineers make a design better.",
        "What is iteration?",
        "Accept improving through repeated tests.",
        "chapters",
      ],
      [
        "This laser-based sensing technology helps Shadow Voyager map terrain and avoid hazards.",
        "What is LiDAR?",
        "Accept laser scanning or light detection and ranging.",
        "testing",
      ],
    ],
  },
  {
    name: "Make the Connection",
    clues: [
      [
        "This company builds Starship, a rocket discussed in the interviews.",
        "What is SpaceX?",
        "",
        "lunar",
      ],
      [
        "Like a car on a long trip, a rocket may need to do this before returning home.",
        "What is refuel?",
        "",
        "mars",
      ],
      [
        "A place where vehicles stop to refuel is a useful Earth analogy for Starpath’s mission.",
        "What is a gas station?",
        "Accept fuel station or service station. This is a classroom analogy.",
        "mars",
      ],
      [
        "Lunar night requires this to keep batteries functioning.",
        "What is heat?",
        "Accept heating, heaters, or keeping the batteries warm.",
        "cold",
      ],
      [
        "Starpath uses this name for fuel-production rate relative to the mass of the equipment producing it.",
        "What is the Starpath Ratio?",
        "Clue and definition supplied by the host; also named in the Sourcery episode’s chapter list.",
        "lunar",
      ],
    ],
  },
];
const clues = categories.flatMap((c, ci) =>
  c.clues.map((a, ri) => ({
    id: `${ci}-${ri}`,
    category: c.name,
    value: (ri + 1) * 200,
    text: a[0],
    answer: a[1],
    note: a[2],
    source: a[3],
  })),
);
const finalClue = {
  category: "Live off the land",
  text: "How can ice on the Moon or Mars become useful to a rocket? Name the two main steps.",
  answer: "Mine the ice, then process it into propellant ingredients.",
  note: "Give credit for both ideas: ① mine or collect local water/ice; ② turn it into useful propellant, such as oxygen. “Mine ice and make rocket fuel” is fine. Exact terminology is not required.",
  source: "lunar",
};
const key = "starpath-classroom-jeopardy-v3";
const defaultNames = ["TEAM SSS", "TEAM XSS", "TEAM MNR", "TEAM JKL"];
const doubles = ["1-2", "2-2"];
const doubleDuration = 8000;
const doubleLimit = (score) => (score > 0 ? Math.max(1000, score) : 0);
const fresh = () => ({
  edition: 4,
  teams: defaultNames.map((name) => ({ name, score: 0 })),
  played: [],
  finalDone: false,
  sessions: {},
  activeId: null,
  history: [],
});
let state = fresh(),
  timerId = null,
  storageOk = true;
const esc = (s) =>
  String(s).replace(
    /[&<>"']/g,
    (c) =>
      ({ "&": "&amp;", "<": "&lt;", ">": "&gt;", '"': "&quot;", "'": "&#39;" })[
        c
      ],
  );
const money = (n) =>
  `${n < 0 ? "−" : ""}$${Math.abs(n).toLocaleString("en-US", { useGrouping: false })}`;
const active = () => (state.activeId ? state.sessions[state.activeId] : null);
const question = () =>
  state.activeId === "final"
    ? finalClue
    : clues.find((c) => c.id === state.activeId);
function validTeams(t) {
  return (
    Array.isArray(t) &&
    t.length >= 1 &&
    t.length <= 6 &&
    t.every((x) => typeof x.name === "string" && Number.isFinite(x.score))
  );
}
try {
  const saved = JSON.parse(localStorage.getItem(key));
  if (saved && validTeams(saved.teams) && Array.isArray(saved.played)) {
    state = { ...fresh(), ...saved, edition: saved.edition || 0 };
    state.sessions = saved.sessions || {};
    state.history = Array.isArray(saved.history)
      ? saved.history.slice(-80)
      : [];
    if (!state.sessions[state.activeId]) state.activeId = null;
  } else {
    const prior = JSON.parse(
      localStorage.getItem("starpath-classroom-jeopardy-v2"),
    );
    if (prior && validTeams(prior.teams)) {
      state.edition = 0;
      state.teams = defaultNames.map((name, i) => ({
        name,
        score: prior.teams[i]?.score || 0,
      }));
      state.played = Array.isArray(prior.played) ? prior.played : [];
      state.finalDone = !!prior.finalDone;
    }
  }
  state.played = state.played.filter((id) => clues.some((c) => c.id === id));
} catch {}
// Apply the requested names and restore the missing tile once, including Undo snapshots.
if (state.edition < 4) {
  const migrate = (s) => {
    s.teams = defaultNames.map((name, i) => ({
      name,
      score: s.teams?.[i]?.score || 0,
    }));
    s.played = (s.played || []).filter((id) => id !== "2-4");
    if (s.sessions) delete s.sessions["2-4"];
    if (s.activeId === "2-4") s.activeId = null;
    s.edition = 4;
  };
  migrate(state);
  state.history.forEach(migrate);
}
function save() {
  try {
    localStorage.setItem(key, JSON.stringify(state));
  } catch {
    if (storageOk) {
      storageOk = false;
      notify("Keep this tab open. Browser saving is unavailable.");
    }
  }
}
function checkpoint() {
  const { history, ...s } = state;
  state.history.push(JSON.parse(JSON.stringify(s)));
  if (state.history.length > 80) state.history.shift();
}
let noticeId;
function notify(text) {
  $("#notice").textContent = text;
  clearTimeout(noticeId);
  noticeId = setTimeout(() => ($("#notice").textContent = ""), 2500);
}
function scoreHTML() {
  return state.teams
    .map(
      (t, i) =>
        `<div class="score-card"><span class="score-name">${esc(t.name)}</span><strong class="score-value ${t.score < 0 ? "negative" : ""}">${money(t.score)}</strong></div>`,
    )
    .join("");
}
function renderBoard() {
  $("#main").innerHTML =
    `<div class="round-heading"><span>ROUND 1</span><span>${state.played.length} / 25</span></div>${pendingWager() ? `<div class="pending-wager"><button id="resumeWagerBtn" class="primary">Resume ${pendingWager().mode === "final" ? "Final Jeopardy" : "Daily Double"}</button></div>` : ""}<section id="board" class="board" aria-label="Jeopardy board">${categories
      .map(
        (c, ci) =>
          `<div class="category"><h2>${c.name}</h2>${clues
            .filter((q) => q.id.startsWith(ci + "-"))
            .map(
              (q) =>
                `<button class="tile ${state.played.includes(q.id) ? "used" : ""}" data-clue="${q.id}" ${state.played.includes(q.id) ? "disabled" : ""} aria-label="${c.name} for ${q.value}${state.played.includes(q.id) ? ", played" : ""}">${state.played.includes(q.id) ? "" : money(q.value)}</button>`,
            )
            .join("")}</div>`,
      )
      .join(
        "",
      )}</section><section aria-label="Team scores" id="scores" class="scores">${scoreHTML()}</section><footer><div><button id="undoBtn" class="quiet" ${state.history.length ? "" : "disabled"}>↶ Undo</button><button id="sourcesBtn" class="quiet">Sources</button></div><button id="finalBtn" class="primary">Final Jeopardy${state.finalDone ? " ✓" : ""}</button></footer>`;
  document
    .querySelectorAll("[data-clue]")
    .forEach((b) => (b.onclick = () => openClue(b.dataset.clue)));
  $("#undoBtn").onclick = undo;
  $("#finalBtn").onclick = openFinal;
  $("#sourcesBtn").onclick = showSources;
  if (pendingWager()) $("#resumeWagerBtn").onclick = resumeWager;
}
function newSession(id) {
  const mode =
    id === "final" ? "final" : doubles.includes(id) ? "double" : "normal";
  return {
    id,
    mode,
    stage: mode === "normal" ? "question" : "bid",
    answerShown: false,
    team: 0,
    bids: state.teams.map((t) => (t.score <= 0 ? "0" : "")),
    bases: state.teams.map((t) => t.score),
    applied: state.teams.map(() => false),
    deadline: null,
    responded: false,
    expired: false,
    duration: doubleDuration,
    remaining: doubleDuration,
  };
}
function pendingWager() {
  return Object.values(state.sessions).find(
    (a) =>
      a.mode !== "normal" &&
      a.stage === "question" &&
      !(a.id === "final" ? state.finalDone : state.played.includes(a.id)),
  );
}
function wagerSettled(a) {
  return (
    a.mode !== "normal" &&
    (a.mode === "double" ? [a.team] : state.teams.map((_, i) => i)).every(
      (i) => a.applied[i] || Number(a.bids[i]) === 0,
    )
  );
}
function resumeWager() {
  const a = pendingWager();
  if (active() || !a) return false;
  state.activeId = a.id;
  save();
  renderDialog();
  return true;
}
function openClue(id) {
  if (active() || !clues.some((c) => c.id === id) || state.played.includes(id))
    return false;
  const pending = pendingWager();
  if (pending && pending.id !== id) {
    resumeWager();
    notify("Score this bet, or choose Skip.");
    return false;
  }
  state.sessions[id] ??= newSession(id);
  state.activeId = id;
  save();
  renderDialog();
  return true;
}
function openFinal() {
  if (active()) return false;
  const pending = pendingWager();
  if (pending && pending.id !== "final") {
    resumeWager();
    notify("Score this bet, or choose Skip.");
    return false;
  }
  state.sessions.final ??= newSession("final");
  state.activeId = "final";
  save();
  renderDialog();
  return true;
}
function renderDialog() {
  const a = active(),
    q = question();
  if (!a || !q) return;
  clearClock();
  $("#clueLabel").textContent =
    a.mode === "final"
      ? `FINAL JEOPARDY · ${q.category}`
      : a.mode === "double"
        ? `DAILY DOUBLE · ${q.category}`
        : `${q.category} · ${money(q.value)}`;
  $("#clueText").textContent =
    a.stage === "bid"
      ? a.mode === "double"
        ? "Daily Double!"
        : q.category
      : q.text;
  $("#clueText").classList.toggle("special-title", a.stage === "bid");
  $("#answerText").textContent = q.answer;
  const s = sources[q.source];
  $("#sourceText").innerHTML =
    `${q.note ? `<p>${esc(q.note)}</p>` : ""}<p><a href="${s.evidence}" target="_blank" rel="noopener">${esc(s.type)}</a></p>`;
  $("#sourceDetails").open = false;
  $("#answerPanel").hidden = !a.answerShown;
  $("#wagerPanel").hidden = a.stage !== "bid";
  $("#awardRow").hidden = a.stage !== "question";
  $("#doneBtn").hidden = a.stage !== "question";
  $("#revealBtn").hidden = a.stage !== "question" || a.answerShown;
  $("#answeredBtn").hidden = true;
  $("#countdown").hidden = a.mode !== "double" || a.stage !== "question";
  $("#clueUndoBtn").disabled = !state.history.length;
  $("#skipBtn").hidden =
    a.mode === "normal" ||
    a.skipped ||
    a.stage !== "question" ||
    wagerSettled(a);
  $("#skipBtn").disabled = clockRunning();
  if (a.stage === "bid") renderBids();
  else {
    renderScoring();
    if (a.mode === "double") startClock();
    else $("#revealBtn").disabled = false;
  }
  if (!$("#clueDialog").open) $("#clueDialog").showModal();
}
function wagerLimit(a, i) {
  return a.mode === "final" ? Math.max(0, a.bases[i]) : doubleLimit(a.bases[i]);
}
function renderBids() {
  const a = active();
  a.bases = state.teams.map((t) => t.score);
  if (a.mode === "double") {
    if (state.teams[a.team]?.score <= 0) {
      const eligible = state.teams.findIndex((t) => t.score > 0);
      if (eligible >= 0) a.team = eligible;
    }
    const limit = wagerLimit(a, a.team);
    $("#wagerPanel").innerHTML =
      `<form id="doubleBidForm" class="double-bid"><label>Team<select id="doubleTeam">${state.teams.map((t, i) => `<option value="${i}" ${a.team === i ? "selected" : ""} ${t.score <= 0 ? "disabled" : ""}>${esc(t.name)} · ${money(t.score)}</option>`).join("")}</select></label><label>${limit ? `Bet · up to ${money(limit)}` : "Positive balance required"}<input id="doubleAmount" type="number" min="1" max="${limit}" step="1" placeholder="$" ${limit ? "" : "disabled"} required></label><button class="primary" type="submit" ${limit ? "" : "disabled"}>Lock bet · 8 seconds</button></form>`;
    $("#doubleTeam").onchange = (e) => {
      a.team = Number(e.target.value);
      renderBids();
    };
    $("#doubleBidForm").onsubmit = (e) => {
      e.preventDefault();
      lockDouble(a.team, $("#doubleAmount").value);
    };
  } else {
    $("#wagerPanel").innerHTML =
      `<form id="finalBidForm"><div class="bid-grid">${state.teams.map((t, i) => `<label class="bid-card"><strong>${esc(t.name)}</strong><span>Available ${money(Math.max(0, a.bases[i]))}</span><input data-bid="${i}" aria-label="${esc(t.name)} bid" type="number" min="0" max="${wagerLimit(a, i)}" step="1" value="${esc(a.bids[i])}" placeholder="$" ${a.bases[i] <= 0 ? "readonly" : ""} required></label>`).join("")}</div><button class="primary" type="submit">Lock bids · Show question</button></form>`;
    document.querySelectorAll("[data-bid]").forEach(
      (el) =>
        (el.oninput = () => {
          a.bids[Number(el.dataset.bid)] = el.value;
        }),
    );
    $("#finalBidForm").onsubmit = (e) => {
      e.preventDefault();
      lockFinal(a.bids);
    };
  }
}
function lockDouble(team, raw) {
  const a = active();
  if (
    !a ||
    a.mode !== "double" ||
    a.stage !== "bid" ||
    !Number.isInteger(team) ||
    !state.teams[team]
  )
    return false;
  const amount = Number(raw);
  if (
    raw === "" ||
    !Number.isInteger(amount) ||
    amount < 1 ||
    amount > doubleLimit(state.teams[team].score)
  ) {
    notify("Check the bet amount.");
    return false;
  }
  a.team = team;
  a.bids[team] = amount;
  a.stage = "question";
  a.duration = doubleDuration;
  a.deadline = Date.now() + doubleDuration;
  a.remaining = doubleDuration;
  save();
  renderDialog();
  return true;
}
function lockFinal(raw) {
  const a = active();
  if (
    !a ||
    a.mode !== "final" ||
    a.stage !== "bid" ||
    !Array.isArray(raw) ||
    raw.length !== state.teams.length
  )
    return false;
  const bids = raw.map(Number);
  if (
    bids.some(
      (b, i) =>
        raw[i] === "" ||
        !Number.isInteger(b) ||
        b < 0 ||
        b > Math.max(0, state.teams[i].score),
    )
  ) {
    notify("Bids must fit each team’s available money.");
    return false;
  }
  a.bids = bids;
  a.bases = state.teams.map((t) => t.score);
  a.stage = "question";
  save();
  renderDialog();
  return true;
}
function clearClock() {
  if (timerId !== null) clearInterval(timerId);
  timerId = null;
}
function clockRunning() {
  const a = active();
  return !!(
    a &&
    a.mode === "double" &&
    a.stage === "question" &&
    !a.responded &&
    !a.expired &&
    a.deadline > Date.now()
  );
}
function tick() {
  const a = active();
  if (!a || a.mode !== "double" || a.stage !== "question") return;
  const duration = a.duration || 6000,
    ms = Math.min(
      duration,
      a.responded ? a.remaining : Math.max(0, (a.deadline || 0) - Date.now()),
    );
  if (!a.responded && ms <= 0 && !a.expired) {
    a.expired = true;
    a.remaining = 0;
    save();
    clearClock();
    renderScoring();
  }
  $("#countdownFill").style.transform = `scaleX(${ms / duration})`;
  $("#countdown").setAttribute("aria-valuemax", String(duration / 1000));
  $("#countdown").setAttribute(
    "aria-valuenow",
    String(Math.ceil(ms / 100) / 10),
  );
  $("#countdown").setAttribute(
    "aria-valuetext",
    a.expired
      ? "Time expired"
      : a.responded
        ? "Answer received"
        : `${Math.ceil(ms / 1000)} seconds remaining`,
  );
  $("#answeredBtn").hidden = a.responded || a.expired;
  $("#revealBtn").disabled = clockRunning();
  $("#doneBtn").disabled = clockRunning();
  $("#skipBtn").disabled = clockRunning();
}
function startClock() {
  tick();
  if (clockRunning()) timerId = setInterval(tick, 25);
}
function answered() {
  const a = active();
  if (!a || !clockRunning()) {
    tick();
    return false;
  }
  a.remaining = Math.max(0, a.deadline - Date.now());
  a.responded = true;
  clearClock();
  save();
  tick();
  renderScoring();
  return true;
}
function reveal() {
  const a = active();
  if (!a || a.stage !== "question" || clockRunning()) return false;
  a.answerShown = true;
  $("#answerPanel").hidden = false;
  $("#revealBtn").hidden = true;
  save();
  return true;
}
function renderScoring() {
  const a = active(),
    q = question();
  if (!a || a.stage !== "question") return;
  const indices = a.mode === "double" ? [a.team] : state.teams.map((_, i) => i);
  $("#awardRow").innerHTML = indices
    .map((i) => {
      const t = state.teams[i],
        amount = a.mode === "normal" ? q.value : Number(a.bids[i]);
      return `<div class="award-team"><div class="team-score-heading"><strong>${esc(t.name)}</strong><span>${money(t.score)}</span></div><div class="money-controls"><button class="negative-button" data-minus="${i}" ${a.applied[i] || a.skipped || clockRunning() ? "disabled" : ""} aria-label="Subtract ${money(amount)} from ${esc(t.name)}">−${money(amount)}</button><button class="positive" data-plus="${i}" ${a.applied[i] || a.skipped || clockRunning() ? "disabled" : ""} aria-label="Add ${money(amount)} to ${esc(t.name)}">+${money(amount)}</button></div></div>`;
    })
    .join("");
  document
    .querySelectorAll("[data-plus]")
    .forEach((b) => (b.onclick = () => adjustScore(Number(b.dataset.plus), 1)));
  document
    .querySelectorAll("[data-minus]")
    .forEach(
      (b) => (b.onclick = () => adjustScore(Number(b.dataset.minus), -1)),
    );
  $("#clueUndoBtn").disabled = !state.history.length;
  $("#doneBtn").disabled = clockRunning();
  $("#skipBtn").hidden = a.mode === "normal" || a.skipped || wagerSettled(a);
  $("#skipBtn").disabled = clockRunning();
}
function adjustScore(i, direction) {
  const a = active(),
    q = question();
  if (
    !a ||
    a.skipped ||
    a.stage !== "question" ||
    clockRunning() ||
    !state.teams[i] ||
    ![1, -1].includes(direction) ||
    (a.mode === "double" && i !== a.team) ||
    (a.mode !== "normal" && a.applied[i])
  )
    return false;
  const amount = a.mode === "normal" ? q.value : Number(a.bids[i]);
  if (!Number.isInteger(amount) || amount < 0) return false;
  checkpoint();
  state.teams[i].score += direction * amount;
  if (a.mode !== "normal") a.applied[i] = true;
  save();
  renderBoard();
  renderScoring();
  return true;
}
function completeClue(skipped = false) {
  const a = active();
  checkpoint();
  if (skipped) a.skipped = true;
  if (a.id === "final") state.finalDone = true;
  else if (!state.played.includes(a.id)) state.played.push(a.id);
  state.activeId = null;
  save();
  clearClock();
  $("#clueDialog").close();
  renderBoard();
  return true;
}
function finishClue() {
  const a = active();
  if (!a || a.stage !== "question" || clockRunning()) return false;
  if (a.mode !== "normal" && !a.skipped && !wagerSettled(a)) {
    notify("Use + / − to score, or Skip.");
    return false;
  }
  return completeClue();
}
function skipClue() {
  const a = active();
  if (
    !a ||
    a.skipped ||
    a.mode === "normal" ||
    a.stage !== "question" ||
    clockRunning()
  )
    return false;
  return completeClue(true);
}
function closeClue() {
  const a = active();
  if (clockRunning()) {
    notify("The answer bar is still running.");
    return false;
  }
  if (a && a.stage === "question" && wagerSettled(a)) return finishClue();
  clearClock();
  state.activeId = null;
  save();
  $("#clueDialog").close();
  renderBoard();
  return true;
}
function undo() {
  if (!state.history.length || clockRunning()) return;
  clearClock();
  const prev = state.history.pop(),
    history = state.history;
  state = { ...prev, history };
  save();
  renderBoard();
  if (active()) renderDialog();
  else $("#clueDialog").close();
}
function panel(title, html) {
  $("#panelTitle").textContent = title;
  $("#panelContent").innerHTML = html;
  $("#panelDialog").showModal();
}
function closePanel() {
  $("#panelDialog").close();
}
function setup() {
  if (pendingWager()) {
    resumeWager();
    notify("Score this bet, or choose Skip.");
    return;
  }
  panel(
    "Teams",
    `<form id="settingsForm"><label class="field">Teams<select id="teamCount">${[1, 2, 3, 4, 5, 6].map((n) => `<option ${n === state.teams.length ? "selected" : ""}>${n}</option>`).join("")}</select></label><div class="team-field-labels"><span>Name</span><span>Score</span></div><div id="teamFields"></div><div class="form-actions"><button type="button" id="newGameBtn" class="danger">Reset game</button><button type="submit" class="primary">Save</button></div></form>`,
  );
  const staged = Array.from({ length: 6 }, (_, i) => ({
    ...(state.teams[i] || {
      name: defaultNames[i] || `TEAM ${String.fromCharCode(65 + i)}`,
      score: 0,
    }),
  }));
  function fields() {
    const count = Number($("#teamCount").value);
    $("#teamFields").innerHTML = staged
      .slice(0, count)
      .map(
        (t, i) =>
          `<div class="field"><input type="text" id="name${i}" aria-label="Team ${i + 1} name" maxlength="24" value="${esc(t.name)}" required><input type="number" id="score${i}" aria-label="Team ${i + 1} score" value="${t.score}" step="1" min="-1000000" max="1000000" required></div>`,
      )
      .join("");
    document.querySelectorAll("#teamFields input").forEach(
      (el) =>
        (el.oninput = () => {
          const i = Number(el.id.replace(/\D/g, ""));
          if (el.id.startsWith("name")) staged[i].name = el.value;
          else staged[i].score = Number(el.value);
        }),
    );
  }
  fields();
  $("#teamCount").onchange = fields;
  $("#settingsForm").onsubmit = (e) => {
    e.preventDefault();
    const teams = staged.slice(0, Number($("#teamCount").value));
    if (
      teams.some(
        (t) =>
          !t.name.trim() ||
          !Number.isInteger(t.score) ||
          Math.abs(t.score) > 1000000,
      )
    )
      return;
    checkpoint();
    state.teams = teams.map((t) => ({ ...t, name: t.name.trim() }));
    for (const [id, a] of Object.entries(state.sessions))
      if (a.stage === "bid") delete state.sessions[id];
    save();
    closePanel();
    renderBoard();
  };
  $("#newGameBtn").onclick = confirmReset;
}
function confirmReset() {
  closePanel();
  panel(
    "Reset scores and board?",
    `<div class="form-actions"><button id="cancelReset">Cancel</button><button id="confirmReset" class="primary">Reset</button></div>`,
  );
  $("#cancelReset").onclick = closePanel;
  $("#confirmReset").onclick = () => {
    checkpoint();
    const { history, teams } = state;
    state = {
      ...fresh(),
      history,
      teams: teams.map((t) => ({ ...t, score: 0 })),
    };
    save();
    closePanel();
    renderBoard();
  };
}
function showSources() {
  panel(
    "Sources",
    `<p><a href="${sources.lunar.url}" target="_blank" rel="noopener">Lunar Ice Mining For Multiplanetary Travel</a></p><p><a href="${sources.mars.url}" target="_blank" rel="noopener">Relentless: A city on Mars</a></p><p><a href="https://www.starpath.space/" target="_blank" rel="noopener">Starpath.space</a></p><p class="small">Podcast clues use published notes and excerpts; full transcripts were unavailable. Additional clues use Starpath’s website and NASA science background.</p><p class="small"><a href="${sources.lunar.evidence}" target="_blank" rel="noopener">Sourcery notes</a> · <a href="${sources.mars.evidence}" target="_blank" rel="noopener">Relentless excerpt</a> · <a href="${sources.nasa.url}" target="_blank" rel="noopener">NASA</a></p>`,
  );
}
$("#setupBtn").onclick = setup;
$("#closePanel").onclick = closePanel;
$("#closeClue").onclick = closeClue;
$("#clueDialog").addEventListener("cancel", (e) => {
  e.preventDefault();
  closeClue();
});
$("#revealBtn").onclick = reveal;
$("#answeredBtn").onclick = answered;
$("#doneBtn").onclick = finishClue;
$("#skipBtn").onclick = skipClue;
$("#clueUndoBtn").onclick = undo;
$("#fullscreenBtn").onclick = async () => {
  try {
    if (document.fullscreenElement) await document.exitFullscreen();
    else if (document.documentElement.requestFullscreen)
      await document.documentElement.requestFullscreen();
    else notify("Use your browser’s full-screen control.");
  } catch {
    notify("Use your browser’s full-screen control.");
  }
};
document.addEventListener("keydown", (e) => {
  if (
    e.key.toLowerCase() === "r" &&
    active() &&
    !["INPUT", "TEXTAREA", "SELECT"].includes(e.target.tagName)
  ) {
    e.preventDefault();
    reveal();
  }
});
document.addEventListener("visibilitychange", () => {
  if (active()?.mode === "double") tick();
});
window.addEventListener("focus", () => {
  if (active()?.mode === "double") tick();
});
renderBoard();
if (active()) renderDialog();
save();
if (document.modelContext?.registerTool) {
  const lifecycle = new AbortController();
  const register = (t) => {
    try {
      Promise.resolve(
        document.modelContext.registerTool(t, { signal: lifecycle.signal }),
      ).catch(() => {});
    } catch {}
  };
  register({
    name: "read_starpath_game",
    title: "Read game",
    description:
      "Read team scores and the board without revealing answers or hidden Daily Double locations.",
    inputSchema: {
      type: "object",
      properties: {},
      additionalProperties: false,
    },
    annotations: { readOnlyHint: true },
    execute: () => ({
      teams: state.teams,
      played: state.played,
      finalDone: state.finalDone,
      categories: categories.map((c) => c.name),
    }),
  });
  register({
    name: "open_starpath_clue",
    title: "Open a clue",
    description:
      "Open an unplayed clue or its Daily Double bidding screen, without revealing answers or changing scores.",
    inputSchema: {
      type: "object",
      properties: { clueId: { type: "string", enum: clues.map((c) => c.id) } },
      required: ["clueId"],
      additionalProperties: false,
    },
    execute: (input) => {
      if (
        !input ||
        typeof input.clueId !== "string" ||
        active() ||
        $("#panelDialog").open ||
        !openClue(input.clueId)
      )
        throw new Error("Choose an available clue.");
      return {
        id: state.activeId,
        stage: active().stage,
        ...(active().stage === "question"
          ? { text: question().text, value: question().value }
          : {}),
      };
    },
  });
  window.addEventListener("pagehide", () => lifecycle.abort(), { once: true });
}
