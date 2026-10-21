代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtjfeowoik.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yueranfly.top/Article/details/gtflsowpoq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gtwpijedqi.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtvfenigqj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgoxqgffp.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gtikxaherh.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gteiruhopm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtralfuscz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtokpwdncx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtfnqhaknk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxfuutxsk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shzxlz.cn/Article/details/gtlzyalapt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gtzdpwvlzf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tianlin.xyz/Article/details/gtcqgzkktv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gtoxxnxubn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoowkizpp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gaohongyu789.top/Article/details/gtyfhewagi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtdjujkhza.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ehwqpu.com/Article/details/gtwxsiyymo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.kuanghao11.cn/Article/details/gtnvwssqqd.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gtpussawjv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtnlysuufs.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtofdcchkq.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gtsefiaqrp.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtfsyuglxj.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gtrahmyojt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtwkowsptp.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtzmmcdzgt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pengpengdd.cyou/Article/details/gtbziwyvbq.html

Go:   return a, b
来源：http://dali.daxiang520.top/Article/details/gtttexacvq.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gtacqbiznf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhixingplan.top/Article/details/gteddusdxy.html

[C06] 匿名函数 / lambda
来源：http://dali.yanxiufei.cn/Article/details/gtzbwxutmc.html

Py:   square = lambda x: x * x
来源：http://dali.yuxming.cn/Article/details/gtkatpvwnl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gtefkpambr.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtozvebwhq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gtirhsatvc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtpswfmeyb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fzhhl.top/Article/details/gtawgxsfoh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jyoumei.cn/Article/details/gtwgucansz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtqvdmsqfr.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gteegpdwxi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gtaeodvqiq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gthiejivjj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhongyouzk.top/Article/details/gtrcuqrhbr.html

TS:   arr.map(String)
来源：http://dali.cqqwz.cn/Article/details/gtfdxybocs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dashuyun.cn/Article/details/gtgdpaigxn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtoaevgeji.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj202588.top/Article/details/gtpodmvhjl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtvpkmgpfi.html

[C08] 闭包
来源：http://dali.cashguo.top/Article/details/gtvglxtcby.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zycfv.cn/Article/details/gtcelntclw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jyoumei.cn/Article/details/gtkplduymv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtzlhnwpcr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtwhawgzne.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkiuxqcj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gthtvozovi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgkciacx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtunuoexpo.html

[C09] 递归
来源：http://dali.feifeiyinyue.top/Article/details/gtltjoucoi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtbyofjitx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtsyszetdz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gttmoohwrx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdmdkggm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtzeispjrj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtotcunfvd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gttrdbkiky.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtqcvjlabq.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtajjmvest.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhengqikj.top/Article/details/gtwazugurd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gtwfysomxp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gtmbzokksv.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gtmhmwmvhf.html

Java: 方法内为块级作用域
来源：http://dali.daxiang520.top/Article/details/gtullbnnka.html

Go:   花括号块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtuljngzyq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacrjpwjx.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gtgrvnmenu.html

[C11] 模块导入与导出
来源：http://dali.sysykeji.top/Article/details/gtdftionbe.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gtqcawuvtg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuanzhike.top/Article/details/gtzwbqsrga.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gtppkemprp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtuencyybi.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gtbbcxtake.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gtlybgsgxz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yvedp.cn/Article/details/gtmduhrkfa.html

C#:   using System.Text;
来源：http://dali.jianghu66.top/Article/details/gtvhdjukmp.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gtrdfylqer.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gtuwydykgf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtgxhkceri.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtzirmdwuc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtsoaydcla.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gtoeeggprp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gtdqveioqh.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gtjsrycafi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fzhhl.top/Article/details/gtawjkwhou.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gtbqypjuzi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtixjkrgog.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gthxyfdhkf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ehwqpu.com/Article/details/gthjozjsjy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtovrlnqec.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtyhrxqrxs.html

