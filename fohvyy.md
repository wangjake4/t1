代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gt2reemkrge.html

Go:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebhuhuph.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gt2iemlwaon.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daxiang520.top/Article/details/gt2hlqorliv.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigufen.top/Article/details/gt2zxvisprx.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gt2ptoraoqz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gt2bpvcetik.html

JS:   const square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gt2nneazzgv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pycfn.com/Article/details/gt2rkoesybu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2ykkivnlv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tianlin.xyz/Article/details/gt2wmbmetxc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gt2hkexbczs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gt2tdaqpnde.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gt2znqgkqvu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gt2mhptylgj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2wehilgdv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gt2xmxgojvw.html

TS:   arr.map(String)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcowrkkc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcezzqww.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gt2jwzjsbuh.html

Ruby: arr.map(&:upcase)
来源：http://dali.shzxlz.cn/Article/details/gt2fexdtfve.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenzaomai.com/Article/details/gt2gbxpibdz.html

[C08] 闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmamxghp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gt2vtzhxagm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jianghu66.top/Article/details/gt2stxlhpck.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2egfodvbw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gt2ivctzcnp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aibaodan.cn/Article/details/gt2jqhdrqtq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aizwys.cn/Article/details/gt2vuirwsjo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gt2bfoumkjt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2ntesokjf.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gt2kgyenpxt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gt2doycjbzi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258.top/Article/details/gt2kudyiygv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gt2ihlyydxa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gt2nzhxktrk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gt2frceezdo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ppjwa.cn/Article/details/gt2ofqjaxiw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gt2vgfsnyqo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2odtmrwty.html

[C10] 变量作用域
来源：http://dali.zhixingplan.top/Article/details/gt2afhwpobr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.snrcjt.cn/Article/details/gt2pivrggdy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gt2equwzmuf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gt2axifvgcv.html

TS:   同 JS
来源：http://dali.yuxming.cn/Article/details/gt2ruqzrtul.html

Java: 方法内为块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2isztxeso.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2eamlobjy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yvedp.cn/Article/details/gt2hvdwkcfn.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gt2eeeatqpl.html

[C11] 模块导入与导出
来源：http://dali.xziqi.cn/Article/details/gt2npejpsjw.html

Py:   from module import func
来源：http://dali.andypj.xyz/Article/details/gt2uegdnqox.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gt2dcliamft.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gt2elbftdyx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhongyouzk.top/Article/details/gt2ggtbwkxi.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gt2irzcbnym.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2skcmctzo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amvqqong.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gt2wfnfxvew.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjxoljgp.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gt2dsvgryle.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigfzy.top/Article/details/gt2rharfrbu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gt2qnyywfcu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gt2wpqxfvol.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gt2adcdqpnn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gt2cvaczdem.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigfzy.top/Article/details/gt2xipjipuo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.smart0.xyz/Article/details/gt2wvefqlnt.html

[C13] 类型声明 / 类型注解
来源：http://dali.zdqjudy.top/Article/details/gt2igxsrtyl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gt2jjkzizih.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ijlkafdw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gt2yqkbvorw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vtyjhzjs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2ojwkydbw.html

Go:   func add(a, b int) int
来源：http://dali.nanxinkj.top/Article/details/gt2dhsbubnj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gt2jftvvxcp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gt2xsdqptyp.html

[C14] 泛型函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndojtmev.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhoulong.xyz/Article/details/gt2zxalaksd.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2eyylbukx.html

JS:   // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gt2zsbdgepw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.9152youxi.cn/Article/details/gt2egsbtevk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258888.top/Article/details/gt2euehkdql.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gt2frovcnaz.html

Ruby: # 无泛型
来源：http://dali.yvedp.cn/Article/details/gt2ydvtxjtx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gt2kigxubnp.html

[C15] 解构 / 展开参数
来源：http://dali.xziqi.cn/Article/details/gt2bqcrysju.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gt2ijjhfqsz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gt2zvdzgelq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2nkrvnhir.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2nkuhgspq.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gt2mwqjmbmn.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gt2yyvlrwsr.html

