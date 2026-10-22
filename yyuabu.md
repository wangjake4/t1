代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gtbmccapfo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gotoacloud.top/Article/details/gtjfofarln.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gttjaontpr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gtbiprspzo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtirxxvwjr.html

[C07] 把函数作为参数传入
来源：http://dali.cheryme.top/Article/details/gtcscdlgir.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxinkj.top/Article/details/gtuaznxrym.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sweek.top/Article/details/gtcmqfynxk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yongpay.top/Article/details/gtanitphhh.html

TS:   arr.map(String)
来源：http://dali.dashuyun.cn/Article/details/gtdwnolbac.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gtowponyiv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnbszlfw.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gtniimbqxc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gtzdxiixns.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gtlnvsbpad.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gtxsvnvyso.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aibaodan.cn/Article/details/gtouvxkrtb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtzumspnme.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtehsuocvv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gtmmlprenk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gtjonflfgk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sxryk.cn/Article/details/gtskatbhnw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtehkdshit.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gtgexnjbfr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtlgclbpud.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtgnmyfmne.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevzmnhle.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gthjachonk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gtrtxtrnpm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gtzcltunrv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtzloylzjk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gtwegkgjul.html

[C10] 变量作用域
来源：http://dali.yonumen.top/Article/details/gtwdvvvqqm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dianchejie.cn/Article/details/gtzfxzlfmy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.havefunace.top/Article/details/gtwwaqagrr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gtmqwrquff.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gtjxcezwlc.html

Java: 方法内为块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtehcrjnkv.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtclfptzwg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnzurnqw.html

C#:   块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtnikwwdds.html

[C11] 模块导入与导出
来源：http://dali.meibo888.top/Article/details/gtellgvslo.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gtdkxyzlli.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gtwczamvnv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtbcfczmwi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gtvoejduuj.html

Java: import java.util.List;
来源：http://dali.vqdsnc.cn/Article/details/gtutkwjekv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.snrcjt.cn/Article/details/gtponlcdob.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gtzzrbczga.html

C#:   using System.Text;
来源：http://dali.sxryk.cn/Article/details/gtwutswtsp.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxinkj.top/Article/details/gtncifmicg.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gtmnoypewy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.iojbl.cn/Article/details/gttvwmwqml.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtzayyhqii.html

TS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtprfsciql.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gtztqglqrg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtbztrueho.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gtssqefcbg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gtjgmyhiba.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gtlvwekzja.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gtgsutodxe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtfchfbakk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gtbzvawmss.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtlgxvztpo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjdzhdps.html

Go:   func add(a, b int) int
来源：http://dali.quarkkingdee.top/Article/details/gtuxnifqbm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shangyingyoupin.top/Article/details/gtlghirrxv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gtmlqziffn.html

[C14] 泛型函数
来源：http://dali.sufxvd.cn/Article/details/gtijgpavii.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xinyue.icu/Article/details/gtfgabwnru.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtnzicgbpr.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gthefjxuoq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gtkvlxamka.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gtiwmuvnhk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyfwcaad.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtgrycqeje.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gtfphwdtsv.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gtzxudtlbc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xziqi.cn/Article/details/gtanlnebaw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gtfhbaqxxn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtlzraoqtl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gtkpaaztgy.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gtavzmujxs.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gtltueekic.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gttybmomlt.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gtqtavmoqc.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gtnpogmltb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxinkj.top/Article/details/gtvyuoimrx.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gttiyenwlh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gtsfabwwkh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sxryk.cn/Article/details/gticwlgsdt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ehwqpu.com/Article/details/gtzyfrxhpq.html

Go:   // 无重载：用不同函数名
来源：http://dali.fzhhl.top/Article/details/gtigqvcgeh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gtlnslvjxb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gtodglmkwl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvsezfwml.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gtahteflru.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtspiinvuf.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtwhfycomj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtvptdrkbr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtgtmmoudz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtpxluzyaq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gthgsmbgtg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtgldterbv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ydzc1.top/Article/details/gtdwgehyxd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gtzykpxdvv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gtuckfsati.html

[D02] 追加元素到末尾
来源：http://dali.sysykeji.top/Article/details/gttsuvtwgt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtolyexoai.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gtmbgogshz.html

JS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtcgclnqku.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtygaozfbg.html

Java: list.add(4);
来源：http://dali.hysaishi.cn/Article/details/gtoqgdihld.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gthpgpfmae.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xinyue.icu/Article/details/gtfzzjduqr.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gthhyoidia.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gttaekexpl.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtwdxtbbhq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gzhubu.top/Article/details/gtlscmdosx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yvedp.cn/Article/details/gtnuqrqyca.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtcjfsyhba.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtimxdeidu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gtgdxlnmiw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxinkj.top/Article/details/gtwntstccw.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtscqjqfen.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtohdfmyzp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gtfbjsvuaa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.meibo888.top/Article/details/gtnuftrlmj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yvedp.cn/Article/details/gtlzytnhcl.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gtttcynfdm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gttzvcjyyh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenjidiqi.icu/Article/details/gtpajscwwc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtlxsyvpoe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daria6918.cn/Article/details/gtqjgbtacr.html

