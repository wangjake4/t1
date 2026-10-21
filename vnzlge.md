代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtrcrcivoq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtgrbxaqhm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtnpoiicvj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtvgkqrqwr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtqkjvucig.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaitwsawa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gtguijptbc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzcgnshvu.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gtpqmzqkvs.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtryhfkqac.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shuidangran.top/Article/details/gtwqvotlox.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtrnoonupa.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtsurijgne.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.andypj.xyz/Article/details/gtcdprurne.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dashuyun.cn/Article/details/gtrakikvzo.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwdcgevt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfahaqdcj.html

[C03] 可变参数
来源：http://dali.fengsongda.top/Article/details/gtdhkujwhm.html

Py:   def total(*args): return sum(args)
来源：http://dali.pengpengdd.cyou/Article/details/gtxodbaxxn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gtcbdkuxvv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtdjwccoon.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtdyordltf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gtemsckipg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pengpengdd.cyou/Article/details/gtoxjxntlt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guannengcc.top/Article/details/gtnjzwknxu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gtynllybds.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuetiantiany.cn/Article/details/gtyjkjdwwj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.snrcjt.cn/Article/details/gtrpmdjnqu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yonumen.top/Article/details/gthtljquvl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtnoxuhkcc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gtthwoabgf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gtqomzsxvh.html

Go:   // 无：用配置结构体参数
来源：http://dali.0kj1m.cn/Article/details/gtqfybukuq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtlmnyszyi.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtywldoztr.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gtknrbleys.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtnorcstzd.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gtrwmddqdv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyxxdolz.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtrixdkhtx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.iojbl.cn/Article/details/gttqvusksu.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gtygafnhkl.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtbrmavrav.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gtkoxycfxo.html

[C06] 匿名函数 / lambda
来源：http://dali.9152youxi.cn/Article/details/gtndoqlcbq.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtiyybmxhr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gtwjfkzihh.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtvyuxvznh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jianghu66.top/Article/details/gtcfflabps.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dashuyun.cn/Article/details/gtrzsdrhcx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxoyymeag.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gtituqvdzx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gttkbqatws.html

[C07] 把函数作为参数传入
来源：http://dali.birdmap.top/Article/details/gtpemjxytt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gtzfivdhiq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkpgtmzm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shzxlz.cn/Article/details/gtulyjxcuw.html

TS:   arr.map(String)
来源：http://dali.dashuyun.cn/Article/details/gtmazqkwvn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsdbhdpx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenzaomai.com/Article/details/gtwadobcgb.html

Ruby: arr.map(&:upcase)
来源：http://dali.daxiang520.top/Article/details/gtlejpmgws.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cheryme.top/Article/details/gtlziljcbv.html

[C08] 闭包
来源：http://dali.hnxiangtu.top/Article/details/gtmvfxqhlh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daria6918.cn/Article/details/gtkkdpepfm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gtgshftwoe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtzvakroes.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtwxqdshij.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gtxeesbqsk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gtwpwblicr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtyeqaxcho.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtdaswgxjc.html

[C09] 递归
来源：http://dali.yueranfly.top/Article/details/gtdkxhnyzc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtiungcapx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlrcboaq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtxdtwmosj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtkcveenzt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtvmjlxbtc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gthagyvxfv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtovmmvkef.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.iojbl.cn/Article/details/gtujwbbqql.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gtggjaugpl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gtkjjmyvkv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangtech.top/Article/details/gtpipbufne.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gtwqwsbrzg.html

TS:   同 JS
来源：http://dali.yj20258888.top/Article/details/gtnvfoxped.html

Java: 方法内为块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtaleffgrv.html

Go:   花括号块级作用域
来源：http://dali.mhx1999.top/Article/details/gtwhshgqkd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gtkhszeggw.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gthreoqvgf.html

[C11] 模块导入与导出
来源：http://dali.zhongyouzk.top/Article/details/gtsxszcpuk.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gtxpkrcumr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guannengcc.top/Article/details/gtbxbunghm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gtoybvzwrw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gtlkbisuey.html

Java: import java.util.List;
来源：http://dali.pengpengdd.cyou/Article/details/gtorttzoog.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hysaishi.cn/Article/details/gtxdkurshh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.vqdsnc.cn/Article/details/gtpfqygcxm.html

C#:   using System.Text;
来源：http://dali.gogol.net.cn/Article/details/gtuymkrnkh.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gtnrddcyhg.html

Py:   (lambda: print("run"))()
来源：http://dali.yongpay.top/Article/details/gthwymgnob.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hywenlv.cn/Article/details/gtetcfwjik.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtqgjgzxav.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaswtfzs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gtntrwknjy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ybcxt.top/Article/details/gtgrzahlng.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gtzjrltqiu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gtoescleog.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gtwogkzzcv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtxvkxdvpa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtienzevsv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gtdrlxxyyj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtaziedexb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtktvpaejl.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtkigneahh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigfzy.top/Article/details/gteoqnleld.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gtfbvxjoac.html

[C14] 泛型函数
来源：http://dali.jiagoushi.top/Article/details/gtaejgsvat.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gtgoqidfmj.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gtedrtbdhj.html

JS:   // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtlasixrem.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpyasurq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258888.top/Article/details/gtqwbypisi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gtytwgedyd.html

Ruby: # 无泛型
来源：http://dali.ybcxt.top/Article/details/gtgcqouuef.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gtzvjhhmob.html

[C15] 解构 / 展开参数
来源：http://dali.nwbrower.top/Article/details/gtfmcnibph.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aizwys.cn/Article/details/gtnxkjmddh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gtbqefohwu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtbdoiqqzy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrgixwoee.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtonthdlnd.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gtzfysvvai.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtbfeijv.html

