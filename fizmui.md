代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gtpcifpskp.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gtpmeqpobr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gtgsgoehgp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gthurrgljv.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gthekjzqqj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtegffwxko.html

[C08] 闭包
来源：http://dali.pycfn.com/Article/details/gtnuubehpl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnefoyxy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkgzmqvq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gthhdrytrv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtkpvmpelr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gtufcbgrbo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gtubsawllz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tanke756.top/Article/details/gthimtlmbb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtatkeszxk.html

[C09] 递归
来源：http://dali.nanxinkj.top/Article/details/gtqamsjlts.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtpecrssoc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hammf.cn/Article/details/gtebnyketb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtdwbufkog.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtzpdesapm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtuswghvzs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.birdmap.top/Article/details/gtundlzixa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtorntroev.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guannengcc.top/Article/details/gtmlqmovwl.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gtqmozslzg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhiwuduotai.top/Article/details/gthwlqvixd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhengqikj.top/Article/details/gtmxmsmrrk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gtmrmekiel.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtscbgbapf.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gttccujvhb.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gtucgbwrld.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangdashe.top/Article/details/gtezplzpcu.html

C#:   块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtqvqbsqpb.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gtrqioyqka.html

Py:   from module import func
来源：http://dali.yongpay.top/Article/details/gtuxprwxoo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gtivputumx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gtkkilsrzg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gtomhvvybi.html

Java: import java.util.List;
来源：http://dali.chenjidiqi.icu/Article/details/gtpocewwkg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gtpoifcdmo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gtrprhzxnb.html

C#:   using System.Text;
来源：http://dali.chenlongwang.top/Article/details/gtuvmvfbbp.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gtpmecgohr.html

Py:   (lambda: print("run"))()
来源：http://dali.vqdsnc.cn/Article/details/gtuweehwct.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gthjqilsqa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtfzztxqxb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtmafwfvdu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxinkj.top/Article/details/gtngtebqsb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gtfnazakvt.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gtcoeyxlgc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gtqggpwidt.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gttimgnfqs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gtoyknzvlx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtnmoncnpt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.quarkkingdee.top/Article/details/gtsxhjkrux.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtjdtirkbr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtjtatwgjq.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gtvwjeabks.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gtudpijzbd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ivvv.top/Article/details/gttjkrartz.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtjdetpijc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gtmagvisql.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtykafcslr.html

JS:   // 无泛型
来源：http://dali.xinyue.icu/Article/details/gtmsprdyhs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gthikybjan.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gtcbebdngn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtudjxqpfr.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gtizggpjnf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gtxwlticgy.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gtahmfqczl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gtmvjlirya.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtnhdpwpvj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtjxuikcbg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gtdyyxrukv.html

Java: // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtlimzqguz.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtircwvbiu.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gtwzdwffno.html

C#:   var (a, b) = pair;
来源：http://dali.tanke756.top/Article/details/gtuvtgddht.html

[C16] 函数 / 方法重载
来源：http://dali.birdmap.top/Article/details/gtpopsihdz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gtmuzcjpya.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gtlsclpwcy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gtiweozguf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gtuimibzvi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtmktoahrv.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcditfrb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.havefunace.top/Article/details/gtzmzpbklo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxhhmyuxk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjwyjsmrw.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomuiciay.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxkawnwtw.html

[D01] 创建数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtyjztvord.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvevfnek.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtmrfhdtvi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nwbrower.top/Article/details/gtcikwmvcb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gtpdlgfvix.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aizwys.cn/Article/details/gtafoopedj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tanke756.top/Article/details/gtsspxxqwz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.bjfxy.top/Article/details/gtiqbfmpvr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gtkioyxhbb.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gtqnimxygr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gtkklhxmqi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtspjyqzqp.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtkdpftzqi.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtxirioyhd.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gtetqzmiuk.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gtwhlabcmn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gtnfzujllw.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcrzhnwx.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258.top/Article/details/gtbkiflgrz.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gtytcjuceh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gtolgzlcij.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gtalkoznja.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.havefunace.top/Article/details/gtoqlxaykm.html

Java: list.add(0, 0);
来源：http://dali.sysykeji.top/Article/details/gtqwtzbhoj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtbymmhyci.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtjzzfowmv.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtoxrzrzlv.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtpgeqhldq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jiagoushi.top/Article/details/gtgsrfgcyk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jyoumei.cn/Article/details/gtcdzlqdyl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gtsjyyvsvl.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtqzxhkoxe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtcfiulvjq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gtyvhpplpc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jiagoushi.top/Article/details/gtcoqmqskp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gttkbdzmdy.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gtollwmcie.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtgevmqwmb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtqhjugjvu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtajrnziex.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangshuangyany.cn/Article/details/gtzejigcsd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxinkj.top/Article/details/gtsohxxxgz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtdusuvqfj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtizlppbaj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtpumcoprh.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtfhrxofho.html

Py:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtxhlaioto.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtyramvfhd.html

JS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gtgvkfcbdf.html

TS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtzrzzvbsc.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gtsgxcuwdj.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuqrigee.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gteetymwyg.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsuwlqam.html

[D07] 切片 / 取子数组
来源：http://dali.shzxlz.cn/Article/details/gtuguaqgyn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.quarkkingdee.top/Article/details/gtzifxrhmw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gthgbpcaao.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtwuegbvog.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtqnnihfdc.html

