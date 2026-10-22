代发 wailian999

[B09] break 与 continue
来源：http://dali.tanke756.top/Article/details/gtdfwptllw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.bjfxy.top/Article/details/gtrdqxtysj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtxpibgbam.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtuzunuhor.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gttdhsxclc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtsiubikfu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hysaishi.cn/Article/details/gthfvwulxy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.feifeiyinyue.top/Article/details/gtworopzny.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtugaaagyg.html

[B10] 遍历同时拿索引
来源：http://dali.redwolf501.top/Article/details/gtrulmcrlc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cqqwz.cn/Article/details/gthgxrnpgp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nanxinkj.top/Article/details/gtwqlsyehp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yangfankeji.com/Article/details/gtsulqltbr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gttsfxwubj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yanxiufei.cn/Article/details/gtsrwxjwgi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cashguo.top/Article/details/gttrabkehy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xziqi.cn/Article/details/gtqtxfpzbk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jlsjyb.cn/Article/details/gttqvebpfl.html

[B11] 生成数字序列 / 区间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvvrsmya.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxuanxn.top/Article/details/gtdxruxwou.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gtlgkyykre.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gtawgbintj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gtunnvztbz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtliuvsnyf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shuidangran.top/Article/details/gtmorgrpcm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258888.top/Article/details/gtcwrfxvtj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtvhkfgkka.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvwanqdt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gtuhftihku.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shangyingyoupin.top/Article/details/gtglxtytyw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtvcvlqirw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtnglqzauj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gthefhfdnf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cashguo.top/Article/details/gtglzkpwmg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tian-w.cn/Article/details/gtyphsilhr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shangyingyoupin.top/Article/details/gtksiejvwp.html

[B13] 判断是否为数字
来源：http://dali.nwbrower.top/Article/details/gtepmhjfge.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtacjwjnrn.html

PHP:  is_numeric($x)
来源：http://dali.tian-w.cn/Article/details/gtnlufieoq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gtncvtjazi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtrzpixvhv.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gtrlykisay.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrblcyfb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cdnleiting.top/Article/details/gtzcaytyso.html

C#:   x is int or double or decimal
来源：http://dali.cashguo.top/Article/details/gtprjvkchn.html

[B14] 判断值是否在集合内
来源：http://dali.hysaishi.cn/Article/details/gtuumpeing.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhongyouzk.top/Article/details/gtossjyswv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ybcxt.top/Article/details/gtjefkswak.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gtkugbjewt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gthqxaweue.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gtsqbslafp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gtkpyvepgx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hysaishi.cn/Article/details/gtlcymwynp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtgpyujuqm.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gtsarjjjes.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gtxubhrilj.html

PHP:  $a && $b || !$c
来源：http://dali.yonumen.top/Article/details/gtlsuninmo.html

JS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtbesvxdxi.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtuxxdlvqo.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtdstndarj.html

Go:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtxzswwuam.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtfjiypvej.html

C#:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gttqfxfnba.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gtuxvpzehh.html

Py:   if not data: return
来源：http://dali.snrcjt.cn/Article/details/gtigsqqsag.html

PHP:  if (!$data) { return; }
来源：http://dali.ehwqpu.com/Article/details/gtpfbxborv.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtgxcfqcee.html

TS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtnaounprp.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtvsogshit.html

Go:   if data == nil { return }
来源：http://dali.tanke756.top/Article/details/gtzaxgoaae.html

Ruby: return if data.nil?
来源：http://dali.cashguo.top/Article/details/gtmgbpnjrv.html

C#:   if (data == null) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjjmpwno.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtnnkwlboa.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gtihokbzhp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnehwommx.html

[C01] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtmjedhihn.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gtvrntmgrf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtfddeqcyv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtpqozbmcd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtpbxfuwge.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtrluwgxsa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gtdqybxbph.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gtutwbnjdd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtkcbifvft.html

[C02] 默认参数
来源：http://dali.nwbrower.top/Article/details/gtxazyfoxs.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gtjugsdzml.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwgfgnsmh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtjteyprpm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtiklagxny.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gtqkzaektm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sxryk.cn/Article/details/gtpmutnmhs.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gtntgjybne.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnqzz.top/Article/details/gtzgwnmrog.html

