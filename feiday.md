代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenjidiqi.icu/Article/details/gtcnklrncj.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gtsakslhrr.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtyoaxviqg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgufenzy.top/Article/details/gtdiwjocsw.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtzihtffsy.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtzkyvoxjj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gtatfyesad.html

JS:   const square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtcucgbewo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtiudwverq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nwbrower.top/Article/details/gtkgvxmjik.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtnauonyjy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtquzgjtpb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtkzrntyrn.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gtmvqpvopc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gtbmjzkouq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258888.top/Article/details/gtrrrbdjea.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gtqofjkjrw.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gthjjbusvs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.redwolf501.top/Article/details/gtkzzhmlns.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jyoumei.cn/Article/details/gtjnukftpu.html

Ruby: arr.map(&:upcase)
来源：http://dali.xinyue.icu/Article/details/gtodaapfwz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhiwuduotai.top/Article/details/gtwihqrxde.html

[C08] 闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtodmobrkq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gtxwnpzydv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gtsloxncxz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtetdqbxiu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtjjorhlmt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.c1oappe.top/Article/details/gtubvexmxo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cucudq.cn/Article/details/gthympnndm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gtfetztsdm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtdpbpqche.html

[C09] 递归
来源：http://dali.xziqi.cn/Article/details/gtozgyttlc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtughrmgtu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gthgvgzsig.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtqjdptlty.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtfbjtdbng.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgzqlfhjf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gtbhomzkdl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtbtjwziip.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gtjvdxgwnd.html

[C10] 变量作用域
来源：http://dali.dashuyun.cn/Article/details/gtjlfyhdek.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangshuangyany.cn/Article/details/gtgvdfdqib.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gtxvtzjhkl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtzvizlmmt.html

TS:   同 JS
来源：http://dali.ydzc1.top/Article/details/gtlxscqmdz.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtitmluiab.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtubfiadzd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gtdlbfwopa.html

C#:   块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtwyjgtynd.html

[C11] 模块导入与导出
来源：http://dali.wangshuangyany.cn/Article/details/gtogszorrp.html

Py:   from module import func
来源：http://dali.fengsongda.top/Article/details/gtrpmxlres.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tian-w.cn/Article/details/gtzcyfanox.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ivvv.top/Article/details/gtganmlxql.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gtetbdmhay.html

Java: import java.util.List;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvomccer.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gtfcomdtxx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guowangkeji.top/Article/details/gtcifypbir.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtjwqoagmr.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gtlissxtdd.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gtpdbydkft.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gtaakqwfdp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gttvqapxwa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtlpbitwnb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shuidangran.top/Article/details/gtchooeqyi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtoabfbcuo.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gtrseqmzpb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.bjfxy.top/Article/details/gtbnuzlkit.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gtlmrepdbd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.haohaochexian.top/Article/details/gthiekhjkh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gttlbuydvc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gtjxvghhnm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gttobosvnn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcmkkwdq.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gtbiapepcj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gttfzbxqaq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtumfuohtk.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gtymcjomkz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gtrgsptwbo.html

PHP:  // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtiuwmpybm.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtyjnqybwf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gtpmrpjtdb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gtujscpooy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gtqthgwbjp.html

Ruby: # 无泛型
来源：http://dali.cheryme.top/Article/details/gtzjrwadgl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gtwrhjednc.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gtpjskohtm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenjidiqi.icu/Article/details/gtfqiwxpoc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gtvkcytrnn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtssiittzc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gtauhjmsjw.html

Java: // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtqmcggwmy.html

Go:   // 无解构
来源：http://dali.nwbrower.top/Article/details/gtvjxdclhv.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gtsdzhbixc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gtbtbtuuus.html

[C16] 函数 / 方法重载
来源：http://dali.gotoacloud.top/Article/details/gtynuawnrc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gtncrlgvht.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtstixnivq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xziqi.cn/Article/details/gtcxswpyog.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gttbgwuihf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ybcxt.top/Article/details/gtphvmqgez.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtcxamszux.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gtaxhsnfzf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gteelfujyv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtqciteblp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtbqqpwsch.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzphyuxyr.html

[D01] 创建数组 / 列表
来源：http://dali.pycfn.com/Article/details/gtvwprdoso.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gtquccxjao.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daxiang520.top/Article/details/gtoeckvplz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gtvghkcgoz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gtyftjpvxe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gtlgvxrfco.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gtqzpwawvz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shzxlz.cn/Article/details/gtgxytrhir.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gtwgmfbboc.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtpdnosiyo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.smart0.xyz/Article/details/gtdponqjgk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gtseejutew.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtjublvjfv.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtuzxvmuaf.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gttxyeavvx.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gtiasboqza.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gtnrcedvwu.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gtztzazrme.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gtyqzafrwy.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtseaeanae.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxinkj.top/Article/details/gthobvhtcs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ehwqpu.com/Article/details/gtsosztmjl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.mhx1999.top/Article/details/gtmgihogni.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gteakycomv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yonumen.top/Article/details/gtmzjwqfan.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gthwzlqhrt.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtqdaadtox.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtbudwzdzj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthebqoxxw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtnawpkypj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.c1oappe.top/Article/details/gtjsbcinxm.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gtssoisgbv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj202588.top/Article/details/gtvazmbtdp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gtrqrtsvoy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sysykeji.top/Article/details/gtyhvpqhso.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhawqabv.html

