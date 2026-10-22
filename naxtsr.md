代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.ppjwa.cn/Article/details/gtjqmdjmrc.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gtgudwnsbt.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gtrxrtgzhe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gtrwkijzfi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dianchejie.cn/Article/details/gtoycufekg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmpaghxwo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tian-w.cn/Article/details/gtbvvqytoa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pengpengdd.cyou/Article/details/gtmkhfczmi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gtumrvmtcw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gtdndzdcsk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.havefunace.top/Article/details/gthgnylmjk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.birdmap.top/Article/details/gtvnmxgikq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tanke756.top/Article/details/gtfjehsspi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtdxcmfvug.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhongyouzk.top/Article/details/gtnuwezbwa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gtezfgaxea.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gtuojgklwn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtdjgertio.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtonguuelr.html

[C05] 返回多个值
来源：http://dali.vqdsnc.cn/Article/details/gtqomdpanl.html

Py:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gtlekmjluz.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqqtaxjh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtffjnhcvu.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtbgiobxip.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gticomnplw.html

Go:   return a, b
来源：http://dali.andypj.xyz/Article/details/gtriumreiq.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gtujauadtw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gtkhgobrhc.html

[C06] 匿名函数 / lambda
来源：http://dali.ppjwa.cn/Article/details/gtjcoavfvp.html

Py:   square = lambda x: x * x
来源：http://dali.guowangkeji.top/Article/details/gtoncfzijd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnqzz.top/Article/details/gtqvpsvppb.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gthiellagp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtjwnurqsz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gzhubu.top/Article/details/gtdcgbbmar.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gtaqqpyvzi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnqzz.top/Article/details/gtdzclddpa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtvqdoupaj.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gtclnoavkn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gtzhddspfc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtggzyfvuw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.feifeiyinyue.top/Article/details/gtoslbzzkt.html

TS:   arr.map(String)
来源：http://dali.ppjwa.cn/Article/details/gticokjwty.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.0kj1m.cn/Article/details/gtwjgqwwni.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhixingplan.top/Article/details/gtoluroevm.html

Ruby: arr.map(&:upcase)
来源：http://dali.haohaochexian.top/Article/details/gtflgcwyqu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuetiantiany.cn/Article/details/gtdremdwpf.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gtncjisgch.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zdqjudy.top/Article/details/gtgejyekgk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gttyaqayak.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtauvhfkft.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiibjdmse.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gtkmbqmsga.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gtfzozpfdx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shangyingyoupin.top/Article/details/gtxgvaxloc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtnarkwbtw.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtdozahhub.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gtgawjurgq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtzhklomgo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gttsgnmzow.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gthptnvcxd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gtqqfgwdgd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gtzdwxolta.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gtoarnxbyy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.haohaochexian.top/Article/details/gtanhyvikz.html

[C10] 变量作用域
来源：http://dali.haohaochexian.top/Article/details/gtpbbwtbom.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xinyue.icu/Article/details/gtyawemrlh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gtfpxfxuwa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cheryme.top/Article/details/gtvowajojv.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtyzypjaiy.html

Java: 方法内为块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtlzjoqxhh.html

Go:   花括号块级作用域
来源：http://dali.smart0.xyz/Article/details/gtvlyvcadd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnxiangtu.top/Article/details/gtqljrityq.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gtkeabhuro.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlyypzsg.html

Py:   from module import func
来源：http://dali.xylfe.cn/Article/details/gtpsiqmpyr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gtnopevhiq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmumkfebm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtjnuyzmzi.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gtgveqxlbz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gtcxmvidvo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.meibo888.top/Article/details/gtgxbgwxvj.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtsonsrnfu.html

[C12] 立即执行函数 IIFE
来源：http://dali.andypj.xyz/Article/details/gtymtymjot.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gthsbazbcw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtpcomlmhr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtzamfmxhk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtkerindjx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jlsjyb.cn/Article/details/gtntcmcwod.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yvedp.cn/Article/details/gttodsxrko.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigfzy.top/Article/details/gtpmagopay.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258.top/Article/details/gtvelukhoj.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtsxbhjefc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtdomdgoel.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtbumilcjj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258888.top/Article/details/gttywpqrno.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtqufvozgj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtnlcmnetf.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gttigjibzh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gtynbpckau.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuxming.cn/Article/details/gtbilfbljm.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gtoudhmiuo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrlyimyg.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gtperhiywq.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtovqdtzlg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hfpthk.cn/Article/details/gtohwalslc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhoulong.xyz/Article/details/gtbfczmkhi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gtigouyuuy.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtkrblsnml.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hywenlv.cn/Article/details/gtvlbmgmkp.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gtxwwkfava.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuanzx.com/Article/details/gtwhlyiidu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gtvcksbuky.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtiywyjmly.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gtkvrjtvla.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtbvjshzhn.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gtbnfnuour.html

Ruby: a, b = pair
来源：http://dali.havefunace.top/Article/details/gtkwjygkdr.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gtolmkngnr.html

[C16] 函数 / 方法重载
来源：http://dali.shangyingyoupin.top/Article/details/gtobcghxxz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gteirmmyqx.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtbmmdmtov.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cucudq.cn/Article/details/gtvczivshj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtbrooogdn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gtezawduib.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gthieofnhs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fengsongda.top/Article/details/gtwoucdhki.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zdqjudy.top/Article/details/gtefqppbyq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvphrfnkk.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gtyzkiivbn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtndgghlch.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gtvvdwhftv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.smart0.xyz/Article/details/gthxlrtviv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnqzz.top/Article/details/gtpzmxyqnf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtsfcktrst.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gtcnwcflpk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmlyttbs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gtcfjoprfo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gtjulkrusm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntvrforr.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gtuajcjsry.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtdlsxxxmq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gtxjvpvncd.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtzzoscppk.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtdzucqqsb.html

