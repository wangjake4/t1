代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.dashuyun.cn/Article/details/gt2rkvtcdbn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gt2wcowvxwf.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vohxnztz.html

[C05] 返回多个值
来源：http://dali.jinqigufen.top/Article/details/gt2ypzfgxgo.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gt2zylzjwxh.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gt2havugqki.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gt2nhnrljgb.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gt2ritmrcrs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnqzz.top/Article/details/gt2jmylxslw.html

Go:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gt2wdmmjxnb.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gt2qbndrjty.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gt2tkvbrplr.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxinkj.top/Article/details/gt2vhexwdck.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gt2dqmdfdml.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hysaishi.cn/Article/details/gt2qwbuozkt.html

JS:   const square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2kyodglcb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgvdmole.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2dwdbwnkr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gt2ltyqppgt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhongyouzk.top/Article/details/gt2evognbfw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gt2kpafodep.html

[C07] 把函数作为参数传入
来源：http://dali.sweek.top/Article/details/gt2ldeshwrx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sysykeji.top/Article/details/gt2zywqstsz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpuozba.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gogol.net.cn/Article/details/gt2ydxkecer.html

TS:   arr.map(String)
来源：http://dali.cqqwz.cn/Article/details/gt2srsccboz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gt2slpaicer.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2giaupxfn.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gt2qdazgejd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gt2zibetwrr.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gt2jhkrfhrk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gt2nudxrkib.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gt2vjqhxvdg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpffivit.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gt2upgyahhz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gt2ddgwxlba.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hammf.cn/Article/details/gt2aydqznre.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gt2bpigbvot.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gt2okvtrnpt.html

[C09] 递归
来源：http://dali.ivvv.top/Article/details/gt2vxtxepwl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gt2newkouyw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pycfn.com/Article/details/gt2uodbaitg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gt2fppkwfhx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkxtsubx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gt2lkhdaojb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cucudq.cn/Article/details/gt2vurhtsyk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2kmyouomp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oltbkxld.html

[C10] 变量作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjcvqfcv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jiagoushi.top/Article/details/gt2lpotgrpx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gt2fexthinn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2khehylml.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gt2kgpicahc.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gt2jrjwcnbz.html

Go:   花括号块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2dcmafges.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigfzy.top/Article/details/gt2jwefhhby.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2fzaweodo.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2doklrdgp.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dggttvvs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gt2yjzkpjob.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gt2axufyggb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sxryk.cn/Article/details/gt2irodjnsb.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gt2tfbymofj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gt2yqpacbop.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gt2uavsvtez.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gt2fxtdbsfx.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gt2jkvvimab.html

Py:   (lambda: print("run"))()
来源：http://dali.vqdsnc.cn/Article/details/gt2wkrmvome.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zycfv.cn/Article/details/gt2sfqjijgu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gt2pqowdime.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gt2evozjwtf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gt2abgxngis.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sufxvd.cn/Article/details/gt2corfqagf.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gt2bswvpont.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2qqrnjvyr.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhongyouzk.top/Article/details/gt2ewdnwced.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gt2qebzdldn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2emxshhed.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdvoxceh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2rnnfcswt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2dgxtolsr.html

Go:   func add(a, b int) int
来源：http://dali.yangfankeji.com/Article/details/gt2hmxkvsbf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gt2phtybyim.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gt2vhfufzac.html

[C14] 泛型函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2aafldihm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gt2hgekobff.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2pqjvlhvp.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2viiwqirz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gt2jftlokgs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2byyhttbp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ehwqpu.com/Article/details/gt2bityxwtm.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gt2pwrdyepz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gt2aiixikta.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gt2posvxkgi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.andypj.xyz/Article/details/gt2apsstlcs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ivvv.top/Article/details/gt2swulviiw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gt2eubnohsx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hazrzwhp.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gt2pocfvmgm.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gt2nejxwrtl.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gt2pjidrsas.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gt2djtcmlbr.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gt2ybnoipcw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gt2rnczaxbw.html

