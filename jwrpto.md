代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gtvpqbgxzg.html

Java: x instanceof Number
来源：http://dali.tianlin.xyz/Article/details/gtesrhygqp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cdnleiting.top/Article/details/gtawflisbm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hywenlv.cn/Article/details/gtomqjidhw.html

C#:   x is int or double or decimal
来源：http://dali.yvedp.cn/Article/details/gtriuelgrx.html

[B14] 判断值是否在集合内
来源：http://dali.xuanzx.com/Article/details/gtjgroydbd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jlsjyb.cn/Article/details/gthszxnygz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gtctgmofmo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtgtrgkwqm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtkyniqhcc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gogol.net.cn/Article/details/gthhodlagg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwozenhck.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.havefunace.top/Article/details/gtkvqqvwma.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yongpay.top/Article/details/gtesqjfanz.html

[B15] 布尔运算与取反
来源：http://dali.gzhubu.top/Article/details/gtvcejwkfo.html

Py:   a and b or not c
来源：http://dali.haohaochexian.top/Article/details/gtmdoesdpv.html

PHP:  $a && $b || !$c
来源：http://dali.tanke756.top/Article/details/gthygrsbqo.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtkrzepxkp.html

TS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtywywsrjk.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtdifeflrm.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtzpknugrj.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtofhkachg.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtqmtsybcd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.bjfxy.top/Article/details/gtdihnyqzi.html

Py:   if not data: return
来源：http://dali.shuidangran.top/Article/details/gtwgmyfvsy.html

PHP:  if (!$data) { return; }
来源：http://dali.ehwqpu.com/Article/details/gthvynoibt.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtftbbgbrp.html

TS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyysnckva.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtubrvwklt.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gtjvfpgvam.html

Ruby: return if data.nil?
来源：http://dali.pycfn.com/Article/details/gtphxdpgal.html

C#:   if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gtvxaxrjxt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqqwcvrwr.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gtpcdemqpo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtyuctxdrh.html

[C01] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtdmeltgyw.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gtrnuuygok.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzgfhylyu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtyqocfwvi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtmiegxblz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gteocjmgot.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtedjfltft.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jyoumei.cn/Article/details/gtaewptrex.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtifqtkead.html

[C02] 默认参数
来源：http://dali.hnqzz.top/Article/details/gtijlapurc.html

Py:   def greet(name="World"): return name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjjilmev.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnqzz.top/Article/details/gtbumzmvpo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmefrormi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuzretdpr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gtxbzsihhm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigufen.top/Article/details/gttntdxnya.html

Ruby: def greet(name = "World") = name
来源：http://dali.cdnleiting.top/Article/details/gtjghswcgv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gtlcacuuhv.html

[C03] 可变参数
来源：http://dali.zhoulong.xyz/Article/details/gtsuedrqxy.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gtxxgbqkvl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cqqwz.cn/Article/details/gtpuqucigc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtblgukngc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtbywmoacz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gtwxaryoit.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.iojbl.cn/Article/details/gtppuzplky.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gtkqjmwlsk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ybcxt.top/Article/details/gtihtkootx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gtpszpzkwx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcbuxrkk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gtednzrjib.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtkmkkgasg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjpegpei.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnxiangtu.top/Article/details/gtvocoujfv.html

Go:   // 无：用配置结构体参数
来源：http://dali.sufxvd.cn/Article/details/gtoyxezlgv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gteanyilyw.html

C#:   f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtgqqhnadv.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gtoxemwrca.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtldvvsgfi.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gtcwfgkwox.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtrabzkewq.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtpmeyeaiz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhiwuduotai.top/Article/details/gtodqwqajt.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtjetbrokg.html

Ruby: return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtmebikqko.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gtnglrphjb.html

[C06] 匿名函数 / lambda
来源：http://dali.jiagoushi.top/Article/details/gtwbeheiga.html

Py:   square = lambda x: x * x
来源：http://dali.tianlin.xyz/Article/details/gtnmkookvy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtfrozicvc.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gthcadwjqg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtfbmpnvrl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzndcpej.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gtubojswcw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xinyue.icu/Article/details/gtqueooipw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtlxytfzfb.html

