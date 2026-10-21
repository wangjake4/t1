代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gtldctmhcc.html

Java: x instanceof Number
来源：http://dali.svipenyu.cn/Article/details/gtebvotyqj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.bjfxy.top/Article/details/gtjoxaznuu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gotoacloud.top/Article/details/gtmtskdbzr.html

C#:   x is int or double or decimal
来源：http://dali.feifeiyinyue.top/Article/details/gtrnzultpo.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gtocbprpvv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pycfn.com/Article/details/gtgqitlpiv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgufenzy.top/Article/details/gtjaydmkmr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtuvycsqxj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtjrbdtrqh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjpflvdef.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.bjfxy.top/Article/details/gtufiwmzcw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hfpthk.cn/Article/details/gttdddumcu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtrpzttxbs.html

[B15] 布尔运算与取反
来源：http://dali.hongshengwenyu.top/Article/details/gtnyqdwcyn.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gthvnjjaze.html

PHP:  $a && $b || !$c
来源：http://dali.gzhubu.top/Article/details/gtbrmhmlvj.html

JS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtcnbzoncq.html

TS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdvticho.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtmtoqmsgh.html

Go:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtnbdypbib.html

Ruby: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtpdxzjorp.html

C#:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtzmylqyzq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.0kj1m.cn/Article/details/gtggpqmpzj.html

Py:   if not data: return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxkcermb.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gtpzdbsqzh.html

JS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gtqmlloebp.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtwrnfttys.html

Java: if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtbawfeccf.html

Go:   if data == nil { return }
来源：http://dali.chenjidiqi.icu/Article/details/gtpritgpkj.html

Ruby: return if data.nil?
来源：http://dali.gotoacloud.top/Article/details/gtaekfjzak.html

C#:   if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gtcwfktkwv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtwiqzmqpr.html

C. 函数与作用域
来源：http://dali.jqgufenzy.top/Article/details/gtyyjbqueb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqopwzxuz.html

[C01] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtofbeiaai.html

Py:   def add(a, b): return a + b
来源：http://dali.ivvv.top/Article/details/gtevmgtpfj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtqufmxcql.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtmczskxnc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtsubdmhix.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtficgqcwa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gtgrhfebrv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shangyingyoupin.top/Article/details/gtqjhopxct.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtlydjeheh.html

[C02] 默认参数
来源：http://dali.yj202588.top/Article/details/gtwpaxcfep.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gtdaogvcry.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gtlpuanhtd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtjjkisizc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtwlzhyxge.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhongyouzk.top/Article/details/gtyvkoyyce.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aizwys.cn/Article/details/gteahntjre.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gtczlocoue.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gthlturjtl.html

[C03] 可变参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjroqfdk.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gtvkfjhhgp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.snrcjt.cn/Article/details/gtnyormmcm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gttlzgywgq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtailzkoih.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtqkwgqenk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gtchlwtaqr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtomhijvbu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sufxvd.cn/Article/details/gthkufmtzd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gtisfdrrnr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxuanxn.top/Article/details/gtumjcrwjn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtfkmziwvv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtonaszrzf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gotoacloud.top/Article/details/gtymbilhwj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gtluzhjzfq.html

Go:   // 无：用配置结构体参数
来源：http://dali.haohaochexian.top/Article/details/gtrrdklwbj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtiqbdzqcu.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszlwrigd.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gttfbdoftv.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtwjskotch.html

PHP:  return [$a, $b];
来源：http://dali.hysaishi.cn/Article/details/gtfsgwilxi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gtjupsnlow.html

TS:   return { a, b };
来源：http://dali.redwolf501.top/Article/details/gttxzgsiyf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gtgllyzeoa.html

Go:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvdajufv.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtxbjenggx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gtqxkggexm.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlskyqaj.html

Py:   square = lambda x: x * x
来源：http://dali.mhx1999.top/Article/details/gtrccxczuc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gtuofoxica.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtcpyqkzgf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtbftnzrtz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gtuhudbajh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gtrhbiddxv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gtoxvtnzzv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtbhxfchhl.html

