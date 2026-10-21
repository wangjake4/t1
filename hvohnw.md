代发 wailian999

Py:   return a, b
来源：http://dali.mhx1999.top/Article/details/gtonjrrbhj.html

PHP:  return [$a, $b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrknsoiq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtrvqsyfkq.html

TS:   return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtxdlmgqft.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daria6918.cn/Article/details/gtdbfgqrnc.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gtqogsgsml.html

Ruby: return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtgxngcduq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sxryk.cn/Article/details/gtleefsyqr.html

[C06] 匿名函数 / lambda
来源：http://dali.snrcjt.cn/Article/details/gtjsmadwfv.html

Py:   square = lambda x: x * x
来源：http://dali.ybcxt.top/Article/details/gtwbdenrkt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sufxvd.cn/Article/details/gtstrratin.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtxnoefkzd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gtwmazuhvk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gtzlapvsgq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.birdmap.top/Article/details/gtjsefwbxf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.c1oappe.top/Article/details/gtltvfdoko.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtcxrladyo.html

[C07] 把函数作为参数传入
来源：http://dali.dashuyun.cn/Article/details/gtgwfprwpn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gtfpgqhezz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gtiqvnbcwr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jiagoushi.top/Article/details/gthekvexjl.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtnpgkqv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.svipenyu.cn/Article/details/gtrkxeyhhc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gtwergqjwz.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gtuojyvhje.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsauieyy.html

[C08] 闭包
来源：http://dali.guannengcc.top/Article/details/gtzumbgjxt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj202588.top/Article/details/gthhndvnga.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gtpmocvvwa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtekknupnr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtitiffuzz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gotoacloud.top/Article/details/gtncayttxm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.316326.xyz/Article/details/gtshewagyl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkenttzz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtlccuqkxh.html

[C09] 递归
来源：http://dali.c1oappe.top/Article/details/gtoohhpwlt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gtbokkoeca.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gtthkmbtal.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gtpuzlseyp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gtztgwxqid.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtpzufgfug.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gtdyavjccn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtxtuxvwgs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dianchejie.cn/Article/details/gtsufdnaah.html

[C10] 变量作用域
来源：http://dali.daria6918.cn/Article/details/gtzokmopjv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aizwys.cn/Article/details/gtmfrypelj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gtlvgoezip.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gtdckgneuq.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gtzadjsncu.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezdpzjfd.html

Go:   花括号块级作用域
来源：http://dali.xziqi.cn/Article/details/gtnwywqvxf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gtnhgbxawt.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwqwspde.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gtcyrxhmfr.html

Py:   from module import func
来源：http://dali.daxiang520.top/Article/details/gtoazhwocj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aizwys.cn/Article/details/gtadwfnpst.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gtboaxxkrg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gthhsjnipf.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gteeqxbeey.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtffjyncgs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gtykhdlmow.html

C#:   using System.Text;
来源：http://dali.iojbl.cn/Article/details/gtxajgxubc.html

[C12] 立即执行函数 IIFE
来源：http://dali.gaohongyu789.top/Article/details/gtwusmbpnn.html

Py:   (lambda: print("run"))()
来源：http://dali.jyoumei.cn/Article/details/gtjpcozyqx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj202588.top/Article/details/gtaulsovvk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtdryulctz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtxptskwic.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gtzuhobcxy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gterihbjus.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gtfsivvreo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gttakjzxdo.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gteakrclbi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtpuskrsnl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtwoxwknsl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gtkzgrukkv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtmtwlxqhx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtgldiegku.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gthzukbhsx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gtmermspbv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtjdchfjyc.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gtxqhammut.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenlongwang.top/Article/details/gtowrqzynj.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtinvndqwz.html

JS:   // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtutzmccro.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guannengcc.top/Article/details/gtfqdxluke.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gttwwnhrgq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gtvyebceee.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtpvrfbkmd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ybcxt.top/Article/details/gtpfcxmhhs.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gtjgfgowpo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtwxpsewfo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gtnlvazubt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtgfqffhpu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenzaomai.com/Article/details/gtfpgzrdaj.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtbdfmenkt.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gtmmlhijoj.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtvctxugdp.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gtmqhucddb.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gtbahjihgn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtctctereb.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gtftcznyth.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hysaishi.cn/Article/details/gtfzjavyjb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gtqiidcuwq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtuagtkaov.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gtphfxonos.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gtjwjrzeic.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gtxzkrorzm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtyqghmaui.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gtcdkxdjgt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyjzutnxj.html

[D01] 创建数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtbmxhqpcj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gtvvvkkbnd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gtpqugkjas.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtkvzzjwmw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gtlithvmqs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gtatplmerb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpczbuud.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhengqikj.top/Article/details/gtrenlepae.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xylfe.cn/Article/details/gtqwtwhsrr.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpamjorys.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hysaishi.cn/Article/details/gtjohthaox.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuanzx.com/Article/details/gtzvhbjlxq.html

JS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gtshsqzuar.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtbjdwsbxe.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gthvppfdwu.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gtjtjnnsyu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gthhxhhvid.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gtjstamese.html

[D03] 在指定位置插入元素
来源：http://dali.zycfv.cn/Article/details/gtqwymqgxs.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gtvqpyifeb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtftweypqm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxuanxn.top/Article/details/gtyndmiajh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtslrjzylb.html

Java: list.add(0, 0);
来源：http://dali.yj202588.top/Article/details/gthbzwtylm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hywenlv.cn/Article/details/gtmthbmcnf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.andypj.xyz/Article/details/gtjjkxywpw.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqyncifg.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtyolzhgfg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cheryme.top/Article/details/gtgvimolga.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gtdzmviopo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavykqvou.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gtqmcjrhug.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuanzhike.top/Article/details/gtutbclrvs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gtfpsucwds.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gtslnabpkc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tanke756.top/Article/details/gtkwgueqnv.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gtvarjexhh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtxwjmjwar.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gteacdfhhy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtuntvjnlw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.bjfxy.top/Article/details/gtfoedwlzu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gtdtxyfjyg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtxcyclmio.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtpeekaqfv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtupuhakjx.html

[D06] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtsihyttqi.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtqauhleqi.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtcvwgioig.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtqpaywxgj.html

TS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gtpmagpwzf.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtiufyngyl.html

Go:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gttwgywtav.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gtkzmdinkl.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gthpgswdfp.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gtnwzktpaf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gtzbmacczv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gtfyeuxuhw.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtexizkqus.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtqpqmuswo.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtzieivxfp.html

Go:   arr[1:4]
来源：http://dali.zhoulong.xyz/Article/details/gtfqjsovrq.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtharbasoz.html

C#:   list.GetRange(1, 3);
来源：http://dali.havefunace.top/Article/details/gtomctsaun.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gtxkwhlrbk.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gttdxpfxzx.html

PHP:  array_merge($a, $b);
来源：http://dali.dashuyun.cn/Article/details/gtiawpsiqf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkntnaspv.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtdeeeugzw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gtecbxpcmt.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gtrhdjckyv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gthxqopjpc.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtojrojnwe.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gtaunvimem.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtoxacjkos.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtbeoemimy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gtiyjssrhe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shuidangran.top/Article/details/gtvucaffht.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gtatqikney.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgkzeqcg.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtgxikrher.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gtkyyjhwjh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gtgfonqrrb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gtcfeawqxp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtgvsrdpxq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gttjcaicvw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtxcalfhrz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xinyue.icu/Article/details/gtfvcezzdv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yangfankeji.com/Article/details/gtiiwsdxnz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gtrovcuxuo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gtelwgbyxx.html

[D11] 反转数组
来源：http://dali.yj20258.top/Article/details/gtknmjvdly.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gtlyocsxfw.html

PHP:  array_reverse($arr);
来源：http://dali.0kj1m.cn/Article/details/gtzeijsfds.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ppjwa.cn/Article/details/gtiuarolui.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gtwnalfkdc.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gtdedqlftz.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gtysuhvwmp.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gtakjdobzr.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtqzhihtxp.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gtivgdmzje.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtknqieiiw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtyrwzackz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtodsondsq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtwwwzucsr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gtxjlwjfou.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtchkpksbc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtuhkutots.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtvvjutxdh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgufenzy.top/Article/details/gtunmtzjfv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gtroniekyh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gttmfhrzwy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtfmmmmhxb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtepnlrdoa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gtncshaxay.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gtjtbqrbmy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gtybixauae.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtftzcfzcz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shangyingyoupin.top/Article/details/gtjqkvcczt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gtxepvbwne.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtfapaegqq.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtzcojbqoi.html

TS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtlumrthaw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gttklvqrsi.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtgtkhaqpk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gtmiakwrbd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gtdymjbsfi.html

[D15] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtodcddswk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtyikrolfi.html

PHP:  array_unique($arr);
来源：http://dali.birdmap.top/Article/details/gtlkkoikvx.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtqwajulda.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtjlyjdlth.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gtiswblrcx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gtyhyhymmb.html

Ruby: arr.uniq
来源：http://dali.cdnleiting.top/Article/details/gtoscrwfcd.html

C#:   list.Distinct().ToList()
来源：http://dali.hysaishi.cn/Article/details/gtvivdcfey.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gtdrkehnwt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtbafxkwwh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtptenulzp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtnmzrikqk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogshgljj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fengsongda.top/Article/details/gtuzbbwtxk.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtzrvumxuy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gtnmhltejt.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gtoiiuhpuz.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gtfbcyyfjs.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtkauluifq.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtyldlfsff.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hfpthk.cn/Article/details/gtpbabvhhd.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gtgffjvznu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.316326.xyz/Article/details/gtveodhawe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtigzodseo.html

Ruby: arr.max;  arr.min
来源：http://dali.jianghu66.top/Article/details/gtdwlvybme.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtmnpsmpux.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gtnuhuiqdf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gthlsnzgcg.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrroibows.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gtuahycykk.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gtvjwjztun.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gtlulbsjhp.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gtikkovxva.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gtvvqurpvy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtsbzclxcj.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gtqiwenhki.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gtpqaspbvt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gthxzkajvw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gthjzjinev.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gtwhqsqwwj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprdnkmis.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gtrmcjbfxj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshyzsfws.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xziqi.cn/Article/details/gtkgtgzxke.html

[D20] 统计每个元素出现次数
来源：http://dali.dashuyun.cn/Article/details/gttdfahvnb.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gtxdxtuihd.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gtnqzpyoyb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtjbojwmdu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtezrjqtye.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gtrfmwvjvv.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gtziianqew.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gtvmdfaesv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gtlluonalq.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gtleaugjtn.html

Py:   x in arr
来源：http://dali.zdqjudy.top/Article/details/gtsyzirnyu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtbkrmyhvt.html

JS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtomtpluhv.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtecdojoen.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtimrecvrj.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtqvwbbedc.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtbrehcoas.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtprfmlcwx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gtkrachtgy.html


<!-- 参考信息 -->