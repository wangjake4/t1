代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgufenzy.top/Article/details/gt2kqtdquce.html

[C03] 可变参数
来源：http://dali.fengsongda.top/Article/details/gt2mitwqpnq.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrgovkyx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gaohongyu789.top/Article/details/gt2jxbsowlr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yavcedau.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gt2rmxarowk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gt2ktablevn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tanke756.top/Article/details/gt2pnkqgpvb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aizwys.cn/Article/details/gt2cpnqzzkg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenzaomai.com/Article/details/gt2jontlgeg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gt2egulvcji.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gt2dneizavr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gt2kjumkxcv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gt2amgdukdm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gt2vdyzivwf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.kuanghao11.cn/Article/details/gt2kghkajpa.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258888.top/Article/details/gt2lkrxlyiz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gt2brzpmivb.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbsbvhtr.html

[C05] 返回多个值
来源：http://dali.gotoacloud.top/Article/details/gt2azendjph.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2bdnwialw.html

PHP:  return [$a, $b];
来源：http://dali.pycfn.com/Article/details/gt2qtxbptnp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gt2tlrftvvt.html

TS:   return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gt2zauwuoeg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhiwuduotai.top/Article/details/gt2gspcpgwq.html

Go:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2ozjctdcj.html

Ruby: return a, b
来源：http://dali.0kj1m.cn/Article/details/gt2bnpiknto.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gt2bpnnzzvk.html

[C06] 匿名函数 / lambda
来源：http://dali.haohaochexian.top/Article/details/gt2hvwgwitw.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gt2lmikehwm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gogol.net.cn/Article/details/gt2dtqsiuge.html

JS:   const square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gt2ippkqjey.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2qiwmocbk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.birdmap.top/Article/details/gt2apmfxyau.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.havefunace.top/Article/details/gt2pwbutjwi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gt2hmoozpwv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2nuwbbmwp.html

[C07] 把函数作为参数传入
来源：http://dali.0kj1m.cn/Article/details/gt2njlmagsv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gt2edzmxisy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gt2xddnamxq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hywenlv.cn/Article/details/gt2gjeccpzk.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gt2vdtmtiyb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gt2lssvzqdl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gt2bfxuhdxb.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcrhvzay.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jianghu66.top/Article/details/gt2pacfsyev.html

[C08] 闭包
来源：http://dali.xuanzx.com/Article/details/gt2grnaxngw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gt2buodtkee.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gt2fngfufil.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gt2hlbostlz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gt2dvltktdo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gt2iiljjixy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2emthybvf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shzxlz.cn/Article/details/gt2ptiywwch.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2catfomix.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbystqer.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gt2rjqgcmsx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gt2qqcpamfo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gt2mrvucdld.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gt2hbvqlxbz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djolenqf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cucudq.cn/Article/details/gt2jppupeld.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gt2zwtnvlzn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ybcxt.top/Article/details/gt2regpxxmx.html

[C10] 变量作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2uyoiicmx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sufxvd.cn/Article/details/gt2fffuqhec.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmiexilj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2focuybwc.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2zanuybbx.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2xkvtazsm.html

Go:   花括号块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2jdewxxtl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.havefunace.top/Article/details/gt2itslypww.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gt2dgpcjanw.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gt2fawqnkxu.html

Py:   from module import func
来源：http://dali.yueranfly.top/Article/details/gt2oyonsrap.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gt2qkwuzbtx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gt2tluzrguo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gt2dpxwhmmg.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjptulvu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xziqi.cn/Article/details/gt2kxuegndv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gt2vkriogxs.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gt2rrbefklm.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gt2uxwvwnqv.html

Py:   (lambda: print("run"))()
来源：http://dali.jyoumei.cn/Article/details/gt2yskzbnzs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gt2xopbybsi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gt2uegayvun.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gt2lnmpvdat.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gt2xssbvszt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tanke756.top/Article/details/gt2hiacxynx.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkinsjgk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sucxdukp.html

