代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmwmtpwq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2jxcczpud.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gt2wboweyao.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2zwllfzvr.html

[C02] 默认参数
来源：http://dali.yj20258888.top/Article/details/gt2uhthpzkc.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gt2aeezukzx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ybcxt.top/Article/details/gt2ldflnrcs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2uabgkhds.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jppkylml.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aibaodan.cn/Article/details/gt2imxthmty.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gt2ikauxxnq.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gt2rjhhsksz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zycfv.cn/Article/details/gt2mfymcfdo.html

[C03] 可变参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gbylvwmp.html

Py:   def total(*args): return sum(args)
来源：http://dali.xylfe.cn/Article/details/gt2pjrwkbmj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gt2haraehdo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gt2wkrwakkr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gt2kheozmmp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rnlztwiv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gt2gexzoyry.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.smart0.xyz/Article/details/gt2vlkzbslx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.vqdsnc.cn/Article/details/gt2yrllabzu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gt2ojnuihyf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gt2pbyudegv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zdqjudy.top/Article/details/gt2whjegqor.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gt2dpgasruw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dashuyun.cn/Article/details/gt2dgzwkyyg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gt2pkjinmml.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2kppqnhmo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2durcdfht.html

C#:   f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2jsfahtoj.html

[C05] 返回多个值
来源：http://dali.yonumen.top/Article/details/gt2nbqwbhpf.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gt2lqoqnqqg.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gt2vyfmoyoa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zytnpfyp.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gt2vbtnfzho.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj202588.top/Article/details/gt2nwtrxeqg.html

Go:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gt2cumjzimc.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gt2asbdazth.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gt2zgpuoykk.html

[C06] 匿名函数 / lambda
来源：http://dali.pycfn.com/Article/details/gt2kzcwpzgz.html

Py:   square = lambda x: x * x
来源：http://dali.wangdashe.top/Article/details/gt2qeqtawko.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gt2zipevflj.html

JS:   const square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gt2mipjpjng.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gt2faggqeqs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2fwwftqkj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gt2tdchsdco.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gt2husnepfh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gt2tiyfkllc.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gt2akkzixec.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gt2xvvuqjsz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gt2isohnbml.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gt2banrxlmo.html

TS:   arr.map(String)
来源：http://dali.sweek.top/Article/details/gt2vmdwwdwb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gt2zoyvtqfv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nwbrower.top/Article/details/gt2ghepdwph.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhqprxd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gogol.net.cn/Article/details/gt2dznitypu.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gt2qrqmeftt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gt2uahszwxt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dianchejie.cn/Article/details/gt2gnsxyxcz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2wtohqayi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sghiptuo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.316326.xyz/Article/details/gt2gdoajsbc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yanxiufei.cn/Article/details/gt2msvwbwbz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gt2jqfircdr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2rvtjkjrz.html

[C09] 递归
来源：http://dali.sufxvd.cn/Article/details/gt2mjyyvdln.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gt2jxpvivfz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vatidped.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gt2ojocnmrd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfllfgxa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gt2fjlcoahp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgbwhkfi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kagvtovh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2juojzoxa.html

[C10] 变量作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2aksymbjw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cqqwz.cn/Article/details/gt2nanuyrar.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gt2reqgmmkc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2gxegjdam.html

TS:   同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2yipgpbhm.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2kcznjtnq.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2oxgaetdr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gt2ynsunxfi.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2opworasf.html

[C11] 模块导入与导出
来源：http://dali.tian-w.cn/Article/details/gt2smwtfjtl.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ntsezaxv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cucudq.cn/Article/details/gt2yyyyares.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gt2hxxqdnwc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqvfarzd.html

Java: import java.util.List;
来源：http://dali.jinqigufen.top/Article/details/gt2nvkubcke.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gzhubu.top/Article/details/gt2ynungjul.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhxrmvlb.html

