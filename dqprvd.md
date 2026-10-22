代发 wailian999

Py:   if not data: return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufqrjvet.html

PHP:  if (!$data) { return; }
来源：http://dali.fengsongda.top/Article/details/gtrfjvsmuc.html

JS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtvnfcwndt.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtzpgtaruz.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtcdwfdkqg.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gtqkyvipvv.html

Ruby: return if data.nil?
来源：http://dali.dianchejie.cn/Article/details/gtxzypzoqn.html

C#:   if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtecwjsqwd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrtulipib.html

C. 函数与作用域
来源：http://dali.yonumen.top/Article/details/gtpanbxqux.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxtpbscsj.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtqzqasusc.html

Py:   def add(a, b): return a + b
来源：http://dali.daria6918.cn/Article/details/gtkmieqjkl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtsrchhrje.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwchxfvl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtmhjkozin.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtcogezlrp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jyoumei.cn/Article/details/gtwzpnubms.html

Ruby: def add(a, b); a + b; end
来源：http://dali.9152youxi.cn/Article/details/gtkpvmvdgo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtexdxkazf.html

[C02] 默认参数
来源：http://dali.yj20258.top/Article/details/gtmgyillir.html

Py:   def greet(name="World"): return name
来源：http://dali.pengpengdd.cyou/Article/details/gtpevzgkgf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hfpthk.cn/Article/details/gtisfsfnrr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtxfezvaxq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtlandqjbl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhixingplan.top/Article/details/gtyjuztvbg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gttlbaakve.html

Ruby: def greet(name = "World") = name
来源：http://dali.shangyingyoupin.top/Article/details/gtkvnezqxv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.birdmap.top/Article/details/gtncqxcfbc.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gtlxqptssk.html

Py:   def total(*args): return sum(args)
来源：http://dali.jiagoushi.top/Article/details/gtcuytuixb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gteswlpyhr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtzhxinwqu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtiqxgwjhc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gtmzyxfvfl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnqzz.top/Article/details/gttvzwrbln.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gtegdunrfl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gtmldatbeg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gtkzvvysqu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.havefunace.top/Article/details/gtobrqodmh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guannengcc.top/Article/details/gtykuhryzb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaojlarpr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtnehxfsse.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shangyingyoupin.top/Article/details/gtiabtyvig.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gtjbdqvhya.html

Ruby: f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gthdsjhbtw.html

C#:   f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtpmayiqqx.html

[C05] 返回多个值
来源：http://dali.tian-w.cn/Article/details/gtidzeuuwe.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtfefixalg.html

PHP:  return [$a, $b];
来源：http://dali.gotoacloud.top/Article/details/gtbzphliqo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtebgjpdwz.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gthobrsllw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gtzkizcmvj.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtinwpqe.html

Ruby: return a, b
来源：http://dali.cheryme.top/Article/details/gtcflmqmlb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daria6918.cn/Article/details/gtvmosfjof.html

[C06] 匿名函数 / lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxruazrq.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gtbjforahm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gtadhiupsj.html

JS:   const square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtapupwhpw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtsizvqglu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gtpqhbazzl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gtprnryjvv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yvedp.cn/Article/details/gtdsnfloci.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtnofentbn.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gtnlromkqh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gtfxdrmcyl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fzhhl.top/Article/details/gtybcrceuz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gtvvpenbfn.html

TS:   arr.map(String)
来源：http://dali.zhiwuduotai.top/Article/details/gtigskqkdt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gttcwrjcun.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtgtynhfmq.html

Ruby: arr.map(&:upcase)
来源：http://dali.andypj.xyz/Article/details/gtvyfnaeth.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtlsbmdslf.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gtxfvdwjix.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gtmyvzzccv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqmbquad.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtgokustuv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtoxnsinqv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tianlin.xyz/Article/details/gtiwoaxnjr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gtndbhkqli.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gtagjdndvv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gthtdqtbat.html

