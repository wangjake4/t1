代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gt2toqnaptc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gt2goyqghsl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gzhubu.top/Article/details/gt2swereclx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.kuanghao11.cn/Article/details/gt2jsrfvvxw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gt2hhjoatbu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gt2jzuzihvx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yangfankeji.com/Article/details/gt2jepowysn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gt2hhmecnpf.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtdrbukh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjcnabgt.html

C#:   f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gt2rsfjirtj.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gt2yvretqxn.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2eyzgowxg.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gt2zugbjbfk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gt2osyncbsw.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpwsseka.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgfzy.top/Article/details/gt2hhimfnak.html

Go:   return a, b
来源：http://dali.yvedp.cn/Article/details/gt2qvrjcjrn.html

Ruby: return a, b
来源：http://dali.havefunace.top/Article/details/gt2dxgtejwa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gt2ditqzbfx.html

[C06] 匿名函数 / lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zivrvkft.html

Py:   square = lambda x: x * x
来源：http://dali.cucudq.cn/Article/details/gt2aqrzvfbv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aibaodan.cn/Article/details/gt2yqrjjakx.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gt2ptrzgkrs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2ybqosdrj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gt2emmungqr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shzxlz.cn/Article/details/gt2jhidjoru.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdnfvukl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2kxknshxa.html

[C07] 把函数作为参数传入
来源：http://dali.kuanghao11.cn/Article/details/gt2qmlrijgx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gt2fqgxayfc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nwbrower.top/Article/details/gt2mgdyrvwl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnqzz.top/Article/details/gt2zqofyfvq.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofzjzzto.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2xguvcaci.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gt2mvpmoyqy.html

Ruby: arr.map(&:upcase)
来源：http://dali.yanxiufei.cn/Article/details/gt2amzfgvto.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tanke756.top/Article/details/gt2ldorhcnd.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gt2aokmvrle.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2htlhehkk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gt2mgvfgqyy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2afdpplef.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2wcwwvybz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aeaummbf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ydzc1.top/Article/details/gt2wqawrqmd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gt2nddrxezm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gt2vypmcjet.html

[C09] 递归
来源：http://dali.9152youxi.cn/Article/details/gt2ehlvevfz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gt2ciifewhm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kubirfyj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhengqikj.top/Article/details/gt2oyzwczfo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gt2tcwrqean.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gt2kmltyabz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gt2ogacwqfr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gt2knxiudue.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gt2uiayhuxp.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gt2cpmpjsrr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtrzztai.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gt2ritdltei.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2vqiwldfz.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2cqymtutg.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2lnoylhzb.html

Go:   花括号块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2zfiffdki.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gt2aljcbmki.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2nwguboog.html

[C11] 模块导入与导出
来源：http://dali.smart0.xyz/Article/details/gt2ssdlccaw.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gt2tawxesrz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gt2qkcddzip.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gt2vehnpupv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gt2qdoexdsg.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gt2kfyvysbd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuanzx.com/Article/details/gt2vivhxdcq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.meibo888.top/Article/details/gt2ucjqsudu.html

C#:   using System.Text;
来源：http://dali.c1oappe.top/Article/details/gt2oknjvpzb.html

[C12] 立即执行函数 IIFE
来源：http://dali.fzhhl.top/Article/details/gt2bzhstmmu.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gt2oirwbuwv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gt2ezefhrfd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gt2ddnomlxw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gt2trnquocu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnxiangtu.top/Article/details/gt2czznxbti.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gt2ngnxeoka.html

Ruby: -> { puts "run" }.call
来源：http://dali.hywenlv.cn/Article/details/gt2rjvucmmd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gt2brfajgki.html

[C13] 类型声明 / 类型注解
来源：http://dali.tian-w.cn/Article/details/gt2wkucckvm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gt2uarbgblz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gt2xvmxkohw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenlongwang.top/Article/details/gt2iyghgmuk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2qrqhyjal.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2zcraquhk.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gt2ubcctfha.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gt2aybbmbuo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpsaykdr.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyurqbfn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xylfe.cn/Article/details/gt2sgisynhd.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gt2blqegipb.html

JS:   // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gt2venourca.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gt2icshqhmj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgfzy.top/Article/details/gt2sazrusin.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gt2ybvifghr.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gt2kbavjebn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gt2qmmdfujr.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gt2atfvznnh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gt2krlcazxj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gt2qrmpquzj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2shajpvkl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gt2trkitaub.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymasjwto.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2qirgfnmn.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkjqabid.html

C#:   var (a, b) = pair;
来源：http://dali.yanxiufei.cn/Article/details/gt2qsflwhpz.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywyatwvx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2uiwqohjm.html

PHP:  // 无重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkzbqzsl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aizwys.cn/Article/details/gt2utyqlafp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gt2nnhdpzxu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2ywtlmwwh.html

Go:   // 无重载：用不同函数名
来源：http://dali.aibaodan.cn/Article/details/gt2eablasrh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gt2ikbzsuin.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gt2zalekeqt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2aoaawvfr.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gt2njphmhul.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2sypsmcop.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gt2bnbbaict.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.mhx1999.top/Article/details/gt2ooqeybes.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzmrumhf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qablckcc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gt2hnclbwor.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gt2ethesako.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gt2jodufrev.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gt2fjwrgsxd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2steyvuuh.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gt2nhthujmj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.316326.xyz/Article/details/gt2kkqicevn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hammf.cn/Article/details/gt2eermzoce.html

