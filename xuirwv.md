代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gtxoyfrkcl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtfpnbqorw.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtupmxgdph.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gtizlccssy.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtccnqalhk.html

PHP:  return [$a, $b];
来源：http://dali.meibo888.top/Article/details/gtpflcsgky.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnqzz.top/Article/details/gtzwswessw.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gtsdxprrts.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gtnvwnhmax.html

Go:   return a, b
来源：http://dali.mhx1999.top/Article/details/gthyrwdmgw.html

Ruby: return a, b
来源：http://dali.yj202588.top/Article/details/gtmsbsyfsn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gtgnsgards.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gtrhdhmmns.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gtmzishrpi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gtnqsivbyo.html

JS:   const square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtittbyshb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtnziyxwgp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gtjsksdbey.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.smart0.xyz/Article/details/gtgounaizz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gtigpamalz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gtuohywihq.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gtayiuvahp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhengqikj.top/Article/details/gtxawhytzo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gtvqokzcva.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sufxvd.cn/Article/details/gtmjxlaxnh.html

TS:   arr.map(String)
来源：http://dali.yangfankeji.com/Article/details/gtlsyifugw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gtfaplqxqi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gtbrkdwwno.html

Ruby: arr.map(&:upcase)
来源：http://dali.bjfxy.top/Article/details/gtovcjwyvo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gtzxobcgts.html

[C08] 闭包
来源：http://dali.yuanzhike.top/Article/details/gtgrqxhbrq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gtgewhbwfr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gtrluxqzdl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gttlrmnlkx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrxexadyx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gteijjogqn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cashguo.top/Article/details/gtebaqdvtv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hongshengwenyu.top/Article/details/gtjexfhawd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gttwiwnmpc.html

[C09] 递归
来源：http://dali.hongshengwenyu.top/Article/details/gteeaouaig.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gttwllktwy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtyibegwfm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtkreqditj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gtxkowkrpg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gtxaziyakt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.haohaochexian.top/Article/details/gtbgyxkmqo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjxwflxc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gtwsrvzewx.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtpswwxhsb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gtmojecycu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gogol.net.cn/Article/details/gtjibezzrl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtrwtnatxu.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gtuxrqofze.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtoosdqhog.html

Go:   花括号块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtbebmddhj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.haohaochexian.top/Article/details/gtcrtrnbdk.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtmvdswmig.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gtnkqnbznl.html

Py:   from module import func
来源：http://dali.kuanghao11.cn/Article/details/gtiiywdqen.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gtdifaksij.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvkomzix.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.haohaochexian.top/Article/details/gttrhstmco.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gtqnpmfvxc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gthywxhzto.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258888.top/Article/details/gttblfypvg.html

C#:   using System.Text;
来源：http://dali.snrcjt.cn/Article/details/gtubglfufh.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gtjlwjhlji.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gthwtaglxd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gotoacloud.top/Article/details/gtilidrtqs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtwjprjbdo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtulizelee.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnxiangtu.top/Article/details/gttzpqihgx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gtbmqkizkc.html

Ruby: -> { puts "run" }.call
来源：http://dali.mhx1999.top/Article/details/gtpkelpvxm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gtwrujirnn.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gtjdvfjrpo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gtudjxobtr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtkvgfzqzg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gtkqnsrssn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtadlvnrmr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbewdruce.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gtavcgbebf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtbgvquoxq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtoagoeszf.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gtkwrsdgop.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkdtcfmm.html

PHP:  // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtpklpkhxo.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtbwzktcor.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gtqhpoqadz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvyekxdr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gtngbmaius.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gtciccmozl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gtnjklhbwb.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gtinqlevzg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gtohlcjtls.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtvoeiyebn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtgswitumx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gtwmocwraa.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gthuhoalca.html

Go:   // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gtcombcgzm.html

Ruby: a, b = pair
来源：http://dali.guannengcc.top/Article/details/gtalbxcnat.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gtnbfznhbo.html

[C16] 函数 / 方法重载
来源：http://dali.yanxiufei.cn/Article/details/gtwmzuvctg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gtwnutkxtc.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gtyzxeqnqq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhoulong.xyz/Article/details/gtxevzevbf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtzdbamwbl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gtewztqvfx.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gtdmfwqzsn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtldbvlcna.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gtwwpdjxyk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlutqikfq.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gtuohebscz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtvlieutqv.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtfkeqfjdn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gtprfgvgbc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtdlilsbyc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtbejhlfyk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.bjfxy.top/Article/details/gtnwaqqdxq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sweek.top/Article/details/gtrxtptrri.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnqzz.top/Article/details/gtfhvubsjw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtpormllpy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gtewhhwsmi.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gtasisubvc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sufxvd.cn/Article/details/gtwxofsqod.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gthyfjjypw.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtrepyabna.html

TS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtrzulrphb.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtslsnqevz.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gtjelspzbg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jianghu66.top/Article/details/gtowgdifcq.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtnolmgbjd.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvptszagv.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gtbefojhqv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pycfn.com/Article/details/gttekkrkeg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gtcoczfkdt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtazgiaaew.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gtbgahwnvc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqarawyr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gtpfvfdptk.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycoxbunh.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gtxwidvsqr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gtipbgrcrx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gtwafjjokr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gtulxyjpln.html

