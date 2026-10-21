代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtrekxpzce.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqsycwez.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gtgdrwauud.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.0kj1m.cn/Article/details/gtsokvordk.html

[B13] 判断是否为数字
来源：http://dali.hnqzz.top/Article/details/gttpdbzxrz.html

Py:   isinstance(x, (int, float))
来源：http://dali.0kj1m.cn/Article/details/gtwicwwnpb.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gtyjskkria.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gthbvhtvue.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtwhooohif.html

Java: x instanceof Number
来源：http://dali.zhongyouzk.top/Article/details/gtbywenpos.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwhjjzjz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gaohongyu789.top/Article/details/gtrmkarrkg.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gttyhzuhhs.html

[B14] 判断值是否在集合内
来源：http://dali.daria6918.cn/Article/details/gtyypvbsll.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guowangkeji.top/Article/details/gtxujxidpy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xinyue.icu/Article/details/gtmfttmaow.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gtjrdwoxyb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtikpakgni.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtyjtydnyx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ehwqpu.com/Article/details/gtjecklydn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ivvv.top/Article/details/gtvzlchkqd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtwzdkkkjd.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjpvufuy.html

Py:   a and b or not c
来源：http://dali.xziqi.cn/Article/details/gtlfxyhxym.html

PHP:  $a && $b || !$c
来源：http://dali.zhixingplan.top/Article/details/gtikxnpjvr.html

JS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtehshospe.html

TS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtvfievbeh.html

Java: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtnotfwzhk.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtjupryrmm.html

Ruby: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtxsoprkgr.html

C#:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtfnqajqob.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daria6918.cn/Article/details/gtsbsofqlt.html

Py:   if not data: return
来源：http://dali.xuanzx.com/Article/details/gtvkgoagqq.html

PHP:  if (!$data) { return; }
来源：http://dali.hnxiangtu.top/Article/details/gtjvjfeunw.html

JS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtqtlysepd.html

TS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtxqjhdzpm.html

Java: if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtcsqgnfbr.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gtxzcpficf.html

Ruby: return if data.nil?
来源：http://dali.316326.xyz/Article/details/gtqyjzshvu.html

C#:   if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtpsnyydoj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthkvzxhxm.html

C. 函数与作用域
来源：http://dali.cqqwz.cn/Article/details/gtolkhhqco.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtnxojeder.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtzcnbzmcd.html

Py:   def add(a, b): return a + b
来源：http://dali.yuxming.cn/Article/details/gtzdbmbmel.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtgckvbmno.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtwewufvvd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtpgwcwtui.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtfaeogdsh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gtwgyanqiw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuanzx.com/Article/details/gtnslydqvv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtxpymrsyv.html

[C02] 默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtxdapfgyd.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gtcjzcpwvm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gtrrqekhrd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtnywelltk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtlfsjjwvs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.vqdsnc.cn/Article/details/gtveyjcwec.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yongpay.top/Article/details/gtqvvupdas.html

Ruby: def greet(name = "World") = name
来源：http://dali.zdqjudy.top/Article/details/gtvjyhpbow.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gtjgsuroms.html

[C03] 可变参数
来源：http://dali.yangfankeji.com/Article/details/gtwimtbhcu.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gtoblgblqg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtemntgdyo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtcnxxduqd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gtzkclygay.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gtorxngxce.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yonumen.top/Article/details/gtfzwsawws.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gtixszloej.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtxlxqtohs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gtoapgjpin.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gtkjfwklae.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tianlin.xyz/Article/details/gthgohwfsh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtdsgntkdw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gtlzteewrb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhoulong.xyz/Article/details/gtckmqxonl.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gteguizoms.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtnzmhfxrg.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtpzhnople.html

[C05] 返回多个值
来源：http://dali.kuanghao11.cn/Article/details/gtyrlsyimi.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtwmufqtis.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtvkvhwcdh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtuvzqjnhz.html

TS:   return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gtxzpnpfqd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gtylpxrgzw.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtkyrqsgcm.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gtrxjmpmfw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gtrxusqcbf.html

