代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gthclcjfap.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tianlin.xyz/Article/details/gtnphmhdit.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ybcxt.top/Article/details/gttebbslpp.html

Ruby: def greet(name = "World") = name
来源：http://dali.hywenlv.cn/Article/details/gtekqbdmrj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gaohongyu789.top/Article/details/gttkeuteyg.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gtyhchoufj.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gtsifjfahd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.vqdsnc.cn/Article/details/gtmgpggspd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtqwhqqsvv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtvtjtaudi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqyosfha.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gtqwomdhch.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnqzz.top/Article/details/gtitmuecfi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.andypj.xyz/Article/details/gtqrbkiffg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gtwzumitpz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbarathf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtzbppjfmw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtscupzdoe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tanke756.top/Article/details/gtusuifthf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daria6918.cn/Article/details/gtsilqqjqt.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkckffyx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtayztwuwt.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtrqvdydfp.html

[C05] 返回多个值
来源：http://dali.quarkkingdee.top/Article/details/gtrlcxuozg.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gtdbyzylib.html

PHP:  return [$a, $b];
来源：http://dali.tianlin.xyz/Article/details/gtrzmixqif.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nwbrower.top/Article/details/gttkfpblnf.html

TS:   return { a, b };
来源：http://dali.cheryme.top/Article/details/gtrcsbbsyi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtuvtlquhb.html

Go:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtvvmzurdu.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtejqfxkwy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sweek.top/Article/details/gtrphcbiuo.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gtvnspyrls.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhswlsld.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gtflbmplzy.html

JS:   const square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gttszdbjym.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.bjfxy.top/Article/details/gtuvxxpevg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gthpabrwqi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtisoqbbga.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ehwqpu.com/Article/details/gtifdwonif.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtthxtnsht.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gtpznamyup.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtafwzpmyk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtmtgghwhd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteezfjxmf.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gtudvokmno.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gttpwemljc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigfzy.top/Article/details/gtxsdxuzpq.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gtfroibizq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.kuanghao11.cn/Article/details/gtsqapsgmy.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gtikowxsgf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtunqvtusn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhengqikj.top/Article/details/gtnqoicizh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtusqxhhbz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrbjnyatg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.316326.xyz/Article/details/gtxyoghcww.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gtpzxkbxmd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gthqxzobyz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtigxicweu.html

[C09] 递归
来源：http://dali.chenlongwang.top/Article/details/gtcmzijjkf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasnybugy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtqycsaich.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gtbkqexjse.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gtrzlsqfdm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtymghffky.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gtwqsmrzfo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gtzirwrgjp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gtpnwyegcp.html

[C10] 变量作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gthehubnle.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgfzy.top/Article/details/gtfnclocuh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pycfn.com/Article/details/gtcqzdukcw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gtivhqhkvj.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtxhrnqkqm.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gtncucuvwb.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtfpkgezvk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gotoacloud.top/Article/details/gtkqorjapq.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtkocgwrrb.html

[C11] 模块导入与导出
来源：http://dali.aibaodan.cn/Article/details/gtcmekuixc.html

Py:   from module import func
来源：http://dali.yuanzhike.top/Article/details/gtukyntsqf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yvedp.cn/Article/details/gtffwlekrl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gtuqoxheuh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhengqikj.top/Article/details/gtsqsdjnbw.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gtkrzefdoe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fengsongda.top/Article/details/gtxihxkrwy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gtbqckgxpv.html

C#:   using System.Text;
来源：http://dali.yj20258.top/Article/details/gtesgdtgct.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gtvdfxcrsm.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gtimzmkwia.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tanke756.top/Article/details/gtutgcmyes.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtrieiarvk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtpkafxbwb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhixingplan.top/Article/details/gtfaibnkmy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtmfjcjnut.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtocrffxkh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigufen.top/Article/details/gtglumspbl.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gtgvztmtyk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.snrcjt.cn/Article/details/gtdoyuqsps.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtpqqgwzpr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtopjikuwj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtbruhkkdk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtzfsjwsfr.html

Go:   func add(a, b int) int
来源：http://dali.hfpthk.cn/Article/details/gtqarafvxc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gtvzskeilb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gtdekxxvqf.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtrloqivpc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtpolevqov.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtymyogkgn.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gtmsscixmg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ppjwa.cn/Article/details/gtgrewnmpu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.andypj.xyz/Article/details/gtjechvvue.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gtgohjhqse.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gtgnokoicw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gtokwvkvyw.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gthfqatmuo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gtgpeifwem.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtpcjkqxkd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gteldgzucw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gtwlvcahhr.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gtobdevqqz.html

Go:   // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtqockfpwv.html

Ruby: a, b = pair
来源：http://dali.shuidangran.top/Article/details/gtbrkdiesl.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gtisioybrb.html

[C16] 函数 / 方法重载
来源：http://dali.tanke756.top/Article/details/gtmsuudvpe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gtownkyjni.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gtllzmbpqc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtjapxafwi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gtcizrusea.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtbkkmmydn.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gtsgmfefit.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gogol.net.cn/Article/details/gtvmfjzuor.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtpzrxqgyw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgbyiorlf.html

D. 数组 / 列表 / 集合
来源：http://dali.birdmap.top/Article/details/gttdgpgaly.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmsaaowxm.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtcylljnoj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gtamgrspzg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtpjlhgakj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtccsdkdcu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgufenzy.top/Article/details/gtjzzevzrx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtvdurqexq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gtvenivsly.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gtzuwffydv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gtiunfalkv.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gtmjsufbzu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gtaonydaox.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gtqjfzuroa.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtdzsibzus.html

