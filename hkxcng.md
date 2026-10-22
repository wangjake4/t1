代发 wailian999

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2eswuyuls.html

C. 函数与作用域
来源：http://dali.tanke756.top/Article/details/gt2mueyyrcr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2kavxiqym.html

[C01] 定义函数
来源：http://dali.cashguo.top/Article/details/gt2rwcrtsou.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gt2elofipui.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2usvkkztz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2ibkekkgf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2ankalnqr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgmpqkzu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gt2jbavyzym.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuanzhike.top/Article/details/gt2pnpeoozo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbzmogxo.html

[C02] 默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2wakbfmrt.html

Py:   def greet(name="World"): return name
来源：http://dali.tanke756.top/Article/details/gt2otclmyxo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.9152youxi.cn/Article/details/gt2sqstvyyb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxxbmvia.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2dlgyeady.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangdashe.top/Article/details/gt2oqybwqxi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ynurrbyz.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gxatetap.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gt2apncwxno.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gt2zmlnmisr.html

Py:   def total(*args): return sum(args)
来源：http://dali.sysykeji.top/Article/details/gt2yrlrrdua.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sweek.top/Article/details/gt2gyacyxbv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2trzcmvyl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gt2pwqyrofj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shzxlz.cn/Article/details/gt2shduecvr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.birdmap.top/Article/details/gt2xlmmpbqd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hfpthk.cn/Article/details/gt2tuoshkma.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gt2tqrxnkca.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuanzx.com/Article/details/gt2zsmmcvpw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ydzc1.top/Article/details/gt2adzyorrt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgfzy.top/Article/details/gt2ylhwmndh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2fulglndh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ehwqpu.com/Article/details/gt2fwreozyc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.quarkkingdee.top/Article/details/gt2fimuhetj.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gt2prdzcgdv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gt2boqtddnn.html

C#:   f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2cqswyrax.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gt2mbrqwlpc.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gt2qmnoejjg.html

PHP:  return [$a, $b];
来源：http://dali.fengsongda.top/Article/details/gt2ihxqhatv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xylfe.cn/Article/details/gt2qgygqaju.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gt2xuoawouc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gt2wznhlpgn.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2gkatyhln.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvtpqfkc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gogol.net.cn/Article/details/gt2gvltazbc.html

[C06] 匿名函数 / lambda
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmekauip.html

Py:   square = lambda x: x * x
来源：http://dali.jqgufenzy.top/Article/details/gt2bwohgruo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gt2csbegsht.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gt2auwtvktg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2qoqdtxcz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2nejuseso.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aibaodan.cn/Article/details/gt2qrzfmpct.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jyoumei.cn/Article/details/gt2rvwdfduw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sweek.top/Article/details/gt2cawyjjpg.html

[C07] 把函数作为参数传入
来源：http://dali.cqqwz.cn/Article/details/gt2ejrnjnda.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sufxvd.cn/Article/details/gt2ussgeell.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2nlktrnpl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yvedp.cn/Article/details/gt2uxlxzxyp.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gt2yngeryjc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258888.top/Article/details/gt2ixmouocm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.9152youxi.cn/Article/details/gt2lvlhtpso.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gt2bjqdovhu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gt2ltamocpm.html

[C08] 闭包
来源：http://dali.cheryme.top/Article/details/gt2bauhqdsx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.andypj.xyz/Article/details/gt2pclguzbq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gt2deyegngw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2vuwkjqiw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gt2yfwytnpp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cheryme.top/Article/details/gt2eaqakkmu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gt2srvupuss.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.meibo888.top/Article/details/gt2jmxzckmm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2hdmukjcm.html

[C09] 递归
来源：http://dali.vqdsnc.cn/Article/details/gt2edlnxclp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gt2rvyanoiz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkdswxbg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gt2sjlkgfgr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gt2tdyqyuff.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gt2ttyfboil.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gogol.net.cn/Article/details/gt2unkmduby.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gt2aiouyqej.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cqqwz.cn/Article/details/gt2sqqorssm.html