[C03] 可变参数
来源：http://dali.zycfv.cn/Article/details/gtuagtydkw.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gthiswknqt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gtsvdeldyj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gthhcakmjo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gtrxshaiof.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xziqi.cn/Article/details/gtykdspkrx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gtxpireynf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gtwlvbwtdw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hywenlv.cn/Article/details/gtwodlrpyb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gtgtaaucgf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxinkj.top/Article/details/gtaymfihci.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gtnhkruyeh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gtblekhrkv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gtchaqhohi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gtvwshtuip.html

Go:   // 无：用配置结构体参数
来源：http://dali.yueranfly.top/Article/details/gtkkeyfhgo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtwmatpzlj.html

C#:   f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtmwrklbrk.html

[C05] 返回多个值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarqtpmmo.html

Py:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gtsxivjzwh.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gtvomvrcsf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtubvrscnq.html

TS:   return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtyobemvlj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shzxlz.cn/Article/details/gtjwnnlwdh.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtjzyddqis.html

Ruby: return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtqcynjvea.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gtinhmblbd.html

[C06] 匿名函数 / lambda
来源：http://dali.jyoumei.cn/Article/details/gtyusnnfjq.html

Py:   square = lambda x: x * x
来源：http://dali.haohaochexian.top/Article/details/gtltowwdgp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gtbjmelfme.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtmyoxvjrn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtbsddnzmu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtvqugbgbr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cashguo.top/Article/details/gtsqnswzgu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gtfzezymty.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtbeubkyzs.html

[C07] 把函数作为参数传入
来源：http://dali.yueranfly.top/Article/details/gtdtiyvpaj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.andypj.xyz/Article/details/gtpyratiai.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtiwsfqagh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258.top/Article/details/gtkygambuj.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkfpqnkk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gtdfzyqhat.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj202588.top/Article/details/gtwrqwpkdp.html

Ruby: arr.map(&:upcase)
来源：http://dali.fengsongda.top/Article/details/gtxflzrcoo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aizwys.cn/Article/details/gtezksifcm.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gtfvkqftrn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gthtpfvvrm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtovmboaco.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtjjginngk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtzyflzqzx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.andypj.xyz/Article/details/gtessktcsb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gttfnrhkdn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gtwgslxkmi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtkltmivak.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gtovtrhcqv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtfmlsicfj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtfrtrwfbc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gtvhovxgzd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtkbstxujx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtzjkxrsgm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gzhubu.top/Article/details/gtxlgshshc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtshzevyuj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtmlpowtht.html

[C10] 变量作用域
来源：http://dali.yangfankeji.com/Article/details/gttwovkutu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xinyue.icu/Article/details/gtgwgremff.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yvedp.cn/Article/details/gtjltwnbei.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gtkebpdxox.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gtnnurhuur.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylcnnugm.html

Go:   花括号块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxyqboqy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gtnkbnrdag.html

C#:   块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtwkospdff.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gtulmkhema.html

Py:   from module import func
来源：http://dali.ivvv.top/Article/details/gthhzhenkg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xylfe.cn/Article/details/gtfrqwobwd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgilfqnou.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shangyingyoupin.top/Article/details/gtxdcxqywt.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gtwsrrbtit.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtxdpgiprh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zdqjudy.top/Article/details/gtichvlwgb.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gtkpxnrklp.html

[C12] 立即执行函数 IIFE
来源：http://dali.0kj1m.cn/Article/details/gtgjbxbblg.html

Py:   (lambda: print("run"))()
来源：http://dali.yuanzhike.top/Article/details/gtaggivtmo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gticbugljs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtvaaiuvto.html

TS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtgjrvgqks.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gtipdnlewr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gtiiecxnhx.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtjfdslmfm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gtrhheukiw.html

