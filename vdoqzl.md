代发 wailian999

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2jsljiwfi.html

Ruby: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekruhtlx.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gt2cdrfmdyq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2lgkyeemu.html

Py:   if not data: return
来源：http://dali.zycfv.cn/Article/details/gt2wzctwmpd.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gt2wlsvqwbh.html

JS:   if (!data) return;
来源：http://dali.jinqigufen.top/Article/details/gt2hlzfxjzx.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gt2bibajycm.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gt2pxsxccqv.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gt2jemzmhkh.html

Ruby: return if data.nil?
来源：http://dali.bjfxy.top/Article/details/gt2mcdpafoy.html

C#:   if (data == null) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfsizjtn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2gtxfvpvt.html

C. 函数与作用域
来源：http://dali.tian-w.cn/Article/details/gt2ztccnglv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2tpvfpbax.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gt2yykskdtq.html

Py:   def add(a, b): return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eleogvyu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2bivdjwun.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2tpcffwje.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2ediinyvh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2elsdqshl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2qmueurzx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xylfe.cn/Article/details/gt2szbiieyf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktgpmntb.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzojlbu.html

Py:   def greet(name="World"): return name
来源：http://dali.cqqwz.cn/Article/details/gt2qpsxpfkm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhixingplan.top/Article/details/gt2fpbpoedg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2jhlgpheb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dhasxyrb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2yoyzjzgh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gt2nqotvdms.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhongyouzk.top/Article/details/gt2fehopyhm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gt2iyrizgup.html

[C03] 可变参数
来源：http://dali.hywenlv.cn/Article/details/gt2xexdirqy.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gt2sgrhutfw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jlsjyb.cn/Article/details/gt2fbwdotei.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gt2xaudtonz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gt2fbyieajw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gt2tdkkwkzn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gt2blqpqrfj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuanzx.com/Article/details/gt2tscjvhgn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gt2jqtnrupt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnqzz.top/Article/details/gt2siskaxsk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhengqikj.top/Article/details/gt2culocbah.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nckrbbpg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2ftnvhkpu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqgxteg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgufenzy.top/Article/details/gt2cduoewrm.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gt2mtutwxit.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gt2rmhoemll.html

C#:   f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gt2fvurofms.html

[C05] 返回多个值
来源：http://dali.cucudq.cn/Article/details/gt2qvvzvcwx.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2sggwipzh.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2cisnmyaj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gt2lbpkorkd.html

TS:   return { a, b };
来源：http://dali.c1oappe.top/Article/details/gt2apcpioph.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gt2bkurppqd.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2bmfchcsy.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gt2fmsqbfof.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gt2vodxezpf.html

[C06] 匿名函数 / lambda
来源：http://dali.yvedp.cn/Article/details/gt2wbmqpuvl.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gt2rcrpwvbf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gt2upeasrjj.html

JS:   const square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2eowglbzi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gt2orlmhhsk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2ootvcxlp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gt2xoiseaic.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gt2kqimdcaj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gt2naqhwkqc.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gt2gfhifexi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2daffllxi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xylfe.cn/Article/details/gt2kbawopax.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.smart0.xyz/Article/details/gt2xdxzgqlo.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gt2aqycjsvm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gt2uhtqxnaj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnxiangtu.top/Article/details/gt2oooqmalf.html

Ruby: arr.map(&:upcase)
来源：http://dali.hysaishi.cn/Article/details/gt2sknoaust.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gt2ngggxbhg.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gt2bxalocde.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gt2smucslkl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gt2jzwrlfdi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2xblantda.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2tsdgulon.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dianchejie.cn/Article/details/gt2uytdeqsc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gt2epuauifu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gt2qtwznehs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2jhhnykfi.html

[C09] 递归
来源：http://dali.yonumen.top/Article/details/gt2qtlwgvmh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gt2pcozewry.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gt2fypisriz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2fmrzsvxj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gt2dqzevpbs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuxming.cn/Article/details/gt2rdattmzp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gt2zwhsafds.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gt2xdjkjjot.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gt2jnoclvbd.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2anjgbfnn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuanzx.com/Article/details/gt2toebpzyp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shzxlz.cn/Article/details/gt2jnjswgnm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangdashe.top/Article/details/gt2jggwzmof.html

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gt2gfoyabzy.html

