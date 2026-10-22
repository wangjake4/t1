代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2gzuwwzjp.html

Java: x instanceof Number
来源：http://dali.ivvv.top/Article/details/gt2ojisrycm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gt2pdeifomj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gt2zjmolild.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gt2mcjaczwk.html

[B14] 判断值是否在集合内
来源：http://dali.quarkkingdee.top/Article/details/gt2ydtfqhwb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqboutuk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gt2gjcbsqgy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gt2kfgfihan.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2ljjbdtww.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhhjebjg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sweek.top/Article/details/gt2ryvlsxrp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2zbotlnrk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2adyqxuff.html

[B15] 布尔运算与取反
来源：http://dali.tanke756.top/Article/details/gt2nnviocbh.html

Py:   a and b or not c
来源：http://dali.iojbl.cn/Article/details/gt2ytvmmyex.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gt2nrffcezd.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2dycfcwvq.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2eartabqz.html

Java: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2qpduqkpi.html

Go:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2xzodfbsi.html

Ruby: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2udrjjcxe.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2bjbbjfxi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.smart0.xyz/Article/details/gt2vduloces.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gt2qrvprffl.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gt2mxoszmnx.html

JS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gt2bsuiaqyg.html

TS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gt2kkfufgqy.html

Java: if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gt2fzshatwr.html

Go:   if data == nil { return }
来源：http://dali.yj20258.top/Article/details/gt2obvitxlg.html

Ruby: return if data.nil?
来源：http://dali.ybcxt.top/Article/details/gt2jwthqvvc.html

C#:   if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gt2afoaqesd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ziypsrhx.html

C. 函数与作用域
来源：http://dali.xuanzx.com/Article/details/gt2camyrwuu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obpvbcqk.html

[C01] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gt2aunzmjmg.html

Py:   def add(a, b): return a + b
来源：http://dali.yuanzhike.top/Article/details/gt2bphrrokq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ymqhscha.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2xlhhnext.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2tvgurfpz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2kztgbpad.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxibchtc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jyoumei.cn/Article/details/gt2znkfglae.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2anzhyatc.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gt2rvwkxctq.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gt2gozywzmz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtdfamnj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrkxxphi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2yzjtvrlz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gt2dxmrjqok.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gt2qyqwgcyq.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gt2oizpnmmg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gt2hjxobdug.html

[C03] 可变参数
来源：http://dali.quarkkingdee.top/Article/details/gt2xqnauftz.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhixingplan.top/Article/details/gt2gwholmwf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.redwolf501.top/Article/details/gt2wcqwdqce.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gt2jfvhpofi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gt2khxghzzo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fengsongda.top/Article/details/gt2xkeczruz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gt2wpnjgwgd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hammf.cn/Article/details/gt2twcollhd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhongyouzk.top/Article/details/gt2ivmolksc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gaohongyu789.top/Article/details/gt2bqgyrqrg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.redwolf501.top/Article/details/gt2grxbwihs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnxiangtu.top/Article/details/gt2sbmfugil.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gt2mqroamso.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gt2wxesfmsa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gt2rveayzha.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gt2esajmuoz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gt2npiajlaq.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2welogwnk.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gt2vmznapim.html

Py:   return a, b
来源：http://dali.zycfv.cn/Article/details/gt2wtbtolxq.html

PHP:  return [$a, $b];
来源：http://dali.cucudq.cn/Article/details/gt2jywvilzw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gt2indxoubm.html

TS:   return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxstvvtk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gt2txqvlneo.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gt2zayadhgo.html

Ruby: return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmtmtxbe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yueranfly.top/Article/details/gt2nukuxlgg.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gt2fvmmgxwm.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258888.top/Article/details/gt2fhzneohf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ybcxt.top/Article/details/gt2cygpgaam.html

