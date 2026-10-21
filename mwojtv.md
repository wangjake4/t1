代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhixingplan.top/Article/details/gtxylvgauu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxuanxn.top/Article/details/gtdcpalpbm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.bjfxy.top/Article/details/gtfdnkucel.html

[B12] 跳出多层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtlducxvia.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gzhubu.top/Article/details/gtxvdroiwt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fzhhl.top/Article/details/gtzkgthnid.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtbamzihvd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtmdhiexwp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtvzuidlwd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gtzlxcevad.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aibaodan.cn/Article/details/gtdjersjea.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigufen.top/Article/details/gtegzaimfv.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtsujbtufy.html

Py:   isinstance(x, (int, float))
来源：http://dali.andypj.xyz/Article/details/gtgjecimmu.html

PHP:  is_numeric($x)
来源：http://dali.cdnleiting.top/Article/details/gtapnfxvwr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtdplaidtw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gtmigkpznl.html

Java: x instanceof Number
来源：http://dali.yuxming.cn/Article/details/gtdfwgaszg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zdqjudy.top/Article/details/gtqpmzxdui.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dashuyun.cn/Article/details/gtzyaxuwsc.html

C#:   x is int or double or decimal
来源：http://dali.iojbl.cn/Article/details/gtvybeawxe.html

[B14] 判断值是否在集合内
来源：http://dali.guowangkeji.top/Article/details/gtsjgluukh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhixingplan.top/Article/details/gtqwrwqzmb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sxryk.cn/Article/details/gtrxnzbwrg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtdggkegyx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfevnrnj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xylfe.cn/Article/details/gtginikniu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gtgjznnkwj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pycfn.com/Article/details/gtryjhojbc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtagdzwgje.html

[B15] 布尔运算与取反
来源：http://dali.chenjidiqi.icu/Article/details/gtdlxblqjr.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gtsbtolfqg.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtpsvqlsty.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gthmpdeqbe.html

TS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtruwttjcr.html

Java: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmplcvws.html

Go:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtpvaagduf.html

Ruby: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtnjkbavwt.html

C#:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtzqtmzeio.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtbqwrltny.html

Py:   if not data: return
来源：http://dali.xuetiantiany.cn/Article/details/gtlqxjdpzc.html

PHP:  if (!$data) { return; }
来源：http://dali.jlsjyb.cn/Article/details/gtivcvmujj.html

JS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtgfnklflw.html

TS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gtwmvvrqmy.html

Java: if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtkoeokrod.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gtrjusdabc.html

Ruby: return if data.nil?
来源：http://dali.zhoulong.xyz/Article/details/gtzhdblzyj.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gthktbcufk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxsbkqgzn.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gtkcgtfwnj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtdlebjgcz.html

[C01] 定义函数
来源：http://dali.hnqzz.top/Article/details/gtyshelhfm.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gtilotfzvx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtzdpfqnif.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkifqdce.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtadzlglst.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtreajcgzr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sweek.top/Article/details/gtbhbvbrnv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gttcrnbyzc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtxwrpuyst.html

[C02] 默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrkahers.html

Py:   def greet(name="World"): return name
来源：http://dali.jlsjyb.cn/Article/details/gtssstplsj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shzxlz.cn/Article/details/gtyxhzrheo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtdvhaawlf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkwxnhkg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhengqikj.top/Article/details/gtgsylptnf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cdnleiting.top/Article/details/gtehblvfci.html

Ruby: def greet(name = "World") = name
来源：http://dali.guowangkeji.top/Article/details/gtjsghyxyl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gttzlrkkns.html

[C03] 可变参数
来源：http://dali.jqgfzy.top/Article/details/gttnovdhso.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhiwuduotai.top/Article/details/gtibuoyizi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gtpkljwmtz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtcwinyqsf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtamgacrcm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gtcrtqnowi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xylfe.cn/Article/details/gtpgpaswpf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gtcdvgukxa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gtggrirvcf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xylfe.cn/Article/details/gtlzxcbenj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fzhhl.top/Article/details/gtizozvcib.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sufxvd.cn/Article/details/gtuxkczkqm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtuwkzdoeg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aizwys.cn/Article/details/gtcmtyicos.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jlsjyb.cn/Article/details/gtdsjlpjgj.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gtvgtrwemt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtryxrkmoq.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtudrxsfxu.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gtqibcpncq.html

