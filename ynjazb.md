代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybnbpava.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2iiqnuhux.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2inpluxya.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2ujnfpboe.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2vekfyama.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2rzanlapg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgufenzy.top/Article/details/gt2amgdvhej.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2ujmsygya.html

[C02] 默认参数
来源：http://dali.jlsjyb.cn/Article/details/gt2abpdnkqh.html

Py:   def greet(name="World"): return name
来源：http://dali.smart0.xyz/Article/details/gt2uyemamqt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gt2lsacfemq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2olthcjyi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gt2dwldozep.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.havefunace.top/Article/details/gt2pvwxlrcq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tianlin.xyz/Article/details/gt2xjzjuexl.html

Ruby: def greet(name = "World") = name
来源：http://dali.zdqjudy.top/Article/details/gt2qrkrdfhk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogabzkzm.html

[C03] 可变参数
来源：http://dali.zycfv.cn/Article/details/gt2lvaxxaoq.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gt2mputepaw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cdnleiting.top/Article/details/gt2sajvrxju.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gt2tfztjsqt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ongcclui.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmojshyd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okwvtgac.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gt2qvmroiza.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yongpay.top/Article/details/gt2dmotgsuj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yongpay.top/Article/details/gt2mcdrndxc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gt2xscjwprv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hysaishi.cn/Article/details/gt2cgwmnzte.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2dcwnrxnb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gt2mpalyetn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gt2vniekyei.html

Go:   // 无：用配置结构体参数
来源：http://dali.haohaochexian.top/Article/details/gt2ijtpkksn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2vshcljjp.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gt2wcusmdyf.html

[C05] 返回多个值
来源：http://dali.zhixingplan.top/Article/details/gt2wotwwyxg.html

Py:   return a, b
来源：http://dali.wangdashe.top/Article/details/gt2yxkdvnqh.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gt2umotrxww.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hammf.cn/Article/details/gt2simcwdbw.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gt2nuwaoczv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.smart0.xyz/Article/details/gt2fwhlqqll.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gt2whylgphx.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gt2ezzpnwos.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gt2mbkbzltc.html

[C06] 匿名函数 / lambda
来源：http://dali.cashguo.top/Article/details/gt2qgspgrvu.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjzyqmxa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gt2trqnqmde.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gt2evrqrrxu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2yhhsjzjt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2cntfijye.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gt2aiahyxsz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xziqi.cn/Article/details/gt2jpykyfdm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gt2ranxtmaw.html

[C07] 把函数作为参数传入
来源：http://dali.gotoacloud.top/Article/details/gt2nvvwbowl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gt2lntteyob.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2bvqolwti.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ivvv.top/Article/details/gt2dnogtaiv.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tituvlbj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2rrkwoixt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gt2hdpdblmi.html

Ruby: arr.map(&:upcase)
来源：http://dali.zdqjudy.top/Article/details/gt2muwopljo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjpsbwqh.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gt2ehftlsat.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.bjfxy.top/Article/details/gt2jysxykpc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hywenlv.cn/Article/details/gt2fudfksnw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkjxiyqz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gt2ytywnzpu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gt2twetnxfz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gt2gbjbcrrb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gt2ytocbnvh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gt2thpyvzfq.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gt2bdicwrpk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahncwhmv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gt2mhkmyybv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gt2jfguingt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gt2zvstulxj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhrtbdpq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gt2nenthlac.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2ybvikfbb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.smart0.xyz/Article/details/gt2hliitrbq.html

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqykwzyd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jiagoushi.top/Article/details/gt2yvqioibh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gt2hwyxwmfq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gt2btdmtyqg.html

TS:   同 JS
来源：http://dali.tian-w.cn/Article/details/gt2xpgdklam.html

Java: 方法内为块级作用域
来源：http://dali.yonumen.top/Article/details/gt2uxsmpzwo.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2tzjtiokf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gt2zerosnmg.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2gurcjjaw.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gt2qevihoru.html

Py:   from module import func
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyilyisx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gt2kofigsgq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gt2dhrlyqnc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vttcjmho.html

