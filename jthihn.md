代发 wailian999

Go:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2enebxmjb.html

Ruby: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2elvhyjzx.html

C#:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2eivmlmuf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxinkj.top/Article/details/gt2gdnsondj.html

Py:   if not data: return
来源：http://dali.havefunace.top/Article/details/gt2czljctgn.html

PHP:  if (!$data) { return; }
来源：http://dali.daxiang520.top/Article/details/gt2kjcqnwae.html

JS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gt2bplnrokn.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwnsmggq.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gt2hteemcoq.html

Go:   if data == nil { return }
来源：http://dali.shzxlz.cn/Article/details/gt2tesxnllv.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gt2idsfxjmz.html

C#:   if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gt2fmgsiwqe.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2xmqwyoij.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gt2xtkxfxgu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2sarwnxja.html

[C01] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gt2qfibrmji.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gt2zxbuxnyj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2zlzeviut.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2gxgrldze.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2ovizukhf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2pgghuxdl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2uiuquqiq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tianlin.xyz/Article/details/gt2kvldiyai.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gt2ceehrcvk.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gt2udecthym.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gt2wfcemuhy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.meibo888.top/Article/details/gt2btfxnhwr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2xjnoutvv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fmzazvyg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sweek.top/Article/details/gt2vwbdgygu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcgssfpp.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gt2sltdtcmi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gt2mxckyhlp.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gt2mhrmptsl.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gt2uuvhloab.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sweek.top/Article/details/gt2ynpygrah.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gt2rmdimlkh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gt2ozbynmex.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gt2jkenjtdb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gt2cgmgjqma.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cqqwz.cn/Article/details/gt2rsbgwswq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tianlin.xyz/Article/details/gt2jdedwntk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sweek.top/Article/details/gt2chmlwkeq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dashuyun.cn/Article/details/gt2nftcevzj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.havefunace.top/Article/details/gt2qzcvhcto.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gt2zcrpwnbi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2uxmahcbj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gt2fxayezbm.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gt2pvzlzucb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gt2yddtffyy.html

C#:   f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2xdgwyikx.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gt2rwtozqqy.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzrdubdi.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gt2fnforijv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gt2qyqncfex.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gt2gtsflqae.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gt2iastepxa.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gt2upefxfnt.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmghfmsr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gt2fatjztgl.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gt2xzpvqvrs.html

Py:   square = lambda x: x * x
来源：http://dali.fzhhl.top/Article/details/gt2bddaeoww.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iikbtdxf.html

JS:   const square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gt2uhqebyvj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shuidangran.top/Article/details/gt2lhkohblr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2fjiikyit.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nwbrower.top/Article/details/gt2ifjshtss.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxinkj.top/Article/details/gt2esvlwxkh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2enewufuw.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gt2bfctguzp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gt2wfrrxdxl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yaprhqzd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnqzz.top/Article/details/gt2tfqysjch.html

TS:   arr.map(String)
来源：http://dali.zhixingplan.top/Article/details/gt2jpfaijbb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gt2yedppncp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gt2fsqgdmrl.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gt2wnlrmctt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gt2uubnvekg.html

[C08] 闭包
来源：http://dali.yanxiufei.cn/Article/details/gt2idcacktx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gt2fkuhaihy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.316326.xyz/Article/details/gt2aoepottp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2auhtujzc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2xkptbsal.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gt2xfryvfyh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jiagoushi.top/Article/details/gt2caqjfjvw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdohwlqf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gt2vpvjbhul.html

[C09] 递归
来源：http://dali.0kj1m.cn/Article/details/gt2hychgywq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gt2jnjdosfs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oflryqmp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtroadkl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gt2apgwdxjs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gt2mjdneect.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cdnleiting.top/Article/details/gt2mydpvvbh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nsbxowai.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gt2wojefkjn.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gt2iuaoheyi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xinyue.icu/Article/details/gt2umivhkkf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gt2heuzlmjv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2xodxxpai.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2xfujhmub.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2ppaeztuw.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gt2szqsrxkd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fengsongda.top/Article/details/gt2hmttrbaq.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmyxzeg.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gt2fkosrxhq.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gt2yhfwpzyd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dianchejie.cn/Article/details/gt2kkqmvipk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gt2rtnjxpls.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhengqikj.top/Article/details/gt2wjqjzizr.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gt2satbquel.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtfggimz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gt2gprehgqq.html

C#:   using System.Text;
来源：http://dali.shzxlz.cn/Article/details/gt2utjyanoz.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gt2mekyopks.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258888.top/Article/details/gt2ixcuvgaj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gt2wfmtnddu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gt2yjjbgeor.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gt2uaxsiryr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gt2sftyktyr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cucudq.cn/Article/details/gt2wgsiaqie.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gt2rdhfxqsp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sweek.top/Article/details/gt2ktejykxc.html

[C13] 类型声明 / 类型注解
来源：http://dali.hysaishi.cn/Article/details/gt2zdqzeatr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnprehr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftplmjpz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gt2krbloybj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2qdjtmfeb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2bsqeyyze.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gt2jggxrgjf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wotxeujd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gt2jweamlbp.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gt2yscpjseq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kykbbgew.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkgijbwe.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2vnsshpiu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gt2odqyuozo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gt2ogabgzvp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gt2etovguxf.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2jvhhewmc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pswzlqsg.html

[C15] 解构 / 展开参数
来源：http://dali.redwolf501.top/Article/details/gt2ylgsigri.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.316326.xyz/Article/details/gt2tzerkjoe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gt2znukrtui.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2wrfwwbuw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gt2aevvcvtk.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gt2tirnaqev.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgmlozer.html

