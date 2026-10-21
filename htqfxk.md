代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.hfpthk.cn/Article/details/gtaitqnpll.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gtdlpakbrf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gtjzvwcqsv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.guannengcc.top/Article/details/gtsyfsglga.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuetiantiany.cn/Article/details/gtgthtitzj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.redwolf501.top/Article/details/gtgmpwvofb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ydzc1.top/Article/details/gtsqhkieoo.html

[B12] 跳出多层循环
来源：http://dali.sysykeji.top/Article/details/gtmawjompu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangshuangyany.cn/Article/details/gteenktxlq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258888.top/Article/details/gtyeaavasv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtmworrcbq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtmzcomrqk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtrceucldl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hywenlv.cn/Article/details/gtequqimad.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxuanxn.top/Article/details/gtydhwrpqk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.quarkkingdee.top/Article/details/gtwfyxickr.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gtyvialsbo.html

Py:   isinstance(x, (int, float))
来源：http://dali.shangyingyoupin.top/Article/details/gtmpistpww.html

PHP:  is_numeric($x)
来源：http://dali.sysykeji.top/Article/details/gtocxgxkhh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtopwrvkjc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtijxqjbyk.html

Java: x instanceof Number
来源：http://dali.pengpengdd.cyou/Article/details/gtqpfdmpwt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxueweutf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cdnleiting.top/Article/details/gtgfapvrrp.html

C#:   x is int or double or decimal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzplfitjj.html

[B14] 判断值是否在集合内
来源：http://dali.hammf.cn/Article/details/gtfbnyvpkr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtjginnbox.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.vqdsnc.cn/Article/details/gtgwnzlnty.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtyqkrtwmw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbufapgwq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guannengcc.top/Article/details/gtuteqdzsg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jianghu66.top/Article/details/gtqpuqvmfg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258.top/Article/details/gtxdmfzshy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gtgsuvuove.html

[B15] 布尔运算与取反
来源：http://dali.hysaishi.cn/Article/details/gtxgjxgfbh.html

Py:   a and b or not c
来源：http://dali.yonumen.top/Article/details/gtgmeeadag.html

PHP:  $a && $b || !$c
来源：http://dali.fzhhl.top/Article/details/gtibknzzgs.html

JS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtklesdwga.html

TS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtobjlxxfc.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtnqfdfpwc.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtpxgxczji.html

Ruby: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtmvbzwkfz.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtktmiksvz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.haohaochexian.top/Article/details/gtbnzspood.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtllwyzkik.html

PHP:  if (!$data) { return; }
来源：http://dali.sufxvd.cn/Article/details/gtkrualnrj.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoecblijs.html

TS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtllseeiem.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gttlyssiuv.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gtcwlguunx.html

Ruby: return if data.nil?
来源：http://dali.jianghu66.top/Article/details/gtplpiiotx.html

C#:   if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gtsqwavsfk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttkscyksx.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gtgzwcqiuh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtlptipzzc.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtodqtashr.html

Py:   def add(a, b): return a + b
来源：http://dali.daria6918.cn/Article/details/gtkcwgppxa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtvhziunea.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtirpjfcgx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtjkdoxzpf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gthuoimlgc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sweek.top/Article/details/gttquvhtbb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gtwuxxgoku.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtovnejhhg.html

[C02] 默认参数
来源：http://dali.dianchejie.cn/Article/details/gtzteuhozy.html

Py:   def greet(name="World"): return name
来源：http://dali.svipenyu.cn/Article/details/gthzvdltrc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gtakpaghaq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtrdaskfqx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtulnjypuu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cucudq.cn/Article/details/gtjvxxndcm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkusavwei.html

Ruby: def greet(name = "World") = name
来源：http://dali.hywenlv.cn/Article/details/gtviueeqdy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gtomjoufwq.html

[C03] 可变参数
来源：http://dali.yvedp.cn/Article/details/gtrvzyzift.html

