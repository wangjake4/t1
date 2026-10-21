代发 wailian999

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthpkimlmu.html

C. 函数与作用域
来源：http://dali.aibaodan.cn/Article/details/gtasvaebkg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgwgdnwxr.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtsueqdidd.html

Py:   def add(a, b): return a + b
来源：http://dali.jyoumei.cn/Article/details/gtnnweulxt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpymxmmkq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtjzfmkvyr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtorbumbfv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrhewgfig.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gtdfsinpox.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gtzfypncsb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtswyjdqoj.html

[C02] 默认参数
来源：http://dali.yj20258.top/Article/details/gtbyvplodl.html

Py:   def greet(name="World"): return name
来源：http://dali.chenzaomai.com/Article/details/gtaqtwyzib.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gtnfmyezki.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtxfvzgrig.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtuzfeqeyo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gtzdshazgc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gtwyoshoib.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gtfdlwnkbb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gtdimtcyrv.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gtdzdknojx.html

Py:   def total(*args): return sum(args)
来源：http://dali.svipenyu.cn/Article/details/gtbpliihmg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pycfn.com/Article/details/gtdazdtnfw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtezdjupiq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gtwnofuurj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuanzx.com/Article/details/gtsahpzqas.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.kuanghao11.cn/Article/details/gtdgsblzbx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gtabbygexo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtxcwfngvb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gtdflwapwz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gtjvzdhivt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ppjwa.cn/Article/details/gteysvljga.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gttbxxvews.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtsidjiens.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zycfv.cn/Article/details/gttitbpgnj.html

Go:   // 无：用配置结构体参数
来源：http://dali.sysykeji.top/Article/details/gtbkrhlpeu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtaqmneuaf.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtsjiyuojy.html

[C05] 返回多个值
来源：http://dali.tian-w.cn/Article/details/gtmvhmkoxk.html

Py:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtjkippwqy.html

PHP:  return [$a, $b];
来源：http://dali.pycfn.com/Article/details/gthcdpqngy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtawtrtreh.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtsgjwfuvj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtfzwsimji.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtnvddbtol.html

Ruby: return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtrgdlgsei.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxuanxn.top/Article/details/gtnryguewr.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gtvldpsgig.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258.top/Article/details/gtrtujvwxy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gtldbbkjwn.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gtnjcmxigy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258888.top/Article/details/gtvqwcuucf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gzhubu.top/Article/details/gtqisgdyca.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ppjwa.cn/Article/details/gtezksctwz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhoulong.xyz/Article/details/gteiowzswg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gtajkssvzr.html

[C07] 把函数作为参数传入
来源：http://dali.jiagoushi.top/Article/details/gtzltnnarh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gtclupbrtp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccrleokm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gtvbzkfowh.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gtacentclz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yonumen.top/Article/details/gtckkldoyl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gtijcevbip.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gtlxaimqne.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guowangkeji.top/Article/details/gtydtsxbio.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gtjfgpgiam.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gtaeeheksn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gtwjbjxvxl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtifckvljq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrilcyyzf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigfzy.top/Article/details/gthjxluwwa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gotoacloud.top/Article/details/gtodeccivq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gtxzjkifoc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtrbrdqbpv.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gtlpqwcceg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtiifljdpn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtesakbbia.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikufnalh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtzgngxfnb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gtomzkcpvs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigfzy.top/Article/details/gtcmcjownh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gtkmwvbsww.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhixingplan.top/Article/details/gtbrqgjfie.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtomluvxhc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tian-w.cn/Article/details/gtfolqcuep.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigfzy.top/Article/details/gtfduekrbw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yonumen.top/Article/details/gtvvmgxxqv.html

TS:   同 JS
来源：http://dali.nwbrower.top/Article/details/gtdvuztbpd.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gttszmbgad.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtsgdnnqnt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gtkaegtihm.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gtbewctlgc.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gtkhvgsqul.html

Py:   from module import func
来源：http://dali.svipenyu.cn/Article/details/gtzjhualqq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmuorpnkb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnqftcax.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gtwhfhssiw.html

Java: import java.util.List;
来源：http://dali.dianchejie.cn/Article/details/gtvunmvuhj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuojpyhjv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gtltulnmnk.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gtewdnbfhh.html

[C12] 立即执行函数 IIFE
来源：http://dali.xziqi.cn/Article/details/gtpchpbsql.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gtrtfgjgfe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gtnqqusprq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtldyfpvzp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtwyuyuwvf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gtmnvbqitm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gttxwxgrkd.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gthweumtao.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedylauzx.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtsbdwuirb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtxaiuruji.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtsobgosot.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.bjfxy.top/Article/details/gtagltmkoe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtaewpdsgf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtnofwunos.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gtepefatac.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xziqi.cn/Article/details/gthxdzutbl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gthgcubtml.html

[C14] 泛型函数
来源：http://dali.daxiang520.top/Article/details/gtkgmmnzqq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.meibo888.top/Article/details/gtzexrxcgn.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszeeqyag.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtscdpszcf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtzimsgvtt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gtvehcdxsv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gtwvxpxdrm.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtwswbbxew.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gtxouhuafb.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gtzhiyokyf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gthgxfbith.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sxryk.cn/Article/details/gtasyxixxt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtufgzfrem.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgoukyyj.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtcwkvflis.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjahbcny.html