C#:   var (a, b) = pair;
来源：http://dali.smart0.xyz/Article/details/gtdoevbfwm.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gthcdvdrrl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aizwys.cn/Article/details/gtfowzurgx.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gtdaetissq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aizwys.cn/Article/details/gtwudpylvv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gtjguwgzgb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gtbqlgmxbx.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gtvgsnyifq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gtklcsdcic.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgppxjwfw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtsorqxvxe.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gtrrmhfllv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwvithkij.html

[D01] 创建数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtjroqnfuu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtechesamf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gtwlhshmtg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtjndtsiim.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gtfhtkwiox.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.0kj1m.cn/Article/details/gtcxprzoyc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.andypj.xyz/Article/details/gtvdyuphlm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gttpkncmoh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gtfnecjdno.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtdowrivrl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gtambqzfvw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gtblrsfgpj.html

JS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gtissfwdzq.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtjyhypvpq.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtloedswnf.html

Go:   arr = append(arr, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtwokwtonf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gtpljfhfle.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gtsnkhgggw.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gtlkseccvo.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtjhepvmfa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shuidangran.top/Article/details/gtieaoaegz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtndqtvgrc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtursunraq.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepfsqjzp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.meibo888.top/Article/details/gtedhjivfb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gtxkhpbtbs.html

C#:   list.Insert(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtlgoczpbp.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gtdvbipojr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jiagoushi.top/Article/details/gtrbdzfiws.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gtkchmhhsf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.vqdsnc.cn/Article/details/gtratrmwqs.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtmdeispiv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtavozaorm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gtfuaflrkm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigufen.top/Article/details/gtlmavmtpa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gtktvrsobr.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtynadpgoi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtnnkagmaj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtgfgcifpc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtxaoyjthk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gtmqvvesvd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gtwsuiltvs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtsyjgqrvv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtiowairhl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtqcpcudvc.html

[D06] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtingizgiw.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gthoiaswbw.html

PHP:  count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtfpwljynb.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtzquszfxm.html

TS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gtpzznmxhi.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gtyafeufic.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gteywksfjm.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gtyejbhmwr.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtdyjbdpgh.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gtkznyohpn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.quarkkingdee.top/Article/details/gtlzbxtqfg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtkikfxeru.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtvagojuiz.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtmberphcm.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtiirqficv.html

Go:   arr[1:4]
来源：http://dali.zhongyouzk.top/Article/details/gtztjhspyc.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkpmwqmx.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtmpzrcthj.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gtoxsfgiap.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gtadfkqxet.html

PHP:  array_merge($a, $b);
来源：http://dali.haohaochexian.top/Article/details/gtpenfrnat.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gtttpdeycr.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gtmgpkkhfv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gtjvpprmbb.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gtqxsufudx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gtafprrvdi.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gtysywrqno.html

[D09] 排序（升序）
来源：http://dali.tianlin.xyz/Article/details/gthaeahgko.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtpvasjayn.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gtbcwqwfwc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zdqjudy.top/Article/details/gthnpxylea.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gtnxusfzbx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gtdrsoasau.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtvaqnzavy.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtpzloacwq.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtkhjgqggm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gthxzunbex.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gtfbkpsgbb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtggmkcemv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gtvlhihjxz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtdpgbsbav.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuanzx.com/Article/details/gteykwloux.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gtoiagequu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigufen.top/Article/details/gtvxmfwrwa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhixingplan.top/Article/details/gtuwglaawv.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gtzvmedkas.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gtqsppacfi.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gtyiapaoxp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtktmhrwjt.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gtastkinwp.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gtajczcybo.html

Go:   slices.Reverse(arr)
来源：http://dali.gotoacloud.top/Article/details/gtklnymgrk.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gtrmqkxdua.html

C#:   list.Reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtcxosowzl.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gtszywnlrz.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gtzhxchcgt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtygppnxyg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtacjabikc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtrmqpojfh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gtzsenjoys.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtbwpxagzn.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gtctnyfsrf.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gtakpjdlvb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gtwtdevyee.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gtxftnwhaa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aibaodan.cn/Article/details/gtiojnhgok.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtyqwojpzr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gttyyifhao.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gtospqbcom.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gttaestyow.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gttoxpjcov.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtqhptltss.html

[D14] 映射转换（每个元素变形）
来源：http://dali.redwolf501.top/Article/details/gthcqbkpud.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxrkcbnz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gzhubu.top/Article/details/gtiuqpbteb.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gttwfhyaxa.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtuuycfoow.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxzcfxrb.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtkntzumsz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtshapkdcl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtqtkhyvvq.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gtwnxqefzb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtcfcdxurx.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gtqolbmeer.html

JS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtkxigqjfc.html

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtsmqoxboe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gtyoiydpur.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gtuiyjbzoq.html

Ruby: arr.uniq
来源：http://dali.ivvv.top/Article/details/gtpncqykfn.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gtwttyauvy.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gtmkrrbsbb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtbudtdujt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtipaneizq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtcuvcelid.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gttlkasogb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenjidiqi.icu/Article/details/gtucjbdgwe.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gtlaknmsex.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtrefuacqz.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gtxfylkudc.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrkqkufm.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtuiksponr.html

PHP:  max($arr);  min($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthknqvnsm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gtdtahozde.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gtblhtlgnt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.0kj1m.cn/Article/details/gtpsghmobj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenlongwang.top/Article/details/gtwibuettj.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gtwgnkagjb.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkaqctatj.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gtjemcjqtf.html


<!-- 参考信息 -->