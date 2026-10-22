代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtrpffegld.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhongyouzk.top/Article/details/gttvgzsfhd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ehwqpu.com/Article/details/gtshfjtbtf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gteagjkdav.html

[C02] 默认参数
来源：http://dali.birdmap.top/Article/details/gttnhiclfa.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtxtrvhwoi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gtsotgzfld.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtqviafhnx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtrupuewpk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.bjfxy.top/Article/details/gtwzdkgkhu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fengsongda.top/Article/details/gtggucdsdz.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gtfbhasyof.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fzhhl.top/Article/details/gtwyltwxkv.html

[C03] 可变参数
来源：http://dali.mhx1999.top/Article/details/gtycvjjhzb.html

Py:   def total(*args): return sum(args)
来源：http://dali.tian-w.cn/Article/details/gtjrcuxlrq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.mhx1999.top/Article/details/gtowuxtkzm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqnbisio.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtotqkewtc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pengpengdd.cyou/Article/details/gthtzxzewl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jyoumei.cn/Article/details/gtshirkbil.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxuanxn.top/Article/details/gtkvqngcbq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pengpengdd.cyou/Article/details/gtlswfgpzd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tianlin.xyz/Article/details/gtupshmznj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gtzjwriytp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.kuanghao11.cn/Article/details/gtushayrqv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtnmlzdmkj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxinkj.top/Article/details/gtaimevvct.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigfzy.top/Article/details/gtxtprfmve.html

Go:   // 无：用配置结构体参数
来源：http://dali.haohaochexian.top/Article/details/gtflszwcmn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtjrfynoaw.html

C#:   f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtccbrtmsl.html

[C05] 返回多个值
来源：http://dali.daxiang520.top/Article/details/gtmxagipaz.html

Py:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtippzyboq.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gtwinavhrx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pycfn.com/Article/details/gtquvsksvz.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrdzmbix.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gtafkjjcxy.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtjbhilryu.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gtlbrhkbma.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hammf.cn/Article/details/gtfwbicdfy.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gtguwoapjk.html

Py:   square = lambda x: x * x
来源：http://dali.zycfv.cn/Article/details/gtoqnwisgl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gtxzgdrrns.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtyldjvpek.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtkwgfhffa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtzloyruop.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gtzcnlkmem.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gtqmpjqtlq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtaokniwgg.html

[C07] 把函数作为参数传入
来源：http://dali.zdqjudy.top/Article/details/gtjwpgrcvf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtxwshvctg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gtbtenufiw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gtvemzuevq.html

TS:   arr.map(String)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclnglntj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.0kj1m.cn/Article/details/gtspjpmutz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jiagoushi.top/Article/details/gtsjmnzajj.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gtyzzjufuz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yvedp.cn/Article/details/gtgwvvaggl.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gtphweymbq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gogol.net.cn/Article/details/gtdxzyirdo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gtjaigimoz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtxroatfwm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmffxyuhh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangshuangyany.cn/Article/details/gtzvrptvdw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangdashe.top/Article/details/gtwvwuzsfo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xylfe.cn/Article/details/gtezivwhiy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtnsifjiwv.html

[C09] 递归
来源：http://dali.fengsongda.top/Article/details/gtdhsabbgy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtecrsqwcs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shuidangran.top/Article/details/gttkvgsahq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtyppqbgzq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtpvxyinsz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmvfbmvnf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gtpqxwaicf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtdchqkvhv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtjpvxzgxr.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gtesddpeuo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258888.top/Article/details/gtzymjexbn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuetiantiany.cn/Article/details/gtlkayexyt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtcabksmep.html

TS:   同 JS
来源：http://dali.birdmap.top/Article/details/gtaovnubly.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtlgoekkna.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gtbluwmcqx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gtpgozaxdj.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtqrdbqsex.html

[C11] 模块导入与导出
来源：http://dali.xylfe.cn/Article/details/gtpamtkopf.html

