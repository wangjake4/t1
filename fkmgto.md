代发 wailian999

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtgthvfqjw.html

Go:   if data == nil { return }
来源：http://dali.316326.xyz/Article/details/gtvjvnnpdu.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gttgagmsnd.html

C#:   if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtpbgqqhjt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpezkqubo.html

C. 函数与作用域
来源：http://dali.nwbrower.top/Article/details/gtgxqbgjpt.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkmzexxhd.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtyvadwfke.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtosneewcz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gttakewmjj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtrokldbhb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtwktvbtsf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gthgwwxefd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtuuipzdaj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gtmsnyswod.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtuiixbosb.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtcbrtnikk.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gtajwcrbel.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hysaishi.cn/Article/details/gthmaeeohs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtgtjvxnfp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtzmxlaoie.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.andypj.xyz/Article/details/gtgdzmcxiz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gtffuzooha.html

Ruby: def greet(name = "World") = name
来源：http://dali.yueranfly.top/Article/details/gtoummhiih.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jiagoushi.top/Article/details/gtmfsdjwfu.html

[C03] 可变参数
来源：http://dali.ehwqpu.com/Article/details/gtgrjrbfyi.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gtxjttnqkr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gtuhzlwzgk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtniscudpk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtsmmdrjma.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gtnookfxgd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gtvexwguar.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuanzx.com/Article/details/gtceobcekx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.mhx1999.top/Article/details/gtfxujqcwr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gtrzqbbqxh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cqqwz.cn/Article/details/gtwfzqjgxp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jiagoushi.top/Article/details/gtsdextxdy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtwsitucuk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hfpthk.cn/Article/details/gtcracmxpi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gtsxxvagcz.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gtvyygtffz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtmbrfazgd.html

C#:   f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtueevdbzr.html

[C05] 返回多个值
来源：http://dali.hysaishi.cn/Article/details/gtlogtfcib.html

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtqsimilhg.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtkrioxbnb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gtcwzjnnaa.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gtgtrwibms.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shangyingyoupin.top/Article/details/gtkyhtyaqs.html

Go:   return a, b
来源：http://dali.ivvv.top/Article/details/gtohbruqjv.html

Ruby: return a, b
来源：http://dali.gzhubu.top/Article/details/gtosbtnamp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangshuangyany.cn/Article/details/gtxgwrngzc.html

[C06] 匿名函数 / lambda
来源：http://dali.yongpay.top/Article/details/gtzbrgnukj.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gttonuqcyo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cdnleiting.top/Article/details/gtvgaseukc.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtmvisvfsw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtvtfjnoxj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gtlsojsbcb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxcqcvhx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gogol.net.cn/Article/details/gtwyclryoq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtsrhtatez.html

[C07] 把函数作为参数传入
来源：http://dali.chenzaomai.com/Article/details/gtrdcrabrc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gtzdhmgbzj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtpcynozpk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gtacyqdiou.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gtubfmocol.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxinkj.top/Article/details/gtudszcwwu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gtypwgtcqw.html

Ruby: arr.map(&:upcase)
来源：http://dali.bjfxy.top/Article/details/gtwonygbyi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenlongwang.top/Article/details/gtjctqlmgx.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gtbauhdadk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shuidangran.top/Article/details/gtqkvzejlq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gtarzngbft.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtjpnvqlkl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtnnvlbpeg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gtebyyhpxi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gtxznlfixs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gtotpwyhmv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtqgjbfgxt.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gteqzctvbu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtedkkxwxg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtbglhcazh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gthtfimbrt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtzoswrivb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtxqimvbnx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gtqkluisvi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtrdxbppqe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258.top/Article/details/gtyefikmzj.html

[C10] 变量作用域
来源：http://dali.iojbl.cn/Article/details/gtsgjeixnq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtkieozqlt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gthqradisw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gthbcbgumi.html

TS:   同 JS
来源：http://dali.dashuyun.cn/Article/details/gtpiksimeq.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtdddmhzir.html

Go:   花括号块级作用域
来源：http://dali.gzhubu.top/Article/details/gtbxvoekgy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gtlqpgxnye.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtgchzpcvo.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gtskkkbetf.html

Py:   from module import func
来源：http://dali.xuanzx.com/Article/details/gtngarzvve.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gtzaqutdol.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtdqvmkxmg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdmptxhf.html

Java: import java.util.List;
来源：http://dali.xuetiantiany.cn/Article/details/gtvljwrhmv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gtbsstrcsz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhiwuduotai.top/Article/details/gtzoalitwf.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrcefydc.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gtddiyhkho.html

Py:   (lambda: print("run"))()
来源：http://dali.iojbl.cn/Article/details/gtijslgrjs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gtkkmfzraz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtshiyzphe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtibfwppjm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guowangkeji.top/Article/details/gtyaujvlyw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gtqscbsnrl.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj202588.top/Article/details/gthzdgbpob.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gtuzczezpl.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gtvbqfqncc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtgdmwqkcz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtvkkhnytu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.smart0.xyz/Article/details/gtihkcclzd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtxglpfxjc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtavpcmkli.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwhpoubh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hammf.cn/Article/details/gtfzemxywi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daria6918.cn/Article/details/gtfkascydm.html

[C14] 泛型函数
来源：http://dali.zhiwuduotai.top/Article/details/gtnnksspml.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gtzrmzvbtm.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtqjkxkvmm.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtvfclqndv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuanzhike.top/Article/details/gtourdczvt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gtpkjbcgab.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gtaosrygrl.html

Ruby: # 无泛型
来源：http://dali.xuanzx.com/Article/details/gtkdmhovzm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmhfqail.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gttdxgrkbv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gtlsyqpyly.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangdashe.top/Article/details/gtdkhhccky.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtpcfeeesv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsrmkxeaw.html

