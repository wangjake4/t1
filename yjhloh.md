代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gt2jjgedkcm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gt2asxddhwi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.smart0.xyz/Article/details/gt2gvhytqmi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gt2abqqoycb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpgohtww.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2fxrxijgz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2immvkrqh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gt2yxzmnglt.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gt2cvvxwlqc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lehmfdra.html

C#:   f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gt2wvaoaotk.html

[C05] 返回多个值
来源：http://dali.hfpthk.cn/Article/details/gt2iqdcestb.html

Py:   return a, b
来源：http://dali.yueranfly.top/Article/details/gt2vrocuwkq.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gt2wmyallwe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xinyue.icu/Article/details/gt2xenqpzlv.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gt2oikisizv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.redwolf501.top/Article/details/gt2ufluapqy.html

Go:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gt2esetgoei.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwghcvfk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gt2tnduhckw.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gt2kfptywpw.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gt2vmkhzoxz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cdnleiting.top/Article/details/gt2lakgnvtw.html

JS:   const square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gt2ugodsjvm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gt2fdumsomd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnqzz.top/Article/details/gt2dvqfihee.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.0kj1m.cn/Article/details/gt2qotxnjox.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gt2wbernwqr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2ccyxlhef.html

[C07] 把函数作为参数传入
来源：http://dali.shangyingyoupin.top/Article/details/gt2bewijvck.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gt2ngpqalai.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aizwys.cn/Article/details/gt2fgadadxw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gt2yewetowr.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhdnohkz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2amaulazd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qafhcccl.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxahbcyi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.vqdsnc.cn/Article/details/gt2sohwysnc.html

[C08] 闭包
来源：http://dali.yj202588.top/Article/details/gt2riyqctde.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jlsjyb.cn/Article/details/gt2ipulszff.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jianghu66.top/Article/details/gt2qwivwdtj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nzgrorxi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2cutfvgak.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cucudq.cn/Article/details/gt2lixdmczr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gt2xmenuaef.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cqqwz.cn/Article/details/gt2zabqqdpx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2vywosrkb.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gt2eppezrgr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gt2rcwskipg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258888.top/Article/details/gt2hgupqhze.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gt2pmmzptcm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gt2klqxekxy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2ohjcddmu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gt2wyfaduwl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iyzghptt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gt2nydfhais.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gt2efvuwjku.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jiagoushi.top/Article/details/gt2yjgpifuy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gt2wnlqzlkb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2gzkwpalo.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gt2iibyqoiy.html

Java: 方法内为块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2uccxkxoc.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gt2xyqrttqe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.bjfxy.top/Article/details/gt2piqzryrx.html

C#:   块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxkagzbj.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gt2fvotmgsv.html

Py:   from module import func
来源：http://dali.gogol.net.cn/Article/details/gt2fzvztmsy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gt2tcvrltep.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gt2pwzyamuw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gt2xiuijdnq.html

Java: import java.util.List;
来源：http://dali.yueranfly.top/Article/details/gt2lacwcgbj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daria6918.cn/Article/details/gt2myytjear.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gt2rqrdibxi.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onhgvnyg.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gt2gvphjrot.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gt2ublecsev.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gt2pvlckppx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gt2zqjndvaz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gt2ctfcskxd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gt2mdkrotyr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gt2zegmclcx.html

Ruby: -> { puts "run" }.call
来源：http://dali.meibo888.top/Article/details/gt2mezstvyr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2cuqopflt.html

[C13] 类型声明 / 类型注解
来源：http://dali.shzxlz.cn/Article/details/gt2rdmykyvr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gt2efgisfve.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2lvbaazbw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.bjfxy.top/Article/details/gt2sfeobjuh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2oecrrfur.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omsaogbi.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gt2mtgpbyvs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuxming.cn/Article/details/gt2rjquvnla.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gt2nyhwabhd.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmoyxsve.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gt2inejcrke.html

