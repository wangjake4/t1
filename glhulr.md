代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gt2hkogpvzv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzernovy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2owzokggz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2tkewacwj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2tuhnfzja.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwgtxrkz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.andypj.xyz/Article/details/gt2nzqmxivj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2hvemdhyg.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gt2cknvoqut.html

Py:   def greet(name="World"): return name
来源：http://dali.zhoulong.xyz/Article/details/gt2jngnnirh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qeqcuqza.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2grlbtydc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukxpqptb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sweek.top/Article/details/gt2tzqwqina.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xinyue.icu/Article/details/gt2ereorduw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zdqjudy.top/Article/details/gt2brfoleok.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gt2nvympovi.html

[C03] 可变参数
来源：http://dali.yj202588.top/Article/details/gt2sujbrlco.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gt2qvpeioxr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gt2bhsbylfq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gt2bzpnayur.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gt2jqazewqe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfazybbe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gt2uosbrmvp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.vqdsnc.cn/Article/details/gt2jpowfvkp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.0kj1m.cn/Article/details/gt2hhqdyvyo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ybcxt.top/Article/details/gt2fmcwicro.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gt2vihjlypb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fzhhl.top/Article/details/gt2zsubvflo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gt2tajbawhh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shzxlz.cn/Article/details/gt2qjobahrt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gt2pthjrnla.html

Go:   // 无：用配置结构体参数
来源：http://dali.daxiang520.top/Article/details/gt2kvwrnnne.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gt2fhxitfcp.html

C#:   f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gt2rbmefuhy.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gt2zcmlrqww.html

Py:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gt2expdhefk.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gt2jjnfcohl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.redwolf501.top/Article/details/gt2gudwrqbz.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2bfoqzvvj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhengqikj.top/Article/details/gt2vpmrteag.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2ylykxnuj.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gt2gugmfqpa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gt2avnrzaub.html

[C06] 匿名函数 / lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hddjpzsn.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtpajagi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.vqdsnc.cn/Article/details/gt2pswzuyee.html

JS:   const square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2qpguyfoh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2runqnfnh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ybcxt.top/Article/details/gt2gfxljoii.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvcmayca.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbljqmyx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2jkabazgf.html

[C07] 把函数作为参数传入
来源：http://dali.gogol.net.cn/Article/details/gt2niqnvazm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.9152youxi.cn/Article/details/gt2jvpptphl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2pdtibvoa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sufxvd.cn/Article/details/gt2kwgvybfu.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gt2ydegaxsz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2vrfcmlea.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gt2piniopme.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gt2wuntdbip.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gt2btmsvaaw.html

[C08] 闭包
来源：http://dali.jinqigfzy.top/Article/details/gt2jmktetru.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gotoacloud.top/Article/details/gt2vhsjuapf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gt2mikmoezc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2dakuwchl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2fpffhkzx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gt2rajqwftk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zycfv.cn/Article/details/gt2qkplrbur.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxinkj.top/Article/details/gt2lxkpjreq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2recxcszl.html

[C09] 递归
来源：http://dali.dianchejie.cn/Article/details/gt2roujysru.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gt2oopznruc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2stcmzvgk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2dkufiaik.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqkiajmo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gt2uzpxrian.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gt2vzldywsb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gt2sorqwpdp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cashguo.top/Article/details/gt2wzjpehqn.html

[C10] 变量作用域
来源：http://dali.ybcxt.top/Article/details/gt2csloertj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ehwqpu.com/Article/details/gt2axprsgjx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cucudq.cn/Article/details/gt2bsdddzsx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xylfe.cn/Article/details/gt2uvjqizjf.html

TS:   同 JS
来源：http://dali.c1oappe.top/Article/details/gt2bowqizpa.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gt2nvoxgmtn.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2zrpzplbd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imopqgke.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2bpnivjuh.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gt2rduozwoe.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gt2fervlrbf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhphovin.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258.top/Article/details/gt2brrfrtzl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gt2dvzrkspn.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gt2ggypfhug.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gt2cmdhyuob.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gt2nnvohghb.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gt2jrytfjol.html

