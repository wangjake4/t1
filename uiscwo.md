代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.quarkkingdee.top/Article/details/gterzzepvm.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangtech.top/Article/details/gticxptwlw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigfzy.top/Article/details/gtdhztvnme.html

JS:   const square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtqfiyoszy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nwbrower.top/Article/details/gtfsvltqll.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gtcjftrjft.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aibaodan.cn/Article/details/gtcqhtcrqk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gtbnsocyfp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gthdanpzlg.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gtopgtqxhh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gtinuaujjm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtttpzyydp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gthwwistab.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gtfzkdnarv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gtipeeysgf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gtsnzflxfd.html

Ruby: arr.map(&:upcase)
来源：http://dali.mhx1999.top/Article/details/gtdjlmhfzo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gtzevyoxos.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gtcxlrrbns.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhengqikj.top/Article/details/gtxwqvlikq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjwgxswk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtsnfeczep.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtjhasubwj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gtdkpjtvgo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gtkodpcvas.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuxming.cn/Article/details/gtnmjhbstg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtvevwjeft.html

[C09] 递归
来源：http://dali.gzhubu.top/Article/details/gtvkqerwmk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtowmqkgkw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hammf.cn/Article/details/gtrpbnehjc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gtuqmkodrt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gthksqxumd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gttrdwcjma.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuncvgvdr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gteryyktqi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gtnpgqkide.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtquxjkmpz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxinkj.top/Article/details/gtatlhsiom.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gtrtgxwxzt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gtzmfmlgvq.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gtdqcnvyit.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gttdhqdpmy.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gtagkkslvc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gtpiyqjdbe.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtevjanslj.html

[C11] 模块导入与导出
来源：http://dali.sufxvd.cn/Article/details/gtfwerxrzl.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gtdaqhcrxo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ivvv.top/Article/details/gtqrwfqrzi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gtlqmfddby.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gtvgelimou.html

Java: import java.util.List;
来源：http://dali.0kj1m.cn/Article/details/gtlrohsmpb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gtilswkmmf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gtrbsleate.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtpapcnzto.html

[C12] 立即执行函数 IIFE
来源：http://dali.ivvv.top/Article/details/gtniigkxwn.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gtnmirnput.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zycfv.cn/Article/details/gtdtuvbbfd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtkbgykhzs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtgglnsogp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gtubmixfon.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ehwqpu.com/Article/details/gtognftyza.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gtyzkmdsgf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtqgzlkaup.html

[C13] 类型声明 / 类型注解
来源：http://dali.vqdsnc.cn/Article/details/gtlnpwscbv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gtghqlroql.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtucrnsqnx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangshuangyany.cn/Article/details/gtzceutykf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gteyllhbkf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtlyzgxaen.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gtpalswexk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahgslsdh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlxxpjtj.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gtpiuhmxdn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xylfe.cn/Article/details/gtxotckdyf.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtziguboda.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtggzkezup.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gogol.net.cn/Article/details/gtgrmopnbm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gtdnqpxisl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtbwkjvpiy.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtuhgrjjbm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gtmcauqfra.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gtqlpoohaz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gtsonyfgfb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gtspbcrnlt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtkqbeybjn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fengsongda.top/Article/details/gtfjofyklh.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gtfcrcjoks.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gtkaekwczk.html

Ruby: a, b = pair
来源：http://dali.xuanzx.com/Article/details/gtmylxnqlx.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gthewkzufx.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gtlkzdnylu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gtgvcyvhfp.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gtwbanijsx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhongyouzk.top/Article/details/gtvkfoqhpx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gtzdcnulln.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gtgueomtpk.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gtovrhvvnf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gttnbifcbs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gtajwrpedt.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtnmchvfuk.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigufen.top/Article/details/gtrqtpgkbz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpimdizaq.html

[D01] 创建数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtqlgabykg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtxsdafctd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtkaybhasw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gtodylmibs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gtvoajtnxg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gtozdevlrx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shzxlz.cn/Article/details/gtyzjpmvjr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtpnafrani.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gtlsalqomg.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gtqjcbznjw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.iojbl.cn/Article/details/gtlfwhdmjc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtnbliuyie.html

JS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtroyfapke.html

TS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gtsktiawtv.html

Java: list.add(4);
来源：http://dali.zhixingplan.top/Article/details/gttzreoapg.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gtrqsypmjz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gtntnlvzmp.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gtazsbuegp.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gtancftjqf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtdzrtysoe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gtjtspaxeb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cashguo.top/Article/details/gtlvdgnbto.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gtwrqsghek.html

