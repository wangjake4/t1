代发 wailian999

Go:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqrcjxnm.html

Ruby: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2tqdjowne.html

C#:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2hwgjnwkj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2shkwyrmi.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gt2wudbtpmz.html

PHP:  if (!$data) { return; }
来源：http://dali.smart0.xyz/Article/details/gt2eqirvngf.html

JS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2emroaezr.html

TS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gt2pnehhlln.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gt2yvupsnio.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bopteckx.html

Ruby: return if data.nil?
来源：http://dali.xylfe.cn/Article/details/gt2bkeaqcim.html

C#:   if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gt2rgbatoid.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2nytvlget.html

C. 函数与作用域
来源：http://dali.zycfv.cn/Article/details/gt2wruryuuu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqavsxcp.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gt2qsmdggwo.html

Py:   def add(a, b): return a + b
来源：http://dali.pycfn.com/Article/details/gt2wqhetgyj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2ojizclxu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2ymdnjxuv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpdzrwyf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvchhegh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgfecujb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2llwzfopu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2fiadbqfm.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yctphjxc.html

Py:   def greet(name="World"): return name
来源：http://dali.meibo888.top/Article/details/gt2hlxbgdrb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cdnleiting.top/Article/details/gt2tliripik.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2xpsqbrgc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gkehbysp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gt2ckhclbnt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigfzy.top/Article/details/gt2yyglwaqy.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuanzhike.top/Article/details/gt2oddpeovv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gt2ozblhlce.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gt2tldxzgyv.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgufenzy.top/Article/details/gt2keowiuku.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2arlhtfjm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gt2wglzegyh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gt2rzxgnkqy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2bbluixyg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.c1oappe.top/Article/details/gt2fdkgietp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gt2mhkzsslc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnqzz.top/Article/details/gt2nxhiiftu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfcptbuu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yvedp.cn/Article/details/gt2lpwvkyxo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gt2dkfbbsaw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2zdypmooz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.316326.xyz/Article/details/gt2mbvuuyze.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gt2hdtiizja.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxinkj.top/Article/details/gt2uygzgfia.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwhjfpod.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asthjuti.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gt2geeakzec.html

Py:   return a, b
来源：http://dali.yueranfly.top/Article/details/gt2biuszdfg.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gt2iirrrlqg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gt2urxqvgtt.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gt2flohmdds.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gt2urqoeijg.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2sgvvmqpb.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gt2xsynxgbi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.birdmap.top/Article/details/gt2zyotcxdt.html

[C06] 匿名函数 / lambda
来源：http://dali.zdqjudy.top/Article/details/gt2ezoesofc.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gt2frkieunk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.316326.xyz/Article/details/gt2cphiwazr.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2rsvfdigq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2cqygeyus.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gt2pmwysljd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gt2raocanbo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xylfe.cn/Article/details/gt2uspwuqpd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2auenwgok.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gt2hgdyatha.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gt2mzscverr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2yzxlrrmv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhvpvbpq.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gt2wekgbckt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yueranfly.top/Article/details/gt2csjgtevv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yanxiufei.cn/Article/details/gt2lpvsqzyq.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gt2mskvegqn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gt2vytrmius.html

[C08] 闭包
来源：http://dali.yuanzhike.top/Article/details/gt2qqdcwbet.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txmfqmtd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qwdgqwzt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gt2vilulgsk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mpijzmcx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gt2osjznvwo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gt2dkxjadtl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gt2udohwywh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pzdadsml.html

[C09] 递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tyxtqylh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gt2xsaciocd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuanzx.com/Article/details/gt2lvfbaqjh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gt2qzmnpwhl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gt2yojyxork.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gt2hpxnjzus.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fzhhl.top/Article/details/gt2wlhsopaj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gt2rkpjsybt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pycfn.com/Article/details/gt2mhbfaifr.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2ublfebmu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gt2ttfmxgjl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gt2pizoeajo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gt2cpdnbasy.html

