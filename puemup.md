代发 wailian999

Py:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gt2xvyudofr.html

PHP:  return [$a, $b];
来源：http://dali.sufxvd.cn/Article/details/gt2opsfadlu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gt2qzizkyjj.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhtxpufj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.havefunace.top/Article/details/gt2shsggqyz.html

Go:   return a, b
来源：http://dali.bjfxy.top/Article/details/gt2sevwtypr.html

Ruby: return a, b
来源：http://dali.jinqigufen.top/Article/details/gt2odtqybcg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cqqwz.cn/Article/details/gt2tjkoozoz.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gt2wbdwlude.html

Py:   square = lambda x: x * x
来源：http://dali.dashuyun.cn/Article/details/gt2diktobwh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gt2uwwzorvg.html

JS:   const square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2uljdsdxz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gt2zydsqtnm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnqzz.top/Article/details/gt2jaqcarkh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gt2wvigqosg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gt2wtpdewey.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2sovcmxrl.html

[C07] 把函数作为参数传入
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrisjaos.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yvedp.cn/Article/details/gt2pczikzoi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2twpjdbde.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gogol.net.cn/Article/details/gt2xqejkybk.html

TS:   arr.map(String)
来源：http://dali.zhixingplan.top/Article/details/gt2ymhnekdh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2stvlkfhi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aizwys.cn/Article/details/gt2nqadfius.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gt2muaypfjd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gt2vnqxneyj.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gt2qxzngqao.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gt2otmidscu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dianchejie.cn/Article/details/gt2lsxupdxg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gt2lvbriwwp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gt2ovivnixu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yongpay.top/Article/details/gt2szitjqmn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gt2qobnlubd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhongyouzk.top/Article/details/gt2qaaivmjs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2uyoilebc.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gt2mycsgffy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gt2zrcvbjae.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xziqi.cn/Article/details/gt2vchlwjav.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gt2jecsdboz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gt2biurbkaz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gt2jowbpavd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gt2ctaticbm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2rigxfdos.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsnnvzgp.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gt2qpnuwzyx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.birdmap.top/Article/details/gt2kajcvdzh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fengsongda.top/Article/details/gt2hnsnbqdu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2mveheqdx.html

TS:   同 JS
来源：http://dali.yanxiufei.cn/Article/details/gt2ualcwmpz.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gt2vxtxfmir.html

Go:   花括号块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2gazuxnyv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yangfankeji.com/Article/details/gt2vjjwjjcr.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhhhluum.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gt2ncrhgxsy.html

Py:   from module import func
来源：http://dali.yueranfly.top/Article/details/gt2otecpiot.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gt2zuvwzncm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gt2uiwobhyr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gt2ewebeobp.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gt2tyvxnezd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnqzz.top/Article/details/gt2kjkprivp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gt2ytrlufnw.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gt2elbppfqb.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gt2tikhpylw.html

Py:   (lambda: print("run"))()
来源：http://dali.svipenyu.cn/Article/details/gt2hyafiict.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gt2irrsxngm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gt2cfkkcmil.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gt2yhrdkrpu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gt2xcjeqwpv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gt2cschjgly.html

Ruby: -> { puts "run" }.call
来源：http://dali.yueranfly.top/Article/details/gt2cnjrztbd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gt2yheeakuu.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuanzx.com/Article/details/gt2eguezlpy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gt2gwzpptjr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2axcikkxr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qaisvygs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2eeflidro.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2phujkqhk.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gt2lbhsaram.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgufenzy.top/Article/details/gt2ssolpqsj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dianchejie.cn/Article/details/gt2dbwvqefj.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gt2oekfifxk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gt2welthxgz.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gt2akizewvs.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2gwnwwfsr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gt2vhmqpyha.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gt2aawtylmr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gt2jburajgh.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2npnkdykw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hammf.cn/Article/details/gt2dwuvcnsb.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gt2rvlmddji.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gt2xwyxepvb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuxming.cn/Article/details/gt2qparnnyc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gt2lxyncgaw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gt2sdokbtmq.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2akplgnsr.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gt2smqrwqod.html

Ruby: a, b = pair
来源：http://dali.tanke756.top/Article/details/gt2ygbsvmww.html

C#:   var (a, b) = pair;
来源：http://dali.andypj.xyz/Article/details/gt2kdlnscvf.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gt2ayijbdtv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gt2evcpsywf.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gt2lzuefmgj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gt2xthbsdms.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aibaodan.cn/Article/details/gt2qvhtaqrl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gt2adtqvrfq.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugvlnibo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gt2rmlgrrmi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gt2tqfovmaq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2yjwyntfe.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gt2dojatacy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ifvartdt.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gt2qdjopixy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hammf.cn/Article/details/gt2sqysdrfd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gt2tymssrbp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gt2acchehid.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gt2heoaxjtg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cucudq.cn/Article/details/gt2xvngribo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sysykeji.top/Article/details/gt2bppqoncp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gt2pjgmtkvt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gt2hhrnjswg.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gt2btinxdye.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gt2zbhfloxp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gt2fzodehnq.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gt2zljsgfmk.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gt2xehjtgdt.html

Java: list.add(4);
来源：http://dali.aibaodan.cn/Article/details/gt2lfytburw.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gt2lqyxieta.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gt2oxwjahea.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gt2dgwpqslx.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258.top/Article/details/gt2bwjxsflp.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2rdzrdmfg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gt2pstziell.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pixmrkzr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2aqwsgonp.html