Java: list.add(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtnrzigzgu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gtqvkwtqnx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gtueaogymj.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtmsfjcsdc.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtiyjudygx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenlongwang.top/Article/details/gtjxmzocle.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aibaodan.cn/Article/details/gtnjlgyvvd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ivvv.top/Article/details/gtspzduhmj.html

TS:   arr.splice(0, 1);
来源：http://dali.aizwys.cn/Article/details/gtdicmbxwp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gtrjdloljm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gtetstlhhh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gtpgcmitiu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gtnrgukmjs.html

[D05] 访问与修改元素
来源：http://dali.chenjidiqi.icu/Article/details/gtaohagilo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtjceyiqgn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtciafbkbg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtukhloqnz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gtwnlibrwo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsflewfqu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtffhueecg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gttxanxvju.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtmztrcfwe.html

[D06] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtmvcntnoq.html

Py:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtciwlugjj.html

PHP:  count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtwtiqpxfm.html

JS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtupcplozz.html

TS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtndxrejzo.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gtplibxhuz.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtnpcyqidl.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gtivaurogs.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gttnymfbfc.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gteahbubhq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmwhoqlk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtlorkdxoy.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtdpdpnsds.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtpeymegft.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtceymnony.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gtgalbvxdq.html

Ruby: arr[1, 3]
来源：http://dali.hywenlv.cn/Article/details/gtxbzhbsvh.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtqocedvuv.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtoalhlalj.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gtpvrimvmx.html

PHP:  array_merge($a, $b);
来源：http://dali.316326.xyz/Article/details/gtnmrvvnrr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gtkkzzmcyj.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gthausmhii.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pycfn.com/Article/details/gtbvsgayxt.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtqmmdbwna.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gtpzqfvbej.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbisliszv.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gtnouwuufp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtvfacswbb.html

PHP:  sort($arr);
来源：http://dali.mhx1999.top/Article/details/gtykxshxpr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gtlutbhraz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gtbnwderjs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cdnleiting.top/Article/details/gtnmpktjvt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtgkgknhua.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtxuzjgzcn.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gtcduxcjnz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gtsnolphoq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.kuanghao11.cn/Article/details/gtpsnycxmm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gtotpjnhuz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gteyffzlvb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtpeiujasc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtniselvsi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gtiyeeqgwz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gtsknzqivg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtwzdgkkzk.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtfwpfjomj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gtgfmlmfdz.html

PHP:  array_reverse($arr);
来源：http://dali.316326.xyz/Article/details/gtuxbponrp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqmgujqn.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtjgbnblee.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gtowecwouv.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gttovjsmod.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtoqxksdvk.html

C#:   list.Reverse();
来源：http://dali.jinqigfzy.top/Article/details/gtmeegshkr.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gtztcopcwt.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuxming.cn/Article/details/gtzxofuojb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gtqzbpnabm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtbopmkysj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtlzfothul.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtzaffpetf.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtjyjhxhqv.html

Ruby: arr.index(x)
来源：http://dali.zhoulong.xyz/Article/details/gtksggwwwd.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtlmyqndbb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gttovsmwrk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cashguo.top/Article/details/gtrogxwknb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gtbxbixjbr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gtlmkovsvr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtarczpnos.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gtmdijgelu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gtrjshiscu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gtanhnaiqk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjlsntjb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzvugalw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sysykeji.top/Article/details/gtdqzarwll.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.haohaochexian.top/Article/details/gteibxsqng.html

JS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtskveefwl.html

TS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtqfbfxhzf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtybrsmzge.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtuzisldba.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtzkdtgafw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtgthsivpz.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gtpaoiqzit.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtonfatcbj.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtarhdtxtt.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtfveglamn.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjuaozcp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtkhkalueb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gtofhtjsjj.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gtglyoente.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtslrlousr.html

[D16] 求和与平均值
来源：http://dali.mhx1999.top/Article/details/gtewpcuhcd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtpwqcrcfr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gtejkvtiog.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtxnqqfnlg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtptuolftw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaeewqik.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gtippuucgc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gtlnvodybc.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtajydsgok.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gtyeirbina.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtjahkrsjp.html

PHP:  max($arr);  min($arr);
来源：http://dali.gzhubu.top/Article/details/gtpoolktwd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gtwflmqqsu.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtjncrbqck.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gtsiqhlzqq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gtsastynpe.html

Ruby: arr.max;  arr.min
来源：http://dali.tianlin.xyz/Article/details/gthoaoolfa.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gtoazqapsq.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyggnaxw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gtcepcmaws.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gtpurstgjp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenlongwang.top/Article/details/gtjyoqumbq.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gtervmkcyq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gtdajttyyd.html

Go:   // 手写双层循环
来源：http://dali.bjfxy.top/Article/details/gtpdcotqry.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gtpyfwgagf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gtxxbvqoqk.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gtjxxihrif.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gtczifbaop.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gtmcalsjbr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gtttefubtf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gthqtckvku.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtbuygggqf.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gtitpeqguo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gtprxdbqrj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtepqknprp.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gtrjkmbidg.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gtgvvnfwry.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gtgkqhqieg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtgpkzuuim.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtwjytyztr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gtvoxjyctk.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gtglrcrwhr.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gtirvmritn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gtuqpsxgtj.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gtytaerxun.html

Py:   x in arr
来源：http://dali.xuanzx.com/Article/details/gticvojtnu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gtvlcrnzgh.html

JS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtsjricqrf.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuwqvdti.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gtidrgppft.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gteafvddkz.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtlshijflq.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtwsqmwphl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gtvywwtokg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtqginitsj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gtkfmtimqj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gtslbvcjlu.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gtvcoagvnu.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtpbwxqzed.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gtullavobn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gtykdykzag.html

C#:   new List<int>(list);
来源：http://dali.ppjwa.cn/Article/details/gtozaodkqw.html


<!-- 参考信息 -->