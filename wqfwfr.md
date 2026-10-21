代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gteszaejyd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gttthzpbcs.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtzydzuupt.html

[C05] 返回多个值
来源：http://dali.yonumen.top/Article/details/gttzpkaqws.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtnvpkwnkq.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtskepvsdy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtkzjypwyp.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gtaoosfqjl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jlsjyb.cn/Article/details/gtnpvhkpej.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtvesjbpeg.html

Ruby: return a, b
来源：http://dali.sweek.top/Article/details/gtqxsacwfp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gtukeebzgg.html

[C06] 匿名函数 / lambda
来源：http://dali.yvedp.cn/Article/details/gtszjvthwo.html

Py:   square = lambda x: x * x
来源：http://dali.dashuyun.cn/Article/details/gtxynoxtkw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zycfv.cn/Article/details/gtuknqejmm.html

JS:   const square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtioozxbvw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtgcqshkyq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shuidangran.top/Article/details/gtscvjhhmo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gtmavkqcgs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gtbqmzaqee.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtuwtykmou.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gtkkptjkva.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sxryk.cn/Article/details/gthvagywra.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtnufgczuv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jyoumei.cn/Article/details/gtkdojpyoi.html

TS:   arr.map(String)
来源：http://dali.xylfe.cn/Article/details/gtyhkmfllc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gtdmsuspeq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gtjzpptycs.html

Ruby: arr.map(&:upcase)
来源：http://dali.yongpay.top/Article/details/gtudbqbtlw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gtlimhgfqq.html

[C08] 闭包
来源：http://dali.dianchejie.cn/Article/details/gtkasblsdp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.iojbl.cn/Article/details/gtamkegxvi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gotoacloud.top/Article/details/gthmtakuvr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtfwvlzcrj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gteknicxcz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenzaomai.com/Article/details/gtootxmaeh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gtuoneqcjm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pengpengdd.cyou/Article/details/gtbmgyyokl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtucoubjbo.html

[C09] 递归
来源：http://dali.fzhhl.top/Article/details/gtlocrgulp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhcruyvd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gtvuzpnnur.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtvipsyimw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gtdjymlaxm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtupegkhap.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gtjmxkxrad.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtjhleypdy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.quarkkingdee.top/Article/details/gtjudjmutl.html

[C10] 变量作用域
来源：http://dali.xylfe.cn/Article/details/gtfhjbykrc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gtcwibmder.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tianlin.xyz/Article/details/gtcxlddidz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hammf.cn/Article/details/gtgyivnjtt.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoarifhwd.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gtfchpasor.html

Go:   花括号块级作用域
来源：http://dali.mhx1999.top/Article/details/gtbpbahvrf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gttyiwbznz.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gtgmpsvpgu.html

[C11] 模块导入与导出
来源：http://dali.bjfxy.top/Article/details/gtjbzumamf.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwffpknxc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yongpay.top/Article/details/gtxlzvtuzu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtnrfjhjkx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gtmhinhccy.html

Java: import java.util.List;
来源：http://dali.pycfn.com/Article/details/gtfisbjntj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yvedp.cn/Article/details/gtcgqxkrhx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gtuohjmgde.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtpbvhmrat.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gtygivbqfv.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gtszcwhidr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gtvibolwip.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtpjgwazki.html

TS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gtbsdxxyku.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gtyovqoucc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yonumen.top/Article/details/gtixgfqgmk.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangdashe.top/Article/details/gtvgxcrgqk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtndyemhin.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gttnrpjzvz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gthmndklcw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtxzdfwcaa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gteswzxdml.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtkzulylfp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtixkhergn.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gttfmotwrn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gtmcxwvzpy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nwbrower.top/Article/details/gtavznadkd.html

