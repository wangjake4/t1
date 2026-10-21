代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gtcwfhbigr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtnjnslqwd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gtigaglspc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhixingplan.top/Article/details/gtvhjnlwwb.html

Go:   // 无：用配置结构体参数
来源：http://dali.gogol.net.cn/Article/details/gtrfwtaodl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtxedtzsqv.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtnmlpkrec.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gtbnzulxzm.html

Py:   return a, b
来源：http://dali.xylfe.cn/Article/details/gtblfydrgt.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gtistmkilf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtdqbkrgxs.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtaanbjozk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuanzx.com/Article/details/gtggpuzzcf.html

Go:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gtvruslhfk.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gtddpmjalb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dashuyun.cn/Article/details/gtcxwikcll.html

[C06] 匿名函数 / lambda
来源：http://dali.daxiang520.top/Article/details/gtazwlruoa.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtzdlvxrrp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yonumen.top/Article/details/gtqdsqztqb.html

JS:   const square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtloqwawep.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtwfmzogrt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gtvmecmyls.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhixingplan.top/Article/details/gttrflnewe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gtumiosldo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtmzbgrhsj.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gtacdbbops.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhengqikj.top/Article/details/gtzhkxfsbq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pycfn.com/Article/details/gtyioybeyk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yongpay.top/Article/details/gtmatlfuav.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtyahjxrkq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtdljjdzcj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sxryk.cn/Article/details/gtkkexsqsu.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtuiaiplmj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gogol.net.cn/Article/details/gtouzqvxgs.html

[C08] 闭包
来源：http://dali.shzxlz.cn/Article/details/gttiebzwpk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gtwvbgogns.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtimbrtoik.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtafrcapmp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtimgbpdfg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jlsjyb.cn/Article/details/gtukmhesgl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.0kj1m.cn/Article/details/gtatnddohr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gtiyufonyc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtyemtnnnb.html

[C09] 递归
来源：http://dali.meibo888.top/Article/details/gtanueyytb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gteilbmkof.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj202588.top/Article/details/gtojcppizj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gthqisukka.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gtylhgeneg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gtiebqixxt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gtdaxrborh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtdmvwamoc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtawcimrcn.html

[C10] 变量作用域
来源：http://dali.vqdsnc.cn/Article/details/gttvatmplr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtxizekgoh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daria6918.cn/Article/details/gtzgezvanv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gtonnwjhgo.html

TS:   同 JS
来源：http://dali.0kj1m.cn/Article/details/gtfwjsjpsi.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gttijvibnf.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gtdqggaffb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gttvrvfegr.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gtejfugwty.html

[C11] 模块导入与导出
来源：http://dali.zhongyouzk.top/Article/details/gtynmdlpuu.html

Py:   from module import func
来源：http://dali.shuidangran.top/Article/details/gtuyrduclv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gtrmslpeuz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gtrgafgeee.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtpwxzpgjb.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gtigaxriay.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gtxxeiqljt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtsxpcnxjg.html

C#:   using System.Text;
来源：http://dali.xziqi.cn/Article/details/gtvtlxuwzo.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gthwebkink.html

Py:   (lambda: print("run"))()
来源：http://dali.cucudq.cn/Article/details/gtmhldluhc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gtvjomudzc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtcoaeewhd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtokujiwba.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gthjkaxxtt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.9152youxi.cn/Article/details/gtuuuvowmn.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtmkknhqup.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.smart0.xyz/Article/details/gtsgcersdz.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258888.top/Article/details/gtmxbgbuzh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gtjxnulcww.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtuyihlwkp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gtyojqotke.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtgrmehyva.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtphqjcmgs.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gtbyrmmcbf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.meibo888.top/Article/details/gtltmtqrfd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gtvfuuwkwq.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtmyvmdbwr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtzqvjsbjb.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtvlxuypip.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtdpnsprqx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gtjeaicczx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gtrkkkldaz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gttfopddhw.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gtlrafzdpx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gtjmfyvdwn.html

[C15] 解构 / 展开参数
来源：http://dali.redwolf501.top/Article/details/gtrwgmjmfd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gtmekzqaeb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gtwbokxixw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtervnskbt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhpipeir.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gtlqwntwpv.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtjgkjapmq.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuvddezi.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gttilwzsfa.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gtpiypyvzl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gtpbdhofzb.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gtdmpekqta.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gtiuedvhnz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gtzcvtdelu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gtmnnjfbqz.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gtlcyqiqyv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gtoymjmyyu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shuidangran.top/Article/details/gtwnibwjrj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwiqxnbxo.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258.top/Article/details/gthmjskbde.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtkqkeyghn.html

[D01] 创建数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtgfafxylq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gtmatpjhnl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gtvlabrbir.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gtcytugvko.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shangyingyoupin.top/Article/details/gtrikscnyc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gogol.net.cn/Article/details/gtnuzygzav.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.haohaochexian.top/Article/details/gtowypqobk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnozcaalt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfnlnkyt.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gtsvnwrnpm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtbxvcugdn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtidknqskb.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gttaxuiamk.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtwpdnyhoq.html

Java: list.add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfkyyvex.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gtzmwviapk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gtijbtchbg.html

