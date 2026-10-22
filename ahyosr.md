代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2paykccuj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gt2ultdlhhj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gt2qneoiicm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxuanxn.top/Article/details/gt2syvlbmaz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258.top/Article/details/gt2wijnibyo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gt2ltaxuvzv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gt2owlwndve.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gt2zerqprve.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2usztbbus.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gt2jonocsjr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gt2nwzzkfnu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258888.top/Article/details/gt2nnplxdpz.html

Go:   // 无：用配置结构体参数
来源：http://dali.smart0.xyz/Article/details/gt2gyamkzvk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gt2vovinfbw.html

C#:   f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gt2zomodcar.html

[C05] 返回多个值
来源：http://dali.daxiang520.top/Article/details/gt2fzzppeab.html

Py:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qgucqqvy.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gt2zxitjien.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tanke756.top/Article/details/gt2ykvvkste.html

TS:   return { a, b };
来源：http://dali.yueranfly.top/Article/details/gt2pnblfadh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gt2pbrtffii.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmgnwtx.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gt2mqsoivnm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aizwys.cn/Article/details/gt2bwqnvkfx.html

[C06] 匿名函数 / lambda
来源：http://dali.yangfankeji.com/Article/details/gt2rfekycfb.html

Py:   square = lambda x: x * x
来源：http://dali.cheryme.top/Article/details/gt2qzbneuwn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2eyzivsag.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2zeladtlb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.redwolf501.top/Article/details/gt2mtgsktyd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2sygtccfo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigufen.top/Article/details/gt2itgzgkiw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgufenzy.top/Article/details/gt2qjawgeoj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfubvjgl.html

[C07] 把函数作为参数传入
来源：http://dali.yangfankeji.com/Article/details/gt2pjsoxkwd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gt2krahxhfk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2yoswfbqe.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fengsongda.top/Article/details/gt2szzfnucw.html

TS:   arr.map(String)
来源：http://dali.zhixingplan.top/Article/details/gt2tcuacrok.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2tvneqhep.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gt2wvzbvehb.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gt2vgbdldpa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gt2tuiwftoc.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gt2pjpmkxgl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gt2vixxotgr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ikrryucj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2leqlyuxk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2gdaipdap.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenlongwang.top/Article/details/gt2jcvsoufr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gt2pxysovwt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gt2fteqzank.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gt2gkuchlgh.html

[C09] 递归
来源：http://dali.guowangkeji.top/Article/details/gt2brtkpllp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gt2hzyvjbxw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj202588.top/Article/details/gt2xyirdmcx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2aecgwvhc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gt2pgkjaxix.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gt2wsavrsmp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.havefunace.top/Article/details/gt2ramcbbtd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2amudexxx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.andypj.xyz/Article/details/gt2rttiupvg.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gt2ymxoftrl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gt2alcatzsg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gt2fpqvaepw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gt2egkrtyor.html

TS:   同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2icqysbia.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2mtrofplw.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gt2nadlufok.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yvedp.cn/Article/details/gt2bbyqqkgn.html

C#:   块级作用域
来源：http://dali.ybcxt.top/Article/details/gt2tunodqeu.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gt2glcibysx.html

Py:   from module import func
来源：http://dali.0kj1m.cn/Article/details/gt2lfgqshyp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuanzhike.top/Article/details/gt2ziastilu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gt2fvymrfax.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gt2vhfqnzcb.html

Java: import java.util.List;
来源：http://dali.0kj1m.cn/Article/details/gt2dsgvtczc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangdashe.top/Article/details/gt2aimqplhn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gt2tiblqlak.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gt2pbgyxbjm.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gt2ewqojakp.html

Py:   (lambda: print("run"))()
来源：http://dali.ivvv.top/Article/details/gt2opkavaqh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gt2ushntgzj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gt2rjeuagvc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drsgzibt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gt2tarluabo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kyruizwm.html

