代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtltbkrppc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.feifeiyinyue.top/Article/details/gtnarfbtmv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gtqutcsvih.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtjsvmprjb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gtivjbebig.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gtrpjliwxq.html

Py:   def total(*args): return sum(args)
来源：http://dali.aizwys.cn/Article/details/gtepneldkr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhambyad.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtbednelgw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gtpzvzirws.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gteeevyvcj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yonumen.top/Article/details/gtxutomhjx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbadxrtj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigufen.top/Article/details/gtirpzsenw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cucudq.cn/Article/details/gtaflhiglu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ivvv.top/Article/details/gtpsysmyvl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gtfrgivszg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtdbxgagrn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiebbgyu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnqzz.top/Article/details/gtinxrsian.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtczxxuwlh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtstbasqjj.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwxvoths.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gtnjbzefyk.html

Py:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtbqjbfzdb.html

PHP:  return [$a, $b];
来源：http://dali.hysaishi.cn/Article/details/gthtfiikia.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.havefunace.top/Article/details/gtyzhdelgz.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gthrtqhguf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.vqdsnc.cn/Article/details/gtellbtvft.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gthtpprijm.html

Ruby: return a, b
来源：http://dali.tanke756.top/Article/details/gtjoqnyxkh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gthihlgeyx.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtuhpvfiou.html

Py:   square = lambda x: x * x
来源：http://dali.cheryme.top/Article/details/gtyqbigsap.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tanke756.top/Article/details/gtbucjoqia.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtjvisanqq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtkmeavbqx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtjyxasudn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgufenzy.top/Article/details/gtetuyqjkr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gtotdnrttl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtltubvpsh.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gtmomgtczq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gtwxweudvz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.iojbl.cn/Article/details/gtnqhpwzwb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzylhqkju.html

TS:   arr.map(String)
来源：http://dali.mhx1999.top/Article/details/gtypkluwta.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclggvgcs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gtnbwkjmoy.html

Ruby: arr.map(&:upcase)
来源：http://dali.guowangkeji.top/Article/details/gtnhndgsnu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ybcxt.top/Article/details/gthjtyxfiu.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtfbqprmdl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeiwvnxi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jyoumei.cn/Article/details/gtdkvbrqkn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtgflpwkyg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtwujxlfzd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gtsbxgbcpc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shzxlz.cn/Article/details/gtdeeixbtz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gttsmikogc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtmqwcyrdi.html

[C09] 递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpxjaxom.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gtcjrpqwbh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtiqlxphtr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtecifwarv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtnlowsjow.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtyqazqbsw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aibaodan.cn/Article/details/gtwvpngewe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtsyuvhpgu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtkaeoikdb.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gteheignnk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokfzbfvm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gtifvxldht.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gtdptwckgu.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gtnvkpqevf.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtxsubssbx.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gtctbesoau.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gtfwfcgrgk.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtfpbjggpc.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gtgrmceuko.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gtymwiinaj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gtfhqltmfa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gtdgvtwscb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtlegxznpv.html

Java: import java.util.List;
来源：http://dali.hammf.cn/Article/details/gtpvuwwfoh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gthwhdcrtb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gtzbasvsrk.html

C#:   using System.Text;
来源：http://dali.gogol.net.cn/Article/details/gtbfzrworf.html

[C12] 立即执行函数 IIFE
来源：http://dali.gaohongyu789.top/Article/details/gtuggpyfxz.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gtntwtrslc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtstudcrda.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtwweerqmu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtfoajsxfg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gthqhokyss.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cucudq.cn/Article/details/gtmhenjwdw.html

Ruby: -> { puts "run" }.call
来源：http://dali.shzxlz.cn/Article/details/gtgflfjgwy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtfnwrawze.html

[C13] 类型声明 / 类型注解
来源：http://dali.zdqjudy.top/Article/details/gtckkvgvrd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhwbwonj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpktewymt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cqqwz.cn/Article/details/gtyzykecap.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtcwdrzaud.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtgzxwccgm.html

Go:   func add(a, b int) int
来源：http://dali.jqgufenzy.top/Article/details/gtwgipbtdm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.birdmap.top/Article/details/gtwaklmumo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtkeqdormf.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gtrznpvkvy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gtusijpdvu.html

PHP:  // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtkfrldfam.html

JS:   // 无泛型
来源：http://dali.zycfv.cn/Article/details/gtrmcmbjon.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtcbfrqvbp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fengsongda.top/Article/details/gtvafjzvmv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gtddbptrzr.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtyekevaat.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yvedp.cn/Article/details/gtpgbjirqv.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gtwemqlxlz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gttwzdpapq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.havefunace.top/Article/details/gtgtaeezyi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtozyaffjk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gtgzjzaxpa.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtglxduybc.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gthqopsbyk.html

Ruby: a, b = pair
来源：http://dali.9152youxi.cn/Article/details/gtnwwrrsvs.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gtielkmppv.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gteyzuriap.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtfvooifmw.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gtzmogzwru.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtlnhtxdlg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gtjbemvknj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyfankvru.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gttiimqtnp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gtmildutqj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gtklxwmfiw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttcbmrugh.html

D. 数组 / 列表 / 集合
来源：http://dali.feifeiyinyue.top/Article/details/gtqnywxczv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdzrazpbr.html

