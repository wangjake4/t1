代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvylqsfa.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2spnrtgja.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpwwqlv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2htngnidk.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2utlfgydd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lcadrudi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqgqmco.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prmbdoqc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dulbqppk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmqgrty.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwkhpkd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiulknkf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqhszbe.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bejyswjt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbbhutc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeftmkz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnlzyfz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlpcded.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyqaxho.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgeyksd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtsrlix.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiggzfr.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcxsils.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxdszsj.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiufnbk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpurhfxp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzemdwe.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oupqbxei.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpuhihq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzfbtxi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjiycld.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkuanwx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2siwddiwj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2goizvuns.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcihkkv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjqhbds.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwdlkvp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sptkcdlk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxbnvca.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2arimwzmj.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cflffchy.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpbgcax.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yskshuox.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2egrouaho.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2czsjraqv.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfnwncf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2txbwmbcj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjvfytx.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxmwgvy.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2twfxacza.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2ethoyegk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmltvwv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhglgok.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyzpthl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqsxnyf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsouqeb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlsqjry.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyghmbp.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2scnbyshu.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvxgusi.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvipgbx.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rhshhylc.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyhpahr.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2emmaisda.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaslfbz.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mgocgyev.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdomusj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hemqkudt.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnwytxz.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcijnlzh.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gngyovmx.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2iurszfiy.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2svlgnmef.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2owyrarkw.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ccehawpa.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqawmjsy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaijpln.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gyupdfct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrpmpdy.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kukcwoot.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2irqbxdnx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edpylfpm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2radsttwm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqyclgy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmbfwzi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmteurw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlyzbjh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrxyutr.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2piklhmqj.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkfgfoy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axiqrjio.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjghjnm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcutgfb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhqnefk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhlggvf.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qsloqtbw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2syhcccgx.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2afcxforr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fycerfyq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdveomc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fugybbgs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjobhlg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnzfhto.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2censqfeo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iodwkpah.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2olaigyol.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qolzfaqy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsjeosr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aiegazas.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oddjuslq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dbktcyiy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrvusgi.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tedzebrb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmglxeb.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbyyulw.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmlrbai.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2luvhwyce.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2urhbthka.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoizcgs.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgjhwlw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2xaawgilj.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwvkncx.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vavxwxbg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2fguoymuw.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vpklicsb.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2gehfzctz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmtrnme.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqakeae.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqselra.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpjqpao.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqampge.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsjdpmr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoyxhpm.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoygxxt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbciizt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrttjmw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2onvqdsyr.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2evtqpzuu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuwhwpn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2etmrejjo.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyehugy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2rvltiqky.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rhscwnel.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsigita.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhddojy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brnqaejr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxmpxot.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgqdirj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2svukyoin.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nyejlewh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoprlfk.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wztvalfv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2owtiynpf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnflpemq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmbvtrb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mgboldcj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwedhmh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjxwehy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrszgpl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfrxxdm.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuonuii.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2kyipscpd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkgxhao.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfrjigq.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqbpgoq.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qompzesb.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2iectinwv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2urkjqyvu.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bowywqmt.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2immjqulu.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvgacps.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2raylowyu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cezduwzj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vumbkkav.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2mssqgbyt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuvmzix.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpyjseo.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2gguqkexf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2awtrveqk.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2zygoghev.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaqzwzm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2itlmluiz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dynoxdpo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkvlihb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsjiygh.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjkpncd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnpbcqq.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2gpebatpo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xihedzvy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhptyoz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrcgtoz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asfigjeg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfvndzn.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzvefkj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2aumfoczi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvpobtt.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkkfsni.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2edmzujzl.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmougvd.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxrvrbe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsokyvdh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dngxanmj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pefcviin.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2axhwgvvs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhxyxzn.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhqxqgs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrpaoqf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2layfinvx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrqksgc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnqermr.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2puqwifbx.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rhysguiv.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpbzomp.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpxswlf.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zywxuiok.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gihbbewv.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2sztdpgld.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvohkvh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbaczbr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwwgwnu.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwswcde.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2czwdtutt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrwgqpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exfmcgnj.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2otemkuxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwazkjec.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtyphtd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2chulvwco.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvpxhac.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2anmolzcr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2slunikyc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2nymtmhtd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2fttymqjg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2whbamhgu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxwtkob.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mshzjnqh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnbgrcd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2akbakylo.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjoblow.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbmtvjq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pordyxjc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2clpapatn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdbayee.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozylhofx.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqalexk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqdiktu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2atocahiq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2uevjzpyt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nznzoajc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2feiocjrb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rblfksvg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoiyqdc.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmllgqg.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nizdxfxd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbagiea.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2omdqcwid.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqeknwa.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdaxzri.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xctrqbbu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2txhhuqtq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpzqmeg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzctgke.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xknukqlg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgepzld.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfrbfxd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2stmttmyv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcfhbhy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkotzqo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2imcjrcjb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdayphp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2axvwdcmh.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dxasgshw.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vujfamni.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2soarkwzq.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2udirjvnl.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiiduqn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2aaivedri.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hancghub.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlatfdh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzubzluv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzoxmid.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2rulloety.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pobyuxks.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuucmxy.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpuxzwh.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vekwlbnb.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuoexpk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2aaawntxt.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iixqazhs.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhsykhz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeebnhg.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiugcoyi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkvbtkb.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2euicstsr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwqjhsj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmyqizg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxefqjr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdzhmif.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2gducyhdi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuyxetq.html


<!-- 参考信息 -->