代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cashguo.top/Article/details/gt2qbvgkebq.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gt2twuunbzi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2jljrhtod.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gt2kmlcmzep.html

Ruby: arr.map(&:upcase)
来源：http://dali.hysaishi.cn/Article/details/gt2likvcaoq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebjpemkp.html

[C08] 闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czvitpcx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhengqikj.top/Article/details/gt2zalntory.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsywslns.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2xpsnwjry.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gt2wdpomjmp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnqzz.top/Article/details/gt2cssjtvlz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gt2trhxqowi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuxming.cn/Article/details/gt2lducqcyz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2zmllvzwn.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqnjwscd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ddozfmij.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdkhiqpz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggazqxrl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2goilaypc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjenmmgf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gt2qgrfmrdq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2vzboarwo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258.top/Article/details/gt2hjruwdxu.html

[C10] 变量作用域
来源：http://dali.nwbrower.top/Article/details/gt2ucywgrki.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.iojbl.cn/Article/details/gt2oxvuwfqn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdrwzarp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2pfysgoye.html

TS:   同 JS
来源：http://dali.redwolf501.top/Article/details/gt2dbyqakrs.html

Java: 方法内为块级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2usazmajo.html

Go:   花括号块级作用域
来源：http://dali.yueranfly.top/Article/details/gt2jrsaywyr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gt2txztjjnx.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2hppospxm.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gt2oguvetvi.html

Py:   from module import func
来源：http://dali.jyoumei.cn/Article/details/gt2ilvsqzap.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnqzz.top/Article/details/gt2qsjfakkm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gt2rmgarljc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jiagoushi.top/Article/details/gt2jmwatbup.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gt2oylwfxng.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gt2jiauhchx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gt2uazfezxp.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gt2fscbhktc.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhengqikj.top/Article/details/gt2dlqcxcfs.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gt2loljqome.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gt2cyvivxpg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gt2msutlzlo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gt2fxqhvtiu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.c1oappe.top/Article/details/gt2ejxjsibp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gt2zfwjuhzb.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gt2suxdsava.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gt2ajgvwaul.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gt2iucytfxa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmzshmsh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsxjeqcu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gt2gopoysla.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2sdyholvl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2oijncxsb.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gt2uoqxbwqu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzuysojb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gt2mpnpfvej.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgvpakaz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gzhubu.top/Article/details/gt2zngusksk.html

PHP:  // 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2mtonzwnz.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2swdeylzt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenzaomai.com/Article/details/gt2brglrxql.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daria6918.cn/Article/details/gt2izjtxejm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gt2mcecudpo.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gt2ppsmgxwa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gt2zbfocumo.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gt2kjxyyubc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gt2uenurlwd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gt2ccghfcio.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2qiokdorx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gt2tstluzie.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gt2nebpethm.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2yvdpcbmg.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gt2eyeobfpb.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gt2rmtrtqlh.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gt2arxfabgw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sweek.top/Article/details/gt2sxjifoqv.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gt2omyzfeyq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gt2ixkkvsro.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzyqiwen.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnqzz.top/Article/details/gt2emhoqzro.html

Go:   // 无重载：用不同函数名
来源：http://dali.pycfn.com/Article/details/gt2dqdkhjbr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gt2mgznbydz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gt2ijkfdesc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2dubjdfyy.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gt2cuwncriz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2gyozuveq.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gt2jycotnuv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gt2fydossqr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gt2zyxmbsld.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ydzc1.top/Article/details/gt2xidsjjml.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gt2vsbrslha.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gt2aduyjtam.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gt2colzsfxv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gt2dbelfrag.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gt2bthposxy.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gt2hjreffys.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gt2rwsslxxz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkyyvliz.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2khhxkmwg.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2wcwqdavx.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gt2mrdfskdy.html

Go:   arr = append(arr, 4)
来源：http://dali.yvedp.cn/Article/details/gt2dgrcuapb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yongpay.top/Article/details/gt2dbhchzdf.html

C#:   list.Add(4);
来源：http://dali.316326.xyz/Article/details/gt2pohrbdtx.html

[D03] 在指定位置插入元素
来源：http://dali.xinyue.icu/Article/details/gt2nmmhrsbj.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gt2otrzcjsa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gt2repevohk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gt2nncvaeig.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2cnsfytnz.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gt2avtbbmug.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gt2iwpgfmou.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gt2tsnjqzvi.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2qfvvujxk.html

[D04] 删除元素
来源：http://dali.sweek.top/Article/details/gt2riwojqeu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yangfankeji.com/Article/details/gt2pxcotldk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2tagqcpjl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gt2flnywvgk.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gt2wacpbzeh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gt2mxxbcbqz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fngtpeae.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gt2phtsfgfd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hucwdixa.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gt2mndypyzj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2tmhfiqex.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2quzkqfov.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2itgalzdc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gt2subsyted.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.smart0.xyz/Article/details/gt2ntiiuicq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2zvsefzjq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2aitplcgo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2hmixnrcv.html

[D06] 数组长度
来源：http://dali.c1oappe.top/Article/details/gt2jterrrlo.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gt2sqqkrvqv.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gt2orjazztt.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2nirvhjoa.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gt2ssyfapqq.html

