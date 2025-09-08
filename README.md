  <!-- =================== README (inline for convenience) =================== -->
  <!--
  README.md

  Q1) var, let, const পার্থক্য (সংক্ষেপে):
  - var: function-scoped; hoisting রয়েছে (declaration উপরে চলে যায়); same name redeclare করা যায়।
  - let: block-scoped; hoisting নেই (temporal dead zone আছে); redeclare করা যায় না একই scope-এ, but reassign করা যায়।
  - const: block-scoped; declaration-এর পরে reassignment করা যাবে না (immutable binding), কিন্তু object-এর ভেতরের প্রপার্টি বদলানো যাবে।

  Q2) map(), forEach(), filter() পার্থক্য:
  - map(): প্রতিটি উপাদানে একটি function চালায় এবং নতুন array রিটার্ন করে (একই length)।
  - forEach(): প্রতিটি উপাদানে function চালায় কিন্তু কিছু রিটার্ন করে না (undefined) — সাধারণত সাইড-ইফেক্টের জন্য।
  - filter(): প্রতিটি উপাদানে predicate চালায় এবং true হওয়া উপাদানগুলো দিয়ে নতুন array রিটার্ন করে (length কম বা সমান)।

  Q3) Arrow functions (ES6):
  - ছোট সিনট্যাক্স: (a,b) => a + b;
  - this lexical binding পায় (arrow function নিজের this তৈরি করে না), তাই callback-এ সুবিধা হয়; আবার constructor হিসেবে new দিয়ে ব্যবহার করা যায় না।

  Q4) Destructuring assignment (ES6):
  - Object destructuring: const {a, b} = obj; // পরিবর্তনশীল a,b টেনে আনে
  - Array destructuring: const [x,y] = arr; // অবস্থান অনুযায়ী মান নেয়
  - Nested ও default values সহ ব্যবহার করা যায়: const {a=10} = obj;

  Q5) Template literals:
  - Syntax: `Hello ${name}!` — backticks ব্যবহার করে expression interpolation সম্ভব।
  - মাল্টিলাইন স্ট্রিং সহজে করা যায়, এবং সহজে variables/expressions embed করা যায়। পুরনো string concatenation (+) এর চেয়ে বেশি readable ও expressive।

  ---------------- Suggested commits (আপনার Git history এর জন্য) ----------------
  1) feat: initial project scaffold (index.html, tailwind CDN, basic layout)
  2) feat(api): add categories & plants fetching + demo fallback
  3) feat(ui): implement card grid, modal and responsive layout
  4) feat(cart): add to cart, remove & total calculation
  5) chore: add README answers and comments in Bangla

  -->