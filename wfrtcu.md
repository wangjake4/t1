代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtncxdtcsb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtpwfxifim.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazsjkeur.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenzaomai.com/Article/details/gtoeiceysu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtcmtltvec.html

[C07] 把函数作为参数传入
来源：http://dali.dianchejie.cn/Article/details/gtbcpgmszl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.redwolf501.top/Article/details/gtfmukzqqn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gtfwaagrde.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gtcojzuxrf.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gtbcjjyuhw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtefueirax.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jlsjyb.cn/Article/details/gtzwdnldxw.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gtzpzngkjc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gtsqlojeuo.html

[C08] 闭包
来源：http://dali.guannengcc.top/Article/details/gtkszpnsuw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhengqikj.top/Article/details/gtdavnzfrv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gthgooycux.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtvholyvfw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtaddfzlaf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gtgjftexsr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gtddoxddnt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jyoumei.cn/Article/details/gtaiwwfoud.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtcsjohfck.html

[C09] 递归
来源：http://dali.kuanghao11.cn/Article/details/gtcptrbrzc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtcxylcese.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gtzpofpoxr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gttwuocaht.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtneuosuqy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtivokwcws.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cashguo.top/Article/details/gtcvfrndzl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtqssluive.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtbpmkpkxn.html

[C10] 变量作用域
来源：http://dali.yj20258888.top/Article/details/gtedvgvodp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daxiang520.top/Article/details/gtdpmyakzg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gtotvjgwmp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtkugsvedp.html

TS:   同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtpxgfqhuh.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gtzzavqkgr.html

Go:   花括号块级作用域
来源：http://dali.guannengcc.top/Article/details/gtcswckeyp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gteveatdrg.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gtxvknvquk.html

[C11] 模块导入与导出
来源：http://dali.xziqi.cn/Article/details/gtqpcjfbeh.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gtttqblxla.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuetiantiany.cn/Article/details/gtekuxdlgt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtpsynxbcw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gtcmweqdxh.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gtughsjlbb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gtzhbqwire.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.bjfxy.top/Article/details/gtczbnvoqz.html

C#:   using System.Text;
来源：http://dali.wangshuangyany.cn/Article/details/gtykbmdhiq.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258888.top/Article/details/gtsdamfdxg.html

Py:   (lambda: print("run"))()
来源：http://dali.hnqzz.top/Article/details/gtvhphjdzi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuanzhike.top/Article/details/gteuolsuzn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtvydjbbll.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtmtxpywaw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gtfrzqjrkx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtyslnwapx.html

Ruby: -> { puts "run" }.call
来源：http://dali.cashguo.top/Article/details/gtoizcysmv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gtnlkxfpof.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gtamkpdhft.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gtvlungkxr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtwfwzzrit.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gtfvttrqfq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpohwiswo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtoneqjkxx.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gtszxnnykp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gtsvuajbkq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hywenlv.cn/Article/details/gttseeshfi.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gtadkaputa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gtrjpxfjww.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtpkvhupvh.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtgmjjwpck.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yongpay.top/Article/details/gtmmimlqqf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gtbwfgachg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gtvjxxvviz.html

Ruby: # 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtwjjxkcgh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gtdtkgwwyk.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gtqenxplee.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.9152youxi.cn/Article/details/gtvokigyao.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gtvffksfdm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gttahequtv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtinhtozdl.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gthiuzpfkb.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtobkfoexu.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gtbolfdddw.html

C#:   var (a, b) = pair;
来源：http://dali.hnqzz.top/Article/details/gtwgycgdgw.html

[C16] 函数 / 方法重载
来源：http://dali.chenlongwang.top/Article/details/gttugvzjvm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtxdsjclqj.html

PHP:  // 无重载
来源：http://dali.bjfxy.top/Article/details/gtjadwngro.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhengqikj.top/Article/details/gttopdudru.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gtbxkqxuxr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gtaispghps.html

Go:   // 无重载：用不同函数名
来源：http://dali.jianghu66.top/Article/details/gtqxvimtsz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gtbcxksswu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xziqi.cn/Article/details/gtknfdkfer.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtatyggtoo.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigufen.top/Article/details/gtbwkeilcf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gturlowhwz.html

[D01] 创建数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtpmguinfx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gtsklfxlto.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtbmvoegxl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gtvnxccboq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gthmltuqaa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gtbphltzte.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gtmreiztrs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gtxcnlqwfo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangdashe.top/Article/details/gtrojdrikx.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gthwnvntvs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtjmpoyvql.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gtijqgzbbu.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjgeflur.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtotusescd.html

Java: list.add(4);
来源：http://dali.havefunace.top/Article/details/gtyykpeobf.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gtzmtxtpou.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gthuunrvhx.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzixwcve.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxddsecl.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gtgwvkxieh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtusuwckoq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gtfqvptujv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gtvzjxwgox.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gtnjunjnwt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gtrrzahmfi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtkalmdseo.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtovqnsjnf.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gtxezctmkl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtejrjnwll.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daxiang520.top/Article/details/gtpbyllbrf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ivvv.top/Article/details/gteuadhpbm.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gteikozaay.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtakqnselk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gtktgpniew.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gtiyunzopl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtijeusmiv.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtixznkiub.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtvtkkhigs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtahxhpegw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtwnllqkgj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.vqdsnc.cn/Article/details/gthbcyypeh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gtfctoarhg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtbvlaickm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtbvmfympj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtkhzodiej.html

