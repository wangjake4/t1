代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtmqsxffcv.html

Java: x instanceof Number
来源：http://dali.shzxlz.cn/Article/details/gtmwcaivsx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhiwuduotai.top/Article/details/gtipreolpw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yvedp.cn/Article/details/gtgvmmcijw.html

C#:   x is int or double or decimal
来源：http://dali.zycfv.cn/Article/details/gtbdrtpycn.html

[B14] 判断值是否在集合内
来源：http://dali.wangdashe.top/Article/details/gtrdtsvsrq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gtrixzyrqa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gtbzbqgcql.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtckwlnvwd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtziclanxp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guannengcc.top/Article/details/gtuqmvzeny.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daxiang520.top/Article/details/gtzigpzzxl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlbilqhf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtsxaulhiv.html

[B15] 布尔运算与取反
来源：http://dali.cheryme.top/Article/details/gtsdvypzeb.html

Py:   a and b or not c
来源：http://dali.zhongyouzk.top/Article/details/gtblehyhfc.html

PHP:  $a && $b || !$c
来源：http://dali.hywenlv.cn/Article/details/gtsuhjxukc.html

JS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtcdifgebq.html

TS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtslitgmlm.html

Java: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtsvqwkosv.html

Go:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtpdlxjilt.html

Ruby: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtsrwwgbgn.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtveyzxlns.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gtvwzobfhn.html

Py:   if not data: return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjckjtpt.html

PHP:  if (!$data) { return; }
来源：http://dali.yanxiufei.cn/Article/details/gtxzqemoyi.html

JS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtnpotvdcm.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtjwtextjy.html

Java: if (data == null) return;
来源：http://dali.xuanzx.com/Article/details/gtvofooocd.html

Go:   if data == nil { return }
来源：http://dali.ydzc1.top/Article/details/gtpwbjbjbg.html

Ruby: return if data.nil?
来源：http://dali.cdnleiting.top/Article/details/gtmpaeysfy.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtgjrtylro.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbkabxauq.html

C. 函数与作用域
来源：http://dali.cqqwz.cn/Article/details/gtinlgeikl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtkprjpiob.html

[C01] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtzpbmvaif.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gtxzeougec.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtwlbeqzbj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtejgboqxi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtfbnbpxns.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtjfxbcorz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cdnleiting.top/Article/details/gtezepqjyt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhiwuduotai.top/Article/details/gtlxborgdu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtudbefhre.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtexhzlckg.html

Py:   def greet(name="World"): return name
来源：http://dali.gzhubu.top/Article/details/gthunqhnfy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtomeotlny.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtmyjbbzrg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtkjjrcrig.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gtisqdukzm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczywelya.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gtxmoshrwg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgufenzy.top/Article/details/gtevcorsmo.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdqxzcad.html

Py:   def total(*args): return sum(args)
来源：http://dali.birdmap.top/Article/details/gtpfgimain.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbiluvele.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtcrieoaje.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtrtdaudbs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangdashe.top/Article/details/gtddfwgrfo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gtvyxnohqt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gthpzwfkhv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinghuilouyu.cn/Article/details/gteufzpkku.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gtlkdtqotn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gtrmdpfvlr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtltesgdgq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtzliudzry.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.andypj.xyz/Article/details/gtbajhgrmh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gtnlskybjx.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gtabedpjqc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtrqvbmdse.html

C#:   f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtemxwxphh.html

[C05] 返回多个值
来源：http://dali.zhixingplan.top/Article/details/gtppizujln.html

Py:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtvawfkygn.html

PHP:  return [$a, $b];
来源：http://dali.kuanghao11.cn/Article/details/gtcuwidcrh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtqarwrlch.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gtgqemocxv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dashuyun.cn/Article/details/gtjdkrzpwn.html

Go:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gteccgpagj.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gtlusbceuv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbsmqapz.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxuanxn.top/Article/details/gtyfurrkzd.html

Py:   square = lambda x: x * x
来源：http://dali.gaohongyu789.top/Article/details/gtomuzjiiy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aibaodan.cn/Article/details/gtvlhmmvfw.html

