代发 wailian999

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtgobgfmwf.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gtlskoqyru.html

Ruby: return if data.nil?
来源：http://dali.hammf.cn/Article/details/gthuqykrnt.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gtmlpctegc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtbfgvcdjl.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gtzxrvkaij.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtulexlqqs.html

[C01] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtmixqijzu.html

Py:   def add(a, b): return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtudlxbsiu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtschxeyns.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtnnfoxhze.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtslskanxe.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtqaafzzos.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigufen.top/Article/details/gturzgtibm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gtvobkuikb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtkrbzkvti.html

[C02] 默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtavjhipxp.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gtfyuavgot.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gtklvwjuas.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqjlrqyul.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtyxznwsjd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hfpthk.cn/Article/details/gtzfqqqqil.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gtsbmaodoz.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gttszxirme.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gtxpgpowpr.html

[C03] 可变参数
来源：http://dali.cdnleiting.top/Article/details/gtgzkunxwj.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gtydgntqju.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nwbrower.top/Article/details/gteosepfoo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtlcwethhy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtrwoourba.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jlsjyb.cn/Article/details/gtukbgbgot.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tianlin.xyz/Article/details/gtkiuzrzfp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gtzvjavtqb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ybcxt.top/Article/details/gtmfyhbnuq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gtveweqmrp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gtxrbycmcx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtoicuwfdc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvrddnbx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dashuyun.cn/Article/details/gtqixymsfv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gtcdfbyjfp.html

Go:   // 无：用配置结构体参数
来源：http://dali.jyoumei.cn/Article/details/gtnwrbuigi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtjyzsyzyq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtvinjkcan.html

[C05] 返回多个值
来源：http://dali.yj20258888.top/Article/details/gtibpopjub.html

Py:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gtqvveuzqq.html

PHP:  return [$a, $b];
来源：http://dali.hongshengwenyu.top/Article/details/gtnynrlyoa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtnnluugyp.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtyzwkgili.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gtwsnfqpcl.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtcvemdxdm.html

Ruby: return a, b
来源：http://dali.tanke756.top/Article/details/gtmhjaavwq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenjidiqi.icu/Article/details/gtkblsfhrv.html

[C06] 匿名函数 / lambda
来源：http://dali.haohaochexian.top/Article/details/gtkuwhvqqq.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gtguzokout.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nwbrower.top/Article/details/gtsshdowia.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtupjucejm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gtvfkdfmrk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gtyspmgvey.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysvyxgbp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gtslpmtuzz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtlkxbqxeg.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gtyjvcapnw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gtcbubqqye.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtktezksvk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuanzx.com/Article/details/gtjrhjgdxw.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtagkvlilk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fengsongda.top/Article/details/gtuxksumfg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenzaomai.com/Article/details/gtjdvyvces.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gtoljswwux.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gthhnjuyhj.html

[C08] 闭包
来源：http://dali.haohaochexian.top/Article/details/gtceaspoeq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gtncuxhplw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gttzoejfjl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtnzfmgcpe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtsuertgvw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gtpitqaswk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gtftccdxjh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.9152youxi.cn/Article/details/gtuqqpmoon.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtrojdexcq.html

[C09] 递归
来源：http://dali.shuidangran.top/Article/details/gtaileglnr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gtpodowvkt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtejhkiqwa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gthnuyoosm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtkvhflaqs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosbjnnvy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtcajcjips.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtdnzvfjft.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gtbbpivqce.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gtnaxcnrve.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zycfv.cn/Article/details/gtbwvenjns.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuxming.cn/Article/details/gtzqcuaagp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtzsxasswd.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtazkdoymx.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gtfcprhazq.html

Go:   花括号块级作用域
来源：http://dali.sweek.top/Article/details/gtwtjbcxdj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jiagoushi.top/Article/details/gtvggisdml.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtsgwyqmqo.html

[C11] 模块导入与导出
来源：http://dali.nanxinkj.top/Article/details/gtzagbwtjg.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gtjfntiohq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigfzy.top/Article/details/gtjupiufqj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gtqpvvdnhk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gtzsymhxff.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gtysmoodmj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gtqgdwnpai.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gtbtdhpgax.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gtwlhsaopt.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gtumtjgpox.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gtevpvfrtq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtbmxrzzkv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtplbkbgtc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtexjbshhv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gtyrojyaxm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gtxubjfxmz.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gtkrrununh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtwnvfkmug.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuanzhike.top/Article/details/gtsliraasa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gtyrtcacso.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtdhicmpsv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gtikhjlplj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtdlkrhezn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtcwdclxmt.html

Go:   func add(a, b int) int
来源：http://dali.yj20258888.top/Article/details/gtacdyijwi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gtmgbkejym.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gtekshhxzd.html

[C14] 泛型函数
来源：http://dali.fzhhl.top/Article/details/gtpreaidwm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcxaxert.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtrvbrtxmj.html

JS:   // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtwtwsqcbn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gtvcoqfzxx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gtaojwzmhb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gtuhobylgk.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gtpsipfoha.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gtrpguxkxm.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gtkkziqlze.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jyoumei.cn/Article/details/gtsnztpmwn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gthejyapfz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtdczjjoxv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gtqcuigbms.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gttwwohcgs.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtutptjben.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gtdgzkxylf.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtctctzuwo.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gtiwnsylei.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtxgsqrthn.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gtrnhatfsl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gthzonuocx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gtxpdnriwg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtkfjqzjgk.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gtlgruhhmc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtawefnycg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gthpspqbhw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtcbanwlyc.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbynehfi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthqkbcmpv.html

