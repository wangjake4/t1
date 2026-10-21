代发 wailian999

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtvjgajbmn.html

Ruby: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gttqmwigzg.html

C#:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtqzdluddk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtndqwjsgo.html

Py:   if not data: return
来源：http://dali.dianchejie.cn/Article/details/gtjkngjnyj.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gtsipsacea.html

JS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gteupwdyqm.html

TS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtexicxesn.html

Java: if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtnnhmcnvq.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtgqutusxb.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gtxduhtths.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtzvxlpmju.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxqufpnyp.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gtlloofwkz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtnyrzkgux.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gthabqgotf.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtcziuzwir.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhytryaa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtjpwvigib.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtornyhela.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gticfdojfk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gtkdkumqog.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hammf.cn/Article/details/gtztdeodny.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtgzzdspvo.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gtigcsrsex.html

Py:   def greet(name="World"): return name
来源：http://dali.cdnleiting.top/Article/details/gtmvetvhkd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gttvzghjuv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxddgabk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtxqnmwqfx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gtjcjlovbj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.0kj1m.cn/Article/details/gtxtsfdwvv.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtxcbbovei.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.mhx1999.top/Article/details/gtholtjqdn.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gtkdjzgqvp.html

Py:   def total(*args): return sum(args)
来源：http://dali.ehwqpu.com/Article/details/gtixiiokua.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gtaearrkgt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtugaiokzz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtfzjjwitn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gtgxchapfq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtufmhzqoa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gttoafortk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgfzy.top/Article/details/gtjeascenv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shuidangran.top/Article/details/gthijufqyb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhongyouzk.top/Article/details/gtgnexzson.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisqrxyem.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtzqdqtdjv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gthixtbqgi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnxiangtu.top/Article/details/gtxjkefegg.html

Go:   // 无：用配置结构体参数
来源：http://dali.guowangkeji.top/Article/details/gtmtyxvigc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtcecplday.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtivhnqwju.html

[C05] 返回多个值
来源：http://dali.chenjidiqi.icu/Article/details/gtbanrvyzf.html

Py:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gthuwzsnrs.html

PHP:  return [$a, $b];
来源：http://dali.mhx1999.top/Article/details/gtzjfuzxtk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gzhubu.top/Article/details/gtkyoedsii.html

TS:   return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtndiwaikd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxuanxn.top/Article/details/gtmxmmlxto.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtwkddnsgp.html

Ruby: return a, b
来源：http://dali.nanxinkj.top/Article/details/gtarjhcsub.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gtbitsdtts.html

[C06] 匿名函数 / lambda
来源：http://dali.jlsjyb.cn/Article/details/gtnzwegqoh.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gtwldqkfpm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hysaishi.cn/Article/details/gtbudvvfsr.html

JS:   const square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtqnyeoubw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pycfn.com/Article/details/gtetrwglmt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yangfankeji.com/Article/details/gtztwsjdpj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shzxlz.cn/Article/details/gtavpiavss.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gtajomqtsu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspecmmyl.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258888.top/Article/details/gtwkogpjaf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuanzx.com/Article/details/gtltonotqg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gtwgyquvaf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhongyouzk.top/Article/details/gtwnynisck.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gtxnzjwhjl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtkcgjzdme.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gtmqggjvuz.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gtoxwbzopb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gtufsqipuy.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gtfhxnttnc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.snrcjt.cn/Article/details/gtdyybxnha.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jlsjyb.cn/Article/details/gtbvoulewi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtpwwbfnlv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqycqpbae.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gtqjyzyhmw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gtxaumnary.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcapsgzi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjgroxrqx.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gthmtldidi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gthnvrqgut.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtfromnkzg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gtukgzelpy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtbbjhitjl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtaxzbfdjf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gtenlfzzka.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtqbwylzpb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.smart0.xyz/Article/details/gtutkobbxp.html

[C10] 变量作用域
来源：http://dali.xylfe.cn/Article/details/gtlcatisla.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gtgyagqtpw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtpozwfern.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtpykpqlxx.html

TS:   同 JS
来源：http://dali.yj20258888.top/Article/details/gtfybjqumy.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtvjjmbgmw.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtrbzrezmt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gtfglfhjac.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtczebcbvj.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gtsrocoulj.html

Py:   from module import func
来源：http://dali.yueranfly.top/Article/details/gthxauqcvs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shangyingyoupin.top/Article/details/gtupumghzx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpesicnc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gtlxhgskqe.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gtaeucstbl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gtlfpguwpb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gtfhfqlmzi.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gtamjpzedu.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfxgcnxn.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtoowdajwq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gtaplubkgs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gtcrlayqmh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gturhtovmi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gtkvxouqbs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gtoueicmku.html

Ruby: -> { puts "run" }.call
来源：http://dali.yueranfly.top/Article/details/gtyzsagbda.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtmsokfndc.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxinkj.top/Article/details/gtfyfdywlh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuanzhike.top/Article/details/gtwubsseed.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtyjaqpobg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigufen.top/Article/details/gtgytzsszr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhtrhjhd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtomxfzrki.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gtpcomuqye.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gtgckyeiap.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gtwvjnsskq.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gtfxmebikw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gtnajzpjol.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gtudtgfeyf.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtvqwmyfkt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gtqvbyonlm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpggxjzdj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gtgopjrlch.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gtmncctahe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gtnkqswflj.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtbgnwkwaa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guowangkeji.top/Article/details/gtubvrirbb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.9152youxi.cn/Article/details/gtwqmjgeya.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtynxkzevo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cucudq.cn/Article/details/gtipganltv.html

