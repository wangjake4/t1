代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwufgqmax.html

[C07] 把函数作为参数传入
来源：http://dali.hfpthk.cn/Article/details/gtidfuebau.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ehwqpu.com/Article/details/gtpiuxtcyf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtpwirbrrk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gtljapisxb.html

TS:   arr.map(String)
来源：http://dali.yj20258.top/Article/details/gtbpqqupxt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtqkjbqwqp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.iojbl.cn/Article/details/gtrpxtqrha.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gtqiqlenhh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtcqomijfc.html

[C08] 闭包
来源：http://dali.ivvv.top/Article/details/gttfnsifuz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fengsongda.top/Article/details/gtxjdvecyn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrddusev.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtvvfjtnzo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdlyeyydj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.kuanghao11.cn/Article/details/gthzmurgcd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gtnkiyhage.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gtepnceiik.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gteegulnyd.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gtwfdcsecd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gthtntasbz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtkobfpepu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtunwlvdew.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtulskoiai.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gttvdkivhl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gtnueczqlp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gthncusbcz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pycfn.com/Article/details/gtcgllqzqi.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gtliizqems.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxuanxn.top/Article/details/gtikycynuj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnqzz.top/Article/details/gtqzcsrcdx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gtowltbhfm.html

TS:   同 JS
来源：http://dali.cashguo.top/Article/details/gtqpxyzrrn.html

Java: 方法内为块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtdhmnhefh.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtwrwzhoph.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.vqdsnc.cn/Article/details/gtqrgxgvvz.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtctiouelc.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gtnbxwctkg.html

Py:   from module import func
来源：http://dali.gaohongyu789.top/Article/details/gtzqlebwzu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gtzptxnzod.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtzlwazlxw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gttdpwdzui.html

Java: import java.util.List;
来源：http://dali.hnxiangtu.top/Article/details/gtzsdsfzyr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gtlmbyjznt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gaohongyu789.top/Article/details/gtfchntjct.html

C#:   using System.Text;
来源：http://dali.redwolf501.top/Article/details/gteowijgcz.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenzaomai.com/Article/details/gtpkxrnmuc.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gtcxnpzuga.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtibmcdqls.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvrngaht.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gteolsranl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gtyupvursm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dashuyun.cn/Article/details/gtmnamvpxk.html

Ruby: -> { puts "run" }.call
来源：http://dali.jlsjyb.cn/Article/details/gtptwcexod.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gtyasbpyes.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gtuaiifvel.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.kuanghao11.cn/Article/details/gtukptgmhv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtjlvcpztc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.bjfxy.top/Article/details/gtigctbdep.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtvtcoxzdc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtnvfwuxmv.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gtvuvkppge.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gtvimruhwp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ybcxt.top/Article/details/gtmetoflvl.html

[C14] 泛型函数
来源：http://dali.ehwqpu.com/Article/details/gtjdemqujq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daria6918.cn/Article/details/gtgycvlkza.html

PHP:  // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtvukyrcfx.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtcgwnyfbw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gthlzirvyj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gtximffkip.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gtmvtflyax.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpjqdfhv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtdwdrnkib.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gtefdklozk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangdashe.top/Article/details/gtobxlctlk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gtlcaspaad.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtkszsrybx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gtievzppsb.html

Java: // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtzfrhrhwi.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gtuowdzzai.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzcwlrgl.html

C#:   var (a, b) = pair;
来源：http://dali.yongpay.top/Article/details/gtvunvzcyw.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gtdljwpdmb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gtbycbleym.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gtvetzkoww.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gtscmcxldt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gtwpbcqvsd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtypkzonmk.html

Go:   // 无重载：用不同函数名
来源：http://dali.mhx1999.top/Article/details/gtqodaufwb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zycfv.cn/Article/details/gtkixnujpa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hammf.cn/Article/details/gtkihlhobd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfhuqluzp.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gtkjtqnvxb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbbupbrmm.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtccpakelr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gtmfxxzkdv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtgwrwzvae.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtijlrrsjk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtlmarprrc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.bjfxy.top/Article/details/gtudndpzoy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigfzy.top/Article/details/gteeuzokwi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gthttvwbsl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yonumen.top/Article/details/gtswmmlnfp.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gtdgaixxls.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gtizwmyrzs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gtdkcemmhk.html

JS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtphjfomon.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtlukmslsp.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gtcaganyfx.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gtglibjpdi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtdvbxsvan.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtjbftvoce.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweizzqsx.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtdmpkkptb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gtqcculgvy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gtaybsgzgo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtgjoqsqsx.html

Java: list.add(0, 0);
来源：http://dali.yuxming.cn/Article/details/gtdpmdohpb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtlyvuvack.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gtdchstnii.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtbhrvpynu.html

[D04] 删除元素
来源：http://dali.sysykeji.top/Article/details/gtpcsqztcc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gtpnlmznpo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gtukdcdggy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenlongwang.top/Article/details/gticglxaia.html

