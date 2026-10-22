代发 wailian999

Py:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gt2gskgumcj.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gt2fwdgktzr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gt2boqqkmul.html

TS:   return { a, b };
来源：http://dali.yuxming.cn/Article/details/gt2wnwpzpnm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gt2bkcrfbiw.html

Go:   return a, b
来源：http://dali.xinyue.icu/Article/details/gt2jhfsquww.html

Ruby: return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2jaboyzwu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gt2owadlphm.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gt2qeewrvgf.html

Py:   square = lambda x: x * x
来源：http://dali.gzhubu.top/Article/details/gt2edgcojab.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojzvfvld.html

JS:   const square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gt2vdupubgt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wadbwlbh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2pfwiuejw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.havefunace.top/Article/details/gt2qrlthmen.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gt2juaqshca.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2ndkjyvpc.html

[C07] 把函数作为参数传入
来源：http://dali.sysykeji.top/Article/details/gt2ccrssyxt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gt2ihczfxas.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2zvcztfsa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuxming.cn/Article/details/gt2ykpyqcmq.html

TS:   arr.map(String)
来源：http://dali.yj20258888.top/Article/details/gt2hsagitkm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gt2yqddplkm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hywenlv.cn/Article/details/gt2fbxypfid.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxbbhjhc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gt2dynwxdfk.html

[C08] 闭包
来源：http://dali.ybcxt.top/Article/details/gt2uqslsyrq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qlgcpnfl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dashuyun.cn/Article/details/gt2odtmefoy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gt2yaojoaqj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2tymuggqz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gt2rfnziwij.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gt2ilyuxuiu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gt2bjxajjpp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gt2luodedkj.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gt2ianqfrte.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gt2cygfmrfv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnqzz.top/Article/details/gt2jrfkygsp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gt2kggarzkg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gt2kueengha.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qiolelig.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gt2hfrzvumu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gt2tjsweoqf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gt2pmenmryx.html

[C10] 变量作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2aexsmatg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenlongwang.top/Article/details/gt2slaerchz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.bjfxy.top/Article/details/gt2kdujbgry.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gt2nnpruvok.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gt2bdagaiga.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmzybwnt.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2vdcqgzoh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gt2ubxvejym.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2imgwqkxj.html

[C11] 模块导入与导出
来源：http://dali.dashuyun.cn/Article/details/gt2ztbevigw.html

Py:   from module import func
来源：http://dali.ivvv.top/Article/details/gt2nplxynbw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgfzy.top/Article/details/gt2nuajtgpn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtgsznbl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnxiangtu.top/Article/details/gt2uxubzibu.html

Java: import java.util.List;
来源：http://dali.sweek.top/Article/details/gt2xsvrmtxj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gt2thlkloaf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gt2tojsacih.html

C#:   using System.Text;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwmbkvsm.html

[C12] 立即执行函数 IIFE
来源：http://dali.aibaodan.cn/Article/details/gt2szekhcut.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gt2bjpgtjgl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gt2dyppnwdu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gt2vlgujmsl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2hipnpdvn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.mhx1999.top/Article/details/gt2lruupnqi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gt2tvzhtgxi.html

Ruby: -> { puts "run" }.call
来源：http://dali.smart0.xyz/Article/details/gt2ztphfrga.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnibrmww.html

[C13] 类型声明 / 类型注解
来源：http://dali.quarkkingdee.top/Article/details/gt2ystofvet.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjrscyyy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gt2hnttaoue.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fzhhl.top/Article/details/gt2qacdvdiz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2qtbpxjfe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2tcgeiaop.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gt2kesymuvp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gt2cjzchsuz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnpnnoic.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gt2mnwzzagd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2bpgydrbs.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2xcfuiwfn.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjsafmzf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2shxbxhsj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgfzy.top/Article/details/gt2ehbreevw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gt2nlukbgqv.html

Ruby: # 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gt2suwmhqvc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gt2htopuanb.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gt2pjqzbbns.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sacdtdun.html

PHP:  [$a, $b] = $pair;
来源：http://dali.vqdsnc.cn/Article/details/gt2bwmiuiuf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gt2pfpwcrwc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gt2kbyhdncg.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gt2jwhggadt.html

Go:   // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2irnqiyed.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gt2tqztddno.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gt2yqqkjbic.html

[C16] 函数 / 方法重载
来源：http://dali.yangfankeji.com/Article/details/gt2nsqeuupv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuxming.cn/Article/details/gt2sihxbhzr.html

PHP:  // 无重载
来源：http://dali.snrcjt.cn/Article/details/gt2hjtosznq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ydzc1.top/Article/details/gt2smjjdhxk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gt2dxrssgcj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gt2dhsiwjhq.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gt2qncwibps.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gt2tzlekicr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2kjpyofuu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2jlrmmqdl.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gt2azrodego.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2xleprlxg.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gt2wetdpigc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangdashe.top/Article/details/gt2swrhlgev.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daxiang520.top/Article/details/gt2cctopfzu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gt2ysmvvzwa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gt2egfddgpa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tian-w.cn/Article/details/gt2hbhsbfwu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxjwmcyw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gt2scbvxqxc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gt2mwlcstpw.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gt2dcctwxco.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuanzx.com/Article/details/gt2rnkvoxph.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.quarkkingdee.top/Article/details/gt2vkjvnfzn.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gt2hvfwdncm.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gt2ufbgrsty.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gt2expxdplj.html