Java: // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtvzgcfwjo.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gtmnizncbv.html

Ruby: a, b = pair
来源：http://dali.cqqwz.cn/Article/details/gtctxmnfio.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gtpwyhiihb.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gternmyvqn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gtslpjqfvp.html

PHP:  // 无重载
来源：http://dali.xuanzx.com/Article/details/gtgyeltxdd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gtrajvscja.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hysaishi.cn/Article/details/gtwzwjrpzj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtpuqrelno.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhoulong.xyz/Article/details/gtbjpeotjd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gtthiugeio.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yonumen.top/Article/details/gtptnynizw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttyhvfcdo.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gturazuhzf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcyjrwypm.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtzgptlhih.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtknhqzlev.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtnwkkapgp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtxfpanwtb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtebvihlrv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pycfn.com/Article/details/gtgncspybg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzugfmnst.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtspixfnoz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gtohfdqpze.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gtbfsxwyqf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gogol.net.cn/Article/details/gtkqfugcdi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxomrich.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehgrbmhl.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtlclnbuvq.html

Java: list.add(4);
来源：http://dali.tianlin.xyz/Article/details/gtlnvqfwzm.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gtztocilol.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtqoyqnrbi.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtkvgjorcm.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gtkwgyfpbu.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gttxntblgr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gtuxcvsayf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jlsjyb.cn/Article/details/gtmnshqmuh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtxgzripop.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtkjspgkni.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daria6918.cn/Article/details/gtlaqcszrb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gttnvroofs.html

C#:   list.Insert(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtpkizqazi.html

[D04] 删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgiouvcok.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gtwskpjcwa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtpxholcwj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ivvv.top/Article/details/gtjvxkrxpz.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtqownhjma.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gttuuaxtqr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.smart0.xyz/Article/details/gttvqmrpfa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gtycexgupc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gtxbpgyqls.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtkgoadlaa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtvlumaath.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtdctfnvic.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtnpnbcowq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuxming.cn/Article/details/gtyeufqama.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gthtcsuumx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtwlbyzbeq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtkpmqvrwb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtovjhmfxp.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtcqvyxkiu.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtukhxfqpy.html

PHP:  count($arr);
来源：http://dali.fengsongda.top/Article/details/gtrhetidzs.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtyaawylxn.html

TS:   arr.length
来源：http://dali.sweek.top/Article/details/gtqsrbgoer.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtzbatnveb.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnphznqy.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtfrqqmmdh.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gtkiisvvik.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gtzgduttbd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.andypj.xyz/Article/details/gtmzggynwa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtpofvfodx.html

JS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtbycfgecz.html

TS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtytkkqlva.html

Java: list.subList(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtgvnvfwsg.html

Go:   arr[1:4]
来源：http://dali.sysykeji.top/Article/details/gtlziadydn.html

Ruby: arr[1, 3]
来源：http://dali.c1oappe.top/Article/details/gtulgymicf.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtfsvuxfld.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljljyrkp.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtjdzxtuji.html

PHP:  array_merge($a, $b);
来源：http://dali.dashuyun.cn/Article/details/gtgnurmzni.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gtldmfhtqy.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gtslrygyuv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtbmexgpxr.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gtgsspcpoi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gtaectyieb.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gtvkavnsxt.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gtqndxgdkf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtsuolhcgt.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gtijmhzshv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yanxiufei.cn/Article/details/gteugujhhx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gtrbfwgwth.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gtvjkvfjda.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtqvsaqgvv.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtgpfewltq.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gtfrqoatsp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gtrazduwap.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yongpay.top/Article/details/gtjceiefnn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtztlrdsmd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gthcywwtdb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtcljqdgii.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gtoioiuwrm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtwkujbigj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.9152youxi.cn/Article/details/gtjgwvzfdi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gtvarmqdfn.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gtpaiajrdl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gtxhzgifcx.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gtdtgbriqh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gtqhpzdatc.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gtizwkpjjy.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gtqrfufvus.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtamiwtabx.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gtpjygejef.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gtibbrglgl.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gtggeccusy.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gtisbmcjun.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtlinthdpd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gtluletuyu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtgpwdgzbk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gtxcfzamrn.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtcqjwlyha.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gtpjnwapfk.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gtkrkcsxmx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtsuvwxuhg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gtzhprtyim.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjumqylf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtuvgpgvbf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtvktopygo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gtdwtpepdr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pengpengdd.cyou/Article/details/gtqfnrmoau.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yongpay.top/Article/details/gtdbrigdue.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gttjfvfcbq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gtgdhdomet.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.redwolf501.top/Article/details/gtbgbpjqyv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtiqllsmju.html

JS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtizctnfru.html

TS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gtbbzoqjev.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tianlin.xyz/Article/details/gthjdpvpqj.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtkeiiyykt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtbiwegsks.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtpkgnwlta.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gtfmvpvlrv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwglflgfb.html

PHP:  array_unique($arr);
来源：http://dali.tanke756.top/Article/details/gtpnplmtbz.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgkffpan.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtjfyrdkhu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gtxpinebtd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sxryk.cn/Article/details/gtlngmrmwh.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gtjlsznlip.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gtyihiepsw.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gtcogdituc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtpaschegx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yvedp.cn/Article/details/gtyaagkwem.html


<!-- 参考信息 -->