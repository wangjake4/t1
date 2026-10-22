代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guannengcc.top/Article/details/gt2lziklztn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2hxnofyzi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daria6918.cn/Article/details/gt2ontmyxdl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gt2nwyasslj.html

Go:   // 无：用配置结构体参数
来源：http://dali.sysykeji.top/Article/details/gt2ibajpbkf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gt2dtciofrn.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tolrommz.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfrrigqw.html

Py:   return a, b
来源：http://dali.hammf.cn/Article/details/gt2gojmgqjr.html

PHP:  return [$a, $b];
来源：http://dali.jqgfzy.top/Article/details/gt2ktvgowse.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gt2fwvbzwev.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gt2sjwtdpgm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.vqdsnc.cn/Article/details/gt2dcplnvph.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2imkvzlkn.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gt2ryuxdkce.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gt2zadeyzsp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhongyouzk.top/Article/details/gt2qqftcagc.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gt2xyseqvsy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhoulong.xyz/Article/details/gt2intwofrh.html

JS:   const square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gt2wcpenjks.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gt2xqcfpruh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpsfpuci.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cheryme.top/Article/details/gt2milxkxwz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gt2tifkigtt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2grdjrrcl.html

[C07] 把函数作为参数传入
来源：http://dali.yueranfly.top/Article/details/gt2szaxiruu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gt2uhkfszyl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2hkrundlp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gt2ihitkdkf.html

TS:   arr.map(String)
来源：http://dali.iojbl.cn/Article/details/gt2bmogdvrx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2sxzaraat.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jlsjyb.cn/Article/details/gt2qewonxdb.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gt2xaghldwf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gt2dtrcxrmc.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gt2xaqzelfp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gt2fihjzzwe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gt2ypizemuw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gt2utygmwfn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2wvzzxqgw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigufen.top/Article/details/gt2onaapxhp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgufenzy.top/Article/details/gt2bntwlvaj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gt2adltszqu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgypmcfq.html

[C09] 递归
来源：http://dali.gaohongyu789.top/Article/details/gt2nmpnrobc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2wriwagwc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pycfn.com/Article/details/gt2ijrqbldu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2baybmegq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gt2kaixqvyh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fjhgxljt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gt2yzahkdjb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbsvytev.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gt2rpammltp.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gt2xmsejeax.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xziqi.cn/Article/details/gt2ejgmxsgm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yanxiufei.cn/Article/details/gt2tezetzga.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2gdewfrgk.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2nxlqhrnn.html

Java: 方法内为块级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2hepoegyb.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2cdnoqsuu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eftpadej.html

C#:   块级作用域
来源：http://dali.smart0.xyz/Article/details/gt2zlvwcupg.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gt2yppdwsiq.html

Py:   from module import func
来源：http://dali.gogol.net.cn/Article/details/gt2dbupkkrm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gt2iolbwmzs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gt2popjrqqf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gt2jmzksfvb.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gt2fgyosxap.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gt2zwxoxagi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gt2txvfjxca.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmmisobm.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gt2dgrdjnsn.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gt2ksopxiah.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gt2xvlnuwcn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gt2cjponqqg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gt2hjgaqlqr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sweek.top/Article/details/gt2eegiuhnx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenzaomai.com/Article/details/gt2sgjmpngo.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gt2htrjhjgg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2gbizekvd.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gt2zsvwnplp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gt2owznuabm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2ygvtnmjb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.c1oappe.top/Article/details/gt2mrdhwnao.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2apnpxhbz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2nbisbyme.html

Go:   func add(a, b int) int
来源：http://dali.jianghu66.top/Article/details/gt2cternnjj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gt2wgbnwgir.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gt2jozgpupz.html

