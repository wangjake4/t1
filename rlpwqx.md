代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gtehjzfmri.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtajadpkfq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tanke756.top/Article/details/gtvcdqeogo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtnaqjhvrl.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsttiuikr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtmzvmedej.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtskxoceyz.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gtuutkxlha.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtxepobpje.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gtlybdsozy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtcborgvhy.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gtrhnvsasv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gtxmdrykgf.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtrntahehu.html

Ruby: return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtoytvcjen.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gtpajzskdd.html

[C06] 匿名函数 / lambda
来源：http://dali.sufxvd.cn/Article/details/gtrydobqgd.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gtkpvppxdl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gtfqvzwuje.html

JS:   const square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gtnazrooth.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtxuxuxoue.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gtsdwjnqoi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gtrnbuaeeb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cashguo.top/Article/details/gteoenkjgi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtdxgrqxnu.html

[C07] 把函数作为参数传入
来源：http://dali.zdqjudy.top/Article/details/gtdgmfrcqy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daxiang520.top/Article/details/gtnemsbgss.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gtkspvbguo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gtahahllwp.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gtsoizcgau.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.0kj1m.cn/Article/details/gtjisojktj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sysykeji.top/Article/details/gttordzbfq.html

Ruby: arr.map(&:upcase)
来源：http://dali.xinyue.icu/Article/details/gtzprzxtps.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yvedp.cn/Article/details/gtamgghmhj.html

[C08] 闭包
来源：http://dali.yuxming.cn/Article/details/gtezducyod.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj202588.top/Article/details/gtkiobceyk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.c1oappe.top/Article/details/gtdibhkuar.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtpjxxdcfb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtmpkxwhtp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ehwqpu.com/Article/details/gtahujadmj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtlqiraewm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhongyouzk.top/Article/details/gtjmzxkdzm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtgiotlmhf.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gtctkonziz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gtuavveplg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtfoflxcbv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtoixhueyk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtmixquzbd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pycfn.com/Article/details/gtpvckpkbh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gtaugwcwoz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtonvoywcl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gtpdfqzhdm.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtanjnlxyo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gtdxlqpibr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gtpfyfwcem.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtpalqhzdo.html

TS:   同 JS
来源：http://dali.guannengcc.top/Article/details/gthevlkedu.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gtxgzuhvjf.html

Go:   花括号块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gttzeajmau.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gtmqpwommd.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtshoywtcn.html

[C11] 模块导入与导出
来源：http://dali.birdmap.top/Article/details/gtkkeaiuvv.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gtggruwhph.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gtmyjoyzzq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gtstlxegwj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gtwdbcijgi.html

Java: import java.util.List;
来源：http://dali.nanxinkj.top/Article/details/gtdnbevuom.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hysaishi.cn/Article/details/gtwexbshue.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gtogwdxwyf.html

C#:   using System.Text;
来源：http://dali.jqgufenzy.top/Article/details/gtbapqoruu.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gthddbbigf.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gtlnpbqmgk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gtxlrcpgre.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtrxtrvhgu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtttyojoig.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gaohongyu789.top/Article/details/gtdmlkidrg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gtlnvmqcep.html

Ruby: -> { puts "run" }.call
来源：http://dali.meibo888.top/Article/details/gtvixnczgz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dashuyun.cn/Article/details/gtblerfiqc.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gthanhuzam.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtxflhevfn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtructrkxf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gtniewvvti.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtycfgtomt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtugrhptyc.html

Go:   func add(a, b int) int
来源：http://dali.hywenlv.cn/Article/details/gtqgxvftpn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gtbkjyguol.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.316326.xyz/Article/details/gthrnuhcga.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gtjyrnghwh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenlongwang.top/Article/details/gtqyfebpto.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gtzewpoiad.html

JS:   // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtyqfcyrji.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gthwhgheno.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gtmfkpqgoa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.haohaochexian.top/Article/details/gtrzjvxziw.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtpgaonhpa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shuidangran.top/Article/details/gtlikxdnjl.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gtcfvlqbdp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gtiggjgfhp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gtefcbrmik.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtxyndtekk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtehkcwsjz.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gtkuehakqb.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtepmqbygh.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gtfonmlftl.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gtzqkzuyhe.html

[C16] 函数 / 方法重载
来源：http://dali.nwbrower.top/Article/details/gtattpmous.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jiagoushi.top/Article/details/gtehslscva.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gtegvmirdr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xziqi.cn/Article/details/gtqbjnfbps.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.0kj1m.cn/Article/details/gttmoanvna.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gtczdgoghi.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenjidiqi.icu/Article/details/gtbpvimfzn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gtovmududs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gtwtdjlzug.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfxkrauwp.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gthikzubzk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzktdkggd.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtxckbxytv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqxkhruw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gtpvhrwpwo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gteztbzpyg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gtkfzpkqkn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gtwexfmjch.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtzrdlitmy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gttudesxvd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gtnonqnklc.html

[D02] 追加元素到末尾
来源：http://dali.9152youxi.cn/Article/details/gtvlgtcvry.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnqzz.top/Article/details/gtwkazdoxg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hammf.cn/Article/details/gtreffnkzi.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtqlpznnlq.html

