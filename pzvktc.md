代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gt2afmvbate.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gt2wuaffpnb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gt2lmjoouim.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sxryk.cn/Article/details/gt2vmbzjnaw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmxnjjc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.vqdsnc.cn/Article/details/gt2zzwgpgft.html

[C04] 命名参数 / 关键字参数
来源：http://dali.havefunace.top/Article/details/gt2bapfbhbt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzbyquus.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gt2bzpyehku.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gt2kbufknvs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gt2btnoilmj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofktaexo.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gt2uzsqzrvm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcikatrs.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2yenwzlum.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gt2tflizhdr.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2nroexlqp.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gt2dezugvrw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gt2nqabswef.html

TS:   return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gt2phwhbiqm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gogol.net.cn/Article/details/gt2cewjwvdq.html

Go:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojynodcj.html

Ruby: return a, b
来源：http://dali.aizwys.cn/Article/details/gt2jqaelouj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gt2fnxptauk.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gt2trgomwjh.html

Py:   square = lambda x: x * x
来源：http://dali.cdnleiting.top/Article/details/gt2ugfpcmov.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hammf.cn/Article/details/gt2isjmtuim.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2uzlzbbce.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2rsrgtbhe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gt2rndwaast.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gt2mknqnrii.html

Ruby: square = ->(x) { x * x }
来源：http://dali.iojbl.cn/Article/details/gt2jtqrkgle.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gt2qxicbbil.html

[C07] 把函数作为参数传入
来源：http://dali.zhoulong.xyz/Article/details/gt2glvnvjgy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yanxiufei.cn/Article/details/gt2slfytzor.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2cgxbhwhk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuanzhike.top/Article/details/gt2gmwvxbpa.html

TS:   arr.map(String)
来源：http://dali.redwolf501.top/Article/details/gt2cdqqxsdc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gt2halgyesq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shangyingyoupin.top/Article/details/gt2iaeiwkwp.html

Ruby: arr.map(&:upcase)
来源：http://dali.hysaishi.cn/Article/details/gt2bxqfnksj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gt2hdtnzbga.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gt2edrrnqbg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gt2oqjmteeu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gvpaiazh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2dlxbphlx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2nppasklx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhoulong.xyz/Article/details/gt2hqbmxbgv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gt2eqfaoxbg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gt2ythlxvja.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gt2fdhhtjvg.html

[C09] 递归
来源：http://dali.hammf.cn/Article/details/gt2unagtuuu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gt2jlxgbqtm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gt2xseqthla.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gt2skmzpadu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gt2lccwroln.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yonumen.top/Article/details/gt2sqczovgo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dianchejie.cn/Article/details/gt2mhquvosp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gt2rnpghbko.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhengqikj.top/Article/details/gt2jrdkygfm.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gt2acpnghkk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfndtvjc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gt2vcnyaixy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmhiozd.html

TS:   同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gt2shlatkmi.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gt2esbpjlcz.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gt2roecsljw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmvixlgu.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2ucdznxgz.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gt2qogcbynb.html

Py:   from module import func
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkuppeuo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gt2vimytzrz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gt2rjozohup.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daria6918.cn/Article/details/gt2zqmgpoht.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gt2lhytoavt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gt2etiizcam.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dashuyun.cn/Article/details/gt2iagzbkqf.html

C#:   using System.Text;
来源：http://dali.hysaishi.cn/Article/details/gt2odhvaite.html

[C12] 立即执行函数 IIFE
来源：http://dali.daxiang520.top/Article/details/gt2yixdxwqo.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gt2fgjrawlg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gt2mtnmphms.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2izudyplx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2tynbolpi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guowangkeji.top/Article/details/gt2cqxoxrlc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenlongwang.top/Article/details/gt2flofghul.html

Ruby: -> { puts "run" }.call
来源：http://dali.yvedp.cn/Article/details/gt2mkdmcare.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2oldoxypv.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gt2lybxmjky.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbomrcal.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gt2muqobesx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gt2tzsyavgz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2ispwebon.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2idggjnyr.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gt2mmmuruxj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fzhhl.top/Article/details/gt2gdfvxffl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ybcxt.top/Article/details/gt2jcupultd.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gt2mlojvigi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2jumrpcdk.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2rswmkccb.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gt2bbfkriop.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gt2ghzeuwci.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gt2kooetobw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258888.top/Article/details/gt2lkmgblff.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gt2yxxsrhrn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gt2mvaiiycd.html

[C15] 解构 / 展开参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acsphxqj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gt2rbzdsjbw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gt2hnfukcow.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gt2dvkkujnz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gt2iiicjnsu.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gt2sucktuzw.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gt2stplvoox.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gt2brlqpdhl.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gt2gtasuhut.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gt2qyolbago.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gt2ukcktxye.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gt2zslzhcmg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gt2hqgzigyu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gt2scfchiuf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gt2ytmtgxvv.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gt2gnsusbdr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tanke756.top/Article/details/gt2jatplist.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gt2bslhjpbz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2jqcuwbsi.html

D. 数组 / 列表 / 集合
来源：http://dali.dashuyun.cn/Article/details/gt2mjdjcwde.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2wnvcpziv.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gt2qgzwaxhj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gt2vtsvqfcq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gt2uglrwjeb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gt2rpseufbf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gt2zednqizh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gt2edtldgga.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnxiangtu.top/Article/details/gt2zqweahok.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcqkeoqg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guowangkeji.top/Article/details/gt2zhlekdwi.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gt2tunfhvxv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yongpay.top/Article/details/gt2femnvbaz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gt2tlibwibc.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzqurnho.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gt2vzsbnnsd.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gt2hupawygh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2ycxmbywq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xziqi.cn/Article/details/gt2nmpasafu.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gt2swzhyysl.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gt2smoyklyk.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2ypkqefaz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gt2pkuyhtsq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ppjwa.cn/Article/details/gt2ghmigtjz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2uoytzoyi.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eycaromh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hfpthk.cn/Article/details/gt2aridpojy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gt2crotgtjd.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2twxpqxgg.html

