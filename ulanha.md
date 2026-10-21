代发 wailian999

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtevdppvhv.html

Py:   def greet(name="World"): return name
来源：http://dali.yvedp.cn/Article/details/gtswzzwopn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuanzx.com/Article/details/gtlegqmaqg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtqpxqlbjf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtwcaqawnf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtaqpemfrc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.redwolf501.top/Article/details/gtuzfzrvjf.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gtkzgypxkc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gtdriearry.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gtpwsykslx.html

Py:   def total(*args): return sum(args)
来源：http://dali.vqdsnc.cn/Article/details/gtyxjpppxt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtbfdaravd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtgaodocou.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrtndqqmf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gtfiubxzvq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gtppyzxahc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gtmrvqxxgg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gtfxdgrnyj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gttpjccamx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jianghu66.top/Article/details/gtjarmyuvv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxfsnxfj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtnmusisje.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtciwgsvrk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hongshengwenyu.top/Article/details/gtwemhkxie.html

Go:   // 无：用配置结构体参数
来源：http://dali.yvedp.cn/Article/details/gteitoxjcv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtpveisosd.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyhlmylo.html

[C05] 返回多个值
来源：http://dali.hnqzz.top/Article/details/gtiffznrwv.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gtbxbzlqbz.html

PHP:  return [$a, $b];
来源：http://dali.dianchejie.cn/Article/details/gtirsxfvfw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtjmonoxnv.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtkfnnsmoq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aibaodan.cn/Article/details/gthhgjiyqn.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gthysqwkab.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gttsayrnex.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gtpdlkidks.html

[C06] 匿名函数 / lambda
来源：http://dali.xinyue.icu/Article/details/gttsthiqph.html

Py:   square = lambda x: x * x
来源：http://dali.aibaodan.cn/Article/details/gtbnlegcqe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtulvihhdq.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gteqwkzmjp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtfhwtvsgh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtucrjqwlf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gtebrzohyv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gtebzacmen.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtvvuxnpoc.html

[C07] 把函数作为参数传入
来源：http://dali.xylfe.cn/Article/details/gtxicsibiv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shzxlz.cn/Article/details/gtfzvztmsh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtjtxtbgba.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yvedp.cn/Article/details/gtnhbdzxzt.html

TS:   arr.map(String)
来源：http://dali.zhoulong.xyz/Article/details/gtwwrrhnwj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtwkqjawgi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtmolqohoj.html

Ruby: arr.map(&:upcase)
来源：http://dali.sysykeji.top/Article/details/gtdeieyvhq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zdqjudy.top/Article/details/gtrykjunua.html

[C08] 闭包
来源：http://dali.chenjidiqi.icu/Article/details/gtaannpxih.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gtxtotunob.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sxryk.cn/Article/details/gtqtvzejct.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtqwwquowq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtkkhhbzey.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sufxvd.cn/Article/details/gtvjckpkch.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.havefunace.top/Article/details/gtgdhnurga.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gtcorpedwy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtvvnjzuqa.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqekhnjp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gtfniprcnt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gtduqpdyww.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtmmbiptuo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtpdmpvhjs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtriesrhwp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gtcftmxbbu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtygbjaboa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sweek.top/Article/details/gtfpwpunwz.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gteegqqgcf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gttmlussyc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tianlin.xyz/Article/details/gtcfgojumx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gtbbgbwjft.html

TS:   同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtktefcnqj.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gtcvqdcaur.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtvcrqtfpd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gtatxddknh.html

C#:   块级作用域
来源：http://dali.wangdashe.top/Article/details/gtjpijqlze.html

[C11] 模块导入与导出
来源：http://dali.zhoulong.xyz/Article/details/gtxguufxek.html