Py:   from module import func
来源：http://dali.fzhhl.top/Article/details/gtskpyvzpp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gthaerlwqz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gtxkbghday.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gtrbqadsvu.html

Java: import java.util.List;
来源：http://dali.jqgfzy.top/Article/details/gtbasngzqj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangdashe.top/Article/details/gthjajpdsf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxinkj.top/Article/details/gthghujwhg.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gtafruvpqa.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gtntmrmjzd.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gtqbrbjwbz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuanzx.com/Article/details/gtrlshcqvt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtoidsezxz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtljflllex.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gaohongyu789.top/Article/details/gtspxqpwjn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gtsryqpzma.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gttkzbopom.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.bjfxy.top/Article/details/gtujqaigff.html

[C13] 类型声明 / 类型注解
来源：http://dali.cdnleiting.top/Article/details/gtrwnxhyhu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtllzjhlsy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtxfvdpvhr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gtxbepqbzo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtwjrfmcis.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gttqvcrhzw.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gtzcngurfg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gtvgtmdbio.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxuanxn.top/Article/details/gtwkpieicm.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gtqqljnoso.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gtndykqzdb.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtudeobpvx.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtijgejnwv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gtkrlmhdbm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtitkdxirj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cheryme.top/Article/details/gtzqeayxne.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gtzimmrkvc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.havefunace.top/Article/details/gtinusqorh.html

[C15] 解构 / 展开参数
来源：http://dali.cheryme.top/Article/details/gtkeladeva.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gtcklpgodv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gttaafvzws.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtsckgdmbd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gthbvuzmwg.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gtjhrdhdnq.html

Go:   // 无解构
来源：http://dali.ivvv.top/Article/details/gtbxzgxfyc.html

Ruby: a, b = pair
来源：http://dali.ehwqpu.com/Article/details/gtftejjsus.html

C#:   var (a, b) = pair;
来源：http://dali.hywenlv.cn/Article/details/gtefacpsic.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gtzdgyngzi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gtwlvyewsi.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gttekyqybd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenjidiqi.icu/Article/details/gthrlubimh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmzzafda.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtcgsfgrrq.html

Go:   // 无重载：用不同函数名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsffcozs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gthwqwheyn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gteehnxybr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzlewfudw.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgufenzy.top/Article/details/gthwwnjjkl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqqvyltsp.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtjhqtrtrj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pycfn.com/Article/details/gtforcfkcm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gtupwormzv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnqzz.top/Article/details/gtaivtyjao.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cqqwz.cn/Article/details/gttnutgqwf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gtktckbtxw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gtaxswxxak.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gotoacloud.top/Article/details/gtvfeubmco.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gtfqmqytyp.html

[D02] 追加元素到末尾
来源：http://dali.nanxuanxn.top/Article/details/gtnvdxlofm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwlpyejw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gtthdjdtic.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gttxiaqjak.html

TS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gteyvrrdbg.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtsallibvy.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gtixtpiatk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gtumqdgtki.html

C#:   list.Add(4);
来源：http://dali.xinyue.icu/Article/details/gttxtcojek.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gtimdfxsjy.html

Py:   arr.insert(0, 0)
来源：http://dali.ivvv.top/Article/details/gtnilcpnfi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gtvludfheh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gtazkjbrhm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtdzdyxgbx.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtaythkdma.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtnmxgiptw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gtajhhgftr.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtckxgoexk.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtvacygeca.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yangfankeji.com/Article/details/gtgbxpmlpo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtqtbqjvvo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gteudrjraf.html

TS:   arr.splice(0, 1);
来源：http://dali.redwolf501.top/Article/details/gtzklmqsyz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtciknhohv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gtujzrvodb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhdapbpu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcybyuhf.html