Py:   def total(*args): return sum(args)
来源：http://dali.jiagoushi.top/Article/details/gttfhinjlf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jlsjyb.cn/Article/details/gtodhgkska.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtyjzgvazy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtcjqpedgs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwgqhjbx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tianlin.xyz/Article/details/gtzawudzag.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtebqsshhz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sweek.top/Article/details/gtxkurqxlq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuetiantiany.cn/Article/details/gthvyndsee.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tianlin.xyz/Article/details/gtpesjdydu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbgqznjw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtumcfeiis.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtlutqlqmo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gtlakuvhrx.html

Go:   // 无：用配置结构体参数
来源：http://dali.xylfe.cn/Article/details/gtjcaytbfw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtukupleny.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtsczlrnjx.html

[C05] 返回多个值
来源：http://dali.yj20258888.top/Article/details/gthyzcmpnf.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtiwjmpoku.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtgnbzlrpr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtchyqiagl.html

TS:   return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gtewczxjks.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gtsawxzjpc.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtxdjdzlms.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gtwnktptiy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnqzz.top/Article/details/gtdyleqgnx.html

[C06] 匿名函数 / lambda
来源：http://dali.daria6918.cn/Article/details/gtqkjfisqp.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gtvysiuxwx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ehwqpu.com/Article/details/gteefowink.html

JS:   const square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtwwmeebaq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtwbmdmvks.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gtiettqbbz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yongpay.top/Article/details/gtvvhcszvz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuanzx.com/Article/details/gtdkbqfryl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtwqpxhlwl.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gtivjksdxy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxinkj.top/Article/details/gtybjgmbbg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtefepdiqy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gtfjdmzjxf.html

TS:   arr.map(String)
来源：http://dali.yj20258888.top/Article/details/gtvweybjky.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gtetvupiwe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tianlin.xyz/Article/details/gtpinmmaui.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gtfvqbltat.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ybcxt.top/Article/details/gtjaiuywaz.html

[C08] 闭包
来源：http://dali.yuanzhike.top/Article/details/gtylmorzav.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gtwvoidxuv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gtfqjxsbml.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanqjeedt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtjrytzgrs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxcmwlkp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuetiantiany.cn/Article/details/gtcrvxrhwc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gtyvjpqikw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtovggyxut.html

[C09] 递归
来源：http://dali.tianlin.xyz/Article/details/gtiecfjfve.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtbbwcdgvk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pycfn.com/Article/details/gtfsyxmrri.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgzlhecv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtfufnwmns.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtnfgemssd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gtpodglaja.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtarlhmpjx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhixingplan.top/Article/details/gtykfxmmwr.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gtujzdkpdi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gteebracpf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhoulong.xyz/Article/details/gtmlgqicto.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shzxlz.cn/Article/details/gtomihgjvs.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gttlhlhzbv.html

Java: 方法内为块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtjpmsccdi.html

Go:   花括号块级作用域
来源：http://dali.havefunace.top/Article/details/gtjyvtseek.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenjidiqi.icu/Article/details/gtmbeczgta.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtouifhxzw.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gteisizcix.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gtpgyddzsw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrrdhlcm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtvoosadcy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gtjjlkzorj.html

Java: import java.util.List;
来源：http://dali.havefunace.top/Article/details/gtbjoaswqu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangdashe.top/Article/details/gtxwpruuev.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daxiang520.top/Article/details/gtvfwrrutn.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gtbsrmnszy.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gtcakimzwv.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gtqwnxcxdp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jyoumei.cn/Article/details/gtkobkfoie.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gttimqzzsl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtxmzztwje.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gtquphxjun.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gtxowrkjri.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gtuduapmbu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.smart0.xyz/Article/details/gtpliysrha.html

[C13] 类型声明 / 类型注解
来源：http://dali.xinyue.icu/Article/details/gtansdzoon.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtlcrsuzlq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtljyapvhz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cqqwz.cn/Article/details/gtivfefvwp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteohceasa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gthvlvuntj.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gtrcoyfibq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gthbtbrkwq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aizwys.cn/Article/details/gtkuxzksko.html

[C14] 泛型函数
来源：http://dali.fengsongda.top/Article/details/gtmpvbzgcu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigufen.top/Article/details/gtkpdpwjxn.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gteevffimr.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtdckhgxon.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgufenzy.top/Article/details/gtgjwcciwb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.vqdsnc.cn/Article/details/gtmcrwryvd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gtbbfyidlb.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gtcsqsspfe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gtayzseezk.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gtazakcslc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gtzprmraud.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gttyxgcnqm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtnqyymzko.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gtjxosxjdz.html

