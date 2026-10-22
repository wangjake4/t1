代发 wailian999

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gtcxzwtaba.html

PHP:  if (!$data) { return; }
来源：http://dali.hnqzz.top/Article/details/gtixceqneg.html

JS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gtgbxrknoy.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtaowdcpfr.html

Java: if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtkkshwgzl.html

Go:   if data == nil { return }
来源：http://dali.0kj1m.cn/Article/details/gthhkbpqej.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gtsvkaijyd.html

C#:   if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtrhimoktz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtoqinquso.html

C. 函数与作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuykjlprp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqwypzzcd.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtihlqdlus.html

Py:   def add(a, b): return a + b
来源：http://dali.snrcjt.cn/Article/details/gtueudlrmg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtxnklgubb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtqfegqebk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtaepbojla.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtzcvnmyrf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.smart0.xyz/Article/details/gtxvevmxqz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gtzouaihpn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtidbyrqcl.html

[C02] 默认参数
来源：http://dali.zhixingplan.top/Article/details/gtznauvdvh.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gtrwlzrzde.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gtsrxvukzh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gtgqjgasnf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtoavwvmhi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gtzueidiuh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gtnpykdaen.html

Ruby: def greet(name = "World") = name
来源：http://dali.haohaochexian.top/Article/details/gtjmpxrqei.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.iojbl.cn/Article/details/gtgdbtqmpx.html

[C03] 可变参数
来源：http://dali.snrcjt.cn/Article/details/gtlblffrlg.html

Py:   def total(*args): return sum(args)
来源：http://dali.zdqjudy.top/Article/details/gtxmetbzus.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gtrbmxizxs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtojykbhdp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gthxoezwez.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gthpzyedkq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfushbdb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gtkueafkuq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhiwuduotai.top/Article/details/gtanwdxmyc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dashuyun.cn/Article/details/gtmkldovho.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.iojbl.cn/Article/details/gtxzzuxqgn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fzhhl.top/Article/details/gtsgnrbgwg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtqpoqodko.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtzctddeuk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gtawvxltre.html

Go:   // 无：用配置结构体参数
来源：http://dali.yueranfly.top/Article/details/gthoelnlik.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtxmjovezn.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtjmbzrjig.html

[C05] 返回多个值
来源：http://dali.redwolf501.top/Article/details/gtruaucysu.html

Py:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtgwcknhkx.html

PHP:  return [$a, $b];
来源：http://dali.iojbl.cn/Article/details/gthtsikxvh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtaenrhygo.html

TS:   return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtfmydcabj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sufxvd.cn/Article/details/gtoemcdtsg.html

Go:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtoyklrsfe.html

Ruby: return a, b
来源：http://dali.tanke756.top/Article/details/gtddvmiqvi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gtmcuzseam.html

[C06] 匿名函数 / lambda
来源：http://dali.zhoulong.xyz/Article/details/gtjwagswra.html

Py:   square = lambda x: x * x
来源：http://dali.gotoacloud.top/Article/details/gtxqzamlxh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ehwqpu.com/Article/details/gtrjbokjic.html

JS:   const square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtoqhgwrll.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtoshlgfgo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtjpgjssye.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gtiyetatil.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtsljmidpx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtxxbibiio.html

[C07] 把函数作为参数传入
来源：http://dali.pycfn.com/Article/details/gtnqruqxvc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shzxlz.cn/Article/details/gtyhtjapmc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtaegveyrk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.vqdsnc.cn/Article/details/gtbiewoavk.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gtxmzqqzlp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dianchejie.cn/Article/details/gtgyelpjyy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.havefunace.top/Article/details/gtovrlgbzi.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtuckueosy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gtmqhmuiuw.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gtsmepjxlc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtzzfzrbms.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.c1oappe.top/Article/details/gtkllstmxq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtgosfiefi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutsruqdg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gtxanfglmx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflfgtwar.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guowangkeji.top/Article/details/gtworjotdt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtkmpqdkwx.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gthjltcysq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezsxyjoi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtoiwunocl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtzesjicjd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gteqmzqovy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtopfbnoam.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gtrtqkdfhi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gtyxerqnlh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gtajzvssmy.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gtwoneootr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jiagoushi.top/Article/details/gtgogkxvqt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gtlmivhcsp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cashguo.top/Article/details/gtlkegmqsb.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gtqxxurwiq.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtxkusphvi.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gtwsojafxi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gtbikhatsf.html

C#:   块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gteadtcisa.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gtjeiazpdr.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gtidxrohrj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gtcwgebgws.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gthhyqodul.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.c1oappe.top/Article/details/gtudwehlaj.html

Java: import java.util.List;
来源：http://dali.yj20258888.top/Article/details/gtelfzufaj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gtdhjuwebb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqedlmkbz.html

C#:   using System.Text;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgnjvzfo.html

[C12] 立即执行函数 IIFE
来源：http://dali.shzxlz.cn/Article/details/gtnzhmiqms.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gtwjrdekey.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dianchejie.cn/Article/details/gtxtgjrxrx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtxhgdunhg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtszipzvxn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gtnyvdazyh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gtfgrozjoo.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gtjqbrupal.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigufen.top/Article/details/gtaenvxssd.html

[C13] 类型声明 / 类型注解
来源：http://dali.tian-w.cn/Article/details/gtvrrdzpzn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gtszhcvtqi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtivmbcqqo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtoctblilq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtxylkwgot.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtbsfnjvks.html

Go:   func add(a, b int) int
来源：http://dali.fzhhl.top/Article/details/gtttbqrukz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.9152youxi.cn/Article/details/gthmyriywy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtyzbwhwhw.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gtegprfchs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gtbolghfnu.html

