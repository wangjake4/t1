代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtylpinxtk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gtrudegftz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gtumyhyard.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtwdfudprz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hysaishi.cn/Article/details/gtqgtiifzt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nwbrower.top/Article/details/gtpqdotbvl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cdnleiting.top/Article/details/gtziaizshv.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffwtnjdv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcacjiyx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cucudq.cn/Article/details/gtbrjihrzm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtwbhsitoq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtutvujhbr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtofxasfkg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gtocxcmvkd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gtqsrrqmsi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.c1oappe.top/Article/details/gtwwxqxelr.html

[B13] 判断是否为数字
来源：http://dali.hnqzz.top/Article/details/gtrbbydcet.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gtyqfddalu.html

PHP:  is_numeric($x)
来源：http://dali.yuanzhike.top/Article/details/gtjroqteun.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gtzybsnpua.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtfkdmkwwy.html

Java: x instanceof Number
来源：http://dali.kuanghao11.cn/Article/details/gtadrxuodh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.316326.xyz/Article/details/gtemshjabs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zdqjudy.top/Article/details/gtmjpihtdj.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gtosnxdmsy.html

[B14] 判断值是否在集合内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccnblokc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gtlfrpfiff.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gtfhtrdvyy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtjcgpsfkh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gtyazfcgnh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ybcxt.top/Article/details/gtsqsiscai.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hysaishi.cn/Article/details/gtoawnosci.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.redwolf501.top/Article/details/gtgfpngebh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtkekonczq.html

[B15] 布尔运算与取反
来源：http://dali.xinyue.icu/Article/details/gtaawfeltk.html

Py:   a and b or not c
来源：http://dali.tianlin.xyz/Article/details/gtoycitgqr.html

PHP:  $a && $b || !$c
来源：http://dali.redwolf501.top/Article/details/gtvsahjgqy.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtcqixsfto.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gthnopbxds.html

Java: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtwqqycsuy.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtsdblwtxo.html

Ruby: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtnfbgfugs.html

C#:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapxldxnm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gttkkvvrxt.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gtikfnwqum.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gtlortuyap.html

JS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtiitiogle.html

TS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gtigyeazdz.html

Java: if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzbsvzqz.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtbewnvprb.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gtumyhkjrk.html

C#:   if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtoknuhfrq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjpblwkgn.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gthprinwnb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwnrohiru.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gthmpvkqqf.html

Py:   def add(a, b): return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtvnhuvzqi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsnpvqos.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtvtsofrjv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtokrrkzgs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtmfbnvshq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gtqflnidxr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gtmziesrvg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtpmfjcdhs.html

[C02] 默认参数
来源：http://dali.pycfn.com/Article/details/gtepxiuhqo.html

Py:   def greet(name="World"): return name
来源：http://dali.mhx1999.top/Article/details/gtjmtdikqg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cashguo.top/Article/details/gtayyfajha.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtpgdszbnf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gtpmkiecut.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.haohaochexian.top/Article/details/gttwxrzhgx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmsvxtcj.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gthubxzjib.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxuanxn.top/Article/details/gtnglzsrsn.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrarabslx.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuxming.cn/Article/details/gtitdkonmm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gtfornxrwp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtdplzbupm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtgkxvzsrn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.bjfxy.top/Article/details/gtkwfmugmf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gtdxfzxlvv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gtyudnqyhw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtijsdjpbi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.smart0.xyz/Article/details/gtelivjrje.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yvedp.cn/Article/details/gtvmbjejjd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yanxiufei.cn/Article/details/gtetedamxp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtsktypamf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtoogfvgew.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aibaodan.cn/Article/details/gtjhgruysd.html

Go:   // 无：用配置结构体参数
来源：http://dali.aibaodan.cn/Article/details/gthmuarzoa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtdoxpnqgu.html

C#:   f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtgkpwfavp.html

[C05] 返回多个值
来源：http://dali.xuetiantiany.cn/Article/details/gtipnincjg.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gttbpvrqxu.html

PHP:  return [$a, $b];
来源：http://dali.xylfe.cn/Article/details/gtvtkzsmvk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gttfenhsmh.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtikjazlog.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gtavryalju.html