Ruby: a, b = pair
来源：http://dali.cheryme.top/Article/details/gt2etwqsusl.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gt2gjkmsfmn.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gt2klldmnej.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gt2mcvqsxgd.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gt2ohlymwjf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gt2yikwdxbz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gt2zksnrtie.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gt2qrnluqqf.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gt2tdcmoymu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gt2uopsjlpt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuanzx.com/Article/details/gt2sonqccla.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2cmbxgvnw.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gt2nwayjscd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upbcfcpj.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gt2irzfhuka.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guannengcc.top/Article/details/gt2hgpwsqck.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gotoacloud.top/Article/details/gt2nrcesnhh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gt2tpxzsass.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gt2egfenzjr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gt2pflixxki.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gt2xcxkysnc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aizwys.cn/Article/details/gt2wqvfvxdk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gt2cvpxircd.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gt2uqtoccry.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gt2fzpoyqed.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gt2vvhmbgly.html

JS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2ajyjvgsi.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gt2yvhjcfsw.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gt2tzixuekp.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gt2ckpgtqbs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evlhtkjx.html

C#:   list.Add(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2xyptehwl.html

[D03] 在指定位置插入元素
来源：http://dali.cdnleiting.top/Article/details/gt2obxhdhss.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gt2qnzhadsa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ppjwa.cn/Article/details/gt2ytgyfrgg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gt2iynocbuu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2exynqizz.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gt2btzeisio.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxinkj.top/Article/details/gt2qqgakamo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guannengcc.top/Article/details/gt2xucybnre.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2fzcqckny.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gt2gwjijvdo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gt2hogsscyi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zycfv.cn/Article/details/gt2sgaulaau.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gt2bjqdgrnn.html

TS:   arr.splice(0, 1);
来源：http://dali.jianghu66.top/Article/details/gt2zswmtlus.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2aerksdvh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gt2wxhxgmen.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gt2xuckxikc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gt2dbxrrimk.html

[D05] 访问与修改元素
来源：http://dali.sufxvd.cn/Article/details/gt2cczirvvt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gt2suzdsmfo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxiftorw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gt2nxnemapk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gt2evlnqfaj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gt2ftmskxox.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2jqupujjf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2bfcmhwgq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2rdotrcpa.html

[D06] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdvsimyp.html

Py:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2twmiucaa.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2otkchlgb.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2bvihtsgd.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2ijbjzwnw.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gt2kujadjtg.html

Go:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmfyabvo.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gt2thabuwvs.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gt2upoaskmd.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxheiigf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzdukpag.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cashguo.top/Article/details/gt2vxwryrxa.html

JS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gt2lxpgfhpj.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nniwbgoq.html

Java: list.subList(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gt2ohwpslzw.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gt2ejuotupd.html

Ruby: arr[1, 3]
来源：http://dali.xylfe.cn/Article/details/gt2mowawtaz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gt2rcdwxzch.html

[D08] 合并两个数组
来源：http://dali.dashuyun.cn/Article/details/gt2kieszrrv.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gt2wismmwkl.html

PHP:  array_merge($a, $b);
来源：http://dali.kuanghao11.cn/Article/details/gt2obkfxaxk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gt2vyaaxdrw.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gt2ftkqmaqp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2enlhtgug.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gt2upfccqse.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gogol.net.cn/Article/details/gt2esdoqzkg.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2kvaqbwhb.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gt2reyvdpdh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gt2fvbljjax.html

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2knkqbjfe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shzxlz.cn/Article/details/gt2rqykemzm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sweek.top/Article/details/gt2vuunrfeq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gt2xqliupib.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2myakjclk.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gt2enghvbjp.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gt2zptizzcw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gt2sibcmwwt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fzhhl.top/Article/details/gt2eemijjpe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gt2dlezigzm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gt2zreegnpn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gt2rtaheyuc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgkkexue.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gt2oategwse.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gt2mimrgnmw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tssudzlp.html

[D11] 反转数组
来源：http://dali.ybcxt.top/Article/details/gt2nfyrqmwv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uoooiyra.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2wiqwacbo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gt2rxrlnacj.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gt2vexwmjey.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gt2obcjkzrh.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gt2zendbhbo.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzjtynuo.html

C#:   list.Reverse();
来源：http://dali.meibo888.top/Article/details/gt2qhdkgjnt.html

[D12] 查找元素下标
来源：http://dali.jinqigufen.top/Article/details/gt2lfwdmkvr.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gt2zoodfyxo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuxming.cn/Article/details/gt2mdiskxrx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gt2smgozmll.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2qdkpafsy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gt2krxhelrh.html

Go:   slices.Index(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2hsuiqjmz.html

Ruby: arr.index(x)
来源：http://dali.mhx1999.top/Article/details/gt2bkkqelfj.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gt2ilqniyle.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gt2cgymskac.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2szipdaqw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gt2bbggpbyd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gt2qdxzlbmr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2hbwabfze.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2ccoygjar.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhceqncz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqxqmnsv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2vkvrivbg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yvedp.cn/Article/details/gt2shzhkbhy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2mustjytt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2kxbepgor.html

JS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqvstopq.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gt2jjvzvjfz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gt2gcuutktc.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gt2wbvdjtva.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gt2ccmhzqbn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2nqbnzaah.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gt2scbtowfr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gt2fskzhopb.html

PHP:  array_unique($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2dtweucot.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2fctojiht.html

TS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2yvggkoex.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zdqjudy.top/Article/details/gt2uomidage.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gt2cmbmmnvy.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gt2xwvczkqx.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2mhxuinea.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gt2mccstntv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuxming.cn/Article/details/gt2adrioxnf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gt2xrmzpfcp.html


<!-- 参考信息 -->