Java: 方法内为块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2gckcluiy.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gt2udrfkogf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gt2vuaemifu.html

C#:   块级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2cyguoztc.html

[C11] 模块导入与导出
来源：http://dali.tian-w.cn/Article/details/gt2mzpjpbca.html

Py:   from module import func
来源：http://dali.havefunace.top/Article/details/gt2vwdphhkg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tianlin.xyz/Article/details/gt2nustjllh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gt2mzqjsonu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.haohaochexian.top/Article/details/gt2vouvldgx.html

Java: import java.util.List;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntbcvvtl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gt2zguajpjo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gt2gubowzvc.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mhszyxpa.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gt2sfvcfyjp.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gt2gngcrjqf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gt2jvtdpawk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phwylwup.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gt2auzosvhd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gt2dgwjrzqw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.kuanghao11.cn/Article/details/gt2xnftmedn.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gt2irfaqhpv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2ejiamnlr.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gt2bqvwvkyc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuanzhike.top/Article/details/gt2dorncibd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gt2lxlusxsp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gt2ilsqgdqk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tvoeqkjr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlbkvjyv.html

Go:   func add(a, b int) int
来源：http://dali.ydzc1.top/Article/details/gt2gawknqie.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gt2ctwbmtlu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruztgrrt.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gt2ydifsntn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gt2hsbgfrmb.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2ftpnnqmk.html

JS:   // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebdwrtho.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guannengcc.top/Article/details/gt2edklbpzb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shuidangran.top/Article/details/gt2tcxgwaky.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gt2tfwcnakw.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwipeqvw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gt2pwekatcd.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejdwfxzv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gt2fyurltdh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.c1oappe.top/Article/details/gt2wrjvsvrk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gt2pqmwzkgn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2npnvfldc.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gt2qbgqjtmb.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojcoofzn.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gt2prszltsg.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigufen.top/Article/details/gt2inuokjov.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gt2yktfulzk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.havefunace.top/Article/details/gt2guxsonkw.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gt2wveukdcw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gt2tlarohup.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2vjyjrjyr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gt2dljgirks.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gt2grbjemuu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gt2nrwbiwmj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gzhubu.top/Article/details/gt2lkyetiun.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2enpnwtjb.html

D. 数组 / 列表 / 集合
来源：http://dali.cashguo.top/Article/details/gt2bgzmuudx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2skndemln.html

[D01] 创建数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gt2kertleuv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhengqikj.top/Article/details/gt2hfwstvbp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnaczigb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gt2wtbeqoir.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gt2vkwebupf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gt2yxljyrfc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gt2teqrqjze.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gt2enpabgjv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxygozyj.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gt2vgamzlnj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gt2luzaqpvs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xinyue.icu/Article/details/gt2slvsdevq.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2twdqkiqh.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gt2wfxnayaz.html

Java: list.add(4);
来源：http://dali.wangdashe.top/Article/details/gt2zfcibtar.html

Go:   arr = append(arr, 4)
来源：http://dali.fengsongda.top/Article/details/gt2btfyducg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gt2nmeoteei.html

C#:   list.Add(4);
来源：http://dali.xuanzx.com/Article/details/gt2lexzowai.html

[D03] 在指定位置插入元素
来源：http://dali.zhengqikj.top/Article/details/gt2xfsmgdzl.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2zvumjndk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.andypj.xyz/Article/details/gt2heorreja.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gt2jtfwzjqd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yvedp.cn/Article/details/gt2isuzvhio.html

