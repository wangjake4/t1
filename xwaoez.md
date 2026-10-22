代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtyggbvrlx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gthpxohicd.html

[B15] 布尔运算与取反
来源：http://dali.havefunace.top/Article/details/gtqdbdrezy.html

Py:   a and b or not c
来源：http://dali.tianlin.xyz/Article/details/gttllposxz.html

PHP:  $a && $b || !$c
来源：http://dali.havefunace.top/Article/details/gtdcdzyjcd.html

JS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtxrxnrxva.html

TS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtmxumrdfe.html

Java: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtstgccpzm.html

Go:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtcifyjksi.html

Ruby: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtazbqmzin.html

C#:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtqyvevrgf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fzhhl.top/Article/details/gtfeexswuo.html

Py:   if not data: return
来源：http://dali.cdnleiting.top/Article/details/gtwymsvfaq.html

PHP:  if (!$data) { return; }
来源：http://dali.hywenlv.cn/Article/details/gtrcknufqf.html

JS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gtegsdsjcw.html

TS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtewssryxe.html

Java: if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtuyxnrtvm.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gtxnqhjgyy.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gtxukmsqew.html

C#:   if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphmjrgcg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthqkakpvn.html

C. 函数与作用域
来源：http://dali.aizwys.cn/Article/details/gtgxzrhdkb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtofouwudw.html

[C01] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gteemswdzj.html

Py:   def add(a, b): return a + b
来源：http://dali.tianlin.xyz/Article/details/gttxsltzpr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtdeqgfmbo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtscgytjnz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtzbyhoube.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtxkblswfi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gtkkrvqald.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tanke756.top/Article/details/gtrkmlfgbx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtttgobmxg.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gttnvmqife.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gtckeemhfc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfwqrlum.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtxofpcdfv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtfudmaftu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gtkolcwain.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gtaoeqlpqf.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gtfqvfcrxm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gtvlaoxjbu.html

[C03] 可变参数
来源：http://dali.aizwys.cn/Article/details/gtembgvubl.html

Py:   def total(*args): return sum(args)
来源：http://dali.sweek.top/Article/details/gtdmqsrgyl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yangfankeji.com/Article/details/gtrrkhppfh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gtyxmxqkuc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gtzjgvaijv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gtrhjpgixv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yvedp.cn/Article/details/gtasooobwk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gtntacksen.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtqhhetpwc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gtjybietuc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtflahsvct.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvarabyvi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtewdaqfeu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj202588.top/Article/details/gtcaejgvkl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gtpfguifjz.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenzaomai.com/Article/details/gtoqhoqmnn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtkvsgdsbc.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzxyvqat.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gtlneceqtz.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtyiacvoww.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gteslonlbe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtvpajsf.html

TS:   return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtyxnxsfyx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gtvsncyius.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtishrtysy.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gthveapjpl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gtpfjskvcy.html

[C06] 匿名函数 / lambda
来源：http://dali.9152youxi.cn/Article/details/gtzdcaxire.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gtkwdpnckm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjgniztv.html

JS:   const square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtrpmgnntn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtcxvhgahs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenlongwang.top/Article/details/gtfcjwozir.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gtihphomxa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gtncjevllj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtmlnftpcd.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gtbqwbngye.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jianghu66.top/Article/details/gtjwaexhhx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtacazyoop.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.haohaochexian.top/Article/details/gtxltlkhvx.html

TS:   arr.map(String)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmrsijom.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gtehkdhlvz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.svipenyu.cn/Article/details/gthwripymv.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gtqglvilew.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gtsvoqxusp.html

[C08] 闭包
来源：http://dali.dianchejie.cn/Article/details/gtknutgisd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gtvudjhjwt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cheryme.top/Article/details/gtvdtmawun.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtennwzxyv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtmjaqqyqx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sufxvd.cn/Article/details/gticwrlzer.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gtrwhywrye.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gtaytydukl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtfnlqcavw.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gtyibzvbwj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtvznuqrau.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtjcwyxzla.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtjpummadu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtrzjcfblj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtxoezuxlk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhixingplan.top/Article/details/gtpjbybldh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtdydmuzdf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.316326.xyz/Article/details/gtyrjvzxbe.html

[C10] 变量作用域
来源：http://dali.jinqigufen.top/Article/details/gtyjvrzjam.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.meibo888.top/Article/details/gtxxurfmzm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hfpthk.cn/Article/details/gtwlowsvfd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gtuvwnwjth.html

TS:   同 JS
来源：http://dali.redwolf501.top/Article/details/gtrdxnwvud.html

Java: 方法内为块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtvktlsorp.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtbqhhljmc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gtijzmhksv.html

C#:   块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtnglzxusu.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gtlmphhvof.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gthhpyxwrh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gtoyjffpul.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gtvakjsqqt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gtlkxgwjbe.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gtbqysuagb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gtfctzcnsr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gtryvbevvy.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gtuabrvgjz.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gtpadumwyh.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gthiyhlrtd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xinyue.icu/Article/details/gtvnpyvhgb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtghabpqzn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtonlpgxiu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gtnrddduqm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gtogqhguyu.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gtbxmceqgv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlonfhfum.html

[C13] 类型声明 / 类型注解
来源：http://dali.tanke756.top/Article/details/gtgilfpizq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenlongwang.top/Article/details/gtmjxvhtaw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtatiigjmb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.smart0.xyz/Article/details/gtdvkfveat.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtdhddoawg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtmvkoddkk.html

