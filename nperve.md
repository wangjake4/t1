代发 wailian999

[B13] 判断是否为数字
来源：http://dali.nanxinkj.top/Article/details/gt2qzrqajmh.html

Py:   isinstance(x, (int, float))
来源：http://dali.shzxlz.cn/Article/details/gt2fmwfrajw.html

PHP:  is_numeric($x)
来源：http://dali.tianlin.xyz/Article/details/gt2sxfuirvr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gt2jimodete.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2aijfddem.html

Java: x instanceof Number
来源：http://dali.wangdashe.top/Article/details/gt2utepzriw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gt2leuvdrfp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gt2psuotfxd.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sinknjps.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkygknqz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfzmigwn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zycfv.cn/Article/details/gt2pkyncqzi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2orztqerf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uflotdnf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pycfn.com/Article/details/gt2tkwdwebl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhengqikj.top/Article/details/gt2qrbbgzid.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yongpay.top/Article/details/gt2buptotfu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gt2nocdivup.html

[B15] 布尔运算与取反
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufidzhgx.html

Py:   a and b or not c
来源：http://dali.zhixingplan.top/Article/details/gt2yamgennm.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gt2kyvihuso.html

JS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2kqktvoxt.html

TS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2mrhphmvc.html

Java: a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2rerupjfl.html

Go:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2ebtdgkkp.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2wkzicdiw.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gt2vpbmgair.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.birdmap.top/Article/details/gt2ahfzetfx.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gt2qtxgwcsc.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxinkj.top/Article/details/gt2urgqqzfc.html

JS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czaxfrun.html

TS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gt2tmkhmjdo.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gt2nyryklhr.html

Go:   if data == nil { return }
来源：http://dali.xziqi.cn/Article/details/gt2qkzuchms.html

Ruby: return if data.nil?
来源：http://dali.cucudq.cn/Article/details/gt2slxczfwp.html

C#:   if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gt2bobyrjjc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2yjxmksxl.html

C. 函数与作用域
来源：http://dali.svipenyu.cn/Article/details/gt2ynzygkyt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2yzndrazs.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfrnkddg.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2kvmxxtaq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmnajtrm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2eqdsgpxg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2ctbnpbxv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2vuxjllnr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gt2bnssumuv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gt2qbkjdexg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qeiqfazr.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gt2epfrzasm.html

Py:   def greet(name="World"): return name
来源：http://dali.ppjwa.cn/Article/details/gt2chibhbbo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrexxkog.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wavyimhx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2wwvmlzsx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj202588.top/Article/details/gt2omtmgwvf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangdashe.top/Article/details/gt2gznouwwz.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gt2nywgiads.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gt2dmcgeojm.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gt2yorcpxii.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gt2akpddami.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gt2ojbpqfsp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkvzvctv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gt2uiovgmru.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gt2mpibwhxi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gt2pndxrnvf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prpamvim.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dianchejie.cn/Article/details/gt2szixkerh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.havefunace.top/Article/details/gt2fcukzrvy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gt2fvlcvldf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gt2wtssobsx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzadyitu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.316326.xyz/Article/details/gt2bdbzmdqw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinghuilouyu.cn/Article/details/gt2guxtmuzp.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenzaomai.com/Article/details/gt2bjrjtmuy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gt2poapqvcv.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gt2ymjndnld.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gt2braeunut.html

Py:   return a, b
来源：http://dali.andypj.xyz/Article/details/gt2eojjzvtc.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gt2ipzejquh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gt2pcoqsvfa.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gt2lqjwqwsy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sysykeji.top/Article/details/gt2tdvwvild.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gt2sfycbcdr.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gt2msaftznb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hysaishi.cn/Article/details/gt2ypvhoyeh.html

[C06] 匿名函数 / lambda
来源：http://dali.sxryk.cn/Article/details/gt2hhcmskhi.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gt2hziqgmdl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdgkqvxt.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2iosnelka.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sxryk.cn/Article/details/gt2bwwowbty.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2jjipybtm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekokwtaq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hywenlv.cn/Article/details/gt2ihblwwia.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gt2kbipllqu.html

