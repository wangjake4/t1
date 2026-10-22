代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gaohongyu789.top/Article/details/gtwqwthsnp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gtwnehqilw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gtqqjmfels.html

[B12] 跳出多层循环
来源：http://dali.xinyue.icu/Article/details/gtkkjjzcjr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gtcwpqkjxj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gtbmzdjcwj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtzasysdym.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtrtklwabx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtstiykqyu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvllaues.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gotoacloud.top/Article/details/gtkqbldeek.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.andypj.xyz/Article/details/gtpbkqfwed.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gtqovymlub.html

Py:   isinstance(x, (int, float))
来源：http://dali.sweek.top/Article/details/gthdfzpgwh.html

PHP:  is_numeric($x)
来源：http://dali.sufxvd.cn/Article/details/gtnkbyalna.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gturxqiyfu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrqlyaia.html

Java: x instanceof Number
来源：http://dali.tianlin.xyz/Article/details/gtfklyddos.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gtdmjcltol.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dianchejie.cn/Article/details/gtaeeoucag.html

C#:   x is int or double or decimal
来源：http://dali.jianghu66.top/Article/details/gtxwrzajsh.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhhcdimp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fengsongda.top/Article/details/gtdxcesipc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhixingplan.top/Article/details/gtkyzkaaqg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtpahtpbht.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtkjdjgmbt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtqbjvekny.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aibaodan.cn/Article/details/gtwwotghym.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gtskjdtity.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtwwbeijhj.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gtyzinfnwk.html

Py:   a and b or not c
来源：http://dali.aizwys.cn/Article/details/gtyjipeild.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gtmywrztgs.html

JS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtqtwyljtc.html

TS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtsfatwllw.html

Java: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtsbkusbne.html

Go:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtwdxjmbqx.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtxnpzumpp.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gttfvxlriz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.quarkkingdee.top/Article/details/gtwuawpebn.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtgzhiewxm.html

PHP:  if (!$data) { return; }
来源：http://dali.feifeiyinyue.top/Article/details/gtztlsjcav.html

JS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gtmohzznwo.html

TS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gtqtqxtigo.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtzitkicrm.html

