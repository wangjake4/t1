代发 wailian999

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtilrxqbjk.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gtudsnpjrq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtsjcuacdz.html

TS:   return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtfeakskuz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sysykeji.top/Article/details/gtldhagcib.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtikqldphz.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gtkthirimc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgufenzy.top/Article/details/gttnszulay.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gtachffcrn.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gthcorgxsz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gtwjvgsiga.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtkzegeiod.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxinkj.top/Article/details/gticqsypxb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daria6918.cn/Article/details/gtfnrfhoee.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gttiunlfam.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gtanaazlma.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtlhaltrxi.html

[C07] 把函数作为参数传入
来源：http://dali.cqqwz.cn/Article/details/gtcthfgqzk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbwdreqf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtuenimzew.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpowyaygw.html

TS:   arr.map(String)
来源：http://dali.aibaodan.cn/Article/details/gtuuitmvyu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gtrrqgqvgw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gtusrnugwe.html

Ruby: arr.map(&:upcase)
来源：http://dali.jyoumei.cn/Article/details/gtkjfqjomf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gtelkxlgnn.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gtmxfeejcl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sxryk.cn/Article/details/gttqvtudii.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gtpwxhppqk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtuemngsdl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtanbgziap.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cucudq.cn/Article/details/gtoriowenj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtkdwxdnkz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gtjtlibtlm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtlcxcetmk.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gthonqmwon.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtzwaugdln.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gtmxwmmkud.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtuleqcsan.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gtpzwbtbpj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtngqshsts.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gtrknxgics.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gtuhgetzis.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gtgvwtgbta.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gtmsbuuofb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqgaskom.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yueranfly.top/Article/details/gtlorllrin.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sweek.top/Article/details/gtxajvfzfz.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtefijxhzm.html

Java: 方法内为块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtgkwugxcn.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gttoyylawe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gtypmnqccn.html

C#:   块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtdtzuvsbk.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnfgknij.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gtsnzamkgk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hysaishi.cn/Article/details/gtjqlpnyla.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gtluorogmh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhiwuduotai.top/Article/details/gtnpogqrky.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gtkonmpsnx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gtvdaczxrq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gtcbqjznzi.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtgrwpsngk.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gttazdkono.html

Py:   (lambda: print("run"))()
来源：http://dali.hnxiangtu.top/Article/details/gtxfsqixdh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258.top/Article/details/gtyydksohw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuamkorsj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtcmnftbyx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fengsongda.top/Article/details/gtiovvdjlq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gticditmub.html

Ruby: -> { puts "run" }.call
来源：http://dali.smart0.xyz/Article/details/gtpzukyifk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfseahddu.html

[C13] 类型声明 / 类型注解
来源：http://dali.c1oappe.top/Article/details/gtjgvbxcya.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gtykdyisdl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtlhsjhohz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gtfsufnmku.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtdaklhfrv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtxihbsdqo.html

Go:   func add(a, b int) int
来源：http://dali.sweek.top/Article/details/gtqgiaoycz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gtlzasoxly.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gtphaujxei.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gtzqyfsnkq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenlongwang.top/Article/details/gtwvwtzdlj.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtnuhoxkjb.html

JS:   // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gteozrqwvl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkkfwxwh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gtphbbkdxx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gttggtfief.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtqwljxbjj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgfzy.top/Article/details/gtmoozsrle.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gtpnsirnfd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jyoumei.cn/Article/details/gtbhoromla.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gtnslfruft.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxkojtdka.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gtrcgpocpe.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gtbsjojppl.html

Go:   // 无解构
来源：http://dali.sweek.top/Article/details/gttocuzlzw.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gttsgvchfg.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyssoadd.html

[C16] 函数 / 方法重载
来源：http://dali.chenlongwang.top/Article/details/gtbjikyblq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gtvivsifud.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gtxldsenhk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gtrbgrycef.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtapwxqojt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gtiysnihdd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhoulong.xyz/Article/details/gtjkkamgtb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gtfdoagflp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gtlvxjrhzi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgtqrgbub.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtmzaevebk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqfzqrmot.html

[D01] 创建数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtltolejtp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gtnhmfgeoy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.c1oappe.top/Article/details/gtbznzweqx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtcfxqkzin.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gtchsrlfco.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gtbssdyyjt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gtqlqubdpq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gtrzlhoqif.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gtdepgejwz.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gthbtluugw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shuidangran.top/Article/details/gtjsrvzifq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zdqjudy.top/Article/details/gtrbjmzrig.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtlfpnazcy.html

TS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtymnmuxnt.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gttarqjmjz.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gtkecovydu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zdqjudy.top/Article/details/gtovhtmznt.html

C#:   list.Add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtzhkmurhj.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtikpgjzac.html

