代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.svipenyu.cn/Article/details/gt2xnpypavs.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2rjlerskq.html

TS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2nuuzwkcx.html

Java: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2odrigczc.html

Go:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2xqushber.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2ikvijkas.html

C#:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2bzvpksig.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2zczixscj.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gt2caaamdyj.html

PHP:  if (!$data) { return; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytbvbddd.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gt2rfjhsuhn.html

TS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2hcsbbrzm.html

Java: if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gt2jikjilyf.html

Go:   if data == nil { return }
来源：http://dali.jiagoushi.top/Article/details/gt2ustetlly.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gt2kznhdpwe.html

C#:   if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gt2uxiztrzv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2qmevfabq.html

C. 函数与作用域
来源：http://dali.shzxlz.cn/Article/details/gt2nrjbqjgg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2fkthmjhg.html

[C01] 定义函数
来源：http://dali.cucudq.cn/Article/details/gt2eaevmnlz.html

Py:   def add(a, b): return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlomolok.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2lkcpjwai.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jmfimmnd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2eeyogblf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dqmibmew.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xziqi.cn/Article/details/gt2tvwjfnms.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gt2xvjfhwbg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2vfxbepwd.html

[C02] 默认参数
来源：http://dali.yj20258.top/Article/details/gt2xptaobjh.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigfzy.top/Article/details/gt2niuhjrnr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gt2cwfupods.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rexwehwk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2qthadwnu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.mhx1999.top/Article/details/gt2zqosfujg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cashguo.top/Article/details/gt2izroqaqv.html

Ruby: def greet(name = "World") = name
来源：http://dali.havefunace.top/Article/details/gt2buwuxbft.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gt2peynibmm.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gt2hsakbvyw.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gt2lbqnsiqt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqaoulrd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2qqapincz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gt2gjsshfaf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gt2ujpkbytn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hywenlv.cn/Article/details/gt2vccyhcpt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gt2gismtion.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuanzhike.top/Article/details/gt2dubvmwro.html

[C04] 命名参数 / 关键字参数
来源：http://dali.mhx1999.top/Article/details/gt2utbbgqsw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gt2fufdedow.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gt2vcqakkst.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2owlishjx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bohxuuak.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gt2regsyqys.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenlongwang.top/Article/details/gt2dpxhysve.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2wmyulsub.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gt2dbavrjkq.html

[C05] 返回多个值
来源：http://dali.kuanghao11.cn/Article/details/gt2hnntqwtx.html

Py:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gt2mxyxqbls.html

PHP:  return [$a, $b];
来源：http://dali.hammf.cn/Article/details/gt2fsubqoxr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnqzz.top/Article/details/gt2haepsvkw.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udgpvvjk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xziqi.cn/Article/details/gt2ncmorany.html

Go:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gt2njddoknb.html

Ruby: return a, b
来源：http://dali.wangdashe.top/Article/details/gt2ezjkxoyv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cucudq.cn/Article/details/gt2fthfpzac.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gt2vykqeiaw.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gt2osdulczc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hammf.cn/Article/details/gt2ggibbich.html

JS:   const square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gt2coivqmjh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2jehisguf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gt2ogtfhxkp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yonumen.top/Article/details/gt2xbyumbkz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gt2ezxdasev.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gt2vizisigi.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gt2slxdbhvl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gt2qticjwkv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2eptfvbqk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gt2oduvtede.html

TS:   arr.map(String)
来源：http://dali.jlsjyb.cn/Article/details/gt2vwbwckgt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2nggtpuil.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jyoumei.cn/Article/details/gt2pexrtrwx.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnzocbar.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ybcxt.top/Article/details/gt2viyqfisu.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gt2xvlxkydh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gt2fmskabgq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fengsongda.top/Article/details/gt2cqfkpyfh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gt2cqlwfhle.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gt2jgbhiszv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gt2apwoedha.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gt2mkkujrqr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tanke756.top/Article/details/gt2ufsstfdu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gt2uyxnmnuf.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gt2bnycviop.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gt2brpeqycp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ivvv.top/Article/details/gt2otrgyuoy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gt2ccxatpzd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gt2tmonrrkf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gt2ddbestls.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gt2scathokl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gt2brgjgqof.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycfusfvh.html

[C10] 变量作用域
来源：http://dali.jianghu66.top/Article/details/gt2ybiinuxp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gt2fkcoagnt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gt2ihgnbhpg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2oxyhkpkl.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gt2xozermpi.html

Java: 方法内为块级作用域
来源：http://dali.tanke756.top/Article/details/gt2jptzdaco.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gt2zomeckta.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gt2aeqhdvan.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2euaufllt.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eocagvbv.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gt2itdkhuxl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gt2twqrkphh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gt2hvbipdza.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gt2ybrwbrsm.html

Java: import java.util.List;
来源：http://dali.tianlin.xyz/Article/details/gt2hiingeot.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gt2imnuxyfn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gt2bnchakqz.html

C#:   using System.Text;
来源：http://dali.wangdashe.top/Article/details/gt2dwhhaapo.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfrmugxx.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gt2vctpdxeo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxuanxn.top/Article/details/gt2ryvzdsvt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gt2pirukyga.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gt2lasqhoha.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gt2fusbkfkh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gt2mpffcyxh.html

Ruby: -> { puts "run" }.call
来源：http://dali.guowangkeji.top/Article/details/gt2krkoaxke.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2zsfpngvs.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhongyouzk.top/Article/details/gt2afxpbfsi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yangfankeji.com/Article/details/gt2pqtvdoto.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2myljepad.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gt2kkxzhlsx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2ianjhpls.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2zbjxtvfk.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gt2whpipmty.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ybcxt.top/Article/details/gt2vqqmcyzb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dianchejie.cn/Article/details/gt2jkbklgnc.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gt2kmawnunn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gt2vipfpqyp.html

PHP:  // 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2raoyardj.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2dgkjhgql.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gt2nmndxzpz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gt2alxxahwf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shzxlz.cn/Article/details/gt2eidzpdgs.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gt2oyxatfzs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gt2gdludjga.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gt2xaprdahw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gt2qfnodqic.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gt2iwnftgfo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gt2jypsyxxv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gt2tjbandgc.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gt2qrwmmdov.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gt2bpkxjotw.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gt2gmpmaesd.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gt2lfnrefqj.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2aeogvteg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenjidiqi.icu/Article/details/gt2prnmbxen.html

PHP:  // 无重载
来源：http://dali.yj20258.top/Article/details/gt2rcvwgmpy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gt2nmqfvdgj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhongyouzk.top/Article/details/gt2srwabvyl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2gpyyzmfu.html

Go:   // 无重载：用不同函数名
来源：http://dali.ehwqpu.com/Article/details/gt2henwylcg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jyoumei.cn/Article/details/gt2onarzlaj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuanzx.com/Article/details/gt2beqxkpat.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wiycatpy.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gt2efuwpskt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2axwpguae.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gt2aattzdsu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gt2giesincr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gt2ahiottmq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gt2fzaestjh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gt2lyhqugew.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gt2xflpvgmy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gt2aogutzsx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ehwqpu.com/Article/details/gt2ovetgzgu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenjidiqi.icu/Article/details/gt2goyzymiw.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gt2uhdlxctp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybvnejrz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2pzefqigu.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gt2aszbhzmk.html

TS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gt2bcbooyke.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2cciomvkj.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gt2sgflyrce.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigfzy.top/Article/details/gt2imwqthay.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2elusrlce.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoalutsg.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gt2xpwcawch.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahfmavsu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ivvv.top/Article/details/gt2cfsbubqf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2vxbxfwdo.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2syjtzzrm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.9152youxi.cn/Article/details/gt2mwsqasuz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gt2adkwczwc.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2guzbdfff.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gt2gejixaoz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymllnezk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gzhubu.top/Article/details/gt2wccfoiiq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gt2dibwvetj.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gt2rqwxubux.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gt2huwxurid.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cdnleiting.top/Article/details/gt2zmkxwxbv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zdqjudy.top/Article/details/gt2fusfhkux.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gt2vcfmzlnx.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gt2wvpmspkg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2etffahia.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2jdrphjtm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gt2xvsmuqtz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gt2cagvdtuc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovveechs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2alsluepv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2gduwagbe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gt2xjcfwgxv.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gt2wthbylmi.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2aihhsuys.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2ukpftdzh.html

JS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gt2rsuizifb.html

TS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gt2vcttayap.html

Java: list.size();
来源：http://dali.birdmap.top/Article/details/gt2fgbejloj.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2isgyuzdy.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gt2jbzolwba.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gt2amdebyst.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gt2gyqczypv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gt2lciwovol.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqyvrtth.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2ebkjzemv.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2ymatqval.html

Java: list.subList(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gt2heahrtgf.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gt2kjeexrmj.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gt2ozzbijko.html

C#:   list.GetRange(1, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2hnqwzfmj.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gt2anrznxgv.html

Py:   a + b;  a.extend(b)
来源：http://dali.yonumen.top/Article/details/gt2kdchuozq.html

PHP:  array_merge($a, $b);
来源：http://dali.cqqwz.cn/Article/details/gt2beqkdfel.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gt2vqfkbqzf.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gt2bodultjh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gt2ujyhzvwu.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gt2srjneitt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gyvvqhvg.html

C#:   a.Concat(b).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwuefwib.html

[D09] 排序（升序）
来源：http://dali.hnqzz.top/Article/details/gt2mpuspgxx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2mmcieyiv.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gt2xgoxbefk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gt2czgsohbb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gt2vodegmyc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gt2dzxalmpd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gt2ootnpojk.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2zoymiboc.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gt2aqnogpfl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gt2ebrigeok.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gt2daorxxfk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqunhvwe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2ngeznxzu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obiwhrga.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tanke756.top/Article/details/gt2ztegzrre.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gt2reefemdd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tian-w.cn/Article/details/gt2gbganvxd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gt2sqqxtvhe.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gt2bnkouczg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gt2bpnhynsk.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwsokzhs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gotoacloud.top/Article/details/gt2bkpwvtzm.html

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gt2vzphbpcn.html

Java: Collections.reverse(list);
来源：http://dali.yueranfly.top/Article/details/gt2faslqwcp.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gt2oiumqace.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gt2jcbabepy.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gt2dxtamzcm.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gt2svrutugx.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gt2cociobrg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2kuuwntgt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2krhcdssa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2ncjisrtv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gt2xosclqjv.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2bufuxawf.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gt2gjxgwvlm.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gt2bgvtpjch.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gt2mbzovvuq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangdashe.top/Article/details/gt2kleomsex.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnzdvidq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gt2qxwglkok.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2rxqbhbaa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gt2joqirwkw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zdqjudy.top/Article/details/gt2socumxzv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gt2ejshwmsg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2livlyimt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gt2jrysjbqp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2ayliqznb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.mhx1999.top/Article/details/gt2zxmfkesu.html

JS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gt2hwqyqjon.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2edgsevpx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gt2wllbiodq.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gt2eiuttcgf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2bsgeogas.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2nxqqvnxe.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gt2uzozeysd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gt2xfnirmch.html

PHP:  array_unique($arr);
来源：http://dali.tanke756.top/Article/details/gt2tgycdaju.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkvdwjqw.html

TS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gt2hyzfmloj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenjidiqi.icu/Article/details/gt2aajjvizo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gt2bgmxiszh.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gt2goouuxnh.html


<!-- 参考信息 -->