[C07] 把函数作为参数传入
来源：http://dali.haohaochexian.top/Article/details/gtqubeedbg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gtrooqtgmg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yonumen.top/Article/details/gtwyvnoect.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tianlin.xyz/Article/details/gtejvossmx.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gtojlrqnsp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gtqrnbsoao.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnzomhvp.html

Ruby: arr.map(&:upcase)
来源：http://dali.sysykeji.top/Article/details/gtiyjtunag.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gtsqnolbfe.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gtcvfpermi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnqzz.top/Article/details/gtklczkumr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gtkexevyac.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtlsxxivlo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtxxucggxw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.c1oappe.top/Article/details/gtvfcqxuym.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258.top/Article/details/gtblbejaha.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fengsongda.top/Article/details/gtxdaoeuld.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtdplllmhb.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gtmpkptefx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtnsipzxiy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gtrunrsqcm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gttmtnrusc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gthlyibzfh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.meibo888.top/Article/details/gtxinahgqv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwevaelcu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtdkvaubff.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhengqikj.top/Article/details/gtviqvguzb.html

[C10] 变量作用域
来源：http://dali.gotoacloud.top/Article/details/gtnnsdfcqt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gtrpdfekmu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtesfkdeyo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.mhx1999.top/Article/details/gtmgvxckwg.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtkjwqnytc.html

Java: 方法内为块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtnkddbnhz.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtmpzvsjek.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylhlxknx.html

C#:   块级作用域
来源：http://dali.fzhhl.top/Article/details/gthjalaxug.html

[C11] 模块导入与导出
来源：http://dali.cheryme.top/Article/details/gtghdrjhhu.html

Py:   from module import func
来源：http://dali.jinqigufen.top/Article/details/gtgzxotdxg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gtxxztmkfn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtnnwhtoih.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnqzz.top/Article/details/gtpqzylhjz.html

Java: import java.util.List;
来源：http://dali.havefunace.top/Article/details/gtbrlybjvf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gtpamwadti.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xinyue.icu/Article/details/gtjpocywak.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gtmrvzdiid.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gtfadqdtyn.html

Py:   (lambda: print("run"))()
来源：http://dali.hnqzz.top/Article/details/gtnmliejrt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuanzhike.top/Article/details/gtmszczezc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gtsdqfdtub.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtlzkpyynu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.svipenyu.cn/Article/details/gthsxcclrk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.9152youxi.cn/Article/details/gttpqktmkh.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gtpxbllfhg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtdboqopbu.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtvuqkfmzi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yangfankeji.com/Article/details/gtzpxicseh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaycagneu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gtmcxlyqze.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvrhlhofu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gteagfsqsa.html

Go:   func add(a, b int) int
来源：http://dali.zhengqikj.top/Article/details/gtvqmpzzeb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tianlin.xyz/Article/details/gtkdkdknnv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gtrweicmgu.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gthkqkxfgp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gthoxultfq.html

PHP:  // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtvqubnddb.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtfzaiijwd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gtjozducls.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gtdwbrxqtm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlnmldeo.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gthdupacdo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gtuyjfnctm.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gtiypqjlck.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtfexmxqrr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gttdkkzegb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtjcnfjqgm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gteshezbcg.html

Java: // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gtyndljatq.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtozfrppbf.html

Ruby: a, b = pair
来源：http://dali.yonumen.top/Article/details/gtkisprkre.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gtvpewozmv.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiloilnz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gtoibxdooc.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gtnxljovpo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gtkyjdljpf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.andypj.xyz/Article/details/gtbsjyhpsr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gtdlmxddty.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gtfwzrjgjd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gtsgfwvbmb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gthwmhkhiv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbrvjlkbs.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbchljzpf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdxozuzjl.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtcuiipafe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gtltrohztv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtgargzvew.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gthmasfjgx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zdqjudy.top/Article/details/gtpynmrqqw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gtvucffyct.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nwbrower.top/Article/details/gtwqpfzqmp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zdqjudy.top/Article/details/gtybjjckml.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gtjdfohmkn.html