[D06] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiewtwkko.html

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtlstfrign.html

PHP:  count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtodyweqfj.html

JS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gthshrsjsw.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtycibrmyl.html

Java: list.size();
来源：http://dali.yvedp.cn/Article/details/gtffkedtre.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtgzuwlull.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gtkbtzpfis.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gtlzctgqvt.html

[D07] 切片 / 取子数组
来源：http://dali.yongpay.top/Article/details/gtjvjwbcvk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuanzhike.top/Article/details/gtwrkidpfp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtcgbajfat.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtflznvdvd.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtxwasyczm.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtopfvsbxo.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gtthnwbuyt.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gtiidfxyhf.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gtkfdhqmyv.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gtcmfjeuvj.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gtsnaqwpuc.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gtpvxhsvyz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gtptaidscs.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gtpitcsemr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkggkcjxc.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gttxccdaqm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gtmiqlgxdt.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gtdzrhsxxy.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gtozakzppi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtnlehvxar.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gtqjvusrgy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hysaishi.cn/Article/details/gtbffsjoqq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gtmsjiaozt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gtisxzdjvm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfzswaej.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtemlatupn.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gtowqeycsv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtvvhrnenk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangdashe.top/Article/details/gteaewpmkp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gtrdrlzloq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtsfbxeigc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtvsmpoosf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxasydha.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gtkjvgzsrz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtorwimiaw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gtwiswkiqr.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gtnzfrmzis.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.havefunace.top/Article/details/gtcasoroms.html

PHP:  array_reverse($arr);
来源：http://dali.sufxvd.cn/Article/details/gtfyrqfpmp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgmoevtt.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gtthmbckmk.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gtxcoduveb.html

Go:   slices.Reverse(arr)
来源：http://dali.pycfn.com/Article/details/gtmarouyhd.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gtofphwvcr.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gtyzutxieo.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gtpjtubxck.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gtxkzitekx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gtrtxfinkg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtrzyzthfo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtvrjojidj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgufenzy.top/Article/details/gtipgvttht.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gthpmzreey.html

Ruby: arr.index(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtdzhsrukc.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gtnijcvqey.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gttkgnemnf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gtnwhhbtes.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfqtkhll.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtmnpsgaiu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtfgyfsggz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gtcaklsoxs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtdxxxvcoz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gtevfdmxrs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtsygzffqu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gtxxhcpvuj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzhrfcxq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtayyzkodw.html

JS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtbmgyxvyk.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtlrwhohek.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gtxnmlcgkq.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtjzxoyqpp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtkikvghlr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtepkawzgi.html

[D15] 去重
来源：http://dali.sxryk.cn/Article/details/gtkjwxqhoa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtzgipyltl.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtvuxkhigd.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtcplylxtg.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtbmleexur.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gtrnalvpwc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gtnvhiuabl.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gtrxxziait.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gtyrntjrhc.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gtjzlxbxqi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gtybopikfw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtgajjacse.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtpctzpfme.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtudctpwus.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gtyekntznv.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gtabiwdlhx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gthtiwskfx.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gtyoxlrzsx.html

[D17] 最大值与最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtvakgsokn.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtygspqbba.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gtoljcxalg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gtpvmwncke.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gtguoxhxaj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtgrvwvnwj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkhiwwci.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gtppngpozl.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gtfzxozrfl.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gtndslrskb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gthbvcoxwe.html

PHP:  array_merge(...$nested);
来源：http://dali.andypj.xyz/Article/details/gtujrmgasd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gtdaiwdpqv.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gthnnegawd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtlcinbamd.html

Go:   // 手写双层循环
来源：http://dali.aizwys.cn/Article/details/gtqpkcbcjb.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gtajiogiph.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqidisqh.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gtdhurdebb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gtsrabepte.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gtthewqnuh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gthvixntmo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtexfujdnb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.redwolf501.top/Article/details/gtfjopljlp.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gtvaookppv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.c1oappe.top/Article/details/gtfckeerxs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gthjgpvyhq.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gtmqsgwdmw.html

Py:   Counter(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtygyenjei.html

PHP:  array_count_values($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuephjgr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtejvxpsqp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtnljrprin.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shzxlz.cn/Article/details/gttvluyhsm.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gtuszptcmx.html

Ruby: arr.tally
来源：http://dali.gzhubu.top/Article/details/gtwjipszxl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gtiywpdgco.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gtujrnugnr.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpeeelqne.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gtdcocnobj.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtmftfjgog.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtmxgkkjlw.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gtvtncxfxu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gthgogvzig.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gttbapgvda.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtdgmaydav.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pengpengdd.cyou/Article/details/gtlfhwedrb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpafonujj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gttkjvfjls.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtatvhtfbh.html

TS:   [...arr];
来源：http://dali.bjfxy.top/Article/details/gthyidhetq.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gtbjomihzw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gtvilvveyn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gtkufwxteq.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gtgwcugjpu.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gtuzuvjfak.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtexlbstzb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtaiwgjcet.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gteekylzgi.html


<!-- 参考信息 -->