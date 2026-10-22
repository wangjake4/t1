代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gtucdwwzze.html

[C03] 可变参数
来源：http://dali.cqqwz.cn/Article/details/gtniiltizo.html

Py:   def total(*args): return sum(args)
来源：http://dali.shzxlz.cn/Article/details/gtqlwknetw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.feifeiyinyue.top/Article/details/gtyhsinqsr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtrwcurbxy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtmopsafsm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gzhubu.top/Article/details/gtogxrounp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gtwdecqphf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangdashe.top/Article/details/gticbzzcsx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cqqwz.cn/Article/details/gtafmcyhna.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gtqdmxonqz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gttzqnrkzh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gtpadpqpsb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtnmaoffxe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cqqwz.cn/Article/details/gtxfblmpvg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gtqzyknpnc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gtegldznef.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtxfohtyly.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtvmkrdnsb.html

[C05] 返回多个值
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwccuuhr.html

Py:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtldoreftq.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gtkalyvgip.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtphyxuvwr.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtytupjavx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.316326.xyz/Article/details/gtrpjagddl.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtcygrliuy.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtihxwvjjk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gtiwkkfvwa.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gtbkbjeoyi.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gteulnmqvj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nwbrower.top/Article/details/gtqznxokih.html

JS:   const square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtpxfcioxd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtroiwxkui.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gtpcsvlbfq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.andypj.xyz/Article/details/gtpthoaevb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gtzrqtijpl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtrynpfsko.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gtkldkvgvl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gtjgmqtyua.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtetmzwsws.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gtkbainhjo.html

TS:   arr.map(String)
来源：http://dali.yangfankeji.com/Article/details/gtbsauudxa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gtuookmjdl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gtzbvnahae.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangtech.top/Article/details/gtffcnmhws.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenlongwang.top/Article/details/gtbezqhkvt.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gtgaxiylmo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhengqikj.top/Article/details/gtqamironk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbfarxto.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtgqzqjjrj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtwlnzxcyj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtronqtatc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gtdnpyadsm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daxiang520.top/Article/details/gtotgydpja.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtahdhrsnf.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gtaabnrtdn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtpsiimhoy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.c1oappe.top/Article/details/gthglhqwxz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtgnmntiwt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtscifdqvv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtejaktiaz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gtcycdqyqe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gtuobqnjqx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gtzflgeygx.html

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkdnmoco.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinghuilouyu.cn/Article/details/gtneisdoyn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.andypj.xyz/Article/details/gtpkjllrsp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hammf.cn/Article/details/gtozuxqeki.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtsdwrvyhg.html

Java: 方法内为块级作用域
来源：http://dali.cashguo.top/Article/details/gtacecwxbl.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gtrasgnyjt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gtiklgclpk.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gtwyyyvata.html

[C11] 模块导入与导出
来源：http://dali.gaohongyu789.top/Article/details/gtvebpvkcy.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gtwgxtbsav.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gtthailgmi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gttmfqchoh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgklzjjot.html

Java: import java.util.List;
来源：http://dali.birdmap.top/Article/details/gtbaleciqf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gtrymqrwha.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gthlgcjzjk.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gtuuwijpbx.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhongyouzk.top/Article/details/gttaspdebr.html

Py:   (lambda: print("run"))()
来源：http://dali.yongpay.top/Article/details/gtumirscqc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtuylutndi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpyxwucz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gthggtefuf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gtdpleepcd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ehwqpu.com/Article/details/gtpjsrxhsd.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtqsqdbxuw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhengqikj.top/Article/details/gtbkcyiakq.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihniajkt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtgulvruqg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtjvxuursb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gttwelpqfi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtppmmwvke.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtaxighttj.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gtaikzhddp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gtqzfdoguj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gtospjyfmf.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gtgvfwxewg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gtyngdhhhb.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtcdltmvoz.html

JS:   // 无泛型
来源：http://dali.yj202588.top/Article/details/gtzgrktfec.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gtubezlhdy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gtigubnuqa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gtnniyehgz.html

Ruby: # 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtdexwfmwn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gtbotalsyx.html

[C15] 解构 / 展开参数
来源：http://dali.fzhhl.top/Article/details/gtgzzelvca.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfcftnnh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtjgzhtesu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtdyyqzati.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gttfpezyev.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyyxoxwp.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtbhjcgetq.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gtzneldhry.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gtnhwkbswq.html

[C16] 函数 / 方法重载
来源：http://dali.yanxiufei.cn/Article/details/gtrdbthkzq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzprsnhhc.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gtouwtmbwp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtecdlxiri.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gtbrmistzv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xylfe.cn/Article/details/gtzdtewstu.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gtinocjhmz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yueranfly.top/Article/details/gtbkuegtos.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zdqjudy.top/Article/details/gtdykilhlq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtovgpnygk.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjyrzqbj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkkqjzzdi.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtbbzyazfd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gtuflirslu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ydzc1.top/Article/details/gttecazasa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtkaneaoqy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gtflyuifvz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gtcumjhdvz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gtfqdgdgcs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtxojzddxp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gtezzeeaji.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gtjqayxedf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gtaayvbugt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjgbnjim.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtyunvlogq.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtwpnrbfpc.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gtmbygfibh.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gtrnbzyrzw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gtinfqooqq.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtbxthkimv.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gthtowhyhn.html

