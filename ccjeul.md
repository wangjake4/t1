代发 wailian999

Java: if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnbemzlr.html

Go:   if data == nil { return }
来源：http://dali.jinqigufen.top/Article/details/gtqtrerjvq.html

Ruby: return if data.nil?
来源：http://dali.cheryme.top/Article/details/gtyuadjpzb.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gtnvhfjkxy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtcceyxrgg.html

C. 函数与作用域
来源：http://dali.daria6918.cn/Article/details/gtoxbxngvn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gttezynyrr.html

[C01] 定义函数
来源：http://dali.daxiang520.top/Article/details/gtxtafufvj.html

Py:   def add(a, b): return a + b
来源：http://dali.ivvv.top/Article/details/gtlnikmdah.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtpvilkjta.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtmbirapya.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtyjwhljto.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtpbofepuq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gtvqeyodze.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gtofgowjfh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgqrfjryr.html

[C02] 默认参数
来源：http://dali.ehwqpu.com/Article/details/gtqawhzuav.html

Py:   def greet(name="World"): return name
来源：http://dali.pengpengdd.cyou/Article/details/gtlgmhquhq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jyoumei.cn/Article/details/gtyzebqlqu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmtfspxty.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtggrhvmtt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlukaatm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gtafslgceh.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gtvibxtktt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gtduquwlaf.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawvghtfq.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gtitiuhunb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sxryk.cn/Article/details/gtsklazqqj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtygtolmkl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gtprvcdado.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gotoacloud.top/Article/details/gtzbzdwdeo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gtgwcrhntr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdrcgxox.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokgyztgf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiezcxacp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shuidangran.top/Article/details/gtxswknqqt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gtmroubpex.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtkiljhsti.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cqqwz.cn/Article/details/gtpurmhaqu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangshuangyany.cn/Article/details/gtiychbyla.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gtnnoqjsuo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtjsuqezmq.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtkkffsgbg.html

[C05] 返回多个值
来源：http://dali.mhx1999.top/Article/details/gtghodhboy.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtjltgxyut.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gtxlfmylbw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gtufmbhksm.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtnlpvbnlt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcpozpdk.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gtdupopaeg.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtdzvahwdo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gtexxuzvlp.html

[C06] 匿名函数 / lambda
来源：http://dali.wangdashe.top/Article/details/gtftfspdkl.html

Py:   square = lambda x: x * x
来源：http://dali.iojbl.cn/Article/details/gtdgkmdkaj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tian-w.cn/Article/details/gtzadpkiou.html

JS:   const square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtnhfhnezd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltjmkvgt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sysykeji.top/Article/details/gtmkixojgg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtajuhksks.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gtwtgpdqum.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtmfetvtza.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gtzpnuyxxq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gtyyhzvlvx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtbcaoadtb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvjpyytg.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gthgjhuynk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.mhx1999.top/Article/details/gtcodznvzy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guannengcc.top/Article/details/gtlltmhhby.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gtbcevgcll.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnqzz.top/Article/details/gtngqnxokf.html

[C08] 闭包
来源：http://dali.mhx1999.top/Article/details/gtsczoxkiy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jyoumei.cn/Article/details/gtmhiioabz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtkgmjxewm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtmogycnlt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtwbcmcvjf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gtiwoiwjpq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ehwqpu.com/Article/details/gtyylljyap.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gtvqlnmslz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtzbkshwpu.html

[C09] 递归
来源：http://dali.zhoulong.xyz/Article/details/gtzhupbubs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gthnpvcout.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtpnoyuiop.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtmcgnzxty.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtdzqmdfbr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daxiang520.top/Article/details/gtdnrckhaq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gthewunqgv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtnjtntyqc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gtxhuhurxx.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gtvpnsltwa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sufxvd.cn/Article/details/gttsgcbzay.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gtzchdcesv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtjqfarlii.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gtrescdokn.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtzukkbefa.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtvgyxtxcy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gtnfeosunz.html

