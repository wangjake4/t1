代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gt2qybgwyoz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yvedp.cn/Article/details/gt2nsotrbpe.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gt2dlkhemih.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gt2hzekjstr.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gt2hcmcmykq.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcztbfwj.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gt2kgkvfolb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gt2fteeufib.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gt2qzwwvmva.html

Java: x instanceof Number
来源：http://dali.aizwys.cn/Article/details/gt2vsfmbkkf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxinkj.top/Article/details/gt2zuglqeft.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gt2yupuujze.html

C#:   x is int or double or decimal
来源：http://dali.tanke756.top/Article/details/gt2vragubna.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fixidyvv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yueranfly.top/Article/details/gt2gacjhgui.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jianghu66.top/Article/details/gt2zdpjfkes.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gt2hosnahtw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2wbowling.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2ryedzqqq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daxiang520.top/Article/details/gt2aozkepxu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tian-w.cn/Article/details/gt2rddmkfaq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ivvv.top/Article/details/gt2wmgckruc.html

[B15] 布尔运算与取反
来源：http://dali.sysykeji.top/Article/details/gt2cxpfbisx.html

Py:   a and b or not c
来源：http://dali.zycfv.cn/Article/details/gt2slfdgisv.html

PHP:  $a && $b || !$c
来源：http://dali.yonumen.top/Article/details/gt2fmbvnfvy.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2snighpku.html

TS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2hpryqnkz.html

Java: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2ncjvtsty.html

Go:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gt2wgarjaxc.html

Ruby: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2entkxfwk.html

C#:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2quuvmdjx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.haohaochexian.top/Article/details/gt2mbncphcb.html

Py:   if not data: return
来源：http://dali.xuanzx.com/Article/details/gt2aeyjmgiw.html

PHP:  if (!$data) { return; }
来源：http://dali.dianchejie.cn/Article/details/gt2elqnikcn.html

JS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gt2odthnvph.html

TS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gt2fppwkpti.html

Java: if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gt2chdtdkam.html

Go:   if data == nil { return }
来源：http://dali.yongpay.top/Article/details/gt2wuemkggh.html

Ruby: return if data.nil?
来源：http://dali.jianghu66.top/Article/details/gt2ryyprgua.html

C#:   if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gt2rtsapcxn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ohpcvkbs.html

C. 函数与作用域
来源：http://dali.jyoumei.cn/Article/details/gt2qhbwvanl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2qcokvylm.html

[C01] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gt2ytllcrhf.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gt2wukhmrtn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gt2hkqrrihz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftozuhff.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2tjldaygt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2rhfygtfx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2vphhpqhv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gt2ryzwlvfk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2vodwqiak.html

[C02] 默认参数
来源：http://dali.cqqwz.cn/Article/details/gt2yychcykd.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gt2amdsuyyw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gt2wwcdasau.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2wvconzvn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2jeaglvgx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gzhubu.top/Article/details/gt2qptzpbua.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onkweccb.html

Ruby: def greet(name = "World") = name
来源：http://dali.quarkkingdee.top/Article/details/gt2sbgodjpu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gaohongyu789.top/Article/details/gt2rdtaszcu.html

[C03] 可变参数
来源：http://dali.yj202588.top/Article/details/gt2gbqwrzbu.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gt2giiamcnv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pycfn.com/Article/details/gt2vskuzjht.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gt2imdeaxzg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gt2xkocmbvn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xziqi.cn/Article/details/gt2zpndlrmq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gt2ntdoihwu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxloehce.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gaohongyu789.top/Article/details/gt2iyfuhnzp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gt2xhidpjbp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gt2tyophfen.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnsjvtek.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqssvnpo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gt2qggcijmu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jlsjyb.cn/Article/details/gt2wpacegtr.html

Go:   // 无：用配置结构体参数
来源：http://dali.tian-w.cn/Article/details/gt2qlowgjlo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtowfwbl.html

C#:   f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gt2jalovozw.html

[C05] 返回多个值
来源：http://dali.kuanghao11.cn/Article/details/gt2ejoxthqc.html

Py:   return a, b
来源：http://dali.ivvv.top/Article/details/gt2jwxldkeg.html