[D05] 访问与修改元素
来源：http://dali.jiagoushi.top/Article/details/gtwrltnykm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtsgxyacze.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtxrngpmod.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtjutodikx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yanxiufei.cn/Article/details/gtuflwgnfo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gtwspshhdl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtbgvguusu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtjcnumwfb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtobyzrlyl.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtvbfmizpj.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtfigkrkry.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gtmyoruaaq.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtlgvycyah.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gttcmeseqk.html

Java: list.size();
来源：http://dali.guowangkeji.top/Article/details/gtxjlnwhfm.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtadwmbqaf.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gtfjkjkhzl.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gteddytlzz.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gtwoauexgv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtktjbkqro.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gtfufkugso.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtdjpaxahh.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtfndsiaax.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtfobrbgvi.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gttrifkjpy.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtgippjogr.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gtspnfbxne.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsowjnpx.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gtsjgmqhrh.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gtgkgpapzg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gtdgdatyam.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gtbabjufxq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gtbunbwyhr.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gtwgyrqjxa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gtugrsgkaa.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtlkyofumv.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gtxqffxxra.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtzorfitmc.html

PHP:  sort($arr);
来源：http://dali.316326.xyz/Article/details/gtotpigjfd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pycfn.com/Article/details/gteyodyjlr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gttopwsnld.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gtepsssfta.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtnfcmyxdu.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtekpsueuy.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gtdhiqxlvq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gtbhakoehw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gtelrjussx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtujwlmfxr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtpfcociix.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtbsuthmti.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fzhhl.top/Article/details/gtznryeoas.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhengqikj.top/Article/details/gtifbtqrpv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuxming.cn/Article/details/gtapffrgkz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmfowkzr.html

[D11] 反转数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsmmjnvw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangdashe.top/Article/details/gtvmvnknei.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gturepqgzh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gtuetsdkwc.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtotxwvpbr.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gtmdkylyzq.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gtgrjbqrav.html

Ruby: arr.reverse
来源：http://dali.havefunace.top/Article/details/gtkjkmhgue.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtyijnybfr.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gthnjstcnc.html

Py:   arr.index(x);  x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvsashou.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gtoikzicue.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtuzedirvh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gtxgkesgah.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gttryitimq.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtgjmhfwna.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtfcjucmco.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gtxuwpwtug.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gtoltrysbb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jianghu66.top/Article/details/gtzhsgzjxh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gttzxsvmey.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtaqbmjagf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtkqzdmerl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yongpay.top/Article/details/gtodgqwhie.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gtewtrlgcg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gtiqmkoyfp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gturjrgqfd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gtzbunznov.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gtmsifotpk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtvtclmwyh.html

JS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtxtxqiedy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtlzeonyrm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gtsgcmxtnq.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtvjjwetak.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gthojrxwqf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gtjzzvviaf.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbtkotad.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtiqfiyxul.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gtyujzteyg.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtswqukzfa.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtpqlaqnxy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gtlziuuytg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gtasnbhact.html

Ruby: arr.uniq
来源：http://dali.cdnleiting.top/Article/details/gtrncenspa.html

C#:   list.Distinct().ToList()
来源：http://dali.hysaishi.cn/Article/details/gtdynfcanh.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gtrrqkvblf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gtgeegldns.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtanllpige.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtmwpwzmky.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtcboeprfs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fengsongda.top/Article/details/gtrypkroyb.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gtfpxlohll.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gtfddcwfgo.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gthnkktcai.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gtrwaxayeh.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtubdiukhq.html

PHP:  max($arr);  min($arr);
来源：http://dali.pycfn.com/Article/details/gthctbzwty.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtkyzjlhjr.html

TS:   Math.max(...arr);
来源：http://dali.yanxiufei.cn/Article/details/gtxhudfwsa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gtyjxrolwx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cheryme.top/Article/details/gttvvcmydx.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gtklhctvsi.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gtvdbqgliz.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gtxgbjtxni.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gtfliuqudj.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gtfvusholc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gtjcmkboou.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gtefxpznok.html


<!-- 参考信息 -->