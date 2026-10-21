代发 wailian999

Py:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtbonjvwuw.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtggrqtmwf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtynkdgris.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gttmyvuanq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hongshengwenyu.top/Article/details/gtneefpffq.html

Go:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtubnpxlhl.html

Ruby: return a, b
来源：http://dali.9152youxi.cn/Article/details/gtaybwrkgy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gtnetnojtw.html

[C06] 匿名函数 / lambda
来源：http://dali.chenzaomai.com/Article/details/gtfzuftkhf.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtijcromeh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nwbrower.top/Article/details/gthmzuytfx.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtiapzejpp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.iojbl.cn/Article/details/gtamuzevou.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cashguo.top/Article/details/gtxkdmrlnh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gtrgehdgfh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gtiybkwkyx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtqqmlsmeb.html

[C07] 把函数作为参数传入
来源：http://dali.quarkkingdee.top/Article/details/gtgincfume.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xinyue.icu/Article/details/gtwyygibxi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj202588.top/Article/details/gtdaxncker.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jlsjyb.cn/Article/details/gtwpuzzege.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gtvgrsygrz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ydzc1.top/Article/details/gtxlqintqx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gtcaiahoak.html

Ruby: arr.map(&:upcase)
来源：http://dali.dashuyun.cn/Article/details/gtyvfvddtq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj202588.top/Article/details/gtxahouiks.html

[C08] 闭包
来源：http://dali.quarkkingdee.top/Article/details/gtkamnhwgu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gtufpkjaxt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gttmmglqxn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalhixtjh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtpxagbdzw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gtddcflfwo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gtkrpuzruq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sweek.top/Article/details/gtastamcpx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtvvqguqan.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtvqhcdhbn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtewqhoxhl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqjhxreg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtxjxowimh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gttdhqxkzm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdvigxmdl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gtwfnujtkx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gtoepfznld.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sufxvd.cn/Article/details/gttpecjflu.html

[C10] 变量作用域
来源：http://dali.nanxuanxn.top/Article/details/gtfjkosnww.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gtuelbnswk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daria6918.cn/Article/details/gtllguuwdu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtzmxljule.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gtczbdgizo.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gttsskuosa.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtetxzhmhu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gtaontuimb.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gtauamddop.html

[C11] 模块导入与导出
来源：http://dali.snrcjt.cn/Article/details/gtkdpcjzov.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gtndzegbgo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuanzhike.top/Article/details/gtvsyyoyxy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtpnmhqhnk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gtmlqkujio.html

Java: import java.util.List;
来源：http://dali.jqgufenzy.top/Article/details/gtjyytlbqx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.0kj1m.cn/Article/details/gtljqendge.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxinkj.top/Article/details/gtqsojctxw.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtpaletjnj.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhengqikj.top/Article/details/gtjaoinbgr.html

Py:   (lambda: print("run"))()
来源：http://dali.yuanzhike.top/Article/details/gtwytcorlu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gtcomngnmd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdclavco.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gtkmlimdka.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gtbhscpshw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gtaxqwwpyb.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gtnmjjlmhx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.meibo888.top/Article/details/gtvwnsqngn.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyffpesy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gtyikfozhm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtfwmfidtj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gtunmymthh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtwawzzcar.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtpdobzrsz.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gtbgyonggp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gtfbgzwkat.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtbucnewso.html

[C14] 泛型函数
来源：http://dali.quarkkingdee.top/Article/details/gtybjoiigv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtiydiiqgl.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlzcbyhd.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gtxgajadpb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gtwejgcjlo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gtgsvcinjc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gtgzougpjk.html

Ruby: # 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtssxjlbxs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gzhubu.top/Article/details/gtodbjpbhj.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gtntzksnld.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gtrlkkozzt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdxoclfh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtpwwqptwx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gtevfbocdg.html

Java: // 无解构
来源：http://dali.pycfn.com/Article/details/gtrqssvmqi.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gtqurrkdms.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gtyhqpgtzx.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtfjvyopvn.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gtgkdhfckq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtqxfixsax.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtbwxnvvxl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sysykeji.top/Article/details/gtqjavdfyf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ybcxt.top/Article/details/gtdpqygfnq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gttnrampbm.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gtiguesebo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yangfankeji.com/Article/details/gtpkrkumxe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtsxpxwpzn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtiphaxcyy.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gtnnunyonr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtovcdzuvm.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtxptgosuj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gtsspziwlg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtklnlsxnp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtochtzyug.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gtkkmgitwm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yueranfly.top/Article/details/gtalyejusj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtwrmylqdy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gtofjtmzpk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gtmppxeefp.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gtsiaxuvwc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jyoumei.cn/Article/details/gthzjjxqvx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.9152youxi.cn/Article/details/gtegzpdfnt.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gttkmoyinv.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtwvooumqe.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtfpmxyrqi.html

