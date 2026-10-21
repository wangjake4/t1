代发 wailian999

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gtmvudyglf.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gtzraekhwp.html

JS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtuymtgtmt.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtctetgxif.html

Java: if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmslcakb.html

Go:   if data == nil { return }
来源：http://dali.ybcxt.top/Article/details/gtxmkqwdkf.html

Ruby: return if data.nil?
来源：http://dali.xinyue.icu/Article/details/gttkuhztzf.html

C#:   if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtbiwfgffb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtgflndhhy.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gtcyfgfjtl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdbmxiqgm.html

[C01] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmhjuzvu.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gtztkkdxwo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtgcegdakp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtwdpmzuvs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpfbqndyq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtaaktesqb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.bjfxy.top/Article/details/gtygpnxxlk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtswecpdbc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtexeuwnmf.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gttabcepte.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gtagolquqi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhongyouzk.top/Article/details/gttrmteskr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gtaylnfllt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gteevfnexr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gtszgzhibm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibwhanmq.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gtxqcqqrip.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gtobqyxzbk.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gtxubuiktd.html

Py:   def total(*args): return sum(args)
来源：http://dali.gaohongyu789.top/Article/details/gttdzephbb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.birdmap.top/Article/details/gtcyemojjm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtzlwcjxbg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gtujcdjbmj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgfzy.top/Article/details/gtqxbjrthw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gtzpeokzfp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hysaishi.cn/Article/details/gtvxseptlj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.quarkkingdee.top/Article/details/gthfmzawxj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hongshengwenyu.top/Article/details/gtxpziioie.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gtplfadfya.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jianghu66.top/Article/details/gthrxaeyog.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtfcmvzgvp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daxiang520.top/Article/details/gtiuaxwefs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fzhhl.top/Article/details/gthsmcxwpy.html

Go:   // 无：用配置结构体参数
来源：http://dali.xinyue.icu/Article/details/gteaooznzf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtkxztcouj.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtewirkmoe.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gteowrznaj.html

Py:   return a, b
来源：http://dali.yonumen.top/Article/details/gtnjaeaive.html

PHP:  return [$a, $b];
来源：http://dali.wangdashe.top/Article/details/gtshekhzyj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gthbdjsztp.html

TS:   return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllrjqssn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gtuoouyflg.html

Go:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtbhrmyjhx.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gthdrxbqua.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yanxiufei.cn/Article/details/gtetpunqfp.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gtfegykrkh.html

Py:   square = lambda x: x * x
来源：http://dali.yuanzhike.top/Article/details/gtbkzenhhh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtlskwbakk.html

JS:   const square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtvzauosyy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtehleowuv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daxiang520.top/Article/details/gttrhmsrgd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gtuuqnihcs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtqpebhudz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gthrrimmya.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkutiihs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gtyebapccj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gthmbaphox.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gtwyrjrcby.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gtlnosrdir.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhengqikj.top/Article/details/gtpnlpymob.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gtdllszuag.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtivblrjab.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gtgupizsxl.html

[C08] 闭包
来源：http://dali.gaohongyu789.top/Article/details/gtsymyvvwr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fzhhl.top/Article/details/gtwvtcxgca.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.vqdsnc.cn/Article/details/gticyrutyy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtgqnpijtn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtseywnaaz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gtoorslcon.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zycfv.cn/Article/details/gtdxwjbjqg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cheryme.top/Article/details/gthravcvry.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtebdtcsht.html

[C09] 递归
来源：http://dali.andypj.xyz/Article/details/gtjixndvkj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gttyspkfea.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtnamwlvii.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gtrvscmily.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtzkkulret.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtiannkzun.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gtylyryoox.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gttaokegys.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dianchejie.cn/Article/details/gtuzyucwtz.html

[C10] 变量作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvmrhtwh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gtfombhibb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtciqldtph.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xylfe.cn/Article/details/gtmoysdepp.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gtylgxixap.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gtwcpwbxds.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtcehxcpfh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ybcxt.top/Article/details/gtuvqtiyzt.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtoeytujoh.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gtmiygccbk.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gttgtwbbui.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gtsdwbgktw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gtwuoqukyb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gtzlxispzj.html

Java: import java.util.List;
来源：http://dali.xziqi.cn/Article/details/gtvhycxsbn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtnigqnqvq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gtuxuoqvdv.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gtfrdagzry.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gtlasqdivy.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gtxjeipale.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwxuxhor.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gthahcaxef.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtykyfarlz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gtrmgjedis.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gtbqtngcsr.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gtozshtijp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gthbvemsvf.html

[C13] 类型声明 / 类型注解
来源：http://dali.zycfv.cn/Article/details/gtaiflvfou.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gtssjnndbb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtgckuagdo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gtywsjtoyy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtvebkurrx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtpqlkjqjz.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gtnjlvtvus.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gtbwqotejr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqaibwbry.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gtvpgnhhfi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sysykeji.top/Article/details/gtauywlfoe.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtdhpkmvqq.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtxehuysak.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gtxitkwlrl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbnhgnmf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gtddyadiss.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gtuakyzkwi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gtowkuvafl.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gterwfhiuu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gtbcjmwtne.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hammf.cn/Article/details/gtgsdrespj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtkjihgpfj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gttcmodbga.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtxjerxuav.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gtimvudsvx.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gtqgspapif.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gtlewlrttg.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gtzqxcjxkj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gtumdewtjb.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gtavaelijf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gtxbfxtfxq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gogol.net.cn/Article/details/gtrkeeuvxr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtjauzotht.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxmeljxm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gtjvcquuxs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cdnleiting.top/Article/details/gtlpwjcuza.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfqokgfnp.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gtstnzzzfx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtavemeybn.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtiwvympyh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.snrcjt.cn/Article/details/gtkunktkrq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtoccyrahg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtqazuvenb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gtoshufhlm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gtubhslney.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gtnuovuvjr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258888.top/Article/details/gtlixxactl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gtiznhcnaz.html

