代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.daxiang520.top/Article/details/gtyoapikor.html

Ruby: f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtnktojrlr.html

C#:   f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtufbaudua.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gtfdavmsal.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtnawfzndq.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gterhwgxfp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gtejegnowj.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtquasqguu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shangyingyoupin.top/Article/details/gthcojhdfs.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhkxtqck.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtfbndjtdl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gtcoeapssi.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gtdxgytlzc.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpksybbzd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gtrrzsmqud.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtpeygyiww.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.andypj.xyz/Article/details/gtysdiyziy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gtpdfwjgcr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtfgavetet.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtpctztfmm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtzwvzmctf.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gtppzhlagl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ehwqpu.com/Article/details/gtfqjcgwgj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtqfouoxqo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.bjfxy.top/Article/details/gtwfjafeql.html

TS:   arr.map(String)
来源：http://dali.hywenlv.cn/Article/details/gtjvcppeev.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gtkmfxwnef.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaypsgcdy.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtaxwgraxf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hammf.cn/Article/details/gtxuqzsaii.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gtdtrsyiit.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sxryk.cn/Article/details/gtejnzdpps.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gtsaapezyo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmpcjfoeq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtxvwmnbac.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmhvvhur.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fzhhl.top/Article/details/gtfrlsyzuz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikbaxmpo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtmvuvpjuv.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gtiissgfxx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtltawmqxd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gtfidnxopr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gttezoemjg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtutpcsinu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtlqxoqreg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gtjmlrrrcs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtufiiwlay.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xziqi.cn/Article/details/gtellezemf.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtdhvqekpu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangshuangyany.cn/Article/details/gtuklxjqyz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gtswkprxsw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gtebffkqoj.html

TS:   同 JS
来源：http://dali.sweek.top/Article/details/gtpidiktey.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtxtnwmata.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gtqmwuxuax.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gtvjltndgp.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gtiemxzmfu.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gttothikry.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gtcwcqvimc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gtarvklcrz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gtkredxeis.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gttypovxcz.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gtgyvhhhra.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gtibqtnylx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gtcahijzds.html

C#:   using System.Text;
来源：http://dali.316326.xyz/Article/details/gtdraalzjj.html

[C12] 立即执行函数 IIFE
来源：http://dali.cqqwz.cn/Article/details/gtfllbcreb.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gtkxzhpqlb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gtrorrnpng.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gttxwmufsu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtixuqrdod.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gtkovqftxs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gthfnsddra.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gtqzhwhpmi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gttydsaiph.html

[C13] 类型声明 / 类型注解
来源：http://dali.sysykeji.top/Article/details/gtmwsaqrdo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gthixppdly.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtjjqaivgm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hywenlv.cn/Article/details/gtwbhledih.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtiyahclxh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtlbyfvrcy.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gtxgduxqkj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtfmhtdqhb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yangfankeji.com/Article/details/gtrxvvlreb.html

[C14] 泛型函数
来源：http://dali.ydzc1.top/Article/details/gtgvfwpprt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhongyouzk.top/Article/details/gtfgvojxdw.html

PHP:  // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtqetamjxx.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtjwpzhsty.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnqzz.top/Article/details/gtsrsjsyba.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gttzipqyqs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.redwolf501.top/Article/details/gtritrppgq.html

Ruby: # 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gttsgvzcse.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gtmysryezp.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gtuzmicvya.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiexaheud.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdkwxvke.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfufsupvg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gtzojdgduj.html

Java: // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtyrmfsuqx.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gtxmwchqvo.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gtubovzoux.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gtdwytsedf.html

[C16] 函数 / 方法重载
来源：http://dali.nanxinkj.top/Article/details/gtcvtuwhqr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtwnhuhq.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gtstdcuahl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gtrgvhnbeu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gthcnpeixp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cheryme.top/Article/details/gtxcrawskz.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gtscvebcoy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cqqwz.cn/Article/details/gtmnmomejn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrvuzneux.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtyfhaozyi.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtboalynyt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtsweikfwp.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtwyyloupo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gtlrmsfbfy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gtvkzvbicf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hammf.cn/Article/details/gtymykqekh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dashuyun.cn/Article/details/gtkjgkfnru.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yueranfly.top/Article/details/gtgvppzlyx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gtqzkmmyaf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ehwqpu.com/Article/details/gticjztdxf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gturyofvhl.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtnmjenauu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nwbrower.top/Article/details/gtosdozolo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gtettbtavc.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcvdktoz.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtbwcdqeob.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtefhbscoz.html

