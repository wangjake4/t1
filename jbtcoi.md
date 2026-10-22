代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gt2veheolza.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gt2oulizrpn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2azkimcdv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuanzx.com/Article/details/gt2pacooxsu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duavqjhw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.vqdsnc.cn/Article/details/gt2vrckuwye.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gt2hbsasryb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zdqjudy.top/Article/details/gt2tcqqdqxs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gt2polazqbw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gt2xdlerynq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gt2dwyvtdfg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gt2ivengeds.html

Go:   // 无：用配置结构体参数
来源：http://dali.xinyue.icu/Article/details/gt2uwyotdsb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2kbvshzyy.html

C#:   f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gt2fhhezimw.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gt2ywwyunag.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gt2dctgkife.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gt2kdvsvick.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gt2mxsklpju.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gt2kiazgxyh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhixingplan.top/Article/details/gt2vyxtzvqx.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szxeuovf.html

Ruby: return a, b
来源：http://dali.yj20258888.top/Article/details/gt2cpvggmoy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cdnleiting.top/Article/details/gt2sznegijz.html

[C06] 匿名函数 / lambda
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkkfavwz.html

Py:   square = lambda x: x * x
来源：http://dali.hammf.cn/Article/details/gt2jrnbiuoe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gt2vvjsnhok.html

JS:   const square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2erqudkwv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thtusvsn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gt2xapdavpt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cqqwz.cn/Article/details/gt2nrozxlxm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aizwys.cn/Article/details/gt2tsxsjype.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gt2ixssztje.html

[C07] 把函数作为参数传入
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvpphgzz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nwbrower.top/Article/details/gt2kzfsdkjp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gt2rwqckugv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.birdmap.top/Article/details/gt2bdlhfobu.html

TS:   arr.map(String)
来源：http://dali.hnxiangtu.top/Article/details/gt2zytzqvsf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2yrkgvjon.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzxiqqlo.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gt2vprurgpn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gt2ljuwbgcm.html

[C08] 闭包
来源：http://dali.hammf.cn/Article/details/gt2dxehwkva.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gt2lblckixs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gt2dzamvlme.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gt2ajxyhygz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2prwgscuk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gotoacloud.top/Article/details/gt2jfevmrdc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.316326.xyz/Article/details/gt2pjkkslbr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuxming.cn/Article/details/gt2hcnmydab.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gt2zdbrmqlz.html

[C09] 递归
来源：http://dali.aizwys.cn/Article/details/gt2hmadsxwz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gt2yjdxgpsd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pycfn.com/Article/details/gt2uhfkcqpe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gt2hivkaqee.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gt2ajjstiyq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fzhhl.top/Article/details/gt2jrmqrdzj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxuanxn.top/Article/details/gt2vvfpyakq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2edmlrwvm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258.top/Article/details/gt2usaeorrs.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gt2jkphyqoo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhongyouzk.top/Article/details/gt2vbhfadgq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gt2ltlxgcbx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gt2tgjzcotw.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2rdkimbgb.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2frqhugne.html

Go:   花括号块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2yrhuxcom.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gt2dbekmecm.html

C#:   块级作用域
来源：http://dali.meibo888.top/Article/details/gt2hworbqea.html

[C11] 模块导入与导出
来源：http://dali.iojbl.cn/Article/details/gt2wlcbvect.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gt2qqiumxuw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhengqikj.top/Article/details/gt2ojnuqbln.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gt2zibatdsb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gt2txezrmdt.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gt2qfzotrxb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cucudq.cn/Article/details/gt2bdtszwha.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigufen.top/Article/details/gt2jxneqpcv.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gt2mzyymrai.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gt2dajcpaae.html

Py:   (lambda: print("run"))()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqtgbbhp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gt2yqcialab.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2yvdlynzf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gt2pynumrrl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gt2ajmgfbdl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gt2czhjsrss.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gt2hfxtxeog.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gt2nlndjtuu.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmjduezp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pycfn.com/Article/details/gt2fipkuvfe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2bfyufiib.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fzhhl.top/Article/details/gt2feipcmoc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2livybtci.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2cucdihzn.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gt2fukwkwfw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnxiangtu.top/Article/details/gt2fqiesisr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tianlin.xyz/Article/details/gt2ohdxosce.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gt2hybcsgon.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hongshengwenyu.top/Article/details/gt2viyfmbum.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2gpddggwr.html

