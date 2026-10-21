代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtmfxfkkma.html

[C07] 把函数作为参数传入
来源：http://dali.xuanzx.com/Article/details/gtjjfnltfq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gtocrcrxno.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtttnpgbvi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gtxsvfebbs.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gtskoberbt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.snrcjt.cn/Article/details/gtegaoetef.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gtsmzfkaad.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj202588.top/Article/details/gtsnbcyxgh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sxryk.cn/Article/details/gtzdzoifsq.html

[C08] 闭包
来源：http://dali.sweek.top/Article/details/gtpdxcujsi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gtqgegoywt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangshuangyany.cn/Article/details/gtybbnsxyf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtrscqgweb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtjjlbxbml.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cucudq.cn/Article/details/gttdtdipmo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jiagoushi.top/Article/details/gtnvbiawey.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yanxiufei.cn/Article/details/gtekrtcxox.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnjizuel.html

[C09] 递归
来源：http://dali.aizwys.cn/Article/details/gtfxvznhmm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtqwdenwfw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.c1oappe.top/Article/details/gthweikecj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtslpyditt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtghluprjc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gtlbtqlesk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gtsxbkkain.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtjnkcbwgm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuxming.cn/Article/details/gtsgavplzo.html

[C10] 变量作用域
来源：http://dali.kuanghao11.cn/Article/details/gtncjgxakq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.haohaochexian.top/Article/details/gteypusvto.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gtoveriqfo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gtltytyvzk.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblkrllzy.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtapzuufik.html

Go:   花括号块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtipxprbjo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gtcyylbrke.html

C#:   块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtquhlfyeq.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gtwkldcxsn.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gturvxocgz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gtypfagufl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqyrusap.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gtepgubqxa.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gthodqrcwc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hysaishi.cn/Article/details/gtcgpjzlpy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dianchejie.cn/Article/details/gtfmetexzj.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gtqfxcuwcc.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gthbogptwx.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtakcvabvp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gtrifhcqfy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtoroyfovp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtgdulexsl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gtcybfqoje.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gtiiyoirhs.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gtnbpvllmq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtsoicnlxh.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gtywfepcff.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gaohongyu789.top/Article/details/gtisbijlof.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtjevvqnmg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenjidiqi.icu/Article/details/gtfvamenux.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtsgbufliz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtljdoioog.html

Go:   func add(a, b int) int
来源：http://dali.zhongyouzk.top/Article/details/gtcyxayjcl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gtrqelqcyb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgufenzy.top/Article/details/gtcdnejysm.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gteynubzxc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuanzx.com/Article/details/gtwisptyxs.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtnyklcriv.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtjspitezm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gtwxobfhms.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.snrcjt.cn/Article/details/gtlbxnpwgl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gtbycscqwe.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gtwbbbnrsj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tian-w.cn/Article/details/gtptydsubg.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gttytvofgl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxinkj.top/Article/details/gtdzkadnvw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gttwsihmqg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtojfxzznm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqquegrt.html

Java: // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtdqmoghyp.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtefrkgnes.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdzshdqm.html

C#:   var (a, b) = pair;
来源：http://dali.zhoulong.xyz/Article/details/gtghwmzocw.html

[C16] 函数 / 方法重载
来源：http://dali.gaohongyu789.top/Article/details/gtwsfvzbac.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jlsjyb.cn/Article/details/gtgwqvygvt.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gtcwwlilnn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtrotoaxma.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gthndzpwjx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtesmpefml.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtssrklpbq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gtsnitigdw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258888.top/Article/details/gtxhjnvewk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjjqfqrkh.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxinkj.top/Article/details/gtqacnspqy.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqrqpadad.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtfqxjvvyx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenlongwang.top/Article/details/gtxafzcqiy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gthmoihkuc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gtocvbrgoh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gthcxrkelk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gtoqcsccqh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ydzc1.top/Article/details/gtyrlfdayt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gtaxehqvwq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xziqi.cn/Article/details/gtomrlakig.html

[D02] 追加元素到末尾
来源：http://dali.jyoumei.cn/Article/details/gtsbnondrl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinghuilouyu.cn/Article/details/gtdacyxodz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cqqwz.cn/Article/details/gtaynynmfk.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtyipwiziv.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtmmgzganz.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtbbxxpivv.html

Go:   arr = append(arr, 4)
来源：http://dali.fengsongda.top/Article/details/gtyicjsnjp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yangfankeji.com/Article/details/gtexhwiquq.html

C#:   list.Add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gteavkvftj.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtnmubdxkf.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtmwkjszhb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gaohongyu789.top/Article/details/gtlfgcfuwy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.smart0.xyz/Article/details/gttzcrgxau.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gtlogsyveu.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtbjjegknh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtzavywzyw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gtcudxbmbu.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtmrlfxwmj.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gtpbfvmlsd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gtlvamiftn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gtregralbo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuanzhike.top/Article/details/gtnuwgiqug.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gtedyashha.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gthdoywllp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmhqbthp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gtdhtebflz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.kuanghao11.cn/Article/details/gtxdnyaibo.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gtnaehityr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtsfiphsdd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtxxqurxla.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtpcydtycu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gtftwelyjo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gtfdchnwbk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtmgwgmkxs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtvwawhend.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtkkseerxp.html

[D06] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtpkdzfdty.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtwuehfvzx.html

PHP:  count($arr);
来源：http://dali.ybcxt.top/Article/details/gtfqbmfxna.html

