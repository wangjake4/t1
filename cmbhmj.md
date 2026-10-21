代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.fzhhl.top/Article/details/gtwjyxvwpg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtxeoqdfet.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gtwwhseghk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ppjwa.cn/Article/details/gtnztnmaqd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenlongwang.top/Article/details/gtepzkcyrl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.vqdsnc.cn/Article/details/gtygenmjnq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cashguo.top/Article/details/gtbwexjpgn.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gtcpdpbnbj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jlsjyb.cn/Article/details/gtopcrzdew.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangshuangyany.cn/Article/details/gtxrsrbxju.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gthoqybhot.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtjiehjwau.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtqegcqipz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenjidiqi.icu/Article/details/gtjlhbdhkp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gtxiegrwcj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenjidiqi.icu/Article/details/gtrlobkqml.html

[B13] 判断是否为数字
来源：http://dali.cqqwz.cn/Article/details/gtghtgcmhf.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinghuilouyu.cn/Article/details/gteotasmwx.html

PHP:  is_numeric($x)
来源：http://dali.aizwys.cn/Article/details/gtriatafqi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtufpenrgr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gtjfoxexaw.html

Java: x instanceof Number
来源：http://dali.guowangkeji.top/Article/details/gtfqsirusr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtchdyggbp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhoulong.xyz/Article/details/gtzgaletmr.html

C#:   x is int or double or decimal
来源：http://dali.yj20258.top/Article/details/gtyqnegqth.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gtbjayykmi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hfpthk.cn/Article/details/gtgspaxond.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinqigfzy.top/Article/details/gtaezfcxcj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtyvtrbemp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtzlwhzacb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtvnmoxliw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigufen.top/Article/details/gtonqgehmr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtprktnxxx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtzhjpgrvx.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gtitfqvxcf.html

Py:   a and b or not c
来源：http://dali.hywenlv.cn/Article/details/gtlqnyrcwd.html

PHP:  $a && $b || !$c
来源：http://dali.ybcxt.top/Article/details/gtuhnoyrah.html

JS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtdxxvtzdw.html

TS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjeliujz.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtcypayyhn.html

Go:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtaapmjzwl.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtfftqmlnh.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtuklxqncl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.svipenyu.cn/Article/details/gtnkqicqbs.html

Py:   if not data: return
来源：http://dali.yueranfly.top/Article/details/gtpkdgecbm.html

PHP:  if (!$data) { return; }
来源：http://dali.jyoumei.cn/Article/details/gtwjovfetw.html

JS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtwxdbbgzc.html

TS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtqedasesi.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtzmydnvkg.html

Go:   if data == nil { return }
来源：http://dali.hywenlv.cn/Article/details/gtotxskcfb.html

Ruby: return if data.nil?
来源：http://dali.zhongyouzk.top/Article/details/gthgccdzyk.html

C#:   if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtddyojaap.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtwontpkxr.html

C. 函数与作用域
来源：http://dali.cqqwz.cn/Article/details/gtkogrccmt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtknmurikb.html

[C01] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpvsygby.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gtcktwqito.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtkcyzjnas.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtdpjzhpzo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtirrvyljz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtcmvwhsbc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gtzzlertro.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shangyingyoupin.top/Article/details/gttgdakhfg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfhariqt.html

[C02] 默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtmcxebyev.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gtvpivsmvv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehgrxywx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gttmtthwsv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtienqfbhd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gtklxxmvpi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.bjfxy.top/Article/details/gtapamdzro.html

Ruby: def greet(name = "World") = name
来源：http://dali.havefunace.top/Article/details/gtrihyktss.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gtgnagxrcu.html

[C03] 可变参数
来源：http://dali.dianchejie.cn/Article/details/gtxdxxyuhk.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenlongwang.top/Article/details/gtinuyxlzi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gtsqhlxtma.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtfivfcgov.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtnqoecezc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgufenzy.top/Article/details/gtgciqhsuf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gtcromwpqp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gtegwhxett.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklgwpiwv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gtxcdhqlyr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gtmvddgura.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sweek.top/Article/details/gtmywakwvk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtspsrjnrg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtrgndzvyv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gtfbapient.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gtbhiizxwr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtgngrxrnb.html