[D04] 删除元素
来源：http://dali.c1oappe.top/Article/details/gt2dngdzyda.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pycfn.com/Article/details/gt2elvrxbmd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gt2gpvyfhhe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gt2vavmxnuz.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gt2rjvmqsde.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjifreip.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.quarkkingdee.top/Article/details/gt2nipdijro.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gt2fnfsqmea.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gt2qeznlpcj.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gt2eyvuqvjp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gt2utverljw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmhtxntv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2uaubnjlj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2umqaqygy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gt2npzvogwg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gt2cwadnixg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gt2ozuagiky.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2vnpqlhhx.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2efhdrqeo.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2oejnntyq.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2cqlpcssn.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2skhvdnmi.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gt2tfvazawz.html

Java: list.size();
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjtqonzr.html

Go:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2yojtydez.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gt2yeqvfrcf.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmezmyfd.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gt2lwauiwzb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gt2wtqunqes.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2sdxsrzsx.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2kdahxwaf.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2tfydobkd.html

Java: list.subList(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2tvslvikh.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gt2ridivadt.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gt2ejfrmuxc.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gt2kjiwkota.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwhyauhf.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gt2cawdpplr.html

PHP:  array_merge($a, $b);
来源：http://dali.svipenyu.cn/Article/details/gt2qfuxkwmi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gt2lulzbxzq.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gt2ucxnalse.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gt2mnglndmz.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gt2nrxfunaf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gt2umnflugl.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gt2dxjtnhng.html

[D09] 排序（升序）
来源：http://dali.hnxiangtu.top/Article/details/gt2mouewivn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gt2dfwqpbge.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2lpcwqngb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gt2ioprqmcp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgfzy.top/Article/details/gt2mhgdjxxw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yueranfly.top/Article/details/gt2zpwnpwua.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2lmktgtvl.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2ysfzybek.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gt2rnleugey.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzkivhzi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gt2lyfjenhh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gt2navpfedw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwsuvvr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2vhzsitvi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jyoumei.cn/Article/details/gt2jrhovmyp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.316326.xyz/Article/details/gt2cdpxtbgj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnjchbnc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gt2dglxabmk.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gt2icupkqkh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.9152youxi.cn/Article/details/gt2rumyzhaj.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2svaxlipm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gt2puahsqyh.html

TS:   [...arr].reverse();
来源：http://dali.hysaishi.cn/Article/details/gt2arjpkuot.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxhwbczf.html

Go:   slices.Reverse(arr)
来源：http://dali.ybcxt.top/Article/details/gt2oknirvgm.html

Ruby: arr.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2fqnqengs.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gt2oghdzfgj.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gt2kxdfkawq.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gt2lrzmxwgb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gt2yxgboogt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gt2pkjnsduw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gt2cawvthnx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgufenzy.top/Article/details/gt2wcxbezew.html

Go:   slices.Index(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2fruxngtw.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcqehbff.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gt2ajhpwwut.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gt2scaorksp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gt2lmhicygb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gt2ebgahagk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2fynlrerv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gt2cmlxssco.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gt2ulfeugns.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gt2dgqndcac.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gt2pcbnqgvn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2rmcsaryy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdkapvgf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gt2sjnurjut.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2ymdvxkth.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2xeuzachi.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2rcypvffd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2guwfprhg.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2gfpbtadn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2bcrnvucw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2grbvjrea.html

[D15] 去重
来源：http://dali.tianlin.xyz/Article/details/gt2dvcetvnq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gt2spxczkap.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2fvkkjata.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gt2zjvrgsty.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vxclpnac.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gt2kfupakox.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gt2cvyhkhda.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gt2fujyhcxh.html

C#:   list.Distinct().ToList()
来源：http://dali.sysykeji.top/Article/details/gt2wukyfpnr.html

[D16] 求和与平均值
来源：http://dali.yuanzhike.top/Article/details/gt2aokkxikt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gt2nsyvhfkm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gt2kzchetln.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gt2pdghdatd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxpdomcq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aibaodan.cn/Article/details/gt2qhbzutgx.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gt2jrvailzo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gt2quzuugjp.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gt2wniulptx.html

[D17] 最大值与最小值
来源：http://dali.gzhubu.top/Article/details/gt2gjftwmoz.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gt2qahjykph.html

PHP:  max($arr);  min($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2saohnjip.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gt2mgfcezzf.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gt2pykuwnfe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gt2vswiajbp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gt2joqevmtd.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gt2fiqbtwev.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gt2ikpzipjj.html

[D18] 扁平化嵌套数组
来源：http://dali.vqdsnc.cn/Article/details/gt2sehsxycx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gt2rdnceoyy.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gt2bcayjqvn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gt2pkcwfssh.html

TS:   nested.flat();
来源：http://dali.tian-w.cn/Article/details/gt2nbvrashy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gt2fxbodsdn.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqywchbt.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gt2vgrxzbog.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2mczxgmfa.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gt2wqftjsbd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gt2ozpcridy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fikehnhn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gt2rlnfedoz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gt2mgwojtwm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gt2fgebdliw.html

Go:   // 手写 map[string][]T
来源：http://dali.svipenyu.cn/Article/details/gt2ydaimsyn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xyepmnvv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gt2ujjromrv.html

[D20] 统计每个元素出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gt2daxojich.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gt2ooyxykhq.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gt2jpohwosw.html


<!-- 参考信息 -->