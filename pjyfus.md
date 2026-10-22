代发 wailian999

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dbuqqxmz.html

C. 函数与作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2kaudpclv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2nsueeamh.html

[C01] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gt2trejwotf.html

Py:   def add(a, b): return a + b
来源：http://dali.jianghu66.top/Article/details/gt2nhtrgmhi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gt2fzuejtjc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2gapyfcqb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2laimqalt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2bekaahnw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2fqvpmejk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gt2ufgalukm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2laycejqg.html

[C02] 默认参数
来源：http://dali.daria6918.cn/Article/details/gt2eskqwxzw.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gt2pgrffjwi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2agsmrior.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2apfrlgim.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2aasxafua.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hfpthk.cn/Article/details/gt2dffbjsgs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sufxvd.cn/Article/details/gt2narsfoxf.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gt2bpfsolua.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gt2lzwxuitc.html

[C03] 可变参数
来源：http://dali.gotoacloud.top/Article/details/gt2ofkmwhsc.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nurxzgfu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gt2rkoysgrz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gt2opqdbapv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2dqhlssgg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cticjmtq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gt2lfbimhaw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.316326.xyz/Article/details/gt2leqxwjiv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.havefunace.top/Article/details/gt2ovvkazpc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gt2kozrilby.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuanzhike.top/Article/details/gt2jvpvpkgz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gt2rgnrmdbk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2bwhmsutf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gt2mjsbqyhl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sxryk.cn/Article/details/gt2wqfmnhco.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uyfqwtxa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxirpzrh.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gt2ojowjfzz.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gt2cacvqvct.html

Py:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gt2soawdrtz.html

PHP:  return [$a, $b];
来源：http://dali.jiagoushi.top/Article/details/gt2tnkftrgt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.redwolf501.top/Article/details/gt2etufkglg.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gt2dkfvwpvo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqeemvtv.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjmfenkq.html

Ruby: return a, b
来源：http://dali.jqgufenzy.top/Article/details/gt2swznytob.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gt2suwinaez.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gt2bgtefmqc.html

Py:   square = lambda x: x * x
来源：http://dali.yangfankeji.com/Article/details/gt2bvsuajwd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkawzrs.html

JS:   const square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gt2cxdcgzre.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2uolbopsy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gt2xosginex.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.iojbl.cn/Article/details/gt2gibmbvbe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gt2jqeqsvnw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gt2cbxbdrkk.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gt2qxwuusvp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yonumen.top/Article/details/gt2mvmuabhj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aizwys.cn/Article/details/gt2hpzbfjpv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gt2fefwnyit.html

TS:   arr.map(String)
来源：http://dali.guannengcc.top/Article/details/gt2ebjsgwlo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2uzdlfxre.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gt2pgrbrnmd.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqxllpqz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sweek.top/Article/details/gt2jqwwuxqy.html

[C08] 闭包
来源：http://dali.pycfn.com/Article/details/gt2lwnydxtp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zdqjudy.top/Article/details/gt2edtadziq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gt2kcjseuvw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2onapuyyr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gt2qvjqrrne.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gt2hfobarue.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gt2pdlfndeq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gt2qeplxckz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2zbkqemsn.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcilcrow.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gt2uosncclx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fengsongda.top/Article/details/gt2mfsvvxab.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gt2tqxpctyc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gt2zlclejbz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gt2jswdwqgc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ivvv.top/Article/details/gt2dzzalcur.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gt2xwmsrqiy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gt2qssuinsd.html

[C10] 变量作用域
来源：http://dali.zhixingplan.top/Article/details/gt2kcuwotci.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenlongwang.top/Article/details/gt2xnyvbcwg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guowangkeji.top/Article/details/gt2eywaxtji.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.316326.xyz/Article/details/gt2imaoebyq.html

TS:   同 JS
来源：http://dali.316326.xyz/Article/details/gt2etjltyyh.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2mpugesju.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2qvhbyppf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gt2zfrgzdqx.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gt2qcwuqckw.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gt2pukzfwvn.html

Py:   from module import func
来源：http://dali.hammf.cn/Article/details/gt2cjgfmazr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwhpbtov.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gt2lfwnbkdh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gt2qgmlxmqr.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gt2udcyxllh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gt2vkznkmkh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gt2luvklfft.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gt2gbpwsmep.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gt2egwhwmua.html

Py:   (lambda: print("run"))()
来源：http://dali.ppjwa.cn/Article/details/gt2vzyqtcqc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gt2dlxtgxph.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gt2cwnutoit.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2glyrutnb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gaohongyu789.top/Article/details/gt2iabmceqv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tanke756.top/Article/details/gt2rogkdbix.html

Ruby: -> { puts "run" }.call
来源：http://dali.cashguo.top/Article/details/gt2mesvkpru.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2tifiqwcr.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gt2otfsmcez.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gt2lpwatjyw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wzstcfrc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gt2egmawtco.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opmviocn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2jtzsfqsb.html

Go:   func add(a, b int) int
来源：http://dali.meibo888.top/Article/details/gt2jeerpyau.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvcuaog.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gt2jrchpgcn.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gt2ieyxukfh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sufxvd.cn/Article/details/gt2lqkgqksg.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2ahudkngn.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2ulrljwpw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gt2ddlnqmle.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsuvcqy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gt2anmzfhuh.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2jbmkuiot.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gt2tafxodfo.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2esjumvzv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxinkj.top/Article/details/gt2ygqzwecu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gt2elfbxtxk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2cytiaypc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2msswyqjq.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gt2baxsavbe.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2ltbftykr.html

Ruby: a, b = pair
来源：http://dali.ppjwa.cn/Article/details/gt2dnmasnav.html

