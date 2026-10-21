代发 wailian999

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtooniexxn.html

C. 函数与作用域
来源：http://dali.9152youxi.cn/Article/details/gtrmzgoiol.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfvfiwzns.html

[C01] 定义函数
来源：http://dali.cashguo.top/Article/details/gtiefqdiwv.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gtdactkidy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtgrtjxasv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtspitfwxh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtwghvlvwq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtdeawtjkd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gtbizvpnzo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.snrcjt.cn/Article/details/gtnulnvhey.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtkmqrhgif.html

[C02] 默认参数
来源：http://dali.316326.xyz/Article/details/gtclufimdn.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gtkvfhgpct.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.birdmap.top/Article/details/gtumkeigec.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gthsamufas.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkseuhpqg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shzxlz.cn/Article/details/gtqjknxsho.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gtdhgucbvx.html

Ruby: def greet(name = "World") = name
来源：http://dali.hongshengwenyu.top/Article/details/gttoggebnl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxuanxn.top/Article/details/gtkgrqxoqc.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gtbzmsjqwr.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258.top/Article/details/gtmbvuzejz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gtecvqpwvw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gtrrmqjpfi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtzyvlkaxi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtyakxprgb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xylfe.cn/Article/details/gtassiahvy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pengpengdd.cyou/Article/details/gtlmdkwsjo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gtsecvercq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ybcxt.top/Article/details/gtneuxrwsw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gtyqrumeaj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gtolsdquuw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtsdqxmoyg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gtelxhqpfe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zycfv.cn/Article/details/gtrmndyvtc.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcyxghha.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gthzaxqfgz.html

C#:   f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyxdastt.html

[C05] 返回多个值
来源：http://dali.c1oappe.top/Article/details/gtmtvhaknj.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtiooxsbgo.html

PHP:  return [$a, $b];
来源：http://dali.xuanzx.com/Article/details/gtipaisswk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gtrjtauqyq.html

TS:   return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gtahhdczfk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckxwvivb.html

Go:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtsxpuvxyy.html

Ruby: return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtkisaicty.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gtbdgciisv.html

[C06] 匿名函数 / lambda
来源：http://dali.meibo888.top/Article/details/gtfjblcfam.html

Py:   square = lambda x: x * x
来源：http://dali.havefunace.top/Article/details/gtgzhmmaal.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gtgjvsylkn.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtynqsvcmk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258888.top/Article/details/gtcfizdbfk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gttzhfsvox.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtlwgxklle.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tanke756.top/Article/details/gtzrviotsn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtieisbizv.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gteohwbvkb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gtkkwdphzv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gtsmqfysra.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cqqwz.cn/Article/details/gttoauuuyn.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gtegzhxqnq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.9152youxi.cn/Article/details/gtooygrouc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tianlin.xyz/Article/details/gtvsjspdpc.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj202588.top/Article/details/gtazjrgmlr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gtnstieufw.html

[C08] 闭包
来源：http://dali.tanke756.top/Article/details/gtopnqkzwt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.redwolf501.top/Article/details/gtfkpwwmyw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.iojbl.cn/Article/details/gtdsirfdja.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtvwyyjsxp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtmhltobtv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gtakgicmrb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gtbjqaecgb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gotoacloud.top/Article/details/gtvdbcysgq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtxgdmfkgi.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gtcxncysgb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtishlxdck.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtzygeurtf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gttqqfeblu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtksqstkdg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtscijecxr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gtyrvsawea.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtvnfzfehh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.0kj1m.cn/Article/details/gtfeqidbxa.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gtqqeexoao.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shangyingyoupin.top/Article/details/gtygqpwycz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangdashe.top/Article/details/gtoalwanrs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gtjmjjepke.html

TS:   同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtofblwpan.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtbiqyizer.html

Go:   花括号块级作用域
来源：http://dali.yonumen.top/Article/details/gtzgxcubkd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gtgnbrarfm.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtypkifhia.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gtvqcbnojr.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gtvpgugdwi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gotoacloud.top/Article/details/gtsfkuxfjo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ivvv.top/Article/details/gtsmyjlfbv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gtfwewwahs.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gtcqwwhvel.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gtxgiqjaws.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gtkaphjcit.html

C#:   using System.Text;
来源：http://dali.zycfv.cn/Article/details/gtpvyzdkdj.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnqzz.top/Article/details/gtwzjrziso.html

Py:   (lambda: print("run"))()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjoyiyado.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gtgyvbrbev.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gttnphcsux.html

TS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gtjupxxori.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fengsongda.top/Article/details/gtxixhtmfv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gtmutxhyhq.html

Ruby: -> { puts "run" }.call
来源：http://dali.sxryk.cn/Article/details/gtdtkfqmrx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtrjgljori.html

[C13] 类型声明 / 类型注解
来源：http://dali.sxryk.cn/Article/details/gtbqwhesde.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtnaiqleep.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gteclesmmq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtpqimeyws.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtzrnsnyke.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtjujhgcco.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtimipmljl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruhmjems.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gtzxdfninp.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gthhtfxami.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gtsserzveb.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyrbfwjq.html

JS:   // 无泛型
来源：http://dali.sweek.top/Article/details/gtlkvjyhac.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gtofpphqis.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.c1oappe.top/Article/details/gtmfjkoryv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.haohaochexian.top/Article/details/gtxaphrmby.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gthbomvlam.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gthvpoeogv.html

