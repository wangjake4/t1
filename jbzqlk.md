代发 wailian999

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gt2vhdyskdi.html

Py:   def greet(name="World"): return name
来源：http://dali.yj202588.top/Article/details/gt2mtdxxjuc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daxiang520.top/Article/details/gt2cpvfwgim.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbckxwqd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gt2jnocymbm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gt2akomoplx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sxryk.cn/Article/details/gt2olvlauno.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gt2qxsajviw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gt2wwjwnldl.html

[C03] 可变参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvpovfbg.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gt2iqhcfrxv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xinyue.icu/Article/details/gt2xeidedpp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gt2avhgxbeh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gt2zzpgcsmq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2jsvnutmq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gt2zrkpefzi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxuwkysg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jiagoushi.top/Article/details/gt2xfeaxscb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gt2gboqrnqp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhengqikj.top/Article/details/gt2dppecavt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gt2vhjdbivl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gt2ngeofecq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovcbknon.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gt2rngpiqrp.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gt2xgdavnas.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gt2sbhbviyj.html

C#:   f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gt2tgncjxcs.html

[C05] 返回多个值
来源：http://dali.yj20258888.top/Article/details/gt2bikmuhpf.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gt2rciytgac.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udjbazxf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gt2hvjkcubk.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egpcxdso.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gt2qhkhsdrq.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2uvyddrqt.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gt2mixujtev.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gt2kzhitizg.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gt2pbpjkegm.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gt2unfzsqkw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gt2umaodsor.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2oipidols.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2lpeveuya.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gt2ckaahyuh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gt2jvpxdmcr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.haohaochexian.top/Article/details/gt2iicpkrbq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2vbwahowc.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gt2sdfakxns.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gt2aqcxzwuu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfhkdnlc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gt2nnfelbrq.html

TS:   arr.map(String)
来源：http://dali.cqqwz.cn/Article/details/gt2yhuufwqg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzxggxvo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gt2jvrqnbtu.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgvapagc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2olyixnmi.html

[C08] 闭包
来源：http://dali.xuanzx.com/Article/details/gt2unbtavvj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuddpnj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sufxvd.cn/Article/details/gt2piaojwre.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gt2zvyqxfkq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2gshtzwxe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2anueexjl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigufen.top/Article/details/gt2zjpcphhb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcdlvqas.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2tcytzvvr.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gt2cafzrqsb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gt2etbfsbcx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.c1oappe.top/Article/details/gt2ndysittp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gt2zqtyseyy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gt2msslxddh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2johhrkth.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gt2obodhuxk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hsbemvdy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shuidangran.top/Article/details/gt2idbigosc.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gt2kwnxhvou.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gt2epnelimi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cucudq.cn/Article/details/gt2bbilbkdd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncqgqsah.html

TS:   同 JS
来源：http://dali.bjfxy.top/Article/details/gt2oncyjfbc.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gt2ydzvimsp.html

Go:   花括号块级作用域
来源：http://dali.cdnleiting.top/Article/details/gt2chirybgu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gogol.net.cn/Article/details/gt2kxgxqbhr.html

C#:   块级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2ojgdgjmd.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gt2fqwycubw.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gt2mhnstsqg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.c1oappe.top/Article/details/gt2klgfpaun.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gt2cnumpfvw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ydzc1.top/Article/details/gt2jisuphix.html

Java: import java.util.List;
来源：http://dali.dianchejie.cn/Article/details/gt2spghbovf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqqfksfp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gt2oqrffadq.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gt2tcwzxbfz.html

[C12] 立即执行函数 IIFE
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxruiuiq.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gt2fbbzafbv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoiibpf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gt2tvrntkwf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2bynngmke.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nwbrower.top/Article/details/gt2drcgaonm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gt2eqampryg.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gt2roarwlcu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2irsvmafw.html

[C13] 类型声明 / 类型注解
来源：http://dali.yanxiufei.cn/Article/details/gt2napwmfqx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gt2govffpqc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2bzdcsewb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.redwolf501.top/Article/details/gt2tggltzan.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2snkwuyad.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flbcfgff.html

Go:   func add(a, b int) int
来源：http://dali.jqgufenzy.top/Article/details/gt2lrfhfgni.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gt2dhwsrzcy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gt2nclymtgq.html

[C14] 泛型函数
来源：http://dali.guannengcc.top/Article/details/gt2gcnbtlpu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hammf.cn/Article/details/gt2obbguxyu.html

PHP:  // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gt2uekybwlc.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gt2sylrijdl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ydcimvkp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gt2pezwqfro.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gt2tpuhpcua.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjgjcsdh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gt2oavtikqd.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zuivtzsl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjsufiap.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gt2kaujnxja.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wsrdbrmj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2owptpzeh.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gt2swteprhu.html

Go:   // 无解构
来源：http://dali.jiagoushi.top/Article/details/gt2fgytzkxh.html

Ruby: a, b = pair
来源：http://dali.cashguo.top/Article/details/gt2vycxtyuw.html

C#:   var (a, b) = pair;
来源：http://dali.kuanghao11.cn/Article/details/gt2ositmxhw.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gt2tylqtkkf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gt2eppqibsb.html

PHP:  // 无重载
来源：http://dali.chenzaomai.com/Article/details/gt2seqecuav.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gt2upemlyuq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gotoacloud.top/Article/details/gt2naoizkdn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cqqwz.cn/Article/details/gt2brhqxpwa.html

