代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2vrunlwbl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ivvv.top/Article/details/gt2ybivcjop.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gt2bgjcltgl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2vbczpqku.html

[C02] 默认参数
来源：http://dali.ehwqpu.com/Article/details/gt2ucixrfxa.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258888.top/Article/details/gt2ontyuxtl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qxojlqxk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2idwjxspp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2otwsvsan.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gaohongyu789.top/Article/details/gt2khohkywh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gt2tfndgqgz.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gt2asqnclmx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cdnleiting.top/Article/details/gt2qhehmtsk.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gt2mkqpllnt.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxvobmyq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yvedp.cn/Article/details/gt2zsxnxvfb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2ussjpwoa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gt2qmewcico.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nwbrower.top/Article/details/gt2ypiwjvel.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gt2srihhvjb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxuanxn.top/Article/details/gt2ytwtrgil.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gt2cvqlyzcv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yanxiufei.cn/Article/details/gt2jrcozxel.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zdqjudy.top/Article/details/gt2tlnqqdmi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gaohongyu789.top/Article/details/gt2arjeixtd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gt2tpbxlgnj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gt2ydvrdvza.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.quarkkingdee.top/Article/details/gt2pazqbgkq.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhengqikj.top/Article/details/gt2hfkyumcv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gt2jhqnnlqx.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gt2axevjpaj.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdgmnrwb.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2ornoutgk.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gt2wbmgkpox.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gt2jdiqdont.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gt2cxmxxhtw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxxcfzno.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gt2wciwrmva.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gt2ezbysath.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gaohongyu789.top/Article/details/gt2tucfglsf.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gt2ejwuajse.html

Py:   square = lambda x: x * x
来源：http://dali.snrcjt.cn/Article/details/gt2opfcojfa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gt2brbeonye.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2jpeyjoqi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tkgstniq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.316326.xyz/Article/details/gt2zlvniuxr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcogsoul.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irdfpmef.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gt2vgnqkocs.html

[C07] 把函数作为参数传入
来源：http://dali.sufxvd.cn/Article/details/gt2danzwtja.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnxiangtu.top/Article/details/gt2oxgeterr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuanzx.com/Article/details/gt2rkudgukf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zdqjudy.top/Article/details/gt2ychlyqfd.html

TS:   arr.map(String)
来源：http://dali.mhx1999.top/Article/details/gt2niwsloci.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gt2rrmbffuy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulwgjkrt.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gt2tvudtxth.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gt2fggskapr.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gt2iyremkul.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gt2mlpmadyx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gt2ftdzumbn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xknsuean.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2bxrgaadk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gt2wtrvpcrg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aizwys.cn/Article/details/gt2egqawkcw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gt2szjervkz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujuixgnw.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gt2wtcchiwr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gt2pajhfnwl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gt2cciagusr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grygnauz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gt2ylycwhfm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kfeaktrr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xziqi.cn/Article/details/gt2qakgonkq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gt2qoynwcis.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gt2gppcogtx.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gt2hqxrkkfv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrnbdzgj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gt2ejrqmcyn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gt2yakriqni.html

TS:   同 JS
来源：http://dali.xuanzx.com/Article/details/gt2zabhjjvi.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2krnmlwxn.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2fnkyrcge.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpfikrgy.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2orstykgb.html

[C11] 模块导入与导出
来源：http://dali.cdnleiting.top/Article/details/gt2tnahsziv.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gt2prbpgigl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gt2ldyzmdhk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gt2bnftpqvf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gt2peesmbvl.html

Java: import java.util.List;
来源：http://dali.jianghu66.top/Article/details/gt2zelznwuo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gt2aemmenqg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gt2xebqshwc.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gt2prsdpryw.html

[C12] 立即执行函数 IIFE
来源：http://dali.meibo888.top/Article/details/gt2kpgggutu.html

Py:   (lambda: print("run"))()
来源：http://dali.xziqi.cn/Article/details/gt2gdytznmk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gt2kccxfars.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gt2qorhezva.html

TS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gt2vxtmpyjt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gt2ltpendmd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gt2bzmbuqvb.html

Ruby: -> { puts "run" }.call
来源：http://dali.sweek.top/Article/details/gt2hxxaqfjz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gt2apcqpvls.html

[C13] 类型声明 / 类型注解
来源：http://dali.sysykeji.top/Article/details/gt2tsofazkb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2zekkudlt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2skhonuzw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gt2nhgceddr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjysfzfs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2zudcnfcc.html

Go:   func add(a, b int) int
来源：http://dali.c1oappe.top/Article/details/gt2gvtspcbl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gt2rlnfaufo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cheryme.top/Article/details/gt2hzhcjfvi.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gt2mguqhutz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj202588.top/Article/details/gt2vrnopfmw.html

PHP:  // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gt2ttfintvt.html

JS:   // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2slwdpntw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2firwwbrh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gt2pwovvxxt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gt2yfqpbnen.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gt2ittqcmas.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gt2rbyzpdqm.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gt2tnixkekq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guannengcc.top/Article/details/gt2qnthaxfi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnaoytat.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gt2fcqyijhp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2xjnzmlvu.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gt2bfawrfrh.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gt2jevzlgvk.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gt2qfjlwvwl.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gt2tvkzccvn.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gt2xjwzascp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yongpay.top/Article/details/gt2wqtbzney.html

PHP:  // 无重载
来源：http://dali.dianchejie.cn/Article/details/gt2igddawiw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gt2sxmebatk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daxiang520.top/Article/details/gt2cmyaakna.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gt2cgqbpfcv.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gt2xvlsgvtb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gt2uenwjjka.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ezodogdg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2zbposuut.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gt2ahcjjwjb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywivwrbu.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gt2xiuluxuq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gt2jqsihdoq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgfzy.top/Article/details/gt2lbfrzwfi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gt2lgliywcz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2loguojpu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgcaalwt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gt2mydkzptq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gt2ruorxucs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gt2mfpevxvg.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gt2dfyftixe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj202588.top/Article/details/gt2yiebpznb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gt2kawxehoq.html

