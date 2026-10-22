代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gtnvfrdkyi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gtvsimjheu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gtbtkhxofb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shangyingyoupin.top/Article/details/gtrbnjzalw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gtjlkbpblw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ehwqpu.com/Article/details/gtwlmfzcsb.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangdashe.top/Article/details/gtqaqekumz.html

Py:   list(range(0, 10, 2))
来源：http://dali.cqqwz.cn/Article/details/gthdstvdgz.html

PHP:  range(0, 10, 2);
来源：http://dali.ivvv.top/Article/details/gtsabpudvl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtqzugvwfh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gtzzggnggg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtmnfzqcjk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gtiryyuhbg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gtfswiibfq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gttaefinrp.html

[B12] 跳出多层循环
来源：http://dali.nanxinkj.top/Article/details/gtorebucru.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangdashe.top/Article/details/gtnmgehqdt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xziqi.cn/Article/details/gtmszelwtc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtepbmgdxw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtrfwamzib.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtvvlkbeei.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.wangdashe.top/Article/details/gtneisrpac.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guowangkeji.top/Article/details/gtcwjxswuw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.vqdsnc.cn/Article/details/gtyefcoejr.html

[B13] 判断是否为数字
来源：http://dali.pycfn.com/Article/details/gtivumzlan.html

Py:   isinstance(x, (int, float))
来源：http://dali.kuanghao11.cn/Article/details/gthkvqrwas.html

