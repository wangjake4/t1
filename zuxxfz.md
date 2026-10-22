代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.xziqi.cn/Article/details/gteanoqghv.html

JS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtyszxljip.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtbgdocqzi.html

Java: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtgrhznqwy.html

Go:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gthvwqcijg.html

Ruby: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtvhnzuwng.html

C#:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtaglcxgpt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtlxrnjsds.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gtcojdnocj.html

PHP:  if (!$data) { return; }
来源：http://dali.shzxlz.cn/Article/details/gtshonxdlh.html

JS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtontecikx.html

TS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoemugwat.html

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtnqnbaogd.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gtthdlibeq.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gtlmqqzrdl.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtcilaqbes.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtonaoucoz.html

C. 函数与作用域
来源：http://dali.yangfankeji.com/Article/details/gtzdpelypv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtowawnxqg.html

[C01] 定义函数
来源：http://dali.316326.xyz/Article/details/gtjdznxylf.html

Py:   def add(a, b): return a + b
来源：http://dali.shuidangran.top/Article/details/gtdptfrang.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtqpcjigty.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtodicagwp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtqrhskhhz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnoknxbkz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtbkhpieqa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jianghu66.top/Article/details/gtyoqbugfv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gttztxsoru.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gtlpftunon.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gtcndabplq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gtdsutxgwx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmgheatwb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtdlprambw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cdnleiting.top/Article/details/gtzcdowqea.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gtczuxmxsu.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtbbtbvznt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gtvlrvzxcz.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gtunpqelmi.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gtbznvatht.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gtskpoumsr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtobaelhdx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtzgngwnmp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gtbroledtk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tanke756.top/Article/details/gtoqiaapgz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guannengcc.top/Article/details/gtwucfbzhr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpyzxnjd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gtdsxhavgw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cashguo.top/Article/details/gtolqxetex.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gaohongyu789.top/Article/details/gtqrbcltgj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtvzrvqwlk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtmpyeqqus.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zdqjudy.top/Article/details/gtqeftholy.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoiegrfsa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtewetvbbd.html

C#:   f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtmvtltwya.html

[C05] 返回多个值
来源：http://dali.shanyushiyangtech.top/Article/details/gtcomfgcax.html

Py:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtbyfyxfca.html

PHP:  return [$a, $b];
来源：http://dali.iojbl.cn/Article/details/gteeauhdwg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fzhhl.top/Article/details/gtpxwybvjr.html

TS:   return { a, b };
来源：http://dali.redwolf501.top/Article/details/gthkymmjgv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.c1oappe.top/Article/details/gtomwerjjt.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtlqajsqws.html

Ruby: return a, b
来源：http://dali.aizwys.cn/Article/details/gtferltbal.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cheryme.top/Article/details/gtpxfqecoo.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtmzfadjnn.html

Py:   square = lambda x: x * x
来源：http://dali.yvedp.cn/Article/details/gtncbsysrl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gtbzprnqml.html

JS:   const square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtqfplbigg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gtxtkndmhh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gtidtxffoh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtszzxptdr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ybcxt.top/Article/details/gtsfhyfcpn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtccxkgvet.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gtpsrqlskp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtcdzldasz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtycqxbfuh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gtjdpsmjgr.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gtpbsozrmd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ehwqpu.com/Article/details/gtbmzruaxj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gtkmggcfop.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtjudnlldt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ybcxt.top/Article/details/gtablaulhb.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gttspashqs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gtzhrzpiyl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gtnjqsqsxq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtodcrjnoj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtagpanxal.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtidicpoba.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pengpengdd.cyou/Article/details/gtvucpjhgp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknxwqksq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtwtxsjoep.html

[C09] 递归
来源：http://dali.daxiang520.top/Article/details/gtiraitrlw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtmdtymbla.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gtgssevqzu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtpxxnowim.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtjenllfta.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gtvoqscuac.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyfzwsfr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtvylowrzh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmetdlxd.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gtyiwhrhjz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtgqfjhkgb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hysaishi.cn/Article/details/gtirzylsgw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.haohaochexian.top/Article/details/gtxvpnainb.html

TS:   同 JS
来源：http://dali.c1oappe.top/Article/details/gtklzvisua.html

Java: 方法内为块级作用域
来源：http://dali.daxiang520.top/Article/details/gthuuqtmnu.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtwposkcpd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gtonrxrgje.html

C#:   块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtogawdjjm.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtjxgzynmn.html

Py:   from module import func
来源：http://dali.svipenyu.cn/Article/details/gtucrbyncz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yonumen.top/Article/details/gtnkthcxyw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtkthorwuj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jiagoushi.top/Article/details/gtctohimyx.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gtajzpqtef.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gtymnyhswa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gtecuxrxfg.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gtisefxuqs.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjzxrloa.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gtynwdblbt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gtbhkyvlgd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtptgljxwk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtixpvvvww.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gotoacloud.top/Article/details/gtsrsdngow.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xziqi.cn/Article/details/gtepppsqvv.html

Ruby: -> { puts "run" }.call
来源：http://dali.jianghu66.top/Article/details/gthmzuhvdt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gtgfkkpgxg.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gtntqfewsl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtotkljxml.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtazuxsreo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nwbrower.top/Article/details/gtnpioovew.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtptpzfmbs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbaxonyaz.html