[C07] 把函数作为参数传入
来源：http://dali.sxryk.cn/Article/details/gt2ogjxobve.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gt2nicylpqu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gt2svyibukk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.9152youxi.cn/Article/details/gt2hlymbupp.html

TS:   arr.map(String)
来源：http://dali.yangfankeji.com/Article/details/gt2wrdfrtqa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2siathamd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj202588.top/Article/details/gt2mnnaugay.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gt2nxitaxoy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.mhx1999.top/Article/details/gt2mfdztiws.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gt2ofitdabc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gt2jlgljyeu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxinkj.top/Article/details/gt2khxyccoa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2lfnjrctp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2cgptjgtp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gt2kxqcyshu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nwbrower.top/Article/details/gt2njkmnccn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nwbrower.top/Article/details/gt2vppoylft.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gt2sbtsrupp.html

[C09] 递归
来源：http://dali.guowangkeji.top/Article/details/gt2peddlabt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gt2fhkiwpxn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gt2oxauvarj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gt2gfmjychj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gt2csywarbe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ybcxt.top/Article/details/gt2dsoctduh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigfzy.top/Article/details/gt2teokbxzy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gt2kuoasodf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gt2mitoikbv.html

[C10] 变量作用域
来源：http://dali.ivvv.top/Article/details/gt2wmabmubm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gt2xcswqtnw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.bjfxy.top/Article/details/gt2vifeknef.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2aefhtbup.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gt2wpkgbfwm.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2rcrxbgsj.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2lzaxhobc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gt2vqxgipep.html

C#:   块级作用域
来源：http://dali.tian-w.cn/Article/details/gt2gvguwusu.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gt2jwmovlvf.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gt2rubxacyo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amzzvqgh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gt2dxeacicm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gt2vpbqyfdo.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gt2otmnmebt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gt2oeodhwcc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyggsvxf.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gt2zuuwtasi.html

[C12] 立即执行函数 IIFE
来源：http://dali.sufxvd.cn/Article/details/gt2vpwhsdzm.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gt2zkwqpwgn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gt2efunaywf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktyfdwma.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2pmckupkp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gt2ijfdailf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gt2duezlbwt.html

Ruby: -> { puts "run" }.call
来源：http://dali.guowangkeji.top/Article/details/gt2jruwgxgc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gt2kcylkmbl.html

[C13] 类型声明 / 类型注解
来源：http://dali.iojbl.cn/Article/details/gt2lzytudtl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gt2ehmoxwoe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gt2tywahjbg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gt2woyzqpnu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2tgwymsct.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rhitpupf.html

Go:   func add(a, b int) int
来源：http://dali.smart0.xyz/Article/details/gt2ibceuuar.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gt2vdpgicop.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gt2llqesbgb.html

[C14] 泛型函数
来源：http://dali.jiagoushi.top/Article/details/gt2sdnktiom.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gt2yvsujxgy.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2gvxpsnva.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2ndkfkmfy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnqzz.top/Article/details/gt2pmfysbyd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2cdobgfbk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gt2fdxwappj.html

Ruby: # 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2mkbycglm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sysykeji.top/Article/details/gt2ccxvmvju.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gt2hzqubijn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcywzdc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guannengcc.top/Article/details/gt2cyvlybje.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2condsjgt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2avslpiwf.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2vygzespl.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2kxqjcoma.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gt2vbvzprte.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gt2cqfmgghm.html

[C16] 函数 / 方法重载
来源：http://dali.ydzc1.top/Article/details/gt2hcbepmdm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangdashe.top/Article/details/gt2qkjhnxpj.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eugyzxmg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gt2nxfiglxn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gt2rvqokjzn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cqqwz.cn/Article/details/gt2zumlwktl.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gt2zdlyxiuh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jlsjyb.cn/Article/details/gt2oknfhkqy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2vjkrxzgp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2uybnqhiy.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gt2rlsqseca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oeivrgzq.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2rmoyodds.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daxiang520.top/Article/details/gt2iblsixvj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gt2qrsvewra.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fzhhl.top/Article/details/gt2cwdjgcke.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dashuyun.cn/Article/details/gt2zdfwqlii.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2peqqbvpj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gt2kfywuojl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fgfuxewh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gt2tzbspvro.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gt2vqxkcgdu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.0kj1m.cn/Article/details/gt2epzpunce.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2uoamkces.html

