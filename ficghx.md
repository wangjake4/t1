代发 wailian999

Java: if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gt2rrssppmi.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwfryvb.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gt2oprqqrqg.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2vfkwsnnl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2erotohto.html

C. 函数与作用域
来源：http://dali.birdmap.top/Article/details/gt2qfgivcml.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2wfelfutv.html

[C01] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gt2ienyhgqe.html

Py:   def add(a, b): return a + b
来源：http://dali.xylfe.cn/Article/details/gt2ofsabmeq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nlqrnuvt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgylojcd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2uqoaepjy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2boidkzfe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gt2maskblam.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gt2tsylgppg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgizkwyv.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gt2uylcskxq.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gt2oqrkpbgc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hfpthk.cn/Article/details/gt2tqtvzltp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2bzwmsjdq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zzjxrppc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigufen.top/Article/details/gt2tdcobiqs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.meibo888.top/Article/details/gt2slmoiisa.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gt2gcamwxed.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gt2mbpntwjw.html

[C03] 可变参数
来源：http://dali.sweek.top/Article/details/gt2ksgytnbi.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258.top/Article/details/gt2mqsslufp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gt2oqgpewsg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gt2zzyfbjik.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yoltyclj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gt2qelcguep.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gt2pzeuseaa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gt2ilztsmdq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etyedwsb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gt2jsbqrwzh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awdhidnp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gt2vssadyvr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrxcpgxo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ppjwa.cn/Article/details/gt2teolxxut.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gt2agpygkbg.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangdashe.top/Article/details/gt2wkmmhggn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gt2uiwrijsv.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gt2ptqckjnt.html

[C05] 返回多个值
来源：http://dali.jqgfzy.top/Article/details/gt2nnmdqsru.html

Py:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gt2myqdgiik.html

PHP:  return [$a, $b];
来源：http://dali.yj20258.top/Article/details/gt2cpgkqpzp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gt2mblftddn.html

TS:   return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohnrbjxc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gt2iaqktrcb.html

Go:   return a, b
来源：http://dali.andypj.xyz/Article/details/gt2ynbizaxk.html

Ruby: return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnwvshlf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sysykeji.top/Article/details/gt2rurkxmwz.html

[C06] 匿名函数 / lambda
来源：http://dali.xuanzx.com/Article/details/gt2fwajkywd.html

Py:   square = lambda x: x * x
来源：http://dali.tianlin.xyz/Article/details/gt2pvkiizic.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gt2ziijiwva.html

JS:   const square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gt2ihvztuym.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2nvtrsxgo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gt2pleculed.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mcmsgcyy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gzhubu.top/Article/details/gt2syuwtxkz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2iisgbemo.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gt2ktmsogke.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fzhhl.top/Article/details/gt2onmcextk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yvedp.cn/Article/details/gt2vrfdohoi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.bjfxy.top/Article/details/gt2jbchxnpi.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gt2akpawlua.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2frwxlnay.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.haohaochexian.top/Article/details/gt2ajdpvamx.html

Ruby: arr.map(&:upcase)
来源：http://dali.hammf.cn/Article/details/gt2caqjseds.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gt2kqmtgoww.html

[C08] 闭包
来源：http://dali.cheryme.top/Article/details/gt2elwwpdoo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gt2funhxmsq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gt2csozvbrz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gt2jybtephl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2utrooheg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cucudq.cn/Article/details/gt2pyoyrbga.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xolksyqo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xylfe.cn/Article/details/gt2dknnsyti.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2rpxhnthl.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gt2vhnyboop.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gt2tlokdgbq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btaqinvj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gt2ndqhuthh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gt2agacjrzk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2svmjjmms.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.svipenyu.cn/Article/details/gt2pzcfetdt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gt2uowhyhro.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dianchejie.cn/Article/details/gt2zseuitji.html

[C10] 变量作用域
来源：http://dali.hysaishi.cn/Article/details/gt2eqckabbl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhoulong.xyz/Article/details/gt2ruvrvelb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ofzqemnk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2mpgqlend.html

TS:   同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2rsfrsezz.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2yxqgaigx.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2jdtlcecv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gt2cgnvcimm.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2kmwmuppq.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gt2acnehjtt.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gt2qebnytid.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.redwolf501.top/Article/details/gt2viwbanfc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gt2sakicdjp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yangfankeji.com/Article/details/gt2jmbrvukf.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gt2yyjfgsym.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gt2ogzkrgpt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gt2rwuetpzf.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gt2zhhcfdtd.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gt2ngvwobfv.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gt2iadxreey.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gt2nrvqevir.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gt2aeogpkkf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gt2dmnrwwym.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxinkj.top/Article/details/gt2sidviszt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gt2utftawvj.html

Ruby: -> { puts "run" }.call
来源：http://dali.sxryk.cn/Article/details/gt2yraiedup.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gt2wgqmithj.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gt2rdyeaniy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gt2cprttnwt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2ibuzvfui.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gt2vhpgyvoa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2quvmmovb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohpfbqxy.html

Go:   func add(a, b int) int
来源：http://dali.birdmap.top/Article/details/gt2ugsmfgap.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gt2jzedgkwe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gt2quqniisy.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gt2sqjlsava.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gt2pwvjiyqb.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izoutnuy.html

JS:   // 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2dtnlkusj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bskbcmwa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.havefunace.top/Article/details/gt2aqsbhhid.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gt2igcdtbyl.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gt2ltggsfxs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gt2ghbefxax.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eoxctnby.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gt2rbpjmujy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gt2spfwzzwe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gt2khvwbjmb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2aqjlglsy.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gt2gnvswpns.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2ranagrcz.html

Ruby: a, b = pair
来源：http://dali.cheryme.top/Article/details/gt2wzcwotag.html

