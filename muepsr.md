代发 wailian999

Py:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtuwgqmevu.html

PHP:  return [$a, $b];
来源：http://dali.hammf.cn/Article/details/gtyujofrje.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gthskmdsug.html

TS:   return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtbxcssfbr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtvfwodudj.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgcodtbu.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gtrweyihta.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrvzlbci.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gtipfggwne.html

Py:   square = lambda x: x * x
来源：http://dali.xuetiantiany.cn/Article/details/gtvmynxrmi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gogol.net.cn/Article/details/gtpawiuael.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtsxzfgilt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.snrcjt.cn/Article/details/gthaxoiwst.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gtdkqczdgv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gtuomvksdv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gtwpqaiugd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gtbvgwmkmm.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gttejkqjqg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gtapzasivg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jianghu66.top/Article/details/gtwwxgxlvr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gtsecwlkpk.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gtrrawbgqu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.bjfxy.top/Article/details/gtnhrdfwpq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gtqdutbtdv.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gtdamxkxux.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtclodswwp.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gtwghtgnbg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gtabuvwdah.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hfpthk.cn/Article/details/gtobgmycbx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtewyqdkab.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtnmnjnzts.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gtsxsiiuaq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigufen.top/Article/details/gtxnnvduog.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daria6918.cn/Article/details/gtnupuqwjo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtwrpfmvns.html

[C09] 递归
来源：http://dali.yonumen.top/Article/details/gtkiltupfa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gthqwvarox.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtecmhmvrm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtxzpoybuw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gtwnzkiepk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtzwccxklh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhixingplan.top/Article/details/gtyqhtipzy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtvgiorqst.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtvykgnkbb.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtlfzpaber.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gtpwnqvlyd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gtiyyxajjl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.andypj.xyz/Article/details/gtniciociz.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gtybfmhsgu.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtwuzqreug.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtaguxtqnn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gtuigghxpm.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gtzegaofca.html

[C11] 模块导入与导出
来源：http://dali.havefunace.top/Article/details/gtrowregdy.html

Py:   from module import func
来源：http://dali.shangyingyoupin.top/Article/details/gttsitncnd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hysaishi.cn/Article/details/gtmqigcsyq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrfbdfpj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtzhrehjnj.html

Java: import java.util.List;
来源：http://dali.zhoulong.xyz/Article/details/gtcoulolgb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtysxntqnw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gtmdyydnxp.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gtgnrsmunw.html

[C12] 立即执行函数 IIFE
来源：http://dali.shangyingyoupin.top/Article/details/gtpmrllslt.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gtnvimxyws.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtxrrmcdpj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtdjyfozqx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtseqwirmj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxuanxn.top/Article/details/gthpgsgmoa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gttbvzvofj.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuxming.cn/Article/details/gtfawrzxbe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gtorfwlgzj.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gtxqmmbkzw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aibaodan.cn/Article/details/gtzxmteknu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtubuivgtt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gtdzjcuhgm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtbnkhyhwc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtuyeaacge.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftkbolsh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gtrodwaidh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gteqhdmhzr.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gtzizokdev.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gtihadpyiy.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtyflpknka.html

JS:   // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtopjwemqw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtqxogsfsi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ppjwa.cn/Article/details/gtxwchfoxu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchoizgej.html

Ruby: # 无泛型
来源：http://dali.c1oappe.top/Article/details/gtfxmyqsyk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gthgewedhm.html

[C15] 解构 / 展开参数
来源：http://dali.mhx1999.top/Article/details/gtawvpvbqx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gttkgcawsj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtcpjinjcw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtfbwjqrlv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgfzy.top/Article/details/gtkvgivwko.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gtniknjwuv.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gtjtqkhvam.html

Ruby: a, b = pair
来源：http://dali.jqgfzy.top/Article/details/gtmvpnlqgm.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnmijaxu.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gtpemkvmru.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gtfvwocwlw.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gtbdcyxvuf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.redwolf501.top/Article/details/gtxzblhojq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ehwqpu.com/Article/details/gtkxoesdmm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nwbrower.top/Article/details/gtzrsndcqw.html

Go:   // 无重载：用不同函数名
来源：http://dali.gaohongyu789.top/Article/details/gtozwiiyeq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gtsmiwemtv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtkvcpanrp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkhxbnaus.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtcywshcsw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvzrxlxwc.html

[D01] 创建数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gtahrjmnjs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.feifeiyinyue.top/Article/details/gtugpbrtbw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnqzz.top/Article/details/gtgveqycqc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gttwzdyuwv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtqirsqxyl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gtyplpwnvv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fengsongda.top/Article/details/gtbrkvdrkq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gtnwejront.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gtztwitetj.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gtufmfgjcg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gtmamondrt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gtpittmsql.html

JS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtygsjtxea.html

TS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gtbweotiay.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gtfnejlfod.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gtrldmujix.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fzhhl.top/Article/details/gtqifnkomr.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gtsdsnwfmw.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gtngtgxlxl.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gtpisqzrnf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hywenlv.cn/Article/details/gtfwbpotcz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gtivxvyvzx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtibhvvkzm.html

