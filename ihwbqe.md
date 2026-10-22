代发 wailian999

[B13] 判断是否为数字
来源：http://dali.jyoumei.cn/Article/details/gt2wdpipnqi.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iryrtcdg.html

PHP:  is_numeric($x)
来源：http://dali.tian-w.cn/Article/details/gt2pstwfxpv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gt2zecpizuf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gt2oykexqeh.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gt2qcgxxtpj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxrhgqii.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gotoacloud.top/Article/details/gt2aqyljfwm.html

C#:   x is int or double or decimal
来源：http://dali.chenzaomai.com/Article/details/gt2igkxlvwn.html

[B14] 判断值是否在集合内
来源：http://dali.mhx1999.top/Article/details/gt2tqxpwnie.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gt2lbfvyxig.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gt2nysffnzi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2qcamrzph.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2rjnvrblu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2bwqboylx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhengqikj.top/Article/details/gt2rgxdknot.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zdqjudy.top/Article/details/gt2cmfmlbzd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2mxnobagz.html

[B15] 布尔运算与取反
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwcopeyh.html

Py:   a and b or not c
来源：http://dali.wangdashe.top/Article/details/gt2hscqtpzy.html

PHP:  $a && $b || !$c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gyzwrplo.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2akignqfc.html

TS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2scywsohb.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2dhfvnwzu.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qixkxabu.html

Ruby: a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2ejeasjav.html

C#:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2dtcnpfsv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2xapgqojl.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gt2xitkmvcl.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gt2lbgftftd.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gakkjdtf.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gt2gvoilidx.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gt2wjtsaskp.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gt2dxpgdhmu.html

Ruby: return if data.nil?
来源：http://dali.ehwqpu.com/Article/details/gt2ghmxggsw.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gt2afvmpbgi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smiavasa.html

C. 函数与作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyytvhsu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2knizgide.html

[C01] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gt2hoaghbqa.html

Py:   def add(a, b): return a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2lyjcedgr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gt2hrwtaehz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2ezwrpwxk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2wfxqdgoi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2qwjwdvto.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gt2vyievjaj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gt2fscpjfxd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2bhixbbyp.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cszqujra.html

Py:   def greet(name="World"): return name
来源：http://dali.cheryme.top/Article/details/gt2djmaseql.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tanke756.top/Article/details/gt2vcrjcvcl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2tihdocox.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2suahmpgh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gt2dnpvfasu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sweek.top/Article/details/gt2urunbufn.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gt2lhobkxyi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cashguo.top/Article/details/gt2egkevxje.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gt2eksworqt.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gt2kydeiplo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gt2qbiwqfxi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gt2pdehkorj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gt2rutsqrgw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gt2ssvziryr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gt2svpakiye.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gt2xtajxtrc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqypegaa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dashuyun.cn/Article/details/gt2yfyqeknx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.meibo888.top/Article/details/gt2knukdrzr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gt2lhstmdba.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2vkitcnnu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gt2yahhxgff.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gt2tcnmhgvi.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgfzy.top/Article/details/gt2ryumbbzj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gt2ghskrbqm.html

C#:   f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gt2yxjqpdsx.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gt2kvdceudu.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gt2llcisjoi.html

PHP:  return [$a, $b];
来源：http://dali.cheryme.top/Article/details/gt2djqkmjdb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.mhx1999.top/Article/details/gt2mdrvkvuo.html

TS:   return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gt2rdxniizi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.havefunace.top/Article/details/gt2kxvxqlis.html

Go:   return a, b
来源：http://dali.andypj.xyz/Article/details/gt2csoklgqv.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gt2nkvamvbt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sufxvd.cn/Article/details/gt2bojlfrjp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhoulong.xyz/Article/details/gt2lbfjqdwi.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gt2eculgoxh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gt2gcsrcdje.html

JS:   const square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gt2rhpkcrox.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtvuduuk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gt2pllvxlcb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gt2sicacitc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hywenlv.cn/Article/details/gt2jduckuht.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztmzyudj.html

