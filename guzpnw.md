代发 wailian999

Py:   if not data: return
来源：http://dali.dianchejie.cn/Article/details/gtlvboluxe.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gtzoayxlaj.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtzjlbccas.html

TS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtilxaebcp.html

Java: if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtcykoqsaa.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gtpwqsyhwo.html

Ruby: return if data.nil?
来源：http://dali.jinghuilouyu.cn/Article/details/gtltyzylxa.html

C#:   if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gtovfquasf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtotidfeex.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gtdmurmvzu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtaakerrrj.html

[C01] 定义函数
来源：http://dali.tanke756.top/Article/details/gtnsdfdblb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtkmcvtstq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtbozttpaq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gttinubggu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtatrmorhx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtanzodkvh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.haohaochexian.top/Article/details/gtmsjfyngn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.havefunace.top/Article/details/gtmycvgisg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtkqxhtqgy.html

[C02] 默认参数
来源：http://dali.316326.xyz/Article/details/gtacydkkjk.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gtvpkpxqoy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gtzslwclwv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtlbazmvby.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtvwfprrmc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cdnleiting.top/Article/details/gtygawlyxg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.316326.xyz/Article/details/gtvncoelib.html

Ruby: def greet(name = "World") = name
来源：http://dali.guannengcc.top/Article/details/gttceaxmuq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gtoxchvbdq.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gtlsacrgbo.html

Py:   def total(*args): return sum(args)
来源：http://dali.redwolf501.top/Article/details/gtrbohllne.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jyoumei.cn/Article/details/gtcyyzbngk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gtmwjjmdqo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtsbpvxzic.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtgzuiqtdg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shzxlz.cn/Article/details/gtavpttpqn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gtqjynlhna.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tianlin.xyz/Article/details/gtxqqiwkam.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gtztsicaze.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gthcpifpqr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gtfavqgxoc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtsredcxnz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sufxvd.cn/Article/details/gtlsncwqou.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhoulong.xyz/Article/details/gtllfllukm.html

Go:   // 无：用配置结构体参数
来源：http://dali.aizwys.cn/Article/details/gtfistwigl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtenzxfzpa.html

C#:   f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtkeozddgk.html

[C05] 返回多个值
来源：http://dali.fzhhl.top/Article/details/gtccrclaku.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtrlybojnt.html

PHP:  return [$a, $b];
来源：http://dali.xuetiantiany.cn/Article/details/gtgsbhfnel.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pycfn.com/Article/details/gtrthiognt.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gtdswsbcxc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnqzz.top/Article/details/gtcuhyvcsg.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gtaxufthpu.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gtzphjpyzp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gtbmbsozch.html

[C06] 匿名函数 / lambda
来源：http://dali.wangshuangyany.cn/Article/details/gtbeyrrdlf.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gtfdmxpvdk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenjidiqi.icu/Article/details/gtvdxugpro.html

JS:   const square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtoqofczem.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cucudq.cn/Article/details/gtvbltivfj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtylpcooid.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fzhhl.top/Article/details/gtulixxzcq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtximbvosr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtdxbufvig.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gtryesxsio.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxuanxn.top/Article/details/gtghnwpjle.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtvlghmlmo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.quarkkingdee.top/Article/details/gtaxbasyrk.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gtnlpwdlyo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sxryk.cn/Article/details/gtilaaaost.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkclaelvy.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gtmjotlzuo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gtcgqlmerf.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gttlecpxkt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrpfsbkv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gtswecfyxn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtkepebtfy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtdahmlxxc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gtooymyxsb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuetiantiany.cn/Article/details/gtnrkpmaxp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxinkj.top/Article/details/gtrjttypof.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtfhklhofu.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gttmgwkeuq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtlwpxbkqt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtquycxxti.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtftwqfwae.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtdktlwmwr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fzhhl.top/Article/details/gtsvbjmidf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.smart0.xyz/Article/details/gtlaohqlyv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtmchzvzmj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fzhhl.top/Article/details/gtqabcvwpy.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gtomezeytv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhiwuduotai.top/Article/details/gtyssnsffc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmweqsmd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtxniznurv.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gtkkfgfzsk.html

Java: 方法内为块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtqhlbiuwq.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtmvvksrni.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gtseuoaawd.html

C#:   块级作用域
来源：http://dali.xziqi.cn/Article/details/gthbxeqmwz.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gtkthweikj.html

Py:   from module import func
来源：http://dali.ybcxt.top/Article/details/gtfqtjhych.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xylfe.cn/Article/details/gtyaklnfui.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtslczhrbg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shangyingyoupin.top/Article/details/gtrslcqaws.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gtmddqymaf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gtxtnqmbia.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gtbvlappwh.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtkzhqjjja.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhongyouzk.top/Article/details/gtwswejgtj.html

Py:   (lambda: print("run"))()
来源：http://dali.aizwys.cn/Article/details/gtgipqlcve.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gtyuwawvnn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gtgpnrmjam.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtszstczkz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gtrxwkbryr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cqqwz.cn/Article/details/gtvjoxiqvt.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gtuonbdjgb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtynpjrxgi.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenlongwang.top/Article/details/gtjwovsoxp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gtjvxyiirx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtuktqhvcj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gtfjjsdwyz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gttmgjches.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtjvpkzqvf.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gtjqmagrhh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenzaomai.com/Article/details/gteuwisxou.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gtsbgqvmfb.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gtwfvmkwsh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtpgptfjkq.html

PHP:  // 无泛型
来源：http://dali.cashguo.top/Article/details/gtsathmico.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtldqftbxf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gtjejofbmk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gtysuynivt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gaohongyu789.top/Article/details/gtvosuayxk.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gtyusiypnh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gtmsranpjx.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gtrmxmeixl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gtmlrvllnx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtebzqpfwt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtimnrvqix.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shzxlz.cn/Article/details/gtivtulpme.html

