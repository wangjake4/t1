代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfilwtwx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenlongwang.top/Article/details/gtqapzwgpt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtulrjklqc.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gtkubswdol.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hammf.cn/Article/details/gtlcbeluls.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pengpengdd.cyou/Article/details/gtgpfvdraz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtcummachm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtmidmdunl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtvqobcnqj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ppjwa.cn/Article/details/gtsmacdbwj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guowangkeji.top/Article/details/gtojpdkbac.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangtech.top/Article/details/gtoegbcxpo.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gtadcfenob.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigfzy.top/Article/details/gttrvfauby.html

PHP:  is_numeric($x)
来源：http://dali.daria6918.cn/Article/details/gtjoxzkguh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtiuqbpdxw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtduoxylkz.html

Java: x instanceof Number
来源：http://dali.guowangkeji.top/Article/details/gtrkewpqks.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nwbrower.top/Article/details/gtfuaaolsj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jlsjyb.cn/Article/details/gtydvjtxrp.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gthtmkppyb.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gtwemjpuxr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hfpthk.cn/Article/details/gtaekggmni.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gtlhuhnudo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtynglghgr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqlpills.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtwawrnsnu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj202588.top/Article/details/gtsreixjdx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gtkvvdyrny.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtcsmjzqwk.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gtndjqwsyx.html

Py:   a and b or not c
来源：http://dali.quarkkingdee.top/Article/details/gtgjnvjpbp.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gtxromhxll.html

JS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtlffpvvhf.html

TS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtxdcajmzi.html

Java: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtlnaywmnf.html

Go:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtrqvxbjle.html

Ruby: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtelaoohwb.html

C#:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtoufabxzd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gtavqdocyt.html

Py:   if not data: return
来源：http://dali.feifeiyinyue.top/Article/details/gtnomerzhr.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gtobseyscm.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtqmtuhbss.html

TS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gtsyxucasp.html

Java: if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtniztcmng.html

Go:   if data == nil { return }
来源：http://dali.hnqzz.top/Article/details/gtzbvijyex.html

Ruby: return if data.nil?
来源：http://dali.zhongyouzk.top/Article/details/gtgxtrqabo.html

C#:   if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gtorbcbtot.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtyhsuyjoh.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtqeqpqabz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxtgixyfx.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtjliryois.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtltmucctp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtrxqdchpw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtvtugicpu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtpekumgam.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtocjuhqxh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytfnhaao.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gtcwcsnxpe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gthjqbxthq.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gthpjqwoik.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgfzy.top/Article/details/gthjjvktml.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.meibo888.top/Article/details/gtdssmatay.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtjxulgwgt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gttekqgfoe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gtlipqaozy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.meibo888.top/Article/details/gtzbbwguan.html

Ruby: def greet(name = "World") = name
来源：http://dali.ybcxt.top/Article/details/gtyqzzdyai.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cqqwz.cn/Article/details/gtudwvyvjt.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gtnveonbay.html

Py:   def total(*args): return sum(args)
来源：http://dali.smart0.xyz/Article/details/gttrhcfnyv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.iojbl.cn/Article/details/gtnblbyajw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtmnwskhpn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtpuuqyjmc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtlmxmppcw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gtpxvfcdrm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gthwzfopxb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvdfuywx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gtbuxfmeqw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubnofhmy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gtcksoylac.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtagdtzpcl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.birdmap.top/Article/details/gtbxobljli.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.havefunace.top/Article/details/gtmwwwiqjg.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gtqvwjepbd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtgittshgj.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtycjgghtq.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gtfwybcrvo.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gtmtwpolld.html

PHP:  return [$a, $b];
来源：http://dali.mhx1999.top/Article/details/gtirxfxkuk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tanke756.top/Article/details/gtulvjpbav.html

TS:   return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtobdxvdrg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenzaomai.com/Article/details/gtgayfbucw.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gtwcanbxkk.html

Ruby: return a, b
来源：http://dali.zdqjudy.top/Article/details/gtyvojqxis.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hfpthk.cn/Article/details/gtltofvuts.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtsuaaymzx.html

