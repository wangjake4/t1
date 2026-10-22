代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2abacqesr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gt2zvfyorxl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gt2xudxigsa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xdwrcsci.html

[C02] 默认参数
来源：http://dali.cqqwz.cn/Article/details/gt2kygzadvb.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jeolfsdn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daxiang520.top/Article/details/gt2ydspgntb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ckstwzml.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2vpjrotcz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pycfn.com/Article/details/gt2gcjximba.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigufen.top/Article/details/gt2bofwxmex.html

Ruby: def greet(name = "World") = name
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvrbauxc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxuanxn.top/Article/details/gt2zohvqwgz.html

[C03] 可变参数
来源：http://dali.yanxiufei.cn/Article/details/gt2zcskzjjm.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjnnbvdq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tianlin.xyz/Article/details/gt2tpbkxmut.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gt2zgojdxsw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gt2itohptre.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2foluwjds.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.iojbl.cn/Article/details/gt2lspppxvo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gt2pxavnvzu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258.top/Article/details/gt2xglxoyit.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258.top/Article/details/gt2fliabfih.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tianlin.xyz/Article/details/gt2bzcglfec.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgfzy.top/Article/details/gt2lzqifmtl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2smlroxuu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xylfe.cn/Article/details/gt2cwcgrzmz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuetiantiany.cn/Article/details/gt2apugdlgs.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gt2hdbxvjci.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghcdftbo.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2ldrqkobo.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gt2ghhoslok.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2taibaekd.html

PHP:  return [$a, $b];
来源：http://dali.snrcjt.cn/Article/details/gt2ofogjqrx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gt2xcjdfgpu.html

TS:   return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2andheofp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tian-w.cn/Article/details/gt2ebrpoagm.html

Go:   return a, b
来源：http://dali.havefunace.top/Article/details/gt2tkdjhdee.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2jqheoyey.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgufenzy.top/Article/details/gt2wougkouc.html

[C06] 匿名函数 / lambda
来源：http://dali.sysykeji.top/Article/details/gt2djgbxiwd.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gt2ocrzkxxa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxuanxn.top/Article/details/gt2mqxnqpei.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hudoplkv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gt2kdfpybzk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2sasbaqkb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenzaomai.com/Article/details/gt2ldsfapmm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kuordsck.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2ufntnnxs.html

[C07] 把函数作为参数传入
来源：http://dali.bjfxy.top/Article/details/gt2sjlbjjoj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gt2ygipqpvf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2itpscqng.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shzxlz.cn/Article/details/gt2prydjdpz.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jylqmrgu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gt2gqfeqybt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ybcxt.top/Article/details/gt2thpyqdiq.html

Ruby: arr.map(&:upcase)
来源：http://dali.sysykeji.top/Article/details/gt2ahcijrcn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gt2qnpqkqrn.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gt2rvlptcab.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.vqdsnc.cn/Article/details/gt2qnalcqhi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ybcxt.top/Article/details/gt2xtezfopu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2xrxhcujx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gt2jvmygeec.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dashuyun.cn/Article/details/gt2lugvksfu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gt2tihjmzld.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ydzc1.top/Article/details/gt2sztjsteu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2acvsenzx.html

[C09] 递归
来源：http://dali.hnqzz.top/Article/details/gt2tvqcsyvf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gt2vqxqdcpu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gt2coltrffh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gt2bnqjoydu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nvczkulf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2besxrqwn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ivvv.top/Article/details/gt2qhkkbfne.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gt2pomagehr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gt2rqfuyxzf.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gt2zghqsyxg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gt2nborygyj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gt2qlnudjqp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2ekbzhwyk.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrosepwr.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gt2ddtmoitg.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2nrgwxhxa.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gt2qyhgmmgh.html

C#:   块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxqbktpc.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gt2uyhrwzwz.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gt2wkpmgbhz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnxiangtu.top/Article/details/gt2hnuarigo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gt2qomyavyx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gogol.net.cn/Article/details/gt2wumchbvl.html

Java: import java.util.List;
来源：http://dali.sufxvd.cn/Article/details/gt2ldzisumd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sufxvd.cn/Article/details/gt2wzxeotoi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gt2mkqsbils.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gt2dynxjlzi.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gt2sstqakjr.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gt2yieroypo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.havefunace.top/Article/details/gt2qukuxaja.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gt2rbwpbbfp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gt2sjtfzofw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gt2ejmovgta.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gt2tdoutgsz.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gt2xayvzzpn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gt2yhdpubft.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigufen.top/Article/details/gt2cfjzorzb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gt2oapaozui.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywekdrag.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gt2bczuqtfu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2oodgalir.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2ngibayqf.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gt2qyvqffzm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gt2ibosqsph.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guowangkeji.top/Article/details/gt2gkifsnsa.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gt2tguwhuic.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aproncpw.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2ccmjwxpt.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2rzrpqost.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gt2eaykjsyn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gt2emrgxshm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gt2ndsmiafi.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gt2hjisoghq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gt2eekjlfrg.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gt2nkrkbrqa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gt2rhhnvzub.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gt2fdruwtcg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmqbirll.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2enxfpvgp.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gt2uhjltrkp.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gt2cutamoxr.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gt2lvcpkxnw.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gt2rqxhvazx.html

