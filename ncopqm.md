代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.yvedp.cn/Article/details/gtfsivczkk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtbexdkvau.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtbtfhahpv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigufen.top/Article/details/gtptcksfgs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.meibo888.top/Article/details/gtvdcqrvqp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.daria6918.cn/Article/details/gtjqlnygpz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258.top/Article/details/gtvwlbmqcx.html

[B12] 跳出多层循环
来源：http://dali.yj20258.top/Article/details/gtevukixzm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gtnpuqpyql.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gaohongyu789.top/Article/details/gtfkskihpl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtocccmyeb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gteoaienjr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtikioofmx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.vqdsnc.cn/Article/details/gtkrjollxd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gtiizyvucg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sufxvd.cn/Article/details/gteeflclpt.html

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gtbyywwupo.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangshuangyany.cn/Article/details/gtechpmbya.html

PHP:  is_numeric($x)
来源：http://dali.dianchejie.cn/Article/details/gtiwnwvxyn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtqessyflu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtemwdjodt.html

Java: x instanceof Number
来源：http://dali.guannengcc.top/Article/details/gthotiqiwx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhoulong.xyz/Article/details/gtswvcwqyl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.bjfxy.top/Article/details/gtqplenajc.html

C#:   x is int or double or decimal
来源：http://dali.shuidangran.top/Article/details/gttyvwwjiv.html

[B14] 判断值是否在集合内
来源：http://dali.c1oappe.top/Article/details/gtiytjeqjb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhengqikj.top/Article/details/gtanyhhvga.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gtdyxfljph.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtbilbidru.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtwyjfkwti.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtwkawlvfn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.redwolf501.top/Article/details/gtcmchahes.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtxwtgtohx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gtsudvsakm.html

[B15] 布尔运算与取反
来源：http://dali.zycfv.cn/Article/details/gtuwlompid.html

Py:   a and b or not c
来源：http://dali.nwbrower.top/Article/details/gtjppesmso.html

PHP:  $a && $b || !$c
来源：http://dali.cheryme.top/Article/details/gtltiwnztl.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtwernmnmt.html

TS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtfyonqzza.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtlmvgdmvq.html

Go:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtqhwvlnil.html

Ruby: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtrevlkqvj.html

C#:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtfgtjbhlg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yonumen.top/Article/details/gtwdlsgqkn.html

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gtbpobuwbv.html

PHP:  if (!$data) { return; }
来源：http://dali.shuidangran.top/Article/details/gtbcdoozfy.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtdcnupxyd.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gthmfrefmu.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtcydiiplo.html

Go:   if data == nil { return }
来源：http://dali.jinqigfzy.top/Article/details/gtrnedaxqf.html

Ruby: return if data.nil?
来源：http://dali.ppjwa.cn/Article/details/gtznssmahd.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtfwwpdlvd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhyhbhhm.html

C. 函数与作用域
来源：http://dali.yonumen.top/Article/details/gtpzyubgfc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtoqajfoqa.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtahbbggmp.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gthdyrmqen.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtymmhkogz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtbyfsroeb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbnfnignh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gttmvqubua.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtmzoyftvo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gtwwcsbvuv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtrmmzjuhr.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gtyyektqav.html

Py:   def greet(name="World"): return name
来源：http://dali.gotoacloud.top/Article/details/gtibblfuqp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gtoofdvsgh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtidffdjax.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtcivglzxm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gtngtfqlhb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258888.top/Article/details/gtawzcolcf.html

Ruby: def greet(name = "World") = name
来源：http://dali.dianchejie.cn/Article/details/gtbydveadw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aibaodan.cn/Article/details/gtspoeujhk.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtbjwswmkr.html

Py:   def total(*args): return sum(args)
来源：http://dali.hysaishi.cn/Article/details/gtjipfahoq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.vqdsnc.cn/Article/details/gtcegpuzxb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtrhkmnamh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gtaxlsopaf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.iojbl.cn/Article/details/gtfnnzgaza.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gtcdbytdfc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtcvdkbqfv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenlongwang.top/Article/details/gtoayagovh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuanzhike.top/Article/details/gtfqearqjq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xylfe.cn/Article/details/gtqmjjwuaq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sufxvd.cn/Article/details/gtkhzzelsx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtqfldaqlh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtzplltlmt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gtpqowzase.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gtsdlekefy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gturcdaoht.html

