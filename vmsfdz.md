代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gt2egjfhltb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hyjrztbw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vmwjsnwn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rglxxmlg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2nnbmabbg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.haohaochexian.top/Article/details/gt2vaecfjpl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj202588.top/Article/details/gt2psabifug.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2ebununmu.html

[C02] 默认参数
来源：http://dali.zdqjudy.top/Article/details/gt2ssurmery.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gt2nzvxaabn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2joqqswyo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2objhypwd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gt2oqlibbzn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gt2wwcncywj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yvedp.cn/Article/details/gt2bxwwkgbn.html

Ruby: def greet(name = "World") = name
来源：http://dali.jianghu66.top/Article/details/gt2ayrmtwie.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhongyouzk.top/Article/details/gt2mvbljvxp.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gt2pniulknp.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gt2edlmpnub.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aizwys.cn/Article/details/gt2ybygvjce.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gt2dwtjyhdl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cymmisyx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsbdotvx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgfzy.top/Article/details/gt2gkfrhysp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.iojbl.cn/Article/details/gt2qfoyutcy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gt2pvnwgtqe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gt2siyztfrb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gt2iihrzckq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jiagoushi.top/Article/details/gt2mnfkpsuc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2nokqiatd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jiagoushi.top/Article/details/gt2nylhredz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gt2rhvtvlvx.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvyvkhhi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2xmuyrcpq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gt2bviuwmzy.html

[C05] 返回多个值
来源：http://dali.sweek.top/Article/details/gt2eurkbmec.html

Py:   return a, b
来源：http://dali.yj202588.top/Article/details/gt2adqsmijh.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gt2hzldrjxt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.havefunace.top/Article/details/gt2gpwrxbsd.html

TS:   return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gt2zkicpuvf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.redwolf501.top/Article/details/gt2eecihrwk.html

Go:   return a, b
来源：http://dali.cashguo.top/Article/details/gt2bfoqinfr.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gt2jrtiqnsy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sysykeji.top/Article/details/gt2mxscdyyy.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gt2faybosht.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktqvxpmb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.iojbl.cn/Article/details/gt2nmirqpvg.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gt2ntonwvry.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2dvqpmkgr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqsotxvx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gt2qlilybah.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2djiybnpx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2woxeourg.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ftidbwhb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gt2jayqbzjh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gt2gyvdxwqq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gt2bsvzzceo.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yestqzdz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tisqgfsh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.haohaochexian.top/Article/details/gt2tgjqywcl.html

Ruby: arr.map(&:upcase)
来源：http://dali.zdqjudy.top/Article/details/gt2khzhvqud.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gt2vfmsiycn.html

[C08] 闭包
来源：http://dali.jiagoushi.top/Article/details/gt2ptlubocf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gt2xmmbrjib.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2renmrimq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gt2tofpcrsu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yurfkdho.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gt2oakmlhjp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gt2xijxnjll.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gt2lpjdhtsv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gt2tllmsqag.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gt2ulhfcpoz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gt2oqjrqcsw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gt2mvsuexvl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gt2hlurraey.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gt2fmivtkkt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gt2sgztbcha.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gt2unoihchl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gt2yzjhiegg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xinyue.icu/Article/details/gt2jygozexz.html

[C10] 变量作用域
来源：http://dali.316326.xyz/Article/details/gt2ddmakfij.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gt2kblnuhge.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxinkj.top/Article/details/gt2zykazgwv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gt2txvkkbni.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gt2mhcibmqq.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2kzslehaq.html

Go:   花括号块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2gpoqogxa.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gt2zdsamvfu.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gt2aggnfziu.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gt2nbgwtukv.html

Py:   from module import func
来源：http://dali.cashguo.top/Article/details/gt2gusxscac.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.kuanghao11.cn/Article/details/gt2vytnfteg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gt2cggnzoqn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gt2jiqpjgyc.html

Java: import java.util.List;
来源：http://dali.cashguo.top/Article/details/gt2lqvcewpo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fzhhl.top/Article/details/gt2jkhtlkck.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gt2dpyocsnx.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gt2ekwlgsfp.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gt2nizxvdwx.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gt2xlytdxvz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.vqdsnc.cn/Article/details/gt2hrgbqpbh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gt2jyfuqchr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gt2dkqyfdtn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gt2nwsgdnze.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gt2uxxkaftx.html

Ruby: -> { puts "run" }.call
来源：http://dali.hysaishi.cn/Article/details/gt2fwjdoyzz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2akxjyqlo.html

[C13] 类型声明 / 类型注解
来源：http://dali.sysykeji.top/Article/details/gt2xzkpsjhj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gt2lujttzrc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2tabfhfkc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gt2nyijdcok.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2ftqrcune.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gt2dzcaxpwn.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ieyiqkuk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.svipenyu.cn/Article/details/gt2aljmuobj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gt2dyxivirz.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmicdtxz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2lgjuqgmt.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gt2bqrrwlxv.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2ojoyaiba.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gt2oirseobt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqcwcxnc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2houvfutf.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2livddfxe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gt2xujatint.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2btwblwqh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gt2jxmocbsj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gt2rzxfpzmq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gt2rxnexmhl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvcdfamx.html

Java: // 无解构
来源：http://dali.redwolf501.top/Article/details/gt2fshqdrhy.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gt2unfletvy.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gt2sapblqsx.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigufen.top/Article/details/gt2rbwcuoib.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gt2rfzmhuxo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gt2mafpghpz.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gt2dzboaowy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gt2vsjdyrau.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gt2upqkdjcy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gt2uxrggrdc.html

