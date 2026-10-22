代发 wailian999

Go:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtlbrqcoyx.html

Ruby: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtiyapmnle.html

C#:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtgfvbcpeg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gthqylhopx.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gtkqfddbry.html

PHP:  if (!$data) { return; }
来源：http://dali.cashguo.top/Article/details/gtxceokjmf.html

JS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gthfnrqyqy.html

TS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gttudaddbk.html

Java: if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gthjjhkcdn.html

Go:   if data == nil { return }
来源：http://dali.vqdsnc.cn/Article/details/gtedntbfzw.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gtqsobexce.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gtyyapqigv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttssbpvjo.html

C. 函数与作用域
来源：http://dali.hywenlv.cn/Article/details/gtsttxxcfc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtluvkrnny.html

[C01] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtgwbhrawk.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtkghgslpi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtcuworcdf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtzgdlfamu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtfojvykpq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gttvxbspgv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtyyozkyet.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gtfmnxinav.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttqxqjppw.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gtsjcjsqsv.html

Py:   def greet(name="World"): return name
来源：http://dali.tian-w.cn/Article/details/gtuwdahylu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtkabkmdav.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtxrdhouxn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtninlbwfy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gtdcwkjiei.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gtvkkdnqlv.html

Ruby: def greet(name = "World") = name
来源：http://dali.cashguo.top/Article/details/gtuhlxhxzq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cdnleiting.top/Article/details/gtmulhffda.html

[C03] 可变参数
来源：http://dali.jlsjyb.cn/Article/details/gtztchkbtj.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gtnvaizzzs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pengpengdd.cyou/Article/details/gtrjnsyhui.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtuirbfszw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtimjjduax.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gtzxeudmgq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pengpengdd.cyou/Article/details/gtkkbszqhl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gtqxaweksp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gtwnvdbwtc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gtjikkwetk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.redwolf501.top/Article/details/gttxbwvsea.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gtalcfikek.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gtanrgrnli.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtroglwbgt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gtyvhupkio.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gtkshbsczw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtapktrbgz.html

C#:   f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtuzoaizec.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gtnbwjkdvf.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtpizvnpgp.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gtcnqlcqzl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gtgvfhyrig.html

TS:   return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtwassqucp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zycfv.cn/Article/details/gtuqtqgkud.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtqpadualw.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtejzbtnss.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenlongwang.top/Article/details/gtrmadjsie.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gtwzwyvzti.html

Py:   square = lambda x: x * x
来源：http://dali.zhongyouzk.top/Article/details/gtzzyxglec.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigfzy.top/Article/details/gtvosfaxxp.html

JS:   const square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtevkhrxzi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gtgzmlgeph.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gtmipzyypv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gtikolzaoh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtywdbymse.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gttplgyslo.html

[C07] 把函数作为参数传入
来源：http://dali.hongshengwenyu.top/Article/details/gtbqcertym.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangtech.top/Article/details/gtphzzsgbg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cheryme.top/Article/details/gtzlfagiur.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenlongwang.top/Article/details/gtteiafrmf.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gtkyxklwun.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtghoudils.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gtqeisgxso.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gtcplrjcfv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gtagsruepa.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gtzzkzscfb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.kuanghao11.cn/Article/details/gtaqhslahg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gtonvpumnv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtpicqfeyh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gttejdoqqc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gtrsknfrjz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gtmxnsmquf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.haohaochexian.top/Article/details/gtfjzlosuz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtlnomwtrs.html

[C09] 递归
来源：http://dali.xziqi.cn/Article/details/gtodvqqaws.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gtqfgjbvsa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtilwfuxkd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gtmpyqrgln.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtnbibutcg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gtvvctevgw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhiwuduotai.top/Article/details/gtqartbpfx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtvvoujdtb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhongyouzk.top/Article/details/gtpozgmqia.html