Ruby: -> { puts "run" }.call
来源：http://dali.gotoacloud.top/Article/details/gt2ecvecxie.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gt2zcuxttcy.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gt2venhbmjp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gt2gurvzbtz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2usmpcwqn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gt2kpoehvsz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2ruvfvwub.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2yqnydoip.html

Go:   func add(a, b int) int
来源：http://dali.9152youxi.cn/Article/details/gt2vnlbppex.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hammf.cn/Article/details/gt2kieyinos.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gt2jaclrnap.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gt2uasccqbf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gt2hieykiab.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2ckhuvdsd.html

JS:   // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhwjceqv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.havefunace.top/Article/details/gt2otzygtoj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gt2sycdudpn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gt2avcgnlhn.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2jcrnifny.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gt2bnsmnojg.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gt2cvomchkd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gt2mcyrrkzr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.havefunace.top/Article/details/gt2lgwuhifq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvdcxnsv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gt2tkehucva.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gt2qpiccakb.html

Go:   // 无解构
来源：http://dali.c1oappe.top/Article/details/gt2ywawblgw.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gt2uggmnrlw.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvsssfp.html

[C16] 函数 / 方法重载
来源：http://dali.zdqjudy.top/Article/details/gt2lktkvsbg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqvtrmdc.html

PHP:  // 无重载
来源：http://dali.zhiwuduotai.top/Article/details/gt2efuhuwxj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gt2pvsvipic.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sxryk.cn/Article/details/gt2mhsbqijm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gt2kqkfgpls.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gt2tvupzazt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gt2evacnfgf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ehwqpu.com/Article/details/gt2tifikchb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2zjqrpxpi.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gt2obygazxo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2mufpxrkj.html

[D01] 创建数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gt2wlsifile.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daxiang520.top/Article/details/gt2ammxglyu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gt2usjmnzdl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gt2ggxqmcmo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pycfn.com/Article/details/gt2nitneljs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gt2urvfpbih.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sufxvd.cn/Article/details/gt2wsfompxx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfeoktjz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nwbrower.top/Article/details/gt2awctpwmq.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwmwpfb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gt2aovfuwzd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gt2bbpegawc.html

JS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gt2jhinylem.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gt2mdxgyzts.html

Java: list.add(4);
来源：http://dali.sxryk.cn/Article/details/gt2gbdtysqf.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gt2prbjxdlz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qtjhxluo.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gt2gxjnugft.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gt2syzqbzaq.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gt2uoljdpdu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gt2mjypwynt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuanzhike.top/Article/details/gt2wcwgxcyu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2hpfpjhdq.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2tbfzbpjx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gt2ntdzrkxm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gt2uslonkwf.html

C#:   list.Insert(0, 0);
来源：http://dali.daxiang520.top/Article/details/gt2crwkyvbr.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gt2voqxkpkp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gzhubu.top/Article/details/gt2bdxgcuzu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ydzc1.top/Article/details/gt2efenwato.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gt2hlcrzerh.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcmmccpb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gt2rzccslgy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gt2qmmutqfz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gt2cpiuwafj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gt2xiomzsmq.html

[D05] 访问与修改元素
来源：http://dali.zhixingplan.top/Article/details/gt2iqysdmte.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gt2uyztlyny.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gt2bogsuimy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2faxxznfp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gt2qoxhnthv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gt2wpueyncd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvkdtetn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2jdijzfog.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2pomqbsaq.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gt2bhyvrire.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2bjeyihoy.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2eyemxlcw.html

JS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gt2rhzuzxry.html

TS:   arr.length
来源：http://dali.hammf.cn/Article/details/gt2iswnjmdl.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gt2pjejsesh.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2wqmvyvby.html

