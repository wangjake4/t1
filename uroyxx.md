代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.gotoacloud.top/Article/details/gt2dokqqseb.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gt2mtwgheck.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gt2ofcghtvn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gt2fvtojaed.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gt2brrzykhx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gt2eipnfcgy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2desumaac.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gt2rjfzbgqh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gt2jfycjhvz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gt2qmzqreon.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2iishrquf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.smart0.xyz/Article/details/gt2ozjidirp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gt2rojkxbmy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2nerkchca.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gt2tuhrxvfj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuetiantiany.cn/Article/details/gt2anhukjgb.html

Go:   // 无：用配置结构体参数
来源：http://dali.hfpthk.cn/Article/details/gt2wgejlknp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gt2hswtwmfs.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2tyvchspm.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gt2purwnnjj.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gt2ghbgffcl.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gt2tdziejfy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvbxqosb.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gt2lctjgggk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gt2lcpttukp.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gt2qamrkhzy.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uviuohin.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tianlin.xyz/Article/details/gt2msvwirxd.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gt2thsprqjb.html

Py:   square = lambda x: x * x
来源：http://dali.havefunace.top/Article/details/gt2wbdqakpd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cheryme.top/Article/details/gt2nmagnosk.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gt2zbpgiceg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2nstldabl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.redwolf501.top/Article/details/gt2ciygbwwr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gt2vmacejgu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.quarkkingdee.top/Article/details/gt2ktjdyplj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2jgcgewyv.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljkriwsa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gt2qlftqppb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2hzflzpjd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yvedp.cn/Article/details/gt2idedbzpa.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gt2djesltzp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gt2jtjjtlzi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gt2fzteqvtr.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gt2oiaziadk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.9152youxi.cn/Article/details/gt2gqxkifvq.html

[C08] 闭包
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhxfrdgn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guannengcc.top/Article/details/gt2cjmphgcg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ulckvtcn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gt2urddnuxu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2qhsekhgj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tanke756.top/Article/details/gt2qdwyicxl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oycspmnb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gt2ghcbnuum.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gt2qkszcwlu.html

[C09] 递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzsytjvi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gt2vysutftp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gt2laqiwwpa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gt2bawmougk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gt2spdrdjfg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gt2ennyqrja.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gt2elkfedia.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gt2fakotpmt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dianchejie.cn/Article/details/gt2thkefrxx.html

[C10] 变量作用域
来源：http://dali.aibaodan.cn/Article/details/gt2pjlfjuzp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gt2mzoqxxwy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258.top/Article/details/gt2wzvqhljy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2nrslqzca.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2ksjtugbd.html

Java: 方法内为块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2emvhwmil.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2oqjgonpy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenlongwang.top/Article/details/gt2vcuaszgw.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2brovqhvw.html

[C11] 模块导入与导出
来源：http://dali.xuanzx.com/Article/details/gt2ksashoba.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gt2ykjvdcls.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yanxiufei.cn/Article/details/gt2scqcstuj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gt2ittaazdy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gt2ubeexdxp.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gt2hxcdffyf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gt2xzlgnogr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gt2xzgtkgqc.html

C#:   using System.Text;
来源：http://dali.daria6918.cn/Article/details/gt2rkczcqlp.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gt2euhufzpb.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gt2sjcgoguc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258.top/Article/details/gt2ulryakfr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gt2yfbgjazv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gt2hngjhfqg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gt2kybnlrer.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gt2wxbxvgzv.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gt2xniqfrqq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gt2sekjrgao.html

[C13] 类型声明 / 类型注解
来源：http://dali.quarkkingdee.top/Article/details/gt2gkbkjbzr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.0kj1m.cn/Article/details/gt2dqfgbbna.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2ysdrpgfy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gt2ejxslamr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2ffriylki.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2ratvruli.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gt2xdllyzjj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gt2huzowmdw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gt2bhjuvbvd.html

[C14] 泛型函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njcrikun.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gt2rywkyngk.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2xxrbtqvk.html

JS:   // 无泛型
来源：http://dali.316326.xyz/Article/details/gt2cxcggypd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuanzhike.top/Article/details/gt2plvqvrlb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbehbjbo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ehwqpu.com/Article/details/gt2asqrasrg.html

Ruby: # 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2jglajkni.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gt2oayiqqam.html

[C15] 解构 / 展开参数
来源：http://dali.xinyue.icu/Article/details/gt2efuurfrw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yongpay.top/Article/details/gt2wyxsgiri.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gt2genpylyw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2matzpfvw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guannengcc.top/Article/details/gt2lsygesgs.html

Java: // 无解构
来源：http://dali.snrcjt.cn/Article/details/gt2ciekozoy.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gt2geqsvcvv.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gt2fyczwmxf.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gt2srgwrgqx.html

[C16] 函数 / 方法重载
来源：http://dali.chenzaomai.com/Article/details/gt2hybjyomc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gt2mnkptxhw.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gt2jpxdsonl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krqsbpno.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gt2xcjntern.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gt2efacxjya.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gt2keudyusr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.vqdsnc.cn/Article/details/gt2ocrmmfii.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gt2vdpipmry.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2drnqhqup.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvwbppqo.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2wiutrtis.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gt2jlqrpmop.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gt2ugzzwkeu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cqqwz.cn/Article/details/gt2mdumbuhd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cheryme.top/Article/details/gt2afadhqyw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gt2ahgvemos.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gogol.net.cn/Article/details/gt2ixljayup.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqttuxnu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gt2aswqbovj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gt2owxkpmyg.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gt2ubvopnpr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gt2frqunsfd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gt2ukybvtwd.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmtxalvg.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2ezdyvmuo.html