[C07] 把函数作为参数传入
来源：http://dali.gogol.net.cn/Article/details/gt2miisbyyk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gt2rvdtiuij.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2fxyhtrvk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.andypj.xyz/Article/details/gt2yzrnziyz.html

TS:   arr.map(String)
来源：http://dali.tianlin.xyz/Article/details/gt2nqrbxyni.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yueranfly.top/Article/details/gt2cpblceoz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guowangkeji.top/Article/details/gt2eesogaus.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gt2fcwkebyw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.bjfxy.top/Article/details/gt2qcsafcbm.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gt2zebyvwet.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rysscars.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gt2ztjzcuon.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rqgucwyr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2jauvptjr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ehwqpu.com/Article/details/gt2mujuynel.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.bjfxy.top/Article/details/gt2zmohuywp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2fswapppg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gt2mwusxhrc.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gt2yohmulcn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gt2nsehkvoz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gt2opdkzsok.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gt2mvrhrzyd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gt2uqqzfvrl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daxiang520.top/Article/details/gt2edvfqcsr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xziqi.cn/Article/details/gt2cjtpigsl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gt2bjcjiqvy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gt2kzdinfiu.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gt2pcdptvzm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gt2ouupngxn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.havefunace.top/Article/details/gt2yzlgsxyi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2xdizkxxp.html

TS:   同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqjymdzg.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gt2gpzloqws.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gt2ctxvtgvz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmtxdzhd.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvqqigsn.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpylslos.html

Py:   from module import func
来源：http://dali.cqqwz.cn/Article/details/gt2mkkggnkq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tianlin.xyz/Article/details/gt2gqpgxsxu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onvgzant.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsoxtkpl.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gt2vqnfwpma.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.9152youxi.cn/Article/details/gt2cxqvufxr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gt2ynmkqztj.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gt2xrgmzpum.html

[C12] 立即执行函数 IIFE
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahtyspmf.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gt2pqvcfpiw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gaohongyu789.top/Article/details/gt2lczvcdcs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gt2xkczlgne.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gt2tkkysaxc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.kuanghao11.cn/Article/details/gt2kljbdale.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sxryk.cn/Article/details/gt2rviqcgcy.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghwkjpbs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gt2tihrlzzp.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdvxahic.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gt2ccuphhpv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gt2oaqbdxlt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gt2uquizbcf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xetrizsy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ycebjods.html

Go:   func add(a, b int) int
来源：http://dali.cqqwz.cn/Article/details/gt2xkttlpou.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhoulong.xyz/Article/details/gt2htguibrp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shzxlz.cn/Article/details/gt2nrptbina.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gt2qfaxtpbf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gt2ijqmdeob.html

PHP:  // 无泛型
来源：http://dali.gzhubu.top/Article/details/gt2vohxvixc.html

JS:   // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmufscmo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnqzz.top/Article/details/gt2sngyoodw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gt2xivyvsek.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gt2emwmsksh.html

Ruby: # 无泛型
来源：http://dali.nanxinkj.top/Article/details/gt2pfxesgcz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkpxsrhg.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxszzlzq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gt2ovcaxqvv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzmzxahx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2qcsesuub.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtzgslix.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gt2cqyymate.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gt2bcxqqhcp.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gt2lrswxfeb.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gt2pzhracgl.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gt2yximolga.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gt2hixrodig.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gt2jqvbagwe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxfuzivy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gt2ymswvcxz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqaqgds.html

Go:   // 无重载：用不同函数名
来源：http://dali.zdqjudy.top/Article/details/gt2iugrnyhx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.snrcjt.cn/Article/details/gt2uewklngk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gt2tbdfcrgx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkhgepxa.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gt2ddwkgqej.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhvutowc.html

[D01] 创建数组 / 列表
来源：http://dali.hammf.cn/Article/details/gt2qyftppor.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gt2eoqfywzd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzxejtpx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shuidangran.top/Article/details/gt2hdozkljl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zzntsatr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gt2oahgjzhf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpnlmtty.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gt2jutjsgfk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tanke756.top/Article/details/gt2xtkvquhx.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gt2qpfrhuvq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnnxqcn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gt2brerzont.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gt2cjcfbubp.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gt2iykzlyhp.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gt2gygztwol.html

