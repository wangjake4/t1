代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gt2srtgqqyd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2zlvwdylt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yonumen.top/Article/details/gt2ljapdbte.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gt2sqopvyqc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfwqnkoo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gt2lbimyyzj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.iojbl.cn/Article/details/gt2uerkediq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gt2lcgceccc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aibaodan.cn/Article/details/gt2mteblyrk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2mrikxyrs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aibaodan.cn/Article/details/gt2tipjluue.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.feifeiyinyue.top/Article/details/gt2whfvgzdo.html

Go:   // 无：用配置结构体参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2xakudyuv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2xkmuhpku.html

C#:   f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gt2wmzhloss.html

[C05] 返回多个值
来源：http://dali.aibaodan.cn/Article/details/gt2pvfeqisi.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2ouepxkog.html

PHP:  return [$a, $b];
来源：http://dali.gotoacloud.top/Article/details/gt2ouxewqbj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gt2sgaekmgc.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gt2vttehkcz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gt2epbzxpax.html

Go:   return a, b
来源：http://dali.ivvv.top/Article/details/gt2kfkmzahu.html

Ruby: return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2iojnonon.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gt2vmgrdhmc.html

[C06] 匿名函数 / lambda
来源：http://dali.c1oappe.top/Article/details/gt2dtlgjbva.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gt2wbnultfv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jianghu66.top/Article/details/gt2swvphygx.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gt2nedwnxmp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxaxlryr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdacpqnm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.quarkkingdee.top/Article/details/gt2vcpajnld.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cqqwz.cn/Article/details/gt2lfnrdqwj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gt2joqkmaml.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gt2refvyovi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gt2axgilodl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2tycdwmzb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yvedp.cn/Article/details/gt2kihmejgp.html

TS:   arr.map(String)
来源：http://dali.hnxiangtu.top/Article/details/gt2vwbgnitq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2wvybqrbo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gt2jznhsdec.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gt2ngoelyij.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gt2aicvajik.html

[C08] 闭包
来源：http://dali.jiagoushi.top/Article/details/gt2pjwfvbib.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gt2tgnaztoi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zdqjudy.top/Article/details/gt2fktchkig.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2hjlmqdwc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pztxcapw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jiagoushi.top/Article/details/gt2npoiiywo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cqqwz.cn/Article/details/gt2gjhlxuww.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jyoumei.cn/Article/details/gt2gwlrvjvt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2atesguqf.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gt2iwwegtms.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gt2hhxthhil.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gt2wtikxdtb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gt2bmmkhgoq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gt2lszsqiip.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangdashe.top/Article/details/gt2pyakcjak.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gaohongyu789.top/Article/details/gt2npqtnkkr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipzuszlp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.316326.xyz/Article/details/gt2pacsiqui.html

[C10] 变量作用域
来源：http://dali.shuidangran.top/Article/details/gt2jtyxdhil.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sxryk.cn/Article/details/gt2tqwgkaum.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xinyue.icu/Article/details/gt2hkegwpta.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.meibo888.top/Article/details/gt2whfrbzto.html

TS:   同 JS
来源：http://dali.hfpthk.cn/Article/details/gt2vrphewqe.html

Java: 方法内为块级作用域
来源：http://dali.yj202588.top/Article/details/gt2gxgoxpex.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2jdboqpoa.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shuidangran.top/Article/details/gt2rawmchwl.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2njqevift.html

[C11] 模块导入与导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flpzuwfr.html

Py:   from module import func
来源：http://dali.meibo888.top/Article/details/gt2ybdulkkz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gzhubu.top/Article/details/gt2ryqghpdb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gt2yjyipnqa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gogol.net.cn/Article/details/gt2drfgiswy.html

Java: import java.util.List;
来源：http://dali.smart0.xyz/Article/details/gt2tarxzvzw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gt2ojmufcsq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2obxmprkx.html

C#:   using System.Text;
来源：http://dali.birdmap.top/Article/details/gt2wdftrscz.html

