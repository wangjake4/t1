代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtpfzkypct.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gtaiidnsqa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gtlajeaixo.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttoprcoh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gtsaiqqcbw.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gtgbjtzxhp.html

Py:   def total(*args): return sum(args)
来源：http://dali.vqdsnc.cn/Article/details/gtktndydci.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xinyue.icu/Article/details/gtjbrgmkrv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtnoggtjst.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtsuvfznxm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258.top/Article/details/gtdubhpirt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gtmnylbsrr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gtttdcjyur.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gtxkmnnrqc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gtrxkytygx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pengpengdd.cyou/Article/details/gtjxeldcfb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtrjrnqxxl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gthipijsak.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gtxyckroaw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigfzy.top/Article/details/gtmggvsobb.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gtyfhjkyxf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtogehdsxq.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtocqgdner.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gtssalvpvc.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtxkzryytj.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gtqybiocxh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtnwjmuzlv.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gtmesduiuq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gttxopewdv.html

Go:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gtllsgbsdm.html

Ruby: return a, b
来源：http://dali.jinqigufen.top/Article/details/gtjqyigqda.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gthgcdfdif.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtmtmkbb.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gttefxnkla.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gtiysmivlv.html

JS:   const square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gthnpgaitd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtouqrhxrp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gzhubu.top/Article/details/gtajkrhkyu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsshiulw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gtuvljiehc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtohbahiyw.html

[C07] 把函数作为参数传入
来源：http://dali.c1oappe.top/Article/details/gtpjgvzptb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gtmneymhjb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtnftyldzy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sxryk.cn/Article/details/gtlyauoout.html

TS:   arr.map(String)
来源：http://dali.nanxinkj.top/Article/details/gtikrpzyjy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtkffbzvci.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrewlwqq.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtqyurbvww.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gtbqijbung.html

[C08] 闭包
来源：http://dali.yongpay.top/Article/details/gtieniypbd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gtawuuegez.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.iojbl.cn/Article/details/gtyhpizxfs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtyuwclztr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtzwnlbqqe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tianlin.xyz/Article/details/gtmdrzmrpt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhongyouzk.top/Article/details/gtrcawbqve.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gtvcwlgyjt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtnaytfhnm.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gtrhfdqdfk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gttflkbjyv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtxbkvhsrx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtbbuuwgmm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gtjbgukbsg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtasdawyir.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gtwqnzyvqc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtwpajistt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtimtdkfmz.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gtejngshwx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gtaczmmowa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yanxiufei.cn/Article/details/gtsnnggaja.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtpuqximgd.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gtyzujjnmh.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtgoizmjln.html

Go:   花括号块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtyktufdog.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbvhxxyr.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtlsrtsynp.html

[C11] 模块导入与导出
来源：http://dali.sysykeji.top/Article/details/gtsxogzkth.html

Py:   from module import func
来源：http://dali.yongpay.top/Article/details/gttkyjqmuo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhengqikj.top/Article/details/gtuiqascho.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtskurvazq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gtppqnsqwl.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gtizswgdbo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtyrlpsroe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gtmgpdukrr.html

C#:   using System.Text;
来源：http://dali.guowangkeji.top/Article/details/gthpssflwf.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gtoyizulzj.html

Py:   (lambda: print("run"))()
来源：http://dali.xinyue.icu/Article/details/gthrcvlgec.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gtkfkhfocg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtzcthqpxr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtwzqnuodd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gtnxxpylfc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ybcxt.top/Article/details/gttmoitdos.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258888.top/Article/details/gtdigaswol.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gtuausvmvg.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtzhhdixrp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gthewhzjfg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gteflvzyri.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shangyingyoupin.top/Article/details/gtpzqyqfxw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtpieogycw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtlliyragj.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gttcxdpkal.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gtednvdzqi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tianlin.xyz/Article/details/gtaopjemzj.html

[C14] 泛型函数
来源：http://dali.ydzc1.top/Article/details/gtrftmbbfd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gtmsuahtek.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtzkfcfjrv.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gtwomlltbb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gtxvicaakw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxinkj.top/Article/details/gtuvxljvlf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gtvunarulq.html

Ruby: # 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtjfslftfe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gtsyyephmf.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gthhcphpws.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtrssiqmww.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gtclrjuafv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gtqwhqtnqi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfugngsu.html

Java: // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtxphlozfz.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtrjxpbynj.html

Ruby: a, b = pair
来源：http://dali.sweek.top/Article/details/gtatmsybbh.html

C#:   var (a, b) = pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunmmegye.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gtfqpfyfpf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gtmwghrpoq.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gtixogmkcf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtkiancmok.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gthekkmvnn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtmyknfebf.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gtfufdpkah.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnqzz.top/Article/details/gtdcxigiml.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtemxzbqcx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlajbkrgo.html

D. 数组 / 列表 / 集合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaruofweb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzxjsphxv.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gtlgmymalj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gzhubu.top/Article/details/gtmwjvejll.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gtvjbveprd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtjbsqdpum.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangtech.top/Article/details/gtgujdlchl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gtdkijyqad.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gtrbcelhzc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuxming.cn/Article/details/gtdpdwqlka.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigufen.top/Article/details/gtvxrbqjhq.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gtgulthmva.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yangfankeji.com/Article/details/gtajelnkmj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guannengcc.top/Article/details/gttkwwkfko.html

