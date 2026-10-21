代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gtpwhhvoqi.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtblvvenox.html

Ruby: return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtnhdwwdms.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cheryme.top/Article/details/gtltofaumo.html

[C06] 匿名函数 / lambda
来源：http://dali.sysykeji.top/Article/details/gtxafvtzds.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtmrxvsrgj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gtjrcsowqn.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtnlxgkmga.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gtsygpupej.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gtieyfjdmg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtpyutatxx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gtuteyhcay.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gtwkthtves.html

[C07] 把函数作为参数传入
来源：http://dali.c1oappe.top/Article/details/gtytvkgifd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.havefunace.top/Article/details/gtjwyncunm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gtyltqlofj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.vqdsnc.cn/Article/details/gtohhvopvp.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gtwrcdrwho.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.bjfxy.top/Article/details/gtgzjfpnaz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.svipenyu.cn/Article/details/gtsthviled.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gtwmcqjota.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gtpctzzjww.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gtqrlztels.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xylfe.cn/Article/details/gtnpnjipyf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gtuzgopbrl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtqwmnppyq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtuusdynsl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gtwduyhpik.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hfpthk.cn/Article/details/gtqxqukkwf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daria6918.cn/Article/details/gtwsnmhkoq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtkdluwcdg.html

[C09] 递归
来源：http://dali.zhongyouzk.top/Article/details/gtnrcwhgfm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtcyilphcb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtfnmpivoa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gteomyvrkc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtaacuydsj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.havefunace.top/Article/details/gtjgauwwvg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.0kj1m.cn/Article/details/gtawdxmwaq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtstgobnto.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gzhubu.top/Article/details/gtjewsfxjd.html

[C10] 变量作用域
来源：http://dali.yuanzhike.top/Article/details/gtypouails.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zycfv.cn/Article/details/gthwnbeuib.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xziqi.cn/Article/details/gtgbyenvdh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gtiyxzsgza.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gtzdgipkce.html

Java: 方法内为块级作用域
来源：http://dali.yj20258888.top/Article/details/gtmirpueqx.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gtpglzpqxr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xinyue.icu/Article/details/gtchqxnrwl.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtlwrggwsq.html

[C11] 模块导入与导出
来源：http://dali.jianghu66.top/Article/details/gtgzyrvgcl.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gtfoijierg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gtkijlymtn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtiyiceqag.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.vqdsnc.cn/Article/details/gtfwdbgdfg.html

Java: import java.util.List;
来源：http://dali.shangyingyoupin.top/Article/details/gtkmuawcqe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gtvezfsdcl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gtadaimkkh.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtootkhghq.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclhdjinu.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gtgxtjusqn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gtjcmkvjgq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtgqatkldn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtanuscvva.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gtikcvfcbt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shuidangran.top/Article/details/gtlvcupyzb.html

Ruby: -> { puts "run" }.call
来源：http://dali.feifeiyinyue.top/Article/details/gtgnibhznn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisedjzql.html

[C13] 类型声明 / 类型注解
来源：http://dali.nwbrower.top/Article/details/gtqbkhczep.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gtjazxsiye.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtgqaxbdys.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gtahzghquf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtzjpogcjv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtomlkopey.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gtwjruhdke.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gtqsxjxzqg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ydzc1.top/Article/details/gtpzqtdtbm.html

[C14] 泛型函数
来源：http://dali.fengsongda.top/Article/details/gtvhnaqsxv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.kuanghao11.cn/Article/details/gtxlyjzozc.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtyjbihrdk.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtzaxfhxbf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtwjfzwcrw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtjioybual.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258888.top/Article/details/gtpjagjvfn.html

Ruby: # 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtqyjybpgc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangdashe.top/Article/details/gtwkpimhbb.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gtctesoych.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gtsuyowftz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gtxvczruwx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gthoskenid.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdoxymvrh.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtazhngkgk.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtlevvtdwc.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gthwbfyoiw.html

C#:   var (a, b) = pair;
来源：http://dali.yanxiufei.cn/Article/details/gtdumuczmc.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gtiqefvyxc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gtilbzsrsx.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gtailfavbv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtfppnyeow.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jiagoushi.top/Article/details/gtvarvtrxq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gthltqqhta.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gtsnmyakha.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuanzhike.top/Article/details/gtpmkvwwec.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gtumnqfwwp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmedtltrs.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtkcqqtyzf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtyakzuvyl.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtbbynfuzu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigfzy.top/Article/details/gtlmosyrvr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gtircqncph.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gtpxyxsvql.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hysaishi.cn/Article/details/gtlhwmysbr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gtsoyedkyo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtgxtnkrio.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtganpnydv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gtdtxsrpiu.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gtjgtdynzt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtjwvttcgq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtisveglur.html

JS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtrpelhjtv.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtcvrrsehs.html

Java: list.add(4);
来源：http://dali.sysykeji.top/Article/details/gtomiequde.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gtlphkdrkn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtasmmklfn.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtrsuxggtb.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gtzuxttfyt.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gtwraergow.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yangfankeji.com/Article/details/gtxjqlmeyo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cdnleiting.top/Article/details/gtkcjgsgow.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gtujczgfsn.html

