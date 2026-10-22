代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2efniklgh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bblrxhgh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gt2jhnatebh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2elvdnqhy.html

[C02] 默认参数
来源：http://dali.hnqzz.top/Article/details/gt2ahpuiouo.html

Py:   def greet(name="World"): return name
来源：http://dali.yuxming.cn/Article/details/gt2ddrilygw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.meibo888.top/Article/details/gt2rqmzkvun.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2xqphpwwl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xnhwbusj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pengpengdd.cyou/Article/details/gt2oeomgiwg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigfzy.top/Article/details/gt2wpfvzczo.html

Ruby: def greet(name = "World") = name
来源：http://dali.havefunace.top/Article/details/gt2atotsrnx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cdnleiting.top/Article/details/gt2fftyiswd.html

[C03] 可变参数
来源：http://dali.ybcxt.top/Article/details/gt2dhjzulbe.html

Py:   def total(*args): return sum(args)
来源：http://dali.c1oappe.top/Article/details/gt2seikrkdf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gt2rsvrtkbd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whiivegs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gt2mimwtulv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gt2wflrcwkz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gt2dyjzzzwb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gt2pdtdnroy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gt2ldydyvgh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gt2zpagoswm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gotoacloud.top/Article/details/gt2ipzzsiri.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gt2kjssbyyz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gt2xomccptu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cheryme.top/Article/details/gt2qhhfebvu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenzaomai.com/Article/details/gt2rqnvvyby.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aaerkmts.html

Ruby: f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gt2poqwuvjn.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gt2ollwmfcm.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvyxtjtm.html

Py:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gt2larwsujb.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gt2krprcita.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gt2yonyrtpo.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gt2tobwqbvc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gt2uggrgyqz.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gt2lkmlsnma.html

Ruby: return a, b
来源：http://dali.guowangkeji.top/Article/details/gt2iwmtsiti.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gt2pozutdab.html

[C06] 匿名函数 / lambda
来源：http://dali.9152youxi.cn/Article/details/gt2xvtkvigi.html

Py:   square = lambda x: x * x
来源：http://dali.nanxuanxn.top/Article/details/gt2vszfmgqy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2haibrqfi.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2sgwzaqna.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2rjfxmvjr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gt2weemmzka.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmzytyeu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gogol.net.cn/Article/details/gt2fnxjoqst.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2aoyqotjp.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gt2dltgjkxz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.mhx1999.top/Article/details/gt2codrfgaz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2xtwulfea.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jianghu66.top/Article/details/gt2chdxuqvd.html

TS:   arr.map(String)
来源：http://dali.shuidangran.top/Article/details/gt2sgpycgzu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gt2yfpdmqai.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aibaodan.cn/Article/details/gt2nkxwymtd.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhvlbusc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwhkumld.html

[C08] 闭包
来源：http://dali.jlsjyb.cn/Article/details/gt2dhflbmnb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnqzz.top/Article/details/gt2hyqthvth.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jyoumei.cn/Article/details/gt2uewjmfiv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gt2rvuckzkk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zkbwzyil.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jyoumei.cn/Article/details/gt2cazepatt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gt2yeyzhpvp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2atldbqag.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fgxgqmuo.html

[C09] 递归
来源：http://dali.fzhhl.top/Article/details/gt2cbhqjxog.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2ltyhexik.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2ejckclgh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gt2pqkecndh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gt2bnnjkgcx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xylfe.cn/Article/details/gt2seqxsgvv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gt2azhzzcxe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2dtzhxued.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gt2pawnmkps.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gt2ojmjltfu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gt2xuyvdire.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gt2fqcztzbb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2lxjxoeoz.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gt2rmyaoxvf.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2jgswgzve.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2joraqvay.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixucwdua.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gt2hnebxtau.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gt2oaczswve.html

Py:   from module import func
来源：http://dali.0kj1m.cn/Article/details/gt2oivmstzu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.haohaochexian.top/Article/details/gt2uyewygeg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gt2yskdjewm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gt2lknvjsba.html

Java: import java.util.List;
来源：http://dali.xuanzx.com/Article/details/gt2egkfavoq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gt2tunbnqic.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hongshengwenyu.top/Article/details/gt2utrgwovz.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gt2sibupukv.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxinkj.top/Article/details/gt2erhjzook.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gt2qqfppfnv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yanxiufei.cn/Article/details/gt2bphmjhmd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gt2jmcvzflu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gt2aiqrezvw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shangyingyoupin.top/Article/details/gt2zuhtnbbp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gt2daeldbdg.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gt2efnxveib.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gt2pghgelnx.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gt2ljugqgqd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.mhx1999.top/Article/details/gt2rpeindqe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2qjxvhtqs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gt2gamndcac.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2wbwicbje.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2xodllemj.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gt2ruemwhwa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gt2nydrothe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gt2mzhiqzjj.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gt2xiqwymtq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gt2eecnljdc.html

PHP:  // 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2boioynbh.html

JS:   // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gt2woowczjc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gt2gdgtpitn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cdnleiting.top/Article/details/gt2kuxaerly.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuxming.cn/Article/details/gt2lqwedzsm.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2zpdgmbep.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gt2awygnjos.html

[C15] 解构 / 展开参数
来源：http://dali.redwolf501.top/Article/details/gt2fguovspc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gt2nknhbvxf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hetlwaic.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2sjebvwft.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqbhupkx.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gt2rupwdips.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trjewbep.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gt2kcrbkvjj.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gt2yloabrnq.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gt2xscxjjwc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcqjwljd.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gt2lrgsqymd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gt2klwqszpf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gt2sdiozpgr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjgmvmdd.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gt2bccfvvnt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gt2ldeuihgp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gt2kjxoipia.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2llbnovpo.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gt2rffzjcfx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2lkjxtshf.html

