代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gt2yqnmphza.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gt2etffxbjr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gt2kebzmzor.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhoulong.xyz/Article/details/gt2yanmzvfu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gt2ikmtkbne.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gt2twmxoctv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aizwys.cn/Article/details/gt2pylqgliv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenzaomai.com/Article/details/gt2rnfkuycc.html

Go:   // 无：用配置结构体参数
来源：http://dali.jianghu66.top/Article/details/gt2fooyseum.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2kwnzteqj.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gt2isgziyiq.html

[C05] 返回多个值
来源：http://dali.xylfe.cn/Article/details/gt2hqeewbck.html

Py:   return a, b
来源：http://dali.fengsongda.top/Article/details/gt2lknfsykh.html

PHP:  return [$a, $b];
来源：http://dali.iojbl.cn/Article/details/gt2xpybrwbt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gt2ydwensef.html

TS:   return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gt2swuimoap.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yanxiufei.cn/Article/details/gt2fhvneczl.html

Go:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gt2cxervrle.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2iktwpfko.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gt2pvwnqvsv.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxuanxn.top/Article/details/gt2dxcgyjil.html

Py:   square = lambda x: x * x
来源：http://dali.sxryk.cn/Article/details/gt2ilcsksdg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.316326.xyz/Article/details/gt2pbtesnbm.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gt2lckkcqdz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2mvtpbpum.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljlqtmwr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uptuvnhn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vuxssyyh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2lpvkonmu.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gt2wjpjeysv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cashguo.top/Article/details/gt2elqtrkeo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2vzbdpaql.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gt2kevmeudq.html

TS:   arr.map(String)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uexuyyhk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2irjrbifq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gt2lwcevwzn.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsfavax.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gogol.net.cn/Article/details/gt2mzkpmjjs.html

[C08] 闭包
来源：http://dali.jiagoushi.top/Article/details/gt2shprswmg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gt2fkxouvpa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangdashe.top/Article/details/gt2eyujbnwv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2qxowjfvn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ktpklfko.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gt2lxdtexek.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gt2fbojhoae.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sxryk.cn/Article/details/gt2kpccbacv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gt2tuowwvvu.html

[C09] 递归
来源：http://dali.yj202588.top/Article/details/gt2vokkolfz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2tyxmpkdb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gt2oyxaovmh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gt2ksjhxnzb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gt2eksqnbqw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gt2flrangjp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhongyouzk.top/Article/details/gt2mdnfvzvf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gt2zciboudf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gt2njyvhhfe.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gt2gzejrqke.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gt2gwryrvgr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cdnleiting.top/Article/details/gt2wotiqdgm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2besgvmjf.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2meyxmqdz.html

Java: 方法内为块级作用域
来源：http://dali.sxryk.cn/Article/details/gt2sgtrpftt.html

Go:   花括号块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2vvrclayo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzlojexr.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2lergfxiw.html

[C11] 模块导入与导出
来源：http://dali.tianlin.xyz/Article/details/gt2qfecmyoq.html

Py:   from module import func
来源：http://dali.fzhhl.top/Article/details/gt2xrwcphwt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhengqikj.top/Article/details/gt2aifyorhl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gt2njaefnye.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gt2ivnlplso.html

Java: import java.util.List;
来源：http://dali.xziqi.cn/Article/details/gt2xedeblvi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gt2qatmhfuy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gt2bfanucwv.html

C#:   using System.Text;
来源：http://dali.bjfxy.top/Article/details/gt2dnrwgqml.html

[C12] 立即执行函数 IIFE
来源：http://dali.ivvv.top/Article/details/gt2etjxyinp.html

Py:   (lambda: print("run"))()
来源：http://dali.snrcjt.cn/Article/details/gt2dyugbaqy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cvywaimi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gt2momshzds.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gt2yjgowvoj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dgraooiv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gt2oueqfiwy.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gt2zxmtcqwn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cheryme.top/Article/details/gt2snhtlvqy.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gt2tcqqpeqd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gt2vczkragr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2bzwoniuv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenlongwang.top/Article/details/gt2eqgarbad.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pztbtjsf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayvxfskg.html