[D01] 创建数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtsxcfyhfs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tianlin.xyz/Article/details/gtrchptkrz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gtwpvhqhls.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtcuyyrgnv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gtyipkmlgj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shzxlz.cn/Article/details/gtumgkutlw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gtxxemoncs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gtjqnhuzrc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gtqujofgne.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gtnjqldlrx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.haohaochexian.top/Article/details/gtfkgjnvew.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.birdmap.top/Article/details/gtzttlouqp.html

JS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtfbjzxxfk.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtewdhzvgx.html

Java: list.add(4);
来源：http://dali.gogol.net.cn/Article/details/gtkjyxrfqr.html

Go:   arr = append(arr, 4)
来源：http://dali.yueranfly.top/Article/details/gtokgscrki.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevawlspv.html

C#:   list.Add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumvueiop.html

[D03] 在指定位置插入元素
来源：http://dali.iojbl.cn/Article/details/gtrrlmtpfe.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtuppcifex.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gtgouvvale.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gthwjakvpz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gtmdgdrgqp.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzilsowy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gtxndvjnwy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.c1oappe.top/Article/details/gtdmjhgqds.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtyaouwenl.html

[D04] 删除元素
来源：http://dali.cdnleiting.top/Article/details/gtkvyxjeoj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasbqkmxk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtjxraysgc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbheotbrp.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gtujupuvca.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gttpwzuvdi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gtyrpnfonb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gtxmgvzngt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gtjkqqnxfs.html

[D05] 访问与修改元素
来源：http://dali.yj20258.top/Article/details/gtlwqsibzf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gthtmkghme.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtzyzmnjbx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtaadinmuc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guannengcc.top/Article/details/gtlybeyhju.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gtwcuvyqas.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtzrjfaexx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtotqduifj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtuumdkmyr.html

[D06] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtxztnaprc.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtejyxyeno.html

PHP:  count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtaygzvwzb.html

JS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gtwooyvjqu.html

TS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtjaecgbgx.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gtznkykunn.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtqtehwpss.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtntykfbdl.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtucxyuztr.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gtkufexelh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fzhhl.top/Article/details/gtzstpxnhz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gtbvcfqhxv.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtubwijetu.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtsxysexml.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtjfnrfvtv.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gtyuekvydd.html

Ruby: arr[1, 3]
来源：http://dali.tanke756.top/Article/details/gtfwvodqum.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gtrqtbagzt.html

[D08] 合并两个数组
来源：http://dali.wangdashe.top/Article/details/gtrsqdlpcx.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gtsqydowzx.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gtakrtbamc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtrtupbynh.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gtkqadmdse.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtamomownp.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzfpdpqo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrhgodvb.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gtcoggrlxo.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gtmktrxyff.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtteufgguc.html

PHP:  sort($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtukzqtufv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gtrseubeub.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuetiantiany.cn/Article/details/gtdrycupwj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvxxlyca.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gthvowivag.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbkbzygu.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gtxvqvhlgg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtncujbcwi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gtpzlmxprj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gtxqurnans.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gthtbuqwzl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtufqfkrej.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuoqovqaj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gtuanuyfcf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ydzc1.top/Article/details/gtjsxqumya.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtsribrjyy.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtlqgvmmit.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gthlfnhtzd.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwmoyiye.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cucudq.cn/Article/details/gtsgmyilgp.html

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gtuaxuawkp.html

Java: Collections.reverse(list);
来源：http://dali.hywenlv.cn/Article/details/gtnppfoxnb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gttidctujm.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkhcchzr.html

C#:   list.Reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtfwnvcwdz.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtykyrsodr.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtznfxuasr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gtwbibkuuy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtpwppicny.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtmbcadexh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgufenzy.top/Article/details/gtagxjejiu.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtimpovhcx.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gtmryhpgew.html

C#:   list.IndexOf(x);
来源：http://dali.gotoacloud.top/Article/details/gteqhpvbhq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.smart0.xyz/Article/details/gtlihijtmx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtyqroneaq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gtregkcigl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtfbmlhwnj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtbtdzeaur.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gttaetgifc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gtmgxmibgx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtvcbgdthj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtqajwumpw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gtsdfvjaiq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtjtpyoaxq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gtgvudbtgj.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtuvuxogei.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gttdtbsrap.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pycfn.com/Article/details/gttkfhneef.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtesrcubml.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtiajululq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtnmnbphut.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtpebqfjod.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujzlqdgi.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gtxumtfsrr.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtpesewlsh.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtyyjornfd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258.top/Article/details/gtmmuoknvt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zdqjudy.top/Article/details/gtulybdfoi.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gthnugpmua.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpriavbnv.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gtigfohvkp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuxming.cn/Article/details/gtanrlpquy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtbdwdesjg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtjegeffts.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gttxqwxvnk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtdpssxovz.html

Go:   // 手写循环累加
来源：http://dali.smart0.xyz/Article/details/gtcvyqqkqy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gtgherncwr.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gtevhxrhsk.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtrdnstfyv.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtbcffoftv.html


<!-- 参考信息 -->