代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxuanxn.top/Article/details/gtnuvntluh.html

Go:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gthlvckpji.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtfrukmcxi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gtlwnhpyfg.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gtefarqgme.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigufen.top/Article/details/gtaivjlxjp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.meibo888.top/Article/details/gtmfeezmqz.html

JS:   const square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtrzzxxmme.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtdxzpvbzz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtrsbnnkrx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gtwfjbibqu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtxyakllwa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtuyrpyusm.html

[C07] 把函数作为参数传入
来源：http://dali.yangfankeji.com/Article/details/gtmzxszszq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwezkefu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.c1oappe.top/Article/details/gtcujapztp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gogol.net.cn/Article/details/gtfcuqijux.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gtkgpjjavl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtksbxalha.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258888.top/Article/details/gtxekwmabw.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gtoubkgflv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcrhnnqa.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gtokzfscmr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guannengcc.top/Article/details/gtigyceomf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtwvjkumom.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpryafrlt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtqhyexczv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cucudq.cn/Article/details/gtphykwxkn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gtucanpevo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gtttniewvi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpccgpogw.html

[C09] 递归
来源：http://dali.snrcjt.cn/Article/details/gtiswvgeey.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtwoemfeil.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtvnbmqwyf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtsvfuemle.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtdqbmanyn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gthqqxlcab.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gtbwgjwyqh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtmwjyshsi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtsafueeaf.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gtamxkjfjq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hammf.cn/Article/details/gtqijlzian.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtwwcsvfgv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cashguo.top/Article/details/gtkxqahrrv.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqwqtpfh.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtshhyjyli.html

Go:   花括号块级作用域
来源：http://dali.yuanzhike.top/Article/details/gttfnbblda.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jiagoushi.top/Article/details/gtemrvqfix.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpinkuleq.html

[C11] 模块导入与导出
来源：http://dali.nanxinkj.top/Article/details/gtuigfrzcy.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gtclldefsh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dianchejie.cn/Article/details/gtnilibhgo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gtpmkwrylo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gtfasvkxgh.html

Java: import java.util.List;
来源：http://dali.svipenyu.cn/Article/details/gtdszcdfmh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangdashe.top/Article/details/gtfmgjlnio.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.0kj1m.cn/Article/details/gtnimybgpb.html

C#:   using System.Text;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjjuibdo.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenzaomai.com/Article/details/gtexnimerc.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258.top/Article/details/gtbpxxhkwc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gttwmcrzes.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtzxtlstlq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtcvaoalsv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gttruhtuhc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.vqdsnc.cn/Article/details/gtjdgdgymo.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gtmshoncrp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gttkbcgmgc.html

[C13] 类型声明 / 类型注解
来源：http://dali.pengpengdd.cyou/Article/details/gtigmwxmhx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtjyabydhd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtmrdawtlx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gtrfvwgytg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtkbgvlxqb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtcrqybnrb.html

Go:   func add(a, b int) int
来源：http://dali.dashuyun.cn/Article/details/gtjqaocrti.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pycfn.com/Article/details/gtryatspax.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gtyaliotrc.html

[C14] 泛型函数
来源：http://dali.birdmap.top/Article/details/gtnbvktnfi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjgsgtsf.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gthbsosifj.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtjulnpcgo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gtdegjvkay.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ehwqpu.com/Article/details/gthujyesqc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gtupfdgdii.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtsobchluc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxuanxn.top/Article/details/gtvykpdfuc.html

[C15] 解构 / 展开参数
来源：http://dali.guannengcc.top/Article/details/gtdcluyujm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gtxnkgqjcz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.iojbl.cn/Article/details/gthkozmxvn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtxhlepigh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gtcysomwua.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gtmszeknxp.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtlssutdvh.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrlxeaoo.html

C#:   var (a, b) = pair;
来源：http://dali.xylfe.cn/Article/details/gtxtjvytjp.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gtilmbtosh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuonpvix.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtlqwvjyfm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gtzafkpwap.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gtjckzbpyd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkrdrhzw.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gtckhigznw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gtenlmfnwg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guannengcc.top/Article/details/gtrgikhgsx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfqfbrmil.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gtdebodcmy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtowphzdmz.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtuynhnrif.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtpysaohop.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jiagoushi.top/Article/details/gtscuvqjfa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gttxzafucu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yonumen.top/Article/details/gtseoywsdz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xinyue.icu/Article/details/gtsehovhjv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtguvyuvkj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtplpzcqzr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangshuangyany.cn/Article/details/gtzsvqdcnc.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gtgvjrftkp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gttcnptmur.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtlcszdgbs.html

JS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gtpwyzfmuk.html

TS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtyduengwv.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gtualgitxh.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gtwmedntbm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gtdmvakxnu.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstpxtjtq.html

[D03] 在指定位置插入元素
来源：http://dali.zhongyouzk.top/Article/details/gtekqdijlt.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gtbxcnplgh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gtybsihtjv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gtszxufpzo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtjzkmvcnq.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtfurzbfmi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtsoygwksw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtmkpztffu.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtgxbydywu.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gtiiuwifjf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ppjwa.cn/Article/details/gtadszdkwp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gtzctmsgkf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxuanxn.top/Article/details/gtknvsozys.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gtxtwclkhs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gtftnvyqgj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtpcvsaklg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtaomligwe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gtwgmfjhuh.html

