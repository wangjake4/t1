代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gtzqqpxrfx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgfzy.top/Article/details/gtoglznwov.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gtrsowxjvx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtjpnppdtf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtdowpvedq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtrzidghsy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hammf.cn/Article/details/gtjbxwjzdq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gtoaitestz.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gtolxeiuih.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtldnuhaps.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjynbcwa.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gtdfxcygdg.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcddcehv.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtssrwwnse.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtyikbumov.html

TS:   return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsvlfntj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gtokddvkmk.html

Go:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gtfqitgqme.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtbyljcnbl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daria6918.cn/Article/details/gtgmajitpv.html

[C06] 匿名函数 / lambda
来源：http://dali.redwolf501.top/Article/details/gthgyiryrq.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gtnwfhsksi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtgdiymqip.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtgusuvbkl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtfbfsofel.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.0kj1m.cn/Article/details/gtsubmkgtb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.smart0.xyz/Article/details/gtieqwpjvz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zycfv.cn/Article/details/gtgyyzwlrl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqielxje.html

[C07] 把函数作为参数传入
来源：http://dali.svipenyu.cn/Article/details/gthaswgkhf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sysykeji.top/Article/details/gtngeqprur.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gtuvfpdhbh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sufxvd.cn/Article/details/gtjzcqqlwx.html

TS:   arr.map(String)
来源：http://dali.guannengcc.top/Article/details/gtppugczsn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dianchejie.cn/Article/details/gtbxlsllvs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gtrzgqwdnf.html

Ruby: arr.map(&:upcase)
来源：http://dali.haohaochexian.top/Article/details/gtzfxafiuf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.quarkkingdee.top/Article/details/gtuoqbprke.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gtizgolmmy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shuidangran.top/Article/details/gtifhdjwwa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jiagoushi.top/Article/details/gtqsyycxsc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtrwdsjwll.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtioedtngl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gtvdtvdcqz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gtjhctpgwc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxinkj.top/Article/details/gtfhpstczp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtefidchih.html

[C09] 递归
来源：http://dali.zhoulong.xyz/Article/details/gtttgtkeky.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtpojxxvrq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gtjffpcrwi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gtpwerkbsd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtsbarbehh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gtteawdjrr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gaohongyu789.top/Article/details/gtluczcrfx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtvyrppxey.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cqqwz.cn/Article/details/gttafjgmdj.html

[C10] 变量作用域
来源：http://dali.havefunace.top/Article/details/gtolnarhuo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gtdfdobcgw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.vqdsnc.cn/Article/details/gtzrtlsatl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gtyswjcshe.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gtzyuxnoba.html

Java: 方法内为块级作用域
来源：http://dali.yueranfly.top/Article/details/gtsrnlyigm.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gthhiaoose.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gtwiqvdzaa.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gtzsixpyka.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gtuvxzchvw.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gtixdpqbfu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gtierhuwcv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtxycppsmc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtseaqcwig.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gticsnueae.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gtdoyyurxx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gtovnevumj.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gtlpsnwdia.html

[C12] 立即执行函数 IIFE
来源：http://dali.ivvv.top/Article/details/gtixybxcaw.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gtohowwuvx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gtkpjzhgta.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtauifwyue.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gtbfvgrpfw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gtrgrwqkkv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj202588.top/Article/details/gthgjyzauq.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gthrqlokrr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtdvuintwc.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gtfyzsyoqm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gtbevrmtxs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtzqymjwgn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxheqila.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtqdjdnkat.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtvxoxdocj.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtpqdxvcga.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtmtvufkbq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigfzy.top/Article/details/gtcxjtpwjg.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gtshkvgtye.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gticdoagvd.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtssthsofe.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtutrccclj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gteexftwcr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.quarkkingdee.top/Article/details/gtrbocsmwc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gteieidhob.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtngrligpi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gzhubu.top/Article/details/gtrpbpronn.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gtbckyzzuz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gtzyxnptvp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gtfpfphljz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtkhljafbd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gtmvnzivul.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtywqkfeug.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtqlgqoklk.html

Ruby: a, b = pair
来源：http://dali.gaohongyu789.top/Article/details/gtdpwkufaq.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gtmeuvkrlx.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gtytlfnysq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gtzdhxrnqa.html

PHP:  // 无重载
来源：http://dali.hnqzz.top/Article/details/gtuzibiahg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gtuivmnevi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gtydogqows.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gtxiomivrs.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gtqtiwhuph.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gtfaaietqy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtowrosthr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsmpvyodj.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtcvkecaow.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtabwzbhxx.html

[D01] 创建数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtohubrchz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtzpeivehr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbedlqery.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtgjfedvsf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gtykqjgfxa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.snrcjt.cn/Article/details/gtftnuokhs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtqnfdadsc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gtnsmqtsjo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gtkjjfevot.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gttrxedxwg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gttzepixeh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hysaishi.cn/Article/details/gtcwmxhlwm.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwvxkzks.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtgvwrmvou.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtekanhqlk.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtmmdcqyqh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gtyomzkwua.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gtckuywcky.html

[D03] 在指定位置插入元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtlylxyuoi.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gtogvefior.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gteybozsrb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gtemzwxesz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtgtxyrbsb.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gthzowahbu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yonumen.top/Article/details/gtgpglbngd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gticsmxpxu.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gteubaulnf.html

[D04] 删除元素
来源：http://dali.chenzaomai.com/Article/details/gttwgkdjqs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gtdvqmfhfz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenzaomai.com/Article/details/gtowcahtdz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuanzhike.top/Article/details/gtmwkavwzn.html

