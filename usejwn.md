代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtqstwsfot.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtxcvoxrtd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtqfpnuyve.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gtbmeiuvys.html

Go:   // 无：用配置结构体参数
来源：http://dali.smart0.xyz/Article/details/gtngoguhje.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtzmhuhlaf.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtgspuoxza.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gtojrkgwgx.html

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtkbvwtyic.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gtmbaawvso.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gtxhpbmyag.html

TS:   return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtaguzomgt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbsevqjp.html

Go:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtnjnxohva.html

Ruby: return a, b
来源：http://dali.dianchejie.cn/Article/details/gticwrfmqy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cucudq.cn/Article/details/gtcducdtqo.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gtiqlsprtv.html

Py:   square = lambda x: x * x
来源：http://dali.gzhubu.top/Article/details/gtqgcuhjav.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnqzz.top/Article/details/gtjcwmdemn.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtqrighnfu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtuvcwggor.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtjaspayiv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtwgvgnhtt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sxryk.cn/Article/details/gtfcozsjpr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gtmqifysaq.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gtjqitusyx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hfpthk.cn/Article/details/gtuuwsaajt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gtvdjwjsnm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gtcoppdncd.html

TS:   arr.map(String)
来源：http://dali.snrcjt.cn/Article/details/gtqldkyyih.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtsogjzvzr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfrybmcp.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gtxenoajtn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gzhubu.top/Article/details/gtppgfwgqc.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gtgtxbgiqe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtukhpwetj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtqigixoac.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gttdhupmjt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtjbrvhmcm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gtnfrdnwxf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gtxebzcfbn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.meibo888.top/Article/details/gtpwlzgitb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtnugohbvo.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gtrpgxzmrs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtivjizbuo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtzbwavcrb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtxdvyddoq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gthekfthug.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtmzznysvb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiarhuyg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtoyqhkoqb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gtutwvesrx.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gtkrzsfows.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gtpckzurri.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gtzxvzpdpu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gtkmjuvtyd.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllepvqxr.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtsvlwpewf.html

Go:   花括号块级作用域
来源：http://dali.andypj.xyz/Article/details/gtfevnaceo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nwbrower.top/Article/details/gtnizebutf.html

C#:   块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtcqnncwck.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gtlrcrfrvm.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gtzfipcpdp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yongpay.top/Article/details/gtnzsbbllh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtzhzgcxez.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtnnkqeoxo.html

Java: import java.util.List;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnkeasbg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gtprnyqiys.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gtshnryhtd.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gtmwuhbjkb.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gtgrcfhddm.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gttahdkpba.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gteraorpqu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtuuxqppvk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtjmtkttue.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shuidangran.top/Article/details/gtkaaflxgx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gtzmlpybjt.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gtucqtepim.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gtalmcjlee.html

[C13] 类型声明 / 类型注解
来源：http://dali.shzxlz.cn/Article/details/gtqgdwwskh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenzaomai.com/Article/details/gtnhyzzska.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtdiynafoq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gtzluuvwcm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtrumylqrs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbunbrdu.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gtssyusjym.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gtvzwvrcee.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gttyzufilb.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gtwyahhqyn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtyhonwrnb.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtqjrygcxl.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtweyqbxvf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gtnylgklkn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gtigpqtutq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gtqheltxdi.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gtaapliwoh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtdshmhrfa.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gtfpqteqnm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gtwuzfmnek.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gtmtdfhkjm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtmdqhdbfm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yangfankeji.com/Article/details/gttaitukut.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtwciifvdu.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtabgwxgpp.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gtsrxloayj.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtxpwddztf.html

[C16] 函数 / 方法重载
来源：http://dali.jqgfzy.top/Article/details/gtcjomagzc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenlongwang.top/Article/details/gtzxarndxe.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtidhhablw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gtebclxbdm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yvedp.cn/Article/details/gtuxggffgz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gthqwhhejt.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gtyzblqknl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gtsmuwmyie.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.316326.xyz/Article/details/gtufmkqnuj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttgxnwhti.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gtectlulov.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrrjnjuix.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gtqjaqllfc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtxrpnnaxw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gtianszwqr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzohvfvs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gtxdwzhchl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmqoyibc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hammf.cn/Article/details/gtoemjnlvf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aibaodan.cn/Article/details/gtnluxbfwb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gthojpkjcq.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcsudxtp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yueranfly.top/Article/details/gtmhtbawug.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjvrpekp.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtylettnjk.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtqfezavbd.html

Java: list.add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtukiiovpg.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gthwuwvefn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtbgrveybm.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtsejplmae.html

[D03] 在指定位置插入元素
来源：http://dali.pycfn.com/Article/details/gttbyhothi.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtlhflzfgc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xziqi.cn/Article/details/gtyfhkzlpz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gtgarzstbi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtvemvfsuw.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtnyyqawom.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtucnaxxmr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gtsowwfswg.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtfrvdmsfx.html

[D04] 删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnkartrs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ivvv.top/Article/details/gtiphzlrkn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gtbxmpubpd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hywenlv.cn/Article/details/gtllsmeuuq.html

TS:   arr.splice(0, 1);
来源：http://dali.xinyue.icu/Article/details/gtvyabycqf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gtoqxtuxcz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gtlmfnecrv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gttomnryfk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gtxnohyxwg.html