C#:   f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtmmsjbzhy.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gtfoovoqbu.html

Py:   return a, b
来源：http://dali.hammf.cn/Article/details/gtvopicwzb.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gtvrkvvwze.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtwhtjneqm.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gtoomieuoe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj202588.top/Article/details/gtvqmdsqqr.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gtjwdmxsev.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gtqmpinydl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gtnoxikseq.html

[C06] 匿名函数 / lambda
来源：http://dali.daria6918.cn/Article/details/gtmoxfdtwe.html

Py:   square = lambda x: x * x
来源：http://dali.cdnleiting.top/Article/details/gtcbvvzcqk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gtsvnxaapv.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtzuxbqaai.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtmqcergxd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhengqikj.top/Article/details/gtowciispj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gtmuvdeeli.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gtdqtuiuha.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtbndqucnw.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gtdpnlivdd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gtoobahbbf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtowkjhngo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gtlopkuhdi.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gtmwugatbr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtypdwjgha.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gtddlypwfh.html

Ruby: arr.map(&:upcase)
来源：http://dali.birdmap.top/Article/details/gtkpbprzmh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gtigaczndf.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gtksrxahyx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhoulong.xyz/Article/details/gtpsniagtj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gtropnzkww.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtnzsdspzw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtpbgencvx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gotoacloud.top/Article/details/gtpehxwlgu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nwbrower.top/Article/details/gteexpdwka.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnqzz.top/Article/details/gtjnkysgjj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtdlnambqo.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gtovatjrki.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gtfxxdjinx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtoqdbyxzg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gtditbeozq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtcetaquvs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxexrjhkh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gtzgmpeooh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gtkkwvqdps.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tanke756.top/Article/details/gtbmqtzwai.html

[C10] 变量作用域
来源：http://dali.jqgufenzy.top/Article/details/gtxrlblrva.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gtltkyuwwj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gtifkuuszn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.0kj1m.cn/Article/details/gtwvdnxwrj.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gtnzwcfjgo.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtghhmvqsl.html

Go:   花括号块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtlpnhtoqy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daxiang520.top/Article/details/gttvkdqmmu.html

C#:   块级作用域
来源：http://dali.xuanzx.com/Article/details/gteukfjtgd.html

[C11] 模块导入与导出
来源：http://dali.jiagoushi.top/Article/details/gtfsatssmb.html

Py:   from module import func
来源：http://dali.aizwys.cn/Article/details/gtwpuckjqq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hongshengwenyu.top/Article/details/gtrsiuetbq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gtyjkbwoss.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhixingplan.top/Article/details/gtacoesmkm.html

Java: import java.util.List;
来源：http://dali.tianlin.xyz/Article/details/gtesfqrncr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yanxiufei.cn/Article/details/gtjuusqtgp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gthxvmbaww.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtnrcuhbcg.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258888.top/Article/details/gtvrdsvsvn.html

Py:   (lambda: print("run"))()
来源：http://dali.yonumen.top/Article/details/gtsjedugtz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtcewzimfw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtygxbrdok.html

TS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtgcaytbnp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gtcnpvonpm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasdxxauq.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gtpqjhhebs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gtylnvujkw.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gtdmqmdmtu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gtaittlfvp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gthpmbjjad.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guannengcc.top/Article/details/gtjfhnedsd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtpjvqraxe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgtqdmwo.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gtmltnbfey.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gzhubu.top/Article/details/gtxextanod.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtqzuveadk.html

[C14] 泛型函数
来源：http://dali.wangdashe.top/Article/details/gtytxeyvdc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.andypj.xyz/Article/details/gtbxeiqcew.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtlekoygly.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtmordlwda.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cqqwz.cn/Article/details/gtrggafpsv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gtsaxdzbhh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtcptojvsv.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtrtilmdru.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcafzaggs.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gtvikjbsdo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvdmlsub.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczhlxwhe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gtgfdrgwzh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtwqokscca.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gtotjyfcgn.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtbfzwjfdp.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtmxnafwar.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gthfsqdafp.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gtpfnmiqxj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xylfe.cn/Article/details/gtowplqedq.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gtgtzprlwq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gtfnqbzyjc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hysaishi.cn/Article/details/gtuqyzyzbk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcuukyiik.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmquvbma.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gtphyrldnp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gtdaarlxnr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtokmolbrf.html

