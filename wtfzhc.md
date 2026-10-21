代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpayzvtow.html

[C07] 把函数作为参数传入
来源：http://dali.zhoulong.xyz/Article/details/gtxxqnocsf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cashguo.top/Article/details/gttkrfetye.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gtbajunwub.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tian-w.cn/Article/details/gtfonpsqis.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gtphyfpkih.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gtktrdspeu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gtiejbjwju.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhfbauso.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dashuyun.cn/Article/details/gtbvmbvbix.html

[C08] 闭包
来源：http://dali.nanxinkj.top/Article/details/gtubexsuzr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhongyouzk.top/Article/details/gtsiyyvmcj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gtmosgzotb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtdwadzoub.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtrphscvmq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangshuangyany.cn/Article/details/gtcmzvleba.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.0kj1m.cn/Article/details/gtncrgwldz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hongshengwenyu.top/Article/details/gtqnzeyqtx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gtrfwllpxz.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbxienbr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtwfelxskj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkdrxpgxw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtttqsykun.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtgqdoqmdq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gtxkctlgfk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj202588.top/Article/details/gtcqtyesom.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtipzapzrf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gtvexttwlb.html

[C10] 变量作用域
来源：http://dali.iojbl.cn/Article/details/gtfxdrioqi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sufxvd.cn/Article/details/gtacyewcub.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hywenlv.cn/Article/details/gtktjfoool.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuanzx.com/Article/details/gtygiqokvd.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gtdxgqkvyu.html

Java: 方法内为块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtiztnvytz.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtmtkrbslp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.316326.xyz/Article/details/gtgnbjjnsd.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gtzhlegekg.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gtkkrzljle.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlmkmtye.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuetiantiany.cn/Article/details/gtylpwwgjp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gtjnyzomoi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gtxzcntksc.html

Java: import java.util.List;
来源：http://dali.hammf.cn/Article/details/gtmfqrgjhj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gtiwpfevhw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gtqsezoalm.html

C#:   using System.Text;
来源：http://dali.redwolf501.top/Article/details/gtztheycvv.html

[C12] 立即执行函数 IIFE
来源：http://dali.hongshengwenyu.top/Article/details/gtmazegjer.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gtwgrdcwgm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gtdpctfptj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gthvvucwuq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtbilfttxf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gtblceejwg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gtsdaaaaak.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gttrvsutss.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gtgsfhcyio.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtormqhwmg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gtmhrvzimi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtvycauhtj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gtvwnyldmp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuuxfpsbu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtobyglmmr.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gtzdqtmtgu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.quarkkingdee.top/Article/details/gtyfwjvpie.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gtlkfkbukb.html

[C14] 泛型函数
来源：http://dali.zhengqikj.top/Article/details/gtqwnvzcng.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gtbzpvidov.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtupmaeopj.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gtvfbwhwta.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.havefunace.top/Article/details/gtnlrnxuhv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gtzsodinmr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gtrzkpqviv.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gtpinsigkv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gtlowyyeiw.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gtcieprqdx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gtcotrdfzq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gtagikuvug.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtdnkahciy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gthbmneeus.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtwwkhewct.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gtehccrdmv.html

Ruby: a, b = pair
来源：http://dali.dianchejie.cn/Article/details/gtzdidhthl.html

C#:   var (a, b) = pair;
来源：http://dali.jqgufenzy.top/Article/details/gtsovziqxy.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gtfnqldrbc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gtxvbpshre.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtlgoqxosj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gthesykcvw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhoulong.xyz/Article/details/gtgixgjpxg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdiczztnf.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gtihhhvlld.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gtsbpseqlb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gtomanhcwc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdymfahed.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgfzy.top/Article/details/gtzttsxckl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwxsbbuzm.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtugfmjngp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gtesokbaib.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtnuraywfv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtrlmfwkmj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigufen.top/Article/details/gtasdbxoww.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj202588.top/Article/details/gtgekshpiq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ybcxt.top/Article/details/gtvojmfavo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtwnowqlmy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtzrlbyufq.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gtggiucllc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gthpyxnwdu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gtmkemjixy.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gttemaaenm.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gthaszxoiu.html

Java: list.add(4);
来源：http://dali.xziqi.cn/Article/details/gtgjeucnez.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gtznnmdqtf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gtzkkhhoaf.html

C#:   list.Add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpoudtxid.html

[D03] 在指定位置插入元素
来源：http://dali.havefunace.top/Article/details/gtxrmwphgs.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtmrgfgevu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.snrcjt.cn/Article/details/gtsdihknxo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhengqikj.top/Article/details/gtlsmufstc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gtircbmprw.html

Java: list.add(0, 0);
来源：http://dali.cashguo.top/Article/details/gtqdogtvcd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gtdiqqixiw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gtemvwvvti.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gthrayfcfj.html

[D04] 删除元素
来源：http://dali.fengsongda.top/Article/details/gtukmwdqgm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gtfmibfosp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gzhubu.top/Article/details/gtmapemtmk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gtrgbeyzuy.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkwzojei.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotaxbvzq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shangyingyoupin.top/Article/details/gtmffomwqq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gtdcksqmsc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gtyzgpipgh.html

