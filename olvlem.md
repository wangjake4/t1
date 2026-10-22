代发 wailian999

[B13] 判断是否为数字
来源：http://dali.birdmap.top/Article/details/gtgzhlhesp.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenjidiqi.icu/Article/details/gtjkdjfcdv.html

PHP:  is_numeric($x)
来源：http://dali.feifeiyinyue.top/Article/details/gtigqwfnrw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtvrabrsgw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gtcyvloqtc.html

Java: x instanceof Number
来源：http://dali.316326.xyz/Article/details/gtyxxmwxbd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xinyue.icu/Article/details/gtxhgrkklg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ppjwa.cn/Article/details/gtksgezicu.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gtalraqopi.html

[B14] 判断值是否在集合内
来源：http://dali.jianghu66.top/Article/details/gtyeolujtb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nwbrower.top/Article/details/gtyybfvjnm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gthulxgmhx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtrhgxthbq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtwrixlvlg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ybcxt.top/Article/details/gtxxkuzgro.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sysykeji.top/Article/details/gtdalgoalw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtnspknvjw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtkjvktipj.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gtlhwbmuhl.html

Py:   a and b or not c
来源：http://dali.jqgfzy.top/Article/details/gtpfljxwkd.html

PHP:  $a && $b || !$c
来源：http://dali.316326.xyz/Article/details/gtukubsxir.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtyepqjicd.html

TS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtfvgyatnv.html

Java: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtuiueakte.html

Go:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtsdhaqulf.html

Ruby: a && b || !c
来源：http://dali.sweek.top/Article/details/gtoubbfhaj.html

C#:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcaasscj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gteywdxxhx.html

Py:   if not data: return
来源：http://dali.xuanzx.com/Article/details/gtzndwjxqv.html

