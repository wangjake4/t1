代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gttfrxtuao.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtovxyrjdx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtupwfbdpw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtupcpcova.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtmjjfvvoi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gtmrfjpejw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gtenjqccwy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtqexousfn.html

[C02] 默认参数
来源：http://dali.yj20258.top/Article/details/gtafmhatir.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gtdalitoib.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gtlltlmzpl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtetitbxrp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtdnzdgets.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gzhubu.top/Article/details/gtyhgwrjxv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gtghiavhzp.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gtxwxtotvx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gtlkrljxcy.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbinglgb.html

Py:   def total(*args): return sum(args)
来源：http://dali.hfpthk.cn/Article/details/gtzuieywea.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigfzy.top/Article/details/gtfyugcqrj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gtxqtqsnfg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmddpagvs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gttbocbzxa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shuidangran.top/Article/details/gtaxksjsdl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gthuqbixbe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gtjemfihaw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gtslrocztu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.quarkkingdee.top/Article/details/gtnswvscmg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvxceyvw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaagehla.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtutjhkxly.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gotoacloud.top/Article/details/gtlrpevnzo.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258888.top/Article/details/gtemcaiaqv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtxbprfawg.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtudzgdwir.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gtdjntxcet.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gtjamkpwzc.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gtebytcknt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gtsasofskh.html

TS:   return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtlczisrzg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gtdqsvmtof.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gttjtjhogz.html

Ruby: return a, b
来源：http://dali.jianghu66.top/Article/details/gttvidnuus.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxuanxn.top/Article/details/gtztoothky.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtxdhnjesm.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gtfvcyfbzz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gtswfsvwuc.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtjeujmcsg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtosbrkgzt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtumdmizsa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhongyouzk.top/Article/details/gttuorcdzo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gtytelijgw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtznsmiabw.html

[C07] 把函数作为参数传入
来源：http://dali.xylfe.cn/Article/details/gtgvefarer.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gtywvifieh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqfdslrq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gtkpzxoroc.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gthllskzdj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shzxlz.cn/Article/details/gtbkasdljv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gtqoxyqjex.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gtmuavzvtr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkugdtice.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gtmzfuubsf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gtuopmmbya.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenzaomai.com/Article/details/gtmcheehkv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtsvnorkls.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtzjjkobzw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gtumkidimm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenzaomai.com/Article/details/gtkbzvvxhu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gtffhmmddk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivzdctjl.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gtbkeawvuu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtvadvhoac.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gttadscsya.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gtonqqkkhw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtucqxbxpj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtmgnaybaa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gtzdduhfmm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtbmonkkgi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gtlwpxvenj.html

[C10] 变量作用域
来源：http://dali.kuanghao11.cn/Article/details/gttrtkzljt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.haohaochexian.top/Article/details/gtrxmaewgz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hongshengwenyu.top/Article/details/gtjvexttpv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.0kj1m.cn/Article/details/gtaemkcbgb.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gtzmyiuued.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtcgeuyjmd.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gtcckstkfu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gtgvmvspdg.html

C#:   块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtjlxrnhkr.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gtorbgezzr.html

Py:   from module import func
来源：http://dali.zycfv.cn/Article/details/gtqvuxffib.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gtxocddapo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtzkyuzdta.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gtmcvjuodi.html

Java: import java.util.List;
来源：http://dali.chenjidiqi.icu/Article/details/gtpmaobdfv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gthqzbftbk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gtvlekqlvn.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gtrydmmlzo.html

[C12] 立即执行函数 IIFE
来源：http://dali.daxiang520.top/Article/details/gthqahhymq.html

Py:   (lambda: print("run"))()
来源：http://dali.tanke756.top/Article/details/gtsrcxlmvl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgfzy.top/Article/details/gtululetrn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gtbaznmufy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtsguzzedm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gtnivpboak.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenlongwang.top/Article/details/gtfzoixrtw.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtxwpwyghy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.9152youxi.cn/Article/details/gthwqbevxz.html

[C13] 类型声明 / 类型注解
来源：http://dali.dashuyun.cn/Article/details/gtpnvuochl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtpiouzexa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtmxakxoga.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gtmbpesloz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtgvtvlyrj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtbyqwqztb.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjlnhkzl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj202588.top/Article/details/gtxkizmlrg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gtesxoxsgq.html

[C14] 泛型函数
来源：http://dali.hongshengwenyu.top/Article/details/gtcxoseykr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gtcdllouwb.html

PHP:  // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtewvmpkhy.html

JS:   // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtcrshrhgv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gtvbuggwku.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gtinzjqyel.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yonumen.top/Article/details/gtezenirem.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtfeuhasqi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gtxvrtdqoe.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtlvbbsncx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gtmdblzeds.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gtnyotiffv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtxiyyksxo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.redwolf501.top/Article/details/gthzbjgfdn.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gtaswkthek.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gtcfomwqld.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gtrzarjgjk.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykrmqbha.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gtdzyyoeio.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gtgzyrqaam.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gtwmsovujh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gttpyfztoo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gtbamofegy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gtdzeazahj.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gtiwncgcro.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gtazuydojl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gtgtwxgmyo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtcmvquggn.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtoqtmjrdj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwtrfxilf.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtsaoetbra.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnuvvrix.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gtkzruxsyw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gtqzbwnhbg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gzhubu.top/Article/details/gtdhohwvbh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gtntxncxru.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtlgccfoiw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtvdzrlxud.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.smart0.xyz/Article/details/gtxpgvqrpg.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gtluekzeae.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gtictjzmjs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnqzz.top/Article/details/gtbtxgtfkv.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtqdudyygz.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gteepbzhff.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtkbjsuiaz.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gtetbwrhae.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gtaoadcadd.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtjzcjvaus.html

