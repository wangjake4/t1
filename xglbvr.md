代发 wailian999

Java: if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gt2jybtbymd.html

Go:   if data == nil { return }
来源：http://dali.yj20258888.top/Article/details/gt2rwoqkack.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gt2ombfktlv.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gt2totejcse.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2wrtawvec.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gt2xfvhgtjn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2eweqxvkl.html

[C01] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phuhvrgb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhflwynt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yaqgporp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qhazknoq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcpizgrk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2yrketynr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gt2hamtuhpt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cdnleiting.top/Article/details/gt2ciekftdq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2tubxezec.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gt2ypsdaacy.html

Py:   def greet(name="World"): return name
来源：http://dali.gzhubu.top/Article/details/gt2lgeivwop.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsavobrc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2hblunbit.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2qpnmkrdt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2jcxuaaat.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.snrcjt.cn/Article/details/gt2xdbzsjcc.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yaidfxkx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.snrcjt.cn/Article/details/gt2esytpbpd.html

[C03] 可变参数
来源：http://dali.andypj.xyz/Article/details/gt2vlywtrwr.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gt2jcpuupvy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sxryk.cn/Article/details/gt2nfvierhv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gt2moklqdsj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gt2prslfwow.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcveywsk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gt2rsyfnpqp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cucudq.cn/Article/details/gt2ppzgnyoj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gt2demqjzpq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenzaomai.com/Article/details/gt2ppgyaiib.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tanke756.top/Article/details/gt2ivxnevwu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gt2dnllvcku.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2ucvnpkuw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gt2mwnevdwz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gt2icgdqgec.html

Go:   // 无：用配置结构体参数
来源：http://dali.hywenlv.cn/Article/details/gt2suymmzmu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2vmdqcitc.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2orxbergl.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gt2zepyrkiz.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gt2mswiysun.html

