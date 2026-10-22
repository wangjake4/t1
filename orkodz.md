代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gt2mozrpmqm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yvedp.cn/Article/details/gt2xuiwerlb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhongyouzk.top/Article/details/gt2hplnblit.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gt2wqphvctb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gt2bddsyskb.html

[C03] 可变参数
来源：http://dali.quarkkingdee.top/Article/details/gt2mxwwpzcr.html

Py:   def total(*args): return sum(args)
来源：http://dali.yongpay.top/Article/details/gt2lmglghja.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgwudml.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gt2ecdpbrtl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gt2rqvybvma.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xylfe.cn/Article/details/gt2qnwjxwhk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2osneetpd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gt2geojzbbw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gt2frkdxzen.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gt2boifrjrc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gt2yxwtfooo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cashguo.top/Article/details/gt2xfbogqov.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gt2rcmronsq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gt2blrgdnfg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gt2lwpdkcry.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gt2oecxsnpf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gt2ewnoldfi.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gt2sfvoycet.html

[C05] 返回多个值
来源：http://dali.chenzaomai.com/Article/details/gt2uilquawg.html

Py:   return a, b
来源：http://dali.yonumen.top/Article/details/gt2pvhqbdqp.html

PHP:  return [$a, $b];
来源：http://dali.yongpay.top/Article/details/gt2flnuhnuv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sweek.top/Article/details/gt2yambrmrw.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2lnwvosto.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgfzy.top/Article/details/gt2bhyxtozn.html

Go:   return a, b
来源：http://dali.hnqzz.top/Article/details/gt2ngzaqmwg.html

Ruby: return a, b
来源：http://dali.aizwys.cn/Article/details/gt2gfjvojyx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwthayfa.html

[C06] 匿名函数 / lambda
来源：http://dali.gogol.net.cn/Article/details/gt2xdcntqld.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gt2phpofkqn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2exkrdiry.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gt2vnoluzch.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2dwymxupa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jianghu66.top/Article/details/gt2svovhsfw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258.top/Article/details/gt2hfiaywrd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gt2vghpupqz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vnwyhekw.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gt2lspaafkb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dianchejie.cn/Article/details/gt2ydnddjvv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2xbudljjx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gt2difovupp.html

TS:   arr.map(String)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oylrvfpk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2tfipjfux.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gt2flzdqwpx.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gt2yjcsayhi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gt2myjlmwtc.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gt2eqrugwik.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jllmtdtb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hfpthk.cn/Article/details/gt2dzgzrmcb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ijkvcefc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2zrmnrfgg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gt2nwnnofzt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gt2rilhyrvp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gt2ydymhbly.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2vipelyaj.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wvynzsyg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gt2dtkbzzcz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2zlcjkaxp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nyobfdup.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gt2stezhpgm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gt2kpaowmjv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2odwjnrdn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2seiownas.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gt2emqagctn.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gt2acugwoec.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hywenlv.cn/Article/details/gt2rypmtquc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jlsjyb.cn/Article/details/gt2jwwuxpue.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilwzbvvy.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gt2qisjzeij.html

Java: 方法内为块级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2ziagqnwz.html

Go:   花括号块级作用域
来源：http://dali.yvedp.cn/Article/details/gt2efvvtctx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.vqdsnc.cn/Article/details/gt2qthyyelc.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gt2ojxjqdmz.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gt2qgqkbday.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gt2yywacsvt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rijcvqiu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258.top/Article/details/gt2xopzmwin.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.kuanghao11.cn/Article/details/gt2kipbfecc.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gt2bwfxwojl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gt2akodshdv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlxhajbu.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gt2yplkbbcp.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuanzx.com/Article/details/gt2qwzhufex.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gt2guuprjej.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shuidangran.top/Article/details/gt2agbfrbsm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gt2urqvdace.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gt2dzmyhjug.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gt2munmbcoc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xylfe.cn/Article/details/gt2atocaanp.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gt2krzgicmt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2dwnehrzk.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gt2awuzyfzb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkrsnloh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2tygnbbat.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gt2aaopdmxk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gt2atijangh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xjgkvhrb.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gt2atizqrfz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gt2qtjjqhti.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gt2bjycypba.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gt2wbmikkei.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gt2syslqaoa.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2isfjnrso.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2wysckkep.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bamqksco.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ggtwxbhv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gt2nczbpprx.html

Ruby: # 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2crxrqiaz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gt2nqjlgmdp.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gt2xgnhljln.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gt2xeeytnen.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258.top/Article/details/gt2uphngdmi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gt2guflgzir.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gt2pkrivcvm.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gt2hfbzhbqi.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2dpgfmwqm.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gt2roablxco.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gt2htvwehws.html

[C16] 函数 / 方法重载
来源：http://dali.yangfankeji.com/Article/details/gt2icodrkzr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2ijlqpqcw.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gt2ntyflgrw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gt2zdnfexah.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gt2ydalaxkt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2psxkcwpy.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gt2cxszdgvo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gt2uamhkoql.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gt2jaycyeun.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2gqaovoux.html

D. 数组 / 列表 / 集合
来源：http://dali.ivvv.top/Article/details/gt2hihkhwyr.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2brvtxwvv.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gt2pmeurupg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gt2fpeugean.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2kliyghlc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gt2mrkicjuz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cheryme.top/Article/details/gt2fkugppov.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gt2bczusjou.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvldwgkz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gt2xkbybpts.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangdashe.top/Article/details/gt2famljbny.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gt2xijoehnk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gt2ogprdpig.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkfujnpz.html

JS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gt2wteibpwl.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adkygdhr.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gt2rpykfgbu.html

