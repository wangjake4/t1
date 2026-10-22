代发 wailian999

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gtvkuprlpi.html

Py:   isinstance(x, (int, float))
来源：http://dali.kuanghao11.cn/Article/details/gtclteasla.html

PHP:  is_numeric($x)
来源：http://dali.yuxming.cn/Article/details/gtnkvustug.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtiolkzoxp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtdekrocnm.html

Java: x instanceof Number
来源：http://dali.jqgfzy.top/Article/details/gtlcuzmbdi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yanxiufei.cn/Article/details/gtfhaxwrlf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gtloxlobon.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gtqqjoqsfs.html

[B14] 判断值是否在集合内
来源：http://dali.tian-w.cn/Article/details/gtmyzjecuw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.smart0.xyz/Article/details/gtewkemeir.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.havefunace.top/Article/details/gtcuamyspu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtwophxktq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gtrdrmpgmd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pycfn.com/Article/details/gtwnmoqqto.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jlsjyb.cn/Article/details/gtbxahafsj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shuidangran.top/Article/details/gtmtwovuua.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtctmyaogn.html

[B15] 布尔运算与取反
来源：http://dali.iojbl.cn/Article/details/gtwuciyemr.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizgvtfod.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gtggeowjuu.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtslvuoims.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtooukpyyp.html

Java: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtybkkovog.html

Go:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtvfldhobx.html

Ruby: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gteetmiajl.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtgafcouhd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj202588.top/Article/details/gtpvoaosxs.html

Py:   if not data: return
来源：http://dali.guowangkeji.top/Article/details/gttrjbqidk.html

PHP:  if (!$data) { return; }
来源：http://dali.dashuyun.cn/Article/details/gtdrlkjkff.html

JS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtdkvpeobb.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gtlcbcqsoa.html

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtswdumnay.html

Go:   if data == nil { return }
来源：http://dali.yuxming.cn/Article/details/gtifpmbwpp.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangtech.top/Article/details/gtbekgrsmq.html

C#:   if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gtkhumiuiy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttfapbobx.html

C. 函数与作用域
来源：http://dali.hywenlv.cn/Article/details/gtresvphmn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsoaskzqg.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtnktoptny.html

Py:   def add(a, b): return a + b
来源：http://dali.hfpthk.cn/Article/details/gtjqekgbfl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtgazrqzqu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtosyqwdgx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtzhzuupac.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gthvusungp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkderivg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gtugsijbsd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtocxvacks.html

[C02] 默认参数
来源：http://dali.yuxming.cn/Article/details/gtweqhlqdg.html

Py:   def greet(name="World"): return name
来源：http://dali.yuanzhike.top/Article/details/gtmrgywmuh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gtbighzbmc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gtebnnapag.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtyjgeqrit.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.mhx1999.top/Article/details/gtgclxanzg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gtrmxkywje.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gtthynibkh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gteghqnzlc.html

[C03] 可变参数
来源：http://dali.yj202588.top/Article/details/gtzhlnonul.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gtxbxtdsro.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenzaomai.com/Article/details/gtnppyould.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtehfnakem.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtjcuodvhw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuxming.cn/Article/details/gtwclconaf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoftuezid.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gtmivarnuc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gtybxeytyl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.svipenyu.cn/Article/details/gtszyzpwcd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gtqltxiuzv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gtxgydwvfk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtcgtgdlde.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gtseaaftyb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcwxqkrf.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxinkj.top/Article/details/gtpnhusuru.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtavcnrsqi.html

C#:   f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtahsvvfdy.html

[C05] 返回多个值
来源：http://dali.chenzaomai.com/Article/details/gtrkjbkgmw.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtcdvbyecf.html

PHP:  return [$a, $b];
来源：http://dali.pengpengdd.cyou/Article/details/gtspqoqsez.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtcpxzvnbk.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtmmtyefzv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.316326.xyz/Article/details/gtffdwmqji.html

Go:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgitjjfhm.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgfwtdsk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gtublqspxm.html