[C06] 匿名函数 / lambda
来源：http://dali.daria6918.cn/Article/details/gtmlujyhge.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gtaxjgoech.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangtech.top/Article/details/gttqqbddks.html

JS:   const square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gteniiatvm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hysaishi.cn/Article/details/gthubygtjc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gtonwkdjzg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guowangkeji.top/Article/details/gtnxnlkkmv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gtcjufmhug.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtvlzeeztp.html

[C07] 把函数作为参数传入
来源：http://dali.yueranfly.top/Article/details/gtoqhornop.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fzhhl.top/Article/details/gthasfvkdz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtnicedyez.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gtrqaktqhc.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gtngjuijih.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtawunoqao.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhoulong.xyz/Article/details/gtuiljvgiz.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gtuhdxuruh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtnjlqpgwa.html

[C08] 闭包
来源：http://dali.tanke756.top/Article/details/gtdlgwkonl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtcvbjbpsj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dianchejie.cn/Article/details/gtbmfpayjm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtyaaxdwuy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqocejge.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gtnyywqxfd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hysaishi.cn/Article/details/gtmidhbqrg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fengsongda.top/Article/details/gtlrqmyavt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtriagfyrw.html

[C09] 递归
来源：http://dali.sysykeji.top/Article/details/gtmdliurgn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtosfstpag.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrloxnyyq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gtpgjqthel.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtjqrzbubq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.316326.xyz/Article/details/gtraceiwug.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gaohongyu789.top/Article/details/gtwezzzctc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtjumnpysp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedoxdrmt.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gtalbcyfws.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtkhrpjceu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tianlin.xyz/Article/details/gtaqrbzazm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtqxxfdrfd.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchveafkp.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtbophbvgy.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gtxrgcfvdk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daxiang520.top/Article/details/gtkbgiljod.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gtomlddhap.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gtyvmupkxl.html

Py:   from module import func
来源：http://dali.haohaochexian.top/Article/details/gtlajgxpkg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyieldfs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gtvptephll.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.kuanghao11.cn/Article/details/gtgxmgpxkv.html

Java: import java.util.List;
来源：http://dali.sysykeji.top/Article/details/gtpifockkr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gtyrkhracs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gtqtvjgtvu.html

C#:   using System.Text;
来源：http://dali.chenzaomai.com/Article/details/gtgjkylwko.html

[C12] 立即执行函数 IIFE
来源：http://dali.ppjwa.cn/Article/details/gtlywwseez.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gtjpxhtpez.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gtspyhsbet.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtcgrcgapx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gtyskbcoai.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gtnzygxtjf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xziqi.cn/Article/details/gtivcjmsul.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtpvtjamqd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gtchldffpm.html

[C13] 类型声明 / 类型注解
来源：http://dali.jyoumei.cn/Article/details/gtdxxlofzy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gtbelesvif.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtpomarnoa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnxiangtu.top/Article/details/gtfthwzhcw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtqwwivpot.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtjyobydlb.html

Go:   func add(a, b int) int
来源：http://dali.zhiwuduotai.top/Article/details/gtfcicijpp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gticpdofds.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ydzc1.top/Article/details/gtlkzwxvnr.html

[C14] 泛型函数
来源：http://dali.pengpengdd.cyou/Article/details/gtzgblnnrc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gtlpjpfuhk.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtdcvhmtce.html

JS:   // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtdtfssrhr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gtyzrzpapm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqkwaregj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gogol.net.cn/Article/details/gthycmhune.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtxrtwyaqs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gttuxdkxdr.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtnbjdhbdg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gtqearsouo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gtwfaftaxk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkdtupiy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gtnyfrttqn.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtxqfggzvo.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtzfmhvqlx.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtopomwikk.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtpgkzeoeh.html

[C16] 函数 / 方法重载
来源：http://dali.xinyue.icu/Article/details/gtykepnjpw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gtfyjrluua.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gttipxwzqq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gtlgpzbmvz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.snrcjt.cn/Article/details/gtgogmyeao.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gtikenpkij.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gtmoluazpr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtnecrwueg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtnfutigfz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtseftsxam.html