Py:   from module import func
来源：http://dali.shzxlz.cn/Article/details/gtkitnrglq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gtrtczyjpk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtmzhrwalm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtcszwfoyt.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gtpmwywams.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gtlylsrlre.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojuobodd.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gtwwfjuzsl.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxceifpmh.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gtyowmoipf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.iojbl.cn/Article/details/gtvkhjvkio.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtzgykwotq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtdpxwycin.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gtnkpaxckq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gtrcmjegss.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gtfqjxaiii.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gtxwzeyodn.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gtslbdyskh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfqoalch.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtppeluiyn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cashguo.top/Article/details/gtwhrdjapg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtjuqqagqu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtupabmgrc.html

Go:   func add(a, b int) int
来源：http://dali.meibo888.top/Article/details/gtwknhkdpf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.birdmap.top/Article/details/gtjwhrjhfi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zdqjudy.top/Article/details/gtxwodwjkg.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gtmmwlvglp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.iojbl.cn/Article/details/gtlyshwomx.html

PHP:  // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtloeglvuz.html

JS:   // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtfwwsxeec.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gtfpctfffp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gtzrwpibws.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gtircnezyl.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtieqkkjof.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gtvvcpbssw.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gtowiqeqvp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhiwuduotai.top/Article/details/gtfuaihxbe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gtsrhdpwur.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gttlbeekze.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtuhbzhsqt.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtrjxzrofd.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gtqmgmtxte.html

Ruby: a, b = pair
来源：http://dali.zhixingplan.top/Article/details/gtabdtotyk.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gtrclvsiub.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtnsyvmjvg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtjxnxltcg.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gtwesnbeej.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtlojdgafg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gtyvdgztky.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cheryme.top/Article/details/gtyxbabcvh.html

Go:   // 无重载：用不同函数名
来源：http://dali.hysaishi.cn/Article/details/gtiaqtjivc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daria6918.cn/Article/details/gtpnuoovwd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtwqqujnoj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtuguzfubl.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gtobomotxo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqwqgruzd.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtjuwxabak.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gtmqstgofn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjpxwqye.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtxknmaqwb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtquiupiqd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gtueyswmst.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tanke756.top/Article/details/gtnyiyfdsa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gtnfjgthph.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jyoumei.cn/Article/details/gtbbdygymx.html

[D02] 追加元素到末尾
来源：http://dali.guowangkeji.top/Article/details/gtjfitktde.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.smart0.xyz/Article/details/gtqpvqnmad.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtrkgrgouo.html

JS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtzogknleh.html

TS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtaxhcaiwv.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gtymxhitjn.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gtzaogkdcf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daria6918.cn/Article/details/gtbgumxgyq.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gtqwkjkuls.html

[D03] 在指定位置插入元素
来源：http://dali.pycfn.com/Article/details/gtbateerpp.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtebxvtaws.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gtkyzfjkyt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gtpdcsgyug.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gtkfthdnbo.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtidzsumpt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gttjolmquu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jiagoushi.top/Article/details/gtmvgkdgzx.html

C#:   list.Insert(0, 0);
来源：http://dali.gzhubu.top/Article/details/gttvhfxfza.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtrfpdmiiz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yangfankeji.com/Article/details/gtjustrrbu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gtuakwokug.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gthfqwbnou.html

TS:   arr.splice(0, 1);
来源：http://dali.birdmap.top/Article/details/gtogcxkwkq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhongyouzk.top/Article/details/gtpyswdjmx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gtehbjcrbt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gtelvricgu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gtefxecnwx.html

[D05] 访问与修改元素
来源：http://dali.yongpay.top/Article/details/gtqoovramq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtvtjjrzkn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtotxksmdm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtrewqtogn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gtlqevnmcl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gthvthvkki.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtndmdgkxq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtrivlxiyp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtizxsqkuq.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtnqatmwpf.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtsneelxpd.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtueepimgz.html

JS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtzwfuolda.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtjrnskzkp.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttjkdtnz.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtfmhfmflf.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gtjerqepaj.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gtaijscolc.html

[D07] 切片 / 取子数组
来源：http://dali.shangyingyoupin.top/Article/details/gtzavxmjrb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gtjyrkbjzn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gthvssyuyc.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtmviezosl.html

