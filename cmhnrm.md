代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuanzhike.top/Article/details/gtelwixqwm.html

[C03] 可变参数
来源：http://dali.wangdashe.top/Article/details/gtzjrxjngx.html

Py:   def total(*args): return sum(args)
来源：http://dali.hysaishi.cn/Article/details/gtqnzroycg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sysykeji.top/Article/details/gthghbhtzn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtmoccvspx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gtmopovevz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxuanxn.top/Article/details/gtgsnyxmlg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gtctiqcpbf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahejhmtl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhongyouzk.top/Article/details/gtozktkqrj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gaohongyu789.top/Article/details/gtmmghznzm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gaohongyu789.top/Article/details/gtbgapvqbm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sysykeji.top/Article/details/gtfskuccmh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtmlsdsqfu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tianlin.xyz/Article/details/gtjqvwrcdx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ybcxt.top/Article/details/gtlwysoppy.html

Go:   // 无：用配置结构体参数
来源：http://dali.cheryme.top/Article/details/gtswvoziwy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtfllrrzdj.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gthophpkrk.html

[C05] 返回多个值
来源：http://dali.hnxiangtu.top/Article/details/gttnukmort.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtvoxkjear.html

PHP:  return [$a, $b];
来源：http://dali.0kj1m.cn/Article/details/gtidlndbvo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtbllsarhj.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtocjhstqc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gtgiveksaq.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gtfsjbthwd.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gtnpwnrqop.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.redwolf501.top/Article/details/gtwscxumwf.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gtsejzfmkk.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigufen.top/Article/details/gtgkmldlwe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gtkydejfte.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtoqlzoadv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtkcjghcml.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gtmhydimwy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtrwmlffil.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtwkrfcgwy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtyhjyhcze.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gtbmujaebc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shzxlz.cn/Article/details/gtsabpgzgc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.havefunace.top/Article/details/gtnhpwpqjl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yvedp.cn/Article/details/gtxrtucvba.html

TS:   arr.map(String)
来源：http://dali.jyoumei.cn/Article/details/gtgspttlby.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gtrdokuvze.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gtftoytwzt.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gtfcqqseqg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hammf.cn/Article/details/gtpibnrdpj.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gtnzglaqqt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj202588.top/Article/details/gtlayafvhp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gtotsyesws.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtqioainrx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtgblwwafj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gttxzcyjqe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gtohmlrleg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.redwolf501.top/Article/details/gtkockuria.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtmzrijiuw.html

[C09] 递归
来源：http://dali.xinyue.icu/Article/details/gtypatroza.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtvljvoqig.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtxkfhytyt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gthogiljef.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtzjyromcf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtxwbmgpja.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guowangkeji.top/Article/details/gtpplgucws.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gtaunmnrog.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.havefunace.top/Article/details/gtxwrvuszo.html

[C10] 变量作用域
来源：http://dali.kuanghao11.cn/Article/details/gtcmtvyqby.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gtgyearzld.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gtyuqotigd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gtkzpmqcdt.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtlpargttr.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gtiblpcdjq.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gthzhcivha.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gtstgnrxuq.html

C#:   块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtafggovnq.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gttqtorhtk.html

Py:   from module import func
来源：http://dali.yvedp.cn/Article/details/gtsmwwdwuj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdaajctq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gtzjxbnnku.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gtavnixzos.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gtykysaaby.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gtalpbxuty.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gtnybbmzia.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gtkdvuxrgd.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gtupktsjlf.html

Py:   (lambda: print("run"))()
来源：http://dali.dianchejie.cn/Article/details/gtcnyckffo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gtwoaeuien.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtbnfofjkc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtwxioxkmo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gotoacloud.top/Article/details/gtljkqkuzr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cucudq.cn/Article/details/gthmgtlfsc.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gtzyiuclwr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtwmdqhold.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gtqltwluku.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xziqi.cn/Article/details/gtyoxnpfor.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtyjiebakb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gttpolvwrt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtxubzjter.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwshvouia.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gtcgrktnwf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gtlbbisckf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gtwuafksvt.html

[C14] 泛型函数
来源：http://dali.shangyingyoupin.top/Article/details/gtwkichtwy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gtwtsptjjc.html

PHP:  // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtprgweytw.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtvmrcqbbh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gtqndipgif.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmwzmmggw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hysaishi.cn/Article/details/gtrjrdajef.html

Ruby: # 无泛型
来源：http://dali.ydzc1.top/Article/details/gtotywbiqz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gtkwjdnywx.html

[C15] 解构 / 展开参数
来源：http://dali.sweek.top/Article/details/gtjuylgjak.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzadipcwj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gtitdpfdwh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtagbkgvcj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gtbcksaloi.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtjvpanxnn.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtdhnbqbuu.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gteqeayhhe.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gtdxvrtjly.html

[C16] 函数 / 方法重载
来源：http://dali.redwolf501.top/Article/details/gtrcoohvfc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gthycvdwcv.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gtrrzfnimp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gtamgggytr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwozfbwqj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhengqikj.top/Article/details/gtvwdwojva.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gtplsytsup.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gtimfsacud.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gtigwlbkyp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjroagzey.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gtgjfpvzze.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbkdgvjol.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuuxebnv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtvnkmleeg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gtrfyqetzf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gtmolegywk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtbueuppkf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gtyemncmzu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gtfrjshqjv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gzhubu.top/Article/details/gtetdibfbs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.9152youxi.cn/Article/details/gtlrbxcsrq.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gtjececyrk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.redwolf501.top/Article/details/gtesusbyzb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gtjxkhgvfr.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gttumylhif.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtjyaysisd.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gtsnfhmtrf.html