[C13] 类型声明 / 类型注解
来源：http://dali.cashguo.top/Article/details/gt2rmrxilof.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2orearqwx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gt2tziusdqb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gt2kwxsdlgh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2rkbxldqg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2ozzrwkly.html

Go:   func add(a, b int) int
来源：http://dali.jiagoushi.top/Article/details/gt2extayybk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gt2adbcsong.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigufen.top/Article/details/gt2sfvhetsa.html

[C14] 泛型函数
来源：http://dali.jianghu66.top/Article/details/gt2ftepovwv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gt2toezandz.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gt2sjmwljkd.html

JS:   // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gt2fgfuypkp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2roqkkbrz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2eamaalpa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.haohaochexian.top/Article/details/gt2aeasaiuu.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gt2hwtnkxjf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gt2vvyqngyc.html

[C15] 解构 / 展开参数
来源：http://dali.chenlongwang.top/Article/details/gt2fdsiucrr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gt2qwtamkfz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yonumen.top/Article/details/gt2nblybspj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gt2pcvmihmf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2uaxdvadb.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gt2bluextem.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2ynfwktuj.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gt2ksqrilpg.html

C#:   var (a, b) = pair;
来源：http://dali.zycfv.cn/Article/details/gt2gvpavcxq.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gt2semozhhx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gt2xsqouayl.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gt2ecfzibib.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gt2axiofgzi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gt2sixncmjf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gt2guqjxtjm.html

Go:   // 无重载：用不同函数名
来源：http://dali.mhx1999.top/Article/details/gt2kjfarlpl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2nawnbfzq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.316326.xyz/Article/details/gt2syfzhecq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2odhxsszx.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gt2yjmvpfzu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2cchetskw.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2otlewpbv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gt2fsyrnrcq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.9152youxi.cn/Article/details/gt2cwnmdhmr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gt2tdhwiwje.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gt2apygaegc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnddtbuh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gt2xybsnvpy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gt2sjzutavl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gt2mlnaftoj.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gt2gqmifjry.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gt2fknlhvzn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.snrcjt.cn/Article/details/gt2idirbjix.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gt2boouqnlb.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2jsgwzlbb.html

Java: list.add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzcuqpyh.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gt2itoouaki.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigfzy.top/Article/details/gt2ubdjsurf.html

C#:   list.Add(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2bposxdiv.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gt2qyxydkpn.html

