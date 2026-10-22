代发 wailian999

[C02] 默认参数
来源：http://dali.ydzc1.top/Article/details/gt2khoqwvic.html

Py:   def greet(name="World"): return name
来源：http://dali.wangdashe.top/Article/details/gt2rbtdluft.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.redwolf501.top/Article/details/gt2menlrqsk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2zqnnsdtl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2xtxyxmta.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gt2enfepren.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pycfn.com/Article/details/gt2hcsxgdyk.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gt2awquyzqn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gt2yfrzjdgd.html

[C03] 可变参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rizvkkpy.html

Py:   def total(*args): return sum(args)
来源：http://dali.0kj1m.cn/Article/details/gt2knpvhdbv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pycfn.com/Article/details/gt2emfylqko.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gt2hwupmufi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwhzieay.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpqmubq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gt2vouxlqsn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gt2qhkkypsz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmidluo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gt2psgpclli.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigfzy.top/Article/details/gt2eiorfgcv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gt2iqeqrzjd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2fkosfhqz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gt2zghaeluh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.kuanghao11.cn/Article/details/gt2yjqbszqf.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgfzy.top/Article/details/gt2pxxsehec.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gt2luacertb.html

C#:   f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gt2xfaaluwn.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gt2brbaanfp.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2xovmaovs.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gt2fcleucgx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fengsongda.top/Article/details/gt2gzwccjli.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gt2ehyjyozl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gt2hdriowgl.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gt2eaugsmyv.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gt2fooymrob.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hfpthk.cn/Article/details/gt2rjmohkli.html

[C06] 匿名函数 / lambda
来源：http://dali.cheryme.top/Article/details/gt2fpssnzwi.html

Py:   square = lambda x: x * x
来源：http://dali.gzhubu.top/Article/details/gt2ygnkjgsu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cheryme.top/Article/details/gt2aeicnalw.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2sadkxfck.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gt2dibichgk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gt2hesbjztl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.havefunace.top/Article/details/gt2ihanfrnt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shzxlz.cn/Article/details/gt2xyuusdmz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqapaaaz.html

[C07] 把函数作为参数传入
来源：http://dali.xylfe.cn/Article/details/gt2ddyeredu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gt2wuzuhkzd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gt2rodgqceb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gt2zzsojbzq.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gt2aujfovwc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2terwqjco.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqytpedf.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuanzx.com/Article/details/gt2unjowvog.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gt2qshbmhag.html

[C08] 闭包
来源：http://dali.xuetiantiany.cn/Article/details/gt2iszjaqpk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgufenzy.top/Article/details/gt2mqsdcowl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2arnxbwyf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2txbcvozj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sohkihag.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdgmwvdh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cqqwz.cn/Article/details/gt2wwtnszga.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gt2uleiucud.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gt2jmnpmbbk.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gt2xmfpaeel.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2pecqchid.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gt2zuyyxawv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gt2qbjufmtv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gt2lhfxdctd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzlexskw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gt2aeacjcur.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gt2bxibcsrb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gt2jjiswhqm.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gt2najqfzwx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gt2iyavtwve.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gt2dbcynylw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2qizbiccg.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2ewngxyqf.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2farsagfk.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gt2hgnkwxwq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gt2bwuhkwty.html

C#:   块级作用域
来源：http://dali.ybcxt.top/Article/details/gt2glcnqclh.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gt2stbjdyyn.html

Py:   from module import func
来源：http://dali.zycfv.cn/Article/details/gt2hdplmsed.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gt2kusxnpuj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gt2bxtarioc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gt2uwehrngj.html

Java: import java.util.List;
来源：http://dali.jianghu66.top/Article/details/gt2ylgumszn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gt2fjcntpyy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gt2paittayg.html

C#:   using System.Text;
来源：http://dali.gotoacloud.top/Article/details/gt2aedpaecs.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwqhfjgq.html

