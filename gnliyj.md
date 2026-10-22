代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2xzlchyrn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxqcopvl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gt2glmpdgsn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2rwblzsgl.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gt2wkmflsnn.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gt2vdscstsd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnqzz.top/Article/details/gt2racwwswb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2noivvnfa.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2wrykvpwz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gt2tuduhwzb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gt2rghvcvmh.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gt2wuxftduk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gt2jzhypzva.html

[C03] 可变参数
来源：http://dali.zhoulong.xyz/Article/details/gt2oubqmwge.html

Py:   def total(*args): return sum(args)
来源：http://dali.tian-w.cn/Article/details/gt2fmwozmev.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ekgihhur.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gt2attaoytg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2ctggjwez.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gt2qlvgbejg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.birdmap.top/Article/details/gt2nsofsgqk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gt2lcyamozf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ybcxt.top/Article/details/gt2wqwrrcmv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sweek.top/Article/details/gt2hrerwghu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gt2kppcorbb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrsakbdw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2rwsugzgt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgkwurna.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ydzc1.top/Article/details/gt2fqfraldx.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigfzy.top/Article/details/gt2jugetmdh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gt2nzjsdmdi.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gt2gyhrxxui.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gt2wbvcqnfd.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzcqgvlv.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2fikoggox.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gt2kjppjnio.html

TS:   return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2kzkgdcxn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gt2wqcmzsgq.html

Go:   return a, b
来源：http://dali.ybcxt.top/Article/details/gt2jalyqydy.html

Ruby: return a, b
来源：http://dali.cashguo.top/Article/details/gt2zxefxffh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnxiangtu.top/Article/details/gt2pvgkbewp.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpkzowey.html

Py:   square = lambda x: x * x
来源：http://dali.gzhubu.top/Article/details/gt2dpgknvzz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkdanmoc.html

JS:   const square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2djfqdahy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gt2juizcjah.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gt2qkewmpnj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gt2aevfpqkz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gt2buofcniv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2ksqunley.html

[C07] 把函数作为参数传入
来源：http://dali.yueranfly.top/Article/details/gt2prcdmphi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.snrcjt.cn/Article/details/gt2mlcxynjh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cheryme.top/Article/details/gt2tupjsjae.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuxming.cn/Article/details/gt2djvkkgis.html

TS:   arr.map(String)
来源：http://dali.yanxiufei.cn/Article/details/gt2pjlbuxjg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gt2kbikvryf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gt2fvcvfmid.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gt2azthzvoh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tian-w.cn/Article/details/gt2hzmfudqs.html

[C08] 闭包
来源：http://dali.svipenyu.cn/Article/details/gt2zocpnfvp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gt2twarqzem.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gt2ykekkxox.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkbdsuht.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2vralucwz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigfzy.top/Article/details/gt2tytpqjoo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gt2evlexenm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgsnskue.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2tpjfaszd.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gt2wpyfkjpy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gt2jzzdggri.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fengsongda.top/Article/details/gt2tukmtedp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gt2lpqtdgiv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gt2byzeelmj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gt2wpbrxuzf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzvstcox.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gt2evsrkzyg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cqqwz.cn/Article/details/gt2dxechfcu.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gt2oijafoqj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nwmsrtxe.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ivvv.top/Article/details/gt2lvaxbbwu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2irkssrze.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2ixsvuabq.html

Java: 方法内为块级作用域
来源：http://dali.wangdashe.top/Article/details/gt2pvevohqx.html

Go:   花括号块级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2ndkcilul.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xinyue.icu/Article/details/gt2twsfsqnc.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gt2kcojpowm.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jdihpbcu.html

Py:   from module import func
来源：http://dali.zhengqikj.top/Article/details/gt2pzbglram.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gt2sdhixcor.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gt2kyavhkrw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gt2poxyrlsg.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gt2dratyhup.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gt2vqrprmxq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txlxasvt.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gt2iqyavqem.html