JS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtpormumtx.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtsqfroixt.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gtyymdyerk.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgfzy.top/Article/details/gtrbuiscsw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtwdxiqrlg.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gtaiybulin.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gtladlpbxa.html

Py:   arr.insert(0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucnaysxy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.havefunace.top/Article/details/gtvtlozfin.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258888.top/Article/details/gtuhqrkuxy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.havefunace.top/Article/details/gtfxpdhgyr.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtgxrsibwt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtvpgpypvr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gtbjvnwvrh.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtdxarumkd.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gtjrqbfmid.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhoulong.xyz/Article/details/gtfoafyizi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsqpwnkj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.0kj1m.cn/Article/details/gtgwwbdbpd.html

TS:   arr.splice(0, 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtntrumbqe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjodyfxeb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gtkrokfoak.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigufen.top/Article/details/gtjcagfssb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tanke756.top/Article/details/gtncwbglmn.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtthntknmu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtyylnstnx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtnrmyciff.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtqeemrfqv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gtpnhvimdm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gtzmggkthu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtgxroptne.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtgtyafxtz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gttlquirlo.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtzhbytvgk.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtlogbxxro.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtmzqffvoc.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtljabvned.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gtlessqved.html

Java: list.size();
来源：http://dali.aizwys.cn/Article/details/gtkupturri.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtmkceuzqj.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gtmphoynpv.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnejtzgb.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gtmfbybpba.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gtqnzryyye.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gtntzdpasr.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtiuxoylbt.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtmtpkzsey.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowiwkjvr.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gtkeqnykui.html

Ruby: arr[1, 3]
来源：http://dali.haohaochexian.top/Article/details/gtxtpzqmic.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtgxqhtmbw.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gtxaedekup.html

Py:   a + b;  a.extend(b)
来源：http://dali.meibo888.top/Article/details/gtwqcndpfr.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gtanyersbh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gtooeprmsa.html

TS:   [...a, ...b];
来源：http://dali.chenjidiqi.icu/Article/details/gtzoqxptpq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtgcxpyjio.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtfcremgic.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtcyecwuny.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtfsmdggrm.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gthamazhmg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtkmkjcjne.html

PHP:  sort($arr);
来源：http://dali.xinyue.icu/Article/details/gtibnuvnpd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gthvzxpjyk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gtpawcaopw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gtuwnxeovq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gthefxeyol.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtqtdrvysz.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gtzxdrzghi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtueqhoiwy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gtrxexovnt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtgqpvpzto.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtoeimncph.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gttumnziyh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtyszxsqej.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ydzc1.top/Article/details/gtipgmsoas.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenzaomai.com/Article/details/gtlndgunvn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fzhhl.top/Article/details/gtyvmspygf.html

[D11] 反转数组
来源：http://dali.ydzc1.top/Article/details/gtrzyqpyrj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shangyingyoupin.top/Article/details/gtsekxfnch.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gthtuwqsrh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yonumen.top/Article/details/gtgqijdkcm.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtskkgbkhh.html

Java: Collections.reverse(list);
来源：http://dali.cqqwz.cn/Article/details/gtojincwno.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gteuecbgfm.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtwvmrpdgj.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gtufcfguia.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gtpztmkmxn.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gtpzrhpqwx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gtapjguoor.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtithnvrws.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gttsqpsbpn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gtbygctqjp.html

Go:   slices.Index(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtqijtxmmc.html

Ruby: arr.index(x)
来源：http://dali.zhengqikj.top/Article/details/gtxwfywobm.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gteafzdoef.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtyxobbfwq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.9152youxi.cn/Article/details/gtrgfysxvk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gtyzuaohqn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtnlmtvhwo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gthwpnjvuv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gtdsojpcvz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyzpolym.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gtoxgcvnmq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtvyntqbio.html

[D14] 映射转换（每个元素变形）
来源：http://dali.bjfxy.top/Article/details/gtoujnhqrs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gteliuiako.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtruihmetb.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtpiijhnju.html

TS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gtzatynuwp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gthsccivxf.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtpjxccfps.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtktptwrpk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gtcrnixgjj.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gtfstmuykp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbzwnhhw.html

PHP:  array_unique($arr);
来源：http://dali.wangdashe.top/Article/details/gteyngwwkz.html

JS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gthqhwmtxc.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtwmcqrpaf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gtnszvfoca.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gtpioaobhr.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtqtrmxsop.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gtwgltcahp.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gtdwodqlpv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtnmibfldx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gteaweunpb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtmkszhtuy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtomsfysfy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gtfkhjqncc.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gtbygvyjvk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtnlhavxkb.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gtioitfurj.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gtzmmzjzwn.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gtfcqkvcfg.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtexdpgedg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgfzy.top/Article/details/gtmkwhcpfv.html

TS:   Math.max(...arr);
来源：http://dali.quarkkingdee.top/Article/details/gtlisefuse.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtycrqpsdk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gtmxdonbye.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gtifnxzwva.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gtkqdswdir.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gtearfndyx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hongshengwenyu.top/Article/details/gtikafwyra.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gtbrcvgxut.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.0kj1m.cn/Article/details/gthikkpbbb.html

TS:   nested.flat();
来源：http://dali.cqqwz.cn/Article/details/gtcnneipjz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gtpklxigwq.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gturpfgjlv.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gtchxldvin.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtzairygcl.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gtgecnznfh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gtfblfbqhc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gtysnpihsy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gtufyhicfk.html


<!-- 参考信息 -->