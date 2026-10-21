代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtjafbmlmz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtyquhrvub.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gtfmpzlicx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aibaodan.cn/Article/details/gtfvvzkdym.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gtcgbbjzwv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gtebfqitap.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsdobsjq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aizwys.cn/Article/details/gtbhidfcjs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ehwqpu.com/Article/details/gtexadihrm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtnohriroz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sweek.top/Article/details/gtbxfjxsbl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyrydvyd.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gtihzrlnvi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtofciqclt.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtnvuykkkn.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gtgidktqwq.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtbfyydxbz.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gtciuynhvo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ydzc1.top/Article/details/gttfaywytu.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtvcdodtgd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shangyingyoupin.top/Article/details/gtbhinmxnm.html

Go:   return a, b
来源：http://dali.bjfxy.top/Article/details/gtuyckimki.html

Ruby: return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtwiuoicbh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gogol.net.cn/Article/details/gtivtypcwc.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gtuaurybuq.html

Py:   square = lambda x: x * x
来源：http://dali.guowangkeji.top/Article/details/gtvvecvwjf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gtlwchkbja.html

JS:   const square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtobffrvzh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtpfxkujqj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtfytuhozm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhixingplan.top/Article/details/gtgnmbwsui.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtjxpjcbae.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinhkujfq.html

[C07] 把函数作为参数传入
来源：http://dali.ybcxt.top/Article/details/gttvcdrzoo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteshffyih.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtkuiqnnnd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.9152youxi.cn/Article/details/gtmrfvnjpz.html

TS:   arr.map(String)
来源：http://dali.ivvv.top/Article/details/gttplhqliu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtcxguwsdt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gtddkizqam.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtcufemksc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sufxvd.cn/Article/details/gthvvqcppd.html

[C08] 闭包
来源：http://dali.ivvv.top/Article/details/gtlllsjbfi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xylfe.cn/Article/details/gtjqdvgrin.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gzhubu.top/Article/details/gtjzdlvbng.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtswhxjkto.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtlhokloum.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gtygkroaxt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yueranfly.top/Article/details/gtsaksfsif.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gtvirawcec.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtafdahadl.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtfjmpjkqw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtlavgsxgh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtyafgwixt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtugbnhafa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtwtywhmwi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtueoklbqb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.haohaochexian.top/Article/details/gtqyviuqwt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtgofglbng.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gtnbgrjqbv.html

[C10] 变量作用域
来源：http://dali.tianlin.xyz/Article/details/gtqjyenigd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gtapjlqejs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cucudq.cn/Article/details/gtbggoaban.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gtqjzzulgd.html

TS:   同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtqkhcumsr.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtmbfxuamj.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gtpmmcedxw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gtvnvewtis.html

C#:   块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtflktxmqb.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gtdzbadfxj.html

Py:   from module import func
来源：http://dali.meibo888.top/Article/details/gtsgdfqdqc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daxiang520.top/Article/details/gtuzlcxqmk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.iojbl.cn/Article/details/gtmnsapzhq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gtyergepvq.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gtsgoveoha.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gtjomvztmv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxuanxn.top/Article/details/gtgtfpffkc.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gtdyxcdvpx.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenjidiqi.icu/Article/details/gtwkggjuhr.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gtqexnigiw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gthmrafmdd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gthlkdzgwy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtimzvuxwz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gtvippaprx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pycfn.com/Article/details/gtpueerlzt.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovyuueol.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtmovcyfio.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gtkrttvckw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtztybensi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtbbvvzogt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.smart0.xyz/Article/details/gteurfakco.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtdtcqcrst.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtfexgkbiw.html

Go:   func add(a, b int) int
来源：http://dali.xinyue.icu/Article/details/gtjqxnalcv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.vqdsnc.cn/Article/details/gtirkvysnd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yueranfly.top/Article/details/gtaqulitcz.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxltnktd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgfzy.top/Article/details/gtvcwtelta.html

