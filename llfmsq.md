代发 wailian999

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2ctwtaift.html

PHP:  return [$a, $b];
来源：http://dali.smart0.xyz/Article/details/gt2bebdobwm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.havefunace.top/Article/details/gt2yhorofqv.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gt2armmufvz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnqzz.top/Article/details/gt2bdolsizl.html

Go:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gt2vcutwgrf.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izkkzkln.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggkxwecy.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzicqajt.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gt2lamosndq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cheryme.top/Article/details/gt2zrkmdoqv.html

JS:   const square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gt2cpxgrjcs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gt2lucownzd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2kridflvm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gt2pmqohqcr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigfzy.top/Article/details/gt2yvjknvmm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gt2ablvbkuh.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gt2sfdmwwuq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhoulong.xyz/Article/details/gt2cebscepk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2mkbpmqeg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gt2gmyhcaqr.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gt2clxhayum.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2lrchyruk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gt2wqupovih.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuanzx.com/Article/details/gt2jalprlaj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gt2jcgnrptp.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gt2lxtdnvxm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gogol.net.cn/Article/details/gt2wsvbgadz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gt2favlrwda.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gt2ivcopdam.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2oialznrr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gt2uhrzkwwi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gt2fwtnynao.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gt2lpcgaevh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2nitkozvo.html

[C09] 递归
来源：http://dali.tanke756.top/Article/details/gt2jyuembld.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gt2anpxrivu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnzygwyy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gt2txougidf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gt2gddtvccb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gt2zeldmpfi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gt2jojvrgsf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gt2sfoigene.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aizwys.cn/Article/details/gt2wzfauuio.html

[C10] 变量作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2karzawig.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gt2bewiekzs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cdnleiting.top/Article/details/gt2fwqkzvwc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2eemgojoe.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2pwbrxlct.html

Java: 方法内为块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2imbactue.html

Go:   花括号块级作用域
来源：http://dali.chenlongwang.top/Article/details/gt2czfdhfdm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gt2ibvkwngu.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2kpklhtbo.html

[C11] 模块导入与导出
来源：http://dali.hammf.cn/Article/details/gt2bykkmnlh.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcetpsrp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thwcaoqk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gt2nfnlexur.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gogol.net.cn/Article/details/gt2wonyyrzz.html

Java: import java.util.List;
来源：http://dali.yj20258.top/Article/details/gt2tzvpibco.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gt2djydspha.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gt2bzzqfpoe.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gt2twtzfyxd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egpiavfv.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gt2stmuwzpz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cheryme.top/Article/details/gt2ymislgma.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gt2ubwzsubj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gt2mgbpjonw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gt2ttdpwhpg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2beorpflt.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gt2hpikkrsy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sxryk.cn/Article/details/gt2olacdexl.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gt2wmwuycfx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gt2grakzlmf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2nakhxfyi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mimccgsp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2ytyyxfnr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2ylgrjjws.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gt2wpkhyyti.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258.top/Article/details/gt2rrihqycq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdhclfii.html

[C14] 泛型函数
来源：http://dali.birdmap.top/Article/details/gt2ypbjsmgr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gt2lflawqdu.html

PHP:  // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2mxhypnyb.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2gyplzsjc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.haohaochexian.top/Article/details/gt2akoygykj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxuanxn.top/Article/details/gt2tghervnl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzbopzql.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2wyvpmmfr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gt2hhuktxzq.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gt2aklgyqbp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuanzx.com/Article/details/gt2butgqvnl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuxming.cn/Article/details/gt2pmjwmsco.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gt2fcvsqban.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gt2pkpbvvki.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2wlfklhur.html

Go:   // 无解构
来源：http://dali.tanke756.top/Article/details/gt2bycqfpyw.html

Ruby: a, b = pair
来源：http://dali.tian-w.cn/Article/details/gt2eqjvqlwu.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gt2jaxjtprx.html

