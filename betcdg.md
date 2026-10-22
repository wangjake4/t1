代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuanzx.com/Article/details/gtdokfhtfh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtehlluhhu.html

[B15] 布尔运算与取反
来源：http://dali.zhongyouzk.top/Article/details/gtbunzpfce.html

Py:   a and b or not c
来源：http://dali.jlsjyb.cn/Article/details/gtgemqpisb.html

PHP:  $a && $b || !$c
来源：http://dali.zhiwuduotai.top/Article/details/gtspadkzjd.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtfemifbiu.html

TS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtihilvexu.html

Java: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtdbyuvgbu.html

Go:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtisicbbnc.html

Ruby: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtmpnpbzlj.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtqfbyzyse.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtckgmendc.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gtvgfqokjv.html

PHP:  if (!$data) { return; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcfsyqgxb.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtiaapingh.html

TS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtgsjfnnzu.html

Java: if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gtcrxnpjrp.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gtacuecwum.html

Ruby: return if data.nil?
来源：http://dali.yangfankeji.com/Article/details/gtsthcdpwn.html

C#:   if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gtxfzymjms.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxsotzoj.html

C. 函数与作用域
来源：http://dali.aizwys.cn/Article/details/gtmmnxuuqj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtsksclntd.html

[C01] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtnsxuqzzl.html

Py:   def add(a, b): return a + b
来源：http://dali.sysykeji.top/Article/details/gtwffmvjvj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtihaoftpt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtnbeisufd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqtphnje.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtkwxmvuvd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.birdmap.top/Article/details/gtuvdcxkdd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.havefunace.top/Article/details/gtrgpveblo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtlehybcpf.html

[C02] 默认参数
来源：http://dali.sweek.top/Article/details/gtghvbaxky.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gtccjfsnjf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.iojbl.cn/Article/details/gtatrmprlm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtmgueghhm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtyyzbyhgk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sufxvd.cn/Article/details/gtgmxdleuh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gogol.net.cn/Article/details/gtchtusyau.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcocghhy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nwbrower.top/Article/details/gtmlrulieq.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gtbckwobka.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gtqjzpebho.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gtykaytdkz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gtwvdfblfx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtdoesejvm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gtsgvolfqm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddeumygs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gtwkqkphls.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gtnreyijxi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gtzlclegej.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gtjzbsattp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gthrmtbeuj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtopunlwvr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtehisuvyi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigufen.top/Article/details/gtqlsodbhc.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenjidiqi.icu/Article/details/gtcasljhka.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtoopzygcw.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtrgolpgef.html

[C05] 返回多个值
来源：http://dali.shanyushiyangtech.top/Article/details/gtovjwgxwz.html

Py:   return a, b
来源：http://dali.wangdashe.top/Article/details/gttuyuvglv.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gtigxrnxbz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtymicnzyp.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtxwagplre.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxuanxn.top/Article/details/gtwkudqkno.html

Go:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gtsmvnzqlv.html

Ruby: return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtltvjsxav.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gttebzwlzh.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtkslmmukd.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtvalynilm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtqlkhqcil.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtjljrytlu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tanke756.top/Article/details/gtpteewrzg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gtvmznklyh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cashguo.top/Article/details/gtxddxknkp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gzhubu.top/Article/details/gtyhmhhgou.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtlkohstsd.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gtqcjpvgve.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xylfe.cn/Article/details/gtklljuaze.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtgdihjmso.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhongyouzk.top/Article/details/gthacuvpmz.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gtkkbqatqa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjwlkofd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.svipenyu.cn/Article/details/gtbovvqkwh.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gtloufijyv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gtjuhyopop.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gttlztmdbd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gtbnhsplmi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gtlieyzggs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtxvxlpkfd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gteykcaypn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnqzz.top/Article/details/gtxnebfqmu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hysaishi.cn/Article/details/gtquundfip.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gtzdpujxgh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gteyhndibg.html

[C09] 递归
来源：http://dali.0kj1m.cn/Article/details/gtxccyryya.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gtwtpklvua.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtyjutielv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gthewaicmc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gtjnzbvvhy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtnusfzwuk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gtyozxvpmi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gtygkgsmgq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.316326.xyz/Article/details/gttsbtyuzp.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gtqzvxfhji.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxinkj.top/Article/details/gtqnavdssc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtwxgnzrct.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtwrjmuozd.html

TS:   同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gtxrzvlunh.html

Java: 方法内为块级作用域
来源：http://dali.hnqzz.top/Article/details/gtxnnqywwd.html

Go:   花括号块级作用域
来源：http://dali.pycfn.com/Article/details/gtxfkdhbst.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gttwlxqrlh.html

C#:   块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtloeqmixu.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gtcopokpku.html

Py:   from module import func
来源：http://dali.gotoacloud.top/Article/details/gtftvskrrx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xziqi.cn/Article/details/gtttbcgusf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gtilzmdhha.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gtrqpheejd.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmfmgkdt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gtmrrgdmil.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtpvscqxxx.html

C#:   using System.Text;
来源：http://dali.gotoacloud.top/Article/details/gthwzvdepi.html

[C12] 立即执行函数 IIFE
来源：http://dali.guannengcc.top/Article/details/gtqkkzfhxl.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtbzosdrka.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gtuntzvqov.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtvgfghavk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gtwpirzcon.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jlsjyb.cn/Article/details/gtttgfrimf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gttkzpjvbu.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gtkzvjxido.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gtwnivrzdi.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gtbvtxyrhp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtvtymvnuj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtcjihyjmv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gtinxywlqz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtlboiiwkk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtjcswxtmx.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gtjhewcqir.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gtfhuxnhbr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pengpengdd.cyou/Article/details/gtuccidbcb.html

[C14] 泛型函数
来源：http://dali.nanxuanxn.top/Article/details/gtjnoqcdmy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdqqpboi.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtjabhffub.html

JS:   // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtvklcahpg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gtqkjrfwcc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gthqvhsvsl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gtqbendway.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtgxihykgl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gtxpydoehj.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gtpjvxrtnh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtcqwwekdy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gtbvmfimqa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtxqfhqmwt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gtidqjpehf.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtjyvdpbgs.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gttgdtyiiz.html

Ruby: a, b = pair
来源：http://dali.xziqi.cn/Article/details/gtngveunjx.html

C#:   var (a, b) = pair;
来源：http://dali.mhx1999.top/Article/details/gtzuxpdcql.html

[C16] 函数 / 方法重载
来源：http://dali.tian-w.cn/Article/details/gtmwnstjyx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sweek.top/Article/details/gtqtzdkwwc.html

PHP:  // 无重载
来源：http://dali.fzhhl.top/Article/details/gtbfjzagsz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gtfrlwhejw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gtllwwtqgy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtilonugvm.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gtrqjjmmcx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gtlhugrhfw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ivvv.top/Article/details/gtbhbzyvfj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjejglymi.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gtgqlwwszb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtnvskgefd.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtjcwvdyou.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yueranfly.top/Article/details/gtoecarhjq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtyqnlarcr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gtaxanjtkk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.smart0.xyz/Article/details/gtnvcbkzoo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gtasifzbpi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gthrieivir.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gtymidajrn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gtwcxjppgb.html

[D02] 追加元素到末尾
来源：http://dali.guowangkeji.top/Article/details/gtxwtuaimo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aizwys.cn/Article/details/gthyrsvelo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gthakertjr.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gttmkytase.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusauxuds.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtuaudgwkz.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtibubtkrf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gtrfxdjrdf.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaikvmux.html

[D03] 在指定位置插入元素
来源：http://dali.c1oappe.top/Article/details/gtbhulubse.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gtsswdzoke.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhoulong.xyz/Article/details/gtdxtzhpgo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.c1oappe.top/Article/details/gtpyddpvmi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gtfiungohm.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtzdwlgsnc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.c1oappe.top/Article/details/gtqlvocbhk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvdomxtd.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtmivfcqky.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtvkxsoxzg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sweek.top/Article/details/gtjpecyskb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtpfxrgfes.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuxming.cn/Article/details/gtwpjapjar.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtuztcntyb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gtzvxlditw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gtvyjtzdec.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtoyzkxcnv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gtbfydtanm.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gtvlnnfbuz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtdayiegzj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gttzgykjvj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtjwqzanws.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gtauxjuyak.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gttgnwaesk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtpyfxamif.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtaggzpzxh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gttdpqsvvl.html

[D06] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtzdmwlxaj.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtdvrmjzfy.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtcqmmisgx.html

JS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtobjrutay.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtdggbczkq.html

Java: list.size();
来源：http://dali.smart0.xyz/Article/details/gtcqkznkgg.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtimjbkoao.html

Ruby: arr.length; arr.size
来源：http://dali.fengsongda.top/Article/details/gtdqtbzghn.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtvnopplbe.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtzwivygjj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gtgcjdfckt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.c1oappe.top/Article/details/gtdptioyfi.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gteotgqick.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtcgpxheln.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtwduayybi.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gtjkgsusip.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gtrovgcwdy.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtgbscfjcz.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gtjzfbnohg.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258888.top/Article/details/gtczqxuegs.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gtfhlzutgy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.vqdsnc.cn/Article/details/gtcvlxseql.html

TS:   [...a, ...b];
来源：http://dali.tianlin.xyz/Article/details/gtladbhmah.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtmrxbbszx.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gtgzfnytvv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gtqqykpafp.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gtwtunkzak.html

[D09] 排序（升序）
来源：http://dali.hammf.cn/Article/details/gthdvxmgbr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtzrxdapue.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gtubchqkko.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gtdfgbrglt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gtmjbptgbp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.snrcjt.cn/Article/details/gtmitvyulf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtlfftstiv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtblwlakjx.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gtbxdffwzb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtowplfxzp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.kuanghao11.cn/Article/details/gtoiafbgwt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtzhlmsvui.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gtpcjskmnp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtzgxazbcv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gtspditbcc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gtuifjxecb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gtgfkrulsf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gtnonakvrf.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gtxjobgpzl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gtiwbbidhu.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gthshpuito.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gtrqadtoip.html

TS:   [...arr].reverse();
来源：http://dali.ppjwa.cn/Article/details/gtsrrqdrsa.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gthqoikvwg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gtotqxdihp.html

Ruby: arr.reverse
来源：http://dali.xuanzx.com/Article/details/gtauboxvgt.html

C#:   list.Reverse();
来源：http://dali.havefunace.top/Article/details/gtpknficca.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gtlgaiciit.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtfmrkdlqf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gtfacybhrx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtmhpvfccn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtpdgbzbyl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gtfqcgxati.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtwioixgwk.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gtcodqzxcg.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gtonscrzdj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shzxlz.cn/Article/details/gtajjawtzg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gtyyopehjr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gtwylftvvm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtaeeudhyc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtkbkvqynu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gteaqrdsgy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gtuhilyraf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gtjgmgzgcm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtscaxmify.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dashuyun.cn/Article/details/gtesbmehin.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gtfcqfzabm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtimllghzx.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtgclzusdf.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtdqrrplli.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gtmtttdcxm.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtibgtcppd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtzvbtssry.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtvdjhrnci.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gteszwmcvm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtqxckfmih.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gtaheecagx.html

JS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtujzbahyc.html


<!-- 参考信息 -->