[C13] 类型声明 / 类型注解
来源：http://dali.tanke756.top/Article/details/gtibiqginm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.meibo888.top/Article/details/gtnksbvyxr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtiodaahao.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gtqrwucceh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtutlsrwfi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtzfcstysu.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxcciifh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhrthzgi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.havefunace.top/Article/details/gtpqqcwede.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gtvowjqfwa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sysykeji.top/Article/details/gtqbhplzlx.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtgfsepzyk.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtkwifoncg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gtliwosczh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gtvzswwlyl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gtsdkvzggb.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtsbgdpkju.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gtwvnxwuzj.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiieahmjl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gtgwnfijym.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gtmxlrnheg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtmiwhnyzs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gtwovzbhvk.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjjyikfh.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gtrtckrusz.html

Ruby: a, b = pair
来源：http://dali.ydzc1.top/Article/details/gtokwvxued.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gtzdvxuoyz.html

[C16] 函数 / 方法重载
来源：http://dali.nanxuanxn.top/Article/details/gtcesvyxsa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258888.top/Article/details/gtrgllqpje.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gtkzsxgrbl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtckoceqyx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gtcvuxtyxg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daxiang520.top/Article/details/gtxjfrkonf.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gtsgslqluu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gtwswbptfs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gtqnfrnscg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqwslcnxw.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtqhiranyh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqxllqpkm.html

[D01] 创建数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtkysilaeg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuanzx.com/Article/details/gtulrivjzg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtnktkouyz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gtgwpmrkfm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gtpbbmiqrp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuanzx.com/Article/details/gtnkmmhmpy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtizznevlo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtbpyjcoou.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gtimlmdqxx.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtcgrtiozf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gtokkupqaj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtzxwkdqmy.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtgpairwvi.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtgweoxfyw.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtxcuobzgy.html

Go:   arr = append(arr, 4)
来源：http://dali.dashuyun.cn/Article/details/gtdendtgjd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gtplduibct.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gtenxuotrp.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtdkoxxvoq.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gtkvgxljym.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cucudq.cn/Article/details/gtgmuuvgxe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xylfe.cn/Article/details/gtraiyneek.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gtvdczbhsl.html

Java: list.add(0, 0);
来源：http://dali.pycfn.com/Article/details/gtblszzbzb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gtexxpaxzd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqjczxwo.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmiipxkl.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtzmgxrsig.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtslgmkcye.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cashguo.top/Article/details/gtswtddfsw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gtomrerxrb.html

TS:   arr.splice(0, 1);
来源：http://dali.fengsongda.top/Article/details/gtwtrziwgh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtrovlkabh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtajyaacec.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gtivksdnoz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dashuyun.cn/Article/details/gtinsmandl.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gtnsnnbktg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gteqrapcgu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtaekgzoou.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtuapngbvo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gtgncvspac.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnsowvzl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtaayuuwre.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtvpalgtzo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtmgpmpihj.html

[D06] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtszucbkfi.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtphgjdojz.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gtinakeehd.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtarlqazan.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtmldfteec.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtagbctxnw.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtyresmshd.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtawfovosi.html

C#:   list.Count;
来源：http://dali.redwolf501.top/Article/details/gtfjcigzwd.html

[D07] 切片 / 取子数组
来源：http://dali.gaohongyu789.top/Article/details/gtcxfdmiol.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdinpbyf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gtawmvdlod.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtcuawmfsi.html

TS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtztdbmjti.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtpwditbnl.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtvlpqwmdf.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gtmewqfiet.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gtkgskbzof.html

[D08] 合并两个数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxjgsrzl.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtlwsyvimr.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gtkyzrwcqz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtzzryvobu.html

TS:   [...a, ...b];
来源：http://dali.cucudq.cn/Article/details/gtwbkqrmzq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gtpwhzxosd.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gtwhoklujz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258888.top/Article/details/gtsvmtiwfs.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtdfrrydsz.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gtkimfurmk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsisaseh.html

PHP:  sort($arr);
来源：http://dali.wangdashe.top/Article/details/gtaqfhkzaa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gtzzoazzdf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gtcxdpdgsf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gtdajwmthc.html


<!-- 参考信息 -->