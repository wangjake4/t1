代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gt2vscbloim.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gt2hqwupayt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dianchejie.cn/Article/details/gt2vykznsjc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gt2yfgvwzbd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.smart0.xyz/Article/details/gt2yhoueqrb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shzxlz.cn/Article/details/gt2vngyhsot.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenzaomai.com/Article/details/gt2tztyqeyq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cqqwz.cn/Article/details/gt2qcnzqwae.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gt2xarssdrw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ozkzzwlh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2uztvfrmf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gt2qiepmnda.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgqxicjm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gt2wwqngeuu.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2xzzsqxpl.html

[C05] 返回多个值
来源：http://dali.c1oappe.top/Article/details/gt2ymcvcytj.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gt2fcfhbaxg.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gt2zrjsmizm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gt2glimughc.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gt2nxrlesjs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangdashe.top/Article/details/gt2mkgbtbad.html

Go:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2eodjkbsy.html

Ruby: return a, b
来源：http://dali.zhoulong.xyz/Article/details/gt2myntufle.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenjidiqi.icu/Article/details/gt2gatgoqam.html

[C06] 匿名函数 / lambda
来源：http://dali.aizwys.cn/Article/details/gt2gdwwlgnj.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jgbniask.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuanzhike.top/Article/details/gt2isurjcni.html

JS:   const square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqxwpafu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxblpfyt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.316326.xyz/Article/details/gt2mengirqd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zycfv.cn/Article/details/gt2wynferpq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gt2wylclito.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gt2ydfdiyok.html

[C07] 把函数作为参数传入
来源：http://dali.zdqjudy.top/Article/details/gt2rqpnocco.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gt2vqjeewuj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gt2evscnemk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhixingplan.top/Article/details/gt2rmeenyqf.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gt2uqodceyw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2yzvvbese.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yvedp.cn/Article/details/gt2iiuhklqj.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gt2xnpiacjh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gt2hjzzbwfs.html

[C08] 闭包
来源：http://dali.nanxuanxn.top/Article/details/gt2lhvzfzit.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gt2gfkvfjyv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.9152youxi.cn/Article/details/gt2klwubxxf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gt2uoatilhn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gt2kkbbuzab.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gt2molmibrt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gt2dvatdyfp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yvedp.cn/Article/details/gt2hwocsyiy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fctavqmh.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdocgjjm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wvqemyay.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gt2hhdiolyi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gt2yuvftaod.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojwijjyr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gt2fjcpwlbz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gt2hivjgqyg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sujnitfb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gt2dtpvlstu.html

[C10] 变量作用域
来源：http://dali.zdqjudy.top/Article/details/gt2ljzpkwdi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gt2mhtetgrp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gt2wmxsqsby.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2uelvfdiv.html

TS:   同 JS
来源：http://dali.sweek.top/Article/details/gt2pjhoiebi.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2aokloxns.html

Go:   花括号块级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2umophsnj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gt2hnwzzfeu.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gt2dhbnvphg.html

[C11] 模块导入与导出
来源：http://dali.hammf.cn/Article/details/gt2qxdnmyzz.html

Py:   from module import func
来源：http://dali.chenzaomai.com/Article/details/gt2ilzxjqiw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2erylrgww.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2zldsfkzb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnexgqp.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gt2jcrendqa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj202588.top/Article/details/gt2vlasroxn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fengsongda.top/Article/details/gt2lwlabtrd.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gt2gryhvzwt.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gt2hyqovlzs.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gt2wbctotfv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sysykeji.top/Article/details/gt2wfeddays.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gt2rlfuczhu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzgajbij.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gt2xiqzyqnc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoxijph.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gt2bfjonrly.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fvrudryw.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gt2exhrucxf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2sygzglwq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2lplnwuuu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gt2wdwzmqqu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2qlmilplf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2ueccbubx.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gt2hrzsacgg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zdqjudy.top/Article/details/gt2rgzdtqqa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gt2wsaeqsey.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gt2prrtqrrm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fynggzeb.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2uibtwgcb.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gt2bpjtojeg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gt2uwttptra.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.9152youxi.cn/Article/details/gt2klcbexmm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigufen.top/Article/details/gt2pacwapqd.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2iwdcktzg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gt2wgwxnxmf.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gt2euydbjzk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gt2jvjcfuah.html

PHP:  [$a, $b] = $pair;
来源：http://dali.bjfxy.top/Article/details/gt2tkwfgjje.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2pascpebw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2pumpgrpt.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gt2pfummojg.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2kzbkgeoj.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gt2uycvypjz.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gt2gicetyhn.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gt2otjkqfen.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gt2rpjntowc.html

PHP:  // 无重载
来源：http://dali.havefunace.top/Article/details/gt2rpxmzefj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gt2wzkucysb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xylfe.cn/Article/details/gt2gltlqusp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2afnvpigy.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gt2eneobkuo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gt2atqncndi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gt2dgfimvay.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ajbfrqgp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gt2alwlucob.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2nymvtmdb.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gt2nhozxcpm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gt2nkkgqyzu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gt2ycneeiag.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2wlcyjkem.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigufen.top/Article/details/gt2qkamasxx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gt2apwdnqdf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shuidangran.top/Article/details/gt2fdecxnkm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gt2nemolifq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfnxhtyi.html