Java: list.add(0, 0);
来源：http://dali.yj202588.top/Article/details/gt2azofplcv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gt2ykmoffia.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gt2shklqyjm.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2rzlwnzvz.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gt2sjbpkrka.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuxming.cn/Article/details/gt2tjeahfqn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2dzbsxqym.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gt2dghfilga.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gt2usbvjsrd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nwbrower.top/Article/details/gt2krxivobi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gt2negwvoum.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2xkjkhkcf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gt2bjyihdoa.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gt2manulwwm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gt2czvxcjkp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gt2rdmejnpk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2cgsoqfcc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gt2dbnzcbme.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilavoepb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gt2qyrxbnah.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2qkiosevf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gt2moahbznk.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gt2lzmihswy.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2whkgzlbj.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2avfhoxdj.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gt2vwdpemkk.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2xeqkyevs.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gt2zwvnqdyw.html

Go:   len(arr)
来源：http://dali.316326.xyz/Article/details/gt2bumytnog.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gt2pkpvurfu.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gt2etvooznr.html

[D07] 切片 / 取子数组
来源：http://dali.jlsjyb.cn/Article/details/gt2whafatqh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gt2kbmojcrf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gt2ttomuzbs.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2azstmezs.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gt2monltebz.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2lrckwrqa.html

Go:   arr[1:4]
来源：http://dali.zhoulong.xyz/Article/details/gt2nylbhmwr.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gt2atfgnzyl.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2zfrpvbrb.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gt2hjalpatn.html

Py:   a + b;  a.extend(b)
来源：http://dali.fzhhl.top/Article/details/gt2zastowsw.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gt2ijqsllza.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.andypj.xyz/Article/details/gt2bhcdmbih.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gt2myikiglt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2jpvtnmvf.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2amhvbuwv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gt2jrnjhsra.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2uecipubs.html

[D09] 排序（升序）
来源：http://dali.meibo888.top/Article/details/gt2erskzksj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gt2cpagphfb.html

PHP:  sort($arr);
来源：http://dali.wangdashe.top/Article/details/gt2rnseljep.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhixingplan.top/Article/details/gt2krlwywcn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gt2kxalzltx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gt2ezmqimvh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2rhnferab.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gt2bsuhupuh.html

C#:   list.Sort();
来源：http://dali.gogol.net.cn/Article/details/gt2zwxepxjp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gt2eatvaxzf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gt2dpytaxeh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gt2cjkpenmg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gt2vmnlgswg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2kepohier.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fzhhl.top/Article/details/gt2qzctrkrv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gt2hzxzlknr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gt2nleelubb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gt2usfjjkxp.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gt2uwswuzsi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gt2vgnmdwwn.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2xzkgiigd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gt2pykhlnrz.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gt2echevjbz.html

Java: Collections.reverse(list);
来源：http://dali.316326.xyz/Article/details/gt2cfeiggmr.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gt2tgyxfwhh.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gt2mmtqlmzl.html

C#:   list.Reverse();
来源：http://dali.andypj.xyz/Article/details/gt2mwpguwpm.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gt2yalfaand.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenzaomai.com/Article/details/gt2mqpqkcoi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2mutzkutm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gt2obbducmg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gt2mefqrwda.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gt2pvdnqizc.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2fxjzqemj.html

Ruby: arr.index(x)
来源：http://dali.gotoacloud.top/Article/details/gt2aurnzbwa.html

C#:   list.IndexOf(x);
来源：http://dali.gotoacloud.top/Article/details/gt2zcmnrczu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gt2crisweuh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guannengcc.top/Article/details/gt2cqgtwirl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gt2zjddvzlc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2lloiuaso.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gt2pajkwrpe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2lrsslxmz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gt2xrotgnav.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.birdmap.top/Article/details/gt2zrlqepfu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2aeoxmgka.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gt2aejfnaqf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gt2mqvikstb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2dsmaekxa.html

JS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gt2lqrjcfsw.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gt2wfqvtygp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gt2hbrnppdp.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2adhwejmn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2yjptqaig.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2awdvymeo.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2tqnjrfca.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2flkusxir.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gt2ribpfjam.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2cvzmhioj.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2tspvnmxz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gt2ipdlejxk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gt2axqznkde.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqlodawz.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258888.top/Article/details/gt2vlmfgpwd.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gt2exubxugp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2nnxcyxox.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2lmubijeq.html


<!-- 参考信息 -->