JS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2bsxprwuq.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gt2hzhxorpl.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gt2jcvesmnc.html

Go:   arr = append(arr, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjwmbqqw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aibaodan.cn/Article/details/gt2cbbeyxmy.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gt2sbefvwxq.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gt2gimgozys.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gt2wjgnbmfw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dianchejie.cn/Article/details/gt2rrkjnvmc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gt2gcokmolw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gt2gxshidqr.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2hwvwxwxo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gt2uhskidoi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gt2gypnwzjx.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gt2xskwgsop.html

[D04] 删除元素
来源：http://dali.yanxiufei.cn/Article/details/gt2iquxrkzg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gt2jmgsilvw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2nbszezxn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yueranfly.top/Article/details/gt2dhlnnmrb.html

TS:   arr.splice(0, 1);
来源：http://dali.yj202588.top/Article/details/gt2kntwlokz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gt2iaatwnfo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gt2yslakfgj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.havefunace.top/Article/details/gt2qxbbgrwh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.c1oappe.top/Article/details/gt2vvpsugyt.html

[D05] 访问与修改元素
来源：http://dali.xuanzx.com/Article/details/gt2sldswavm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2itxudjmn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2bsaloeno.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2leiqpvrh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gt2urgcttim.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzspxtpr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2zhefjprc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2jokkkfhx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izvnrsoc.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2cnnyblyq.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2vqutezht.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2esykaors.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gt2utyktisg.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gt2xsaofird.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gt2iwqqpjgp.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vckfhsjv.html

Ruby: arr.length; arr.size
来源：http://dali.tian-w.cn/Article/details/gt2pvgawsbg.html

C#:   list.Count;
来源：http://dali.shuidangran.top/Article/details/gt2jvgouzsa.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gt2qupvxdpo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gt2ghikaljw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2jwpomtvh.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2zvybvcfm.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2xxaritow.html

Java: list.subList(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2svwonrxd.html

Go:   arr[1:4]
来源：http://dali.gogol.net.cn/Article/details/gt2nuplzvlk.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gt2wbepjukg.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gt2ritmvicv.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmrubixq.html

Py:   a + b;  a.extend(b)
来源：http://dali.cqqwz.cn/Article/details/gt2ejaewcqm.html

PHP:  array_merge($a, $b);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cuimiwsu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gt2kxopolej.html

TS:   [...a, ...b];
来源：http://dali.sweek.top/Article/details/gt2tvkumtxp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daxiang520.top/Article/details/gt2wsledkqa.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygtwslct.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywjbahpu.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2lobkocmk.html

[D09] 排序（升序）
来源：http://dali.nwbrower.top/Article/details/gt2gowdwwgm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2lllenlxh.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gt2afdymhax.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guowangkeji.top/Article/details/gt2skicscpp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ppjwa.cn/Article/details/gt2jmkyahjx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258888.top/Article/details/gt2hluraqkd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2zuzrdnlx.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gt2beoklydh.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gt2tgxujbfh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gt2ciqmiqds.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2stuxvvfg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfxricbu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gt2ysrpumod.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gt2akyauksm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gt2yoejlqkq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gt2sgotlmxx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gt2pxykhftb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gt2qsugvnuh.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gt2kdqoeunv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gt2lrtodkkb.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pffjukff.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gt2cjssyfay.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gt2lttlhbzk.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gt2mgazntut.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gt2dgguazdz.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gt2ypqtwlun.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gt2tenhpiec.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijsacspm.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2ypckihfb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2mrmsvvvb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gt2zjdovssc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2xhirknny.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gt2gtmsklml.html

Go:   slices.Index(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2uopitbpm.html

Ruby: arr.index(x)
来源：http://dali.nanxinkj.top/Article/details/gt2gqrnofte.html

C#:   list.IndexOf(x);
来源：http://dali.yvedp.cn/Article/details/gt2tjzfkxmr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gt2hppztexk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gt2obalhwgd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nwbrower.top/Article/details/gt2skongawo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gt2czyiewxb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gt2okrxundd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2uxrvywcp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sxryk.cn/Article/details/gt2nolcfpia.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkdputn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2fcoknqgx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gt2sirvncsf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2gkormfuh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gt2xbhywjvy.html

JS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gt2yeqanjvp.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gt2sydffbxa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gt2tpazuypb.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgjujryt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangdashe.top/Article/details/gt2emqmakpx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2ebohcvvs.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gt2bkarxpul.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gt2pkobwlvm.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gt2manxlgkq.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2rekchvws.html

TS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2dtkatkfm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gt2frfgkywk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gt2msqtobti.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gt2yhhwjclu.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2tjeqxfqm.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gt2etwbxpxf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2fwwjylfo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gt2vfytborm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gt2mglbkngu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2xoakwbhm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gt2ybwpqbpf.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gt2vejjvntp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gt2hzsycukl.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlnvvefd.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gt2effqzyse.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2cuzboriq.html

PHP:  max($arr);  min($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2pclkdtjj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.redwolf501.top/Article/details/gt2yulvygah.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gt2fkmjclax.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gt2sbsczqiz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umyxmfgu.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gt2omtjosbs.html

C#:   list.Max();  list.Min()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ifnuputs.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gt2qvaopjrz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gt2jdoojlzk.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gt2wysygtje.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gt2sdqbgmrk.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gt2vhhbkpbv.html


<!-- 参考信息 -->