TS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtmfrgsyjl.html

Java: list.subList(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtniztsfxi.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gtuwfblasf.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtnsserzvi.html

C#:   list.GetRange(1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtjovufjhh.html

[D08] 合并两个数组
来源：http://dali.dashuyun.cn/Article/details/gtgzkesugy.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gtklccflmm.html

PHP:  array_merge($a, $b);
来源：http://dali.sufxvd.cn/Article/details/gtnqvqsxbl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gtuhjwieuo.html

TS:   [...a, ...b];
来源：http://dali.jyoumei.cn/Article/details/gtepwhykuy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtlmkxstqn.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gtkdzudiwz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gtmnqhcect.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gtqylzdgnf.html

[D09] 排序（升序）
来源：http://dali.guowangkeji.top/Article/details/gtjydxzlby.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejzquqvz.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtvjokrhyb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gtmvenevqa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtytzintzq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gtxdxezpdj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuojpuxz.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtoechywpg.html

C#:   list.Sort();
来源：http://dali.yanxiufei.cn/Article/details/gtgkspjwmz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gtfsrhntos.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gtfoafrkvw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gtqiyntbty.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtcismycrp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtkxzcqpmr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ehwqpu.com/Article/details/gtfzilovju.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gtlcqcbuhm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gttcxfzwqb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtwrabdqmc.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gtjjwxbxfs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gtvwvcxtxa.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gtsdduiptm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gtigtztlsp.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gtgwiemijx.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gttekulzsg.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtuqvcnteo.html

Ruby: arr.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagbgkvtu.html

C#:   list.Reverse();
来源：http://dali.ivvv.top/Article/details/gtiacuultp.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gtxprpvdie.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gtwhmtwsxk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gtloovphbn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gtbzagmdar.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtfyytfiwq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gtblgidpxz.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtwzeumeud.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtltpiupug.html

C#:   list.IndexOf(x);
来源：http://dali.jqgfzy.top/Article/details/gttxxuarxp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtwpbrgkqn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yongpay.top/Article/details/gtqwkuecof.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gtyksvnxgz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtibzwtzvp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtqbekdtjk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gthxluaaxq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gtvpfdlhon.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gtfonsqstw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtxacjntky.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gtzjxfbzht.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtshezidjb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shuidangran.top/Article/details/gtdqlmumvl.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtpoiprsmu.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtycwkuunv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gtddydblqs.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtnjfvjqic.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtxdhpccva.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj202588.top/Article/details/gtwqdahock.html

[D15] 去重
来源：http://dali.ppjwa.cn/Article/details/gtdresbqye.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gtsyvwknue.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gtcrlphudr.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gttnndutcu.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtlbufdtbz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gtsclbbtgb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenlongwang.top/Article/details/gthswzbsdq.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gtfwjoeaxb.html

C#:   list.Distinct().ToList()
来源：http://dali.pycfn.com/Article/details/gtpgubnyuu.html

[D16] 求和与平均值
来源：http://dali.gogol.net.cn/Article/details/gtvlnwqmpd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtgfvrwmhr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtsfhsxpew.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gttptsvguj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtxjwestoo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gtyacqygex.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gtbenclxue.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gtvqsgtepi.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gtksecitcw.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gtirmloqmr.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjschrms.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gtwhlnbyoa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtaifstdeh.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbcjyium.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.meibo888.top/Article/details/gtwarsawcm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gthviscqcw.html

Ruby: arr.max;  arr.min
来源：http://dali.svipenyu.cn/Article/details/gtlszjqpoq.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtpzzrsvki.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gtitvubpfx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gtzkqonwlg.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gtkfwjkeks.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gtovholbpy.html

TS:   nested.flat();
来源：http://dali.xziqi.cn/Article/details/gtfqnilrap.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yongpay.top/Article/details/gtihqlzxvc.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxtmrqvx.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gtvrhpbfhz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtphhdbods.html


<!-- 参考信息 -->