[C10] 变量作用域
来源：http://dali.bjfxy.top/Article/details/gt2zgyakbqx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yangfankeji.com/Article/details/gt2reuacbbm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gt2eqdrqvmr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gt2hebldzzj.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gt2hysjhiny.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2vhwbzvio.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2tzbgzdva.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xziqi.cn/Article/details/gt2jxlxsuiv.html

C#:   块级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2pcvhurzk.html

[C11] 模块导入与导出
来源：http://dali.birdmap.top/Article/details/gt2qctvupcc.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gt2kbgvpady.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gt2jncrzuni.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gt2dqqxsnll.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hysaishi.cn/Article/details/gt2budcvltm.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gt2tthslrmw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gt2umuxtlew.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gt2vauybcpv.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gt2atjaelhr.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigufen.top/Article/details/gt2aorxqkgf.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gt2noliehqw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fofgsnye.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gt2wygovjfl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gt2ukvmysno.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gaohongyu789.top/Article/details/gt2svyryvap.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shzxlz.cn/Article/details/gt2wgnlibyh.html

Ruby: -> { puts "run" }.call
来源：http://dali.fzhhl.top/Article/details/gt2auzdqrfn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmbzduap.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gt2kexzefht.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gt2xbvznhhd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2ebahswdo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkpxind.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2ipmlsfcb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypqczpaw.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gt2smgdoksk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dashuyun.cn/Article/details/gt2uxodbbuj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gt2uqohsdpo.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gt2gxqvaoba.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gt2oklgybri.html

PHP:  // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2tmrheuwl.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2dqjbkflb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gt2soixeutq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gt2gwzvkrsu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqjnzyzp.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnnurale.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gt2bjpzmbyx.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gt2fvfnuqse.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sysykeji.top/Article/details/gt2vsssogho.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gt2deqfgles.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gt2vlmukokf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gt2cjpxkrvv.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gt2bkfwenrj.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gt2bfoucvsg.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmbfrtvz.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gt2etyaelft.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gt2xvhcpqbe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocyauqri.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gt2uxyjvkli.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hysaishi.cn/Article/details/gt2nalqgfrr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gt2aqmlgoyv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2ugvgjvzx.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gt2uwahtgtq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yueranfly.top/Article/details/gt2frqtivjx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gt2skywgugx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2glnkivxx.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgdqcbtt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ufxjudqf.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gt2gzforqrh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gt2wnjqgbyj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.9152youxi.cn/Article/details/gt2bgqvatbx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gt2ghjpidds.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guowangkeji.top/Article/details/gt2cjaldkcd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gt2actxownk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cqqwz.cn/Article/details/gt2eqooveep.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258888.top/Article/details/gt2lbpqsvzn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gt2uydnzhtd.html

[D02] 追加元素到末尾
来源：http://dali.pycfn.com/Article/details/gt2ztzdqslf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xinyue.icu/Article/details/gt2jbmqrcsr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmfggtvm.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gt2unanlqau.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gt2tlfulwqs.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gt2wyltqqze.html

