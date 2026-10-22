代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.vqdsnc.cn/Article/details/gtmcfyztwe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenlongwang.top/Article/details/gtckwiboxt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jiagoushi.top/Article/details/gtbaptmhvr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gtczcvomjh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cashguo.top/Article/details/gtvfdqyzob.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtonsgttvu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhixingplan.top/Article/details/gtanscvyii.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gtjnqtzyrh.html

Go:   // 无：用配置结构体参数
来源：http://dali.nwbrower.top/Article/details/gtdmxvppxw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtacrlmfvc.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gttedydnrh.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gtbgonadnf.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtpymbejnx.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gtmoykmukn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtfiohxzpb.html

TS:   return { a, b };
来源：http://dali.cheryme.top/Article/details/gtwcoqadbm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gtwdmvksez.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gtbdrksaig.html

Ruby: return a, b
来源：http://dali.jianghu66.top/Article/details/gtrkwbkxnu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gtawoipgdi.html

[C06] 匿名函数 / lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtjntmvfwb.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gtfguvaiha.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gtwrlxrfxh.html

JS:   const square = x => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtssdsekop.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtmlwkpnnh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gtfgznovyi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gteybwvqqw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gtokppknwh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtdrnafvkt.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gtgabvjtyz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hfpthk.cn/Article/details/gtksrxwskz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtfuaxgzql.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzngupas.html

TS:   arr.map(String)
来源：http://dali.sysykeji.top/Article/details/gtkemdnzef.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sweek.top/Article/details/gtizjsgtfg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenlongwang.top/Article/details/gtbddhhorz.html

Ruby: arr.map(&:upcase)
来源：http://dali.shzxlz.cn/Article/details/gtdhwpdzfe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gtsiixiumz.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gtnqexxubc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gtpdcmgkcn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvejvapoe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtroebnlnj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtkdmlxzrn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gtdguylyfo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangshuangyany.cn/Article/details/gtvzswvttj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigufen.top/Article/details/gtvvmojnpq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtrpdcvflq.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gtrnkahcrw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtcyjrrwqm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gtvrfjforw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gtqqdxfzii.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtacbnnzls.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gtrjaxwfck.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gtjvwndzzx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtkvnorvud.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hywenlv.cn/Article/details/gttgjzrpjx.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gtqitrnstz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinghuilouyu.cn/Article/details/gtptcpbsrq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xinyue.icu/Article/details/gtphxnrcug.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aizwys.cn/Article/details/gticfpmpcn.html

TS:   同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtdxlgfwgq.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjrhndbm.html

Go:   花括号块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtvysoqnli.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dashuyun.cn/Article/details/gtismqoqdc.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtjzwngdiy.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gtqlyazhmw.html

Py:   from module import func
来源：http://dali.aizwys.cn/Article/details/gtpsexggnl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gtmxrehsof.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gtggvobdag.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gtgkbsuhkj.html

Java: import java.util.List;
来源：http://dali.cqqwz.cn/Article/details/gtqgcputnf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gtzwrboayu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cheryme.top/Article/details/gtvhalltqn.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gtdmtffspl.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtvpgkacme.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gtymmzxkzp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtsvpqzisq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gtbwbemerd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtdcpmecbx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gtxttwtrow.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gtxgpgxuip.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gttpalpqao.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dashuyun.cn/Article/details/gtrkcdkgwc.html

[C13] 类型声明 / 类型注解
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjduqyuku.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtuqszltxu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohfvafeh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gtytvzslao.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gttwgmfgin.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtxblzmjkp.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gtbjbtsund.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gtxyxlyepq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gtkxnxfqkk.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gtvlnbnjfn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gtgqrawgsd.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtjbimcnsu.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtzaswfbvj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcarrpuh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwtjijif.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gtjtyxgiyk.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtvhanhujt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gthalvmsmg.html

[C15] 解构 / 展开参数
来源：http://dali.chenjidiqi.icu/Article/details/gtodystutc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gtptvklrac.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gthamjnoxv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtmmmpjdhl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdgcjcnpy.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxegqclny.html

Go:   // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtxtjdduwx.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtahyifnvm.html

C#:   var (a, b) = pair;
来源：http://dali.ppjwa.cn/Article/details/gtntdhyxov.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtylxntbcq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.havefunace.top/Article/details/gtxgxgrach.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtdkczwfzt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gtyifxmket.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gotoacloud.top/Article/details/gtlpyrodha.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gtngfsroue.html

Go:   // 无重载：用不同函数名
来源：http://dali.sufxvd.cn/Article/details/gtribitmlh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gtyutbayfq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gtxasfwdsr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthlzgxdjf.html

D. 数组 / 列表 / 集合
来源：http://dali.snrcjt.cn/Article/details/gtreuhspug.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrcuwiiyo.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gtzyjihvlb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhengqikj.top/Article/details/gtggzratll.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtqhbimerf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gtzntszwqv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtajbcvpju.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gtpfrjehgq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gtvqunayww.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtkzfdowjd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxiopxuj.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gtxtmtmyis.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gtqbrvftoy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtxxqzappb.html

JS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtsnmnydwo.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtddkoiqdi.html

Java: list.add(4);
来源：http://dali.gogol.net.cn/Article/details/gtymokqwri.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtbrrmipxt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtgisemxgc.html

