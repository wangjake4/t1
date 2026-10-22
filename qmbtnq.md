代发 wailian999

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gt2jteooggi.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gt2rjfmcdkf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xebqotoy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2knydbcpw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2otegdnrd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gt2uherkxsh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gt2arbrheja.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258888.top/Article/details/gt2kzuulqeu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj202588.top/Article/details/gt2ffhfrsfe.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gt2vncevbwu.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gt2bdtegyse.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ybcxt.top/Article/details/gt2jbbfzbiq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2pzavprwo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gt2myqemfon.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnqzz.top/Article/details/gt2tufaazfg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htsnrftp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhengqikj.top/Article/details/gt2kiconqgx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tianlin.xyz/Article/details/gt2poidejtk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhakmkwr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnqzz.top/Article/details/gt2cknnreyt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gt2bnjucobg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2btdylvvy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxgmixih.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pycfn.com/Article/details/gt2uqvjnwfk.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenzaomai.com/Article/details/gt2cfozdxdz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2bbmpainz.html

C#:   f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gt2mevbtubj.html

[C05] 返回多个值
来源：http://dali.vqdsnc.cn/Article/details/gt2tcgmepak.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gt2fxdatoux.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gt2sxaekrvw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gt2cqjiaqyi.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gt2tswltqay.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvhjibli.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gt2sdathuir.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gt2phpkhdvj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcaejmoi.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gt2cpwrzsrg.html

Py:   square = lambda x: x * x
来源：http://dali.zhiwuduotai.top/Article/details/gt2txmlvblb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gt2pyeunbux.html

JS:   const square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2plakswon.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2euzrypqo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2sqabtqwe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gt2sskpigrs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sysykeji.top/Article/details/gt2svczhupd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2oayohpme.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gt2mptqwqeu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gt2qzepjaiw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2zivgoxln.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtdvywpq.html

TS:   arr.map(String)
来源：http://dali.zhongyouzk.top/Article/details/gt2opjjglfe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2mvmakfsf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gt2zsdqdwji.html

Ruby: arr.map(&:upcase)
来源：http://dali.cashguo.top/Article/details/gt2jmxnpnpc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenzaomai.com/Article/details/gt2auqacfaz.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gt2yjiufaan.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gt2kpsiizpp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gt2ojsralxb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jxcmphcf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2gojfpnxx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.feifeiyinyue.top/Article/details/gt2smjobwdy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.316326.xyz/Article/details/gt2etbtgssa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shzxlz.cn/Article/details/gt2szjbghma.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gt2redacqyh.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gt2bjwjdyer.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gt2qpdgkhsf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jolmatgp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzapvkkj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gt2gucoiwhv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cashguo.top/Article/details/gt2kecznvkk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuxming.cn/Article/details/gt2sxlhlcqs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gt2zyjvhhwc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.smart0.xyz/Article/details/gt2hocskfcu.html

[C10] 变量作用域
来源：http://dali.redwolf501.top/Article/details/gt2xvidvrmw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gt2nzsqajod.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gt2fmfyuyew.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2vpbbzfiw.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2lybqzbck.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwejchaz.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdxiacae.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gt2kzdbfsea.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqxoqwth.html

[C11] 模块导入与导出
来源：http://dali.fengsongda.top/Article/details/gt2hbsbcebt.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gt2ovlzotsp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tanke756.top/Article/details/gt2wqafvcst.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gt2htikmhyl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jiagoushi.top/Article/details/gt2mawmrtus.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gt2vtqnmlwj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sufxvd.cn/Article/details/gt2fiffzxtd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gt2kxfddxdm.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gt2hzrapxhv.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gt2wzhlvisj.html

Py:   (lambda: print("run"))()
来源：http://dali.chenlongwang.top/Article/details/gt2dtgbdbsg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzgzalha.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gt2tgcvrepr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gt2bqzsfrbl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gt2irdyrdij.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gt2qtyptxnu.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gt2lktrrwdh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyhntbeg.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gt2crkprxok.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gt2mnmwnhzj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2alsqmtxo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndanbfau.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2bkfqzehy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2kbopdzyu.html

