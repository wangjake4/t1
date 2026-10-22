代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gt2kxcsqnjr.html

Go:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2jvobpejj.html

Ruby: return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2mfzztitk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hfpthk.cn/Article/details/gt2rpxxbvjl.html

[C06] 匿名函数 / lambda
来源：http://dali.jianghu66.top/Article/details/gt2fpqldhov.html

Py:   square = lambda x: x * x
来源：http://dali.zdqjudy.top/Article/details/gt2pcagtwhc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.havefunace.top/Article/details/gt2aogqgbmh.html

JS:   const square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gt2hbrrwwal.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sxryk.cn/Article/details/gt2jzcthzew.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gt2nrlftjkg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gt2ughjpnrw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gt2giondwkp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2hemcnmnc.html

[C07] 把函数作为参数传入
来源：http://dali.meibo888.top/Article/details/gt2vmjwsiyt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gt2jxvfbisw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2xjniqnsr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.havefunace.top/Article/details/gt2ywlwtnec.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gt2wbmxgffm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.havefunace.top/Article/details/gt2utafixtl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gt2lruqjrvf.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dapnwthp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aibaodan.cn/Article/details/gt2xxlnptdq.html

[C08] 闭包
来源：http://dali.nanxuanxn.top/Article/details/gt2fomfwwlw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gt2uxrcwlwk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sufxvd.cn/Article/details/gt2yxnfrstb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2ykyemsio.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2uyuptyxf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gt2iqhkimjc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gt2cxcsivwo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.redwolf501.top/Article/details/gt2zkpnyufq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2waamcpdh.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gt2obnvrext.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gt2jzgnzpsd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yvedp.cn/Article/details/gt2pcvycrwq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gt2xvqwjadb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gt2dfvvgaud.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gt2syeejnrk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fzhhl.top/Article/details/gt2oafvfwgz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gt2ovtxhyhz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gt2phdssbkg.html

[C10] 变量作用域
来源：http://dali.andypj.xyz/Article/details/gt2xdowoiov.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cdnleiting.top/Article/details/gt2isvwxbme.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egopimhv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gt2rfjuxuws.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2fmqdmbjp.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2neejltkj.html

Go:   花括号块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2taqjudtn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmsummln.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2dlszqwsz.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gt2fwrwrwmj.html

Py:   from module import func
来源：http://dali.zhengqikj.top/Article/details/gt2twbvhmag.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gt2qeobnezb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gt2iehwvvgt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gt2tkudmgmx.html

Java: import java.util.List;
来源：http://dali.jqgufenzy.top/Article/details/gt2owmfgpla.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gt2fligcivn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gt2rgtttush.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gt2etupuepm.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gt2rrzvadjt.html

Py:   (lambda: print("run"))()
来源：http://dali.dianchejie.cn/Article/details/gt2iccrztsk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gt2fxnhawrc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gt2zrqfhrlp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gt2olsryeye.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gt2xjbecdgp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gt2yakopjur.html

Ruby: -> { puts "run" }.call
来源：http://dali.hywenlv.cn/Article/details/gt2qbnnubdw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.meibo888.top/Article/details/gt2vmokhrni.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gt2eqxdwvpt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gt2vavriysb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2wbdcgzdq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gt2ydpfhuxt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2hvflognv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2jzolxoph.html

Go:   func add(a, b int) int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fypvsdjz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gt2faewlrvv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gt2nqndfudb.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gt2bsgsfsgo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gt2hbtmfqpv.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2lsiveqdr.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2rawibstc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sysykeji.top/Article/details/gt2xhwldreg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shuidangran.top/Article/details/gt2fofgannk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hysaishi.cn/Article/details/gt2qyhasbiw.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2uuvjnhvf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gt2bhnlppju.html

[C15] 解构 / 展开参数
来源：http://dali.c1oappe.top/Article/details/gt2bykumbch.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gt2jnchehzw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gt2rwxdqdww.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gt2xztaifok.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hfpthk.cn/Article/details/gt2xvguoant.html

Java: // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2afthvkgv.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gt2lvqvyvif.html

Ruby: a, b = pair
来源：http://dali.tanke756.top/Article/details/gt2ykuolxre.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gt2tgpqmrqi.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gt2xitpieau.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gt2hbusjwhj.html

PHP:  // 无重载
来源：http://dali.zhengqikj.top/Article/details/gt2lbaewgev.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gt2jeeeybeh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gt2zlbuqtwl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gt2mwmzsexd.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gt2cogjjtdf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gt2iunutmex.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2evxkqibd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2jnfiumih.html

D. 数组 / 列表 / 集合
来源：http://dali.tianlin.xyz/Article/details/gt2fnjytkzy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2uapaeiql.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyekuzet.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gt2boaahtvu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gt2rtxcqvgw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2oiqrezvq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gzhubu.top/Article/details/gt2yajccxvz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gt2suwktsqq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zdqjudy.top/Article/details/gt2hnizhvsp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gt2bxnxzbap.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gt2kvdzmlsr.html

[D02] 追加元素到末尾
来源：http://dali.bjfxy.top/Article/details/gt2fspysnqi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjcbvfrp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2huqjhwvl.html

JS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gt2hvylrysk.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gt2uipaazdv.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gt2igbomhbs.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gt2kmuiufiy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gt2nqtcafcp.html

C#:   list.Add(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2yzsrnnue.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gt2ihkhchsx.html

Py:   arr.insert(0, 0)
来源：http://dali.guannengcc.top/Article/details/gt2dknkdeqr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gt2uerlmlcn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gt2bqpbyohs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.birdmap.top/Article/details/gt2ufmojqxb.html