Go:   // 无重载：用不同函数名
来源：http://dali.fzhhl.top/Article/details/gt2saizqipb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqnkbwwa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gt2oiqdjvka.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2etnlxyfa.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gt2pjvooyvn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2gtroihew.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gt2zesnvbyp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gt2gmhhvfzz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cqqwz.cn/Article/details/gt2dutekjgh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fiaeirlh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gt2bsarjnmg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuanzx.com/Article/details/gt2ecymfqef.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gt2escbktpx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gogol.net.cn/Article/details/gt2evriihqb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gt2zowdpijn.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gt2exuahdqo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gt2oclztsjk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gt2cbxurezz.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gt2yaleouiv.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gt2arwqurks.html

Java: list.add(4);
来源：http://dali.havefunace.top/Article/details/gt2yvppjjun.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gt2ktnphglm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hywenlv.cn/Article/details/gt2xtkxtmcp.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gt2jdoahepr.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gt2jwxffzdi.html

Py:   arr.insert(0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2cwgjhrfn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sufxvd.cn/Article/details/gt2rbzfpgcj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkzlznxr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmcevqqq.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykbsaktl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.kuanghao11.cn/Article/details/gt2huvjkqmi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gt2sizwrpfn.html

C#:   list.Insert(0, 0);
来源：http://dali.316326.xyz/Article/details/gt2urbftgji.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gt2hkohfppe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gt2nubfyfis.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2spopriqr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zemeafob.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gt2guroardk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fzhhl.top/Article/details/gt2wfrsirvh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxinkj.top/Article/details/gt2kbqtrnem.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxinkj.top/Article/details/gt2pziqfkjp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gt2cqsvmvrk.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gt2tamgbrws.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2mrrwrbjr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2ssdnddqf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vaeknbdo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gt2bppuxqbk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdhmbgro.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffdjpcew.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2lsqplida.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gt2kzvgzstq.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gt2lxpuobee.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2jnmrelxu.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2ljfngatl.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2feyldqat.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gt2vtlcvzhf.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gt2pilihoot.html

Go:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2pekwsopr.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gt2yjgqrxiu.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gt2jphqhlbi.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gt2wfoahhmp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yangfankeji.com/Article/details/gt2hyseeufi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fzhhl.top/Article/details/gt2haswxufs.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cevyghvx.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2xknesxcr.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2nuuqgcde.html

Go:   arr[1:4]
来源：http://dali.havefunace.top/Article/details/gt2ndjobmsi.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gt2zlswgqvy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkyutluc.html

[D08] 合并两个数组
来源：http://dali.shzxlz.cn/Article/details/gt2mkurkhlu.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2qcamaxgt.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gt2kobpwcew.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258888.top/Article/details/gt2euubzfhg.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gt2tipxodck.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2xbhtqxmo.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gt2wtdufhoz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cashguo.top/Article/details/gt2fteoqlny.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2hctwyivw.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gt2umjnwdpq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2fxnafytg.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2ykathmpt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aizwys.cn/Article/details/gt2dmzwbpoc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gt2wfxcqmqn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gt2gsmfgees.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gt2bupwytre.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2otycnmli.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uiklfqhk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gt2jgrueoiw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2umrmgimc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2nozynrea.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2ntdmwqkl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2vzdkvfey.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gt2jdwrygqn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gt2jaqiaulw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gt2hxvbnsmg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idyhvafv.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gt2ehiumios.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gt2mpmwxjjc.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bskkujpo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gt2esylqcpv.html

TS:   [...arr].reverse();
来源：http://dali.jinqigfzy.top/Article/details/gt2tzrhbxub.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2loqqofiw.html

Go:   slices.Reverse(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2tweuzjjv.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gt2gfcgfvlr.html

C#:   list.Reverse();
来源：http://dali.zhongyouzk.top/Article/details/gt2heovsrfu.html

[D12] 查找元素下标
来源：http://dali.gzhubu.top/Article/details/gt2hikmoiya.html

Py:   arr.index(x);  x in arr
来源：http://dali.dianchejie.cn/Article/details/gt2aecvynlk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2plzzjhvm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfnyynwv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2pmicvmoj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hglrtkkk.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2etbhcubh.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gt2uxqiufel.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gt2kgssgsau.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgfzy.top/Article/details/gt2ovakzrrk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrgzrvkd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmrlzhwl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2ltqyhubi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2izbiqmhn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gt2dybqnvnd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gt2jvtcgxrq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gt2kgzueqih.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2pcznpgfv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gt2tjqqbdfi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gt2xfthnslq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2mummcpfn.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2difbqrlx.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbsrierc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2xepsfbag.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gt2xvsfrzbx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2wbqsjwcp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kaufeyqf.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2qazlydal.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gt2ajvnmoqu.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gt2gdqyeehi.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gt2ylxjwsys.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gt2cdvcmfyb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gt2oyczrvzn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gt2fzozywnz.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gt2mykzaxls.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzioszev.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gt2keqwwbti.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2cphfnmbf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yueranfly.top/Article/details/gt2bovmbflh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gt2ylylnujv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gt2bkgbiiwr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gt2oblrugdi.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gt2fswhidap.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gt2xmlwsfmu.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gt2nymlvtfj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmwoqhf.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gt2pggxxbcd.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gt2oqzrhmew.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxcuisae.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gt2qcbhyjbl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gt2dltowqbj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gt2pwccgfvy.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gt2nmmgwsva.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndkhmygo.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gt2ghmgyhfy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybwloxad.html

PHP:  array_merge(...$nested);
来源：http://dali.gogol.net.cn/Article/details/gt2bozvtrnp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpldjpzr.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gt2zyfythet.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2eoikhpqd.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jaivdvfh.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gt2jiprsbxi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2enxaexfc.html


<!-- 参考信息 -->