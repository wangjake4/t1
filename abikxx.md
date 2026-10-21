代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gthuutwqnx.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gtcoigwtfb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hfpthk.cn/Article/details/gtwpztswvd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtiogepmmq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jlsjyb.cn/Article/details/gttljaqibl.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtrvplwmht.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gtdvynfxle.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.iojbl.cn/Article/details/gteuvhdihg.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gtrxtsuyhl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gtywjggymo.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gtedwpitin.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgufenzy.top/Article/details/gtopxjaonz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gtiugufkyk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtsrrkjspp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtytrjhsuq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hfpthk.cn/Article/details/gtzhstibco.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtduxvgtmj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtqccogkxc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtzcqdcqqt.html

[C09] 递归
来源：http://dali.gzhubu.top/Article/details/gtvhtsmmty.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtkamwrhsz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gtedktlxqo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtelmdmqdi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtxgpnwwvo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtaamqucuv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aibaodan.cn/Article/details/gttdllegbl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gturmesqmw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gtvgkqbelq.html

[C10] 变量作用域
来源：http://dali.iojbl.cn/Article/details/gtviycdodw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gtlvtkbdin.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gtvxhjlocd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtzblrtmuk.html

TS:   同 JS
来源：http://dali.aibaodan.cn/Article/details/gtkmcejbti.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gtuxmtvahy.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtpckeoloz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgfzy.top/Article/details/gtfhxxnaeq.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtjyhjchfs.html

[C11] 模块导入与导出
来源：http://dali.havefunace.top/Article/details/gtzgbwcnkl.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gtjrgrsapk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gtglikqcof.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gtpygtyujc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gtjhkghtom.html

Java: import java.util.List;
来源：http://dali.havefunace.top/Article/details/gtdwwdoblf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gtufcxyixa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gtzdjxxqgs.html

C#:   using System.Text;
来源：http://dali.xinyue.icu/Article/details/gtdcscqefu.html

[C12] 立即执行函数 IIFE
来源：http://dali.shzxlz.cn/Article/details/gtfzgpqmoj.html

Py:   (lambda: print("run"))()
来源：http://dali.snrcjt.cn/Article/details/gtjspzmspj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gtelpmeykv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtqgkgpbzt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtnazhpi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gtlergywwz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xylfe.cn/Article/details/gtqolxjwxi.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvjpuqar.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gtbtcbsrwn.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gtiufrxkju.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gtsnmouaaq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmevuskfo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gtzohuvppr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtaboyzzzs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtbecqxigk.html

Go:   func add(a, b int) int
来源：http://dali.zhengqikj.top/Article/details/gtbgkgvqrp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gtbskqmgwj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ybcxt.top/Article/details/gtkhibofyi.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gtgzokgbwo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gtbgxdckib.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtzjmpusgy.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtokljirwa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gtrkuldwgy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gtanmdqvmb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gtaulmskrb.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtnpkrajhg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gttgktlvxb.html

[C15] 解构 / 展开参数
来源：http://dali.guowangkeji.top/Article/details/gtlemjptzm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gtmomrocis.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gtvzztqtjv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuclhnypx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenzaomai.com/Article/details/gtwxndwmai.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gtoimqndng.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gthjbelues.html

Ruby: a, b = pair
来源：http://dali.hongshengwenyu.top/Article/details/gtshctkira.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gtlclmvpep.html

[C16] 函数 / 方法重载
来源：http://dali.cqqwz.cn/Article/details/gtwjoljeru.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxfbvovn.html

PHP:  // 无重载
来源：http://dali.gaohongyu789.top/Article/details/gtmirynqdv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gtozznluhj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gtthlexnmb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gtnjjurlra.html

Go:   // 无重载：用不同函数名
来源：http://dali.aizwys.cn/Article/details/gtjfxqjugz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gtbogpoqwe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gtswnhakvm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrrankmai.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gtoitnfxlt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbyueymnp.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtjozljxfc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pengpengdd.cyou/Article/details/gtlddxfbyt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtwnjzjbun.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxinkj.top/Article/details/gthoeikmhm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gtwlvrsfjd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtgnrzhxsk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gtiocmbmlq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gtuvgmosjv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gttvigylem.html

[D02] 追加元素到末尾
来源：http://dali.shangyingyoupin.top/Article/details/gtyswieafc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gtwumyjxmi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gtpnnqqjnu.html

JS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gthbxmlojl.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtcjbqpoqv.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtxckftvqe.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtaphgaysx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gtfbxvwsue.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gtkhmefxzh.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gtpnslamjv.html