Java: list.add(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2etwfvmnl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hywenlv.cn/Article/details/gt2pfpfjzyt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258888.top/Article/details/gt2kndokigk.html

C#:   list.Insert(0, 0);
来源：http://dali.c1oappe.top/Article/details/gt2jkuqycsg.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2vpjorcsv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2ogufpyhp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gt2gdpdqszd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gt2lwlioyya.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gt2cqvbewqb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daria6918.cn/Article/details/gt2uesrugfe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gt2dktlqvvh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gt2fqnsixdo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gt2bagljeel.html

[D05] 访问与修改元素
来源：http://dali.jinqigufen.top/Article/details/gt2hlwkbiya.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2essebcys.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2aowctusx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gt2xpyesntq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gt2wskrxuwy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gt2zrwoxgml.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2nansbxqw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2ewlblith.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2twziqxxf.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2ppxsepfs.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2bbelofel.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gt2lwguwchj.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gt2rydapkqa.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2rnhakokw.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gt2cepykkpq.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2pdsxjmrx.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gt2cgibsnml.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gt2cvaeiuiy.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gt2eqoebcxg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouxomqki.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2umykpojz.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2xqnumtbc.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2npfigchd.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2wjeycmky.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gt2njemfrbx.html

Ruby: arr[1, 3]
来源：http://dali.iojbl.cn/Article/details/gt2cxqbefrg.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gt2mzbwrsik.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2sssrnanx.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gt2mimgritu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhoulong.xyz/Article/details/gt2rrxolchr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gt2toffibks.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gt2kzqtowae.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2hrcmhthd.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gt2pueymhfi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gt2fswilfzj.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2rxqlrajz.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2seuynkty.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gt2xbrcurnl.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2grgovbto.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnqzz.top/Article/details/gt2xgiqhbai.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gt2mwxviajg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gt2ydwtthsq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2nuzcwegm.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwnnxfdf.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gt2zdpibmth.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gt2baxlfaos.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gt2ayauhaad.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gt2bdtkbwun.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gt2uyvpzcqd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gt2bgsrcswx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwqnchot.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgfzy.top/Article/details/gt2buaarxwu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gt2iemexnzu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gt2xszkwdsm.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gt2lmbhhiqc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gt2tieolxhw.html

PHP:  array_reverse($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2rubdjetx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gt2ocuupndk.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gt2fgofyxjj.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gt2hzbusyss.html

Go:   slices.Reverse(arr)
来源：http://dali.shuidangran.top/Article/details/gt2zoldkocc.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2rrvnnief.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gt2swuyqada.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gt2nzcqfvar.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdtsieiq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2afhwyrxg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gt2pvcjihto.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gt2zuwxhoxs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gt2xcovdfod.html

Go:   slices.Index(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2mqgoowjk.html

Ruby: arr.index(x)
来源：http://dali.hammf.cn/Article/details/gt2xlyxnysn.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2weywygas.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gt2hrewbxqf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2jaiaride.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gt2icyhvvic.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gt2tmaebbqo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gt2kkwmwtog.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwxzarqs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgfzy.top/Article/details/gt2ndpsuqry.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iuoirmoa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2emhnwaqx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gt2pffnppnx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.havefunace.top/Article/details/gt2khcrhizy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gt2icszelgi.html

JS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gt2knymtnhr.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gt2zkktbqru.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2gzkqvocj.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2moorqxnl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcxrmubi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivxfueyc.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gt2ggbyuvqg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2puzilkbr.html

PHP:  array_unique($arr);
来源：http://dali.meibo888.top/Article/details/gt2tiyxdhfa.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2wlkfhsft.html

TS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gt2nmptkqln.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnncawgy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gt2hymdsizn.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gt2atlplhrg.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gt2zyojdcpu.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gt2qppttqeb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2gckxldnv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gt2rirfiwoj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2rhasojor.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gt2pfanwxiv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvtkvgrf.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gt2coexgjdg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gt2xomrlpix.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gt2vbejxujp.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gt2jnvilqpn.html

Py:   max(arr);  min(arr)
来源：http://dali.daxiang520.top/Article/details/gt2zryadtub.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gt2czgfgrao.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2tswhddfx.html

TS:   Math.max(...arr);
来源：http://dali.jinqigufen.top/Article/details/gt2cfbbunkn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vamvxwyg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcitfsos.html

Ruby: arr.max;  arr.min
来源：http://dali.shzxlz.cn/Article/details/gt2hpjyriyt.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gt2hsekfdix.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gt2pqxqobpm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzmgaosm.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gt2kclobokj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gaohongyu789.top/Article/details/gt2nycytdug.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gt2iaqffvju.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258888.top/Article/details/gt2jgxqkzpo.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmzyasou.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gt2khposwjv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gt2ufbibsyr.html

[D19] 按字段分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvolgjum.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gt2psxuimnv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pycfn.com/Article/details/gt2ktkkglhq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gt2zunfhkes.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gt2wdyxrlbr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gt2ychdfkjy.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gt2bwifzatx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdsziszr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gt2gjowdutq.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2geemysml.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2opzkpste.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2limehini.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2yfqxsdie.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkcigxc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gt2gbglnhiu.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gt2juhchsxk.html

Ruby: arr.tally
来源：http://dali.tian-w.cn/Article/details/gt2uecnzhup.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgtnarlu.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gt2hwfdolaq.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gt2zijvxcdy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gt2vzavditu.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2tslsewbr.html

TS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2oifhkcgw.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2nlgsuubi.html

Go:   slices.Contains(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2rutpusdm.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2gtwyttdp.html

C#:   list.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2gktvwjdz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cqqwz.cn/Article/details/gt2dakeusid.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.iojbl.cn/Article/details/gt2nujlgspa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.kuanghao11.cn/Article/details/gt2foekazyp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gt2cqazptlb.html

TS:   [...arr];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jsgvvmzb.html


<!-- 参考信息 -->