Java: list.add(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtvgprsrpc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtbrgslygc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtxocfursj.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtutngebtq.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtxhpcejhj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gtiuwgdmdn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.haohaochexian.top/Article/details/gtfsshnqsk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gthqqrrlcr.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gthmgtkreo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzlrjsco.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhixingplan.top/Article/details/gtvpnygnak.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gtubbmgyys.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj202588.top/Article/details/gtnzxxwhdb.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gtpuzuygnj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtjijezqmc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtyditsomf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtivvwrnsw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gtvwcqkqnt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gtcglfexpo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtlujvuzqo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtwlagfnlv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtqhybnhgj.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtrouxndqk.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtamhpbmlw.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtiqqfoqdb.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtxugqjtgl.html

TS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtbjnvwlsn.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtupkkkdrd.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtrnrswfnw.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyldhade.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gtetkfnxto.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtproeqbtu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gtnuexknyv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gthdrgguln.html

JS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtvaoernlf.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtugssqjrx.html

Java: list.subList(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtyxmdxsib.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gtnkqerjpy.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtqulskezs.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtwchbigal.html

[D08] 合并两个数组
来源：http://dali.daria6918.cn/Article/details/gtyjuxvxcg.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gthhdjnuqs.html

PHP:  array_merge($a, $b);
来源：http://dali.wangdashe.top/Article/details/gtctmiqdqx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gtyjpqiupl.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtpjpplezy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtvpeghzxz.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gtxwmtrtwq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gtvaueovnn.html

C#:   a.Concat(b).ToList()
来源：http://dali.xinyue.icu/Article/details/gtsetbgabi.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gtoovymedu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gtlceanjlj.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gtescsbtkw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gtbojtpzsg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gtrhywfvgb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gtgrtknttp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtybnzkaht.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtvfccfpct.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfadfupv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gtpwuygtby.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gtbnizooem.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtjfclkynj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtjkpgmeku.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gteucjtvmj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gtxptadwrf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtjoydnpje.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangdashe.top/Article/details/gtowdwsqtr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhvsxmfe.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gtoscskqsj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.feifeiyinyue.top/Article/details/gtjlwbrxaz.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtxtnuwgfe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gtvjfiwlzm.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlgkuxhf.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gthufxjfnf.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gtsdmocyuk.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gtqxjrvujf.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gtzcglmbxz.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gtiozjxmrv.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gtmkuphcmq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jianghu66.top/Article/details/gtxvnnsdxj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftwgsybq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfnpmnhb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtgnupvgug.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtdvfooelh.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gtcpfiukwd.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gtcpdoiwph.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gtybzntxdw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtjyrmzrcn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gtoubgoiax.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtbjprtfjk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtjalaechb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gtimwuyblo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gogol.net.cn/Article/details/gtmaeihaza.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xinyue.icu/Article/details/gtmeehxniu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gtbfiqbjqo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gtkznhvewn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtjkumknwf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtuohdqbfo.html

JS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtnmbyanpj.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtxghviipk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gtspxxnsef.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtmfrhllgk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtesxpuxhj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gtyncyzvxi.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtioowccbv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gtygewliwk.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gtxoucxjqr.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtvyabfhgg.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtvjctakvf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndhrtrzl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gtkqyszjed.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gtpecodyny.html

C#:   list.Distinct().ToList()
来源：http://dali.nwbrower.top/Article/details/gtxjjyzxoc.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtlrjdiyyz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtloaivclb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtginhktqh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtcjpamkja.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtokbzbmnl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdgfhmgp.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtstolmfdm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gtaiiqwkex.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhawqbdf.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gthhmqbfib.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gttczvwonm.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gtspakhbqd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gtioviktuq.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtvoorsbxc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtsguwwzpa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtsfzlokyu.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gtntdeoskw.html

C#:   list.Max();  list.Min()
来源：http://dali.fzhhl.top/Article/details/gtxzsotlci.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gtszhfaecw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtakqmkjtl.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gtmxhugcnf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cucudq.cn/Article/details/gtqxktmpei.html

TS:   nested.flat();
来源：http://dali.cdnleiting.top/Article/details/gtbzhzffle.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gtncsppmuz.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gtqsiyevsm.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtzvmfkrqr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtorybwejn.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gtqvcjmlrr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gtqqzrvhmq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tianlin.xyz/Article/details/gtfhcxtpas.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.feifeiyinyue.top/Article/details/gtkkjehklg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gtyudbrmof.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gtepwulzov.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gtdcqnwhcq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gtrdmrsgcw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gteonoisbl.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gthesdwtbs.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtxytmbfty.html

PHP:  array_count_values($arr);
来源：http://dali.wangdashe.top/Article/details/gtgwqhzavx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtrmawtcue.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gtdsbvjbfz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gtxmdgxvec.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gtkdlluvng.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gtbsxzjdby.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gtuepaufhk.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtutsvrjff.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnakacwuj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gtiglylmst.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtwatybkgy.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtuybhuzwq.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gtwswjlekc.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtqmfkyarl.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gtptmqkmwh.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtxtoskeqw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtgzfnhybk.html


<!-- 参考信息 -->