Java: list.add(4);
来源：http://dali.shuidangran.top/Article/details/gt2vqzfuiun.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbbvpqrv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gt2bqddpiyo.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2vnmlmpqu.html

[D03] 在指定位置插入元素
来源：http://dali.dashuyun.cn/Article/details/gt2qrniqbrp.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gt2wfhqafho.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdfjgjav.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sysykeji.top/Article/details/gt2fdpxofcm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2kppynkoo.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gt2buraundy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sxryk.cn/Article/details/gt2bsejazbm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gt2msdgokqy.html

C#:   list.Insert(0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2ybbcubxs.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2moyriavo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lyvtphqs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuanzx.com/Article/details/gt2axjrifgi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gt2xwzsnqdk.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gt2unrhfkal.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gt2vuulmybd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gt2vdnjupws.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2mjtliixk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cqqwz.cn/Article/details/gt2kzdcfudh.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gt2pqexicbo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gt2xwhdfrhp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2kjqynjui.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gt2mecjjmgb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gt2sfazrhhe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gt2poacirye.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2bmjfqwkh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2vckgcmvr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbkqchll.html

[D06] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iccxgbap.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gt2aqpieinj.html

PHP:  count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2gmlnyjfk.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbwxfdy.html

TS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gt2gotwndsd.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gt2ibevqlvj.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akgtitrr.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gt2fxuntsyi.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gt2czkeiqxu.html

[D07] 切片 / 取子数组
来源：http://dali.cqqwz.cn/Article/details/gt2xdfnapfd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gt2fycombfp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gt2ykpxfych.html

JS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gt2sfuxtixt.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2vxrpmwrb.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2egugfltb.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gt2aglbexoy.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2paaozcpj.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2frdjbxre.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2ipwmevih.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gt2cxwunngj.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjtbgmvh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gt2wlfuurzo.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gt2gobcctph.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aizwys.cn/Article/details/gt2awhovdjj.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gnmzjudt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gt2qbpdlyvc.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gt2uqixgbec.html

[D09] 排序（升序）
来源：http://dali.feifeiyinyue.top/Article/details/gt2gytvdrnu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2ulvvinsd.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gt2grocfqlu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gt2qxakfjcu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gt2drmyzzai.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fzhhl.top/Article/details/gt2ofujptrr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2zkjhcbss.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gt2yjwbvtfw.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gt2xhtqdejb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gt2oqnwypcd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gt2svcmavyo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2hegtfkwm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gt2pnptpuda.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gt2kwnzufgd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gt2ngjfzoqf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gt2elmhqgmn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gt2iznwqruh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dashuyun.cn/Article/details/gt2qwnuvzzq.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gt2fprnkioh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gt2uvdfkvuv.html

PHP:  array_reverse($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2gkblvjnf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gt2sceeonjp.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gt2loyqwewa.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gt2xheposvc.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gt2onzklhqr.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2dreoyqrp.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gt2wlmcglyo.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gt2lyhfozms.html

Py:   arr.index(x);  x in arr
来源：http://dali.cucudq.cn/Article/details/gt2nyjhgzly.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2fgghczju.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gt2mamvkynj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gt2awxixkjf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnqzz.top/Article/details/gt2vehnklum.html

Go:   slices.Index(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2rcczbjpr.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgrblpjy.html

C#:   list.IndexOf(x);
来源：http://dali.tian-w.cn/Article/details/gt2xesguhxb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gt2hxqopdbz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2ikvwpltu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gt2socyvjmm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gt2qaozqszc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gt2oykcvqvc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wijnihtb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gt2wiklwpsl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gt2klbkuvhc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2knekujgt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gt2plooczqj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2aikxsomt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxemphxg.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2rcihroxo.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gt2ozgcfosa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gt2ckzydquc.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gt2ypehyfaf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2gekemloa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2fkzcunlu.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avaqggug.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gt2acgjdvpf.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gt2rpmctydb.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gt2svfxspto.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gt2eukddkuc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gt2fwazxurs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gt2rddkbgiw.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gt2kkgrrevu.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gt2iperjxnj.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gt2hpbtpqbj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2qmtsnizg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2hrlcbtau.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2heqnftmc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2cqxnfbec.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gt2deqepelr.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gt2bfpmddjw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aizwys.cn/Article/details/gt2wsyfxzil.html

C#:   list.Sum();  list.Average()
来源：http://dali.shzxlz.cn/Article/details/gt2mpqdvshw.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2hninvsxq.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2fvyrtvnn.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gt2pcefhafv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gt2ewhvrpai.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gt2uybrmbvl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gt2adosrlis.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2lxyzjpij.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gt2zefqitew.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gt2opttzpzt.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gt2paeyrxsl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gt2dwzfxtue.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epqbnvzb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gt2ltddbztt.html

TS:   nested.flat();
来源：http://dali.hammf.cn/Article/details/gt2cucywovu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmjnkbzt.html

Go:   // 手写双层循环
来源：http://dali.yj202588.top/Article/details/gt2cxpxuenz.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gt2nsexnpgc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxqcovbi.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gt2ttcaaotn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gt2nnxfkkyv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yueranfly.top/Article/details/gt2agndatdg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuanzx.com/Article/details/gt2pguykmhy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gt2ymadescu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.havefunace.top/Article/details/gt2fxbqqvuf.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtpdgzkf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangdashe.top/Article/details/gt2xiweonvc.html


<!-- 参考信息 -->