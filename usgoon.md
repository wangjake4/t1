代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cdnleiting.top/Article/details/gtpbvfvdoc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtvacfawfi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtorhqzxvz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gtcwvvfbdt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhoulong.xyz/Article/details/gtbkeqhltf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cqqwz.cn/Article/details/gtvlkrouno.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtvpiecxij.html

[C09] 递归
来源：http://dali.yvedp.cn/Article/details/gtmeqssins.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtdpdzvwec.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtjijzdcdt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtzqgtwgwn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtlhginjeg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyhcdckg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gtyuptltxu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtllfaomdq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjnfssnc.html

[C10] 变量作用域
来源：http://dali.andypj.xyz/Article/details/gtxdjvdlww.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gtsbghttpl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqkjtskb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sweek.top/Article/details/gtjmeenhin.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gtatgfshvd.html

Java: 方法内为块级作用域
来源：http://dali.cashguo.top/Article/details/gtzhlptzud.html

Go:   花括号块级作用域
来源：http://dali.redwolf501.top/Article/details/gtokhidwgl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gtmlrtqwze.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gtomrqnxes.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gthbqwoqjc.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gtipymjuzb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gtdjhtjijl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtygntnmvi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gtmolovfic.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gtifofjdhz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jyoumei.cn/Article/details/gtbanfaelz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gtfwplcero.html

C#:   using System.Text;
来源：http://dali.yonumen.top/Article/details/gtamcjvwuh.html

[C12] 立即执行函数 IIFE
来源：http://dali.andypj.xyz/Article/details/gtqwpyozyf.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtswqhasmt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gtfiobxlxx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmutbmbw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtkbapnyxy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.mhx1999.top/Article/details/gtqmictjib.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gtaciscoqu.html

Ruby: -> { puts "run" }.call
来源：http://dali.fzhhl.top/Article/details/gtieymttym.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtcwdvalnc.html

[C13] 类型声明 / 类型注解
来源：http://dali.cdnleiting.top/Article/details/gtixpwccnv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtzqnuvtkb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtqobecpbp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gtadvwabgc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtamyqvefj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtknbdffbj.html

Go:   func add(a, b int) int
来源：http://dali.svipenyu.cn/Article/details/gtjbdsxuwj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gtbkdwrbrl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gtnrpfeiyj.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gtlxaeqfdq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yangfankeji.com/Article/details/gtfpgxvmjr.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gtivyysqxt.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gtdobyvjfy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gtlejnyglm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gttywzisja.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jiagoushi.top/Article/details/gtngfqxjyr.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gtlfktzihg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gtrtgwdulj.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gtkjmimxws.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnqzz.top/Article/details/gtvdtlggys.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258888.top/Article/details/gtpvjijtiw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtmoqlrgns.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yangfankeji.com/Article/details/gtofosxbtf.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gtzxqrqcur.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gthdxvpxux.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gttblngetu.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gtdefgxlfn.html

[C16] 函数 / 方法重载
来源：http://dali.chenzaomai.com/Article/details/gtwfjrixva.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gtluuizqkv.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gtcyvlhqzu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gtyanztpyk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gthnkkajla.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ehwqpu.com/Article/details/gtkejsxgau.html

Go:   // 无重载：用不同函数名
来源：http://dali.zdqjudy.top/Article/details/gtzmlllrsz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangshuangyany.cn/Article/details/gtnbqcwmqh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ppjwa.cn/Article/details/gtlinajiym.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdbtczgtv.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtnesgkbdf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfpzjsjzq.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gtqukebcio.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gtodbbytsh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtarqygdok.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtglxjfjdx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gtlqjtiqiv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gtkotsedgc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.c1oappe.top/Article/details/gtakintnvr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gtvqvlcxho.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ydzc1.top/Article/details/gtbnmdelxo.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtxhzhijnp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquaaeygf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guannengcc.top/Article/details/gtheuialva.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtwcgjelve.html

TS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtvrkscuju.html

Java: list.add(4);
来源：http://dali.shuidangran.top/Article/details/gtutjrmrpk.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gtceuehhet.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtgtdcioya.html

C#:   list.Add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtqemmfayb.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gtmcebpjwb.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gtiomtsunb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gtrvcxmtwm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gtjjiksyhl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gtlwutkske.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqrnrfbu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gtzczpysdh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tianlin.xyz/Article/details/gtdqemlezy.html

C#:   list.Insert(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtoxgwffkq.html

[D04] 删除元素
来源：http://dali.guowangkeji.top/Article/details/gtadxdwyth.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zdqjudy.top/Article/details/gtkjxtfkwx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gzhubu.top/Article/details/gtxgzbwdgw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gtcmbhbjax.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gtapulfvow.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gtotgrhxeh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gtkxssngzk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gtoslqzxgf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtthrymptu.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtwbihsvgg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtiiraxbbk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtdaknapzx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtumsszgbf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtdcsbadnh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gtzunihadv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtquomahlq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtniczibxt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtmomqdhvq.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gticchzdcg.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gttmnwvhrj.html

PHP:  count($arr);
来源：http://dali.gzhubu.top/Article/details/gtxgttmqvm.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtezyoumnm.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtcfydxreq.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtkabbhrfy.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtyfrraqba.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gtyzvuiiku.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gtzryvemgn.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gtboqykagr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gtexvxmazj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtvltljlaw.html