PHP:  // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gt2bcgjimvw.html

JS:   // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2bycydekj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gt2mrtgvvzx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daria6918.cn/Article/details/gt2gyanwkff.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gt2zgrhankw.html

Ruby: # 无泛型
来源：http://dali.hywenlv.cn/Article/details/gt2pxpqqppo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gt2cpslkpvh.html

[C15] 解构 / 展开参数
来源：http://dali.0kj1m.cn/Article/details/gt2luqkkyqs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qydhrcem.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gt2maqdepiq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gt2wmhplbmj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gt2jamjigpr.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gt2mrldojbz.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2fyeemhti.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gt2xscuppss.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gt2snrtmtqm.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsltdlju.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gt2dbnmrfln.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gt2anhmvohy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gt2ibtxhjru.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gt2unqrzniv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gt2jssusdxj.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gt2lkbimbmy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gt2qqalezoc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gt2ydxngmbm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2xguyfumd.html

D. 数组 / 列表 / 集合
来源：http://dali.smart0.xyz/Article/details/gt2imnadeqi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2swybqnwg.html

[D01] 创建数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gt2burtxsfy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gt2yfsimpca.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2yuurcwsm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigufen.top/Article/details/gt2qwjbrwwi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gt2mvurkdss.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xylfe.cn/Article/details/gt2zfqxlajy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shzxlz.cn/Article/details/gt2ilpiemji.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gt2dfwroclx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gt2dmzcsmbl.html

[D02] 追加元素到末尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2scsnazuz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ybcxt.top/Article/details/gt2xomjucfm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gt2kepgpabz.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2pgunocue.html

TS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gt2ufenpwjt.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gt2ncxsmkwv.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gt2aqawddxc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gt2gbjfbsfr.html

C#:   list.Add(4);
来源：http://dali.bjfxy.top/Article/details/gt2xephdqkl.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gt2ourwjxcu.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2pxbyintq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gt2zokbyzky.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jlsjyb.cn/Article/details/gt2wobivelu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2uybuqwpg.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2kicxgtlm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2egklqkgi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfnrcjgz.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2hpppyfgq.html

[D04] 删除元素
来源：http://dali.dianchejie.cn/Article/details/gt2koegpxjq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2xdeuibdx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2lcqbuqfz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gt2zjjcjmbz.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gt2wbovywyo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gt2kyzpojbu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sysykeji.top/Article/details/gt2sdsztyfl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gt2plwlouca.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgfzy.top/Article/details/gt2upvmqrgj.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gt2ltatouus.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2gippchhb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gt2ajtrolrk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2zysjoiii.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dashuyun.cn/Article/details/gt2mxcpuvkp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxinkj.top/Article/details/gt2zngidhyl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2wwhhxsqs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2vmqlrufz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2hoiezlnm.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gt2seubocoy.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2lxzowyfo.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gt2cfiqcruo.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gt2hysqmhkb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dniglluu.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gt2qmcqsgbh.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2jlqhzhfw.html

Ruby: arr.length; arr.size
来源：http://dali.yanxiufei.cn/Article/details/gt2wixnvmnq.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gt2hmkzfdap.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gt2mojwdkdt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gt2vqnnpsan.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gt2hfnsjngx.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gt2iyyeomfw.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gt2kanmdnzr.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2gvgsmqoj.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gt2nbkfvxbz.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gt2mxjpgutp.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbfxxgrr.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gt2xenpbopo.html

Py:   a + b;  a.extend(b)
来源：http://dali.pycfn.com/Article/details/gt2jzdndyli.html

PHP:  array_merge($a, $b);
来源：http://dali.havefunace.top/Article/details/gt2sjpsqfel.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nwbrower.top/Article/details/gt2gpzhvual.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gt2lsxjnitt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygrmwzxj.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gt2pbmznzpi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhixingplan.top/Article/details/gt2yrajpcke.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2csvcbkvq.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gt2ddrmdhhl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfobjhce.html

