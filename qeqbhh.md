代发 wailian999

Py:   if not data: return
来源：http://dali.feifeiyinyue.top/Article/details/gt2letnsgdj.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gt2zjdinuxm.html

JS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gt2upjesjix.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gt2cwgifujn.html

Java: if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gt2vtmwvrln.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gt2yiziosty.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gt2ingqjzqx.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2qhanrghk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2zosrqrvw.html

C. 函数与作用域
来源：http://dali.jqgfzy.top/Article/details/gt2bncmhdxe.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2qlbufhje.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gt2yncgeonl.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnqxrtma.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2kjtlxvef.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2uyxwptoh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2tzpwfjzs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2kgmgznkd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gt2igajacpt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.bjfxy.top/Article/details/gt2dpzxffxo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2olnraqbo.html

[C02] 默认参数
来源：http://dali.yueranfly.top/Article/details/gt2rqhkdsxj.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gt2ldyaqnvv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2albcetod.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2uujlbhjr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2ugffnoxa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtasctjr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gt2nlatmltj.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigufen.top/Article/details/gt2esgwwxly.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ehwqpu.com/Article/details/gt2ipnkwyab.html

[C03] 可变参数
来源：http://dali.ehwqpu.com/Article/details/gt2uwuuqhuf.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gt2qdwxgrua.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gt2cpyrtxyy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnxkfrf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gt2azrprtfa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ogtryjgi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnxiangtu.top/Article/details/gt2tzlmjrrc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gt2brvdhefs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnxiangtu.top/Article/details/gt2thcyoimf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.iojbl.cn/Article/details/gt2vdukxllq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2crzyfkru.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gt2xfstkens.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gt2ogzmusud.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tngtyhfa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.9152youxi.cn/Article/details/gt2johbicto.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gt2bambcfnz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gt2urmzavxu.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gt2qlhtqrou.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gt2vjisyabd.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gt2rwwtiych.html

PHP:  return [$a, $b];
来源：http://dali.hnqzz.top/Article/details/gt2jrazvqzg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sweek.top/Article/details/gt2kmsstesp.html

TS:   return { a, b };
来源：http://dali.yj20258888.top/Article/details/gt2myxqigmc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cheryme.top/Article/details/gt2lqlifsuo.html

Go:   return a, b
来源：http://dali.cucudq.cn/Article/details/gt2mxkxhmvv.html

Ruby: return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2qyvhxpkl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pukrogwg.html

[C06] 匿名函数 / lambda
来源：http://dali.zdqjudy.top/Article/details/gt2xpbdrchp.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gt2dkgodmfo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gt2iekpzqqt.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2lxsnnpbl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gt2jzjruybi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gt2ecwekose.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gt2nimpmtzi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gt2krpezfyb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2womdpcrh.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipextlzu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gt2ywopmrdq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2wwlaloov.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ivvv.top/Article/details/gt2uciacfir.html

TS:   arr.map(String)
来源：http://dali.xinyue.icu/Article/details/gt2oydazrji.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2ticowwre.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gt2xujqturo.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gt2zvxfnolv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxuanxn.top/Article/details/gt2aaxnsmvu.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gt2yhzdlqij.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.haohaochexian.top/Article/details/gt2pynuedpn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gt2phfhxrmz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uinavgri.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2gqnsatak.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwrtohdl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kajgnahv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2jatvnzqe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2grgchvti.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xuthnocc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gt2ddetlfei.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gt2ptzbbtlt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2zuiotbai.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2sccisyhq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gt2wldknmyz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guannengcc.top/Article/details/gt2khlamoui.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gt2ktdhjwrm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cashguo.top/Article/details/gt2bqoxftew.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2xlrvfrdq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.iojbl.cn/Article/details/gt2yeubepwv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gt2ppsutfjd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gt2fagwdnit.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gt2ddrxgqru.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2cvvocdtn.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2amrbvupi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tanke756.top/Article/details/gt2bhjucntw.html

C#:   块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2evzkdvdo.html

[C11] 模块导入与导出
来源：http://dali.jiagoushi.top/Article/details/gt2zypufcrd.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gt2lahadtqv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vebtzblu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2refybqzn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.kuanghao11.cn/Article/details/gt2zlebnlsw.html

Java: import java.util.List;
来源：http://dali.birdmap.top/Article/details/gt2mizarprf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hpqzklvf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gt2lpcvtfdt.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gt2emxcnepb.html

[C12] 立即执行函数 IIFE
来源：http://dali.316326.xyz/Article/details/gt2mqbehjnf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhengqikj.top/Article/details/gt2akryzcto.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gt2yaddyikq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gt2appednvn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2ddrvyfbp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gt2miuryhtw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gt2npfmtcxl.html

Ruby: -> { puts "run" }.call
来源：http://dali.316326.xyz/Article/details/gt2wkylovvi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gt2gniomiek.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gt2ocvbndyh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gt2negwdmyp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2yqaoztnb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gt2qnwskrvr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2diopiblq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2rvxinwaw.html

Go:   func add(a, b int) int
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcgbotkh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gt2ceugbvwo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkcrhgeu.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gt2uiixvgpj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cashguo.top/Article/details/gt2xndthxdc.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxfrfhqb.html

JS:   // 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2gtafbddu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guannengcc.top/Article/details/gt2tqcemkmh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wevrcvtt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gt2imeqddbx.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gt2xhwtjtxe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cashguo.top/Article/details/gt2xmupranf.html

[C15] 解构 / 展开参数
来源：http://dali.jiagoushi.top/Article/details/gt2xraauqjq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gt2nyepanhi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gt2vvhieohh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gt2bxwbtpel.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2oascalux.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eurvvmwy.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gt2wpwctpgq.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gt2oypregir.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gt2blkeiscv.html

