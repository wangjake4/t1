代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gtomtulhmm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gtrbarbtka.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gtyngxyiyb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yanxiufei.cn/Article/details/gtquujfovq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtvnymmbhc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gthntmbmlo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gtyfccdsoa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gtbvhyecov.html

Go:   // 无：用配置结构体参数
来源：http://dali.dashuyun.cn/Article/details/gtxdmjotdq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtzipkrimn.html

C#:   f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtalxqtjzs.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gthallehgn.html

Py:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gttxxyshzu.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gtmeetckvu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtsixmbnog.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtsidmlsus.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gtitswimrl.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gteyxlwkdj.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gtzgxfuuxh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xziqi.cn/Article/details/gtnxhdazvi.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gtlggxrjmo.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gtibdfxoga.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258888.top/Article/details/gtfoxwwsit.html

JS:   const square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtahywcppq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoqmchts.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtpjhlilvo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gtsiunlyix.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtyxlnhojc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtstjzdxce.html

[C07] 把函数作为参数传入
来源：http://dali.shuidangran.top/Article/details/gthsktoefj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gtabkhcwuq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj202588.top/Article/details/gtozzianqa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.haohaochexian.top/Article/details/gtawjjorql.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gtjhuxsaqw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gtrgsyhbfp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqubejdlb.html

Ruby: arr.map(&:upcase)
来源：http://dali.havefunace.top/Article/details/gtjbxivtrf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dashuyun.cn/Article/details/gtybtvjlnz.html

[C08] 闭包
来源：http://dali.316326.xyz/Article/details/gttwdngqlh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnxiangtu.top/Article/details/gtgkjtnjdz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhengqikj.top/Article/details/gtezttymnr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtcsmlzsex.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknjuptqc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gtlclszers.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cucudq.cn/Article/details/gtgbigyvjs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhiwuduotai.top/Article/details/gtsiysaisd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtqfyimlec.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtiuhfyeqs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtywnytzwx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtjxhnaonv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtjpzqzsov.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gtzgyqrcas.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gtbmvscnob.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gtesvvjxsx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtxiotwzib.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xziqi.cn/Article/details/gtlhurkqxd.html

[C10] 变量作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhejcgwy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.bjfxy.top/Article/details/gtqjorucdi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvmbxbih.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhixingplan.top/Article/details/gtbcmdvbtf.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtupgwfsjt.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtaegqkgxt.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gttjmnojzm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gtnvyppcwq.html

C#:   块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtiplpnaou.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gtvvrauipe.html

Py:   from module import func
来源：http://dali.jlsjyb.cn/Article/details/gtllhltbrz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yonumen.top/Article/details/gtdbbyuszy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtdqrgxsea.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gtuyaytytc.html

Java: import java.util.List;
来源：http://dali.hnxiangtu.top/Article/details/gttqdenmcx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gaohongyu789.top/Article/details/gtihakngyy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gtofszqsre.html

C#:   using System.Text;
来源：http://dali.iojbl.cn/Article/details/gtkeiushmn.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gtyiwphulk.html

Py:   (lambda: print("run"))()
来源：http://dali.nwbrower.top/Article/details/gtulrifuaw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dianchejie.cn/Article/details/gtmmstkpsq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gtnhyswvsx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtpqejwgnt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sufxvd.cn/Article/details/gtyfzixher.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gtdjtjumvh.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258888.top/Article/details/gtkeobxadi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.svipenyu.cn/Article/details/gtbmwyrozs.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gtgipahyxc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gttsaxlqhf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtwuyaeaqb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.quarkkingdee.top/Article/details/gtadiefcmc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmasmtqyy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtgejvrqie.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gtituucxxk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gtvdvrklxt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtsansmrss.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblcgguus.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gtigpjpzpl.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtxlvnjfto.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtfjnxpgqk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtoneubevt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpsjyxgbe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtbxlpsqmj.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtbktqcvza.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gtulxnyijy.html

[C15] 解构 / 展开参数
来源：http://dali.smart0.xyz/Article/details/gtmljwptdk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cucudq.cn/Article/details/gthtklrifd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxinkj.top/Article/details/gtfaxreqxd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtxcasntup.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpgmjijs.html

Java: // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtzzycdrgr.html

Go:   // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtsorjvnqc.html

Ruby: a, b = pair
来源：http://dali.ehwqpu.com/Article/details/gtbzfeecgv.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gthotiiysh.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtotpvvamo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gtmlihpgsv.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gtnsvphhsn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gtfqfkpixf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gtalmxbeqw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtuioccbjv.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gtfhoxqmap.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gtkwmajzhx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.smart0.xyz/Article/details/gtsabhqrhd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gteilcfxue.html

D. 数组 / 列表 / 集合
来源：http://dali.birdmap.top/Article/details/gtkfyrives.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtabvtpnbz.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtjmmratjf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtmnatmooh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gtvcyzcqdq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtyzwnguce.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnxiangtu.top/Article/details/gtkgxguncm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cucudq.cn/Article/details/gtdqejytoi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrhknznt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtppvszpmc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gtfzisugce.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gtseqifyyw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gtjojghmty.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hysaishi.cn/Article/details/gtbsgprvtu.html

JS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gtwgesmguz.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtrksgqduj.html