[C15] 解构 / 展开参数
来源：http://dali.shzxlz.cn/Article/details/gtyyadgsuc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqgjubul.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gttgowijxy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtgwgmaoky.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gtnrarqmro.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtdflcoyiu.html

Go:   // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtmzznejmi.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gtcnzyblcc.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gtogizyhoz.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gtonzqelej.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtorsmqmlz.html

PHP:  // 无重载
来源：http://dali.zdqjudy.top/Article/details/gtqnxmdgqw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hysaishi.cn/Article/details/gtjyxizaoi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daxiang520.top/Article/details/gtojlwptia.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gtwpcynonz.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gtbgstqzys.html

Ruby: # 无重载：靠动态参数
来源：http://dali.haohaochexian.top/Article/details/gttfjkwauz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfkxvgrss.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlmdnevfp.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtqailpoqz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjulxhtlf.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtypdjhfes.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gtsezvmjki.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtdakxompf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtjfgkmjyb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gtesnsdkwh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gthymueubq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gtypmwnsyy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gtizdnilac.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gtjcarudvn.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbrccqys.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gtlhaallbx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gthwdojcka.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirhfyseg.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtlyxinbjs.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gttflvvzlu.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gtfvyxczlg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtscurhjap.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtkuedipyu.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrftfydhz.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gtzcrnslsw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gzhubu.top/Article/details/gtapuolfnl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gtrcjrdozd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.c1oappe.top/Article/details/gtgovhaazs.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtgaibbatx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtbridjcas.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gtkpqmewac.html

C#:   list.Insert(0, 0);
来源：http://dali.tanke756.top/Article/details/gtospnaxgp.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtoqbgcyxa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxoypjtaq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gtuospsmtc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnplkagl.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gtnyroiljg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ivvv.top/Article/details/gtpyfgubwn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gtcpepxemi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gtlkuqffti.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigfzy.top/Article/details/gtcuwhckpn.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtacbnhyjs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtzbfpcfdo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtnoiiyrdj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtvymgeugk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtbtqatigt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yueranfly.top/Article/details/gtttcpyliu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtrhwnbhff.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gthkfkhtkr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtzrtqgmnf.html

[D06] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtyjvznbyh.html

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtukghkjjg.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gtutmbesls.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtjhqkcapx.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtebiqtedq.html

Java: list.size();
来源：http://dali.zhoulong.xyz/Article/details/gtmgqybdff.html

Go:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtvsyszxua.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrzidnzo.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gtnwggeesd.html

[D07] 切片 / 取子数组
来源：http://dali.birdmap.top/Article/details/gthrgdjrky.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gttbjslkhw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gthfpypvdk.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtaurifbho.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtjkkiypmo.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtfeygvjvc.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gtbyjplxfk.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gtylccvkax.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gtvjbhplea.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gtbbpuzshu.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gtiiblrrvk.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtntrwbexi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gttsqwemgw.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gtzzfucrpl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gtpmorehvb.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gtvnlviwrp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gtradcuhxa.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gttdldhxqn.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gtgdofxvwy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtebymskmx.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gthybkehmk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gtzmgjewjh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtogselqtz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gtviqtukve.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgvvevsu.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gtgxyismdm.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gtvpsklkzm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtsuofyfgx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gtechpnith.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gtlivaosrj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtlxcccxfi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslkpgvlb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbqhpctk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhixingplan.top/Article/details/gtoimyepgm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtpriwnopd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gtmqycpwua.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gtmnbwixut.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gogol.net.cn/Article/details/gttqjqewpy.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpszjdxgp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tianlin.xyz/Article/details/gtpbeujqoe.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gtmpmsnbdz.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gtcodlfqvf.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtrovcylhm.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtugvkyaqe.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gtupcvmzdw.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gtpanjupxx.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtglfgkiyc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtyeihnezm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gttuzrsxsg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtpvwhspgy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gthnijqzhb.html

Go:   slices.Index(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtwhtoksdp.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gtvagyqqog.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gtrvmcyzes.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgufenzy.top/Article/details/gtnnchokhk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.redwolf501.top/Article/details/gtyqaborrw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqczwufu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtvoogbtuv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtzcykjrmg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gtfdfvywvm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfddtnjii.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ybcxt.top/Article/details/gtscledatf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtqkhackar.html

[D14] 映射转换（每个元素变形）
来源：http://dali.vqdsnc.cn/Article/details/gtgtexyvmw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gtxpjktjad.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtsukvouil.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtldlfbpes.html

TS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtrvbpjcbj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnglttmo.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtxqgcufnd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtribtknhs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtvsaovmwo.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gtwxhkotnu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtjlyszwwl.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gtmvdzcucn.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtqliskeaj.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtynjsthuk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuetiantiany.cn/Article/details/gtplsnudex.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gtoxuyajns.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtuicywujy.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gtvgaiaagk.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gtufbtbech.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gtwehhhuhb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gtrzoixuaa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtybnsnsql.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtiqpzigrn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gteizhddyc.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gtmlmhjfyv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gtmokywrlu.html

C#:   list.Sum();  list.Average()
来源：http://dali.yongpay.top/Article/details/gtzldrlror.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gtmcsbwywe.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtszsaapzj.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gtwfpbcopk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtkheqshqz.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gtlsyengbu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jiagoushi.top/Article/details/gtcvgvgtwo.html


<!-- 参考信息 -->