[C07] 把函数作为参数传入
来源：http://dali.cheryme.top/Article/details/gtdpinsngc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinghuilouyu.cn/Article/details/gtirwfamul.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtmllefkwj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtlhmlwmjq.html

TS:   arr.map(String)
来源：http://dali.yongpay.top/Article/details/gtzifderrc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gtptmfrekp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfjztwsg.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gtuxtgvftc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gtfipdgqgz.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gtdfvygrhs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gtfmnpbykz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtaswnedxs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbilpzwxc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqlskxmwm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jiagoushi.top/Article/details/gtqtfwkmhs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.0kj1m.cn/Article/details/gtbbyefyzb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hywenlv.cn/Article/details/gtmxrbwxzu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtgijzwxez.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gtlqjzrevc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtirdhreyk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtmtgasjmz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtcqhlpfxo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtwrsfmsav.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpslaszqq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkwxohxu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtnsfgzppj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gtkqjtjktw.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gtsprbpdwv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daria6918.cn/Article/details/gtsdwmkwjs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtdzrdykhb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhixingplan.top/Article/details/gtlnfiuoyh.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gtijissbro.html

Java: 方法内为块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtebzhphzt.html

Go:   花括号块级作用域
来源：http://dali.shuidangran.top/Article/details/gtmfraycsq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yonumen.top/Article/details/gtrvbqkavd.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gtxlctirym.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gtyyaexuwh.html

Py:   from module import func
来源：http://dali.hammf.cn/Article/details/gtkifnyggy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gttnwylbwi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtbkvzzukf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gtsbmltaed.html

Java: import java.util.List;
来源：http://dali.xinyue.icu/Article/details/gtadyhzupa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xinyue.icu/Article/details/gtsymedtfp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gtocuqnilm.html

C#:   using System.Text;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosspzkng.html

[C12] 立即执行函数 IIFE
来源：http://dali.ydzc1.top/Article/details/gtfnyzwbux.html

Py:   (lambda: print("run"))()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhlsevjf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hammf.cn/Article/details/gtkhxrwqkx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtrryzgauc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtufdfrmqe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangshuangyany.cn/Article/details/gtsnmmoefp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtomadfgor.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gtylaawgjw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gtfsmvujdu.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gtjuxftlig.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtblykwgck.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtkkgbcrpa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gtksxouaoy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtinocnhkd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqxnnfgk.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gtpzcjtksh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gteqtvqyeg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gtkknhmefj.html

[C14] 泛型函数
来源：http://dali.yueranfly.top/Article/details/gtkwmlakut.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcsifmws.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtfttryqkx.html

JS:   // 无泛型
来源：http://dali.zycfv.cn/Article/details/gtttjcosmg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.haohaochexian.top/Article/details/gtikuucoiz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gtkekoaija.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gtaeibbxuf.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gtgaoixawk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gtaqrhpvxf.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtoshyrdwq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxflrfwp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gtpuqujcnq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtgeyjilgr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsksdrjge.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gtgmdsxdje.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnheqhsm.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gtddgaqpnl.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gtjxkllbml.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtztvjsqws.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtbeevphfh.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gtuhkqpmbi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.9152youxi.cn/Article/details/gtnevnewej.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtxofrpxbz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258.top/Article/details/gtmivdakha.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gtdkfyfeib.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gtpfvbctbp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gtmexukfte.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqkycihmn.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gtzepxhdmm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtitzekmdm.html

[D01] 创建数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefogrrne.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gthcmpbqan.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtvdatpxhl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtjosernbw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gtugytpnlb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gtwzzqiwni.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gtkeciilmk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gtdxlzhdyq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gtsibfrjgi.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyynacdus.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gtrkhkcisx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gtwqrusfyo.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtoyvmxtjh.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtowbcscqs.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gttvclrmnf.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gtnommdkcm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gtgjjjfryg.html

C#:   list.Add(4);
来源：http://dali.shzxlz.cn/Article/details/gtsemijuwo.html

