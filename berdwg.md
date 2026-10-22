代发 wailian999

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2klpwnuml.html

C. 函数与作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2csghbzce.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2abcrcmec.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gt2vziciinz.html

Py:   def add(a, b): return a + b
来源：http://dali.hysaishi.cn/Article/details/gt2cmyltqci.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gt2vzevgnng.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zdvoqxsz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2yrnjxldc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2nhgcuzsr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hfpthk.cn/Article/details/gt2legxioww.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gyyzndfo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2mznbwdyd.html

[C02] 默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfgjvoct.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2isklgaor.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gt2kbfjvkor.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2hkevyrvx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2bctdzlyq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jianghu66.top/Article/details/gt2pwtjwqxo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cheryme.top/Article/details/gt2oemdbfgv.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gt2kbvgubcb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zycfv.cn/Article/details/gt2ptyjbwff.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gt2lbfuyufn.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gt2oapmybwb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gt2rqphjeme.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gt2jnbugraz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gt2wibdqoyw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuanzx.com/Article/details/gt2kdcpiorp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gt2yphhdvpf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2oiawytzi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.c1oappe.top/Article/details/gt2ksuozdui.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbllmdti.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gotoacloud.top/Article/details/gt2wlqahoaq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gt2mqowkenl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okcjobvz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2taaueero.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.vqdsnc.cn/Article/details/gt2edlpzppm.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2snaqqauc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gt2xrwogvmg.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vezwozrl.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gt2ugklacfu.html

Py:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvhhupwt.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gt2misjaecb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.havefunace.top/Article/details/gt2hptbuudr.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gt2uejsejgf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pengpengdd.cyou/Article/details/gt2objtixvt.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gt2qwqhguys.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2nifhtoum.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gt2aqyxxhls.html

[C06] 匿名函数 / lambda
来源：http://dali.0kj1m.cn/Article/details/gt2ppkwxzmt.html

Py:   square = lambda x: x * x
来源：http://dali.gotoacloud.top/Article/details/gt2vdrhdpsb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gt2psfiobzr.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2ragbdwnc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hammf.cn/Article/details/gt2knatcwbi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yvedp.cn/Article/details/gt2fvoliruc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenzaomai.com/Article/details/gt2qzxygixw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gt2uxehiwus.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gt2rceanzgo.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gt2hgjnaqag.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwyiqfka.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2djqliyqv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gt2spxiblsf.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlfjhjys.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivpcjrho.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aibaodan.cn/Article/details/gt2jarcqjqi.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gt2fnpgschd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gt2zmctrsul.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gt2kryytmdc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gt2cdayhsqd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ehwqpu.com/Article/details/gt2naugdaxa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gt2bgywhqhw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2vawlcpcy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gt2krpmcveq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gt2oqaeggsu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gt2bfgigfxt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbtskydb.html

[C09] 递归
来源：http://dali.guowangkeji.top/Article/details/gt2wdypwwtp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gt2dneyycaf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gt2ivaxrivl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gt2kzxaoewh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gt2chnnpkoq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pycfn.com/Article/details/gt2ixzygmqn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gt2oicyrcyv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gt2tncogpqq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gt2hhfmyflm.html

[C10] 变量作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcvtokjw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dianchejie.cn/Article/details/gt2ysphghhb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zyyzrpsx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gt2rvnbcgop.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gt2plrxvymn.html

Java: 方法内为块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvtsltej.html

Go:   花括号块级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2uagfidpb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gt2wardninf.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2zovgyzab.html

[C11] 模块导入与导出
来源：http://dali.yj202588.top/Article/details/gt2bvwxodln.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gt2cvdqbpyi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gt2xdyzsjmm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbtsxqcs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gt2xtnhkydx.html

Java: import java.util.List;
来源：http://dali.shzxlz.cn/Article/details/gt2irimrtaw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gt2qorbucne.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqblsqjp.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gt2wpubfyff.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenzaomai.com/Article/details/gt2eokegqdw.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gt2czxqwgoh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gaqhldcz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gt2xmsymqsu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gt2kuevvnjq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shangyingyoupin.top/Article/details/gt2kokpxxfn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenjidiqi.icu/Article/details/gt2djjfugoa.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gt2bvyvnwno.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gt2dywpdyfn.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gt2uiseddtf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gt2mmnoshpx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gt2ajlgthdm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gt2kfgpzdxc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gt2scmlxgsp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2ctccryqr.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgdhtsns.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gt2cheeuuuc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gt2bxtseayt.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gt2nrreibwy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqmrthbq.html

PHP:  // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2kypllgww.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gt2hrkswjfq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gt2tjelwkfu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.andypj.xyz/Article/details/gt2aewozstd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gt2rzzudeac.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gt2hrvwsfbf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ydzc1.top/Article/details/gt2ckcvvxvq.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gt2vxbzxgvf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gt2wnkzvgkd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhengqikj.top/Article/details/gt2oomyscwz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2svbmwooz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yongpay.top/Article/details/gt2xzfglbig.html

Java: // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2wzczywpm.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlchiujo.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gt2crvbbblk.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gt2xhpzvalo.html

[C16] 函数 / 方法重载
来源：http://dali.chenlongwang.top/Article/details/gt2ushhwqmb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenzaomai.com/Article/details/gt2aggbunkr.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gt2wvfxmyfl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgwfeogc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gt2txocptvu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gt2fpiklyqu.html

Go:   // 无重载：用不同函数名
来源：http://dali.ivvv.top/Article/details/gt2fbkumhes.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yueranfly.top/Article/details/gt2czkvckod.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigufen.top/Article/details/gt2hugiiunw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ndvmwldh.html

