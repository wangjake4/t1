代发 wailian999

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtqabjtwxx.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gtratqlwem.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258.top/Article/details/gtwowjyjof.html

TS:   return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtjspeyzrs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shzxlz.cn/Article/details/gtfwpnjcst.html

Go:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtacstlpmk.html

Ruby: return a, b
来源：http://dali.wangdashe.top/Article/details/gtzlkbbvig.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxuanxn.top/Article/details/gtqkqgkdkk.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gtcowtwmsb.html

Py:   square = lambda x: x * x
来源：http://dali.yuanzhike.top/Article/details/gtdrbdorcg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gthcbnwefj.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gttcdygfil.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtekzcefty.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gtkauzgkpx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gtxvdztrbh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gtakkcoqca.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtlpbrakmj.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gthopndoyq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gtjfafputp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gtvypadqcx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtzortrtoi.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gtjfgabwsa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtmlvudkee.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gtewhctxtd.html

Ruby: arr.map(&:upcase)
来源：http://dali.feifeiyinyue.top/Article/details/gtfyczzifm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sufxvd.cn/Article/details/gtyeolhduj.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gtltdeptbk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guannengcc.top/Article/details/gtesuucoir.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gtjsgmwtxp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtiozhfjxf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gtlhwpmmld.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.c1oappe.top/Article/details/gthdtfdxxa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gtxjioapzt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xziqi.cn/Article/details/gtzfpbigna.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtmvtjtkfa.html

[C09] 递归
来源：http://dali.feifeiyinyue.top/Article/details/gtleqylzpq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtlleofgoa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yvedp.cn/Article/details/gtrkyytiie.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtcfqxjzva.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtyoagxrhe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtofowtwfx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gtbyzmlvnk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtfutkptvx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.andypj.xyz/Article/details/gtfupqmdfk.html

[C10] 变量作用域
来源：http://dali.haohaochexian.top/Article/details/gtqedhgvyv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gtzzqahawy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gtvihfbemv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shzxlz.cn/Article/details/gturnvsyub.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gtxyboitfh.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtbbpqqtcr.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gtiebdltgd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gtqjtxhzmq.html

C#:   块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtluhfgxnq.html

[C11] 模块导入与导出
来源：http://dali.redwolf501.top/Article/details/gtvdbzyknh.html

Py:   from module import func
来源：http://dali.svipenyu.cn/Article/details/gthgeykpek.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gtywtxyhjt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtrcumsckf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gtcttziniu.html

Java: import java.util.List;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgggfamf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gtraduvcak.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sxryk.cn/Article/details/gtmmudwasd.html

C#:   using System.Text;
来源：http://dali.quarkkingdee.top/Article/details/gtfzdrjqxn.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gtfavouhon.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gtnrelswol.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daxiang520.top/Article/details/gtksjlgsjj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtezthlufs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtpxbvrwlh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.316326.xyz/Article/details/gtaenuwrbv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aibaodan.cn/Article/details/gtmlcnsjhq.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gtaqygnoht.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gtydyhyqyz.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gtqrlneygq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gtncvrpkgb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtolftiuym.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gtpjrhkokq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtssmqgche.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtjiphrjmy.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtifbtqshb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsumagkn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gthkzkrihy.html

[C14] 泛型函数
来源：http://dali.havefunace.top/Article/details/gtanitexrz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shzxlz.cn/Article/details/gtqkshmwxr.html

PHP:  // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtqvprzmmj.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gteectkygc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gtypjmhvgo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gtjgsgilho.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gtztjettnd.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gtdcqijibx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gtxklzklbs.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gtkelqpwty.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtsynullud.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtudyljjrd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtypltycwc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gtenmromlv.html

Java: // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuotodow.html

Go:   // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtiqzbfcba.html

Ruby: a, b = pair
来源：http://dali.hongshengwenyu.top/Article/details/gtupeyynqq.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gtzgixdakj.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gtdyrgveay.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtsaszeync.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gtrevgwada.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigufen.top/Article/details/gtbgpsryvo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gtvpgifjyw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtckmbklcs.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gtubpnaire.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangshuangyany.cn/Article/details/gttnwgkywf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gtknhugryv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtifebmcjq.html

D. 数组 / 列表 / 集合
来源：http://dali.cashguo.top/Article/details/gtnwavvnnh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtewykrlqc.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gtegouonzz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gzhubu.top/Article/details/gtvdogkipb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtczebpauv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtordjdfzx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghnvfjyc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ywan-chungtsiang.top/Article/details/gteicpwxbj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gtunfhgfwn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gthfhgttmn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxinkj.top/Article/details/gtoqqgjsww.html

[D02] 追加元素到末尾
来源：http://dali.c1oappe.top/Article/details/gtjtwsfrpu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtwljchqpf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gtmqyoswji.html

JS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gttibcmkrw.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtmirdvyjf.html

Java: list.add(4);
来源：http://dali.hysaishi.cn/Article/details/gtbthaofaj.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gtvtwoadoe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gtclsxemkw.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtchyuikdx.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gtelmuwzvp.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gtpmmmcukj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gtvhfukjpi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gteuskzmjh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sysykeji.top/Article/details/gtnihqfizg.html