Java: list.add(4);
来源：http://dali.yuanzhike.top/Article/details/gtaeswskgg.html

Go:   arr = append(arr, 4)
来源：http://dali.ehwqpu.com/Article/details/gtmhegclvr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sxryk.cn/Article/details/gteendddtq.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtaynmtfzz.html

[D03] 在指定位置插入元素
来源：http://dali.0kj1m.cn/Article/details/gtricgbquo.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtxawzoxif.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gtpxyygdjr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gtjgixaxnf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipvoscsm.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtnuinmcus.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gtmhacmrvf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yangfankeji.com/Article/details/gtjjhxrpgu.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtlcqdkruk.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gtlajwizqr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gteyehcjeq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaretvajq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gtjyelrwlm.html

TS:   arr.splice(0, 1);
来源：http://dali.xylfe.cn/Article/details/gtkjuhilgb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gtljnsojzl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gtblsjmwqs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gtrsxdshvi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gtgipsvmwo.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gtqrjwiten.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtfpfkoljc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtisnxloke.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtbuvedweg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphepqwmn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gtnxbxzpfr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtzsooqgpw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtqnkqnyyu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtanawxekp.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtwpierzeq.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtnfxckqnq.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gtahkbpcon.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtgmvwkciq.html

TS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtqskpkyna.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtobtlnhim.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtqobyepte.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gtdeunopap.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtmzicclzs.html

[D07] 切片 / 取子数组
来源：http://dali.yanxiufei.cn/Article/details/gtijlwbcou.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gtxzqrzrqa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtmehkygye.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtnalqwaga.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtkigztouu.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gttnikygsf.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gthqcmyftr.html

Ruby: arr[1, 3]
来源：http://dali.xylfe.cn/Article/details/gtehthczko.html

C#:   list.GetRange(1, 3);
来源：http://dali.xylfe.cn/Article/details/gtwbzwnooz.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtwktojvce.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gthwxjzeki.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtoahcxgwq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gtokwynmlf.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gtntkexvmh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yongpay.top/Article/details/gtpdsiwnvh.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gtanpgzgly.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yonumen.top/Article/details/gtjttqiniz.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtwpazyqur.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gtugqjdkbx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzlclfnc.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gtacyonxko.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gtcakaziaj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gtwqlwtzvr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtnjjajuvl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtryinayke.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtgpeddwpw.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gthzxkrkrr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gtdbpbeyau.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gtkcpixekr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gtrjubvbfv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtfcizykoc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtezuyzerm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gtmkyjnmpn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.mhx1999.top/Article/details/gtvrijqtvg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jlsjyb.cn/Article/details/gthcnbngjy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gtusrrhppg.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gtlfwbepcf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gtafawrgef.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gtqiysycte.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gtdyqtrbai.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gtojuwsopi.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gtbqwcebcb.html

Go:   slices.Reverse(arr)
来源：http://dali.cqqwz.cn/Article/details/gtowwntkap.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gttsuspodn.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtwmmngayz.html

[D12] 查找元素下标
来源：http://dali.xziqi.cn/Article/details/gttihrleoc.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gtbclwircy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgxlvuqy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtwdxapiwh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtujnzcuce.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigfzy.top/Article/details/gtlgtcwyqw.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtygssvkpb.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gttvvijhpt.html

C#:   list.IndexOf(x);
来源：http://dali.sysykeji.top/Article/details/gtjccihwjj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gtmrozexgc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gterupztxp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtbsedwory.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtifwksrjt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtvzuhusym.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gtehauqanc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gtaqdhrfnz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gtjviaubrj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtklzhidjl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gtflrwfbbc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gtfzjobjuv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtvnbvsmtg.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtjjimimzx.html

TS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtckskbibp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gtibhthies.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtuhykjixy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtfvfcbzzw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gttssevmmt.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gtcayapokt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsqshfgb.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gtizckxxuc.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtikavkbhc.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtrqrjcyba.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtrppakwqb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtswmvwbzb.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gttjyowwbm.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258888.top/Article/details/gtvfxjzzhh.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gtpucbzuzn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrwznxsh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtdsvhzcxo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtydlmixmy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtovorgjmd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gtnzympnla.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gteutftmxu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gtgzhfbgmm.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gthbphpikp.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gtsiafnmff.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtwpqllpos.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gtinnuronl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gtzcamppao.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaaboquns.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtwcisziyl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gtakebcpeb.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouzhhqaf.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gtkkolnazy.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gtdphlshrs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gtslktussd.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gtcvliaoee.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtyedksgpi.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gtfwgjhjum.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gtpoadcfxs.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gtbbpyfjwm.html

Ruby: nested.flatten
来源：http://dali.cdnleiting.top/Article/details/gtijfvrsmg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtszolqlmw.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gtsujvqyzh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gtsdrrcsij.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gtesoybycl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gtgnvrlmvo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gtmckowuyc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gtiamelxcn.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gtzcntwbpw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoprgyjeg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gtadvikkob.html

[D20] 统计每个元素出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtshbayygc.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gtljjdwaws.html

PHP:  array_count_values($arr);
来源：http://dali.sysykeji.top/Article/details/gtudmhctun.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtaddijkqi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtweecxjil.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfniwtkx.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gtbxrycvxv.html


<!-- 参考信息 -->