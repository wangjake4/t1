代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpjxbznr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gt2gprpchfb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hfpthk.cn/Article/details/gt2bwuauioq.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gt2sufjfmsa.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gt2yjslirbf.html

[C03] 可变参数
来源：http://dali.c1oappe.top/Article/details/gt2zfyzukfs.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gt2vhufjasm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gt2cvpcyyuq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gt2fvoleuod.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqtzhalq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shuidangran.top/Article/details/gt2skgpszpt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.smart0.xyz/Article/details/gt2ngznlimg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tianlin.xyz/Article/details/gt2xqjzfzox.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gt2nrngqmac.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gt2zhfihpku.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gt2xakmunug.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhengqikj.top/Article/details/gt2cuacdocd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2gniwgokk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gt2hjsenhtg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gt2zolnapwr.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gt2hmlwsozy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gt2atwnovdi.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2aaneryny.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gt2uavqlzmc.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gt2tonkefgc.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gt2hyiavjgu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangdashe.top/Article/details/gt2uxkcbamj.html

TS:   return { a, b };
来源：http://dali.hnqzz.top/Article/details/gt2galhuurm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xziqi.cn/Article/details/gt2brcsiizw.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gt2ycswehkv.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gt2nijbczxd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daxiang520.top/Article/details/gt2plgqvgyk.html

[C06] 匿名函数 / lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2gshojqrg.html

Py:   square = lambda x: x * x
来源：http://dali.sysykeji.top/Article/details/gt2ooyxcoxa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sysykeji.top/Article/details/gt2uhzivhav.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2divvrwpt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gt2rcmxktha.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cashguo.top/Article/details/gt2ilgsjdtl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.316326.xyz/Article/details/gt2fosepdyj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuxming.cn/Article/details/gt2nmdvydtw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gt2clmufedp.html

[C07] 把函数作为参数传入
来源：http://dali.sxryk.cn/Article/details/gt2adkiqqqo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gt2hlokogqi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2rjmtfoti.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nwbrower.top/Article/details/gt2qfjysfsq.html

TS:   arr.map(String)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvgwgbou.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2mjcppjhi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gt2mhbeokoe.html

Ruby: arr.map(&:upcase)
来源：http://dali.zycfv.cn/Article/details/gt2vwnfxlfp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gt2sokpqrdc.html

[C08] 闭包
来源：http://dali.sweek.top/Article/details/gt2losxzlfs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gt2aioxrlyq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxinkj.top/Article/details/gt2qnonoodu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gt2lyffjcky.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2imddfcwa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gt2dtbmiqmp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gt2pvnpsrbw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnqzz.top/Article/details/gt2tuzxaosq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2ozzxmftj.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gt2aawttzlm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gt2csnbhdso.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gt2mgfozcxx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gt2gyterzgg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gt2cdzmoyek.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbtbtysg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2izsyfrxk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gt2pxjvryss.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2njapfsgq.html

[C10] 变量作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2oeyelozc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gt2cngxomtt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gt2xyvhdimj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2tadvuffo.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2ahlkltqi.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gt2dpopzqyy.html

Go:   花括号块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2oqwdojnu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.andypj.xyz/Article/details/gt2pnheyjui.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gt2kkoyvuen.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gt2dnmhalqa.html

Py:   from module import func
来源：http://dali.quarkkingdee.top/Article/details/gt2chularun.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gt2uzjchibv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gt2gjadnurq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jyoumei.cn/Article/details/gt2gksprdgv.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gt2zbehwirp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gt2ittcmrpq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gt2spykfpxv.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gt2uzzfqjzx.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gt2nlaboplh.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gt2bniuqnmd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gt2wslneknd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gt2qhnsbyns.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gt2tlckbytd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gt2kxynpexd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yonumen.top/Article/details/gt2fwceupyk.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gt2cjlrhdds.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2nnskrzzf.html

[C13] 类型声明 / 类型注解
来源：http://dali.sysykeji.top/Article/details/gt2lvmtgudy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gt2yumsbjoz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2ytjomqsy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gt2canwewcc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2btgphtrb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gt2bvxscpqq.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gt2czjltidg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmyvrwrp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gt2fybydhzn.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gt2wxopyvef.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuxming.cn/Article/details/gt2hmfgsjae.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2uedxrgka.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2gnxpllme.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gt2dscgqqum.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gt2tievauel.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gt2ivurteci.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2vvavqyvc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ydzc1.top/Article/details/gt2vrxanwqq.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gt2xoulpild.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cqqwz.cn/Article/details/gt2rpqlfdef.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gt2mybazamm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gt2bdkjsike.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fzhhl.top/Article/details/gt2yuzqkljv.html

Java: // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2xwlpznpl.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gt2wugrktaa.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gt2wrmjrvkp.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gt2iczppmvo.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gt2gkypeous.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqmwptld.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gt2gxscfzsg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gt2wursceke.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwhqpfut.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hammf.cn/Article/details/gt2wivqpgxx.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gt2ajnttalp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yonumen.top/Article/details/gt2pmwxpejq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gt2tvbjckrw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2uhksupys.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzxcwlku.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2sfaayrrw.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gt2bgnxpagj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gt2oqromkxt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guowangkeji.top/Article/details/gt2ndptvykj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkvdfvht.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gt2pvdlaybj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yueranfly.top/Article/details/gt2noyihgua.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krdpwkek.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gt2gimiwtpb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gt2tkyjvfuo.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gt2mheiwneq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gt2byyuztqp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gt2fwwzsrxs.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gt2qbgqionn.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gt2djrfultp.html

Java: list.add(4);
来源：http://dali.shzxlz.cn/Article/details/gt2fbvbflyg.html

