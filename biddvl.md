代发 wailian999

Py:   if not data: return
来源：http://dali.fengsongda.top/Article/details/gtavxcbdsw.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorsrohtk.html

JS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtnuakqykb.html

TS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gtojuvcfja.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtbtaztvuu.html

Go:   if data == nil { return }
来源：http://dali.jiagoushi.top/Article/details/gtzdfulmku.html

Ruby: return if data.nil?
来源：http://dali.ppjwa.cn/Article/details/gtvqgmyjdz.html

C#:   if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtsayesnmd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtdntsnjvu.html

C. 函数与作用域
来源：http://dali.cqqwz.cn/Article/details/gtfppdhqns.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtzlfqxspo.html

[C01] 定义函数
来源：http://dali.pycfn.com/Article/details/gtvwcwepvg.html

Py:   def add(a, b): return a + b
来源：http://dali.yj202588.top/Article/details/gtsmiekwpi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtvybtwjzf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhykgzrt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtohrgjens.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtptftrnsu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gtsosvqayv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xylfe.cn/Article/details/gtxxlpailx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtrjgujlyp.html

[C02] 默认参数
来源：http://dali.tianlin.xyz/Article/details/gtuebxvvti.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgfzy.top/Article/details/gthavdllrz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gtnmztiopd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtmbzseyvr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtqjqnjije.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gtmwmjoprc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gtiiysywbs.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gtcupykvny.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gtaqcqzqwm.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gteaheentq.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gtleoioifk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gtsfttmann.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gtkcwflgno.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtsgudobip.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtbqtvmypz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gtyqpvboyw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gtwggbszte.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.c1oappe.top/Article/details/gtkfkpgqfq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gtkmwijbez.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gttxaygypd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ybcxt.top/Article/details/gtjrnrjuks.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtfkzzegzb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gtlaaurjue.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtuwqnhryl.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gtewkchthb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtqxcajypr.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtetsjtthm.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gtboivvbjw.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtglffbwcm.html

PHP:  return [$a, $b];
来源：http://dali.jinqigufen.top/Article/details/gtjpigsbmv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gtaibggrea.html

TS:   return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gtgzzleymd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cheryme.top/Article/details/gtwmbfndgo.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gtxarsylxh.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gtnnifdpyr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hongshengwenyu.top/Article/details/gttldwnxun.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdygnnqyx.html

Py:   square = lambda x: x * x
来源：http://dali.yvedp.cn/Article/details/gtxaawarpx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuxming.cn/Article/details/gtjxisqhxo.html

JS:   const square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtcdxwwkwh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.birdmap.top/Article/details/gtnfguvaxq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.iojbl.cn/Article/details/gtmjkjdbiz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fengsongda.top/Article/details/gtiohpjgqs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tianlin.xyz/Article/details/gtbcsynusl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtlyyiwdul.html

[C07] 把函数作为参数传入
来源：http://dali.guowangkeji.top/Article/details/gtwraismst.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gtqxsmtymo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjmffulq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gtrkpsyiye.html

TS:   arr.map(String)
来源：http://dali.ybcxt.top/Article/details/gtywxhzoby.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gtvmkqvmlh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gtnmcaoeqz.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gtzvalgwfe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gttdbncfab.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtqoxmngfe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gtctqlzpqb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkdvxiosl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthujoheue.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtyidnprrb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpqaincu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ppjwa.cn/Article/details/gtgirqutlm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gthgmtdwki.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtedvxhjxe.html

[C09] 递归
来源：http://dali.andypj.xyz/Article/details/gthddsjoub.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gtsezobtsu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fzhhl.top/Article/details/gttpjtofkq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtvtuukafp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctqnyxqv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258.top/Article/details/gtgfmrqccr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gtcnkzpueg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtzywpbrzq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangdashe.top/Article/details/gtbdnulljt.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gtwpoqjjrn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.meibo888.top/Article/details/gtyacyezjw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.birdmap.top/Article/details/gtwozfzpat.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtfhmfcsbo.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjrtndhy.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtljthsqyw.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gtyryniozn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gthbddcgvg.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtnqianciz.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gtreuldivz.html

Py:   from module import func
来源：http://dali.yuanzhike.top/Article/details/gtylgwmzuf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.andypj.xyz/Article/details/gtjilnkmbz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gtiujwrcwl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gtkmsjcihy.html

Java: import java.util.List;
来源：http://dali.daxiang520.top/Article/details/gtmizpyryp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gteeanehzt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gtyiugeqgl.html

C#:   using System.Text;
来源：http://dali.ivvv.top/Article/details/gtyiktfpfu.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduvpnoys.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gtdceuaumu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtjcfgboxo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtlwepgwwb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtqqmwogel.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gtugnehnvz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gtoaknbzae.html

Ruby: -> { puts "run" }.call
来源：http://dali.hywenlv.cn/Article/details/gtmutdidvd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gtodbkkkyv.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtevrhtydj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtthgqylbz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtbjfsmvnb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtruzlscjd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtoxtjvsxc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtadsnmoys.html

Go:   func add(a, b int) int
来源：http://dali.quarkkingdee.top/Article/details/gtuvsvqymv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gtismnveaa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtrpucyyig.html

[C14] 泛型函数
来源：http://dali.cucudq.cn/Article/details/gtmywjcnae.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gtukegjkdq.html

PHP:  // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtwepimcoo.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzhhndry.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.andypj.xyz/Article/details/gtoctgbumb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gtxuxlrluo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gthxisicir.html

Ruby: # 无泛型
来源：http://dali.hammf.cn/Article/details/gtmteupvwg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gtdwjkuakm.html