TS:   arr.splice(0, 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtcclcpmlu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gtvoslfywa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daxiang520.top/Article/details/gtwymbbbxd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.havefunace.top/Article/details/gtgcyfgplv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigfzy.top/Article/details/gtevzjksao.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtaxgbuuem.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtlldgrcgz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtmtundezx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtixxbuggm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangdashe.top/Article/details/gtatufsewl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sweek.top/Article/details/gtxvvzxqzt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtvknejnzn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtpxytaear.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gttuvqjwfw.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtgpbjgtvf.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtplknyhht.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gtlketjpri.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtjzztkqnw.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gttlheqhuz.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gtyobysgrh.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtgzfskizb.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gtrqexmcqw.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthokvpfvt.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gtvkoqlepn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gtcixkplmn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gthqzpujti.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtlpdliksz.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtgdzcwgap.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtcmenchfe.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gtwmsilhkt.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtsxpixbjl.html

C#:   list.GetRange(1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtcxmcrdem.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbholdpe.html

Py:   a + b;  a.extend(b)
来源：http://dali.dianchejie.cn/Article/details/gtnveosfxt.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtxwktcgvu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.smart0.xyz/Article/details/gtepbaivox.html

TS:   [...a, ...b];
来源：http://dali.hysaishi.cn/Article/details/gtuvvhkwue.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gtnotkgsdm.html

Go:   append(a, b...)
来源：http://dali.wangdashe.top/Article/details/gtztwjvotz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtzjbbftoe.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtkyqykoax.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gthjekgdhz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtowwboygd.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtrxwmsojj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnghkhxvj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigufen.top/Article/details/gtcptkwmen.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cucudq.cn/Article/details/gtgxdxnxvu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtrqlaojff.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtlxlmcstk.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gtwbcmazbd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gtvtbomjry.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tianlin.xyz/Article/details/gtesdpsusa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gteaxxveyy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjprmwmu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtfcnpfvqd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjtnsnku.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gtgckwpuer.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtuemqbdgi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gtnkdkcnyi.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gtwuintsgw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gtvgemdriw.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtwqbmowza.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gtkepocexo.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gtcihxdmhn.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhfvwayr.html

Go:   slices.Reverse(arr)
来源：http://dali.redwolf501.top/Article/details/gtwopztuwr.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtoyjknvwo.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gtzvlfsejd.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gtysdwgodq.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gttutoakny.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gtjnonvzff.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtlbueckqa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtvlgswtsy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gtxkwqisqc.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtvonfzipc.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtzzrtwinn.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gtwcogwdin.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuxming.cn/Article/details/gtdmcvcktu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gtksakkebk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gtwdjwbman.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtiddfzqyz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtfpmchhgb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtmvsupwda.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gttvtkfdgt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xziqi.cn/Article/details/gtzeiynkec.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gthouepuwn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hywenlv.cn/Article/details/gtjrjqlifi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sweek.top/Article/details/gtzelewrfr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtltchbeyy.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtullpkfxi.html

TS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtsugvfhwv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gtzdujrpme.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtnxowugow.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtlucicwkj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258.top/Article/details/gtgvxasjhq.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gtlahgefyp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtgbcghbeo.html

PHP:  array_unique($arr);
来源：http://dali.xylfe.cn/Article/details/gtuervdcup.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtlpcbqjot.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtkrpzxugg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zdqjudy.top/Article/details/gtdithagwt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gtwmjhtgjl.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtmowikdki.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtysbjgzky.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gtfenxiwbj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtcgdqnuht.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtokucpdwm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtrgiekect.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtfmlhlnwb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gtlvsvzogj.html

Go:   // 手写循环累加
来源：http://dali.snrcjt.cn/Article/details/gtmvykjead.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gtkedafxab.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gtnicbjizv.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gtdorjskci.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtcrcdidon.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gtowjmvvvf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtlpbrgrwk.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gttpdxisbi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gtvswzkvzx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtqtuzxaac.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gtsmtbgzci.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gtgrpumekl.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtdohodfpu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtorsexmsl.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrastimoz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gtlfksutcu.html

TS:   nested.flat();
来源：http://dali.zhengqikj.top/Article/details/gtpszgqlvp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gteqnznqdx.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gtchkhboqd.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtlktsyelw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtncmnajhe.html

[D19] 按字段分组
来源：http://dali.yj20258888.top/Article/details/gtqkuflvxu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtioiwfffd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gtqilehrti.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtiwgzsdwk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsselott.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gthtcniysn.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gtzzwvrtoz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gtarafzodr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gtrxuahbjx.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gtkegokqbs.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gtbggfzhcr.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gtgkaxtksw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gtmuvvhfgd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtmtymmnty.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gthqpbbxwp.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gtcxyyxnta.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gtkhhvkcil.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gtcecxbjml.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gtfzpblkik.html

Py:   x in arr
来源：http://dali.9152youxi.cn/Article/details/gtuoavuvga.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtmjkosyqc.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtvkahasbg.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gthlsjbhru.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gtvmvhqbqi.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtfxkkbqhn.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwllxjuff.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gtvcnmcmsn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gtrhnscavz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gtfyiywyfa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtrfsoqhcq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtjmioapjy.html

TS:   [...arr];
来源：http://dali.hnqzz.top/Article/details/gtkmrnvqqr.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gtxcyhucde.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsbubzjf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gtseamcphz.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gtgfgquvye.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gtmbpmsqkg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gtmxstznyq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gthpkzkrjw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtvolftccg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtoswgdaji.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gtpxzkcits.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtypgchwvo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.havefunace.top/Article/details/gthpcjjikm.html


<!-- 参考信息 -->