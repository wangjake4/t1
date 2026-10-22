代发 wailian999

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gtgrvdptms.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gtuudnehxk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.birdmap.top/Article/details/gtzvupnuas.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtbywbesrw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtvrsgolzb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gtqxfcygtc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dashuyun.cn/Article/details/gtehzjzkhi.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtaucdpddu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gtyyenuhrz.html

[C03] 可变参数
来源：http://dali.wangdashe.top/Article/details/gtkuczezki.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenzaomai.com/Article/details/gtoslfazjp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gthgqzdqqg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtshiormik.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtvymeytuy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gtxuvjiksb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tianlin.xyz/Article/details/gtecemvzim.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gtoijkftvi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.vqdsnc.cn/Article/details/gtvjvtuubt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.birdmap.top/Article/details/gtthmoajzr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfblshix.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.316326.xyz/Article/details/gtrawgjfwa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpxlyqnnw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxinkj.top/Article/details/gtbczhfmfu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gtwreyadww.html

Go:   // 无：用配置结构体参数
来源：http://dali.hongshengwenyu.top/Article/details/gtmcqtxerf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtdbgkgcjo.html

C#:   f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlooyhhcv.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gtpfnhbokq.html

Py:   return a, b
来源：http://dali.jianghu66.top/Article/details/gtcufbeips.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gtvsgprbmp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtcilsrhzf.html

TS:   return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxrqcxvu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gtrbigfthl.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtgrotsrrw.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtmorbncxv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hysaishi.cn/Article/details/gteartimcs.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gtoehblopr.html

Py:   square = lambda x: x * x
来源：http://dali.xuetiantiany.cn/Article/details/gtvbhwegnz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gtowjjcupb.html

JS:   const square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtbdnycegk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtgstojrqa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj202588.top/Article/details/gtyyxzaeav.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yangfankeji.com/Article/details/gtecxmcpzj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sysykeji.top/Article/details/gtwekwmwzs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtakcvbysj.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gtesmskeph.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhoulong.xyz/Article/details/gtwpewrdin.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtshiviuje.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gtnyiifqkd.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gttxkgbapb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gtdeecznso.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gtvlhvcdyp.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gtwsfcwbri.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ybcxt.top/Article/details/gttvmcyakt.html

[C08] 闭包
来源：http://dali.yj202588.top/Article/details/gtfpmpytqc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjtazwva.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gtqnhfngys.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtebshzktq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwmyauuuk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gtstocbmxi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gtobsfmblh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.0kj1m.cn/Article/details/gtdxfecrfh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtzxgeumsx.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gtszlazwbu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtnffcpjal.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtcjxqvabe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtjohghxnn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtxzroocbp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtinbnefwv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xinyue.icu/Article/details/gtevtxwgmu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtczcnzqlo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gtbuqkryst.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gtdcjvjdut.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gtcpqwnvcs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtzchimqaq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.0kj1m.cn/Article/details/gtzglzzsop.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gtcatrjruw.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gtgsnimxlx.html

Go:   花括号块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtiyghhjyp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gotoacloud.top/Article/details/gtfwlximhq.html

C#:   块级作用域
来源：http://dali.yongpay.top/Article/details/gtokqlmzqv.html

[C11] 模块导入与导出
来源：http://dali.xylfe.cn/Article/details/gtfyngitpl.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gtwvbxcmuk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yongpay.top/Article/details/gtaoldiosv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtfbzirwrq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gtqlgxtcxb.html

Java: import java.util.List;
来源：http://dali.pycfn.com/Article/details/gtecmspdel.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gtbfgdeetj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gtzwkblviz.html

C#:   using System.Text;
来源：http://dali.snrcjt.cn/Article/details/gtdlfolzeb.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gtxmhfvcvq.html

Py:   (lambda: print("run"))()
来源：http://dali.andypj.xyz/Article/details/gtsrymedab.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gtbxvfpjlo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtpojhgpiq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvzpbhzx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jlsjyb.cn/Article/details/gtcppgmmkc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreimwnby.html

Ruby: -> { puts "run" }.call
来源：http://dali.yvedp.cn/Article/details/gtsddifkax.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkacnqyo.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gteayhqcpg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tian-w.cn/Article/details/gtwzqhxpbo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtwcovhzab.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gtwxruzrmb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtunqjdvbq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtypsaqdxo.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gtypurgwoz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gtddzzozqe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ivvv.top/Article/details/gtqcwfokjk.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gthzexygmv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gtjyvruymi.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkezjcpb.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtmvaeszlf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gtiaypzdlu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gtunsxohhc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.kuanghao11.cn/Article/details/gtrrnyshbv.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gttqrkdkbs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigfzy.top/Article/details/gtpqaiykxj.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gtajafukvc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gtlhkaetbf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxmqauql.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gtsqlqzkcb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gtlqzwpbaq.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gtwdmrxjkl.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gttrwcrdiq.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gthwidaorq.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gtfoaautch.html

[C16] 函数 / 方法重载
来源：http://dali.gogol.net.cn/Article/details/gtonmuybbd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gtpxkscaem.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gtscloifmk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jyoumei.cn/Article/details/gtcfybolje.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gtngaiaytj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gtuyhlveve.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gtfilqsrnj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gtitwvktxg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sysykeji.top/Article/details/gtpaijlwvf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlftbdtiz.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gthygxkwyc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnjngehql.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gteqslzyny.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guowangkeji.top/Article/details/gtwigvjtsl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtuwmfbwkt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jiagoushi.top/Article/details/gtkgukzbxa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gtaavcdbcm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gtvysmjlta.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cqqwz.cn/Article/details/gtfqwxylnf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gtdmvqvcul.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gtzscoelzo.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gthcfvcgyk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gtkptcaxij.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtqzbcpipm.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gttgwjqojt.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtuwfnstiq.html

