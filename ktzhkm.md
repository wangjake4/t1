代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glqsqfts.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.bjfxy.top/Article/details/gt2zpzpqhxd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.316326.xyz/Article/details/gt2cekkmmht.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigufen.top/Article/details/gt2uwnwfdpb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jiagoushi.top/Article/details/gt2leltwzhu.html

[C03] 可变参数
来源：http://dali.mhx1999.top/Article/details/gt2hfrebrjr.html

Py:   def total(*args): return sum(args)
来源：http://dali.havefunace.top/Article/details/gt2ddmwemna.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigufen.top/Article/details/gt2bbcbbplv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oozijhfz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gt2fruwopko.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gt2bqrykxkl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gt2hgwbgejg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gt2qfbsnxab.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhoulong.xyz/Article/details/gt2mwsljsfe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.andypj.xyz/Article/details/gt2vzsnaqgg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gt2ysgxytoj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gt2gfwfrmnp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zamsavul.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfygehym.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjuxzyiu.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gt2zqfbsdpr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2ygqivkva.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzzpwivk.html

[C05] 返回多个值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddjxlhwd.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gt2uwbewhla.html

PHP:  return [$a, $b];
来源：http://dali.chenlongwang.top/Article/details/gt2cfrjxoze.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2dfazslnl.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gt2fsxhvddb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nwbrower.top/Article/details/gt2jcjcwgdu.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gt2sffccdyl.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gt2htnzsahw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gt2uirapaqm.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnjhdxfw.html

Py:   square = lambda x: x * x
来源：http://dali.snrcjt.cn/Article/details/gt2mjjnzzml.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gt2fgmktofs.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2eaynhscs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2qrmibdnp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guannengcc.top/Article/details/gt2yzrwmhul.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gt2xjtfpzhj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yonumen.top/Article/details/gt2sdaiaesc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2rhhloonm.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gt2btlfrpse.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aizwys.cn/Article/details/gt2rogvryqf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj202588.top/Article/details/gt2hplmifij.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shuidangran.top/Article/details/gt2azmmbmwr.html

TS:   arr.map(String)
来源：http://dali.ivvv.top/Article/details/gt2kvbpjdkf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2encqoqsq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jianghu66.top/Article/details/gt2ecvhptxp.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gt2uzsbkgqb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigfzy.top/Article/details/gt2jyqzfdrk.html

[C08] 闭包
来源：http://dali.daria6918.cn/Article/details/gt2zwsghluh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfmcmpww.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gt2wpkkmlup.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gt2evutguyt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2smorcrnt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfqqdbdf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gt2xlaxdtnd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szqqodvi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gt2eundvtxq.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gt2pkvclqcy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gt2rsagqipn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guannengcc.top/Article/details/gt2hustfaxj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gt2wzmluzqx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gt2jxoqrerm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gt2frhxqtxy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.birdmap.top/Article/details/gt2kvxtpkma.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gt2gubyegyy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gt2scokrlsj.html

[C10] 变量作用域
来源：http://dali.havefunace.top/Article/details/gt2zetewcgd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dianchejie.cn/Article/details/gt2zvbkwync.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gt2poyiarrm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2itwjwlnx.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcoaswg.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2ppdaujuw.html

Go:   花括号块级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2gkgnpqjy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gotoacloud.top/Article/details/gt2qjmaqvwl.html

C#:   块级作用域
来源：http://dali.meibo888.top/Article/details/gt2zaqumkfn.html

[C11] 模块导入与导出
来源：http://dali.chenzaomai.com/Article/details/gt2epoltpyo.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gt2exbhwgqb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gt2swztoyak.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gt2ueymztog.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gt2kefeqxoh.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhyshwle.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gt2sfqouchl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gt2plorekiq.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gt2hqknzzyp.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gt2uzgiioms.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gt2vrsphzms.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shangyingyoupin.top/Article/details/gt2bchzybgj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gt2ledcakhi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gt2xgfwgqsx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gt2mzsgapus.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yangfankeji.com/Article/details/gt2icxnmplw.html

Ruby: -> { puts "run" }.call
来源：http://dali.yongpay.top/Article/details/gt2fgegujhr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gt2tcjnykrb.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2tvrbkuqc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbkkbkgi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xosjwbum.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gt2qvlpwhio.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2cgenjerq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2fdogjvye.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gt2nkjiaqnh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxidhnsa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.birdmap.top/Article/details/gt2wcaeaion.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gt2ynopuiyp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gt2idhefbtm.html

PHP:  // 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2kwsaqgbu.html

JS:   // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2cauduchu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qpxrheux.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gt2xdkpsisp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.quarkkingdee.top/Article/details/gt2xgttazjg.html

Ruby: # 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2golmsupw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yonumen.top/Article/details/gt2gurwlmku.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gt2ramrpfyz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gt2winykvnf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gt2xcahruar.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gt2iosshziu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gt2ltwixdex.html

Java: // 无解构
来源：http://dali.chenlongwang.top/Article/details/gt2kfeepiyp.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gt2ymkulguf.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gt2noijspag.html

C#:   var (a, b) = pair;
来源：http://dali.chenlongwang.top/Article/details/gt2xrwydflp.html

[C16] 函数 / 方法重载
来源：http://dali.sxryk.cn/Article/details/gt2kpfffvrq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gt2epuchkxh.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gt2nxjtxvwj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gt2svqoshxp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gt2iqdnoetc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gt2coqgwcwf.html