Java: list.add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtltvetque.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtyjluscjs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gtidjkixyk.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gtjoxlcuyk.html

[D03] 在指定位置插入元素
来源：http://dali.0kj1m.cn/Article/details/gteyowragz.html

Py:   arr.insert(0, 0)
来源：http://dali.iojbl.cn/Article/details/gtnlktogww.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sufxvd.cn/Article/details/gtjsgzmjjp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gtrfwxvvwb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtlgypqccl.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtkedkkjrb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gtzvcpeghk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gtgpjkptye.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtablunvbe.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gtcziyphyn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ivvv.top/Article/details/gtwyzpeimc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gtaddlhhal.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtdznbwreb.html

TS:   arr.splice(0, 1);
来源：http://dali.havefunace.top/Article/details/gtuqrutabf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznaqaeju.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gteccwsjuf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gtfcsglopa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gtfqvabkun.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gtonhtnlbz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gteuyvosfb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtcapthwsq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gthyiytsep.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtbuyvzxjr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yueranfly.top/Article/details/gtfbkareta.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtoglzmtmd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtgayvftkw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtsirroajn.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtjwrmxfus.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtekiqbkar.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtjdgwfdxk.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtyusasgis.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gtkdbwkkwz.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gtzqttyros.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtomzfcsrf.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtcawygckt.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gteakkjgpg.html

[D07] 切片 / 取子数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwvvdigu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gttbbyixea.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtagprcdok.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtclkhvzwe.html

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtgwufwhax.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtihimocue.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtslufhulj.html

Ruby: arr[1, 3]
来源：http://dali.guannengcc.top/Article/details/gtwotudwvw.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtiwutkvdl.html

[D08] 合并两个数组
来源：http://dali.fengsongda.top/Article/details/gtuwyhupeh.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gtnxmzewis.html

PHP:  array_merge($a, $b);
来源：http://dali.dianchejie.cn/Article/details/gtdvgmddgu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gtvuodbnbc.html

TS:   [...a, ...b];
来源：http://dali.vqdsnc.cn/Article/details/gtyiurtbns.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gtkvwaqqjp.html

Go:   append(a, b...)
来源：http://dali.aizwys.cn/Article/details/gtpmjbhgbj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtjlczgrlx.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtribdbsod.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gtqklnmklm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtedktyqqh.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtzjuileth.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gtxufbybya.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dashuyun.cn/Article/details/gtcdoeodsv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gtrjnpotit.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtecqwingn.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtayeehpbj.html

C#:   list.Sort();
来源：http://dali.zhixingplan.top/Article/details/gthxvvknfp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gtuydmjoot.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gtsmczllwq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtrpshmhsf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtpkaapute.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtkqsuxvyq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cdnleiting.top/Article/details/gtvpgpzkoa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gtoviqvzov.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ehwqpu.com/Article/details/gtnurcarxl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gtdmumlpwu.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gtuxxxmgve.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gtesbqkchg.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtwjismspc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuebzeqtt.html

TS:   [...arr].reverse();
来源：http://dali.tanke756.top/Article/details/gtvbjvmoof.html

Java: Collections.reverse(list);
来源：http://dali.0kj1m.cn/Article/details/gtxoxmxbki.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gtgorewbdy.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gtqnuqczml.html

C#:   list.Reverse();
来源：http://dali.yuanzhike.top/Article/details/gtkjityjra.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gtltxattqu.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gtrsgluqwz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtgdwdiklo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gthllzbjld.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gttocfgdmm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gtlnywtkcx.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtlwwlzcsd.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gtvtqaeyys.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gtcwntflxi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gtwetknvtj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ehwqpu.com/Article/details/gteabmdlwt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gtsmztoqhh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtxhdovygs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtrnetmmhj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdmvhawp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.bjfxy.top/Article/details/gturtujzru.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtbhtshcvf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gtzrlgsrrs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtkkicqnav.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gtowxyvkjh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtujjnhgzt.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtcntdzwvm.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqrbfzok.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gttjzizrnn.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtjadxrthp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtyzwzzzim.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtntekxbuk.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gtuqocerzh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtrqmedlub.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtnqiknily.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtwsoqcpfx.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtfrxmrftf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gtbjwvncxm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xinyue.icu/Article/details/gtfkmppeip.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gtyqhfomks.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gtybxbosfk.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gtrajnaocr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gtddvehwuh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gtvhytvakb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtvpvqjlie.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtrwbnbsvt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gtfdzbgaot.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gtpmegazgx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gtkyddwymm.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gtcbytphmv.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gtpciwjsoj.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gtgnpysyxn.html

PHP:  max($arr);  min($arr);
来源：http://dali.iojbl.cn/Article/details/gtzmbgjnae.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gtflyspwei.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gttaupuooy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gtaaexkiix.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtzqklomxa.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gthxnjsqqq.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gteisefstd.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gtdtmxfsqd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gtqwyqpwqd.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gtdfabktgj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gtvqzkudfj.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gtreccqnrn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gttnwgznpt.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gtajafenpk.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gthicnjsno.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtgysygqeg.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gthgoyfbgp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gtviqcmpbg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gtcizshyrm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttodaengz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtjybapany.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtwwbdjz.html

Go:   // 手写 map[string][]T
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcfjfloy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gtsoffrazd.html


<!-- 参考信息 -->