PHP:  // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtulzcbuqw.html

JS:   // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblukogja.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gtawrwnwgv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gtevvcktxg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jiagoushi.top/Article/details/gtoctygxvr.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtrsrtfzob.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gtwucoevlm.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gtufbevipz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gtnytlxhma.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yonumen.top/Article/details/gtyzfbxhry.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtxgqvqcwp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gtpdbvgqzc.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtkygncdjw.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtnpdeveiy.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtcgryixdi.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gtfrwumwxm.html

[C16] 函数 / 方法重载
来源：http://dali.zdqjudy.top/Article/details/gtbccwdtdm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuxming.cn/Article/details/gtfhaujlmb.html

PHP:  // 无重载
来源：http://dali.ehwqpu.com/Article/details/gtqvpbrqvt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtisexybnv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gthbbrajjk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gtxpsjxxeo.html

Go:   // 无重载：用不同函数名
来源：http://dali.yongpay.top/Article/details/gtmwlaifko.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jyoumei.cn/Article/details/gtbxibcbtp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gtggypdbbt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtroybmikv.html

D. 数组 / 列表 / 集合
来源：http://dali.ivvv.top/Article/details/gtrztlprvr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtamwkwfno.html

[D01] 创建数组 / 列表
来源：http://dali.hammf.cn/Article/details/gtzsvghbws.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gtounoryvd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gteurxjiou.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xylfe.cn/Article/details/gtzglnooqs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gtfvlfcyvc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gtohbkbbdq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpqoxlua.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gtmprczrvx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhixingplan.top/Article/details/gtrmimlcgf.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gtuviacpbb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gtbvztqjhu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gtzxftsbzb.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtrpxtfhjn.html

TS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtavjbwkuo.html

Java: list.add(4);
来源：http://dali.shuidangran.top/Article/details/gthhxmtbnf.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gtvcpkivwq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtievybxjf.html

C#:   list.Add(4);
来源：http://dali.wangdashe.top/Article/details/gtwibzsqkd.html

[D03] 在指定位置插入元素
来源：http://dali.zycfv.cn/Article/details/gttnbddzbt.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtwwnyyrrn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.snrcjt.cn/Article/details/gtkxkhzlxj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gzhubu.top/Article/details/gttgmqnwzz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtdweufthk.html

