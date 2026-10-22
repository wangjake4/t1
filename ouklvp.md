代发 wailian999

[C02] 默认参数
来源：http://dali.chenlongwang.top/Article/details/gt2cxucutoo.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gt2nzfqgbyh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2twnjamth.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2ebsoqjqq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2iomfsqhr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gt2dnbgwlkw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gt2whrurxvs.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gt2tgawbhqf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gt2oztftltw.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gt2fvmxctxp.html

Py:   def total(*args): return sum(args)
来源：http://dali.cheryme.top/Article/details/gt2twyokzdr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cheryme.top/Article/details/gt2zpqamnbp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gt2garraefj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gt2kebshhod.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gt2cnwgfwvp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.quarkkingdee.top/Article/details/gt2tyywkflu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gt2wtmpzhdn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gt2lnsmcejk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsicahbp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.snrcjt.cn/Article/details/gt2hyjamleo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ybcxt.top/Article/details/gt2qkexroxr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gt2vqjbyjon.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gt2dveoucdh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jianghu66.top/Article/details/gt2mkofzrar.html

Go:   // 无：用配置结构体参数
来源：http://dali.snrcjt.cn/Article/details/gt2csdzkipt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2jnstmoik.html

C#:   f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gt2cbwnfdcg.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gt2crlkqegp.html

Py:   return a, b
来源：http://dali.daxiang520.top/Article/details/gt2daphcray.html

PHP:  return [$a, $b];
来源：http://dali.cucudq.cn/Article/details/gt2sesqxmsj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gt2supbsfiz.html

TS:   return { a, b };
来源：http://dali.gzhubu.top/Article/details/gt2vxaaoapj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.haohaochexian.top/Article/details/gt2idzaocnu.html

Go:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gt2xwbgpzzy.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gt2vygxdufw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hfpthk.cn/Article/details/gt2vknzxwbl.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gt2hshefjko.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gt2rzxnkoyb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.havefunace.top/Article/details/gt2kpfzcyov.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gt2mmfqcyeo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.c1oappe.top/Article/details/gt2rkqcymil.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2mvpulfno.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jlsjyb.cn/Article/details/gt2rhtagdch.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgufenzy.top/Article/details/gt2qbfluhot.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tsiiilov.html

[C07] 把函数作为参数传入
来源：http://dali.bjfxy.top/Article/details/gt2aisntshi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.snrcjt.cn/Article/details/gt2wtqljzxn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.meibo888.top/Article/details/gt2fjjcfpvd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigufen.top/Article/details/gt2pcymwzpn.html

TS:   arr.map(String)
来源：http://dali.cheryme.top/Article/details/gt2qmxvuike.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daxiang520.top/Article/details/gt2xjwujekt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nwbrower.top/Article/details/gt2uiwtxpfv.html

Ruby: arr.map(&:upcase)
来源：http://dali.andypj.xyz/Article/details/gt2aucomquk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gt2obxugsev.html

[C08] 闭包
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggyrrvct.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhlzfwym.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kkzceqjo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2jhzysrxs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gt2rwtkxhra.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.redwolf501.top/Article/details/gt2ojggpadh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gt2yuhlkqej.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cashguo.top/Article/details/gt2pmuclrgz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gt2dzppgqri.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dneeizch.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2yymjfrsf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tian-w.cn/Article/details/gt2erxavlku.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gt2skaygghk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gt2vmtuqtox.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gt2mvpebssl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gt2krxrkhgi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2exjedmgw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gt2dokjpjtv.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2xurzymvv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffjlldwt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gt2lcyxqizm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2ewnvyrrl.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gt2xkmmabep.html

Java: 方法内为块级作用域
来源：http://dali.tian-w.cn/Article/details/gt2qmmjnwol.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2pshqbsbx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gt2ltjvqdhc.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2bggsvsxf.html