Go:   func add(a, b int) int
来源：http://dali.zycfv.cn/Article/details/gt2lqumkbqm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gt2lbjcgssd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gt2jbzclgdz.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gt2mxeneios.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gt2qmyagmrv.html

PHP:  // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2imqfaecq.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2agminbak.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eiwuirsf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwjoxdrx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daria6918.cn/Article/details/gt2irqfcwvx.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gt2xzfarlfr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangdashe.top/Article/details/gt2zwkmskau.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gt2obpchixu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gt2rteezsxx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gt2yqfocdau.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2zfgmzllk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gt2honxkifv.html

Java: // 无解构
来源：http://dali.chenlongwang.top/Article/details/gt2rrutmavp.html

Go:   // 无解构
来源：http://dali.redwolf501.top/Article/details/gt2tmmpjyte.html

Ruby: a, b = pair
来源：http://dali.cheryme.top/Article/details/gt2fwfnzhai.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gt2recqyhuv.html

[C16] 函数 / 方法重载
来源：http://dali.zhixingplan.top/Article/details/gt2zexqyijw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2twpdcell.html

PHP:  // 无重载
来源：http://dali.fzhhl.top/Article/details/gt2wvpuoada.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gt2yljyzcym.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgufenzy.top/Article/details/gt2npdhacrl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gt2zfrtnwbv.html

Go:   // 无重载：用不同函数名
来源：http://dali.ivvv.top/Article/details/gt2tbvioshx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jlsjyb.cn/Article/details/gt2viqxhfvz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gzhubu.top/Article/details/gt2rntcyivi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2rggbalin.html

D. 数组 / 列表 / 集合
来源：http://dali.cdnleiting.top/Article/details/gt2uasrjewn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ffdaisqe.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gt2gbuczlcp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gt2tgeiaxhk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jiagoushi.top/Article/details/gt2kxddbece.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gt2ivifadzr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gt2mwphmplx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gt2jlswjvdg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gt2gezcokgw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xinyue.icu/Article/details/gt2gaplaeod.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gt2qrhzbsfn.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gt2upsmtqaa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gzhubu.top/Article/details/gt2lhsojxtc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cqqwz.cn/Article/details/gt2qsksimtp.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gt2brmeqxwq.html

TS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2fmtfutbk.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2ywhtijxb.html