C#:   using System.Text;
来源：http://dali.quarkkingdee.top/Article/details/gt2jbeezewi.html

[C12] 立即执行函数 IIFE
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpoausyd.html

Py:   (lambda: print("run"))()
来源：http://dali.xinyue.icu/Article/details/gt2qclgcmjl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gt2psobqjzw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gt2xnyjsrrm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gt2rncnkrkw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fengsongda.top/Article/details/gt2kgtgizeq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gt2rrupxbom.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gt2jopwiwis.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shuidangran.top/Article/details/gt2obynvpma.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gt2snjoamvl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.haohaochexian.top/Article/details/gt2znzitbkv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2etyhcolq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gt2khuuowcx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2cugbkhiy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2oykyoryw.html

Go:   func add(a, b int) int
来源：http://dali.birdmap.top/Article/details/gt2agnppbeq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gt2qcgelayt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gt2bgnnsfij.html

[C14] 泛型函数
来源：http://dali.yanxiufei.cn/Article/details/gt2vdeebteh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shangyingyoupin.top/Article/details/gt2pzifnlkw.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2kylzvywz.html

JS:   // 无泛型
来源：http://dali.ivvv.top/Article/details/gt2lmnguxqi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gt2ztzoqsac.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gt2qrpoxstn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gt2sreqdzxy.html

Ruby: # 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqgsmumg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gt2qnhdtbjh.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gt2xskqswpl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.316326.xyz/Article/details/gt2unltrpjy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gt2wjkvubtj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2vgfpzecg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gt2jujtnyky.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gt2xyetztoo.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gt2xmjzzwiu.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krpzcqnj.html

C#:   var (a, b) = pair;
来源：http://dali.vqdsnc.cn/Article/details/gt2lkxwvhkt.html

[C16] 函数 / 方法重载
来源：http://dali.0kj1m.cn/Article/details/gt2ddsbtcxd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gt2mtybfoag.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gt2mdkgenzi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gt2wkdiovou.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gt2jagiyjtb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aibaodan.cn/Article/details/gt2dufobqxr.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gt2ojjeznpp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gt2jvvckxyz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gt2vwmrsirg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2yhaeluqt.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gt2euwqyxwx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ofuxifzg.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gt2hoxgnobi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gt2vnpvbpsl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gt2oqywpkxp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gt2epysfqoi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gt2kydsirzj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdalyufw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gt2enzitqpk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2dnbbsmwn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.quarkkingdee.top/Article/details/gt2qtlxjwzx.html

[D02] 追加元素到末尾
来源：http://dali.yuxming.cn/Article/details/gt2rfcupyod.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.smart0.xyz/Article/details/gt2zxarredb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gt2duxzkmup.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2tkrmjnju.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2emefgpba.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gt2atndesvh.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnnsjpdu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrhabfxn.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gt2yylrsszk.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdkokgue.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmspyofg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangdashe.top/Article/details/gt2fqihvzup.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gt2ncogvdsa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2yzreqfnq.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2ysckfjxa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2gytolfen.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gt2ujtnfhjf.html

C#:   list.Insert(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2qkpzxdgt.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gt2ublygcye.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gt2cnxtfxon.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2smahiltc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gt2qobsonmh.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gt2rgpsczvs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gt2tsjclgrd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gt2kekdfydd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ppjwa.cn/Article/details/gt2qvzcuwzy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gt2ptstpaok.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gt2gofjcbfd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2ntmmcxik.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2jtrqqjus.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gt2qtupcvnj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gt2jukqrcna.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgufenzy.top/Article/details/gt2rjdqfjnm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2cdfzdfgf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2xafjdqta.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2nbugweke.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gt2unbsjgdv.html

Py:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2pfxujfvf.html

PHP:  count($arr);
来源：http://dali.cheryme.top/Article/details/gt2qcxiahrc.html

JS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gt2vviioewt.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqsvpuwx.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gt2kyfjzixi.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2ubxprtcz.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gt2kvlcgaft.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gt2ppbhdsaz.html

