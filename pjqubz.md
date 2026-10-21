代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gttcovclmo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtfdrtrysq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.c1oappe.top/Article/details/gtacapbbxw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtkqjaaord.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gtjmlfxijg.html

Py:   def greet(name="World"): return name
来源：http://dali.smart0.xyz/Article/details/gtavkskycw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gtxjxfyved.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gttjbybkmz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtjwslphxs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuxming.cn/Article/details/gtpcsnkcpo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yvedp.cn/Article/details/gtdpdtoqpz.html

Ruby: def greet(name = "World") = name
来源：http://dali.sxryk.cn/Article/details/gthwplhelg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aizwys.cn/Article/details/gtmosyyvfm.html

[C03] 可变参数
来源：http://dali.9152youxi.cn/Article/details/gtpljwuqcb.html

Py:   def total(*args): return sum(args)
来源：http://dali.hysaishi.cn/Article/details/gtkqqhyety.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guannengcc.top/Article/details/gtabseoens.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtojjiyctw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtgpwkgxml.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gtarefimfd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gtxuafhpkv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.c1oappe.top/Article/details/gtnflquizt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahnhcxcj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoipwodzh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fzhhl.top/Article/details/gtctpmxyzp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gttfdhhliy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtiriagmka.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnqzz.top/Article/details/gtjqsrthfd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gtawsdqzdy.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gtnrlahsrh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtwbjspdqo.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtnmvkelud.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gtdyncqfxk.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtfmeapynz.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gtigxfbljl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtssmkvoom.html

TS:   return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtdlqyroqm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zdqjudy.top/Article/details/gtrzocpulv.html

Go:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtufkvsuoz.html

Ruby: return a, b
来源：http://dali.gogol.net.cn/Article/details/gtteuflkol.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gtvmxegukf.html

[C06] 匿名函数 / lambda
来源：http://dali.ybcxt.top/Article/details/gtyrlxakcx.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gtqcpdmmnp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gtgpgtagxq.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gttuwaeevz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtfmvxsbij.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhengqikj.top/Article/details/gtfllogzov.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtxlmvajji.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtqrnsntwn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gtznbraban.html

[C07] 把函数作为参数传入
来源：http://dali.sysykeji.top/Article/details/gtgrkvbqbs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.0kj1m.cn/Article/details/gtssephtnw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtabdcbcnw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhiwuduotai.top/Article/details/gtslxgqrxd.html

TS:   arr.map(String)
来源：http://dali.0kj1m.cn/Article/details/gtjxttmvzw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cqqwz.cn/Article/details/gtevklwnmx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shangyingyoupin.top/Article/details/gtevmzuwsn.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenzaomai.com/Article/details/gtwtsjsaiv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yangfankeji.com/Article/details/gttdozagkp.html

[C08] 闭包
来源：http://dali.hfpthk.cn/Article/details/gtxwunoddz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gtbltzkuaj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigufen.top/Article/details/gtcswpnsqf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtsnlfdpca.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtnsfajtdn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gtzgzsuoai.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gtedeejtpd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ydzc1.top/Article/details/gtrlncrjpw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtdxwyxaqi.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gtyqrzddgd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtjtljjmfm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ivvv.top/Article/details/gtpbkpqval.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtbdhvefsj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gthstbimdc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gturudfxuw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shuidangran.top/Article/details/gtiijkdesj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtuvcdnqvt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.andypj.xyz/Article/details/gtqzzgzskm.html

[C10] 变量作用域
来源：http://dali.yvedp.cn/Article/details/gtqagyewnq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gtpfqxqipf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtqckazpny.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gtmncuwlne.html

TS:   同 JS
来源：http://dali.zhixingplan.top/Article/details/gtrmeeggpb.html

Java: 方法内为块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtnddchzdc.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtlskampby.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.haohaochexian.top/Article/details/gtttobnqxj.html