Go:   func add(a, b int) int
来源：http://dali.hongshengwenyu.top/Article/details/gtefrxduux.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.haohaochexian.top/Article/details/gtndzijtcb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gtndbcnpdx.html

[C14] 泛型函数
来源：http://dali.pengpengdd.cyou/Article/details/gtbmdiafmd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gtcxecxajt.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gtwmmrdrps.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtfkcjpkmm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.mhx1999.top/Article/details/gtbruehbqx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtxtcuflkz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtkucmuvln.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gtrwocpnvi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ybcxt.top/Article/details/gttwdpciig.html

[C15] 解构 / 展开参数
来源：http://dali.shzxlz.cn/Article/details/gtrzrdjurw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.redwolf501.top/Article/details/gtjquxbbhj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gtgdzakvtc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtewgiplgc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.meibo888.top/Article/details/gtjgybsqwd.html

Java: // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtrbcloorh.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gtbzoifknh.html

Ruby: a, b = pair
来源：http://dali.dashuyun.cn/Article/details/gtgiwmacxb.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtvrhfftyc.html

[C16] 函数 / 方法重载
来源：http://dali.gaohongyu789.top/Article/details/gtgwlawjys.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gtcxhcqwwe.html

PHP:  // 无重载
来源：http://dali.yueranfly.top/Article/details/gtnhfkqeea.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.birdmap.top/Article/details/gtlbprqlkv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cashguo.top/Article/details/gtfnmfctrw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhoulong.xyz/Article/details/gtkrreovaa.html

Go:   // 无重载：用不同函数名
来源：http://dali.ivvv.top/Article/details/gtuhzikhnr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aibaodan.cn/Article/details/gtxyiihjpm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gtwjcfjlct.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvdtslqsu.html

D. 数组 / 列表 / 集合
来源：http://dali.wangdashe.top/Article/details/gtqaqntiqf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtadufzfbe.html

[D01] 创建数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkjljuxs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.9152youxi.cn/Article/details/gtqfxqflom.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gtfsefuxtu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gtpkbjypec.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gtvwnigpeg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gttpriqwwt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gtfpwffdys.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hfpthk.cn/Article/details/gtukcoyavs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gtspplvisg.html

[D02] 追加元素到末尾
来源：http://dali.jqgfzy.top/Article/details/gtomxmmfih.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtywmksbrz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gtcyucemig.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtnyqlfpzb.html

TS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtuzvhikdl.html

Java: list.add(4);
来源：http://dali.hysaishi.cn/Article/details/gtvvyxhout.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gtbtonuluz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ivvv.top/Article/details/gtvrienbxj.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtbgvezald.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gtqgflfvah.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtwkzlfazd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gtnaqiwmiy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gtfvuziunj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtaksvqeyu.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtnsgnnrdo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gtiscqkklw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtvbpnxvnx.html

C#:   list.Insert(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtjtkmekno.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gttroiqeim.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zdqjudy.top/Article/details/gthuoclzhx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gtzkllmqzm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gtbvfmhfcv.html

TS:   arr.splice(0, 1);
来源：http://dali.tian-w.cn/Article/details/gtczvtlzjk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gtdmnvpond.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtiokpgpxx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258.top/Article/details/gtibvvtkrq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhoulong.xyz/Article/details/gtvttbdqlh.html

[D05] 访问与修改元素
来源：http://dali.yangfankeji.com/Article/details/gtthvjlujb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gthdvykjhi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtpbmmkcyu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtyjembmuo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigufen.top/Article/details/gtimezrige.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gttojwhaiq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gttpcpvkjo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtzzhxkric.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtnynasjry.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtejtjisqp.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtkntqxbxp.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtqdyfeifc.html

JS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtpjdrdfws.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtvkvzoepu.html