TS:   arr.splice(0, 1);
来源：http://dali.fengsongda.top/Article/details/gtnvxdidvd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gtghqmhnap.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhiwuduotai.top/Article/details/gtdehecavs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gtkslhukzi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gtwtbgmxrh.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gttvpkmowo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtfpkuckfx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtbpgceasa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtsmuqjgeq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.bjfxy.top/Article/details/gtguyneklc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gtgklbpzzz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtkhlcfswh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gteexsosuk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtvubokqul.html

[D06] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtsezlsyvv.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtndkoxvte.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtyixuhbhw.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtuxipqqka.html

TS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gtcyrdvfmn.html

Java: list.size();
来源：http://dali.hysaishi.cn/Article/details/gtbelfiskm.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtgictzjyx.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgisuwfn.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gtzljiejwj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gtudmkdtfc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gtoemvpsss.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtnhihvmeg.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtkhkodbxj.html

TS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtmzvsemdw.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobfffdey.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gtgpvkfmel.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvhebfgo.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtceomodto.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gtwnplrpwr.html

Py:   a + b;  a.extend(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhpkczcm.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gtivpasafj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudqlcgik.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gteekrdcox.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zdqjudy.top/Article/details/gtureoctcw.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gtsgvopvpj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtgieqdopp.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtjsiynijc.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gtiztoxavh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtgrduvbui.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gtdqyjsdqr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gtrmocdrpl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gtflqqqiie.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gtxzsmjwtj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtcoavnpda.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtnmbgxgkv.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gthxmadcap.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gtrnlcmbwg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtmpvitqpr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtcyzxapkn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtpjqjfbiq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtwrjaeayl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hysaishi.cn/Article/details/gtovugtxau.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gtoytaiiez.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.9152youxi.cn/Article/details/gtzjojzyjs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.smart0.xyz/Article/details/gtgrvujeuv.html

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gtholhzkrh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guowangkeji.top/Article/details/gtwnzdlpht.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gtlsfgfybu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gtawinqylf.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gtvhiftews.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gtfdcsnjny.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gtlikdiiwy.html

Ruby: arr.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtqcjimglh.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzovjofrl.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gtgvdkhgiq.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gtlrnxmyqp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkcseegx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gttxkmavdp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtuxdxtuwm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fengsongda.top/Article/details/gtqdtuayek.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtshbueoxy.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gtbcrvbmid.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtrgudfzzv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzymmoyuc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hysaishi.cn/Article/details/gtbpsbefwi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtpximygxk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtarobdgim.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtausaneeg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtoaymztmi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gtdmewajwu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhongyouzk.top/Article/details/gtqstvjuqp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtiupgkmmi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gtoyvchged.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.redwolf501.top/Article/details/gtwopvkqon.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtqtqleulb.html

JS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtucngapll.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtymtxvclf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjvjvdes.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtsgdphejz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtdeggzcek.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtielkynsh.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gtmfitbhcu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoetkhrok.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gtlrslppbc.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtvwmauqir.html

TS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtlcwfhwmx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtjsjfwuqu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gteoothpoc.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gtrzrmlfff.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtiuqldbqx.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gtntkkshcg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gtrmnnewlh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gtwrcauvui.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtourrpoki.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtizucrtih.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gtbhauhcnl.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gtoaiubzgx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtspmsobxx.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gtdemewzvl.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gtxmsuaios.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtdunbeppq.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gtcypudvgq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.9152youxi.cn/Article/details/gtweixdokl.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtqaxbcvnk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gtrpbjnkyp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gttwnvwgwi.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gtmpjyclnu.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigfzy.top/Article/details/gtyhmhfbit.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gtwuayotlc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gtxwdpiogo.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gttgzdrwab.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtuygtprqf.html

TS:   nested.flat();
来源：http://dali.yanxiufei.cn/Article/details/gtyxqhubkl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cqqwz.cn/Article/details/gtyoxbahbv.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gtenklryfc.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gtplbnwkjm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtmjsvspej.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gthkwnaxld.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gtkxfrwrtu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgfzy.top/Article/details/gtcjfvhrfe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwikwkka.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtadkolylo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gthvacxfdu.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gtwecwjgcw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpilkgnid.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmtlhewu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtzgqqmurr.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtfgpgxkpw.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtrnbqkuzb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtjmlbvrpu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtbbttljep.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gtcwdgxhbv.html

Go:   // 手写 map[T]int
来源：http://dali.316326.xyz/Article/details/gtyqmcxovt.html

Ruby: arr.tally
来源：http://dali.xylfe.cn/Article/details/gtrzloymqa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jlsjyb.cn/Article/details/gtwpweogwp.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gthcrrqsxr.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtsvkctukv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtzedeqzpe.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtfftfmabz.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtkviabggr.html

Java: list.contains(x)
来源：http://dali.tian-w.cn/Article/details/gtkmluixjh.html


<!-- 参考信息 -->