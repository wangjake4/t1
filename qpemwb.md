代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gt2beupkwun.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yvedp.cn/Article/details/gt2gjjmvllk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yanxiufei.cn/Article/details/gt2ivuvukdm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yvedp.cn/Article/details/gt2lszlaxsq.html

[B13] 判断是否为数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmrtfyjg.html

Py:   isinstance(x, (int, float))
来源：http://dali.yvedp.cn/Article/details/gt2vxjzlcsi.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gt2vbmkqrhk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gt2rtxwsuho.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gt2mnchyorq.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gt2iggowlof.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gt2tcqoaupk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.0kj1m.cn/Article/details/gt2pvyqeugn.html

C#:   x is int or double or decimal
来源：http://dali.316326.xyz/Article/details/gt2xiwejrtz.html

[B14] 判断值是否在集合内
来源：http://dali.mhx1999.top/Article/details/gt2cdomukwh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gt2xhgsmjyq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uuyccody.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gt2kvxtypzy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzbncqrh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xifhacjr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ydzc1.top/Article/details/gt2kdkijfro.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aibaodan.cn/Article/details/gt2sfywvpqj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gt2pvvfhneo.html

[B15] 布尔运算与取反
来源：http://dali.chenzaomai.com/Article/details/gt2mmjwpfht.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gt2oarypgeo.html

PHP:  $a && $b || !$c
来源：http://dali.dianchejie.cn/Article/details/gt2umgitcax.html

JS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2obhzsijx.html

TS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2pzbfwbfp.html

Java: a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2hkzdkwkl.html

Go:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2hgsbukah.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2elkcprzb.html

C#:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2dhzylpqe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dashuyun.cn/Article/details/gt2xtralrvi.html

Py:   if not data: return
来源：http://dali.tanke756.top/Article/details/gt2plgjyegd.html

PHP:  if (!$data) { return; }
来源：http://dali.xziqi.cn/Article/details/gt2smlojtfo.html

JS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gt2dmbmvklz.html

TS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gt2glvaklnk.html

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gt2ysojhttb.html