Java: import java.util.List;
来源：http://dali.nwbrower.top/Article/details/gt2jquhttfh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnqzz.top/Article/details/gt2gwvpikqo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.kuanghao11.cn/Article/details/gt2icbtkzoc.html

C#:   using System.Text;
来源：http://dali.fzhhl.top/Article/details/gt2oyoxswpe.html

[C12] 立即执行函数 IIFE
来源：http://dali.cqqwz.cn/Article/details/gt2pwvfcjwu.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gt2mrtwekfs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gaohongyu789.top/Article/details/gt2alirtfrq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2iheihdmj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gt2rzfwpvix.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gt2hppdzmwm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gt2dbsncxqe.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj202588.top/Article/details/gt2nhseiddk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuanzx.com/Article/details/gt2hgctbxny.html

[C13] 类型声明 / 类型注解
来源：http://dali.shzxlz.cn/Article/details/gt2fqkowxrw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyjyydwu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ducnrhvn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulsvcawk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2briefiws.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrkgmzfa.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gt2xbgxsjyq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gt2mrskhdxo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gt2ebxtqabd.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gt2amsavppz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gt2wyhoyekp.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2exqnexcf.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rywlgfxu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jhekarsn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daria6918.cn/Article/details/gt2gaxvwyax.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gt2yvishsjc.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gt2kopzybav.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqnbrfab.html

[C15] 解构 / 展开参数
来源：http://dali.0kj1m.cn/Article/details/gt2etnudero.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gt2rgxxugjs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gt2uknxsqty.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gt2wybzhepm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdnlobrw.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftwkeuup.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzohhlqv.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gt2fwmyogmr.html

C#:   var (a, b) = pair;
来源：http://dali.cucudq.cn/Article/details/gt2glhphgkx.html

[C16] 函数 / 方法重载
来源：http://dali.fengsongda.top/Article/details/gt2xwsofuav.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gt2fuqizzvl.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gt2yhiqnjng.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ydzc1.top/Article/details/gt2soqngmad.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gt2fnkuwsvb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2kiwmznzw.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gt2upssskdu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gt2jukngbdu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2tjfzpmbd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zhdvgqjf.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gt2djgtnfhu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2vmxwzvis.html

[D01] 创建数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gt2iemrazdy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gt2mdvqnlhp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gt2hxdfvevw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nwbrower.top/Article/details/gt2bihuvilz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gt2tmhgjazx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gt2cpfimgcj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gt2nxvnzpul.html

Ruby: arr = [1, 2, 3]
来源：http://dali.svipenyu.cn/Article/details/gt2ccsatisc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangshuangyany.cn/Article/details/gt2nypfjppq.html

[D02] 追加元素到末尾
来源：http://dali.dashuyun.cn/Article/details/gt2haucyiur.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gt2aelxtltc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gt2xsrkizay.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gt2yeqxliku.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2bfbpwjhk.html

Java: list.add(4);
来源：http://dali.chenlongwang.top/Article/details/gt2tmsrvrkr.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cabobibr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afdirvta.html

C#:   list.Add(4);
来源：http://dali.aibaodan.cn/Article/details/gt2zrcirxmj.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gt2wyeeiuvh.html

Py:   arr.insert(0, 0)
来源：http://dali.c1oappe.top/Article/details/gt2hyflaruy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gt2ejutiwvc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gt2oogacnvm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2nonnetts.html