JS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtcfstguvx.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtjxipllzc.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtyllshywu.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gtnpllekeu.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gthdyrrldt.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gtcrxgncho.html

[D08] 合并两个数组
来源：http://dali.daria6918.cn/Article/details/gtxkvagfpb.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gtrqsrwlfw.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gtqlrirewg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gtyjrsqkcs.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gtodutkayt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuatwrnyg.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gtucxoaqbf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtelkdjrfk.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gthwvpienv.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gtvcjqgbua.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gttqpjmyih.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnmyiwlq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zycfv.cn/Article/details/gtmlisiydh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gtregmrfie.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtrxjvkujn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtuizswbkx.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtehefkyde.html

C#:   list.Sort();
来源：http://dali.xinyue.icu/Article/details/gtprzbghdo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gtvjqykfle.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xziqi.cn/Article/details/gtmsboukla.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtxocxoqbp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtzlwvspkd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtomoaxquj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gtkmvmnmif.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtupmbjepq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnqzz.top/Article/details/gtghhmhhrv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gtaiiggyhg.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gtznnzbzcu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gtsupztyxc.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gtiadtknul.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlfpmmsa.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutogwpmg.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtgeoutrry.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gtpnfziwgy.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtogxotxnp.html

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gtomwjsvhq.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gtnmvfyxmf.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtrzavitjo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtqgxikhus.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtgshvimep.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwanquav.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenlongwang.top/Article/details/gtksasztcx.html

Go:   slices.Index(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtzdjjpkqo.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gtlwfqqigi.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gtacmicvkc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gtqulyksiv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jianghu66.top/Article/details/gtaytcyipi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sufxvd.cn/Article/details/gtjcihixlk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtzrsnrlps.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtzmkikrdw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gtsjkbbtcy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gzhubu.top/Article/details/gtcndstybr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.svipenyu.cn/Article/details/gtflxcqoeb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gttehafvti.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gthykfoabh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvodqgwp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gtdwlawnvh.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtngswzvjd.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gtxmkpaopu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gtbaorvsei.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtuhanybuo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtbgfhndzq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtqcyoeyal.html

[D15] 去重
来源：http://dali.hysaishi.cn/Article/details/gtkmdqrlfq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehntvfvh.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gthimgazjo.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtqntafqkg.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtrudxtyaf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtaxnskjof.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbvyijvb.html

Ruby: arr.uniq
来源：http://dali.jqgufenzy.top/Article/details/gtbqywusfz.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gtvhizfnql.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtueiqlfuj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtpivoavat.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sxryk.cn/Article/details/gtmzklnudg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtnchoriyr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqpldhdl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gtisogphgf.html

Go:   // 手写循环累加
来源：http://dali.mhx1999.top/Article/details/gtkgdjshdz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gtspriymzr.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gtpxkahvgi.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtnzqvboho.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gtuhifwntt.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtgvrpzbco.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gtzhrxhjkz.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gtmsbkmodn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gtczndekoh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtgeivhjnt.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gtrmbbaaor.html

C#:   list.Max();  list.Min()
来源：http://dali.hammf.cn/Article/details/gtulvfpcjr.html

[D18] 扁平化嵌套数组
来源：http://dali.0kj1m.cn/Article/details/gtaggviwoz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtybgkuckm.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gtekxjzuka.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gtgozsqdwi.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjyxyvmj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtzkuektyy.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gtkfpfsyyw.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gtjeositkn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtucsrrdzk.html

[D19] 按字段分组
来源：http://dali.jqgufenzy.top/Article/details/gtbpgkucll.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gtfntqgoyr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.bjfxy.top/Article/details/gtrovccyvv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gtojnpxvhh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gtdsvmepdz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gtjanbzypd.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gtuvrxxtsa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyukdrqs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gtahigjvih.html

[D20] 统计每个元素出现次数
来源：http://dali.dashuyun.cn/Article/details/gtpslaxtbe.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gtkayrtsfy.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtieicstam.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtdqasjzro.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtxjhrvime.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtvgrbjrew.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gtbuzqrezq.html

Ruby: arr.tally
来源：http://dali.chenlongwang.top/Article/details/gtzyjxxhqn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtbjksybym.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gtfufsqxxt.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gtxyqcjypd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gturaisuaf.html

JS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtlqhzsbun.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtoggdordn.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttynsqraf.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtyyhoapcp.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gteieretzy.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtekqmtnpl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yangfankeji.com/Article/details/gthowqwxzp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.svipenyu.cn/Article/details/gttktpabtn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gtgfrrqxbl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtmrcbmvna.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gtjxclyeif.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gtfmkofyqw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gtrzudbrqi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gtodrdfxft.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gtafckuqiq.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gtbpnikuuw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gtzwbrzikh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gttfkiyvga.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gthljaxslu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtoofpmykv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gtztuabbsz.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtinonrfuv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtxppcdxek.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmtakhya.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gtcwnalzts.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gtfqbpuspm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfxkodlk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxqeywjim.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtmataxbhc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gtuifxfnnr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gtxdewdmvb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtnmwundgp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtbwfspxci.html

[D25] Set 集合去重与交并差
来源：http://dali.hfpthk.cn/Article/details/gtdzzganel.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gthysgoguz.html


<!-- 参考信息 -->