Py:   arr.insert(0, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2tiuxijbp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gt2fwgkdefr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gt2sxelxllu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yvedp.cn/Article/details/gt2mtnyujga.html

Java: list.add(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2covdotqx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nwbrower.top/Article/details/gt2ufedbqdi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuanzhike.top/Article/details/gt2othokurq.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gt2kaucsrgm.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gt2ojcujbzk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guowangkeji.top/Article/details/gt2jtnmovoo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gt2vbqrpvpa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gt2qkyjgdhn.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2icyrcwxi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gt2nzfgfevn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gt2syhhevjt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gt2laaufjly.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xafrwdem.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gt2rxbxgeun.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2ooyfyxnk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhjasugj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejnoubdo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shuidangran.top/Article/details/gt2bzpyyfqu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gt2wstkuvwr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2nzzxkzpl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2vnrrwxtz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2zrxsimlp.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dykjstkg.html

Py:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2xrshpjey.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2xppalheg.html

JS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2lhncsefq.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2iecmvezy.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gt2kemdfwii.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gt2dmffiymq.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gt2gmmzsznx.html

C#:   list.Count;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xyvyvuek.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gt2uxfpxazi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gt2hydmtrvf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tianlin.xyz/Article/details/gt2ktzrdnvu.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2ggigbqpf.html

TS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2qiicwfmh.html

Java: list.subList(1, 4);
来源：http://dali.andypj.xyz/Article/details/gt2cqaxjwtx.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gt2kkegdpsu.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gt2tgmpmepi.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rpgcvwse.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gt2dndxsjxk.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2dczwqgsx.html

PHP:  array_merge($a, $b);
来源：http://dali.guowangkeji.top/Article/details/gt2tunhfrgq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gt2czqfmdmm.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gt2hlewtggx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2ejrprabj.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lsvvagax.html

Ruby: a + b;  a.concat(b)
来源：http://dali.svipenyu.cn/Article/details/gt2jbftbzzu.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gt2nicfcvch.html

[D09] 排序（升序）
来源：http://dali.pycfn.com/Article/details/gt2bepogctc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2nsqwtyhb.html

PHP:  sort($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2jcnpzhkx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gzhubu.top/Article/details/gt2frintoso.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgufenzy.top/Article/details/gt2twuovvpe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gt2iolgydut.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2ukmetsei.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gt2cetltyim.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iiumerzo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gt2zlibgzhs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gt2qiwkmohb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhfjiguj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gt2jioobrzt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gt2vqbgmqha.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gt2shhojuiw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gt2cheqinjh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shuidangran.top/Article/details/gt2wunzdptz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ybcxt.top/Article/details/gt2jalzfkfb.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxvmrlnq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sxryk.cn/Article/details/gt2lhiczaen.html

PHP:  array_reverse($arr);
来源：http://dali.316326.xyz/Article/details/gt2oihmoqpz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gt2hinmmshk.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gt2tihxpqrn.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gt2czkscklo.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2xdkibhwf.html

Ruby: arr.reverse
来源：http://dali.mhx1999.top/Article/details/gt2xznafczu.html

C#:   list.Reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gt2toxdvxyg.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gt2tvsdcquh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gt2trwcduse.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2lrkemshh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gt2orvvqukd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2bragzxme.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gt2opqmdlow.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2pjmbblab.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gt2xlkwlpqz.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gt2cjhtfxyn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xziqi.cn/Article/details/gt2umrnnhjp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gt2xxntwhyp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gt2tltbvyth.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2sbzpfedy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2oclbxdkq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gt2lhgkkkzh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gt2xckbapss.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cufkomkh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2mgmwtzmd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhixingplan.top/Article/details/gt2aytmfdfq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gt2vykuoszl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijmewdgj.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gt2crpmtuvt.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2zxfgwnfx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gt2mrcxhnyy.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gt2cefeqpju.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2ennkyyzn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2acfuxews.html

[D15] 去重
来源：http://dali.guowangkeji.top/Article/details/gt2lpsclfui.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gt2gyfvtoso.html

PHP:  array_unique($arr);
来源：http://dali.yj202588.top/Article/details/gt2nuehqdoi.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gt2fpuegqst.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvlujvvk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigufen.top/Article/details/gt2zmxpjtla.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gt2zbtjtxqf.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gt2rltwmphq.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gt2yhzldarn.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gt2qtpbclqk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2llgayoor.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2ozfznbom.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2wdsldpad.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lphupals.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gt2pdktvlim.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gt2zlfyseir.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gt2xgaeduyc.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gt2eiddnmoz.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gt2zblrfcgq.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2kaeiwccs.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2jdloiena.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gt2dthxymoz.html

TS:   Math.max(...arr);
来源：http://dali.xylfe.cn/Article/details/gt2ufbnihkq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnrhybxb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gt2dxktmtbl.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gt2qgframxl.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gt2ajlorgtb.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gt2axnxxewk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gt2ckztvdsp.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gt2snyfyqlh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmkyfkty.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klamarnh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2xetgnnbo.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gt2ohhwrsfc.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gt2yalhpyxp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2mcmsmxvi.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gt2xgphsegp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.birdmap.top/Article/details/gt2jeagujcu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czaquogs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gt2fbltydlt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gt2wpqyuxbg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gt2artrxglk.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gt2nfpbsigs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xinyue.icu/Article/details/gt2mrerrgoj.html


<!-- 参考信息 -->