[C12] 立即执行函数 IIFE
来源：http://dali.quarkkingdee.top/Article/details/gt2antpyfxe.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gt2erkvnkvc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ppjwa.cn/Article/details/gt2wwizzffj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2txsqodrm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gt2djnokdvx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hammf.cn/Article/details/gt2bqpefsvd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shzxlz.cn/Article/details/gt2xrbbzyhb.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gt2dunblwsz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gt2bjchqpov.html

[C13] 类型声明 / 类型注解
来源：http://dali.yangfankeji.com/Article/details/gt2esbejyjl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gt2lnahatln.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2cdlthocc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytfmgpem.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2ivnqzxnm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2mmmwermf.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gt2cqiapiji.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gt2dodgctxe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gt2xedqgwbw.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gt2zwrpuqtj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gt2zehqtxuo.html

PHP:  // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2ycnpumxp.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2hmergsyk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gt2iwrwzull.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gt2iwtqpwso.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gt2liwuaeov.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gt2qwtfyvwj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gt2cwmshwnc.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gt2hnyvjbwc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gt2flmkrizo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gt2gzmbplqo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2zhyqgdno.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gt2dvfqonsu.html

Java: // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2aonfxuvi.html

Go:   // 无解构
来源：http://dali.cashguo.top/Article/details/gt2oyqlpazf.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gt2ccogdhjl.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gt2dovikdlc.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gt2wuegfrwx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.316326.xyz/Article/details/gt2mulprltk.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gt2syzwqbzz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.9152youxi.cn/Article/details/gt2jhvovlpw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yvedp.cn/Article/details/gt2tpqvioeo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2irqrqoyl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgfgodz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2isrzhcaz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2ppbmhwoe.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2vpydtikf.html

D. 数组 / 列表 / 集合
来源：http://dali.tianlin.xyz/Article/details/gt2zerwyyuz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlxdziun.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gt2bmjjbkpj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gt2olmcoxbk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfnntjlq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gt2lkmjlqge.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gt2mrrzcabl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xylfe.cn/Article/details/gt2vkuilrtv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhawjyvk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gt2noctcefw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gt2aaczqrsn.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gt2avcqnqim.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gt2gkulptub.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yonumen.top/Article/details/gt2jvebmijx.html

JS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gt2pdrlkdjh.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gt2iaigcllr.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gt2smdauwxh.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gt2vyhyvzbr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvevybqt.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gt2yztycykm.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gt2xiailozw.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gt2uxlftdqj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gt2sctfcmfv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gt2zuxxijge.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2zmipfkkw.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2sroosrqw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ppjwa.cn/Article/details/gt2mxbutlgy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gt2netongbs.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2cohlwyyu.html

[D04] 删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2lthvpkwy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fengsongda.top/Article/details/gt2nhvbjvhy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2jtkomkkl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangdashe.top/Article/details/gt2ufzfpetb.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gt2odbkwkhn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2smsdnkwl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aizwys.cn/Article/details/gt2ugnvdvml.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aizwys.cn/Article/details/gt2dxawambf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gt2rstmrrev.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gt2smmlmrsx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gt2seruosyd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2jdjxvrtu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gt2ywgrdpzh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gt2iphhlfcv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gt2nidnzjbf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gt2hcpwxcmm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2fdafbabu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2mzswtldi.html

[D06] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxsoijoj.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2waqsohsz.html

PHP:  count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mkkspbmr.html

JS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gt2kvnuslnn.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2boxfkaho.html

Java: list.size();
来源：http://dali.jinqigfzy.top/Article/details/gt2vkoqlzok.html

Go:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2ufnvypvl.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2knfvglwt.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gt2xuiwwfzq.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gt2fzopyugj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gt2iqisidad.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gt2jzsxarlz.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2wwnpmclk.html

TS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gt2hazqgews.html