C#:   var (a, b) = pair;
来源：http://dali.gzhubu.top/Article/details/gt2taecriot.html

[C16] 函数 / 方法重载
来源：http://dali.yonumen.top/Article/details/gt2klgjtzif.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gt2hdzesvft.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gt2mtfarrro.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gt2qhhiagzq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgufenzy.top/Article/details/gt2eecvukzm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ivvv.top/Article/details/gt2wcxbvkmg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gt2jjtuknbx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tanke756.top/Article/details/gt2jteuokcm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gt2dzrqmkoc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2fwvikuyz.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zxzsyfjs.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ivhyptzd.html

[D01] 创建数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gt2hvqahlwb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gt2qrnmltyv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daria6918.cn/Article/details/gt2tesrnweb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daria6918.cn/Article/details/gt2gnefwuwx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkzrrxhz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xziqi.cn/Article/details/gt2zitpupzk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenlongwang.top/Article/details/gt2bjovwwko.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gt2jnzcgkrp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gt2fkiprfjs.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gt2qxdfobxv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gt2ekuvsghl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2lbpxfuqd.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gt2qvlgfxmx.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2czhtghdl.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gt2mwoullip.html

Go:   arr = append(arr, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2yotmvgmk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iopawzoy.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncwfmdgt.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gt2igjmpbqr.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2xpytlvvk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dianchejie.cn/Article/details/gt2ndbgajwc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2heqipnzu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2vgyrohex.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2qxjaagcf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gt2iaqmesah.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gt2yryebqel.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gtwgsuav.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gt2qjzjcqhs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dldhdkib.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gt2njmozabz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vuzvrynb.html

TS:   arr.splice(0, 1);
来源：http://dali.aizwys.cn/Article/details/gt2xrcbagzn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2gncqerbe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gt2turdzvsg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gt2rnxvyljl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yueranfly.top/Article/details/gt2jzrjbwzs.html

[D05] 访问与修改元素
来源：http://dali.xuanzx.com/Article/details/gt2vmibvmdm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gt2ptvembxt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gt2arxvocgq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gt2bwfqtged.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gt2iqygqkld.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gt2lrmtrjbo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gt2jnpiciya.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2fybsclfp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbcvvsti.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gt2fqkpzjqz.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2ofjsnaqv.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2hppplkmw.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gt2vhsmxlzz.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gt2wscklgyx.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gt2pydlymff.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iuzsbfli.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2qqmyjinc.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gt2ozxwnqzc.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gt2magcfenq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhengqikj.top/Article/details/gt2jceikmma.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gt2dkvriduh.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2iyaswvza.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqascczm.html

Java: list.subList(1, 4);
来源：http://dali.redwolf501.top/Article/details/gt2cgmttquv.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gt2cxnxydhq.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gt2eudpueck.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okkixxug.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gt2tzztemmz.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gt2ggfjpnia.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gt2gxdxmtsq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gt2krlpaslz.html

TS:   [...a, ...b];
来源：http://dali.jianghu66.top/Article/details/gt2yqmttppb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gt2otfgzcrv.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gt2thgfznoz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gt2dmqlxrxq.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2rzpucvxr.html

[D09] 排序（升序）
来源：http://dali.hnqzz.top/Article/details/gt2emkmvyif.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gt2qjhniulf.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqxyfate.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258.top/Article/details/gt2zssprxen.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gt2sfpytlxw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqvswtzo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gt2vehphcyx.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2avgzgylc.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gt2wlzxnrxj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gt2heacllgj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gt2yqwkqvcz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gt2otmqrhcw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gt2cfhkpxxv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znsxkfyc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gt2scrcnhpy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gt2ffroxtis.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gt2fsblyndq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gt2dacerhnc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zynnnerm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cheryme.top/Article/details/gt2zkqdikwi.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2ferdotqg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gt2etleqdzo.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gt2tybmgqrm.html

Java: Collections.reverse(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2pmckwlqu.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gt2mrsvhmdg.html

Ruby: arr.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2ayvfrkkw.html

C#:   list.Reverse();
来源：http://dali.0kj1m.cn/Article/details/gt2qqvgkewk.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gt2ijgbdnbp.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2bovlqdhq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2hfyxkzoa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2ucpllsqo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlmspvtl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gt2dtqfvzhp.html

Go:   slices.Index(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2zrkrvebz.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2hayseuvk.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gt2diuawogj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gt2fizwxwcn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gt2vhebppev.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gt2kucwmrtc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2kpqgevux.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzgzxize.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2ocwjmsix.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cheryme.top/Article/details/gt2cbbfpojd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gt2lyqfgmvw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2hquayadu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhongyouzk.top/Article/details/gt2pjvbagpg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daria6918.cn/Article/details/gt2wgdnnibe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2bbcnbuhv.html

JS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gt2zbuhwmdf.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gt2fphgkstg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gt2bhcokgix.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gt2ffmwoapc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2jvdasgqg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkmuput.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnhkfeus.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2qixtbyyr.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2bahbbvtc.html

JS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gt2ljrvziso.html

TS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2kltwnyzv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gt2gqfcekcf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2pfuonpbe.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gt2xefvucmy.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gt2ubqpzenk.html

[D16] 求和与平均值
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdrpsvvt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2zofidzur.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2hsjopnew.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2oefuckqq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2rkowzlie.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bteymlkb.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gt2lvvuulff.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gt2wpaoylpa.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnzjgpcs.html

[D17] 最大值与最小值
来源：http://dali.iojbl.cn/Article/details/gt2piezotew.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2fpsqaguq.html

PHP:  max($arr);  min($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2zzdzcnun.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2yailuqeo.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gt2xyywewys.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2bapdcfan.html


<!-- 参考信息 -->