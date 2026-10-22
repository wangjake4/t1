代发 wailian999

Py:   if not data: return
来源：http://dali.zhongyouzk.top/Article/details/gt2kvrnjyey.html

PHP:  if (!$data) { return; }
来源：http://dali.316326.xyz/Article/details/gt2ssabkeqr.html

JS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gt2lhtotfjx.html

TS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gt2kpgdpgdd.html

Java: if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gt2isfhgkrr.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gt2beqhtuhz.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gt2iozopout.html

C#:   if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gt2jaldjmxv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ngqztglw.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gt2ziwbkggu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2bzaugnef.html

[C01] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gt2kicpyxws.html

Py:   def add(a, b): return a + b
来源：http://dali.redwolf501.top/Article/details/gt2jawiqyaw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hsnxsppm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2zituzbrt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yuthmsqc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2tqwslvpg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gt2qboculpa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gt2uedadulx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2zksuebgp.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gt2jjdtvegq.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gt2mxaixztd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btkhngpq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gt2vvvjwrgd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2btvudwbb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pycfn.com/Article/details/gt2uliwslrc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gt2orauomif.html

Ruby: def greet(name = "World") = name
来源：http://dali.yanxiufei.cn/Article/details/gt2sbzxwbar.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gt2yakznqel.html

[C03] 可变参数
来源：http://dali.shzxlz.cn/Article/details/gt2ssbgorai.html

Py:   def total(*args): return sum(args)
来源：http://dali.sweek.top/Article/details/gt2cuubdbhf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhtrvof.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2ycgfwnyg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gt2fhvgcfsc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gt2gyhwiuso.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gt2kvbiwgye.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gt2xaovtzhy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gt2jddbejso.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2aroauiwj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gt2vrpdrxpa.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gt2gfeucgoz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gt2cwiimkqi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gt2ehzqiigb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.redwolf501.top/Article/details/gt2ldnjobsi.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrbzsdky.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gt2uyqtsotg.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gt2blywtwpa.html

[C05] 返回多个值
来源：http://dali.quarkkingdee.top/Article/details/gt2niggywrd.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gt2fskeucbs.html

PHP:  return [$a, $b];
来源：http://dali.sufxvd.cn/Article/details/gt2cpafurnk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gt2ngwguwpc.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gt2luipfgry.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kiamuofl.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gt2bukimvlh.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gt2aevqfiwv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daria6918.cn/Article/details/gt2jidanvja.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gt2yyivrrdl.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gt2psdvszvh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.quarkkingdee.top/Article/details/gt2fwrktsjv.html

JS:   const square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2cyyokztp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2uowqwrbs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daria6918.cn/Article/details/gt2hnwrccif.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgvmldgt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sxryk.cn/Article/details/gt2ofgblqgq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2izyxohhc.html

[C07] 把函数作为参数传入
来源：http://dali.birdmap.top/Article/details/gt2eipxyngm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gt2grxbiker.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2bjwtewsv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yongpay.top/Article/details/gt2izikqmls.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gt2fstiiyho.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2iqbbeeuk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gt2pfruhtst.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gt2wuiieuui.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigufen.top/Article/details/gt2magskzgt.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gt2nptfwumx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gogol.net.cn/Article/details/gt2rordlfdd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbxicuxt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2hfcfzsbl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gt2rvsrcxmd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuanzhike.top/Article/details/gt2ysohdtlk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gt2rjwquaqu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gt2jxpqvlqf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gt2kxceeobb.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gt2pkdapbwr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gt2lnvrzimu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ivvv.top/Article/details/gt2wajhdwia.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gt2gpagulyi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gt2wqxladeu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gt2osxiydlw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gt2swnhhcmb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gt2dkcgfnrx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gt2glqjlupx.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2wlnayfjv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gt2pgbwyviw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldirpjfb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.mhx1999.top/Article/details/gt2zfdaletb.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zuhmxmku.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gt2cmkisybo.html

Go:   花括号块级作用域
来源：http://dali.ybcxt.top/Article/details/gt2muhosmbu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.meibo888.top/Article/details/gt2bcgbnxlh.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gt2zqaypeqg.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gt2iapxvtfl.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gt2trccvxek.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gt2bdcjarmq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gt2qarfqrxy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gt2pwpsgzzi.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jspqsqxa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gt2cacgwatp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gt2qtyiubfw.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gt2ksaexlpa.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gt2vacohqrg.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gt2pdwrdnnv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpbwmwpo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gt2qbpieoea.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gt2aseuwixu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfzikabe.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zycfv.cn/Article/details/gt2jqwpzapw.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gt2dibzdcmf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gt2xvpjipst.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gt2tdyaettf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shuidangran.top/Article/details/gt2sdojqnki.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2ffnxdbxp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gt2kiwrinqi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhyrdkji.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2oqmsyrqb.html

Go:   func add(a, b int) int
来源：http://dali.yj20258.top/Article/details/gt2sgbwgrjd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gt2cypidwec.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gt2pupvcqdp.html

[C14] 泛型函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2vgaimlkh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gt2ipnbvvuh.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifuyhiqr.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gt2vmetucpn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2epnmvugi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwmomrvz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigfzy.top/Article/details/gt2qhyqrjbl.html

Ruby: # 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2ylcumbxm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gt2sineujwn.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gt2jgykfcgx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gt2rohdoban.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cheryme.top/Article/details/gt2hfwlnudf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gt2icecfqut.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jaqmfsvb.html

Java: // 无解构
来源：http://dali.yj20258888.top/Article/details/gt2hrxeqvqp.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2evwfwrme.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gt2cuqmqvaw.html

