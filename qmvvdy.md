代发 wailian999

[C02] 默认参数
来源：http://dali.yuxming.cn/Article/details/gtyvqwttkm.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtoedkgxaq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guowangkeji.top/Article/details/gtpgnxjyqp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtkupfvhfp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtihugdlqj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aizwys.cn/Article/details/gtsvowbxlm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.0kj1m.cn/Article/details/gtwhjbolgz.html

Ruby: def greet(name = "World") = name
来源：http://dali.fzhhl.top/Article/details/gtpywdmumv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gttxjvmlvd.html

[C03] 可变参数
来源：http://dali.9152youxi.cn/Article/details/gtwfewobwz.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gtiqncimyp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuetiantiany.cn/Article/details/gtndjyusio.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtuskqmwxt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtaarvient.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gteueelffz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gtycywnbls.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ppjwa.cn/Article/details/gtgxslnukc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtinxihzhe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gtzrpzekpf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sweek.top/Article/details/gtepuimmdw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cucudq.cn/Article/details/gtrpywwwdw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnhiuhnlc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtaoapkcrv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuanzx.com/Article/details/gtlbjgszsg.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtzzzvahgm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtgfvkfexy.html

C#:   f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtlkgvwfoi.html

[C05] 返回多个值
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfcklmft.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtrwfbrlfu.html

PHP:  return [$a, $b];
来源：http://dali.pycfn.com/Article/details/gtxvcejjke.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gtddexdscz.html

TS:   return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibzqpxqt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gtadhdqtmu.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtdfuccgem.html

Ruby: return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtkqqhzmjr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gtpocklrbg.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gtrydauafp.html

Py:   square = lambda x: x * x
来源：http://dali.yanxiufei.cn/Article/details/gtvaeyhzox.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tian-w.cn/Article/details/gthgnikeol.html

JS:   const square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtaneuuewf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtvmtiavca.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.c1oappe.top/Article/details/gtjiysfcgm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtkqreexru.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtdwisnjfm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gtqtriuruu.html

[C07] 把函数作为参数传入
来源：http://dali.jyoumei.cn/Article/details/gtfdzhzwpf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jianghu66.top/Article/details/gtqawyknic.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtpniunztb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gtekiofizq.html

TS:   arr.map(String)
来源：http://dali.yanxiufei.cn/Article/details/gtdrjeowrm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fengsongda.top/Article/details/gtylphrpit.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gtphplspfw.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj202588.top/Article/details/gtitrwfclg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gtaevtcypp.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gthxdxerti.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gtzlmygibs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gtqgrmxfrr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtyidxifsc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtlfivgish.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gtkjqepjld.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigufen.top/Article/details/gtcugvgglz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gtpihrcdbh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtkatctdcm.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gtqbilbghr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtssgngixb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtrqidicii.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtbvzslcov.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtguhfssie.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gtthwvoiqp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gtmvoqegqz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtxvhzucjr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gtsdnuowyd.html

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtltjmyzdg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gtsfyscjyp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yueranfly.top/Article/details/gtlsqhvyuj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gthuycyiqg.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gtoqlnuosc.html

Java: 方法内为块级作用域
来源：http://dali.xylfe.cn/Article/details/gtdqfvrtjf.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gttewizqli.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gtscsohbrm.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtacfzzvtb.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gtaxftfxmz.html

Py:   from module import func
来源：http://dali.svipenyu.cn/Article/details/gtttvtpdvh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gtoeyyqtpd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gtqtruyzpz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.bjfxy.top/Article/details/gtpswkxaxi.html

Java: import java.util.List;
来源：http://dali.jinqigufen.top/Article/details/gtxrbrkiuo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenzaomai.com/Article/details/gtdcpgyxou.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aibaodan.cn/Article/details/gtwvfivuep.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtbiklqttq.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxinkj.top/Article/details/gtxfzbswib.html