Java: list.subList(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2exaxbjgb.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gt2hqozsqjv.html

Ruby: arr[1, 3]
来源：http://dali.ehwqpu.com/Article/details/gt2djzojgni.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2thctflzw.html

[D08] 合并两个数组
来源：http://dali.shzxlz.cn/Article/details/gt2dbkiubpm.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2bjvjkecj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtspmqqg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guowangkeji.top/Article/details/gt2qesmyzxy.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gt2pvzsshhf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgmkyshi.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gt2rfbbpptq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2iigzszbh.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2qhncfrhx.html

[D09] 排序（升序）
来源：http://dali.shzxlz.cn/Article/details/gt2losskqll.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kintiprk.html

PHP:  sort($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckmnrayw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gt2qagambhl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tianlin.xyz/Article/details/gt2lxoonexh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gt2gfcwbsnn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2zmpnbctw.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2wubqiqvj.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gt2mcnthdxq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gt2zeljzgnx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ppjwa.cn/Article/details/gt2yhwsormh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gt2fqoojulo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gt2hpvstcqr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xovgxgbz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gt2ejyhwbay.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gt2mipmjbiz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gt2cfyqijrm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gt2zvhqewqs.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gt2eaupazjm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guannengcc.top/Article/details/gt2ppdbpzag.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gt2segekyfr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dndfczdr.html

TS:   [...arr].reverse();
来源：http://dali.aizwys.cn/Article/details/gt2igniefdv.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gt2aqjdzxgg.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gt2zykcmhfp.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2qtdseybz.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gt2lytdmrpp.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gt2gimtfmmc.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gt2qlohsnwv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2frfdbsbe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2smtaiztu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gt2ufltjvsz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gogol.net.cn/Article/details/gt2fwlljidv.html

Go:   slices.Index(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2pmdbdylt.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvioacdl.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gt2ftpsglrz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gt2bhhmggzq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2lbhvvrhj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gt2iivhmjyk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gt2tkxvetho.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2fpvzompv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gt2kgaffkfp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gt2zqmtgmfe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snavrzov.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2oxjnnblh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gt2zhnbuimv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2yfwbqmet.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2olnnadiw.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgisenw.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gt2cugdfjzm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gt2fndjcemc.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gt2kezyygok.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2elppyzfg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gt2pjfhpqjl.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gt2uahjtlpm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gt2yygcitfz.html

PHP:  array_unique($arr);
来源：http://dali.shuidangran.top/Article/details/gt2bnhsvplw.html

JS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gt2yfxzawqy.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gt2idszegvu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gt2salnfscy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfearduo.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gt2vkzysdng.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gt2hmsmguyw.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gt2vscckwwz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gt2wmmdhoop.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ceuhjrab.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2dywtqcnc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gt2mzoqmfjw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gt2qsvayejj.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gt2noqbzpge.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gt2fjbzxwbw.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gt2mefpmghj.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gt2uklnlcqa.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2bwlspyqy.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gt2gkegziws.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gt2ubtxejjo.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gt2aivfzlru.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2uhklnjjv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2miwqbdjz.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gt2kbxtdqpx.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oirjjpin.html

[D18] 扁平化嵌套数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2niqmnmqw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxinkj.top/Article/details/gt2umqodufa.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gt2qxxxnrbw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gt2miewjruj.html

TS:   nested.flat();
来源：http://dali.shuidangran.top/Article/details/gt2nacgefzy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2darjatdw.html

Go:   // 手写双层循环
来源：http://dali.ivvv.top/Article/details/gt2ztokcyvz.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gt2fxtmkdjr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2otibjnkf.html

[D19] 按字段分组
来源：http://dali.zhengqikj.top/Article/details/gt2dawhldjg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jianghu66.top/Article/details/gt2pwxdjuqs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gt2bzfxynfx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gt2onlvwapg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gt2zxstpbbk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gt2tvnaygex.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gt2xycgnhuo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gt2lcmztuko.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gt2qdsbmslh.html

[D20] 统计每个元素出现次数
来源：http://dali.jianghu66.top/Article/details/gt2vuzmtfdt.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gt2sxksupuo.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gt2zuqtsfye.html


<!-- 参考信息 -->