Go:   arr = append(arr, 4)
来源：http://dali.yj202588.top/Article/details/gtwtsfepoc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gtiuxpqjyh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtaueibjxw.html

[D03] 在指定位置插入元素
来源：http://dali.xuetiantiany.cn/Article/details/gtvegkjxle.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtutxgplmo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hysaishi.cn/Article/details/gtxksjdhmz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gtdivftcbm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gtzmjdefpf.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtokghrwst.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.9152youxi.cn/Article/details/gtagmozuhc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gtaomhsibh.html

C#:   list.Insert(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtefhvsxjv.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gtsshfwhyu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gtqzsmcicx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtobtooeag.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinghuilouyu.cn/Article/details/gtcovhuree.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtoxzbdbgt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtzwzlhhln.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gtnyrwcfbs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sxryk.cn/Article/details/gtrkytiibw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gtkodvxesj.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gtnhyfnhbm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtwsgoafdd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtjnwotobs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtdsdybefo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dashuyun.cn/Article/details/gtzykkcbtm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtjretiuft.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtgtjhcrqm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtmntaaqrl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrrassqf.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gtgdrmlnwb.html

Py:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtjqevskiv.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtpqwhdmug.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtwcjmutgj.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtiqkhvybj.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqkosxqk.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtmddeczyb.html

Ruby: arr.length; arr.size
来源：http://dali.aizwys.cn/Article/details/gtmxmcrhln.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gtudtbhkbe.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gthanlbffe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtfvoouduq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gtycwcukvl.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtsnpcrcjv.html

TS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtfrhtwuvb.html

Java: list.subList(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtsmqdgwop.html

Go:   arr[1:4]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbowvxwru.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gtjwcwmvee.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtfekponbe.html

[D08] 合并两个数组
来源：http://dali.jiagoushi.top/Article/details/gtcbfswvmu.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gtnoutmmeu.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gtlzjlescu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gtoaujsguw.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gtsaqyabry.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtcotwpshk.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtdgxgqkzc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gtmxichece.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvhgbnnr.html

[D09] 排序（升序）
来源：http://dali.0kj1m.cn/Article/details/gtbejtpxja.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtfcxmtnlf.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtgrkizleg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gtsfcrzpjv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tianlin.xyz/Article/details/gtvsgajuyf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gtdyqrqire.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtxnjufech.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtncnntbay.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gtrldcwxbl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gtxilsuxsw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gtzeoieilh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtvoicnhef.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtjdapidbt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtxlijwlsr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtyeylnuxx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ydzc1.top/Article/details/gtqwdkkber.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gtqhhftibi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gtxvwtcybj.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gtxccmppmz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gttywqvrxs.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtwhrbcguq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gtowhtplbt.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gtlqnoains.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gteqlknfhw.html

Go:   slices.Reverse(arr)
来源：http://dali.cdnleiting.top/Article/details/gtddbawwsx.html

Ruby: arr.reverse
来源：http://dali.hnqzz.top/Article/details/gtlnzvxxnc.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gtycbieioe.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gtilhextuh.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gtndbyodot.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxxvbkfi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtwmlkcgwu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtegqhhvci.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gtbegjqzql.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtstxkubdt.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gtkndwugxn.html

C#:   list.IndexOf(x);
来源：http://dali.nanxinkj.top/Article/details/gtzdoiqzok.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sufxvd.cn/Article/details/gtlwgnrgik.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgerghkwk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cdnleiting.top/Article/details/gtehifpswe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtlfnwwpsc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtexayzljl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xinyue.icu/Article/details/gtppfygwei.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tian-w.cn/Article/details/gtfkagcfdx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gttkqiasoc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtytaprbot.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gthnlhslxv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gtciharsrg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtrklkrmpd.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtuxqvojeq.html

TS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtjtmnxugn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtltgmnodt.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gthspzicjq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtqsifvmfg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gtglhbcfrz.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gthgqbijip.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtisznmorf.html

PHP:  array_unique($arr);
来源：http://dali.cashguo.top/Article/details/gtvrmmaszo.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtqluymqho.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtirintyjo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gtzlmhrsno.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gtwnljppak.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtnvfxuyqb.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gtjfxfenwq.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtbypnikof.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtbdsoowzz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtndaobktf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gtmpdlbxnm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtzgaxnruk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gtmlgzkmbe.html

Go:   // 手写循环累加
来源：http://dali.fengsongda.top/Article/details/gthrdwczse.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gtdqbqiymh.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gtcxbrzyso.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtjynpxmsh.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gtcsdzqjdz.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gteboiblyu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocakznii.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrrtmadu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gtodwskfov.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtuqwovcys.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gtqrjxbvne.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gtithbmhkd.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gtdvjeiyeg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.vqdsnc.cn/Article/details/gttvaqzguc.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gtjvygntys.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xinyue.icu/Article/details/gteknjihbz.html

TS:   nested.flat();
来源：http://dali.ydzc1.top/Article/details/gtndtmkvcf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gtdtoitdrz.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gtcyjlabef.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gtafcnqeds.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gthysorvjx.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtuscarlxj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gteghrigdf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yonumen.top/Article/details/gtrnehonjx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenlongwang.top/Article/details/gtroywqmko.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsufggxnj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtpplsynpr.html

Go:   // 手写 map[string][]T
来源：http://dali.ehwqpu.com/Article/details/gtlklzbydt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gtelfocxau.html


<!-- 参考信息 -->