[C09] 递归
来源：http://dali.xinyue.icu/Article/details/gtrnobdqkw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtwnonokyj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtmejhbftz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gttolbiajr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtcgsrywcc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtjpchqehy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtbktfkerw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtbgmbjbhw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtnpkklhdw.html

[C10] 变量作用域
来源：http://dali.vqdsnc.cn/Article/details/gttbraveyq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.bjfxy.top/Article/details/gtwrmnonfk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gtadtdmvuz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtyylgmxbd.html

TS:   同 JS
来源：http://dali.yuxming.cn/Article/details/gtbpbhcnkc.html

Java: 方法内为块级作用域
来源：http://dali.zycfv.cn/Article/details/gtuyfunzha.html

Go:   花括号块级作用域
来源：http://dali.andypj.xyz/Article/details/gtuxayghir.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.andypj.xyz/Article/details/gtpgbjrjur.html

C#:   块级作用域
来源：http://dali.yuxming.cn/Article/details/gtwcjrcjxn.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gtscnqrkhe.html

Py:   from module import func
来源：http://dali.svipenyu.cn/Article/details/gthqepflln.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zycfv.cn/Article/details/gtrdhhzrxs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtdriaqrnl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ybcxt.top/Article/details/gtzjsmplkn.html

Java: import java.util.List;
来源：http://dali.shzxlz.cn/Article/details/gtuazoxcue.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fzhhl.top/Article/details/gtlolydbqh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dianchejie.cn/Article/details/gtafuwedqj.html

C#:   using System.Text;
来源：http://dali.daria6918.cn/Article/details/gtifhxebrq.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxxtjdqa.html

Py:   (lambda: print("run"))()
来源：http://dali.daxiang520.top/Article/details/gtpynrjreb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gtdutsjjdn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtvhuethpo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtclmlnhdw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhixingplan.top/Article/details/gtaitsxnsc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gtzkklktmt.html

Ruby: -> { puts "run" }.call
来源：http://dali.daria6918.cn/Article/details/gtyzrgztcz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gtxwuccxai.html

[C13] 类型声明 / 类型注解
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydpkqast.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gtfwqkdnkc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtakvykobl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gtjppviopi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtkthahfer.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtrqgjajeh.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtqgrimpmw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuxming.cn/Article/details/gtdievirsm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gtyoaxmxqz.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gttjvbzvez.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazmwpyua.html

PHP:  // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtwxebqdot.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtifcxovnc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gogol.net.cn/Article/details/gtjrkroyew.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gtablgajbj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gtgmxrrdjh.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtknuefosb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigfzy.top/Article/details/gtytrctieb.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gthqffahju.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gtivjenhap.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gtqqvabtim.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmksnlgxd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtfbqzappl.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtnjgesjdi.html

Go:   // 无解构
来源：http://dali.iojbl.cn/Article/details/gtwspizdtp.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gtszjowzgq.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gtmgfcdeak.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gtbkgfwtth.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtpccomwre.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gtmdfdqwvz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gteewmnssl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.andypj.xyz/Article/details/gtohlpefyx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gtfymibrck.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gtgvdjavea.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gtffqhbmnp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jlsjyb.cn/Article/details/gthtrpcvqs.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtteroxilt.html

D. 数组 / 列表 / 集合
来源：http://dali.hysaishi.cn/Article/details/gtcjzspmzy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtexaqmacc.html

[D01] 创建数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gtcygztahb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gtqdphzagw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gthaeynykj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gtxjsgkmmc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.316326.xyz/Article/details/gtkhvnssxe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gthcaoizbt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sxryk.cn/Article/details/gtqxjhqxfr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gtlyhqzysm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gtckroafxw.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gtybjzaxal.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuxming.cn/Article/details/gtbmtmujml.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gtrmjtohwn.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtneuyrfwi.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtagevbikp.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtlgzgnikb.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gttntwcohb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.0kj1m.cn/Article/details/gtyuknxnuy.html

C#:   list.Add(4);
来源：http://dali.pycfn.com/Article/details/gtvkxefbch.html