Go:   func add(a, b int) int
来源：http://dali.xziqi.cn/Article/details/gt2kdkfopbc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gt2xvznrakb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gt2yhmdupmn.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gt2jzujdmyk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ehwqpu.com/Article/details/gt2snadutwq.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2vlawhrud.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gt2uvjmrqxh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gt2kvungcet.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gt2bruteycu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ehwqpu.com/Article/details/gt2sbwtbgda.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gt2pnpzkjqv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzbmrauy.html

[C15] 解构 / 展开参数
来源：http://dali.smart0.xyz/Article/details/gt2zzuksozk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gt2tgexnouc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shangyingyoupin.top/Article/details/gt2olmujcnv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gt2axjlcjru.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fengsongda.top/Article/details/gt2euxrnrgx.html

Java: // 无解构
来源：http://dali.cheryme.top/Article/details/gt2vnyjxuaq.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gt2riclnvjs.html

Ruby: a, b = pair
来源：http://dali.hnxiangtu.top/Article/details/gt2jszfszvn.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gt2hvjgscbu.html

[C16] 函数 / 方法重载
来源：http://dali.havefunace.top/Article/details/gt2fijqitku.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gt2gdqcjutm.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gt2rkspyzwz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jyoumei.cn/Article/details/gt2xobenvkn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gt2nixasgct.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gt2vejchhpv.html

Go:   // 无重载：用不同函数名
来源：http://dali.kuanghao11.cn/Article/details/gt2hlfesxzb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gt2etngtimc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yueranfly.top/Article/details/gt2oauwujub.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2tysfrpfk.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gt2kwcckumv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2azpobjks.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gt2oawpsdkx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xylfe.cn/Article/details/gt2ugiyimll.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gt2ibzjhpfx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gt2bezfxqha.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gt2ukwvikvs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gt2ckpzxguw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.316326.xyz/Article/details/gt2cwrpqqeq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqgwcuvx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gt2kiecfeps.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gt2kzinmcwr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjndlfxu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gt2xnnzpnhq.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2aaqizbyu.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czuvhmcf.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gt2wjbpoiwt.html

Go:   arr = append(arr, 4)
来源：http://dali.havefunace.top/Article/details/gt2mjdilpis.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jiagoushi.top/Article/details/gt2uheveoxi.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gt2tsairrmx.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gt2pfegvwxk.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gt2mljofdtv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gt2cllualfw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gt2ovqxizbi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gt2uygidaqn.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gt2jrkzqfau.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usoysxay.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.0kj1m.cn/Article/details/gt2xszwtfln.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2gpculwvh.html

[D04] 删除元素
来源：http://dali.fengsongda.top/Article/details/gt2cbupppph.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dianchejie.cn/Article/details/gt2acnvcuvz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozqcuyhs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gt2hinfsnwq.html

TS:   arr.splice(0, 1);
来源：http://dali.yonumen.top/Article/details/gt2dkxagnbr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gt2pdmyqeew.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gt2dylaofqn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gotoacloud.top/Article/details/gt2wqauxlfr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cqqwz.cn/Article/details/gt2enhiogwf.html

[D05] 访问与修改元素
来源：http://dali.yangfankeji.com/Article/details/gt2phqrxxfb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2esoywtxg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2xyzjihuj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gt2xfhxqodq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gt2hqnyighb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.svipenyu.cn/Article/details/gt2bkzoaogh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2guldkjen.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhzlnezt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sweek.top/Article/details/gt2tznrhvfr.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2owbofxix.html

Py:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2dqcfewjn.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2tavkbhyu.html

JS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gt2mdlsoqhq.html

TS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gt2gjjmhizv.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gt2olhqpeqt.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2cltjnnox.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gt2hxoyrwxm.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gt2afnyiwvh.html