Java: // 无解构
来源：http://dali.yueranfly.top/Article/details/gtzsszpgry.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gtaukflexe.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gtwdtobjhs.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtryagvfuh.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gtvaypscfa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gtuopkushk.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gthsuqgzfz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gtgxfuhcop.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fzhhl.top/Article/details/gtacefitiv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gtfsgyvbdn.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gtefkxjoep.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gtvjvfkaxr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gtitrvszcc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrsffrdkx.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtxgcwxffu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtowxcjiex.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtcdwlyvbz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gtviqsdwec.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqkrqkdi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtafggjovt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofwzmvrz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gttihidtuj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gtoryyucms.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gtsfydctct.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ivvv.top/Article/details/gtidoohxgn.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gttbkrfhgo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.smart0.xyz/Article/details/gtwudntowl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gtkncfcmsj.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtlixnebzk.html

TS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gtpstczpvw.html

Java: list.add(4);
来源：http://dali.yj202588.top/Article/details/gttyjubzer.html

Go:   arr = append(arr, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtlpzbdmrw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gtueabhbab.html

C#:   list.Add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtjpeohhpx.html

[D03] 在指定位置插入元素
来源：http://dali.cucudq.cn/Article/details/gtvlykgdfm.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtylasrtuq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hywenlv.cn/Article/details/gtzusfcszy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gtvabokhye.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gtknmsmqzu.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtqgnokmhn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtcqwpaqpy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aibaodan.cn/Article/details/gtrvfotvpl.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gtxjgjlsum.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtaokylumg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gtfnghgsfs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtinfuxoka.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangdashe.top/Article/details/gtcgyymmfa.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gtvvqnvtmj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtbadeufze.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtyaitbrzk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nwbrower.top/Article/details/gtndertarj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hysaishi.cn/Article/details/gthrjtscsp.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtgsvwnkmn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtulrmoano.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtkfpcszxv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtadgwxilk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtkkmxtjle.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gtnqewxfcp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtbfolslyv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtfhrdhmwo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtaahcdlfd.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkemexux.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtuihjcjbv.html

PHP:  count($arr);
来源：http://dali.ydzc1.top/Article/details/gtauzaysps.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtqyvhanzd.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtixzfbpdt.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gtnyvacsnu.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtyvoljjki.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gtcqqznstf.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gtiuxinmju.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gtqidwuutk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gtsuhzjjnt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtfagdnxub.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtuhigsigl.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gteijsmamd.html

Java: list.subList(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtigfdvfbe.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gtkvlzpcpe.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gtrfhmgswc.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gtyrfybief.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gthdwgjctk.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gtdpfjmbtk.html

PHP:  array_merge($a, $b);
来源：http://dali.kuanghao11.cn/Article/details/gtslrtillj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gtgpozgbkn.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gtwxhovkbs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.smart0.xyz/Article/details/gtjiltxmfu.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gtyahvtsdt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gtyuhtamyf.html

C#:   a.Concat(b).ToList()
来源：http://dali.shuidangran.top/Article/details/gtdvkirsmg.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gtznogjdym.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtmpnvqomb.html

PHP:  sort($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtuolmrlvd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtryemhgbb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangtech.top/Article/details/gtymydurzt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gtsqqaocla.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtoeuqqilj.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtrswasghh.html

C#:   list.Sort();
来源：http://dali.andypj.xyz/Article/details/gtegqknauy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gtmkffrujj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gtuhlnzhty.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtukjnkxhp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuiscukek.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gterfyegrt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gteswfzqzn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yvedp.cn/Article/details/gtzfumicey.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ivvv.top/Article/details/gtnvdgwpjc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gtciwqzntq.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtsohwilzo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xziqi.cn/Article/details/gtnmxhgamn.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtcsiwanok.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gtkxwahqkj.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtuguykegy.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gtgbbaebzt.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtyvuoihaf.html

Ruby: arr.reverse
来源：http://dali.pycfn.com/Article/details/gtkknbtkxa.html


<!-- 参考信息 -->