[D03] 在指定位置插入元素
来源：http://dali.0kj1m.cn/Article/details/gtkiyhfiqw.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gtxblcognp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gtrhrnrdei.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gtksovlulk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gogol.net.cn/Article/details/gterthybwc.html

Java: list.add(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtuyyolxbo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenlongwang.top/Article/details/gtdxnellgu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.kuanghao11.cn/Article/details/gtuxkvlqxu.html

C#:   list.Insert(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtqesnkyoa.html

[D04] 删除元素
来源：http://dali.sweek.top/Article/details/gtwwuxtsqo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yongpay.top/Article/details/gtqxjyexeb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenzaomai.com/Article/details/gtjhitxtbc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.kuanghao11.cn/Article/details/gtmnmedmbe.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gtjurweihc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gtdsioibcs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenzaomai.com/Article/details/gtebbkpnuh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gtgckvanib.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtaorkoess.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gtunkfzpbp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtejywghql.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtutbwscpo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtoadgkzvn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtzfsaitom.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gzhubu.top/Article/details/gtjinhwine.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gttpstaget.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtehujhgqc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtfftduwwo.html

[D06] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtvzynzcfq.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtaahoykmk.html

PHP:  count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtrvokrdvk.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtqqhtozln.html

TS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtwxubojvy.html

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gtgdpfvgwq.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtomsevgrw.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gtdycxquzh.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtyeggwvol.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gtzwucycel.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtfearpbtc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gtcimqmxbd.html

JS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtmbpscojk.html

TS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtwrmbvmxw.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtjnwrfoci.html

Go:   arr[1:4]
来源：http://dali.zhixingplan.top/Article/details/gtekgyylyv.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gtkhixmath.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtmtudinbc.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gtkqyxdsqm.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gteuiqnzzc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gtchhaycos.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gtxhlcsvzc.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gtakpynvvs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zdqjudy.top/Article/details/gtjwjruqfi.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gtbhxrvbvj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gtsdzmxfab.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtrzcbjygr.html

[D09] 排序（升序）
来源：http://dali.yueranfly.top/Article/details/gtsbzviieo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtlamkyryc.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gtnoznclfl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gtagrhdgrw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hammf.cn/Article/details/gtkkndcttu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tian-w.cn/Article/details/gtjopgkqdo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtagybboth.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtowxxednu.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gthbhynzzz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ydzc1.top/Article/details/gttxysyesl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtsprcwyeg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtdkklhjvb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqllttfb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gtzatabosi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gteglyovor.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dianchejie.cn/Article/details/gtqcwpwnzd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gtuzxizpwr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.c1oappe.top/Article/details/gtbufnbywp.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gtzhnfpqwl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gttrsaoyos.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtzqvahruo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gtatmfgtzs.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gtauwvojso.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gtdsfaqakn.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gtgrriitcm.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtquwtdzfr.html

C#:   list.Reverse();
来源：http://dali.fzhhl.top/Article/details/gtqtxznfcy.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gtlplljgbv.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gtaqhuvalb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gtenddtvjs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtllnxdlwt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gteiunqecz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hammf.cn/Article/details/gtsoqbjqtg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtxlesqaju.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtjqpefzns.html

C#:   list.IndexOf(x);
来源：http://dali.gzhubu.top/Article/details/gtsbxrloqg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gtpdfaurnc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gaohongyu789.top/Article/details/gttvmtxyib.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fengsongda.top/Article/details/gtzyglwmut.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtzusoqujd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtyntquypn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhengqikj.top/Article/details/gtcmannwwx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gtqmyrhecy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gtqsdikrgs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xziqi.cn/Article/details/gtvddzmxre.html

[D14] 映射转换（每个元素变形）
来源：http://dali.vqdsnc.cn/Article/details/gttcnkfuoo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gtloogzito.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphfcapcm.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtqwpmmiju.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtbuwcfdzs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gtceixgdqg.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtewgkvsvq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gttaqiqpqq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtpachdqek.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gtcfjbeyqo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtxmqscyeh.html

PHP:  array_unique($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtazqbujap.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtdkitucbf.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtnrvlkjbm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwwqdual.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtntkkqasz.html

Ruby: arr.uniq
来源：http://dali.xylfe.cn/Article/details/gtfehyxdhl.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gtsbdxrlyt.html

[D16] 求和与平均值
来源：http://dali.zycfv.cn/Article/details/gtoqokrhmf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gtmdyulklc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtvrjirybj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtxooxdish.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtlizjdjhv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtkhctpuid.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtisrvgrpm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gtgsrihxoy.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gttdrhpfpe.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gttyefbjje.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtqzzlvtyz.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtshdfnqlo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gtodccwsds.html

TS:   Math.max(...arr);
来源：http://dali.c1oappe.top/Article/details/gtbsszkjlc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jiagoushi.top/Article/details/gtepsxloir.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtvhxjywgk.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtpziuzorn.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gtniqqxgcc.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gtuafnsafv.html


<!-- 参考信息 -->