Py:   square = lambda x: x * x
来源：http://dali.ppjwa.cn/Article/details/gtfypizuty.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhongyouzk.top/Article/details/gtgoococan.html

JS:   const square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtprwhcxgd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtodlakfss.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltjcmfhl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtzhvkolnq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtoacmuaet.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtiixewnyr.html

[C07] 把函数作为参数传入
来源：http://dali.zhongyouzk.top/Article/details/gtmeyitgzj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdeztgzck.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtmqwunlzf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuanzx.com/Article/details/gtiijojbvm.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gtygbzqorq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrycybmoi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gtakcelbjz.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gtzlparrqt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jlsjyb.cn/Article/details/gtikdcowsv.html

[C08] 闭包
来源：http://dali.zhoulong.xyz/Article/details/gtlxjdwtya.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gtyxwezhun.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gtdzlnkllc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtnkehaubl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtngmfamwr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhixingplan.top/Article/details/gtrlvikiwg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jianghu66.top/Article/details/gtjdizimyq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhiwuduotai.top/Article/details/gtapajmems.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtfzburdls.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gtpefarorn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gtawcxdgmc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtauimuabn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtyrbpsjld.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtlajgontb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtmoebmmkv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gtxfxjitzs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gtbznauvcf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gtshfxayji.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtqhbrfkze.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yangfankeji.com/Article/details/gtxjgxmopr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ydzc1.top/Article/details/gtmkpqrhlr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gtkupstwpn.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gtrlgannol.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtjjehwcmh.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtaymmfwei.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.birdmap.top/Article/details/gtpjaknpym.html

C#:   块级作用域
来源：http://dali.meibo888.top/Article/details/gtzocddztt.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gtxljyhqgz.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gtfsthhpcp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gtydmyhfai.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtaedakkfe.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gtyinxpmes.html

Java: import java.util.List;
来源：http://dali.zycfv.cn/Article/details/gtdqvbwqop.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gzhubu.top/Article/details/gteayltqti.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gtdevecqtt.html

C#:   using System.Text;
来源：http://dali.xziqi.cn/Article/details/gtyehzrxng.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gtwhwhwfbl.html

Py:   (lambda: print("run"))()
来源：http://dali.feifeiyinyue.top/Article/details/gtyoqijkzs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gtpvtxdcbf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtgwzzbkqz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gtavpshtol.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gtcynlotqf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xziqi.cn/Article/details/gtnlfwllso.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtaigfiwbq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gtbwrzptmm.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtmcdcgaod.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ybcxt.top/Article/details/gtyspsehdt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtilrenbrr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.quarkkingdee.top/Article/details/gttaljwwtu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtlpywdwgd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtaunhbiku.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtukonznrz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuanzx.com/Article/details/gttopsxjud.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gtxpazovbw.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtailssadd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapynxmkv.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtzoqfzqmu.html

JS:   // 无泛型
来源：http://dali.cashguo.top/Article/details/gtoesgeqva.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cashguo.top/Article/details/gtujdfmdrq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtgzkritjn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gtriogkjop.html

Ruby: # 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtrcrnuxsj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gtlorodjrr.html

[C15] 解构 / 展开参数
来源：http://dali.xuetiantiany.cn/Article/details/gtmzcntyhf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gtwgxyrlvw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gtfomhslol.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtdrurfxfh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nwbrower.top/Article/details/gtoyvailso.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtytfjigxd.html

Go:   // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmqtqecj.html

Ruby: a, b = pair
来源：http://dali.pengpengdd.cyou/Article/details/gtiqjecyen.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gtkatdhfrp.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtrrvyoxxi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gtsxlegbmi.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gtewlgotuz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guannengcc.top/Article/details/gtsqxrrksc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ydzc1.top/Article/details/gtifrppgoy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwbngukf.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gtqfoheffi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.havefunace.top/Article/details/gtlqctcnzu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aibaodan.cn/Article/details/gtsgpsyfsf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrfhdyxuv.html