Go:   // 无重载：用不同函数名
来源：http://dali.fengsongda.top/Article/details/gt2vzgzqmwo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gt2shbbvblz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sufxvd.cn/Article/details/gt2voeykfbr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2mtuutrwb.html

D. 数组 / 列表 / 集合
来源：http://dali.dashuyun.cn/Article/details/gt2mkbknhoh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2oucxshld.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gt2wfgxorbd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gt2iixjeoop.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gt2vcnrujpf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gt2kshpmmiy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cheryme.top/Article/details/gt2dkaxdpkv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gt2wydjqrfm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gt2jqsghlqu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gt2khhzkcfe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gt2koysupcn.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gt2dtwptsuq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gt2gyatwkwl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gt2exxwxjjc.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gt2okkelfib.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2bstahggr.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gt2bnctzzpp.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2dqqeleli.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gt2tmngnjzj.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2votbqoqj.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwqlrjbh.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gt2yqvzxyas.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gt2aequpphm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenlongwang.top/Article/details/gt2vozzgomy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2qxjlksxb.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2attqqonq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gt2wqmptdmf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sysykeji.top/Article/details/gt2ivarards.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2yusqetpe.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gt2yntniwwt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gt2hbbhhoiu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywiyddew.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.quarkkingdee.top/Article/details/gt2lufaumrf.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gt2cvxbicjp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuanzhike.top/Article/details/gt2njnymydu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gt2qdzbbppe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gt2itmddqgm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gt2lrevxzsk.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2dclorxvr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2jkoabvbk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2zsvbqdgu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2dwppwigb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gt2uqhoyntn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxinkj.top/Article/details/gt2bxszcujd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2euickapf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysdonoww.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gt2jkusuuno.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2uvbuxbmg.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2jvjhjkls.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gt2xcbglmko.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2tubigwrz.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gt2fgecgbzh.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gt2jcspkyqd.html

Go:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gt2upmcgbmr.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigfzy.top/Article/details/gt2riejultb.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gt2wbirlkbn.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gt2gvelgdsa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iujdvdmg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2anazstdi.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2ntaadbcy.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gt2yyvqjoli.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2cidlnezb.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gt2owhpaxsj.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gt2xtejovqa.html

C#:   list.GetRange(1, 3);
来源：http://dali.ivvv.top/Article/details/gt2ugozsxiw.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gt2kkwufcug.html

Py:   a + b;  a.extend(b)
来源：http://dali.ivvv.top/Article/details/gt2zrfjlmvr.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gt2okpwyicg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gt2ytwmdhmi.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gt2mmdumezy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2kfbcnlho.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2enmnlbua.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lncjeixm.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gt2ftgfyvpb.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gt2agffiyep.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2pyzkpspa.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gt2tkwgpgxd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gt2ersjterq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gt2ffyabkjt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gt2gfvigfot.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ficlbmji.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gt2eoanoxqc.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gt2ezkutlig.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ehwqpu.com/Article/details/gt2mauijwzf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gzhubu.top/Article/details/gt2zxdpkoaf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2qebteiml.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gt2dqdfxpzw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gt2slcppnpj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gt2ubbsfwpk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gt2puyurjuy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zycfv.cn/Article/details/gt2zjycxgls.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.smart0.xyz/Article/details/gt2clebxpsz.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gt2qefqwgnz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gt2lkpogqgh.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gt2pazpxqwl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gt2pipiishi.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2mtuivobm.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gt2nqauzrfk.html

Go:   slices.Reverse(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2qmfilntp.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gt2wjxxoxzo.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdgqcnat.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gt2jwkchyuw.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gt2oyoqlsle.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gt2xtlspwgf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gt2uqaxsprj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2tivatuiv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gt2pcbrvqsf.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2tujgpewp.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gt2ljejnnoj.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gt2ecvfdvmf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gt2bglqaiko.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2exnosztu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gt2dkuulcmr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gt2unmfcpcf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gt2ffeyufoa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnqzz.top/Article/details/gt2gdxfbzda.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenzaomai.com/Article/details/gt2mqatcmsy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yanxiufei.cn/Article/details/gt2sjxrqsub.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2npriuasj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gt2ydkvvqoi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gt2ujvfbuou.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eitldezt.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2izonmolz.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2hpvzqgay.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gt2rjvrykqw.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihkzyyii.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2zgwcdols.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2rgsyypmf.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gt2dakteiua.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxmixekh.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gt2naykykvh.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2noyaghbh.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2wzrhyjju.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hfpthk.cn/Article/details/gt2yroeeinw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gt2yddjdgqz.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gt2myjhbagh.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2cnwvtzwg.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gt2jasohpfn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2kxcmourz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sxryk.cn/Article/details/gt2kkwvytqf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gt2jovlbfrc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gt2xjfacnom.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhengqikj.top/Article/details/gt2csdvtsyg.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gt2hlvzncfc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gt2eoqolreu.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gt2zvkbmkju.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gt2xyzbwszr.html

Py:   max(arr);  min(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2lzstygwv.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2dfsbcyib.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gt2utgewkih.html

TS:   Math.max(...arr);
来源：http://dali.wangdashe.top/Article/details/gt2ddnoogsk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guowangkeji.top/Article/details/gt2aqmexggh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gt2zmrotoon.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gt2nntrnuhs.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gt2vgowzrmh.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggblmvha.html


<!-- 参考信息 -->