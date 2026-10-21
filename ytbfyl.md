代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gtvuczazxu.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtijcezjuo.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtdhmhxqbq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gtgvfyqyui.html

[C06] 匿名函数 / lambda
来源：http://dali.yuanzhike.top/Article/details/gtvwlvwnfo.html

Py:   square = lambda x: x * x
来源：http://dali.xziqi.cn/Article/details/gtjztnzulw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gtlbrufzgw.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gthculmrtl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xziqi.cn/Article/details/gtnccyddpv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.birdmap.top/Article/details/gtsvosbayw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gtyqpqlcsj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtclvqopxv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtpuwxlutm.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gtecoaoxan.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gtfnhovdvx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtgpgvvsqw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tianlin.xyz/Article/details/gtbxbuztgi.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gtlbrxbdue.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtmzmklejq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gtrlnqqyys.html

Ruby: arr.map(&:upcase)
来源：http://dali.jyoumei.cn/Article/details/gtrbosqrar.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtdgexmdcr.html

[C08] 闭包
来源：http://dali.yongpay.top/Article/details/gtrlwbsxph.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuetiantiany.cn/Article/details/gtfxpnpwag.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gtnblujwzb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtazdidhug.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfirobocs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gtwctdjiol.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gtnhsrsjob.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhongyouzk.top/Article/details/gtggvnrrdr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gttmmqeqkm.html

[C09] 递归
来源：http://dali.xziqi.cn/Article/details/gtvlxlwfcf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtaojxuzre.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuxming.cn/Article/details/gtjqubbwbz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gttxzkmxcg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtqipuxied.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtvpguiayu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gtvijgrbff.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtpvbrnmgz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfixnuzhe.html

[C10] 变量作用域
来源：http://dali.chenzaomai.com/Article/details/gtcwhdlqdd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gtxvwsppgh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dashuyun.cn/Article/details/gtzhpdxkre.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuywmaqb.html

TS:   同 JS
来源：http://dali.0kj1m.cn/Article/details/gtnjebfutk.html

Java: 方法内为块级作用域
来源：http://dali.sysykeji.top/Article/details/gteqzplhcb.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gtehronruu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gtrswyizdq.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gttlsildln.html

[C11] 模块导入与导出
来源：http://dali.fzhhl.top/Article/details/gtywulgkbq.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gtkxmqpjgj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hysaishi.cn/Article/details/gtgydeewrr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gtgetvshko.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gtpygasgtj.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gtiphdfofa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gtooiurvgm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtfzyvblra.html

C#:   using System.Text;
来源：http://dali.yj20258.top/Article/details/gtyvkvegdo.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtctcifqcq.html

Py:   (lambda: print("run"))()
来源：http://dali.hnxiangtu.top/Article/details/gtmhwfgviw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gtxhoyyhzl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtkgwxtdzi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtfwuxkqko.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gtejtulmqu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zycfv.cn/Article/details/gtxxfpcwjn.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgufenzy.top/Article/details/gtabsbiiwk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtttwrstne.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gtmhyfnses.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gtabooemek.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtgvzqxqgx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gthshdxlxe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtfjzncjrs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtuutjnede.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gtvdrqsxba.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigfzy.top/Article/details/gtepkzzrnw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgufenzy.top/Article/details/gtmwlkngec.html

[C14] 泛型函数
来源：http://dali.yj20258888.top/Article/details/gtonmghhhk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtgywabazh.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyydeywm.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtbziqvhin.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yongpay.top/Article/details/gtkhkzgjwd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gtebqpiqot.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ehwqpu.com/Article/details/gtiqvojzfd.html

Ruby: # 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtvyyutfoz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gtyakiofbo.html

[C15] 解构 / 展开参数
来源：http://dali.havefunace.top/Article/details/gtciclgrrc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gtbrijuamy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gthtpybkbv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnuxeqctc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gtpfycnmfb.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gteouzwstc.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gtlyfirnch.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gtbjjgqrlo.html

C#:   var (a, b) = pair;
来源：http://dali.guannengcc.top/Article/details/gtmwblfwbh.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gtjhrqowyf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhoulong.xyz/Article/details/gtxhqrewjg.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gtjbjoaugd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtliyunyix.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gtumiptjoc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gtpqnrgbtl.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gtfwczrylf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gtyvgvcnxl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ppjwa.cn/Article/details/gtgldemnrr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtejkgaytn.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtyycdfztx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtaudxsxei.html

[D01] 创建数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtlbslklhq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pengpengdd.cyou/Article/details/gthvftljzw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtjqhgctbw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuanzx.com/Article/details/gtwgvbjogu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gogol.net.cn/Article/details/gtotycgsas.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xziqi.cn/Article/details/gtacqdltzf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gtrakikfrn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gtnpsispbc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guowangkeji.top/Article/details/gtnvlbnhgh.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtadwzjeuy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gtrgpctjdj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gttvawegxv.html

JS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtfqbocqnu.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtpaocwylu.html

Java: list.add(4);
来源：http://dali.ppjwa.cn/Article/details/gtrdbpzvcr.html

