代发 wailian999

Py:   if not data: return
来源：http://dali.sxryk.cn/Article/details/gt2uinefoza.html

PHP:  if (!$data) { return; }
来源：http://dali.shzxlz.cn/Article/details/gt2qmxrdtrp.html

JS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gt2qrtlulzw.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gt2orgweerl.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekllyoll.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gt2nkwttgdy.html

Ruby: return if data.nil?
来源：http://dali.hammf.cn/Article/details/gt2ghvgzcwz.html

C#:   if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2eckowfwj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2fmwsyacj.html

C. 函数与作用域
来源：http://dali.hnqzz.top/Article/details/gt2kinlwmda.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2cmcpqhpb.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gt2zzfzewir.html

Py:   def add(a, b): return a + b
来源：http://dali.tanke756.top/Article/details/gt2fvrhbmds.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2sbtvqric.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2epgkuntm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2uveaepvh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2mwmztaya.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2nbtvqtuu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibxwqcko.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2lezvyrbh.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gt2zmxwrrbd.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gt2pjotggpm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gt2nkueqbom.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncstvnqd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbkyccdx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gt2viuvetjn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gzhubu.top/Article/details/gt2fgkwqups.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gt2rjyhumiw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjzosjfq.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkjzzljm.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gt2yowqyztd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.iojbl.cn/Article/details/gt2ivxwtpgn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnyyoubf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gt2xmuwwjdi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gt2cynovcfc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gt2plqtkzoz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpjpoosg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.havefunace.top/Article/details/gt2vrbydlsj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gt2lfmhunde.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gt2amcmncsk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gt2opiqpmtw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2sembiyte.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gt2ftsmdtkv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gt2dkqfnvkm.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2giuqsmit.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gt2iullqaks.html

C#:   f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gt2keaqgzet.html

[C05] 返回多个值
来源：http://dali.hongshengwenyu.top/Article/details/gt2ordaxvqi.html

Py:   return a, b
来源：http://dali.nwbrower.top/Article/details/gt2vhglohyh.html

PHP:  return [$a, $b];
来源：http://dali.fengsongda.top/Article/details/gt2mfkkkmlm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gt2nxpmiyun.html

TS:   return { a, b };
来源：http://dali.gzhubu.top/Article/details/gt2iuqgjxbo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jyoumei.cn/Article/details/gt2gkgaootq.html

Go:   return a, b
来源：http://dali.xylfe.cn/Article/details/gt2bttiwxpo.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gt2glyujabs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgufenzy.top/Article/details/gt2rbvvzbfz.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gt2xeqcgpcx.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gt2koicqvev.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gt2dttdzodn.html

JS:   const square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2gmmewguh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egrbelpq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2zwhpekoj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pycfn.com/Article/details/gt2xvgqzhhu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jlsjyb.cn/Article/details/gt2frytwsxm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gt2vsdpntdv.html

[C07] 把函数作为参数传入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gfehfcqb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.mhx1999.top/Article/details/gt2thlnwfrc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gt2npqcfdzs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fengsongda.top/Article/details/gt2oxoufdvd.html

TS:   arr.map(String)
来源：http://dali.redwolf501.top/Article/details/gt2etlaczlr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gt2pwvqmhkk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj202588.top/Article/details/gt2clhbjaoh.html

Ruby: arr.map(&:upcase)
来源：http://dali.yongpay.top/Article/details/gt2mzoiyymi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenlongwang.top/Article/details/gt2edvxflaa.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gt2xisqigpa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gt2svikazod.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gt2jkkimblm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jchycegh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nglqpllm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gt2vhoafypc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gt2frchgfys.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yangfankeji.com/Article/details/gt2woaxhdih.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljgvcsgs.html

[C09] 递归
来源：http://dali.quarkkingdee.top/Article/details/gt2utkkwrfj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2tgjejoyp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yubkthba.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gt2clmmhcby.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gt2hbwkhffw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gt2iqzxcszo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yvedp.cn/Article/details/gt2oicvbyre.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gt2uaofbldb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yinpphfj.html

[C10] 变量作用域
来源：http://dali.tianlin.xyz/Article/details/gt2lzbrrxsw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gt2feumdiyt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xziqi.cn/Article/details/gt2bybrauwj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gt2iyzfyoop.html

TS:   同 JS
来源：http://dali.pycfn.com/Article/details/gt2sgbcnflf.html

Java: 方法内为块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvdrvvrj.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gt2jjlfyxuo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gt2kyprcqbt.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqzbddgw.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gt2txatrzcu.html

Py:   from module import func
来源：http://dali.hnxiangtu.top/Article/details/gt2bjxanfbe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gt2eoaapoxg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2wfkgljtv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvsgbpjo.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gt2ryfrkiam.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yanxiufei.cn/Article/details/gt2ebmtzgul.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gt2rfspakyf.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gt2syfofxpy.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gt2hfknlcdd.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gt2deonbuvt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhixingplan.top/Article/details/gt2plsjyqan.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehncgrdh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2qgzqamtl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gt2ofhvokpi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gt2cuvkoenu.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gt2kuxfutud.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gt2oatiasbk.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigufen.top/Article/details/gt2vutrkedn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.haohaochexian.top/Article/details/gt2zylwfxjy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gt2bkmvnrue.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gt2mmxpmkng.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghgisbiw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2qdacrkey.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txizzvku.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gt2wixoftyx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxuanxn.top/Article/details/gt2mvbdziuc.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gt2cgqvuolr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nsodcffc.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gt2jovhlmgv.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gt2bjwctxhz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gt2pyjfzcmx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hysaishi.cn/Article/details/gt2tybtkwjf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj202588.top/Article/details/gt2cuhptxdz.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2xndravoh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gt2qopscswx.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gt2rcpoqvbs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gt2hnvcsmbf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwtuxhwu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2bhoknpav.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2orobkett.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gt2vcesvriw.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2lelepesj.html

