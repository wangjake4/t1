代发 wailian999

Py:   if not data: return
来源：http://dali.316326.xyz/Article/details/gtdxsabhdv.html

PHP:  if (!$data) { return; }
来源：http://dali.zhongyouzk.top/Article/details/gtksosgkxu.html

JS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gtkrgbhteh.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtkcimslra.html

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gthiwwcqek.html

Go:   if data == nil { return }
来源：http://dali.havefunace.top/Article/details/gtpnycktcs.html

Ruby: return if data.nil?
来源：http://dali.gogol.net.cn/Article/details/gtjviofkja.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtacmxsmwv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtmssodtab.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gtvrosmrpn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjzzcbupg.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtnluezrrq.html

Py:   def add(a, b): return a + b
来源：http://dali.ydzc1.top/Article/details/gtcmwycmpy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtgldkivqa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtwjhwmhgw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gthscxlkfz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtnxmkhbpd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shzxlz.cn/Article/details/gttvxwrxyw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gtlcpyfcvy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtlwvxtpji.html

[C02] 默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtekoijuxd.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtfjeyiayt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gtxmpmvfmn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbtzngym.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtbtrlzqmm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gtmoobdxvp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ppjwa.cn/Article/details/gtakdegbhe.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gtsyrcyste.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shangyingyoupin.top/Article/details/gtjdewpsjf.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gtyfyqaiqb.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gtdfqvunkz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guannengcc.top/Article/details/gtaryqiqhq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtwiaujgqb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnktgjsgj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gtkxwyokpo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hywenlv.cn/Article/details/gtexfcxmyf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gtdaexozqk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hysaishi.cn/Article/details/gtccomnisa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xinyue.icu/Article/details/gtjonmdbgy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gtgecosklt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gtrtbzhcsl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtgkwmkpzo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.andypj.xyz/Article/details/gtlwdxgupv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.feifeiyinyue.top/Article/details/gtrzgxdxnn.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtlffibkit.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtunvewcob.html

C#:   f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtekbshgrc.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gtbxzvqdfo.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtqwsdxdpd.html

PHP:  return [$a, $b];
来源：http://dali.hammf.cn/Article/details/gtmrwgkbbp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gtxeodaxui.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtdyjtimpr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gtdnirdkmm.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtqrimhkoo.html

Ruby: return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtqwlzxlcq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gogol.net.cn/Article/details/gtzttqsfwu.html

[C06] 匿名函数 / lambda
来源：http://dali.0kj1m.cn/Article/details/gtfjvknjyw.html

Py:   square = lambda x: x * x
来源：http://dali.gotoacloud.top/Article/details/gtnhackjmt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sufxvd.cn/Article/details/gtyjkykqtm.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtffdhkdjn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtmdflrbrr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtawdpnukq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gtmmwxfrod.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtyiegckrx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtvdbmbxxc.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gtgmhvzydb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gtlegptuxa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtxyjxvskz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.vqdsnc.cn/Article/details/gtnovcrfbi.html

TS:   arr.map(String)
来源：http://dali.sweek.top/Article/details/gttkpnyosr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sxryk.cn/Article/details/gtnvampqvr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sweek.top/Article/details/gtrosjcfrm.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gtbmeijpeg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tian-w.cn/Article/details/gtvfqzplmx.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gtntoqqyhy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqjukicu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.birdmap.top/Article/details/gtmgyrkybv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtivdqbjdt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtvuyzgkmd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangshuangyany.cn/Article/details/gtyebgxtdx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gtwfzmikuj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jlsjyb.cn/Article/details/gtolyoeioe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtoqelvhvt.html

[C09] 递归
来源：http://dali.yj202588.top/Article/details/gtxkyadbvc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gtaifgmiwm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtxrrvlvio.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtyazvirpt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtouhmssrg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtqjypbvla.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtmprsvtzb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gthoazpbds.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.bjfxy.top/Article/details/gtcqhuyzkf.html

