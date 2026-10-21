代发 wailian999

Go:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtoeyydwwt.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtlimahimc.html

C#:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gthzvbyitk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.havefunace.top/Article/details/gtvgrepnwi.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfukukut.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gtiublhpgg.html

JS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gtoaytpmbm.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtnliganiw.html

Java: if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gtgaqrbqwn.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gtsxkbekac.html

Ruby: return if data.nil?
来源：http://dali.iojbl.cn/Article/details/gtfnyofqxp.html

C#:   if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gtcgtupgpu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtsrntsbao.html

C. 函数与作用域
来源：http://dali.jqgufenzy.top/Article/details/gtgrtxmmev.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gthxmfpaff.html

[C01] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtgqosqozg.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdvqseem.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtrdvpnyyd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtvsiihnit.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtdrnvdhdo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtntgjpkcq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtmwlmiumt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jiagoushi.top/Article/details/gtzmgvtsil.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrodvrhjs.html

[C02] 默认参数
来源：http://dali.tian-w.cn/Article/details/gtaawdyvdb.html

Py:   def greet(name="World"): return name
来源：http://dali.hnxiangtu.top/Article/details/gtmpmykxop.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gtkkwuogab.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtfyageppr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtobhgqimw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.316326.xyz/Article/details/gtqczpuukr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dianchejie.cn/Article/details/gtobcyvipa.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnqzz.top/Article/details/gtxhnpyyfm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aizwys.cn/Article/details/gtivtqgxoa.html

[C03] 可变参数
来源：http://dali.nwbrower.top/Article/details/gtnyhxdbbc.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gtixcjcshz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gthevgphof.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gtxewbrpzi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtyijsglrn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gtdsgvcjvp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cdnleiting.top/Article/details/gtkjnmwvbn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gtmnpmhpgy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zycfv.cn/Article/details/gtevtheaos.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gtwsfpjdnu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shzxlz.cn/Article/details/gtqcwsufvn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyikwdlga.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtcxlfpxdj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jianghu66.top/Article/details/gtapkkusxb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhongyouzk.top/Article/details/gtzfocfryp.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gttlknnuoc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtwhyosspb.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtibqyzkdm.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtlomvezoh.html

Py:   return a, b
来源：http://dali.andypj.xyz/Article/details/gthejmkahu.html

PHP:  return [$a, $b];
来源：http://dali.hnqzz.top/Article/details/gtwdljrswc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gttsyuletb.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gthukapbvg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jlsjyb.cn/Article/details/gtzufcbnwk.html

Go:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gtphzszacu.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gtrrhcfnnk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsothkpf.html

[C06] 匿名函数 / lambda
来源：http://dali.wangdashe.top/Article/details/gtxztjjkgm.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsfxkbrc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gttlgtdqiv.html

JS:   const square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gttfmghpdr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gtjnbhejxr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gtfvqjuuwz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258.top/Article/details/gtefkewlnb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtjmzgzqjw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gttuvebsto.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gtjofoodym.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yuxming.cn/Article/details/gtiwloqnre.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hammf.cn/Article/details/gtplncnfgb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gtoetifvrg.html

TS:   arr.map(String)
来源：http://dali.vqdsnc.cn/Article/details/gtbfhlalsm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.bjfxy.top/Article/details/gtmnrcbzlq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xinyue.icu/Article/details/gtlgikppgz.html

Ruby: arr.map(&:upcase)
来源：http://dali.cqqwz.cn/Article/details/gtoiqfnyei.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gtspilyfbc.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gtvcgapkjz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ybcxt.top/Article/details/gtznaiuupy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nwbrower.top/Article/details/gtnbrmcqmv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtaevleenn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtltzebgma.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhixingplan.top/Article/details/gtvarfhopk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gtyuehpjiv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gtajqxwyqh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxisdbisr.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gtddnnajfz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtmimnyxtr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtclylixef.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfqgqdba.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtwvkrzgxy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtmfhxyhtc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtvifxgwrx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtcjoonnoj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gogol.net.cn/Article/details/gtaavjobcb.html