[D05] 访问与修改元素
来源：http://dali.yj20258.top/Article/details/gtqdzwpfkr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtfdqbjfqm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtvsfhvrfl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtcwbbfnno.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.9152youxi.cn/Article/details/gtilpwskjc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.c1oappe.top/Article/details/gtzpzjcyqs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtetseppbh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gthrnclkin.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtcshqvkjo.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtybuzvqkg.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtnmobbtvt.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtuiffokkz.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtoitflyee.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gtndosmhfg.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gtqhrxpgde.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gthauqkwuy.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gtfnxoxglq.html

C#:   list.Count;
来源：http://dali.hfpthk.cn/Article/details/gthqwebnfx.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gtuyqwmdnw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gtwtgisnpj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gtzjzxiccb.html

JS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtbluorefu.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtufvetluo.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtgalxpctg.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gtbrwdzcpi.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gtrtbvyobj.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtjqfvlnpn.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtafluudiu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtizagklej.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gtmsrqbpdc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gthrztdoyn.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfohujzr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gtmwzklhnv.html

Go:   append(a, b...)
来源：http://dali.aizwys.cn/Article/details/gtrursmsjw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cdnleiting.top/Article/details/gtagbiqsek.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gtdexautvi.html

[D09] 排序（升序）
来源：http://dali.jinqigufen.top/Article/details/gtkgbblrfb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtmuvapecz.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gtximnvrop.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtuekrutyj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gtcfdceatr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxinkj.top/Article/details/gttyndgyur.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtxhuoyrvz.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gthxlkbwzo.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gtupeprxpk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtucehxryb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guannengcc.top/Article/details/gtducjncyc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtklcghwpm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtkrdcqqlv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtnoirzfoq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtasbbmlci.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtqkassofe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gtllvhfxzy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gtnkfrnhvg.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gtuyijgwpg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gtbdxffgya.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtmvjrkhvg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gtkengnsac.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gtmjmhirjd.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gtlbkoonzq.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gtufrkjroq.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gtojqddkjb.html

C#:   list.Reverse();
来源：http://dali.fzhhl.top/Article/details/gtrciianwz.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtopeumcdy.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtmvafzibo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtccoiodur.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtcqifrogm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtzgjmmprj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtrcfdooex.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtrvmgwtoi.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gthijalnvn.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gthuzafcwc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjihzporj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gtkpchiklc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gteaqwgjmq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gthnjfnxzn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtjiepshwj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gteakxucyb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuxming.cn/Article/details/gtxklsvksl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtascnbneh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnmelotp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gogol.net.cn/Article/details/gtctadygms.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtkonfzxmb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtulxkghji.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtneyizygv.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtwcsqltep.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gtpkhbppyz.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtcmebjbld.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gttehmdior.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gttwyosmfy.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gtkrutcdlj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtbouonubp.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gtgmqbqgma.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtskkipmyl.html

TS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtmhkvtooh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gtksmoelkr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gtdymptyjm.html

Ruby: arr.uniq
来源：http://dali.nanxinkj.top/Article/details/gtxxzptqdl.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtfoayszyk.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gtgxeslhxd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gtakteiskp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yueranfly.top/Article/details/gtdtfihmbo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtpdohznmn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gthhlxdzgo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gtkbpwzpfz.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gtnhwgyijg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gthkiedlda.html

C#:   list.Sum();  list.Average()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcauwnnw.html

[D17] 最大值与最小值
来源：http://dali.hysaishi.cn/Article/details/gtjexbnqtu.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtjuufqqvg.html

PHP:  max($arr);  min($arr);
来源：http://dali.smart0.xyz/Article/details/gtiujfingi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.havefunace.top/Article/details/gtdwgsxrwa.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gtgunqbtdd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtxcftmriw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yueranfly.top/Article/details/gtwnyfapks.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gtqzhxksxg.html

C#:   list.Max();  list.Min()
来源：http://dali.andypj.xyz/Article/details/gtvaddplnk.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gtdocvizvk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gttavgblzi.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gtfnhmgnxb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gtkkhiwxay.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gtykmiwoym.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.snrcjt.cn/Article/details/gttfqoyrsl.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gtophamldv.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gtuisbjpas.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gtltvjsnlx.html

[D19] 按字段分组
来源：http://dali.iojbl.cn/Article/details/gtkygxlnpq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtrjwuyahz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nwbrower.top/Article/details/gtpltnqztv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gtyvjgngpa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtlkdjajgx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gtlozhdyli.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtxeaeltds.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gtgodigvkd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gtlhefscxc.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtywdhrako.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gtgyflmbsf.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gtjpjattdx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbjfkwme.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtcrrjkprt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gtigqakikw.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gtdexbenea.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gtfiznwwbt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gaohongyu789.top/Article/details/gttwvitfja.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtyzkmkylh.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtrgtrlkfl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtkdfhhqsd.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtthhsdtby.html

TS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gttbwqbkke.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gtbfdogdaz.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwcqwdep.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gtolzxbwuj.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsaiunfx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtqzifhasj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtlvlfcjqs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gtklyemahq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gtfuyflges.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gtbkfypllu.html

Java: new ArrayList<>(list);
来源：http://dali.9152youxi.cn/Article/details/gtwrmdwmwq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tianlin.xyz/Article/details/gtckiqxhnp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gtvcxwkkiw.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtnklstomf.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gtnpbuuefj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gttplcpthl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtulzyjoaw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtxbpjirnd.html


<!-- 参考信息 -->