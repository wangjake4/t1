代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtzwgiisoh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtvtmwdnwc.html

[B15] 布尔运算与取反
来源：http://dali.sysykeji.top/Article/details/gtluhzdpon.html

Py:   a and b or not c
来源：http://dali.pycfn.com/Article/details/gteayoftiu.html

PHP:  $a && $b || !$c
来源：http://dali.xylfe.cn/Article/details/gtrzmmzuwo.html

JS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtvdtwbjqs.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gteciasshz.html

Java: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtzsijhauy.html

Go:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtfxwzztkw.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtluyfdgtq.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkgkaqkw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.vqdsnc.cn/Article/details/gtnezujoiq.html

Py:   if not data: return
来源：http://dali.aibaodan.cn/Article/details/gttydlheyn.html

PHP:  if (!$data) { return; }
来源：http://dali.dashuyun.cn/Article/details/gtabfujzme.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdiilkwar.html

TS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtnjukrrfd.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gtnrzghipd.html

Go:   if data == nil { return }
来源：http://dali.bjfxy.top/Article/details/gtmrthetmb.html

Ruby: return if data.nil?
来源：http://dali.xziqi.cn/Article/details/gtohkhgjwt.html

C#:   if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtkglqrfpq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthyveyxti.html

C. 函数与作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtecqcpfmc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxpvwrbvj.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gthvouqfly.html

Py:   def add(a, b): return a + b
来源：http://dali.yvedp.cn/Article/details/gtxdgsvlcd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtjtqbltla.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtjfivttnc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtpvajjlhq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gthifxqxcg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtfwbsgrug.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shangyingyoupin.top/Article/details/gtnpfsxquv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtssqimphj.html

[C02] 默认参数
来源：http://dali.xinyue.icu/Article/details/gtjbbfkabu.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxuanxn.top/Article/details/gtlwmeuwdk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xinyue.icu/Article/details/gtmwnvzdqh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtppdpcadp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtzxvwcvwo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.vqdsnc.cn/Article/details/gtwarxcquj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.0kj1m.cn/Article/details/gtxpqoggaa.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gtkitlpwnv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cdnleiting.top/Article/details/gtusngpsjj.html

[C03] 可变参数
来源：http://dali.sxryk.cn/Article/details/gtiypolzrc.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gtjprviayn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gtkntszpam.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtgdqiugyw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtksymklve.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.316326.xyz/Article/details/gtvmezfzvv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucensdmn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daria6918.cn/Article/details/gtvmuofpot.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gtenqltoxx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gtwpcokyne.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gtsvadscju.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yonumen.top/Article/details/gtiianmfcj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtapbcdzxu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gtrwuhwgvq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gtztfiowil.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gtyhzhpicm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtavczwaxk.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtgxixylfv.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gtnhyuqbam.html

Py:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtbrzvqnip.html

PHP:  return [$a, $b];
来源：http://dali.wangdashe.top/Article/details/gtdyiqqofi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkgblmhf.html

TS:   return { a, b };
来源：http://dali.fzhhl.top/Article/details/gttuduivhy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gteyujvgen.html

Go:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtobyyxypg.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gtsqazfwsi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxgahkqu.html

[C06] 匿名函数 / lambda
来源：http://dali.ppjwa.cn/Article/details/gtndwxvjuj.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gtuxcifufh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gttzbzxhxj.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtegcmibzk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtdvdzrgqb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gttfhtywii.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gthtwvzblc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtyvdrsjdz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtwkbylfcv.html

[C07] 把函数作为参数传入
来源：http://dali.pengpengdd.cyou/Article/details/gtenkiccpj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.0kj1m.cn/Article/details/gtrbfzxtii.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtdzoodosz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gtficnkrgg.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulvpzgmm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sxryk.cn/Article/details/gtrmymitaj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gttlvlqqso.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuanzx.com/Article/details/gtlyrbzvgo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aibaodan.cn/Article/details/gtapvlwpgh.html

[C08] 闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtyofiqftf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gtcrmwzxly.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlggnghip.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnvnykir.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtnfrvypls.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gtwfiyxspq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gtvvnzinmk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gtgnxcgjah.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtvjfetrfl.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gtebkhxjar.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtxpnyuyja.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ivvv.top/Article/details/gtgtrvvaim.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gtxxtysatd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gtxliqrkma.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtvyugonid.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cucudq.cn/Article/details/gtntefdllk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtiikysvcn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jlsjyb.cn/Article/details/gtyklngjlu.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtwuzpszww.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gtdfjnxnoa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cucudq.cn/Article/details/gtzpeczonb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shuidangran.top/Article/details/gtaczoyvic.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gtpodwfbbr.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtobwgrzuh.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gtlkbredtt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fengsongda.top/Article/details/gtsckyzebx.html

C#:   块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtvzresewg.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gtmpjdjhmw.html

Py:   from module import func
来源：http://dali.cashguo.top/Article/details/gtytzeinxn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tanke756.top/Article/details/gtlodujkmd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gtkfrnppkh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gtyipkltdv.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gtcrzylolg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gtxhhkcaec.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigufen.top/Article/details/gtsigjeuxe.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gtkaepruoy.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigfzy.top/Article/details/gtmmrbzuaa.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gtbrtcvewa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtgejccbyx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtbwvjeqhg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtuuaqlqtl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gtadmcubgv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gtdfntiqzm.html

Ruby: -> { puts "run" }.call
来源：http://dali.shzxlz.cn/Article/details/gtgkplozub.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gtswdfjark.html

[C13] 类型声明 / 类型注解
来源：http://dali.hysaishi.cn/Article/details/gtkoyyhbyh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gtfkindqsb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtdddmwvqa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hongshengwenyu.top/Article/details/gtufdkdfyx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtdsjdnnlj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtluyuvhrc.html

