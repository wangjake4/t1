代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gt2dlmahuar.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gt2ynitmuef.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dianchejie.cn/Article/details/gt2hfyehkol.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.quarkkingdee.top/Article/details/gt2ioqrhnpq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqrgeeok.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2bwfwiwhp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gt2awnxgllm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gt2cmlgsywc.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gt2tqfjstjz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gt2outhkpmg.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gt2opkdshio.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gt2mxdlqavt.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gt2ohyrrrwd.html

PHP:  return [$a, $b];
来源：http://dali.sysykeji.top/Article/details/gt2szamhism.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrhkabgu.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvbikibr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gt2suzmgmsa.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2imicnrey.html

Ruby: return a, b
来源：http://dali.yj20258888.top/Article/details/gt2ytqgnhre.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gt2irtrmovk.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gt2ussgkrot.html

Py:   square = lambda x: x * x
来源：http://dali.aibaodan.cn/Article/details/gt2mwucfsra.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daxiang520.top/Article/details/gt2gnvkfdce.html

JS:   const square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gt2xftevfnd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2tryvwxxb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gt2sxxpotcw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gt2jevytymw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gt2ngbojrwe.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gt2umsvxmxt.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2lhowimdx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yangfankeji.com/Article/details/gt2qmqwubwn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgndhfir.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhengqikj.top/Article/details/gt2gwpnsanl.html

TS:   arr.map(String)
来源：http://dali.xylfe.cn/Article/details/gt2tbelvoff.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2gdvtrqnw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gt2kjixaelp.html

Ruby: arr.map(&:upcase)
来源：http://dali.shuidangran.top/Article/details/gt2pcgtvhhp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gt2jqqnyegp.html

[C08] 闭包
来源：http://dali.hnxiangtu.top/Article/details/gt2xtsptuox.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sweek.top/Article/details/gt2pbbthphb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangdashe.top/Article/details/gt2gkhugauu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gt2cqtyomxu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gt2iftklhpw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gt2woolfxgq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gt2upbfvqcw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gt2cqstyvea.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zbhslzpc.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gt2cyhbnsht.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gt2qbubhzdc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fzhhl.top/Article/details/gt2dvlkfnvd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gt2ojwmkstl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gt2qbrigiob.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxqakkqi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xziqi.cn/Article/details/gt2jmipznkd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gt2sjvjvnzp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shuidangran.top/Article/details/gt2tlbatuya.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gt2rhogzxhh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gt2ldlxzivw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dashuyun.cn/Article/details/gt2jbqmweuf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2doajpbgb.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2rgkhagcc.html

Java: 方法内为块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2wajegkyz.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gt2pnftwtzt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jiagoushi.top/Article/details/gt2oadcjlrn.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2gomksyke.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gt2jpkoeytl.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gt2afzrpecw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gt2jdqaokvn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gt2sigftguz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gt2behdloff.html

Java: import java.util.List;
来源：http://dali.yonumen.top/Article/details/gt2phoacoek.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ydzc1.top/Article/details/gt2jsggtypd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gt2ksmvyfnz.html

C#:   using System.Text;
来源：http://dali.havefunace.top/Article/details/gt2gcmafggc.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhengqikj.top/Article/details/gt2hdvrjojo.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mcpnxvvt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gt2smeupoao.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2iofqklcw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gt2iamgtyaj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gt2gyqyernb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gt2qobuksrd.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gt2hmuybcsw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2skpsozza.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnxiangtu.top/Article/details/gt2kghefpav.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gt2ofwrqope.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vqkpnksp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cashguo.top/Article/details/gt2nayiuptw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2maqxgmyb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2tlrbkgzt.html

Go:   func add(a, b int) int
来源：http://dali.vqdsnc.cn/Article/details/gt2uangpkus.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gt2uuhiduaz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gt2qjchixbb.html

[C14] 泛型函数
来源：http://dali.cdnleiting.top/Article/details/gt2icylvoln.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gt2bneqskvl.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2qgahollg.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2igimnkbu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gt2plisiboe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ybcxt.top/Article/details/gt2vmwlqscy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gt2hanoskov.html

Ruby: # 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2lqoingai.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gt2ivgojuoq.html

[C15] 解构 / 展开参数
来源：http://dali.cucudq.cn/Article/details/gt2ikfgkphl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shzxlz.cn/Article/details/gt2hviwmjdh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hammf.cn/Article/details/gt2acroufee.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2bgxzcbbm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2rflimfvw.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gt2jivuquwt.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gt2pssvwyfi.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gt2azksjfjg.html

C#:   var (a, b) = pair;
来源：http://dali.hfpthk.cn/Article/details/gt2sownwnvq.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gt2nqcfftnp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2rxcwtpiv.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gt2lggmpoop.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gt2fmznwape.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gt2wdjtxaiv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gt2ncgkwagu.html

Go:   // 无重载：用不同函数名
来源：http://dali.iojbl.cn/Article/details/gt2wookutys.html

Ruby: # 无重载：靠动态参数
来源：http://dali.bjfxy.top/Article/details/gt2qfgpjdvl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gt2pvhkgyhf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2imqgztrk.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gt2hykeslgw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbevypaj.html

[D01] 创建数组 / 列表
来源：http://dali.sxryk.cn/Article/details/gt2kbaoltha.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdqpuayr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.mhx1999.top/Article/details/gt2vvdsclfw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2tiklztxw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jlsjyb.cn/Article/details/gt2zaikjvdf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eoxtohcf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ydzc1.top/Article/details/gt2rubjgmrv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gt2wsiozkyr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxpddwxz.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gt2yekmmluz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gt2qwjwacyr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gt2qejlqmtj.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gt2pldnpfvj.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnztwgcw.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gt2zfmdmxie.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2frqhuhey.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gt2qvjcwyur.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gt2iuzcxogm.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gt2gbphfnkh.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jlxocmah.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gt2zsqpkhto.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gt2xryycgus.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2kwpytyrp.html