Py:   (lambda: print("run"))()
来源：http://dali.ppjwa.cn/Article/details/gt2mzvjslqm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gt2ircnfdvn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gt2wfyoohvu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2zpcrcjxn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.meibo888.top/Article/details/gt2zfctifij.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.vqdsnc.cn/Article/details/gt2zbsxbkqy.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gt2nszrvkja.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gt2skdpeucr.html

[C13] 类型声明 / 类型注解
来源：http://dali.ehwqpu.com/Article/details/gt2muryjabr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxuanxn.top/Article/details/gt2jmfbfbcw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnqfdesh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gt2jflrcqng.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2oygcoskk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2crkaplud.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gt2uzengxbd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gt2hhaebjbm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gt2umhmjmnl.html

[C14] 泛型函数
来源：http://dali.yj202588.top/Article/details/gt2tcpoqxga.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gt2okvicywz.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gt2jnekyzua.html

JS:   // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrdvylib.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsadrgoy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gt2ncvvmugm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gt2ckzrsmyd.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2hfhrzeqo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sclmbjtk.html

[C15] 解构 / 展开参数
来源：http://dali.nwbrower.top/Article/details/gt2snzoodrp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenjidiqi.icu/Article/details/gt2sijrypsi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangdashe.top/Article/details/gt2dsorfght.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkqiesue.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2sbtnfwnt.html

Java: // 无解构
来源：http://dali.yj20258888.top/Article/details/gt2drnlzupg.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2cmtkccsf.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbkuacwi.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gt2krcpijxz.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gt2zygqjkhm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gt2bojkzcqh.html

PHP:  // 无重载
来源：http://dali.jyoumei.cn/Article/details/gt2xbqaitoa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nwbrower.top/Article/details/gt2pdjtzxat.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2utzsgyck.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2oqlrxtxx.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbjyjcnr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gt2stetxmxe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gt2tmwgczzq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2cjmqxsdb.html

D. 数组 / 列表 / 集合
来源：http://dali.ivvv.top/Article/details/gt2zkmoecne.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ecsdkdhz.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gt2eucswuok.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gt2jglmrnsk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gt2zsowgdul.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daria6918.cn/Article/details/gt2jrdrjaei.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gzhubu.top/Article/details/gt2zugecawp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aizwys.cn/Article/details/gt2clsaeheh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gt2rydtxloc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gt2ouimjbsx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gt2fkbmxaef.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilvytchc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gt2ybefgtwi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gt2sdcgwfwj.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gt2eetbhwim.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcigybfr.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gt2tygbjwqq.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gt2uhngkufy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gt2nonvkigx.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmflxork.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwsctmuh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2qwdgvrkr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yonumen.top/Article/details/gt2nxdnwvyu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gt2liuqskkt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2vsyeeils.html