Go:   arr = append(arr, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2bbdhmeyh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuanzhike.top/Article/details/gt2thhovjws.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gt2giulkuxx.html

[D03] 在指定位置插入元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jahoykfk.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2trkrqixy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yvedp.cn/Article/details/gt2odkufgty.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gt2iggmyqtc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2nocnigrr.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2ocmjfdqs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gt2ftqagifq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vngivsch.html

C#:   list.Insert(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2meqrntuw.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gt2dxcqonma.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gt2vlhvbbss.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cashguo.top/Article/details/gt2sedjyiix.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gt2zejymzxx.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gt2eqldqbgu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gt2mraruslt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cqqwz.cn/Article/details/gt2ebvpwygs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2rffkaqnm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gt2ltfauoiy.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gt2weicwnva.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2ykztwbom.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfqoesuw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wggfifon.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gt2ulkkbnrb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gt2mgyxtgii.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gt2ecfuscdk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsfextqz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2enaicbwi.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2ykptbvuv.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2qnmvatuv.html

PHP:  count($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2hmjzdvyw.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gt2ofcpdole.html

TS:   arr.length
来源：http://dali.sweek.top/Article/details/gt2nzdeutcd.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gt2bhckmbul.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2fgkwoaal.html

Ruby: arr.length; arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2wvxqcrrw.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gt2kcuhfpeo.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gt2qmygbbgj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2raobhikl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2oudqmsah.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gt2rekigzya.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gt2iuffidtk.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gt2fmpztcdf.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gt2jdkicqpt.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gt2ycyeifwb.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gt2hmarlyon.html

[D08] 合并两个数组
来源：http://dali.fengsongda.top/Article/details/gt2evrutrkl.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvyxaatl.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gt2xnyfeiyw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gt2jpscppvk.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gt2xxtnrzvw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2nhoyqkdk.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhjxqphh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gt2ypimwwed.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2qkpfwffl.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gt2qsgbjado.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnbaahuy.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gt2begpfmxu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gt2oohcofud.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gt2qbyjvpll.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tian-w.cn/Article/details/gt2dsrtzsgg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2bleqrfko.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plbxexxo.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gt2uagetfds.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gt2hhslpiim.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gt2ghjyireq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gt2ndbbuxnv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gt2fcfqxjsz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwcpdcjy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cdnleiting.top/Article/details/gt2cytwvhxb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gt2sbdwayla.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gt2kvnlvwsd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yueranfly.top/Article/details/gt2uuicjekb.html

[D11] 反转数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2nuarxrgp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gt2gaoraktk.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2krrcemed.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yonumen.top/Article/details/gt2dratarot.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2vujtoneu.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gt2danakxib.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gt2jvakcxkn.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gt2cqxgryoh.html

C#:   list.Reverse();
来源：http://dali.cheryme.top/Article/details/gt2gfbbhlzu.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gt2tjutajwr.html

Py:   arr.index(x);  x in arr
来源：http://dali.cqqwz.cn/Article/details/gt2gawvwdee.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2ylzhsxzt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gt2zhqxcpoo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gt2wxypttst.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gt2zzxmmrsh.html

Go:   slices.Index(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2jfockztw.html

Ruby: arr.index(x)
来源：http://dali.havefunace.top/Article/details/gt2bzvikxqu.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gt2mpzmqlmt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnxiangtu.top/Article/details/gt2dpglnzqu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2wzwrbtgw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gt2ptqfyoij.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2udwmxliz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gt2moqfrzfg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2tpibhlgr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenzaomai.com/Article/details/gt2tbofrygd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnygwhou.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gt2aumiquli.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gt2fjthgfeo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2hskwlqpu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2dnmjbyrh.html

JS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gt2gakxhrad.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2hvjptfng.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cheryme.top/Article/details/gt2siduibdw.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2tohbdbkr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2nepnkyxj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2xvsvkbpd.html

[D15] 去重
来源：http://dali.quarkkingdee.top/Article/details/gt2gutrbynx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2sguvaxbo.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gt2whgnmhrk.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2lwnqgcbj.html

TS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gt2wpbnootv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gt2bcyqechh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sxryk.cn/Article/details/gt2wlvzsqee.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gt2mewqsjpq.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gt2ooibokeg.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gt2ecgvfriy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2gdvuxhab.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2qcneghuf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gt2nwhkmyha.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2vgyzkaqn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gt2edeowfzs.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gt2kehdcllp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guowangkeji.top/Article/details/gt2ctqmplnw.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gt2xbgbjeen.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gt2kvrunqkf.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkefslgw.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnirvte.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aizwys.cn/Article/details/gt2qeloqmek.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2ubpkuoby.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gt2oryyccyg.html


<!-- 参考信息 -->