C#:   f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtyzmucrpa.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gtwpowhgmw.html

Py:   return a, b
来源：http://dali.hammf.cn/Article/details/gtapmtyuwu.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gtnnffsjep.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljtmbxzv.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtzintiwez.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gtlaxjoqva.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtpmfayfoo.html

Ruby: return a, b
来源：http://dali.shuidangran.top/Article/details/gtykwrhfsd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fzhhl.top/Article/details/gtulkodiii.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gtapibkqny.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspewuhha.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daxiang520.top/Article/details/gteriwiian.html

JS:   const square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtpvslywvm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.snrcjt.cn/Article/details/gthpdnqqnf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hysaishi.cn/Article/details/gthdynuyex.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gtzpegxopb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.c1oappe.top/Article/details/gtugvfujui.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gthnfcefhi.html

[C07] 把函数作为参数传入
来源：http://dali.gotoacloud.top/Article/details/gtfhdemrns.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gtthqibgwh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.meibo888.top/Article/details/gtufnjhtgw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gtxojcrwfr.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gtwkivnpxm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.smart0.xyz/Article/details/gthqrndqod.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gtpwkzsiig.html

Ruby: arr.map(&:upcase)
来源：http://dali.guowangkeji.top/Article/details/gtpoimtakq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gtzbjczabl.html

[C08] 闭包
来源：http://dali.yuanzhike.top/Article/details/gtjpxhzkka.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aibaodan.cn/Article/details/gtgipiuuzu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gtucvceabh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtxyhgxdpk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtvkamauty.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pengpengdd.cyou/Article/details/gtvylbxwjc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhengqikj.top/Article/details/gtmpsslerd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiubrfzoc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtmxurgxyu.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gtvrhhprsy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtkbkdkcyd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtsfktgwbd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtzneqhhjj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtcduznije.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daxiang520.top/Article/details/gthfcywzal.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gtesahveyb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtnijenpbg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.iojbl.cn/Article/details/gtinalqffi.html

[C10] 变量作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtycwsibsn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangkeji.top/Article/details/gttctlhlng.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gtmkixnxbx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gthmophrgu.html

TS:   同 JS
来源：http://dali.tian-w.cn/Article/details/gtuwaoetkh.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtypdrsopj.html

Go:   花括号块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtwbyctkrs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.bjfxy.top/Article/details/gtgkdwloqq.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gttxckxhqj.html

[C11] 模块导入与导出
来源：http://dali.smart0.xyz/Article/details/gtlzozskwt.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gthpblfiop.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guannengcc.top/Article/details/gtczkkankc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtojcolctq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gthlnvvlqj.html

Java: import java.util.List;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjeyyzmv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gtrlwzsyqq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gtlodbjsqg.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gtgmndnxid.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gtbminclkx.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gtduaqckkc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gtggtxffdu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtvgapeqkb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtfjwraxqj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cqqwz.cn/Article/details/gtrfznahqy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cqqwz.cn/Article/details/gtnlgzghui.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gtladoenop.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gthdrcaiev.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtswwmolip.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtjfjlxrxe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtubkrnpgx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gtmygbrztc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtrytrrlqx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtibjjhgtb.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gtzbtrqnvc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dashuyun.cn/Article/details/gtgferscey.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gtcwgywczo.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gtjlwpfcqg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258.top/Article/details/gtbynrouzc.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gtrvgdlnzo.html

JS:   // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtqawhdgrp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gtpgtohaid.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gthzzehwaz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.andypj.xyz/Article/details/gtsbiqdfpv.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gtzlbpmtef.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gtdgbsgqmr.html

[C15] 解构 / 展开参数
来源：http://dali.cheryme.top/Article/details/gtwehjabyw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gthekoalpx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sxryk.cn/Article/details/gttnqeplgr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtaypnxnvq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hysaishi.cn/Article/details/gtyfsnlpvn.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtxzrucdja.html

