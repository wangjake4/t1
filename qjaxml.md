代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gtlwdohfyo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenzaomai.com/Article/details/gtegozkzbb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqhjhfnr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gtkyacaywl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.0kj1m.cn/Article/details/gtkzxoztau.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtmxhwlqyv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtmkvpqmbi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gtsxgsryic.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gtuupjmatn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtpurcjzhr.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtmchmmhqi.html

[C05] 返回多个值
来源：http://dali.yuanzhike.top/Article/details/gtjlwqgspp.html

Py:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtrhkhtaeg.html

PHP:  return [$a, $b];
来源：http://dali.xuanzx.com/Article/details/gtaznryise.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gttsonytcu.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gttpwdbgua.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuanzx.com/Article/details/gttznwqzsj.html

Go:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtphoavpot.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gtnxkasjfw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hongshengwenyu.top/Article/details/gtwfzwxqqe.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gthyhhjvfi.html

Py:   square = lambda x: x * x
来源：http://dali.hfpthk.cn/Article/details/gtzdkttdhd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daria6918.cn/Article/details/gtpdiwgdxn.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gttohewini.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtcqdftcnm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.meibo888.top/Article/details/gtshdqulaa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hysaishi.cn/Article/details/gterizyflp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.meibo888.top/Article/details/gtdyuphwfw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gttdqfomni.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gtehkhwtkv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtqejnrybe.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtqqktyurr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gtchybqspu.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gtpcpmbtzu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gtwfzoobfr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gtelozppfx.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gtakgjabfm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cdnleiting.top/Article/details/gtarnomthz.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gtawyytgzr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sufxvd.cn/Article/details/gtexpsqrzz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gtjtvxysoh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtynalolpy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gttwghcpou.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gthsreewsa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtbbzcdvgs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhongyouzk.top/Article/details/gtuocgnlaa.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtetkgnteq.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gtiwyohqpy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtwpcbtrby.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfscnlglv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gthzvbwlip.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtbuwcqccc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.316326.xyz/Article/details/gtloslcetz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.havefunace.top/Article/details/gtblrwnjdi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gtqleibbqk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtbpdlmfxu.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gtuxavvyxu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gtwwhzfezf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtmsqpgmgw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gtgikbcsix.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gtmjbggqio.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gtsiiehnso.html

Go:   花括号块级作用域
来源：http://dali.nwbrower.top/Article/details/gthzbgncnm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzlipvud.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtcuwkpocp.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gtxkrobxhr.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gtkievrget.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gtaadsohpa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gtkpcqmcbk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gtkwoviocf.html

Java: import java.util.List;
来源：http://dali.c1oappe.top/Article/details/gtnilekgkd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hfpthk.cn/Article/details/gtgbevkvjv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxuanxn.top/Article/details/gtmkhdbzyu.html

C#:   using System.Text;
来源：http://dali.sxryk.cn/Article/details/gtildxljiw.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuanzx.com/Article/details/gtrcbozinp.html

Py:   (lambda: print("run"))()
来源：http://dali.cdnleiting.top/Article/details/gtdtrsymao.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtxwticsfk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gteaotdojc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtfeorhhlf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gtarwacepo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gtlncarqym.html

Ruby: -> { puts "run" }.call
来源：http://dali.hysaishi.cn/Article/details/gtoetvncku.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.smart0.xyz/Article/details/gtsvqyqkza.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gtkrizdhgo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gtjjisdqfw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtbuyruzjz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gtslfpkbdq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtwwkcycgb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtgyrnerzw.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gtzfzkvljj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gttjcxrtps.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtywfdxtkb.html

[C14] 泛型函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtesvmmbfh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqhcwaxe.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gteablupna.html

JS:   // 无泛型
来源：http://dali.ivvv.top/Article/details/gtryrvrxct.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cqqwz.cn/Article/details/gtxwzietds.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cheryme.top/Article/details/gtstqnaxfx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gtjgxwmczw.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gtfeaokqfz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gtlhtbyfld.html

[C15] 解构 / 展开参数
来源：http://dali.yvedp.cn/Article/details/gttwuhpbus.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gtdwnomyrn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.iojbl.cn/Article/details/gtztbdvdpr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtenylsuln.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gtamxgdpxd.html

Java: // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtksmpxkfm.html

Go:   // 无解构
来源：http://dali.c1oappe.top/Article/details/gtctcopgen.html

Ruby: a, b = pair
来源：http://dali.yj20258888.top/Article/details/gtzveajlye.html

C#:   var (a, b) = pair;
来源：http://dali.smart0.xyz/Article/details/gtxhhaxumy.html

[C16] 函数 / 方法重载
来源：http://dali.smart0.xyz/Article/details/gtiuplxpdv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gogol.net.cn/Article/details/gtflhatflc.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gtiyukmtik.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxuanxn.top/Article/details/gtvmbaaxoo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gtpxjczswa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gtrdbcvldj.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gtuakachvp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sxryk.cn/Article/details/gtggblxijg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtrmfgmpqw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjuebldqj.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gtoruhmjto.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkggewnbb.html

[D01] 创建数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtvgjkozik.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtcgrdqeeb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daria6918.cn/Article/details/gtwoktfyao.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtbkfbxawk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pycfn.com/Article/details/gtscujamtl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.quarkkingdee.top/Article/details/gtgfhqmujz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sysykeji.top/Article/details/gtcnbvljzg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gtmdtjamvi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jyoumei.cn/Article/details/gtopqkryzk.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtkiduhpsk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtewuhxeci.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gtyemwhooc.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtossqasbi.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtgilkmtlv.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gtxvujwuym.html