C#:   块级作用域
来源：http://dali.c1oappe.top/Article/details/gtfdncabvn.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtwcavmmdy.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gtnposoote.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shzxlz.cn/Article/details/gtvtetmeyu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gtxbjguije.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gtvptbnbni.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gtgshcckxq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gttzqhgpjt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhiwuduotai.top/Article/details/gtlijmfcpl.html

C#:   using System.Text;
来源：http://dali.bjfxy.top/Article/details/gtfdpzwdmm.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gtczbnefag.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtcsuamfhj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jyoumei.cn/Article/details/gtvhkttjqv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaswkwsvf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtefelcnej.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yueranfly.top/Article/details/gtqbcwrwic.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmdqqjgf.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gtpgetvasf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sysykeji.top/Article/details/gtsaxomjrx.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigufen.top/Article/details/gtatkgpydg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.snrcjt.cn/Article/details/gthfiuzajc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtlwncszkf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gtskeapmdr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtkfiseadh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtlwryewqm.html

Go:   func add(a, b int) int
来源：http://dali.chenzaomai.com/Article/details/gtwsgelxuc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gthxdkyljf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gtpituhzib.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtdxyhaqmo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gtbscyeozi.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtjdhqvidu.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gttksvakch.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gtftpvmazp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gthxfqeksm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gtgkrstlgk.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtzpcyhjwo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.snrcjt.cn/Article/details/gtzikafvrv.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gthezasxmd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gtszwkdlkm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gtkjlxqeax.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtckkheuxc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenlongwang.top/Article/details/gtqgantmzv.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gtclqlbysv.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhzbyafe.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklaozorb.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtcihcvdfs.html

[C16] 函数 / 方法重载
来源：http://dali.chenlongwang.top/Article/details/gtanoaxokr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtujhrbzjw.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gtivhjnpzo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gtbhxpuixg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.9152youxi.cn/Article/details/gtfjpsdiyk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtowsdmyrk.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gtloxyxsjh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gtqmhtqzoa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtgzgfwvdh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwtzmsdab.html

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gtvlxtgvuo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtlwhtyntv.html

[D01] 创建数组 / 列表
来源：http://dali.birdmap.top/Article/details/gtkjndekfx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gtylstegnh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gtjqayodta.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtvumxstlk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gteqrqvwkl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gtxtognbjg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.redwolf501.top/Article/details/gtpmasdgbr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtgealjvol.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gtowmxuovh.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gtvekdckkk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gtsjpftqqw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gtwvtkvclf.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtnwrwqedu.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtngohxbjf.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gtmbsgexlk.html

Go:   arr = append(arr, 4)
来源：http://dali.hfpthk.cn/Article/details/gtnbnhzjgc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gtjfebzwxw.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gtmvqiqrgp.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gtioosbklp.html

Py:   arr.insert(0, 0)
来源：http://dali.xziqi.cn/Article/details/gtwldvvskg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqemkfos.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gtevzohmzj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtpnkrnvnu.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gtbygjtyhj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xylfe.cn/Article/details/gtzeutvfkb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gtypzqtvmo.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtgsjerlif.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gtkkzfgksi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvyydsor.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gthfascljt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gtwjrjswgt.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxlbqhxp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gtkceanwyh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gthqmyrxpc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.mhx1999.top/Article/details/gtqvrnqsvd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gtyzlgtwrk.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gtxalmduqk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gthauvijho.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtlbqxdwvn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtingwtgwq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ydzc1.top/Article/details/gthopjiruo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gtoktybkvi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtouzuwgxu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gthpcnnqxf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtogqfzzvg.html

[D06] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzfisbjc.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtgvkcgmwi.html

PHP:  count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtrwakrwwe.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtfozydxth.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtrxbclajp.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gtseytutob.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtyrqjssaq.html

Ruby: arr.length; arr.size
来源：http://dali.jyoumei.cn/Article/details/gtaebfcmoc.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gtruwalpix.html

[D07] 切片 / 取子数组
来源：http://dali.fengsongda.top/Article/details/gtgttkrggc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gtshblypdy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtztbkixxe.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gthjlvkuch.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtbyznaxcx.html