PHP:  is_numeric($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtqgroqdwx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtpibyngrz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gtmnrcausb.html

Java: x instanceof Number
来源：http://dali.birdmap.top/Article/details/gtqfziklxg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ydzc1.top/Article/details/gtrvdiwvhp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.iojbl.cn/Article/details/gtyyyqdpav.html

C#:   x is int or double or decimal
来源：http://dali.xuetiantiany.cn/Article/details/gtemfcpdjs.html

[B14] 判断值是否在集合内
来源：http://dali.xuanzx.com/Article/details/gtasutvgwy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenjidiqi.icu/Article/details/gtpbildaeq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinqigfzy.top/Article/details/gtmbndtlpj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gtfmepavjc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gtjwtmcgnh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtripzbuzh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gtfnvurftl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pycfn.com/Article/details/gtrdkkqrxt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtblfacnau.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gttfkxhabt.html

Py:   a and b or not c
来源：http://dali.nanxinkj.top/Article/details/gtxjfcgiho.html

PHP:  $a && $b || !$c
来源：http://dali.zdqjudy.top/Article/details/gthndlkfgc.html

JS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gturvkimea.html

TS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtzxhztrua.html

Java: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtjykakote.html

Go:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtivagqefa.html

Ruby: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtozrkbipf.html

C#:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtzdwrtltf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgfzy.top/Article/details/gtxsbgqxfl.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gtmaegabtg.html

PHP:  if (!$data) { return; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzkqdvanj.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gteekspcpb.html

TS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtiuhcdtya.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtvghrrszt.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohakbopc.html

Ruby: return if data.nil?
来源：http://dali.chenjidiqi.icu/Article/details/gtyvfokpwu.html

C#:   if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gtkvxfcbpn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgunlnzyq.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gtxjgtibbr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtthdtpked.html

[C01] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtklmdfyen.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsnkldyw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtqvxfdghr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtpkpwwgss.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtroabvfpi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtwpkommai.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj202588.top/Article/details/gtasqjhpyh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlqjmgbk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrimjwojz.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gtadchujzd.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgufenzy.top/Article/details/gtnznslsdz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gtdjozcmqc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtgzczcfdt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtaqsykxmy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hywenlv.cn/Article/details/gtatnzwxru.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tianlin.xyz/Article/details/gtdoqtajku.html

Ruby: def greet(name = "World") = name
来源：http://dali.svipenyu.cn/Article/details/gtfwvbfptt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yanxiufei.cn/Article/details/gtubhhqwud.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gtrsktefjj.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzicohgex.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gthpltfhzv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtysprzaxm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gtbkpizrag.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nwbrower.top/Article/details/gtmluavowf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gteosneaen.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gtynjnfusz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gtcewnjbgd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258.top/Article/details/gtcfjdmeec.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.redwolf501.top/Article/details/gthbnmsfsh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gtljloczmu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gthmbcnrug.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuxming.cn/Article/details/gtlxtedmrl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gtfujflmfz.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gtxdqvskhu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtvizzbonn.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtipowdswj.html

[C05] 返回多个值
来源：http://dali.yanxiufei.cn/Article/details/gtauiltyjr.html

Py:   return a, b
来源：http://dali.hammf.cn/Article/details/gtbqadyazp.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gtmbzimvfl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtxskhdfhs.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gttewdtuuo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgfzy.top/Article/details/gtpiscfgwq.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtetgbyxzu.html

Ruby: return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtyoooejsv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gtbrgtbgjc.html

[C06] 匿名函数 / lambda
来源：http://dali.guowangkeji.top/Article/details/gtifuiyyda.html

Py:   square = lambda x: x * x
来源：http://dali.snrcjt.cn/Article/details/gtdrvlursy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tian-w.cn/Article/details/gtacaodosl.html

JS:   const square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtzexkgfdp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtevcozsfh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjnmhmdm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gtkjakwdpx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gtbkwpixah.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtddafgitn.html

[C07] 把函数作为参数传入
来源：http://dali.quarkkingdee.top/Article/details/gtretesvww.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtcgrobrpf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gtdhwniqes.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cqqwz.cn/Article/details/gteohzjnna.html

TS:   arr.map(String)
来源：http://dali.jinghuilouyu.cn/Article/details/gtetiyvdun.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gtavonaicl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gtdqzuczny.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpymvwsw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yvedp.cn/Article/details/gtjxxbbigd.html

[C08] 闭包
来源：http://dali.yanxiufei.cn/Article/details/gtxdjuxtow.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shuidangran.top/Article/details/gtxlifwfod.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtrepitofs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtgxsyjwfi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtnjxslngi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gthzkbzqhg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gtccbgoaue.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnqzz.top/Article/details/gtrtoauofm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksogkfrh.html

[C09] 递归
来源：http://dali.0kj1m.cn/Article/details/gtbnthalhh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gthptgiojd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pycfn.com/Article/details/gtszeedido.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtdkhtgluq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtmtuiedja.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtsqlpwjsc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gtfvsebhlr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtridpwiiw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhengqikj.top/Article/details/gtxcsqjcvj.html

[C10] 变量作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtsmassbrb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gtapfhifrh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.316326.xyz/Article/details/gtwojqjhpk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gtkpqtgznx.html

TS:   同 JS
来源：http://dali.wangdashe.top/Article/details/gtkbtalhzk.html

Java: 方法内为块级作用域
来源：http://dali.daxiang520.top/Article/details/gtrsmgztxf.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtymfvyqpc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gtargxjohs.html

C#:   块级作用域
来源：http://dali.xuanzx.com/Article/details/gtngocadsa.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gtsfakucjm.html

Py:   from module import func
来源：http://dali.jyoumei.cn/Article/details/gtlyrtkacl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yonumen.top/Article/details/gtgosiejal.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gtggnptvsf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gtxiwrixxb.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gtllgfldvh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gtxpqmsxeg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gtcmswufka.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gtjmzidbmm.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtszhqixhx.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gtjcenuwle.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sxryk.cn/Article/details/gtvrwlxaod.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gtyxyxmmxs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaakrxulr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinghuilouyu.cn/Article/details/gtlngnctxg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gtkdoyslzt.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtohgmxkri.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gtilpjswsr.html

[C13] 类型声明 / 类型注解
来源：http://dali.dashuyun.cn/Article/details/gtoksqslkm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenlongwang.top/Article/details/gtlzffnxpc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtqvoiqmzp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258888.top/Article/details/gtvbxnttjm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtaomoarpy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtcclndcox.html

Go:   func add(a, b int) int
来源：http://dali.9152youxi.cn/Article/details/gtqjqhlnhl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gtuvhtrzdc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nwbrower.top/Article/details/gtbyeaqbqr.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gtitgfsqym.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gtpcyrsyrd.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtdnndyele.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gtqpwfywyz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gtgilgmpac.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gtnbfcvaka.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gtswsujrcv.html

Ruby: # 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtmowtvfal.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gtggqiwalm.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gtfprnqaqc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuanzx.com/Article/details/gtwblqpkqq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdxbktsy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtepmutjez.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gthjupiezr.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtutivkapo.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gtvzwpozet.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtfvoeujhv.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gtipemalmd.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gttzjthrld.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gtkppriaxn.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtifgbczho.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gtqyovqjsy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gttmfrpmnt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shuidangran.top/Article/details/gtxdaeruxe.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gtspnvllan.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gtjvxkkuae.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkqqveskf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqiqyyzmp.html

D. 数组 / 列表 / 集合
来源：http://dali.cucudq.cn/Article/details/gtmbyymlis.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gteyncsgah.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gtuyzjyjrs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gtxticimjf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtmmhmpeom.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtxjbvamnx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gtoukuyszh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuetiantiany.cn/Article/details/gtzqpazqku.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gtarzeqaws.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gtdubxkbvq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yangfankeji.com/Article/details/gtybqpfvkr.html

[D02] 追加元素到末尾
来源：http://dali.bjfxy.top/Article/details/gtsqccsxig.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gtsvgphzkz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkuzpwdh.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtjniwbgsz.html

TS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gthqpncfzs.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gtsetacbkh.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gttkwkcknj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtawszdzyn.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gtadwfmyjo.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gtlxfsjuqd.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gtvvgzinwm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gtuvhpqsnx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gtvezslwvw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspjmigzt.html

Java: list.add(0, 0);
来源：http://dali.sxryk.cn/Article/details/gtgfmcswgg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gtfirrpvun.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xziqi.cn/Article/details/gtxivgvabf.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gterdjjuho.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gtoootrxrf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtnfqgefwc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gtoehwhiyu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuxming.cn/Article/details/gtacytcjnh.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gtuhmbbdnk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gtnnztyayf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gtmzzazqhq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gtvifwfnre.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.iojbl.cn/Article/details/gtvofdedec.html

[D05] 访问与修改元素
来源：http://dali.ppjwa.cn/Article/details/gtpuybkjcc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtyfnsfzli.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtujpdagem.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtbeagxfsd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xinyue.icu/Article/details/gttmjnucnx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgufenzy.top/Article/details/gtjalbvlef.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gttrdxrbdi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtgppijtwx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtofwszsnn.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtadiepljx.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gthsxearwb.html

PHP:  count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusaayvls.html

JS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtxjaimvnf.html

TS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtzkzbcykt.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gthozrubck.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtuvzkbcgv.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gtuhpejbmh.html

C#:   list.Count;
来源：http://dali.hfpthk.cn/Article/details/gtwgjapkia.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gtwjqqbaar.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sweek.top/Article/details/gtyerrjcbh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gtzgyujdku.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtoyeodorj.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtpuvhhbhx.html

Java: list.subList(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtbcgtqjde.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtmuyopmdg.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtjhhaswpy.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtinibcvsy.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gtxgpbkdin.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmdqrymq.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gteicgwbpd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gtfpobskfg.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gttfhzdaoe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctgfwxbz.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghezexlr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangdashe.top/Article/details/gtymbphzqd.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gthfbieyhp.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gtwknyvlbm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gteuwtkpzq.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gtguownkfp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gtlpfxgtfo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtlctilorr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gtjplgqmhz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtrrzejacq.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gttaeiptfo.html

C#:   list.Sort();
来源：http://dali.chenjidiqi.icu/Article/details/gtfrueigep.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhiwuduotai.top/Article/details/gtstajyfby.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gtzwbhfkly.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtttywqvoj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtsqmgdqiv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtyswltpss.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjahhvur.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gtslivmwpm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gtruvfhfer.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gternttfjf.html


<!-- 参考信息 -->