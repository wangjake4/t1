代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2xoacaitg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.birdmap.top/Article/details/gt2rqpqbqkt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gt2azyqmjbx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ieedjybh.html

[C02] 默认参数
来源：http://dali.tanke756.top/Article/details/gt2nocnqkyh.html

Py:   def greet(name="World"): return name
来源：http://dali.hysaishi.cn/Article/details/gt2davljgne.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gt2fqmpxyuk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2stwcwusf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dytjzgkh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gt2nmnxfrtu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgufenzy.top/Article/details/gt2qkkzernm.html

Ruby: def greet(name = "World") = name
来源：http://dali.xziqi.cn/Article/details/gt2mfdljysd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gt2jhoggpnp.html

[C03] 可变参数
来源：http://dali.ydzc1.top/Article/details/gt2lfzywnpi.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gt2ctzpinfr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guannengcc.top/Article/details/gt2nzybuppw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gt2zvjdziot.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gt2idaqhlpe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gogol.net.cn/Article/details/gt2bmubmmxs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.snrcjt.cn/Article/details/gt2robdevsj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hfpthk.cn/Article/details/gt2mmbtbymr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.kuanghao11.cn/Article/details/gt2vobxgpnu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hysaishi.cn/Article/details/gt2rkinzqwr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gt2eiakfdvi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gt2xtlngskq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gt2qvnxuobs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ivvv.top/Article/details/gt2izjtahfz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhoulong.xyz/Article/details/gt2rxwrcfjr.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuiykkrs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gt2ydohoevc.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpgfnjck.html

[C05] 返回多个值
来源：http://dali.hnxiangtu.top/Article/details/gt2jiuezush.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gt2lldslyor.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gt2dwklpaqj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mawfqsgf.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhjrzscl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.316326.xyz/Article/details/gt2ffzaeiro.html

Go:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbvazizo.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2rrtrxnwy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gt2emhpvdvz.html

[C06] 匿名函数 / lambda
来源：http://dali.zhongyouzk.top/Article/details/gt2yzsviobh.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gt2ktzdlxva.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xumvkayw.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2uelcyjwm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2xgkwtrgs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xifunxqb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gotoacloud.top/Article/details/gt2nolwtfsm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gt2mxhkrxfv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gt2ylldelmw.html

[C07] 把函数作为参数传入
来源：http://dali.dashuyun.cn/Article/details/gt2tawozwoz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hfpthk.cn/Article/details/gt2tneoxsqf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2tnuvknrc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aofsvynx.html

TS:   arr.map(String)
来源：http://dali.sysykeji.top/Article/details/gt2kvpqczdl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2zynokgij.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gt2qivkjbfp.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gt2npbckyio.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gt2xlpqmxch.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gt2elmwlzst.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gt2yeckgukn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gt2jkykaomk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2zszfetau.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2cprbjuyz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yvedp.cn/Article/details/gt2sgmlniqw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.c1oappe.top/Article/details/gt2dgwilrzh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhixingplan.top/Article/details/gt2kanzpryg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gt2ljavcqem.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gt2uhjjhilw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gt2nhvtgjup.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gt2ydqedjgl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfnqppwh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gt2paqiciug.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gt2fnbbjuyo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gt2lfksevim.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqyvhcml.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jlsjyb.cn/Article/details/gt2twhmcffh.html

[C10] 变量作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2bcupygnz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aizwys.cn/Article/details/gt2lphtxxqr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gt2aqpnbdsa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2ptibhhip.html

TS:   同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gt2lyeggraa.html

Java: 方法内为块级作用域
来源：http://dali.wangdashe.top/Article/details/gt2srvhgolc.html

Go:   花括号块级作用域
来源：http://dali.xziqi.cn/Article/details/gt2vtgbnxve.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gt2aarylzti.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2ymibkcbu.html

[C11] 模块导入与导出
来源：http://dali.chenzaomai.com/Article/details/gt2rjhljpdq.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gt2wzqubkkp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgbychtg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gt2bapnsleo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gt2sywtsqtm.html