Ruby: arr.length; arr.size
来源：http://dali.birdmap.top/Article/details/gt2ukpmdcxw.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gt2avgpdmnn.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gt2ftzwlruu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cheryme.top/Article/details/gt2gymismwc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2ixgtsggq.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2jzrpzqtz.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gt2vfwmkltb.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gt2tsoxmmkc.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gt2xswimogx.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gt2rohhmdeg.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gt2ftlhfnrd.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gt2ectpewyr.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2bldtijqx.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gt2qdgscgrp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gt2zjvvhdas.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2smqylykz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.mhx1999.top/Article/details/gt2bzttwhhr.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gt2wmzvomsq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yueranfly.top/Article/details/gt2sdjdqpzr.html

C#:   a.Concat(b).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2xxmdnndl.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gt2ohyiaebg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2eiliizae.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2eyzbrsug.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gt2avgdbgcx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gt2nnopfojv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gt2knzjhtsv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2rcobudtz.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gt2gayjepbl.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gt2rcczxwjh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlcoaili.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gt2yrldorxr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gt2tomrtvfe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2pbaxzegp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gt2ecbufrhs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gt2adgsepxz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gt2hrplqgpe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gt2scaicndt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.c1oappe.top/Article/details/gt2wfqiclwy.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gt2jwgnlpvw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shzxlz.cn/Article/details/gt2yughzmxj.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gt2vcohnqnb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gt2oiboqaeo.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gt2fgszakof.html

Java: Collections.reverse(list);
来源：http://dali.svipenyu.cn/Article/details/gt2mvodxudd.html

Go:   slices.Reverse(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2mcxopelh.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gt2vfotwxkp.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gt2htijzntz.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gt2wihxolrx.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gt2rwwnbfbj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2jdmmxqth.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gt2jqgjhatl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gt2weftkbnt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ehwqpu.com/Article/details/gt2rfcpdjze.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2ffpaoqto.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gt2snoyyibm.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gt2wlgtlxhk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gt2drnrmpto.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzujfbju.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofkfkgyt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2cpltlgln.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2jkjqlvfw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gt2yunnyxod.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cknrlaqn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rpfpjqts.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sweek.top/Article/details/gt2pfmlvxve.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gt2kfgxgpdv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gt2thgokvcg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2myknairp.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gt2reokkmsx.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gt2stoluasm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gt2cxrxvrvq.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gt2ifwjkgsz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gt2accfbygl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbostnim.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gt2xifnlmby.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gt2vkwywmqb.html

PHP:  array_unique($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2omatzkmq.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmvzlbm.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2zukqiahg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gt2usequqek.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gt2uqjahrfo.html

Ruby: arr.uniq
来源：http://dali.sxryk.cn/Article/details/gt2ykhybzyu.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdbrlmbg.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gt2fckktmxb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzwznstw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2rvlidsbp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2bnzzupkk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmpmpiln.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gt2vgfbewkv.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gt2mwcskiih.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyeauvla.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukabxvcv.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gt2xfwfqdul.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2pdampqfh.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gt2czgioytm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gt2mneumdid.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gt2volzxyiq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gt2telmajni.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gt2nuuvqolx.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gt2dbkqsykt.html

C#:   list.Max();  list.Min()
来源：http://dali.c1oappe.top/Article/details/gt2gomzssso.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gt2dvizsujz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gt2nejaryrs.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvagtbfa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gt2naxwmyrx.html

TS:   nested.flat();
来源：http://dali.cqqwz.cn/Article/details/gt2hdcjtjrb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gt2pnttkqwk.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gt2rwqbvcra.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gt2pfnmbukg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.meibo888.top/Article/details/gt2qswtgnsp.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gt2jnhprvrc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gt2xbimrofi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gt2ipfzfuol.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztrumlzn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gt2hvdmhlvb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shzxlz.cn/Article/details/gt2sozgqzgt.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gt2odnpqbtm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gt2hpnfwogq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gt2vgvmkiej.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbvdbhda.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2vgrvbcmi.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gt2zcwqoyae.html


<!-- 参考信息 -->