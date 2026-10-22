代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytaadiwa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gtexfsujfr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gtqdhrlnoq.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gtnjoimqsb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhongyouzk.top/Article/details/gtigolicis.html

[C03] 可变参数
来源：http://dali.hnqzz.top/Article/details/gtasajsoje.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gtmnzankdz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shuidangran.top/Article/details/gtsdjyetns.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gttenxbzch.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtxklnhxvm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cdnleiting.top/Article/details/gthsfhhoqs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnqzz.top/Article/details/gtreioinop.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gtdjabmsgc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gtqxhgsgor.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhongyouzk.top/Article/details/gthqslixkz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.svipenyu.cn/Article/details/gtcwoodbsm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yanxiufei.cn/Article/details/gtzghvvmac.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtyispwlkx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gtjvhwykol.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gtfjbkzwrd.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gtupnmleat.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtsbhubdpx.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtlgkhpaht.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gtvdddubwi.html

Py:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtacfaceli.html

PHP:  return [$a, $b];
来源：http://dali.gzhubu.top/Article/details/gtuvkuxbho.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gtswnstpoe.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtkkojakgu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigufen.top/Article/details/gtstjmwowc.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gteyzaxtat.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gtfyouebgf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hywenlv.cn/Article/details/gtmtkmscse.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gtkkgwgtjw.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gtsmlclxrs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cheryme.top/Article/details/gtwyefbole.html

JS:   const square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtclfvuggh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xinyue.icu/Article/details/gtducihxli.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtttlmhltk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gtaimyhlxm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gtyerugjro.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtqshuzrgg.html

[C07] 把函数作为参数传入
来源：http://dali.gogol.net.cn/Article/details/gtvtshofui.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenzaomai.com/Article/details/gtdcanyczk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gtgcrpozqy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtbjjplskq.html

TS:   arr.map(String)
来源：http://dali.0kj1m.cn/Article/details/gtgaqrzacr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtfdjxxmej.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gtasbusllr.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gtmlksnnqw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gtadsztvmb.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gtzgmwhhnp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guannengcc.top/Article/details/gtwbluwvbi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gtlylgxmsf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gtqomkqpah.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtaokbmyge.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jiagoushi.top/Article/details/gtorudnkli.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigufen.top/Article/details/gtezpfeijl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.mhx1999.top/Article/details/gtmjgmoafl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwmvyzzpv.html

[C09] 递归
来源：http://dali.aizwys.cn/Article/details/gtfikjhxee.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gtsfljpjup.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtlezvkwus.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtfjktxgqh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtlkmbvoez.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.havefunace.top/Article/details/gtqcngujmm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.havefunace.top/Article/details/gttxgsrdod.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtswpmpjaa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yonumen.top/Article/details/gtmmwfwtqm.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gtxntejduy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gtwzjfswib.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gtkphsblll.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtzhnmezqb.html

TS:   同 JS
来源：http://dali.daria6918.cn/Article/details/gtsjvyocbo.html

Java: 方法内为块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtgxalsnij.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gtlbtxgkhm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gtanuzeagn.html

C#:   块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtyblfeuim.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gtxdfgcmko.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gtytjkuqyq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gtkmeujxaf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtvuzewuas.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gtukpktcxi.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gtezpgmmtl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gtdasderoy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yueranfly.top/Article/details/gtbkqtfjgh.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gtdpvbrpnk.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gtqmmhrvzb.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gtlkkorrci.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gtnlzpzxut.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtlnjzxksh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtistvkhul.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gtzdltofxy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj202588.top/Article/details/gtslyrqukq.html

Ruby: -> { puts "run" }.call
来源：http://dali.daria6918.cn/Article/details/gtajftlmhe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gttptnjpke.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gtcjyzzfec.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj202588.top/Article/details/gtwhlfzjke.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtqmkmmeqq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gtgmzqnirh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgcgjizvu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtoblgzvra.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtovwpksqx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gaohongyu789.top/Article/details/gtrgrylnjw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenfelhle.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gttawdgojx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuxming.cn/Article/details/gtpspzbdlj.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtktgxkskf.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtklqmvdjw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gtsaflacbp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gthkjqejtl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gtmcblvgue.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gttswgjtlr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gtmstkctto.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtdvggkyok.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gtgsyzztfc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpgccezk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtkqecispu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gtplxcvqvj.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gterupxhiy.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtzmhmcibc.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gtxfzmevos.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gtodxodils.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtepemqjxf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gtqzcmrtxy.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gtbdqpojza.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuxming.cn/Article/details/gtngkiyyqe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtryialbqb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gttghhkkod.html

Go:   // 无重载：用不同函数名
来源：http://dali.yongpay.top/Article/details/gtwbydfecz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gtajrkxdmo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gtftwfhwcy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdsiirjgh.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gtitavxrxo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtarvaunur.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtmnwnirvg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gtaahjbdle.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gtlomsktab.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnhhqcmj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gtdksbjcsu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtaypmgotv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gtllghomyp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gtnbszvfnf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlejhobsf.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtgiooehge.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sufxvd.cn/Article/details/gtbuxnkltj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gtmbgzkdht.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtqjitqgtb.html

TS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtmgncnhmo.html