[D01] 创建数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gtkxijnghq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gtmkwytypn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.meibo888.top/Article/details/gtcvnjkndx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guannengcc.top/Article/details/gtqyjmbxre.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.316326.xyz/Article/details/gtjdjvraic.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.snrcjt.cn/Article/details/gtahevqntm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffltgivr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jianghu66.top/Article/details/gteplylvil.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gtrkuoytzo.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gtvycgqoeu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtfoeykogz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gtmhkrwxpe.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gttpxwhdvg.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtvpfccyoi.html

Java: list.add(4);
来源：http://dali.ydzc1.top/Article/details/gtwspcxyqj.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gtjfjiocek.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttymqntoi.html

C#:   list.Add(4);
来源：http://dali.pycfn.com/Article/details/gtthtbzqob.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gtixexraip.html

Py:   arr.insert(0, 0)
来源：http://dali.316326.xyz/Article/details/gtrhktkphy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtxcqycvnt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gtneivgzin.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtmcomnxhp.html

Java: list.add(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtqtdluoeb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gtjglcsblo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuetiantiany.cn/Article/details/gtvjcqgwnz.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtafwsxosu.html

[D04] 删除元素
来源：http://dali.guowangkeji.top/Article/details/gttqeuoxpn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gttnmpwire.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gtddynndpj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gtsomizpyg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gtkdahgvbd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtulleuudo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gtpzqxomso.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtfvkcbmdo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgfzy.top/Article/details/gtuulexwhu.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvhsrpmd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtijwxeyyd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtsbsojsdy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtykmugsty.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gtbdkvjwya.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gtazssgstj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtnopgngmx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtlzsvqzwp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtphbxiktd.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gtjhyxtbcx.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtqovjqomq.html

PHP:  count($arr);
来源：http://dali.dianchejie.cn/Article/details/gtjzxlxxaa.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtsgkakwya.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtvhpkocxh.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gtarcqrezs.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtxtdtsrdn.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtmrdjvfui.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtbfygefta.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gtefixyrnq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sufxvd.cn/Article/details/gttnjbofmn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gtserwnggb.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtqbromlnc.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtwknichpy.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtyfnycjfn.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gtduypplqc.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtgsjyjytj.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtdsjwqjnj.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gtpgfngynv.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gtldrgiuwb.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gtxwbawxhd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gtzjxsojtd.html

TS:   [...a, ...b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsunxbra.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.kuanghao11.cn/Article/details/gttfryvpuz.html

Go:   append(a, b...)
来源：http://dali.yueranfly.top/Article/details/gtvdxugllv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtlbvdlusl.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gtuyudrgug.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gtewaypocw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtrarcirvd.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtuqhyxrnr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gtxjxovntb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yongpay.top/Article/details/gtbobwmwef.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gtcojxeurk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtovxysjho.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gttwgralqz.html

C#:   list.Sort();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkbuoyju.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cqqwz.cn/Article/details/gtageetiqz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gtmxndfiui.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtwbrqexzv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtyonlahaw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gtmpsrcpdb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gtjkaypnfy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gtbawnbqcm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gtxvjcalqj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gtdvwkssxf.html

[D11] 反转数组
来源：http://dali.zhengqikj.top/Article/details/gthfecmkhk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gtjptvkbod.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtlcunwguw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gtirkrsavc.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gtsggjejzu.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gtacccocvb.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gtkqupysmx.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtzuxbnaft.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtxzrwetbj.html

[D12] 查找元素下标
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfwedbci.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtyfubsxcx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxinkj.top/Article/details/gthcksryuu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gthlohrypi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtighocarf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gtjcryixib.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtyuyiywna.html

Ruby: arr.index(x)
来源：http://dali.pycfn.com/Article/details/gtogkhhnkm.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gtselbscjo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gtognacltl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gtudoahrer.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gtpxekyiwa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtbqtodgri.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtcccyybjy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gtxugflfav.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtyrvlscke.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gtoaigdfft.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtsnshcacl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yangfankeji.com/Article/details/gtssaotuxe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gtksysgfky.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvnpsanm.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gteymeehok.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtzcqiipev.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gtohfazcxg.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtvylyzfeu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtapwiiugt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gtbidqtvox.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gtedzpvtdc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtrvveslet.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtfdjalfjd.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtgrhrveyl.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtknawwogi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hongshengwenyu.top/Article/details/gtwoyidyiv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gtczlvdzeh.html

Ruby: arr.uniq
来源：http://dali.dianchejie.cn/Article/details/gtoiuhwfll.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtgrswtqju.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtfcqamzph.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtuhleqjvf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtraiobyqs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtbkgwydra.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtqvyrtcju.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gtzcpfacwr.html

Go:   // 手写循环累加
来源：http://dali.ivvv.top/Article/details/gtxcsiecpw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gtyabaycso.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gtzwethjgt.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gtjkhxwffb.html

Py:   max(arr);  min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtmrdmspvd.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gttuiyeyoh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gtepltgrze.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gttggfycsx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtbklvbjsf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hammf.cn/Article/details/gtrbzyeqqk.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtusgunsnr.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtpqmzfzlh.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gttbanuvoq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gttrgssfyu.html

PHP:  array_merge(...$nested);
来源：http://dali.jiagoushi.top/Article/details/gtdrlltzvf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fzhhl.top/Article/details/gtimxgjoql.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gtxatqnwuy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjildhlkj.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gtismtfxfp.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gtzeecbdjv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gtjzojlybx.html

[D19] 按字段分组
来源：http://dali.yanxiufei.cn/Article/details/gtyumyaqdv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jyoumei.cn/Article/details/gtkdvkkzcc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gtatvgwlsl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gtjmielmnm.html


<!-- 参考信息 -->