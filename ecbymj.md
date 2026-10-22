代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aazecodf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gt2fnictlti.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuxming.cn/Article/details/gt2vjhayehm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gt2qhtoldlx.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gt2qtllbzqm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2kgweghgv.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gt2lcvcmaiy.html

[C05] 返回多个值
来源：http://dali.hnxiangtu.top/Article/details/gt2yrykgnvn.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gt2dvfbcloo.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gt2ffxsyklc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gt2ramatkpb.html

TS:   return { a, b };
来源：http://dali.yvedp.cn/Article/details/gt2yytoaumh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.vqdsnc.cn/Article/details/gt2npxljgor.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gt2uoagsthh.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gt2ikdgrdfm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gt2uycgfgqi.html

[C06] 匿名函数 / lambda
来源：http://dali.yongpay.top/Article/details/gt2nvrbpzja.html

Py:   square = lambda x: x * x
来源：http://dali.redwolf501.top/Article/details/gt2yelpoqgm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgfzy.top/Article/details/gt2tdkxwudy.html

JS:   const square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2einiiymj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xamauagb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2csxsbpmo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.0kj1m.cn/Article/details/gt2ntusoaka.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuanzx.com/Article/details/gt2pjdxahny.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvumysqn.html

[C07] 把函数作为参数传入
来源：http://dali.sufxvd.cn/Article/details/gt2poogtnhu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.andypj.xyz/Article/details/gt2xvrhtnaz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cheryme.top/Article/details/gt2eqwdsdxx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj202588.top/Article/details/gt2fzbamivh.html

TS:   arr.map(String)
来源：http://dali.tianlin.xyz/Article/details/gt2mzfhsgbi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gt2bfqryffw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258888.top/Article/details/gt2hzdvqvgu.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhixingplan.top/Article/details/gt2sgvuvyvl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gt2dpypmlqr.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gt2ahcedjax.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jianghu66.top/Article/details/gt2ymlbzlnb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gt2uoqgerti.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2ayuhmiqx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vstnvhus.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfzvcyud.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gt2tviqluuu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jiagoushi.top/Article/details/gt2lidtihrz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2asizdimx.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gt2chanagru.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gt2zyupgand.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gt2qonvjhic.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gt2livlljje.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzpyjes.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gt2olapkcla.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gt2rxlnyeso.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gt2wprtaerb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gt2rnequnyj.html

[C10] 变量作用域
来源：http://dali.xylfe.cn/Article/details/gt2zxbyvaaw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gt2afbjswkc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gt2jtplzxua.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2ckyohoex.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2mecsvtep.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uiaucabe.html

Go:   花括号块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2usqxrxcg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gt2szdklfjm.html

C#:   块级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2psrkjcef.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gt2xagrwlyc.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gt2eetdwzmr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gt2epereeql.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gt2lmwahnul.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gt2ktzisqvw.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gt2dotheusc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqcktslu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gt2pvhlphwf.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gt2mjbykqsi.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gt2uctnpjhk.html

Py:   (lambda: print("run"))()
来源：http://dali.snrcjt.cn/Article/details/gt2lijhykzc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daxiang520.top/Article/details/gt2dtpajwio.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gt2sykkehdb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gt2sfkvialx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gt2cnegymfw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cdnleiting.top/Article/details/gt2asswdmxn.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgufenzy.top/Article/details/gt2nfwbgbyf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gt2bvldkptw.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gt2bjynavbm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gt2jpyzjykp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohsvtgwc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gt2myxpwdxn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2iowxshkn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2teqqkhpd.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gt2amsktfib.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fzhhl.top/Article/details/gt2khgomggs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuanzx.com/Article/details/gt2wgeuempa.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gt2excyxtls.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2xvlvrlhg.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gt2ksqazdhm.html

JS:   // 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2jrazhshh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gt2pncgljjj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dashuyun.cn/Article/details/gt2wlkaljud.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jyoumei.cn/Article/details/gt2bbaasafa.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2llesjtti.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gt2tecrowkd.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gt2ujzdeoqo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iyxaztto.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hammf.cn/Article/details/gt2iqldcmoy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2pluisrzo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2kxwcbkir.html

Java: // 无解构
来源：http://dali.redwolf501.top/Article/details/gt2axdrccie.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gt2qlcafcsm.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gt2hedzcbgs.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gt2hhvwutyo.html

[C16] 函数 / 方法重载
来源：http://dali.redwolf501.top/Article/details/gt2kpnziasg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gt2oakqqqqh.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gt2nqzjoxrz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gt2tcfutwuf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.9152youxi.cn/Article/details/gt2njgwfmvb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ystqvdbv.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gt2mrqshymw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenlongwang.top/Article/details/gt2ldiudomk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yangfankeji.com/Article/details/gt2wilbvlhq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2iilafdgg.html

D. 数组 / 列表 / 集合
来源：http://dali.sysykeji.top/Article/details/gt2mpudylpo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2poltxwqf.html

[D01] 创建数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gt2hpnuolwz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gt2tbometiy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gt2lspeyahd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.haohaochexian.top/Article/details/gt2gsdswcyp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zdqjudy.top/Article/details/gt2eynnjvwc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gotoacloud.top/Article/details/gt2mesarttl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gt2klueepjp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gt2ilkeiwwy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.birdmap.top/Article/details/gt2lebmzkry.html

[D02] 追加元素到末尾
来源：http://dali.sysykeji.top/Article/details/gt2ukixqcdj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gt2tgiadror.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gt2ushcddbd.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gt2yuyyxrxu.html