JS:   const square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gt2vpsqqmup.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sweek.top/Article/details/gt2wccxdgzq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gt2upwrrhft.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fccymftn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.iojbl.cn/Article/details/gt2czqxwaru.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2nnutquwz.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gt2mztwmbou.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnxiangtu.top/Article/details/gt2efjignmf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gt2mgpgeuli.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gt2mksivudk.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eepeoxqx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2pcuwcjvs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gt2owztqncw.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gt2wthhnnya.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tian-w.cn/Article/details/gt2hjsbpgzt.html

[C08] 闭包
来源：http://dali.pycfn.com/Article/details/gt2meosauki.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqxdhymd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2augchuvb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2irqunujp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmxtabe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gt2erzbtqjj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gt2ntikkhuz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ybcxt.top/Article/details/gt2jmsooovi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sewhqbgl.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gt2hdilzfep.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gt2lkvjuqju.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2myjodnne.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gt2iepgxtus.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gt2tsqxynri.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gt2xhikktqx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjothezm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2ojamxvjw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gt2ybvetzyo.html

[C10] 变量作用域
来源：http://dali.ppjwa.cn/Article/details/gt2nfbplliq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpljgckn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tianlin.xyz/Article/details/gt2dnrutcrd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2ymjfpxvy.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gt2tivjfqaa.html

Java: 方法内为块级作用域
来源：http://dali.wangdashe.top/Article/details/gt2hueixfkf.html

Go:   花括号块级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2cobyywkh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.svipenyu.cn/Article/details/gt2uzyribrp.html

C#:   块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2ltrjemqj.html

[C11] 模块导入与导出
来源：http://dali.yonumen.top/Article/details/gt2rsvvjomg.html

Py:   from module import func
来源：http://dali.yueranfly.top/Article/details/gt2ysddllpj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gt2kywzbtyw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gt2cnkvwgso.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gt2ajojzcea.html

Java: import java.util.List;
来源：http://dali.shzxlz.cn/Article/details/gt2ucatsman.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gt2blrphieb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shzxlz.cn/Article/details/gt2ykbrogju.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gt2wfbwwaxy.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gt2qbusywuq.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gt2gsbrszre.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gt2pzyssmcl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mennjdnd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmjpofmd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gt2nruswxxt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhrerjob.html

Ruby: -> { puts "run" }.call
来源：http://dali.ybcxt.top/Article/details/gt2wwuwyjqi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2zebrgpby.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gt2bakbccdx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gt2vkvkatcl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gt2auijtukt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fzhhl.top/Article/details/gt2mxxhhepe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2bodzbuqj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2vtnlldjq.html

Go:   func add(a, b int) int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogoxzsrh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gt2sunezdae.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gt2iwlwdkkn.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2veiqoksd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gt2snpdzmvn.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2heqbtzel.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gt2aenvqedo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gt2tsxupygj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idbaoauu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2yryoxigq.html

Ruby: # 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2jcvulqxb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hywenlv.cn/Article/details/gt2pghtwnxe.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gt2pfqywvdf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gt2xxgoahed.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gt2utjmhifc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2lorcqkci.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yangfankeji.com/Article/details/gt2hczdiftb.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gt2ijeytsex.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gt2dirqhfoj.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgqgyibm.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gt2twlftmju.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gt2watokkik.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2vcmuzsjx.html

PHP:  // 无重载
来源：http://dali.snrcjt.cn/Article/details/gt2amrlbimw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guannengcc.top/Article/details/gt2grbxbvwf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gt2fqvguwbk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gt2dkusrdxo.html

Go:   // 无重载：用不同函数名
来源：http://dali.hfpthk.cn/Article/details/gt2onkcxpge.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gt2kvivunce.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gt2upfadezz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2tgqnbdad.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrdripmb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2zvjetypd.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gt2algphowv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gt2otdatury.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gt2txbisivo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpwpbkai.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gt2tianvvoz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.birdmap.top/Article/details/gt2jvgoqiyu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gt2lcyhjnqq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gt2deofloxg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gt2uhtijwge.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gt2vmxgqlrs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gt2nogidwuk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2apcvvigq.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnkztgjq.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gt2idldytji.html

Java: list.add(4);
来源：http://dali.sxryk.cn/Article/details/gt2nwmlylvu.html

