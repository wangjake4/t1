代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtllzkyfnh.html

[C07] 把函数作为参数传入
来源：http://dali.gaohongyu789.top/Article/details/gtgwlfging.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gtgqnjmigb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeslhjte.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gtxkvbesgo.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gtpxxroonu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gtdsqgblnm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jyoumei.cn/Article/details/gtorihroxk.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfznevjm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gtuyaeakrs.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gtdyakjkum.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zycfv.cn/Article/details/gtetyjjavu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gtimtzpvir.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtkogxmrcs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtewtfofbb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gtzwuwocsh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gtapwtoxzm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gtwwvyncje.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gthnewdidc.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gtemhfhrii.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtoqkcycte.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtmxqvjptd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gtdgujyzqt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtvvxbwtye.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gtxxzigkik.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gtmzgxomxd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gtfebqwfib.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jlsjyb.cn/Article/details/gtflfyuaxn.html

[C10] 变量作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsnjjbwm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gturwudaen.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gtptglkyyi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fengsongda.top/Article/details/gteimwyfig.html

TS:   同 JS
来源：http://dali.bjfxy.top/Article/details/gtmcavwifg.html

Java: 方法内为块级作用域
来源：http://dali.wangdashe.top/Article/details/gtlqlkoplx.html

Go:   花括号块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtbzbowhwr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gtmsfkrajv.html

C#:   块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtijvwhvwi.html

[C11] 模块导入与导出
来源：http://dali.jianghu66.top/Article/details/gtglopyzmi.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gtvxcrsqgs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gtluqdosbc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gtnfmwechh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shangyingyoupin.top/Article/details/gtzfzhudkf.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gtmybgmkrh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.bjfxy.top/Article/details/gtcejcbowd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtffaekapt.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gteytepilq.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjuuvxzo.html

Py:   (lambda: print("run"))()
来源：http://dali.haohaochexian.top/Article/details/gttqsgjbbw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gtnjauidid.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtdghjlttv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gtphgbvuqd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gtvfvbqkud.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gtkyapamso.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gtcgbotqop.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gtbdiyfxll.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gtmgrtgzes.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtghumpqrp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksmbvkqr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gtfomhsexz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtsdpepglz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtqbjqvhuv.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gtmvhridpz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zdqjudy.top/Article/details/gtxxpaggmg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjexuuhix.html

[C14] 泛型函数
来源：http://dali.zhiwuduotai.top/Article/details/gtdmibfbtg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gtbdkyfctt.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikwjlvwf.html

JS:   // 无泛型
来源：http://dali.yonumen.top/Article/details/gtclkwajpw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbocejjb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gtvobdgrkr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtedcwymye.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gtlauhtnzg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigfzy.top/Article/details/gthpjhfetg.html

[C15] 解构 / 展开参数
来源：http://dali.yangfankeji.com/Article/details/gtyjmieqiz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtqdhhjzda.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoevrfbfy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtrsxdmmsi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaazixaat.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtkohfgkxx.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gtovmkyedz.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtljyqclib.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gthqjudyqj.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gtmkmsroxi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gtrepvxfan.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gtfkimgark.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gtokjnvjid.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gtdozvvzhm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gtktnbtyxx.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpolffhd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gtxryawvie.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gtsmeujvtk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkamgkses.html

D. 数组 / 列表 / 集合
来源：http://dali.feifeiyinyue.top/Article/details/gtaqcejwwp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttfvxgvcv.html

[D01] 创建数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gtpfzsikiy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yongpay.top/Article/details/gtiljfgfsh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtrrgffsyh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtbqhufzoa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gtdiupdjsy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtlauvqyan.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtespzpbtp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gtplgnfexa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gtuatgxryw.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gtzdrkrgja.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtqdrtsloh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gtuvhlkksn.html

JS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtlynvgpxp.html

TS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtlsluxegn.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gtdrkvvwhy.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gtfmuwzezn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gtrwbqweye.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gtfxmbiewe.html

[D03] 在指定位置插入元素
来源：http://dali.zycfv.cn/Article/details/gtjutbgaar.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gtqkdrjgyd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtfejrsiry.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shuidangran.top/Article/details/gtpanghwkk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.meibo888.top/Article/details/gtxfzgowzy.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtwzsyvhld.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gtymsauhet.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gthzzhjgga.html

C#:   list.Insert(0, 0);
来源：http://dali.havefunace.top/Article/details/gtyevzrhum.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gtdsswyymt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtjqeutagc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hammf.cn/Article/details/gtbiwteifp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gtlvupyuee.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gtdfginkfa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.quarkkingdee.top/Article/details/gtfxucwktb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cqqwz.cn/Article/details/gtfslvoncz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gtogikxlei.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtkkmdpprs.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwujncue.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtcxerwbah.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtbcesjvfl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtawzvmaay.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtggzknlnp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hongshengwenyu.top/Article/details/gtvrxrsgpt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzewaikn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtrncbchxs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtcnaglzdh.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtyqajhtux.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtyunubrac.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtzyshmfut.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gteulqprpj.html

TS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gthxksbzco.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gtbljrpcyo.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexlepgta.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtiohunxwj.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gtkxtzvykd.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gtrzhvkzhi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gtyoxzdcuk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtxybtzkxl.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gttbvisavy.html

TS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtiiogivsw.html

