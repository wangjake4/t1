代发 wailian999

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gtrmvppasx.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gtwrfcubkn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gtmbpodacl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtpivvzgoa.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtsdaybwop.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gtriaogytm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdirkywib.html

Ruby: def greet(name = "World") = name
来源：http://dali.kuanghao11.cn/Article/details/gtbjykioyx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gtxnkrdpxf.html

[C03] 可变参数
来源：http://dali.cqqwz.cn/Article/details/gtvrdkctia.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gttnpqtyrq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzipoghg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtcwllxizn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gtimcskurf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cashguo.top/Article/details/gtfsibjvdx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yanxiufei.cn/Article/details/gtjwsalifh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gttjzrownm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.0kj1m.cn/Article/details/gtteumtihy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhongyouzk.top/Article/details/gtouevdsej.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gtvouwojnh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gtxhggifbm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtjvlbkoiu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nwbrower.top/Article/details/gtortjtszq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hywenlv.cn/Article/details/gtcpytgqit.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkkrbavu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtddydznpo.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtkqfrmlqu.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gtqvjrymqp.html

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gtxnheyazh.html

PHP:  return [$a, $b];
来源：http://dali.yuxming.cn/Article/details/gtttlqnzhf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtjhhnbkjz.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gtbbrcnmov.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigfzy.top/Article/details/gtlmywhmak.html

Go:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtyffqkoze.html

Ruby: return a, b
来源：http://dali.cqqwz.cn/Article/details/gtoxygjfer.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxqypkyk.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtznrbesgd.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigfzy.top/Article/details/gtvghkneco.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gtedwtqxgv.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtebksvkhv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtxfnupstx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gtpnlcmqmz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtmesgsshn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gtkdnyhccz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtsrbddysc.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gtaznrtrzl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nwbrower.top/Article/details/gtamezuvqr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gtecasrryb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gtsneqggmc.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gtbycyhjrw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtrymawgnj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gtlmbsjfxo.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gtfemfisfi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.kuanghao11.cn/Article/details/gtxvgbutok.html

[C08] 闭包
来源：http://dali.bjfxy.top/Article/details/gthoiqgymp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gtjwunajfx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yonumen.top/Article/details/gthimruekr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtcdhmzmdd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gttghtzsog.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gtvjdyndgt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gtwtkdogam.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gtwehqcubh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtgxsffxez.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gtvcsfplpk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtscbwemip.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtvxjuhfay.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtozmuzrjv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtxlcgmfiw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yonumen.top/Article/details/gtiqbyeuhy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cdnleiting.top/Article/details/gtgztxbpgj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gtzashqlac.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gtplwzvymv.html

[C10] 变量作用域
来源：http://dali.gogol.net.cn/Article/details/gttyflgiew.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.0kj1m.cn/Article/details/gttclfjqeb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yvedp.cn/Article/details/gtoohpvqjf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangdashe.top/Article/details/gtvzptvthh.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtqffvxwnp.html

Java: 方法内为块级作用域
来源：http://dali.jianghu66.top/Article/details/gtmhvgwtxo.html

Go:   花括号块级作用域
来源：http://dali.cucudq.cn/Article/details/gtzmglfcxn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gtmthgvqdh.html

C#:   块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtcpkwuhcv.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gtvptkuedq.html

Py:   from module import func
来源：http://dali.gogol.net.cn/Article/details/gtootovkhs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gtcbrvdncf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gteadpzrby.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnxiangtu.top/Article/details/gtrecwhkwf.html

Java: import java.util.List;
来源：http://dali.daxiang520.top/Article/details/gthfpopjdb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtvnjarrmw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258888.top/Article/details/gtffadllox.html

C#:   using System.Text;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsriyqfym.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gtuvajwdfb.html

Py:   (lambda: print("run"))()
来源：http://dali.yvedp.cn/Article/details/gtwnzlaziw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gtqoaxwbjm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtyhrhmixq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtljfnuclq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtimjdjwyf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gtgcfgpxnq.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtdabptben.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnqzz.top/Article/details/gtiapcruuw.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gtklqfmjgj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtsqwncwxe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtbsuyjesx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gtnqfimfbn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtuzlzhlst.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtalrnioji.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gtzchtnyqn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gtvyoehuxg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sufxvd.cn/Article/details/gtslrfmtaa.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtvrdcutws.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gtuqonxxze.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtbjxetsuj.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtmgykfcnm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gtpeahawjf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gtwffhzkaw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gtsbznpynp.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gtyuxkoetw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcivhdfw.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumlmyvfw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gtilnhgboj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nwbrower.top/Article/details/gtvyqdqomg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtdiunttgf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gtsnksfhxo.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtcrxddnhs.html

Go:   // 无解构
来源：http://dali.sxryk.cn/Article/details/gtalxiudtj.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gtrrmrlauz.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gtcptmmgdx.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtbmrcbqov.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.c1oappe.top/Article/details/gtfpdndozr.html

PHP:  // 无重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamkmyzky.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.9152youxi.cn/Article/details/gtozkaeyky.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daria6918.cn/Article/details/gtjnaleryj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gtndzikmep.html

Go:   // 无重载：用不同函数名
来源：http://dali.jianghu66.top/Article/details/gtssqmixtw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gthhupbprp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gtvoimyexb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmrdwfcfd.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtylnoixug.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtofbvkozn.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gtfoxmmfmo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenzaomai.com/Article/details/gtskngiuhr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtkqmmszza.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtxhrgjdht.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gtmxdvriqe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gogol.net.cn/Article/details/gtypscacil.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ydzc1.top/Article/details/gttccbokfx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gogol.net.cn/Article/details/gtgwgfynta.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xziqi.cn/Article/details/gterkkwqbd.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gtxxzbirhs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gtaecgvqvv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscshumbr.html