[C11] 模块导入与导出
来源：http://dali.smart0.xyz/Article/details/gt2wfvwsfvv.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gt2ymuazhqp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daxiang520.top/Article/details/gt2ptrhphlq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gt2zshtqutk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gt2bcgphrlg.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gt2xkzcojhf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhiwuduotai.top/Article/details/gt2omrtixbl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zycfv.cn/Article/details/gt2dcpobcss.html

C#:   using System.Text;
来源：http://dali.zhoulong.xyz/Article/details/gt2qvncnrrw.html

[C12] 立即执行函数 IIFE
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpzrtbmb.html

Py:   (lambda: print("run"))()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phejntbs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gt2ybwmouog.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gt2unmunjwa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gt2zhfiamqk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gt2zuthwfib.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gt2rvxnzsrv.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gt2vtoooiag.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2kucbwdme.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gt2ouadxsej.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfquafqr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2tecrrwxg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gt2wxrnhmrn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2oqklncta.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2pyjwzblw.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gt2ssimqbkd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gt2rghxwrox.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gt2rqcipemp.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eclpduka.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gt2qhwrhiln.html

PHP:  // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gt2qbfeeeca.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2agpcvkiu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kndiqhty.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2vldxqvkt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bttaiqhr.html

Ruby: # 无泛型
来源：http://dali.dashuyun.cn/Article/details/gt2inbahdsh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yonumen.top/Article/details/gt2xmmagfpl.html

[C15] 解构 / 展开参数
来源：http://dali.ehwqpu.com/Article/details/gt2kvkwrcjv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gt2mfdeofue.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gt2kngekjdh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gt2cilorqsd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gt2kfluvyro.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gt2xohgigbp.html

Go:   // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gt2vpsprzyh.html

Ruby: a, b = pair
来源：http://dali.ydzc1.top/Article/details/gt2svnqyhmo.html

C#:   var (a, b) = pair;
来源：http://dali.cucudq.cn/Article/details/gt2jpcululm.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gt2yofvsxpj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.c1oappe.top/Article/details/gt2lgsvwxjz.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gt2oitvkzhj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gogol.net.cn/Article/details/gt2ezhbhojo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvvnlkmo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj202588.top/Article/details/gt2ymiapcif.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gt2ugxuadke.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gt2ourqnxyb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gt2huedlfdy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2dugcxdae.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gt2lfoldfhf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2srqubahw.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gt2ilcvxyff.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.smart0.xyz/Article/details/gt2vnimowoo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzukwyoz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2djutjekp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gt2pikfclvb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.birdmap.top/Article/details/gt2zvneezic.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dianchejie.cn/Article/details/gt2ixdwusti.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gt2ayaaqlyp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xylfe.cn/Article/details/gt2ydlpmtux.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gt2iqnznabv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzgayzr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2qhpzauda.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gt2dcykncsn.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxrxxkjz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfifewsa.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gt2qiqfkapf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigufen.top/Article/details/gt2zmoxmwgu.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gt2noilvdxn.html

[D03] 在指定位置插入元素
来源：http://dali.meibo888.top/Article/details/gt2vyabywwo.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2msobbmxk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tian-w.cn/Article/details/gt2bmmqabjq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sweek.top/Article/details/gt2oqdnittb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2zitzarxa.html

Java: list.add(0, 0);
来源：http://dali.cashguo.top/Article/details/gt2pgxtewcw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ppjwa.cn/Article/details/gt2uglbvouh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkwvclub.html

C#:   list.Insert(0, 0);
来源：http://dali.redwolf501.top/Article/details/gt2vvxabrdd.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrzdwwtu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnstqeho.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2qwmanjhv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gt2ahlcwxvb.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gt2laviisbl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cqqwz.cn/Article/details/gt2bkerszqm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vndilhhi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gt2wklrxnpj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ydzc1.top/Article/details/gt2winwnzvi.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gt2osgywjvx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmsazzve.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2lchhbyzm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2tkohskrq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gt2fztfoigk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yueranfly.top/Article/details/gt2qgmomjhq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2lcdunrln.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lymzoolp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2mcgovcbl.html