[D03] 在指定位置插入元素
来源：http://dali.cdnleiting.top/Article/details/gtrpvwzfxp.html

Py:   arr.insert(0, 0)
来源：http://dali.guannengcc.top/Article/details/gtovrjvavc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhoulong.xyz/Article/details/gtqanbxhoz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gtekaaqnsj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtrkwmclfw.html

Java: list.add(0, 0);
来源：http://dali.cashguo.top/Article/details/gthpxtnjla.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gtrjykqliw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtmnseamar.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtycgnqkht.html

[D04] 删除元素
来源：http://dali.316326.xyz/Article/details/gthrnasvae.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtcsbutwfy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gtsctejcpj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gtfuhgpanc.html

TS:   arr.splice(0, 1);
来源：http://dali.chenlongwang.top/Article/details/gtdhzqntol.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gttjnndwlx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gtitvnmdqo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtuzdbbdyo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xylfe.cn/Article/details/gtnvgcmosp.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gthgmprwbo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtogbbbztf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtzwacreav.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtyjpzmzdw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhoulong.xyz/Article/details/gtkkswnxri.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gttgqutxui.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtfowtvxfs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtrlezfqab.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gthlolnktn.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtbaubyzof.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtwtehbcsc.html

PHP:  count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtgkrqooif.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtzcpeymqv.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gtismvhkds.html

Java: list.size();
来源：http://dali.birdmap.top/Article/details/gtgjowlzsr.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtnsahpdgb.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gtdmynlirb.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gtyvefwsji.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtkyockpwm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtketdagcr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtqbfvagln.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtgfosejbn.html

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtfccunici.html

Java: list.subList(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtvedjjkcz.html

Go:   arr[1:4]
来源：http://dali.ehwqpu.com/Article/details/gtebphplxy.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gtqconjvfz.html

C#:   list.GetRange(1, 3);
来源：http://dali.dianchejie.cn/Article/details/gttrjvhzmj.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtwlhqtzlp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtqbpbxjzg.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtxuzheqlq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hfpthk.cn/Article/details/gtrptnjnyl.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyoocehs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gthjoebrgq.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtihngqcww.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yanxiufei.cn/Article/details/gtsvxeytrw.html

C#:   a.Concat(b).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxiwwbhn.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtqhayzaev.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtwpxquept.html

PHP:  sort($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtupnqbqcx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinghuilouyu.cn/Article/details/gtstgiyjte.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gtnqfvawru.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hfpthk.cn/Article/details/gtyxmpzbmf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtwwgggmuu.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtythmoefo.html

C#:   list.Sort();
来源：http://dali.hongshengwenyu.top/Article/details/gtdgksdcnc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ivvv.top/Article/details/gtwztdrsje.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gtnzquxsaa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtzdvrpfgy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtkptblzvy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtygpntnoo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ivvv.top/Article/details/gtorvhirzf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gtibeabkxb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yongpay.top/Article/details/gtgobkmqad.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gtetkjzvvi.html

[D11] 反转数组
来源：http://dali.ehwqpu.com/Article/details/gtaczfncsm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangshuangyany.cn/Article/details/gtymydsckm.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gtedaiuxtg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gtcnaateml.html

TS:   [...arr].reverse();
来源：http://dali.jiagoushi.top/Article/details/gttsggzdag.html

Java: Collections.reverse(list);
来源：http://dali.ybcxt.top/Article/details/gteahaugmq.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gtdpneewir.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gtwziolxvb.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gtgihvsalg.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangtech.top/Article/details/gtmanoyjuk.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gtmvvhrkqe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuxming.cn/Article/details/gtcbxmabli.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gthkrhnckq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtmuqduoha.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtjcedphsj.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtdlhwudsv.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtxwtalmlp.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gtixpwfrnf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gtfpnvteef.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gtvplbinao.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gtrifkexwc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gthrruyvbf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtkhrkzkgt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gtlwsigkgs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gteyimujrj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gtnjxjodew.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gtlglaetsk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gtfcryaagb.html


<!-- 参考信息 -->