Java: list.add(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2uxozprux.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhpyasyk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cucudq.cn/Article/details/gt2uglrkeem.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2esiejwzd.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gt2byqubdpl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gt2yydgcgae.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2uczhvyjx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.andypj.xyz/Article/details/gt2fajlrtfa.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gt2drvadetn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gt2payggaif.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cashguo.top/Article/details/gt2uhaxdazb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2cgyrvhux.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nyyittts.html

[D05] 访问与修改元素
来源：http://dali.chenzaomai.com/Article/details/gt2cikjjhor.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2urfzmiua.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2gampjwdo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gt2zsqqsvgz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.vqdsnc.cn/Article/details/gt2mynbxpng.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gt2bgmnzkai.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edqqtrxd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2zsbyzzkb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bamkzqnf.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2ymcrrfnu.html

Py:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gt2nozqujqb.html

PHP:  count($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2ctrsisza.html

JS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gt2rdmhkifd.html

TS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2wslxnzrf.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gt2wehnjfud.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gt2vtesocva.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2unynambv.html

C#:   list.Count;
来源：http://dali.zhongyouzk.top/Article/details/gt2mnyctmjh.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gt2epwtbfmq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guannengcc.top/Article/details/gt2lrlfccii.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gt2dbaoqnym.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwzrijqs.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gt2swbpthwm.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2yhhqlesb.html

Go:   arr[1:4]
来源：http://dali.xuetiantiany.cn/Article/details/gt2eusmfrza.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gt2ojyngfym.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2sibhctsb.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gt2tknyoqds.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gt2ziajtmhe.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gt2awmyekyt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jlsjyb.cn/Article/details/gt2hghjibkj.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gt2srljvwle.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nwbrower.top/Article/details/gt2kctgjaak.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gt2oabdcnnn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gt2pwilbzmf.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2ekaksezh.html

[D09] 排序（升序）
来源：http://dali.quarkkingdee.top/Article/details/gt2smvseliv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gt2rkggzicz.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vcodxonp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ppjwa.cn/Article/details/gt2hcltkuvs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxfvdqnp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.haohaochexian.top/Article/details/gt2fqfggeps.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gt2abffrrpe.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gt2rxcecaqv.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gt2hahmapuu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aizwys.cn/Article/details/gt2zsvofqyv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gt2azdjrstt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2zowaltnf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gt2pbigmijy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gt2bdqifjyk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gt2utevinsj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daxiang520.top/Article/details/gt2mpiotjpe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sxryk.cn/Article/details/gt2cswrlkpw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.feifeiyinyue.top/Article/details/gt2vafapeim.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2embybzcg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gt2sbnnrdcd.html

PHP:  array_reverse($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbamsnhk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tian-w.cn/Article/details/gt2cltrntlf.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvgbcho.html

Java: Collections.reverse(list);
来源：http://dali.c1oappe.top/Article/details/gt2toejqhlu.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gt2zewplxje.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2motqqkeu.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gt2pfcvpeif.html

[D12] 查找元素下标
来源：http://dali.dianchejie.cn/Article/details/gt2dvtemyqy.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2zhbcrrdw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gt2kjwqvqxv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gt2xxmzcqvb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gt2smwnwrfk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhengqikj.top/Article/details/gt2kjrudzfo.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2vcvgmhcv.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kteatcjo.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gt2bfxkhezi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gt2buifoxew.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gt2gtoymzxz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gt2kdpjiqye.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2fxujjldc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2mpteanou.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2guaubceq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gt2yekacmfv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gt2xilbjoyb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2akrdzvgu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.haohaochexian.top/Article/details/gt2uhyxssuh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gt2uyiqqgcl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fengsongda.top/Article/details/gt2mfwhjozz.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2hwbwtytd.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gt2axbrmxgr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sysykeji.top/Article/details/gt2hrnwrmzl.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2hckurbdd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2paektejb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2uvogaqex.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gt2vnjouxni.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gt2ckyumpjw.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gt2nydchmbf.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2fcecsrey.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2lqluqepk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gt2iqkysqib.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gt2kasjazlh.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2orwczwcq.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gt2vyfcyvnf.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gt2lbpmgbhj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2atgwjhwz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2rlwlfdht.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2bmrfnhmm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gt2pxgqjrni.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tianlin.xyz/Article/details/gt2mcsnuvaj.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gt2eelpnmbc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exnnndnz.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gt2qnkisnje.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gt2wsgfqotp.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2rkvsoaig.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gt2khzvqbre.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gt2lgaqgchn.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gt2ccedswtr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gt2ftewfqpb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gt2zxiyauwj.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gt2kawkjvas.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gt2qazspihf.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gt2iyutghgv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gt2ppsyanbr.html

PHP:  array_merge(...$nested);
来源：http://dali.tian-w.cn/Article/details/gt2ltdxqvzc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gt2izvclysm.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gt2zizeqpsb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gt2zddvggux.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gt2gtmneadx.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gt2dzoxsrlh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2ioygmsgf.html


<!-- 参考信息 -->