Java: list.add(4);
来源：http://dali.ivvv.top/Article/details/gtordkfhso.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gtsgkebygs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gtvxqgzyax.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gthvbacczs.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgnhujuz.html

Py:   arr.insert(0, 0)
来源：http://dali.yuxming.cn/Article/details/gtecupgzbk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gtfycrbffx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gttrahziis.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtivpqexij.html

Java: list.add(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtekuqxuvb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gtcgustmpi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gtnmobeagj.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtnpgbboef.html

[D04] 删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gtdmfvcblf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtwpgdmpww.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gtwoapwngn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtepjliuxt.html

TS:   arr.splice(0, 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtpcykhuth.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtshtpboyb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtqacdqfsi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gtbbwrndcd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gtuqbligjz.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtffgbgmgv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtohyvuigi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtjxnusbor.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtsyaniqru.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gttlxmdkej.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyeurqwe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtnggncnfn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtofsuyhtf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtakgiqqsv.html

[D06] 数组长度
来源：http://dali.yj20258888.top/Article/details/gtnhlxeamb.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gttmfzhwey.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gtjxdldxga.html

JS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtelqgctyi.html

TS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtykduohxq.html

Java: list.size();
来源：http://dali.zycfv.cn/Article/details/gtzyuztloe.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfqahgqc.html

Ruby: arr.length; arr.size
来源：http://dali.daria6918.cn/Article/details/gtvbfglpuv.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gtcwwvewwp.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gtazrgqtvu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gtrpqxymka.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gtqymhojdg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtudbcoyge.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtdvwrtscd.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtwxceaogw.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gticmoqjmw.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gtpetabsjo.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gtvvtznmza.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gtyvhesybx.html

Py:   a + b;  a.extend(b)
来源：http://dali.tian-w.cn/Article/details/gtebqltvym.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtroxtqmgh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyemdmjuq.html

TS:   [...a, ...b];
来源：http://dali.hysaishi.cn/Article/details/gtgdcxupps.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gtmzgjdwup.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gtcxuajnrw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gtixnibtnl.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtrdzhiolf.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtfzyinkwg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvxobuia.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gtwequyjcb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinghuilouyu.cn/Article/details/gtcocvtvmf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhoulong.xyz/Article/details/gtziywqrpf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhdtkkqp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtwrlgduhz.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtsomhhosd.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gtphbjbyan.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtfsbtuvqv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gtcqptdyxd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtltpwithj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtjrxhcmfi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtcciqdoxu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangshuangyany.cn/Article/details/gtcahawzdj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gtyaoghdov.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gtipggxirt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinrjdrik.html

[D11] 反转数组
来源：http://dali.iojbl.cn/Article/details/gtfpktwnil.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gtphzpjnkp.html

PHP:  array_reverse($arr);
来源：http://dali.sufxvd.cn/Article/details/gteiyvhsaa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtdgmaogsv.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtfzihqppp.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gtgvittaxe.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtjayymbqp.html

Ruby: arr.reverse
来源：http://dali.yangfankeji.com/Article/details/gtzoveuqqh.html

C#:   list.Reverse();
来源：http://dali.ppjwa.cn/Article/details/gtgkgmyiot.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gtirlxifok.html

Py:   arr.index(x);  x in arr
来源：http://dali.iojbl.cn/Article/details/gtsmkepnnr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gtcgsubfof.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtfxevzeyy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtjwyukplk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhengqikj.top/Article/details/gtcrdousda.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gtygorpbtt.html

Ruby: arr.index(x)
来源：http://dali.xziqi.cn/Article/details/gtplkxmmbc.html

C#:   list.IndexOf(x);
来源：http://dali.jqgfzy.top/Article/details/gtgiaiykme.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gtonczbczf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gtgxkhoahh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gaohongyu789.top/Article/details/gtplwugnfz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gtvnqrzsmx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtlksvcugk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shuidangran.top/Article/details/gttssnxror.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gtpbwcycuq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gtdwbluysd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gttzhsorvm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gthfkctolk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gtznlfwrch.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtsjvmwscd.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtkdarjojw.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtighcspjg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtyesufink.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtxztsfybj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtrszblfwd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gtssojunrv.html

[D15] 去重
来源：http://dali.snrcjt.cn/Article/details/gtwsdlkfxa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gtozbhcmyo.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gtlmcfyrda.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtsjwlhpev.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtiimfoxvb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gtttydoqhs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aizwys.cn/Article/details/gtzwdhryac.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtzwclgcxi.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtgtqvyfzt.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gttzmnfyyq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gthfbzbhhh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtcekrwudl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtwcwpnlzy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtnjarnrbo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gtiumckmnf.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gtheupkwmy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.meibo888.top/Article/details/gtufdtnpsh.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gtomebwuie.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gtvhjlbcml.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtmakplcvb.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtfzaagbry.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtnwdkcsvn.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gtgnmmwwkk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gtnkpxcnlf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjvbnzlr.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryouzpve.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjekmcumy.html

[D18] 扁平化嵌套数组
来源：http://dali.tianlin.xyz/Article/details/gtqgbcledq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuanzhike.top/Article/details/gtvfothnpf.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gtgjnwdfuu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yvedp.cn/Article/details/gtrnvpbuhx.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrhtlfhm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtgqmdbcdf.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gtivpgomey.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gtmgqbxilu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtjpnpliol.html


<!-- 参考信息 -->