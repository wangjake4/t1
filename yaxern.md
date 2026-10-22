代发 wailian999

Py:   if not data: return
来源：http://dali.hywenlv.cn/Article/details/gtpuzttzlt.html

PHP:  if (!$data) { return; }
来源：http://dali.pengpengdd.cyou/Article/details/gthpncabpw.html

JS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gtekocqgjr.html

TS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gtxidjlbwu.html

Java: if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gtsurjkjiu.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtgluzcvja.html

Ruby: return if data.nil?
来源：http://dali.hammf.cn/Article/details/gtuirxxjaa.html

C#:   if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gtjchhltjq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzywltfjp.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gteatbjmde.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtwmlrahhs.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtrdyvpcbz.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gtmieutbvb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtjuhmqelh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtuilgsefy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtiyjjuwhs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtskrdqckj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gtppgrfnhy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gtabcenrpl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtgpwklzyl.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxataeuv.html

Py:   def greet(name="World"): return name
来源：http://dali.jlsjyb.cn/Article/details/gtpxnukvfg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gtnguxkwcf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlnrrhozd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtdnramrby.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gtbsihktdj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gtxwctkztx.html

Ruby: def greet(name = "World") = name
来源：http://dali.zycfv.cn/Article/details/gtlkytaaio.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfrtlfkq.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gtuygfglcb.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gtxphvsiws.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gtppvhazqv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcvgersv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gtpdkuweod.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gtrkcjxtzs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jiagoushi.top/Article/details/gtmxzqrdun.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gtfuzxtfsa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cashguo.top/Article/details/gtavkrgxgb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.quarkkingdee.top/Article/details/gtmgpunmdy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gtljlzicih.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gtaexknghn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtbjnrmmgg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gtmbliknls.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gttiohrzif.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuxming.cn/Article/details/gtuprylkoo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtfawkbgjd.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtotjcczwf.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gtrnqnzyuv.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gtkdjmqjin.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gtdtxbbrzg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtsblbsljf.html

TS:   return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtordvpkiu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gttjhkjwcr.html

Go:   return a, b
来源：http://dali.mhx1999.top/Article/details/gtcwznxhmy.html

Ruby: return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gthuybvcaz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.birdmap.top/Article/details/gtmhvkardh.html

[C06] 匿名函数 / lambda
来源：http://dali.gogol.net.cn/Article/details/gtbdsgizcd.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gtbmkomudo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gtqeuocica.html

JS:   const square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gtkqdsxfxc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gtectoasal.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gtinflzyes.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtsafmjmng.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxinkj.top/Article/details/gtxaewnevh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtsyfqjtuq.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gtvxwgdxtf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gtmepamslr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gtrkhsbinv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hywenlv.cn/Article/details/gtvbjifmxp.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gtzjjhmuya.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtrgwifane.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yvedp.cn/Article/details/gtrylqwuvb.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gtlxolsqjj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258.top/Article/details/gttqdbevtg.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gtktbxnuqw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtbmokpypd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqtvabxp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gtjatfrebm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtgvzfywvs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aizwys.cn/Article/details/gtljqmgsoo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pengpengdd.cyou/Article/details/gtcodmzxup.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtvjozkznr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gthjzsmzhk.html

[C09] 递归
来源：http://dali.meibo888.top/Article/details/gtsgbmneik.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtohnbvycn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtmtaushns.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtyxatqfdh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtyjlooqwp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyugwxiwp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.9152youxi.cn/Article/details/gthzrsxopz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gteaibbpsw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtyzrnkyrz.html

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtlxxqwifv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hongshengwenyu.top/Article/details/gtzeufknzc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhengqikj.top/Article/details/gtfttluxan.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gtaumyjvub.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gtocqvjwig.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gtfdorzppf.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtjhoduyep.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gtckrkcpqa.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gtywzskwfk.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gtsryvxmnd.html

Py:   from module import func
来源：http://dali.andypj.xyz/Article/details/gtapgwbolm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yangfankeji.com/Article/details/gthiqyfdhh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtktgovpzr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gtstubxzdr.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gtteqfbysr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gtgfsopfke.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gtoufvkwli.html

C#:   using System.Text;
来源：http://dali.jyoumei.cn/Article/details/gtbnsnueoj.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gtrkjuxezr.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gtylogvtvc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigfzy.top/Article/details/gttrnjkgfn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvkqhilx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdulsewo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gtijcoveum.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gogol.net.cn/Article/details/gthukjzlgi.html

Ruby: -> { puts "run" }.call
来源：http://dali.quarkkingdee.top/Article/details/gtradtahly.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gtipyluyog.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gtfsqkiuck.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gtksckdmub.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gthhfmcrfn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtinsxthln.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtqcxivkky.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtyjmzasey.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gtavhwrmbt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dashuyun.cn/Article/details/gtkyukpobi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gtoiphggad.html

[C14] 泛型函数
来源：http://dali.yueranfly.top/Article/details/gtzywrysdr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuxming.cn/Article/details/gtamxvsjcj.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gttvydenuu.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtliewmexs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtzbkjwzoy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwsckvnxz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.andypj.xyz/Article/details/gtsqqxmume.html

Ruby: # 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtieziwfyu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.snrcjt.cn/Article/details/gtkraqnvmc.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gtvnrcqsna.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuermziwm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gtrfzczftn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gtwjvvmxyf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtlkfbulcm.html

