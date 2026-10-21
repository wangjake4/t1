代发 wailian999

[B13] 判断是否为数字
来源：http://dali.ehwqpu.com/Article/details/gthxaxanpr.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gtpccrbgkw.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gttoegigpf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtqeceohex.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtyusibupf.html

Java: x instanceof Number
来源：http://dali.yj20258888.top/Article/details/gtzzzbameb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigfzy.top/Article/details/gtdmmanyyx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gtfbjuwcpw.html

C#:   x is int or double or decimal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezezyfga.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gtghndgojn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hfpthk.cn/Article/details/gtywgxtyvx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jlsjyb.cn/Article/details/gtjrdouzem.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdssjdyn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtfyfrevsj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ydzc1.top/Article/details/gtvgwetmdx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yanxiufei.cn/Article/details/gtpnmmpcev.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtmvbnuhur.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtfukyocqa.html

[B15] 布尔运算与取反
来源：http://dali.jinqigufen.top/Article/details/gtufemgoxr.html

Py:   a and b or not c
来源：http://dali.wangdashe.top/Article/details/gttxrpdbnm.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gtcepuhqhz.html

JS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gttjlnmqtm.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtkvkqrhmt.html

Java: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrrodpmq.html

Go:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtdjtbbvyx.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxnpqdav.html

C#:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtxsjyzdvz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258.top/Article/details/gtkkkitxjf.html

Py:   if not data: return
来源：http://dali.xziqi.cn/Article/details/gtrffiuhwr.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcckctyl.html

JS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtevtsjuzc.html

TS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtxdfpjtxt.html

Java: if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gtlynyfvrj.html

Go:   if data == nil { return }
来源：http://dali.birdmap.top/Article/details/gtelvewwrp.html

Ruby: return if data.nil?
来源：http://dali.ybcxt.top/Article/details/gtdomirkjp.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gtncwfthin.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmsrqkazr.html

C. 函数与作用域
来源：http://dali.zhixingplan.top/Article/details/gtxumtdkor.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvafijozw.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtgqgiwhri.html

Py:   def add(a, b): return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtagkoonee.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtabpdukxr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiumnafw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtxmiegzjb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtaffhsllp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtfgbvfgvl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlyyqxcl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtalncsruu.html

[C02] 默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtiaxapbur.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgfzy.top/Article/details/gtvhdrlmus.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gtpldxcsbm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtwgjsycry.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gthbjexacp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gtwxqbemvq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gtvqsmooed.html

Ruby: def greet(name = "World") = name
来源：http://dali.snrcjt.cn/Article/details/gtxhhncubn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.svipenyu.cn/Article/details/gttcfvdcpm.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gtjbvhgdwc.html

Py:   def total(*args): return sum(args)
来源：http://dali.yangfankeji.com/Article/details/gtclumxdmq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gthynjlhnp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtpgmipgbn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gthhcilvom.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gtlucfjlga.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gtlwrpmcjk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtketdxbpk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinghuilouyu.cn/Article/details/gteokykexs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gthasoltee.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gtcaopbiba.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cdnleiting.top/Article/details/gtzamapobm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtkdtoywyc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tanke756.top/Article/details/gtmtzvdudc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hongshengwenyu.top/Article/details/gthdgeohwo.html

Go:   // 无：用配置结构体参数
来源：http://dali.gaohongyu789.top/Article/details/gtcqliuubg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtlpawakya.html

C#:   f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtsmaaqzcr.html

[C05] 返回多个值
来源：http://dali.c1oappe.top/Article/details/gtjanhyfof.html

Py:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtpwiqzzgs.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrwbxgyp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtlsxctxhk.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtrumxwadi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.redwolf501.top/Article/details/gtpcfpcspo.html

Go:   return a, b
来源：http://dali.yueranfly.top/Article/details/gthbovnzcl.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gtsuxrktiu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gtvefbhdep.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtipdgnlcq.html

Py:   square = lambda x: x * x
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuygkrtir.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shzxlz.cn/Article/details/gtvkrhumkr.html

