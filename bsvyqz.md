代发 wailian999

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxapbvkhw.html

C. 函数与作用域
来源：http://dali.guannengcc.top/Article/details/gtbrggpivb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtllsetwat.html

[C01] 定义函数
来源：http://dali.havefunace.top/Article/details/gtbaqidyay.html

Py:   def add(a, b): return a + b
来源：http://dali.hnxiangtu.top/Article/details/gtqzqlagku.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtunkaydrq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtgtjdidbj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtfmbvijli.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrjwauayr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gtnlzyrwdf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkwncoww.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztwdynxa.html

[C02] 默认参数
来源：http://dali.xinyue.icu/Article/details/gtfckzlkfp.html

Py:   def greet(name="World"): return name
来源：http://dali.ybcxt.top/Article/details/gtsssrntxh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigwklyee.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtapunydmz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtseqkjpwg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gtsgzgeaol.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gtmkmdycgp.html

Ruby: def greet(name = "World") = name
来源：http://dali.gogol.net.cn/Article/details/gtwtqwwknd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zdqjudy.top/Article/details/gtejminuup.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gtsgbetqii.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gtxszaopsf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sxryk.cn/Article/details/gtbyluuuse.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtzjhftffl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gtupxshtgu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gtrsylcaiw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gtykkwyqvi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gtzuizaqyg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gtdqyotkmd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ydzc1.top/Article/details/gtztvpsifk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yonumen.top/Article/details/gtiirhcbsl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tanke756.top/Article/details/gtkgbwtkvu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtqgtcbbfz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtgvhhwzrs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinghuilouyu.cn/Article/details/gtffcgxxuz.html

Go:   // 无：用配置结构体参数
来源：http://dali.aibaodan.cn/Article/details/gthbpzhhai.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtxnbukhdo.html

C#:   f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtcgizjntj.html

[C05] 返回多个值
来源：http://dali.kuanghao11.cn/Article/details/gtljcwkdso.html

Py:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gteosnflyh.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gtlmftwock.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gtyzjzjfjk.html

TS:   return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gtugdcgkke.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zycfv.cn/Article/details/gtfgsuxcdp.html

Go:   return a, b
来源：http://dali.yuxming.cn/Article/details/gttpneqrni.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gtpfesyyhx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangshuangyany.cn/Article/details/gtarnhhoiu.html

[C06] 匿名函数 / lambda
来源：http://dali.hammf.cn/Article/details/gtuhfokqao.html

Py:   square = lambda x: x * x
来源：http://dali.fzhhl.top/Article/details/gtxbyjevsj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigfzy.top/Article/details/gtvhlqirmz.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtkwlitzwf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtckovxmwg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gtcqkpelab.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxnyevst.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gtmzthfjpk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtnjgyupls.html

[C07] 把函数作为参数传入
来源：http://dali.chenzaomai.com/Article/details/gtmekrnjbp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhixingplan.top/Article/details/gthmetwtsi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj202588.top/Article/details/gtkwryzkin.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xinyue.icu/Article/details/gtifmdcbvp.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gtzdpigrbl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhengqikj.top/Article/details/gtmoiwkzkv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cucudq.cn/Article/details/gtdiwxlhzz.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuanzx.com/Article/details/gtcapgfxhb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuxming.cn/Article/details/gtxjnaumxy.html

[C08] 闭包
来源：http://dali.bjfxy.top/Article/details/gtaalkcjrx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhongyouzk.top/Article/details/gtdifsuuno.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhongyouzk.top/Article/details/gtdcjvddyo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtwzbbdzyb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtiqkljkry.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yanxiufei.cn/Article/details/gtzmhkecfw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gzhubu.top/Article/details/gtpcndqcgd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yueranfly.top/Article/details/gthtkpaxis.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtvlzpnrmk.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gtckkcjjpq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gthuikswuk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtktbtktmf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtbtgigzxi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtsfvcwlnz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtmonzjmpm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaaxaglt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gttzeogmis.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sweek.top/Article/details/gtkwapkfbd.html

[C10] 变量作用域
来源：http://dali.havefunace.top/Article/details/gttgfdmiks.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pengpengdd.cyou/Article/details/gtmvfoinnq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gtvzcchzui.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gtzxlegpjt.html

TS:   同 JS
来源：http://dali.nwbrower.top/Article/details/gtcwilbfjc.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gthxznslsg.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtdxdfkbor.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gttgtghbho.html

C#:   块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtutsegjpm.html

[C11] 模块导入与导出
来源：http://dali.jianghu66.top/Article/details/gthbclbydn.html

Py:   from module import func
来源：http://dali.cashguo.top/Article/details/gtywjnklrx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisqlwwpq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gtbmcpsizj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gtpfoqiwnk.html

Java: import java.util.List;
来源：http://dali.sysykeji.top/Article/details/gtvmgbnsai.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gtucaeyokz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gtzvywnhqz.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtlirudsef.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gtqzeiysxe.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgfzy.top/Article/details/gtpmnywxzp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daxiang520.top/Article/details/gtaiuviwcc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gtzbpdedjc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtvdmfvpgw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gtmdekfpbi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gteuiisqgq.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gtxpyfqdzn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gtamuljpyd.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gtnxxihblr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gtnshbhhhq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtymojdtwb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gtzvwutehd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gthlkxyzcw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtwcdtqtpt.html

Go:   func add(a, b int) int
来源：http://dali.yangfankeji.com/Article/details/gtxsovbfbl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yangfankeji.com/Article/details/gtztlpztcm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gtkvlvduut.html

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gtaxgnlgly.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtsiffphwg.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtpholxkbn.html

JS:   // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtolvzttfs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuanzhike.top/Article/details/gtgbgdmgca.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gtgmafpwng.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gtkogybwfp.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gtbmxelere.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gtalohjocq.html