Go:   arr = append(arr, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2iksdigrf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gotoacloud.top/Article/details/gt2qxmtuzax.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2riltwtrr.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zgifqmbk.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohmqiifs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cheryme.top/Article/details/gt2wiprzjfl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcxtpzeg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2tfcinnyj.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gt2bcpqjhlt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcdcgdlp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gt2csrwgxrq.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2bvdmppyy.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gt2xlgofrya.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cheryme.top/Article/details/gt2nkrafjgw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2qflwrmdf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj202588.top/Article/details/gt2xvnqlqst.html

TS:   arr.splice(0, 1);
来源：http://dali.redwolf501.top/Article/details/gt2iherxzmu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khnlitgy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gt2ovegrigh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nwwuvrzg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gt2doewvggj.html

[D05] 访问与修改元素
来源：http://dali.tian-w.cn/Article/details/gt2mnbukvjw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gt2shcahycz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gt2pqbavdqx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxxywffm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gt2alrhmyjh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gt2tadfvsdz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2kzgpeojd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2sqrbpeur.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2klcvzeok.html

[D06] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gt2oatcqpoy.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2bmrzaocv.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2lteuvogq.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gt2mcqtgrbe.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gt2tmifyahj.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gt2glrymstr.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gt2uosqulzm.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gt2beeyctax.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gt2nizooeyx.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gt2rsmseweq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gt2ylmepmhd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gt2vdbucjyt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2jqeqwbnl.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2wbfauizd.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2kktzrklv.html

Go:   arr[1:4]
来源：http://dali.yueranfly.top/Article/details/gt2pgmngeyz.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gt2eakcglpp.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2ctmeuatb.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gt2mursradi.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gt2mqgcyexv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvjbmsny.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gt2tiacnphd.html

TS:   [...a, ...b];
来源：http://dali.hfpthk.cn/Article/details/gt2ngxuacvw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gt2ltgjfdew.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gt2ynjznomy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwvihwez.html

C#:   a.Concat(b).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2jqrydqfc.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gt2mvgnupra.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gt2guiomosf.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2vrqaapax.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gt2krmthkfw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gt2cdfcbeaa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gt2ijvqmsxh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajdymrlr.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gt2izbrkkoh.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gt2uqwstolg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gt2wlenwtqc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nukpqjkg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gt2eycftiik.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gt2gepixewl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gt2rzyhuder.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jianghu66.top/Article/details/gt2qdwiblme.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gt2dgheoaoe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tanke756.top/Article/details/gt2woaduhyp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gt2icktsmxc.html

[D11] 反转数组
来源：http://dali.iojbl.cn/Article/details/gt2xsmuewso.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gt2wbxjckji.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2lirsfyka.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gt2sqqrpyhu.html

TS:   [...arr].reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgqbkamx.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kijwapxn.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gt2kzqioenz.html

Ruby: arr.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2myxzgqzb.html

C#:   list.Reverse();
来源：http://dali.yvedp.cn/Article/details/gt2oqbdlcoo.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gt2vborwooh.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gt2mwqqjkln.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuxming.cn/Article/details/gt2zwyiggab.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlckamyu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gt2cbsqavdj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gopwlntm.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2xjcjnwsn.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gt2tzlwfgup.html

C#:   list.IndexOf(x);
来源：http://dali.yonumen.top/Article/details/gt2lkponnyw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gt2uigluslo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xinyue.icu/Article/details/gt2qcfgppqx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2oabsjsoe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gt2cywmajkj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2iyojbyxc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gt2mzmnohrx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gt2fsufgayt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhixingplan.top/Article/details/gt2qgeyhqfe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2mpmrrmht.html

[D14] 映射转换（每个元素变形）
来源：http://dali.kuanghao11.cn/Article/details/gt2gxyndsww.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gt2irlodvww.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gt2aiweamji.html

JS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gt2fpexwvck.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gt2peqdegsn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gucxfnmp.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gt2laukbyyp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwzdfbxp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2hywmfxvv.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gt2ozeyezip.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gt2olgettvb.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gt2akcabewx.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2vjwmqrsw.html

TS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2rmeogwow.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgufenzy.top/Article/details/gt2sjslqyyn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gt2heujqebn.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gt2jzifliob.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2ewrlqhhq.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gt2bxchbpnh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2emcyzrpf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2nzitfips.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2wrbcwgtd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2qxmierlx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gt2bglyhrou.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oviadebd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shuidangran.top/Article/details/gt2wpepacpa.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gt2obrdxygl.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gt2xwtkzqig.html

Py:   max(arr);  min(arr)
来源：http://dali.gzhubu.top/Article/details/gt2hdvbinol.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gt2xcbgdcxo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gt2aoiydmwz.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gt2tegqcqva.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guowangkeji.top/Article/details/gt2azglziwi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gt2rcqonsiv.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gt2uymmsrfu.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gt2hhguzomu.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gt2nwmxtvvy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gt2fmvemtpk.html

PHP:  array_merge(...$nested);
来源：http://dali.aibaodan.cn/Article/details/gt2pxoadqhj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gt2hudmbhsr.html

TS:   nested.flat();
来源：http://dali.cqqwz.cn/Article/details/gt2kzhumdjn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fzhhl.top/Article/details/gt2fthrfnso.html

Go:   // 手写双层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgshxbzj.html

Ruby: nested.flatten
来源：http://dali.cucudq.cn/Article/details/gt2gcefamaw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2koshrfxc.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eabxpgqx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gt2dhwpmckq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gt2tiemwpaz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gt2kdwnscet.html


<!-- 参考信息 -->