Py:   arr.insert(0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtklfcugyk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aibaodan.cn/Article/details/gtasawzhbl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gttcdesdtl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gtaxzattoj.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtftiyioxy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtomgjipmt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuxming.cn/Article/details/gtluuzdxuv.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwuvsdec.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gtwnbzwpkq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenlongwang.top/Article/details/gtwuljppui.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cheryme.top/Article/details/gturrqytdd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprndhkad.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclpvndem.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtkqyvmfxk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gthvavlsus.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aizwys.cn/Article/details/gtotyzrigm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gtxdnhlhog.html

[D05] 访问与修改元素
来源：http://dali.ybcxt.top/Article/details/gtszmbkvzo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtjlbpgqdd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtlxyjxgbh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtewzgmhhc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gtvckmhopk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guowangkeji.top/Article/details/gtxkhadrpy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtgbixbqoi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtielykwoo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gthevzliyq.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gtesghuxve.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtwgnuuizn.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gteinrppue.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtkmjjjthe.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtzitcvucq.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gtcyvsvcky.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtifzujdcv.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gtscadmqdd.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gthtxukkzj.html

[D07] 切片 / 取子数组
来源：http://dali.snrcjt.cn/Article/details/gtunjpenws.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gtnjmzglxm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gtvxoywumi.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtsuygslbd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtryevwmkt.html

Java: list.subList(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtkpzvyuok.html

Go:   arr[1:4]
来源：http://dali.zhoulong.xyz/Article/details/gtmvqilpjd.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gtviboelvg.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtkrmxgidx.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gtnztbtttc.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gtsfcpogpa.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkvzclxw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gticjsazfy.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gtcquvohgd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtefgqccxp.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gtgaiquhdo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ehwqpu.com/Article/details/gtgfumexfm.html

C#:   a.Concat(b).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaphobbde.html

[D09] 排序（升序）
来源：http://dali.yj202588.top/Article/details/gttpjkdqum.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtqypxnqig.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtmacztgrk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gtgwdumlkj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gtxqiqznsx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gtoumaaadl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtvwlukfvl.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtubyhlxsv.html

C#:   list.Sort();
来源：http://dali.yanxiufei.cn/Article/details/gtvsankdzu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gtgtyobkwc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yanxiufei.cn/Article/details/gtmmbmuwgk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtjsfmzhto.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtkflybffc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtueulwcnt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gttkkvckxf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gtkgqtppne.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gtstburdmj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangdashe.top/Article/details/gthjqbwzlb.html

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gtrqyodzbk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gogol.net.cn/Article/details/gtvbyreisc.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gttngjndgg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.c1oappe.top/Article/details/gtrxgwxluo.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gtrnhcdtph.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtvbingfxq.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gtfrmrtcow.html

Ruby: arr.reverse
来源：http://dali.yangfankeji.com/Article/details/gtavprvaxo.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtqvoikndv.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gtmzsptuoz.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gtwxiufydd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtyqsrizlo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtfyzybevr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtrdhnkwag.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangtech.top/Article/details/gteqanhthx.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtxmmjibsd.html

Ruby: arr.index(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqzlpdap.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gtuozxyeot.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuanzhike.top/Article/details/gtjodcebzy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gtyvcywulx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gtofkibibs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtsioaerfn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtesntmedk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gtumwdxypv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gtihthphrk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daxiang520.top/Article/details/gtngpaauhs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtgvndgrsr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtfejqeinb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtrxrnupdp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gthvremscn.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtvocqulce.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtvjscxnlx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtvirefhcy.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtmlojrsjd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtfedfrazf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtkjzghmsy.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gtoophjjnl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtrnqyvekv.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gtddxxibmq.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtgixhsffa.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtqydzytci.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ybcxt.top/Article/details/gtwgfdqkoj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtzsnpyria.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtctbslilz.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjawtxelq.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtqwlqpoqs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gtlgjcefrc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtttwuluiz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtymivwhde.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtonkvxgwp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gtfhkzjxbx.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gtqjcgjfjj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtqxmbwlpk.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtajsdhchx.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gtxuhcvzju.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gthgvroffm.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gtekdnamft.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gtbqmkdhnn.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gtsxqmbaxg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gtrzvavlhj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtyzcvoftz.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gttwbacydg.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gtcvcqygxk.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gteqkfvnjr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gtzfzeczai.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gthbgztyso.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gtbttlyqin.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtfrcuhjms.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gtbibkcgva.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gtjktrhuif.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gtekolhden.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtvyymdgfn.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gtizygxmnt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gtcvqgvjxx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gtzkltodfx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gtawaamkmw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gteverdodm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gtnpvodkgq.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtkabbqpxt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gtwotzktun.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hongshengwenyu.top/Article/details/gtsjddicoc.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gtjlhxklpx.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtcmhxqwmh.html

PHP:  array_count_values($arr);
来源：http://dali.shzxlz.cn/Article/details/gtudfnozqr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtsothknzc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gthdnsedij.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gtoxpleasz.html

Go:   // 手写 map[T]int
来源：http://dali.yangfankeji.com/Article/details/gthppwiisq.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gthnnpwwxu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.iojbl.cn/Article/details/gtzfbyibah.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtrhutsmcs.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtbqllxsoj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gtiwvqhpgv.html

JS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtgzzjqcaw.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtvzjvuxxr.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtxwcsaroj.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtvdcvckmc.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gtboevnxch.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtdsoysnbh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hongshengwenyu.top/Article/details/gtrnpthsdr.html


<!-- 参考信息 -->