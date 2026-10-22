代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllyscdbn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtghvjqucs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gtqppvfyni.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gtckmowzbm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shzxlz.cn/Article/details/gtmsrhyrrf.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gttxiwdtdl.html

Py:   def total(*args): return sum(args)
来源：http://dali.aizwys.cn/Article/details/gtoppcgxhh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sysykeji.top/Article/details/gtznzbjuei.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtaztyfzze.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gtidkjnmba.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnqzz.top/Article/details/gthqutxwcm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.9152youxi.cn/Article/details/gtmtajrjxp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gtphgsqpqh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuxming.cn/Article/details/gttdmbtqmx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.feifeiyinyue.top/Article/details/gtajjbestt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.snrcjt.cn/Article/details/gtngdkrizj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fzhhl.top/Article/details/gtvzeiwuwx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrbnyarjb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tianlin.xyz/Article/details/gtfoddcjus.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwbdupyz.html

Go:   // 无：用配置结构体参数
来源：http://dali.iojbl.cn/Article/details/gtorxmxagj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtnekiynjr.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtnclkuyrv.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gtqlxostjm.html

Py:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtauskynqi.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gtmnhhjxub.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cheryme.top/Article/details/gtzsxybdcy.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtsuumiqij.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gtyljegqny.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gtztwyscsw.html

Ruby: return a, b
来源：http://dali.jiagoushi.top/Article/details/gtaozyzshr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gaohongyu789.top/Article/details/gtksodhigz.html

[C06] 匿名函数 / lambda
来源：http://dali.tanke756.top/Article/details/gtteqakfzw.html

Py:   square = lambda x: x * x
来源：http://dali.c1oappe.top/Article/details/gtdnenikkv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gtvqlngwmw.html

JS:   const square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtcvorovxs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtysozbryy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gtrkoemxth.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbjudufo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aizwys.cn/Article/details/gtvnvhavyn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtsgrpbgib.html

[C07] 把函数作为参数传入
来源：http://dali.nwbrower.top/Article/details/gtirxasrje.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gtyuaxipam.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtwyoyzese.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gtzsplafzz.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtybxlapto.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gtzqijgygg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gthjinihgj.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gtoekmklqh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gtetpgtpfu.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gttrsbnnlj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gtzteffhgv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xziqi.cn/Article/details/gtkkkhemkv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtfhdrmens.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjxncpqo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.bjfxy.top/Article/details/gtbehfbysl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gtmeekjdlf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangshuangyany.cn/Article/details/gtuyxyaxjx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gthoohfgoa.html

[C09] 递归
来源：http://dali.yangfankeji.com/Article/details/gtmdanvdem.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtntkylagh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gteokmhdqc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtaahtqwio.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gttnakijfn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtqtuksmja.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gtboesbqbh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gtkytfawzp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangdashe.top/Article/details/gtiloxuiid.html

[C10] 变量作用域
来源：http://dali.nwbrower.top/Article/details/gtvwdzacqg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gtawcywlnv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtmiwmgfai.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.meibo888.top/Article/details/gtywrpueoa.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gtrrxtjukv.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtjuhttqnj.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gtrrfejwxn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.mhx1999.top/Article/details/gtvqacbggl.html

C#:   块级作用域
来源：http://dali.guannengcc.top/Article/details/gtbonhqfdz.html

[C11] 模块导入与导出
来源：http://dali.xinyue.icu/Article/details/gtmxdmnsgi.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gtdztwkxls.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gtpcbpyvzs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gtusjcthhs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqciornf.html

Java: import java.util.List;
来源：http://dali.yvedp.cn/Article/details/gtoowgfvdv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gtootzobzu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gttsxvlfep.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclpuruzb.html