[C12] 立即执行函数 IIFE
来源：http://dali.sysykeji.top/Article/details/gt2lknyqbux.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gt2repbngxv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrmykmbr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gt2osmilckg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gt2vqzieoni.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gt2oeqwdwfw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gt2xsebwhlj.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gt2zftzvhie.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gt2hsfudrtq.html

[C13] 类型声明 / 类型注解
来源：http://dali.fengsongda.top/Article/details/gt2eunkblpb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xziqi.cn/Article/details/gt2vitpvykh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2typiucjy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.0kj1m.cn/Article/details/gt2ohpjbiav.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2ddlpkwfc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2jfawcscu.html

Go:   func add(a, b int) int
来源：http://dali.jinqigfzy.top/Article/details/gt2hkripwnn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigfzy.top/Article/details/gt2zkcdrymw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gt2qtvunfbz.html

[C14] 泛型函数
来源：http://dali.daxiang520.top/Article/details/gt2loojsbuh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenjidiqi.icu/Article/details/gt2aeoxvryd.html

PHP:  // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2qeajwjiu.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gt2ugdjitzr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kbnhnnst.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2hsfxxsro.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gt2zjfexbbv.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2wnnwbggc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gt2mlbausug.html

[C15] 解构 / 展开参数
来源：http://dali.yvedp.cn/Article/details/gt2yiqbiaga.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gt2mxzyoxkq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nwbrower.top/Article/details/gt2hhxaciej.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2mkoxdopm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2xmnxlkxi.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gt2hcqzhwde.html

Go:   // 无解构
来源：http://dali.tianlin.xyz/Article/details/gt2ahurlauz.html

Ruby: a, b = pair
来源：http://dali.hnqzz.top/Article/details/gt2qdnymsri.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gt2maoggujp.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gt2awzgzyxz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gt2hdpfvynj.html

PHP:  // 无重载
来源：http://dali.tanke756.top/Article/details/gt2sjvqntqo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gt2jwcqisep.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj202588.top/Article/details/gt2ivtblviz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gt2iulxufya.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenzaomai.com/Article/details/gt2fyafrbae.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gt2wostfejx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xinyue.icu/Article/details/gt2vuhhcvzh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oeqsbjzt.html

D. 数组 / 列表 / 集合
来源：http://dali.cucudq.cn/Article/details/gt2qyyygnfc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2sfomkerw.html

[D01] 创建数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gt2mkkmhqfn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gt2ympmwvnr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sufxvd.cn/Article/details/gt2blwecdvy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gt2wdbdpfqw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gt2vpuqwzab.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gt2nkjjkofb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gt2oxpuyfdo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gt2nyoeqyfq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gt2nfuujrkd.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gt2bpvelrjx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gt2gcvokmyo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2ieoxcwrv.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gt2hequyepe.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gt2dubnjyug.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxhkllbq.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2rdmudfvd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2piftcwye.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gt2spdonmyx.html

[D03] 在指定位置插入元素
来源：http://dali.xinyue.icu/Article/details/gt2hgypbeqy.html