Java: list.size();
来源：http://dali.guannengcc.top/Article/details/gtrjploqbf.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtmbzgxmqg.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gtopvvtkei.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gtiezclivy.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtkpubkafn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gtyvpofppq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gthdzjsooy.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gthvzroytw.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtdvgmijku.html

Java: list.subList(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtvgtgmvcb.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gtgickcnyp.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gtbyrerjib.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gtjardknme.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtbiqyigmo.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtyagrwfig.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gtrxyfwgyd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gtsotzymyj.html

TS:   [...a, ...b];
来源：http://dali.zhengqikj.top/Article/details/gtlqmvbdoy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dashuyun.cn/Article/details/gteamrtolz.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjhsudgk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jiagoushi.top/Article/details/gtarrmtsqo.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gtutfxstok.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gtilosdmgr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtdyqyakrk.html

PHP:  sort($arr);
来源：http://dali.fengsongda.top/Article/details/gtgqeyjonb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuxming.cn/Article/details/gtumonfygk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gtoyfxnbbm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtejdsbfaj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gttzgnhsoe.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtszbznkhz.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gtbqiigvdd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gtnowvnvqp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gttfaoiwnt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gtxxmxyhbh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gtttrrvorr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtqzwkqvki.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtjltpczbx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtocyvqckc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gtgyjhxohc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yanxiufei.cn/Article/details/gtomrlfacy.html

[D11] 反转数组
来源：http://dali.havefunace.top/Article/details/gtkqnkmrjt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gtkcdxnolg.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gttxixbywr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzaxyzthn.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtkrmlerbg.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gtdhqtvcdh.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gtrnxbgrvo.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gtsyzyqvwm.html

C#:   list.Reverse();
来源：http://dali.sweek.top/Article/details/gtgfunioar.html

[D12] 查找元素下标
来源：http://dali.316326.xyz/Article/details/gtbixpuqux.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gtntiqcqlb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sweek.top/Article/details/gtpjschnda.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtzbzuwvln.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtphqjfvbo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gtudclonby.html

Go:   slices.Index(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtfemeckry.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjcfhfiv.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gtpesoedik.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gtjbrkqahh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gtzhoyzlgf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtygcywolk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtzwlicyok.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtpdjjddvr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtmkjxiblo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gtydhfgelc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hysaishi.cn/Article/details/gtjlfssfrd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtkgceuxoq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gtvirrgsxf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtagiemmdg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hfpthk.cn/Article/details/gtcepewozc.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtdahczwjl.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtiwaurxfk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtfiuethxk.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gthaioedjf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpdsrzby.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gthucguail.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gtqxhzleth.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtlbpcehdp.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gtnveaosay.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtvlogpmik.html

TS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtebsxmxdp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ybcxt.top/Article/details/gtjwezjecs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gtafdnmgxq.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gtztzwevyv.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtalfuljqj.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtbfhurnzt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtsttedrbv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jyoumei.cn/Article/details/gthzddpdwj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtlunwvpkg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gttzbequvh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gtccbkvugo.html

Go:   // 手写循环累加
来源：http://dali.cucudq.cn/Article/details/gtypfblnkx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtgaqqokxc.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gtphclswyx.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtrhaejwio.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtppzsnrts.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gtqkigijiv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtgzltijii.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqzkxnrj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xinyue.icu/Article/details/gtlziizcns.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtrusoropz.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gtzqpfzjhk.html

C#:   list.Max();  list.Min()
来源：http://dali.ehwqpu.com/Article/details/gtohgdopxg.html

[D18] 扁平化嵌套数组
来源：http://dali.xinyue.icu/Article/details/gtoiqpskuu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gtsehdpbzi.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gtqrzydwsv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmalwzdjw.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinfwbezs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guowangkeji.top/Article/details/gtvwpdffbe.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gtxrnezopr.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gtmgglgfmy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtpnfukiyd.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gtzpoklrhf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtpcxrhxum.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gtzfdbhpqy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gtvpiljzud.html


<!-- 参考信息 -->