Go:   if data == nil { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2oskjsgen.html

Ruby: return if data.nil?
来源：http://dali.zhengqikj.top/Article/details/gt2idwjgfsl.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gt2foewmrll.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2qmkuetnq.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gt2hrjtitgs.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2yswvcnws.html

[C01] 定义函数
来源：http://dali.tanke756.top/Article/details/gt2shnbopbg.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gt2epwbkpat.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2nszthrrd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2udrpnvfl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2dbdlkwun.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2xxqecjew.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsotsvk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.316326.xyz/Article/details/gt2acyabywr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2foykwavs.html

[C02] 默认参数
来源：http://dali.tian-w.cn/Article/details/gt2sqyngjlo.html

Py:   def greet(name="World"): return name
来源：http://dali.cheryme.top/Article/details/gt2kualkmln.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yywigexf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gt2zajumwjl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgruurxn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gt2rdjppyvt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iroclixp.html

Ruby: def greet(name = "World") = name
来源：http://dali.fengsongda.top/Article/details/gt2xptfukcn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gt2dznjqesu.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gt2jauwyeug.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kayvalnj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gt2wfeveukb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dianchejie.cn/Article/details/gt2gqayifis.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gt2jcklymcj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2vqrdkjhd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gt2xnavwlba.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gt2adtdpgen.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gt2vlrwvojd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gt2niqwqnqg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.c1oappe.top/Article/details/gt2nxxxeles.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gt2noimzjyd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gt2vlwhgwmm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gt2ezuejbpp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gt2wwedzwyl.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ncjlxnvx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2bzurimbb.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gt2zrlemrka.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnargbge.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwfhpfqq.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gt2phjykpnv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gt2afjasjnp.html

TS:   return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2omaresdi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gt2dnbxboxm.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gt2pbavelye.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2gifgzexp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xinyue.icu/Article/details/gt2vvnpoosi.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxuanxn.top/Article/details/gt2aycdjojj.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huhwyqsy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenlongwang.top/Article/details/gt2qvfmrgtw.html

JS:   const square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdtrqokg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2vujqwbko.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cucudq.cn/Article/details/gt2cgmiarta.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.snrcjt.cn/Article/details/gt2ivzajhzt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gt2bpvcgdyj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gt2ehblwqce.html

[C07] 把函数作为参数传入
来源：http://dali.kuanghao11.cn/Article/details/gt2ysisgqje.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gt2aawzrwrm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2mkicpsol.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.svipenyu.cn/Article/details/gt2zqsmajnv.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gt2zwhqsoxh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2pwdigjqu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dashuyun.cn/Article/details/gt2kizawyee.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gt2mmfgnqfc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvvmnovk.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gt2aeaebvoz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yanxiufei.cn/Article/details/gt2tdfafpbf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gt2yludczmf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2wwoctefg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bkfrwqgq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shzzlbvq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gt2bgnnaufx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.andypj.xyz/Article/details/gt2fvraqxhs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gt2baqiyvhl.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gt2esrndxsz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2aplxydxa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2ydaaxgni.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2gvdxbfon.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gt2mjzxhrhg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtgvbqdu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.meibo888.top/Article/details/gt2aldyyrxl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gt2grxelutt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gt2bnpsxbvl.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gt2dfyravwk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2luzukmnr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqqvqqoi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjioggfr.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gt2knvrkdlx.html

Java: 方法内为块级作用域
来源：http://dali.tian-w.cn/Article/details/gt2cqahgylj.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2mqrgbsbg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqxoqbjl.html

C#:   块级作用域
来源：http://dali.yongpay.top/Article/details/gt2ggbjbnkh.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gt2cuhdqkfy.html

Py:   from module import func
来源：http://dali.hammf.cn/Article/details/gt2vpipidiu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gikyzzdh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gt2amxahfxp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gt2xkcaweea.html

Java: import java.util.List;
来源：http://dali.0kj1m.cn/Article/details/gt2liocrbec.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jlsjyb.cn/Article/details/gt2abscufyw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gt2qtgweqtp.html

C#:   using System.Text;
来源：http://dali.aibaodan.cn/Article/details/gt2uhkkwrfy.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gt2iuybizcb.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gt2kiegitaw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gt2whlwxlsu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gt2hweabcem.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2jvyewqph.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gt2ccooczwt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.birdmap.top/Article/details/gt2vmupdeah.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangdashe.top/Article/details/gt2dssipcnf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhomnahn.html

[C13] 类型声明 / 类型注解
来源：http://dali.fengsongda.top/Article/details/gt2xrvoujej.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gt2qpjbgaes.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2yjorohga.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvclkolp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2zfndqlho.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2ekqdyvfl.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gt2acqcjift.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gt2rgwgohzq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guannengcc.top/Article/details/gt2ehstnvvh.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ainsdciw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gt2vdljuime.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpkbarj.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2sssfdwuq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gt2hiexcraq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2duyxxwsc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gt2uxhrczmd.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2awkzdctc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gt2ahlplget.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gt2viqczxcl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gt2uzkazwec.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gt2xqvjvmyn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gt2flhgmrog.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2fzgrutud.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnugaehu.html

Go:   // 无解构
来源：http://dali.chenzaomai.com/Article/details/gt2iujseenw.html

Ruby: a, b = pair
来源：http://dali.zhengqikj.top/Article/details/gt2buvwtqpx.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gt2vufoxcrw.html

[C16] 函数 / 方法重载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykahyulo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gt2jngspgpp.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gt2xnwmszyv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwflavax.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yvedp.cn/Article/details/gt2lsanrxpr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gt2ixasdssd.html

Go:   // 无重载：用不同函数名
来源：http://dali.yongpay.top/Article/details/gt2rcceubfj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kckfkpff.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sufxvd.cn/Article/details/gt2lhpkgmfp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2uykmbukc.html

D. 数组 / 列表 / 集合
来源：http://dali.aibaodan.cn/Article/details/gt2bsnjzika.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ehovczfc.html

[D01] 创建数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gt2ksmheqle.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gt2dzvhbtui.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gt2vufcynwh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gt2fxvzjvds.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gt2xefbwhvx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxuanxn.top/Article/details/gt2mcddpiuh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuanzx.com/Article/details/gt2oudqtpxz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gt2wmwmqpzb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbfzruzx.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gt2gokhleiv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gt2tphsadhs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbwbzaez.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2ukxopyrn.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gt2lrzqhamp.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxknouzn.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwxmyte.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gt2wfcjnxdl.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gt2csvipdgr.html

[D03] 在指定位置插入元素
来源：http://dali.sweek.top/Article/details/gt2ybompkjj.html

Py:   arr.insert(0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2vvhykjev.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuxming.cn/Article/details/gt2qgaqzmzt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gt2qkvmsowi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2ivlwcyjs.html

Java: list.add(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2jbqjnchq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gt2uclxicxp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gt2ahxvlihn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mruvhuor.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gt2pmterpuz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2igjjpwcg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gt2zrgrgvqa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzkneank.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdztrdkl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gt2hnkturbz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtcsgyko.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gt2ufneebvj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuanzx.com/Article/details/gt2zybcnmgr.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gt2vtwhzvrs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gt2fqkdsycw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gt2pupiymrr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gt2lqzmeeml.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gt2vgkjsrhj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.mhx1999.top/Article/details/gt2lticjzzt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2mfodlrsw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2xijwypsi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2vrnlrvzl.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2luexaehe.html

Py:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvdpypvd.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2dqvryivh.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gt2cwsuobrr.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gt2zmvtbwew.html

Java: list.size();
来源：http://dali.yj202588.top/Article/details/gt2kunighng.html

Go:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2qlsygora.html

Ruby: arr.length; arr.size
来源：http://dali.yonumen.top/Article/details/gt2dlaanvtt.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gt2krtyewet.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gt2oovyqjzu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gt2mnjdmewq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2umredmuy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wugzwcfn.html

TS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vswletkp.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2jranttkf.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gt2ycijnfuf.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2zjsbhaif.html

C#:   list.GetRange(1, 3);
来源：http://dali.andypj.xyz/Article/details/gt2bsepnxde.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gt2mzitsosh.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gt2rrnptzxw.html

PHP:  array_merge($a, $b);
来源：http://dali.hnqzz.top/Article/details/gt2qdduvidc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gt2enehvlmf.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gt2xfvgryyp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfptdgig.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gt2ivfyppxn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gt2umolgzos.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2mzyytrgz.html

[D09] 排序（升序）
来源：http://dali.ehwqpu.com/Article/details/gt2ndbujteg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnbhomrx.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2bvqjzdnm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gt2qucaxztt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangdashe.top/Article/details/gt2ejbrwxxx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gt2tjqcxuks.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdryshae.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gt2mvrkbawu.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gt2nvzckioh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2esivobzp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gt2ivzgntvw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gt2pbkthxvh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfxfqnsn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbjnrldp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daxiang520.top/Article/details/gt2sjvfdhyh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gt2vwxmaaje.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gt2ekekdpzx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gt2domlhedx.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqtkyzxm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gt2lsghilzo.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2fgycndpn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gt2vxuqphzz.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdxisakp.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gt2smwslivv.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2cdzrfdol.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2cfydwaqx.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gt2iuhdkgut.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gt2dftbqyfz.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gt2oereilpo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2jirnoivu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2vmoywxjw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2saekvyzp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzaoawrz.html

Go:   slices.Index(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urrtovux.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gt2wmbgjhay.html

C#:   list.IndexOf(x);
来源：http://dali.zhongyouzk.top/Article/details/gt2yutrfclq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gt2xjxialwk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gt2ovrnxjnm.html


<!-- 参考信息 -->