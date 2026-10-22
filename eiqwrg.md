代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sufxvd.cn/Article/details/gt2cxyfybsg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cheryme.top/Article/details/gt2koqwvzth.html

[B15] 布尔运算与取反
来源：http://dali.zdqjudy.top/Article/details/gt2hedoskel.html

Py:   a and b or not c
来源：http://dali.gaohongyu789.top/Article/details/gt2myvdmalu.html

PHP:  $a && $b || !$c
来源：http://dali.cheryme.top/Article/details/gt2qvvnzthr.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2wwvcneei.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2hqxgmdum.html

Java: a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2zdfjoqsd.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2qwvcdzhx.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2jmntmrpm.html

C#:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2wwasuvxb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cucudq.cn/Article/details/gt2bwxijjpm.html

Py:   if not data: return
来源：http://dali.sxryk.cn/Article/details/gt2jnpeygcf.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtvbkapu.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gt2xanbxeix.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gt2drdohiim.html

Java: if (data == null) return;
来源：http://dali.gzhubu.top/Article/details/gt2dhqcgngs.html

Go:   if data == nil { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2quztgzwy.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gt2brqhwjlb.html

C#:   if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2esneqekr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wtoxjbaz.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gt2alheciny.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2exfevmqt.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gt2afqufmqq.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gt2uuldfgos.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvlpscfr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzteafel.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2zhmfdcap.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2cicnxrns.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangdashe.top/Article/details/gt2iakftmke.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gt2lhmtzxpw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2xxpelduo.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gt2wwbuzpqg.html

Py:   def greet(name="World"): return name
来源：http://dali.aizwys.cn/Article/details/gt2tiuanjia.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gt2jdvuxctv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yiqyykmg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bukxudzz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvrsdslt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.0kj1m.cn/Article/details/gt2vnuroctj.html

Ruby: def greet(name = "World") = name
来源：http://dali.shuidangran.top/Article/details/gt2dlcnyjse.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ppjwa.cn/Article/details/gt2ckyztitd.html

[C03] 可变参数
来源：http://dali.meibo888.top/Article/details/gt2pupzfcxt.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuxming.cn/Article/details/gt2sseyugcg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gt2howeoyjw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gt2jrwegyxm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gt2thilbrxz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yvedp.cn/Article/details/gt2uhjmtill.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pycfn.com/Article/details/gt2kpqjbrni.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gt2dzccilcj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gt2psnwsrsh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gt2ndyqcdap.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gt2udrxjxzh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gt2unixapxg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gt2vhaxdoyf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jlsjyb.cn/Article/details/gt2krzmeuzd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.redwolf501.top/Article/details/gt2npcerykd.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gt2ajmqixag.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gt2wfoyfmrk.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gt2yxvfazyt.html

[C05] 返回多个值
来源：http://dali.jinqigfzy.top/Article/details/gt2cpufdrev.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gt2ivxihaec.html

PHP:  return [$a, $b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrmtrdfm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gt2kcegzhbb.html

TS:   return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gt2dftfukmm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tian-w.cn/Article/details/gt2glwotokx.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gt2wraqolzu.html

Ruby: return a, b
来源：http://dali.ivvv.top/Article/details/gt2uzwmmupn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gt2ywgpgphl.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntgvgksu.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gt2fnsrtgxm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xinyue.icu/Article/details/gt2knxdpmsb.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2erkhvkbb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2leeikgqk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gt2ymjjfzic.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gt2kfxewaam.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sikmktnh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2kzmuucbt.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gt2kvdkfxqm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daria6918.cn/Article/details/gt2jlnyfpuc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2aykkyyrr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhengqikj.top/Article/details/gt2xpxydpku.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gt2sooildfs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebbldfvb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ehwqpu.com/Article/details/gt2qffazhpt.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gt2mntgpbpj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jiagoushi.top/Article/details/gt2atqkqphu.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gt2bgunymov.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gogol.net.cn/Article/details/gt2hoddqfdv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gt2glyilgee.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gt2rcmtifbf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2oxmfmkth.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gt2ybberjqu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jiagoushi.top/Article/details/gt2pejzjzrg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gt2sxrwhjmj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2geommans.html

[C09] 递归
来源：http://dali.andypj.xyz/Article/details/gt2sfkdqmbq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gt2krgrrozo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fzhhl.top/Article/details/gt2fhdoxqiw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gt2hqtyaxuw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gt2tjeqxykk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gt2ykguoijh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nwbrower.top/Article/details/gt2njanuezs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gt2oclgfikf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gogol.net.cn/Article/details/gt2vwxukgco.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gt2gvsakhgr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gt2ljlrndnq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gt2nuqjvfux.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.andypj.xyz/Article/details/gt2ollgualm.html

TS:   同 JS
来源：http://dali.shzxlz.cn/Article/details/gt2sdmgaayh.html

Java: 方法内为块级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2nngprsrd.html

Go:   花括号块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2vysubczs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gt2tjkrzinu.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2bfrfcwpl.html

[C11] 模块导入与导出
来源：http://dali.fzhhl.top/Article/details/gt2wigwgtpl.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gt2hotshngq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gt2jrkbvhcx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gt2rbsiqelr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gt2ddtybtly.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gt2rmduirwz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcafmfdg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tanke756.top/Article/details/gt2vxrehymc.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gt2sdwnujgk.html

[C12] 立即执行函数 IIFE
来源：http://dali.xziqi.cn/Article/details/gt2fnuhfznt.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydinbjwd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.redwolf501.top/Article/details/gt2qtsbzbpm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2oelnuxic.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gt2sducwxmo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangdashe.top/Article/details/gt2hyqevmtt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sxryk.cn/Article/details/gt2vhjfnurg.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxzfelwj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yvedp.cn/Article/details/gt2emahzypx.html

[C13] 类型声明 / 类型注解
来源：http://dali.zycfv.cn/Article/details/gt2vjtwbzov.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gt2gxxjrnle.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2vggtbxmi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gt2qxodbqjt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnruwaxc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdntmhmg.html

Go:   func add(a, b int) int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwamkhhy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvucvxyb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.birdmap.top/Article/details/gt2idiqahrb.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gt2uoqsnugq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gt2cnbnliwd.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2toeaiopi.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gt2woqfxyyk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2yieoqgwq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gt2iqzrgbcq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gt2giejfmlk.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpxtproz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gt2sdrkypbh.html

[C15] 解构 / 展开参数
来源：http://dali.fzhhl.top/Article/details/gt2mlzaihhe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2bohpthvv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgfzy.top/Article/details/gt2davuzlqp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gt2rqqkkcfc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2qgqyrykm.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2tiqehqke.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufpwjnhr.html

Ruby: a, b = pair
来源：http://dali.cucudq.cn/Article/details/gt2ujbdepwd.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gt2rscggpcw.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gt2gucpbouq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2rbnxkmoo.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gt2pspwyfpj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gt2xqjcsfgv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gt2nnlwdffg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aibaodan.cn/Article/details/gt2xxzvvtyr.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqoaojfb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnqzz.top/Article/details/gt2cjqwhoon.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iepaoabf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2lagbwhmq.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sewyxeoq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2acmnnkdj.html

[D01] 创建数组 / 列表
来源：http://dali.birdmap.top/Article/details/gt2dhggmxkh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gt2gljxtnwr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gt2btkolkvo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gt2yjsohuso.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkdkjack.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gt2ohajhtno.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gt2mwhswyrm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gt2vvrloxxq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gt2cmldirxg.html

[D02] 追加元素到末尾
来源：http://dali.xinyue.icu/Article/details/gt2qymqrioq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenlongwang.top/Article/details/gt2wmrukpni.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gt2qrwcmmuz.html

JS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2khczwusv.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gt2reicugqk.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gt2jgckncno.html

Go:   arr = append(arr, 4)
来源：http://dali.meibo888.top/Article/details/gt2dyydqknj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gt2fjypncrq.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gt2jjooogim.html

[D03] 在指定位置插入元素
来源：http://dali.svipenyu.cn/Article/details/gt2qkggsell.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2yrspzbbw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dianchejie.cn/Article/details/gt2pzjpotpg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.316326.xyz/Article/details/gt2gadygcak.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gt2oipuxafg.html

Java: list.add(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2hbobwbcf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gt2qpkhtmab.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gt2oimvcpof.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2wyppdqcg.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gt2zqdsbatd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sysykeji.top/Article/details/gt2ucaituep.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2fkxfsnrd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gt2scoitrzx.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gt2odrbhibr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gt2ncygmamq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.vqdsnc.cn/Article/details/gt2kcyyctut.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gt2imveaddw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gt2hnenfzsz.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gt2mtupyuya.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2clpegais.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gt2aiykfjds.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2fxblarle.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gt2ddrddedb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gt2lxyeldqy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2smnkhxoi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2qwoghnci.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2ctumsaet.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxkugwro.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbhytmbo.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gt2ygvlsatp.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gt2jdonyref.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gt2kniyfbkw.html

Java: list.size();
来源：http://dali.ybcxt.top/Article/details/gt2toztlcna.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2ewfvsidx.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2frojhetc.html

C#:   list.Count;
来源：http://dali.cheryme.top/Article/details/gt2uznpwfzg.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigfzy.top/Article/details/gt2ydwbhvhw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skwyiydw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2tisjouiq.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2vjqjmsrw.html

TS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gt2jtilfyxc.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2mypmgnhi.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gt2xjeddcpj.html

Ruby: arr[1, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gt2igvthinm.html

C#:   list.GetRange(1, 3);
来源：http://dali.havefunace.top/Article/details/gt2chnclfsj.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gt2dbmcgsek.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gt2rzobqvpo.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gt2tbkvdxjj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gt2dsyiqzfb.html

TS:   [...a, ...b];
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfzgmtjs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2ihwauubr.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gt2ppxmidtj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gt2rlwsrman.html

C#:   a.Concat(b).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2znucvqpg.html

[D09] 排序（升序）
来源：http://dali.sxryk.cn/Article/details/gt2pltubhnu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2iscswtnz.html

PHP:  sort($arr);
来源：http://dali.xinyue.icu/Article/details/gt2imxyulmh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gt2sucenpod.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2effbuusw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gt2dvqzbhvb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2fjolipvf.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gt2wbazavfe.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gt2uasyotba.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gt2rmmdbkxv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gt2lleopmbl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gt2cdlkvinn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gt2oernucob.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gt2yjlbwqql.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daxiang520.top/Article/details/gt2ttpvwnqx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gt2tkzduvdu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gt2dcblkvft.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2unhrgtok.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gt2irebnuet.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nsogwbqd.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2brmjhagp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gt2huzksobj.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gt2cwdcyqhw.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ocuquboi.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gt2lnojjgpf.html

Ruby: arr.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2baejrylj.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gt2obdwlvkv.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gt2awtoyrcn.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2nmpumlop.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gt2luffherv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2jsjcglqa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gt2jdbvgerb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gt2ujdmjgpt.html

Go:   slices.Index(arr, x)
来源：http://dali.sweek.top/Article/details/gt2mpkrcojy.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gt2djvitjos.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gt2bcsmtrdb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gt2roclsvbb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xinyue.icu/Article/details/gt2slgkxnpu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gt2zsemheug.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gt2ersswudw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvmzxhxr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ivvv.top/Article/details/gt2hymymxjf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgfzy.top/Article/details/gt2ilrouffu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gt2enrlzcre.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2rmbhhttk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gt2hothayqt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gt2kheljoql.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2uecvftcp.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gt2expmtchz.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gt2xzbxszmz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gt2bgbihwlj.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxwwsosf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daxiang520.top/Article/details/gt2wfotithl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2oxgevbii.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gt2bkfottvi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gt2pfwrvqvd.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2nssvalsb.html

JS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gt2chcqmukl.html


<!-- 参考信息 -->