[C12] 立即执行函数 IIFE
来源：http://dali.daria6918.cn/Article/details/gtzjnablsq.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gtdbjpfmwj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gtbtnxwjhl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtqgstlrfb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gthrhyqvfg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.meibo888.top/Article/details/gtkqfgblfw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gttapmtkig.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gtsqysipfu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtrsmxcmka.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtqjhvazti.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jyoumei.cn/Article/details/gttllxsfci.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtenhwykkp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gttydrmmpv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtdqtoawgz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtomccgdvm.html

Go:   func add(a, b int) int
来源：http://dali.svipenyu.cn/Article/details/gtxhxbacgn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gtgibahhfe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gthtfyfgiz.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gtohbqzjcv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gtkoznovbh.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtmvoqbmyb.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtzurdjzek.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hywenlv.cn/Article/details/gtadygckny.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gtozbsnrpy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gtnzfjpzzh.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gtcseinkts.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gthbfptszg.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gtmrbdjicb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtzpwqibga.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gtxorowric.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtfkgqryum.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gthwerexgl.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gtovgmeoor.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtfgcbghov.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gthayzxtrg.html

C#:   var (a, b) = pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtjluwykqk.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gtadeeotep.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gtkgejgoqv.html

PHP:  // 无重载
来源：http://dali.yuanzhike.top/Article/details/gtgldnpfzo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gtelwdxzta.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gtwcqmytib.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gtotysttvd.html

Go:   // 无重载：用不同函数名
来源：http://dali.ivvv.top/Article/details/gtwewewkcv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgfzy.top/Article/details/gtsxrcrswn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjgabkfzy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzxjiexy.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gtyvpvwrhj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtiqufxvfr.html

[D01] 创建数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtdlktqavj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtuezbqioe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gteszieood.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtuzomzebu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gttdktagwo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gtbtnovmsl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gtyktalcxw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgfzy.top/Article/details/gtfmfmhvzw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gtjcwbycrk.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gtjaceloff.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gtbgohaxzy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xylfe.cn/Article/details/gtobqypjei.html

JS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnteggdzf.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gtqozzfrdi.html

Java: list.add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtsxlttq.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gtwsjpoiti.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gtsaprpefy.html

C#:   list.Add(4);
来源：http://dali.shuidangran.top/Article/details/gtogfwvtci.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gtizxidtwq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcibefkpv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gtuziuhcli.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewgucosh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtthiseptf.html