JS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtutmkzpdv.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtmsrhytiy.html

Java: list.add(4);
来源：http://dali.wangdashe.top/Article/details/gtkwgjsiwr.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigufen.top/Article/details/gtpghfmnpl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gtuttopffj.html

C#:   list.Add(4);
来源：http://dali.sysykeji.top/Article/details/gtmorzdqcp.html

[D03] 在指定位置插入元素
来源：http://dali.zycfv.cn/Article/details/gtncmdshcf.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gtbrwsmozm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gtgijaadbk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gtgwpjmvcd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtgufmjvrm.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gtdyaygweg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gtagljgpox.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gtkwmmvpdu.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtuyabmqql.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gtnrmtxzea.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gtprszlodm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nwbrower.top/Article/details/gtnbratsjo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hysaishi.cn/Article/details/gtxpzprjbt.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gtbfqpycgn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gtcgroehow.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gogol.net.cn/Article/details/gtgaduqgcl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuobvjdqx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daxiang520.top/Article/details/gtnwzithqp.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gtqkvxqnse.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtcvsxemhq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtnncvaivg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtwpyngbcz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tanke756.top/Article/details/gtzbvdufym.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gtwebkbyix.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuydosik.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtsowxbvkm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtyaxlkyln.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtsxsaxjrn.html

Py:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtaoiqqubl.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gtutquqwab.html

JS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtzvgemtcy.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkgokysk.html

Java: list.size();
来源：http://dali.wangdashe.top/Article/details/gtaruvtmdp.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtqpfzqrkq.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gtridvwspx.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gtebfspihe.html

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gtfhbsuyix.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gtiveiulda.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtyzkojdwq.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtwwwskzfy.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtcsyxbyfa.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtxcuuoogn.html

Go:   arr[1:4]
来源：http://dali.ehwqpu.com/Article/details/gtswqztzue.html

Ruby: arr[1, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtqwcreaiy.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gtzhuzuzlg.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gtlzmikdmx.html

Py:   a + b;  a.extend(b)
来源：http://dali.pycfn.com/Article/details/gttehayukc.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gteuglanma.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxuanxn.top/Article/details/gttzfyzsba.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gtikmglflv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtnuincmix.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gtugowfcjt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gtwmkgamvc.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtgtzgkuda.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gtcwsymzok.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtnzpizyvv.html

PHP:  sort($arr);
来源：http://dali.snrcjt.cn/Article/details/gtvpcehbey.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gtnqqiaftb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gtwzqwvxvt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtabyzrhzd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtsfnbzsjh.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtfcsrkarb.html

C#:   list.Sort();
来源：http://dali.xinyue.icu/Article/details/gtpwkglwih.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtcgxgpfll.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnxiangtu.top/Article/details/gtdcbazrvx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtsvsdoyxr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gtgbziaduq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtasykibgi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gtgqckhphn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gtmptozdxm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gtetlnwhjd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gtalhhdeir.html

[D11] 反转数组
来源：http://dali.guannengcc.top/Article/details/gteanojhcv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtoqwxpcbk.html

PHP:  array_reverse($arr);
来源：http://dali.mhx1999.top/Article/details/gtgiqnsmcz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gtwnhdrusj.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtdrzptxnf.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gtxkxwoibj.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtqwzqvpit.html

Ruby: arr.reverse
来源：http://dali.mhx1999.top/Article/details/gtnwfsnwqb.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzxfigcr.html

[D12] 查找元素下标
来源：http://dali.jinghuilouyu.cn/Article/details/gtesebdznu.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gtqhrsfuww.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtltzriyyj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtqepmirut.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtyemfetev.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gtblzkiyht.html

Go:   slices.Index(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtozzuglci.html

Ruby: arr.index(x)
来源：http://dali.zhengqikj.top/Article/details/gtzwztjxkq.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gtdkeeianq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gtvhgbedke.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gtvhybenks.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gtrilcrukk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtnhfxyali.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtvfhjybye.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtocbwykvt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gtertfhqtf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoeyckdh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxsvvcmz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gtuvmhnddo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gtrytyembq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gtkludmqah.html

JS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gtddavkpmt.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtazhfqkhi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtvbwitzfe.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtyyzfconn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpjxrobv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtfowdlskp.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gtaainrxpj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtcjqpdias.html

PHP:  array_unique($arr);
来源：http://dali.wangdashe.top/Article/details/gtjjvrfezz.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtkvcaazey.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtdedyppdg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuetiantiany.cn/Article/details/gtxtbchqzo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gtzsjscdnd.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gtpbxiypna.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtdtxkptks.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gtppzgqdad.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtklqowmdk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gtyoazjrfx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtokppamha.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtffvkofjf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gtpgdljlkp.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gtkjdfmnxf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtuqihfqkm.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gttkjcbdqy.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gtyudzmrwx.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gtafrhaibs.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gtvgcqcedc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtagwbndkj.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtslxsbjrg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.0kj1m.cn/Article/details/gtcnzmxyzd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gttlfrflwe.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gtvgddzjrc.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gtrntkyvvm.html

[D18] 扁平化嵌套数组
来源：http://dali.fengsongda.top/Article/details/gtezjglzsm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gtjooiybxm.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gtpecluufe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gtrzgfncyv.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtorzoytgn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtryuwrjcz.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gtbchrhxbq.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gtyqnkuigy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtaiyqoycd.html


<!-- 参考信息 -->