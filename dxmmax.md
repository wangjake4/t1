代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258.top/Article/details/gt2pyvvnsaw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gt2wdibxpch.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ivvv.top/Article/details/gt2pdykiejk.html

[B12] 跳出多层循环
来源：http://dali.yueranfly.top/Article/details/gt2iencydpw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yuxming.cn/Article/details/gt2rqblwicp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yueranfly.top/Article/details/gt2eychufho.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gt2zgkxlzca.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gt2kltegqyx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2zefvcruz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aizwys.cn/Article/details/gt2zxgflcrs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wswqvobo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gaohongyu789.top/Article/details/gt2dhuiifdp.html

[B13] 判断是否为数字
来源：http://dali.nwbrower.top/Article/details/gt2oegaahdi.html

Py:   isinstance(x, (int, float))
来源：http://dali.aizwys.cn/Article/details/gt2gfyiijxb.html

PHP:  is_numeric($x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmzjqwja.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhvrsdym.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gt2azfxmtgo.html

Java: x instanceof Number
来源：http://dali.ehwqpu.com/Article/details/gt2hlktigkh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sufxvd.cn/Article/details/gt2gqcanhco.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuetiantiany.cn/Article/details/gt2shwzyswj.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gt2shzuomdb.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gt2kqqpvyxx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gaohongyu789.top/Article/details/gt2dustdkgu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qobdlzdy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2rxjkqxmc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2wqfgjyfu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2psaqybtl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gotoacloud.top/Article/details/gt2ekgpxole.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gt2mnalitpv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gt2twxlkmsm.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gt2cferfgwi.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gt2zqixyrvt.html

PHP:  $a && $b || !$c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgazmzil.html

JS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2iiteplzp.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2kafgdpjk.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2lkfvqxxy.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2kktonohp.html

Ruby: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxvxzwgr.html

C#:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2jnmpmwwj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.0kj1m.cn/Article/details/gt2iexgxsfj.html

Py:   if not data: return
来源：http://dali.fzhhl.top/Article/details/gt2nqziyduk.html

PHP:  if (!$data) { return; }
来源：http://dali.aibaodan.cn/Article/details/gt2szivclut.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdrcxmji.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2palssvhu.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gt2xotgddcq.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sawuuuen.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gt2gctadhok.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtzslsri.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2mewgyoqo.html

C. 函数与作用域
来源：http://dali.fengsongda.top/Article/details/gt2tavqgpnr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2cebyqppn.html

[C01] 定义函数
来源：http://dali.xuanzx.com/Article/details/gt2jwbilfun.html

Py:   def add(a, b): return a + b
来源：http://dali.daxiang520.top/Article/details/gt2vfeomgys.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2hjhunyop.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2wpivkjql.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2pgqmnfie.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2ndfwufei.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zycfv.cn/Article/details/gt2jfievcie.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ppjwa.cn/Article/details/gt2lzhdqbxp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2zphezleh.html

[C02] 默认参数
来源：http://dali.vqdsnc.cn/Article/details/gt2vqvkkguz.html

Py:   def greet(name="World"): return name
来源：http://dali.hammf.cn/Article/details/gt2ejjyqiof.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ybcxt.top/Article/details/gt2czpznyfk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2cvcchvcj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2gihvnefx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nwbrower.top/Article/details/gt2ksoxlnhq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gt2wjatwgum.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gt2nuaanwac.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.andypj.xyz/Article/details/gt2atrblcih.html

[C03] 可变参数
来源：http://dali.yj20258888.top/Article/details/gt2vvxgvnso.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gt2elgapxyv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigufen.top/Article/details/gt2ywmjjrxw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gt2vgvmbzyy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gt2qhbnypgq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gt2oeurdhsc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gt2lzswmjmb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yvedp.cn/Article/details/gt2xmhvatpn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hysaishi.cn/Article/details/gt2cfmqcwgv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gt2paflikge.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cdnleiting.top/Article/details/gt2drpojfyr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frbcnsnk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2rfkeasik.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guowangkeji.top/Article/details/gt2pjrsoerb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.redwolf501.top/Article/details/gt2pfnjntxh.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gt2kthsqtcl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gt2rzieaooy.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gt2vlfomlvz.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gt2cmhfstam.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gt2mncimmkj.html

PHP:  return [$a, $b];
来源：http://dali.jinqigfzy.top/Article/details/gt2gbyckmki.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hammf.cn/Article/details/gt2lwhqddbw.html

TS:   return { a, b };
来源：http://dali.c1oappe.top/Article/details/gt2rtrulxwn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.svipenyu.cn/Article/details/gt2wpimtuzv.html

Go:   return a, b
来源：http://dali.bjfxy.top/Article/details/gt2dravwzqv.html

Ruby: return a, b
来源：http://dali.9152youxi.cn/Article/details/gt2ardkjcpu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gt2flazgpcg.html

[C06] 匿名函数 / lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mltnyicr.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gt2sqeyxhwj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cdnleiting.top/Article/details/gt2qmnatdoo.html

JS:   const square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2mwvjygem.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2wbesilnh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmhwnrjk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cdnleiting.top/Article/details/gt2vunxlxnf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cashguo.top/Article/details/gt2kqelllgq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gt2lidysder.html

[C07] 把函数作为参数传入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjrtvzvu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sufxvd.cn/Article/details/gt2denmcxnv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2dbwnejif.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gt2kjtgxlrh.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gt2kfpiyqhp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daxiang520.top/Article/details/gt2pjswgoxg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.vqdsnc.cn/Article/details/gt2ozikbvnv.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gt2xznlyxev.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gt2nmghzxma.html

[C08] 闭包
来源：http://dali.nanxuanxn.top/Article/details/gt2gsndqrue.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gt2oyuvivke.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yonumen.top/Article/details/gt2pmyuwwby.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2bekihyyh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gt2idwswbfx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gt2bzczomvu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hysaishi.cn/Article/details/gt2gywrgdik.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.9152youxi.cn/Article/details/gt2cwhmqpap.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stoqgunc.html

[C09] 递归
来源：http://dali.hfpthk.cn/Article/details/gt2pyktbwqz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfkaaedv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gt2digdwkpn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gt2mcgsqqgc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gt2hcrdiptj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gt2aosnuyee.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cashguo.top/Article/details/gt2xgpfxtiv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gt2xwxbcqms.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gt2yvpkouti.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gt2cnaqkrhy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cashguo.top/Article/details/gt2lgpexpal.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.316326.xyz/Article/details/gt2llipuwyd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gt2fxiujrdy.html

TS:   同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2unahqjnr.html

Java: 方法内为块级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2dsgnughq.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifghejxw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jiagoushi.top/Article/details/gt2orwirvqn.html

C#:   块级作用域
来源：http://dali.gzhubu.top/Article/details/gt2ejjioear.html

[C11] 模块导入与导出
来源：http://dali.zhixingplan.top/Article/details/gt2wjvkjyth.html

Py:   from module import func
来源：http://dali.cashguo.top/Article/details/gt2qedablsk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gt2iquyhhrq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gt2kxcyluoe.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gt2auusityi.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulbpddrw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gt2pjdihdgj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gt2zqohejpx.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbxofhjv.html

[C12] 立即执行函数 IIFE
来源：http://dali.daxiang520.top/Article/details/gt2tzazmrfk.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gt2saaqdzpi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.vqdsnc.cn/Article/details/gt2zgkidawu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcmcvzkp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gt2xycnbihc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gt2ooavhfvk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aibaodan.cn/Article/details/gt2wpvtadsp.html

Ruby: -> { puts "run" }.call
来源：http://dali.jianghu66.top/Article/details/gt2iiarehxc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gt2fmkndkvg.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gt2hlydvzab.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnqzz.top/Article/details/gt2zjuzfcfo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2ygtonryr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangdashe.top/Article/details/gt2uzhwkmul.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2xiiysydb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lqyjfqpr.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gt2esbuazif.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gt2ngehutru.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gt2elnpcldi.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gt2ioiqjqbi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gt2dfhqbnoy.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gt2vdjakmvd.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2gbaokyjl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzurknbf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gt2qqsirhug.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gt2xbcznspj.html

Ruby: # 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2jzcnyjya.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gt2sniyhcqh.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gt2cglrhsmd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gt2oantxcaj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sweek.top/Article/details/gt2wekfddvv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gt2acvuvglp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2oluhdvoe.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2pwtedvtn.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gt2jgwxuthk.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gt2zfsrwvks.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gt2fchadrcc.html

[C16] 函数 / 方法重载
来源：http://dali.zhoulong.xyz/Article/details/gt2mcmpogwr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gt2zmiparif.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gt2qhbkoznr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gt2sukpcupo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pipuakiv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2nqkithhx.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gt2illoxnps.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gt2xflrupwd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gt2cbkoxkdh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbounqum.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgfzy.top/Article/details/gt2hgydadxg.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smawaopq.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gt2dixagyjf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gt2lziueuei.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gt2rarxfbrw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gt2banqwabg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gt2jybwpdlw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuanzx.com/Article/details/gt2zqbkzhpb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sweek.top/Article/details/gt2jnmaelzq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gt2avfdtomv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.birdmap.top/Article/details/gt2qtdlyckw.html

[D02] 追加元素到末尾
来源：http://dali.hnxiangtu.top/Article/details/gt2wyyjdtzj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.iojbl.cn/Article/details/gt2kvgacyxl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiggikgo.html

JS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gt2fsuhxxmj.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gt2jofguvqu.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2glyckbyt.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gt2lhsnumpw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gt2vycfozsx.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gt2puoluofk.html

[D03] 在指定位置插入元素
来源：http://dali.daxiang520.top/Article/details/gt2uzaexqao.html

Py:   arr.insert(0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2pdjgdmlj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gt2ioikzbiq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gt2dutckcqr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gt2qkrbuplr.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2woxkqhgd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gt2hqbulkqp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gt2crmynhjb.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2injfgufm.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2qpxwzlkf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258.top/Article/details/gt2trufztsp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oezutibl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gt2zwqhnqyd.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gt2bzwynexa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gt2tvqjbzoh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftgbeuur.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfdrppuq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gt2ypxzngra.html

[D05] 访问与修改元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvrbhwwf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2kbxgeqre.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gt2kbezlyyk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2fzabujht.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gt2hqfekukz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gt2vpadbdeu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2pzqzlujz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghkpqmyf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2epircgep.html

[D06] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gt2hnrhrxro.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gt2hvwoodkz.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gt2enriwcji.html

JS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2dodhkeqe.html

TS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2jfzemhvj.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gt2ogdjscqw.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gt2xjspcivi.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gt2ayxewqqr.html

C#:   list.Count;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eizxitpk.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gt2gxmuztdm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gt2xhhpgcqq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2hsbgmvrd.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2pngupikf.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2oykdaneq.html

Java: list.subList(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gt2nmsoxoht.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gt2hworzywg.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gt2xcidojlz.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenlongwang.top/Article/details/gt2zcmmzyiz.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gt2cxuztkoq.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gt2taqtbxws.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbujihdq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2unzhjpiu.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gt2tgeziwoz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wiyqgkaj.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gt2xufctooa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gt2smeaigrp.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2pceqzoys.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gt2yysppeuv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gt2bhanqizz.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2gjiwpyxc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdjewbwe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sweek.top/Article/details/gt2dijowrek.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gt2xjrgkhwg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gt2omlovojz.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gt2iwnzeuyn.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gt2ywdsojld.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.smart0.xyz/Article/details/gt2csuymssc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.iojbl.cn/Article/details/gt2eonjpwbc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gt2vrcvhfsw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gt2nzumhtnk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dnfopftw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gt2rwymvasd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sufxvd.cn/Article/details/gt2vytpxsfg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gt2awushrdp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsjhmllj.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gt2pqnqlsfa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wclwqbpc.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvbqgbtc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gt2yvmxpvii.html

TS:   [...arr].reverse();
来源：http://dali.sysykeji.top/Article/details/gt2jaosxlxs.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gt2lnxkhrtz.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2kzjxaqnv.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxhlghaz.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gt2huyilhcy.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gt2ougusiww.html

Py:   arr.index(x);  x in arr
来源：http://dali.shuidangran.top/Article/details/gt2mecnvlfl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfuebgrf.html


<!-- 参考信息 -->