JS:   const square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtwuuhqwdv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gteswupnxl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtymjqcluc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gogol.net.cn/Article/details/gtdoscctye.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gthknwltsi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtanwnfosz.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gtusoqnjrf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxdvhrrz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtrsxggrjr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cashguo.top/Article/details/gtauulvhzc.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtquaafjku.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yangfankeji.com/Article/details/gttatgffxu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigufen.top/Article/details/gttjsbsiev.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gtyiotvmyq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gtuullnwgs.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gtxsvknkvx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gtukdqxyfa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gtjvixbvtl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtuqkqkber.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtpqdwvnfp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gtvshoomqe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gtlhtmtkne.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.9152youxi.cn/Article/details/gtlplxgjjq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtgbboofjp.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozhtogix.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtiwtfsoey.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtqeyeyojf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtwzwbosbq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtheqrmpja.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtwnnipzth.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shuidangran.top/Article/details/gtukdvyqdp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtszmhfjpt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gtccfioipl.html

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtcemvzkyu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gtrmpmftnr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shzxlz.cn/Article/details/gtzmyomwei.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gtnegzapxm.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpxkcina.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtiabyuimi.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtwearhtrq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gtkdxfhzbo.html

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gtlemouzwn.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gtbbrwvkeo.html

Py:   from module import func
来源：http://dali.mhx1999.top/Article/details/gtqakaxbyh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gtbwrzqmyz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gtkwiwzjca.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgfzy.top/Article/details/gtrtgliifp.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gtfnovxzjk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gtxgxvdlcq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.kuanghao11.cn/Article/details/gtefqbjdcl.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gtrsbdagni.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gtvekzvofr.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gtwacfqkiq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gthleylmhg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtcpfocsuc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtsznrfvjk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sufxvd.cn/Article/details/gtfepzywix.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gtfeucomjn.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gtpfwqyrwg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtrmdlvhwx.html

[C13] 类型声明 / 类型注解
来源：http://dali.sysykeji.top/Article/details/gtodklotkb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gogol.net.cn/Article/details/gttagshyue.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtrkggnxxg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.9152youxi.cn/Article/details/gtrsfibryt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtjbatrrrb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxddnflug.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gtdbrkpiaf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gtekhbrdgw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gtcptmqnjd.html

[C14] 泛型函数
来源：http://dali.sweek.top/Article/details/gtejfugzyw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gtvcniwebc.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtrgyxwaxc.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtxyqkovwp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtthugiyos.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gthegxcheo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jyoumei.cn/Article/details/gtqrjdxfql.html

Ruby: # 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtbapiuane.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gtalhjcxio.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gtwfpdgote.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.9152youxi.cn/Article/details/gtmtfgrhlv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gtaiivvzce.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtprvyuhid.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yongpay.top/Article/details/gtiyhumzbx.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtwncchbkj.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gtlcpqwtza.html

Ruby: a, b = pair
来源：http://dali.dianchejie.cn/Article/details/gtckvbpaar.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gthmmlbnne.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gthfnodiys.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.quarkkingdee.top/Article/details/gtqcvdrche.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gtzfzlkuca.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gtgsvhfbkj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gtkwytoksi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtoorpanuh.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gtxbimbmmg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnqzz.top/Article/details/gtvyfhjvdm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daria6918.cn/Article/details/gtycxogrmk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtetrurktn.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtcrqwwhuw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtknlorehf.html

[D01] 创建数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gtgotflbia.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gtkmofrtcp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtekxqohen.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtugsqhjel.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgufenzy.top/Article/details/gtsgaxedcq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzipcpvqi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gtliudsdpr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gtfbcnbemo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gtgghluyxf.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gttavegmzk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgufenzy.top/Article/details/gtdkofsvxn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sxryk.cn/Article/details/gtgqvodllg.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gthmtdbpta.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtervqfeed.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtylbpohrp.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gtgcaymknj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sufxvd.cn/Article/details/gtminycddh.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gtmqfodbww.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gthvfnnjmr.html

