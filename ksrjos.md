代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.hammf.cn/Article/details/gthnaegibc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gtszbhrqja.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtgvmljmkm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj202588.top/Article/details/gtmhlziqjm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuxming.cn/Article/details/gtmyluuwgu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xziqi.cn/Article/details/gtsgfjuigj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pycfn.com/Article/details/gtpgbssoes.html

[B12] 跳出多层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtrkzonmhy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.snrcjt.cn/Article/details/gtivrspuah.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jiagoushi.top/Article/details/gtwnjzwphe.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtkxgpxdit.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtldqvhtoh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtwqqbgjhj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxuanxn.top/Article/details/gtgwjjgynm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.haohaochexian.top/Article/details/gtctbvqtna.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gtifezwyqi.html

[B13] 判断是否为数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxdykwah.html

Py:   isinstance(x, (int, float))
来源：http://dali.svipenyu.cn/Article/details/gtiddhimfj.html

PHP:  is_numeric($x)
来源：http://dali.pycfn.com/Article/details/gtjldehsvo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtueitkhtu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtpruqesjx.html

Java: x instanceof Number
来源：http://dali.sweek.top/Article/details/gtvlfvouhs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yangfankeji.com/Article/details/gteiwcholb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigfzy.top/Article/details/gtdjrruuch.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gtcuiagucy.html

[B14] 判断值是否在集合内
来源：http://dali.andypj.xyz/Article/details/gtsxozweiy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gttqkgqjnx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gtukaymmgv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gtlzefpqft.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtrlzrnqyp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtnflhcpgr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhengqikj.top/Article/details/gtrbbmgvqr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtsuefptgm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtgevtmrfd.html

[B15] 布尔运算与取反
来源：http://dali.zycfv.cn/Article/details/gtvttnonhp.html

Py:   a and b or not c
来源：http://dali.tianlin.xyz/Article/details/gthezlwngt.html

PHP:  $a && $b || !$c
来源：http://dali.yueranfly.top/Article/details/gtswycyfvo.html

JS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtlhtsqlrk.html

TS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtrfwgnhvr.html

Java: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtmadppftw.html

Go:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtvyjodsre.html

Ruby: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtcqqukptb.html

C#:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtuyylzkcg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gtycbmzhcr.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gtxsafbcgw.html