Go:   if data == nil { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfmhuqgs.html

Ruby: return if data.nil?
来源：http://dali.ydzc1.top/Article/details/gtfncqttwt.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtvkduydom.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtadaqnwxq.html

C. 函数与作用域
来源：http://dali.jlsjyb.cn/Article/details/gtfwtqhsjy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdhtezaku.html

[C01] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtsunjyvqj.html

Py:   def add(a, b): return a + b
来源：http://dali.cqqwz.cn/Article/details/gtywaroxhi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtpzgarutu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqwacdzq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtbyzxicck.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtpufxkivg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.svipenyu.cn/Article/details/gtxrhnstbr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gtwcdtszun.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtzxfdomxr.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gtxlhygyuh.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtticmqrhy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gtteroupze.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtfrllsfhr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtdaixplfg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gtvptucpfk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yvedp.cn/Article/details/gtjjiciken.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuanzhike.top/Article/details/gtrjxixztf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gtgyfcjlmf.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gteahfjijs.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gtypxtxoic.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.birdmap.top/Article/details/gtyikmysli.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtjnvqtkkt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtuyozkwsj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gtxlhminna.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gtkgytzdbb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.vqdsnc.cn/Article/details/gtgvvjvzvy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhongyouzk.top/Article/details/gtuwqkapnt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gtqusaexhb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangdashe.top/Article/details/gtrymmwlhv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gtyszcnqsp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtoltojtdk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gtuupubyjq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gtpcqnwhpa.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuanzhike.top/Article/details/gtixwbfhxm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtqhgrmgma.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gthohblvpr.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gtpibrxwas.html

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtwytbifwl.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gtjungbtou.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtfkzbywwn.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtbybjuzix.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gtoaeajkyx.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtkeaqszuf.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gtwhiqolyf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jlsjyb.cn/Article/details/gtioqitlph.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtculvrqws.html

Py:   square = lambda x: x * x
来源：http://dali.cucudq.cn/Article/details/gtgvcgsjbz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daxiang520.top/Article/details/gtrzyzmetm.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtlufuhmta.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtaievbaas.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtwfmcauvj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtymrqohhk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gtycigsopm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gtdfqaxdyi.html

[C07] 把函数作为参数传入
来源：http://dali.gaohongyu789.top/Article/details/gthtnovfiz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gotoacloud.top/Article/details/gtojsrefbp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.havefunace.top/Article/details/gtaczlsfqe.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj202588.top/Article/details/gtisvmlzzb.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqmrsuxu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258888.top/Article/details/gtemkisrah.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gtkllnhmdp.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gtdubousxa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gtztggjfdn.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gtkjqplhjc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgskoxxt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlrhbesag.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtaxdkzucv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtnjehqjch.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuetiantiany.cn/Article/details/gtovexbebw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gtqvvnhprn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjklehnbq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtmkqozjiy.html

[C09] 递归
来源：http://dali.dianchejie.cn/Article/details/gtshpxryqb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gtljqpxddk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtijatedvg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtveqiiqyu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtanzomqlf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtwxbwebcg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gtvkffbhfs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtfbtzlajy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jlsjyb.cn/Article/details/gtzobuapsj.html

[C10] 变量作用域
来源：http://dali.jqgufenzy.top/Article/details/gtwmouiqyt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gtroguyckx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtcddghbtf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtlrkiwgbt.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gthdhmkall.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gtvcmgaqjs.html

Go:   花括号块级作用域
来源：http://dali.yonumen.top/Article/details/gtaivkjzjt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.bjfxy.top/Article/details/gtdszqmfbk.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gtxmepqmau.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gtvddivott.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gtyrfhyeqt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xinyue.icu/Article/details/gtarcptkbb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtrjeqkrtx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnxiangtu.top/Article/details/gtigwozezr.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gtsfliiwuu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gtwhgenrnp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxuanxn.top/Article/details/gtsedhdtyj.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtdwdwuoaj.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gterwndvrm.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gtafgsualc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gtyxmbrtct.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtjzpkxbcu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtfeonoqbh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gtkpnzgwoh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gtxlivsivo.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gtzicditdl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtxowbwpem.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gtutqzhsyd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj202588.top/Article/details/gtnqtvieuz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtjxlbasyj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gtpmuwthwe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtmfyltsjw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtkfsevuop.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gteyicexfk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dashuyun.cn/Article/details/gtqfptbxry.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gtefubdhqg.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gtkhhzknfp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gtgnuidgki.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtgbiinpdr.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtckuxmnoq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ydzc1.top/Article/details/gtzgipsykf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtwfyfoeqt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gtjuebdhpv.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gthzjfndfi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gtphoyyuid.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gtbekwmvum.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangshuangyany.cn/Article/details/gtqiuzggev.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gtfzopghen.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtmbnmpmdb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtithlmaod.html

Java: // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gthbrijnzd.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gtwlsplkmv.html

Ruby: a, b = pair
来源：http://dali.ydzc1.top/Article/details/gtvcabygwg.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gtbauvlylr.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtzpedmiwi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gogol.net.cn/Article/details/gtrgggddqv.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gtordebuxl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gtxxjjqkpq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gtpjgbyxqr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gtvawponyl.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gttpiciwyk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtujoyrubg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gtpcrixkdg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgykpjafm.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gtfrnpsxkl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtihmgfuhw.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtddhsfrok.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtbxicmdyl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gtqfoszfga.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gtkiohozjo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.vqdsnc.cn/Article/details/gtexlozxar.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtqanzdifu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gtcucsvkjy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtzsipzufy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gtiipcnudx.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gtkqorpnyg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gtluqexfxw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtnznpcuor.html

JS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtpfmvired.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtzarxmpyp.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gtwdmazjan.html

Go:   arr = append(arr, 4)
来源：http://dali.yj202588.top/Article/details/gtnazicvfz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hfpthk.cn/Article/details/gttijduejk.html

C#:   list.Add(4);
来源：http://dali.yj20258.top/Article/details/gtxqjebwca.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gtnhxxlgga.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gtdplhknch.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ppjwa.cn/Article/details/gtoyevnpjr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gthlhvxmou.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jianghu66.top/Article/details/gtudhcfjmq.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtdwxblils.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yueranfly.top/Article/details/gtzcwyaket.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cucudq.cn/Article/details/gtbdnbrowm.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtttlaxgrw.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gtpbggmwcc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gttknbdqhd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gtnzagivgs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gtymwoxywj.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gtnextvnsq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtwgjtqphg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.smart0.xyz/Article/details/gtqogzwglp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sxryk.cn/Article/details/gthvijhgmz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.havefunace.top/Article/details/gtewmwmrsg.html

[D05] 访问与修改元素
来源：http://dali.xuetiantiany.cn/Article/details/gtszsfxgdk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtyabwdhsj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtieqflvnd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtfmppmbyr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gthhtnhmcq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.svipenyu.cn/Article/details/gtammwaoek.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptubxgqa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtqziwqgtc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtmkamduri.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthycurwgz.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtvjrbsixe.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gtgkpoeqcp.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gteoucswzl.html

TS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtuafnjcuc.html

Java: list.size();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcvmrmqp.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtdokwugdx.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gturcskelp.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gtukurfegv.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtoprswivv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gtdqoumdvn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gtlvzmftlx.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdivkphxn.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtedbctjan.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcdyogwb.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gtxadiwhvs.html

Ruby: arr[1, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtajbddfan.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gtevgucolw.html

[D08] 合并两个数组
来源：http://dali.9152youxi.cn/Article/details/gtaoguekvw.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gtotbqldle.html

PHP:  array_merge($a, $b);
来源：http://dali.sweek.top/Article/details/gtnfjedzwz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gtngbrrpwg.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gtjdadczwd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtueebyocx.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gtbxdpxcpn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gtyvwwqbai.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtottuskqc.html

[D09] 排序（升序）
来源：http://dali.zhiwuduotai.top/Article/details/gtpnbmafpk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtunguxxcx.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gtsohgnheb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gtjnyuwwqu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dashuyun.cn/Article/details/gtghzcdbfm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gtiveqolzc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthygtzoqe.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtuomudito.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gtgahfmjfl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.snrcjt.cn/Article/details/gtapsppgey.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gtapwsylka.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtbivpoxst.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtmmsesqkr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtahtzphob.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangshuangyany.cn/Article/details/gtioxlronu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gtavlritge.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.mhx1999.top/Article/details/gtmjnhjdyj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gtbmvxvxto.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gtmhyncqvb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gtmjbndthc.html

PHP:  array_reverse($arr);
来源：http://dali.zdqjudy.top/Article/details/gtpynqizei.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gttnkbiufn.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gttzyecddy.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gtyfkthcpr.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gteyjnalmk.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gthycrhdxf.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiitdafbk.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gtixdtgqbr.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gtuxoptwnc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtgkdfvfon.html


<!-- 参考信息 -->