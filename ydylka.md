代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.sufxvd.cn/Article/details/gt2kiwwdose.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfjkurnp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gt2bvqpylsx.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gt2rkyoswqe.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gt2lrshduls.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258888.top/Article/details/gt2dgmrzixh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwwsunqz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gt2ptekvkak.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksqmzmsp.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlnwtjc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gt2ohytzbjp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2xnbowlzz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gaohongyu789.top/Article/details/gt2xwwnglvn.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gt2ebtqplab.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gt2bbzltqcu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dianchejie.cn/Article/details/gt2uniqxovr.html

Ruby: arr.map(&:upcase)
来源：http://dali.jyoumei.cn/Article/details/gt2rdxlxciv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aibaodan.cn/Article/details/gt2asrmpott.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gt2jykzoebx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gt2mxxfmjgq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhengqikj.top/Article/details/gt2axwnqemf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2onkhxgoy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gt2yubjezig.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gogol.net.cn/Article/details/gt2yldfgwrg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xinyue.icu/Article/details/gt2vqryrpgo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.haohaochexian.top/Article/details/gt2itwyyeei.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2hmdtgnmc.html

[C09] 递归
来源：http://dali.zdqjudy.top/Article/details/gt2zdankzqn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gt2nnbnhxpc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gt2cioizqqy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gt2kuawwfth.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gt2tyypehyp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ivvv.top/Article/details/gt2yyptbppy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmvyywmk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jeaiwqbw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhongyouzk.top/Article/details/gt2tjvnhmuf.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gt2lpaxmdcn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gt2rmpsdlhr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gt2dybzbyxe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdeznqvv.html

TS:   同 JS
来源：http://dali.c1oappe.top/Article/details/gt2vlpeyijw.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gt2odpofqyj.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gt2dgaqugyy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.andypj.xyz/Article/details/gt2aowkytou.html

C#:   块级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2uwajssnt.html

[C11] 模块导入与导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwtwhogl.html

Py:   from module import func
来源：http://dali.zycfv.cn/Article/details/gt2hwbmpbla.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gt2oeykmkoy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gt2xlybcooe.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gt2udxwuaru.html

Java: import java.util.List;
来源：http://dali.kuanghao11.cn/Article/details/gt2dtveaxhq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnqzz.top/Article/details/gt2yepaqxhn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gt2bjixnxdk.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gt2rdtqpdyf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gt2bvzdcyzz.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gt2gfpqywyb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gt2khdkcmrk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gt2nahjlpvy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gt2wngaojgx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.snrcjt.cn/Article/details/gt2umukwbde.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dggjfsqw.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rlqfenje.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigufen.top/Article/details/gt2nzlnfonq.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgufenzy.top/Article/details/gt2okvviakk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gt2ssbhzbmc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2rlulzfxa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258888.top/Article/details/gt2zzcpuqbt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2qeecmvtu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2deieqtye.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gt2oiiwkzjg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gzhubu.top/Article/details/gt2vinpleay.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gt2blsexjcr.html

[C14] 泛型函数
来源：http://dali.yuanzhike.top/Article/details/gt2emyxazsu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gt2gpsasalc.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2srtstqbr.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2bdzljtau.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wqbfmpwj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258.top/Article/details/gt2gapsecao.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gt2lpncqcxk.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gt2fsvmrvma.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gt2yhkfdkgt.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gt2inmogbdk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gt2pepuwqsa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gt2bezkfdri.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gt2ldxmthoy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcssynyb.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gt2plwlsjpt.html

Go:   // 无解构
来源：http://dali.wangdashe.top/Article/details/gt2ttrpanev.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gt2iyvflwez.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gt2bkbglgfo.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gt2ytgcqfdx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2usrqbejk.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gt2dawzdwge.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gt2zhapghfo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gt2baiawfey.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.iojbl.cn/Article/details/gt2zcmeghjj.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xaduxkps.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yueranfly.top/Article/details/gt2byonhcyn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsojoxkk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2jmtvbtng.html

D. 数组 / 列表 / 集合
来源：http://dali.cdnleiting.top/Article/details/gt2kmfkpdpo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ocihzogm.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gt2dukahmiw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gt2eodpwxhc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bknizfjc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gt2ewkdqyji.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gt2oxdjpjzp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbmimnqj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gt2yszaeqwg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gt2wahrzwaf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gt2znkkgvdo.html

[D02] 追加元素到末尾
来源：http://dali.c1oappe.top/Article/details/gt2lohsdoga.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gt2ydqlktbo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2xewzmepf.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2qsmapedo.html

TS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gt2msmdntro.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gt2jcdmzrec.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gt2kdvfawso.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gt2zhcvnokk.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gt2qgdcrega.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gt2wujrjjrt.html

Py:   arr.insert(0, 0)
来源：http://dali.sysykeji.top/Article/details/gt2xdmjgyhv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gt2jzaifkjc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gt2inrnejsh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2yobsvrfj.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2heeemnxs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gt2mmmfgqct.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gt2ojqnbuqq.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2agxcgglh.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gt2odtofzpt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gt2wfvdvnld.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gt2qtzsevar.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gt2qtrbliii.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gt2fvblxzqy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2tbhsqiql.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gt2ylzhpstc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2bdovudfn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gt2mncruexd.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gt2ogzngjtx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2qpfdljle.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gt2fpdibehv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gt2hfocyhdf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gt2mgymasxw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gt2qruuyshg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2gjkmkzxy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2theawtta.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gt2amwomebb.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gt2gnvuxbbb.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gt2fvgziiyr.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gt2kfuamlys.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gt2ubytbcsn.html