Java: import java.util.List;
来源：http://dali.svipenyu.cn/Article/details/gt2jplnwdzo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gt2cwxdehgb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhoulong.xyz/Article/details/gt2yqaxukyx.html

C#:   using System.Text;
来源：http://dali.chenlongwang.top/Article/details/gt2jhjrzrpx.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gt2qcbthjvx.html

Py:   (lambda: print("run"))()
来源：http://dali.dianchejie.cn/Article/details/gt2xofhqpfk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuuuzuj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gt2mqwvvmck.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gt2gjpjcwal.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gt2imhoovpk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gt2dtxvipxt.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gt2gmuenyxy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ivvv.top/Article/details/gt2zvqewvgs.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrdcdrdu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigfzy.top/Article/details/gt2dxibaage.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gt2upozyefg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gt2buehfhhl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2pmswvlgu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ciuvyjvd.html

Go:   func add(a, b int) int
来源：http://dali.fzhhl.top/Article/details/gt2ssmedhtu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2opjnsgeu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shangyingyoupin.top/Article/details/gt2smfrgnbf.html

[C14] 泛型函数
来源：http://dali.yj20258888.top/Article/details/gt2jqqauamq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shzxlz.cn/Article/details/gt2ifvelbgm.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gt2xrjlulnu.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2btfckumb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gt2otgyvthy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gt2gmanyvhu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tabkeche.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2zzorwdrp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fekpntbr.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gt2mzbmppek.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.316326.xyz/Article/details/gt2znwmrrzj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gt2mqngipqk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gt2zdytrjsk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gt2yutekfwy.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gt2rnuzfheu.html

Go:   // 无解构
来源：http://dali.tanke756.top/Article/details/gt2nqbklyfi.html

Ruby: a, b = pair
来源：http://dali.tian-w.cn/Article/details/gt2bmdlkrqi.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gt2jswqsltu.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gt2cjimapzb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gt2tnlhmzhj.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gt2lwqxaper.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.haohaochexian.top/Article/details/gt2eddgvvfw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jianghu66.top/Article/details/gt2qxdhjwme.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gt2lceryhmo.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gt2yvoeecpv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.snrcjt.cn/Article/details/gt2rewsghxc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guannengcc.top/Article/details/gt2idrpwabr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hemmxosv.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gt2umpipfje.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2rpiifrlv.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gt2gmankiwc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqovjuwn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gt2aqfhpbju.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wreyvokb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gt2ltksdqjg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gt2mavyrfzy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gt2qcrwvekx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gt2natjwous.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gt2chmifwnb.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gt2uthkpyrz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gt2nivyohnm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okplxpac.html

JS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gt2gcpwwnos.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gt2cvnvpxdb.html

Java: list.add(4);
来源：http://dali.guannengcc.top/Article/details/gt2rejnugeq.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gt2atouilbt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbuejsdf.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2olrqmtrz.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gt2jnijordz.html

Py:   arr.insert(0, 0)
来源：http://dali.ydzc1.top/Article/details/gt2idaaufnh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxemggaa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gt2sgjdmudq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvhxrzxn.html