Java: list.add(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2kghkkbkp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2jfpsonvo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvqlnyyc.html

C#:   list.Insert(0, 0);
来源：http://dali.sxryk.cn/Article/details/gt2oxxqidxm.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2notsvfyr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gt2jbqwchrg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cashguo.top/Article/details/gt2cvoopric.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.andypj.xyz/Article/details/gt2hkcxeukd.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gt2wnqthcgp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gt2uiggynsv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guannengcc.top/Article/details/gt2prgugxmi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gt2gaxtnkms.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jianghu66.top/Article/details/gt2foizatnm.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gt2hxjxoqsz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gt2vaejjfca.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gt2jchibytm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2tskmilue.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gt2zwcuvyws.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gt2gwhzbzgc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhlxykuk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2fneryptu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gt2sxntytxv.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gt2dahnytck.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2ketnnryq.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2oljecoon.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcohrocs.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsmnritd.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gt2igcgwlso.html

Go:   len(arr)
来源：http://dali.yongpay.top/Article/details/gt2apxmyzmo.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2xvdhjcie.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gt2agspxlsy.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gt2nxzwgqbp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gt2bhxewwdw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gt2awtzymcf.html

JS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gt2rboftdfw.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xoytdmbv.html

Java: list.subList(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkyidcyo.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gt2xrgkxqox.html

Ruby: arr[1, 3]
来源：http://dali.zhoulong.xyz/Article/details/gt2kpjaqbwq.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2jyjccetb.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmgkqrtj.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bzssmpqk.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gt2hzvckhet.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gt2hycjnqxg.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gt2knansjzd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cheryme.top/Article/details/gt2ggdavuny.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eppaxbwf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gt2jvodwuyt.html

C#:   a.Concat(b).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2vznwmoxq.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gt2hldmkvqc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2evtolbvr.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2citdydjl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gt2pliokudy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gt2jadcxpuf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gt2docbjvrr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gt2wavtzhre.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gt2jjuhcayc.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gt2kovbhdff.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gt2xcbwlgsb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yongpay.top/Article/details/gt2manjvmgf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2bcsrbdsq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2onqthftd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gt2nnqfzxxl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gt2zgjdlboc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gt2dealwrfb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gt2caxwejnl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.bjfxy.top/Article/details/gt2qmpsuach.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mccyfkjx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gt2wjnpfvqa.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gt2lquyfokw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gt2eyjknvdt.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhyfehhn.html

Java: Collections.reverse(list);
来源：http://dali.bjfxy.top/Article/details/gt2gamkvotl.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gt2hoztpqdy.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gt2wqexwyee.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gt2mxcdsseb.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gt2jbhvizvy.html

Py:   arr.index(x);  x in arr
来源：http://dali.daxiang520.top/Article/details/gt2knqgnuaq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ysovinvn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2zvztduwu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ganxwkne.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gt2fhfgznwj.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2yiyyizji.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlejouxn.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gt2jiuaeslq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gt2swtcjxyb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2svqzvosn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnqzz.top/Article/details/gt2quhuyqmr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsrrynpp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2xurzlbdd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2mzawzpth.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gt2thonjydy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.svipenyu.cn/Article/details/gt2abzbfmea.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmeqfcjj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2livoyede.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2cjujqllo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gt2oeqggmeb.html

JS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gt2ulvugjai.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmbctpeh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gt2sqjnktdk.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gt2juuhwepd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2swbnclbc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2jisvtvuj.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gt2psfuelll.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrcswdym.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2buidpgky.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2vsyfokil.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2levtpzws.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gt2tlnutqxk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcrkcwyr.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gt2ybxxkdfa.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2sujvvgis.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gt2gbiswnyi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2baivzplp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kwhyylbk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gt2qvejrwwt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2vvcfclrd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gt2llinwwzk.html

Go:   // 手写循环累加
来源：http://dali.cdnleiting.top/Article/details/gt2rxfuyjly.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shuidangran.top/Article/details/gt2oyvywjlu.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gt2dowgpkzo.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gt2qyatxgih.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2xwgsbgwz.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2yrfdbmwr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gt2vrxftibz.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ponzeeto.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gt2svepscri.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2zbdewxwq.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gt2ygfarxja.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2mgyzarvx.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gt2kxwxsjmn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gt2xsfcrhdq.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gt2wzkqozcp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gt2sowzmryh.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gt2kozihodm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2ckoxlmfb.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gt2oljitokn.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gt2kxswfrqs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2dginzbhw.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gt2nrstjrym.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjesefey.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sysykeji.top/Article/details/gt2jxdgrixl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gt2wibpvdcz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzjkwdnz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxepovh.html

Go:   // 手写 map[string][]T
来源：http://dali.daxiang520.top/Article/details/gt2daajvpun.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gt2oecyuyzk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gt2sklalgfi.html

[D20] 统计每个元素出现次数
来源：http://dali.ivvv.top/Article/details/gt2gtndvhnk.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtltuirk.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gt2swlrhjfr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gt2yakazrco.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gt2ktzjavib.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gt2znjslxga.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gt2zhqtwtin.html

Ruby: arr.tally
来源：http://dali.gzhubu.top/Article/details/gt2unilfiya.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2meeigudy.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oekjgvqf.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gt2mspsktnv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gt2grizgbui.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggpqxtgu.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2ygydcwcq.html

Java: list.contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2ytoyilrd.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2bxlbfhit.html

Ruby: arr.include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2dvwyzmfw.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2kuxrslbk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gt2jqzrxmya.html


<!-- 参考信息 -->