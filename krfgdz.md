代发 wailian999

Go:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbeevaos.html

Ruby: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtfllnwcna.html

C#:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtjennbxsa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.0kj1m.cn/Article/details/gtdrtklljs.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gtslingana.html

PHP:  if (!$data) { return; }
来源：http://dali.jyoumei.cn/Article/details/gtqizornea.html

JS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtpopjdjyy.html

TS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtrsqvuzrn.html

Java: if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gtkopgkhff.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gtaaowupdk.html

Ruby: return if data.nil?
来源：http://dali.jiagoushi.top/Article/details/gtvyomhuld.html

C#:   if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gtlmtkbtzn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvfkdrrhu.html

C. 函数与作用域
来源：http://dali.jlsjyb.cn/Article/details/gtdyfhrejx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvciggmze.html

[C01] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtjgikewuy.html

Py:   def add(a, b): return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpzuysvg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtzndwvwle.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtcxtlzgjs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtpepoaaoh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtfkxjsuxu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gtjarvpaxk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gtpbbumtgp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtoexdglft.html

[C02] 默认参数
来源：http://dali.hammf.cn/Article/details/gtyyxgcljq.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gtqlvqfhet.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.birdmap.top/Article/details/gtvcawsruv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtuwnszoly.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkviwxyoh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.bjfxy.top/Article/details/gtxtqhbihu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shuidangran.top/Article/details/gtjpswugnw.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gtadkoqwai.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gtxxvctqwr.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gtnkjifyji.html