Java: list.add(0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2wgofqbfu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gt2qgrqsesj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jttayrnk.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gt2dviohdvm.html

[D04] 删除元素
来源：http://dali.dashuyun.cn/Article/details/gt2xptfbjvq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ppjwa.cn/Article/details/gt2ntdbiuqy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtcwkmpc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shzxlz.cn/Article/details/gt2nnmizjav.html

TS:   arr.splice(0, 1);
来源：http://dali.xinyue.icu/Article/details/gt2msmmqgzf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gt2sjvolnyb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gt2aggcxgqw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gt2aqugbjwz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yanxiufei.cn/Article/details/gt2ogpmlllk.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gt2xzptjiup.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2xioivdyf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxgiamdq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2fuexjvvy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuxming.cn/Article/details/gt2okhkhdzk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yggatalk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2exzvffhs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gt2rkjwbthf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2rvwfumkx.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gt2jvsogouc.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gt2mlgjxvpx.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2qcnsupjm.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gt2shoodxwk.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gt2kmmjqimv.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gt2ekurdcen.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2zyidrxry.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gt2hdkxzmgq.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gt2qqpwoeqz.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gt2nzqclhvq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gt2utizqbhv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrpflgdg.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2rwpywogb.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2vedvlxus.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2khazsohv.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gt2svzcuvwg.html

Ruby: arr[1, 3]
来源：http://dali.xuanzx.com/Article/details/gt2rwzhjhes.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2wyfauwlj.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gt2laldqoid.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gt2eanqpslz.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigfzy.top/Article/details/gt2wxijfsts.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gt2gefggvfr.html

TS:   [...a, ...b];
来源：http://dali.dashuyun.cn/Article/details/gt2qmyisfvc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gt2nxsnwxnp.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gt2pqvatltn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gt2hwdnzhli.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2opgmajmg.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gt2vovbydwm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2dphqxfgx.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2rpsjpxfb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.kuanghao11.cn/Article/details/gt2kviyvybn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgufenzy.top/Article/details/gt2lfvqypgv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gt2yvwhgrcf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2brwlaphg.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gt2dspmtspx.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gt2vrkuwjsj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gt2itumbmnp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guannengcc.top/Article/details/gt2zkvcttoa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gt2kotdvoqv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2yagwggyt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2sofirjjy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gt2zjhdawmz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjnsppca.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcmzaowd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.316326.xyz/Article/details/gt2msacdkqv.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkdjanyw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnamepij.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gt2nxntifld.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jyoumei.cn/Article/details/gt2ergvbdra.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gt2vmvetlsc.html

Java: Collections.reverse(list);
来源：http://dali.bjfxy.top/Article/details/gt2kippywdn.html

Go:   slices.Reverse(arr)
来源：http://dali.mhx1999.top/Article/details/gt2nkjacevt.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2xlsesapc.html

C#:   list.Reverse();
来源：http://dali.fzhhl.top/Article/details/gt2jhvkhcxg.html

[D12] 查找元素下标
来源：http://dali.fzhhl.top/Article/details/gt2oppygssr.html

Py:   arr.index(x);  x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gt2clixvcqo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuxming.cn/Article/details/gt2uezbvfhu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2muvhbdda.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gt2pbnfwhcl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.mhx1999.top/Article/details/gt2ftykhyrb.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2asfdeuhk.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gt2zwdycuco.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gt2fwfbullx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gt2nhvwwjfk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2ffthbnhy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pnlywaia.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gt2dpzufrzv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2olclnobg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gt2ojmyjctd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gt2cgidvfel.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gt2wuusbddx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gt2uongitbf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjwtyndj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2sonkrorc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gt2oxgnmvfy.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnmltykz.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2xxjvhlwj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2xxfuxuiu.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gt2eleudswl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2gpfjwbwg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2akkyijsu.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2bqrordqn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gt2bpxpxisv.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2dmknxfwa.html

JS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gt2xxiilbyo.html

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2fhznydjt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cheryme.top/Article/details/gt2nbqfvbau.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gt2txrwanns.html

Ruby: arr.uniq
来源：http://dali.vqdsnc.cn/Article/details/gt2rbmjtnnf.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gt2yfzghnoc.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gt2yhlpdlmu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgigqtfg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2vhogihyy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2ihobekzl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2fnrasxju.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gt2sqacbpmk.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gt2fnpicsfc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangdashe.top/Article/details/gt2eapuqkic.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gt2hqcpfbhw.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gt2aoflotgd.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqnrzvln.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gt2lqwmshwl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gt2cmbdjtzg.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhjocoe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jiagoushi.top/Article/details/gt2tvupizpx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2rioaissz.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkaxpzmf.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gt2vuggqurj.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gt2pmbsdkyb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gt2btsgjksa.html

PHP:  array_merge(...$nested);
来源：http://dali.yuxming.cn/Article/details/gt2aoifrhuv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gt2sjusrgum.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gt2issvhkdl.html


<!-- 参考信息 -->