JS:   const square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gtyyuqokaz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtskjpyyxt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtqxlxmibf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gtwvwmkcsx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gtxpkpjyto.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtumqjawuc.html

[C07] 把函数作为参数传入
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzxllqif.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhengqikj.top/Article/details/gtmftazzqm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.meibo888.top/Article/details/gtenbppqtp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gteafcistl.html

TS:   arr.map(String)
来源：http://dali.zhoulong.xyz/Article/details/gtmylrpihh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtgnhxursy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gtzwcfaucn.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gtbmwcasdn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gtbcmevegx.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gtadacfsbl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gtmgkwjydr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ehwqpu.com/Article/details/gtpdltvpao.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtxsdyqwan.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtnsihcfqd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangshuangyany.cn/Article/details/gtvggtnavh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yanxiufei.cn/Article/details/gthfxapibb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gtujjmnpei.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtpfkxycjs.html

[C09] 递归
来源：http://dali.yanxiufei.cn/Article/details/gthpkguuup.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtlxzrefvg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthjftvrps.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gttpodigiy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtdhevudyb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gteoeoxrzd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gtkihisqmf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtjgnatmhj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fzhhl.top/Article/details/gtzebfkzla.html

[C10] 变量作用域
来源：http://dali.316326.xyz/Article/details/gtfnciloec.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gtfoflkllu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gttgzznsel.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gtmevxiuow.html

TS:   同 JS
来源：http://dali.shzxlz.cn/Article/details/gtrgdrzumk.html

Java: 方法内为块级作用域
来源：http://dali.cashguo.top/Article/details/gtzdmehukc.html

Go:   花括号块级作用域
来源：http://dali.shuidangran.top/Article/details/gtyhltfbtp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yvedp.cn/Article/details/gtjmiyhxdf.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gtcwwlbaed.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gtsqfsdzyf.html

Py:   from module import func
来源：http://dali.xylfe.cn/Article/details/gtadarpqvq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shzxlz.cn/Article/details/gtbmmrbjlb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.birdmap.top/Article/details/gtiljxpior.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gtwvntgafa.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniwkjssz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.0kj1m.cn/Article/details/gtarbgjpez.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gtyytcvdxt.html

C#:   using System.Text;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgshrgdi.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigfzy.top/Article/details/gtjhvrylyx.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gthenylcxe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hywenlv.cn/Article/details/gtreiucvpo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtfrrfflox.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtwnzymsyy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258.top/Article/details/gtmlzoixds.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sufxvd.cn/Article/details/gtbgepfrqe.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gtefqsdhkp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.haohaochexian.top/Article/details/gtftsxkjtn.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gtwlxmbync.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xziqi.cn/Article/details/gtevhtbovm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtzddkkxzg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhengqikj.top/Article/details/gtnstxdhmk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtkodpaypo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtahfkbwvv.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gtzppoaprs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gtvndnupqj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daria6918.cn/Article/details/gtcyngfvbs.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gtungjuaxw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenzaomai.com/Article/details/gtalfbsxme.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtmzhvumcd.html

JS:   // 无泛型
来源：http://dali.xinyue.icu/Article/details/gtnziltulr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gtrgbvzdss.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfzjjglu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtyupwawwe.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtfllubmed.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gtzbtqzdta.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gtfmazovbb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258.top/Article/details/gtnhzhncvp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gtaglebbgr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtpqxsegyt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gtqyuimzbp.html

Java: // 无解构
来源：http://dali.shuidangran.top/Article/details/gtieqqeevu.html

Go:   // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gtbfctmhaf.html

Ruby: a, b = pair
来源：http://dali.xziqi.cn/Article/details/gtupdwwboh.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gtpbgugtqk.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gtqdixtpml.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gtrlrwbtmj.html

PHP:  // 无重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gttylbgfpi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gtxofmyduh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gtgtrfeuzf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtcpwmqyfr.html