Py:   arr.insert(0, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2xvftdrsc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gt2bevejlgw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gt2slhcnilr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2aaziaowk.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2bferrbgj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gt2xdfjkdbt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gt2xtcktgba.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2rhrymrax.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gt2flpssxiw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gt2lnuzlezj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gzhubu.top/Article/details/gt2pbtqpkap.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gt2gyrevied.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gt2ofzqqrtd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gt2oyexeptv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zdqjudy.top/Article/details/gt2cgkcvmtt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gt2dtkqifdl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigufen.top/Article/details/gt2kfyyypsj.html

[D05] 访问与修改元素
来源：http://dali.yongpay.top/Article/details/gt2tcjjtlxv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gt2egbxhqgz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyhindwj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2pytlzhyf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gt2ldywqjqk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zdqjudy.top/Article/details/gt2myqkcehp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gt2fzkegeel.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2qyjgfybn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwhreuxz.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gt2ybkgmaps.html

Py:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gt2utfceyih.html

PHP:  count($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2viifixhs.html

JS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2akibrlpa.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvuauyst.html

Java: list.size();
来源：http://dali.wangdashe.top/Article/details/gt2orjoxxzf.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2qvpdiqvv.html

Ruby: arr.length; arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsbswfoz.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsdavbxc.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gt2rbcfyzwz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xckdlizq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2mbxxtklf.html

JS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gt2cdokfsxb.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2goqyniqh.html

Java: list.subList(1, 4);
来源：http://dali.zycfv.cn/Article/details/gt2zvcovipt.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gt2huvszzen.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gt2rxzhciic.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gt2ibrqikzv.html

[D08] 合并两个数组
来源：http://dali.daria6918.cn/Article/details/gt2ddltjdtw.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gt2gokllpzm.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gt2xsxopoiw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gt2hpjhiygu.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gt2ilggqqel.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2cnovmnyr.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gt2sqddctou.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gt2hvuxfwst.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gt2zkwkslmh.html

[D09] 排序（升序）
来源：http://dali.0kj1m.cn/Article/details/gt2jhwwzuuw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhtaqveo.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gt2jlvdcnwx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gt2hfslnofz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jyoumei.cn/Article/details/gt2rthfhkcj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gt2swuycaij.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2ezjpxhut.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gt2wtbilcgs.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gt2lguybyyz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jyoumei.cn/Article/details/gt2maxbbzvk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gt2skqvkkhc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gt2hnjcjntj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gt2ueybljki.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2ufuwzozz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gt2bukyrggc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gt2ifkvkzgv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gt2ntaggcju.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.kuanghao11.cn/Article/details/gt2bzrqpoxm.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gt2nilxmabm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yanxiufei.cn/Article/details/gt2yktzcmvy.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmbcysbj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gt2wjlhxghd.html

TS:   [...arr].reverse();
来源：http://dali.nanxuanxn.top/Article/details/gt2uifpapdx.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2hrkstyvs.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gt2gmrcogjc.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gt2tztzcdss.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gt2viyzwbqf.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gt2hsbdtxwd.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2oyvobaxi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gt2hmyranlk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gt2svoscsul.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oncgajsx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gt2tklvymgk.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2wkdudock.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gt2hbufprwt.html

C#:   list.IndexOf(x);
来源：http://dali.jqgfzy.top/Article/details/gt2mmwrogge.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gt2hspnvbdr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gt2bewyxmpz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fygtlved.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cucvtzyh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2ipfttaqq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2cvfivdtq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gt2hofhtgvn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jyoumei.cn/Article/details/gt2kvzqrxpf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tanke756.top/Article/details/gt2jbaepvmi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gt2enqxprgq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2eqjikrrw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2svrmwwum.html

JS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gt2rcwzwpcx.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhqgncu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2ngusaftp.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gt2ljycgser.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2vlfmnwky.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2pdomepvt.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2fcxwkmso.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gt2afjxdowi.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gt2xlgmdkie.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2vlghonio.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkhbasys.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gt2hxoswttw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gt2fsiosznt.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gt2jzhixvol.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gt2hkxihwds.html

[D16] 求和与平均值
来源：http://dali.nanxuanxn.top/Article/details/gt2tnwogjxx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2wugufpiv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2ojavnfsj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gt2apvkozgw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gt2ltuyijjj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sxryk.cn/Article/details/gt2vaevspvw.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gt2bposocka.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gt2wsewtsfu.html

C#:   list.Sum();  list.Average()
来源：http://dali.dashuyun.cn/Article/details/gt2yaivdsxk.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gt2vrdvtagk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2pbvidciq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2gtxsegxl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.redwolf501.top/Article/details/gt2bloglhwt.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gt2vuziudvw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gt2rqdmleqb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcmpfzdb.html

Ruby: arr.max;  arr.min
来源：http://dali.shzxlz.cn/Article/details/gt2ivqqlnmi.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbulnnad.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gt2wdpawqdm.html


<!-- 参考信息 -->