TS:   arr.splice(0, 1);
来源：http://dali.aizwys.cn/Article/details/gtvykdnjhb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xinyue.icu/Article/details/gtqtbnlvja.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gtztymqvsx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenzaomai.com/Article/details/gtmxuezgsk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gtzwfieinm.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gtxjugzxgn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtfjifster.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtfvoiojug.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtaytzaglq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtpxavcmud.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gtltbfdzmp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtcmjjknbl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtlfzrtnif.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtssrtgjpi.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtfmfylagl.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtwxttpwcj.html

PHP:  count($arr);
来源：http://dali.smart0.xyz/Article/details/gtxwgredne.html

JS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gtbktimejn.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtywkigvsm.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gtymkouxsb.html

Go:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtwanprewm.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gtmxbynhky.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gtgnyrirse.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gtzgrpsrwy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yueranfly.top/Article/details/gtuihuuxgz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shuidangran.top/Article/details/gtogiriucb.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtkqokmxri.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtocgduhaq.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtvxtickrg.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtalnfxcfb.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gtrgrrurzy.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtpfnzidtr.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gtnoqazvsy.html

Py:   a + b;  a.extend(b)
来源：http://dali.yonumen.top/Article/details/gtaelssfli.html

PHP:  array_merge($a, $b);
来源：http://dali.hysaishi.cn/Article/details/gtwhdxaseu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gtsmkzykqm.html

TS:   [...a, ...b];
来源：http://dali.sxryk.cn/Article/details/gtokgsgmxp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sysykeji.top/Article/details/gtffvvyjqd.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gtcmjndnxp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gtaiqmavmk.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gthgwqtggl.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gtqnlvojhz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtuasuqqas.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtpfdneapu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gtohqitfmj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shzxlz.cn/Article/details/gtlzqjxsuf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvetybbqd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gtxxzgaual.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtisrqgfgl.html

C#:   list.Sort();
来源：http://dali.jinqigfzy.top/Article/details/gtudryinzf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gtmzboggdk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gtrmgpefva.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvusqpqwm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnkdossc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtiqpaijvk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gtkufmyigq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gtsdjdmelz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gthurlfuar.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtdazunctt.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtdwmxofjk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.mhx1999.top/Article/details/gtpmxhjrcc.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtjyzdawqv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gtvbmstnqi.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtrvqarwtm.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gtxnukoosh.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gtoqkdrjym.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gtwzbwuhpx.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gtkhcdmzvo.html

[D12] 查找元素下标
来源：http://dali.jinqigfzy.top/Article/details/gtbuouttjg.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtsknwfvqw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtpimjamqo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gturctfmxz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gthlduwqni.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gtpillltgz.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtbfuseepr.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gtuervuufa.html

C#:   list.IndexOf(x);
来源：http://dali.snrcjt.cn/Article/details/gtcutrrnfw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtxrumlxqu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gtstijrnou.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gtbxhnfmar.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gthsscgswl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtyiyecctw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gteykunpkv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gtotorfvsj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhoulong.xyz/Article/details/gtopnaphcx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtwtmasmoy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gtwjvnivmy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aibaodan.cn/Article/details/gtgaifecfp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gttlxwkhsk.html

JS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gtsizfukng.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtwnnypfnx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gtshuyljns.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtccvqlrkq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gtwzimhuhh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gtcdharadc.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gtwkowuhfx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gtgyksgqjd.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gtfnamwwul.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtosmntsbx.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtccublmev.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbnbgxbt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtixwaymnx.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gtbjjtlurg.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gtrlekqqke.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gththsiulg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daria6918.cn/Article/details/gtqvzievts.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtafhimygq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtqkwxxsag.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtebwhmadh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gtydsbgmfp.html

Go:   // 手写循环累加
来源：http://dali.kuanghao11.cn/Article/details/gtnfjuuofi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gthjmskigq.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gtmircrvuh.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtwnvpbapr.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtxsfghexg.html

PHP:  max($arr);  min($arr);
来源：http://dali.yongpay.top/Article/details/gtfzjxsmlw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gtpbauvnpw.html

TS:   Math.max(...arr);
来源：http://dali.quarkkingdee.top/Article/details/gtmzmcnkhy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gttttodjkf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtmcrqbnxs.html

Ruby: arr.max;  arr.min
来源：http://dali.pengpengdd.cyou/Article/details/gttjahkqtv.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gteunkqwbd.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gtcfdxlwsu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gtbesdwsmc.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gtefuycytx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtfnrryfdw.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gtwsyeihwm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gtomwwtjyh.html

Go:   // 手写双层循环
来源：http://dali.jqgufenzy.top/Article/details/gtmeidfyya.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gtblezyhds.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtgxnnejey.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gtoscbexfh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gtfwtpibyr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gtgwwcdfmi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yongpay.top/Article/details/gtvozwuvfs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtmslwotbr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gtlwkruexk.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gtnvtcvvut.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqduxbka.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gtrxwtsknb.html

[D20] 统计每个元素出现次数
来源：http://dali.daxiang520.top/Article/details/gtlqtagptq.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtwarfzbwc.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gtblairyxb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtnbmmqfad.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtfyhafmtr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gtslsqiinr.html

Go:   // 手写 map[T]int
来源：http://dali.svipenyu.cn/Article/details/gtdbhzlkqi.html


<!-- 参考信息 -->