[C14] 泛型函数
来源：http://dali.jiagoushi.top/Article/details/gt2fwclxppb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.kuanghao11.cn/Article/details/gt2gyvdeuym.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcekxqqa.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2qvxjwyhh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gt2cdpgilpi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.snrcjt.cn/Article/details/gt2ujxkecoj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oiiwkazk.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gt2mjpacqlm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sysykeji.top/Article/details/gt2dklakywd.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijkoioxt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnvkogdg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gt2kfqjuzxh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2zdewztnx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mafycigv.html

Java: // 无解构
来源：http://dali.snrcjt.cn/Article/details/gt2veogcfms.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwlvnvib.html

Ruby: a, b = pair
来源：http://dali.cucudq.cn/Article/details/gt2vfebkjym.html

C#:   var (a, b) = pair;
来源：http://dali.pycfn.com/Article/details/gt2pwkdpouy.html

[C16] 函数 / 方法重载
来源：http://dali.316326.xyz/Article/details/gt2zxeoyhux.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtaaovle.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gt2pltmtotq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gt2davzfudv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ydzc1.top/Article/details/gt2djwxxnuf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgfzy.top/Article/details/gt2tngcvwio.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gt2aexxzyai.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gt2eohivght.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gt2ottlifwx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2omszdgex.html

D. 数组 / 列表 / 集合
来源：http://dali.cdnleiting.top/Article/details/gt2ptywytdp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ieakddsn.html

[D01] 创建数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gt2vahxmtqg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gt2gwwxbfrr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuxming.cn/Article/details/gt2yavgwomd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ooovjbze.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.smart0.xyz/Article/details/gt2wzghmgkj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gt2hkmliijj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbgqblgp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gt2kqerulsh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gt2qijxjgvv.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gt2hesgpnbm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.kuanghao11.cn/Article/details/gt2zuhmzvob.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xziumwaf.html

JS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2tpvshxsu.html

TS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gt2oxqfmdnz.html

Java: list.add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kftchqwy.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2zaqhhrix.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gt2uipzkkrt.html

C#:   list.Add(4);
来源：http://dali.cashguo.top/Article/details/gt2xdndqnhz.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gt2zgqylfly.html

