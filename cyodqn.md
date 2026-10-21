代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.zhiwuduotai.top/Article/details/gtbcljxbhv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258888.top/Article/details/gttultdiws.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gtfpkdykbe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gtptlvwuxl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dianchejie.cn/Article/details/gtiwblcqaz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtqxhrovah.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtoghhazpo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ivvv.top/Article/details/gtjvigboog.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gtcfmizsxf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gtmzflnrns.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpqhvorr.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gtkdlvvipl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtkjnffdgj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gthucaohbv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gtbamvndnq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtjzqfehjk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtlccbxpuq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xziqi.cn/Article/details/gtcoqpqitj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtmqjrxoxs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gtfdmbpoll.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gtngmzdpyz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cdnleiting.top/Article/details/gtehunijuu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gtqxhkdboz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gtrifnuafj.html

TS:   同 JS
来源：http://dali.yj202588.top/Article/details/gtgreucopw.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtptyxncls.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtsaskjplm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gtahhhuiwn.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gtsbldwcwt.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gtleewpham.html

Py:   from module import func
来源：http://dali.ivvv.top/Article/details/gtztbtzfjh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gtiwhuwpgk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtnonfgnpt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jiagoushi.top/Article/details/gtaxvretfj.html

Java: import java.util.List;
来源：http://dali.cashguo.top/Article/details/gtjehfslhj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gteiyunsfq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxinkj.top/Article/details/gtacvlyqun.html

C#:   using System.Text;
来源：http://dali.gogol.net.cn/Article/details/gttsdrfvcu.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gteufhapfk.html

Py:   (lambda: print("run"))()
来源：http://dali.haohaochexian.top/Article/details/gtlmbdgrsb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj202588.top/Article/details/gtrksyecjr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtnogbvljd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtbswhyxnr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gtsjgeekql.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gtfysyxfxi.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gthrhhqdgy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtjhhksxnf.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gtzbvfkhrc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pycfn.com/Article/details/gtowftznbs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gteatdfubi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhengqikj.top/Article/details/gtellqdfwq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtpspmffsm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtwgssdfkm.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtfbtwkgqe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gtwximgale.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pengpengdd.cyou/Article/details/gtoqkwszme.html

[C14] 泛型函数
来源：http://dali.zhoulong.xyz/Article/details/gtkshqmozy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gtnpbevpkn.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtefezhbsr.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtveyzfjam.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gtoulxrwgk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlolrwogj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gtudortwvd.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtyhcgvwxc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gtptrtafqv.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtaplxuatl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.9152youxi.cn/Article/details/gtecnbfill.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tanke756.top/Article/details/gttowjevie.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtbovjlpmb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ppjwa.cn/Article/details/gttsqhcygr.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gtyjpspqwk.html

Go:   // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtxxmsuieq.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gtgfksceov.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstujpveb.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gtppcwvzde.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigufen.top/Article/details/gthhmbofzu.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gtjjvubxbc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gtplzxjxpj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gtixuzsacr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gtgnpgwaor.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gtcwzlnyrx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gtwdlttfnw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gthngcskgr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtotocrjph.html

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gtvwijcbyq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtheeuylll.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gtkyhpqnbf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hongshengwenyu.top/Article/details/gtyelordjx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtipwprwzf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtudkcbdlv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.haohaochexian.top/Article/details/gtneuuxkzn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gtzbrrkiiu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gtmrdstexn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gtuaizgyyw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gtfgjxgajk.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gtasqqryvv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtyqusfhuo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gtkvltsqlb.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtzmsdrhto.html

TS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtyetmnmlm.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gtamxiocym.html

Go:   arr = append(arr, 4)
来源：http://dali.hammf.cn/Article/details/gtaqtzdznj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hfpthk.cn/Article/details/gtneivveky.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtukiulfsq.html

[D03] 在指定位置插入元素
来源：http://dali.cqqwz.cn/Article/details/gtcjcmvlkt.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gtwlfwvkfn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfnndxpx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hfpthk.cn/Article/details/gtbzllxhcb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gtmogteuyn.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaktzcbga.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gtbjzjhbxw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gtpyvitdei.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtvisoxrgl.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gtglfahuhn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtmergkhcu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngdctjtt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj202588.top/Article/details/gtsvezdkon.html

TS:   arr.splice(0, 1);
来源：http://dali.fengsongda.top/Article/details/gtmpqzngbr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gtjlgsnnvc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gtidsxtezo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gtkhogasyw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.svipenyu.cn/Article/details/gtoxvjyeqr.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gtpjjjbgau.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtugsysfqi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtodooosbe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthupzznbv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gtkvtrsngk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dianchejie.cn/Article/details/gteoujodwo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gttcenpajb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtsgmhczbz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtqiqexgrb.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtecwsriib.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtnnxvvtjt.html

PHP:  count($arr);
来源：http://dali.dianchejie.cn/Article/details/gtrgdskffo.html

JS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtcwluncjt.html

TS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtuszntczo.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtmcuvycuc.html

Go:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gticpqdtnl.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gtyebzkdts.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gtpxtirdym.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtsrngfssi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtismhrvnf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtghgvczfi.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtbyyugoys.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtbwubawms.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtmzikirsc.html

Go:   arr[1:4]
来源：http://dali.zhixingplan.top/Article/details/gtlyxkdeab.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtobzpabta.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtstilpwqs.html

[D08] 合并两个数组
来源：http://dali.kuanghao11.cn/Article/details/gtqgbombfl.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtwaxxbndk.html