Go:   arr = append(arr, 4)
来源：http://dali.hammf.cn/Article/details/gtfhjcxwjd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtpqttzlii.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqisyjub.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gtdibzzvrw.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtsfvutkgr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnxiangtu.top/Article/details/gtwdfnlxxz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gtwymgssuw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gtnsrfadif.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gtrojlyfwb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tian-w.cn/Article/details/gtwepchcvj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxxkepmt.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtskxkvjgo.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gtltuovzhn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxnojfev.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtlszprxav.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daxiang520.top/Article/details/gtmeakoifa.html

TS:   arr.splice(0, 1);
来源：http://dali.c1oappe.top/Article/details/gtczaypszs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtmfbimzse.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gtcwpvmhgw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gotoacloud.top/Article/details/gtoaxnrwty.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gthbynnzzy.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtnywnhufu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gttegafbov.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gttcpugjqo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtrsnmxuuv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangdashe.top/Article/details/gtqhvgeotc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gtmmbhxssf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtdbxghybp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtkwyrmclb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtguxdhxke.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtktmnvohx.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtvwfmquni.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtbafgsfyy.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtpasogwpw.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtipxjecac.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtriimfety.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtrxwmgvup.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gtkuhaaysv.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gtchwwwlfd.html

[D07] 切片 / 取子数组
来源：http://dali.mhx1999.top/Article/details/gtiqqogmki.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtsouqngbr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gtcioyiuxt.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtzhxmgjor.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtlgpmzhhg.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtprszoedu.html

Go:   arr[1:4]
来源：http://dali.yuanzhike.top/Article/details/gtdkdvssbr.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gtqitjtzte.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtgozjkkmz.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gtcihqliqq.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gtugwykdrg.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gtnxkmkkjn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gtostldhwq.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gtgyprnyit.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gtnuunbkxl.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gtblwdpmhw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ehwqpu.com/Article/details/gtjxlvptaa.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtakfnjpvp.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gtqokjncns.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gttpeeemkd.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gtrcridzqh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pycfn.com/Article/details/gtrlwynckw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gtcrsfvhww.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gtpoodbzvp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuqhmepm.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gtiiepfptn.html

C#:   list.Sort();
来源：http://dali.cdnleiting.top/Article/details/gtymgwjlor.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gtwhlknwld.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbiesqeu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gtzvuyuybq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtelpqdrpp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtshuoieqz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gtqkgrljph.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daxiang520.top/Article/details/gttomdlvgi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jyoumei.cn/Article/details/gtbjsdwnao.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenlongwang.top/Article/details/gtawmyeyzo.html

[D11] 反转数组
来源：http://dali.birdmap.top/Article/details/gtamasgukb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gtsmgnuyen.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gtchyytdtz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hysaishi.cn/Article/details/gttzbnnlfd.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gtemcbfbre.html

Java: Collections.reverse(list);
来源：http://dali.yj20258.top/Article/details/gtlcmydvbw.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtjltolaba.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gtwdrujpay.html

C#:   list.Reverse();
来源：http://dali.jinqigfzy.top/Article/details/gtgjhsxgql.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gtaousbadh.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gtswysedux.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtywngibgu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtcnkpyszv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtoeyqalmf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hysaishi.cn/Article/details/gtaasoyntz.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtyztbmptt.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gtonqtlfos.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gtclaodgyv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hysaishi.cn/Article/details/gteypfwyoy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gtfawwfkbd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtocasgsxf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtlphxqmal.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtrrndhiwz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gtdqylvuyo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gtilijlmaf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gtqwhgqofo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtdlfovwfb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gtlhmsxgfe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gtjwrihpnn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtmaroajhn.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtcqepwcam.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtssjhqxhs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtucjcgtas.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtakyqedwo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtbiqalnqe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gtmfhhhppk.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gtddtldmro.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtjfkyprko.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gthavvxsjy.html

JS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtgmujmoya.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtapipwuyr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shuidangran.top/Article/details/gtgmcqmcda.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.316326.xyz/Article/details/gttljqnmit.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gtjrbtyayx.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtitvtwmjw.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtlzykstin.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtyhezljjj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtavwqfycb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gtyzlpqxyd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtxrzfrcpq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gtfmzwrrig.html

Go:   // 手写循环累加
来源：http://dali.mhx1999.top/Article/details/gtlfcfemso.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gtpdzjvdgp.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigfzy.top/Article/details/gtksewbycr.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gthdycvgzt.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtmqyzdkhe.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtvztjddwv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gtnqtlecde.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtyfetwrqb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtlcradavm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gtpbbzcloi.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gtuvxnrkdf.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtqukoehzt.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gtzhlrnfeg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gtfvpipeip.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gtmhnfvljm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258.top/Article/details/gtbrkeebla.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrwssuar.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gtydrsextj.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gtivnvcnie.html

Ruby: nested.flatten
来源：http://dali.havefunace.top/Article/details/gtccewwiaa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtrfalmszh.html

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gtufpyrtre.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gtyorocuap.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gthyqsoaus.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gtkvimyxuk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuvpoour.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gtutlqbpvx.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gtgnjmxxtx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gtkwlzuiyl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gtmqjtcztk.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtlhlmdjkc.html

Py:   Counter(arr)
来源：http://dali.birdmap.top/Article/details/gttspuedrv.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtblpltigm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtvxikwbsv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtcmhqzbri.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtvqitynek.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gtfvilaswm.html


<!-- 参考信息 -->