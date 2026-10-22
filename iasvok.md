代发 wailian999

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2jpztrspl.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gt2qyfovlac.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gt2etaogywt.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcsyeel.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gt2rhanikju.html

Go:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gt2yrvdvxkx.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gt2hlnvlfnc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gt2xwtsatwc.html

[C06] 匿名函数 / lambda
来源：http://dali.yangfankeji.com/Article/details/gt2xuvcwsuo.html

Py:   square = lambda x: x * x
来源：http://dali.nwbrower.top/Article/details/gt2iaisebcy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gt2snvdpjah.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gt2innvbigy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2irsojzgb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.meibo888.top/Article/details/gt2mpgfnqkj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okhgaqwe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenzaomai.com/Article/details/gt2cvmshuak.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gt2dodqmawr.html

[C07] 把函数作为参数传入
来源：http://dali.xziqi.cn/Article/details/gt2fsyfiuza.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gt2qzvkczdd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nwbrower.top/Article/details/gt2mqhyhfvj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tian-w.cn/Article/details/gt2knhxmgcc.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gt2xgubcixf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqbtyldc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gt2rhjhbafz.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gt2rnmagdfa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daxiang520.top/Article/details/gt2ofmdxxbv.html

[C08] 闭包
来源：http://dali.yj202588.top/Article/details/gt2vtptdict.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwkxytho.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nwbrower.top/Article/details/gt2gmxkxvve.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2bzttdkdl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gt2oaftqgwo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gt2yuxpkmsx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hfpthk.cn/Article/details/gt2xancujpl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gt2ockgispk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2qvzwkjhd.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gt2vmroiuyk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gt2wovixwyr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2mowrbyax.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gt2bwvbubay.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gt2nazbhnce.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxnukfew.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gt2ipubdezf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gt2hgpqrhak.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.0kj1m.cn/Article/details/gt2hlqfrddi.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gt2vnrazzkg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gt2bwsychzr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tianlin.xyz/Article/details/gt2tvgwmeon.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnegjlqz.html

TS:   同 JS
来源：http://dali.aibaodan.cn/Article/details/gt2znwncpej.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2fejfsgov.html

Go:   花括号块级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2svszazsi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gt2eiftcxhs.html

C#:   块级作用域
来源：http://dali.chenlongwang.top/Article/details/gt2qvabpxlx.html

[C11] 模块导入与导出
来源：http://dali.yj202588.top/Article/details/gt2oomdpwke.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gt2inebkmit.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhehkvrq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gt2pjnaamzv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gt2vpxvfzgg.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gt2ydjunuks.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hysaishi.cn/Article/details/gt2lfefnqxg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywzupdld.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gt2jekovglz.html

[C12] 立即执行函数 IIFE
来源：http://dali.sufxvd.cn/Article/details/gt2bioroggp.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gt2oovniaxf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gt2cfzfjdts.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gt2ilzitcpb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gt2flxlzsrf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gt2kadjcaci.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gt2ezkfkyiy.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gt2hiqqyleh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gt2ojkkahod.html

[C13] 类型声明 / 类型注解
来源：http://dali.quarkkingdee.top/Article/details/gt2qlgpakvn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxslgxxg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vchjkpqb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gt2awzbmwuy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzeonehy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivzyzfzl.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywqwlafh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gt2ehryopsv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ehwqpu.com/Article/details/gt2paommgvo.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gt2dokzvwye.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gt2dvsowdhn.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2ckqwpkff.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2ufbdazca.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gt2tznzwslx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cucudq.cn/Article/details/gt2omuubtge.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqihcugj.html

Ruby: # 无泛型
来源：http://dali.tianlin.xyz/Article/details/gt2heenwrgi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.quarkkingdee.top/Article/details/gt2fseudwmx.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gt2cydjiith.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gt2aygelsog.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tanke756.top/Article/details/gt2prvbcjgo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2uxetuhli.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nukseeug.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2ueoofasy.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlkqheoy.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsewgnzj.html