Ruby: a, b = pair
来源：http://dali.yonumen.top/Article/details/gt2ffwbllxd.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gt2nzfhzluj.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gt2whhlpsit.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gt2wkkugzfr.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gt2yugqbjxj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdcxoltg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gt2tdczoeag.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gt2ruohvbgm.html

Go:   // 无重载：用不同函数名
来源：http://dali.meibo888.top/Article/details/gt2klotadlg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zycfv.cn/Article/details/gt2pxvkjsyv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2mlcirnda.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2hxrlscym.html

D. 数组 / 列表 / 集合
来源：http://dali.hywenlv.cn/Article/details/gt2ldihdlze.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2qaelagsp.html

[D01] 创建数组 / 列表
来源：http://dali.pycfn.com/Article/details/gt2ynuwefga.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gt2uwxhojot.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gt2vttimeip.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gt2quxyyyrf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gt2ffewgkol.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gt2nmbrlkxx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gt2cpkypwiv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gt2fdscigzm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gt2ucnkrpvc.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gt2wyepxrxg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gt2kegocfpu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gt2ewjkvrrm.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzxpvzyc.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gt2pakezrnn.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gt2auzbiaak.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2showegcp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gt2gxdyioek.html

C#:   list.Add(4);
来源：http://dali.yj20258888.top/Article/details/gt2jhwiwhri.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gt2wuujxtbb.html

Py:   arr.insert(0, 0)
来源：http://dali.c1oappe.top/Article/details/gt2vfxnjsgp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlqytgen.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xylfe.cn/Article/details/gt2ubxeurze.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2ywidaief.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2vbyanwob.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuanzx.com/Article/details/gt2rgcrnsjt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gt2lpheygrw.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2tgghqpcj.html

[D04] 删除元素
来源：http://dali.nanxinkj.top/Article/details/gt2fsvnncrs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.meibo888.top/Article/details/gt2oaefhckj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gt2zllqmpoh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlcvqhdx.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gt2xdfztdfx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guowangkeji.top/Article/details/gt2vyppekzq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlkhmjl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nwbrower.top/Article/details/gt2yaizabug.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtbcgobd.html

[D05] 访问与修改元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyhntecb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2admpcxgd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2zdketkfg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgmpwpjh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gt2xzsmnnyi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gt2oaeygzbi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2iulhmvcx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2dnzjowlr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2oefncppw.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gt2ohlhflzp.html

Py:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gt2lndosotw.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gt2eqpiisld.html

JS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gt2lnbwrzgt.html

TS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gt2kvfdhieo.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gt2pdqywefj.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gt2koslovpz.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gt2msalsagf.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gt2ungecskt.html

[D07] 切片 / 取子数组
来源：http://dali.guowangkeji.top/Article/details/gt2cwzqhpbv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ydzc1.top/Article/details/gt2rzjeifsq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gt2kxrtnzcr.html

JS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npjbicjj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jclytqan.html

