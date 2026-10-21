代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigufen.top/Article/details/gtozjlfrnz.html

Go:   return a, b
来源：http://dali.hammf.cn/Article/details/gtznmgmvkk.html

Ruby: return a, b
来源：http://dali.zhengqikj.top/Article/details/gtgwmcpmcw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gtmimgflkk.html

[C06] 匿名函数 / lambda
来源：http://dali.bjfxy.top/Article/details/gtaerfpofg.html

Py:   square = lambda x: x * x
来源：http://dali.aibaodan.cn/Article/details/gtcrvwxuod.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgfzy.top/Article/details/gtslvwlbck.html

JS:   const square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtnvxxpegt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gtumszilgt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtimaashid.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gtxkcgioqy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigufen.top/Article/details/gtdcxfspvv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtofelvzth.html

[C07] 把函数作为参数传入
来源：http://dali.sxryk.cn/Article/details/gtlvakdtal.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnxiangtu.top/Article/details/gtyvtgxyue.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtwhaguhql.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gzhubu.top/Article/details/gtxagzbdyq.html

TS:   arr.map(String)
来源：http://dali.ehwqpu.com/Article/details/gtgowfikkc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yonumen.top/Article/details/gtmhcipanh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gotoacloud.top/Article/details/gtrdvtjnte.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhiwuduotai.top/Article/details/gtjfsiybif.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtrgnrvnga.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gtoowywgrz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.haohaochexian.top/Article/details/gtgaftmxyy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzohphvqr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtwpgnhoud.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtgfwehdto.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aibaodan.cn/Article/details/gtbhhazkcj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258.top/Article/details/gtkdjbqcce.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtrqpohmnu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtfycjmzia.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gthbkckwlr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtzevmzsqm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hammf.cn/Article/details/gtegrxgmmh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gtrhtlgpzy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtraobmlrf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gtpexieylq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.kuanghao11.cn/Article/details/gtxywxoepu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gtnrkhbmpx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gtnpezshpe.html

[C10] 变量作用域
来源：http://dali.c1oappe.top/Article/details/gtvqglejub.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gtuahfcalt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gthdzxjmrx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dashuyun.cn/Article/details/gtftvwhade.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gtwehxocki.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjcfezvv.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gtfcatkqjy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ybcxt.top/Article/details/gtyprkwxaz.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gtzbvguxdw.html

[C11] 模块导入与导出
来源：http://dali.jiagoushi.top/Article/details/gtnvrdcakr.html

Py:   from module import func
来源：http://dali.jinqigufen.top/Article/details/gttldcibod.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gotoacloud.top/Article/details/gtqblfdvod.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gtazkdspja.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gthljqkllv.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gtmbzqxsiu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cashguo.top/Article/details/gtydfhmhfb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.kuanghao11.cn/Article/details/gtuhidrpnx.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gtxagvyqxw.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gtdjxgibsy.html

Py:   (lambda: print("run"))()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddwrsoei.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtcsbrhiio.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtjibkhfif.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtlwhdrqat.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gtvebjxtfx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gtbaxckkna.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangdashe.top/Article/details/gtdofivgjg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gtahzjaupf.html

[C13] 类型声明 / 类型注解
来源：http://dali.hysaishi.cn/Article/details/gtshwriznw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xziqi.cn/Article/details/gtcedhcnjz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gttuyyjodn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.0kj1m.cn/Article/details/gtzrhscocw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtgkmvmigo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtbzyxrrsb.html

Go:   func add(a, b int) int
来源：http://dali.hammf.cn/Article/details/gtzdlkzteq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fengsongda.top/Article/details/gtehvywxtn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gtpczswcyl.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gtobqtgpwa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gtbetpykmp.html

PHP:  // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtlmlqcgvw.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gttcndepvg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gtnukricsr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtntvbypfv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gtakusfqym.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gthtnvndcn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gtihlgstxm.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gtqwrzafri.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gtxzrrhraa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gtyeeydfde.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtesggwymn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gtwcdjdxht.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gtsuluquqi.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gthkyweotz.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhfzmmcs.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtnwvkcoro.html

[C16] 函数 / 方法重载
来源：http://dali.feifeiyinyue.top/Article/details/gtyqttsdim.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnqzz.top/Article/details/gtdpzyawds.html

PHP:  // 无重载
来源：http://dali.redwolf501.top/Article/details/gtfdxonqqj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cashguo.top/Article/details/gtgxgfpfel.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gtygzesiax.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ehwqpu.com/Article/details/gtbvqujwak.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhoulong.xyz/Article/details/gtakruxews.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gtpocvqetn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gthzanfgor.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxudwetzz.html

D. 数组 / 列表 / 集合
来源：http://dali.yvedp.cn/Article/details/gtvfunsyne.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtspfoteoe.html

[D01] 创建数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gtttammvpc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbyilkwu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtfcacfjnm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ivvv.top/Article/details/gtfahpjyjp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtereadnlp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gtlzwzmukr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gtusdfyoir.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gteajotowz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtojhhhofy.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gtruurgmuy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gtmvkhpsck.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gtcxwfkump.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtwbwidcjl.html

TS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gthgyejdec.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gtacdhsbap.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtedzsmjio.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gtvvokiyrk.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gtytrzbmgu.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gtwcnhzbvm.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtcgsncgab.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqhuawin.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhongyouzk.top/Article/details/gtuijaxhac.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtnhqeweiq.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gtlzyqsgqv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.meibo888.top/Article/details/gtldjvclhw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gtoxxhavpg.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtflawwgcb.html