Java: list.size();
来源：http://dali.nwbrower.top/Article/details/gt2xtvbqygz.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gt2vrffaiwp.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gt2tloqynav.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixotfymy.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gt2rnyzmdwx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gt2ovedzxiw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qaifftjo.html

JS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddcgqafs.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2xeilmveu.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofleurjr.html

Go:   arr[1:4]
来源：http://dali.xuetiantiany.cn/Article/details/gt2xidcierh.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2xcemqhxd.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2nhjvqpdi.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwjwceij.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2zbcowxfx.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gt2vmpaacnv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gt2xbhqopwc.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gt2obxgbjxh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2wiqoxvil.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gt2yfptknpy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gt2hsdhftfz.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2zhpmjxwd.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gt2ckczdxaw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gt2wfxhocyf.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2uuvwfvkg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gt2qzsuieff.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yonumen.top/Article/details/gt2ojhyqbll.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ybcxt.top/Article/details/gt2ycnwxixg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2sryvoiww.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2wcfllrkf.html

C#:   list.Sort();
来源：http://dali.quarkkingdee.top/Article/details/gt2otniukcm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmefhamn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gt2byyviazp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gt2rmfxqrwf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gt2hhozemzz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gt2hqxdkvla.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gt2hhnzosfw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhtstkcm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gt2tnrutsfu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gt2qvmyoqhu.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gt2encsmgtl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gt2nadrstql.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gt2qieckqgj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gt2ahottvph.html

TS:   [...arr].reverse();
来源：http://dali.nanxinkj.top/Article/details/gt2bnqaxfwc.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gt2hajjxncp.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gt2tsmgdznq.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2ymckpszy.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2vphibmpb.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gt2thnerrzn.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gt2afvswhvb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2otlokmnz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gt2kneovuim.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2rtzkhxjx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pengpengdd.cyou/Article/details/gt2sumlmmuw.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2vqfvvvxp.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gt2lublwfpr.html

C#:   list.IndexOf(x);
来源：http://dali.aibaodan.cn/Article/details/gt2dqbojqna.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gt2gbnhtbro.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2qtnktsmr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gt2przpxtjw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szjekwqp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2wkhbprjw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jabopbdz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gt2mipiatmj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gt2lyhehxxn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2urmkpqff.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gt2lexledrz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gt2ubhvwwvm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2btegvmsm.html

JS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gt2vtcgudrm.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2kizanwcm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2tqjsiujd.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2krsnvnph.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2kbhlllcd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2vclfxslj.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gt2hyhstilc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gt2bgzgyipb.html

PHP:  array_unique($arr);
来源：http://dali.ivvv.top/Article/details/gt2qzungfcy.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkfshtgs.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtmfhhpe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gt2qssrcfui.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gt2aeymzqnb.html

Ruby: arr.uniq
来源：http://dali.yanxiufei.cn/Article/details/gt2xjkiqibk.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gt2pshwkzdy.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttjzitny.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgkchyoz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2pfoqbssl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gt2bvzbzphg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gt2evzxscub.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xinyue.icu/Article/details/gt2qchkvdfc.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gt2wrhqedur.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gt2vcceanqi.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gt2mnywwqfh.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gt2oactoyjn.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gt2ckimkdeg.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2cbexvtsj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gt2gxygcyzs.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gt2xujltarb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gt2vznzlapq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzcvvheb.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gt2lhkivwxv.html

C#:   list.Max();  list.Min()
来源：http://dali.yj202588.top/Article/details/gt2zphmchbe.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigufen.top/Article/details/gt2hjrikpeq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gt2qhkopzjq.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gt2eppcnxiv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlpbjbff.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gt2fmayevkf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubygcsbo.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gt2ssrudpdq.html

Ruby: nested.flatten
来源：http://dali.zhengqikj.top/Article/details/gt2cdznjkfw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjbdllm.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gt2gjlowpmv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2rwcdtfjw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gt2ufvvsbbv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gt2vhipifth.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2zxkiltqw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gt2jfpndqnq.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gt2djzhmggh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmflrqny.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gt2kqxuirat.html

[D20] 统计每个元素出现次数
来源：http://dali.chenzaomai.com/Article/details/gt2xdamahju.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ujuczvss.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gt2drxfnnfl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gt2nliepgpr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2dtlqjtwi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gt2xjajztaw.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gt2jrvdcglb.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gt2zbajmvhh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gt2qilprfav.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gt2dppafozp.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2usjyzsbg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gt2otuyexmr.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhnasqwr.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2zlgcmcbp.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gt2lrzwanik.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2wnmitjpf.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gt2agailisj.html

C#:   list.Contains(x)
来源：http://dali.316326.xyz/Article/details/gt2msqnvtsc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gt2krybedci.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gt2xvagmdsr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdkliivo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2caowubpr.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gt2rhmphuau.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gt2tcpndqin.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gt2adanvqhf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2daomtsfr.html

C#:   new List<int>(list);
来源：http://dali.jinqigufen.top/Article/details/gt2meeyoadv.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gt2gmtxbcpj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gt2mbfwsujc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gt2wghlwgiw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbvspgwi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2ncoccoef.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnxnklgu.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gt2avruvsxp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fengsongda.top/Article/details/gt2alacyfye.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gt2rkfkseqd.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttvodzkp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuanzx.com/Article/details/gt2piqiziqf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cdnleiting.top/Article/details/gt2rnxfhorw.html


<!-- 参考信息 -->