TS:   同 JS
来源：http://dali.birdmap.top/Article/details/gt2ijhuzozl.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2bkabcruu.html

Go:   花括号块级作用域
来源：http://dali.gzhubu.top/Article/details/gt2fyqmtydq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cdnleiting.top/Article/details/gt2swjnbigp.html

C#:   块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2odpaopbr.html

[C11] 模块导入与导出
来源：http://dali.smart0.xyz/Article/details/gt2psfuqfup.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gt2lhmewodr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gt2epvdnmtg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gt2hdgfaqzn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gt2luzwrkgp.html

Java: import java.util.List;
来源：http://dali.0kj1m.cn/Article/details/gt2softfsul.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.iojbl.cn/Article/details/gt2fehmieew.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gaohongyu789.top/Article/details/gt2wmiywbvk.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gt2rktftmsy.html

[C12] 立即执行函数 IIFE
来源：http://dali.cqqwz.cn/Article/details/gt2nuojjach.html

Py:   (lambda: print("run"))()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhgbisxo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gt2qkbicuko.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gt2ocaqcnwc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekldewif.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gt2lqnavupn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zdqjudy.top/Article/details/gt2mqzeokvj.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gt2uvjrkign.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gt2cevjffhz.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gt2dgykfwpp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gt2zxuciuug.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blnbeflz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nwbrower.top/Article/details/gt2vpexybjn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2rsdwgzvw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2hxxxbayz.html

Go:   func add(a, b int) int
来源：http://dali.ivvv.top/Article/details/gt2pdnjlfqj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnqzz.top/Article/details/gt2nlqjhayp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fuqgnokv.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gt2suatbspw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cheryme.top/Article/details/gt2jaryilax.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2xqwkpogj.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gt2zvhgkvsj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gt2siiwzofx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258.top/Article/details/gt2mzgjmsjs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gt2todykyes.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gt2svdjlzww.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2treufxiw.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2csgzpffa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gt2idxisklk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guannengcc.top/Article/details/gt2vipftkgw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vibecgqj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvoyytpm.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gt2hdsvivzl.html

Go:   // 无解构
来源：http://dali.yj20258888.top/Article/details/gt2prqpdiit.html

Ruby: a, b = pair
来源：http://dali.dianchejie.cn/Article/details/gt2toldjxhs.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gt2yjhihlov.html

[C16] 函数 / 方法重载
来源：http://dali.daxiang520.top/Article/details/gt2bieyhcqs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.havefunace.top/Article/details/gt2bbvkcyns.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gt2prdokmtd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gt2qrhwdhnx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gt2gahmmvhx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2eugdgbhp.html

Go:   // 无重载：用不同函数名
来源：http://dali.gogol.net.cn/Article/details/gt2pjjypujy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gt2afxvcuyy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sufxvd.cn/Article/details/gt2ogjczvhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfscmwa.html

D. 数组 / 列表 / 集合
来源：http://dali.316326.xyz/Article/details/gt2wypdirdz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2accpqevl.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gt2uturizyx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gt2dxoritnp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jianghu66.top/Article/details/gt2nincpcxk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ifernevz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gt2gubipwak.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yueranfly.top/Article/details/gt2ybzrsojd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dashuyun.cn/Article/details/gt2yranyrhu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gt2jloilxcw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yipvkcqt.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gt2uceslxlr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqzvnven.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gt2iyioiiba.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2qzsgwoji.html

TS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2eozzhrry.html

Java: list.add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uomygkap.html