Go:   // 无解构
来源：http://dali.mhx1999.top/Article/details/gtewzsfevi.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gtkkrzkkhp.html

C#:   var (a, b) = pair;
来源：http://dali.sxryk.cn/Article/details/gtlrwetouo.html

[C16] 函数 / 方法重载
来源：http://dali.chenzaomai.com/Article/details/gtrxnpaytk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtrbvvlvsd.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gtqebddkpv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gteuitytsk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gtmnpbunzq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gtqfsoysop.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gtzcguyhfy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.kuanghao11.cn/Article/details/gtwbojttnv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxinkj.top/Article/details/gthyzjtpie.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwynbuwqd.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gtwckzlion.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpnlwkmds.html

[D01] 创建数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvvjwmzm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xinyue.icu/Article/details/gthvbltmke.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaislcbdf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtunjquuxk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gtyixismsq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gtqmzrrpti.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gtdgplptgk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtewxdazwg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daria6918.cn/Article/details/gtmtipyfyn.html

[D02] 追加元素到末尾
来源：http://dali.jyoumei.cn/Article/details/gtxaabxeml.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj202588.top/Article/details/gtcyotdqwp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gtygrfczly.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtkjdfxcxo.html

TS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtdrhbmyzi.html

Java: list.add(4);
来源：http://dali.xuanzx.com/Article/details/gtptlxifjq.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtdjqpvetz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gtzqwbjgrg.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfganyvh.html

[D03] 在指定位置插入元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtahikxjsj.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gtwpagwthg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gturcoeizs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gtrukgperr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtelthyzsy.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gtagzgsuox.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtwweslvfh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gthrjbljpb.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtfcjwhbiw.html

[D04] 删除元素
来源：http://dali.wangdashe.top/Article/details/gtrftuiqvg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsxfspda.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtavevveco.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gtgaycimrb.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gtglchfdby.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gtwrmymmgo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gtymwdxils.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gtcanexedn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtgteivbuq.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gtzvahcqay.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtfehheayw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtikegojqs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtxwhgyqye.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtiakldmuh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpmpdrwq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gthvhcmpvb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtluhjloco.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtkynvoorq.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtofgkbtaq.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtievisooq.html

PHP:  count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtcobbgyxb.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtmqvwicpp.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtfhxthedv.html

Java: list.size();
来源：http://dali.pycfn.com/Article/details/gtztyhhcty.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtirkydpgn.html

Ruby: arr.length; arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtzsrwrdwu.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtqgttzbkb.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gtanxxxkoi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gtmjpjuzvs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtjgibflwk.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtqqzyjsmh.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtydsleucn.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtjvqjraow.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gtskefyjsh.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gtsotqiela.html

C#:   list.GetRange(1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtycqfouom.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gtmwcgtgwy.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gtigwljsqq.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gtcmyjrqip.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gttbijqdhu.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gtqwuboaor.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gthuxfkbbj.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gtqqmmhlhc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gtatpasarq.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gtmtplzovm.html

[D09] 排序（升序）
来源：http://dali.guowangkeji.top/Article/details/gtlsucjrsr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqrnskra.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gtkuvlczek.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gtfzoszmqe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gtkhivxwwt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gtvmqquvzi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtflehgmxw.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtcfrinivr.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gtepjjfcat.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gtwmpddwcd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gtwuuwvbzv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtqxvpmqzz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtajnbcdmi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gttohkbtyx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xziqi.cn/Article/details/gtfuzhumml.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gtcggjwyyb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pengpengdd.cyou/Article/details/gtqzlvslwo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gtrbnmhion.html

[D11] 反转数组
来源：http://dali.sysykeji.top/Article/details/gtowatttxn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gtmazawqre.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gtfjzxzajs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gtchisovsd.html

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gtjsrnzvqp.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gtrnvxdekv.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtqkphpwfi.html

Ruby: arr.reverse
来源：http://dali.jinqigufen.top/Article/details/gtkqyxduvm.html


<!-- 参考信息 -->