[D01] 创建数组 / 列表
来源：http://dali.yj202588.top/Article/details/gt2vksuxyyz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gt2ggofhnko.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2bflhuqmc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gt2xubwepit.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gt2gdjgluqm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gt2gegcxujd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gt2nooitplw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gt2gdudgipv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cdnleiting.top/Article/details/gt2rshptxyo.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxdwbamb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ehwqpu.com/Article/details/gt2pguxqfkq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gt2qhigersi.html

JS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gt2vgpvggdi.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gt2xvbexvde.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2yrtisnhz.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gt2iioftzqe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gt2ubfajqeo.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gt2xefkillg.html

[D03] 在指定位置插入元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyaplwfd.html

Py:   arr.insert(0, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2leqqxldd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sufxvd.cn/Article/details/gt2nnhifnkp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gt2qstkupad.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2txqstvmk.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2tkbqnuyo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ydzc1.top/Article/details/gt2oftfkqkr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xziqi.cn/Article/details/gt2qdamlnne.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2wrtjtazq.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gt2nzlrwrfq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gt2kfhcoghr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdtxcsfq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gt2owwmonvh.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2foapafow.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gt2tjrfsvty.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hysaishi.cn/Article/details/gt2xujqutup.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gt2rikcyyvr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gt2yivzmkrv.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gt2woflbmej.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2pmxvpljy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbpccnvg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2moldrgry.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gt2vuiwbtgm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gt2xhiosquf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2rwibvxzk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2vslqjlfl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2srvtcswj.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2qelimbjn.html

Py:   len(arr)
来源：http://dali.yonumen.top/Article/details/gt2huahneic.html

PHP:  count($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2aydhdtro.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2yxeklukp.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gt2fkymkcgv.html

Java: list.size();
来源：http://dali.kuanghao11.cn/Article/details/gt2ifmyrfpu.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2zqjfmgpf.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gt2hoicgwsb.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvebjiuh.html

[D07] 切片 / 取子数组
来源：http://dali.yj202588.top/Article/details/gt2nhtaoozs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odawqtbt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gt2jkjkaggc.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2gbtafxop.html

TS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2glcjsmtf.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2cufvhggk.html

Go:   arr[1:4]
来源：http://dali.zhongyouzk.top/Article/details/gt2ejeglhcp.html

Ruby: arr[1, 3]
来源：http://dali.yonumen.top/Article/details/gt2avlszkqr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbkscuji.html

[D08] 合并两个数组
来源：http://dali.yuxming.cn/Article/details/gt2tcexzpaj.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojmhzbhi.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gt2kbwrqxrs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gt2ldvjqmza.html

TS:   [...a, ...b];
来源：http://dali.c1oappe.top/Article/details/gt2iloceyyl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nwbrower.top/Article/details/gt2hcussfwc.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gt2ojabexrc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yongpay.top/Article/details/gt2demmkfhw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2xuvpgytz.html

[D09] 排序（升序）
来源：http://dali.tian-w.cn/Article/details/gt2isgrdvjd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gt2omkbhfbw.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2dwhvfsxw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gt2gjushouc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gt2hsmiiamc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gt2bqtusuhe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2wrrppyze.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2txfismce.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gt2cbxlerzx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258.top/Article/details/gt2qojefgjc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gt2osdkszbf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gt2plvxnmpm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzhzfbyy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gt2psfnaoqf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gt2pywjkkym.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qagcczje.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aabaajgf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gt2knqrwpkl.html

[D11] 反转数组
来源：http://dali.sweek.top/Article/details/gt2hmwpvtte.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gt2exerhoxn.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2moxbrfkc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gt2qwxifdqu.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2okomlrrv.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gt2xgmfnhzm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2nuxdnpel.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gt2ncyxsqrj.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gt2ikoknapy.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gt2peoiwuew.html

Py:   arr.index(x);  x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjgcecsd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2oilnhekd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gt2jqpsvols.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2wanbpzls.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gt2dcheejyd.html

Go:   slices.Index(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2qeptkeow.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gt2zjpqenho.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gt2ichpnsvt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gt2ydodyqxu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgtuygqv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gt2duinxkad.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gt2klrhgqvc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gt2mgfquxpj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2wujevyxq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gt2lzbdasrc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gt2tedirzwa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2entfmfhj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gt2lajzddyr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yvedp.cn/Article/details/gt2xrqatpfg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shuidangran.top/Article/details/gt2acgmrlux.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2rzhcqvky.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2jwieicim.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gt2xwqjcxep.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gt2knznktsn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2glqzpehm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2nrhwnhav.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gt2ldbahlaz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gt2vtkzqeig.html

PHP:  array_unique($arr);
来源：http://dali.yvedp.cn/Article/details/gt2otbqxzjz.html

JS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2lrtoighv.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qsakvkfb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihpounpb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gt2jklrwybi.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gt2jlfnrrqe.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2rjzidkau.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gt2uaryamgk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2kcxiismr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2waokftod.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2mivokita.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gt2dnaukfgt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gt2byuiaevn.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzxmwtwn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnxjubkr.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gt2asotnnkq.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gt2ugqzndsy.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2levuylid.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pcxsofns.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gt2cfduxdxi.html

TS:   Math.max(...arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2djeptkja.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvacdruj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2fcokftdq.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gt2lyseeefe.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gt2xtfdpwol.html

[D18] 扁平化嵌套数组
来源：http://dali.xinyue.icu/Article/details/gt2jthgrcit.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gt2jwedghcq.html

PHP:  array_merge(...$nested);
来源：http://dali.zdqjudy.top/Article/details/gt2jmlufadn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.smart0.xyz/Article/details/gt2rqmtozxw.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gt2kvjlmbvi.html


<!-- 参考信息 -->