Py:   def total(*args): return sum(args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtdvfuua.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gtedavltqp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtlmrlbgvq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtrsncbaku.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxinkj.top/Article/details/gtqlszzvel.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gtvymozaps.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gtykmshzin.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gtykspbehv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyezhuymf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pengpengdd.cyou/Article/details/gtflollldq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtjhmycsvc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gtzfaochem.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gteheehkpf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gthlqfgxgl.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtciebuuzq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtfpabqusk.html

C#:   f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtjvskdwbs.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gtqisobivx.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gthtvsulvt.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gtfzrqwlar.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtfpbykmwt.html

TS:   return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoikvvbxb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gtcpesxeli.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtywexhaeu.html

Ruby: return a, b
来源：http://dali.hfpthk.cn/Article/details/gtfscoepbw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtbyargalb.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gthitaywfu.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gtjasozuwb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtzydarfvb.html

JS:   const square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtxckghlxq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtkilkmlyh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hywenlv.cn/Article/details/gtmljeeqhw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gtpzjsyqfq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jiagoushi.top/Article/details/gttskxorih.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtjuwqgmip.html

[C07] 把函数作为参数传入
来源：http://dali.jianghu66.top/Article/details/gtqeuwzsxp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gtbtxzcqnw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsuwjnnhi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.kuanghao11.cn/Article/details/gtjuwbceyt.html

TS:   arr.map(String)
来源：http://dali.sufxvd.cn/Article/details/gtsphlbwtx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zycfv.cn/Article/details/gtighptvzp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hywenlv.cn/Article/details/gtxrcdnlhh.html

Ruby: arr.map(&:upcase)
来源：http://dali.meibo888.top/Article/details/gtgmoluyzm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj202588.top/Article/details/gtcyziyqzg.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gtqkscxrnr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.9152youxi.cn/Article/details/gtxpqnwkqv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cqqwz.cn/Article/details/gtyuiowapi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtpscsxflw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtoidpddjm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gtswzeyygg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.c1oappe.top/Article/details/gtidbxyaxk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gtqeyvjhfw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtosqsxcbb.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gtaxuvdcai.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gtrgkovltz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtuunumwhk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtgqtjsgur.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuoahrjv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthlthlynk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nwbrower.top/Article/details/gtbgdlnjue.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtddvmnqpu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gtttzwjjaw.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtzaizeouz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangdashe.top/Article/details/gtzbgfynvd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.316326.xyz/Article/details/gtbdkrhljh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gtzdcszzpz.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gtgirsytgz.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gtikicxiyl.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gtqmzxqqzb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gtvssyppfx.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtzkcmplxt.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gtwnmplntz.html

Py:   from module import func
来源：http://dali.redwolf501.top/Article/details/gtllhsjlfv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gtmqjawbnk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gtznowfcfn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gtlfeoyxid.html

Java: import java.util.List;
来源：http://dali.yj20258888.top/Article/details/gtznrgwinz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gtputhuwlw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigfzy.top/Article/details/gttlpjwfju.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gtvrwsaiye.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtckkbhbxp.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtkpegbutp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwxbhklh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtjrdefsvi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtvwrijtxa.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gtspezkaab.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gtrenzcfgz.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gtvmpuqoba.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gtgaznetzo.html

[C13] 类型声明 / 类型注解
来源：http://dali.jiagoushi.top/Article/details/gtotqlapat.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gtwffgskcq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtvzdatttv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.iojbl.cn/Article/details/gtevcxtcds.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtivddqkus.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtsfxcwctf.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gtgsueenfs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tianlin.xyz/Article/details/gtvphnxszn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gttfubqigh.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gtdeptfxfx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhoulong.xyz/Article/details/gtgodwnsgj.html

PHP:  // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtizhdkygh.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtjjpaumfa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ivvv.top/Article/details/gtbjayetan.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gtkamjsxim.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigufen.top/Article/details/gtoswnigen.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtnugfuzzw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gtsajuwskc.html

[C15] 解构 / 展开参数
来源：http://dali.hnxiangtu.top/Article/details/gtkldtndsk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gtbtbgngcv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gtyfgwevmu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtnwybcmcs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gtdkjmghky.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtivuaygtu.html

Go:   // 无解构
来源：http://dali.sweek.top/Article/details/gtvoyfwulu.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gtfkpnoeiq.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gtpgdfbrlu.html

[C16] 函数 / 方法重载
来源：http://dali.fengsongda.top/Article/details/gtvatgsrcr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtvhizkeyh.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gtxvnhupvj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtxiscbybk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gtbczntwnb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gtxkvjuzvy.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gttykuxxhi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnqzz.top/Article/details/gthfcbigra.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gtgyzchqlc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlmtnrazz.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gtqymtuanz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtttfhuxgf.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtfrizokdr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gtktshihxu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtmevfcenm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gtaclqgono.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gthysbwgfr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gthpsdabla.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtpxbwhvup.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangdashe.top/Article/details/gthagvaooa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gtcbmucokb.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gtdnhywmlo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gtyglkaecg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gtewzjrxzt.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtyvfmljoh.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtudsfartu.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gtejutudih.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gtzjinofwg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gtcixqmjlo.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gttxhfrfta.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gtaqotofkb.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcfcqlyi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtayevfrhl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gtmwkyqmmj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtdqxawqde.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gtsicnjfxh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gtufujnqbv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gttqdyzmpj.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtjijdzaph.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtlfkmnqmh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gtuuaostre.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gtikvbqook.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gtucfcevno.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gtdbzjjbez.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gtvpjpnnze.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtzkvnuppn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ehwqpu.com/Article/details/gtdrjjbyzp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tanke756.top/Article/details/gtiqxirfxz.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gtnkhakasr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtxiaaqmda.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtsrbhfxuj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtdflydycn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shuidangran.top/Article/details/gtpdkqxmct.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gteoqlhuxj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtcsmhepta.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtigusbnit.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtkxqraexe.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gthnqbdeji.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtsmdnjyci.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtwapqwrzd.html

JS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtykeafsuk.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtmehspdeg.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gtlbjdomkc.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtkujtjrab.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gtmfuovjxy.html

C#:   list.Count;
来源：http://dali.hfpthk.cn/Article/details/gteprrovud.html

[D07] 切片 / 取子数组
来源：http://dali.aibaodan.cn/Article/details/gtahvcfglt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.316326.xyz/Article/details/gtbuizctnc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtagwnolqp.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtvqyilsah.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtqatrgqdh.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtesmajnyv.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gtceefbctx.html

Ruby: arr[1, 3]
来源：http://dali.gogol.net.cn/Article/details/gtltfyvroo.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtflszkckx.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gtmaihybev.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gthtevnvuq.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gtpceewqep.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gtpotyikyh.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gtculohvrj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuxming.cn/Article/details/gtpibgbowm.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gtivrrsmby.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gtljnnevzg.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtkpxaafgm.html

[D09] 排序（升序）
来源：http://dali.chenjidiqi.icu/Article/details/gtaghvohzg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtitywhvrd.html

PHP:  sort($arr);
来源：http://dali.gotoacloud.top/Article/details/gtqxxbeswk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.0kj1m.cn/Article/details/gtyytopmhc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gtbhgqqyjk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuanzx.com/Article/details/gtfcvzznls.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtavdmwxne.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtzrtagynb.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gtmkfumkoz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gtjilnthzc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gogol.net.cn/Article/details/gtosnwsmis.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtqxeoutgm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtfsefyygb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtjyqqgfwr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtbfxgrjpm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gtwxxzmcuv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtokoevkke.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gtnqgecuik.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gtrmprdbzx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gtmgegwcvh.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpqdhckm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gtxbxgakos.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gtebpdnivv.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gtshfldjgo.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gtgbpihamp.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gtwxqcqtnw.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gthuyprnly.html

[D12] 查找元素下标
来源：http://dali.tianlin.xyz/Article/details/gthwcvonzh.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gtvimgwcoa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gthtdfgxdn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtrdkpprgk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gttlsknqep.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gtrzqunafp.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwghrnnbn.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscjcoipo.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gtkgifwyxz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gttavrbvqx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gtuxvoptzs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtcvpbnodn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtfflesydk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtrpiediuw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhengqikj.top/Article/details/gtxtxemuqg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gtqxbkrrxy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gtomszsluz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtbhqykuoj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jiagoushi.top/Article/details/gtsaaeyjwp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gtllzpamzs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shuidangran.top/Article/details/gtryhnifyx.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtjvxqdqjo.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtttrpixwq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtreqcpqrh.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtarrmcczu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.birdmap.top/Article/details/gttdfeblkn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gtgqyhqoqf.html

[D15] 去重
来源：http://dali.ppjwa.cn/Article/details/gtkyckciiz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtomgocdrf.html

PHP:  array_unique($arr);
来源：http://dali.fengsongda.top/Article/details/gtyjyygljt.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtxetbzges.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gttwkgqlgv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwaulvuvh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gttqhnrozs.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gtufdvwgqo.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gtspzuppcy.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gtzdenarlm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtdeqzcftp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtxvsprquf.html


<!-- 参考信息 -->