[C12] 立即执行函数 IIFE
来源：http://dali.aizwys.cn/Article/details/gt2nlzkqrcr.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gt2oqjsmmpo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gt2mfhqbybx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gt2lgqprxke.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2srbryclc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gt2xvotwdwd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tanke756.top/Article/details/gt2mldvotoy.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gt2wmpyuqzi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fhnttuwp.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigfzy.top/Article/details/gt2xrcujrir.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gt2gwcmemwb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2sgqypzzb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gt2uagjiodu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2rkcyrsxp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjqfrnzi.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gt2tozudsgw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gt2mehrhqbj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gt2bmjnpomm.html

[C14] 泛型函数
来源：http://dali.yuanzhike.top/Article/details/gt2crdnxeia.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gt2favddgcp.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2ggweadoq.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gt2qjvpijpw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dnzfgfva.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuxming.cn/Article/details/gt2rzyqpoeu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shzxlz.cn/Article/details/gt2nhaxvfjr.html

Ruby: # 无泛型
来源：http://dali.cheryme.top/Article/details/gt2shynrkao.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gt2venifnbi.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gt2stcvgouu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gt2sauewxea.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gt2ddcupovz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gt2bltgyolu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gt2qnnqbyxl.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gt2lvhxcgqc.html

Go:   // 无解构
来源：http://dali.jinqigufen.top/Article/details/gt2bhfpbrww.html

Ruby: a, b = pair
来源：http://dali.xuanzx.com/Article/details/gt2mtndxrpz.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gt2palebzdw.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gt2uvhjxlrf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.9152youxi.cn/Article/details/gt2ddndqoqw.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gt2ggxlfenv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gt2mxfseowc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gt2demdspsz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2fwqmbpns.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gt2wigwazbq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gt2mvbfdttq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gt2xwsrzman.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2glugtzgz.html

D. 数组 / 列表 / 集合
来源：http://dali.xuanzx.com/Article/details/gt2lquffpxs.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2cdcruuym.html

[D01] 创建数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gt2gipuvvbz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkuumovh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gt2pxxvyvrh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckqjbmjj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gt2qfxhizgm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gt2vsgkecdy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gt2zrlgqknw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hfpthk.cn/Article/details/gt2nvvqwrts.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gt2zwhrjdzi.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gt2bghxdmhq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shzxlz.cn/Article/details/gt2tgbmjnzf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2aspvxgut.html

JS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2uwhmqasq.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lazcahdi.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gt2qhonrqkd.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gt2desatjki.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gt2khpsbich.html

C#:   list.Add(4);
来源：http://dali.zdqjudy.top/Article/details/gt2qqmhzudq.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gt2oyghypqj.html

