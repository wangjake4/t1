代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xylfe.cn/Article/details/gt2yszccsoi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ydzc1.top/Article/details/gt2xjrlvauo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ehwqpu.com/Article/details/gt2xerbglgn.html

[B12] 跳出多层循环
来源：http://dali.sufxvd.cn/Article/details/gt2nrpopctf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gt2kmkceilx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gt2tcuhxrxz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gt2ybjligcf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bfynvieo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gt2crhxltcl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gt2suknmcjh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258888.top/Article/details/gt2siaygcwc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gt2txtmvmle.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gt2tlfbzkze.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhengqikj.top/Article/details/gt2xfnfmlza.html

PHP:  is_numeric($x)
来源：http://dali.andypj.xyz/Article/details/gt2jdlzezod.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gt2gmhivsrf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2nliebeph.html

Java: x instanceof Number
来源：http://dali.sysykeji.top/Article/details/gt2jvezavmu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hammf.cn/Article/details/gt2jwvqohlo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwvnfhd.html

C#:   x is int or double or decimal
来源：http://dali.shuidangran.top/Article/details/gt2cfgruepx.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gt2wjuxkxki.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gt2gsoewbsp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ehwqpu.com/Article/details/gt2kfhmziye.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2ubhmgjwc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gt2jguzkqpr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxlloubn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xziqi.cn/Article/details/gt2nooawlvx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gt2dnwhyvjk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2mgqewmxv.html

[B15] 布尔运算与取反
来源：http://dali.yvedp.cn/Article/details/gt2ceajazrl.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gt2myotwmws.html

PHP:  $a && $b || !$c
来源：http://dali.shangyingyoupin.top/Article/details/gt2aljprdsj.html

JS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2djtxyhnw.html

TS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2aoajfxhx.html

Java: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2muqskdzi.html

Go:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2gizjkvdm.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2loixwiog.html

C#:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2amltebte.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gt2dukyuprf.html

Py:   if not data: return
来源：http://dali.jqgufenzy.top/Article/details/gt2mytyojqs.html

PHP:  if (!$data) { return; }
来源：http://dali.xylfe.cn/Article/details/gt2tashiukk.html

JS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gt2ejtadwpu.html

TS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gt2wqejcnxw.html

Java: if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2mmdptwrp.html

Go:   if data == nil { return }
来源：http://dali.hnqzz.top/Article/details/gt2lybnlunm.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2byqujbvk.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwaaauyn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2sstysmyc.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gt2touviway.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2whnvfhss.html

[C01] 定义函数
来源：http://dali.sxryk.cn/Article/details/gt2jcdsrqty.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gt2qtznpjvm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2wvepogbw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2mxrrrdzu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zvhugyqg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khcyvxac.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2mltsezvd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gt2muiyjcql.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2wbeennhl.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxkyfxsy.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gt2hipraiad.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gt2qekaecmn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2mykbvspd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2tkbwdqkx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gt2wulplvat.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gt2ffvtyepw.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gt2kgarnypk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smmyfvya.html

[C03] 可变参数
来源：http://dali.0kj1m.cn/Article/details/gt2vipxldml.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gt2bkrcuaor.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gt2dkqyhxoj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gt2tuzqieqi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gt2uzebrtmd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2lwmlmmkh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.snrcjt.cn/Article/details/gt2hobhdclg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gt2cwcysmrt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gt2fnndeeyk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj202588.top/Article/details/gt2vlhsramr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gt2oebrnqoc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhgrjvzk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2wyxuhybl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gt2wgrmlcqf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cucudq.cn/Article/details/gt2uuvemqyp.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gt2mhsjeaql.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gt2wdnsyrqq.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2vplbdlzd.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gt2ujkjvick.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2eqtojfmm.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gt2pmnywchh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gt2novvwdgt.html

TS:   return { a, b };
来源：http://dali.iojbl.cn/Article/details/gt2seszcdwv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gt2kbzuimsi.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2rtlsygbs.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2rrkjezpf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhwvimdn.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gt2xvjiyjvb.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrmkeoah.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gt2cqcrspcg.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2rxyaobta.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.smart0.xyz/Article/details/gt2ffgxzonl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2holmjfrr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.316326.xyz/Article/details/gt2krdumjal.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gt2qyjzpebb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gt2caixnntp.html

[C07] 把函数作为参数传入
来源：http://dali.sufxvd.cn/Article/details/gt2kvrpkvcc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wuxqylka.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2grafpkcq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gt2oeigqcle.html

TS:   arr.map(String)
来源：http://dali.c1oappe.top/Article/details/gt2ryhdqxkh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gt2sozkyvrd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwtolhwr.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gt2muxoozxy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gt2njqclnxb.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gt2nhtchnok.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jyoumei.cn/Article/details/gt2pcgwedhy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gaohongyu789.top/Article/details/gt2iirwbpsk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2mldztvft.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sclovexr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cheryme.top/Article/details/gt2vrbgekrj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrngcgmu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhongyouzk.top/Article/details/gt2ibnnhhxp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2wjfmbkld.html

[C09] 递归
来源：http://dali.vqdsnc.cn/Article/details/gt2hidkfcne.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gt2ziuntjws.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ffdfjohb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gt2luundkth.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gt2hgebwptr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gt2tsxrbpxm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gt2rdezyeyi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vijqssle.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pstyjpvh.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gt2imqmiwub.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gt2qnmcpwuy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258.top/Article/details/gt2slijtcft.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2njuacmvz.html

TS:   同 JS
来源：http://dali.tian-w.cn/Article/details/gt2xtzqadsj.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2kelkzovg.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmypybro.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gt2qchygtjq.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2gqpfldfl.html