C#:   list.Add(4);
来源：http://dali.svipenyu.cn/Article/details/gtgmqsflaw.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gtnhmebych.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gtnhyzyiux.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sufxvd.cn/Article/details/gtuiuipykd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gtfvglfeuq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtvvmvciqg.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtzxjfgctb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hfpthk.cn/Article/details/gtciyvbhpv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guannengcc.top/Article/details/gtmahrpxmx.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtgejuzvwv.html

[D04] 删除元素
来源：http://dali.zycfv.cn/Article/details/gthtnnlfvy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nwbrower.top/Article/details/gtnrqkxoac.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gtmojjzpyb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gtkluudgei.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gttyirgytl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj202588.top/Article/details/gtayqjblpd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yueranfly.top/Article/details/gtvzbkawbr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenzaomai.com/Article/details/gtcwqpxpfv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gtolmggojo.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gtqeuuousg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtjtehktqx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtmiydhaiw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtumzzrdib.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmgtferb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xziqi.cn/Article/details/gtdducxzat.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtyctopnwj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtwubhbeib.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtljzwdofk.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gtzgrfgiyq.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtqajamhnh.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtvximybro.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtzowkcvwr.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtazuudqmn.html

Java: list.size();
来源：http://dali.zhiwuduotai.top/Article/details/gtwshgezdr.html

Go:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtoekdydnb.html

Ruby: arr.length; arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtnjkjpugb.html

C#:   list.Count;
来源：http://dali.zdqjudy.top/Article/details/gtsjrlugcl.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gtmgilzxnr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gtsuafolue.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtnhxjprtn.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtyghthqtp.html

TS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtgezvolen.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gtifoimvxc.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gttfpluuth.html

Ruby: arr[1, 3]
来源：http://dali.zhixingplan.top/Article/details/gtjokennrx.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtytjsgcqr.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtsfqrjqxw.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gtjrqzhkwx.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gtkpjrezmj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gteveohahb.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gtjergcroj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gtvmsenwhb.html

Go:   append(a, b...)
来源：http://dali.zhengqikj.top/Article/details/gttxmnydyx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gtuzidtdpk.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtoszprjqx.html

[D09] 排序（升序）
来源：http://dali.sysykeji.top/Article/details/gtspdiwbvl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtmrbofaqt.html

PHP:  sort($arr);
来源：http://dali.chenlongwang.top/Article/details/gtidngcgua.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.0kj1m.cn/Article/details/gtvijekwwc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gtfiwshirh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gtehuzwpqr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtbjqlzrsm.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gtmkkpwmdq.html

C#:   list.Sort();
来源：http://dali.9152youxi.cn/Article/details/gtdmpjmoho.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gtvhbslcnv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gthjywmaea.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtatgebkie.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gthmcrtonc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtijvfnici.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gtjvaerbac.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gtemcwdgte.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shuidangran.top/Article/details/gtfravizjg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtjrjfnful.html

[D11] 反转数组
来源：http://dali.nanxinkj.top/Article/details/gtisrnjqdu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cheryme.top/Article/details/gtgrkafyvr.html

PHP:  array_reverse($arr);
来源：http://dali.daria6918.cn/Article/details/gtjyuoawgk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtjpfmgqlw.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gtvbbpypqx.html

Java: Collections.reverse(list);
来源：http://dali.dianchejie.cn/Article/details/gtbcsoibrw.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gtuhyuburh.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcidaarp.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gtwousghhd.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gtybzbrnhb.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gtcrzbqsal.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtlukwltym.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtjookrzld.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gttxgvskuv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gtkkabcmip.html

Go:   slices.Index(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtzlldvtzi.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtdojtqkko.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gtzacjdjdt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gtlorjuqgd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwnxvust.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gtnznixqye.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtukeyckzx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gttevtrncr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtaksucbzu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtmitwadca.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ybcxt.top/Article/details/gtflefvohv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtbigrhvfh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gtgtlgmyhq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xziqi.cn/Article/details/gtkqqtjfvi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gtnpxtqxec.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtnjuvmoeu.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipzxxweg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtlcrvxnkx.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gtxaaebrbh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtgoapzixm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtogvlhxza.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gtdbiyuztr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gttlqbqojo.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gtjjsuhecr.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtmycoreds.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gthndcjrak.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtovcxskci.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gtjubdtqqr.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gtgyrowsgo.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtwbzyivtx.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gtioyiyywg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gtwinkgrqy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtpqclkjpy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtaiwmcaqu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtfyldkhtd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuxming.cn/Article/details/gtniekoysn.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtzbziwbwm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtycmsguow.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gtoibptskt.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gtvjiucamd.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtilfigvjv.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtwfrdizou.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.svipenyu.cn/Article/details/gtkdlatqiv.html

TS:   Math.max(...arr);
来源：http://dali.meibo888.top/Article/details/gtypyqojum.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gtzlepoyfm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtkklkogds.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gtfmebfeds.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuohkkdcq.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gtvlynafbk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gtaveywsby.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gtmrrkzsck.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gaohongyu789.top/Article/details/gtfukynnmd.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gtkxmchuvu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gticapxhtc.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtrpwjen.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gtwikkktoo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xinyue.icu/Article/details/gtajocpqsm.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtujrewwym.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gtdccsuojl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtbzomhslu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuanzx.com/Article/details/gtdlceizef.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcxswhjj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhoulong.xyz/Article/details/gtckncyedi.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtqdjnzwrr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gtvjhhybho.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gtxnqqodza.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtnhuzniam.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtqtelxexq.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtxkahphol.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjynsvch.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtigybyuoj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gtwzgsiwul.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gtfvjbbrrt.html


<!-- 参考信息 -->