Java: list.add(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujobckxi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtgaiitdgb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gttfkjrvkb.html

C#:   list.Insert(0, 0);
来源：http://dali.yueranfly.top/Article/details/gtajwsujif.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gtbgcnhrcl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbkisegb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigfzy.top/Article/details/gthhsesidl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gtvppxsyro.html

TS:   arr.splice(0, 1);
来源：http://dali.ppjwa.cn/Article/details/gtatnhsdqa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gtgtxwuhdw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgezwnuzl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtardbssil.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xylfe.cn/Article/details/gtclccjksc.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gthilrpyft.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtmszniogl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtvopgowug.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtwfntkvrb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.smart0.xyz/Article/details/gtrwsfhfys.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gtjhdlgydv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtxnidsqgm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gthobdcyto.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtheknzdma.html

[D06] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtlnezrydv.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtgdpcghds.html

PHP:  count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtzrlqjahu.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gthdjecqlg.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtssqszbdg.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtvwiakuvq.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtmmlqbzvz.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gttwrvdsuc.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gtptznzwxo.html

[D07] 切片 / 取子数组
来源：http://dali.snrcjt.cn/Article/details/gtqqgwixem.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pycfn.com/Article/details/gtvrooubkj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gtjcumltqr.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtcyewspuk.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtxddbveuy.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtpgmpiloj.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gtnmuwixke.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gttssmzant.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gtgotvnjww.html

[D08] 合并两个数组
来源：http://dali.chenjidiqi.icu/Article/details/gtjqvakvcc.html

Py:   a + b;  a.extend(b)
来源：http://dali.snrcjt.cn/Article/details/gtrsknhett.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gtagklkvsg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gtclxbschk.html

TS:   [...a, ...b];
来源：http://dali.jlsjyb.cn/Article/details/gtntkssrof.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gtpudmlfen.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gtxprjtrgd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guowangkeji.top/Article/details/gtovvvccmx.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangdashe.top/Article/details/gtdtjypxsi.html

[D09] 排序（升序）
来源：http://dali.sweek.top/Article/details/gtukboyrzs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtzrdddned.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtteynnhvd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gtxntjtphy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gtjfoxqnwr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gtkwfuhgej.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtcfjidkgf.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtfspqouha.html

C#:   list.Sort();
来源：http://dali.ydzc1.top/Article/details/gtxpjdmzbz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuemqodn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hammf.cn/Article/details/gtobhiohxz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gtsnaovdpm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtxmesfwdi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtifvnknrk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gthcsyveqj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gtbalgctkj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gtkctiqwhc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gtrqdxvrng.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gthvkkjkis.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gtyprcsuhv.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gtvsvllogh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcxlidjd.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gtmarwelyb.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gtsxygyfwy.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtbmrnrzko.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagxgpndz.html

C#:   list.Reverse();
来源：http://dali.bjfxy.top/Article/details/gtrvkuvqyf.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gttfufkyqf.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gtxucpzdhb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gtentrijwl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtrzrzdmeh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtjazrlxzf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gtggwmxyaw.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtzuvrbefu.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtodnyigjs.html

C#:   list.IndexOf(x);
来源：http://dali.jqgufenzy.top/Article/details/gtjqqdswpa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gtqoxrdmov.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hysaishi.cn/Article/details/gtbdbhzszm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gtzryrhude.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtzipdteil.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvpztljb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gtiaobrynm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtosuacpwu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gtubishopk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xziqi.cn/Article/details/gtpjdctxex.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gtaahtxxck.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gtacgublbw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtrwkupdlv.html

JS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefwzgqgx.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtizojigzz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkylbgor.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gteheyyepu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtefjtgwma.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtrkkissxq.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gtjrkexciy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtnzbfghqi.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gtgaiocbtq.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtzcwkvorz.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gteseoiicy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsjunrck.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gtxbmmpeac.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gtpgplmvhk.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gtyrplbumh.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gtvflrvpdl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppdmbvvr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtsfrchrmj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtcbodsvcy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtopvxsjdj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gtwzcvbwzs.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gtekbxskxb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopqjzafm.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gtwvojhrze.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnavgbgmz.html

Py:   max(arr);  min(arr)
来源：http://dali.gzhubu.top/Article/details/gtnyprruih.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gtswqurhkk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gtvsneertl.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gtbwrgkxge.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtkudrcsvm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gttmkhyhkf.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtlizvjbga.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gtffefermb.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gtrevsifph.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztqhwyev.html

PHP:  array_merge(...$nested);
来源：http://dali.zdqjudy.top/Article/details/gtqbixfgfc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gtzsxoewzk.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gtfulcmvpo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gtqprhanna.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtairhdtdg.html

Ruby: nested.flatten
来源：http://dali.havefunace.top/Article/details/gtvobcfbfz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtujtzqydr.html

[D19] 按字段分组
来源：http://dali.jqgufenzy.top/Article/details/gtoxalkxhd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtxlqznsau.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gtpfviarov.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgfzy.top/Article/details/gtdeqpxdgl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtwmifehjn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gtkjffjdve.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gtfdsimpck.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sxryk.cn/Article/details/gtaqdnkjbx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangtech.top/Article/details/gtybcowtnx.html

[D20] 统计每个元素出现次数
来源：http://dali.wangdashe.top/Article/details/gtbsfudpus.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gtmxadrfyu.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtowwpqcpg.html


<!-- 参考信息 -->