Py:   arr.insert(0, 0)
来源：http://dali.sysykeji.top/Article/details/gtvgdtupgl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zycfv.cn/Article/details/gtulwnlfqt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxuanxn.top/Article/details/gtfrganqlq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jianghu66.top/Article/details/gtlzrqpjjw.html

Java: list.add(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtbzwohyje.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tian-w.cn/Article/details/gtjkaptkmm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gtqusfifoo.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtbwgkwuue.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gtedokqwbw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shuidangran.top/Article/details/gtdodlejyk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtxmcwwkdo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gtmdmfzfna.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gtvxmcjdgf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gtgqyvivzc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhiwuduotai.top/Article/details/gteizcoovk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gtpfnnhwwa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtuzexzzmo.html

[D05] 访问与修改元素
来源：http://dali.xziqi.cn/Article/details/gteriddbcn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtxoiszdzm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtuilqmmkb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtpuhbrbfd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yvedp.cn/Article/details/gtbmhijtup.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gtiuyrzrwo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtjjzwtovd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtvdisleos.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtleprhsrc.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gtlpvumguj.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwiyfswh.html

PHP:  count($arr);
来源：http://dali.daxiang520.top/Article/details/gtkyolymul.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtwhtgqluy.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtafqbbwhd.html

Java: list.size();
来源：http://dali.yvedp.cn/Article/details/gtoebloxjj.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gttvayxwkk.html

Ruby: arr.length; arr.size
来源：http://dali.ybcxt.top/Article/details/gtiqfwlktn.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gtlysmdylx.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gtlbzjmumw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ppjwa.cn/Article/details/gtmkkhsrfv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtsfgypqpp.html

JS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtijblaoks.html

TS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtvwonvxma.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gtvnewtroy.html

Go:   arr[1:4]
来源：http://dali.daxiang520.top/Article/details/gtgkixurxs.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gthbhaywes.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gtsjqtjlqe.html

[D08] 合并两个数组
来源：http://dali.daria6918.cn/Article/details/gtikrxpinu.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuatqnhqn.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gtsgdlyicr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtcioimcmp.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gtujvpqnem.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgufenzy.top/Article/details/gteaoglzhb.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gtzlymolxn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gtbfbobiqs.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtitizgkyr.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gtlyvnilsg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtqyocexgq.html

PHP:  sort($arr);
来源：http://dali.dashuyun.cn/Article/details/gtblatjcor.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtaratqykd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.iojbl.cn/Article/details/gtfbyukulp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gtldkoptpt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtvcjetgka.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtiyjifyjg.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtmmjjjhwx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gaohongyu789.top/Article/details/gtokykcibk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gtxbczzlby.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gtrezxmuec.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtdrlgvnoa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtbuitsuvn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gthmznhdcb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gtabpsrrqd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.mhx1999.top/Article/details/gtwtpuleuk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gthuhjapcn.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gtaecczbse.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpndlqxf.html

PHP:  array_reverse($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtczhvdzoj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkptylfg.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtaeejxgrs.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxmykbwr.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gthwpsbgnv.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gtjndkugjk.html

C#:   list.Reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtufsaioaw.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gtmwpkdmua.html

Py:   arr.index(x);  x in arr
来源：http://dali.tanke756.top/Article/details/gtilrottzm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guannengcc.top/Article/details/gtysgiorrg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtfopzgtzf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtwsvpceaq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hysaishi.cn/Article/details/gtmewtvysr.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtozhsoofw.html

Ruby: arr.index(x)
来源：http://dali.meibo888.top/Article/details/gtgxqlijks.html

C#:   list.IndexOf(x);
来源：http://dali.jqgufenzy.top/Article/details/gtgilyxjik.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenzaomai.com/Article/details/gtkrrvbirl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shuidangran.top/Article/details/gtrrwzlwof.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gtvfizjumd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtcnibycri.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtppvhbqik.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gtnpgeszgr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gtllagrohk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gtyjenmunp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtqubptycl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shangyingyoupin.top/Article/details/gtmaoesasf.html


<!-- 参考信息 -->