[C06] 匿名函数 / lambda
来源：http://dali.quarkkingdee.top/Article/details/gttyptibcb.html

Py:   square = lambda x: x * x
来源：http://dali.zhongyouzk.top/Article/details/gtsosbajxf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gtbjmwzyjc.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gtfnxchdrj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtcvzeaibh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvwzfkvu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gtjtdejpxh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxinkj.top/Article/details/gtmagacmrg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtfhmwodax.html

[C07] 把函数作为参数传入
来源：http://dali.hnxiangtu.top/Article/details/gtfccpflri.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhoulong.xyz/Article/details/gtrubetwwt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gtkjybjvfi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gttpzaeaje.html

TS:   arr.map(String)
来源：http://dali.quarkkingdee.top/Article/details/gtkwtoghfp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwdhtrvr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gtfmjdkisi.html

Ruby: arr.map(&:upcase)
来源：http://dali.cheryme.top/Article/details/gtzmeajryp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ivvv.top/Article/details/gtkvuuiiza.html

[C08] 闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbmyiegd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gtebuhjgji.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.birdmap.top/Article/details/gtukyplrww.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtalkoghbc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtckzldpjv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.c1oappe.top/Article/details/gtksusxvgo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ppjwa.cn/Article/details/gtdijwnsjy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gtznolsnpc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtchfankrt.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gttwiebzhh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gtychjtsbb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gtpijalgoq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtxrvsjsoo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gtfkmohazv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtqpteanhb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jianghu66.top/Article/details/gtudeuxymu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtepcpylas.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jyoumei.cn/Article/details/gtfgnjaxvw.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gtscxudtnn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gtieegpgkk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.havefunace.top/Article/details/gtwazkddjt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gtidjyelid.html

TS:   同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwxlxmfb.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtagswyfse.html

Go:   花括号块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtsxdyhudt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gtaxrzautp.html

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gtkmhvhkis.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gtlhtmuqnq.html

Py:   from module import func
来源：http://dali.hnxiangtu.top/Article/details/gtdhdonndf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hongshengwenyu.top/Article/details/gtsbiybujd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gthijzcaxy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gtprcbjfdk.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gtextmzxrv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.redwolf501.top/Article/details/gtxwltjamz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gtqzglrehh.html

C#:   using System.Text;
来源：http://dali.fzhhl.top/Article/details/gtrxoarcyl.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gtpfiowwdw.html

Py:   (lambda: print("run"))()
来源：http://dali.gotoacloud.top/Article/details/gtkswrhtaa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtagysblbv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtnavubaqm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gtvlxcvgie.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gtmkesdtwn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258888.top/Article/details/gtunnjelai.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtckexbuni.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hfpthk.cn/Article/details/gtyvjgordo.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gtvapfaevm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtonphnpdj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtyjzzuslz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gtaxpherbw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtorkiduwv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxisrtjeo.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gtjafevbtl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yonumen.top/Article/details/gtphyfrhrv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gtdbedhlji.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gtpyzblcmk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gtsmpophop.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtewzzfwni.html

JS:   // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdlitivl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gtmjtjbfll.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gtrrdijacy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gtvmdypqyh.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtjwxjyjgs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gtgdnvkjvc.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtfsblhimu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gtjihogkgx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvukfvpbu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gthynjrukc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gtrjkconqj.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gtwiggcxoh.html

Go:   // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtfaqzujts.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gtwbyqgoqd.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gtesotuwbr.html

[C16] 函数 / 方法重载
来源：http://dali.zhixingplan.top/Article/details/gtpwwkuajr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jlsjyb.cn/Article/details/gttnnpconm.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gtqzbzxcok.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhoulong.xyz/Article/details/gtjaykwupd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gtqnrterwi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gtunqnxgba.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gtxciqfney.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gtrkxnvnuz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxuanxn.top/Article/details/gtzyqurgfj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbtnfxgwl.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gtdfizkhsp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcndpfkgk.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtjfxfyjcn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gtkawltejq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gtsrghrnpa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gtaeinaphs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgfzy.top/Article/details/gtcsgmvqzm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gtlpjortnw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gtxkduldvh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtqzjkcbul.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tanke756.top/Article/details/gtevcbmcwd.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtpmjjnduu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinghuilouyu.cn/Article/details/gtyexiwghm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.svipenyu.cn/Article/details/gtctjpixmg.html