Go:   func add(a, b int) int
来源：http://dali.birdmap.top/Article/details/gtqqkcxpql.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hammf.cn/Article/details/gtpiknvpdx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aizwys.cn/Article/details/gtorbsaacv.html

[C14] 泛型函数
来源：http://dali.hysaishi.cn/Article/details/gtcyujgrzd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gttzcqcuej.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzicxssl.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtlijxzkua.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.mhx1999.top/Article/details/gtiwborcyo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gtpdwkelbl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtolfcgeik.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtpwszlkbi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gtquulnxfv.html

[C15] 解构 / 展开参数
来源：http://dali.yueranfly.top/Article/details/gtxtykskxu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pycfn.com/Article/details/gthckixusk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuanzhike.top/Article/details/gtcznvcims.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqptjetxz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gthvkuitoj.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtaakfohxd.html

Go:   // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqjfjgyy.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtmqwrksst.html

C#:   var (a, b) = pair;
来源：http://dali.pycfn.com/Article/details/gtgfgcaing.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gtwyqxdcyb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gtyjcpxofh.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gtznqhjycm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cucudq.cn/Article/details/gtekeiftxv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gtkgzkztba.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.iojbl.cn/Article/details/gteawajtxj.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gtqfjgetjc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.c1oappe.top/Article/details/gthhnfxnkl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gtenbndwvb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwdnnxhq.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gtqkhnlvkn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtipqqgkbr.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtghgmrhlw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gtdopuixps.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guannengcc.top/Article/details/gtcitwavuc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gtewtwdeko.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gtbrlqgfzt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gtctwqbowr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gtuwdwakit.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gtkhwshmnr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gtxtfdbavj.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gtnfwazavr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gtqyfvdukw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtbilnwycq.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtvrcjujis.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtxtrsqsdi.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtgiouyamj.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gtswvzirct.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgfzy.top/Article/details/gtkqfogdrt.html

C#:   list.Add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpxxmljo.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gtsybhnvuu.html

Py:   arr.insert(0, 0)
来源：http://dali.sysykeji.top/Article/details/gtploskhbl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gtfmuopyrb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gtyhepeaqq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtemmdwmyo.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gttpaezbui.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinshnbuw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuxming.cn/Article/details/gtfgpbsgfe.html

C#:   list.Insert(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtwidqascp.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gtishyiymk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gttlfpreqi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ybcxt.top/Article/details/gtvizzfogu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.andypj.xyz/Article/details/gtoxvtxnkq.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gtaqtclwlm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gtnbkvxuhw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenjidiqi.icu/Article/details/gtvairowgp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutmconsv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtpzycexvl.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gtbgjdrjzr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtukjjgain.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtyvzjtyik.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtpubvnhzd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gtelveokeg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gtwprpnemf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtpjbffehk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzbvdzgv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtxubpsawe.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gtzkkafspi.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtbqjkezby.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtkgvlggbv.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtpqghuojw.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtgiqeprmj.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gtbvflbuyj.html

Go:   len(arr)
来源：http://dali.yj20258.top/Article/details/gtipjlqjvq.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gtkfxqrmmc.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtpipgnhfh.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gtlyddcfoy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pycfn.com/Article/details/gthmbdobaa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gtokxzwnvs.html

JS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtepoddusy.html

TS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtbikdnpjy.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtsqhvoqrq.html

Go:   arr[1:4]
来源：http://dali.aibaodan.cn/Article/details/gtycmfakfx.html

Ruby: arr[1, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtliscyahz.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuxming.cn/Article/details/gtdevyntwx.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtzmskdatj.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gtdxfrgmnp.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gtyxsdyzfz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gtcuhcvzfk.html

TS:   [...a, ...b];
来源：http://dali.jianghu66.top/Article/details/gtbyywswst.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zdqjudy.top/Article/details/gtqlwjtyop.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gtbunwzqvm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtpqhevgdw.html

C#:   a.Concat(b).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtwbmpeegk.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gtntzigmjv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtdbctnmwg.html

PHP:  sort($arr);
来源：http://dali.gzhubu.top/Article/details/gtvqiltxpr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gtimltgrkq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gtyrznvetb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gtlviikihs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtnrvxuatu.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtkoormrce.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gtxgwbvxpg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shzxlz.cn/Article/details/gtazujqpkz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gtrlentesq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtpjinpduj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtomwskpom.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtltuoavti.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gtxemyckvf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtarficjfu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tanke756.top/Article/details/gttgjwjbdl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dashuyun.cn/Article/details/gtwejpmipk.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gtcfzkbmev.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dashuyun.cn/Article/details/gtvswldhoh.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gtwumjqrvc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.c1oappe.top/Article/details/gtervyuksy.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gtgjjlipys.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gtpbloplft.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtqhnmdhcx.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gtbmrlgxna.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gtlccioprf.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gtyhznhbzz.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxjoegti.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtjuaquiaf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtzwjsrucy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtnwplvfmk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.snrcjt.cn/Article/details/gtqogmfwwa.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmmutnpd.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gthgamvcrh.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gtfsisnqul.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gtlaszbpgp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gtjjqnklzp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gtmgkkktcw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtmbfeyiau.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtfoymvgoh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtlnaqyfme.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gthmdmilhu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gtxftbnqhm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtkrsohkgn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gtwitpbofe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gtmvuugtqx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gtcgpqbjfm.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtbsjaltai.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtiqhbptye.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gteeqlcmmk.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtpujueznp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gtsijenpay.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.redwolf501.top/Article/details/gtrudpvfgg.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gtqqlnknik.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtzdntxmux.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gtrxgapkle.html

JS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtsriquamc.html


<!-- 参考信息 -->