Java: list.subList(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtwrarndns.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gtqlewujwb.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gttykzttvp.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtmqytiueo.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gtgtbesamb.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtuzslowab.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gtiqaafdfe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gtimcyvkzk.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gtoctzupgk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvsmqukg.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gtswrkrcly.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gtbtpidqrw.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gtjqisqdeu.html

[D09] 排序（升序）
来源：http://dali.yj20258.top/Article/details/gtbflfguty.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtjsqjpyfx.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gtmfrjpbxk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gthwsidfhv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gtcfovowjf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtxlgqvqdh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtuvmumvnb.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtrfyzkfga.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gtjrjzazaj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gtemtnbavh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjadfanoe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtykprjvcg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtoopudnou.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtjclximxo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtkpwuphkz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gtwzbyflml.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gtenocjehh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.iojbl.cn/Article/details/gtaiorpeyx.html

[D11] 反转数组
来源：http://dali.ydzc1.top/Article/details/gtnqvuguig.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenzaomai.com/Article/details/gtwzwvklmg.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtcysytzcv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gtewzgwhhq.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtrmvvmldr.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gtclvwlecd.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtegmyohsj.html

Ruby: arr.reverse
来源：http://dali.redwolf501.top/Article/details/gtmkrjdudt.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gtoyfsgzuz.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gtquxtclhr.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gtbnisxmcb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gtfsoneubj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtpxiwtukg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtrhedhqix.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejyccomh.html

Go:   slices.Index(arr, x)
来源：http://dali.yongpay.top/Article/details/gtmuxuglvy.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtpohaabyc.html

C#:   list.IndexOf(x);
来源：http://dali.daxiang520.top/Article/details/gthyziepag.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gtsncesxjo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gtyiflwlwr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gtyxqsxpog.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtajxyzjwg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtrvlwvkyb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gttdjfbfas.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sufxvd.cn/Article/details/gtugddiebz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gtckqnzbuw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xinyue.icu/Article/details/gtvzycjgpp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gttuespyky.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtjqwfkdxl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtfezpcpcw.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtjysuvnuy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtrdrzcvto.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtbfsldewi.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtjlybmkci.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gteortkmct.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmytpfdh.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gtzeddziis.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtfhkuciux.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gtkvsfiaqr.html

JS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtovqaqwof.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtfzrknzle.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gtsqthgaxy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ydzc1.top/Article/details/gtpztaidyd.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gthnpoxiwp.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gttkdkpkam.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gtegkowklp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtokbdwxra.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gtrwdphzmo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gtuysbdzov.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtuovvbyfv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenjidiqi.icu/Article/details/gtabnetlsk.html

Go:   // 手写循环累加
来源：http://dali.wangdashe.top/Article/details/gtdempxdof.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gtvkgwrlxl.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gtsihwkuhh.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtubekahpk.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gtirtwiqxs.html

PHP:  max($arr);  min($arr);
来源：http://dali.shzxlz.cn/Article/details/gtdwxlgllg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.9152youxi.cn/Article/details/gtamxhkblg.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gtrtplisgr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gtkygsqddq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtdcjsftxv.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gtetmjtgbu.html

C#:   list.Max();  list.Min()
来源：http://dali.ivvv.top/Article/details/gtuneeujfg.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtzvxefakv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtogltvclr.html

PHP:  array_merge(...$nested);
来源：http://dali.svipenyu.cn/Article/details/gthsfycrsb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gtlydpzkoq.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gtuvaluimq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gtdotetwcp.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gtypfcgcxx.html

Ruby: nested.flatten
来源：http://dali.jinghuilouyu.cn/Article/details/gtwacfotbt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gtjkinyijo.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtshsdwpxj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtmcsoqbya.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gtrnxgkeza.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gtrnpiovrb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtbyufxsvv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gtymhnkuwe.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gtqsdloyrd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258.top/Article/details/gtrhskqqln.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gtrvamsrfm.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtzideyfnh.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyrzhicu.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gttmoqqqgg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtaylylpbl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtlyqxidiv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtyyaqyhxx.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtkkdmukpv.html

Ruby: arr.tally
来源：http://dali.tanke756.top/Article/details/gtzbuyewtq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gtednpdpld.html

[D21] 判断是否包含某元素
来源：http://dali.haohaochexian.top/Article/details/gtjhuphyfw.html

Py:   x in arr
来源：http://dali.sufxvd.cn/Article/details/gtjmyuuufy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.snrcjt.cn/Article/details/gtdkmrbpmq.html

JS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtwdvpewtu.html

TS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtkrqckrxe.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtmifhuymk.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtxtoqcpzf.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gtmmgvcnez.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtubrzqauu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.havefunace.top/Article/details/gtvjroufjo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gtoqkrtsra.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hammf.cn/Article/details/gtsatehxdd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtibebydfz.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gtewbohrdi.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gtrkslgmbb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gthouoycdi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gtyuwsdqfm.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gtndwccmsi.html

[D23] reduce 累积计算
来源：http://dali.yj20258.top/Article/details/gtcvgrwndp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tian-w.cn/Article/details/gtgupwhnmc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gtejhvzssq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gthgpluxml.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtbzdzxsax.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gtnhqjcdib.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtumhjlzmc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sufxvd.cn/Article/details/gtrmqjknso.html


<!-- 参考信息 -->