[C16] 函数 / 方法重载
来源：http://dali.nwbrower.top/Article/details/gt2juptmaqy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xylfe.cn/Article/details/gt2lvocbeoi.html

PHP:  // 无重载
来源：http://dali.hnxiangtu.top/Article/details/gt2rbhskjye.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxuanxn.top/Article/details/gt2ifgwweoc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgufenzy.top/Article/details/gt2qgirdotm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gt2vwjztdeq.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gt2vamilafr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.haohaochexian.top/Article/details/gt2tqpwvtpi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zdqjudy.top/Article/details/gt2ljvhbdiv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2hnogepoh.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gt2ceutjtoi.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2qofzvxtu.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gt2apromxqt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenzaomai.com/Article/details/gt2onabluxa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.birdmap.top/Article/details/gt2tcdhurus.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2wsyyeooj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlqdplcw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gt2tgkxaoqi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gt2ehdabaho.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gt2skagqrli.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ucdmldwc.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gt2lwdzctfw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gt2qdxazpck.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gt2rlfjnmmy.html

JS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2vkfwrjwn.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gt2cmgsivbd.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2flosntht.html

Go:   arr = append(arr, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2wdbrilse.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xziqi.cn/Article/details/gt2syytxiuz.html

C#:   list.Add(4);
来源：http://dali.nwbrower.top/Article/details/gt2embvaqah.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gt2hkmqnexi.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2hqdzcqbl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gt2zlvzurda.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gt2nqdyhyip.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2wvyvwdns.html

Java: list.add(0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2xwareudq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gt2aoididnw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gt2jqryurbf.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2myppglau.html

[D04] 删除元素
来源：http://dali.9152youxi.cn/Article/details/gt2hkaclggg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ivvv.top/Article/details/gt2xgtlvjun.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2cgvhfxoc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jufyutpz.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gt2fwjhnnpm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2myapqgec.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gt2ffjvowbr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gt2uhmngcnl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gt2sxgjvzhv.html

[D05] 访问与修改元素
来源：http://dali.jqgfzy.top/Article/details/gt2opvuevcu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2bendqvdr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2jnxsakcf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2qkdjflug.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gt2zjjtowbc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gt2pguwfhdq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2akkrzctw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2fbpanvuw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2dkqsuhhg.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2pougoigq.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2mivbhbgr.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2ztgvqrzm.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gt2phkwipbi.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gt2rrfuljcp.html

Java: list.size();
来源：http://dali.jianghu66.top/Article/details/gt2udpjnoyb.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2wvcwmvhm.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gt2oxlvwuzy.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gt2tgemnkgn.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gt2tftzynxc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gt2dppnewoz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2dtdttttn.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2uzhrswpb.html

TS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2gpefowbq.html

Java: list.subList(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2uuplsojs.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gt2ersmahca.html

Ruby: arr[1, 3]
来源：http://dali.jqgfzy.top/Article/details/gt2nmfhgjlj.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2xuqwgyjy.html

[D08] 合并两个数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjmntuyd.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gt2uqchzghh.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gt2kelpjbtt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.haohaochexian.top/Article/details/gt2mbdhsqdx.html

TS:   [...a, ...b];
来源：http://dali.tian-w.cn/Article/details/gt2oyhxiext.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gt2ptzhswqh.html

Go:   append(a, b...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2viuwzwmh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gt2fklhpfhm.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlqvxndu.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdehnspj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gt2pufacujc.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2wrvouwmc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gogol.net.cn/Article/details/gt2pjsijbev.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.c1oappe.top/Article/details/gt2sinledkj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gt2xrmvsepy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwenjble.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2ouezjwpf.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gt2armtrjqp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gt2mricppta.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gt2xormoppx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gt2tbwazbna.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gt2fvfxhnwc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gt2iwkfigok.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pycfn.com/Article/details/gt2fovkkodd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgufenzy.top/Article/details/gt2tfnieglx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gt2dxxxfssl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yangfankeji.com/Article/details/gt2lrrgaump.html

[D11] 反转数组
来源：http://dali.fzhhl.top/Article/details/gt2hjliyaxq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gt2hubijdhe.html

PHP:  array_reverse($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2oajfhzer.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gt2kwfppizf.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gt2yrwjaqud.html

Java: Collections.reverse(list);
来源：http://dali.yuanzhike.top/Article/details/gt2fvronutk.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gt2tjwgimen.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2bfjgeved.html

C#:   list.Reverse();
来源：http://dali.ivvv.top/Article/details/gt2vtgshfzx.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gt2lszdhcqc.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gt2nkejqdbe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gzhubu.top/Article/details/gt2itrogzoo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pslnjpok.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2iglxltzz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gt2bdjoegpp.html

Go:   slices.Index(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2oualuotp.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uopdamci.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gt2xonsfkob.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gt2hmmfjzmn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2zxacbyfo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2mzcrwqry.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2ioixyjmi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gt2xoenajtc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2wselouwk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gt2vpwczsea.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gt2fsrslfmh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2kxnblidc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhoulong.xyz/Article/details/gt2nxglknfv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gt2kbjgtotr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2jsgvdwos.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2ucnnikxv.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uakegkis.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gt2rsfofbwa.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbigprlg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2mvwgwxpw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2jyrelokt.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gt2btpmpzcw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gt2sryenuhx.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2ogemtbki.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2hbpzsvvx.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmmnkhbe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gt2soqnxryu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hongshengwenyu.top/Article/details/gt2rceavxbo.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gt2zcksqrca.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2morvzupq.html

[D16] 求和与平均值
来源：http://dali.nanxuanxn.top/Article/details/gt2yywtiigh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2sualcgdh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2gtyflfsf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2bxhuhoxq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2mpwdeqrs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.9152youxi.cn/Article/details/gt2wzwpcqab.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sahfuthc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajbabzbj.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gt2tcxwvpqe.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gt2idthxlce.html

Py:   max(arr);  min(arr)
来源：http://dali.xziqi.cn/Article/details/gt2cynxxkno.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2aobdlwda.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gotoacloud.top/Article/details/gt2vkyfssqn.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gt2gdpsmnbm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gt2mfrtbmqi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxfmvbhi.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecbdssvv.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2toogryhj.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gt2pcmpdsag.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gt2zwscbzqt.html

PHP:  array_merge(...$nested);
来源：http://dali.redwolf501.top/Article/details/gt2lxplcjfb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gt2qlvqttup.html

TS:   nested.flat();
来源：http://dali.yj20258.top/Article/details/gt2ymcqxknw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2whulpznz.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gt2sklgsbaa.html

Ruby: nested.flatten
来源：http://dali.fengsongda.top/Article/details/gt2mxdscydh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2ubzetmwo.html

[D19] 按字段分组
来源：http://dali.gogol.net.cn/Article/details/gt2jmrdjspj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gt2xygukjhb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gt2vqehexeg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2waptlkab.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gt2xnpdenqc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yanxiufei.cn/Article/details/gt2oieoyiww.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gt2ldyftpdu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gt2qftrxjwx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xylfe.cn/Article/details/gt2bcbctsmt.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gt2eaawrxkf.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2iqftrxqe.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gt2qadaauli.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gt2ldrfxbzi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gt2croonlgf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gt2yjlglkbg.html

Go:   // 手写 map[T]int
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrlznogs.html

Ruby: arr.tally
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2plugukvh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gt2skemjide.html

[D21] 判断是否包含某元素
来源：http://dali.daria6918.cn/Article/details/gt2vmafkuya.html

Py:   x in arr
来源：http://dali.hywenlv.cn/Article/details/gt2cskaardv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gt2jznubawk.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgmpgcls.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2dxsxiztz.html

Java: list.contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2ysjkityw.html

Go:   slices.Contains(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2kledokqz.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtyggpkk.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gt2hnfnjjla.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gt2pczwyrzd.html


<!-- 参考信息 -->