Go:   // 无重载：用不同函数名
来源：http://dali.gaohongyu789.top/Article/details/gtgqbkllht.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gtfdialvhl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gtvsfdkhst.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzylppwzk.html

D. 数组 / 列表 / 集合
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkspossy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpqtnduze.html

[D01] 创建数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gtzbwqsnlv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gtbzffvoct.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtnihnbmwc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gtsxhzbhmf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gtlopvmjor.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvkmumyr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.bjfxy.top/Article/details/gtkwdtuins.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtqdcilmuc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gtckaufrjk.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gtpislbipl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.kuanghao11.cn/Article/details/gtkirxsqfc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenlongwang.top/Article/details/gtkrktmgam.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtpbmslirb.html

TS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtkgwqedjv.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gtyznbkakr.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpzhygxz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gtrjpztzsl.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gtbacuhgex.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gthusrospc.html

Py:   arr.insert(0, 0)
来源：http://dali.hywenlv.cn/Article/details/gttkktytui.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gtczfxxtvx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.haohaochexian.top/Article/details/gtposkhies.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtnycudbqh.html

Java: list.add(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtoxewljdo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzetctgz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdzetmxx.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtgxhbulle.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtfqtzautg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gtxxquxxqf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gtpwawugdh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gtlemwkqee.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtmskukwbe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gtnhzrxety.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsummtmb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ivvv.top/Article/details/gtfmjeaeli.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gtoynxutkx.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtpbwuixby.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtotfpquoz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtcfyjmcnf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtxslqmsci.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zdqjudy.top/Article/details/gtzpbxxjvp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmsaeyhh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtypapnisv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtwdpefxmk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtivtwcwox.html

[D06] 数组长度
来源：http://dali.ivvv.top/Article/details/gtdorvgkji.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtvjntdvys.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gtusyatzrd.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtcqgwntbz.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtmfctrueo.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gtbqhnizvy.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtlmlpleun.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtgemstlcc.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gtudsrqgwk.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtuhmfdual.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gtkxxvstqo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gtprabrvac.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtirfoqawc.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtldqcisda.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtwgjsqwoi.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gtvvnqrtlp.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gttquwvgyj.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsxikdlo.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gtuyptppjd.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gtxhzwuquk.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gtleylkpvx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtlbjskats.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gttiatarhl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtkqojlnzg.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gtpvxuslgx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gtnbdgtpba.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gtjoepbukr.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gtenrzswch.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gteipvjluw.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gtpoqxchqq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqzofrjy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtdgqwccvo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdznrccjr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtvpkaxisf.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtkjylfnuj.html

C#:   list.Sort();
来源：http://dali.xziqi.cn/Article/details/gtuguwxrgi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvelwlrwq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gtfkkzeqbt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gtfjapeudi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtsqfhucbp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtdyrrplnc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhongyouzk.top/Article/details/gtxttsuxlz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gttxbxjljz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gtzgxipqht.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gtvqcdxzth.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gtmzcwqobt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtftkbffwe.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtsxrzgija.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuxming.cn/Article/details/gtdjuypjhx.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtkndrimvl.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gtoicxhbkn.html

Go:   slices.Reverse(arr)
来源：http://dali.cdnleiting.top/Article/details/gtwfolgbqx.html

Ruby: arr.reverse
来源：http://dali.havefunace.top/Article/details/gtdrhqejqs.html

C#:   list.Reverse();
来源：http://dali.cashguo.top/Article/details/gtkvgpsqij.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gtzsntnrza.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtbisjsoxt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jianghu66.top/Article/details/gtfdkltlmo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtufxypbii.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtbhluztun.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gthpwcpugi.html

Go:   slices.Index(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenfgixsk.html

Ruby: arr.index(x)
来源：http://dali.vqdsnc.cn/Article/details/gtmfnamyfo.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gtjalwcorf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gtgvdyqmnx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tianlin.xyz/Article/details/gtptmjnnnq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtlvoboyvt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtfewwqpni.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtgoikcjbh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtedylduso.html


<!-- 参考信息 -->