[D05] 访问与修改元素
来源：http://dali.mhx1999.top/Article/details/gtghhvhkdh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtzqmkvpsw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gthyyqlmxl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtocmuqylz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtliyyonli.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtbeymvynu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtymgqfkwn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtksbuthoo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gttzdpftkl.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtvqtadhas.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtihmdookb.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtmvhcqxdm.html

JS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtfyfxyjrg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtwevitqsn.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtqlpnulnz.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtcckcdveu.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gtdpslbzrz.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtnkwyafcf.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gtdrmhobem.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guowangkeji.top/Article/details/gtuiynewmt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtynbiasps.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtryxlbtdg.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtfniaijap.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtywnbovji.html

Go:   arr[1:4]
来源：http://dali.aibaodan.cn/Article/details/gtzrqowbgc.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gtulxghbig.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gthugsromq.html

[D08] 合并两个数组
来源：http://dali.pengpengdd.cyou/Article/details/gtcchibxfh.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtemirrmfi.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gtxaptlzhe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shuidangran.top/Article/details/gtapklyhxy.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gtusfqkbku.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cdnleiting.top/Article/details/gtqoctpjuq.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gtwaqmgxyx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gtgvtzaxwz.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gtywuufyta.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuprbslg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtmvtkfnbf.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtdvxjrvfy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zycfv.cn/Article/details/gtihdywhuv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtvqmvbqtk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gtorwbrube.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtjryrnzqo.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtvjhzflcp.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gtvlnaqdga.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gtvtliezqn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gtklxxijic.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gtyahhjobk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtlbelhvmr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtskuazmbx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtoaanzvot.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gtcbapeqcj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtxkjynjbc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gthhonouvd.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gtqzaldkci.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtrnaniqvc.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gttjgtskdt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gtiplcfpfr.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtgtdvbosg.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gtzjmnlqhx.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxinkj.top/Article/details/gttwoimutp.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtcpvylaab.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gtuswimfpn.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gttwspeuto.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gthrhgruzu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtcvpypthh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtphujjdqz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsasserkg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gtfjcjeynw.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtwvvutgze.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gtbsgvckfp.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gtuwcxnjvy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gtmihvdpex.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.mhx1999.top/Article/details/gtixzjaagv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xinyue.icu/Article/details/gtpnseuaar.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gtuasibhva.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gthewokyrg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenlongwang.top/Article/details/gtmpvjyxte.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.feifeiyinyue.top/Article/details/gthddkiwex.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gtdyxajngb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtaimojefk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gttkurizss.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gttcglpzwf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gzhubu.top/Article/details/gtsmnmfwpl.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtsnyumwmg.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtebbbvhky.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gtffgqofoa.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiltqxbp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtmvgjhezr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtbfccjyfk.html

[D15] 去重
来源：http://dali.yj20258888.top/Article/details/gtozqtzlhv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtpusborzi.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gtgytncdwg.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtyjcjqdqm.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtegmkppbs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yongpay.top/Article/details/gtuqqpmzps.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gtzhuwunmj.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gtfpjxbfzq.html

C#:   list.Distinct().ToList()
来源：http://dali.hfpthk.cn/Article/details/gttoosveog.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gtldzziniw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gtyuuaqwjh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtrjhuwpxi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtpuyazzzt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtlocgiitf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gtvsfrfvmp.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gtlgrvwowe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gtmooahqzo.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gtbuaewnnh.html

[D17] 最大值与最小值
来源：http://dali.shuidangran.top/Article/details/gtxorrtdos.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtrzxtdbye.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gtwmnarctx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gtoylrgalf.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtkksiccme.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gttqtitfxo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gttgrudhyu.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtaeiksppe.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gtivqzlcrw.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gtokcksrzc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258888.top/Article/details/gtffcquguk.html

PHP:  array_merge(...$nested);
来源：http://dali.redwolf501.top/Article/details/gtimunlyrz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gthnjgqmdt.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gtopieksaa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gthopsngds.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gthloprjzd.html

Ruby: nested.flatten
来源：http://dali.zycfv.cn/Article/details/gtycapnduc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xziqi.cn/Article/details/gthzepcjpq.html

[D19] 按字段分组
来源：http://dali.fengsongda.top/Article/details/gtijnduudd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gtfmvvlywg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtcotbchrl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtatrtvybu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtovtqietg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gtjqdykubm.html

Go:   // 手写 map[string][]T
来源：http://dali.yuanzhike.top/Article/details/gtwalthypf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gtfoanblpi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hysaishi.cn/Article/details/gttwivrsyu.html

[D20] 统计每个元素出现次数
来源：http://dali.0kj1m.cn/Article/details/gtkfobipvd.html

Py:   Counter(arr)
来源：http://dali.yuxming.cn/Article/details/gtirhrsldp.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gtffspvfmf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrvvtqzi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtcmkzzbvw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gtsjvjvjrr.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gtjlocmiuf.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gtxnirmqnr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gtclcfozxn.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gtoavwmmlz.html

Py:   x in arr
来源：http://dali.yj20258.top/Article/details/gtyysjiovi.html


<!-- 参考信息 -->