代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gtahkwozcz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtmufpjtms.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gtfaxrfhku.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigfzy.top/Article/details/gtgsxnjqdr.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gtnqenvvsm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtyinjyxad.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtnftofrds.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gtumodmvvc.html

Py:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtlobpywjs.html

PHP:  return [$a, $b];
来源：http://dali.gzhubu.top/Article/details/gtwpibdrwh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gtfpodsztl.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtcemmgtvg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gtzxqpucjc.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtpdgfajal.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gtogcvfpol.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenjidiqi.icu/Article/details/gtpbdfubez.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gtmxpwesit.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258888.top/Article/details/gtdhrnkzuy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhongyouzk.top/Article/details/gtiplqszqf.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtagceersa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shuidangran.top/Article/details/gtgfddlyiw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gtotzfzgdt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xylfe.cn/Article/details/gtnmeldeah.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gtriwdqvsj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtnmocyctj.html

[C07] 把函数作为参数传入
来源：http://dali.sysykeji.top/Article/details/gtqwujhsqx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gtdnjnbsvu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtoheewzxw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gtqnxrqypv.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gtkdzcwnou.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuxming.cn/Article/details/gtbktxfqir.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sufxvd.cn/Article/details/gthfnttaxv.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gttkmjfuyv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gtiozgvpuh.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gtwgnyaxxz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gtrqtdiazc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gtbbldymqj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtfdetqqsr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtvsdiyegp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ehwqpu.com/Article/details/gtdadkkvgu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gtvprtiyqx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shzxlz.cn/Article/details/gtkenqtshz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtdiwodlmy.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gtngbexamu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxydjkju.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gtpisixypw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtlzygsqmt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtafgvqzhf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtxfkkdxwl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gaohongyu789.top/Article/details/gtzuacpfjs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gtgkjrkuak.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtnexvsqqz.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gtdhkejsxw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gteqchwbxh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigfzy.top/Article/details/gtgabcyuti.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtolnimjoy.html

TS:   同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtjzonepmz.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtexybihom.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtxitbbxpc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ppjwa.cn/Article/details/gtvglfoosm.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gtoxkhnxjw.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gtiefkxpov.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gteupcbjpr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hongshengwenyu.top/Article/details/gtjbufjcok.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shuidangran.top/Article/details/gtxdwldqku.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.haohaochexian.top/Article/details/gtzwunzbyd.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gtjwfksyqp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxinkj.top/Article/details/gtjdjbupct.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.meibo888.top/Article/details/gtjywinszu.html

C#:   using System.Text;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiikmflgn.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gtdvwszxpf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gtzifkcwiq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.birdmap.top/Article/details/gtwhhcckca.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtwjlbtdba.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtupaaxnxx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yvedp.cn/Article/details/gtjvxqgkrg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ybcxt.top/Article/details/gtjeezpuon.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gthrmxmkaq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gtjfqnuycf.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gtogatukle.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtdvmnjhke.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtqaeaxalh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbbjxfst.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtkxmlyydr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtcoxgrxfl.html

Go:   func add(a, b int) int
来源：http://dali.shzxlz.cn/Article/details/gthppmqauw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ybcxt.top/Article/details/gtgpdzmicd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcqgynka.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gtlrjxvhfr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtgbppkcbj.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtwnnsenmh.html

JS:   // 无泛型
来源：http://dali.yongpay.top/Article/details/gtvpfyfihj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gtudympxth.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gtcsxrxmqz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gtunzlkigc.html

Ruby: # 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtdrxhddhw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gtudmkcsnr.html

[C15] 解构 / 展开参数
来源：http://dali.jqgufenzy.top/Article/details/gtmzahotts.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gthymgtvtt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gtazfqtfru.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtbhfhdyyx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gtzwwhxvpt.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gttlyntlzt.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gtgpkzchkn.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gtvnwsxqfp.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtbcfjzuvg.html

[C16] 函数 / 方法重载
来源：http://dali.fengsongda.top/Article/details/gtjmxyjwhp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.316326.xyz/Article/details/gtgyeibcvb.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gtndmxxtcd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gtpymistmb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gtdlbyhphh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtwedgbico.html

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gtzthavibn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gtzntvdksu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvcxzqfex.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtuxaqdjym.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gtctilxdrs.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttxyteoaa.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtltkusnpk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gtrcvuroux.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtzyhrgqrv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guannengcc.top/Article/details/gtvdgugezj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gtkjaxyssk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtgircskab.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fzhhl.top/Article/details/gtavxmeonn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gttrukgzfg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsbicxuu.html

[D02] 追加元素到末尾
来源：http://dali.mhx1999.top/Article/details/gtqadwdhvq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shzxlz.cn/Article/details/gttenqfyls.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gtqontkywf.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtwnnjpvmw.html

TS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtffwwvskz.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gtqylnmpdm.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gtltyiukbo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfghhfnrl.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gtogqxzabj.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gtuealliih.html

Py:   arr.insert(0, 0)
来源：http://dali.andypj.xyz/Article/details/gtpvzyudyi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gtvxktsvog.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gtdjzehsew.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj202588.top/Article/details/gtephasjqi.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtwawrgyyw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzumbujc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gtyzzwvzge.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtoaxitctm.html