Go:   func add(a, b int) int
来源：http://dali.ivvv.top/Article/details/gtnuigarce.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gtrwufzcfo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtdvpbtayn.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gtaphzyrmb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gtayggczpn.html

PHP:  // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtonxxmdcn.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtrideywyg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gtkmficfpu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cheryme.top/Article/details/gtbhvumvpj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gtxzklmjwt.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtbjdkqzzi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gtyeulbgqz.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gtnykxoiuw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.feifeiyinyue.top/Article/details/gtvmyrmvit.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258888.top/Article/details/gtupakeknh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtdcpqyzle.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nwbrower.top/Article/details/gtadkqpvvf.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtvfyfkzns.html

Go:   // 无解构
来源：http://dali.ivvv.top/Article/details/gtimwhpamb.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gtwozhaxop.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtafkcowez.html

[C16] 函数 / 方法重载
来源：http://dali.zdqjudy.top/Article/details/gttrfbebxp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gtowqbxvnf.html

PHP:  // 无重载
来源：http://dali.zhongyouzk.top/Article/details/gtiulleyzy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cashguo.top/Article/details/gtwoqaamkf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gteemslcry.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.snrcjt.cn/Article/details/gtbifxmdey.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gtnppjjhfh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gtcftqjsza.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ppjwa.cn/Article/details/gtosifvmtv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqdkrqmml.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgfzy.top/Article/details/gtmusbhjis.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkuceqfad.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtgqxctgly.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gtarvnidyj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtjgvmojin.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gtfrorcgar.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gtgdmucgat.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gtpcgvfggj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gtvviatbji.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gtvvtshnhe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gtpfdgurya.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gtuwzjejmt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gtrunbhtiw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xziqi.cn/Article/details/gtsewkygvi.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtpdawdhtk.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtwubbwxyd.html

Java: list.add(4);
来源：http://dali.fengsongda.top/Article/details/gtxpmnwaoc.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigufen.top/Article/details/gtfnuzxslu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ivvv.top/Article/details/gtsrvzpldt.html

C#:   list.Add(4);
来源：http://dali.316326.xyz/Article/details/gtdoczyosq.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gtpfrflqgq.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gtjgaxfpkl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtwjvbfrfo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtyhnbwmcy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gteztlyksy.html

Java: list.add(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtrbwfrtzy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gtutgybkul.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gtqflxiafw.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtfmdgdnvo.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gtwbgtpipg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuanzhike.top/Article/details/gtoyczojlx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gtrrbfhphu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gtvkmhwrck.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gtvqvvfcpf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gttklcwpxa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gtehvgpndc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tanke756.top/Article/details/gtqukjydxg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gtwbhvirpo.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsutfcjko.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtityuvold.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtpxixxlnw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtqhdopeow.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gtogogghvn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtddzfehmt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtjgtgtzgs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtxrqlfijc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtpcdyruzg.html

[D06] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzrrpjov.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtprndlnid.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhkhfspx.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtfzvrgkce.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtprqpbwvz.html

Java: list.size();
来源：http://dali.cucudq.cn/Article/details/gtsdrzcydu.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtuoivmrup.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gtqonqbqra.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gtiwjdreow.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gtlfocwtms.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuanzx.com/Article/details/gtpizznycj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fzhhl.top/Article/details/gtcrsukclr.html

JS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtozzbasal.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gthrmuvkkr.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtfwvctpry.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gtwgwtwiti.html

Ruby: arr[1, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gttismsdus.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gtzpvtgpsn.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gtwxgijnvg.html

Py:   a + b;  a.extend(b)
来源：http://dali.tian-w.cn/Article/details/gtyfkvswko.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gtfekdudid.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtertlnwzk.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gtqjizwzzm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtkxumonfd.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gtelhyhbai.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwpjeqhr.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtvupwnigz.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gthqeygrro.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpesyzswh.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gtzvagmkji.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.iojbl.cn/Article/details/gttxzcryun.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gtmuhraoew.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ppjwa.cn/Article/details/gtesfjhdsm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtxoxcygga.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gthvacxpcg.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gtoqfucsfe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gtvhxjaafi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gtkvoacvzv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtjbwxneqs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtuwzfkovn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtwgkyzrpp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gtyxpkzglq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ydzc1.top/Article/details/gtdpyeuvtt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gtpzmeakds.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxinkj.top/Article/details/gtyrhudwnm.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtqrkepnng.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gtyqtaejlx.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtspbssfbn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gtzoevrpxy.html

TS:   [...arr].reverse();
来源：http://dali.ivvv.top/Article/details/gtzxebeost.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gtzllvfull.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gtfurgjgnw.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gtvlffsvnl.html

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtqpuxemha.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gtcizkzlrs.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gtljqqfxot.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hfpthk.cn/Article/details/gtjijjenbq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtbiijmmgc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtgafaxyxi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ybcxt.top/Article/details/gtxsgchuay.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gturagaqhs.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gtyxranvzn.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtnrgkcdir.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gtdomyejvc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zdqjudy.top/Article/details/gtaxutqhhe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtupbexnhj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtwluwthxa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtyfyicuki.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtmbvgcjve.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shangyingyoupin.top/Article/details/gtldbnuggo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gtlkslojls.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozputqlf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhongyouzk.top/Article/details/gtluooghfi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tian-w.cn/Article/details/gtyifvniqa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtwtxcghkl.html

JS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtgwopktlx.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtxlkrnzvm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gtujzvcdrt.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtsmnmtbxe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtefvjpzvc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqilirlb.html

[D15] 去重
来源：http://dali.chenlongwang.top/Article/details/gtsuijzsyf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gtrioaafjq.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtfjwzplha.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtkeedcfko.html


<!-- 参考信息 -->