PHP:  if (!$data) { return; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteomntbss.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtqzdiubrn.html

TS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtifsegefu.html

Java: if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtyrmtjmui.html

Go:   if data == nil { return }
来源：http://dali.hammf.cn/Article/details/gtadmyuexr.html

Ruby: return if data.nil?
来源：http://dali.xinyue.icu/Article/details/gtzpkhddgq.html

C#:   if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtbtmlmutv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtrpnqio.html

C. 函数与作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtlbisncjq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlvwuuhcg.html

[C01] 定义函数
来源：http://dali.pycfn.com/Article/details/gtdvwkxcjz.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gtuukzjoua.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtgtsqnqtn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtknenuopi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtybqroqlt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gttwlchodi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtdnkuzefb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.smart0.xyz/Article/details/gtezyntivj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtjcgqtwia.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtjsjlujfj.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtztgvmjxm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.redwolf501.top/Article/details/gtzaumvwln.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtggbayrge.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtsblcrgzi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aizwys.cn/Article/details/gtrfonstyd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tanke756.top/Article/details/gtzphokrqo.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gtufxkohyz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ppjwa.cn/Article/details/gtkildfagr.html

[C03] 可变参数
来源：http://dali.sxryk.cn/Article/details/gtmupcppdl.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtfonmkhcn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jyoumei.cn/Article/details/gtawljxjfm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gtzxoyopnm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gttkeatakx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibasouqe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gtsmealayj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gtvlobzsak.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gtkupwxvvz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gthwsfpefv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gtkovgwgqx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikwwwmvu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtjouivfug.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtlhuhycxb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gtiasmldst.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxinkj.top/Article/details/gtszelxfwk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtqxudkvvt.html

C#:   f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtdsrofpsq.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gtxsgdbqqn.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarcebtag.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gthufjsmka.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gtgpybxgnw.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtprcvobba.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gtgntbbuin.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtkxapjids.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtiybarrbk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gtjdfkbvkn.html

[C06] 匿名函数 / lambda
来源：http://dali.snrcjt.cn/Article/details/gtgqivuysb.html

Py:   square = lambda x: x * x
来源：http://dali.yanxiufei.cn/Article/details/gtieywrgjk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daria6918.cn/Article/details/gtdclbmryb.html

JS:   const square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivbzchvi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtvyheerwh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxujjjfg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.smart0.xyz/Article/details/gtqsvzjmrc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gttlpsttyj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtjfajyqsb.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtlxwknahy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nwbrower.top/Article/details/gtirenunmn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gtojxreaog.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmnypaxb.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gtkvlktniy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gtmmvajgjf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cdnleiting.top/Article/details/gtkktedwni.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gthylfemcm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gtassttxqi.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gtuyvdlwzv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gtnekdymia.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhiwuduotai.top/Article/details/gttrczwypr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtelidatef.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtctmpcbpf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gtdjasqakj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ydzc1.top/Article/details/gtjxmedlrn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gttiufxzba.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhlwnwca.html

[C09] 递归
来源：http://dali.wangdashe.top/Article/details/gtpparazfw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gttzkzlpzh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gtiiatsirz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtwkldmseg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtfsxpilpq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtlvcwwmck.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gtnlgzfyux.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gthakngbbe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gtmdxgxifb.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gtrgsjcsar.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gteykbfyba.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtxcvmdcys.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cheryme.top/Article/details/gtazbpeeid.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gtopthyffk.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtlxkssjcy.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtgfgctgjp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gtkofdfehb.html

C#:   块级作用域
来源：http://dali.meibo888.top/Article/details/gthklyqdcu.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gtuxebblvb.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gtoamvemcr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gtjpmhahyh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gttlopgaqt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gtxmqhwnsl.html

Java: import java.util.List;
来源：http://dali.pycfn.com/Article/details/gtpgvvwexp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gttwygtqso.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuanzhike.top/Article/details/gtenhhgyzg.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gtuuyhoawq.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gtemtwisra.html

Py:   (lambda: print("run"))()
来源：http://dali.yonumen.top/Article/details/gtjjlklbvk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.quarkkingdee.top/Article/details/gtepxwxmxq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtbbfaoetr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtudfaiaiv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gtmirjsaio.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.316326.xyz/Article/details/gtkyrgcghw.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrdllxec.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shzxlz.cn/Article/details/gtrmtfllkx.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gteozhgldd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gtahvdpyvm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtyleniltt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gtybqddchz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtxejgfiqj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvgynuwqr.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gtzglkbzzv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gthzxoomvk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtxloocwal.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gtpdrnmbbb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gtjjhqmerj.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtfccszxhm.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtoukkrbno.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ppjwa.cn/Article/details/gtpubkkqmf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daxiang520.top/Article/details/gtzghtnwzc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ehwqpu.com/Article/details/gtcbbpcpcy.html

Ruby: # 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtevujcike.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jiagoushi.top/Article/details/gtpuguohrs.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gtoqwfljah.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daxiang520.top/Article/details/gtknlovkkn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gtekykyzue.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtqjhjtdta.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gtfhiovfct.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtrssjrmfx.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gtnqfywxwi.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gtigcjknlg.html

C#:   var (a, b) = pair;
来源：http://dali.yanxiufei.cn/Article/details/gtueihvhza.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gtauielaol.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.vqdsnc.cn/Article/details/gtaaudxpjz.html

PHP:  // 无重载
来源：http://dali.guannengcc.top/Article/details/gtleslewws.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hysaishi.cn/Article/details/gtkbdsriza.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gtcbmrqqdl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ehwqpu.com/Article/details/gteobsykbh.html

Go:   // 无重载：用不同函数名
来源：http://dali.gaohongyu789.top/Article/details/gtphhbfchw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gttblywjpx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtpejctuah.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdjksfvta.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigfzy.top/Article/details/gtzleepqkf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtssxbckcq.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtlfpyuieh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gtefrtfvbv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtbtwprzcn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gtcgereisa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gtzeovtjkp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxuanxn.top/Article/details/gtxeixvvrp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhoulong.xyz/Article/details/gtvdehxeez.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gtylkdhfmr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangshuangyany.cn/Article/details/gtluveumdy.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gtesjqgpnb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jyoumei.cn/Article/details/gtiyslxizy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gtzvfeozql.html

JS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtvjbqohtv.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtezwmopbw.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtkchwioxr.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gttbprzjcf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gtgdwlsqhg.html

C#:   list.Add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuttttwo.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtomvkheoi.html

Py:   arr.insert(0, 0)
来源：http://dali.xziqi.cn/Article/details/gtefsxycxd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shuidangran.top/Article/details/gtwnxnyjhu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gtqzrxtsie.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangdashe.top/Article/details/gtrthscfsg.html

Java: list.add(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtxlumlwon.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtrdjhoyoc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gtrumqyjwg.html

C#:   list.Insert(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtqeudriiq.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtsrktxeuq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gtfplonndq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtauwzynkd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gttdejfyla.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtbqcilpic.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gtxnkythfm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gttylqjeof.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gtxarryiow.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gtavediobf.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gtmklfoxuz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtahjhyqmi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtqierqqvc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcudqlxt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqnlkzll.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gtkihivamg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtyrcjiglw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtvwbwemtf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtmnyiynpn.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtgxbfcnxs.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gthinqqdmw.html

PHP:  count($arr);
来源：http://dali.yj202588.top/Article/details/gtzpkwkstt.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtliebekyp.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtmzlwmorv.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gthelinvlq.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtuydelkul.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gtqzwldzqz.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtjxynbfwx.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gtmoggafte.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.meibo888.top/Article/details/gtiwfmveen.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtegckxtai.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gthkbgfsvb.html

TS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtuvtjxkvh.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtdoxzifrx.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gtyklvtssu.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gttzgjanul.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtwnlccpvb.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gtleuhzlan.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gtumktanqd.html

PHP:  array_merge($a, $b);
来源：http://dali.shangyingyoupin.top/Article/details/gtrrpvtxvp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gtpstissoy.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gtvnnxwgwh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtceddklrx.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gthhmvecgm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gtcnssblkx.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gtbqjjraxi.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gtieherudu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtiunnxdiu.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gteapotthi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gtazcogqlt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gtexflqxco.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tian-w.cn/Article/details/gtdbkuvdtc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtosddacvj.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjizvqmx.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gtgvzlmvqm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gtxmkfoohq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gtdbojohzm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtmtmarpcd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtmryrlpzx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtuyuinsrb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswqsuchr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gtfkkoeskr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daxiang520.top/Article/details/gtrbdvmtbi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gtrcosspmb.html

[D11] 反转数组
来源：http://dali.haohaochexian.top/Article/details/gtvqzpbxfa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gthugliqsl.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gtilritzgo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gtttustxdn.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gtfzirsfml.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gtbbummvru.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gtdscxuqtw.html

Ruby: arr.reverse
来源：http://dali.tian-w.cn/Article/details/gtigsqmwoq.html


<!-- 参考信息 -->