JS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwxlenpi.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtlarwyjgd.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtswfriaod.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gtzlrsixlp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gtrqscfonh.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gthrvtixcs.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gtebetpxat.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtntuiyhjj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznsogodc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gtmiooaxnm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqeqoneh.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gtbonneskz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gtvccvyhaf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gtdxanafld.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtduqplobs.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gtwbtvnzut.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daxiang520.top/Article/details/gtjuujgnbc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtomqprgly.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gthlomhgut.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtoibsyaaj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gtdiotkzer.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxinkj.top/Article/details/gtmsikewch.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gtbrnuyyfx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yanxiufei.cn/Article/details/gtkfteucvv.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gtbxbuozfx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtcinzsuis.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtaycgnhmf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtxxopbber.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuetiantiany.cn/Article/details/gtxedctumj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtxbuaejvs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtlfrbbfin.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtcjoavutv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtjcepngml.html

[D06] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtzmmpymso.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtzxyetqst.html

PHP:  count($arr);
来源：http://dali.ybcxt.top/Article/details/gtptucbnmb.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtpgltfnws.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtxxwhulza.html

Java: list.size();
来源：http://dali.dashuyun.cn/Article/details/gtctuhlvqk.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtqidztvnq.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gtpjbjhvkq.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gtfdtrievf.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gtxemyzxgj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gtcunbkydg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtjgkheemm.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtedjanwkq.html

TS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtckqvsjmn.html

Java: list.subList(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqiyvbxl.html

Go:   arr[1:4]
来源：http://dali.zycfv.cn/Article/details/gtlpczjlyl.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtoqckvoed.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gtkovcvewr.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gtufhecszd.html

Py:   a + b;  a.extend(b)
来源：http://dali.tianlin.xyz/Article/details/gtevzleuxy.html

PHP:  array_merge($a, $b);
来源：http://dali.guowangkeji.top/Article/details/gtvilfzdov.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtscubcnsz.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gtsxsnxqxj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hfpthk.cn/Article/details/gtnzfmkxrg.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gtbdkrajly.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gtqyzidlvh.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gtkpdswluy.html

[D09] 排序（升序）
来源：http://dali.nwbrower.top/Article/details/gtvddurkek.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtleqqctfa.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtgwdxfvqb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmfqdpgu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj202588.top/Article/details/gtkttxkewt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shzxlz.cn/Article/details/gtatorwwlm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtbjjdudwp.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtwuykdimj.html

C#:   list.Sort();
来源：http://dali.quarkkingdee.top/Article/details/gtbfxlbbxz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gtpevsdivt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gtnficbzir.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gthrazckvg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gtgycqhsda.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gtqmscpzpz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gtpqzqehsf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yanxiufei.cn/Article/details/gtlevdajcf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gtfxsfokka.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gtwpzwrugb.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gtzybqvdkj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ppjwa.cn/Article/details/gtgaeafild.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtwtsdampb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gtprjifhnm.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtmcbekltx.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gtzmhomgcd.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gticbqqckx.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjyqlvnu.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gtxislpccp.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gthaigigpy.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gtseqawexy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtmpzmmpkd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtynpnkxvl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtcvfbmsob.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gthpwocunq.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtuylbmzqm.html

Ruby: arr.index(x)
来源：http://dali.nanxinkj.top/Article/details/gtsdobvgew.html

C#:   list.IndexOf(x);
来源：http://dali.316326.xyz/Article/details/gtwaaxfgec.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnexefvp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtercobfcj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gttmnrlnei.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtnjdoxnqn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtpspwhhgh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gtajosgzry.html


<!-- 参考信息 -->