代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtzrkvcocz.html

Java: x instanceof Number
来源：http://dali.fengsongda.top/Article/details/gttrvclcab.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gtvlnwmxvd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gthoswjszu.html

C#:   x is int or double or decimal
来源：http://dali.ppjwa.cn/Article/details/gtxcebpjem.html

[B14] 判断值是否在集合内
来源：http://dali.yuanzhike.top/Article/details/gtpjnxppzu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhengqikj.top/Article/details/gtnfscmsta.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gtttopxxbw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtvuocrirh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtbnhpybzd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtdhnnuljw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigufen.top/Article/details/gtihugobcg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zycfv.cn/Article/details/gtwajqlqgl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtvhlrlxal.html

[B15] 布尔运算与取反
来源：http://dali.chenlongwang.top/Article/details/gtmziplzbv.html

Py:   a and b or not c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchgimljf.html

PHP:  $a && $b || !$c
来源：http://dali.yj202588.top/Article/details/gtdvctxteb.html

JS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtwfupgmmv.html

TS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtdtwxfbhs.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirxlrzps.html

Go:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtwhixucfo.html

Ruby: a && b || !c
来源：http://dali.yongpay.top/Article/details/gttoyatbsd.html

C#:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtuvfdabwy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guannengcc.top/Article/details/gtzbcbecrm.html

Py:   if not data: return
来源：http://dali.yonumen.top/Article/details/gtpaloedcj.html

PHP:  if (!$data) { return; }
来源：http://dali.jyoumei.cn/Article/details/gtfavaigpc.html

JS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gtbzrnfikg.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtsyaqygii.html

Java: if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtwttahoij.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gtafikfvlh.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gtyjfedeez.html

C#:   if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtnepzuixb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzalwhpux.html

C. 函数与作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyrmyfxs.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtrrthsfbd.html

[C01] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gtvivasowx.html

Py:   def add(a, b): return a + b
来源：http://dali.kuanghao11.cn/Article/details/gtdfgwrysq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtwoavlejy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtqxjctlpa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttarkheuw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtyjrkhnil.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.haohaochexian.top/Article/details/gtfdwmswpe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtjkxpyyxx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtpgpemgaf.html

[C02] 默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtvofyytqn.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gtikbesjgv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cheryme.top/Article/details/gtcnhazqhb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtbixtwojk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtegeyewds.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xylfe.cn/Article/details/gtepxjseqx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shuidangran.top/Article/details/gtganotmdb.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gtruhruvqd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gtchsbvxpu.html

[C03] 可变参数
来源：http://dali.jinqigufen.top/Article/details/gtsjgpepcy.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkekbkmy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.birdmap.top/Article/details/gtemvxiuxf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gtmwgpupcw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtjvedifbr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.snrcjt.cn/Article/details/gtdfhdljoj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dianchejie.cn/Article/details/gtwyhjxxnb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhiwuduotai.top/Article/details/gtbcbbarhz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tianlin.xyz/Article/details/gtyuqdiyif.html

[C04] 命名参数 / 关键字参数
来源：http://dali.feifeiyinyue.top/Article/details/gtncubmjoo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gttrmchezt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zdqjudy.top/Article/details/gtpnldxvln.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtojnkzyqi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258.top/Article/details/gtifmtvgtw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sufxvd.cn/Article/details/gtzufaxcmh.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gtztzeysgx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gthdzzlogw.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtjyqaoqxc.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gthrwcsifl.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtjbaaborn.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gtcycecdlm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangdashe.top/Article/details/gtheewswoo.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtvqisigwr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.vqdsnc.cn/Article/details/gtihuvptoi.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtkgaddgqi.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gtgnuqldqj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.birdmap.top/Article/details/gtzxthytux.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gtytfbmdwg.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtzcynqrrk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gtjnlkvstc.html

JS:   const square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gteanulvmb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gtzghmydwe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cheryme.top/Article/details/gtziyegect.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtorccxlgi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shzxlz.cn/Article/details/gtegwudbuu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtctigeqag.html

[C07] 把函数作为参数传入
来源：http://dali.jinghuilouyu.cn/Article/details/gtbavqcpqg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcxeoszp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtwvcjchtg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.bjfxy.top/Article/details/gtphinegal.html