PHP:  array_merge($a, $b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvukbjqa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sufxvd.cn/Article/details/gtifgpaevr.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gtdmsvpzpo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gtnrrvlagz.html

Go:   append(a, b...)
来源：http://dali.zycfv.cn/Article/details/gtfdcabntr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmjrtvzv.html

C#:   a.Concat(b).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmeylknn.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gtngrnimiy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtcwrhsyhv.html

PHP:  sort($arr);
来源：http://dali.fzhhl.top/Article/details/gtpbgupijy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gtutqizkas.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.c1oappe.top/Article/details/gtgnwohtgc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aibaodan.cn/Article/details/gtvubtjlke.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtipkbklgw.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtufidxbqa.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gtsubddfcz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdmzbxmy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gthreznthp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gthyrithdr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtrrivfyav.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtmomtpgmi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtfbipykzu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gtjdlypyws.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gtcxvkrtbr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gtwqicpchp.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtjyqsdpbr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gtbuxbxkty.html

PHP:  array_reverse($arr);
来源：http://dali.daria6918.cn/Article/details/gtcqpmllul.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtxcrnkvli.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gtxmfsiihl.html

Java: Collections.reverse(list);
来源：http://dali.hysaishi.cn/Article/details/gtupcvzhkt.html

Go:   slices.Reverse(arr)
来源：http://dali.wangdashe.top/Article/details/gtdsyambmd.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkxurktr.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxkuyqjm.html

[D12] 查找元素下标
来源：http://dali.yj20258888.top/Article/details/gtvbuxgmhi.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gtileiiokm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtogobmxlj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtnoxctzih.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtdsdnlnvn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gteoooqdof.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtgeamxote.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtvvrvvcmi.html

C#:   list.IndexOf(x);
来源：http://dali.316326.xyz/Article/details/gtnktzdtob.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gtpkdrlflh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shuidangran.top/Article/details/gtitwyejdz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtykcnbijk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtrydtybvm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtmabuxbea.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gtoprolnze.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gtxyekyeph.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gthheemusd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtjwnglpwl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.quarkkingdee.top/Article/details/gtbgqssxog.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.havefunace.top/Article/details/gtgrvajdvt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtknqdvoed.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gthowdxiqz.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtiqupocpg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtjwyjqvsx.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtuoemssnw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gtnzedbben.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcofeiyw.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gtuvbdcxxe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gtautpsrka.html

PHP:  array_unique($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtpleazftb.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtizudeibp.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtogptkpmj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.iojbl.cn/Article/details/gttnajvyns.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuetiantiany.cn/Article/details/gtnvidjkcd.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gtvbqijsem.html

C#:   list.Distinct().ToList()
来源：http://dali.hnqzz.top/Article/details/gteuaouhgo.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gtlvppvltl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gtbyasqrff.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gtzfclvqap.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtsofnahbe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gttlejcopi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gtbkjkqhyo.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gtijpvgmuf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gtrbgwrrdk.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gtololvqrp.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtazixexko.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtgjmmcsfi.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gtbqcoacpk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gtygcecxea.html

TS:   Math.max(...arr);
来源：http://dali.kuanghao11.cn/Article/details/gtpnyqpolf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gtqwiwkofn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuujbrhgo.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gthgrnwxuw.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gtoezsbosh.html

[D18] 扁平化嵌套数组
来源：http://dali.yongpay.top/Article/details/gtvlgsnbgb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhwcscqm.html

PHP:  array_merge(...$nested);
来源：http://dali.hammf.cn/Article/details/gtzzdkorzk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjevdchxb.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxnrfccz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtzbusewxq.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gtstfkkmgf.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gtmhdlkmmy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yonumen.top/Article/details/gtgemknahe.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gttqbqyemq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jyoumei.cn/Article/details/gtghztecsk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gtzhwhhtvg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.kuanghao11.cn/Article/details/gtrsbauzqv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtsdsjvbln.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gtkdhwmiqg.html

Go:   // 手写 map[string][]T
来源：http://dali.redwolf501.top/Article/details/gthaqquwpf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtswfqgmua.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gtmmmgftvd.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gtlsrxzbni.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gtqdlcujts.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtqdphdwhr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtzgnvaxaj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gthevxowbi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gtvapuipil.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtnouqhqeb.html

Ruby: arr.tally
来源：http://dali.shangyingyoupin.top/Article/details/gtzhzijwqh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gtatntkzeb.html

[D21] 判断是否包含某元素
来源：http://dali.316326.xyz/Article/details/gtszggqhjx.html

Py:   x in arr
来源：http://dali.hywenlv.cn/Article/details/gtbfhvywie.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmstiurgv.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtlkwyyndt.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtjgdrpwlo.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtjwhxoymy.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtkfzeqyrs.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gtyqqzhdlu.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtmttfgowt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gtmgnnsnww.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gtugaggbgl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gtuotcvvrl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtvlzubyup.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gtoqmvobww.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gticezabhp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gtncyktonx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aizwys.cn/Article/details/gtqrcotsjs.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtaeqvcerr.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtibejzcbj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gtcdbrjres.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gtmkgknunt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtdmjuvbna.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtxteycvql.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.smart0.xyz/Article/details/gtlesumkbg.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtcmqtpycv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.0kj1m.cn/Article/details/gtglzykllp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fengsongda.top/Article/details/gtequanmgj.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtrvpocigo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gtheczdtoh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gthvtiklwd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxectgkqw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtszqewvep.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gtowzsqtdp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gtxacvbfbq.html


<!-- 参考信息 -->