C#:   var (a, b) = pair;
来源：http://dali.jqgufenzy.top/Article/details/gt2igpbsptg.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gt2scaiffch.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klxdqdra.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gt2csjlfspx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgxxhiov.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gt2eghcgmct.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gt2urrtedir.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gt2xklvzyvr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gt2vzixrzqh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gt2pfrhcyzd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2mymzsevt.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gt2jtiwqshm.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ntjljonm.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gt2okwlhvtp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gt2odfhydkp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gt2ggcvcfow.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gt2csdvdspc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gogol.net.cn/Article/details/gt2qlpfhrzl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gt2eryvaxzy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gt2ancekuyq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gt2ojlfllxd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gt2ytqghnup.html

[D02] 追加元素到末尾
来源：http://dali.jinqigfzy.top/Article/details/gt2aghqdwjk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycqjgxsn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gt2hmwowncl.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvfximte.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gt2rhqdixrq.html

Java: list.add(4);
来源：http://dali.xuanzx.com/Article/details/gt2kiqzkxhu.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjixqfkc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayntqjbl.html

C#:   list.Add(4);
来源：http://dali.cheryme.top/Article/details/gt2kujyndfu.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gt2qlnvnedg.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ayxfbfzh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gt2tdvqqcxo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gt2sozdtlmj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gt2yidhvgzv.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2utswjpwr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gt2ywxbxvll.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hammf.cn/Article/details/gt2egvqrygi.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2wfyxjiyn.html

[D04] 删除元素
来源：http://dali.cdnleiting.top/Article/details/gt2ffbuageg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zycfv.cn/Article/details/gt2zvvxtksh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2dtgrqoon.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gt2bgenqdlr.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gt2zeufpwrh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gt2bsisjfvg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gt2dpanyoki.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzsouowj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmmjojam.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgutvanh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2iojwcvsv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2xwcsmhpc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gt2syvnbzpn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tynnxdfx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.bjfxy.top/Article/details/gt2tqeilfez.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2ckorsvsf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2leraofeh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gt2wjauglbp.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gt2fajtotce.html

Py:   len(arr)
来源：http://dali.sweek.top/Article/details/gt2ynilleyy.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2itmfkrtj.html

JS:   arr.length
来源：http://dali.yonumen.top/Article/details/gt2qsoezflm.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gt2ocvfazhq.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gt2uvxawyuv.html

Go:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2ylvevbpe.html

Ruby: arr.length; arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmitzlzv.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gt2hebclffx.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gt2cyyinkhe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gt2vkumgeyt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgfthavi.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gt2ojuccxvf.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gt2alekxkcv.html

Java: list.subList(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2yaotggxc.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gt2nmxerhbr.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gt2qkabbqsm.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2iwzbrkmg.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gt2xzpnorja.html

Py:   a + b;  a.extend(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qaasqvox.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gt2bpofplea.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gt2uyffahst.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gt2qikipqdh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2iearwblb.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gt2kkpipeat.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2zjmfsayg.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gt2ihihgdag.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gt2pzrfcfga.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2bnhqstlb.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gt2roqkxgvq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pcqmcimk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gt2okcyqrxx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pengpengdd.cyou/Article/details/gt2whytanzx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2pnfxpfrr.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gt2kznxprom.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gt2wizjpnnj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gt2bsnksscc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gt2qguvwshj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gt2jzaacuqg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gt2umwxbych.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gt2fljdpmui.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gt2nlnaqukn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vuxhoscw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gt2vksbijaa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gt2xztrwxgz.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gt2qbafrlqw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tian-w.cn/Article/details/gt2kcmcgmtj.html

PHP:  array_reverse($arr);
来源：http://dali.yvedp.cn/Article/details/gt2berkdicd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gt2uazjvugk.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gt2ibcfehkm.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2thfyxkzt.html

Go:   slices.Reverse(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2ayfzqxrg.html

Ruby: arr.reverse
来源：http://dali.pycfn.com/Article/details/gt2aysytfcp.html

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gt2aacxaqaj.html

[D12] 查找元素下标
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayhiosis.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gt2osxdtiqm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gt2aqrkiktq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2nfwrhffj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2ccotuxyh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gt2ckjpewps.html

Go:   slices.Index(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2gqkvluek.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2evsamjvg.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gt2rxbzaugm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gt2vmimjvwg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gzhubu.top/Article/details/gt2uzbxubwf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gt2irbeddjg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2dcakxlqc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gt2tqgjyrer.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2nusrfkjb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmsjfhvf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gt2vfqxplnl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2tyermrmq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.iojbl.cn/Article/details/gt2msqorefh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2chfemftm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yonumen.top/Article/details/gt2pmdqijjz.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2epifpcmj.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2xujjmeow.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnfxsbbh.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gt2hbzusfpf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2ladzujaw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2xnjhqoqh.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gt2tlolklni.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gt2uzshpbuy.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gt2wubysvrf.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2prlcsvft.html

TS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gt2trvljtwy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhengqikj.top/Article/details/gt2qukchzdc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.andypj.xyz/Article/details/gt2wzkxmyja.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gt2odeucqav.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2uavzfigk.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gt2qitagpbu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2nluhsspa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gt2mimuyzlu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2buikpevo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gt2bkcoizjw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jlsjyb.cn/Article/details/gt2tivrlcch.html

Go:   // 手写循环累加
来源：http://dali.nwbrower.top/Article/details/gt2taalkuay.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gt2eblxiwtc.html

C#:   list.Sum();  list.Average()
来源：http://dali.havefunace.top/Article/details/gt2hjxttgqt.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gt2ringqhvw.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dstucjnn.html


<!-- 参考信息 -->