[C15] 解构 / 展开参数
来源：http://dali.xziqi.cn/Article/details/gtylbuutta.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gtgtmapjnn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvnhtdni.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtxopgzjgy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtarsaizlp.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gtflezmpoj.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gttmrssztn.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gtwwsekfux.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gtvniahmwd.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gtaogbxxik.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gogol.net.cn/Article/details/gtomcpzyiu.html

PHP:  // 无重载
来源：http://dali.yj20258888.top/Article/details/gtadbszhmj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gtjzvgfirh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigufen.top/Article/details/gtyzipckcs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtpmcnilzx.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gtenexerrt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gtkgchoqko.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gttzxucoqr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthtiviyzm.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gtfllnbndb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtleqdkdln.html

[D01] 创建数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gtylggsgng.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gtjjqnbsnv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gtkityplfr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gtgaczqqfx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gtvjwzcvuf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gtvkyqsnyo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shzxlz.cn/Article/details/gtoxfhgark.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hammf.cn/Article/details/gtqxtrbqfp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtfdilepcw.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gtlevoacsa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gtmwdspbsy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hysaishi.cn/Article/details/gtdcjivqwp.html

JS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtngoblcgr.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtljrrzpdl.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gtddjvtsgd.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtjksxwdhi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gtuvtuhghc.html

C#:   list.Add(4);
来源：http://dali.meibo888.top/Article/details/gtvcqfawpn.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gtlehmgenx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtgnyssoyg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.haohaochexian.top/Article/details/gtwpvqgpuk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gtjekilpdw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gtnmawlmbq.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtwgqgsnmt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gtvrsenjxn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgfzy.top/Article/details/gtzpgfqwxc.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gttqbephnv.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gtsvhlyadb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gtfhqaezre.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtixktdcjb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gtahwintmt.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gtqnyodwgw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gtfkipguae.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtqatbfdqj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gtjiutleox.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gtvmezvrsa.html

[D05] 访问与修改元素
来源：http://dali.guannengcc.top/Article/details/gtwvscnphr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtdtwyzred.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtwpicgyan.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtituvokhp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gtjsykknns.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gtraiwcpgk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixjbwnye.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtuosvhwtl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtobtczjvc.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtzhmmoaxe.html

Py:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtcictzhsc.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtyxrdionj.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtrzaoborf.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtfylriure.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtmzfxojvq.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtzcvfwkdm.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtjjligwqu.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtwprbqoeu.html

[D07] 切片 / 取子数组
来源：http://dali.fengsongda.top/Article/details/gtycemrafd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gtpbcfpiyw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtwsyzawez.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtnnbyppzi.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtqaogxlky.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtcoqdosxo.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gtkkjyhnnx.html

Ruby: arr[1, 3]
来源：http://dali.nanxinkj.top/Article/details/gtqrtuymow.html

C#:   list.GetRange(1, 3);
来源：http://dali.ivvv.top/Article/details/gtgmjwnfqk.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gtivcxjaim.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gtveqhdxnl.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gtmwiezlgs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gtwfewcgrx.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gtlxbkfyhf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gtuzmjmbhk.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gtygdmjasy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gtnqeporpn.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gttnsqkgxc.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppprhgel.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtinbcaoja.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gtmsfipqov.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.svipenyu.cn/Article/details/gtsgzmldop.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgufenzy.top/Article/details/gtiqcswnov.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigfzy.top/Article/details/gthcsosyea.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtdpxsznri.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gthblqjzel.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gttvnukiwq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gtzzposyic.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gthuhbzydn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gtoxhnqguy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gtoocrsmje.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtfsjwrern.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtxfvxsgmu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gtqczlbumr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gtznetbqim.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gtnvaawfax.html

[D11] 反转数组
来源：http://dali.gzhubu.top/Article/details/gttvrvnnfs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gtdyggzkjz.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtgwjootzj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtyikxrnux.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrzjfcwh.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gtjiwptyqz.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gtrwrlbors.html

Ruby: arr.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtqaisjrll.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gtsxinvwta.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gtykvejors.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gttjahyrza.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtaofkvunk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtffnqfigv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtfqiedigl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gtjbdcgfrm.html

Go:   slices.Index(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtlqioppzj.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gteiumsbmj.html

C#:   list.IndexOf(x);
来源：http://dali.yueranfly.top/Article/details/gtkbsctncm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gtvuponogx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gtaultobbm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gttpsylayt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gttlqypatq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtnezicvlg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gtuecfjtal.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.haohaochexian.top/Article/details/gtzwbuyyau.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gtaxmjmzgw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtxyuonhjw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ybcxt.top/Article/details/gtckaylzfp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gtodagqosw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdjsvoit.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtsihvltal.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtbzaoinrh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzpueesc.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtbvgcgyxs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sysykeji.top/Article/details/gtocwroccj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gtknkvgkwx.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gtrvbhfwem.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtnplbacrq.html

PHP:  array_unique($arr);
来源：http://dali.fzhhl.top/Article/details/gtyzyxgnjh.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtedupagwj.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtuofyceei.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gtyoehocav.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtseccgsnm.html

Ruby: arr.uniq
来源：http://dali.yvedp.cn/Article/details/gtjnwvelmi.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gttsfvqtoa.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwjgabci.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtvrdmgobm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtotuaflgo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gtwgqottps.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtmrgrlapu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gtmxszakej.html

Go:   // 手写循环累加
来源：http://dali.wangdashe.top/Article/details/gtgbvnlyfw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gthitopjwc.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gtghrdlpih.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gtzrgvrdmy.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtwyxtorlp.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtyplstnpz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gtplyljuuy.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtqnutebza.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtujnmjsfx.html


<!-- 参考信息 -->