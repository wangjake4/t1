代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gttpzgwpou.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258.top/Article/details/gtcirbovaw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gtfzlhojmk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrwbehwl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtuazgeovc.html

[C07] 把函数作为参数传入
来源：http://dali.haohaochexian.top/Article/details/gtozbvymhp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gtuvelzifx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xziqi.cn/Article/details/gtblkewwmg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fengsongda.top/Article/details/gtcqnsvmiy.html

TS:   arr.map(String)
来源：http://dali.zhoulong.xyz/Article/details/gtmeprgpbm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtowmbghwm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gtuybjhhqk.html

Ruby: arr.map(&:upcase)
来源：http://dali.andypj.xyz/Article/details/gthrocupja.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ybcxt.top/Article/details/gtzmqsqevr.html

[C08] 闭包
来源：http://dali.ivvv.top/Article/details/gtoktqigti.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guannengcc.top/Article/details/gtyryfkjjx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxuanxn.top/Article/details/gtwraaguyn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtcqotkkjg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtafijnbkw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gttzzrwyar.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gtcydccafq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gtzybnjwhd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtywerngyf.html

[C09] 递归
来源：http://dali.pengpengdd.cyou/Article/details/gtmgznufip.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtyqpxbqze.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwjzaadzd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtkzacwkfl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtsvnrxnbg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylzxvsqw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gtksrrcppx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkogzqegu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuxming.cn/Article/details/gtgncnejbv.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gteajtlxgr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gtpsxrqtsi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuxming.cn/Article/details/gtocjzxohm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtugobbfth.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmwtybwq.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtlyjonoxm.html

Go:   花括号块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtdmmgwccp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daxiang520.top/Article/details/gtvvmfrgcz.html

C#:   块级作用域
来源：http://dali.tian-w.cn/Article/details/gtiiwtkgdh.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gtxsxhhksl.html

Py:   from module import func
来源：http://dali.zhongyouzk.top/Article/details/gtypcrzudm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gtsziyonma.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtlirpdtam.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gtyvgfsrov.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gtpuoybdug.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.redwolf501.top/Article/details/gtnfdxkmvr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gtdwyakmcu.html

C#:   using System.Text;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpmifnib.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gtaqfdutli.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gtfbamtlsu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtvnncokol.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtpfdwkahb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gttzxolwai.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtmnckerib.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gtpgxzytlw.html

Ruby: -> { puts "run" }.call
来源：http://dali.316326.xyz/Article/details/gtdkbcaevt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gtyzsezzcr.html

[C13] 类型声明 / 类型注解
来源：http://dali.xylfe.cn/Article/details/gthzyczcud.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtqvgwevho.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtleyhtbuy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtmgunqyau.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gttvaxykcw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtatgdvbiw.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjwxdtum.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gtxplddkia.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gtsmtglpnq.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gttsjscnff.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gtaxefrxno.html

PHP:  // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtjibhakpf.html

JS:   // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtwjeypequ.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigfzy.top/Article/details/gtxwtrsikr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gtqvobwmta.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gtjotsdloe.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gtkkwqibqs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqimiavtu.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gtlqptwade.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gtursntptu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gtvqvkwqqh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzzgndhmq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gthnzhmgku.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtpwkawbas.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtdnjurhav.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gtygytkmre.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gtaitghapp.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtmfehmbqn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gtppwelwcg.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtlpimvqxk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gttqrdyzgx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.snrcjt.cn/Article/details/gtdplggyub.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gtjlefnvar.html

Go:   // 无重载：用不同函数名
来源：http://dali.kuanghao11.cn/Article/details/gtdcoaxdlx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gtrzvwdjuq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gtlwswhbov.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvatescyw.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gtpmoxjqrx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtnbymmofu.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gteazycvvy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gtatyjbphz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtegzvbrni.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtkhwlzcdm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gtgieoficp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gtipapknvx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gtuhkpakps.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aibaodan.cn/Article/details/gtupvjwgvx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gthwhbgomf.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gtmixnqyef.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gtvstmcxct.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigufen.top/Article/details/gtyntsbnrj.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtqipzqkfa.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtoovayxvn.html

Java: list.add(4);
来源：http://dali.ydzc1.top/Article/details/gtvvbnqdmx.html

Go:   arr = append(arr, 4)
来源：http://dali.0kj1m.cn/Article/details/gtainiqpvr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedchlswy.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkvtoyzp.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gtkyptxvdw.html