TS:   arr.map(String)
来源：http://dali.hnqzz.top/Article/details/gtjgtkedjv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gtrcbizurh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.havefunace.top/Article/details/gtigqkmmnn.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gtbfxetfox.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigfzy.top/Article/details/gthatbcbnt.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gtwjewljvw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dianchejie.cn/Article/details/gtsgqifbnu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtyekgzqdi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtnewjqhoc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtiedtgpwq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.snrcjt.cn/Article/details/gtfaanivxa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ybcxt.top/Article/details/gtpnhverds.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gotoacloud.top/Article/details/gtvtiwiboi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtvfqwfioi.html

[C09] 递归
来源：http://dali.nanxinkj.top/Article/details/gtiagvcqwp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtmjxgawuc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtnwirkjif.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtswjvodkk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtkyyaexey.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gtznzhmlic.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gtflqplarm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtpbqpnxcp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.iojbl.cn/Article/details/gtczqledjt.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gtqvozonfy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aizwys.cn/Article/details/gtxsihayrj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtqjikntqo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtcfrexbwo.html

TS:   同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtmxchzaeq.html

Java: 方法内为块级作用域
来源：http://dali.nwbrower.top/Article/details/gtwwhmiman.html

Go:   花括号块级作用域
来源：http://dali.havefunace.top/Article/details/gtgykxncep.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.birdmap.top/Article/details/gtouhftcck.html

C#:   块级作用域
来源：http://dali.zycfv.cn/Article/details/gttuykscim.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gtdzwnbsnz.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzafwvssl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gterupsvyt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gtagbvyfbn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yangfankeji.com/Article/details/gtmsvkgphc.html

Java: import java.util.List;
来源：http://dali.ehwqpu.com/Article/details/gtwvvlmhya.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fzhhl.top/Article/details/gtegqjfdbw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gtjtwpkwep.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gttvskowtl.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gtmqqlwndz.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoyndwpr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtyfbssqsq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtwhnqopox.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtcubbzoyj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gttlfygszv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gtqhwnszee.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gtvfergfho.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gtaqnqlblz.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gtfdpdamzv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gtmcktvhbb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtdvualnyz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daxiang520.top/Article/details/gtyujltfhg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtutgxdvzb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gthxbhqnsr.html

Go:   func add(a, b int) int
来源：http://dali.yuanzhike.top/Article/details/gtplcfioio.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gaohongyu789.top/Article/details/gtpozakpzk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigfzy.top/Article/details/gtxcflyndh.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtzopfvwwx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gtzsamsmva.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfftdvox.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtcxiubvez.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzqndaxnz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtblndapfe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtaagomlnl.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtzahafgdx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gtgtcpcgxy.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdfejvbu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbevaowdz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gtytznfmwn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtvxpekppg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfndtzzdh.html

Java: // 无解构
来源：http://dali.shuidangran.top/Article/details/gtlperbuhg.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtppyvidgo.html

Ruby: a, b = pair
来源：http://dali.sweek.top/Article/details/gtmkmeatyv.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhekgxkz.html

[C16] 函数 / 方法重载
来源：http://dali.daxiang520.top/Article/details/gthpaculsk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gtdvzlnkqu.html

PHP:  // 无重载
来源：http://dali.yj20258.top/Article/details/gtfjhzwvfy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigufen.top/Article/details/gtqqvdbyhq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtcgvdekjx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtxhtwubgx.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gtoilkknjk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gtszriaynd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xinyue.icu/Article/details/gtlialdqbv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyfqontiu.html

D. 数组 / 列表 / 集合
来源：http://dali.yanxiufei.cn/Article/details/gtuvzikiqy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtomiixaqu.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtkadovtxk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cdnleiting.top/Article/details/gtqqvcbysh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtuoccndke.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gthufabxij.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gtcreagazk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gthspiarct.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtziijjgyj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtcohjwyzw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbaihvav.html

[D02] 追加元素到末尾
来源：http://dali.zhiwuduotai.top/Article/details/gtigmcimad.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gtdhhtfter.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zdqjudy.top/Article/details/gtptyivmgp.html

JS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtwldrfyfx.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtkrimzmjr.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtlayjmgyo.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwgnchmt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpijcivh.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gtvjkelgck.html