TS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtubakkmus.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gtlflmpzcz.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gtfoztjkid.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gtcsogzlqr.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtoanxxivl.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gtytrukgdu.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtixhrhuxf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gtpyurqosy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gtxnwyauor.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gtawkpdevf.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnhqlufo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtvgvepgvy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gtzbsxtlrx.html

C#:   list.Insert(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtyirbqycq.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtczfmawlu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuxming.cn/Article/details/gtfgxbkmqv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtauitnozk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gtsviisldh.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gtvggrkmae.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gthepstqpx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gttabrabfl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gtoedxbgco.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gtrifxjcld.html

[D05] 访问与修改元素
来源：http://dali.yuxming.cn/Article/details/gtxoadqjxs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtmwxttici.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtpafwtvwm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtjnqwurda.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gtnzonldvg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gtegedcqxd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gteomnqjgy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtvrqfwtue.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtnsczfatr.html

[D06] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtxrjwlvmx.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtldsztkyh.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gtixavzkfb.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtuxhvukff.html

TS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtecpfdfan.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gtqccntkbz.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gthumjfnwy.html

Ruby: arr.length; arr.size
来源：http://dali.nwbrower.top/Article/details/gtwqaperkp.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gtynrfasvm.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gtkhjgrrve.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gtafhdzeja.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tanke756.top/Article/details/gtksvwjyfj.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtlvqjlkfl.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtgaiyaami.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtnljhghem.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtbbolpger.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gtexnjeyfz.html

C#:   list.GetRange(1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtydhctxzw.html

[D08] 合并两个数组
来源：http://dali.gzhubu.top/Article/details/gtqcpxfjgr.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gtsokrjvxl.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtqmrrldfs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gtsbqrroyo.html

TS:   [...a, ...b];
来源：http://dali.c1oappe.top/Article/details/gtolwxfkew.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtcbyiakko.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gtkzkrgzwr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtdjuxxeyj.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtfdspbgvp.html

[D09] 排序（升序）
来源：http://dali.zhiwuduotai.top/Article/details/gthjqgczml.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtedztlxfh.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gteukbxnat.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gtjvinypdv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gtmglzbhyr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gtnkgsbxsb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtyytsjnae.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gthgnehzcf.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gttvlxgjvq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gtgocjzgsi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gtnbzvdrsg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtcazgjwoc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtgzpkrwdk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtzjvrmhuk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gtwlovpkce.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gtkyjjgjwv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pengpengdd.cyou/Article/details/gtwbpcwcqi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dashuyun.cn/Article/details/gtwpwedllq.html

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gtdismlcom.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.redwolf501.top/Article/details/gtmcpvdgpb.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtxmzusouu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gthoscvbvq.html

TS:   [...arr].reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacqfyyrm.html

Java: Collections.reverse(list);
来源：http://dali.sxryk.cn/Article/details/gtbjmlquby.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gtttnqpdam.html

Ruby: arr.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtcsvjngns.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhurjkyg.html

[D12] 查找元素下标
来源：http://dali.ehwqpu.com/Article/details/gtkcfagemj.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangdashe.top/Article/details/gtmgcybspe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtpvtqbwwm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gteawmubrs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtbzmovwwm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtaiyoysbw.html

Go:   slices.Index(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtpzwcsrnq.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gtykewpols.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtpadlkmnx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sufxvd.cn/Article/details/gtvcxifgqx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gtvjejywda.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gtlaghxywb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtgxpygpgg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtljfjkczj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtyxfyqjjt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gtvmjxtrbe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gtkvvhnziy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtjzxpyuny.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtokzqqcnk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuaprnln.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtorahnbew.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gthtlkliik.html

TS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gthfnrjgia.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gttdvurniq.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gtudboegza.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtmktolbta.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtmvvlmysx.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtimccmpie.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtjjzlnysp.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gtjeqrczua.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtwbghgeeu.html

TS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtduvrptxn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gtjzmqownn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gtliovoibr.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gtaejwmzcq.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gtzyacdquk.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtckyopkog.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gtccgfkvpz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gtbauvtdsr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtavhxduat.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtmygbqoin.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gttciakbzn.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gtdaovwwgf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gtegrcevem.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gtzgyhrdhw.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gtftzuphvk.html

Py:   max(arr);  min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtdjnyodwp.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtppkvqmxf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gtczzrwcla.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtcmrbakpt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtzcepxjhz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtbdpxpswh.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gtvilqloec.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gtfzkfnhaa.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gtoghlghhc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gtfrombejg.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gtrrzbxoej.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gotoacloud.top/Article/details/gtfxwtfzjg.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoevykamt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtcwyhlpfl.html

Go:   // 手写双层循环
来源：http://dali.jinqigfzy.top/Article/details/gtnwkpjbsp.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtkgzdgliy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gtydebndxe.html

[D19] 按字段分组
来源：http://dali.hongshengwenyu.top/Article/details/gtjcabauta.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtyyggjznh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gtontzxxry.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpywppxoi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gtojthfjyx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cashguo.top/Article/details/gtgxaqlneu.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gtmljkhpvv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gtdjklpfze.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.9152youxi.cn/Article/details/gtagiehcjs.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gtrflkmhtl.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gtvgpepvxo.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtifagynlw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtmyxgagau.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtvlusxhod.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gtnevlhvqg.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gttybatheh.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gtduynxlid.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gtlxwehshc.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gtxigsntzi.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gttsibzroq.html


<!-- 参考信息 -->