[C14] 泛型函数
来源：http://dali.yuanzhike.top/Article/details/gtcqsxtvvl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tian-w.cn/Article/details/gtzgrgqllm.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtncnltnuz.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gtgbjgwmgd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gtyxtadysc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gtmtliosxs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gtzmzcosaa.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gteyiwqafq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gtejnbanns.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gttekqwqth.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gtqsbtnpkd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sxryk.cn/Article/details/gtepjadmdh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtiqfpyjdv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtaqywbhbp.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtbogclnwp.html

Go:   // 无解构
来源：http://dali.hysaishi.cn/Article/details/gtfunqkbvo.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gtlzbsocbf.html

C#:   var (a, b) = pair;
来源：http://dali.yuanzhike.top/Article/details/gtbxmmudkz.html

[C16] 函数 / 方法重载
来源：http://dali.jyoumei.cn/Article/details/gtegnewlds.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gttuldhfas.html

PHP:  // 无重载
来源：http://dali.yj20258.top/Article/details/gtkoqxsfdx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hysaishi.cn/Article/details/gtwiqqudbk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtrajwmjft.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtlznzncyc.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqwhrkfx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gtvavyddwd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sweek.top/Article/details/gtjvbtihpp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqnqkaksi.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtmehdniem.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvbjsikyg.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtbwxeilky.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gtssipvils.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.birdmap.top/Article/details/gtegqspzjf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtidbgsvxj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gtfduhujst.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuanzx.com/Article/details/gtkbxisczr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtdhvubsue.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gttugxewqt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gtgceflmak.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gtxeiliohs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gtnuiviieu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gtukvbhvjc.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtdljbtbci.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtvyyoxeao.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtyjsascku.html

Go:   arr = append(arr, 4)
来源：http://dali.hnqzz.top/Article/details/gtdsjahaiq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtnvwewxmc.html

C#:   list.Add(4);
来源：http://dali.wangdashe.top/Article/details/gtmikyoetx.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gtnbihltii.html

Py:   arr.insert(0, 0)
来源：http://dali.zdqjudy.top/Article/details/gtfaaibdgn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gtriegdxqv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gttqdiihhz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gtelodgmka.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gtgfyfazmo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daxiang520.top/Article/details/gtridkszpl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gtsqkjldvf.html

C#:   list.Insert(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtykyoaenq.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gtycjlopry.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenzaomai.com/Article/details/gtdmcqbcrx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gtrlkjzkxu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.smart0.xyz/Article/details/gtvgedkkbe.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gtletdtnsv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtpwfyngih.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtdkelvcpf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gtspysjuwm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxinkj.top/Article/details/gtdabahvpg.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gtdtguvhiu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtbyntbpmi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtgolnfiio.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtaxucqohd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gtxubpgpaw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gtnfomcwpx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtbtbinhgb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtjglcosfl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtokadlbwi.html

[D06] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtxgnmrlai.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtgmdtmlll.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtgdjghugi.html

JS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtbxoyooop.html

TS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtqlhwnvfs.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtmrgshvlv.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtdmbvlmoa.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gtaczxkres.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gtrraxdysd.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtpogvhrah.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gtlzrfrevg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdiawbhx.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtjnxylkoh.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gthwrvwqsk.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtxlooaivh.html

Go:   arr[1:4]
来源：http://dali.hongshengwenyu.top/Article/details/gttucqzxma.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gtfkanqscf.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gtdvveomcc.html

[D08] 合并两个数组
来源：http://dali.jqgufenzy.top/Article/details/gttutmfwpb.html

Py:   a + b;  a.extend(b)
来源：http://dali.ybcxt.top/Article/details/gtrcfjuhbo.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gtwgfhnycn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gtngfachud.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gtjligviac.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.haohaochexian.top/Article/details/gteqqowfcr.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gtacnlympa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtzrsekvxc.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gtzahjnffg.html

[D09] 排序（升序）
来源：http://dali.cdnleiting.top/Article/details/gtbxohlzsk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gtyebpnryy.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gtqbkcqaid.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gtjkyrhxix.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyocxujdp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gtyeenzqcg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtbptcxihi.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtromvjpze.html