Go:   arr = append(arr, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtrattvvhw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gtmeiakbly.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gtyszrygwj.html

[D03] 在指定位置插入元素
来源：http://dali.svipenyu.cn/Article/details/gtlmmipcxc.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtpteqjxfm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigfzy.top/Article/details/gtcazoktcf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gtndcajdcg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtlnqnqagw.html

Java: list.add(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtqxiqqdgs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gtqefauzlk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gtyfbzbycz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtzhybcbaj.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtqqewfong.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gtgsjvtzzm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gtnzlgqvxl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gtzzmbqadi.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gttaghvipo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gtrbtugupi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gtspzgogcy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gtvpwrlhcz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xziqi.cn/Article/details/gtfwpvsvha.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtbaupktoo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtrrhcwfqg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtbusrdzpd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gttdqkmsqf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtwtqzjodz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ppjwa.cn/Article/details/gtuxapcvll.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtoojqpsmo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gttigebpvk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtctfgarof.html

[D06] 数组长度
来源：http://dali.cheryme.top/Article/details/gtuliibuhx.html

Py:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtbdqjcxtq.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gtvhkdhvdk.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtoplhpury.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtzjzispnt.html

Java: list.size();
来源：http://dali.nwbrower.top/Article/details/gtuzmrodzh.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtwrrylite.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gtwofasyta.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtzntfhnoy.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gtauaqapms.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxuanxn.top/Article/details/gtsygefrfq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtpbbvklda.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtsycqsszf.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtiqxdpuen.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtkssvglep.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gtyyueyyut.html

Ruby: arr[1, 3]
来源：http://dali.tian-w.cn/Article/details/gtcqqkauhz.html

C#:   list.GetRange(1, 3);
来源：http://dali.havefunace.top/Article/details/gtrsdbzmkq.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gtmpsgkdkh.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gtnqnfysvo.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gtvbblccrd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jiagoushi.top/Article/details/gtzhmhqkka.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gtcrlwiknq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtqjpvznlb.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiexaqhck.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gtfcrryjfd.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtcrqpeqek.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gtbeffxmru.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcttbapxz.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gttqeatmxh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nwbrower.top/Article/details/gthkomdlts.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guannengcc.top/Article/details/gtfzywvbuh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gtktufmliz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtkdvziitt.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gtnwksetit.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gteyobfmdq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangdashe.top/Article/details/gttpldonuq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gttfwwpjoj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtrcwwcqgb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtunmyduyp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtszkfxmqd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tanke756.top/Article/details/gtfuikwiom.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gtmpndubcv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenjidiqi.icu/Article/details/gtjfapctfb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gtpecfoknd.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gtdfgipxhq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gtlrhypbpp.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtnsllediu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuxming.cn/Article/details/gtadimefzy.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gtnaybujln.html

Java: Collections.reverse(list);
来源：http://dali.yuanzhike.top/Article/details/gtzwerxgsu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtrjzbvkzg.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gtkgpazyah.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gtxsgeavzf.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gtyyaiznxj.html

Py:   arr.index(x);  x in arr
来源：http://dali.ivvv.top/Article/details/gtlgyzziyg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guannengcc.top/Article/details/gtbbzwxmom.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtwrpaqznf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtrbpofvjy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gttnjavpnp.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtvripfjph.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gtcesqzrul.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gtztnlruyi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gtnsxciuqo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gtcmdymlkm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gtqzfvvdcn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcibuwhv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtcxxitkjy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.mhx1999.top/Article/details/gtiutoqcvu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gtznqhlbtt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtxkvdaboh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gtxakeojsm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gtyxugonqw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gtqvqgmkij.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zdqjudy.top/Article/details/gtmlhyafhj.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtcigpiveu.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtegfbelgo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtdiuiihfr.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtmnxgeuqd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtkzsgqxkr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtaaxbkljg.html

[D15] 去重
来源：http://dali.yangfankeji.com/Article/details/gtubnxhajv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtfmimjspv.html

PHP:  array_unique($arr);
来源：http://dali.zycfv.cn/Article/details/gttlaezjkc.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtzxdzenki.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtxaocxmci.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gtoscdwixh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gttfqbrbng.html

Ruby: arr.uniq
来源：http://dali.meibo888.top/Article/details/gtdeguazet.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gtgvizqcio.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtwuslnegr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtnyuwkjek.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gtwinzrlwt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtiaqxrljh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtzldbohmv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gteazvrroh.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfvhaium.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgfzy.top/Article/details/gtoxicvhve.html

C#:   list.Sum();  list.Average()
来源：http://dali.tanke756.top/Article/details/gtzyboppzn.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gtmvxipbja.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtldqumchy.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gtvrzqtoaw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gtlzrddwde.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtxbsxiwdo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtdonoovhe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gtildbjtjc.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtvrijylnk.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gtlsqutfns.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gtbulxpofd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtowaadrvu.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gtiqlonxbj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gtrwpjebmh.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtttewwijz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtycdorxwr.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gtkduncnen.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gtmzwhhiwf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtfznxxplp.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gtykovtpso.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gtplohalmz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gtfgyxtdbw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gtconqifig.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gtlijtmnso.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtizaxmixj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhoulong.xyz/Article/details/gtirlltepk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtmltdlwpn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gtjtdgitvm.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gticcvhzld.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzesuewzw.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gtgnpgpfqm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtrqhbeobp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtngwqwpbt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtiapmepay.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtwydwbjqn.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gtyflhktlk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gtutxzomvc.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gtqqxzodua.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtxiltnmlm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gtouozbzyt.html

JS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtsouejlpg.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtttmahyky.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gtdrubiduz.html


<!-- 参考信息 -->