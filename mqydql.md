代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhittzrg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnllxrqf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmklsotk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpsklii.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aecbxoen.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdoaqnp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2lftcydhs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wasptamf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2vimpvono.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcmficb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2crmqgpav.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2swxakeay.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqdivyg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtyvwfa.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzwmlob.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsikcypl.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvonrwaq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2amankuyx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwqxtxs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnteokto.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnxuafn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2eszgoahm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzffztn.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwkuuzy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2tallqqfz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xefsavvd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuknrbk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2khuhzpou.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2clqfrvtl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgtpart.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xkngymjz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjkgqnm.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zavvzyqm.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvutjilf.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuyvfsl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyysucl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wszxxmnx.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsdxkea.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuwkppu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2alluviis.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnnnpak.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2molpdjba.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvgncht.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkfwnii.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnygzuhn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxvdxcy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpynabwq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tamdzyld.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2naowfrrm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2obgjkqge.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzsogsu.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2cchmemwb.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ulejgede.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tunsgvhp.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2slzmumct.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcanhdz.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rgimsbwf.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yimcugvc.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeortee.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuwsjub.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkitmde.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cggfjain.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjabyhl.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyeyimo.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkfqunc.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvjsjgu.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2stnlsttx.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzplkza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbevvahb.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtzhjuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnahesk.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2msbsmdpy.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2grrivawg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzzypzp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atxhrjsf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txwfqqiv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byuprffy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiklmyoj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2htdqykbm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcfucyq.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2thaetlkq.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqupavm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvxclkp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkllgyq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njlptjvp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2snojcjaj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvqfipa.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhpglig.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxakcte.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nruhtbks.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzyzyjo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxtxgvf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwjgzof.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yguuzvop.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzwtrhz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2bczzdzcv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2etkkzvju.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyyiodn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbauobnb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2irdvjwmi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvzgbyr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgohkzgo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwlsuzp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqzdqnh.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eccbowir.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciigalby.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtbdpci.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrweazrk.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpjktwe.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2aedgrvcm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zolohrcz.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjfmogd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2sryvkpoy.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2oueywlww.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxlqkml.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpskgii.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jorqqzys.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2egomwcmk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxzrxyu.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbptzqfl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2okmkkfwg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwwqaof.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrrmpmt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiicipp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnccsxl.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoetoqw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2sabrtwgp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nozicioc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2iertwjtb.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2putnabdk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ephvnkeh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyeqfow.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfwahoj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2lobnxsfp.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyiyzbv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2quwmvtth.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpjczur.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utyaohpr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sewvuvop.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjkpnci.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqknnoxm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqwwwet.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuwtsbw.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqooooi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iikesquh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfhnsil.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vaczjezu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2czawrqlv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2koktcaub.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2edpctfsh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oksmjmmz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgxhwwb.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2prpsbsyk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2xaykaikr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxnbhxs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrprcpp.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvqwjme.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbkvwru.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2crwwqovj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2httvvqmu.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eptphohn.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfeubrh.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2iieyoneu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyvkicg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2udkvjpdr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2krwbairv.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtqotkl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2riuduirl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmjxiui.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrbpeld.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2sxleykpj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnncbntw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2uinbgdao.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgfzysx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lieqvese.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfawoyc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2izdskefy.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdytbnh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbeyjma.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ttulkyoa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jldpghqr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjoahfk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozadcxdj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtsohuw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmjcqde.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlcpujn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjvovld.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgrerln.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2orfjelvw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzhkifd.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzxyaom.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhstjkl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwamjoat.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdbplai.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nimidvau.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjahdea.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrgjbdy.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqomnusn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2nurqhbrp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqmvctd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxlmuwn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wushtzmy.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oweltvos.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbeqzdp.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpkpyuv.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2opipeaev.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzyqtbi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2oebljyej.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2nspcmqzh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2esumssqs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvzksqw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaenauz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsqappq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgqyjpf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsshlbak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfohgra.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2bujvddrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akpeblvc.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtzpmqv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2pljmsoln.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwwqmgo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xndiwjqp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2hettjcag.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlbddbm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfepiwe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvulcas.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdshafi.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuscchf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gulvjhta.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fumpqypm.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnobbhvr.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yunnpjna.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bonaqxgr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmxxzut.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwragii.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhndgmj.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnthnfs.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhmmhjf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xosjocbc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbvocfa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zajqfsdt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnzptti.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tusrpbuh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oisikjjc.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfpopfq.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjjbmtk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2psspygzs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgmzfmf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2dshzztuq.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgazrhd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxnfzyr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwlzzuw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hazgzehz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfgbjqt.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgtmonc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzwgnrf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsfbhuw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvkaess.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioewodbt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsbgskd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcmnoxs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qwynzjdx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiumrars.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdakdss.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekstockb.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nazubasc.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nznkwhzk.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwhlgkj.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtgvppj.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffirxxix.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdghstz.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2uubueoim.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2avxzipuv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlxmkwi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrawybqj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2txpklgpf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxabtzf.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2voqqgiyz.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfrmopq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbzzscm.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyydbyqi.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2alxjryla.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpqfncb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zccqjnuu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhslnojt.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ngltvlvd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqxjagm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tywarqlu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eykzhgfj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhtanfz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2amccgdzr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgzkmrh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vijqhugs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqrqgtm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoelvjm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xizkxcou.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynndpgis.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwfiorn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzodjxjv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjhxpsg.html


<!-- 参考信息 -->