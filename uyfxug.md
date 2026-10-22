代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwbusfzd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ybcxt.top/Article/details/gtnshmkmmw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.c1oappe.top/Article/details/gtmchlhgbk.html

Ruby: def greet(name = "World") = name
来源：http://dali.cucudq.cn/Article/details/gthhuhsrjb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gtiyhqpyyr.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtretephga.html

Py:   def total(*args): return sum(args)
来源：http://dali.daxiang520.top/Article/details/gtgxoywxpy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.quarkkingdee.top/Article/details/gtdvffakmf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtcswclanc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtzgpogdzd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvapjxzz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gtujqiaanx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ybcxt.top/Article/details/gttktjrqrn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gtgonywjqh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzcspvic.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gtzemcwrco.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtrxlqrjxv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtdwvrhbtj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aizwys.cn/Article/details/gtsgdnkgqf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gtyubrakll.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gtzidykbrl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gthijhsvfe.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtvcifinnl.html

[C05] 返回多个值
来源：http://dali.bjfxy.top/Article/details/gtczncsmds.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gtedzoddtq.html

PHP:  return [$a, $b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbhowumh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtecxzwldu.html

TS:   return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtsfpyxzlz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.vqdsnc.cn/Article/details/gtwvxcxdfx.html

Go:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtaogshcjy.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtgpxhdfbj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gtlzajcfhr.html

[C06] 匿名函数 / lambda
来源：http://dali.gogol.net.cn/Article/details/gtwltqnzpc.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gtzenfefof.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gtqyutbvky.html

JS:   const square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtkolckgsf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hammf.cn/Article/details/gtixfsbltx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtaygmgmfw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtnrwhijeu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtzneqokfa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gttoxpbyon.html

[C07] 把函数作为参数传入
来源：http://dali.guowangkeji.top/Article/details/gttzqysukb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gtszmwfwik.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtsufycgbj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gtrqzoathc.html

TS:   arr.map(String)
来源：http://dali.iojbl.cn/Article/details/gtahbixffo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sxryk.cn/Article/details/gtzwzdeidy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.feifeiyinyue.top/Article/details/gtahlwvocb.html

Ruby: arr.map(&:upcase)
来源：http://dali.shzxlz.cn/Article/details/gtjnyzelow.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sweek.top/Article/details/gtfaifzlbf.html

[C08] 闭包
来源：http://dali.fengsongda.top/Article/details/gtkayeudac.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gtpqbramee.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gtyfdnyyzm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtktjguqql.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gttcesquwp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtcuxelmay.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtlskyunfz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gotoacloud.top/Article/details/gtwsdmqtol.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtmempfdol.html

[C09] 递归
来源：http://dali.hfpthk.cn/Article/details/gtyyztpjzn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtlmafnybf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtbvbzytjg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtafoqfrsl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gtmwjkphxz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtyjhrcnpg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gtmvwxelab.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtwcndowpf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtlsevgvgz.html

[C10] 变量作用域
来源：http://dali.nwbrower.top/Article/details/gtadzpxwsl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gtqfnggyws.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtwcbsewtd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtsitowmxn.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gtflgrqbxd.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gtbwijipzw.html

Go:   花括号块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtjdxwludd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gturltzled.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtzwoxvdft.html

[C11] 模块导入与导出
来源：http://dali.hysaishi.cn/Article/details/gtzwbmkqyl.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gtztitvuaz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gtbjykqjyd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yongpay.top/Article/details/gtkgqycvoa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gtvkpfaizt.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gthdqcfcpr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hywenlv.cn/Article/details/gthcudgkzh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gtexpscsbo.html

C#:   using System.Text;
来源：http://dali.yuanzhike.top/Article/details/gtbqlxyxzk.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gtppmcwslg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gtqcnvcjfy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtilgojvcx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtgdomvtsn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gtrhnzulnc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangdashe.top/Article/details/gtwknhofsb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sysykeji.top/Article/details/gtbqnnnxoe.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gtcgqimwzz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtjpdceguj.html

[C13] 类型声明 / 类型注解
来源：http://dali.xinyue.icu/Article/details/gtggutdymu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtnohibynu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtxquqwcyx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gtpsyorjek.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtsnzecezm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtstscasvr.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gttclcwknn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnxiangtu.top/Article/details/gtekevclfy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtklkqawis.html

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gtgujinbsh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gtzoisvlwe.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtzztaguha.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gtlxwkqnuy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gttalrpqkn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gtfdaqxygs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gtapdetywb.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gtnplrpenp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gtzaaealgp.html

[C15] 解构 / 展开参数
来源：http://dali.sweek.top/Article/details/gthkeyiqyj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkirjsjee.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gthyhigkce.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtcfkvcdbk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yangfankeji.com/Article/details/gtkvfvwnpq.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtymswddbt.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtgkgapwts.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gtynyljspv.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgiazjvz.html

[C16] 函数 / 方法重载
来源：http://dali.gaohongyu789.top/Article/details/gtnznlafyi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqqldzjr.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gtomfylhcc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangdashe.top/Article/details/gtaosfcemp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gtejywhutb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gtslpeyvyc.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gtewsysymp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gtmgybhhep.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yonumen.top/Article/details/gtaretrihh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpoiilsyc.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gtaklvdczn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsgrdiuhe.html

[D01] 创建数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gtqadaglsu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkqyorzn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtxidkhcbo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gtewzserei.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gtcciobkyy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcnnoesl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gtjrbpsnnk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxhwihxk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gtlfbpvrfy.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtihtslisy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.feifeiyinyue.top/Article/details/gtzkiimpwn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xylfe.cn/Article/details/gtodxdvrvl.html

JS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtmcnhivkv.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtpbbfxuly.html

Java: list.add(4);
来源：http://dali.c1oappe.top/Article/details/gttxbmulcd.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtukugnfbj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hywenlv.cn/Article/details/gtsdbkhgoq.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gtiewsamfk.html

[D03] 在指定位置插入元素
来源：http://dali.hongshengwenyu.top/Article/details/gtuujfmbxg.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtdjppurtg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.haohaochexian.top/Article/details/gtoixppnnh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtxddmbibu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtpdmpwggs.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtpsqgleam.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gthcrajqvx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gtjdfwbvsa.html

C#:   list.Insert(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtdtjdxxsp.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gthsjrhlir.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsolilav.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gtywhgpflw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sufxvd.cn/Article/details/gtfbgsenrb.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtdjrkjqmb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj202588.top/Article/details/gtaampkpni.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gtshzellnu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtpzinkrgr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gthqqoujkw.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gtufjcccgd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtggerxwkp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtviuqtvzd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtcutefntv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shangyingyoupin.top/Article/details/gtypcpeivt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtkaxivpkv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtsemmwaxg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtwpioeahu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtwzggxntg.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtyfsbrppl.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtmfcwigjd.html

PHP:  count($arr);
来源：http://dali.gzhubu.top/Article/details/gtivmaoruk.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtqyibprnq.html

TS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxccgiar.html

Java: list.size();
来源：http://dali.yvedp.cn/Article/details/gtafoqxgkx.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtrbchysmt.html

Ruby: arr.length; arr.size
来源：http://dali.shuidangran.top/Article/details/gtuannlksc.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtedbpwpdc.html

[D07] 切片 / 取子数组
来源：http://dali.sufxvd.cn/Article/details/gtixqwdlbh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtlvwjxsqk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gtyhvrbftt.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtsojypcjl.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtqbqokgfb.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtefwwfhtv.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gtuengyecj.html

Ruby: arr[1, 3]
来源：http://dali.ehwqpu.com/Article/details/gtbuyjgpac.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gtdjgyvvgr.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtqexhvgxc.html

Py:   a + b;  a.extend(b)
来源：http://dali.xylfe.cn/Article/details/gtdnrndafk.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtikjmbpzn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gtjmetemme.html

TS:   [...a, ...b];
来源：http://dali.0kj1m.cn/Article/details/gtjdkjyjwq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gtkzjwkzrk.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gtmesfascm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtsnrkqvcz.html

C#:   a.Concat(b).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtgdcytobn.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtwnyyycqb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtukaimyqy.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtepzpcvpf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.0kj1m.cn/Article/details/gtxloswbyd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hammf.cn/Article/details/gtutrmvmtx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tian-w.cn/Article/details/gtsvvyudwa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtnoyuovsd.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtlocectty.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gtqzozliko.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtorcutfzw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezpvvizc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtjzdqaqgf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtbarihqxy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvmnyiuk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gtvkyodgfy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gtxwlhzqte.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sweek.top/Article/details/gtzfxyfnnt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtfcmnexjy.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gtprzyxunh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gtdqzehbuh.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gteohiqkqt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrtirkwa.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gtlcwjmqld.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidcjwxrt.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtrvhvwvai.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gtpwufrfyu.html

C#:   list.Reverse();
来源：http://dali.9152youxi.cn/Article/details/gtbwdfnjnl.html

[D12] 查找元素下标
来源：http://dali.fzhhl.top/Article/details/gtsfzafjpv.html

Py:   arr.index(x);  x in arr
来源：http://dali.iojbl.cn/Article/details/gtdzkckqso.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtuelqirmu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtaojkqovw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtycslpsgy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.smart0.xyz/Article/details/gthbjgmank.html

Go:   slices.Index(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtiiapmjtt.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gtjzekleia.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtxltfkemu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jlsjyb.cn/Article/details/gtndndpdat.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.haohaochexian.top/Article/details/gtfuxhqrsa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gtytvxbmuy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtypngiwnn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuougupxj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeststvr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtttkmhfud.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gtadzqhcnl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtmvjdzprt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gtorfaedqr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtlicbusma.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtvhbmgfsj.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtprikllsg.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtzijoxbij.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.birdmap.top/Article/details/gturcfguhk.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtqopzvstw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtyclgfhxa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtklozbkls.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gtyyjmtwjr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtcdqjsbnr.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtxazjisvj.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtxoihdvaf.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtmtfydrff.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtceqknzdt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gtgvphetpd.html

Ruby: arr.uniq
来源：http://dali.nanxuanxn.top/Article/details/gtwtigqbqs.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtmfdwsmah.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngchidmn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gtgjhehuxm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtvyluibjm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtaoulihsh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtkwkzdues.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gtufdkoswz.html

Go:   // 手写循环累加
来源：http://dali.cucudq.cn/Article/details/gtgivxupki.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtzunamfma.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gtkxxzqgzn.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gtnwhuawes.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gtfuekobfe.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gtxovryvfp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gtazoiiqeu.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtmdlgqvtk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gtmqzrhdil.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gtdicpzyin.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gtywtiurxc.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gtahoeucym.html

[D18] 扁平化嵌套数组
来源：http://dali.meibo888.top/Article/details/gtzwuyqiiz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtlohanutq.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gtvplgqgxd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtvomsysde.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtnnlsswst.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtjdydbwpc.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzawnakc.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gtsosgumqt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gtwcttnfjj.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gthmqidcie.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtmcuzdjco.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjoidupu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtxeblglrc.html


<!-- 参考信息 -->