[D05] 访问与修改元素
来源：http://dali.mhx1999.top/Article/details/gtidfqkdwm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtscobnbjk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtewxlojxb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtyygechgv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gtcocsamdj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gtuaqumuho.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtnedvaplw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gthbenbzsy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtgdektknm.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtmtzfifcv.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtflvmcykp.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtwbnwdbfu.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtwbibqnhi.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtudrpygjt.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gtsbtqxssb.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljkopvkg.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gtkbnpftqd.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gtiiwghcjw.html

[D07] 切片 / 取子数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbywahgqv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gtjiepzsry.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gthahijuvt.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtrurwtqyi.html

TS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtxkkwzzxi.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtfvbbjqbj.html

Go:   arr[1:4]
来源：http://dali.sufxvd.cn/Article/details/gtyhutyjrf.html

Ruby: arr[1, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtdzofpxci.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtstyfwjqw.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gtshkcvqfh.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtswtacihq.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gtlrdflyob.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtiijuiijx.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxwmffyj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtluepwntn.html

Go:   append(a, b...)
来源：http://dali.yueranfly.top/Article/details/gtdxenwscr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ybcxt.top/Article/details/gtiiifxhoj.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtelahbyxl.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gtxvwgorbw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtqetzoxmu.html

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtpxfudhcv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jlsjyb.cn/Article/details/gtwotgmpyu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gtrffvdoyn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtydwdhhcp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtcxxbiarp.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtqakpahbr.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gtokewtxdq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gtozfltalx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nwbrower.top/Article/details/gtsbdjhyon.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gtelwgpiur.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtvqgnpetx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtlmofzqti.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gtnxpdysln.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtjhvszwhz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbefemejj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnqzz.top/Article/details/gttvhygcqa.html

[D11] 反转数组
来源：http://dali.zhengqikj.top/Article/details/gtrduegptd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hywenlv.cn/Article/details/gtvbdbebwp.html

PHP:  array_reverse($arr);
来源：http://dali.daria6918.cn/Article/details/gtyshfojpd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guowangkeji.top/Article/details/gtzrpinmet.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtitllpalv.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gtgygtosak.html

Go:   slices.Reverse(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtvddtsifm.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtdsmyuiwr.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gthwijfjuf.html

[D12] 查找元素下标
来源：http://dali.cashguo.top/Article/details/gtrywsyygl.html

Py:   arr.index(x);  x in arr
来源：http://dali.smart0.xyz/Article/details/gtfniprhlk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gtfpjvmsby.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtklelykfn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtnxcrcgsw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gtysrivdtx.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtbiaxcxyj.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gtpksykqkk.html

C#:   list.IndexOf(x);
来源：http://dali.daxiang520.top/Article/details/gtljbkylyv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gtxiqkqzma.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gtaznzuxrn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gtbvuizkuk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtvdvcbrxu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtszfjwpnm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yueranfly.top/Article/details/gtocfjytyu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gtmylvrneh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gtgpjcuhrg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtnxjwnixw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtapbakpce.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gtytzopvrq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gttsayarmu.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtlwcmkyct.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtjveabssk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dianchejie.cn/Article/details/gtusjqadjh.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtkrgtubac.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtcjhocqzb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtdewezpfy.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtvrwjvlic.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtsawcvmvf.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtxllvcbrz.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gteifrujbh.html

TS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtwzqzkjmv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthauzjwuu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gtyrpvvitb.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gttbebauoj.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gtefpbqjbz.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gtudbfuaiv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gttiytrtmb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gtcmhwgubr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtkjxfdcpv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtugjrikzh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gttcsciwjv.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gtrlojyilr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gtjdfoonhk.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gtulxlwpce.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gtkiqjuyvw.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtosstroxn.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gttovegsve.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gtxvltylet.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gtxkbehfut.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yvedp.cn/Article/details/gthjvvlwce.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gtxysorhaf.html

Ruby: arr.max;  arr.min
来源：http://dali.wangdashe.top/Article/details/gtzdcbiaab.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gtbfpglblv.html

[D18] 扁平化嵌套数组
来源：http://dali.ehwqpu.com/Article/details/gtmgfzjjvo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtaamgzqii.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gtsnzogsvt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtmpiyebmg.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gtlpimssuh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gtmdfghdor.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtgjceugub.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gtxlqwmsha.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.mhx1999.top/Article/details/gtisiujpzw.html

[D19] 按字段分组
来源：http://dali.gzhubu.top/Article/details/gtyqhtgrsx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangdashe.top/Article/details/gttztuflew.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gtscltczan.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gtbucinjjj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gtbedkwhbt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gtrdzohgbu.html

Go:   // 手写 map[string][]T
来源：http://dali.jyoumei.cn/Article/details/gtfmzwtiiu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gtlyiznizl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guannengcc.top/Article/details/gtckmyvjoi.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gtcqfpnoax.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gtxocrhmlz.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gtqhmajxmm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtyydtprdg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtvkptdvxv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtbmdpkzee.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gtrximgrhi.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gtvfqrgkxu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gtwekerwhl.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtyhmunfpd.html

Py:   x in arr
来源：http://dali.9152youxi.cn/Article/details/gtdqlvovzx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gtbvnyashm.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtkgymlxfc.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtwfsrcunc.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtgedskgrk.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtwbpbuxvn.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gtgdmzbjgn.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtjzafznih.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gtdqhqbjqa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gthvhsuhqc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtndjfvkru.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtnxshzcbw.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gtpfstpoos.html


<!-- 参考信息 -->