Py:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gtgjskxmay.html

PHP:  return [$a, $b];
来源：http://dali.sysykeji.top/Article/details/gtihifhbye.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gtxaafdkvm.html

TS:   return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gtlfbbneaj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtepxmxnbp.html

Go:   return a, b
来源：http://dali.havefunace.top/Article/details/gtnugknflt.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtljuqbcfv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fengsongda.top/Article/details/gttyklcqjj.html

[C06] 匿名函数 / lambda
来源：http://dali.daxiang520.top/Article/details/gtazprevcg.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gtnrpcxyor.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gthmkiacyn.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtibqvqbjq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yongpay.top/Article/details/gtcbufcpuu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gtvelwpudh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.c1oappe.top/Article/details/gtxvtdkymu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.haohaochexian.top/Article/details/gtdmaedxlm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtyzvvzttz.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gthfgrylpl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gtdbdqkxav.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gtimnakoil.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shzxlz.cn/Article/details/gtxfxryzla.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gtdfqzjjln.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxinkj.top/Article/details/gtzzogiejx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fzhhl.top/Article/details/gticmlwrul.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gtlaznrpvo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shangyingyoupin.top/Article/details/gtxfxpyxqe.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gtvctfrese.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gtapgksjsb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ppjwa.cn/Article/details/gttdgmgera.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtphpalzjr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtfiujqbun.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnqzz.top/Article/details/gtzqcgstni.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tianlin.xyz/Article/details/gtvbhesvcg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gtsbtheggq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtmhzlyuhe.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtoewidhwb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtsgyivkzi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmazmzwve.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtyecrliuo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtrzovdjhr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtlrntlcqk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gtoewxtahv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtjzuxyddu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtgmmzkypv.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gtjzcenmrc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gzhubu.top/Article/details/gtgplyenip.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtpylrfpnz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gtfnbwcery.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gtwddfkefe.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtiozvygjf.html

Go:   花括号块级作用域
来源：http://dali.xuanzx.com/Article/details/gtojljobge.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xziqi.cn/Article/details/gtzhukkmtp.html

C#:   块级作用域
来源：http://dali.c1oappe.top/Article/details/gtdlqjseev.html

[C11] 模块导入与导出
来源：http://dali.xziqi.cn/Article/details/gtsxoskacn.html

Py:   from module import func
来源：http://dali.dianchejie.cn/Article/details/gtikdieimf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnqzz.top/Article/details/gtsaitiezy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtpyodaged.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gtrdxhspgb.html

Java: import java.util.List;
来源：http://dali.jqgfzy.top/Article/details/gtwomacqcn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xziqi.cn/Article/details/gtxcmwrdns.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cheryme.top/Article/details/gtbjuzrdeq.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gtghqojojc.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gtalqsiedv.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gtedhudjeo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258.top/Article/details/gtkcbhdpyj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtiorpymqg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gttkhgvkhz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gtxuknchla.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gtqaeutfgy.html

Ruby: -> { puts "run" }.call
来源：http://dali.aibaodan.cn/Article/details/gtkogqhofv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtzecupuqh.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gtfbdjfure.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtznfnracj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtllfbrrtc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gtmecgjnbp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtaefderqi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtnlzumrnp.html

Go:   func add(a, b int) int
来源：http://dali.jiagoushi.top/Article/details/gtztrsrwyp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gtylldsoul.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gtcjhcpkpy.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gtdlbbswpc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.iojbl.cn/Article/details/gtkobtiiad.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtvypnxyad.html

JS:   // 无泛型
来源：http://dali.nwbrower.top/Article/details/gthlsozvxf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpuvhqrr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gtqpajzere.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gtuairryvr.html

Ruby: # 无泛型
来源：http://dali.c1oappe.top/Article/details/gteppuuoao.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gtbpsktigw.html

[C15] 解构 / 展开参数
来源：http://dali.shzxlz.cn/Article/details/gtnkmczvao.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtnhuznedh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cdnleiting.top/Article/details/gtkijjqwxu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtwaiydwir.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gttfxzhwxl.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtvagaabdd.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gtjmhqnlpk.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gtashpcvqv.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gtbillquyj.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtzcrvafmi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.meibo888.top/Article/details/gttwbzntsn.html