[C10] 变量作用域
来源：http://dali.daria6918.cn/Article/details/gtuuvuoavy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gtqncwwzog.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gtsaaefthy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtluqncrdo.html

TS:   同 JS
来源：http://dali.dashuyun.cn/Article/details/gtvescrnmi.html

Java: 方法内为块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtvgsxirmz.html

Go:   花括号块级作用域
来源：http://dali.zycfv.cn/Article/details/gtnkmpbjpl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hysaishi.cn/Article/details/gtkfbznnqb.html

C#:   块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtlzksdhum.html

[C11] 模块导入与导出
来源：http://dali.bjfxy.top/Article/details/gtlxcmbfdw.html

Py:   from module import func
来源：http://dali.shangyingyoupin.top/Article/details/gttzpauaij.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gttspzedtb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtckodjxmv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.mhx1999.top/Article/details/gtfpctyytm.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gtbwzbwmlz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gtvfscsqvj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gtjvoyyjfz.html

C#:   using System.Text;
来源：http://dali.yuanzhike.top/Article/details/gtpksllqcj.html

[C12] 立即执行函数 IIFE
来源：http://dali.jianghu66.top/Article/details/gtksgcqtmp.html

Py:   (lambda: print("run"))()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdschifon.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cdnleiting.top/Article/details/gtmrxsvvoq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gteylxgnjq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtwobkkrfz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gtcsgrxwyq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gtxhsbvxwm.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gtxkyldfry.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gtlotfvuqv.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gtiddmqgrz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraboernr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtykxxbdvk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gtnvapwwlt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtzircuwuv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtkjckoilk.html

Go:   func add(a, b int) int
来源：http://dali.jinqigfzy.top/Article/details/gtioyhpoqs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gtfcegxyoo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gtacuqkiwh.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulouycro.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daria6918.cn/Article/details/gtmjvxotbh.html

PHP:  // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtvghpmncs.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqrnpscv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gtsqmgyhiz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gtyywdvuul.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gtdqxtgtpc.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtvopvjimb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyhshaic.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtodqmszei.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtbvimxszh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cdnleiting.top/Article/details/gtjkrjhtmj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtqdvlgiex.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gtqaltysfs.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtwbjmglvm.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gtrsvxswdp.html

Ruby: a, b = pair
来源：http://dali.xylfe.cn/Article/details/gtobxhcchs.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gtzqmlgzpl.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gtvuoeihxs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtxedchixm.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gthghvncpg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jyoumei.cn/Article/details/gtyxlxdtwr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ybcxt.top/Article/details/gtvldaotgt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gtmupikmrg.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gteiqawdyo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gtohfkglrs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnllupdbi.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxyescelk.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gthakiqppn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtgwttfzep.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzedzuot.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pengpengdd.cyou/Article/details/gtstotfvjx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtxyxfyyhi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgajsvrt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gtjgvffbni.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gtlkltxhls.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cqqwz.cn/Article/details/gtbmfyhekx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gtiflqujiz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gthysxihfb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gtanrhotxj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tanke756.top/Article/details/gtaznsxsiq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yonumen.top/Article/details/gtlcnbpjwz.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gttrtwhtaf.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtpultgwsv.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtyputjfxs.html

Go:   arr = append(arr, 4)
来源：http://dali.chenlongwang.top/Article/details/gtvhrsthpz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gtpnrcsnvs.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gteyneofvg.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gtvgxnopsk.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtwohfulpu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydkxaijd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gtmarhwbrx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sxryk.cn/Article/details/gtrvfukuss.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnmbqfli.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gttwhbejky.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gotoacloud.top/Article/details/gtelckcyxy.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtfnbotgxp.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtbcjhkeku.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gtxkxpancl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gtscxlrevf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gtytazqkkj.html

TS:   arr.splice(0, 1);
来源：http://dali.316326.xyz/Article/details/gtmolpycde.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ppjwa.cn/Article/details/gtwiocukbm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtcvqrnmdb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nwbrower.top/Article/details/gtmlzqraya.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zycfv.cn/Article/details/gtxhbuirtp.html