Py:   arr.insert(0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtglrmwllg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxinkj.top/Article/details/gtcaqtxwvs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cucudq.cn/Article/details/gtvgdowxzh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtpsbwdetk.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtguhzhmgs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gteahrgvun.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gtorbcxnzw.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtclxupgsc.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtkzqbazxk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtosiimzvq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dianchejie.cn/Article/details/gtzcfimoov.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtomcpqdtz.html

TS:   arr.splice(0, 1);
来源：http://dali.birdmap.top/Article/details/gtdgedllek.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gtjdlwsyzb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gtvckxvqgb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenzaomai.com/Article/details/gtfepzdndv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gtubehqjey.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtivfyfqoq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gthvvotahp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtgzpprrjm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gttojlyqlj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gtapyzrmpx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppzefmlg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtwmaikalb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvaqnmcxz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtpvcxoqkz.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtcywioyav.html

Py:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtcjoltwpa.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtdazzdsgr.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtfactmvib.html

TS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtpkudrnsb.html

Java: list.size();
来源：http://dali.yuanzhike.top/Article/details/gtpalqmhmh.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtvgqabtfc.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnoqttcv.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gtrobpvywy.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gtjiysqnor.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtstrjuhle.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtlmocgted.html

JS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtaauyuqie.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtkpfflwyf.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtfokcowtf.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gteprbidsy.html

Ruby: arr[1, 3]
来源：http://dali.snrcjt.cn/Article/details/gteefhjqcr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtpwsmefnv.html

[D08] 合并两个数组
来源：http://dali.bjfxy.top/Article/details/gtjnljnrqc.html

Py:   a + b;  a.extend(b)
来源：http://dali.cucudq.cn/Article/details/gtihshithy.html

PHP:  array_merge($a, $b);
来源：http://dali.guannengcc.top/Article/details/gtbbdodivk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gtrxigcnmm.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcehmhvx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtflrvluth.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gtpfixgwjo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tian-w.cn/Article/details/gtxxicmusp.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gthcgbxqwa.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gtvxbvlwlb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtfhufyocq.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gtbpyotvso.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gtdlxtpnpp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gtvznaqibe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gtievbepzo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtygguhrlq.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtkqmjvzdr.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gtxcndktbl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gtekcikvgy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hammf.cn/Article/details/gtegudvdst.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gtwlfpnism.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtsatlqtfb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtfinhwwtp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hfpthk.cn/Article/details/gtvvtgqvgd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtlnpnugmp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtmspiubgb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweyfxcfz.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gtzcvxpqpr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gtryjiebyx.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258888.top/Article/details/gtmckkswyi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gtapmydvbc.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gtahybalna.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gtqhqcxzwy.html

Go:   slices.Reverse(arr)
来源：http://dali.redwolf501.top/Article/details/gtmpgmxeym.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gtiwxadhxq.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtudqeaylj.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gtaqbjvouy.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtiixzzvof.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yonumen.top/Article/details/gtrzsdtfta.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtgegejfey.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtxovjujoj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gtapxxaeyv.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtqaultzxx.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gtcotomaei.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gtmsvcmwze.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gtensdtdrs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtcldcyarl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtxgnrzfep.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttrezfwu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gtjjpkoecx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtrqdaqkya.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gtwxvaacpc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gtmaunbpdm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtgumuoyed.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sweek.top/Article/details/gtuljodygd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gtctrlbbmt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtabyejvfv.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtocsqqiwi.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtqefimbke.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtvxppleuv.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtckptfray.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtcxnyxxwk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fengsongda.top/Article/details/gtbaudlroy.html

[D15] 去重
来源：http://dali.yj20258888.top/Article/details/gtqsnvnzhg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtblevigqn.html

PHP:  array_unique($arr);
来源：http://dali.cashguo.top/Article/details/gtkwfjhozz.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthynkpvll.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtbhxphhwo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ybcxt.top/Article/details/gtafdugxua.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gtgnbcixat.html

Ruby: arr.uniq
来源：http://dali.meibo888.top/Article/details/gtfrgwblny.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtdpdfzqvh.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gtscsfdada.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtrywnxzfb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sxryk.cn/Article/details/gtpnbfsgdf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtoeezrxap.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtibjkltnj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gtlztlmhgd.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gtfcfcagtz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gtxsmbojde.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gtcaalpwnv.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gtdyufehio.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gtaavablum.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gtdgpzggfp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtbnzjkgfr.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtilvrijdo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtetzbhvta.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sxryk.cn/Article/details/gtyldhzrwm.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gtivimcpdl.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtlxdsunho.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gtvviqucuw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gthhavtiow.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gtyhnivwog.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gtbhmbmjng.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gtwvbwkzya.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtaictdiol.html

Go:   // 手写双层循环
来源：http://dali.yuanzhike.top/Article/details/gttdpubuxm.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gttmknlpjh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gttzwocquo.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gtzicklmyv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gtwcuyxapk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtzsyiecbb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gtkhiormxo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gtcnrjlhbu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gtuayzsyem.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gtybfbkfny.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gtwqivumyo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xinyue.icu/Article/details/gtkbkjvwkc.html

[D20] 统计每个元素出现次数
来源：http://dali.dashuyun.cn/Article/details/gtyrmzypbr.html

Py:   Counter(arr)
来源：http://dali.gogol.net.cn/Article/details/gtuzgrngwv.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtrxxhyhzt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtknmzanjl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtbngrzlxx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gtyyjlvgxr.html

Go:   // 手写 map[T]int
来源：http://dali.zhixingplan.top/Article/details/gtirncdtlh.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gtcfflqntk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zycfv.cn/Article/details/gtbhqhluuk.html

[D21] 判断是否包含某元素
来源：http://dali.jianghu66.top/Article/details/gtnymclmnh.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtqzkxmpur.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gtuxwfnbfc.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtesndxiss.html

TS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtudqjkiis.html

Java: list.contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtkzxczgao.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtdyierhij.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gthtyggnup.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtquomkb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xylfe.cn/Article/details/gtfpqdillj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtnpeideyn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gtchmmozqp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtfhknhicv.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gthjieojcy.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gtzhvoqjfj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258.top/Article/details/gtbmkvgpie.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gtxbvapvqc.html

C#:   new List<int>(list);
来源：http://dali.ybcxt.top/Article/details/gticjtqtsk.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gttwmzkteg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gtakptbxqk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuanzhike.top/Article/details/gtemmxrtkc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtkksqxznf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtqcbrhboo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.mhx1999.top/Article/details/gtjkedskzq.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gtvazuubfj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gtvvmicfnh.html


<!-- 参考信息 -->