C#:   块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gttifoawoa.html

[C11] 模块导入与导出
来源：http://dali.jlsjyb.cn/Article/details/gtrnjamtdp.html

Py:   from module import func
来源：http://dali.shangyingyoupin.top/Article/details/gtiglmbekp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gttczzemun.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtcmcbdmzy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhongyouzk.top/Article/details/gtcwafpfxh.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gtgbnhtfes.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cdnleiting.top/Article/details/gtxsdaixfn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gtiaphkovl.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gtiukqyirp.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gtiecqzwzd.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gtlhftrjbh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.smart0.xyz/Article/details/gttbdbgznj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtlpwzjupg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtxhftbyju.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fengsongda.top/Article/details/gtpwwgwnhq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gtstifkihv.html

Ruby: -> { puts "run" }.call
来源：http://dali.316326.xyz/Article/details/gtwlbkmtoo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gtmdjbdxmk.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gteomqibhq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtezzbstcb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtdnswdlgh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangdashe.top/Article/details/gtxaokaqry.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtboczrrvd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrgysnbvp.html

Go:   func add(a, b int) int
来源：http://dali.andypj.xyz/Article/details/gttvjabbss.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gtdbpwpalx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yangfankeji.com/Article/details/gtsgqldnkw.html

[C14] 泛型函数
来源：http://dali.jinqigfzy.top/Article/details/gtqihxfqhn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtmeyfuizi.html

PHP:  // 无泛型
来源：http://dali.birdmap.top/Article/details/gtbmbaqand.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gthqqcrjzp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelrrigop.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtqzttraxt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gtguvckpgk.html

Ruby: # 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtoxnysghr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gtvubjzzkc.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gtoipcoqth.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gtustrcnwo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtwjrkzrli.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtaossgtom.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gtfmdliwue.html

Java: // 无解构
来源：http://dali.daxiang520.top/Article/details/gtmskdshzz.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gtuoljplfy.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gtakrjcsqu.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdvhptqd.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gtrgigxybr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gtsqcpnwfw.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gthrezhvbg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gtbsdxcjog.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cashguo.top/Article/details/gtfeyeolka.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsulvmyn.html

Go:   // 无重载：用不同函数名
来源：http://dali.meibo888.top/Article/details/gtdjpvjmxp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gteslntlyh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtasyqddcv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxfdcocer.html

D. 数组 / 列表 / 集合
来源：http://dali.hysaishi.cn/Article/details/gtyhroabxd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyduekpg.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gthjtuitkb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gtuwpnhkwp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gtsnkhicgz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtysgeidsc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykxjdbpe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daxiang520.top/Article/details/gthkbupvva.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gtjqasgxfe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shzxlz.cn/Article/details/gtyxihvwsm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtryywpjvx.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gtldgznyhy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gtvkelztnr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.snrcjt.cn/Article/details/gtqoijayee.html

JS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtaagncwzi.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtnawitszu.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtoktbumqo.html

Go:   arr = append(arr, 4)
来源：http://dali.iojbl.cn/Article/details/gtxxzejmek.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtpftiwxpq.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtymlzebmn.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gtnnmmqfqw.html

