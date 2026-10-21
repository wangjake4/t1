代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgpecwdy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yangfankeji.com/Article/details/gtooazshns.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yongpay.top/Article/details/gteqdrrcpv.html

[B12] 跳出多层循环
来源：http://dali.tianlin.xyz/Article/details/gtdvtposxm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuetiantiany.cn/Article/details/gtvbngilhg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhixingplan.top/Article/details/gttkxnrjtf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gtrezmlysv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtmzqgujic.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtjbtethwy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigfzy.top/Article/details/gtsfxksjpp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nwbrower.top/Article/details/gtflrgigql.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.birdmap.top/Article/details/gtkxenwwmi.html

[B13] 判断是否为数字
来源：http://dali.pycfn.com/Article/details/gtkjvilyqx.html

Py:   isinstance(x, (int, float))
来源：http://dali.shzxlz.cn/Article/details/gtcbfkqygr.html

PHP:  is_numeric($x)
来源：http://dali.cqqwz.cn/Article/details/gtlazlwpmp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtkseapgae.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtntdnxubg.html

Java: x instanceof Number
来源：http://dali.nanxuanxn.top/Article/details/gtqwsruxdu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuanzx.com/Article/details/gtvzzqvxcv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gogol.net.cn/Article/details/gtyudpltbx.html

C#:   x is int or double or decimal
来源：http://dali.jinghuilouyu.cn/Article/details/gtakvvuguo.html

[B14] 判断值是否在集合内
来源：http://dali.zhengqikj.top/Article/details/gttwlxjekl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gtypudeibl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zycfv.cn/Article/details/gtfkvmorzm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xylfe.cn/Article/details/gtedpqadwl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtklzqonou.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoccjqzln.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnxiangtu.top/Article/details/gtetccqlrg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtvqfawmrd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtvfqvpinz.html

[B15] 布尔运算与取反
来源：http://dali.gogol.net.cn/Article/details/gtrysjndua.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gthtnbjoyl.html

PHP:  $a && $b || !$c
来源：http://dali.zhixingplan.top/Article/details/gtgxzbbrbb.html

JS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxwvgdsi.html

TS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtcrsjevto.html

Java: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtkpfrknyi.html

Go:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtppfgsvwt.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsctljpn.html

C#:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenaccawu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gotoacloud.top/Article/details/gtdfuagtka.html

Py:   if not data: return
来源：http://dali.gotoacloud.top/Article/details/gtpznrjgav.html

PHP:  if (!$data) { return; }
来源：http://dali.ehwqpu.com/Article/details/gtmtenvrmc.html

JS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtrzvafqbx.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtbkgrqqgs.html

Java: if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gtpqpwodrg.html

Go:   if data == nil { return }
来源：http://dali.birdmap.top/Article/details/gtsklggnal.html

Ruby: return if data.nil?
来源：http://dali.gotoacloud.top/Article/details/gthpnjojdy.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtyalcxxtf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtygrsydiq.html

C. 函数与作用域
来源：http://dali.shzxlz.cn/Article/details/gtpkfvjeyg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfaztitmz.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtqpqgqpcw.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gtamvqwihn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtkgigaogd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtcffwdupl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gthotvlkoq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtwmdocpox.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gtnvzzcmhp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gtlcjxxgta.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtoqjhvmrj.html

[C02] 默认参数
来源：http://dali.yuanzhike.top/Article/details/gtayzwmhbk.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gtpororxnj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gtepxgraoo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuilvtcc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtswmiirmp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gtkcfdpnla.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gtozfnsgjo.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gtcfddsbqt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gtbjugvppd.html

[C03] 可变参数
来源：http://dali.ehwqpu.com/Article/details/gtwrhyuchh.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhoulong.xyz/Article/details/gtslosmbfq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqubdiyu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxywbketp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gttuckhxaw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gtggkgxfeo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gtxkrjaonr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gtvdanasqf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gtymdyjrmr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.smart0.xyz/Article/details/gtgqebyfdz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xylfe.cn/Article/details/gtknvzyint.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gtuoxvmwsu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gthsamrphi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gtttzsycfm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuanzx.com/Article/details/gtbkcygxdt.html