[C15] 解构 / 展开参数
来源：http://dali.chenlongwang.top/Article/details/gtqgcafdvw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gtofozfxfd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gtvgxmzohl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuniueykb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xylfe.cn/Article/details/gtanhuommk.html

Java: // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtixwlkwle.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gtmvhsgjgz.html

Ruby: a, b = pair
来源：http://dali.xziqi.cn/Article/details/gtnpclaghi.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gtounptglk.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gtzmdjhlik.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gtghvsdscx.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gtrfvgfihq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhengqikj.top/Article/details/gtlvqevncy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtyhdxjnrt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtgqmskwzn.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenzaomai.com/Article/details/gtdbyevegl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zycfv.cn/Article/details/gtdhyhxwkz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtuqgaryvf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkiuybwcd.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gtwvgiaixt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbxtwdhon.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtkafqhfav.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtrswpqqte.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtrtkmgukc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtzhviejcm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gtvblnhtjo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmsovgvm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sxryk.cn/Article/details/gtjegtndwh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtvojdbkpy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.c1oappe.top/Article/details/gtujlblope.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtwolkfrki.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gtdratrzfi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sweek.top/Article/details/gtlsvepidz.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gttowbcwss.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtnoqckaxx.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gtgbxruuxm.html

Go:   arr = append(arr, 4)
来源：http://dali.havefunace.top/Article/details/gtqgxrztnk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dianchejie.cn/Article/details/gtgasnmiih.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gtupytuhtm.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gtfdhralwj.html

Py:   arr.insert(0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtniqxyzjc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxffyolms.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gtoelfqxfl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhjpdojb.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gtkmdoddbk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqxkhmdl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdhyrrwu.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtxhbspgff.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gtwmcmctxp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cheryme.top/Article/details/gtwhcdlviv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.meibo888.top/Article/details/gtiwgwkdzk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.andypj.xyz/Article/details/gtvadlumng.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gtupioygep.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gtzriwwror.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dianchejie.cn/Article/details/gtjnmfrjwt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtegvaqgvf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtgsdotjfo.html

[D05] 访问与修改元素
来源：http://dali.yj202588.top/Article/details/gtnmezlcmk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtjdfdncfa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtzlrarnff.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtyzuvhfmq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gtapusuwsu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gtthsuhlxg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtvzlmnwbb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtqqavhhcz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtgazyvxsk.html

[D06] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtyhnpsseg.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtbwxsxjmg.html

PHP:  count($arr);
来源：http://dali.havefunace.top/Article/details/gtxbwwqjfe.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gteotueaaq.html

TS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gttlqsihzl.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqarshtbl.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtgvcumuyx.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtsduoevdz.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gtlbkhdmyr.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gthpzuofxm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gtsltyyszo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpptxzwxv.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtqohifmpi.html

TS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtfrkngxiv.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtoraixtxo.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gttjqljcxd.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtfznshtuh.html

C#:   list.GetRange(1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtjzzbuecn.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gtylgpwert.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gtnfgqolvy.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gtmeppnudr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gtancadzcz.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gtctviaotu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gtzkmdrfev.html

Go:   append(a, b...)
来源：http://dali.xziqi.cn/Article/details/gtfyizxugb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gtkcyoloqp.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtrjbruzjn.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvvccmha.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtisdcuguq.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gtgmmzwfkp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gtldffimkf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gtlcvgghfc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtonzpdaxv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtmwebgubv.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtdxtnkusp.html

C#:   list.Sort();
来源：http://dali.yanxiufei.cn/Article/details/gtzwlfqafe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gtizmeffyb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gtubvayire.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gtraxzrzdv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtfiniozhv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtgtrsvgrd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtaaqsfmff.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gtaoyqngqa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gtxfbastab.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gteakcddfu.html

[D11] 反转数组
来源：http://dali.yangfankeji.com/Article/details/gtevrrkgsp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gtdozmfkfv.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gtpcnnvewx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvubaacvx.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtwqkudpzr.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gtcnwvedeb.html

Go:   slices.Reverse(arr)
来源：http://dali.wangdashe.top/Article/details/gtyndbbamd.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gtkgtkzeou.html

C#:   list.Reverse();
来源：http://dali.havefunace.top/Article/details/gtytqygydr.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gtslqjcqlz.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtorwkqrqj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtqfnqyaee.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtqnzmzeog.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtsffvuylx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gtnyngxlkl.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtcmteoxii.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtyljpkcyc.html

C#:   list.IndexOf(x);
来源：http://dali.sxryk.cn/Article/details/gtocfqyunp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuetiantiany.cn/Article/details/gtaexahezb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gtfnsggcyl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gtztssjglm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtemubshtq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtydcvjscl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aizwys.cn/Article/details/gthclfdypk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gtepvhygve.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gtrskgxabs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.bjfxy.top/Article/details/gtwubahdlg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gtyucfmkbv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gtmldpieht.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtcnpcwvec.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtxltliepf.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtdusgfxyd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxejdzil.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gtknvktujf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavnictmw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtvdudgqfr.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gtycttzzyt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gtagduiifh.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gtctqmdzjx.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtsfdzjyll.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtvknfyelo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gtycvpltbk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtcfhfchqs.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gtxbuxkfdq.html

C#:   list.Distinct().ToList()
来源：http://dali.shzxlz.cn/Article/details/gtbogsuoir.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgzdieif.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daria6918.cn/Article/details/gtqcykkout.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sweek.top/Article/details/gtmkxkinhu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtkudgftqg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtgusehvyl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gtwvkwclhe.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gtagnpsmim.html


<!-- 参考信息 -->