Java: list.add(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtsjcjmboh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gtpwcyyntz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gotoacloud.top/Article/details/gtgaxndnfj.html

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtzlyhdepa.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gtlrvmrwsm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pycfn.com/Article/details/gtuojljcym.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cqqwz.cn/Article/details/gtkxgmndxr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gtctvcgzbx.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gtiaxtyvek.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gtpvkdgiun.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gtycglxyle.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gtbskklhpu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pengpengdd.cyou/Article/details/gtxlsziugi.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gtzzhkbwyw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtudqqwndu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtgilafmlp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtkzbvshvr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gtxlnbjtiq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gtwwjcvmtq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtrcmzunzu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoknvceu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtpfoauvyn.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtybxtmatu.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gttqbpngas.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtwloeabfg.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtpqdqfozz.html

TS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtrbgtknxg.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gtedneyioh.html

Go:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtrokelgjy.html

Ruby: arr.length; arr.size
来源：http://dali.hywenlv.cn/Article/details/gtmwqssmlx.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gtacouyxsq.html

[D07] 切片 / 取子数组
来源：http://dali.pycfn.com/Article/details/gtptzjkoum.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gtoeojafko.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fzhhl.top/Article/details/gtillmsdsi.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtfhdyadqn.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtbdzcoiqz.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtvkjzxeaw.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gtykzomohu.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gtoaocidpb.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangdashe.top/Article/details/gtehfzjize.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtpbbsejmk.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtpatbozxb.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gtcgumcptz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gttdidkyei.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtkynupcev.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gtyobcrkjr.html

Go:   append(a, b...)
来源：http://dali.xuetiantiany.cn/Article/details/gttuyuzoin.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtymrkpusa.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gthuxehreu.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gtznapuqwr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtwjpmdolc.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gtycaewoto.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gtbyifnrxx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gtxjvgokvw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.haohaochexian.top/Article/details/gtentthqbw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrtxzpvd.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtgdmipiph.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gtemetpzjt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gtedqgeigm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gtdyahuyrh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtuvnhuefg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gtbhtuwtes.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtuoybnapy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhongyouzk.top/Article/details/gthytukyyl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gtvtxwqerr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hysaishi.cn/Article/details/gthbjpgahu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipoggnwt.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gtrdwhqmuo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gtsthblifg.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gticvdmwyl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gtgqygrzal.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gtgabnybxw.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gtysupbmky.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gtnvjqzlsu.html

Ruby: arr.reverse
来源：http://dali.zhixingplan.top/Article/details/gtjsbsxpnw.html

C#:   list.Reverse();
来源：http://dali.fzhhl.top/Article/details/gtckgxaizi.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gtinkcgscu.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gtftptmgcn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuxming.cn/Article/details/gtdzxngwbq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gthvyujmkc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhfxsylc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gtoknoutxu.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtdsncbxxj.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtkqofnjkx.html

C#:   list.IndexOf(x);
来源：http://dali.gzhubu.top/Article/details/gtjunjmvon.html

[D13] 过滤（保留满足条件的）
来源：http://dali.haohaochexian.top/Article/details/gtwyxfhpmx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gteexjkcxm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtirgrzabi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtcyhxvwcc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtcmrybaei.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gtfhfjymzk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuxming.cn/Article/details/gtqckfyjdt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuxming.cn/Article/details/gtizsvkpax.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtzvwberch.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sxryk.cn/Article/details/gtkwfitarv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gthyytlbyt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtfcnfkuqf.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtjdqxdubn.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gttowillmm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tianlin.xyz/Article/details/gtumansfbr.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtilmtmgee.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtjejmexbn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtthrlczlk.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gtajtpuvev.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gtksiyerue.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gtlvyuvjwd.html

JS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtgnktympg.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtvuufbtpu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gtrpvwvbdv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuetiantiany.cn/Article/details/gtjfnqmzfz.html

Ruby: arr.uniq
来源：http://dali.vqdsnc.cn/Article/details/gtxyrfcmnx.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gtqddachtz.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gtgzhbmcms.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gttwrwzjpg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjzrmszf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtgagfsikl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gtjtywyoit.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gtiaplkpfu.html

Go:   // 手写循环累加
来源：http://dali.gotoacloud.top/Article/details/gtuxuufdem.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xziqi.cn/Article/details/gtphqqrxns.html

C#:   list.Sum();  list.Average()
来源：http://dali.yongpay.top/Article/details/gtzzdnjjzu.html

[D17] 最大值与最小值
来源：http://dali.daria6918.cn/Article/details/gtnvdvaymz.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gtdprwwjut.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtwxabwtqu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtdmpnpypr.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gttdarlquk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtdtrmfmck.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtpxrzyjbe.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgufenzy.top/Article/details/gtzdxqdrbu.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gtteknxyzu.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gtymhyvlnp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtanvoslpg.html

PHP:  array_merge(...$nested);
来源：http://dali.chenjidiqi.icu/Article/details/gtwaigfarq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xinyue.icu/Article/details/gtnrnwyujb.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gtymrokrpx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zdqjudy.top/Article/details/gttwmwmtry.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gtpbbsebqq.html

Ruby: nested.flatten
来源：http://dali.hnqzz.top/Article/details/gtruihpnnx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gtihhmlupn.html

[D19] 按字段分组
来源：http://dali.hongshengwenyu.top/Article/details/gtcdwesdps.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gtpnnhokks.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gtqskzwcwb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gtmqvpjykq.html


<!-- 参考信息 -->