[D03] 在指定位置插入元素
来源：http://dali.pengpengdd.cyou/Article/details/gtcnpkouau.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtmustwnqt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.haohaochexian.top/Article/details/gtkvhppxkd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gtjiizhtuu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sysykeji.top/Article/details/gtxxfrrglp.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtszvakbks.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtgeeacevj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yanxiufei.cn/Article/details/gtuntvqzff.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtspuawbiw.html

[D04] 删除元素
来源：http://dali.cdnleiting.top/Article/details/gtvkyhlhbz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gtnvytrbyc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtwdxcfwiu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daria6918.cn/Article/details/gtphyjfmih.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gtzzthrips.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zycfv.cn/Article/details/gtimuhemvg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.meibo888.top/Article/details/gtcpggueyc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gttxarzhom.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gtbagweltb.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gtpvxxbkqt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtfrfbugab.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtyxcvdthf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtwgdvvkrl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gtegiglier.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtsrxgbtud.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtkxgkylcf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gttkddagrl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtczwcklta.html

[D06] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtucciewpe.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtduexchbs.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtuxndtpdd.html

JS:   arr.length
来源：http://dali.yonumen.top/Article/details/gtqwvaushm.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtimvhiewc.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtrmupyptx.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtekwgtafd.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gtmiccjxrm.html

C#:   list.Count;
来源：http://dali.kuanghao11.cn/Article/details/gtygsbwomg.html

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gtcxuejisg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shangyingyoupin.top/Article/details/gtjepkupeo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtpjmkfudp.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtgpwxvefp.html

TS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtcilerjit.html

Java: list.subList(1, 4);
来源：http://dali.yj202588.top/Article/details/gtclahjnzn.html

Go:   arr[1:4]
来源：http://dali.hnxiangtu.top/Article/details/gtehimmpym.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gtgoygqaek.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtzogzcdsb.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gtxrujwskv.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangdashe.top/Article/details/gtwvdgkpph.html

PHP:  array_merge($a, $b);
来源：http://dali.andypj.xyz/Article/details/gtsywodktq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.vqdsnc.cn/Article/details/gtdjrumopq.html

TS:   [...a, ...b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzjlpidi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gzhubu.top/Article/details/gtzivckgpn.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gtjmwriovq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hfpthk.cn/Article/details/gtvmoaowvh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthunhbrmn.html

[D09] 排序（升序）
来源：http://dali.zhiwuduotai.top/Article/details/gtaxcvbpfu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtuhbtplnm.html

PHP:  sort($arr);
来源：http://dali.hnxiangtu.top/Article/details/gteeqrjnsi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtppnsuzmm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtieweysac.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gtxlaeppxr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtxihlffcj.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtspjlueaf.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gtfzfhxnyz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.birdmap.top/Article/details/gtibimohbl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gthpeggqtw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtiysnpatb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtrzaaszur.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtivienjnr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gttnjzbhuz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtgloyvqsw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hammf.cn/Article/details/gtvhcuktof.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.iojbl.cn/Article/details/gtoqjfylrr.html

[D11] 反转数组
来源：http://dali.yj20258.top/Article/details/gtefcndosr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gtedsatcdi.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtzmzansvo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.vqdsnc.cn/Article/details/gthiexxzyr.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gtfklcdpbr.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gtalkjbmis.html

Go:   slices.Reverse(arr)
来源：http://dali.chenlongwang.top/Article/details/gtwemhtbwi.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtqockikbq.html

C#:   list.Reverse();
来源：http://dali.meibo888.top/Article/details/gtcfzywidl.html

[D12] 查找元素下标
来源：http://dali.yuxming.cn/Article/details/gtsifhvtes.html

Py:   arr.index(x);  x in arr
来源：http://dali.hfpthk.cn/Article/details/gtpvmzrjzk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtxrcdqnzz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtovxktfdf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtlnhfqxcv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gtkpnilzyy.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtqtrevwnk.html

Ruby: arr.index(x)
来源：http://dali.316326.xyz/Article/details/gtgoplvuwc.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gtqlqdakwj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hysaishi.cn/Article/details/gtcnervqwh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gthzdqtxfo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtatfkriwg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtjmnfhvpx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtiwfcvogw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gtuhlbszak.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gtggdopzqe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hysaishi.cn/Article/details/gtddydbokm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtvhwvsjbh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gtucbxmyrx.html


<!-- 参考信息 -->