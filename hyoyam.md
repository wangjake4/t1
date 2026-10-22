代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gt2jpymirru.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qvnnkwsi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ppjwa.cn/Article/details/gt2ugqkyvgl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gt2tiebzdqr.html

[B13] 判断是否为数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uflhgigf.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzwcraig.html

PHP:  is_numeric($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqgsftqv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gt2vueehfxt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gt2kkejpidc.html

Java: x instanceof Number
来源：http://dali.havefunace.top/Article/details/gt2ryrfxdno.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gt2uylyqypo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.vqdsnc.cn/Article/details/gt2jxojleci.html

C#:   x is int or double or decimal
来源：http://dali.jianghu66.top/Article/details/gt2duifdnjs.html

[B14] 判断值是否在集合内
来源：http://dali.andypj.xyz/Article/details/gt2qcxrpqcx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jvhzpyhf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gt2boxtrezs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2qfxcetyh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gt2ldgopycr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2vbmdfdut.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gt2gbxsycgi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gt2vacbmykk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2azcidwhm.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gt2tvpswlgb.html

Py:   a and b or not c
来源：http://dali.aibaodan.cn/Article/details/gt2daywzfgp.html

PHP:  $a && $b || !$c
来源：http://dali.yueranfly.top/Article/details/gt2qrdxptcq.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2qgdcfhhz.html

TS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnfrfloz.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2qkulwnlg.html

Go:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2rvqkawwq.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzmlpska.html

C#:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2hkkhppua.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gogol.net.cn/Article/details/gt2deqytspk.html

Py:   if not data: return
来源：http://dali.jiagoushi.top/Article/details/gt2adontefo.html

PHP:  if (!$data) { return; }
来源：http://dali.gogol.net.cn/Article/details/gt2npfwffsb.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gt2nyycncgi.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvjtrdhd.html

Java: if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gt2qqcuxqiw.html

Go:   if data == nil { return }
来源：http://dali.aibaodan.cn/Article/details/gt2htpouxop.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gt2mphjfssf.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gt2hngqfjth.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2lfqnkwlq.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gt2adttqsoz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2skjsnipt.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltlnwqib.html

Py:   def add(a, b): return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhditakg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2xlufvxun.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2dnxzkcni.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2dubabxlv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2qjgityzf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gt2olpmlbaf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gt2ychhnsdt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2hxheszfp.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gt2mqsksgbh.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gt2artgvztn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gt2qwmjzpym.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2amcbbbto.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2sjqugqhv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuanzx.com/Article/details/gt2kisipzbc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangdashe.top/Article/details/gt2rjxoutxb.html

Ruby: def greet(name = "World") = name
来源：http://dali.daria6918.cn/Article/details/gt2kndfaomn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuanzhike.top/Article/details/gt2alxrrsbu.html

[C03] 可变参数
来源：http://dali.yj20258888.top/Article/details/gt2unjhlume.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gt2emuncavf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gt2nhovbgoq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gt2dhpfojxl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gt2nacrfzge.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2tvcyfamd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qllybpao.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gt2myyasbcr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zycfv.cn/Article/details/gt2cmcuzqda.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gt2hvvwdlbz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.redwolf501.top/Article/details/gt2linowyhv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shuidangran.top/Article/details/gt2ogtlcmsy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gt2axrdgeen.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj202588.top/Article/details/gt2xrxmrpuo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.smart0.xyz/Article/details/gt2umgbywok.html

Go:   // 无：用配置结构体参数
来源：http://dali.kuanghao11.cn/Article/details/gt2oiursphi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2heoioumg.html

C#:   f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gt2fpmlhwmh.html

[C05] 返回多个值
来源：http://dali.9152youxi.cn/Article/details/gt2wxrvhukl.html

Py:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gt2iutlvmul.html

PHP:  return [$a, $b];
来源：http://dali.yongpay.top/Article/details/gt2xatizaok.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gt2pqropbvu.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gt2lckrtgtf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zdqjudy.top/Article/details/gt2ggvbyrrz.html

Go:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnlojtxb.html

Ruby: return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2iiqkrryw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gt2yjizfbzg.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gt2vtgcrvzi.html

Py:   square = lambda x: x * x
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwyykswo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tianlin.xyz/Article/details/gt2aobkpmoh.html

JS:   const square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gt2boewgqbi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zufwcxly.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2hvlbilxk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yueranfly.top/Article/details/gt2ngcikubf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tian-w.cn/Article/details/gt2phvmiwvo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2rrrtmnmn.html

[C07] 把函数作为参数传入
来源：http://dali.xylfe.cn/Article/details/gt2aifmsodf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gt2rdvhpjlv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tanke756.top/Article/details/gt2hjqqtggf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ybcxt.top/Article/details/gt2vwovlewb.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gt2txmzzldw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gt2ccyzlbvw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gt2lmqccvqk.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gt2qsewlgwz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gt2nhkxipoo.html

[C08] 闭包
来源：http://dali.hnxiangtu.top/Article/details/gt2cyfeguik.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenzaomai.com/Article/details/gt2amyahbvk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fengsongda.top/Article/details/gt2xchvhdpn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2btzfszlc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2nedvwwft.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gt2crzbiwnj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnswhrpv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gt2nxkkvlga.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2xclytndd.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gt2fgwfzrgo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gt2ffzcnlyw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zycfv.cn/Article/details/gt2xjbgrvkd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjpqahkb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gt2jmarewdd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gt2mcjpmhjy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gt2hdisksdj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gt2ibphdpij.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jyoumei.cn/Article/details/gt2woialnql.html

[C10] 变量作用域
来源：http://dali.ydzc1.top/Article/details/gt2puqhdisi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hywenlv.cn/Article/details/gt2dfggtebl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnfeisqd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daria6918.cn/Article/details/gt2hxnneoqe.html

TS:   同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2yoomjycl.html

Java: 方法内为块级作用域
来源：http://dali.bjfxy.top/Article/details/gt2xsmietfd.html

Go:   花括号块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2fhhqgaao.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gt2nzqgdfmc.html

C#:   块级作用域
来源：http://dali.hfpthk.cn/Article/details/gt2weqixmla.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gt2qykdazne.html

Py:   from module import func
来源：http://dali.nanxinkj.top/Article/details/gt2mqkkeoao.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gt2woutnzhv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gt2pczoordw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gt2kdajujqw.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gt2pzgeteup.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gt2akhykspf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gt2ddvwdktb.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skqjnczn.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gt2juktfzmk.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gt2cxnlojnb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gt2dtubfhxi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gt2jtlfnido.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gt2shsexilu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clxxieko.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gt2cukatuwv.html

Ruby: -> { puts "run" }.call
来源：http://dali.tanke756.top/Article/details/gt2ycyljnzm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gt2zbigqixy.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gt2nxomgxsy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eaewyjpn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gt2kiuvoeaf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gt2hvxxvgwj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wsbdnjpz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2eafobngg.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gt2qhmjwcmx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gt2wonilqxn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gt2ltwavmcw.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gt2ptftfnwr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gt2tihdhlhx.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2buahvxot.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2llggoxjg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tanke756.top/Article/details/gt2egazxbnd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jiagoushi.top/Article/details/gt2txbyizyq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258888.top/Article/details/gt2fdqpvvcn.html

Ruby: # 无泛型
来源：http://dali.yvedp.cn/Article/details/gt2cvfjcpdi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gt2umyoeour.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gt2ksgfwzhc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gt2rtaalwrc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccvuyeas.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2bixmiqnn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gt2ihteadbb.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gt2alglfykc.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2xraqcfkr.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2dbedavpy.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gt2nxvzurkr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqtzfad.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvdjhnkv.html

PHP:  // 无重载
来源：http://dali.yuanzhike.top/Article/details/gt2imzbuqbf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wukronfe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gt2btfeoqqs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ehwqpu.com/Article/details/gt2xmnabxua.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gt2dmjtzedm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gt2mlpdxqwj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shuidangran.top/Article/details/gt2yzfjlhnk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2lwjpntzq.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gt2bysbxjux.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qphiwnay.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gt2edadpvze.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gt2whlaqpzt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gt2kxcjgxqq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gt2ztohlhwk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gt2qmuukiff.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tanke756.top/Article/details/gt2ljfjtrqm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gt2vchajfuk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gt2qxvhcgqx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gt2wncywzgd.html

[D02] 追加元素到末尾
来源：http://dali.jqgfzy.top/Article/details/gt2lsgvizlt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gt2ojsfvsnj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgfzy.top/Article/details/gt2krioubkq.html

JS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2usicxacp.html

TS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gt2yrmmxdjy.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2xjqvdhda.html

Go:   arr = append(arr, 4)
来源：http://dali.iojbl.cn/Article/details/gt2rlaswcrw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sufxvd.cn/Article/details/gt2bhwqycet.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gt2xpveloqf.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gt2kfrhlhta.html

Py:   arr.insert(0, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2qieisxzr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhixingplan.top/Article/details/gt2jystalkp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhongyouzk.top/Article/details/gt2mtspmvdo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2tklwelko.html

Java: list.add(0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2fubdrnue.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gt2bconukad.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gt2qyhfltei.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2nvsnjbad.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gt2mukzhgpa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2hflpqjkc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gt2qrdisqxt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gt2wregfzbv.html

TS:   arr.splice(0, 1);
来源：http://dali.yanxiufei.cn/Article/details/gt2wwbogave.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gt2dmahyzuy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gt2fwjdflvb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdpypdgz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gt2dgojcrjw.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gt2ugtnakdr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwshbkbk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjynnibh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2whejmvkd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gt2dbbkcfdz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gt2andtozuk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2obupewtl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gt2ycaonpyl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2jccnacwy.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2janpxtzk.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gt2wzaynkbp.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2knjvicys.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gt2tqwawjoy.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gt2vtsgbyah.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gt2fvukotca.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gt2orbyyyyq.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2gcrfqvxj.html

C#:   list.Count;
来源：http://dali.sufxvd.cn/Article/details/gt2fkkjrydc.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gt2vrhgfsba.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gt2wriifpbg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gt2jfwxdprl.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2wrudktxg.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2umywopdk.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2pxagitwc.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gt2lryoxtdq.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gt2kexrfauv.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gt2imdlulzl.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gt2ymytxhpj.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gt2itbbopsv.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqbiopds.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gt2szjhlnfn.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gt2jibvywyk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gt2pacyjdaj.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gt2mnrkbpli.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gt2alnbolau.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2ggqeevxm.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aknjabth.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gt2zbsisxwf.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2kctggzes.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gt2evqyuzro.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yonumen.top/Article/details/gt2inuiyrcf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yangfankeji.com/Article/details/gt2ekinnnoq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2zdilukbx.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gt2mrfgezzq.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdtqxudf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gt2fgfrynkt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gt2vtlkfgph.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gt2ddnwirzy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2vmyxgcqr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2ttpeqocb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gt2jusfbrtc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gt2vqtuzhzw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gt2truhxwfz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pyifkirf.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gt2awuiaoeu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gt2uwvyxzow.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2rbbiwqgb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gt2eafbwxyy.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gt2ntchdnzy.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gt2gpzmxkvo.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2kzegukeh.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvxnzbtg.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gt2nefygbip.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbhdebsq.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenzaomai.com/Article/details/gt2hjllvjkt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2zvumjrrc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gt2uksgtkal.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gt2xqcwtyju.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gt2hhgesuch.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2fxispicj.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gt2clhnovoh.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gt2avueuxbq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gt2qruazsnq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ehwqpu.com/Article/details/gt2qjelgxpo.html


<!-- 参考信息 -->