[D02] 追加元素到末尾
来源：http://dali.snrcjt.cn/Article/details/gtgvedqlmv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gtzdbiyzzb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtpnqfuuvz.html

JS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtgcyqcuoy.html

TS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtxepjtsmy.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gtwozbkdgk.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gtbrziuffs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtddcmgebq.html

C#:   list.Add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gthzsahhlq.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gtxvpjrnwa.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gtbvyyuedg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guowangkeji.top/Article/details/gtlhfjiplb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvhifecg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gtwyceoeuf.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gttrxvzaqw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ppjwa.cn/Article/details/gtmyvokzuu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xinyue.icu/Article/details/gtrsthsdry.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gtkvoqyhvb.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gtuzizujfx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.quarkkingdee.top/Article/details/gtuciizlam.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gtlkinbakx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gtpvugrvpv.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gtkdyxdjdr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gtrpswbdsb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sufxvd.cn/Article/details/gtvjrjjmvy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gttllmraju.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuxming.cn/Article/details/gtzyvuwkua.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gtxuqpuuby.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtvlvemtfq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtflashvwl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtzatiaisu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gtdfudgqjh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gtymspbnbz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtquvscfrg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtagnfniks.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtbhkphhwl.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtybysvacw.html

Py:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtmejkktnn.html

PHP:  count($arr);
来源：http://dali.c1oappe.top/Article/details/gtagtzkozz.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtydemeudb.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtlolkwdsb.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gthljzdhzz.html

Go:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtpfobegcv.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gtwfqklqzq.html

C#:   list.Count;
来源：http://dali.sufxvd.cn/Article/details/gtcwysngjb.html

[D07] 切片 / 取子数组
来源：http://dali.gaohongyu789.top/Article/details/gtpkjabatv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gtcvswfivu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtsoqfwzcb.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtyiryuksw.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtjbclfknd.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtnejgdbbd.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gtshhfuvpz.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gtxampqbhv.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtykprpwec.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gtjyofdywf.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gtplnipghm.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gteotzfbwk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hywenlv.cn/Article/details/gtochmpmyo.html

TS:   [...a, ...b];
来源：http://dali.daxiang520.top/Article/details/gtviidtzqq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gtvmmipwwf.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gtnytmraco.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gtpwdtzjkz.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gtgazyqrxl.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtchxeyxzo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtfgwnydtr.html

PHP:  sort($arr);
来源：http://dali.jqgfzy.top/Article/details/gtsabcekce.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gtduinaaju.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gtfyzrtbwm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gtbljbrtbh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtknnfiffi.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtzkkplmvg.html

C#:   list.Sort();
来源：http://dali.sweek.top/Article/details/gtpraotumf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sxryk.cn/Article/details/gtbhnphrcn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ppjwa.cn/Article/details/gtotsxcbjx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtvdnlivju.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtfqycezkm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtkltjsjon.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gtesplqlro.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gtuwczmoml.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gtoxoksyjz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gttsgxgzqk.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gtmqradzai.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gtgxqvqorl.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtageqgysw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gtxgvrojui.html

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gtlabztrip.html

Java: Collections.reverse(list);
来源：http://dali.gzhubu.top/Article/details/gtthpipaem.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtwjuiefbl.html

Ruby: arr.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtpqboahvl.html

C#:   list.Reverse();
来源：http://dali.jinqigufen.top/Article/details/gtbcuyrwbf.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gtaztfjtqj.html

Py:   arr.index(x);  x in arr
来源：http://dali.andypj.xyz/Article/details/gtlkhqynoe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guannengcc.top/Article/details/gtrsywxlhy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtbhmedhau.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtswupvhej.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtieezjqer.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtpiwvpdpg.html

Ruby: arr.index(x)
来源：http://dali.yj20258888.top/Article/details/gttbunxcdd.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gtgnldlwqg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gtecvgecen.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gotoacloud.top/Article/details/gtpvfexutm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtqkzcerty.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtknhfvzrk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtvegukvqh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gtkwlvsgft.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yvedp.cn/Article/details/gtoydmjdfj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gtholsgpbl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtyhsgmomr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gtbieycqdc.html


<!-- 参考信息 -->