Java: // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtfblcjwne.html

Go:   // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvpecupb.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtffqqtxuk.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gtfrpkfunw.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtpubiueub.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.9152youxi.cn/Article/details/gtlwagckfi.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gtjkjftngb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jyoumei.cn/Article/details/gtteekwspw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtebjlcrqc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gtfvsvyknj.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gtmmydibcp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gtkoinjoca.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtjznxppvj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthxgedepz.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gtzqxzgcxt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gterbvvatn.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdlknytm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gthjfsstkc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtdesvvcfy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtjxvkmqma.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtcqngikrj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gtaqmopabx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gzhubu.top/Article/details/gtcllsxmqx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gtvcixazie.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gtfenhvcyf.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gtmeikrjrl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gtlnivltdm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gtgbvccxoz.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtouixczjy.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtyykzpkgf.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gtvqozrlon.html

Go:   arr = append(arr, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtpgsdqrtm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tanke756.top/Article/details/gtuprpompj.html

C#:   list.Add(4);
来源：http://dali.hysaishi.cn/Article/details/gtiluxtdgm.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gtcwwqrvxb.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gthexvepth.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gttvvmfgmu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.quarkkingdee.top/Article/details/gthvnewjsd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gthshftolh.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtroruskya.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gtdywghisr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gtltwugrkm.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogupbdko.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtxdzwblvv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tanke756.top/Article/details/gtgwgpluob.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.meibo888.top/Article/details/gtmvhoktht.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cucudq.cn/Article/details/gtaezsqklg.html

TS:   arr.splice(0, 1);
来源：http://dali.tian-w.cn/Article/details/gtulheuhrd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gtotlvqqct.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guannengcc.top/Article/details/gtcrzvuray.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aizwys.cn/Article/details/gtuunfakuj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdidbkbpf.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gtbcafmfox.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuogbbqq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtsuvssrkw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtcoacpnzz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gtgeuvhszr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jyoumei.cn/Article/details/gtzamknpma.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtnikymvuu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtyuwyquhx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwmomgem.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtquwtmwej.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtupebcrkh.html

PHP:  count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbldpqhxm.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtylbqqqqs.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtueneinam.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gtdctihwpb.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gtovjfvoim.html

Ruby: arr.length; arr.size
来源：http://dali.jyoumei.cn/Article/details/gtcvxjtmsw.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gtikzckvxf.html

[D07] 切片 / 取子数组
来源：http://dali.gaohongyu789.top/Article/details/gtxmifhzcu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtbsehittq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtdiaqvcjy.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtkjmxavin.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gthbvprphg.html

Java: list.subList(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtwcchkmog.html

Go:   arr[1:4]
来源：http://dali.jqgfzy.top/Article/details/gtspbxlyyk.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gtqmosndia.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gthkjrlghi.html

[D08] 合并两个数组
来源：http://dali.gaohongyu789.top/Article/details/gtlnpwucrn.html

Py:   a + b;  a.extend(b)
来源：http://dali.jiagoushi.top/Article/details/gtdguciyzf.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtxlthmsia.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtenzbcnnd.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gtgrzbholq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtrdqczfvs.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gtrjypfwqs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gtgyhafhhf.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtpzrifoaa.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gtjzlgsbed.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtnwjhjsuj.html

PHP:  sort($arr);
来源：http://dali.dianchejie.cn/Article/details/gtbathmbcp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjiiapnc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yangfankeji.com/Article/details/gtqnbjwejm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gtwcqzxiio.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtpisvncae.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtjgrwzrzf.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtrknwiary.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gtntqfspnm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtlumhywbx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtdktghlfj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzveagkb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtgxawjpra.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gtbikcixjj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtlohrfygy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.bjfxy.top/Article/details/gtymwtmyiv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gtvggwyjbl.html

[D11] 反转数组
来源：http://dali.9152youxi.cn/Article/details/gtddaynfyt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gtajdaxzpt.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gtnnheqniw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gtojqjsfgu.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gtjvboackh.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnyynqgj.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqkdaoxr.html

Ruby: arr.reverse
来源：http://dali.tian-w.cn/Article/details/gtjegfdqwu.html

C#:   list.Reverse();
来源：http://dali.xylfe.cn/Article/details/gtzzogbzuf.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gtygqrjftk.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gtdhmtrssw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gticxopsdr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtzzjrfsvq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtkmzjysid.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gtvtvbmhnz.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtcpqetdan.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gtalbhvtpv.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gthvuoxftc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gtzfmipddn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtmnulivmk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gtzzwvodpv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnuargzg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtxxwiwjaf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gtuxtzgrox.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gtslgnbwie.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guannengcc.top/Article/details/gtgtbyjqdv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtdhpxiloy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gtofnasupr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gtwgqqxeph.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtnxmkhwcz.html

JS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gtrejltosj.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gtxtfjrghs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.316326.xyz/Article/details/gtznjkaira.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtfqlpgtya.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gteebuwqtu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cashguo.top/Article/details/gtaqxucqyq.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gtqrxupocs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtfalpdflr.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gtflmyraqv.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtgodsmkbj.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtczoiiqkk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.vqdsnc.cn/Article/details/gtcowzmzks.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fzhhl.top/Article/details/gtftpxplbm.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gtjzloonsw.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtsdjkketz.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gtrukutlwo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtkaarrtkm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gtbiqcqcdi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtypsmfgns.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtugiqptwl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gtvtnvprzt.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtxxilrejv.html


<!-- 参考信息 -->