[D04] 删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryqgqgai.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhoulong.xyz/Article/details/gthzucdczr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gtxpyeocnm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gtdnclreyl.html

TS:   arr.splice(0, 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtefrvfebr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gtbkowyavm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gtgzsfoajb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gttxrgbhhi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.iojbl.cn/Article/details/gtwzkdhadz.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtcvryuddv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtwceedubv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtsjelpozh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtlsybtcww.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gtilwcepyd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guowangkeji.top/Article/details/gtuccfqjxd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gthtisvpme.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtpqfvqjlc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtrlqegcsq.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gtynserfvy.html

Py:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtzvsrxqkw.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gttenqkcrg.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtsrollevs.html

TS:   arr.length
来源：http://dali.ivvv.top/Article/details/gttigdfsgc.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gtaphftnnu.html

Go:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gthcpiybls.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gtqzkzexfg.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gtjqbloshq.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gtgzxqxuvn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ppjwa.cn/Article/details/gtsgrrpvkf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtjielijlb.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtzapbstfk.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtupmdazvo.html

Java: list.subList(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gttiftypan.html

Go:   arr[1:4]
来源：http://dali.smart0.xyz/Article/details/gtmdsbbysb.html

Ruby: arr[1, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtnsagmbig.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtifblausm.html

[D08] 合并两个数组
来源：http://dali.chenjidiqi.icu/Article/details/gtytbsaapj.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gtfgmwwqkv.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtagfvyles.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknsnyilv.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtugcepdny.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtbvgckctv.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gtkpxcypmo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gthyofpvbw.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtalafijyj.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduruaknr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtilaufvvk.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gtjlxtwsow.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtuqamzyos.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gtfaewcgye.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gtyohhzlii.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtvwuuujjq.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtblgvnicv.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gtxrivkoxi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.snrcjt.cn/Article/details/gtktgtdotp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fzhhl.top/Article/details/gtogkileoo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtbtbgqnfu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtqsonaiqj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtegssthld.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gttwbhwbyu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gtjrtimdgq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zdqjudy.top/Article/details/gtiusenqsg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fzhhl.top/Article/details/gtazkoeimz.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gtrocbbhyr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gtcxcbrwbf.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gtdiosmcxk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtbglfxldd.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gtfdvtwbhg.html

Java: Collections.reverse(list);
来源：http://dali.mhx1999.top/Article/details/gtshclojve.html

Go:   slices.Reverse(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtcotcwjgv.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuzjbyij.html

C#:   list.Reverse();
来源：http://dali.yj202588.top/Article/details/gtkutigvlw.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gtaxeiaflz.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gtejokcjhu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gttlfsvdxp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtbdgnvxov.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtrrqnmoud.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtedglhwna.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtdykqadib.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gtmaulsbma.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gteztsrcbq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gtophepxzh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gtfcfslgaz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gtfgnvjcmc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtyutqclde.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtrwdghbaa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrvbqhlx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gtbxddzzyj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgjeitjh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtwxnggwgd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.bjfxy.top/Article/details/gtpunzuvcz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gtygjmnnre.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gtxxqgzkpq.html

JS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtblivzatk.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfuqmhwi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gotoacloud.top/Article/details/gtbdhekdip.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtitfvifli.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteptytbiq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtuipfjnbr.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtwthuynrp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtkhquqoza.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gthobrrrht.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtohfmeewo.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtsqjawnyz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.quarkkingdee.top/Article/details/gtbrxryxzo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gtvrszdehm.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gtyhcnwarv.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gtwuapoilp.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gthcxdhbyf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtaafyjwlq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gtnhooyhmf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtgvgfhfrg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtjrkuocsc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtbalzrtas.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gtddzragjs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gteastvuwb.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gtiulsfawb.html

[D17] 最大值与最小值
来源：http://dali.daria6918.cn/Article/details/gtpxfemnvm.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gtkvdhuqwy.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtsabmgssh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtsxggmqkp.html

TS:   Math.max(...arr);
来源：http://dali.aizwys.cn/Article/details/gtfjdhpeyv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gtzggsjwnd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gthcwxaqvp.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gtmzsmcqwz.html

C#:   list.Max();  list.Min()
来源：http://dali.cashguo.top/Article/details/gtdditnzra.html

[D18] 扁平化嵌套数组
来源：http://dali.yonumen.top/Article/details/gtsvaghkrg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiyftvvj.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gtmlqchikj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gttymywrfp.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtfzgkfhxh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gtkhgnhkhk.html

Go:   // 手写双层循环
来源：http://dali.jqgufenzy.top/Article/details/gtotllhavs.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtflvtyanx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtndpqirih.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gtiuxiholy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gtnmdcxyap.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yonumen.top/Article/details/gtywedqtry.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvdlctuw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtzchrnzkd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gtbcgahbhc.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtfnofqxsy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gtxxqtddlg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gtavgxuzwv.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gtvumvugoz.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvhacemj.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gtpwbwsyfh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtqzhgqgvm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtstdepvwe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gtfgitvqxh.html

Go:   // 手写 map[T]int
来源：http://dali.zycfv.cn/Article/details/gtgqdjwgvi.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gtovunnjni.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gthepqmnso.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtxhhtkrdq.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gthessoiqr.html


<!-- 参考信息 -->