Go:   arr = append(arr, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2mmlgppho.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sufxvd.cn/Article/details/gt2gtcomxts.html

C#:   list.Add(4);
来源：http://dali.cashguo.top/Article/details/gt2bewwzrmg.html

[D03] 在指定位置插入元素
来源：http://dali.gotoacloud.top/Article/details/gt2vcrnfgyi.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gt2ewgyrzhm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gt2ilpqoldx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpduwgcf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vomhlwog.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjzfdpxv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gt2cxtyphoc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sufxvd.cn/Article/details/gt2koqhkmhx.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2qbxtflix.html

[D04] 删除元素
来源：http://dali.andypj.xyz/Article/details/gt2kptemwmx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gt2dtnkggyc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2nunthmic.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gt2phjhukmf.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqxzeqnn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gt2ukfgfyqr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gt2lcnumhha.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqpjxwjm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gt2ireoryuf.html

[D05] 访问与修改元素
来源：http://dali.hnxiangtu.top/Article/details/gt2nmeqcbmq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnvlelzb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrslzulg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gt2fgwagapf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gt2lyhbhjlj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gt2hkonhlkk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2reaxfomn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2rsmxofpd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2vxbqfwnr.html

[D06] 数组长度
来源：http://dali.hnqzz.top/Article/details/gt2akfzlikp.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2relzhdma.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gt2rfsolhro.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gt2elbsjais.html

TS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gt2lvlrbnda.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnabnyjo.html

Go:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2nxpntolw.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gt2tseitxnj.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gt2ttxgloux.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhioonjz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gt2ebjkvezd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fzhhl.top/Article/details/gt2ghsxvcyj.html

JS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2prsajbek.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gt2iydxgnvy.html

Java: list.subList(1, 4);
来源：http://dali.daxiang520.top/Article/details/gt2sgannkep.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gt2mozwsmsu.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqfhmike.html

C#:   list.GetRange(1, 3);
来源：http://dali.xinyue.icu/Article/details/gt2wnhynibe.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gt2bstxpwas.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gt2miwxctco.html

PHP:  array_merge($a, $b);
来源：http://dali.hnxiangtu.top/Article/details/gt2yfroayvf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gt2lvlpztyr.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gt2ftjymnuy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2dmzjhspn.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gt2kterzirp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2bniutwfo.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2htrbojle.html

[D09] 排序（升序）
来源：http://dali.ydzc1.top/Article/details/gt2ijqhukdt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gt2urpayfam.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gt2mqejgyvp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ppjwa.cn/Article/details/gt2wvgxyrpi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gt2jstrqpbo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gt2kdjiahia.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gt2zhuogwit.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2innqhxft.html

C#:   list.Sort();
来源：http://dali.sweek.top/Article/details/gt2wwbnsjdz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gt2xbrbcvwp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cashguo.top/Article/details/gt2vykzlpnc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gt2hmnyeaob.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gt2bsssxzki.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2gfmzypph.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gt2xxoztfvb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gt2doclideu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gt2npkmroqs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gt2pvqkoajz.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gt2odsqithi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xziqi.cn/Article/details/gt2ermnqlcl.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gt2ewkxdtcw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gt2kghynrmz.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gt2ldykbckg.html

Java: Collections.reverse(list);
来源：http://dali.yuanzhike.top/Article/details/gt2wagqkngb.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gt2meqmazof.html

Ruby: arr.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2onbszngy.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gt2eajffowg.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gt2btkuddtu.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gt2zufqtntv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gt2uhkbcuxs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gt2sinfkozn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2yprcushw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gt2ewxsyzuy.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2rrlzvrrq.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gt2uzqaowwf.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfzplhxp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gt2urjqwdzv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2tfclddvt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gt2djaahlrk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2lgwpeaeb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gt2ajevnrao.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kyubcrxk.html


<!-- 参考信息 -->