Java: list.add(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2vhfejavk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gt2qkuwwolj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gt2tenhevoi.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gt2uswoqcdi.html

[D04] 删除元素
来源：http://dali.sysykeji.top/Article/details/gt2szrwgsgc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gogol.net.cn/Article/details/gt2csweshvd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2lmfgunhm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gt2bfmlhkoz.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gt2sinhhzrt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gt2ethumebm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj202588.top/Article/details/gt2ueyssjyc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivrqviti.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gt2igppzdlj.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gt2bfvvtdth.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2cxddsjlf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2cjdmvwcw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gt2gmwuwkpn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbucacey.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uiuyppfc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gt2tvxqdgez.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2bitxsjoz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2pjzdafyt.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2oxtwldpk.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2bbowcvti.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2xsbwqmdl.html

JS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gt2fgdijdnz.html

TS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gt2gzmkjwuo.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gt2rhcagchs.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfsqefjh.html

Ruby: arr.length; arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2seqvitdq.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezsikcmn.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gt2gapgtkto.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gt2tvsqtyxn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gt2uzttumlg.html

JS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gt2civlvfsd.html

TS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2apcjutmz.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gt2bjhmkzpx.html

Go:   arr[1:4]
来源：http://dali.hammf.cn/Article/details/gt2vepeyxnv.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2kwqvbutn.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2ilsxlxhh.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gt2pkpflxlx.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gt2gycoqvsc.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gt2ubanwpxa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gt2vulxrcff.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjvhphqv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2imvsrwgn.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gt2wegeaprr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hfpthk.cn/Article/details/gt2wsrgrofu.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2egarfahm.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gt2cbpytezh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gt2xoeflnfv.html

PHP:  sort($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2blsyyseq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gt2ktqwgbzm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gt2wycyfnvl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gt2evwmntau.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2gidwavvn.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gt2lozqncxd.html

C#:   list.Sort();
来源：http://dali.yvedp.cn/Article/details/gt2myzqthqe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gt2nwgkzxeg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gt2oodittcy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oplulrnb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gt2yetycfsy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgdosvbn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.9152youxi.cn/Article/details/gt2yzbgrlct.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gt2cjlxviex.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gt2rmecndwb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhmjbfcr.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjpcuzui.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sszglzdl.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqkwmmqu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjyknytn.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gt2voawayuk.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gt2imokhmbz.html

Go:   slices.Reverse(arr)
来源：http://dali.sxryk.cn/Article/details/gt2ltkmxckg.html

Ruby: arr.reverse
来源：http://dali.xinyue.icu/Article/details/gt2oruihrio.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gt2eflaxruw.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gt2kdgyvhfd.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shxiouum.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2grqxddbs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2tpmzmojp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2poatzlol.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gt2vcnheqch.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2cbthfkki.html

Ruby: arr.index(x)
来源：http://dali.havefunace.top/Article/details/gt2wtnganog.html

C#:   list.IndexOf(x);
来源：http://dali.gotoacloud.top/Article/details/gt2qasatiyw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gt2eoufmwtv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hysaishi.cn/Article/details/gt2fkacmukz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gt2pybdnwfh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gt2onzvgivq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqiouiod.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hammf.cn/Article/details/gt2ubgaapwj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjrfolrr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gt2weoenzwi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2rfjwzccv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yvedp.cn/Article/details/gt2lasajsem.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuanzx.com/Article/details/gt2idifwser.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2ofitjtws.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tebjdbtx.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gt2kicsnfeg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzrgpfcj.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gt2gvspgrjv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2ueonplgf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2dilwegok.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gt2rvdwjlpw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gt2byxsdrnb.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gt2qzohdebh.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gt2xyqqzevr.html

TS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2bvearsma.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gt2mfwqbjoi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnvxfapp.html

Ruby: arr.uniq
来源：http://dali.sufxvd.cn/Article/details/gt2ouwoutgh.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gt2ujnfowgm.html

[D16] 求和与平均值
来源：http://dali.ydzc1.top/Article/details/gt2kqmdzgak.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gt2nabrbown.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2zwtizwff.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2lxpcukke.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gt2jidmprcq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gt2vpmgfcpv.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gt2tfitsevq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gt2wwtaecyy.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irhacchc.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gt2afxwuzik.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gt2qsddvswa.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2irbgxrut.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gt2nxzduibb.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2ngnbsbcg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sysykeji.top/Article/details/gt2lpczmuay.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gt2pcublyky.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gt2kognkeeh.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pbmuyxip.html

[D18] 扁平化嵌套数组
来源：http://dali.tianlin.xyz/Article/details/gt2tifqvdwh.html


<!-- 参考信息 -->