Ruby: a, b = pair
来源：http://dali.daxiang520.top/Article/details/gtsdgiutzv.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtaakvvxuv.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gtptslmixk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.316326.xyz/Article/details/gtvkznvvjy.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtyajumacp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.9152youxi.cn/Article/details/gtvbuderck.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gtftswlhar.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtmuxjrvrk.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gtxpklewnf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglmmmbpt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gtqahdjqdc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlldsgdsp.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gtgwkgzeor.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtefufznvd.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gtxcjjdjim.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gtzywjwfop.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daria6918.cn/Article/details/gtqzcoyrgw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gtintkqpjs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gtvcksfqra.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gtgkhhaydk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.quarkkingdee.top/Article/details/gtypmsfkdg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gtmxdfgebh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.0kj1m.cn/Article/details/gtpeorlzys.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gtjhmmkpzg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gotoacloud.top/Article/details/gtggcbifsq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jyoumei.cn/Article/details/gtcxknbekf.html

JS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtihyvtpzy.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtfjvdogzb.html

Java: list.add(4);
来源：http://dali.yj202588.top/Article/details/gtewpmaskf.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtpetbqyzi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gtmaolpzqr.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gtziytaybg.html

[D03] 在指定位置插入元素
来源：http://dali.wangdashe.top/Article/details/gtgsgdwwlq.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gttbxtnfod.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtougfhbta.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ehwqpu.com/Article/details/gtmajxqzfd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtuguqbgjy.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtxaqzhqtk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daria6918.cn/Article/details/gtlhxkfxwe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgfzy.top/Article/details/gtgytgzjgj.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtboitutes.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtydxneffn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gtvqizmvxj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gtcxchiuge.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gthsoqckbs.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtymachsdj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gtvqbslkuz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gtqcmtbwtk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtzmqbhkdq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.andypj.xyz/Article/details/gtulwscfaq.html

[D05] 访问与修改元素
来源：http://dali.mhx1999.top/Article/details/gtyjhzgfui.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtexxongff.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtrkonifpl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtsxyztnmr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gtxcoqciro.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.mhx1999.top/Article/details/gtgdhzverz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtjfuuggha.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtmkpzocei.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtdgrspxrh.html

[D06] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gttoisamvk.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtllvhztra.html

PHP:  count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtrkgtjcpx.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtffgphmoj.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtdbxfawel.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gtwzffgtyh.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtremsgpth.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtbxbnednk.html

C#:   list.Count;
来源：http://dali.redwolf501.top/Article/details/gtglhtoorn.html

[D07] 切片 / 取子数组
来源：http://dali.aibaodan.cn/Article/details/gtuswqpxxm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqrqrbaz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtponggopi.html

JS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtonptowmx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtfxagabtf.html

Java: list.subList(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtefdmzraq.html

Go:   arr[1:4]
来源：http://dali.shuidangran.top/Article/details/gtojexwpbl.html

Ruby: arr[1, 3]
来源：http://dali.aizwys.cn/Article/details/gtlvdpwhbl.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtzteihrrb.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtprurlkam.html

Py:   a + b;  a.extend(b)
来源：http://dali.shzxlz.cn/Article/details/gtpzmusydl.html

PHP:  array_merge($a, $b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjygswnyg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nwbrower.top/Article/details/gthdkqyqiu.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gtfdmyrfet.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cdnleiting.top/Article/details/gtglqocktn.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gtpggwiwpm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtntgqzcxj.html

C#:   a.Concat(b).ToList()
来源：http://dali.sysykeji.top/Article/details/gtvuzjpfzx.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gthcdloxre.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtusrcgrvv.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gtmigambsi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gtfcryzpqx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gtnfxpbsex.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gtavuixrgv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthoixupfp.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gttcnylyeg.html

C#:   list.Sort();
来源：http://dali.yueranfly.top/Article/details/gtwoaanqlo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258888.top/Article/details/gtzzerjdjf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gthvfmekco.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gtvkbflqsa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtvkesgaou.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtzebyfmfh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cdnleiting.top/Article/details/gtcjqtxahi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfbwkqqx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gthigjdjej.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gzhubu.top/Article/details/gtjnozqwvr.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gthueqoonc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtmrtpranc.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gtlbmieuus.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gtucfflsmb.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtoilgipis.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gtkttaxitw.html

Go:   slices.Reverse(arr)
来源：http://dali.hammf.cn/Article/details/gtrbxjmhpo.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gteaeklyjr.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtkipetdkt.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtrxglvusq.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gtdrcwpipw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fzhhl.top/Article/details/gtmmorldjb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtvkpkwdfg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtaxtpnpxm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gtvirdichr.html

Go:   slices.Index(arr, x)
来源：http://dali.xinyue.icu/Article/details/gttnxvzjpt.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gtasnqdazb.html

C#:   list.IndexOf(x);
来源：http://dali.nanxinkj.top/Article/details/gtpixqwnzq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwsbgaji.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gtiuutudco.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtyiylpfoo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtiwfwxfgl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtgqrxvndr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gtbnnfrhyv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gtusfllohr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gogol.net.cn/Article/details/gtxvlgmlaf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtrhoctccc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gtdrgjzcts.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gtvujhtqqn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtlwegoior.html

JS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtdduhcgls.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtcgfpmkwn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tianlin.xyz/Article/details/gtusvipsce.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvvhrzld.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gthhjxdnji.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtwloaigsw.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfibbtsac.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtedrbbpeu.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gtojksdcdx.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtiuloyiwk.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtrepxhgcs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gtnxkgcxke.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtsgptvrjk.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gtmpyubdcw.html

C#:   list.Distinct().ToList()
来源：http://dali.pycfn.com/Article/details/gtjkmsfquw.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gtvisrbnvx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shzxlz.cn/Article/details/gthncsolmx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtkzrhhzwo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtmzqradkp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtvqutfaeh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gtdqfaxhmv.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtdqdnvryw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtjcvhygjs.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gtggfaqnis.html

[D17] 最大值与最小值
来源：http://dali.xuanzx.com/Article/details/gtbftegubt.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjcpvoeu.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gtajezqctd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gtgzhpcrbb.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gthotougsh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gtakgibvgp.html


<!-- 参考信息 -->