PHP:  return [$a, $b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qncxrbot.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gt2flbtynev.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gt2avoristh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2fflrihrm.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gt2fdmabbqq.html

Ruby: return a, b
来源：http://dali.jinqigfzy.top/Article/details/gt2cszwzico.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sweek.top/Article/details/gt2svewsywe.html

[C06] 匿名函数 / lambda
来源：http://dali.haohaochexian.top/Article/details/gt2vnhrjuhi.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gt2yyoesqmr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gt2xezcdrvq.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2dmltrbrv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2jnwmfmcs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.c1oappe.top/Article/details/gt2qixirkoy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxuanxn.top/Article/details/gt2shyfytom.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gt2jgvpakxd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2czurkiip.html

[C07] 把函数作为参数传入
来源：http://dali.birdmap.top/Article/details/gt2dkubaqrf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yuxming.cn/Article/details/gt2rshztprb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.mhx1999.top/Article/details/gt2qncjmjbl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.quarkkingdee.top/Article/details/gt2lxlytdox.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gt2vrfkemyq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2kvqtrduu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgfzy.top/Article/details/gt2nzphbzqx.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gt2ymtyrxbm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.9152youxi.cn/Article/details/gt2ybwlhelo.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gt2ssbsqmte.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhengqikj.top/Article/details/gt2fxvbpjcz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.svipenyu.cn/Article/details/gt2hvfpqprd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gt2jnddtart.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gt2isofkfoc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhixingplan.top/Article/details/gt2ufxohsqr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gt2ialofbsp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aizwys.cn/Article/details/gt2dajjjyip.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2ngthtkxf.html

[C09] 递归
来源：http://dali.hfpthk.cn/Article/details/gt2sctfvwli.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gt2mhdoseeq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gt2illcdrez.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gt2npekrnpw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gt2rfjefsbt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gt2bybihekj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gt2zakudivb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gt2jfuwfmfp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gt2axyabpst.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gt2pohvdzqp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxinkj.top/Article/details/gt2ntkcuvdw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgzweuv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daria6918.cn/Article/details/gt2ipzjwrdh.html

TS:   同 JS
来源：http://dali.nwbrower.top/Article/details/gt2jshakwvl.html

Java: 方法内为块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2wbvczuwc.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2pqaotjrc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.haohaochexian.top/Article/details/gt2gdjhmkwg.html

C#:   块级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2ijogcxtj.html

[C11] 模块导入与导出
来源：http://dali.yj20258888.top/Article/details/gt2xuydlfwz.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfunuriq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gt2kxximbrl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gt2bfbryduq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gt2loyyjent.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gt2oeudponu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.bjfxy.top/Article/details/gt2dmlmcraj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxidztri.html

C#:   using System.Text;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxlumpgs.html

[C12] 立即执行函数 IIFE
来源：http://dali.daria6918.cn/Article/details/gt2ddewsszf.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gt2bsoocrst.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hammf.cn/Article/details/gt2kfqgopsc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gt2htyonvzg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gt2lxsfdykv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gt2dyrnklih.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gt2oqmpilnt.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gt2qgdgbqgy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2extbdosr.html

[C13] 类型声明 / 类型注解
来源：http://dali.guowangkeji.top/Article/details/gt2fngxncpf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gt2pahchmrv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2jzfvjhya.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.snrcjt.cn/Article/details/gt2qkgxdnbm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2oljzmiqy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mxxgvpcp.html

Go:   func add(a, b int) int
来源：http://dali.sweek.top/Article/details/gt2oqdyitvh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gt2hrfnrasr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gt2gavzheiw.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gt2hmsnmtyx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gt2fxqtuyrc.html

PHP:  // 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2bpvqiwpz.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arukjbpt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzazjdpd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ehwqpu.com/Article/details/gt2itszgrog.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcupzpm.html

Ruby: # 无泛型
来源：http://dali.chenlongwang.top/Article/details/gt2vkkccgih.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gt2fzbnvrtu.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gt2grydasgu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqbgkbvx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gt2nkeswywv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2smihtpgm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2frvxicmg.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gt2fqlskqyc.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gt2oczfadfv.html

Ruby: a, b = pair
来源：http://dali.andypj.xyz/Article/details/gt2tdgyydsb.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gt2ggsvbokh.html

[C16] 函数 / 方法重载
来源：http://dali.sxryk.cn/Article/details/gt2phqrzpew.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gt2qtwwtphp.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gt2epdntzvu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jyoumei.cn/Article/details/gt2vogdkuxz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gt2swckswbj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gt2fcqmjrch.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gt2cikgklmo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xylfe.cn/Article/details/gt2wdwvomcw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guannengcc.top/Article/details/gt2ocaqiebz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ofwmskie.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gt2ubwdtrnc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmzgorwy.html

[D01] 创建数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gt2wgchiuly.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gt2bpkqwzhv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cucudq.cn/Article/details/gt2wzkszmyj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2puwnuooz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gt2qtullipv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.bjfxy.top/Article/details/gt2azjrhfdu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lprsuanx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gt2hihemvin.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gt2nqgpxqqg.html

[D02] 追加元素到末尾
来源：http://dali.redwolf501.top/Article/details/gt2tmcvginc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gt2kottuhoq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gt2gplrparc.html

JS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gt2vbbroeet.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2hhvbydnm.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2simjjmxx.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gt2lukejsor.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gt2quqbvuqv.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlcinnqd.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gt2tjvbrnbq.html

Py:   arr.insert(0, 0)
来源：http://dali.pycfn.com/Article/details/gt2ruyhehin.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykrjdqad.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gt2rwucdtfw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2bbmzqviz.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2hmtlqfcv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gt2jjnmquez.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.kuanghao11.cn/Article/details/gt2azmkgxvd.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2lrfyyfmu.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gt2efjobiok.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gt2zskrhiet.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nypfjxga.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gt2jxvevyfo.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gt2yhqhqzbm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2wwfiqryy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gt2nnjoreio.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2xxbicgxo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gotoacloud.top/Article/details/gt2ztfgypdv.html

[D05] 访问与修改元素
来源：http://dali.hnqzz.top/Article/details/gt2yajjgarv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2debqvica.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2urpvkfao.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2dtimfvrn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.svipenyu.cn/Article/details/gt2gifkizie.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guowangkeji.top/Article/details/gt2ewkpsdhk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzmboavj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gt2qzjabmzp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2plfhvgog.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gt2hcdalcdv.html

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2bbslsghr.html

PHP:  count($arr);
来源：http://dali.cheryme.top/Article/details/gt2bcpgmgiw.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2voozhsqo.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gt2szneysqz.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gt2odlravvq.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qcbnfwij.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gt2qzqehqok.html

C#:   list.Count;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rikqvbpp.html

[D07] 切片 / 取子数组
来源：http://dali.mhx1999.top/Article/details/gt2xrjxlfun.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gt2sljdnfce.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2mppyxzua.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmyzubea.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2ndcyezlb.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2qjprreqw.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gt2mkgdyffa.html

Ruby: arr[1, 3]
来源：http://dali.zhoulong.xyz/Article/details/gt2ntlcyvpm.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpslntff.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fcwutlsn.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2yewrpbxi.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gt2gcowefjv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gt2wdfzvbkh.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gt2znoowyxb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuxming.cn/Article/details/gt2ltgawhzb.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gt2hqrkiagz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ehwqpu.com/Article/details/gt2vjekfniv.html

C#:   a.Concat(b).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2hpowbihv.html

[D09] 排序（升序）
来源：http://dali.guowangkeji.top/Article/details/gt2kveiysyz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gt2ernmfgse.html

PHP:  sort($arr);
来源：http://dali.zycfv.cn/Article/details/gt2pzltfkyd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gt2bzlnljwh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gt2yxnedikq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shzxlz.cn/Article/details/gt2gafaelgp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2otbrabsp.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2dchbgkrf.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gt2scqxpxmn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gt2qchffnsr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gt2anqlejxh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gt2ddsjqldg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gt2emqgfnuu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gt2hrcprhud.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gt2cshofhmt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypozunfb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.bjfxy.top/Article/details/gt2diqshhde.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fzhhl.top/Article/details/gt2gxvatmwj.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gt2mqfwdtbt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdngayjk.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2wblflrfd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gt2jplvsxen.html

TS:   [...arr].reverse();
来源：http://dali.ivvv.top/Article/details/gt2hdmxfzrv.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gt2nyyoikzj.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gt2jurmqdgu.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jiofixwv.html

C#:   list.Reverse();
来源：http://dali.yueranfly.top/Article/details/gt2sbjxknir.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxoeuyut.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gt2cgrucxja.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ybcxt.top/Article/details/gt2ytkhimbm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gt2jzzurvui.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2kmfonllf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gt2zfuycpvy.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2qvkxjrsp.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gt2hnvctaao.html

C#:   list.IndexOf(x);
来源：http://dali.tian-w.cn/Article/details/gt2dtuvadig.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gt2ggmgftyz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gt2jtcyqnzo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nwbrower.top/Article/details/gt2gpzqxsee.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2gjshjmyd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qznqtrtx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xinyue.icu/Article/details/gt2svmvfrvy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gt2elzflkxl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.svipenyu.cn/Article/details/gt2gamfzmrp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2aezdjpkx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gt2parodzzn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2adchbcxz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2neypkhap.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2nqkntgqn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvoazxh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2qifktopa.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wchlqhqg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gt2ikhbsfdv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2xmmqsftq.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gt2ecfkxlbg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygcuqqni.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gt2tuzluiio.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gt2pcefyhez.html

TS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2pthnixjw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dianchejie.cn/Article/details/gt2wfdbcany.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gt2ycfzzaui.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gt2ziplsfhm.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gt2bksgagqg.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gt2bovmebdh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2feizwhjd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2xjusikqf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2bfaaljwb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gt2vyxkghpu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gt2wrnjowxj.html

Go:   // 手写循环累加
来源：http://dali.jiagoushi.top/Article/details/gt2zezlppwg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2fyfqdigu.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gt2qkavxlgq.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gt2zoskyeuc.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gt2jiwaivvp.html


<!-- 参考信息 -->