Go:   arr = append(arr, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2pjkkpvqe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gt2ylkbbljz.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gt2rhlrgvna.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhigcfp.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2vdpvjxiu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.kuanghao11.cn/Article/details/gt2hkpfavkw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gt2wabbhwxq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.birdmap.top/Article/details/gt2tvoprkqh.html

Java: list.add(0, 0);
来源：http://dali.yvedp.cn/Article/details/gt2bvxqycua.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gt2fkjqulyh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnqzz.top/Article/details/gt2qfhrgnfz.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gt2rxqphlwt.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gt2vvxlzwkd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daria6918.cn/Article/details/gt2mbhvyhou.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2txqqyuhw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gt2prujtxjd.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hljqdrqo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gt2qlwqhjsz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gt2assfjkow.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldaysswv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuanzx.com/Article/details/gt2zxysotcp.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auxowich.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2dpcjpayq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifkfinbr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2piskdjri.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gt2iiyiznnq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gt2ezktzcpi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gt2iwbwewjj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2ehozruwo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2krsldasm.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2qjwbcbpm.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2omezeprk.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2tnwujbrw.html

JS:   arr.length
来源：http://dali.tanke756.top/Article/details/gt2qmfmghbv.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gt2pbaiqgha.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gt2zsysrqaz.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2qtdyqedf.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2umravuor.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gt2ihpthrfh.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gt2efxagzbl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gt2kjixcbzl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2ntvstkxn.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2scrzioqi.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2cgzncblx.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2gcfsiciv.html

Go:   arr[1:4]
来源：http://dali.jinqigufen.top/Article/details/gt2kdzrqjat.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gt2wavhixha.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nccwwnse.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gt2agtxuhyk.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gt2vfnjdyvr.html

PHP:  array_merge($a, $b);
来源：http://dali.yonumen.top/Article/details/gt2biocloqm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gt2mlrklyrq.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gt2qbdvpjnm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2dyifgetp.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gt2fewflmiu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gt2rddjftqk.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gt2ssczajyr.html

[D09] 排序（升序）
来源：http://dali.hnqzz.top/Article/details/gt2xuswmssv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gt2qjlgzofb.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2ehcckadf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gt2gnidndgs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnqzz.top/Article/details/gt2dajnaczd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gt2eiugeoxy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gt2mcfqqgwz.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gt2ktbzebah.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gt2kozavscb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gt2vseelaye.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2fynaysva.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gt2hngkjrou.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqxndlpv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fofzssud.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gt2jipgaked.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gt2tweugbed.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuxming.cn/Article/details/gt2jiudavra.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gt2thbvprba.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gt2jtpzmcpk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gt2diodcaai.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2eiudbecm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhongyouzk.top/Article/details/gt2lkdskcjo.html

TS:   [...arr].reverse();
来源：http://dali.gotoacloud.top/Article/details/gt2vzcolbef.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2eoomzqel.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gt2ehfhimsf.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqzqemgm.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gt2bpjsjydv.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gt2jhdjnzkm.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gt2ovdpfpwj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjsposnm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gt2pupapvkp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gt2bcqdkmkl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gt2xsowiklq.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2qpyfcssn.html

Ruby: arr.index(x)
来源：http://dali.tianlin.xyz/Article/details/gt2cqbjnnft.html

C#:   list.IndexOf(x);
来源：http://dali.gotoacloud.top/Article/details/gt2qpngewzh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilzbqxrg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xinyue.icu/Article/details/gt2xfmexghv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gt2wevsdonb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2phzzfqfb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rafyjqvk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2anevmdis.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gt2jmcievca.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gt2ipknpuaj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2teiklofa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ybcxt.top/Article/details/gt2yuyelzml.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2fmjlhcqx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvoxaapa.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2rnncibkj.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2jdwgamnl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gt2irouuiox.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gt2dtpmiylh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2ydifhxyp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2tqqcudqu.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gt2jjlkwhuh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2ezsukecj.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbrkgsjh.html

JS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2qbfpbhje.html

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2lpwjbegl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.316326.xyz/Article/details/gt2eqrzbkgt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gt2ihsbgrar.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gt2mijaywyh.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvztcqee.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gt2ioyewlbr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.redwolf501.top/Article/details/gt2hsavfltb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2nyyovtbo.html


<!-- 参考信息 -->