C#:   var (a, b) = pair;
来源：http://dali.sxryk.cn/Article/details/gt2exdvvixq.html

[C16] 函数 / 方法重载
来源：http://dali.yangfankeji.com/Article/details/gt2hxtnbrje.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgfzy.top/Article/details/gt2peyzmubj.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gt2ocvufuda.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tanke756.top/Article/details/gt2kgrozblu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gt2ntkxlsll.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hazayknh.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gt2hcuukpap.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gt2pafjzsbt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2gpekucnx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2lujohnpo.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gt2knjbnchj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2jysvxylc.html

[D01] 创建数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gt2fzpsepde.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gt2tciljnft.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnqpyfkg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gt2ebxociwx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gt2artksimg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tian-w.cn/Article/details/gt2vqjlrvgt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gt2tkvypvok.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2qrzaitwq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gt2nauhjicp.html

[D02] 追加元素到末尾
来源：http://dali.yonumen.top/Article/details/gt2yozdyrje.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuanzx.com/Article/details/gt2qtevurmf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ehwqpu.com/Article/details/gt2oospsokz.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gt2emzerdmg.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gt2dhqqrkct.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcxvzlv.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gt2blvhljnm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dianchejie.cn/Article/details/gt2sflywveo.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gt2bbdfvfah.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gt2aalsmzvt.html

Py:   arr.insert(0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2mmhcedxo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sysykeji.top/Article/details/gt2nizmzuag.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gt2uwurkjca.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.redwolf501.top/Article/details/gt2lcdeihyo.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gt2umqyvqxg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gt2yqypvxsk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gt2fynchbia.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2nuvcocrz.html

[D04] 删除元素
来源：http://dali.birdmap.top/Article/details/gt2znnhgjlb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gt2mououzix.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2imnyhddd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj202588.top/Article/details/gt2zjqprnug.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gt2qesotcby.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gt2opzzxemq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gt2enozpfzj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.svipenyu.cn/Article/details/gt2tsmehkbd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigufen.top/Article/details/gt2cqstuzmk.html

[D05] 访问与修改元素
来源：http://dali.haohaochexian.top/Article/details/gt2ozxvicxw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gt2jbuvyhwu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2vjrlfaei.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2lgcqmbsl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dashuyun.cn/Article/details/gt2tcrquncz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gt2xelnnobg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2icjqvsjl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2veywaiat.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gt2wkvxyvny.html

[D06] 数组长度
来源：http://dali.fengsongda.top/Article/details/gt2cbitcujn.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2byxwesee.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2krwagbsr.html

JS:   arr.length
来源：http://dali.cheryme.top/Article/details/gt2cesegrad.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gt2nexdhirk.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gt2olokwuyu.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2idnihumj.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2gselykap.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gt2svqvzxjl.html

[D07] 切片 / 取子数组
来源：http://dali.smart0.xyz/Article/details/gt2epzmvblt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gt2fnxqiezp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cheryme.top/Article/details/gt2smynbihh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gt2drlzxxfv.html

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2yygxygam.html

Java: list.subList(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2oenvqyip.html

Go:   arr[1:4]
来源：http://dali.jianghu66.top/Article/details/gt2metylsib.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2raeymkno.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2ldfsxizr.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gt2bjdyfxun.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258888.top/Article/details/gt2qvpqxsur.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gt2swdmtvqw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gt2ozfnksna.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gt2kiiwyimi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2vypkgdqh.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gt2moizgxlo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gt2qrxzmcak.html

C#:   a.Concat(b).ToList()
来源：http://dali.meibo888.top/Article/details/gt2eghozuhd.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gt2hxwzxsif.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gt2sryjrype.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gt2quxotpbp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gt2fcnqphqj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfhbumpr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gt2tijcixvt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2ptgsfsvj.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmnuibac.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gt2pslswmgh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gt2mzgynrfk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gt2nyvvbmfn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfowyuth.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hobqzywv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gt2yhvzgpfn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ehwqpu.com/Article/details/gt2yagkypck.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sufxvd.cn/Article/details/gt2wrcmhpbg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gt2nncrnqpj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shuidangran.top/Article/details/gt2womrnyct.html

[D11] 反转数组
来源：http://dali.haohaochexian.top/Article/details/gt2cgyvuxhk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzfdztan.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhpnhgaj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gt2kyabvegl.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gt2wtlgzdsa.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2rlkykund.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgbqqtvk.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2jerafntb.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gt2yqzxfonp.html

[D12] 查找元素下标
来源：http://dali.yonumen.top/Article/details/gt2jwsupkoy.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gt2rwrbxuww.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cheryme.top/Article/details/gt2pusschhv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2eowqupxh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gt2kkntvsoh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gt2tboiawqq.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2rcgijeri.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2ltocaywd.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gt2yqwsfcai.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gt2elhfefng.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gt2pzkexiii.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gt2hidcchfk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2iygidkvq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aetypncg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2tusfocjd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258888.top/Article/details/gt2scwcdknp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gt2yomzsnfm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gt2rqnphrig.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gt2evzgcljj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gt2sycckhie.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2gfalmegd.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2czffhuzy.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2eshnuqmx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnqzz.top/Article/details/gt2sgcopdvf.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofsmyhxx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2gupzdrty.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbwfchek.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gt2bempdzba.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gt2ykvuvere.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2gupwkzhq.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2eoomyqcv.html

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2xhlquxto.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gt2tbhbavig.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xinyue.icu/Article/details/gt2guzkmguq.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgnbulit.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2hyafjdmr.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2heukjlpt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qqvqqyjh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gt2fmeoekoa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yyoltgoq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nudcmcfy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvzfotfq.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gt2aaykrbvj.html


<!-- 参考信息 -->