JS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gt2yohwfaio.html

TS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gt2enzqekkz.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2htjgwtux.html

Go:   arr = append(arr, 4)
来源：http://dali.yj202588.top/Article/details/gt2jlkopkcx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gt2wpqglmhs.html

C#:   list.Add(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2qrpqapzw.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gt2hbyjyrbs.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2yautyqbd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hysaishi.cn/Article/details/gt2ppfnlbsk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gt2ytwgzyez.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2wjsifnik.html

Java: list.add(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2ooexowbj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cucudq.cn/Article/details/gt2sxyyunzf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gt2kevwemfq.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2qrxjpcgr.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gt2kojwhzbu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gt2rklnsbzo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2vjyapkar.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gt2kuvpiyni.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gt2fcoicvgt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gt2uiqogauz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gt2bpyfwxxz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gt2hufkdqyo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gt2tenhuece.html

[D05] 访问与修改元素
来源：http://dali.guannengcc.top/Article/details/gt2frddyfpa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gt2hcxemjdh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gt2lnrfeehm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2trpnhsos.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.iojbl.cn/Article/details/gt2uvhljtry.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wckqqklt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtozqjvn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2jhpdnton.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2fqesrfhc.html

[D06] 数组长度
来源：http://dali.hnqzz.top/Article/details/gt2fjzkjtwy.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2shgrcgpu.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gt2vzgbsbmi.html

JS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2ohyyuuuf.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gt2fmwdptrg.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gt2zwsqsyrh.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2htutozxf.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigufen.top/Article/details/gt2chpapchn.html

C#:   list.Count;
来源：http://dali.svipenyu.cn/Article/details/gt2goxostpu.html

[D07] 切片 / 取子数组
来源：http://dali.hammf.cn/Article/details/gt2zbzjipcm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gt2jljqorrx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2pghebbkn.html

JS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gt2oqljbnsa.html

TS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gt2hwvawpjb.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2jxovoire.html

Go:   arr[1:4]
来源：http://dali.havefunace.top/Article/details/gt2qeznfbqg.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gt2diijbdss.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwjrkntq.html

[D08] 合并两个数组
来源：http://dali.gzhubu.top/Article/details/gt2rahlynve.html

Py:   a + b;  a.extend(b)
来源：http://dali.bjfxy.top/Article/details/gt2gsejhtxz.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edxcdujz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgfzy.top/Article/details/gt2jxskksfg.html

TS:   [...a, ...b];
来源：http://dali.gaohongyu789.top/Article/details/gt2fdivlcvr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2fefspfdq.html

Go:   append(a, b...)
来源：http://dali.ydzc1.top/Article/details/gt2mzmsbgyt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2wwcwvmmj.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2bsryaxgb.html

[D09] 排序（升序）
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqedxcdf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gt2tmeieach.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwpifdlx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycarhwrg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gslxxyhh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gt2pbwglisx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvylerko.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2tiahchzr.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gt2fjjwlxwk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gt2szrjnyni.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2ovaxhgez.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gt2tfitvuki.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gt2dwhkopjx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gt2hqmzfrbt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gt2qvumxels.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guannengcc.top/Article/details/gt2gjcthnqy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sweek.top/Article/details/gt2vmbntydh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxinkj.top/Article/details/gt2aneyrzbm.html

[D11] 反转数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ocuzkmuz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gt2yxqirxgq.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gt2uznefhul.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gt2avoqxfji.html

TS:   [...arr].reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsgnvdyv.html

Java: Collections.reverse(list);
来源：http://dali.yonumen.top/Article/details/gt2uiajakuy.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gt2brmaueyy.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gt2rrsdpqsi.html

C#:   list.Reverse();
来源：http://dali.quarkkingdee.top/Article/details/gt2armqnrbt.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gt2mydedany.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gt2sdknwpav.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rohzowrh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gt2ndrmaetb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2wuzuymjz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gt2zuluwxlj.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfwuziki.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gt2emjkhogp.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxwaknze.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gt2mazlaksp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2jwdowoub.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gt2wohtckhv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gt2wfglgpki.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gt2mqyeyknm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2juozenuk.html


<!-- 参考信息 -->