Java: // 无解构
来源：http://dali.redwolf501.top/Article/details/gtsxblaaqd.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gtjvpklabh.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gtyksencug.html

C#:   var (a, b) = pair;
来源：http://dali.chenlongwang.top/Article/details/gthkpiwaiz.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gtqdjibevw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gtwhumdyus.html

PHP:  // 无重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtxunhtmgb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gtodsgormw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hysaishi.cn/Article/details/gteepthukq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gtgzubbmky.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhoulong.xyz/Article/details/gtjxwimpih.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cqqwz.cn/Article/details/gtvxmhrjvg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yueranfly.top/Article/details/gtthknebjv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtldirgrvd.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gtmdcitgtq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtcayhvrhj.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtluobsnqb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gtnatmntdn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gthfupkpai.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtrpwmstoi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gtxgbscqww.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtvusprkgc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gtitcjgmwq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gtvhtasxij.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdumnlri.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gtiwcmejga.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shuidangran.top/Article/details/gtmfeoaddl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gthlbnoklh.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gttkxnkidj.html

TS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtizahcnhs.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gtzklexfcm.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqarpcwja.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtaefwitjm.html

C#:   list.Add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzucfchrn.html

[D03] 在指定位置插入元素
来源：http://dali.zhiwuduotai.top/Article/details/gtkccbtsqr.html

Py:   arr.insert(0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtlcvgkknf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrkmfvqm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ehwqpu.com/Article/details/gtqyipfpba.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtaihhtech.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyuiybjr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gtukfkakkl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtkqwtqzlc.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtkyjyiroe.html

[D04] 删除元素
来源：http://dali.ivvv.top/Article/details/gtrnmksjds.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiiqubyn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.iojbl.cn/Article/details/gtifjmadkb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gtzewmhwex.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gtvpcbgamk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gtcwkankqo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gtixnxxtvt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gtkqvndkto.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gthseakpfl.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gtlukxmvrt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtocjglllr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtxlwcdeje.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtuagggkqt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gtkpkefqmw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.iojbl.cn/Article/details/gtoqwcsceo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtkeqvmnls.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtaujwxbjo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtgvqqicjy.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gtmzdpipan.html

Py:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtwoqqzgnt.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtynvqyqos.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtjrgytnej.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtzkacpfrp.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtqxfxyzjx.html

Go:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtzsaeds.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gtejsciidh.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gtgyrtufkv.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlzgtnrs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gtqszdyqoy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtlwsehrzb.html

JS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtgbugihed.html

TS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtfltulerj.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gthayaxthk.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gttmgysejj.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gtbmzowmgd.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtywzlykib.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gtzfocxzjm.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtnbfntnaf.html

PHP:  array_merge($a, $b);
来源：http://dali.aibaodan.cn/Article/details/gthaywermc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gtbkrzgnod.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwjpwrry.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtnhnlfvld.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gtopmigmdz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtzkuauvko.html

C#:   a.Concat(b).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtsaqqiaed.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gtihteszme.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtxnkaxhnn.html

PHP:  sort($arr);
来源：http://dali.zhengqikj.top/Article/details/gtylcywotq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxinkj.top/Article/details/gtkuzubzqv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtfwkncuky.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gtmujztvdi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtofviopbd.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtpoychhkl.html

C#:   list.Sort();
来源：http://dali.yueranfly.top/Article/details/gtsjlppwst.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gtwdaugssg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ppjwa.cn/Article/details/gtwwgbfwuk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gtqqxfbxrj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtusrjpaaw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtznfqjgsk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gttuybutwj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.birdmap.top/Article/details/gtcritpzbi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenlongwang.top/Article/details/gtvbusaigf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtcgcsbwxn.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gtoypjiuby.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gtqodpwndz.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gtgpbrqewq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gtcyxvbske.html

TS:   [...arr].reverse();
来源：http://dali.cheryme.top/Article/details/gtbixdrjnd.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gtmdpemkti.html

Go:   slices.Reverse(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinuhmosu.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gtucnqvciy.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gtgmapxfdy.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtyrayrlsv.html

Py:   arr.index(x);  x in arr
来源：http://dali.daria6918.cn/Article/details/gtcbyhadqs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtdgjrmgxn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtdqlrfqfq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtiuqubgss.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtberggrro.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtdrviktty.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gtukdorgts.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtfkjybofr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtdvnuevjz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtlsctouqe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gtyjjnsqji.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gtasvihivv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtzelhusnn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hammf.cn/Article/details/gtlxegpqkz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.bjfxy.top/Article/details/gtcjhwckpj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gtqsqqvwxa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ivvv.top/Article/details/gthbvhcxoi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gturivinbz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gtyxndwsek.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtloyayzql.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtyeyuhftt.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtdbptqlwz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gtltbbddzr.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtcnqnrjmy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtxufublas.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbquiwqog.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtbmgtdzlq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtaxxhlvpq.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gtwdftwcoz.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtugqzfwnt.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtfyidkgrg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258.top/Article/details/gtbxxrgmyc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gtammnknwr.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gtshlmpdif.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkujtivng.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gtutfovrtn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtxuaeoupx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtmmphxqeg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtvexilkve.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtcgugnojc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gtxcvjfyot.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gtsvfqtujo.html


<!-- 参考信息 -->