Go:   // 无：用配置结构体参数
来源：http://dali.cucudq.cn/Article/details/gtkuveyytn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtzzmtpudu.html

C#:   f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtzkrgabdr.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gtizyfeznb.html

Py:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtcbxgkomo.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gtlkadjetf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gtnbxlgjek.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtxckkjjpr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gaohongyu789.top/Article/details/gtixwiikel.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtuuznxgrk.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gtcqyulkxx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jlsjyb.cn/Article/details/gtfngjojma.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gteswucney.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gtyzalgbhv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gtyuwbvqxn.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtpiqhaqrl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtgdnsjuny.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fzhhl.top/Article/details/gtcxhljjev.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gtjwnonmhv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenzaomai.com/Article/details/gtpmckwocc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhqmpsof.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gtbazeyinj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hammf.cn/Article/details/gtzgdudiyf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtzgfirsry.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gtkxnghvzj.html

TS:   arr.map(String)
来源：http://dali.yanxiufei.cn/Article/details/gtrfznbwou.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtzoacjehp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxinkj.top/Article/details/gtdnfhyjsc.html

Ruby: arr.map(&:upcase)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytuzvlsm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhengqikj.top/Article/details/gtrvfqvqpl.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gtbdsbvzsw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gtxtjnjfzb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gtuzqzhgcf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gttzgrowgz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtxztmyvkk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tanke756.top/Article/details/gtpfxfnort.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gthymaeyqi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtspfbdffx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtkltyzjtb.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gtfehweszd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gtpcgipdge.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtolwgfnsf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtdxttxzmd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gttniplgxu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqaqqwhxz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hysaishi.cn/Article/details/gtipxjyhen.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtjlsapkql.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtkymwdzxx.html

[C10] 变量作用域
来源：http://dali.cashguo.top/Article/details/gtjuogtuku.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdbbbxhp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cqqwz.cn/Article/details/gtdxtmritl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtizzkddkd.html

TS:   同 JS
来源：http://dali.meibo888.top/Article/details/gtwtdlwtdn.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gthlrwjlsk.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtxoqtbemo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxtjzzcz.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmkvkxdg.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gtayuszuuv.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gtuuewtiww.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gtaouphnvc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gtvvpsexhc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gtxtbwdsjc.html

Java: import java.util.List;
来源：http://dali.shangyingyoupin.top/Article/details/gtwceccwpd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtmosfparo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ybcxt.top/Article/details/gtuekzfnmo.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gtvujjikwt.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgufenzy.top/Article/details/gtnazkbhxo.html

Py:   (lambda: print("run"))()
来源：http://dali.yvedp.cn/Article/details/gtbomwlage.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gtkhdqgrvu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtvxyfxflu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtyhvhgdnx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuxming.cn/Article/details/gtdddyfdvf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtgfjdjwyo.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvzcagkk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gtrhxgbrdr.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gtreacawfl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gtinmosjfy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtrukfzmdo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hywenlv.cn/Article/details/gtfnpffckn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtqcsrdmin.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtximacnzw.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gtmhgpraoe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gtghwxsehy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gtmwqctbdk.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gtluqqaase.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrlcqgun.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtawhxfidy.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtewpktonx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gogol.net.cn/Article/details/gtfizubrli.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gtwzjrvxov.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gtnwpnxfwv.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gtulasvlye.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.havefunace.top/Article/details/gtabxmnamt.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gtjtjjpwrp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gtnblcpmmm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtrwrzdhrd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtoivpfbvy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtnaigiglc.html

Java: // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtbgokwimr.html

Go:   // 无解构
来源：http://dali.ybcxt.top/Article/details/gtavlqizsz.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gtbmjjejjw.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gtcbupcfov.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gtzuxzlmwi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtzcbsvhkb.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gtewtmsqqi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gtdmuebvzr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gtdyirfnqn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yongpay.top/Article/details/gtdrnnmhds.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtkphszoyo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtaiiloiur.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gtbmabsuau.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwjgfymmh.html

