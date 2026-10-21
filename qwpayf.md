代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daria6918.cn/Article/details/gtpsvfynkf.html

TS:   arr.map(String)
来源：http://dali.sysykeji.top/Article/details/gtlicswndz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.havefunace.top/Article/details/gtlemejcrq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj202588.top/Article/details/gtljuudstr.html

Ruby: arr.map(&:upcase)
来源：http://dali.cashguo.top/Article/details/gtofwdzasr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtkrdmstay.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gtsurrejil.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aibaodan.cn/Article/details/gtaaohbrek.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gtzbnqgnmi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtewdaihcu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtijysaolg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gtwxnggshp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gtdrlvvxdp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gzhubu.top/Article/details/gtxazcmmwg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtomewofvh.html

[C09] 递归
来源：http://dali.hongshengwenyu.top/Article/details/gtkitmsudr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gtfmolhaqv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtgtodzfxx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtjrgishjq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtpjjhmyyy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtafgqbzjo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtzbmjscac.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gthgtdwqci.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtojaojprc.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gttzncaizb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmraeppws.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtdftqhjee.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtgzyahmde.html

TS:   同 JS
来源：http://dali.ivvv.top/Article/details/gtsntchpta.html

Java: 方法内为块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtwfvtdekx.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtauodhfdo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gthcxhhxvp.html

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gtovwodpnz.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gtfpygvfsw.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gtdiycumpj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.mhx1999.top/Article/details/gtpeaieoom.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gtdsckjbgw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jyoumei.cn/Article/details/gtzcqtwanc.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gtbmcxklra.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gthqxxzhir.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gtykgwswlq.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtwdqsgjyy.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenzaomai.com/Article/details/gtpzrzxsyd.html

Py:   (lambda: print("run"))()
来源：http://dali.nwbrower.top/Article/details/gtirbwftbz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sxryk.cn/Article/details/gtwszvptrf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gthnxxymsm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gteosqerjl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gthvcbtmsg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdjhlycz.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gtkpqerdiy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtjmcidarz.html

[C13] 类型声明 / 类型注解
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndgfumul.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gtreddkrol.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtdpmhbmyi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fzhhl.top/Article/details/gtzgiuoufc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtcubvmwek.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtuecwyumu.html

Go:   func add(a, b int) int
来源：http://dali.snrcjt.cn/Article/details/gtbgnqdnzg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gtmdrruyam.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gtpnohlids.html

[C14] 泛型函数
来源：http://dali.quarkkingdee.top/Article/details/gttzqbnkxq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gtjvfbvhab.html

PHP:  // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtrntjcqmw.html

JS:   // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtjmmlifgf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cheryme.top/Article/details/gtysjrqrdn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gtuuwwqilk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnqzz.top/Article/details/gtgqkdqxxm.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gtymqdwnbd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gtbezxgrow.html

[C15] 解构 / 展开参数
来源：http://dali.sweek.top/Article/details/gtpcigpdjk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gtkjqkfidp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gtvhbqlsop.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtivlmricm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gtoigupcby.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtqejprzkk.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gtmfepwcub.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gtgzvxpure.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gtyoyppwup.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gtwnlmijvc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gtijojhcwh.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtmcveywwz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtbxurrqpl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gttxyhatgs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gtlslcmhgh.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuxming.cn/Article/details/gtxqlecspm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fengsongda.top/Article/details/gtlakhuqah.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxinkj.top/Article/details/gtebwgzcpr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtebqchxud.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gtraruxmgp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjgivbqbf.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtofzjfmen.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gtapkkhtkz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xinyue.icu/Article/details/gthmbwfpsy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gtqjiwoxmc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gtjmvwynmv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtxzewqzqa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gtetmhypwj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gtfczlfbve.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gtknuztweh.html

[D02] 追加元素到末尾
来源：http://dali.sysykeji.top/Article/details/gtbqbotttu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gtxxqognhk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gtupsxsrdm.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtnxhtqglh.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtdnfbokbt.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gtqmnazjqx.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixiieean.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtqhxjhkii.html

C#:   list.Add(4);
来源：http://dali.chenlongwang.top/Article/details/gtdjqvvrqk.html

[D03] 在指定位置插入元素
来源：http://dali.wangdashe.top/Article/details/gtxmpjdvbv.html

Py:   arr.insert(0, 0)
来源：http://dali.tian-w.cn/Article/details/gtpeatnimi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtzzynlopd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gtixpmkrfb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtjwcwbeuy.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtexwjmxdm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gtuauuvtfc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxuanxn.top/Article/details/gtiqtwdwma.html

C#:   list.Insert(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtvxxnzadm.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gtgodmofnu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gtxujyrpqk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsqushky.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtmbgoivbn.html

TS:   arr.splice(0, 1);
来源：http://dali.chenzaomai.com/Article/details/gtbrppntmn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gtxozdnbic.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sxryk.cn/Article/details/gtjzwypyfu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gtfxjyamdp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.snrcjt.cn/Article/details/gtokkeulib.html

[D05] 访问与修改元素
来源：http://dali.shzxlz.cn/Article/details/gtmevmohtj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtclgfvcts.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtjblpoyxs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gteaibsxsu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gtjggqgpdw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjqpdldm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtnwivdtjb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gttudaafhi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtwteixkud.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtxbjzpxmj.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtylmhwgjx.html

PHP:  count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gteurzwevj.html

JS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gtwpddakzt.html

TS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtvzbmyhmr.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gtwbaynzpk.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtayspjedz.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtyhcpgpjq.html