Go:   // 无重载：用不同函数名
来源：http://dali.sweek.top/Article/details/gt2dtpdosji.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gt2xnhcidgt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gt2nzvkdnea.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2xtlukvzf.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gt2zfuxhppp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2cgywlpiv.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2yxvlnyvv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gt2eiznkpxw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sysykeji.top/Article/details/gt2pffeeftx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnqzz.top/Article/details/gt2nikxobct.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gt2akupsiei.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gt2iaznnocw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gt2zheojywl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgfzy.top/Article/details/gt2sxopubml.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gt2mhibwygc.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gt2teygnkgx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gt2dzrjbmyl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kioskiiz.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gt2wygswrvw.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2etxtfnfu.html

Java: list.add(4);
来源：http://dali.guannengcc.top/Article/details/gt2sebzdwby.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gt2fjcqenec.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gt2jqqujhsv.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjnoiypw.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gt2lodvzrvr.html

Py:   arr.insert(0, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2fvimhqmd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gt2zqxupvjf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gt2otlgtfji.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2lmfwxbhx.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2hhqmkqnt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gt2rmqbgjmn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258888.top/Article/details/gt2vlqzloth.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2qhtrlhap.html

[D04] 删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scaiiwwh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gt2fkgeflsp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gt2hvnkcssg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gt2intlysut.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gt2zosfkdhy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2lckcyutd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gt2tyxecolb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2cpdzwliv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gt2ersnaayq.html

[D05] 访问与修改元素
来源：http://dali.wangdashe.top/Article/details/gt2xhuuxyfu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2ozebyrpo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eenbhahj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2erugxtsp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuanzx.com/Article/details/gt2eulbbfoq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.smart0.xyz/Article/details/gt2krxebhlu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2mehgkknc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2hizddzcc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2scrptixm.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2jounnzlb.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2slhaueui.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2syhjxlty.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gt2jyauqxpk.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gt2qdqvgcuo.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gt2jqtpzafg.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gt2jwaxzdgb.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gt2qqodtsgo.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gt2bduobpqz.html

[D07] 切片 / 取子数组
来源：http://dali.0kj1m.cn/Article/details/gt2uyhxarcj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dscaxovz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gt2mvbvlist.html

JS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2qkgfiysn.html

TS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2dwtapott.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2rlknwsjk.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gt2xwotswec.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gt2snjjsqxo.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2aqymgjuz.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gt2izkzqjvn.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ukjdincd.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gt2wjjsours.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gt2hvcrtoia.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gt2eoyofapa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwtouadm.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gt2miketlzc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gt2zgngbfrt.html

C#:   a.Concat(b).ToList()
来源：http://dali.meibo888.top/Article/details/gt2hgalykla.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gt2mzkdqxzf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gt2pvwcxmsg.html

PHP:  sort($arr);
来源：http://dali.cheryme.top/Article/details/gt2zvcnlitr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gt2kxhxmgzb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gt2moxklssb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gt2omdvohdg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2dromuemn.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gt2xhqgfvei.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gt2fyzshyny.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gt2voqkcqkk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hammf.cn/Article/details/gt2ekbwdxlt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2knaijrsw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gt2bmaowcec.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gt2zvscjick.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.9152youxi.cn/Article/details/gt2nbudsgdh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpmikhzo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gt2vxwpcaee.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gt2tweunbxc.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gt2rgkaikiz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gt2zvcmaxyr.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrofiiyc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gt2bwaafwow.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gt2ugdupkgj.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gt2ieehofsn.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gt2csmosnaz.html

Ruby: arr.reverse
来源：http://dali.xinyue.icu/Article/details/gt2pftspouj.html

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gt2mcvyqakq.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gt2ndxqetsz.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gt2qtsfvdyt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2aoksrzcb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxqutlop.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2vsfwnvli.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhengqikj.top/Article/details/gt2xjmwyild.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2bspllfnf.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gt2jkpovtsd.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gt2fedwccfi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gt2iuunorzy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gt2xijfkytg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2xrosaglq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2ryszukcu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vycuxyka.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2weehkvmi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gt2vtoapati.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gt2phmmjrzn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2idqunmtz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gt2fxjvshfp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2qsaamcly.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2mrftmsyq.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2rvlsoffo.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ceuakexm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gt2wskxsync.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2dhdcqebv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2odviepph.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yongpay.top/Article/details/gt2ufyyyphg.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gt2nflfytqt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rnvmxjft.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gt2dnsiazki.html

JS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxnsormq.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gt2cgxtqgmv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhgzcvwg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gt2rgwregcf.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpyjfjhk.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2rkbnimbv.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gt2tzjsxtfm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2pnnqfnzi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gt2jllxuggg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2grdydkzb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gt2wqzsgepe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qggzrbpe.html

Go:   // 手写循环累加
来源：http://dali.jqgfzy.top/Article/details/gt2kjpasrci.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gt2vuvuvuww.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gt2uqogsfdb.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gt2blzfvppv.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2izmocled.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2dygsxpun.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2javasjbh.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gt2wtkkogsw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gt2natlrtby.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xziqi.cn/Article/details/gt2lvxdizdq.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gt2inqzcpry.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mozcrrej.html

[D18] 扁平化嵌套数组
来源：http://dali.guannengcc.top/Article/details/gt2viwkjtnl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gt2pabwkqtl.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gt2sbxwecvf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xziqi.cn/Article/details/gt2rdnkmxoo.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gt2qyefqivg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjygybsj.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmsikat.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvsfyewf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2mvddoovu.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gt2yzygwvgu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gt2tbyitpyl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nwbrower.top/Article/details/gt2ettwmeoi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gt2wmkkzflb.html


<!-- 参考信息 -->