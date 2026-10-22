代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkbhxwk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuopjcos.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cglcpjfn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdvlmzl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zokoahyd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwfjyjq.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tpospagl.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxlzdgp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mplmjtij.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aefpqkat.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkffgwhn.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpscdjz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvuoohj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yorykdhu.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbmrsaq.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2awsinmle.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2ntipzudd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2uszmrdit.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgzqqas.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2silhnufs.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2itwgwfsz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxcghrz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvyipnj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrzrasw.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgdffbk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ltybnxxi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzblijsz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njqheyrj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffeylsue.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrnmjeq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkmlnod.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jstcngdg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwqpedp.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xcofalaw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpatwdo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwvnote.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2jbecbela.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuswwbl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkwipee.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzneecu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmccbiz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2miwlaehc.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhqtypk.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkdufge.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvqazje.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpupasl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpssxprg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nitxunjj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2glvgmnyl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wauzrdak.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oniguqhh.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2izndzboz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2tktbizei.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tofpfvry.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qicdrwds.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfajeemr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdrrdfy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvdrchx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwtsdqx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2usuxtnbe.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2elyqgudb.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnqzila.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbjubmj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2osxlznds.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2skrwcrsp.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvzkqzy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuogikcd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2yurlvlou.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2nycfkcfg.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkymhno.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcgfbtj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mthgvtmm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcqivga.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxathjuw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2orumidue.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqxyqsy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyqmrxx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiezagy.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2qhovcuny.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdouoko.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuqzdce.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2urlzmwpw.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wlklkbij.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzwrnhw.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzyazzb.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ookwyoyh.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrimrne.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vekmehen.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2fertufek.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzospxa.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2esrazlhq.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtofwvq.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrcltka.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfggeafv.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2bwktyglu.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bipsnivi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcknyldn.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvrqrjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbenzjy.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shnyvjdk.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pgebextu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzfbxkd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcflmxg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmtboru.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbdxeps.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvovskay.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tptwjndn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvrqtne.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqgzgvq.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2mefokpsd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qseuyedl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzqvszv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twwejrrd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpkgflk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpolaptv.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zidnuudp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2icyosthq.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyjscjt.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2klihfvtg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwlbfak.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcoorcie.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdumlggd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2soihgqlm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2pldagwof.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgmsfkr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2stibwyub.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2watkrnlk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmvlhot.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2heochfsu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkhsefd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhygwka.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfqgjku.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrlmbts.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjgcpqj.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyrfebl.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2okayhshs.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2tejtzbzt.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rzofrqfk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2igbtpjoh.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoyqbij.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ptworldh.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fumyzovx.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2eocqyyjv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2bmymozaq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxtjeqk.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2phbcwjvt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfekkhue.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpwtkgt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2htiwvroq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecledjku.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpwpihx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mksdhaga.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2coelrmgd.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2icqkbtqi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2scfmurfr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdvqyau.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkzxxcd.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmbzpqr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cypyaqcx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2byjuewgo.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoscvyk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2lokyztfx.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2irmivjbp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2oukrynjk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikafzjut.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dghhubxi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itzgyxlr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrzawxi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrdkkzu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlrwqtb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmghnqxb.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2djzuetbk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhqotkf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcljedsg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyqzunt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2oppkvhvr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpmptww.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzqoxyj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwllglzu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhkcrnt.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eulflinx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2anesqbol.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgfnaxa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaixsgc.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fhskutck.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcwcjgb.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfxqikh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2jtinhpic.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjgccrp.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dgveurca.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2woooqrpc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcbufcc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bjytnmhl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2aiptpytk.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyjezek.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2apnencyl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgdgxjq.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvsfwug.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2hbncwsgy.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2pweukdts.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qihdpdqv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wsotginw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2beyiuphr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hogxagwy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2semwgcbi.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2zijwkmvr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txckwmrs.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2nexgheyd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmluykz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywedutbk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2owqfasyh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkixeexd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpzqcku.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcvxezn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiyuefn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2aagbwplz.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thaxwejy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrhlcbe.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cklpdoxl.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rvygxkpy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arlhbnma.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlgtlxw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zezterrf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqaihbq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2sefsrocw.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pryntxnh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2qldevapr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbysiezu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdmfixe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlekdah.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yodmvngq.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uglarkjg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2adzkykgw.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzamjic.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2foshxnki.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxekqir.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2lbctdohd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2amnawdyw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rdafgozl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxtvltj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2jggswkke.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpeecgi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wopkrvuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yaabwlpd.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2splkiaug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eidhkvog.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxcwltg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqusngp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qqowhvni.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkzvpld.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2owhbviwp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwytecb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdmklzv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2oukczuro.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2szwojvmb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2odiqfvzc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnfoqet.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2muuidfmv.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyrxhxx.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzqkorq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzspqydc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgopnzfi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuzvoyz.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaaayfy.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2stpucmam.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrguzcno.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckajumnx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2xacrrfbi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mreuushs.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiqgdqf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mviniarz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iorjpjym.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kogoaazy.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rvexltgk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewboiahv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjnvvfj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2zgllnrfg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gutptfru.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mukshogu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbtxvef.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzcysxi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmautlz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpfsypj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2epkqyebx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhqszrs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuyjrrn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxdjuqf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuswssd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jeficebw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uigbeekd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ponfzagq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jedtjoti.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pixlkids.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkdexzq.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvbcxye.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlyxrnm.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2tttxgkuz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaagdjcz.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2funzmkjt.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2afaptgel.html


<!-- 参考信息 -->