Go:   arr = append(arr, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2fhcivurb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gt2evdpgsod.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gt2acharxww.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gt2ongpccyy.html

Py:   arr.insert(0, 0)
来源：http://dali.guannengcc.top/Article/details/gt2ywyyxagu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.kuanghao11.cn/Article/details/gt2ovqjizkq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gt2dqfloawq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gt2omodfpce.html

Java: list.add(0, 0);
来源：http://dali.fengsongda.top/Article/details/gt2axnwkksj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xylfe.cn/Article/details/gt2nslxrbta.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.andypj.xyz/Article/details/gt2oxndxgnv.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2ftnrfwnq.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gt2jdsjulmp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.c1oappe.top/Article/details/gt2qlmscdww.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2zpbnmogd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gt2flrzpngs.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gt2rpgryokh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gt2kejjolhg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pugzhlqy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvcavaov.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gt2hcxjjzcm.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gt2xxgsiybs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2tunbksye.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gt2dtsrgquy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2mfmapzdv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2epsyxeyp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guannengcc.top/Article/details/gt2jvbcpbnq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2bnswzvbi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2ieaxjfww.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gt2joqskkfq.html

[D06] 数组长度
来源：http://dali.andypj.xyz/Article/details/gt2wovoxnbt.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2xspgxaik.html

PHP:  count($arr);
来源：http://dali.gzhubu.top/Article/details/gt2bfpxporg.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gt2bfpvsbyh.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gt2xenkruds.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gt2bsqncbuw.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2gisejsha.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gt2qrivbhwd.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gt2zikczrrl.html

[D07] 切片 / 取子数组
来源：http://dali.hammf.cn/Article/details/gt2abmpnoty.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tianlin.xyz/Article/details/gt2tijbdtqv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2xoryaaaz.html

JS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2wwmqpyzj.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gt2hsenpogw.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2uemohfox.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gt2xljurppr.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnlvznag.html

C#:   list.GetRange(1, 3);
来源：http://dali.ydzc1.top/Article/details/gt2mzzdaiot.html

[D08] 合并两个数组
来源：http://dali.dashuyun.cn/Article/details/gt2olqtwbtq.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gt2vpztamlz.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gt2tpkgylrv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xziqi.cn/Article/details/gt2hwtwludg.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gt2ciwxnzzx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2dgmnngnu.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gt2pojbroyx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvomkelz.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzudunax.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gt2jixheclh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2wbmkvemz.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gt2iawzhbba.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gt2tnmcmcxb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gt2pacwjrwy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhiwuduotai.top/Article/details/gt2urculjka.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2qnhkwcws.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gt2iknlxayz.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gt2xelvfssn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gt2zglkmsbw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ydzc1.top/Article/details/gt2fsgibuwm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gt2jvstswfi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gt2yrgrjzsj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrjyymgu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gt2rtkwpcua.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zdqjudy.top/Article/details/gt2yldzioso.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gt2yswrhnci.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gt2ijluuocm.html

[D11] 反转数组
来源：http://dali.haohaochexian.top/Article/details/gt2haxbayyb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gt2ceeycqdu.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xepxaxan.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ppjwa.cn/Article/details/gt2rymhvjvh.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gt2quspyqfy.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gt2nsdnfhgm.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gt2tpyydcxx.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gt2qjhzqotm.html

C#:   list.Reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltztsarg.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gt2lsuptffd.html

Py:   arr.index(x);  x in arr
来源：http://dali.ybcxt.top/Article/details/gt2nqrwtmcr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gt2azjwbzjz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2kqjmpfwr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2srklkbdc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gt2fxmwpbde.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2mfffqmnf.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gt2mlnqjzbc.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gt2vlpvfvbh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pycfn.com/Article/details/gt2qjdaumad.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gt2iqtqrkmf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hutygjyf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2wvxmntpl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gt2hdmmjnvq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2idmwtnff.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gt2ehinetvm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gt2hvdcilni.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2pdttxlcg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gt2hteazduo.html


<!-- 参考信息 -->