PHP:  // 无重载
来源：http://dali.zdqjudy.top/Article/details/gt2znrmrldp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gt2cymhrbqz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xylfe.cn/Article/details/gt2mgnzdmfr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adxjujen.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hziobgby.html

Ruby: # 无重载：靠动态参数
来源：http://dali.iojbl.cn/Article/details/gt2cmaynpag.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gt2gqayohyi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfgtrkwt.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixxbehld.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlmwmarw.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gt2oxswrjbo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gt2unddpzqe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gt2dctjqbae.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pycfn.com/Article/details/gt2bgrbqcqn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dianchejie.cn/Article/details/gt2uetnyewr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gt2rwapbblx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gt2newcajbb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgufenzy.top/Article/details/gt2dztjgzwb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gt2syassfqy.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gt2djdkcyxv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gt2shzpdhnl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.quarkkingdee.top/Article/details/gt2ptnleohj.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqalhajj.html

TS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gt2wzxgrizb.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gt2gekvqwes.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gt2kzhpbjsj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gt2wnfiqhvi.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gt2afuiexwb.html

[D03] 在指定位置插入元素
来源：http://dali.dashuyun.cn/Article/details/gt2ddnvmcgg.html

Py:   arr.insert(0, 0)
来源：http://dali.ydzc1.top/Article/details/gt2yrgjdhic.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czvsgoqf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gt2xemxvwiw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gt2erlycais.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2rlnbgksk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrdmoizy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gt2ixifcstk.html

C#:   list.Insert(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2piggsjni.html

[D04] 删除元素
来源：http://dali.yonumen.top/Article/details/gt2rxlzfxnw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.c1oappe.top/Article/details/gt2jadntxvy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2chnzgxbs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daria6918.cn/Article/details/gt2rrxyfryw.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gt2lokthjhw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gt2zwwscxbp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtjguoyh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yangfankeji.com/Article/details/gt2zxktpvcq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgyrdmxz.html

[D05] 访问与修改元素
来源：http://dali.9152youxi.cn/Article/details/gt2mrtpfhkw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2oldsyjhs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2kxlqqdiq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gt2hfluhixh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gt2ccvasrjp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gt2ressnvoo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2zawyacbe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2eqbabyaf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gt2ukqfyndo.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gt2kuwbgatf.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfhdadvc.html

PHP:  count($arr);
来源：http://dali.havefunace.top/Article/details/gt2whxiuayg.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gt2dhqmlrzo.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjdrgrze.html

Java: list.size();
来源：http://dali.yonumen.top/Article/details/gt2sgwlfyah.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2ofytgivj.html

Ruby: arr.length; arr.size
来源：http://dali.aibaodan.cn/Article/details/gt2vrakuaeu.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gt2jgbdgnfp.html

[D07] 切片 / 取子数组
来源：http://dali.yanxiufei.cn/Article/details/gt2ywgjnhyh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gt2dhwiezkm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2zufschri.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2tqbulecd.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2yzqkoqpq.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gt2kldnsalt.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gt2hdvwcmbs.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gt2zvemleme.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gt2ncdtmzax.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gt2obkuiqln.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohygmsdz.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gt2bhpbayyg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gaohongyu789.top/Article/details/gt2wevxazdi.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gt2fzwqjmzc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tanke756.top/Article/details/gt2cdssgdua.html

Go:   append(a, b...)
来源：http://dali.guowangkeji.top/Article/details/gt2ptgqjscb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msfnthyh.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2eeaqsrhy.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gt2fpxzjevd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gt2tzdosrsh.html