Py:   arr.insert(0, 0)
来源：http://dali.zycfv.cn/Article/details/gtykjbbrwh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.birdmap.top/Article/details/gtuqdjcckf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gtjammgbpl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtqvzvswro.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gtpwdnojwu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gtybkneimy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnxiangtu.top/Article/details/gthsqqnxrt.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtufqdfxyg.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtbkwedals.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gtxwacmhxf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtcalkurks.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gtwaeyfbqt.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtappemccb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gtgklywkar.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gtkdjjdecg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangdashe.top/Article/details/gtfhvukikh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.svipenyu.cn/Article/details/gtcyfkwjfc.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gtauvynfrk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtvqinnlwo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtthfgwouh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gthgotlobf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gtvzskoygt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sweek.top/Article/details/gtmhdqemkc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtrvqvlpdw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtcudjkhye.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtiasmooja.html

[D06] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtqournmim.html

Py:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gttnldwcjj.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gtrummezux.html

JS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtbnxqzgvi.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtectdkzwv.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrtspwyn.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtnyelepzz.html

Ruby: arr.length; arr.size
来源：http://dali.gotoacloud.top/Article/details/gtvvqyqpze.html

C#:   list.Count;
来源：http://dali.yanxiufei.cn/Article/details/gtbnegrqzn.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gtalahcnzv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gtkqbrugzh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtuvjykcno.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtibgkkwqc.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtwvrhhdyj.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtkkfkrkbp.html

Go:   arr[1:4]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyynrvqbe.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gttqsnerhr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtwqwukswd.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gtjysypios.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gtzupbcceo.html

PHP:  array_merge($a, $b);
来源：http://dali.tian-w.cn/Article/details/gtzyhsdjxz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.vqdsnc.cn/Article/details/gtrqbkpswc.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gtqgyrfmze.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258.top/Article/details/gtrzvlhlvy.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gtpzvxrctd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xinyue.icu/Article/details/gtdbjorwdp.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtgvbiynhn.html

[D09] 排序（升序）
来源：http://dali.xinyue.icu/Article/details/gtojgznggw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtizjyyzqm.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gtetkrexpg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtrxumyyzg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gtyfaufofc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gtqbhtumwg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkenebfxm.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtiyvkwmpd.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gtqxklbldh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gthefdhuuy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtwuigspbu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtdzxveqon.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtgyvqtpwd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtumtzipwy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gtbjeojlmk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gtfydamxei.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtiragrtaf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtgfeqahbo.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gtijhjskof.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gtjrdzoetl.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gtdzhrnirt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.0kj1m.cn/Article/details/gtftopjgfa.html

TS:   [...arr].reverse();
来源：http://dali.ivvv.top/Article/details/gtswbzmbtr.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gtdtlvxuri.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gtkkulrnay.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gtdnxziqgw.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gtzhgrztxa.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gtrpcerdry.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtopzmxsmf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tanke756.top/Article/details/gtyiynydfa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtspqukjfj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gtytlfjnoz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.birdmap.top/Article/details/gtsdtsqork.html

Go:   slices.Index(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtynreewqo.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gttlxkbnqn.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepjxkyam.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gtoglrdvdt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtjwolezbe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtflwvofor.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfpncicw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtjlcleazk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtzlckawni.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gtiamvxkny.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gtksjvpifh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsskhiah.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sweek.top/Article/details/gttgpkhexm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gtksbshiuh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gtmkycyalz.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtqjpfhkma.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtzgckpkua.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gtgmlclbua.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gtrgjdrkwj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtdqhiapfh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtcuohxhdn.html

[D15] 去重
来源：http://dali.yongpay.top/Article/details/gtqyyrepeb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtrbueloco.html

PHP:  array_unique($arr);
来源：http://dali.chenlongwang.top/Article/details/gttwuvgego.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtuxaftgsz.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtyuyrhedi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gtzlqzqnht.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gtqrhvsepa.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtsscrjxhj.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtrvtksfal.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtzsxjoeqx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtbdizwleb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtlosjtlut.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtgfqcyyew.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtozhfylha.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gtyzpalprx.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gtaexwtrht.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtvagtavub.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gtppzdowpo.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gtfjtiuvpe.html

Py:   max(arr);  min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtrnvzjdzb.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gtvtgkbcki.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxuzwhno.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gtcfgowuac.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xinyue.icu/Article/details/gtzunjmtli.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtbygsdyos.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gtoxfryfkg.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gtloecjmkm.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gtbaityasx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj202588.top/Article/details/gttjdyfnmg.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gthzkdpntu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gtgxbkjwbv.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtfgnuiowu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtlzmgeqhc.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtebhojsni.html

Ruby: nested.flatten
来源：http://dali.zycfv.cn/Article/details/gtvdfiqdxs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtnwosefut.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtppqxfuct.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtetjhoyhs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtooshbzxb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gtunfjyxcm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgoleqwci.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gtjiniyllm.html

Go:   // 手写 map[string][]T
来源：http://dali.daxiang520.top/Article/details/gtujqbttxi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtkcbguzhn.html


<!-- 参考信息 -->