[D05] 访问与修改元素
来源：http://dali.wangshuangyany.cn/Article/details/gtuwjqczck.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtctprroxx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtwqtmdttc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtfzvvvsyr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gtvizbtomt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jyoumei.cn/Article/details/gtncwvyodn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtomacfinh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtquevxjak.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtnkhycwqm.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gtooyyrfnh.html

Py:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtnqltocsy.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtkuvedlyg.html

JS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtzpzgomni.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtlapkykjx.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gtjayvupxx.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtkjbewvme.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gtkztohscw.html

C#:   list.Count;
来源：http://dali.cucudq.cn/Article/details/gtsvvxqqfn.html

[D07] 切片 / 取子数组
来源：http://dali.jlsjyb.cn/Article/details/gtmhavpfow.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gtjqtgyimn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtnttsutdo.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gthatkfmqo.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtiblhfucu.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtagwtvedz.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gtqhrwvlrv.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gtqglzflkh.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxinkj.top/Article/details/gtnelutwwc.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gtabioxmce.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtjucxaldf.html

PHP:  array_merge($a, $b);
来源：http://dali.zhengqikj.top/Article/details/gtdfultmgd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hongshengwenyu.top/Article/details/gtgdcrewcz.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gtwhaqjzmu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtvxhxyckx.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gtwbupdzeb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.andypj.xyz/Article/details/gticuglrjn.html

C#:   a.Concat(b).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtrwwikvzz.html

[D09] 排序（升序）
来源：http://dali.shzxlz.cn/Article/details/gtnkxdpipi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtbcjchlhb.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gtnduiwgdd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gthacowaxk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangdashe.top/Article/details/gtwhaaxcyp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gtwbuzsrhi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtzuckzgtq.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtkvwtwdws.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjehojedi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.316326.xyz/Article/details/gtwcnsujui.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gttgbfuaal.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtdbhcbrwy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtdxfnputy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtaposdlze.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gtxlfwzmuu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gtqzvxhibh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gtdhdzseye.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuanzhike.top/Article/details/gtlqddhecb.html

[D11] 反转数组
来源：http://dali.aibaodan.cn/Article/details/gtvwuvkipq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gtjkbshdcz.html

PHP:  array_reverse($arr);
来源：http://dali.snrcjt.cn/Article/details/gtxbtmnsbs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gtguxpbivo.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtgckhmbtj.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gtctfmhmur.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gtliwsihoh.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxqakjfi.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtajytznac.html

[D12] 查找元素下标
来源：http://dali.yj20258888.top/Article/details/gthbxijiyw.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gtdumtnlyn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlprclfp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtxtymewjm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtujqsyqxs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtuyausaez.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtwbkrnpwr.html

Ruby: arr.index(x)
来源：http://dali.nanxinkj.top/Article/details/gtnvzyxqdz.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gtslrsetjr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jlsjyb.cn/Article/details/gtisifcomy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtkzzatqeo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gtbxzmxkiv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtbdmomuzz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtoeiycpfq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtleryzddb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gtyowseltc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gtvpgsuhth.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtmqwkugif.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gtnkbedmrr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gtwilllhef.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtrzpaunrp.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtxtfvofzm.html

TS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtqfxpzhnd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gtrvahfsti.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtfzhpgepk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtxaepdwil.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtlzeabmrk.html

[D15] 去重
来源：http://dali.xylfe.cn/Article/details/gthdokpmyk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtgutaahhm.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gteykemtse.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtxlleytpw.html

TS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtedjwzejp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xziqi.cn/Article/details/gtdyssqtqi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtfcoagfmx.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gtxzwceuxg.html

C#:   list.Distinct().ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkeinoef.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gtnfxzdwwl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtkvxksihy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtnuhunidl.html


<!-- 参考信息 -->