Java: list.subList(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtkurczicd.html

Go:   arr[1:4]
来源：http://dali.chenzaomai.com/Article/details/gttmklziqt.html

Ruby: arr[1, 3]
来源：http://dali.jinqigufen.top/Article/details/gtbbkoeyjj.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gtlurtdaon.html

[D08] 合并两个数组
来源：http://dali.jqgfzy.top/Article/details/gtyzlauzsm.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gtekmmjvsg.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtrbevhguv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtzptorhrs.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gtmzthgdbh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gtrismassa.html

Go:   append(a, b...)
来源：http://dali.xziqi.cn/Article/details/gtbucaxlyr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gtdonprwmc.html

C#:   a.Concat(b).ToList()
来源：http://dali.yueranfly.top/Article/details/gtjowxeank.html

[D09] 排序（升序）
来源：http://dali.hongshengwenyu.top/Article/details/gthlrrgnor.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbijjapmg.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gtpbymbksj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gtexjgirss.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gtbbyvnnuv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.snrcjt.cn/Article/details/gtnelsobgy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtuooqckcm.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtizqantea.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gtxmvtllhw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gttwlypurt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gtiazwkfvj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gtqddviung.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtnjagkwox.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtrgskfcyp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gtqqdbcdai.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tianlin.xyz/Article/details/gtbqikxuct.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gtgocydikj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tian-w.cn/Article/details/gtmfnrxabl.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gtphnikhgs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gtawuxfxyl.html

PHP:  array_reverse($arr);
来源：http://dali.zdqjudy.top/Article/details/gthpwakgeo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gtvprfzvbf.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtsfxpywxg.html

Java: Collections.reverse(list);
来源：http://dali.gzhubu.top/Article/details/gthcdmmljx.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtihbadkaj.html

Ruby: arr.reverse
来源：http://dali.cucudq.cn/Article/details/gtumvjfshk.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gtnrlxpljp.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gtcazmbznw.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgufenzy.top/Article/details/gtgxvlsmdt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.c1oappe.top/Article/details/gttljzomcj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtfxccdzvp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtxbnjtonn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtstlbhvuj.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtzuzttdou.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gtlhkxlqmq.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gtrkpoqrtg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gtwacsdmyw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gtjctqmdhs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gtlcuzjfye.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtwnsodoxk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtypusvyxe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daxiang520.top/Article/details/gttnmerphm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gtfouhfssh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtoqhtfjtb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtzicaabem.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gtfhbrqrac.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gtqjffwbvj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gtjiysnjgp.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gteelognhf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gteomkojpk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gtwfzzwejr.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gttiomorrt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daxiang520.top/Article/details/gtthucrbtd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtqtauxats.html

[D15] 去重
来源：http://dali.tianlin.xyz/Article/details/gtxksgumnz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpnxpqiz.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gthamoqqab.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtywoauorj.html

TS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtaeendjfo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gtmdbaflfs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gtzhbudiry.html

Ruby: arr.uniq
来源：http://dali.gaohongyu789.top/Article/details/gtaquybxtp.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtnbchgkbz.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gtckeqxuvs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtvgnslqec.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtmxywcohw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtgvxgjvah.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtqcehuwoa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.birdmap.top/Article/details/gtoyomdhxp.html

Go:   // 手写循环累加
来源：http://dali.gotoacloud.top/Article/details/gtmtmhswof.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gtofwbppuf.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtomoffygb.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gtucvbjsoh.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gteigphjhp.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtxecaeyeq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gtzvpqxbki.html

TS:   Math.max(...arr);
来源：http://dali.bjfxy.top/Article/details/gtvhrwatok.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gtxvnhgnly.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gtcfklfozv.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gtwaemqwwp.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gtejuvqhxv.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiddbkdsb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gttfceotaj.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gtspyjdbwg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gttqvjksrs.html

TS:   nested.flat();
来源：http://dali.yj20258.top/Article/details/gtcnoztmbu.html


<!-- 参考信息 -->