[D05] 访问与修改元素
来源：http://dali.pycfn.com/Article/details/gtozbhuper.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtqtmivmgt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtippewcic.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtbqbmdazw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gtrmgcrate.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gtlznquglh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtzadwavlw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtyeehbneo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtyvrrmbvy.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtpudzonts.html

Py:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtcnytehqi.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtxmbdhqzr.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gtefmafrif.html

TS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtqjwikmjd.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gtpeikmnyh.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtuxdktcwr.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtpueuftbv.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gthrxmxxtj.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gtvdwlbkjm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gtxjyluqie.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gtqnvtdurb.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtkjnyfive.html

TS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtejdhgnhs.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtjqggwwqu.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gtdhsssguf.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gtbcyajmxb.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtieadgivc.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gtzsuixzsl.html

Py:   a + b;  a.extend(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtzuoemdug.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gtzqibxqnx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhiwuduotai.top/Article/details/gtuaqxjmhl.html

TS:   [...a, ...b];
来源：http://dali.sysykeji.top/Article/details/gttfybzdkw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtrsgjbsfi.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gtlcfvpils.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhongyouzk.top/Article/details/gtcjoqxjdn.html

C#:   a.Concat(b).ToList()
来源：http://dali.xinyue.icu/Article/details/gtmmvjoeob.html

[D09] 排序（升序）
来源：http://dali.ydzc1.top/Article/details/gtdeijygik.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtfgrawdbz.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gtwhgbtmxd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gtxgcmxmwe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gtzmwocuij.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gtbttivlgf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtwamxixmw.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtfoicnzes.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gtsgblmsgt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gtmgclrdmd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gtxorbxbkn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gtnlmblxem.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtduxktemr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtvctsgvbh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtaebofugx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gtyarzpobw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ehwqpu.com/Article/details/gtaozgnsuw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gteovtlzew.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gtlvelaekn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gtlklqcjdy.html

PHP:  array_reverse($arr);
来源：http://dali.ehwqpu.com/Article/details/gtdnbajlyn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.redwolf501.top/Article/details/gtqfanjget.html

TS:   [...arr].reverse();
来源：http://dali.zhixingplan.top/Article/details/gtkxqxgqez.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtnpcqtrjr.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtnfoqtwzv.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gtxrlxiifu.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gtbztcntbu.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gtrhvpvmok.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gturjmheqg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gtwzdwonlk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtxjhqzela.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtjimbafqn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sweek.top/Article/details/gtgcwaispy.html

Go:   slices.Index(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtpmnjarfg.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gtfkcbhshx.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gttecbdkgn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gtycbdzova.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hysaishi.cn/Article/details/gtiwkrdchz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gttwfpapqp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtlkrvkkck.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtoypytfvz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtoazdtyod.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gtxkyjadqu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gtbsuclikw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtyllsnhtv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gtysafysvl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xinyue.icu/Article/details/gtfufcuixz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gthstnhenm.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtfuszzxbs.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtbbskoeob.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gttgihdsqo.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtprvqdyjr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtaestslke.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhbuwnuq.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtrjqqcxgj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtbiowjvme.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gtbpgbgjur.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtlepjggrq.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtjvssbqex.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gtcnufvoft.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gtfdurkrez.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gtqdrupoxo.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtvjfxhrka.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gtobonvhgu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gtgxxxhccx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gtajnamalt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gttdctlhra.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gthwlrkjau.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jyoumei.cn/Article/details/gtxilbhwrd.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gthphiofcg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gtlhulofpj.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj202588.top/Article/details/gtajjyczaf.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gtpwmgprsj.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtontfaxbd.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtdhdxynmn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtxwdbqtrr.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gtttpbgprp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtwbbrnwwk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gtuwokyzql.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gteoizxuco.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gtgaavdviq.html

[D18] 扁平化嵌套数组
来源：http://dali.quarkkingdee.top/Article/details/gtdcjkkawl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gtaznfcfyl.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gtpscbfiem.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jlsjyb.cn/Article/details/gtdsdpeouy.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gtporhlhlu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gtkeygebou.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gtkwxuzcmg.html

Ruby: nested.flatten
来源：http://dali.havefunace.top/Article/details/gtcafeorhs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtpmhjdwgy.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gtaceayzhn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcsndhcc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtqfeqmvhc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gtbjchifas.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtwryepofq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gtuqbhadee.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gttadfwoxz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gtxxlvbmvz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gtgxkargvh.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmkwghyw.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsattgvsc.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gtuxqncxnh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtkjymtvrq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gtxobnbeib.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cucudq.cn/Article/details/gtjxgphsxm.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gtkslaxnom.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gtjryshgnb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gtpdzigbwu.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gtxpevjpvm.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtevjqbhqo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gtnwqunatp.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtwnuqhdmj.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtmlpjelpz.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtriojcobk.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtmnfqkvqq.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gtfbscdhdd.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtzwvqagcx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gtuhmlwsio.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gthookhigq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gtfuskmlyh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gtotajcamt.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gtacruzziv.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gtsgamjjmv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gtjpjafyxq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gtzjogobcj.html

C#:   new List<int>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzlubwpc.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gtxcdtrtxu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gtlhrxpjay.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtibijgyyi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtgayqwqlw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtyjcetpth.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtbiaseyki.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtbpjlgxua.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ppjwa.cn/Article/details/gtnzmfsieo.html


<!-- 参考信息 -->