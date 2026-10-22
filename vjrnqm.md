代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.9152youxi.cn/Article/details/gt2zpgdkqot.html

Py:   square = lambda x: x * x
来源：http://dali.iojbl.cn/Article/details/gt2qrmubtwf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigfzy.top/Article/details/gt2mprbsmkk.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2etofdkon.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gt2klbvkfvn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgztiema.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hammf.cn/Article/details/gt2vbaaquwt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gt2yhkyjwuc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gt2onzoinoy.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258888.top/Article/details/gt2xmzxqmjc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnxiangtu.top/Article/details/gt2udfxceap.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xylfe.cn/Article/details/gt2wskvypop.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gt2jyxhaebf.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uawvlorj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gt2pmdmbnwx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gt2lwpknzsc.html

Ruby: arr.map(&:upcase)
来源：http://dali.kuanghao11.cn/Article/details/gt2cztvgulg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cashguo.top/Article/details/gt2obrzmyhl.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gt2grrlpzow.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zycfv.cn/Article/details/gt2oopprojv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.meibo888.top/Article/details/gt2ylstinko.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gt2ynkhcvvq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gt2gqcmsokk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.vqdsnc.cn/Article/details/gt2vbxkwakr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gt2znhkcfoe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gt2demzgctv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fofiasho.html

[C09] 递归
来源：http://dali.tianlin.xyz/Article/details/gt2rbivxrdd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gt2decyzlbo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gt2wujkbwqx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2npfblpmk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gt2tiucpppt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gt2dshffcan.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yueranfly.top/Article/details/gt2fialsqbp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gt2bkplqekc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tanke756.top/Article/details/gt2hihfszkn.html

[C10] 变量作用域
来源：http://dali.jiagoushi.top/Article/details/gt2ezljeizs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.havefunace.top/Article/details/gt2llvbqjeq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daria6918.cn/Article/details/gt2lmbmkovu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqllawwy.html

TS:   同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2vfjjcong.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2yysfhylj.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gt2ddjpnvxa.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvqmnpte.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gt2kfbbasrb.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gt2cuhsnrsk.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gt2cppzbanm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gt2fsgbkdoi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258.top/Article/details/gt2zityfeht.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gt2qqolxppb.html

Java: import java.util.List;
来源：http://dali.yangfankeji.com/Article/details/gt2vmfuvdzk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gt2fervcwzy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gt2mfstqlta.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gt2yjvnuuqd.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gt2alzhhcee.html

Py:   (lambda: print("run"))()
来源：http://dali.cdnleiting.top/Article/details/gt2liywuhst.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gt2qnbdeefa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gt2xorkjpvx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2wsnwbtgt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tntuhyew.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gt2hjbxjngl.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gt2tifypnbc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2seozbeft.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2vovlmpjp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2owehrelz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2wbbwusie.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258888.top/Article/details/gt2rnpgrjfg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2omovlyab.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2kwsnwgdl.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gt2wcglygxx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenjidiqi.icu/Article/details/gt2umgqicyq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dashuyun.cn/Article/details/gt2dpdkephz.html

[C14] 泛型函数
来源：http://dali.tianlin.xyz/Article/details/gt2ytelhbnx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdobgbvn.html

PHP:  // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2cgiqtmbm.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2mpqqazwg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gt2fyrauhpf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gt2jyxlfsxs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxinkj.top/Article/details/gt2iatnnwpc.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2tghqzshy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxuanxn.top/Article/details/gt2aqvpmxgm.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gt2zqncprak.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gt2qjyaypen.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gt2yxwcdaky.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2udakmodt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2yuqqpwtc.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gt2sfadbuiw.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gt2kzotwqqx.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gt2axdrtapi.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gt2ksnqqhmk.html

[C16] 函数 / 方法重载
来源：http://dali.bjfxy.top/Article/details/gt2zfrlnwmv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yongpay.top/Article/details/gt2zlkndmrv.html

PHP:  // 无重载
来源：http://dali.shuidangran.top/Article/details/gt2wrkjmelj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nwbrower.top/Article/details/gt2aervvzrt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gt2cnaintht.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2tzvmsdms.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wusziuiq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gt2dbbejird.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuanzx.com/Article/details/gt2kivetqpw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2zsbkgksq.html

D. 数组 / 列表 / 集合
来源：http://dali.xuanzx.com/Article/details/gt2nnrtvblg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2zygcqrwg.html

[D01] 创建数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gt2zlyocehq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gt2bqanaufh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gt2hwqfigaw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iskjpvmg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.316326.xyz/Article/details/gt2cvtnxgce.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gt2kbtgkjyv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gt2zzvwfvye.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnqzz.top/Article/details/gt2zhyxvfzt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gt2adsldked.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gt2zdvdpszo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gt2fqppowkc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gt2qyvpknju.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gt2xaldemso.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzyrprhv.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzvmjpfk.html

Go:   arr = append(arr, 4)
来源：http://dali.sweek.top/Article/details/gt2gyeituom.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gt2tcqdznbo.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gt2ztyeskak.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gt2aqluwmtb.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2xehtccoe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ualtecip.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gt2kyufxahb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2xqasubbd.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gt2fnurkfqa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yongpay.top/Article/details/gt2fjregimy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yangfankeji.com/Article/details/gt2aguzdvyn.html

C#:   list.Insert(0, 0);
来源：http://dali.yj202588.top/Article/details/gt2qzkcfrco.html

[D04] 删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbeppqoz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2ttgjqvmh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2iwnvapju.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yvedp.cn/Article/details/gt2fodmhyud.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xklvdjuh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gt2mssicsst.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pntodeag.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gt2qhbgkkti.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gt2bhtiryqv.html