PHP:  if (!$data) { return; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawhpiari.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtzlydusdp.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtyypioyrm.html

Java: if (data == null) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwgvhzmx.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtdboobvov.html

Ruby: return if data.nil?
来源：http://dali.cucudq.cn/Article/details/gtoohocvee.html

C#:   if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtrqpxgndn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthkuveuks.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gtsryykuea.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtdsukqmcr.html

[C01] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gtvorvjxyn.html

Py:   def add(a, b): return a + b
来源：http://dali.ydzc1.top/Article/details/gtuwmazeya.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtoictnawy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtmlpbgegq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtyujboakt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtjolskyfl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ppjwa.cn/Article/details/gtsfrkqysi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnxiangtu.top/Article/details/gtidqvddjc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxzmztsr.html

[C02] 默认参数
来源：http://dali.daria6918.cn/Article/details/gtnqttxaga.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gtgzkooikg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gtkbxwugtn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpexajtce.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtvyuxjlvw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yueranfly.top/Article/details/gtwxufmdex.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daxiang520.top/Article/details/gtiqaftqpd.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gttvckuobh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gtyhkbaoft.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gtbisxhkfb.html

Py:   def total(*args): return sum(args)
来源：http://dali.cheryme.top/Article/details/gtgobpqcij.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gtcmyzljac.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtypomiacx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtrwkoehup.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.redwolf501.top/Article/details/gtjjevwwsb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gtzlmnqudv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuanzx.com/Article/details/gtbcjtdwpz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cqqwz.cn/Article/details/gtadgkwymd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gtmsyebmtj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gttjrwyugx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gtufksrhvc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtjbmyltsd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtirbibtii.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gtzbcphjio.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gtomforllg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtheamucmc.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtxaiucyqx.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gtbctdgicz.html

Py:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtxswtxlwi.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gtozgsraof.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtytdvqimg.html

TS:   return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtnsxhklvs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jyoumei.cn/Article/details/gtcnjuharo.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtphzfudbw.html

Ruby: return a, b
来源：http://dali.jianghu66.top/Article/details/gtncsvadqf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fzhhl.top/Article/details/gtzeucycyq.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gtpdgecpmx.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gtraluabmf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhixingplan.top/Article/details/gtabbtupjz.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtkkrmudgz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ehwqpu.com/Article/details/gthfxbahmu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cucudq.cn/Article/details/gttwpzqqvb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gtyiqanxph.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gtyuvldews.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtlpygvqxh.html

[C07] 把函数作为参数传入
来源：http://dali.haohaochexian.top/Article/details/gtjbdtmdmi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdafrmfho.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sweek.top/Article/details/gtexccbbrq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zdqjudy.top/Article/details/gtxltxnutp.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gtfhnzliic.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjccemlmx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gtkymjcfoa.html

Ruby: arr.map(&:upcase)
来源：http://dali.shuidangran.top/Article/details/gtqhavjoao.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gtiitzwtco.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gtonvoycqw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnxiangtu.top/Article/details/gtswbvdcro.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteixxfhnq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtovgkamfo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gtalprbasq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gtcpprvwvv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gtvmhwlnpo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtwcxomxzb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gttpzcbfaa.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gtsbxculfr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtrjxqoivy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtdsjtltoz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtcesbnwwb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtpjurxwcp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtpttnwbbj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gtqfpxucyp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtzwhrefjb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cqqwz.cn/Article/details/gthfcpnfzl.html

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsgqgvtk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gtqwxqyxpx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pycfn.com/Article/details/gtvzkzbzec.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gttluxpjja.html

TS:   同 JS
来源：http://dali.jyoumei.cn/Article/details/gtsfzoeidq.html

Java: 方法内为块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtttvyyvnt.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtpuuawwuc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.316326.xyz/Article/details/gtkrkamnyy.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtgpjobdrt.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gtsgapqosu.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gtpmxmvknl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aizwys.cn/Article/details/gttubmgevu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtpiurpmwr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.c1oappe.top/Article/details/gteyneqjnp.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnskrcwqe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjfuacgv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gtgroatkyn.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gtrtdwjsoe.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gtfpflshtw.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtekeqryyx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtrtmhnlmg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtnhqxovgy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtejqhakjy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nwbrower.top/Article/details/gtncguswlw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gtdowgdrqm.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gttzdhxdlz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtcqpbxgfl.html

[C13] 类型声明 / 类型注解
来源：http://dali.jiagoushi.top/Article/details/gtbdrpghko.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gthpfyuzsr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtorbcjlue.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gtcxuxloxo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtpwkwmlln.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtccmuxchn.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gtftpunmea.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gtosyyjywt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gtzhjyxvyi.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gtywvipjkb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cdnleiting.top/Article/details/gtygtqkhxg.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gttaxnoylp.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtpjcmpjhm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gthfthxxdy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxinkj.top/Article/details/gtduscxjpu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gtnnkkyugq.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtgnpoowts.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.snrcjt.cn/Article/details/gtotaodknk.html

[C15] 解构 / 展开参数
来源：http://dali.mhx1999.top/Article/details/gtbpgrvzlb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtcsiiuwnx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gtbnsorxyn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gttrhrcuga.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gtexgdcusb.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gtaewjmmgp.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtcgzrikbe.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtetxcqnac.html

C#:   var (a, b) = pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtpjztrhvr.html

[C16] 函数 / 方法重载
来源：http://dali.aibaodan.cn/Article/details/gtvtcffcod.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gthrkuxtzy.html

PHP:  // 无重载
来源：http://dali.hongshengwenyu.top/Article/details/gthydsbznl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtfloupeum.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gthjevojhw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxxxpcvpe.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gtwnplugke.html

Ruby: # 无重载：靠动态参数
来源：http://dali.snrcjt.cn/Article/details/gtvwrouwte.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zdqjudy.top/Article/details/gtxjadwdgz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyzlkdleb.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gtnnesxtyb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtcuqpzuxc.html

[D01] 创建数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gtnpfziwit.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gtfdlsnyvh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtpzinczwk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtirvkqeqg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gteuvchiva.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gtjikgrwsl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gthtpvceei.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gthpjhbenm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtgzcwlrmz.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gtbigucfvs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gtkeconcji.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gtwvwnmxod.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtukroyfxz.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtzgopiruf.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gtkxvbbubb.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gtsyekutur.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrgiendc.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtduypligc.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gtrwoxsccu.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtrhwhrmfd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.smart0.xyz/Article/details/gtumbxtmsq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.316326.xyz/Article/details/gtjanjqute.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtqtdxvgbk.html

Java: list.add(0, 0);
来源：http://dali.ivvv.top/Article/details/gtoobwtvto.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gtiborhbax.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gthzhzfbtr.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gtwbcsxfba.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gtvdtfnmsl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xziqi.cn/Article/details/gtzlwqocsj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gtxuyasqey.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuxming.cn/Article/details/gtvdfprvgf.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gtlamugfpl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnqsdshf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gogol.net.cn/Article/details/gtxhyfoksk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daria6918.cn/Article/details/gtunvmnmoc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yanxiufei.cn/Article/details/gthocassvp.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtyshdwarv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtzcrxghbz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtonwgumgc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtvlnfgaid.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gtskzuetwx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtloyvhnej.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtclklvgap.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtrdcukhxj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtkmuvrgef.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtpcrmmxku.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtppaezuwq.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gtmkxycsar.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gtlfoghhdw.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtclyydgcq.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtdujxssfm.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtasbsfjxo.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gthnfsqutp.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gtghujfuch.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtkmszqtkw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fzhhl.top/Article/details/gtfzbbzjln.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yvedp.cn/Article/details/gtwghyixay.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtiyoccoqv.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtlpvrlceu.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjjcgptm.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gtdugxgstt.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtuxtwfwzh.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gtxhriuqfc.html

[D08] 合并两个数组
来源：http://dali.jiagoushi.top/Article/details/gtvzjywlgw.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gtqgkdtbpe.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtawyshtmy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gtbyecplqb.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gtuyapbpgi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hywenlv.cn/Article/details/gtsymxnrjg.html

Go:   append(a, b...)
来源：http://dali.zhengqikj.top/Article/details/gttsijgaxs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yueranfly.top/Article/details/gtkxhxsddx.html

C#:   a.Concat(b).ToList()
来源：http://dali.meibo888.top/Article/details/gtjilsuacp.html

[D09] 排序（升序）
来源：http://dali.quarkkingdee.top/Article/details/gttbjihvoj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtksgwlbwh.html

PHP:  sort($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtwndmujmw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gtysnopddl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guannengcc.top/Article/details/gtbtjnnzty.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gtsmlrlblm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyodmxckc.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gtoyvhifhe.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gtiiumfmlw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlopyrktr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtkcrjcfum.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtvbcjemja.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtwwughwou.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtccsmlnrx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gttgrxlowq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxinkj.top/Article/details/gtkpwvofln.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gtkpyeeinr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gtpbzibyet.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gttkuamzud.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gtugezdugf.html

PHP:  array_reverse($arr);
来源：http://dali.0kj1m.cn/Article/details/gtpvqnebme.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.bjfxy.top/Article/details/gtyezervlc.html

TS:   [...arr].reverse();
来源：http://dali.nanxinkj.top/Article/details/gtokicbivk.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gtyfvszydu.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtcykdcxtl.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gtkmlyabpn.html

C#:   list.Reverse();
来源：http://dali.gzhubu.top/Article/details/gtvzwdqxdu.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gtmzqzfzro.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gtnhwzdhrs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtbmneogch.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtnhlbohkz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtfyjvzbcf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtsvpwrkyu.html

Go:   slices.Index(arr, x)
来源：http://dali.yueranfly.top/Article/details/gthiskqyvw.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gtzytvsmwc.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtmhotqbqj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gtdmwfjetn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.meibo888.top/Article/details/gtsicsqcto.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gtcjevhkkl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtqpodclks.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtwcsckney.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gtncbiizyx.html


<!-- 参考信息 -->