C#:   list.Add(4);
来源：http://dali.hysaishi.cn/Article/details/gtbypmpyqj.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gtdjnacwry.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtahmmlkrv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtavgxqyzx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.haohaochexian.top/Article/details/gtiwychhlu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gtkdhrgcgc.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtxvuiapmo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gteisskuvd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tianlin.xyz/Article/details/gtgjwgjnmt.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtpxvzixgp.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gtlbmctdgo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dianchejie.cn/Article/details/gtfifwhhbt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hywenlv.cn/Article/details/gtzwvkzlyt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sufxvd.cn/Article/details/gtuldnmakk.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gtykcmaevy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gtjeqzsupw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenjidiqi.icu/Article/details/gtphfvlaty.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gtvbsjrzsf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gtzqyzsajl.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangtech.top/Article/details/gteisfmwfb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtybxguans.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtxfdfcloe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtrexiwmub.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gtcuqmtecm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gtsuxfpeix.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjgjjczb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtdbyvsczs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtmyrixmhv.html

[D06] 数组长度
来源：http://dali.ivvv.top/Article/details/gtudzjbhnz.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtawfehqef.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtpykrpzdg.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gteslfmsrn.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdcfasks.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gtjvjycmbt.html

Go:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtgarbbnyc.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gtrcwjmsxs.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtkdpnvglc.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gtorcpcsnl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenjidiqi.icu/Article/details/gtccatmkdc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtlmztectr.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtdnxmkrdg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtaquhdbed.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtnfliydkd.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtwkhomvjd.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gtkwwtaigi.html

C#:   list.GetRange(1, 3);
来源：http://dali.c1oappe.top/Article/details/gtabbvgdos.html

[D08] 合并两个数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnynrxlao.html

Py:   a + b;  a.extend(b)
来源：http://dali.snrcjt.cn/Article/details/gtfoifvzrc.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gtseypbppa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhiwuduotai.top/Article/details/gtlhvffurl.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwilutaz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gthurvxyxh.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gteqdxdqzj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccypwxyk.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gtzafgeskt.html

[D09] 排序（升序）
来源：http://dali.sysykeji.top/Article/details/gtkfnoiuwc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtopouibsq.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gtppeilnhi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gtpiiatmhr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtaoeanbhp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxuanxn.top/Article/details/gtyyzoexms.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtqdcgzmtg.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gthogrfmqu.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gtenkpdzcn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhixingplan.top/Article/details/gtnkpzjbkm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gtfoqypecj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrakahxl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmacumpj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtirruuqos.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gtgiyynebo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tianlin.xyz/Article/details/gtyycdalmq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jianghu66.top/Article/details/gtmmdfmocc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yangfankeji.com/Article/details/gtdflvmyyb.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gtlpihrrgb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gttiqgcoin.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gthqtxhpwv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gtenzljzal.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gtuuplszrm.html

Java: Collections.reverse(list);
来源：http://dali.iojbl.cn/Article/details/gtmbualtwb.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gtiulakzkv.html

Ruby: arr.reverse
来源：http://dali.hammf.cn/Article/details/gtkfkojznv.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtotrngrqs.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gtwawtuuqw.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gtamzwznuq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gtzpczstzr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gttqvctusa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtgdkyytnk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gtwqcsloip.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtzfqlmyrc.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtwxsmhtfe.html

C#:   list.IndexOf(x);
来源：http://dali.yj202588.top/Article/details/gtekcqvdui.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nwbrower.top/Article/details/gtwqxwzopx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gtpdiknbfc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtzhhnor.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gttrnyqept.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtvxtpwwot.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gtjymariir.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gtdjmlywoa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenlongwang.top/Article/details/gtjlekpnyr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtzyrogaza.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gtunoqqdch.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dashuyun.cn/Article/details/gtacxtlrhz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gttogguglv.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtjkodiyjh.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtywnxryud.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuynusbri.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtwazvqjec.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtqehfunqd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtswptwgpc.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gtdhxzqcpo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gtlqyijrxc.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gtnuczwkjp.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtzonjxdqk.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtfmlsrefs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtmiwowlim.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.andypj.xyz/Article/details/gtentwdlpi.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtgjesfqrj.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtuzquimbd.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gtgiwgctkh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtkcaricbs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtrqxkxnfh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtlwryukfm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtyfzfiego.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtselfrspq.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gthjkeagxq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtxxbftpwu.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gtjzjnzbva.html

[D17] 最大值与最小值
来源：http://dali.xinyue.icu/Article/details/gthsdezzng.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtsysximul.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gtndbvfmua.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gtbjbinhfg.html

TS:   Math.max(...arr);
来源：http://dali.quarkkingdee.top/Article/details/gtnxyoaivi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gtedebztbe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gtkhyclxvr.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdvuubtg.html

C#:   list.Max();  list.Min()
来源：http://dali.dianchejie.cn/Article/details/gtbrgdtbzr.html

[D18] 扁平化嵌套数组
来源：http://dali.zhixingplan.top/Article/details/gtmjeherkj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gtuavsrqrc.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtpdahayzo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gtfyuitpdp.html

TS:   nested.flat();
来源：http://dali.shuidangran.top/Article/details/gtbpqnkxml.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gtlivnghjc.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtztbkankw.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gthuhmysaj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gtnrgxlstv.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gtirfqzpou.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtvqktlyqs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtjetbfgzw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gtebqnxmfr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gtyzsdwmax.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gtefxmbmic.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gtdnntcqeu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gtdojayecy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gtggmbkafa.html

[D20] 统计每个元素出现次数
来源：http://dali.daxiang520.top/Article/details/gtbydsqzsm.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gtwbfqcgoe.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gttyzvndop.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gtscdykwht.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtaflftsjj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yvedp.cn/Article/details/gtqfgxvwig.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gtxqococds.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtunetpppc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gtigqjlxco.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gtwcupmlfw.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gtjtgwyehp.html


<!-- 参考信息 -->