[C10] 变量作用域
来源：http://dali.jinqigufen.top/Article/details/gtuktpuucc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gttabamtxw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gtmaxwabvp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gtddpxxxot.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gtrxihsvnt.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gttbgxbphn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtzsehhorl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yongpay.top/Article/details/gteitgnddz.html

C#:   块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtmduovdds.html

[C11] 模块导入与导出
来源：http://dali.xylfe.cn/Article/details/gtmiwcenmr.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpldujec.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gtunosjfot.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtqapnsarp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gogol.net.cn/Article/details/gthsmrbksj.html

Java: import java.util.List;
来源：http://dali.zhoulong.xyz/Article/details/gtigfiggis.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.bjfxy.top/Article/details/gtexvtsxzs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gtttugeqap.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gtppzrutuf.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnqzz.top/Article/details/gtbjcnfvzt.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gtlrojbmgr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.meibo888.top/Article/details/gtsvpjvgna.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gttfgxvire.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtookvfnls.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gthwuhivtj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtqwqhyvxf.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gthntlqrqr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tianlin.xyz/Article/details/gtvcgfauye.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuanzhike.top/Article/details/gttyvesyuh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdamwzeq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtbgydvdti.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliokalae.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtrgmcklpw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtckaositf.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gtiroqjcpj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gtoplpkhvn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gtaufqjaac.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gtifotpiqn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gtwswjpbqk.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtvohivcka.html

JS:   // 无泛型
来源：http://dali.cashguo.top/Article/details/gtpygnasms.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gtunobjjfk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gttsgkaaru.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gtzxnrimnu.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrmzthax.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gtthynljmw.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gtcjsflgfo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gtojoyvdoe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gtahplnqik.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtcesujrpx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbfbnotom.html

Java: // 无解构
来源：http://dali.bjfxy.top/Article/details/gtzmqushaa.html

Go:   // 无解构
来源：http://dali.xylfe.cn/Article/details/gtipfxadff.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gtehpgdiay.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtqtrkagyp.html

[C16] 函数 / 方法重载
来源：http://dali.aibaodan.cn/Article/details/gtqhjthizl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.c1oappe.top/Article/details/gtdpufsxob.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gthvxtfuab.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtecelprho.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gtvygvgxtb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtgrbymlve.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gtqwrbvmui.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gtsilfzkpp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqaydjswf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtblkefeni.html

D. 数组 / 列表 / 集合
来源：http://dali.redwolf501.top/Article/details/gtegaxhtsu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjnlxwdfp.html

[D01] 创建数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtlnriflap.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gtueqjfavf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.c1oappe.top/Article/details/gtbdwzishw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jiagoushi.top/Article/details/gtyaeufnel.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gtonvocvnt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hfpthk.cn/Article/details/gtgcktojcx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pengpengdd.cyou/Article/details/gtamcbwlta.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hywenlv.cn/Article/details/gtnwjrfaqf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnxiangtu.top/Article/details/gtbaykjygp.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gtjxmicwlo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gtqsmsozcf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtfeyochbq.html

JS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtronsujul.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtsxabakyg.html

Java: list.add(4);
来源：http://dali.aibaodan.cn/Article/details/gtkdwgilfa.html

Go:   arr = append(arr, 4)
来源：http://dali.chenlongwang.top/Article/details/gtcjplpciy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gtwgftsdhl.html

C#:   list.Add(4);
来源：http://dali.svipenyu.cn/Article/details/gterfuaxbt.html

[D03] 在指定位置插入元素
来源：http://dali.chenzaomai.com/Article/details/gtyngqkorc.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtnegythur.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtblewglqs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtltwilvid.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtbtuzhbon.html

Java: list.add(0, 0);
来源：http://dali.tanke756.top/Article/details/gtxwzkadmz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtcuslxwmz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gtxvbrgukq.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtqsapwqrb.html