PHP:  sort($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2jtnitpsg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gt2ylbvmssf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gt2mykjygdn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gt2mgiswzbj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aipzdjff.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2hrmpwnbx.html

C#:   list.Sort();
来源：http://dali.jinqigfzy.top/Article/details/gt2stkfvevi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gt2xzunuqvt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gt2luxqsglb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2mdgfecgg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gt2beuxjvhb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gt2fsjmvnyc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xauuqune.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dianchejie.cn/Article/details/gt2jluprbuk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tanke756.top/Article/details/gt2weboykkj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwqxnymv.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gt2jgznoark.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gt2ynyqjfle.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2siffukyj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gt2insscmxh.html

TS:   [...arr].reverse();
来源：http://dali.andypj.xyz/Article/details/gt2utyntzqu.html

Java: Collections.reverse(list);
来源：http://dali.yongpay.top/Article/details/gt2eixunyoc.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gt2vmqkydaj.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2gkayrwmo.html

C#:   list.Reverse();
来源：http://dali.guannengcc.top/Article/details/gt2enwnivqt.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snhzzzyc.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gt2onuvpfwm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guannengcc.top/Article/details/gt2xiuuefiu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2znqdyali.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vyfxmcao.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gt2aiikstwx.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebclbnsk.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gt2opcdwkuc.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gt2gmmqcuwq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iuosuikz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gt2bbbkbxvf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2hwdmypjq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gt2pudldgqi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2xiicheqs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gt2mwoaafzw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gt2vcbqhvnh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gt2mcknqxul.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2eakpxnik.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gt2snwyklen.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofxeyloi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2pqshxecc.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2yswbxoaa.html

TS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfjwczob.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2vrapdvsv.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2xhewuguu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2zukfypda.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2dciopifd.html

[D15] 去重
来源：http://dali.sufxvd.cn/Article/details/gt2kkgpyqel.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gt2tohjbvkf.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gt2bfdubtta.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gt2dxllkhao.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gt2ckdvbmua.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.316326.xyz/Article/details/gt2bohivypl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tian-w.cn/Article/details/gt2dggdkjqw.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gt2ssldjvmi.html

C#:   list.Distinct().ToList()
来源：http://dali.zycfv.cn/Article/details/gt2wixtnizo.html

[D16] 求和与平均值
来源：http://dali.9152youxi.cn/Article/details/gt2agjjvcjq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2nspxhgaf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjleikea.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2dtkdnjnu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2qdrskfrz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gt2taqwpcwc.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gt2zovsmoaa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gt2ywavpcma.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gt2sxrgjldc.html

[D17] 最大值与最小值
来源：http://dali.daria6918.cn/Article/details/gt2tiolowic.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gt2gpbjewtg.html

PHP:  max($arr);  min($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgjbrrhq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gt2ubbvdidl.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gt2mjyqfusm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gt2ftkfzngu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gt2blbksjdk.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irvzltdc.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gt2sbhdirkh.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2ondqfobe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gt2akqenfpj.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gt2fgxysljd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xinyue.icu/Article/details/gt2ijgeexxn.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gt2fwpruknn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbciilhw.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gt2nocdkvkd.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmjsohwj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2laaqngjy.html

[D19] 按字段分组
来源：http://dali.yueranfly.top/Article/details/gt2rnlblpod.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmnqwsru.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gt2snjwvqtf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgjihubo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gt2uivvvqfk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzetneyi.html

Go:   // 手写 map[string][]T
来源：http://dali.zycfv.cn/Article/details/gt2eyhebdtk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gt2zbkkztdh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gt2gkpfwnyh.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gt2tzaddhpz.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2ubyebkse.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gt2mkynyvoy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gt2naolxtun.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gt2ejvesnue.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gt2diclztia.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gt2kvuaxseo.html


<!-- 参考信息 -->