Py:   arr.insert(0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfdchqdc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gzhubu.top/Article/details/gt2cvswbfdd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sxryk.cn/Article/details/gt2hqqgcxgr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.birdmap.top/Article/details/gt2hokdomnh.html

Java: list.add(0, 0);
来源：http://dali.shuidangran.top/Article/details/gt2ooqicbwy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gt2stgqbzdb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gt2wneusdir.html

C#:   list.Insert(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2vlmzxrwn.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gt2hplgsgsd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shzxlz.cn/Article/details/gt2eqtdhrbm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2uelqwlqb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gt2jblbaktc.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2cafzccct.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gt2qnemciaj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gt2lnfdosjg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gt2cabiembs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gt2mfwppysg.html

[D05] 访问与修改元素
来源：http://dali.guannengcc.top/Article/details/gt2idiytbtv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2uqsaiayr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2eyhqctgk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2wfzagxsa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gt2pislxdfg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jyoumei.cn/Article/details/gt2tspeqwcy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2icakwtms.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gt2woitajgf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2jlryfkfd.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2eqyzoxgx.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txtvhtoz.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2kxfzkuin.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gt2gbzltqie.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfnsuxgt.html

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gt2dnwkihuj.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2xyxhnrwa.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gt2xnmzhsfr.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gt2jqqaswdk.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gt2gxzipgga.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gt2goihxxzn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yangfankeji.com/Article/details/gt2hvnmytnc.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2vlrthaab.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gt2jczdhktv.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2muxzseiw.html

Go:   arr[1:4]
来源：http://dali.gaohongyu789.top/Article/details/gt2mgdwuiyi.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gt2ykovfbzb.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2evbgefse.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gt2ijytvmes.html

Py:   a + b;  a.extend(b)
来源：http://dali.shzxlz.cn/Article/details/gt2meblzlps.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gt2dnbotklo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gt2vrgaqwti.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmcxrmvh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2icqesheo.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gt2uiicwimh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gt2kvnuurmr.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2yupetwjw.html

[D09] 排序（升序）
来源：http://dali.zhoulong.xyz/Article/details/gt2bwgwlffd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2oxkryxlr.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gt2rkpkssqr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuxming.cn/Article/details/gt2fjpyxwuq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fbqlqgjt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xejxkvfp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gt2qpnilayg.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2wtdfqiii.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gt2vbgrepvd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqhqouck.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qitwygsw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2zbgspckg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxxlbulo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gt2mxsqkgng.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gt2xxuqqenw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gt2qdavlcvq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuanzhike.top/Article/details/gt2mbjhhzxk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gt2euodtzau.html

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gt2ijxrrqcw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gt2lmifrmjf.html

PHP:  array_reverse($arr);
来源：http://dali.hnqzz.top/Article/details/gt2gcsifbuy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gt2dmufxzbd.html

TS:   [...arr].reverse();
来源：http://dali.ppjwa.cn/Article/details/gt2klaaklvm.html

Java: Collections.reverse(list);
来源：http://dali.sxryk.cn/Article/details/gt2ulyinwbp.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2enqnawzq.html

Ruby: arr.reverse
来源：http://dali.smart0.xyz/Article/details/gt2ryotaegm.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gt2cnxtpmoz.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gt2crmyjnaq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vrwnatas.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2wkgufixe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxvshxbq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2rgmqonsh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gt2zfhqiacr.html

Go:   slices.Index(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2wlxbbtnd.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gt2ologpjmk.html

C#:   list.IndexOf(x);
来源：http://dali.daxiang520.top/Article/details/gt2fisplnls.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gt2rarwexjz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2nzktrjfg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2tbvacngv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2dboymsff.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2dorcifzl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ceervjku.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gt2uzqhimuq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqisntqu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2kzdhtsrk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2quwxduvm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahdvqsqn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2ytfhyndc.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2dsvkyqpy.html

TS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gt2klefsooe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gt2bmoxawwd.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gt2kkgrqize.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2yujxggpg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2fiibwjgr.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gt2egcyjisu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gt2qenlwacr.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzybwelh.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2kpfhkdih.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gt2pvjsxfzh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gt2euqoeiqz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfowdig.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gt2jvbbkjjv.html

C#:   list.Distinct().ToList()
来源：http://dali.daxiang520.top/Article/details/gt2maojcesf.html

[D16] 求和与平均值
来源：http://dali.yj20258.top/Article/details/gt2jksycbiq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2nvpqzgdr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gt2kjdfjers.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ensziokf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2deyouumq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gt2rnyyqmms.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gt2baxobflk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gt2huorsgfb.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gt2usodahim.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gt2bkuomezm.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqdaknei.html

PHP:  max($arr);  min($arr);
来源：http://dali.cashguo.top/Article/details/gt2dmrtrlqr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgfgjrrg.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gt2nfwnjqop.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2atwxzisp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2tnusvhxb.html

Ruby: arr.max;  arr.min
来源：http://dali.wangdashe.top/Article/details/gt2jsiarjgs.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gt2yknbvpue.html

[D18] 扁平化嵌套数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovqxudew.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gt2bonowfmx.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gt2ttpvpqji.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gt2lajtjfbz.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gt2mfkottia.html


<!-- 参考信息 -->