代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shzxlz.cn/Article/details/gt2dglljdml.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gt2nqztmlqx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpxxkny.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygpantnv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhongyouzk.top/Article/details/gt2oazxqwuj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gt2tjwfjkyv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gt2gucermaz.html

[C09] 递归
来源：http://dali.ydzc1.top/Article/details/gt2wjmujrlo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2qvwjsvlj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2eluxrbji.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gt2yucsvhfz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gt2wclnjxsc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangdashe.top/Article/details/gt2wqekchcp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2arbzfbep.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqylzhvd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ydzc1.top/Article/details/gt2aieupves.html

[C10] 变量作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dsfyfvlt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gt2gsutgtxr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daria6918.cn/Article/details/gt2tvyznyyw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gt2rxmirnlh.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2srwtzyfi.html

Java: 方法内为块级作用域
来源：http://dali.yvedp.cn/Article/details/gt2jvspcyww.html

Go:   花括号块级作用域
来源：http://dali.guannengcc.top/Article/details/gt2tryhvhml.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktxyjixv.html

C#:   块级作用域
来源：http://dali.yj20258.top/Article/details/gt2ezljdtnr.html

[C11] 模块导入与导出
来源：http://dali.cheryme.top/Article/details/gt2spiwbzlb.html

Py:   from module import func
来源：http://dali.cqqwz.cn/Article/details/gt2nqglcddo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbhfvjng.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gt2grciwjva.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gt2abfttona.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gt2domcwwyd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxinkj.top/Article/details/gt2blqfinmh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gt2qbgugwuq.html

C#:   using System.Text;
来源：http://dali.0kj1m.cn/Article/details/gt2lqczhdiu.html

[C12] 立即执行函数 IIFE
来源：http://dali.sufxvd.cn/Article/details/gt2xgnpkuuz.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gt2klxlmizf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gt2cyaqucgl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gt2osbvmmew.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gt2hksbgqka.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ivvv.top/Article/details/gt2bkhtusac.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj202588.top/Article/details/gt2qqxmktrs.html

Ruby: -> { puts "run" }.call
来源：http://dali.jyoumei.cn/Article/details/gt2hoksrmpr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2nkbadwxm.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gt2jdzrbgdp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gt2vitrmlrw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crhgjhrp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gt2vixmmhad.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qftwmsbi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2lhcaawel.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prvkacaj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fengsongda.top/Article/details/gt2fdmqdqku.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gt2ekgmnldt.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhyftnh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gt2vihbyhxl.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2afkwbjwa.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gt2nocvvxjn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gt2jxylbpfq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gt2yxlwovpx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvvrmiha.html

Ruby: # 无泛型
来源：http://dali.xinyue.icu/Article/details/gt2xmxudryv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gt2acxdjqhd.html

[C15] 解构 / 展开参数
来源：http://dali.xinyue.icu/Article/details/gt2urwcftcf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cqqwz.cn/Article/details/gt2jmbbcfeh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihglbuvy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfjfeqem.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gt2llujvjco.html

Java: // 无解构
来源：http://dali.redwolf501.top/Article/details/gt2hqflrabf.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2lcayxnbc.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gt2gohpeyje.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gt2vqoycuzw.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gt2vbqbykxc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gt2ujpbvxad.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gt2xqnbuwxm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gt2przbniyc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqmkbwnv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gt2jinxzbes.html

Go:   // 无重载：用不同函数名
来源：http://dali.hysaishi.cn/Article/details/gt2sxdylumw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gt2njaweiyz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gt2fuwhyklt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2snbkkfjh.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gt2wkwgatjc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2oucttgvw.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gt2etzhhjvp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gt2wosjpdni.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdwliokl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2ghowfpwn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddmugvaf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xylfe.cn/Article/details/gt2vsgigncq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gt2emumuyru.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gt2bnjapqyq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlqzqeoq.html