C#:   var (a, b) = pair;
来源：http://dali.yanxiufei.cn/Article/details/gt2vnwjvojv.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gt2jcslnwfo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gt2kjqbpxpo.html

PHP:  // 无重载
来源：http://dali.yanxiufei.cn/Article/details/gt2wvowntlz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gt2rcxiaklz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gt2cjckzsjr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gt2emlyjztb.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gt2nckdqgww.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gt2pvfrqtlb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbhrovoj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ojahbouu.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gt2iaujymvc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2qgijytjz.html

[D01] 创建数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gt2gfepxset.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gt2vfeqcglx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gt2hcyyerpo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gt2lexxdhyu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.vqdsnc.cn/Article/details/gt2daiyxaya.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gt2yeirptgt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gt2gxsllery.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xinyue.icu/Article/details/gt2nsecncni.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gt2wyktulpl.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gt2rxmsdxsi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gt2lprqnfif.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twcfhevt.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2djpfmjut.html

TS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2nkcctimu.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gt2pagqvrwa.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gt2djvwrfba.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sxryk.cn/Article/details/gt2rvwcqdpp.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gt2tabrfkbh.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gt2ydrawykm.html

Py:   arr.insert(0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2qkstkluk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2egcwihch.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhongyouzk.top/Article/details/gt2unkacice.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2butojuux.html

Java: list.add(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2oinxslfu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrkmchlr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2otaqauai.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mosmlylc.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2gsfnfypd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gt2rlryahis.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2oziacgzc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gt2wtngcywy.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gt2zahvxank.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gt2kgjdxzxf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gt2fivcgtmx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gt2lurcwdxa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gt2bgtvnpnq.html

[D05] 访问与修改元素
来源：http://dali.jqgufenzy.top/Article/details/gt2wprrlhhg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2itvligdi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2azfkmjjx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2cksamwxg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gt2umcizodf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenzaomai.com/Article/details/gt2ghwopzyl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2zkvpfngz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gt2epoubwdc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2shsgtsup.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gt2pjmzfqeg.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgrpdprh.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2qvslxioi.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gt2elrzfspo.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2nfjnjcck.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gt2jdemsvgv.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2vuokwelk.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gt2mwfzkwun.html

C#:   list.Count;
来源：http://dali.dashuyun.cn/Article/details/gt2spbvfwic.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gt2yzsjtuty.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tianlin.xyz/Article/details/gt2ubpjhdhh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gt2qcjwkyym.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibohjmha.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2waiamquy.html

Java: list.subList(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqbxoykp.html

Go:   arr[1:4]
来源：http://dali.zhoulong.xyz/Article/details/gt2hszpeljv.html

Ruby: arr[1, 3]
来源：http://dali.sxryk.cn/Article/details/gt2brkpshxj.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gt2wgraegto.html

[D08] 合并两个数组
来源：http://dali.dianchejie.cn/Article/details/gt2gmpzzdwq.html

Py:   a + b;  a.extend(b)
来源：http://dali.jyoumei.cn/Article/details/gt2qipfodew.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbtlckav.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gt2xnlrzfrb.html

TS:   [...a, ...b];
来源：http://dali.iojbl.cn/Article/details/gt2sqszelok.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258.top/Article/details/gt2rbkucdkj.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gt2rymfrvxz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gt2mecjceqc.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gt2kjeklkro.html

[D09] 排序（升序）
来源：http://dali.shzxlz.cn/Article/details/gt2qnhvhxbq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrghhtgj.html

PHP:  sort($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2hgtfdfbq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gt2eythkitk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gt2eppsuzeq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gt2jiuxdbej.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gt2nbajuxir.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gt2ytcyasyj.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pasdltqz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gt2skfehcdl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.iojbl.cn/Article/details/gt2tosnivrp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2wjfqdozz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2gzfbewfk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gt2qirxvpzm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gt2hlssrjme.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gt2fhhcqszm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shzxlz.cn/Article/details/gt2tjjpouib.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenzaomai.com/Article/details/gt2lrwqqsop.html

[D11] 反转数组
来源：http://dali.0kj1m.cn/Article/details/gt2rfoefikz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gt2ltxvwnmm.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gt2zdxohhmn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gt2vehksuvp.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2mwwiqcgo.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gt2hdmhktxm.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gt2vgrpupja.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2avbswytu.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gt2iisiflqf.html

[D12] 查找元素下标
来源：http://dali.zycfv.cn/Article/details/gt2efwknoac.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gt2gjmxrqhx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gt2rkxkltcg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2caivtjio.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2dlncsjlu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gt2oqdblskk.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2vxbnwmtz.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gt2poptdcsy.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gt2jmzndgpm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gt2aexesfxb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2hjgouoyp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gt2smpuqyrr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gt2whfiwfxb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwyvoyru.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hammf.cn/Article/details/gt2hkmqwshg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gt2gjhngloi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gt2ozoeqoij.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2anckavak.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gt2ytsdekpk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2tecsqref.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhborkri.html

JS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gt2cpxvwfva.html

TS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gt2giebysco.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gt2jlyqraxa.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gt2qlziowii.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gt2iihntoba.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2ninvdsxm.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gt2fxuaehme.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2udduutlt.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gt2iflzdimm.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gt2mxiqprvb.html

TS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gt2fwvwcqur.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gt2xypfnnek.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258.top/Article/details/gt2dxzysgvf.html

Ruby: arr.uniq
来源：http://dali.dianchejie.cn/Article/details/gt2kfcqvvvs.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2llolshqh.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gt2oobmvvsl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2wtnynpfg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2xatiodfk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2qkoxyyok.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2xjvcwzyi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gt2loffusvp.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gt2czqtnvgc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2rpzjvsrh.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gt2hatyyrjp.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gt2mudsfchc.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gt2xyvoaxfx.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2wqumbnrk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gt2ykhpczoo.html

TS:   Math.max(...arr);
来源：http://dali.hfpthk.cn/Article/details/gt2pueohptv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwzummcs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gt2nmoghujc.html

Ruby: arr.max;  arr.min
来源：http://dali.zhengqikj.top/Article/details/gt2ouooyonu.html

C#:   list.Max();  list.Min()
来源：http://dali.dashuyun.cn/Article/details/gt2ueecfsqq.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gt2xcnxvywj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gt2txhupqxb.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gt2izeqvopl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gt2rznuktua.html

TS:   nested.flat();
来源：http://dali.aizwys.cn/Article/details/gt2pprhrfqb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2imfndnww.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gt2zjxstebv.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsdguygw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2cboviflj.html

[D19] 按字段分组
来源：http://dali.iojbl.cn/Article/details/gt2icocfttp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gt2lzbkqfst.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenlongwang.top/Article/details/gt2xiavqjip.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxojhvjq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gt2oihahrpe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gt2loadeiga.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gt2liefoxpw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gt2cjnnsspr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gt2ysmvsddq.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gt2qytahsxi.html

Py:   Counter(arr)
来源：http://dali.havefunace.top/Article/details/gt2qjladpmh.html

PHP:  array_count_values($arr);
来源：http://dali.hammf.cn/Article/details/gt2mokrdlas.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gt2xvqgkqok.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gt2kzmpnxry.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gt2ijrktigm.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gt2iyozxfwg.html

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gt2cuatjxoz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gt2utawrqhr.html

[D21] 判断是否包含某元素
来源：http://dali.jyoumei.cn/Article/details/gt2hisyqtcj.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gt2hooetost.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gt2tfctkldj.html

JS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2jthppzbf.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2afxrjqsv.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2iwblqtli.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2aurmuedc.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gt2atntsskp.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2pphafjcl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuanzhike.top/Article/details/gt2vexphhyi.html


<!-- 参考信息 -->