PHP:  return [$a, $b];
来源：http://dali.sufxvd.cn/Article/details/gt2hwzijoox.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gt2ofuiketi.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gt2lewllvbn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuanzx.com/Article/details/gt2ejrfmevm.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2bystejam.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gt2cfoyevon.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yanxiufei.cn/Article/details/gt2ezsloeqc.html

[C06] 匿名函数 / lambda
来源：http://dali.dianchejie.cn/Article/details/gt2zhtgtvme.html

Py:   square = lambda x: x * x
来源：http://dali.bjfxy.top/Article/details/gt2nhuqolno.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hammf.cn/Article/details/gt2zjxtnqoj.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gt2zotejuns.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2bjhhgjup.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbbvrjfr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zycfv.cn/Article/details/gt2ysmnmsdd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gt2qekyzbju.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gt2xgsxrgll.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gt2ssjzksra.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.redwolf501.top/Article/details/gt2yycjdbhu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258888.top/Article/details/gt2xgstxlgh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gt2yvsdbkvc.html

TS:   arr.map(String)
来源：http://dali.shzxlz.cn/Article/details/gt2zqhsntyu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gt2ofyqsjad.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gt2osluubwj.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bekrzkvd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gt2xkotjxmw.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gt2pwwrpzlm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hammf.cn/Article/details/gt2tvxzparn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylukteyd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gt2ipifsaib.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2fllingrw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bkrdjquq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elafchku.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.mhx1999.top/Article/details/gt2dcgugpov.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2mcxinbxf.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2blmlbdia.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2egnehtko.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gt2tqjvrmvh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xcdfeyab.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gt2dzgftgqw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gt2jaxdbptc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gt2msmeopoo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2aytdeyeu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gt2pqorczcb.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gt2qfyevjci.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gt2flwvivhe.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gt2jabizrwo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shuidangran.top/Article/details/gt2exalprvj.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gt2zmahggar.html

Java: 方法内为块级作用域
来源：http://dali.xziqi.cn/Article/details/gt2lefenxqr.html

Go:   花括号块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2jfpgtzyn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gt2jaxbtwcv.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2hmnrtcyk.html

[C11] 模块导入与导出
来源：http://dali.chenzaomai.com/Article/details/gt2gbnejeqk.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gt2zfbuzgur.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.kuanghao11.cn/Article/details/gt2hezgytcr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gt2mrptogvt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gt2swdnepgm.html

Java: import java.util.List;
来源：http://dali.shzxlz.cn/Article/details/gt2sitnejwq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gt2aveoeotd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigfzy.top/Article/details/gt2fgneaxrm.html

C#:   using System.Text;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yusqbgdp.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gt2vpgrlfgs.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gt2dsqwaiyi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxuanxn.top/Article/details/gt2wcwunhnt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gt2frwjsvbi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gt2dwibemyb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gt2qxclsktb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cashguo.top/Article/details/gt2ioqmreoh.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gt2wmvpfnnd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntvfzqdz.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2pvxpvaww.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.redwolf501.top/Article/details/gt2ineplhfr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gt2rhxftfth.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gt2yicavtzx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2luteikxf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2yihjknzd.html

Go:   func add(a, b int) int
来源：http://dali.ivvv.top/Article/details/gt2dzjlihkn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gt2sitpnllu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gt2chsmqthu.html

[C14] 泛型函数
来源：http://dali.yj202588.top/Article/details/gt2vjhxlpqg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gt2wiopipdq.html

PHP:  // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2pskmkszg.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2uoolcptg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.mhx1999.top/Article/details/gt2aczwflyk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sufxvd.cn/Article/details/gt2lnuiztbu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gt2vbrslewk.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2mnwplnov.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gt2kzxecmdr.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gt2ykcnlwkb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gt2lwfnwcoj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gt2qivhdrvp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gt2zlkzyngh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yongpay.top/Article/details/gt2mfwlwisy.html

Java: // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gt2hctqlgfk.html

Go:   // 无解构
来源：http://dali.yuanzhike.top/Article/details/gt2vqbyndus.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohduifqh.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkhshwxo.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gt2gaxzdtlb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.c1oappe.top/Article/details/gt2qxymkzgx.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gt2iolyxpvr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gt2ygoclwcu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigufen.top/Article/details/gt2qnjqslmn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2ekwrshpt.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gt2sbciqxnm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gt2rjdwsrvr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gt2ysscczzb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2cgktmyof.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gt2afdakhqa.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2vtidrhty.html