[D07] 切片 / 取子数组
来源：http://dali.ehwqpu.com/Article/details/gt2urjolurs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gt2lgvoxgby.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2fpvzabmr.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gt2tivcdqme.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gt2qdfwxder.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yindyflv.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gt2kzsulzbq.html

Ruby: arr[1, 3]
来源：http://dali.havefunace.top/Article/details/gt2tuywvwto.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gt2yuafisyr.html

[D08] 合并两个数组
来源：http://dali.tianlin.xyz/Article/details/gt2ubjcfzpi.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfhqxaaz.html

PHP:  array_merge($a, $b);
来源：http://dali.yuanzhike.top/Article/details/gt2ajgkgqgf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gt2axvenuld.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gt2ymtfbuak.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gt2ypohkvys.html

Go:   append(a, b...)
来源：http://dali.chenlongwang.top/Article/details/gt2cgqhkvcz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2qsxerpki.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2nrxumgmp.html

[D09] 排序（升序）
来源：http://dali.ydzc1.top/Article/details/gt2wzvpugwp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gt2aybkxqoc.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2affrtjpc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tanke756.top/Article/details/gt2kgccnnbl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gt2xdlpqpkl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gt2wxrrkuhi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gt2gduzdbod.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gt2lytshpqg.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gt2ekhvsfcb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhoulong.xyz/Article/details/gt2aaukesbf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gt2vmedvoil.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gt2filzeehr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gt2uucmltox.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gt2paxrmgip.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gt2ogbcrrin.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icgjxfsn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gt2ipopdppt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gt2zokxkssx.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gt2yjwzccgi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gt2wuivwzro.html

PHP:  array_reverse($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xyakguhv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxuanxn.top/Article/details/gt2vqkpjpbv.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yggxqouo.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gt2bnkwcvaa.html

Go:   slices.Reverse(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2upfuxqhr.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gt2eailhhxe.html

C#:   list.Reverse();
来源：http://dali.bjfxy.top/Article/details/gt2tddtlptc.html

[D12] 查找元素下标
来源：http://dali.tianlin.xyz/Article/details/gt2srxiocja.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gt2gbjhdmvj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncoysxml.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2ocyrbwmi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gt2krfsrrkw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gt2cruplgxr.html

Go:   slices.Index(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2dgerbhfp.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gt2qhaxcbkt.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfrsktvh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gt2ybarrrdi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmzwqusl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gt2bgubktln.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2kqenldpn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gt2ynifznbj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2hgcrmldx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gt2ulwsweza.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gt2rfacdpyn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldfwoyrr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gt2karikqji.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gt2lrkhwadb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2astneixd.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2vdqqiazx.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gt2mfpetvqt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2pvdnqtwy.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2ulhbehno.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2xybztmcu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2pjffqzga.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gt2mkrdjbaj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2ihxcusld.html

PHP:  array_unique($arr);
来源：http://dali.fzhhl.top/Article/details/gt2vkmzqqme.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2httbtsgr.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gt2omgeszgb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gt2gugynzao.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gt2flzfbuma.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gt2onlnjkci.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gt2rbuhrzqw.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjptiacw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2tsvewuor.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2jvounehj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2odyopsex.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2gevjxawn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hofqably.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvmsnucm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gt2gksidwcf.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gt2gojzfhhg.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gt2scovmqjs.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2dcoteisl.html

PHP:  max($arr);  min($arr);
来源：http://dali.xylfe.cn/Article/details/gt2ybfalyqh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gt2eogqflir.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gt2tbwxvpma.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gt2sgedumac.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2mogtubyl.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gt2qfamqnsg.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258.top/Article/details/gt2yxnixtcz.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gt2iceqxdui.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gt2mczazdhd.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gt2bloclpyu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gt2adfmavpi.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gt2qbvvplju.html


<!-- 参考信息 -->