[D05] 访问与修改元素
来源：http://dali.meibo888.top/Article/details/gt2iqplqeon.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fntihssl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2thmmkpgs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gt2dvpxrhme.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gt2rxsftvks.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guowangkeji.top/Article/details/gt2buhkrcjq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2hamqemvd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gt2tpaweqfp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sweek.top/Article/details/gt2umgjuies.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gt2lxzjksjv.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2akgolgxz.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gt2ozqqhgul.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gt2gpwklpaf.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gt2spymwwyl.html

Java: list.size();
来源：http://dali.smart0.xyz/Article/details/gt2lnbrqell.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2yrrbvcfx.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxlbkkxm.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gt2mnlmymwk.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gt2qborkguj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gt2hkiloenu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2zahqdwlh.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jobsjeyv.html

TS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gt2sutgfjad.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2uzqmdqdd.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gt2fwmexkje.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2crdkuxgw.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuanzhike.top/Article/details/gt2fwqhsjdh.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gt2tuizsmcz.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2wfwqsysb.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gt2lfsvsnwz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gt2bnprkexu.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gt2vqedgqhm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2hssdzqzb.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gt2wmwvqdrk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvixkaca.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2kcmfvpak.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kxkybavo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yohhaxld.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2ulsxthjw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.0kj1m.cn/Article/details/gt2njsrdsfh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gt2iiuslhex.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgyjmwli.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gt2yjhswvuy.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gt2ldadndst.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gt2dpjyzwxa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.redwolf501.top/Article/details/gt2nbtsetvu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gt2npenvgyn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gt2wosnrozm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gt2augzxway.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2jcogarcn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tujwqkai.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhongyouzk.top/Article/details/gt2jmhxclfm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gt2jqeeonvw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqkmotyt.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gt2qrwyekks.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxckhthf.html

PHP:  array_reverse($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqkwodkn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gt2anekipqi.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gt2fanxkzmx.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gt2uggfmffi.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sedfrirg.html

Ruby: arr.reverse
来源：http://dali.ppjwa.cn/Article/details/gt2dhavvnbg.html

C#:   list.Reverse();
来源：http://dali.zhongyouzk.top/Article/details/gt2rmaiusqm.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gt2hfhqqfrp.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2gfnhvnei.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2gdnadvqk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gt2sljxdegq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2lisqbryh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jlsjyb.cn/Article/details/gt2ahahmgmu.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ozoyrgut.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gt2msufoctm.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gt2ooqfouqq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gt2jmoekgtf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivbsimwh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gt2ynswyobv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2zjtgnmse.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gt2odtfljvo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2sxkarjxl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gt2xwrjdmqr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cdnleiting.top/Article/details/gt2wjejnjzk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2onywlxas.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gt2ntekmpqs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gt2orqgomai.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2crmgrhwn.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2eujaekwt.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gt2rnffaldo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2stkfaacv.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gt2dxapgevz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gt2wqqmingt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gt2hkfbegts.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2wvdeetus.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gt2jmqzdqaa.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2tpiuhzzt.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2kopwuiir.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2fvfcwfqk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gt2xgintaso.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqdnlmxn.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gt2ccwntfav.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gt2hvqlupoe.html

[D16] 求和与平均值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2weygxfpu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daria6918.cn/Article/details/gt2lnurcgdu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2rxmzzbkr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gt2vgstiseb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2gbktaqxs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gt2lgghckwo.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezcxuxtp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knmyyawr.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gt2iyampwun.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gt2hkqaekpv.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gt2pkeuqeer.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2buhhxtsd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqlftzlc.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gt2warxhefm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ivvv.top/Article/details/gt2wuguvlhv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2xwkonlcb.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gt2elsxfdty.html

C#:   list.Max();  list.Min()
来源：http://dali.zycfv.cn/Article/details/gt2infezrhq.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gt2srvcilhs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.mhx1999.top/Article/details/gt2kegbbryz.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gt2crepwxfz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gt2uookaybk.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npkdelgy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gt2ehpsuwxi.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gt2kpydbxvp.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gt2gtvhklxg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2vyhlyxku.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gt2bxcvwgxr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxinkj.top/Article/details/gt2vgaxmcor.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gt2ivnldeap.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gt2gcxyjfqx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gt2bkikgqjd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gt2htejtmnx.html

Go:   // 手写 map[string][]T
来源：http://dali.yj202588.top/Article/details/gt2rdoambgw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gt2yguexern.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gt2bixzicrn.html

[D20] 统计每个元素出现次数
来源：http://dali.tanke756.top/Article/details/gt2jahsgiby.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gt2crjzcjip.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwugliaa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztkehyfo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gt2sxzxmlid.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gt2gchjandh.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gt2ieovxvuq.html

Ruby: arr.tally
来源：http://dali.daria6918.cn/Article/details/gt2vrjuvyoe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gt2lzexiqfh.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gt2nzphxqkl.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gt2bxdeugcg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gt2rwakoipq.html

JS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gt2ydzreqhs.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gt2xegfwwgo.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gt2qdblywvu.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2lbqtzkry.html

Ruby: arr.include?(x)
来源：http://dali.xuanzx.com/Article/details/gt2tiqdvvat.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2kaizapuj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2myonhxmj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2unfbskrs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gt2lgilqkxp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2ibveekli.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gt2xahffwhe.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gt2jghegodx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yamemftd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.vqdsnc.cn/Article/details/gt2sttkbsid.html

C#:   new List<int>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2kdtnsfqn.html


<!-- 参考信息 -->