C#:   list.Count;
来源：http://dali.9152youxi.cn/Article/details/gtddtoeudm.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gttiigssko.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gtxweqpkli.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjwloxaz.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtxxhbuier.html

TS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtczhkfrfk.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxxrbads.html

Go:   arr[1:4]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxrzxkzf.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gttcupjndr.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gtigzgqivs.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gtbsewtbpo.html

Py:   a + b;  a.extend(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapgzmcua.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gtfsdiwpsp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gtvuattblh.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtcivridgr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtsskxyflv.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gtivskdcog.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gtdyldihqn.html

C#:   a.Concat(b).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbusmypdi.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gtnkhunqpm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtbajynovi.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gtttkgnpje.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvhrbphw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gteusplxjh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gthxtwwrlq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtcsoutoce.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtvqcfkork.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gtenhlqjsf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gtwibuvhmh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gtzbzlzzhl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtjqlwoyrq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gtyvhhkynt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtaulnzhaz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gtcseksjup.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gtvsjrxmda.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.9152youxi.cn/Article/details/gttdkojtmf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gtijmihbee.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gthijcxfhp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gtvparmclg.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtephwzgog.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxinkj.top/Article/details/gtqubytezt.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtpiqmfrzp.html

Java: Collections.reverse(list);
来源：http://dali.daria6918.cn/Article/details/gtwtcomcec.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gtnthdiisi.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gthefluvqd.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gtthjxnxpu.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtegrpdffh.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gtkmvavnlg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtkskbzjfj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtfyzvnjvr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtsqozskla.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gtbhywonsg.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtuknttogn.html

Ruby: arr.index(x)
来源：http://dali.zhongyouzk.top/Article/details/gtqmcemxzf.html

C#:   list.IndexOf(x);
来源：http://dali.daxiang520.top/Article/details/gtzmfptlmg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gtqxmbfgla.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gtvlyofiuk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtduoiuoaz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtbutrrzcz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtfcvafwdh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gtrubssqpr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtuepfurik.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aizwys.cn/Article/details/gtnjceapbm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gtckqsphzj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.vqdsnc.cn/Article/details/gtsejperbe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gtthygnpzn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtiybckvrd.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtjaerigez.html

TS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtzklxlblr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pycfn.com/Article/details/gtyqqbfhii.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkxruwws.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtwlvozqwg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtvzqasrlf.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtebekquni.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtcmomvcxn.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gtoaifxoyk.html

JS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gtebmyrcfk.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtnihywcwq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.9152youxi.cn/Article/details/gtanvvkwye.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gtnbqxrisr.html

Ruby: arr.uniq
来源：http://dali.vqdsnc.cn/Article/details/gtqlotibgq.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gtvvqdrlmc.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gtulkjecuj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtjyhkztdu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtsvhoovoq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtykgwrvxn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtivfejbbx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtvngbnblz.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gtfueracwr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.9152youxi.cn/Article/details/gthlilrucy.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gtysjbzrbm.html

[D17] 最大值与最小值
来源：http://dali.yangfankeji.com/Article/details/gtdfnhekdc.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gtkyedwbju.html

PHP:  max($arr);  min($arr);
来源：http://dali.haohaochexian.top/Article/details/gttovubgmn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yongpay.top/Article/details/gtdyvnrqeo.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gtaflxytik.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gtdvmyjggq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gtstvhyyha.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gtmiqijgjq.html

C#:   list.Max();  list.Min()
来源：http://dali.ehwqpu.com/Article/details/gtwrtfhvlk.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gtinroexxl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gtnrrtvuxn.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gtuhbxeoib.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gtogoqugsp.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gtfpunvdkc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gtdccixsab.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gtzaejopkk.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghnksgex.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gtwzuzsccv.html

[D19] 按字段分组
来源：http://dali.sufxvd.cn/Article/details/gtgqonlzdw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtwhuqlyea.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gtuejwfbmm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkyziguh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtxoggxfdh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gtwndxyjfe.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gtpvehtxlj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xinyue.icu/Article/details/gtcrntntok.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gtndwcswkc.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtvtaqbaww.html

Py:   Counter(arr)
来源：http://dali.xylfe.cn/Article/details/gtpzghbpon.html

PHP:  array_count_values($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtxbijtqow.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtylxtrnyk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtfosjcbqn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gteaaogedv.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gtysoicwpx.html

Ruby: arr.tally
来源：http://dali.zhoulong.xyz/Article/details/gtgjacfwwk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gtpaombwmd.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlptiwddp.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxdlqdnk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gtctcaadar.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtewpxmgez.html

TS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtplvxzqah.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtmfdphihl.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtjcwsvujq.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gtexbwcimp.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtoizrbvkx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtckajwbqy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gtnvdokrgv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gtwbljfssc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gtsroadire.html

TS:   [...arr];
来源：http://dali.sxryk.cn/Article/details/gtugsxduej.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvebmfbga.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cashguo.top/Article/details/gtkirlaeib.html

Ruby: arr.dup;  arr.clone
来源：http://dali.haohaochexian.top/Article/details/gtcjtdjxqn.html

C#:   new List<int>(list);
来源：http://dali.shuidangran.top/Article/details/gtciltznhh.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gtfvckqmmd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwdevopb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cqqwz.cn/Article/details/gtpboastmz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtqvukfgrq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtwtsvfmho.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gtpimilnlw.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtypdqgpqw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gtvxwtpccq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gtvxuaqreb.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gttrkrsdds.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gtgwzdydev.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gtsdkzfkmc.html


<!-- 参考信息 -->