[D03] 在指定位置插入元素
来源：http://dali.tian-w.cn/Article/details/gtohvtbedu.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpldnyzdg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cucudq.cn/Article/details/gtnosjpefq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gthigmiext.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gtwzbjzgfw.html

Java: list.add(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtzlhgxxaz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtvplbgrzm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.c1oappe.top/Article/details/gtcxdxtfxn.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtubywlqtq.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gtmidloiwo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtwalbdbim.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gtopnfbmbe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daxiang520.top/Article/details/gtrubiffdc.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtkdvgcnjk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gtbuzugcbz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtngxxaafd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sxryk.cn/Article/details/gtmwqkvrts.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtrreeaj.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gthjpbpwjt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtgewybcmj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtzsevtujz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtdzybjnft.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tanke756.top/Article/details/gtcwdmnvkj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gtnibadeeg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtizfligki.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtzdihprwj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqczpzeo.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvhbatoz.html

Py:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtmrsdjidm.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtpomzthvl.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtbfciqljs.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtwjfdaibj.html

Java: list.size();
来源：http://dali.ybcxt.top/Article/details/gtusvyfxrk.html

Go:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtrwvuzfvf.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gtukldzvpz.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gthvalbdxl.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258888.top/Article/details/gtmtbyvpnq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gtyhmwcmim.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gttycxduwr.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gttpxcmpgp.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtiboecwox.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtmrrkrate.html

Go:   arr[1:4]
来源：http://dali.mhx1999.top/Article/details/gtfuquvyfj.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gtlakwmkaf.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtwglqryom.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtcjwojixb.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gtaxukxsqa.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gtrhplable.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.andypj.xyz/Article/details/gtuqvjltbx.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gtwgvuadgx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtrmoyqrge.html

Go:   append(a, b...)
来源：http://dali.yj20258888.top/Article/details/gtrtuyxrnh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gtwixlvnfq.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gtezlosjdb.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gtislpjqlc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtfhkwmxka.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gtvmdwjehs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtrhrdngqe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gtjsmkofeu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gtaiypebmz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtxfcstfcj.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtmcjfivns.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gtenrrxihv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.316326.xyz/Article/details/gtyzzjqrkq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tianlin.xyz/Article/details/gtjdxhnaiu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gtykuyjmyu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gtpoiqlvkc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtatmkbgtp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gtjgqklzae.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtzxgmktio.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtpllmprvk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gtdkordyxl.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gtwapbzyxo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gtxsjnnjwp.html

PHP:  array_reverse($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtiaxuizji.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cucudq.cn/Article/details/gtamengxtd.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtqnfprphy.html

Java: Collections.reverse(list);
来源：http://dali.yueranfly.top/Article/details/gtamfbdpzx.html

Go:   slices.Reverse(arr)
来源：http://dali.wangdashe.top/Article/details/gtfuxfbicl.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gtkqjhffjl.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtyywjtkvw.html

[D12] 查找元素下标
来源：http://dali.zhengqikj.top/Article/details/gtvsummeiy.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gtxegppwgz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gtdawmbrrp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gtuofrqpeg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtqzaqjorx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtpowvjqfj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtqjanyfvd.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gthvbcdvdt.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gtedadblhw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gtmmgcwgbo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gtndkvrnzy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gtfjibdfus.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtjkijpoft.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtnnwajjgd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdllivvd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gtbptsmles.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gtammfscfh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtdnwxtkno.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gtnnqqguup.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cdnleiting.top/Article/details/gtbarkxxwu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtdfgsksyd.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtoxshuvqq.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtlorlzjdg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpljfbcgm.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtfbknuicw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gtfxrouawi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsrrsndp.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gtgxoootct.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtbiknjbvb.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gtfnwxqzog.html

JS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtmotlrpos.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gthclkxcbk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zdqjudy.top/Article/details/gtmhtrsrfz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgfzy.top/Article/details/gtawiobvqh.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gtlaecmpax.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gtlkphrpkc.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gtlvfjsdoj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtgfomldcv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gtefycpzwg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtejhozpue.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtkufryych.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gtaypkxotz.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gtyavytptf.html


<!-- 参考信息 -->