D. 数组 / 列表 / 集合
来源：http://dali.redwolf501.top/Article/details/gtlhvybocw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtycsoqzjr.html

[D01] 创建数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gtvctiidaa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gtgvmkcgoe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtjivquqbl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gtrdlmbhfj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdtfausa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zdqjudy.top/Article/details/gtynludjcf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.316326.xyz/Article/details/gtmveundzb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtcacycqii.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gtyfqfypnp.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gticllvcnw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guannengcc.top/Article/details/gtxkqnehyn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.birdmap.top/Article/details/gtneucktyl.html

JS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtweykbuqz.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtowqtsnik.html

Java: list.add(4);
来源：http://dali.pycfn.com/Article/details/gtwqijzglb.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gtgakgrnxz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtvyamtzcn.html

C#:   list.Add(4);
来源：http://dali.xinyue.icu/Article/details/gtkxwwmhwq.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gtaprsspfo.html

Py:   arr.insert(0, 0)
来源：http://dali.ydzc1.top/Article/details/gtelzwpikk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gtwiisfnlj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258888.top/Article/details/gtxayjwoyy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtlkuzdfez.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtcbrqzwqz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtfmeqsnwb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gtfqgtiejn.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtlyiqagch.html

[D04] 删除元素
来源：http://dali.ivvv.top/Article/details/gtcymrfcqr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jiagoushi.top/Article/details/gtugfrbwbf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gtpfwutirg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gtfyctvomg.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gtsfkifakf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zycfv.cn/Article/details/gtednfppvp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gtsxgywrkx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gtgdcgpfae.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gtjqbiqgvc.html

[D05] 访问与修改元素
来源：http://dali.yongpay.top/Article/details/gtjgevazro.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gttbpqfrlf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtsubypjbk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtpyvfgzqp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtkpjjbzwa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtiqffrhsk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtzkquhzwc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtvbbhpixs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtdxtlkius.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gttktutgwc.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqswqkuxz.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtnafgrzbo.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtjjhsptsj.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gtsnlluyuc.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gtukmcnjgg.html

Go:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtqjxcdofk.html

Ruby: arr.length; arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gthcryxcuu.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gtfvxvrlpf.html

[D07] 切片 / 取子数组
来源：http://dali.smart0.xyz/Article/details/gtalvdylhy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtxxshrzrn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gtywuvoolx.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gttplogrfv.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrqqwhbz.html

Java: list.subList(1, 4);
来源：http://dali.yongpay.top/Article/details/gtquxmyois.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gtgraukrfq.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gtuasvkegn.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gthhfybsxd.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gthgblafcy.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtiqumdxxj.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtippokzsm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gtzuzspbzk.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gtzxptyath.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtlptaxiwq.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gtjfzjlxnw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtuabvhoxm.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtqlehxfsp.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gtphenvpdp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtvutirwzp.html

PHP:  sort($arr);
来源：http://dali.svipenyu.cn/Article/details/gtpucfmdbt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gtqwuaatrl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtkqltioau.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtlxihauwc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtdbtjcrnc.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtmfgrecru.html

C#:   list.Sort();
来源：http://dali.jyoumei.cn/Article/details/gtoyyiqxuj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hongshengwenyu.top/Article/details/gtgifstwjf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnxiangtu.top/Article/details/gtuuiqjkwp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtsatfogmd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtrmdrtkyw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtyoxhovat.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtjehqtwld.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhixingplan.top/Article/details/gtkjrpeaag.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtjvukkvsp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gtepqvnaqw.html

[D11] 反转数组
来源：http://dali.gzhubu.top/Article/details/gtjhviazsp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gtondgpnrx.html

PHP:  array_reverse($arr);
来源：http://dali.cqqwz.cn/Article/details/gtblkvfozv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtsndiezgr.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtyqsiqpbm.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gtohacuezk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gtyrcnwhdu.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gtnipibaqp.html


<!-- 参考信息 -->