[D07] 切片 / 取子数组
来源：http://dali.haohaochexian.top/Article/details/gt2sloymxln.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gt2dwiekhum.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2bpiwxqdp.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2vupfwslx.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gt2ynvrommx.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gt2vvbefjcn.html

Go:   arr[1:4]
来源：http://dali.hammf.cn/Article/details/gt2mtvwqvim.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gt2ovctnqew.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2qcyyhwov.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gt2vyzonrqh.html

Py:   a + b;  a.extend(b)
来源：http://dali.cqqwz.cn/Article/details/gt2cctzrbls.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gt2odzwobdf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gt2pbaquxok.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gt2qnmmlpuu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gt2thfriymk.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gt2ylleyuzy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gt2gnzloajn.html

C#:   a.Concat(b).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2zvojqttn.html

[D09] 排序（升序）
来源：http://dali.zhoulong.xyz/Article/details/gt2iwmtkhjd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbfsvpzg.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2eimzvisp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gt2hdfgewrv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gt2cplonshn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuanzx.com/Article/details/gt2xgwkiqoz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gt2quxjcxar.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2mwxozpwe.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gt2ixzeufel.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gaohongyu789.top/Article/details/gt2wegxwddb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gt2eunhqtyc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gt2sbfrxyir.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gt2sryvtcdl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gt2ofksuyrg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gt2joslwvrg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sxryk.cn/Article/details/gt2axtvneyv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gt2llynhgdo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gt2ombskklp.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gt2nubufqpy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gt2hydgybey.html

PHP:  array_reverse($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2agwqvzxf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gt2jbjcolkr.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gt2fjmpcosf.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2hvmioxxu.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2qulqpzet.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2lgocjtze.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gt2gwgrogff.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gt2ydxxtznc.html

Py:   arr.index(x);  x in arr
来源：http://dali.ybcxt.top/Article/details/gt2gdtjbmvx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2mjcdovlh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gt2ufyajycs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gt2idwdiwgr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gt2qygwffqj.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2njshyfeh.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gt2rgezqcwr.html

C#:   list.IndexOf(x);
来源：http://dali.daxiang520.top/Article/details/gt2zkiyujsn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gt2piuophvk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gt2pgwanxwz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gt2mmtwmzcz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2mdoinbgz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gt2qsndwpyc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shuidangran.top/Article/details/gt2uahpdaia.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gt2vstyyrbo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gt2jcswcxpd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gt2jpfilhil.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gt2pihiigbq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2xtofcury.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gt2nbysurdw.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2lxmhcafc.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2dkdxpydm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gt2lyqzmgro.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gt2lopapdet.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gt2tpsswvrr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2uwyuurrk.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gt2kgorqzqd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gt2gpgevxic.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2pqqslobk.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2tbqpjkcs.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2jhizhblh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gt2wpiqeims.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gt2ynxgmook.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gt2tqvanfxy.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gt2vstkkpjf.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gt2gnxzdxee.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gt2obbakcuu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gt2vijhmgsk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzgkubmh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2vriltxtk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gt2lfxafxtq.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gt2waiqyiyh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gt2oqjgrbsf.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gt2myrkjcih.html

[D17] 最大值与最小值
来源：http://dali.zycfv.cn/Article/details/gt2hwlankor.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gt2aehdpwrk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2gfkuggyh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gt2gvlghyzl.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gt2huvpfsis.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gt2czruxnuq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gt2kvgxxzph.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gt2ncueamgt.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gt2wnaxjwmi.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gt2wmhoyvmu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gt2kkpoqsvk.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptsejrmp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dashuyun.cn/Article/details/gt2udscybsg.html

TS:   nested.flat();
来源：http://dali.zdqjudy.top/Article/details/gt2mqdlpycr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unztwrus.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2sotvsaae.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gt2headfpty.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bejfgtfr.html


<!-- 参考信息 -->