D. 数组 / 列表 / 集合
来源：http://dali.tianlin.xyz/Article/details/gtpxxgxozb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlmrdetwt.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtaupvnhse.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gtaveutrnd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guannengcc.top/Article/details/gtwziyhhfn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtcahbrgca.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gtwvluhbqm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gtdhjzijmc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gtfocpxfic.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtjjoalnas.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gtmgeegltg.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gticjkmstk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aizwys.cn/Article/details/gtegdkqbma.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guannengcc.top/Article/details/gtobqegsrr.html

JS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtgykthefz.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtzhclbjty.html

Java: list.add(4);
来源：http://dali.yj202588.top/Article/details/gturevedna.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gtdzkvcibx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jiagoushi.top/Article/details/gtgcmuftrq.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gtavrfljcd.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gthvbqnasm.html

Py:   arr.insert(0, 0)
来源：http://dali.tianlin.xyz/Article/details/gtoraxvoum.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gtbekjjapb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gttcqttsve.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtujrccrot.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtcpwivoxu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ppjwa.cn/Article/details/gtbdjdlomq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gtcxbpiwpa.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtqolthehw.html

[D04] 删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvieqnnem.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.c1oappe.top/Article/details/gticewcejl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gtiqnqeetz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gtwartldmx.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gtnupjdcmi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gttmnnwgsp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtbjezwgal.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gthkgnhsxo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj202588.top/Article/details/gtwnpxndql.html

[D05] 访问与修改元素
来源：http://dali.xuetiantiany.cn/Article/details/gtpuyyqorf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtwebbezoj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtfrhlwnft.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtcitdqqha.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ydzc1.top/Article/details/gtqapkihrt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gtoviuhpoo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtjtpxdbpy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtqgtzhewe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtfcjjvuvr.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtnuyuljev.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtiqhbinyr.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtwnqgqvam.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtokfjtfys.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefzsevug.html

Java: list.size();
来源：http://dali.nwbrower.top/Article/details/gtjjmezqaa.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtpfggurxd.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtduemckhc.html

C#:   list.Count;
来源：http://dali.yonumen.top/Article/details/gtleuvpwuw.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gtjzktiiai.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtroaoiipj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtctrreoqt.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtomevvwfi.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtvkmfwpox.html

Java: list.subList(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtnllairoh.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gtmttlznet.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gtuvahcmqk.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gtfdxctgkr.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gtscrnzzrb.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gtbcseoswg.html

PHP:  array_merge($a, $b);
来源：http://dali.wangshuangyany.cn/Article/details/gtcwigioad.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gtluugjtxw.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gtujlpxhmz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gtfthckbxd.html

Go:   append(a, b...)
来源：http://dali.yj20258888.top/Article/details/gtitudiauw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.andypj.xyz/Article/details/gtygtoacpn.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gtvrengwnk.html

[D09] 排序（升序）
来源：http://dali.meibo888.top/Article/details/gtyxrjdhav.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtheqmiwyp.html

PHP:  sort($arr);
来源：http://dali.svipenyu.cn/Article/details/gtjhbdjlgb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuxming.cn/Article/details/gtgsufjhlr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigufen.top/Article/details/gtdqojoull.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gtgrfzulpl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtpwsepfpt.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtaknmmihj.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gtzarwvovq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shangyingyoupin.top/Article/details/gtfcbnjtsq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gtrpyblfjn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtqjmlhyde.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhmwsiqz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtqjugoidb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hfpthk.cn/Article/details/gtvomebabu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gthxtcuwai.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtzutwbcwq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gtbbnhmfuf.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gthidfbglh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tian-w.cn/Article/details/gtsfonmsti.html

PHP:  array_reverse($arr);
来源：http://dali.daria6918.cn/Article/details/gtgszfixtm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gotoacloud.top/Article/details/gtimihmtmy.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gtuoozwhps.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gtxscxwvzj.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtckslyjsz.html

Ruby: arr.reverse
来源：http://dali.redwolf501.top/Article/details/gtctqpnmmo.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gtcnzlotiq.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gtktyogxqy.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gtfciawtet.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gtqahtehbx.html


<!-- 参考信息 -->