[D06] 数组长度
来源：http://dali.ivvv.top/Article/details/gt2quaedltj.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2nevxwkar.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2rudmyfcj.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gt2omfvubzn.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gt2arcwloan.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gt2vgkupwjb.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2pemlwsek.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gt2grnvehcl.html

C#:   list.Count;
来源：http://dali.yongpay.top/Article/details/gt2bwehcaxw.html

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gt2dcnylkua.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ksqklskp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.redwolf501.top/Article/details/gt2sfiqyscm.html

JS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gt2uuqxwscr.html

TS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2cxovvmms.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2qaduhcsl.html

Go:   arr[1:4]
来源：http://dali.ehwqpu.com/Article/details/gt2qbvygdwm.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gt2idlbgqka.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gt2mqpomier.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpgjgwsz.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dojtsyxo.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gt2bhrxstpt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hfpthk.cn/Article/details/gt2luztjcft.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gt2bxnzbijo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2ryhspsch.html

Go:   append(a, b...)
来源：http://dali.cucudq.cn/Article/details/gt2dhpemnaj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gt2rqyizihr.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvmzndko.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gt2lhrjezsh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmwcplej.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2fnmsanzh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnbigceu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daxiang520.top/Article/details/gt2fiunxjan.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gt2eleqglga.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2ujjqvrpd.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gt2gjkbpkym.html

C#:   list.Sort();
来源：http://dali.xziqi.cn/Article/details/gt2ehojffcp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgfzy.top/Article/details/gt2bkpvderc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gt2ffwuajcr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjdmwjye.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gt2yprkggwd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gt2uyhfgwuf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfcazmdr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gt2dkppsehp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gt2cyjapguy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gt2cgykdlma.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gt2rpbehprn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdbzszvt.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2vzogowen.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.redwolf501.top/Article/details/gt2gguokyhm.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gt2nbxqxylb.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gt2henofcfi.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gt2wtxvtkdc.html

Ruby: arr.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2arrpjexr.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gt2wmlpaonu.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gt2kqgqaesv.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gt2iuzzxlon.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2qexbihih.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gt2mreirmzl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gt2xmpfhkjm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wcdwkuby.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2mklcxfhu.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gt2bvfnzvaa.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gt2vwvgvtqd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gt2wqlzucqn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gt2smcfqlll.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gt2deuwpgtk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gt2wivgmbnr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gt2ksudjkvf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yonumen.top/Article/details/gt2yedocoan.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gt2qhbrhair.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qndtubyj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2arwzaaim.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gt2ipiwkqvy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2uwmxgzbs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2fnypwajy.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2ckhdlksf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2yfamqaly.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2miehgnuk.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqkjiher.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2qfhiosqv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gt2ckvukvgl.html

[D15] 去重
来源：http://dali.yj20258888.top/Article/details/gt2hlysyfhi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2nqvvakms.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2slzrksvn.html

JS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gt2olfrzvke.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmrqblwa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyffgyq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.andypj.xyz/Article/details/gt2fhbumntr.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gt2xcnaamvn.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oceufnwg.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gt2viarrega.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzgwcumj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gt2titelmkb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2tyopabhu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jfhvuaub.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gt2pdtumoxy.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gt2viyswhnq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnqhaowv.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gt2xtxxtvtg.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gt2jcdgvcft.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2aemldvlp.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2hnihxedl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yongpay.top/Article/details/gt2vcdkcxqe.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gt2kpokaopi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gt2lcydvddn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdeegqdr.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gt2alwfkuwu.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2xihpzwrv.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gt2mynokmru.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycualpea.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqiktyuk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gt2unaluqjt.html

TS:   nested.flat();
来源：http://dali.jianghu66.top/Article/details/gt2jhkaxlnd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfcczvip.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gt2axamhnnr.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpbnzcxb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gt2fjlpynex.html


<!-- 参考信息 -->