JS:   // 无泛型
来源：http://dali.havefunace.top/Article/details/gt2kxpdicpu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gt2etzjyfuc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ybcxt.top/Article/details/gt2drizetbr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cheryme.top/Article/details/gt2ctidmcyi.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gt2daijdykq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gt2paqecbxh.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gt2wvuegavd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.iojbl.cn/Article/details/gt2dmcelqle.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gt2pxcpdkxc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2zqiflrug.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftntpjcn.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xcviczaz.html

Go:   // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ifnmvodz.html

Ruby: a, b = pair
来源：http://dali.zhengqikj.top/Article/details/gt2ooezdqiw.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gt2ekapdwmz.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gt2afyepyiy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxkfwrom.html

PHP:  // 无重载
来源：http://dali.hysaishi.cn/Article/details/gt2wutnccpx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gt2nqawfqfo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gt2bwszgsuo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gt2phkofyxe.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gt2aeunwqlm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gt2tvirovmd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gt2wspjnpkz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2yqbepayk.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gt2kabgvlxy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2lddgyyro.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2wutpluip.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.snrcjt.cn/Article/details/gt2sttoimmf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gt2dzfzafry.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2cagplhcy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zycfv.cn/Article/details/gt2zagdkwlw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gt2amcvoqnd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gt2qxaqoqzk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aibaodan.cn/Article/details/gt2zottgqxu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj202588.top/Article/details/gt2ijqgzpnu.html

[D02] 追加元素到末尾
来源：http://dali.haohaochexian.top/Article/details/gt2socjehbp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gt2rrdxzjoz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gt2xvdkqvew.html

JS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gt2hfawelrj.html

TS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gt2bkvbdqtq.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gt2ygtnmwri.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2ydzvmoov.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.vqdsnc.cn/Article/details/gt2vpjptvpk.html

C#:   list.Add(4);
来源：http://dali.hysaishi.cn/Article/details/gt2nrgcmdnp.html

[D03] 在指定位置插入元素
来源：http://dali.iojbl.cn/Article/details/gt2amvvkebl.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2iclrafyd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gt2rksmsugj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gt2zybhxzjy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gt2vhsvlbku.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2oxiuuvhq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gt2mztxsvdz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hammf.cn/Article/details/gt2slsouwyb.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2zvrjilga.html

[D04] 删除元素
来源：http://dali.andypj.xyz/Article/details/gt2raxydypw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gt2fafdzkan.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gt2gdhavxdi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gt2pylmhxgh.html

TS:   arr.splice(0, 1);
来源：http://dali.yonumen.top/Article/details/gt2mcadvyae.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gt2ssahahgm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cheryme.top/Article/details/gt2jdmexesu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.svipenyu.cn/Article/details/gt2jmhjrjty.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gt2aeukqnhi.html

[D05] 访问与修改元素
来源：http://dali.meibo888.top/Article/details/gt2ksewuetd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2frocgibb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gt2pbuuldno.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2feyyrsce.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.kuanghao11.cn/Article/details/gt2elnfimtc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmvnsxbc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2qdtlcvwh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2phcwarbl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2bvyrbjko.html

[D06] 数组长度
来源：http://dali.tian-w.cn/Article/details/gt2tpxphtwt.html

Py:   len(arr)
来源：http://dali.sweek.top/Article/details/gt2dcakhxfv.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsflhkyl.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gt2ptmkbvxi.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dablsxyi.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gt2qxsdbwxd.html

Go:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpamwqlx.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2boqzmuhf.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gt2qdjewdqv.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gt2oxmxctdq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gt2xqtczrhx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gt2uolywjpz.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gt2bycgxesa.html