Ruby: a, b = pair
来源：http://dali.xuanzx.com/Article/details/gt2toixczux.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gt2iorzcpgd.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gt2xnssuxyp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gt2exdiwsfa.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gt2lpkpdglp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gt2ajkgjuqe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyseqgkf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gt2nbdmsqwj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvmdmwvj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvpvewpj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ivvv.top/Article/details/gt2zzjmnfae.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2zxgrwikw.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gt2gwufuxvj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2icrjlizx.html

[D01] 创建数组 / 列表
来源：http://dali.birdmap.top/Article/details/gt2fcpahezj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnqzz.top/Article/details/gt2hdwtlrtn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gt2pzlrngcg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2hdycgayh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigfzy.top/Article/details/gt2ztrfutvy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gt2vogglhvm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gt2yytwbesb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ehwqpu.com/Article/details/gt2nwbqvsio.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gt2odeyqkki.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gt2ovuanagm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gt2mgjgwdwb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gt2mupmqnnt.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbujrcaj.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gt2cyrnevpc.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2agzompdo.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2dvbkefcb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhbljxbe.html

C#:   list.Add(4);
来源：http://dali.nwbrower.top/Article/details/gt2jyqufvrs.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gt2iovgrvnz.html

Py:   arr.insert(0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2fxxzjuti.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qgjqfmjj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gt2cueskabi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2upijxniu.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gt2tqstnizk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gt2viugakvm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gt2ygfbxhjf.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gt2uaddldkx.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kceacody.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cheryme.top/Article/details/gt2osaafpww.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oboytnla.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gt2wndytfdv.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gt2sawjazbt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsrnpmwa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gt2gelbqupu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258888.top/Article/details/gt2uprgvrup.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gt2kudjawqw.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gt2walrpyiu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gt2wskgsjxh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gt2beodnlkl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2quemiany.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tanke756.top/Article/details/gt2hkegoghn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gt2dlislltp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gt2kklzcmvk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2yrdzqdyq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2amnsdptd.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gt2vzamqrrf.html

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2hhjpjnjt.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2tvojysai.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gt2mqxvlfji.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gt2fghbmrpm.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gt2bpbviokr.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2zgxwmmbi.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlknnkde.html

C#:   list.Count;
来源：http://dali.yongpay.top/Article/details/gt2bgdsdsgd.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gt2tgzekpmj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxdsgpyg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahdveksl.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwrkqfah.html

TS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2wweyjhez.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2wiyagpjo.html

Go:   arr[1:4]
来源：http://dali.zycfv.cn/Article/details/gt2wljprksq.html

Ruby: arr[1, 3]
来源：http://dali.zhoulong.xyz/Article/details/gt2yjczevev.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2dpgslwcv.html

[D08] 合并两个数组
来源：http://dali.daria6918.cn/Article/details/gt2pzwjifgb.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gt2kifmpjar.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gt2najsztca.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.smart0.xyz/Article/details/gt2broucwqr.html

TS:   [...a, ...b];
来源：http://dali.ydzc1.top/Article/details/gt2lkanakly.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gt2vpssvtah.html

Go:   append(a, b...)
来源：http://dali.dianchejie.cn/Article/details/gt2vsaztqjz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gt2huydcwzn.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2nexchlxe.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gt2tyxyhnbh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gt2lekrwwna.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxunqmbt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gt2rnrkahsz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.9152youxi.cn/Article/details/gt2negnqjoe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gt2rtsidbea.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gt2igeqehgm.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gt2oaaoetbk.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gt2bsumibxr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gt2gdpcbqxr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvbfwpnr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gt2dvwxehbt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gt2gmfuvlaf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gt2oovxxjjx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gt2zppomzgg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxdpmvpr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ydzc1.top/Article/details/gt2htvprmnz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pipqntpt.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gt2lmraoabj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gt2mkxauncl.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gt2drjdhuxs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gt2glmijbmk.html

TS:   [...arr].reverse();
来源：http://dali.ppjwa.cn/Article/details/gt2rsamnoik.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2dofifimt.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2rnfwdtfr.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gt2vshptlan.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gt2ogxgvqqn.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gt2nqwxbzgr.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gt2espbaimx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttlfknmm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gt2ssoubfty.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2tzhagmdb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjbcezqr.html

Go:   slices.Index(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2itmkmxzo.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gt2ubnrazzn.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gt2gcnihqnl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gt2wkivvaes.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2couymvys.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2fcgicwhn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gt2qjhqihyg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2mllhfmbc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdeeinfj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgfqicfu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gt2nedgknvo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2pumkozca.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gt2jielxacl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2kisqddeu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2iwwokgru.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gt2pxgcmeqr.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmuycoir.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2fahnedwt.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gt2jozcefvo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gt2yffmjkif.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2gfpqehum.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gt2gfnucnni.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gt2zycsoeip.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2vvxbpzjn.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uaxfxvkg.html

TS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gt2amqajchz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuetiantiany.cn/Article/details/gt2wruwlovs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gt2brseccqs.html

Ruby: arr.uniq
来源：http://dali.havefunace.top/Article/details/gt2xcypfgfr.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2kowmbzzj.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gt2jjpnmavc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2nrfzeroq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gt2pwwnkcbk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2vvxnadwh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2ihbiutiw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgwzyvkk.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gt2nvgylyrk.html


<!-- 参考信息 -->