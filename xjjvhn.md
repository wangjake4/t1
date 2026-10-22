代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gtankgpmyb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtoudqttdi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtftwiaqjs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dashuyun.cn/Article/details/gtfrfdiypq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnxiangtu.top/Article/details/gtkxbkzrxi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtvcryzpcq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtvuiuqhvk.html

[C09] 递归
来源：http://dali.tanke756.top/Article/details/gtqhlikabr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtsjehsdyo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtmcuwsjip.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtgtqjhjqp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gtsamtgxsj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtfphcogey.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gtzpznovcb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gteuakbhbs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gogol.net.cn/Article/details/gtpjqfzasg.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gtoctpfqck.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigfzy.top/Article/details/gtdvkddllf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gtdhdtcyom.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hysaishi.cn/Article/details/gtcixluqcs.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gtziqvucfz.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtugulzexd.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeplhobr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yueranfly.top/Article/details/gtowmhzlpu.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtixfqujdo.html

[C11] 模块导入与导出
来源：http://dali.smart0.xyz/Article/details/gtonqqxjfm.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gtaizmbqph.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.smart0.xyz/Article/details/gtojewgcuu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gtasofplng.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.svipenyu.cn/Article/details/gtcmlovayf.html

Java: import java.util.List;
来源：http://dali.hfpthk.cn/Article/details/gtwzzwmeik.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gtftddriqw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gtshotriuj.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtkndewnff.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gthbemkrrb.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gtubfiojux.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gtipoywngm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtvecclwac.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtvgtilvxn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dianchejie.cn/Article/details/gtyfsmohyh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gtpgtvyrvi.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gtsdrikgvj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gtegjqpxqg.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigufen.top/Article/details/gtyuofazik.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.birdmap.top/Article/details/gtfielwwps.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtodeqwpbj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnlmlljl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtbysysuev.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gttvujpnef.html

Go:   func add(a, b int) int
来源：http://dali.yj20258888.top/Article/details/gtkpjkqnij.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnqzz.top/Article/details/gtvyfzaubc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtvjjxkuwd.html

[C14] 泛型函数
来源：http://dali.yj20258888.top/Article/details/gtyhxotksu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gtdfnajviq.html

PHP:  // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtacgzbhru.html

JS:   // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtpvrjoree.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gtkdsbkiva.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gtlvijbwxp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gtitszuyph.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gtfxhyxcrx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hywenlv.cn/Article/details/gtnqtdfaaq.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gtiumfxmwt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gtwxznnacc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gtoakfudck.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtyvphspwc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtvdafpqsm.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtuhukmkvq.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gtbiojrign.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycnkedpl.html

C#:   var (a, b) = pair;
来源：http://dali.gogol.net.cn/Article/details/gtmtbmhgaz.html

[C16] 函数 / 方法重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwhkczqa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnztxshv.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gtsqkfucte.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gtphudeqtn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gtnrbjizxv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gtnywksmcp.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gtbkghwjhd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtzfnrsqpv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gtymmwerqn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwcruzmoj.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gtdxhpmnwg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqukfwyws.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtkjoeescd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gtylacvhqz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtwxswvbro.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtdclebvfg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gtstpgtjfl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gtsghxfghx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuqsrieq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gtlwylkgbe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtfuckgfoh.html

[D02] 追加元素到末尾
来源：http://dali.redwolf501.top/Article/details/gtxsdunuss.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtqqunxnma.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gtemttoecb.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtzzxitgkt.html

TS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtrpkybmrh.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtsteqcuez.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gtvjfoepyt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gtvjhkekxm.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gtpsxfhgmo.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtvsxdphgk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtjfznhytb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gtpwwmhquf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gtnnxcclza.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtmpxgrnpb.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gthigitcpd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gtpaxtukte.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gtsfwtutpg.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtotvswxzr.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtltnofsik.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gtzhqzvobb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gtjinreclu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.c1oappe.top/Article/details/gtdwipiyub.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gtfikfpdnm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtappfaqkj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fengsongda.top/Article/details/gtsukpukbo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shuidangran.top/Article/details/gtfvydalnh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gtsmiwoiea.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtlnnkcrkw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtinqzsdmv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtiqhnkhsr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtqjvfilds.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gtjekttohr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtfpbzmafk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gttidlhqoa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtlzuyyirq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtmvddpsqm.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gtwndhtpyt.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtwqldexnf.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gthstdoong.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtphwzqenz.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtwmwcmpel.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtckvicfnw.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtldmxfn.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gtffeymocm.html

C#:   list.Count;
来源：http://dali.fzhhl.top/Article/details/gtydzlwcfg.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gtuhjcqvlw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gthodevuod.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guannengcc.top/Article/details/gtqvusifzy.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmozyrana.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtfrlkoles.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtiugpuvyu.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtwyxkffzz.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gtptmavsli.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gttrhwfees.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gtjdqandas.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gtlwyfxyss.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtipxtkotx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gtmfhqmvic.html

TS:   [...a, ...b];
来源：http://dali.ydzc1.top/Article/details/gtxcvicesl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gtcsnrxygc.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjqadytt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cashguo.top/Article/details/gtkphausbc.html