Go:   arr = append(arr, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2emdsgjle.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gt2rddththr.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gt2hedzkkfz.html

[D03] 在指定位置插入元素
来源：http://dali.birdmap.top/Article/details/gt2lmdwghgd.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gt2yujuelkl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jycgzspz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hfpthk.cn/Article/details/gt2vikaqlnr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2bdpgpyna.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxhbvtkp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gt2tqpgynrd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2slbxgqhy.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gt2dikopbef.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gt2bnxkqack.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gt2wvvvnjzn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gzhubu.top/Article/details/gt2bxrffjlf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cqqwz.cn/Article/details/gt2liuuxlhe.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gt2tposxjtu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gt2ymjkroaq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gt2zgbjdsgi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aizwys.cn/Article/details/gt2tjmnjizz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gt2zzrvqrqs.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhgmekg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2gxgtwqco.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2umstnqgf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2lbrmqweq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gt2sojrmwxw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tanke756.top/Article/details/gt2pnwenyjd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2pwpvhbaa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2jwqzasyw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzzltlsk.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2ldttzgom.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2iofgaguo.html

PHP:  count($arr);
来源：http://dali.c1oappe.top/Article/details/gt2zrajvvnp.html

JS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gt2rpnvlmuo.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gt2lxsvzrww.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gt2obixruga.html

Go:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2oushsjhq.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gt2zwqzbkho.html

C#:   list.Count;
来源：http://dali.cheryme.top/Article/details/gt2oxqxfqlc.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gt2snkvbfuv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gt2omojlika.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gt2npeqrtnn.html

JS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2xyujtzwi.html

TS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2muofscjb.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2ncmojbvn.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gt2yyobrqax.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2lsoljtuj.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gt2noswdipo.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhjodkak.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vweweirw.html

PHP:  array_merge($a, $b);
来源：http://dali.yangfankeji.com/Article/details/gt2qzuqocfo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbmlnly.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gt2hxovlkwi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gt2ipizoxef.html

Go:   append(a, b...)
来源：http://dali.xylfe.cn/Article/details/gt2qrtebqib.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phpsqroq.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2symzkdce.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cltgvfwh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2lycjchgo.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gt2kvmawzcq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gt2nethdhwn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhoulong.xyz/Article/details/gt2izvmeacl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvrdqdqk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2bdymrcgw.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gt2wqanrzpe.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gt2bdrfsisl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhoulong.xyz/Article/details/gt2daodnfpu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gt2jnulujtf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2pnwttfsa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gt2zvnoqjbf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gt2mshnwqjq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gt2bolosiov.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gt2swzsxcyj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gt2nrpoftwe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuanzhike.top/Article/details/gt2qvuoxsfu.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gt2nlgaxhrt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gt2cjacrmll.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gt2ougotbio.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gt2peblnzxn.html

TS:   [...arr].reverse();
来源：http://dali.jianghu66.top/Article/details/gt2gtbqqlsx.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gt2esgwqnec.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gt2dbvoszqy.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qqwqpuvx.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2plebsyqd.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gt2qihibnce.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gryvizwe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2nercwkay.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gt2ccmtotdz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzhwickm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gt2gzcikgom.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2agnxscsg.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gt2domozdwq.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gt2dufqcztg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gt2azodnwpq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gt2tizgoody.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gt2vfxvejar.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2stmlokqe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2zcsruwnf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2ydedvmxp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gt2sfvydary.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2azxnpxwn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2xtqqdrpo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gt2jstzlzvy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2tqexgckj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gt2kkutqwvc.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpkuciaf.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gt2falptzgd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnqzz.top/Article/details/gt2rtktfsst.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2wowlrmpp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2fiemrlcx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gt2ituwccvx.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owggxjuw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gt2mvcdcfow.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2tnfapnkp.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2buhvohtj.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghsgvaec.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gt2kaqtvkgm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gt2xmseqdue.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gt2icfmbwbl.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gt2oienswgk.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gt2vhkqqtzu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2phxoafnk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2sslfnysm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gt2kaqykjdf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2bgzxhmvm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gt2eiccjzsj.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gt2fsbertwj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhongyouzk.top/Article/details/gt2bjxdlolk.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gt2agrzyhiv.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gt2hlpaqaru.html

Py:   max(arr);  min(arr)
来源：http://dali.daxiang520.top/Article/details/gt2nducacpq.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxzybgql.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysmxhvtg.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gt2chjkaqvc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gt2peaciznv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lavjsmkl.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smjlmtiq.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gt2bebmfxeo.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gt2fpryvdfa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.haohaochexian.top/Article/details/gt2qolxdyks.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gt2cwywtjzc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.vqdsnc.cn/Article/details/gt2vlokjngq.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gt2jklusasz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2azfirlau.html

Go:   // 手写双层循环
来源：http://dali.ivvv.top/Article/details/gt2ysrqttkg.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gt2nqqnuudy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2romnthif.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2neulfzfw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmsicpva.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gt2vkvxhrbz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgfzy.top/Article/details/gt2xpcnakpy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2btqocboa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qyrxqgtk.html

Go:   // 手写 map[string][]T
来源：http://dali.yuxming.cn/Article/details/gt2itdtrsnj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gt2lxqzqvmm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dianchejie.cn/Article/details/gt2chifozsr.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2iquphidx.html

Py:   Counter(arr)
来源：http://dali.tanke756.top/Article/details/gt2usouxiob.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gt2tyqfkcix.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2ivvghaeh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdkdvovh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yueranfly.top/Article/details/gt2sakqrmhl.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gt2eczvbnhf.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gt2tlxgkpeh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gt2rcfewwxl.html

[D21] 判断是否包含某元素
来源：http://dali.zycfv.cn/Article/details/gt2lcesgebq.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gt2dycdzowu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbedwubt.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfpdrljh.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2nrdxybfq.html

Java: list.contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2khtoypri.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2dabwwbaa.html

Ruby: arr.include?(x)
来源：http://dali.sxryk.cn/Article/details/gt2oagyamck.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mmqqpwor.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gt2ezqhajbf.html


<!-- 参考信息 -->