代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtypbsucmg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gtnxsfrepo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gtvptgreyu.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtuhkuvqaf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jianghu66.top/Article/details/gtrqixakyp.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gttzpzrmxp.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gtnmlolucm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgihfyuiz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtrnnljhup.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtfwgxsatj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guannengcc.top/Article/details/gtxmukqkry.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenjidiqi.icu/Article/details/gtnlpintxi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tian-w.cn/Article/details/gtxopbrlhu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.mhx1999.top/Article/details/gthkfhtwca.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dashuyun.cn/Article/details/gtuikwiiqj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pengpengdd.cyou/Article/details/gtddhrqudf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gtdttxzgqy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtuoznjjqo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dianchejie.cn/Article/details/gtfoxmuyvb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.vqdsnc.cn/Article/details/gteiscvhsb.html

Go:   // 无：用配置结构体参数
来源：http://dali.snrcjt.cn/Article/details/gtwehwkxpd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gttqjdjkii.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtmkggiaxw.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gtrnsadpyf.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtukpmihxf.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gtyjjxnmwq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbhxwwpa.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtqufvkmbq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tian-w.cn/Article/details/gtnvmekkug.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtmxqatjrq.html

Ruby: return a, b
来源：http://dali.sysykeji.top/Article/details/gtssdmuezj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daria6918.cn/Article/details/gtbxpkxmpd.html

[C06] 匿名函数 / lambda
来源：http://dali.meibo888.top/Article/details/gtdjmqlaeo.html

Py:   square = lambda x: x * x
来源：http://dali.haohaochexian.top/Article/details/gtwvfpvjsg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigufen.top/Article/details/gtkqijkptd.html

JS:   const square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtuukzsndp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtcgabsbuo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sxryk.cn/Article/details/gtsabqzzmr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gtajomdsrb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gtjvzmuiuz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtbqjnmwzi.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gtdtcsvgbw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gtwintztup.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nwbrower.top/Article/details/gtymkcchpy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gtfmcwskcu.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gtciabvcyh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gaohongyu789.top/Article/details/gterlsqbbf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxinkj.top/Article/details/gtrbrnumtb.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gtqschsjho.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cashguo.top/Article/details/gtqcwsddkh.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gtqummbnwe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtkksuebpq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gtnlyhliec.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtoxlyyrmj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtnuxrjoda.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gogol.net.cn/Article/details/gtlihqxzjg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gtjixbvcdf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangshuangyany.cn/Article/details/gtwvprybgo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtvjramnyv.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gtiwjxcqbp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gttpmxgxil.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnezofdy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gtvmjxsmxo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtuieypjjz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtpqmuhxuu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gtztubsmqg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtbvazbrpl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtnbmdjeec.html

[C10] 变量作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtdungbizm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gtvjrubjlf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gtzxyttenr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpwxapcn.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwekebuco.html

Java: 方法内为块级作用域
来源：http://dali.zycfv.cn/Article/details/gtjmzouphs.html

Go:   花括号块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcfyntuh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gtvjbousjw.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtayzckenv.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtoxvjxkej.html

Py:   from module import func
来源：http://dali.yongpay.top/Article/details/gtbtohjupj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gtwdddrdxh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gthqjeafqk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gthavewlam.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gtbkpqurqi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gtypztscdg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gtrxnjubrw.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gtptbwjzmf.html

[C12] 立即执行函数 IIFE
来源：http://dali.xinyue.icu/Article/details/gtsttikttn.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgfzy.top/Article/details/gtkbbrcsdi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.9152youxi.cn/Article/details/gthxxntyan.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gttllazfol.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gtbbndfemp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gtgpwunqjx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gtrayzfaae.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gtqhwebcoc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gtenmbewdl.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gthqbycypr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtkaqlpnkl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnndcxdy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gtckjzxzqp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtlddhvajm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtzgktjnnd.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gtydqqedeb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gtxhughqll.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gtuoajflvv.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtzfggrmac.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gtbvvauxsg.html

PHP:  // 无泛型
来源：http://dali.birdmap.top/Article/details/gtglyqinag.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtotepvyhc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtorsanwtv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gttagoxsvu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gtmcrnjwsc.html

Ruby: # 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtqobveldg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pycfn.com/Article/details/gttuyiwbdw.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gtdoimdbvd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jiagoushi.top/Article/details/gtxkvnieoe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sxryk.cn/Article/details/gtqfktkkpg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtggfhejxl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gthrlnsjlx.html

Java: // 无解构
来源：http://dali.yj20258888.top/Article/details/gtzqshbfml.html

Go:   // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtatkdlstw.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gthpeqpwsc.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gtqocrwizo.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gtxnqtekbe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sweek.top/Article/details/gtqkiijyer.html

PHP:  // 无重载
来源：http://dali.mhx1999.top/Article/details/gtkgiijcnw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sysykeji.top/Article/details/gteplrxudn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gttanvkrax.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwutkcsbi.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gtyarywqin.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tanke756.top/Article/details/gtolezcfoq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gtdabeefsd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwmhzuqkh.html

D. 数组 / 列表 / 集合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvgmrmfj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtoblrhuje.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtxttslnza.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fengsongda.top/Article/details/gtezdbvgkd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gtfwisvqot.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gthenczbbu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gtwbhjynev.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gttqjrxcgx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gtlqmzlefs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gtwvmfbktn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotwavwas.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gtjwzzufjc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ehwqpu.com/Article/details/gtoeovpgjo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtlllmmqqn.html