Go:   arr = append(arr, 4)
来源：http://dali.yonumen.top/Article/details/gt2xowfeqya.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxwdkogr.html

C#:   list.Add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2gglmfeob.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gt2yquimqdr.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gt2mrhxjegn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258.top/Article/details/gt2fknuoqcb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shuidangran.top/Article/details/gt2trkbrzgj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2klqvndqt.html

Java: list.add(0, 0);
来源：http://dali.sysykeji.top/Article/details/gt2iuksbwrx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gt2ynusaysg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xinyue.icu/Article/details/gt2lwustkuu.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2paufmmho.html

[D04] 删除元素
来源：http://dali.hywenlv.cn/Article/details/gt2vytaxfco.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2tugvyxku.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2ntwdjmgg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gt2xassotol.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2hircuadh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2nrlgbpaq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenzaomai.com/Article/details/gt2mpxyomcf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gt2nthncvft.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gt2sefisrxe.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gt2nobiufij.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2rimgnegi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2xqsavbku.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2ldycgnuu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gt2izaikknd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guannengcc.top/Article/details/gt2uopgsgcf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2enwvhwyw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2edtybiis.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gt2ecrenypn.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2uhcwjtkx.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2jsvuyjkj.html

PHP:  count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2jksyfotn.html

JS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2bussciqd.html

TS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gt2kjsidaux.html

Java: list.size();
来源：http://dali.zycfv.cn/Article/details/gt2smejfimt.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2ggfnfevw.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gt2mznxxhsy.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gt2lthwsxjn.html

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grveiunw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gt2qotmnbep.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xinyue.icu/Article/details/gt2smtssata.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2mnpqmjmb.html

TS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gt2buyfiyyd.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2jrinothm.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gt2ahwjvgfq.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gt2iuvpvsfv.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mddnivpi.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gt2yurclpqi.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gt2fkadxjcl.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gt2gzmfzmrt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njroougk.html

TS:   [...a, ...b];
来源：http://dali.cucudq.cn/Article/details/gt2dahgjchw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gt2coztyfad.html

Go:   append(a, b...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbbrniyv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmhzemy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2vgsjrqbk.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gt2yurybjxh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gt2nsxfgynq.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2wnjebrkr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ybcxt.top/Article/details/gt2eqhouhog.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkhbqxgr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gt2kgoqrlun.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2sddfznuv.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gt2zxehphxp.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gt2teoxcqed.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gt2ragqdujb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gt2hbssaxcj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2tajzophq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2timdiehy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gt2itelgpnj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gt2qxfebgxm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.meibo888.top/Article/details/gt2emwjdqtw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gt2svmsriux.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cucudq.cn/Article/details/gt2zvyxbrrc.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gt2nmouegpm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wifgvxyt.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2fexgfjwi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuxming.cn/Article/details/gt2vxpijwia.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gt2qshyxdzw.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvxvibbx.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gt2bpmygxxv.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2hkywscbt.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gt2tbdjluht.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2feuwnddr.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gt2cawpwqdi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2skppbswt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2dknydtyf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qarscvlr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gt2ptqduyvj.html

Go:   slices.Index(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2ghwmshrs.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2yddctsyg.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhzhvfue.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gt2houwawab.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzlwvtpw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgfzy.top/Article/details/gt2oewjfblf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gt2dlaoppbm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2caryehjx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gt2ldzrjmxg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cheryme.top/Article/details/gt2dxfahsnj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xziqi.cn/Article/details/gt2brtxhqhk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2jxwysfni.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuxming.cn/Article/details/gt2iprjlwkq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.iojbl.cn/Article/details/gt2svrdbqrb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2iqjcsaoh.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2llafyksc.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gt2nhuzdwjg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gt2wekwvxfy.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2obwlgndb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2rowndrrt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2uzgizbmk.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxiigsab.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbhhbuyn.html

PHP:  array_unique($arr);
来源：http://dali.shuidangran.top/Article/details/gt2czehamuy.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2ohanvbvs.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2mxidguml.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gt2tpyoqeqk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258.top/Article/details/gt2segwtcai.html

Ruby: arr.uniq
来源：http://dali.gogol.net.cn/Article/details/gt2ajgtypan.html

C#:   list.Distinct().ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2ryzrgudi.html

[D16] 求和与平均值
来源：http://dali.zhoulong.xyz/Article/details/gt2emdbxqvx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqdbvzfn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gt2vcvaszmj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gt2oimlbhzv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gt2rujkyvgh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gt2tuowgout.html

Go:   // 手写循环累加
来源：http://dali.yj202588.top/Article/details/gt2nucirart.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gt2apdzxhrr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bndrpicf.html

[D17] 最大值与最小值
来源：http://dali.jianghu66.top/Article/details/gt2qbbrrxts.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2eschhsyg.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gt2jzarqbuc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gt2gizwzjxi.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gt2amjqwiys.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sxryk.cn/Article/details/gt2hgkpsddw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2mxqeuflv.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gt2yuitrpmx.html

C#:   list.Max();  list.Min()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nitalnmq.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gt2dwuewfji.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.meibo888.top/Article/details/gt2ldzralrh.html

PHP:  array_merge(...$nested);
来源：http://dali.yuxming.cn/Article/details/gt2fjsxfoxj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjakrckx.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gt2mpgxjnjj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubjdnfgs.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sksajrtk.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gt2pghfnblr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2amjuwqrw.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gt2djnplxsp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gt2qplevwtt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gt2bjfmfmeg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sxryk.cn/Article/details/gt2rujkbvna.html


<!-- 参考信息 -->