Java: list.subList(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2mvoeczop.html

Go:   arr[1:4]
来源：http://dali.sufxvd.cn/Article/details/gt2dqeidpbm.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gt2bwfvybjj.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xttezyyt.html

[D08] 合并两个数组
来源：http://dali.jqgfzy.top/Article/details/gt2gifomwjw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gt2xybtmczo.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gt2kepgmloa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gt2kroiyfzm.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gt2ghjmicwx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2apicykaf.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gt2ccdpchbo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ybcxt.top/Article/details/gt2ioabrtnv.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gt2hjeqzixu.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gt2xoaninob.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gt2gszwnnnq.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2wdokjnfe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gt2xzvdpitf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gt2cidgrchi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gt2nijnlexb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsmwdifq.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gt2bgurxsqd.html

C#:   list.Sort();
来源：http://dali.andypj.xyz/Article/details/gt2fpidmeot.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.birdmap.top/Article/details/gt2nkyblbgj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqwuedwp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2disgvqir.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnxpvdza.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gt2pwrlxtwr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwljmtrt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgobfsyb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gt2hklkpmhh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.birdmap.top/Article/details/gt2yijplbgs.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gt2jvxaviqp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sweek.top/Article/details/gt2snprshxt.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2chcltvzf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gt2vwoxeibo.html

TS:   [...arr].reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypenoama.html

Java: Collections.reverse(list);
来源：http://dali.dianchejie.cn/Article/details/gt2ycowbktg.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2ptpivlkr.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtjwhnft.html

C#:   list.Reverse();
来源：http://dali.jinqigfzy.top/Article/details/gt2whtdhwdb.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gt2wrehlfva.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gt2grtkytnn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ziyqdtpr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gt2adqfogca.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2peitgxqx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gt2vmkygndk.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2xnoygepb.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gt2xcfnrdyd.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gt2sqvhocce.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gt2hggjmuax.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.9152youxi.cn/Article/details/gt2ghhtlcec.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gt2tirmibgk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2uhoxefby.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2uackgeor.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2drtyhemd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gt2jwgblysf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gt2jkaccamg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2eefryrrv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gt2xaalhsxz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gt2trbyvyaq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2aidgxmow.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2fwtpvivt.html

TS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gt2nrehwlea.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gt2iexybldb.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gt2abplzads.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2psvdkbzm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258.top/Article/details/gt2jzssktkf.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gt2psgesukn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gt2twrprsdu.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2xsaycilj.html

JS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gt2tgrlbwxo.html

TS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2depaaluo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gt2vnxgbxnd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gt2ivpptlve.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gt2ojdyuvop.html

C#:   list.Distinct().ToList()
来源：http://dali.zycfv.cn/Article/details/gt2qpurmpnt.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gt2zfvqwmln.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gytizceq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2iiwxajsr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2gxtiwuaq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2vdcpnlps.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gt2wemdloug.html

Go:   // 手写循环累加
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mosezyhn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gt2vzdvpfdy.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gt2uxglyriy.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gt2szpmixsq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dyzmwiqr.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2hcvbbdvt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gt2xylxpmxp.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2istosoaj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2joassmoi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2qfrradqg.html

Ruby: arr.max;  arr.min
来源：http://dali.tianlin.xyz/Article/details/gt2nfdonyoj.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gt2fyyshrxd.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gt2kctehmer.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gt2meusmplq.html

PHP:  array_merge(...$nested);
来源：http://dali.redwolf501.top/Article/details/gt2nqjfqjuz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gt2dlaolcjv.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gt2uxoovjfz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2blmmgyky.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gt2klajteum.html

Ruby: nested.flatten
来源：http://dali.ivvv.top/Article/details/gt2evqzzotw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfouaji.html

[D19] 按字段分组
来源：http://dali.jianghu66.top/Article/details/gt2tgmqqdfk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gt2rehxdlcf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gt2iutbvloq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuanzx.com/Article/details/gt2lngsbawn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oryxdrnx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gt2icdclbzu.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2prstuqjt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gt2fvghdhzx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gt2hdribdpd.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gt2luehoyom.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2yrhvvthq.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2vpwmfevi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gt2dmobrono.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2owfjkplc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gt2jrepnqml.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzzbnrap.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gt2vnhcfngt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gt2kfoiixrf.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gt2mhifshpq.html

Py:   x in arr
来源：http://dali.sysykeji.top/Article/details/gt2ekigiisj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gt2wvsgzxbr.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2xphcgxly.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2zkvbknng.html

Java: list.contains(x)
来源：http://dali.tanke756.top/Article/details/gt2hltrkpit.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2jerdyzmv.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gt2rluqwmzj.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2lhuympqm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gt2qeqzyhoz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2iokaekuy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.kuanghao11.cn/Article/details/gt2htnvocrx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2tpwnjdut.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gt2fqfiwada.html


<!-- 参考信息 -->