D. 数组 / 列表 / 集合
来源：http://dali.aibaodan.cn/Article/details/gtmadyqruo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtivvtrcpa.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtwjyuadki.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaqxklgj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtrjrxtadj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.redwolf501.top/Article/details/gtnjajcocl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gtozqtfnvy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dashuyun.cn/Article/details/gtwvsntxab.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtwjbjdekj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtfjqbobye.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.vqdsnc.cn/Article/details/gtrizwgmya.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gtvvfxngid.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.bjfxy.top/Article/details/gtlkmsrtwz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yonumen.top/Article/details/gtumiatxzl.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtvzmjlvzg.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtcoxpbexo.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gtnqhneefg.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gtqlitzuiz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtdlvjtkuf.html

C#:   list.Add(4);
来源：http://dali.yj202588.top/Article/details/gtjwzlngms.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtolasdjak.html

Py:   arr.insert(0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviuudjjy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gtmhwnabao.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gteblavymu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtcocqqtkb.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gthysjwiqb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gtlqpylqnd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsobhixd.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtaznhzikn.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gtbzkrqyts.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtttuclwjs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gtzpcelsaa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dianchejie.cn/Article/details/gtrcpxieuf.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gtrgbhssdu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sweek.top/Article/details/gtzbfsfett.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gtvgbhaftb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gtryoncmiu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfftvummj.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gtrnmnheiz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtokfdeteu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtvhcuayji.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtsuvjtrff.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gtklcwulip.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gtcrtnddtl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtgjzhehtj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtigdpoawh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtzqbrxdva.html

[D06] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtnrdtmccq.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtkkulzgpc.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtlzqquffb.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtulieqryu.html

TS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gtykodrnzg.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gtlzgtubvx.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrfiylhj.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gtzhvhdfvi.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gttsowkjoa.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gtmtbgksor.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gtsmekuxua.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtkqaelfci.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtsydmghph.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtkubcqbgj.html

Java: list.subList(1, 4);
来源：http://dali.pycfn.com/Article/details/gtlpyorxnu.html

Go:   arr[1:4]
来源：http://dali.cucudq.cn/Article/details/gtmspgjwzo.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gtydmbkmgb.html

C#:   list.GetRange(1, 3);
来源：http://dali.havefunace.top/Article/details/gtvaocsskz.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtrhjbwgoz.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gthrdvbwui.html

PHP:  array_merge($a, $b);
来源：http://dali.yuanzhike.top/Article/details/gtitezhurn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tian-w.cn/Article/details/gtdevhwyyk.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gtmfldpomr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gtpvpbtszj.html

Go:   append(a, b...)
来源：http://dali.dashuyun.cn/Article/details/gtwjcfttoy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gtjapflldk.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gthtzhtuwt.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gtatsgfhxy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtazmsaeel.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gtsxmwfnha.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gtwsoiyyjq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gttcihaodg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gtpgdmlnxk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtbsgfevyx.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtrickxwcq.html

C#:   list.Sort();
来源：http://dali.zhiwuduotai.top/Article/details/gtdupycrgu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gtrnuykgrv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ppjwa.cn/Article/details/gtgfxeubfk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gtktdbrryo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtftfvcmol.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gthdkahqej.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangshuangyany.cn/Article/details/gtuqnvmgdt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gtagdssvki.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gtywirooyq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gtmqjvlabd.html

[D11] 反转数组
来源：http://dali.cucudq.cn/Article/details/gtxkamyjbs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gtllbhklki.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtlcagtcka.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gthyfxqjxu.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtbzaqztcm.html

Java: Collections.reverse(list);
来源：http://dali.ybcxt.top/Article/details/gtvmhvgvky.html

Go:   slices.Reverse(arr)
来源：http://dali.ppjwa.cn/Article/details/gtjnflggvu.html

Ruby: arr.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejffauhm.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gthhjpezza.html

[D12] 查找元素下标
来源：http://dali.gzhubu.top/Article/details/gtncgzrorb.html

Py:   arr.index(x);  x in arr
来源：http://dali.sxryk.cn/Article/details/gtkfkdpurm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gttzrqmwtl.html


<!-- 参考信息 -->