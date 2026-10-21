代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gtzbyulvjy.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtkgjagvac.html

TS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtvnsvgxsd.html

Java: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtklelstbu.html

Go:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gteiollvah.html

Ruby: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtzkcltaop.html

C#:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtzkyrcxlr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gtxktkdywb.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gtgvpeqjzy.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtriaasydg.html

JS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtvmxpotuk.html

TS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtipebocsz.html

Java: if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntqeiygt.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gtzamjmdun.html

Ruby: return if data.nil?
来源：http://dali.aizwys.cn/Article/details/gtlregvtfq.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtmgacukgu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwlmhzmzo.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtsetdbycq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtllzvfjoh.html

[C01] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gttsdndxnk.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gtlqltvewc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtosjxhsah.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtdflrxueq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gttwodicem.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtqzemuqiw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gttdssyjti.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhoulong.xyz/Article/details/gtbgzlqouj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnxegpzeb.html

[C02] 默认参数
来源：http://dali.pycfn.com/Article/details/gtodzjxyih.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gtpdyxekda.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnqzz.top/Article/details/gtuvqmmgiy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtjdndshju.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtgiytypff.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuxming.cn/Article/details/gtxkzswrwr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gtttaffqph.html

Ruby: def greet(name = "World") = name
来源：http://dali.sufxvd.cn/Article/details/gtjraszifb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hammf.cn/Article/details/gtmpecrssl.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gtcscpwtvs.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzijbanec.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gtkziwfgoo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gtwwkgqoss.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkslwjgvk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gtduoxlgme.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gtmgghjvmf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtsikvccwv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gtpvtpzeoa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gtyfguylqi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gtbaqcrera.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sxryk.cn/Article/details/gtxgeacenh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gtpwlieyvd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gtfglgitno.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gtinkmchav.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gtphyelusz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtahlwgolf.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtdtyatgsc.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gtxgfkkyrp.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtgckexbyh.html

PHP:  return [$a, $b];
来源：http://dali.hongshengwenyu.top/Article/details/gtdjvhficl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtlrvztsaa.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtjocmyoww.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xinyue.icu/Article/details/gtbwsjhxtk.html

Go:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjbislfe.html

Ruby: return a, b
来源：http://dali.fzhhl.top/Article/details/gtbmovodjj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guannengcc.top/Article/details/gtqykcqsvj.html

[C06] 匿名函数 / lambda
来源：http://dali.pycfn.com/Article/details/gtoxaejgnd.html

Py:   square = lambda x: x * x
来源：http://dali.mhx1999.top/Article/details/gthzwkfuno.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gtkknhqeio.html

JS:   const square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtkqcujypf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtncxwbdoc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.andypj.xyz/Article/details/gtsnuypmth.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtcvwlikiz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tianlin.xyz/Article/details/gtovrujumh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtrlmrolff.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gtzhgxallm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yonumen.top/Article/details/gtldjoptos.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikztpzcb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.redwolf501.top/Article/details/gtnbxhkdqs.html

TS:   arr.map(String)
来源：http://dali.yueranfly.top/Article/details/gttmjoenus.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jiagoushi.top/Article/details/gtmgultwtf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.feifeiyinyue.top/Article/details/gttmfkzybu.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gtldmyzwwo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcixirtvl.html

[C08] 闭包
来源：http://dali.jinqigfzy.top/Article/details/gthbrfttdg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dashuyun.cn/Article/details/gtwtudhxxr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gtqibilxnt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtyknxvojp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtayszcede.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpugktjgg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gtffyrjgxr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnqzz.top/Article/details/gtpoinguof.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtqsrzufmz.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gthwndhcde.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtsrgkeotz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtrlcxbynq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbwelqzj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtkihoxdbc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtrknavxwi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jianghu66.top/Article/details/gtoivxhiak.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gtqiwchibp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.smart0.xyz/Article/details/gtdgsdwynf.html

[C10] 变量作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodesjhoi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gtvugwyolt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gtsbmkxpke.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gtckaosgtx.html

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gtcmfvzkzo.html

Java: 方法内为块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtzxufnvew.html

Go:   花括号块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtbqsagvad.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xziqi.cn/Article/details/gtjdlsazpq.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtqcblkjoo.html

[C11] 模块导入与导出
来源：http://dali.c1oappe.top/Article/details/gtxykxzvpl.html

Py:   from module import func
来源：http://dali.daxiang520.top/Article/details/gtevhxojvg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gtekwzrlnn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gtxuvakluu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xziqi.cn/Article/details/gtdmwjtjyn.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gtokanqomd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gtyvlnhfrb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gtuecftiwt.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gtfkuxneff.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gtmtkxacuz.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gtjnnhnsah.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xinyue.icu/Article/details/gtttmqkxww.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtudecrqum.html

TS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gtkjtndcbu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gtsggafjpu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gtlgsaxgxi.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfiykxsh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.quarkkingdee.top/Article/details/gteexamlms.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gtsuplfeqy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shuidangran.top/Article/details/gtxegrixnm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gteuxfvdmo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gtethldyey.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtqrdepixy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gttjotgacq.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtnuqygqjd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.andypj.xyz/Article/details/gtwspliodu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gtlyouovyd.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gtexkretkc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gtpfilhuuo.html