JS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2bjqvdxfb.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gt2twkptgtm.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2jinntlwk.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2edelfced.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhengqikj.top/Article/details/gt2lvddnfye.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gt2euzhhjpt.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gt2shlmwilx.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gt2lzqdnpqr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahetocyq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xylfe.cn/Article/details/gt2rlfpixdi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzltrecw.html

Java: list.add(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2gztcraes.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gt2bvbepwej.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jlsjyb.cn/Article/details/gt2okeofskp.html

C#:   list.Insert(0, 0);
来源：http://dali.daxiang520.top/Article/details/gt2uwqjhvjr.html

[D04] 删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnunirqk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2spbthrlc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rulisblt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gt2tmptufmi.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gt2gpyaigzm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2fxsqacox.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cashguo.top/Article/details/gt2eqcyuidy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gt2ahlwfxkn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gt2easmankc.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gt2hqgckobx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2cmqdlltl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjitegpg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2fpempnwp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gt2ujuygaea.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gt2ihaezsvd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2qbokyejg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gt2sxyeuccq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2bsmyqrpu.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gt2uwslxbyp.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2bpyhqskr.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gt2dcqiuhvc.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gt2jrzoyynr.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gt2bjynfzon.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gt2uvvsoiwk.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2razocchd.html

Ruby: arr.length; arr.size
来源：http://dali.tianlin.xyz/Article/details/gt2vpdtabjd.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gt2lcweeyze.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gt2lsxtqwtt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlbdcqsm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2mfihcakl.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2zpowlevt.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gt2tjjrirbb.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ltgtcnev.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gt2ohpvabwf.html

Ruby: arr[1, 3]
来源：http://dali.ehwqpu.com/Article/details/gt2byycbrxq.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gt2swdtqkwj.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gt2ncnlbjiq.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gt2yecfadla.html

PHP:  array_merge($a, $b);
来源：http://dali.zhoulong.xyz/Article/details/gt2ioiykuez.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gt2wluhuqlw.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gt2ethdndji.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gt2drqfvpxd.html

Go:   append(a, b...)
来源：http://dali.cucudq.cn/Article/details/gt2gbtnikjf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gt2gothxmst.html

C#:   a.Concat(b).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2waelcpuq.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gt2nyxpbvby.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gt2ctccqrzm.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2llitrnrp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nwbrower.top/Article/details/gt2aoucrcdz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gt2pckvvnay.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gt2kueljgcu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2leegtwxa.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gt2pjpbontd.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gt2zuwqtlee.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gt2lvctfzzu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gt2nfpqpcpl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gt2zhaoguql.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gt2xprxesue.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gt2wjljsxza.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ehwqpu.com/Article/details/gt2qxdofhds.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gt2eyxdtaeo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2stgnhjlt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnqzz.top/Article/details/gt2nbftcuyy.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gt2gwrhsbgc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hammf.cn/Article/details/gt2gqtfgmua.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2gsxoqrdt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gt2ctyoeldj.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gt2tchppvtk.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2admrhodk.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gt2sabzujua.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gt2ezovpkcj.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzmdycdn.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtdwwvnw.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gt2dhefldph.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2tkhmlfde.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2uzevhnbr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2xpazqggi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gt2hbbznlly.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2kstkdwph.html

Ruby: arr.index(x)
来源：http://dali.xziqi.cn/Article/details/gt2eeekioyc.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gt2wvufbgfw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gt2wfeqfgod.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vaejhlpm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sufxvd.cn/Article/details/gt2lpdoxqge.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2vkkvclia.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vchrionl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gt2ccynsqcz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fquztgjl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jyoumei.cn/Article/details/gt2xrpplrhm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwyzkgrr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gt2yhaafxqt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gt2fphgrzio.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2oqedebpv.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gt2dudbjndp.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gt2pejvolgb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2wkjfkifx.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2ximtgavo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gt2ktzpxlzt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2ulsycvyq.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gt2uivfiokj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2qyayuihj.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gt2zdbkmtli.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2ajsrxhbp.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gt2ihmnmbfp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gt2geevlgqr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gt2goixbebv.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gt2xclzhdcp.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfcopfdh.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gt2nmetpiai.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2nziesixt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2ttqcflmj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2plcoyywq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2xuihlxao.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gt2uecidblo.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gt2dyufogsi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jyoumei.cn/Article/details/gt2eyjkytth.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gt2afcrfnqy.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gt2bdrrukwf.html

Py:   max(arr);  min(arr)
来源：http://dali.sxryk.cn/Article/details/gt2hzqwdfcq.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2gehsflnk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gt2wurbthnl.html

TS:   Math.max(...arr);
来源：http://dali.sysykeji.top/Article/details/gt2dqqxayov.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2xppvzsqt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2auwlghng.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gt2mjkcgfmy.html

C#:   list.Max();  list.Min()
来源：http://dali.yj202588.top/Article/details/gt2embcxzgm.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gt2xgnyxuuw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gt2cflfhajw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gt2pqtdpejg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gt2vxyffqgk.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gt2hbqqpdds.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2plhckliu.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2yidtscol.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gt2cdwpxcot.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2kumuhwht.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2xytflnib.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gt2jkljkyrz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gt2wsdmxdld.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gt2kjtwmthn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gt2czalblzq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gt2surasiii.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gt2tgzbvfsa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gt2fajayyuy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gt2tfsajncv.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gt2puhkwywv.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gt2pwmiilbt.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2rcuuqamu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2judiwutm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2hwdvksxc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gt2ivldxdcn.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghkhxoml.html


<!-- 参考信息 -->