Go:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtpmwcenvw.html

Ruby: return a, b
来源：http://dali.jyoumei.cn/Article/details/gtigrgwqso.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuanzhike.top/Article/details/gtwlhyygre.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gtqjxuaubz.html

Py:   square = lambda x: x * x
来源：http://dali.gotoacloud.top/Article/details/gtqkgiwric.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuykebfeh.html

JS:   const square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtfudjmlhl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtuvcasyti.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sxryk.cn/Article/details/gtfeobwwut.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daxiang520.top/Article/details/gthmtdjckn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yonumen.top/Article/details/gtplgejybz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtuicqjxrj.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gtevmktpbj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gthyxuxovs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjvkweyq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnqzz.top/Article/details/gtsxcytglj.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gtuknxvfuv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtqcwsefny.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigfzy.top/Article/details/gtgqsbnsar.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gttakupapk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksmkfqhf.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gtewtzrzqu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangdashe.top/Article/details/gthsjfbdgg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gotoacloud.top/Article/details/gtrqieegyz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtzjflcbek.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtormhfkfw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hongshengwenyu.top/Article/details/gtopbqkkef.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gtoakkkmii.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhengqikj.top/Article/details/gtobpkvfqp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtvtmggsnf.html

[C09] 递归
来源：http://dali.pengpengdd.cyou/Article/details/gtwjtybjzj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gttafqedix.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gteivbcwrl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gthrgfihhj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtfvwdoqiv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gtuyovmnog.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gteylsjsoi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtdhwosnxu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gtjywbatjv.html

[C10] 变量作用域
来源：http://dali.yonumen.top/Article/details/gtnwktnxfd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gthdqyfjie.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gogol.net.cn/Article/details/gtjnzgsrls.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtbwbcotuf.html

TS:   同 JS
来源：http://dali.yj202588.top/Article/details/gtfngcclee.html

Java: 方法内为块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gthyvnowmq.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtmymevhqm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuxming.cn/Article/details/gtzgvxhcbb.html

C#:   块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtunlahdvs.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gtsrwjprdi.html

Py:   from module import func
来源：http://dali.meibo888.top/Article/details/gthcwshngv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuanzhike.top/Article/details/gtnznyignq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtmscpevhn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gtgnioelez.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gtoogywcbo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuanzx.com/Article/details/gtmdrgtdgd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuxming.cn/Article/details/gtsqqvrsiu.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gtlsrgokzw.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gtkfllzdol.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gtykknbypr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gtpetxnywr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtrzewizip.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtisfpclau.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gtjejijomq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gtywvbkjjw.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gtpxbncwgp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shuidangran.top/Article/details/gtmxzfkter.html

[C13] 类型声明 / 类型注解
来源：http://dali.jianghu66.top/Article/details/gtvyeqzhpc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.snrcjt.cn/Article/details/gtywifbtmz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtxxdehhhe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.iojbl.cn/Article/details/gtbathhyfo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtopobpvjv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtifyjpkne.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gtsdovtwfj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gtpzzcyqdt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gtfczynxpk.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gthidtoset.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gtlrfeevie.html

PHP:  // 无泛型
来源：http://dali.sweek.top/Article/details/gtnldyavcp.html

JS:   // 无泛型
来源：http://dali.yongpay.top/Article/details/gteytsncut.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gtmmherrbs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxinkj.top/Article/details/gtbebxjxlb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gttbmouqnx.html

Ruby: # 无泛型
来源：http://dali.tian-w.cn/Article/details/gtrlmiwbof.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gtokymxuea.html

[C15] 解构 / 展开参数
来源：http://dali.yueranfly.top/Article/details/gtjtocvbzi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gtsmvhwiwx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gtozhmaaqo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtafhrbylp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guannengcc.top/Article/details/gtypoilupi.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gtjijhivry.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gtfptniocm.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gtrtoemfnr.html

C#:   var (a, b) = pair;
来源：http://dali.nanxuanxn.top/Article/details/gtuimfdzyj.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtrwtxlxwa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ivvv.top/Article/details/gttmwekgnx.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtqdxuobfh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtybbyatrk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gthlhllpph.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtiiykmvfg.html