Java: list.add(0, 0);
来源：http://dali.yvedp.cn/Article/details/gt2ynbspzxj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gt2asqzbspy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gt2tntgawpy.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2iiwpumoc.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gt2ukbfjaeb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tofjfjen.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daxiang520.top/Article/details/gt2jqacfruw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gt2mggxdsic.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gt2rftajfli.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxrtyeql.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gt2fpdkarho.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ivvv.top/Article/details/gt2xdmruolg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxuanxn.top/Article/details/gt2voqtmfnw.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gt2jdqebiuo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2vbfvhalb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gt2xiqccldq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2pbojmmuw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gt2koziixxe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gt2jucgscex.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gt2zwjcdtyn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gt2mqdgadmq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjmbubjb.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gt2sznexugd.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gt2bxchpsbf.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gt2hevpdybq.html

JS:   arr.length
来源：http://dali.sweek.top/Article/details/gt2gyswchjv.html

TS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gt2unhwgvec.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gt2jpmzienn.html

Go:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2euwmnkgk.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnknaqrr.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gt2forfrmfr.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2iypwrpmt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gt2yhwdrvfu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbhjcsdj.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2rnfoatqt.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2waghfhwg.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2qxehltez.html

Go:   arr[1:4]
来源：http://dali.cheryme.top/Article/details/gt2cexbskff.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gt2ejkcceib.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gt2syydwxmg.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gt2zfzxsrpx.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gt2xnshqmep.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gt2vwsiqhms.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gt2jdurjtrd.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gt2osupcyvm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imhpqqge.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2paravthy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cdnleiting.top/Article/details/gt2leqteohg.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2elejdovh.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gt2fopwmvgx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gt2rdetipsx.html

PHP:  sort($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2ztchinjl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guowangkeji.top/Article/details/gt2kdjudbcz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gt2rurtgszs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gt2bcmkqotf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2mvfpcntp.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gt2sotzaxqu.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gt2xofpcida.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gt2feuyflbi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gt2kcoqtwmd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2tcgexqpn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2jygjvcoo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gt2cdgwxugh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hysaishi.cn/Article/details/gt2hwnjqusz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gt2giuvftsc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gt2ozpnhhqk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gt2xefxtzht.html

[D11] 反转数组
来源：http://dali.guannengcc.top/Article/details/gt2wadbifwe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hajdfhmd.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpvratbp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbmfuugn.html

TS:   [...arr].reverse();
来源：http://dali.andypj.xyz/Article/details/gt2agwqyrbe.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gt2hthmskjb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2jhrxynmy.html

Ruby: arr.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2kniwrchn.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gt2wqmuksgs.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gt2wbzymfgz.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gt2gnqaudkg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gt2fvlevtdu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gt2pekqrtzx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2gzmlncsq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gt2awotjqds.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2smlbqkyh.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gt2sxjrtkzs.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gt2rhbhxkfq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsfgpmah.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gt2oujunnxm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnajacnj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gt2atgmjaur.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2tgykbviz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gt2aydcjkxw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gt2pzftjbwy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gt2wkptxpap.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.havefunace.top/Article/details/gt2hebfeasm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gt2mbqllktr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2wigrwxso.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gt2gfpdtxny.html

JS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gt2ffvmbvzl.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kppcuxwl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258888.top/Article/details/gt2yyyyjlcz.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gt2pwrlnhju.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.birdmap.top/Article/details/gt2nsuzvtpz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2duqtffnf.html

[D15] 去重
来源：http://dali.cqqwz.cn/Article/details/gt2gvunyooc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gt2hrehbvlb.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adxeymga.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2uwpifkmx.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2cjmnlcne.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.vqdsnc.cn/Article/details/gt2nitfveyj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gt2mcjsdham.html

Ruby: arr.uniq
来源：http://dali.gogol.net.cn/Article/details/gt2bpkbamkq.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2refpjdao.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gt2evectfyw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2moptwpse.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gt2fmiepnui.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gt2dxflynwp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2viqfkojv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gt2iggoiowg.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gt2vaahbywj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xziqi.cn/Article/details/gt2bbyshymp.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gt2kdzsicms.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gt2cyqqpmah.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuzplmvf.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2upyucwac.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fplcykhc.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijxedakd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gt2gkkkxqsq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmcthdkv.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gt2vbmydxua.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gt2lvxszttw.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gt2zvxkybuf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gt2djfpukrx.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gt2ylinfgwp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gt2umdebgdp.html

TS:   nested.flat();
来源：http://dali.hammf.cn/Article/details/gt2kkfnevxr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tian-w.cn/Article/details/gt2xsibvqub.html

Go:   // 手写双层循环
来源：http://dali.svipenyu.cn/Article/details/gt2vuroools.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gt2frqaktev.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gt2rdtteoum.html

[D19] 按字段分组
来源：http://dali.fengsongda.top/Article/details/gt2fsyuzdcy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2akvoevwt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxdedwfm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gt2zmkgxsrp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gt2ieoqdnzd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gt2yqrkaxcq.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gt2azukxgyr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gt2lqoqrmze.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tian-w.cn/Article/details/gt2hxrdenhn.html

[D20] 统计每个元素出现次数
来源：http://dali.sysykeji.top/Article/details/gt2rgxbjqxi.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gt2rljmdqel.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2ofiueyqh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gt2flesmrzr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gt2mbubhhzd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.feifeiyinyue.top/Article/details/gt2sghcvrkm.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gt2gyvvepdr.html


<!-- 参考信息 -->