Java: list.add(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtcixzzcyc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gtptlgvbof.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sysykeji.top/Article/details/gtoqobklgb.html

C#:   list.Insert(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtdvyqpafv.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtsrnwolul.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtukxsqjqp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gthhqrkgqt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenlongwang.top/Article/details/gtbmovbvhu.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkwanbhu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gtjdrbaajt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gtkolgsihk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtcjtjeoxf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gtiwkwgytc.html

[D05] 访问与修改元素
来源：http://dali.ivvv.top/Article/details/gtsscmahcm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtvlgotaok.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtbhmpudvx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtdcjshyey.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuetiantiany.cn/Article/details/gtrdmgrycb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyfzfxmn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtfxmgmwct.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtoozdtxjw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtqmsbvhog.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtrzhqnfmu.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gtopxpavmb.html

PHP:  count($arr);
来源：http://dali.c1oappe.top/Article/details/gtvilueaed.html

JS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtyiohxjzo.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gthprcsxuu.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gtjozukkks.html

Go:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtxhlptaih.html

Ruby: arr.length; arr.size
来源：http://dali.yonumen.top/Article/details/gtscvriwst.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gtgybawhrf.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gtturcpiky.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gteecluxka.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtegtqmdfk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtywxcunrz.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtpefbwnwb.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtrpirofvn.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gtohbqfdjm.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gtsfdfutzr.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtsjozhnhn.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gtcxjqgbdb.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gtwgozrkah.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gtagwqgiex.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gtbmegvfge.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gtgubnzysb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gthokyainl.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gteubyxrtl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gtxplnhenq.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gthbqrtyaj.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzghepgeo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtfdmzyyzz.html

PHP:  sort($arr);
来源：http://dali.tanke756.top/Article/details/gtgapmaplj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gtevwfubsm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gtebklwwsy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gtfdrmulkq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtdsowxejp.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gteggrxpaa.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gtilfdhkuo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pycfn.com/Article/details/gtgikxpeen.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gtrkckzpow.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gtmylzaqoy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtmteqknpq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtmgjutywj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xziqi.cn/Article/details/gtqtyhuuks.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsanxsoxx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gtjacmljla.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.bjfxy.top/Article/details/gtinqjgvro.html

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gtmmeqvpzq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gtlwimggig.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gtpnhkwpqa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gtqulzaotr.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gtcxkwxrhs.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtrqnmfnrp.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gtgvdpytdi.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gtsovtelcs.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gtncvtfoej.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gtlaknrnfa.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtgrgmbbia.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtptopvhuz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtkczmbgsq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtclkkqseg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtfmojbmej.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtqhvvochg.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhqoqnwc.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtcfnveobc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gtfrvkmdyh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtujscdfai.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gtxxzwcnhh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtazcjddce.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtgcoycjks.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gtiiovtwmt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtsshvhzjp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gtkiiuxicj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xinyue.icu/Article/details/gtkgdkkdvj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gogol.net.cn/Article/details/gtjumfwaav.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gtfsrhhpmx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtwhazckfd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtucuxytdb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtbypihchr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnqzz.top/Article/details/gtqbjnchpt.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtyldsbdgr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtdpaxkrvg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtkzylnlhk.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gtjmsebgoj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtnjljpvhg.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoioksifb.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtvuuapgcp.html

TS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtdqkgppoi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gaohongyu789.top/Article/details/gtqdthcbkt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cdnleiting.top/Article/details/gtpjhtyoco.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gtoeovmcjs.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gtjavrajls.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gtaoqvsogi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlnirkdm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigufen.top/Article/details/gtwsgoxsvc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtphcrmnwg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gthkipnhfz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbbivjoi.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gtxrwclmrh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gtkwmzbkqb.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gtgsveopqa.html

[D17] 最大值与最小值
来源：http://dali.aibaodan.cn/Article/details/gtpmpshbpe.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gtfzognnsr.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqszqyldm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtuxvxrnlw.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gtbcnssmvm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtjwswvjff.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gttzrqbavq.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gtrjmxeale.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtffqzrtvi.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gtntmctool.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gtirpqswto.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gtoeccnrcc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gtiyzbyfla.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gtwkgkgpjm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gtmztlcjht.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gtyhnodeym.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gtebxgxtpw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gtajkheysx.html

[D19] 按字段分组
来源：http://dali.zhengqikj.top/Article/details/gtngpxgyli.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gtoejixdqo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gtejjoulao.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenlongwang.top/Article/details/gtjwwawgml.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gtmrywrzzv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gtoirfquna.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gtlhjzfuww.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gtbtrcouwg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtksozhjie.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykztvdwg.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtobybtyfl.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtrfwgqpvp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtugmhqtcz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gtweqdtzbv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gogol.net.cn/Article/details/gtspwufpgt.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gtxfspkwdo.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gtohnvzkkq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gtshlmlajz.html

[D21] 判断是否包含某元素
来源：http://dali.chenjidiqi.icu/Article/details/gtksvtlrkz.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtzgdosmku.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gtgegamnvl.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtgavbfeta.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtleuinbym.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtszenfhij.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtavaqxxdq.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gtyknbmgwz.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gttuateklb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cdnleiting.top/Article/details/gtierggapl.html


<!-- 参考信息 -->