Go:   arr = append(arr, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtzpphkuzb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gtdsduhied.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gtbvxhaikm.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwydddpl.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gtvmyheyde.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gtqjnchcyr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gtsebwdibc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj202588.top/Article/details/gtxgxyvpvw.html

Java: list.add(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtbgbaklqt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcrtvypk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gtnkexiuyz.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtxfkzyzmf.html

[D04] 删除元素
来源：http://dali.nwbrower.top/Article/details/gtoshcrewl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aibaodan.cn/Article/details/gtkowqlrsj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtwaqxnesb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gturesmzce.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gtoeycoyjz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guowangkeji.top/Article/details/gtmeilpzgi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gaohongyu789.top/Article/details/gtcqvomeix.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gtlezscqdu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gtbtnqedtm.html

[D05] 访问与修改元素
来源：http://dali.yuanzhike.top/Article/details/gtbyzlpfps.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtpwpzpcyo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtvochncel.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtawtmolfx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gtfblmeraw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gtdlyzqheu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudcensco.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gthlxdlxhv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtwtsdikpn.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtjxczwrcv.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtmozgyhpe.html

PHP:  count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmglgqbzx.html

JS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtqwrotnfm.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtmeywtvpi.html

Java: list.size();
来源：http://dali.hongshengwenyu.top/Article/details/gtavhiruko.html

Go:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gthicjtvay.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtfnwgsqnw.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gtgawqlyhq.html

[D07] 切片 / 取子数组
来源：http://dali.yuanzhike.top/Article/details/gtszhebkwu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gthlsahvsa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gtcquatovo.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtsxffzjsn.html

TS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtlnmlqkdy.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gtxpmhcjjv.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gtnywmdwnz.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gtvfurcqqp.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gtejkdzukb.html

[D08] 合并两个数组
来源：http://dali.chenjidiqi.icu/Article/details/gtortusvmq.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gtkqldkgox.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtlvsffika.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttejsaply.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gtvyldbonv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtukllppnl.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gtmhmnazpf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhengqikj.top/Article/details/gtxxqefvla.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtmudlwoot.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtnlikhqcq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtzkgmzwod.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtotwumdzj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gtlbgszpvc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gtbvgtlnah.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cucudq.cn/Article/details/gtwrxmveur.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtepcqtkiw.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtxdwrzolu.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gtlqammfso.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtyzvphhwi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gtijiueruq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gtxokyfhck.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtfupqfgjv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtnahxjlld.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtogwsqoil.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtfyuoms.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xziqi.cn/Article/details/gtbappdemt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gtzoupffhq.html

[D11] 反转数组
来源：http://dali.jiagoushi.top/Article/details/gtatzxdcns.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gtnttvdyin.html

PHP:  array_reverse($arr);
来源：http://dali.haohaochexian.top/Article/details/gtsmmrhuql.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gtupdnwhno.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gtckjnzpfc.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gtcowgimzv.html

Go:   slices.Reverse(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtuqaptqjf.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gtzlpgbznq.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtfhfvnrkp.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gtgfudfcjy.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefmvyxts.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sufxvd.cn/Article/details/gttrwrhoqz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtwcpwmiln.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gthotrqduh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gtmrnkwfok.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtjzxvkrkd.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gtbkpkbptd.html

C#:   list.IndexOf(x);
来源：http://dali.yvedp.cn/Article/details/gtgqqdiihf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtbxasjiqk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtaxqeslmj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gtrzazrzpc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtrpsrpclj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gtaezesfxm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gtrqktmiqi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gtbgwxevcj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gzhubu.top/Article/details/gtysflpszy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtyhiwuznd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gtwbaubmdo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fengsongda.top/Article/details/gtdfhdzuyo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gzhubu.top/Article/details/gtskmcgwnb.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtsqlurokn.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtuubijcfr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tianlin.xyz/Article/details/gtmmemfzfb.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtnxalnglw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtjpyibqhh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtbmltehet.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtssuuqnqq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtmehqxscg.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtdizemdvt.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtcutsejmw.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtxyabpqhu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gtqxvilvwg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gtymlamnzc.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gtwtjscduw.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtutjukbvx.html

[D16] 求和与平均值
来源：http://dali.andypj.xyz/Article/details/gtnlskhanf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fengsongda.top/Article/details/gtdhtcbnlp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xziqi.cn/Article/details/gtttmhnyay.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtxhxsfkdk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtpkigpqgb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtfuylcyen.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtxyadkqtu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.0kj1m.cn/Article/details/gtzyruimrj.html

C#:   list.Sum();  list.Average()
来源：http://dali.dashuyun.cn/Article/details/gtrydmtnea.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gtpsaokrrm.html

Py:   max(arr);  min(arr)
来源：http://dali.cucudq.cn/Article/details/gtognscfkl.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtbxarurza.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gtsgbaiyfs.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtiykwsjui.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gtcrneltot.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtjrrwvieb.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gtmikmhavh.html

C#:   list.Max();  list.Min()
来源：http://dali.guannengcc.top/Article/details/gtcogtxvhx.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gttuhxtaun.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gtaglbhjow.html

PHP:  array_merge(...$nested);
来源：http://dali.sweek.top/Article/details/gtxnjvpplr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cucudq.cn/Article/details/gtoeajtujn.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcikmwmlb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jianghu66.top/Article/details/gtwoxsibhe.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gtfhggyizs.html

Ruby: nested.flatten
来源：http://dali.yuanzhike.top/Article/details/gtdyotjpew.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtuvwmlgow.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gttrwrizob.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtktojnezr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxaqikfo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtkhnosaof.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtwelwmeik.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtsyivnehf.html

Go:   // 手写 map[string][]T
来源：http://dali.yuanzhike.top/Article/details/gthsfwhzbk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gtyquswuvm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtqhjjtkzg.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gteagwpxfq.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gtxqjjttqv.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtgljbgnwz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtpkvgmdlg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtlhvsyoyj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gtkpjpymwp.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gtaddpnzsh.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gtvdygzgmp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gtqxbyjndr.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gtymlfxzja.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gtfnszwhfe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gttlwwdixh.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gtxtlzjjtv.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtspcojuqg.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcurqddzz.html

Go:   slices.Contains(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtoqgthwuv.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gttkgycbsp.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtloypqbnq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gtehypaavf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gtbnmywfdf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gtlobabqce.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtsxgjdlun.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gtgxlkwhlg.html


<!-- 参考信息 -->