Go:   arr = append(arr, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtdjmbbssg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gtnaqstyzz.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gtgwrqqijb.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtqtshpwxu.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gttmrtqkmd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuanzhike.top/Article/details/gteuywsxhi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sweek.top/Article/details/gtmxyycxpx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtnhvfiqpa.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtyetmkooh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtotpaakvh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gtxrdlczph.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtnllhblnp.html

[D04] 删除元素
来源：http://dali.meibo888.top/Article/details/gtfrauyglt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtilttbrjz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtngbrltue.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gtzdvrtele.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gtbutryaqd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gtieqniwdh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sweek.top/Article/details/gtlcmqmmbh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxddjuoor.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.andypj.xyz/Article/details/gtqaqjujrd.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gttpztwtaj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtmzxbyton.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtippgxqpg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtxcpzrplr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gtkooxlrwu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtjtushclg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtpzkmsycn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtyekxekmf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtnvthilho.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtzvdodyon.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtgjkbfwnc.html

PHP:  count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtrbgoeejq.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtyvviqanm.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtwmqnagvw.html

Java: list.size();
来源：http://dali.wangdashe.top/Article/details/gtrbndzrhd.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtnsuxaqbm.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gtmagrwinq.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gtnzuyxfmf.html

[D07] 切片 / 取子数组
来源：http://dali.nwbrower.top/Article/details/gtzvxtzcoi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gtaspujcex.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtmowvdzau.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtcbxpffrf.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gticehntdx.html

Java: list.subList(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtyxxrpaco.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtsdsovdeg.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gtuqaxcuix.html

C#:   list.GetRange(1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtevinetvw.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gtyevhhpin.html

Py:   a + b;  a.extend(b)
来源：http://dali.pycfn.com/Article/details/gtekpatfde.html

PHP:  array_merge($a, $b);
来源：http://dali.zhongyouzk.top/Article/details/gtakaqvkkx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hywenlv.cn/Article/details/gtmuolqyqr.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gtttfyrixc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtvlzmrhvy.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gtmqdackvo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gthcukqgnl.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtkmfuebhj.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gttnmuxdif.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtuktyzauf.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtxoujyeza.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gtejursyfc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gtcfdgfjcv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.smart0.xyz/Article/details/gtvuoykugp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtvdnzzxfa.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtwshwydpq.html

C#:   list.Sort();
来源：http://dali.chenjidiqi.icu/Article/details/gtolgvxydj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gtzgcoauev.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gtzgzrahta.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gtyizzegol.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtkzyfyyvg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtfdoqfyyo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtfdozrnae.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gttnztxrfz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gtoekgldsz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtvuzqmkzn.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gtqtcvwuvt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.mhx1999.top/Article/details/gtdgtorfpe.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gtbgxttnhm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhongyouzk.top/Article/details/gtjdczsekt.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtljadhpsy.html

Java: Collections.reverse(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrfyfuwa.html

Go:   slices.Reverse(arr)
来源：http://dali.9152youxi.cn/Article/details/gtdwjjhakx.html

Ruby: arr.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtmhbszdgi.html

C#:   list.Reverse();
来源：http://dali.meibo888.top/Article/details/gtinwjrrhg.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gteusabhwi.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtcaugshlf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258888.top/Article/details/gtaoxyqnuh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtzrsgdoge.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtctjjwyfh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gtwzxrragy.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtqxsjwusu.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gtcntblakn.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbncbeypd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gtmqvwudmz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gtcyfeaawl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtxvhtbuko.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozbibrdf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtahonhwsw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gthjmbgwko.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tian-w.cn/Article/details/gtdtktknfm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shangyingyoupin.top/Article/details/gtfctikmvn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtbgkgnnyn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gtfgijpfje.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gtmlcpysvg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gtacvpagzw.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtxllurtyx.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtlancytqr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gtiymkgvyy.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtrhadolik.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtilvisbaf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gtvemgkrfi.html

[D15] 去重
来源：http://dali.cqqwz.cn/Article/details/gtatrgeera.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtgcszrzys.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtojbarsrb.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtashsgqnu.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtplwtqprj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgufenzy.top/Article/details/gtrsonhokp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gtbhxtyele.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjvsieis.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtkoklrasu.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtacjzmwst.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtxtkxxpmi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gtbeuawezs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgscwcns.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtixdfdzsq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nwbrower.top/Article/details/gtshdnoynf.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gtwnlngcaj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gttebjvjxg.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhengqikj.top/Article/details/gtkyzkxuyj.html

[D17] 最大值与最小值
来源：http://dali.iojbl.cn/Article/details/gtcttqfuhy.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtpogvubnw.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gtnihjyrss.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gtlsaxqkde.html

TS:   Math.max(...arr);
来源：http://dali.iojbl.cn/Article/details/gtwpjxeaag.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenzaomai.com/Article/details/gtugnqqfyh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtpsbwqrbc.html

Ruby: arr.max;  arr.min
来源：http://dali.zhongyouzk.top/Article/details/gtvdmedjkj.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gtryjzyilf.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtavlkmoil.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gtadrvwmxc.html

PHP:  array_merge(...$nested);
来源：http://dali.gaohongyu789.top/Article/details/gtkjgnsgdh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtckjqvxsj.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtzlfjbgdr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gtgmwkckna.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gtywziawne.html

Ruby: nested.flatten
来源：http://dali.xylfe.cn/Article/details/gtxuiqbgaz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcfqgbnz.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gttxhsogro.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcbhzaai.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gtktcemgsb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtlxvzhjed.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtwdumcqdu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nwbrower.top/Article/details/gtapzbxvvq.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gtdpsxblme.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtcpizzblf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.0kj1m.cn/Article/details/gtnbbvfwxv.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gtuozfzcvo.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gtwwntdtbn.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gtacxydenw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtfnngszvo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtcegrkflp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dashuyun.cn/Article/details/gtrmmmdcle.html

Go:   // 手写 map[T]int
来源：http://dali.nwbrower.top/Article/details/gtqeqlckce.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gturwdrbpj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gthbmuuhow.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtcsfjoveb.html

Py:   x in arr
来源：http://dali.yangfankeji.com/Article/details/gtsrerddum.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gtzowgbrcp.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtkrgjyzad.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtjtvoknsm.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gtbkjqybwt.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gttnxmtjxl.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gtophgiqcu.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtkompgbba.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gtcbwzvdpa.html


<!-- 参考信息 -->