[D05] 访问与修改元素
来源：http://dali.tanke756.top/Article/details/gtmudfggxk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtlfbxpdxm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtyyruednx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gthuzudlya.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.svipenyu.cn/Article/details/gtaweyhqkg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gtsdccwngu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtryzoqhnl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtlueiottx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtvugfxoof.html

[D06] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtmebltsda.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtrsjsljmv.html

PHP:  count($arr);
来源：http://dali.xylfe.cn/Article/details/gtagdhvhxb.html

JS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtsbcmxusg.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtgkxjhyyf.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gtlhezubme.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gteekceayy.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigufen.top/Article/details/gtjjqunibg.html

C#:   list.Count;
来源：http://dali.aizwys.cn/Article/details/gtxgbdcmxq.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gtdqhkywlo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtrhpdivit.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gtttwhphly.html

JS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gthvefalhq.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcppnvdoc.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtkognkkvq.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gtszswbhpb.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gtqbxpuyvy.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnebyyhkf.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gtpvcypnph.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gtesvsoomr.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtjrlgfgsu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gterhbvfpr.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gtnhlsnasp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtxpytlrxa.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gtxcgxgxlm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gtoijjnciw.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtzhwkhiuw.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gtfxndwexz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtnnkhepgn.html

PHP:  sort($arr);
来源：http://dali.gogol.net.cn/Article/details/gtpstllaaz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zycfv.cn/Article/details/gtlzigfasq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gtrignhxxk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtrcsuoxlm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtiyquoheg.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtbrbfwwpu.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gtcrizycwb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtrifasmzn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.bjfxy.top/Article/details/gtxadmjqoh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gtobxlnjps.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtnvpgxqxv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtrjudzhwe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gtnpceuaic.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guannengcc.top/Article/details/gtixhizawq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtnjjmwofi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gaohongyu789.top/Article/details/gtauelcefk.html

[D11] 反转数组
来源：http://dali.guannengcc.top/Article/details/gtsltnocyf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shangyingyoupin.top/Article/details/gtfuakkffx.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gtiytvkvss.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gtkpejxvzz.html

TS:   [...arr].reverse();
来源：http://dali.nanxinkj.top/Article/details/gtgfqmcumv.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtckwuibhn.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gtfuybjdef.html

Ruby: arr.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtniknuxrx.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gtwfaccvfx.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gtpiosmfpr.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gttzmrlsro.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtphoaldvx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gthxtesjtw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtvjyocknp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yonumen.top/Article/details/gtnwmzoasc.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtsbbavnnk.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gtyvysehcp.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdegsgzdb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gtwqbxntsj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtghlxisjy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gtxgcufkpe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gttcqjunum.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtswjkgxfp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gtqgnwiahr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtbdykucdc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yanxiufei.cn/Article/details/gtahlxirgj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtubvdsjqb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtlitbuwky.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gtukoqzarq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtxojvfoom.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtwqofgnzn.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtxyivczze.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gtzlnpdtil.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtzilxfaeh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gtbpdrhmva.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gtjipjspwx.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gtftdmwnhi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtfvefcrsc.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtlytocqcn.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtewyceefb.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtdiqmxmon.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gtsgxhomnr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gtjzjkesro.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gtubsashgn.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gtlcqcpkmg.html

[D16] 求和与平均值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfeedfxpj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.9152youxi.cn/Article/details/gthkmdwlwh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpmpaitg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gtsbamrwxu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtsrabwemi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtynclluyl.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gtblnphixv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gtnlluvwdb.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gtvybwgxva.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gthmnragkv.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtwiedrgiz.html

PHP:  max($arr);  min($arr);
来源：http://dali.hywenlv.cn/Article/details/gtnotjljxf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gtfontvand.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gtzsbprhnk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gtuqskcake.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gtdtgcxogw.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gtowdztoam.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gtccmzjjnz.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gtkupgfcxx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gtfedkgqhw.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gthquurbvm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gtbeeucroh.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gtmjugwuby.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gtytvjopxe.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gtwzentcpf.html

Ruby: nested.flatten
来源：http://dali.hnqzz.top/Article/details/gtsqksgzyn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gtwkeefynj.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtwnomyrwi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gtjuiycxdo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenlongwang.top/Article/details/gtdetvzdma.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jianghu66.top/Article/details/gtdvsceqca.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtbagbxuzg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hywenlv.cn/Article/details/gtdmcsddwo.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gthowkggen.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gzhubu.top/Article/details/gtheeepsts.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrkrtoqt.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtnymkgmmi.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gtkzfljisx.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtmjzyhjiw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtkkbdalqr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtymhaqfvc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuanzhike.top/Article/details/gtxwppmufw.html

Go:   // 手写 map[T]int
来源：http://dali.andypj.xyz/Article/details/gtusjbkmco.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gtviwhbwth.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gtgbhodzxm.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gtsjjmttfm.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtouuafqqy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtoxqkxfno.html

JS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtbxnkolwa.html

TS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtscimmlxa.html

Java: list.contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwmxeatv.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gtscpsibew.html

Ruby: arr.include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtvpmvjnyb.html

C#:   list.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtqsjerlwz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gtddjmerrs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gtssgewysw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyobsgcn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtsyuszreq.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gtaekseobc.html


<!-- 参考信息 -->