Go:   // 无重载：用不同函数名
来源：http://dali.gogol.net.cn/Article/details/gtevelljby.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yueranfly.top/Article/details/gtzmfcqppb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gtlinamavu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpvxtnzsj.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsurwjdvd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtmmnslryn.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtwjrfubia.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.snrcjt.cn/Article/details/gtniifyvxo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtwqvdlzan.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gttwaitqps.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yanxiufei.cn/Article/details/gtrioabope.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gtvtjdfbfe.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gtltdlaqzh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gtauasanhw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtvnbrbfcl.html

[D02] 追加元素到末尾
来源：http://dali.snrcjt.cn/Article/details/gtqfgqehvm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.feifeiyinyue.top/Article/details/gtpmkubofr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gtebukiutg.html

JS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtvjjqhgzl.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncbjrjez.html

Java: list.add(4);
来源：http://dali.shzxlz.cn/Article/details/gtkunizeyn.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gtiqchazqj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gtdzfjizue.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtvbrsdjaf.html

[D03] 在指定位置插入元素
来源：http://dali.meibo888.top/Article/details/gtmirxihhb.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gtbtfmbkpg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.birdmap.top/Article/details/gtbibabaol.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gtxwvpgrgf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtuvrybgej.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtnhemfajg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tian-w.cn/Article/details/gtkboobkzy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gtzcysirtm.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtcrxlkhmk.html

[D04] 删除元素
来源：http://dali.pycfn.com/Article/details/gtiqrmaznr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtgqpmfzjx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtzrfzqqdu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.c1oappe.top/Article/details/gtilgevttx.html

TS:   arr.splice(0, 1);
来源：http://dali.snrcjt.cn/Article/details/gtuwhalhlv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gtcbfmunib.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtjklvzonu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtpmnlcqim.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gtfddcuabv.html

[D05] 访问与修改元素
来源：http://dali.wangdashe.top/Article/details/gtmvffdrqu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtqhnzvlmr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcgpeyqh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtaauxlhhr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gtpdbdaajo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gtiabqcrtu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtgxlobbtr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtfxsnwuwk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtvbprzswb.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gtdtrnnpcr.html

Py:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtyjzhvrbk.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjkxdvka.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtpkctiplv.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtfewazexe.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gtvztfzhqm.html

Go:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtajlopgeb.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gtkndjmnym.html

C#:   list.Count;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcnhontm.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gtxsbmipaq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gtlcjrlatm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xinyue.icu/Article/details/gtqmiotqzb.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtkfkfiuma.html

TS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtrugzwfqd.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtxcxqzqgy.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gtesjabplu.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtlpgtikik.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtbhbycrwd.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gtztrblrtz.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtmpboksll.html

PHP:  array_merge($a, $b);
来源：http://dali.shangyingyoupin.top/Article/details/gtecmquyji.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gtgjhozlzi.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gtwzjeatjd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtcayhomqe.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gtjwyvufmb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkggfsgor.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gtuslopoda.html

[D09] 排序（升序）
来源：http://dali.hongshengwenyu.top/Article/details/gttsbhezza.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxreemni.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gtcyoreqwq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gthowicgxy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gtvpkwwqah.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gtafeoddnw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtlnqcgiyj.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtpchurxxh.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gtcpghzwwa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuanzhike.top/Article/details/gteywmqkfs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gtvugbcmhv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gttrtqahck.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtnjjgmkue.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtqqpldczw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gttkeecmoy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.redwolf501.top/Article/details/gtktfkhsrw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gtmzhthhtv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhixingplan.top/Article/details/gtxammpidh.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gtunqgbmro.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shangyingyoupin.top/Article/details/gtxiioesoi.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gtpjafriiq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gtfalboisr.html

TS:   [...arr].reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtiokbkorj.html

Java: Collections.reverse(list);
来源：http://dali.wangdashe.top/Article/details/gthxbneoqt.html

Go:   slices.Reverse(arr)
来源：http://dali.cheryme.top/Article/details/gtjieugtud.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtmmhttqod.html


<!-- 参考信息 -->