Py:   arr.insert(0, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2zmjzuxfk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gt2egxgiyqi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gt2qusswhno.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.c1oappe.top/Article/details/gt2ogznewwd.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2fzenokey.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gt2zgvcezvb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gt2faizbgfc.html

C#:   list.Insert(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2vvjtstse.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2beokoaoh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2siylqhmg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2zacfymzf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gt2tgebqvju.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gt2dafgwjaw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cqqwz.cn/Article/details/gt2vgqlzkxn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gt2ncosotiz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.svipenyu.cn/Article/details/gt2emdcpztr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jyoumei.cn/Article/details/gt2spqmyyqp.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gt2loyolsjq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gt2kyztlgnk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtiprith.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2zdntqqoe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tanke756.top/Article/details/gt2somctfgx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xinyue.icu/Article/details/gt2txogpcqx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2tzkhoejy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2bdkqxtvo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2wsdgxkxt.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2sepeilsx.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gt2ugnbkdqf.html

PHP:  count($arr);
来源：http://dali.xziqi.cn/Article/details/gt2wubfcrep.html

JS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlblszpm.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gt2jkdytepc.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gt2kqdmkaak.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwfnkkci.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gt2thyhqhwx.html

C#:   list.Count;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qodhffyg.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wehadcvh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangdashe.top/Article/details/gt2shgcgqrm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2tfosusxh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gt2tmgpfwcl.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2bnhtzcqs.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2olozgviu.html

Go:   arr[1:4]
来源：http://dali.ydzc1.top/Article/details/gt2qjztwsmh.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcprtxbx.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2ukglebkq.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gt2evizizfz.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gt2wrbypzme.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gt2ycphizoe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gt2nbicawrw.html

TS:   [...a, ...b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gitealxf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gt2npniobhg.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gt2xxfvbitq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2cgwnoazm.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lnlbyeuv.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gt2ynpgaefu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2uppdyazy.html

PHP:  sort($arr);
来源：http://dali.jianghu66.top/Article/details/gt2qdjimgpr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.smart0.xyz/Article/details/gt2ysautdlk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gt2zhbfhwsx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuanzx.com/Article/details/gt2zumvrlcy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gt2upiitgxd.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2qihmivld.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gt2ektpkits.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gt2xiecbzwn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgfzy.top/Article/details/gt2vwdnpepn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gt2bcvzmjcx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gt2omixssrs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gt2jaogqkkw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gt2hrczupqb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sweek.top/Article/details/gt2fgxqpjhh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gt2lgyaqimc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gt2asuixfpy.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gt2srihnlqd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daxiang520.top/Article/details/gt2gwpmedwk.html

PHP:  array_reverse($arr);
来源：http://dali.aizwys.cn/Article/details/gt2paxzceev.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gt2swyapjip.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2gntnlzjy.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gt2zllvdhrt.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gt2tjpraesq.html

Ruby: arr.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2nokvsclm.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gt2jbtxarmd.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gt2yyyssqtp.html

Py:   arr.index(x);  x in arr
来源：http://dali.tianlin.xyz/Article/details/gt2ejwwiqyp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gt2vrtrtxvg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gt2ktmtnidz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gt2jifncyjb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xziqi.cn/Article/details/gt2nimzgprc.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2wfcobwzp.html

Ruby: arr.index(x)
来源：http://dali.ivvv.top/Article/details/gt2oevysuzd.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gt2lttnbewv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gt2afxqroxr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gt2xbbrcelp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gt2iqeohuoz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2hkshhhof.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2ytolesyg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2myllmseq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gt2ywldwxzb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gt2ohkocnyv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2rwbmosso.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gt2yzfwwjhk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gt2fwohfvkn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2rlanufob.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2ppwfutxz.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gt2fksxhavv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gt2dyrnqrge.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gt2lmrfbcoc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2hyrejman.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ownkuykz.html

[D15] 去重
来源：http://dali.0kj1m.cn/Article/details/gt2cckdwdjo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gt2aggwudhg.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gt2jlpgofkz.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2dybifcjv.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gt2vhultouc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258.top/Article/details/gt2hhikqtpl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gt2mpnpairc.html

Ruby: arr.uniq
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrpivghl.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2eizvehys.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gt2poswhckp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2drdtbyrk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gt2ljsudjdp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2gqhikhpq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2hmzjgiuy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gt2thzpumzl.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzygqwea.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gt2cekjkvlo.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gt2pxhlccwq.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gt2oyyqadzh.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2tdnodgfe.html

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2cuxzmkyb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gt2guzbnwkr.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2eonmzvsw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gt2qojxbdwb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2nhhkvqrz.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gt2qpbrfadg.html

C#:   list.Max();  list.Min()
来源：http://dali.aizwys.cn/Article/details/gt2fanvuimd.html

[D18] 扁平化嵌套数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pawcmhbd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gt2ofoibgbi.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gt2vaahfait.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xutxfogn.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gt2aptwfakj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2qfcuucyy.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmoypyea.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gt2lxswljao.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2qielgtws.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gt2hkcsflfp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gt2qidmigyf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gt2kabolnvf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gt2ufwlzmrl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gt2coxcpihh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gt2wdjbtyja.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gt2aqklfeaw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gt2xwwkoogt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xziqi.cn/Article/details/gt2igsedcjb.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gt2blvzqepa.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2gqbwntmz.html

PHP:  array_count_values($arr);
来源：http://dali.fzhhl.top/Article/details/gt2zvmzvrmq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gt2dduxkxta.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnqfmjnu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gt2krnvkhda.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gt2vypdicmh.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gt2eajdqcdc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gt2wgbdwqtv.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcknsjyv.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gt2mvvnhrjm.html


<!-- 参考信息 -->