[D04] 删除元素
来源：http://dali.wangdashe.top/Article/details/gtafyncsvl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gtntgggeub.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtmfbomwwa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cdnleiting.top/Article/details/gtgbbkjldl.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gtgxdysbyo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fzhhl.top/Article/details/gtpyzmsqkt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtqamibvyd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gtithitjly.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pycfn.com/Article/details/gtwvgzxxkf.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gtwvmyurgn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtgyxkccvr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtuftcqbka.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtyzdygrhf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtmbdmwohi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gtwmfolayw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtjouagiqi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtgcrhtvni.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtgccxqsrb.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gtgvwbjuia.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtcdgnglnu.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtlcffnxjd.html

JS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtxzgdtdow.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gttlqqrped.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghqusygv.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gttxofpfyw.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gttwjkgvdr.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gtvtgkvuhm.html

[D07] 切片 / 取子数组
来源：http://dali.fengsongda.top/Article/details/gtbyvvmdiz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtgzktdvqi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gtkmyhdoju.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtkdjgxdbx.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtvlpovstz.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gtmzwtuwhq.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gthmzufbqz.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gtzsoafopp.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtdzdzvfaf.html

[D08] 合并两个数组
来源：http://dali.nanxinkj.top/Article/details/gtshpupcok.html

Py:   a + b;  a.extend(b)
来源：http://dali.sysykeji.top/Article/details/gtjanvmjiw.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtxpheqcrf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gtohtlzdju.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gtepvccoay.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtyweibrii.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujvgsmir.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gtuoklgdhb.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtbvtckqsi.html

[D09] 排序（升序）
来源：http://dali.yueranfly.top/Article/details/gtnkvpoitv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gtpzjkdtgz.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjoszokg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gtmfewsrpa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbzstzwt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gtwnlgbyrr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtnritmmoa.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtfplvikvk.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gtsxogtxuw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhiwuduotai.top/Article/details/gtptfdldcg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtjkeqbiwv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtmudwylaa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuobvvawz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gttoxrrnyt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gtqfltjnrc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gtqsmenuju.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqajtujbz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gtjifayvko.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gtfzabsvkr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ppjwa.cn/Article/details/gtdxejrhcl.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gtzisthawg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gtjxrriaeh.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtwqtnodhf.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gtyrkcpuvn.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gtnjmnyodl.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gtajokljyd.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gtpthfomjd.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtxspjnjfj.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gtbdlarxds.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtohecwwxx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtueyuqagk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtobbtwnqp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gtocghbioe.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtdpxlxhzf.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gtivvrgazj.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gtshzdryzv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gtdrurixbk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gtvwxangxr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gtqlfqfjpt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtvrcztohr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfxgrpfk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnqzz.top/Article/details/gtzqfupdgv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gthddubgwu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gtwnhuabrp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gttcxnypgv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sxryk.cn/Article/details/gtepqgkfzd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gtqqyaidnv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtpkvfztnc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtlkplazra.html

TS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtbiolpndx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.0kj1m.cn/Article/details/gtjriszvxo.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtufazxjbq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtqcmnhrfl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gtlmmhgpgr.html

[D15] 去重
来源：http://dali.yangfankeji.com/Article/details/gtepjlcgws.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtnccfyhdb.html

PHP:  array_unique($arr);
来源：http://dali.zycfv.cn/Article/details/gtxpjocwdm.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtkikiznzc.html

TS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtvyexxlog.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gtxbuwxgll.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gtbasdacbx.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gtwadspthc.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gtmchtkqtr.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gtejyfwakm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtjiajjtro.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hammf.cn/Article/details/gtycmvmfnp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtazdhtyyd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gthxjwpdzd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sxryk.cn/Article/details/gtzxgpaqcc.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gtqjlbyasc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtuqkcpgxw.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gthbgnpipf.html

[D17] 最大值与最小值
来源：http://dali.birdmap.top/Article/details/gtjxddrxjm.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtettjkyth.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gtafazgexn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gtcidhxaqh.html

TS:   Math.max(...arr);
来源：http://dali.jqgfzy.top/Article/details/gtviydryvp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gtyomzsfkg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gteijuoeuy.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gtofaknecf.html

C#:   list.Max();  list.Min()
来源：http://dali.cdnleiting.top/Article/details/gtgynnfdsm.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gtnsvzymte.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gtgrikeend.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gtbgcwcgfy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtkxxbmrln.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gtcikyotvg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtvzgclnle.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtxfushlyi.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtylrtilna.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtnovmvexb.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gtyojfhdfw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gtfifbdpmf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtvbaoaemz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangtech.top/Article/details/gthsckgutf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtvvjwobse.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtrvpfnlog.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxuanxn.top/Article/details/gteycequbc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigfzy.top/Article/details/gtbqkbdyyp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gtvxsjqzhm.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gtualmjidy.html

Py:   Counter(arr)
来源：http://dali.havefunace.top/Article/details/gtxqqucumg.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gtqopjbdbs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkoqhjrw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtalqibqre.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gtzbuiqyyv.html

Go:   // 手写 map[T]int
来源：http://dali.shangyingyoupin.top/Article/details/gtldnhssne.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gtyakuvvrb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gthqhvatcc.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gtunhymkby.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gtuwglfajd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtvuyoualb.html

JS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtnvofqnmf.html

TS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtmkvzsqge.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtcwqscikd.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepvvapyb.html

Ruby: arr.include?(x)
来源：http://dali.tian-w.cn/Article/details/gtjqrshxga.html

C#:   list.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtvpjuitmj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aizwys.cn/Article/details/gtqzxlemcd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gtvtwjyahh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtwifkfwrq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gtfusfhvdt.html

TS:   [...arr];
来源：http://dali.tianlin.xyz/Article/details/gtlaorjtdj.html


<!-- 参考信息 -->