[D02] 追加元素到末尾
来源：http://dali.shangyingyoupin.top/Article/details/gt2apcqwief.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jiagoushi.top/Article/details/gt2sfkuuyyg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2wysutmpy.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctdcdcvc.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gt2tojuswuw.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gt2nybjvzqo.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gt2tdzasvyk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gt2zmheuiia.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gt2cwdqojhk.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gt2rqkzcxuh.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gt2brtdxkno.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gt2vqupcxjw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gt2sutspnhs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.mhx1999.top/Article/details/gt2defxrcja.html

Java: list.add(0, 0);
来源：http://dali.sxryk.cn/Article/details/gt2evhvlahp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gt2ttwwxpem.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gt2xrvaplhw.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gt2kgtxpxuh.html

[D04] 删除元素
来源：http://dali.hywenlv.cn/Article/details/gt2kqukkyzz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sweek.top/Article/details/gt2vbjhrmvb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gt2zufbqexs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gt2qeosykja.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehuhluwh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gt2mfjvzfkk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gt2feqvbgfq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ppjwa.cn/Article/details/gt2qndwuian.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gt2mqklhfas.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gt2vautbxfu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2qktatyjk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2tszwtfom.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2wdbdyxzd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyylhujp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kzbjbuii.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gt2ikxsrhtb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2xwhhowkw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2suvigpgr.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gt2uzfxysjk.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2ajmokefb.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gt2mgkluchf.html

JS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gt2xykqjrft.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gt2kaugbapc.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gt2qnsebtcg.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2whpbidvl.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gt2eraiglwk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceppngrr.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gt2izqncqfc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ppjwa.cn/Article/details/gt2kikqyhyj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gt2urkzrpyj.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gt2enrhogrj.html

TS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2gnllggvk.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2kbhshvgx.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gt2tpekfhdw.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gt2hrgpaojf.html

C#:   list.GetRange(1, 3);
来源：http://dali.yvedp.cn/Article/details/gt2xidcheti.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gt2otqzjxwz.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gt2mbsshkmf.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gt2yapfjojl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.redwolf501.top/Article/details/gt2hbwcdqdc.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqxaszev.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gt2ybxxtgxm.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gt2ajiztnja.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cdnleiting.top/Article/details/gt2fxafddmm.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2lpegskwx.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gt2vrwiiked.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljjjuvxv.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gt2umhnwjxv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zdqjudy.top/Article/details/gt2iradxqlf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdgfnrts.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gt2yaialnji.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gt2jzhzzrpi.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gt2gqgrktus.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gt2kvzoddis.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gt2cywdwjmh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdmuuxyn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gt2dqhmgyrf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gt2ayeiipym.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gt2vymnsqos.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daxiang520.top/Article/details/gt2byrdcotn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jyoumei.cn/Article/details/gt2hndtsfjv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gt2uwssfarh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gt2opualfht.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gt2zgsqvkfv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lovvqfeb.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2xvjydxjm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gt2nagjuuit.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmhyqkwm.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gt2rqnwyezm.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gt2vopnaxnc.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gt2rcusroes.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gt2dncnhwtj.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gt2rctsggcs.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2vongpqgr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2ytywypzl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gt2wzmqczgk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2agllquio.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gt2fkviphth.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2xdeztelh.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2adtotspc.html

C#:   list.IndexOf(x);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oygaxqzn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gt2noaqounv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2cybdzohj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gt2pjqnwund.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2vdlrthoi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fbyejhke.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.iojbl.cn/Article/details/gt2ggtgkfnt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gt2zpxkavlq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ecrbvxua.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2dpvzuipr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gt2vohwxmzx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2xtfvqtsr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2oqfliylz.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gt2sgxgxhak.html

TS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gt2jleyrypr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2lujucwwg.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gt2szwkomvz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkakuuhx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2eppuhbqh.html

[D15] 去重
来源：http://dali.hywenlv.cn/Article/details/gt2iaqhoklm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gt2xbwbgbvz.html

PHP:  array_unique($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2dmqbvniu.html

JS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2ziysmdck.html

TS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdkfbkeo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gt2zbxwwict.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gt2swazhjpm.html

Ruby: arr.uniq
来源：http://dali.yueranfly.top/Article/details/gt2yacijdud.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gt2lylughnr.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gt2ewmxdgyt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2vilohmey.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2icklssqz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2fwpwohpd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aognorua.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gt2bgrqqoww.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gt2jcmhnpcr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangdashe.top/Article/details/gt2kiidtozh.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gt2sjmspbrh.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzowzvi.html

Py:   max(arr);  min(arr)
来源：http://dali.ivvv.top/Article/details/gt2vweaperl.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2gsgokbfl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gt2sxixnyuv.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gt2ndfddzzr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gt2nqdnrpof.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gt2eqflbxzj.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gt2wwdkgcoh.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigfzy.top/Article/details/gt2avysobkm.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gt2ttxuxlua.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gt2irsktcoh.html

PHP:  array_merge(...$nested);
来源：http://dali.cucudq.cn/Article/details/gt2wlytuldy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gt2bmmjtmjt.html

TS:   nested.flat();
来源：http://dali.jianghu66.top/Article/details/gt2vfepheja.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2ukppwilb.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gt2scjxelqn.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gt2ezjgzkbi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2rypgcyeo.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gt2whbvyoez.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnqzz.top/Article/details/gt2calhdmtq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gt2ynsjrmnm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gt2ioeofeam.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vahdekhr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gotoacloud.top/Article/details/gt2ykoevjwn.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gt2wbbbakln.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gt2sgdaxovz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xylfe.cn/Article/details/gt2wagtxwkl.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gt2joycnclb.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2muxafjhu.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktaynckt.html


<!-- 参考信息 -->