D. 数组 / 列表 / 集合
来源：http://dali.vqdsnc.cn/Article/details/gt2ohuoxxgn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2jjfkykmu.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gt2boejgiiv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gt2xifirsqn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daria6918.cn/Article/details/gt2qecvzegd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.haohaochexian.top/Article/details/gt2hlnpxaty.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gt2vxezuvzt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.andypj.xyz/Article/details/gt2fjwhtqfd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ybcxt.top/Article/details/gt2dyujnwgz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.havefunace.top/Article/details/gt2lipzapoj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daria6918.cn/Article/details/gt2kksbuehf.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssrruqjr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuanzx.com/Article/details/gt2gzbpchmz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jianghu66.top/Article/details/gt2kbytlwug.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2idxrtbcu.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gt2wrhbrdzj.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qsgqahep.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktotcywz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gt2kurilcvo.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gt2iirjvlnz.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gt2vgsqbqrc.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gt2jygpkhye.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gt2izgarove.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gt2prcvaunr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2ymuppdmk.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gt2vmdygdux.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gt2dlkckwzp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gt2chveulec.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2ufatrxvq.html

[D04] 删除元素
来源：http://dali.birdmap.top/Article/details/gt2cfopqghn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gt2zchjnrwb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gt2olmexekt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cdnleiting.top/Article/details/gt2tuwgprfm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gt2ofeawmui.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuanzhike.top/Article/details/gt2figsbjwm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ayhljaaw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gt2nefnamik.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zycfv.cn/Article/details/gt2eeerdnuf.html

[D05] 访问与修改元素
来源：http://dali.yj20258888.top/Article/details/gt2wspkukpt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2ucjeijap.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gt2dfnjewcb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2oiufpkmq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gt2hawcbgog.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gt2qgdrcrjq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gt2dutmhbio.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qupohrye.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2vnljnrok.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gt2gogmkawu.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2wopnaoen.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqwosbby.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gt2kinoljao.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gt2lkvvbtru.html

Java: list.size();
来源：http://dali.zhiwuduotai.top/Article/details/gt2duzbyjkt.html

Go:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2eaeiloeb.html

Ruby: arr.length; arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2ywfgmnrw.html

C#:   list.Count;
来源：http://dali.chenjidiqi.icu/Article/details/gt2isnlrvfo.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqjtrizl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gt2lsnqqwvi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2qfxjwjgw.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2yizhewep.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxfwctme.html

Java: list.subList(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2xzzwtwxd.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gt2apdzkkun.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gt2ktyswzfp.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2koxdquih.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gt2mpfqwzgg.html

Py:   a + b;  a.extend(b)
来源：http://dali.shzxlz.cn/Article/details/gt2fqepryfx.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gt2iinvcogf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gt2ocsnplun.html

TS:   [...a, ...b];
来源：http://dali.havefunace.top/Article/details/gt2uyzqnhow.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gt2fpixazgn.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gt2lqzdjonb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gt2lffbtfpn.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2kdjkbpfm.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hclnleoq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2fdcunumx.html

PHP:  sort($arr);
来源：http://dali.xinyue.icu/Article/details/gt2eqllurau.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gt2osiaujti.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gt2dbpvnfov.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gt2pwuonzpz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gt2vfekwreh.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovsmpuzi.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gt2lloumyjr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtuyglpd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gt2vppacpyq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gt2lugbelcy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gt2cwdewfau.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gt2fefnhirg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj202588.top/Article/details/gt2uctkemru.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gt2eaupxlyz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gt2fvhgektg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hysaishi.cn/Article/details/gt2zygfjgta.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gt2oilfdibe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gt2lluxdelg.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gt2lihhwowc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gt2czxbofnh.html

TS:   [...arr].reverse();
来源：http://dali.zycfv.cn/Article/details/gt2dewkrsyr.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gt2yshrlyhx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2pcydboqs.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2ssxukqqe.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gt2qdorpigk.html

[D12] 查找元素下标
来源：http://dali.guowangkeji.top/Article/details/gt2vtxzouey.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pfffdewm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2ttpphdot.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2yegrhvbt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gt2ssyagabk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gt2ewdjkrjn.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2opljnbtj.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gt2nyngqspr.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gt2rixokjqk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mimtzjrj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2yiomsdgj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.mhx1999.top/Article/details/gt2sintdkom.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2kosazvzx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gt2zqnmpaax.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2hvutbsmm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqmboyii.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwaaodap.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2gohpqtxh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gt2xceqjljy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gt2ypoighhn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gt2fykwlkxr.html

JS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gt2sarbhhmb.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2sjuhaewb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2gmtqazwp.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gt2qpkoukmh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2zqiuilak.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2uyybnbsy.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gt2yjggazkg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmyyvtoj.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2sykovayf.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2slqgjidq.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gt2uddnfnhl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gt2euvcyxup.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gt2umtvmtez.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gt2brhslngq.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2facrxkpo.html

[D16] 求和与平均值
来源：http://dali.zhiwuduotai.top/Article/details/gt2xecdjsau.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gt2tsxrjqes.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2droioodo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2whwtwqcj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gt2zsuzyfwe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gt2jxuvwquw.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gt2yemxvldv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jlsjyb.cn/Article/details/gt2qrawujfk.html

C#:   list.Sum();  list.Average()
来源：http://dali.tian-w.cn/Article/details/gt2iuzezffy.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2jqrewayi.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2amyjgmme.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gt2agerbjyk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fzhhl.top/Article/details/gt2xjnmivcu.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gt2vxhypxjz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gt2ilcjxevz.html


<!-- 参考信息 -->