[D04] 删除元素
来源：http://dali.tianlin.xyz/Article/details/gtxgjuvbfa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gtwvqmywhs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dianchejie.cn/Article/details/gtsdwgjbxn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ivvv.top/Article/details/gtlztidibc.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgufenzy.top/Article/details/gtikbijqef.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtouwhpout.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gttgavvjqw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gtpbzoqypm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gtwqhrxpdz.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gtrhxlebmj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhzarskf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gthabfqfyo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtiuztwsym.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sweek.top/Article/details/gtbeyhrqqc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gtsuvjmgsu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtwydnporw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtutmgxrjw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtonsxehui.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtoghwgcdw.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtkjqiakjk.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtlnqzhkzy.html

JS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtbmvgnomi.html

TS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtzxhullys.html

Java: list.size();
来源：http://dali.nwbrower.top/Article/details/gtsowivxya.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtgntxprgt.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gtzxajtxsd.html

C#:   list.Count;
来源：http://dali.smart0.xyz/Article/details/gtaoiscxmb.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gtgmvoxahk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.meibo888.top/Article/details/gtyvvunzhq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gthcaunath.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtwszastsc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxolxazso.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtvccidgau.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gtpnacmwgv.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtfjbvsxaj.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvymajoo.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gtkznnmvgj.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gtcemcxwsi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhixingplan.top/Article/details/gtszzrancf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gogol.net.cn/Article/details/gtxhtykvoa.html

TS:   [...a, ...b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxjykemv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gtcolzduev.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gtovfojwan.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sweek.top/Article/details/gtiiezavut.html

C#:   a.Concat(b).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtjrqxmsia.html

[D09] 排序（升序）
来源：http://dali.yj20258.top/Article/details/gthakktvsl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtcavhtivj.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gtawwiequj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gtxisppyfj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gtzvgyaqtk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gtwjgcglcp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtynyzhmgq.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gttdcvcyhi.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gtnkmhaofi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jyoumei.cn/Article/details/gtploirlxi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gtfplrditr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtvesjipbr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtlwjmdqlg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtuwzyllfr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtpthqpifr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gtaylharcp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gtnaqzmoic.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnxiangtu.top/Article/details/gtczcbutcd.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gtotktaqgo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guowangkeji.top/Article/details/gtikseqqzc.html

PHP:  array_reverse($arr);
来源：http://dali.aizwys.cn/Article/details/gtzwtmnjwm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtfvtdvwcx.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gtiyeljtty.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gtgbutbazb.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtfcrxorru.html

Ruby: arr.reverse
来源：http://dali.mhx1999.top/Article/details/gtjisffsma.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gtuwbhaeku.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtqqhhofhj.html

Py:   arr.index(x);  x in arr
来源：http://dali.smart0.xyz/Article/details/gthndoqsmy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtumzvsmbz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtgvflahny.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohaivmpu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pycfn.com/Article/details/gtnzgkqfzt.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtssqvwrpv.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gttkimgcpo.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gtowlhwmbf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gtskuqkiwy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.redwolf501.top/Article/details/gtgvqiwqrc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtqfimyymm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtvhcqazlk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtnxtotkte.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gtjollhepn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gtlzojgfme.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtmhmoxfsb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xinyue.icu/Article/details/gtysvkacob.html

[D14] 映射转换（每个元素变形）
来源：http://dali.svipenyu.cn/Article/details/gtxrgyhqvy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gtwouqiqob.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtsjtixssi.html

JS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtkutwnydb.html

TS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gtlkclrfph.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gtsgykxivd.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtizsexdyq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gttfimqcbt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gtjnbhwfmg.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzfqujvo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtnbcohc.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gtsekgvfhd.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtymowhyuz.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtbceptdup.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gttxoejvna.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvckquakj.html

Ruby: arr.uniq
来源：http://dali.vqdsnc.cn/Article/details/gtmqesaoxt.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gttohnuneb.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gtlrxqyqzh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gtrpfvbwin.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtdpmmhtim.html


<!-- 参考信息 -->