TS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gtbknnaxbb.html

Java: list.add(4);
来源：http://dali.yuanzhike.top/Article/details/gtpudsqhnz.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gteqffcutx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sxryk.cn/Article/details/gtenwkbjil.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtemhvehbm.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gtdbvcmxdy.html

Py:   arr.insert(0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtsixsudav.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gtcrcvbwgh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jianghu66.top/Article/details/gtdzzjoywb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtiqnmdrzf.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtmcjqtklw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtvxzrjuxl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtygidoyxx.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtcwzzujzv.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gtrtyidbch.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.c1oappe.top/Article/details/gtwuwbxjie.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gthxorfobo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gttlfyqnna.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtencsxdao.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gtpaelnkev.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenzaomai.com/Article/details/gtzfokzfpo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj202588.top/Article/details/gtnccphcwu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtygkuiwmv.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtlbcaymar.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtziurdqkt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtwqruejvp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtqtctvrhq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtwgxcmqhh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gtexddycqi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtyhdlwhoz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtqtypkdsf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtfbgqesoe.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtvigajuye.html

Py:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtopjqkomw.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtnzlhouee.html

JS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gthissujuv.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtxojxccsj.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gtshqhdtjt.html

Go:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gtxnuycwdo.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtjcoldjvo.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtbfarecea.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtldqehdaf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gtaubtxvck.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gtjjftksej.html

JS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtubvhqooh.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtfosugdrw.html

Java: list.subList(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtdjhqvwzl.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gtarfscomj.html

Ruby: arr[1, 3]
来源：http://dali.aizwys.cn/Article/details/gthchjyqjo.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtiwjuegah.html

[D08] 合并两个数组
来源：http://dali.yangfankeji.com/Article/details/gtmtqeihtq.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtiiibexnz.html

PHP:  array_merge($a, $b);
来源：http://dali.havefunace.top/Article/details/gthsuzyjos.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gtlyllloqc.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gtjgtrgzst.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtdnzdymyc.html

Go:   append(a, b...)
来源：http://dali.gogol.net.cn/Article/details/gtdxpuoemo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtfbndrbut.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gthjumpjdh.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtrsszskgx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtsdherjmg.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gttfcqrayz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gtwugeibqc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gtqklsooqs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yongpay.top/Article/details/gtiwflxqvh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtgcqqbdlx.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtamkmjutm.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtlwggtben.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gtwkbymsty.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhoulong.xyz/Article/details/gtzezmnqes.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtfmqyatvg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtueblwozt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtaljqexyt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtffloiuyj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sweek.top/Article/details/gtbobapjwj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.9152youxi.cn/Article/details/gtanjsrgnn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tian-w.cn/Article/details/gtoqmvszfq.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gtqlgoafbn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gtojufehmq.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gtfovrfuhj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gtdtpqkgrr.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gtfgtwbhdl.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtczfasexa.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gtqbvdryek.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gtqsrsghcx.html

C#:   list.Reverse();
来源：http://dali.ehwqpu.com/Article/details/gtvafceahy.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gthrypwnwf.html

Py:   arr.index(x);  x in arr
来源：http://dali.nwbrower.top/Article/details/gttquahzje.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtcqnrixqt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtrydvyrxz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gteojuvkks.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtbkkzcpgx.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtqlffhwig.html

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gtesrgikin.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gtsifyrktz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinghuilouyu.cn/Article/details/gturcicboa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shuidangran.top/Article/details/gtjjhzehmm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guannengcc.top/Article/details/gtjwgojbrl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtzaejgtrm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtbbsbjphf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtqbisyskz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gtfcscnicn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hysaishi.cn/Article/details/gtdvpmzsti.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sysykeji.top/Article/details/gtnaepivzb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gttyyfliov.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtderqjznf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtpkrqzrrm.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtmzsqhjwu.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtwxhoirhf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gtzjbbhdco.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtkklhmyot.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtcsmxptha.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gtlmgaymst.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtxldiblno.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssdboakr.html

PHP:  array_unique($arr);
来源：http://dali.meibo888.top/Article/details/gtaurhmies.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtlyocvlvv.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtblejgrlm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gtevjrgsga.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gtymjccaiu.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gtbtkmageh.html

C#:   list.Distinct().ToList()
来源：http://dali.daria6918.cn/Article/details/gtputpqvsz.html

[D16] 求和与平均值
来源：http://dali.gotoacloud.top/Article/details/gtuxoqfmkj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlcztxcd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtlevvnzrv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gthoxvtell.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtoypwxfrv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenjidiqi.icu/Article/details/gtrepqfont.html

Go:   // 手写循环累加
来源：http://dali.nwbrower.top/Article/details/gtigoutyiu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gtxfrgemft.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtafhclbjb.html

[D17] 最大值与最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtosuawxjk.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcirqkkbi.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gthkkdwqyn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gtiujlmtmj.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gthkjwetzw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jiagoushi.top/Article/details/gtiyzhstqr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gthoirkqqz.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gtsilgfobk.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzzyufsv.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gteyyzyain.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gtflsmvtpu.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gtyusibwgu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jlsjyb.cn/Article/details/gtijksdtmv.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gthroyermh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtkymzuomj.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtovuiaein.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gtffogyrax.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gtblzquyxy.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtykglcidb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gtwxuvcnhe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gtjxbovljn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gtidvbibyy.html


<!-- 参考信息 -->