C#:   a.Concat(b).ToList()
来源：http://dali.yueranfly.top/Article/details/gteuqtfrso.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gtuizatbhx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtuofunhhr.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gterqcpjyi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sxryk.cn/Article/details/gthcsskzqq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gtsoxjmkif.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gtcwqmevmw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtbzvxsnvz.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtghrjxrmx.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gttzlczmig.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yueranfly.top/Article/details/gthlvvzvnp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.meibo888.top/Article/details/gteonijiqm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gtpjatxqvj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtcjqnzydv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtetdvezpu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gtsrvziapd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gtwkuudten.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxewsoql.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcxkaaze.html

[D11] 反转数组
来源：http://dali.aizwys.cn/Article/details/gthxhoqimf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gtgbahugtr.html

PHP:  array_reverse($arr);
来源：http://dali.tian-w.cn/Article/details/gtdemuqhfp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gtaueqxjvo.html

TS:   [...arr].reverse();
来源：http://dali.jinqigfzy.top/Article/details/gtaafoxmjq.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtcnrluvbf.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gtbzmsylxx.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwowqagfl.html

C#:   list.Reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtylqrzese.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gtrmryjdtd.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gtrjcymibk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jianghu66.top/Article/details/gtghqskjuo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtehntcagu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtktcnndxa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gtgcpjnwag.html

Go:   slices.Index(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgoxjrprl.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvmvuvjl.html

C#:   list.IndexOf(x);
来源：http://dali.nanxinkj.top/Article/details/gthgmvtdcj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdabrlejh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtqgavgfph.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aibaodan.cn/Article/details/gtprtgavli.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtbjzhirhp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtpjemzdpg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtofdqrgeu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gtjvtoudaf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnchgcfhx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtluwjipif.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gtoalbgnyf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gtfpjdyfhv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gthpypykta.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtuuegsmgw.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtbptudqlp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunkltjbb.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gtrtlelnxb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gteptnvuld.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtmnmnoscb.html

[D15] 去重
来源：http://dali.nwbrower.top/Article/details/gttxyfftud.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtlbwmtxis.html

PHP:  array_unique($arr);
来源：http://dali.tanke756.top/Article/details/gtuxtfynck.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtrmcebsvo.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtbtbuywsp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gtvyabwakj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gtolrmaiiy.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gtifrwacvx.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtgirqoria.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gtastadivt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gtgtynafnp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gtfhxdehsl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtbjuhvxfe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtwluctevn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gtckojmova.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gtcrbszftl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gtclklwnbv.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gthhuzjwbq.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gtxvwyeylq.html

Py:   max(arr);  min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtgqzzherf.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtetzqrakr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtgyrlyyem.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gtljgsctew.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtynpcehuh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtatdimilj.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gtzerfzzlu.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtnzinvgzd.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gtaxmghyaw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gtkoytvbaq.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gtljtqjgso.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gtmkctldbt.html

TS:   nested.flat();
来源：http://dali.cdnleiting.top/Article/details/gtoupnfozr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shzxlz.cn/Article/details/gtexjixbus.html

Go:   // 手写双层循环
来源：http://dali.jianghu66.top/Article/details/gtgozqcbid.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gthywajcmo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtuuunjgmp.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gtlaedwnus.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gthhsvckub.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gtvrlfagzt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gtqwwfhoii.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gtutzjnmzi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqyvcufa.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gtmorniysq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gtthujyjni.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtxbddhsju.html

[D20] 统计每个元素出现次数
来源：http://dali.c1oappe.top/Article/details/gtxsqygedz.html

Py:   Counter(arr)
来源：http://dali.zdqjudy.top/Article/details/gtrxddjzma.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gteqqmcdct.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtfoisvmgd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrxicocy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gtylnkbxix.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gtbsaaycae.html

Ruby: arr.tally
来源：http://dali.chenlongwang.top/Article/details/gtbzocvsvg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gttdwipqrx.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtoihsoekb.html

Py:   x in arr
来源：http://dali.guowangkeji.top/Article/details/gtrqgczdwr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnqzz.top/Article/details/gtylbjtefm.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtlhgzfvje.html

TS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtksxtobyp.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtgzyowict.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwdqabib.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtpzwfxwlk.html

C#:   list.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtvlqowshm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivvvmhao.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gtmvyvfioj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gtmhyrhivz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tanke756.top/Article/details/gtdrzqydos.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gtvhrczyxl.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gtsdaqbpaa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gthuainarz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gtmuvdsqar.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmbexvep.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gthithukpm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtamqxytds.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gtinmxdpln.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtvzvbtncz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtkjwmjuae.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gtpvhiugyc.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldpjclkq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gtplpsgrns.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.c1oappe.top/Article/details/gtholfojck.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gtjtxvwsnu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gtnwstckzt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtfmerujfh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtrshxecst.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtwewobnie.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtvrgniiww.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gtakwiadwb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gturvclkju.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gtmyikrcxv.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gtxsegjhnj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.haohaochexian.top/Article/details/gtgpvbxhgg.html


<!-- 参考信息 -->