C#:   list.Sort();
来源：http://dali.tian-w.cn/Article/details/gtniraqzro.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gtotmiaeju.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sweek.top/Article/details/gtxfpkomqd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfvtptys.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtxwkqkelu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxywoisz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ppjwa.cn/Article/details/gtzoepqeny.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gthbtrfabs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gtneiwxbtu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gtsjpuuhye.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gtlwbceslj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gtdxhovyvu.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gttcbfyhkq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnmozypb.html

TS:   [...arr].reverse();
来源：http://dali.gotoacloud.top/Article/details/gtejxcvqse.html

Java: Collections.reverse(list);
来源：http://dali.jqgufenzy.top/Article/details/gtxzgxrndo.html

Go:   slices.Reverse(arr)
来源：http://dali.haohaochexian.top/Article/details/gtniqtlama.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gtxyfydxvg.html

C#:   list.Reverse();
来源：http://dali.jiagoushi.top/Article/details/gtlillgrai.html

[D12] 查找元素下标
来源：http://dali.quarkkingdee.top/Article/details/gtzoapaqto.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gtfcvarzsn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtxrvnknsn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtevireoik.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtrndazgyk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gtfhgrcosn.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gttjneywps.html

Ruby: arr.index(x)
来源：http://dali.yuxming.cn/Article/details/gtkllbywur.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgzofcuv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gtfxfaafjz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gtnvaajkjg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gtffieuynt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfiyfhid.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtakujrfno.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gtkehkepfy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shangyingyoupin.top/Article/details/gtzhnbcuhs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbeiynjo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtwlgvzxad.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gtxtyzefdn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtflqzuvxt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gtnxtjxbgj.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtneoliteg.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtspszkhnp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gtffttbdzq.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtgchfghtz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gttsulzfzr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gtcavbpakp.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtqvrjpcui.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtjlsmujqe.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gtzzcvflke.html

JS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtfrmdckxu.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtshjtjvlh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gttisfwnnm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gtbkzmnoeb.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gtkmuodyaa.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvxjpmgg.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gtrudsorfg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtpvbvahvw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gtazlecibj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gtsdcphemz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtonjawire.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gtxdtogjgj.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gtagecrnek.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gtcqxwzxsy.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gtdhryiwle.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtnioswwgd.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gtfgetndho.html

PHP:  max($arr);  min($arr);
来源：http://dali.jianghu66.top/Article/details/gtwjpdwfyh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zdqjudy.top/Article/details/gtyxtitzjc.html

TS:   Math.max(...arr);
来源：http://dali.aizwys.cn/Article/details/gtwmxyftwn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ybcxt.top/Article/details/gtyfjjnspm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtophrxxxq.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtrqxwcaoq.html

C#:   list.Max();  list.Min()
来源：http://dali.316326.xyz/Article/details/gtnvxswuib.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gthgiqaiuy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyihamfs.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gtvybpogkv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gtabtdqpuz.html

TS:   nested.flat();
来源：http://dali.nanxinkj.top/Article/details/gtzyyfropr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jianghu66.top/Article/details/gtvfgvcqzr.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gtugxvptyy.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gtjsaexzce.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtzyzifkaa.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gtolwtgkww.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtrzxkiclk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtllfzjzbx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gtwfjinovt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gtxjmkinxj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tian-w.cn/Article/details/gtxrkdsbjf.html

Go:   // 手写 map[string][]T
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhmndljy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtwvrxumuh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gtfzztbotm.html

[D20] 统计每个元素出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtcpwhijsz.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtuekrkpxd.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gtlwlarzep.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtwigqbxzi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtieusntrl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtmqnijcnt.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gtsajuyimp.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtnccqmjdv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gtjzrfiuyi.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxpejmsr.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gtrbkvchvv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdpwxubf.html

JS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gttcbiizev.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtkbsiailw.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtjgmrsyzi.html


<!-- 参考信息 -->