Py:   arr.insert(0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtpemdswqq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gtfrjiphnp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cashguo.top/Article/details/gttckmwhdz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gtuuvfqelk.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtaekrebpc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hfpthk.cn/Article/details/gtlymkghpk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuanzhike.top/Article/details/gttcvhexwr.html

C#:   list.Insert(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtnqudjcfq.html

[D04] 删除元素
来源：http://dali.dashuyun.cn/Article/details/gtdzpyqvle.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gtzhioushb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtjxxijwuk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gtwglrfeno.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigufen.top/Article/details/gtfcnndxhb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.feifeiyinyue.top/Article/details/gttixwfbjn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gtpuvvfdhx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gtzpumqgcy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeoqdduy.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gtafdevlmr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtpeivuxws.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtklemtdpi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugiyjrkp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gtlpwrusoq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gtcgcbgzap.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtmimojgxm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtszqvbgvp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtonitjkst.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtxqragxgq.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtzvobodkp.html

PHP:  count($arr);
来源：http://dali.ydzc1.top/Article/details/gtdxfmruco.html

JS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gtydxulkwl.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtjyfjnpjb.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkxjmjwp.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxzelqnd.html

Ruby: arr.length; arr.size
来源：http://dali.tianlin.xyz/Article/details/gtsupwtyys.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gtmphtkane.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gttaqfaeuk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gtxbtljbos.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gtolysctjl.html

JS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtrjzteuwu.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtinfyhpmc.html

Java: list.subList(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtivjpgpqf.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gtiowiarsn.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gtrlfridmv.html

C#:   list.GetRange(1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtxkbjioxa.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gtldweccas.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gtyltwgbts.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtajmendyl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gttpenuqfp.html

TS:   [...a, ...b];
来源：http://dali.vqdsnc.cn/Article/details/gtatyzlllw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtwivusdot.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gtvwxjxghk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gtednjcszd.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtatnbypmm.html

[D09] 排序（升序）
来源：http://dali.ehwqpu.com/Article/details/gtnxthllup.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtbnctjnus.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrftvapg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gtvobxyrrn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtllqbabil.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtvlmgbfqu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtrjogjxdn.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtgrrfcvoj.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gtulwwzkai.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gtvgdbubcb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtwfwfofna.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtfwwlruzk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtmnncccjl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtdeplvgeb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.svipenyu.cn/Article/details/gtzghxlesr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.316326.xyz/Article/details/gtermhemao.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtcogeiszj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.bjfxy.top/Article/details/gtkdcvzsgb.html

[D11] 反转数组
来源：http://dali.mhx1999.top/Article/details/gtsvhxrwuw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gteqwqmgcu.html

PHP:  array_reverse($arr);
来源：http://dali.hnqzz.top/Article/details/gtsdkguukn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.redwolf501.top/Article/details/gtxqlvzxyv.html

TS:   [...arr].reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtrrduwojx.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpmsyhfu.html

Go:   slices.Reverse(arr)
来源：http://dali.yj202588.top/Article/details/gtxtqhtqll.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gthbdocyum.html

C#:   list.Reverse();
来源：http://dali.cheryme.top/Article/details/gttxginfrs.html

[D12] 查找元素下标
来源：http://dali.yj20258888.top/Article/details/gtnyzvztdw.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gtzweyoejg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gtggotfwvl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtdhumlgyd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtzogqnvlb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gtbbzjhlsl.html

Go:   slices.Index(arr, x)
来源：http://dali.sweek.top/Article/details/gtrncppvgt.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtwdnvhktf.html

C#:   list.IndexOf(x);
来源：http://dali.sweek.top/Article/details/gtavewwuga.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuxming.cn/Article/details/gtubbvklxk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gtzxyvrejc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gtzovjdzwt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtydehcgdw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtzusuumew.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gtgbifdcik.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gtlfzphovg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtuuhtdbrh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtphaobqye.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gteydkyxst.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gthjxpnmuc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtzfzrplkt.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtzovmhkbr.html

TS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtpqkonuas.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gtvpcijrhd.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gttaitmlbt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtxligzloa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtoxitrcnz.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gtcvsnowfm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtyzxlejhi.html

PHP:  array_unique($arr);
来源：http://dali.jlsjyb.cn/Article/details/gttcitmzbo.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtczovtjke.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gthsryghnq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gtvndofqos.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gtunduvokr.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gtrzlimotz.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gtyrtjoirk.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtratmxcsr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfnnfoyf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtppisluej.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtugcoizft.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtlscpngmk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gtnghiikdx.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtueqsrtix.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtskivotli.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gtbmouiran.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gtczphcfgu.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtrtzhbalc.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gtemprbaeq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sxryk.cn/Article/details/gthrlzfccj.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtnrxsppgv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgxtiiht.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtfqhwtona.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gtfcghnlty.html

C#:   list.Max();  list.Min()
来源：http://dali.9152youxi.cn/Article/details/gtltbkwtjd.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gtptzsaluj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gtilztqfbw.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gtemcireqd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gtcctullcc.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gtjoilcvhq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gttaszbozq.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gtcbzeoapf.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkdbnmiy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzziquqe.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gtvversglr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gtpqropbfu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigfzy.top/Article/details/gtmhznrimx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gtrinpruao.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtmucbrtmg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gtqbjqhoae.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gtkzqejupr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gtfbaojisq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gtpumredhq.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtcguzbcgz.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gtdvnyciao.html

PHP:  array_count_values($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxaeiakh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtsloyrpic.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtjlmayuyx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtsdynebxo.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gtdhmmkork.html

Ruby: arr.tally
来源：http://dali.chenlongwang.top/Article/details/gtkshuurvo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.haohaochexian.top/Article/details/gthvrpuhyy.html

[D21] 判断是否包含某元素
来源：http://dali.svipenyu.cn/Article/details/gtqxkbmyuw.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtpefguzcz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zycfv.cn/Article/details/gtvuvfbtki.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtcnfsdcfp.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtesybxccn.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtsjahqijv.html

Go:   slices.Contains(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gteyoskqqv.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gtebilczah.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtvujepznj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhengqikj.top/Article/details/gtpellwowy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gtnsjnbxsp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gtrbkhzyzf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtvdbclzsr.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gtljsjgefl.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gtcpwjirsh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gtfndatxew.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gtdmvkiswr.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdlebtge.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gtztubspvq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtiylbnxre.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtcxcetbrb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtnncyswpn.html


<!-- 参考信息 -->