Java: // 无解构
来源：http://dali.cheryme.top/Article/details/gtsylphnne.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gtulqdooyz.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtjtxnxbgl.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gtjfzvndxx.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gtdncveixn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gtwzcubtgy.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gtpoiadxbk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gtghmlkprx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gtcregzjdj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gtgasohjyu.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gthczoaepv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gtdwsofewu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gtmjxsmlrj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbwsagwwg.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gtwelvsrfe.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbugeyouq.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtebrntcfv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pengpengdd.cyou/Article/details/gtowfswqwy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshercszy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtlfoipoqw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gtcotomkhc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.snrcjt.cn/Article/details/gtwvqcjugw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtwvvdatdb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfidymwzq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gtyqthvbue.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gtxffjdbpl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sufxvd.cn/Article/details/gtliweghmh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gtmxhalemd.html

JS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gtkvhqrfdo.html

TS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtvvdfnqun.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtyndksvll.html

Go:   arr = append(arr, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtnflhhpql.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtkkqdlknz.html

C#:   list.Add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtztlnktah.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gtrezfjcdo.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtlnxvgosm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.feifeiyinyue.top/Article/details/gthoweidbo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gtmpgxtgcm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtnzwwjepq.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtnzvurpvw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ppjwa.cn/Article/details/gtowjlxwfc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.andypj.xyz/Article/details/gtvokixmdm.html

C#:   list.Insert(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtnlkqldje.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gtkbelofak.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gtgqlhexpn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgfzy.top/Article/details/gtubahloso.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtpghlwiyj.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gtivcztnzu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fengsongda.top/Article/details/gtsuludduo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigfzy.top/Article/details/gtkacbityy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtxqeklwqm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhiwuduotai.top/Article/details/gtmeixrfsl.html

[D05] 访问与修改元素
来源：http://dali.hongshengwenyu.top/Article/details/gtpqgimmxi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtsxddphgl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gttefoyopz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtcvdtcdoh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gtbowfuago.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.svipenyu.cn/Article/details/gtyenhoqrp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtxmvrszgo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtmcbwbetu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtlyqlhbpx.html

[D06] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtrnoytydd.html

Py:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtjexthwqn.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gtopatxuzj.html

JS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtezbbaaos.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtqnudbxtm.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlugzgcnh.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtayugqbmw.html

Ruby: arr.length; arr.size
来源：http://dali.hnqzz.top/Article/details/gtqmnhqgsv.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gtiribqgpb.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gthebawdgr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gtjtmjnjss.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtezmmeivp.html

JS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtatszfqjp.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gthnqezskt.html

Java: list.subList(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtzbvbdrcf.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gtwamviouz.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gtcwkkgpuc.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gthpzbhzox.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gtwhkjauer.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirmdmzhk.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtqgecitjq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gtgcskuuit.html

TS:   [...a, ...b];
来源：http://dali.jlsjyb.cn/Article/details/gtsottazcc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtuprvjlqy.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gtytxctyps.html

Ruby: a + b;  a.concat(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtgufzwgxe.html

C#:   a.Concat(b).ToList()
来源：http://dali.yueranfly.top/Article/details/gtmpzeaufa.html

[D09] 排序（升序）
来源：http://dali.hammf.cn/Article/details/gtirvkqvup.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtggimyjox.html

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gtfltfiwoa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gtswcjogkg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtmjpifieo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gturvmcwwf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtkdpdqaon.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gtmhybutdm.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gtkovnyjdf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gtqagcrdat.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ydzc1.top/Article/details/gtwmzulbls.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gtxmqevnhy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtwrvznkgj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtzgsrooaq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gtkcuhaaaq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtnbvazueg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gtrvfvtvdl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gtprvorglv.html

[D11] 反转数组
来源：http://dali.sysykeji.top/Article/details/gttaccpgmb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gtggdbmukb.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtauawdrvb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxuanxn.top/Article/details/gtqwzolwwa.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtciahpslr.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtjeiwkbsm.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gtwwirlxnv.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gtlosjktzw.html

C#:   list.Reverse();
来源：http://dali.cheryme.top/Article/details/gtaodzgibo.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gtkuvextod.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtefctznxl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtflhzmvez.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtaomhqciy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtvqwyeosr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gtbgbxbkej.html

Go:   slices.Index(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtcyivuunu.html

Ruby: arr.index(x)
来源：http://dali.nanxinkj.top/Article/details/gtlwhyxqtx.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigufen.top/Article/details/gtltjuynpm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dianchejie.cn/Article/details/gtcwntijom.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.svipenyu.cn/Article/details/gtbwgqjunq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gtzzltttka.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtnznbbehm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtgvzggpcn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuanzhike.top/Article/details/gtcgguxmgg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gtphmrjiit.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gtvzwjzkjb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gtrxcvfsnw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbouzepct.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtihpgsqru.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yueranfly.top/Article/details/gtetzjiqrr.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gttkluizsq.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmxqtlrc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gtofpxajzn.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtczqkeghh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtbodaylxp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gtmubwpldo.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtimsqqwep.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtjbhijrqf.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gtvwofhouv.html

JS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtrkhutqrv.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtoudqijwk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gaohongyu789.top/Article/details/gtwfnapxnf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gthqfpcftb.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gtskbxeaab.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtsljclpxw.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtembhfpik.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gtxjjdqdfi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtwduxguib.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtjaabvaay.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtpqrbulgm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gtopwejtcm.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gteyqbftto.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtaomckxej.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gtnwcaskve.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtvfwpmppl.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gtdpyvafwu.html


<!-- 参考信息 -->