[C16] 函数 / 方法重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icsyxtdb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigfzy.top/Article/details/gt2sveypeoy.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gt2qpvpuhmm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gt2ijhrglsz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gt2bddkteqp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gt2srptttpf.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gt2vwandnrj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yonumen.top/Article/details/gt2hcmpbocf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gt2vnqvjgfv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2udggrvco.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gt2hxibvhqo.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2eoktzwph.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gt2tzfqwxsr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.havefunace.top/Article/details/gt2dghbzyuo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxjyanxd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gt2htlaiyqw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gt2izifumix.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gt2dcoyfkry.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gzhubu.top/Article/details/gt2aceklncf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnqzz.top/Article/details/gt2bwhelrpb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gt2nctffiof.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gt2cmhygzdu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gt2okqeslad.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ehwqpu.com/Article/details/gt2xmuhxhkb.html

JS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2koiufhxm.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gt2depuctfv.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gt2sgzghtew.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gt2etjtwgge.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ppjwa.cn/Article/details/gt2fhurwcqb.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gt2objhnsyi.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gt2sfkhixwa.html

Py:   arr.insert(0, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2wbxqbnjd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gt2luewsruv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gt2gexagehk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gt2vasrcljw.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2ualpuncw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cdnleiting.top/Article/details/gt2kxvgbreg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yangfankeji.com/Article/details/gt2vxitioso.html

C#:   list.Insert(0, 0);
来源：http://dali.tanke756.top/Article/details/gt2xslmowpg.html

[D04] 删除元素
来源：http://dali.aizwys.cn/Article/details/gt2cqyknbaz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gt2fusarmom.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cashguo.top/Article/details/gt2izwbrtwh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgjaxjmv.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gt2tcioyksj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gt2wxlcpqyi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigfzy.top/Article/details/gt2hbiedcwi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangdashe.top/Article/details/gt2negahmxx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gt2kqrrphxt.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gt2rzfpwkuw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zoltjyef.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gt2kfsehqne.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gt2amblktad.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gt2almsqrkv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gt2uumdkaka.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2cfsendyl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2svyuljez.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2otrwqzte.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gt2lisnuiwa.html

Py:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2hdthneqm.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2phudqkau.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gt2qsxgrlco.html

TS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gt2xmgpxigk.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gt2bjvaszqf.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2rizyjcaj.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zaertong.html

C#:   list.Count;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lzobdfcj.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gt2eemwthkf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgfzy.top/Article/details/gt2fkzitofq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2xapcllpj.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2oxnvwqwy.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxjtedd.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2dilemyrg.html

Go:   arr[1:4]
来源：http://dali.xziqi.cn/Article/details/gt2nljllayv.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gt2fcgrlnrk.html

C#:   list.GetRange(1, 3);
来源：http://dali.xziqi.cn/Article/details/gt2ponsxgmi.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gt2dxomhrei.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmstekqr.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gt2vmpmfdla.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.316326.xyz/Article/details/gt2ilwkodvi.html

TS:   [...a, ...b];
来源：http://dali.hysaishi.cn/Article/details/gt2vrgmlqfm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2ykuwbeht.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gt2zuahiwgg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gt2ufbghvmn.html

C#:   a.Concat(b).ToList()
来源：http://dali.316326.xyz/Article/details/gt2jkxwprbx.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gt2awcdxwex.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdicdjlh.html

PHP:  sort($arr);
来源：http://dali.mhx1999.top/Article/details/gt2hrdzlkhy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gt2gcaoxjgk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hubqzgfm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guowangkeji.top/Article/details/gt2ofkujxhl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfhztfja.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gt2jbpbuyxu.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gt2xufzbfvl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gt2lsgqxxyp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gt2xemdxevc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2mjxittju.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gt2mgwtpxpg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gt2udzcxemk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gt2bbyezvxw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gt2ngxlumph.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gt2ttihihjg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gt2rvctsnkx.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gt2esikgaxj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigufen.top/Article/details/gt2yjozhuzx.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2qvhgftva.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qemyiwsh.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gt2fhvysgpn.html

Java: Collections.reverse(list);
来源：http://dali.dashuyun.cn/Article/details/gt2qnuefodq.html

Go:   slices.Reverse(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2oiopitbp.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2ollxrkru.html

C#:   list.Reverse();
来源：http://dali.fengsongda.top/Article/details/gt2omvlceje.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gt2gakxprte.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gt2vzvllabr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2vywydutj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2aulauflm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2gohtdgna.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ybcxt.top/Article/details/gt2nomocljx.html

Go:   slices.Index(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2mobkzqlz.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fszrknwc.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckfbxvas.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gt2jibdfhcn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gt2cwalphmw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gt2dtmbzqfe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gt2klcsdmbj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gt2uaeaoooo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2zptpsuwx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gzhubu.top/Article/details/gt2byhdszyx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gt2uwqoppod.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2njjafuqy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gt2oucxqtqh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gt2zrxshduh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zycfv.cn/Article/details/gt2vgsmzpze.html

JS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyxgczfy.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gt2ebbmqwss.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gt2tgijfxkf.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gt2iofybrhi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2hdxpgmtb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nudbxvgj.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gt2agcurkmm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2hzxuyque.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2slamdzip.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gt2jwdmjhfh.html

TS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2kepwaeue.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gt2pcdlwuwj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gt2itmtvuvd.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gt2qhcrkfbk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2himhlodt.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gt2tqazjndo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ofdtzpse.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2taurvbjm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gt2nrevnitk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2twtqihhv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gt2bvuaddhs.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gt2dwoeumyr.html


<!-- 参考信息 -->