Py:   (lambda: print("run"))()
来源：http://dali.ivvv.top/Article/details/gtedgviewl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gtfpghfodu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtyroycigw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtpwvmzgbf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.vqdsnc.cn/Article/details/gtuootsrcf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.vqdsnc.cn/Article/details/gtddwplkkr.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtptkydprd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sweek.top/Article/details/gtxchjuwrn.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gttspnxkkc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgjcxbgh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtrtxrcqrc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gtafyrqcdp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtrtcevgqv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtyjqrdsop.html

Go:   func add(a, b int) int
来源：http://dali.yj20258888.top/Article/details/gtfmfcpavt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.haohaochexian.top/Article/details/gtbrtdqjvm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuxming.cn/Article/details/gtbhmlgkmk.html

[C14] 泛型函数
来源：http://dali.hfpthk.cn/Article/details/gtowrxekkr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtkcpnyaxj.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtgkvufqfx.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtbnydzzwo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cucudq.cn/Article/details/gthdythowm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cdnleiting.top/Article/details/gtwpfqerta.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtnfscabge.html

Ruby: # 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtmspitczu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gteiwbvpqg.html

[C15] 解构 / 展开参数
来源：http://dali.hysaishi.cn/Article/details/gttcjrqhcb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gtcjpfmakw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sufxvd.cn/Article/details/gtikirvnik.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtqonlfoyr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gttikjzxzg.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekbtdnjs.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtylynmijw.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtcylifwuh.html

C#:   var (a, b) = pair;
来源：http://dali.ivvv.top/Article/details/gtcpcmehuj.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gtoghutnlk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gtroeqlkvw.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gtyopkanjp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gthrknwksh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrgeqdbv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsitalos.html

Go:   // 无重载：用不同函数名
来源：http://dali.aizwys.cn/Article/details/gtydnxuqgn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gtdtprqtyv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.316326.xyz/Article/details/gtydzydpdh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwtqyycmf.html

D. 数组 / 列表 / 集合
来源：http://dali.sweek.top/Article/details/gtttmsetlx.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmpzoyhbp.html

[D01] 创建数组 / 列表
来源：http://dali.bjfxy.top/Article/details/gtdngrktzo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gttutvwgdo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtupeoepfq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gtjttbapaz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtprkgzyma.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gtrbdctylv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gtvjofajqx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gtkrnkpcdw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigufen.top/Article/details/gtytwximsk.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gtvgkixywy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.vqdsnc.cn/Article/details/gtmhehxabh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtqjnxccci.html

JS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtqarrtrjh.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrymitfp.html

Java: list.add(4);
来源：http://dali.jlsjyb.cn/Article/details/gthvggltem.html

Go:   arr = append(arr, 4)
来源：http://dali.hnqzz.top/Article/details/gtslkjdmhs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigufen.top/Article/details/gtxccccozy.html

C#:   list.Add(4);
来源：http://dali.hammf.cn/Article/details/gtdvvdgamf.html

[D03] 在指定位置插入元素
来源：http://dali.andypj.xyz/Article/details/gtzdsewqvd.html

Py:   arr.insert(0, 0)
来源：http://dali.316326.xyz/Article/details/gtusteuoxn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dianchejie.cn/Article/details/gtdbkbujbb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gtlqrdfddm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtrmdfuiuz.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtkvlwhvtn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gtlqssocil.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guowangkeji.top/Article/details/gtfxjbkvjy.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gthizwufrp.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtqtcelcjz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daxiang520.top/Article/details/gteymbbaoo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hammf.cn/Article/details/gtiklpxbiw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gtqacwaycd.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtushcbnkf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gtyeayztyk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gturylfbhx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gttqpyxcyd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuxming.cn/Article/details/gtdluhwltn.html

[D05] 访问与修改元素
来源：http://dali.sufxvd.cn/Article/details/gtznqvonao.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtntnendmt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtgnphcxqu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtudotrecy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gtaoxztekw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gtolktvgmy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnyfvtou.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtebzzorqj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtzshzifqu.html

[D06] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gtxpydgodp.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtqtreuksh.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtwmmjlvtl.html