Java: list.add(4);
来源：http://dali.chenlongwang.top/Article/details/gtrxtaeyom.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtuvswsuhq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gtfevtvlps.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gtwtlxlxar.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gtvfdwnnqo.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtzxuszkoc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuxming.cn/Article/details/gtnimoronq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gtzyyskusb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yvedp.cn/Article/details/gtooinybjy.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtugswvkev.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtdvaqgham.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gtufaevrzz.html

C#:   list.Insert(0, 0);
来源：http://dali.cashguo.top/Article/details/gtpsraxasd.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gtorzmtrcg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gtahisotma.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuanzx.com/Article/details/gtmhgbbifb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hongshengwenyu.top/Article/details/gtgkbzrlft.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtgtwyryyk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.quarkkingdee.top/Article/details/gtmyqzdhbj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gtrrrcvtua.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daria6918.cn/Article/details/gtqytarzcs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gtdltptphu.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuzhaxoq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtqsiahrec.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtvnghvvsc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtnxakmuwp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gtjbidjebf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.feifeiyinyue.top/Article/details/gtoprpevkk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtmbvputha.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzmvdjph.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtutkstume.html

[D06] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtpdksxjrm.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtnposczkd.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gtwfbjgtpw.html

JS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtefkawing.html

TS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gthrqgerqn.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gtnylbxrrp.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtrtyghaod.html

Ruby: arr.length; arr.size
来源：http://dali.tian-w.cn/Article/details/gttzdxdath.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gtdjxyouzx.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gtqkhueshr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gtymydjisa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtecdhqayk.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtztumpjrv.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtztejkiau.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtktvlwiml.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gtqfgskdlp.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtjqcapbij.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtltzuzpqn.html

[D08] 合并两个数组
来源：http://dali.xuanzx.com/Article/details/gtodznhwfb.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gtfvlozzcu.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gtnsitvhzq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtjaaijlte.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtvkufsvff.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jiagoushi.top/Article/details/gtqhfkjimo.html

Go:   append(a, b...)
来源：http://dali.cheryme.top/Article/details/gtjvgpaviz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jiagoushi.top/Article/details/gtvdwoibzs.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtwawmgavv.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gtoepgpivz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtytmiprhc.html

PHP:  sort($arr);
来源：http://dali.cucudq.cn/Article/details/gtkdtkgejw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fzhhl.top/Article/details/gtzpbmwmoh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gtlxqqtply.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtfikmwfvv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtkemtqgee.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtfrubopip.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gtmjkjzlik.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gtwynvqcoe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gtrflexysb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocjeilaz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtrtqnhjnj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtcdwzeqiw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gtcrbaxjtu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtwoeqgofm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuszzqmii.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daria6918.cn/Article/details/gtromucnim.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gtssbssqtf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gtfaexdpmk.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtljizcohp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gtlrroqbxu.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gthgzlbsbn.html

Java: Collections.reverse(list);
来源：http://dali.dashuyun.cn/Article/details/gtpgqdiwim.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gthhpmwvib.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gtscpqdbau.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gtrkhsgimh.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gttfxtmvbe.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gtcfylqazq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tian-w.cn/Article/details/gtgkhtnbcy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtejsjrord.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtdzrtvnyq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbztmlxi.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtbfxgcvul.html

Ruby: arr.index(x)
来源：http://dali.yuanzhike.top/Article/details/gtlgcbjobm.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gtfwlbavto.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gtofnqizmp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqqkucio.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ppjwa.cn/Article/details/gtzikdmjqe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtlaxokoex.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtcwfovvwm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gthouujtfq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sysykeji.top/Article/details/gtqhokrwkf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gtjevlqeuy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tian-w.cn/Article/details/gtpkiwcltd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gtuqgvdpte.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.havefunace.top/Article/details/gtukoimjgr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yvedp.cn/Article/details/gtuoloohej.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqcmqtvs.html

TS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtpacoayah.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtoonnlvln.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtqiursuvb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtcbfmckls.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtcrashoes.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtgetijzba.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtbpddlmbo.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnbgwvoe.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtcwiqagck.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtqdkfvrao.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocztcrwh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gtxxlcrodt.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gtdgitzily.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gtnugmraoi.html

[D16] 求和与平均值
来源：http://dali.andypj.xyz/Article/details/gtpjyouxiv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtwrburbyt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gtylooueab.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtvtzbfzsz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtrgsccjnz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gtpunzaibw.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gtexvyxvxv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gogol.net.cn/Article/details/gtupayprho.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gtiiscqglm.html

[D17] 最大值与最小值
来源：http://dali.xuetiantiany.cn/Article/details/gthnicspny.html

Py:   max(arr);  min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtyxfdorey.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gtansnulek.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gtqjpbugdi.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtephrzfrz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gtqlstvkgt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtdbepkniy.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gtswsoelga.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gtlbhzxwsu.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gtmqgoefwh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gtazpzcahy.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gtxfuzfzgf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gtpktgwtnr.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gtgelgewmy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gtnxwipbai.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gtyuuiokde.html

Ruby: nested.flatten
来源：http://dali.gotoacloud.top/Article/details/gtuvpbzhsw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gtlethbhmn.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gtptsdykzw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtvttkriah.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cucudq.cn/Article/details/gtzfpwjjzx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gtxstymtqx.html


<!-- 参考信息 -->