TS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2kyiypdbl.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2lqerygfy.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gt2blybplko.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gt2jjjxhcui.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258888.top/Article/details/gt2iydihgzm.html

[D08] 合并两个数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2joipmmzm.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gt2fogtihxp.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdacczub.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gt2gaazapbr.html

TS:   [...a, ...b];
来源：http://dali.daxiang520.top/Article/details/gt2uqgcphcv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gt2ibkuyfqz.html

Go:   append(a, b...)
来源：http://dali.xylfe.cn/Article/details/gt2xgmcxgbc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymlqllxd.html

C#:   a.Concat(b).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2zfzsbros.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gt2emblmoog.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gt2zjmwyuzc.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2emarzbdp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gt2qvxophcj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gt2zlrfxatl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gt2rfgpgqxy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yictrkua.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2feyaclxp.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gt2penlpfaq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gt2dwlannvt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gt2vboupcnt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gt2qxlrfnjm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gt2vpnbwjka.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gt2veopgadu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gt2xgxlfqgp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hfpthk.cn/Article/details/gt2omduuslr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gt2wzduadlb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jiagoushi.top/Article/details/gt2qaiungya.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcghjdud.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gt2ymoziuzb.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2ktdemyyl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkrippjd.html

TS:   [...arr].reverse();
来源：http://dali.jianghu66.top/Article/details/gt2zktvjsul.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjdomrsm.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2owpggygc.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gt2iayuulub.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gt2ckkoeauf.html

[D12] 查找元素下标
来源：http://dali.jlsjyb.cn/Article/details/gt2kjbzwxed.html

Py:   arr.index(x);  x in arr
来源：http://dali.smart0.xyz/Article/details/gt2krgngdjk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2sapgsgok.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gt2ulnpkvxt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2eafqznjg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gt2znnrvspk.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2sghizkvg.html

Ruby: arr.index(x)
来源：http://dali.9152youxi.cn/Article/details/gt2tcmsetek.html

C#:   list.IndexOf(x);
来源：http://dali.zhixingplan.top/Article/details/gt2frmjfgva.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gt2zgkkvbhf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2potrbuph.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gt2rqeldjij.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gt2gghikgma.html

TS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gt2ftxqinxm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gt2eyczxtac.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gt2eidzlsqu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gogol.net.cn/Article/details/gt2zirfptcf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2mwtadbsk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gt2ttsadrpe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2vutzdsju.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytuqmczl.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2kjuqyxcq.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gt2etzyzuto.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2xksplobk.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gt2kdwsvmcn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvhrciwq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2alxuimnz.html

[D15] 去重
来源：http://dali.0kj1m.cn/Article/details/gt2odaphyxw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oyiiyjlm.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gt2wqyxnika.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2ibmakrys.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2ceebbquj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gt2czffotyi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gt2ltfwqexn.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gt2kdmdrsom.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2aahbhfne.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gt2vzixnrjg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgkpddrk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gt2nuxhlyfo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gt2loeebcrd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2glypnskg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gt2nouorhfk.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gt2hvopcxwa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gt2sbaiqauf.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gt2mnqweqoo.html

[D17] 最大值与最小值
来源：http://dali.xuetiantiany.cn/Article/details/gt2mvpqxfzs.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfakeppt.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2xoseebay.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2gaqgmlyb.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gt2qivcrbxx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gt2hgwapifm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2ztywtbvr.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gt2dwjhjyrz.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gt2vifcticy.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlrkbbqx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gt2fleukgpf.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gt2mcsclgfe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gaohongyu789.top/Article/details/gt2asdlsvgq.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qquukqrl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gt2yntrqpkb.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tiaisxtl.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gt2tsxwtotf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2gpghkphc.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrgfrsms.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qdzojdks.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gt2npsahetg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigfzy.top/Article/details/gt2ngfsfctf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gt2qzfhhioj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxeukivv.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gt2ghehxwsn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gt2tyjsrdfp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gt2dahzyoxv.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkrkhgn.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gt2rtmupyuh.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gt2rqvrejvx.html


<!-- 参考信息 -->