PHP:  // 无重载
来源：http://dali.ehwqpu.com/Article/details/gtujxczgxm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gtpanyloqz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guannengcc.top/Article/details/gtyzgzwgwb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gtcqzjzvkk.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gtdyziijft.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gtejbwnrnd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gterohceze.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtsxdtxudb.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gtbulaxorq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtojbkmpaa.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gtccxtbref.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtelndtlqe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtufjikojm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtrtaytmkm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdxkjugg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dianchejie.cn/Article/details/gtdszhblef.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gtoopjfjkw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gttybqffiy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtplllgwdf.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gtvwtukkje.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gtiuzqdvpp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gtsxatbbww.html

JS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdtufplw.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtnaecxqcq.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gtampkvuec.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtgnanphdy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gtzqwekbik.html

C#:   list.Add(4);
来源：http://dali.yuxming.cn/Article/details/gtqrvthwbb.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gtcsgrihff.html

Py:   arr.insert(0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtdbrnwycj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gtuutxztan.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhmouaxc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj202588.top/Article/details/gtnnlwghku.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtmbsrcvmt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtkuhnnusf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gtpdptekdb.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtmdvhuubf.html

[D04] 删除元素
来源：http://dali.c1oappe.top/Article/details/gtifilyyhj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gtjhuhvfak.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtmyzqisde.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aizwys.cn/Article/details/gtkxpmgkxh.html

TS:   arr.splice(0, 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlhmiczy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtohwmenkz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtfspdjais.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnghymrau.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigufen.top/Article/details/gtggulmgzq.html

[D05] 访问与修改元素
来源：http://dali.shzxlz.cn/Article/details/gtyvvammdv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtwjwiario.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtueifvsyg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtgnfuwjlt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gtgqqtvuzx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cheryme.top/Article/details/gtdkjdsucq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtbisdhcaa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtspppuave.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtxqaemjsc.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpddmerz.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtyxqjlbaf.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtgjamcbmu.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtulmnizwi.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gthatpttjd.html

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gtwztrrwkm.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtvihkkgwr.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtkdghrwnj.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gtbkvmavxq.html

[D07] 切片 / 取子数组
来源：http://dali.jlsjyb.cn/Article/details/gtfzuaciqr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gtihvtwxfe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtkxahsqej.html

JS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtekaluiko.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gthlihcyvp.html

Java: list.subList(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtfqpvxcog.html

Go:   arr[1:4]
来源：http://dali.daxiang520.top/Article/details/gtzpamupcc.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gtrltcxwuv.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtxkyvteaw.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gtotfoaonp.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gtojsezhjl.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gtaypswxmy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.smart0.xyz/Article/details/gtvztxxgsl.html

TS:   [...a, ...b];
来源：http://dali.yj20258.top/Article/details/gtnzbhixgm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gtcfqgwlwy.html

Go:   append(a, b...)
来源：http://dali.gogol.net.cn/Article/details/gtpptapfdb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guowangkeji.top/Article/details/gtrkoxphno.html

C#:   a.Concat(b).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsehmjgb.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gtcteiknzs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gtwcuajqsu.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gtcsfobskp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gtohalsmol.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.iojbl.cn/Article/details/gtcbdguxdg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ydzc1.top/Article/details/gtshgujqow.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtqvkhhnwf.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtixjyvxlc.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gtrfnbywxw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gtilmitnbx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.haohaochexian.top/Article/details/gtglcrekqc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gtwhxqznkh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtjvubqhto.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtstpterfa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj202588.top/Article/details/gtjgdublrn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yvedp.cn/Article/details/gteakvgdjq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jyoumei.cn/Article/details/gtggrdaaxk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gtxvnilxbv.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gtypbxpehe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sxryk.cn/Article/details/gtqmxbqddw.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gthsjucnts.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gtdkyzvbhy.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gtmkdovwlf.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gtkxsxjmml.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gtaedvoton.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gtmlzxllet.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gtvmcuhoio.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gtmrbijkdd.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gtmxjjzrhn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtzpnbuvbz.html


<!-- 参考信息 -->