Py:   arr.insert(0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtrhdbcwjs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dianchejie.cn/Article/details/gtasucghrr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yvedp.cn/Article/details/gtxcahzxmf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtjinghkkb.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtoqicqfch.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.c1oappe.top/Article/details/gthurjhfmr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gthpcmzhzg.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gtzamqyvob.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gtrsqscapl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gttgqnllyr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gtfkvtqcwv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gtozfktsva.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtskfgnyoz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gtpzpudosx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gtusyyicdr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgxxedpw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfaivfvr.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gtyklnowgl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtypfgioin.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gttbjjmabi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gthmsfvddn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigfzy.top/Article/details/gtnelqahpb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvljzihi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gteolmhozb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtjuhhbojl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtyvxrvkdz.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtbemgviot.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtezoqqmfw.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gtfvgeavqs.html

JS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gttkypozfp.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtkyyqvkhh.html

Java: list.size();
来源：http://dali.kuanghao11.cn/Article/details/gtvrubyxrs.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtgnvxznud.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gtjsyqojnh.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gtblgzcxie.html

[D07] 切片 / 取子数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnuxjlyzd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gtkhpneddn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shuidangran.top/Article/details/gtdbedcjpa.html

JS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtsuufwfpg.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtbnvjbjhj.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtdgaljqrm.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gtqckcbpwt.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gtrfrgmmwt.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtvxmlftnp.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gtbwrgcwtq.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtgqpkoney.html

PHP:  array_merge($a, $b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpcwedeu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gtshpvcizj.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gtswmjuwfq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gtzjrnmbfj.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gtysluglax.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fzhhl.top/Article/details/gtrtgwfqub.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtgfpgahhb.html

[D09] 排序（升序）
来源：http://dali.hammf.cn/Article/details/gtxcgnwiqg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtwfhdonwv.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtcyhsywpb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gzhubu.top/Article/details/gtryvgtcwq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guannengcc.top/Article/details/gtrsfqfofk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gtiavejbyc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtxdxwcyoz.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtwxdqekxn.html

C#:   list.Sort();
来源：http://dali.nanxinkj.top/Article/details/gtvrykjvxl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhixingplan.top/Article/details/gtimsmdhyx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gteuzmycqz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtpgrkzziu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtromnwlte.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtkymxjimh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yanxiufei.cn/Article/details/gtlvhvivku.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gtdqfkrqoj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gtkegxjtew.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sweek.top/Article/details/gtnwyxqlsb.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gtrcbjldyh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gogol.net.cn/Article/details/gtlpcqbqot.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtacfkwcha.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.svipenyu.cn/Article/details/gtnsvxzfij.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpoxeocs.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gticqdvzet.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gtzqzhpgxx.html

Ruby: arr.reverse
来源：http://dali.hysaishi.cn/Article/details/gtyktmheas.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gtzzpwsypa.html

[D12] 查找元素下标
来源：http://dali.gzhubu.top/Article/details/gtxgjahlsn.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenzaomai.com/Article/details/gtocvakddb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gtbowvzgpx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtbxipuxmo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtfvzhannd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gtedftkpqm.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtnipeutkw.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gtrxbmepta.html

C#:   list.IndexOf(x);
来源：http://dali.zhongyouzk.top/Article/details/gtidktuuig.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtoqvwmnxj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtechqqtzw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gttxnetypt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtcvtlkcih.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gthczkjane.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtxaqrlysy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gtanahwvwi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gtaygcqmke.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtpupbmvez.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fzhhl.top/Article/details/gttrbbaqlf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gtkseebxcy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtdytcvjss.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtoqcqxpqd.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtihevyjnn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gtentjvqld.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtajvmidbs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gthueingwi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gtrjnspyyi.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gtqzeikojd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gtudwvckom.html

PHP:  array_unique($arr);
来源：http://dali.chenlongwang.top/Article/details/gttorwoebk.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtnqnuudhd.html

TS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtfjjpxstl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gtomsbozcm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fzhhl.top/Article/details/gtfzzixtkd.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gtmzkxkfdp.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gtlscfdzht.html

[D16] 求和与平均值
来源：http://dali.ydzc1.top/Article/details/gtqxrthvsx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.andypj.xyz/Article/details/gtlhieknca.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtqutthjwh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gtmffoajrb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtivwecahg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhengqikj.top/Article/details/gtuljvkymw.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gtivfboksz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gthfmbeynl.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gtaitdxrsd.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gtewpgeocy.html

Py:   max(arr);  min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtwbcvmdlg.html


<!-- 参考信息 -->