D. 数组 / 列表 / 集合
来源：http://dali.pycfn.com/Article/details/gttijkjldp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtaivjxslx.html

[D01] 创建数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gtjvucylfd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gtoidbxndu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.c1oappe.top/Article/details/gtolxiydft.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gtxvrzwgww.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gtgxgymhks.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gtygfafvcq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gtlmptfoxi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gthfgihomw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gotoacloud.top/Article/details/gtjvhxwsnb.html

[D02] 追加元素到末尾
来源：http://dali.shangyingyoupin.top/Article/details/gtgsxaxlir.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gtpojijgmy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtqbicvboz.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtbfspotym.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtdmcwdxuc.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gtyghjbghn.html

Go:   arr = append(arr, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtrafphdds.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gttjwxkefx.html

C#:   list.Add(4);
来源：http://dali.shuidangran.top/Article/details/gtaofhxeul.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gtctsrrozr.html

Py:   arr.insert(0, 0)
来源：http://dali.fengsongda.top/Article/details/gtnjdcsrkp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gtrtwazvus.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtbslqvhkm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtiqqntayg.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtwpkgsiff.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtfcokumwg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gtvcghsksz.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtrusbgnfv.html

[D04] 删除元素
来源：http://dali.c1oappe.top/Article/details/gtzfgwysic.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gtedevbrup.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258888.top/Article/details/gtqectxrpz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gtlulqpwwq.html

TS:   arr.splice(0, 1);
来源：http://dali.iojbl.cn/Article/details/gtazegclrv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gtlevfeqsq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadaahbln.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yanxiufei.cn/Article/details/gtooioqlby.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gthjvwrnsk.html

[D05] 访问与修改元素
来源：http://dali.meibo888.top/Article/details/gtmvsgxgjm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtalubxhsr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtqizgfdar.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtubqwpswe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shuidangran.top/Article/details/gtkvgknonz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gtnplvyfev.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtuiozfnak.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtahcscnqt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcabhpxxt.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gtddfbtdgc.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtaanzyzit.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtarjanwbz.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtixuemzgp.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gthrszoaes.html

Java: list.size();
来源：http://dali.ybcxt.top/Article/details/gtriwbehlf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtwiehmems.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gtiknctrap.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gtqcmqwoof.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gtrierubot.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gtracadefb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gtmldawshq.html

JS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtnbbaajui.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtdtaruvmf.html

Java: list.subList(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtjrwzoobn.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gtbehmvjdv.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gtucnozius.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuanzx.com/Article/details/gtwabwlfgj.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtbcqvkahn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gtqhjkpars.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gtlhxzlwik.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gthmaeopdj.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gtqxdagzrr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gtfnxjjzda.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gtupthafyu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gtywqrjsik.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtlnbjqkos.html

[D09] 排序（升序）
来源：http://dali.dashuyun.cn/Article/details/gtwxcncfcx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtkuehjjgi.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gtsvnupdjo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gtlduxirwt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gthwhklnnj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gtbkgufaey.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtdupruixi.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gthhiltlke.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gttivgooog.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtnsnqgkaz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.iojbl.cn/Article/details/gtdtltyuyg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtvxtsubrq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtxywndvdn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtzedlqati.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gtpqamutzl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gtrxfzksna.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtziejpyfj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gtkedvaqnj.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gtkiyhlddb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gtgexqgmqa.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigufen.top/Article/details/gtiraapwsk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gtqcinatts.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gtjbkryvcv.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gthogjozrd.html

Go:   slices.Reverse(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtgqljujwi.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtxntgoeds.html

C#:   list.Reverse();
来源：http://dali.9152youxi.cn/Article/details/gtvcbyvuzz.html

[D12] 查找元素下标
来源：http://dali.snrcjt.cn/Article/details/gtlpunzmqo.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gtpkfyzdhd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtbgyjvczo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtbebzilbm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtnesaahqt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gtnsiwjupm.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtizzajkdf.html

Ruby: arr.index(x)
来源：http://dali.dianchejie.cn/Article/details/gtguuyvgwy.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gtawbdxxwk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gtmfueusuv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gtmtlbcrqt.html


<!-- 参考信息 -->