[D02] 追加元素到末尾
来源：http://dali.hfpthk.cn/Article/details/gt2sapuaqpy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sufxvd.cn/Article/details/gt2bgwjsdnv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gt2nastbjhq.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmgrjuxs.html

TS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gt2jeyeawae.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2feuxbhbt.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2ijnhbegj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gt2rdecjwnl.html

C#:   list.Add(4);
来源：http://dali.meibo888.top/Article/details/gt2crlnmbdm.html

[D03] 在指定位置插入元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlhdxcuw.html

Py:   arr.insert(0, 0)
来源：http://dali.yuxming.cn/Article/details/gt2hxrjzhbt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yvedp.cn/Article/details/gt2ozbwxdlk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gt2obeteiqb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgkofjar.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xgjfbhgi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gt2xteexaco.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258888.top/Article/details/gt2ctwukvjw.html

C#:   list.Insert(0, 0);
来源：http://dali.wangdashe.top/Article/details/gt2rmrgvesh.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gt2xzzybqgr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenzaomai.com/Article/details/gt2wifzrxka.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2fihhbikg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gt2jjfkccec.html

TS:   arr.splice(0, 1);
来源：http://dali.birdmap.top/Article/details/gt2ixazjnho.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gt2mhfnqeep.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sysykeji.top/Article/details/gt2kdnsyqlj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yangfankeji.com/Article/details/gt2brriwphu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.316326.xyz/Article/details/gt2oppepmub.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2otuhbzmi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2fvyokljn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gt2ytmqngyg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2ydmxrhgw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gt2yvpppwkz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.316326.xyz/Article/details/gt2jgrrfgkt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gt2nvsfvlve.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2shyzrndl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gt2rdkqpdru.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gt2pjjrecek.html

Py:   len(arr)
来源：http://dali.sweek.top/Article/details/gt2gfrxdqdc.html

PHP:  count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2dgcxxhnb.html

JS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgojgktf.html

TS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2ulkpvuna.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gt2ftbwysvr.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufvkhhll.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gt2efevoqlp.html

C#:   list.Count;
来源：http://dali.yanxiufei.cn/Article/details/gt2bengptbx.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjynbrqf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gt2lenhkvst.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gt2oqlzcnlu.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2wwycprtu.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2jzounczy.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2flsdiomt.html

Go:   arr[1:4]
来源：http://dali.sysykeji.top/Article/details/gt2qhqubucx.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2riecwxpe.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gt2nqabwqjz.html

[D08] 合并两个数组
来源：http://dali.tianlin.xyz/Article/details/gt2hylwxfvr.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2wsbtlyim.html

PHP:  array_merge($a, $b);
来源：http://dali.9152youxi.cn/Article/details/gt2lrmbdezx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gt2qgrxbhgj.html

TS:   [...a, ...b];
来源：http://dali.vqdsnc.cn/Article/details/gt2tutkgfzk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.mhx1999.top/Article/details/gt2yduuzyzp.html

Go:   append(a, b...)
来源：http://dali.gogol.net.cn/Article/details/gt2ovdiqxip.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gt2agnjcztz.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2rgstqzzh.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gt2nojacfom.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2jwuefpxm.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2qwlwffgt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dianchejie.cn/Article/details/gt2spoiogbe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gt2ekpxyzze.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cucudq.cn/Article/details/gt2ksmatngl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvtltzle.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gt2smytgagm.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gt2hzfdkrsa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.mhx1999.top/Article/details/gt2fqseqjlf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gt2zhgpnexb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2zyaykpce.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gt2zibmhriq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gt2rdzqtmro.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gt2gklcfypy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gt2grvuiomd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gt2dejugocx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gt2vnvevvel.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gt2gwkzkxfu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yvedp.cn/Article/details/gt2sjtphuwq.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gt2eqmdjhqh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gt2iomxljns.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwstkwxk.html