[C11] 模块导入与导出
来源：http://dali.sxryk.cn/Article/details/gt2tjfzngyn.html

Py:   from module import func
来源：http://dali.ivvv.top/Article/details/gt2mqvqsejq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gt2bnrsxvvg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gt2wpqspjjs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmlvfhjm.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gt2rsbsceeq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gt2jlpbjglk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gt2gwtstpcj.html

C#:   using System.Text;
来源：http://dali.chenlongwang.top/Article/details/gt2xfqmoyqi.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gt2kifslzwg.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gt2cjhkwjti.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gt2evaqmxtq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gt2iwsluosq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gt2bogmvxiu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gt2vuhcvqbo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tanke756.top/Article/details/gt2sidjgovg.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gt2yuowtfxb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ivvv.top/Article/details/gt2xjebzccs.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gt2kxumepfj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jianghu66.top/Article/details/gt2qqsounxq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2muylawev.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.c1oappe.top/Article/details/gt2xsrahvsc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2akkybheo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2gkxoibcn.html

Go:   func add(a, b int) int
来源：http://dali.zhengqikj.top/Article/details/gt2rhyofyrm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gt2sdypvpzw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gt2louhhpga.html

[C14] 泛型函数
来源：http://dali.vqdsnc.cn/Article/details/gt2cyfaorlk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gt2grkkvnab.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2yscmfwwt.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2ijslctao.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guannengcc.top/Article/details/gt2brjzumxv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gt2hanlruqp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yanxiufei.cn/Article/details/gt2bdukivcu.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2zebjqsvx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gt2rnwzhhdb.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gt2prawqhxh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.svipenyu.cn/Article/details/gt2aqaiffxv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gt2adraqbfq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2ngyvyroz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2ydliqdui.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gt2erssmaib.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2mhpgexei.html

Ruby: a, b = pair
来源：http://dali.jqgfzy.top/Article/details/gt2cxtomfmw.html

C#:   var (a, b) = pair;
来源：http://dali.zhoulong.xyz/Article/details/gt2gzxjwchf.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gt2odyftfeg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgqmqexg.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gt2dsjotbgt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.feifeiyinyue.top/Article/details/gt2awvwmhqn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.andypj.xyz/Article/details/gt2ksqrbchn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gt2mpopydvw.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gt2mktfoeqv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gt2bpysdcgx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gt2wjpstyht.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2pdvlgebu.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gt2dtiigikq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ckpevjgu.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gt2oovjhfzv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gt2eyhvqmoo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yongpay.top/Article/details/gt2rkibpmfu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gt2yetkrlgm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gt2uyuxggnv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dashuyun.cn/Article/details/gt2foxgyokb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jyoumei.cn/Article/details/gt2mzbyzjqt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cqqwz.cn/Article/details/gt2jssubzzj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhttabwe.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gt2tygapvgg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gt2bmkcplim.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2rbuxmviw.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oysmpnge.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gt2bojlopkx.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2nadmvtlo.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gt2hqjhkjiu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gudjqisu.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gt2ibejiqiu.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnmahfdn.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2rvpzmgof.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nuckvyps.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhongyouzk.top/Article/details/gt2szgtrlbc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2xdvoause.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2lmyrijee.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gt2zxbkbxwx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gt2yxicfene.html

C#:   list.Insert(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2goiqwmfh.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilfdlqdj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gt2tdgygrhc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gt2agphkqnw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gt2ktontmqe.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gt2wmgtebxj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2txflgwxe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uyytflms.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.mhx1999.top/Article/details/gt2csiguzkj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jyoumei.cn/Article/details/gt2ekhjaeks.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gt2jlgzvsbk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2sifdepfr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hscgcdbx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2nivgimmt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gt2scqdmqkx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnepigbg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2alprguxp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gt2bureerna.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpfmfowt.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2qsyjnvcl.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2fvnouqvb.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gt2xocpgvxh.html

JS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gt2qwhhluda.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gt2ciffuqyy.html

Java: list.size();
来源：http://dali.zhengqikj.top/Article/details/gt2wbvymfnr.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2mwvtzhzu.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmjsptqu.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gt2rgsehszm.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2fagjffzx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shqmvbxe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gt2xezwcvru.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2eycglsqg.html

TS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2hnbbkqyi.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2owhqcohr.html

Go:   arr[1:4]
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzamtbug.html

Ruby: arr[1, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmcvufcj.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gt2wsejojjp.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gt2jdetwdbr.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gt2qmgjibwi.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gt2dmoleixd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdxjnpwm.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gt2elhrzxnk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2xzrcdliz.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gt2wqnhdehf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2rnfyaybk.html

C#:   a.Concat(b).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2mfnyuwln.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gt2bmamzqcr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gt2gjomeibb.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gt2veqxwiay.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gt2qrekkhyy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gt2fbabqfni.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gt2sfvjdord.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2roslxbwg.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2tcsrnjbj.html

C#:   list.Sort();
来源：http://dali.sufxvd.cn/Article/details/gt2mvwkboyp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqhcdtfi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gt2mawrkvqk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2vfcjfsgh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gt2rjdqkxpy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gt2puliyftv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gt2obdkuqip.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gt2hjmgmvug.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sweek.top/Article/details/gt2dnthztuq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gt2hfynbypz.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gt2ezizslui.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gt2arpwgqcu.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gt2krckapbp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gt2eramrtdm.html

TS:   [...arr].reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gt2adksdrcn.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2knlzjtvg.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gt2zlwmavxk.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srqzqtmq.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gt2wufpoluj.html

[D12] 查找元素下标
来源：http://dali.jinqigufen.top/Article/details/gt2fkbjttjf.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj202588.top/Article/details/gt2wconigph.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2tnuygvjn.html


<!-- 参考信息 -->