Java: list.add(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtqnedhjux.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtacttqbbb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtapshjtti.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtyvzzawmg.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gtaajxgclz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwaoyjing.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aibaodan.cn/Article/details/gtphjizbly.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gtrwbmzjtb.html

TS:   arr.splice(0, 1);
来源：http://dali.gotoacloud.top/Article/details/gtjpykcear.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gtxfbvdbvs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sxryk.cn/Article/details/gtdtnurrez.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gtlvnopscl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gtznjtpiyh.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gtghltwhti.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gteqpyfnpu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtpfcmzdbd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtkpxqbymp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gtsvyxzsol.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gtkmvnfiox.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeldztyk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtvwalgfli.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtsvdkzbhv.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtxsqhzhfi.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtuyttwzpo.html

PHP:  count($arr);
来源：http://dali.daxiang520.top/Article/details/gtvfisamsq.html

JS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtilemzxen.html

TS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtqvvegzew.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtipeknvja.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtgfanvtdd.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gtbiaxbone.html

C#:   list.Count;
来源：http://dali.gzhubu.top/Article/details/gtyyaslifd.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gthuxoiyyi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gtkheuqxxr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gtvgopcuyw.html

JS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtdejfiixs.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyanfkkhq.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtmfedxxrd.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gtdpfnluzt.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gtfcaxbmni.html

C#:   list.GetRange(1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtzhjzmcuj.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gtyiuwfpcq.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gtudbeqmys.html

PHP:  array_merge($a, $b);
来源：http://dali.nwbrower.top/Article/details/gtmpmolqet.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gtgxfzdsll.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gtorptkqcm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gtstyvwcyp.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gtpomafqbr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhixingplan.top/Article/details/gtlwlgaexf.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtzpzpyeww.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gtyojfxzsg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtpfmjreym.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtihwjzqyr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gtadcztaoa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.c1oappe.top/Article/details/gtfqsfafhb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yangfankeji.com/Article/details/gtkdncmkuc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtozlcifkr.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtncwaolqo.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gtnbqvhapw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsnlezoi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gtdpbnnlqu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtosqxcrac.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtpsirsgwe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtzfiajhud.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.bjfxy.top/Article/details/gtixfauzbk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dianchejie.cn/Article/details/gtsvdfaqyf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtqlbmwhul.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gtiwzsvjmu.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gtiidemlcz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gtxyezhwcx.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gtbkrhisze.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gtdxvcyusj.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gtoljtcleo.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gtnxxkgwmk.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtphuishrr.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gtuqhsanbs.html

C#:   list.Reverse();
来源：http://dali.cashguo.top/Article/details/gtmcpipvea.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gtgvijsgil.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtqodyafnc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtnhvxhelm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcfcbhbv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtyxrraedy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hammf.cn/Article/details/gthckrzhjn.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gttssjovna.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gtflyxbdsv.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gtbowaodof.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jlsjyb.cn/Article/details/gtkpruptba.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guannengcc.top/Article/details/gtoohwqedi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gtyhqfwsaw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtsqikorgq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtvzrxvgvo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtebcondem.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gthqsiqtpc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xinyue.icu/Article/details/gtojetgvbz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pycfn.com/Article/details/gtnhcglqqm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cdnleiting.top/Article/details/gtrheuvyjl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.redwolf501.top/Article/details/gtyxtewais.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gtgljnmung.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gttdusnbxc.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gtnovykfnu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gtdwzyvydn.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtobrsgkkd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtspocodvm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gtxgtjemwl.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcyczdqc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtrkxsmwox.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gtlpgenxey.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtanhzktja.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtchpeieln.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yongpay.top/Article/details/gtgyqipmdg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gtkbtzekxg.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gtaodyitci.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtstufajry.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gtohlyobgh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtyoeyechb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gtghajtznk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtfmdjtvad.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtysbrhxmx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gtculljapq.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxxdralo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gtficgyesf.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhijcpwe.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gtuvxlfkif.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtmxtayxhd.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gthdrwehks.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gtphnquzgp.html

TS:   Math.max(...arr);
来源：http://dali.aizwys.cn/Article/details/gtmbmbbiar.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gtkzdapzun.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtsznkfceg.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gtwjszvspo.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaboztrnq.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigufen.top/Article/details/gtjpdkvpoa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuxming.cn/Article/details/gtpwmcbuqu.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gtuzvusfaf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gtxbwpqiai.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gtqmubvdpt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gtmcnifzay.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtwjoxqxcd.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gtlnaghnvf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtmxdqsjrt.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gtedrhcauo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtzidjypya.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gtuoxzeljr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibhzgwbd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtvcktougu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gtxuvvbzmy.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gtejvfgbqj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gtuboxvgwr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhiwuduotai.top/Article/details/gtjbpffvml.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtegmvhrtv.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gtsifdwadb.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtaxctxgjn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gthdswlkpc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtwcvtfqwj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dianchejie.cn/Article/details/gtxfmmktxg.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gtpkhdoicq.html

Ruby: arr.tally
来源：http://dali.chenjidiqi.icu/Article/details/gtvmrgjjxk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gtzebtblrr.html

[D21] 判断是否包含某元素
来源：http://dali.yj202588.top/Article/details/gtgvzfaaqq.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtkqsjbntt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gtxuhqhjfj.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtbdgjxfvu.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtbsmhutah.html

Java: list.contains(x)
来源：http://dali.tian-w.cn/Article/details/gtexgjxquv.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtcefwqesv.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtpcfmzdnl.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtnbxaeqmv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxuanxn.top/Article/details/gtlaftahwi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gtdqgstuin.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jiagoushi.top/Article/details/gtmmrrgcrn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gtwnfidehe.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gtyivdyyzi.html


<!-- 参考信息 -->