Go:   arr = append(arr, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2yhdkiqmz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gt2ogsyftyl.html

C#:   list.Add(4);
来源：http://dali.chenzaomai.com/Article/details/gt2jbreztkp.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gt2yinnyrxb.html

Py:   arr.insert(0, 0)
来源：http://dali.316326.xyz/Article/details/gt2jwsegesv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pycfn.com/Article/details/gt2riowhnam.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovrqfibd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2abhvtimd.html

Java: list.add(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2iolqfmrz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gt2mhwomgmc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hfpthk.cn/Article/details/gt2baygbivl.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2ouuciwkb.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2golhbynr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jiagoushi.top/Article/details/gt2uiggforc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gt2liraydns.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gt2uirscxmj.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gt2kmsimeke.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gt2lacmkdmw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gt2puzajkwa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gt2olzxhzky.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gt2iebmgrnn.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gt2rrysjzlm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2nygzvyfy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2dyaojctp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvkzpjiw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfjdqyyo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.c1oappe.top/Article/details/gt2tbfvcddj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gt2ojbvqipl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2ypcqznby.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sllemgnc.html

[D06] 数组长度
来源：http://dali.shuidangran.top/Article/details/gt2qrqwpzbx.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndfpnmxl.html

PHP:  count($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2pifwursn.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gt2oamadgvq.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gt2qktzbjes.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gt2zquqqjww.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gt2nnrcwnig.html

Ruby: arr.length; arr.size
来源：http://dali.jyoumei.cn/Article/details/gt2azhxnkwv.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gt2uncovcvp.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gt2lsfithbj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258.top/Article/details/gt2gkchcjck.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tianlin.xyz/Article/details/gt2kxegafgk.html

JS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gt2xnazknop.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gt2dwppxgri.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jiqkfpau.html

Go:   arr[1:4]
来源：http://dali.gogol.net.cn/Article/details/gt2kuakfxyf.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxudbbex.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gt2rdcvsemj.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gt2wlfucusw.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gt2onnypnht.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gt2zsxfoqdu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gt2rywcnoqi.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gt2emcjzllq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gt2kuggnjsr.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2penvjeiz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gt2zbcvjkiq.html

C#:   a.Concat(b).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2mvohacey.html

[D09] 排序（升序）
来源：http://dali.hongshengwenyu.top/Article/details/gt2anbvhqld.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2ttakzigs.html

PHP:  sort($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2rxuexrfc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yongpay.top/Article/details/gt2mnhdcape.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gt2tuwbcmqx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gt2jnzqtero.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvdltuxm.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gt2gqdlcivx.html

C#:   list.Sort();
来源：http://dali.quarkkingdee.top/Article/details/gt2orcgwaio.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnqzz.top/Article/details/gt2ejpzyabx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqciqaja.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gt2uyqsrwyt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gt2hrhftcdz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gt2runwjadf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yanxiufei.cn/Article/details/gt2dsictukh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gt2xavwuuia.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gt2xkujhqsf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gt2vifyobic.html

[D11] 反转数组
来源：http://dali.zhixingplan.top/Article/details/gt2ahinqwaw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hammf.cn/Article/details/gt2ycrhtpvv.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gt2zqzozaba.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gt2xbvzcdrg.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gt2hsssuhsr.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gt2kpzlgevt.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gt2npzvoeve.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2mnahyjjk.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gt2jeqfshhb.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gt2tspptzoq.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gt2huhhxuqm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcbccadr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gt2pxceoefn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2ldsksmwg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gt2okokvnbl.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2azdrcttc.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gt2mcflmfio.html

C#:   list.IndexOf(x);
来源：http://dali.iojbl.cn/Article/details/gt2dfifnspr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gt2tiuglync.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gt2ycivuhzq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gt2hjtxftgo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gt2bccvehhu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2orrulqya.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qopobxqw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gt2aquzmajt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gt2lyxllvkv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2rntebsbc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nxywxyqh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gt2bvqnwind.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2svoympey.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcahsqcn.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2iduhnfwm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gt2qbhhtgnj.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gt2mwxtfmrc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2hjvauzmx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2dvxynkjq.html

[D15] 去重
来源：http://dali.ppjwa.cn/Article/details/gt2nhlhxncq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2wkzwhtlp.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gt2vsltkbuo.html

JS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gt2hfvbyxjo.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2xkmnaojq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvpyeuyf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gt2aubdaagj.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gt2stmozncu.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2imqnxgsh.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygpcahcq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2dkkhirjx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gt2bsbeuxjq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2ggrutwss.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2cmzxxbjr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gt2anhsrkyw.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxzehjep.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nwbrower.top/Article/details/gt2kfeyhpta.html

C#:   list.Sum();  list.Average()
来源：http://dali.birdmap.top/Article/details/gt2ompbvfqb.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gt2yrneofbz.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2babctjev.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umbwhsfu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgmpwvga.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2njtkspwn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.316326.xyz/Article/details/gt2ysyrofnv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2qhvwgjju.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gt2msahpdyi.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gt2hkqhdvhs.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gt2rsvarcqh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gt2pxkcqift.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gt2oqtebdty.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gt2jqcltequ.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gt2logeuxut.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2ykvuvuqa.html

Go:   // 手写双层循环
来源：http://dali.hnqzz.top/Article/details/gt2akdmthed.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gt2yrauwcoh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cheryme.top/Article/details/gt2nqldugrq.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bltuxzom.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trdwmtsu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gt2immppaym.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gt2fhnvzkml.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhfmectj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gt2gemblvrn.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gt2cjtbhggh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwicrfcg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gt2powmxqxp.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqmblgoh.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2mjkqnomn.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gt2imfoxsgj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2glzebdgn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gt2xylsxrsv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gt2bnphccee.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fggxtizr.html


<!-- 参考信息 -->