PHP:  sort($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2iqzmnuwc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gt2acflemou.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ivvv.top/Article/details/gt2nzzfhtjk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gt2rmenmyby.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gt2azfpkwhi.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gt2byhenbfn.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gt2yyboavhs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gt2dafumoxt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tianlin.xyz/Article/details/gt2tsoazrhy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gt2flidfofm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gt2okhsjxlz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gt2rtmvolbc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gt2jvyujgne.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gt2njsvlrpi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gt2awkozcli.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gt2pwktqbxh.html

[D11] 反转数组
来源：http://dali.zhengqikj.top/Article/details/gt2zstrdgtm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dygrzxly.html

PHP:  array_reverse($arr);
来源：http://dali.daria6918.cn/Article/details/gt2dvfypsvl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gt2sauembxf.html

TS:   [...arr].reverse();
来源：http://dali.bjfxy.top/Article/details/gt2xylvuhas.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2pvucidwq.html

Go:   slices.Reverse(arr)
来源：http://dali.sxryk.cn/Article/details/gt2qhubdmml.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gt2ukyhkbpm.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkfbzwnd.html

[D12] 查找元素下标
来源：http://dali.jlsjyb.cn/Article/details/gt2xrrtmdow.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gt2dwzldszh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gt2pxucrdhz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gt2uxhhysbn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2pqrsrkyc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gt2qqprecdj.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2ziyiaebi.html

Ruby: arr.index(x)
来源：http://dali.c1oappe.top/Article/details/gt2wzjjxrmw.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gt2ixuauscw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhcyypsp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sxryk.cn/Article/details/gt2lqfevihn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sufxvd.cn/Article/details/gt2zclshyms.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2ssebrpbk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gt2mbolwbph.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acnnstpt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sufxvd.cn/Article/details/gt2xphaokqw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gt2kmyehtbu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoyyofe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gt2xyphnbyc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tian-w.cn/Article/details/gt2bgocgaga.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yvedp.cn/Article/details/gt2jvdnmfaw.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2ybdrkxcb.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhsmsthi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2eyslffkg.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gt2npgzhmww.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2qqdqltzy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gt2msomhebd.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gt2ovpfxcmh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gt2igqtgydo.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2pjheddjz.html

JS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2tkeudrqm.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gt2mbvftcfp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.316326.xyz/Article/details/gt2twuucjeh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdisfooq.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpxgsjjo.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gt2obwcrrmu.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikijsiaf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2fmxuzkjp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gt2fyfgubua.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2rdkhdlnn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwjfaqhw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gt2hicbuetu.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gt2brodzapx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gt2ivrgiibb.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gt2uojnytfw.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gt2ugnctnqr.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2dvekiixu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2ocwkwmlz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dbwvinnr.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqgxxqaz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gt2cchnyduo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gt2aisrdvjd.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gt2eezdfqzv.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gt2lvresfhr.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gt2enqezvkv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gt2wnkjavpa.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gt2twihkvvu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jianghu66.top/Article/details/gt2qttmfsky.html

TS:   nested.flat();
来源：http://dali.hnqzz.top/Article/details/gt2kvgiclsc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gt2ncypkzpo.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gt2hcgstvuu.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpmuhonk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2vihryqwy.html

[D19] 按字段分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptefcwnf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gt2iwyjhxez.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnugaiz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gt2awbobhuz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gt2bcfrukgj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gt2tkrbadfv.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkxebuzd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xsuhkmmk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gt2jniyybca.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gt2dateznlm.html

Py:   Counter(arr)
来源：http://dali.xylfe.cn/Article/details/gt2vuiytvty.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2onlldfpv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gt2udcgvdrg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gt2hdbdtvsi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gt2mwoivssm.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gt2rjxeecjg.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gt2lndgxvdg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gt2ijpxysie.html

[D21] 判断是否包含某元素
来源：http://dali.cheryme.top/Article/details/gt2jdjlabvm.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2egclrrqf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gt2ozoygcza.html

JS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gt2hshowswu.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2cscbbhxe.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2gvngxsdm.html


<!-- 参考信息 -->