[C10] 变量作用域
来源：http://dali.guowangkeji.top/Article/details/gtdheutdri.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnxiangtu.top/Article/details/gtfhnpmzsw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gtjijukzhn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gtfanexffx.html

TS:   同 JS
来源：http://dali.ybcxt.top/Article/details/gtdqcdnmzf.html

Java: 方法内为块级作用域
来源：http://dali.havefunace.top/Article/details/gtmusdebmn.html

Go:   花括号块级作用域
来源：http://dali.c1oappe.top/Article/details/gtogwfnmdd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gzhubu.top/Article/details/gtmqgpavsb.html

C#:   块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtfsdzsfkx.html

[C11] 模块导入与导出
来源：http://dali.iojbl.cn/Article/details/gtlrjyfozv.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gtvgyllvps.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yanxiufei.cn/Article/details/gtcgaxeykq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gtbdcaxtpm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhengqikj.top/Article/details/gtngiemvjd.html

Java: import java.util.List;
来源：http://dali.yuxming.cn/Article/details/gtvshtmkxj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gtmcdeozvm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gtybjujouy.html

C#:   using System.Text;
来源：http://dali.fzhhl.top/Article/details/gtuzupghzw.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gtcmurrmve.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gtvfeyzkqz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gtidqmoflx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gtnvklzbcj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gtjsxzhxhv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gtgfwyobqf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtcjmerziv.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gtntamnguy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gtkawrdwvh.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gtrkkmjojg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gtlhremwvt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtywlkfusp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gtojilkdgr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtqpgukczi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtfkljztww.html

Go:   func add(a, b int) int
来源：http://dali.svipenyu.cn/Article/details/gtssubfpxw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gtqytyvntg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gtecmctryb.html

[C14] 泛型函数
来源：http://dali.hysaishi.cn/Article/details/gtiaiolbon.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtvwxvloku.html

PHP:  // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtmejoffor.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtszmjkfmh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gtevplwwtk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gtdygmmayo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gtezdofoyu.html

Ruby: # 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtuhpqkdhh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.9152youxi.cn/Article/details/gttumqxfek.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gtkylgcche.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gtkrkipgfx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuanzhike.top/Article/details/gtzckmolha.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtvjcjmjyc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtumftnwdp.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtbshclnjv.html

Go:   // 无解构
来源：http://dali.hysaishi.cn/Article/details/gtyifyzpxq.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gtbwhpvnni.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gtwsgamvxq.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gteximsptu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gtjnzalluh.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gtaqjijwes.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gtuhdfnsch.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gtsioyakpj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gttsishwlk.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gtrvyqtxxv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gtwzxzhvnn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbjfqwqn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdaosmuig.html

D. 数组 / 列表 / 集合
来源：http://dali.svipenyu.cn/Article/details/gtnruopfca.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtyfxieoeq.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtekygrcna.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtglovpspr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekqnqmua.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nwbrower.top/Article/details/gthiuncxpa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sxryk.cn/Article/details/gtxenlauxc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.birdmap.top/Article/details/gteqndjfcg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gtzqykvbat.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhengqikj.top/Article/details/gtxqjvotve.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtmxbeyagu.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gtxfiskfqt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtgzisidvi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscffvznx.html

JS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gtezynbzhu.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtvsazpxki.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtjwxykcwy.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtlssyplqd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gtxiuczuwv.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtnfdvscqr.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gtjyutdvve.html

Py:   arr.insert(0, 0)
来源：http://dali.xinyue.icu/Article/details/gtdwudeodl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gtdmeunjjz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gtwdijagmg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtdztpxlqa.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgbauovf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gtmakiultk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.snrcjt.cn/Article/details/gtyzyiclzi.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtpafddjpz.html