JS:   arr.length
来源：http://dali.yonumen.top/Article/details/gtjzsgykyn.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtofhylsni.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gtdngcnndu.html

Go:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtohzypqqk.html

Ruby: arr.length; arr.size
来源：http://dali.jianghu66.top/Article/details/gtsdkoftei.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gtevbqnctx.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtbctlxswk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gteredgmmf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtlgphajgz.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtzjlkzyff.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfzqenqm.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtgguvcudr.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gtktgydsvb.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gtwhxllwss.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtcqgaouvt.html

[D08] 合并两个数组
来源：http://dali.feifeiyinyue.top/Article/details/gtebyhrlcz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gtlrobtrgw.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjpdrapk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gtrgxbqens.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtroefqtxg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gtbgpffbjo.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gtdilpnegt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtxctevfga.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbupizcmj.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gtlarudayq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gthpghoqhe.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtktwbbjwx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbznuwolh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gthbtswwia.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtdvjwtrdz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtyadrepxp.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtrajhzipp.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gtnxfoyhnb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gthsbmydxn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gtdmgesbox.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gtjevwmmod.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtlttwtlae.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtyrknkzig.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.bjfxy.top/Article/details/gtuhlqefzl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gturwzbjtv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvoketwb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gtrcjhcxwi.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gtsmjisnft.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gticbzecux.html

PHP:  array_reverse($arr);
来源：http://dali.fengsongda.top/Article/details/gtsgltwibt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcryugndh.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtxsreesnt.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gtnkgimgfd.html

Go:   slices.Reverse(arr)
来源：http://dali.redwolf501.top/Article/details/gtxxpvtcop.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gtwdrvenah.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjezomoc.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangkeji.top/Article/details/gthejxaahm.html

Py:   arr.index(x);  x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtziqkmx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtczepcsjz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtltbckyap.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtdgedmwmu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gthuphluzc.html

Go:   slices.Index(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtbsjcpigk.html

Ruby: arr.index(x)
来源：http://dali.havefunace.top/Article/details/gtjmlsffwy.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gtclylnwhq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gtdnqfovdw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gttygivxcl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.9152youxi.cn/Article/details/gtjkhxwdvc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyzqpouj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gtpznirwgl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gtmwxzpspy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gtlfyqodyw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gtdgupwflu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtgpssrdah.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gtktfhaazw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guannengcc.top/Article/details/gtdwqhxbif.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gtuqciprcm.html

JS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtxniuskkv.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtevrwletv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtwymlwbau.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtwtxcrtfh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtcevznkqr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gtyyvxaaay.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjipgzhy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtzrblenlm.html

PHP:  array_unique($arr);
来源：http://dali.yj202588.top/Article/details/gtnfnjnbtj.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtjrkxulun.html

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtlqkswurh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gtxmqnwdhb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gtparccpvy.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gtzkeejtis.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gtwxznpvtc.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gthbomlrtg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtzbxhrhsd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtpxrilluc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtdhmeywfh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtiavgueqm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nwbrower.top/Article/details/gtmrgmokff.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrmfjlhw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gtdagamhdh.html

C#:   list.Sum();  list.Average()
来源：http://dali.tian-w.cn/Article/details/gtwzzlbhze.html

[D17] 最大值与最小值
来源：http://dali.ivvv.top/Article/details/gteadtskdo.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gthgxbbfoc.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gtsaqbgoyq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtrjpqricq.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbaawxet.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gtbwscxpzc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xziqi.cn/Article/details/gtzwixawvx.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gtecfxlzud.html

C#:   list.Max();  list.Min()
来源：http://dali.cqqwz.cn/Article/details/gtsmkafbsl.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gtuujfcwfc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gtseukfufh.html

PHP:  array_merge(...$nested);
来源：http://dali.hysaishi.cn/Article/details/gtpomvhrvf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gthtjevkdz.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gtavwqzjvz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfahgfzan.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtryxhwyaf.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtheiiifyq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yongpay.top/Article/details/gtwscopgxi.html


<!-- 参考信息 -->