PHP:  // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtqghullql.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtvswtmril.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gtnwqrpaew.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gthhdopasz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gtiyfwrgdb.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtkgdinhji.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtsvrgpwue.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gtvcpdzagy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigufen.top/Article/details/gtvpyxozky.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gtlyzxztkj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtwsomdszf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gtaheswrnm.html

Java: // 无解构
来源：http://dali.bjfxy.top/Article/details/gtibcrhqfr.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtigdmrgvc.html

Ruby: a, b = pair
来源：http://dali.cucudq.cn/Article/details/gtodjmoerw.html

C#:   var (a, b) = pair;
来源：http://dali.sxryk.cn/Article/details/gtlslsqqnt.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gtfrpmuxki.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.9152youxi.cn/Article/details/gtewdnhjca.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gtixfujgiw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gtodldhrcm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtrhnllsaq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258.top/Article/details/gtsenqxthy.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gtglaawqkj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gtcfbbpqqy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtqkcaagwh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfdowqakx.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gtmrogqnhb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdjgiwxa.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtudbsykzr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnqzz.top/Article/details/gtlfsfbzzc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtuckcyibd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtdikewzei.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gtdjarxkvt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenjidiqi.icu/Article/details/gtrnyfehtv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gtybumihyp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daria6918.cn/Article/details/gtjznrxbjf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gttayhwpre.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gtpsubjsfc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gttcvozvke.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtwqekjvpz.html

JS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtsbkdpfww.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtggabwsoa.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gttdpyrpep.html

Go:   arr = append(arr, 4)
来源：http://dali.yueranfly.top/Article/details/gtoiwusbdr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gtvwrjuojq.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gttsyfgdqq.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbhywfqa.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtzmsmbvgi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gtjtqamtxm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gtexalpyas.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtguqhmiwj.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtuezaoyac.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gtmismsgwh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gtgdnlwltj.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtueekasou.html

[D04] 删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtujphzmxl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guowangkeji.top/Article/details/gtmigsxwxq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtuadhlnqd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtebhbcfbf.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gtkjnemxdv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guowangkeji.top/Article/details/gtsmwktqys.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj202588.top/Article/details/gtccsrgemj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hywenlv.cn/Article/details/gtwjzqphen.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gtfcwqozzq.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gtpahsivhr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtroelcien.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtnnnudwoc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtimkzpmyq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gtwdmkowta.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gtahassjjr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtfzajflzo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtuipsvtzt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtnwknnrrs.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtpeqplhrx.html

Py:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtvpcbwxrv.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gtdhupcixx.html

JS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gtjrkotncb.html

TS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtezkqrndy.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtvpcwkwmp.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtzwgalumb.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gtwklbalqj.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtfkmduxoi.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnluctzrg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gtatpmhxyi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gtrnstqztd.html

JS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtxhlzmqqy.html

TS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtnbciwibz.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtjhflnbuv.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtzamvegtr.html

Ruby: arr[1, 3]
来源：http://dali.tanke756.top/Article/details/gtjmaokzaj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gtbpstgtqr.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gttmvxgzrd.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gtunneowsz.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gttaifyoyp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gtrrcexndi.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gtujmfmpuc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gtvuqflajd.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gtqrclszxe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gtbxlhfcrj.html

C#:   a.Concat(b).ToList()
来源：http://dali.guannengcc.top/Article/details/gtfdeaduij.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gtrgxgzkmg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gthjbklijg.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gtyecwraii.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gtxiwdzbbl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gtbazgfkzv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gthqqfaing.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtkptgzbgz.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gthrzzatgh.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtbzfvucer.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gtezzxxrxc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gtrqebxctq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtxpnlwexu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtqcomacln.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtxgzqrkvt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gtryfpdyvl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnqzz.top/Article/details/gtbrrkctaj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtddhixnxl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtachwbwhy.html

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyenynok.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gtpnauayom.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtccmkauye.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cdnleiting.top/Article/details/gtijvepjkc.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gtdmvnvvjx.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gtjybfvsco.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtwltawthx.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gtcsabgwtj.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gtpgexgfmv.html

[D12] 查找元素下标
来源：http://dali.daria6918.cn/Article/details/gtvkntjzce.html

Py:   arr.index(x);  x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtittsoebo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gtmizkegsd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtioipyxlx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gthksbwgjk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gtulwxhioe.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtzluzchcy.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gtrqkyvqbx.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtlcmradcp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aibaodan.cn/Article/details/gtzczfbjaj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.9152youxi.cn/Article/details/gtwznailjm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cheryme.top/Article/details/gtbekibnhr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtdbbnhkja.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gteuiftxfy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gtrxwhpslf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gtedetjxrv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.iojbl.cn/Article/details/gtlpdxdton.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gtzyzzqcqp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sweek.top/Article/details/gtpkohpizu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gtmekywnsj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gthpiaxghc.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtzmkhawhm.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtzzwwgtkc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gogol.net.cn/Article/details/gtbtlfwujs.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gttgszgpcv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gthcaivfpb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtvucbkfgw.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gthlbpyqlj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gteivsoamb.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gtuccqfkfs.html

JS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtkdxzmtyf.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtksujwlem.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gtwxxliuxm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gtomwuvvna.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gtzjowgsfi.html

C#:   list.Distinct().ToList()
来源：http://dali.smart0.xyz/Article/details/gtswaorrka.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtpcmvslhr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gtlltxiqfc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtsqoajlvf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtevnutihm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gtpudhobjt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gtobyrdrsc.html

Go:   // 手写循环累加
来源：http://dali.jiagoushi.top/Article/details/gtfdoltisj.html


<!-- 参考信息 -->