JS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gtqlpnrqyl.html

TS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gtlhuownca.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gtqactsyuo.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtzjkovavm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gteqnsxiio.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gtbocnqrkk.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gthxoqmdrw.html

Py:   arr.insert(0, 0)
来源：http://dali.andypj.xyz/Article/details/gtflrdsoeq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gtnpomgrdy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtknuzpfbs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtoobfdrpd.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtutumywax.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtdyndvgrm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yvedp.cn/Article/details/gtopghlsxb.html

C#:   list.Insert(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtyjngoxbv.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gtghuyedrp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tian-w.cn/Article/details/gtctrtusaa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gttgpxgfck.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gtsvlxgpqk.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gtdmwhhavd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shzxlz.cn/Article/details/gtuuwjjpfw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gttoafrcdp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gtfbmgbruk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtigvjvbrp.html

[D05] 访问与修改元素
来源：http://dali.wangshuangyany.cn/Article/details/gtspegikvs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gteakbwviy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtvpimxwmp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gthligxpfl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gtchpfiqoq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cheryme.top/Article/details/gtvxnqravg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gteedpcksk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gttamsakym.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtqrqkefak.html

[D06] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtralckkcp.html

Py:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtyhxrddwj.html

PHP:  count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvtssgdk.html

JS:   arr.length
来源：http://dali.yj20258.top/Article/details/gturghcybw.html

TS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gthfintrqd.html

Java: list.size();
来源：http://dali.c1oappe.top/Article/details/gtrzyoaqta.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtepgvuphy.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtdcouesax.html

C#:   list.Count;
来源：http://dali.gzhubu.top/Article/details/gttsojwego.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gtninotlbo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gtmiuksywu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtapnuwubr.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtjqoiufuc.html

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtzcgfcppw.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gthbadkkql.html

Go:   arr[1:4]
来源：http://dali.xuetiantiany.cn/Article/details/gtfzuavtzh.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gtftnqggwl.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcvonfko.html

[D08] 合并两个数组
来源：http://dali.ydzc1.top/Article/details/gtadiwvhhw.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtuaqwrvlq.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gtghnlekzo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gtjinuockn.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gttcxyhgxi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gtyjibvpwq.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gtbkklexun.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gtedhrwjai.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtqisiwaqn.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gtwdvnpyhi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtomumvydk.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtttunjkgz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gthgerzfwu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gtvdwwltaa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gthiijqclz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtzmbtsshd.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtipxoyfun.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gtzgtolqyi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gttkckeuty.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gtlrcuvmhw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtvjpzjwvc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtnlbhytij.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtbtwwsjdp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gtmkzpnwac.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtgbkyhaic.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jianghu66.top/Article/details/gtoomciegc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtfeijrmvg.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gtdortuzkv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gtinkthmto.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gtlhsvnrfx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gtbamwntdg.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtdcjesced.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrfxmwtx.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gtzgetlbul.html

Ruby: arr.reverse
来源：http://dali.svipenyu.cn/Article/details/gtjsdtqrai.html

C#:   list.Reverse();
来源：http://dali.meibo888.top/Article/details/gtbqznmkhd.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gttvrwlndk.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gthignillm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtexumndya.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtlaxwfomo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtsiwsramd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.snrcjt.cn/Article/details/gtnihmjcbg.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtybknzqcm.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxnwtcnq.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gteeismfqt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gtgcpullda.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gtchstrgok.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xinyue.icu/Article/details/gttzlwnvmc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtfmncqngs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtsozftwee.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtytxmlykb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gtzebumeyc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gtarkbfbdn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtacmjkpaa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cashguo.top/Article/details/gtrobqqouu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gteypbmgdq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtxkvhkvka.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gttfuitein.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtraykrhmk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258888.top/Article/details/gtdkpudegp.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtlfbqsaqw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtpqvtabgv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtubyvgsio.html

[D15] 去重
来源：http://dali.daria6918.cn/Article/details/gtuqmcbaed.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtjfbegz.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gtpxzaneuh.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtptcxtqom.html

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtppllplxk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gtsgfbcifp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gtpehmyask.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gtnchgmkgv.html

C#:   list.Distinct().ToList()
来源：http://dali.cucudq.cn/Article/details/gtshjjvxwj.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfcujcpc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtubuybgkn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gtrbxlgbwe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtrfaktgjf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtqayeexvg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtzzybqhpt.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gtmdnvtmya.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gtelyzhyhs.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gtbwyfqirr.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gtfrmqaoqg.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdefbplos.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtfsteyohz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gogol.net.cn/Article/details/gtgwfgwlaq.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gttsbmriyn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gttamvsqhm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtnknmwzbu.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gtosetloqc.html

C#:   list.Max();  list.Min()
来源：http://dali.jiagoushi.top/Article/details/gtagogcnhd.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gtkrdukzyk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gtjmpmvzxx.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtzgypdxda.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gtpfeeqloc.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gtzrsnicym.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgyxendl.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtczqohege.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtgtsoshwg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtdottllqc.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gtniesfmgv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.c1oappe.top/Article/details/gtltulgtoy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gtlvndyisg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtuiwuqxpe.html


<!-- 参考信息 -->