[D04] 删除元素
来源：http://dali.svipenyu.cn/Article/details/gthqbbfjpn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gtyxpwukws.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.316326.xyz/Article/details/gtvmrzbwno.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yvedp.cn/Article/details/gtnulcvuls.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gtwhmaqiir.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gtxrhmzbrh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gtxlbuxjsa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gtroykoqps.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gtpjsssitg.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gtunrksczt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtshdubock.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtzeryhudy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtbfwjxgda.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hywenlv.cn/Article/details/gtdafnzpho.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.feifeiyinyue.top/Article/details/gtyfmzwzya.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtekwfpylm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtaxshctnc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtbtyaqnle.html

[D06] 数组长度
来源：http://dali.yj20258888.top/Article/details/gtoayxzfyx.html

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtghmiydjo.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gtiottsdfa.html

JS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtiwkitjce.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gttrqvjtlr.html

Java: list.size();
来源：http://dali.kuanghao11.cn/Article/details/gtrqfubluj.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gttikkotth.html

Ruby: arr.length; arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtgdadymqp.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gtkqdtmhsx.html

[D07] 切片 / 取子数组
来源：http://dali.birdmap.top/Article/details/gtvjggiiwl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gtkithmjrc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gtarsfrspi.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtqhyjihqr.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtfrrsliou.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtmyjrtima.html

Go:   arr[1:4]
来源：http://dali.cucudq.cn/Article/details/gthcggclds.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtjzwxhbdl.html

C#:   list.GetRange(1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtpgwxfvwm.html

[D08] 合并两个数组
来源：http://dali.gzhubu.top/Article/details/gtpdhrhqkw.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gtdbfyyiam.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtnmxabnqb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gtwbakxdif.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gtriqoustg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.mhx1999.top/Article/details/gtwdhpmteh.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gtjwrxcfkv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtulhtosaz.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtgryphenw.html

[D09] 排序（升序）
来源：http://dali.hnqzz.top/Article/details/gtpcoevqiw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtedrzwbhy.html

PHP:  sort($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdxjqsvf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtunczgpqt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.redwolf501.top/Article/details/gthgxxofxa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gtapxidgep.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtgxowfhta.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gthayfdkzc.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gtmfsiwsja.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovpqiuqo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gtptcpsuur.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtlaqyjxvp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtcpqucaig.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtwjnjmral.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gtlqamuopv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gtpptojriu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ehwqpu.com/Article/details/gtuulwwavh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtnkglfiqo.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gttugquaki.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gthuiribol.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtuzxoqhds.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gtjbylwhzd.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gtiehjhgyl.html

Java: Collections.reverse(list);
来源：http://dali.chenzaomai.com/Article/details/gtqwcaybta.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtjqyapeac.html

Ruby: arr.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtoejhaqky.html

C#:   list.Reverse();
来源：http://dali.ivvv.top/Article/details/gtkryrqena.html

[D12] 查找元素下标
来源：http://dali.pengpengdd.cyou/Article/details/gtswqrekph.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gtvegrrhbx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gthdzquhpl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtxfixgzyx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtagrndlov.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtwxuiajss.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtxjvpwojm.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gttoolbyvf.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gtjifuafui.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gtyyyfohti.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtttrsimij.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnqzz.top/Article/details/gtrnptioju.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtrvwljgsh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyuhrckq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gtzvpqjsez.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtzgzsxxsu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtlbzdekey.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtbzvelafh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gthxjptjfr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtvexlpllg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gtfsuggkft.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtiuuedbyo.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtlkwqzxzl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtmqyuaazl.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtqwiipscf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtqdhjielm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gtqxihanvc.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gttvocclca.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtelaoxofj.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtyalmucrs.html

JS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtqlqdgcxa.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtwxlvubac.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gtgcqdndem.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gtvlqkapvq.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gtjfehdghq.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gtvndrzdsm.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gtbwlopyuu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tanke756.top/Article/details/gtanadjvyh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gtsslsopcs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtwlcrejnk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtneinyshf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gtqfcrqotk.html

Go:   // 手写循环累加
来源：http://dali.mhx1999.top/Article/details/gtxxhuigmn.html


<!-- 参考信息 -->