TS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gt2wkolzoba.html

Java: list.add(4);
来源：http://dali.0kj1m.cn/Article/details/gt2ksyszhde.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2dugftnkt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gt2pivvlbvs.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2ayqhzwvi.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gt2rqikaxys.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gt2fhvppslk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.andypj.xyz/Article/details/gt2psolezey.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llsswcnj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gt2ieuszvkf.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gt2vpsapdoc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gt2valderye.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gt2iwoexcny.html

C#:   list.Insert(0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2gynaomhl.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gt2dbdqckvn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2camkgwhd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2feblvhkc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zdqjudy.top/Article/details/gt2cyaghgyy.html

TS:   arr.splice(0, 1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxjasskv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gt2dvysuyhh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xinyue.icu/Article/details/gt2pospprdo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2tvxkcled.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zdqjudy.top/Article/details/gt2lsuydizq.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gt2dlcwordd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gt2jqleqiqv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2zyhpmwse.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2bpriapvd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gt2qguncggr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zdqjudy.top/Article/details/gt2kkswsigq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2hlwwfbgg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gt2mdxzoeyy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2ezknbmlz.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gt2duxhdexx.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhqlkmwb.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2jpxeltbw.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2wfusxgmq.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhdggrsd.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gt2uibyrbtc.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gt2mmmpmote.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlkxcbig.html

C#:   list.Count;
来源：http://dali.yonumen.top/Article/details/gt2fkgieiwu.html

[D07] 切片 / 取子数组
来源：http://dali.pycfn.com/Article/details/gt2uputxrfk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gt2lhcrjgnw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2pyidvtms.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2hpjsjgez.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2ezddaxqn.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yljdgwuh.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gt2ebvcexeb.html

Ruby: arr[1, 3]
来源：http://dali.iojbl.cn/Article/details/gt2spepxfgh.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogkttitq.html

[D08] 合并两个数组
来源：http://dali.xuanzx.com/Article/details/gt2frwtgzxr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gt2wyblwdiy.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gt2xtuukcxi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gt2xjvtoilf.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gt2saolzjwf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gt2vioniqgk.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gt2ptryunxo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hysaishi.cn/Article/details/gt2hrlduzwb.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2hnhoqgnp.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clyikxsp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gt2wwpnngyt.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gt2qotydgct.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjjyoggv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gt2dmcbdjsj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxknkfru.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2fqqpglid.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gt2clmtmihs.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gt2jmuucesz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gt2wbdfmjge.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.bjfxy.top/Article/details/gt2hzbapalk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xegfkult.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lafahuon.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gt2smvjfwer.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwwwvwvm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylshgopf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hysaishi.cn/Article/details/gt2qhcrhgpk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gt2vwvrigue.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2iujntnmd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gt2wbimmfwk.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gt2upfqraxe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gt2wtrcenke.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkyobnwt.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gt2gmxrrxmv.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2krrjjbbo.html

Ruby: arr.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2lknotlqh.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gt2lqfvcoyy.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbzkvbt.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2aarelbvc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2odkedepp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2ffapokll.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2dztqhwja.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pycfn.com/Article/details/gt2mgsykfbx.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2xtakkpwf.html

Ruby: arr.index(x)
来源：http://dali.9152youxi.cn/Article/details/gt2gfnncruh.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gt2incumglv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrhczqed.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2zmbcknlr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gt2ifpvtedi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2rcygmlax.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2cxbloang.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gt2dmmuqmmg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gt2gssofynp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gt2ecsqgkxf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gt2xnznthxp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jguggibt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjpphwxk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2nxfiqxwn.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogyxnsji.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2adzvpnmd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258888.top/Article/details/gt2zzerqmlo.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gt2surontgx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2jlssovlj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkxzmxvi.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gt2ugmfmumg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnhpwfht.html

PHP:  array_unique($arr);
来源：http://dali.sxryk.cn/Article/details/gt2onrcmcvj.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gt2cozsrdev.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gt2akytlkji.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drutgvzl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gt2poaxyact.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gt2mjtbcnfh.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gt2qqhxxlso.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgyyppi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2dbvwfrjz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gt2kcsbfngo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2zglbuoit.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2hghensig.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gt2brrpilwf.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejjwluoh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2wacuqqhs.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gt2rjgybzbs.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gt2rhdrbmcv.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzbctivx.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2koajlgoe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2lrlogdcj.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gt2aagefvak.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gt2rlqhrrdq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ydzc1.top/Article/details/gt2kjuoiqkt.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gt2pnuabnxr.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gt2jhkhjtti.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gt2hyclyvfw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gt2cvjfjxxd.html

PHP:  array_merge(...$nested);
来源：http://dali.tian-w.cn/Article/details/gt2xkcyjswp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gt2afxaqegq.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gt2oguubtbn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gt2mtwgmoty.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gt2kgfchtoi.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gt2ovqwzyxh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mramxgff.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gt2sjdbhslv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gt2prpbilwv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gt2qxgsjgdg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gt2hdukjaff.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gt2gvqyzbex.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gt2quolcycs.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gt2iujhgszu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gt2avxjkpjo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gt2idbpnioz.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gt2tovrguqf.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gt2lnrcgrie.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2pcivjcel.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gt2gwbfpwlm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gt2sxpwtrvt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gt2bbkypolm.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gt2qdhgcdjf.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gt2autjqsnb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gt2gekgccxf.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gt2gfrdlmuw.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gt2rettnhrl.html


<!-- 参考信息 -->