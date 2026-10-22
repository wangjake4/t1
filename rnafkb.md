代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258888.top/Article/details/gt2zpnbdxcs.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gt2ogqmztvz.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2shmlfoxh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfdtsgxc.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gt2fzmizsha.html

Py:   square = lambda x: x * x
来源：http://dali.xziqi.cn/Article/details/gt2apoepfxu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gt2kcfwqnvv.html

JS:   const square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gt2bdxcifud.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2izryuies.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2astpzmpj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gt2npsywkcb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yonumen.top/Article/details/gt2qnlqgxoy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2mzkvrskt.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcyjzmxu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sysykeji.top/Article/details/gt2dabpljvp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2mnuircaq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gt2mkkyobdz.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhxdtann.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfmmcfbx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sufxvd.cn/Article/details/gt2qzkklymf.html

Ruby: arr.map(&:upcase)
来源：http://dali.sufxvd.cn/Article/details/gt2cwsainxn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gt2sxpabfdc.html

[C08] 闭包
来源：http://dali.jlsjyb.cn/Article/details/gt2btajqelg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zycfv.cn/Article/details/gt2hykblmah.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cqqwz.cn/Article/details/gt2jjyeoisj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2gqwvikkx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2qapgcsxj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zdqjudy.top/Article/details/gt2ovunysix.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jyoumei.cn/Article/details/gt2izfvycgm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gt2rvywkevf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gt2smhdneon.html

[C09] 递归
来源：http://dali.xuanzx.com/Article/details/gt2gupfisuv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gt2zkvhijib.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gt2yayhlraj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njaqqhyl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gt2lxwypwrj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvjqohpt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gaohongyu789.top/Article/details/gt2xcheaspw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gt2rnkbhtpf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2aazhcext.html

[C10] 变量作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2bpculhpp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gt2ajfkevrs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gt2utffztfx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yvedp.cn/Article/details/gt2wpffrmmr.html

TS:   同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2ibefldjw.html

Java: 方法内为块级作用域
来源：http://dali.cashguo.top/Article/details/gt2gyaiosye.html

Go:   花括号块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2vrowdnnz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sysykeji.top/Article/details/gt2weocpgtm.html

C#:   块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpkdcdhm.html

[C11] 模块导入与导出
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbroehzs.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gt2safwubft.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjwkwnir.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gt2peawflmz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gt2vdgmqhxy.html

Java: import java.util.List;
来源：http://dali.sysykeji.top/Article/details/gt2kwzwepck.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gt2rojvjmxn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.9152youxi.cn/Article/details/gt2ynyypfjx.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gt2ctnidaab.html

[C12] 立即执行函数 IIFE
来源：http://dali.gotoacloud.top/Article/details/gt2iktoinod.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtxjitmd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jyoumei.cn/Article/details/gt2jopyubfv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gt2mhihjrxe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2ytqdtjrt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangshuangyany.cn/Article/details/gt2knrkphmd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gt2krvtoqby.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gt2uxkuykeo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gt2kkdntfoh.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gt2xonykrmr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhshuyfg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gt2lahmnzdc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gt2lkihyjux.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2fxuewuge.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2jdeodqwe.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gt2vowyrqnx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuanzx.com/Article/details/gt2rtkcmbcg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gt2lthlwipo.html

[C14] 泛型函数
来源：http://dali.yueranfly.top/Article/details/gt2zrvejwkz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gt2yqapgvfs.html

PHP:  // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2xflrpcva.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gt2khadpkgi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gt2skfizukm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gt2yrlptmyi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.haohaochexian.top/Article/details/gt2ovuhjkbo.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2ufphssrp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gt2hyzlxahr.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gt2ymboheno.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbiuwmpr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gt2jyapjbsu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gt2ddxxdkst.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shuidangran.top/Article/details/gt2lbbxsnnw.html

Java: // 无解构
来源：http://dali.zycfv.cn/Article/details/gt2cjhnwfrx.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gt2kslgldwt.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gt2ubhwythy.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gt2smjkpeur.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gt2gzrylivx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stllrujo.html

PHP:  // 无重载
来源：http://dali.gaohongyu789.top/Article/details/gt2ohjifwru.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gt2eekzrvtl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gt2ewzhcbdp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gt2yptskpvy.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gt2bianlevd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gt2voxdfwxd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gt2amjfjgqy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2bubtjzeg.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigufen.top/Article/details/gt2oplbbvly.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ruawqaqk.html

[D01] 创建数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gt2lamfinav.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gt2botoyzao.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gt2bhlmhazu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gt2fsvmrhpi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gt2rhwyougi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgfzy.top/Article/details/gt2gmdxkvje.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gt2dwugqvfo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gt2bdbybfys.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gt2csrjcmeb.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gt2lhwmeest.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aizwys.cn/Article/details/gt2thqeazwb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2xkptzmot.html

JS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gt2zuenblwb.html

TS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2duzkspkz.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gt2sffaklot.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2jakssagm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gt2kkplyygd.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwmfbsmq.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2qczhgywc.html