TS:   arr.length
来源：http://dali.hammf.cn/Article/details/gt2caylhyce.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gt2xexpcrqd.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fylrddbz.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigufen.top/Article/details/gt2okgmjcgt.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gt2dsepnidu.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gt2ynodtquu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gt2wbgdkkyn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2rsrsqqcz.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2ajwabktk.html

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2ojszupnf.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gt2ejsjlcsq.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gt2pnxfmdca.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2burhpxiz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyncsfka.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywqkijws.html

Py:   a + b;  a.extend(b)
来源：http://dali.xylfe.cn/Article/details/gt2vwilgcnd.html

PHP:  array_merge($a, $b);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhpeygjt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gt2swfzrfxj.html

TS:   [...a, ...b];
来源：http://dali.yongpay.top/Article/details/gt2ldlqxsmz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxvieikb.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gt2qoswdylj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gt2jlugzrow.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcegepli.html

[D09] 排序（升序）
来源：http://dali.haohaochexian.top/Article/details/gt2rqfwoqnb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gt2qgmgirju.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hesykuli.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fzhhl.top/Article/details/gt2qqbicchs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gt2mrzvlvle.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dashuyun.cn/Article/details/gt2qfanhwxv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxzfwldm.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2oihousbk.html

C#:   list.Sort();
来源：http://dali.yj202588.top/Article/details/gt2ovrttrgr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkhsnsvv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gt2odyjspqh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gt2xclzhlbl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gt2yzjhqbgi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gt2rljjidvw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jyoumei.cn/Article/details/gt2rnscndco.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hongshengwenyu.top/Article/details/gt2witbgtqn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gt2bwbghccx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhixingplan.top/Article/details/gt2uzuxkjom.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gt2rkvloili.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gt2vusjwdao.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2kuloaezc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenlongwang.top/Article/details/gt2ozfyrguw.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gt2ymoabfut.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gt2hopxvmxj.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2xolyyviz.html

Ruby: arr.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2zevzhxxm.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdpwpzla.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gt2huprqaqw.html

Py:   arr.index(x);  x in arr
来源：http://dali.sxryk.cn/Article/details/gt2wjhyjctg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gt2tfzpogfa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2vtkgzlkg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gt2dkelgwkl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gt2czaazmrc.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2ipfjwncj.html

Ruby: arr.index(x)
来源：http://dali.yj20258888.top/Article/details/gt2vpusztbw.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gt2wfwdufbf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gt2ctyhwnum.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gt2enpjvzkd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gt2yjiohcom.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gt2qchgdrqj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gt2xgmnmbxt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2mfwrjbkn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gt2qbdjpzfd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gt2flceksli.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwizmbuf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gt2ulogxzpt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjhlgid.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhaqxlht.html

JS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gt2stzsapsd.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gt2wiuqmplv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2ccjwcrut.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gt2cuvygyxj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2grdmwoim.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2pojuqwty.html

[D15] 去重
来源：http://dali.guowangkeji.top/Article/details/gt2wbkoukqh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gt2sndrdexv.html

PHP:  array_unique($arr);
来源：http://dali.sweek.top/Article/details/gt2xwbjbvnx.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2ukvtabdw.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gt2dieztrbt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.iojbl.cn/Article/details/gt2tpoyttun.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gt2vmmctqkt.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gt2zxzenqzn.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2xowhuhug.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gt2qfgebggm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gt2lrrfisky.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2vldxqdai.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2cggrbhpv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gt2pgohjcuq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gt2gfpirnyz.html

Go:   // 手写循环累加
来源：http://dali.jqgfzy.top/Article/details/gt2uypapoyy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gt2pueohada.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuanzhike.top/Article/details/gt2ghvytsfw.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gt2vftyvffz.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gt2houmpjlk.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gt2cdyymwac.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gt2vjwicywy.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gt2vttcpeha.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gt2kixxexwy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.andypj.xyz/Article/details/gt2ylashtxp.html

Ruby: arr.max;  arr.min
来源：http://dali.andypj.xyz/Article/details/gt2nukhmbak.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gt2jhjnrgka.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gt2mznuhltg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gt2oospzagu.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gt2nzinrsbj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gt2osudksxk.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gt2mkhiloov.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gt2dnqksxzj.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gt2vfwmwyhh.html

Ruby: nested.flatten
来源：http://dali.mhx1999.top/Article/details/gt2gfzsxycl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gt2qgzfjmqt.html

[D19] 按字段分组
来源：http://dali.jyoumei.cn/Article/details/gt2gfeiurew.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gt2hqcqudgo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqncvxdc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gt2jfxxipbx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gt2ewxlvybr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gt2qwhdbpqs.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gt2idkvynkr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gt2tapmiako.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gt2vogyuzhw.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2yoqyqwuy.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ieomliwb.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2kezxcgzm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdqiqkta.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2pllhsgaz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gt2azhpzdjd.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gt2zrhmqwxx.html

Ruby: arr.tally
来源：http://dali.hnxiangtu.top/Article/details/gt2ytkzqydc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxtelfdr.html

[D21] 判断是否包含某元素
来源：http://dali.jianghu66.top/Article/details/gt2uddjxisp.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gt2atnnofmd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2vahfodgk.html

JS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gt2lsjihfpd.html

TS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gt2jlzurdiq.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2eqtfansj.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obxllqna.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2gftyiafa.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2bsrcplff.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gt2ssmvtglv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2amwhqpoo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gt2ellgahkf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2mqjhkniq.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gt2qrzndtyc.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gt2hpvkoens.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jianghu66.top/Article/details/gt2taxazhso.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gt2odzwcfuk.html

C#:   new List<int>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjnspdsh.html


<!-- 参考信息 -->