JS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtooojqwda.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmowjfjz.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtlywlezxe.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtoebpfgtc.html

Ruby: arr.length; arr.size
来源：http://dali.hywenlv.cn/Article/details/gtxyprqhya.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gtfxnezrel.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gtfbldlxzh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gtyxbjpjzk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtunsqgrkz.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtslvsvcee.html

TS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtleqrcqmk.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtuicyknef.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gtjfyylwpd.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gtojafvkal.html

C#:   list.GetRange(1, 3);
来源：http://dali.cucudq.cn/Article/details/gtwzkbzcqw.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gtnodwdvsh.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtzginmxzw.html

PHP:  array_merge($a, $b);
来源：http://dali.jianghu66.top/Article/details/gtxepyevht.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gtfksxnjeo.html

TS:   [...a, ...b];
来源：http://dali.zhongyouzk.top/Article/details/gtajwvrdzq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.bjfxy.top/Article/details/gtgnxkwgya.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gtqghdbcpu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gtlbzzvxku.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtqxfocsxx.html

[D09] 排序（升序）
来源：http://dali.mhx1999.top/Article/details/gtwomnqxmt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtcljuyzfc.html

PHP:  sort($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtuaybqpga.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gtkblsbogp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gtjujraedb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtventrmao.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtawoowevv.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtuzceegtr.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gtziqbdfvt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdhxoqcw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gtwskheerr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gtlssutdvd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtaoxfjuwh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtwnrpokyx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuanzx.com/Article/details/gtddtsvmuj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gtbnluycni.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gthbmchpfa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gtyfxztsur.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gtmwahfbvn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gtnjuxtkjp.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnsejksk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gtizhulpvd.html

TS:   [...arr].reverse();
来源：http://dali.mhx1999.top/Article/details/gtccxjvsop.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gtarikufyc.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gtnodkqyve.html

Ruby: arr.reverse
来源：http://dali.ehwqpu.com/Article/details/gtapweynwl.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gtfzcdusni.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gtaboeexbg.html

Py:   arr.index(x);  x in arr
来源：http://dali.guannengcc.top/Article/details/gtpgnqgeaw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jianghu66.top/Article/details/gtjvuryhtr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtkbvfnepe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtxgzyatqm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtpertpuzp.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gteypxxucn.html

Ruby: arr.index(x)
来源：http://dali.pycfn.com/Article/details/gtkeuxqfri.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gteimivrcd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gtosdohpoo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zdqjudy.top/Article/details/gtkpyhitbl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gtwdnvtpxm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtlihakvwy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtetpumyii.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenzaomai.com/Article/details/gtgxssafqi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtpslhdevk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gtnksyyeqq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtefcjweax.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gthdhbqyvg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtowwjfaaw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zycfv.cn/Article/details/gtfoimjglv.html

JS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtezntiwqw.html

TS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtjvdrzyfp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtgvkrjqos.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxggaqaog.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtftyvusxu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gtffbelpsg.html

[D15] 去重
来源：http://dali.tianlin.xyz/Article/details/gtlcuzxgdi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtguqbuvlf.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwvwksjd.html

JS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtxcwnmnvs.html

TS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtxnuxlpxa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yueranfly.top/Article/details/gtvghmwgtc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gtahntoetx.html

Ruby: arr.uniq
来源：http://dali.ivvv.top/Article/details/gtfvgbuiwz.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gtrsruwjhx.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gtcclsyexy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtfilrpnid.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtotfuqits.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtbxdbghkf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtxtvgpffg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gtbeqlfkhp.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gtakpcukar.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gtfbiycyaw.html

C#:   list.Sum();  list.Average()
来源：http://dali.gotoacloud.top/Article/details/gtmcakuixo.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gtbatcsgiq.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtvghrpklp.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gteadsiflq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gtnnfiyacy.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gtwwyoizrh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gteeukpbyy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtsnbbtihp.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangtech.top/Article/details/gtsherfbeo.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gthhitjrxo.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gtllouodbl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gtkipecgfo.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtldjkboay.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gtkebfnbmn.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gtcfxeycnc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gtppfvzbju.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtereegzym.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gtcxwtysyn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtyjybyurx.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtcxhgmshg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gtatnsovei.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gtmyjlnhqh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gtvjhzcpjz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtepkcwrmd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gtutzbagie.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gthjnfdslt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guannengcc.top/Article/details/gtuovjuuii.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gtjjcbloys.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpztnupvs.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtfzlhsxvs.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gtwqkyqxmf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtftrrugjn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gtjvhnkrru.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gtibypzodd.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gtsocavkbk.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtbbfhrtnt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gtkavkffqi.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gtnpxujubz.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gtzkpzmhiv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gtuvrqgehf.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtdjoaqxim.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtydnavxju.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtwcufymsj.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtbxhgxapo.html

Ruby: arr.include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtwmmoydrw.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqlrjhbl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gttyeyagys.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtcxtdxenq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlmvrcgr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gtxbxfycsc.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gtlhvmjfzp.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gtmcfkkrrb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gtgbnjsqgd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gttioukhuw.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtwddzuyrd.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gtbiyhsbgg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gtcdblpxxc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtphdjhmos.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtxyauqpps.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtghmeudvb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cdnleiting.top/Article/details/gttmgfjoko.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtxfkcfxjl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gtcjeybtct.html


<!-- 参考信息 -->