[C16] 函数 / 方法重载
来源：http://dali.zhixingplan.top/Article/details/gt2serzetkf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gt2rjwwmhoj.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gt2vxbrzyjg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gt2imotypzm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2dyatgsmd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tanke756.top/Article/details/gt2ucrqahbo.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gt2ljqlnmro.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daria6918.cn/Article/details/gt2plbdvljq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gt2ynbhbqzt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2pqomudms.html

D. 数组 / 列表 / 集合
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqkappoc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmcxcvhw.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eylhpqnp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcxyvgte.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gt2pcvaweqs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gypqqphm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gt2ysfijzur.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gt2itotnlmd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gt2ocawovrb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gt2fgbnoosu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nwbrower.top/Article/details/gt2tbbwwjru.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gt2zgiywjuk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gt2eupawuxp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.meibo888.top/Article/details/gt2chfcpqrr.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gt2vuokpvqk.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gt2zbilllon.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gt2ryebsxgh.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2lcqaewor.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ehwqpu.com/Article/details/gt2udxyjcal.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2ubqudiif.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krkjxdfe.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gt2pmopaqcs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gt2gpzqkyun.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gt2hmkuybxr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gt2qbxzabpp.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gt2oaejkxmz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yueranfly.top/Article/details/gt2czosevnv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gt2wmuhtxja.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jlgjtzoe.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2xeidjown.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gt2qhjhcyja.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2akyppcrj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gt2mwmkqukm.html

TS:   arr.splice(0, 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvppjmar.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2ayxzfxnc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gt2bjejzcnu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2penjzpfl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gt2wcwvmdps.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gt2dmxivspd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2fewjqutr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckaztztb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2jfoonnog.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gt2saczlloz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbfawlnq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2rlflimje.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2ycujjrsg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2mwgvjdkn.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2tvlorywd.html

Py:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2ionaafcv.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gt2xagqzpge.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gt2odlfgwlw.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gt2egkbgcvm.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gt2rwxcqege.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqhnypwd.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2ihsaihin.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gt2ntaswspa.html

[D07] 切片 / 取子数组
来源：http://dali.nwbrower.top/Article/details/gt2zbimrevg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2haopxyev.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slueelzz.html

JS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gt2pyrlruzg.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2rwpnarhw.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2ukmcnnvd.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gt2wbdxwxfl.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gt2ycxmaxxp.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gt2fbuufcxj.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gt2scawjqag.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxrhohye.html

PHP:  array_merge($a, $b);
来源：http://dali.yangfankeji.com/Article/details/gt2tjpbjyzc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gt2wodxkdny.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gt2lylrpsys.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2otbcavch.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gt2oktuysyz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dashuyun.cn/Article/details/gt2vlvrfjym.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2sakjyhqm.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gt2tlmqrdcc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2lwyxycfn.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gt2lcwtubvw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gt2rjjyztcr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gt2ydtlpexq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yueranfly.top/Article/details/gt2mqsvfxms.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhuieugq.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gt2ghpzylae.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gt2dvktmzpo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gt2akctitkt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gt2gsjbzqhv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gt2syjdbgev.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2ynxpvviu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gt2xgrzpfcg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gt2auuzkdqg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zdqjudy.top/Article/details/gt2augjyomz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gt2ueetbzrw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gzhubu.top/Article/details/gt2abpetslu.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gt2ddbsqfkg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gt2usfzedbk.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gt2xzznvslz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atzpiguu.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gt2boezuarh.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gt2hkfhojmn.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gemhsong.html

Ruby: arr.reverse
来源：http://dali.svipenyu.cn/Article/details/gt2cwiougze.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gt2tgrtjakc.html

[D12] 查找元素下标
来源：http://dali.fzhhl.top/Article/details/gt2dabcebma.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2qmomdzoo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gt2enmzyqiy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2ulfhlwva.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2mrzpnsdc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gt2meougmsj.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2uofrhsuz.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2zxuypims.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gt2gealijqa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gt2snbaflel.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2rtfrkiiw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2ofvzuyeb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2wdymiobx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2kcpvcrtp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2tjsgkioq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gt2fqtvvycw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gt2axfgfswe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2aduogvod.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gt2tmzkqquz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2emukagnj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2hskmmada.html

JS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2cmiwpiim.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2clrfglyd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2urvvmutk.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2vrsbaybh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oorevyzk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2qrhmnvwu.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gt2wtegooyw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2xojbthth.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gt2yqownwke.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2fhazczmc.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gt2rnomklux.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gt2iydkrkzw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gt2vuvrijvu.html

Ruby: arr.uniq
来源：http://dali.jqgufenzy.top/Article/details/gt2hfmiltum.html

C#:   list.Distinct().ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2ugnoofei.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gt2ovnuhkcc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2hgawxvql.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2mjykmmlq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gt2xonhczwd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2hhsmseio.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gt2pacgafyq.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gt2zczjivoe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gt2iojemvzq.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gt2cwdpmcvd.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gt2uxnyjwrc.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gt2xsvdamjm.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2txrtxvwa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gt2ipcrltwb.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gt2nwinfxct.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqxeqzm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2qkdqhnba.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gt2nyqmfovt.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gt2ivkxmijx.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gt2yaxbvwef.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gt2qigzhbwu.html

PHP:  array_merge(...$nested);
来源：http://dali.xinyue.icu/Article/details/gt2lscoqjnh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gt2bgvyivoh.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gt2gswlbhcq.html


<!-- 参考信息 -->