Java: list.subList(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtosxgqljb.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gtgqjmylor.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gtxuziomkw.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gtzbveotqv.html

[D08] 合并两个数组
来源：http://dali.aizwys.cn/Article/details/gtpmtssyxd.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gtwgnfvwsk.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtqeujasvf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gtlguvevcf.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gtfeccouhg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtyktikuxv.html

Go:   append(a, b...)
来源：http://dali.xylfe.cn/Article/details/gtmfsanhfu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gtexhfcmit.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtkxjuydbu.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gtyfragiwx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtpaatahud.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gtiyvvybdj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gtphqgjcof.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yonumen.top/Article/details/gtemndwtwz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ivvv.top/Article/details/gtfvyjxbfm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtmywxajyn.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtqzsyrpag.html

C#:   list.Sort();
来源：http://dali.zhixingplan.top/Article/details/gtwylnfghj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sxryk.cn/Article/details/gtjsstrmfx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aizwys.cn/Article/details/gtnrbpbnoe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtegqyfmnp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtkgjnqxfi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtfjuqgyrj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tanke756.top/Article/details/gtwurjpowz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gtvxzjitsa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jyoumei.cn/Article/details/gtgjikobgk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuanzhike.top/Article/details/gtnxprzruc.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtkadqjzmi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gtymwseyrk.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gtzrkjvksb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtdpvtteyf.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtcsyhivcj.html

Java: Collections.reverse(list);
来源：http://dali.hywenlv.cn/Article/details/gtzslxuljv.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtknprzvww.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gteuufhcam.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gtvneidmww.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfldkwik.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gtmxaumfjg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtbicvzvtv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtyxxnkycr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtauzmdjzm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gtaaclilip.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtrnnacvvd.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gtqnccqnfi.html

C#:   list.IndexOf(x);
来源：http://dali.c1oappe.top/Article/details/gtjljlmuax.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hongshengwenyu.top/Article/details/gttiuevpyt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslyoncfu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gtkdhpjqqj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtxwiwqmww.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gttxerjcmq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtfosqlhkp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtxpgipiih.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ivvv.top/Article/details/gttcpkhsyq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gtwzpegimy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gtlgyetexw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gtkcpwmvsm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtcsedloeq.html

JS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gtrxnxkshc.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtnpjled.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuccdbvdh.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtzsipobfa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtgshxfixn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtskopndls.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gtuicajxfh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtjdgnqzge.html

PHP:  array_unique($arr);
来源：http://dali.svipenyu.cn/Article/details/gtetzmgzhl.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtpvbcrfex.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtztoxnapa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gttgkjdzfw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gtloowhavs.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gtrqmzcdlv.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gtcynpkfdl.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtoxriydar.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtgobkvidx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gtcdroqozl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtyxdupmno.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtqtwqdpjf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sxryk.cn/Article/details/gtddoaxciz.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gtwmmwwbba.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gtgiwqsqvz.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gthdewhyqy.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gtisfxtvsw.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtjvayigex.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gtmlwehbmo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gtjebbqrff.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gtkxefjoqv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gtbyrlwaum.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtxutfsfpn.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gtbzpxqrmd.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gttuvheckg.html

[D18] 扁平化嵌套数组
来源：http://dali.redwolf501.top/Article/details/gtomtjlpce.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.svipenyu.cn/Article/details/gttjwljoja.html

PHP:  array_merge(...$nested);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjrondxt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gtvfgfhbnp.html

TS:   nested.flat();
来源：http://dali.shuidangran.top/Article/details/gtdrciuald.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtlhnwmdct.html

Go:   // 手写双层循环
来源：http://dali.zhixingplan.top/Article/details/gtiqukvvnt.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gtneizivrk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtlmxkasht.html

[D19] 按字段分组
来源：http://dali.zdqjudy.top/Article/details/gtygkemkpr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gtspyeogei.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.0kj1m.cn/Article/details/gtafbbwkat.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dianchejie.cn/Article/details/gtxzychqml.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gtbjgfzrbx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gtvayiwvkv.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtnnmfhtpt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtgizpqdkh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hammf.cn/Article/details/gtcnikelmt.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gtegfmpwgw.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gthtnrjywl.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtegskuqrz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtkfajafjg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtsxqsehnm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gthncxxbhr.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gtrudpniao.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gtuogjzwxf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gtucfuiniu.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gtaoautxmm.html

Py:   x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtholfmibn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gtiyfcthqi.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtkgcoacpk.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtubixxqza.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtkmnipytq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtiitxbftt.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnjvyglg.html

C#:   list.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtsrlxmnbz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuanzhike.top/Article/details/gtxljhosib.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtjgflaobd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gtdmzpzwut.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtkaupfklr.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtfvzmfuyd.html

Java: new ArrayList<>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtuvswonrh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hfpthk.cn/Article/details/gttjdniiya.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gtxdmfgxbh.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gtgflnaomv.html

[D23] reduce 累积计算
来源：http://dali.hfpthk.cn/Article/details/gtwbfbmmrs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gttzbwqngk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gtoiehogkz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtgbynjaoo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gtzptvttcv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gtpnbtsnpx.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtwlsjhgdb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gtzeoaupxq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtzayfjojt.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gtciziuocq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gtehjbdekw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gtmdjhmuqe.html


<!-- 参考信息 -->