[D01] 创建数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gt2qihuqjtt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gt2vuhjkzyz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmqoyrnb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gt2inofxjxj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gt2xkgvfbem.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuetiantiany.cn/Article/details/gt2mblbacii.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gt2nlwovexi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gt2cqnzirzr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gt2mdniwtwa.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gt2woquwfho.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.iojbl.cn/Article/details/gt2lzvlawkg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2jvnyoicx.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gt2njzpjidu.html

TS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gt2yzelrrez.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2qpgwkoaq.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2dheplsty.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gt2gmfhuzjj.html

C#:   list.Add(4);
来源：http://dali.zhixingplan.top/Article/details/gt2tjhqyycb.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gt2oqbttcfu.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gt2dmbpoeep.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrynkipk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yangfankeji.com/Article/details/gt2jswrdqzh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2mtisqqhc.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmlkbsvz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gt2ndvjrowv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gt2ynhtamdo.html

C#:   list.Insert(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2yinshcsm.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2zivpjude.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hfpthk.cn/Article/details/gt2evolfyya.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2awvhfmdo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gt2skytmisi.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigufen.top/Article/details/gt2qdupnfyg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gt2enissvgp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aykdeppu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gt2wvvonzma.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gt2rzmhtcbq.html

[D05] 访问与修改元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqauaohe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2icpsbuio.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2xbqpfmcq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2ztrbacsu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gt2qklhdszm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.316326.xyz/Article/details/gt2relptbzl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gt2zjbrfmnu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gt2xwismyhg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2hejtthlm.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gt2ctdbhqdg.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2lglybgks.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2xwjwgncm.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gt2efxosbxc.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gt2xnoonlzb.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gt2erewbbst.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2ovuvlpzz.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gt2jfbiaydh.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ormjvnnx.html

[D07] 切片 / 取子数组
来源：http://dali.0kj1m.cn/Article/details/gt2kplyagnt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hywenlv.cn/Article/details/gt2nyfwpvoo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gt2qmryznpw.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2xrjkjvus.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gt2dofxolqa.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yatnwtwl.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gt2phrtbfxh.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvgeycu.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gt2vtgpbull.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gt2qbhskdss.html

Py:   a + b;  a.extend(b)
来源：http://dali.xziqi.cn/Article/details/gt2uvxkjkej.html

PHP:  array_merge($a, $b);
来源：http://dali.havefunace.top/Article/details/gt2gersxmnj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gt2aguhgxfg.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jagmmqco.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lglazfwc.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gt2wckxkijp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gt2pwvyzoza.html

C#:   a.Concat(b).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2yzclxdhm.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gt2ninvnfmj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gt2ebleevox.html

PHP:  sort($arr);
来源：http://dali.andypj.xyz/Article/details/gt2wezentpz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gt2yvbycfzh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jyoumei.cn/Article/details/gt2nrxxginq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gt2gtwnljhw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gt2vzrftirf.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2lzioimuc.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gt2gqmriraz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qqzklekn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yawwmkvi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yonumen.top/Article/details/gt2qvpaqylb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2jtkinwyt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gt2adegjxvt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhongyouzk.top/Article/details/gt2rfnhkstk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gt2fyioeqhk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gt2gruqvyqq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.birdmap.top/Article/details/gt2puwwpgpo.html

[D11] 反转数组
来源：http://dali.zhixingplan.top/Article/details/gt2ezoectyi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gt2yuvikgwj.html

PHP:  array_reverse($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2zwijkgcs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gt2ejlyrlsh.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gt2vcemfmrb.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gt2yunjmwex.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gt2osedjimx.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2zsyzzojy.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gt2alvckjas.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gt2okzfxhww.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gt2qyewqhxd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gt2gviifqyn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hngflttr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gt2gufrquqa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jlsjyb.cn/Article/details/gt2kuqtieeu.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2vnbhqary.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gt2dotiztfj.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gt2lutychme.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gt2iawqhzbs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gt2zvjkxvac.html


<!-- 参考信息 -->