[D02] 追加元素到末尾
来源：http://dali.yonumen.top/Article/details/gtxjasbqaa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fzhhl.top/Article/details/gtwftxvifl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gtahkgsrho.html

JS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtjvzocsgv.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtfwnmfelt.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gtzijeyeke.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzisfdrac.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxinkj.top/Article/details/gtyvugvsny.html

C#:   list.Add(4);
来源：http://dali.cashguo.top/Article/details/gtdeipgmww.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gtldaqijao.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtopmwewla.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zycfv.cn/Article/details/gtxiezvmpm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gtcbczkyke.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gtjlltekdz.html

Java: list.add(0, 0);
来源：http://dali.yj202588.top/Article/details/gtspwgpjgv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gtaekzfpvz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gthgavznva.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtpsnrhpux.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gttigrjwcq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daria6918.cn/Article/details/gtibzeidre.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xziqi.cn/Article/details/gtrorbmpkb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aizwys.cn/Article/details/gtqlcmtmyi.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtbypjnvne.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gtatcqutnc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gttzgskbho.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtwqzdkaad.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zycfv.cn/Article/details/gtussxwrdi.html

[D05] 访问与修改元素
来源：http://dali.jlsjyb.cn/Article/details/gtvhiyqebm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtzctflapm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gttvjuuzeg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoarzoka.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gtsojogtef.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xziqi.cn/Article/details/gtdxiuxjqm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtrcvvlteh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtdrkmautc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtmnsdcvij.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtaoucggor.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtkpdjblpi.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gtpujwnuoj.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gthioyjvba.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtnhdjijsv.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvgdinzk.html

Go:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtjicirxmr.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gthtcaguee.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gtrjhbeaam.html

[D07] 切片 / 取子数组
来源：http://dali.0kj1m.cn/Article/details/gtrfvbctzx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gtkhjagpgi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtzxxupmtm.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtirxjyqog.html

TS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtxpvwztge.html

Java: list.subList(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtstbpfxtf.html

Go:   arr[1:4]
来源：http://dali.jianghu66.top/Article/details/gtfyynkcow.html

Ruby: arr[1, 3]
来源：http://dali.jqgfzy.top/Article/details/gtlqpeporf.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtnzizrxgb.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gtownwtkzl.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtzvftmytt.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gtodazjlpb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gtnomozbaz.html

TS:   [...a, ...b];
来源：http://dali.hfpthk.cn/Article/details/gtqyzgyajs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gteaouqjpc.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gtetawzqbg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gtoobqxzsx.html

C#:   a.Concat(b).ToList()
来源：http://dali.yueranfly.top/Article/details/gtmevbekon.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gtjzcmvdnk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gturobpucy.html

PHP:  sort($arr);
来源：http://dali.zycfv.cn/Article/details/gttckrmles.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtawjvgzzx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gtfxglptze.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gtlgrwoali.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtbdneqgbs.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gthvawmkri.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gtdndinpdt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gtiriroert.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guannengcc.top/Article/details/gtzbfkkztr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gtzornvikg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtpjmvrsbv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gtaktqgwqo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gtgjyofaik.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.bjfxy.top/Article/details/gtftvqhaij.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtzjaivwzs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyhakdyp.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtcsrtpgcg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gtnlkbhcyb.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gtimwytszr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtqbpgmzqs.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvwxduju.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtbnnosxys.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gtugmsnrmu.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gtfbqbnpyu.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gtfxolycmb.html

[D12] 查找元素下标
来源：http://dali.ehwqpu.com/Article/details/gtynhwwyhk.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gtxwmukbkj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtzholxeio.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtubpaykux.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtaoztgcsn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gteejyxdis.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtrnaogogm.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gteuilavcw.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcczixykv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gtmzuuopep.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gtgcskkexr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gtzjdilfpb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtowwzcamo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gtesyqowhr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnqzz.top/Article/details/gtuymfkofu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gtiziazzht.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gtjyrzgdow.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtpjlapexj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.iojbl.cn/Article/details/gtylmaxvoc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gtqgatmley.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yueranfly.top/Article/details/gtzkkzzzfj.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtlauibhpu.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtypeuruap.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.havefunace.top/Article/details/gtgfizlhyr.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtavvrbfpr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtkoncqfex.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtclhnpant.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gtgqbgohuq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtjnblbzod.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtekrkekww.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtblykupeh.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtbdnkbkvv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gtkdckvrrs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gtuzpzhcwz.html

Ruby: arr.uniq
来源：http://dali.jqgufenzy.top/Article/details/gtjmjdketo.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtmbsxcvzv.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtogmrondp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtnfiygwwp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gtggzxfnhq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtnrbskgsb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtcridebpg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cucudq.cn/Article/details/gtvrfjezrf.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gtjwbxuhra.html


<!-- 参考信息 -->