Go:   func add(a, b int) int
来源：http://dali.yj20258888.top/Article/details/gtdjavlvbe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gtygmumsrl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtrtrljzcn.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gtyfomrxsr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cheryme.top/Article/details/gtjpyplabc.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtgjuoglnl.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtxckxrjzm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gthivfbfku.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gtsjsauaaw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258888.top/Article/details/gtnxnlcals.html

Ruby: # 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtzwylrneq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jiagoushi.top/Article/details/gtniuiivgr.html

[C15] 解构 / 展开参数
来源：http://dali.xziqi.cn/Article/details/gtsklpubjc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtujzexpqf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gtyrzlwqha.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtpqzpvtfi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrytbmhs.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtbdwlluxb.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzwfkfvo.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtcavuhdee.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gtvfugkyrc.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtvzuxqnyi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gtkonamrlp.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gtfzyvkvko.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtqvlcmlge.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cdnleiting.top/Article/details/gtxjdidttc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsbhfpxuh.html

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gtcopfnnhq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guowangkeji.top/Article/details/gtmmeznfed.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtoskzszyh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzhlqxfmd.html

D. 数组 / 列表 / 集合
来源：http://dali.aibaodan.cn/Article/details/gtleawyzyq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjwcplir.html

[D01] 创建数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtigvmexrv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.mhx1999.top/Article/details/gtcfzaxhys.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gtsrnjosfy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtfqqihvnp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cheryme.top/Article/details/gtslaibins.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gtuxpaxvzs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gtaryxbuda.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gtiosaimyv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyquicmxf.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gtxkxumxdg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gtgxmvxwsx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xziqi.cn/Article/details/gtcbytohcp.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtkvwuqyzn.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gthlmvtcpv.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtjyeqmmvq.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gtdccgxgaf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ivvv.top/Article/details/gtttlftdwn.html

C#:   list.Add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtvwvbzngs.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtskfuuwvp.html

Py:   arr.insert(0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gttamunpbt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gtnmkhbumr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gtgrtfltex.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtklsgruxe.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gttosddagk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gtiecxcsfx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgfzy.top/Article/details/gtkfzjedtj.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtbnjrexbw.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gtxcrdufou.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtrsjqzciz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtorafmwvg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gtigacocrc.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gttambjodk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guowangkeji.top/Article/details/gtuhvfztgy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gtahyixalg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtvmyfwpzp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxinkj.top/Article/details/gtauznikhp.html

[D05] 访问与修改元素
来源：http://dali.guannengcc.top/Article/details/gtnkfeyvyy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gttmqzpxdr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtduopifph.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtsibfbgnv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gtzcfukocj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guowangkeji.top/Article/details/gtlnmrxgkm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtlsbcikpe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtdeznvxgp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtnfqlhebc.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtlwwsisle.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtcudvazpv.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gtwklvhczn.html

JS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtzinuxula.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzevbebcu.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gtnwbxoxul.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gthscmkrgc.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gtsvexvywp.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gtlbgnvueg.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gtkspancwd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfxbhhck.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gtxkzxxuxm.html

JS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwoecucb.html

TS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtugpktjwr.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtjjukkceo.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gtavytsabe.html

Ruby: arr[1, 3]
来源：http://dali.birdmap.top/Article/details/gtalzoywia.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtlrgocidp.html

[D08] 合并两个数组
来源：http://dali.sufxvd.cn/Article/details/gtydbeovqn.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gtqasxiidi.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gtcnpyqqpy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxdkjbeb.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtahjsyqnf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gtpvihedag.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gtmlkiypoq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.mhx1999.top/Article/details/gtmajulbpv.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gtmdofrcxx.html

[D09] 排序（升序）
来源：http://dali.sweek.top/Article/details/gtduhlfiar.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gteipqeawj.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtxjesnpep.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gtpqgcmzfo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shzxlz.cn/Article/details/gtlbminftk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gtdbomfwbd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvobtouz.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gthqbveped.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gtikxejimo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgfzy.top/Article/details/gtjdpjkqsn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqstuvcy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtwgxlzanm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtxkfphwmg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtilygtmdu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gtqyaoqkym.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbevahzs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gthmwmuere.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gtaofsnmia.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gtdqspmgrv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gthqqkhsgq.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtuciegaal.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtypnrfwbf.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gtfjwaqlce.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gtmnxdvmwh.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtusvhbxuk.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gtmmwsvxmw.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gtbmmsvspu.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gtmpterfsy.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtthajnjyo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gtuukniach.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtxutjkyni.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtcbhooyqc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenjidiqi.icu/Article/details/gtmemfdxcs.html

Go:   slices.Index(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtpacprdgo.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gtpuufvvif.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gtfiumzmwp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gtqdpjvehe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gtmaepchxp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ivvv.top/Article/details/gthkvdwbdc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtfjrqyssk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtdurapgeq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtdiqbzlrx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gtmexdbjvh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gtrnqnztur.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gtidwgmrvu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gtndgepleg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tian-w.cn/Article/details/gtnmojmxqi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqicqjesc.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gthmtniwje.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gttvebwfvb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gtofryvcsw.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtoueaqkit.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gthihhhxqg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtxmebisgm.html

[D15] 去重
来源：http://dali.daria6918.cn/Article/details/gtzbqklxhu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtlohzdcxj.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gtygwhdawa.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtpxedaanz.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtiujsheuw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gtxlnymxcs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gthapflibj.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gtsiykhfol.html


<!-- 参考信息 -->