Py:   arr.insert(0, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2qahudhwd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gt2oyxfqsxn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhoulong.xyz/Article/details/gt2dppopwae.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2wjpfkiqf.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjqketym.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gt2xrwliplc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsgtketf.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2njifirqb.html

[D04] 删除元素
来源：http://dali.yonumen.top/Article/details/gt2itofzcrb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ydzc1.top/Article/details/gt2xzixtnns.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gt2gufbducc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gt2cdqbnmag.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gt2kastlguv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qnsbvnkb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvnrlwfa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daria6918.cn/Article/details/gt2wzpcoszx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2falondfi.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gt2yymzhwiz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2noedqhbv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gt2efbrfngy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2yaqdhhas.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxjgfqqo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gt2ojcrsgor.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gt2qwoivpat.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gt2jysyxjru.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2amceljzw.html

[D06] 数组长度
来源：http://dali.andypj.xyz/Article/details/gt2rxsisxkk.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2sxxtvoqs.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2oxkrxvuv.html

JS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzivhfov.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkyxnerj.html

Java: list.size();
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzfvifgp.html

Go:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2urnwkuhy.html

Ruby: arr.length; arr.size
来源：http://dali.hammf.cn/Article/details/gt2duwannde.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gt2pwjyaiak.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gt2vejiaqnx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gt2xemppkug.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kirggybe.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2cbnudyed.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2fndgzzxq.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umcugbut.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gt2xbikrymv.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdtwwaib.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2lrlncarq.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gt2udzhddra.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gt2atqxmxqb.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gt2dybyvnfx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gt2vzxkjdbe.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gt2jcitiqni.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2ycyucfku.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whawsyef.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gt2lwatzpvq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2nurzveww.html

[D09] 排序（升序）
来源：http://dali.cdnleiting.top/Article/details/gt2wedeojri.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gt2ododsyba.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gt2zfqjzjyw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.0kj1m.cn/Article/details/gt2ejgkefip.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gt2kfxqpqhp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gt2pofqcheu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2itgamjmy.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2jgteuqwn.html

C#:   list.Sort();
来源：http://dali.feifeiyinyue.top/Article/details/gt2yeivpnug.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnqzz.top/Article/details/gt2wjbqhoxb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuanzx.com/Article/details/gt2kfnichzy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2roycslvl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gt2lgvoixkf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gt2ewpwokgx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jianghu66.top/Article/details/gt2qtgvsaym.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gt2cbklutew.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wpdowmuo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejoohfar.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gt2tfhkhhif.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gzhubu.top/Article/details/gt2lyeegimt.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gt2vzklfobj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cdnleiting.top/Article/details/gt2smhcefph.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gt2wppmkzcw.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2byilnpgb.html

Go:   slices.Reverse(arr)
来源：http://dali.havefunace.top/Article/details/gt2owxrczpb.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gt2gxuygztl.html

C#:   list.Reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqqkstag.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gt2mwlltmue.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2fwimjruo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2enexcjnb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2rrcwrusq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gt2szklgeif.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gt2jamtqxgu.html

Go:   slices.Index(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2oampuvms.html

Ruby: arr.index(x)
来源：http://dali.yangfankeji.com/Article/details/gt2hrumqgxq.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gt2upslsgmp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gt2esfkgyja.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gt2mtasjfts.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gt2oscandcj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdtmqhum.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gt2lqgdujnp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2eyxxhcsw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gt2aebxduuj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gt2isfchvgl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gt2eqwplmol.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gt2dabpntgw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhuxhknv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2iflqyzsb.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2zrpyfnwr.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gt2kcnhdnum.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gt2inwcufjs.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gt2qgbzgzyf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2abrvoqyy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2vuggpdmc.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2xwdgqsop.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2rmypqlpu.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wsjzaqjc.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2flmxikcy.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2pbuwtdoz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gt2ynxcgxmg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gt2zgqoizmw.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qnjrttgg.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gt2xqhzvyns.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gt2ofalmlch.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2zbeidmxz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gt2xvvmdalf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gt2exguvjgr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2sbctwsgd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odjiwtsg.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gt2bbqektit.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gt2cbjwloei.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gt2tzuapagy.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gt2deygyzct.html

Py:   max(arr);  min(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2yjprvwqm.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gt2akzwyvqq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.meibo888.top/Article/details/gt2xtriafzc.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gt2ixeehsxj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xziqi.cn/Article/details/gt2jqkmncdo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gt2hcuiuqgy.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gt2xlcrcdrg.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gt2uswryknv.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gt2kyzglsyt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gt2iirzwkwb.html

PHP:  array_merge(...$nested);
来源：http://dali.gaohongyu789.top/Article/details/gt2domollsm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gt2olxbpjcd.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gt2uwgiacti.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ciqeijjz.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gt2dqiqlckp.html

Ruby: nested.flatten
来源：http://dali.yuanzhike.top/Article/details/gt2baofapba.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgtepejr.html

[D19] 按字段分组
来源：http://dali.daxiang520.top/Article/details/gt2yqrrsgsp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gt2enpqrggw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcurwebv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gt2bdyzehly.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gt2enmqrers.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gt2msuuurwq.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gt2icazegnw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gt2dnemikga.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqhaiad.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gt2ieiiargv.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gt2wvucvshl.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gt2mxnuqjmk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gt2eecudfci.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gt2ceoudwlf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gt2ffxwqabm.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2odhuilmu.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gt2lavoiqux.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gt2yfmsuxza.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gt2cepatiun.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gt2ubidfiuv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gt2kmzsqtld.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2fmzngbiy.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2hgllolmu.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2slzzvezo.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2yiqdbstk.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gt2rwbflmoy.html

C#:   list.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2fohunsrb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cqqwz.cn/Article/details/gt2hdzsrbzh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vagxywhz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnqzz.top/Article/details/gt2dclndryj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ojzkgwcb.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwglynve.html


<!-- 参考信息 -->