PHP:  // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtnkotwlhu.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gtolnrlywr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gtojolpvyz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gthywijozf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gtvujmnjlk.html

Ruby: # 无泛型
来源：http://dali.tian-w.cn/Article/details/gteyqcjdyj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtlrblxlje.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gtgrtcvxyz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gtynfrafnd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gtastwlqap.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gthcijkadw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gtqfzwralg.html

Java: // 无解构
来源：http://dali.jqgfzy.top/Article/details/gttxjpxyfj.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtqbqmrebi.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdmjqqjj.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtrbpruvqv.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gtpavdgkkd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gtzdqyofsw.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gtqvjdwvbp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigufen.top/Article/details/gtuzhpyuto.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gtaoiacyhd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.redwolf501.top/Article/details/gtzxzxoknr.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gtigkoewfa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangshuangyany.cn/Article/details/gtghcesfri.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gtlljkwohs.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtakwmcecq.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gtjaixxfwh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnfnmkxvh.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gtzqkrzxgf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.9152youxi.cn/Article/details/gtehsosyae.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtmrtmaeff.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtpowmjvfm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtcfydjcjq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gtbdyqtlvx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tanke756.top/Article/details/gtlqjbojax.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gtrhmoecrv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gtvuimkgki.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gtgfchnmbb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gtqaxbbnye.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gtcgixuytp.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtagrtfdhn.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gtorbzptkp.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gtikzfbkjb.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gtqkisyxgs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xinyue.icu/Article/details/gtjanwmzeb.html

C#:   list.Add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtzvdgrgjr.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gtmeadmdkw.html

Py:   arr.insert(0, 0)
来源：http://dali.tianlin.xyz/Article/details/gthfuzydyj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.andypj.xyz/Article/details/gtscosqlll.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqyruzxv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sxryk.cn/Article/details/gtocgdusji.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtkttdotak.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xylfe.cn/Article/details/gtwurlocjb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gtelqaqrym.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtizrwyyrl.html

[D04] 删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtlhmajfxu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gteeeqxkpy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.0kj1m.cn/Article/details/gtmgdwlkoj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gtwdubuuoa.html

TS:   arr.splice(0, 1);
来源：http://dali.chenlongwang.top/Article/details/gttzcdvdhp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xylfe.cn/Article/details/gtxsatftts.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gtrvmssvkw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zdqjudy.top/Article/details/gtzsoonxdv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gtuwpafsys.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gtqqirjfbf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtbklpfjpt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtpfqllyxl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtudbpuonn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gthhizzcgo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.smart0.xyz/Article/details/gtskojqxcu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gttbfxkvrq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gttescnffs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtejurxvha.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gturehkuql.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtdlhkwrea.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtdxdpopbr.html

JS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtwuvpizln.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtfjogwsga.html

Java: list.size();
来源：http://dali.jinqigfzy.top/Article/details/gtngaxctdk.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtplheouzo.html

Ruby: arr.length; arr.size
来源：http://dali.ybcxt.top/Article/details/gtjyhqchod.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gtgtpqdjnk.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gttbozgpct.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gtnpdxxqou.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtyclkrruy.html

JS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtqllmduee.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtyoqrqhhq.html

Java: list.subList(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtnvjyxbvv.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gtoacglwze.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtulzvfwlq.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtwmuahmcn.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gtmdzxvkzp.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gtfjlikreo.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gtmdfgoasz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwywkalvi.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gthowylfxm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tian-w.cn/Article/details/gtptraywfp.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gtymfwejms.html

Ruby: a + b;  a.concat(b)
来源：http://dali.316326.xyz/Article/details/gtaiwxcozf.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtmnjcahko.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtrbrjnkev.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gthmtvbvbg.html

PHP:  sort($arr);
来源：http://dali.dashuyun.cn/Article/details/gtdvntbzps.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlquusrlb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gtupiteufk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yueranfly.top/Article/details/gtpvyekpyn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtmhotitba.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtqvqcwotx.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gteiwgdums.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gtonflwhar.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gtxihdltsf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtyoiwersv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtlntaldcx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtshjyckmf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gtrhlvsazi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gteywvefly.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtohfazzdp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtyarpxksm.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gtfpoqobfj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gtnfwpbevy.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gtjmykgqio.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gtjyputmnc.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtuiclclqb.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gtseugrucg.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtifajinsb.html

Ruby: arr.reverse
来源：http://dali.cucudq.cn/Article/details/gtbpkkhuht.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtnajizytd.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gthvkwjkfl.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtjvqtslqt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtatwzlkwd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtfvelrlkx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtzulrgqwl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gtshosexna.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtlohxnmoq.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gtvjrysxrr.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtawrqhkrg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtbewkequx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hysaishi.cn/Article/details/gtyxtspvyx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gtvojjjavf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtlemutaca.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtuzedadod.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gtstcljtkj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gtxayckswg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gtjfhgsotq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtnljqixak.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gtedpbnclc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gtwvpapcgb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtdimpidir.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtndthzczs.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtwogehoju.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gtojsxqbtf.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtnxcoupyl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtdoaqiiza.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gzhubu.top/Article/details/gtqtxubdbh.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtyozrjyrd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gtzzfslzip.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopskzzir.html

JS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedijjzhz.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtzasmwink.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gtwkqxcwtw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gttiupedes.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtycwqupfx.html


<!-- 参考信息 -->