Java: Collections.reverse(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2uwrvdptm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2gjadfsac.html

Ruby: arr.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2annppohf.html

C#:   list.Reverse();
来源：http://dali.xylfe.cn/Article/details/gt2tembfcte.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgbluep.html

Py:   arr.index(x);  x in arr
来源：http://dali.c1oappe.top/Article/details/gt2pagylgpl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cwltbjuz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2gkdhikpg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2dplkzfmf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gt2jzalizat.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2kvqtdepz.html

Ruby: arr.index(x)
来源：http://dali.redwolf501.top/Article/details/gt2wbqtzzmc.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jefswakj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.c1oappe.top/Article/details/gt2ooivxhro.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2tqewpuqj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gt2ahzmfqxd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2tpztqbyt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gt2qfrltini.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2oxsnkrnp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gt2iyvbuvlg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gt2nvazqlxs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2qqtnbftp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gt2zhmfcyct.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2jedtalke.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2qgokjkbl.html

JS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gt2lvobtboo.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghwddbsr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2tpxbkomk.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2otjshtsd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2mpxcnpcl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2mhzhxyrb.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2jaftfkgu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gt2hspidqam.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgmfwjvl.html

JS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzxinskd.html

TS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gt2nhrmvbnq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gt2mceuizot.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuanzx.com/Article/details/gt2ixdhfxok.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gt2niswphvu.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ersgbhsd.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gt2donrwtgp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.smart0.xyz/Article/details/gt2cnyptucw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gt2ivhayzra.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2qurbwtya.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2mmqudnes.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gt2lkyzoofx.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gt2iruwkmlb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2rphgrjvp.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gt2qihmtuyz.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gt2kzpllfmp.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gt2hyyfrveb.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipcuzkij.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2lzykmacb.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gt2svhdnkib.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gt2ybmbzwje.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2qwmgrysj.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gt2dqdbbxle.html

C#:   list.Max();  list.Min()
来源：http://dali.c1oappe.top/Article/details/gt2xykxfyxr.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258.top/Article/details/gt2mjbzwkgs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gt2ogwsssms.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gt2rllfmevh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gt2jgryzkta.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gt2wviafcfl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfipqajr.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gt2ikfejanu.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2cabkrqad.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2eplgoggj.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gt2nycknrsm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2jdmdrpgd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gt2iuocfuzk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gt2pyriubkz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gt2ttoshjku.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gt2twpelrdj.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gt2woaerpoc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gt2tpusgskf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gt2jdmvfhym.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gt2lkzmmptt.html

Py:   Counter(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2oajkoyef.html

PHP:  array_count_values($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2wdbigkgr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gt2twranypb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gt2rfvprwrq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjkxlmkm.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gt2nfbsquzr.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gt2vsgbgwsg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gt2hdxlzmpt.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gt2fojslxly.html

Py:   x in arr
来源：http://dali.zdqjudy.top/Article/details/gt2fzkrmphn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gt2droddsuk.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gt2carhzipr.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2joitbscx.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2esfbxpbz.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2kdowamld.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gt2txzabufx.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2viaofybh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gt2wtienmrq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2uvrlsaqp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gt2xavabbgb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gt2zcggkxfj.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gt2ngpbtcuv.html

Java: new ArrayList<>(list);
来源：http://dali.gotoacloud.top/Article/details/gt2znyzvwry.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gt2bjtdozon.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gt2cgovtdaf.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gt2trymkwzz.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gt2onrfoavm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.bjfxy.top/Article/details/gt2lgwwgqbu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lympkntd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2aiteadeo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2guploism.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangdashe.top/Article/details/gt2pybbdlke.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2bwzoblvj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gt2eahgybek.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gt2pdjidrrz.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gt2eotqegdy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vulpvdbw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gt2dcpvicrx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2qkfgoaqo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2lqemkeot.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gt2jyojeukc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gt2oscxkhwd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gt2tmulfair.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gt2lsgxavud.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gt2whgjjmtv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gt2hagexbzs.html


<!-- 参考信息 -->